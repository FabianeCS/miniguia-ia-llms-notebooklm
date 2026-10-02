# Cicatrizes e Troubleshooting

As cicatrizes registram problemas reais encontrados durante o uso do
NotebookLM. Elas fazem parte do projeto porque mostram o processo de
experimentação.

## Cicatriz 1 --- resposta não correspondeu ao assunto solicitado

Em uma das perguntas, o objetivo era receber uma explicação sobre Large
Language Models. Entretanto, a resposta apresentada repetiu o conteúdo
relacionado a tokens.

### Problema

A resposta não acompanhou o objetivo principal da pergunta.

### O que foi aprendido

Uma possível melhoria é reforçar o assunto central e pedir uma estrutura
explícita.

### Prompt de recuperação

> Minha pergunta é especificamente sobre Large Language Models (LLMs). A
> resposta anterior falou sobre tokens, mas não explicou o conceito de
> LLM. Refaça a resposta focando no que é um LLM, como ele funciona e dê
> um exemplo simples.

------------------------------------------------------------------------

## Cicatriz 2 --- resposta repetiu a pergunta anterior

Em outra pergunta, o objetivo era saber quais cuidados um iniciante
deveria ter ao utilizar LLMs. A resposta voltou a apresentar as
limitações e problemas de confiabilidade dos modelos, repetindo o
conteúdo da pergunta anterior.

### Problema

A resposta abordou um assunto relacionado, mas não entregou a
organização prática solicitada.

### O que foi aprendido

Para perguntas desse tipo, é útil indicar exatamente a estrutura da
resposta.

### Prompt de recuperação

> Com base exclusivamente nas fontes deste notebook, liste 5 cuidados
> práticos para um iniciante que utiliza LLMs. Para cada cuidado,
> informe: 1) o cuidado; 2) por que ele é importante; 3) um exemplo
> prático. Não repita apenas a lista de limitações dos LLMs.

------------------------------------------------------------------------

## Checklist de troubleshooting

Quando uma resposta não estiver adequada:

1.  Verifique se a pergunta foi realmente respondida.
2.  Identifique qual parte do pedido foi ignorada.
3.  Reformule o tema principal de maneira explícita.
4.  Defina o formato esperado.
5.  Informe a quantidade de itens quando necessário.
6.  Peça para usar somente as fontes do notebook quando essa for a
    intenção.
7.  Gere uma nova resposta e compare com a anterior.
8.  Registre o problema como parte do processo de aprendizagem.

## Importante

As cicatrizes não significam necessariamente que as fontes estejam
erradas. Elas registram situações em que a resposta gerada não
correspondeu exatamente à solicitação feita durante o experimento.
