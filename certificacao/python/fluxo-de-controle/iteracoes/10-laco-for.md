---
titulo: Laço for
---

# Laço for

O laço for em Python é uma estrutura de repetição que percorre itens de uma sequência (como listas, tuplas, strings, dicionários) ou de um intervalo definido pela função range(), executando um bloco de código para cada item da sequência, sendo ideal para processar coleções de dados ou repetir tarefas um número conhecido de vezes. Sua sintaxe é for item in sequencia:, onde item é uma variável que recebe cada valor da sequencia a cada iteração, e o bloco de código é indentado abaixo.

## Iterável

Funciona com qualquer objeto que pode ser "percorrido" (listas, tuplas, strings, dicionários).

~~~python
for item in sequencia:
    # faça algo com o item
~~~

### Iterando através de uma Lista (List)

~~~python
frutas = ["maçã", "banana", "cereja"]

for fruta in frutas:
    print(f"Eu gosto de {fruta}")
~~~

### Iterando através de uma String

~~~python
saudacao = "Olá Mundo"

for caractere in saudacao:
    print(f"Caractere: {caractere}")
~~~

### Iterando através de uma Tupla

Tuplas são semelhantes às listas, mas imutáveis.

~~~python
coordenadas = (10, 20, 30)

for coord in coordenadas:
    print(f"Coordenada: {coord}")
~~~

### Iterando através de um Dicionário (Dict)

Com dicionários, você pode iterar através das chaves, valores ou ambos os pares de chave-valor.

~~~python
pessoa = {"nome": "João", "idade": 30, "cidade": "São Paulo"}

# Iterando através das chaves (padrão)
for chave in pessoa:
    print(f"Chave: {chave}, Valor: {pessoa[chave]}")

# Iterando através dos valores
for valor in pessoa.values():
    print(f"Valor: {valor}")

# Iterando através dos pares chave-valor usando .items()
for chave, valor in pessoa.items():
    print(f"Chave: {chave}, Valor: {valor}")
~~~

## Usando range() para iterar por Índice

Se você precisar do índice do item durante a iteração (comum em outras linguagens, mas menos idiomático em Python), você pode usar range() em combinação com len():

~~~python
lista = ["a", "b", "c"]

for indice in range(len(lista)):
    print(f"Índice: {indice}, Valor: {lista[indice]}")
~~~

## Usando enumerate() (método preferido para índices)

A função enumerate() é a maneira mais "pythônica" de obter o índice e o valor simultaneamente:

~~~python
lista = ["a", "b", "c"]

for indice, valor in enumerate(lista):
    print(f"Índice: {indice}, Valor: {valor}")
~~~

## Compreensões de lista

Uma maneira concisa e eficiente de criar novas listas com base em sequências existentes:

~~~python
numeros = [1, 2, 3, 4, 5]

quadrados = [x * x for x in numeros]
# quadrados agora é [1, 4, 9, 16, 25]

pares = [x for x in numeros if x % 2 == 0]
# pares agora é [2, 4]
~~~
