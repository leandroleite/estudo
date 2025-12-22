---
titulo: Sistemas numéricos binários, octais, decimais e hexadecimais
---

# Sistemas numéricos binários, octais, decimais e hexadecimais

Python lida nativamente com sistemas numéricos como binário (base 2), octal (base 8), decimal (base 10) e hexadecimal (base 16), usando prefixos como _0b_, _0o_, e _0x_ para representá-los diretamente e funções como _bin()_, _oct()_, _hex()_ para converter inteiros decimais para essas outras bases, sendo essenciais para programação, hardware e manipulação de dados em TI.

## Sistemas Numéricos

- **Decimal (Base 10)**: Usa 0-9. O mais comum no dia a dia.
- **Binário (Base 2)**: Usa 0 e 1. Linguagem fundamental dos computadores.
- **Octal (Base 8)**: Usa 0-7. Útil em permissões de arquivos (Unix/Linux).
- **Hexadecimal (Base 16)**: Usa 0-9 e A-F (A=10, F=15). Usado para cores (HTML/CSS), endereços de memória e depuração.

## Representação e Conversão em Python

**Definindo Literais**:

- Decimal: 10
- Binário: 0b1010 (equivalente a 10 decimal)
- Octal: 0o12 (equivalente a 10 decimal)
- Hexadecimal: 0xA (equivalente a 10 decimal).

**Convertendo para Outras Bases (de Decimal)**:

- bin(10) -> '0b1010'
- oct(10) -> '0o12'
- hex(10) -> '0xa'.

**Convertendo para Decimal (de Outras Bases)**:

- int('1010', 2) -> 10
- int('12', 8) -> 10
- int('A', 16) -> 10

## Exemplo Prático

~~~python
# Definindo números em diferentes bases
num_decimal = 255
num_binario = 0b11111111 # 255
num_octal = 0o377        # 255
num_hex = 0xFF           # 255

print(f"Decimal: {num_decimal}")
print(f"Binário: {num_binario}")
print(f"Octal: {num_octal}")
print(f"Hexadecimal: {num_hex}")

# Convertendo de decimal para outras bases
print(f"\nConversão de 255 para Binário: {bin(num_decimal)}") # '0b11111111'
print(f"Conversão de 255 para Octal: {oct(num_decimal)}")   # '0o377'
print(f"Conversão de 255 para Hexadecimal: {hex(num_decimal)}") # '0xff'

# Convertendo de outras bases para decimal (usando int())
print(f"De '11111111' (binário) para decimal: {int('11111111', 2)}") # 255
print(f"De 'FF' (hexadecimal) para decimal: {int('FF', 16)}")         # 255
~~~
