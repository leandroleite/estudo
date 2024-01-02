---
titulo: String
---
- [Java: verifique se a string é nula, vazia ou em branco](https://codegym.cc/pt/groups/posts/pt.666.java-verifique-se-a-string-e-nula-vazia-ou-em-branco): Em Java, é muito fácil confundir uma string nula, vazia ou em branco para iniciantes. No entanto, vamos pela definição de cada um para traçar uma linha de diferença. 

# String

## String nula

- É é usada para se referir a nada
- Indica que a variável String não está realmente vinculada a nenhum local de memória

~~~Java
String myName = null;
~~~

## String vazia

-  Significa uma String com comprimento igual a zero.
-  Existe método **.isEmpty()** que retorna se está vazia ou não

~~~Java
String myName = new String();
if (myName != null || myName.isEmpty()) {
  //String é vazia
}
~~~

## String em branco

- É igual a uma String com um ou vários espaços
-  Existe método **.isBlank()** que retorna se está em branco ou não

~~~Java
String myName = new String("   \t  \n    \t \t   ");
if (myName != null || myName.isBlank()) {
  //String em branco
}
~~~ 
