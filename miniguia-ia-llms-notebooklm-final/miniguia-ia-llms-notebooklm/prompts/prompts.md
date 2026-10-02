# Engenharia de Prompts

## Objetivo

Os prompts foram usados para transformar o NotebookLM em uma ferramenta
de estudo ativo, solicitando explicações em diferentes níveis de
profundidade e formatos.

## 1. Prompt para iniciante

> Com base exclusivamente nas fontes deste notebook, explique o que é
> Inteligência Artificial Generativa. Considere que sou iniciante em
> tecnologia. Utilize linguagem simples e dê três exemplos práticos.

**Por que funciona:** define a base de informação, o público e o formato
desejado.

## 2. Prompt para explicação simples + técnica

> Com base nas fontes, explique o que é um Large Language Model (LLM).
> Explique primeiro de forma simples e depois apresente uma explicação
> um pouco mais técnica.

**Por que funciona:** obriga a separar dois níveis de explicação.

## 3. Prompt para organizar conceitos

> Com base nas fontes, explique a relação entre Inteligência Artificial,
> Machine Learning, Deep Learning, IA Generativa e LLMs. Organize os
> conceitos do mais amplo para o mais específico.

**Por que funciona:** pede uma estrutura explícita para evitar uma lista
desconectada.

## 4. Prompt para resumo

> Faça um resumo de \[TEMA\] em 5 pontos. Para cada ponto, explique o
> conceito em uma ou duas frases e dê um exemplo.

## 5. Prompt para comparação

> Compare \[A\] e \[B\] em uma tabela com as colunas: definição,
> finalidade, exemplo, vantagem e limitação.

## 6. Prompt para corrigir uma resposta fora do assunto

> Minha pergunta é especificamente sobre \[TEMA\]. A resposta anterior
> não respondeu ao que foi solicitado. Refaça a resposta focando somente
> em \[TEMA\] e organize em: definição, funcionamento e exemplo.

## 7. Prompt para cuidados de um iniciante

> Com base exclusivamente nas fontes deste notebook, liste 5 cuidados
> que uma pessoa iniciante deve ter ao utilizar LLMs. Para cada cuidado,
> explique o motivo em uma frase e dê um exemplo prático.

## 8. Prompt para verificar aderência

> Verifique se sua resposta responde diretamente à pergunta. Se algum
> trecho não responder ao que foi solicitado, remova-o e refaça a
> resposta de forma objetiva.

## O que foi aprendido

As experiências mostraram que especificar **tema + público + fonte +
formato + quantidade de itens** ajuda a tornar a tarefa mais clara.
Também foi importante verificar a resposta depois de gerada, porque uma
resposta pode repetir conteúdo anterior ou sair do foco da pergunta.
