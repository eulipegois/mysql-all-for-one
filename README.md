# One for All

## Projeto para praticar todos os conceitos de SQL aprendidos. Utilizando um banco de dados chamado Northwind, que será usado neste projeto.

# Tabela de conteúdos

<p align="center">
  <a href="#features">Features</a>
  <a href="#requisitos">Pré requisitos</a>
  <a href="#tech">Tecnologias</a>
  <a href="#autor">Autor</a>
</p>

<h4 align="center"> 
	Projeto Concluído 🚀
</h4>

<h1 id="features">Features</h1>

- [x] 

<h1 id="requisitos">Pré-requisitos</h1>

### Com Docker
 
> :information_source: Rode os serviços `node` e `db` com o comando `docker-compose up -d`.
- Lembre-se de parar o `mysql` se estiver usando localmente na porta padrão (`3306`), ou adapte, caso queria fazer uso da aplicação em containers
- Esses serviços irão inicializar um container chamado `all_for_one` e outro chamado `all_for_one_db`.
- A partir daqui você pode rodar o container `all_for_one` via CLI ou abri-lo no VS Code.

> :information_source: Use o comando `docker exec -it all_for_one bash`.
- Ele te dará acesso ao terminal interativo do container criado pelo compose, que está rodando em segundo plano.
- As credencias de acesso ao banco de dados estão definidas no arquivo `docker-compose.yml`, e são acessíveis no container através das variáveis de ambiente `MYSQL_USER` e `MYSQL_PASSWORD`. 💡

> :information_source: Instale as dependências [**Caso existam**] com `npm install`. (Instale dentro do container)

## Sem Docker

> :information_source: Instale as dependências [**Caso existam**] com `npm install`

<h1 id="tech">Tecnologias</h1>

As seguintes ferramentas foram usadas na construção do projeto:

- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/en/)
- [VScode](https://code.visualstudio.com/)
- [MySQL](https://www.mysql.com/)

<h1 id="autor">Autor</h1>

<p>Luiz Felipe Espindola Gois</p>

[Linkedin](https://www.linkedin.com/in/luizfelipegois/)
[Behance](https://www.behance.net/luizfelipe_gois)