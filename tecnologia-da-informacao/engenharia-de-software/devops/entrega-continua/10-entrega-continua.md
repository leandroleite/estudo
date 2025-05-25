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
