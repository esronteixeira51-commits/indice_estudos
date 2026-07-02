# Algoritmos — Ordem das Operações

## Algoritmo de Resolução Passo a Passo

Dada uma expressão: resolva **uma operação por vez**, reescrevendo a expressão a cada passo.

**Exemplo:** $20 - 3 \times 2^2 + (15 - 7) \div 4$

### Passo 1: Parênteses

$$ 20 - 3 \times 2^2 + 8 \div 4 $$

### Passo 2: Potências

$$ 20 - 3 \times 4 + 8 \div 4 $$

### Passo 3: Multiplicações e Divisões (esquerda → direita)

$$ 20 - 12 + 2 $$

### Passo 4: Adições e Subtrações (esquerda → direita)

$$ 8 + 2 = 10 $$

**Resultado:** $10$

## Técnica de Sublinhado

Sublinhe cada operação conforme a resolve:

$$ 20 - \underline{3 \times \underline{2^2}} + \underline{(15 - 7)} \div 4 $$
$$ 20 - \underline{3 \times 4} + \underline{8 \div 4} $$
$$ \underline{20 - 12} + 2 $$
$$ \underline{8 + 2} = 10 $$

## Dicas
- Nunca faça duas operações de prioridades diferentes num único passo.
- Rescreva a expressão completa a cada passo.
- Use parênteses para deixar claro o que está resolvendo.

---
**Próximo:** [Problemas](Problemas.md)
