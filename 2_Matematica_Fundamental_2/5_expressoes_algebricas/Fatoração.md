# Fatoração

A **fatoração** é o processo de reescrever uma expressão algébrica como um produto de fatores mais simples. É a operação inversa da multiplicação e é essencial para simplificar expressões, resolver equações e trabalhar com frações algébricas.

## Fator Comum em Evidência

Identificar o **fator comum** a todos os termos e colocá-lo em evidência.

$$ ax + ay = a(x + y) $$

### Exemplos

$$ 3x + 6 = 3(x + 2) $$
$$ 4x^2 - 8x = 4x(x - 2) $$
$$ 5x^2y + 10xy^2 = 5xy(x + 2y) $$
$$ x^3 + x^2 = x^2(x + 1) $$

### Passo a Passo

1. Encontre o MDC dos coeficientes
2. Identifique variáveis comuns com menor expoente
3. Coloque o fator comum em evidência

## Fatoração por Agrupamento

Quando não há fator comum em todos os termos, agrupamos termos que têm fatores em comum.

$$ ax + ay + bx + by = a(x + y) + b(x + y) = (a + b)(x + y) $$

### Exemplos

$$ x^2 + 3x + 2x + 6 = x(x + 3) + 2(x + 3) = (x + 2)(x + 3) $$
$$ 2x^2 - 3x + 4x - 6 = x(2x - 3) + 2(2x - 3) = (x + 2)(2x - 3) $$
$$ x^3 + x^2 + x + 1 = x^2(x + 1) + 1(x + 1) = (x^2 + 1)(x + 1) $$

> **Dica:** Agrupar de forma que os parênteses resultantes sejam iguais!

## Diferença de Quadrados

$$ a^2 - b^2 = (a + b)(a - b) $$

### Exemplos

$$ x^2 - 9 = (x + 3)(x - 3) $$
$$ 4x^2 - 25 = (2x + 5)(2x - 5) $$
$$ x^4 - 1 = (x^2 + 1)(x^2 - 1) = (x^2 + 1)(x + 1)(x - 1) $$
$$ 16 - 49y^2 = (4 + 7y)(4 - 7y) $$

> **Cuidado:** Só funciona para **diferença** ($a^2 - b^2$), não para soma ($a^2 + b^2$ não fatora em reais).

## Trinômio Quadrado Perfeito

$$ a^2 + 2ab + b^2 = (a + b)^2 $$
$$ a^2 - 2ab + b^2 = (a - b)^2 $$

### Exemplos

$$ x^2 + 6x + 9 = (x + 3)^2 $$
$$ x^2 - 10x + 25 = (x - 5)^2 $$
$$ 4x^2 + 12x + 9 = (2x + 3)^2 $$
$$ 9x^2 - 24x + 16 = (3x - 4)^2 $$

> **Verificação:** O termo do meio é sempre $2 \times \sqrt{\text{primeiro}} \times \sqrt{\text{último}}$.

## Fatoração de Trinômio do 2º Grau

$$ x^2 + bx + c = (x + m)(x + n) $$

Onde:
- $m + n = b$ (soma dos coeficientes)
- $m \cdot n = c$ (produto dos coeficientes)

### Exemplos

$$ x^2 + 5x + 6: \quad m + n = 5, \quad m \cdot n = 6 \implies m = 2, n = 3 $$
$$ x^2 + 5x + 6 = (x + 2)(x + 3) $$

$$ x^2 - 7x + 12: \quad m + n = -7, \quad m \cdot n = 12 \implies m = -3, n = -4 $$
$$ x^2 - 7x + 12 = (x - 3)(x - 4) $$

$$ x^2 + x - 12: \quad m + n = 1, \quad m \cdot n = -12 \implies m = 4, n = -3 $$
$$ x^2 + x - 12 = (x + 4)(x - 3) $$

### Para Coeficiente de $x^2$ diferente de 1

$$ ax^2 + bx + c = a(x - r_1)(x - r_2) $$

Ou usar o método da chave/teste:

$$ 2x^2 + 7x + 3 = (2x + 1)(x + 3) $$

Verificação: $2x \cdot x + 2x \cdot 3 + 1 \cdot x + 1 \cdot 3 = 2x^2 + 6x + x + 3 = 2x^2 + 7x + 3$ ✓

## Casos Especiais

### Diferença de Cubos

$$ a^3 - b^3 = (a - b)(a^2 + ab + b^2) $$

$$ x^3 - 8 = (x - 2)(x^2 + 2x + 4) $$

### Soma de Cubos

$$ a^3 + b^3 = (a + b)(a^2 - ab + b^2) $$

$$ x^3 + 27 = (x + 3)(x^2 - 3x + 9) $$

> **Nota:** Soma de quadrados ($a^2 + b^2$) **não fatora** em reais!

## Fatoração Completa (Exemplo Combinado)

$$ 2x^4 - 32 $$
$$ = 2(x^4 - 16) \quad \text{(fator comum)} $$
$$ = 2(x^2 + 4)(x^2 - 4) \quad \text{(diferença de quadrados)} $$
$$ = 2(x^2 + 4)(x + 2)(x - 2) \quad \text{(diferença de quadrados novamente)} $$

## Aplicações na Vida Real

- **Física:** equações de movimento, fatoração para encontrar tempos de queda
- **Engenharia:** dimensionamento de estruturas, otimização de materiais
- **Economia:** ponto de equilíbrio, maximização de lucro (fatorando para encontrar raízes)
- **Criptografia:** fatoração de números grandes (RSA), polinômios em corpos finitos
- **Computação:** simplificação de expressões, compiladores, otimização de código
- **Design:** proporções áureas, divisão de espaços, padrões geométricos
- **Jogos:** interpolação, curvas de Bézier, detecção de colisão (fatorando polinômios)
- **Estatística:** decomposição de variância, análise fatorial
- **Química:** equilíbrio químico, constantes de equilíbrio (fatoração de polinômios)
- **Medicina:** modelos de crescimento, eliminação de medicamentos (fatorando para encontrar tempos críticos)

## Problemas

### Nível 1 — Básico

**1.** Fatore $3x + 6$.

$$ 3(x + 2) $$

**Resposta:** $3(x + 2)$.

**2.** Fatore $x^2 - 16$.

$$ (x + 4)(x - 4) $$

**Resposta:** $(x + 4)(x - 4)$.

**3.** Fatore $x^2 + 8x + 16$.

$$ (x + 4)^2 $$

**Resposta:** $(x + 4)^2$.

**4.** Fatore $x^2 + 5x + 6$.

$$ 2 + 3 = 5, \quad 2 \cdot 3 = 6 \implies (x + 2)(x + 3) $$

**Resposta:** $(x + 2)(x + 3)$.

**5.** Fatore $x^2 - 9x + 20$.

$$ -4 + (-5) = -9, \quad (-4)(-5) = 20 \implies (x - 4)(x - 5) $$

**Resposta:** $(x - 4)(x - 5)$.

### Nível 2 — Intermediário

**6.** Fatore $x^3 - x$ completamente.

$$ x(x^2 - 1) = x(x + 1)(x - 1) $$

**Resposta:** $x(x + 1)(x - 1)$.

**7.** Fatore $x^2 + 2x - 15$.

$$ 5 + (-3) = 2, \quad 5 \cdot (-3) = -15 \implies (x + 5)(x - 3) $$

**Resposta:** $(x + 5)(x - 3)$.

**8.** Fatore $2x^2 + 5x + 2$.

Testando: $(2x + 1)(x + 2) = 2x^2 + 4x + x + 2 = 2x^2 + 5x + 2$ ✓

**Resposta:** $(2x + 1)(x + 2)$.

**9.** Fatore $x^3 + 27$.

$$ x^3 + 3^3 = (x + 3)(x^2 - 3x + 9) $$

**Resposta:** $(x + 3)(x^2 - 3x + 9)$.

**10.** Fatore $x^2 + 7x + 12$ por agrupamento (adicione e subtraia um termo).

$$ x^2 + 7x + 12 = x^2 + 3x + 4x + 12 = x(x + 3) + 4(x + 3) = (x + 4)(x + 3) $$

**Resposta:** $(x + 3)(x + 4)$.

### Nível 3 — Desafio

**11.** Fatore $x^4 - 16$ completamente.

$$ (x^2)^2 - 4^2 = (x^2 + 4)(x^2 - 4) = (x^2 + 4)(x + 2)(x - 2) $$

> $x^2 + 4$ não fatora em reais (soma de quadrados).

**Resposta:** $(x^2 + 4)(x + 2)(x - 2)$.

**12.** Fatore $x^3 - 3x^2 - 4x + 12$ por agrupamento.

$$ x^2(x - 3) - 4(x - 3) = (x^2 - 4)(x - 3) = (x + 2)(x - 2)(x - 3) $$

**Resposta:** $(x + 2)(x - 2)(x - 3)$.

**13.** Se $x^2 + bx + c = (x + p)(x + q)$, encontre $b$ e $c$ em função de $p$ e $q$. Depois, se $p + q = 7$ e $p^2 + q^2 = 25$, encontre $c$.

$$ (x + p)(x + q) = x^2 + (p + q)x + pq = x^2 + bx + c $$
$$ b = p + q, \quad c = pq $$

$$ p + q = 7 $$
$$ p^2 + q^2 = 25 $$

$$ (p + q)^2 = p^2 + 2pq + q^2 = 49 $$
$$ 25 + 2pq = 49 $$
$$ 2pq = 24 $$
$$ pq = 12 $$

$$ c = pq = 12 $$

**Resposta:** $b = p + q$, $c = pq$. Para $p + q = 7$ e $p^2 + q^2 = 25$: $c = 12$.

---
**Fim — Fatoração**
