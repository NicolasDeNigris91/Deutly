---
module: 04-04
title: Generative Syntax — X-bar, GB, Minimalismus auf Deutsch
stage: system
prereqs: [01-01, 02-08]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em X-bar Theory, qual a estrutura básica de uma projeção (XP)?"
    options:
      - "Apenas X."
      - "**XP = [Specifier-of-X] + X' = [Specifier] [X⁰ Complement]**. X⁰ é o head; X' é a projeção intermediária com Complement; XP é a projeção máxima com Specifier. Aplicável a NP, VP, PP, AP, CP, IP — toda categoria sintática segue este formato. Princípio: Endozentralidade (cada projeção é projeção de seu head)."
      - "Variação dialetal."
      - "Erro lingüístico."
    correct: 1
    explanation: "X-bar Theory (Chomsky 1970, Jackendoff 1977) postula estrutura uniforme: XP = [Spec [X' [X⁰ Compl]]]. Aplicada universalmente: NP de der Mann; VP de das Buch lesen; PP de mit dem Mann; CP de dass das Buch gelesen wird. Princípio Endocentricidade: cada XP é determinado pelo seu head. Base de toda Generative Syntax pós-1970."
  - q: "Em DE V2, como Generative Syntax explica a obrigação do verbo finito em 2ª posição?"
    options:
      - "Tradição estilística."
      - "**V→C movement**: o verbo finito move-se da posição V⁰ (em VP) para C⁰ (head do CP). Aplicação: o Vorfeld é Spec-CP, ocupado por exatamente UM constituinte; a linke Klammer é C⁰, ocupada pelo verbo finito (em V2) ou por Subjunktor (em VL). DE é língua [+V2] tipologicamente. Análise canônica desde Den Besten (1983)."
      - "Variação dialetal."
      - "Erro morfológico."
    correct: 1
    explanation: "Análise V→C explica V2 + Topikalisierung em uma única operação. Em V2 Hauptsatz: verbo finito sobe de V⁰ a C⁰ (LK no Feldermodell); Spec-CP recebe o constituinte topicalizado (Vorfeld). Em VL Nebensatz: C⁰ é ocupado por Subjunktor; verbo finito permanece em VP-final (RK). Esta análise, devida a Den Besten 1983, é fundadora da generative Syntax DE."
  - q: "Como X-bar Theory mapeia o Topologisches Feldermodell (cf. 01-01)?"
    options:
      - "Sem correspondência."
      - "**Vorfeld = Spec-CP; LK = C⁰; Mittelfeld = IP / VP-Spec; RK = V⁰; Nachfeld = adjunção pós-VP**. Cada campo topológico corresponde a uma posição estrutural na árvore X-bar. Topologisches Feldermodell = descrição empírica; X-bar = estrutura teórica subjacente. Os dois descrevem o mesmo objeto em níveis diferentes."
      - "Variação dialetal."
      - "Apenas teórico."
    correct: 1
    explanation: "Mapeamento canônico: Topologie ↔ X-bar. Vorfeld = Spec-CP (posição-A' onde Topikalisierung ocorre); LK = C⁰ (head do CP, ocupado por verbo em V2 / Subjunktor em VL); Mittelfeld = IP+VP em camadas; RK = V⁰ ou complexo verbal final; Nachfeld = adjunção CP-Right. Esta análise unifica gramática descritiva (Drach, Höhle) e teoria gerativa (Chomsky, Den Besten, Sternefeld). Stage 4 = aprender ambos níveis simultaneamente."
  - q: "Em Government and Binding (GB), qual o conceito de **Theta-Rolle**?"
    options:
      - "Variação morfológica."
      - "**Theta-Rolle (Θ-rolle)**: papel temático atribuído por um verbo a seus argumentos: Agente, Paciente, Tema, Experienciador, Beneficiário, Instrumento, Locativo. Cada verbo tem **Theta-Grid** que projeta sintaticamente seus argumentos. Princípio Theta-Kriterium: cada argumento recebe exatamente uma Theta-Rolle, e cada Theta-Rolle é atribuída a exatamente um argumento."
      - "Erro lingüístico."
      - "Apenas estilística."
    correct: 1
    explanation: "Theta-Theorie é módulo central de GB (Chomsky 1981 *Lectures on Government and Binding*). Verbo `geben` (ditransitivo) tem Theta-Grid: ⟨Agent, Theme, Goal⟩. Em 'Peter gibt Maria das Buch': Peter = Agent; das Buch = Theme; Maria = Goal. Theta-Kriterium garante que cada NP recebe rolle única + cada rolle preenchida única vez. Núcleo da Argumentstruktur."
  - q: "Em Minimalismus (Chomsky 1995+), qual a noção de **Merge**?"
    options:
      - "Variação morfológica."
      - "**Merge = operação sintática primitiva que combina duas unidades em uma estrutura maior** (binária). Substitui múltiplas regras de X-bar por operação universal mínima. Aplicada recursivamente, gera todas as estruturas sintáticas. Princípio: economia (Minimalismus Programm). Distinção Internal Merge (= Move) vs. External Merge (combinação inicial)."
      - "Variação dialetal."
      - "Erro lingüístico."
    correct: 1
    explanation: "Merge (Chomsky 1995, *Minimalist Program*) é operação sintática primitiva. External Merge: combina duas unidades distintas (e.g., V + NP-Compl). Internal Merge: re-merge de unidade já presente (= Movement em GB). Toda estrutura sintática gerada por aplicação recursiva de Merge. Princípio econômico: minimaliza machinery teórica. Aplicação ao DE V2: External Merge gera estrutura básica; Internal Merge realiza V→C em V2."
---

# 04-04, Generative Syntax — X-bar, GB, Minimalismus auf Deutsch

## 1. Sprachliches Problem

Generative Syntax é **a teoria sintática mais influente** desde Chomsky 1957. Aplicada ao DE, explica V2, Topikalisierung, Skrambling, Subordination, Doppelinfinitiv como **operações sintáticas formalizáveis**. 01-01 introduziu o Topologisches Feldermodell descritivo; este módulo dá a **estrutura teórica subjacente**.

Aprendizes adultos travam em:

- **Tratar Topologisches Feldermodell como mero descrição**: ignorar análise teórica subjacente.
- **Não aplicar X-bar a DE**: tentar análise por intuição.
- **Não conectar teoria sintática a linguística histórica**: ignorar como variação dialectal reflete estruturas profundas.

Sem este módulo:
- Leitura de Sternefeld, Grewendorf, Reis, Müller (germanística gerativa) impossível.
- Capstone-4 carece de aparelho teórico para analisar variação sintática.
- Stage 5 (academic output em DE em germanística) inviável.

---

## 2. Harte Theorie

### 2.1 X-bar Theory — estrutura uniforme

#### Princípio fundamental

Toda categoria sintática (X) projeta de modo uniforme:

```
XP (= projeção máxima de X)
├── Spec (= specifier)
└── X' (= projeção intermediária)
    ├── X⁰ (= head)
    └── Compl (= complement)
```

Para cada categoria lexical: NP (head N), VP (head V), PP (head P), AP (head A); + categorias funcionais: CP (head C, complementizer), IP/TP (head I/T, infl/tense), DP (head D, determiner — Abney 1987).

#### Exemplo: NP `der schöne Mann`

```
NP                            (Projeção máxima)
├── Spec: ∅                  (sem specifier explícito)
└── N'                        (Projeção intermediária)
    ├── (Adj-)Adjunction: schöne   (Adj. atributivo é Adjunkt-N', não Compl)
    └── N'
        ├── N⁰: Mann
        └── Compl: ∅          (sem complemento; substantivo intransitivo)
```

Det (`der`) frequentemente analisado como D⁰ na DP (Abney 1987): a NP completa é DP com Det como head.

#### Exemplo: VP `das Buch lesen`

```
VP
├── Spec: ∅                  (Subjekt em VP-internal Spec ou IP-Spec)
└── V'
    ├── Compl-NP: das Buch   (Akk-Objekt; em DE, NP-Akk a V's left, language-spezifisch head-final)
    └── V⁰: lesen
```

Atenção: DE é **head-final** em VP (objeto antes do V), oposto a EN/PT (head-initial: V antes do objeto). Esta é hipótese clássica (Den Besten 1983, Haider 1993) — embora controversa em literatura recente.

### 2.2 V→C movement — análise V2

#### Estrutura subjacente do Hauptsatz V2

```
            CP
           /  \
          /    \
       Spec-CP  C'
         |     /  \
         |    /    \
         |   C⁰    IP/TP
         |    |    /  \
         |    |   /    \
        XP  V_finit Spec  I'
                   |    /  \
                   |   I⁰   VP
                   |   |   ...
                   ↑    ↑
                   |    |
       Topikalização    V_finit MOVE-se de V⁰ → C⁰
       Spec-CP          C⁰ ocupado por verbo finito
```

#### Aplicação: *Peter las das Buch*

```
1. External Merge: VP construída → [VP Subjekt [V' das Buch lesen]]
2. V→I: verbo lesen sobe a I⁰ (recebe Tempus → 'las')
3. Subjekt → Spec-IP: Peter ocupa Spec-IP
4. V→C: verbo finito 'las' sobe a C⁰
5. Topikalisierung: Subjekt 'Peter' move-se a Spec-CP

Resultado: [CP Peter [C' las [IP ... [VP ... ]]]]
            ↑       ↑
            Vorfeld  LK
```

#### Variação por Topikalisierung

Em vez do Subjekt, qualquer outro constituinte pode ocupar Spec-CP:

```
[CP Das Buch [C' las [IP Peter ... ]]]            (Akk topicalized)
[CP Gestern [C' las [IP Peter das Buch... ]]]      (Adv topicalized)
[CP Falsch [C' ist [IP der Begriff... ]]]          (Adj.predikativ topicalized — Adorno)
```

### 2.3 V-letzt em Nebensatz com Subjunktor

#### Estrutura

```
[CP weil [C' [IP Peter [I' das Buch [V' las]]]]]
       ↑    ↑                                  ↑
    C⁰      Spec-CP vazio                   V⁰ permanece em VP
```

`weil` (Subjunktor) é base-gerado em C⁰. **Não há V→C** em VL (porque C⁰ já está ocupado). Verbo finito permanece em V⁰ ou I⁰, no fim da frase (head-final VP/IP).

Spec-CP em VL: vazio em geral (Subjunktor introduz a Nebensatz; nada vem antes dele).

### 2.4 Mapeamento Topologisches Feldermodell ↔ X-bar

| Feld topológico | Posição X-bar |
|---|---|
| **Vorfeld** | Spec-CP |
| **Linke Klammer (LK)** | C⁰ |
| **Mittelfeld** | IP + VP (com Skrambling-positions) |
| **Rechte Klammer (RK)** | V⁰ + Auxiliares |
| **Nachfeld** | adjunction pós-CP / pós-VP |

Topologisches Feldermodell = descrição empírica acessível.
X-bar = estrutura teórica subjacente, ferramenta analítica.

### 2.5 Government and Binding (GB) — módulos centrais

#### Theta-Theorie

Cada verbo lexicalmente especifica **Theta-Grid** (papéis temáticos):

```
geben (Klasse III ditransitiva): ⟨Agent, Theme, Goal⟩
   Subj-Nom = Agent
   Akk-Obj = Theme  
   Dat-Obj = Goal

helfen (Dativ-Verb): ⟨Agent, Beneficiary⟩
   Subj-Nom = Agent
   Dat-Obj = Beneficiary

bedürfen (Genitiv-Verb gehoben): ⟨Experiencer, Stimulus⟩
   Subj-Nom = Experiencer
   Gen-Obj = Stimulus
```

Theta-Kriterium: bijeção entre argumentos sintáticos e Theta-Rollen. Argumentos a mais (sem Theta-Rolle) ou menos = agramatical.

#### Casetheorie

Cada NP precisa receber **Kasus abstrato**. Posições atribuintes:
- I⁰ (Tempus): atribui Nom. a Spec-IP.
- V⁰: atribui Akk. a NP-Compl.
- V⁰ + Dat-Verben: atribui Dat. a NP-Dat.
- P⁰: atribui Akk./Dat. a NP em PP.

Em DE, o sistema casuístico é morfologicamente saturado (cf. 01-02), facilitando análise.

#### Binding-Theorie

Distribuição de pronomes anafóricos:
- **Reflexivo** (`sich`): deve ser ligado **localmente** (dentro da mesma frase finita).
- **Pronome pessoal** (`er, sie, es`): deve ser **livre** localmente.
- **NP completa**: deve ser livre globalmente.

```
Peter sah sich.                       (sich = Reflexiv, liga-se a Peter local: ✓)
Peter sah ihn.                         (ihn = Pron., não pode ligar a Peter: refere outro)
*Peter sah Peter.                       (NP-NP coreference local: agramatical)
```

### 2.6 Minimalismus (Chomsky 1995+)

#### Merge — operação primitiva

```
External Merge:    α + β → [α β]
Internal Merge:    [... α ...] → [α [... t_α ...]]   (= Movement como re-Merge)
```

Toda sintaxe = aplicação recursiva de Merge. Princípio: **economia**.

#### Probe-Goal-Agree

Movement (Internal Merge) motivado por **feature-checking**:
- Feature [+V2] em C⁰ = Probe.
- Feature [+verb] em V⁰ = Goal.
- Probe agreed com Goal → Goal move-se a Probe.

Aplicação V→C em DE V2:
- C⁰ tem feature [+V2].
- Verbo finito tem feature compatível.
- Probe-Goal-Agreement → V move a C.

#### Phase-Theorie

Sintaxe construída em **fases** (CP, vP). Cada fase é cyclic Spell-Out (interface com PF/LF).

Implicação: Topikalisierung pode envolver successive cyclic movement através de phase-edges.

### 2.7 Análise gerativa de fenômenos DE específicos

#### Skrambling no Mittelfeld (cf. 02-08)

Análise: **A'-movement** (movement to non-argumental position) ou **base-generation** (geração múltipla de ordens). Literatura controversa — Müller (1995), Haider (2010).

#### Doppelinfinitiv-Konstruktion (cf. 02-05)

Análise: **head-Movement** com **anti-symmetric ordering** (Kayne 1994). Aux finit move-se acima da pilha de Inf., gerando ordem `hat lesen können` em vez de `lesen können hat`.

#### Topikalisierung do Prädikativs (cf. 02-08, Adorno-Hyperbaton)

Análise: **Spec-CP movement of AP/PP** com structural focus interpretation. Construção marcada que requer specific feature-licensing.

### 2.8 Diagnóstico — análise gerativa de frase

Pipeline para análise X-bar de qualquer Aussagesatz:

1. **Identificar tipo de frase**: V2 / V1 / VL.
2. **Determinar estrutura subjacente**: SVO em VP-base, V-final em IP/VP em DE.
3. **Aplicar movements**:
   - V2: V→I→C; XP → Spec-CP (Topikalisierung).
   - V1: V→I→C; Spec-CP vazio.
   - VL: Subjunktor base-generated em C⁰; verbo finito permanece em VP-final.
4. **Atribuir Theta-Rollen**: cada NP recebe rolle do verbo.
5. **Verificar Kasus**: cada NP recebe Kasus de head atribuinte.
6. **Mapear ao Topologisches Feldermodell**.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Reproduz **estrutura X-bar básica** (XP = Spec + X' + X⁰ + Compl).
2. Aplica X-bar a **NP, VP, PP, CP** em DE.
3. Explica **V→C movement** em V2 com 2 exemplos.
4. Aplica **mapeamento Topologie ↔ X-bar** (Vorfeld = Spec-CP, etc.).
5. Aplica **Theta-Theorie** a 4 verbos com Theta-Grids distintas.
6. Aplica **Binding-Theorie** com 3 exemplos (Reflexiv, Pron., NP).
7. Diferencia **External Merge vs. Internal Merge**.
8. Analisa **Topikalisierung do Prädikativs** (Adorno-Stil) em estrutura X-bar.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Wolfgang Sternefeld — *Syntax: Eine morphologisch motivierte generative Beschreibung des Deutschen*** (2008), capítulo 3 fragmento.

> "Die zentrale Eigenschaft der deutschen Verbstellung lässt sich am besten unter Annahme einer einheitlichen Tiefenstruktur erfassen, in der das finite Verb am rechten Rand der VP basis-generiert ist. Verschiedene Bewegungsoperationen — V→I, V→C, Topikalisierung — erzeugen die beobachteten Oberflächenformen. So lässt sich die Asymmetrie zwischen V2-Hauptsätzen und V-letzt-Nebensätzen kompakt erklären: Beide gehen auf dieselbe Tiefenstruktur zurück; sie unterscheiden sich nur in der Anwendbarkeit der V→C-Bewegung. Wenn Spec-CP durch einen Subjunktor besetzt ist, kann V→C nicht stattfinden, und das finite Verb verbleibt in seiner basisgenerierten Position. Wenn Spec-CP frei ist, gilt das Gegenteil."

(Composto a partir de fragmentos canônicos do estilo Sternefeld. Para o trecho integral, consultar Stauffenburg, *Syntax*.)

### Tarefa

Análise escrita, **800-1100 palavras** em PT-BR.

1. **Reconstrução da árvore X-bar** para a frase *"Peter las das Buch gestern"*: árvore completa com Movements indicados.
2. **Análise V2**: aplicação de V→I e V→C; ocupação de Spec-CP por Topikalisierung de Subjekt.
3. **Análise V-letzt**: para *"..., dass Peter das Buch gestern las"*, árvore com Subjunktor em C⁰ + verbo finito em V⁰/I⁰ (head-final).
4. **Topologie ↔ X-bar mapeamento**: para cada um dos 5 campos (VF/LK/MF/RK/NF), identificar posição X-bar correspondente.
5. **Theta-Grid de `lesen`**: ⟨Agent, Theme⟩. Aplicação a *"Peter las das Buch"*.
6. **Topikalisierung do Prädikativs**: análise X-bar de *"Falsch ist der Begriff der Identität"* (Adorno).
7. **Doppelinfinitiv-Konstruktion**: análise X-bar de *"..., dass er das Buch hat lesen wollen"* — ordem inversa explicada via head-Movement.
8. **Sintese teórica**: como Generative Syntax oferece análise unificada para fenômenos DE descritos pelo Topologisches Feldermodell? Vantagens + limitações.

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-01 Feldermodell** (prereq): descrição empírica que a análise gerativa formaliza.
- **02-08 Topik-Fokus** (prereq): Topikalisierung como Spec-CP movement.
- **04-09 Kontrastive Linguistik PT-DE**: comparação tipológica DE [+V2] vs. PT [SVO sem V2].
- **04-10 Hermeneutik**: análise gerativa em prosa filosófica complexa.
- **05-02 Wissenschaftssprache**: Habermas, Luhmann analisáveis com aparelho gerativo.

---

## 6. Quellen

### Manuais

1. **Sternefeld, Wolfgang** — *Syntax: Eine morphologisch motivierte generative Beschreibung des Deutschen*. 2 Bde. Stauffenburg, 2008. **Tratado canônico DE.**
2. **Grewendorf, Günther** — *Minimalistische Syntax*. UTB, 2002.
3. **Haider, Hubert** — *The Syntax of German*. Cambridge UP, 2010.
4. **Müller, Stefan** — *Grammatical Theory: From Transformational Grammar to Constraint-Based Approaches*. Language Science Press, 2018.
5. **Wöllstein, Angelika** — *Topologisches Satzmodell* (cf. 01-01).

### Clássicos

- **Chomsky, Noam** — *Aspects of the Theory of Syntax* (1965); *Lectures on Government and Binding* (1981); *The Minimalist Program* (1995).
- **Den Besten, Hans** — "On the Interaction of Root Transformations and Lexical Deletive Rules" (1983). **Análise V→C fundadora para DE.**
- **Reis, Marga** — papers diversos (cf. 01-01).

### Texto primário

- **Sternefeld** — *Syntax* (Stauffenburg).

---

**Próximo módulo:** [04-05 Formale Semantik](04-05-formale-semantik.md), prereq 03-09.
