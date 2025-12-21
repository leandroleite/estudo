---
titulo: Estrutura match/case
---

# Estrutura match/case

match/case em Python (a partir da versão 3.10) é uma estrutura de controle de fluxo poderosa, similar ao switch/case de outras linguagens, mas com correspondência de padrões estruturais, permitindo comparar um valor com vários padrões (constantes, tipos, sequências, etc.) e executar um bloco de código específico, tornando o código mais limpo e legível para múltiplos if/elif/else, com o case _ funcionando como o default ou else genérico.

## Como funciona

- **match**: Inicia a estrutura, seguido pela expressão (variável ou valor) a ser avaliada.
- **case**: Define os padrões para comparação. Se o padrão corresponder ao valor, o código sob o case é executado.
- **_ (underscore)**: Um padrão curinga, que corresponde a qualquer valor que não foi casado por nenhum case anterior, similar ao default.

### Exemplo básico (semelhante a switch/case)

~~~python
dia = 2 # Suponha que 1=Domingo, 2=Segunda, etc.

match dia:
    case 1:
        print("É domingo!")
    case 2:
        print("É segunda-feira!")
    case 3:
        print("É terça-feira!")
    case _: # Caso padrão (default)
        print("Dia inválido ou não especificado.")
~~~

### Exemplo com múltiplos valores no mesmo case

~~~python
dia = 1

match dia:
    case 1 | 7: # Corresponde se dia for 1 OU 7 (fim de semana)
        print("É fim de semana!")
    case 2 | 3 | 4 | 5 | 6: # Corresponde a dias da semana
        print("É dia útil.")
    case _:
        print("Dia inválido.")
~~~

### Exemplo com correspondência de padrões (mais avançado)

~~~python
ponto = (0, 1) # Uma tupla (x, y)

match ponto:
    case (0, 0):
        print("Origem")
    case (x, 0): # Captura o valor de x
        print(f"No eixo X, em x={x}")
    case (0, y): # Captura o valor de y
        print(f"No eixo Y, em y={y}")
    case (x, y): # Captura ambos x e y
        print(f"Ponto ({x}, {y})")
    case _:
        print("Não é um ponto válido.")
~~~

## Quando usar

- Substituir longas cadeias de if/elif/else por uma estrutura mais clara e legível.
- Lidar com diferentes estruturas de dados (listas, tuplas, objetos) de forma elegante.
- Quando a lógica depende de muitos valores ou padrões diferentes para a mesma variável. 
