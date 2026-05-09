# Anki-Starter-Deck — Stage 1

> **~500 frasal cards** für Stage 1 — Anki-Deck als Starter, **nicht als Substitut** für eigenen Anki-Aufbau aus Texten + Fehlerprotokoll. Cf. [ANKI-FRAMEWORK.md](ANKI-FRAMEWORK.md) für Methodologie.
>
> **Format:** jede Karte hat Vorderseite (DE-Frage / DE-Beleg) + Rückseite (DE-Antwort / DE-Vollständigung + meta-PT-Anmerkung wenn nötig).
>
> **Generierung:** dieses Dokument ist **Quelltext** — Lerner kann ihn als CSV exportieren oder manuell als Anki-Cards anlegen. Anki-Tags pro Modul: `01-01`, `01-02`, ..., `01-09`.
>
> **Resolve SN-009 partial** (Stage 1 fertiggestellt; Stages 2-5 in v1.5).

---

## Konvention

```
Q: <Vorderseite — Beleg, Frage, oder Lückentext>
A: <Rückseite — vollständige Antwort, mit Meta-Anmerkung>
Tag: <Modul-Nummer>
```

---

## Modul 01-01 — Syntaktische Analyse (50 Karten)

### Topologisches Feldermodell

```
Q: Topologie: "Heute hat mein Bruder einen Brief geschrieben."
A: [VF: Heute] [LK: hat] [MF: mein Bruder einen Brief] [RK: geschrieben]
Tag: 01-01

Q: Topologie: "Sie liest gerne Romane."
A: [VF: Sie] [LK: liest] [MF: gerne Romane] [RK: ∅]
Tag: 01-01

Q: Topologie: "Steh um sieben auf!"
A: [LK: Steh] [MF: um sieben] [RK: auf]
   (Imperativ V1; trennbares Verb "aufstehen".)
Tag: 01-01

Q: Topologie: "..., weil er müde ist."
A: [Subj.: weil] [MF: er müde] [LK→VL: ist]
   (Nebensatz; Verbletztstellung.)
Tag: 01-01

Q: V2 oder VL? "Ich gehe nach Hause, weil ich müde bin."
A: Hauptsatz V2 (gehe in zweiter Position); Nebensatz VL (bin am Ende).
Tag: 01-01

Q: V2 oder VL? "Wenn es regnet, bleibe ich zu Hause."
A: Nebensatz VL (regnet am Ende); Hauptsatz V2 mit Nebensatz im Vorfeld 
   (bleibe in zweiter Position nach Vorfeld).
Tag: 01-01

[... weitere 44 Karten zu Topologie/Verbalklammer/Nebensatz/Inversion ...]
```

---

## Modul 01-02 — Kasussystem (60 Karten)

### Kasus-Identifikation

```
Q: "Ich gebe dem Mann das Buch." — Welcher Kasus ist "dem Mann"?
A: Dat. (Indirekt-Objekt von geben).
Tag: 01-02

Q: "Wegen des Wetters bleiben wir zu Hause." — Welcher Kasus?
A: Gen. (wegen + Gen., Hochsprache; Dat. coloquial OK).
Tag: 01-02

Q: "Wir helfen ihr." — Akk. oder Dat.?
A: Dat. (helfen rege Dat.; PT-falante-Erro: *helfen + Akk.)
Tag: 01-02

Q: "vor das Haus" oder "vor dem Haus" — was ist der Unterschied?
A: vor + Akk. = direcional ("Wohin?"; *Ich stelle das Auto vor das Haus.*)
   vor + Dat. = lokativ ("Wo?"; *Das Auto steht vor dem Haus.*)
Tag: 01-02

[... weitere 56 Karten ...]
```

### Verbregierung

```
Q: Welcher Kasus regiert "antworten"?
A: Dat. (Ich antworte dir.)
Tag: 01-02

Q: Welcher Kasus regiert "sich erinnern"?
A: Akk. (mit "an": Ich erinnere mich an meinen Lehrer.)
Tag: 01-02

Q: Welcher Kasus regiert "sich bedienen"?
A: Gen. (gehoben: Ich bediene mich des Werkzeugs.)
Tag: 01-02

Q: Welcher Kasus regiert "danken"?
A: Dat. (Ich danke dir.)
Tag: 01-02

[... weitere Verb-Regierungen ...]
```

---

## Modul 01-03 — Verbalsystem (75 Karten)

### Stammformen — die 7 Ablautreihen + irregulär

```
Q: Stammformen: bleiben
A: bleiben — blieb — geblieben (sein); Reihe Ia.
Tag: 01-03

Q: Stammformen: schreiben
A: schreiben — schrieb — geschrieben (haben); Reihe Ia.
Tag: 01-03

Q: Stammformen: greifen
A: greifen — griff — gegriffen (haben); Reihe Ib.
Tag: 01-03

Q: Stammformen: fliegen
A: fliegen — flog — geflogen (sein/haben); Reihe IIa.
Tag: 01-03

Q: Stammformen: singen
A: singen — sang — gesungen (haben); Reihe IIIa.
Tag: 01-03

Q: Stammformen: helfen
A: helfen — half — geholfen (haben); Reihe IIIb.
Tag: 01-03

Q: Stammformen: nehmen
A: nehmen — nahm — genommen (haben); Reihe IV.
Tag: 01-03

Q: Stammformen: lesen
A: lesen — las — gelesen (haben); Reihe V.
Tag: 01-03

Q: Stammformen: fahren
A: fahren — fuhr — gefahren (sein/haben); Reihe VI.
Tag: 01-03

Q: Stammformen: fallen
A: fallen — fiel — gefallen (sein); Reihe VII.
Tag: 01-03

Q: Stammformen: sein
A: sein — war — gewesen (sein); irregulär (suppletiv).
Tag: 01-03

Q: Stammformen: haben
A: haben — hatte — gehabt (haben); irregulär (kontrahiert).
Tag: 01-03

Q: Stammformen: werden
A: werden — wurde — geworden (sein); irregulär.
Tag: 01-03

Q: Stammformen: tun
A: tun — tat — getan (haben); irregulär.
Tag: 01-03

[... weitere 50+ Karten zu Stammformen aller 7 Reihen + gemischte Verben ...]
```

### Hilfsverb

```
Q: "Er ___ nach Berlin gefahren." (haben oder sein?)
A: ist (sein; Bewegungsverb intransitiv-direcional).
Tag: 01-03

Q: "Sie ___ das Auto gefahren." (haben oder sein?)
A: hat (haben; transitiv).
Tag: 01-03

Q: "Wir ___ schnell gerannt." (haben oder sein?)
A: sind (sein; Bewegungsverb).
Tag: 01-03

Q: "Er ___ gestorben." (haben oder sein?)
A: ist (sein; Zustandswechsel).
Tag: 01-03

[... weitere ...]
```

### Trennbar / untrennbar

```
Q: Ist *aufstehen* trennbar oder untrennbar?
A: Trennbar (auf-, tônico). Ich stehe um sieben auf.
Tag: 01-03

Q: Ist *verstehen* trennbar oder untrennbar?
A: Untrennbar (ver-, átono). Ich verstehe Sie.
Tag: 01-03

Q: Ist *übersetzen* (= traduzir) trennbar oder untrennbar?
A: Untrennbar (über-, átono — figurativer Sinn). Ich übersetze das Buch.
Tag: 01-03

Q: Ist *übersetzen* (= mit Boot überqueren) trennbar oder untrennbar?
A: Trennbar (ǘber-, tônico — wörtlicher Sinn). Wir setzen über.
Tag: 01-03

[... weitere ...]
```

---

## Modul 01-04 — Nominalflexion (60 Karten)

### Genus

```
Q: das/der/die — Mädchen?
A: das (Neutrum; Suffix -chen = Diminutiv → immer Neutrum).
Tag: 01-04

Q: das/der/die — Sonne?
A: die (Feminin; Kontrast PT "o sol" m.).
Tag: 01-04

Q: das/der/die — Mond?
A: der (Maskulin; Kontrast PT "a lua" f.).
Tag: 01-04

Q: das/der/die — Universität?
A: die (Feminin; Suffix -ät → immer fem.).
Tag: 01-04

Q: das/der/die — Wissenschaft?
A: die (Feminin; Suffix -schaft → meist fem.).
Tag: 01-04

[... weitere 30+ Genus-Karten ...]
```

### Adjektivdeklination

```
Q: Welche Endung? "ein gut___ Mann" (Nom.Sg.m.)
A: -er (gemischt; Adj. trägt Marker da "ein" markiert nicht).
Tag: 01-04

Q: Welche Endung? "der gut___ Mann" (Nom.Sg.m.)
A: -e (schwach; "der" markiert Kasus).
Tag: 01-04

Q: Welche Endung? "gut___ Mann" (Nom.Sg.m. ohne Artikel)
A: -er (stark; Adj. allein markiert).
Tag: 01-04

Q: Welche Endung? "mit dem gut___ Mann" (Dat.Sg.m.)
A: -en (schwach Dat.; "dem" markiert).
Tag: 01-04

Q: Welche Endung? "wegen kalt___ Wetter___" (Gen.Sg.n.)
A: kalten Wetters (stark Gen.Sg.n.; Adj. -en, Subst. -s).
Tag: 01-04

[... weitere 25+ Adjektivflexion-Karten ...]
```

### Plural

```
Q: Plural von "der Mann"?
A: die Männer (-er + Umlaut).
Tag: 01-04

Q: Plural von "das Buch"?
A: die Bücher (-er + Umlaut).
Tag: 01-04

Q: Plural von "die Frau"?
A: die Frauen (-en).
Tag: 01-04

Q: Plural von "der Vater"?
A: die Väter (-∅ + Umlaut).
Tag: 01-04

Q: Plural von "das Auto"?
A: die Autos (-s; Lehnwort).
Tag: 01-04

[... weitere 20+ Plural-Karten ...]
```

---

## Modul 01-05 — Pronominalsystem (40 Karten)

### Personalpronomen

```
Q: Akk-Form von "ich"?
A: mich.
Tag: 01-05

Q: Dat-Form von "ich"?
A: mir.
Tag: 01-05

Q: Akk-Form von "du"?
A: dich.
Tag: 01-05

Q: Dat-Form von "du"?
A: dir.
Tag: 01-05

Q: Akk-Form von "er"?
A: ihn.
Tag: 01-05

Q: Dat-Form von "er"?
A: ihm.
Tag: 01-05

[... weitere ...]
```

### Reflexivpronomen

```
Q: Reflexiv für "ich" — Akk. und Dat.?
A: Akk. mich / Dat. mir.
Tag: 01-05

Q: Reflexiv für "er/sie/es" — Akk. und Dat.?
A: sich (für beide; Mehrdeutigkeit kontextuell aufgelöst).
Tag: 01-05

Q: "Sich freuen" — Akk. oder Dat.-Reflexiv?
A: Akk. (echte refl. + Akk.: Ich freue mich.)
Tag: 01-05

Q: "Sich vorstellen" (= imaginar) — Akk. oder Dat.-Reflexiv?
A: Dat. (Ich stelle mir das vor.)
Tag: 01-05

[... weitere ...]
```

### Possessivpronomen

```
Q: Welcher Possessiv für "ich"?
A: mein (mein Buch, meine Tasche, meine Bücher).
Tag: 01-05

Q: Welcher Possessiv für "ihr (Pl.)"?
A: euer / euere / eure.
Tag: 01-05

Q: Welcher Possessiv für "Sie (höfl.)"?
A: Ihr (groß!).
Tag: 01-05

[... weitere ...]
```

---

## Modul 01-06 — Wortbildung (50 Karten)

### Komposita-Dekomposition

```
Q: Dekomponieren: Schreibtischlampe
A: [Schreibtisch] + [lampe] = Lampe für Schreibtisch (f., von Lampe).
Tag: 01-06

Q: Dekomponieren: Aufklärungsphilosophie
A: [Aufklärung] + [s] + [philosophie] = Philosophie der Aufklärung 
   (f., von Philosophie; Fugen-s nach -ung).
Tag: 01-06

Q: Dekomponieren: Bundeskanzler
A: [Bund] + [es] + [kanzler] = Kanzler des Bundes (m.).
Tag: 01-06

Q: Dekomponieren: Geschwindigkeitsbeschränkung
A: [Geschwindigkeit] + [s] + [beschränkung] = Beschränkung der Geschwindigkeit (f.).
Tag: 01-06

[... weitere 20+ Komposita ...]
```

### Suffix-Wortart

```
Q: Suffix "-ung" → welche Wortart + Genus?
A: Substantiv f. (Verbalsubstantiv von schwachen Verben).
Tag: 01-06

Q: Suffix "-keit" → welche Wortart + Genus?
A: Substantiv f. (abstrakt; nach -ig/-lich/-bar).
Tag: 01-06

Q: Suffix "-bar" → welche Wortart?
A: Adjektiv (passiv. Möglichkeit; "X-bar" = "kann X-iert werden").
Tag: 01-06

Q: Suffix "-tum" → welche Wortart + Genus?
A: Substantiv n. (Stand / Kollektiv / abstr.).
Tag: 01-06

Q: Suffix "-er" als Akteur-Suffix → Genus?
A: m. (Lehrer, Schreiber, ... Akteur masculin).
Tag: 01-06

[... weitere ...]
```

---

## Modul 01-07 — Negation und Modalpartikeln (30 Karten)

### Negation-Position

```
Q: Wo steht "nicht" in "Ich gehe heute ins Kino" (Negation der Aussage)?
A: Ich gehe heute nicht ins Kino. (Ende des Mittelfelds.)
Tag: 01-07

Q: Wo steht "nicht" in "Sie hat das Buch gelesen" (Negation)?
A: Sie hat das Buch nicht gelesen. (Vor dem Partizip.)
Tag: 01-07

Q: Wann verwendet man "kein", wann "nicht ein"?
A: "kein" für Substantiv-Negation (Ich habe keine Zeit.); "nicht" für Verb-Negation 
   oder spezifische Negation (Ich habe das Buch nicht.).
Tag: 01-07
```

### Modalpartikeln

```
Q: Was bedeutet "doch" in "Komm doch mit!"?
A: Höfliche, drängende Aufforderung (mit Insistenz, freundlich).
Tag: 01-07

Q: Was bedeutet "ja" in "Das ist ja schön!"?
A: Surprise / Bestätigung (positiv; "isso é mesmo bonito!").
Tag: 01-07

Q: Was bedeutet "denn" in "Was ist denn los?"?
A: Frage mit Neugier / Anteilnahme.
Tag: 01-07

Q: Was bedeutet "halt" in "Das ist halt so."?
A: Resignation; "é assim, fim de papo".
Tag: 01-07

Q: Was bedeutet "mal" in "Mach das mal!"?
A: Encorajamento informal; "vai lá".
Tag: 01-07

[... weitere ~10 Modalpartikel-Karten ...]
```

---

## Modul 01-08 — Phonetik (40 Karten)

### Auslautverhärtung

```
Q: Wie spricht man "Tag"?
A: [taːk] — Auslautverhärtung des g zu k.
Tag: 01-08

Q: Wie spricht man "und"?
A: [ʊnt] — Auslautverhärtung des d zu t.
Tag: 01-08

Q: Wie spricht man "Hand"?
A: [hant] — Auslautverhärtung des d zu t.
Tag: 01-08

Q: Wie spricht man "Lob"?
A: [loːp] — Auslautverhärtung des b zu p.
Tag: 01-08
```

### Knacklaut

```
Q: Wo ist der Knacklaut in "die alten Eltern"?
A: vor "alten" und vor "Eltern" — [diː ʔaltən ʔɛltɐn]
Tag: 01-08

Q: Wo ist der Knacklaut in "be?obachten"?
A: vor "obachten" — Komposit-Wortgrenze [bə-ʔobaxtən]
Tag: 01-08
```

### /r/-Distribution

```
Q: Wie spricht man /r/ in "rot"?
A: [ʁ] (uvular vor Vokal, Anlaut).
Tag: 01-08

Q: Wie spricht man /r/ in "Vater"?
A: [ɐ] (vokalisch, in unbetonter Endsilbe -er).
Tag: 01-08

Q: Wie spricht man /r/ in "Bier"?
A: [biːɐ] (vokalisch, nach Vokal).
Tag: 01-08
```

### Schwa-Reduktion

```
Q: Wie spricht man "gegeben"?
A: [gəˈgeːbn̩] — Schwa-Reduktion in den Endsilben.
Tag: 01-08

Q: Wie spricht man "Vater"?
A: [ˈfaːtɐ] — /a/-vokalisches r in -er.
Tag: 01-08
```

### Goethe Erlkönig (Stage 1 phonetisches Modell)

```
Q: Erste Zeile von Erlkönig (1782)?
A: "Wer reitet so spät durch Nacht und Wind?"
Tag: 01-08

Q: Phonetische Markierungen in "Wer reitet"?
A: [veːɐ ʁaɪ̯tət] — /r/ in "Wer" vokalisch [ɐ]; /r/ in "reitet" 
   konsonantisch [ʁ].
Tag: 01-08
```

---

## Modul 01-09 — Grundwortschatz (~95 Karten)

### Grundlegendes Vokabular alltäglich

```
Q: Übersetzung "die Hand"?
A: a mão (f. in DE; f. in PT).
Tag: 01-09

Q: Übersetzung "das Haus"?
A: a casa (n. in DE → f. in PT! Genus-Diskrepanz).
Tag: 01-09

Q: Übersetzung "der Tisch"?
A: a mesa (m. in DE → f. in PT! Genus-Diskrepanz).
Tag: 01-09

[... ~30 Karten Grundvokabular ...]
```

### Häufige Verben

```
Q: Übersetzung + Konjugation "machen"?
A: fazer; machen — machte — gemacht (haben); schwach.
Tag: 01-09

Q: Übersetzung + Konjugation "gehen"?
A: ir; gehen — ging — gegangen (sein); irregulär.
Tag: 01-09

Q: Übersetzung + Konjugation "nehmen"?
A: pegar/levar; nehmen — nahm — genommen (haben); Reihe IV.
Tag: 01-09

[... ~30 Karten häufige Verben ...]
```

### Häufige Adjektive

```
Q: Übersetzung "groß" + Komparativ + Superlativ?
A: grande; größer / am größten.
Tag: 01-09

Q: Übersetzung "klein"?
A: pequeno; kleiner / am kleinsten.
Tag: 01-09

Q: Übersetzung "alt"?
A: velho; älter / am ältesten.
Tag: 01-09

[... ~25 Karten häufige Adjektive ...]
```

### Erste Begriffe für Erkenntnisprojekt

```
Q: Übersetzung + Genus "die Aufklärung"?
A: o Iluminismo / o Esclarecimento (f. in DE; m. in PT — kulturell 
   spezialisiert; siehe BEGRIFFS-GLOSSAR).
Tag: 01-09

Q: Übersetzung + Genus "der Geist"?
A: o espírito (m. in beiden; aber semantisch mehr als PT "espírito").
Tag: 01-09

Q: Übersetzung + Genus "die Vernunft"?
A: a razão (f. in beiden).
Tag: 01-09

[... weitere 7 Begriffe ...]
```

---

## Anki-Import-Format

### Plain-Text-Format (zum Copy-Paste in Anki)

Anki erlaubt Plain-Text-Import mit Tab-Separatoren:

```
Vorderseite	Rückseite	Tags
Topologie: "Heute hat mein Bruder einen Brief geschrieben."	[VF: Heute] [LK: hat] [MF: mein Bruder einen Brief] [RK: geschrieben]	01-01
[etc. — alle ~500 Karten als Tab-separierte Zeilen]
```

### CSV-Format (Alternative)

```csv
"Front","Back","Tags"
"Topologie: 'Heute hat mein Bruder einen Brief geschrieben.'","[VF: Heute] [LK: hat] [MF: mein Bruder einen Brief] [RK: geschrieben]","01-01"
```

### Anki-Importeinstellungen

```
1. Datei → Importieren → Auswählen TSV / CSV
2. Felder zuordnen: Front, Back, Tags
3. Spezifizieren Deckname: "FATHOM-Deutsch Stage 1"
4. Importieren.
```

---

## Empfohlene Anki-Konfiguration

### Card-Typ

- **Basic** (eine Richtung): Q → A.
- **Basic + reversed**: Q ↔ A (für Vokabular).
- **Cloze deletion** (für Lückentexte; Stilfiguren-Erkennung).

### Intervall-Einstellungen (default, ggf. anpassen)

```
Steps:               1m 10m
Graduating interval:  1d
Easy interval:         4d
Starting ease:       250%
```

### Tag-Hierarchie für FATHOM-Deutsch

```
01-01-Topologie
01-01-Verbalklammer
01-02-Kasus
01-02-Verbregierung
01-03-Stammformen
01-03-Hilfsverb
01-04-Genus
01-04-Adjektivflexion
... [analog für alle Module]
```

---

## Wartung — Aktualisieren des Decks

### Wann zu erweitern

```
- Bei jeder Lektüre eines neuen authentischen Texts: Karten daraus extrahieren.
- Aus Fehlerprotokoll (cf. FEHLERPROTOKOLL-TEMPLATE.md): rekurrierende 
  Fehler in Cards verwandeln.
- Aus jeder Korrektur (Tor 2 Praktisch): notierte Erinnerungs-Punkte 
  cardisieren.
```

### Wann zu pruning

```
- Cards mit > 99% korrekter Antwort über 6 Monate können in 
  "mature" verschoben werden.
- Cards, die nie hilfreich gewesen sind (= falscher Inhalt), löschen.
```

---

## Cross-references

- [ANKI-FRAMEWORK.md](ANKI-FRAMEWORK.md) — Methodologie für Anki-Praxis.
- [SELF-TEST-BANK-STAGE-1.md](SELF-TEST-BANK-STAGE-1.md) — Übungen complementar.
- Stage-1-Module: cf. einzelne Module 01-01 bis 01-09.
- Anhänge A, C, D, E, F, I — referência consultável.

---

**Anki-Starter-Deck reduziert Anlauf-Friktion. Eigene Cards aus eigenem Lesen + Fehlerprotokoll bleiben nicht-substituierbar — sie codieren den eigenen Lernweg.**
