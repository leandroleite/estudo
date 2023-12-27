---
titulo: Junções (join)
---
- [SQL JOIN  Aprenda INNER, LEFT, RIGHT, FULL e CROSS](https://www.alura.com.br/artigos/join-em-sql): Na linguagem SQL, executamos diversas consultas para geralmente criar relatórios que serão posteriormente utilizados para análise e a tomada de alguma decisão, e para criarmos consultas cada vez mais completas precisamos utilizar várias tabelas em conjunto e para isso usamos os JOINs.

# Junções (join)

Uma cláusula JOIN em SQL, correspondente a uma operação de junção em álgebra relacional, combina colunas de uma ou mais tabelas em um banco de dados relacional. Ela cria um conjunto que pode ser salvo como uma tabela ou usado da forma como está.

## Inner Join

- Compara cada linha da tabela A com as linhas da tabela B para encontrar todos os pares de linhas que satisfazem a condição de junção.
- Se a condição de junção for avaliado como TRUE, os valores da coluna das linhas correspondentes das tabelas A e B serão combinados em uma nova linha e incluídos no conjunto de resultados.

~~~sql
SELECT <select_list> FROM Tabela A
INNER JOIN Tabela B ON A.Key = B.Key
~~~

## Left Join

- Retorna todas as linhas da tabela **“esquerda” A** e as linhas correspondentes ou valores NULL da tabela **“esquerda” A**.

~~~sql
SELECT <select_list> FROM Tabela A
LEFT JOIN Tabela B ON A.Key = B.Key
~~~

## Right Join

- Retorna um conjunto de resultados que inclui todas as linhas da tabela **“direita” B**, com ou sem linhas correspondentes na tabela **“esquerda” A**.

~~~sql
SELECT <select_list> FROM Tabela A
RIGHT JOIN Tabela B ON A.Key = B.Key
~~~

## Full Join

- Retorna todas as linhas das tabelas unidas, correspondidas ou não

~~~sql
SELECT <select_list> FROM Tabela A
FULL JOIN Tabela B ON A.Key = B.Key
~~~

## Cross Join - Produto Cartesiano

- Retorna todas as linhas das tabelas por cruzamento, ou seja, para cada linha da tabela esquerda queremos todos os linhas da tabelas direita ou vice-versa.
- Também é chamado de produto cartesiano entre duas tabelas.

~~~sql
SELECT <select_list> FROM Tabela A
CROSS JOIN Tabela B
~~~

~~~sql
SELECT <select_list> FROM Tabela A, Tabela B
~~~
