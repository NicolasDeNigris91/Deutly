# Veröffentlichung-Template — Manuskript-Submission an DE-Zeitschrift

> Template para [CAPSTONE-5 — Erkenntnisprojekt v4](../../05-meisterschaft/CAPSTONE-meisterschaft.md) + Modul 05-05 (Public Output). Strukturiertes Submission-Paket für Veröffentlichung in einer DE/AT/CH-Zeitschrift (kulturell oder akademisch).
>
> **Niveau-Erwartung:** C2+. Manuskript geht durch peer review eines wissenschaftlichen oder kulturellen Verlags. Volume: variabel je Zeitschrift, typisch **5000-12000 Wörter**.

---

## Frontmatter

```yaml
---
typ: veroeffentlichung-submission
stage: 05
capstone: CAPSTONE-5
zeitschrift-zielort: "[Name der Zeitschrift]"
zeitschrift-typ: [akademisch | kulturell | hybrid]
zeitschrift-territorium: [DE / AT / CH]
manuskript-titel: "[Manuskript-Titel]"
manuskript-untertitel: "[optional]"
verfasser: [Name]
korrespondenz-email: [E-Mail]
institution: [optional — Universität/Independent]
datum-submission: YYYY-MM-DD
manuskript-wortzahl: [exakt]
manuskript-version: [v1 / v2 / v3 ...]
quellen-primaer: [N]
quellen-sekundaer: [N]
zitierweise: [Chicago / DGfS / MLA / Zeitschrifts-eigen]
status: [in-Vorbereitung | submitted | review | accepted | rejected | published]
---
```

---

## Submission-Paket — die 4 Dokumente

Standard-Submission an DE-Zeitschrift erfordert:

```
1. Manuskript (Hauptdokument)              ~5000-12000 W
2. Exposé (Zusammenfassung + Positionierung) ~1-2 Seiten / ~600-1200 W
3. Lebenslauf akademisch                    1-3 Seiten
4. Anschreiben (Cover Letter)                1 Seite / ~300 W
```

(Manche Zeitschriften erfordern auch: Anonymisierte Version für Blind Review; Ethikerklärung; Konfliktabklärung.)

---

## 1. Manuskript — strukturelle Konventionen

### 1.1 Titelseite

```markdown
# [Manuskript-Titel]
## [Untertitel]

**Autor:** [Name]
**Institution:** [Universität / unabhängig]
**E-Mail:** [Korrespondenz-Adresse]
**Datum:** YYYY-MM-DD

**Wortzahl:** [exakt]
**Schlüsselbegriffe:** [4-6, in DE]

---

[Manuskript folgt.]
```

### 1.2 Abstract (zweisprachig)

```markdown
## Zusammenfassung (DE)

[150-250 W in DE; entspricht den Abstract-Konventionen der Zeitschrift.]

**Schlüsselbegriffe:** [4-6 in DE]

## Abstract (EN)

[150-250 W in EN; oft erforderlich auch für DE-Zeitschriften.]

**Keywords:** [4-6 in EN]
```

### 1.3 Hauptkörper

Strukturschema je nach Zeitschrift; **Standard akademisch**:

```
1. Einleitung                    ~10%
2. Forschungsstand                ~15%
3. Methode                        ~10%
4. Hauptteil — Analyse            ~45-50%
5. Diskussion                     ~10-15%
6. Schluss                         ~3-5%
+ Literaturverzeichnis
+ optional Anhang
```

(Cf. [AUFSATZ-5000W-TEMPLATE](AUFSATZ-5000W-TEMPLATE.md) für detaillierten Aufbau einer akademischen Arbeit.)

### 1.4 Stilistische Erwartungen — DE-Zeitschriften-Standard

- **Wissenschaftsdeutsch hoch** (cf. [03-07](../../03-stil/03-07-wissenschaftliches-schreiben.md)).
- **Konjunktiv I** in indirekter Rede verpflichtend.
- **Nominaler Stil** dominant in akademischen Zeitschriften (Adorno-Linie); verbaler Stil in kulturellen Magazinen (Feuilleton).
- **Kein Ich** in akademischen Zeitschriften standard (Ausnahme: methodologische Reflexion); Ich erlaubt in kulturellen Magazinen.
- **Anglizismen** vermeiden, falls DE-Pendant existiert.
- **Tempus**: meist Präsens für Theorie/Argumentation, Präteritum für historische Analyse, Perfekt seltener.

### 1.5 Zitierweise

#### Chicago-Style (häufig in Geistes-/Kulturwissenschaften DE)

```
Im Text: (Habermas 1981, Bd. 1, S. 26)
Bibliographie: 
Habermas, Jürgen. 1981. Theorie des kommunikativen Handelns. 
  2 Bde. Frankfurt am Main: Suhrkamp.
```

#### DGfS-Standard (Deutsche Gesellschaft für Sprachwissenschaft)

```
Im Text: Habermas (1981: 26)
Bibliographie:
Habermas, Jürgen (1981): Theorie des kommunikativen Handelns. 
  2 Bde. Frankfurt am Main: Suhrkamp.
```

#### Eigene Zeitschrifts-Konvention

- **Konsultieren**: jedes Zeitschrift hat *Autorenrichtlinien* / *Hinweise für Autor:innen*. **Verbindlich.**

### 1.6 Anhang (optional)

- Datentabellen.
- Korpus-Auszüge.
- Anonymisierte Version (für Blind Review).

---

## 2. Exposé — Submission-Begleitdokument

### Funktion

Das Exposé erläutert dem Editor:
- Wo das Manuskript in der Forschungslandschaft positioniert ist.
- Welche neue Perspektive es bietet.
- Warum es zu **dieser Zeitschrift** passt.

### Strukturschema (~1-2 Seiten)

```markdown
# Exposé zum Manuskript "[Titel]"

## 1. Forschungsfrage (~150 W)
[Klare Frage; nicht-trivial; offen für die Disziplin.]

## 2. Forschungslücke (~200 W)
[Was die existierende Forschung sagt; was fehlt.]

## 3. These (~100 W)
[Eine zentrale Behauptung; verteidigbar.]

## 4. Methodisches Vorgehen (~150 W)
[Welche Methode? Warum? Kurz.]

## 5. Hauptbeitrag (~200 W)
[Was das Manuskript zur Forschungslandschaft hinzufügt.]

## 6. Passung zur Zeitschrift (~100 W)
[Warum diese Zeitschrift? Mit Bezug auf 2-3 verwandte Artikel, 
die in derselben Zeitschrift publiziert wurden.]

## 7. Vorgesehene Publikationsform
[Manuskript ist: Forschungsartikel | Essay | Rezension | 
Diskussionsbeitrag | Conference-Paper-extended.]
```

---

## 3. Lebenslauf akademisch (CV)

### Format

```markdown
# [Name]

## Kontakt
- Adresse
- E-Mail
- ORCID (falls vorhanden)
- Website / Social Media (LinkedIn, Academia.edu)

## Akademischer Werdegang
- [Promotion / Master / Bachelor — mit Universität, Jahr, Titel der Arbeit]

## Berufliche Stationen
- [Positionen, Institutionen, Zeitraum]

## Forschungsschwerpunkte
- [3-5 Bereiche]

## Publikationen
### Monografien
[Liste]

### Aufsätze in Zeitschriften
[Liste mit vollständigen bibliographischen Angaben]

### Buchbeiträge
[Liste]

### Rezensionen
[Liste]

## Vorträge
[Auswahl: 5-10 wichtigste Vorträge mit Ort + Jahr]

## Lehre
[Wichtige Seminare, falls relevant]

## Mitgliedschaften
[Akademische Gesellschaften]

## Auszeichnungen / Stipendien
[Falls vorhanden]
```

### Hinweise

- **Ausführlich**, aber nicht ausschweifend. 1-3 Seiten Standard.
- **Chronologisch oder rückwärts-chronologisch.**
- **Keine privaten Angaben** (Familienstand, Geburtsdatum etc.) sofern nicht explizit verlangt.

---

## 4. Anschreiben (Cover Letter)

### Funktion

Das Anschreiben begleitet die Submission. **Formell**, **kurz**, **präzise**.

### Format

```markdown
[Name + Adresse Verfasser]
[E-Mail]
[Datum]

[Name des Editors / Editorial Team]
[Zeitschrift]
[Adresse]

Sehr geehrte Frau Prof. Dr. [Nachname] / 
Sehr geehrter Herr Prof. Dr. [Nachname] / 
Sehr geehrte Damen und Herren,

hiermit reiche ich mein Manuskript "[Titel]" 
zur möglichen Veröffentlichung in [Zeitschriftenname] ein.

[1-2 Sätze über den Inhalt des Manuskripts.]

[1-2 Sätze über die Passung zur Zeitschrift.]

[Bestätigung: Manuskript ist anderswo nicht eingereicht; ich erkläre 
mich mit den Autorenrichtlinien einverstanden; etc.]

Über eine positive Antwort würde ich mich freuen.

Mit freundlichen Grüßen
[Name]

Anlagen:
- Manuskript ([Wortzahl] W)
- Exposé
- Lebenslauf
- ggf. anonymisierte Version
```

### Stilistische Erwartungen

- **Sehr formell** in akademischen Zeitschriften.
- **Mittelformell** in kulturellen Zeitschriften.
- **Nicht überlang** — eine Seite max.

---

## Welche Zeitschriften? — Zielort-Auswahl

### Akademisch — Geistes-/Kulturwissenschaft

```
Deutsche Zeitschrift für Philosophie       — DE, akademisch breit
Philosophische Rundschau                    — DE, philosophisch
Zeitschrift für philosophische Forschung    — DE, akademisch
Kant-Studien                               — Kant-spezialisiert
Hegel-Studien                              — Hegel-spezialisiert
Heidegger-Studien                          — Heidegger
Philosophisches Jahrbuch                    — DE, breit
Allgemeine Zeitschrift für Philosophie     — DE
Mittelweg 36                                — Hamburger Institut
Frankfurter Schule + Kritische Theorie:
  Constellations                            — international
  Critical Horizons                         — international
```

### Akademisch — Soziologie / Politik

```
Soziale Welt                                — DE, soziologisch
Berliner Journal für Soziologie             — DE, soziologisch
Leviathan                                   — DE, politik-soziologisch
Politische Vierteljahresschrift             — DE, politisch
Zeitschrift für Politische Theorie          — DE, politische Theorie
```

### Akademisch — Linguistik

```
Zeitschrift für Sprachwissenschaft           — DE, linguistisch
Linguistische Berichte                       — DE, linguistisch
Deutsche Sprache                              — DE, germanistisch
Muttersprache                                — DE, germanistisch
```

### Kulturell

```
Merkur                                       — DE, kulturpolitisch
Kursbuch                                     — DE, kulturpolitisch
Sinn und Form                                — DE, literarisch-kulturell
neue deutsche literatur (ndl)                — DE, literarisch
Du                                           — CH, kulturell
NZZ Folio                                    — CH, kulturpolitisch
```

### Online + Open Access

```
Praefaktisch                                 — Philosophie online
Geschichte der Gegenwart                     — DE/CH, kulturpolitisch online
JoTC (Journal of Translation and 
  Critical Theory)                           — international online
```

### Hinweis

Vor der Submission: **Autorenrichtlinien** der Zeitschrift sorgfältig lesen. Format-Konventionen variieren stark.

---

## Submission-Workflow

```
1. Manuskript v1: Schreibphase (~3-12 Monate je Capstone)
2. Eigenkorrektur v2: 4-5 Camadas (~1-2 Monate)
3. Externe Korrektur v3: Mentor / Peer (~1-2 Monate)
4. Finalisierung v4: Letzter Schliff (~2-4 Wochen)
5. Submission: Manuskript + Exposé + CV + Anschreiben
6. Review-Wartezeit: 2-12 Monate (variabel)
7. Major / Minor Revision: ~1-3 Monate
8. Akzeptanz: ~6-18 Monate Submission → Publikation
```

---

## Realistic Expectations

### Akzeptanzraten DE-Zeitschriften (typisch)

```
Top-akademische Zeitschriften:        ~10-20% Akzeptanzquote
Mittlere akademische Zeitschriften:   ~20-40%
Kulturelle Zeitschriften:             variabel, oft 5-30%
Open Access / online:                  ~30-60% (höher)
```

### Gründe für Ablehnung

```
- Forschungslücke nicht klar markiert
- Methodisches Vorgehen unklar
- Argumentation nicht stringent
- Quellen unzureichend (für akademisch)
- Stil nicht zur Zeitschrift passend
- Forschungsstand veraltet
- Format nicht den Autorenrichtlinien entsprechend
```

### Bei Ablehnung

```
1. Reviewer-Feedback ernst nehmen.
2. Revision basierend auf Feedback (auch wenn Manuskript abgelehnt).
3. Re-Submission an andere Zeitschrift mit überarbeiteter Version.
4. NIE entmutigen — Akzeptanz ist langer Weg.
```

---

## Cross-references

- Módulo central: [05-05 Public Output](../../05-meisterschaft/05-05-public-output.md) (auch Vortrag, Podcast).
- Módulo correlato: [05-04 Eigene Stimme](../../05-meisterschaft/05-04-eigene-stimme.md).
- CAPSTONE: [CAPSTONE-meisterschaft](../../05-meisterschaft/CAPSTONE-meisterschaft.md).
- Template correlato: [AUFSATZ-5000W-TEMPLATE](AUFSATZ-5000W-TEMPLATE.md) (akademische Aufsatz-Konventionen).
- Template correlato: [BEGRIFFSANALYSE-TEMPLATE](BEGRIFFSANALYSE-TEMPLATE.md) (für korpusbasierte Manuskripte).

## Quellen für Submission-Praxis

- **Autorenrichtlinien** der jeweiligen Zeitschrift (verbindlich).
- **Eco, Umberto** — *Wie man eine wissenschaftliche Abschlußarbeit schreibt.* Heidelberg: UTB. Klassiker für akademische Schreib-Praxis.
- **Kornmeier, Martin** — *Wissenschaftlich schreiben leicht gemacht.* 9. Aufl., Bern: Haupt, 2021.
- **Werder, Lutz von** — *Selbstkurzanleitung für wissenschaftliches Arbeiten.* Berlin: Schibri, 2020.

---

**Veröffentlichung ist der finale Schritt — wer publiziert, hat die Schwelle zwischen Lerner + Beitragender überschritten.**
