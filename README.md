# ADO 3

## Objetivo

Continue o ADO 2 com AJAX e login/senha.

## Etapas

* 1. Pegue o seu ADO 2 como ponto de partida.
* 2. Termine qualquer coisa que tenha ficado para trás no ADO 2.
* 3. Faça todas as funcionalidades implementadas funcionarem a partir de um único arquivo PHP por meio de AJAX.
* 4. Implemente uma tela de login.
* 5. Garanta que as funcionalidades trazidas do ADO 2 não sejam acessíveis sem que o usuário esteja logado.
* 6. Garanta que usuários não logados sejam redirecionados à tela de login e usuários logados à tela principal.
* 7. Implemente na tela principal o botão de logout por POST.
* 8. Na tela principal, mostre também o nome do usuário que está logado.

A tabela de usuários se chama `usuario` e contém os seguintes campos:

* `chave` - Tipo `INTEGER`, auto-incremento
* `login` - Tipo `TEXT`.
* `senha` - Tipo `TEXT`.
* `nome` - Tipo `TEXT`.

Nenhum dos campos permite `NULL`. Não está sendo pedida nenhuma funcionalidade de cadastro de usuários, portanto você deve pré-popular o banco de dados com os usuários.
