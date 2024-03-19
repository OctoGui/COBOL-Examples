# Programa display-timing

Autor: Erik Eriksen

Data: 2021-08-29

Propósito: Testar a velocidade de escrita na tela entre as duas sintaxes de exibição na posição da tela.

Tectônicos: cobc

## Divisão de identificação

O programa é identificado pelo nome `display-timing`.

## Divisão de ambiente

A divisão de ambiente contém a seção de entrada e saída.

## Divisão de dados

A divisão de dados contém a seção de arquivos e a seção de armazenamento de trabalho.

### Seção de Armazenamento de Trabalho

Esta seção declara várias variáveis de trabalho e constantes usadas ao longo do programa.

## Divisão de procedimento

A divisão de procedimento contém a lógica principal do programa, que é dividida em várias seções e parágrafos.

### Procedimento principal

O procedimento principal contém a lógica principal do programa. Ele exibe um prompt para o usuário começar, em seguida, executa uma série de testes de tempo de exibição na tela. Cada teste consiste em exibir um caractere na tela várias vezes e medir quanto tempo isso leva. O procedimento principal então calcula e exibe a diferença de tempo e a média dos tempos de teste.

### compute-and-display-diff

Este parágrafo calcula a diferença de tempo entre o início e o fim de um teste de tempo de exibição da tela e exibe os resultados.

### compute-and-display-average

Este parágrafo calcula a média dos tempos de teste e exibe o resultado.

## Fim do programa display-timing
