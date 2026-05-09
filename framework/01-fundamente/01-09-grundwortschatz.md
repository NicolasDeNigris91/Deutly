---
module: 01-09
title: Grundwortschatz — strukturelle Grundvokabeln (~2000 Lemmata)
stage: fundamente
prereqs: [01-04]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Por que cards de Anki em FATHOM-Deutsch devem ser **frasais**, não palavras isoladas?"
    options:
      - "Frasal cards são mais fáceis."
      - "Palavras isoladas codificam significado **fora de contexto sintático**, gerando interlíngua. Frasal cards codificam: 1) significado em uso real; 2) Genus + Kasus do substantivo; 3) Rektion + valência do verbo; 4) Kollokationelle Passung; 5) Stilstufe. Card isolada falha em todos esses."
      - "Anki não suporta cards longas."
      - "Tradição alemã."
    correct: 1
    explanation: "Card isolada do tipo 'der Verstand → o entendimento' falha em codificar Gen.Sg. ('des Verstandes', e-Erweiterung), regência ('sich seines Verstandes bedienen'), Kollokation ('den Verstand verlieren / zur Vernunft kommen / der gesunde Menschenverstand'). Frasal card de Beleg autêntico carrega tudo isso. Ver STUDY-PROTOCOL.md §2."
  - q: "Qual o critério principal para escolher os ~2000 Lemmata do Grundwortschatz?"
    options:
      - "Listas tradicionais Goethe-Zertifikat A1+A2."
      - "**Frequência empírica em corpus** (DWDS-Kernkorpus 18-21, top 2000 Lemmata) — cobre ~85% de qualquer texto autêntico moderno. Suplementado por: vocabulário do *Begriff* escolhido (Capstone), vocabulário operacional (academic verbs, conectivos), vocabulário fonético-frequente (Modalpartikeln, pronomes)."
      - "Vocabulário coloquial."
      - "Vocabulário gehoben."
    correct: 1
    explanation: "Goethe-Listen são pedagógicas, não corpus-baseadas. DWDS-Kernkorpus oferece ranqueamento empírico — top 2000 Lemmata cobrem ~85% de qualquer texto moderno. Resto: vocabulário específico do Begriff + Modalpartikeln + conectivos lógicos. Total Anki-Deck Stage 1: ~1500 frasal cards (cobertura + redundância de Anki review)."
---

# 01-09, Grundwortschatz — strukturelle Grundvokabeln (~2000 Lemmata)

## 1. Sprachliches Problem

Vocabulário não é "lista para memorizar". É **rede semântica saturada por uso**. Aprendizes que tratam Wortschatz como lista (Duolingo-style, Goethe-listas decoradas) acumulam ~3000-5000 itens passive recall mas falham em production: tropeçam em Genus, Kasus-rektion, Kollokation, Stilstufe — porque cada palavra foi internalizada **fora de seu sistema sintático-pragmático**.

Este módulo é **metodológico** — define como se constrói o Grundwortschatz operacional, não enumera as 2000 palavras (lista exaustiva pertence ao Anki-Deck do aluno, sustentado em DWDS).

---

## 2. Methodologie

### 2.1 Frasal Cards como unidade canônica (cf. STUDY-PROTOCOL.md §2)

Princípio: **toda Anki card é uma frase**, não uma palavra.

#### Estrutura recomendada

```
FRENTE (Cloze-Style):
Aufklärung ist der Ausgang des _________ aus seiner selbstverschuldeten 
Unmündigkeit. (Kant, 1784)

VERSO:
"Menschen" — Gen.Sg. de "der Mensch" (m., N-Deklination: 
Nom. der Mensch / Akk. den Menschen / Dat. dem Menschen / Gen. des Menschen). 
Plural: die Menschen.

ETYMOLOGIE: ahd. mennisco (= "humano"). Cognato com lat. 'humanus' apenas 
indireto.

KOLLOKATIONEN: der einzelne Mensch, der moderne Mensch, der ganze Mensch, 
ein Mensch von Charakter, Mensch werden.

REGISTER: neutro/Hochsprache.
```

Cada card carrega: forma fonética (IPA opcional), gênero, paradigma flexional crítico, etymologia curta, 3-5 Kollokationen canônicas, register, e **uma frase autêntica de Beleg**.

#### Frasal cards específicos por tipo de Lemma

| Tipo | Card-Frente exemplifica |
|---|---|
| Substantivo | uso típico em frase, Gen.Sg. saliente, Kollokation |
| Verbo | flexão Prät./Part.II + Aux.; rektion (Akk./Dat./Gen.); 1 Inf./1 Pres./1 Prät./1 Part.II num pequeno paradigma |
| Adjetivo | uso atributivo + Komparativ + Superlativ; com substantivo de Kollokation típica |
| Adverbio | posição típica no MF; combina com qual tipo de frase |
| Modalpartikel | em pelo menos 2 frases distintas mostrando função pragmática |
| Konjunktor / Subjunktor | em frase que mostra Wortstellung (V2/VL) |

### 2.2 Top-2000 Lemmata DWDS-Kernkorpus 18-21

**DWDS-Kernkorpus** (Berlin-Brandenburgische Akademie der Wissenschaften) é corpus diacrônico do alemão escrito séc. XVIII-XXI. Lista ranking-frequência: https://www.dwds.de/d/glossar.

Top-100 lemmata cobrem ~50% de qualquer texto moderno; top-1000 cobrem ~75%; top-2000 cobrem ~85%. Cobertura assintótica: cada Lemma adicional contribui marginalmente menos.

Estratégia de aquisição:

```
Semana 1-2:    Top 1-200 (Funktionswörter + verbos centrais: 
               sein, haben, werden, können, müssen, gehen, kommen, sehen, 
               wissen, sprechen, machen, geben, nehmen, finden, tun, lassen, 
               denken, glauben, sagen, fragen, ... + 100 substantivos centrais)
               
Semana 3-6:    Top 201-700 (substantivos abstratos centrais, conectivos lógicos,
               adjetivos centrais, verbos de comunicação)
               
Semana 7-12:   Top 701-1500 (substantivos concretos por campo, verbos de ação)
               
Semana 13-20:  Top 1501-2000 (sufixos derivacionais produtivos, 
               vocabulário formal-acadêmico básico)
```

Suplementos paralelos:
- **Vocabulário do *Begriff*** escolhido (Capstone-1): 100-150 cards próprios, com frases canônicas dos primärquellen.
- **Modalpartikeln**: 14 cards (cf. 01-07) com 2-3 frases por partícula.
- **Pronomes**: 60 cards cobrindo paradigmas de 01-05.
- **Konjunktoren**: 30 cards (`weil, dass, wenn, obwohl, als, da, ob, bevor, sodass, indem, sofern, ...`) com frases mostrando Wortstellung.

### 2.3 Campos semânticos prioritários para Stage 1

Estruturação por **Wortfeld** (campo semântico) acelera retenção via associação:

| Wortfeld | Lemmata centrais (amostra) |
|---|---|
| **Família** | Vater, Mutter, Bruder, Schwester, Sohn, Tochter, Onkel, Tante, Großvater, Großmutter, Cousin/Cousine, Eltern, Kind, Geschwister, verheiratet, geschieden |
| **Tempo** | Jahr, Monat, Woche, Tag, Stunde, Minute, gestern, heute, morgen, jetzt, später, früher, oft, manchmal, immer, nie, zeitig, spät |
| **Lugar** | Haus, Wohnung, Stadt, Land, Straße, Platz, Bahnhof, Flughafen, Schule, Universität, Büro, Hotel, Restaurant, Kino, Park, Garten |
| **Movimento** | gehen, kommen, fahren, fliegen, laufen, springen, stehen, sitzen, liegen, ziehen, schicken, bringen, holen, treffen, ankommen, abfahren |
| **Comunicação** | sagen, sprechen, fragen, antworten, erklären, beschreiben, schreiben, lesen, hören, sehen, schauen, verstehen, glauben, denken, meinen |
| **Estados / sentimentos** | sein, werden, bleiben, fühlen, lieben, hassen, fürchten, hoffen, wünschen, freuen, ärgern, sich freuen, sich ärgern, müde, glücklich, traurig |
| **Quantidade / abstração** | Zahl, Menge, viel/wenig, mehr/weniger, einige, manche, jeder, alle, keine, etwas, nichts, alles, ein paar |
| **Conectivos lógicos** | und, oder, aber, denn, weil, obwohl, deshalb, daher, trotzdem, also, sonst, jedoch, allerdings, freilich, gleichwohl, mithin (gehoben) |
| **Modalpartikeln** | doch, ja, halt, eben, denn, mal, eigentlich, schon, aber, vielleicht, bloß, wohl |
| **Vocabulário acadêmico básico** | These, Argument, Beleg, Ursache, Wirkung, Folge, Bedeutung, Erkenntnis, Begriff, Theorie, Methode, Forschung, Analyse, Untersuchung, Kritik |

### 2.4 Kollokationen — núcleo da prática avançada

Palavra isolada ≠ uso. Kollokation = **combinação preferencial** entre palavras: `bittere Enttäuschung` (não `*saure Enttäuschung`), `harte Kritik`, `scharfer Protest`, `Vertrag schließen` (não `*machen`), `eine Rolle spielen`, `Anwendung finden`, `in Anspruch nehmen`.

Recursos:

- **DWDS Wortprofil** — https://www.dwds.de/wp — para qualquer Lemma, mostra Kollokationen ranked por co-ocorrência.
- **Wortschatz Leipzig** — https://wortschatz.uni-leipzig.de — estatística de co-ocorrência.
- **Linguee / Reverso Context** — exemplos de uso (filtrar por nativo).

Em Stage 2-3, módulos `02-09 Lexik II` e `03-03 Idiomatik und Phraseologie` sistematizam.

### 2.5 Anti-padrões a evitar

| Anti-padrão | Por quê falha |
|---|---|
| **Cards isoladas** (`Verstand → entendimento`) | Sem Genus/Gen./Kollokation/Stilstufe. Vocabulário passivo. |
| **Listas Goethe decoradas linearmente** | Não corpus-baseadas; cobertura inferior; sem hierarquia frequência. |
| **Tradução PT→DE em cada card** | Cria interlíngua. Aluno aprende a "buscar palavra DE para X PT" em vez de pensar em DE. |
| **Apenas substantivos** | Verbos de baixa frequência mas alta complexidade (rektion) ficam de fora. |
| **Ignorar Modalpartikeln** | Falar sem MP soa não-nativo desde A2. |
| **Decks de 100+ cards/dia novos** | Saturação cognitiva. Anki-Forschung: 20-40 novas/dia é máximo sustentável. |

### 2.6 Workflow diário Anki

```
06:00-06:25   Anki reviews diárias (cards due)
              ~25 min em fluxo regular após acumulação
              
21:00-21:15   15 cards novas adicionadas
              cada uma com frase autêntica + flexão crítica + Kollokation
              
Semanal (sáb. AM)  Releitura do Fehlerprotokoll dos últimos 7 dias
                   Conversão de erros em cards novos
```

Sustentabilidade: **20-40 cards novas / semana**, **15-25 min reviews / dia**. Total Stage 1: ~1500 frasal cards em 6-12 meses (depende da consistência).

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se:

1. Tem Anki deck próprio com **≥ 800 frasal cards** após Stage 1 (verificável em estatísticas Anki).
2. Cobre 6+ campos semânticos (§2.3) com 50+ cards cada.
3. Cada card no deck tem: frase autêntica + flexão crítica + Kollokation + register + (opcional) etymologia.
4. Demonstra retenção: dado um Lemma do top-200 DWDS, produz frase de uso, Genus, Gen.Sg., e 2 Kollokationen sem consultar.
5. Distingue **Kollokation correta vs. incorreta** em 5 pares (e.g., `bittere Enttäuschung` vs. `*saure Enttäuschung`).
6. Lista os **14 Modalpartikeln** com 1 exemplo de uso cada (cf. 01-07).
7. Identifica os **30 Konjunktoren / Subjunktoren mais frequentes** com classificação (koordinativ / subordinativ / kausal / temporal / konzessiv / final / konditional).
8. Tem mantido cadência ≥ 5 dias/semana de reviews por **≥ 30 dias consecutivos** (auto-disciplina mensurável).

---

## 4. Sprachliche Aufgabe

Aufgabe deste módulo é **construção do deck**, não análise textual. Critério de avaliação é **operacional**:

1. **Construir Anki deck próprio** "FATHOM-Deutsch Stage 1" com:
   - Top 200 DWDS Lemmata, cada um como frasal card.
   - 14 Modalpartikeln cards.
   - 30 Konjunktoren/Subjunktoren cards.
   - 50 cards do *Begriff* escolhido (Capstone-1).
   - 50 cards de erros próprios (do Fehlerprotokoll).
   
   Total inicial: ~344 cards.
2. **Demonstrar uso por 30 dias consecutivos** (Anki streak ≥ 30 + estatísticas verificáveis).
3. **Aplicar 10 Lemmata** do deck em **frases produzidas** (não copiadas) — testando Genus, Kasus-rektion, Kollokation simultaneamente.
4. **Auto-auditoria**: revisitar 20 cards aleatórias semanalmente; reproduzir frase + flexão + Kollokation em folha em branco. Marcar gaps.

Após 30 dias de streak + 800+ cards: requisitar **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **STUDY-PROTOCOL.md §2**: o pacote diário Anki deste módulo.
- **01-04 Nominalflexion** (prereq): cards devem incluir Genus + Plural + Gen.Sg.
- **01-03 Verbalsystem**: cards de verbos starke devem incluir Stammformen.
- **01-05 Pronominalsystem**: paradigmas pronominais como cards.
- **01-06 Wortbildung**: identificar sufixos com Genus mecânico em cada card de substantivo derivado.
- **01-07 Negation und Modalpartikeln**: 14 MP cards obrigatórias.
- **02-09 Lexik II — operationaler Wortschatz**: extensão para vocabulário de Politik/Wirtschaft/Wissenschaft (Stage 2).
- **03-03 Idiomatik und Phraseologie**: aprofundamento sistemático de Kollokationen e Phraseologismen (Stage 3).
- **03-09 Lexik III — geisteswissenschaftlicher Wortschatz**: Filosofia/Recht/Theologie (Stage 3).
- **04-02 Etymologie und Wortgeschichte**: cards passam a incluir etymologia diacrônica (Stage 4).
- **04-08 Korpuslinguistik**: análise empírica DWDS/COSMAS — cards baseados em Beleg de corpus (Stage 4).

---

## 6. Quellen

### Recursos lexicográficos

1. **DWDS** — https://www.dwds.de — dicionário + corpora + Wortprofil.
2. **Duden Online** — https://www.duden.de.
3. **DWDS-Kernkorpus 21** (frequência) — base empírica do top-2000.
4. **Wortschatz Leipzig** — https://wortschatz.uni-leipzig.de.

### Anki

- **Anki** — https://apps.ankiweb.net — desktop + mobile + sync.
- **AnkiWeb decks comunitários** — disponíveis para Goethe-Wortschatz; **servem de starter, mas você cria o seu**.
- **Documentação Anki** — https://docs.ankiweb.net.

### Métodos de Wortschatz-Erwerb

- **Tschirner, Erwin / Möhring, Jupp** — *Häufigkeitswörterbuch der deutschen Sprache: Schriftlicher und mündlicher Sprachgebrauch*. Routledge, 2019. **Frequência empírica.**
- **Niemeier, Susanne** — *Lexikalische Aspekte des Deutscherwerbs*. Stauffenburg, 2019.
- **Schmitt, Norbert** — *Researching Vocabulary*. Palgrave, 2010. (Em inglês; metodologia comparativa.)

### Frasal Cards / Sentence Mining

- **All Japanese All The Time / Migaku** — não-DE específico, mas metodologia "sentence mining" influenciou abordagens modernas.
- **Refold** — comunidade de imersão estruturada (DE como target language).

---

**Próximo:** [CAPSTONE-fundamente.md](CAPSTONE-fundamente.md) — Erkenntnisprojekt v0, integrando todos os 9 módulos do Stage 1.
