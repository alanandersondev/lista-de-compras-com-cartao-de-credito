# 💳 Controle de Compras com Cartão de Crédito

Este projeto simula um **sistema de controle de compras em um cartão de crédito**, permitindo ao usuário registrar 
compras, validar limite disponível, listar compras realizadas em ordem crescente e exibir o saldo final do cartão.

Projeto focado na prática de **Programação Orientada a Objetos (POO)**, **listas**, **ordenação** e **entrada de 
dados via terminal** em Java.

---

## 📌 Funcionalidades

- 💰 Definir limite do cartão de crédito
- 🛒 Registrar compras com descrição e valor
- ❌ Bloquear compras por saldo insuficiente
- 📋 Listar compras realizadas
- 🔃 Ordenar compras por valor
- 📊 Exibir saldo final do cartão

---

▶️ Execução do Programa

Ao iniciar o programa, o usuário define o limite do cartão e, em seguida, pode cadastrar compras até que o saldo 
seja insuficiente ou escolha sair.

```txt
Digite o limite do cartão:
1000
Digite a descrição da compra:
Fone
Digite o valor da compra:
200
Compra realizada!
Digite 0 para sair ou 1 para continuar
1
Digite a descrição da compra:
Mouse
Digite o valor da compra:
150
Compra realizada!
Digite 0 para sair ou 1 para continuar
0
***********************
COMPRAS REALIZADAS:

Mouse - 150.0
Fone - 200.0

***********************

Saldo do cartão: 650.0
```
---
## 🛒 Compra

A classe Compra representa uma compra realizada com:

- 📌 Descrição
- 💲 Valor da compra

Ela implementa a interface Comparable, permitindo que as compras sejam ordenadas pelo valor.

  ---
  
## 💳 Cartão de Crédito

A classe CartaoDeCredito é responsável por:

- Armazenar o limite do cartão
- Controlar o saldo disponível
- Validar se a compra pode ser realizada
- Armazenar a lista de compras

---

## 📊 Regra de Negócio
```txt
Se valor da compra <= saldo → compra aprovada
Se valor da compra > saldo → compra recusada
```
---

##🛠️ Tecnologias Utilizadas

- ☕ Java
- 🧠 Programação Orientada a Objetos (POO)
- 📋 Listas (ArrayList)
- 🔃 Ordenação (Collections.sort)
- 🔁 Laços de repetição (while)
- 🔐 Encapsulamento
- ⌨️ Entrada de dados com Scanner

## 📚 Conceitos Aplicados

- Classes e objetos
- Encapsulamento
- Interfaces (Comparable)
- Controle de fluxo
- Regras de negócio
- Manipulação de listas
- Ordenação de dados

## 🧱 Estrutura do Projeto
```txt
src
├── Principal.java
├── CartaoDeCredito.java
└── Compra.java
```
