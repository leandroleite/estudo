---
titulo: Léxico, sintaxe e semântica
---

# Léxico, sintaxe e semântica

Em programação, Léxico, Sintaxe e Semântica definem as regras para escrever código:

- O Léxico são os "blocos" (tokens, palavras-chave, identificadores).
- A Sintaxe é a gramática que organiza esses blocos (a estrutura da frase).
- A Semântica é o significado, o que o código realmente faz, garantindo que a instrução seja logicamente coerente e funcional.

O compilador/interpretador verifica o léxico (tokens), depois a sintaxe (estrutura) e, por fim, a semântica (significado e lógica) para garantir que o programa funcione como esperado, prevenindo erros.

## Léxico (Análise Léxica)

- **O que é**: O dicionário da linguagem, ou seja, o conjunto de palavras-chave, identificadores, operadores e símbolos que a linguagem reconhece (os "tokens").
- **Exemplo**: Em int x = 5;, int, x, =, 5, ; são os tokens léxicos.
- **Erro Léxico**: Um caractere inválido ou uma palavra desconhecida, como integer x = 5;.

## Sintaxe (Análise Sintática)

- **O que é**: As regras gramaticais que ditam como os tokens (do léxico) devem ser combinados e organizados para formar frases válidas na linguagem.
- **Exemplo**: Em muitas linguagens, é obrigatório declarar o tipo de variável (int), usar ponto e vírgula no final, etc..
- **Erro Sintático**: Uma estrutura mal formada, como int x 5; (faltou o ; ou o = correto).

## Semântica (Análise Semântica)

- **O que é**: O significado das instruções, a lógica por trás do código. Garante que a construção sintaticamente correta faça sentido e execute a ação desejada.
- **Exemplo**: Tentar somar um número a uma palavra (5 + "hello"), ou usar uma variável antes de declará-la.
- **Erro Semântico**: O código é estruturalmente correto, mas logicamente falho, como int total = 10 + 5; (correto), versus int total = 10 / 0; (semântico inválido, divisão por zero).
