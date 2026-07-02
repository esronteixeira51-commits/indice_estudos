# Função Quadrática (y = ax² + bx + c)

A **função quadrática** (ou função do 2º grau) é uma função da forma $f(x) = ax^2 + bx + c$, com $a \neq 0$. Seu gráfico é uma **parábola**, uma das curvas mais importantes da matemática, aparecendo em trajetórias de projéteis, refletores de antenas, pontes arco e otimizações de lucro.

## Definição

$$ f(x) = ax^2 + bx + c \quad \text{com} \quad a \neq 0 $$

Onde:
- $a$ = coeficiente de $x^2$ (determina a concavidade)
- $b$ = coeficiente de $x$ (determina a posição do eixo de simetria)
- $c$ = termo independente (intercepto com o eixo $y$)

## Gráfico: A Parábola

### Concavidade

- $a > 0$: parábola com **concavidade para cima** (∪) — tem ponto **mínimo**
- $a < 0$: parábola com **concavidade para baixo** (∩) — tem ponto **máximo**

### Vértice

O vértice é o ponto de máximo (se $a < 0$) ou mínimo (se $a > 0$) da parábola.

$$ x_v = -\frac{b}{2a} \quad \text{e} \quad y_v = f(x_v) = -\frac{\Delta}{4a} $$

Onde $\Delta = b^2 - 4ac$.

### Eixo de Simetria

A reta vertical $x = -\frac{b}{2a}$ é o eixo de simetria da parábola.

### Raízes (Zeros)

$$ x = \frac{-b \pm \sqrt{\Delta}}{2a} $$

- $\Delta > 0$: duas raízes reais distintas (parábola cruza o eixo x em 2 pontos)
- $\Delta = 0$: uma raiz real dupla (parábola tangencia o eixo x)
- $\Delta < 0$: nenhuma raiz real (parábola não cruza o eixo x)

## Forma Canônica (Forma do Vértice)

Completando o quadrado:

$$ f(x) = a(x - x_v)^2 + y_v $$

$$ f(x) = a\left(x + \frac{b}{2a}\right)^2 - \frac{\Delta}{4a} $$

Esta forma facilita identificar o vértice e esboçar o gráfico.

## Exemplos

### Exemplo 1: Parábola com mínimo ($a > 0$)

$$ f(x) = x^2 - 4x + 3 $$

- $a = 1 > 0$ (concavidade para cima)
- $\Delta = 16 - 12 = 4$
- Raízes: $x = \frac{4 \pm 2}{2} = 3$ ou $1$
- Vértice: $x_v = \frac{4}{2} = 2$, $y_v = 4 - 8 + 3 = -1$
- Vértice: $(2, -1)$ (ponto mínimo)
- Intercepto $y$: $(0, 3)$

### Exemplo 2: Parábola com máximo ($a < 0$)

$$ f(x) = -2x^2 + 8x - 5 $$

- $a = -2 < 0$ (concavidade para baixo)
- $\Delta = 64 - 40 = 24$
- Raízes: $x = \frac{-8 \pm \sqrt{24}}{-4} = \frac{-8 \pm 2\sqrt{6}}{-4} = 2 \mp \frac{\sqrt{6}}{2}$
- Vértice: $x_v = -\frac{8}{-4} = 2$, $y_v = -2(4) + 16 - 5 = 3$
- Vértice: $(2, 3)$ (ponto máximo)

## Sinal da Função Quadrática

| Condição | $a > 0$ | $a < 0$ |
|----------|---------|---------|
| $\Delta > 0$ | $f(x) > 0$ fora das raízes; $f(x) < 0$ entre | $f(x) < 0$ fora das raízes; $f(x) > 0$ entre |
| $\Delta = 0$ | $f(x) \geq 0$ sempre; $f(x) = 0$ no vértice | $f(x) \leq 0$ sempre; $f(x) = 0$ no vértice |
| $\Delta < 0$ | $f(x) > 0$ para todo $x$ | $f(x) < 0$ para todo $x$ |

## Aplicações na Vida Real

- **Física:** queda livre, lançamento de projéteis ($h = h_0 + v_0t - \frac{1}{2}gt^2$)
- **Engenharia:** arcos de pontes, projéteis parabólicos, refletores de antenas
- **Economia:** maximização de lucro (função de lucro quadrática)
- **Óptica:** espelhos parabólicos, antenas parabólicas (foco da parábola)
- **Arquitetura:** arcos parabólicos, domos, design estrutural
- **Esportes:** trajetória de bolas, saltos, arremessos
- **Biologia:** modelos de crescimento populacional com limitação de recursos
- **Jogos:** trajetórias de projéteis, saltos de personagens
- **Finanças:** funções de utilidade quadráticas, análise de risco
- **Estatística:** mínimos quadrados (ajuste parabólico a dados)

## Problemas

### Nível 1 — Básico

**1.** Determine o vértice de $f(x) = x^2 - 6x + 5$.

$$ x_v = -\frac{-6}{2(1)} = 3 $$
$$ y_v = 9 - 18 + 5 = -4 $$

**Resposta:** Vértice: $(3, -4)$. É um mínimo pois $a = 1 > 0$.

**2.** Esboce a parábola $f(x) = -x^2 + 4x - 3$ indicando vértice, raízes e intercepto com $y$.

- $a = -1 < 0$ (concavidade para baixo, máximo)
- $\Delta = 16 - 12 = 4$
- Raízes: $x = \frac{-4 \pm 2}{-2} = 3$ ou $1$
- $x_v = -\frac{4}{-2} = 2$, $y_v = -4 + 8 - 3 = 1$
- Vértice: $(2, 1)$ (máximo)
- Intercepto $y$: $(0, -3)$

**Resposta:** Vértice $(2, 1)$, raízes $x = 1$ e $x = 3$, intercepto $y$ em $(0, -3)$. Máximo em $y = 1$.

**3.** Encontre as raízes de $f(x) = 2x^2 - 7x + 3$.

$$ \Delta = 49 - 24 = 25 $$
$$ x = \frac{7 \pm 5}{4} \implies x = 3 \text{ ou } x = \frac{1}{2} $$

**Resposta:** $x = \frac{1}{2}$ ou $x = 3$.

**4.** Para que valores de $x$ a função $f(x) = x^2 - 5x + 6$ é negativa?

Raízes: $x = 2$ e $x = 3$
$a = 1 > 0$ (negativa entre as raízes)

**Resposta:** $(2, 3)$ ou $2 < x < 3$.

**5.** Escreva $f(x) = x^2 + 4x + 1$ na forma canônica.

$$ x^2 + 4x + 1 = (x^2 + 4x + 4) - 4 + 1 = (x + 2)^2 - 3 $$

**Resposta:** $f(x) = (x + 2)^2 - 3$. Vértice: $(-2, -3)$.

### Nível 2 — Intermediário

**6.** Uma bola é lançada verticalmente de uma altura de 20 m com velocidade inicial de 15 m/s. A altura é $h(t) = 20 + 15t - 5t^2$. Qual a altura máxima? E quando toca o solo?

Vértice (máximo): $t_v = -\frac{15}{2(-5)} = 1{,}5$ s
$$ h(1{,}5) = 20 + 15(1{,}5) - 5(2{,}25) = 20 + 22{,}5 - 11{,}25 = 31{,}25 \text{ m} $$

Toca o solo: $h(t) = 0$
$$ -5t^2 + 15t + 20 = 0 \implies t^2 - 3t - 4 = 0 $$
$$ (t - 4)(t + 1) = 0 \implies t = 4 \text{ s} \quad (t = -1 \text{ não faz sentido}) $$

**Resposta:** Altura máxima: 31,25 m (em $t = 1{,}5$ s). Toca o solo em $t = 4$ s.

**7.** O lucro de uma empresa é $L(x) = -2x^2 + 80x - 600$, onde $x$ é a quantidade produzida. Qual a produção que maximiza o lucro? Qual o lucro máximo?

$$ x_v = -\frac{80}{2(-2)} = 20 \text{ unidades} $$
$$ L(20) = -2(400) + 80(20) - 600 = -800 + 1600 - 600 = 200 \text{ reais} $$

**Resposta:** 20 unidades. Lucro máximo: R$ 200,00.

**8.** Determine a função quadrática cujo gráfico tem vértice em $(2, -1)$ e passa por $(0, 3)$.

Forma canônica: $f(x) = a(x - 2)^2 - 1$
$$ f(0) = a(4) - 1 = 3 \implies 4a = 4 \implies a = 1 $$
$$ f(x) = (x - 2)^2 - 1 = x^2 - 4x + 4 - 1 = x^2 - 4x + 3 $$

**Resposta:** $f(x) = x^2 - 4x + 3$.

**9.** Para que valores de $k$ a função $f(x) = x^2 - 4x + k$ tem duas raízes reais positivas?

Condições:
1. $\Delta > 0$: $16 - 4k > 0 \implies k < 4$
2. Soma das raízes $> 0$: $4 > 0$ ✓ (sempre)
3. Produto das raízes $> 0$: $k > 0$

**Resposta:** $0 < k < 4$.

**10.** Determine o valor máximo de $f(x) = -3x^2 + 12x + 5$ no intervalo $[0, 4]$.

Vértice: $x_v = -\frac{12}{2(-3)} = 2$
$f(2) = -3(4) + 24 + 5 = -12 + 24 + 5 = 17$

Verificar extremos:
$f(0) = 5$
$f(4) = -3(16) + 48 + 5 = -48 + 48 + 5 = 5$

**Resposta:** Máximo: 17 (em $x = 2$).

### Nível 3 — Desafio

**11.** Se $f(x) = ax^2 + bx + c$ tem raízes $r_1$ e $r_2$, mostre que $f(x) = a(x - r_1)(x - r_2)$. Use isso para fatorar $2x^2 - 5x - 3$.

**Prova:** Se $r_1$ e $r_2$ são raízes, então $f(r_1) = f(r_2) = 0$. A função $g(x) = a(x - r_1)(x - r_2)$ também é quadrática com as mesmas raízes e coeficiente de $x^2$ igual a $a$. Logo $f(x) - g(x)$ é uma função quadrática com mais de duas raízes, o que só é possível se $f(x) - g(x) = 0$.

Fatoração de $2x^2 - 5x - 3$:
$$ \Delta = 25 + 24 = 49 $$
$$ x = \frac{5 \pm 7}{4} \implies x = 3 \text{ ou } x = -\frac{1}{2} $$
$$ 2x^2 - 5x - 3 = 2(x - 3)\left(x + \frac{1}{2}\right) = (x - 3)(2x + 1) $$

**Resposta:** $2x^2 - 5x - 3 = (x - 3)(2x + 1)$.

**12.** Uma cerca de 40 m de comprimento deve formar um retângulo contra uma parede (apenas 3 lados precisam de cerca). Qual a área máxima possível?

Sejam $x$ os lados perpendiculares à parede e $y$ o lado paralelo.
$$ 2x + y = 40 \implies y = 40 - 2x $$
$$ A = x \cdot y = x(40 - 2x) = 40x - 2x^2 $$

Máximo: $x_v = -\frac{40}{2(-2)} = 10$ m
$$ y = 40 - 2(10) = 20 \text{ m} $$
$$ A_{max} = 10 \times 20 = 200 \text{ m}^2 $$

**Resposta:** Área máxima: $200 \text{ m}^2$ (dimensões: 10 m × 20 m).

**13.** Se $f(x) = x^2 + bx + c$ tem valor mínimo $-4$ em $x = 3$, e $f(1) = 0$, determine $b$ e $c$.

Vértice em $(3, -4)$:
$$ x_v = -\frac{b}{2} = 3 \implies b = -6 $$
$$ f(x) = (x - 3)^2 - 4 = x^2 - 6x + 9 - 4 = x^2 - 6x + 5 $$
$$ c = 5 $$

Verificação: $f(1) = 1 - 6 + 5 = 0$ ✓

**Resposta:** $b = -6$, $c = 5$.

---
**Fim — Função Quadrática**
