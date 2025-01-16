# Jogo de Pedra, Papel, Tesoura, Lagarto, Spock em C

Este é um projeto simples de **Pedra, Papel, Tesoura, Lagarto, Spock** desenvolvido em **C**. O jogo permite que o jogador jogue contra o computador, onde o jogador escolhe entre cinco opções: **Pedra**, **Papel**, **Tesoura**, **Lagarto** ou **Spock**, e o computador escolhe aleatoriamente entre as opções. O vencedor é determinado com base nas regras do jogo.

## Regras do Jogo

- **Pedra** vence **Tesoura** e **Lagarto**.
- **Tesoura** vence **Papel** e **Lagarto**.
- **Papel** vence **Pedra** e **Spock**.
- **Lagarto** vence **Papel** e **Spock**.
- **Spock** vence **Tesoura** e **Pedra**.
- Se ambos escolherem a mesma opção, é um empate.

## Funcionalidades

- **Jogador vs Computador:** O jogador escolhe entre **Pedra**, **Papel**, **Tesoura**, **Lagarto** ou **Spock** e o computador faz uma escolha aleatória.
- **Exibição do Resultado:** O resultado da partida (vencedor ou empate) é exibido no console.
- **Múltiplas Rodadas:** O jogador pode jogar várias rodadas, e o jogo continua até ser interrompido.

## Tecnologias Utilizadas

- **Linguagem:** C
- **Bibliotecas:** Nenhuma biblioteca externa (utiliza apenas as funções básicas da linguagem C como `stdio.h`, `stdlib.h`, e `time.h`).

## Como Jogar

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/seunome/pedra-papel-tesoura-lagarto-spock.git
