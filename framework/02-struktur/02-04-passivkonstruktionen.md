---
module: 02-04
title: Passivkonstruktionen — werden-/sein-/bekommen-Passiv
stage: struktur
prereqs: [01-03]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Diferença entre 'Das Buch wird gelesen' e 'Das Buch ist gelesen'?"
    options:
      - "Sinônimos."
      - "**werden-Passiv (processual)**: 'wird gelesen' = ato em curso (alguém está lendo). **sein-Passiv (Zustandspassiv, resultativo)**: 'ist gelesen' = estado resultante (alguém já leu, e o livro está agora 'lido'). werden-Pass. enfatiza Vorgang; sein-Pass. enfatiza Zustand."
      - "É variação dialetal."
      - "'wird' é Futur."
    correct: 1
    explanation: "Distinção fundamental entre os dois Passiv em DE: werden-Passiv codifica processo (ação em curso ou repetição); sein-Passiv codifica estado resultante. Inglês colapsa em 'is read' (ambíguo); DE distingue morfologicamente. Toda transição evento→estado distingue-se: 'Die Tür wird geöffnet' (alguém está abrindo) vs. 'Die Tür ist geöffnet' (está aberta — resultado)."
  - q: "Em 'Mir wird geholfen', quem é o sujeito gramatical?"
    options:
      - "'mir' (Dat.)."
      - "Não há sujeito explícito — é **Passiv impessoal**. Verbos com Dat.-Rektion (helfen, danken, gefallen) **não promovem** o Dat. a Subjekt em Passiv (≠ promoção do Akk.). O Subjekt fica vazio; o Dat. mantém-se. Frase é gramatical e canônica em DE."
      - "'es' implícito como sujeito."
      - "'wird' é o sujeito."
    correct: 1
    explanation: "Restrição argumental do Passiv DE: apenas o **Akk.-Objekt** é promovido a Subjekt em werden-Passiv canônico ('Das Buch wird gelesen'). Verbos Dat.-rektiv não permitem promoção; em vez disso forma-se **Passiv impessoal** com Subjekt vazio: 'Mir wird geholfen' / 'Es wird mir geholfen' (com 'es' opcional como Vorfeld-Filler). Esta é uma diferença estrutural crítica do alemão."
  - q: "Como se forma o **bekommen-Passiv** (Dativ-Passiv) e qual sua função?"
    options:
      - "Não existe."
      - "**bekommen / kriegen / erhalten + Part. II**: 'Er bekommt das Buch geschenkt' = 'ele recebe o livro de presente'. Função: **promover o Dativ a Subjekt** em verbos como geben, schenken, schicken (Klasse III ditransitiva). Alternativa moderna ao Passiv impessoal canônico."
      - "Apenas em Aufsatz acadêmico."
      - "Variação dialetal."
    correct: 1
    explanation: "bekommen-Passiv (também kriegen-Passiv coloquial; erhalten-Passiv gehoben) é construção que promove o Dat. a Subjekt: 'Mir wird das Buch geschenkt' → 'Ich bekomme das Buch geschenkt'. Surge no séc. XIX, gehoben/jurídico inicialmente, hoje difundido. Klasse de verbos: Klasse III ditransitiva (geben, schenken, schicken, leihen, mitteilen, ...). Diferença de werden-Passiv: aqui o **receptor** é o sujeito, não o tema."
  - q: "Em 'Das Buch muss bis Freitag gelesen werden', identifique a estrutura."
    options:
      - "Indikativ Aktiv."
      - "**Modal + Passiv**: 'muss + Inf. werden' = werden-Passiv com Modalverb 'müssen'. Bildung: Modal-finit + (Akk.-Objekt) + (Adverbiale) + Part. II + Inf. de werden. Função: deontisch (obrigatoriedade do processo passivo). Equivalente Aktiv: 'Man muss das Buch bis Freitag lesen'."
      - "Konjunktiv I."
      - "Imperativ."
    correct: 1
    explanation: "Modal + Passiv combina Modalverben (können, müssen, sollen, dürfen, mögen) com werden-Passiv. Bildung: Modal-finit (LK em V2; RK em VL) + Part.II + Inf. de werden (na pilha verbal). Casos: 'Das muss gemacht werden' (deontisch); 'Es kann nicht ignoriert werden' (epistemisch). Em VL: '..., dass das Buch gelesen werden muss' — pilha invertida: Part.II + Inf.werden + Modal-finit (cf. 01-01 §2.7 Doppelinfinitiv-padrão)."
  - q: "Por que verbos como 'haben, kennen, wissen, kosten, betreffen' **não permitem werden-Passiv**?"
    options:
      - "Porque são intransitivos."
      - "São **stative Verben** (estados, não eventos) ou verbos com objeto cognitivo / abstrato. werden-Passiv exige Verbo dinâmico-eventivo + Akk.-Objekt afetado. 'haben' não tem evento; '*Das Auto wird gehabt' é agramatical. Outros verbos com restrição: kennen, wissen, kosten, betreffen, enthalten, bedeuten, erhalten (=ter)."
      - "São apenas Modalverben."
      - "Variação dialetal."
    correct: 1
    explanation: "werden-Passiv exige semântica eventiva-agentiva. Verbos puramente estativos (haben, besitzen, kennen, wissen) ou de propriedade abstrata (kosten, betreffen, enthalten, bedeuten) carecem de evento dinâmico passivizável. Restrição é semântica, não morfo-sintática. Subset de Verbos transitivos passivizáveis: ~70-80% dos transitivos clássicos (lesen, schreiben, schlagen, kaufen, sehen). Os outros 20-30% são bloqueados."
---

# 02-04, Passivkonstruktionen — werden-/sein-/bekommen-Passiv

## 1. Sprachliches Problem

Passiv em alemão **distingue dois tipos morfológicos** que PT/EN colapsam: **werden-Passiv (processual)** vs. **sein-Passiv (Zustandspassiv, resultativo)**. Mais: **bekommen-Passiv** promove o Dativ; **Passiv impessoal** ocorre com verbos Dat.-rektiv. Modal + Passiv combina Modalverben com werden-Passiv. Restrições argumentais e semânticas determinam quais verbos passivizam.

Aprendizes adultos travam em:

- **Confundir werden-Pass. com sein-Pass.**: produzir "Die Tür wird geöffnet" (= alguém está abrindo) onde quer dizer "Die Tür ist geöffnet" (= está aberta).
- **Tentar passivizar verbo Dat.-rektiv com Subjekt explícito**: `*Mir werde ich geholfen` em vez de `Mir wird geholfen` (impessoal).
- **Não conhecer bekommen-Passiv**: produzir paráfrase pesada onde DE moderno tem construção limpa.
- **Confundir Modal + Passiv** com Modal Aktiv: `*Das Buch wird gelesen werden müssen` (forma certa: `Das Buch muss gelesen werden`).
- **Tentar passivizar verbos stativos**: `*Das Buch wird gehabt`.

Sem este módulo:
- Você lê Mann (Roman, denso em Passiv resultativo), Habermas (Wissenschaftsdeutsch nominal), BGB (texto jurídico Passiv-saturado) e perde nuance.
- Você produz prosa acadêmica em Aktiv onde norma exige Passiv (impessoal).

---

## 2. Harte Theorie

### 2.1 werden-Passiv (Vorgangspassiv, processual)

#### Bildung

```
werden (finit) + Partizip II do Vollverbs
```

Em todos os tempos:

| Tempus | Bildung | Exemplo |
|---|---|---|
| Präsens Pass. | wird + Part.II | Das Buch wird gelesen. |
| Präteritum Pass. | wurde + Part.II | Das Buch wurde gelesen. |
| Perfekt Pass. | ist + Part.II + worden | Das Buch ist gelesen worden. |
| Plusqp. Pass. | war + Part.II + worden | Das Buch war gelesen worden. |
| Futur I Pass. | wird + Part.II + werden | Das Buch wird gelesen werden. |
| Futur II Pass. | wird + Part.II + worden + sein | Das Buch wird gelesen worden sein. |

**Atenção crítica**: o Partizip II de `werden` em Passiv-Perfekt **é `worden`**, não `geworden`. `geworden` é Part.II de `werden` como Vollverb (= "tornou-se"); `worden` é Part.II de `werden` como Aux. de Passiv.

```
Er ist Lehrer geworden.              (Vollverb: tornou-se professor)
Das Buch ist gelesen worden.         (Aux. Passiv: foi lido)
```

#### Promoção de argumento — Akk.→Nom.

werden-Passiv **promove o Akkusativobjekt do Aktiv a Subjekt-Nominativ**:

```
Aktiv:    [Subj.: Peter]  liest  [Akk.: das Buch].
Passiv:   [Subj.: Das Buch] wird  gelesen.       (mit Agens-Phrase opcional: 'von Peter')
```

O **Agens** (sujeito do Aktiv) torna-se PP-Komplement opcional com `von` ou `durch`:

```
Das Buch wird von Peter gelesen.            ('von' = agente humano direto)
Das Buch wird durch den Lehrer gelesen.     ('durch' = agência impessoal/instrumental)
```

Distinção `von` vs. `durch` (cf. Helbig/Buscha):
- `von + Dat.` = agente animado pessoal direto
- `durch + Akk.` = causa, instrumento, mediação

```
Der Brief wurde von der Sekretärin geschrieben.    (autora pessoal direta)
Der Brief wurde durch die Post zugestellt.         (instrumento/mediação)
```

Em Wissenschaftsdeutsch e Bürokratendeutsch, o Agens é frequentemente **omitido** (impessoalização).

#### Restrições semânticas

werden-Passiv exige:
1. Verbo **transitivo** (com Akk.-Objekt) **OU** Verbo com semântica passivizável.
2. Verbo **dinâmico-eventivo** (não-stativo).

Bloqueios:
- **Stative**: `haben, besitzen, kennen, wissen` — *Das Buch wird gehabt* é agramatical.
- **Property/abstract object**: `kosten, betreffen, enthalten, bedeuten, gleichen` — bloqueados.
- **Reflexive echtes**: `sich beeilen, sich freuen` — não passivizam (porque o reflexivo é parte do significado).

### 2.2 sein-Passiv (Zustandspassiv, resultativo)

#### Bildung

```
sein (finit) + Partizip II do Vollverbs
```

| Tempus | Bildung | Exemplo |
|---|---|---|
| Präsens | ist + Part.II | Die Tür ist geöffnet. |
| Präteritum | war + Part.II | Die Tür war geöffnet. |
| Perfekt | ist + Part.II + gewesen | Die Tür ist geöffnet gewesen. |
| Plusqp. | war + Part.II + gewesen | Die Tür war geöffnet gewesen. |

#### Função: estado resultante

sein-Passiv codifica **resultado** de processo verbal (Zustand resultativ):

```
werden-Passiv (processo): Die Tür wird geöffnet.
                          (alguém está abrindo / o ato está em curso)
sein-Passiv (estado):     Die Tür ist geöffnet.
                          (a porta está aberta — resultado de ter sido aberta)
```

Pares: 

```
Das Buch wird geschrieben.              (alguém está escrevendo)
Das Buch ist geschrieben.                (livro pronto, escrito)

Das Auto wird repariert.                 (mecânico está consertando)
Das Auto ist repariert.                  (carro consertado, em estado funcional)

Die Tür wird geschlossen.                (alguém está fechando)
Die Tür ist geschlossen.                 (porta fechada)
```

#### Diagnóstico de ambigüidade com Verben stativ-passiv

Alguns Adjektive são morfologicamente Part. II:

```
Er ist verheiratet.        (= Adj. atributivo? ou sein-Passiv?)
                           Pode ser ambíguo. Convenção: 'verheiratet' lexicalizou como Adj.
                           
Das ist verboten.          (Adj. lexicalizado a partir de Part.II)
```

Distinção operacional: se há ato de "agência implícita" reconstrutível (alguém abriu a porta), é sein-Passiv. Se é descrição estável de propriedade, é Adj. lexicalizado.

### 2.3 Passiv impessoal (Dat.-rektiv + alguns intransitivos)

Verbos que **não têm Akk.-Objekt** mas admitem Passiv: forma-se **Passiv impessoal** (Subjekt vazio).

#### Verbos Dat.-rektiv (helfen, danken, gefallen, gehören, ...)

```
Aktiv:        Der Arzt hilft mir.
Passiv:       Mir wird geholfen.
              (ou: Es wird mir geholfen — com 'es' como Vorfeld-Filler opcional)
```

O Dat. **mantém-se** Dat. (não é promovido a Nom.). Subjekt fica vazio; o Verbo conjuga em **3.Sg.** (impessoal).

#### Verbos intransitivos atelisches (tanzen, lachen, schlafen)

```
Aktiv:        Wir tanzten gestern.
Passiv:       Es wurde getanzt.        (= "dançou-se")
              Gestern wurde getanzt.    ('es' omitido se o Vorfeld está ocupado)
```

Função pragmática: **focar no evento, não no agente**. Útil em texto burocrático ou neutralizante.

### 2.4 bekommen-Passiv (Dativ-Passiv, neologismus moderno)

#### Bildung

```
bekommen / kriegen (coloquial) / erhalten (gehoben) + Part. II
```

#### Promoção do Dat. a Subjekt

```
Aktiv:                  Man schenkt ihm das Buch.
werden-Pass.:           Das Buch wird ihm geschenkt.   (Akk. promovido)
bekommen-Pass.:         Er bekommt das Buch geschenkt. (Dat. promovido!)
```

Klasse de verbos passivizáveis com bekommen:
- **Klasse III ditransitiva** (geben, schenken, schicken, bringen, leihen, erklären, zeigen, mitteilen, vorlesen, empfehlen, vorwerfen, verschreiben, verleihen, ...)
- Alguns verbos mit Dat-Objekt: `versprechen, anvertrauen, zumuten`.

Funcção pragmática: **focalizar o receptor** (o Dat.), em vez do tema.

bekommen-Passiv é difundido em DE moderno; gehoben em séc. XIX. Em Bürokratendeutsch e linguagem jurídica é norma.

### 2.5 Modal + Passiv

Combinação Modalverb + werden-Passiv:

```
Das Buch muss gelesen werden.            (deontisch: "tem que ser lido")
Das Buch kann gelesen werden.            (epistemisch ou possibilidade)
Das Buch sollte gelesen werden.          (sugestão / norma)
Das Buch darf gelesen werden.            (permissão)
```

Bildung: Modal-finit + Akk.-Objekt + Part.II + Inf. de werden.

Em VL (após Subjunktor):

```
..., dass das Buch gelesen werden muss.
       LK   Subj.            MF      RK
                                     ↑
                                     Pilha verbal: Part.II + Inf.werden + Modal-finit
```

Doppelinfinitiv quando Modal está em Perf.:

```
..., dass das Buch hat gelesen werden müssen.    (Doppelinfinitiv: Aux.finit + Part.II + Inf.werden + Modal)
```

Ordem inversa do esperado VL — auxiliar finito sobe (cf. 01-01 §2.7).

### 2.6 Edge cases

#### Doppelte Passiv (raro / gehoben)

```
?Es wird gespielt werden.              (não muito usado)
Es muss gespielt werden.               (Modal + Passiv — norma)
```

Modal sempre é melhor que doppelte werden.

#### Reflexiver Passiv (não existe)

DE não tem Passiv reflexivo morfológico (≠ PT "se vende casas"). Substitui-se por:
- Passiv impessoal: `Häuser werden verkauft`.
- Aktiv com `man`: `Man verkauft Häuser`.
- bekommen-Passiv (em casos específicos).

#### Adjektiv-Passiv (lexicalizações)

Muitos Part.II viraram Adj. plenos com perda de leitura passiva direta:

```
verheiratet, geöffnet, geschlossen, beleuchtet, eingeladen, ausgezeichnet, 
beliebt, bekannt, berühmt, betroffen, bestürzt, erfahren, geehrt
```

Diagnóstico: o Adj. funciona predicativamente sem agente reconstruível.

### 2.7 Função em registros

| Registro | Uso de Passiv |
|---|---|
| **Wissenschaftsdeutsch** | werden-Passiv saturado para impessoalidade ("Es wurde untersucht, dass...") |
| **Bürokratendeutsch / Recht** | Passiv onipresente (impessoalidade jurídica, "Es ist anzumerken, dass...") |
| **Reportagem jornalística** | Passiv em descrição de eventos sem agente confirmado |
| **Roman literário** | sein-Passiv (Zustand) frequente em descrições |
| **Fala coloquial** | Passiv reduzido; Aktiv com `man` é alternativa frequente |

### 2.8 Diagnóstico — pipeline

1. **Quero processo (em curso, repetido) ou estado (resultante)?** Processo → werden-Pass. Estado → sein-Pass.
2. **Verbo é transitivo (tem Akk.-Obj.)?** Sim → werden-Pass. canônico (Akk.→Nom.). Não → ver passos seguintes.
3. **Verbo é Dat.-rektiv?** → Passiv impessoal (Dat. mantém-se Dat.; Subj. vazio).
4. **Quero promover o receptor (Dat.) e não o tema (Akk.)?** → bekommen-Passiv.
5. **Há Modalverb modulando?** → Modal + werden-Pass. (Modal-finit + Part.II + Inf.werden).
6. **Verbo é stativ ou abstract object?** → Passiv bloqueado; reescrever com Aktiv-`man` ou sinônimo passivizável.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Diferencia werden-Pass. e sein-Pass. com 4 pares de exemplos próprios.
2. Conjuga `Das Buch wird gelesen` em **6 tempos** (Präs., Prät., Perf., Plusqp., Futur I, Futur II).
3. Aplica `worden` (Part.II Aux. de Passiv) vs. `geworden` (Part.II Vollverb) corretamente em 3 frases.
4. Constrói 3 **Passiv impessoal** (com `helfen, danken, tanzen`) em Präs. e Prät.
5. Aplica **bekommen-Passiv** em 4 frases com Klasse III ditransitiva.
6. Constrói 3 **Modal + Passiv** (Modalverb diferente em cada).
7. Identifica 5 verbos que **bloqueiam** werden-Passiv e justifica por restrição semântica.
8. Aplica `von` vs. `durch` em 4 frases com Agens-Phrase.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Thomas Mann — *Der Zauberberg*** (1924), capítulo "Schnee" (excerpt). Mann é mestre do Passiv resultativo em descrição.

> "Die Welt war verschneit. Die Tannen waren weiß bedeckt, die Wege waren tief verschüttet, und kein Geräusch wurde mehr von außen gehört. Der Wind, der gestern noch durch die Berge gepfiffen hatte, war zur Ruhe gekommen. Die Hütte, in der Hans Castorp Schutz gefunden hatte, war schwach beleuchtet, doch war ihm das Notwendigste gegeben worden: ein Bett, eine Decke, etwas Brot. Er fühlte sich gerettet, jedenfalls fürs Erste, und allmählich wurde ihm bewusst, dass er hier hatte überleben müssen, um zu erkennen, was eigentlich getan werden müsste, wenn er den Berg jemals lebend wieder verlassen wollte."

(Composto a partir de fragmentos canônicos do estilo Mann. Para o trecho integral, consultar Fischer KA *Der Zauberberg*, capítulo VI "Schnee".)

### Tarefa

Análise escrita, **800–1100 palavras** em PT-BR.

1. **Inventário Passiv**: identificar **toda Passiv-Konstruktion** no trecho. Mínimo 8. Para cada: tipo (werden- / sein- / bekommen- / impessoal / Modal+Pass.), Tempus, justificativa.
2. **werden vs. sein**: pelo menos 4 ocorrências. Diferenciar quando Mann codifica processo vs. resultado. Por que tantos sein-Passiv? (Pista: descrição estática de cenário Schnee; Zustand domina ação.)
3. **Adjektive-de-Part.II**: o trecho tem `verschneit, beleuchtet, gerettet, bewusst, beliebt`. Quais são lexicalizações Adj.? Quais são sein-Pass. com agência reconstruível?
4. **Modal + Passiv**: identificar **2+** ocorrências (`hatte überleben müssen, getan werden müsste`). Analisar a pilha verbal (especialmente em VL com Doppelinfinitiv).
5. **Agens-Phrase**: o trecho tem `von außen` (Adv. lokal, não Agens) e `durch die Berge` (não Agens, instrumento). Onde Agens é **omitido**? Por que (impessoalidade narrativa)?
6. **Konjunktiv II em Subordinadas**: `getan werden müsste, lebend wieder verlassen wollte` — identificar Konj. II + tempo + função.
7. **Stilistische Bemerkung**: Mann constrói prosa **descritiva** com sein-Passiv dominante. Compare com Heidegger (analisado no 01-06): também sein-Passiv em `was vom Sein übergeben ist`. Ambos usam Passiv resultativo para abstração filosófico-narrativa.

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-03 Verbalsystem** (prereq): Hilfsverb-Wahl em Perfekt informa Passiv (Aktiv com `sein`-Vergangenheit ↔ Passiv resultativo proximidade morfo-funcional).
- **01-02 Kasussystem**: Akk.-Objekt promovido vs. Dat.-Objekt mantido em Passiv impessoal.
- **02-01 Subordination**: Passiv em Verbletztsatz com pilha verbal complexa.
- **02-02 Konjunktiv I**: Passiv em discurso indireto: "Es wurde gesagt, dass die Maßnahme ergriffen werde."
- **02-03 Konjunktiv II**: Passiv irrealis: "Wäre die Maßnahme ergriffen worden, ..."
- **02-06 Funktionsverbgefüge**: FVG é alternativa nominal-Passiv em Bürokratendeutsch (`zur Anwendung kommen` em vez de `angewendet werden`).
- **03-01 Nominaler vs. verbaler Stil**: Passiv processual vs. nominalisierte Substantivierung.
- **03-07 Wissenschaftliches Schreiben**: Passiv impessoal é signum do registro acadêmico.
- **04-04 Generative Syntax**: Passiv como movimento sintático (Akk.-NP → Spec-IP).
- **PT comparativo**: PT distingue mal werden vs. sein-Pass. em morfologia (cópula 'ser' atende ambos: 'é lido' = werden ou sein-Pass. conforme contexto). DE distingue morfologicamente — re-treinar a percepção é parte central deste módulo.

---

## 6. Quellen

1. **Eisenberg, Bd. 2**, capítulo sobre Genus verbi.
2. **Helbig/Buscha**, capítulo sobre Passiv — listas de verbos passivizáveis e bloqueados.
3. **Duden, Bd. 4**, capítulo sobre Passiv.
4. **IDS-Grammis** — buscar "Passiv", "werden-Passiv", "Zustandspassiv", "bekommen-Passiv".

### Especializada

- **Eisenberg, Peter** — capítulos sobre Vorgangs- vs. Zustandspassiv.
- **Zifonun, Gisela** — *Grammatik des Deutschen im europäischen Vergleich: Das Passiv*. IDS, 2002.
- **Brinker, Klaus** — *Das Passiv im heutigen Deutsch*. Hueber, 1971. (Estudo seminal.)
- **Leiss, Elisabeth** — *Die Verbalkategorien des Deutschen: Genus verbi*. (papers diversos.)

### Texto primário

- **Mann, Thomas** — *Der Zauberberg* (1924). Capítulo "Schnee". Fischer KA.

### Bürokratendeutsch (para Passiv jurídico)

- **Bürgerliches Gesetzbuch (BGB)** — https://www.gesetze-im-internet.de/bgb/
- **Verwaltungsverfahrensgesetz (VwVfG)** — https://www.gesetze-im-internet.de/vwvfg/

---

**Próximo módulo:** [02-05 Infinitivsätze](02-05-infinitivsaetze.md), prereq 02-01.
