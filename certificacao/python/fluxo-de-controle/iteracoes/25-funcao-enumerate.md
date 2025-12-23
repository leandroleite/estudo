---
titulo: Função enumerate
---

# Função enumerate

A função enumerate() em Python adiciona um contador a um iterável (como lista, tupla, string) e retorna um objeto enumerado, que gera tuplas de (índice, valor) a cada iteração, sendo útil para acessar tanto o índice quanto o item em um loop for sem gerenciar o contador manualmente, começando por padrão em 0, mas podendo ser alterado com o argumento start.  

## Como Funciona

enumerate(iteravel, start=0)

- **iteravel**: Qualquer objeto que possa ser percorrido (lista, tupla, string, etc.).
- **start**: (Opcional) O número inicial do contador (padrão é 0).

~~~Python

frutas = ['maçã', 'banana', 'cereja']

# Usando enumerate para obter índice e valor
for indice, fruta in enumerate(frutas):
    print(f"Índice: {indice}, Fruta: {fruta}")

# Exemplo com 'start' personalizado
for indice, fruta in enumerate(frutas, start=1):
    print(f"Item {indice}: {fruta}")
~~~

## Vantagens

- **Código mais limpo e "Pythônico"**: Evita a necessidade de criar e incrementar uma variável de contador manualmente.
- **Acesso fácil ao índice**: Simplifica loops que precisam saber a posição de cada item.
- **Flexibilidade**: O argumento start permite iniciar a contagem de qualquer número.
