# CAPSTONE-EVOLUTION — Erkenntnisprojekt

> O Erkenntnisprojekt é o produto único que evolui em todos os 5 capstones do FATHOM-Deutsch. Ele é o análogo da *Logística* no Fathom: um único objeto sustentado, refatorado e densificado a cada estágio.

---

## Por que um Begriff?

Línguas não são listas de palavras — são redes semânticas estruturadas em torno de **Begriffe** (conceitos densos, historicamente carregados, intraduzíveis sem perda).

Investigar **um único Begriff** ao longo de toda a trilha:
- Cria continuidade pedagógica (cada estágio aprofunda o mesmo objeto).
- Constrói **Wortschatz pesado** em torno de um campo semântico real.
- Liga gramática (Stages 1–2), estilo (Stage 3), linguística e hermenêutica (Stage 4), output público (Stage 5).
- Produz, ao final, um objeto **publicável** com voz própria.

---

## Como escolher o Begriff

Critérios:

1. **Densidade filológica**: existe tradição documentada de uso erudito do termo (300+ anos).
2. **Diferença com o português**: o termo NÃO é traduzível por uma palavra única em PT (*Bildung* ≠ educação; *Geist* ≠ espírito; *Aufklärung* ≠ iluminismo simples).
3. **Interesse pessoal**: você vai conviver com esse Begriff por anos. Tem que sustentar fascínio.
4. **Disponibilidade de Primärquellen**: textos canônicos acessíveis.

Sugestões canônicas (com tradição filológica robusta):

| Begriff | Tradição | Canônicos | Por que escolher |
|---------|----------|-----------|------------------|
| **Aufklärung** | Iluminismo crítico | Kant *Was ist Aufklärung?*; Habermas *Strukturwandel der Öffentlichkeit*; Foucault *Qu'est-ce que les Lumières?*; Horkheimer/Adorno *Dialektik der Aufklärung* | Begriff político-filosófico; faz ponte com português ("Iluminismo") mas tem extensões intraduzíveis. |
| **Bildung** | Humboldt | Humboldt *Theorie der Bildung des Menschen*; Adorno *Theorie der Halbbildung* | Sem equivalente em PT; mistura formação, cultura, autoformação. Domínio educacional. |
| **Geist** | Idealismo alemão | Hegel *Phänomenologie des Geistes*; Dilthey *Aufbau der geschichtlichen Welt*; Cassirer | Begriff fundador da tradição idealista. |
| **Wahrheit** | Hermenêutica + analítica | Heidegger *Vom Wesen der Wahrheit*; Gadamer *Wahrheit und Methode*; Frege *Der Gedanke*; Tugendhat | Cruza tradições; ótimo pra contraste analítica vs. hermenêutica. |
| **Macht** | Filosofia política | Nietzsche *Wille zur Macht*; Weber *Wirtschaft und Gesellschaft*; Foucault *Surveiller et punir* (em DE: *Überwachen und Strafen*); Arendt *Macht und Gewalt* | Forte em ciência política. |
| **Sein** | Ontologia | Heidegger *Sein und Zeit* | Mais difícil; só escolha se você já lê filosofia. |
| **Sprache** | Filosofia da linguagem | Wittgenstein *Tractatus*, *Philosophische Untersuchungen*; Heidegger *Unterwegs zur Sprache*; Gadamer; Habermas *Theorie des kommunikativen Handelns* | Recursivo: você usa linguagem pra estudar linguagem. Excelente pra quem ama meta-níveis. |

Você pode escolher um *Begriff* fora desta lista, desde que documente em `Erkenntnisprojekt/wahl.md` os critérios cumpridos.

---

## Progressão v0 → v4

### v0 — Stage 1 (Fundamente): Glossar fonético-estrutural

**Saída esperada:** ~30 entries lexicográficas relacionadas ao Begriff, com:
- Lemma (com Genus, Numerus, Genitiv-Sg., Plural)
- Transcrição IPA
- Etimologia curta (1 linha — Pfeifer ou Kluge)
- Definição em alemão (1–2 frases, baseada no Duden)
- Frase de Beleg (1, do canônico primário escolhido)
- Análise topológica da frase de Beleg (Vor-/Mittelfeld/Rechte Klammer marcadas)

**Exemplo (com Begriff = Aufklärung):**

```
## Aufklärung, die

Genus, Numerus, Genitiv-Sg., Plural: f., Sg., der Aufklärung, die Aufklärungen
Aussprache: [ˈaʊ̯fˌklɛːʁʊŋ]
Etymologie: ahd. *aufkleron 'erhellen' → frnhd. 'klar machen', 18. Jh. 
            metonymisch übertragen auf den geistesgeschichtlichen Prozess.
Definition (Duden, sinnsvariant 1): "geistesgeschichtliche Bewegung des 
            17. und 18. Jahrhunderts, die im Vertrauen auf die menschliche 
            Vernunft gegen Vorurteile, Unwissenheit und Aberglauben kämpfte".
Beleg (Kant 1784): "Aufklärung ist der Ausgang des Menschen aus seiner 
            selbstverschuldeten Unmündigkeit."
Analyse: 
  | Aufklärung | ist | der Ausgang des Menschen aus seiner selbstverschuldeten 
              Unmündigkeit. |
  |    VF      | LK  |                  MF                                  | RK ∅
  Subjekt: Aufklärung. Prädikativ: der Ausgang... mit Genitivattribut "des 
  Menschen" + Präpositionalattribut "aus seiner selbstverschuldeten Unmündigkeit".
```

**Volume:** ~30 entries × 6 campos = ~180 datapoints; ~10 horas de trabalho.

---

### v1 — Stage 2 (Struktur): Argumentativer Aufsatz, 1500 Wörter

**Saída esperada:** Aufsatz argumentativo em alemão, **1500 palavras**, sobre uma tese específica relacionada ao Begriff. Estrutura canônica:

```
1. Einleitung (~150 W)        — pergunta-condutora + tese
2. Begriffsklärung (~200 W)   — definição operacional do Begriff
3. Argumentation (~500 W)     — 2–3 argumentos, cada com Beleg
4. Gegenargument (~250 W)     — antítese forte (steelmann)
5. Replik (~250 W)            — defesa da tese
6. Schluss (~150 W)           — síntese + abertura
```

**Exemplo de pergunta (Begriff = Aufklärung):**
> "Inwiefern ist Habermas' Begriff der 'kommunikativen Vernunft' eine Fortsetzung oder eine Korrektur der kantischen Aufklärung?"

**Exigências técnicas (oriundas dos módulos 02-01 a 02-09):**
- Konjunktiv I em discurso indireto (citando Habermas).
- Konjunktiv II em hipotéticos.
- 2+ Passivkonstruktionen idiomáticas.
- 2+ Funktionsverbgefüge.
- Argumentação encadeada com Subjunktoren (`indem`, `obgleich`, `sofern`, `inwiefern`, ...).

**Loop de Refinamento completo aplicado.**

---

### v2 — Stage 3 (Stil): Wissenschaftlicher Aufsatz, 5000 Wörter

**Saída esperada:** Aufsatz acadêmico em registro científico, **5000 palavras**, com Literaturverzeichnis (10–15 fontes primárias).

Estrutura:

```
1. Einleitung & Forschungsfrage (~400 W)
2. Forschungsstand (~700 W)     — revisão da literatura
3. Methodisches Vorgehen (~300 W)
4. Hauptteil (~3000 W)
   4.1 Begriffsgeschichtliche Rekonstruktion
   4.2 Hauptthese mit Argumentation
   4.3 Diskussion
5. Schluss & Ausblick (~600 W)
6. Literaturverzeichnis
```

**Exigências técnicas (oriundas dos módulos 03-01 a 03-09):**
- Nominaler Stil dominante (FVG, Substantivierung, abstrakte NPs).
- Modalpartikeln em nuance acadêmica (`durchaus`, `freilich`, `gleichwohl`, `mithin`, `indessen`).
- Stilfiguren conscientes (Hyperbaton, Chiasmus em pelo menos 2 passagens).
- Citações canônicas em DE original, com tradução PT em rodapé quando ambíguas.
- Zitiernormen acadêmicas (Chicago, MLA ou DGfS — escolha uma e mantenha).

**Loop de Refinamento + 2 rounds de revisão.**

---

### v3 — Stage 4 (System): Korpusbasierte Begriffsanalyse

**Saída esperada:** Análise empírica diacrônica do Begriff via DWDS / COSMAS II.

Saída concreta:

```
1. Forschungsfrage (1 página)
   "Wie hat sich die kollokative Umgebung des Lemmas 'Aufklärung' 
   zwischen 1750 und 2020 verschoben?"

2. Methode (1 página)
   - Korpus: DWDS-Kernkorpus 18.–21. Jh. (Disco-Korpus).
   - Anfrage: $l = Aufklärung; Zeitbänder: 1750–1800, 1800–1850, ...
   - Tools: DWDS-Wortprofil, Kollokationsanalyse via Log-Dice.

3. Ergebnisse (5–7 páginas)
   - Tabelas de top-20 Kollokationen por Zeitband.
   - Gráficos de Frequenzverlauf.
   - Análise qualitativa de mudança semântica (Begriffsverschiebung).

4. Diskussion (3–4 páginas)
   - Begriffsgeschichtliche Einordnung (Koselleck-style).
   - Crítica ao Korpus (representatividade, viés).

5. Anhang
   - Tabelas brutas, scripts de Anfrage, Belege selecionados.
```

**Exigências técnicas (oriundas dos módulos 04-01 a 04-10):**
- Domínio de DWDS / COSMAS II.
- Análise diacrônica (Begriffsgeschichte, à la Koselleck).
- Kontrastive Notiz com PT (existe Begriffsverschiebung análoga em "iluminismo"?).
- Zitate de pelo menos 1 texto Mhd. ou Frnhd. relevante (se houver Vorläufer do Begriff).

**Volume:** ~10–15 páginas + anexos. ~80–120 horas de trabalho.

---

### v4 — Stage 5 (Meisterschaft): Veröffentlichung

**Saída esperada:** Artigo publicado em revista alemã/austríaca/suíça (cultural ou acadêmica).

Veículos possíveis:

| Tipo | Exemplos |
|---|---|
| Cultural elite | *Merkur*, *Sinn und Form*, *Lettre International*, *Schreibheft* |
| Acadêmica filosófica | *Zeitschrift für philosophische Forschung*, *Deutsche Zeitschrift für Philosophie* |
| Acadêmica linguística | *Zeitschrift für Sprachwissenschaft*, *Deutsche Sprache*, *Linguistische Berichte* |
| Acadêmica germanística | *Zeitschrift für Germanistische Linguistik (ZGL)*, *Germanisch-Romanische Monatsschrift* |
| Feuilleton | FAZ-Feuilleton, NZZ-Feuilleton, *Die Zeit* (mais difícil — exige editor) |

**Estrutura:**
- Adapta v3 pra formato editorial (3000–8000 palavras dependendo do veículo).
- Submissão completa (Manuskript + Exposé + Lebenslauf).
- Revisão de editor + 1–2 rounds de revisão peer.

**Exigências técnicas (oriundas dos módulos 05-01 a 05-07):**
- *Stimme* madura, identificável.
- Domínio de Übersetzungstheorie quando citar texto em outra língua.
- Vortrag de 30 min sobre o tema (gravado, paralelo).
- 1 episódio de podcast em alemão sobre o tema.

**Não passa o capstone até** publicação aceita (ou recusa motivada por critério editorial não-linguístico).

---

## Cronograma típico (estimativa)

| Capstone | Volume | Tempo (sustentado) |
|---|---|---|
| v0, Glossar | ~30 entries | 30–60 h |
| v1, Aufsatz 1500 W | ~5–7 páginas | 40–80 h |
| v2, Wiss. Aufsatz 5000 W | ~15–20 páginas | 100–200 h |
| v3, Korpusanalyse | ~30 páginas | 150–300 h |
| v4, Veröffentlichung | ~20–30 páginas (publicado) | 200–500 h |

Total Erkenntnisprojekt: **~500–1100 horas** ao longo de 2–5 anos.

---

## Output cumulativo

Ao final do Estágio 5, você tem:
- 1 Glossar fonético-estrutural canônico do *Begriff*.
- 4 Aufsätze de profundidade crescente.
- 1 análise korpusbasiert publicável.
- 1 publicação em revista DE.
- 1 Vortrag gravado.
- 1 episódio de podcast em DE.
- 1 corpus pessoal de Anki cards saturado em torno do *Begriff*.

Isso **é** maestria do *Begriff*. E maestria do *Begriff* é a forma concreta de C2+ erudito.

---

**Fim do documento.**
