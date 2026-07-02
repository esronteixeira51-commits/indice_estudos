# Números Reais

Os **números reais** ($\mathbb{R}$) são a união dos números racionais ($\mathbb{Q}$) e irracionais ($\mathbb{I}$). Eles completam a reta numérica, preenchendo todos os pontos sem lacunas. O conjunto dos reais é a base para a análise matemática, cálculo, e praticamente toda a matemática avançada.

## Definição

$$ \mathbb{R} = \mathbb{Q} \cup \mathbb{I} $$

Onde:
- $\mathbb{Q}$ = racionais (frações, decimais finitas ou periódicas)
- $\mathbb{I}$ = irracionais (decimais infinitas não periódicas)
- $\mathbb{Q} \cap \mathbb{I} = \emptyset$ (disjuntos)

## Hierarquia Completa

$$ \mathbb{N} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R} \subset \mathbb{C} $$

| Conjunto | Contém | Exemplos |
|----------|--------|----------|
| **Naturais** $\mathbb{N}$ | $0, 1, 2, 3, \ldots$ | 5, 100, 0 |
| **Inteiros** $\mathbb{Z}$ | $\ldots, -2, -1, 0, 1, 2, \ldots$ | -3, 0, 7 |
| **Racionais** $\mathbb{Q}$ | $\frac{a}{b}$ com $a, b \in \mathbb{Z}, b \neq 0$ | $\frac{2}{3}, -\frac{5}{4}, 0{,}75$ |
| **Irracionais** $\mathbb{I}$ | Não podem ser $\frac{a}{b}$ | $\sqrt{2}, \pi, e$ |
| **Reais** $\mathbb{R}$ | $\mathbb{Q} \cup \mathbb{I}$ | Todos os acima |

## A Reta Real

A reta real é uma representação geométrica onde:
- Cada ponto corresponde a **exatamente um** número real
- Cada número real corresponde a **exatamente um** ponto
- Não há "buracos" ou lacunas

```
<---|----|----|----|----|----|----|----|----|----|----|----|----|--->
   -3   -2   -1    0   +1   +2   +3   √2   π    e
```

### Completude (Axioma da Supremo)

Todo conjunto não vazio de reais limitado superiormente tem um **supremo** (menor limitante superior). Essa propriedade é única dos reais e não vale para os racionais!

**Exemplo:** O conjunto $\{x \in \mathbb{Q} \mid x^2 < 2\}$ não tem supremo em $\mathbb{Q}$ (seria $\sqrt{2}$, que é irracional). Em $\mathbb{R}$, o supremo é $\sqrt{2}$.

## Comparação e Localização na Reta

### Ordem Total

Para quaisquer $a, b \in \mathbb{R}$, uma e apenas uma das seguintes é verdadeira:
$$ a < b, \quad a = b, \quad a > b $$

### Propriedades da Ordem

| Propriedade | Descrição |
|-------------|-----------|
| **Tricotomia** | $a < b$ ou $a = b$ ou $a > b$ |
| **Transitividade** | $a < b$ e $b < c$ → $a < c$ |
| **Adição** | $a < b$ → $a + c < b + c$ |
| **Multiplicação** | $a < b$ e $c > 0$ → $ac < bc$; $c < 0$ → $ac > bc$ |

## Intervalos na Reta Real

| Notação | Descrição | Representação |
|---------|-----------|---------------|
| $[a, b]$ | Fechado: $a \leq x \leq b$ | Inclui extremos |
| $(a, b)$ | Aberto: $a < x < b$ | Exclui extremos |
| $[a, b)$ | $a \leq x < b$ | Inclui $a$, exclui $b$ |
| $(a, b]$ | $a < x \leq b$ | Exclui $a$, inclui $b$ |
| $[a, \infty)$ | $x \geq a$ | Ilimitado superior |
| $(-\infty, b)$ | $x < b$ | Ilimitado inferior |
| $(-\infty, \infty)$ | Todos os reais | $\mathbb{R}$ inteiro |

## Exemplos

### Exemplo 1: Localização

Localize na reta real: $-2{,}5$, $\frac{3}{4}$, $\sqrt{2}$, $\pi$, $-\sqrt{3}$.

$$ -2{,}5 = -\frac{5}{2} $$
$$ \frac{3}{4} = 0{,}75 $$
$$ \sqrt{2} \approx 1{,}414 $$
$$ \pi \approx 3{,}142 $$
$$ -\sqrt{3} \approx -1{,}732 $$

Ordem crescente: $-2{,}5 < -\sqrt{3} < \frac{3}{4} < \sqrt{2} < \pi$

### Exemplo 2: Intervalo

Escreva o intervalo $-2 < x \leq 3$ em notação de intervalo.

$$ x \in (-2, 3] $$

### Exemplo 3: Completude

Mostre que $\sqrt{2}$ é o supremo de $A = \{x \in \mathbb{Q} \mid x^2 < 2\}$.

1. $\sqrt{2}$ é limitante superior: se $x \in A$, $x^2 < 2$, então $x < \sqrt{2}$ (para $x > 0$).
2. $\sqrt{2}$ é o menor: para qualquer $\epsilon > 0$, existe $x \in A$ tal que $\sqrt{2} - \epsilon < x$ (por densidade dos racionais).

**Resposta:** $\sqrt{2} = \sup(A)$ em $\mathbb{R}$, mas não existe em $\mathbb{Q}$.

### Exemplo 4: Densidade

Entre quaisquer dois reais $a < b$, existe:
- Um racional $q$ tal que $a < q < b$
- Um irracional $r$ tal que $a < r < b$

**Prova:** Seja $a < b$. Tome $n$ grande o suficiente tal que $\frac{1}{n} < b - a$. Então existe inteiro $m$ tal que $a < \frac{m}{n} < b$ (racional). Para irracional, adicione $\sqrt{2}/n$ a um racional adequado.

## Aplicações na Vida Real

- **Física:** medidas contínuas (tempo, espaço, massa) — teoricamente reais, na prática aproximadas
- **Engenharia:** tolerâncias, dimensões, precisão de máquinas
- **Economia:** taxas de câmbio, juros, preços (contínuos na teoria, discretos na prática)
- **GPS:** coordenadas (latitude, longitude, altitude) — valores reais contínuos
- **Música:** frequências (Hz) — contínuas, mas notas são discretas
- **Medicina:** medições (temperatura, pressão, glicose) — valores reais
- **Estatística:** distribuições contínuas (normal, exponencial) — definidas em $\mathbb{R}$
- **Computação:** números de ponto flutuante (aproximação finita dos reais)
- **Arquitetura:** proporções, medidas, escalas (contínuas na teoria)
- **Cosmologia:** distâncias, tempo, temperatura do universo — valores reais

## Problemas

### Nível 1 — Básico

**1.** Classifique os números: $-3$, $\frac{2}{3}$, $\sqrt{5}$, $0{,}\overline{7}$, $\pi$, $0$, $\sqrt{16}$.

**Resposta:**
- Naturais: $0$, $\sqrt{16} = 4$
- Inteiros: $-3$, $0$, $4$
- Racionais: $-3$, $\frac{2}{3}$, $0{,}\overline{7} = \frac{7}{9}$, $0$, $4$
- Irracionais: $\sqrt{5}$, $\pi$
- Reais: todos

**2.** Escreva em notação de intervalo: $x \geq -2$.

**Resposta:** $[-2, \infty)$

**3.** Escreva em notação de intervalo: $-1 < x < 5$.

**Resposta:** $(-1, 5)$

**4.** O número $\sqrt{4}$ é irracional? Justifique.

$$ \sqrt{4} = 2 = \frac{2}{1} \text{ (racional)} $$

**Resposta:** Não, é racional (inteiro).

**5.** Escreva o conjunto $\{x \in \mathbb{R} \mid -3 \leq x < 2\}$ em notação de intervalo.

**Resposta:** $[-3, 2)$

### Nível 2 — Intermediário

**6.** Prove que entre $\sqrt{2}$ e $\sqrt{3}$ existe um racional.

$$ \sqrt{2} \approx 1{,}414, \quad \sqrt{3} \approx 1{,}732 $$

$1{,}5 = \frac{3}{2}$ está entre eles: $1{,}414 < 1{,}5 < 1{,}732$.

**Resposta:** $\frac{3}{2} = 1{,}5$ é um racional entre $\sqrt{2}$ e $\sqrt{3}$.

**7.** Qual o supremo do conjunto $\{x \in \mathbb{R} \mid x < 3\}$? E o máximo?

Supremo: $3$ (menor limitante superior).
Máximo: não existe (nenhum elemento do conjunto é igual a 3).

**Resposta:** Supremo = 3. Máximo = não existe.

**8.** O conjunto $[0, 1]$ é limitado? Qual seu supremo e ínfimo? E máximo e mínimo?

Limitado: sim (entre 0 e 1).
Supremo = 1, Ínfimo = 0.
Máximo = 1 (pertence ao conjunto), Mínimo = 0 (pertence ao conjunto).

**Resposta:** Limitado. Supremo = 1, Ínfimo = 0, Máximo = 1, Mínimo = 0.

**9.** Mostre que $0{,}\overline{9} = 1$ usando a completude da reta real.

Seja $x = 0{,}\overline{9}$. Para qualquer $\epsilon > 0$, existe $n$ tal que $1 - 10^{-n} < x < 1$.
Mas $1 - 10^{-n} = 0{,}\underbrace{99\ldots9}_{n}$. Se $x < 1$, então $1 - x > 0$. Mas para qualquer $\epsilon > 0$, existe $n$ tal que $10^{-n} < \epsilon$, então $1 - x < \epsilon$. Logo $1 - x = 0$ (não pode ser positivo, senão seria maior que algum $10^{-n}$). Portanto $x = 1$.

**Resposta:** $0{,}\overline{9} = 1$ (prova usando completude/ordem dos reais).

**10.** Se $a < b$ são reais, quantos irracionais existem entre $a$ e $b$?

**Resposta:** Infinitos (os irracionais são densos na reta real).

### Nível 3 — Desafio

**11.** Prove que $\sqrt{2} + \sqrt{3}$ é irracional (sem usar a prova do arquivo anterior, use propriedades dos reais).

Suponha $\sqrt{2} + \sqrt{3} = r$ (racional). Considere o polinômio:
$$ (x - \sqrt{2} - \sqrt{3})(x - \sqrt{2} + \sqrt{3})(x + \sqrt{2} - \sqrt{3})(x + \sqrt{2} + \sqrt{3}) = 0 $$

Isso expande para:
$$ (x^2 - (\sqrt{2} + \sqrt{3})^2)(x^2 - (\sqrt{2} - \sqrt{3})^2) = 0 $$
$$ (x^2 - 5 - 2\sqrt{6})(x^2 - 5 + 2\sqrt{6}) = 0 $$
$$ (x^2 - 5)^2 - 24 = 0 $$
$$ x^4 - 10x^2 + 1 = 0 $$

Se $r$ é raiz racional, pelo teorema das raízes racionais, $r = \pm 1$. Mas $r = \sqrt{2} + \sqrt{3} \approx 3{,}146 \neq \pm 1$. Contradição! ✗

**Resposta:** $\sqrt{2} + \sqrt{3}$ é irracional (prova via polinômio e raízes racionais).

**12.** Se $A = \{x \in \mathbb{Q} \mid x^2 < 2\}$, qual é o supremo de $A$ em $\mathbb{R}$? E em $\mathbb{Q}$?

Em $\mathbb{R}$: $\sup(A) = \sqrt{2}$ (existe, é irracional).
Em $\mathbb{Q}$: não existe supremo (não há racional que seja o menor limitante superior — para qualquer racional $q > \sqrt{2}$, existe outro racional $r$ mais próximo de $\sqrt{2}$).

**Resposta:** Em $\mathbb{R}$: $\sqrt{2}$. Em $\mathbb{Q}$: não existe.

**13.** A união $\mathbb{Q} \cup \mathbb{I}$ é numerável? Explique.

$\mathbb{Q}$ é numerável (enumerável). $\mathbb{I}$ é não numerável (não enumerável, tem a cardinalidade do contínuo).
A união de um enumerável com um não enumerável é não enumerável.

**Resposta:** Não, $\mathbb{R} = \mathbb{Q} \cup \mathbb{I}$ é não numerável (cardinalidade do contínuo, $2^{\aleph_0}$).

---
**Fim — Números Reais**
