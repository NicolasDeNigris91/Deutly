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

## DL-2026-05-09-009 — Anexos canônicos + Templates como diretórios separados

### Contexto

Em v1.1, ao implementar anexos exhaustivos (Ablautreihen, Modalverben) e templates de output (Tagebuch, Aufsätze, Vortrag, Begriffsanalyse), surgiu decisão de organização: integrar conteúdo em módulos existentes ou criar diretórios separados em `00-meta/`?

### Alternativas consideradas

1. **Integrar diretamente em módulos**: Ablautreihen em 01-03; Modalverben em 02-07; Templates em respectivos Capstones. Pros: leitura linear sem fragmentação. Contras: módulos ficariam massivos (>2000 linhas); referência consultável seria difícil de localizar; templates poderiam parecer prescritivos demais quando integrados ao corpo do Capstone.

2. **Diretórios separados em `00-meta/anhaenge/` e `00-meta/templates/`** (escolhido). Pros: separação semântica clara — módulos pedagógicos vs. referências consultáveis vs. scaffolds opcionais; navegação independente; arquivos podem evoluir em cadência distinta; cross-references explícitas mantêm integração. Contras: leitor precisa seguir links.

3. **Tudo num documento único** ("ANNEXES.md" + "TEMPLATES.md"): Pros: menos arquivos. Contras: arquivos ficariam massivos (>1500 linhas cada); diff em PRs seria difícil de revisar; não escalaria para v1.2 (FVG, Stilfiguren).

### Decisão tomada

Opção 2.

### Justificativa

- **Princípio de single-responsibility por arquivo**: pedagogia (módulos) vs. referência (anhaenge) vs. scaffold (templates) são funções distintas. Misturar tipos diferentes degrada legibilidade.
- **Escalabilidade**: v1.2 trará SN-003 (FVG 200+) e SN-004 (Stilfiguren com exemplos), também naturalmente Anhänge. v2.0 pode trazer mais templates (Übersetzung, Glosse). Estrutura de diretório acomoda.
- **Cross-reference explícita preserva integração**: cada módulo principal contém um marker (📚 ou 📋) que aponta ao Anhang/Template correspondente. Aluno encontra naturalmente.
- **Audit + manutenção**: editor pode atualizar uma tabela em ANHANG-A sem tocar 01-03; isso reduz risco de regressão em módulo pedagógico.

### Trade-offs aceitos

- **Leitor precisa navegar entre arquivos** para usar Anhang/Template enquanto estuda módulo. → Mitigação: cross-reference no topo da seção do módulo + back-link no final do Anhang.
- **Aumento de arquivos no `00-meta/`** de 16 para 17+ (DAG.md) + duas pastas com 7 arquivos. → Aceitável; INDEX.md atualizado para listar nova estrutura.

### Status

Active.

---

## DL-2026-05-09-010 — Worked examples como diretório separado `examples/`

### Contexto

Em v1.2, ao implementar SN-014 partial (Capstone-1 exemplar Aufklärung), surgiu decisão: integrar exemplar diretamente em CAPSTONE-fundamente.md, ou criar diretório separado `framework/00-meta/examples/`?

### Alternativas consideradas

1. **Integrar em CAPSTONE-fundamente.md** como Sektion §X "Beispiel" ao final. Pros: leitura linear. Contras: bloat do módulo (>2000 linhas com exemplar de 30 entries); pedagogia abstrata vs. exemplar concreto misturados; risco de aluno copiar sem ler regras.
2. **Diretório separado `examples/`** (escolhido). Pros: separação semântica clara entre "abstrakte Aufgabenbeschreibung" (módulo) e "konkretes Beispiel" (examples/); cross-link explícito força aluno a entender abstração antes de ver exemplar; warnings explícitas na pasta dedicada; escalável para futuros exemplares de Capstone-2/3/4/5.
3. **Em separate repo (Deutly-Examples)**: Pros: isolamento total. Contras: fragmentação do projeto; quebra de cross-references diretos; manutenção complicada.

### Decisão tomada

Opção 2: `framework/00-meta/examples/` com README.md indexador + warnings explícitas em cada exemplar.

### Justificativa

- **Risco pedagógico de cópia mitigado** por separação física + warnings explícitas em cada exemplar.
- **Escalabilidade**: ao implementar Capstone-2/3/4/5 exemplares (v2.0+), todos vão neste diretório.
- **Audit + manutenção**: editor pode atualizar exemplar sem tocar módulo pedagógico.
- **Análogo a anhaenge/ e templates/**: completa o trio "pedagogy / reference / scaffold / exemplar" = 4 funções distintas, 4 diretórios.

### Trade-offs aceitos

- **Aluno precisa navegar entre arquivos** para usar exemplar enquanto estuda CAPSTONE-fundamente. → Mitigação: cross-reference no topo do CAPSTONE-fundamente + back-link em cada exemplar.

### Status

Active.

---

## DL-2026-05-09-011 — Governance via .github/ + GitHub Actions (markdown-lint + link-check)

### Contexto

Em v1.2, framework tornou-se complex enough (12+ commits, 17+ docs meta, 50+ módulos) para benefit de CI/CD básico. Decisão: adicionar GitHub Actions, ou manter manual?

### Alternativas consideradas

1. **Sem CI**: manutenção manual. Pros: simplicidade. Contras: drift, broken links, markdown inconsistências detectados tarde.
2. **Markdown-link-check + markdownlint via GitHub Actions** (escolhido). Pros: automated catching de broken links em PRs + scheduled (semanal); markdown lint enforces consistência de formato; cost zero (free tier). Contras: aumento de complexity em .github/.
3. **Custom validation scripts (Node, Python)**: Pros: controle total. Contras: dependency management; complexity.

### Decisão tomada

Opção 2.

### Justificativa

- **Free tier GitHub Actions** suporta workflow weekly + per-PR sem custo.
- **Markdown-link-check** detecta link rot (especially DWDS, IDS-Grammis, Pfeifer URLs) — crítico para framework com ~100+ external references.
- **Markdownlint** padroniza formato; reduz fricção de PR review.
- **Configurações em JSON** (`.github/markdownlint.json`, `.github/markdown-link-check-config.json`) versionadas — explicit, auditable.

### Trade-offs aceitos

- **Workflow precisa GitHub Actions habilitado** no repo (já está, mas ConfigDrift possible).
- **Configurações são opinativas** (e.g., MD013 desabilitada = sem limite de linha) — refletem priorização de prosa densa sobre formatting estrito.

### Status

Active.

---

## DL-2026-05-09-012 — Auditoria parcial: orthographia historisch preservada vs. moderna corrigida

### Contexto

Em auditoria pragmática (v1.2), questão: como tratar `daß / mußte / wußte / großse` (orthographia anterior à Rechtschreibreform 1996) vs. `dass / musste / wusste / große` (orthographia moderna)?

### Alternativas consideradas

1. **Tudo moderno**: corrigir até em citações historischer Texte. Contras: anachronismus + descaracterização das fontes; Kafka 1915 escreveu `daß` — substituir é falsificação textual.
2. **Tudo histórico**: preservar `daß` em todos contextos. Contras: framework ensina **DE moderno** (Rechtschreibreform 1996/2006); aluno aprenderia ortografia obsoleta.
3. **Distinção rigorosa** (escolhido): orthographia historisch preservada **só em citações primárias de textos pre-1996**; orthographia moderna em prosa do framework + paradigmas modernos + exemplos invented.

### Decisão tomada

Opção 3.

### Justificativa

- **Princípio da fidelidade textual**: citações de Kafka, Goethe, Grimm, Kant, Luther, Schiller etc. **devem** preservar orthographia da Quelle (Akademie-Ausgabe ou edição canônica).
- **Princípio da norma vigente**: framework ensina norma **atual** (post-Rechtschreibreform). Em paradigmas (e.g., listagem de Modalverben em §2 de 01-03), orthographia atual é correto.
- **Distinção explícita**: a coexistência de `dass` (norma) + `daß` (Kafka 1915) em mesmo módulo é **pedagogicamente valiosa** — aluno aprende variabilidade ortográfica histórica.

### Trade-offs aceitos

- **Aluno pode confundir-se** ao ver `daß` em texto-âncora e `dass` no metatexto. Mitigação: futura inserção de Anmerkung explícita no início de módulos com Belege historisch (`framework/01-fundamente/01-03-verbalsystem.md` e similares).

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
