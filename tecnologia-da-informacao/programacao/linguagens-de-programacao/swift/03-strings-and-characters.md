---
titulo: Strings and Characters
---

# Strings and Characters

## Interpolação de String

A interpolação de string é uma maneira de construir um novo valor de string a partir de uma mistura de constantes, variáveis, literais e expressões, incluindo seus valores dentro de um literal de string. Você pode usar a interpolação de string em literais de string de linha única e multilinha. Cada item inserido na string literal é colocado entre parênteses, prefixados por uma barra invertida (\\)

~~~swift
let multiplier = 3
let message = "\(multiplier) times" // 3 times"

print(#"Write an interpolated string in Swift using \(multiplier)."#)
// Prints "Write an interpolated string in Swift using \(multiplier)."

print(#"6 times 7 is \#(6 * 7)."#)
// Prints "6 times 7 is 42."
~~~
