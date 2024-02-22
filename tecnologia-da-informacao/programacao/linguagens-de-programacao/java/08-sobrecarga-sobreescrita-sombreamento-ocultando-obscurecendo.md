---
titulo: Sobrecarga, Sobreescrita, Sombreamento, Ocultando e Obscurecendo
---
- [5 Java concepts explained: Overloading, overriding, shadowing, hiding, and obscuring](https://programming.guide/java/overloading-overriding-shadowing-hiding-obscuring.html): All five concepts are related to using the same name for different things.

# Sobrecarga, Sobreescrita, Sombreamento, Ocultando e Obscurecendo

## Sobrecarga - Overloading

Método na mesma classe com mesmo nome (mas com tipos de parâmetros diferente).

~~~java
class C {
    void m(String s) { System.out.println("String: " + s); }
    void m(int i)    { System.out.println("int: " + i);    }
}
~~~

## Sobreescrita - Overriding

Tem relação com a herança. **@Override**

Em Java, **variáveis de instância não se sobrescreve**. Somente sobrescreve **métodos**, 

~~~java
class Animal {
    void eat() { System.out.println("Cachorro comendo"); }
}

class Cachorro extends Animal {
    @Override
    void eat() { System.out.println("Cachorro comendo"); }
}
~~~

## Sombreamento - Shadowing

Quando uma variável sombrea outra se for do mesmo nome e acessível no mesmo lugar.

~~~java
class C {
    int i = 0;

    void m() {
        int i = 1;        
        System.out.println(i); // Variável local
        System.out.println(this.i); // Variável da classe
    }
}
~~~

## Ocultando - Hiding

Um campo esconde todos os campos com o mesmo nome nas superclasses. 

No exemplo abaixo, existem duas variáveis definidas. Uma para cada classe. Na classe Cachorro se quiser acessar a pernas da super classe, tem que usar super.pernas.
~~~java
class Animal {
    int pernas = 2;
}

class Cachorro extends Animal {
    int pernas = 4;
}
~~~

## Obscurecendo - Obscuring

Se uma variável local e uma classe tenha o mesmo nome, existe as regras de precedência podem tornar a classe inutilizável.

~~~java
class C {
    void m() {
        String System = "";
        System.out.println("Hello World"); // Não compila            
    }
}
~~~
