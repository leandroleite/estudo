---
titulo: Função range
---

# Função range

Em Python, range() **é uma função que gera sequências de números inteiros**, muito usada em loops for, com a sintaxe range(início, fim, passo), onde início (padrão 0) e passo (padrão 1) são opcionais, e o número fim **não é incluído** na sequência; para criar uma lista concreta a partir dela, usa-se list(range(...)).

## Uso range

- **range(fim)**: Gera números de 0 até fim - 1.
- **range(início, fim)**: Gera números de início até fim - 1.
- **range(início, fim, passo)**: Gera números de início até fim - 1, com incrementos de passo.

~~~python
# Exemplo 1: Loop simples (0 a 4)
for i in range(5):
    print(i)

# Exemplo 2: Lista de 1 a 10 (fim é exclusivo)
lista_numeros = list(range(1, 11))
print(lista_numeros) # Saída: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Exemplo 3: Contagem regressiva ou com passo diferente
for j in range(10, 0, -2):
    print(j) # Saída: 10, 8, 6, 4, 2
~~~

## Pontos importantes

- **Eficiência**: range() retorna um objeto iterável, não uma lista completa, o que economiza memória, especialmente para sequências grandes.
- **Uso com list()**: Para ver os números gerados como uma lista, use list(range(início, fim)).
