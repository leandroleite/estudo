---
titulo: Compreensão de listas
---

# Compreensão de listas

Compreensão de listas em Python é uma forma concisa e elegante de criar listas a partir de sequências existentes (como outras listas, tuplas ou range), aplicando expressões e filtros em uma única linha de código, substituindo loops for tradicionais para tornar o código mais limpo, legível e "pythônico". A sintaxe básica é [expressao for item in iteravel if condicao], permitindo transformar e filtrar elementos rapidamente, como gerar uma lista de quadrados ou selecionar números pares.

## Estrutura básica

[expressão for item in iterável if condição]

## Criando uma lista simples

~~~python
# Tradicional
quadrados = []
for x in range(10):
    quadrados.append(x**2)

# Compreensão de lista
quadrados = [x**2 for x in range(10)]
~~~

## Com filtragem (if)

~~~python
# Para incluir apenas números pares:
pares = [x for x in range(20) if x % 2 == 0]
~~~

## Com condicional complexa (if/else)

~~~python
# 'Par' se for par, 'Ímpar' se não for
resultado = ['Par' if x % 2 == 0 else 'Ímpar' for x in range(5)]
~~~

## Manipulando Strings

~~~python
nomes = ['alice', 'bob', 'charlie']
nomes_maiusculos = [nome.upper() for nome in nomes]
~~~

## Com Loops Aninhados

~~~python
lista_a = [1, 2]
lista_b = ['a', 'b']
pares_combinados = [(x, y) for x in lista_a for y in lista_b] 
# [(1, 'a'), (1, 'b'), (2, 'a'), (2, 'b')]
# Os loops aninhados seguem a ordem for externo, for interno, como em loops tradicionais. 
~~~

## Benefícios

- **Concisão**: Menos linhas de código para a mesma tarefa.
- **Legibilidade**: Código mais limpo e fácil de entender (uma vez familiarizado).
- **Eficiência**: Geralmente mais rápido que loops for explícitos.
