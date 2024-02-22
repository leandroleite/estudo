---
titulo: Tipos de dados primitivos e por referência
---
- [Tipos de dados por valor e por referência em Java]([https://programming.guide/java/overloading-overriding-shadowing-hiding-obscuring.html](https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293)): Veja neste artigo a definição de variáveis e os tipos de dados por valor e por referência utilizados na linguagem Java, entendendo como funciona sua declaração e inicialização.

# Tipos de dados primitivos e por referência

O Java possui dois tipos de dados que são divididos em **por valor** (tipos primitivos) e **por referência** (tipos por referência).

## Tipos Primitivos - por valor

São boolean, byte, char, short, int, long, float e double.

- As **variáveis de instância da classe** de tipo primitivo são **inicializadas por padrão**:
  - Com 0 para byte, char, short, int, long, float e double
  - Com false para boolean
- As **variáveis locais de métodos** de tipo primitivo precisam ser iniciadas antes de usar (senão ocorre erro)

## Tipos por Referência

São classes que especificam os tipos de objeto Strings, Arrays Primitivos e Objetos.

- Armazenam as localizações dos objetos na memória do computador
- São inicializadas com o valor **null**
