---
titulo: Sum
---
- [Python Numpy transpose() Função](https://www.delftstack.com/pt/api/numpy/python-numpy-transpose/): Python Numpy numpy.transpose() inverte os eixos do array de entrada ou simplesmente transpõe a matriz de entrada.

# Sum

Retorna a soma

## Array 1D

Retorna um **escalar** com a soma dos valores.

~~~python
a = np.array([1,2,3,4,5])
prod = sum(a)
# 15
~~~

## Array 2D

Retorna um array **escalar** com a soma dos valores das colunas.

~~~python
a=np.array([[3,4],
            [4,5]])
prod = sum(a)
# [7 9]
~~~
