---
module: 01-02
title: Kasussystem — Funktionen und Träger
stage: fundamente
prereqs: [01-01]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Por que 'Vor dem Gesetz steht ein Türhüter' usa Dat. e não Akk. depois de 'vor'?"
    options:
      - "Porque 'vor' sempre rege Dat."
      - "Porque é uma Wechselpräposition: Dat. quando indica Lage (localização estática), Akk. quando indica Richtung (movimento direcional). Aqui é Lage."
      - "Porque o Türhüter está no Akkusativ e a preposição concorda."
      - "Porque é variação estilística de Kafka."
    correct: 1
    explanation: "'vor' é Wechselpräposition: rege Dat. para Lage (Wo? — onde algo está) e Akk. para Richtung (Wohin? — para onde algo se move). 'Vor dem Gesetz steht...' indica posição estática, daí Dat."
  - q: "Em 'sich seines Verstandes bedienen', por que 'Verstand' está no Genitiv?"
    options:
      - "Porque é Possessivattribut."
      - "Porque 'sich bedienen' rege Genitivobjekt — pertence à classe fechada de verbos reflexivos com Gen.-Rektion (gehoben/archaisch)."
      - "Porque toda NP após Reflexivpronomen vai pro Gen."
      - "Porque é uma elipse de 'des Verstandes Wert'."
    correct: 1
    explanation: "'sich bedienen' é membro da klasse fechada de Reflexiva mit Gen.-Rektion (sich annehmen, sich bemächtigen, sich entsinnen, sich enthalten, sich erinnern, sich rühmen, sich schämen, sich versichern, sich bedienen). Equivalente moderno coloquial: 'seinen Verstand benutzen' (Akk.-Rektion)."
  - q: "Qual a forma correta do Genitiv Sg. de 'der Mensch'?"
    options:
      - "des Mensches"
      - "des Menschs"
      - "des Menschen"
      - "der Mensches"
    correct: 2
    explanation: "'Mensch' pertence à N-Deklination (klasse fechada de Maskulina: Mensch, Held, Bote, Junge, Russe, Türke, Affe, Hase, Polizist, Präsident, Student...). Todos os casos não-Nom. + Plural levam -(e)n: den Menschen, dem Menschen, des Menschen, die Menschen."
  - q: "Em 'Trotz dem Wetter' vs 'Trotz des Wetters', qual é norma da Hochsprache escrita?"
    options:
      - "'Trotz dem Wetter' (Dat.) — 'trotz' rege Dat. modernamente."
      - "'Trotz des Wetters' (Gen.) — 'trotz' rege Gen. em Hochsprache; o Dat. é coloquial regional (sul, austríaco)."
      - "Ambos são igualmente corretos em qualquer contexto."
      - "'Trotz' não rege caso, é advérbio."
    correct: 1
    explanation: "'Trotz' rege Gen. em norma escrita standard (Eisenberg, Duden). O uso com Dat. é difundido coloquialmente, especialmente bávaro-austríaco (Plurizentrik), e tolerado pelo Duden como variante; não é norma da Hochsprache acadêmica."
  - q: "Em 'Ich helfe dem Mann', por que 'Mann' está no Dat.?"
    options:
      - "Porque 'helfen' é verbo intransitivo."
      - "Porque 'helfen' rege Dativobjekt — pertence à classe verbal Dat.-rektiv (helfen, danken, gehören, gefallen, antworten, begegnen, raten, vertrauen, gratulieren, fehlen, schaden)."
      - "Porque o sujeito é 'ich' e o Dativ marca contraste."
      - "Porque a frase é declarativa."
    correct: 1
    explanation: "Existe uma klasse delimitada de verbos que regem Dat. (não Akk., como seria intuitivo pra falantes de PT/EN). Helbig/Buscha lista ~50; os centrais são memorizáveis: helfen, danken, gehören, gefallen, antworten, begegnen, raten, vertrauen, gratulieren, fehlen, schaden, drohen, dienen, folgen, gehorchen, glauben (Person)."
---

# 01-02, Kasussystem — Funktionen und Träger

## 1. Sprachliches Problem

O alemão tem **quatro Kasus** (Nom., Akk., Dat., Gen.) — número modesto comparado ao russo (6) ou polonês (7) — mas a **distribuição** dos Kasus é onde o alemão complica:

- O caso quase nunca está marcado **no substantivo**. Está nos **acompanhantes**: artigo, pronome possessivo, adjetivo atributivo. *Mann* não muda; *der Mann / den Mann / dem Mann / des Mannes* é onde o caso aparece.
- A **regência verbal** (`helfen + Dat`) e a **regência preposicional** (`mit + Dat`, `für + Akk`) são memorizáveis mas vastas. Erros aqui são marcadores imediatos de não-nativo: `*ich helfe dich`.
- Há uma **classe fechada de verbos com Gen.-Rektion** (`sich bedienen`, `bedürfen`, `gedenken`) — gehoben/arcaica mas viva no Wissenschaftsdeutsch. Sem ela, você não lê Kant.
- Existe uma **N-Deklination** que parece exceção arbitrária mas é classe sistemática (`Mensch, Held, Junge, Bote, Polizist, Student, Präsident...`).
- O Genitiv **recua** sob pressão coloquial (Dativ assume território) — mas a recuperação do Gen. é signum de Wissenschaftsregister hoch. Nas Plurizentrik-Varietäten DE/AT/CH, o ritmo desse recuo difere.

Sem este módulo:
- Você produz `*ich helfe dich` (Akk.) por contaminação de PT/EN; nativo identifica em <1s.
- Você lê `sich seines Verstandes bedienen` e perde 3 minutos checando o que `seines` modifica.
- Você escreve `*den Mann hat geschlafen` (`den Mann` em Vorfeld interpretado como Akk.) ou `*die Frau hilft den Mann` (Akk. em vez de Dat.).
- Você não consegue diagnosticar Plurizentrik (`Trotz dem Wetter` vs `Trotz des Wetters`).

Este módulo organiza o sistema. A regência específica é Anki — mas o **sistema** que torna a regência inteligível é teoria.

---

## 2. Harte Theorie

### 2.1 Os 4 Kasus, função primária

| Kasus | Funções primárias | Pergunta-Test |
|---|---|---|
| **Nominativ** | Subjekt; Prädikativ (após `sein`, `werden`, `bleiben`, `heißen`); Anredeform (vokativ-ähnlich) | *Wer/Was?* |
| **Akkusativ** | Direktes Objekt (Akk.-Objekt); Akk.-Rektion preposicional; Zeitdauer (`einen Tag lang`); Wechselpräp. + Richtung; Akk. nach `kosten` | *Wen/Was?* |
| **Dativ** | Indirektes Objekt; Dat.-Rektion verbal; Dat.-Rektion preposicional; Dativus commodi; Dativus possessivus; Wechselpräp. + Lage | *Wem?* |
| **Genitiv** | Possessivattribut; Partitivattribut; Subjektgenitiv vs. Objektgenitiv; Genitivobjekt (gehoben); Gen.-Rektion preposicional; Adjektiv-Rektion (`bewusst, würdig, mächtig`) | *Wessen?* |

A pergunta-Test (W-Frage) é instrumento didático canônico — mas **não suficiente** para Wechselpräpositionen e Adjektivrektion. Use-a como triagem, não como veredito.

### 2.2 Onde o caso aparece — morfologia da Trägermarkierung

Em DE moderno, o substantivo carrega **pouca** marca de caso. As marcas estão nos acompanhantes.

#### Marcação no substantivo (residual)

| Caso | Marca residual no substantivo | Exemplo |
|---|---|---|
| Nominativ | ∅ | `der Mann` |
| Akkusativ | ∅ (exc. N-Deklination) | `den Mann` ; `den Menschen` (N-Dekl.) |
| Dativ | -e arcaico opcional Sg.m./n.; -n obrigatório Pl.; -en N-Dekl. | `dem Manne` (gehoben) ; `den Männern` ; `dem Menschen` |
| Genitiv | -(e)s Sg.m./n.; -en N-Dekl. | `des Mannes` ; `des Menschen` |

A "Dativ-e" (`dem Manne`) está em recuo desde o séc. XIX; sobrevive em fórmulas (`zu Pferde, zu Hause, im Lande, dem Manne kann geholfen werden, von Hause aus`).

#### Marcação nos acompanhantes — Tabela canônica do Det.

|  | Sg.m. | Sg.f. | Sg.n. | Pl. |
|---|---|---|---|---|
| **Nom.** | der | die | das | die |
| **Akk.** | den | die | das | die |
| **Dat.** | dem | der | dem | den (+ -n no N) |
| **Gen.** | des (+ -es no N) | der | des (+ -es no N) | der |

Desta tabela emergem todos os outros Determinativa por **mesmas terminações** sobre raízes diversas:

```
dies-er / dies-en / dies-em / dies-es     (demonstrativo)
welch-er / welch-en / welch-em / welch-es (interrogativo)
jed-er / jed-en / jed-em / jed-es          (universal)
mein, dein, sein, ihr (Sg.m./n.: ∅; Sg.f./Pl.: -e); -en/-em/-es seguindo o padrão
```

#### Adjektivflexion (overview)

Adjektivos atributivos têm 3 padrões — função do Det. precedente:

| Padrão | Quando | Por quê |
|---|---|---|
| **Schwach** (-e/-en) | após Det. com marca de caso (`der, dies-, welch-`) | Det. já marca caso → Adj. minimaliza |
| **Stark** (carrega as marcas do Det.) | sem Det. | Adj. assume função distintiva do caso |
| **Gemischt** | após `ein, kein, mein, dein, sein, ihr, unser, euer` no Sg. (onde `ein` não marca caso) | Adj. complementa o que `ein` não marca |

Detalhe completo no módulo **01-04 Nominalflexion**. Aqui basta: a marca de caso migra entre Det. e Adj. — sempre alguém marca.

### 2.3 N-Deklination — classe fechada sistemática

Não é exceção arbitrária. É uma **klasse fechada** de Maskulina cujo padrão é: terminação `-(e)n` em todos os casos exceto Nom.Sg.

| Sub-classe | Membros | Padrão |
|---|---|---|
| **Belebte Mask. em -e** | Junge, Bote, Russe, Türke, Affe, Hase, Löwe, Riese, Erbe, Genosse, Buchstabe (irreg.) | Akk./Dat./Gen.Sg. + Pl. = `-(e)n` |
| **Bisilábicos arcaicos** | Mensch, Held, Bauer (gemischt: Gen. `des Bauern` ; alguns dialetos `des Bauers`), Herr (irreg.: `den Herrn / dem Herrn / des Herrn / die Herren`), Nachbar (gemischt) | idem |
| **"Ausländer"-Mask.** | Polizist, Präsident, Diplomat, Student, Tourist, Pilot, Architekt, Soldat, Fotograf, Idiot, Pianist, Optimist, Komponist, Demokrat | idem |
| **Sub-classe `-(e)ns` Genitiv** | Name, Buchstabe, Glaube, Gedanke, Frieden, Wille, Funke (gemischt) | Gen.Sg. = `-(e)ns`: `des Namens, des Glaubens, des Willens, des Gedankens` ; demais idem N-Dekl. |

Pattern de detecção: se a palavra é Mask. e refere a **pessoa, profissão acadêmica/oficial ou ser animado**, **provavelmente é N-Dekl.** (Polizist → des Polizisten ; Architekt → den Architekten).

Erro recorrente de não-nativo: `*Ich sehe den Polizist` em vez de `*Ich sehe den Polizisten*`.

### 2.4 Verbal-Rektion

O verbo determina o caso de seu objeto. Três grandes classes:

#### Klasse I — `+ Akk` (default)

A maioria dos verbos transitivos. Não memorizar lista — assumir Akk. como default.

```
sehen, lesen, kaufen, essen, trinken, nehmen, geben (+ Dat),
hören, finden, suchen, treffen, fragen, lieben, hassen, ...
```

#### Klasse II — `+ Dat` (klasse fechada — memorizável)

```
helfen, danken, gehören, gefallen, antworten, begegnen,
raten, vertrauen, gratulieren, fehlen, schaden, drohen,
dienen, folgen, gehorchen, glauben (+ Pers.: ich glaube dir),
zuhören, zustimmen, widersprechen, ähneln, nahekommen,
beistehen, beitreten, einfallen (+ Pers.: das fällt mir ein),
gelingen (+ Pers.: das gelingt mir), passen (+ Pers.),
schmecken (+ Pers.), wehtun (+ Pers.), ...
```

Heuristica: muitos significam **interação social interpessoal** (helfen, danken, antworten, raten). Sub-padrão: psicológico-experiencial (gefallen, schmecken, fehlen, einfallen) — sujeito é o **estímulo**, dativo é o **experiente**.

#### Klasse III — `+ Akk + Dat` (ditransitivos)

```
geben, schenken, schicken, bringen, leihen, erklären, zeigen,
empfehlen, vorlesen, mitteilen, verkaufen, wünschen, anbieten,
versprechen, zumuten, ...
```

Padrão: dativ = receptor; akk. = tema. Default Mittelfeld-Reihenfolge: Dat. (recipient) > Akk. (tema) (cf. 01-01 §2.4).

```
Ich gebe | dem Mann | das Buch.       (default: Dat > Akk)
Ich gebe | das Buch | dem Mann.       (foco contrastivo: Mann é foco)
Ich gebe | es        | ihm.            (Pron-Akk > Pron-Dat — invertido!)
```

#### Klasse IV — `+ Gen` (gehoben/archaisch — klasse fechada pequena)

```
bedürfen, gedenken, harren, ermangeln, entbehren, walten,
achten (gehoben), entraten, sich annehmen, sich bedienen,
sich bemächtigen, sich besinnen, sich entsinnen, sich enthalten,
sich erfreuen, sich erinnern (gehoben — moderno: an + Akk),
sich rühmen, sich schämen, sich versichern, sich vergewissern,
sich entledigen, sich erbarmen, sich erwehren, sich anmaßen.
```

Quase todos têm equivalente moderno coloquial:

| gehoben | moderno |
|---|---|
| `seines Verstandes sich bedienen` | `seinen Verstand benutzen / gebrauchen` |
| `sich der Sache annehmen` | `sich um die Sache kümmern` |
| `seiner Pflicht gedenken` | `an seine Pflicht denken` |
| `eines Verbrechens sich rühmen` | `mit einem Verbrechen prahlen` |

Em Wissenschaftsdeutsch (Kant, Hegel, Habermas) e em Bürokratendeutsch judicial, a Klasse IV é viva. Em fala coloquial, está extinta.

#### Klasse V — `+ 2 × Akk` (residual)

Apenas:

```
lehren  (Akk. der Person + Akk. der Sache):  Er lehrt mich Deutsch.
nennen  (Akk. + Akk. predikativ):           Er nennt ihn einen Freund.
schimpfen (gehoben):                          Er schimpft ihn einen Idioten.
heißen   (Akk. + Akk. predikativ, gehoben):  Man heißt ihn einen Verräter.
kosten  (Akk. der Person + Akk. der Sache):  Es kostet mich einen Tag.
```

Padrão em recuo: `lehren + Akk + Akk` é norma; `lehren + Dat + Akk` é coloquial difundido (`Er lehrt mir Deutsch` é frequentíssimo, mas não-norma).

### 2.5 Präpositional-Rektion

Cada Präposition rege caso fixo. Memorização **obrigatória** (Anki-Material).

#### + Akk apenas

```
durch, für, gegen, ohne, um, wider,
bis (geralmente),
entlang (postposto: den Fluss entlang)
```

Mnemônico: **DÜFOGUW** ou **DOGFU** + alguns.

#### + Dat apenas

```
aus, bei, mit, nach, seit, von, zu,
gegenüber (também postposto: dem Haus gegenüber),
außer, entgegen, gemäß, zuwider,
ab (uso temporal: ab dem 1. Mai)
```

Mnemônico: **AusBeiMitNachSeitVonZu** + extras.

#### + Gen (klasse aberta, em recuo)

```
anhand, anlässlich, angesichts, anstatt/statt, anstelle,
aufgrund, ausschließlich, behufs (alt), betreffs, bezüglich,
einschließlich, halber (postposto), hinsichtlich, infolge,
inmitten, innerhalb, jenseits, kraft, längs (Gen./Dat.),
mangels, mittels, namens, oberhalb, seitens, trotz (Gen./Dat.),
um... willen, ungeachtet, unterhalb, vermittels, vermöge,
während (Gen./Dat. cooloquial), wegen (Gen./Dat. coloquial),
zugunsten, zwecks
```

Em coloquial (especialmente bávaro-austríaco), `trotz, während, wegen, statt` migram para Dat. (`trotz dem Regen, wegen dem Wetter`) — Duden tolera mas não é norma escrita.

#### Wechselpräpositionen — Akk. (Richtung) vs. Dat. (Lage)

```
an, auf, hinter, in, neben, über, unter, vor, zwischen
```

Diagnóstico:
- **Wohin?** (movimento direcional, mudança de posição) → Akk.
- **Wo?** (localização estática, posição mantida) → Dat.

```
Ich gehe in die Schule.       (Wohin? — Akk.)
Ich bin in der Schule.        (Wo?   — Dat.)

Er stellt das Buch auf den Tisch.   (Wohin? — Akk.)
Das Buch liegt auf dem Tisch.       (Wo?   — Dat.)

Vor dem Gesetz steht ein Türhüter.  (Wo?   — Dat.)
Er tritt vor das Gesetz.            (Wohin? — Akk., gehoben)
```

Falsamente intuitivo: alguns verbos parecem implicar movimento mas o caso preposicional decide pela **localização do resultado**, não pelo movimento. `Er hängt das Bild an die Wand` (Akk., chega à parede) ; `Das Bild hängt an der Wand` (Dat., está na parede).

### 2.6 Adjektiv-Rektion

Adjetivos predicativos podem reger caso de complemento.

#### + Dat (klasse principal)

```
ähnlich, bekannt, bewusst (gehoben + Gen),
dankbar, fremd, freundlich, gewachsen, gleich,
nahe, nützlich, peinlich, schädlich, treu, überlegen,
unterlegen, verwandt, willkommen
```

```
Er ist mir dankbar.                  (Dat. mir)
Das ist meinem Vater ähnlich.        (Dat. Vater)
Er ist seiner Verantwortung gewachsen. (Dat. Verantwortung — não Gen.!)
```

#### + Akk

```
gewohnt, los (acus. residual), satt, leid (geh.),
wert (em geral Gen.: einer Sache wert)
```

```
Ich bin diese Diskussion satt.       (Akk.)
Er ist seinen Job los.               (Akk., coloquial)
```

#### + Gen (gehoben)

```
bewusst, gewahr, gewiss, kundig, mächtig, eingedenk,
schuldig, teilhaftig, verdächtig, würdig
```

```
Er ist sich seiner Verantwortung bewusst.    (Gen., gehoben — alt: + Dat. norm)
Er ist der deutschen Sprache mächtig.        (Gen., klassisch)
Er wurde des Mordes verdächtigt.             (Gen., judicial)
```

### 2.7 Festsprachliche Kasusreste

Construções fixas onde o caso é lexicalizado e não generalizável:

```
zu Hause / nach Hause              (Dat./Akk. fossilizados)
guten Mutes sein                    (Gen.Sg., gehoben)
des Pudels Kern                     (Gen.Sg. ante-posto, gehoben/Goethe-Echo)
im Falle eines Notfalls             (Gen.Sg., bürokratendeutsch)
eines schönen Tages                 (Gen.Sg. adverbial, narrativo)
auf eigene Faust                    (Akk., idiomatisch)
im Großen und Ganzen                (Dat., adverbial)
von Hause aus                       (Dat. fossilizado em PP)
seit eh und je                      (locução fixa)
```

Reconhecer essas como festsprachlich (e não como produtivas) evita generalização errônea.

### 2.8 Plurizentrik do Genitiv-Recuo

| Variedade | Padrão de Genitiv-Recuo |
|---|---|
| **Bundesdeutsches Hochdeutsch (escrito)** | Gen. preservado em norma; coloquial admite Dat. com `wegen, trotz, während, statt`. |
| **Österreichisches Hochdeutsch** | Recuo um pouco mais avançado coloquialmente; norma escrita conservadora. |
| **Schweizer Hochdeutsch** | Gen. **mais preservado** em escrita; Schweizer Mundart é caso à parte (sem Gen.). |
| **Bayerisch / Süddeutsch (oral)** | Forte preferência por Dat. (`wegen dem Wetter`); evita Gen. quase categoricamente. |

Em Wissenschaftsdeutsch ou Feuilleton de elite (FAZ, NZZ, Die Zeit), use Gen. canônico. Em diálogo ou prosa coloquial, Dat. é defensível.

### 2.9 Diagnóstico — pipeline para identificar o caso de uma NP

Aplicar **na ordem**:

1. **Préposição rege?** Se a NP está dentro de PP, a preposição fixa o caso (com cuidado para Wechselpräp.: aplicar Wo?/Wohin?).
2. **Verbo rege?** Se a NP é objeto de um verbo, identificar o verbo e sua klasse (I-V).
3. **Adjektivo rege?** Se a NP é complemento de adjetivo predicativo (`bewusst + Gen`).
4. **Predikativ?** Após `sein, werden, bleiben, heißen` → Nom.
5. **Subjekt?** → Nom. (default).
6. **Default funcional**: 
   - direkt-Objekt → Akk.
   - indirekt-Objekt → Dat.
   - Possessivattribut → Gen.
7. **W-Frage-Test** (último recurso): *Wer/Was/Wen/Wem/Wessen?*

Se o pipeline 1–7 não converge, é caso fossilizado (festsprachlich) — verificar diccionariamente.

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**, consegue:

1. Listar **6+ verbos da Klasse II (Dat.-rektiv)** com exemplo próprio cada.
2. Listar **6+ verbos da Klasse IV (Gen.-rektiv)** e dar o equivalente moderno coloquial de cada.
3. Explicar a **N-Deklination** com 3 sub-classes e 4 membros de cada.
4. Aplicar o **diagnóstico Wo?/Wohin?** em 5 frases com Wechselpräpositionen criadas por você.
5. Dar a **flexão completa** de `der Mensch`, `der Bauer`, `der Herr`, `der Name` (4 N-Dekl. com sub-padrão `-(e)ns`).
6. Listar **5 Präp. + Gen** e diagnosticar quais admitem Dat. coloquial (e onde — bundesdeutsch, austríaco, suíço).
7. Listar **6 adjetivos** com regência de caso (Dat./Akk./Gen.) com exemplo cada.
8. Dadas 10 NPs em frases autênticas, identificar o caso de cada uma e justificar via pipeline §2.9.

---

## 4. Sprachliche Aufgabe

### Texto-âncora

**Franz Kafka — *Vor dem Gesetz*** (parábola, originalmente em *Der Process*, capítulo "Im Dom"; publicada isoladamente em *Selbstwehr*, 1915).

> "Vor dem Gesetz steht ein Türhüter. Zu diesem Türhüter kommt ein Mann vom Lande und bittet um Eintritt in das Gesetz. Aber der Türhüter sagt, daß er ihm jetzt den Eintritt nicht gewähren könne. Der Mann überlegt und fragt dann, ob er also später werde eintreten dürfen. 'Es ist möglich', sagt der Türhüter, 'jetzt aber nicht.' Da das Tor zum Gesetz offensteht wie immer und der Türhüter beiseitetritt, bückt sich der Mann, um durch das Tor in das Innere zu sehn."

(Continuação completa em Reclam UB 9430 ou Projekt Gutenberg.)

### Tarefa

Análise escrita, **800–1200 palavras** em PT-BR com terminologia DE intacta. Sem consultar gramática durante a Aufgabe.

1. **Inventário Kasus**: identificar **toda NP** do trecho e classificar (Kasus, gênero, número), justificando via pipeline §2.9. Mínimo 25 NPs.
2. **Wechselpräpositionen no trecho**: identificar **todas** (`vor`, `zu`, `in`, `durch`, `um`...) e diagnosticar Lage vs. Richtung em cada uma.
3. **Verbal-Rektion**: para os verbos do trecho (`stehen, kommen, bitten, sagen, gewähren, überlegen, fragen, dürfen, eintreten, offenstehen, beiseitetreten, sich bücken, sehn`), classificar pela klasse (I-V) e justificar.
4. **N-Deklination no trecho**: identificar todas as ocorrências (atenção a `der Mann`, `der Türhüter`, `der Bote`...) e marcar a flexão.
5. **Genitiv preservado**: o trecho tem `vom Lande` (Dat. fossilizado) e `Eintritt in das Gesetz` (Akk. — Wechselpräp. + Richtung). Há Genitivos? Onde? Por que tão escassos comparado a Kant?
6. **Konjunktiv I em discurso indireto**: `gewähren könne`, `werde eintreten dürfen` — identificar formas e justificar (Konjunktiv I é território do módulo 02-02; aqui basta reconhecer e marcar). Por que Kafka usa Konjunktiv I e não Indikativ?
7. **Comparação Kasus-densidade Kant vs. Kafka**: Kant tem 5 Genitive numa frase; Kafka tem ~0 nesta abertura. Diagnóstico: registro? gênero textual? estilo do autor?

Output esperado: prosa analítica densa, em PT-BR, com terminologia DE intacta.

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-01 Syntaktische Analyse** (prereq direto): a localização das NPs no Mittelfeld depende do Feldermodell; a hierarquia Dat. > Akk. (default) e Pron-Akk. > Pron-Dat. (em pronomes) já foi tratada lá.
- **01-04 Nominalflexion**: este módulo identifica os Kasus; o 01-04 detalha a flexão dos Determinativa e Adjektive em cada caso.
- **01-05 Pronominalsystem**: pronomes carregam marca de caso máxima (`er/ihn/ihm/seiner`); o sistema é mais regular que o nominal.
- **01-06 Wortbildung**: muitos Komposita herdam Genitivattribute fossilizados (`Geistesblitz, Gottesfurcht, Tageslicht`).
- **02-01 Subordination**: a regência preposicional aparece em Subjunktoren preposicionais (`bevor, sobald, sodass`).
- **02-04 Passivkonstruktionen**: o `werden`-Passiv promove o Akk.-Objekt a Subjekt-Nom., mas Dat.-Objekt não promove (`Mir wird geholfen` — sujeito é impessoal/elidido). O comportamento sob passivização é diagnóstico de klasse verbal.
- **03-01 Nominaler Stil**: a densidade de Genitivattribute em prosa nominal (Adorno, Habermas) ressuscita o caso ameaçado de recuo.
- **04-09 Kontrastive Linguistik PT–DE**: PT colapsou Akk./Dat. em "objeto direto/indireto" sem morfologia distinta; DE preserva. A intuição PT é o erro mais frequente em `helfen + Dat`.
- **PT comparativo**: PT tem caso vestigial em pronomes átonos (`me, te, se, lhe`). DE distribui caso pleno em Det. e Adj. Aprender DE = re-treinar a percepção do caso.

---

## 6. Quellen

### Gramáticas canônicas

1. **Eisenberg, Peter** — *Grundriss der deutschen Grammatik*. Bd. 1 *Das Wort*, capítulos sobre Substantiv-Flexion e Det.-Flexion. Bd. 2 *Der Satz*, capítulo sobre Rektion.
2. **Helbig, Gerhard / Buscha, Joachim** — *Deutsche Grammatik. Ein Handbuch für den Ausländerunterricht*. Capítulos sobre "Verben mit Dativ", "Verben mit Genitiv", "Präpositionen". Listas exaustivas.
3. **Engel, Ulrich** — *Deutsche Grammatik*. Iudicium, 2009. Abordagem dependencial — apresenta regência como propriedade lexical do Verbo. Excelente como contraste teórico.
4. **Duden, Bd. 4: Die Grammatik**. 9. Aufl. 2016. Capítulos sobre Kasusrektion preposicional. Para zonas duvidosas e Plurizentrik.
5. **Zifonun / Hoffmann / Strecker** — *Grammatik der deutschen Sprache*. De Gruyter, 1997. (IDS-Grammatik.) Capítulo sobre "Komplemente" — densíssimo, Stage 4+.

### Sobre Genitiv-Recuo especificamente

- **Behaghel, Otto** — *Deutsche Syntax: Eine geschichtliche Darstellung*. Bd. 1, capítulo sobre Genitiv. Heidelberg: Winter, 1923. **A descrição clássica do recuo do Genitiv ao longo da história do alemão.**
- **Sick, Bastian** — *Der Dativ ist dem Genitiv sein Tod* (3 Bde., 2004-2006). Não-acadêmico mas popular; discute Plurizentrik. Tomar com filtro — Sick é prescritivista.
- **Konopka, Marek / Wöllstein, Angelika (Hg.)** — *Genitivobjekt im Deutschen*. (Vários papers em ZGL.)

### Sobre N-Deklination

- **Köpcke, Klaus-Michael** — *Untersuchungen zur Pluralbildung im Deutschen*. Stauffenburg, 1993. Inclui análise de N-Dekl. como sub-sistema.
- **Eisenberg, Bd. 1** — capítulo sobre "Schwache Maskulina".

### IDS-Grammis (online)

- **https://grammis.ids-mannheim.de/** — buscar por "Kasus", "Rektion", "N-Deklination", "Wechselpräposition", "Genitivobjekt".

### Texto primário do módulo

- **Kafka, Franz** — *Vor dem Gesetz*. Em: *Selbstwehr*, Jg. 9, Nr. 34 (07.09.1915); reeditado em *Der Process*, capítulo "Im Dom" (1925, póstumo, ed. Max Brod). 
   - Edição canônica: *Kritische Ausgabe*, S. Fischer, Bd. *Der Process*.
   - Edição acessível: Reclam UB Nr. 9430.
   - Online: https://www.projekt-gutenberg.org/kafka/process/process.html

### Léxicos de regência

- **Helbig, Gerhard / Schenkel, Wolfgang** — *Wörterbuch zur Valenz und Distribution deutscher Verben*. Niemeyer. **Léxico de valência verbal — referência canônica para regência.**
- **VALBU** (Valenzwörterbuch deutscher Verben) — IDS, online: https://grammis.ids-mannheim.de/verbvalenz

---

**Próximo módulo:** [01-03 Verbalsystem I](01-03-verbalsystem.md) (após os 3 Tore deste passarem).
