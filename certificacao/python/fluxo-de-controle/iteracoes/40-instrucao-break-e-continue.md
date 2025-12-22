---
titulo: Instrução break e continue
---

# Instrução break e continue

Em Python, break e continue controlam laços (for, while), sendo que break **interrompe** o laço completamente, saindo dele. continue, por sua vez, **pula** a iteração atual e passa para a próxima, sem parar o laço, sendo úteis para flexibilizar a execução e ignorar condições específicas.

## break: Interrompe o laço

- **O que faz**: Finaliza a execução do laço imediatamente, e o programa continua com o código após o laço.
- **Quando usar**: Quando uma condição específica é atendida e não há necessidade de continuar as iterações, economizando recursos.

~~~python
# Exemplo com break
print("Exemplo com break:")
for i in range(5):
    if i == 3:
        print(f"Encontrou {i}, quebrando o laço!")
        break # O laço para aqui
    print(f"Iteração {i}")
print("laço finalizado.")
~~~

## continue: Pula a iteração atual

- **O que faz**: Pula o restante do código dentro do bloco do laço para a iteração atual e começa a próxima iteração.
- **Quando usar**: Para ignorar o processamento de certos itens, mas ainda iterar sobre todos os outros.

~~~python
# Exemplo com continue
print("\nExemplo com continue:")
for i in range(5):
    if i % 2 == 0: # Pula os números pares
        print(f"Número {i} é par, pulando...")
        continue # Pula para a próxima iteração
    print(f"Processando número ímpar: {i}")
print("laço concluído.")
~~~
