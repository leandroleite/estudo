---
titulo: Busca binária
---
- [O poder da busca binária](https://www.dio.me/articles/o-poder-da-busca-binaria): Em algoritmo, a pesquisa binária, também conhecida como pesquisa de vetores, pesquisa logarítmica ou divisão binária, é um algoritmo de pesquisa que encontra a posição de um valor alvo dentro de uma matriz. 

# Busca binária

- É um algoritmo de pesquisa que encontra a posição de um valor alvo dentro de uma matriz.
- É mais rápida que a pesquisa linear, exceto para matrizes pequenas. 
- A matriz deve ser classificada primeiro para poder aplicar a pesquisa binária.
- Existem estruturas de dados especializadas projetadas para pesquisa rápida, como tabelas de hash, que podem ser pesquisadas com mais eficiência do que a pesquisa binária.

## Pesquisa binária

- A pesquisa binária compara o valor de destino com o elemento do meio da matriz.
- Se não forem iguais, a metade em que o alvo não pode estar é eliminada e a busca continua na metade restante, novamente tomando o elemento do meio para comparar com o valor escolhido na busca, e repetindo isso até que o valor alvo seja encontrado.
- Se a pesquisa terminar com a metade restante vazia, o alvo não está na matriz/vetor.

## Algoritmo

- Funciona em arrays/listas definidas.
- Começa comparando um elemento no meio da lista com o valor escolhido.
  - Se o valor de destino corresponder ao elemento, sua posição na matriz será retornada.
  - Se o valor de destino for menor que o elemento, a pesquisa continua na metade inferior da matriz.
  - Se o valor de destino for maior que o elemento, a pesquisa continua na metade superior da matriz.
- Ao fazer isso, o algoritmo elimina a metade em que o valor alvo não pode estar em cada iteração, tornando muito mais rápido.
