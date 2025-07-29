# 🏦 Sistema Bancário em Python

Este é um projeto simples de terminal feito em Python que simula um sistema bancário básico com as operações de **depósito**, **saque**, **extrato** e **encerramento da sessão**.

---

## 📋 Regras de Negócio

O sistema opera com as seguintes regras:

- **Saldo Inicial:** O saldo da conta começa em R$ 0.
- **Limite de Saque por Operação:** Cada saque não pode exceder **R$ 500**.
- **Limite de Saques Diários:** São permitidos no máximo **3 saques por dia**.
- **Validação de Depósito:** Apenas valores **positivos** podem ser depositados.
- **Validação de Saque:**
  - Não é possível sacar um valor **maior que o saldo disponível**.
  - Não é possível sacar um valor que **exceda R$ 500** por operação.
  - Não é possível realizar saques se o **limite diário de 3 saques** for atingido.
  - Apenas valores **positivos** podem ser sacados.

---

## 🚀 Melhorias Implementadas em relação à versão inicial no link: https://github.com/digitalinnovationone/trilha-python-dio/blob/main/00%20-%20Fundamentos/desafio.py

A versão aprimorada deste código inclui as seguintes melhorias:

- ✅ **Padronização do Menu:** O menu de opções agora é mais claro e utiliza `[D]`, `[S]`, `[E]`, `[F]` para fácil identificação.
- ✅ **Tratamento de Entrada:** A entrada do usuário para as opções do menu (`input(menu).upper()`) é convertida para maiúscula, garantindo que o sistema funcione independentemente de digitar `d` ou `D`, por exemplo.
- ✅ **Mensagens de Erro Aprimoradas:** Mensagens mais descritivas informam o motivo exato da falha da operação (ex: `"O valor informado deve ser maior que zero."`).
- ✅ **Opção de Sair (Finalizar):** Adição da opção `[F] Finalizar e sair`, que encerra o programa com uma mensagem de despedida.
- ✅ **Clareza no Extrato:** Exibição da mensagem `"Não foram realizadas movimentações."` de forma mais amigável quando o extrato está vazio.

---

## 📌 English Version
# 🏦 Python Banking System

This is a simple terminal-based project written in Python that simulates a basic banking system with operations like **deposit**, **withdrawal**, **statement**, and **exit**.

---

## 📋 Business Rules

The system operates with the following rules:

- **Initial Balance:** Account balance starts at R$ 0.
- **Withdrawal Limit per Operation:** Each withdrawal cannot exceed **R$ 500**.
- **Daily Withdrawal Limit:** A maximum of **3 withdrawals per day** is allowed.
- **Deposit Validation:** Only **positive values** can be deposited.
- **Withdrawal Validation:**
  - You cannot withdraw more than the **available balance**.
  - You cannot withdraw an amount that exceeds the **R$ 500 per-operation limit**.
  - You cannot perform more than **3 withdrawals per day**.
  - Only **positive values** can be withdrawn.

---

## 🚀 Improvements Made (compared to the initial version)

The improved version of this code includes the following enhancements:

- ✅ **Standardized Menu:** The options menu is now clearer, using `[D]`, `[S]`, `[E]`, `[F]` for easier identification.
- ✅ **Input Handling:** The user's input for menu options (`input(menu).upper()`) is converted to uppercase, ensuring the system works whether the user types `d` or `D`, for example.
- ✅ **Improved Error Messages:** More descriptive messages now explain the exact reason an operation failed (e.g., `"The entered amount must be greater than zero."`).
- ✅ **Exit Option:** Added the `[F] Finish and Exit` option, which ends the program with a farewell message.
- ✅ **Clearer Statement Display:** When no transactions have occurred, the message `"No transactions have been made."` is shown in a cleaner way.

---


