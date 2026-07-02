# Potenciação (Aprofundamento)

A **potenciação** é a operação de multiplicar um número por ele mesmo várias vezes. No aprofundamento, expandimos os expoentes para incluir **inteiros negativos** e **fracionários**, além de revisitar as propriedades fundamentais com maior rigor.

## Revisão: Potência com Expoente Natural

$$ a^n = \underbrace{a \times a \times \ldots \times a}_{n \text{ vezes}}, \quad a \in \mathbb{R}, \quad n \in \mathbb{N} $$

## Potências com Expoente Inteiro Negativo

### Definição

$$ a^{-n} = \frac{1}{a^n}, \quad a \neq 0 $$

### Por que essa definição?

Queremos que a propriedade $a^m \cdot a^n = a^{m+n}$ continue válida para inteiros negativos:

$$ a^n \cdot a^{-n} = a^{n + (-n)} = a^0 = 1 $$

$$ a^{-n} = \frac{1}{a^n} $$

### Exemplos

$$ 2^{-3} = \frac{1}{2^3} = \frac{1}{8} $$
$$ \left(\frac{2}{3}\right)^{-2} = \frac{1}{(2/3)^2} = \frac{1}{4/9} = \frac{9}{4} $$
$$ (-5)^{-1} = \frac{1}{-5} = -\frac{1}{5} $$
$$ \left(\frac{1}{2}\right)^{-1} = 2 $$

> **Importante:** $(-a)^{-n} = \frac{1}{(-a)^n}$ (o sinal depende da paridade de $n$).

### Potência Negativa de Fração

$$ \left(\frac{a}{b}\right)^{-n} = \left(\frac{b}{a}\right)^n = \frac{b^n}{a^n} $$

**Exemplo:**
$$ \left(\frac{3}{4}\right)^{-2} = \left(\frac{4}{3}\right)^2 = \frac{16}{9} $$

## Potências com Expoente Fracionário (Racional)

### Definição

$$ a^{\frac{m}{n}} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m, \quad a > 0 \text{ (ou } a \geq 0 \text{ se } n \text{ ímpar)} $$

### Por que essa definição?

Queremos que $(a^{\frac{1}{n}})^n = a^{\frac{1}{n} \cdot n} = a^1 = a$.

Logo $a^{\frac{1}{n}}$ é um número que, elevado a $n$, dá $a$ — exatamente a definição de raiz $n$-ésima!

### Exemplos

$$ 8^{\frac{1}{3}} = \sqrt[3]{8} = 2 $$
$$ 16^{\frac{3}{4}} = (\sqrt[4]{16})^3 = 2^3 = 8 $$
$$ 27^{-\frac{2}{3}} = \frac{1}{27^{\frac{2}{3}}} = \frac{1}{(\sqrt[3]{27})^2} = \frac{1}{3^2} = \frac{1}{9} $$
$$ \left(\frac{1}{4}\right)^{\frac{1}{2}} = \sqrt{\frac{1}{4}} = \frac{1}{2} $$

## Propriedades das Potências (Reais)

Para $a, b > 0$ (ou ajustes quando $a, b$ podem ser negativos) e $m, n \in \mathbb{R}$:

| Propriedade | Fórmula | Exemplo |
|-------------|---------|---------|
| **Produto** | $a^m \cdot a^n = a^{m+n}$ | $2^3 \cdot 2^{-2} = 2^{1} = 2$ |
| **Quociente** | $\frac{a^m}{a^n} = a^{m-n}$ | $\frac{2^5}{2^{-3}} = 2^{8} = 256$ |
| **Potência de Potência** | $(a^m)^n = a^{m \cdot n}$ | $(2^{-2})^{-3} = 2^{6} = 64$ |
| **Produto de Potências** | $(a \cdot b)^n = a^n \cdot b^n$ | $(2 \cdot 3)^{-2} = 2^{-2} \cdot 3^{-2} = \frac{1}{4} \cdot \frac{1}{9}$ |
| **Quociente de Potências** | $\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}$ | $\left(\frac{2}{3}\right)^{-2} = \frac{2^{-2}}{3^{-2}} = \frac{9}{4}$ |
| **Expoente Zero** | $a^0 = 1$ (para $a \neq 0$) | $5^0 = 1$, $(-3)^0 = 1$ |

### Cuidados com Bases Negativas

- $a^{\frac{m}{n}}$ com $a < 0$ só é definido quando $n$ é **ímpar** (pois raiz de índice par de número negativo não é real).
- $(-2)^{\frac{1}{2}} = \sqrt{-2}$ não é real.
- $(-2)^{\frac{1}{3}} = \sqrt[3]{-2} = -\sqrt[3]{2}$ é real.

## Exemplos

### Exemplo 1: Simplificação

$$ \frac{2^{-3} \cdot 2^5}{2^{-2}} = 2^{-3+5-(-2)} = 2^{4} = 16 $$

### Exemplo 2: Raiz como Potência

$$ \sqrt[3]{x^2} = x^{\frac{2}{3}} $$
$$ \frac{1}{\sqrt{x}} = x^{-\frac{1}{2}} $$

### Exemplo 3: Expressão com Expoentes Negativos

$$ \left(\frac{2^{-1} \cdot 3^2}{2^{-3} \cdot 3^{-1}}\right)^{-2} $$

Dentro do parêntesis:
$$ 2^{-1-(-3)} \cdot 3^{2-(-1)} = 2^{2} \cdot 3^{3} = 4 \cdot 27 = 108 $$

Elevado a $-2$:
$$ 108^{-2} = \frac{1}{108^2} = \frac{1}{11664} $$

### Exemplo 4: Equação com Expoentes

$$ 2^{x} = \frac{1}{32} $$

$$ \frac{1}{32} = \frac{1}{2^5} = 2^{-5} $$

$$ x = -5 $$

## Aplicações na Vida Real

- **Física:** decaimento radioativo ($N = N_0 \cdot 2^{-t/T}$), Lei de Coulomb ($F \propto r^{-2}$)
- **Química:** concentração de reagentes, pH ($[H^+] = 10^{-pH}$)
- **Biologia:** crescimento populacional (expoente negativo em decaimento)
- **Economia:** depreciação de bens, inflação acumulada, juros compostos
- **Engenharia:** atenuação de sinal, perda de carga, decaimento térmico
- **Computação:** memória (KB = $2^{10}$, MB = $2^{20}$), endereçamento, pixels
- **Astronomia:** magnitude estelar (escala logarítmica com expoentes negativos)
- **Medicina:** meia-vida de medicamentos, dosagem decay
- **Música:** equalização, decaimento de reverberação (expoentes negativos no tempo)
- **Estatística:** distribuição exponencial ($f(x) = \lambda e^{-\lambda x}$)

## Problemas

### Nível 1 — Básico

**1.** Calcule $2^{-4}$.

$$ 2^{-4} = \frac{1}{2^4} = \frac{1}{16} $$

**Resposta:** $\frac{1}{16}$.

**2.** Calcule $\left(\frac{3}{2}\right)^{-2}$.

$$ \left(\frac{3}{2}\right)^{-2} = \left(\frac{2}{3}\right)^2 = \frac{4}{9} $$

**Resposta:** $\frac{4}{9}$.

**3.** Escreva $\sqrt[3]{x^4}$ usando expoente fracionário.

$$ \sqrt[3]{x^4} = x^{\frac{4}{3}} $$

**Resposta:** $x^{\frac{4}{3}}$.

**4.** Calcule $8^{\frac{2}{3}}$.

$$ 8^{\frac{2}{3}} = (\sqrt[3]{8})^2 = 2^2 = 4 $$

**Resposta:** $4$.

**5.** Simplifique $x^{-3} \cdot x^5$.

$$ x^{-3} \cdot x^5 = x^{-3+5} = x^2 $$

**Resposta:** $x^2$.

### Nível 2 — Intermediário

**6.** Calcule $16^{-\frac{3}{4}}$.

$$ 16^{-\frac{3}{4}} = \frac{1}{16^{\frac{3}{4}}} = \frac{1}{(\sqrt[4]{16})^3} = \frac{1}{2^3} = \frac{1}{8} $$

**Resposta:** $\frac{1}{8}$.

**7.** Simplifique $\frac{3^{-2} \cdot 3^4}{3^{-1}}$.

$$ \frac{3^{-2} \cdot 3^4}{3^{-1}} = 3^{-2+4-(-1)} = 3^{3} = 27 $$

**Resposta:** $27$.

**8.** Escreva $\frac{1}{\sqrt[5]{x^3}}$ usando expoente.

$$ \frac{1}{\sqrt[5]{x^3}} = \frac{1}{x^{\frac{3}{5}}} = x^{-\frac{3}{5}} $$

**Resposta:** $x^{-\frac{3}{5}}$.

**9.** Resolva $5^{x} = \frac{1}{125}$.

$$ \frac{1}{125} = \frac{1}{5^3} = 5^{-3} $$
$$ x = -3 $$

**Resposta:** $x = -3$.

**10.** Calcule $\left(\frac{2^{-3} \cdot 4^2}{8^{-1}}\right)^{\frac{1}{2}}$.

$$ 4 = 2^2, \quad 8 = 2^3 $$
$$ \frac{2^{-3} \cdot (2^2)^2}{(2^3)^{-1}} = \frac{2^{-3} \cdot 2^4}{2^{-3}} = 2^{-3+4-(-3)} = 2^{4} = 16 $$
$$ 16^{\frac{1}{2}} = 4 $$

**Resposta:** $4$.

### Nível 3 — Desafio

**11.** Simplifique $\frac{2^{n+2} + 2^{n+1}}{2^{n-1}}$.

$$ 2^{n+2} + 2^{n+1} = 2^n \cdot 2^2 + 2^n \cdot 2^1 = 2^n(4 + 2) = 2^n \cdot 6 $$
$$ \frac{2^n \cdot 6}{2^{n-1}} = \frac{2^n \cdot 6}{2^n \cdot 2^{-1}} = 6 \cdot 2 = 12 $$

**Resposta:** $12$.

**12.** Resolva $3^{2x-1} = 27^{x+2}$.

$$ 27 = 3^3 $$
$$ 3^{2x-1} = (3^3)^{x+2} = 3^{3x+6} $$
$$ 2x - 1 = 3x + 6 $$
$$ -x = 7 $$
$$ x = -7 $$

**Resposta:** $x = -7$.

**13.** Se $a^{\frac{2}{3}} = 4$, encontre $a^{-\frac{1}{3}}$.

$$ a^{\frac{2}{3}} = 4 \implies (a^{\frac{1}{3}})^2 = 4 \implies a^{\frac{1}{3}} = 2 \text{ (ou } -2 \text{)} $$

$$ a^{-\frac{1}{3}} = \frac{1}{a^{\frac{1}{3}}} = \frac{1}{2} \text{ (ou } -\frac{1}{2} \text{)} $$

**Resposta:** $\frac{1}{2}$ (se $a^{\frac{1}{3}} = 2$) ou $-\frac{1}{2}$ (se $a^{\frac{1}{3}} = -2$).

---
**Fim — Potenciação (Aprofundamento)**
