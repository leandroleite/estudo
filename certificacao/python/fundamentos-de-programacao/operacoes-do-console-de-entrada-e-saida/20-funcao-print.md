---
titulo: Função print()
---

# Função print()

Em Python, você usa a função print() (tudo minúsculo) para exibir informações no console, escrevendo o que quer mostrar entre parênteses, como print("Olá, Mundo!") para textos ou print(variavel) para variáveis, sendo uma função nativa que não precisa de importação, e permite formatação com argumentos como sep (separador) e end (final de linha), ou usando f-strings para incluir variáveis diretamente.

## Uso básico

- print(texto)

~~~python
# Exemplo básico
print("Olá, Mundo!")

# Imprimindo variáveis
nome = "Maria"
idade = 30
print("Nome:", nome, "Idade:", idade)

# Usando f-strings (Python 3.6+) para formatação
print(f"O nome dela é {nome} e ela tem {idade} anos.")

# Controlando o separador (sep) e o final da linha (end)
print("Maçã", "Banana", "Laranja", sep="-") # Saída: Maçã-Banana-Laranja
print("Isso", end=" ")
print("fica na mesma linha.") # Saída: Isso fica na mesma linha.
~~~

## Parâmetros sep= e end=

Em Python, print(..., sep='separador', end='final') personaliza a saída: sep (separador) define o que vai entre os itens (padrão é espaço) e end define o que vai no final da linha (padrão é \n, uma nova linha), permitindo que múltiplos print continuem na mesma linha ou adicionem caracteres específicos.

~~~python
print("banana", "maçã", "laranja", sep=' | ')
# Saída: banana | maçã | laranja

print("Olá", end=' ')
print("Mundo!")
# Saída: Olá Mundo!

print("a", "b", "c", sep='-', end='...\n')
print("d", "e", sep='-')
# Saída: a-b-c...
# Saída: d-e
~~~

## Parâmetro flush=True

print(..., flush=True) em Python **força a exibição imediata da saída**, esvaziando o buffer de impressão, o que é crucial para exibir barras de progresso, logs em tempo real ou textos que precisam aparecer antes de um time.sleep() ou fim de um loop, quebrando o comportamento padrão de bufferização para otimizar a escrita.

- **Buffer**: A saída do print() é, por padrão, armazenada temporariamente (buffer) antes de ser exibida, para agrupar dados e melhorar a performance.
