---
module: 04-07
title: Textlinguistik — Kohäsion, Kohärenz, Textsorten
stage: system
prereqs: [03-07]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Distinção entre **Kohäsion** e **Kohärenz** em Textlinguistik?"
    options:
      - "Sinônimos."
      - "**Kohäsion = ligação gramatical** entre frases via mecanismos formais (anáfora pronominal, Konjunktoren, repetição lexical, isotopia, Tempora). **Kohärenz = ligação semântico-pragmática** que faz o texto fazer sentido como unidade temática (relação tópico-conteúdo, Implikaturen, frames cognitivos, conhecimento de mundo). Texto pode ser kohäsiv mas inkohärent (frases bem-ligadas mas sem sentido) ou kohärent mas wenig-kohäsiv (sentido implícito sem marcação formal)."
      - "Variação dialetal."
      - "Erro lingüístico."
    correct: 1
    explanation: "Halliday/Hasan (1976) + Brinker (1985+) estabelecem distinção. Kohäsion = mecanismos formais (anáfora, Konjunktor, Tempora-Sequenz, isotopia lexical). Kohärenz = unidade semântico-pragmática (frame, Topik-Kontinuität, Implikatur, conhecimento de mundo). Texto coerente exige ambos; um pode falhar enquanto outro funciona. Análise textlinguística mapeia ambos níveis."
  - q: "Que **5 mecanismos centrais de Kohäsion** Halliday/Hasan identificam?"
    options:
      - "Sem mecanismos."
      - "**(1) Reference (anáfora pronominal: er, sie, das); (2) Substitution (substituição lexical: einer, derselbe); (3) Ellipse (omissão: 'Peter kam und [∅] sah'); (4) Conjunction (Konjunktoren e Konjunktionaladverbien: und, aber, deshalb, gleichwohl); (5) Lexical Cohesion (repetição, Synonyme, Hyponym/Hyperonym, isotopia)**."
      - "Variação dialetal."
      - "Erro lingüístico."
    correct: 1
    explanation: "Halliday/Hasan 1976 (*Cohesion in English*) tipologia clássica, aplicada ao DE por Brinker. (1) Reference: anáfora ('Peter kam. Er war müde'). (2) Substitution: 'Ich nehme den blauen Pulli, du den roten'. (3) Ellipse: 'Peter las das Buch, [∅] schloss [∅] und legte [∅] weg'. (4) Conjunction: Konnektoren (cf. 02-01 + 02-09). (5) Lexical: repetição lexical, Synonyme, Hyponym-Hierarchien, isotopia (campos semânticos)."
  - q: "**Textsorte** vs. **Texttyp** em Brinker?"
    options:
      - "Sinônimos."
      - "**Textsorte = unidade comunicativa-funcional convencional na praxe lingüística** (Bedienungsanleitung, Geschäftsbrief, Roman, Gebrauchsanweisung, Lehrbuch). **Texttyp = abstração teórica que classifica funções textuais comunicativas básicas** (Informieren, Apellieren, Obligieren, Kontaktieren, Deklarieren). Distintos por nível de abstração: Textsorte = empírico-cultural; Texttyp = teórico-funcional. Brinker (1985 *Linguistische Textanalyse*) opera ambos."
      - "Variação dialetal."
      - "Apenas teórico."
    correct: 1
    explanation: "Brinker 1985 (*Linguistische Textanalyse*) distingue: Texttyp (5 funções: Informieren, Appellieren, Kontaktieren, Obligieren, Deklarieren — extensão de Searle Sprechakte para texto inteiro). Textsorte = realizações empíricas: Roman é Textsorte com função primária Informieren+Erzählen; Gebrauchsanweisung = Appellieren; Lehrbuch = Informieren. Análise textlinguística = identificar Texttyp + Textsorte + Kohäsion + Kohärenz."
  - q: "**Anaphorische Referenz** em DE oferece quais formas?"
    options:
      - "Apenas pronomes."
      - "**(1) Personalpronomen (er, sie, es, sie-Pl.); (2) Demonstrativpronomen tônico (der, die, das; dieser, jener); (3) NP plena com Det. definido (= 'der Mann'); (4) Substantivierungen (= 'die Reform' retomando ato antes mencionado); (5) Pronominaladverbien (damit, dafür, davon, daran).** Cada um tem distribuição + nuance pragmática distinta."
      - "Variação dialetal."
      - "Erro morfológico."
    correct: 1
    explanation: "Cf. 01-05 + 02-08. Anáfora em DE estratificada: Personalpronomen = referência básica; Demonstrativpronomen tônico = ênfase contrastiva; NP plena = re-ativação após distância; Substantivierung = retomada de proposição/ato; Pronominaladverb = retomada de PP/argumento abstrato. Análise textlinguística mapeia cadeias anaphóricas + diagnostica falhas (referência ambígua, distância excessiva)."
  - q: "Em prosa de Sebald (*Die Ringe des Saturn*, 1995), qual o estilo textual distintivo?"
    options:
      - "Convencional narrativa."
      - "**Kohäsion + Kohärenz extremas via parataxe associativa, frases longas hipotáticas, repetição de motivos isotópicos, intertextualidade densa (citação, alusão, referência fotográfica)**. Sebald constrói textos que parecem fragmentários superficialmente mas operam coerência associativa-meditativa em escala-livro. Modelo de Kohärenz literária moderna."
      - "Variação dialetal."
      - "Apenas estilística."
    correct: 1
    explanation: "Sebald (*Die Ringe des Saturn* 1995, *Austerlitz* 2001) é mestre da Kohärenz literária moderna. Características: parataxe associativa em frases longas (Konjunktoren leves: 'und', 'aber', 'oder'); isotopia (motivos: ruínas, viagem, memória, fotografia); intertextualidade densa (Conrad, Browne, Borges, Kafka); referência fotográfica como Kohäsions-Ressort visual. Modelo de coerência sem trama linear — análise textlinguística reveladora."
---

# 04-07, Textlinguistik — Kohäsion, Kohärenz, Textsorten

## 1. Sprachliches Problem

Textlinguistik analisa **unidades textuais inteiras** (não apenas frases isoladas). Como frases conectam? Como texto é coerente como unidade? Que tipos textuais existem? Aprendiz adulto que ignora textlinguística produz Aufsatz **com frases corretas mas com texto desarticulado**.

Aprendizes adultos travam em:

- **Kohäsion fraca**: produzir frases conectadas por 'und' apenas; faltar Konjunktionaladverbien acadêmicos (cf. 02-09).
- **Kohärenz quebrada**: frases corretas, mas texto sem foco temático; falhas de Topik-Kontinuität.
- **Misturar Textsorten**: produzir Aufsatz com elementos de Reportagem, ou Reportagem com Argumentation acadêmica.
- **Não dominar análise**: tratar texto como sequência de frases isoladas.

Sem este módulo, **CAPSTONE-3 e CAPSTONE-4** sofrem em coerência textual; análise crítica de textos canônicos (Sebald, Mann, Bernhard) fica plana.

---

## 2. Harte Theorie

### 2.1 Kohäsion — mecanismos formais

#### 5 categorias (Halliday/Hasan 1976; Brinker 1985 para DE)

##### (1) Reference / Anáfora

```
Personalpronomen:    Peter kam zu mir. Er war müde.
                            ↑
                            er = Peter (anáfora)
                            
Demonstrativpronomen tônico:
                     Hans und Peter waren da. Der eine kam aus Berlin, 
                     der andere aus Hamburg.
                     
Possessivpronomen:   Maria liest ihr Buch.   (ihr = Marias)
```

##### (2) Substitution

Substituição lexical de NP/VP por elemento mais reduzido:

```
"Welchen Pulli möchten Sie?"
"Den blauen."         (substituição: 'den blauen Pulli' → 'den blauen')

"Hat er das gesagt?"
"Das hat er nicht."   (substituição: 'das' substitui o conteúdo)

"Magst du Kaffee?"
"Ich nehme einen."    (Substituição com 'einen' = 'einen Kaffee')
```

##### (3) Ellipse

Omissão sintática recuperável pelo contexto:

```
Peter las das Buch und [∅] schloss [∅] und legte [∅] weg.
                       Subj.       Akk-Obj    Akk-Obj
                       elidido     elidido    elidido (recuperável)

"Wer kommt?" 
"Maria."   (= 'Maria kommt' — Subjekt + Verb omitidos)
```

##### (4) Conjunction (Konjunktoren + Konjunktionaladverbien)

Cf. 02-01 + 02-09. Marcadores explícitos de relação:

```
Aditivo:        und, ferner, zudem, überdies
Adversativo:    aber, jedoch, indessen, gleichwohl, allerdings
Causal:         weil, denn, deshalb, folglich, mithin
Temporal:       dann, danach, schließlich, zuvor, gleichzeitig
Konzessiv:      obwohl, trotzdem, dennoch, ungeachtet
Final:          damit, dazu, deswegen, um ... zu
Konditional:    wenn, falls, sofern, andernfalls
```

##### (5) Lexical Cohesion

###### Repetição lexical
```
Peter kam ins Zimmer. Peter setzte sich.    (repetição direta)
Peter kam ins Zimmer. Der Mann setzte sich. (repetição via Hyperonym)
```

###### Synonyme / Synonymie

```
'Aufklärung' ↔ 'Erleuchtung' (gehoben sinônimo parcial)
'Begriff' ↔ 'Konzept' (parcialmente)
```

###### Hyponymie / Hyperonymie

```
Hyperonym Vehículo: Auto
Hyponyma:           Sportwagen, LKW, Limousine, Cabrio
```

Cadeias hierárquicas em texto criam Kohäsion.

###### Isotopia (Greimas)

Recorrência de **traços semânticos** em texto:

```
Texto sobre crise econômica — isotopia /finanças/:
   Kapital, Investition, Rendite, Zinsen, Aktie, Anleihe, Konjunktur, BIP, 
   Inflation, Deflation, Wachstum, Rezession.

Texto sobre Heidegger — isotopia /Sein/:
   Sein, Seiende, Dasein, Wesen, Wahrheit, Lichtung, Verbergung, Eigentlichkeit.
```

Reconhecer isotopia = competência leitora; produzir isotopia = competência escritora.

### 2.2 Kohärenz — unidade semântico-pragmática

#### Princípios (Brinker, de Beaugrande/Dressler 1981)

Kohärenz emerge de:
1. **Topik-Kontinuität**: tópico mantido (com possíveis sub-tópicos).
2. **Frame-Konsistenz**: frame conceitual estável (e.g., 'visit ao médico' ativa frames específicos).
3. **Implikaturen disponíveis**: ouvinte pode preencher lacunas via inferência.
4. **Conhecimento de mundo**: comum/cultural permite resolução.

#### Texto kohäsiv mas inkohärent (raro mas possível)

```
"Peter kam ins Zimmer. Er ist 32 Jahre alt. Die Sonne scheint nicht."
   ↑ kohäsiv (er = Peter; resto frasal correto)
   ↑ inkohärent (sem unidade temática óbvia; exige forte inferência)
```

#### Texto kohärent com kohäsão fraca (frequente em literatura)

```
Sebald: "Die Bibliothek war leer. Die Sonne fiel durch die hohen Fenster. 
         Die Bücher staubten."
   ↑ kohäsão minima (Det. definido; ausência de Konjunktor)
   ↑ Kohärenz forte (frame: lugar antigo, decadência, contemplação)
```

#### Diagnóstico Kohärenz

Pergunta: **o texto faz sentido como unidade?**
- Topik se mantém ou muda coerentemente?
- Frames acumulados são compatíveis?
- Implikaturen recuperáveis?
- Conhecimento de mundo necessário é compartilhável?

### 2.3 Textsorte vs. Texttyp (Brinker 1985)

#### 5 Texttypen (funções comunicativas)

| Texttyp | Função primária | Textsorten típicas |
|---|---|---|
| **Informativ** | Informieren | Reportagem, Lehrbuch, Wikipedia-Artikel, Wissenschaftlicher Artikel |
| **Appellativ** | Appellieren / requerer ação | Anúncio publicitário, Bedienungsanleitung, Pamphlet político, Petition |
| **Obligativ** | Obligieren | Vertrag, Versprechen, Garantie, Eheschein |
| **Kontaktiv** | Kontaktieren | Geburtstagskarte, Kondolenzbrief, Smalltalk-Dialog |
| **Deklarativ** | Deklarieren | Urteil, Trauungsformel, Patentlauf, Ernennungsurkunde |

#### Textsorten DE canônicas (amostra)

```
Schriftliche:
  Roman, Erzählung, Novelle, Märchen
  Lyrik, Drama (texto)
  Aufsatz wissenschaftlich, Aufsatz argumentativ
  Reportagem, Kommentar, Glosse, Feuilleton, Leitartikel, Nachricht
  Geschäftsbrief, Privatbrief, E-Mail
  Bedienungsanleitung, Gebrauchsanweisung, Vertrag
  Lehrbuch, Lexikon-Artikel
  Tagebuch, Memoiren

Mündliche:
  Vortrag, Rede, Predigt
  Interview, Diskussion, Smalltalk
  Konferenzgespräch, Verhandlung
  Telefongespräch
```

Cada Textsorte tem convenções de **estrutura, registro, Kohäsion-Mechanismen, Implikaturen-Frames**.

### 2.4 Análise textlinguística — pipeline

#### Análise Kohäsion

1. **Cadeia anaphórica**: traçar Personalpronomen, Demonstrativ, NP plena retomando.
2. **Konjunktoren**: identificar conectivos lógicos.
3. **Substitutions / Ellipsen**: marcar omissões recuperáveis.
4. **Repetição lexical / Synonyme / Hyponym-Hierarchien**.
5. **Isotopia**: identificar traços semânticos recorrentes.

#### Análise Kohärenz

1. **Topik-Verfolgung**: Topik se mantém? Subtópicos relacionados?
2. **Frame-Konsistenz**: frames conceituais ativados são compatíveis?
3. **Implikaturen-Inferenz**: lacunas semantic-pragmáticas preenchíveis?
4. **Konhecimento de mundo**: necessário, disponível ao leitor pretendido?

#### Análise Textsorte

1. **Identificar Texttyp** primário (Brinker 5).
2. **Identificar Textsorte específica** (Roman, Aufsatz, Bedienungsanleitung).
3. **Convenções estruturais**: presença / ausência respeitada?
4. **Registro adequado** (cf. 03-02).

### 2.5 Sebald — caso paradigmático de Kohärenz literária

W.G. Sebald (1944-2001) constrói prosa onde Kohärenz **não emerge de trama linear** mas de **associação meditativa**. Características:

#### Parataxe associativa em frases longas

Frases longas com 'und'-encadeamento:

```
"Ich ging weiter, und die Sonne fiel hinter den Hügel, und die Schatten verlängerten 
sich, und ich dachte an die Zeit, als ich zum ersten Mal hier gewesen war, und an 
das Gespräch, das wir damals geführt hatten, und das ich seitdem nicht hatte 
vergessen können."
```

Konjunktoren leves ('und'); coordenação associativa; tempo cinematográfico.

#### Isotopia múltipla

```
Motivo /viagem/: Ich ging, gingen, wandere, Reise, Strecke, Weg, fortbewegen
Motivo /memória/: dachte, erinnerte, vergessen, früher, damals, einmal
Motivo /ruína/: Verfall, verlassen, leer, eingestürzt, vergangen
Motivo /tempo/: Stunde, Minuten, lange, schon, immer, erinnerte
```

Cada parágrafo entrelaça isotopias múltiplas — produz Kohärenz associativa.

#### Intertextualidade densa

Citações + alusões + referências:
- Joseph Conrad
- Sir Thomas Browne  
- Borges
- Kafka
- Walter Benjamin

Cada referência cria Kohäsion intertextual.

#### Fotografia como Kohäsions-Ressort

Imagens em preto-e-branco intercaladas. Não-decorativas; ancoram texto e criam Kohäsion visual-textual.

### 2.6 Aufsatz acadêmico — Kohäsion + Kohärenz calibradas

Cf. 03-07. Aufsatz exige:

```
Kohäsion:    
  - Anáforas claras (Personalpronomen + NP plena recorrente).
  - Konjunktionaladverbien acadêmicos (mithin, gleichwohl, ferner, indessen).
  - Wiederaufnahme de Begriffe centrais.
  - Tempora-Konsistenz (Präs. atemporal em definição; Prät./Perf. em narrativa de pesquisa).

Kohärenz:
  - Topik-Kontinuität com Begriff central.
  - Argumentation linear (These → Beleg → Schluss).
  - Frames conceituais explícitos.
  - Conhecimento prévio do leitor calibrado.
```

### 2.7 Diagnóstico — análise textlinguística

Pipeline:
1. **Identificar Texttyp + Textsorte**.
2. **Análise Kohäsion**: 5 mecanismos.
3. **Análise Kohärenz**: Topik, Frame, Implikatur.
4. **Diagnosticar falhas**: anáfora ambígua? Topik-Bruch? Konjunktor errado?
5. **Reescrita**: corrigir falhas.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Define **Kohäsion vs. Kohärenz** com 2 exemplos cada.
2. Lista os **5 mecanismos de Kohäsion** com 1 exemplo DE cada.
3. Diferencia **5 Texttypen Brinker** (Informativ, Appellativ, Obligativ, Kontaktiv, Deklarativ) com 1 Textsorte cada.
4. Identifica **isotopia** em 1 trecho dado.
5. Aplica **análise Kohäsion + Kohärenz** a 1 parágrafo de Aufsatz.
6. Diagnostica **anáfora ambígua** em 2 frases.
7. Reconhece **Sebald-Stil** em 1 trecho com 4 marcadores.
8. Calibra Kohäsion + Kohärenz em texto produzido próprio (Aufsatz).

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**W.G. Sebald — *Die Ringe des Saturn: Eine englische Wallfahrt*** (1995), capítulo 1 fragmento.

> "Im August 1992, als die Hundstage allmählich zu Ende gingen, hatte ich mich auf eine Wanderung durch die ostenglische Grafschaft Suffolk gemacht, in der Hoffnung, mich von der Beklemmung erholen zu können, die nach dem Abschluss einer größeren Arbeit über mich gekommen war. Und tatsächlich gelang es mir auch, in dem dünn besiedelten Landstrich zwischen Lowestoft und Aldeburgh stunden- und tagelang nicht eine einzige Menschenseele zu Gesicht zu bekommen. Die nächst gelegenen Ortschaften lagen nicht selten Stunden voneinander entfernt, und die wenigen Häuser, an denen ich vorbeikam, schienen mir verlassen oder waren von ihren Bewohnern nur in den Sommermonaten bezogen."

(Excerpt de Sebald, *Die Ringe des Saturn*, Eichborn 1995. Texto integral em Eichborn / Hanser.)

### Tarefa

Análise escrita, **800-1100 palavras** em PT-BR.

1. **Análise Kohäsion**: identificar mecanismos (Reference, Substitution, Ellipse, Conjunction, Lexical Cohesion). 4+ ocorrências.
2. **Anáforas-Kette**: traçar referência de 'ich, mich, meiner' no trecho. Onde apareceu primeiro? Como se mantém?
3. **Konjunktoren e Konjunktionaladverbien**: identificar 5 ocorrências. Função discursiva.
4. **Isotopia**: identificar **3 motivos isotópicos** (e.g., /viagem/, /isolamento/, /tempo/, /melancolia/).
5. **Tempora-Sequenz**: o trecho mistura Plusqp. ('hatte ich mich gemacht'), Konj. II ('erholen zu können'), Prät. (gingen, gelang, lagen). Análise de Tempora-Konsistenz.
6. **Kohärenz-Topik**: qual o Topik central? Como se mantém ao longo das 3 frases?
7. **Texttyp + Textsorte**: classificar (Roman? Erzählung? Reisebericht? meditativ?). Justificar.
8. **Stilkritik**: como Sebald codifica Kohärenz associativa-meditativa via parataxe + frases longas? Função estilístico-temática (memória, viagem, decadência).

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **03-07 Wissenschaftliches Schreiben** (prereq): Aufsatz-Kohäsion calibrada.
- **02-01 Subordination**: Konjunktoren como Kohäsions-Ressort.
- **02-09 Lexik II**: Konjunktionaladverbien acadêmicos.
- **01-05 Pronominalsystem**: anáfora.
- **04-06 Diskursanalyse**: análise meso de coerência.
- **04-08 Korpuslinguistik**: análise empírica de Kohäsion via corpus.

---

## 6. Quellen

1. **Brinker, Klaus** — *Linguistische Textanalyse: Eine Einführung in Grundbegriffe und Methoden*. 9. Aufl. E. Schmidt, 2018. **Manual canônico DE.**
2. **De Beaugrande, Robert / Dressler, Wolfgang** — *Einführung in die Textlinguistik*. Niemeyer, 1981. **Tratado fundador.**
3. **Halliday, M.A.K. / Hasan, Ruqaiya** — *Cohesion in English* (1976). Longman.
4. **Heinemann, Wolfgang / Viehweger, Dieter** — *Textlinguistik*. Niemeyer, 1991.
5. **Vater, Heinz** — *Einführung in die Textlinguistik*. UTB, 2001.

### Textsorten

- **Fix, Ulla** — *Texte und Textsorten — sprachliche, kommunikative und kulturelle Phänomene*. Frank & Timme, 2008.
- **Adamzik, Kirsten** — *Textsorten: Reflexionen und Analysen*. Stauffenburg, 2000.

### Texto primário

- **Sebald, W.G.** — *Die Ringe des Saturn: Eine englische Wallfahrt* (1995). Hanser/Eichborn.
- **Sebald** — *Austerlitz* (2001). Hanser.

---

**Próximo módulo:** [04-08 Korpuslinguistik](04-08-korpuslinguistik.md), prereq 04-02.
