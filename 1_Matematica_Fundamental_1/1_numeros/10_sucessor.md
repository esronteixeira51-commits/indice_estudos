# Sucessor

O **sucessor** de um número natural é o número que vem **imediatamente depois** dele na sequência dos números naturais. É o número que, subtraído de 1, resulta no número original.

## Definição

$$ \text{Sucessor}(n) = n + 1 $$

O sucessor é obtido adicionando **1** ao número.

## Exemplos

| Número | Sucessor | Cálculo |
|--------|----------|---------|
| 5 | 6 | 5 + 1 = 6 |
| 10 | 11 | 10 + 1 = 11 |
| 99 | 100 | 99 + 1 = 100 |
| 999 | 1.000 | 999 + 1 = 1.000 |
| 0 | 1 | 0 + 1 = 1 |
| 1.999.999 | 2.000.000 | 1.999.999 + 1 = 2.000.000 |

## Sucessor na Reta Numérica

```
←──|──|──|──|──|──|──|──|──|──|──|──|──→
   0  1  2  3  4  5  6  7  8  9 10 11
         ↑  ↑
      sucessor de 4 = 5
```

## Relação entre Antecessor e Sucessor

- O sucessor de **n** é **n + 1**
- O antecessor de **n** é **n − 1**
- O sucessor do antecessor de **n** é **n** (desde que n > 0)
- O antecessor do sucessor de **n** é **n**

$$ \text{Sucessor}(\text{Antecessor}(n)) = n \quad (n > 0) $$
$$ \text{Antecessor}(\text{Sucessor}(n)) = n $$

## Sucessor de Números Pares e Ímpares

- Sucessor de número **par** é **ímpar**:
  - 8 → 9 (ímpar)
  - 20 → 21 (ímpar)

- Sucessor de número **ímpar** é **par**:
  - 7 → 8 (par)
  - 21 → 22 (par)

- Sucessor de número terminado em **9** muda a casa:
  - 9 → 10 (muda de unidade para dezena)
  - 19 → 20 (muda dezena)
  - 99 → 100 (muda centena)
  - 999 → 1.000 (muda milhar)

## Aplicações

- **Contagem:** 1, 2, 3, 4, 5... cada número é o sucessor do anterior
- **Sequências:** progressões aritméticas de razão 1
- **Paginação:** próxima página é o sucessor da atual
- **Datas:** amanhã é o sucessor de hoje no calendário
- **Fila:** a próxima pessoa é a "sucessora" da atual

## Problemas

### Nível 1 — Básico

**1.** Qual é o sucessor de 23?

**Resposta:** 24.

**2.** Qual é o sucessor de 99?

**Resposta:** 100.

**3.** O sucessor de 6 é par ou ímpar?

**Resposta:** 7, que é ímpar.

### Nível 2 — Intermediário

**4.** Se o sucessor de um número é 501, qual é o número?

**Resposta:** 500.

**5.** Qual é o sucessor do sucessor de 45?

**Resposta:** Sucessor de 45 = 46. Sucessor de 46 = 47.

**6.** O sucessor de um número ímpar é sempre par. Verdadeiro ou falso?

**Resposta:** Verdadeiro.

### Nível 3 — Desafio

**7.** Se A + B = 101 e B é o sucessor de A, quais são A e B?

*Resolução:*
$$ B = A + 1 $$
$$ A + (A + 1) = 101 $$
$$ 2A + 1 = 101 $$
$$ 2A = 100 $$
$$ A = 50 $$
$$ B = 51 $$

**Resposta:** A = 50, B = 51.

**8.** O quadrado de um número é igual ao quadrado de seu sucessor menos 21. Qual é o número?

*Resolução:*
$$ n^2 = (n+1)^2 - 21 $$
$$ n^2 = n^2 + 2n + 1 - 21 $$
$$ 0 = 2n - 20 $$
$$ 2n = 20 $$
$$ n = 10 $$

Verificação: 10² = 100. 11² = 121. 121 − 21 = 100. ✓

**Resposta:** 10.

---
**Próximo:** [Decomposição](11_decomposição.md)
