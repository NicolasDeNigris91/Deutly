---
module: 01-01-de
title: Syntaktische Analyse — Topologisches Feldermodell (Deutsche Fassung)
stage: fundamente
prereqs: []
status: aktiv
language: de
parallel-to: 01-01-syntaktische-analyse.md
---

# 01-01 — Syntaktische Analyse — Topologisches Feldermodell (Deutsche Fassung)

> **Hinweis:** Dies ist die deutschsprachige Parallel-Adaptation von [01-01-syntaktische-analyse.md](01-01-syntaktische-analyse.md) (PT-BR-Original). Bestimmt für fortgeschrittene Lerner (C1+), die Modul-Inhalt auf Deutsch konsultieren möchten. Bei Inkonsistenzen gilt das PT-BR-Original als Referenz.
>
> **Status:** Erstadaptation v2.5 (2026-05-10). Resolve **SN-008 weiter expanded**.

## 1. Sprachliches Problem

Das Deutsche operiert syntaktisch nach dem **Topologischen Feldermodell** — einer der grundlegendsten + folgenreichsten Strukturen der DE-Grammatik. Wer es nicht beherrscht, kann keinen DE-Satz korrekt analysieren oder produzieren.

Hindernisse für PT-Falante:

- **PT ist SVO konsistent**; DE ist V2 im Hauptsatz + Verbletzt im Nebensatz.
- **PT hat keine Verbalklammer**; DE-Verben werden oft auf zwei Positionen verteilt.
- **Mittelfeld-Anordnung** ist im DE flexibel + pragmatisch gesteuert; PT-Wortstellung ist starrer.

## 2. Harte Theorie

### 2.1 Felder-Inventar

Der DE-Satz hat 5 topologische Felder:

| Feld | Funktion | Beleg |
|---|---|---|
| **Vorfeld (VF)** | 1 Konstituent vor finitem Verb | *Heute* |
| **Linke Klammer (LK)** | finites Verb (V2) oder Subjunktor (VL) | *hat* / *weil* |
| **Mittelfeld (MF)** | Subjekt + Objekte + Adverbiale | *mein Bruder einen Brief* |
| **Rechte Klammer (RK)** | nicht-finite Verbteile (Part.II, Inf., trennbares Präfix) | *geschrieben* |
| **Nachfeld (NF)** | extraponierte Konstituenten (oft schwere) | *, weil er Kontakt halten will* |

**Beispiel-Satz:**
> *Heute hat mein Bruder einen Brief geschrieben, weil er Kontakt halten will.*

```
[VF: Heute] [LK: hat] [MF: mein Bruder einen Brief] [RK: geschrieben] 
[NF: , weil er Kontakt halten will]
```

### 2.2 V2-Constraint

Im **Hauptsatz** muss das finite Verb in **2. Position** stehen — die LK. Das Vorfeld kann von genau **einem** Konstituent besetzt sein:

- *Heute hat mein Bruder...* (Adverbial im VF)
- *Mein Bruder hat heute...* (Subj. im VF)
- *Einen Brief hat mein Bruder heute...* (Akk-Obj. im VF — kontrastiv markiert)

Nicht: *Heute mein Bruder hat...* (zwei Konstituenten im VF — agrammatisch).

### 2.3 Verbletztstellung im Nebensatz

Subjunktoren (*weil, dass, wenn, obwohl, da, als, ob, ...*) leiten Nebensätze ein. Konsequenz: das finite Verb wandert in die **Rechte Klammer** (Verbletzt-Stellung).

> *...weil ich gestern Brot gekauft habe.*
> 
> ```
> [Subj.: weil] [MF: ich gestern Brot] [RK: gekauft habe]
> ```

### 2.4 Verbalklammer

Bei zusammengesetzten Tempora (Hilfsverb + Part.II oder Modal + Inf.) entsteht die **Verbalklammer**:
- LK: finites Hilfsverb / Modalverb.
- RK: Part.II oder Infinitiv.

> *Sie hat das Buch gelesen.* — LK *hat*; RK *gelesen*.
> *Du musst mich anrufen.* — LK *musst*; RK *anrufen*.
> *Er steht um sieben Uhr auf.* — LK *steht*; RK *auf* (trennbares Präfix).

Sätze ohne Verbalklammer (= einfaches Verb): *Wir gehen ins Kino*. RK leer.

### 2.5 Ausklammerung (Nachfeld)

Schwere Konstituenten (Relativsätze, lange PPs, Vergleichssätze) werden oft aus der Verbalklammer ins **Nachfeld** verschoben:

> *Er hat das Buch gelesen, das er gestern gekauft hat.*
> 
> Statt: *Er hat das Buch, das er gestern gekauft hat, gelesen* (= klammerintern; pragmatisch schwer).

Funktion: reduziert die Verarbeitungs-Last des Arbeitsgedächtnisses des Lesers/Hörers.

### 2.6 Mittelfeld-Anordnung

Im Mittelfeld ist die Wortstellung **pragmatisch flexibel**, aber durch Default-Hierarchien geregelt:

**Pronominalfeld vor NP**:
> *Ich habe es ihm gestern gegeben.* (Akk-Pron *es* + Dat-Pron *ihm* → vor Adverbial)

**NP-Default Dat vor Akk**:
> *Ich habe gestern dem Mann das Buch gegeben.* (Dat-NP *dem Mann* vor Akk-NP *das Buch*)

**Tempus < Modus < Lokus** (Adverbial-Default):
> *Ich habe gestern aus Versehen in der Küche das Glas zerbrochen.*

## 3. Texto-âncora

**Grewendorf, Günther / Hamm, Fritz / Sternefeld, Wolfgang**: *Sprachliches Wissen. Eine Einführung in moderne Theorien der grammatischen Beschreibung*. Frankfurt: Suhrkamp 1987.

**Plus**: Eisenberg, Peter: *Grundriss der deutschen Grammatik*, Bd. 2 *Der Satz*. 5. Aufl. Stuttgart: Metzler 2020.

## 4. Sprachliche Aufgabe

(a) **Feldermodell-Analyse-Übung**: 20 DE-Sätze topologisch dekomponieren (Hauptsätze + Nebensätze + Sätze mit Verbalklammer + Sätze mit Ausklammerung).

(b) **Topikalisierungs-Übung**: 5 Sätze mit verschiedenen Vorfeld-Wahlen konstruieren — pragmatische Differenzierung markieren.

(c) **Mittelfeld-Anordnungs-Drill**: 10 Sätze mit gegebenen Konstituenten in korrekter Mittelfeld-Reihenfolge zusammenstellen.

## 5. Verbindungen

- **Prereq**: keine (Stage-1-Eingangs-Modul).
- **Ergänzt durch**: 01-02 Kasussystem; 01-03 Verbalsystem; 02-01 Subordination; 02-08 Topik-Fokus.
- **Cross-Reference**: 04-04 Generative Syntax (V→C-Bewegung erklärt Feldermodell); 04-09 Kontrastive PT-DE.

## 6. Konzeptuelles Tor

1. Welche 5 Felder hat das Topologische Feldermodell?
2. Was ist V2-Constraint im Hauptsatz?
3. Warum steht das finite Verb im Nebensatz mit *weil* am Ende?
4. Was ist Verbalklammer? Konstruieren Sie 3 Beispiele.
5. Was ist Ausklammerung? Wann wird sie verwendet?

## 7. Praktisches Tor

Vorlage der drei Aufgaben (a, b, c). Loop der Verfeinerung. 5 Begründungsfragen.

## 8. Literaturverzeichnis

- Eisenberg, Peter: *Grundriss der deutschen Grammatik*. 2 Bde. Stuttgart: Metzler.
- Helbig, Gerhard / Buscha, Joachim: *Deutsche Grammatik*. Berlin: Langenscheidt 2001.
- IDS-Grammis (online: grammis.ids-mannheim.de).

---

## Cross-references

- [01-01-syntaktische-analyse.md](01-01-syntaktische-analyse.md) — PT-BR-Original.
- [INDEX-DE](../00-meta/INDEX-DE.md).
- [MENTOR-DE](../../MENTOR-DE.md).
