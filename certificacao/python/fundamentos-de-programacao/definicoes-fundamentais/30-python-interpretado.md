---
titulo: Python interpretado
---

# Python interpretado

Python é considerada **interpretada** porque o código-fonte é executado linha por linha por um interpretador, o que proporciona **flexibilidade**, **portabilidade** e **facilidade de depuração**, permitindo encontrar erros rapidamente.

Na verdade, Python é um híbrido: ele compila o código para um formato intermediário chamado bytecode, que é então interpretado pelo interpretador (como o CPython), oferecendo um meio-termo entre a produtividade de linguagens interpretadas e a otimização de linguagens compiladas.

## Python é classificada como interpretada

- **Execução em Tempo Real (Linha por Linha)**: O interpretador lê e executa o código Python diretamente, sem a necessidade de uma compilação completa para código de máquina antes da execução, como em C ou C++.
- **Portabilidade**: O mesmo código Python pode rodar em diferentes sistemas operacionais (Windows, macOS, Linux) desde que haja um interpretador Python instalado, pois o interpretador cuida das diferenças de plataforma.
- **Desenvolvimento Rápido e Depuração**: A execução linha por linha facilita a identificação e correção de erros, pois o programa para assim que encontra um problema, o que é ótimo para prototipagem e aprendizado.

## O Híbrido (Bytecode):

- Quando você executa um script Python, ele é primeiro compilado para um formato de bytecode (arquivos .pyc).
- Esse bytecode é mais otimizado e mais rápido para o interpretador processar do que o código-fonte original.
- A **VM Python** (Máquina Virtual) então interpreta esse bytecode para instruções de máquina.
