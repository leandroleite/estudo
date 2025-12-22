---
titulo: Comentários
---

# Comentários

Em Python, comentários são textos ignorados pelo interpretador, usados para explicar o código, melhorar a legibilidade e desativar temporariamente trechos de código, usando # para linhas únicas ou aspas triplas (""" ou ''') para blocos de múltiplas linhas (docstrings).

Eles são essenciais para documentação e colaboração, ajudando outros desenvolvedores e seu "eu" futuro a entender a lógica do código.

## Comentários de Linha Única

Comenta tudo o que vem depois dele na mesma linha, seja no início ou após o código.

- **Símbolo**: # (cerquilha).

~~~python
    # Esta é uma linha inteira de comentário
    nome = "Maria" # Comentário após o código
~~~

## Comentários de Múltiplas Linhas (Docstrings)

Define blocos de texto que abrangem várias linhas, frequentemente usadas como docstrings (documentação de funções, classes e módulos).

- **Símbolo**: """ (três aspas duplas) ou ''' (três aspas simples).

~~~python
    """
    Este é um comentário de bloco.
    Ele pode ter quantas linhas forem necessárias
    e serve para explicações detalhadas.
    """
    def saudacao(nome):
        """Esta docstring explica a função saudacao."""
        print(f"Olá, {nome}!")
~~~
