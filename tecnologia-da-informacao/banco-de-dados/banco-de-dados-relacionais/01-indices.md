---
titulo: Índices
---
- [O que são indexes de bancos de dados e quando pode ser útil em nossa aplicação?](https://dev.to/gabrielgcj/o-que-sao-indexes-de-bancos-de-dados-e-quando-pode-ser-util-em-nossa-aplicacao-4kmg): São estruturas de dados usadas para acelerar as consultas em um banco de dados.
- [Índices e o excesso de coisa boa – Parte 01: identificando casos críticos](https://imasters.com.br/banco-de-dados/indices-e-o-excesso-de-coisa-boa-parte01-identificando-casos-criticos): O índice é uma benção no universo dos bancos de dados.
- [Índices: Equilibrando os pratos da balança](https://imasters.com.br/banco-de-dados/indices-equilibrando-os-pratos-da-balanca): Desde que inventaram os primeiros computadores, os profissionais da área de tecnologia da informação são pressionados a desenvolver aplicações em prazos cada vez menores. 

# Índices

São estruturas de dados usadas para acelerar as consultas em um banco de dados.

São muito bons para melhorar performance de consultas (os SELECTs), mas eles causam uma sobrecarga nas operações de inclusão, alteração ou exclusão de dados (INSERTs, UPDATEs e DELETEs).

Um bom índice deve ter alta cardinalidade, isto é, usar valores que são raramente repetidos. Dessa forma, um valor pesquisado vai selecionar um pequeno número de registros (e muitas vezes um único registro, como acontece quando temos índices do tipo UNIQUE). Por exemplo: nunca se devem indexar campos do tipo SIM ou NÃO, já que eles selecionam metade de toda tabela.

## Índices não-clusterizados

Estes são catálogos construídos a partir dos dados da tabela, nos mesmos moldes do índice remissivo dos livros que eu descrevi anteriormente. Cada tabela pode ter quantos índices não-clusterizados que se deseje criar.

## Índices clusterizados

Esse índice redefine a ordenação física em que os dados são armazenados. Isso quer dizer que os dados são inseridos nas páginas de dados de tal maneira que sejam fisicamente gravados na ordem desejada. Por essa razão, cada tabela pode ter no máximo um índice clusterizado.
