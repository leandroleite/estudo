---
titulo: Tipos de Componentes
---
- [Componentes funcionais x componentes de classe no React Native](https://www.freecodecamp.org/portuguese/news/componentes-funcionais-x-componentes-de-classe-no-react-native/#:~:text=Os%20componentes%20funcionais%20s%C3%A3o%20mais,(do%20ingl%C3%AAs%2C%20stateless).): No React Native, há dois tipos principais de componentes que compõem uma aplicação: componentes funcionais e componentes de classe. 

# Tipos de Componentes

No React Native, há dois tipos principais de componentes que compõem uma aplicação: **componentes funcionais** e **componentes de classe**. 

## Componentes de classe

- São classes do JavaScript ES2015 que estendem uma classe base do React chamada **Component**.
- Dá para a classe o acesso aos métodos do ciclo de vida do React, como render, bem como às funcionalidades de state/props dos componentes pai.

## Componentes funcionais

- São mais simples.
- Eles não gerenciam seu próprio state nem têm acesso aos métodos de ciclo de vida fornecidos pelo React Native.
- Eles são, literalmente, funções do JavaScript antigas e simples – às vezes, chamados de componentes sem estado (stateless).
