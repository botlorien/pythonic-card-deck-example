# FrenchDeck - Um Baralho de Cartas Estilo Francês

Este projeto implementa uma simulação simples de um baralho de cartas no estilo francês utilizando Python. A classe `FrenchDeck` permite criar um baralho com 52 cartas, manipulá-lo e classificá-lo com base no valor das cartas, sendo os naipes ordenados de acordo com um valor predefinido.

## Visão Geral

O código cria uma classe `FrenchDeck` que representa um baralho tradicional com 52 cartas, contendo quatro naipes: espadas, corações, ouros e paus. Além disso, a função `spades_high` ordena as cartas de forma que espadas tenham o valor mais alto, seguidas por corações, ouros e paus.

## Funcionalidades

- Criar um baralho de cartas com 52 cartas.
- Classificar as cartas com base no valor dos naipes, onde espadas têm maior prioridade.
- Manipular o baralho usando funcionalidades integradas como comprimento (`len()`) e indexação (`getitem()`).

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/botlorien/pythonic-card-deck-example.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd frenchdeck
   ```
3. Execução:
   ```bash
   python french_deck.py
   ```

4. Exemplo de saída:
   ```bash
   Card(rank='2', suit='clubs')
   Card(rank='3', suit='clubs')
   ...
   Card(rank='A', suit='spades')

   ```
   
