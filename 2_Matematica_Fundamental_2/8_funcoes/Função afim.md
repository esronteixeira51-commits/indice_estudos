# Função Afim (y = ax + b)

A **função afim** (ou função linear, ou função do 1º grau) é a função mais simples e fundamental da matemática. Ela descreve relações de proporcionalidade direta com um acréscimo constante: a distância percorrida por um carro em velocidade constante, o custo de uma corrida de táxi, a conversão de temperaturas entre escalas.

## Definição

$$ f(x) = ax + b \quad \text{ou} \quad y = ax + b $$

Onde:
- $a$ = **coeficiente angular** (taxa de variação, inclinação da reta)
- $b$ = **coeficiente linear** (intercepto, valor de $y$ quando $x = 0$)

## Casos Especiais

| Caso | Fórmula | Nome | Gráfico |
|------|---------|------|---------|
| $a \neq 0$, $b \neq 0$ | $y = ax + b$ | Função afim (geral) | Reta inclinada |
| $a \neq 0$, $b = 0$ | $y = ax$ | Função linear (proporcional) | Reta pela origem |
| $a = 0$, $b \neq 0$ | $y = b$ | Função constante | Reta horizontal |
| $a = 0$, $b = 0$ | $y = 0$ | Função nula | Eixo x |

## Gráfico

O gráfico de uma função afim é sempre uma **reta**.

- **Coeficiente angular $a$:** determina a inclinação
  - $a > 0$: reta crescente (sobe da esquerda para a direita)
  - $a < 0$: reta decrescente (desce da esquerda para a direita)
  - $a = 0$: reta horizontal
  - $|a|$ maior = reta mais "íngreme"

- **Coeficiente linear $b$:** determina onde a reta cruza o eixo $y$
  - Ponto $(0, b)$ é o intercepto com o eixo $y$

### Exemplos Gráficos

```
y = 2x + 1 (crescente, intercepta y em 1)
y = -x + 3 (decrescente, intercepta y em 3)
y = 2 (constante, horizontal)
```

## Determinação da Função Afim

### Dados dois pontos $(x_1, y_1)$ e $(x_2, y_2)$

**Coeficiente angular:**
$$ a = \frac{y_2 - y_1}{x_2 - x_1} = \frac{\Delta y}{\Delta x} $$

**Coeficiente linear:**
$$ b = y_1 - a x_1 $$

### Exemplo

Determine $f(x)$ que passa por $(1, 5)$ e $(3, 11)$.

$$ a = \frac{11 - 5}{3 - 1} = \frac{6}{2} = 3 $$
$$ b = 5 - 3(1) = 2 $$
$$ f(x) = 3x + 2 $$

## Zero da Função (Raiz)

O ponto onde $f(x) = 0$ (intersecção com o eixo $x$):

$$ ax + b = 0 \implies x = -\frac{b}{a} \quad (a \neq 0) $$

## Sinal da Função Afim

- $a > 0$: $f(x) < 0$ para $x < -b/a$; $f(x) > 0$ para $x > -b/a$
- $a < 0$: $f(x) > 0$ para $x < -b/a$; $f(x) < 0$ para $x > -b/a$

## Função Crescente / Decrescente / Constante

- $a > 0$: função é **crescente** (quanto maior $x$, maior $f(x)$)
- $a < 0$: função é **decrescente** (quanto maior $x$, menor $f(x)$)
- $a = 0$: função é **constante**

## Aplicações na Vida Real

- **Física:** movimento uniforme $s = s_0 + vt$ (posição = inicial + velocidade × tempo)
- **Economia:** custo total $C = CF + CV \times q$ (custo fixo + variável por unidade)
- **Finanças:** juros simples $M = C + J \times t$ (montante = capital + juros acumulados)
- **Meteorologia:** conversão de temperaturas $C = \frac{5}{9}(F - 32)$ ou $F = \frac{9}{5}C + 32$
- **Geografia:** altitude em função da distância (terreno plano ou inclinado constante)
- **Engenharia:** deformação linear de materiais dentro do limite elástico (Lei de Hooke: $F = kx$)
- **Medicina:** dosagem linear com o peso ($D = k \times m$)
- **Cozinha:** receitas proporcionais (dobrar ingredientes = dobrar resultado)
- **Jogos:** experiência por nível, progressão linear de habilidades
- **Estatística:** regressão linear simples (ajuste de reta a dados)

## Problemas

### Nível 1 — Básico

**1.** Determine a função afim que passa pelos pontos $(0, 3)$ e $(2, 7)$.

$$ a = \frac{7 - 3}{2 - 0} = \frac{4}{2} = 2 $$
$$ b = 3 \text{ (pois quando } x = 0, y = 3 \text{)} $$
$$ f(x) = 2x + 3 $$

**Resposta:** $f(x) = 2x + 3$.

**2.** Esboce o gráfico de $y = -2x + 4$ e determine onde a reta corta os eixos.

- Eixo $y$: $x = 0 \implies y = 4$ → ponto $(0, 4)$
- Eixo $x$: $y = 0 \implies -2x + 4 = 0 \implies x = 2$ → ponto $(2, 0)$
- Reta decrescente (pois $a = -2 < 0$)

**Resposta:** Corta o eixo $y$ em $(0, 4)$ e o eixo $x$ em $(2, 0)$. Reta decrescente.

**3.** Se $f(x) = 3x - 6$, encontre o zero da função.

$$ 3x - 6 = 0 \implies x = 2 $$

**Resposta:** $x = 2$.

**4.** A temperatura em Celsius é $C = \frac{5}{9}(F - 32)$. Converta $77°F$ para Celsius.

$$ C = \frac{5}{9}(77 - 32) = \frac{5}{9}(45) = 5 \times 5 = 25°C $$

**Resposta:** $25°C$.

**5.** Uma corrida de táxi custa R$ 5,00 de bandeirada mais R$ 2,50 por km. Escreva a função e calcule o custo de 8 km.

$$ C(x) = 5 + 2{,}5x $$
$$ C(8) = 5 + 2{,}5(8) = 5 + 20 = 25 \text{ reais} $$

**Resposta:** $C(x) = 5 + 2{,}5x$. Custo de 8 km: R$ 25,00.

### Nível 2 — Intermediário

**6.** Determine a função afim $f(x) = ax + b$ tal que $f(1) = 4$ e $f(-2) = -5$.

$$ \begin{cases} a + b = 4 \\ -2a + b = -5 \end{cases} $$

Subtraindo: $3a = 9 \implies a = 3$
$b = 4 - 3 = 1$

$$ f(x) = 3x + 1 $$

**Resposta:** $f(x) = 3x + 1$.

**7.** Para que valores de $x$ a função $f(x) = -3x + 9$ é positiva?

$$ -3x + 9 > 0 \implies -3x > -9 \implies x < 3 $$

**Resposta:** $x < 3$ ou $(-\infty, 3)$.

**8.** Um carro parte da posição 20 km e viaja a 80 km/h. Escreva a função posição $s(t)$ e determine quando passa pelo km 180.

$$ s(t) = 20 + 80t $$
$$ 20 + 80t = 180 \implies 80t = 160 \implies t = 2 \text{ h} $$

**Resposta:** $s(t) = 20 + 80t$. Passa pelo km 180 em $t = 2$ horas.

**9.** Determine a função que converte km/h em m/s.

1 km/h = $\frac{1000}{3600}$ m/s = $\frac{5}{18}$ m/s

$$ f(x) = \frac{5}{18}x $$

Converta 90 km/h:
$$ f(90) = \frac{5}{18} \times 90 = 5 \times 5 = 25 \text{ m/s} $$

**Resposta:** $f(x) = \frac{5}{18}x$. 90 km/h = 25 m/s.

**10.** Determine o ponto de interseção das retas $y = 2x + 1$ e $y = -x + 4$.

$$ 2x + 1 = -x + 4 \implies 3x = 3 \implies x = 1 $$
$$ y = 2(1) + 1 = 3 $$

**Resposta:** $(1, 3)$.

### Nível 3 — Desafio

**11.** Se $f(x) = ax + b$ satisfaz $f(f(x)) = 4x + 3$, encontre $a$ e $b$.

$$ f(f(x)) = f(ax + b) = a(ax + b) + b = a^2x + ab + b = 4x + 3 $$

$$ a^2 = 4 \implies a = 2 \text{ ou } a = -2 $$

Caso $a = 2$: $2b + b = 3 \implies 3b = 3 \implies b = 1$
Caso $a = -2$: $-2b + b = 3 \implies -b = 3 \implies b = -3$

**Resposta:** $a = 2, b = 1$ (função $f(x) = 2x + 1$) ou $a = -2, b = -3$ (função $f(x) = -2x - 3$).

**12.** Um reservatório tem 500 litros e recebe água a 20 litros/minuto, enquanto um outro reservatório tem 1000 litros e perde água a 30 litros/minuto. Após quantos minutos terão o mesmo volume? Qual será esse volume?

$$ V_1(t) = 500 + 20t $$
$$ V_2(t) = 1000 - 30t $$

$$ 500 + 20t = 1000 - 30t $$
$$ 50t = 500 \implies t = 10 \text{ min} $$
$$ V = 500 + 20(10) = 700 \text{ litros} $$

**Resposta:** 10 minutos. Volume: 700 litros.

**13.** Seja $f(x) = ax + b$ com $a > 0$. Mostre que $f$ é bijetora de $\mathbb{R}$ para $\mathbb{R}$ e encontre sua inversa. Prove que $f^{-1}$ também é afim.

**Injetora:** $f(x_1) = f(x_2) \implies ax_1 + b = ax_2 + b \implies ax_1 = ax_2 \implies x_1 = x_2$ (pois $a \neq 0$).

**Sobrejetora:** Para qualquer $y \in \mathbb{R}$, $x = \frac{y - b}{a}$ satisfaz $f(x) = y$.

Logo é bijetora.

**Inversa:**
$$ y = ax + b \implies x = \frac{y - b}{a} = \frac{1}{a}y - \frac{b}{a} $$
$$ f^{-1}(x) = \frac{1}{a}x - \frac{b}{a} $$

Que é da forma $f^{-1}(x) = cx + d$ com $c = \frac{1}{a}$ e $d = -\frac{b}{a}$.

**Resposta:** $f^{-1}(x) = \frac{1}{a}x - \frac{b}{a}$, que é afim com coeficientes $c = \frac{1}{a}$ e $d = -\frac{b}{a}$.

---
**Fim — Função Afim**
