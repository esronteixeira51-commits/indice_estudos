# Radiciação (Aprofundamento)

A **radiciação** é a operação inversa da potenciação. Dado um número $a$ e um índice $n$, a raiz $n$-ésima de $a$ é o número que, elevado a $n$, resulta em $a$. No aprofundamento, estudamos raízes de índice qualquer, simplificação, operações e racionalização.

## Raiz Enésima

### Definição

$$ \sqrt[n]{a} = b \iff b^n = a $$

Onde:
- $n$ = **índice** (grau da raiz), $n \in \mathbb{N}$, $n \geq 2$
- $a$ = **radicando**
- $b$ = **raiz**

### Condições de Existência

| Índice | Radicando | Raiz | Exemplo |
|--------|-----------|------|---------|
| $n$ **par** | $a \geq 0$ | $b \geq 0$ (raiz principal) | $\sqrt{4} = 2$ (não $-2$) |
| $n$ **par** | $a < 0$ | **Não existe** em $\mathbb{R}$ | $\sqrt{-4}$ não é real |
| $n$ **ímpar** | $a \in \mathbb{R}$ (qualquer) | $b$ tem mesmo sinal de $a$ | $\sqrt[3]{-8} = -2$ |

> **Raiz quadrada:** $\sqrt{a}$ (índice 2, omitido)
> **Raiz cúbica:** $\sqrt[3]{a}$ (índice 3)

### Propriedades

$$ \sqrt[n]{a \cdot b} = \sqrt[n]{a} \cdot \sqrt[n]{b} \quad (a, b \geq 0 \text{ se } n \text{ par}) $$
$$ \sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}} \quad (b \neq 0) $$
$$ \sqrt[n]{a^m} = (\sqrt[n]{a})^m = a^{\frac{m}{n}} $$
$$ \sqrt[m]{\sqrt[n]{a}} = \sqrt[m \cdot n]{a} $$
$$ \sqrt[n]{a^n} = |a| \text{ se } n \text{ par}, = a \text{ se } n \text{ ímpar} $$

## Simplificação de Radicais

### Fatoração do Radicando

Decompor o radicando em fatores primos e extrair potências que coincidam com o índice.

**Exemplo:**
$$ \sqrt{72} = \sqrt{2^3 \cdot 3^2} = \sqrt{2^2 \cdot 2 \cdot 3^2} = 2 \cdot 3 \cdot \sqrt{2} = 6\sqrt{2} $$

**Exemplo:**
$$ \sqrt[3]{81} = \sqrt[3]{3^4} = \sqrt[3]{3^3 \cdot 3} = 3\sqrt[3]{3} $$

### Redução ao Mesmo Índice

$$ \sqrt[n]{a} = \sqrt[n \cdot m]{a^m} $$

**Exemplo:**
$$ \sqrt{2} = \sqrt[6]{2^3} = \sqrt[6]{8} $$
$$ \sqrt[3]{3} = \sqrt[6]{3^2} = \sqrt[6]{9} $$

## Operações com Radicais

### Adição e Subtração

Só podemos somar radicais **semelhantes** (mesmo índice e mesmo radicando após simplificação).

$$ 3\sqrt{2} + 5\sqrt{2} = 8\sqrt{2} $$
$$ 7\sqrt{3} - 2\sqrt{3} = 5\sqrt{3} $$

**Não semelhantes:**
$$ \sqrt{2} + \sqrt{3} \text{ (não pode simplificar)} $$

**Após simplificar podem tornar-se semelhantes:**
$$ \sqrt{8} + \sqrt{2} = 2\sqrt{2} + \sqrt{2} = 3\sqrt{2} $$

### Multiplicação e Divisão

Mesmo índice:
$$ \sqrt[n]{a} \cdot \sqrt[n]{b} = \sqrt[n]{a \cdot b} $$
$$ \frac{\sqrt[n]{a}}{\sqrt[n]{b}} = \sqrt[n]{\frac{a}{b}} $$

Índices diferentes: reduzir ao mesmo índice primeiro.

$$ \sqrt{2} \cdot \sqrt[3]{3} = \sqrt[6]{2^3} \cdot \sqrt[6]{3^2} = \sqrt[6]{8 \cdot 9} = \sqrt[6]{72} $$

## Racionalização de Denominadores

Eliminar radicais do denominador de uma fração.

### Tipo 1: Denominador com $\sqrt{a}$

$$ \frac{1}{\sqrt{a}} = \frac{1}{\sqrt{a}} \cdot \frac{\sqrt{a}}{\sqrt{a}} = \frac{\sqrt{a}}{a} $$

**Exemplo:**
$$ \frac{3}{\sqrt{2}} = \frac{3\sqrt{2}}{2} $$

### Tipo 2: Denominador com $a \pm \sqrt{b}$

Multiplicar pelo conjugado $a \mp \sqrt{b}$:

$$ \frac{1}{a + \sqrt{b}} = \frac{1}{a + \sqrt{b}} \cdot \frac{a - \sqrt{b}}{a - \sqrt{b}} = \frac{a - \sqrt{b}}{a^2 - b} $$

**Exemplo:**
$$ \frac{2}{3 + \sqrt{5}} = \frac{2(3 - \sqrt{5})}{(3 + \sqrt{5})(3 - \sqrt{5})} = \frac{2(3 - \sqrt{5})}{9 - 5} = \frac{2(3 - \sqrt{5})}{4} = \frac{3 - \sqrt{5}}{2} $$

### Tipo 3: Denominador com $\sqrt{a} \pm \sqrt{b}$

Multiplicar pelo conjugado $\sqrt{a} \mp \sqrt{b}$:

$$ \frac{1}{\sqrt{2} + \sqrt{3}} = \frac{\sqrt{2} - \sqrt{3}}{(\sqrt{2} + \sqrt{3})(\sqrt{2} - \sqrt{3})} = \frac{\sqrt{2} - \sqrt{3}}{2 - 3} = \frac{\sqrt{2} - \sqrt{3}}{-1} = \sqrt{3} - \sqrt{2} $$

### Tipo 4: Denominador com raiz cúbica

Usar fatoração $a^3 \pm b^3 = (a \pm b)(a^2 \mp ab + b^2)$:

$$ \frac{1}{\sqrt[3]{a}} = \frac{\sqrt[3]{a^2}}{a} $$

$$ \frac{1}{1 + \sqrt[3]{2}} = \frac{1 - \sqrt[3]{2} + \sqrt[3]{4}}{(1 + \sqrt[3]{2})(1 - \sqrt[3]{2} + \sqrt[3]{4})} = \frac{1 - \sqrt[3]{2} + \sqrt[3]{4}}{1 + 2} = \frac{1 - \sqrt[3]{2} + \sqrt[3]{4}}{3} $$

## Exemplos

### Exemplo 1: Simplificação

$$ \sqrt{50} = \sqrt{25 \cdot 2} = 5\sqrt{2} $$
$$ \sqrt[3]{40} = \sqrt[3]{8 \cdot 5} = 2\sqrt[3]{5} $$
$$ \sqrt[4]{162} = \sqrt[4]{81 \cdot 2} = 3\sqrt[4]{2} $$

### Exemplo 2: Operações

$$ \sqrt{12} + \sqrt{27} - \sqrt{3} = 2\sqrt{3} + 3\sqrt{3} - \sqrt{3} = 4\sqrt{3} $$

$$ \sqrt{2} \cdot \sqrt[4]{8} = 2^{\frac{1}{2}} \cdot 2^{\frac{3}{4}} = 2^{\frac{5}{4}} = 2 \cdot \sqrt[4]{2} $$

### Exemplo 3: Racionalização

$$ \frac{5}{\sqrt{5} - \sqrt{3}} = \frac{5(\sqrt{5} + \sqrt{3})}{(\sqrt{5} - \sqrt{3})(\sqrt{5} + \sqrt{3})} = \frac{5(\sqrt{5} + \sqrt{3})}{5 - 3} = \frac{5(\sqrt{5} + \sqrt{3})}{2} $$

## Aplicações na Vida Real

- **Física:** velocidade, aceleração, energia cinética ($E = \frac{1}{2}mv^2$), queda livre ($v = \sqrt{2gh}$)
- **Engenharia:** tensão de ruptura, dimensionamento de estruturas (teorema de Pitágoras generalizado)
- **Química:** velocidade de reação, concentração, pH ($pH = -\log[H^+]$ envolve log, mas raízes aparecem em fórmulas de estado)
- **Biologia:** taxa metabólica, superfície corporal ($\sqrt{altura \times peso}$ em fórmulas aproximadas)
- **Geografia:** distância euclidiana, distância entre cidades (fórmula de Haversine)
- **Astronomia:** distância de estrelas, leis de Kepler (período orbital)
- **Economia:** volatilidade (desvio padrão = raiz quadrada da variância), risco de investimentos
- **Medicina:** cálculo de doses, índice de massa corporal, dosagem por superfície corporal
- **Arquitetura:** proporções áureas, diagonais, escalas, perspectiva
- **Computação:** normalização de vetores, distância entre pontos, machine learning (normas L2)

## Problemas

### Nível 1 — Básico

**1.** Simplifique $\sqrt{48}$.

$$ \sqrt{48} = \sqrt{16 \cdot 3} = 4\sqrt{3} $$

**Resposta:** $4\sqrt{3}$.

**2.** Calcule $\sqrt[3]{-27}$.

$$ \sqrt[3]{-27} = -3 \quad \text{(pois } (-3)^3 = -27 \text{)} $$

**Resposta:** $-3$.

**3.** Calcule $\sqrt{2} \cdot \sqrt{8}$.

$$ \sqrt{2 \cdot 8} = \sqrt{16} = 4 $$

**Resposta:** $4$.

**4.** Racionalize $\frac{1}{\sqrt{3}}$.

$$ \frac{1}{\sqrt{3}} = \frac{\sqrt{3}}{3} $$

**Resposta:** $\frac{\sqrt{3}}{3}$.

**5.** Simplifique $\sqrt{8} + \sqrt{2}$.

$$ 2\sqrt{2} + \sqrt{2} = 3\sqrt{2} $$

**Resposta:** $3\sqrt{2}$.

### Nível 2 — Intermediário

**6.** Racionalize $\frac{3}{2 + \sqrt{5}}$.

$$ \frac{3}{2 + \sqrt{5}} \cdot \frac{2 - \sqrt{5}}{2 - \sqrt{5}} = \frac{3(2 - \sqrt{5})}{4 - 5} = \frac{3(2 - \sqrt{5})}{-1} = 3(\sqrt{5} - 2) $$

**Resposta:** $3(\sqrt{5} - 2)$ ou $3\sqrt{5} - 6$.

**7.** Simplifique $\sqrt[3]{16} + \sqrt[3]{54}$.

$$ \sqrt[3]{16} = \sqrt[3]{8 \cdot 2} = 2\sqrt[3]{2} $$
$$ \sqrt[3]{54} = \sqrt[3]{27 \cdot 2} = 3\sqrt[3]{2} $$
$$ 2\sqrt[3]{2} + 3\sqrt[3]{2} = 5\sqrt[3]{2} $$

**Resposta:** $5\sqrt[3]{2}$.

**8.** Racionalize $\frac{1}{\sqrt{7} - \sqrt{2}}$.

$$ \frac{1}{\sqrt{7} - \sqrt{2}} \cdot \frac{\sqrt{7} + \sqrt{2}}{\sqrt{7} + \sqrt{2}} = \frac{\sqrt{7} + \sqrt{2}}{7 - 2} = \frac{\sqrt{7} + \sqrt{2}}{5} $$

**Resposta:** $\frac{\sqrt{7} + \sqrt{2}}{5}$.

**9.** Calcule $\sqrt{2} \cdot \sqrt[3]{4}$.

Reduzir ao mesmo índice (6):
$$ \sqrt{2} = 2^{\frac{1}{2}} = 2^{\frac{3}{6}} = \sqrt[6]{2^3} = \sqrt[6]{8} $$
$$ \sqrt[3]{4} = 4^{\frac{1}{3}} = (2^2)^{\frac{1}{3}} = 2^{\frac{2}{3}} = 2^{\frac{4}{6}} = \sqrt[6]{2^4} = \sqrt[6]{16} $$
$$ \sqrt[6]{8 \cdot 16} = \sqrt[6]{128} = \sqrt[6]{2^7} = 2\sqrt[6]{2} $$

**Resposta:** $2\sqrt[6]{2}$.

**10.** Simplifique $\sqrt{50} - \sqrt{18} + \sqrt{8}$.

$$ 5\sqrt{2} - 3\sqrt{2} + 2\sqrt{2} = 4\sqrt{2} $$

**Resposta:** $4\sqrt{2}$.

### Nível 3 — Desafio

**11.** Racionalize $\frac{1}{\sqrt[3]{2} - 1}$.

Usar $a^3 - b^3 = (a-b)(a^2 + ab + b^2)$ com $a = \sqrt[3]{2}$, $b = 1$:

$$ \frac{1}{\sqrt[3]{2} - 1} \cdot \frac{\sqrt[3]{4} + \sqrt[3]{2} + 1}{\sqrt[3]{4} + \sqrt[3]{2} + 1} = \frac{\sqrt[3]{4} + \sqrt[3]{2} + 1}{2 - 1} = \sqrt[3]{4} + \sqrt[3]{2} + 1 $$

**Resposta:** $\sqrt[3]{4} + \sqrt[3]{2} + 1$.

**12.** Se $\sqrt{x} + \frac{1}{\sqrt{x}} = 3$, encontre $x + \frac{1}{x}$.

Eleve ao quadrado:
$$ \left(\sqrt{x} + \frac{1}{\sqrt{x}}\right)^2 = 9 $$
$$ x + 2 \cdot \sqrt{x} \cdot \frac{1}{\sqrt{x}} + \frac{1}{x} = 9 $$
$$ x + 2 + \frac{1}{x} = 9 $$
$$ x + \frac{1}{x} = 7 $$

**Resposta:** $7$.

**13.** Simplifique $\frac{\sqrt{6} + \sqrt{2}}{\sqrt{6} - \sqrt{2}}$.

$$ \frac{\sqrt{6} + \sqrt{2}}{\sqrt{6} - \sqrt{2}} \cdot \frac{\sqrt{6} + \sqrt{2}}{\sqrt{6} + \sqrt{2}} = \frac{(\sqrt{6} + \sqrt{2})^2}{6 - 2} = \frac{6 + 2\sqrt{12} + 2}{4} = \frac{8 + 4\sqrt{3}}{4} = 2 + \sqrt{3} $$

**Resposta:** $2 + \sqrt{3}$.

---
**Fim — Radiciação (Aprofundamento)**
