# ProjetoConta

Projeto Conta Bancária em C#
Um projeto de console simples para simular operações básicas de uma conta bancária, desenvolvido em C#.

📝 Descrição
Este é um projeto de aprendizado para praticar os conceitos de Programação Orientada a Objetos (POO) em C#, como classes, propriedades e métodos. O objetivo é criar um sistema onde o usuário possa gerenciar uma conta bancária, realizando depósitos e saques.

🚀 Estado Atual
Atualmente, o projeto possui a estrutura inicial:

ContaBancaria.cs: Uma classe que define a estrutura de uma conta bancária com as seguintes propriedades:

Numero (int): O número da conta.

Titular (string): O nome do titular da conta.

Saldo (double): O saldo disponível na conta.

Program.cs: O ponto de entrada da aplicação, com o método Main ainda vazio, pronto para receber a lógica de interação com o usuário.

🛠️ Próximos Passos (To-Do)
Para que o projeto se torne funcional, as seguintes implementações são necessárias:

Criar Construtores na Classe ContaBancaria:

Um construtor que receba o número da conta e o titular.

Um segundo construtor que também inclua um depósito inicial.

Adicionar Métodos à Classe ContaBancaria:

Criar um método Depositar(double quantia) para adicionar valor ao saldo.

Criar um método Sacar(double quantia) para retirar valor do saldo, com uma regra de negócio (ex: cobrança de uma taxa de R$ 5,00 por saque).

Sobrescrever o método ToString() para exibir os dados da conta de forma formatada.

Implementar a Lógica no Program.cs:

Solicitar ao usuário os dados da conta (número, titular).

Perguntar se haverá um depósito inicial.

Instanciar o objeto ContaBancaria.

Exibir os dados da conta.

Criar um menu para que o usuário possa escolher entre Depositar, Sacar e Sair.
