# Mini Guia --- Fundamentos de IA Generativa e LLMs

## 1. Inteligência Artificial Generativa

A IA generativa é apresentada no material estudado como uma tecnologia
capaz de criar novos conteúdos a partir de padrões aprendidos nos dados.

Exemplos trabalhados no estudo:

-   geração de texto;
-   geração de imagens;
-   apoio à criação de conteúdo e aprendizagem.

## 2. Large Language Model (LLM)

Um LLM é uma rede neural treinada com grandes quantidades de dados
textuais para prever o próximo token de uma sequência.

O material também apresenta:

-   arquitetura Transformer;
-   pesos numéricos;
-   tokens e tokenização;
-   janela de contexto;
-   geração autoregressiva;
-   etapas de treinamento e pós-treinamento.

## 3. Relação entre conceitos

Uma organização didática utilizada no estudo foi:

**IA → Machine Learning → Deep Learning → IA Generativa → LLM**

Essa representação serve para visualizar a relação entre os conceitos
estudados.

## 4. Tokens

O texto é transformado em tokens por um tokenizer. Os tokens são
associados a IDs numéricos e são esses números que o modelo processa.

Um token pode representar uma palavra inteira, parte de uma palavra,
pontuação ou outro elemento.

## 5. Janela de contexto

A janela de contexto é o limite de tokens que pode ser considerado em
uma interação.

Ela influencia:

-   retenção de informações;
-   coerência;
-   quantidade de conteúdo disponível para o modelo;
-   custo e latência.

## 6. Treinamento

Durante o treinamento, o modelo aprende seus pesos a partir dos dados
utilizados no processo.

O estudo descreveu o pré-treinamento como uma etapa baseada na previsão
do próximo token, seguida por etapas de pós-treinamento como SFT e RLHF.

## 7. Inferência

Na inferência, os pesos já treinados são utilizados para produzir uma
saída a partir da entrada recebida.

O material também descreve a geração como um processo de processamento
da entrada e posterior geração dos tokens de saída.

## 8. Por que usar tokens?

O uso de tokens permite transformar linguagem em representações
numéricas processáveis pelo modelo. A tokenização também permite
trabalhar com partes de palavras, pontuação e outros elementos.

## 9. Limitações

Entre as limitações estudadas estão:

-   contexto finito;
-   chamadas stateless;
-   possibilidade de alucinações;
-   não determinismo;
-   dificuldade em matemática exata e lógica formal;
-   ausência de conhecimento em tempo real por padrão.

## 10. Regra prática de estudo

Uma boa utilização de um LLM para aprender não é apenas pedir uma
resposta. É também:

**perguntar → analisar → verificar → reformular → comparar → registrar o
aprendizado.**
