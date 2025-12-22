---
titulo: Linguagens compiladas e interpretradas
---

# Linguagens compiladas e interpretradas

Linguagens compiladas traduzem todo o código-fonte para código de máquina antes da execução, gerando um executável mais rápido, mas menos portátil (ex: C, C++)

Linguagens interpretadas traduzem linha por linha em tempo real por um interpretador, oferecendo mais flexibilidade e portabilidade, mas geralmente com performance menor (ex: Python, JavaScript)

## Linguagens Compiladas

- **Como funciona**: Um compilador traduz todo o código-fonte para código de máquina (binário) de uma vez, criando um arquivo executável separado.
- **Vantagens**: Execução mais rápida, detecção de erros antes da execução.
- **Desvantagens**: Menos portabilidade (precisa compilar para cada sistema), processo de "build" mais demorado para mudanças.
- **Exemplos**: C, C++, Go, Rust, Swift, Delphi.

## Linguagens Interpretadas

- **Como funciona**: Um interpretador lê e executa o código-fonte linha por linha, em tempo real.
- **Vantagens**: Maior flexibilidade, portabilidade (mesmo código roda em qualquer lugar com o interpretador), fácil depuração.
- **Desvantagens**: Geralmente mais lentas que as compiladas, erros só aparecem na execução.
- **Exemplos**: Python, JavaScript, PHP, Ruby, Perl.

## JIT (Just-in-Time)

O JIT (Just-in-Time) é uma técnica utilizada em alguns interpretadores para melhorar o desempenho. O JIT compila partes do código em tempo de execução, otimizando-as para a arquitetura específica do computador. Isso pode resultar em um ganho significativo de desempenho em algumas situações.

## Linguagens Híbridas

- **Como funciona**: Compilam o código-fonte para um código intermediário (bytecode) e depois uma máquina virtual (interpretador) executa esse bytecode.
- **Vantagens**: Combina performance (compilação) com portabilidade (máquina virtual).
- **Exemplos**: Java, C# (com .NET).
