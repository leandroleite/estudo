---
titulo: Aninhamento de laços
---

# Aninhamento de laços

Aninhamento de laços em Python significa colocar um loop (como for ou while) dentro de outro, permitindo iterações em múltiplas dimensões, ideal para trabalhar com matrizes ou criar padrões complexos, onde o loop interno executa todas as suas iterações para cada iteração do loop externo, mas atenção para não tornar o código ilegível ou lento com muitos níveis de aninhamento, o que é comum em.

## Como funciona

- **Laço Externo**: O loop principal, que controla as iterações maiores.
- **Laço Interno**: O loop que fica dentro do laço externo; ele reinicia completamente a cada nova iteração do externo.
- **Combinação**: Você pode aninhar for com for, while com while, ou for com while e vice-versa.

~~~python
for i in range(3): # Loop externo (linhas)
    for j in range(3): # Loop interno (colunas)
        print(f"({i}, {j})", end=" ")
    print() # Pula para a próxima linha

# Saída:
# (0, 0) (0, 1) (0, 2) 
# (1, 0) (1, 1) (1, 2) 
# (2, 0) (2, 1) (2, 2) 
~~~

## Para que servem

- **Manipulação de Dados Multidimensionais**: Como listas de listas (matrizes).
- **Geração de Padrões**: Criar triângulos de asteriscos, tabuadas, etc..
- **Tarefas Repetitivas**: Executar uma tarefa em diferentes conjuntos de dados.

## Dicas e Cuidados

- **Desempenho**: Muitos níveis de aninhamento (mais de 3) podem ser lentos e difíceis de entender.
- **Legibilidade**: Mantenha o código limpo e com nomes de variáveis claros.
- **Controle**: Use break para sair do loop mais interno e continue para pular para a próxima iteração do loop interno.
