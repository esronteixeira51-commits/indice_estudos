# Comparação e Ordenação de Inteiros

A **comparação** de números inteiros permite dizer se um número é maior, menor ou igual a outro. A **ordenação** organiza os números em ordem crescente ou decrescente. Na reta numérica, a ordem é natural: quanto mais à direita, maior o número.

## Definição

Para quaisquer números inteiros $a$ e $b$:

- $a > b$ (a maior que b): $a$ está à direita de $b$ na reta numérica
- $a < b$ (a menor que b): $a$ está à esquerda de $b$ na reta numérica
- $a = b$ (a igual a b): $a$ e $b$ ocupam o mesmo ponto na reta numérica
- $a \geq b$ (a maior ou igual a b): $a > b$ ou $a = b$
- $a \leq b$ (a menor ou igual a b): $a < b$ ou $a = b$
- $a \neq b$ (a diferente de b): $a$ não é igual a $b$

## Regras de Comparação

### 1. Positivos vs. Negativos

Qualquer número positivo é **maior** que qualquer número negativo (e que o zero):

$$ +1 > 0 > -1 $$
$$ +100 > -1.000.000 $$

### 2. Entre Positivos

Quanto maior o valor absoluto, maior o número:

$$ 5 > 3 \quad \text{porque} \quad 5 \text{ está à direita de } 3 $$

### 3. Entre Negativos

Quanto maior o valor absoluto, **menor** o número:

$$ -5 < -3 \quad \text{porque} \quad -5 \text{ está à esquerda de } -3 $$

> **Regra mnemônica:** "O mais frio é o menor." $-10°C < -5°C$ (mais frio = menor número).

### 4. Zero

Zero é maior que todos os negativos e menor que todos os positivos:

$$ -3 < 0 < +2 $$

## Ordenação Crescente e Decrescente

### Crescente (do menor para o maior)

$$ -7 < -4 < -1 < 0 < +2 < +5 < +10 $$

### Decrescente (do maior para o menor)

$$ +10 > +5 > +2 > 0 > -1 > -4 > -7 $$

## Exemplos

### Exemplo 1

Ordene em ordem crescente: $-5, +3, -8, 0, +1, -2$

$$ -8 < -5 < -2 < 0 < +1 < +3 $$

### Exemplo 2

Compare: $-15$ e $-7$

$$ -15 < -7 \quad \text{(porque 15 > 7, e são negativos, inverte!)} $$

### Exemplo 3

Qual é o maior inteiro menor que $-2{,}3$? E o menor inteiro maior que $-2{,}3$?

$$ \text{Maior inteiro } < -2{,}3: -3 $$
$$ \text{Menor inteiro } > -2{,}3: -2 $$

### Exemplo 4

Escreva os inteiros entre $-4$ e $+3$ (inclusive):

$$ -4, -3, -2, -1, 0, +1, +2, +3 $$

Total: 8 números.

### Exemplo 5

Se $x$ é um inteiro tal que $-5 < x \leq 2$, quais são os valores possíveis de $x$?

$$ x \in \{-4, -3, -2, -1, 0, +1, +2\} $$

Note que $-5$ está **excluído** ($<$) e $+2$ está **incluído** ($\leq$).

## Aplicações na Vida Real

- **Temperatura:** ordenar cidades do mais frio ao mais quente
- **Finanças:** ordenar saldos de contas (mais negativo = mais endividado)
- **Esportes:** classificação por saldo de gols (maior = melhor)
- **Geografia:** profundidades (mais negativo = mais fundo)
- **Elevações:** ordenar picos de montanhas (mais alto = maior número positivo)
- **História:** ordenar eventos cronológicos (anos a.C. = negativos)
- **Jogos:** rankings, pontuações, níveis de dificuldade
- **Física:** potenciais elétricos, níveis de energia
- **Química:** pH (menor = mais ácido, maior = mais básico, mas escala logarítmica)
- **Astronomia:** magnitudes estelares (negativas = mais brilhantes)

## Problemas

### Nível 1 — Básico

**1.** Ordene em ordem crescente: $-9, +4, -3, 0, +7, -1$.

**Resposta:** $-9 < -3 < -1 < 0 < +4 < +7$

**2.** Ordene em ordem decrescente: $-2, -10, +5, 0, -5, +8$.

**Resposta:** $+8 > +5 > 0 > -2 > -5 > -10$

**3.** Compare usando $<$, $>$ ou $=$: $-12$ e $-8$.

**Resposta:** $-12 < -8$

**4.** Qual é o maior número inteiro negativo? (O maior dentre os negativos)

**Resposta:** $-1$ (está mais próximo do zero)

**5.** Quais inteiros $x$ satisfazem $-3 \leq x < 2$?

**Resposta:** $x \in \{-3, -2, -1, 0, +1\}$ (5 valores)

### Nível 2 — Intermediário

**6.** Dado o conjunto $A = \{-7, -2, 0, +3, -5, +8, -1\}$:
  a) Qual o maior elemento?
  b) Qual o menor elemento?
  c) Ordene em ordem crescente.

**Resposta:**
a) $+8$
b) $-7$
c) $-7 < -5 < -2 < -1 < 0 < +3 < +8$

**7.** Se $x$ é um inteiro tal que $-4 < x \leq 3$ e $y$ é um inteiro tal que $-2 \leq y < 5$, quantos pares $(x, y)$ são possíveis?

$$ x \in \{-3, -2, -1, 0, 1, 2, 3\} \quad (7 \text{ valores}) $$
$$ y \in \{-2, -1, 0, 1, 2, 3, 4\} \quad (7 \text{ valores}) $$
$$ \text{Pares} = 7 \times 7 = 49 $$

**Resposta:** 49 pares possíveis.

**8.** Qual o maior inteiro $n$ tal que $n < -3{,}14$?

$$ n = -4 \quad (-4 < -3{,}14 \text{ e } -3 > -3{,}14) $$

**Resposta:** $-4$

**9.** Três cidades têm temperaturas: $A = -5°C$, $B = +2°C$, $C = -8°C$. Ordene da mais fria para a mais quente.

**Resposta:** $C < A < B$ (ou $-8°C < -5°C < +2°C$)

**10.** Se $a < b$ e $b < c$, então $a < c$ (propriedade transitiva). Verifique com $a = -7$, $b = -2$, $c = +5$.

$$ -7 < -2 \quad \checkmark $$
$$ -2 < +5 \quad \checkmark $$
$$ -7 < +5 \quad \checkmark $$

**Resposta:** Verificada: $-7 < -2 < +5$.

### Nível 3 — Desafio

**11.** Quantos inteiros $n$ satisfazem $-100 < n < 100$ e $n$ é par?

Inteiros entre $-100$ e $100$: $-99, -98, \ldots, -2, 0, 2, \ldots, 98, 99$

Pares: $-98, -96, \ldots, -2, 0, 2, \ldots, 96, 98$

De $-98$ a $98$ em passos de 2:

$$ \frac{98 - (-98)}{2} + 1 = \frac{196}{2} + 1 = 98 + 1 = 99 $$

**Resposta:** 99 números pares.

**12.** Se $x$ é um inteiro e $-5 < x \leq 4$, qual o valor de $|x|$ para cada $x$ possível? Qual o maior valor de $|x|$?

$$ x \in \{-4, -3, -2, -1, 0, 1, 2, 3, 4\} $$
$$ |x| \in \{4, 3, 2, 1, 0, 1, 2, 3, 4\} $$

Maior valor de $|x|$: $4$ (ocorre em $x = -4$ e $x = +4$)

**Resposta:** Maior valor de $|x|$ é $4$.

**13.** Se $a$, $b$ e $c$ são inteiros tais que $a < b < c$ e $a + b + c = 0$, com $a = -5$, quantos valores possíveis existem para $b$ e $c$?

$$ -5 + b + c = 0 \implies b + c = 5 $$

Com $-5 < b < c$:
- $b = -4 \implies c = 9$ ($-4 < 9$ ✓)
- $b = -3 \implies c = 8$ ✓
- $b = -2 \implies c = 7$ ✓
- $b = -1 \implies c = 6$ ✓
- $b = 0 \implies c = 5$ ✓
- $b = 1 \implies c = 4$ ✓
- $b = 2 \implies c = 3$ ✓
- $b = 3 \implies c = 2$ (mas $3 < 2$ é falso ✗)

Total: 7 pares $(b, c)$.

**Resposta:** 7 valores possíveis para $(b, c)$: $(-4, 9), (-3, 8), (-2, 7), (-1, 6), (0, 5), (1, 4), (2, 3)$.

---
**Fim — Comparação e Ordenação de Inteiros**
