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

- [x] Exiba apenas os nomes dos produtos na tabela products.
- [x] Exiba os dados de todas as colunas da tabela products.
- [x] Escreva uma query que exiba os valores da coluna que representa a primary key da tabela products.
- [x] Conte quantos registros existem na coluna product_name da tabela products.
- [x] Monte uma query que exiba os dados da tabela products a partir do quarto registro até o décimo terceiro.
- [x] Exiba os dados das colunas product_name e id da tabela products de maneira que os resultados estejam em ordem alfabética dos nomes.
- [x] Mostre apenas os ids dos 5 últimos registros da tabela products (a ordernação deve ser baseada na coluna id).
- [x] Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.
- [x] Mostre todos os valores de notes da tabela purchase_orders que não são nulos.
- [x] Mostre todos os dados da tabela purchase_orders em ordem decrescente, ordenados por created_by em que o created_by é maior ou igual a 3.
- [x] Exiba os dados da coluna notes da tabela purchase_orders em que seu valor de Purchase generated based on Order é maior ou igual a 30 e menor ou igual a 39.
- [x] Mostre as submitted_date de purchase_orders em que a submitted_date é do dia 26 de abril de 2006.
- [x] Mostre os resultados da coluna supplier_id da tabela purchase_orders em que o supplier_id seja maior ou igual a 1 e menor ou igual 3.
- [x] Mostre somente as horas (sem os minutos e os segundos) da coluna submitted_date de todos registros da tabela purchase_orders.
- [x] Exiba a submitted_date das purchase_orders que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
- [x] Mostre os registros das colunas id e supplier_id das purchase_orders em que os supplier_id sejam tanto 1, ou 3, ou 5, ou 7.
- [x] Mostre todos os registros de purchase_orders que tem o supplier_id igual a 3 e status_id igual a 2.
- [x] Mostre a quantidade de pedidos que foram feitos na tabela orders pelo employee_id igual a 5 ou 6, e que foram enviados através do método(coluna) shipper_id igual a 2.
- [x] Adicione à tabela order_details um registro com order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e inventory_id: 129.
- [x] Adicione com um único INSERT, duas linhas à tabela order_details com os mesmos dados do requisito 20.
- [x] Atualize os dados de discount do order_details para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).

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
