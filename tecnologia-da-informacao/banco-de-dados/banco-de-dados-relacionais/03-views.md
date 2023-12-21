---
titulo: Views
---
- [Entendendo Views, Sequences e Synonyms](https://www.dio.me/articles/entendendo-views-sequences-e-synonyms): No contexto de bancos de dados relacionais, especialmente em relação à Linguagem de Consulta Estruturada (SQL), existem diversos recursos destinados a auxiliar no aperfeiçoamento da manipulação de dados, otimização de consultas e no gerenciamento do banco.
- [https://rockcontent.com/br/blog/view-materializada/](https://rockcontent.com/br/blog/view-materializada/): Uma view materializada representa uma seleção de dados gravada em uma nova tabela física no banco de dados. Sua utilização ajuda a melhorar a performance da aplicação, a diminuir o consumo de recursos de máquina e a reduzir os custos de processamento.

# Views

- É uma tabela virtual que representa o resultado de uma consulta SQL pré-definida.
- Essencialmente, não há armazenamento físico dos dados da tabela original, mas sim do query realizado para a obtenção dessa tabela; elas podem ser criadas a partir de uma ou mais tabelas, bem como por meio de outras visões.
- Outra característica é que, assim como qualquer outra tabela, pode-se realizar inserções, exclusões, atualizações e consultas com ela.

## View Materializada

É o resultado de uma query ou seleção feita em uma ou mais tabelas de um banco de dados e o conteúdo retornado é armazenado no formato de uma nova tabela no banco.
