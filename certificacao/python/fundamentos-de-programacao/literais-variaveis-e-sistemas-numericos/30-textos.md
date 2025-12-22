---
titulo: Textos
---

# Textos

Em Python, **textos são representados por strings**, delimitadas por aspas (simples ou duplas), e podem ser manipulados com funções como _len()_ para tamanho ou fatiamento por índice, além de métodos como _find()_.

# Strings

- **Definição:** Textos entre aspas simples ' ' ou duplas " ".

~~~python
nome = "Alice"
mensagem = 'Olá, mundo!'
~~~

- **Acesso e Tamanho**: Strings são como listas de caracteres, indexadas a partir de 0.

~~~python
print(len(nome)) # Saída: 5
print(nome[0])   # Saída: A
~~~

- **Fatiamento (Slicing)**: Pegar pedaços do texto.

~~~python
print(nome[1:4]) # Saída: lic
~~~

## Formatação de Strings

Use f-strings (f"...") para inserir variáveis facilmente ou o método _str.format()_ para controle detalhado.

~~~python
idade = 30
print(f"Olá, {nome}, você tem {idade} anos.")
~~~
