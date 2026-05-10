# CHANGELOG — FATHOM-Deutsch

> Histórico de versões do framework. Cada release nota mudanças significativas. Referenciado em MENTOR.md §10.2.

---

## v3.0 — 2026-05-10 — MAJOR: Tradução DE Stage 1+2 vollständig + Multilingual (EN/ES/FR) + Comunidade-/Peer-Review-Governance + AnkiWeb-Export-Guide

**MAJOR VERSION BUMP.** v3.0 markiert die Vollständigkeit der internationalen Erschließung des Frameworks: alle Stage-1+2-Module ins DE adaptiert; English INDEX + Spanish/French READMEs; AnkiWeb-Publishing-Anleitung + Comunidade-Governance + Peer-Review-Prozess dokumentiert.

### Adicionado

#### Tradução DE — Stage 1 alle 10 Module + Stage 2 alle 9 Module (17 neue Adaptationen)

**Stage 1 (9 neue Adaptationen; ergänzt 01-01-de aus v2.5):**
- 01-02-de Kasussystem.
- 01-03-de Verbalsystem (Konjugation + Hilfsverb-Wahl + Trennbarkeit).
- 01-04-de Nominalflexion (Genus + Plural + Adjektivdeklination 3 Patterns).
- 01-05-de Pronominalsystem (5 Pron-Klassen + Tabellen).
- 01-06-de Wortbildung (Komposition 4 Klassen + Derivation Suffixe).
- 01-07-de Negation + Modalpartikeln Grundlagen.
- 01-08-de Phonetik (Auslautverhärtung + /r/-Distribution + /x/-/ç/ + Knacklaut + Vokal-Längen).
- 01-09-de Grundwortschatz (~2000 Lemmata + Anki-Aufbau-Strategie).
- 01-10-de Konversation Stage 1 (Tandem-Praxis + Replik-Frasen + Modalpartikel-Reaktivierung).

**Stage 2 (8 neue Adaptationen; ergänzt 02-01-de aus v2.5):**
- 02-02-de Konjunktiv I (indirekte Rede + Synkretismus-Lösung).
- 02-03-de Konjunktiv II (Irrealis + Höflichkeit + würde-Periphrase).
- 02-04-de Passivkonstruktionen (3 Passive + Modal+Passiv + Ersatzformen).
- 02-05-de Infinitivsätze (zu-Regel + um zu/damit + AcI).
- 02-06-de Funktionsverbgefüge (Vollverb-Äquivalente + Domänen).
- 02-07-de Modalverben (deontisch vs. epistemisch + epistemische Skala).
- 02-08-de Topik-Fokus-Struktur (Vorfeldwahl + Mittelfeld-Default + Skrambling + Akzent-Fokus).
- 02-09-de Lexik II (akademische Konnektoren + Argumentations-Verben gradiert + Kollokationen wissenschaftlich).

**Format**: konzise DE-Adaptationen (~1500-2500W); strukturell parallel zum PT-BR-Original; PT-BR bleibt Referenz.

**Cumulativo Tradução DE jetzt**: alle Stage 1+2 (19 Module) + Schlüssel-Module Stage 3-5 (3) + alle 29 Stage-6-Module nativ DE + 4 Meta-Docs DE + BEGRIFFS-GLOSSAR DE = ~50% framework cumulative.

#### Multilingual — EN + ES + FR

- **INDEX-EN.md** (`framework/00-meta/`): English parallel translation des INDEX. Vollständige Tabelle aller 5 Stages × 46 Modules + 7 Capstones + Stage 6 mit allen 4 Tracks. Hinweise zur Konsultation auf Englisch + Sequenz der Multilingual-Erweiterung.
- **README-ES.md** (raiz): Edición española del README — Marco de Adquisición de Alemán C2+ para hispanohablantes adultos. Estructura del marco + Filosofía + Cómo empezar + Licencia + Comunidad.
- **README-FR.md** (raiz): Édition française du README — Cadre d'Acquisition de l'Allemand C2+ pour francophones adultes. Structure + Philosophie + Comment commencer + Licence + Communauté.

#### Operational + Governance

- **ANKI-EXPORT-GUIDE.md** (`framework/00-meta/`): vollständige Anleitung zur Konversion der Anki-Starter-Decks ins AnkiWeb-Publishable-Format + Publishing-Workflow. Python-Skript für Markdown→TSV-Konversion. Deck-Hierarchie-Empfehlungen. Cloze-Karten-Spezialbehandlung. **Resolve SN-009 enhanced** (AnkiWeb-Deck-Publikations-Workflow dokumentiert).

- **COMMUNITY-GUIDELINES.md** (`framework/00-meta/`): Governance + Verhaltensrichtlinien für FATHOM-Deutsch-Comunidade. Hauptkanäle (Discord/Matrix geplant + GitHub Discussions aktiv + Cohort-Tracking-System Vision). Verhaltens-Richtlinien (intellektueller Fokus + Rigor über Brand + Honestidade über Niveau). Lesegruppen + Cohort-Programme + jährliche Online-Konferenz Vision. Beiträge zur Framework-Entwicklung. Forschung + wissenschaftliche Veröffentlichung. Mantenedor-Verantwortung. Krisensituationen. **Resolve SN-013 partial start** (Comunidade-Aufbau dokumentiert).

- **PEER-REVIEW-PROTOCOL.md** (`framework/00-meta/`): Protokoll zur systematischen Peer-Review durch externe DE-Linguisten/Germanisten/DaF-Spezialisten. Reviewer-Profile + Akquisitions-Strategien + Anreize. Strukturierter Review-Bogen (10 Sektionen + 5-Stufen-Empfehlung). Implementations-Workflow + Konflikt-Management zwischen Reviewern. Hochpriorität-Review-Bedarfsfelder (Stage 4 + Stage 5 + Stage 6 Tracks). Akquisitions-Anschreiben-Beispiele (akademisch + DaF-Lehrer). **Resolve SN-010 partial start** (Peer-Review-Validierung dokumentiert).

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-008 | P2 | experimento | Tradução DE | **Partial enhanced extended** (~50% framework; alle Stage 1+2 Module + Stage 6 + 4 Meta-Docs) |
| SN-009 | P2 | expansão | Anki-Decks pré-construídos | **Enhanced** (AnkiWeb-Publishing-Workflow dokumentiert; Decks bereit) |
| SN-010 | P2 | experimento | Peer-Review-Validierung | **Partial start** (Protokoll + Workflow dokumentiert; Reviewer-Akquisition kann beginnen) |
| SN-013 | P3 | experimento | Comunidade ativa | **Partial start** (COMMUNITY-GUIDELINES + Discord/Matrix-Kanal-Inventar geplant) |

### Estatísticas v3.0

```
Arquivos novos:                                 25
  Tradução DE Stage 1:                          9 (01-02 a 01-10)
  Tradução DE Stage 2:                          8 (02-02 a 02-09)
  INDEX-EN:                                     1 (English parallel)
  README-ES:                                    1 (Edición española)
  README-FR:                                    1 (Édition française)
  ANKI-EXPORT-GUIDE:                            1 (AnkiWeb-Publishing)
  COMMUNITY-GUIDELINES:                         1 (Comunidade-Governance)
  PEER-REVIEW-PROTOCOL:                         1 (Linguisten-Validierung)
  
Arquivos modificados:                            5
  INDEX.md (Tradução DE Sektion vollständig + Multilingual + Comunidade)
  + 4 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT, ROADMAP)

Cumulativo (após v3.0):
  Module total:                                  75 (Stage 1-5: 46 + Stage 6: 29)
  Capstones encadeados:                          11 (5 Stage 1-5 + 6 Stage 6)
  Capstone-Exemplares:                            5 (Aufklärung complete)
  Anhänge:                                       12 (A-L)
  Trilhas:                                        7
  Anki cards Stages 1-5:                         ~2900 (AnkiWeb-Publishing-bereit)
  Self-test Übungen Stages 1-5:                   150
  Tradução DE:                                    ~50% framework (alle Stage 1+2 + Schlüssel Stage 3-5 + alle Stage 6 + Meta-Docs + BEGRIFFS-GLOSSAR)
  Multilingual:                                   INDEX-EN + READMEs DE/EN/ES/FR
  Comunidade-Aufbau:                              dokumentiert (Discord/Matrix geplant)
  Peer-Review:                                    Protokoll dokumentiert
```

### Honestidade pedagógica

v3.0 markiert die **internationale Erschließungs-Vollständigkeit** des Frameworks. Aluno hat agora:

- **PT-BR-Original** für muttersprachliche Lerner.
- **DE-Adaptationen** für C1+ immersive Konsultation (~50% framework).
- **EN INDEX** für internationale Lerner.
- **ES + FR README-Intros** für hispano- + frankophone Lerner-Akquisition.
- **AnkiWeb-Publishing-Workflow** für direkten Anki-Import.
- **Comunidade-Governance** für sustained Comunidade-Aufbau.
- **Peer-Review-Protokoll** für externe Validierung.

**Wichtigste verbleibende Lücken nach v3.0:**
- Tradução DE 100% (Stage 3-5 verbleibende ~25 Module + Anhänge + Templates) → v4.0+.
- Vollständige EN-Übersetzung des Frameworks → v4.0+.
- ES/FR-Übersetzungen partielle (mehr als nur READMEs) → v4.0+.
- AnkiWeb-Decks tatsächlich publiziert (nicht nur Workflow dokumentiert) → praktischer Schritt.
- Discord/Matrix-Server tatsächlich aufgebaut (nicht nur Governance dokumentiert) → praktischer Schritt.
- 3-5 Peer-Reviews tatsächlich durchgeführt (nicht nur Protokoll dokumentiert) → praktischer Schritt.

v3.0+ (operationaler Schritt) wird die "tatsächliche Operation" der dokumentierten Strukturen umfassen — Server aufbauen, Decks publizieren, Reviewer akquirieren.

---

## v2.5 — 2026-05-10 — Stage 6 vollständig (Tracks C + D) + Tradução DE Module-Adaptation

### Adicionado

#### Stage 6 Track C — Fachsprache spezialisiert (3 Sub-Tracks; 13 arquivos)

**Sub-Track C1 — Rechtsdeutsch (5 arquivos):**
- 06-C1-1 BGB + ZPO + StGB-Auszüge (5 BGB-Bücher + 4-Methoden-Auslegung + § 211/212 Mord/Totschlag).
- 06-C1-2 Urteils-Deutsch (BGH + BVerfG; Konj. I in Tatbestand; Tenor-Formeln).
- 06-C1-3 Vertragsdeutsch + AGB (§§ 305-310 BGB; Salvatorische Klausel; Schriftform).
- 06-C1-4 Anwaltliches Schreiben (Klageschrift § 253 ZPO + Erwiderung + Mandanten-Korrespondenz + Gutachten).
- CAPSTONE-6-C1 Juristische Übersetzung oder Gutachten.

**Sub-Track C2 — Medizinisches Deutsch (4 arquivos):**
- 06-C2-1 Anatomie + Physiologie (Lat-DE-Lexikon + Patienten-Sprache vs. Fachsprache + Pathologie-Endungen).
- 06-C2-2 Diagnostik-Berichte + Arztbriefe (Anamnese-Struktur + Befund + ICD-10 + Akronyme klinisch).
- 06-C2-3 Forschungs-Publikation Medizin (IMRaD + Studien-Designs + Statistische Begriffe + Helsinki-Deklaration + DE-medizinische Zeitschriften).
- CAPSTONE-6-C2 Approbation oder medizinisch-wissenschaftliche Publikation.

**Sub-Track C3 — Technisches Deutsch (4 arquivos):**
- 06-C3-1 DIN-Normen-Sprache (DIN-Klassifikation + normative Modal-Verben + Standard-Architektur + FVG-Saturation).
- 06-C3-2 Patentschriften (DPMA + EPA + WIPO; "dadurch gekennzeichnet, dass" + Bezugszeichen-System).
- 06-C3-3 Technische Dokumentation (DIN EN 82079 Bedienungsanleitungen + Sicherheitshinweis-Formeln + API-Doku + Sicherheitsdatenblätter 16 Sektionen).
- CAPSTONE-6-C3 Technische Übersetzung publiziert.

#### Stage 6 Track D — Mentoring + DaF-Lehre (7 arquivos)

- 06-D-1 DaF-Methodik (SLA-Theorien Krashen/Swain/Bjork/Long/Selinker + Erwachsenen-DaF-Spezifika + Curriculum-Design).
- 06-D-2 Niveaustufen-Differenzierung (CEFR A1-C2 + Can-Do-Statements + Grammatik-Progression + Lehrtechniken pro Niveau).
- 06-D-3 Phonetik-Lehre (DE-Phonetik-Spezifika + PT-falante-Interferenzen + 5 Korrektur-Methoden + Critical Period).
- 06-D-4 Materialien + Curriculum (Lehrwerk-Verlage Hueber/Cornelsen/Klett/Schubert + Adoption vs. Eigenentwicklung + OER).
- 06-D-5 DaF-Diplom (Goethe-DLL + universitärer Master DaF/DaZ + ABRAPA + Berufliche Strukturen).
- 06-D-6 Mentoring institutionell (Universität + Sprachschule + Online + Privat + Tandem).
- CAPSTONE-6-D Eigene DaF-Praxis (30+ Lerner mentoriert + DaF-Zertifikat).

#### Tradução DE — 5 Module-Adaptationen (5 arquivos)

Parallel-Adaptationen Schlüsselmodule Stage 1-5:
- **01-01-de** Syntaktische Analyse — Topologisches Feldermodell (Stage 1).
- **02-01-de** Subordination — Subjunktoren + Verbletztstellung (Stage 2).
- **03-07-de** Wissenschaftliches Schreiben (Stage 3).
- **04-10-de** Hermeneutik klassischer Texte (Stage 4).
- **05-04-de** Eigene Stimme — Stilbildung (Stage 5).

Format: konzise DE-Adaptationen (~2000-2500W); strukturell parallel zum PT-BR-Original; PT-BR bleibt Referenz bei Inkonsistenzen.

### Modificado

#### STAGE-6-OUTLINE.md aktualisiert

- Status: "Track A + B vollständig in v2.0 implementiert; Track C + D vollständig in v2.5 implementiert. Stage 6 jetzt komplett (4 Tracks + 7 Capstones-6)."
- Track C + D Sektionen markiert mit ✅ implementiert.

#### DAG.md erweitert

- Globaler cross-Stage-Diagramm: Stage 6 Track C + D als parallele post-CAPSTONE-5-Knoten + 2 neue Capstones (CAPSTONE-6-C1/2/3 zusammenfasst + CAPSTONE-6-D).
- Stage 6 jetzt **alle 4 Tracks** im DAG sichtbar.

#### INDEX.md aktualisiert

- Stage 6 Sektion erweitert um Track C (3 Sub-Tracks) + Track D mit kompletten Modul-Tabellen.
- Total-Zeile aktualisiert: **75 Module + 11 Capstones** cumulativo.
- Tradução DE Sektion neu mit 5 Module-Adaptationen + Hinweise auf bestehende DE-Meta-Docs.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-008 | P2 | experimento | Tradução DE | **Partial enhanced** (3 Meta-Docs + BEGRIFFS-GLOSSAR + 5 Module-Adaptationen ~25%; alle Module v3.0) |
| SN-016 | P3 | expansão | Stage 6 Specialization | **DONE** (alle 4 Tracks A+B+C+D vollständig implementiert) |

### Estatísticas v2.5

```
Arquivos novos:                                 25
  Track C1 (Recht):                              5 (4 Module + CAPSTONE)
  Track C2 (Medizin):                            4 (3 Module + CAPSTONE)
  Track C3 (Technik):                            4 (3 Module + CAPSTONE)
  Track D:                                       7 (6 Module + CAPSTONE)
  Tradução DE Module-Adaptationen:               5 (Schlüsselmodule Stage 1-5)
  
Arquivos modificados:                            6
  STAGE-6-OUTLINE.md (Status v2.5 + Tracks C/D markiert)
  DAG.md (Tracks C + D + 2 neue Capstones)
  INDEX.md (Stage 6 erweitert + Total-Zeile + Tradução DE Sektion)
  + 4 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT, ROADMAP)

Cumulativo (após v2.5):
  Module total:                                  75 (Stage 1-5: 46 + Stage 6: 29)
  Capstones encadeados:                          11 (5 Stage 1-5 + 6 Stage 6: A + B + C1 + C2 + C3 + D)
  Capstone-Exemplares:                            5 (CAPSTONE-1+2+3+4+5 sobre Aufklärung)
  Anhänge:                                       12 (A-L)
  Trilhas:                                        7
  Anki cards Stages 1-5:                         ~2900
  Self-test Übungen Stages 1-5:                   150
  Tradução DE:                                    INDEX + MENTOR + STUDY-PROTOCOL + BEGRIFFS-GLOSSAR + 13 Stage-6-Module + 5 Stage-1-5-Module-Adaptationen (~25%)
  Mermaid-Diagramme:                              15+ (Stage 6 Tracks C + D in globalem Diagramm)
```

### Honestidade pedagógica

v2.5 schließt die Stage-6-Implementation ab. Aluno hat agora **4 vollständige Spezialisierungs-Tracks**:

- **Track A** → professionelle Übersetzungs-Karriere (literarisch + philosophisch + juristisch + kulturwissenschaftlich + Lektorat).
- **Track B** → akademische Promotion in DE-Akademie (Forschungsfrage + Monographie + Konferenz + Netzwerk + Drittmittel + Habilitation).
- **Track C** → Fachsprach-Spezialisierung (Recht / Medizin / Technik) für Berufs-Praxis in DE/AT/CH.
- **Track D** → DaF-Lehre + Mentoring (Goethe-Institut + Universität + Privat).

**Wichtigste verbleibende Lücken nach v2.5:**
- Tradução DE 100% (alle Module + Anhänge + Templates; v3.0 geplant).
- Comunidade-Aufbau (Discord/Matrix; SN-013).
- Peer-Review von DE-Linguisten (cf. SN-010).
- AnkiWeb-Deck publiziert.
- Multilingual Framework (EN/ES/FR-Übersetzungen; v3.0+).

---

## v2.0 — 2026-05-09 — Major Release: CAPSTONE-5 exemplar + Stage 6 Tracks A + B vollständig

**Major Version Bump.** v2.0 markiert das Ende des Base-Curriculums (Stages 1-5 + 5 Capstones-Exemplares vollständig) + den Beginn der Spezialisierungs-Tracks (Stage 6 Track A + B operativ implementiert).

### Adicionado

#### CAPSTONE-5-AUFKLAERUNG-EXEMPLAR — abschließendes Veröffentlichungs-Modell

- **CAPSTONE-5-AUFKLAERUNG-EXEMPLAR.md** (`framework/00-meta/examples/`): Worked Example einer publizierbaren Veröffentlichung (~8000W; *Merkur*-Format). 6 Sektionen: I Eingangs-Beobachtung; II Was Kant meinte (Re-Lektüre 1784); III Die zwei Aufklärungen — Adorno und Habermas; IV Aufklärung als Übung — eine dritte Position (Foucault-Anschluss); V Aufklärung in der postfaktischen Zeit (3 Lebenswelt-Beispiele); VI Schluss — Aufklärung als kleine Beharrlichkeit. Plus Anhang mit submissions-konformer Methodik (Stilfeature-Markierung, Korrekturschleife dokumentiert v1→v2→v3, Bewertung ~92%, Submissions-Materialien für Merkur). **Schließt SN-014 vollständig** (alle 5 Capstones-Exemplares done; Erkenntnisprojekt-Reihe v0→v4 vollständig).

#### Stage 6 Track A — Übersetzungswissenschaft + Praxis (vollständig implementiert)

7 Dateien in `framework/06-spezialisierung/`:

- **06-A-1 Übersetzungstheorie vertieft** — Schleiermacher / Benjamin / Berman / Steiner / Venuti gelesen + analysiert; eigene translatologische Position (~3000-5000W) verteidigt.
- **06-A-2 Literarische Übersetzung PT↔DE** — Mann + Machado de Assis doppelte Übersetzung + Vergleich mit existierenden Übersetzungen.
- **06-A-3 Philosophische Übersetzung** — Heidegger nach PT (*SuZ* §§1–7 + §31); Diskussion 3 PT-Übersetzungs-Wege für *Dasein* (Beibehaltung / Pre-sença Schuback / Existência).
- **06-A-4 Juristische Übersetzung** — BGB-Auszüge + GG/CRFB vergleichend; funktional-äquivalente Übersetzung; Stilkonvention Beamtendeutsch + Juristendeutsch.
- **06-A-5 Kulturwissenschaftliche Übersetzung** — Adorno + Bourdieu + Habermas; Begriffs-Tradition (Bildungsbürger / Halbbildung / Habitus / Distinktion / Lebenswelt).
- **06-A-6 Lektorat + Redaktion** — 4 Lektorats-Phasen (eigenes / Peer / Verlagslektor / Druck); Argumentations-Strategie mit Verlagslektor; Übersetzer-Lektor-Kommunikation.
- **CAPSTONE-6-A Publizierte Buchübersetzung** — vollständige Buchübersetzung (~150-300 S.) in etabliertem Verlag publiziert. Anschluss-Karrieren: Freier Literaturübersetzer / Verlagslektor / Akademischer Übersetzer / Konferenzdolmetscher.

#### Stage 6 Track B — Germanistische Forschung Promotion-Vorbereitung (vollständig implementiert)

8 Dateien in `framework/06-spezialisierung/`:

- **06-B-1 Forschungsfrage-Entwicklung** — Promotion-würdige Forschungsfrage + Exposé (~15-30 S.) gemäß DE-Akademie-Standard; 4 Kriterien (Originalität, Bearbeitbarkeit, Methodische Konsistenz, Anschlussfähigkeit).
- **06-B-2 Wissenschaftliches Schreiben spezialisiert** — Monographie-Format (~400-600 S.); Pilot-Kapitel (~40-60 S.); Architektur über Kapitel; Längen-Management.
- **06-B-3 Konferenz-Praxis** — Conference-Paper Long/Short-Format; Akademie-Vortrag (15-20 min); Reviewing eigene + fremde Arbeit; Konferenz-Inventar (DGfS, Germanistenverband, DGPhil, IVG, Hegel-Kongress).
- **06-B-4 Akademisches Netzwerk** — Fachgesellschaften DE-Akademie; akademische Korrespondenz-Konventionen DE; Reviewing für Journals + Konferenzen; Sub-Disziplinen-Engagement.
- **06-B-5 Promotionsantrag** — DFG / FWF / SNF / DAAD / Stiftungen-Inventar; Antrag-Struktur (Anschreiben + Lebenslauf + Exposé + Empfehlungs- + Doktorvater-Bestätigungs-Schreiben); 5-Jahres-Plan + Stipendien-Wahl.
- **06-B-6 Drittmittel + Forschungs-Praxis** — DFG-Drittmittel-Inventar; Forschungsdaten-Management (FAIR-Prinzipien + DMP); Open-Access-Strategie + CC-Lizenzen; Forschungs-Ethik (Plagiat + DSGVO + Ethik-Kommissionen); Reproduzibilitäts-Krise.
- **06-B-7 Habilitation (optional)** — Habilitations-Schrift-Architektur; Lehrerfahrung + Lehrportfolio; Karriere-Alternativen (Habilitation vs. Junior-Professur vs. internationale Karriere).
- **CAPSTONE-6-B Promotion-Beginn** — Doktorvater-Wahl + Vertrag + 1. Jahres-Berichts-Manuskript (~30-50 S.); Forschungs-Roadmap. Anschluss-Karrieren: Postdoc / Junior-Professur / Habilitation / Forschungsstelle / Stiftungs-Karriere / international.

### Modificado

#### STAGE-6-OUTLINE.md aktualisiert

- Status-Markierung: "Track A + Track B vollständig implementiert in v2.0".
- Track A + B Modul-Sektionen markiert als ✅ implementiert.
- Tracks C + D bleiben Blueprint für v2.5+.

#### DAG.md erweitert

- Globaler cross-Stage-Diagramm: Stage 6 Track A + Track B als parallele post-CAPSTONE-5-Knoten + 2 neue Capstones (CAPSTONE-6-A + CAPSTONE-6-B).
- **Stage 6 Track A Sub-DAG** novo: Mermaid-Diagramm mit 6 Modulen + CAPSTONE-6-A; cross-reference zu Stage 5 (05-03 Übersetzung).
- **Stage 6 Track B Sub-DAG** novo: Mermaid-Diagramm mit 7 Modulen + CAPSTONE-6-B; cross-references zu Stage 4-5 (CAPSTONE-4 + 05-02 Wissenschaftssprache).

#### INDEX.md aktualisiert

- Header inkludiert CAPSTONE-5 exemplar + Stage 6 Tracks-Verweise.
- Stage 6 Tabelle hinzugefügt mit Track A + Track B Modul-Listen + Saídas.
- Total-Zeile aktualisiert: **59 Module + 7 Capstones** cumulativo.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-014 | P3 | expansão | Capstones exemplares | **DONE** (alle 5 Capstones-Exemplares 1+2+3+4+5 sobre Aufklärung complete) |
| SN-016 | P3 | expansão | Stage 6 Specialization | **Partial enhanced** (Track A + Track B vollständig; Track C + D bleiben Blueprint v2.5+) |

### Estatísticas v2.0

```
Arquivos novos:                                 16
  CAPSTONE-5-AUFKLAERUNG-EXEMPLAR.md             1 (~8000W publizierbarer Aufsatz)
  Track A:                                       7 (6 Module + CAPSTONE-6-A)
  Track B:                                       8 (7 Module + CAPSTONE-6-B)
  
Arquivos modificados:                            6
  INDEX.md (header + Stage 6 Sektion + Total-Zeile)
  DAG.md (globaler cross-Stage + 2 Sub-DAGs Stage 6)
  STAGE-6-OUTLINE.md (Status v2.0 + Track A/B markiert)
  + 4 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT, ROADMAP)

Cumulativo (após v2.0):
  Module total:                                  59 (Stage 1-5: 46 + Stage 6: 13)
  Capstones encadeados:                           7 (5 Stage 1-5 + 2 Stage 6)
  Anhänge:                                       12 (A-L; unverändert)
  Trilhas:                                        7 (unverändert)
  Anki cards Stages 1-5:                         ~2900 (unverändert seit v1.9)
  Self-test Übungen Stages 1-5:                   150 (unverändert seit v1.9)
  Capstone-Exemplares:                             5 (CAPSTONE-1+2+3+4+5 sobre Aufklärung)
  Tradução DE:                                    INDEX + MENTOR + STUDY-PROTOCOL + BEGRIFFS-GLOSSAR + Stage 6 Module (~25%)
  Mermaid-Diagramme:                              15 (13 + 2 Sub-DAGs Stage 6)
```

### Honestidade pedagógica

v2.0 markiert eine **major release**: Base-Curriculum (Stages 1-5) ist mit allen 5 Capstones-Exemplares + 5 Anki-Decks + 5 Self-test-Banks + 4 Meta-Docs in DE komplett. Stage 6 Spezialisierungs-Tracks (Übersetzung + Forschung) sind operativ verfügbar — aluno completando CAPSTONE-5 hat klare Wege:

- **Track A** → professionelle Übersetzungs-Karriere (Verlagskooperation, Buchpublikation, Fachübersetzung).
- **Track B** → akademische Karriere (Promotion in DE-Akademie, Konferenz-Engagement, Habilitation oder Junior-Professur).

Tracks C (Fachsprache spezialisiert) + D (Mentoring + DaF-Lehre) bleiben für v2.5+ — nicht weil sie weniger wichtig sind, sondern weil C + D weniger universell anwendbar sind (C ist berufsspezifisch; D erfordert Lehr-Anbindung).

**Wichtigste Lücken nach v2.0:**
- Tracks C + D Implementation (v2.5).
- Tradução DE 100% (alle Module + Anhänge + Templates; v2.5).
- Comunidade-Aufbau (Discord/Matrix; cf. SN-013).
- Peer-Review von DE-Linguisten (cf. SN-010).
- AnkiWeb-Deck publiziert.

---

## v1.9 — 2026-05-09 — Empirische Erweiterung Stage 5 + CAPSTONE-4 exemplar

### Adicionado

#### Stage-5-Apparat operacional (encerrando a série Anki + Self-test 1-5)

- **ANKI-STARTER-DECK-STAGE-5.md** (`framework/00-meta/`): ~400 frasal cards organizados pelos 7 módulos do Stage 5 (05-01 Politische Sprache, 05-02 Wissenschaftssprache Habermas/Luhmann/Adorno, 05-03 Übersetzungstheorie + Praxis, 05-04 Eigene Stimme + Stilbildung, 05-05 Public Output, 05-06 Mentoring, 05-07 Goethe C2/TestDaF). Cards Konstellation-orientiert (Stage-5-Charakter): mehr Tiefe pro Karte, weniger Karten total. **Resolve SN-009 vollständig** (Stages 1-5 alle done; ~2900 cards cumulativo).
- **SELF-TEST-BANK-STAGE-5.md** (`framework/00-meta/`): 23 Übungen + 1 Stage-Final-Mini-Aufsatz (~400W). Schwierigkeit ★/★★/★★★. Cada Übung: Frage + Erwartete Lösung + Begründung + Verweis. Übungen vermehrt Output-orientiert (Plenarrede-Skript, Adorno-Stil-Imitation, PT↔DE-Übersetzung, Mentee-Diagnose, Goethe-Umarbeitung). Vorbereitung explizit für CAPSTONE-5.

#### Worked example novo — CAPSTONE-4-AUFKLAERUNG-EXEMPLAR

- **CAPSTONE-4-AUFKLAERUNG-EXEMPLAR.md** (`framework/00-meta/examples/`): vollständiges Worked Example einer korpusbasierten Begriffsanalyse (~30 pp.) gemäß BEGRIFFSANALYSE-TEMPLATE. Methodische Trias (diachron + synkron + hermeneutisch) integriert. **35 Primärbelege** systematisch geschichtet nach 5 Sub-Traditionen (Kant-aufklärerisch, Hegel-rekonstruktiv, Adorno-kritisch, Habermas-rekonstruktiv-kritisch, Foucault-genealogisch). **12 Sekundärquellen** für Forschungsstand. **DWDS-Frequenzverlauf 1700–2025** mit 8-Phasen-Periodisierung. **DWDS-Wortprofil-Top-30-Kollokationen** mit Cluster-Analyse. **Konstellations-These** (Aufklärung als simultan-konstellatorische Multi-Tradition statt sukzessiv-diakronisch abgelöst). Methodenkritik integriert (Korpus-Beschränkungen + hermeneutische Grenzen + wirkungsgeschichtliche Selbstreflexion). Korrekturschleife dokumentiert (v1→v2→v3, Bewertung ~92%). **Resolve SN-014 partial enhanced** (Capstones 1+2+3+4 done; -5 in v2.0).

### Modificado

#### INDEX.md atualizado

- Header inkludiert Anki Stage 5 + Self-Test Stage 5 + CAPSTONE-4 exemplar.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-009 | P2 | expansão | Anki-Decks pré-construídos | **DONE** (Stages 1-5 alle complete; ~2900 cards cumulativo) |
| SN-014 | P3 | expansão | Capstones exemplares | **Partial enhanced** (CAPSTONE-1+2+3+4 done; -5 em v2.0) |

### Estatísticas v1.9

```
Arquivos novos:                                  3
  ANKI-STARTER-DECK-STAGE-5.md                    1 (~400 cards)
  SELF-TEST-BANK-STAGE-5.md                       1 (~30 Übungen)
  CAPSTONE-4-AUFKLAERUNG-EXEMPLAR.md              1 (~30pp Worked Example)
  
Arquivos modificados:                            5
  INDEX.md (header)
  + 4 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT, ROADMAP)

Conteúdo cumulativo:
  Anki cards Stages 1+2+3+4+5:                   ~2900 cards (todos Stages done!)
  Self-test Übungen Stages 1+2+3+4+5:             150 Übungen (todos Stages done!)
  Capstone-Exemplares:                              4 (CAPSTONE-1+2+3+4 sobre Aufklärung)
  Tradução DE:                                     INDEX + MENTOR + STUDY-PROTOCOL + BEGRIFFS-GLOSSAR (~15%)
  Module total (unverändert):                     46
  Anhänge (unverändert):                          12 (A-L)
  Trilhas (unverändert):                           7
```

### Honestidade pedagógica

v1.9 schließt die **Stage-Apparat-Reihe** ab: alle 5 Stages haben jetzt Anki-Deck (~2900 cards cumulativo) + Self-test-Bank (~150 Übungen). Aluno completando Stages 1-5 mit kompletten Anki + Self-test entra em CAPSTONE-5 com gesamtem Stage-1-bis-5-Apparat ativo. CAPSTONE-4 exemplar demonstra methodischen Standard für korpusbasierte Begriffsanalyse: nicht nur Aufsatz argumentativ (CAPSTONE-2) oder wissenschaftlich (CAPSTONE-3), sondern korpus-empirisch fundierte Synthese mit Methodenkritik.

**Wichtigste Lücke nach v1.9**: CAPSTONE-5 exemplar (Veröffentlichung; ~5000-12000W). Geplant v2.0 zusammen mit Stage 6 Tracks.

---

## v1.8 — 2026-05-09 — Empirische Erweiterung Stage 4 + Tradução DE meta-docs

### Adicionado

#### Stage-4-Apparat operacional

- **ANKI-STARTER-DECK-STAGE-4.md** (`framework/00-meta/`): ~600 frasal cards organizados pelos 10 módulos do Stage 4 (04-01 Historische Linguistik, 04-02 Etymologie, 04-03 Variationslinguistik, 04-04 Generative Syntax, 04-05 Formale Semantik, 04-06 Diskursanalyse, 04-07 Textlinguistik, 04-08 Korpuslinguistik, 04-09 Kontrastive Linguistik PT-DE, 04-10 Hermeneutik klassischer Texte). Cards por sub-tópico com Belege primários (Grimm, Pfeifer, Frege, Foucault, Heidegger, Gadamer) + Cross-Module-Karten (Generative+Hermeneutik; Korpus+Etymologie+Begriffsanalyse; Kontrastive+Generative) + Stage-4-Cloze-Diagnose. Anki-Tag-Hierarchie + Empfehlung der Karten-Reihenfolge. **Resolve SN-009 partial** (Stages 1+2+3+4 done; Stage 5 in v1.9).
- **SELF-TEST-BANK-STAGE-4.md** (`framework/00-meta/`): 30 Übungen com Lösungen (3 pro Modul × 10 Module + 2 Cross-Module + 1 Stage-Final-Skizze ~300W). Schwierigkeit ★/★★/★★★. Cada Übung: Frage + Erwartete Lösung + Begründung + Verweis. Vorbereitung explizit für CAPSTONE-4 (korpusbasierte Begriffsanalyse).

#### Tradução DE — Meta-docs paralelas

- **MENTOR-DE.md** (raiz): Erstübersetzung des [MENTOR.md](MENTOR.md) (Mentoring-Protokoll) ins Deutsche. Vollständige Strukturerhaltung (4 Modi + 4-Schicht-Loop der Verfeinerung + 3 Tore + Sprach-/Stilregel + 7 nicht-verhandelbare Prinzipien + Anti-Burlung-Tabelle). Zielgruppe: C1+ Self-Mentoring auf Deutsch oder Tandem mit deutschsprachigem Mentor.
- **STUDY-PROTOCOL-DE.md** (raiz): Erstübersetzung des [STUDY-PROTOCOL.md](STUDY-PROTOCOL.md) (Kognitive Techniken für L2) ins Deutsche. Vollständige Strukturerhaltung (12 Techniken: Active Recall, Spaced Repetition mit Anki, Comprehensible Input+1, Output Hypothesis, Shadowing, Feynman, Deliberate Practice, Spaced Re-Test, Fehler-Journal, Reading Primary Sources, Cohort/Peer, Sustainability checkpoints + tägliches Mindest-Paket).

### Modificado

#### INDEX.md atualizado

- Header inkludiert Anki Stage 4 + Self-Test Stage 4 + MENTOR-DE + STUDY-PROTOCOL-DE-Verweise.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-008 | P2 | experimento | Tradução do framework para DE | **Partial enhanced** (INDEX + MENTOR + STUDY-PROTOCOL done; BEGRIFFS-GLOSSAR já em DE; alle Module em v2.5+) |
| SN-009 | P2 | expansão | Anki-Decks pré-construídos | **Partial enhanced** (Stages 1+2+3+4 done; Stage 5 v1.9) |

### Estatísticas v1.8

```
Arquivos novos:                                  4
  ANKI-STARTER-DECK-STAGE-4.md                    1 (~600 cards)
  SELF-TEST-BANK-STAGE-4.md                       1 (~30 Übungen)
  MENTOR-DE.md                                    1 (tradução DE paralela MENTOR)
  STUDY-PROTOCOL-DE.md                            1 (tradução DE paralela STUDY-PROTOCOL)
  
Arquivos modificados:                            5
  INDEX.md (header)
  + 4 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT, ROADMAP)

Conteúdo cumulativo:
  Anki cards Stages 1+2+3+4:                     ~2500 cards cumulativo
  Self-test Übungen Stages 1+2+3+4:               120 Übungen cumulativo
  Tradução DE:                                     INDEX + MENTOR + STUDY-PROTOCOL (~15% framework)
  Module total (unverändert):                     46
  Anhänge (unverändert):                          12 (A-L)
  Trilhas (unverändert):                           7
```

### Honestidade pedagógica

v1.8 não adiciona novas estruturas conceituais — replica em Stage 4 o padrão operacional v1.6/v1.7 + estende a frente de tradução DE com os 2 dossiês procedurais centrais (MENTOR + STUDY-PROTOCOL). Aluno completando Stages 1-4 com Anki + Self-test entra em CAPSTONE-4 (~30pp korpusbasierte Begriffsanalyse) com Generative-Werkzeug + Hermeneutik-Tradition + Korpus-Praxis + Etymologie-Kompetenz ativos. MENTOR-DE + STUDY-PROTOCOL-DE permitem que aluno C1+ no Modus B (Tandem) ou Modus A (Self-Mentor) operiere komplett auf Deutsch.

---

## v1.7 — 2026-05-09 — Empirische Erweiterung Stage 3 + Tradução DE INDEX

### Adicionado

#### Stage-3-Apparat operacional

- **ANKI-STARTER-DECK-STAGE-3.md** (`framework/00-meta/`): ~700 frasal cards organizados pelos 10 módulos do Stage 3 (03-01 Nominal vs. verbal, 03-02 Register, 03-03 Idiomatik, 03-04 Pragmatik, 03-05 Modalpartikeln saturation, 03-06 Stilfiguren, 03-07 Wissenschaftliches Schreiben, 03-08 Journalistischer Stil, 03-09 Lexik III geisteswissenschaftlich, 03-10 Hörverstehen colloquial). Cards por sub-tópico + Cross-Module-Karten (Register+Stilfiguren; Modalpartikel+Pragmatik; Stilfigur+Lexik III) + Stage-3-Cloze-Diagnose. Anki-Tag-Hierarchie + Empfehlung der Karten-Reihenfolge. **Resolve SN-009 partial** (Stages 1+2+3 done; Stages 4-5 in v1.8-v1.9).
- **SELF-TEST-BANK-STAGE-3.md** (`framework/00-meta/`): 30 Übungen com Lösungen (3 pro Modul × 10 Module + 2 Cross-Module + 1 Stage-Final-Aufsatz ~250W). Schwierigkeit ★/★★/★★★. Cada Übung: Frage + Erwartete Lösung + Begründung + Verweis. Vorbereitung explizit für CAPSTONE-3.

#### Tradução DE — INDEX paralela

- **INDEX-DE.md** (`framework/00-meta/`): Erstübersetzung des [INDEX.md](INDEX.md) ins Deutsche. Vollständige Tabelle aller 5 Stages × 46 Module + alle 12 Anhänge + 8 Templates + 3 Worked Examples + DAG (textual ASCII + Mermaid) + Capstone-Erkenntnisprojekt + Hinweise zur DE-Konsultation. Nicht-Substitut des PT-BR-Originals; bei Inkonsistenzen gilt PT-BR. **Resolve SN-008 partial start**.

### Modificado

#### INDEX.md atualizado

- Header inkludiert Anki Stage 3 + Self-Test Stage 3 + INDEX-DE-Verweis.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-008 | P2 | experimento | Tradução do framework para DE | **Partial start** (INDEX-DE done; MENTOR + STUDY-PROTOCOL em v1.8) |
| SN-009 | P2 | expansão | Anki-Decks pré-construídos | **Partial enhanced** (Stages 1+2+3 done; Stages 4-5 v1.8-v1.9) |

### Estatísticas v1.7

```
Arquivos novos:                                  3
  ANKI-STARTER-DECK-STAGE-3.md                    1 (~700 cards)
  SELF-TEST-BANK-STAGE-3.md                       1 (~30 Übungen)
  INDEX-DE.md                                     1 (tradução DE paralela INDEX)
  
Arquivos modificados:                            1
  INDEX.md (header)
  + 4 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT, ROADMAP)

Conteúdo cumulativo:
  Anki cards Stages 1+2+3:                       ~1900 cards cumulative
  Self-test Übungen Stages 1+2+3:                 90 Übungen cumulative
  Tradução DE:                                     INDEX (~5%)
  Module total (unverändert):                     46
  Anhänge (unverändert):                          12 (A-L)
  Trilhas (unverändert):                           7
```

### Honestidade pedagógica

v1.7 não adiciona novas estruturas conceituais — replica em Stage 3 o padrão operacional v1.6 + abre frente de tradução DE com INDEX. Aluno completando Stages 1-3 com Anki + Self-test entra em CAPSTONE-3 (5000W wissenschaftlich) com Modalpartikel-Saturation + Stilfiguren-Inventar + Wissenschaftsdeutsch-Konnektoren + Lexik III ativos. INDEX-DE permite que aluno C1+ faça Stage-Navigation em modo imersivo.

---

## v1.6 — 2026-05-09 — Empirische Erweiterung Stage 2 + Konsistenz-Auditoria

### Adicionado

#### Stage-2-Apparat operacional

- **ANKI-STARTER-DECK-STAGE-2.md** (`framework/00-meta/`): ~700 frasal cards organizados pelos 9 módulos do Stage 2 (02-01 Subordination, 02-02 Konjunktiv I, 02-03 Konjunktiv II, 02-04 Passivkonstruktionen, 02-05 Infinitivsätze, 02-06 FVG, 02-07 Modalverben, 02-08 Topik-Fokus, 02-09 Lexik II). Cards-Cluster por Modul-Sektion + Cross-Module-Karten + Stage-2-Cloze-Diagnose. Anki-Tag-Hierarchie + Empfehlung der Karten-Reihenfolge. **Resolve SN-009 partial** (Stage 2 fertiggestellt; Stages 3-5 in v1.7-v1.9).
- **SELF-TEST-BANK-STAGE-2.md** (`framework/00-meta/`): 30 Übungen com Lösungen (3 pro Modul × 9 Module + 2 Cross-Module + 1 Stage-Final-Aufsatz ~200W). Schwierigkeit ★/★★/★★★. Cada Übung: Frage + Erwartete Lösung + Begründung + Verweis auf Modul-Sektion. Vorbereitung explizit für CAPSTONE-2.

### Korrigido

#### SN-005 — Cross-Reference-Auditoria sistemática

- Auditoria automatizada via Subagent: 592 links em 112 .md-files verificados.
- **1 link quebrado real korrigiert**: `STAGE-6-OUTLINE.md:351` referenzierte `ROADMAP.md` mit relativem Pfad statt `../../ROADMAP.md` (root-Position). Fixiert.
- 1 Placeholder im Template `MODULE-TEMPLATE.md:158` — kein Fix nötig (Template-Eigenschaft).

#### SN-006 — Ortografia + Dash-Auditoria

- Auditoria automatizada via Subagent: 120+ .md-files gescannt.
- **0 Verstöße** ß/ss em prosa autoral moderna (Categoria A) — confirmação: bereinigung in v1.2 war vollständig; bestand seit Repository-Anfang.
- **Citações historischer Texte preservaram orthographia originalis** (Categoria B): Brüder Grimm 1857, Kafka 1915, Kant 1787, Luther 1530 — alle Daß/mußte/usw. korrekt erhalten.
- **66 dash-fixes** in 17 Dateien: hyphen `-` → en-dash `–` in Datums-Ranges (z.B. `1923-29` → `1923–29`, `1927-1998` → `1927–1998`, `1750-1800` → `1750–1800`). Betroffene Dateien:
  - `framework/00-meta/BEGRIFFS-GLOSSAR.md` (21)
  - `framework/00-meta/BEGRIFF-INDEX.md` (7)
  - `framework/00-meta/CAPSTONE-EVOLUTION.md` (2)
  - `framework/05-meisterschaft/05-04-eigene-stimme.md` (6 + 1 manual)
  - `framework/05-meisterschaft/05-02-wissenschaftssprache.md` (4 + 1 open-range manual)
  - `framework/04-system/04-01-historische-linguistik.md` (5)
  - `framework/03-stil/03-09-lexik-3.md` (5)
  - `framework/04-system/04-10-hermeneutik.md` (4)
  - `framework/03-stil/03-08-journalistischer-stil.md` (3)
  - `framework/02-struktur/02-05-infinitivsaetze.md` (2)
  - `framework/03-stil/03-03-idiomatik.md` (2)
  - `framework/04-system/04-02-etymologie.md` · `framework/03-stil/03-06-stilfiguren.md` · `framework/04-system/04-05-formale-semantik.md` · `framework/03-stil/03-10-hoerverstehen.md` · `framework/04-system/04-07-textlinguistik.md` · `framework/04-system/04-06-diskursanalyse.md` (1 cada).
- ISO-Daten (`2026-05-09`) werden konvenções-gemäß weiter mit hyphen-minus geschrieben (norm).

### Modificado

#### DAG.md erweitert

- Stage 1 Mermaid-Diagramm mit Modul **01-10 Konversation** als parallel-Knoten + Verweis-Konvention.
- Stage 3 Mermaid-Diagramm mit Modul **03-10 Hörverstehen colloquial** + Cross-Refs zu 03-02/03-04/03-05.
- Module-counts updated: Stage 1 (9 → 10) + Stage 3 (9 → 10) im globalen cross-Stage-Diagramm.
- **Caminho E novo** — Konversation → Hörverstehen → Public Output (01-08 → 01-10 → 03-02 → 03-04 → 03-10 → 05-04 → 05-05): caminho crítico für Trilha G (Auswandern). Schließt die explizite Lücke von "Tagesschau-Standard ohne traseira colloquial".

#### INDEX.md atualizado

- Header inclui ANKI-STARTER-DECK-STAGE-2 + SELF-TEST-BANK-STAGE-2.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-005 | P1 | correção | Auditoria consistência cross-module | **Done** (Vollständige sistemática Auditoria; 1 fix) |
| SN-006 | P1 | melhoria | Edits ortográficos + Dash-Audit | **Done** (Vollständige Auditoria; 66 dash-fixes; 0 ß/ss-Verstöße) |
| SN-009 | P2 | expansão | Anki-Decks pré-construídos | **Partial enhanced** (Stages 1+2 done; Stages 3-5 in v1.7-v1.9) |

### Estatísticas v1.6

```
Arquivos novos:                                  2
  ANKI-STARTER-DECK-STAGE-2.md                    1 (~700 cards)
  SELF-TEST-BANK-STAGE-2.md                       1 (~30 Übungen)
  
Arquivos modificados:                          ~22
  DAG.md (Stage 1 + Stage 3 Mermaid + Caminho E)
  INDEX.md (header)
  STAGE-6-OUTLINE.md (1 link fix)
  17 Dateien (en-dash sweep)
  3 meta-docs (CHANGELOG, RELEASE-NOTES, SPRINT-NEXT)
  ROADMAP.md (status v1.5 → v1.6)

Conteúdo cumulativo:
  Anki cards Stage 1 + 2:                        ~1200 cumulative
  Self-test Übungen Stage 1 + 2:                  60 cumulative
  Module total (unverändert):                     46
  Anhänge (unverändert):                          12 (A-L)
  Trilhas (unverändert):                          7
  Cross-references valid:                          592 (auditiert; 100% gültig)
  Mermaid-Diagramme cumulativo:                   13 (1 master + 5 stages + 5 caminhos críticos + 2 augmentado)
```

### Honestidade pedagógica

v1.6 não adiciona conteúdo conceitual novo — adiciona **operacionalidade aprofundada para Stage 2**: o aluno que conclui Stages 1 + 2 com Anki-Stage-2 + Self-test-Stage-2 entra em CAPSTONE-2 com vocabulário argumentativo + drill-Konjunktiv-II/Passiv/FVG ativo, sem necessidade de improvisar próprio Anki-Aufbau apenas com material de Stage 1. Próximas releases (v1.7-v1.9) replicam esta empirische Erweiterung em Stages 3-5.

---

## v1.5 — 2026-05-09 — Konversations-Lücke geschlossen: 2 Anhänge + 2 Module + Trilha G

### Adicionado

#### Anhänge novos (2)

- **ANHANG K — Alltagskommunikation** (`framework/00-meta/anhaenge/`): 5 Bereiche (Telefon, Service, Small Talk, Behörden, Notfälle) com Skripten + Beispiel-Dialogen + Stilstufen-Markierung. Inclui Trinkgeld-Konvention DE, Steuerklassen-Übersicht, Notrufnummern (110/112/116-117), kanonische Phrasen für Anmeldung/Krankenversicherung/Aufenthaltstitel.
- **ANHANG L — Dialekte + Soziolekte**: 4 Hauptdialekte (Berlinerisch, Bayrisch, Wienerisch, Schwyzerdütsch) + Plattdeutsch + 3 Soziolekte (Jugendsprache, Kiezdeutsch, Beamtendeutsch). Cada um mit lautlichen + lexikalischen Eigenheiten + Klassischen Phrasen + Beispiel-Dialogen + Hörbeispielen-URLs + Diagnostik für Lerner.

#### Module novos (2 — Stage 1 + Stage 3 erweitern auf 10 Module)

- **Modul 01-10 — Konversation Stage 1** (`framework/01-fundamente/`): einziges Stage-1-Modul, das **non-substituierbar** durch Markdown allein ist; verlangt Tandem-Praxis (Modus B). Inclui Output-Hypothesis (Swain 1985), 3 Modi der L2-Konversations-Praxis, Replik-Frasen (Bausteine) + Repliken-Skripte (Sequenzen), Modalpartikel-Reaktivierung (5 unverzichtbare Modalpartikeln Stage 1: doch/ja/mal/denn/eigentlich), Pausen-Wörter-Reaktivierung (also/naja/tja vs. PT então/tipo), Tempo-Erwartung Stage 1-5, Diagnostik für Stage-1-Konversations-Niveau, Tandem-Diagnostik-Aufgabe in 3 Sitzungen.
- **Modul 03-10 — Hörverstehen colloquial** (`framework/03-stil/`): schließt die Lücke zwischen Tagesschau-artificial Standard + colloquialer Realität. Hörverstehen-Pyramide (5 Stufen, A1-C2), 4 colloquiale Distinktionen (Tempo 180-220 W/min, Klitisierung, Modalpartikel-Saturation, Hesitations-Diskursmarker), 4 methodische Phasen (untertitelt → halbblind → blind → Shadowing), 6 kanonische Filme/Serien (Tatort, Babylon Berlin, Dark, Goodbye Lenin, Lola rennt, Bad Banks), Aufgabe = Tatort-Folge in 3 Phasen analysieren (~300 min total).

#### Trilha G novo

- **Trilha G — Auswandern** (em [LEARNING-PATHWAYS.md](LEARNING-PATHWAYS.md) §7.5): para PT-falante imigrando para DE/AT/CH dentro de 6-24 meses. Diferença essencial das outras trilhas: prioriza registro cotidiano + behördisch + profissional sobre erudite-acadêmico. Stage 1 com 01-10 Konversation prio máxima; Stage 3 com 03-10 Hörverstehen + 03-02/-04/-05 prio; Stage 4 reduzido (apenas 04-09 + 04-03); Stage 5 com 05-04/-05/-07 prio. Capstone-5 modificado: integração documentada (Anmeldung + Krankenversicherung + Arbeitsvertrag + Goethe C1/TestDaF TDN4 + Vortrag profissional) em DE/AT/CH-Stadt. Inclui Pré-Auswanderung-Checkliste (12/6/3 Monate vor + erste 3 Monate nach), Cidades-Ziel-Übersicht (Berlin/München/Hamburg/Frankfurt/Wien/Zürich), Riscos da Trilha (Stage 4-5 erudite-Lücke, Phonetik-Fossilisierung, Bürokratie-Schock, Isolationsgefahr).

### Cross-references novas

- 01-10 → ANHANG K + ANHANG D + AUDIO-VIDEO-CANON.
- 03-10 → ANHANG L + AUDIO-VIDEO-CANON + 01-08/01-10/03-02/03-04.
- INDEX.md atualizado: Stage 1 = 10 modulos; Stage 3 = 10 modulos; Total = 46 modulos.
- Stage 1 + Stage 3 READMEs atualizados.
- anhaenge/README atualizado com K + L (12 Anhänge total agora).
- Trilha G integrada em LEARNING-PATHWAYS §7.5 + Comparação tabular.

### Estatísticas v1.5

```
Arquivos novos:                                 4
  Anhänge:                                       2 (K, L)
  Module:                                        2 (01-10, 03-10)
  
Arquivos modificados:                          ~6
  LEARNING-PATHWAYS.md (Trilha G adicionada)
  INDEX.md (Stage 1 + Stage 3 + total counts)
  Stage READMEs (1 + 3) com novos modulos no DAG
  anhaenge/README atualizado (12 Anhänge)
  Meta-docs (SPRINT-NEXT, CHANGELOG, RELEASE-NOTES)

Conteúdo:
  Total modulos cumulativo:                     46 (era 44)
  Anhänge cumulativo:                           12 (era 10)
  Trilhas:                                       7 (era 6)
  Conversational Skripten (Anhang K):            ~150
  Dialekt-Phrasen + Hörbeispiele:                ~80
```

### Honestidade pedagógica

v1.5 adiciona explicitamente o que faltava para **fluência conversacional cotidiana** (não apenas fluência acadêmica). Reconhece que CAPSTONE-3 exemplar demonstra Wissenschaftsdeutsch hoch — mas que aluno completando v1.0-v1.4 ainda não conseguiria pedir um Bier num Berliner Späti sem treinamento adicional específico. v1.5 fecha esta lacuna estrutural.

---

## v1.4 — 2026-05-09 — Aprofundamento operacional: 3 templates novos + self-test + Anki + CAPSTONE-3 exemplar + Stage 6 outline + Roadmap

### Adicionado

#### Templates novos (3)

- **GLOSSE-TEMPLATE.md** — feuilletonistische Glosse (~350-500W) com 5-Bewegung-Struktur (Eröffnung, Beobachtung, Aufschwung, Wendung, Pointe). Incluye Beispiel-Glosse + Stilexpektativas.
- **UEBERSETZUNGSANALYSE-TEMPLATE.md** — kontrastive PT↔DE-Übersetzungsanalyse (~3500-4500W) com 8 Sektionen (Abstract, Quelltext+Übersetzung, methodische Vorbemerkung, translatologische Theorie, sprachliche Analyse, Übersetzungsentscheidungen, Vergleich mit existierenden Übersetzungen, Reflexion). Schleiermacher-Achse + Benjamin/Berman/Steiner integriert.
- **VEROEFFENTLICHUNG-TEMPLATE.md** — Manuskript-Submission an DE-Zeitschrift mit 4-Dokumente-Paket (Manuskript + Exposé + Lebenslauf akademisch + Anschreiben). Liste de Zeitschriften canon (akademisch + kulturell). Submission-Workflow + realistic Akzeptanzraten.

#### Operational tooling

- **SELF-TEST-BANK-STAGE-1.md** — ~30 Übungen com Lösungen para os 9 módulos do Stage 1 + Cross-Module-Übungen + Stage-1-Abschluss-Selbstdiagnose.
- **ANKI-STARTER-DECK-STAGE-1.md** — ~500 frasal cards organizados pelos 9 módulos. Inclui Anki-Import-Format (TSV/CSV), Konfigurations-Empfehlungen, Tag-Hierarchie. Resolve **SN-009 partial**.

#### Worked example novo

- **CAPSTONE-3-AUFKLAERUNG-EXEMPLAR.md** — Aufsatz wissenschaftlich ~5000W sobre *Aufklärung* (continuação da progressão Glossar v0 → Aufsatz v1 → Aufsatz wissenschaftlich v2). 7 Sektionen (Abstract → Einleitung → Forschungsstand 3-Linien → Methodologie Koselleck → Hauptteil 3-aspectual → Diskussion + Synthese → Schluss). 7 Primärquellen + 9 Sekundärquellen. Konj.I (12+) + Konj.II (6+) + FVG (12+) + Passiv (8+) + Modalverben epistemisch + Konnektoren acadêmicos (18+) integrados ohne Stilbruch. Korrekturschleife dokumentada v1→v3. Bewertung ~91%.

#### Stage 6 + Roadmap (v2.0+ Blueprint)

- **STAGE-6-OUTLINE.md** — Spezialisierungs-Tracks Blueprint para post-CAPSTONE-5: Track A (Übersetzung), Track B (Forschung Promotion), Track C (Fachsprache 3 Sub-Tracks), Track D (Mentoring + DaF). 4 Tracks × 5-7 Module + Capstone-6 spezifisch. Berufliche Anschlussmöglichkeiten + Selection-Criterion. **Resolve SN-016 partial.**
- **ROADMAP.md** (root) — Long-term vision document v1.4→v3.0+. Status quo + 6 versões previstas + strategische Prinzipien + open questions + Beitragender-Information.

### Cross-references novas

- INDEX.md → SELF-TEST-BANK + ANKI-STARTER-DECK + STAGE-6-OUTLINE + ROADMAP + 3 templates novos + CAPSTONE-3 exemplar.
- templates/README atualizado com 3 templates adicionais (GLOSSE, UEBERSETZUNGSANALYSE, VEROEFFENTLICHUNG).
- examples/README atualizado com CAPSTONE-3 exemplar.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-009 | P2 | expansão | Anki decks pré-construídos | Partial (Stage 1 done; Stages 2-5 v1.5) |
| SN-014 | P3 | expansão | Capstones exemplares | Partial (CAPSTONE-1+2+3 done; -4/-5 v2.0+) |
| SN-016 | P3 | expansão | Stage 6 specialization | Partial (Outline done; full implementation v2.0+) |

### Estatísticas v1.4

```
Arquivos novos:                                  7
  Templates:                                      3 (GLOSSE, UEBERSETZUNGSANALYSE, VEROEFFENTLICHUNG)
  Operational:                                    2 (SELF-TEST-BANK + ANKI-STARTER-DECK)
  Worked example:                                 1 (CAPSTONE-3)
  Strategic:                                      1 (STAGE-6-OUTLINE)
  Roadmap:                                        1 (ROADMAP.md em root)

Arquivos modificados:                           ~5
  Catalog updates:                               2 (templates/README, examples/README)
  Meta-docs:                                     3 (INDEX, SPRINT-NEXT, CHANGELOG)

Conteúdo:
  Templates output cumulativo:                   8 (era 5)
  Worked examples cumulativo:                    3 (CAPSTONE-1+2+3 sobre Aufklärung)
  Self-test Übungen:                              ~30 (Stage 1)
  Anki cards starter:                             ~500 (Stage 1)
  Stage 6 Tracks Blueprint:                       4 (A, B, C, D)
```

---

## v1.3 — 2026-05-09 — Maestria total profunda: BEGRIFFS-GLOSSAR + Wortbildung + Phraseologismen + AUDIO-CANON + CAPSTONE-2 exemplar

### Adicionado

#### Glossário filosófico-filológico cumulativo

- **BEGRIFFS-GLOSSAR.md** (`framework/00-meta/`): 111 entries em 11 grupos cobrindo Begriffe filosóficos + filológicos centrais que atravessam Stages 3-5. Cada entry: definição operacional + etymon Pfeifer-Stil + tradição central + sub-tradições + Quellen primárias. Cross-references via `→`. **Resolve SN-007.**

#### Anhänge novos

- **ANHANG I — Wortbildung** (`framework/00-meta/anhaenge/`): 3 Verfahren (Komposition, Derivation, Konversion) + 4 Strukturklassen-Komposita (Determinativ, Kopulativ, Possessiv, Verbal) + Fugenelemente + catálogo de ~25 Suffixe derivacionais com Genus + Wortart-Resultat + produtividade + Diagnostik-Pipeline para Komposita-Dekomposition.
- **ANHANG J — Phraseologismen kanonisch**: ~450 Phraseologismen em 6 grupos: Redewendungen alltagssprachlich (~120), Idiomatik gehoben/literarisch (~80), Sprichwörter (~70), Geflügelte Worte aus DE-Klassik (~60, von Goethe/Schiller/Heine/Kant/Hegel/Nietzsche/Brecht/Marx/Adorno), Routineformeln pragmatisch (~40), Kollokationen lexikalisch fixiert (~80). Strategie de Aquisição por Stage.

#### Audio + Video Canon

- **AUDIO-VIDEO-CANON.md** (`framework/00-meta/`): Liste kanonischer Hörstoffe für Shadowing — Tagesschau, Deutschlandfunk-Sendungen, Adorno/Habermas/Sloterdijk-Vorträge auf YouTube, Universitäts-Mediatheken, Podcasts (Lage der Nation, Soziopod, Das Philosophische Radio), Hörbücher (Librivox + kommerziell), Filmographie (Fassbinder/Herzog/Wenders), Strukturierte Shadowing-Übung pro Stage.

#### Worked example novo

- **CAPSTONE-2-AUFKLAERUNG-EXEMPLAR.md** (`framework/00-meta/examples/`): Aufsatz argumentativ ~1500W sobre *Aufklärung* (continuação Glossar v0 do CAPSTONE-1 exemplar). Demonstra Konj. I (6+ instâncias) + Konj. II (4+) + FVG (5+) + Passiv (3+) + Modalverben epistemisch + Konnektoren acadêmicos. 5 Primärquellen + 4 Sekundärquellen com Akademie-Ausgabe-Belegung. Strukturanalyse + Korrekturschleife dokumentada (v1→v3) + Bewertung gemäß RUBRIC.md §3.

#### Cross-references novas

- 01-06 Wortbildung → ANHANG I.
- 03-03 Idiomatik → ANHANG J.
- CAPSTONE-2 → CAPSTONE-2 Exemplar.
- INDEX.md → BEGRIFFS-GLOSSAR + AUDIO-VIDEO-CANON + ANHANG I/J + CAPSTONE-2 Exemplar.
- anhaenge/README atualizado com 10 entries (A-J).
- examples/README atualizado com 2 worked examples.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-007 | P1 | expansão | BEGRIFFS-GLOSSAR cumulativo | Done |
| SN-014 | P3 | expansão | Capstones exemplares | Partial (CAPSTONE-1 + CAPSTONE-2 done; -3/-4/-5 v2.0+) |

### Estatísticas v1.3

```
Arquivos novos:                                 5
  BEGRIFFS-GLOSSAR.md                            1 (111 entries)
  ANHANG-I-WORTBILDUNG.md                        1
  ANHANG-J-PHRASEOLOGISMEN.md                    1 (~450 Phraseologismen)
  AUDIO-VIDEO-CANON.md                           1
  CAPSTONE-2-AUFKLAERUNG-EXEMPLAR.md             1

Arquivos modificados:                           ~7
  Wiring novos:                                  3 modulos (01-06, 03-03, CAPSTONE-2)
  Catalog updates:                               2 READMEs (anhaenge, examples)
  Meta-docs:                                     ~4 (INDEX, SPRINT-NEXT, CHANGELOG, RELEASE-NOTES)

Conteúdo:
  Begriffe catalogados:                          111
  Phraseologismen:                               ~450
  Wortbildungs-Patterns sistematizados:          ~50 (3 Verfahren + 25 Suffixe + 4 Klassen + Fugenelemente)
  Audio/Video-Quellen kanon:                     ~30 entries com URLs
  Capstone exemplares cumulativo:                2 (CAPSTONE-1 + CAPSTONE-2 sobre Aufklärung)
```

---

## v1.2 — 2026-05-09 — Maestria total: 6 novos Anhänge + governance + Capstone exemplar

### Adicionado

#### Anexos referenciais (`framework/00-meta/anhaenge/`) — 6 novos

- **ANHANG C — Präpositionen**: klasse fechada Akk-only (8) + Dat-only (~15) + Wechselpräpositionen (9 com par mínimo Akk/Dat) + Genitiv (~30 gehoben/juridisch). Idiomatik fixos + Verb+Präp.-Konstruktionen + falsche Freunde PT-DE.
- **ANHANG D — Konnektoren**: 3 klassen sintáticas distintas (Konjunktoren V2 / Subjunktoren VL / Konjunktionaladverbien V2 com Vorfeld) + listagem por função (causal, konzessiv, konditional, konsekutiv, final, temporal, adversativ, modal, komplement) + acadêmicos kombinationen (zwar...allerdings, etc.) + falsos cognatos PT-DE.
- **ANHANG E — Adjektivdeklination**: 3 padrões (schwach / stark / gemischt) × 4 Kasus × 4 categorias (m/f/n/Pl) com Diagnostik-Pipeline + Sonderfälle (-er/-el/-en Tilgungen, hoch→hoh-, lila/rosa invariáveis, substantivierte Adjektive) + Anki-Schema operacional.
- **ANHANG F — PT-DE Kontrastive**: ~30 fenômenos sistemáticos (V2 vs. SVO, Verbalklammer, VL em Nebensatz, Wechselpräpositionen, 4 Kasus, Verbregierung, doppelter Akkusativ, Konj. I, Konj. II, Modalverben deontisch/epistemisch, haben/sein, Wortbildung composicional, Genus arbitrarität, Modalpartikeln, Höflichkeitsformen Sie/du, Negation-Position, kein vs. nicht ein, Wortbildung, Substantivierung, Kapitalisierung, AcI, Auslautverhärtung, /r/-Distribution etc.) + Fossilisations-Risiko-Matrix por Stage.
- **ANHANG G — FVG Canônica**: >250 Funktionsverbgefüge organizadas por 18 Funktionsverben principais (bringen, kommen, finden, stehen, nehmen, machen, geben, ziehen, führen, halten, treffen, üben, erheben, leisten, gewinnen, treten, setzen, legen) + perypheras (gehen, geraten, treiben, bleiben, verfügen, verleihen, aufweisen, besitzen). Marcação por Domäne (Wissenschaft / Jurisprudenz / Bürokratie / Politik / Gehoben / Neutro) + Aquisitions-Scaffold por Stage. Resolve **SN-003**.
- **ANHANG H — Stilfiguren-Beispiele**: 20+ Stilfiguren com 3-5 exemplos canônicos cada (Adorno, Heidegger, Mann, Bernhard, Goethe, Brecht, Kant, Habermas, Nietzsche, Hegel, Schiller). Cluster por Domäne (Wissenschaftsdeutsch / Vortrag / Feuilleton / lyrisch). Stilfiguren-Bilanz para CAPSTONE-3 (5000W). Resolve **SN-004**.

#### Governance + Discoverability

- **README-EN.md**: versão internacional accessível, com Quickstart + estrutura + 5 Stages + reference-layer + license/community.
- **CODE_OF_CONDUCT.md**: convenção de conduta (foco intelectual, rigor sobre brand, honestidade sobre nível, PT/DE preferidos).
- **.github/ISSUE_TEMPLATE/** com 3 templates: bug_report.md, feature_request.md, question.md.
- **.github/PULL_REQUEST_TEMPLATE.md**: checklist incluindo regra "sem AI co-author trailer" + author-Konvention.
- **.github/workflows/markdown-link-check.yml**: auto-verificação de links semanal + em PRs.
- **.github/workflows/markdown-lint.yml**: linting Markdown em PRs.
- **.github/markdownlint.json** + **.github/markdown-link-check-config.json**: configurações.
- **README.md root**: Quickstart adicionada + estrutura tree expandida com novos diretórios.
- **anhaenge/README.md**: catálogo dos 8 Anhänge com links + função + origem + status.
- **templates/README.md**: catálogo dos 5 templates + workflow + princípios.
- **examples/README.md**: catálogo dos worked examples + princípio + warnings.

#### Worked examples (`framework/00-meta/examples/`)

- **CAPSTONE-1-AUFKLAERUNG-EXEMPLAR.md**: Glossar v0 completo sobre *Aufklärung* com 30 entries reais (1 Begriff + 5 Komposita + 4 Cognatos + 3 Antônimos + 10 Termos zentral + 4 Verbos + 3 Adjektive). Cada entry segue 9-Felder-Schema (Aussprache IPA + Flexão + Etymologie + Definition + Beleg primário + Topologische Analyse + Kollokationen + Stilstufe + Verweise). Belege primários de Kant 1784, Hegel 1807, Adorno/Horkheimer 1944, Habermas 2001, Foucault 1984. ~95 Anki-cards generierten exemplificadas. Warnings explícitas contra cópia. Resolve **SN-014 partial** (Capstone-1; Capstones-2/3/4/5 diferidos).

#### Cross-references

- 01-02 §2 → ANHANG C.
- 01-04 §2 → ANHANG E.
- 02-01 §2 → ANHANG D.
- 02-06 → ANHANG G.
- 03-06 §2 → ANHANG H.
- 04-09 §2 → ANHANG F.
- CAPSTONE-fundamente → CAPSTONE-1-AUFKLAERUNG-EXEMPLAR.
- INDEX.md atualizado com links a todos novos artefatos.

### Korrigido (Auditoria pragmática)

- **55 cross-references entre módulos verificados** — todos válidos.
- **5 fixes ß→ss** em paradigmas modernos (não-historisch):
  - 01-03 §2.2 (lista gemischte Verben + Modalverben): `wußte/mußte/gemußt` → `wusste/musste/gemusst`.
  - 01-03 §2.9 (Modalverben Präteritum-Liste): `mußte` → `musste`.
  - 01-03 §2.2 (Modalverben Tabelle Part.II): `gemußt` → `gemusst`.
  - 01-08 §3 (IPA-list Übung): `gewußt` → `gewusst`.
  - FEHLERPROTOKOLL-TEMPLATE Bernhard-Stil-Beispiel: `daß` → `dass`.
- **Citações historischer Texte preservaram orthographia originalis**: Kafka 1915, Goethe 1808, Brüder Grimm 1857, Kant 1781/87, Luther 1530, Schiller 1786 — em todos casos `daß`, `mußte`, `müßte` mantidos como historisch korrekt.

### Resolvido (SN-Items)

| SN | Prio | Tipo | Título | Status |
|---|---|---|---|---|
| SN-003 | P1 | expansão | Anexo 200+ FVG canônicas | Done |
| SN-004 | P1 | expansão | Anexo Stilfiguren com exemplos | Done |
| SN-005 | P1 | correção | Auditoria consistência cross-module | **Partial** (cross-refs OK; sistemática deferida v1.3) |
| SN-006 | P1 | melhoria | Edits ortográficos cross-module | **Partial** (5 ß→ss corrigidos; deep audit deferida v1.3) |
| SN-014 | P3 | expansão | Capstones exemplares | **Partial** (Capstone-1 done; -2/-3/-4/-5 v1.5+) |

### Estatísticas v1.2

```
Arquivos novos:                        ~17
  Anexos (anhaenge/):                   6 (C, D, E, F, G, H) + README
  Worked examples (examples/):          1 + README
  Templates README:                     1
  Governance (root):                    2 (README-EN, CODE_OF_CONDUCT)
  GitHub config (.github/):             7 (3 ISSUE_TEMPLATEs, PR_TEMPLATE, 
                                            2 workflows, 2 configs)

Arquivos modificados:                   ~12
  Cross-refs em módulos:                7 (01-02, 01-04, 02-01, 02-06, 03-06, 04-09, CAPSTONE-1)
  Auditoria-fixes:                      2 (01-03, 01-08, FEHLERPROTOKOLL)
  Meta-docs:                            4 (INDEX, SPRINT-NEXT, CHANGELOG, RELEASE-NOTES)
  README root:                          1 (Quickstart + structure tree)

Conteúdo:
  Verbos / formas catalogados:          Anexos C/D/E/F/G/H = ~600 entries de referência
  Glossar exemplar entries:             30
  Stilfiguren com exemplos:             20+ figuras × 3-5 exemplos = ~60 exemplos
  FVG catalogadas:                      >250
  Mermaid-Diagramme (cumulativo):       12
```

---

## v1.1 — 2026-05-09 — Anexos canônicos + DAG visual + output templates

### Adicionado

#### Anexos canônicos (`framework/00-meta/anhaenge/`)

- **ANHANG A — Ablautreihen** (`ANHANG-A-ABLAUTREIHEN.md`): ~166 verbos starke distribuídos pelas 7 Ablautreihen (com sub-Reihen Ia/Ib + IIa/IIb + IIIa/IIIb), klasse gemischt (9 verbos), Modalverben morfo-gemischt (6), irregulär (4), suppletiv (gehen/stehen). Cada entrada: Inf. + Prät.3.Sg. + Part.II + Hilfsverb (haben/sein/dual) + frase-Beleg. Resolve SN-001 (P1).
- **ANHANG B — Modalverben** (`ANHANG-B-MODALVERBEN.md`): 6 Modalverben × 6 pessoas × 8 Tempora/Modi (Präsens, Präteritum, Konj. I, Konj. II, Perfekt-Vollv., Perfekt-Modal/Ersatzinf., Plusquamperfekt, Futur I/II). Seções complementares: Modal + Perfekt-Inf. (epistemisch retrospektiv); Modal + Passiv (werden- e sein-); paradigma `möchten` höflich; Modal-Skala epistêmica; Pseudo-Modal `brauchen`. Resolve SN-002 (P1).

#### DAG visual (`framework/00-meta/DAG.md`)

- Master DAG file com diagrama global cross-Stage + 5 DAGs detalhados por Stage (com setas tracejadas para prereqs cross-Stage) + 4 caminhos críticos cross-Stage:
  - Caminho A: Sintaxe → Generative → Hermenêutica (01-01 → 02-08 → 04-04 → 04-10 → 05-02).
  - Caminho B: Lexik → Register → Diskursanalyse (01-09 → 02-09 → 03-02 → 03-08 → 04-06 → 05-01).
  - Caminho C: Schreiben → Stilbildung → Output (03-01 → 03-07 → 04-07 → 05-04 → 05-05).
  - Caminho D: Diakronie → Korpus → Begriffsgeschichte (01-06 → 04-01 → 04-02 → 04-08 → CAPSTONE-4).
- INDEX.md augmentado com Mermaid cross-Stage.
- 5 Stage READMEs com Mermaid local paralelo ao ASCII existente. Resolve SN-012 (P2).

#### Templates de output (`framework/00-meta/templates/`)

- **TAGEBUCH-TEMPLATE** — Tageseintrag in DE com 4 Strukturvarianten (frei / Reflexion strukturiert / Lesetagebuch / Sprachreflexion) + 4 Niveau-Modi (M1 Einfach a M4 Wissenschaftsdeutsch) + Korrekturschleife (4 Camadas) + Beispieleintrag.
- **AUFSATZ-1500W-TEMPLATE** — CAPSTONE-2 com 6 Sektionen (Einleitung → These → Argumentation I + II → Gegenargument → Schluss) + exigências stilísticas (Konj. I + Konj. II + Passiv + 1+ FVG + 1+ wörtliches Zitat) + 3-Round-Korrekturschleife + RUBRIC-Hinweis.
- **AUFSATZ-5000W-TEMPLATE** — CAPSTONE-3 com 7 Sektionen (Abstract → Einleitung → Forschungsstand → Methodologie → Hauptteil 3-aspectual → Diskussion + Gegenargument → Schluss) + Wissenschaftsdeutsch-hoch-Erwartungen + Literaturverzeichnis-Format + Mindestquellen (≥ 5 Primär + ≥ 5 Sekundär).
- **VORTRAG-TEMPLATE** — Modul 05-05 com 30-min-Skript-Strukturschema + Sprechgeschwindigkeit (~130 W/min × 30 = ~3900 W) + Pausenmarkierung + phonetische Aufmerksamkeit (Auslautverhärtung, Knacklaut, /r/-Distribution) + Q&A-Vorbereitung intern.
- **BEGRIFFSANALYSE-TEMPLATE** — CAPSTONE-4 com methodische Trias (diachron Frequenz + synchron Kollokationen + hermeneutisch Tiefenanalyse) + Korpus-Auswahl-Diskussion (DWDS / COSMAS-II) + Beleg-Anhang-Format (≥ 30 Belege) + Methodenkritik. Resolve SN-011 (P2).

#### Cross-references neue Verknüpfungen

- 01-03 §2.3 → ANHANG A (Ablautreihen).
- 02-07 §2.1 → ANHANG B (Modalverben).
- CAPSTONE-2 / -3 / -4 → respektive Output-Templates.
- 05-05 → VORTRAG-TEMPLATE.
- INDEX.md → anhaenge/ + templates/ + DAG.md.

### Korrigido / verändert

- INDEX.md: lista de "Documentos meta complementares" expandida com `DAG.md`, `anhaenge/`, `templates/`.
- 5 Stage READMEs: estrutura "DAG do Stage N" subdividida em "Textual (ASCII)" + "Visuell (Mermaid)".
- SPRINT-NEXT.md: SN-001, SN-002, SN-011, SN-012 marcados como Done; cadência de releases atualizada.

### Resolvido (SN-Items, cf. SPRINT-NEXT.md)

- SN-001 [P1] — Anexo 7 Ablautreihen completas.
- SN-002 [P1] — Anexo Modalverben em todos modos + tempos.
- SN-011 [P2] — Templates Markdown para output do aluno.
- SN-012 [P2] — Diagramas DAG visuais.

### Estatísticas v1.1

```
Novos arquivos:                    8
  Anexos:                          2 (ANHANG-A, ANHANG-B)
  Templates:                       5 (Tagebuch, Aufsatz-1500W, Aufsatz-5000W, Vortrag, Begriffsanalyse)
  Master DAG:                      1 (DAG.md)
Arquivos modificados:              ~10
  Cross-refs em modul 01-03 + 02-07
  Templates hinweise em 4 Capstones + 05-05
  INDEX.md + 5 Stage READMEs (Mermaid)
  SPRINT-NEXT.md (status updates)

Verbos catalogados (ANHANG A):     ~166
Modalverb-Konjugationsformen 
documentadas (ANHANG B):           ~300
Mermaid-Diagramme adicionados:     12 (1 master + 5 stages local + 1 INDEX + 5 caminhos críticos)
Output-Templates:                  5 (cobre todos Capstones + Tagebuch sustentado + Vortrag)
```

---

## v1.0 — 2026-05-08 — Initial Public Release

### Adicionado

- **5 Stages estruturalmente completos**:
  - Stage 1 (Fundamente): 9 módulos + Capstone-1.
  - Stage 2 (Struktur): 9 módulos + Capstone-2.
  - Stage 3 (Stil): 9 módulos + Capstone-3.
  - Stage 4 (System): 10 módulos + Capstone-4.
  - Stage 5 (Meisterschaft): 7 módulos + Capstone-5.
- **44 módulos + 5 Capstones encadeados** (Erkenntnisprojekt v0→v4).
- **~50 textos-âncora canônicos** (Kant 1784 a Habermas 2001).
- **Documentos meta**:
  - INDEX.md, CAPSTONE-EVOLUTION.md.
  - REFERENCES-ELITE.md, READING-LIST.md, GLOSSAR.md.
  - SELF-ASSESSMENT.md, RUBRIC.md.
  - ANKI-FRAMEWORK.md, FEHLERPROTOKOLL-TEMPLATE.md.
  - MODULE-TEMPLATE.md, LEARNING-PATHWAYS.md, BEGRIFF-INDEX.md.
  - DECISION-LOG.md, SPRINT-NEXT.md.
  - RELEASE-NOTES.md.
- **Documentos do root**: README.md, MENTOR.md, STUDY-PROTOCOL.md, PROGRESS.md, LICENSE (CC BY-NC 4.0), .gitignore.
- **Push GitHub**: 6 commits encadeados (`26dd446`, `c4c5dc6`, `afa617c`, `fa81120`, `98afac6`, [v1.0]).

### Trilhas suportadas

- Trilha A — Canônica (default, generalista).
- Trilha B — Geisteswissenschaft (filosofia + germanística).
- Trilha C — Linguistik (germanística + linguística aplicada).
- Trilha D — Tradução PT↔DE.
- Trilha E — Berufsdeutsch (uso profissional).
- Trilha F — PhD-DE acelerada.

### Princípios estabelecidos

- Não-negociáveis pedagógicos (cf. README.md).
- Loop de Refinamento em 4 camadas (Grammatik / Lexik / Stil / Native erudite, cf. MENTOR.md §1).
- 3 Tore obrigatórios por módulo (Konzeptuell / Praktisch / Verbindungen, cf. MENTOR.md §3 + RUBRIC.md).
- Capstones encadeados em torno de Begriff escolhido.

---

## Convenções de versionamento

### Major version (v2.0, v3.0)

Mudança estrutural significativa: adição de novo Stage, reorganização da topologia, mudança em pré-requisitos canônicos.

### Minor version (v1.1, v1.2)

Adição de módulo opcional, anexos extensivos, novas trilhas, expansões pedagógicas.

### Patch version (v1.0.1, v1.0.2)

Correções de erros, atualização de referências, edits ortográficos.

---

## Próximas versões previstas (cf. SPRINT-NEXT.md)

### v1.1 (~6-12 meses)

- Glossário cross-stage de Begriffe centrais cumulativo.
- Anexos com listas exhaustivas de starken Verben (7 Ablautreihen).
- Anexos com Modalverben em todos modos + tempos.
- Anexos com FVG canônicas (200+ entries).
- Anexos com Stilfiguren com exemplos múltiplos.
- Edits ortográficos + revisão consistência cross-module.

### v1.5 (~12-24 meses)

- Tradução do framework para DE original (atualmente em PT-BR).
- Adição de tracks empíricas com Anki decks pré-construídos.
- Validação peer-review por linguistas DE.
- Templates Markdown para Tagebuch + Aufsatz + Vortrag.

### v2.0 (~24-48 meses)

- Comunidade de mentees + cohorts ativos.
- Capstones de exemplares (1-2 por Begriff publicados como modelo).
- Feedback loop com aprendizes que completaram.
- Iterações pedagógicas baseadas em dados.
- Possível adição de módulo 06 (Specialization tracks).

---

## Como contribuir mudanças

1. **Issue ou Discussion no GitHub**: descrever mudança proposta.
2. **DECISION-LOG entry** (se mudança estrutural): justificar.
3. **Pull Request**: implementar.
4. **Review**: discussão pública.
5. **Merge**: incorporar em main + atualizar CHANGELOG.

(Cf. CONTRIBUTING.md quando criado.)

---

## Notas de migração

(Sem migrações necessárias para v1.0; primeira release.)

Em versões futuras, esta seção documentará passos para alunos atualizarem dependências (e.g., novos textos-âncora; reordenamento de módulos).
