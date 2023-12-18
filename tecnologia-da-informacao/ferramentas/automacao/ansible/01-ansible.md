---
titulo: Ansible
---
- [Para que serve o Ansible. O que é módulo, playbook e linguagem YAML. - 4Linux]([https://developer.android.com/guide/components/activities/intro-activities?hl=pt-br](https://4linux.com.br/o-que-e-ansible/)): Ansible é uma ferramenta de automação de TI que pode configurar sistemas, implantar aplicativos e provisionar recursos de nuvem. Ansible usa uma abordagem agentless para gerenciar configurações, o que significa que não é necessário instalar um agente de software em seus sistemas para serem gerenciados. Além disso, Ansible pode ser executado em qualquer sistema operacional que suporte Python.
- [Princípios básicos do Ansible](https://www.redhat.com/pt-br/topics/automation/learning-ansible-tutorial): O Ansible® é um mecanismo open source de automação. Ele ajuda a automatizar o provisionamento, o gerenciamento de configurações, a implantação de aplicações, a orquestração e muitos outros processos de TI.
- [Ansible dicas para quem está começando a usar a ferramenta de automação](https://blog.mandic.com.br/artigos/ansible-dicas-para-quem-esta-comecando-a-usar-a-ferramenta-de-automacao/): O Ansible é uma ferramenta de automação de código aberto usada para configurar servidores, instalar software e executar uma grande variedade de tarefas de TI a partir de uma localização central.

# Ansible

- É uma ferramenta de automação de TI que pode configurar sistemas, implantar aplicativos e provisionar recursos de nuvem.
- Usa uma abordagem agentless para gerenciar configurações, o que significa que não é necessário instalar um agente de software em seus sistemas para serem gerenciados.

## Automação sem agentes

O Ansible é uma ferramenta sem agentes, ou seja, não requer instalação de software para gerenciamento dos nós. Ele acessa seu inventário e lê as informações sobre quais máquinas você deseja gerenciar. O Ansible tem um arquivo de inventário padrão, mas você pode criar o seu próprio arquivo e definir quais servidores quer que sejam gerenciados. 

Ele usa o protocolo SSH para se conectar aos servidores e executar as tarefas. Por padrão, o Ansible usa chaves SSH com o ssh-agent e seu nome de usuário atual para se conectar a máquinas remotas. Não é preciso ter login de raiz. Faça login com qualquer usuário e execute os comandos su ou sudo.

## YAML - linguagem de modelagem de dados

- O Ansible usa uma abordagem de desenvolvimento de código declarativo para criar e gerenciar configurações. 
- Isso significa que, em vez de escrever scripts para automatizar tarefas, os usuários definem o estado desejado dos sistemas e Ansible torna a realidade. 
- O Ansible fornece uma linguagem de modelagem de dados, chamada YAML. Com ela é possível escrever os playbooks que são usados para definir o estado desejado dos sistemas.

## Ansible Playbook

- São um conjunto de instruções que especificam como um determinado sistema deve ser configurado ou gerenciado.
- Podem ser usados para automatizar tarefas simples ou complexas e podem ser facilmente compartilhados entre equipes de operações.
- São escritos em YAML, um formato de texto simples que é fácil de ler e de escrever.
- Cada Playbook consiste em um conjunto de chamadas de ação, que especificam o que o Ansible deve fazer em cada etapa. As ações são executadas em ordem, e os resultados da execução de cada ação são usados como entrada para as ações subsequentes.

Uma playbook basicamente é composta por **‘play’** e **‘tasks’**. 

- Uma **‘play’** é análoga a uma jogada ensaiada de basquete. Define-se quais jogadores participarão (Hosts alvo) e quais passos (tasks) serão executados.
- Num nível básico, uma **‘tasks’** nada mais é do que uma chamada aos **módulos** do Ansible.

## Tasks

Uma tarefa é a menor unidade de trabalho.

## Plays

Um play é composto de tarefas.

## Roles

as funções são usadas para salvar e organizar manuais e permitir compartilhar e reutilizar playbooks. 

## Ansible Galaxy

O Ansible Galaxy é um repositório online onde as funções são carregadas para que possam ser compartilhadas com outras pessoas. Está integrado com o GitHub, de modo que os roles podem ser organizados em repositórios Git e, em seguida, compartilhados via Ansible Galaxy.
