---
titulo: Operadores e expressões booleanos
---

# Operadores e expressões booleanos

Expressões booleanas em Python são expressões que resultam em True (verdadeiro) ou False (falso), usando operadores de comparação (==, !=, <, >, <=, >=) para comparar valores e operadores lógicos (and, or, not) para combinar condições, fundamentais para controles de fluxo como if e while, e a capitalização de True e False é obrigatória.

## Operadores de Comparação (Relacionais)

Comparam valores e retornam um booleano.

- == (igual a): 5 == 5 é True.
- != (diferente de): 5 != 6 é True.
- < (menor que): 1 < 2 é True.
- \> (maior que): 10 > 5 é True.
- <= (menor ou igual a): 5 <= 5 é True.
- \>= (maior ou igual a): 10 >= 5 é True.

## Operadores Lógicos

Operam em valores booleanos.

- and: Retorna True se ambas as condições forem verdadeiras. Ex: (2 > 1) and (5 < 10).
- or: Retorna True se pelo menos uma condição for verdadeira. Ex: (2 > 1) or (5 > 10).
- not: Inverte o valor booleano. Ex: not (2 > 1) é False.

## Uso em Condicionais

São a base para decisões no código.

~~~python
idade = 20
if idade >= 18:
    print("É maior de idade") # Saída: É maior de idade
else:
    print("É menor de idade")
~~~

## Conversão Implícita (Falsy/Truthy)

Em Python, certos valores são "falsos" (falsy) e outros "verdadeiros" (truthy) em contextos booleanos.

- Falsy: 0, None, strings vazias "", listas vazias [], tuplas vazias (), dicionários vazios {}.
- Truthy: Qualquer valor não-vazio ou não-zero.

~~~python
if "Olá": # String não-vazia é True
    print("Esta string é 'truthy'") # Saída: Esta string é 'truthy'
~~~
