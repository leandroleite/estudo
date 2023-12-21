---
titulo: Triggers (Gatilhos)
---
- [O que é e como usar trigger em SQL](https://www.alura.com.br/artigos/trigger-em-sql): Quando estamos trabalhando com bancos de dados relacionais geralmente temos a necessidade de realizar uma determinada ação de acordo com algum evento que acontecer, tipo um INSERT, UPDATE, DELETE, e é isso que o Trigger nos possibilita no SQL.

# Triggers (Gatilhos)

É um procedimento armazenado no banco de dados que é chamado automaticamente sempre que ocorre um evento especial no banco de dados.

## Vantatens

- Gerar alguns valores de coluna derivados automaticamente;
- Aplicar a integridade referencial;
- Registro de eventos e armazenamento de informações no acesso à tabela;
- Auditoria;
- Replicação síncrona de tabelas;
- Imposição de autorizações de segurança;
- Impedir transações inválidas.
- 
## Classes

### Triggers DDL (Data Definition Language)

É acionada em eventos que alteram a estrutura (como criar, modificar ou soltar uma tabela) ou em determinados eventos relacionados ao servidor, como alterações de segurança ou atualização de eventos estatísticos.

### Triggers DML (Data Modification Language)

O evento de disparo é uma declaração de modificação de dados; poderia ser uma instrução de inserção, atualização ou exclusão em uma tabela ou em uma exibição.

