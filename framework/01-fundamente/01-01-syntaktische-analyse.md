---
module: 01-01
title: Syntaktische Analyse — Topologisches Feldermodell
stage: fundamente
prereqs: []
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: aktiv
quiz:
  - q: "Por que 'Heute ich gehe ins Kino' é agramatical em alemão?"
    options:
      - "Em alemão, advérbios temporais sempre vão depois do sujeito."
      - "O Vorfeld só admite UM constituinte, e 'heute' já o ocupou; o verbo finito (linke Klammer) deve vir imediatamente em 2ª posição."
      - "Sujeito tem que aparecer depois do objeto direto."
      - "É uma regra estilística, não gramatical."
    correct: 1
    explanation: "O alemão é uma língua V2: o verbo finito ocupa a 2ª posição estrutural; o Vorfeld pode ter exatamente UM constituinte. 'Heute ich gehe' tenta dois (heute + ich) antes do verbo, violando V2."
  - q: "Em 'Peter hat gestern in Berlin ein Buch gekauft', qual é a rechte Satzklammer?"
    options:
      - "hat"
      - "gestern"
      - "ein Buch"
      - "gekauft"
    correct: 3
    explanation: "A rechte Klammer é ocupada pelo verbo não-finito (Partizip II ou Infinitiv) em tempos compostos. 'gekauft' fecha a moldura verbal junto com 'hat' (linke Klammer)."
  - q: "Por que '...weil ich gestern Brot gekauft habe' tem o verbo finito no fim?"
    options:
      - "Porque 'weil' é um Subjunktor que licencia Verbletztstellung — a rechte Klammer absorve o verbo finito."
      - "Porque é uma regra estilística."
      - "Porque o passado-composto sempre vai no fim."
      - "Porque a frase é interrogativa."
    correct: 0
    explanation: "Subjunktoren (weil, dass, wenn, obwohl, da, als, ob, ...) introduzem Verbletztsätze: o Subjunktor ocupa a linke Klammer e o verbo finito desce pra rechte Klammer."
  - q: "Em 'Er hat das Buch gelesen, das er gestern gekauft hat', que mecanismo posiciona o Relativsatz após a moldura verbal?"
    options:
      - "Topikalisierung (movimento pro Vorfeld)"
      - "Ausklammerung (extraposição pro Nachfeld)"
      - "Skrambling (reordenação dentro do Mittelfeld)"
      - "Inversão sujeito-verbo"
    correct: 1
    explanation: "Ausklammerung é a extraposição de constituintes pesados (Relativsätze, longos PPs, Vergleichssätze) pra fora da Verbalklammer, ocupando o Nachfeld. Reduz carga de processamento da memória de trabalho."
  - q: "No Mittelfeld de 'Ich habe ihm gestern das Buch nicht gegeben', qual o princípio que ordena 'ihm' antes de 'das Buch'?"
    options:
      - "Pronome (definido, dado) precede SN definida (dada): hierarquia Pronominalfeld > NP-definida > NP-indefinida."
      - "Dativo sempre precede acusativo."
      - "Ordem alfabética."
      - "Não há princípio: a ordem do Mittelfeld é livre."
    correct: 0
    explanation: "Mittelfeld obedece à hierarquia Pronominalfeld > definite NP > indefinite NP, e thematisch (dado) > rhematisch (novo). 'ihm' (Pronomen, dado) precede 'das Buch' (definida, dada). 'Nicht' aparece imediatamente antes do constituinte focado."
---

# 01-01, Syntaktische Analyse — Topologisches Feldermodell

## 1. Sprachliches Problem

Maioria dos manuais ensina alemão como uma língua de "ordem livre" com algumas regras adicionais ("verbo na segunda posição", "verbo no fim em Nebensatz"). Isso é falso — e custa caro:

- Você produz frases que parecem certas mas têm Wortstellung agramatical.
- Você lê Kant ou Hegel e perde a estrutura porque três Genitiv-NPs aninhadas no Mittelfeld viram uma sopa.
- Você não entende por que *"Peter hat das Buch gelesen, das er gestern in der Buchhandlung gekauft hat"* soa nativo, mas *"Peter hat das Buch, das er gestern in der Buchhandlung gekauft hat, gelesen"* soa pesado e arcaico.

A verdade é que o alemão tem uma **arquitetura sintática rígida** descrita pelo **Topologisches Feldermodell** (Drach 1937, refinado por Höhle 1986, Reis 1980/1993, Sternefeld, Wöllstein 2014). Cada Aussagesatz é organizado em 5 campos topológicos. O verbo finito não está "na posição 2" — ele forma a **linke Satzklammer** de uma moldura verbal (**Verbalklammer**) que estrutura toda a frase.

Sem este modelo:
- Você escreve *"Heute ich gehe ins Kino"* porque traduz da intuição PT/EN. A frase é agramatical: o Vorfeld só admite UM constituinte, e *heute* já o ocupou.
- Você não consegue diagnosticar por que sua frase em DE está estranha — você sente que está, mas não sabe nomear o problema.
- Você não consegue ler textos densos com fluência analítica.

Este módulo te dá a **gramática estrutural** do alemão. Sem ela, todos os módulos posteriores (Kasus, Konjunktiv, Stil, Hermeneutik) operam sobre uma base que você não enxerga.

---

## 2. Harte Theorie

### 2.1 Verbalklammer e os 5 campos

Aussagesatz alemão = moldura formada pela **Verbalklammer** + 3 campos topológicos:

```
┌──────────┬───────────────────┬───────────────┬───────────────────┬──────────┐
│ Vorfeld  │ Linke Satzklammer │   Mittelfeld  │ Rechte Satzklammer│ Nachfeld │
│   (VF)   │       (LK)        │     (MF)      │       (RK)        │   (NF)   │
└──────────┴───────────────────┴───────────────┴───────────────────┴──────────┘
```

Estrutura concreta com Verbalklammer expandida:

```
Peter | hat | gestern in Berlin ein Buch | gekauft | , das ihm gefiel.
  VF  |  LK |          MF                |   RK    |        NF
```

Componentes:
- **Vorfeld (VF)**: posição inicial, exatamente UM constituinte (qualquer um — Subjekt, Objekt, advérbio, oração subordinada, prädikativ).
- **Linke Satzklammer (LK)**: verbo finito (em Hauptsatz V2) ou Subjunktor / Relativpronomen (em Nebensatz Verbletzt).
- **Mittelfeld (MF)**: o coração da frase — onde moram complementos e adjuntos não-topicalizados.
- **Rechte Satzklammer (RK)**: verbo não-finito (Infinitiv, Partizip II) em tempos compostos; verbo finito em Verbletztsatz.
- **Nachfeld (NF)**: posição opcional após a moldura — para constituintes pesados extrapostos.

A **Verbalklammer** é o esqueleto mental: você lê uma frase alemã localizando primeiro a LK e a RK, e tudo entre elas é Mittelfeld; tudo antes é Vorfeld; tudo depois é Nachfeld.

### 2.2 Tipos de frase = padrão de Klammer

| Tipo de frase | LK | RK | Exemplo |
|---|---|---|---|
| **Verbzweitsatz (V2)** — Hauptsatz declarativo | finito | não-finito (se houver) | *Peter hat das Buch gelesen.* |
| **Verberstsatz (V1)** — Entscheidungsfrage / Imperativ / Konditional sem `wenn` | finito | não-finito | *Hat Peter das Buch gelesen?* / *Lies das Buch!* / *Hätte ich es gewusst, ...* |
| **Verbletztsatz (VL)** — Nebensatz introduzido por Subjunktor / Relativpronomen | Subjunktor / Rel. | finito (todo o pacote verbal vai pra cá) | *...weil Peter das Buch gelesen hat.* |

A constraint **V2** não significa "verbo é a segunda palavra" — significa "verbo finito é o segundo **constituinte**". Por isso *"Der Mann mit dem roten Hut hat geschlafen"* é V2: o Vorfeld inteiro é UM constituinte (NP complexa), independente de quantas palavras contém.

### 2.3 Vorfeld: topicalização e função discursiva

Qualquer constituinte pode ocupar o Vorfeld — e a escolha tem **função informacional**:

| Vorfeld ocupado por | Efeito | Exemplo |
|---|---|---|
| Subjekt (default) | Frame neutro | *Peter las das Buch.* |
| Tempora-Adv. | Frame temporal | *Gestern las Peter das Buch.* |
| Objekt-Akk. | Tópico contrastivo | *Das Buch las Peter (nicht die Zeitschrift).* |
| Adverbiale Bestimmung | Frame circunstancial | *In der U-Bahn las Peter das Buch.* |
| Subordinada inteira | Frame proposicional | *Dass Peter das Buch las, überraschte mich.* |
| Prädikativ / Adjektiv | Foco rematizado | *Müde war Peter (sehr).* |
| Infinitivsatz | Tematização proposicional | *Das Buch zu lesen, war eine Pflicht.* |

Regra de ouro: **um e somente um constituinte no Vorfeld**. Tentar dois é agramatical. Exceção marginal: o Vorvorfeld para Diskursmarkierer (*"Aber, der Mann hat geschlafen"* — onde *aber* não conta como constituinte interno da frase).

### 2.4 Mittelfeld: hierarquia de ordem

O Mittelfeld parece "livre" mas obedece a princípios de ordem entrelaçados:

```
Princípios em ordem decrescente de força:
1. Pronome > NP plena
2. Definido / dado / thematisch > indefinido / novo / rhematisch
3. Belebtes (animado) > unbelebtes (não-animado)
4. Subjekt > Objekt-IO > Objekt-DO (ordem default; quebrável por foco)
5. Wackernagel: pronomes átonos clitic-like se aglomeram logo após a LK
6. Negation `nicht`: imediatamente antes do constituinte focado, ou no fim do Mittelfeld para negação de frase
```

Exemplos com diferenças sutis:

```
[1] Ich habe dem Mann das Buch gegeben.
    (default: Subj > IO-Dat > DO-Akk, ambos NP definidas)

[2] Ich habe das Buch dem Mann gegeben.
    (foco contrastivo: dem Mann é o foco — "ao homem, não à mulher")

[3] Ich habe es ihm gegeben.
    (pronominal: Akk-Pron > Dat-Pron — INVERTIDO em relação ao default!)

[4] Ich habe es dem Mann gegeben.
    (mix: Pron-Akk > NP-Dat — Pronome sobe pelo princípio 1)

[5] Ich habe ihn nicht gesehen.
    (Pron > Negation; nicht imediatamente antes da RK porque negação de frase)

[6] Ich habe ihn nicht GESTERN gesehen, sondern HEUTE.
    (nicht antes do constituinte focado [GESTERN], que é o ponto contrastivo)
```

A regra [3] é frequentemente apresentada errada em manuais. O correto: na sequência **puramente pronominal**, a ordem é `Nominativ > Akkusativ > Dativ`. Com NPs plenas, a default é `Nominativ > Dativ > Akkusativ`.

### 2.5 Verbalklammer expandida: tempos compostos e modais

A LK e RK ficam mais ricas com Hilfsverben e Modalverben:

```
Peter | hat              | das Buch       | gelesen.
  VF  | LK (hat)         |     MF         | RK (gelesen)

Peter | hat              | das Buch lesen | wollen.
  VF  | LK (hat)         |     MF         | RK (lesen wollen)

Peter | wird             | das Buch       | gelesen haben.
  VF  | LK (wird)        |     MF         | RK (gelesen haben)

Peter | hätte            | das Buch       | gelesen haben können.
  VF  | LK (hätte)       |     MF         | RK (gelesen haben können)
```

Regra: a **rechte Klammer** absorve o verbo não-finito principal + todos os auxiliares dependentes. Em ordem: V_principal − Modal − Auxiliar (lendo da esquerda pra direita dentro da RK), com algumas inversões licenciadas pela Doppelinfinitiv-Konstruktion (§2.7).

### 2.6 Ausklammerung (extraposição pro Nachfeld)

Constituintes "pesados" (Relativsätze longos, Infinitivsätze, comparações com *als/wie*, longos Präpositionalphrasen) tendem a sair do Mittelfeld pro Nachfeld pra reduzir carga de processamento.

```
[Pesado, dentro da Klammer — gramatical mas estranho]
Peter hat das Buch, das er gestern in der Buchhandlung am Bahnhof gekauft hat, gelesen.

[Ausgeklammert — natural]
Peter hat das Buch gelesen, das er gestern in der Buchhandlung am Bahnhof gekauft hat.
            ↑ RK              ↑ Nachfeld
```

Regra de bolso: se um Relativsatz tem mais de ~5–7 palavras, **ausklammern**. Para vergleichende Konstruktionen (*als / wie*), a Ausklammerung é quase obrigatória:

```
Er ist klüger, als ich gedacht hatte.    (vergleichendes als no Nachfeld — natural)
*Er ist klüger als ich gedacht hatte, geworden.    (forçadíssimo)
```

### 2.7 Verbletztsatz: a moldura "fechada"

Em Nebensatz introduzido por Subjunktor (*weil, dass, wenn, obwohl, da, als, ob, sodass, indem, sofern, ...*) ou Relativpronomen:

```
..., weil | Peter gestern das Buch gelesen | hat.
       LK |           MF                   | RK
```

A LK é o Subjunktor (não um verbo). A RK é o **verbo finito** — vai pro fim. Tempo composto: *... gelesen hat* (Partizip + Auxiliar finito, nessa ordem).

#### Doppelinfinitiv-Konstruktion (exceção crítica)

Com `werden` futuro, ou com Modal em Perfekt + Vollverb, surge a **Doppelinfinitiv**-construção, em que a Verbletztstellung é "violada":

```
..., dass Peter das Buch | wird lesen müssen.
                              ↑ Auxiliar finito ANTES da pilha de infinitivos

..., weil Peter das Buch | hat lesen wollen.
                              ↑ idem
```

Aqui o auxiliar finito sobe na pilha verbal, posicionado antes dos infinitivos, não depois. Isso é **Standardregel obrigatória**, não opção. A motivação é morfo-prosódica: o Modal em Doppelinfinitiv-Konstruktion não pode ser Partizip (não existe *gewollt haben lesen* em alemão padrão), então o Vollverb fica no infinitivo e o auxiliar precede.

### 2.8 V1: a moldura "aberta na esquerda"

Verberstsatz: a posição do Vorfeld está **vazia** (ou nem existe; a frase começa direto pela LK).

Tipos:

```
Entscheidungsfrage: 
    Hat | Peter das Buch | gelesen?

Imperativ (2ª pessoa Sg./Pl., 1ª pessoa Pl.):
    Lies | das Buch!
    Lasst | uns gehen!

Konditional sem 'wenn' (Stilstufe gehoben):
    Hätte | ich das gewusst, | (--- mata)
    ich wäre nicht gekommen.    [a apódose vem como V2 sem 'so' obrigatório, embora 'so' seja comum]

Wunschsatz im Konjunktiv II:
    Wäre | ich doch reicher!

Narratives V1 (Stil literário):
    Kommt | da plötzlich ein Mann ums Eck.
```

V1 é marcado: tem função pragmática específica. Em prosa narrativa moderna usa-se sparingly.

### 2.9 Resumo visual: Schema de Felder

```
                                  Verbalklammer
                              ┌─────────────────┐
   Vorfeld    Linke Klammer   Mittelfeld    Rechte Klammer    Nachfeld
   ════════   ═════════════   ══════════    ══════════════    ════════
  
   V2:    [X]   |   V_fin   |  ...........  |  V_nicht-fin  |  [Y]  
   V1:     ∅    |   V_fin   |  ...........  |  V_nicht-fin  |  [Y]  
   VL:     ∅    |   Subj.   |  ...........  |  V_fin (+RK)  |  [Y]  
```

X = qualquer constituinte topicalizado.
Y = constituinte ausgeklammert (Relativsatz, Vergleich, Inf-Satz, longa PP).

Internalizar este schema é o objetivo do módulo.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**, consegue:

1. **Dado um Aussagesatz arbitrário, marcar VF / LK / MF / RK / NF** com 100% de acerto, em V2, V1 e VL.
2. **Explicar por que *"Heute ich gehe ins Kino"* é agramatical** com referência ao princípio V2 e à constraint do Vorfeld.
3. **Diferenciar V1, V2, VL** com um exemplo seu de cada tipo, e explicar a função pragmática de cada um.
4. **Aplicar a hierarquia do Mittelfeld** com exemplos próprios:
   - Pron > NP-def > NP-indef
   - Subj > IO-Dat > DO-Akk (default em NPs plenas)
   - Pron-Nom > Pron-Akk > Pron-Dat (em pronomes)
   - `nicht` imediatamente antes do foco
5. **Identificar Ausklammerung** num texto autêntico e explicar a motivação processual.
6. **Reescrever um Nebensatz quebrando a Verbletztstellung** e diagnosticar onde está o erro.
7. **Desenhar a árvore topológica** de uma frase com Verbalklammer expandida (modal + auxiliar; e.g., *"Er hätte das Buch gelesen haben können"*).
8. **Explicar a Doppelinfinitiv-Konstruktion** com exemplo próprio e justificar a inversão.

Threshold = você produz cada item dos 8 acima em folha em branco, sem consulta, com exemplos próprios (não os do módulo).

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Immanuel Kant — *Beantwortung der Frage: Was ist Aufklärung?*** (Berlinische Monatsschrift, Dezember 1784).

> "Aufklärung ist der Ausgang des Menschen aus seiner selbstverschuldeten Unmündigkeit. Unmündigkeit ist das Unvermögen, sich seines Verstandes ohne Leitung eines anderen zu bedienen. Selbstverschuldet ist diese Unmündigkeit, wenn die Ursache derselben nicht am Mangel des Verstandes, sondern der Entschließung und des Mutes liegt, sich seiner ohne Leitung eines anderen zu bedienen."

### Tarefa

Análise escrita, **600–1000 palavras** em PT-BR com terminologia técnica em alemão original (`Vorfeld`, `Verbalklammer`, `Genitivattribut`, etc.). Sem consultar gramática durante a Aufgabe.

1. **Análise topológica** das 3 frases. Para cada uma, marcar `VF | LK | MF | RK | NF` com fronteiras explícitas.
2. **Genitivattribute**: identificar todos (são vários) e seus núcleos.
3. **Topicalização incomum** na 3ª frase: identificá-la e explicar seu efeito retórico.
4. **Infinitivsätze com `zu`**: decompor os dois ("...zu bedienen" — aparece duas vezes) e marcar o Mittelfeld interno de cada um.
5. **Genitivobjekt arcaico**: explicar por que *"sich seines Verstandes (bedienen)"* usa Genitiv e não Akkusativ. Qual a regência verbal de `sich bedienen`? Como soaria em alemão moderno?
6. **Reescrita**: reescrever a 3ª frase com **ordem default** (sem topicalização adjetival inicial). Comparar o efeito retórico das duas versões.

### Output esperado

Texto único, em PT-BR, com terminologia DE, fluido. Não responda em itens com checkboxes — produza prosa analítica densa.

Após terminar, peça o **Praktisches Tor**. Loop de Refinamento será aplicado às suas escolhas técnicas (terminologia precisa? análise correta? identificação de fenômenos completa?).

---

## 5. Erweiterungen und Verbindungen

- **01-02 Kasussystem**: o Mittelfeld é também o palco onde os Kasus se distribuem; entender a topologia é prerequisito pra entender a função sintática dos Kasus. A Aufgabe acima já força você a tropeçar no Genitivobjekt de *sich bedienen* — material direto do 01-02.
- **01-03 Verbalsystem**: a RK absorve toda a "pilha" verbal (Modal + Auxiliar + Vollverb). Este módulo te ensina a localizá-la; o 01-03 te ensina a flexioná-la.
- **01-07 Negation**: a posição de `nicht` é pura função do Feldermodell — sem este módulo, posição de Negation é folclore.
- **02-01 Subordination**: Subjunktoren licenciam Verbletztstellung; este módulo é prerequisito direto.
- **02-08 Topik-Fokus-Struktur**: o jogo VF/MF/Nachfeld é o aparato sintático do que pragmaticamente é Topik–Fokus. Este módulo é a sintaxe; o 02-08 é a semântica/pragmática que se mapeia sobre ela.
- **04-04 Generative Syntax**: o Feldermodell é descritivo; a generative syntax (X-bar, GB, Minimalismus) o reduz a movimento V→C e Spec-CP. Você precisa do descritivo antes do gerativo.
- **04-10 Hermeneutik klassischer Texte**: ler Kant, Hegel, Heidegger sem o Feldermodell é como ler programa C sem entender pilha. Este módulo é o pré-requisito mais direto da hermenêutica em estágio 4.
- **PT comparativo**: o português é SVO rígido com pouca topicalização morfologicamente marcada; o alemão é V2-rígido com tudo topicalizável. A intuição PT é seu principal inimigo aqui — se você "traduz mentalmente PT→DE", produz Wortstellung errada. O Feldermodell é o antídoto.

---

## 6. Quellen

### Gramáticas canônicas (em ordem de profundidade)

1. **Eisenberg, Peter** — *Grundriss der deutschen Grammatik*. Bd. 2: *Der Satz*. 5. Aufl. Metzler, 2020. **Capítulos sobre Satzklammer e Felder são os primários.**
2. **Helbig, Gerhard / Buscha, Joachim** — *Deutsche Grammatik. Ein Handbuch für den Ausländerunterricht*. Langenscheidt. §§ sobre Wortstellung, especialmente capítulo "Stellung der Satzglieder".
3. **Engel, Ulrich** — *Deutsche Grammatik*. Iudicium, 2009. Abordagem dependencial; complementa a leitura do Eisenberg.
4. **Duden, Bd. 4: Die Grammatik**. 9. Aufl. 2016. Usar pra zonas duvidosas.
5. **Zifonun / Hoffmann / Strecker** — *Grammatik der deutschen Sprache*. De Gruyter, 1997. (IDS-Grammatik; densíssima — para Stage 4+.)

### Sobre Topologisches Feldermodell especificamente

- **Drach, Erich** — *Grundgedanken der deutschen Satzlehre*. Diesterweg, 1937. **O texto fundador do modelo.** Edições posteriores reeditadas (WBG).
- **Höhle, Tilman N.** — *Topologische Felder* (1986, Manuskript Köln). Reeditado em: *Beiträge zur deutschen Grammatik* (De Gruyter, 2019). Refinamento moderno do modelo.
- **Reis, Marga** — "Word order in German" e *Wortstellung und Informationsstruktur* (Niemeyer, 1993). Trata a interface Mittelfeld–Pragmatik.
- **Wöllstein, Angelika** — *Topologisches Satzmodell*. Kurze Einführungen in die germanistische Linguistik 8. Universitätsverlag Winter, 2014. **Introdução acadêmica curta — comece aqui se quiser monografia dedicada.**
- **Sternefeld, Wolfgang** — *Syntax: Eine morphologisch motivierte generative Beschreibung des Deutschen*. 2 Bde. Stauffenburg, 2008. Para a interface descritivo↔generative.

### IDS-Grammis (online, gratuito)

- **https://grammis.ids-mannheim.de/** — busque por "Topologisches Feldermodell", "Satzklammer", "Vorfeld", "Mittelfeld". Cada entrada tem aparato bibliográfico denso.

### Texto primário do módulo

- **Kant, Immanuel** — *Beantwortung der Frage: Was ist Aufklärung?* (1784). *Berlinische Monatsschrift*, Dezember-Heft, S. 481–494.
   - Edição canônica: *Akademieausgabe* Bd. VIII, S. 33–42.
   - Edição acessível: *Werkausgabe in zwölf Bänden*, Hg. Wilhelm Weischedel, Suhrkamp, Bd. XI, S. 53–61.
   - Edição online (Projekt Gutenberg): https://www.projekt-gutenberg.org/kant/aufklaer/aufkl001.html

---

**Próximo módulo:** [01-02 Kasussystem](01-02-kasussystem.md) (assim que os 3 Tore deste passarem).
