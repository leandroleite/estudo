---
titulo: Instruções
---

# Instruções

Instruções em Python são comandos que você escreve em um editor de código (como VS Code, PyCharm) para que o interpretador Python execute tarefas, como exibir textos (usando print()), receber dados do usuário (input()), fazer comparações (if/else), repetir ações (for, while), e manipular dados com funções e métodos (ex: .upper() para texto ou métodos de lista como insert()), sempre prestando atenção à sintaxe e ao recuo (indentação) correto com 4 espaços.

## Instruções Fundamentais

- **print()**: Exibe uma mensagem ou valor na tela.

~~~python
print("Olá, Mundo!")
~~~

- **input()**: Captura dados digitados pelo usuário (retorna texto).

~~~python
nome = input("Digite seu nome: ")
~~~

- **int()/float()**: Converte texto para números inteiros ou decimais.

~~~python
idade = int(input("Digite sua idade: "))
~~~

- **Variáveis**: Armazenam dados (ex: nome = "Ana"). Python diferencia maiúsculas de minúsculas (minhaVar é diferente de MinhaVar).

- **if/elif/else**: Executa blocos de código baseados em condições.

~~~python
if idade >= 18:
    print("Adulto")
else:
    print("Menor de idade")
~~~

- **for e while (Laços/Loops)**: Repetem blocos de código.

~~~python
for i in range(3): # Repete 3 vezes
    print(i)
~~~

- **Métodos de String**: Operações sobre textos.

~~~python
texto = "python é legal"
print(texto.upper()) # Saída: PYTHON É LEGAL
~~~

- **Métodos de Lista**: Manipulam listas (estruturas de dados).

~~~python
frutas = ["maçã", "banana"]
frutas.append("laranja") # Adiciona laranja
~~~

