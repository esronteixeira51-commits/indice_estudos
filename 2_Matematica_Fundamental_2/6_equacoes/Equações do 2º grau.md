# Equações do 2º Grau

Uma **equação do 2º grau** (ou equação quadrática) é uma equação que pode ser escrita na forma $ax^2 + bx + c = 0$, onde $a$, $b$ e $c$ são números reais e $a \neq 0$. É uma das equações mais importantes da matemática, com aplicações em praticamente todas as áreas do conhecimento.

## Forma Geral

$$ ax^2 + bx + c = 0, \quad a \neq 0 $$

## Fórmula de Bhaskara (Fórmula Resolutiva)

$$ x = \frac{-b \pm \sqrt{\Delta}}{2a} $$

Onde **delta** (discriminante) é:

$$ \Delta = b^2 - 4ac $$

## O Discriminante e o Número de Raízes

| Discriminante | Número de raízes reais | Tipo |
|---------------|------------------------|------|
| $\Delta > 0$ | 2 raízes distintas | $x_1 = \frac{-b + \sqrt{\Delta}}{2a}$, $x_2 = \frac{-b - \sqrt{\Delta}}{2a}$ |
| $\Delta = 0$ | 1 raiz real (dupla) | $x = \frac{-b}{2a}$ |
| $\Delta < 0$ | 0 raízes reais | 2 raízes complexas conjugadas |

## Relações de Girard (Soma e Produto das Raízes)

Se $x_1$ e $x_2$ são as raízes de $ax^2 + bx + c = 0$:

$$ x_1 + x_2 = -\frac{b}{a} \quad \text{(soma)} $$
$$ x_1 \cdot x_2 = \frac{c}{a} \quad \text{(produto)} $$

### Verificação

$$ x_1 + x_2 = \frac{-b + \sqrt{\Delta}}{2a} + \frac{-b - \sqrt{\Delta}}{2a} = \frac{-2b}{2a} = -\frac{b}{a} $$

$$ x_1 \cdot x_2 = \frac{(-b)^2 - (\sqrt{\Delta})^2}{4a^2} = \frac{b^2 - (b^2 - 4ac)}{4a^2} = \frac{4ac}{4a^2} = \frac{c}{a} $$

## Casos Especiais

### $b = 0$ (equação incompleta: $ax^2 + c = 0$)

$$ ax^2 = -c $$
$$ x^2 = -\frac{c}{a} $$
$$ x = \pm \sqrt{-\frac{c}{a}} $$

> Requer $-\frac{c}{a} \geq 0$ para raízes reais.

**Exemplo:**
$$ x^2 - 9 = 0 \implies x^2 = 9 \implies x = \pm 3 $$

### $c = 0$ (equação incompleta: $ax^2 + bx = 0$)

$$ x(ax + b) = 0 $$
$$ x = 0 \quad \text{ou} \quad ax + b = 0 $$
$$ x = 0 \quad \text{ou} \quad x = -\frac{b}{a} $$

**Exemplo:**
$$ x^2 - 5x = 0 \implies x(x - 5) = 0 \implies x = 0 \text{ ou } x = 5 $$

### $b = c = 0$ (equação: $ax^2 = 0$)

$$ x = 0 \quad \text{(raiz dupla)} $$

## Fatoração de Trinômio do 2º Grau

Se $\Delta \geq 0$ e as raízes são $x_1$ e $x_2$:

$$ ax^2 + bx + c = a(x - x_1)(x - x_2) $$

## Exemplos

### Exemplo 1: Duas raízes reais

$$ x^2 - 5x + 6 = 0 $$
$$ \Delta = 25 - 24 = 1 $$
$$ x = \frac{5 \pm 1}{2} $$
$$ x_1 = 3, \quad x_2 = 2 $$

Verificação: $3 + 2 = 5 = -(-5)/1$ ✓, $3 \cdot 2 = 6 = 6/1$ ✓

### Exemplo 2: Raiz dupla

$$ x^2 - 6x + 9 = 0 $$
$$ \Delta = 36 - 36 = 0 $$
$$ x = \frac{6}{2} = 3 $$

$$ x^2 - 6x + 9 = (x - 3)^2 $$

### Exemplo 3: Sem raízes reais

$$ x^2 + x + 1 = 0 $$
$$ \Delta = 1 - 4 = -3 < 0 $$

Sem raízes reais. (Em complexos: $x = \frac{-1 \pm i\sqrt{3}}{2}$)

### Exemplo 4: Com frações

$$ 2x^2 - 3x - 2 = 0 $$
$$ \Delta = 9 + 16 = 25 $$
$$ x = \frac{3 \pm 5}{4} $$
$$ x_1 = 2, \quad x_2 = -\frac{1}{2} $$

### Exemplo 5: Usando soma e produto sem Bhaskara

$$ x^2 - 7x + 12 = 0 $$

Soma = 7, Produto = 12. Procurar dois números que somam 7 e multiplicam 12: 3 e 4.

$$ x^2 - 7x + 12 = (x - 3)(x - 4) = 0 \implies x = 3 \text{ ou } x = 4 $$

## Aplicações na Vida Real

- **Física:** queda livre, lançamento de projéteis ($h = h_0 + v_0t - \frac{1}{2}gt^2$)
- **Economia:** maximização de lucro, ponto de equilíbrio
- **Engenharia:** deflexão de vigas, otimização de estruturas
- **Geometria:** área do retângulo, teorema de Pitágoras (algumas formas)
- **Finanças:** juros compostos, valor presente
- **Biologia:** modelos de crescimento populacional (logístico)
- **Medicina:** concentração de medicamentos no tempo
- **Química:** equilíbrio químico, velocidade de reação
- **Estatística:** regressão quadrática, ajuste de curvas
- **Jogos:** trajetórias parabólicas, saltos, projéteis

## Problemas

### Nível 1 — Básico

**1.** Resolva $x^2 - 5x + 6 = 0$.

$$ \Delta = 25 - 24 = 1 $$
$$ x = \frac{5 \pm 1}{2} \implies x = 3 \text{ ou } x = 2 $$

**Resposta:** $x = 2$ ou $x = 3$.

**2.** Resolva $x^2 - 9 = 0$.

$$ x^2 = 9 \implies x = \pm 3 $$

**Resposta:** $x = -3$ ou $x = 3$.

**3.** Resolva $x^2 - 4x = 0$.

$$ x(x - 4) = 0 \implies x = 0 \text{ ou } x = 4 $$

**Resposta:** $x = 0$ ou $x = 4$.

**4.** Determine o discriminante de $x^2 + 2x + 5 = 0$ e classifique as raízes.

$$ \Delta = 4 - 20 = -16 < 0 $$

**Resposta:** Não há raízes reais (duas raízes complexas).

**5.** Se $x_1$ e $x_2$ são raízes de $x^2 - 8x + 15 = 0$, calcule $x_1 + x_2$ e $x_1 \cdot x_2$ sem resolver a equação.

$$ x_1 + x_2 = -(-8)/1 = 8 $$
$$ x_1 \cdot x_2 = 15/1 = 15 $$

**Resposta:** Soma = 8, Produto = 15.

### Nível 2 — Intermediário

**6.** Resolva $2x^2 - 7x + 3 = 0$.

$$ \Delta = 49 - 24 = 25 $$
$$ x = \frac{7 \pm 5}{4} \implies x = 3 \text{ ou } x = \frac{1}{2} $$

**Resposta:** $x = \frac{1}{2}$ ou $x = 3$.

**7.** Resolva $x^2 + x + 1 = 0$.

$$ \Delta = 1 - 4 = -3 < 0 $$

**Resposta:** Sem raízes reais.

**8.** Se $x_1 + x_2 = 6$ e $x_1 \cdot x_2 = 8$, escreva a equação do 2º grau que tem $x_1$ e $x_2$ como raízes.

$$ x^2 - (x_1 + x_2)x + x_1 x_2 = 0 $$
$$ x^2 - 6x + 8 = 0 $$

**Resposta:** $x^2 - 6x + 8 = 0$.

**9.** Um retângulo tem perímetro 20 e área 21. Quais são suas dimensões?

$$ 2(\ell + w) = 20 \implies \ell + w = 10 $$
$$ \ell \cdot w = 21 $$

São raízes de $x^2 - 10x + 21 = 0$:
$$ \Delta = 100 - 84 = 16 $$
$$ x = \frac{10 \pm 4}{2} \implies x = 7 \text{ ou } x = 3 $$

**Resposta:** 7 e 3 (comprimento e largura).

**10.** Determine $m$ para que $x^2 - 4x + m = 0$ tenha raiz dupla.

$$ \Delta = 16 - 4m = 0 \implies m = 4 $$

**Resposta:** $m = 4$.

### Nível 3 — Desafio

**11.** Se $x_1$ e $x_2$ são raízes de $x^2 + px + q = 0$, encontre $x_1^2 + x_2^2$ em função de $p$ e $q$.

$$ x_1 + x_2 = -p, \quad x_1 x_2 = q $$
$$ x_1^2 + x_2^2 = (x_1 + x_2)^2 - 2x_1 x_2 = p^2 - 2q $$

**Resposta:** $x_1^2 + x_2^2 = p^2 - 2q$.

**12.** A soma de um número e seu inverso é $\frac{10}{3}$. Qual é o número?

$$ x + \frac{1}{x} = \frac{10}{3} $$
$$ 3x^2 + 3 = 10x $$
$$ 3x^2 - 10x + 3 = 0 $$
$$ \Delta = 100 - 36 = 64 $$
$$ x = \frac{10 \pm 8}{6} \implies x = 3 \text{ ou } x = \frac{1}{3} $$

**Resposta:** $x = 3$ ou $x = \frac{1}{3}$ (que são inversos um do outro!).

**13.** Uma bola é lançada verticalmente de uma altura de 20 m com velocidade inicial de 15 m/s. A altura em função do tempo é $h(t) = 20 + 15t - 5t^2$. Quando a bola toca o solo? Qual a altura máxima atingida?

**Toca o solo:** $h(t) = 0$
$$ 20 + 15t - 5t^2 = 0 $$
$$ -5t^2 + 15t + 20 = 0 $$
$$ t^2 - 3t - 4 = 0 $$
$$ (t - 4)(t + 1) = 0 $$
$$ t = 4 \text{ s} \quad (t = -1 \text{ não faz sentido}) $$

**Altura máxima:** Vértice da parábola em $t = -b/(2a) = -15/(2(-5)) = 1{,}5$ s
$$ h(1{,}5) = 20 + 15(1{,}5) - 5(1{,}5)^2 = 20 + 22{,}5 - 11{,}25 = 31{,}25 \text{ m} $$

**Resposta:** Toca o solo em 4 s. Altura máxima: 31,25 m.

---
**Fim — Equações do 2º Grau**
