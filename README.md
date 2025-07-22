# 💰 Sistema Bancário em Python

Este é um projeto simples de terminal desenvolvido em Python que simula operações bancárias como **depósito**, **saque** e **emissão de extrato**.

## 🚀 Funcionalidades

- 📥 **Depósito**: Permite depositar valores positivos no saldo da conta.
- 💸 **Saque**:
  - Limite de **R$ 500,00** por saque.
  - Máximo de **3 saques por dia**.
  - Verificação de saldo disponível.
- 📄 **Extrato**: Mostra todas as movimentações e o saldo atual.
- ❌ **Saída**: Encerra o programa.

## ⚙️ Como funciona

O sistema exibe um menu interativo no terminal com as seguintes opções:

O usuário escolhe a operação digitando o número correspondente. O sistema executa a ação e exibe mensagens de sucesso ou erro conforme necessário.

## 🧠 Regras de negócio

- Apenas valores **positivos** são aceitos para depósito e saque.
- O valor máximo por saque é **R$ 500,00**.
- O número máximo de saques por execução é **3**.
- O extrato mostra os depósitos e saques realizados ou informa que nenhuma movimentação foi feita.

## 🛠️ Como executar

1. Tenha o **Python 3** instalado na sua máquina.
2. Salve o código em um arquivo, por exemplo: `sys_bank.py`
3. No terminal, navegue até o diretório do arquivo e execute:

```bash
python sys_bank.py
