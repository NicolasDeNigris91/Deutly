---
module: 01-08
title: Phonetik & Phonologie — IPA, Vokalsystem, Konsonanten, Auslautverhärtung, Knacklaut
stage: fundamente
prereqs: []
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Por que 'lieb' termina em [p] e não [b], como 'liebe' [b]?"
    options:
      - "Erro fonológico do falante."
      - "**Auslautverhärtung**: em sílaba final, oclusivas vozeadas /b, d, g/ neutralizam para /p, t, k/. Regra fonotática alemã. 'lieb' [liːp]; 'liebe' [ˈliːbə] (com -e átona, /b/ não está em coda)."
      - "Variação dialetal."
      - "Erro ortográfico."
    correct: 1
    explanation: "Auslautverhärtung é regra obrigatória da fonologia DE: em fim de sílaba (Auslaut), as oclusivas /b, d, g/ devozeiam para [p, t, k]. Isso afeta também /v/ → [f] em alguns casos lexicalizados. Adicionar sufixo (-e, -en) muda silabificação e desfaz o devozeamento. Pares clássicos: Tag [taːk] / Tage [ˈtaːɡə]; Hund [hʊnt] / Hunde [ˈhʊndə]."
  - q: "Como se distingue [ç] (ich-Laut) de [x] (ach-Laut)?"
    options:
      - "São o mesmo som."
      - "Distribuição alofônica: [ç] após vogais frontais (i, e, ä, ö, ü, ei, eu, äu) + após consoantes; [x] após vogais traseiras (a, o, u, au). 'ich' [ɪç], 'Buch' [buːx], 'Bach' [bax], 'lachen' [ˈlaxn̩], 'sicher' [ˈzɪçɐ]."
      - "[ç] é gehoben, [x] coloquial."
      - "Variação dialetal apenas."
    correct: 1
    explanation: "/ç/ e /x/ são alofones em complementação distribucional do fonema /x/. [x] após vogais traseiras [a, o, u, aʊ]; [ç] em todas as demais posições (após vogais frontais, consoantes, no diminutivo -chen). Não há pares mínimos onde [ç] e [x] contrastam — daí serem alofones, não fonemas."
  - q: "Em 'die Eltern', há um som não escrito antes de [ɛ]. Qual?"
    options:
      - "Nenhum — palavra começa direto com [ɛ]."
      - "**Knacklaut** [ʔ] (oclusiva glotal): em DE, palavras (ou sílabas dentro de palavra) que começam com vogal são precedidas obrigatoriamente por uma oclusiva glotal silente. 'die Eltern' = [diː ˈʔɛltɐn]. Em frase corrida: 'mit Eltern' = [mɪt ˈʔɛltɐn] (não fundindo: *[mɪˈtɛltɐn])."
      - "Schwa [ə]."
      - "Aspiração [h]."
    correct: 1
    explanation: "O Knacklaut [ʔ] é traço fonológico decisivo do alemão padrão (Hochdeutsch). Toda vogal inicial em palavra (ou em sílaba composto-interna após fronteira morfológica) recebe [ʔ] obrigatório. 'beobachten' = [bəˈʔoːbaxtn̩] (com [ʔ] entre be- e -obachten). Sem o Knacklaut, ouvinte nativo identifica não-nativo imediatamente."
  - q: "Em -en não-acentuado final de palavra (e.g., 'lesen, machen, gehen'), como se realiza foneticamente em fala normal?"
    options:
      - "[en] como ortografado."
      - "Schwa-Reduktion + assimilação: [ən] em fala lenta, mas frequentemente reduzido a [n̩] (sílaba consonântica) em fala normal: 'lesen' [ˈleːzn̩], 'machen' [ˈmaxn̩], 'gehen' [ˈɡeːn̩]. O schwa [ə] é dropado e /n/ torna-se núcleo silábico."
      - "[ɪn]."
      - "[un]."
    correct: 1
    explanation: "Em fala normal, o sufixo -en átono sofre Schwa-Reduktion massiva. Padrão: o schwa pode persistir em fala lenta/cuidada [ən], mas é eliminado em fala fluente, deixando o /n/ como núcleo silábico [n̩]. Após /b, p, m/ pode haver assimilação: 'haben' [ˈhaːbm̩]; 'leben' [ˈleːbm̩]. Essa redução é traço de fala fluente nativa — sua ausência soa pedante."
  - q: "Como se realiza /r/ em coda silábica final (Auslaut), como em 'der, mehr, Vater'?"
    options:
      - "[r] trinado."
      - "[ɐ̯] vocal (vogal aberta posterior não-silábica): 'der' [deːɐ̯], 'mehr' [meːɐ̯], 'Vater' [ˈfaːtɐ]. Apenas em ataque silábico /r/ realiza-se como uvular [ʁ]: 'rot' [ʁoːt], 'fahren' [ˈfaːʁən]."
      - "[ʔ] glotal."
      - "Não realizado (silente)."
    correct: 1
    explanation: "Distribuição /r/ em DE padrão: ataque silábico → uvular [ʁ] (rot, sehr [zeːɐ̯] — atenção: 'sehr' tem r em coda → [ɐ̯]); coda silábica + final de palavra → vocal [ɐ̯]. Em sufixo -er final → schwa-r [ɐ]: 'Vater' [ˈfaːtɐ], 'Kinder' [ˈkɪndɐ]. Apenas em registros gehoben (canto operístico, declamação clássica) ou regional (sul) o /r/ trinado [r] aparece."
---

# 01-08, Phonetik & Phonologie

## 1. Sprachliches Problem

A pronúncia alemã é frequentemente apresentada a aprendizes como "fácil" (oposto da francesa). É enganoso. O alemão tem ~16 vogais (vs. 5 em PT), distinção sistemática de **Quantität** (Länge), Auslautverhärtung obrigatória, Knacklaut em todo Vokal-Anlaut, distribuição alofônica [ç]/[x], realização vocálica de /r/ em coda, Schwa-Reduktion massiva em -en final.

Sem este módulo:
- Você pronuncia `lieb` como [liːb] (em vez de [liːp]) — Auslautverhärtung ignorada.
- Você funde `mit Eltern` em [mɪˈtɛltɐn] (em vez de [mɪt ˈʔɛltɐn]) — Knacklaut omitido.
- Você diz `Bach` [bax] como [baç] — alofone errado.
- Você pronuncia `lesen` [ˈleːzən] em vez de [ˈleːzn̩] — Schwa-Reduktion não aplicada.
- Você produz [ʁ] uvular em todos os contextos, inclusive coda — `Vater` errado em [ˈfaːtʁ̩] em vez de [ˈfaːtɐ].

Cada um desses traços é diagnóstico imediato de não-nativo. Internalizá-los é precondição para Stage 2+.

---

## 2. Harte Theorie

### 2.1 IPA — inventário fonético do alemão padrão

#### Vokale

DE distingue 16 monóftongos + 3 diftongos:

| IPA | Exemplo | Tipo |
|---|---|---|
| **i:** | Liebe [ˈliːbə] | longa, tensa, fechada |
| **ɪ** | Lippe [ˈlɪpə] | curta, frouxa, fechada |
| **e:** | Leben [ˈleːbn̩] | longa, tensa, semi-fechada |
| **ɛ** | Bett [bɛt] | curta, frouxa, semi-aberta |
| **ɛ:** | Mädchen [ˈmɛːtçən] (gehoben) | longa frontal aberta (recuo em fala moderna; muitos nativos têm [eː] aqui) |
| **a:** | Vater [ˈfaːtɐ] | longa, central baixa |
| **a** | Mann [man] | curta, central baixa |
| **o:** | rot [ʁoːt] | longa, tensa, semi-fechada arredondada |
| **ɔ** | Stock [ʃtɔk] | curta, frouxa, semi-aberta arredondada |
| **u:** | Buch [buːx] | longa, tensa, fechada arredondada |
| **ʊ** | Mutter [ˈmʊtɐ] | curta, frouxa, fechada arredondada |
| **y:** | grün [ɡʁyːn] | longa, tensa, fechada frontal arredondada |
| **ʏ** | Glück [ɡlʏk] | curta, frouxa, fechada frontal arredondada |
| **ø:** | schön [ʃøːn] | longa, tensa, semi-fechada frontal arredondada |
| **œ** | Köln [kœln] | curta, frouxa, semi-aberta frontal arredondada |
| **ə** | bitte [ˈbɪtə] | schwa, central neutro (átono) |
| **ɐ** | Vater [ˈfaːtɐ] (sufixo -er) | r-átono / r-vocal |

Diftongos: [aɪ̯] (Eis), [aʊ̯] (Haus), [ɔɪ̯] (heute, Häuser).

#### Konsonanten (resumo)

Oclusivas: /p, b, t, d, k, ɡ/.
Fricativas: /f, v, s, z, ʃ, ʒ, ç, x, h, ʁ/.
Nasais: /m, n, ŋ/.
Líquidas: /l, ʁ/ (ataque) / [ɐ̯] (coda).
Affricatas: /pf, ts, tʃ/.

### 2.2 Vokalquantität — distinção sistemática

DE distingue **vogais longas vs. curtas** com **alteração simultânea de qualidade** (tensa vs. frouxa):

| Curta (frouxa) | Longa (tensa) | Par mínimo |
|---|---|---|
| ɪ | iː | bitten [ˈbɪtn̩] / bieten [ˈbiːtn̩] |
| ɛ | eː | Wetter [ˈvɛtɐ] / Weht-er |
| a | aː | Stadt [ʃtat] / Staat [ʃtaːt] |
| ɔ | oː | offen [ˈʔɔfn̩] / Ofen [ˈʔoːfn̩] |
| ʊ | uː | Mutter [ˈmʊtɐ] / Mut-er |
| ʏ | yː | Glück [ɡlʏk] / Tür [tyːɐ̯] |
| œ | øː | können [ˈkœnən] / Söhne [ˈzøːnə] |

Ortografia indica frequentemente o comprimento:
- **Vogal longa**: dupla vogal (`Boot, Saal, See`); silent-h depois (`Bahn, sehen, ihn`); vogal antes de consoante simples + sílaba final em -e (`Tage, Liebe, machen`).
- **Vogal curta**: dupla consoante depois (`Mann, Bett, Mutter, müssen`).

Heurística não-fail-safe; existem exceções (`Stadt` é curta apesar de ortografia simples; `Mond` é longa apesar de pareça consoante simples).

### 2.3 Auslautverhärtung

**Regra fonológica obrigatória**: oclusivas vozeadas /b, d, g/ devozeiam para /p, t, k/ em **fim de sílaba** (Auslaut).

```
Tag           [taːk]      ← /tag/ + Auslautverhärtung
Tage          [ˈtaːɡə]    ← /g/ em ataque silábico, sem mudança

Hund          [hʊnt]      ← /hʊnd/ + Auslautverhärtung
Hunde         [ˈhʊndə]    ← /d/ em ataque, sem mudança

lieb          [liːp]      ← /liːb/ + Auslautverhärtung
Liebe         [ˈliːbə]    ← /b/ em ataque, sem mudança

gibt          [ɡiːpt]     ← /ɡiːb/ + /t/ flexional; /b/ em coda → [p]
gibst         [ɡiːpst]    ← idem

zog           [tsoːk]     ← /ʦoːg/ + Auslautverhärtung
zog-en        [ˈʦoːɡn̩]   ← /g/ em ataque, sem mudança
```

Adicionar sufixo (`-e, -en, -er`) **resilabifica** a consoante para ataque, **desfazendo** a Auslautverhärtung.

Nota: ortografia preserva a forma "subjacente" (com b/d/g) — a regra é puramente fonológica. Por isso `Tag` se escreve com `g` mas se diz com [k].

### 2.4 Knacklaut (oclusiva glotal [ʔ])

**Regra fonotática obrigatória**: vogais em **início de palavra** ou em **início de morfema** após fronteira recebem [ʔ] silente.

```
Apfel              [ˈʔapfl̩]
Eltern             [ˈʔɛltɐn]
in Eltern          [ɪn ˈʔɛltɐn]      (não fundindo: *[ɪˈnɛltɐn])
beobachten         [bəˈʔoːbaxtn̩]    (entre be- e -obachten)
Verein             [fɛɐ̯ˈʔaɪ̯n]      (entre Ver- e -ein)
sich erinnern      [zɪç ʔɛɐ̯ˈʔɪnɐn]
```

**Função fonotática**: marca fronteira morfo-silábica. Sem [ʔ], `mit Eltern` se confundiria com `Mittel-tern`. O Knacklaut é a fronteira audível.

Aprendizes PT/EN frequentemente omitem [ʔ] (PT/EN não têm Knacklaut sistemático), produzindo fusões que soam "moles" / não-nativas.

### 2.5 Schwa [ə] e Schwa-Reduktion

**Schwa** [ə] é a vogal átona neutra. Aparece exclusivamente em **sílabas átonas**, especialmente em sufixos:

```
bitte         [ˈbɪtə]
Liebe         [ˈliːbə]
Bruder        [ˈbʁuːdɐ]    (sufixo -er → [ɐ], schwa-r)
Vater         [ˈfaːtɐ]     (idem)
```

**Schwa-Reduktion** em -en final: o schwa é **dropado**, e /n/ assume o papel de núcleo silábico [n̩].

```
lesen         [ˈleːzn̩]    (em fala normal; [ˈleːzən] em fala lenta)
machen        [ˈmaxn̩]
gehen         [ˈɡeːn̩]
sind          [zɪnt]
```

Após /b, p, m/, assimilação: /n/ → [m̩].

```
haben         [ˈhaːbm̩]
leben         [ˈleːbm̩]
oben          [ˈʔoːbm̩]
```

Após /g, k/, assimilação: /n/ → [ŋ̩].

```
backen        [ˈbakŋ̍]
sagen         [ˈzaːɡŋ̍]    (sul/coloquial)
```

A ausência de Schwa-Reduktion (pronunciar `lesen` como [ˈleːzən] em fala normal) soa pedante / não-nativo. Para aprendizes, **forçar a reduction é parte do shadowing essencial**.

### 2.6 [ç] (ich-Laut) vs. [x] (ach-Laut) — distribuição alofônica

Os dois são **alofones** do fonema /x/, em **complementação distribucional**:

| Após | Realização | Exemplo |
|---|---|---|
| Vogal frontal (/i, e, ɛ, y, ø, œ/) | [ç] | ich [ʔɪç], echt [ʔɛçt], Bücher [ˈbyːçɐ], höchst [høːçst] |
| Vogal traseira (/a, o, u, aʊ̯/) | [x] | Bach [bax], doch [dɔx], Buch [buːx], Frauchen [ˈfʁaʊ̯çən] (— exceção: -chen sempre [ç]) |
| Consoante | [ç] | manche [ˈmançə], welche [ˈvɛlçə] |
| Após consoante final ou em ataque | [ç] | China [ˈçiːna] (nordeste); Chemie [çeˈmiː] |
| Diminutivo -chen | [ç] sempre | Mädchen [ˈmɛːtçən], Bäumchen [ˈbɔɪ̯mçən] |

Não há pares mínimos onde [ç]/[x] contrastam (são alofones, não fonemas).

Diagnóstico: olhar para a vogal **imediatamente anterior**. Vogal frontal → [ç]; traseira → [x]; após consoante / em diminutivo → [ç].

### 2.7 /r/ — distribuição alofônica

| Posição | Realização | Exemplo |
|---|---|---|
| Ataque silábico (antes de vogal) | [ʁ] uvular | rot [ʁoːt], fahren [ˈfaːʁən], drei [dʁaɪ̯] |
| Coda silábica final / após vogal longa | [ɐ̯] vocal | mehr [meːɐ̯], wir [viːɐ̯], hier [hiːɐ̯] |
| Sufixo -er final | [ɐ] schwa-r | Vater [ˈfaːtɐ], Kinder [ˈkɪndɐ] |
| Antes de consoante | varia entre [ʁ] e [ɐ̯] regional | Werk [vɛʁk] ou [vɛɐ̯k] |

Em registros gehoben (canto operístico, declamação clássica) e regional sul, /r/ trinado [r] aparece. Em DE padrão moderno, [ʁ] uvular em ataque + [ɐ̯] vocal em coda é norma neutra.

Aprendizes lusófonos: cuidado para não usar [ɾ] (tep alveolar de "barata") — é desviante em DE.

### 2.8 Wortakzent

Padrões de acentuação em DE:

#### Komposita: acento na **primeira** raíz

```
Áutobahn         [ˈʔaʊ̯toˌbaːn]
Brótbäcker       [ˈbʁoːtˌbɛkɐ]
Lébensmittel     [ˈleːbənsˌmɪtl̩]
```

#### Verben com prefixos

- Trennbar (acento no prefixo): áufstehen, ánkommen, áuslesen.
- Untrennbar (acento no Stamm): verstéhen, bekómmen, erfáhren.

#### Empréstimos do latim/grego

Frequentemente acento na sílaba penúltima ou antepenúltima:

```
Universität       [ʔunivɛʁziˈtɛːt]      (acento final)
Politik           [poliˈtiːk]            (acento final)
Phänoménologie   [fɛnomenoloˈɡiː]       (acento final)
Demokratíe       [demokʁaˈtiː]          (acento final)
Telefón           [teleˈfoːn]            (acento final)
```

#### Substantivos germânicos

Acento na primeira sílaba (raiz):

```
Vater             [ˈfaːtɐ]
Mutter            [ˈmʊtɐ]
Kindergarten      [ˈkɪndɐˌɡaʁtn̩]
```

### 2.9 Plurizentrik fonética

| Variedade | Diferenças notáveis |
|---|---|
| **Bundesdeutsch (norte)** | [ʁ] uvular padrão; [aː] mais aberta; -ig final = [ɪç] (König [ˈkøːnɪç]) |
| **Bundesdeutsch (sul)** | [r] alveolar mais frequente; -ig final pode ser [ɪɡ] |
| **Österreichisch** | [r] alveolar; vogais em geral mais abertas; entonação distinta |
| **Schweizer Hochdeutsch** | [r] frontal; vogais com qualidade distinta; entonação cantante |
| **Schweizerdeutsch (Mundart)** | sistema fonológico distinto — não Hochdeutsch |

Para Sprachprüfungen (Goethe, TestDaF), modelo é **Bundesdeutsch nördliche-mittlere Norm** (rádio Tagesschau, Deutschlandfunk).

### 2.10 Diagnóstico — checklist auditivo

Ouvir-se gravando e checar:

1. **Auslautverhärtung**: `Hund` é [hʊnt]?
2. **Knacklaut**: `die Ecke` tem [ʔ] entre artigo e Ecke?
3. **Schwa-Reduktion**: `lesen` é [ˈleːzn̩] (não [ˈleːzən])?
4. **[ç] vs [x]**: `ich` é [ʔɪç] e `Buch` é [buːx]?
5. **/r/ em coda**: `Vater` é [ˈfaːtɐ] (não [ˈfaːtʁ̩])?
6. **Vokalquantität**: `Stadt` [ʃtat] ≠ `Staat` [ʃtaːt]?
7. **Wortakzent em Komposita**: `Áutobahn` (acento primeiro)?

Se 2+ falhas: shadowing diário 15 min com Tagesschau + Goethe-Deklamation (recursos no §6).

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se, **sem consultar**:

1. Transcrever foneticamente em IPA 8 palavras autênticas (e.g., *Liebe, Mädchen, Buch, sehr, Vater, beobachten, gewusst, Universität*).
2. Aplicar **Auslautverhärtung** em 5 pares (Stamm-Stamm+sufixo: *Tag/Tage, lieb/Liebe, ...*).
3. Identificar **Knacklaut** em 3 expressões (palavra com vogal-Anlaut, palavra composta com fronteira morfológica, fronteira de palavra).
4. Diferenciar [ç] e [x] em 6 palavras dadas, justificando pela vogal anterior.
5. Realizar /r/ em **3 contextos** (ataque, coda final, sufixo -er) com IPA correto.
6. Reproduzir **Schwa-Reduktion + assimilação** em 4 verbos no Inf. (*haben, lesen, sagen, kommen*).
7. Distinguir **Vokalquantität** em 4 pares mínimos (*Stadt/Staat, bitten/bieten, offen/Ofen, Mann/Bann*).
8. Marcar acento em 6 palavras: 2 Komposita germânicas, 2 verbos com prefixo (trennbar + untrennbar), 2 empréstimos latinos.

---

## 4. Sprachliche Aufgabe

### Material 1: Tagesschau

Selecionar **5 minutos** de Tagesschau atual (https://www.tagesschau.de/multimedia/sendung/) e transcrever foneticamente em IPA **as primeiras 30-50 palavras**.

### Material 2: Declamação clássica

**Goethe — *Erlkönig*** (1782). Declamar (após ouvir gravação modelo, e.g., declamação clássica em Deutsche Welle ou Goethe-Stiftung), gravar-se, e analisar a própria declamação.

> *"Wer reitet so spät durch Nacht und Wind?  
> Es ist der Vater mit seinem Kind;  
> Er hat den Knaben wohl in dem Arm,  
> Er faßt ihn sicher, er hält ihn warm."*

### Tarefa

Análise escrita, **600–1000 palavras** em PT-BR.

1. **Transcrição IPA**: as 30-50 palavras da Tagesschau, marcadas com IPA detalhado.
2. **Auslautverhärtung detectada**: identificar **toda ocorrência** no material.
3. **Knacklaut detectado**: idem.
4. **[ç]/[x] no material**: distribuição.
5. **Schwa-Reduktion no material**: identificar ocorrências e marcar quando o falante reduziu vs. preservou.
6. **/r/ no material**: classificar realizações ([ʁ], [ɐ̯], [ɐ]) e justificar pela posição.
7. **Auto-análise da declamação do Erlkönig**: gravar e ouvir-se com o checklist §2.10. Identificar **3 falhas próprias** mais graves e propor exercício corretivo (qual som/qual contexto/quantos minutos de shadowing por dia).

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **01-03 Verbalsystem**: Auslautverhärtung interage com flexão verbal (`gibt` [ɡiːpt] vs `geben` [ˈɡeːbm̩]).
- **01-04 Nominalflexion**: Plural/Sg. de muitos substantivos depende de manifestação fonética (resyllabification).
- **01-05 Pronominalsystem**: pronomes átonos (Wackernagel) sofrem reduções fonéticas em fala (`hab' ich` [ˈhaːp ʔɪç]).
- **01-06 Wortbildung**: fronteiras morfológicas em Komposita são marcadas por Knacklaut em Vokal-Anlaut do segundo elemento.
- **01-09 Grundwortschatz**: Anki cards devem incluir IPA quando pronúncia não-óbvia.
- **02-01 Subordination**: prosódia distingue Hauptsatz/Nebensatz audicialmente.
- **04-01 Historische Linguistik**: muitas regras fonéticas modernas (Auslautverhärtung documentada desde Mhd.) são heranças.
- **04-03 Variationslinguistik**: Plurizentrik fonética é tópico próprio.
- **PT comparativo**: PT-BR não tem Knacklaut, distingue mal Vokalquantität, tem /r/ velar/uvular variável; aprender DE é re-treinar ouvido + aparelho fonatório.

---

## 6. Quellen

### Manuais

1. **Hall, Christopher** — *Modern German Pronunciation*. 2. ed. Manchester UP, 2003. **Manual canônico para aprendizes anglo-saxões.**
2. **Kohler, Klaus J.** — *Einführung in die Phonetik des Deutschen*. 2. Aufl. E. Schmidt, 1995.
3. **Wiese, Richard** — *The Phonology of German*. Oxford UP, 1996. **Tratado fonológico definitivo.**
4. **Kleiner, Stefan / Knöbl, Ralf** — *Duden, Bd. 6: Das Aussprachewörterbuch*. 7. Aufl. 2015. **Dicionário de pronúncia normativa.**
5. **Krech, Eva-Maria et al.** — *Deutsches Aussprachewörterbuch*. De Gruyter, 2009.

### IDS-Grammis

- **https://grammis.ids-mannheim.de/** — buscar "Phonetik", "Phonologie", "Auslautverhärtung", "Knacklaut".

### Recursos de prática (shadowing)

- **Tagesschau** — https://www.tagesschau.de — gravações + transcrição.
- **Deutschlandfunk** — https://www.deutschlandfunk.de — alta qualidade de pronúncia padrão.
- **Goethe-Stiftung Aussprache-Tools** — https://www.goethe.de/lhr/prj/aoz/index.htm
- **Forvo** — https://forvo.com/languages/de — pronúncia palavra-a-palavra por nativos.

### Texto primário (para declamação)

- **Goethe, Johann Wolfgang von** — *Erlkönig* (1782). Edição: Hamburger Ausgabe.
- **Schiller, Friedrich** — *Die Bürgschaft, Die Glocke* (similar uso pra prosódia clássica).

---

**Próximo módulo:** [01-09 Grundwortschatz](01-09-grundwortschatz.md), prereq `01-04`.
