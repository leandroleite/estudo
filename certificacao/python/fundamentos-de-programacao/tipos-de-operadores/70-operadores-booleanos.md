---
titulo: Operadores booleanos
---

# Operadores booleanos

Operadores booleanos em Python são and, or, e not, usados para combinar ou inverter condições lógicas, retornando True ou False. and retorna True se ambas as condições forem verdadeiras; or retorna True se pelo menos uma for verdadeira; e not inverte o valor booleano (de True para False, ou vice-versa). Eles são essenciais para controlar o fluxo de programas através de if statements e loops.

## Operador and (E)

Retorna True somente se todas as condições forem True.

- Exemplo: (idade > 18) and (tem_carteira == True).

## Operador or (OU)

Retorna True se pelo menos uma das condições for True.

- Exemplo: (pode_dirigir == True) or (tem_autorizacao == True).

## Operador not (NÃO)

Inverte o valor booleano de uma expressão.

- Exemplo: not (idade < 18) retorna True se a idade for 18 ou mais.

## Uso em Código

~~~Python
idade = 25
tem_carteira = True

# Exemplo com 'and'
pode_ir = (idade >= 18) and tem_carteira
print(f"Pode ir: {pode_ir}") # Saída: Pode ir: True

# Exemplo com 'or'
pode_pegar_carona = (idade < 18) or (idade > 60)
print(f"Pode pegar carona: {pode_pegar_carona}") # Saída: Pode pegar carona: False

# Exemplo com 'not'
nao_pode_dirigir = not tem_carteira
print(f"Não pode dirigir: {nao_pode_dirigir}") # Saída: Não pode dirigir: False
~~~
