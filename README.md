# DesafioControleFluxo

Este projeto consiste em um programa Java que exemplifica o uso de controle de fluxo por meio de um cenário de contagem. Ao executar o programa, você deve fornecer dois números inteiros como parâmetros via terminal. O programa então realiza uma contagem incrementada entre esses números e imprime cada número no console. Se o primeiro número for maior ou igual ao segundo, uma exceção personalizada `ParametrosInvalidosException` é lançada, sinalizando que o segundo parâmetro deve ser maior que o primeiro.

## Funcionalidades

- Recebe dois números inteiros como entrada.
- Realiza uma contagem incrementada entre esses números e imprime cada número no console.
- Lança uma exceção personalizada `ParametrosInvalidosException` se o primeiro número for maior ou igual ao segundo.

## Utilização

1. Clone este repositório.
2. Compile e execute a classe `Contador.java`.
3. Siga as instruções para fornecer os números via terminal e observe a contagem e exceções geradas conforme necessário.

## Exemplo de Uso

Digite o primeiro parâmetro:
10
Digite o segundo parâmetro:
5
Lançando ParametrosInvalidosException: O segundo parâmetro deve ser maior que o primeiro


## Exceção Personalizada

A classe `ParametrosInvalidosException` representa a exceção customizada para lidar com o caso em que o segundo parâmetro é menor ou igual ao primeiro. Isso demonstra o uso avançado de controle de fluxo para garantir a integridade dos parâmetros de entrada.

