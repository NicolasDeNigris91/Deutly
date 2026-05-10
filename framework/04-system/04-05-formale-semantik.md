---
module: 04-05
title: Formale Semantik — Wahrheitsbedingungen, Quantorenlogik
stage: system
prereqs: [03-09]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em Frege (*Über Sinn und Bedeutung*, 1892), distinção entre 'Sinn' e 'Bedeutung'?"
    options:
      - "Sinônimos."
      - "**Sinn = modo de apresentação** (sentido, conteúdo cognitivo); **Bedeutung = referente** (objeto extensional ao qual a expressão refere). Exemplo canônico: 'Morgenstern' e 'Abendstern' têm Sinn distinto (apresentações diferentes) mas Bedeutung idêntica (planeta Vênus). Distinção fundamental para semântica analítica DE."
      - "Variação dialetal."
      - "Erro filosófico."
    correct: 1
    explanation: "Frege 1892 *Über Sinn und Bedeutung* é texto fundador da semântica analítica. Sinn = sentido / conteúdo cognitivo / Modus do conceber; Bedeutung = referência extensional. Distinção: 'Morgenstern' (= astro da manhã) e 'Abendstern' (= astro da tarde) têm Sinn distinto, mas Bedeutung idêntica (Venus). Aplicação: identidades '(M = A)' são informativas porque Sinn diferem; tautologias '(M = M)' não são. Frege estabelece base da formal Semantik."
  - q: "O que são **Wahrheitsbedingungen** em formal Semantik?"
    options:
      - "Variação morfológica."
      - "**Condições sob as quais uma proposição é verdadeira** (truth conditions). Davidson (1967): 'compreender o significado de uma frase = saber sob que condições ela é verdadeira'. Aplicação: para 'Schnee ist weiß', a Wahrheitsbedingung é 'a entidade designada por Schnee tem propriedade designada por weiß'. Programa de formalização: derivação composicional do significado a partir das partes."
      - "Variação dialetal."
      - "Erro semântico."
    correct: 1
    explanation: "Wahrheitsbedingungen-semantik é programa central da semântica formal pós-1960. Tarski 1944 (semantic conception of truth) → Davidson 1967 (truth-conditional Bedeutungstheorie) → Montague 1973 (intensional logic + λ-calculus). Princípio: significado = condições de verdade; sentenças complexas têm Wahrheitsbedingungen derivadas composicionalmente das partes. Em DE, terminologia consolidada via traduções de Tugendhat, Carnap, Frege."
  - q: "Em Quantorenlogik, distinção entre quantificadores universais (∀) e existenciais (∃)?"
    options:
      - "Sinônimos."
      - "**∀ (alle)** = quantificador universal: '∀x P(x)' = 'para todo x, P(x) é verdadeiro' = 'todos x satisfazem P'. **∃ (es gibt)** = quantificador existencial: '∃x P(x)' = 'existe (pelo menos) um x tal que P(x) é verdadeiro' = 'algum x satisfaz P'. Distinção lógica fundamental; em DE: 'alle Menschen sind sterblich' (∀) vs. 'es gibt einen Menschen, der ...' (∃). Skopusphänomene quando combinados."
      - "Variação dialetal."
      - "Erro lógico."
    correct: 1
    explanation: "Quantorenlogik (Frege 1879 *Begriffsschrift*) formaliza quantificação. ∀x.P(x) = todos; ∃x.P(x) = existencial; ∀ é dual de ∃ (¬∃x¬P(x) = ∀x.P(x)). Em DE: 'jeder, alle, kein-' (∀); 'einige, manche, ein-' (∃). Skopusphänomene: 'Jeder Student liest ein Buch' (∀ > ∃: cada estudante seu livro / ∃ > ∀: um livro lido por todos — ambíguo)."
  - q: "Em DE, 'Niemand kommt' e 'Es kommt niemand' são equivalentes em Wahrheitsbedingungen?"
    options:
      - "Diferentes em sentido."
      - "**Idêntica Wahrheitsbedingung**: ambas → '¬∃x.kommt(x)' (não existe x tal que x vem). Variantes sintáticas (Topikalização do 'niemand' no Vorfeld em (1); estrutura impessoal com 'es' e 'niemand' no MF em (2)). Wahrheitsbedingungen idênticas, Informationsstrukturen distintas (cf. 02-08 Topik-Fokus)."
      - "Variação dialetal."
      - "Erro lógico."
    correct: 1
    explanation: "Wahrheitsbedingungen são invariantes sob Topikalisierung. 'Niemand kommt' e 'Es kommt niemand' têm idêntica Wahrheitsbedingung (¬∃x.kommt(x)) mas estruturas informacionais distintas: (1) niemand topicalizado; (2) es-impessoal com niemand no MF. Distinção semântica vs. pragmática: semântica formal opera sobre Wahrheitsbedingungen; pragmática (cf. 03-04) sobre uso. Programa Montague + Heim/Kratzer Lehrbuch."
  - q: "Por que Carnap e Tugendhat são autores fundamentais para formale Semantik DE?"
    options:
      - "Coincidência."
      - "**Carnap (*Bedeutung und Notwendigkeit* 1947) introduziu intensão/extensão e modal logic em DE; Tugendhat (*Vorlesungen zur Einführung in die sprachanalytische Philosophie* 1976) é manual canônico em DE da semântica analítica.** Ambos consolidam terminologia formal em DE. Sem Carnap+Tugendhat, formale Semantik DE seria apenas tradução de inglês."
      - "Variação regional."
      - "Apenas filosóficos."
    correct: 1
    explanation: "Carnap e Tugendhat são os principais consolidadores da formale Semantik em DE. Carnap (1947 *Meaning and Necessity*; em DE *Bedeutung und Notwendigkeit*) introduz intensão (= função de mundos possíveis a extensão) e extensão (= referente atual). Tugendhat 1976 (*Vorlesungen zur Einführung in die sprachanalytische Philosophie*) é manual em DE. Junto com Frege (séc. XIX) e Wittgenstein, formam tradição analítica DE. Aprender = ler em alemão (não tradução de inglês)."
---

# 04-05, Formale Semantik — Wahrheitsbedingungen, Quantorenlogik

## 1. Sprachliches Problem

Formale Semantik = **a teoria do significado linguístico em forma matemática**. Aplicada ao DE, derive Wahrheitsbedingungen de cada Aussagesatz, formaliza Quantifikation, Skopus, intensionalidade, modalidade. Aprendiz adulto que ignora formal Semantik perde a dimensão científica da significação.

Frege (1892), Carnap (1947), Tarski (1944), Davidson (1967), Montague (1973), Kratzer/Heim (1998) são autores canônicos. Frege e Carnap escreveram em DE — leitura primária acessível.

Aprendizes adultos travam em:

- **Confundir Sinn e Bedeutung** (Frege).
- **Não dominar Quantifikation**: tratar `jeder, alle, einige` como variantes lexicais.
- **Ignorar Skopusphänomene**: não detectar ambigüidades semânticas.
- **Não reconhecer terminologia DE consolidada** (Carnap, Tugendhat).

Sem este módulo, leitura de Frege, Wittgenstein, Tugendhat em DE original sofre, e CAPSTONE-4 carece de aparelho semântico.

---

## 2. Harte Theorie

### 2.1 Frege — Sinn und Bedeutung

#### Distinção fundamental (1892)

```
Sinn (m.)        = sentido / modo de apresentação / conteúdo cognitivo
Bedeutung (f.)   = referente / objeto / extensão
```

#### Exemplo canônico

```
'Morgenstern'    Sinn: "astro brilhante visível ao amanhecer"
                 Bedeutung: planeta Venus

'Abendstern'     Sinn: "astro brilhante visível ao anoitecer"
                 Bedeutung: planeta Venus

→ Sinn(Morgenstern) ≠ Sinn(Abendstern)
→ Bedeutung(Morgenstern) = Bedeutung(Abendstern) = Venus
```

#### Aplicação a identidades

A informatividade de identidades (`a = b`) requer que Sinn(a) ≠ Sinn(b), mesmo se Bedeutung(a) = Bedeutung(b):

```
'Morgenstern = Abendstern'
   = identidade informativa (descoberta astronômica)
   
'Morgenstern = Morgenstern'
   = tautologia trivial
```

#### Sinn de frases inteiras

Para frases inteiras: Sinn = **Gedanke** (pensamento, proposição); Bedeutung = **Wahrheitswert** (verdadeiro / falso).

```
'Schnee ist weiß'    Gedanke: o pensamento de que neve é branca
                     Wahrheitswert: wahr (se neve é branca; falsch caso contrário)
```

### 2.2 Wahrheitsbedingungen-Semantik

#### Princípio Davidson 1967

> *"Compreender o significado de uma frase = saber sob que condições ela é verdadeira."*

Programa: derivar Wahrheitsbedingung composicionalmente das partes.

#### Exemplo: `Schnee ist weiß`

```
||Schnee||      = entidade Schnee no mundo (extensão de tipo e)
||weiß||        = propriedade ser branco (extensão de tipo ⟨e,t⟩, função e → t)
||ist weiß||    = predicado complexo, propriedade ser branco
||Schnee ist weiß||  = Wahrheitsbedingung: 'a entidade Schnee tem a propriedade ser branco'
                  = 1 (verdadeiro) sse Schnee é elemento da extensão de weiß
```

#### Tipos semânticos

```
e         = entidade individual (ex: Peter)
t         = valor de verdade (Wahrheitswert: 1, 0)
⟨e,t⟩    = propriedade (função de e a t; ex: weiß, schlafen)
⟨⟨e,t⟩,t⟩ = quantificador (função de propriedade a valor de verdade; ex: jeder, einige)
⟨e,⟨e,t⟩⟩ = relação binária (verbo transitivo)
```

#### Composição

Tipos compõem-se via aplicação functional:

```
[lesen]: ⟨e, ⟨e,t⟩⟩          (relação)
[das Buch]: e                  (entidade)
[lesen das Buch]: ⟨e,t⟩       (propriedade: 'ler o livro')
[Peter]: e
[Peter liest das Buch]: t      (valor de verdade)
```

### 2.3 Quantorenlogik

#### Quantificadores

```
∀x.P(x)    = 'para todo x, P(x)'              (universal)
∃x.P(x)    = 'existe (pelo menos um) x tal que P(x)'   (existencial)

¬∃x.P(x)   = ∀x.¬P(x)        (não existe = todos não)
¬∀x.P(x)   = ∃x.¬P(x)        (não todos = existe um que não)
```

#### Em DE: lexikalische Realisierung

```
Universais (∀):     alle, jeder, keiner (negativo), niemand (negativo), nichts (negativo)
Existenciais (∃):   einige, manche, ein-, jemand, etwas
```

#### Skopusphänomene (ambigüidades de escopo)

```
"Jeder Student liest ein Buch."
   Lesart 1 (∀ > ∃): cada estudante lê algum livro (livros podem diferir)
                     ∀x.[Student(x) → ∃y.[Buch(y) ∧ liest(x,y)]]
                     
   Lesart 2 (∃ > ∀): existe um livro que cada estudante lê (mesmo livro)
                     ∃y.[Buch(y) ∧ ∀x.[Student(x) → liest(x,y)]]
```

Ambigüidade central da semântica formal. Idêntica em DE e EN.

#### Quantificadores em DE escrita

```
'Alle Menschen sind sterblich'     →  ∀x.[Mensch(x) → sterblich(x)]
'Einige Studenten lesen Bücher'    →  ∃x.[Student(x) ∧ liest(x,Bücher)]
'Niemand kommt'                     →  ¬∃x.kommt(x) = ∀x.¬kommt(x)
'Kein Mensch ist unsterblich'       →  ¬∃x.[Mensch(x) ∧ unsterblich(x)]
```

### 2.4 Intension e Extension (Carnap 1947)

#### Distinção

```
Extension       = referente atual (no mundo atual @)
Intension       = função de mundos possíveis a extensões
                  (Eintrag de cada mundo: extensão diferente)
```

#### Exemplo

```
'Bundeskanzler'    Extension @2025: pessoa específica
                   Intension: função w → indivíduo-Bundeskanzler-em-w

'9'                Extension: número 9 (estável across mundos)
                   Intension: função w → 9 (constante)

'Schnee ist weiß'  Extension @ atual: 1 (verdadeiro)
                   Intension: função w → 1 ou 0 (depende de neve em w)
```

#### Aplicação ao Konjunktiv II irrealis (cf. 02-03)

```
'Wenn ich Zeit hätte, käme ich.'
   Konditional irrealis Präsens
   = avaliação em mundo-possível w' (não atual)
   = Wahrheitsbedingung: 'em todo w' onde-eu-tenho-tempo, eu-venho em w''
```

Modalverben (cf. 02-07) também envolvem quantificação sobre mundos possíveis:
```
'Er muss krank sein.'           epistemisch: ∀w accessible: krank(er, w)
'Er kann krank sein.'           epistemisch: ∃w accessible: krank(er, w)
```

### 2.5 Funktionale Semantik — λ-Kalkül

Aplicação funcional via λ-abstração (Church 1932–41; aplicado a Sprache: Montague 1973).

#### Exemplos

```
||schlafen||      = λx.schläft(x)             (função e → t)
||Peter||         = peter                      (entidade)
||Peter schläft||  = (λx.schläft(x))(peter)
                    = schläft(peter)            (Reduktion β)

||liest||         = λx.λy.liest(y, x)          (relação binária via curry-Format)
||das Buch||      = das_buch
||Peter liest das Buch||
                  = ((λx.λy.liest(y, x))(das_buch))(peter)
                  = (λy.liest(y, das_buch))(peter)
                  = liest(peter, das_buch)
```

### 2.6 Implikatur e Inferência (cf. 03-04)

Distinção:

```
Wahrheitsbedingung    = condição lógica
Implikatur            = inferência pragmática (Grice 1975)
Präsupposition        = condição assumida pelo enunciado
Implikation logisch   = relação válida formalmente
```

Exemplo:

```
"Hans hat aufgehört zu rauchen."
   Wahrheitsbedingung: Hans não fuma agora.
   Präsupposition:     Hans fumava antes.
   Implikatur:          (variável conforme contexto)
```

### 2.7 Diagnóstico — análise semântica formal de frase

Pipeline:

1. **Identificar verbos e sua Theta-Grid + Argumentstruktur**.
2. **Atribuir tipos semânticos** a cada constituinte.
3. **Compor por aplicação functional**.
4. **Derivar Wahrheitsbedingung**.
5. **Identificar Skopus** se há quantificadores.
6. **Distinguir intensão/extensão** se há contextos modais ou temporais.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Aplica **Frege Sinn/Bedeutung** com 4 exemplos próprios.
2. Define **Wahrheitsbedingung** com 3 frases DE exemplificadas.
3. Aplica **Quantorenlogik** ∀ e ∃ a 4 frases DE.
4. Identifica **Skopusphänomene** em 2 frases ambíguas.
5. Distingue **Intension vs. Extension** com 3 exemplos (incluindo Bundeskanzler-Beispiel).
6. Aplica **λ-Kalkül** a 1 frase simples + 1 frase com verbo transitivo.
7. Diferencia **Wahrheitsbedingung / Präsupposition / Implikatur**.
8. Analisa formalmente **Modalverben epistemisch** (∀/∃ sobre mundos accessibles).

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Gottlob Frege — *Über Sinn und Bedeutung*** (1892), excerpt.

> "Der Gedanke, den die Sätze 'Morgenstern' und 'Abendstern' gemein haben, ist offenbar nicht der Sinn dieser Sätze; denn er ist mit dem astronomisch-empirischen Gehalt der Identität 'Morgenstern = Abendstern' verbunden. Die beiden Eigennamen haben verschiedene Sinne, aber dieselbe Bedeutung. Der Sinn umfasst die Art und Weise des Gegebenseins; die Bedeutung ist der Gegenstand selbst. Die Unterscheidung gilt nicht nur für Eigennamen, sondern für jeden sprachlichen Ausdruck, der einen objektiven Inhalt trägt."

(Texto integral em Frege, *Funktion, Begriff, Bedeutung*, Hg. Patzig, Vandenhoeck & Ruprecht.)

### Tarefa

Análise escrita, **800-1000 palavras** em PT-BR.

1. **Distinção Sinn/Bedeutung explicitada**: parafrasear em PT-BR como Frege a estabelece.
2. **Aplicação a 4 pares próprios**: identificar pares onde Sinn ≠ Bedeutung idêntica.
3. **Aplicação à frase**: para uma frase do trecho, identificar Sinn (= Gedanke) e Bedeutung (= Wahrheitswert).
4. **Quantorenanálise**: 'Die Unterscheidung gilt für jeden sprachlichen Ausdruck' — aplicar ∀.
5. **Tipos semânticos**: atribuir tipos a 'Morgenstern' (e), 'haben Bedeutung' (⟨e,t⟩?), e à proposição.
6. **Implikatur na escolha lexical**: por que Frege escolhe 'objektiv' em vez de 'subjektiv'? Implikatur filosófica.
7. **Conexão com Heidegger**: como Frege Sinn/Bedeutung dialoga (ou se opõe a) Heidegger Wahrheit-als-Aletheia? Ambos são alternativas semântico-filosóficas distintas.

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **03-09 Lexik III** (prereq): vocabulário filosófico-semântico.
- **02-07 Modalverben**: análise formal de Modalverben epistemisch como quantificação sobre mundos possíveis.
- **02-03 Konjunktiv II**: análise modal-irrealis em formal Semantik.
- **04-04 Generative Syntax**: estrutura sintática suporta composição semântica.
- **04-08 Korpuslinguistik**: análise empírica de Skopusphänomene.
- **04-10 Hermeneutik**: contraste Frege (sprachanalytisch) vs. Heidegger (hermeneutisch) sobre Bedeutung.

---

## 6. Quellen

### Clássicos primários

1. **Frege, Gottlob** — *Über Sinn und Bedeutung* (1892); *Begriffsschrift* (1879); *Der Gedanke* (1918). Em: *Funktion, Begriff, Bedeutung*, Hg. Patzig, Vandenhoeck & Ruprecht.
2. **Carnap, Rudolf** — *Bedeutung und Notwendigkeit* (1947, em DE). Springer.
3. **Wittgenstein, Ludwig** — *Tractatus logico-philosophicus* (1921). Suhrkamp.

### Manuais

4. **Heim, Irene / Kratzer, Angelika** — *Semantics in Generative Grammar*. Blackwell, 1998. **Manual canônico moderno (em inglês, mas terminologia DE consolidada).**
5. **Tugendhat, Ernst** — *Vorlesungen zur Einführung in die sprachanalytische Philosophie*. Suhrkamp, 1976. **Manual em DE.**
6. **Lohnstein, Horst** — *Formale Semantik und natürliche Sprache*. 2. Aufl. De Gruyter, 2011.

### Texto primário do módulo

- **Frege** — *Über Sinn und Bedeutung*. Em: *Zeitschrift für Philosophie und philosophische Kritik*, NF 100 (1892), 25-50. Online: https://www.deutschestextarchiv.de/.

---

**Próximo módulo:** [04-06 Diskursanalyse](04-06-diskursanalyse.md), prereq 03-08.
