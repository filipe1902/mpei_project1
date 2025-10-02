# Fake News Detector -- MPEI Projeto 1

## Autores

-   Gonçalo Ribau (119560)
-   Filipe Marques (120303)
  
  Dezembro 2024

------------------------------------------------------------------------

## Descrição

Este projeto consiste numa aplicação capaz de **analisar notícias e
classificá-las como verdadeiras ou falsas**, combinando três técnicas de
forma integrada: **Bloom Filter**, **Naive Bayes** e **MinHash**.

------------------------------------------------------------------------

## Funcionamento

1.  **Entrada do Utilizador**
    -   O programa solicita a **fonte**, o **título** e o **conteúdo**
        da notícia.
2.  **Verificação com Bloom Filter**
    -   Caso a **fonte esteja associada a notícias falsas**, a notícia é
        automaticamente classificada como **falsa**.\
    -   Se não estiver, o programa continua a análise.
3.  **Classificação com Naive Bayes**
    -   O conteúdo da notícia é avaliado através de um classificador
        Naive Bayes treinado com datasets de notícias verdadeiras e
        falsas.
4.  **Otimização com MinHash**
    -   Antes do treino, o MinHash remove notícias redundantes ou
        demasiado semelhantes, garantindo **eficiência** e **melhor
        desempenho** do classificador.

------------------------------------------------------------------------

