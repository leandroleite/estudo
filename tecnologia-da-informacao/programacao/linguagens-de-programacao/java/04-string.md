---
titulo: String
---
- [Trabalhando com string: String em Java}(https://www.devmedia.com.br/trabalhando-com-string-string-em-java/21737): Veja neste artigo o que são String em Java. Todos os tipos utilizados na linguagem Java, com exceção dos tipos primitivos (int, double, char e boolean), são objetos. O tipo String, com S maiúsculo, é um dos objetos mais utilizados.
- [Java: verifique se a string é nula, vazia ou em branco](https://codegym.cc/pt/groups/posts/pt.666.java-verifique-se-a-string-e-nula-vazia-ou-em-branco): Em Java, é muito fácil confundir uma string nula, vazia ou em branco para iniciantes. No entanto, vamos pela definição de cada um para traçar uma linha de diferença.
- [String em Java: Entendendo e utilizando essa classe](https://www.devmedia.com.br/string-em-java-entendendo-e-utilizando-essa-classe/25503): String é uma das classes mais utilizadas, dada a trivialidade do processamento de textos em aplicações e as facilidades que ela provê nesse contexto. Através deste artigo você aprenderá como criar e utilizar Strings em Java.

# String

String são objetos ou instâncias da classe **java.lang.String**, portanto, devem ser declarados e instanciados.

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

## Concatenando Strings

### Método concat

- **String concat(String str)**
- Só aceita string como parâmetro (se for caractere tem que converter antes para String)

~~~java
"teste".concat("string2");
string1.concat(Character.toString('x'));
~~~

### Operador +

~~~java
"Hello," + " world" + "!"
~~~

## Método charAt

- **char charAt(int index)**
- retorna o caractere
- índice semore começa com 0

## Método length

- **int length()**
- retorna o tamanho

