# DAG — Pré-requisitos visualizados

> Mapa visual de dependências entre módulos. Renderizado nativamente em GitHub via Mermaid.
>
> **Convenções gráficas:**
> - **Caixas com bordas arredondadas** = módulos regulares.
> - **Caixas com bordas duplas** = Capstones (Erkenntnisprojekt v0-v4).
> - **Caixas pontilhadas** = módulos paralelos (sem prereqs estritos).
> - **Setas sólidas** = pré-requisito intra-Stage.
> - **Setas tracejadas** = pré-requisito cross-Stage.
> - **Caixas em cor distinta por Stage** = camada do framework.

Pré-requisitos extraídos de [INDEX.md](INDEX.md). Para detalhe textual, cf. cada módulo + Stage README.

---

## Mapa global cross-Stage (caminho crítico)

```mermaid
flowchart LR
    classDef stage1 fill:#e8f3ff,stroke:#0a4d8c,color:#0a2540
    classDef stage2 fill:#fff4e6,stroke:#a04a00,color:#3a1a00
    classDef stage3 fill:#f0f8e6,stroke:#3a6b00,color:#1a2a00
    classDef stage4 fill:#fff0f5,stroke:#7a0050,color:#2a001a
    classDef stage5 fill:#f5f0ff,stroke:#3a0a8c,color:#1a0040
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S1["Stage 1 — FUNDAMENTE<br/>(10 Module)"]:::stage1
    S2["Stage 2 — STRUKTUR<br/>(9 Module)"]:::stage2
    S3["Stage 3 — STIL<br/>(10 Module)"]:::stage3
    S4["Stage 4 — SYSTEM<br/>(10 Module)"]:::stage4
    S5["Stage 5 — MEISTERSCHAFT<br/>(7 Module)"]:::stage5
    S6A["Stage 6 Track A<br/>ÜBERSETZUNG<br/>(6 Module + Capstone)"]:::stage5
    S6B["Stage 6 Track B<br/>FORSCHUNG<br/>(7 Module + Capstone)"]:::stage5
    S6C["Stage 6 Track C<br/>FACHSPRACHE<br/>(C1: 4 + C2: 3 + C3: 3 Module<br/>+ 3 Capstones)"]:::stage5
    S6D["Stage 6 Track D<br/>MENTORING + DaF<br/>(6 Module + Capstone)"]:::stage5

    C1[["CAPSTONE-1<br/>Glossar v0"]]:::capstone
    C2[["CAPSTONE-2<br/>Aufsatz 1500 W"]]:::capstone
    C3[["CAPSTONE-3<br/>Aufsatz 5000 W"]]:::capstone
    C4[["CAPSTONE-4<br/>Begriffsanalyse korpusbasiert"]]:::capstone
    C5[["CAPSTONE-5<br/>Veröffentlichung"]]:::capstone
    C6A[["CAPSTONE-6-A<br/>Publizierte Buchübersetzung"]]:::capstone
    C6B[["CAPSTONE-6-B<br/>Promotion-Beginn"]]:::capstone
    C6C[["CAPSTONE-6-C1/2/3<br/>Fachsprache-Praxis<br/>(Recht/Medizin/Technik)"]]:::capstone
    C6D[["CAPSTONE-6-D<br/>Eigene DaF-Praxis"]]:::capstone

    S1 --> C1 --> S2 --> C2 --> S3 --> C3 --> S4 --> C4 --> S5 --> C5
    C5 -.-> S6A --> C6A
    C5 -.-> S6B --> C6B
    C5 -.-> S6C --> C6C
    C5 -.-> S6D --> C6D
```

> **Spezialisierungs-Tracks** Stage 6 sind optional + parallel post-CAPSTONE-5. Alle 4 Tracks (A + B + C + D) v2.5 vollständig implementiert.

---

## Stage 1 — FUNDAMENTE

```mermaid
flowchart LR
    classDef base fill:#e8f3ff,stroke:#0a4d8c,color:#0a2540
    classDef parallel fill:#fafafa,stroke:#888888,color:#333333,stroke-dasharray: 5 3
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    M0101["01-01<br/>Syntaktische Analyse"]:::base
    M0102["01-02<br/>Kasussystem"]:::base
    M0103["01-03<br/>Verbalsystem I"]:::base
    M0104["01-04<br/>Nominalflexion"]:::base
    M0105["01-05<br/>Pronominalsystem"]:::base
    M0106["01-06<br/>Wortbildung I"]:::base
    M0107["01-07<br/>Negation + MP"]:::base
    M0108["01-08<br/>Phonetik"]:::parallel
    M0109["01-09<br/>Grundwortschatz"]:::base
    M0110["01-10<br/>Konversation"]:::parallel
    C1[["CAPSTONE-1<br/>Glossar v0"]]:::capstone

    M0101 --> M0102
    M0101 --> M0103
    M0102 --> M0104
    M0102 --> M0105
    M0104 --> M0105
    M0104 --> M0106
    M0104 --> M0109
    M0101 --> M0107
    M0103 --> M0107
    M0108 -.-> M0110

    M0102 --> C1
    M0103 --> C1
    M0104 --> C1
    M0105 --> C1
    M0106 --> C1
    M0107 --> C1
    M0108 --> C1
    M0109 --> C1
    M0110 --> C1
```

> **Konvention:** 01-10 (Konversation) ist parallel und erfordert Tandem-Praxis (Modus B); 01-08 (Phonetik) ist Voraussetzung lautlich (gepunktet), aber kein hartes Prereq.

---

## Stage 2 — STRUKTUR

```mermaid
flowchart LR
    classDef base fill:#fff4e6,stroke:#a04a00,color:#3a1a00
    classDef cross fill:#e8f3ff,stroke:#0a4d8c,color:#0a2540,stroke-dasharray: 4 2
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S1_0101["01-01"]:::cross
    S1_0103["01-03"]:::cross
    S1_0109["01-09"]:::cross

    M0201["02-01<br/>Subordination"]:::base
    M0202["02-02<br/>Konjunktiv I"]:::base
    M0203["02-03<br/>Konjunktiv II"]:::base
    M0204["02-04<br/>Passivkonstruktionen"]:::base
    M0205["02-05<br/>Infinitivsätze"]:::base
    M0206["02-06<br/>Funktionsverbgefüge"]:::base
    M0207["02-07<br/>Modalverben"]:::base
    M0208["02-08<br/>Topik-Fokus"]:::base
    M0209["02-09<br/>Lexik II"]:::base
    C2[["CAPSTONE-2<br/>Aufsatz 1500 W"]]:::capstone

    S1_0101 -.-> M0201
    S1_0103 -.-> M0201
    S1_0103 -.-> M0204
    S1_0103 -.-> M0207
    S1_0101 -.-> M0208
    S1_0109 -.-> M0209

    M0201 --> M0202
    M0201 --> M0203
    M0201 --> M0205
    M0204 --> M0206

    M0201 --> C2
    M0202 --> C2
    M0203 --> C2
    M0204 --> C2
    M0205 --> C2
    M0206 --> C2
    M0207 --> C2
    M0208 --> C2
    M0209 --> C2
```

---

## Stage 3 — STIL

```mermaid
flowchart LR
    classDef base fill:#f0f8e6,stroke:#3a6b00,color:#1a2a00
    classDef cross fill:#fff4e6,stroke:#a04a00,color:#3a1a00,stroke-dasharray: 4 2
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S2_0206["02-06"]:::cross
    S2_0207["02-07"]:::cross
    S2_0209["02-09"]:::cross

    M0301["03-01<br/>Nominal vs. verbal"]:::base
    M0302["03-02<br/>Register"]:::base
    M0303["03-03<br/>Idiomatik"]:::base
    M0304["03-04<br/>Pragmatik"]:::base
    M0305["03-05<br/>Modalpartikeln"]:::base
    M0306["03-06<br/>Stilfiguren"]:::base
    M0307["03-07<br/>Wissenschaftl. Schreiben"]:::base
    M0308["03-08<br/>Journalistischer Stil"]:::base
    M0309["03-09<br/>Lexik III"]:::base
    M0310["03-10<br/>Hörverstehen colloquial"]:::base
    C3[["CAPSTONE-3<br/>Aufsatz 5000 W"]]:::capstone

    S2_0206 -.-> M0301
    S2_0209 -.-> M0302
    S2_0209 -.-> M0303
    S2_0209 -.-> M0309
    S2_0207 -.-> M0304
    S2_0207 -.-> M0305

    M0301 --> M0306
    M0301 --> M0307
    M0302 --> M0308
    M0302 --> M0310
    M0304 --> M0310
    M0305 --> M0310

    M0301 --> C3
    M0302 --> C3
    M0303 --> C3
    M0304 --> C3
    M0305 --> C3
    M0306 --> C3
    M0307 --> C3
    M0308 --> C3
    M0309 --> C3
    M0310 --> C3
```

> **Konvention:** 03-10 (Hörverstehen colloquial) konsolidiert Register (03-02), Pragmatik (03-04) und Modalpartikeln (03-05) in der Rezeption; cross-link an 01-08 Phonetik + 01-10 Konversation für Aussprache-Internalisierung.

---

## Stage 4 — SYSTEM

```mermaid
flowchart LR
    classDef base fill:#fff0f5,stroke:#7a0050,color:#2a001a
    classDef cross fill:#f0f8e6,stroke:#3a6b00,color:#1a2a00,stroke-dasharray: 4 2
    classDef cross2 fill:#fff4e6,stroke:#a04a00,color:#3a1a00,stroke-dasharray: 4 2
    classDef cross1 fill:#e8f3ff,stroke:#0a4d8c,color:#0a2540,stroke-dasharray: 4 2
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S1_0101["01-01"]:::cross1
    S1_0106["01-06"]:::cross1
    S2_0208["02-08"]:::cross2
    S3_0302["03-02"]:::cross
    S3_0307["03-07"]:::cross
    S3_0308["03-08"]:::cross
    S3_0309["03-09"]:::cross

    M0401["04-01<br/>Historische Linguistik"]:::base
    M0402["04-02<br/>Etymologie"]:::base
    M0403["04-03<br/>Variationslinguistik"]:::base
    M0404["04-04<br/>Generative Syntax"]:::base
    M0405["04-05<br/>Formale Semantik"]:::base
    M0406["04-06<br/>Diskursanalyse"]:::base
    M0407["04-07<br/>Textlinguistik"]:::base
    M0408["04-08<br/>Korpuslinguistik"]:::base
    M0409["04-09<br/>Kontrastive Linguistik"]:::base
    M0410["04-10<br/>Hermeneutik"]:::base
    C4[["CAPSTONE-4<br/>Begriffsanalyse"]]:::capstone

    S1_0106 -.-> M0401
    S3_0309 -.-> M0401
    S3_0302 -.-> M0403
    S1_0101 -.-> M0404
    S2_0208 -.-> M0404
    S3_0309 -.-> M0405
    S3_0308 -.-> M0406
    S3_0307 -.-> M0407
    S3_0309 -.-> M0410

    M0401 --> M0402
    M0402 --> M0408
    M0404 --> M0409
    M0404 --> M0410

    M0401 --> C4
    M0402 --> C4
    M0403 --> C4
    M0404 --> C4
    M0405 --> C4
    M0406 --> C4
    M0407 --> C4
    M0408 --> C4
    M0409 --> C4
    M0410 --> C4
```

---

## Stage 5 — MEISTERSCHAFT

```mermaid
flowchart LR
    classDef base fill:#f5f0ff,stroke:#3a0a8c,color:#1a0040
    classDef cross fill:#fff0f5,stroke:#7a0050,color:#2a001a,stroke-dasharray: 4 2
    classDef cross3 fill:#f0f8e6,stroke:#3a6b00,color:#1a2a00,stroke-dasharray: 4 2
    classDef parallel fill:#fafafa,stroke:#888888,color:#333333,stroke-dasharray: 5 3
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S3_0307["03-07"]:::cross3
    S3_0308["03-08"]:::cross3
    S4_0406["04-06"]:::cross
    S4_0409["04-09"]:::cross
    S4_0410["04-10"]:::cross

    M0501["05-01<br/>Politische Sprache"]:::base
    M0502["05-02<br/>Wissenschaftssprache"]:::base
    M0503["05-03<br/>Übersetzungstheorie"]:::base
    M0504["05-04<br/>Eigene Stimme"]:::base
    M0505["05-05<br/>Public Output"]:::base
    M0506["05-06<br/>Mentoring"]:::parallel
    M0507["05-07<br/>Goethe C2 (opt.)"]:::parallel
    C5[["CAPSTONE-5<br/>Veröffentlichung"]]:::capstone

    S4_0406 -.-> M0501
    S4_0410 -.-> M0502
    S4_0409 -.-> M0503
    S3_0307 -.-> M0504
    S3_0308 -.-> M0504

    M0504 --> M0505

    M0501 --> C5
    M0502 --> C5
    M0503 --> C5
    M0504 --> C5
    M0505 --> C5
    M0506 --> C5
```

---

## Stage 6 Track A — ÜBERSETZUNGSWISSENSCHAFT + PRAXIS

```mermaid
flowchart LR
    classDef base fill:#fce4ec,stroke:#a3185f,color:#3a0a30
    classDef cross fill:#f5f0ff,stroke:#3a0a8c,color:#1a0040,stroke-dasharray: 4 2
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S5_0503["05-03"]:::cross

    M0A1["06-A-1<br/>Übersetzungstheorie<br/>vertieft"]:::base
    M0A2["06-A-2<br/>Literarische<br/>Übersetzung"]:::base
    M0A3["06-A-3<br/>Philosophische<br/>Übersetzung"]:::base
    M0A4["06-A-4<br/>Juristische<br/>Übersetzung"]:::base
    M0A5["06-A-5<br/>Kulturwiss.<br/>Übersetzung"]:::base
    M0A6["06-A-6<br/>Lektorat<br/>+ Redaktion"]:::base
    C6A[["CAPSTONE-6-A<br/>Publizierte Buchübersetzung"]]:::capstone

    S5_0503 -.-> M0A1
    M0A1 --> M0A2
    M0A1 --> M0A4
    M0A2 --> M0A3
    M0A3 --> M0A5
    M0A2 --> M0A6
    M0A3 --> M0A6

    M0A1 --> C6A
    M0A2 --> C6A
    M0A3 --> C6A
    M0A4 --> C6A
    M0A5 --> C6A
    M0A6 --> C6A
```

---

## Stage 6 Track B — GERMANISTISCHE FORSCHUNG (Promotion-Vorbereitung)

```mermaid
flowchart LR
    classDef base fill:#e0f2f1,stroke:#00695c,color:#003a30
    classDef cross fill:#fff0f5,stroke:#7a0050,color:#2a001a,stroke-dasharray: 4 2
    classDef cross5 fill:#f5f0ff,stroke:#3a0a8c,color:#1a0040,stroke-dasharray: 4 2
    classDef capstone fill:#fffacd,stroke:#806000,color:#332400,stroke-width:3px

    S4_C4["CAPSTONE-4"]:::cross
    S5_0502["05-02"]:::cross5

    M0B1["06-B-1<br/>Forschungsfrage-<br/>Entwicklung"]:::base
    M0B2["06-B-2<br/>Wissenschaftl.<br/>Schreiben spez."]:::base
    M0B3["06-B-3<br/>Konferenz-<br/>Praxis"]:::base
    M0B4["06-B-4<br/>Akademisches<br/>Netzwerk"]:::base
    M0B5["06-B-5<br/>Promotions-<br/>antrag"]:::base
    M0B6["06-B-6<br/>Drittmittel<br/>+ Forsch.-Praxis"]:::base
    M0B7["06-B-7<br/>Habilitation<br/>(optional)"]:::base
    C6B[["CAPSTONE-6-B<br/>Promotion-Beginn"]]:::capstone

    S5_0502 -.-> M0B1
    S4_C4 -.-> M0B1

    M0B1 --> M0B2
    M0B2 --> M0B3
    M0B3 --> M0B4
    M0B1 --> M0B5
    M0B4 --> M0B5
    M0B5 --> M0B6
    M0B6 --> M0B7

    M0B1 --> C6B
    M0B2 --> C6B
    M0B3 --> C6B
    M0B4 --> C6B
    M0B5 --> C6B
    M0B6 --> C6B
    M0B7 --> C6B
```

---

## Caminhos críticos cross-Stage

### Caminho A — Sintaxe → Generative → Hermenêutica

```mermaid
flowchart LR
    classDef path fill:#fffacd,stroke:#806000,color:#332400,stroke-width:2px

    A1["01-01<br/>Topologisches<br/>Feldermodell"]:::path
    A2["02-08<br/>Topik-Fokus"]:::path
    A3["04-04<br/>Generative Syntax"]:::path
    A4["04-10<br/>Hermeneutik"]:::path
    A5["05-02<br/>Wissenschaftssprache"]:::path

    A1 --> A2 --> A3 --> A4 --> A5
```

Sem este caminho dominado, leitura de Heidegger / Hegel / Habermas é tateamento.

### Caminho B — Lexik → Register → Diskursanalyse

```mermaid
flowchart LR
    classDef path fill:#fffacd,stroke:#806000,color:#332400,stroke-width:2px

    B1["01-09<br/>Grundwortschatz"]:::path
    B2["02-09<br/>Lexik II"]:::path
    B3["03-02<br/>Register"]:::path
    B4["03-08<br/>Journalistischer Stil"]:::path
    B5["04-06<br/>Diskursanalyse"]:::path
    B6["05-01<br/>Politische Sprache"]:::path

    B1 --> B2 --> B3 --> B4 --> B5 --> B6
```

Sem este caminho, análise de Bundestag-Plenarprotokoll é leitura ingênua.

### Caminho C — Schreiben → Stilbildung → Output

```mermaid
flowchart LR
    classDef path fill:#fffacd,stroke:#806000,color:#332400,stroke-width:2px

    C1n["03-01<br/>Nominal vs. verbal"]:::path
    C2n["03-07<br/>Wissenschaftl.<br/>Schreiben"]:::path
    C3n["04-07<br/>Textlinguistik"]:::path
    C4n["05-04<br/>Eigene Stimme"]:::path
    C5n["05-05<br/>Public Output"]:::path

    C1n --> C2n --> C3n --> C4n --> C5n
```

Sem este caminho, CAPSTONE-5 (Veröffentlichung) é tentativa em vez de output.

### Caminho D — Diakronie → Korpus → Begriffsgeschichte

```mermaid
flowchart LR
    classDef path fill:#fffacd,stroke:#806000,color:#332400,stroke-width:2px

    D1["01-06<br/>Wortbildung"]:::path
    D2["04-01<br/>Historische Linguistik"]:::path
    D3["04-02<br/>Etymologie"]:::path
    D4["04-08<br/>Korpuslinguistik"]:::path
    D5["CAPSTONE-4<br/>Begriffsanalyse korpusbasiert"]:::path

    D1 --> D2 --> D3 --> D4 --> D5
```

Sem este caminho, CAPSTONE-4 não tem método empírico — vira ensaio impressionista.

### Caminho E — Konversation → Hörverstehen → Public Output (Trilha G Auswandern)

```mermaid
flowchart LR
    classDef path fill:#fffacd,stroke:#806000,color:#332400,stroke-width:2px

    E1["01-08<br/>Phonetik"]:::path
    E2["01-10<br/>Konversation Stage 1"]:::path
    E3["03-02<br/>Register"]:::path
    E4["03-04<br/>Pragmatik"]:::path
    E5["03-10<br/>Hörverstehen colloquial"]:::path
    E6["05-04<br/>Eigene Stimme"]:::path
    E7["05-05<br/>Public Output"]:::path

    E1 --> E2 --> E3 --> E4 --> E5 --> E6 --> E7
```

Sem este caminho, fluência conversacional cotidiana fica em **Tagesschau-Standard sem traseira colloquial** — ouvinte profissional entende, mas no Späti em Berlin trava. Caminho crítico para Trilha G (Auswandern, cf. LEARNING-PATHWAYS §7.5).

---

## Como usar este DAG

### Beim Planen

1. **Mapear posição atual**: identificar quais módulos estão DONE em PROGRESS.md.
2. **Identificar nós desbloqueados**: módulos cujos prereqs estão satisfeitos.
3. **Escolher próximo módulo**: priorizar por trilha (cf. LEARNING-PATHWAYS.md) e Begriff (cf. BEGRIFF-INDEX.md).

### Beim Auditieren

1. **Audit de progressão** (cf. MENTOR.md §10.4): cada 90 dias, sobrepor PROGRESS.md ao DAG e diagnosticar:
   - Módulos com prereqs satisfeitos mas não-iniciados há > 60 dias?
   - Módulos iniciados mas com Tor pendente há > 30 dias?
   - Caminho crítico (A-D) progride proporcionalmente?

### Beim Branchen

Trilhas (cf. LEARNING-PATHWAYS.md) podem **omitir** caminhos não-essenciais:

- **Trilha E (Berufsdeutsch)**: omite Caminho D (Diakronie/Korpus) parcialmente.
- **Trilha B (Geisteswissenschaft)**: enfatiza Caminhos A + D.
- **Trilha D (Tradução)**: enfatiza 04-09 + 05-03 (não no DAG core acima).

---

## Cross-references

- [INDEX.md](INDEX.md) — listagem textual completa dos prereqs.
- [LEARNING-PATHWAYS.md](LEARNING-PATHWAYS.md) — 6 trilhas alternativas com seus DAGs próprios.
- [CAPSTONE-EVOLUTION.md](CAPSTONE-EVOLUTION.md) — encadeamento dos Capstones em torno de Begriff.
- Stage READMEs (cada um com DAG local em ASCII + Mermaid):
  - [Stage 1 README](../01-fundamente/README.md)
  - [Stage 2 README](../02-struktur/README.md)
  - [Stage 3 README](../03-stil/README.md)
  - [Stage 4 README](../04-system/README.md)
  - [Stage 5 README](../05-meisterschaft/README.md)
