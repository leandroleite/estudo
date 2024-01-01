---
titulo: TypeScript
---
- [O que é TypeScript? [Guia para iniciantes]](https://tecnoblog.net/responde/o-que-e-typescript-guia-para-iniciantes/): Saiba o que é TypeScript, quando foi criado e quais recursos e vantagens a linguagem adiciona ao JavaScript tradicional
- [Introdução a Typescript: o que é e como começar?](https://blog.geekhunter.com.br/introducao-a-typescript/): Sabendo das limitações que o Javascript possui, Anders Hejlsberg, que também participou da criação do C#, do Delphi, do Turbo Pascale da plataforma .NET, resolveu criar o Typescript.
- [TypeScript, conheça o JavaScript com tipos](https://4future.com.br/index.php/2023/10/11/typescript-conheca-o-javascript-com-tipos/): Antes de mais nada, o TypeScript não é uma linguagem de programação como muitos pensam.

# TypeScript

TypeScript é um superconjunto de JavaScript, ou seja, um conjunto de ferramentas e formas mais eficientes de escrever código JavaScript, adicionando recursos que não estão presentes de maneira nativa na linguagem.

A principal caraterística do TypeScript é sua tipagem forte, razão pela qual leva no seu nome: type quer dizer tipo. Mas também há outro aspecto, a **Orientação a Objetos**.

## Tipagem estática

~~~typescript
let numeroQualquer: number;
valor = 10.5;
~~~

## Inferência de tipo

É a tipagem "automática", onde a variável ou retorno de uma função consegue identificar o tipo baseado no seu valor inicial (ou no valor de retorno no caso da função).

~~~typescript
let numeroQualquer: 10; // number
valor = 10.5;
~~~

