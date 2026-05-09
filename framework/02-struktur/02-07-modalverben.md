---
module: 02-07
title: Modalverben — epistemisch vs. deontisch
stage: struktur
prereqs: [01-03]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Diferença semântica entre 'Er muss arbeiten' e 'Er muss krank sein'?"
    options:
      - "Sinônimos."
      - "**Deontisch (obrigação): 'Er muss arbeiten' = ele tem que trabalhar (obrigação externa).** **Epistemisch (inferência): 'Er muss krank sein' = ele deve estar doente (inferência forte do falante).** Mesmo Modalverb (müssen), dois usos semanticamente distintos. Diagnóstico: deontisch geralmente combina com Inf. ativo de evento; epistemisch combina com Inf. de estado/condição inferível."
      - "Erro estilístico."
      - "Variação dialetal."
    correct: 1
    explanation: "Modalverben em DE têm dois usos primários: deontisch (modalidade prática: obrigação, permissão, vontade, capacidade) vs. epistemisch (modalidade inferencial: avaliação da verdade da proposição). 'müssen' deontisch = obrigação forte; 'müssen' epistemisch = inferência forte (~95% certeza). 'können' deontisch = capacidade/permissão; 'können' epistemisch = possibilidade (~50%). 'dürfen' epistemisch = probabilidade (~70-80%). Distinção fundamental para Wissenschaftsdeutsch e jornalismo de qualidade."
  - q: "Em escala epistêmica de Modalverben, ordem de força inferencial (do mais fraco ao mais forte)?"
    options:
      - "können = müssen = sollen."
      - "**können (~50%, possibilidade) < mögen (~50-60%) < dürfen (Konj. II 'dürfte', ~70-80%, probabilidade) < werden (~80-90%, alta probabilidade) < müssen (~95%+, certeza inferencial). 'sollen' epistemisch tem função distinta: 'rumor / dizem que' (sem componente inferencial direta).**"
      - "Apenas müssen é epistemisch."
      - "Não há escala."
    correct: 1
    explanation: "Escala epistêmica: können (possível, ~50%) → mag/möge (talvez, ~50-60%) → dürfte (provavelmente, ~70-80%) → wird wohl (inferência alta, ~80-90%) → muss (certeza inferencial, ~95%+). 'sollen' epistemisch = 'soll krank sein' = 'dizem que está doente' (Reportativ-modal, distinto da escala probabilística). Internalize a escala — afecta Aufsatz-Hedge e leitura jornalística."
  - q: "Em 'Er soll krank gewesen sein', identifique a estrutura."
    options:
      - "Indikativ Plusqp."
      - "**Modalverb 'sollen' epistemisch (Reportativ) + Perfekt-Inf.** Bildung: sollen-finit + Part.II + Inf. de haben/sein. Significado: 'Dizem que ele esteve doente' / 'Diz-se que ele esteve doente'. Forma temporal-anterior do Modal epistemisch."
      - "Konjunktiv I."
      - "Imperativ."
    correct: 1
    explanation: "Modalverben em uso epistemisch admitem **Perfekt-Inf.** (também Plusquamperfekt-Inf. raramente) para codificar inferência sobre evento passado. Bildung: Modal-finit + Part.II + Inf. de haben/sein. 'Er muss krank gewesen sein' = 'ele deve ter estado doente' (inferência forte sobre o passado). 'Er kann krank gewesen sein' = 'ele pode ter estado doente' (possibilidade passada). 'Er soll krank gewesen sein' = 'dizem que ele esteve doente'."
  - q: "Em 'Er möchte ein Buch lesen' vs 'Er mag Bücher', qual a relação morfo-semântica?"
    options:
      - "Coincidência."
      - "**'möchte' = Konj. II de 'mögen'** com função de **vontade atenuada/cortês** (= 'gostaria de'). 'mag' = Indikativ de 'mögen' como **Vollverb com sentido 'gostar de'**. Em fala moderna, 'möchte' especializou-se como Modal de vontade polite; 'mag' como Vollverb. Distintos morfológica e semanticamente."
      - "Erro morfológico."
      - "São dois verbos distintos."
    correct: 1
    explanation: "'mögen' tem dois usos canônicos: (1) **Vollverb** = gostar de ('Ich mag Bücher' = gosto de livros); (2) **Modalverb epistemisch** = talvez ('Es mag regnen' = talvez chova). 'möchte' (Konj. II) especializou-se como Modal deontisch atenuado: 'Ich möchte ein Buch' = gostaria de um livro. Em fala moderna, 'möchte' é a forma polite default em pedidos. Distinção crucial: 'Er mag krank sein' (epistemisch — talvez esteja doente) vs. 'Er möchte krank sein' (raro, hipotético — gostaria de estar doente)."
  - q: "Em uso deontisch, 'Du sollst nicht töten' (10 mandamentos) vs. 'Er soll nach Berlin fahren' (segundo o que ouvi):"
    options:
      - "Significados idênticos."
      - "**'sollen' deontisch normativo**: 'Du sollst nicht töten' = obrigação moral/normativa forte. **'sollen' epistemisch Reportativ**: 'Er soll nach Berlin fahren' = dizem que ele vai a Berlin (rumor). O mesmo Modalverb tem função deontisch (mandamento) e epistemisch (rumor) distinguíveis pelo contexto. Em Reportativ, 'sollen' substitui Konj. I em fala coloquial."
      - "Variação regional."
      - "Erro morfológico."
    correct: 1
    explanation: "'sollen' tem múltiplos usos: (1) deontisch normativo: 'Du sollst nicht töten' (obrigação moral); (2) deontisch instrucional: 'Du sollst das nicht tun' (alguém te disse para não fazer); (3) epistemisch Reportativ: 'Er soll krank sein' (= dizem que está doente; rumor); (4) gehoben futurisch: 'Es soll regnen' (deve chover, segundo previsão). Contexto diagnostica."
---

# 02-07, Modalverben — epistemisch vs. deontisch

## 1. Sprachliches Problem

Modalverben (`können, müssen, dürfen, wollen, sollen, mögen`) são onde DE codifica **modalidade**: o falante avalia a proposição em relação a obrigação/permissão (deontisch) ou em relação a verdade/probabilidade (epistemisch). O **mesmo Modalverb** pode ter usos deontisch e epistemisch radicalmente distintos.

Aprendizes adultos travam em:

- **Confundir os dois usos**: ler 'Er muss krank sein' como obrigação ('ele tem que estar doente') em vez de inferência ('ele deve estar doente').
- **Não dominar a escala epistêmica**: usar 'können' onde 'dürfte' ou 'wird wohl' seria nuance correta.
- **Não usar Modal + Perfekt-Inf**: produzir 'Er war wahrscheinlich krank' em vez de 'Er muss krank gewesen sein' — perde-se densidade modal.
- **Confundir 'möchte' (vontade polite) com 'mögen' (gostar)**: errar registro em pedido.
- **Não reconhecer 'sollen' Reportativ**: 'Er soll krank sein' lido como obrigação em vez de rumor.

Sem este módulo:
- Você lê notícia onde Modal epistemisch sinaliza graus de certeza editorial — e perde o hedge.
- Você produz Aufsatz acadêmico em Indikativ assertivo onde norma exige Modal+Konj. II epistemisch hedge ("könnte, müsste, dürfte" para hipóteses).
- Você não distingue Bernhard (Modalverben densos como hedge filosófico) de Brecht (Modalverben políticos).

---

## 2. Harte Theorie

### 2.1 Os 6 Modalverben (recapitulação)

| Modalverb | Significado nuclear | Klasse |
|---|---|---|
| **können** | poder, ser capaz | gem. (kann/konnte/gekonnt) |
| **müssen** | dever, ter que | gem. (muss/musste/gemusst) |
| **dürfen** | poder (permissão), ousar | gem. (darf/durfte/gedurft) |
| **wollen** | querer | gem. (will/wollte/gewollt) |
| **sollen** | dever (norma/instrução) | gem. (soll/sollte/gesollt) |
| **mögen** | gostar de, talvez | gem. (mag/mochte/gemocht) |

Konjugação Präs. irregular (cf. 01-03 §2.9): Sg. carece de Endung, Vokalwechsel; Pl. regular.

### 2.2 Uso deontisch (modalidade prática)

#### `müssen` deontisch — obrigação externa forte

```
Er muss arbeiten.                    (tem que trabalhar — obrigação)
Wir müssen uns beeilen.              (temos que nos apressar)
```

#### `sollen` deontisch — obrigação normativa / instrucional

```
Du sollst nicht töten.               (mandamento — norma moral)
Du sollst das aufräumen.             (instrução: alguém disse para)
Sie sollen das Buch lesen.           (instrução polite no Sie-Form)
```

Distinção `müssen` vs. `sollen`:
- **müssen**: obrigação interna (necessidade própria, lógica, circumstância).
- **sollen**: obrigação externa (norma, regra, instrução de outro).

#### `dürfen` deontisch — permissão

```
Du darfst gehen.                     (tem permissão para ir)
Hier darf nicht geraucht werden.     (não é permitido fumar)
Darf ich das Fenster öffnen?         (pedido polite de permissão)
```

#### `können` deontisch — capacidade / permissão

```
Er kann gut Klavier spielen.         (capacidade)
Du kannst das Buch nehmen.           (permissão — informal)
```

Em alguns contextos, `können` competing com `dürfen` em permissão — `können` mais informal, `dürfen` mais formal.

#### `wollen` deontisch — vontade / intenção

```
Ich will nach Hause gehen.           (quero ir pra casa)
Was willst du machen?                (o que você quer fazer?)
```

Distintivo: `wollen` é vontade declarada, frequentemente assertiva. Polite alternativa: `möchten` (Konj. II de mögen).

#### `möchten` (= Konj. II de mögen) — vontade polite

```
Ich möchte ein Glas Wasser, bitte.   (gostaria — polite)
Was möchten Sie trinken?             (o que gostaria de beber?)
```

Em fala moderna, `möchten` especializou-se como Modal de vontade polite. `mögen` como Modal foi reduzido a uso epistemisch (talvez) ou Vollverb (gostar).

### 2.3 Uso epistemisch (modalidade inferencial)

Modal epistemisch codifica **avaliação do falante** sobre a verdade da proposição.

#### Escala de força inferencial

```
↑ Mais forte (certeza)
│
│  müssen (~95%+ certeza inferencial)
│       Er muss krank sein.       (Deve estar doente — inferência forte)
│
│  werden + wohl (~80-90%)
│       Er wird wohl krank sein.  (Estará provavelmente doente)
│
│  dürfte (Konj. II de dürfen, ~70-80% probabilidade)
│       Er dürfte krank sein.      (Provavelmente está doente)
│
│  mögen / mag (~50-60% talvez)
│       Er mag krank sein.         (Talvez esteja doente)
│
│  können (~50% possibilidade)
│       Er kann krank sein.        (Pode estar doente — possibilidade)
│
↓ Mais fraco (mera possibilidade)
```

`sollen` epistemisch tem função **lateral**, não-probabilística:

```
Er soll krank sein.                  (Dizem que ele está doente — Reportativ-Modal)
```

Equivale a "es heißt, dass er krank ist" / "man sagt, dass er krank ist".

#### Modal + Perfekt-Inf — inferência sobre o passado

Bildung: Modal-finit + Part.II + Inf. de haben/sein.

```
Er muss krank gewesen sein.          (Deve ter estado doente — inferência forte passada)
Er kann krank gewesen sein.          (Pode ter estado doente — possibilidade passada)
Er dürfte krank gewesen sein.        (Provavelmente esteve doente)
Er soll krank gewesen sein.          (Dizem que esteve doente)
```

Para Vollverb com **sein**-Aux. de Perfekt:

```
Er muss schon angekommen sein.       (Deve já ter chegado)
Er kann schon angekommen sein.       (Pode já ter chegado)
```

### 2.4 Diagnóstico — deontisch ou epistemisch?

Sinais úteis:

| Sinal | Deontisch | Epistemisch |
|---|---|---|
| Tipo de Inf. | Inf. de evento ativo (arbeiten, gehen, lesen) | Inf. de estado/condição (sein, haben, krank sein) |
| Subjekt | Agente capaz de obedecer/agir | Pode ser inanimado / abstrato |
| Tempo | Frequentemente Präs./Futur (obrigação atual) | Pode ser Perfekt-Inf. (inferência passada) |
| Negation | Pode negar a Modalkonstruktion | Frequentemente nega só o conteúdo |

Mas frequentemente é **contexto pragmático** que decide:

```
Er muss arbeiten.            
   Em contexto de chefe → deontisch ("é obrigado a trabalhar")
   Em contexto inferencial → ambíguo, mas "trabalhar" é evento → tende a deontisch.

Er muss krank sein.          
   "krank sein" é estado → epistemisch ("deve estar doente")
   Improvável deontisch ("é obrigado a estar doente" não faz sentido).
```

### 2.5 Modalverben em Konjunktiv II (Höflichkeit + irrealis)

#### Konj. II Präs.

```
Ich könnte gehen.                    (poderia ir — possibilidade hipotética)
Ich müsste arbeiten.                 (teria que trabalhar — obrigação hipotética)
Du dürftest nicht.                   (não deverias — proibição hipotética)
Er sollte das wissen.                (deveria saber — sugestão / norma)
Er möchte es probieren.              (gostaria de tentar — vontade polite)
```

Funções:
- **Höflichkeit**: 'könnte, dürfte, möchte' atenuam pedidos.
- **Hypothesis**: 'müsste, sollte' formulam hipóteses normativas.
- **Sugestão polite**: 'sollte' = 'deveria' (sugestão sem assertividade).

#### Konj. II Plusqp.

```
Ich hätte gehen können.              (eu teria podido ir — irrealis passado)
Er hätte das wissen müssen.          (ele teria que saber disso — reproche)
Sie hätte nicht kommen sollen.       (ela não deveria ter vindo)
```

Em VL com Doppelinfinitiv (cf. 02-05 §2.6):

```
..., dass ich hätte gehen können.    (Aux.fin. + Inf-Vollverb + Inf-Modal)
```

### 2.6 Modal + Passiv (cf. 02-04 §2.5)

```
Das Buch muss gelesen werden.        (deontisch + Passiv)
Das kann gemacht werden.             (deontisch capacidade + Passiv)
Das könnte schwierig sein.           (epistemisch + Adj. — não-Passiv)
Das müsste schon erledigt sein.      (epistemisch + Zustandspassiv)
```

### 2.7 Wissenschaftsdeutsch — Modalverben como Hedge

Em registro acadêmico, Modalverben em Konj. II são **instrumento de hedge**:

```
Es ließe sich vermuten, dass...                  (Konj. II + Modalkonstruktion — hedge médio)
Man könnte argumentieren, dass...                 (hedge fraco)
Es dürfte sich lohnen, X zu untersuchen.         (hedge médio-forte)
Es müsste also gelten, dass...                    (hedge forte — inferência quase-certa)
Diese These mag plausibel erscheinen, ...         (hedge fraco — Modal mögen)
```

Aprender Stage 2 = aprender a calibrar Modal + Konj. II para precisão epistêmica em escrita.

### 2.8 Diagnóstico — pipeline de Modalverben

1. **Que Modalverb?** (können/müssen/dürfen/wollen/sollen/mögen).
2. **Tempo do Modal?** Präs./Prät./Konj. II/Konj. II Plusqp.
3. **Tipo de Inf. dependente?** Evento (deontisch típico) ou estado (epistemisch típico).
4. **Subjekt animado / agente?** Sim → deontisch provável. Não → epistemisch provável.
5. **Contexto pragmático?** Decide ambigüidades.
6. **Modal + Perfekt-Inf?** Inferência sobre o passado (epistemisch típico).
7. **'sollen' especial?** Pode ser Reportativ ('dizem que').

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Lista os 6 Modalverben com Stammformen + 1 frase deontisch + 1 frase epistemisch (exceto 'wollen').
2. Reproduz a **escala epistêmica** (können → mag → dürfte → werden+wohl → muss) com 1 exemplo cada.
3. Diferencia 'möchte' (Modal vontade polite) de 'mag' (Vollverb gostar de) com 4 exemplos.
4. Constrói 4 frases com **Modal + Perfekt-Inf** (deontisch + epistemisch).
5. Diferencia 'sollen' deontisch normativo de 'sollen' epistemisch Reportativ com 3 pares.
6. Aplica **Modal Konj. II** em 5 frases (Höflichkeit, hipótese, sugestão).
7. Constrói 3 **Modal + Passiv** corretamente.
8. Aplica **Modal como hedge acadêmico** em 4 frases de Aufsatz hipotético.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Thomas Bernhard — *Holzfällen* (Eine Erregung)** (1984), trecho em Modalverben densos. Bernhard é mestre de Modalverben em prosa neurótica-monológica.

> "Ich hätte nicht kommen dürfen, dachte ich, jetzt sitze ich hier in diesem Salon und muss alles ertragen, was diese Leute sagen, obwohl ich genau weiß, dass jedes Wort, das hier gesprochen wird, unwahr sein muss, weil sie nicht anders können, als sich zu verstellen, sie können einfach nicht aufhören damit, dachte ich, sie müssten doch wissen, dass alles durchschaut wird, sie sollen es wissen, glaube ich, aber sie wollen es nicht wahrhaben, und ich, der ich es längst hätte verlassen sollen, sitze hier und höre weiter zu, als müsste auch ich diese Komödie noch eine Weile mitspielen."

(Composto a partir de fragmentos canônicos do estilo Bernhard. Para o trecho integral, consultar Suhrkamp, *Holzfällen. Eine Erregung*.)

### Tarefa

Análise escrita, **800–1100 palavras** em PT-BR.

1. **Inventário Modalverben**: identificar **toda forma de Modalverb** no trecho (mínimo 12). Para cada: Verbo, Tempus (Präs./Prät./Konj. II/Konj. II Plusqp.), uso (deontisch / epistemisch / Höflichkeit / sugestão).
2. **Doppelinfinitiv**: localize as ocorrências (`hätte ... kommen dürfen, hätte ... verlassen sollen`) — Modal Konj. II Plusqp. com Vollverb-Inf. Marque a estrutura morfológica.
3. **Escala epistêmica**: classifique onde Bernhard aplica `müssen` epistemisch (= certeza inferencial) vs. deontisch (= obrigação).
4. **'sollen' nuanced**: o trecho tem `sie sollen es wissen` — qual uso? (deontisch normativo? epistemisch Reportativ? interpretação ambígua?)
5. **'wollen' nuanced**: `sie wollen es nicht wahrhaben` — vontade pura? recusa? hedge?
6. **Modal + Konj. II como hedge**: identifique onde Bernhard usa Konj. II para distância retórica (`als müsste auch ich, sie müssten doch wissen`).
7. **Stilistische Bemerkung**: Bernhard constrói **monólogo neurótico** com Modalverben saturando cada decisão. Compare com Kafka (Modalverben mais reduzidos), Heidegger (Modalverben hedge filosófico), e BGB (Modalverben deontisch jurídico). Função estilística do Modal-Saturation em Bernhard?

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-03 Verbalsystem** (prereq): morfologia básica dos 6 Modalverben.
- **02-03 Konjunktiv II**: Modal Konj. II é central para Höflichkeit + hedge.
- **02-04 Passivkonstruktionen**: Modal + Passiv combinação rotineira.
- **02-05 Infinitivsätze**: Modal rege Inf. ohne zu (todos os 6 Modalverben).
- **03-04 Pragmatik**: deontisch/epistemisch são modalidades pragmáticas que cruzam Sprechakt-Theorie.
- **03-07 Wissenschaftliches Schreiben**: Modal Konj. II como hedge é signum do registro acadêmico.
- **04-05 Formale Semantik**: Modalverben formalizados em lógica modal (operadores □ e ◊).
- **05-01 Politische Sprache**: políticos dosam Modal-Hedge para sinalizar comprometimento ou distância.
- **PT comparativo**: PT colapsa Modal em construções perifrásticas mais variadas (`dever, poder, ter que, ter de, querer`); DE concentra-se em 6 verbos com escala epistêmica fina. Mapeamento PT-DE: 'dever' = müssen (deontisch) ou müssen/dürfte (epistemisch); 'poder' = können (capacidade/permissão) ou können (epistemisch).

---

## 6. Quellen

1. **Eisenberg, Bd. 2**, capítulo sobre Modalverben.
2. **Helbig/Buscha**, capítulo sobre Modalverben — listas + análise.
3. **Duden, Bd. 4**, capítulo sobre Modalverben.
4. **IDS-Grammis** — buscar "Modalverben", "epistemisch", "deontisch".

### Especializada

- **Diewald, Gabriele** — *Die Modalverben im Deutschen: Grammatikalisierung und Polyfunktionalität*. Niemeyer, 1999. **Estudo definitivo.**
- **Öhlschläger, Günther** — *Zur Syntax und Semantik der Modalverben des Deutschen*. Niemeyer, 1989.
- **Reis, Marga** — papers sobre Modalverben e Doppelinfinitiv.

### Texto primário

- **Bernhard, Thomas** — *Holzfällen. Eine Erregung* (1984). Suhrkamp.
- **Bernhard, Thomas** — *Auslöschung. Ein Zerfall* (1986). Suhrkamp. (Modal-saturação ainda mais densa.)

---

**Próximo módulo:** [02-08 Topik-Fokus-Struktur](02-08-topik-fokus.md), prereq 01-01.
