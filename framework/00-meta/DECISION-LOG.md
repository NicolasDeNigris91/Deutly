# DECISION-LOG — Decisões estruturais documentadas

> Log de **decisões estruturais** do framework. Referenciado em MENTOR.md §10.2. Cada entrada documenta uma escolha não-trivial de design + sua justificativa, para auditoria + futura reflexão.

---

## Convenção

```
## DL-YYYY-MM-DD-NNN — [Decisão curta]

**Contexto:**
[Situação que motivou a decisão]

**Alternativas consideradas:**
1. [Opção A] — pros: [...]; contras: [...]
2. [Opção B] — pros: [...]; contras: [...]
3. [...]

**Decisão tomada:**
[Opção escolhida]

**Justificativa:**
[Por que essa opção; raciocínio + fontes]

**Trade-offs aceitos:**
[O que se perde com essa escolha]

**Status:**
[Active / Superseded by DL-XXX]
```

---

## DL-2026-05-08-001 — Estrutura em 5 Stages encadeados (em vez de currículo modular)

### Contexto

Decisão fundamental no design do framework: como organizar progressão A1→C2+?

### Alternativas consideradas

1. **Currículo modular não-sequencial**: aluno escolhe módulos conforme interesse. Pros: flexibilidade. Contras: lacunas estruturais; sem garantia de pré-requisitos.
2. **CEFR-stage strict**: A1, A2, B1, B2, C1, C2 como estágios. Pros: alinhamento com norma internacional. Contras: CEFR é descritivo, não estrutural; força conteúdo errado em estágios errados (e.g., Konjunktiv I aparece muito tarde).
3. **5 Stages com pré-requisitos bloqueantes** (escolhido): Fundamente → Struktur → Stil → System → Meisterschaft. Pros: progressão filológica natural; sintaxe → estilística → linguística → output. Contras: rigidez aparente; demanda commitment longo.

### Decisão tomada

Opção 3.

### Justificativa

Aprendizagem L2 adulta beneficia-se de **estrutura forte com pré-requisitos**: sem fundação sintática (Stage 1-2), estilística (Stage 3) é exercício vazio; sem estilística, hermenêutica (Stage 4-10) é tateamento; sem hermenêutica, output público (Stage 5) é mecânico. CEFR é referência mas não estrutura; estrutura emerge de **lógica filológica do alemão** + **lógica pedagógica adulta** (cf. Ericsson 2016 *Peak* sobre deliberate practice).

### Trade-offs aceitos

- Aluno não-acadêmico (Trilha E) pode considerar Stage 4 over-engineered. → Mitigação: trilha alternativa documentada (LEARNING-PATHWAYS.md).
- Tempo total massivo (2-5 mil horas). → Aceitável para C2+ World Class genuíno.

### Status

Active.

---

## DL-2026-05-08-002 — Capstones encadeados em torno de UM Begriff (em vez de projetos diversos)

### Contexto

Como organizar Capstones (Stage 1: Glossar; Stage 2: Aufsatz 1500 W; Stage 3: Aufsatz 5000 W; Stage 4: Begriffsanalyse korpusbasiert; Stage 5: Veröffentlichung)?

### Alternativas consideradas

1. **Capstones diversos não-relacionados**: cada Stage com tema próprio. Pros: variedade. Contras: aluno não desenvolve profundidade em nenhum tema; dispersão.
2. **Capstones encadeados em torno de UM Begriff** (escolhido): Erkenntnisprojekt v0→v4 sobre 1 Begriff escolhido em Stage 1. Pros: profundidade; tradição filológica; output cumulativo; saturação lexical natural; mentoring focado. Contras: aluno fica preso a Begriff escolhido se interesse muda.
3. **Capstones por trilha**: cada trilha tem Capstones específicos. Pros: alinhamento. Contras: complexidade exponencial.

### Decisão tomada

Opção 2.

### Justificativa

Aprendizagem profunda em germanística filosófica beneficia-se de **um único objeto sustentado**. Tradição: Begriffsgeschichte (Brunner/Conze/Koselleck) opera assim; pesquisadores acadêmicos comprometem-se com Begriffe singulares por décadas (Habermas com Aufklärung, Adorno com Identität, Heidegger com Sein). FATHOM-Deutsch reproduz essa lógica em escala de aprendizagem.

Risk de fixação em Begriff: mitigado por **mudança documentada via DECISION-LOG** (não casual; mas legítima em audit).

### Trade-offs aceitos

- Aluno descobre que Begriff inicial não é central → Mudança via DECISION-LOG entry justificada.
- Aprendiz não-acadêmico (Trilha E) pode achar Erkenntnisprojekt over-engineered → Mitigação: Trilha E modifica volume de Capstones.

### Status

Active.

---

## DL-2026-05-08-003 — 3 Tore obrigatórios por módulo (em vez de avaliação aberta)

### Contexto

Como avaliar progressão por módulo?

### Alternativas consideradas

1. **Avaliação informal (self-evaluation)**: aluno decide quando passou. Contras: auto-engano massivo.
2. **3 Tore (Konzeptuell + Praktisch + Verbindungen)** (escolhido). Pros: estruturado, replicável, mentoreável. Contras: rigidez.
3. **Tor único**: simplificar. Contras: perde dimensões (conceito, prática, integração).

### Decisão tomada

Opção 2 com critérios em RUBRIC.md.

### Justificativa

Pedagogia adulta L2 (Ericsson, Karpicke, Bjork) demonstra que **deliberate practice + feedback imediato + critérios explícitos** maximizam progressão. 3 Tore operacionalizam: conceitual (Active Recall via perguntas em folha branca); prático (output corrigido por Loop de Refinamento); conexões (integração inter-módulos via spaced re-test).

### Trade-offs aceitos

- Tempo investido por Tor (~30-60 min cada). → Aceitável para profundidade.
- Risk de "passar por exhaustão" em self-mentor. → Mitigação: audit retrospectivo a cada 90 dias (MENTOR.md §10.4).

### Status

Active.

---

## DL-2026-05-08-004 — Frasal cards canônico em Anki (em vez de cards de palavra-tradução)

### Contexto

Como construir Anki deck para FATHOM-Deutsch?

### Alternativas consideradas

1. **Cards isoladas de palavra-tradução**: tradição comum em Goethe-listas. Pros: rápido. Contras: sem Genus/Kasus/Kollokação; vocabulário passivo.
2. **Frasal cards baseadas em Beleg autêntico** (escolhido). Pros: contexto preservado; flexão crítica codificada; Kollokationen visíveis. Contras: mais lento construir.
3. **Cards de fluência (cloze)**: misto. Pros: balance. Contras: ainda perde contextos.

### Decisão tomada

Opção 2, documentada em ANKI-FRAMEWORK.md.

### Justificativa

Pesquisa em Wortschatz-Erwerb adulto (Schmitt 2010, Niemeier 2019, Tschirner/Möhring 2019) demonstra superioridade de cards contextuais. Card isolada falha em codificar Genus, Kasus, Rektion, Kollokation, Stilstufe — todos esquivos sem contexto. Frasal card resolve.

### Trade-offs aceitos

- Tempo de construção: ~2-5 min por card vs. 30s para card isolada. → Aceitável dado retention superior.
- Anki deck cresce mais lentamente em quantidade. → Aceitável dado qualidade.

### Status

Active.

---

## DL-2026-05-08-005 — Konj. I em Reportativ como norma cross-stage (em vez de optional)

### Contexto

Como tratar Konj. I em discurso indireto?

### Alternativas consideradas

1. **Konj. I optional**: como em fala coloquial DE. Pros: fácil. Contras: produzir Aufsatz acadêmico em Indikativ é Stilbruch.
2. **Konj. I obrigatório em Reportativ acadêmico** (escolhido). Pros: norma jornalística + acadêmica DE; preserva distância editorial. Contras: aprendizado tardio para PT-falantes.

### Decisão tomada

Opção 2, com módulo dedicado (02-02).

### Justificativa

Aufsatz acadêmico DE de qualidade exige Konj. I em discurso indireto. Sem dominá-lo, aluno produz prosa indistinguível de jornalismo popular. Konj. I é parte do padrão Wissenschaftsdeutsch hoch que CAPSTONE-3+ exige.

### Trade-offs aceitos

- Curva de aprendizado mais íngreme em Stage 2. → Aceitável.

### Status

Active.

---

## DL-2026-05-08-006 — Plurizentrik DE/AT/CH como norma equivalente (em vez de Bundesdeutsch único)

### Contexto

Como tratar variantes nacionais DE?

### Alternativas consideradas

1. **Bundesdeutsch como única norma**: tradição prescritivista clássica. Pros: simples. Contras: trata austríaco/suíço como "desviante", o que é factualmente errado.
2. **Plurizentrik com 3 normas equivalentes** (escolhido). Pros: alinhamento com Ammon 1995 + sociolinguística moderna; respeita variação. Contras: mais complexidade para aprendiz iniciante.

### Decisão tomada

Opção 2, com módulo dedicado (04-03) + integração em 03-02.

### Justificativa

DE é língua plurizentrik documentada (Ammon 1995, Schmidlin 2011). Tratar AT 'Marille' como erro é equivalente a corrigir 'lift' britânico para 'elevator' americano. Aluno avançado (C1+) deve reconhecer e respeitar.

### Trade-offs aceitos

- Aluno iniciante (A1-A2) escolhe um (default Bundesdeutsch); aprofundamento em Stage 4. → Aceitável progressão.

### Status

Active.

---

## DL-2026-05-08-007 — Tradução PT↔DE como Trilha D + módulo 05-03 (em vez de subsidiária)

### Contexto

Como tratar tradução em FATHOM-Deutsch?

### Alternativas consideradas

1. **Tradução como atividade subsidiária**: integrada apenas em 04-09. Pros: simples. Contras: subestima importância para aprendiz lusófono.
2. **Trilha D dedicada + Modul 05-03 Übersetzungstheorie + Praxis** (escolhido). Pros: reconhece tradução como output legítimo de Stage 5; suporta tradutores literários/filosóficos. Contras: complexidade.

### Decisão tomada

Opção 2.

### Justificativa

Para aluno lusófono adulto, tradução PT↔DE é forma de output **muito comum** (mais comum que publicação acadêmica original em DE). Subestimá-la = perder uma trajetória legítima. Trilha D reconhece + estrutura.

### Trade-offs aceitos

- Aumento da complexidade de LEARNING-PATHWAYS.md (6 trilhas vs. 5). → Aceitável.

### Status

Active.

---

## DL-2026-05-08-008 — Sem Co-Authored-By: Claude em commits

### Contexto

Quando o framework foi escrito com assistência da Claude (Anthropic AI Assistant), como atribuir authorship?

### Alternativas consideradas

1. **Co-Authored-By: Claude trailer**: sinaliza assistência AI. Pros: transparência. Contras: contradiz instrução explícita do mantenedor.
2. **Author = Nicolas De Nigris apenas, sem AI attribution** (escolhido). Pros: alinhamento com instrução do mantenedor; framework é trabalho intelectual + curatorial do mantenedor. Contras: ausência de transparência sobre AI assistance.

### Decisão tomada

Opção 2, conforme instrução explícita do mantenedor (`~/.claude/CLAUDE.md`).

### Justificativa

Mantenedor estabeleceu como diretriz global: "Never add `Co-Authored-By: Claude` ... in any repository". Decisão respeitada cross-commit. Framework intellectual content é responsabilidade autoral de Nicolas De Nigris (curatorial + editorial decisions); AI assistance é instrumental, não co-autoral.

### Trade-offs aceitos

- Menor transparência sobre processo de produção. → Mitigação: este DECISION-LOG entry documenta a escolha.

### Status

Active.

---

## DL-template para entradas futuras

```markdown
## DL-YYYY-MM-DD-NNN — [Decisão curta]

**Contexto:**

**Alternativas consideradas:**
1. ...
2. ... (escolhido)
3. ...

**Decisão tomada:**

**Justificativa:**

**Trade-offs aceitos:**

**Status:** Active / Superseded by DL-XXX
```

---

## Como adicionar entrada

1. Identificar decisão estrutural (não-trivial, com alternativas reais consideradas).
2. Adicionar entrada no template.
3. Numerar sequencialmente: `DL-YYYY-MM-DD-NNN` (NNN = ordem do dia).
4. Commit com mensagem específica: `DECISION-LOG: DL-YYYY-MM-DD-NNN [decisão curta]`.

---

## Não-aplicável a

- Edits ortográficos.
- Adições de exemplos em módulos existentes.
- Atualizações de referências bibliográficas.
- Tipos de mudanças menores.

(Para essas: CHANGELOG.md basta.)

---

**Decisões estruturais documentadas = framework auditável + reflexivo + emendável conscientemente.**
