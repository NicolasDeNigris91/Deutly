---
module: 01-03
title: Verbalsystem I — Tempus, Konjugation, Trennbarkeit
stage: fundamente
prereqs: [01-01]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Em alemão coloquial do sul (Bayern, Österreich, Schweiz), 'Ich bin gestern ins Kino gegangen' é mais frequente que 'Ich ging gestern ins Kino'. Qual a melhor explicação?"
    options:
      - "O sul não conhece Präteritum."
      - "Distribuição sociolinguística: Präteritum é tempo da Schriftsprache e da narração escrita; Perfekt domina a fala. A Süd-Nord-Schiebung intensifica: na oralidade bávaro-austríaca, Präteritum é quase ausente exceto em 'sein', 'haben' e Modalverben."
      - "É erro coloquial; norma escrita exige Perfekt."
      - "Präterito alemão exige verbos modais."
    correct: 1
    explanation: "Em DE oral, o Perfekt domina; o Präteritum sobrevive na escrita literária e jornalística. A linha sul→norte intensifica o fenômeno: na fala bávara/austríaca, o Präteritum é quase ausente (exceto 'sein, haben' e Modalverben). Norma escrita preserva o Präteritum como tempo narrativo neutro (Märchen, Roman, Reportagem)."
  - q: "Em 'Er ist nach Berlin gefahren' vs 'Er hat das Auto gefahren', por que dois Hilfsverben distintos para o mesmo verbo 'fahren'?"
    options:
      - "Erro; ambas variantes existem por descuido normativo."
      - "Distribuição sintática-semântica: 'sein' para verbo de movimento intransitivo com mudança de localização ('fahren' direcional sem Akk.-Objekt); 'haben' para uso transitivo ('das Auto fahren' = conduzir o veículo)."
      - "É opcional, falante escolhe livremente."
      - "'sein' é norma escrita, 'haben' é fala."
    correct: 1
    explanation: "A escolha do Hilfsverbs depende da sintaxe-semântica do verbo na ocorrência específica. 'fahren' intransitivo direcional (mudança de lugar) → 'sein'; 'fahren' transitivo (com Akk.-Objekt: 'Auto fahren', 'Pferd fahren') → 'haben'. Outros verbos com idêntico comportamento dual: 'fliegen, schwimmen, segeln, reiten, rudern'."
  - q: "Em 'Sie hat den Brief geöffnet' vs 'Sie hat den Brief erhalten', por que 'geöffnet' tem ge- mas 'erhalten' não?"
    options:
      - "É fonologia regional, não regra sistemática."
      - "Prefixos átonos (be-, ge-, er-, ver-, zer-, ent-, emp-, miss-) são untrennbar e bloqueiam o 'ge-' do Partizip II; verbos sem prefixo átono levam 'ge-' regularmente."
      - "É regra ortográfica histórica."
      - "Erro: a forma correta seria 'geerhalten'."
    correct: 1
    explanation: "Prefixos verbais distinguem-se primeiramente pela acentuação. Tônicos = trennbar (auf-, ab-, ein-, mit-, vor-, weg-, hin-, her-, zu-, ...); átonos = untrennbar (be-, ge-, er-, ver-, zer-, ent-, emp-, miss-). O Partizip II de Verben mit untrennbarem Präfix nunca recebe 'ge-' (verstanden, vergessen, erkannt, bekommen — não *geverstanden, *gevergessen)."
  - q: "Por que 'denken → dachte → gedacht' é classificado como gemischt e não starke ou schwach?"
    options:
      - "Porque combina Vokalwechsel (Ablaut: e→a) com sufixo dental do schwachen Präteritums (-te)."
      - "Porque tem dois infinitivos."
      - "Porque é dialetal."
      - "Porque é Modalverb."
    correct: 0
    explanation: "Verben gemischter Konjugation combinam Ablaut (característico das starken) com o Dental-Suffix '-te' das schwachen no Präteritum. Lista canônica: bringen-brachte, denken-dachte, kennen-kannte, nennen-nannte, rennen-rannte, brennen-brannte, senden-sandte, wenden-wandte, wissen-wußte. Modalverben também: müssen-mußte, können-konnte, dürfen-durfte, wollen-wollte, sollen-sollte, mögen-mochte."
  - q: "Em 'durchqueren' vs 'durchstreichen', ambos com prefixo 'durch-', um é trennbar e outro untrennbar. Como diagnosticar?"
    options:
      - "É arbitrário."
      - "Prefixos ambivalentes (durch-, über-, unter-, um-, wider-, wieder-) seguem regra dupla: tônico = trennbar e sentido literal-espacial; átono = untrennbar e sentido figurado-abstrato. 'durchquéren' (átono) = atravessar metaforicamente → untrennbar; 'dúrchstreichen' (tônico, raro hoje) = riscar de cabo a rabo → trennbar."
      - "Depende da pessoa."
      - "Sempre são untrennbar."
    correct: 1
    explanation: "Os 6 prefixos ambivalentes (durch-, über-, unter-, um-, wider-, wieder-) admitem duas leituras: tônica + literal espacial = trennbar; átona + figurado/abstrato = untrennbar. Diagnóstico: pronúncia (acento) + significado. Pares clássicos: 'umfahren' (trennbar: derrubar atropelando) vs 'umfahren' (untrennbar: contornar); 'übersetzen' (trennbar: atravessar de barco) vs 'übersetzen' (untrennbar: traduzir)."
---

# 01-03, Verbalsystem I — Tempus, Konjugation, Trennbarkeit

## 1. Sprachliches Problem

O verbo é o **âncora estrutural** da frase alemã: forma a Verbalklammer (linke + rechte Satzklammer), distribui Kasus aos seus argumentos, e carrega 5 traços flexionais simultâneos (Person, Numerus, Tempus, Modus, Genus verbi).

Pontos onde aprendizes adultos travam reincidentemente:

- **Konjugationsklassen** parecem caos. Não são: o alemão tem **3 padrões sistemáticos** (stark, schwach, gemischt) + 4 verbos irregulares (sein, haben, werden, tun). As starken se distribuem por **7 Ablautreihen** historicamente preservadas.
- **Hilfsverb-Wahl** (haben vs. sein) parece arbitrária. Não é: distribui-se por critério sintático-semântico (telicidade + intransitividade direcional).
- **Trennbar vs. untrennbar** parece lista interminável. Não é: prefixos átonos = untrennbar; tônicos = trennbar; e os 6 ambivalentes seguem regra clara (literal/espacial vs. figurado/abstrato).
- **Tempusverteilung** Präteritum vs. Perfekt parece estilística. Não é: é **sociolinguística** com Süd-Nord-Schiebung documentada — Perfekt domina oralmente, Präteritum domina na escrita literária/jornalística.

Sem este módulo:
- Você produz `*Ich bin das Buch gelesen` (sein em vez de haben com transitivo) ou `*Ich habe nach Berlin gegangen` (haben em vez de sein com Bewegungsverb).
- Você lê *Der goldene Schlüssel* dos Grimm (Präteritum dominante) e tropeça em `lag, fand, grub, drehte` por não reconhecer as Ablautreihen.
- Você usa Perfekt em redação acadêmica onde Präteritum seria norma, ou Präteritum em fala coloquial soando livresco.

Este módulo organiza o sistema verbal em sua forma operacional. Konjunktiv I/II são adiados para 02-02/02-03 (precisam do Verbalsystem básico estabilizado primeiro).

---

## 2. Harte Theorie

### 2.1 O que uma forma verbal finita codifica

Uma única forma finita carrega **5 traços simultâneos**:

| Traço | Valores |
|---|---|
| **Person** | 1., 2., 3. |
| **Numerus** | Sg., Pl. |
| **Tempus** | Präsens, Präteritum, Perfekt, Plusquamperfekt, Futur I, Futur II |
| **Modus** | Indikativ, Konjunktiv I, Konjunktiv II, Imperativ |
| **Genus verbi** | Aktiv, Passiv (werden-Pass., sein-Pass.) |

Exemplo: `er hätte gelesen gehabt` codifica simultaneamente:
- Person 3., Numerus Sg., Tempus Plusquamperfekt (variant doppelte Perfekt-Bildung), Modus Konjunktiv II, Genus Aktiv.

A morfologia distribui esses traços entre verbo finito + Hilfsverben + Modalverben + Partikel `nicht`. Em `er hätte gelesen gehabt`: `hätte` carrega Person/Numerus/Modus; `gelesen` carrega Genus + Aspekt resultativo; `gehabt` é o auxiliar do duplo-Perfekt (gehoben/coloquial sul).

### 2.2 Konjugationsklassen — os 3 padrões sistemáticos + irregulares

#### Schwache Verben (regelmäßig)

Padrão: stem invariável + sufixo dental `-te-` no Präteritum + Partizip II em `ge-...-t`.

```
machen — machte — gemacht
kaufen — kaufte — gekauft
arbeiten — arbeitete — gearbeitet  (Erweiterung mit -e- após Stammausgang -t/-d)
hören — hörte — gehört
```

**Maioria absoluta dos verbos**. Default produtivo: novos verbos entram nesta klasse (`googeln → googelte → gegoogelt`).

#### Starke Verben (Ablaut-Vokalwechsel)

Padrão: **Vokalwechsel** (Ablaut) no Präteritum e/ou Partizip II + Partizip II em `ge-...-en`.

```
singen — sang — gesungen
nehmen — nahm — genommen
sehen — sah — gesehen
fahren — fuhr — gefahren
schreiben — schrieb — geschrieben
```

Distribuídos em **7 Ablautreihen** historicamente preservadas (§2.3).

#### Gemischte Verben (Mix de Ablaut + Dental-Suffix)

Padrão: Vokalwechsel + sufixo dental `-te-` no Präteritum + Partizip II em `ge-...-t`.

```
denken — dachte — gedacht
bringen — brachte — gebracht
kennen — kannte — gekannt
nennen — nannte — genannt
rennen — rannte — gerannt
brennen — brannte — gebrannt
senden — sandte — gesandt    (também schwach: sendete — gesendet, em sentido "transmitir")
wenden — wandte — gewandt    (também schwach: wendete — gewendet, em sentido "virar")
wissen — wußte — gewußt
```

**Modalverben pertencem à mesma klasse** morfologicamente (Vokalwechsel + Dental-Suffix):

```
können — konnte — gekonnt
müssen — mußte — gemußt
dürfen — durfte — gedurft
wollen — wollte — gewollt
sollen — sollte — gesollt
mögen — mochte — gemocht
```

#### Irreguläre (klasse fechada de 4)

```
sein  — war   — gewesen      (suppletiv: stems b- / s- / w-)
haben — hatte — gehabt       (kontrahiert: hab(e)-st, hab(e)-t, hatte = "habde")
werden — wurde — geworden     (irreg.: w-...-d-)
tun   — tat   — getan         (irreg.: tu-/ta-/-an)
```

São centrais como Vollverben e como Hilfsverben. Devem ser memorizadas com tabela completa.

### 2.3 As 7 Ablautreihen

A distribuição dos starke Verben em 7 classes é descendente do germânico (cf. Eisenberg Bd. 1; Stein 1991). Cada Reihe define o **padrão de Vokalwechsel** Inf. → Prät.Sg. → Part.II.

| Reihe | Ablaut Inf-Prät-Part | Verbos representativos | Sub-padrão |
|---|---|---|---|
| **I** | ei — ie — ie | bleiben—blieb—geblieben; schreiben—schrieb—geschrieben; treiben—trieb—getrieben | (Sub-Ia: ei—i—i: greifen—griff—gegriffen) |
| **II** | ie/ü — o — o | fliegen—flog—geflogen; ziehen—zog—gezogen; biegen—bog—gebogen; lügen—log—gelogen | — |
| **III** | i — a — u/o | singen—sang—gesungen; trinken—trank—getrunken; finden—fand—gefunden; helfen—half—geholfen; werfen—warf—geworfen | (Sub-IIIa: -nn/-mm/-ng: -u-; Sub-IIIb: -lf/-rf/-rb: -o-) |
| **IV** | e — a — o | nehmen—nahm—genommen; sprechen—sprach—gesprochen; brechen—brach—gebrochen; treffen—traf—getroffen | — |
| **V** | e/i — a — e | geben—gab—gegeben; sehen—sah—gesehen; lesen—las—gelesen; essen—aß—gegessen; sitzen—saß—gesessen | (e-Stamm; Part.II preserva -e-) |
| **VI** | a — u — a | fahren—fuhr—gefahren; tragen—trug—getragen; schlagen—schlug—geschlagen; waschen—wusch—gewaschen | — |
| **VII** | a/au/ei/o — ie — a/au/ei/o | fallen—fiel—gefallen; halten—hielt—gehalten; laufen—lief—gelaufen; heißen—hieß—geheißen; schlafen—schlief—geschlafen; rufen—rief—gerufen | (Reduplikation histórica; Part.II preserva vogal do Inf.) |

**Estratégia de aquisição**: não memorizar verbo-por-verbo. Memorizar **um representante por Reihe** + reconhecer padrão. Verbos novos starke (raros, mas existem em formação por composição: `aufschreiben, beschreiben`) entram na Reihe pelo Stamm.

Diagnóstico rápido: se o Vokal de Inf. é `ei`, é Reihe I; se é `i + nasal/líquida`, é Reihe III; se é `e` curto + cons., é Reihe IV ou V (V tem Part.II em `e`, IV em `o`).

### 2.4 Tempussystem — 6 Tempora

#### Bildung dos 6 Tempora (Aktiv)

| Tempus | Bildung | Exemplo (sehen st.) |
|---|---|---|
| **Präsens** | Stamm + Personalendung | ich sehe, du siehst, er sieht |
| **Präteritum** | Stamm-mit-Ablaut + Personalendung | ich sah, du sahst, er sah |
| **Perfekt** | Hilfsverb (haben/sein) Präs. + Partizip II | ich habe gesehen |
| **Plusquamperfekt** | Hilfsverb Prät. + Partizip II | ich hatte gesehen |
| **Futur I** | werden Präs. + Infinitiv | ich werde sehen |
| **Futur II** | werden Präs. + Partizip II + Infinitiv (haben/sein) | ich werde gesehen haben |

#### Distribuição funcional

| Tempus | Função primária | Função secundária |
|---|---|---|
| **Präsens** | tempo presente, default não-marcado | future com adverbial (`Morgen gehe ich ins Kino`); narrativo histórico (`Im Jahre 1789 marschiert eine Menge...`) |
| **Präteritum** | passado da escrita literária/jornalística (Märchen, Roman, Reportagem); auxiliar e modal na fala | — |
| **Perfekt** | passado da fala (default oral); resultativo (estado presente derivado de evento passado) | — |
| **Plusquamperfekt** | anterioridade dentro de narrativa em Präteritum/Perfekt | — |
| **Futur I** | futuro; **modal-epistemisch** (`Er wird (wohl) krank sein` = "deve estar doente") | promessa, vontade |
| **Futur II** | futuro perfectivo; epistemisch (`Er wird (wohl) angekommen sein` = "deve já ter chegado") | — |

**Süd-Nord-Schiebung** (escala de uso oral do Präteritum):

```
Norddeutschland:        Präteritum-Toleranz oral média
                        (Hamburg, Hannover: "ich ging" oral aceitável)
Mitteldeutschland:      Präteritum oral em recuo
                        (Frankfurt, Köln: misto)
Süddeutschland:         Präteritum oral quase extinto
                        (Bayern, BW: só sein/haben/Modalverben)
Österreich:             idem sul; Präteritum só na escrita
Schweiz:                Schweizerdeutsch sem Präteritum;
                        Schweizer Hochdeutsch (escrita) preserva
```

Em escrita acadêmica, Präteritum é norma; usar Perfekt em Aufsatz é Stilbruch.

### 2.5 Hilfsverben para Perfekt — distribuição haben vs. sein

#### sein (klasse delimitada)

```
1. Bewegungsverben mit Ortsänderung (intransitiv):
   gehen, kommen, fahren, fliegen, laufen, springen, fallen, steigen,
   reisen, ziehen (sich begeben), wandern, klettern, segeln, schwimmen
   (em sentido direcional)

2. Zustandswechsel-Verben (intransitiv):
   sterben, geboren werden, einschlafen, aufwachen, erfrieren, schmelzen,
   wachsen, vergehen, verschwinden, geschehen, passieren, gelingen, misslingen

3. Estados-Auxiliares irregulares:
   sein selbst (ich bin gewesen), bleiben (ich bin geblieben), 
   werden (ich bin geworden — Vollverb e Pass.-Auxil.)
```

#### haben (default)

Tudo o mais: transitivos, reflexivos, atelische intransitive (`schlafen, sitzen, liegen, stehen` no norte; em sul/Áustria, esses são `sein`-Verben — Plurizentrik).

#### Verbos com dupla classificação por sintaxe

| Verbo | sein | haben |
|---|---|---|
| fahren | intransitivo direcional: *Ich bin nach Berlin gefahren.* | transitivo: *Ich habe das Auto gefahren.* |
| fliegen | direcional: *Er ist nach Tokio geflogen.* | transitivo (pilotar): *Er hat den Hubschrauber geflogen.* |
| schwimmen | direcional: *Sie ist über den See geschwommen.* | atelisch: *Sie hat eine Stunde geschwommen.* (oral norte; sul: ist) |
| reiten | direcional: *Wir sind nach Hause geritten.* | transitivo (cavalo específico): *Er hat den Hengst geritten.* |
| schwimmen, segeln, rudern, tanzen | regional: norte tende `haben` para atelisch; sul/Áustria tende `sein` |

### 2.6 Trennbare vs. untrennbare Verben

Distinção fundamental: o **prefixo verbal**.

#### Untrennbare Präfixe (klasse fechada — átonos)

```
be-, ge-, er-, ver-, zer-, ent-, emp-, miss-
```

Comportamento sintático:
- **Nunca separa** — em V2/V1: `Ich verstehe das.` (Não: `*Ich stehe das ver`).
- **Partizip II sem `ge-`**: `verstanden, vergessen, erkannt, bekommen, entdeckt, mißlungen` (não `*geverstanden`).
- **Acentuação**: o prefixo é átono; acento principal cai no Stamm: ver-stéh-en, be-kómm-en.

#### Trennbare Präfixe (klasse aberta — tônicos)

```
ab-, an-, auf-, aus-, bei-, ein-, fort-, hin-, her-, los-, mit-, 
nach-, über-* (manchmal), um-* (manchmal), unter-* (manchmal), 
vor-, weg-, weiter-, zu-, zurück-, zusammen-
```

Comportamento sintático:
- **Separa em V2/V1**: prefixo vai pra rechte Klammer.
  ```
  Ich stehe um 7 Uhr auf.        (V2: prefixo → RK)
  Steh um 7 Uhr auf!             (V1 imperativo)
  ..., weil ich um 7 Uhr aufstehe. (VL: reúne)
  ```
- **Partizip II infixa `ge-`** entre prefixo e Stamm: `auf-ge-standen, mit-ge-bracht, ein-ge-stiegen`.
- **Acentuação**: prefixo é tônico — primary stress: **áuf**stehen, **éin**steigen, **mít**bringen.

#### Prefixos ambivalentes (klasse fechada de 6 — duplo padrão)

```
durch-, über-, unter-, um-, wider-, wieder-
```

Cada um pode ser **trennbar (tônico, sentido literal/espacial)** ou **untrennbar (átono, sentido figurado/abstrato)**:

| Verbo | Sentido literal (trennbar, tônico) | Sentido figurado (untrennbar, átono) |
|---|---|---|
| umfahren | `úmfahren` = derrubar atropelando: *Der LKW ist den Pfosten umgefahren.* | `umfáhren` = contornar, dar volta: *Wir haben die Stadt umfahren.* |
| übersetzen | `übersetzen` = atravessar de barco: *Der Fährmann hat uns übergesetzt.* | `übersétzen` = traduzir: *Sie hat das Buch übersetzt.* |
| umstellen | `úmstellen` = redistribuir, mudar: *Ich habe die Möbel umgestellt.* | `umstéllen` = cercar: *Die Polizei hat das Haus umstellt.* |
| durchschauen | `dúrchschauen` = olhar através de: *Schau die Liste durch!* | `durchscháuen` = perceber a verdade por trás: *Ich habe seinen Plan durchschaut.* |
| widerspiegeln | `wíderspiegeln` = refletir: *Der See spiegelt die Berge wider.* | `widerspíegeln` (raro, gehoben) | 
| wiederholen | `wíederholen` = trazer de volta: *Hol das Buch wieder!* | `wiederhólen` = repetir: *Wiederhol den Satz.* |

Diagnóstico operacional: **pronuncie**. Se o acento cai no prefixo, é trennbar. Se cai no Stamm, é untrennbar.

### 2.7 Modus — Indikativ e Imperativ (Konj. I/II → 02-02/02-03)

#### Indikativ

Default factual. Toda discussão acima foi em Indikativ.

#### Imperativ

Existe em 3 formas pessoais:

| Pessoa | Bildung | Exemplo |
|---|---|---|
| 2.Sg. (du) | Stamm-Endung-∅ (alt -e); manchmal Vokalwechsel em starken Verben da Reihe IV/V | Lies! / Sieh! / Nimm! / Geh! / Komm! |
| 2.Pl. (ihr) | 2.Pl. Indikativ Form sem Pron. | Lest! / Seht! / Nehmt! / Geht! |
| Höflichkeitsform (Sie) | 3.Pl. Indikativ Form + 'Sie' (postposto) | Lesen Sie! / Sehen Sie! / Nehmen Sie! |
| 1.Pl. (wir) | Konj. I do 1.Pl. + 'wir' (postposto) — usado como Aufforderung | Lesen wir! / Gehen wir! / Lassen wir uns gehen! |

Posição sintática: V1 (cf. 01-01 §2.8). Imperativ tem morfologia reduzida: sem -e final em starken Verben (Lies! não *Liese!).

#### Konjunktiv I/II — overview (postergado)

Konjunktiv I marca **indirekte Rede** (Reportativ). Konjunktiv II marca **Irrealis** e **Höflichkeit**. Aparição já foi notada em Kafka (cf. 01-02 §6 da Aufgabe: `gewähren könne`, `werde eintreten dürfen`). Tratamento sistemático em 02-02 e 02-03.

### 2.8 Reflexivkonstruktionen

#### Echte Reflexive

Verbo **sempre** reflexivo, sem alternativa não-reflexiva:

```
sich beeilen, sich freuen, sich bedanken, sich erinnern, sich entschließen,
sich entwickeln, sich erholen, sich verlieben, sich wundern, sich schämen,
sich weigern, sich begnügen, sich befassen, sich kümmern (um), sich sehnen (nach)
```

#### Falsche Reflexive (Reflexivierung de transitivo)

Verbo transitivo aplicado a si mesmo:

```
sich waschen ← jemanden waschen
sich anziehen ← jemanden anziehen
sich verletzen ← jemanden verletzen
sich sehen (im Spiegel) ← jemanden sehen
```

#### Reziproke

Significado "uns/eles um ao outro", apenas em Plural:

```
Sie treffen sich.       (=einander)
Wir kennen uns.         (=einander)
```

Pode ser substituído por `einander` (gehoben): `sie kennen einander` (em vez de `sie kennen sich`).

#### Akkusativ vs. Dativ-Reflexivpronomen

A maioria dos echten Reflexive rege Akk. Mas alguns regem Dat., distinguindo-se em 1.Sg./2.Sg.:

| Pessoa | Akk. | Dat. |
|---|---|---|
| 1.Sg. | mich | mir |
| 2.Sg. | dich | dir |
| 3.Sg./Pl. + 1./2.Pl. | sich | sich |

Exemplos:
```
Akk.: Ich wasche mich.       Ich freue mich.       Ich beeile mich.
Dat.: Ich wasche mir die Hände.   Ich merke mir das.   Ich stelle mir vor.
```

A distinção é decisiva apenas em 1.Sg. e 2.Sg. — em 3ª pessoa, `sich` é ambíguo entre Akk. e Dat.

Verbos com Reflexiv-Dat. comuns:
```
sich (Dat.) etwas merken       (memorizar)
sich (Dat.) etwas vorstellen   (imaginar)
sich (Dat.) etwas leisten      (permitir-se)
sich (Dat.) etwas ansehen      (assistir, ver)
sich (Dat.) etwas wünschen     (desejar)
sich (Dat.) etwas einbilden    (imaginar erroneamente)
```

### 2.9 Tabelas canônicas (reference)

#### sein, haben, werden — irreguläre

**sein** (= ser/estar)

| | Präsens | Präteritum | Perfekt | Konj. I | Konj. II |
|---|---|---|---|---|---|
| ich | bin | war | bin gewesen | sei | wäre |
| du | bist | warst | bist gewesen | seist | wärst |
| er/sie/es | ist | war | ist gewesen | sei | wäre |
| wir | sind | waren | sind gewesen | seien | wären |
| ihr | seid | wart | seid gewesen | seiet | wäret |
| sie/Sie | sind | waren | sind gewesen | seien | wären |

**haben** (= ter)

| | Präsens | Präteritum | Perfekt | Konj. I | Konj. II |
|---|---|---|---|---|---|
| ich | habe | hatte | habe gehabt | habe | hätte |
| du | hast | hattest | hast gehabt | habest | hättest |
| er/sie/es | hat | hatte | hat gehabt | habe | hätte |
| wir | haben | hatten | haben gehabt | haben | hätten |
| ihr | habt | hattet | habt gehabt | habet | hättet |
| sie/Sie | haben | hatten | haben gehabt | haben | hätten |

**werden** (= tornar-se; Aux. Futur; Aux. Passiv)

| | Präsens | Präteritum | Perfekt | Konj. I | Konj. II |
|---|---|---|---|---|---|
| ich | werde | wurde | bin geworden | werde | würde |
| du | wirst | wurdest | bist geworden | werdest | würdest |
| er/sie/es | wird | wurde | ist geworden | werde | würde |
| wir | werden | wurden | sind geworden | werden | würden |
| ihr | werdet | wurdet | seid geworden | werdet | würdet |
| sie/Sie | werden | wurden | sind geworden | werden | würden |

#### Modalverben — Präsens irregulär (Sg. carece de Endung em 1./3.; Vokalwechsel)

| | können | müssen | dürfen | wollen | sollen | mögen |
|---|---|---|---|---|---|---|
| ich | kann | muss | darf | will | soll | mag |
| du | kannst | musst | darfst | willst | sollst | magst |
| er/sie/es | kann | muss | darf | will | soll | mag |
| wir | können | müssen | dürfen | wollen | sollen | mögen |
| ihr | könnt | müsst | dürft | wollt | sollt | mögt |
| sie/Sie | können | müssen | dürfen | wollen | sollen | mögen |

Präteritum (gemischt: Vokalwechsel + Dental):
```
konnte, mußte, durfte, wollte, sollte, mochte
```

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**, consegue:

1. Listar **as 7 Ablautreihen** com 1 verbo representativo de cada (Stammformen completas).
2. Conjugar `sein, haben, werden` em **todas as formas** das 6 Tempora Indikativ (rapidamente, sem hesitar).
3. Justificar a escolha de `haben` ou `sein` em 8 frases criadas por você (com pelo menos 2 casos de verbo dual: `fahren, fliegen, schwimmen, reiten`).
4. Listar **6+ untrennbare Präfixe** e **6+ trennbare Präfixe** com 1 verbo de exemplo cada.
5. Diagnosticar os **6 prefixos ambivalentes** com par mínimo (literal/figurado) para 4 deles.
6. Explicar a **Süd-Nord-Schiebung** do Präteritum e suas implicações para escrita acadêmica vs. fala.
7. Listar **8 verbos gemischter Konjugation** + os 6 Modalverben com Stammformen (Präsens.3.Sg. / Präteritum.3.Sg. / Partizip II).
8. Diferenciar `Akk.-Reflexiv` de `Dat.-Reflexiv` com 4 exemplos próprios; identificar 5 verbos echte reflexive.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Brüder Grimm — *Der goldene Schlüssel*** (Kinder- und Hausmärchen, 1812; redigido por Wilhelm Grimm). Märchen completo, ~200 palavras. Texto-âncora canônico para Verbalsystem porque:
- Märchen é gênero canônico do **Präteritum narrativo**.
- Densidade de Verben starker Konjugation por todas as 7 Ablautreihen.
- Uso variado de Trennbare Verben.
- Concentração final de Modalverben + Konjunktiv II irrealis.
- Tempus-Bruch deliberado no fim (Präteritum → Präsens → Futur I).

```
Zur Winterszeit, als einmal ein tiefer Schnee lag, mußte ein armer Junge 
hinausgehen und Holz auf einem Schlitten holen. Wie er es nun zusammengesucht 
und aufgeladen hatte, wollte er, weil er so erfroren war, noch nicht nach 
Hause gehen, sondern erst Feuer anmachen und sich ein bißchen wärmen. Da 
scharrte er den Schnee weg, und wie er so den Erdboden aufräumte, fand er 
einen kleinen goldenen Schlüssel. Nun glaubte er, wo der Schlüssel wäre, 
müßte auch das Schloß dazu sein, grub in der Erde und fand ein eisernes 
Kästchen. "Wenn der Schlüssel nur paßt!" dachte er, "es sind gewiß 
kostbare Sachen in dem Kästchen." Er suchte, aber es war kein Schlüsselloch 
da, endlich entdeckte er eins, aber so klein, daß man es kaum sehen konnte. 
Er probierte, und der Schlüssel paßte glücklich. Da drehte er einmal herum, 
und nun müssen wir warten, bis er vollends aufgeschlossen und den Deckel 
aufgemacht hat, dann werden wir erfahren, was für wunderbare Sachen in dem 
Kästchen lagen.
```

### Tarefa

Análise escrita, **800–1200 palavras** em PT-BR com terminologia DE intacta. Sem consultar gramática durante a Aufgabe.

1. **Inventário verbal**: identificar **toda forma verbal finita** do trecho (mínimo 25). Para cada, registrar: Verbo (Inf.), Tempus, Modus, Person/Numerus, Klasse (st./sw./gem./irr.).
2. **Ablautreihen**: para os Verben starker Konjugation, atribuir Reihe (I-VII) e justificar pelo Vokalmuster.
3. **Trennbare Verben**: identificar **todos** (mínimo 5) e marcar onde o prefixo está localizado em cada ocorrência (RK em Hauptsatz; reunido em Nebensatz; Partizip II com `ge-` infixo).
4. **Hilfsverb-Wahl**: para cada Perfekt/Plusquamperfekt no trecho, justificar `haben` ou `sein` segundo o critério §2.5.
5. **Tempus-Verteilung**: o trecho começa em Präteritum, muda no fim. Identificar onde ocorre o Tempus-Bruch e analisar sua função narrativa (efeito metaleptico — saída do mundo do Märchen para a moldura do narrador).
6. **Konjunktiv II em discurso indireto-condicional**: localizar `wäre, müßte` e explicar por que Konjunktiv II e não Indikativ. (Pré-tópico de 02-03; aqui basta reconhecer.)
7. **Modalverb-Distribuição**: 7 Modalverben aparecem (`mußte, wollte, konnte, müßte, müssen, werden`). Classificar cada um como **deontisch** (obrigação/permissão/vontade) ou **epistemisch** (inferência/probabilidade). Note que `werden` futuro é caso à parte.

Output esperado: prosa analítica densa, em PT-BR, com terminologia DE intacta. Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-01 Syntaktische Analyse** (prereq): a localização do verbo na Verbalklammer (LK em V2; RK em VL; pacote inteiro em VL com Modal+Aux) é o substrato sintático sobre o qual a morfologia verbal se aplica.
- **01-02 Kasussystem**: a Klasse verbal (Akk.-rektiv, Dat.-rektiv, Gen.-rektiv) é determinada lexicalmente pelo verbo e fixa o caso dos argumentos. Verbalsystem é a forma; Kasussystem é a regência.
- **01-04 Nominalflexion**: o Partizip II de starken Verben em -en pode ser usado atributivamente e é declinado como adjetivo (`das gelesene Buch, des gelesenen Buches`).
- **01-06 Wortbildung**: trennbare/untrennbare é manifestação morfológica da estrutura interna de Komposita verbais.
- **02-02 Konjunktiv I**: marcação morfológica do Reportativs. Pré-requisito direto: dominar Indikativ-Stammformen.
- **02-03 Konjunktiv II**: Irrealis + Höflichkeit. Pré-requisito: starkstem-Präteritum (Konj.II forma-se sobre o Stamm do Präteritum starker Verben + Umlaut).
- **02-04 Passivkonstruktionen**: werden-Passiv = werden + Partizip II. Sein-Passiv = sein + Partizip II. Pré-requisito: domínio de Partizip II em todas as classes.
- **02-05 Infinitivsätze**: a sintaxe do Infinitivs depende de cohärenz/inkohärenz, que depende da klasse verbal (sehen/hören/lassen comportam-se diferente de wollen/können).
- **02-07 Modalverben**: epistemisch vs. deontisch — aprofundamento de §2.7. Pré-requisito: morfologia básica das Modalverben.
- **03-01 Nominaler vs. verbaler Stil**: a escolha entre Funktionsverbgefüge (nominaler) e verbo simples (verbaler) é central no Wissenschaftsdeutsch.
- **04-01 Historische Linguistik**: as 7 Ablautreihen são heranças do germânico; aprender Ahd./Mhd. esclarece simetrias hoje opacas.
- **PT comparativo**: PT tem ~13 tempos morfológicos vs. ~6 em DE; mas DE distribui Tempus + Modus + Genus em pacotes auxiliar+participio onde PT faz com sufixo. Direção do mapeamento não é trivial: Perfekt DE ≠ "pretérito perfeito composto" PT; Präteritum DE ≠ "pretérito perfeito simples" PT em registro.

---

## 6. Quellen

### Gramáticas canônicas

1. **Eisenberg, Peter** — *Grundriss der deutschen Grammatik*. Bd. 1 *Das Wort*, capítulos sobre Verbalflexion e Stammbildung. Bd. 2 *Der Satz*, capítulo sobre Tempus-Modus-System.
2. **Helbig, Gerhard / Buscha, Joachim** — *Deutsche Grammatik*. Capítulos sobre "Konjugation", "Tempus", "Genus verbi". Listas exaustivas de starken Verben por Reihe.
3. **Engel, Ulrich** — *Deutsche Grammatik*. Iudicium, 2009. Tratamento dependencial do verbo + valência.
4. **Duden, Bd. 4: Die Grammatik**. 9. Aufl. 2016. Tabelas canônicas de conjugação; tratamento de trennbar/untrennbar.
5. **Duden, Bd. 9: Richtiges und gutes Deutsch**. Para zonas duvidosas (Süd-Nord-Schiebung, Plurizentrik).

### Sobre Ablautreihen

- **Stein, Stephan** — *Stammbildungslehre des Deutschen*. Niemeyer, 1998.
- **Krause, Wolfgang** — *Handbuch des Gotischen*. Beck, 1968. (Para origem germânica das Reihen.)
- **Eisenberg, Bd. 1**, capítulo "Starke Verben — Ablautreihen".

### Sobre Tempus-Distribuição

- **Thieroff, Rolf** — *Das finite Verb im Deutschen: Tempus-Modus-Distanz*. Narr, 1992.
- **Hennig, Mathilde** — *Tempus und Temporalität in geschriebenen und gesprochenen Texten*. Niemeyer, 2000. **Estudo empírico da Süd-Nord-Schiebung.**
- **Welke, Klaus** — *Tempus im Deutschen: Modellierung eines komplexen Bedeutungssystems*. De Gruyter, 2005.

### Sobre Trennbarkeit

- **Stiebels, Barbara / Wunderlich, Dieter** — "Morphology feeds syntax: the case of particle verbs". *Linguistics* 32 (1994), 913–968.
- **Müller, Stefan** — *Complex Predicates: Verbal Complexes, Resultative Constructions, and Particle Verbs in German*. CSLI, 2002.

### IDS-Grammis

- **https://grammis.ids-mannheim.de/** — buscar "Tempus", "Konjugation", "Trennbarkeit", "Ablautreihe", "Modalverb".

### Léxico de valência

- **Helbig / Schenkel** — *Wörterbuch zur Valenz und Distribution deutscher Verben*. Niemeyer.
- **VALBU** (online IDS): https://grammis.ids-mannheim.de/verbvalenz

### Texto primário do módulo

- **Brüder Grimm** — *Der goldene Schlüssel*. KHM 200, último Märchen da Sammlung. *Kinder- und Hausmärchen* (1812; canônica: 7. Aufl. 1857). Reclam UB; Projekt Gutenberg: https://www.projekt-gutenberg.org/grimm/maerchen/chap201.html

---

**Próximo módulo (paralelo):** [01-04 Nominalflexion](01-04-nominalflexion.md). Ambos podem ser feitos em paralelo dado prereqs satisfeitos (01-01 + 01-02).
