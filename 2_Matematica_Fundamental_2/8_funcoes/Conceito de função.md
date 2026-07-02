# Conceito de Função

Uma **função** é uma relação matemática que associa a cada elemento de um conjunto (domínio) **exatamente um** elemento de outro conjunto (contradomínio). Funções descrevem dependências entre grandezas: a posição depende do tempo, o custo depende da quantidade, a temperatura depende da altitude.

## Definição Formal

$$ f: A \to B $$

Uma função $f$ do conjunto $A$ (domínio) para o conjunto $B$ (contradomínio) é uma regra que associa a **cada** $x \in A$ **exatamente um** $y \in B$.

$$ y = f(x) $$

- $x$ = **variável independente** (entrada, argumento)
- $y$ = **variável dependente** (saída, imagem)
- $f(x)$ = valor da função em $x$

## Notações Comuns

| Notação | Exemplo | Significado |
|---------|---------|-------------|
| $y = f(x)$ | $y = 2x + 1$ | $y$ é função de $x$ |
| $f: x \mapsto y$ | $f: x \mapsto 2x + 1$ | $f$ leva $x$ em $2x + 1$ |
| $f(x) = 2x + 1$ | $f(3) = 7$ | Valor da função em $x = 3$ é $7$ |

## Componentes de uma Função

### Domínio ($D$)

Conjunto de todos os valores de $x$ para os quais a função está definida.

$$ D = \{x \in \mathbb{R} \mid f(x) \text{ está definida}\} $$

**Exemplos:**
- $f(x) = 2x + 1$: $D = \mathbb{R}$ (todos os reais)
- $f(x) = \frac{1}{x}$: $D = \mathbb{R} \setminus \{0\}$ (excluímos $x = 0$)
- $f(x) = \sqrt{x}$: $D = [0, +\infty)$ (não negativos)
- $f(x) = \log(x)$: $D = (0, +\infty)$ (positivos)

### Contradomínio ($CD$)

Conjunto onde a função "pode" assumir valores (geralmente $\mathbb{R}$).

### Imagem ($Im$)

Conjunto de todos os valores que a função **realmente assume**.

$$ Im = \{f(x) \mid x \in D\} $$

**Exemplo:** $f(x) = x^2$
- $D = \mathbb{R}$
- $CD = \mathbb{R}$
- $Im = [0, +\infty)$ (quadrados são sempre não negativos)

## Gráfico de uma Função

O gráfico de $f$ é o conjunto de todos os pontos $(x, f(x))$ no plano cartesiano.

$$ \text{Gráfico} = \{(x, y) \in \mathbb{R}^2 \mid y = f(x), x \in D\} $$

### Teste da Reta Vertical

Uma curva no plano representa uma função **se e somente se** nenhuma reta vertical intersecta a curva em mais de um ponto.

## Exemplos de Funções

### Função Constante

$$ f(x) = c $$

- $D = \mathbb{R}$
- $Im = \{c\}$
- Gráfico: reta horizontal

### Função Identidade

$$ f(x) = x $$

- $D = \mathbb{R}$
- $Im = \mathbb{R}$
- Gráfico: bissetriz dos quadrantes ímpares (reta $y = x$)

### Função Módulo (Valor Absoluto)

$$ f(x) = |x| = \begin{cases} x, & x \geq 0 \\ -x, & x < 0 \end{cases} $$

- $D = \mathbb{R}$
- $Im = [0, +\infty)$
- Gráfico: "V" com vértice na origem

### Função Parte Inteira (Floor)

$$ f(x) = \lfloor x \rfloor = \text{maior inteiro } \leq x $$

- $f(2{,}3) = 2$, $f(5) = 5$, $f(-1{,}7) = -2$
- Gráfico: "degraus" (função escada)

## Função Injetora, Sobrejetora e Bijetora

| Tipo | Definição | Significado |
|------|-----------|-------------|
| **Injetora** (um-para-um) | $f(a) = f(b) \implies a = b$ | Nenhum $y$ é imagem de dois $x$ diferentes |
| **Sobrejetora** (sobre) | $\forall y \in B, \exists x \in A: f(x) = y$ | Todos os $y$ no contradomínio são atingidos |
| **Bijetora** | Injetora E sobrejetora | Cada $x$ vai para um $y$ único, e vice-versa |

### Exemplo: Função Bijetora

$$ f(x) = 2x + 1 \text{ de } \mathbb{R} \text{ para } \mathbb{R} $$

- Injetora: $2a + 1 = 2b + 1 \implies a = b$ ✓
- Sobrejetora: para qualquer $y$, $x = \frac{y - 1}{2}$ é solução ✓
- Bijetora ✓

## Função Composta

$$ (f \circ g)(x) = f(g(x)) $$

Aplicamos $g$ primeiro, depois $f$.

**Exemplo:** $f(x) = x^2$, $g(x) = x + 1$
$$ (f \circ g)(x) = f(g(x)) = f(x + 1) = (x + 1)^2 $$
$$ (g \circ f)(x) = g(f(x)) = g(x^2) = x^2 + 1 $$

> **Importante:** $f \circ g \neq g \circ f$ em geral! (composição não é comutativa)

## Função Inversa

Se $f$ é **bijetora**, existe $f^{-1}$ tal que:
$$ f^{-1}(f(x)) = x \quad \text{e} \quad f(f^{-1}(y)) = y $$

**Exemplo:** $f(x) = 2x + 1$ e $f^{-1}(x) = \frac{x - 1}{2}$
$$ f^{-1}(f(3)) = f^{-1}(7) = \frac{7 - 1}{2} = 3 $$ ✓

## Aplicações na Vida Real

- **Física:** posição em função do tempo $s(t)$, velocidade $v(t)$, aceleração $a(t)$
- **Economia:** custo total $C(q)$, receita $R(p)$, demanda $D(p)$
- **Biologia:** crescimento populacional $P(t)$, decaimento radioativo $N(t)$
- **Engenharia:** tensão em função da deformação, vazão em função da pressão
- **Medicina:** concentração de medicamento no sangue $C(t)$
- **Meteorologia:** temperatura em função da hora $T(h)$, pressão em função da altitude
- **Finanças:** montante em função do tempo $M(t)$, valor presente $VP(t)$
- **Geografia:** altitude em função das coordenadas $h(x, y)$
- **Jogos:** pontuação em função do tempo, nível em função da experiência
- **Estatística:** distribuição de probabilidade $f(x)$, função densidade

## Problemas

### Nível 1 — Básico

**1.** Se $f(x) = 3x + 2$, calcule $f(1)$, $f(0)$, $f(-2)$.

$$ f(1) = 3(1) + 2 = 5 $$
$$ f(0) = 3(0) + 2 = 2 $$
$$ f(-2) = 3(-2) + 2 = -4 $$

**Resposta:** $f(1) = 5$, $f(0) = 2$, $f(-2) = -4$.

**2.** Qual o domínio de $f(x) = \frac{1}{x - 2}$?

$$ x - 2 \neq 0 \implies x \neq 2 $$

**Resposta:** $D = \mathbb{R} \setminus \{2\}$.

**3.** Se $f(x) = x^2 - 1$, calcule $f(2)$ e $f(f(2))$.

$$ f(2) = 4 - 1 = 3 $$
$$ f(f(2)) = f(3) = 9 - 1 = 8 $$

**Resposta:** $f(2) = 3$, $f(f(2)) = 8$.

**4.** A curva $x^2 + y^2 = 4$ representa uma função? Justifique.

Para $x = 0$: $y^2 = 4 \implies y = 2$ ou $y = -2$. Um $x$ associado a dois $y$!

**Resposta:** Não, pois uma reta vertical $x = 0$ intersecta a curva em dois pontos $(0, 2)$ e $(0, -2)$. Falha no teste da reta vertical.

**5.** Se $f(x) = 2x$ e $g(x) = x + 3$, calcule $(f \circ g)(x)$ e $(g \circ f)(x)$.

$$ (f \circ g)(x) = f(g(x)) = f(x + 3) = 2(x + 3) = 2x + 6 $$
$$ (g \circ f)(x) = g(f(x)) = g(2x) = 2x + 3 $$

**Resposta:** $(f \circ g)(x) = 2x + 6$, $(g \circ f)(x) = 2x + 3$.

### Nível 2 — Intermediário

**6.** Encontre a função inversa de $f(x) = 3x - 5$.

$$ y = 3x - 5 \implies y + 5 = 3x \implies x = \frac{y + 5}{3} $$
$$ f^{-1}(x) = \frac{x + 5}{3} $$

**Resposta:** $f^{-1}(x) = \frac{x + 5}{3}$.

**7.** Determine a imagem de $f(x) = x^2 + 2x + 3$.

Completando o quadrado:
$$ f(x) = (x^2 + 2x + 1) + 2 = (x + 1)^2 + 2 $$

$(x + 1)^2 \geq 0$, então $f(x) \geq 2$.

**Resposta:** $Im = [2, +\infty)$.

**8.** Se $f(x) = 2x + 1$ e $g(x) = x^2$, resolva $f(g(x)) = 9$.

$$ f(g(x)) = f(x^2) = 2x^2 + 1 = 9 $$
$$ 2x^2 = 8 \implies x^2 = 4 \implies x = \pm 2 $$

**Resposta:** $x = 2$ ou $x = -2$.

**9.** Determine o domínio de $f(x) = \sqrt{x - 3} + \frac{1}{x - 5}$.

$$ x - 3 \geq 0 \implies x \geq 3 $$
$$ x - 5 \neq 0 \implies x \neq 5 $$

**Resposta:** $D = [3, +\infty) \setminus \{5\} = [3, 5) \cup (5, +\infty)$.

**10.** Verifique se $f(x) = x^3$ é injetora.

$$ f(a) = f(b) \implies a^3 = b^3 \implies a = b $$ (em reais)

**Resposta:** Sim, é injetora (e também sobrejetora de $\mathbb{R}$ para $\mathbb{R}$, logo bijetora).

### Nível 3 — Desafio

**11.** Se $f(x) = \frac{2x + 1}{x - 3}$, encontre $f^{-1}(x)$.

$$ y = \frac{2x + 1}{x - 3} $$
$$ y(x - 3) = 2x + 1 $$
$$ yx - 3y = 2x + 1 $$
$$ yx - 2x = 3y + 1 $$
$$ x(y - 2) = 3y + 1 $$
$$ x = \frac{3y + 1}{y - 2} $$

$$ f^{-1}(x) = \frac{3x + 1}{x - 2} $$

**Resposta:** $f^{-1}(x) = \frac{3x + 1}{x - 2}$ (para $x \neq 2$).

**12.** Mostre que $f(x) = x^2$ com $D = [0, +\infty)$ é injetora e encontre sua inversa.

Se $f(a) = f(b)$ com $a, b \geq 0$:
$$ a^2 = b^2 \implies a = b \text{ (pois ambos são } \geq 0 \text{)} $$
Logo é injetora.

Inversa: $y = x^2 \implies x = \sqrt{y}$ (tomamos a raiz positiva pois $x \geq 0$)
$$ f^{-1}(x) = \sqrt{x} $$

**Resposta:** $f^{-1}(x) = \sqrt{x}$ (para $x \geq 0$).

**13.** Se $f(x) = 2x + 3$ e $g(x) = ax + b$, encontre $a$ e $b$ tais que $(f \circ g)(x) = (g \circ f)(x)$ para todo $x$.

$$ (f \circ g)(x) = f(ax + b) = 2(ax + b) + 3 = 2ax + 2b + 3 $$
$$ (g \circ f)(x) = g(2x + 3) = a(2x + 3) + b = 2ax + 3a + b $$

Igualando:
$$ 2ax + 2b + 3 = 2ax + 3a + b $$
$$ 2b + 3 = 3a + b $$
$$ b + 3 = 3a $$
$$ b = 3a - 3 $$

Infinitas soluções! Por exemplo, $a = 1 \implies b = 0$; $a = 2 \implies b = 3$; etc.

**Resposta:** $b = 3a - 3$ (para qualquer $a \in \mathbb{R}$). Exemplos: $(a, b) = (1, 0), (2, 3), (0, -3)$.

---
**Fim — Conceito de Função**
