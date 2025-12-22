---
titulo: Recomendações do PEP-8
---

# Recomendações do PEP-8

O PEP 8 é o guia de estilo oficial do Python que define convenções para tornar o código mais legível e consistente, focando em indentação (4 espaços, sem tabs), comprimento de linha (máx. 79 caracteres), nomenclatura (snake_case para funções/variáveis, CamelCase para classes), uso de espaços em torno de operadores/vírgulas, e organização de importações em linhas separadas no topo do arquivo, visando clareza e colaboração.

## Principais Recomendações do PEP 8

**Indentação**:

- Use **4 espaços** por nível de indentação; nunca use tabs.
- Evite misturar espaços e tabs.

**Comprimento da Linha**:

- Limite as linhas a **79 caracteres** para facilitar a leitura lado a lado.
- Use quebras de linha com parênteses para expressões longas, preferencialmente antes de operadores binários (como +, *).

**Nomenclatura (Naming Conventions)**:

- **Funções e Variáveis**: snake_case (minúsculas com sublinhados).
- **Classes**: CamelCase (primeira letra de cada palavra maiúscula).
- **Constantes**: MAIUSCULAS_COM_SUBLINHADOS.
- Evite usar l, O, I como nomes de variáveis de caractere único para não confundir com 1 e 0.

**Espaçamento**:

- Use espaços em torno de operadores (=, ==, +, -) e após vírgulas.
- Evite espaços no final das linhas e excesso de espaços em branco.

**Importações**:

- Coloque todas as importações no topo do arquivo, em linhas separadas.
- Agrupe-as: bibliotecas padrão, terceiros, locais.

**Comentários**:

- Use comentários para explicar o "porquê", não o "o quê" (o código deve ser autoexplicativo).
- Comentários de linha única começam com # seguido de um espaço.
- Use docstrings (strings de múltiplas linhas) para documentar funções, classes e módulos.

**Organização**:

- Separe funções e classes com duas linhas em branco.
- Use linhas em branco para separar blocos lógicos dentro de funções.
