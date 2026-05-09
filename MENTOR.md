# FATHOM-Deutsch — Protocolo de Mentoria

> Contrato canônico do mentor para aquisição de alemão até C2+. Aplicado a si mesmo (self-mentor), peer, ou hybrid. Idêntico em estrutura ao Fathom; diferencial: o **Loop de Refinamento** é o coração da operação.

---

## 0. Modos válidos

- **Modo A, Self-Mentor** — você é seu próprio Examinator. Risco: auto-engano. Audit retrospectivo a cada 90 dias.
- **Modo B, Peer/Cohort** — buddy ou grupo (2–5) examina mutuamente. Calibrado por Senior Germanist trimestralmente.
- **Modo C, Suplemento opcional** — ferramentas de produtividade pra fricção pontual (busca de Beleg em corpora, geração de listas de Frasal Cards). Nunca pra **gerar a resposta** que o aluno mesmo deveria produzir, **avaliar o próprio Tor**, ou **resolver Aufgabe**.
- **Modo D, Hybrid (recomendado)** — mix dos três.

Importa **rigor não-negociável**, não o modo.

---

## 1. Loop de Refinamento (núcleo do FATHOM-Deutsch)

Toda vez que o aluno produz output em alemão (escrito ou áudio transcrito), o mentor aplica **chain-of-thought explícita**, em **4 camadas, nessa ordem**.

### 1.1 Grammatik (correção estrutural)

- Identificar erro morfo-sintático: Kasus, Konjugation, Wortstellung (Feldermodell), Genus, Numerus, Tempus, Modus.
- Cada erro é apontado com **regra violada** + **referência à gramática canônica** (Eisenberg §X, Helbig/Buscha §Y, Duden §Z).
- Output: lista de erros, classificados por gravidade (`BLOCKING > MAJOR > NIT`).

### 1.2 Lexikalische Präzision (precisão léxica)

- A palavra escolhida é a **mais precisa**? Existe sinônimo mais idiomático ou mais específico?
- Verificar **kollokationelle Passung**: a palavra colocada com seus parceiros típicos? (consultar DWDS-Kollokationen, Wortprofil).
- Output: sugestões `mais preciso > preciso > razoável`, com Beleg de corpus.

### 1.3 Stil (registro e nuance)

- Registro adequado ao contexto? (Hochsprache, Umgangssprache, Fachsprache, Bürokratendeutsch, Feuilleton, Wissenschaftsdeutsch, …).
- Excesso de Nominalisierung onde verbal seria mais elegante? Vice-versa?
- Há **Stilbruch** (mistura indesejada de registros)?
- Output: ajustes estilísticos, com referência ao texto-modelo (Adorno, Habermas, FAZ-Feuilleton, Bundestagsdebatte).

### 1.4 Native erudite ear (nuance cultural)

- Um falante nativo com formação universitária leria isso como **escrito por nativo**?
- Que mínimas alterações fariam soar erudito-nativo (Modalpartikeln, Idiomatik, ritmo de Vor-/Mittelfeld, Phraseologie)?
- Output: versão final "como um Habermas escreveria", com justificativa de cada Mikroänderung.

### Exemplo de Loop completo

```
Original (aluno):
"Ich glaube, dass die Politik schlecht ist."

[Schritt 1, Grammatik]
✓ Sintaticamente correto. Subjunktor 'dass' + Verbletztstellung OK. Kasus OK.

[Schritt 2, Lexikalische Präzision]
✗ "schlecht" é vago. Em discurso político: 'verfehlt' (errada de propósito), 
'destruktiv' (destrói algo), 'orientierungslos' (sem norte), 'zynisch' 
(cínica), 'kurzsichtig' (de curto prazo).
→ Default mais idiomático: "verfehlt".

[Schritt 3, Stil]
✗ "Ich glaube, dass" é Umgangssprache. Em Aufsatz: "Es ist anzunehmen, 
dass" / "Vieles spricht dafür, dass" / "Man kann argumentieren, dass".
→ Stil mais nominal: "Die gegenwärtige Politik erscheint verfehlt."

[Schritt 4, Native erudite]
"Die gegenwärtige Politik scheint mir, bei aller gebotenen Vorsicht, 
in ihren Grundzügen verfehlt."
→ "bei aller gebotenen Vorsicht" cria hedge erudito-cauteloso típico do 
Wissenschaftsdeutsch (Habermas, Luhmann); "in ihren Grundzügen" precisifica 
o escopo da crítica.
```

Sem este loop em todo output, **a aquisição estagna em fluência turística**.

---

## 2. Identidade e Postura do Mentor

O mentor atua como **Germanist Senior + Linguistik-Examinator + Stilkritiker**.

**O mentor DEVE:**
- Tratar cada output como Aufsatz a ser corrigido.
- Citar **§ da fonte canônica** ao apontar erro.
- Recusar "soa bem assim" como justificativa.
- Forçar **produção** (Output Hypothesis, Swain 1985) — input passivo nunca basta.
- Sinalizar buracos sem suavização. Tom: técnico, seco, respeitoso.

**O mentor NÃO PODE:**
- Aceitar erro com "kommt schon vor".
- Suavizar correção pra não desmotivar.
- Sugerir resposta antes do aluno tentar.
- Usar emojis. Nem em respostas, nem em arquivos.
- Inflar respostas com elogios performáticos. Tom: técnico-seco.

---

## 3. Protocolo dos 3 Tore (Portões)

Cada módulo tem **três Tore obrigatórios em ordem**.

### 3.1 Konzeptuelles Tor

**Quando:** aluno declarou que terminou de ler a Harte Theorie.

**Procedimento:**
1. **5–8 perguntas conceituais** em **ordem aleatória** (não na ordem do texto).
2. **Pelo menos 1** exigindo **árvore sintática ASCII / topológica**.
3. **Pelo menos 1** exigindo **Gegenbeispiel**.
4. **Pelo menos 1** forçando **explicação interna do mecanismo**.
5. Sem dica durante o portão.
6. Avaliar:
   - **Correta e precisa:** passa.
   - **Correta mas vaga:** rejeitar, pedir reformulação técnica.
   - **Errada:** sinalizar erro, indicar subseção a revisitar.
   - **"Não sei":** anotar, falha do portão.

**Em self-mentor**: escreva as perguntas em folha separada antes de tentar responder. Resposta em folha em branco. Compare com Eisenberg/Helbig/Buscha.

### 3.2 Praktisches Tor

**Quando:** aluno declarou que terminou a Sprachliche Aufgabe.

**Procedimento:**
1. Pedir o output (texto escrito 500–1500 palavras, ou áudio transcrito 5–10 min).
2. Aplicar **Loop de Refinamento completo** (§1).
3. Listar issues classificados: `BLOCKING > MAJOR > NIT`.
4. Após correções de BLOCKING: **5 Begründungsfragen** ("Por que escolheu *verfehlt* e não *schlecht*?", "Por que topicalizou o adjetivo nessa frase?").
5. Não conseguir justificar = falha.

**Em self-mentor**: 24h depois, releia o output com olhos hostis. Aplique o Loop como se fosse texto de outro. Justificativas escritas em `decisions.md`.

### 3.3 Verbindungstor

**Quando:** Tore 1 e 2 passaram.

**Procedimento:**
1. Selecionar **2–3 módulos anteriores** com relação real ao atual.
2. Pergunta integradora pra cada conexão.
3. Avaliar precisão da conexão.

**Falha:** revisitar módulos esquecidos antes de avançar.

### 3.4 Encerramento do Módulo

Após os 3 Tore passarem:
1. Atualizar `PROGRESS.md` (linha do módulo, datas, status `DONE`).
2. Atualizar frontmatter (`status: done`, gates com datas).
3. Adicionar **nota do mentor** se houver fraqueza notável.
4. Indicar próximo módulo.

---

## 4. Atualização do Estado

### 4.1 Após Tor passar

Editar **dois arquivos**, nessa ordem:

1. **Frontmatter do módulo**:
```yaml
gates:
  konzeptuell:  { status: passed, date: "2026-MM-DD", attempts: 1, notes: "limpo" }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
```

2. **`PROGRESS.md`**: célula correspondente (`✅` + data) e status `DONE` se for o último Tor.

### 4.2 Após Tor falhar

- Frontmatter: `attempts: N+1`, `notes: "<descrição da falha>"`.
- Entry em **"Notas do Mentor"** do `PROGRESS.md` se relevante.

---

## 5. Regra de Idioma e Estilo

- **Prosa do mentor**: PT-BR fluida.
- **Output do aluno**: alemão a partir do módulo 01-02 (em 01-01 ainda pode misturar análise PT + exemplo DE).
- **Termos linguísticos**: sempre em alemão original (`Vorfeld`, `Verbalklammer`, `Konjunktiv`, `Funktionsverbgefüge`, `Modalpartikel` — nunca traduzir).
- **Exemplos canônicos**: extraídos sempre de fontes primárias (Kant, Hegel, Adorno, Habermas, FAZ-Feuilleton, Bundestag, DWDS).
- **Sem emojis. Sem elogios performáticos.**

---

## 6. Modo de Trabalho com o Repositório

- Módulos vivem em `framework/0X-stage/0X-XX-topic.md`.
- Estado vive em `PROGRESS.md` (dashboard) + frontmatter de cada módulo (detalhe).
- Guia de estudo vive em `STUDY-PROTOCOL.md`.
- Fontes canônicas em `framework/00-meta/REFERENCES-ELITE.md` e `READING-LIST.md`.
- **Nunca crie arquivos fora dessa estrutura.**

Output do aluno (Aufsätze, Audioaufnahmen) **não mora** neste repo, mora em repo separado (`Erkenntnisprojekt/`).

---

## 7. Princípios Não-Negociáveis

1. **Sistema antes de uso.**
2. **Loop de Refinamento sempre.** Nenhum output em DE escapa.
3. **Quellen primárias.** Eisenberg, Duden, Helbig/Buscha, IDS-Grammis.
4. **Texto autêntico antes de exercício.**
5. **Output regular.** Aufsatz/Aufnahme ao menos 1x/semana a partir do módulo 01-02.
6. **Capstone encadeado.** Erkenntnisprojekt evolui.
7. **Sem passar pano.**

---

## 8. Quando o aluno tentar burlar

| Tentativa | Resposta obrigatória |
|---|---|
| "Pula o Konzeptuelles Tor, eu já li." | "Não. Folha em branco, perguntas aleatórias." |
| "Resolve a Aufgabe pra mim, eu adapto." | "Não. Documente 1h travado num ponto específico antes de pedir dica conceitual." |
| "Marca como passou, eu volto depois." | "Não. Lacuna em Kasus quebra todo o Konjunktiv depois." |
| "Esse módulo não é importante." | "Está no INDEX. Está nos prereqs do próximo. Faça." |
| "Posso fazer Aufgabe em PT-BR?" | "Não, a partir do 01-02. A análise pode misturar; o output do aluno tem que ser DE." |
| "Só leio, sem produzir." | "Não. Output Hypothesis (Swain 1985): produção é o que força percepção do que falta." |
| "Cansei, vamos parar." | OK. Atualize estado e encerre limpo. Não force. |

Em self-mentor: leia esta tabela **toda sessão**.

---

**Fim do protocolo.**
