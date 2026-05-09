# CONTRIBUTING — Como contribuir ao FATHOM-Deutsch

> Bem-vindo. Este documento estabelece **como contribuir** ao framework: tipos de contribuição aceitos, processo de Pull Request, padrões de qualidade, governança.

---

## 1. Tipos de contribuição aceitos

### Correções (sempre bem-vindas)

- **Erros tipográficos** em DE ou PT.
- **Citações erradas** (edição, página, autor).
- **Inconsistências** cross-module (mesmo termo definido em lugares diferentes).
- **Cross-references quebradas** (link para módulo inexistente).
- **Erros gramaticais** em exemplos.

### Melhorias (aceitas com discussão)

- **Esclarecimento** de explicação obscura.
- **Adição de exemplo** a módulo existente.
- **Refinamento** de pipeline diagnóstico.
- **Atualização** de referência bibliográfica (edição mais recente).

### Expansões (aceitas com Issue prévia)

- **Novo anexo** consolidando informação.
- **Lista expandida** (verbos, FVG, Stilfiguren, etc.).
- **Novo Begriff** scaffold em BEGRIFF-INDEX.md.
- **Nova trilha** em LEARNING-PATHWAYS.md.

### Mudanças estruturais (aceitas com DECISION-LOG entry obrigatório)

- **Reordenamento** de módulos.
- **Alteração de pré-requisitos**.
- **Adição de novo módulo**.
- **Mudança de Capstone-spec**.

### Não-aceitos

- **Conversão para LMS** ou sistema proprietário.
- **Adição de gamificação rasa** (badges, etc.) — anti-padrão pedagógico (cf. SPRINT-NEXT.md SN-W002).
- **Integração de AI tutor** como substituto de mentor humano (cf. SN-W003).
- **Conteúdo comercial** (CC BY-NC 4.0).

---

## 2. Processo de Pull Request

### Antes de submeter

1. **Issue prévia** se mudança não-trivial: descreva proposta + receba feedback.
2. **Fork** o repo.
3. **Branch específico**: `tipo/descricao-curta` (e.g., `correction/typo-01-04`, `expansion/sn-001-ablautreihen`).

### Padrão de commit

```
tipo: descrição curta (max 70 char)

Descrição mais longa explicando o porquê (não o quê).
Múltiplas linhas se necessário.

Refs: #issue-number ou DL-YYYY-MM-DD-NNN se aplicável.
```

Tipos:
- **fix**: correção de erro detectado.
- **edit**: edição menor (typo, formatação).
- **expand**: adição de conteúdo (novo anexo, exemplos).
- **refactor**: reorganização sem mudança de conteúdo.
- **docs**: atualização de documentação.

### Author do commit

```
Author: [Seu nome] <[seu-email]>
```

**Não adicionar `Co-Authored-By: Claude` ou similar** — conforme DL-2026-05-08-008.

### Submissão

1. **Push** para seu fork.
2. **Pull Request** ao repo principal.
3. **Descrição do PR**: link para Issue + DECISION-LOG entry se aplicável.
4. **Review**: discussão pública.
5. **Merge** após aprovação.

---

## 3. Padrões de qualidade

### Conteúdo técnico

- **Referência canônica obrigatória**: cada afirmação técnica deve apontar para Eisenberg, Helbig/Buscha, Engel, Duden, IDS-Grammis (gramáticas) ou Pfeifer/Kluge (etymologia) ou Schmitt/Niemeier (pedagogia L2) ou autor reconhecido.
- **Sem afirmações sem fonte** ("Em alemão, X é assim" sem § da gramática).
- **Exemplos autênticos**: prefira textos de Kant, Hegel, Heidegger, Adorno, Habermas, Mann, Bernhard, Sebald, Kafka, etc. Evitar exemplos artificiais.
- **Stilstufe marcada**: cada termo + exemplo deve ter Stilstufe explícita (gehoben / neutral / Umgangssprache / Bürokratisch / wissenschaftlich).

### Estilo de escrita

- **Prosa em PT-BR** (atual; pode mudar com SN-008).
- **Termos técnicos em DE original**: nunca traduzir 'Vorfeld', 'Konjunktiv', 'Stilfigur', 'Begriff'.
- **Frases médias-curtas**: legibilidade > densidade.
- **Sem emojis** (regra cross-stage do framework).
- **Sem elogios performáticos** ("ótimo!", "excelente!").
- **Tom seco-técnico** consistente com MENTOR.md §1.

### Markdown formatting

- **Títulos hierárquicos**: H1 (módulo) → H2 (seção) → H3 (subseção).
- **Frontmatter YAML** consistente em módulos (cf. MODULE-TEMPLATE.md).
- **Listas + tabelas** quando estruturalmente apropriadas.
- **Code blocks** para exemplos sintáticos / morfológicos.
- **Bold** moderado para ênfase técnica.
- **Italic** para termos primeiramente introduzidos ou para títulos de obras.

### Citação de Quellen

```markdown
**Eisenberg, Peter** — *Grundriss der deutschen Grammatik*. Bd. 2: *Der Satz*. 5. Aufl. Stuttgart: Metzler, 2020.
```

Padrão: Sobrenome, Prenome — *Título*. Volume / Edição. Local: Verlag, Ano.

---

## 4. Governance

### Maintainer

**Nicolas De Nigris** (https://github.com/NicolasDeNigris91).

Decisões finais sobre PR, mudanças estruturais, cadência de releases.

### Discussão

- **GitHub Issues**: para bugs, propostas, dúvidas.
- **GitHub Discussions** (se ativado): para conversação aberta.
- **Pull Requests**: para mudanças concretas.

### Decisões estruturais

- **DECISION-LOG entry obrigatório** para mudanças que afetam estrutura cross-stage.
- **CHANGELOG entry** para qualquer mudança incorporada em release.
- **SPRINT-NEXT entry** para mudanças planejadas mas não-iniciadas.

### Releases

- **Cadência**: ~v1.1/v1.5/v2.0 (cf. SPRINT-NEXT.md).
- **Tag em Git**: cada release tagged (`v1.0`, `v1.1`, etc.).
- **RELEASE-NOTES.md atualizado**.

---

## 5. Licença + atribuição

### Licença

CC BY-NC 4.0 (Creative Commons Attribution-NonCommercial 4.0 International).

Você concorda em licenciar suas contribuições sob a mesma licença.

### Atribuição

Contribuidores são creditados em:
- **CHANGELOG.md** (para mudanças incorporadas).
- **AUTHORS.md** (se criado em v1.5+).
- **Commit history** preservado.

Você **não é coautor do framework** — você contribui melhorias. O framework é trabalho intelectual + curatorial primário do maintainer.

### Sem AI co-author

Conforme DL-2026-05-08-008, **commits NÃO devem ter `Co-Authored-By: Claude`** ou trailers AI similares. Authorship é humana.

---

## 6. Code of Conduct

### Princípios

- **Foco técnico**: discussões sobre framework, não sobre pessoas.
- **Respeito**: discordância é bem-vinda; ataque pessoal não.
- **Tom seco-técnico**: consistente com MENTOR.md (sem elogios performáticos, sem suavização desnecessária).
- **Sem emojis**: convenção do framework.
- **Inclusão**: framework é para qualquer aprendiz adulto sério; pluralidade de origens é virtude.

### Inaceitável

- Ataques pessoais, harassment, discriminação.
- Spam, autopromoção comercial.
- Sabotagem (introduzir erros deliberadamente).
- Violação de licença CC BY-NC 4.0.

### Reporting

Se ocorrer comportamento inaceitável: contatar maintainer via GitHub Issue privada ou e-mail (se publicado em GitHub profile).

---

## 7. Como começar

### Para iniciante absoluto

1. **Ler o framework** primeiro (Stage 1-2 mínimo).
2. **Detectar inconsistências / erros** durante leitura.
3. **Submeter Issue ou Pull Request** para correção.

### Para aluno avançado

1. **Identificar item de SPRINT-NEXT.md** que ressoa.
2. **Comentar na Issue** ou criar uma.
3. **Implementar** após aprovação do maintainer.
4. **Pull Request**.

### Para especialista (linguista, germanista)

1. **Audit estrutural**: revisar trilha completa por área de expertise.
2. **Submeter feedback** consolidado via Issue.
3. **Pull Requests** para correções específicas.
4. **Considerar** SN-010 (peer-review formal).

---

## 8. Comunidade

### Canais

- **GitHub repo**: https://github.com/NicolasDeNigris91/Deutly.
- **Issues + Discussions**: GitHub.
- **Cohorts** (futuro): SN-013 prevê comunidade ativa em v2.0.

### Multi-geracional

Framework prevê **multi-geracional**: alunos que completam Stage 5 tornam-se mentores de próxima geração (módulo 05-06 Mentoring von Lernenden).

---

## 9. Recursos para contribuidores

### Documentos centrais

- **README.md** — manifesto.
- **MENTOR.md** — protocolo do mentor.
- **STUDY-PROTOCOL.md** — pedagogia adulta L2.
- **CHANGELOG.md** — histórico de versões.
- **DECISION-LOG.md** — decisões estruturais.
- **SPRINT-NEXT.md** — backlog.
- **RELEASE-NOTES.md** — release notes.

### Convenções

- **MODULE-TEMPLATE.md** — template para novos módulos.
- **FEHLERPROTOKOLL-TEMPLATE.md** — template Fehlerprotokoll.
- **ANKI-FRAMEWORK.md** — Anki workflow.
- **LEARNING-PATHWAYS.md** — trilhas alternativas.
- **BEGRIFF-INDEX.md** — Begriffe canônicos.

---

## 10. Agradecimentos

Framework escrito por **Nicolas De Nigris**.

Gramáticas-fonte: Eisenberg, Helbig/Buscha, Engel, Duden, Zifonun (IDS), Wöllstein, Sternefeld.

Pedagogia L2: Krashen, Swain, Bjork, Karpicke/Roediger, Ericsson, Schmitt.

Filosofia DE: Habermas, Luhmann, Adorno, Heidegger, Gadamer, Foucault.

Tradução: Schleiermacher, Benjamin, Berman, Venuti.

Begriffsgeschichte: Brunner/Conze/Koselleck, Ritter, Mittelstraß.

Corpora: DWDS (BBAW), COSMAS II (IDS Mannheim), Pfeifer.

---

**Contribuições de qualidade são bem-vindas. Framework cresce via curadoria + iteração + comunidade.**
