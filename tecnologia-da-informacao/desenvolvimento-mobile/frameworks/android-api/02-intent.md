---
titulo: Intent
---
- [Intents e filtros de intents]([https://www.ibm.com/br-pt/topics/supervised-learning#:~:text=O%20aprendizado%20supervisionado%2C%20conhecido%20tamb%C3%A9m,ou%20preveem%20resultados%20com%20precis%C3%A3o.](https://developer.android.com/guide/components/intents-filters?hl=pt-br)): O Intent é um objeto de mensagem que pode ser usado para solicitar uma ação de outro componente do aplicativo.

# Intent

O Intent é um objeto de mensagem que pode ser usado para solicitar uma ação de outro componente do aplicativo. 

## Iniciar uma atividade

Uma Activity representa uma única tela em um aplicativo. É possível iniciar uma nova instância de uma Activity passando um Intent para startActivity(). O Intent descreve a atividade a iniciar e carrega todos os dados necessários.

## Iniciar um serviço

Para versões anteriores ao Android 5.0 (API nível 21), é possível iniciar um serviço usando os métodos da classe Service. É possível iniciar um serviço para realizar uma operação que acontece uma vez (como fazer o download de um arquivo) passando um Intent a startService(). O Intent descreve o serviço a iniciar e carrega todos os dados necessários.

## Fornecer uma transmissão

Transmissão é uma mensagem que qualquer aplicativo pode receber. O sistema fornece diversas transmissões para eventos do sistema, como quando o sistema inicializa ou o dispositivo inicia o carregamento. Você pode fornecer uma transmissão a outros aplicativos passando um Intent ao sendBroadcast() ou ao sendOrderedBroadcast().

## Tipos de intents

- **intents explícitos** especificam qual aplicativo atenderá ao intent, fornecendo o nome do pacote do aplicativo de destino ou o nome da classe de um componente totalmente qualificado.
- **intents implícitos** não nomeiam nenhum componente específico, mas declaram uma ação geral a realizar, o que permite que um componente de outro aplicativo a processe. 
