---
titulo: Where
---
- [Numpy.where](https://datascience.eu/pt/programacao/numpy-where/): numpy.where(condição[, x, y]) Elementos de retorno escolhidos entre x ou y, dependendo da condição.

# Where

numpy.where(condição[, x, y]) 

- Elementos de retorno escolhidos entre x ou y, dependendo da condição.

## numpy.where(condição)

- Abreviatura para abreviatura para np.asarray(condição).nonzero()
- Retorna os **índices** que a condição for verdadeira

~~~Python
nomes = np.array(['João', 'Pedro', 'João', 'Paulo'])
# (array([0, 2]),)
~~~

## numpy.where(condição, x, y) 

- Elementos de retorno escolhidos entre x ou y, dependendo da condição.
- Se condição for verdadeiro então retorna x, senão y

~~~Python
a = np.arange(10)
# [0 1 2 3 4 5 6 7 8 9]
np.where(a < 5, a, 10*a)
# [ 0  1  2  3  4 50 60 70 80 90]
~~~
