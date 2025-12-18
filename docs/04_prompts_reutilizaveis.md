# 04 — Biblioteca de prompts reutilizáveis (para revisão)

> Use em qualquer caderno do NotebookLM. A ideia é ter prompts “de rotina”, sem precisar reinventar.

## Prompts de resumo
### P1 — Resumo em 7 linhas com citações
“Resuma o tema **{TEMA}** em 7 linhas, em português simples, e cite a fonte (S#) para cada ponto.”

### P2 — Resumo estruturado (definição → exemplo → erro comum)
“Explique **{CONCEITO}** com:
1) definição,
2) exemplo numérico simples,
3) erro comum + como evitar.
Cite S# em cada item.”

## Prompts de compreensão profunda
### P3 — Perguntas de verificação
“Crie 5 perguntas para eu testar se entendi **{TEMA}**. Depois, responda com justificativa e cite S#.”

### P4 — ‘Explique como se eu tivesse 12 anos’
“Explique **{CONCEITO}** com analogias do dia a dia (máximo 10 linhas). Cite S#.”

### P5 — Contraste (comparação)
“Compare **{A}** vs **{B}** em uma tabela: o que é, quando faz sentido, riscos, custos/tributos, pegadinhas. Cite S#.”

## Prompts de estudo ativo
### P6 — Flashcards
“Crie 12 flashcards (frente/verso) sobre **{TEMA}**, com linguagem objetiva, citando S# em cada cartão.”

### P7 — Mapa mental textual
“Crie um mapa mental textual de **{TEMA}** (tópicos e subtópicos). Cite S# nos ramos principais.”

## Prompts de auditoria (anti-alucinação)
### P8 — O que NÃO está nas fontes
“Liste tudo que você **não consegue afirmar** com base nas fontes S1–S5 sobre **{TEMA}** e diga qual fonte eu deveria adicionar.”

### P9 — Checagem de consistência
“Releia sua resposta e aponte trechos que estão **diretamente suportados** por S1–S5 e quais são inferências. Cite S#.”

## Prompts de aplicação prática
### P10 — Mini-caso (reserva de emergência)
“Vou te dar um cenário; recomende uma estratégia **em renda fixa**, com foco em liquidez e risco, baseada só em S1–S5. Se precisar, faça perguntas antes.”
