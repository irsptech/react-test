# react-test-irsp

Olá! Você é muito bem-vindo aqui na IRSP Tech.

Este teste tem como objetivo a criação de uma aplicação para manipular usuários. Você fará chamadas para uma API para recuperar, atualizar, criar e excluir dados de usuários.

Para este projeto, precisamos de três telas:

Home: Exiba todos os usuários existentes, com opções para criar um novo usuário, editar ou excluir usuários existentes.

Cadastro de usuários: Formulário de criação de usuário, com campos relevantes, como nome, e-mail, senha, etc.

Editar usuário: Formulário de edição de usuário, permitindo atualizar os detalhes do usuário.

Você precisará interagir com a API para obter os dados iniciais e manipulá-los conforme necessário.

## Desafio 1
Faça uma requisição GET para buscar todos os usuários da API. Para realizar esse desafio, você pode utilizar uma lista pronta ou criar sua própria lista.
  - https://jsonplaceholder.typicode.com/users
  - https://my-json-server.typicode.com/

Use esses dados para preencher a página inicial. Cada usuário deve ter opções para editar e excluir. Quando o botão de exclusão for clicado, uma requisição DELETE deve ser feita para excluir o usuário da API. Dica: axios é um ótimo cliente HTTP para fazer essas requisições.

## Desafio 2
Na tela de criação do usuário, faça uma requisição POST para a API com os dados do novo usuário quando o formulário for enviado. O usuário deve ser adicionado à lista na tela inicial após a criação bem-sucedida.

## Desafio 3
Na tela de edição do usuário, faça uma requisição PUT para a API com os detalhes atualizados do usuário quando o formulário for submetido. Os detalhes atualizados do usuário devem ser refletidos na lista na tela inicial.

## Desafio Extra
Garanta que sua aplicação seja responsiva e amigável para dispositivos móveis. Lembre-se da importância da semântica HTML - escolha os elementos apropriados para cada parte da interface do usuário.

E mais: ao terminar, envie-nos seu repositório! Adoraríamos ver o que você conseguiu criar.

## Diferenciais
- Utilizar Redux para controle de estado.
- Realizar commits frequentes para que possamos acompanhar a evolução do seu trabalho.

Boa sorte! Estamos ansiosos para ver o que você vai criar.
