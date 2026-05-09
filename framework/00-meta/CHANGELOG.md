# CHANGELOG — FATHOM-Deutsch

> Histórico de versões do framework. Cada release nota mudanças significativas. Referenciado em MENTOR.md §10.2.

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
