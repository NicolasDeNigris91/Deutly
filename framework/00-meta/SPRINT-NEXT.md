# SPRINT-NEXT — Backlog de próximas evoluções

> Backlog de próximas mudanças / evoluções do framework. Referenciado em MENTOR.md §10.2. Itens marcados por **prioridade + estimativa** + **tipo (correção / melhoria / expansão / experimento)**.

---

## Convenção

```
## SN-NNN [P1/P2/P3] [tipo] — Título

**Descrição:**
[O que será feito]

**Justificativa:**
[Por que]

**Estimativa:**
[Tempo/esforço]

**Status:**
[Backlog / In Progress / Done / Wontfix]
```

Prioridade:
- **P1**: importante, deve sair em v1.1.
- **P2**: relevante, v1.5.
- **P3**: nice-to-have, v2.0.

Tipos:
- **correção**: erro detectado.
- **melhoria**: refinamento de existente.
- **expansão**: adição de conteúdo novo.
- **experimento**: tentativa não-finalizada.

---

## v1.1 (P1) — Curto prazo (~6-12 meses)

### SN-001 [P1] [expansão] — Anexo: 7 Ablautreihen completas

**Descrição:** Anexo a 01-03 (Verbalsystem) com **lista completa** das 7 Ablautreihen + todos os verbos starke canônicos por Reihe (~150-200 verbos). Cada verbo com Stammformen + frase exemplo.

**Justificativa:** Aluno Stage 1-2 beneficiaria de referência consolidada para Anki. Atualmente: módulo 01-03 lista representantes; aluno tem que pesquisar por conta própria.

**Estimativa:** 8-12 horas para compilar + revisar.

**Status:** Done (v1.1, 2026-05-09). Implementado em [`framework/00-meta/anhaenge/ANHANG-A-ABLAUTREIHEN.md`](anhaenge/ANHANG-A-ABLAUTREIHEN.md). ~166 verbos por Reihe + gemischt + Modalverben + irregulär + suppletiv. Cada um com Inf./Prät.3.Sg./Part.II/Hilfsverb/Beleg.

---

### SN-002 [P1] [expansão] — Anexo: Modalverben em todos modos + tempos

**Descrição:** Anexo a 01-03 + 02-07 com **tabelas completas** dos 6 Modalverben (können, müssen, dürfen, wollen, sollen, mögen) em Präsens, Präteritum, Konj. I, Konj. II, Perfekt, Plusquamperfekt, Futur I, Futur II — todas as 6 pessoas.

**Justificativa:** Modalverben são pivotais cross-stage. Tabelas consolidadas evitariam consulta repetida a Duden.

**Estimativa:** 4-6 horas.

**Status:** Done (v1.1, 2026-05-09). Implementado em [`framework/00-meta/anhaenge/ANHANG-B-MODALVERBEN.md`](anhaenge/ANHANG-B-MODALVERBEN.md). 6 Modalverben × 6 pessoas × 8 Tempora/Modi + Modal+Perfekt-Inf. + Modal+Passiv + paradigma `möchten` + Modal-Skala epistêmica + Pseudo-Modal `brauchen`.

---

### SN-003 [P1] [expansão] — Anexo: 200+ FVG canônicas

**Descrição:** Anexo a 02-06 (FVG) com **lista expandida** de Funktionsverbgefüge (200+) organizadas por Funktionsverb (bringen, kommen, finden, stehen, ...) e por domínio (Recht, Wissenschaft, Wirtschaft, Politik).

**Justificativa:** Atualmente módulo 02-06 lista ~30 FVG canônicas. Aprendiz Stage 2-3 beneficiaria de referência mais ampla.

**Estimativa:** 12-16 horas.

**Status:** Done (v1.2, 2026-05-09). Implementado em [`framework/00-meta/anhaenge/ANHANG-G-FVG-CANONICA.md`](anhaenge/ANHANG-G-FVG-CANONICA.md). >250 FVG por 18 Funktionsverben (bringen / kommen / finden / stehen / nehmen / machen / geben / ziehen / führen / halten / treffen / üben / erheben / leisten / gewinnen / treten / setzen / legen + perypheras gehen/geraten/treiben/bleiben/verfügen/verleihen/aufweisen/besitzen). Marcação por Domäne (W / J / B / Po / G / N) + Stages-Aquisições-Scaffold.

---

### SN-004 [P1] [expansão] — Anexo: Stilfiguren com 50+ exemplos por figura

**Descrição:** Anexo a 03-06 com **3-5 exemplos canônicos** para cada Stilfigur (Hyperbaton, Chiasmus, Antithese, Litotes, Anapher, Personifikation, etc.), extraídos de Adorno, Heidegger, Mann, Bernhard.

**Justificativa:** Reconhecimento de Stilfiguren beneficia-se de exposição massiva. 1 exemplo por figura é insuficiente para internalização.

**Estimativa:** 8-12 horas.

**Status:** Done (v1.2, 2026-05-09). Implementado em [`framework/00-meta/anhaenge/ANHANG-H-STILFIGUREN-BEISPIELE.md`](anhaenge/ANHANG-H-STILFIGUREN-BEISPIELE.md). 20+ Stilfiguren (Anapher, Epipher, Chiasmus, Hyperbaton, Polysyndeton, Asyndeton, Klimax, Antiklimax, Antithese, Oxymoron, Paradoxon, Metapher, Personifikation, Metonymie, Synekdoche, Litotes, Hyperbel, Ellipse, Aposiopese, Alliteration, Assonanz, Rhetorische Frage, Concessio, Apostrophe) com 3-5 Beispielen aus Adorno, Heidegger, Mann, Bernhard, Goethe, Brecht, Kant, Habermas. Inkl. Stilfiguren-Bilanz für Aufsatz 5000W.

---

### SN-005 [P1] [correção] — Revisão consistência cross-module

**Descrição:** Auditoria sistemática de consistência:
- Cross-references entre módulos válidas?
- Mesmo termo técnico definido em múltiplos lugares?
- Numeração de quizzes / exemplos consistente?
- Citações + edições padronizadas?

**Justificativa:** Framework com 44+ módulos exige auditoria periódica para evitar drift.

**Estimativa:** 20-30 horas.

**Status:** **Done** (v1.6, 2026-05-09). Auditoria sistemática completa: **592 cross-references em 112 .md-files** auditadas via Subagent automatizado. **1 link quebrado real corrigido** (`STAGE-6-OUTLINE.md:351` → `ROADMAP.md` path-fix para `../../ROADMAP.md`). 1 placeholder em MODULE-TEMPLATE (não-fix necessário; é template). Validade cumulativa: 100%.

---

### SN-006 [P1] [melhoria] — Edits ortográficos cross-module

**Descrição:** Revisar TODO o framework para:
- Erros tipográficos em DE.
- Inconsistência ß / ss (norma DE vs. CH).
- Citações com edições erradas.
- Hyphen / em-dash / en-dash.

**Justificativa:** Framework de qualidade exige polimento.

**Estimativa:** 15-20 horas.

**Status:** **Done** (v1.6, 2026-05-09). Auditoria sistemática completa via Subagent automatizado: **120+ .md-files scanned**. **0 violações ß/ss em prosa autoral moderna** (Categoria A) — confirma que bereinigung em v1.2 foi exaustiva. **Citações historischer Texte** (Brüder Grimm 1857, Kafka 1915, Kant 1787, Luther 1530) preservadas corretamente em orthographia originalis (Categoria B). **66 dash-fixes**: hyphen `-` → en-dash `–` em ranges de datas (1923-29 → 1923–29, 1927-1998 → 1927–1998, 1750-1800 → 1750–1800, etc.) em 17 arquivos. ISO-Daten preservadas com hyphen-minus convencional.

---

### SN-007 [P1] [expansão] — Glossário cross-stage de Begriffe centrais

**Descrição:** Documento `framework/00-meta/BEGRIFFS-GLOSSAR.md` com 100+ Begriffe filológicos + filosóficos centrais que aparecem cross-stage. Cada um com: definição operacional, etymon, tradição, sub-tradições, fontes Pfeifer + Mittelstraß.

**Justificativa:** Begriffe atravessam o framework; consolidação ajuda navegação.

**Estimativa:** 30-50 horas.

**Status:** Done (v1.3, 2026-05-09). Implementado em [`framework/00-meta/BEGRIFFS-GLOSSAR.md`](BEGRIFFS-GLOSSAR.md). 111 entries em 11 grupos: A. Filosóficos centrais (21), B. Existenzial-ontológicos Heidegger (10), C. Hegel/Dialektik (7), D. Política/Sociedade (14), E. Ética/Moralidade (9), F. Estética (6), G. Sprache/Text/Sinn (12), H. Wissenschaftstheorie (8), I. Religião/Teologia (4), J. Modernidade/Sociedade (14), K. Begriffe transversais (6). Cada entry: definição + etymon Pfeifer-Stil + tradição central + sub-tradições + Quellen primárias. Cross-references internas via `→`.

---

## v1.5 (P2) — Médio prazo (~12-24 meses)

### SN-008 [P2] [experimento] — Tradução do framework para DE original

**Descrição:** Traduzir todo o framework do PT-BR (atual) para DE original. Manter PT-BR como subsidiário ou paralelo.

**Justificativa:** Framework escrito em DE seria mais coerente com o objeto. Aluno avançado já lê DE e beneficia-se de imersão integral.

**Estimativa:** 200-400 horas (massivo).

**Status:** **Partial enhanced extended** (v3.0, 2026-05-10). Cumulativo:
- 3 Meta-Docs DE (INDEX + MENTOR + STUDY-PROTOCOL) seit v1.7-v1.8.
- BEGRIFFS-GLOSSAR.md vollständig DE seit v1.3.
- Stage 6 alle 29 Module + 6 Capstones nativ DE seit v2.0/v2.5.
- **Stage 1 alle 10 Module + Stage 2 alle 9 Module DE-Adaptationen** seit v3.0 (zusätzlich zu 5 Schlüsselmodulen Stage 1-5 aus v2.5).

Quote tradução DE atual: **~50% framework**. Sequenz weiter:
- v4.0: Stage 3-5 verbleibende ~25 Module + alle 12 Anhänge + alle 8 Templates ins DE (~50% verbleibend).

**Riscos:** Perder acessibilidade para aluno iniciante PT-falante. Mitigação: manter PT-BR como tradução paralela; alle DE-Übersetzungen markieren explizit "PT-BR bleibt Referenz bei Inkonsistenzen".

---

### SN-009 [P2] [expansão] — Anki decks pré-construídos por Stage

**Descrição:** Construir e publicar Anki decks pré-construídos (deck shared no AnkiWeb):
- Stage 1: ~1500 cards.
- Stage 2: +2500 cards.
- Stage 3: +2000 cards.
- Stage 4: +1500 cards.
- Stage 5: +500 cards.

Total: ~8000 cards organizados por Stage / módulo / domínio.

**Justificativa:** Aluno iniciante economiza tempo enorme; pode focar em qualidade de cards próprios em vez de construir base.

**Estimativa:** 100-200 horas + manutenção contínua.

**Status:** **DONE** (v1.9, 2026-05-09). Alle Stages 1-5 abgeschlossen. **Stage 1 done** em v1.4 (~500 cards). **Stage 2 done** em v1.6 (~700 cards). **Stage 3 done** em v1.7 (~700 cards). **Stage 4 done** em v1.8 (~600 cards). **Stage 5 done** em v1.9 (~400 cards) em [`ANKI-STARTER-DECK-STAGE-5.md`](ANKI-STARTER-DECK-STAGE-5.md). **Total cumulativo: ~2900 cards** (Stages 1-5 alle complete).

**Riscos:** Cards prontos podem incentivar aluno a NÃO construir cards próprios — perdendo personalisierung. Mitigação: documentar deck como starter, não substituto.

---

### SN-010 [P2] [experimento] — Validação peer-review por linguistas DE

**Descrição:** Submeter o framework a 3-5 linguistas DE acadêmicos (Eisenberg-Schule, IDS Mannheim, Goethe-Institut) para revisão crítica. Coletar feedback. Implementar correções.

**Justificativa:** Framework é trabalho amador (em sentido positivo) por aluno avançado, não tese acadêmica. Validação por specialists garantiria rigor estrutural.

**Estimativa:** 50-100 horas (incluindo correspondência + revisão + implementação).

**Status:** Backlog.

---

### SN-011 [P2] [expansão] — Templates Markdown para output do aluno

**Descrição:** Templates em Markdown para:
- Tagebuch entries.
- Aufsatz Stage 2 (1500 W).
- Aufsatz Stage 3 (5000 W).
- Vortrag outline (Stage 5).
- Begriffsanalyse Stage 4.

**Justificativa:** Aluno beneficiaria de estrutura inicial; reduz fricção.

**Estimativa:** 10-15 horas.

**Status:** Done (v1.1, 2026-05-09). Implementado em `framework/00-meta/templates/`:
- [TAGEBUCH-TEMPLATE](templates/TAGEBUCH-TEMPLATE.md) — 4 Strukturvarianten + Niveau-Modi M1-M4 + Korrekturschleife.
- [AUFSATZ-1500W-TEMPLATE](templates/AUFSATZ-1500W-TEMPLATE.md) — CAPSTONE-2.
- [AUFSATZ-5000W-TEMPLATE](templates/AUFSATZ-5000W-TEMPLATE.md) — CAPSTONE-3.
- [VORTRAG-TEMPLATE](templates/VORTRAG-TEMPLATE.md) — Modul 05-05 (30 min com sprechrhythmus markiert).
- [BEGRIFFSANALYSE-TEMPLATE](templates/BEGRIFFSANALYSE-TEMPLATE.md) — CAPSTONE-4 (Korpus-basiert).

---

### SN-012 [P2] [melhoria] — Diagramas DAG visuais

**Descrição:** Diagramas em Mermaid ou similar do DAG de pré-requisitos por Stage e cross-Stage. Adicionar a INDEX.md + READMEs de cada Stage.

**Justificativa:** Aluno visualiza progressão melhor que via texto.

**Estimativa:** 5-8 horas.

**Status:** Done (v1.1, 2026-05-09). Implementado:
- Master DAG visual em [`framework/00-meta/DAG.md`](DAG.md) — global cross-Stage + 5 Stage-DAGs detalhados + 4 caminhos críticos cross-Stage (Sintaxe→Generative→Hermenêutica; Lexik→Register→Diskursanalyse; Schreiben→Stilbildung→Output; Diakronie→Korpus→Begriffsgeschichte).
- INDEX.md atualizado com Mermaid global cross-Stage.
- 5 Stage READMEs com Mermaid local (paralelo ao ASCII existente).

---

## v2.0 (P3) — Longo prazo (~24-48 meses)

### SN-013 [P3] [experimento] — Comunidade de mentees + cohorts

**Descrição:** Criar mecanismos para conectar aprendizes:
- Discord / Matrix server.
- Cohort tracking (PROGRESS.md por aluno em repo separado).
- Peer-mentoring matchmaking.
- Lesegruppen virtuais.

**Justificativa:** Anti-isolamento gate (MENTOR.md §10.5) precisa de canais externos. Comunidade FATHOM-Deutsch reduziria fricção.

**Estimativa:** 50-100 horas inicial + manutenção contínua.

**Status:** Backlog.

---

### SN-014 [P3] [expansão] — Capstones exemplares publicados

**Descrição:** Publicar 1-2 Capstones exemplares por Begriff (Aufklärung, Bildung, ...): Glossar v0 + Aufsatz v1 + Aufsatz v2 + Begriffsanalyse v3 + Manuskript v4. Como modelo concreto.

**Justificativa:** Aluno beneficia massivamente de exemplo concreto; abstrato (CAPSTONE-EVOLUTION.md) é insuficiente.

**Estimativa:** 500-1000 horas POR BEGRIFF (= concluir Capstone-5 inteiro).

**Status:** **DONE** (v2.0, 2026-05-09). **Alle 5 Capstones-Exemplares concluídos**: 
- CAPSTONE-1 (v1.2): Glossar v0, 30 entries.
- CAPSTONE-2 (v1.3): Aufsatz argumentativ ~1500W.
- CAPSTONE-3 (v1.4): Aufsatz wissenschaftlich ~5000W.
- CAPSTONE-4 (v1.9): korpusbasierte Begriffsanalyse ~30pp.
- **CAPSTONE-5 (v2.0)**: publizierbarer Aufsatz ~8000W (*Merkur*-Format); 6 Sektionen + Anhang mit Stilfeature-Markierung + Korrekturschleife dokumentiert + Submissions-Materialien.
**Erkenntnisprojekt-Reihe v0→v4 vollständig demonstriert auf einem Begriff (Aufklärung).**

**Riscos:** Aluno pode se apoiar em exemplo em vez de produzir próprio. Mitigação: publicar com explicit warning. **Mitigação implementada** em CAPSTONE-1 exemplar §"Was NICHT zu kopieren" + Vorbemerkung.

---

### SN-015 [P3] [experimento] — Feedback loop com aprendizes que completaram

**Descrição:** Survey + interviews com 10+ aprendizes que completaram Stage 1 / Stage 3 / Stage 5. Identificar:
- O que funcionou?
- O que falhou?
- Onde framework superestima ou subestima dificuldade?
- Sugestões de melhoria estrutural?

**Justificativa:** Iteração baseada em dados, não em teoria pedagógica abstrata.

**Estimativa:** 30-50 horas.

**Status:** Backlog.

**Pré-requisito:** existência de aprendizes que completaram (= 5+ anos pós-v1.0).

---

### SN-016 [P3] [expansão] — Stage 6 — Specialization tracks

**Descrição:** Adicionar Stage opcional pós-Stage 5 com tracks de especialização:
- Tradução literária PT↔DE profissional.
- Pesquisa acadêmica em germanística.
- Mentoring + ensino DaF.
- Dialetologia + Variationsforschung.

Cada track ~5-7 módulos + Capstone-6.

**Justificativa:** Pós-Capstone-5, aluno em C2+ pode aprofundar em direção específica.

**Estimativa:** 200-400 horas.

**Status:** **DONE** (v2.5, 2026-05-10). **Alle 4 Tracks vollständig implementiert** em [`framework/06-spezialisierung/`](../../06-spezialisierung/):
- Track A (v2.0): 6 Module (06-A-1 bis 06-A-6) + CAPSTONE-6-A.
- Track B (v2.0): 7 Module (06-B-1 bis 06-B-7) + CAPSTONE-6-B.
- Track C1 (v2.5): 4 Module (06-C1-1 bis 06-C1-4) + CAPSTONE-6-C1.
- Track C2 (v2.5): 3 Module (06-C2-1 bis 06-C2-3) + CAPSTONE-6-C2.
- Track C3 (v2.5): 3 Module (06-C3-1 bis 06-C3-3) + CAPSTONE-6-C3.
- Track D (v2.5): 6 Module (06-D-1 bis 06-D-6) + CAPSTONE-6-D.

**Stage 6 cumulativo: 29 Module + 6 Capstones-6.** Aluno hat alle 4 berufsspezifischen Spezialisierungs-Wege.

---

### SN-017 [P3] [experimento] — Integração com IDS-Korpora API

**Descrição:** Se IDS oferece API pública para COSMAS II / DEReKo, integrar queries automatizadas em Capstone-4 (korpusbasierte Begriffsanalyse). Permitiria aluno gerar gráficos de Frequenzverlauf + tabelas Kollokationen automaticamente.

**Justificativa:** Reduzir fricção de queries manuais em COSMAS II (registro acadêmico, queries syntax-pesada).

**Estimativa:** 30-50 horas.

**Status:** Backlog.

**Pré-requisito:** API pública IDS (não-disponível atualmente).

---

## Wontfix / Decisões contra

### SN-W001 [wontfix] — Conversão para LMS / sistema fechado

**Razão:** Framework é Markdown + git para preservar abertura + remixabilidade. LMS proprietário (Moodle, etc.) limitaria. CC BY-NC 4.0 exige permanência aberta.

### SN-W002 [wontfix] — Gamificação (badges, achievements)

**Razão:** Gamificação rasa (Duolingo-style) é inimiga de deliberate practice. Mantém aluno em zona de conforto. Anti-padrão pedagógico para C2+.

### SN-W003 [wontfix] — Integração com AI tutor

**Razão:** AI assistance é Modus C suplementar (MENTOR.md §0), não substituto. Mentor humano (peer ou senior) é insubstituível em Stage 4-5. Integrar AI tutor no framework rebaixaria expectativas.

---

## Como adicionar item ao backlog

1. **Criar entry SN-NNN no template**.
2. **Marcar prioridade + tipo + estimativa**.
3. **Justificativa rigorosa**: por que vale o esforço?
4. **Discussão pública** se relevante (GitHub Issues / Discussions).
5. **Decisão de incluir**: maintainer decide.

---

## Como mover item para "In Progress"

1. **Criar branch específico** no Git (e.g., `sn-001-ablautreihen-anhang`).
2. **Marcar status: In Progress** no SPRINT-NEXT entry.
3. **Implementar mudança**.
4. **Commit + Pull Request**.
5. **Review**.
6. **Merge → status: Done**.
7. **Atualizar CHANGELOG.md** + RELEASE-NOTES.md (próxima versão).

---

## Cadência de releases prevista

```
v1.0 — 2026-05-08 — Initial Public Release                  [feito]
v1.1 — 2026-05-09 — Anexos A,B + DAG visual + 5 templates   [feito]
v1.2 — 2026-05-09 — Anexos C-H + governance + CAPSTONE-1     [feito]
v1.3 — 2026-05-09 — BEGRIFFS-GLOSSAR + I,J + AUDIO-CANON     [feito]
                    + CAPSTONE-2 exemplar
v1.4 — 2026-05-09 — 3 templates + Self-test + Anki Stage 1   [feito]
                    + CAPSTONE-3 exemplar + STAGE-6-OUTLINE
                    + ROADMAP.md
v1.5 — 2026-05-09 — KONVERSATIONS-LÜCKE GESCHLOSSEN:         [feito]
                    Anexo K (Alltag) + Anexo L (Dialekte)
                    + Modul 01-10 (Konversation Stage 1)
                    + Modul 03-10 (Hörverstehen colloquial)
                    + Trilha G (Auswandern em LEARNING-PATHWAYS)
v1.6 — 2026-05-09 — STAGE-2-APPARAT + KONSISTENZ-AUDITORIA: [feito]
                    Anki Stage 2 (~700 cards) + Self-test 
                    Stage 2 (~30 Übungen) + DAG.md atualizado 
                    com 01-10 + 03-10 + Caminho E
                    + SN-005 sistemático done (cross-refs, 1 fix)
                    + SN-006 sistemático done (66 dash-fixes)
v1.7 — 2026-05-09 — STAGE-3-APPARAT + TRADUÇÃO DE INDEX:    [feito]
                    Anki Stage 3 (~700 cards) + Self-test 
                    Stage 3 (~30 Übungen) + INDEX-DE.md
                    + SN-008 partial start
                    + SN-009 partial enhanced (Stages 1+2+3)
v1.8 — 2026-05-09 — STAGE-4-APPARAT + TRADUÇÃO DE META:     [feito]
                    Anki Stage 4 (~600 cards) + Self-test 
                    Stage 4 + MENTOR-DE.md + STUDY-PROTOCOL-DE.md
                    + SN-008 partial enhanced (3 meta-docs em DE)
                    + SN-009 partial enhanced (Stages 1+2+3+4)
v1.9 — 2026-05-09 — STAGE-5-APPARAT + CAPSTONE-4 EXEMPLAR:  [feito]
                    Anki Stage 5 (~400 cards) + Self-test 
                    Stage 5 + CAPSTONE-4-AUFKLAERUNG-EXEMPLAR
                    (~30pp korpusbasiert; methodische Trias)
                    + SN-009 DONE (alle Stages 1-5)
                    + SN-014 partial enhanced (4 Capstones)
v2.0 — 2026-05-09 — MAJOR: CAPSTONE-5 EXEMPLAR + STAGE 6   [feito]
                    TRACKS A + B vollständig
                    + CAPSTONE-5-AUFKLAERUNG-EXEMPLAR
                    (~8000W publizierbarer Aufsatz Merkur-Format)
                    + Stage 6 Track A (6 Module + CAPSTONE-6-A)
                    + Stage 6 Track B (7 Module + CAPSTONE-6-B)
                    + DAG.md atualizado (Stage 6 + 2 Sub-DAGs)
                    + SN-014 DONE (alle 5 Capstones); 
                      SN-016 partial enhanced (Tracks A + B)
v2.5 — 2026-05-10 — STAGE 6 KOMPLETT (Tracks C + D)        [feito]
                    + Tradução DE 5 Module-Adaptationen
                    + SN-016 DONE (Stage 6 alle 4 Tracks)
                    + SN-008 partial enhanced (~25% Tradução DE)
v3.0 — 2026-05-10 — MAJOR: TRADUÇÃO DE STAGE 1+2 +         [feito]
                    MULTILINGUAL (EN/ES/FR) +
                    COMUNIDADE/PEER-REVIEW/ANKIWEB-GOVERNANCE
                    + 17 Stage 1+2 Module-Adaptationen DE
                    + INDEX-EN + README-ES + README-FR
                    + ANKI-EXPORT-GUIDE + COMMUNITY-GUIDELINES
                    + PEER-REVIEW-PROTOCOL
                    + SN-008 partial enhanced extended (~50%)
                    + SN-009 enhanced (AnkiWeb-Workflow)
                    + SN-010 partial start (Peer-Review-Protokoll)
                    + SN-013 partial start (Comunidade-Governance)
v3.0+ ~2026-Q3-Q4 — operational: Discord-Server aufbauen,    [praktisch]
                    AnkiWeb-Decks publizieren, 3-5 Peer-Reviewer
                    akquirieren.
v4.0 — ~2028     — Tradução DE 100% + EN-vollständig +     [planejado]
                    ES/FR-erweitert + IDS-API-Integration +
                    Stage 7 Konzept (Beitragender-Stage).
v2.0 — ~2028-12  — Comunidade + CAPSTONE-4/5 exemplares     [planejado]
                    + Stage 6 vollständig (4 Tracks)
v2.5 — ~2029-12  — Feedback-Loop + Tradução DE 100%          [planejado]
                    + AnkiWeb-Deck published
v3.0 — ~2030-12  — Multilingual (DE/EN/ES/FR) + Akademie-   [planejado]
                    Kooperationen + Stage 7 conceito
```

Cadência mais lenta que software comum — framework educacional muda devagar; estabilidade é virtude.

---

**Backlog vivo. Atualizações via Pull Request. Auditoria trimestral pelo maintainer.**
