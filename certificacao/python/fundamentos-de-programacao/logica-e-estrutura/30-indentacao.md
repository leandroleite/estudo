---
titulo: Indentação
---

# Indentação

A indentação em Python é o recuo (espaços ou tabs) no início das linhas de código, essencial para definir a estrutura e os blocos lógicos (como loops for, condicionais if, funções def), substituindo chaves {} de outras linguagens; é uma regra sintática obrigatória, não apenas estilo, e deve ser consistente (padrão de 4 espaços) para evitar IndentationError.

## Por que é importante?

- **Define blocos**: Indica quais comandos pertencem a qual estrutura (ex: o que está dentro de um if ou for).
- **Legibilidade**: Torna o código mais fácil de ler e entender a organização.
- **Obrigatória**: Diferente de outras linguagens, o Python a usa para sua lógica; código mal indentado causa erro.

## Regras e Convenções

- **Consistência**: Use sempre o mesmo nível de recuo (espaços ou tabs) dentro do mesmo bloco.
- **Padrão**: O recomendado é usar 4 espaços por nível de indentação.
- **Início**: A primeira linha de código não pode ter recuo.
- **Delimitador**: Usa-se os dois-pontos (:) para indicar o início de um bloco indentado.

~~~python
# Código bem indentado
if 5 > 3:
    print("Cinco é maior que três")  # Bloco do if
    print("Este também está dentro do if")

# Código com erro de indentação (IndentationError)
# if 5 > 3:
# print("Isso vai dar erro") # Linha sem indentação no bloco
~~~
