---
titulo: Select
---
- [Guia de consultas para o comando SELECT](https://www.devmedia.com.br/sql-select-guia-para-iniciantes/29530): Veremos nesse artigo um pequeno guia de consultas para o comando SELECT, um dos mais importantes da linguagem SQL.
- [google](): sql select

# Select

Permite recuperar os dados de um objeto do banco de dados, como uma tabela, view e, em alguns casos, uma stored procedure (alguns bancos de dados permitem a criação de procedimentos que retornam valor).

## Sintaxe básica

~~~SQL
SELECT <lista_de_campos> FROM <nome_da_tabela>
~~~

## Comando Where

Permite ao comando SQL passar condições de filtragem.

~~~SQL
SELECT campo FROM tabela WHERE campo = 1
~~~

## Ordenação - Order By

Define a ordenação.

~~~SQL
SELECT campo FROM tabela ORDER BY campo
~~~

## Funções de agrupamentos

São cinco as funções básicas de agrupamento:

- **AVG**: Retorna a média do campo especificado
- **MIN/MAX**: Retorna o menor e o maior valor
- **SUM**: Retorna o somatório de um grupo de registros
- **COUNT**: Retorna a quantidade de itens da seleção

## Agrupamento - Group By

Retorna informações agrupadas de um conjunto de registros, estabelecendo uma condição de agrupamento.

~~~SQL
SELECT CODCLIENTE, COUNT(*) FROM PEDIDOS
GROUPY BY CODCLIENTE
~~~

### Having

Filtra a cláusula GROUP BY.

~~~SQL
SELECT CODCLIENTE, COUNT(*) FROM PEDIDOS
GROUPY BY CODCLIENTE HAVING COUNT(*) >= 2
~~~
