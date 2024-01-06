---
titulo: Tratamento de exceções
---
- [Tratando exceções em Java](https://www.devmedia.com.br/tratando-excecoes-em-java/25514): Veja neste artigo como tratar exceções na linguagem Java, entendendo a teoria de funcionamento desse tipo de estrutura, passando pelos comandos de tratamento e captura até a customização de exceções para fins específicos.
- [Hands-on: como lidar com exceções em Java](https://medium.com/itautech/hands-on-como-lidar-com-exce%C3%A7%C3%B5es-em-java-1272d19ea181): Quando estamos atuando em ambientes críticos, como os que envolvem quantias financeiras ou interações com o mercado financeiro, por exemplo, é muito importante conseguirmos identificar rapidamente as causas de um problema quando ele aparece.

# Tratamento de exceções

As exceções ocorrem quando algo imprevisto acontece, elas podem ser provenientes de erros de lógica ou acesso a recursos que talvez não estejam disponíveis.

## Tipos de exceções

- **Checked exceptions**: ão as exceções em que um compilador torna seu tratamento obrigatório. Nesses casos, a maneira mais simples de trata-las é lançando a exceção adiante — porém, o código que utilizar o seu método deverá tratar obrigatoriamente a exceção em um bloco { try catch }, ou também lançá-la adiante.
- **Unchecked exceptions**: são exceções em que o compilador não estabelece obrigatoriedade para o seu tratamento. E é aqui que mora o perigo, já que você não receberá um aviso sobre sua existência.

## Tratando exceções - try catch finally

~~~java
try
{
  //trecho de código que pode vir a lançar uma exceção
}
catch(tipo_exceçao_1 e)
{
  //ação a ser tomada
}
catch(tipo_exceçao_2 e)
{
  //ação a ser tomada
}
finally
{
  //ação a ser tomada
}
~~~

- **try{ … }** - Neste bloco são introduzidas todas as linhas de código que podem vir a lançar uma exceção.
- **catch(tipo_excessao e) { … }** - Neste bloco é descrita a ação que ocorrerá quando a exceção for capturada.
- **finaly { ...}** - Ação a ser executada sempre no final.

## Comando throws

Utiliza o comando **throws** na assinatura do método quando se deseja que a exceção não seja tratada no método.

~~~java
public class TesteString {
  private static void aumentarLetras() throws NullPointerException //lançando excessão
  {
~~~

## Comando throw

Utiliza o comando **throw** para lançar uma exceção padrão.

~~~java
private static void aumentarLetras() throws Exception //lançando exceção
{
  try
  {
    ...
  }
  catch(NullPointerException e)
  {
    throw new Exception(e);
  }
}
~~~

## Criando exceções

Criar classe herdada de **Exception**.

~~~java
public class SemLetraBException extends Exception {
  @Override
  public String getMessage(){
    return "Não existe letra B em sua frase";
  }
}
~~~

