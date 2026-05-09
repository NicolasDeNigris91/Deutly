---
module: CAPSTONE-fundamente
title: Erkenntnisprojekt v0 — Glossar fonético-estrutural do Begriff
stage: fundamente
prereqs: [01-01, 01-02, 01-03, 01-04, 01-05, 01-06, 01-07, 01-08, 01-09]
gates:
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
status: locked
---

# CAPSTONE-fundamente — Erkenntnisprojekt v0

> Primeiro stage do produto encadeado do FATHOM-Deutsch. Este Capstone integra os 9 módulos do Stage 1 num único deliverable: o **Glossar fonético-estrutural** do *Begriff* escolhido.

---

## 1. Pré-condição: escolha do *Begriff*

Antes de começar este Capstone, registrar em PROGRESS.md (na seção "Erkenntnisprojekt escolhido") o *Begriff* + justificativa.

Sugestões canônicas (cf. CAPSTONE-EVOLUTION.md):
- *Aufklärung* (Iluminismo) — Kant, Habermas, Foucault, Horkheimer/Adorno
- *Bildung* (formação intelectual-cultural) — Humboldt, Schleiermacher, Adorno
- *Geist* (espírito) — Hegel, Dilthey, Cassirer
- *Wahrheit* (verdade) — Heidegger, Gadamer, Frege
- *Macht* (poder) — Nietzsche, Foucault, Weber, Arendt
- *Sein* (ser) — Heidegger
- *Sprache* (linguagem) — Wittgenstein, Heidegger, Gadamer, Habermas

Critério: existe tradição filológica documentada (300+ anos), o termo NÃO é traduzível por palavra única em PT, há Primärquellen acessíveis, e o tema sustenta interesse de longo prazo.

Você pode escolher fora desta lista, desde que documente em `Erkenntnisprojekt/wahl.md` os critérios cumpridos.

---

## 2. Deliverable: 30 entries lexicográficas

O Glossar v0 tem **30 entries** — cada uma um Lemma do campo semântico do *Begriff* (incluindo o próprio *Begriff* + Komposita + cognatos + termos relacionados).

### Composição mínima das 30 entries

| Tipo | Quantidade | Exemplo (com Begriff = Aufklärung) |
|---|---|---|
| O *Begriff* central | 1 | *Aufklärung* |
| Komposita do *Begriff* | 5 | *Aufklärungsphilosophie, Aufklärungszeitalter, Selbstaufklärung, Aufklärungsschrift, Aufklärungsdialektik* |
| Cognatos / sinônimos parciais | 4 | *Erleuchtung, Erläuterung, Erkenntnis, Vernunft* |
| Antônimos | 3 | *Unmündigkeit, Aberglaube, Vorurteil* |
| Termos centrais da tradição | 10 | *Verstand, Vernunft, Mut, Mündigkeit, selbstverschuldet, Leitung, Öffentlichkeit, Kritik, Räsonnement, Mündigkeit* |
| Verbos centrais | 4 | *aufklären, sich bedienen, gebrauchen, sich emanzipieren* |
| Adjetivos centrais | 3 | *aufgeklärt, mündig, kritisch* |

Total: ~30. Pode ajustar proporção, mas cobertura mínima dos 7 tipos é exigida.

### Schema da entry lexicográfica

Cada entry contém **9 campos**, em ordem fixa:

```markdown
## <Lemma>, <Genus|Klasse>

**Aussprache (IPA):** [...]

**Flexão:** Genus, Numerus, Genitiv-Sg., Plural (ou Konj.: Inf., 3.Sg.Prät., Part.II, Hilfsverb)

**Etymologie (1 linha):** ahd./mhd./lat./gr. → significado-base → significado moderno

**Definition (1-2 frases, Hochsprache, ≈ Duden):** definição operacional usada nos primärquellen

**Beleg (1 frase canônica):** uma frase de Primärquelle (Kant, Hegel, Habermas, ...) onde o Lemma aparece

**Topologische Analyse do Beleg:** marcar VF / LK / MF / RK / NF + identificar Kasus + flexão das partes relevantes

**Kollokationen:** 3-5 combinações canônicas (consultar DWDS-Wortprofil)

**Stilstufe:** neutro / Wissenschaftsdeutsch / gehoben / Bürokratendeutsch / coloquial

**Verweise:** ligações com outras entries do glossário e textos primários
```

### Exemplo de entry completa (Begriff = Aufklärung)

```markdown
## Aufklärung, die (f., -en)

**Aussprache (IPA):** [ˈʔaʊ̯fˌklɛːʁʊŋ]

**Flexão:** f., Sg./Pl.: Genitiv-Sg. = der Aufklärung, Plural = die Aufklärungen

**Etymologie:** ahd. *uf-kleron "esclarecer, iluminar (à luz)" → frnhd. "klar machen, 
erläutern" → 18. Jh. metonymisch: a movimento intelectual-político iluminista. Sufixo 
-ung formaliza Substantivierung de aufklären (separável: auf+klären).

**Definition (Duden, sinnvariante 1):** "Geistesgeschichtliche Bewegung des 17. und 
18. Jahrhunderts, die im Vertrauen auf die menschliche Vernunft gegen Vorurteile, 
Unwissenheit und Aberglauben kämpfte; geistige Verfassung, die durch Vernunftgebrauch 
sich aus selbstverschuldeter Unmündigkeit befreien will."

**Beleg (Kant 1784):** "Aufklärung ist der Ausgang des Menschen aus seiner 
selbstverschuldeten Unmündigkeit."

**Topologische Analyse do Beleg:**
| Aufklärung | ist | der Ausgang des Menschen aus seiner selbstverschuldeten 
Unmündigkeit. |
|     VF     | LK  |                          MF                                | 
RK ∅ | NF ∅
- Subjekt: Aufklärung (Nom.Sg.f.)
- Prädikativ: der Ausgang... (NP, Nom.Sg.m.) com Genitivattribut "des Menschen" 
  (Gen.Sg.m. — N-Deklination!) + Präpositionalattribut PP[aus + Dat]: "aus seiner 
  selbstverschuldeten Unmündigkeit" (Dat.Sg.f.; Adj. gemischt -en)

**Kollokationen:** der Aufklärung dienen, die Dialektik der Aufklärung (Adorno/
Horkheimer), die Rückseite/Schattenseite der Aufklärung, eine kritische Aufklärung, 
das Erbe der Aufklärung

**Stilstufe:** neutro/Wissenschaftsdeutsch (em uso filosófico-histórico); 
Aufklärung pode ser uso coloquial pra "esclarecimento" geral, e.g., 
"Aufklärung über Drogen" = informação preventiva.

**Verweise:** Unmündigkeit, Vernunft, Verstand, Mut, Kritik, kritische Theorie, 
selbstverschuldet
```

---

## 3. Construção: workflow recomendado

### Etapa 1 — Listar 30 Lemmata candidatos (~3-5 horas)

1. Reler o(s) Primärquelle do *Begriff* (Kant, *Was ist Aufklärung?*; ou Humboldt, *Theorie der Bildung des Menschen*; etc.).
2. Sublinhar cada Lemma central encontrado.
3. Triagem por relevância: ~30 mais densos.
4. Confronto com DWDS-Wortprofil pra identificar Komposita relevantes não cobertos.

### Etapa 2 — Preencher cada entry (~30 minutos cada × 30 = ~15 horas)

Para cada Lemma, percorrer os 9 campos:

1. **IPA**: consultar Duden Aussprachewörterbuch ou DWDS.
2. **Flexão**: consultar Duden online + DWDS.
3. **Etymologie**: Pfeifer (1 linha apenas; síntese, não tratado).
4. **Definition**: Duden online (cuidar para não copy-paste — sintetizar com palavras próprias).
5. **Beleg**: extrair de Primärquelle com cuidado (página + edição).
6. **Topologische Analyse**: aplicar 01-01.
7. **Kollokationen**: DWDS-Wortprofil filtra ranked.
8. **Stilstufe**: Duden + intuição calibrada por leitura intensiva.
9. **Verweise**: links internos do glossário.

### Etapa 3 — Auditoria (~3-5 horas)

1. Verificar consistência: todos seguem o schema?
2. Verificar completude: 7 tipos cobertos?
3. Verificar qualidade da Topologische Analyse: amostragem aleatória de 5 entries; refazer análise sem consultar e comparar.
4. Refazer Belege com más escolhas (frase muito curta, ambígua, ou pouco representativa).

### Etapa 4 — Submissão para Praktisches Tor

Submeter o Glossar completo + indicar onde está hospedado (repo `Erkenntnisprojekt/`, separado de `Deutly/`). Mentor avalia segundo §4.

**Estimativa de tempo total: 25-50 horas** distribuídas em ~4-8 semanas (1-2 entries/dia + revisão).

---

## 4. Critério de Avaliação (Praktisches Tor)

Aplicação da RUBRIC.md ao Glossar:

### Camada 1 — Grammatik

- [ ] **Topologische Analyse correta** em 30/30 Belege (fronteiras VF/LK/MF/RK/NF; Kasus identificados).
- [ ] **Flexão completa e correta** em 30/30 entries (Genus, Numerus, Genitiv-Sg., Plural, ou Konj. para verbos).
- [ ] **N-Deklination** identificada onde aplicável (e.g., `Mensch, Held, Bote, Polizist, ...`).

### Camada 2 — Lexikalische Präzision

- [ ] **Definition** sintetizada com nuance (não plagiada do Duden).
- [ ] **Kollokationen** corretas e filtradas por relevância (não as primeiras 3 do DWDS, mas as 3-5 que iluminam o uso filosófico do termo).
- [ ] **Stilstufe** identificada com correção (saber distinguir uso filosófico de uso coloquial em pelo menos 5 entries).

### Camada 3 — Stil

- [ ] **Belege escolhidos com critério**: frase curta o suficiente para análise, longa o suficiente para mostrar contexto. Tirada de Primärquelle (não de paráfrase secundária).
- [ ] **Etymologia concisa** (1 linha cada). Não-tratado, não-fragmentária.
- [ ] **Verweise pertinentes** (não apenas listagem mecânica).

### Camada 4 — Native Erudite

- [ ] O Glossar como um todo **coere** como objeto unitário (não 30 itens isolados, mas mapa do *Begriff* como rede semântica).
- [ ] Cobertura representativa do **campo semântico** completo (Komposita + cognatos + antônimos + tradição + verbos + Adj.).

### Begründungsfragen (após correções)

```
1. Por que escolheu este Beleg específico de Kant em vez do parágrafo seguinte?
2. Em "des Menschen", por que N-Dekl. e não regular Gen.?
3. Por que classificou "Aufklärung" como neutro em alguns contextos e Wissenschaftsdeutsch em outros?
4. Por que esta Kollokation aparece em DWDS-Wortprofil mas você não a incluiu?
5. Como você diferenciaria entre "Aufklärung" e "Erleuchtung" num texto novo?
```

Não conseguir justificar 3+/5 = falha.

---

## 5. Output cumulativo

Ao concluir CAPSTONE-fundamente:

- **30 entries lexicográficas** salvas em `Erkenntnisprojekt/v0-glossar.md`.
- **Anki deck atualizado** com cada Lemma e Beleg correspondente (50-60 cards adicionados).
- **PROGRESS.md** atualizado: Stage 1 marcado COMPLETED.
- **Sintese reflexiva** (1 página, em PT-BR + DE Lemmata): o que aprendi sobre o *Begriff* e sobre o sistema gramatical alemão na construção deste Glossar?
- **Lista de candidatos para v1** (Stage 2): perguntas/teses que emergem do Glossar e que serão exploradas no argumentativen Aufsatz (1500 W) do CAPSTONE-2.

Você está agora **estruturalmente armado** para Stage 2: pode decompor sintaticamente, justificar Kasus, conjugar verbos starke, flexionar adjetivos, ler densamente.

---

## 6. Quellen

- Os Primärquellen do *Begriff* escolhido (cf. READING-LIST.md).
- DWDS Wortprofil (https://www.dwds.de/wp).
- Pfeifer, *Etymologisches Wörterbuch des Deutschen* (dtv).
- Duden, Bd. 6: *Das Aussprachewörterbuch*.
- Eisenberg, Helbig/Buscha, Engel para Topologie e flexão.
- Edições canônicas dos primärquellen (Suhrkamp, Klostermann, Akademieausgabe, Reclam).

---

**Status:** LOCKED. Desbloqueia após os 9 módulos do Stage 1 com 3 Tore cada concluídos.

**Próximo Stage:** [Stage 2 — Struktur](../02-struktur/README.md) (a construir).
