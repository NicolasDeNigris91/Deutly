# RELEASE-NOTES — FATHOM-Deutsch

> Documenta o estado das releases do framework FATHOM-Deutsch.

---

## v1.1 — Anexos canônicos + DAG visual + output templates (2026-05-09)

### Eixos da release

Eleva o framework de **estruturalmente completo** (v1.0) para **operacionalmente world-class**: referência consultável + navegável + redutor-de-fricção para output do aluno.

### O que está novo

#### 1. Anexos canônicos (`framework/00-meta/anhaenge/`)

Referência consultável para os dois sistemas com maior densidade morfo-sintática do alemão.

##### ANHANG A — Ablautreihen

- ~166 verbos starke catalogados nas 7 Reihen + sub-Reihen (Ia/Ib, IIa/IIb, IIIa/IIIb).
- Cada entrada: Inf. + Prät.3.Sg. + Part.II + Hilfsverb (haben/sein/dual) + Beleg-Frase.
- Klassen complementares: gemischt (9 verbos), Modalverben morfo-gemischt (6), irregulär (4: sein/haben/werden/tun), suppletiv (gehen/stehen).
- Pipeline diagnóstico (vogal + Konsonant-Kontext → Reihe).
- Estratégia de aquisição via Anki por Reihe.

##### ANHANG B — Modalverben

- 6 Modalverben (können / müssen / dürfen / wollen / sollen / mögen) × 6 pessoas × 8 Tempora/Modi.
- Distinção Vollverb-Perfekt (Part.II *gekonnt*) vs. Modal-Perfekt (Ersatzinf. *können*).
- Modal + Perfekt-Inf. (epistemisch retrospektiv).
- Modal + Passiv (werden- e sein-).
- Paradigma `möchten` höflich (Konj. II lexicalizado).
- Modal-Skala epistêmica (~50% können → ~95% muss).
- Pseudo-Modal `brauchen` (Stage-2-relevant).

#### 2. DAG visual em Mermaid (`framework/00-meta/DAG.md`)

Mapas visuais nativamente renderizados em GitHub:

- **Master cross-Stage DAG**: 5 Stages encadeados via Capstones.
- **5 DAGs detalhados por Stage**: cada Stage com prereqs internos + cross-Stage (setas tracejadas distintas) + Capstone como terminal.
- **4 caminhos críticos cross-Stage**:
  - A) Sintaxe → Generative → Hermenêutica.
  - B) Lexik → Register → Diskursanalyse.
  - C) Schreiben → Stilbildung → Public Output.
  - D) Diakronie → Korpus → Begriffsgeschichte.
- INDEX.md + 5 Stage READMEs com Mermaid local paralelo a ASCII.
- Convenções gráficas (cores por Stage, Capstones com bordas duplas, prereqs cross-Stage tracejados).

#### 3. Templates de output (`framework/00-meta/templates/`)

5 templates Markdown reduzem fricção operacional. Scaffolds, não camisas de força.

- **TAGEBUCH-TEMPLATE** — entrada diária em DE com 4 Strukturvarianten + 4 Niveau-Modi.
- **AUFSATZ-1500W-TEMPLATE** — CAPSTONE-2 com 6 Sektionen + Korrekturschleife.
- **AUFSATZ-5000W-TEMPLATE** — CAPSTONE-3 com Wissenschaftsdeutsch hoch + ≥ 5 Primär-/Sekundärquellen.
- **VORTRAG-TEMPLATE** — Modul 05-05 com Sprechrhythmus + Pausenmarkierung + phonetische Aufmerksamkeit.
- **BEGRIFFSANALYSE-TEMPLATE** — CAPSTONE-4 com methodische Trias (Frequenzverlauf + Kollokationsanalyse + hermeneutische Tiefe).

#### 4. Cross-references novas

Templates + Anhänge ligados de volta aos módulos:

- 01-03 §2.3 → ANHANG A.
- 02-07 §2.1 → ANHANG B.
- CAPSTONE-2 → AUFSATZ-1500W-TEMPLATE.
- CAPSTONE-3 → AUFSATZ-5000W-TEMPLATE.
- CAPSTONE-4 → BEGRIFFSANALYSE-TEMPLATE.
- 05-05 → VORTRAG-TEMPLATE.
- INDEX.md → todas as três pastas novas.

### Estatísticas v1.1

```
Arquivos novos:                       8
  framework/00-meta/anhaenge/          2 (Ablautreihen + Modalverben)
  framework/00-meta/templates/         5
  framework/00-meta/DAG.md             1

Arquivos modificados:                 ~10
  Cross-references em módulos          (01-03, 02-07, 4 Capstones, 05-05)
  Mermaid em READMEs                   (INDEX + 5 Stage READMEs)
  Status-Updates em SPRINT-NEXT        (4 SN-Items: 001, 002, 011, 012)

Conteúdo:
  Verbos starke catalogados            ~166
  Modalverb-Konjugationsformen         ~300
  Mermaid-Diagramme adicionados        12
  Output-Templates                      5
```

### Resolvidos (SN-Items)

| SN | Prio | Tipo | Título | Esforço estimado | Status |
|---|---|---|---|---|---|
| SN-001 | P1 | expansão | Anexo 7 Ablautreihen | 8-12 h | Done |
| SN-002 | P1 | expansão | Anexo Modalverben | 4-6 h | Done |
| SN-011 | P2 | expansão | Templates Markdown | 10-15 h | Done |
| SN-012 | P2 | melhoria | Diagramas DAG visuais | 5-8 h | Done |

### Próximas releases previstas (cf. SPRINT-NEXT.md)

- **v1.2 (~2026-09)**: SN-003 (FVG 200+) + SN-004 (Stilfiguren-Beispiele) + SN-005-006 (auditoria + edits ortográficos).
- **v1.5 (~2027-12)**: SN-008 (tradução DE) + SN-009 (Anki decks) + SN-010 (peer-review).
- **v2.0 (~2028-12)**: SN-013 (comunidade) + SN-014 (Capstones exemplares) + SN-016 (Stage 6).

### Status v1.1

**Operacionalmente world-class para uso individual sustentado.** Aluno pode:

- Iniciar imediatamente via INDEX.md → Stage 1 README → módulo 01-01 / 01-08.
- Consultar ANHANG A / B durante Stage 1-2 sem sair do framework.
- Visualizar progressão via DAG visual (cross-Stage + 4 caminhos críticos).
- Usar Templates como scaffold para todos os Capstones + Tagebuch sustentado + Vortrag em 05-05.

Próximas releases: aprofundamento referencial (FVG, Stilfiguren) + qualidade publicável (auditoria) + abertura comunitária (peer-review, Anki decks).

---

## v1.0 — Initial Public Release (2026-05-08)

### Conteúdo

#### Documentos do root

- **README.md** — manifesto + estrutura geral.
- **MENTOR.md** — protocolo do mentor + Loop de Refinamento (4 camadas).
- **STUDY-PROTOCOL.md** — 12 técnicas cognitivas adultas para L2.
- **PROGRESS.md** — dashboard de progresso através dos 5 Stages.
- **LICENSE** — CC BY-NC 4.0.
- **.gitignore** — exclui `.claude/`, `Erkenntnisprojekt/`, Anki state.

#### Meta documents (`framework/00-meta/`)

- **INDEX.md** — mapa global dos 44 módulos + 5 Capstones com prereqs.
- **CAPSTONE-EVOLUTION.md** — Erkenntnisprojekt v0→v4 trajetória.
- **REFERENCES-ELITE.md** — gramáticas + corpora + autores canônicos.
- **READING-LIST.md** — texto-âncora por módulo.
- **GLOSSAR.md** — 110+ termos linguísticos canônicos em DE.
- **SELF-ASSESSMENT.md** — calibração inicial (CEFR + estrutural + Wortschatz + fonético).
- **RUBRIC.md** — critérios pass/fail dos 3 Tore (Konzeptuell + Praktisch + Verbindungen).
- **ANKI-FRAMEWORK.md** *(novo v1.0)* — operacionalização do Anki cross-stage.
- **FEHLERPROTOKOLL-TEMPLATE.md** *(novo v1.0)* — template do registro de erros.
- **MODULE-TEMPLATE.md** *(novo v1.0)* — template para novos módulos.
- **LEARNING-PATHWAYS.md** *(novo v1.0)* — 6 trilhas alternativas.
- **BEGRIFF-INDEX.md** *(novo v1.0)* — scaffold dos 7 Begriffe canônicos.
- **DECISION-LOG.md** *(novo v1.0)* — log de decisões estruturais.
- **CHANGELOG.md** *(novo v1.0)* — histórico de versões.
- **SPRINT-NEXT.md** *(novo v1.0)* — backlog de próximas evoluções.
- **RELEASE-NOTES.md** *(este arquivo)*.

#### Stages estruturalmente completos

##### Stage 1 — Fundamente (`framework/01-fundamente/`)

9 módulos + Capstone-1:

```
01-01 Syntaktische Analyse — Topologisches Feldermodell      [Kant, 1784]
01-02 Kasussystem — Funktionen und Träger                    [Kafka, 1915]
01-03 Verbalsystem I — Tempus, Konjugation, Trennbarkeit    [Brüder Grimm, 1857]
01-04 Nominalflexion — Genus, Numerus, Adjektivdeklination   [Kleist, 1810]
01-05 Pronominalsystem                                       [Tucholsky, 1919]
01-06 Wortbildung I — Komposition + Derivation               [Heidegger, 1947]
01-07 Negation und Modalpartikeln Grundlagen                 [Brecht, 1939]
01-08 Phonetik & Phonologie                                  [Tagesschau + Goethe Erlkönig]
01-09 Grundwortschatz                                        [DWDS-Kernkorpus]
CAPSTONE-1 — Erkenntnisprojekt v0 (Glossar fonético-estrutural)
```

##### Stage 2 — Struktur (`framework/02-struktur/`)

9 módulos + Capstone-2:

```
02-01 Subordination — Subjunktoren und Verbletztstellung     [Kafka, Der Process]
02-02 Konjunktiv I (indirekte Rede)                          [FAZ-Politik atual]
02-03 Konjunktiv II (Irrealis und Höflichkeit)               [Schiller, 1786]
02-04 Passivkonstruktionen                                   [Mann, Zauberberg]
02-05 Infinitivsätze                                         [Musil, MoE]
02-06 Funktionsverbgefüge                                    [BGB §§ 1-242]
02-07 Modalverben — epistemisch vs. deontisch                [Bernhard, Holzfällen]
02-08 Topik-Fokus-Struktur                                    [Adorno, Minima Moralia]
02-09 Lexik II — operationaler Wortschatz                    [Habermas, Strukturwandel]
CAPSTONE-2 — Erkenntnisprojekt v1 (argumentativer Aufsatz 1500 W)
```

##### Stage 3 — Stil (`framework/03-stil/`)

9 módulos + Capstone-3:

```
03-01 Nominaler vs. verbaler Stil                            [Adorno, Negative Dialektik]
03-02 Register — Hochsprache, Umgangs-, Fach-, Plurizentrik  [Coletânea registros]
03-03 Idiomatik und Phraseologie                             [Karl Kraus, Letzte Tage]
03-04 Pragmatik                                              [Bundestag Plenarprotokoll]
03-05 Modalpartikeln (sistematische Vertiefung)              [Bernhard, Auslöschung]
03-06 Stilfiguren und Rhetorik                               [Heidegger, Kunstwerk]
03-07 Wissenschaftliches Schreiben                           [Luhmann, Soziale Systeme]
03-08 Journalistischer Stil                                  [Coletânea midiática]
03-09 Lexik III — geisteswissenschaftlicher Wortschatz       [Kant, KrV]
CAPSTONE-3 — Erkenntnisprojekt v2 (wissenschaftlicher Aufsatz 5000 W)
```

##### Stage 4 — System (`framework/04-system/`)

10 módulos + Capstone-4:

```
04-01 Historische Linguistik — Idg., Ahd., Mhd., Frnhd., Nhd. [Walther + Luther]
04-02 Etymologie und Wortgeschichte                          [Pfeifer 30 entries]
04-03 Variationslinguistik — Plurizentrik DE/AT/CH           [Coletânea regional]
04-04 Generative Syntax — X-bar, GB, Minimalismus           [Sternefeld]
04-05 Formale Semantik — Wahrheitsbedingungen, Quantorenlogik [Frege, 1892]
04-06 Diskursanalyse — Foucault, KDA                         [Foucault + Bundestag]
04-07 Textlinguistik — Kohäsion, Kohärenz, Textsorten        [Sebald, Ringe Saturn]
04-08 Korpuslinguistik (DWDS, COSMAS II)                     [DWDS Wortprofil]
04-09 Kontrastive Linguistik PT-DE                            [PT-DE coletânea paralelas]
04-10 Hermeneutik klassischer Texte                          [Heidegger + Hegel]
CAPSTONE-4 — Erkenntnisprojekt v3 (korpusbasierte Begriffsanalyse ~30 páginas)
```

##### Stage 5 — Meisterschaft (`framework/05-meisterschaft/`)

7 módulos (05-07 opcional) + Capstone-5:

```
05-01 Politische Sprache — Bundestagsdebatten, Parteiprogramme [Plenarprotokoll]
05-02 Wissenschaftssprache — Habermas, Luhmann, Adorno         [Habermas TkH + Luhmann SS + Adorno ND]
05-03 Übersetzungstheorie und -praxis                          [Schleiermacher + Benjamin]
05-04 Eigene Stimme — Stilbildung                               [Mann + Bernhard + Kafka auto-retrospectivas]
05-05 Public Output — Vortrag, Artikel, Podcast                 [Adorno EnA + Habermas Friedenspreisrede]
05-06 Mentoring von Lernenden                                   [aplicação cross-stage]
05-07 Goethe-Zertifikat C2 / TestDaF (opcional)                 [Modellprüfungen]
CAPSTONE-5 — Erkenntnisprojekt v4 (Veröffentlichung em revista DE/AT/CH + Vortrag + Podcast + Mentoring)
```

### Estatísticas v1.0

```
Total stages:                5
Total módulos:               44 (Stage 1: 9; Stage 2: 9; Stage 3: 9; Stage 4: 10; Stage 5: 7)
Total Capstones:             5 (Erkenntnisprojekt v0→v4)
Total textos-âncora:         ~50 obras canônicas (séc. XII a XXI)
Total documentos meta:       16 (em framework/00-meta/)
Total commits GitHub:        6 (incluindo este v1.0 release)
Estimativa de horas total:   2-5 mil h (trajetória canônica)
Estimativa de tempo:         5-10 anos (trajetória canônica)
```

### Trilhas alternativas suportadas

```
Trilha A — Canônica (default; generalista, 2-5 mil h)
Trilha B — Geisteswissenschaft (filosofia + germanística; 2.5-4.5 mil h)
Trilha C — Linguistik (germanística + linguística aplicada; 3-5 mil h)
Trilha D — Tradução PT↔DE (Übersetzungswissenschaft; 2.5-4.5 mil h)
Trilha E — Berufsdeutsch (uso profissional; 1.5-3 mil h)
Trilha F — PhD-DE acelerada (intensiva; 2-3 mil h em 2-3 anos)
```

(Cf. LEARNING-PATHWAYS.md.)

### Begriffe canônicos sugeridos para Erkenntnisprojekt

```
1. Aufklärung (Kant, Habermas, Foucault, Horkheimer/Adorno)
2. Bildung (Humboldt, Adorno)
3. Geist (Hegel, Dilthey, Cassirer)
4. Wahrheit (Heidegger, Gadamer, Frege, Tugendhat)
5. Macht (Nietzsche, Foucault, Weber, Arendt)
6. Sein (Heidegger)
7. Sprache (Wittgenstein, Heidegger, Gadamer, Habermas)
```

(Cf. BEGRIFF-INDEX.md para scaffolds detalhados.)

---

## Princípios não-negociáveis (cf. README.md)

```
1. Sistema antes de uso.
2. Sem passar pano (Loop de Refinamento sempre).
3. Quellen primárias (Eisenberg, Duden, Helbig/Buscha, IDS-Grammis).
4. Texto autêntico antes de exercício.
5. Output regular em DE (a partir do módulo 01-02).
6. Nominaler vs. verbaler Stil.
7. Capstone encadeado (Erkenntnisprojekt evolui).
```

---

## Princípios pedagógicos (cf. STUDY-PROTOCOL.md)

```
1. Active Recall (Karpicke/Roediger 2008)
2. Spaced Repetition (Bjork desirable difficulty)
3. Comprehensible Input + 1 (Krashen 1985)
4. Output Hypothesis (Swain 1985)
5. Shadowing (Arguelles, Kluge)
6. Feynman Technique adaptada a L2
7. Deliberate Practice (Ericsson 2016 Peak)
8. Spaced Re-Test (decay & refresh, 90-day cycle)
9. Fehlerprotokoll continuo
10. Reading Primary Sources (não-graded readers após B2)
11. Cohort/Peer (anti-isolamento gate, MENTOR.md §10.5)
12. Sustainability checkpoints
```

---

## Saída cumulativa esperada (CAPSTONE-5 completo)

Ao terminar o Stage 5:

- **Erkenntnisprojekt v4 publicado** em revista DE/AT/CH.
- **5 Capstones encadeados** salvos: v0 (Glossar) → v1 (Aufsatz 1500 W) → v2 (Aufsatz 5000 W) → v3 (Begriffsanalyse korpusbasiert ~30 páginas) → v4 (Veröffentlichung).
- **1 Vortrag de 30 min gravado** em Hochdeutsch erudito.
- **1 episódio de podcast em DE**.
- **3+ Lernende mentorados** com aparelho RUBRIC.md.
- **Anki deck saturado** (~10000+ frasal cards).
- **Tagebuch em DE** 12+ meses sustentado.
- **Goethe C2 / TestDaF** (opcional, marcador externo).

---

## Status v1.0

**Estruturalmente completo + operacional**. Aluno pode iniciar trajetória hoje.

### Como começar

1. Ler `README.md` (este repo).
2. Ler `STUDY-PROTOCOL.md` (técnicas obrigatórias).
3. Ler `MENTOR.md` (contrato do mentor).
4. Aplicar `framework/00-meta/SELF-ASSESSMENT.md` (calibração).
5. Escolher trilha em `framework/00-meta/LEARNING-PATHWAYS.md`.
6. Escolher Begriff em `framework/00-meta/BEGRIFF-INDEX.md`.
7. Abrir `framework/01-fundamente/01-01-syntaktische-analyse.md` + iniciar.

---

## Próximas evoluções (cf. SPRINT-NEXT.md)

### v1.1 (curto prazo, ~6-12 meses)

- Glossário cross-stage de Begriffe centrais cumulativo.
- Anexos com listas exhaustivas de starken Verben (7 Ablautreihen completas).
- Anexos com Modalverben em todos modos + tempos.
- Anexos com FVG canônicas (200+ entries).
- Anexos com Stilfiguren com exemplos múltiplos.
- Edits ortográficos + revisão consistência.

### v1.5 (médio prazo, ~12-24 meses)

- Tradução do framework para DE original (atualmente em PT).
- Adição de tracks empíricas com Anki decks pré-construídos.
- Validação peer-review por linguistas DE.

### v2.0 (longo prazo, ~24-48 meses)

- Comunidade de mentees + cohorts ativos.
- Capstones de exemplares (1-2 por Begriff publicados como modelo).
- Feedback loop com aprendizes que completaram.
- Iterações pedagógicas baseadas em dados.

---

## Atribuição

Framework escrito por Nicolas De Nigris. Síntese pedagógica baseada em:

- Eisenberg, Helbig/Buscha, Engel, Duden, IDS-Grammis (gramáticas canônicas).
- Krashen, Swain, Bjork, Karpicke/Roediger, Ericsson (pedagogia adulta L2).
- Schleiermacher, Benjamin, Berman, Venuti (Übersetzungstheorie).
- Habermas, Luhmann, Adorno, Heidegger, Gadamer, Foucault (filosofia DE).
- Pfeifer, Kluge, DWDS, COSMAS II, Brunner/Conze/Koselleck (linguística histórica + corpora).
- Wodak, Jäger, Spitzmüller (KDA + Diskurslinguistik).

Crédito completo em `framework/00-meta/REFERENCES-ELITE.md` + nas Quellen de cada módulo.

---

## Licença

CC BY-NC 4.0 (Creative Commons Attribution-NonCommercial 4.0 International).

Você pode compartilhar e adaptar, desde que dê crédito e não use comercialmente. Detalhes legais em [LICENSE](../../LICENSE).

---

## Contato + comunidade

GitHub: https://github.com/NicolasDeNigris91/Deutly

Issues / Pull Requests: bem-vindos.

---

**FATHOM-Deutsch v1.0 — primeira versão completa. Trajetória estruturada de A1 estrutural a C2+ World Class. 44 módulos + 5 Capstones encadeados em torno de Begriff escolhido.**
