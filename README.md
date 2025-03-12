![Sistema Bancário Simples](https://img.shields.io/badge/Sistema_Banc%C3%A1rio_Simples-blue?style=for-the-badge)

Este é um sistema bancário simples desenvolvido em Python como parte de um exercício de programação. O objetivo é simular operações básicas de um banco, como depósitos, saques, consulta de extrato, cadastro de usuários e gerenciamento de contas correntes. O código foi projetado para ser modular, utilizando funções com regras específicas de passagem de argumentos (positional-only, keyword-only e mistos).

## 🟢 Funcionalidades

- **Depósito**: Permite adicionar valores à conta (argumentos apenas por posição).
- **Saque**: Permite retirar valores da conta, com limites de valor e número de saques diários (argumentos apenas por nome).
- **Extrato**: Exibe o histórico de transações e o saldo atual (argumentos mistos: positional-only e keyword-only).
- **Criar Usuário**: Cadastra novos clientes com nome, CPF, data de nascimento e endereço.
- **Criar Conta Corrente**: Cria contas vinculadas a um usuário, com agência fixa ("0001") e número sequencial.
- **Listar Clientes**: Exibe todos os clientes cadastrados.
- **Listar Contas Correntes**: Mostra todas as contas correntes com informações do titular e saldo.

## 🟢Requisitos

- Python 3.6 ou superior (devido ao uso de sintaxe como `positional-only` e `keyword-only` arguments, introduzidos no Python 3.8).
- Não são necessárias bibliotecas externas; o projeto usa apenas a biblioteca padrão `datetime`.

## 🟢Instalação

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/sistema-bancario-simples.git
