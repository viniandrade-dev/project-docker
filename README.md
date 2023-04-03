#  PROJECT-DOCKER !
<!-- Olá, Tryber!
Esse é apenas um arquivo inicial para o README do seu projeto.
É essencial que você preencha esse documento por conta própria, ok?
Não deixe de usar nossas dicas de escrita de README de projetos, e deixe sua criatividade brilhar!
:warning: IMPORTANTE: você precisa deixar nítido:
- quais arquivos/pastas foram desenvolvidos por você; 
- quais arquivos/pastas foram desenvolvidos por outra pessoa estudante;
- quais arquivos/pastas foram desenvolvidos pela Trybe.
-->

Projeto desenvolvido enquanto aluno da Trybe para praticar conceitos de containers, images e como orquestrar uma aplicação utilizando Dockerfile e docker-compose.

## Sobre o projeto

- O projeto consiste de uma aplicação todo list clássica. O back-end e front-end foram desenvolvidos previamente pela Trybe, ficando responsável pelo aluno desenvolver o código dos Dockerfiles nos diretórios./docker/todo-app/front-end/, ./docker/todo-app/back-end/ e ./docker/todo-app/tests/. Também desenvolvi o código do arquvivo docker-compose no diretório ./docker/.
- Os arquivos no diretório ./docker/docker-commands/ são referentes aos requisitos pedidos pela Trybe para o desenvolvimento do projeto. Mais especificamentes os arquivos command01.dc até command08.dc são exercícios com comandos docker. Já os arquivos commands09.dc até command11.dc realizam o build de seus respectivos Dockerfiles. Por fim, o command12.dc é o que roda a aplicação via docker-compose.
- Para rodar a aplicação é preciso ter o docker-compose v1.29 ou mais e rodar o comando docker-compose up -d em ./docker. Após isso basta acessar o localhost na porta em que o front-end está hospedado =)
