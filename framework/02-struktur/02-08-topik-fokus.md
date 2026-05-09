---
module: 02-08
title: Topik-Fokus-Struktur — Thema-Rhema, Skrambling
stage: struktur
prereqs: [01-01]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em 'Peter las das Buch gestern' vs 'Das Buch las Peter gestern', qual a diferença pragmática?"
    options:
      - "Equivalentes."
      - "**Topikalização**: 'Peter' no Vorfeld = tópico neutro (Subjekt-default). 'Das Buch' no Vorfeld = tópico contrastivo / focal-rematizado ('o livro [não outro objeto], Peter leu ontem'). A escolha do constituinte do Vorfeld codifica **estrutura informacional** (Topik-Fokus)."
      - "Variação dialetal."
      - "Erro de Wortstellung."
    correct: 1
    explanation: "Vorfeld em DE V2 admite **um e somente um constituinte**, mas qual constituinte é escolhido carrega função discursiva: tematização (frame neutro), topicalização contrastiva, focal de remate. 'Peter las das Buch' = default; 'Das Buch las Peter' = ênfase em 'Buch' (= 'foi o livro que Peter leu'). DE explora esta liberdade muito mais que SVO-fixo (PT/EN)."
  - q: "Em 'Ich habe ihm gestern das Buch nicht gegeben', qual a regra que ordena os constituintes do Mittelfeld?"
    options:
      - "Ordem livre."
      - "**Hierarquia do Mittelfeld**: Pron > NP-def > NP-indef; thematisch (dado) > rhematisch (novo); animado > inanimado; Subj > IO-Dat > DO-Akk (default em NPs plenas); 'nicht' antes do constituinte focado. 'ihm' (Pron., dado) precede 'das Buch' (NP-def, dado). 'nicht' antes de 'gegeben' indica negação de frase com foco no remate."
      - "Variação dialetal."
      - "Apenas Komma decide."
    correct: 1
    explanation: "Mittelfeld obedece a hierarquia complexa entrelaçando vetores morfológicos (Pron > NP) + informacionais (dado > novo) + semânticos (animado > inanimado) + sintáticos (Subj > IO > DO default). Skrambling (reordenação) é função de foco: mover constituinte para posição saliente quebra default e gera contraste. Cf. 01-01 §2.4."
  - q: "Em 'Er hat das Buch GELESEN, nicht WEGGEWORFEN', a entonação enfática indica:"
    options:
      - "Ortografia incomum."
      - "**Foco contrastivo prosódico**: stress nuclear cai no constituinte focado ('GELESEN'), com contraste explícito ('nicht WEGGEWORFEN'). Mesmo Wortstellung, prosódia diferente. Em escrita, marca-se com VERSAIS, *itálico*, ou estrutura `nicht X, sondern Y`."
      - "Erro de pronúncia."
      - "Variação regional."
    correct: 1
    explanation: "Foco em DE marca-se de 3 modos complementares: (1) prosódico (stress nuclear no foco); (2) sintático (Topikalisierung pro Vorfeld); (3) lexical (Modalpartikeln, 'sogar, nur, gerade'). 'Er hat das Buch GELESEN, nicht WEGGEWORFEN' = stress no Vollverb final + contraste explícito. Em escrita literária ou lingüística, marca-se com VERSAIS ou *kursiv*."
  - q: "Em 'Adorno schreibt: \"Falsch ist der Begriff der Identität\"', identifique a função sintática-retórica."
    options:
      - "Erro de Wortstellung."
      - "**Topikalisierung do Prädikativs**: Adj. predikativ ('falsch') no Vorfeld, em vez do Subjekt ('der Begriff'). Função retórica: foregrounding ético-cognitivo do juízo ('falso é... ' — atenção primária ao juízo, não ao objeto). Padrão típico do Wissenschaftsdeutsch hoch (Kant, Hegel, Adorno, Heidegger). Cf. análise de 'Selbstverschuldet ist diese Unmündigkeit' (Kant)."
      - "Variação dialetal."
      - "Apenas para versos."
    correct: 1
    explanation: "Topikalisierung do Prädikativs (Adj. ou NP) é estratégia retórica clássica em prosa filosófica DE. Ordem default: 'Der Begriff der Identität ist falsch'. Topikalizada: 'Falsch ist der Begriff der Identität'. Função: rhema (avaliação) precede thema (objeto avaliado). Anáfora estrutural com tradição (Kant: 'Selbstverschuldet ist diese Unmündigkeit'; Heidegger: 'Vergessen ist das Sein')."
  - q: "Skrambling no Mittelfeld em 'Gestern hat Peter das Buch dem Mann gegeben' (vs. default 'dem Mann das Buch'):"
    options:
      - "Erro."
      - "**Skrambling para Foco**: a inversão (Akk-NP antes de Dat-NP) marca foco em 'dem Mann' (= 'AO HOMEM, não a outra pessoa'). Default: Dat-NP > Akk-NP. Skrambling permitido em DE (oposto a SVO-fixo PT/EN). Resulta em interpretação contrastiva, frequentemente combinada com prosódia enfática."
      - "Variação Plurizentrik."
      - "Apenas em poesia."
    correct: 1
    explanation: "DE permite reordenação de Akk e Dat NPs no Mittelfeld por motivos discursivos (Skrambling). Default 'Subj-Dat-Akk-V'; movimento de Akk antes de Dat marca foco contrastivo no Dat. Idêntica reordenação possível com Adverbiale: 'Gestern hat Peter das Buch dem Mann GEGEBEN' enfatiza ato; 'Gestern hat dem Mann Peter das Buch gegeben' marca contraste sobre Dat. Liberdade combinatória é signum de DE como língua de Wortstellung discursiva."
---

# 02-08, Topik-Fokus-Struktur — Thema-Rhema, Skrambling

## 1. Sprachliches Problem

Stage 1 ensinou o **Feldermodell** descritivo. Stage 2 ativa o **uso pragmático** desse modelo: a escolha do constituinte do Vorfeld, a ordem do Mittelfeld, o Skrambling, a marcação prosódica de foco — todos codificam **estrutura informacional** (Information Structure).

Aprendizes adultos travam em:

- **Sempre colocar Subjekt no Vorfeld** (calque PT/EN SVO), produzindo prosa monotônica sem variação informacional.
- **Não topicalizar para foregrounding retórico**: perder oportunidades de ênfase sobre objeto, adverbial, prädikativ.
- **Não dominar Skrambling**: ordem default invariável no Mittelfeld → falha em codificar contraste.
- **Não reconhecer foco prosódico**: ler texto sem perceber stress nuclear, perdendo nuance.

Sem este módulo:
- Você lê Adorno, Heidegger, Kant e perde a topicalização retórica que os caracteriza.
- Você produz Aufsatz monotônico Subj-V-Obj-Adv, sem variação informacional.
- Você ouve Tagesschau e não percebe foco contrastivo no stress.

---

## 2. Harte Theorie

### 2.1 Topik-Fokus — distinção fundamental

**Topik (Thema)**: o constituinte sobre o qual a frase fala — informação **dada** (presente no contexto, recuperável anaforicamente, presupposta).

**Fokus (Rhema)**: o constituinte que adiciona **informação nova** sobre o tópico — o "remate" da frase.

Default em discurso neutro:

```
[TOPIK / dada] — [FOKUS / nova]
   "Peter"          "las das Buch gestern"
```

Princípio universal: **dada antes nova** em ordem default. Línguas variam em flexibilidade.

### 2.2 Vorfeld — escolha codifica frame discursivo

Em DE V2, o Vorfeld admite **um e somente um constituinte**, mas qual constituinte é escolhido tem **função informacional**:

| Vorfeld ocupado por | Função discursiva | Exemplo |
|---|---|---|
| **Subjekt** | Frame neutro (default) | Peter las das Buch gestern. |
| **Tempora-Adv.** | Frame temporal | Gestern las Peter das Buch. |
| **Lokal-Adv.** | Frame espacial | In der Bibliothek las Peter das Buch. |
| **Akk-Objekt** | Tópico contrastivo | Das Buch las Peter (nicht die Zeitschrift). |
| **Dat-Objekt** | Tópico contrastivo | Dem Mann gab Peter das Buch (nicht der Frau). |
| **Prädikativ-Adj.** | Foco rematizado retoricamente | Müde war Peter (sehr). / Falsch ist der Begriff. |
| **Inf-Satz** | Tematização proposicional | Das Buch zu lesen, war eine Pflicht. |
| **Subordinada inteira** | Frame proposicional | Dass Peter das Buch las, überraschte mich. |

A escolha do Vorfeld é **opção retórica do falante**. DE explora esta liberdade muito mais que SVO-fixo (PT/EN).

### 2.3 Topikalisierung do Prädikativs (estratégia clássica)

Padrão: Adj. ou NP predicativo no Vorfeld, em vez de Subjekt.

```
Default:                 Diese Unmündigkeit ist selbstverschuldet.
Topikalizado:            Selbstverschuldet ist diese Unmündigkeit.
                         (Kant 1784)

Default:                 Der Begriff der Identität ist falsch.
Topikalizado:            Falsch ist der Begriff der Identität.
                         (Adorno-Stil)

Default:                 Das Sein ist vergessen.
Topikalizado:            Vergessen ist das Sein.
                         (Heidegger)
```

Função:
- **Rhema-Thema-Inversão**: a avaliação (rhema) precede o objeto (thema).
- **Foregrounding ético/cognitivo**: o juízo recebe peso estrutural antes da identificação.
- **Anáfora estrutural**: cria padrão recognível ("Adj.predikativ + ist + NP-Subjekt").
- **Tradição Wissenschaftsdeutsch**: Kant → Hegel → Adorno → Heidegger.

Em prosa moderna acadêmica, esta Topikalisierung é gehoben mas viva.

### 2.4 Mittelfeld — Skrambling

**Skrambling** = reordenação dos constituintes do Mittelfeld por motivos discursivos. DE permite Skrambling muito mais que SVO-fixo.

#### Ordem default

```
[Subjekt] [IO-Dat-NP] [Adverbiale] [DO-Akk-NP] [Negation] [Prädikativ / V_inf]
```

Exemplo:

```
Ich habe | dem Mann | gestern | das Buch | nicht | gegeben.
            ↑ default
```

#### Skrambling para foco

Mover Akk antes de Dat marca **foco contrastivo no Dat**:

```
Default:    Ich habe dem Mann das Buch gegeben.    (info neutra)
Skrambled:  Ich habe das Buch dem Mann gegeben.    (Foco em 'dem Mann')
                                  ↑ "AO HOMEM, não outra pessoa"
```

Mover Adverbiale para diferente posição altera frame:

```
Default:    Ich habe das Buch gestern gelesen.
Skrambled:  Ich habe gestern das Buch gelesen.    (frame temporal recolocado)
```

#### Pronominalização e Wackernagel-Position

Pronomes átonos aglomeram-se logo após LK (Wackernagel), em ordem **Pron-Nom > Pron-Akk > Pron-Dat**:

```
Hat | er es ihm | gestern | gegeben?
       Wackernagel-Block
```

Pronome sobe: `Pron-Akk` antes de `NP-Dat`:

```
Ich habe es dem Mann gegeben.    (Pron-Akk 'es' antes de NP-Dat 'dem Mann')
```

### 2.5 Foco prosódico (stress nuclear)

Em DE oral, **stress nuclear** marca foco:

```
Peter hat das BUCH gelesen.            (stress em 'BUCH' — foco no objeto)
PETER hat das Buch gelesen.            (stress em 'PETER' — foco no agente)
Peter hat das Buch GELESEN.            (stress no Vollverb — foco no ato/predicado)
```

Em escrita, marca-se com:
- **VERSAIS** (raro, agressivo).
- ***Itálico*** (acadêmico).
- Estrutura `nicht X, sondern Y` (contraste explícito).
- Reformulação cleft: `Es ist X, der/die/das ...` (cleft DE, embora menos usada que cleft EN).

### 2.6 Marcadores de foco lexicais

#### Fokuspartikeln (klasse fechada)

```
auch       (também, inclusivo)
sogar      (até mesmo, escalar)
selbst     (até mesmo — sinônimo de sogar, gehoben)
nur, bloß  (apenas, exclusivo)
allein     (só, gehoben)
gerade     (justamente, precisão)
ebenso     (igualmente)
sonst      (caso contrário)
```

Posição: **imediatamente antes do constituinte focado**.

```
Auch PETER hat das Buch gelesen.       (até mesmo Peter)
Nur PETER hat das Buch gelesen.        (só Peter)
Sogar PETER hat es gelesen.            (escalar: até mesmo Peter, surpresa)
Gerade PETER hat es gelesen.           (precisão: foi exatamente Peter)
```

### 2.7 Fragmentos e elipse contextual

Em diálogo / texto encadeado, foco frequentemente sobrevive em fragmentos elípticos:

```
A: Wer hat das Buch gelesen?
B: Peter.                              (= 'Peter hat das Buch gelesen' — foco em 'Peter')

A: Was hat Peter gelesen?
B: Das Buch.                           (= 'Peter hat das Buch gelesen' — foco em 'Buch')
```

A elipse preserva apenas o constituinte focado. Stage 2-3 desenvolve análise discursiva (cf. 03-04 Pragmatik).

### 2.8 Ausklammerung (cf. 01-01 §2.6) e impacto informacional

Constituintes pesados (Relativsätze, Inf-Sätze, Vergleichssätze longos) extrapõem para o Nachfeld por motivos de processamento + informacionais:

```
Default (pesado):    Peter hat das Buch, das er gestern in der Buchhandlung 
                     am Bahnhof gekauft hat, gelesen.
Ausgeklammert:       Peter hat das Buch gelesen, das er gestern in der 
                     Buchhandlung am Bahnhof gekauft hat.
```

Ausklammerung simultaneamente:
- Reduz carga de processamento.
- Posiciona constituinte pesado depois do remate (rhema), preservando flow informacional.
- Permite leitura linear sem retrocesso.

### 2.9 Diagnóstico — pipeline para Topik-Fokus

Quando lendo:
1. **Identificar Vorfeld**: constituinte topicalizado ou Subjekt default?
2. **Mittelfeld**: ordem default ou Skrambling? Onde está 'nicht'?
3. **Stress prosódico**: identificar foco nuclear (oral) ou marcação textual.
4. **Fokuspartikeln**: 'auch, sogar, nur, gerade' antes do focado.
5. **Ausklammerung**: constituintes pesados no Nachfeld.

Quando escrevendo:
1. **Topikalizar conforme contexto**: não sempre Subjekt no Vorfeld.
2. **Skrambling para contraste**: alterar ordem padrão Mittelfeld para foco.
3. **'nicht' antes do foco**: quando Constituent negation.
4. **Ausklammerung de Relativsätze pesadas**: norma escrita.
5. **Fokuspartikeln**: usar parcimoniosamente, com escopo claro.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Reescreve uma frase neutra (Peter las...) em **5 versões** com Vorfeld diferentes (Subjekt, Akk, Dat, Adverbiale temporal, Adverbiale lokal). Para cada: identifica o frame discursivo.
2. Aplica **Topikalisierung do Prädikativs** em 3 frases gehoben.
3. Identifica em 6 frases dadas se o Mittelfeld está em **default** ou **skrambled**, justificando a função.
4. Posiciona **'nicht'** corretamente em 4 frases (sentential vs. constituent negation).
5. Aplica **Wackernagel-Position** em 3 frases com pronomes átonos.
6. Lista **6 Fokuspartikeln** com 1 exemplo cada.
7. Aplica **Ausklammerung** em 3 frases com Relativsätze pesadas; justifica processualmente.
8. Identifica foco nuclear (oral) em 3 frases dadas, marcando o stress.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Theodor W. Adorno — *Minima Moralia: Reflexionen aus dem beschädigten Leben*** (1951), §§ "Asyl für Obdachlose" e "Tough Baby". Adorno é mestre de Topikalisierung retórica em prosa filosófica.

> "Falsch ist der Begriff der Identität. — Was als 'Erkenntnis' der Welt aufgeboten wird, ist die Wiederholung dessen, was die Welt aus den Menschen gemacht hat. — In der Vereinzelung selber, der das Subjekt sich überlässt, liegt die Macht der Gesellschaft. — Tough zu sein, das fordert die Gesellschaft, indem sie den Einzelnen, der nicht hart wird, zugrunde gehen lässt. — Aber nicht immer war es so. Verbreitet hat sich das Bild des starken Mannes erst mit der Industrialisierung; vor ihr, in feudalen Gesellschaften, galten andere Tugenden. — Mit dem Verschwinden der Tradition aber verschwindet auch der Maßstab dafür, was eigentlich noch Tradition heißt."

(Composto a partir de fragmentos canônicos do estilo Adorno. Para passagens integrais, consultar Suhrkamp, *Minima Moralia*, GS Bd. 4.)

### Tarefa

Análise escrita, **800–1100 palavras** em PT-BR.

1. **Inventário Vorfeld-Constituintes**: identificar **toda Vorfeld-Position** no trecho. Para cada Aussagesatz: qual constituinte ocupa o Vorfeld? Por quê (frame discursivo, topicalização, ênfase)?
2. **Topikalisierung do Prädikativs**: o trecho abre com `Falsch ist der Begriff der Identität` — análise da função retórica. Compare com Kant `Selbstverschuldet ist diese Unmündigkeit` e Heidegger `Vergessen ist das Sein`.
3. **Skrambling no Mittelfeld**: identifique em pelo menos 3 frases onde Adorno se desvia da ordem default. Diagnostique a função de cada Skrambling.
4. **Topikalização de subordinadas**: `In der Vereinzelung selber, der das Subjekt sich überlässt, liegt die Macht der Gesellschaft` — análise de PP-Topikalisierung + Relativsatz aninhada.
5. **Inversão Vorfeld + Konjunktor**: `Verbreitet hat sich das Bild...` — Part.II + Verb finit no Vorfeld? (Atenção: aqui é V2 com Subjekt no MF — análise da cadeia.)
6. **Foco lexical**: identifique Fokuspartikeln e Modalpartikeln no trecho (`erst, eigentlich, noch, nicht immer, aber`).
7. **Stilistische Bemerkung**: Adorno constrói prosa de **Sätze sentenziosos** (curtos, aforísticos), cada um com Topikalisierung retórica. Função filosófico-política da escolha (kritische Theorie como Stilbruch da prosa filosófica?). Compare com Kant (períodos longos), Heidegger (Komposita filosóficos), Habermas (Wissenschaftsdeutsch hoch sistemático).

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-01 Feldermodell** (prereq): este módulo é o **uso pragmático** do modelo descritivo do 01-01.
- **01-02 Kasussystem**: NPs no Mittelfeld carregam Kasus que constrange Skrambling parcialmente.
- **01-05 Pronominalsystem**: Wackernagel-Position é aplicação direta.
- **01-07 Modalpartikeln**: MPs cruzam estrutura Topik-Fokus.
- **02-01 Subordination**: Subordinadas topicalizadas ocupam Vorfeld; Ausklammerung as posiciona em Nachfeld.
- **03-04 Pragmatik**: Topik-Fokus é categoria pragmática prima — esse módulo é prerequisito direto.
- **03-06 Stilfiguren**: Topikalisierung é Stilfigur clássica (Hyperbaton, Anastrophe, ...).
- **03-08 Journalistischer Stil**: Feuilleton-Stil de FAZ/NZZ usa Topikalisierung como marca de qualidade.
- **04-04 Generative Syntax**: Topik-Fokus formalizado como movimento sintático (Spec-CP, Topic-Phrase, Focus-Phrase).
- **04-06 Diskursanalyse**: análise de coerência discursiva depende de Topik-Fokus.
- **04-07 Textlinguistik**: Kohäsion via Topik-Chains.
- **PT comparativo**: PT é SVO mais rígido; Topikalisierung em PT marca-se mais com clivagem ('é o livro que Peter leu') ou prosódia. DE tem mais flexibilidade sintática.

---

## 6. Quellen

1. **Eisenberg, Bd. 2**, capítulos sobre Wortstellung e Mittelfeld.
2. **Helbig/Buscha**, capítulo sobre Stellung der Satzglieder.
3. **Reis, Marga** — *Wortstellung und Informationsstruktur*. Niemeyer, 1993. **Estudo seminal sobre Skrambling em DE.**
4. **Lenerz, Jürgen** — *Zur Abfolge nominaler Satzglieder im Deutschen*. Narr, 1977.
5. **Müller, Stefan** — papers sobre Information Structure em DE.
6. **IDS-Grammis** — buscar "Topik", "Fokus", "Skrambling", "Informationsstruktur".

### Especializada

- **Lambrecht, Knud** — *Information Structure and Sentence Form*. Cambridge UP, 1994. (Tipologia comparativa.)
- **Krifka, Manfred** — papers sobre Foco e Alternativas semânticas.
- **Frey, Werner** — papers sobre Vorfeld e Topikalisierung.

### Texto primário

- **Adorno, Theodor W.** — *Minima Moralia*. Suhrkamp, GS Bd. 4.
- **Adorno** — *Negative Dialektik* (1966). Suhrkamp, GS Bd. 6. (Densidade Topikalisierung ainda mais sistemática.)

---

**Próximo módulo:** [02-09 Lexik II — operationaler Wortschatz](02-09-lexik-2.md), prereq 01-09.
