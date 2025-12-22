---
titulo: Booleanos, inteiros e números de ponto flutuante
---

# Booleanos, inteiros e números de ponto flutuante

Em Python, **Booleanos** (_bool_) representam _True_ ou _False_, **Inteiros** (_int_) são números inteiros (sem casas decimais) e **Pontos Flutuantes** (_float_) são números com casas decimais, sendo que o Python gerencia automaticamente esses tipos numéricos, com _int_ tendo precisão ilimitada e _float_ usando o formato de ponto flutuante padrão.

## Booleanos (bool)

Representam valores lógicos: _True_ (verdadeiro) ou _False_ (falso).

- São fundamentais para controle de fluxo (condicionais _if/else_) e lógica.
- _0_, _0.0_, _None_, e sequências vazias (_""_, _[]_, _()_) são considerados "falsos" em contextos booleanos, enquanto outros valores são "verdadeiros".

~~~python
# Exemplo de Booleanos
verdadeiro = True
falso = False
print(type(verdadeiro)) # <class 'bool'>
~~~

## Inteiros (int)

Números inteiros (positivos, negativos, ou zero) sem parte fracionária, como _10_, _-5_, _0_.

- Em Python, inteiros têm precisão ilimitada, o que é uma vantagem sobre outras linguagens.

~~~python
# Exemplo de Inteiros
idade = 30
quantidade = -100
print(type(idade)) # <class 'int'>
~~~

## Pontos Flutuantes (float)

Números com casas decimais (números reais), como _3.14_, _0.001_, _7.0_.

- É o tipo usado para representar frações e medidas mais precisas.
- Operações entre _int_ e _float_ geralmente resultam em float.

~~~python
# Exemplo de Pontos Flutuantes
altura = 1.75
temperatura = -10.5
print(type(altura)) # <class 'float'>

# Conversão de int para float
numero_inteiro = 7
numero_float = float(numero_inteiro)
print(numero_float) # 7.0
print(type(numero_float)) # <class 'float'>
~~~
