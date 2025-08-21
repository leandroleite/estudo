---
titulo: Dívida técnica
---

# Dívida Técnica

A dívida técnica no Scrum refere-se ao **custo implícito de trabalho ou retrabalho ao adotar uma solução mais fácil, rápida ou conveniente no presente, em vez de usar uma abordagem melhor que levaria mais tempo**. Ela implica um custo futuro de retrabalho que surge da priorização de velocidade e atalhos de curto prazo em detrimento de um código de maior qualidade.

## O Guia do Scrum e a Dívida Técnica

O Guia do Scrum não menciona explicitamente a dívida técnica.

- O Scrum Team nunca compromete a qualidade.
- A definição de "Concluído" é fornecida pela organização de engenharia ou pela Equipe de Desenvolvimento. Se a definição de "Concluído" for melhorada, pode ser necessário retrabalhar Incrementos anteriores do produto.
- O Product Owner é responsável por maximizar o valor do trabalho da Equipe de Desenvolvimento.
- A Equipe de Desenvolvimento é responsável por entregar um Incremento de Produto (pelo menos) ao final do sprint, aderindo à definição de "Pronto".
- Durante o Planejamento do Sprint, a Equipe de Desenvolvimento escolhe os itens do Backlog do Produto que considera necessários para atingir a Meta do Sprint e pode adicionar novos itens se mais for aprendido.

## Responsabilidade e Gestão da Dívida Técnica no Scrum

- Lidar com a dívida técnica é uma **responsabilidade de toda a Equipe Scrum**. É um excelente exemplo dos freios e contrapesos integrados do Scrum.
- A remoção e erradicação da dívida técnica **devem ser incorporadas ao próximo sprint**. Isso significa controlar e pagar a dívida técnica para manter a velocidade e a produtividade do desenvolvedor.
- **Não gerenciar a dívida técnica vai contra os princípios de adaptabilidade e entregabilidade do Scrum** e pode bloquear o progresso da equipe, tornando a base de código mais difícil de ler, manter e estender.

## Como Lidar com a Dívida Técnica em uma Equipe Scrum

- **Seja transparente:** Visualize a dívida técnica existente de forma destacada.
- **Use métricas de código para monitorar a dívida técnica**, como complexidade ciclomática, cobertura de código, classificação SQALE, violações de regras, ou simplesmente conte o número de bugs.
- **Pague a dívida técnica regularmente a cada sprint:** Considere alocar de 15% a 20% da capacidade da Equipe de Desenvolvimento a cada Sprint para lidar com refatoração e correção de bugs.
- **Certifique-se de que todas as tarefas relacionadas à dívida técnica façam parte do Product Backlog** – não há contabilidade paralela no Scrum. Elas devem ser priorizadas e trabalhadas pelas equipes conforme necessário.
- **Adapte sua definição de "Concluído"** para atender à sua compreensão da qualidade do produto, por exemplo, definindo requisitos de qualidade de código que contribuam para manter a dívida técnica em um nível administrável a longo prazo.
- **Crie um procedimento padrão sobre como lidar com experimentos** que introduzirão temporariamente dívida técnica para acelerar o aprendizado em um campo crítico.

## Glossário

- **Dívida Técnica:** O custo implícito de retrabalho adicional causado pela escolha de uma solução fácil e rápida agora, em vez de uma abordagem melhor que levaria mais tempo. Pode ser intencional ou não intencional.
- **Scrum:** Uma estrutura ágil de gerenciamento de projetos que visa ajudar a estruturar e gerenciar equipes, normalmente por meio de um Product Owner, um Scrum Master e Desenvolvedores.
- **Product Owner:** O membro da Equipe Scrum responsável por maximizar o valor do trabalho da Equipe de Desenvolvimento, gerenciando o Product Backlog.
- **Equipe de Desenvolvimento:** No Scrum, o grupo de profissionais que entrega um Incremento "Pronto" de um produto funcional ao final de cada Sprint.
- **Incremento do Produto:** A soma de todos os itens do Product Backlog concluídos durante um Sprint e os Incrementos de todos os Sprints anteriores. Deve estar em um estado "Pronto".
- **Definição de "Pronto":** Uma lista formal de critérios ou padrões que um item do Product Backlog deve atender para ser considerado "concluído". Garante a qualidade do Incremento.
- **Product Backlog:** Uma lista ordenada de tudo o que se sabe ser necessário no produto. É a única fonte de requisitos para quaisquer alterações a serem feitas no produto.
- **Sprint Backlog:** O conjunto de itens do Product Backlog selecionados para o Sprint, mais o plano para entregá-los e atingir a Meta do Sprint.
- **Sprint:** Um time-box de um mês ou menos durante o qual um Incremento "Pronto", utilizável e potencialmente liberável do produto é criado.
- **Refatoração:** O processo de melhorar a estrutura interna de um código existente sem alterar seu comportamento externo. Essencial para gerenciar e reduzir a dívida técnica.
- **Complexidade Ciclomática:** Uma métrica de código que indica a complexidade de um programa, baseada no número de caminhos independentes através do código. Usada para monitorar a dívida técnica.
- **Cobertura de Código:** Uma métrica que mede a porcentagem de linhas de código, ramos ou declarações que são executadas por testes automatizados. Usada para monitorar a dívida técnica.
- **Classificação SQALE:** Um modelo de classificação para avaliação da qualidade do software, frequentemente usado para quantificar a dívida técnica.
- **Gráfico Burn-down:** Um gráfico que mostra a quantidade de trabalho restante versus o tempo em um Sprint. Pode ser adaptado para visualizar o impacto da dívida técnica na produtividade.
- **Dívida Técnica Intencional:** Dívida técnica criada deliberadamente por decisões táticas para alcançar objetivos de curto prazo, com ou sem a intenção de refatorar posteriormente.
- **Dívida Técnica Não Intencional:** Dívida técnica criada inconscientemente devido a codificação ruim, falta de conhecimento, pressa ou testes inadequados, sem que os desenvolvedores estejam cientes dos problemas introduzidos.
- **Dívida Técnica Ambiental:** Dívida técnica que surge devido a fatores externos ao código ou às intenções dos desenvolvedores, como atualizações de sistema operacional, APIs de terceiros ou patches de segurança que afetam a funcionalidade existente.
- **Revisão de Sprint:** Um evento Scrum formal onde a Equipe Scrum e as partes interessadas inspecionam o Incremento do Produto e adaptam o Product Backlog, fornecendo uma oportunidade para discutir a dívida técnica.
- **Empirismo:** Um pilar do Scrum que baseia decisões em experiências passadas e observação, em vez de em planos detalhados. Promovido através da transparência, inspeção e adaptação.
- **Fábrica de Recursos:** Um termo pejorativo para uma equipe ou organização que se concentra exclusivamente na entrega de novos recursos, muitas vezes à custa da qualidade e do gerenciamento da dívida técnica.
