---
titulo: Requisitos não funcionais
---

# Requisitos não funcionais

Os Requisitos Não Funcionais **definem "como" o sistema deve se comportar, em vez de "o que" ele faz**. Eles descrevem atributos do sistema que não são funcionalidades diretas, mas que **garantem a qualidade e o comportamento do produto**. Ao contrário dos requisitos funcionais, que direcionam os recursos de um produto, os NFRs asseguram a qualidade geral do produto e a satisfação do usuário.

## Tornadar visíveis dentro do Scrum

- **No Backlog do Produto como itens próprios**: RNFs podem ser adicionados ao Backlog do Produto como itens independentes. Isso garante que sejam visíveis, estimáveis e possam ser priorizados juntamente com os requisitos funcionais. É útil para RNFs que não se aplicam amplamente a todo o incremento do produto.
- **Integrados na Definição de Pronto (DoD - Definition of Done)**: Para RNFs que se aplicam a todo o incremento do produto e a muitos itens do Backlog do Produto, a inclusão na Definição de Pronto é uma prática comum. Isso assegura que cada incremento do produto atenda a esses critérios de qualidade antes de ser considerado "Pronto", garantindo que a qualidade seja uma preocupação constante em todos os Sprints.
- **Nos critérios de aceitação de itens do Backlog do Produto**: Os RNFs podem ser incorporados aos critérios de aceitação de histórias de usuário específicas. Isso ajuda a detalhar como uma funcionalidade particular deve se comportar em termos de qualidades não funcionais, como "o e-mail de confirmação deve ser enviado em até 30 segundos após o pagamento".
- **Lista separada no quadro do Scrum**: Manter uma lista dedicada ou usar uma coluna/cor distinta no quadro do Scrum pode aumentar a visibilidade dos RNFs para a equipe.
- **Testes de integração e regressão**: A execução regular desses testes pode identificar se algum RNF foi negligenciado, permitindo que as tarefas pendentes sejam adicionadas ao Backlog do Sprint subsequente.

## Melhores práticas

- **Envolver o Product Owner**: O Product Owner deve ter um entendimento profundo dos RNFs, pois ele é responsável pelo Product Backlog. Interações e revisões regulares são essenciais para garantir que os RNFs sejam priorizados corretamente. Mesmo que a origem seja técnica, o Product Owner deve validar e priorizar.
- **Revisar e atualizar regularmente**: Assim como os requisitos funcionais, os RNFs podem evoluir. Revisões regulares, através do refinamento do backlog, garantem que os RNFs permaneçam relevantes e alinhados aos objetivos do projeto.
- **Usar ferramentas e técnicas**: Ferramentas como JIRA ou Trello podem ser personalizadas para destacar os RNFs. Técnicas como o mapeamento de histórias de usuários também podem ajudar a visualizar como os RNFs se encaixam no cenário geral do produto.
- **Feedback Antecipado**: Incorporar RNFs na Definição de Pronto e testá-los desde o início de um Sprint permite obter feedback rápido, evitando problemas maiores no final do desenvolvimento.
- **Priorização e Iteração**: Tratar os RNFs como "requisitos" que podem ser refinados, testados e corrigidos ao longo das Sprints, garantindo que a qualidade seja uma preocupação constante.

## Glossário

- **Requisitos Não Funcionais**: Atributos que definem "como" um sistema deve se comportar, focando em qualidades como desempenho, segurança, usabilidade, confiabilidade, escalabilidade e manutenibilidade, em vez de "o que" ele faz.
- **Requisitos Funcionais**: Descrições do que um sistema deve fazer, ou seja, as funcionalidades e características diretas que o produto oferece aos usuários.
- **Scrum**: Um framework ágil para desenvolver e sustentar produtos complexos, com foco em equipes pequenas e auto-organizadas trabalhando em iterações curtas (Sprints).
- **Product Backlog**: Uma lista ordenada de tudo que é conhecido por ser necessário no produto. É a única fonte de requisitos para qualquer alteração a ser feita no produto e contém recursos, funções, requisitos, melhorias e correções.
- **Definição de Pronto**: Uma descrição formal do estado do Incremento quando ele atende às medidas de qualidade exigidas para o produto. Garante que todos os membros da equipe saibam o que significa "Pronto" para um incremento, incluindo frequentemente requisitos não funcionais.
- **Sprint**: Um período de tempo fixo (geralmente de uma a quatro semanas) durante o qual uma "versão" utilizável e potencialmente liberável do produto é criada.
- **Incremento**: A soma de todos os itens do Product Backlog concluídos durante uma Sprint e o valor de incrementos de todas as Sprints anteriores. Deve ser utilizável e aderir à Definição de Pronto.
- **Product Owner**: O membro da equipe Scrum responsável por maximizar o valor do produto resultante do trabalho da Equipe de Desenvolvimento. Ele gerencia o Product Backlog.
- **Equipe de Desenvolvimento**: Pessoas na Equipe Scrum que estão comprometidas em criar qualquer aspecto de um Incremento utilizável em cada Sprint.
- **Critérios de Aceitação**: Condições que um item do Product Backlog deve satisfazer para ser aceito como "concluído". Podem incluir requisitos não funcionais específicos para aquele item.
- **Refinamento do Backlog**: Uma atividade contínua no Scrum onde o Product Owner e a Equipe de Desenvolvimento adicionam detalhes, estimativas e ordem aos itens do Product Backlog. Anteriormente conhecido como "Backlog Grooming".
- **Visibilidade**: Um pilar do empirismo no Scrum que se refere à necessidade de que todos os aspectos do processo e do trabalho sejam visíveis para aqueles que são responsáveis pelo resultado.
- **Performance**: Um tipo de RNF que descreve a velocidade, tempo de resposta e capacidade de um sistema.
- **Segurança**: Um tipo de RNF que se refere à proteção de dados e recursos do sistema contra acessos não autorizados ou ameaças.
- **Usabilidade**: Um tipo de RNF que descreve a facilidade com que os usuários podem aprender e operar o sistema.
- **Escalabilidade**: Um tipo de RNF que indica a capacidade do sistema de lidar com um aumento na carga de trabalho ou no número de usuários.
