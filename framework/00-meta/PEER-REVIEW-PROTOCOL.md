# PEER-REVIEW-PROTOCOL — Externe Linguisten-Validierung

> Protokoll zur systematischen Peer-Review des FATHOM-Deutsch-Frameworks durch externe DE-Linguisten / Germanisten / DaF-Spezialisten.
>
> **Status:** v3.0 (2026-05-10). Resolve **SN-010 partial start** (Peer-Review-Validierung).

---

## 1. Hintergrund

FATHOM-Deutsch wurde von einem PT-falante adulto Lerner mit germanistisch-linguistischem Hintergrund konstruiert. Das Framework ist **amateurisch im positiven Sinne** — nicht akademische Tese, sondern operatives Werkzeug. **Validierung durch Specialists** garantiert struktureller Rigor.

Ziel: 3-5 externe DE-Linguisten / Germanisten / DaF-Spezialisten reviewen das Framework systematisch. Feedback dokumentiert + Korrekturen implementiert.

---

## 2. Reviewer-Profile

### 2.1 Wunsch-Profil

Idealkandidaten:
- **Sprach-Niveau**: Native DE (oder C2-Akademiker).
- **Disziplin**: Germanistische Linguistik / DaF-Methodik / Allgemeine Linguistik / Komparative Linguistik.
- **Erfahrung**: 5+ Jahre Lehre + Forschung an DE-Universität oder Goethe-Institut.
- **Affiliation**: Universitätsinstitut (z.B. IDS Mannheim, Goethe-Institut, Eisenberg-Schule); Forschungs-Stiftung; Akademie der Wissenschaften.
- **Interesse**: an L2-Erwerb-Frameworks; an Comparative-Methodologie PT-DE.

### 2.2 Kontakt-Strategien

**Standard-Akquisitionswege**:
- Direkte E-Mail an institutionelle Kontakte (mit Empfehlung von Mentor / Senior-Akademiker).
- Vortrag an Universität DaF-Konferenz + spätere Anfrage.
- Kontakt über GitHub Discussions oder akademische Twitter-Plattform.
- Kontakt via gemeinsame Drittparteien (Empfehlung von Honneth-/Habermas-Schule etc.).

### 2.3 Anreize für Reviewer

**Reciprocity**:
- Anerkennung im CHANGELOG + RELEASE-NOTES + PEER-REVIEW-Verzeichnis.
- Ko-Autorenschaft an publikations-würdigen Methoden-Reflexionen (wenn Peer-Review zu Publikation führt).
- Einladung als Featured-Speaker zur jährlichen FATHOM-Deutsch Online-Konferenz.
- Honorar nicht obligatorisch (Framework ist non-commercial), aber bei substantieller Review-Arbeit (>10 Stunden) verhandelbar mit pre-deklariertem Reviewer-Stipendium.

---

## 3. Review-Format

### 3.1 Strukturierter Review-Bogen

Reviewer erhält:
- Vollständiges Repository-Zugang (Read-only oder Fork).
- Strukturierter Review-Bogen (~10-15 Seiten Template).
- Spezifische Stage / Modul / Anhang zu reviewen (nach Reviewer-Spezialisierung).

**Review-Bogen-Sektionen**:

1. **Identifikation Reviewer + Datum**.
2. **Reviewte Komponenten** (z.B. "Stage 2 + ANHANG D + ANHANG G").
3. **Allgemeine Eindrücke** (Lerner-Eignung; pädagogische Tiefe; Authentik-Anteil; ~500W).
4. **Strukturelle Korrektheit pro Komponente** (Tabellen-Format):
   - Komponent | Korrekt? | Anmerkung |
5. **Quellenkritik** (Akademie-Ausgabe-Verweise; Sekundärliteratur-Aktualität).
6. **Methodologische Reflexion** (SLA-Theorie-Bezüge; Methodologie der Loop der Verfeinerung; Stage-Progression-Logik).
7. **Spezifische Korrektur-Vorschläge** (Tippfehler + Strukturfehler + konzeptuelle Lücken).
8. **Vergleich mit etablierten DaF-Lehrwerken** (Hueber / Cornelsen / Klett / Schubert).
9. **Empfehlungs-Klassifikation** (5-Stufen-Skala):
   - 1 = Major restructuring nötig.
   - 2 = Substantielle Korrekturen nötig.
   - 3 = Akzeptabel mit moderaten Korrekturen.
   - 4 = Gut; nur kleine Korrekturen.
   - 5 = Hervorragend.
10. **Beschreibung des Reviewers + Erlaubnis zur Anerkennung**.

### 3.2 Review-Zeitrahmen

Standard-Erwartung: 4-8 Wochen ab Erhalt des Materials.

Reviewer kann sich für eine Sub-Komponente entscheiden (ein Stage, eine Sub-Track, eine Disziplin) statt das gesamte Framework — Spezialisierungs-Tiefe > breite-Oberflächlichkeit.

---

## 4. Implementations-Workflow

### 4.1 Mantenedor-Phase

Nach Erhalt des Reviews:
1. **Triage**: Mantenedor klassifiziert jeden Korrektur-Vorschlag:
   - **Akzeptiert sofort** (substantielle + begründete Korrektur).
   - **Diskussion nötig** (philosophische Differenz oder methodische Wahl).
   - **Abgelehnt mit Begründung** (selten; aber transparent dokumentieren).

2. **Implementierung**: Akzeptierte Korrekturen via Pull Request mit Verweis auf Reviewer.

3. **Diskussion**: Strittige Punkte via Issue oder Direkt-Korrespondenz mit Reviewer; Konsensus angestrebt.

### 4.2 Anerkennung in Repository

Reviewer wird anerkannt (mit Erlaubnis):

- **In CHANGELOG**: "v3.0 — Peer-Review-Korrekturen implementiert (Reviewer: Prof. Dr. NN, Universität Heidelberg)".
- **In RELEASE-NOTES**: Substantielle Diskussion der Korrektur-Beiträge.
- **In PEER-REVIEW-Verzeichnis** (`framework/00-meta/peer-review/REVIEWER-NN.md`): vollständige Review-Bogen + Mantenedor-Antwort + Implementations-Notizen.
- **In README**: Reviewer-Liste + Affiliation + Datum.

### 4.3 Konflikte zwischen Reviewern

Wenn mehrere Reviewer zu derselben Komponente unterschiedliche Empfehlungen geben:
- Mantenedor moderiert Diskussion.
- Bei strittigen Methoden-Entscheidungen: DECISION-LOG-Eintrag mit transparenter Begründung.
- Bei strittigen Inhalts-Entscheidungen: ggf. zusätzlicher Expert-Review oder Comunidade-Diskussion.

---

## 5. Spezifische Review-Bedarfsfelder

### 5.1 Hochpriorität für Review

**Stage 4 Module** (Linguistik):
- 04-04 Generative Syntax: Reviewer mit Generative-Syntax-Hintergrund.
- 04-05 Formale Semantik: Reviewer mit Frege/Montague-Hintergrund.
- 04-06 Diskursanalyse: Reviewer mit Foucault- oder Fairclough-Hintergrund.
- 04-08 Korpuslinguistik: Reviewer mit DWDS/COSMAS-II-Erfahrung.
- 04-10 Hermeneutik: Reviewer mit Heidegger/Gadamer-Spezialisierung.

**Stage 5 Module** (Output):
- 05-02 Wissenschaftssprache: Reviewer mit Habermas/Luhmann/Adorno-Spezialisierung.

**Stage 6 Tracks**:
- Track A (Übersetzung): Reviewer mit Übersetzungs-Praxis-Erfahrung.
- Track B (Forschung): Reviewer mit Promotionserfahrung.
- Track C (Fachsprache): Reviewer aus Recht / Medizin / Technik mit DE-Spezialisierung.
- Track D (DaF-Lehre): Reviewer Goethe-Lehrer + Master DaF/DaZ-Absolvent.

### 5.2 Mittelpriorität

**Stage 1-3 Module**: Bewährte L2-Methodik; weniger experimentell. Review willkommen, aber weniger dringend.

**Anhänge A-L**: technisch-grammatical; Review für Aktualität + Vollständigkeit nützlich.

---

## 6. Review-Ergebnis-Verwertung

### 6.1 Iterativ

Jede Major-Release (v3.0+) integriert akkumulierte Reviews. Mantenedor verpflichtet sich:
- Quartalsweise: Review-Status-Bericht im CHANGELOG.
- Jährlich: zusammenfassende Diskussion der Peer-Review-Lessons im RELEASE-NOTES.
- Bei substantiellen Reviews (>5 Reviewer mit detailliertem Feedback): Major-Release-Anlass.

### 6.2 Publikation der Methode

Wenn 5+ Reviewer das Framework substantiell bewertet haben:
- Möglicher Aufsatz: "FATHOM-Deutsch — Methodologische Reflexion eines L2-Erwerbs-Frameworks für PT-falante adulto" — co-authored mit ausgewählten Reviewern.
- Submission an *Deutsch als Fremdsprache* (Zeitschrift) oder *Info DaF* (Goethe).
- Konferenzpräsentation an DGfS / DaF-Tagung.

---

## 7. Beispiele für Akquisitions-Anschreiben

### 7.1 Akademisches Anschreiben

```
Betreff: Anfrage Peer-Review FATHOM-Deutsch — L2-Erwerbs-Framework PT-DE

Sehr geehrte Frau Professorin / Sehr geehrter Herr Professor [Name],

mit großem Respekt vor Ihrer Forschung in [Spezialisierungsgebiet] möchte ich 
Sie um Peer-Review eines L2-Erwerbs-Frameworks bitten: FATHOM-Deutsch 
(github.com/NicolasDeNigris91/Deutly).

Das Framework ist eine systematische Curriculum-Architektur für PT-falante 
adulto-Lerner zum Erreichen von C2+ in germanística filosófica. 75 Module 
über 6 Stages + 11 Capstones; CC BY-NC 4.0.

Spezifisch interessiert mich Ihre Beurteilung von [Stage 4 / Track B / etc.] 
mit Fokus auf [strukturelle Korrektheit / methodische Verortung / 
Quellenkritik].

Voraussichtlicher Zeitaufwand: 8-12 Stunden über 4-6 Wochen.

Anerkennung: Ihr Name + Affiliation in CHANGELOG + RELEASE-NOTES + 
PEER-REVIEW-Verzeichnis (mit Ihrer Erlaubnis).

Anbei: Repository-Link + strukturierter Review-Bogen + Spezifika der 
gewünschten Review-Komponenten.

Ich würde mich sehr über Ihre Antwort + ggf. ein Treffen zur Diskussion 
freuen.

Mit besten Grüßen,
[Name]
[Kontakt]
```

### 7.2 DaF-Lehrer-Anschreiben

Variation für DaF-Lehrer am Goethe-Institut: zusätzlich Bezug auf Goethe-DLL-Tradition + Praxis-Relevanz für Erwachsenen-DaF.

---

## 8. Cross-references

- [COMMUNITY-GUIDELINES.md](COMMUNITY-GUIDELINES.md).
- [DECISION-LOG.md](DECISION-LOG.md) — strukturelle Entscheidungen.
- [CODE_OF_CONDUCT.md](../../CODE_OF_CONDUCT.md).
- [GitHub Discussions](https://github.com/NicolasDeNigris91/Deutly/discussions).

---

**Peer-Review ist Validierungs-Gate für FATHOM-Deutsch-Reife. Externe Linguisten-Beteiligung ist langfristige Voraussetzung für akademische Anerkennung des Frameworks.**
