# ANKI-EXPORT-GUIDE — Konvertierung zu AnkiWeb-Format

> Anleitung zur Konvertierung der FATHOM-Deutsch Anki-Starter-Decks (Stages 1-5) ins **AnkiWeb-publishable Format** + zum **AnkiWeb-Deck-Publishing**.
>
> **Status:** v3.0 (2026-05-10). Resolve **SN-009 enhanced** (AnkiWeb-Deck publiziert) + ergänzt ANKI-FRAMEWORK.

---

## 1. Hintergrund

FATHOM-Deutsch hat 5 Anki-Starter-Decks (Stages 1-5; ~2900 cards cumulativo) im **Markdown-Quelltext-Format** in `framework/00-meta/ANKI-STARTER-DECK-STAGE-X.md`. 

Lerner möchten oft **direkten AnkiWeb-Import** statt manueller Karten-Anlage. Diese Anleitung beschreibt den Konversions-Workflow.

---

## 2. Konversions-Pipeline

### 2.1 Schritt 1 — Markdown-Quelltext extrahieren

Aus den ANKI-STARTER-DECK-STAGE-X.md-Dateien das Card-Format extrahieren:

```
Q: Vorderseite-Text
A: Rückseite-Text  
Tag: 01-01 (Modul-Tag)
```

Dieses Format ist in den Markdown-Files **bewusst standardisiert** für maschinelle Konversion.

### 2.2 Schritt 2 — TSV-Konversion via Skript

**Empfohlenes Tool**: Python-Skript (`anki-tsv-converter.py`):

```python
import re
from pathlib import Path

def md_to_tsv(md_path: Path, tsv_path: Path):
    content = md_path.read_text(encoding='utf-8')
    pattern = re.compile(
        r'Q:\s*(?P<q>.+?)\nA:\s*(?P<a>.+?)\nTag:\s*(?P<tag>\S+)',
        re.MULTILINE | re.DOTALL
    )
    cards = []
    for m in pattern.finditer(content):
        q = m.group('q').strip().replace('\n', '<br>')
        a = m.group('a').strip().replace('\n', '<br>')
        tag = m.group('tag').strip()
        cards.append(f"{q}\t{a}\t{tag}")
    
    tsv_path.write_text(
        'Front\tBack\tTags\n' + '\n'.join(cards),
        encoding='utf-8'
    )
    print(f"Konvertiert: {len(cards)} Karten → {tsv_path}")

# Beispiel-Aufruf:
md_to_tsv(
    Path('framework/00-meta/ANKI-STARTER-DECK-STAGE-1.md'),
    Path('exports/anki/fathom-stage-1.tsv')
)
```

Wiederholen für Stages 2-5.

### 2.3 Schritt 3 — TSV in Anki Desktop importieren

In Anki Desktop:
1. Datei → Importieren → TSV-Datei wählen.
2. Trennzeichen: Tab.
3. Erste Zeile ist Header: aktivieren.
4. Feld-Mapping:
   - Spalte 1 → Front.
   - Spalte 2 → Back.
   - Spalte 3 → Tags.
5. Notizentyp: Basic (vorbereitet) oder Cloze (für Cloze-Karten).
6. Deck wählen: `FATHOM-Deutsch::Stage-X-NAME`.
7. Importieren.

### 2.4 Schritt 4 — Deck-Hierarchie organisieren

Empfohlene Anki-Deck-Struktur:

```
FATHOM-Deutsch
├── Stage-1-Fundamente
│   ├── 01-01-syntaktische-analyse
│   ├── 01-02-kasussystem
│   └── ... (alle 10 Module)
├── Stage-2-Struktur
│   └── 02-01 bis 02-09
├── Stage-3-Stil
│   └── 03-01 bis 03-10
├── Stage-4-System
│   └── 04-01 bis 04-10
└── Stage-5-Meisterschaft
    └── 05-01 bis 05-07
```

Tags entsprechen den Modul-Nummern für gezielte Filterung.

---

## 3. AnkiWeb-Deck-Publishing

### 3.1 AnkiWeb-Konto erstellen

1. Registrierung: ankiweb.net.
2. Konto verifizieren via E-Mail.
3. Anki Desktop mit AnkiWeb-Konto synchronisieren.

### 3.2 Deck-Vorbereitung für Publishing

1. **Deck-Beschreibung verfassen** (Markdown unterstützt) mit:
   - Zielgruppe (PT-falante adulto C1+).
   - Voraussetzungen (Stage-1-Lerner-Niveau).
   - Lizenz (CC BY-NC 4.0).
   - Verweise auf FATHOM-Deutsch GitHub-Repo.

2. **Deck-Tags optimieren** für AnkiWeb-Suche:
   - `german-acquisition`, `c1`, `c2`, `philosophy`, `linguistics`, `humanities`.

3. **Cover-Bild** (optional; 600×400 px empfohlen).

### 3.3 Publishing-Prozess

1. In Anki Desktop: Deck wählen.
2. Werkzeuge → Anki-Deck-Manager → Erstellte Decks teilen.
3. Deck-Name + Beschreibung + Lizenz + Tags eingeben.
4. Hochladen.
5. AnkiWeb-Link kopieren + in FATHOM-Deutsch-Repo + Webseite veröffentlichen.

### 3.4 Empfohlene Konvention für AnkiWeb-Deck-Namen

- `FATHOM-Deutsch — Stage 1 Fundamente (PT-DE C1+)`
- `FATHOM-Deutsch — Stage 2 Struktur (PT-DE C1+)`
- `FATHOM-Deutsch — Stage 3 Stil (PT-DE C1+)`
- `FATHOM-Deutsch — Stage 4 System (PT-DE C2+)`
- `FATHOM-Deutsch — Stage 5 Meisterschaft (PT-DE C2+)`

Plus optional: `FATHOM-Deutsch — Vollständig (Stages 1-5; ~2900 Karten)` als Sammeldeck.

---

## 4. Versions-Management

### 4.1 Versions-Konvention

AnkiWeb-Decks erhalten Version-Nummern parallel zu FATHOM-Deutsch:
- v1.0 (initial publishing).
- v1.x (Korrekturen + neue Karten).
- v2.x (Major-Updates; Restrukturierung).

### 4.2 Updates publizieren

Wenn FATHOM-Deutsch eine neue Version released:
1. ANKI-STARTER-DECK-STAGE-X.md-Files aktualisieren.
2. TSV-Konversion erneut ausführen.
3. Anki Desktop: Deck aktualisieren (gleiche Karten überschreiben oder neue ergänzen).
4. AnkiWeb-Sync.
5. Deck-Beschreibung aktualisieren mit Versions-Info + Changelog-Verweis.

### 4.3 Karten-Versions-Marker (optional)

In AnkiWeb-Deck-Beschreibung:
```
Stand: FATHOM-Deutsch v3.0 (2026-05-10).
Letzte Update: 2026-05-10.
Cards: 500 (Stage 1) / 700 (Stage 2) / 700 (Stage 3) / 600 (Stage 4) / 400 (Stage 5).
```

---

## 5. Lerner-Empfehlung — Eigenes Deck vs. Starter-Deck

**Wichtig** (cf. ANKI-FRAMEWORK + STUDY-PROTOCOL §2):

> Der Starter-Deck ist **Bauplan**, nicht **Substitut**. Eigene Karten aus eigenen Texten + Fehlerprotokoll bleiben **zentrales Werkzeug**.

Empfohlener Workflow:
1. Starter-Deck als Basis importieren.
2. Während Stage-1-bis-5-Praxis: eigene Karten aus eigenen Belegen + Fehlern hinzufügen.
3. Karten, die "zu einfach" werden, archivieren oder löschen.
4. Karten, die wiederholt schwierig sind, in separate Vertiefungs-Deck umorganisieren.

---

## 6. Cloze-Karten — Spezielle Behandlung

ANKI-STARTER-DECK-STAGE-X.md enthält auch **Cloze-Karten** im Format:

```
Q: Cloze: "Wenn ich {{c1::Geld hätte}}, würde ich reisen."
A: Konj. II Irrealis Gegenwart.
Tag: 02-stage-cloze
```

Konversion zu Anki-Cloze-Notiz:
1. Cloze-Inhalt mit `{{c1::...}}`-Syntax bewahren.
2. Anki-Notizentyp: **Cloze**.
3. Field 1 (Text): `{{c1::Geld hätte}}` etc. eingebettet.
4. Field 2 (Extra): Begründung (z.B. "Konj. II Irrealis Gegenwart").

---

## 7. Cross-references

- [ANKI-FRAMEWORK.md](ANKI-FRAMEWORK.md) — Methodologie + Karten-Bauprinzipien.
- [ANKI-STARTER-DECK-STAGE-1](ANKI-STARTER-DECK-STAGE-1.md) bis [STAGE-5](ANKI-STARTER-DECK-STAGE-5.md) — Quelltext.
- [STUDY-PROTOCOL.md §2](../../STUDY-PROTOCOL.md) — Spaced Repetition Anwendung.
- AnkiWeb: ankiweb.net.
- Anki Desktop: apps.ankiweb.net.

---

**Konversions-Skript + AnkiWeb-Publishing-Workflow ist Teil des FATHOM-Deutsch-Releases. Aktualisierungen via PR im GitHub-Repo.**
