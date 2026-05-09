# Aufsatz-Template — wissenschaftlicher Aufsatz, 5000 Wörter

> Template para [CAPSTONE-3 — Erkenntnisprojekt v2](../../03-stil/CAPSTONE-stil.md). Wissenschaftlicher Aufsatz, ~5000 Wörter, mit Primärquellen + Literaturverzeichnis.
>
> **Niveau-Erwartung:** C1 sólido encaminhando a C2. Wissenschaftsdeutsch hoch — Adornoesque-Habermasian. Konjunktiv I + Konjunktiv II + Passivkonstruktionen + FVG + Stilfiguren + Modalpartikel + nominaler Stil integrados ohne Stilbruch.
>
> **Bewertungskriterien:** cf. [RUBRIC.md](../RUBRIC.md) §4 (Aufsatz-akademisch-Bewertung).

---

## Frontmatter

```yaml
---
typ: wissenschaftlicher-aufsatz
stage: 03
capstone: CAPSTONE-3
begriff: [Aufklärung | Bildung | Geist | Wahrheit | Macht | Sein | Sprache]
titel: "[Titel — Format z.B. 'Begriffsverschiebung von X bei Autor Y zwischen Z1 und Z2']"
untertitel: "[optional — präzisiert Methode oder Korpus]"
verfasser: [Name]
datum: YYYY-MM-DD
wortzahl: [exakt]
zeit-investiert: [Stunden — typisch 100-300 h]
korrektur-runde: [v1 | v2 | v3]
quellen-primaer: [N. ≥ 5]
quellen-sekundaer: [N. ≥ 5]
zitate-woertlich: [N. ≥ 8]
verwendete-methoden: [Begriffsgeschichte | hermeneutisch | diskursanalytisch | textlinguistisch | mehrere]
---
```

---

## Strukturschema (Wissenschaftlicher Standard)

```
0. Abstract (DE)            ~150 W   (3%)
1. Einleitung               ~500 W   (10%)
2. Forschungsstand          ~800 W   (16%)
3. Methodologie              ~400 W   (8%)
4. Hauptteil — Analyse      ~2500 W  (50%)
   4.1 Erster Aspekt         ~800 W
   4.2 Zweiter Aspekt        ~900 W
   4.3 Dritter Aspekt        ~800 W
5. Diskussion + Gegenargument ~500 W  (10%)
6. Schluss + Aussicht         ~150 W  (3%)
─────────────────────────────────
Total:                      ~5000 W

(+ Literaturverzeichnis, ohne Wortzahl-Anrechnung)
```

Toleranz: ±5% Gesamt (4750-5250 W).

---

## 0. Abstract — Zusammenfassung (~150 W)

### Funktion
**Eigenständiger** Mini-Aufsatz. Kann separat zitiert werden. Vor Lektüre des Hauptteils muss ein Leser entscheiden können, ob der Aufsatz für ihn relevant ist.

### Format

```markdown
## Abstract

[Frage / Problem — 1-2 Sätze.]

[Methode / Korpus — 1 Satz.]

[Hauptergebnis — 2-3 Sätze. Indikativ; keine Hedge-Modalverben.]

[Konsequenz / Beitrag — 1 Satz.]

**Schlüsselbegriffe:** [Begriff], [verwandte Begriffe], [Methode], [Autor/Korpus].
```

---

## 1. Einleitung (~500 W)

### Funktion
Vier Teile: (1) Hinführung; (2) Forschungslücke; (3) These; (4) Vorschau auf den Aufbau.

```markdown
## 1. Einleitung

### 1.1 Hinführung
[Konkrete Beobachtung, Phänomen, kontroverses Zitat. ~100 W. 
Keine Allgemeinplätze.]

### 1.2 Forschungslücke
[Was die bestehende Literatur (zumindest die wichtige) zum Thema sagt 
— in indirekter Rede mit Konjunktiv I. Was fehlt? ~200 W.]

### 1.3 These
[Zentrale These, in 2-3 Sätzen. Direkt. Verteidigbar. 
Möglichst nicht-trivial. ~75 W.]

### 1.4 Aufbau
[Knappe Vorausschau: Kapitel 2 stellt den Forschungsstand dar... 
Kapitel 3 erläutert die methodische Vorgehensweise... ~125 W.]
```

---

## 2. Forschungsstand (~800 W)

### Funktion
Verortung in der Disziplin. Nicht **alle** Literatur referieren — die **relevante** Literatur kritisch positionieren.

### Strukturelle Bausteine

```markdown
## 2. Forschungsstand

### 2.1 [Erste Tradition / Schule]
[Z.B. "Begriffsgeschichte nach Koselleck" oder "Habermas-Tradition" 
oder "kritisch-dialektische Linie". 
Drei zentrale Positionen kritisch zusammenfassen, mit Konjunktiv I 
in indirekter Rede. 200-300 W.]

### 2.2 [Zweite Tradition / Schule]
[Komplementär oder konkurrierend. 200-300 W.]

### 2.3 Forschungslücke (Eingrenzung)
[Was die genannten Positionen NICHT erklären / NICHT untersucht haben. 
Hier wird die These des Aufsatzes positioniert. 100-200 W.]
```

### Stilistische Erwartungen
- **Konjunktiv I in indirekter Rede:** verpflichtend.
- **Distanzmarkierung:** *Habermas vertritt die Position, dass...*; *Aus Adornos Perspektive ließe sich einwenden...*
- **Mind. 5 zitierte Quellen** in diesem Kapitel, mit Akademie-Ausgaben oder kanonischen Editionen.

---

## 3. Methodologie (~400 W)

### Funktion
Methode explizit machen + verteidigen.

### Strukturelle Bausteine

```markdown
## 3. Methodologie

### 3.1 Methodische Wahl
[Welche Methode wird angewendet? Begriffsgeschichte (Koselleck)? 
Hermeneutisch (Gadamer)? Diskursanalytisch (Foucault)? 
Textlinguistisch (Brinker)? Korpusbasiert (DWDS)? Mischung?]

### 3.2 Korpus / Quellen
[Konkrete Liste: welche Texte werden analysiert, welche Edition, 
welche Auswahl, warum diese.]

### 3.3 Begrenzung
[Was diese Methode NICHT leisten kann. Selbstkritisch.]
```

---

## 4. Hauptteil — Analyse (~2500 W, das Herz)

### Funktion
Drei Aspekte des Begriffs / Phänomens systematisch analysieren. Belege + Analyse + Verbindungen.

### Strukturelle Bausteine

```markdown
## 4. Hauptteil

### 4.1 [Erster Aspekt — z.B. semantisches Spektrum]
[Topiksatz.]

[Beleg 1 — wörtliches Zitat aus Primärquelle.]
> [Wörtliches Zitat]
> (Autor Jahr: Seite)

[Analyse — was zeigt der Beleg, in welchem Verhältnis steht er zur These?
~100-150 W.]

[Beleg 2 — Kontrast oder Verstärkung.]

[Analyse + Brücke. ~100-150 W.]

[Synthese des Aspekts — 2-3 Sätze.]

### 4.2 [Zweiter Aspekt — z.B. historische Verschiebung]
[Analog. Längeres Kapitel, da Hauptbeitrag des Aufsatzes.]

### 4.3 [Dritter Aspekt — z.B. heutige Anwendung / Spannung]
[Analog. Kann auch konkrete moderne Quelle einbeziehen.]
```

### Stilistische Erwartungen (Wissenschaftsdeutsch hoch)

- **Nominaler Stil** dominant (cf. 03-01): *die Verschiebung des Begriffs* statt *dass der Begriff sich verschoben hat*. Aber **nicht ausschließlich** — verbaler Stil für Bewegung, Argumentation.
- **FVG idiomatisch:** *zur Sprache bringen, in Erwägung ziehen, in den Blick nehmen, zur Diskussion stellen, Stellung beziehen, Position beziehen, in Frage stellen*.
- **Konjunktiv I** für indirekte Rede; **Konjunktiv II** für Hedge / Hypothese.
- **Passiv** wo objektive Distanz angemessen: *Diese Lesart ist von X kritisiert worden* (werden-Pass.) bzw. *Diese These ist erschöpft* (sein-Pass.).
- **Modalverben epistemisch** in Hedge: *dürfte, könnte, müsste, mag*.
- **Modalpartikel** strategisch: *freilich, indessen, mithin, allerdings, gleichwohl*. Vermeiden umgangssprachliche (*halt, eben, mal*).
- **Stilfiguren gehoben** sparsam: Chiasmus, Antithese, gelegentliche Hyperbaton.
- **Konnektoren** akademische: *demzufolge, mithin, gleichwohl, indes, insofern, sofern, sodass*.

---

## 5. Diskussion + Gegenargument (~500 W)

### Funktion
**Selbst-Kritik** + Verteidigung gegenüber dem stärksten Einwand. 
Ohne diesen Teil ist der Aufsatz keine Wissenschaft, sondern Bekenntnis.

```markdown
## 5. Diskussion

### 5.1 Möglicher Einwand
[Stärkster Einwand fair dargestellt — Konjunktiv I oder direkte Rede 
des hypothetischen Kritikers.]

### 5.2 Antwort
[Drei mögliche Strategien:
  (a) Akzeptieren mit Differenzierung;
  (b) Zurückweisen mit Argument;
  (c) Verträglich-Machen via Begriffsdifferenzierung.]

### 5.3 Grenzen der eigenen Position
[Ehrliche Selbstbegrenzung: was kann der Aufsatz NICHT leisten? 
Welche weitergehenden Fragen bleiben offen?]
```

---

## 6. Schluss + Aussicht (~150 W)

### Funktion
**Synthese**. **Nicht** Wiederholung, **nicht** "wie ich gezeigt habe".

```markdown
## 6. Schluss

[Synthese der These nach der Analyse — 2-3 Sätze. Hat sich die These 
durch die Analyse präzisiert oder verändert? Wie?]

[Aussicht — welche Forschungsfrage liegt nun offen, die der Aufsatz 
nicht beantworten konnte? 1-2 Sätze.]

[Schlusssatz — konkret, nicht pathetisch.]
```

---

## Literaturverzeichnis (am Ende, ohne Wortzahl-Anrechnung)

### Format

```markdown
## Literaturverzeichnis

### Primärquellen

- Kant, Immanuel (1784): *Beantwortung der Frage: Was ist Aufklärung?* 
  In: *Berlinische Monatsschrift* IV, S. 481-494. — Akademie-Ausgabe 
  Bd. VIII, S. 33-42. Nachdruck: Reclam UB 9714, Stuttgart 2010.

- Kant, Immanuel (1781/1787): *Kritik der reinen Vernunft*. 
  Akademie-Ausgabe Bd. III (B-Auflage). 

[etc., chronologisch oder alphabetisch nach Autor.]

### Sekundärliteratur

- Brandt, Reinhard (2003): *Aufklärung*. In: Historisches Wörterbuch 
  der Philosophie, hrsg. v. Joachim Ritter et al., Bd. 12, 
  Basel: Schwabe, Sp. 1242-1268.

- Habermas, Jürgen (1981): *Theorie des kommunikativen Handelns*. 
  2 Bde. Frankfurt am Main: Suhrkamp.

[etc.]

### Korpora / Online-Ressourcen (optional)

- DWDS — *Digitales Wörterbuch der deutschen Sprache*. Berlin-Brandenburgische 
  Akademie der Wissenschaften. https://www.dwds.de/

- COSMAS II — *Corpus Search, Management and Analysis System*. 
  Institut für Deutsche Sprache, Mannheim. https://cosmas2.ids-mannheim.de/

- IDS-Grammis — Grammatisches Informationssystem. 
  https://grammis.ids-mannheim.de/
```

### Mindestanforderungen für CAPSTONE-3

- **≥ 5 Primärquellen** in Akademie-Ausgaben oder kanonischen Editionen.
- **≥ 5 Sekundärquellen** (mind. 2 davon aus historischer Wörterbuch- oder Begriffsgeschichte-Tradition).
- **≥ 8 wörtliche Zitate** im Aufsatz, alle korrekt belegt.

---

## Korrekturschleife (Loop de Refinamento, intensiviert)

Stage-3-Aufsatz duldet keine v1-direkt-publizierte Fassung. Mindestens **3 Korrekturrunden**.

**v1 (~14 Tage Schreibzeit):** Erster Entwurf, vollständig. Erlauben Lücken; markieren mit `[?]`.

**v2 (~7 Tage Eigenüberarbeitung):** 4 Camadas (cf. MENTOR.md §1):
- C1 Grammatik (Kasus, Verbstellung, Konjunktiv-Konsekutivität).
- C2 Lexik (Wortwahl, Wissenschaftsregister, Anglizismen vermeiden).
- C3 Stil (nominaler/verbaler Balance, Modalpartikeln, Wiederholungen).
- C4 Native erudite (was würde Habermas / Luhmann / Adorno anders schreiben?).

**v3 (~7 Tage):** Externe Korrektur — Mentor / Peer / Tandempartner. Iterieren.

Optional **v4** wenn v3 noch substantielle Schwächen aufzeigt.

Nur **v3 (oder v4)** zählt als CAPSTONE-3 abgeschlossen.

---

## Bewertung — RUBRIC.md §4

```
Konzeptuelle Tiefe:                ~/25%
Argumentstärke + Methode:          ~/20%
Stilistische Reife (C1+):          ~/20%
Quellennutzung + Forschungsstand:  ~/15%
Sprachliche Korrektheit:           ~/10%
Originalität / Eigenständigkeit:   ~/10%
─────────────────────────────────────────
Gesamt:                            ~/100%

Pass: ≥ 75%; ohne externe Korrektur ≥ 80%.
```

---

## Anti-Patterns

- **Wikipedia-Eröffnung** ("Seit Aristoteles..."). Vermeiden.
- **Keine Forschungslücke benannt.** Aufsatz ohne Lücke = Referat.
- **Nur Sekundärliteratur.** Mind. 5 Primärquellen Pflicht.
- **Nur Indikativ-Behauptungen.** Konjunktiv I + II Pflicht.
- **Aufsatz ohne Gegenargument.** Bekenntnis, kein Aufsatz.
- **Schluss = Wiederholung.** Synthese + Aussicht.
- **Anglizismen** (*Output, Framework, Approach* unkommentiert). Vermeiden, falls DE-Pendant existiert.
- **Floskeln** (*"Es gibt also viel zu tun"*, *"Letztendlich kann man sagen"*). Streichen.

---

## Cross-references

- [CAPSTONE-3 — Erkenntnisprojekt v2](../../03-stil/CAPSTONE-stil.md) — kontextuelle Aufgabe.
- [03-01 Nominal vs. verbaler Stil](../../03-stil/03-01-nominal-vs-verbal.md).
- [03-06 Stilfiguren](../../03-stil/03-06-stilfiguren.md).
- [03-07 Wissenschaftliches Schreiben](../../03-stil/03-07-wissenschaftliches-schreiben.md) — Hauptmodul.
- [03-09 Lexik III](../../03-stil/03-09-lexik-3.md) — geisteswissenschaftlicher Wortschatz.
- [BEGRIFF-INDEX.md](../BEGRIFF-INDEX.md) — Quellenliste pro Begriff.
- [REFERENCES-ELITE.md](../REFERENCES-ELITE.md) — Kanonische Sekundärliteratur.
- [RUBRIC.md](../RUBRIC.md) §4.
- [Aufsatz-1500W-Template](AUFSATZ-1500W-TEMPLATE.md) — Vorgängerstufe.
- [Begriffsanalyse-Template](BEGRIFFSANALYSE-TEMPLATE.md) — Stage-4-Erweiterung mit Korpus.

---

**Aufsatz 5000 W ist die Schwelle zwischen B2-C1-Aufsatz und akademischem Output. Hier wird sichtbar, ob Wissenschaftsdeutsch hoch operativ geworden ist oder ob es noch Ziel statt Vermögen ist.**
