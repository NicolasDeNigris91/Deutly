---
module: 04-08
title: Korpuslinguistik — DWDS, COSMAS II, kollokationsbasierte Analyse
stage: system
prereqs: [04-02]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
quiz:
  - q: "Quais os 2 corpora centrais para análise empírica do alemão?"
    options:
      - "Apenas DWDS."
      - "**(1) DWDS (Digitales Wörterbuch der deutschen Sprache; Berlin-Brandenburgische Akademie)**: corpora diacrônicos (Kernkorpus 18-21, ZeitungsKorpus, ReferenzKorpus, BlogKorpus) + Wortprofil + Etymologie. **(2) COSMAS II (Corpus Search, Management and Analysis System; IDS Mannheim)**: maior corpus DE; DEReKo (Deutsches Referenzkorpus, 50+ bilhões de palavras). Ambos são **referência mundial** para análise empírica DE."
      - "Variação dialetal."
      - "Apenas históricos."
    correct: 1
    explanation: "DWDS (https://www.dwds.de) e COSMAS II (https://cosmas2.ids-mannheim.de) são as duas grandes infraestruturas para Korpuslinguistik DE. DWDS oferece interface mais acessível, integração lexicográfica (Wörterbuch + Korpus), Wortprofil canônico para Kollokationen. COSMAS II é maior corpus, requer registro institucional, queries mais avançadas (Anfragesyntax COSMAS). Capstone-4 = aplicação operacional de ambos."
  - q: "Que método estatístico DWDS-Wortprofil usa para identificar Kollokationen significativas?"
    options:
      - "Frequência simples."
      - "**Log-Dice**: medida de associação que pondera frequência conjunta (de palavra-alvo + palavra-companheira) por frequências individuais, identificando combinações **estatisticamente preferenciais** acima de chance. Alternativas: Mutual Information (MI), t-score, Log-Likelihood. Log-Dice é robusto a viés de frequência baixa. DWDS-Wortprofil mostra Kollokationen ranqueadas por log-Dice."
      - "Variação dialetal."
      - "Apenas frequência."
    correct: 1
    explanation: "Métodos de associação estatística: Log-Dice (Rychlý 2008) é robusto e standard em DWDS-Wortprofil. Outros: MI (Church/Hanks 1990), t-score, Log-Likelihood (Dunning 1993). Log-Dice ranqueia Kollokationen acima de chance — distingue 'bittere Enttäuschung' (preferencial) de 'große Enttäuschung' (frequente mas menos diagnóstica). Capstone-4 = usar Wortprofil com leitura crítica de Log-Dice."
  - q: "Em análise diacrônica do *Begriff* via DWDS-Kernkorpus, que **3 dimensões** se rastreiam?"
    options:
      - "Apenas frequência."
      - "**(1) Frequenzverlauf (curva de frequência ao longo de Zeitbänder); (2) Kollokationsprofil (mudança de Kollokationen preferenciais entre Zeitbänder, refletindo Bedeutungsverschiebung); (3) Belegkontext (citações representativas em contexto, com fontes documentadas).** Combinação dessas 3 dimensões = análise diacrônica empírica robusta. Aplicação: Begriffsgeschichte koselleckiana com aparelho computacional."
      - "Variação dialetal."
      - "Apenas teórica."
    correct: 1
    explanation: "Begriffsanalyse korpusbasiert (Capstone-4) opera 3 dimensões: (1) Frequenzverlauf — gráfico de frequência por Zeitband (1750-1800, 1800-1850, ..., 2000-2025); (2) Kollokationsprofil dinâmico — quais palavras co-ocorriam em cada Zeitband? Mudança = Bedeutungsverschiebung; (3) Belegkontext — citações específicas com fontes (autor, obra, ano, página). Combinadas, oferecem evidência empírica para análise diacrônica koselleckiana."
  - q: "**TüBa-D/Z** (Tübingen Baumbank des Deutschen / Zeitungskorpus) é distintivo porque..."
    options:
      - "Variação dialetal."
      - "**Corpus sintaticamente anotado (TreeBank) com análise sintática manual**. Não apenas tokens; cada frase tem árvore sintática anotada (constituintes, relações dependenciais, função sintática). Permite buscar **estruturas sintáticas específicas** (e.g., 'todos os AcI com sehen como verbo principal'; 'todos os Doppelinfinitive em Nebensätze'). Recurso central para Generative Syntax empírica em DE."
      - "Apenas Zeitung."
      - "Variação ortográfica."
    correct: 1
    explanation: "TüBa-D/Z (Universität Tübingen) é um Treebank — corpus sintaticamente anotado. Diferente de corpora de texto bruto (DWDS, COSMAS): aqui cada frase tem análise sintática manual (constituintes, dependências, funções). Permite queries estruturais. Outros Treebanks DE: TIGER-Corpus (Saarland/Stuttgart), NEGRA. Recursos para análise gerativa empírica + linguística computacional."
  - q: "Em CAPSTONE-4 (korpusbasierte Begriffsanalyse), qual o output mínimo esperado?"
    options:
      - "Apenas teoria."
      - "**~30 páginas com: (1) Forschungsfrage; (2) Methode (corpora, queries, ferramentas); (3) Ergebnisse — tabelas Frequenzverlauf, top Kollokationen por Zeitband, gráficos; (4) Diskussion — Begriffsgeschichtliche Einordnung, Bedeutungsverschiebung, kontrastive Notiz PT-DE; (5) Anhang — tabelas brutas, scripts de Anfrage, Belege selecionados.** Volume: ~10-15 páginas analíticas + anexos."
      - "Variação dialetal."
      - "Apenas leitura."
    correct: 1
    explanation: "CAPSTONE-4 spec: análise empírica diacrônica do *Begriff* via DWDS-Kernkorpus 18-21 (+ COSMAS II opcional). Estrutura canônica: Forschungsfrage + Methode + Ergebnisse (gráficos, tabelas) + Diskussion (Begriffsverschiebung à la Koselleck) + Anhang. Output filológico-empírico ~30 páginas. Constitui v3 do Erkenntnisprojekt — passo decisivo na maturação do estudo."
---

# 04-08, Korpuslinguistik — DWDS, COSMAS II, kollokationsbasierte Analyse

## 1. Sprachliches Problem

Korpuslinguistik = **análise empírica do alemão baseada em grandes corpora textuais**. Resolve a questão central: o que dizem os falantes nativos **de fato**, não apenas o que gramáticas prescrevem? Aplicada a Begriffsanalyse: como Begriffe **mudam** ao longo de séculos? Capstone-4 depende deste módulo.

Aprendizes adultos travam em:

- **Argumentar etymologia / Bedeutung por intuição**: ignorar evidência empírica.
- **Não dominar DWDS / COSMAS II**: não saber operar queries.
- **Não interpretar Kollokationsprofile**: tratar Kollokationen como decoração.
- **Não integrar diacrônico + sincrônico**: separar Begriffsgeschichte de Frequenzanalyse.

Sem este módulo, **CAPSTONE-4** é inviável; pesquisa em germanística empírica fica fora de alcance.

---

## 2. Harte Theorie

### 2.1 Corpora centrais para análise DE

#### DWDS (Berlin-Brandenburgische Akademie der Wissenschaften)

URL: https://www.dwds.de

**Subcorpora**:
- **Kernkorpus 18** (1700-1800): textos selecionados séc. XVIII.
- **Kernkorpus 19** (1800-1900): séc. XIX.
- **Kernkorpus 20** (1900-2000): séc. XX.
- **Kernkorpus 21** (2000-presente): séc. XXI.
- **ZeitungsKorpora** (Berliner Zeitung, Tagesspiegel, ZEIT, FAZ, NZZ).
- **BlogKorpus**.
- **Web-Korpora** (Internet-DE).
- **DTA** (Deutsches Textarchiv): textos pré-1900 com transcrição precisa.

**Tools**:
- **Wortprofil**: Kollokationsanalyse Log-Dice.
- **Etymologie online**: Pfeifer integrado.
- **DWDS-Wörterbuch**: léxico moderno.
- **DWDB-Grimm**: léxico histórico.

#### COSMAS II (IDS Mannheim)

URL: https://cosmas2.ids-mannheim.de (acesso registrado)

**DEReKo (Deutsches Referenzkorpus)**: maior corpus DE público, 50+ bilhões de palavras (jornais, livros, web, transcrições orais).

**Anfragesyntax COSMAS**:
```
&Aufklärung      (busca lema, todas as formas flexionadas)
"Aufklärung"     (busca palavra exata)
$l = Aufklärung  (lema, equivalente a &Aufklärung)
@(durch+Aufklärung)  (Kollokationen específicas)
...
```

#### TüBa-D/Z (Tübingen Treebank)

Corpus sintaticamente anotado (TreeBank) com análise manual. Permite queries estruturais (X-bar, dependências). Recurso para Generative Syntax empírica.

#### Outros corpora DE relevantes

- **NEGRA** (Saarland): Treebank.
- **TIGER** (Stuttgart-Saarland): Treebank maior.
- **Falko** (HU Berlin): corpus de aprendizes DaF (interlíngua).
- **Wenker-Atlas / DiWA**: corpora dialectais históricos.

### 2.2 DWDS-Wortprofil — análise kollokationsbasiert

#### Workflow

1. Acessar https://www.dwds.de/wp.
2. Inserir Lemma (e.g., 'Aufklärung').
3. DWDS retorna **Kollokationen ranqueadas por log-Dice** organizadas em tipos sintáticos:
   - **als Subjekt** (Verbo + Aufklärung como Subj.).
   - **als Akkusativ-Objekt** (Verbo + Aufklärung als Akk-Obj.).
   - **als Genitivattribut** (substantivos modificados por Aufklärung-Gen.).
   - **als Präpositionalobjekt** (verbos com Präp + Aufklärung).
   - **als Modifikator** (Adj. modificando Aufklärung).
   - **als Kompositum-Bestandteil** (Aufklärungs-X, X-Aufklärung).

#### Exemplo: Aufklärung — top Kollokationen (sintetizado)

```
Adjetivos modificadores:   politische, sexuelle, kritische, dialektische, 
                            europäische, bürgerliche, historische
Verbos com Aufklärung-Akk: leisten, betreiben, fordern, brauchen, bringen
Verbos com Aufklärung-Subj: erfolgen, geschehen, mangeln, fehlen
Präpositional:             zur Aufklärung beitragen, im Sinne der Aufklärung
Komposita:                  Aufklärungsbedarf, Aufklärungskampagne, Aufklärungsfilm,
                            Aufklärungspflicht, Aufklärungsbewegung, Aufklärungszeitalter
```

#### Análise de Bedeutungsverschiebung via Kollokationen

Comparar Kollokationen **entre Zeitbänder**:

```
Aufklärung em Kernkorpus 18 (séc. XVIII):
   - bürgerliche Aufklärung, philosophische Aufklärung, Aufklärungsbewegung
   - Verbund com Vernunft, Mündigkeit, Verstand, Toleranz

Aufklärung em Kernkorpus 21 (séc. XXI):
   - politische Aufklärung, sexuelle Aufklärung, Aufklärungsbedarf
   - Verbund com Information, Klarheit, Transparenz, Whistleblower
```

Mudança: de Begriff filosófico-político (séc. XVIII) para termo administrativo-informacional (hoje). **Bedeutungsverschiebung** documentada empiricamente.

### 2.3 Frequenzanalyse diacrônica

#### Workflow

1. DWDS → Frequenzanalyse.
2. Inserir Lemma.
3. Visualizar **Frequenzverlauf** ao longo de Zeitbänder (frequência relativa por milhões de palavras).
4. Identificar **picos, vales, tendências**.
5. Correlacionar com eventos históricos (Aufklärung-Bewegung séc. XVIII; Aufklärung-Begriff revisitado anos 1990 com Habermas; etc.).

#### Exemplo (Aufklärung sintetizado)

```
Frequência relativa por século:

Séc. XVII:       baixíssima (Begriff ainda emergente).
Séc. XVIII:      pico inicial em ~1750-1800 (Aufklärungsbewegung).
Séc. XIX:        moderada-alta (Aufklärung historizada).
Séc. XX (início): moderada (categoria histórica).
Séc. XX (60-80s): pico secundário (Habermas, Frankfurter Schule).
Séc. XXI:         frequência sustentada, com expansão para 'sexuelle Aufklärung', etc.
```

### 2.4 Anwendung em Begriffsanalyse — Capstone-4

#### Pipeline

1. **Selecionar Begriff** (cf. CAPSTONE-1).
2. **DWDS Frequenzanalyse**: Frequenzverlauf ao longo de Zeitbänder.
3. **DWDS Wortprofil**: Kollokationen contemporâneas + por Zeitband (se disponível).
4. **DWDS Belegsuche**: extrair 30+ citações representativas por Zeitband, com fontes documentadas.
5. **Análise comparativa**: Bedeutungsverschiebung via mudança em Kollokationen + Belege.
6. **Begriffsgeschichtliche Einordnung**: dialogar com Koselleck, Brunner/Conze, HWP (Ritter).
7. **Kontrastive Notiz PT-DE**: como o Begriff DE traduz/não-traduz em PT? (cf. 04-09).

#### Output em CAPSTONE-4

```
1. Forschungsfrage
2. Methode (corpora, ferramentas, queries específicas)
3. Ergebnisse:
   3.1 Frequenzverlauf (gráficos)
   3.2 Top-Kollokationen por Zeitband (tabelas)
   3.3 Belegkontext (excerpts representativos)
4. Diskussion:
   4.1 Begriffsgeschichtliche Einordnung
   4.2 Bedeutungsverschiebung diagnosticada
   4.3 Kontrastive Notiz PT-DE
5. Schluss + Ausblick
6. Anhang: tabelas brutas, scripts, Belege selecionados completos
```

### 2.5 Métodos estatísticos centrais

#### Log-Dice (Rychlý 2008)

```
log-Dice(w_target, w_companion) = 14 + log₂(2*f(w_target ∧ w_companion) / (f(w_target) + f(w_companion)))
```

Interpretação: log-Dice > ~7 indica Kollokation forte; > ~10 muito forte.

#### Mutual Information (MI; Church/Hanks 1990)

```
MI(w_target, w_companion) = log₂(P(w_target ∧ w_companion) / (P(w_target) * P(w_companion)))
```

Sensível a low-frequency events; pode hipersuperestimar Kollokationen raras.

#### Log-Likelihood (Dunning 1993)

Mais robusto a frequência baixa; usado em alguns sistemas (Sketch Engine, alguns DWDS-Modus).

### 2.6 Diagnóstico — pipeline de Korpuslinguistik

Para query empírica:

1. **Definir pergunta**: o que quero saber?
2. **Selecionar corpus** apropriado (Kernkorpus diacrônico? ZeitungsKorpus sincrônico? Treebank sintático?).
3. **Construir query**: lema, palavra, contexto, ressorts sintáticos.
4. **Coletar dados**: frequenzanalyse + Wortprofil + Belege.
5. **Análise estatística**: log-Dice, MI, frequência relativa.
6. **Interpretação**: Bedeutungsverschiebung, mudança discursiva, evidência tipológica.
7. **Documentar**: fontes, método, queries (replicabilidade).

---

## 3. Schwelle der Meisterschaft

Você passa o Konzeptuelles Tor se:

1. Aplica **DWDS-Wortprofil** para 4 Lemmata distintos, listando top-5 Kollokationen de cada.
2. Aplica **DWDS-Frequenzanalyse** para 2 Lemmata, interpretando Frequenzverlauf diacrônico.
3. Diferencia **DWDS / COSMAS II / TüBa-D/Z** com casos de uso distintos.
4. Aplica **log-Dice** com 3 Kollokationen ranqueadas, interpretando significância.
5. Constrói **query Anfragesyntax COSMAS** simples.
6. Mapeia **Bedeutungsverschiebung** de 1 Begriff via comparação Zeitband-Kollokationen.
7. Extrai **5+ Belegkontext** com fontes documentadas (autor, obra, ano, página).
8. Esboço de **Capstone-4 Methode** seção (1 página).

---

## 4. Sprachliche Aufgabe

### Material

**DWDS Wortprofil** + **Kernkorpus 18-21** para o *Begriff* escolhido (CAPSTONE-1).

### Tarefa

Análise escrita, **800-1200 palavras** em PT-BR.

1. **Workflow DWDS**: documentar passo-a-passo a análise do *Begriff*: queries, telas, dados extraídos.
2. **Frequenzanalyse**: gráfico de Frequenzverlauf 1700-2025 (5 Zeitbänder). Interpretação histórica.
3. **Kollokationsprofile diacrônicos**: top-10 Kollokationen para 3 Zeitbänder (séc. XVIII, séc. XX inicial, séc. XXI). Comparação.
4. **Bedeutungsverschiebung diagnosticada**: identificar 3 mudanças significativas via Kollokationen-Vergleich.
5. **Belegkontext**: extrair 10 citações representativas, com autor, obra, ano. 3 por Zeitband.
6. **Komposita-Familie**: mapear 5 Komposita centrais com *Begriff* (Aufklärungsbewegung, Aufklärungspflicht, etc.). Cada um documentado em DWDS.
7. **Métodos críticos**: discutir limitações de DWDS (cobertura, viés de seleção, métodos estatísticos). Análise crítica de Log-Dice.
8. **Esboço Capstone-4 Methode**: estrutura preliminar de seção metodológica para o futuro Capstone.

Após terminar, peça o **Praktisches Tor**.

---

## 5. Erweiterungen und Verbindungen

- **04-02 Etymologie** (prereq): etymon + Bedeutungsverschiebung como aparelho complementar.
- **04-01 Historische Linguistik**: Sprachstufen como contexto temporal.
- **04-07 Textlinguistik**: Kohäsion analisável empiricamente.
- **04-09 Kontrastive Linguistik PT-DE**: corpora paralelos PT-DE.
- **04-10 Hermeneutik**: leitura filológica + evidência empírica.
- **CAPSTONE-4**: aplicação direta deste módulo.

---

## 6. Quellen

### Manuais

1. **Lemnitzer, Lothar / Zinsmeister, Heike** — *Korpuslinguistik: Eine Einführung*. 3. Aufl. Narr, 2015. **Manual canônico DE.**
2. **Scherer, Carmen** — *Korpuslinguistik*. Winter, 2014.
3. **Lüdeling, Anke / Kytö, Merja (Hg.)** — *Corpus Linguistics: An International Handbook*. 2 Bde. De Gruyter, 2008-2009.
4. **McEnery, Tony / Hardie, Andrew** — *Corpus Linguistics: Method, Theory and Practice*. Cambridge UP, 2012.

### Recursos online

- **DWDS** — https://www.dwds.de.
- **COSMAS II** — https://cosmas2.ids-mannheim.de.
- **TüBa-D/Z** — https://www.sfs.uni-tuebingen.de/ascl/ressourcen/corpora/tueba-dz.html.
- **DTA — Deutsches Textarchiv** — https://www.deutschestextarchiv.de.

### Especializada

- **Rychlý, Pavel** — "A Lexicographer-Friendly Association Score". *RASLAN* 2008. (Log-Dice introduction.)
- **Church, Kenneth / Hanks, Patrick** — "Word Association Norms, Mutual Information, and Lexicography". *Computational Linguistics* 16 (1990).
- **Dunning, Ted** — "Accurate Methods for the Statistics of Surprise and Coincidence". *Computational Linguistics* 19 (1993).

---

**Próximo módulo:** [04-09 Kontrastive Linguistik PT-DE](04-09-kontrastive-linguistik.md), prereq 04-04.
