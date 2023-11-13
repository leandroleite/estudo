---
titulo: Manipulação de arrays
---
- [Conhecendo map, filter e reduce em JavaScript](https://hcode.com.br/blog/conhecendo-map-filter-reduce-em-javascript): Manipular arrays é um dos trabalhos mais repetitivos que realizamos ao trabalhar com JavaScript. E há três métodos muito conhecidos que nos ajudam nessa manipulação: map(), filter() e reduce(). Eles são métodos conhecidos, mas nem sempre lembramos o objetivo de cada um deles.

# Manipulação de arrays

Manipular arrays é um dos trabalhos mais repetitivos que realizamos ao trabalhar com JavaScript.

## map()

Executa uma função em todos os itens de um array. Retorna um novo array.

~~~javascript
arr.map(function(elemento, índice, array){  }, this);
~~~

## filter()

Filtra um array. Retorna um novo array.

~~~javascript
arr.filter(function(elemento, índice, array){  }, this);
~~~

## reduce()

Reduz um array em um único resultado.

~~~javascript
arr.reduce(function(acumulador, valorAtual, [indice , array]), valorInicial);
~~~
