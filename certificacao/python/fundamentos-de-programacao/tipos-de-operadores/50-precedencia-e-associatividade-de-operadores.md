---
titulo: Precedência e associatividade de operadores
---

# Precedência e associatividade de operadores

Em Python, **precedência** define qual operador é executado primeiro (ex: * antes de +), enquanto **associatividade** define a ordem entre operadores de mesma precedência (geralmente da esquerda para a direita, exceto ** que é da direita para a esquerda). Use parênteses () para forçar a ordem desejada, alterando a hierarquia padrão e melhorando a legibilidade.

## Precedência (Hierarquia)

A ordem geral de execução é:

- **Parênteses ()**: A mais alta precedência, altera a ordem.
- __Expoente **__: (Ex: 2**3 é 8, não 2+1 em 2**1+1).
- **Multiplicação** *, **Divisão** /, **Divisão inteira** //, **Módulo** % (mesma precedência).
- **Adição** +, **Subtração** - (mesma precedência).
- **Operadores de Comparação** (>, <, >=, <=, ==, !=).
- **Operadores Lógicos** not, and, or (com not tendo precedência sobre and, e and sobre or).

~~~python
# Exemplo de precedência: Multiplicação antes da adição
resultado = 2 + 3 * 4  # 3 * 4 é calculado primeiro (12), depois 2 + 12 = 14
print(resultado) # Saída: 14
~~~

## Associatividade (Direção)

Quando operadores têm a mesma precedência, a associatividade determina a ordem:

- **Esquerda para Direita**: A maioria dos operadores (como +, -, *, /, //, %, and, or, comparações).

~~~python
# 2 - 3 + 4 é (2 - 3) + 4, não 2 - (3 + 4)
print(2 - 3 + 4) # Saída: 3
~~~

- **Direita para Esquerda**: Operador de expoente ** e atribuição =.

~~~python
# 2 ** 3 ** 2 é 2 ** (3 ** 2), não (2 ** 3) ** 2
print(2 ** 3 ** 2) # Saída: 512 (2 elevado a 9)
~~~

## Parênteses: A Chave para o Controle

Use parênteses () para agrupar partes da expressão, garantindo a ordem de cálculo que você deseja, independentemente da precedência ou associatividade padrão.

~~~python
# Sem parênteses:
print(2 + 3 * 4) # Saída: 14

# Com parênteses:
print((2 + 3) * 4) # Saída: 20 (5 * 4)
~~~
