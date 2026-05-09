---
module: CAPSTONE-system
title: Erkenntnisprojekt v3 — korpusbasierte Begriffsanalyse + filologische Kritik
stage: system
prereqs: [04-01, 04-02, 04-03, 04-04, 04-05, 04-06, 04-07, 04-08, 04-09, 04-10]
gates:
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
status: locked
---

# CAPSTONE-system — Erkenntnisprojekt v3

> Quarto stage do produto encadeado do FATHOM-Deutsch. Integra os 10 módulos do Stage 4 numa **korpusbasierte Begriffsanalyse + filologische Kritik** (~30 páginas) do *Begriff* escolhido em CAPSTONE-1.

> 📋 **Template completo** com estrutura metodológica (diachrone + synchrone + hermeneutische Trias), Korpus-Auswahl, Beleg-Sammlung-Format, Diagramme (Frequenzverlauf), Kollokationstabellen, Methodenkritik: [BEGRIFFSANALYSE-TEMPLATE](../00-meta/templates/BEGRIFFSANALYSE-TEMPLATE.md).

---

## 1. Continuidade com Capstones anteriores

- **CAPSTONE-1** (Stage 1): Glossar v0 (30 entries lexicográficas).
- **CAPSTONE-2** (Stage 2): argumentativer Aufsatz v1 (1500 W).
- **CAPSTONE-3** (Stage 3): wissenschaftlicher Aufsatz v2 (5000 W) com Primärquellen.
- **CAPSTONE-4** (Stage 4): **korpusbasierte Begriffsanalyse v3** — análise empírica diacrônica + filologische Kritik (~30 páginas).

A pergunta-condutora é refinada pela trajetória; o aparelho ganha rigor empírico via DWDS/COSMAS + filológico via Pfeifer/Kluge + hermenêutico via Gadamer/Heidegger.

---

## 2. Deliverable: Korpusbasierte Begriffsanalyse (~30 páginas)

Texto científico em alemão, **~30 páginas** (~10000-12000 palavras), com aparelho empírico + filológico + hermenêutico.

### Estrutura canônica

```
1. Forschungsfrage + Tese (~1 página)              ~3-4%
   - Pergunta empírico-filológica refinada
   - Tese sobre Bedeutungsverschiebung do Begriff

2. Forschungsstand (~3 páginas)                    ~10%
   - Begriffsgeschichtliche Forschung (Koselleck, HWP, Brunner/Conze)
   - Filológica + hermenêutica (cf. autores Stage 4)
   - Empírica (corpora-Studien anteriores)

3. Methode (~2 páginas)                            ~7%
   - Korpora utilizados (DWDS-Kernkorpus 18-21 + COSMAS DEReKo opcional)
   - Anfragesyntax e queries específicas
   - Métodos estatísticos (Log-Dice, Frequenzverlauf)
   - Filológica: Pfeifer + Kluge consultados
   - Hermenêutica: Vorverständnis + autores como referência interpretativa

4. Ergebnisse (~10-12 páginas)                     ~35-40%
   4.1 Frequenzverlauf 1700-2025 (1-2 gráficos + interpretação)
   4.2 Kollokationsprofil por Zeitband (3-5 tabelas)
   4.3 Belegkontext (10-30 citações representativas, fontes documentadas)
   4.4 Análise etymologica diacrônica (Pfeifer + cadeia Idg.→Nhd.)
   4.5 Análise sintática (X-bar / Topologie em frases canônicas)
   4.6 Análise estilística (Stilfiguren em autores canônicos)

5. Diskussion (~6-8 páginas)                       ~25-27%
   5.1 Bedeutungsverschiebung diagnosticada
   5.2 Begriffsgeschichtliche Einordnung (Koselleck-Tradition)
   5.3 Hermenêutica filosófica (autores: Kant, Hegel, Heidegger, Adorno, Habermas)
   5.4 Kontrastive Notiz PT-DE (cf. 04-09)
   5.5 Crítica + auto-crítica metodológica

6. Schluss + Ausblick (~1-2 páginas)               ~5%
   - Síntese das contribuições
   - Questões abertas
   - Conexão com Stage 5 (publicação pública)

7. Literaturverzeichnis                            (anexo, não conta nas 30 pgs.)
   - 20-30 fontes primárias e secundárias
   - Zitierweise consistente

8. Anhang                                          (anexo)
   - A. Tabelas brutas DWDS (frequência, Kollokationen)
   - B. Scripts de queries (anfragesyntax)
   - C. Belege selecionados completos com fontes
   - D. Análise etymologica detalhada (cadeia Idg.→Nhd.)
```

### Exemplo de pergunta-condutora ampliada (Begriff = Aufklärung)

> "Wie hat sich das Bedeutungsspektrum des Begriffs 'Aufklärung' im DWDS-Kernkorpus zwischen 1750 und 2025 verschoben — und welche philosophisch-historischen Implikationen lassen sich daraus für die Begriffsgeschichte koselleckianischer Tradition ableiten?"

> "Inwiefern lässt sich die heideggersche Re-etymologisierung der 'Wahrheit' als Aletheia empirisch durch DWDS-Belege stützen oder problematisieren — und welche Konsequenzen folgen daraus für die hermeneutische Methodologie?"

---

## 3. Exigências técnicas

O Aufsatz deve demonstrar **uso ativo dos 10 módulos do Stage 4**.

### Filologica + Hermenêutica

- [ ] **Análise sintática integrada**: 5+ frases analisadas em Topologisches Feldermodell + X-bar (cf. 01-01 + 04-04).
- [ ] **Análise morfológica**: 10+ Komposita / Substantivierungen analisadas (cf. 01-06 + 03-09).
- [ ] **Análise etymologica**: cadeia Idg.→Nhd. para 5+ Begriffe centrais (cf. 04-02 + Pfeifer).
- [ ] **Análise estilística**: 5+ Stilfiguren identificadas em autores canônicos (cf. 03-06).
- [ ] **Hermeneutik aplicada**: hermeneutischer Zirkel + Vorverständnis + Wirkungsgeschichte explicitados (cf. 04-10).

### Empírica (DWDS/COSMAS)

- [ ] **Frequenzanalyse diacrônica**: gráfico Frequenzverlauf 1700-2025.
- [ ] **Kollokationsprofile**: top-20 Kollokationen por Zeitband (3+ Zeitbänder).
- [ ] **Belegkontext**: 30+ citações representativas com fontes documentadas (autor, obra, ano, página).
- [ ] **Análise estatística**: Log-Dice interpretado para Kollokationen relevantes.
- [ ] **Anfragesyntax documentada**: queries específicas reproduzíveis em anexo.

### Discursiva + Crítica

- [ ] **Diskursanalyse aplicada** (cf. 04-06): mapear Diskursstrang do *Begriff* em 2+ veículos.
- [ ] **Kontrastive Notiz PT-DE** (cf. 04-09): seção dedicada (~1 página).
- [ ] **Crítica metodológica**: limitações de DWDS, viés de seleção, métodos estatísticos.
- [ ] **Auto-crítica**: posicionamento autoral, Vorurteil produtivo (Gadamer), Wirkungsgeschichte da própria leitura.

### Estilística + Stage 1-3

- [ ] **Konj. I em Reportativ**: 15+ ocorrências citando Primärquellen.
- [ ] **Konj. II em hedge / irrealis**: 10+ ocorrências.
- [ ] **Stilfiguren acadêmicas**: Hyperbaton, Litotes, Chiasmus calibrados.
- [ ] **Konjunktionaladverbien acadêmicos**: 20+ distintos.
- [ ] **FVG canônicas**: 12+ distintas.
- [ ] **Topikalisierung não-default**: variação retórica em 25+ frases.

---

## 4. Construção: workflow recomendado

### Etapa 1 — Pesquisa empírica (~40-60 horas)

1. **DWDS Wortprofil sistemático** do Begriff + 5-10 Begriffe relacionados.
2. **DWDS Frequenzanalyse diacrônica** (1700-2025).
3. **Belegsuche**: extrair 50+ citações representativas; selecionar 30 melhores.
4. **COSMAS II opcional**: queries adicionais para confirmação / triangulação.

### Etapa 2 — Pesquisa filológica (~30-50 horas)

1. **Pfeifer / Kluge / DWB**: cadeia etymológica completa Idg.→Nhd. para Begriffe centrais.
2. **HWP (Ritter)**: leitura de entradas para Begriffe centrais.
3. **Geschichtliche Grundbegriffe (Brunner/Conze/Koselleck)**: Begriffsgeschichte canônica.
4. **Lexer**: para Mhd.; Lutherbibel para Frnhd. (se relevante).

### Etapa 3 — Pesquisa hermenêutica (~30-50 horas)

1. **Re-leitura de Primärquellen**: Kant, Hegel, Heidegger, Adorno, Habermas (conforme tradição do Begriff).
2. **Forschungsstand**: 10-15 artigos / livros recentes.
3. **Wirkungsgeschichte**: trajetória de recepção do Begriff.

### Etapa 4 — Esboço estrutural (~5-10 horas)

1. Esboço de 4-5 páginas com argumentação principal.
2. Distribuição em 6 seções com volume planejado.
3. Mapeamento dos 7 níveis de análise.

### Etapa 5 — Escrita do primeiro draft (~80-150 horas)

Por seção, em ordem inversa do impacto:
1. **Methode** primeiro (técnica, mais fácil).
2. **Ergebnisse** (empírica + filológica).
3. **Diskussion** (interpretativa).
4. **Forschungsstand** (síntese).
5. **Einleitung + Schluss** por último.

### Etapa 6 — Revisão Loop de Refinamento (~40-60 horas)

3 rounds completos:
1. **Grammatik + Lexikalische Präzision**.
2. **Stil + Native erudite**.
3. **Coerência argumentativa + dados empíricos verificados**.

### Etapa 7 — Submissão para Praktisches Tor

Submeter Aufsatz + Anhang. Mentor avalia segundo §5 + RUBRIC.md.

**Estimativa total: 250-400 horas** distribuídas em **6-12 meses**.

---

## 5. Critério de Avaliação (Praktisches Tor)

### Camada 1 — Grammatik

- [ ] Zero BLOCKING errors em sintaxe.
- [ ] ≤ 8 MAJOR errors em ~10000-12000 W.
- [ ] Konj. I rigoroso em Reportativ.
- [ ] X-bar / Topologie aplicada corretamente em frases analisadas.

### Camada 2 — Lexikalische Präzision

- [ ] Vocabulário Lexik III + filológico aplicado com nuance.
- [ ] Konjunktionaladverbien acadêmicos diversos (20+).
- [ ] Hedge calibrado epistemicamente (4+ níveis).
- [ ] FVG corretamente combinadas (12+).
- [ ] Termos hermenêuticos usados precisamente.

### Camada 3 — Stil

- [ ] Wissenschaftsdeutsch hoch consistente sem Stilbruch.
- [ ] Stilfiguren acadêmicas calibradas.
- [ ] Coerência discursiva (cf. 04-07).
- [ ] Citation markers + Konj. I + Zitierweise consistentes.

### Camada 4 — Empírica

- [ ] **DWDS workflow documentado** e reproduzível.
- [ ] **Dados empíricos verificáveis** (gráficos, tabelas, Belege com fontes).
- [ ] **Análise estatística adequada** (Log-Dice interpretado).
- [ ] **Belege selecionados representativamente** (não cherry-picked).

### Camada 5 — Hermenêutica

- [ ] **Hermeneutischer Zirkel** documentado (iterações).
- [ ] **Vorverständnis** explicitado.
- [ ] **Wirkungsgeschichte** integrada.
- [ ] **Horizontverschmelzung** reconhecida.
- [ ] **Posicionamento autoral** crítico.

### Begründungsfragen (8+ obrigatórias)

```
1. Por que escolheu este corpus específico (DWDS Kernkorpus vs. COSMAS DEReKo)?
2. Como justifica seu critério de seleção de Zeitbänder?
3. Como interpretou Log-Dice = X em Kollokação Y?
4. Por que cita autor A em vez de autor B em Forschungsstand?
5. Como sua leitura dialoga com a Wirkungsgeschichte do Begriff?
6. Como justifica sua escolha entre etymologia descritiva (Pfeifer) e Re-etymologisierung filosófica (Heidegger)?
7. Que Vorverständnis trouxe para a análise; como o hermeneutischer Zirkel modificou?
8. Por que aborda kontrastive PT-DE em determinada seção (e não outra)?
```

Não conseguir justificar 6+/8 = falha.

---

## 6. Output cumulativo

Ao concluir CAPSTONE-system:

- **Korpusbasierte Begriffsanalyse v3** (~30 páginas) salvo em `Erkenntnisprojekt/v3-analyse.md`.
- **Anki deck atualizado**: ~9000-10000 frasal cards, com cobertura geisteswissenschaftlich + empírica.
- **Fehlerprotokoll** atualizado.
- **PROGRESS.md** atualizado: Stage 4 marcado COMPLETED.
- **Sintese reflexiva** (2 páginas, em PT-BR + DE Lemmata): o que aprendi sobre o Begriff e sobre o sistema metalingüístico DE na construção desta análise?
- **Lista de candidatos para v4** (Stage 5): vias de publicação, public output, mentoring que emergem da análise. Stage 5 = Veröffentlichung em revista DE/AT/CH.

Você está agora **filológica + empírica + hermeneuticamente apto a publicar em germanística junior**: pode produzir Begriffsanalyse defensável, manipular DWDS/COSMAS para análise diacrônica, aplicar hermeneutik filosófica, dialogar com tradição Koselleck/Brunner/Conze, e contribuir para Forschung em Germanistik / Philosophie / kontrastive Linguistik.

---

## 7. Quellen

### Recursos lexicográficos + corpora

- **DWDS** — https://www.dwds.de.
- **COSMAS II** — https://cosmas2.ids-mannheim.de.
- **Pfeifer** — *Etymologisches Wörterbuch des Deutschen* (dtv).
- **Kluge** — *Etymologisches Wörterbuch der deutschen Sprache* (De Gruyter).
- **Mittelstraß** — *Enzyklopädie Philosophie und Wissenschaftstheorie* (Metzler).
- **Ritter** — *Historisches Wörterbuch der Philosophie* (Schwabe). 13 Bde.
- **Brunner / Conze / Koselleck** — *Geschichtliche Grundbegriffe* (Klett-Cotta). 8 Bde.
- **Lexer** — *Mittelhochdeutsches Handwörterbuch* (online: Wörterbuchnetz).
- **Grimm DWB** — *Deutsches Wörterbuch* (online: DWDS).

### Manuais

- **Lemnitzer / Zinsmeister** — *Korpuslinguistik* (cf. 04-08).
- **Esselborn-Krumbiegel** — *Von der Idee zum Text* (cf. 03-07).
- **Steinhoff** — *Wissenschaftliche Textkompetenz* (cf. 03-07).
- **Gadamer** — *Wahrheit und Methode* (cf. 04-10).

### Veículos de publicação acadêmica

- *Zeitschrift für philosophische Forschung* (DZPhil).
- *Deutsche Zeitschrift für Philosophie*.
- *Mittelweg 36* (Hamburger Institut für Sozialforschung).
- *Zeitschrift für Sprachwissenschaft (ZfS)*.
- *Zeitschrift für Germanistische Linguistik (ZGL)*.
- *Begriffsgeschichte / Conceptual History* (Brill).

### RUBRIC.md

- Cf. framework/00-meta/RUBRIC.md para critérios estruturados.

---

**Status:** LOCKED. Desbloqueia após os 10 módulos do Stage 4 com 3 Tore cada concluídos.

**Próximo Stage:** [Stage 5 — Meisterschaft](../05-meisterschaft/README.md) (a construir).
