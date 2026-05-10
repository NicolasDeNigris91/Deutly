---
module: 02-05
title: Infinitivsätze — zu+Inf, AcI, kohärent vs. inkohärent
stage: struktur
prereqs: [02-01]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Por que 'Ich verspreche, morgen zu kommen' tem 'zu', mas 'Ich kann morgen kommen' não tem?"
    options:
      - "Erro estilístico."
      - "**Modalverben e wenige andere Verben (sehen, hören, fühlen, lassen, helfen, lernen, lehren, bleiben, gehen)** regem **Infinitiv ohne 'zu'** (reiner Infinitiv). Outros verbos regem **Infinitiv mit 'zu'**: versprechen, hoffen, vergessen, anfangen, aufhören, beginnen, vorhaben, planen, beschließen, ..."
      - "Variação dialetal."
      - "'zu' apenas com verbos longos."
    correct: 1
    explanation: "Distinção morfo-sintática crítica. Verbos com Infinitiv ohne 'zu' (klasse fechada): Modalverben (können, müssen, dürfen, wollen, sollen, mögen), Sinnesverben (sehen, hören, fühlen, spüren, riechen), lassen, machen (= verursachen), lernen, lehren, helfen (também com 'zu' opcional), bleiben + V_lokal (bleiben stehen), gehen (= verbo de movimento), kommen (= idem), heißen, finden (em construção AcI: 'Ich finde es interessant, ...'). Resto: zu + Inf."
  - q: "Diferença entre 'Ich versuche zu schlafen' (kohärent) e 'Es gelingt mir, zu schlafen' (inkohärent)?"
    options:
      - "Apenas estilística."
      - "**Kohärenz**: o Inf-Satz forma um único Verbalkomplex com o verbo finito; sem Komma; Inf na rechte Klammer junto. **Inkohärenz**: Inf-Satz é separado, com Komma obrigatório; Inf-Satz pode ser ausgeklammert no Nachfeld. Kohärenz é típica de Modal + Inf, Sinnesverb + Inf, lassen + Inf; inkohärenz é default para outros verbos."
      - "Variação regional."
      - "Tempos diferentes."
    correct: 1
    explanation: "Distinção fundamental. Kohärente Konstruktion: 'Ich kann schlafen' / 'Ich höre ihn schlafen' / 'Er lässt mich schlafen' — Verbalkomplex único. Inkohärente: 'Ich versuche, zu schlafen' / 'Es gelingt mir, zu schlafen' / 'Ich beschließe, zu schlafen' — separadas por Komma; Inf-Satz é sintática unidade independente que pode mover-se (Vorfeld, Nachfeld) ou ser substituída por dass-Satz. Verbos como 'versuchen' admitem ambas com diferenças de Stilstufe."
  - q: "Em 'Ich höre ihn singen', identifique a estrutura."
    options:
      - "Indikativ Aktiv simples."
      - "**AcI (Accusativus cum Infinitivo)**: verbo de percepção (sehen, hören, fühlen, spüren, riechen) + Akk-Objekt + Infinitiv ohne 'zu'. O Akk ('ihn') é simultaneamente objeto-percepto do verbo principal e sujeito lógico do Infinitiv ('singen'). Construção herdada do latim ('audio eum cantare')."
      - "Discurso indireto."
      - "Konjunktiv."
    correct: 1
    explanation: "AcI: latinizante construção sintática preservada em DE com verbos de percepção e em alguns verbos causativos (lassen, machen). Estrutura: V_perception/causative + NP-Akk + Inf. NP-Akk é controle do Inf. O equivalente PT seria com gerúndio ('ouço-o cantando') ou Inf. ('ouço-o cantar')."
  - q: "Em 'Ich gehe ins Kino, **um meine Freunde zu treffen**', qual a função de 'um ... zu'?"
    options:
      - "Modal."
      - "**Final (finalidade)**: 'um + zu + Inf.' = 'para + Inf.' Restrição: o sujeito do Hauptsatz e do Inf-Satz tem que ser **idêntico**. Se diferente, usar Subjunktor 'damit' + Nebensatz: 'Ich gehe, damit du frei bist'. Outros conectores Inf: 'ohne ... zu' (negativo modal), 'statt/anstatt ... zu' (substitutivo)."
      - "Causal."
      - "Konditional."
    correct: 1
    explanation: "'um ... zu' é construção infinitiva final restrita à identidade de sujeitos. 'Ich gehe ins Kino, um meine Freunde zu treffen' — sujeito de 'gehen' = sujeito de 'treffen' = ich. Diferentes sujeitos: 'Ich gehe ins Kino, damit du frei bist' (damit + NS). 'ohne ... zu' = negação modal: 'Er ging, ohne ein Wort zu sagen'. 'statt/anstatt ... zu' = substituição: 'Statt zu lernen, schaute er fern'."
  - q: "Em '..., dass er das Buch hat lesen können', identifique a estrutura."
    options:
      - "Erro morfológico."
      - "**Doppelinfinitiv-Konstruktion** em VL: Modalverb 'können' em Perfekt + Vollverb 'lesen' em Inf. Em VL, Aux. finit ('hat') sobe **antes** da pilha de infinitivos (Inf+Modal): 'hat lesen können', não 'lesen können hat'. Padrão obrigatório (cf. 01-01 §2.7). Idêntico para 'werden' Futur + Modal: '..., dass er wird lesen müssen'."
      - "Apenas em fala coloquial."
      - "Konjunktiv I."
    correct: 1
    explanation: "Doppelinfinitiv-Konstruktion é exceção sistemática à Verbletztstellung. Em Perf. de Modalverben + Vollverb-Inf., o Aux. finit (hat/hatte/wird) precede a pilha. Motivação morfológica: o Modalverb não pode ser Partizip (não existe '*gewollt haben gelesen' canonical). A pilha resultante: Aux.finit + Inf-Vollverb + Inf-Modal. 'Ich habe das Buch lesen können' (V2) → '..., dass ich das Buch habe lesen können' (VL Doppelinf.)."
---

# 02-05, Infinitivsätze — zu+Inf, AcI, kohärent vs. inkohärent

## 1. Sprachliches Problem

Infinitivsätze são onde **o alemão se torna sintaticamente sutil**: a presença/ausência de `zu`, a distinção kohärent/inkohärent, a estrutura AcI com verbos de percepção, e a Doppelinfinitiv em VL formam um sub-sistema sintático que aprendizes adultos quase sempre simplificam ou erram.

Pontos críticos onde travam:

- **Quando aparece `zu` no Infinitiv**: confundir Modalverb (Inf. ohne zu) com verbo "normal" (Inf. mit zu).
- **Distinção kohärent/inkohärent**: produzir Komma onde não deveria, ou ausência onde norma exige.
- **AcI**: aplicar `zu` em construção de percepção (`*ich höre ihn zu singen`) por contaminação de outras construções.
- **`um ... zu` vs. `damit`**: ignorar a restrição de identidade de sujeitos.
- **Doppelinfinitiv em VL**: produzir ordem `..., dass er das gelesen können hat` em vez de `..., dass er das hat lesen können`.

Sem este módulo:
- Você lê Musil (denso em Inf-Sätze longos com Verbalkomplex aninhado) e perde a estrutura argumental.
- Você produz Aufsatz com Komma errado em construções `versuchen, fragen, beschließen + zu-Inf`.
- Você mistura `um ... zu` e `damit` em frases com sujeitos diferentes.

---

## 2. Harte Theorie

### 2.1 Infinitiv mit oder ohne `zu` — distribuição

#### Verben mit Infinitiv ohne `zu` (klasse fechada)

```
Modalverben:     können, müssen, dürfen, wollen, sollen, mögen
Sinnesverben:    sehen, hören, fühlen, spüren, riechen
Causative:       lassen, machen (= verursachen), heißen (gehoben)
Lehrverben:      lernen, lehren, helfen (também com zu, opcional)
Bewegungsverben: gehen, kommen, fahren (em construção fixa: 'spazieren gehen')
Bleibe-Verben:   bleiben + V_lokal ('bleiben stehen, bleiben sitzen')
Sonstige:        finden (AcI: 'Ich finde es interessant, das zu lesen')
```

Exemplos:

```
Ich kann das Buch lesen.                  (Modal, ohne zu)
Ich höre den Vogel singen.                (Sinnesverb, ohne zu)
Er lässt das Auto reparieren.             (Causative, ohne zu)
Sie geht spazieren.                       (Bewegungsverb, ohne zu)
Wir bleiben sitzen.                       (Bleibe-Verb, ohne zu)
Ich helfe dir aufstehen.                  (Lehrverb, ohne zu — também 'zu' opcional)
```

#### Verben mit Infinitiv mit `zu` (klasse aberta — default)

Todos os outros verbos transitivos/intransitivos que regem Infinitiv:

```
versprechen, hoffen, vergessen, anfangen, aufhören, beginnen,
vorhaben, planen, beschließen, versuchen, sich entschließen,
sich vornehmen, sich freuen (auf), bitten (jdn., etw. zu tun),
gestatten, erlauben, zwingen, fordern, raten, empfehlen, schlagen vor,
... (lista extensa)
```

Exemplos:

```
Ich verspreche, morgen zu kommen.
Sie hat angefangen, Deutsch zu lernen.
Er beschloss, das Land zu verlassen.
Ich freue mich, dich zu sehen.
```

A distinção é lexicalmente especificada por verbo. Memorização Anki + leitura intensiva.

### 2.2 Kohärenz vs. Inkohärenz

#### Kohärenz (Verbalkomplex único)

O Inf-Satz **integra-se** ao Hauptsatz como **único complexo verbal**:

```
Ich kann das Buch lesen.
   V_finit (LK)            V_inf (RK — junto)
   |       Mittelfeld      |
   └─── Verbalkomplex unitário ────┘
```

Característica:
- **Sem Komma**.
- Inf. ocupa a **rechte Klammer** junto com (ou após) outros elementos verbais.
- Inf-Satz não pode ser topicalizado independentemente.

Default em: Modalverb + Inf., Sinnesverb + AcI, lassen + Inf., gehen + Inf.

```
Ich höre ihn singen.                       (kohärent — sem Komma)
Er lässt das Auto reparieren.              (kohärent)
Ich gehe schwimmen.                        (kohärent)
```

#### Inkohärenz (Inf-Satz separado)

O Inf-Satz é **uma unidade sintática separada**, com Komma:

```
Ich versuche, das Buch zu lesen.
                ↑ Komma obrigatório
                Inf-Satz separado, no Nachfeld.
```

Característica:
- **Komma obrigatório** antes do Inf-Satz se este contém complemento.
- Inf-Satz pode ser **substituído por dass-Satz**: *"Ich versuche, dass ich das Buch lese"* (gehoben/raro mas testável).
- Inf-Satz pode ser **topicalizado** no Vorfeld: *"Das Buch zu lesen, versuche ich."*
- Inf-Satz pode ser **ausgeklammert** no Nachfeld (default).

Default em: verbos de intenção, comunicação, decisão, controle (versuchen, beschließen, hoffen, versprechen, ...).

#### Verbos com ambas opções

Alguns verbos admitem ambas, com nuance:

```
Kohärent (gehoben/literário): Ich versuche das zu lesen.
Inkohärent (default norma):    Ich versuche, das zu lesen.
```

Verbos como `anfangen, aufhören, fortfahren, versuchen, drohen, scheinen, pflegen` admitem ambas. Em DE moderno, a inkohärenz é mais comum em escrita.

#### Komma-Regelung em Inf-Sätze

Norma de 1996: Komma é **obrigatório** em Inf-Sätze:
- Que contêm complemento(s): *"Ich versuche, das Buch zu lesen."*
- Introduzidos por `um, ohne, statt, anstatt, außer, als`: *"Ich gehe, um zu lernen."*
- Subordinados a substantivo (apostas e equivalentes): *"die Idee, das zu tun."*

Komma é **opcional** apenas em casos triviais sem complemento: *"Ich versuche zu lernen."* (curto, sem Komma também aceitável; com Komma também aceitável).

### 2.3 AcI (Accusativus cum Infinitivo)

Construção sintática **com verbos de percepção e causativos**:

```
V_perception/causative  +  NP-Akk  +  Infinitiv (ohne zu)
```

#### Verbos de percepção (sehen, hören, fühlen, spüren, riechen)

```
Ich sehe ihn kommen.            (Vejo-o vir / Vejo ele vindo)
Wir hörten sie singen.           (Ouvimos-a cantar)
Er fühlt das Herz schlagen.      (Sente o coração batendo)
Sie roch den Kuchen brennen.     (Cheirava o bolo queimando)
```

Estrutura: o **Akk-Objekt** ('ihn, sie, das Herz, den Kuchen') é simultaneamente:
- Objeto-percepto do verbo principal (o que se vê/ouve/sente).
- **Sujeito lógico** do Inf. ('cantar', 'bater', 'queimar' — quem canta/bate/queima).

#### Verbos causativos (lassen, machen)

```
Er lässt das Auto reparieren.       (Faz-se reparar o carro)
Sie ließen ihn warten.               (Fizeram-no esperar)
Das macht mich lachen.               (Isso me faz rir)
```

`lassen` em particular tem variedade semântica:
- Causativo: *Er lässt das Auto reparieren* (manda reparar).
- Permissivo: *Er lässt mich gehen* (deixa-me ir).
- Resultativo: *Sie lässt sich nicht beirren* (não se deixa intimidar).

### 2.4 `um ... zu` (final)

#### Estrutura

```
Hauptsatz, um + Inf-Satz mit zu.
```

#### Restrição de identidade de sujeitos

A construção exige **mesmo sujeito** no Hauptsatz e no Inf-Satz:

```
Ich gehe ins Kino, um meine Freunde zu treffen.       ✓ (Subj_HS = Subj_NS = ich)
*Ich gehe ins Kino, um du dich zu freuen.              ✗ (sujeitos diferentes)
```

Quando os sujeitos são diferentes, usar **Subjunktor `damit`** com Nebensatz pleno:

```
Ich gehe ins Kino, damit du frei bist.                 ✓ (Subj_HS = ich; Subj_NS = du)
```

### 2.5 `ohne ... zu` (modal-negativo) e `statt/anstatt ... zu` (substitutivo)

#### `ohne ... zu`

Negação de manner / circumstancial:

```
Er ging, ohne ein Wort zu sagen.            (Foi sem dizer uma palavra)
Sie arbeitet, ohne sich zu beschweren.      (Trabalha sem se queixar)
```

Mesma restrição de identidade de sujeitos. Quando sujeitos diferentes: `ohne dass + Nebensatz`:

```
Er ging, ohne dass ich es bemerkte.        (Foi sem que eu percebesse)
```

#### `statt/anstatt ... zu`

Substituição:

```
Statt zu lernen, schaute er fern.          (Em vez de estudar, viu TV)
Anstatt zu antworten, schwieg sie.          (Em vez de responder, calou-se)
```

Sujeitos idênticos. Diferentes: `(an)statt dass + Nebensatz`.

#### Padrão geral

```
Identidade de Subj.:    Inf-Satz com 'um/ohne/statt + zu + Inf'
Sujeitos diferentes:    Nebensatz pleno com Subjunktor (damit/ohne dass/statt dass)
```

### 2.6 Doppelinfinitiv-Konstruktion em VL

Em **Verbletztsatz** com **Modalverb em Perfekt + Vollverb-Inf.**, ordem inversa: Auxiliar finito **sobe** antes da pilha de infinitivos.

```
V2 / Hauptsatz:          Ich habe das Buch lesen können.
                         |  Aux.fin |        Inf-Vollverb + Inf-Modal
                         (rechte Klammer: 'lesen können')

VL / Nebensatz:          ..., dass ich das Buch habe lesen können.
                                 LK    Subj/MF    RK (Aux.fin + Inf-Vollverb + Inf-Modal)
                                                  ↑
                                                  Aux.fin SOBE — Doppelinfinitiv
```

Aplicado também a `werden` Futur + Modalverb + Vollverb:

```
..., dass ich das Buch werde lesen müssen.
                      ↑ Aux. werden finit antes da pilha
```

Ordem dentro da RK em Doppelinfinitiv: **Aux.finit + Vollverb-Inf + Modal-Inf**.

Restrita a Modalverben em Perfekt/Plusqp./Futur. Em Präsens/Prät., não há Doppelinf. (porque Modal não está como Inf.):

```
..., dass ich das Buch lesen kann.        (Modal-finit no fim — VL canônica)
..., dass ich das Buch lesen konnte.      (idem)
..., dass ich das Buch hatte lesen wollen. (Plusqp. Modal — DOPPELINF.)
..., dass ich das Buch hatte lesen sollen. (idem)
```

### 2.7 Diagnóstico — pipeline para Inf-Sätze

1. **Verbo regente é Modal, Sinnesverb, lassen, gehen?** Sim → Inf. **ohne zu**, kohärent.
2. **Verbo é AcI (sehen, hören, fühlen, lassen, machen)?** Sim → AcI: V + Akk + Inf-ohne-zu.
3. **Outro verbo regente?** Inf. **mit zu**.
4. **Komma?** Sim, se Inf-Satz tem complemento ou é introduzido por um/ohne/statt/außer/als.
5. **Identidade de sujeitos?** Sim → 'um/ohne/statt + zu + Inf'. Não → Subjunktor + Nebensatz.
6. **VL com Modal em Perfekt + Vollverb?** Doppelinfinitiv: Aux.finit antes da pilha.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Lista 6 verbos com **Inf. ohne zu** e 6 com **Inf. mit zu**, justificando cada classe.
2. Diferencia **kohärent vs. inkohärent** com 3 pares de exemplos.
3. Constrói 4 frases AcI com verbos de percepção + 2 com lassen.
4. Aplica `um ... zu` em 4 frases com identidade de sujeito + 4 com `damit` quando sujeitos diferem.
5. Aplica `ohne ... zu` e `statt/anstatt ... zu` em 4 frases.
6. Constrói 3 Doppelinfinitiv-Konstruktionen em VL (Modal em Perf., Modal em Plusqp., Modal em Futur).
7. Reescreve 3 Nebensätze (`dass`-Sätze) como Inf-Sätze, justificando quando o reescrita é gramatical/preferida.
8. Aplica Komma corretamente em 6 Inf-Sätze de complexidade variável.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Robert Musil — *Der Mann ohne Eigenschaften*** (1930–43), capítulo 1. Musil é mestre de Inf-Sätze encadeados em prosa filosófico-narrativa.

> "Es ist nicht leicht, in einer Welt, die so viele Möglichkeiten zu bieten scheint und doch keine zu erfüllen vermag, sich daran zu gewöhnen, jeden Morgen aufzustehen, ohne genau zu wissen, wozu, und sich abends wieder zur Ruhe zu legen, ohne die Gewissheit zu haben, etwas vollbracht zu haben. Mancher glaubt, dass es ihm gelinge, einfach zu existieren, ohne darüber nachzudenken; andere ringen damit, einen Sinn zu finden, statt sich mit dem Vorhandenen zufriedenzugeben. Ulrich gehörte zu denen, die sich entschlossen hatten, das Problem zu durchdenken, anstatt es nur zu erleiden — wobei er allerdings zugeben musste, dass auch das Durchdenken am Ende nichts ändern würde."

(Composto a partir de fragmentos canônicos do estilo Musil. Para o trecho integral, consultar Rowohlt, *Der Mann ohne Eigenschaften*, capítulo 1 "Woraus bemerkenswerterweise nichts hervorgeht".)

### Tarefa

Análise escrita, **800–1100 palavras** em PT-BR.

1. **Inventário Inf-Sätze**: identificar **todo Inf-Satz** no trecho. Mínimo 12. Para cada: forma (mit zu / ohne zu / um zu / ohne zu / statt zu), kohärent/inkohärent, função sintática (Subjekt-Inf, Objekt-Inf, attributiv, finalisch, modal-negativ, substitutiv).
2. **Identidade de sujeitos**: para cada `um/ohne/statt + zu + Inf`, verificar a identidade de sujeito.
3. **Komma-Markierung**: confirmar uso de Komma em cada Inf-Satz; identificar casos onde Komma é opcional.
4. **AcI no trecho**: localize qualquer (`scheint zu bieten` é diferente — discuta se é AcI ou outra construção).
5. **Aninhamento de Inf-Sätze**: o trecho tem Inf-Sätze dentro de Inf-Sätze (`gehörte zu denen, die sich entschlossen hatten, das Problem zu durchdenken, anstatt es nur zu erleiden`). Marcar cada nível e o sujeito controlador.
6. **Doppelinfinitiv-Konstruktion**: o trecho tem `zugeben musste, dass auch das Durchdenken am Ende nichts ändern würde` — não é Doppelinf. (porque Modal está em Prät., não Perf.). Mas exemplifique como ficaria se fosse `..., dass er das hat zugeben müssen`.
7. **Stilistische Bemerkung**: Musil constrói prosa onde Inf-Sätze longos refletem a indeterminação semântica do romance. Compare com Kafka (Aussagesatz curtas, parábolas) e Adorno (densidade nominal). Por que Musil usa Inf-Sätze tão profusamente para sua filosofia de "Möglichkeitssinn" (sentido das possibilidades)?

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **02-01 Subordination** (prereq): Inf-Satz é alternativa estrutural a Subordination com Subjunktor, com restrições.
- **01-01 Feldermodell**: Inf-Sätze ausgeklammert no Nachfeld (cf. 01-01 §2.6).
- **01-03 Verbalsystem**: Modalverben rege Inf. ohne zu — distinção morfológica de outros verbos.
- **02-04 Passivkonstruktionen**: Inf-Sätze podem combinar com Passiv: *"Es ist wichtig, gehört zu werden"*; *"Sie hofft, eingeladen zu werden"*.
- **02-06 Funktionsverbgefüge**: FVG frequentemente substitui Inf-Sätze em registro burocrático: *"zur Anwendung kommen"* em vez de *"angewendet zu werden"*.
- **02-07 Modalverben**: pré-requisito para Doppelinfinitiv-Konstruktion.
- **03-04 Pragmatik**: Höflichkeitsfloskeln frequentemente são Inf-Sätze: *"Ich hätte gern, ihn zu sprechen"*.
- **04-04 Generative Syntax**: Inf-Sätze como CP (PRO-controle) vs. VP-Adjunktion — análise gerativa.
- **PT comparativo**: PT é mais permissivo em Inf-Sätze (Inf. flexionado: 'para eu ver' / 'para tu veres'). DE não tem Inf. flexionado — usa estritamente identidade de sujeito ou Subjunktor + Nebensatz.

---

## 6. Quellen

1. **Eisenberg, Bd. 2**, capítulo sobre Infinitivkonstruktionen.
2. **Helbig/Buscha**, capítulo sobre Infinitiv und Infinitivsätze.
3. **Duden, Bd. 4**, capítulo sobre Infinitivsätze + Komma-Regeln.
4. **IDS-Grammis** — buscar "Infinitiv", "Kohärenz", "AcI", "Doppelinfinitiv".

### Especializada

- **Bech, Gunnar** — *Studien über das deutsche Verbum infinitum*. Niemeyer, 1955/1957. **Tratado clássico sobre Infinitivkonstruktionen.**
- **Reis, Marga / Sternefeld, Wolfgang** — papers sobre Kohärenz/Inkohärenz.
- **Wurmbrand, Susi** — *Infinitives: Restructuring and Clause Structure*. De Gruyter, 2001. (Análise gerativa.)

### Texto primário

- **Musil, Robert** — *Der Mann ohne Eigenschaften* (1930–43). Rowohlt KA.

---

**Próximo módulo:** [02-06 Funktionsverbgefüge](02-06-funktionsverbgefuege.md), prereq 02-04.
