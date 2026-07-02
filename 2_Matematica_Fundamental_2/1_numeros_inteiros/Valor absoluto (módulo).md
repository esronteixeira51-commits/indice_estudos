# Valor Absoluto (Módulo)

O **valor absoluto** (ou **módulo**) de um número inteiro é sua distância até o zero na reta numérica, independentemente de seu sinal. Ele sempre resulta em um valor não negativo.

## Definição

$$ |x| = \begin{cases} x, & \text{se } x \geq 0 \\ -x, & \text{se } x < 0 \end{cases} $$

Em palavras: o valor absoluto "tira" o sinal do número, deixando apenas sua magnitude.

## Propriedades

### 1. Não Negatividade

$$ |x| \geq 0 \text{ para todo } x \in \mathbb{Z} $$

$$ |x| = 0 \iff x = 0 $$

### 2. Simetria

$$ |-x| = |x| $$

### 3. Multiplicativa

$$ |x \cdot y| = |x| \cdot |y| $$

### 4. Divisória (para $y \neq 0$)

$$ \left|\frac{x}{y}\right| = \frac{|x|}{|y|} $$

### 5. Desigualdade Triangular

$$ |x + y| \leq |x| + |y| $$

$$ |x - y| \geq ||x| - |y|| $$

### 6. Quadrado e Raiz

$$ |x|^2 = x^2 $$

$$ \sqrt{x^2} = |x| $$

## Exemplos

### Exemplo 1

$$ |+7| = 7 $$
$$ |-7| = 7 $$
$$ |0| = 0 $$

### Exemplo 2

$$ |3 - 8| = |-5| = 5 $$
$$ |8 - 3| = |5| = 5 $$

> **A distância é simétrica!** $|a - b| = |b - a|$.

### Exemplo 3

$$ |(-4) \times 3| = |-12| = 12 $$
$$ |-4| \times |3| = 4 \times 3 = 12 $$

Verifica-se a propriedade multiplicativa.

### Exemplo 4

$$ |2 + (-5)| = |-3| = 3 $$
$$ |2| + |-5| = 2 + 5 = 7 $$

Note que $3 \leq 7$, confirmando a desigualdade triangular: $|x + y| \leq |x| + |y|$.

### Exemplo 5

$$ \sqrt{(-5)^2} = \sqrt{25} = 5 = |-5| $$

> **Cuidado:** $\sqrt{x^2} = |x|$, não simplesmente $x$! $\sqrt{(-5)^2} \neq -5$.

## Equações com Módulo

### Tipo 1: $|x| = a$ (com $a > 0$)

$$ x = a \quad \text{ou} \quad x = -a $$

**Exemplo:** $|x| = 5$
$$ x = 5 \quad \text{ou} \quad x = -5 $$

### Tipo 2: $|x| = a$ (com $a = 0$)

$$ x = 0 $$

### Tipo 3: $|x| = a$ (com $a < 0$)

$$ \text{Sem solução (impossível)} $$

> **O valor absoluto nunca é negativo!**

### Tipo 4: $|x - a| = b$

$$ x - a = b \quad \text{ou} \quad x - a = -b $$
$$ x = a + b \quad \text{ou} \quad x = a - b $$

**Exemplo:** $|x - 3| = 4$
$$ x - 3 = 4 \implies x = 7 $$
$$ x - 3 = -4 \implies x = -1 $$

## Inequações com Módulo

### Tipo 1: $|x| < a$ (com $a > 0$)

$$ -a < x < a $$

**Exemplo:** $|x| < 3$
$$ -3 < x < 3 $$

### Tipo 2: $|x| > a$ (com $a > 0$)

$$ x < -a \quad \text{ou} \quad x > a $$

**Exemplo:** $|x| > 2$
$$ x < -2 \quad \text{ou} \quad x > 2 $$

### Tipo 3: $|x - a| < b$

$$ a - b < x < a + b $$

**Exemplo:** $|x - 5| < 2$
$$ 5 - 2 < x < 5 + 2 $$
$$ 3 < x < 7 $$

## Aplicações na Vida Real

- **Distância:** $|a - b|$ = distância entre $a$ e $b$ na reta numérica
- **Erro e incerteza:** $|valor_{medido} - valor_{real}|$ = erro absoluto
- **Física:** deslocamento (com sinal) vs. distância percorrida (sem sinal)
- **Economia:** variação absoluta de preços, diferença de cotações
- **Engenharia:** tolerância em peças mecânicas (±0,5 mm = $|x - nominal| \leq 0{,}5$)
- **Estatística:** desvio absoluto, erro médio absoluto
- **Geografia:** diferença de altitude, profundidade (sempre positiva)
- **Programação:** função `abs()` em linguagens de código
- **Jogos:** dano (sempre positivo), cooldown, delays
- **Música:** intervalo musical (distância entre notas, independente da direção)

## Problemas

### Nível 1 — Básico

**1.** Calcule: $|+9|$, $|-9|$, $|0|$, $|-15|$, $|+100|$.

**Resposta:** $9$, $9$, $0$, $15$, $100$.

**2.** Se $x = -4$, calcule $|x|$, $|x + 3|$, $|2x|$.

$$ |x| = |-4| = 4 $$
$$ |x + 3| = |-4 + 3| = |-1| = 1 $$
$$ |2x| = |2 \times (-4)| = |-8| = 8 $$

**Resposta:** 4, 1, 8.

**3.** Resolva: $|x| = 6$

$$ x = 6 \quad \text{ou} \quad x = -6 $$

**Resposta:** $x = 6$ ou $x = -6$.

**4.** Resolva: $|x - 2| = 5$

$$ x - 2 = 5 \implies x = 7 $$
$$ x - 2 = -5 \implies x = -3 $$

**Resposta:** $x = 7$ ou $x = -3$.

**5.** A que distância de $-3$ está o número $+8$ na reta numérica?

$$ |8 - (-3)| = |11| = 11 $$

**Resposta:** 11 unidades.

### Nível 2 — Intermediário

**6.** Resolva: $|2x - 1| = 7$

$$ 2x - 1 = 7 \implies 2x = 8 \implies x = 4 $$
$$ 2x - 1 = -7 \implies 2x = -6 \implies x = -3 $$

**Resposta:** $x = 4$ ou $x = -3$.

**7.** Resolva: $|x| < 4$ (inteiros)

$$ -4 < x < 4 $$
$$ x \in \{-3, -2, -1, 0, 1, 2, 3\} $$

**Resposta:** $-3, -2, -1, 0, 1, 2, 3$ (7 números inteiros).

**8.** Resolva: $|x + 3| \leq 2$ (inteiros)

$$ -2 \leq x + 3 \leq 2 $$
$$ -5 \leq x \leq -1 $$
$$ x \in \{-5, -4, -3, -2, -1\} $$

**Resposta:** $-5, -4, -3, -2, -1$ (5 números inteiros).

**9.** Se $|x| = 3$ e $|y| = 5$, quais são os possíveis valores de $|x + y|$?

- $x = 3, y = 5$: $|3 + 5| = 8$
- $x = 3, y = -5$: $|3 - 5| = 2$
- $x = -3, y = 5$: $|-3 + 5| = 2$
- $x = -3, y = -5$: $|-3 - 5| = 8$

**Resposta:** $|x + y|$ pode ser $2$ ou $8$.

**10.** Verifique a desigualdade triangular para $x = -4$ e $y = 7$:

$$ |x + y| = |-4 + 7| = |3| = 3 $$
$$ |x| + |y| = 4 + 7 = 11 $$
$$ 3 \leq 11 \quad \checkmark $$

**Resposta:** Verificada: $3 \leq 11$.

### Nível 3 — Desafio

**11.** Resolva: $|x - 1| + |x + 2| = 5$

Precisamos analisar os intervalos:

- **Caso 1:** $x < -2$
  $$ -(x - 1) - (x + 2) = 5 $$
  $$ -x + 1 - x - 2 = 5 $$
  $$ -2x - 1 = 5 \implies -2x = 6 \implies x = -3 $$
  Verificação: $-3 < -2$ ✓

- **Caso 2:** $-2 \leq x < 1$
  $$ -(x - 1) + (x + 2) = 5 $$
  $$ -x + 1 + x + 2 = 5 $$
  $$ 3 = 5 \text{ (impossível!)} $$

- **Caso 3:** $x \geq 1$
  $$ (x - 1) + (x + 2) = 5 $$
  $$ 2x + 1 = 5 \implies 2x = 4 \implies x = 2 $$
  Verificação: $2 \geq 1$ ✓

**Resposta:** $x = -3$ ou $x = 2$.

**12.** Quantos números inteiros satisfazem $|x - 5| + |x + 3| = 8$?

Análise dos intervalos:

- **Caso 1:** $x < -3$
  $$ -(x - 5) - (x + 3) = 8 $$
  $$ -x + 5 - x - 3 = 8 $$
  $$ -2x + 2 = 8 \implies -2x = 6 \implies x = -3 $$
  Mas $x < -3$, então $x = -3$ não é solução neste caso (verificamos: $x = -3$ é o limite).

- **Caso 2:** $-3 \leq x \leq 5$
  $$ -(x - 5) + (x + 3) = 8 $$
  $$ -x + 5 + x + 3 = 8 $$
  $$ 8 = 8 \text{ (sempre verdade!)} $$
  Todos os inteiros neste intervalo são solução: $-3, -2, -1, 0, 1, 2, 3, 4, 5$ (9 valores).

- **Caso 3:** $x > 5$
  $$ (x - 5) + (x + 3) = 8 $$
  $$ 2x - 2 = 8 \implies 2x = 10 \implies x = 5 $$
  Mas $x > 5$, então não é solução neste caso.

**Resposta:** 9 números inteiros: $-3, -2, -1, 0, 1, 2, 3, 4, 5$.

**13.** Se $|x| < 3$ e $|y| < 2$, qual o maior valor possível de $|x + y|$? E o menor?

Pela desigualdade triangular:
$$ |x + y| \leq |x| + |y| < 3 + 2 = 5 $$

Maior valor possível (limite): próximo de 5 (ex: $x = 2{,}9, y = 1{,}9$ → $|x + y| = 4{,}8$; ou $x = -2{,}9, y = -1{,}9$ → $|x + y| = 4{,}8$).

Maior valor **inteiro**: $x = 2, y = 1$ → $|2 + 1| = 3$... mas podemos chegar mais perto: $x = 2, y = 1$ não é o máximo. Com $x = 2, y = 1$ → 3. Mas $x = 2, y = 1{,}9$ não é inteiro. Inteiros: $x = 2, y = 1$ → 3. Ou $x = -2, y = -1$ → 3.

Espera, se $x$ e $y$ são inteiros: $x \in \{-2, -1, 0, 1, 2\}$, $y \in \{-1, 0, 1\}$.
Maior $|x + y|$: $x = 2, y = 1$ → $|3| = 3$ ou $x = -2, y = -1$ → $|-3| = 3$.
Menor $|x + y|$: $x = 0, y = 0$ → $|0| = 0$.

**Resposta:** Se inteiros: maior = 3, menor = 0. Se reais: menor = 0 (quando $x = -y$), maior tende a 5 (mas nunca alcança se $|x| < 3$ e $|y| < 2$ estritos).

---
**Fim — Valor Absoluto (Módulo)**
