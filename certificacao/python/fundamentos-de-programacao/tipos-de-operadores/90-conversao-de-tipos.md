---
titulo: Conversão de tipos
---

# Conversão de tipos

Em Python, conversão de tipos (ou type casting) é mudar um dado de um tipo para outro usando funções como int(), float(), str(), list() para conversão **explícita**, ou automaticamente pelo interpretador em operações (conversão **implícita**) para evitar perda de dados, como combinar int com float resultando em float. É essencial para manipular entradas do usuário e realizar cálculos, mas requer cuidado para evitar erros (ValueError) ao converter texto para números, como ao tentar converter "3.14" para inteiro.

## Conversão Explícita (Type Casting)

Você usa funções específicas para forçar a conversão.

- **int(valor)**: Converte para inteiro. int("123") vira 123.
- **float(valor)**: Converte para ponto flutuante. float(3) vira 3.0.
- **str(valor)**: Converte para string/texto. str(123) vira "123".
- **list(valor)**: Converte para lista. list("abc") vira ['a', 'b', 'c'].
- **tuple(valor)**: Converte para tupla.
- **set(valor)**: Converte para conjunto.

~~~python
# Exemplos de conversão explícita
texto_numero = "42"
numero_inteiro = int(texto_numero)
print(numero_inteiro + 10) # Saída: 52

numero_float = 3.14159
texto_float = str(numero_float)
print(f"O número é {texto_float}") # Saída: O número é 3.14159
~~~

## Conversão Implícita

Python faz isso sozinho em expressões para preservar o dado.

- Um int com um float resulta em float (ex: 5 + 2.5 vira 7.5).

## Cuidado com Erros

Ao converter texto para número, o texto deve ser um valor numérico válido, ou ocorrerá um ValueError (ex: int("hello") falha).

~~~python
# Exemplo de erro
try:
    valor_invalido = int("25.5")
except ValueError as e:
    print(f"Erro: {e}") # Saída: Erro: invalid literal for int() with base 10: '25.5'
~~~
