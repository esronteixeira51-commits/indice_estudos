# Função Logarítmica (y = log_a x)

A **função logarítmica** é a **inversa** da função exponencial. Enquanto a exponencial responde "qual o resultado de elevar a base a uma potência?", o logaritmo responde "a qual potência devo elevar a base para obter esse resultado?". É fundamental em escalas de magnitude, decibéis, pH, crescimento e análise de dados.

## Definição

$$ y = \log_a x \iff a^y = x $$

Onde:
- $a > 0$, $a \neq 1$ (base)
- $x > 0$ (argumento deve ser positivo)
- $y$ = logaritmo de $x$ na base $a$

## Domínio e Imagem

- $D = (0, +\infty)$ (apenas números positivos)
- $Im = \mathbb{R}$ (todos os reais)

> **Importante:** Não existe $\log_a 0$ nem $\log_a(\text{negativo})$ em reais!

## Casos: Crescente vs Decrescente

| Base | Comportamento | Gráfico | Exemplo |
|------|--------------|---------|---------|
| $a > 1$ | **Crescente** | Sobe da esquerda para a direita | $\log_2 x$ |
| $0 < a < 1$ | **Decrescente** | Desce da esquerda para a direita | $\log_{1/2} x$ |

## Propriedades dos Logaritmos

Para $a > 0$, $a \neq 1$, $M > 0$, $N > 0$:

1. **Produto:** $\log_a(M \cdot N) = \log_a M + \log_a N$
2. **Quociente:** $\log_a\left(\frac{M}{N}\right) = \log_a M - \log_a N$
3. **Potência:** $\log_a(M^n) = n \cdot \log_a M$
4. **Raiz:** $\log_a(\sqrt[n]{M}) = \frac{1}{n} \log_a M$
5. **Mudança de base:** $\log_a M = \frac{\log_b M}{\log_b a}$
6. **Logaritmo de 1:** $\log_a 1 = 0$ (pois $a^0 = 1$)
7. **Logaritmo da base:** $\log_a a = 1$ (pois $a^1 = a$)
8. **Inversa:** $a^{\log_a x} = x$ e $\log_a(a^x) = x$

## Logaritmo Natural ($\ln$) e Decimal ($\log$)

- **Logaritmo natural:** $\ln x = \log_e x$ (base $e \approx 2{,}718$)
- **Logaritmo decimal (ou comum):** $\log x = \log_{10} x$ (base 10)

## Gráfico

O gráfico de $y = \log_a x$ é simétrico ao de $y = a^x$ em relação à reta $y = x$ (são inversas).

```
y = log_2 x:        y = log_{1/2} x:
    |   *                *   |
    |  *                  *  |
    | *                    * |
----+-----------------------+----
    |*                      *|
    |1                      |
```

- Passa por $(1, 0)$ (pois $\log_a 1 = 0$)
- Passa por $(a, 1)$ (pois $\log_a a = 1$)
- O eixo $y$ ($x = 0$) é uma **assíntota vertical**
- Nunca toca o eixo $y$ (domínio $x > 0$)

## Equações Logarítmicas

### Básica

$$ \log_a x = b \implies x = a^b $$

**Exemplo:** $\log_2 x = 5 \implies x = 2^5 = 32$

### Com propriedades

$$ \log_3 x + \log_3(x-2) = \log_3 8 $$
Condição: $x > 0$ e $x - 2 > 0 \implies x > 2$

$$ \log_3[x(x-2)] = \log_3 8 $$
$$ x(x-2) = 8 $$
$$ x^2 - 2x - 8 = 0 $$
$$ (x-4)(x+2) = 0 \implies x = 4 \text{ ou } x = -2 $$

$x = -2$ não satisfaz $x > 2$. **Resposta:** $x = 4$.

### Mudança de base

$$ \log_2 5 = \frac{\log 5}{\log 2} \approx \frac{0{,}699}{0{,}301} \approx 2{,}32 $$

## Aplicações na Vida Real

- **Química:** pH = $-\log_{10}[H^+]$ (escala logarítmica de acidez)
- **Física:** escala de decibéis (dB) = $10 \log_{10}(P/P_0)$ (intensidade sonora)
- **Astronomia:** magnitude de estrelas (escala logarítmica de brilho)
- **Geologia:** escala de Richter para terremotos ($M = \log_{10}(A/A_0)$)
- **Biologia:** contagem de colônias de bactérias (logaritmo da contagem)
- **Informática:** complexidade de algoritmos ($O(\log n)$), profundidade de árvores
- **Música:** escala de tons (intervalos logarítmicos de frequência)
- **Finanças:** tempo para dobrar investimento (regra dos 70)
- **Estatística:** transformação logarítmica de dados (normalização)
- **Radiologia:** absorção de radiação (Lei de Beer-Lambert, logarítmica)

## Problemas

### Nível 1 — Básico

**1.** Calcule $\log_2 8$, $\log_3 27$, $\log_5 1$, $\log_{10} 1000$.

$$ \log_2 8 = 3 \text{ (pois } 2^3 = 8 \text{)} $$
$$ \log_3 27 = 3 \text{ (pois } 3^3 = 27 \text{)} $$
$$ \log_5 1 = 0 \text{ (pois } 5^0 = 1 \text{)} $$
$$ \log_{10} 1000 = 3 \text{ (pois } 10^3 = 1000 \text{)} $$

**Resposta:** 3, 3, 0, 3.

**2.** Resolva $\log_2 x = 5$.

$$ x = 2^5 = 32 $$

**Resposta:** $x = 32$.

**3.** Simplifique $\log_2(8 \cdot 4)$.

$$ \log_2(8 \cdot 4) = \log_2 8 + \log_2 4 = 3 + 2 = 5 $$

Ou: $8 \cdot 4 = 32 = 2^5$, então $\log_2 32 = 5$.

**Resposta:** 5.

**4.** Simplifique $\log_3\left(\frac{27}{9}\right)$.

$$ \log_3\left(\frac{27}{9}\right) = \log_3 27 - \log_3 9 = 3 - 2 = 1 $$

Ou: $\frac{27}{9} = 3 = 3^1$, então $\log_3 3 = 1$.

**Resposta:** 1.

**5.** Esboce o gráfico de $y = \log_2 x$ e indique pontos importantes.

- $(1, 0)$: $\log_2 1 = 0$
- $(2, 1)$: $\log_2 2 = 1$
- $(4, 2)$: $\log_2 4 = 2$
- $(0{,}5, -1)$: $\log_2(0{,}5) = -1$
- Crescente (base $2 > 1$)
- Assíntota vertical: $x = 0$

**Resposta:** Gráfico crescente passando por $(1, 0)$, $(2, 1)$, $(4, 2)$, com assíntota em $x = 0$.

### Nível 2 — Intermediário

**6.** Resolva $\log_2(x+1) + \log_2(x-1) = 3$.

Condição: $x + 1 > 0$ e $x - 1 > 0 \implies x > 1$

$$ \log_2[(x+1)(x-1)] = 3 $$
$$ (x+1)(x-1) = 2^3 = 8 $$
$$ x^2 - 1 = 8 $$
$$ x^2 = 9 \implies x = 3 \text{ ou } x = -3 $$

$x = -3$ não satisfaz $x > 1$. **Resposta:** $x = 3$.

**7.** Calcule $\log_4 8$ usando mudança de base.

$$ \log_4 8 = \frac{\log_2 8}{\log_2 4} = \frac{3}{2} = 1{,}5 $$

**Resposta:** $\frac{3}{2}$ ou $1{,}5$.

**8.** Resolva $3^{x} = 7$ usando logaritmos.

$$ x = \log_3 7 = \frac{\log 7}{\log 3} \approx \frac{0{,}845}{0{,}477} \approx 1{,}77 $$

**Resposta:** $x = \log_3 7 \approx 1{,}77$.

**9.** O pH de uma solução é definido como $pH = -\log_{10}[H^+]$. Se $[H^+] = 10^{-5}$ mol/L, qual o pH?

$$ pH = -\log_{10}(10^{-5}) = -(-5) = 5 $$

**Resposta:** $pH = 5$ (solução ácida, mas moderadamente).

**10.** Resolva $\log_5(x^2 - 5x + 6) = \log_5(x - 1)$.

Condição: $x^2 - 5x + 6 > 0$ e $x - 1 > 0$

$$ x^2 - 5x + 6 = x - 1 $$
$$ x^2 - 6x + 7 = 0 $$
$$ x = \frac{6 \pm \sqrt{36 - 28}}{2} = \frac{6 \pm \sqrt{8}}{2} = \frac{6 \pm 2\sqrt{2}}{2} = 3 \pm \sqrt{2} $$

Verificar condições:
- $x = 3 + \sqrt{2} \approx 4{,}41$: $x - 1 > 0$ ✓, $x^2 - 5x + 6 = (x-2)(x-3) = (1+\sqrt{2})(\sqrt{2}) > 0$ ✓
- $x = 3 - \sqrt{2} \approx 1{,}59$: $x - 1 > 0$ ✓, $x^2 - 5x + 6 = (x-2)(x-3) = (1-\sqrt{2})(-\sqrt{2}) = -\sqrt{2} + 2 > 0$? $2 - 1{,}41 = 0{,}59 > 0$ ✓

Ambas são válidas!

**Resposta:** $x = 3 + \sqrt{2}$ ou $x = 3 - \sqrt{2}$.

### Nível 3 — Desafio

**11.** Se $\log_2 a + \log_2 b = 5$ e $\frac{a}{b} = 4$, encontre $a$ e $b$.

$$ \log_2(ab) = 5 \implies ab = 2^5 = 32 $$
$$ \frac{a}{b} = 4 \implies a = 4b $$

$$ 4b \cdot b = 32 \implies 4b^2 = 32 \implies b^2 = 8 \implies b = 2\sqrt{2} \text{ (positivo)} $$
$$ a = 4(2\sqrt{2}) = 8\sqrt{2} $$

**Resposta:** $a = 8\sqrt{2}$, $b = 2\sqrt{2}$.

**12.** Resolva $\log_2 x + \log_4 x + \log_8 x = 11$.

Mudar tudo para base 2:
$$ \log_4 x = \frac{\log_2 x}{\log_2 4} = \frac{\log_2 x}{2} $$
$$ \log_8 x = \frac{\log_2 x}{\log_2 8} = \frac{\log_2 x}{3} $$

Seja $y = \log_2 x$:
$$ y + \frac{y}{2} + \frac{y}{3} = 11 $$
$$ y\left(1 + \frac{1}{2} + \frac{1}{3}\right) = 11 $$
$$ y \cdot \frac{6 + 3 + 2}{6} = 11 $$
$$ y \cdot \frac{11}{6} = 11 \implies y = 6 $$
$$ \log_2 x = 6 \implies x = 2^6 = 64 $$

**Resposta:** $x = 64$.

**13.** Uma cultura de bactérias cresce de modo que após $t$ horas, a população é $P(t) = P_0 \cdot e^{kt}$. Se a população dobra em 3 horas, quanto tempo leva para triplicar? Use $\ln 3 / \ln 2 \approx 1{,}585$.

$$ P(3) = 2P_0 \implies P_0 e^{3k} = 2P_0 \implies e^{3k} = 2 $$
$$ 3k = \ln 2 \implies k = \frac{\ln 2}{3} $$

Para triplicar: $P(t) = 3P_0$
$$ e^{kt} = 3 \implies kt = \ln 3 \implies t = \frac{\ln 3}{k} = \frac{\ln 3}{\ln 2 / 3} = 3 \cdot \frac{\ln 3}{\ln 2} \approx 3(1{,}585) \approx 4{,}76 \text{ horas} $$

**Resposta:** Aproximadamente 4,76 horas (ou cerca de 4 horas e 45 minutos).

---
**Fim — Função Logarítmica**
