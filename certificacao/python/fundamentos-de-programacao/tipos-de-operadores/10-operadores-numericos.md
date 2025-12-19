---
titulo: Operadores numéricos
---

# Operadores numéricos

Em Python, os operadores numéricos (ou aritméticos) realizam cálculos matemáticos básicos e avançados, como adição (+), subtração (-), multiplicação (*), divisão (/), divisão inteira (//), módulo (%) (resto da divisão) e potência ( ou pow()**), além de operadores de atribuição composta (ex: +=) para operações e atribuições simultâneas, e o operador unário de negação para inverter o sinal de um número.

## Principais Operadores Numéricos

- **+ (Adição)**: 5 + 3 resulta em 8.
- **- (Subtração)**: 5 - 3 resulta em 2.
- *** (Multiplicação)**: 5 * 3 resulta em 15.
- **/ (Divisão)**: 6 / 2 resulta em 3.0 (sempre um float).
- **// (Divisão Inteira/Piso)**: 7 // 3 resulta em 2 (arredonda para baixo).
- **% (Módulo)**: 7 % 3 resulta em 1 (o resto da divisão).
- __**(Potência/Exponenciação)__: 2 ** 3 resulta em 8 (2 elevado a 3).
- **pow(base, expoente)**: Alternativa para potência, ex: pow(2, 3).

## Operadores de Atribuição Composta

Esses operadores combinam uma operação e a atribuição à mesma variável:

- a += b é o mesmo que a = a + b.
- a -= b, a *= b, a /= b, a //= b, a %= b funcionam de forma similar.

## Exemplos Práticos

~~~python
a = 10
b = 3

print(f"Adição: {a + b}")        # Saída: 13
print(f"Subtração: {a - b}")     # Saída: 7
print(f"Multiplicação: {a * b}") # Saída: 30
print(f"Divisão: {a / b}")       # Saída: 3.333...
print(f"Divisão Inteira: {a // b}") # Saída: 3
print(f"Módulo: {a % b}")        # Saída: 1
print(f"Potência: {a ** b}")     # Saída: 1000

# Atribuição Composta
a += 5  # a agora é 15 (10 + 5)
print(f"a após += 5: {a}")
~~~

## Ordem de Precedência

Em Python, a ordem de execução segue a matemática, mas com algumas particularidades:

- Parênteses ()
- Potência **
- Multiplicação *, Divisão /, Divisão Inteira //, Módulo % (da esquerda para a direita)
- Adição +, Subtração - (da esquerda para a direita).
