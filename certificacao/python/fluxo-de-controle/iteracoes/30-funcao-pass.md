---
titulo: Instrução pass
---

# Instrução pass

A instrução pass em Python é um comando nulo que não faz nada, servindo como um **espaço reservado** sintaticamente necessário em blocos de código (como funções, classes ou loops if/else) que ainda não foram implementados, evitando erros e permitindo que o programa continue a execução, podendo ser substituído por código real futuramente.

## Onde usar pass

- **Funções e Classes Vazias**: Para definir a estrutura de uma função ou classe sem erro, antes de adicionar a lógica.

~~~python
def minha_funcao_futura():
    pass # A função está definida, mas não faz nada ainda

class MinhaClasse:
    pass # Classe definida para uso posterior
~~~

- **Instruções Condicionais (if/elif/else)**: Quando você quer que uma condição não faça nada, mas precisa que o bloco exista.

~~~python
x = 10
if x > 5:
    print("x é maior que 5")
else:
    pass # Não faz nada se x não for maior que 5
~~~

- **Loops (for, while)**: Para pular iterações ou como um ponto de parada temporário.

~~~python
for i in range(5):
    if i == 2:
        pass # Pula a iteração quando i é 2, mas o loop continua
    else:
        print(i)
~~~

## Por que usar pass?

- **Evita erros de indentação**: O Python exige código em blocos indentados; pass preenche esse espaço.
- **Organização**: Permite estruturar o código e voltar para preencher as partes depois, sem quebrar o programa.
