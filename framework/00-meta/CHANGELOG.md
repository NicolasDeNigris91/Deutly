# CHANGELOG — FATHOM-Deutsch

> Histórico de versões do framework. Cada release nota mudanças significativas. Referenciado em MENTOR.md §10.2.

---

## v1.1 — 2026-05-09 — Anexos canônicos + DAG visual + output templates

### Adicionado

#### Anexos canônicos (`framework/00-meta/anhaenge/`)

- **ANHANG A — Ablautreihen** (`ANHANG-A-ABLAUTREIHEN.md`): ~166 verbos starke distribuídos pelas 7 Ablautreihen (com sub-Reihen Ia/Ib + IIa/IIb + IIIa/IIIb), klasse gemischt (9 verbos), Modalverben morfo-gemischt (6), irregulär (4), suppletiv (gehen/stehen). Cada entrada: Inf. + Prät.3.Sg. + Part.II + Hilfsverb (haben/sein/dual) + frase-Beleg. Resolve SN-001 (P1).
- **ANHANG B — Modalverben** (`ANHANG-B-MODALVERBEN.md`): 6 Modalverben × 6 pessoas × 8 Tempora/Modi (Präsens, Präteritum, Konj. I, Konj. II, Perfekt-Vollv., Perfekt-Modal/Ersatzinf., Plusquamperfekt, Futur I/II). Seções complementares: Modal + Perfekt-Inf. (epistemisch retrospektiv); Modal + Passiv (werden- e sein-); paradigma `möchten` höflich; Modal-Skala epistêmica; Pseudo-Modal `brauchen`. Resolve SN-002 (P1).

#### DAG visual (`framework/00-meta/DAG.md`)

- Master DAG file com diagrama global cross-Stage + 5 DAGs detalhados por Stage (com setas tracejadas para prereqs cross-Stage) + 4 caminhos críticos cross-Stage:
  - Caminho A: Sintaxe → Generative → Hermenêutica (01-01 → 02-08 → 04-04 → 04-10 → 05-02).
  - Caminho B: Lexik → Register → Diskursanalyse (01-09 → 02-09 → 03-02 → 03-08 → 04-06 → 05-01).
  - Caminho C: Schreiben → Stilbildung → Output (03-01 → 03-07 → 04-07 → 05-04 → 05-05).
  - Caminho D: Diakronie → Korpus → Begriffsgeschichte (01-06 → 04-01 → 04-02 → 04-08 → CAPSTONE-4).
- INDEX.md augmentado com Mermaid cross-Stage.
- 5 Stage READMEs com Mermaid local paralelo ao ASCII existente. Resolve SN-012 (P2).

#### Templates de output (`framework/00-meta/templates/`)

- **TAGEBUCH-TEMPLATE** — Tageseintrag in DE com 4 Strukturvarianten (frei / Reflexion strukturiert / Lesetagebuch / Sprachreflexion) + 4 Niveau-Modi (M1 Einfach a M4 Wissenschaftsdeutsch) + Korrekturschleife (4 Camadas) + Beispieleintrag.
- **AUFSATZ-1500W-TEMPLATE** — CAPSTONE-2 com 6 Sektionen (Einleitung → These → Argumentation I + II → Gegenargument → Schluss) + exigências stilísticas (Konj. I + Konj. II + Passiv + 1+ FVG + 1+ wörtliches Zitat) + 3-Round-Korrekturschleife + RUBRIC-Hinweis.
- **AUFSATZ-5000W-TEMPLATE** — CAPSTONE-3 com 7 Sektionen (Abstract → Einleitung → Forschungsstand → Methodologie → Hauptteil 3-aspectual → Diskussion + Gegenargument → Schluss) + Wissenschaftsdeutsch-hoch-Erwartungen + Literaturverzeichnis-Format + Mindestquellen (≥ 5 Primär + ≥ 5 Sekundär).
- **VORTRAG-TEMPLATE** — Modul 05-05 com 30-min-Skript-Strukturschema + Sprechgeschwindigkeit (~130 W/min × 30 = ~3900 W) + Pausenmarkierung + phonetische Aufmerksamkeit (Auslautverhärtung, Knacklaut, /r/-Distribution) + Q&A-Vorbereitung intern.
- **BEGRIFFSANALYSE-TEMPLATE** — CAPSTONE-4 com methodische Trias (diachron Frequenz + synchron Kollokationen + hermeneutisch Tiefenanalyse) + Korpus-Auswahl-Diskussion (DWDS / COSMAS-II) + Beleg-Anhang-Format (≥ 30 Belege) + Methodenkritik. Resolve SN-011 (P2).

#### Cross-references neue Verknüpfungen

- 01-03 §2.3 → ANHANG A (Ablautreihen).
- 02-07 §2.1 → ANHANG B (Modalverben).
- CAPSTONE-2 / -3 / -4 → respektive Output-Templates.
- 05-05 → VORTRAG-TEMPLATE.
- INDEX.md → anhaenge/ + templates/ + DAG.md.

### Korrigido / verändert

- INDEX.md: lista de "Documentos meta complementares" expandida com `DAG.md`, `anhaenge/`, `templates/`.
- 5 Stage READMEs: estrutura "DAG do Stage N" subdividida em "Textual (ASCII)" + "Visuell (Mermaid)".
- SPRINT-NEXT.md: SN-001, SN-002, SN-011, SN-012 marcados como Done; cadência de releases atualizada.

### Resolvido (SN-Items, cf. SPRINT-NEXT.md)

- SN-001 [P1] — Anexo 7 Ablautreihen completas.
- SN-002 [P1] — Anexo Modalverben em todos modos + tempos.
- SN-011 [P2] — Templates Markdown para output do aluno.
- SN-012 [P2] — Diagramas DAG visuais.

### Estatísticas v1.1

```
Novos arquivos:                    8
  Anexos:                          2 (ANHANG-A, ANHANG-B)
  Templates:                       5 (Tagebuch, Aufsatz-1500W, Aufsatz-5000W, Vortrag, Begriffsanalyse)
  Master DAG:                      1 (DAG.md)
Arquivos modificados:              ~10
  Cross-refs em modul 01-03 + 02-07
  Templates hinweise em 4 Capstones + 05-05
  INDEX.md + 5 Stage READMEs (Mermaid)
  SPRINT-NEXT.md (status updates)

Verbos catalogados (ANHANG A):     ~166
Modalverb-Konjugationsformen 
documentadas (ANHANG B):           ~300
Mermaid-Diagramme adicionados:     12 (1 master + 5 stages local + 1 INDEX + 5 caminhos críticos)
Output-Templates:                  5 (cobre todos Capstones + Tagebuch sustentado + Vortrag)
```

---

## v1.0 — 2026-05-08 — Initial Public Release

### Adicionado

- **5 Stages estruturalmente completos**:
  - Stage 1 (Fundamente): 9 módulos + Capstone-1.
  - Stage 2 (Struktur): 9 módulos + Capstone-2.
  - Stage 3 (Stil): 9 módulos + Capstone-3.
  - Stage 4 (System): 10 módulos + Capstone-4.
  - Stage 5 (Meisterschaft): 7 módulos + Capstone-5.
- **44 módulos + 5 Capstones encadeados** (Erkenntnisprojekt v0→v4).
- **~50 textos-âncora canônicos** (Kant 1784 a Habermas 2001).
- **Documentos meta**:
  - INDEX.md, CAPSTONE-EVOLUTION.md.
  - REFERENCES-ELITE.md, READING-LIST.md, GLOSSAR.md.
  - SELF-ASSESSMENT.md, RUBRIC.md.
  - ANKI-FRAMEWORK.md, FEHLERPROTOKOLL-TEMPLATE.md.
  - MODULE-TEMPLATE.md, LEARNING-PATHWAYS.md, BEGRIFF-INDEX.md.
  - DECISION-LOG.md, SPRINT-NEXT.md.
  - RELEASE-NOTES.md.
- **Documentos do root**: README.md, MENTOR.md, STUDY-PROTOCOL.md, PROGRESS.md, LICENSE (CC BY-NC 4.0), .gitignore.
- **Push GitHub**: 6 commits encadeados (`26dd446`, `c4c5dc6`, `afa617c`, `fa81120`, `98afac6`, [v1.0]).

### Trilhas suportadas

- Trilha A — Canônica (default, generalista).
- Trilha B — Geisteswissenschaft (filosofia + germanística).
- Trilha C — Linguistik (germanística + linguística aplicada).
- Trilha D — Tradução PT↔DE.
- Trilha E — Berufsdeutsch (uso profissional).
- Trilha F — PhD-DE acelerada.

### Princípios estabelecidos

- Não-negociáveis pedagógicos (cf. README.md).
- Loop de Refinamento em 4 camadas (Grammatik / Lexik / Stil / Native erudite, cf. MENTOR.md §1).
- 3 Tore obrigatórios por módulo (Konzeptuell / Praktisch / Verbindungen, cf. MENTOR.md §3 + RUBRIC.md).
- Capstones encadeados em torno de Begriff escolhido.

---

## Convenções de versionamento

### Major version (v2.0, v3.0)

Mudança estrutural significativa: adição de novo Stage, reorganização da topologia, mudança em pré-requisitos canônicos.

### Minor version (v1.1, v1.2)

Adição de módulo opcional, anexos extensivos, novas trilhas, expansões pedagógicas.

### Patch version (v1.0.1, v1.0.2)

Correções de erros, atualização de referências, edits ortográficos.

---

## Próximas versões previstas (cf. SPRINT-NEXT.md)

### v1.1 (~6-12 meses)

- Glossário cross-stage de Begriffe centrais cumulativo.
- Anexos com listas exhaustivas de starken Verben (7 Ablautreihen).
- Anexos com Modalverben em todos modos + tempos.
- Anexos com FVG canônicas (200+ entries).
- Anexos com Stilfiguren com exemplos múltiplos.
- Edits ortográficos + revisão consistência cross-module.

### v1.5 (~12-24 meses)

- Tradução do framework para DE original (atualmente em PT-BR).
- Adição de tracks empíricas com Anki decks pré-construídos.
- Validação peer-review por linguistas DE.
- Templates Markdown para Tagebuch + Aufsatz + Vortrag.

### v2.0 (~24-48 meses)

- Comunidade de mentees + cohorts ativos.
- Capstones de exemplares (1-2 por Begriff publicados como modelo).
- Feedback loop com aprendizes que completaram.
- Iterações pedagógicas baseadas em dados.
- Possível adição de módulo 06 (Specialization tracks).

---

## Como contribuir mudanças

1. **Issue ou Discussion no GitHub**: descrever mudança proposta.
2. **DECISION-LOG entry** (se mudança estrutural): justificar.
3. **Pull Request**: implementar.
4. **Review**: discussão pública.
5. **Merge**: incorporar em main + atualizar CHANGELOG.

(Cf. CONTRIBUTING.md quando criado.)

---

## Notas de migração

(Sem migrações necessárias para v1.0; primeira release.)

Em versões futuras, esta seção documentará passos para alunos atualizarem dependências (e.g., novos textos-âncora; reordenamento de módulos).
