---
titulo: Precisão dos números de ponto flutuante
---

# Precisão dos números de ponto flutuante

A precisão de números de ponto flutuante (float) em Python **é baseada no padrão IEEE 754 de precisão dupla (float64)**, oferecendo alta precisão para a maioria dos usos, mas com limitações inerentes à representação binária, que causa pequenas imprecisões em alguns decimais (como 0.1 + 0.1 + 0.1 != 0.3). Para cálculos financeiros ou científicos que exigem precisão exata, o módulo decimal do Python é a solução, pois permite controle total sobre a precisão e arredondamento, evitando erros de representação.

## Problemas de Precisão com float

- **Representação Binária**: Números decimais como 0.1 não podem ser representados exatamente em binário, resultando em aproximações.
- 0.1 + 0.1 + 0.1 - 0.3 em float não resulta em 0, mas em um valor muito próximo, como 5.55e-17.
- **Acúmulo de Erros**: Em cálculos iterativos (ex: somar 0.1 dez vezes), os pequenos erros podem se acumular, afastando o resultado do valor esperado.

## Soluções para Alta Precisão

### Módulo decimal

- Importe from decimal import * para usar aritmética decimal exata.
- Use Decimal('0.1') em vez de 0.1 para garantir a precisão.
- Controle a precisão com getcontext().prec = N.

### Módulo math

Oferece funções para trabalhar com precisão, embora o decimal seja melhor para aritmética exata.

### Formatando Saída

Use formatação de string para apresentar números com casas decimais controladas (ex: f"{numero:.2f}") quando a precisão interna não for o foco, mas sim a exibição.
