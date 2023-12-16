---
titulo: Activity
---
- [Introdução a atividades](https://developer.android.com/guide/components/activities/intro-activities?hl=pt-br): A classe Activity é um componente crucial de um app para Android, e a maneira como as atividades são lançadas e reunidas é uma parte fundamental do modelo de aplicativo da plataforma. 

# Activity

A classe Activity é um componente crucial de um app para Android, e a maneira como as atividades são lançadas e reunidas é uma parte fundamental do modelo de aplicativo da plataforma. Diferentemente dos paradigmas de programação em que os apps são lançados com um método main(), o sistema Android inicia o código em uma instância Activity invocando métodos de callback que correspondem a estágios específicos do ciclo de vida.

## Ciclo de vida da atividade

### onCreate()

- Você precisa implementar esse callback, que é acionado quando o sistema cria sua atividade. A implementação inicializará os componentes essenciais da atividade.
- Quando onCreate() termina, o próximo callback sempre é onStart().

### onStart()

Quando onCreate() sai, a atividade entra no estado "Iniciado" e se torna visível para o usuário. Esse callback contém o que equivale aos preparativos finais da atividade para ir para o primeiro plano e se tornar interativa.

### onResume()

- O sistema invoca esse callback imediatamente antes de a atividade começar a interagir com o usuário. Neste ponto, a atividade fica na parte superior da pilha de atividades e captura toda a entrada do usuário. A maior parte da funcionalidade principal de um app é implementada no método onResume().

### onPause()

- O sistema chama onPause() quando a atividade perde o foco e entra em um estado "Pausado".
- Esse estado ocorre quando, por exemplo, o usuário toca no botão "Voltar" ou "Recentes".
- Quando o sistema chama onPause() para sua atividade, isso significa, tecnicamente, que ela ainda está parcialmente visível. Porém, na maioria das vezes, é uma indicação de que o usuário está deixando a atividade e que logo ela entrará no estado "Interrompido" ou "Retomado".
- Uma atividade no estado "Pausado" pode continuar atualizando a IU se o usuário estiver esperando por isso. Exemplos de uma dessas atividades incluem a exibição da tela de um mapa de navegação ou de um player de mídia sendo reproduzido. Mesmo que essas atividades percam o foco, o usuário espera que a IU continue sendo atualizada.

### onStop()

- O sistema chama onStop() quando a atividade não está mais visível para o usuário. Isso pode acontecer porque a atividade está sendo destruída, uma nova atividade está sendo iniciada ou uma atividade existente está entrando em um estado "Retomado" e está cobrindo a atividade interrompida. Em todos esses casos, a atividade interrompida não fica mais visível.
- O próximo callback que o sistema chamar será onRestart(), se a atividade voltar a interagir com o usuário, ou onDestroy(), se essa atividade for completamente encerrada.

### onRestart()

- O sistema invoca esse callback quando uma atividade no estado "Interrompido" está prestes a ser reiniciada. onRestart() restaura o estado da atividade a partir do momento em que ela foi interrompida.

### onDestroy()

- O sistema invoca esse callback antes de uma atividade ser destruída.
- Esse é o último callback que a atividade recebe. onDestroy() normalmente é implementado para garantir que todos os recursos de uma atividade sejam liberados quando ela (ou o processo que a contém) for destruída.
