
# Sistema Bancário em Python

Este projeto implementa um sistema bancário simples em Python, com as operações essenciais: depósito, saque e extrato. O objetivo é simular as funcionalidades básicas de um banco, permitindo a prática de lógica de programação e manipulação de dados. O sistema também considera regras como limite diário de saques e registro detalhado das operações para extrato. Funcionalidades:

- Depósito de valores positivos
- Saque com limite por operação e limite diário de saque
- Exibição do extrato com todas as transações realizadas 
- Controle de saldo atualizado a cada operação

## CÓDIGO APRIMORADO

🔧Melhorias Implementadas no Sistema Bancário

Nesta etapa do projeto, o código original do sistema bancário foi refatorado com o uso de funções específicas para cada operação: depósito, saque e extrato. Essa refatoração teve como objetivo melhorar a estrutura, legibilidade e manutenção do sistema, além de aplicar boas práticas de programação com foco na reutilização de código. 

✅ O que foi melhorado:

- #### Modularização do código Cada funcionalidade principal foi isolada em uma função:

- realizar_deposito() 
- realizar_saque() 
- exibir_extrato()

Isso permite que o código seja mais organizado, reutilizável e fácil de testar individualmente.

- #### Separação de responsabilidades 

O código agora segue uma lógica mais clara, onde cada função tem uma única responsabilidade. Isso reduz a complexidade do main() e facilita futuras alterações.

- #### Facilidade de manutenção e evolução Com as funções isoladas, a inclusão de novas regras (como taxas bancárias, autenticação, limites diferenciados etc.) se torna mais simples e segura, evitando efeitos colaterais em outras partes do sistema.

- #### Leitura e entendimento simplificados 

A estrutura refatorada melhora significativamente a compreensão do código, tanto para o próprio autor quanto para outros desenvolvedores que venham a colaborar ou revisar o projeto.
