# Regra de Sinais

A **regra de sinais** é a base para todas as operações com números inteiros. Ela determina o sinal do resultado quando multiplicamos, dividimos, ou trabalhamos com potências de números negativos. Compreender essa regra é essencial para não cometer erros em expressões mais complexas.

## A Regra Fundamental

> **Sinais iguais = resultado positivo (+)**
> **Sinais diferentes = resultado negativo (−)**

### Multiplicação e Divisão

| Operação | Sinais | Resultado | Exemplo |
|----------|--------|-----------|---------|
| $(+a) \times (+b)$ | Iguais | $+$ | $5 \times 3 = 15$ |
| $(-a) \times (-b)$ | Iguais | $+$ | $(-5) \times (-3) = 15$ |
| $(+a) \times (-b)$ | Diferentes | $-$ | $5 \times (-3) = -15$ |
| $(-a) \times (+b)$ | Diferentes | $-$ | $(-5) \times 3 = -15$ |

> As mesmas regras valem para a **divisão**.

### Adição e Subtração

A regra de sinais para adição/subtração é diferente:

| Situação | Como resolver | Exemplo |
|----------|-------------|---------|
| Soma de positivos | Soma normal | $3 + 5 = 8$ |
| Soma de negativos | Soma e conserva o sinal negativo | $(-3) + (-5) = -8$ |
| Positivo + negativo | Subtração, sinal do maior | $7 + (-4) = 3$ |
| Positivo − negativo | Torna-se adição: $a - (-b) = a + b$ | $7 - (-4) = 11$ |
| Negativo − positivo | Torna-se adição: $-a - b = -(a + b)$ | $(-7) - 4 = -11$ |

> **Mnemônica para adição/subtração:**
> - "Mais com mais, mais" (soma de positivos)
> - "Menos com menos, menos" (soma de negativos)
> - "Mais com menos, sinal do maior" (sinais diferentes)
> - "Menos com menos vira mais" (subtrair negativo = adicionar positivo)

## Potências e Regra de Sinais

### Base Negativa

| Expoente | Resultado | Exemplo | Por quê? |
|----------|-----------|---------|----------|
| **Par** | Positivo | $(-2)^4 = +16$ | $(-2) \times (-2) \times (-2) \times (-2)$: 4 negativos (par) |
| **Ímpar** | Negativo | $(-2)^5 = -32$ | 5 negativos (ímpar) |

> **Regra:** $(-a)^n$:
> - $n$ par → positivo
> - $n$ ímpar → negativo

### Cuidado: Parênteses!

$$ (-2)^4 = (-2) \times (-2) \times (-2) \times (-2) = +16 $$
$$ -2^4 = -(2^4) = -16 $$

> **Sem parênteses**, o sinal negativo é aplicado **depois** da potência!

## Produto de Múltiplos Fatores

Conte o número de fatores negativos:
- **Par de negativos** → resultado positivo
- **Ímpar de negativos** → resultado negativo

### Exemplo

$$ (-2) \times (-3) \times (-4) \times (+5) \times (-1) \times (-6) $$

Negativos: $(-2), (-3), (-4), (-1), (-6)$ → **5 negativos** (ímpar)

Resultado: **negativo**

Valor absoluto: $2 \times 3 \times 4 \times 5 \times 1 \times 6 = 720$

Resultado final: **-720**

## Expressões com Parênteses e Sinais

### Ordem de Resolução

1. **Parênteses** (do mais interno para o mais externo)
2. **Potências e raízes**
3. **Multiplicação e divisão** (da esquerda para a direita)
4. **Adição e subtração** (da esquerda para a direita)

### Exemplo Passo a Passo

$$ (-3)^2 - 2 \times (-5) + (-8) \div (-2) - (-1)^3 $$

**Passo 1:** Potências
$$ (-3)^2 = +9 $$
$$ (-1)^3 = -1 $$

**Passo 2:** Multiplicação e divisão
$$ 2 \times (-5) = -10 $$
$$ (-8) \div (-2) = +4 $$

**Passo 3:** Substituição
$$ 9 - (-10) + 4 - (-1) $$

**Passo 4:** Simplificar sinais
$$ 9 + 10 + 4 + 1 = 24 $$

> **Resposta:** $24$

## Aplicações na Vida Real

- **Física:** forças opostas (tensão/compressão), cargas elétricas atrativas/repulsivas
- **Finanças:** multiplicação de taxas de juros negativas (deflação)
- **Jogos:** combos multiplicadores de dano (positivos e negativos)
- **Química:** produtos de reações com íons de cargas opostas
- **Engenharia:** cálculos estruturais com esforços de sentidos opostos
- **Meteorologia:** variações de pressão multiplicadas por área (força)
- **Economia:** elasticidade preço (multiplicação de variações percentuais)
- **Astronomia:** magnitude aparente de estrelas (logaritmo negativo)
- **Computação:** operações bit a bit, sinal de números, overflows
- **Estatística:** correlação negativa (multiplicação de desvios)

## Problemas

### Nível 1 — Básico

**1.** Determine o sinal do resultado: $(-3) \times (-7)$

**Resposta:** Positivo (dois negativos = sinais iguais = +)

**2.** Determine o sinal do resultado: $(-5) \times 8$

**Resposta:** Negativo (sinais diferentes = −)

**3.** Calcule: $(-2)^6$

Expoente par → positivo
$$ 2^6 = 64 $$

**Resposta:** $+64$ (ou 64)

**4.** Calcule: $(-2)^7$

Expoente ímpar → negativo
$$ 2^7 = 128 $$

**Resposta:** $-128$

**5.** Calcule: $-3^2$ (sem parênteses!)

$$ -3^2 = -(3^2) = -9 $$

**Resposta:** $-9$ (não é 9!)

### Nível 2 — Intermediário

**6.** Determine o sinal de $(-1) \times (-2) \times (-3) \times (-4) \times (-5) \times (-6)$ sem calcular o valor.

Negativos: 6 (par) → resultado positivo.

**Resposta:** Positivo.

**7.** Calcule: $-2^3 + (-2)^3$

$$ -2^3 = -(2^3) = -8 $$
$$ (-2)^3 = (-2) \times (-2) \times (-2) = -8 $$
$$ -8 + (-8) = -16 $$

**Resposta:** $-16$

**8.** Calcule: $(-1)^{100} + (-1)^{101} + (-1)^{102} + (-1)^{103}$

$$ (-1)^{100} = +1 \text{ (par)} $$
$$ (-1)^{101} = -1 \text{ (ímpar)} $$
$$ (-1)^{102} = +1 \text{ (par)} $$
$$ (-1)^{103} = -1 \text{ (ímpar)} $$

$$ 1 + (-1) + 1 + (-1) = 0 $$

**Resposta:** $0$

**9.** Se $a < 0$ e $b < 0$, qual o sinal de $a \times b$? E de $a + b$? E de $a - b$?

- $a \times b$: $(-) \times (-) = +$ → **positivo**
- $a + b$: $(-a) + (-b) = -(a + b)$ → **negativo**
- $a - b$: $(-a) - (-b) = -a + b = b - a$ (sinal depende de quem é maior em módulo)

**Resposta:** $a \times b$ = positivo; $a + b$ = negativo; $a - b$ = depende (se $|a| > |b|$, negativo; se $|b| > |a|$, positivo).

**10.** Determine o sinal do produto: $(-1) \times (-2) \times (-3) \times \ldots \times (-50)$.

São 50 fatores negativos (par) → resultado positivo.

**Resposta:** Positivo.

### Nível 3 — Desafio

**11.** Calcule: $(-2)^3 \times (-3)^2 \div (-6)^2 - (-1)^{50} + (-5)^0$

**Passo 1:** Potências
$$ (-2)^3 = -8 \text{ (ímpar)} $$
$$ (-3)^2 = 9 \text{ (par)} $$
$$ (-6)^2 = 36 \text{ (par)} $$
$$ (-1)^{50} = 1 \text{ (par)} $$
$$ (-5)^0 = 1 \text{ (qualquer número ≠ 0 elevado a 0 = 1)} $$

**Passo 2:** Multiplicação e divisão
$$ (-8) \times 9 = -72 $$
$$ (-72) \div 36 = -2 $$

**Passo 3:** Adição e subtração
$$ -2 - 1 + 1 = -2 $$

**Resposta:** $-2$

**12.** Para quais valores de $n$ (inteiro positivo) o resultado de $(-3)^n$ é positivo? E negativo?

- Positivo: quando $n$ é **par** (2, 4, 6, 8, ...)
- Negativo: quando $n$ é **ímpar** (1, 3, 5, 7, ...)

**Resposta:** Positivo para $n$ par; negativo para $n$ ímpar.

**13.** Simplifique: $\frac{(-a)^2 \times (-b)^3}{(-a)^3 \times (-b)^2}$ (assumindo $a, b > 0$)

$$ (-a)^2 = a^2 \text{ (par)} $$
$$ (-b)^3 = -b^3 \text{ (ímpar)} $$
$$ (-a)^3 = -a^3 \text{ (ímpar)} $$
$$ (-b)^2 = b^2 \text{ (par)} $$

$$ \frac{a^2 \times (-b^3)}{(-a^3) \times b^2} = \frac{-a^2 b^3}{-a^3 b^2} = \frac{a^2 b^3}{a^3 b^2} = \frac{b}{a} $$

**Resposta:** $\frac{b}{a}$

---
**Fim — Regra de Sinais**
