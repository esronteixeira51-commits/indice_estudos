# Números Irracionais

Os **números irracionais** são números reais que **não podem** ser expressos como uma fração $\frac{a}{b}$ onde $a$ e $b$ são inteiros e $b \neq 0$. Eles preenchem as "lacunas" entre os racionais na reta numérica, completando o conjunto dos números reais.

## Definição

Um número é **irracional** se não pode ser escrito como razão de dois inteiros. Sua representação decimal é:
- **Infinita** (não termina)
- **Não periódica** (não tem um padrão repetitivo)

## Exemplos Clássicos

### 1. $\sqrt{2}$ — Raiz Quadrada de 2

$$ \sqrt{2} \approx 1{,}41421356\ldots $$

**Prova de irracionalidade (por contradição):**

Suponha $\sqrt{2} = \frac{a}{b}$ com $a, b$ inteiros, $MDC(a, b) = 1$.

$$ 2 = \frac{a^2}{b^2} \implies a^2 = 2b^2 $$

Logo $a^2$ é par, então $a$ é par. Seja $a = 2k$:

$$ (2k)^2 = 2b^2 \implies 4k^2 = 2b^2 \implies 2k^2 = b^2 $$

Logo $b^2$ é par, então $b$ é par. Mas $a$ e $b$ são ambos pares, contradizendo $MDC(a, b) = 1$. ✗

**Conclusão:** $\sqrt{2}$ é irracional.

### 2. $\pi$ — Pi

$$ \pi \approx 3{,}14159265\ldots $$

Razão entre a circunferência e o diâmetro de qualquer círculo. Provar que $\pi$ é irracional é difícil (demonstrado por Lambert em 1761).

### 3. $e$ — Número de Euler

$$ e \approx 2{,}71828182\ldots $$

Base do logaritmo natural. Aparece em crescimento exponencial, juros compostos, probabilidade. Irracionalidade provada por Euler.

### 4. $\phi$ (Phi) — Proporção Áurea

$$ \phi = \frac{1 + \sqrt{5}}{2} \approx 1{,}61803399\ldots $$

Irracional porque contém $\sqrt{5}$.

### 5. Logaritmos de inteiros (em bases racionais)

$$ \log_2 3, \quad \log_{10} 2, \quad \ln 2 $$

São irracionais (na maioria dos casos).

## Diferença entre Racionais e Irracionais

| Característica | Racional | Irracional |
|----------------|----------|------------|
| Forma fração | Sim ($\frac{a}{b}$) | Não |
| Decimal | Finita ou periódica | Infinita e não periódica |
| Padrão | Repetição | Sem padrão |
| Exemplos | $\frac{1}{2}, \frac{3}{7}, 0{,}75$ | $\sqrt{2}, \pi, e$ |
| Densidade na reta | Sim, mas com "buracos" | Preenche os buracos |

## Aproximações Racionais

Como os irracionais não têm representação exata em decimal, usamos **aproximações**:

| Irracional | Aproximação | Precisão |
|------------|-------------|----------|
| $\sqrt{2}$ | $\frac{99}{70} \approx 1{,}4142857$ | 4 casas decimais |
| $\pi$ | $\frac{22}{7} \approx 3{,}142857$ | 2 casas decimais |
| $\pi$ | $\frac{355}{113} \approx 3{,}1415929$ | 6 casas decimais |
| $e$ | $\frac{19}{7} \approx 2{,}714$ | 2 casas decimais |
| $\phi$ | $\frac{13}{8} = 1{,}625$ | 2 casas decimais |

> **Importante:** Aproximações racionais são sempre **imprecisas** para irracionais! O erro nunca é zero.

## Aplicações na Vida Real

- **Geometria:** diagonal do quadrado de lado 1 = $\sqrt{2}$; circunferência do círculo = $\pi \times d$
- **Física:** frequências naturais, ressonância, ondas (aparecem $\pi$ e $\sqrt{2}$)
- **Engenharia:** estruturas com proporção áurea ($\phi$)
- **Arte e arquitetura:** Partenon, Mona Lisa (proporção áurea)
- **Natureza:** espiral de Fibonacci (converge para $\phi$), arranjo de folhas, conchas
- **Finanças:** crescimento exponencial ($e$), juros compostos contínuos
- **Estatística:** distribuição normal (aparece $\pi$ e $e$)
- **Música:** frequências de notas, oitavas, intervalos (logaritmos)
- **Computação:** algoritmos de geração de números pseudoaleatórios
- **Cosmologia:** constantes fundamentais ($\pi$, $e$ em fórmulas)

## Problemas

### Nível 1 — Básico

**1.** Classifique como racional ou irracional: $\frac{3}{4}$, $\sqrt{3}$, $0{,}\overline{6}$, $\pi$, $-5$, $\sqrt{25}$.

**Resposta:** Racionais: $\frac{3}{4}$, $0{,}\overline{6} = \frac{2}{3}$, $-5$, $\sqrt{25} = 5$. Irracionais: $\sqrt{3}$, $\pi$.

**2.** $\sqrt{9}$ é irracional? Justifique.

$$ \sqrt{9} = 3 = \frac{3}{1} \text{ (inteiro, portanto racional)} $$

**Resposta:** Não, $\sqrt{9} = 3$ é racional (inteiro).

**3.** Explique por que $\sqrt{2} + \sqrt{2} = 2\sqrt{2}$ é irracional.

Se $2\sqrt{2}$ fosse racional, então $\sqrt{2} = \frac{\text{racional}}{2}$ seria racional. Contradição!

**Resposta:** $2\sqrt{2}$ é irracional (produto de racional não-nulo e irracional é irracional).

**4.** Escreva $\pi$ com 5 casas decimais.

**Resposta:** $\pi \approx 3{,}14159$

**5.** A fração $\frac{22}{7}$ é igual a $\pi$? Explique.

$$ \frac{22}{7} \approx 3{,}142857\ldots \neq 3{,}141592\ldots = \pi $$

**Resposta:** Não é igual. É uma **aproximação** (diferença ≈ 0,00126...).

### Nível 2 — Intermediário

**6.** Prove que $\sqrt{3}$ é irracional (adaptando a prova de $\sqrt{2}$).

Suponha $\sqrt{3} = \frac{a}{b}$ com $MDC(a, b) = 1$.
$$ 3b^2 = a^2 $$
Logo $a^2$ é múltiplo de 3, então $a$ é múltiplo de 3. Seja $a = 3k$:
$$ 3b^2 = 9k^2 \implies b^2 = 3k^2 $$
Logo $b$ é múltiplo de 3. Contradição: $a$ e $b$ ambos múltiplos de 3, mas $MDC(a, b) = 1$. ✗

**Resposta:** Prova por contradição adaptada (usando primalidade de 3).

**7.** O número $0{,}101001000100001\ldots$ (padrão: 1, 0, 1, 00, 1, 000, 1, 0000...) é racional ou irracional? Justifique.

O padrão é 1, depois 0, depois 1, depois 00, depois 1, depois 000... O número de zeros entre os 1s cresce: 1, 2, 3, 4, ... Não há repetição periódica! A lacuna entre os 1s aumenta indefinidamente.

**Resposta:** Irracional (decimal infinita não periódica).

**8.** Calcule a diagonal de um quadrado de lado 3 cm. O resultado é racional ou irracional?

$$ d = 3\sqrt{2} \text{ cm} \approx 4{,}24 \text{ cm} $$

**Resposta:** Irracional ($3\sqrt{2}$ cm). Aproximadamente 4,24 cm.

**9.** Se $x$ é irracional, $x^2$ é sempre irracional? Dê um contraexemplo ou prove.

Contraexemplo: $x = \sqrt{2}$ é irracional, mas $x^2 = 2$ é racional!

**Resposta:** Não é sempre irracional. Contraexemplo: $(\sqrt{2})^2 = 2$ (racional).

**10.** Qual é a área de um círculo de raio 1? O resultado é racional ou irracional?

$$ A = \pi \times 1^2 = \pi $$

**Resposta:** Irracional ($\pi$ unidades de área).

### Nível 3 — Desafio

**11.** Prove que $\sqrt{2} + \sqrt{3}$ é irracional.

Suponha $\sqrt{2} + \sqrt{3} = r$ (racional).
$$ (\sqrt{2} + \sqrt{3})^2 = r^2 $$
$$ 2 + 2\sqrt{6} + 3 = r^2 $$
$$ 2\sqrt{6} = r^2 - 5 $$
$$ \sqrt{6} = \frac{r^2 - 5}{2} $$

Como $r$ é racional, $\frac{r^2 - 5}{2}$ é racional. Logo $\sqrt{6}$ seria racional. Mas $\sqrt{6}$ é irracional (prova similar a $\sqrt{2}$). Contradição! ✗

**Resposta:** $\sqrt{2} + \sqrt{3}$ é irracional (prova por contradição).

**12.** Quantos números irracionais existem entre 0 e 1? E entre 1 e 2?

**Resposta:** Infinitos em ambos os intervalos (de fato, mais irracionais que racionais em qualquer intervalo — os irracionais são "não enumeráveis", enquanto os racionais são "enumeráveis").

**13.** O número $\sqrt[3]{2}$ (raiz cúbica de 2) é irracional? Prove ou refute.

Suponha $\sqrt[3]{2} = \frac{a}{b}$ com $MDC(a, b) = 1$.
$$ 2 = \frac{a^3}{b^3} \implies a^3 = 2b^3 $$
Logo $a^3$ é par, então $a$ é par. Seja $a = 2k$:
$$ 8k^3 = 2b^3 \implies 4k^3 = b^3 $$
Logo $b^3$ é par, então $b$ é par. Contradição: $a$ e $b$ pares, mas $MDC(a, b) = 1$. ✗

**Resposta:** $\sqrt[3]{2}$ é irracional (prova similar a $\sqrt{2}$, usando cubos).

---
**Fim — Números Irracionais**
