---
module: 02-01
title: Subordination — Subjunktoren und Verbletztstellung
stage: struktur
prereqs: [01-01, 01-03]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Diferença sintática entre 'denn' e 'weil'?"
    options:
      - "São sinônimos."
      - "'denn' é Konjunktor coordenativo (V2 mantido na 2ª oração); 'weil' é Subjunktor (licencia Verbletztstellung). 'Ich bleibe, denn es regnet.' (V2) vs. 'Ich bleibe, weil es regnet.' (VL)."
      - "'denn' é gehoben; 'weil' coloquial."
      - "'denn' rege Akk., 'weil' rege Dat."
    correct: 1
    explanation: "Distinção sintática crítica. Konjunktoren coordenativos (und, oder, aber, sondern, denn) **não licenciam** Verbletztstellung — segunda oração permanece V2. Subjunktoren (weil, dass, wenn, obwohl, ...) licenciam Verbletztstellung. Coloquialmente, 'weil' + V2 ('weil es regnet ja') é difundido em fala bávaro-austríaca, mas Hochsprache rejeita."
  - q: "Em 'Ich gehe, sobald er kommt', qual a função e Wortstellung de 'sobald'?"
    options:
      - "Adverbio temporal — 2ª oração mantém V2."
      - "Subjunktor temporal — licencia Verbletztstellung. 'sobald' significa 'assim que / no momento em que'. Ordem na 2ª oração: Subjunktor (LK) + Subj. + ... + V_finit (RK)."
      - "Substantivo."
      - "Modalpartikel."
    correct: 1
    explanation: "Subjunktoren temporais formam klasse específica: als (passado pontual), wenn (presente/futuro/iterativo), sobald, sooft, bevor, ehe, nachdem, seitdem, solange, während, kaum dass. Todos licenciam VL. 'als' vs. 'wenn' é distinção crítica: 'als' = uma vez, no passado; 'wenn' = repetitivo OU futuro/condicional."
  - q: "Em 'Sie sagte, dass sie krank sei' vs 'Sie sagte, dass sie krank ist', qual a diferença de modo?"
    options:
      - "São equivalentes."
      - "Konj. I 'sei' marca **Reportativ** (citação de discurso); Indikativ 'ist' marca **assunção do conteúdo pelo narrador**. FAZ/NZZ usam quase sempre Konj. I em indirekte Rede; fala coloquial usa Indikativ. Detalhe em 02-02."
      - "'sei' é gehoben; 'ist' coloquial."
      - "Erro morfológico em uma das frases."
    correct: 1
    explanation: "Konjunktiv I em 'dass'-Sätzen sinaliza Reportativ — narrador transmite mas não endossa. Indikativ sinaliza Endorsement: o narrador apresenta como fato. Em norma jornalística escrita, Konj. I é regra; em fala, Indikativ predomina. Heidegger e Kafka usam-no em diferentes funções narrativas (Kafka: distância; Heidegger: discurso filosófico)."
  - q: "Por que 'Wenn ich Zeit hätte, würde ich kommen' usa Konj. II e não Indikativ?"
    options:
      - "Estilística."
      - "Konditionalsatz **irrealis** (contrafactual: 'se eu tivesse tempo' implica que não tenho). Konj. II marca o irrealis em ambas as orações. Em condicional **real** ('wenn ich morgen Zeit habe, komme ich'), Indikativ é norma."
      - "Konj. II é norma escrita sempre."
      - "Erro: deveria ser 'wenn ich Zeit habe'."
    correct: 1
    explanation: "Konditionalsätze distinguem-se por realis vs. irrealis. Realis: 'wenn ich morgen Zeit habe, komme ich' (Indikativ; se acontecer, vou). Irrealis: 'wenn ich Zeit hätte, würde ich kommen' (Konj. II; contrafactual: não tenho tempo). Distinção morfo-semântica obrigatória em escrita; fala coloquial neutraliza com würde-Umschreibung em ambos os ramos."
  - q: "Quais Subjunktoren licenciam Verbletztstellung em alemão? Lista os 5 principais por categoria semântica."
    options:
      - "Apenas 'dass' e 'weil'."
      - "Causal: weil, da, zumal. Konzessiv: obwohl, obgleich, wenngleich. Konditional: wenn, falls, sofern. Final: damit, dass+Konj. Konsekutiv: sodass. Temporal: als, wenn, sobald, bevor, nachdem, während. Modal: indem, wobei. Komparativ: als ob, als wenn. Indireter Frage: ob, w-Wörter."
      - "Apenas conjunções coordenativas."
      - "Apenas em registro gehoben."
    correct: 1
    explanation: "Subjunktoren formam grande klasse aberta com 8+ subcategorias semânticas. Helbig/Buscha lista ~80; centrais ~40. Memorização Anki + reconhecimento por leitura intensiva. Cada Subjunktor licencia Verbletztstellung obrigatoriamente em norma escrita."
---

# 02-01, Subordination — Subjunktoren und Verbletztstellung

## 1. Sprachliches Problem

Subordination é onde Stage 2 começa. No Stage 1, dominou-se a Aussagesatz simples (V2). Aqui se aprende a **encadear orações** mantendo a arquitetura sintática rígida do alemão (Verbletztstellung em Nebensatz, mas V2 mantido em Hauptsatz mesmo após coordenativo).

Aprendizes adultos travam em:

- **Confundir Konjunktor (coordenativo) com Subjunktor (subordinativo)**: usar `denn` esperando Verbletztstellung, ou `weil` esperando V2.
- **Listar Subjunktoren** mas não diferenciá-los por nuance semântica (`als` vs. `wenn`; `weil` vs. `da` vs. `zumal`; `obwohl` vs. `obgleich` vs. `wenngleich`).
- **Aplicar modo** errado em Nebensatz: usar Konjunktiv I em condicional (deveria ser Konj. II), ou Indikativ em Reportativ jornalístico (deveria ser Konj. I).
- **Resolver Komma-rules**: norma alemã exige vírgula obrigatória antes de toda Nebensatz (≠ EN, onde é frequente opcional).
- **Coordenação de Nebensätze**: como aninhar um Nebensatz dentro de outro? Como coordená-los? Como decidir extraposição (Nachfeld) vs. encaixamento (Mittelfeld)?

Sem este módulo:
- Você produz `*Ich bleibe, weil es regnet ja` (V2 em weil-Satz, errado em escrita).
- Você lê Kafka *Der Process* (denso em subordinação encadeada) e perde a estrutura argumental.
- Você falha em produzir Aufsatz acadêmico — o registro depende de subordinação multi-camada.

---

## 2. Harte Theorie

> 📚 **Listas exhaustivas** dos 3 klassen sintáticas de Konnektoren (Konjunktoren / Subjunktoren / Konjunktionaladverbien) com função + Beleg em [ANHANG D — Konnektoren](../00-meta/anhaenge/ANHANG-D-KONNEKTOREN.md). Esta seção apresenta as klassen sintáticas; o Anhang é referência consultável.

### 2.1 Konjunktor vs. Subjunktor — distinção fundamental

#### Konjunktoren (coordenativos) — não licenciam VL

Klasse pequena (klasse fechada): `und, oder, aber, sondern, denn, doch (= aber), allein (gehoben = aber)`.

Comportamento sintático: **mantêm V2** em ambas orações coordenadas.

```
Ich bleibe, denn es regnet.       (V2 em ambas: 'bleibe' em 1ª; 'regnet' em 2ª)
Ich bleibe, aber er geht.         (V2 + V2)
Ich gehe, oder ich bleibe.        (V2 + V2)
```

Konjunktoren também ocorrem em coordenação **interna** (sem Komma quando coordena constituintes, não orações): `Hund und Katze, Apfel oder Birne, schnell aber falsch`.

#### Subjunktoren (subordinativos) — licenciam VL

Klasse aberta + grande. Toda Subjunktor introduz Nebensatz com **Verbletztstellung**: o Subjunktor ocupa a linke Klammer (LK); o verbo finito desce para a rechte Klammer (RK).

```
..., weil es regnet.                              (LK 'weil' + ... + RK 'regnet')
..., dass er kommt.                               (LK 'dass' + ... + RK 'kommt')
..., obwohl er müde ist.                          (LK 'obwohl' + ... + RK 'ist')
..., wenn ich Zeit habe.                          (LK 'wenn' + ... + RK 'habe')
..., bevor wir gehen.                             (LK 'bevor' + ... + RK 'gehen')
```

### 2.2 Subjunktoren por categoria semântica

#### Kausal (causa, razão)

| Subjunktor | Nuance |
|---|---|
| **weil** | causa direta, default neutro |
| **da** | causa conhecida/compartilhada (gehoben) |
| **zumal** | causa adicional reforçando (gehoben) |
| **deshalb / deswegen** (conjuncional, V2!) | conseqüência (= "por isso, portanto") — **não Subjunktor mas Konjunktionaladverb**: licencia V2, não VL |

Distinção `weil` vs. `da`:
- `weil`: introduz causa nova/desconhecida. Default em fala e escrita.
- `da`: causa já conhecida ou pressuposta. *"Da Sie ja schon Bescheid wissen, ..."* (= "como você já sabe").

#### Konzessiv (concessão / oposição)

| Subjunktor | Nuance |
|---|---|
| **obwohl** | concessão neutra (= "embora") |
| **obgleich** | concessão gehoben (= obwohl) |
| **wenngleich** | concessão muito gehoben |
| **auch wenn** | concessão hipotética (= "mesmo se") |
| **selbst wenn** | concessão hipotética enfática |
| **trotzdem** (Konjunktionaladv., V2!) | "apesar disso" — não licencia VL |

#### Konditional (condição)

| Subjunktor | Nuance |
|---|---|
| **wenn** | condição real ou hipotética; default |
| **falls** | condição real eventuativa (= "caso") |
| **sofern** | condição restritiva (= "na medida em que") |
| **es sei denn, dass / es sei denn** | exceção (= "a menos que") |

Distribuição em irrealis: `wenn ... wäre + Konj. II` (cf. 02-03).

#### Final (finalidade)

| Subjunktor | Nuance |
|---|---|
| **damit** | finalidade neutro |
| **dass** + Konj. (gehoben) | finalidade gehoben (raro) |
| **um ... zu + Inf.** | finalidade com Inf-Satz (cf. 02-05); só se sujeito é o mesmo das duas orações |

```
Ich gehe, damit du frei bist.         (sujeitos diferentes → damit + Nebensatz)
Ich gehe, um frei zu sein.            (sujeito mesmo → um + zu-Inf-Satz)
```

#### Konsekutiv (conseqüência)

| Subjunktor | Nuance |
|---|---|
| **sodass / so dass** | conseqüência neutra |
| **so ... dass** (Korrelat) | conseqüência intensificada |

```
Es regnete stark, sodass ich nass wurde.
Es regnete so stark, dass ich nass wurde.
```

#### Temporal (tempo)

Klasse com **distinção crítica** `als` vs. `wenn`:

| Subjunktor | Função |
|---|---|
| **als** | passado pontual, único: *"Als ich gestern kam, ..."* |
| **wenn** | presente / futuro / repetição passada: *"Wenn ich komme, ..."* / *"Immer wenn ich kam, ..."* |
| **sobald** | "assim que" |
| **sooft** | "sempre que" |
| **bevor / ehe** | "antes que" |
| **nachdem** | "depois que" — Tempus shift obrigatório (Plusqp. + Prät. ou Perf. + Präs.) |
| **seitdem / seit** | "desde que" |
| **solange** | "enquanto" |
| **während** | "durante / enquanto" |
| **kaum dass** | "mal/assim que" (gehoben) |
| **bis** | "até que" |

**Tempus-Concord em `nachdem`**:

```
Nachdem er gegessen hatte, ging er.        (Plusqp. + Prät.)
Nachdem er gegessen hat, geht er.          (Perf. + Präs.)
*Nachdem er aß, ging er.                    (Tempus errado — duas Prät.)
```

#### Modal / Comparativ (modo / comparação)

| Subjunktor | Função |
|---|---|
| **indem** | "ao + Inf." (modo, simultaneidade) |
| **wobei** | "no que / sendo que" (modo accessorial) |
| **als ob / als wenn** + Konj. II | "como se" (comparação irrealis) |
| **soviel / soweit** | "tanto quanto / até onde" |
| **je ... desto / umso** (Korrelat) | "quanto mais ... mais" |

```
Er löste das Problem, indem er die Methode anwandte.
Es schien, als ob er müde wäre.
Je mehr er las, desto besser verstand er.
```

#### Indireter Frage (W-Frage / Polar)

| Forma | Função |
|---|---|
| **ob** | indireter polar Frage (= EN "whether") |
| **wer / was / wann / wo / warum / wie / welcher / wessen / wem / wen** (W-Wörter) | indireter W-Frage |

```
Ich frage mich, ob er kommt.            (polar)
Ich weiß nicht, wann er kommt.          (W-Frage)
Er fragte, wo das Buch sei.             (W-Frage com Konj. I)
```

W-Wörter funcionam como Subjunktoren em Nebensatz indireter; licenciam VL.

### 2.3 Wortstellung em Nebensatz com Subjunktor

Padrão geral:

```
[Subjunktor]  [Subj./Pron.]  [Mittelfeld]  [V_finit]
     LK            (na ordem do MF)              RK
```

```
..., weil | Peter | gestern das Buch | gelesen hat.
       LK    Subj      Mittelfeld         RK
```

A RK absorve **toda a pilha verbal** (Aux. + Modal + Vollverb não-finito). Em VL com Modal + Inf., ordem dentro da RK: `..., weil er das Buch lesen wollte` (Inf. + Modal-finito).

#### Doppelinfinitiv-Konstruktion (cf. 01-01 §2.7)

Em VL com `werden` Futur ou com Modal em Perfekt + Vollverb, surge inversão: Auxiliar finito **sobe** antes da pilha de infinitivos.

```
..., weil er das Buch hat lesen wollen.        (Modal em Perf., DOPPELINFINITIV)
..., dass er das Buch wird lesen müssen.       (Futur + Modal + Vollverb)
```

Não:
```
*..., weil er das Buch lesen wollen hat.       (agramatical com Modal-Vollverb-Aux)
```

### 2.4 Komma-Regelung

Regra de ouro: **toda Nebensatz é separada por Komma** em norma escrita (≠ EN, onde é frequente opcional).

```
Ich gehe, weil es regnet.            ✓
Bevor er kam, hatte ich gegessen.    ✓
Er sagte, dass er müde sei.          ✓
```

Komma também separa:
- Konjunktoren coordenativos antes de oração coordenada com sujeito explícito (`Ich bleibe, denn es regnet`).
- Infinitivsätze com `zu` quando contém complemento (cf. 02-05): *"Es ist wichtig, ihn zu fragen."*
- Aposições, parênteses, vocativos.

Não separa:
- Coordenação de constituintes simples (`Hund und Katze`).
- Adverbiais simples no Vorfeld (`Heute komme ich.`).

### 2.5 Aninhamento e coordenação de Nebensätze

#### Aninhamento (uma Nebensatz dentro de outra)

```
[Hauptsatz, [NS1, [NS2 dentro de NS1]]]
```

```
Er sagte, dass er weiß, dass es geregnet hat.
   ↑ NS1  ↑ Subj.+Verb fim   ↑ NS2 dentro de NS1, Subj. + Verb fim
```

Cada nível tem sua própria VL. Quando o aluno encontra 3-4 níveis, deve **identificar fronteiras** e cada Subjunktor + Verb fim independentemente.

#### Coordenação de Nebensätze

Por `und, oder, aber`, com Konjunktor antes da segunda Nebensatz:

```
Er sagte, dass er müde sei und dass er gehe.       (coord. de duas NS dass-)
                ↑ NS1            ↑ NS2 (Konjunktor 'und' coordena)
```

Pode-se elidir o segundo Subjunktor (gehoben):

```
Er sagte, dass er müde sei und gehe.               (Subjunktor 'dass' elidido)
```

#### Posição da Nebensatz: Vorfeld, Mittelfeld, Nachfeld

| Posição | Exemplo |
|---|---|
| Vorfeld | *Dass er kommt, freut mich.* (Nebensatz topicalizada como Subjekt) |
| Mittelfeld | *Ich habe, weil es regnete, einen Schirm gekauft.* (raro, gehoben/literário) |
| Nachfeld (default) | *Ich habe einen Schirm gekauft, weil es regnete.* (Ausklammerung; default em fala e escrita) |

Cf. 01-01 §2.6 Ausklammerung.

### 2.6 Edge cases e Plurizentrik

#### `weil` + V2 em fala (proibido em norma)

```
Coloquial bávaro/austríaco:  Ich bleibe, weil es regnet ja.    (V2 em weil-Satz!)
Norma escrita:                Ich bleibe, weil es ja regnet.    (VL canônica)
```

Em fala bávaro-austríaca, "weil" + V2 é difundido e tem função pragmática distinta (causa "razão a posteriori" vs. "weil + VL" = causa "factual"). Norma escrita rejeita.

#### `denn` em uso restrito

`denn` ocorre **apenas como Konjunktor coordenativo** (V2). Não confundir com Modalpartikel `denn` em Frage (cf. 01-07 §2.5):

```
Ich gehe, denn es regnet.            (Konjunktor coordenativo causal)
Was machst du denn?                  (Modalpartikel; sem efeito subordinativo)
```

#### `nachdem` causal (gehoben)

Em registro acadêmico, `nachdem` pode introduzir causal (= "uma vez que"), homógrafo do temporal:

```
Nachdem die Voraussetzungen erfüllt sind, kann der Antrag bearbeitet werden.
   ↑ Causal (= "uma vez que / sendo que"), não temporal puro.
```

Distingue-se do temporal pelo Tempus-padrão: causal pode usar Präsens; temporal exige Tempus shift.

### 2.7 Diagnóstico — pipeline para Subordination

1. **Konjunktor ou Subjunktor?** Konjunktor (und, oder, aber, sondern, denn, doch) → V2 mantido. Subjunktor → VL obrigatória.
2. **Que categoria semântica?** (causal, konzessiv, konditional, final, ...)
3. **Modo**: Reportativ → Konj. I (cf. 02-02). Irrealis → Konj. II (cf. 02-03). Default → Indikativ.
4. **Tempus**: `nachdem` → shift obrigatório. Outros → conforme contexto.
5. **Komma**: presente antes de toda Nebensatz.
6. **Posição**: Nachfeld (default) / Vorfeld (topicalização) / Mittelfeld (gehoben).
7. **Aninhamento**: identificar cada nível separadamente; cada um tem sua VL.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Lista 8+ Subjunktoren em 4 categorias semânticas (causal, konzessiv, konditional, temporal) com 1 exemplo cada.
2. Diferencia `denn` (Konjunktor) de `weil` (Subjunktor) com pares de exemplos mostrando V2 vs. VL.
3. Aplica `als` vs. `wenn` corretamente em 6 frases (passado pontual / repetitivo / futuro / condicional).
4. Constrói 3 frases em **3 níveis de aninhamento** (Hauptsatz com NS1 com NS2 dentro de NS1).
5. Coordena 2 Nebensätze com `und` em 1 frase (com elisão facultativa do segundo Subjunktor).
6. Distingue `dass` + Indikativ (assunção) de `dass` + Konj. I (Reportativ) com 2 exemplos próprios.
7. Aplica Tempus-shift em 2 frases com `nachdem` (Plusqp. + Prät.; Perf. + Präs.).
8. Reescreve 3 frases coloquiais (`weil` + V2) em norma escrita (VL).

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Franz Kafka — *Der Process***, capítulo "Im Dom" (1925, póstumo). Trecho do diálogo K. com o Geistlicher.

> "Du missverstehst den Schreiber, sagte der Geistliche; was er sagt, hat einen anderen Sinn, als du ihm gibst, weil du der Welt zu sehr verhaftet bist und nicht erkennst, dass es Dinge gibt, die jenseits aller alltäglichen Bedeutung liegen, und dass das, was vom Türhüter berichtet wird, nicht im Sinne des bürgerlichen Rechts zu deuten ist, sondern im Sinne einer Wahrheit, die das menschliche Verstehen übersteigt, ohne dass sie deshalb falsch wäre."

(Composto a partir de fragmentos canônicos do estilo Kafkaiano. Para o trecho integral, consultar Suhrkamp KA *Der Process*, capítulo IX.)

### Tarefa

Análise escrita, **800–1200 palavras** em PT-BR com terminologia DE intacta. Sem consultar.

1. **Identificação de Subjunktoren e Konjunktoren** no trecho. Marcar cada um, classificar (categoria semântica), e identificar VL/V2 da oração que introduzem.
2. **Análise topológica em níveis**: o trecho tem aninhamento profundo (3-4 níveis). Marcar cada nível, com sua linke Klammer (Subjunktor) e rechte Klammer (verbo finito).
3. **Identificar Konjunktiv I/II** se presentes (`falsch wäre`). Justificar modo escolhido.
4. **Identificar Passivkonstruktionen** (`berichtet wird`, `zu deuten ist`). Tipo (werden-Pass. processual; sein-Pass. ou Modalkonstruktion?).
5. **Wortstellung dos Nebensätze**: posição (Nachfeld? Vorfeld? Mittelfeld?). Justificar cada escolha.
6. **Komma-Markierung**: confirmar que cada Nebensatz é precedida por Komma. Identificar se há outras vírgulas (aposição, ...).
7. **Stilistische Bemerkung**: Kafka encadeia 4+ Nebensätze coordenadas/aninhadas numa única frase. Função estilística-narrativa? (Compare com prosa simples de *Vor dem Gesetz* analisada no 01-02 — mesmo autor, registros distintos.)

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-01 Feldermodell** (prereq): Subjunktor = LK em VL; verbo finito = RK em VL.
- **01-03 Verbalsystem** (prereq): formas verbais finitas no Stamm da RK em VL.
- **01-07 Negation und Modalpartikeln**: Modalpartikeln habitam o Mittelfeld também em Nebensätze.
- **02-02 Konjunktiv I**: dass-Sätze + indireter Frage frequentemente exigem Konj. I.
- **02-03 Konjunktiv II**: konditional irrealis + comparação `als ob` + Wunschsatz.
- **02-05 Infinitivsätze**: `damit` Subjunktor vs. `um ... zu + Inf.` em finalidade.
- **02-08 Topik-Fokus**: posição da Nebensatz no Vorfeld é topicalização proposicional.
- **03-04 Pragmatik**: nuance entre `weil`, `da`, `zumal` é diferença pragmática.
- **04-04 Generative Syntax**: subordinação como projeção CP em árvore X-bar.
- **PT comparativo**: PT mantém SVO em subordinação (`porque está chovendo`); DE muda para VL (`weil es regnet`). Re-treino exige internalizar fluxo invertido.

---

## 6. Quellen

1. **Eisenberg, Bd. 2**, capítulo sobre Nebensatz e Subjunktoren.
2. **Helbig/Buscha**, capítulo sobre Konjunktionen — listagem exaustiva.
3. **Engel**, *Deutsche Grammatik*, capítulo sobre Subordination.
4. **Duden, Bd. 4**, capítulos sobre Konjunktionen e Komma-Regeln.
5. **IDS-Grammis** — buscar "Subjunktor", "Nebensatz", "Verbletztstellung".

### Literatura especializada

- **Pasch, Renate / Brauße, Ursula et al.** — *Handbuch der deutschen Konnektoren*. De Gruyter, 2003. **Tratado canônico das conjunções e Subjunktoren.**
- **Reis, Marga / Wöllstein, Angelika** — *Wortstellung im Deutschen*. Niemeyer.

### Texto primário

- **Kafka, Franz** — *Der Process*. Kritische Ausgabe, S. Fischer.

---

**Próximo módulo:** [02-02 Konjunktiv I](02-02-konjunktiv-1.md), prereq deste.
