---
titulo: Modificadores de acesso
---
- [Modificadores de acesso](https://www.dio.me/articles/modificadores-de-acesso): Modificadores de acesso são palavras-chave usadas em Java para controlar a visibilidade de membros de uma classe, como atributos e métodos.
- [Modificadores de Acesso](https://medium.com/trainingcenter/modificadores-de-acesso-3f87133611c8): Nem sempre é interessante expor seus métodos e atributos para qualquer pessoa que consuma suas classes, por isso existem os modificadores de acesso.

# Modificadores de acesso

Modificadores de acesso são palavras-chave usadas em Java para controlar a visibilidade de membros de uma classe, como atributos e métodos. 

## Public

- O acesso público é o mais permissivo. 
- Qualquer classe pode acessar membros públicos.

## Private

- O acesso privado é o mais restritivo.
- Apenas a classe que define o membro pode acessar membros privados.

## Protect

- O acesso protected é intermediário entre public e private.
- Membros protected podem ser acessados por classes descendentes da classe que define o membro.

## Default

- Modificador de acesso padrão, usado quando nenhum for definido.
- Neste caso os atributos, métodos e classes são visíveis por todas as classes dentro do mesmo pacote.
