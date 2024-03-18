# Simulador Bancário em Python

Esse projeto é um simulador bancário simples desenvolvido em Python como parte do desafio proposto pelo curso "Formação Pytho Developer" da [DIO (Digital Innovation One)](http://www.dio.me).

## Sobre o projeto

O simulador bancário permite que o usuário realize as seguintes operações:

- Depósito
- Saque
- Exibir extrato
- Criar nova conta
- Listar contas
- Criar novo usuário
- Sair

O código mantém um saldo, um limite de saques e um número de saques para cada conta. Além disso, ele mantém uma lista de usuários e uma lista de contas. Cada conta é associada a um usuário específico.

Quando o usuário seleciona a opção de depósito, o valor informado é adicionado ao saldo da conta atual e registrado no extrato. Quando o usuário seleciona a opção de saque, o valor informado é subtraído do saldo da conta atual, desde que haja saldo suficiente, o valor do saque não exceda o limite e o número de saques não exceda o limite de saques. O extrato é atualizado com o valor do saque.

A opção de exibir extrato mostra as movimentações da conta atual e o saldo atual. A opção de criar nova conta solicita o CPF de um usuário existente e, se encontrado, cria uma nova conta associada a esse usuário. A opção de listar contas mostra as informações de todas as contas existentes.

A opção de criar novo usuário solicita as informações do usuário (CPF, nome, data de nascimento e endereço) e as adiciona à lista de usuários. O CPF deve ser único para cada usuário.

## Técnicas utilizadas

Esse projeto utiliza as seguintes técnicas e conceitos em Python:

- Funções
- Entrada e saída de dados
- Listas
- Controle de fluxo
- Tratamento de exceções

## Importância do projeto para o meu aprendizado

Esse projeto foi importante para o meu aprendizado porque me permitiu aplicar e consolidar meus conhecimentos em Python, especialmente em relação às funções, entrada e saída de dados, listas e controle de fluxo. Além disso, me deu a oportunidade de praticar a organização do código em módulos e funções, bem como a implementação de tratamento de exceções.

## Sobre a DIO

A [DIO (Digital Innovation One)](http://www.dio.me) é uma plataforma de educação online que oferece cursos em tecnologia, com foco em programação, data science, cloud e ciência de dados. Com uma comunidade ativa de mais de 1 milhão de desenvolvedores, a DIO oferece acesso a conteúdo de alta qualidade, projetos práticos e mentoria de especialistas em tecnologia.
