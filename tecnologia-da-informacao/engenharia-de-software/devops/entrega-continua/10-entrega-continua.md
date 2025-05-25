---
titulo: Entrega Contínua
---

# Entrega Contínua

A Entrega Contínua (Continuous Delivery, ou CD) **é uma prática de DevOps que automatiza o processo de construção, teste e implantação de software, permitindo que as alterações sejam entregues aos usuários de forma rápida e segura**. Em essência, a CD garante que o software esteja sempre pronto para ser lançado, e que as atualizações sejam efetuadas de forma eficiente.

## Como funciona

- **Automatização**: A CD utiliza ferramentas e pipelines automatizados para executar testes e implantações, reduzindo a necessidade de intervenção manual.
- **Integração Contínua**: A CD é frequentemente combinada com a Integração Contínua (CI), que automatiza a integração de código em um repositório central.
- **Testes Automáticos**: A CD inclui testes automatizados em várias etapas do processo de desenvolvimento, desde testes de unidade até testes de integração e teste de desempenho.
- **Implantação Automática**: O código aprovado pelos testes é automaticamente implantado em ambientes de teste e/ou produção, dependendo da configuração do pipeline.
- **Feedbacks Contínuos**: A CD permite que os desenvolvedores recebam feedback sobre as alterações de código e as implantações, o que ajuda a identificar e corrigir problemas rapidamente.

## Benefícios

- **Aceleração da entrega de software**: A CD permite que as equipes entreguem software mais rapidamente, reduzindo o tempo entre o desenvolvimento e a produção.
- **Melhora da qualidade do software**: Os testes automatizados ajudam a identificar e corrigir erros de código antes que eles sejam implantados em produção.
- **Redução de riscos de implantação**: A CD permite que as equipes implantem alterações de forma mais segura e confiável, reduzindo o risco de interrupções ou problemas na produção.
- **Melhora da colaboração entre equipes**: A CD promove a colaboração entre as equipes de desenvolvimento, operações e testes, o que ajuda a criar um processo de desenvolvimento mais eficiente.
- **Aumento da satisfação do cliente**: A entrega de software mais rápida e de melhor qualidade leva a um aumento da satisfação do cliente.

## Entrega Contínua vs. Implantação Contínua

A diferença crucial entre Entrega Contínua e Implantação Contínua é a presença de uma aprovação manual para atualizar o ambiente de produção.

- Com a Entrega Contínua, o artefato de compilação pronto para implantação aguarda a decisão do desenvolvedor para ser implantado em produção. Cada alteração de código é enviada para um ambiente de teste ou preparação (não produção).
- Com a Implantação Contínua, a atualização da produção ocorre automaticamente, sem aprovação explícita.

## Glossário

- **Entrega Contínua**: Prática de desenvolvimento de software onde as alterações de código são automaticamente preparadas para uma liberação para produção, garantindo que o software esteja sempre pronto para ser lançado.
- **Integração Contínua**: Prática onde os desenvolvedores integram o código frequentemente em um repositório compartilhado, geralmente várias vezes ao dia, e cada integração é verificada por uma compilação e testes automatizados.
- **Pipeline de Lançamento**: Uma série de estágios automatizados que uma alteração de código passa desde o commit inicial até a implantação em produção, incluindo compilação, teste e preparação.
- **Ambiente de Teste/Preparo**: Um ambiente que replica de perto o ambiente de produção e é usado para executar testes mais abrangentes antes da liberação final.
- **Artefato de Compilação**: O resultado de um processo de compilação, como um pacote executável ou instalador, que está pronto para ser implantado.
- **Implantação Contínua**: Uma extensão da Entrega Contínua onde as alterações de código que passam em todos os estágios do pipeline de lançamento são automaticamente implantadas em produção sem aprovação manual.
- **Testes Automatizados**: Testes que são executados por meio de scripts e ferramentas, em vez de manualmente, como testes de unidade, integração, UI e carga.
- **Infraestrutura como Código**: A prática de gerenciar e provisionar infraestrutura de TI através de código, em vez de processos manuais.
- **Tempo de Mitigação**: O tempo que leva para resolver e mitigar um problema ou incidente de produção.
- **Tempo de Correção**: Similar ao TTM, refere-se ao tempo necessário para corrigir um defeito ou erro após ele ter sido identificado.
- **Fail-fast**: Uma abordagem em testes onde os testes com maior probabilidade de falha são executados primeiro no pipeline para identificar problemas o mais cedo possível.
- **DevOps**: Um conjunto de práticas que combina desenvolvimento de software (Dev) e operações de TI (Ops) para encurtar o ciclo de vida de desenvolvimento de sistemas e fornecer entrega contínua de alta qualidade.
