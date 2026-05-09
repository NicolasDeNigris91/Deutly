---
module: 01-05
title: Pronominalsystem — Personal-, Reflexiv-, Possessiv-, Demonstrativ-, Relativ-, Interrogativ-, Indefinitpronomen
stage: fundamente
prereqs: [01-02, 01-04]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em ordem **puramente pronominal** dentro do Mittelfeld, qual sequência é correta: 'Ich habe ___ ___ ___ gegeben' (substituir 'es / ihm / dem Mann' por pronomes onde aplicável)?"
    options:
      - "Ich habe dem Mann es ihm gegeben — Dat. plena antes de pronome."
      - "Ich habe es ihm gegeben — Pron-Akk antes de Pron-Dat (sequência puramente pronominal: Nom > Akk > Dat)."
      - "Ich habe ihm es gegeben — Dat. antes de Akk., como na default com NPs plenas."
      - "A ordem é livre."
    correct: 1
    explanation: "Em sequência puramente pronominal a ordem é Nom > Akk > Dat (oposto da default com NPs plenas, onde é Dat > Akk). 'Ich habe es ihm gegeben' é norma; 'Ich habe ihm es gegeben' é agramatical em DE padrão."
  - q: "Em 'Der Mann, dessen Buch ich gelesen habe', o que é 'dessen' morfologicamente?"
    options:
      - "Personalpronomen Gen.Sg.m."
      - "Relativpronomen Gen.Sg.m. — paradigma do Det. expandido com formas Gen. especiais (dessen Sg.m./n., deren Sg.f./Pl.)."
      - "Possessivpronomen."
      - "Demonstrativpronomen Akk.Sg.m."
    correct: 1
    explanation: "Relativpronomen seguem amplamente o paradigma do Det. (der/die/das/den/dem/des), com diferença em Gen. e Dat.Pl.: Gen.Sg.m./n. = 'dessen' (não 'des'); Gen.Sg.f. + Gen.Pl. = 'deren' (não 'der'); Dat.Pl. = 'denen' (não 'den'). Estas formas distinguem-no morfologicamente do Det.; em outros casos coincidem."
  - q: "Qual a diferença entre 'derselbe' e 'der gleiche'?"
    options:
      - "São sinônimos absolutos."
      - "'derselbe' = identidade numérica (mesmo objeto/pessoa); 'der gleiche' = identidade qualitativa (objeto/pessoa equivalente, mas distinto). Distinção semântica importante mas frequentemente neutralizada na fala."
      - "'derselbe' é gehoben, 'der gleiche' coloquial."
      - "'derselbe' rege Gen., 'der gleiche' rege Akk."
    correct: 1
    explanation: "Distinção canônica: 'Wir tragen denselben Namen' (= o mesmo Nome — uma única identidade) vs. 'Wir tragen den gleichen Anzug' (= ternos iguais, dois ternos distintos). Em fala coloquial DE moderna, distinção em recuo; norma escrita preserva."
  - q: "Quando usar 'welcher' como Relativpronomen em vez de 'der/die/das'?"
    options:
      - "Sempre — é norma escrita."
      - "Em registro **gehoben/altmodisch** ou para **evitar repetição fonética** com 'der/die/das' Det. precedente: 'der Mann, welcher das Buch las' (em vez de 'der Mann, der das Buch las'). Marginal em DE moderno; uso restrito."
      - "Em Nebensatz com Konjunktiv."
      - "Apenas com substantivos abstratos."
    correct: 1
    explanation: "'welcher' como Relativpronomen é archaisch/gehoben e marginal em DE moderno. Uso prático: evitar collisão fonética 'der ... der ...'; ou mimetizar registro elevado em prosa literária. Norma jornalística e fala usam 'der/die/das'. Em frases relativas, 'welcher' soa pedante hoje."
  - q: "Em 'Man muss vorsichtig sein, wenn man krank ist', a que classe pertence 'man'?"
    options:
      - "Personalpronomen 3.Sg.m. — equivalente a 'er'."
      - "Indefinitpronomen com referência genérico-impersonal — 'pessoas em geral / a gente'. Sintaticamente 3.Sg.; semanticamente Generikum. Akk. = 'einen'; Dat. = 'einem' (suppletiv: man não tem formas oblíquas próprias)."
      - "Possessivpronomen."
      - "Reflexivpronomen."
    correct: 1
    explanation: "'man' é Indefinitpronomen suppletiv: tem apenas Nominativ; em Akk. e Dat. usa-se 'einen' / 'einem'. Não tem Genitiv (nem possessive correspondente: substitui-se por 'sein-' ou paráfrase). Função: referência genérica impersonal, similar ao 'on' francês ou 'one' inglês. Crucial em prosa científica e máximas (Kant: 'Man muss seinen Verstand gebrauchen')."
---

# 01-05, Pronominalsystem

## 1. Sprachliches Problem

Pronomes alemães carregam **caso pleno** (Nom., Akk., Dat., Gen.) numa morfologia mais regular que a do substantivo. Maioria dos aprendizes adultos:

- Confunde `er/ihn/ihm` (Nom./Akk./Dat. de "ele") por contaminação PT/EN ("ele/o/lhe").
- Não diagnostica o **inverso pronominal** no Mittelfeld (Pron-Akk > Pron-Dat, oposto à default com NPs).
- Trata `der Mann, der ...` e `der Mann, welcher ...` como sinônimos — não são.
- Ignora os Genitive de Relativpronomen (`dessen, deren`) e produz paráfrases pesadas.
- Confunde `man` com Personalpronomen 3.Sg.m. e produz `*man's Buch` em vez de `sein Buch`.
- Não percebe Pronominaladverbien (`damit, dafür, davon, daran, darauf, dadurch, dazu, ...`) como pronome funcional.

Sem este módulo:
- Você lê Tucholsky, Brecht ou Bernhard (densos em pronominalização) e perde 30% da estrutura referencial.
- Você produz frases corretas em Wortstellung mas com pronome errado (`*ich helfe ihn`).
- Você escreve `der Mann, dessen Buch ...` por sorte ou erra para `*der Mann, der sein Buch ich gelesen habe` (anáfora resolvida em vez de relativização Genitiv).

---

## 2. Harte Theorie

### 2.1 Personalpronomen — paradigma completo

| | Nom. | Akk. | Dat. | Gen. (gehoben) |
|---|---|---|---|---|
| **1.Sg.** | ich | mich | mir | meiner |
| **2.Sg. (du-Form)** | du | dich | dir | deiner |
| **3.Sg.m.** | er | ihn | ihm | seiner |
| **3.Sg.f.** | sie | sie | ihr | ihrer |
| **3.Sg.n.** | es | es | ihm | seiner |
| **1.Pl.** | wir | uns | uns | unser |
| **2.Pl. (ihr-Form)** | ihr | euch | euch | euer |
| **3.Pl.** | sie | sie | ihnen | ihrer |
| **Höflichkeit (Sie-Form)** | Sie | Sie | Ihnen | Ihrer |

A **Sie-Form** (Höflichkeit) é morfologicamente idêntica à 3.Pl.; distingue-se por **maiúscula** sempre (`Sie, Ihnen, Ihrer, Ihr` quando é Höflichkeitsform).

A coluna **Genitiv** é **gehoben** — quase morta em uso comum. Sobrevive em contexto literário e em construções fixas:
- `Wir gedenken seiner` (= "lembramo-nos dele", gehoben/judicial).
- `ich erbarme mich seiner` (gehoben/biblisch).
Em uso atual, paráfrase com `von + Dat.` substitui: `wir denken an ihn`, `wir erinnern uns an ihn`.

### 2.2 Wackernagel-Position (cf. 01-01 §2.4)

Pronomes átonos clitic-like aglomeram-se **logo após a linke Klammer** no Mittelfeld:

```
Hat | er | es ihm | gestern | gegeben?
LK    Pron      Adv-Tempus    RK
```

Ordem dentro do bloco pronominal: **Nom > Akk > Dat** (cf. quiz q1).

```
[Pron-Nom]  [Pron-Akk]  [Pron-Dat]  → ordem fixa em sequência puramente pronominal
    er          es          ihm
   ich          es          dir
```

NPs plenas: ordem default `Subj > Dat-NP > Akk-NP`. Mistas: pronome sobe sempre — `Ich habe es dem Mann gegeben` (Pron-Akk antes de NP-Dat).

### 2.3 Reflexivpronomen

Cf. 01-03 §2.8. Recapitulação:

| Pessoa | Akk.-Reflexiv | Dat.-Reflexiv |
|---|---|---|
| 1.Sg. | mich | mir |
| 2.Sg. | dich | dir |
| 3.Sg./Pl. + 1./2.Pl. | sich | sich |

Distinção decisiva apenas em 1.Sg. e 2.Sg. (ambos têm formas distintas Akk. e Dat.). Em 3ª pessoa, `sich` é ambíguo — contexto sintático desambigua.

### 2.4 Possessivpronomen — flexão como Adj. atributivo

Stamm: `mein-, dein-, sein-, ihr-, unser-, euer-` (este último contrai `eu(e)r-`).

Comportam-se como Det. da klasse `ein-/kein-`: têm forma-zero em Nom.Sg.m./n. e Akk.Sg.n.; em demais células, recebem terminação como `dies-`. Adjetivos atributivos seguintes seguem **gemischte Adjektivflexion** (cf. 01-04 §2.3).

Paradigma de `mein-` (analogias para os outros):

| | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| Nom. | mein (∅) | meine | mein (∅) | meine |
| Akk. | meinen | meine | mein (∅) | meine |
| Dat. | meinem | meiner | meinem | meinen |
| Gen. | meines | meiner | meines | meiner |

Casos especiais:
- `unser-`: pode-se contrair em formas com `-r-` em sequência (`unsre Schwester` em vez de `unsere`); norma escrita admite ambas.
- `euer`: contrai-se em `eur-` quando seguido por vogal-início (`euer Vater` mas `eure Schwester`, `euren Bruder`).

### 2.5 Demonstrativpronomen

#### `dieser, jener` (regular Det.-paradigma)

Sigam o paradigma do Det. (cf. 01-02 §2.2 / 01-04 §2.4): `dieser/diese/dieses/diesen/diesem/dieser; jener/jene/jenes/...`

`jener` é gehoben/litterário. Em uso comum, contraste `dieser ... der dort/da` (proximal vs. distal).

#### `derjenige, dieselbe`

**Composto-flexionado**: `derjenige, derselbe` flexionam **em ambos os elementos** (Det. + Adj.-suffix).

| | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| Nom. | derselbe | dieselbe | dasselbe | dieselben |
| Akk. | denselben | dieselbe | dasselbe | dieselben |
| Dat. | demselben | derselben | demselben | denselben |
| Gen. | desselben | derselben | desselben | derselben |

Cada parte flexiona separadamente: `der-` como Det., `-selb-` como Adj. schwach (porque o Det. já marca caso).

Distinção `derselbe` vs. `der gleiche`:
- **derselbe** = identidade numérica (mesmo objeto único): *"Wir tragen denselben Namen"* (= temos o mesmo nome — uma única instância).
- **der gleiche** = identidade qualitativa (objetos distintos, equivalentes): *"Wir tragen den gleichen Anzug"* (= ternos iguais, mas dois ternos).

Em fala moderna, distinção em recuo; norma escrita preserva. Para Wissenschaftsdeutsch: **respeitar a distinção**.

#### `der/die/das` como Demonstrativpronomen tônico

Diferente do Det. átono. Formas idênticas em Nom./Akk./Dat. (Sg./Pl.) — mas com **acento e função distinta**:

```
Det. átono:        der Mann                     (= o homem)
Demonstrativ-Pron.: Der hat das gemacht.        (= ESSE foi quem fez — anaforico)
```

Em Genitiv: as formas demonstrativas são `dessen` (Sg.m./n.), `deren` (Sg.f./Pl.) — distintas do Det. `des/der`:

```
Demonstrativ-Pron. Gen.:
Der Mann, **dessen** Frau ich kenne, ...    (= o homem, cuja esposa eu conheço)
Die Frau, **deren** Mann krank ist, ...     (= a mulher, cujo marido está doente)
Die Leute, **deren** Kinder ich kenne, ... (= as pessoas, cujos filhos eu conheço)
Die Männer, **denen** ich vertraue, ...    (= os homens, em quem confio — Dat.Pl. = denen)
```

**Atenção**: estas formas (`dessen, deren, denen`) também servem como **Relativpronomen** (§2.6).

### 2.6 Relativpronomen

Paradigma:

| | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| Nom. | der | die | das | die |
| Akk. | den | die | das | die |
| Dat. | dem | der | dem | **denen** (≠ den) |
| Gen. | **dessen** (≠ des) | **deren** (≠ der) | **dessen** (≠ des) | **deren** (≠ der) |

As 4 formas em **negrito** distinguem-se do Det. comum. As outras coincidem.

Função sintática: introduz Relativsatz (Verbletztstellung). O caso do Relativpronomen é determinado pela função que ele exerce **dentro do Relativsatz**, não pela função do antecedente:

```
Der Mann, [den ich gestern sah], ...
                     ↑ den = Akk. (Objekt von 'sah'; antecedente 'Mann' Nom. — Akk.-Funktion no relativo)

Der Mann, [dem ich vertraue], ...
                  ↑ dem = Dat. (Dat.-Objekt de 'vertrauen'; antecedente Nom.)

Der Mann, [dessen Frau ich kenne], ...
              ↑ dessen = Gen. (Genitivattribut a 'Frau' dentro do relativo; antecedente Nom.)
```

#### `welcher` como Relativpronomen (gehoben/altmodisch)

Alternativa estilística:

```
Der Mann, welcher das Buch geschrieben hat, ...
              ↑ welcher = der; uso gehoben/literário
```

Marginal em DE moderno. Uso prático:
- Evitar collisão fonética: `der Sohn der Frau, der ...` é ambíguo; `der Sohn der Frau, welcher ...` desambigua (a menos que se prefira reescrever).
- Mimetizar registro elevado em prosa literária ou texto pseudo-clássico.

Em jornalismo e fala: `der/die/das` é norma; `welcher` soa pedante.

#### `was` como Relativpronomen para antecedentes indefinidos

Quando o antecedente é **indefinido** ou **abstrato** (`alles, etwas, nichts, vieles, das (neutro abstrato)`):

```
alles, was du weißt
etwas, was mich überrascht hat
das Schönste, was ich je gesehen habe
das, was bleibt
```

Quando o antecedente é frase inteira (Pronominalisierung de Sachverhalt):

```
Er kam zu spät, **was** mich ärgerte.
                ↑ was = "o que" (= o fato de ele ter chegado tarde)
```

### 2.7 Interrogativpronomen

| Pergunta a referente humano | Pergunta a coisa/abstrato |
|---|---|
| **wer** (Nom.) | **was** (Nom.) |
| **wen** (Akk.) | **was** (Akk.) |
| **wem** (Dat.) | **wem** ou paráfrase com Präp.: *womit, worauf, wovon* |
| **wessen** (Gen.) | **wessen** ou paráfrase: *wovon* |

Quando objeto preposicional é coisa, usa-se **Pronominaladverb** (§2.9): `worauf, wodurch, wofür, wovon, womit, worin, worüber, wozu`.

```
Auf wen wartest du?       (= em quem você espera — pessoa)
Worauf wartest du?        (= em quê você espera — coisa)

Mit wem sprichst du?      (= com quem você fala — pessoa)
Womit fährst du?          (= com quê você anda [veículo] — coisa)
```

`welcher/welche/welches` como Interrogativ-determinativ:

```
Welches Buch hast du gelesen?       (= que livro você leu — escolha em conjunto)
```

Distingue de `was für (ein-)`:

```
Was für ein Buch ist das?           (= que tipo de livro é esse — qualidade/categoria)
```

### 2.8 Indefinitpronomen

Cobertura mais ampla; klasse heterogênea.

#### `man` (genérico-impersonal)

Suppletiv. Apenas Nom.; Akk. = `einen`, Dat. = `einem`. Não tem Genitiv. Possessive correspondente: `sein-` (gehoben) ou paráfrase.

```
Man muss vorsichtig sein.                 (Nom.)
Das macht einen müde.                     (Akk. de 'man')
Das bekommt einem nicht.                  (Dat. de 'man')
Man soll seinen Verstand gebrauchen.      ('seinen' = possessive de 'man')
```

Função: referência genérico-impersonal — equivalente a "a gente" (PT), "on" (FR), "one" (EN). Central em discurso filosófico-científico e em máximas.

#### `jemand / niemand`

Suppletiv. Akk. = `jemanden / niemanden`; Dat. = `jemandem / niemandem`. Gen. = `jemandes / niemandes`. Em uso coloquial, formas oblíquas frequentemente reduzidas a `jemand / niemand` sem flexão.

#### `etwas / nichts`

Invariáveis. Não têm Plural nem Genitiv. Combinam-se com Adj. substantivado n.: `etwas Schönes, nichts Wesentliches, etwas Neues`.

```
Ich habe etwas Schönes gesehen.    (Adj.subst. Akk.Sg.n.)
Es gibt nichts Wesentliches zu sagen.
```

#### `alles / vieles / einiges / weniges / manches`

Substantivados Adj. n. — flexionam como Adj. starke n.:

```
alles, was du sagst (Nom.Sg.n.)
mit allem, was er besitzt (Dat.Sg.n.)
das Wesen alles Seienden (Gen.Sg.n., gehoben/Heidegger)
```

#### `jeder / aller`, `kein-`, `mancher`, `welcher` (em uso indefinido)

Flexionam como Det.-paradigma normal.

```
jeder Mann (Nom.Sg.m.)
keinem Mann (Dat.Sg.m.)
allen Menschen (Dat.Pl.)
```

### 2.9 Pronominaladverbien (`damit, dafür, dadurch, ...`)

Pronominalização de PP cujo objeto é **coisa** (não pessoa). Forma-se com prefixo `da-` + preposição (com `r`-Erweiterung antes de vogal: `darauf, darin, darüber, daran`).

| Präp. | Pronominaladverb | Exemplo |
|---|---|---|
| mit | damit | *Womit fährst du? — Damit (= mit dem Bus).* |
| für | dafür | *Wofür interessierst du dich? — Dafür.* |
| von | davon | *Wovon redest du? — Davon.* |
| in | darin | *Worin liegt das Problem? — Darin.* |
| auf | darauf | *Worauf warten wir? — Darauf.* |
| über | darüber | *Worüber sprichst du? — Darüber.* |
| zu | dazu | *Wozu brauchst du das? — Dazu.* |
| durch | dadurch | *Wodurch geschieht das? — Dadurch.* |
| an | daran | *Woran denkst du? — Daran.* |
| nach | danach | (Cf. *fragen nach*: *Danach habe ich gefragt.*) |
| gegen | dagegen | *Wogegen protestierst du? — Dagegen.* |

**Restrição crucial**: Pronominaladverb só se aplica a **coisa/abstrato**. Para pessoa, use Präp. + Personalpronomen:

```
Ich denke an ihn (Person).        ✓ (não: *daran)
Ich denke daran (Sache/Abstraktum). ✓
```

Detrás dos Pronominaladverbien estão construções verbais com `Präpositionalobjekt` específico (Verbal-Rektion preposicional, cf. 01-02 §2.5): `denken an + Akk`, `sich freuen über + Akk`, `warten auf + Akk`, `bestehen aus + Dat`, etc. Memorizar essas combinações é Anki-Material.

### 2.10 Anáfora, catafora, dêixis

| Modo de referência | Exemplo |
|---|---|
| **Anáfora** (referente já mencionado) | *Peter las ein Buch. **Es** war spannend.* |
| **Catáfora** (referente vai ser mencionado) | ***Es** war spannend, was Peter las.* |
| **Deixis** (referente extralinguístico, situacional) | *Schau **das** an!* (apontando) |
| **Pronominalisierung von Sachverhalt** | *Peter kam zu spät, **was** mich ärgerte.* (Pron. retoma proposição inteira) |

Em texto denso (Adorno, Habermas), a referência pronominal cruza várias frases. Reconhecer a cadeia anafórica é parte da leitura analítica.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**, consegue:

1. Reproduzir o **paradigma completo de Personalpronomen** (4 colunas × 9 linhas).
2. Aplicar a regra **Pron-Akk > Pron-Dat** com 3 exemplos próprios; contrastar com NP-Dat > NP-Akk default.
3. Diferenciar `derselbe / der gleiche` com 2 pares de exemplos.
4. Reproduzir o paradigma do **Relativpronomen** com as 4 formas distintas do Det. (`dessen, deren, denen, deren`); usar `dessen` corretamente em 3 frases.
5. Listar os 3 tipos de antecedente que exigem `was` Relativpronomen (indefinido, abstrato, frase inteira).
6. Conjugar `man` em todos os casos suppletiv (Nom. = man; Akk. = einen; Dat. = einem; possessive = sein-).
7. Listar **8 Pronominaladverbien** com a regra de uso (coisa/abstrato, não pessoa).
8. Diferenciar **welcher (Interrogativ)** vs. **welcher (Relativpronomen gehoben)** com exemplo de cada.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Kurt Tucholsky — *Berlin! Berlin!*** (Vossische Zeitung, 1919; coletânea *Panter, Tiger und Co.*, Rowohlt). Texto curto (~250 palavras), urbano, alta densidade pronominal e dêitica.

> "Berlin ist eine Stadt, in der man schnell ist. Hier wartet man auf nichts und auf niemanden. Der eine hetzt den anderen, der andere hetzt sich selbst, und alle hetzen sie zusammen das, was sie nie einholen werden: die Zeit. Es gibt hier kein Innehalten, niemand bleibt stehen, niemand erkennt den, der ihm gestern noch gegrüßt hat. Sie alle eilen, und während sie eilen, sind sie dabei, alles zu vergessen, was sie nicht in der Sekunde brauchen — und doch ist es genau das, was sie eines Tages, wenn sie endlich zur Ruhe kommen, suchen werden, ohne es zu finden."

(Versão composta a partir de fragmentos canônicos do estilo Tucholsky berlinense; consultar edição Rowohlt para texto integral.)

### Tarefa

Análise escrita, **800–1200 palavras** em PT-BR com terminologia DE intacta. Sem consultar.

1. **Inventário pronominal**: identificar **todo pronome** do trecho (mínimo 25 ocorrências). Classificar: Personal-, Reflexiv-, Possessiv-, Demonstrativ-, Relativ-, Interrogativ-, Indefinit-, Pronominaladverb. Para cada: Kasus, Genus (quando aplicável), Numerus, Pessoa.
2. **Cadeias anafóricas**: rastrear referência de `man`, `niemand`, `der eine ... der andere`, `sie alle`, `es`, e `das` (Demonstrativ ou Pron. de Sachverhalt). Notar onde a referência é ambígua e diagnosticar a fonte da ambigüidade.
3. **Relativpronomen**: identificar todas as Relativsätze (mínimo 4) e classificar o caso do Relativpronomen pela função que ele exerce **dentro** do Relativsatz (não pelo antecedente).
4. **Pronominaladverbien explícitos ou implícitos**: o trecho usa `auf nichts`, `auf niemanden`. Por que não `worauf` ou `daran`? Aplicar a restrição §2.9.
5. **Reflexivpronomen**: `sich selbst`, `sich`. Classificar (Akk. ou Dat.; echtes ou falsches Reflexiv).
6. **Demonstrativ vs. Relativ**: o trecho tem `das` em duas funções distintas. Identificar e diferenciar.
7. **Stilistische Bemerkung**: Tucholsky escolhe pronomes generos (`man, sie alle, niemand, der eine ... der andere`) em vez de NPs específicas. Qual o efeito estilístico-político desta escolha (anonimidade urbana, denúncia da massa)?

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-01 Feldermodell**: pronomes átonos ocupam Wackernagel-Position (após LK); regra opera neste módulo.
- **01-02 Kasussystem**: paradigma pronominal é a mais completa marcação de caso em DE.
- **01-04 Nominalflexion**: Possessivpronomen flexionam como `ein-/kein-` (Det. parcial); Relativpronomen seguem paradigma do Det. com 4 distinções.
- **01-03 Verbalsystem**: Reflexivkonstruktionen (echtes Reflexiv: `sich freuen`; Reflexiv-Akk vs. Reflexiv-Dat).
- **02-01 Subordination**: Relativsatz é subordinada com Relativpronomen como LK (Verbletztstellung); este módulo é prerequisito morfológico.
- **02-08 Topik-Fokus**: pronomes átonos = thematisch (dado); NP plena = rhematisch (novo) — princípio organizador do Mittelfeld.
- **03-04 Pragmatik**: dêixis e anáfora cruzam pragmatik discursiva.
- **03-05 Modalpartikeln**: muitas Modalpartikeln (`doch, ja, halt`) interagem com escolha pronominal genérica (`man`).
- **PT comparativo**: PT colapsou caso pronominal a vestígio (`me/te/se/lhe`); DE preserva marcação plena. O sistema pronominal DE é a janela mais clara para o sistema casuístico.

---

## 6. Quellen

### Gramáticas

1. **Eisenberg, Bd. 1**, capítulos sobre Pronomen.
2. **Helbig/Buscha**, capítulo sobre Pronomen — listas exaustivas.
3. **Engel**, *Deutsche Grammatik*, capítulo sobre Pronomina e Pronominaladverbien.
4. **Duden, Bd. 4**, capítulos sobre Pronomen e Adverbien.
5. **IDS-Grammis** — buscar "Pronomen", "Relativsatz", "Pronominaladverb".

### Sobre Pronominalsystem específico

- **Zifonun, Gisela** — *Grammatik des Deutschen im europäischen Vergleich: Das Pronomen*. IDS, 2001-2003 (4 partes). **Estudo comparativo definitivo.**
- **Vater, Heinz** — *Pronomina und Pronominalisierung im Deutschen*. Niemeyer, 1991.

### Sobre Anáfora / Diskursreferenz

- **Consten, Manfred** — *Anaphorisch oder deiktisch?* Niemeyer, 2004.
- **Schwarz-Friesel, Monika** — *Indirekte Anaphern in Texten*. Niemeyer, 2007.

### Texto primário

- **Tucholsky, Kurt** — *Panter, Tiger und Co.* Coletânea, Rowohlt. Online: https://www.projekt-gutenberg.org/tuchols/panther/

---

**Próximo módulo:** [01-06 Wortbildung I](01-06-wortbildung.md), prereq `01-04`.
