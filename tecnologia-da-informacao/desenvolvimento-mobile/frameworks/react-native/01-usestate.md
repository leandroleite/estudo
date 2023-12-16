---
titulo: useState
---
- [Hooks de forma resumida](https://pt-br.legacy.reactjs.org/docs/hooks-overview.html): Hooks são uma nova adição no React 16.8. Eles permitem que você use o state e outros recursos do React sem escrever uma classe.

# useState

- Nós o chamamos dentro de um componente funcional para adicionar alguns states locais a ele. 
- React irá preservar este state entre re-renderizações.
- useState retorna um par: o valor do state atual e uma função que permite atualizá-lo.
- Você pode chamar essa função a partir de um manipulador de evento ou de qualquer outro lugar.

~~~javascript
function Example() {
  // Declara uma nova variável de state, que chamaremos de "count" - inicializa com 0
  const [count, setCount] = useState(0);
~~~
