---
titulo: Operações Básicas
---
# Operações Básicas

## Operador de Atribuição

O operador de atribuição (**a = b**) inicializa ou atualiza o valor de **a** com o valor de **b**:

~~~swift
let b = 10
var a = 5
a = b
~~~

Se o lado direito da atribuição for uma tupla com vários valores, seus elementos podem ser decompostos em várias constantes ou variáveis de uma só vez:

~~~swift
let (x, y) = (1, 2)
// x = 1
// y = 2
~~~

Não retorna valor:

~~~swift
if x = y {
    // Não é válido, pois x = y não retorna valor.
}
~~~
