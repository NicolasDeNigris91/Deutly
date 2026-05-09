# Begriffsanalyse-Template — korpusbasierte Begriffsanalyse

> Template para [CAPSTONE-4 — Erkenntnisprojekt v3](../../04-system/CAPSTONE-system.md). Korpusbasierte Begriffsanalyse, ~25-40 Seiten, mit DWDS / COSMAS-II-Daten + diachroner + synchroner Achse.
>
> **Niveau-Erwartung:** Stage-4 / C1+. Methodisch rigoros — Begriffsgeschichte (Brunner / Conze / Koselleck) + Korpuslinguistik (DWDS, COSMAS II) + Hermeneutik (Gadamer) integriert.
>
> **Bewertungskriterien:** cf. [RUBRIC.md](../RUBRIC.md) §5 (Begriffsanalyse-Bewertung).

---

## Frontmatter

```yaml
---
typ: korpusbasierte-begriffsanalyse
stage: 04
capstone: CAPSTONE-4
begriff: [Aufklärung | Bildung | Geist | Wahrheit | Macht | Sein | Sprache]
titel: "[Titel — z.B. 'Aufklärung 1750-2025: Begriffsverschiebung im DWDS-Korpus']"
verfasser: [Name]
datum: YYYY-MM-DD
seitenzahl: [25-40 typisch]
zeit-investiert: [Stunden — typisch 200-500 h]
korpus-primaer: [DWDS-Kernkorpus | COSMAS-II-Archive | beide]
zeitschnitt: [z.B. 1750-2025 in 50-Jahre-Schnitten]
beleg-anzahl: [empfohlen ≥ 30 Belege]
methode: [Begriffsgeschichte + Kollokationsanalyse + Frequenzverlauf + hermeneutische Lesart]
---
```

---

## Strukturschema

```
0. Abstract (DE)                      ~250 W   (1 Seite)
1. Einleitung                         ~1500 W  (3-4 Seiten)
2. Forschungsstand                    ~2000 W  (4-5 Seiten)
3. Methodologie + Korpus              ~1500 W  (3-4 Seiten)
4. Diachrone Achse — Frequenzverlauf  ~2000 W  (4-5 Seiten + Diagramme)
5. Synchrone Achse — Kollokationen    ~2000 W  (4-5 Seiten + Tabellen)
6. Hermeneutische Tiefenanalyse       ~3000 W  (6-8 Seiten)
   6.1 Beleg-Cluster I (Aufklärung 1)  
   6.2 Beleg-Cluster II (Aufklärung 2) 
   6.3 Beleg-Cluster III (Aufklärung 3)
7. Diskussion + Methodenkritik         ~1500 W  (3 Seiten)
8. Schluss + Forschungsdesiderate      ~500 W   (1 Seite)
9. Anhang — Beleg-Sammlung            (separat, ~30+ Belege)
10. Literaturverzeichnis              (separat, ≥ 8 Primär + ≥ 8 Sekundär)
─────────────────────────────────────────────
Total Haupttext:                      ~14250 W (28-32 Seiten Standardlayout)
```

---

## 0. Abstract (~250 W)

```markdown
## Abstract

[Frage — 1-2 Sätze.]
[Korpus + Methode — 1-2 Sätze.]
[Hauptergebnis (frequenz + kollokational + hermeneutisch) — 4-5 Sätze.]
[Beitrag zur Begriffsgeschichte — 1 Satz.]

**Schlüsselbegriffe:** [Begriff], [verwandte Begriffe], 
DWDS, COSMAS-II, Begriffsgeschichte, Kollokationsanalyse, Frequenzverlauf.
```

---

## 1. Einleitung (~1500 W)

### Strukturelle Bausteine

```markdown
## 1. Einleitung

### 1.1 Phänomen
[Konkretes Phänomen, das den Begriff aktualisiert. Eine zeitgeschichtliche 
Beobachtung. ~300 W.]

### 1.2 Theoretischer Rahmen — Begriffsgeschichte
[Kurze Verortung: Begriffsgeschichte als Methode (Brunner, Conze, Koselleck 
in *Geschichtliche Grundbegriffe*; Pocock-Cambridge-School). Was erlaubt 
diese Methode, was nicht? ~400 W.]

### 1.3 Forschungsfrage
[Spezifische Frage. Z.B.: "Wie hat sich der Begriff 'Aufklärung' im 
deutschen Schriftkorpus zwischen 1750 und 2025 verschoben — semantisch, 
distributionell, ideologisch?" ~200 W.]

### 1.4 These (vorläufig)
[Vorab-Hypothese, die durch die Korpusanalyse getestet wird. 
Konjunktiv II hedge. ~200 W.]

### 1.5 Aufbau
[Vorausschau auf Kapitel 2-8. ~400 W.]
```

---

## 2. Forschungsstand (~2000 W)

### Strukturelle Bausteine

```markdown
## 2. Forschungsstand

### 2.1 Begriffsgeschichte als Tradition
[Brunner / Conze / Koselleck — *Geschichtliche Grundbegriffe* (1972-97). 
Methodische Grundlagen. ~500 W.]

### 2.2 Spezifische Forschung zum Begriff
[Z.B. für 'Aufklärung': Brandt 2003 in HWPh, Bd. 12; Geier 2012; 
Schneiders 1989. Kritisch positionieren. ~700 W.]

### 2.3 Korpuslinguistische Vorarbeiten
[Welche Korpus-Studien existieren bereits zum Begriff? DWDS-Trends, 
Wortprofil-Analysen, Konkordanz-Studien. ~500 W.]

### 2.4 Forschungslücke
[Was bisher fehlt — die Lücke, die diese Begriffsanalyse füllt. ~300 W.]
```

---

## 3. Methodologie + Korpus (~1500 W)

### Strukturelle Bausteine

```markdown
## 3. Methodologie und Korpus

### 3.1 Korpus-Auswahl
[Welcher Korpus, warum?
- DWDS-Kernkorpus 21 (1900-2000): Standard-Schriftsprache.
- DWDS-Zeitungskorpus (Tagesspiegel 1996-, Berliner Zeitung, ZEIT 1946-): 
  Pressediskurs.
- DWDS-Korpus historische Texte (1500-1900): diachrone Tiefe.
- COSMAS-II-Archive: speziell für Bundestags-Plenarprotokolle, 
  juristische / wissenschaftliche Texte.
~600 W.]

### 3.2 Zeitliche Eingrenzung
[Welcher Zeitschnitt? z.B. 1750-2025 in 50-Jahre-Intervallen 
(1750-1800; 1800-1850; ...; 2000-2025). Begründung. ~300 W.]

### 3.3 Operationalisierung
[Wie wird der Begriff in Korpus operationalisiert?
- Lemma-Suche: *Aufklärung*.
- Wortfamilie-Suche: *aufklären, Aufklärer, Aufklärerin, aufgeklärt, 
  aufklärerisch, Aufklärungsbewegung*.
- Komposita: *Aufklärungsbedürftig, Aufklärungsarbeit, Aufklärungsversuch*.
- Filter: Ausschluss falscher Treffer (z.B. 'Aufklärung' im militärischen 
  Sinn = Reconnaissance).
~400 W.]

### 3.4 Methodische Trias
1. **Diachron**: Frequenzverlauf der Lemmata über Zeit.
2. **Synchron**: Kollokationen pro Periode (DWDS-Wortprofil; LogDice / MI / t-Score).
3. **Hermeneutisch**: Tiefenanalyse von 30+ ausgewählten Belegen aus 
   verschiedenen Perioden / Genres.

[Methodenkritik: was diese Trias NICHT leisten kann (z.B. außerschriftliche 
Diskurse, mündliche Verwendung). ~200 W.]
```

---

## 4. Diachrone Achse — Frequenzverlauf (~2000 W + Diagramme)

### Strukturelle Bausteine

```markdown
## 4. Diachrone Achse

### 4.1 Frequenzverlauf des Lemmas
[DWDS-Wortverlaufskurve einbetten als Diagramm.

📊 [Diagramm: Frequenz pro Mio. Tokens, 1750-2025]

Beobachtungen quantitativ:
- Welche Spitzen? (z.B. 1780-1790 = Kant-Phase; 1944 = Adorno-Horkheimer; 
  1981 = Habermas-Modernity; 2001 = Friedenspreis Habermas)
- Welche Täler?
- Trendlinie: insgesamt Anstieg / Stagnation / Abnahme?
~700 W.]

### 4.2 Frequenzverlauf der Wortfamilie
[Vergleich der Lemmata: 'Aufklärung' (Substantiv) vs. 'aufklären' (Verb) 
vs. 'aufgeklärt' (Adjektiv-Partizip). 
Welche Form dominiert wann? Was sagt das über Begriff-Verwendung?
~600 W.]

### 4.3 Genre-Differenzierung
[Frequenz pro Genre: Belletristik / Wissenschaft / Zeitung / Recht. 
Wann ist 'Aufklärung' ein wissenschaftlicher Begriff, wann ein 
politischer Slogan?
~700 W.]
```

---

## 5. Synchrone Achse — Kollokationen (~2000 W + Tabellen)

### Strukturelle Bausteine

```markdown
## 5. Synchrone Achse — Kollokationsprofil

### 5.1 Top-20-Kollokationen pro Periode

📊 [Tabelle: Top-20-Kollokationen 1750-1800 / 1800-1850 / ... / 2000-2025
mit LogDice-Score]

| Position | 1750-1800 | 1850-1900 | 1950-2000 | 2000-2025 |
|----------|-----------|-----------|-----------|-----------|
| 1 | Vernunft | Bildung | Aufklärung_Sex | Verschwörung |
| 2 | Mündigkeit | Volk | Sexualkunde | Halbwahrheiten |
| 3 | ... | ... | ... | ... |

[700 W: Analyse der Trends.]

### 5.2 Bedeutungswandel via Kollokationen
[Welche Kollokationen verschwinden? Welche entstehen neu? Was sagt das 
über semantische Verschiebung? ~700 W.]

### 5.3 Plurizentrische Differenz (DE/AT/CH)
[Falls Korpus dies erlaubt: Differenz Bundesdeutsch vs. Österreichisches 
vs. Schweizerisches. ~600 W.]
```

---

## 6. Hermeneutische Tiefenanalyse (~3000 W)

### Strukturelle Bausteine

```markdown
## 6. Hermeneutische Tiefenanalyse — drei Beleg-Cluster

### 6.1 Beleg-Cluster I: 'Aufklärung' als Ausgang aus Unmündigkeit (1780-1810)

**Belege (Auswahl von 10):**

> Beleg 1: Kant 1784 (KrV-Nähe)
> "Aufklärung ist der Ausgang des Menschen aus seiner selbstverschuldeten Unmündigkeit."
> (Kant 1784, AA VIII, S. 35)

[Sprachliche Analyse: 
- Topologische Position des Subjekts ('Aufklärung').
- FVG 'der Ausgang des Menschen' — nominaler Stil.
- 'selbstverschuldet' — reflexive Schuldzuschreibung.]

[Hermeneutische Analyse: Was wird hier geleistet? Welche Lesart? 
~300 W pro Beleg-Cluster.]

> Beleg 2: Mendelssohn 1784, *Über die Frage: Was heißt Aufklären?*
> [...]

[~5-10 Belege pro Cluster, mit Analyse.]

[Synthese des Clusters: Was charakterisiert diese Phase semantisch? 
~300 W.]

### 6.2 Beleg-Cluster II: 'Aufklärung' als ambivalente Bewegung (1944-1947)
[Adorno/Horkheimer, *Dialektik der Aufklärung*; Heidegger; Bloch.]

### 6.3 Beleg-Cluster III: 'Aufklärung' als unabgeschlossenes Projekt vs. Ende (1981-2001)
[Habermas vs. Foucault vs. Lyotard.]

### 6.4 Synthese aller Cluster
[~500 W: Was hat sich verschoben? Was ist konstant geblieben?]
```

---

## 7. Diskussion + Methodenkritik (~1500 W)

### Strukturelle Bausteine

```markdown
## 7. Diskussion und Methodenkritik

### 7.1 Befund-Synthese
[Ergebnis der drei methodischen Achsen zusammenführen. ~500 W.]

### 7.2 Theoretische Konsequenzen
[Was bedeuten die Befunde für die Begriffsgeschichte? Bestätigen / 
verändern sie die These der Einleitung? ~500 W.]

### 7.3 Methodenkritik
[Was die Korpusanalyse NICHT zeigen kann:
- Mündliche Verwendung.
- Diskursrelevanz außerhalb von Schriftkorpora.
- Implizite Verwendung (wo das Wort nicht fällt, aber der Begriff aktiv ist).
- Plurizentrische Asymmetrien jenseits von DWDS/COSMAS-II-Korpora.

Selbstkritisch + ehrlich. ~500 W.]
```

---

## 8. Schluss + Forschungsdesiderate (~500 W)

```markdown
## 8. Schluss

### 8.1 Synthese
[~150 W: Hauptbefund in 2-3 Sätzen.]

### 8.2 Forschungsdesiderate
[Was sind die nächsten Forschungsschritte, die diese Analyse 
nahelegt? ~250 W.]

### 8.3 Schlussbild
[Konkretes Schlussbild oder konkrete offene Frage. ~100 W.]
```

---

## 9. Anhang — Beleg-Sammlung (separate Datei oder Anhang)

```markdown
# Anhang — Beleg-Sammlung

## Beleg 1
- **Quelle:** Kant, Immanuel (1784), AA VIII, S. 35.
- **Periode:** 1780-1800
- **Genre:** Wissenschaft (Aufklärungs-philosophie)
- **Beleg-Text:** "[Wörtlich, ggf. längerer Kontext-Auszug]"
- **Sprachliche Notiz:** [topologische Analyse + FVG + Modal + ...]
- **Hermeneutische Notiz:** [Funktion des Belegs für die These]

## Beleg 2
[...]

[≥ 30 Belege, kategorisiert nach Cluster.]
```

---

## 10. Literaturverzeichnis

### Mindestanforderungen
- **≥ 8 Primärquellen** in Akademie-Ausgaben oder kanonischen Editionen.
- **≥ 8 Sekundärquellen** (mind. 3 aus Begriffsgeschichte; mind. 2 aus Korpuslinguistik).
- **Korpora + Tools** als separate Sektion.

```markdown
## Literaturverzeichnis

### Primärquellen

[Chronologisch oder alphabetisch.]

### Sekundärliteratur (Begriffsgeschichte)

- Brunner, Otto / Conze, Werner / Koselleck, Reinhart (Hgg.) (1972-97): 
  *Geschichtliche Grundbegriffe — Historisches Lexikon zur 
  politisch-sozialen Sprache in Deutschland.* 8 Bde. Stuttgart: Klett-Cotta.

- Koselleck, Reinhart (1979): *Vergangene Zukunft — Zur Semantik 
  geschichtlicher Zeiten.* Frankfurt am Main: Suhrkamp.

[etc.]

### Sekundärliteratur (Korpuslinguistik)

- Bubenhofer, Noah (2009): *Sprachgebrauchsmuster — Korpuslinguistik 
  als Methode der Diskurs- und Kulturanalyse.* Berlin: de Gruyter.

- Lemnitzer, Lothar / Zinsmeister, Heike (2010): 
  *Korpuslinguistik — Eine Einführung.* Tübingen: Narr.

[etc.]

### Korpora und Werkzeuge

- DWDS — *Digitales Wörterbuch der deutschen Sprache.* 
  Berlin-Brandenburgische Akademie der Wissenschaften. 
  https://www.dwds.de/

- DWDS-Wortprofil — Kollokationsanalyse-Tool. 
  https://www.dwds.de/d/wortprofile

- DWDS-Zeitverlauf — Wortverlaufskurven-Tool. 
  https://www.dwds.de/d/wortverlauf

- COSMAS II — *Corpus Search, Management and Analysis System.* 
  IDS Mannheim. 
  https://cosmas2.ids-mannheim.de/

- Pfeifer, Wolfgang et al.: *Etymologisches Wörterbuch des Deutschen.* 
  Online-Version (DWDS-eingebettet).
```

---

## Korrekturschleife (Loop für Stage-4-Output)

**v1 (~3-4 Monate Schreibzeit):** Erste vollständige Fassung. Lücken erlaubt.

**v2 (~1 Monat Eigenüberarbeitung):** Camadas C1-C4 (cf. MENTOR.md §1) + spezifische Camada C5: **methodische Konsistenz** (Korpus → Befund → These verträglich).

**v3 (~1 Monat externe Korrektur):** Mentor (idealerweise Germanist mit Korpus-Erfahrung).

Optional **v4** wenn substantielle methodische Schwächen.

---

## Bewertung — RUBRIC.md §5

```
Konzeptuelle Tiefe:                ~/15%
Methodische Rigorosität:           ~/20%
Korpus-Nutzung:                    ~/15%
Hermeneutische Tiefenanalyse:      ~/15%
Stilistische Reife (C1+):          ~/10%
Quellennutzung:                    ~/10%
Sprachliche Korrektheit:           ~/5%
Originalität:                      ~/10%
─────────────────────────────────────────
Gesamt:                            ~/100%

Pass: ≥ 80%; mit externe Korrektur ≥ 85%.
```

---

## Anti-Patterns

- **Korpus als Schmuck.** Korpus muss These tragen, nicht dekorieren.
- **Kein hermeneutischer Tief.** Frequenz + Kollokationen ohne hermeneutische Lesart = Datendump.
- **Methode ohne Reflexion.** Methodenkritik ist Pflicht, nicht Option.
- **Begriffsgeschichte als Listenwerk** statt als Argument.
- **Synchroner und diachroner Schnitt** ohne Verbindung — beide brauchen einen gemeinsamen Befund.
- **Belege ohne Kontext.** Jeder Beleg braucht 1-2 Sätze Vorgängertext für hermeneutische Verständlichkeit.

---

## Cross-references

- [CAPSTONE-4 — Erkenntnisprojekt v3](../../04-system/CAPSTONE-system.md) — kontextuelle Aufgabe.
- [04-01 Historische Linguistik](../../04-system/04-01-historische-linguistik.md) — diachrone Grundlage.
- [04-02 Etymologie](../../04-system/04-02-etymologie.md) — Pfeifer als Quelle.
- [04-08 Korpuslinguistik](../../04-system/04-08-korpuslinguistik.md) — Hauptmethode.
- [04-10 Hermeneutik](../../04-system/04-10-hermeneutik.md) — Tiefenanalyse-Methode.
- [BEGRIFF-INDEX.md](../BEGRIFF-INDEX.md) — Quellen pro Begriff.
- [REFERENCES-ELITE.md](../REFERENCES-ELITE.md) — kanonische Sekundärliteratur.
- [RUBRIC.md](../RUBRIC.md) §5.
- [Aufsatz-5000W-Template](AUFSATZ-5000W-TEMPLATE.md) — Vorgängerstufe (ohne Korpus).

---

**Begriffsanalyse korpusbasiert ist die methodische Schwelle des FATHOM-Deutsch — sichtbar wird, ob Wissenschaftsdeutsch + Korpusmethode + Hermeneutik integriert sind oder ob sie noch nebeneinander stehen.**
