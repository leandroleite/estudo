---
titulo: Convenções de nomenclatura
---

# Convenções de nomenclatura

As convenções de nomenclatura em Python, guiadas pelo PEP 8, focam em legibilidade e consistência, usando **snake_case** (minúsculas com _) para funções, métodos e variáveis; **CamelCase** (maiúsculas no início de cada palavra) para classes; e **CAPITALIZED_WITH_UNDERSCORES** para constantes, evitando l, O, I e nomes confusos, enquanto nomes "privados" usam _ e "mágicos" __dunder__.

## Principais Convenções

**Variáveis e Funções/Métodos**: snake_case (letras minúsculas, palavras separadas por _) para clareza e legibilidade.

- Exemplo: nome_usuario, calcular_total().

**Classes**: CamelCase (CamelCase), com a primeira letra de cada palavra maiúscula.

- Exemplo: MinhaClasse, Pessoa.

**Constantes**: CAPITALIZED_WITH_UNDERSCORES (maiúsculas, palavras separadas por _) para constantes globais.

- Exemplo: MAX_TENTATIVAS, PI.

**Módulos e Pacotes**: Nomes curtos e em minúsculas.

- Exemplo: meu_modulo, utils.

## Convenções Especiais

- **_privado**: Um único sublinhado no início indica um membro "privado" (convenção, não regra forçada).
- **__dunder__**: Dois sublinhados no início e fim (métodos "mágicos") são reservados para funções especiais do Python (ex: __init__, __str__).
- **Evitar l, O, I**: Não use l (minúsculo L), O (maiúsculo O) ou I (maiúsculo I) como nomes únicos para evitar confusão com 1 e 0.
