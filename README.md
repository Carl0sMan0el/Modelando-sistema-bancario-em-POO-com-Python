# Sistema Bancário em Python

Este projeto visa modelar um sistema bancário utilizando conceitos de Programação Orientada a Objetos (POO) em Python. O sistema permite a criação de contas bancárias, depósitos, saques, transferências entre contas e consulta de saldo.

## Funcionalidades

- **Criação de Contas:** Permite criar contas bancárias com um número único de conta e um titular.
- **Depósitos:** Permite adicionar fundos à conta.
- **Saques:** Permite retirar fundos da conta, desde que o saldo seja suficiente.
- **Transferências:** Permite transferir fundos entre contas.
- **Consulta de Saldo:** Permite consultar o saldo disponível na conta.

## Estrutura do Código

O código está organizado em classes para representar os diferentes componentes do sistema bancário.

### Classes Principais

#### ContaBancaria

Representa uma conta bancária.

##### Atributos:

- `numero_conta`: Número único da conta.
- `titular`: Nome do titular da conta.
- `saldo`: Saldo disponível na conta.

##### Métodos:

- `__init__(self, numero_conta, titular, saldo=0)`: Inicializa uma nova conta bancária.
- `depositar(self, valor)`: Adiciona fundos à conta.
- `sacar(self, valor)`: Retira fundos da conta, se o saldo for suficiente.
- `consultar_saldo(self)`: Retorna o saldo disponível na conta.
- `transferir(self, valor, conta_destino)`: Transfere fundos para outra conta.


