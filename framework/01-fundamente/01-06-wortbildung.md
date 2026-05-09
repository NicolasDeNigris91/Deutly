---
module: 01-06
title: Wortbildung I — Komposition, Derivation, Konversion, Fugenelemente
stage: fundamente
prereqs: [01-04]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em 'Donaudampfschiffahrtsgesellschaftskapitän', quantos Komposita-Glieder há e qual o Determinatum (último elemento determinante)?"
    options:
      - "5 Glieder; Determinatum = Donau."
      - "6 Glieder (Donau + Dampf + Schiff + Fahrt + Gesellschaft + Kapitän); Determinatum = Kapitän — herda Genus (m.) e Numerus do último elemento."
      - "É uma única palavra simples."
      - "É erro de escrita; deveria ser separada."
    correct: 1
    explanation: "Komposita longos são típicos do alemão (especialmente Bürokratendeutsch). Regra de leitura: identificar fronteiras morfológicas (Fugenelemente como -s- são pistas), ler **da direita para a esquerda** — o último elemento (Determinatum) determina Genus e Numerus; os anteriores (Determinantia) modificam-no. 'Donaudampfschiffahrtsgesellschaftskapitän' = capitão da companhia de navegação a vapor do Danúbio = Kapitän (m., Sg.)."
  - q: "Por que 'Liebesbrief' tem '-s-' entre 'Liebe' e 'Brief'?"
    options:
      - "Erro ortográfico; norma seria 'Liebebrief'."
      - "É um Fugenelement morfo-fonológico (-s-, -(e)n-, -e-, -er-, -ens-, -∅). Distribuído por padrão derivacional do primeiro elemento. Sufixos -ung, -heit, -keit, -schaft, -tum, -tät tipicamente disparam Fugen-s. 'Liebe' não termina em sufixo claro mas trate-se de morphologia lexicalizada com Fugen-s."
      - "É variante austríaca."
      - "Indica relação de posse."
    correct: 1
    explanation: "Fugenelemente são morfemas auxiliares entre os elementos de um Kompositum. Distribuição é em parte regular (sufixo -ung → -s: Erfahrungsbericht; sufixo -keit → -s: Wirklichkeitsverlust; sufixo -heit → -s: Freiheitsraum) e em parte lexicalizada (Liebesbrief, Tagesschau, Mannschaftskapitän). Não é 'genitivo posposto' — embora histórico-etimologicamente venha do Genitiv."
  - q: "Em 'Lehrer' (m.) → 'Lehrerin' (f.) → Plural?"
    options:
      - "die Lehrerinnen — sufixo Pluralbildung -nen para feminino derivado em -in."
      - "die Lehrerin (invariável)."
      - "die Lehrerins."
      - "die Lehrerinen."
    correct: 0
    explanation: "Substantivos femininos derivados em -in formam Plural com **duplicação consonântica + -en**: -in → -innen. Padrão: Lehrer → Lehrerin → Lehrerinnen; Student → Studentin → Studentinnen; Doktor → Doktorin → Doktorinnen. A duplicação do 'n' é ortográfica (sílaba átona; impede leitura *-i-nen)."
  - q: "Heidegger escreve 'In-der-Welt-sein' como conceito central. Que tipo de Wortbildung é essa?"
    options:
      - "Erro ortográfico."
      - "Substantivierung de Phrase via hyphenação — fenômeno típico de Wissenschaftsdeutsch hoch e especialmente da fenomenologia heideggeriana. Toda a phrase 'In-der-Welt-sein' funciona como NP única, Neutrum (porque o núcleo é o Inf. substantivado 'sein'), Sg. Genitiv = 'des In-der-Welt-seins'."
      - "Variante poética."
      - "Calco do latim."
    correct: 1
    explanation: "Heidegger usa hyphenação para Substantivieren phrases inteiras como conceitos filosóficos: 'In-der-Welt-sein' (ser-no-mundo), 'Sein-zum-Tode' (ser-para-a-morte), 'Mit-sein' (ser-com), 'Sich-zeigen' (mostrar-se). O Determinatum (núcleo categorizador) é o último elemento — frequentemente Inf. substantivado em -en (Neutrum). Genus e Numerus seguem o último."
  - q: "Em 'das Lesen', 'das Gehen', 'das Schwimmen' (Substantivierung de Verb-Inf.), todos têm Genus = Neutrum. Por quê?"
    options:
      - "Coincidência."
      - "Todo Inf. substantivado é Neutrum sistematicamente — regra mecânica da Wortbildung. Conjuga-se com a tendência geral: Substantivierungen abstratas → Neutrum."
      - "Apenas verbos com -en final."
      - "É variação dialetal."
    correct: 1
    explanation: "Substantivierung do Inf. é mecanicamente Neutrum, sem exceções. 'das Lesen, das Schreiben, das Singen, das Tanzen, das Sterben'. Genitive: 'des Lesens'. Plural raríssimo (Inf. é abstrato; Pl. quando se concebe instâncias: 'die Lesungen' usa-se -ung, não Inf.subst.). Outros padrões automáticos: -chen/-lein → n.; -ung → f.; -keit/-heit → f."
---

# 01-06, Wortbildung I — Komposition, Derivation, Konversion, Fugenelemente

> 📚 **Sistematização exhaustiva** dos 3 Wortbildungs-Verfahren + catálogo de Suffixe derivacionais (com Genus + Wortart-Resultat + produtividade) + Strukturklassen-Komposita + Diagnostik-Pipeline em [ANHANG I — Wortbildung](../00-meta/anhaenge/ANHANG-I-WORTBILDUNG.md). Esta seção apresenta o sistema; o Anhang é referência consultável.

## 1. Sprachliches Problem

Wortbildung é onde o alemão **expande infinitamente** seu léxico sem precisar de empréstimo. Falantes nativos formam Komposita ad hoc (`Donaudampfschiffahrtsgesellschaftskapitän, Schadenfreude-Empfänger, Kaffeemaschinenreparateur`) e o sistema os interpreta sem hesitação.

Aprendizes adultos travam em:

- **Reconhecer fronteiras** em Komposita longos (sem espaços!): *Geschwindigkeitsbegrenzung* = Geschwindigkeit + Begrenzung.
- **Atribuir Genus** a Komposita: regra é mecânica (último elemento determina), mas requer treino.
- **Aplicar Fugenelemente** corretamente: `-s-, -(e)n-, -e-, -er-, -ens-, -∅`. Distribuição parcialmente previsível, parcialmente lexicalizada.
- **Diferenciar prefixos derivacionais** (`be-, ge-, er-, ver-, zer-, ent-, miss-`) de prefixos verbais separáveis (cf. 01-03 §2.6).
- **Substantivar formações** corretamente: Inf. → das X; Adj. → das X (abstrato) ou der/die X (referente humano).
- **Interpretar Wortbildung filosófica** de Heidegger, Adorno, Sloterdijk: hyphenação, neologismos, re-etymologisierung. Sem este módulo, Stage 4-Hermeneutik não opera.

Sem este módulo:
- Você lê `Sein-zum-Tode` em Heidegger e perde 5 minutos tentando entender se é frase ou conceito.
- Você produz `*ein Kindergartenstuhl der grosse` em vez de `*ein großer Kindergartenstuhl` (Adj.flexion sobre o Determinatum).
- Você atribui Genus errado a Komposita (`*die Hausschuh` em vez de `der Hausschuh` — *Schuh* é m., não *Haus*).

---

## 2. Harte Theorie

### 2.1 Komposition — três tipos básicos

Komposition = combinação de duas (ou mais) **Lexeme** numa única palavra. Por **relação semântica** entre Determinans (modificador) e Determinatum (núcleo):

#### Determinativkompositum (default — relação modifier→head)

O Determinans **especifica/restringe** o Determinatum:

```
Apfelbaum    = um tipo de Baum (que dá Äpfel)
Tischlampe   = um tipo de Lampe (que está no Tisch)
Hauseingang  = um tipo de Eingang (do Haus)
Briefträger  = um tipo de Träger (de Briefe)
Wirtschaftskrise = uma Krise (da Wirtschaft)
```

Genus + Numerus + Klasse herdados do **Determinatum** (último elemento):
- `Apfelbaum` = m. (Baum é m.); Pl. *Apfelbäume* (Pl. de *Baum*).
- `Tischlampe` = f. (Lampe é f.); Pl. *Tischlampen*.
- `Schreibtisch` = m. (Tisch é m.); Pl. *Schreibtische*.

Ad-hoc-Komposita: falantes formam livremente; nem todos lexicalizados. *Frühlingsabendspaziergang* (passeio de noite de primavera) é compreensível sem lexicalização.

#### Kopulativkompositum (relação coordenativa)

Os elementos estão em **relação aditiva** (ambos contribuem igualmente):

```
Hosenrock    = Hose + Rock (peça que é hose e saia)
Strumpfhose  = Strumpf + Hose (meia-calça)
süßsauer     = süß + sauer (sabor agridoce)
schwarzweiß  = schwarz + weiß
deutsch-französisch (com hyphen)  = ambos
```

Klasse mais raro; típico de cores, sabores, materiais.

#### Possessivkompositum (Bahuvrihi — gehoben/literário)

O Kompositum não denota o Determinatum, mas algo **caracterizado** pelo Determinatum:

```
Rotkäppchen   = "menina caracterizada por chapeuzinho vermelho" (não um Käppchen!)
Großmaul      = "alguém com boca grande" (= fanfarrão; não uma boca!)
Langfinger    = "pessoa com dedos longos" (= ladrão)
Schwarzhaar   = (raro) "pessoa de cabelo preto"
```

Klasse parcialmente lexicalizada. Improdutivo em DE moderno (oposto ao sânscrito Bahuvrihi clássico). Aparece em apelidos, contos, gírias.

### 2.2 Komposita complexos (3+ elementos)

Princípio: **lê-se da direita para a esquerda**. O último elemento é Determinatum; tudo à esquerda é Determinans (que pode internamente ser composto).

```
Lebensversicherungsgesellschaft
= [[Lebens][Versicherungs]]gesellschaft
= Gesellschaft (núcleo: f., Pl. -en)
   ↑
   Versicherung (especifica que tipo de Gesellschaft)
   ↑
   Leben (especifica que tipo de Versicherung)

= "companhia de seguro de vida"
```

**Verschachtelung** sem limite teórico. Wortbildung produtiva em Bürokratendeutsch e Bildzeitungsschlagzeilen.

### 2.3 Fugenelemente — morfemas conectores

Entre os elementos, frequentemente aparece um **Fugenelement** (morfema vazio semanticamente, mas obrigatório/permitido morfologicamente):

| Fuge | Distribuição | Exemplos |
|---|---|---|
| **-s-** | após sufixos -ung, -heit, -keit, -schaft, -tum, -ling, -tät, -ität, -ion; em alguns m./n. lexicalizados | Wohnungsamt, Freiheitsraum, Wirklichkeitsverlust, Eigenschaftswort, Königtumsanspruch, Lehrlingsausbildung, Universitätsbibliothek |
| **-(e)n-** | após femininos em -e, e em N-Deklination | Frauenberuf, Studentenwohnung, Heldenstatue, Sonnenaufgang, Strahlenkrankheit |
| **-e-** | após alguns m. monossilábicos | Tagebuch, Hundeleine, Mausefalle, Hilfeleistung |
| **-er-** | residual: alguns Pl. fossilizados | Männerbund, Kindergarten, Bilderbuch, Hühnerei, Eierschale |
| **-ens-** | classe N-Dekl. com Gen. -ens | Herzensangelegenheit, Namensschild, Friedenspreis, Glaubensbekenntnis |
| **-∅** (zero) | default em muitos casos | Apfelbaum, Tischlampe, Hauseingang, Bierglas, Weinflasche |

Distribuição parcialmente regular (sufixo prediz Fuge), parcialmente lexicalizada. Memorização Anki + leitura intensiva.

### 2.4 Derivation — Präfixe + Suffixe

#### Suffixe nominais (cf. 01-04 §2.1 — sufixos com Genus mecânico)

Recapitulação dos mais produtivos:

| Sufixo | Genus | Categoria | Exemplos |
|---|---|---|---|
| -ung | f. | Substantivierung de Verb (Aktion) | Lösung, Hoffnung, Entwicklung, Bedeutung |
| -heit | f. | abstração a partir de Adj. simples | Freiheit, Schönheit, Wahrheit, Gesundheit |
| -keit | f. | abstração a partir de Adj. derivado em -ig/-lich/-bar | Möglichkeit, Höflichkeit, Schwierigkeit |
| -schaft | f. | coletivo / qualidade | Wissenschaft, Freundschaft, Mannschaft, Bereitschaft |
| -tum | n. | coletivo / abstração | Eigentum, Christentum, Königtum, Beamtentum |
| -nis | n./f. | abstração / resultado | Geheimnis (n.), Erkenntnis (f.), Verständnis (n.), Zeugnis (n.) |
| -ling | m. | pessoa caracterizada | Lehrling, Frühling, Schmetterling, Säugling |
| -er | m. | Nomen agentis | Lehrer, Spieler, Schreiber |
| -in | f. | feminização a partir de m. | Lehrerin, Studentin, Doktorin (Pl. -innen) |
| -chen, -lein | n. | Diminutiv | Mädchen, Häuschen, Bübchen, Brüderlein, Fräulein |

#### Suffixe adjetivais

| Sufixo | Categoria | Exemplos |
|---|---|---|
| -ig | qualidade | hügelig, durstig, mutig, geistig |
| -lich | qualidade / atributo | freundlich, möglich, persönlich, rechtlich |
| -isch | adjektivo de origem/povo/Adj. de N. | praktisch, dialektisch, kindisch, deutsch, italienisch |
| -bar | possibilidade passiva ("X-able") | lesbar, machbar, erreichbar, verfügbar |
| -sam | tendência / disposição | achtsam, sparsam, tugendhaft, wirksam |
| -haft | natureza / propriedade | tugendhaft, krankhaft, vorbildhaft |
| -los | privação | hilflos, hoffnungslos, sinnlos |
| -voll | abundância | hoffnungsvoll, sinnvoll, mühevoll |
| -reich | "rico em" | erfolgreich, lehrreich, einflussreich |
| -frei | "livre de" | rauchfrei, fehlerfrei, schmerzfrei |

#### Präfixe verbais (cf. 01-03 §2.6)

Untrennbar (átonos): `be-, ge-, er-, ver-, zer-, ent-, emp-, miss-`.
Trennbar (tônicos): `auf-, ab-, an-, aus-, bei-, ein-, mit-, nach-, vor-, weg-, zu-, ...`.
Ambivalente (6): `durch-, über-, unter-, um-, wider-, wieder-`.

Função semântica dos untrennbaren mais produtivos:

| Präfix | Função semântica | Exemplos |
|---|---|---|
| **be-** | transitivisierung; movimento sobre superfície | bedenken, befahren, besitzen, beschreiben |
| **er-** | Vollendung; Resultat | erfahren, erleben, ertragen, erblühen |
| **ver-** | mudança radical; perda; intensificação | verstehen, vergessen, verlieren, verändern |
| **zer-** | destruição / fragmentação | zerbrechen, zerstören, zerreissen |
| **ent-** | remoção; início | entfernen, entdecken, entstehen, entlassen |
| **miss-** | erro; desvio | missverstehen, missachten, misslingen |

#### Präfixe nominais

| Präfix | Função | Exemplos |
|---|---|---|
| **un-** | negação | Unmöglichkeit, Unsicherheit, Unmensch |
| **ur-** | original / primitivo | Ursprung, Urvater, Ursache, Urlaub |
| **erz-** | intensificação (gehoben) | Erzbischof, Erzfeind |
| **miss-** | erro | Missverständnis, Missachtung |
| **un-** | + Adj. | unmöglich, unsicher, unfreundlich |

### 2.5 Konversion — substituição categorial sem afixo

#### Verb-Inf. → Substantiv (Neutrum)

```
lesen → das Lesen
schreiben → das Schreiben
sterben → das Sterben (Heidegger-tema)
hervorgehen → das Hervorgehen
```

Sistemático: **todo Inf. substantivado é Neutrum**. Genitiv = -s: *des Lesens, des Schreibens*. Pl. raro (use sufixo -ung em alternativa: *die Lesungen* em vez de *die Lesen*).

#### Adj. → Substantiv

Substantivierung de Adj. mantém **flexão de Adj.** (cf. 01-04 §2.5):
- Abstrato → n.: *das Schöne, das Wahre, das Gute, das Erhabene* (Kant), *das Eigentliche / Uneigentliche* (Heidegger).
- Referente humano → m./f.: *der Reiche, die Kranke, der Bekannte, der Angeklagte*.
- Referente humano genérico Pl. → m.f.Pl.: *die Deutschen, die Reichen, die Armen*.

#### Partizip → Substantiv

Particularmente produtivo em registro jurídico/político:

```
der Vorsitzende  (Part.Präs. de vorsitzen, "que preside")
der Studierende (Part.Präs.)
der Angeklagte (Part.II)
der Verstorbene (Part.II)
der Reisende (Part.Präs.)
```

Flexionam como Adj. substantivados (gemischt/schwach).

### 2.6 Confixe (Wortbildungselemente prä-/sufixoides)

Elementos limítrofes entre raiz e prefixo, frequentemente de origem grega/latina, produtivos em terminologia técnica:

| Confix | Posição | Significado | Exemplos |
|---|---|---|---|
| **bio-** | prefixoide | vida | Biologie, Biograph, Biotop |
| **geo-** | prefixoide | terra | Geologie, Geographie, Geophysik |
| **tele-** | prefixoide | distância | Telephon, Telegraphie, Television |
| **auto-** | prefixoide | próprio / automático | Autobiographie, Automatik, Autorität (lat.) |
| **mikro-/makro-** | prefixoide | pequeno/grande | Mikroskop, Makrokosmos |
| **anti-** | prefixoide | contra | Antibiotikum, antifaschistisch |
| **inter-** | prefixoide | entre | International, Interaktion |
| **trans-** | prefixoide | através | Transformation, Transport |
| **-logie** | sufixoide | ciência de | Biologie, Soziologie, Phänomenologie |
| **-graphie** | sufixoide | escrita / descrição | Geographie, Photographie, Bibliographie |
| **-skop** | sufixoide | observação | Mikroskop, Teleskop, Stethoskop |
| **-thek** | sufixoide | coleção | Bibliothek, Diskothek, Mediathek |

Em Wissenschaftsdeutsch e em terminologia técnica, Konfixe atravessam o léxico. **Reconhecimento etimológico** (grego/latino) é parte do Stage 4 (módulos 04-01 / 04-02).

### 2.7 Heideggers Wortbildung — caso paradigmático

Heidegger é o mestre da **Wortbildung filosófica** em DE moderno. Estratégias documentadas:

#### Hyphenierung de Phrasen

Toda phrase substantivada como conceito único, com hyphens:

```
das In-der-Welt-sein         (= ser-no-mundo)
das Sein-zum-Tode            (= ser-para-a-morte)
das Mit-sein                 (= ser-com)
das Sich-zeigen              (= mostrar-se a si)
das Vor-laufen               (= correr-adiante; Vorlaufen)
das An-sich-halten           (= conter-se)
```

Núcleo categorizador é o último elemento — em todos esses, é Inf. substantivado em -en, logo **Neutrum, Sg.** (Pl. raro). Genitiv: `des In-der-Welt-seins`.

#### Re-etymologisierung

Heidegger explora a **etymologia** dos termos para reativar significados arcaicos:

```
Wahrheit ← gr. ἀ-λήθεια (a-letheia, "des-velamento") 
   → Heidegger: "Unverborgenheit" (= não-encobrimento)

Logos ← gr. λέγειν (legein, "colher, reunir, dizer") 
   → Heidegger: "das Sagen, das Versammeln"

Phänomen ← gr. φαίνεσθαι (phainesthai, "mostrar-se") 
   → Heidegger: "das Sich-zeigen"
```

Esta estratégia transforma cada conceito em Wortbildung-Operation. O texto torna-se sequência de **Begriffsmaschinen** que se montam diante do leitor.

#### Komposita filosóficos novos

```
das Geviert (= "o Quaternal" — Erde, Himmel, Götter, Sterbliche)
das Gestell (= "armação" — modo do desvelamento técnico)
die Lichtung (← Lichten) (= "clareira" — onde o Ser se desvela)
das Da-sein (= ser-aí — não confundir com Substantiv comum Dasein)
```

#### Negações e In-Präfixe

```
das Un-Heimliche       (Un + heimlich, com hyphen para enfatizar tensão)
das Un-Verborgene      (Un + Verborgen)
das Nicht-Mehr-Sein    (Phrase substantivada)
```

A leitura de Heidegger é, em larga medida, **leitura morfo-sintática de Wortbildung**. Sem este módulo + 04-02 Etymologie + 04-10 Hermeneutik, não opera.

### 2.8 Diagnóstico — pipeline de análise de Kompositum

Aplicar, dado um Kompositum:

1. **Identificar fronteiras morfológicas**: leitura silábica + busca por Fugenelemente (`-s-, -(e)n-, -e-, -er-, -ens-`).
2. **Ler da direita para a esquerda**: último elemento = Determinatum. Aplica Genus + Numerus + Klasse.
3. **Identificar tipo**: Determinativ (default), Kopulativ (coordenativo), Possessiv (Bahuvrihi).
4. **Para cada Determinans**, recursivamente: é simples ou interno-composto?
5. **Para sufixos finais**, identificar Genus mecânico (-ung→f., -keit→f., -tum→n., etc.).
6. **Para prefixos**, identificar Klasse (untrennbar/trennbar/ambivalent).
7. **Para hyphen-Komposita** (Heidegger): identificar Phrase como NP única; Determinatum é o último elemento.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**, consegue:

1. Diferenciar **3 tipos de Komposita** (Determinativ, Kopulativ, Possessiv) com 2 exemplos próprios cada.
2. Identificar **Genus + Numerus + Plural** de 8 Komposita ad hoc novos via Determinatum.
3. Aplicar **Fugenelemente** corretamente: 5 Komposita com -s-, 3 com -(e)n-, 2 com -e-, 2 com -er- — todos com regra de uso justificada.
4. Listar **8 sufixos derivacionais** com Genus mecânico + Klasse de derivação.
5. Diferenciar **untrennbare, trennbare, ambivalente Präfixe** com diagnóstico operacional (acento + sentido literal/figurado).
6. Substantivar **3 Verben no Inf.**, **3 Adjektive abstractos**, **2 Partizipien** com flexão correta nos 4 Kasus.
7. Analisar **3 Komposita heideggerianos hyphenados** (`In-der-Welt-sein, Sein-zum-Tode, Mit-sein`) identificando Determinatum, Genus, Genitiv-Sg.
8. Decompor **`Donaudampfschiffahrtsgesellschaftskapitän`** em 6 elementos com Determinatum identificado.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Martin Heidegger — *Brief über den Humanismus*** (1947, abertura). Texto curto (~150 palavras), denso em Wortbildung-Estratégias.

> "Wir bedenken das Wesen des Handelns noch lange nicht entschieden genug. Man kennt das Handeln nur als das Bewirken einer Wirkung. Deren Wirklichkeit wird geschätzt nach ihrem Nutzen. Aber das Wesen des Handelns ist das Vollbringen. Vollbringen heißt: etwas in die Fülle seines Wesens entfalten, in diese hervorgeleiten, producere. Vollbringbar ist deshalb eigentlich nur das, was schon ist. Was aber vor allem 'ist', ist das Sein. Das Denken vollbringt den Bezug des Seins zum Wesen des Menschen. Es macht und bewirkt diesen Bezug nicht. Das Denken bringt ihn nur als das, was ihm selbst vom Sein übergeben ist, dem Sein dar."

(Edição canônica: *Wegmarken*, Vittorio Klostermann, GA Bd. 9.)

### Tarefa

Análise escrita, **800–1200 palavras** em PT-BR com terminologia DE intacta. Sem consultar.

1. **Inventário Wortbildung**: identificar **toda formação morfológica** complexa do trecho. Mínimo 20 itens. Para cada, classificar: Komposition (qual tipo?) / Derivation (qual sufixo? qual prefixo?) / Konversion (Verb-Inf., Adj., Part.?) / Phrase-Substantivierung (hyphenado?).
2. **Substantivierungen de Verb-Inf.**: o trecho tem várias (`Handeln, Bewirken, Vollbringen, Denken, Sein`). Identificar todas; classificar Genus + Genitiv-Sg.
3. **Sufixos com Genus mecânico**: `Wesen, Wirkung, Wirklichkeit, Nutzen, Bezug, Mensch`. Para cada, identificar sufixo derivacional ou estrutura morfológica e justificar Genus.
4. **Prefixe verbais**: `bedenken, bewirken, vollbringen, entfalten, hervorgeleiten, vergeben` (no fim). Para cada, classificar prefixo (untrennbar, trennbar, ambivalent) e justificar via §2.4.
5. **Heidegger-Wortbildung-Estratégias**: identificar momentos de:
   - Substantivierung de Inf. como termo filosófico (5+ ocorrências).
   - Re-etymologisierung (e.g., `producere` em latim — por que o autor insere?).
   - Composição hyphenada (não aparece no trecho, mas é o método; comparar com o que aparece).
6. **Análise sintática integrada**: aplicar 01-01 (Feldermodell) + 01-04 (Adjektivflexion) + este módulo simultaneamente em uma frase escolhida (e.g., *"Aber das Wesen des Handelns ist das Vollbringen"*).
7. **Comparação Heidegger vs. Kant**: Kant escreve nominal Stil com Genitivketten; Heidegger acrescenta hyphenação + re-etymologia + neologismo. Ambos são Wissenschaftsdeutsch hoch — onde divergem estilisticamente?

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-04 Nominalflexion** (prereq): sufixos com Genus mecânico foram introduzidos lá; aqui são tratados como mecanismos derivacionais.
- **01-03 Verbalsystem**: Trennbare/untrennbare Verben (cf. §2.6 do 01-03) é a face verbal da Wortbildung; aqui a face nominal e mista.
- **01-09 Grundwortschatz**: Anki cards devem ser **frasais**, não isoladas; e devem cobrir Komposita produtivos do Wissenschaftsdeutsch.
- **02-06 Funktionsverbgefüge**: FVG são forma de Wortbildung verbal-leve + nominalisada (`zur Sprache bringen, Anwendung finden`); pré-requisito direto.
- **03-01 Nominaler Stil**: a hipernominalização do Wissenschaftsdeutsch é Wortbildung em escala de texto.
- **04-01 Historische Linguistik**: muitos prefixos/sufixos são heranças do Idg./Ahd.
- **04-02 Etymologie**: re-etymologisierung como estratégia hermenêutica (Heidegger, Adorno, Sloterdijk).
- **04-10 Hermeneutik**: leitura de Heidegger é leitura de Wortbildung; este módulo é prerequisito direto.
- **PT comparativo**: PT tem Komposition pobre (`guarda-chuva, beija-flor`), produtividade restrita; DE expande indefinidamente. Calque PT→DE produz frases pesadas (`Versicherung des Lebens` em vez de `Lebensversicherung`).

---

## 6. Quellen

### Gramáticas

1. **Eisenberg, Bd. 1**, capítulos sobre Wortbildung (Komposition, Derivation, Konversion).
2. **Helbig/Buscha**, capítulo sobre Wortbildung.
3. **Fleischer, Wolfgang / Barz, Irmhild** — *Wortbildung der deutschen Gegenwartssprache*. 4. Aufl. De Gruyter, 2012. **A monografia canônica.**
4. **Donalies, Elke** — *Die Wortbildung des Deutschen: Ein Überblick*. Narr, 2005.
5. **Fuhrhop, Nanna / Peters, Jörg** — *Einführung in die Phonologie und Graphematik*. Metzler, 2013. (Para Fugenelemente.)

### Sobre Komposition

- **Donalies, Elke** — *Die Komposita-Bildung im Deutschen*. Narr, 2007.
- **Schlücker, Barbara** — *Die deutsche Kompositionsfreude*. De Gruyter, 2015.

### Sobre Heideggers Wortbildung

- **Pöggeler, Otto** — *Der Denkweg Martin Heideggers*. Neske, 1990. Capítulos sobre linguagem em Heidegger.
- **Heidegger, Martin** — *Unterwegs zur Sprache* (1959). GA Bd. 12. **Texto fundador onde Heidegger reflete sobre sua própria Wortbildung.**

### IDS-Grammis

- **https://grammis.ids-mannheim.de/** — buscar "Wortbildung", "Komposition", "Derivation", "Fugenelement".

### Texto primário

- **Heidegger, Martin** — *Brief über den Humanismus* (1947). In: *Wegmarken* (GA Bd. 9), Vittorio Klostermann, 1976.

---

**Próximo módulo:** [01-07 Negation und Modalpartikeln Grundlagen](01-07-negation-modalpartikeln.md), prereqs `01-01 + 01-03`.
