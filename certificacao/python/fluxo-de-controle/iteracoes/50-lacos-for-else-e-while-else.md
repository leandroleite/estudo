---
titulo: Laços for-else e while-else
---

# Laços for-else e while-else

Em Python, os blocos else associados a laços (for e while) são executados **somente se o laço terminar naturalmente**, ou seja, sem ser interrompido por um comando break.

## for-else

O bloco else do for é executado se o laço percorrer completamente todos os itens do iterável sem encontrar um break.

- É comumente usado para operações de busca, onde você quer fazer algo se um item **não** for encontrado após verificar todos os elementos.

~~~python
itens = [1, 3, 5, 7]
item_procurado = 2

for item in itens:
    if item == item_procurado:
        print(f"Item {item_procurado} encontrado!")
        break
else:
    # Este bloco só executa se o 'break' não for acionado
    print(f"Item {item_procurado} não encontrado na lista.")

# a saída será "Item 2 não encontrado na lista." porque o laço termina sem break.
~~~

### while-else

O bloco else do while é executado quando a condição do laço se torna False. Assim como no for, ele não é executado se o laço for interrompido por um break.

~~~python
contador = 0

while contador < 3:
    print(f"Contador é {contador}")
    contador += 1
else:
    # Este bloco só executa quando a condição 'contador < 3' se torna False
    print("O laço while terminou normalmente.")

# A saída mostrará os números de 0 a 2 e, em seguida, "O laço while terminou normalmente.".
~~~
