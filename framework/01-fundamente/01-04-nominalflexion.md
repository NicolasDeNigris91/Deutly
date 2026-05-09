---
module: 01-04
title: Nominalflexion — Genus, Numerus, Adjektivdeklination
stage: fundamente
prereqs: [01-02]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Por que 'das Mädchen' é Neutrum apesar de referir uma menina?"
    options:
      - "Erro lexicográfico do Duden."
      - "Genus gramatical é independente do sexo biológico. Sufixos derivacionais determinam Genus mecanicamente: -chen e -lein criam Diminutiva sempre Neutrum (das Mädchen, das Fräulein, das Bübchen, das Häuschen)."
      - "É arcaísmo lutherano."
      - "É variação dialetal."
    correct: 1
    explanation: "Sufixos diminutivos -chen e -lein convertem qualquer raiz em Neutrum, independentemente do sexo do referente. Outros sufixos com Genus mecânico: -ung (f.: die Lösung), -heit/-keit (f.: die Freiheit), -schaft (f.: die Wissenschaft), -tum (n.: das Eigentum), -nis (n. ou f., contexto), -er (m.: der Lehrer; mas die Mauer)."
  - q: "Em 'mit einem schönen alten roten Haus', por que '-en' nos três adjetivos?"
    options:
      - "Repetição estilística."
      - "Coordenação adjetival não-marcada."
      - "Após 'einem' (Det. carregando marca de caso Dat.Sg.n. = 'einem'), todos adjetivos atributivos seguintes seguem Adjektivflexion gemischte/schwache. Em Dat.Sg., a terminação é -en para todos os Genera."
      - "É erro frequente; norma seria '-em'."
    correct: 2
    explanation: "Adjetivflexion segue padrão: após Det. com marca clara de caso (der/dem/des), Adj. é schwach (-e ou -en); após 'ein/kein/mein' que tem casos com marca-zero (Nom.Sg.m./n., Akk.Sg.n.), Adj. é gemischt — completa a marca. Em Dat.Sg.n., 'einem' já marca; Adj. = schwach = -en. Múltiplos adjetivos coordenados sem 'und' tomam todos a mesma terminação."
  - q: "Qual o Plural de 'der Atlas, der Kaktus, der Index'?"
    options:
      - "die Atlasse, die Kaktusse, die Indexe"
      - "die Atlanten (geh.) / Atlasse (norm); die Kakteen (geh.) / Kaktusse (norm); die Indizes (Fach) / Indexe (norm)"
      - "Não têm Plural."
      - "Plural=Singular: die Atlas, die Kaktus, die Index"
    correct: 1
    explanation: "Substantivos de origem latina/grega podem manter Plural étimológico em registro técnico-acadêmico (Atlanten, Kakteen, Indizes, Lexika, Praktika, Tempora, Visa) e adotar Plural alemão regular em uso comum (Atlasse, Kaktusse, Indexe, Lexikons, Praktikums, Tempen, Visums). Wissenschaftsdeutsch prefere o Plural étimológico; uso geral admite ambos."
  - q: "Como se forma o Plural de 'der Mann, das Buch, die Frau, der Junge, das Mädchen, der Vater'?"
    options:
      - "Sempre com -e ou -en."
      - "Cinco padrões: -e (Tag→Tage), -er+Umlaut (Buch→Bücher), -(e)n (Frau→Frauen, Junge→Jungen), -∅+Umlaut (Vater→Väter), -∅ (Mädchen→Mädchen). Distribui-se por Genus + estrutura silábica + sufixo."
      - "É arbitrário; cada palavra tem padrão único."
      - "-s para todos os modernos."
    correct: 1
    explanation: "Plural alemão tem 5 padrões principais: -e (com/sem Umlaut: Tag-Tage, Hand-Hände), -er (com Umlaut em raízes Vokal: Buch-Bücher, Mann-Männer), -(e)n (femininos -e/-er, e N-Dekl.: Frau-Frauen, Junge-Jungen), -∅ (com/sem Umlaut: Vater-Väter, Lehrer-Lehrer), -s (estrangeirismos: Auto-Autos, Hotel-Hotels). Distribuição é largamente previsível por Genus + estrutura."
  - q: "Em 'wegen schlechten Wetters', por que 'schlechten' (-en) e não 'schlechtes'?"
    options:
      - "Erro; norma seria 'schlechtes Wetter'."
      - "Após preposição com Gen.-Rektion sem Det., Adj. é stark e em Gen.Sg.m./n. termina em -en (não -es) — fenômeno conhecido como 'Endung -es vs -en' do Genitivs. Em Hochsprache moderna admite-se ambos com leve preferência por -en após Adj. mais palavra."
      - "É variação dialetal."
      - "Forma poética."
    correct: 1
    explanation: "Em Gen.Sg.m./n. starke Adjektivflexion sem Det., a terminação canônica é -en (não -es), porque o substantivo já carrega -es: 'wegen schlechten Wetters' (não *'wegen schlechtes Wetters'). Mesmo padrão: 'trotz starken Regens', 'voll bitteren Schmerzes'. Helbig/Buscha registra a regra; Duden tolera variação."
---

# 01-04, Nominalflexion — Genus, Numerus, Adjektivdeklination

## 1. Sprachliches Problem

A flexão nominal alemã é frequentemente apresentada como **caos memorizável**. Não é caos: é um sistema com 4 vetores entrelaçados (Kasus, Genus, Numerus, Determination) e 3 padrões de Adjektivflexion que se distribuem por **regra**.

Pontos onde aprendizes adultos travam:

- **Genus arbitrário**: `das Mädchen` (Neutrum, mas refere menina), `der Tisch` (Maskulin), `die Sonne` (Femininum) — a alocação parece aleatória. Mas há **regras semânticas + morfológicas + fonológicas** que cobrem ~80% dos substantivos. Os outros 20% são memorização.
- **Pluralbildung**: 5 padrões (`-e, -er, -(e)n, -∅, -s`) com Umlaut opcional — distribuição largamente previsível por Genus + estrutura silábica + sufixo derivacional.
- **Adjektivflexion**: as 3 séries (schwach, stark, gemischt) parecem 3 listas independentes; na verdade são **uma regra**: a marca de caso aparece **uma vez** — se o Det. já a carrega, Adj. minimaliza; se Det. não carrega ou está ausente, Adj. assume.
- **Irregular Genitiv-Markierung em starken Adj.** sem Det.: `wegen schlechten Wetters` (não `*schlechtes Wetters`) — exceção sistemática.

Sem este módulo:
- Você produz `*ein schöner alter rote Haus` (terminações inconsistentes) e cada falante nativo flagged em <1s.
- Você forma plurais por intuição PT/EN: `*die Manns, *die Buchs`.
- Você atribui Genus por critério semântico (`*der Mädchen`, `*die Tisch`) e desconhece os ~30 sufixos com Genus mecânico.

Este módulo organiza o sistema. Memorização lexical (Genus de cada substantivo individual) é Anki-Material — mas o **sistema** que torna a memorização inteligível é teoria.

---

## 2. Harte Theorie

> 📚 **Tabelas exhaustivas** dos 3 Padrões da Adjektivdeklination (schwach/stark/gemischt) × 4 Kasus × 4 Genus/Numerus em [ANHANG E — Adjektivdeklination](../00-meta/anhaenge/ANHANG-E-ADJEKTIVDEKLINATION.md). Esta seção apresenta a Logik; o Anhang é referência consultável.

### 2.1 Genus — três valores, alocação semi-previsível

DE distingue 3 Genera: **Maskulin** (m.), **Feminin** (f.), **Neutrum** (n.). O Genus é propriedade lexical do substantivo, marcada no Det.

#### Critérios semânticos (válidos para subset)

| Critério | Genus default | Exemplos | Exceções |
|---|---|---|---|
| Pessoas masculinas | m. | der Mann, der Vater, der Bruder, der Onkel, der Sohn | das Kind, das Mädchen (Diminutivos n.) |
| Pessoas femininas | f. | die Frau, die Mutter, die Schwester, die Tante, die Tochter | idem |
| Animais machos / fêmeas | m. / f. | der Hahn, die Henne; der Stier, die Kuh | espécies em si seguem outros critérios |
| Árvores | f. | die Eiche, die Buche, die Birke, die Tanne | der Ahorn, der Wacholder |
| Frutas | f. | die Birne, die Pflaume, die Kirsche, die Banane | der Apfel, das Pfirsich (Pl. die Pfirsiche) |
| Bebidas alcoólicas | m. | der Wein, der Schnaps, der Likör, der Whisky | das Bier (Neutrum!) |
| Dias, meses, estações | m. | der Montag, der Mai, der Sommer | das Frühjahr |
| Números | f. | die Eins, die Million, die Milliarde | — |
| Pontos cardeais, ventos, precipitação | m. | der Norden, der Wind, der Regen, der Schnee | — |
| Metais | n. | das Gold, das Silber, das Eisen, das Kupfer | der Stahl |

#### Critérios morfológicos (sufixos derivacionais — alocação **mecânica**)

| Sufixo | Genus | Exemplos |
|---|---|---|
| **-ung** | f. | die Lösung, die Endung, die Wohnung, die Bedeutung, die Erfahrung |
| **-heit, -keit** | f. | die Freiheit, die Schönheit, die Möglichkeit, die Höflichkeit |
| **-schaft** | f. | die Wissenschaft, die Freundschaft, die Mannschaft, die Eigenschaft |
| **-ion, -tät, -ie, -ik** | f. | die Nation, die Universität, die Theorie, die Logik |
| **-anz, -enz, -ur, -ade, -age** | f. | die Distanz, die Existenz, die Kultur, die Limonade, die Etage |
| **-er** (Nomina agentis) | m. | der Lehrer, der Spieler, der Schreiber | (mas: die Mauer, die Steuer, die Mutter — exc. lexicalizadas) |
| **-ling** | m. | der Lehrling, der Frühling, der Schmetterling, der Säugling |
| **-or, -ist, -ent, -ant, -ar, -är** | m. | der Doktor, der Pianist, der Student, der Demokrat, der Kommissar, der Sekretär |
| **-ismus** | m. | der Kapitalismus, der Realismus, der Humanismus |
| **-chen, -lein** (Diminutiva) | n. | das Mädchen, das Häuschen, das Büchlein, das Brüderlein, das Fräulein |
| **-tum** | n. | das Eigentum, das Königtum, das Christentum, das Beamtentum (mas: der Reichtum, der Irrtum — exc. lexicalizadas) |
| **-nis** | n. ou f. | das Geheimnis, das Erlebnis (n.); die Erkenntnis, die Finsternis (f.) — distribuição lexicalizada |
| **-(s)el** | n. | das Rätsel, das Mittel, das Übel |
| **-ment** | n. | das Element, das Argument, das Dokument, das Instrument |
| **-ma** | n. | das Thema, das Drama, das Problem, das Klima |
| **Substantivierung de Verbinfinitiv** | n. | das Lesen, das Singen, das Schwimmen |
| **Substantivierung de Adj./Part.** | n. (abstrato) ou m./f. (referente humano) | das Schöne, das Wesentliche; der Reiche, die Kranke |

#### Critérios fonológicos (residuais, baixa cobertura)

- Monossílabos masculinos com vogal final fechada tendem a m. (`der Mann, der Sohn`).
- Substantivos em `-e` átono são frequentemente f. (`die Sonne, die Liebe, die Erde, die Lampe`) — mas há exceções m. da N-Dekl. (`der Junge, der Bote, der Russe`) e n. (`das Auge, das Ende`).

#### Cobertura

Os critérios semânticos + morfológicos cobrem ~80% dos substantivos. Os ~20% restantes são lexicalmente marcados — **memorização Anki obrigatória**, sempre **com artigo**: nunca aprenda `Tisch` isolado, sempre `der Tisch`.

### 2.2 Numerus — Pluralbildung em 5 padrões

| Padrão | Marcação | Genus tendencial | Exemplos | Anti-exemplos |
|---|---|---|---|---|
| **-e** | sufixo `-e`, com ou sem Umlaut | m. e n. monossilábicos | der Tag → Tage; der Tisch → Tische; der Hund → Hunde; das Brot → Brote; **com Umlaut**: die Hand → Hände; die Wand → Wände; der Sohn → Söhne; der Stuhl → Stühle | — |
| **-er** | sufixo `-er`, **sempre com Umlaut** se possível | n. monossilábicos majoritariamente | das Buch → Bücher; das Haus → Häuser; das Kind → Kinder; das Land → Länder; der Mann → Männer; der Wald → Wälder | — |
| **-(e)n** | sufixo `-en` ou `-n` | f. (default amplo); N-Dekl. m.; alguns n. | die Frau → Frauen; die Schwester → Schwestern; die Tante → Tanten; die Universität → Universitäten; der Junge → Jungen; der Mensch → Menschen; das Hemd → Hemden; das Bett → Betten | — |
| **-∅** (zero, com ou sem Umlaut) | sem sufixo | m. e n. com sufixo `-er, -el, -en` | der Lehrer → Lehrer; der Onkel → Onkel; das Zeichen → Zeichen; **com Umlaut**: der Vater → Väter; der Bruder → Brüder; die Mutter → Mütter; die Tochter → Töchter (femininos -er restritos!) | — |
| **-s** | sufixo `-s` | estrangeirismos, abreviaturas, neologismos | das Auto → Autos; das Hotel → Hotels; der Park → Parks; der Lkw → Lkws; das Foto → Fotos; das Kino → Kinos | — |

#### Distribuição condicionada por sufixo

| Sufixo | Plural |
|---|---|
| -ung, -heit, -keit, -schaft, -ion, -ität, -ie | -en |
| -chen, -lein (Diminutiva) | -∅ |
| -er, -el, -en (Mas./Neutr.) | -∅ (com Umlaut quando possível em m.) |
| -ling | -e |
| -nis | -se (sufixo de marca: Geheimnis → Geheimnisse) |
| -tum | -tümer (Umlaut) |
| -ist, -ent, -ant, -or | -en (N-Dekl.) |

#### Pluralia étimológicos (registro Wissenschaftsdeutsch)

| Sg. (lat./gr.) | Pl. étimológico (gehoben) | Pl. germanizado (norm) |
|---|---|---|
| das Lexikon | die Lexika | die Lexikons |
| das Praktikum | die Praktika | (raro) |
| das Visum | die Visa | die Visen |
| der Atlas | die Atlanten (gehoben) | die Atlasse |
| der Kaktus | die Kakteen (Botanik) | die Kaktusse |
| der Index | die Indizes (Fach) | die Indexe |
| das Tempus | die Tempora (Linguistik) | die Tempen (raro) |
| das Drama | die Dramen | (raro) |
| das Forum | die Foren / Fora (gehoben) | — |
| das Datum | die Daten | — |

Em Aufsatz acadêmico, use Plural étimológico. Em texto comum, germanizado.

### 2.3 Adjektivflexion — 3 padrões via UMA regra

Adjetivos atributivos (i.e., **antepostos** ao substantivo: `der schöne Mann`) são flexionados. Adjetivos predicativos (`Der Mann ist schön`) são **invariantes**.

A flexão atributiva tem 3 padrões nominalmente, mas **uma única regra subjacente**:

> **A marca de caso aparece UMA vez.** Se o Det. carrega marca clara, Adj. minimaliza (schwach). Se Det. não marca ou está ausente, Adj. assume a marca (stark). Se Det. é parcial (ein-/kein-/mein-), Adj. complementa o que falta (gemischt).

#### Schwach — após Det. com marca

Det. canônico: `der, die, das, dieser, jener, jeder, mancher, welcher, solcher, derjenige, derselbe`.

| Caso | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| Nom. | der gut**e** Mann | die gut**e** Frau | das gut**e** Kind | die gut**en** Leute |
| Akk. | den gut**en** Mann | die gut**e** Frau | das gut**e** Kind | die gut**en** Leute |
| Dat. | dem gut**en** Mann | der gut**en** Frau | dem gut**en** Kind | den gut**en** Leuten |
| Gen. | des gut**en** Mannes | der gut**en** Frau | des gut**en** Kindes | der gut**en** Leute |

**Padrão**: 5 formas em `-e` (Nom.Sg. todos + Akk.Sg.f./n.) e o resto em `-en`.

#### Stark — sem Det. (ou após Det. sem marca: `viel, manch, etwas`)

| Caso | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| Nom. | gut**er** Wein | gut**e** Suppe | gut**es** Brot | gut**e** Leute |
| Akk. | gut**en** Wein | gut**e** Suppe | gut**es** Brot | gut**e** Leute |
| Dat. | gut**em** Wein | gut**er** Suppe | gut**em** Brot | gut**en** Leuten |
| Gen. | gut**en** Weines | gut**er** Suppe | gut**en** Brotes | gut**er** Leute |

**Padrão**: Adj. carrega exatamente as terminações que o Det. teria (compare com tabela do Det. em 01-02 §2.2): `-er, -e, -es, -em, -er, -em, -en/-er` etc. **Exceção: Gen.Sg.m./n.** = `-en` (não `-es`), porque o substantivo já marca com `-(e)s`.

#### Gemischt — após `ein, kein, mein, dein, sein, ihr, unser, euer`

Det. parcial: `ein` (e mein-, kein-, etc.) tem **forma-zero** em Nom.Sg.m., Nom.Sg.n., Akk.Sg.n. Nessas posições, Adj. assume marca starke; nas demais, schwach.

| Caso | Sg.m. | Sg.f. | Sg.n. | Pl. (= mit kein-) |
|---|---|---|---|---|
| Nom. | ein gut**er** Mann | eine gut**e** Frau | ein gut**es** Kind | keine gut**en** Leute |
| Akk. | einen gut**en** Mann | eine gut**e** Frau | ein gut**es** Kind | keine gut**en** Leute |
| Dat. | einem gut**en** Mann | einer gut**en** Frau | einem gut**en** Kind | keinen gut**en** Leuten |
| Gen. | eines gut**en** Mannes | einer gut**en** Frau | eines gut**en** Kindes | keiner gut**en** Leute |

**Padrão**: nas 3 células onde `ein` é zero (Nom.Sg.m., Nom.Sg.n., Akk.Sg.n.), Adj. = `-er, -es, -es` (starke). Em todas as demais, Adj. = `-e` ou `-en` (schwache).

#### Adjetivos coordenados sem `und`

Múltiplos adjetivos atributivos em série tomam **todos a mesma terminação**:

```
der schöne alte rote Wagen      (Nom.Sg.m.: schwach -e)
einen schönen alten roten Wagen (Akk.Sg.m.: gemischt → -en + schwach -en)
mit einem schönen alten roten Wagen (Dat.Sg.m.: gemischt -en)
```

Nada de `*einen schönen alter roter Wagen` ou variações.

### 2.4 Det. — paradigma completo

Tabela mestre do Det. (cf. 01-02 §2.2, expandida):

|  | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| **Nom.** | der | die | das | die |
| **Akk.** | den | die | das | die |
| **Dat.** | dem | der | dem | den (+ -n no N) |
| **Gen.** | des (+ -es no N) | der | des (+ -es no N) | der |

Mesmas terminações para: `dies-, jen-, jed-, manch-, welch-, solch-, derjenig-, derselb-`.

`ein-, kein-, mein-, dein-, sein-, ihr-, unser-, euer-` segue mesmo padrão **exceto** que tem **forma-zero** em Nom.Sg.m., Nom.Sg.n., Akk.Sg.n. (cf. tabela gemischt §2.3).

### 2.5 Substantivierte Adjektive

Adj. substantivado mantém **flexão de adjetivo** (não de substantivo).

```
ein Reicher ← reich + Substantivierung (= um homem rico)
eine Kranke ← krank (= uma mulher doente)
das Schöne ← schön (= o que é belo, abstrato)
die Deutschen ← deutsch (= os alemães, sob certo enquadramento)
ein Bekannter ← bekannt (= um conhecido [m.])
```

Flexão segue padrão schwach/stark/gemischt conforme o Det.

```
ein Reicher (Nom.Sg.m., gemischt)
des Reichen (Gen.Sg.m., gemischt)
einem Reichen (Dat.Sg.m., gemischt)
zwei Reiche (Pl., stark sem Det.)
die Reichen (Pl., schwach com Det.)
```

Casos famosos da literatura:
- `der Andere` (Levinas em DE) — Adj. substantivado.
- `das Erhabene` (Kant) — Adj. substantivado abstrato.
- `der Vorsitzende` — Partizip Präs. substantivado.
- `der Angeklagte` — Partizip II substantivado, jurídico.

### 2.6 Komposita — Genus e Plural

**Komposita herdam Genus do último elemento** (Determinatum):

```
der Tisch + die Lampe = die Tischlampe (f., Genus de Lampe)
das Auto + die Bahn = die Autobahn (f., Genus de Bahn)
der Wein + das Glas = das Weinglas (n., Genus de Glas)
die Hand + der Schuh = der Handschuh (m., Genus de Schuh)
```

Plural também segue o último elemento:

```
die Tischlampe → die Tischlampen
das Weinglas → die Weingläser
der Handschuh → die Handschuhe
```

Exceções: alguns Komposita lexicalizados perdem o Plural canônico do Determinatum (`die Wohnungen`, mas formação Komposita pode adotar `-bauten`).

### 2.7 N-Deklination revisitada (cf. 01-02 §2.3)

Em 01-02 a N-Dekl. foi introduzida do ponto de vista do Kasus. Aqui a vemos como **subsistema da Nominalflexion**:

| Sg. | Pl. |
|---|---|
| Nom. der Junge | die Jungen |
| Akk. den Junge**n** | die Jungen |
| Dat. dem Junge**n** | den Jungen |
| Gen. des Junge**n** | der Jungen |

Padrão: terminação `-(e)n` em **todas as células exceto Nom.Sg**. Sub-classe `-(e)ns` em Gen.Sg.: `der Name → des Namens`, `der Glaube → des Glaubens`, `der Wille → des Willens`.

### 2.8 Adjektivkomparation

Comparativo: Adj. + `-er` (com Umlaut em monossilábicos a/o/u → ä/ö/ü).

```
schön → schöner; klein → kleiner; alt → älter; groß → größer; jung → jünger
```

Superlativo: Adj. + `-st` (com Umlaut + e-Erweiterung após sibilante/dental).

```
schön → schönst; klein → kleinst; alt → ältest; groß → größt; heiß → heißest
```

Em uso atributivo, segue Adjektivflexion normal:

```
der schönere Mann (Komparativ + schwach Sg.m. Nom.)
der schönste Mann (Superlativ + schwach Sg.m. Nom.)
```

Em uso adverbial-predikativo: `am schönsten`.

```
Hans ist am schönsten.   (Hans é o mais belo)
Hans singt am schönsten. (Hans canta mais belamente)
```

Irreguläre Komparation:

| Adj. | Komp. | Superl. |
|---|---|---|
| gut | besser | am besten / der beste |
| viel | mehr | am meisten / die meisten |
| nah(e) | näher | am nächsten / der nächste |
| hoch | höher | am höchsten / der höchste |
| gern | lieber | am liebsten |

### 2.9 Diagnóstico — pipeline de Adjektivflexion

Aplicar **na ordem**:

1. **Adj. está atributivo (anteposto a substantivo)?** Se predicativo, **não flexiona**.
2. **Há Det. precedendo?**
   - Sim, com marca clara (`der, dieser, jeder, ...`) → schwach.
   - Sim, mas com forma-zero possível (`ein, kein, mein, ...`) → gemischt.
   - Não → stark.
3. **Identificar Kasus + Genus + Numerus.**
4. **Aplicar tabela** (§2.3 schwach/stark/gemischt).
5. **Múltiplos Adj.?** Mesma terminação para todos.
6. **Edge case Gen.Sg.m./n. starke**: `-en` em vez de `-es` (porque substantivo já marca).

Se 1–6 não converge, é forma fossilizada (`alle, viele, einige, manche` têm comportamento idiosincrático — verificar Helbig/Buscha).

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**, consegue:

1. Listar **8 sufixos com Genus mecânico** (4 femininos, 2 masculinos, 2 neutros) com 1 exemplo cada.
2. Atribuir Genus a 15 substantivos novos via combinação de regras semânticas + morfológicas + fonológicas; identificar quantos são lexicalmente marcados.
3. Formar **Plural** de 12 substantivos cobrindo os 5 padrões (`-e, -er, -(e)n, -∅, -s`), justificando a escolha por sufixo/Genus.
4. Diferenciar Plural étimológico vs. germanizado em 4 substantivos (`Lexikon, Atlas, Visum, Index`).
5. Aplicar Adjektivflexion (schwach/stark/gemischt) em **20 frases** cobrindo os 4 Kasus × 3 Genera × 2 Numera × 3 padrões — produção em folha em branco.
6. Explicar a **regra única subjacente** aos 3 padrões (a marca de caso aparece **uma vez**).
7. Resolver o **Gen.Sg.m./n. starke `-en`** com 4 exemplos (`wegen schlechten Wetters, trotz starken Regens, voll bitteren Schmerzes, statt teuren Geschenkes`).
8. Substantivar 3 adjetivos e flexioná-los nos 4 Kasus × Sg./Pl. com Det. variado.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Heinrich von Kleist — *Anekdote aus dem letzten preußischen Kriege*** (1810). Anedota completa, ~150 palavras. Texto-âncora canônico para Nominalflexion porque:
- Densidade alta de NPs com Det. + Adj. + N (cadeias modificadores).
- Mistura de Genera com modificações múltiplas.
- Genitivattribute em série (típico do registro narrativo militar do início do séc. XIX).
- Casos de N-Deklination explícitos (`der Soldat, der Husar, der Held`).

```
In einem bei Jena, während der Schlacht, in Brand geschossenen Dorf, wo,
wegen Mangels an Spritzen, das Feuer ungehemmt um sich griff, und alles 
mit dem Untergang bedroht war, stand, in einer Toreinfahrt, ein Husar, 
mit einem Spielbube, der ihm aus seiner Branntweinflasche zu trinken gab. 
Dem Husaren, der schon kreuz und quer einen Schluck genommen hatte, kam 
ein Zaudrer von einem dicken Bierwirt aus dem benachbarten Hause, mit 
einem Talern in der Hand und Schweiß auf der Stirn, gerannt; er sah ihn 
verdutzt an, und fragte: was er, in drei Teufels Namen, so vergnügt 
machen sollte, da das Haus über ihm in Flammen stehe? — "Was geht's 
mich an?" antwortete der Husar, indem er die Flasche vom Mund absetzte: 
"Möge die Welt, mit Verlaub, in Trümmer fallen!" — und nahm einen 
neuen Schluck.
```

(Versão modernizada na ortografia; original em Kleist, *Berliner Abendblätter* nº 13, 15.10.1810.)

### Tarefa

Análise escrita, **800–1200 palavras** em PT-BR com terminologia DE intacta. Sem consultar gramática durante a Aufgabe.

1. **Inventário NP**: identificar **toda NP atributivamente expandida** (i.e., com Det. + Adj. + N, ou Det. + N + Genitivattribut). Mínimo 12.
2. **Adjektivflexion**: para cada Adj. atributivo no trecho, classificar (schwach/stark/gemischt) e justificar via pipeline §2.9.
3. **Genus + Numerus**: para os 12+ substantivos identificados, atribuir Genus + Numerus + Kasus. Verificar Genus por critério morfológico/semântico/fonológico onde aplicável.
4. **N-Deklination**: identificar todas as ocorrências da N-Dekl. no trecho (`der Husar, der Soldat, der Bube...`) e marcar a flexão correta em cada caso.
5. **Genitivattribute**: o trecho tem alguns. Identificar e classificar (Possessivattribut, Partitivattribut, Subjektgenitiv?).
6. **Pluralbildung**: identificar Plurale no trecho (`Spritzen, Trümmer, Flammen, ...`) e classificar pelo padrão.
7. **Komposita**: identificar Komposita lexicais (`Branntweinflasche, Bierwirt, Toreinfahrt`) e marcar Genus + Plural — ambos herdados do Determinatum (último elemento).
8. **Stilistische Bemerkung**: o estilo de Kleist apresenta densidade adjetival e Genitivkonstruktion barrocas. Comparar com a clareza sintática de Kafka e a hipernominalização de Kant (cf. módulos anteriores).

Output esperado: prosa analítica densa, em PT-BR, com terminologia DE intacta. Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-02 Kasussystem** (prereq direto): Kasus marca-se em Det. + Adj. (mais que em N). Este módulo é a continuação morfológica de 01-02.
- **01-01 Syntaktische Analyse**: NPs habitam o Mittelfeld (e Vorfeld). A interna estrutura da NP é desenvolvida aqui.
- **01-05 Pronominalsystem**: pronomes seguem flexão paralela à do Det.; relação direta.
- **01-06 Wortbildung**: composição (último elemento determina Genus) e derivação (sufixos → Genus mecânico) — núcleo deste módulo.
- **02-01 Subordination**: Relativpronomen são pronomes flexionados em Kasus + Genus + Numerus — usa toda a tabela do Det. com pequenas variações.
- **02-04 Passivkonstruktionen**: Partizip II usado atributivamente é flexionado como Adj. (`das gelesene Buch`).
- **02-05 Infinitivsätze**: Substantivierung de Infinitiv → Neutrum (`das Lesen, das Schreiben`).
- **03-01 Nominaler Stil**: Adornos, Habermas e Wissenschaftsdeutsch em geral acumulam NPs com cadeias adjetivais densas; este módulo é o aparelho.
- **03-02 Register**: Plural étimológico (Lexika vs. Lexikons) é marcador de registro acadêmico.
- **04-04 Generative Syntax**: as 3 séries de Adjektivflexion são formalizáveis como **regras de concordância** (Agree) em uma gramática gerativa. Consequência: aprender o sistema descritivo daqui é prerequisito do gerativo lá.
- **PT comparativo**: PT marca apenas Numerus + Gênero no Adj. (e Numerus em Substantivo); DE marca Numerus + Gênero + **Kasus** + **Det.-Determination** simultaneamente. A complexidade morfológica é qualitativamente diferente.

---

## 6. Quellen

### Gramáticas canônicas

1. **Eisenberg, Peter** — *Grundriss der deutschen Grammatik*. Bd. 1 *Das Wort*, capítulos sobre Substantivflexion, Adjektivflexion, Wortbildung. **Referência teórica primária.**
2. **Helbig, Gerhard / Buscha, Joachim** — *Deutsche Grammatik*. Capítulos sobre "Genus", "Numerus", "Adjektivdeklination". Listas exaustivas.
3. **Engel, Ulrich** — *Deutsche Grammatik*. Iudicium, 2009. Tratamento dependencial.
4. **Duden, Bd. 4: Die Grammatik**. 9. Aufl. 2016. Tabelas de flexão; tratamento de pluralia étimológicos.
5. **Duden, Bd. 1: Die deutsche Rechtschreibung**. Para Plural-Variantes ortográficas.

### Sobre Genus

- **Köpcke, Klaus-Michael / Zubin, David** — "Sechs Prinzipien für die Genuszuweisung im Deutschen". *Die Sprache* 30 (1984), 26–50. **Estudo seminal sobre alocação semi-previsível de Genus.**
- **Köpcke, Klaus-Michael** — *Untersuchungen zum Genussystem der deutschen Gegenwartssprache*. Niemeyer, 1982.

### Sobre Adjektivflexion

- **Wegener, Heide** — *Die Nominalflexion des Deutschen — verstanden als Lerngegenstand*. Niemeyer, 1995.
- **Bittner, Andreas / Köpcke, Klaus-Michael** — *Adjektivische Flexion im Deutschen*. (Verschiedene Aufsätze.)

### Sobre Pluralbildung

- **Köpcke, Klaus-Michael** — *Untersuchungen zur Pluralbildung im Deutschen*. Stauffenburg, 1993. **Referência sobre os 5 padrões e sua distribuição.**
- **Wiese, Richard** — *The Phonology of German*. Oxford UP, 1996. (Capítulos sobre fonologia da flexão.)

### IDS-Grammis

- **https://grammis.ids-mannheim.de/** — buscar "Genus", "Numerus", "Pluralbildung", "Adjektivflexion", "Komposition".

### Texto primário do módulo

- **Kleist, Heinrich von** — *Anekdote aus dem letzten preußischen Kriege*. *Berliner Abendblätter* nº 13, 15.10.1810. 
   - Edição canônica: *Sämtliche Werke und Briefe*, Hg. Helmut Sembdner, dtv (Münchner Ausgabe).
   - Edição acessível: Reclam UB, *Anekdoten*.
   - Online: https://www.projekt-gutenberg.org/kleist/abendbl/abendbl.html

---

**Próximo módulo:** [01-05 Pronominalsystem](01-05-pronominalsystem.md), prereqs `01-02 + 01-04`.
