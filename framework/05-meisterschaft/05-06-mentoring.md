---
module: 05-06
title: Mentoring von Lernenden
stage: meisterschaft
prereqs: [01-01, 01-02, 01-03, 01-04, 01-05, 01-06, 01-07, 01-08, 01-09, 02-01, 02-02, 02-03, 02-04, 02-05, 02-06, 02-07, 02-08, 02-09, 03-01, 03-02, 03-03, 03-04, 03-05, 03-06, 03-07, 03-08, 03-09, 04-01, 04-02, 04-03, 04-04, 04-05, 04-06, 04-07, 04-08, 04-09, 04-10]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em FATHOM-Deutsch, qual a postura do mentor (Self-Mentor, Peer ou Senior)?"
    options:
      - "Apoio amigável."
      - "**Germanist Senior + Linguistik-Examinator + Stilkritiker** (cf. MENTOR.md §2). DEVE: tratar cada output como Aufsatz a corrigir; citar regra com § da fonte canônica; recusar 'soa bem' como justificativa; forçar produção. NÃO PODE: aceitar erro com 'kommt schon vor'; suavizar para não desmotivar; sugerir resposta antes do aluno tentar; usar emojis. Tom: técnico, seco, respeitoso."
      - "Variação dialetal."
      - "Apenas pedagógico."
    correct: 1
    explanation: "Mentor postura é definida em MENTOR.md §2. Não é apoio amigável (terapia). É avaliação técnica rigorosa. Princípios: Aufsatz como objeto de correção; citação de regra com §; rejeição de 'soa bem'; forçar produção (Output Hypothesis). Aplicado consistentemente em self-mentor, peer-mentor, e senior-mentor. Em Stage 5 §05-06: aluno torna-se mentor de outros — aplica essa postura aos próprios mentees."
  - q: "Em **Loop de Refinamento** aplicado a output de mentee, quais 4 camadas?"
    options:
      - "Apenas gramatical."
      - "**(1) Grammatik (correção estrutural com regra + § da fonte); (2) Lexikalische Präzision (sinônimo mais exato + Kollokationen DWDS); (3) Stil (registro adequado + Stilfiguren + Stilbruch detection); (4) Native erudite ear (versão final 'como Habermas escreveria').** Cada camada é chain-of-thought explícita (cf. MENTOR.md §1). Output: BLOCKING > MAJOR > NIT classification + Begründungsfragen."
      - "Variação dialetal."
      - "Apenas pedagógico."
    correct: 1
    explanation: "Loop de Refinamento (cf. MENTOR.md §1) é núcleo do FATHOM-Deutsch. 4 camadas em ordem: Grammatik → Lexikalische Präzision → Stil → Native erudite. Cada camada chain-of-thought explícita. Output: classificação BLOCKING (= agramatical, falha de comunicação) > MAJOR (= sinaliza não-nativo) > NIT (= deslize estilístico) + 5 Begründungsfragen sobre escolhas. Aplicado consistentemente em todos Tore practicos (cf. RUBRIC.md)."
  - q: "Em **3 Tore (Portões)** aplicados a mentee em estado avançado, qual a sequência?"
    options:
      - "Apenas escrita."
      - "**(1) Konzeptuelles Tor: 5-8 perguntas em ordem aleatória sobre Harte Theorie do módulo, exigindo árvore + Gegenbeispiel + explicação interna; (2) Praktisches Tor: Loop de Refinamento completo sobre output do mentee + 5 Begründungsfragen; (3) Verbindungstor: 2-3 conexões com módulos anteriores.** Os 3 portões precisam passar para módulo virar 'done'. Falha = re-tentativa em 48h+. Cf. MENTOR.md §3 + RUBRIC.md."
      - "Variação dialetal."
      - "Apenas pedagógico."
    correct: 1
    explanation: "3 Tore obrigatórios: Konzeptuelles → Praktisches → Verbindungstor. Konzeptuelles: 5-8 perguntas sobre Harte Theorie em ordem aleatória, exigindo árvore + Gegenbeispiel + explicação interna. Praktisches: Loop de Refinamento + 5 Begründungsfragen sobre output. Verbindungstor: conexões com módulos anteriores (mínimo 2). Os 3 precisam passar; falhar = re-tentativa em 48h+ com perguntas diferentes. Aplicado consistentemente em mentoring."
  - q: "Em **pedagogia adulta de L2 (DaF/DaZ)**, que **3 técnicas centrais** sustentam aprendizagem em Stage 4-5?"
    options:
      - "Apenas memorização."
      - "**(1) Deliberate Practice (Ericsson): foco na fronteira de habilidade, com feedback imediato + correção; (2) Active Recall + Spaced Repetition (Anki): forçar recuperação ativa em intervalos crescentes; (3) Output Hypothesis (Swain 1985): produção (escrita/fala) força noticing-the-gap.** Combinação: prática focada + retenção sistematizada + produção iterada. Cf. STUDY-PROTOCOL.md §1-§4."
      - "Variação dialetal."
      - "Apenas teórico."
    correct: 1
    explanation: "STUDY-PROTOCOL.md sintetiza 12 técnicas cognitivas obrigatórias para L2. Núcleo Stage 4-5: Deliberate Practice (Ericsson 2016 *Peak*) + Active Recall + Spaced Repetition (Karpicke/Roediger 2008 + Bjork *desirable difficulty*) + Output Hypothesis (Swain 1985). Combinadas, sustentam progresso de C1 a C2+. Mentor de mentees Stage 5: aplica + reforça essas técnicas na prática mentee."
  - q: "Em **anti-isolamento gate** (cf. MENTOR.md §10.5), após quanto tempo solo o mentee deve estabelecer canal externo?"
    options:
      - "Não há limite."
      - "**6 meses solo (sem peer, sem mentor humano, sem cohort) → bloquear avanço temporariamente até estabelecer 1+ canal externo**: Tandem-Partner falante nativo, Lesegruppe, Universitäts-Sprachkurs Niveau Mittelstufe, OSS-Übersetzungsprojekt, ou similar. Solo absoluto detecta menos buracos prosódicos + pragmáticos. Aceitar o gate é sinal de mentor maduro."
      - "Variação dialetal."
      - "Apenas teórico."
    correct: 1
    explanation: "Anti-isolamento gate (MENTOR.md §10.5) é regra protetiva. Após 6 meses solo: bloquear avanço até canal externo estabelecido. Razão: solo detecta menos buracos (prosódicos, pragmáticos, sociolinguísticos). Canais válidos: Tandem-Partner nativo (apps Tandem/HelloTalk); Lesegruppe (book club em DE); Universitäts-Sprachkurs Niveau B2-C1; OSS-Übersetzungsprojekt (literatura DE pra PT). Mentor enforces gate em mentees após 6 meses solo. Quem ignora o gate plateauiza."
---

# 05-06, Mentoring von Lernenden

## 1. Sprachliches Problem

Em Stage 5, aluno aplica o que **aprendeu como aluno** **a outros mentees**. Mentor maduro (Senior-Germanist + Examinator + Stilkritiker) aplica RUBRIC.md, Loop de Refinamento, 3 Tore — não como ritual, mas como instrumento pedagógico calibrado.

Aprendizes adultos travam em:

- **Confundir mentoring com terapia / amizade**: suavizar correção; aceitar 'soa bem'.
- **Não dominar técnicas adultas de L2**: ignorar Deliberate Practice + Active Recall + Output Hypothesis.
- **Não aplicar RUBRIC.md sistematicamente**: avaliar por intuição.
- **Não enforces anti-isolamento gate**: deixar mentees plateauarem.

Sem este módulo, **maioria dos alunos abandona Stage 5** ou estagna em B2-C1. Mentoring rigoroso = continuidade do framework.

---

## 2. Harte Theorie

### 2.1 Postura do mentor (cf. MENTOR.md §2)

#### Identidade

**Germanist Senior + Linguistik-Examinator + Stilkritiker**. Não é apoio emocional, não é geração de código, não é amizade.

#### Princípios

```
DEVE:
- Tratar cada interação como avaliação.
- Exigir precisão técnica: 'acho que entendi' não passa.
- Sempre perguntar 'por quê?' e 'como funciona internamente?'.
- Forçar aluno a desenhar fluxos, dar contraexemplos, conectar com módulos anteriores.
- Sinalizar buracos sem suavização. Linguagem direta.
- Recusar pulos de etapa, pulos de portões, ou avanços sem prova.

NÃO PODE:
- Resolver os Aufgaben pelo aluno.
- Marcar Tor como passado sem prova real.
- Aceitar 'depois eu volto nisso'.
- Usar emojis.
- Inflar respostas com elogios performáticos.

POSTURA PADRÃO: assuma que o aluno ainda não sabe até prova em contrário.
```

### 2.2 Loop de Refinamento aplicado a mentee

Cf. MENTOR.md §1. Cada output (Aufsatz, Tagebuch-Entry, Vortrag transcrito) passa por **chain-of-thought explícita em 4 camadas**.

#### Exemplo aplicado

Output do mentee:

> "Ich glaube, dass die Politik schlecht ist."

##### Schritt 1 — Grammatik

```
✓ Sintaticamente correto.
   Subjunktor 'dass' + Verbletztstellung → OK.
   Kasus + Subj-V agreement → OK.
   Tempora konsistent → OK.
```

##### Schritt 2 — Lexikalische Präzision

```
✗ "schlecht" é vago.
   Em discurso político: alternativas mais precisas:
   - 'verfehlt' (errada de propósito)
   - 'destruktiv' (destrói algo)
   - 'orientierungslos' (sem norte)
   - 'zynisch' (cínica)
   - 'kurzsichtig' (de curto prazo)
   
   Default mais idiomático para crítica neutra: 'verfehlt'.
   
   Consulta DWDS-Wortprofil para 'Politik' confirma kollokação.
```

##### Schritt 3 — Stil

```
✗ "Ich glaube, dass" é Umgangssprache.
   Em Aufsatz acadêmico:
   - "Es ist anzunehmen, dass..."
   - "Vieles spricht dafür, dass..."
   - "Man kann argumentieren, dass..."
   
   Mais nominal: 
   "Die gegenwärtige Politik erscheint verfehlt."
```

##### Schritt 4 — Native erudite

```
"Die gegenwärtige Politik scheint mir, bei aller gebotenen Vorsicht, 
in ihren Grundzügen verfehlt."

   ↑ "bei aller gebotenen Vorsicht": hedge erudito-cauteloso típico do
     Wissenschaftsdeutsch (Habermas, Luhmann).
   ↑ "in ihren Grundzügen": precisifica escopo da crítica.
```

#### Classificação de erros

```
BLOCKING:  agramatical / falha de comunicação.
   Exemplo: "*Ich helfe dich" (Akk em vez de Dat).

MAJOR:     sinaliza não-nativo.
   Exemplo: "Ich glaube, dass die Politik schlecht ist" (registro errado para Aufsatz).

NIT:       deslize estilístico, tolerável.
   Exemplo: ordem do Mittelfeld sub-ótima mas gramatical.
```

#### 5 Begründungsfragen obrigatórias após correções de BLOCKING

```
1. Por que escolheu palavra X em vez de Y aqui?
2. Por que Konjunktiv I em vez de Indikativ aqui?
3. Por que Genitiv aqui em vez de von+Dat.?
4. Por que estrutura ativa em vez de Passiv aqui?
5. Por que essa Modalpartikel aqui?
```

Não conseguir justificar 3+/5 = **falha** (código colado/intuído).

### 2.3 3 Tore aplicados a mentee (cf. MENTOR.md §3)

#### 1. Konzeptuelles Tor

**Quando**: mentee declarou que terminou de ler a Harte Theorie do módulo.

**Procedimento**:
1. **5-8 perguntas conceituais** em ordem aleatória.
2. Pelo menos 1 exigindo **árvore sintática ASCII / topológica**.
3. Pelo menos 1 exigindo **Gegenbeispiel**.
4. Pelo menos 1 forçando **explicação interna do mecanismo**.
5. Sem dica durante o portão.

**Avaliação**:
- Correta + precisa → passa.
- Correta + vaga → rejeitar, pedir reformulação técnica.
- Errada → sinalizar, indicar subseção a revisitar.
- "Não sei" → falha.

#### 2. Praktisches Tor

**Quando**: mentee declarou ter terminado a Sprachliche Aufgabe.

**Procedimento**:
1. Pedir output (texto 500-1500 W ou áudio transcrito 5-10 min).
2. Aplicar **Loop de Refinamento completo** (§2.2).
3. Listar issues classificados (BLOCKING > MAJOR > NIT).
4. **5 Begründungsfragen** após correções.

**Critério de pass**: Camada 1 sem BLOCKING; ≤ 5 MAJOR em texto curto. Conforme Stage do mentee (cf. RUBRIC.md §2).

#### 3. Verbindungstor

**Quando**: Tore 1 e 2 passaram.

**Procedimento**:
1. Selecionar **2-3 módulos anteriores** com relação real ao atual.
2. Pergunta integradora para cada.
3. Avaliar precisão da conexão.

**Falha**: revisitar módulos esquecidos antes de avançar.

### 2.4 Modos de mentoring (cf. MENTOR.md §0)

#### Modo A — Self-Mentor

Mentee é seu próprio Examinator. Aplicar postura mentor a si mesmo.

**Risco**: auto-engano. Audit retrospectivo a cada 90 dias.

#### Modo B — Peer-Mentor

Buddy ou pequeno grupo (2-5 pessoas) examinam-se mutuamente. Cohort com cadência semanal mínima.

**Calibração**: mentor humano Senior+ ocasional (mensal/trimestral) calibra rigor do grupo.

#### Modo C — Suplemento opcional

Ferramentas de produtividade (busca de Beleg em corpora, sugestão de Frasal Cards). **Nunca** para gerar resposta, avaliar Tor, ou resolver Aufgabe.

#### Modo D — Hybrid (recomendado)

Mix dos três: self-mentor (Anki, journal, micro-Tore); peer-cohort (semanal, Tore grandes); senior-mentor (mensal/trimestral, calibration profunda); suplemento ocasional (fricções pontuais).

### 2.5 Pedagogia adulta de L2 (DaF/DaZ)

#### Técnicas centrais (cf. STUDY-PROTOCOL.md)

##### Active Recall (Karpicke/Roediger)

> *"Forçar recuperação ativa cria traços de memória mais fortes que reler."*

Aplicação: após ler Harte Theorie, fechar livro + escrever em folha em branco a regra com 1 exemplo próprio.

##### Spaced Repetition (Bjork desirable difficulty)

> *"Revisão em intervalos crescentes maximize retention."*

Aplicação: Anki obrigatório a partir do módulo 01-02; frasal cards (cf. 01-09).

##### Comprehensible Input + 1 (Krashen 1985)

> *"Aquisição se dá em input ligeiramente acima do nível atual."*

Aplicação: texto autêntico calibrado a 10-20% acima do nível.

##### Output Hypothesis (Swain 1985)

> *"Produção força noticing-the-gap."*

Aplicação: 1 Aufsatz/semana a partir do módulo 01-02; 1 Sprachaufnahme/semana a partir de 02-01.

##### Deliberate Practice (Ericsson 2016 *Peak*)

> *"Prática focada em fronteira de habilidade, com feedback imediato."*

Aplicação: Sprachliche Aufgaben sempre na fronteira; nunca em zona de conforto.

##### Spaced Re-Test (decay & refresh)

A cada 90 dias, refazer 3 perguntas aleatórias dos Tore conceituais dos últimos 5 módulos. Falhar 1+ → marcar como `needs_refresh`.

### 2.6 Anti-isolamento gate (cf. MENTOR.md §10.5)

Após 6 meses solo (sem peer, sem mentor humano, sem cohort) → **bloquear avanço temporariamente** até canal externo estabelecido:

- Tandem-Partner nativo (Tandem app, HelloTalk).
- Lesegruppe / book club em DE.
- Universitäts-Sprachkurs Niveau B2-C1.
- OSS-Übersetzungsprojekt.
- Mentor humano Senior+ ocasional (paid ou OSS-met).
- OSS contribution recente com PR review em DE.

**Razão**: solo absoluto detecta menos buracos (prosódicos, pragmáticos, sociolinguísticos). Aceitar o gate = sinal de mentor maduro.

### 2.7 Sustainability checkpoints (cf. MENTOR.md §10.4)

A cada 3 Tore passados, autocheck honesto do mentee:

```
□ Dormindo 7+ horas/dia regularmente?
□ Mantém exercício 3x/semana?
□ Cohort/peer ativo (algum contato técnico nas últimas 2 semanas)?
□ Fehlerprotokoll recebendo entries?
□ Sintoma de queima (irritabilidade, sleep ruim, retirada)?
```

Se 2+ em vermelho: **pause 1-2 semanas**. Volume sem consolidação não vira maestria.

### 2.8 Conjunto de exigências para mentee Stage 5+

Para mentor de Stage 5:

- Mentee passou Stages 1-4 (autodeclarado + audit).
- Anki deck saturado (~7000+ cards).
- Aufsatz Stage 3+ produzido (5000 W).
- Begriffsanalyse Stage 4 produzida (~30 páginas).
- Tagebuch em DE 6+ meses.
- Pelo menos 1 canal externo ativo.

Mentor verifica + aplica RUBRIC.md ao output Stage 5.

### 2.9 Workflow mentoring sustentável

#### Frequência

```
Self-mentor: diariamente (Anki, Tagebuch).
Peer-cohort: semanal (1-2h, discussão + Tore).
Senior-mentor: mensal/trimestral (1-2h, calibration).
```

#### Por sessão

```
1. Status check (5 min): onde mentee está? Que módulo? Que Tor pendente?
2. Loop de Refinamento aplicado (15-30 min): output recente do mentee.
3. Pergunta-condutora (15-30 min): conceitual ou conexão.
4. Próximos passos (5 min): que módulo? Que Aufgabe? Cadência?
5. Documentação: notas em PROGRESS.md (ou equivalente do mentee).
```

#### Sustentabilidade

```
Quanto tempo mentor dedica por mentee:
   Stage 1-2: 1-2h/semana sustentado.
   Stage 3-4: 2-4h/semana (Aufsätze longos exigem leitura crítica).
   Stage 5: 4-8h/mês (Capstone-5 review).

Mentor com 3+ mentees simultâneos: ~5-10h/semana dedicado.
```

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se:

1. Aplica **Loop de Refinamento completo** (4 camadas) a 1 output de mentee.
2. Aplica **3 Tore** a 1 mentee em módulo escolhido.
3. Lista **5 técnicas centrais de pedagogia L2 adulta** (cf. STUDY-PROTOCOL.md).
4. Reconhece **anti-isolamento gate** + 5 canais externos válidos.
5. Aplica **sustainability checkpoint** a 1 mentee.
6. Diferencia **modos A, B, C, D de mentoring** com pros/contras de cada.
7. Constrói **plano de mentoring** para 1 mentee (Stages 1-5, cronograma esperado).
8. Identifica **3 padrões de auto-engano** em self-mentor com correção.

---

## 4. Sprachliche Aufgabe

### Tarefa

**Mentor 3 Lernende DE durante 6 meses** (em modo peer ou senior). Documentar:

1. **Plano inicial**: para cada mentee, identificar Stage atual + módulo prioritário + cadência esperada.
2. **Sessões mensais**: registrar 1 sessão por mês por mentee (6 sessões por mentee × 3 mentees = 18 sessões).
3. **Loop de Refinamento aplicado**: documentar 6 aplicações completas (4 camadas) em outputs de mentees, com BLOCKING/MAJOR/NIT classification + 5 Begründungsfragen.
4. **3 Tore conduzidos**: aplicar pelo menos 3 Tore (1 conceitual + 1 prático + 1 conexão) a cada mentee.
5. **Anti-isolamento gate aplicado**: identificar mentee em risco; intervir com canal externo.
6. **Sustainability checkpoints**: aplicar a cada mentee a cada 3 Tore.
7. **Auto-reflexão**: ao final de 6 meses, escrever 1500 W em DE sobre experiência de mentoring — o que aprendi sobre próprio Stil ao examinar outro? Onde mentoring expandiu meu próprio Verstehen?
8. **Documentação**: cada mentee tem registro PROGRESS.md atualizado.

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **MENTOR.md** (cross-Stage): contrato canônico aplicado.
- **STUDY-PROTOCOL.md** (cross-Stage): técnicas pedagógicas adultas.
- **RUBRIC.md** (cross-Stage): critérios pass/fail dos Tore.
- **Todos módulos Stages 1-4**: prereqs do mentor.
- **05-04 Eigene Stimme**: mentor aplica Stimme própria + reconhece Stimme emergente em mentees.
- **05-07 Goethe C2 / TestDaF**: mentor calibra mentees para certificações externas se aplicável.

---

## 6. Quellen

### Pedagogia DaF/DaZ

1. **Krumm, Hans-Jürgen et al. (Hg.)** — *Deutsch als Fremd- und Zweitsprache: Ein internationales Handbuch*. 2 Bde. De Gruyter, 2010.
2. **Storch, Günther** — *Deutsch als Fremdsprache: Eine Didaktik*. 2. Aufl. Fink, 2008.
3. **Roche, Jörg** — *Fremdsprachenerwerb / Fremdsprachendidaktik*. UTB, 2013.

### Adult learning + L2

- **Ericsson, K. Anders / Pool, Robert** — *Peak: Secrets from the New Science of Expertise* (2016). (Em DE: parcial em manuais.)
- **Karpicke, J. / Roediger, H.** — *Science* 2008. (Active Recall.)
- **Bjork, R. A. / Bjork, E. L.** — *Desirable Difficulties* (papers).
- **Krashen, Stephen** — *The Input Hypothesis* (1985).
- **Swain, Merrill** — *The Output Hypothesis* (1985).

### MENTOR.md + RUBRIC.md (interno)

- **MENTOR.md** (framework/MENTOR.md): contrato canônico do mentor.
- **STUDY-PROTOCOL.md** (framework/STUDY-PROTOCOL.md): técnicas cognitivas obrigatórias.
- **RUBRIC.md** (framework/00-meta/RUBRIC.md): critérios pass/fail.

---

**Próximo módulo:** [05-07 Goethe-Zertifikat C2 / TestDaF (opcional)](05-07-goethe-c2.md), prereq todos os módulos.
