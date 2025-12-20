---
titulo: Função input()
---

# Função input()

Em Python, a função input() é usada para receber dados do usuário no terminal, exibindo uma mensagem (prompt) e aguardando que o usuário digite algo e pressione Enter; por padrão, ela sempre retorna o que foi digitado como texto (string), sendo necessário converter para int() (inteiro) ou float() (decimal) para realizar cálculos, como idade = int(input("Digite sua idade: ")), para uma interação dinâmica.

## Uso Básico

- input() lê a linha inteira como uma string.

~~~python
nome = input("Digite seu nome: ") # O texto entre aspas é o prompt
print(f"Olá, {nome}!") # A saída será "Olá, [nome digitado]!"
~~~

## Recebendo Números (Conversão)

- int() e float() para converter para números

~~~python
# Recebe como texto, depois converte para inteiro
idade_str = input("Digite sua idade: ")
idade = int(idade_str)
print(f"Daqui a 10 anos, você terá {idade + 10} anos.")

# Ou converte diretamente na mesma linha
altura = float(input("Digite sua altura (ex: 1.75): "))
print(f"Sua altura é {altura}m.")
~~~

## Recebendo Múltiplos Valores na Mesma Linha (Split)

- input().split() **é usado para ler uma linha de texto do usuário e dividi-la em uma lista de strings**, usando espaços em branco como separador padrão, o que é perfeito para capturar múltiplas entradas em uma linha, como 10 20 30 se tornando ['10', '20', '30'].

- map(int, ...) aplica a função int() a cada item da lista gerada pelo split(), convertendo as strings para números inteiros.
- list(...) transforma o resultado do map em uma lista.

~~~python
entrada_numeros = input("Digite números separados por espaço: ")
numeros_str = entrada_numeros.split() # ['10', '20', '30']
numeros_int = list(map(int, numeros_str)) # [10, 20, 30]
~~~

## Pontos Chave

- input(): Sempre retorna uma string (texto).
- int() / float(): Use para converter a entrada para um número inteiro ou decimal, respectivamente, quando necessário para operações matemáticas.
- split(): Combina com input() para pegar múltiplos valores em uma linha, separando-os em uma lista.
