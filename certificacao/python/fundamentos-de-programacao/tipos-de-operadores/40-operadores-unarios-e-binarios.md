---
titulo: Operadores unários e binários
---

# Operadores unários e binários

Em Python, operadores **unários** agem em um único operando (ex: -5 para negar), enquanto **binários** agem em dois operandos (ex: 2 + 3 para somar), sendo os mais comuns os aritméticos (+, -, *, /) e lógicos (and, or, not), além de relacionais e de atribuição, organizados por precedência e com exemplos como o unário - para sinal e binário + para soma ou concatenação.

## Operadores Unários

Operam em um único valor ou variável (operando).

- **+ (Unário Positivo)**: _+5_ (raramente usado, não altera o valor).
- **- (Unário Negativo/Sinal)**: _-5_ (inverte o sinal do número).
- ~ **(Bitwise NOT)**: Inverte os bits (ex: _~5_).
- **not (Negação Lógica)**: _not True_ resulta em _False_.

~~~python
# Exemplo de operador unário
numero = 10
negativo = -numero # O '-' é unário
print(negativo) # Saída: -10

# Exemplo de not
esta_ativo = True
nao_ativo = not esta_ativo # 'not' é unário
print(nao_ativo) # Saída: False
~~~

## Operadores Binários

Requerem dois operandos para formar uma expressão.

- **Aritméticos**: + (soma), - (subtração), * (multiplicação), / (divisão), % (módulo), // (divisão inteira), ** (exponenciação).
- **Relacionais (Comparação)**: ==, !=, <, >, <=, >= (retornam True ou False).
- **Lógicos**: and, or, not (que também pode ser unário).
- **Atribuição**: = (atribuição simples), +=, -= (atribuição aumentada).

~~~python
# Exemplo de operador binário (aritmético)
resultado = 5 + 3 # '+' é binário
print(resultado) # Saída: 8

# Exemplo de operador binário (relacional)
maior = 10 > 5 # '>' é binário
print(maior) # Saída: True

# Exemplo de operador binário (lógico)
print(True and False) # 'and' é binário
~~~

## Diferenças Chave

- **Número de Operandos**: Unários usam 1, binários usam 2.
- **Símbolos**: Alguns símbolos, como - e +, podem ser unários (sinal) ou binários (operação) dependendo do contexto.
- **Precedência**: Em Python, operadores unários (como - de sinal) geralmente têm precedência maior que operadores binários (como + ou - de soma/subtração).
