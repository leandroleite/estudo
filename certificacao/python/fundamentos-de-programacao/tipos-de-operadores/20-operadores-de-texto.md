---
titulo: Operadores de texto
---

# Operadores de texto

Em Python, operadores de texto (strings) incluem **concatenação (+)**, **repetição (*)**, e operadores de associação como **in** e **not in** para verificar a presença de substrings, além de operadores de **comparação** (==, !=, >, <) para comparar textos, e métodos de string para formatação e manipulação como **f-strings**, que são essenciais para trabalhar com texto de forma eficiente.

## Operadores Básicos

- **+ (Concatenação)**: Une duas strings.

~~~python
'Olá' + ' ' + 'Mundo'  # 'Olá Mundo'
~~~

- *** (Repetição)**: Repete uma string um número de vezes.

~~~python
'Oi' * 3  # 'OiOiOi'
~~~

## Operadores de Comparação (Retornam True/False)

- **== (Igual a)**: Verifica se duas strings são idênticas.
- **!= (Diferente de)**: Verifica se são diferentes.
- **> (Maior que)**: Compara lexicograficamente (ordem alfabética).
- **< (Menor que)**: Compara lexicograficamente.
- **>= / <= (Maior/Menor ou igual a)**: Comparações inclusivas.

## Operadores de Associação

- **in**: Verifica se uma substring está contida em outra string.

~~~python
'sol' in 'nasol'  # True
~~~

- **not in**: Verifica se uma substring não está contida em outra string.

## F-Strings: Literais de string formatadas

F-strings em Python (a partir da versão 3.6) são literais de string formatadas, que começam com f ou F antes das aspas, permitindo incorporar expressões e variáveis diretamente dentro das chaves {} para interpolação de texto, tornando o código mais limpo, legível e eficiente para formatar dados, como números decimais (:.2f), datas e alinhamento de texto.

- **Sintaxe Básica**: Adicione f antes das aspas e coloque variáveis ou expressões entre chaves {}.

~~~python
nome = "Mundo"
print(f"Olá, {nome}!") # Saída: Olá, Mundo!
~~~

- **Casas Decimais**: Use :.Nf para formatar um float com N casas.

~~~python
valor = 123.4567
print(f"Valor formatado: {valor:.2f}") # Saída: Valor formatado: 123.46
~~~

- **Separador de Milhar**: Use , dentro das chaves.

~~~python
numero_grande = 1000000
print(f"Número grande: {numero_grande:,}") # Saída: Número grande: 1,000,000
~~~

- **Datas e Horas**: Use formatadores como %Y-%m-%d.

~~~python
from datetime import datetime
agora = datetime.now()
print(f"Data de hoje: {agora:%d/%m/%Y}") # Saída: Data de hoje: 19/12/2025 (exemplo)
~~~

- **Alinhamento**: Use :<, :>, :@ com a largura desejada.

~~~python
print(f"|{nome:<10}|") # Saída: |Mundo     | (alinhado à esquerda)
~~~

## Método .format()

O método .format() em Python serve para inserir variáveis e valores dentro de strings usando {} como marcadores de posição, substituídos na ordem ou por nome/índice, sendo uma forma mais moderna e flexível que o antigo operador %, e permitindo controle de formato (casas decimais, alinhamento) e reutilização de variáveis, ideal para construir textos dinâmicos em português ou qualquer idioma.

- **Marcadores de Posição {}**: Coloque chaves onde os valores devem aparecer.
- **Argumentos**: Passe os valores para o método .format() após a string. 

~~~python
nome = "Maria"
idade = 30
print("Olá, {}! Você tem {} anos.".format(nome, idade))
# Saída: Olá, Maria! Você tem 30 anos.
~~~

- **Ordem Posicional**: Os argumentos são substituídos na ordem em que são passados.

~~~python
print("O {0} é {1}.".format("gato", "preto"))
# Saída: O gato é preto.
~~~

- **Por Nome (Argumentos Nomeados)**: Para maior clareza e ordem flexível.

~~~python
print("O {animal} é {cor}.".format(cor="verde", animal="sapo"))
# Saída: O sapo é verde.
~~~

- **Reutilização**: Pode-se usar o mesmo argumento múltiplas vezes.

~~~python
print("A {p} pode ser usada de novo: {p}!".format(p="variável"))
# Saída: A variável pode ser usada de novo: variável!
~~~

- **Especificadores de Formato**: Controles finos para números, alinhamento, etc., usando : dentro das chaves.

~~~python
print("Número: {:d}, Float (2 casas): {:.2f}".format(10, 3.14159))
# Saída: Número: 10, Float (2 casas): 3.14
print("Alinhado à direita: {:>10}".format("oi"))
# Saída: Alinhado à direita:         oi
~~~

## Exemplos Práticos

~~~python
nome = "Python"
saudacao = f"Bem-vindo ao {nome}!" # F-string
print(saudacao) # Bem-vindo ao Python!

texto1 = "programação"
texto2 = "amor"
print(f"'{texto2}' está em '{texto1}'? {'amor' in texto1}") # 'amor' está em 'programação'? True

print("abc" < "abd") # True (ordem alfabética)
~~~
