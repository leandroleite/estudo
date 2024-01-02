---
titulo: Princípios da programação orientada a objetos
---
- [Princípios de programação orientada a objetos em Java: Conceitos de POO para iniciantes](https://www.freecodecamp.org/portuguese/news/principios-de-programacao-orientada-a-objetos-em-java-conceitos-de-poo-para-iniciantes/) : A programação orientada a objetos é um paradigma de programação onde tudo é representado como um objeto.
- [Herança de construtores e Override](https://www.javaprogressivo.net/2012/10/heranca-de-construtores-e-override.html): Agora que você já sabe o que é herança, sua importância, quando usar e viu vários exemplos práticos do mundo real, vamos mostrar como fazer uma classe herdar as características de outra.
- [Variáveis ​​estáticas em Java – Por que e como usar métodos estáticos](https://www.dio.me/articles/variaveis-estaticas-em-java-por-que-e-como-usar-metodos-estaticos): Variáveis ​​estáticas e métodos estáticos são dois conceitos importantes em Java.

# Princípios da programação orientada a objetos

A programação orientada a objetos é um paradigma de programação onde tudo é representado como um objeto.

## Encapsulamento

É um processo de envolver dados e código em uma única unidade.

- Modificador de acesso **private**, que indica que a variável não pode ser acessado fora da classe.
- Métodos **getters** e **setters** públicos para acessar estados privados de modo seguro.

## Herança

Herança é um mecanismo onde um objeto recebe todos os comportamentos e estados de um objeto pai.

### Classe

Classes permitem heranças simples, multinível e hierárquicas. 

- **extends** somente uma classe
- **implements** uma interface

### Interface

Interfaces permitem heranças múltiplas e híbridas.

- **extends** outra interface

## Abstração

Abstração é o processo de esconder os detalhes de implementação e exibir apenas as funcionalidades para o usuário.

### Classes abstratas

- Não podem ser instanciadas.
- Podem ter construtores, métodos estáticos e métodos finais.

### Métodos abstratos

- Não possuem implementação.
- Não devem ser marcados como **private**

### Classes abstratas e métodos abstratos

- Se pelo menos um método for abstrato dentro de uma classe, então toda a classe deve ser abstrata.
- A primeira classe concreta que herde de uma classe abstrata deve prover implementação para todos os métodos abstratos.
- Caso a subclasse não implemente os métodos abstratos da superclasse, ela deve também ser marcada como abstrata.

## Interface

É um template de uma classe. É 100 abstrata. 

- Construtores não são permitidos aqui.
- Os métodos da interface são public e abstract.
- As variáveis de interface são public, static e final

A partir do Java, 8 foi introduzida a possibilidade de implementar métodos default e estáticos dentro de uma interface

### Métodos default

Tem que conter implementação na interface.

### Métodos estáticos

Chamar usando o nome da interface.

## Polimorfismo

É  a habilidade de um objeto de assumir diversas formas.

### Sobrecarga de métodos

Uma classe possui vários métodos, que possuem o mesmo nome mas parâmetros diferentes - **method overload**

- Precisa ter uma lista de parâmetros diferente.
- Pode possuir tipos de retorno diferentes.
- Pode possuir modificadores de acesso diferentes.
- Pode lançar exceções diferentes.

### Sobrescrita de métodos

Uma subclasse tem o mesmo método que foi declarado na superclasse **method override**

- Deve possuir a mesma lista de parâmetros.
- Deve possuir o mesmo tipo de retorno: embora um retorno covariante nos permita alterar o tipo de retorno do método sobrescrito.
- Não pode possuir um modificador de acesso mais restritivo: deve possuir um modificador de acesso menos restritivo.
- Não deve lançar uma exceção verificada (checked exception) nova ou mais ampla:
  - pode lançar exceções verificadas mais restritas
  - pode lançar qualquer exceção não verificada.
- Apenas métodos herdados podem ser sobrescritos (é necessário um relacionamento É UM).

## Métodos e variáveis estáticas - Static

- Há apenas uma cópia delas para toda a classe
- Não precisa instanciar a classe para chamar método estático
- Métodos estáticos somente podem ser redefinidos, nunca sobrescritos
- Nunca poderá acessar um variável não static de um método static

## Blocos de inicialização

- executam sempre antes de chamar o construtor
- set for **static** executa somente a primeira vez

### Ordem de Inicialização

- Os campos e os blocos inicializadores de instância são executados na ordem em que aparecem o arquivo.
- O construtor é executado depois que todos os campos e blocos de inicialização de instância são executados.

## Construtores

- Construtores não são herdados
- Para chamar explícitamente o construtor da superclasse, usa-se **super"" sempre na 1ª linha
- Se no construtor da subclasseSe não existir super(), java chmama implicitamente o construtor padrão da superclasse
