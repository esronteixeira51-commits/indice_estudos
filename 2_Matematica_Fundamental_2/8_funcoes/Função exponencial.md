# Função Exponencial (y = a^x)

A **função exponencial** é uma função da forma $f(x) = a^x$, onde a base $a$ é um número real positivo diferente de 1. Ela descreve crescimentos e decaimentos rápidos: populações de bactérias, juros compostos, decaimento radioativo, propagação de vídeos virais e degradação de medicamentos.

## Definição

$$ f(x) = a^x \quad \text{com} \quad a > 0 \text{ e } a \neq 1 $$

Onde:
- $a$ = **base** da exponencial
- $x$ = **expoente** (pode ser qualquer real)

## Domínio e Imagem

- $D = \mathbb{R}$ (todos os reais)
- $Im = (0, +\infty)$ (sempre positiva, nunca zero ou negativa)

## Casos: Crescimento vs Decaimento

| Base | Comportamento | Gráfico | Exemplo |
|------|--------------|---------|---------|
| $a > 1$ | **Crescente** | Sobe da esquerda para a direita | $2^x$ |
| $0 < a < 1$ | **Decrescente** | Desce da esquerda para a direita | $(\frac{1}{2})^x = 2^{-x}$ |
| $a = 1$ | Constante | Reta horizontal | $1^x = 1$ (excluído da definição) |

## Propriedades

Para $a > 0$ e $a \neq 1$:

1. $a^0 = 1$ (intercepto com o eixo $y$)
2. $a^1 = a$
3. $a^{x+y} = a^x \cdot a^y$
4. $a^{x-y} = \frac{a^x}{a^y}$
5. $(a^x)^y = a^{xy}$
6. $a^x > 0$ para todo $x$ (sempre positiva)
7. $a^x = 1 \iff x = 0$
8. $a^x = a^y \iff x = y$ (injetora)

## Função Exponencial Natural: $e^x$

A base $e \approx 2{,}71828...$ (número de Euler) é a base natural da exponencial. Aparece em:
- Juros compostos contínuos
- Crescimento natural de populações
- Decaimento radioativo
- Leis de resfriamento de Newton

$$ f(x) = e^x $$

## Gráfico

```
y = 2^x:       y = (1/2)^x = 2^(-x):
    |    *        *    |
    |   *            *  |
    |  *              * |
    | *                *|
----+-------------------+----
    |*                  *|
    |                   |
```

- Ambas passam por $(0, 1)$
- O eixo $x$ ($y = 0$) é uma **assíntota horizontal**
- Nunca toca o eixo $x$ (sempre $y > 0$)

## Equações Exponenciais

### Mesma base

$$ a^x = a^y \implies x = y $$

**Exemplo:** $2^{x+1} = 2^3 \implies x + 1 = 3 \implies x = 2$

### Bases diferentes (usar logaritmo)

$$ 3^x = 5 \implies x = \log_3 5 = \frac{\log 5}{\log 3} $$

### Exemplo com produtos

$$ 2^x \cdot 4^{x-1} = 8 $$
$$ 2^x \cdot (2^2)^{x-1} = 2^3 $$
$$ 2^x \cdot 2^{2x-2} = 2^3 $$
$$ 2^{3x-2} = 2^3 $$
$$ 3x - 2 = 3 \implies x = \frac{5}{3} $$

## Aplicações na Vida Real

- **Finanças:** juros compostos $M = C(1 + i)^t$
- **Biologia:** crescimento de bactérias $N = N_0 \cdot 2^{t/T}$ (T = tempo de geração)
- **Física:** decaimento radioativo $N = N_0 \cdot e^{-\lambda t}$
- **Medicina:** meia-vida de medicamentos, concentração no sangue
- **Química:** reações de primeira ordem, cinética química
- **Demografia:** crescimento populacional (modelo de Malthus)
- **Tecnologia:** Lei de Moore (transistores dobram a cada 2 anos)
- **Marketing:** crescimento viral de conteúdo, propagação de informação
- **Epidemiologia:** fase inicial de propagação de doenças (modelo exponencial)
- **Ecologia:** crescimento de algas, invasão de espécies

## Problemas

### Nível 1 — Básico

**1.** Calcule $f(0)$, $f(1)$, $f(2)$, $f(-1)$ para $f(x) = 2^x$.

$$ f(0) = 2^0 = 1 $$
$$ f(1) = 2^1 = 2 $$
$$ f(2) = 2^2 = 4 $$
$$ f(-1) = 2^{-1} = \frac{1}{2} = 0{,}5 $$

**Resposta:** $f(0) = 1$, $f(1) = 2$, $f(2) = 4$, $f(-1) = 0{,}5$.

**2.** Esboce o gráfico de $f(x) = 3^x$ e identifique se é crescente ou decrescente.

- Base $3 > 1$ → crescente
- Passa por $(0, 1)$, $(1, 3)$, $(-1, \frac{1}{3})$
- Assíntota: $y = 0$

**Resposta:** Crescente. Passa por $(0, 1)$.

**3.** Resolva $2^{x} = 16$.

$$ 16 = 2^4 \implies x = 4 $$

**Resposta:** $x = 4$.

**4.** Resolva $5^{x-1} = 25$.

$$ 25 = 5^2 \implies x - 1 = 2 \implies x = 3 $$

**Resposta:** $x = 3$.

**5.** Um investimento rende 10% ao ano. Qual o montante após 3 anos se o capital inicial é R$ 1000,00?

$$ M = 1000(1 + 0{,}10)^3 = 1000(1{,}1)^3 = 1000(1{,}331) = 1331 \text{ reais} $$

**Resposta:** R$ 1331,00.

### Nível 2 — Intermediário

**6.** Resolva $3^{x+1} + 3^{x-1} = 30$.

$$ 3^{x+1} = 3 \cdot 3^x, \quad 3^{x-1} = \frac{3^x}{3} $$
$$ 3 \cdot 3^x + \frac{3^x}{3} = 30 $$
$$ 3^x\left(3 + \frac{1}{3}\right) = 30 $$
$$ 3^x \cdot \frac{10}{3} = 30 $$
$$ 3^x = 9 = 3^2 \implies x = 2 $$

**Resposta:** $x = 2$.

**7.** Uma população de bactérias dobra a cada 2 horas. Se começa com 1000 bactérias, quantas haverá após 8 horas? Escreva a função.

$$ N(t) = 1000 \cdot 2^{t/2} $$
$$ N(8) = 1000 \cdot 2^{8/2} = 1000 \cdot 2^4 = 1000 \cdot 16 = 16000 $$

**Resposta:** $N(t) = 1000 \cdot 2^{t/2}$. Após 8 horas: 16.000 bactérias.

**8.** Resolva $2^{x} = 3^{x-1}$.

$$ 2^x = 3^{x-1} \implies 2^x = \frac{3^x}{3} \implies 3 \cdot 2^x = 3^x $$
$$ 3 = \frac{3^x}{2^x} = \left(\frac{3}{2}\right)^x $$
$$ x = \log_{3/2} 3 = \frac{\log 3}{\log(3/2)} = \frac{\log 3}{\log 3 - \log 2} \approx \frac{0{,}477}{0{,}176} \approx 2{,}71 $$

**Resposta:** $x = \log_{3/2} 3 = \frac{\log 3}{\log 3 - \log 2} \approx 2{,}71$.

**9.** Um medicamento tem meia-vida de 6 horas. Se a dose inicial é 200 mg, quanto resta após 24 horas? Escreva a função.

$$ C(t) = 200 \cdot \left(\frac{1}{2}\right)^{t/6} = 200 \cdot 2^{-t/6} $$
$$ C(24) = 200 \cdot 2^{-24/6} = 200 \cdot 2^{-4} = 200 \cdot \frac{1}{16} = 12{,}5 \text{ mg} $$

**Resposta:** $C(t) = 200 \cdot 2^{-t/6}$. Após 24 horas: 12,5 mg.

**10.** Determine o domínio de $f(x) = 2^{\sqrt{x-1}}$.

$$ x - 1 \geq 0 \implies x \geq 1 $$

**Resposta:** $D = [1, +\infty)$.

### Nível 3 — Desafio

**11.** Resolva $4^x - 2^{x+1} - 8 = 0$.

$$ 4^x = (2^2)^x = 2^{2x} = (2^x)^2 $$
Seja $y = 2^x$ ($y > 0$):
$$ y^2 - 2y - 8 = 0 $$
$$ y = \frac{2 \pm \sqrt{4 + 32}}{2} = \frac{2 \pm 6}{2} $$
$$ y = 4 \text{ ou } y = -2 \text{ (não válido, pois } y > 0 \text{)} $$
$$ 2^x = 4 = 2^2 \implies x = 2 $$

**Resposta:** $x = 2$.

**12.** Se $f(x) = a^x$ passa por $(2, 9)$, determine $a$ e calcule $f(3)$ e $f(-1)$.

$$ a^2 = 9 \implies a = 3 \quad (a > 0) $$
$$ f(3) = 3^3 = 27 $$
$$ f(-1) = 3^{-1} = \frac{1}{3} $$

**Resposta:** $a = 3$. $f(3) = 27$, $f(-1) = \frac{1}{3}$.

**13.** Um país tem população de 10 milhões e cresce a 2% ao ano. Em quantos anos a população dobrará? Use $\log_{1,02} 2 = \frac{\ln 2}{\ln 1{,}02} \approx 35$.

$$ P(t) = 10 \cdot (1{,}02)^t $$
$$ 10 \cdot (1{,}02)^t = 20 \implies (1{,}02)^t = 2 $$
$$ t = \log_{1,02} 2 \approx 35 \text{ anos} $$

**Resposta:** Aproximadamente 35 anos (Regra dos 70: $70/2 = 35$).

---
**Fim — Função Exponencial**
