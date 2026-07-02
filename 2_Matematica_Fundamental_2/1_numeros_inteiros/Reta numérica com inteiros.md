# Reta Numérica com Inteiros

A **reta numérica** é uma representação gráfica dos números inteiros ao longo de uma linha. Ela permite visualizar a ordenação, comparação e distância entre números de forma intuitiva.

## Definição

A reta numérica dos inteiros é uma linha horizontal (ou vertical) onde:
- Os números crescem da **esquerda para a direita**
- O **zero** está no centro (ou em algum ponto de referência)
- Os **positivos** estão à direita do zero
- Os **negativos** estão à esquerda do zero

```
<---|----|----|----|----|----|----|----|----|----|----|--->
   -5   -4   -3   -2   -1    0   +1   +2   +3   +4   +5
```

## Eixo Horizontal e Vertical

### Eixo Horizontal (X)

```
    -5  -4  -3  -2  -1   0   1   2   3   4   5
<---|---|---|---|---|---|---|---|---|---|---|--->
```
- Direita = positivo
- Esquerda = negativo

### Eixo Vertical (Y)

```
     +5 |
     +4 |
     +3 |
     +2 |
     +1 |
      0 +------------------
     -1 |
     -2 |
     -3 |
     -4 |
     -5 |
```
- Cima = positivo
- Baixo = negativo

## Propriedades na Reta Numérica

### 1. Ordem Crescente

$$ a < b \iff a \text{ está à esquerda de } b \text{ na reta numérica} $$

### 2. Distância até o Zero (Valor Absoluto)

A distância de um número ao zero é seu **valor absoluto** (módulo):

$$ |-5| = 5 \quad |+3| = 3 \quad |0| = 0 $$

### 3. Distância entre Dois Números

$$ d(a, b) = |a - b| = |b - a| $$

### 4. Simetria

Para cada número positivo $n$, existe um número negativo $-n$ à mesma distância do zero.

$$ -(-3) = 3 $$

## Operações na Reta Numérica

### Adição

- **Adicionar positivo:** andar para a **direita**
- **Adicionar negativo:** andar para a **esquerda**

**Exemplo:** $2 + (-5)$
- Comece em 2
- Ande 5 unidades para a esquerda
- Resultado: $-3$

### Subtração

- **Subtrair positivo:** andar para a **esquerda**
- **Subtrair negativo:** andar para a **direita**

**Exemplo:** $-3 - (-4)$
- Comece em $-3$
- Ande 4 unidades para a direita (subtrair negativo = adicionar positivo)
- Resultado: $+1$

### Multiplicação por Escalar

- **Multiplicar por positivo:** "esticar" na mesma direção
- **Multiplicar por negativo:** "esticar" na direção oposta (refletir pelo zero)

## Exemplos

### Exemplo 1

Represente na reta numérica: $-4, -1, 0, 2, 5$

```
<---|----|----|----|----|----|----|----|----|----|----|--->
   -5   -4   -3   -2   -1    0   +1   +2   +3   +4   +5
         ^              ^    ^              ^              ^
```

Ordem crescente: $-4 < -1 < 0 < 2 < 5$

### Exemplo 2

Calcule a distância entre $-3$ e $+4$:

$$ d(-3, 4) = |-3 - 4| = |-7| = 7 \text{ unidades} $$

Ou contando na reta: de $-3$ até $0$ são 3, de $0$ até $4$ são 4. Total: $3 + 4 = 7$.

### Exemplo 3

O oposto de $-5$ é $+5$. Na reta numérica:

```
<---|----|----|----|----|----|----|----|----|----|----|--->
   -6   -5   -4   -3   -2   -1    0   +1   +2   +3   +4   +5   +6
         ^                                  ^              ^
         |<------------ 5 unidades --------->|
              |<------------ 5 unidades --------->|
```

Ambos estão a 5 unidades de distância do zero, em lados opostos.

### Exemplo 4

Se $x$ está entre $-3$ e $2$ na reta numérica, quais são os possíveis valores inteiros de $x$?

$$ x \in \{-2, -1, 0, 1\} $$

### Exemplo 5

Se $a$ é um número à esquerda de $-2$ e $b$ é à direita de $+3$, qual a menor distância possível entre $a$ e $b$ (se ambos são inteiros)?

- $a$ mais à direita possível: $-3$ (ou $-2$ se $a < -2$, então $a \leq -3$)
- $b$ mais à esquerda possível: $+4$ (ou $+3$ se $b > 3$, então $b \geq 4$)

Menor distância: $|-3 - 4| = 7$

## Aplicações na Vida Real

- **GPS e mapas:** coordenadas em retas numéricas (latitude e longitude)
- **Elevadores:** painel com subsolos negativos e andares positivos
- **Jogos:** posicionamento de personagens em eixos 1D, 2D, 3D
- **Física:** movimento unidimensional (movimento retilíneo)
- **Termômetros:** escala de temperatura como reta vertical
- **Economia:** linha do tempo de saldos bancários
- **História:** linha do tempo com anos a.C. (negativos) e d.C. (positivos)
- **Engenharia:** deslocamentos, deformações (tensão positiva, compressão negativa)
- **Música:** intervalos (subir = positivo, descer = negativo)
- **Pintura:** perspectiva, posicionamento em canvas digital

## Problemas

### Nível 1 — Básico

**1.** Represente na reta numérica os números: $-6, -2, 0, 3, 7$.

**Resposta:** (representação gráfica mental: -6, -2, 0, 3, 7 marcados na reta)

**2.** Qual número está mais distante do zero: $-8$ ou $+5$?

$$ |-8| = 8 \quad |+5| = 5 $$

**Resposta:** $-8$ (distância 8 vs. 5).

**3.** Se um ponto está a 3 unidades de distância de $-1$ na reta numérica, quais são seus possíveis valores?

$$ x = -1 + 3 = +2 \quad \text{ou} \quad x = -1 - 3 = -4 $$

**Resposta:** $+2$ ou $-4$.

**4.** Ordene os números usando a reta numérica: $-5, +3, -1, 0, -8, +2$.

**Resposta:** $-8 < -5 < -1 < 0 < +2 < +3$.

**5.** O oposto de $-7$ é $+7$. Qual a distância entre $-7$ e seu oposto?

$$ |-7 - 7| = |-14| = 14 \text{ unidades} $$

**Resposta:** 14 unidades.

### Nível 2 — Intermediário

**6.** Na reta numérica, um ponto $P$ está entre $-5$ e $3$. Se $P$ está a mesma distância de $-5$ e de $3$, qual o valor de $P$?

$$ P = \frac{-5 + 3}{2} = \frac{-2}{2} = -1 $$

**Resposta:** $P = -1$ (ponto médio).

**7.** Um ponto $A$ está em $-4$ e outro ponto $B$ está em $+6$. Um ponto $C$ está entre $A$ e $B$ e divide o segmento na razão 2:3 (mais próximo de $A$). Qual a coordenada de $C$?

$$ \text{Distância total} = 6 - (-4) = 10 $$
$$ \text{De } A \text{ até } C: \frac{2}{5} \times 10 = 4 $$
$$ C = -4 + 4 = 0 $$

**Resposta:** $C = 0$.

**8.** Se $x$ está à direita de $-3$ e à esquerda de $+2$ na reta numérica, e $x$ é inteiro, quantos valores possíveis $x$ pode assumir?

$$ x \in \{-2, -1, 0, 1\} $$
$$ \text{Total} = 4 \text{ valores} $$

**Resposta:** 4 valores ($-2, -1, 0, 1$).

**9.** Dois pontos $A$ e $B$ na reta numérica são tais que $A < B$ e a distância entre eles é 12. Se $A$ está a 5 unidades do zero, quais são os possíveis valores de $B$?

- Caso 1: $A = -5$ (à esquerda do zero)
  $$ B = -5 + 12 = +7 $$
- Caso 2: $A = +5$ (à direita do zero)
  $$ B = 5 + 12 = +17 $$

**Resposta:** $B = +7$ (se $A = -5$) ou $B = +17$ (se $A = +5$).

**10.** Em uma reta numérica vertical, um pássaro está em $+20$ m e um peixe em $-8$ m. Qual a distância vertical entre eles?

$$ |20 - (-8)| = 28 \text{ m} $$

**Resposta:** 28 m.

### Nível 3 — Desafio

**11.** Na reta numérica, três pontos $A$, $B$ e $C$ estão tais que $A < B < C$. A distância $AB = 5$ e a distância $BC = 7$. Se $A$ está em $-4$, onde está $C$?

$$ B = -4 + 5 = +1 $$
$$ C = 1 + 7 = +8 $$

**Resposta:** $C = +8$.

**12.** Quantos números inteiros estão a uma distância menor ou igual a 4 de $-2$ na reta numérica?

$$ |-2 - x| \leq 4 \implies -4 \leq -2 - x \leq 4 $$
$$ -2 \leq x \leq 6 $$

Inteiros: $-2, -1, 0, 1, 2, 3, 4, 5, 6$
$$ \text{Total} = 9 \text{ números} $$

**Resposta:** 9 números inteiros.

**13.** Um ponto se move na reta numérica começando em $+3$. Ele dá um salto de $-7$ (para a esquerda), depois um salto de $+4$, depois de $-2$, e finalmente de $+9$. Onde ele para?

$$ 3 - 7 + 4 - 2 + 9 = 7 $$

**Resposta:** Para em $+7$.

---
**Fim — Reta Numérica com Inteiros**
