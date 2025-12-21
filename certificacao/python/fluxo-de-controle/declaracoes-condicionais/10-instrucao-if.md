---
titulo: Instrução if
---

# Instrução if

Declarações condicionais em Python (if, elif, else) permitem que seu código tome decisões, executando blocos diferentes de instruções com base em condições Verdadeiro/Falso, sendo o if para a condição inicial, elif para condições alternativas e else para o caso padrão, com a **indentação (espaços)** definindo o escopo de cada bloco. Existe também a **expressão ternária**, uma forma compacta de if-else em uma linha, e a instrução pass para blocos vazios.

## Principais Estruturas

- **if (Se)**: Executa um bloco de código se a condição for verdadeira.

~~~python
idade = 20
if idade >= 18:
    print("Você é maior de idade.")
~~~

- **if-else (Se-Senão)**: Executa um bloco se a condição for verdadeira e outro se for falsa.

~~~python
idade = 15
if idade >= 18:
    print("Maior de idade.")
else:
    print("Menor de idade.")
~~~

- **if-elif-else (Se-Senão Se-Senão)**: Verifica múltiplas condições sequencialmente, ideal para quando há várias alternativas.

~~~python
nota = 75
if nota >= 90:
    print("Aprovado com A")
elif nota >= 70:
    print("Aprovado com B")
else:
    print("Reprovado")
~~~

## Características Importantes

- **Indentação**: Em Python, a indentação (geralmente 4 espaços) é crucial para definir quais linhas pertencem a qual bloco condicional. Sem ela, o código não funciona.
- **elif**: Abreviação de "else if" (senão se), permite testar múltiplas condições sem excesso de aninhamento.
- **else**: Bloco opcional que captura todas as situações em que as condições anteriores do if e elif foram falsas.

## Sintaxe Concisa

- **Expressão Ternária**: Uma forma de escrever if-else em uma linha.

~~~python
status = "Adulto" if idade >= 18 else "Menor"
~~~

- **pass**: Usado como um placeholder em um bloco condicional que você não quer que execute nenhuma ação ainda, para evitar erros de sintaxe.

~~~python
if True:
    pass # Faz nada, apenas um placeholder
~~~
