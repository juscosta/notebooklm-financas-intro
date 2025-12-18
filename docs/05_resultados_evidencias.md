# 05 — Registro de testes de prompts (respostas + referências)

> Como usar: no NotebookLM, execute cada prompt e cole aqui:
- o prompt usado (versão A/B/C),
- a resposta,
- e as referências que o NotebookLM apontar (S# + página/trecho).

Abaixo deixei um **modelo preenchido** (exemplo) para você usar como referência do “nível” esperado.
Quando você rodar no seu NotebookLM, substitua pela resposta real com as citações automáticas dele.

---

## Teste 1 — “Juros simples x juros compostos”

### Prompt A (direto)
“Explique a diferença entre juros simples e juros compostos com um exemplo curto, e cite S#.”

**Resposta (exemplo):**
- Juros simples incidem apenas sobre o capital principal; por isso o acréscimo tende a ser linear.
- Juros compostos incorporam os juros ao principal a cada período, e então os juros passam a render juros (“juros sobre juros”), fazendo o valor crescer mais rápido.
- Exemplo: em um empréstimo de R$ 1.000 por 6 meses a 5% a.m., o simples chega a R$ 1.300, enquanto o composto chega a aproximadamente R$ 1.340,10.  
**Referências:** S1 (seção “Atenção aos juros”, p. 25–26).

### Prompt B (com estrutura)
“Explique juros compostos com: 1) definição; 2) fórmula; 3) exemplo numérico; 4) alerta sobre dívidas. Cite S#.”

**Resposta (exemplo):**
1) Definição: juros compostos são “juros sobre juros”, pois os juros de cada período são incorporados ao capital e também passam a render.  
2) Fórmula típica: M = C(1+i)^n.  
3) Exemplo: C=1.000, i=10% a.m., n=4 → M≈1.464,10.  
4) Alerta: o crescimento exponencial ajuda investimentos, mas também pode “explodir” dívidas.  
**Referências:** S1 (definição e exemplo p. 26), S3 (fórmula e exemplo p. 32).

### Prompt C (checagem)
“Liste 3 erros comuns de quem calcula juros compostos e corrija. Cite S#.”

**Resposta (exemplo):**
- Confundir taxa ao mês com taxa ao ano (precisa padronizar a unidade de tempo).
- Somar juros linearmente em vez de capitalizar (no composto, o montante vira novo capital).
- Esquecer que vender antes do prazo pode mudar o resultado real (risco/condições do produto).  
**Referências:** S1 (capitalização e efeito no tempo), S3 (capitalização e interpretação).

---

## Teste 2 — “Inflação, IPCA e poder de compra”

### Prompt A
“O que é inflação? Como IPCA e INPC se relacionam com isso? Cite S#.”

**Resposta (exemplo):**
- Inflação é o aumento de preços de produtos e serviços e costuma ser medida por índices de preços.
- O IBGE produz IPCA (considerado oficial pelo governo federal) e INPC; ambos medem a variação de preços de uma cesta de consumo.
- O IPCA cobre um grupo mais amplo (famílias com renda de 1 a 40 salários mínimos), enquanto o INPC cobre um grupo menor (1 a 5 salários mínimos).  
**Referências:** S2 (seção “O que é inflação” e “Diferença entre IPCA e INPC”).

### Prompt B (aplicação)
“Se meu salário subiu 3% no ano e o IPCA foi 4%, o que aconteceu com meu poder de compra? Cite S#.”

**Resposta (exemplo):**
- Você perdeu poder de compra, porque os preços subiram mais do que sua renda.  
**Referências:** S2 (seção “Poder de compra”).

### Prompt C (conexão macro)
“Por que o IPCA é citado junto com metas de inflação e taxa de juros? Cite S#.”

**Resposta (exemplo):**
- Porque o IPCA é usado como referência para metas de inflação e se conecta às decisões de taxa de juros.  
**Referências:** S2 (seção “Por que se fala tanto em IPCA?”).

---

## Teste 3 — “Renda fixa e Tesouro Direto”

### Prompt A
“O que é renda fixa e quais riscos devo olhar? Faça em tópicos e cite S#.”

**Resposta (exemplo):**
- Renda fixa: investimentos que pagam remuneração ligada a uma taxa de juros; pode ser prefixada (definida na aplicação) ou pós-fixada (definida no resgate com base em indexador).  
- Riscos: crédito (capacidade do emissor pagar), liquidez (dificuldade/condições de resgate) e outros custos/tributos associados.  
**Referências:** S1 (definição de renda fixa e prefixado/pós-fixado), S4 (riscos de crédito e liquidez).

### Prompt B (Tesouro Direto)
“Explique Tesouro Selic, Tesouro IPCA+ e Tesouro Prefixado e quando cada um costuma ser usado. Cite S#.”

**Resposta (exemplo):**
- Tesouro Selic: pós-fixado ligado à Selic; costuma ser indicado para objetivos de curto prazo.
- Tesouro IPCA+: parte da rentabilidade varia com IPCA; costuma ser indicado para objetivos de longo prazo e para tentar manter o poder de compra.
- Tesouro Prefixado: taxa conhecida no vencimento; costuma ser usado quando você quer previsibilidade até a data final.  
**Referências:** S5 (descrição dos títulos).

### Prompt C (custos/tributos)
“Quais custos/tributos aparecem no Tesouro Direto (custódia, IR, IOF) e quando? Cite S#.”

**Resposta (exemplo):**
- Custódia: existe taxa de custódia (B3) e o material cita cobrança anual com cobrança semestral.
- IR: incide sobre rendimentos em tabela regressiva conforme prazo.
- IOF: pode incidir em resgates/vendas em prazo inferior a 30 dias.  
**Referências:** S5 (custos e tributação), S4 (IOF/IR e tabela regressiva).
