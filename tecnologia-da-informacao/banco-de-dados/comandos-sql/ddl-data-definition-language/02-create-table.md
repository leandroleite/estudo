---
titulo: Create Table
---
- [Sintaxe SQL do grupo DDL – CREATE TABLE](https://douglasgaspar.wordpress.com/2013/10/18/sintaxe-sql-do-grupo-ddl-create-table/): O grupo DDL é responsável pela criação, alteração, remoção ou redefinição de objetos em um banco de dados. 

# Create Table

Comando DDL para criação de tabela.

## Sintaxe

~~~sql
CREATE TABLE [nome_da_tabela](
[col1] [tipo_de_dado] [NOT NULL | NULL] [AUTO_INCREMENT] [UNIQUE | PRIMARY [KEY]],
[col2] [tipo_de_dado] [NOT NULL | NULL] [AUTO_INCREMENT] [UNIQUE | PRIMARY [KEY]],
…
CONSTRAINT [nome] FOREIGN KEY [nome_coluna] REFERENCES [tabela] (campo)
);
~~~

## Atributos

- **NOT NULL**: indica que um campo não poderá ficar nulo
- **NULL**: indica que o campo pode ser nulo
- **AUTO_INCREMENT**: informa ao SGBD que aquela coluna será preenchida automaticamente, por ele, a cada novo registro
- **UNIQUE**: chave secundária da tabela
- **PRIMARY KEY**: chave primária da tabela
- Quando houver, dentro do mesmo par de colchetes, o símbolo **|** significa que deve ser escolhido um **ou** outro atributo para o campo.
- O **;** delimita o final de um comando.
