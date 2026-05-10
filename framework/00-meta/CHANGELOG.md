# CHANGELOG — FATHOM-Deutsch

> Histórico de versões do framework. Cada release nota mudanças significativas. Referenciado em MENTOR.md §10.2.

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
