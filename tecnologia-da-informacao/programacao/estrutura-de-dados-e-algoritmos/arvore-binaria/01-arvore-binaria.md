---
titulo: Árvore Binária
---
- [Árvores binárias de busca](https://www.ime.usp.br/~pf/algoritmos/aulas/binst.html): Assim como árvores binárias generalizam listas encadeadas, árvores binárias de busca (= binary search trees = BSTs) generalizam listas encadeadas crescentes.
- [Árvore binária de busca](https://pt.wikipedia.org/wiki/%C3%81rvore_bin%C3%A1ria_de_busca): Em Ciência da computação, uma árvore binária de busca (ou árvore binária de pesquisa) é uma estrutura de dados de árvore binária baseada em nós, onde todos os nós da subárvore esquerda possuem um valor numérico inferior ao nó raiz e todos os nós da subárvore direita possuem um valor superior ao nó raiz (esta é a forma padrão, podendo as subárvores serem invertidas, dependendo da aplicação).
- [Árvores binárias](https://www.ime.usp.br/~pf/algoritmos/aulas/bint.html): Uma árvore binária é uma estrutura de dados mais geral que uma lista encadeada.  Este capítulo introduz algumas operações básicas sobre árvores binárias. O capítulo seguinte, Árvores binárias de busca, trata de uma aplicação fundamental.
- [Árvore AVL](https://pt.wikipedia.org/wiki/%C3%81rvore_AVL): Árvore AVL é uma árvore binária de busca balanceada[2], ou seja, uma árvore balanceada (árvore completa) são as árvores que minimizam o número de comparações efetuadas no pior caso para uma busca com chaves de probabilidades de ocorrências idênticas.

# Árvore Binária

Uma árvore binária é uma estrutura de dados mais geral que uma lista encadeada.

## Elementos
- **Nós** - são todos os itens guardados na árvore
- **Raiz** - é o nó do topo da árvore (no caso da figura acima, a raiz é o nó 8)
- **Filhos** - são os nós que vem depois dos outros nós (no caso da figura acima, o nó 6 é filho do 3)
- **Pais** - são os nós que vem antes dos outros nós (no caso da figura acima, o nó 10 é pai do 14)
- **Folhas** - são os nós que não têm filhos; são os últimos nós da árvore (no caso da figura acima, as folhas são 1, 4, 7 e 13)

## Altura e profundidade

- **Altura de um nó x**: é a distância entre x e o seu descendente mais afastado.
- **Altura de uma árvore**: é a altura da raiz da árvore.

Uma árvore com um único nó tem altura 0.

## Árvores Binárias de Busca

É uma estrutura de dados de árvore binária baseada em nós, onde todos os nós da subárvore esquerda possuem um valor numérico inferior ao nó raiz e todos os nós da subárvore direita possuem um valor superior ao nó raiz (esta é a forma padrão, podendo as subárvores serem invertidas, dependendo da aplicação).

O objetivo desta árvore é estruturar os dados de forma a permitir busca binária.

Árvores binárias de busca (Binary Search Trees = BSTs) generalizam listas encadeadas crescentes.

### Complexidade

A complexidade das operações depende diretamente da altura da árvore.

- Árvore Balanceada: **O(log n)**
- Pior caso (degeneração da árvore em lista encadeada): **O(n)**

### Percursos

#### Pré-ordem (ou profundidade)

- Visita a raiz
- Percorre a subárvore esquerda em pré-ordem
- Percorre a subárvore direita em pré-ordem

#### Ordem Simétrica (chaves ordenadas)

- Percorre a subárvore esquerda em ordem simétrica
- Visita a raiz
- Percorre a subárvore direita em ordem simétrica

#### Pós-ordem

- Percorre a subárvore esquerda em pós-ordem
- Percorre a subárvore direita em pós-ordem
- Visita a raiz

## Árvore AVL (Busca Balanceada)

Todas as suas folhas têm aproximadamente a mesma profundidade.

Para garantir essa propriedade em aplicações dinâmicas, é preciso reconstruir a árvore para seu estado ideal a cada operação sobre seus nós (inclusão ou exclusão), para ser alcançado um custo de algoritmo com o tempo de pesquisa.
