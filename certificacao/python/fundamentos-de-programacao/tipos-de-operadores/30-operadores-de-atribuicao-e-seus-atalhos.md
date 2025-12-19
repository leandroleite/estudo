---
titulo: Operadores de atribuição e seus atalhos
---

# Operadores de atribuição e seus atalhos

Em Python, operadores de atribuição (como =, +=, -=) servem para **atribuir valores a variáveis** e seus atalhos (ou atribuições aumentadas) **combinam a operação aritmética com a atribuição**, como _x += 2_ que é o mesmo que _x = x + 2_, economizando código e tornando-o mais legível, especialmente para operações como soma, subtração, multiplicação e divisão.

## Operador de Atribuição Simples

- **=**: Atribui um valor diretamente a uma variável.

~~~python
nome = "Alice". 
~~~

## Operadores de Atribuição Abreviados (Atalhos)

Esses operadores realizam uma operação matemática e atribuem o resultado de volta à variável, na mesma linha.

- **Adição e atribuição**: x += 5
- **Subtração e atribuição**: x -= 3
- **Multiplicação e atribuição**: x *= 2
- **Divisão e atribuição (resultado sempre float)**: x /= 4
- **Divisão inteira e atribuição**: x //= 4
- **Módulo (resto da divisão) e atribuição**: x %= 3
- **Exponenciação e atribuição**: x **= 2

## Exemplo Prático

~~~python
# Usando o operador de soma
contador = 5
contador += 10  # Equivalente a contador = contador + 10
print(contador) # Saída: 15

# Usando o operador de multiplicação
valor = 2
valor *= 4  # Equivalente a valor = valor * 4
print(valor) # Saída: 8
~~~
