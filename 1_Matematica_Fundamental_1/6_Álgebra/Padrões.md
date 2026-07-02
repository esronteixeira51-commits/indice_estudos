# Padrões

Um **padrão** é uma regularidade ou repetição observada em uma sequência, figura, estrutura ou processo. Reconhecer padrões é uma das habilidades fundamentais da álgebra e da matemática como um todo.

## Definição

Padrão é uma **regra** que permite prever o próximo elemento de uma sequência ou construir novos elementos a partir de um modelo.

## Tipos de Padrões

### 1. Padrões Numéricos

**Crescimento constante (aditivo):**

$$ 3, 7, 11, 15, 19, \ldots $$

Cada termo = anterior + 4

**Crescimento multiplicativo:**

$$ 2, 6, 18, 54, 162, \ldots $$

Cada termo = anterior × 3

**Padrão alternado:**

$$ 1, -1, 1, -1, 1, -1, \ldots $$

Sinal alterna: positivo, negativo, positivo, negativo...

**Padrão de repetição:**

$$ 1, 2, 3, 1, 2, 3, 1, 2, 3, \ldots $$

Ciclo de 3 termos.

### 2. Padrões Geométricos

**Figuras que crescem:**

```
Termo 1:  □           (1 quadrado)
Termo 2:  □□□         (3 quadrados)
Termo 3:  □□□□□       (5 quadrados)
Termo 4:  □□□□□□□     (7 quadrados)

Padrão: adicionar 2 quadrados a cada termo
Fórmula: a_n = 2n - 1
```

**Figuras aninhadas:**

```
Termo 1:  ○             (1 círculo)
Termo 2:  ◎             (círculo com ponto)
Termo 3:  ◎ ○           (círculo com ponto + círculo)
```

### 3. Padrões de Posição

Padrões em tabelas ou coordenadas:

| Posição (n) | Valor |
|-------------|-------|
| 1 | 4 |
| 2 | 7 |
| 3 | 10 |
| 4 | 13 |
| 5 | 16 |

Padrão: $a_n = 3n + 1$

## Como Identificar um Padrão

### Passo 1: Observe os primeiros termos

$$ 2, 5, 10, 17, 26, \ldots $$

### Passo 2: Calcule as diferenças entre termos consecutivos

$$ 5-2=3, \quad 10-5=5, \quad 17-10=7, \quad 26-17=9 $$

Diferenças: $3, 5, 7, 9$ → crescendo de 2 em 2 (diferença de segunda ordem constante)

### Passo 3: Relacione com posição

| n | a_n | Diferença |
|---|-----|-----------|
| 1 | 2 | - |
| 2 | 5 | +3 |
| 3 | 10 | +5 |
| 4 | 17 | +7 |
| 5 | 26 | +9 |

Observe: $a_n = n^2 + 1$

- $1^2 + 1 = 2$ ✓
- $2^2 + 1 = 5$ ✓
- $3^2 + 1 = 10$ ✓
- $4^2 + 1 = 17$ ✓
- $5^2 + 1 = 26$ ✓

**Padrão encontrado:** $a_n = n^2 + 1$

## Padrões na Vida Real

- **Música**: ritmos, escalas, acordes
- **Arte**: azulejos, mosaicos, mandalas
- **Natureza**: conchas em espiral, arranjo de folhas, cristais de neve
- **Calendário**: dias da semana se repetem a cada 7 dias
- **Trânsito**: semáforos, rotas de ônibus
- **Programação**: loops, arrays, estruturas de dados

## Padrões e Álgebra

O reconhecimento de padrões é o **primeiro passo** para criar expressões algébricas:

| Padrão verbal | Expressão algébrica |
|---------------|---------------------|
| "O dobro de um número" | $2n$ |
| "Um número mais 5" | $n + 5$ |
| "O quadrado de um número menos 3" | $n^2 - 3$ |
| "A soma de dois números consecutivos" | $n + (n+1) = 2n+1$ |

---
**Próximo:** [Regularidades](Regularidades.md)
