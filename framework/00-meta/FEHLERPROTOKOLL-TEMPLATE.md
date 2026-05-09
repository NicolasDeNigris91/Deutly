# FEHLERPROTOKOLL-TEMPLATE — Registro de erros

> Template operacional para o Fehlerprotokoll mantido pelo aprendiz. Referenciado em STUDY-PROTOCOL.md §9 + MENTOR.md §3.2 + 01-09 §2. Este arquivo documenta o template; o Fehlerprotokoll real do aluno mora em repo separado (`Erkenntnisprojekt/Fehlerprotokoll.md`).

---

## 1. Princípio

> *"Erro repetido é gap não-percebido; erro registrado é gap em vias de fechamento."*

Cada correção do Loop de Refinamento (cf. MENTOR.md §1) → entry no Fehlerprotokoll. Releitura semanal antes de Aufsatz novo. Cards Anki gerados de erros recorrentes.

---

## 2. Schema de entry

### Template canônico

```markdown
## YYYY-MM-DD — [Stage / Modul]

**Original (aluno):**
[texto produzido com erro]

**Camada do Loop de Refinamento:**
[Grammatik / Lexikalische Präzision / Stil / Native erudite]

**Erro:**
[descrição precisa do erro]

**Regra violada:**
[regra gramatical com referência: "Eisenberg §X.Y" ou "Helbig/Buscha §Z"]

**Correção:**
[forma correta]

**Comentário (opcional):**
[contexto, comparação com erro anterior, padrão detectado]

**Card Anki gerado:**
[Frente / Verso] — link para card no deck.

**Tags:**
[stage::X, module::Y, error_type::Z]
```

### Exemplo 1 — Camada Grammatik (Kasus)

```markdown
## 2026-04-15 — Stage 1 / Modul 01-02 Kasussystem

**Original (aluno):**
"Ich helfe den Mann."

**Camada:** Grammatik (Kasusrektion)

**Erro:** Akkusativ ('den Mann') em vez de Dativ ('dem Mann').

**Regra violada:** Helbig/Buscha §3.4.2 — verbo `helfen` rege Dativobjekt.
Pertence à classe verbal Dat.-rektiv (helfen, danken, gehören, gefallen,
antworten, begegnen, raten, vertrauen, gratulieren, fehlen, schaden).

**Correção:** "Ich helfe **dem** Mann."

**Comentário:** Erro recorrente — calque PT/EN ('I help the man'). 
Verbos Dat-rektiv exigem treino específico (Anki classe).

**Card Anki gerado:**
   Frente: "Ich __________ dem Mann mit den Koffern."
   Verso: "helfe" (helfen + Dat — verbo rege Dativ; Hilfsverb haben).

**Tags:** stage::1, module::01-02, error_type::kasusrektion
```

### Exemplo 2 — Camada Lexikalische Präzision

```markdown
## 2026-05-22 — Stage 3 / Modul 03-09 Lexik III

**Original (aluno):**
"Die Aufklärung ist schlecht."

**Camada:** Lexikalische Präzision

**Erro:** "schlecht" é vago + inadequado em Aufsatz acadêmico filosófico.

**Regra violada:** Stilkalibrierung; cf. STUDY-PROTOCOL.md §1 (Active Recall) +
MENTOR.md §1.2 (Lexikalische Präzision como camada do Loop).

**Correção:** Mais preciso para discurso filosófico-crítico:
   - "verfehlt" (errada de propósito)
   - "kurzsichtig" (de curto prazo)
   - "ambivalent" (contraditória interna)
   - "selbstdestruktiv" (Adorno-style: dialektisch falsch)

**Comentário:** Reler Adorno, *Dialektik der Aufklärung*: como crítica de 
Aufklärung opera via vocabulário dialektisch, não via "schlecht/gut".

**Card Anki gerado:**
   Frente: "Die Aufklärung ist nicht ___________ (categórico negativo), 
            sondern dialektisch ambivalent." (Adorno-Tradition)
   Verso: "schlecht" — termo coloquial inadequado em discurso acadêmico.
          Substituições contextualizadas: verfehlt, kurzsichtig, ambivalent.

**Tags:** stage::3, module::03-09, error_type::lexikalische_praezision, 
          domain::philosophie, source::adorno
```

### Exemplo 3 — Camada Stil

```markdown
## 2026-07-10 — Stage 4 / Modul 04-10 Hermeneutik

**Original (aluno):**
"Heidegger sagt halt einfach, dass die Wahrheit Aletheia ist."

**Camada:** Stil

**Erro:** Stilbruch grave — Modalpartikeln 'halt einfach' (Umgangssprache 
coloquial) em texto sobre Heidegger (Aufsatz acadêmico Wissenschaftsdeutsch hoch).

**Regra violada:** 03-02 Register; 03-05 Modalpartikeln-Distribuição:
Modalpartikeln em Aufsatz acadêmico são Stilbruch.

**Correção:** "Heidegger argumentiert, die Wahrheit gehe auf Aletheia 
zurück." (Konj. I + neutro acadêmico)
ou: "Wie Heidegger zeigt, ist die Wahrheit als Aletheia zu verstehen." 
(Konj. II + epistemic hedge)

**Comentário:** Modalpartikeln são bandeira de Umgangssprache. Em Aufsatz 
acadêmico: substituir por Konj. I + Konjunktionaladverbien acadêmicos 
(mithin, gleichwohl, freilich) ou hedge expressions (vermutlich, möglicherweise).

**Card Anki gerado:**
   Frente: "Heidegger argumentiert, die Wahrheit __________ auf Aletheia 
            zurück." (Konj. I em Aufsatz acadêmico)
   Verso: "gehe" (Konj. I 3.Sg. de gehen). Em discurso indireto acadêmico,
          Konj. I é norma; evitar Modalpartikeln coloquiais.

**Tags:** stage::4, module::04-10, error_type::stilbruch, register::academic, 
          source::heidegger
```

### Exemplo 4 — Camada Native erudite ear

```markdown
## 2026-09-03 — Stage 5 / Modul 05-04 Eigene Stimme

**Original (aluno):**
"Ich denke, dass die Politik schlecht ist."

**Camada:** Native erudite ear

**Erro:** Texto gramaticalmente correto + lexicalmente OK + estilisticamente 
neutro, mas **falta Stimme** — nativo culto leria como tradução literal de PT/EN.

**Correção:** Versões com Stimme calibrada conforme tradição:

   Habermas-Stil (rekonstruktiv):
   "Eine kritische Analyse der gegenwärtigen Politik legt nahe, dass die 
   Geltungsansprüche, die sie zu bedienen vorgibt, bei nüchterner Prüfung 
   nicht standhalten."

   Adorno-Stil (aphoristisch-kritisch):
   "Verfehlt ist, schlechthin verfehlt, die Politik, die sich ihrer eigenen 
   Negativität nicht zu stellen vermag."

   Bernhard-Stil (saturado-neurótico):
   "Die Politik ist halt einfach, dachte ich, von Grund auf verfehlt, immer 
   schon verfehlt gewesen, und zwar so verfehlt, dass man kaum noch zu sagen 
   wagt, wie verfehlt sie eigentlich ist."

**Comentário:** Cada Stilstrategie codifica **diferent diagnóstico filosófico-
político**. Adorno-Stil = recusa categorial; Habermas-Stil = rekonstruktive 
Kritik; Bernhard-Stil = neurose obsessiva. Eigene Stimme emerge na escolha 
entre essas tradições.

**Card Anki gerado:** [não gerado — questão de Stilbildung não-mecânica]

**Tags:** stage::5, module::05-04, error_type::stimme_fehlt, stilbildung
```

---

## 3. Workflow operacional

### Imediatamente após correção

1. **Anotar entry** seguindo schema canônico.
2. **Marcar tags** apropriadas.
3. **Gerar card Anki** se aplicável (não-mecânico em Stage 5+).

### Semanalmente (sábado AM)

1. **Releitura completa** dos últimos 7 dias de entries.
2. **Identificar padrões**: erros recorrentes em camadas específicas?
3. **Atualizar Anki**: cards adicionais para erros recorrentes (3+ vezes).

### Mensalmente

1. **Releitura dos últimos 30 dias**.
2. **Audit por camada**: 
   - Camada 1 (Grammatik): % de erros total. Foco em qual?
   - Camada 2 (Lexikalische Präzision): repetições? quais campos?
   - Camada 3 (Stil): Stilbruch padrão?
   - Camada 4 (Native erudite ear): Stilbildung emergente identificável?
3. **Plano corretivo**: revisitar módulos onde erros se concentram.

### Trimestralmente (90-day cycle)

1. **Audit honesto**: Fehlerprotokoll completo.
2. **Identificação de stagnation**: erros nas mesmas categorias após 90+ dias?
3. **Re-test**: aplicar Spaced Re-Test (cf. STUDY-PROTOCOL.md §8) em módulos onde erros persistem.

---

## 4. Categorização de erros (taxonomia)

### Por Camada do Loop de Refinamento

```
Camada 1 — Grammatik:
   ::grammatik::wortstellung   (Feldermodell, V2/VL/V1)
   ::grammatik::kasusrektion   (verbo, prep., adj.)
   ::grammatik::konjugation    (Stammformen, Tempora, Konj.)
   ::grammatik::adjflexion     (schwach/stark/gemischt)
   ::grammatik::genus          (atribuição errada)
   ::grammatik::numerus        (Plural)

Camada 2 — Lexikalische Präzision:
   ::lex::vocabulario_vago     (escolha imprecisa)
   ::lex::kollokation_falsa    (DWDS-Wortprofil violado)
   ::lex::falso_amigo          (PT-DE)
   ::lex::etymologisch_falsch  (uso anacrônico)

Camada 3 — Stil:
   ::stil::stilbruch           (registros incompatíveis)
   ::stil::nominal_versus_verbal (calibração inadequada)
   ::stil::modalpartikel_falsch (em registro errado)
   ::stil::stilfigur_misslungen (Hyperbaton mal-aplicado, etc.)

Camada 4 — Native erudite:
   ::native::stimme_fehlt      (sem voz autoral)
   ::native::tradutorisch      (calque PT/EN visível)
   ::native::pretensiosismo    (over-Stilfiguren)
```

### Por Stage

```
::stage::1, ::stage::2, ::stage::3, ::stage::4, ::stage::5
```

### Por módulo

```
::module::01-01, ::module::01-02, ..., ::module::05-07
```

### Por fonte / autor (quando aplicável)

```
::source::kant, ::source::hegel, ::source::heidegger, ::source::adorno,
::source::habermas, ::source::luhmann, ::source::mann, ::source::bernhard,
::source::sebald, ::source::kafka
```

---

## 5. Métricas

### Indicadores de saúde do Fehlerprotokoll

```
□ Frequência de entries:    >3/semana (saudável); <1/semana (audit insuficiente).
□ Distribuição por camada:   se dominante 1 camada, foco específico necessário.
□ Erros recorrentes:         queda ao longo de 90 dias (saudável); platô (gap).
□ Cards Anki gerados:        ≥30% das entries viram cards (saudável).
□ Releitura semanal feita:   sim (saudável); não (decay).
```

### Sinais de progresso

- **Distribuição de camadas se desloca**: erros migram de Camada 1 (Grammatik) para Camada 3-4 (Stil/Native erudite). Isso é progresso — você está em fronteira mais sofisticada.
- **Erros mesmos não-recorrentes**: se erro X foi cometido em fevereiro mas não em julho, regra internalizada.
- **Diversidade de fontes**: erros agora ocorrem em texto Heidegger / Hegel / Adorno (Stage 4-5), não em texto Brüder Grimm (Stage 1).

### Sinais de stagnation

- **Mesmos erros há 90+ dias**: módulo prereq frágil.
- **Camada 1 dominante após Stage 2**: regredir a 01-01 / 01-02 / 01-04.
- **Falta de cards gerados**: Anki desconectado do Fehlerprotokoll.

---

## 6. Conexão com mentoring

Mentor (cf. 05-06) revisa Fehlerprotokoll do mentee:

1. **Distribuição por camada**: onde está a fronteira? Há regressão?
2. **Cards Anki gerados**: Fehlerprotokoll → Anki conexão funcionando?
3. **Padrões persistentes**: módulos prereq frágeis identificáveis?
4. **Plano corretivo**: ajustar progressão.

Em peer-mentoring: ambos aplicam audits cruzados de Fehlerprotokoll.

---

## 7. Estrutura de arquivo recomendada

```
Erkenntnisprojekt/
└── Fehlerprotokoll/
    ├── 2026-Q1.md            (entries jan-mar 2026)
    ├── 2026-Q2.md
    ├── 2026-Q3.md
    ├── 2026-Q4.md
    ├── audit-90d-2026-Q1.md  (audit trimestral)
    ├── audit-90d-2026-Q2.md
    └── ...
```

Granularidade trimestral facilita audit + re-test.

---

## 8. Princípios não-negociáveis

1. **Anote todo erro corrigido pelo Loop de Refinamento** (mesmo aparentemente trivial).
2. **Cite regra com §**: nunca anote sem fonte canônica.
3. **Releia semanalmente**: sem releitura, Fehlerprotokoll é arquivamento, não aprendizado.
4. **Gere cards Anki** para erros recorrentes (3+ vezes).
5. **Audit honesto**: trimestralmente, sem auto-suavização.
6. **Conecte com mentoring**: peer ou senior revisa periodicamente.

> *"Fehlerprotokoll honesto é onde aquisição adulta de L2 acontece."*
