# Inequações do 2º Grau (Parábola e Intervalos)

Uma **inequação do 2º grau** é uma desigualdade que pode ser escrita na forma $ax^2 + bx + c > 0$ (ou $<$, $
geq$, $
leq$), onde $a 
eq 0$. A solução envolve analisar o **sinal da função quadrática** (parábola) e identificar os intervalos onde a expressão é positiva, negativa, ou zero.

## Conceito

$$ ax^2 + bx + c \quad \text{vs} \quad 0 $$

Onde:
- $a$, $b$, $c$ são coeficientes reais
- $a 
eq 0$
- A relação pode ser $>$, $<$, $
geq$, $
leq$, $
eq$

## O Sinal da Parábola

A função $f(x) = ax^2 + bx + c$ representa uma **parábola**. O sinal depende de:

### 1. Coeficiente $a$ (concavidade)

- $a > 0$: parábola com **concavidade para cima** (∪)
- $a < 0$: parábola com **concavidade para baixo** (∩)

### 2. Discriminante $
Delta = b^2 - 4ac$ (raízes)

| $
Delta$ | Raízes Reais | Gráfico | Sinal |
|-----------|-------------|---------|-------|
| $
Delta > 0$ | 2 raízes distintas ($x_1 < x_2$) | Cruza o eixo x em 2 pontos | Muda de sinal nos zeros |
| $
Delta = 0$ | 1 raiz dupla ($x_1 = x_2$) | Toca o eixo x em 1 ponto | Não muda de sinal (igual a zero no vértice) |
| $
Delta < 0$ | Nenhuma raiz real | Não cruza o eixo x | Sempre positivo ou sempre negativo |

### Regra dos Sinais (Resumo)

Para $a > 0$:
- $
Delta > 0$: $f(x) > 0$ fora das raízes ($x < x_1$ ou $x > x_2$); $f(x) < 0$ entre as raízes ($x_1 < x < x_2$)
- $
Delta = 0$: $f(x) 
geq 0$ para todo $x$; $f(x) = 0$ apenas em $x = -b/2a$
- $
Delta < 0$: $f(x) > 0$ para todo $x$ (sempre positivo)

Para $a < 0$ (inverte tudo!):
- $
Delta > 0$: $f(x) < 0$ fora das raízes; $f(x) > 0$ entre as raízes
- $
Delta = 0$: $f(x) 
leq 0$ para todo $x$
- $
Delta < 0$: $f(x) < 0$ para todo $x$ (sempre negativo)

## Método de Resolução

### Passo a Passo

1. **Encontrar as raízes** (se existirem): $ax^2 + bx + c = 0$ (Bhaskara)
2. **Analisar o sinal de $a$** (concavidade)
3. **Analisar o discriminante** $
Delta$
4. **Montar o quadro de sinais** ou esboçar a parábola
5. **Identificar os intervalos** que satisfazem a inequação

### Exemplo 1: Duas raízes, $a > 0$

$$ x^2 - 5x + 6 > 0 $$

Raízes: $x^2 - 5x + 6 = 0 \implies (x - 2)(x - 3) = 0 \implies x = 2$ ou $x = 3$

$a = 1 > 0$ (concavidade para cima)

Quadro de sinais:

```
         x < 2    2 < x < 3    x > 3
(x-2)      -          +          +
(x-3)      -          -          +
Produto    +          -          +
```

Queremos $> 0$:
**Resposta:** $(-
fty, 2) \cup (3, +
fty)$

Na reta real: bolhas abertas em 2 e 3, linhas para fora.

### Exemplo 2: Duas raízes, $a < 0$

$$ -x^2 + 5x - 6 > 0 $$

Multiplicar por $-1$ (inverte a desigualdade!):
$$ x^2 - 5x + 6 < 0 $$

Raízes: $x = 2$ e $x = 3$
$a = 1 > 0$

Queremos $< 0$ (entre as raízes):
**Resposta:** $(2, 3)$

> **Alternativa:** Usar a regra com $a < 0$ original: $f(x) > 0$ entre as raízes para $a < 0$.

### Exemplo 3: $
Delta = 0$

$$ x^2 - 4x + 4 
geq 0 $$

$$ 
Delta = 16 - 16 = 0 $$
Raiz: $x = 2$ (dupla)
$a = 1 > 0$ (sempre $
geq 0$, zero apenas em $x = 2$)

**Resposta:** Todos os reais ($
mathbb{R}$ ou $(-
fty, +
fty)$)

### Exemplo 4: $
Delta < 0$

$$ x^2 + x + 1 > 0 $$

$$ 
Delta = 1 - 4 = -3 < 0 $$
$a = 1 > 0$ (sempre positivo, nunca cruza o eixo x)

**Resposta:** Todos os reais ($
mathbb{R}$)

$$ x^2 + x + 1 < 0 \implies \text{ nenhuma solução} \implies \emptyset $$

### Exemplo 5: Inequação com $
leq$ ou $
geq$

$$ x^2 - 5x + 6 
leq 0 $$

Raízes: $x = 2$ e $x = 3$
$a = 1 > 0$

Queremos $
leq 0$ (inclui zero): entre as raízes, incluindo as raízes.

**Resposta:** $[2, 3]$

## Inequações Quociente (Racional)

Quando temos fração de polinômios:

$$ \frac{P(x)}{Q(x)} > 0 $$

**Método:** Analisar o sinal de numerador e denominador separadamente, depois aplicar a regra de sinais da multiplicação/divisão.

**Exemplo:**
$$ \frac{x^2 - 5x + 6}{x - 1} > 0 $$

Numerador: $x^2 - 5x + 6 = 0 \implies x = 2$ ou $x = 3$
Denominador: $x - 1 = 0 \implies x = 1$ (excluído!)

Quadro de sinais:

| Intervalo | $x^2-5x+6$ | $x-1$ | Fração |
|-----------|------------|-------|--------|
| $x < 1$ | $+$ | $-$ | $-$ |
| $1 < x < 2$ | $+$ | $+$ | $+$ |
| $2 < x < 3$ | $-$ | $+$ | $-$ |
| $x > 3$ | $+$ | $+$ | $+$ |

**Resposta:** $(1, 2) \cup (3, +
fty)$

> **Cuidado:** $x = 1$ é sempre excluído (anula denominador)!

## Produto de Inequações

$$ (x - 1)(x - 2)(x - 3) > 0 $$

Raízes: $x = 1$, $x = 2$, $x = 3$

Análise de sinal (produto de 3 fatores, todos positivos para $x > 3$):
- $x > 3$: todos $+$ → produto $+$
- $2 < x < 3$: dois $+$, um $-$ → produto $-$
- $1 < x < 2$: um $+$, dois $-$ → produto $+$
- $x < 1$: todos $-$ → produto $-$ (3 negativos = negativo)

**Resposta:** $(1, 2) \cup (3, +
fty)$

## Aplicações na Vida Real

- **Física:** altura de projétil ($h(t) > 0$ quando está no ar)
- **Economia:** lucro positivo ($L(x) = -ax^2 + bx + c > 0$ para faixa de produção)
- **Engenharia:** tensão dentro de limites aceitáveis ($T(x) 
leq T_{max}$)
- **Medicina:** concentração de medicamento eficaz ($C_{min} 
leq C(t) 
leq C_{max}$)
- **Química:** pH aceitável ($pH$ em faixa segura)
- **Estatística:** intervalo de confiança, variação dentro de limites
- **Jogos:** detecção de colisão (ponto dentro de região parabólica)
- **Finanças:** preço dentro de faixa de aceitação
- **Geografia:** altitude segura para navegação
- **Arquitetura:** carga em estrutura dentro de limites parabólicos

## Problemas

### Nível 1 — Básico

**1.** Resolva $x^2 - 7x + 10 > 0$.

Raízes: $(x - 2)(x - 5) = 0 \implies x = 2$ ou $x = 5$
$a = 1 > 0$ (positivo fora)

**Resposta:** $(-
fty, 2) \cup (5, +
fty)$.

**2.** Resolva $x^2 - 9 < 0$.

Raízes: $x = \pm 3$
$a = 1 > 0$ (negativo entre)

**Resposta:** $(-3, 3)$.

**3.** Resolva $-x^2 + 4x - 3 
geq 0$.

Multiplicar por $-1$ (inverte): $x^2 - 4x + 3 
leq 0$
Raízes: $x = 1$ e $x = 3$
$a = 1 > 0$ ($
leq 0$ entre as raízes)

**Resposta:** $[1, 3]$.

**4.** Resolva $x^2 + 2x + 5 > 0$.

$$ 
Delta = 4 - 20 = -16 < 0 $$
$a = 1 > 0$ (sempre positivo)

**Resposta:** $
mathbb{R}$ (todos os reais).

**5.** Resolva $x^2 - 6x + 9 
leq 0$.

$$ 
Delta = 36 - 36 = 0 $$
Raiz: $x = 3$ (dupla)
$a = 1 > 0$ (sempre $
geq 0$, zero em $x = 3$)

**Resposta:** $\{3\}$ (apenas $x = 3$).

### Nível 2 — Intermediário

**6.** Resolva $2x^2 - 5x - 3 < 0$.

$$ 
Delta = 25 + 24 = 49 $$
$$ x = \frac{5 \pm 7}{4} \implies x = 3 \text{ ou } x = -\frac{1}{2} $$
$a = 2 > 0$ (negativo entre as raízes)

**Resposta:** $(-\frac{1}{2}, 3)$.

**7.** Resolva $-3x^2 + 2x + 1 
geq 0$.

Multiplicar por $-1$ (inverte): $3x^2 - 2x - 1 
leq 0$
$$ 
Delta = 4 + 12 = 16 $$
$$ x = \frac{2 \pm 4}{6} \implies x = 1 \text{ ou } x = -\frac{1}{3} $$
$a = 3 > 0$ ($
leq 0$ entre)

**Resposta:** $[-\frac{1}{3}, 1]$.

**8.** Resolva $\frac{x^2 - 4}{x + 1} > 0$.

Numerador: $x^2 - 4 = 0 \implies x = \pm 2$
Denominador: $x = -1$ (excluído)

| Intervalo | $x^2-4$ | $x+1$ | Fração |
|-----------|---------|-------|--------|
| $x < -2$ | $+$ | $-$ | $-$ |
| $-2 < x < -1$ | $-$ | $-$ | $+$ |
| $-1 < x < 2$ | $-$ | $+$ | $-$ |
| $x > 2$ | $+$ | $+$ | $+$ |

**Resposta:** $(-2, -1) \cup (2, +
fty)$.

**9.** Resolva $(x - 1)(x - 3)(x - 5) < 0$.

Raízes: $x = 1, 3, 5$

Análise (produto de 3 fatores, positivo para $x > 5$):
- $x > 5$: $+$ $+$ $+$ = $+$
- $3 < x < 5$: $+$ $+$ $-$ = $-$
- $1 < x < 3$: $+$ $-$ $-$ = $+$
- $x < 1$: $-$ $-$ $-$ = $-$

Queremos $< 0$:
**Resposta:** $(-
fty, 1) \cup (3, 5)$.

**10.** Um projétil é lançado com altura $h(t) = -5t^2 + 20t$. Para quais tempos $t > 0$ o projétil está acima de 15 metros?

$$ -5t^2 + 20t > 15 $$
$$ -5t^2 + 20t - 15 > 0 $$
Multiplicar por $-1$: $5t^2 - 20t + 15 < 0$
$$ t^2 - 4t + 3 < 0 $$
$(t - 1)(t - 3) < 0$

**Resposta:** $1 < t < 3$ (entre 1 e 3 segundos).

### Nível 3 — Desafio

**11.** Resolva $x^4 - 5x^2 + 4 < 0$.

Seja $y = x^2$:
$$ y^2 - 5y + 4 < 0 $$
$(y - 1)(y - 4) < 0 \implies 1 < y < 4$

$$ 1 < x^2 < 4 $$

$x^2 > 1 \implies x < -1$ ou $x > 1$
$x^2 < 4 \implies -2 < x < 2$

Interseção: $(-2, -1) \cup (1, 2)$

**Resposta:** $(-2, -1) \cup (1, 2)$.

**12.** Resolva $\frac{x^2 - 4x + 3}{x^2 - 1} 
leq 0$.

Numerador: $(x - 1)(x - 3) = 0 \implies x = 1, 3$
Denominador: $(x - 1)(x + 1) = 0 \implies x = 1, -1$ (excluídos!)

Simplificar: $\frac{x - 3}{x + 1} 
leq 0$ para $x 
eq 1$

Raízes: $x = 3$ e $x = -1$

| Intervalo | $x-3$ | $x+1$ | Fração |
|-----------|-------|-------|--------|
| $x < -1$ | $-$ | $-$ | $+$ |
| $-1 < x < 3$ | $-$ | $+$ | $-$ |
| $x > 3$ | $+$ | $+$ | $+$ |

Queremos $
leq 0$:
**Resposta:** $(-1, 1) \cup (1, 3]$.

> $x = 1$ é excluído (anula denominador), $x = 3$ é incluído ($
leq$), $x = -1$ é excluído.

**13.** Para que valores de $k$ a inequação $x^2 - 2kx + k + 2 > 0$ é válida para todo $x$ real?

Queremos: $
Delta < 0$ e $a > 0$ (sempre positivo)
$a = 1 > 0$ ✓
$$ 
Delta = 4k^2 - 4(k + 2) < 0 $$
$$ 4k^2 - 4k - 8 < 0 $$
$$ k^2 - k - 2 < 0 $$
$(k - 2)(k + 1) < 0$

**Resposta:** $-1 < k < 2$ ou $(-1, 2)$.

---
**Fim — Inequações do 2º Grau**
