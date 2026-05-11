# 💳 Controle de Cartão de Crédito - Compras com Ordenação em Java

[![Java](https://img.shields.io/badge/Java-17%2B-007396?logo=java)](https://www.oracle.com/java/technologies/javase-downloads.html)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

> Sistema interativo que simula o controle de um cartão de crédito: define limite, registra compras, verifica saldo disponível e ao final lista todas as compras ordenadas por valor – tudo em Java puro.

## 📌 Sobre o projeto

Este código foi desenvolvido durante meus estudos de Java e Programação Orientada a Objetos. Ele resolve um problema comum: **gerenciar os gastos de um cartão de crédito de forma simples e intuitiva**.

O fluxo do programa:

1. O usuário informa o **limite** do cartão.
2. Em um loop, o usuário digita descrição e valor de uma compra.
3. O sistema verifica se há **saldo** suficiente:
   - Se sim, registra a compra e pergunta se o usuário quer continuar.
   - Se não, encerra o loop e exibe o resumo.
4. Ao final, todas as compras são **ordenadas do menor para o maior valor** (usando `Comparable`) e exibidas junto com o saldo restante.

## 🧠 Conceitos aplicados

- **Encapsulamento** – atributos privados com getters (limite, saldo, compras)
- **ArrayList** – armazenamento dinâmico das compras
- **Classes e objetos** – `CartaoDeCredito`, `Compra` e `Main`
- **Interface `Comparable`** – implementação do método `compareTo` para ordenar por valor
- **Collections.sort()** – ordenação automática da lista
- **Interação com usuário via `Scanner`** – entrada de dados no console
- **Controle de fluxo** – loop `while` com condição de saída

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/cartao-credito.git
