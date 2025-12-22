---
titulo: Palavras-chaves
---

# Palavras-chaves

Palavras-chave em Python são **identificadores reservados** com significados especiais, que não podem ser usadas como nomes de variáveis ou funções, mas são cruciais para a sintaxe e lógica do código.

## Exemplos de Palavras-Chave e Uso

- **Controle de Fluxo**: if, elif, else, for, while, break, continue, return, match, case (para estruturas condicionais e loops).
- **Definição**: def (funções), class (classes).
- **Valores Especiais**: None (nulo), True (verdadeiro), False (falso).
- **Operadores Lógicos/Identidade**: and, or, not, is, in.
- **Tratamento de Erros**: try, except, finally, raise, assert, del, pass.
- **Importação e Escopo**: import, from, global, nonlocal, as, with, yield.
- **Assíncrono (Moderno)**: async, await (novos em Python 3).

## Como funcionam

- **Reservadas**: Têm um propósito fixo na linguagem.
- **Não Usáveis como Nomes**: Você não pode criar uma variável ou função chamada if ou def, por exemplo.
- **Dicas de IDE**: Editores de código (IDEs) geralmente as destacam e avisam quando você tenta usá-las indevidamente.

## Como ver todas

Você pode usar o módulo keyword do Python para listar todas as palavras-chave ativas no seu interpretador:
python

~~~python
import keyword
print(keyword.kwlist)
~~~

