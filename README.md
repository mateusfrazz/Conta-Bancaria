# 💰 Desafio: Sistema de Conta Bancária

Este repositório contém a implementação de um sistema básico de gerenciamento de contas bancárias em TypeScript, onde apliquei conceitos de **modificadores de acesso** (`public` e `private`) e **encapsulamento**. 

---

## 📋 Funcionalidades

1. **Criar uma conta bancária**:
   - Cada conta possui:
     - Nome do titular (`public`).
     - Saldo (`private`).

2. **Operações disponíveis**:
   - Depositar valores na conta.
   - Sacar valores (com validação de saldo).
   - Exibir o saldo atual.
   - Mostrar um resumo com informações do titular e do saldo.

3. **Validações implementadas**:
   - Depósitos devem ser valores positivos.
   - Saques não podem exceder o saldo disponível.
   - O saldo é protegido por encapsulamento e não pode ser acessado diretamente.

---

## 🛠️ Tecnologias utilizadas

- **TypeScript**: Linguagem principal para aplicar boas práticas de programação orientada a objetos (POO).
- **Node.js** (opcional): Para testar o código em um ambiente local.

---

## 🚀 Como executar

1. Certifique-se de ter o Node.js instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-conta-bancaria.git
