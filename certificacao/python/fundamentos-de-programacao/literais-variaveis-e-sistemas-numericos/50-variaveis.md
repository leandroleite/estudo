---
titulo: Variáveis
---

# Variáveis

Variáveis em Python são nomes que referenciam espaços na memória para guardar dados (números, textos, listas, etc.), criadas com o sinal de igual (_=_), sem precisar declarar o tipo, pois Python infere dinamicamente (ex: idade = 30, nome = "Ana"). Elas usam convenções como minúsculas e snake_case para nomes, não podem usar palavras reservadas e são essenciais para manipular informações em programas. 

## Como funcionam

- **Criação e Atribuição**: Você cria uma variável ao dar um nome e atribuir um valor a ela. nome_variavel = valor.
- **Tipos Dinâmicos**: Python descobre o tipo (inteiro int, decimal float, texto str, booleano bool, etc.) automaticamente.
- **Uso**: Use o nome da variável para acessar ou modificar o valor. A função print() mostra o valor.

~~~Python
# Exemplo de criação e uso
idade = 25         # int (inteiro)
nome = "Carlos"    # str (texto)
altura = 1.75      # float (decimal)
is_ativo = True    # bool (booleano)

print(idade)       # Saída: 25
print(nome)        # Saída: Carlos
print(type(nome))  # Saída: <class 'str'>
~~~

## Regras para Nomes (Identificadores)

- Podem conter letras (minúsculas/maiúsculas), números e sublinhado (_).
- Não podem começar com um número.
- Devem ser descritivos (ex: nome_completo em vez de nc).
- Não podem ser palavras reservadas da linguagem (como if, for, while, True).
- Convenção: snake_case (palavras separadas por _) para variáveis e funções, e MAIUSCULAS para constantes.

## Exemplos de Tipos Comuns

- _int_: Números inteiros (ex: 10, -5).
- _float_: Números decimais (ex: 3.14, 0.5).
- _str_: Sequências de caracteres (ex: "Olá Mundo", 'Python').
- _bool_: Valores booleanos (_True_ ou _False_).
- _list_, _tuple_, _dict_: Estruturas de dados mais complexas.
