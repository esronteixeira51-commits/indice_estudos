# Antecessor

O **antecessor** de um número natural é o número que vem **imediatamente antes** dele na sequência dos números naturais. É o número que, adicionado de 1, resulta no número original.

## Definição

$$ \text{Antecessor}(n) = n - 1 $$

O antecessor é obtido subtraindo **1** do número.

## Exemplos

| Número | Antecessor | Cálculo |
|--------|------------|---------|
| 5 | 4 | 5 − 1 = 4 |
| 10 | 9 | 10 − 1 = 9 |
| 100 | 99 | 100 − 1 = 99 |
| 1.000 | 999 | 1.000 − 1 = 999 |
| 1 | 0 | 1 − 1 = 0 |

## O Zero e o Antecessor

O número **0** é o antecessor de **1**. No entanto, **0 não tem antecessor** no conjunto dos números naturais (pois não existe número natural antes de zero).

> **Conjunto dos naturais:** 0, 1, 2, 3, 4, ... (inclui zero)
> **Conjunto dos naturais não-nulos:** 1, 2, 3, 4, ... (não inclui zero)

## Antecessor na Reta Numérica

```
←──|──|──|──|──|──|──|──|──|──|──|──|──→
   0  1  2  3  4  5  6  7  8  9 10 11
         ↑  ↑
      antecessor de 5 = 4
```

## Antecessor de Números Pares e Ímpares

- Antecessor de número **par** é **ímpar**:
  - 8 → 7 (ímpar)
  - 20 → 19 (ímpar)

- Antecessor de número **ímpar** é **par**:
  - 7 → 6 (par)
  - 21 → 20 (par)

- Antecessor de **múltiplo de 10** termina em 9:
  - 10 → 9, 20 → 19, 100 → 99, 1.000 → 999

## Aplicações

- **Contagem regressiva:** 10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0!
- **Lançamento de foguete:** contagem regressiva
- **Sequências:** identificar padrões numéricos
- **Números de casa:** encontrar o vizinho anterior
- **Data anterior:** "ontem" é o antecessor de "hoje" no calendário

## Problemas

### Nível 1 — Básico

**1.** Qual é o antecessor de 15?

**Resposta:** 14.

**2.** Qual é o antecessor de 100?

**Resposta:** 99.

**3.** O antecessor de 7 é par ou ímpar?

**Resposta:** 6, que é par.

### Nível 2 — Intermediário

**4.** Se o antecessor de um número é 456, qual é o número?

**Resposta:** 456 + 1 = 457.

**5.** Qual é o antecessor do antecessor de 20?

**Resposta:** Antecessor de 20 = 19. Antecessor de 19 = 18.

**6.** O antecessor de um número par é sempre ímpar. Verdadeiro ou falso?

**Resposta:** Verdadeiro.

### Nível 3 — Desafio

**7.** Se A + B = 100 e A é o antecessor de B, quais são A e B?

*Resolução:*
$$ A = B - 1 $$
$$ (B - 1) + B = 100 $$
$$ 2B = 101 $$
$$ B = 50{,}5 $$

**Resposta:** Não existe solução com números naturais (a soma de dois números consecutivos é sempre ímpar: n + (n+1) = 2n+1).

**8.** O produto de um número e seu antecessor é 56. Qual é o número?

*Resolução:*
$$ n \times (n - 1) = 56 $$
$$ n^2 - n - 56 = 0 $$
$$ n = \frac{1 + \sqrt{1 + 224}}{2} = \frac{1 + 15}{2} = 8 $$

**Resposta:** 8 (8 × 7 = 56).

---
**Próximo:** [Sucessor](10_sucessor.md)
