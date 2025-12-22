---
titulo: Notação científica
---

# Notação científica

Em Python, a notação científica usa a letra _e_ (ou _E_) para representar potências de 10, como _1.23e4_ (1.23 x 10^4), facilitando a escrita de números grandes ou pequenos, e você pode formatar a saída com f-strings (ex: f'{num:.2f}') para controlar casas decimais ou até suprimir a notação científica, como "{:.3f}".format ou f'{num:.9f}' para exibir o número completo.

## Como usar a notação científica em Python

**Entrada de números**: Use _e_ ou _E_.

- _1.23e4_ é o mesmo que 12300.0.
- _6.022e23_ (Número de Avogadro).
- +1e-5_ (0.00001). 

**Saída (Impressão)**:

- **Padrão**: Python usa notação científica para números muito grandes ou pequenos automaticamente.
- f-strings (mais comum): f'{num:g}' ou f'{num:f}'.
- **Método format()**: "{:.3f}".format(12345.6789) para formatar.

## Exemplos práticos

~~~python
numero_grande = 1234567890.0
numero_pequeno = 0.000000123

# Saída padrão (Python usa notação científica)
print(numero_grande) # Saída: 1.23456789e+09
print(numero_pequeno) # Saída: 1.23e-07

# Formatação para remover a notação científica (ponto fixo)
print(f'{numero_grande:.2f}') # Saída: 1234567890.00
print(f'{numero_pequeno:.9f}') # Saída: 0.000000123
~~~

## Para números complexos

Use j para a parte imaginária (ex: 3 + 4j).

## Para precisão e controle avançado

Use o módulo decimal para aritmética de ponto fixo precisa, se necessário para evitar erros de arredondamento em cálculos financeiros ou científicos.
