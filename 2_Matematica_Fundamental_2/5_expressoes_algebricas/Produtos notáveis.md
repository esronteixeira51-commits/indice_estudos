# Produtos Notáveis

Os **produtos notáveis** são padrões de multiplicação que aparecem com frequência na álgebra. Memorizá-los economiza tempo e reduz erros, além de serem essenciais para fatoração e simplificação de expressões.

## Quadrado da Soma

$$ (a + b)^2 = a^2 + 2ab + b^2 $$

### Por que funciona?

$$ (a + b)^2 = (a + b)(a + b) = a \cdot a + a \cdot b + b \cdot a + b \cdot b = a^2 + 2ab + b^2 $$

### Exemplos

$$ (x + 3)^2 = x^2 + 2 \cdot x \cdot 3 + 3^2 = x^2 + 6x + 9 $$
$$ (2a + 5)^2 = (2a)^2 + 2(2a)(5) + 5^2 = 4a^2 + 20a + 25 $$
$$ (x + y)^2 = x^2 + 2xy + y^2 $$

> **Cuidado comum:** $(a + b)^2 \neq a^2 + b^2$! Falta o $2ab$.

## Quadrado da Diferença

$$ (a - b)^2 = a^2 - 2ab + b^2 $$

### Por que funciona?

$$ (a - b)^2 = (a - b)(a - b) = a^2 - ab - ba + b^2 = a^2 - 2ab + b^2 $$

### Exemplos

$$ (x - 4)^2 = x^2 - 2 \cdot x \cdot 4 + 4^2 = x^2 - 8x + 16 $$
$$ (3x - 2)^2 = (3x)^2 - 2(3x)(2) + 2^2 = 9x^2 - 12x + 4 $$
$$ (a - b)^2 = a^2 - 2ab + b^2 $$

> **Cuidado comum:** $(a - b)^2 \neq a^2 - b^2$! É diferente do produto da soma pela diferença.

## Produto da Soma pela Diferença

$$ (a + b)(a - b) = a^2 - b^2 $$

### Por que funciona?

$$ (a + b)(a - b) = a \cdot a - a \cdot b + b \cdot a - b \cdot b = a^2 - b^2 $$

> Os termos $-ab$ e $+ab$ **cancelam**!

### Exemplos

$$ (x + 5)(x - 5) = x^2 - 25 $$
$$ (2x + 3)(2x - 3) = (2x)^2 - 3^2 = 4x^2 - 9 $$
$$ (x + y)(x - y) = x^2 - y^2 $$

## Tabela Resumo dos Produtos Notáveis

| Produto | Fórmula | Resultado |
|---------|---------|-----------|
| Quadrado da soma | $(a + b)^2$ | $a^2 + 2ab + b^2$ |
| Quadrado da diferença | $(a - b)^2$ | $a^2 - 2ab + b^2$ |
| Soma × diferença | $(a + b)(a - b)$ | $a^2 - b^2$ |

## Identidades Adicionais Úteis

### Cubo da Soma

$$ (a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3 $$

### Cubo da Diferença

$$ (a - b)^3 = a^3 - 3a^2b + 3ab^2 - b^3 $$

### Diferença de Cubos (relacionada)

$$ (a - b)(a^2 + ab + b^2) = a^3 - b^3 $$

### Soma de Cubos (relacionada)

$$ (a + b)(a^2 - ab + b^2) = a^3 + b^3 $$

## Aplicações na Vida Real

- **Física:** energia cinética expandida, aproximações $(1 + x)^2 \approx 1 + 2x$ para $x$ pequeno
- **Engenharia:** cálculo de áreas (quadrado de $(a+b)$), volumes
- **Economia:** juros compostos $(1 + i)^2 = 1 + 2i + i^2$, crescimento quadrático
- **Geometria:** área de quadrado com lado $(a+b)$, diferença de áreas
- **Estatística:** variância de $(X + Y)$, expansão de momentos
- **Cálculo numérico:** aproximações de Taylor, linearização
- **Computação:** otimização de código, simplificação algébrica
- **Criptografia:** operações em corpos finitos, álgebra modular
- **Jogos:** cálculos de dano, área de efeito, detecção de colisão
- **Arquitetura:** cálculo de áreas de terrenos com dimensões $(a+b)$

## Problemas

### Nível 1 — Básico

**1.** Expanda $(x + 2)^2$.

$$ x^2 + 2 \cdot x \cdot 2 + 2^2 = x^2 + 4x + 4 $$

**Resposta:** $x^2 + 4x + 4$.

**2.** Expanda $(x - 3)^2$.

$$ x^2 - 2 \cdot x \cdot 3 + 3^2 = x^2 - 6x + 9 $$

**Resposta:** $x^2 - 6x + 9$.

**3.** Calcule $(x + 4)(x - 4)$.

$$ x^2 - 4^2 = x^2 - 16 $$

**Resposta:** $x^2 - 16$.

**4.** Calcule $(2x + 1)^2$.

$$ (2x)^2 + 2(2x)(1) + 1^2 = 4x^2 + 4x + 1 $$

**Resposta:** $4x^2 + 4x + 1$.

**5.** Calcule $(3x - 2)(3x + 2)$.

$$ (3x)^2 - 2^2 = 9x^2 - 4 $$

**Resposta:** $9x^2 - 4$.

### Nível 2 — Intermediário

**6.** Expanda $(x + y + z)^2$.

$$ (x + y + z)^2 = [(x + y) + z]^2 = (x + y)^2 + 2(x + y)z + z^2 $$
$$ = x^2 + 2xy + y^2 + 2xz + 2yz + z^2 $$
$$ = x^2 + y^2 + z^2 + 2xy + 2xz + 2yz $$

**Resposta:** $x^2 + y^2 + z^2 + 2xy + 2xz + 2yz$.

**7.** Calcule $(x^2 + 1)(x^2 - 1)$.

$$ (x^2)^2 - 1^2 = x^4 - 1 $$

**Resposta:** $x^4 - 1$.

**8.** Calcule $(x + y)^2 - (x - y)^2$.

$$ (x^2 + 2xy + y^2) - (x^2 - 2xy + y^2) = 4xy $$

> **Fórmula útil:** $(a+b)^2 - (a-b)^2 = 4ab$

**Resposta:** $4xy$.

**9.** Se $(x + \frac{1}{x})^2 = 25$, encontre $x^2 + \frac{1}{x^2}$.

$$ (x + \frac{1}{x})^2 = x^2 + 2 \cdot x \cdot \frac{1}{x} + \frac{1}{x^2} = x^2 + 2 + \frac{1}{x^2} = 25 $$
$$ x^2 + \frac{1}{x^2} = 25 - 2 = 23 $$

**Resposta:** $23$.

**10.** Calcule $101^2$ usando produto notável.

$$ 101^2 = (100 + 1)^2 = 100^2 + 2 \cdot 100 \cdot 1 + 1^2 = 10000 + 200 + 1 = 10201 $$

**Resposta:** $10201$.

### Nível 3 — Desafio

**11.** Calcule $99^2 - 101^2$ sem calcular cada quadrado.

$$ 99^2 - 101^2 = (99 + 101)(99 - 101) = 200 \cdot (-2) = -400 $$

> Usando $a^2 - b^2 = (a+b)(a-b)$

**Resposta:** $-400$.

**12.** Se $a + b = 5$ e $ab = 6$, encontre $a^2 + b^2$ e $a^3 + b^3$.

$$ a^2 + b^2 = (a + b)^2 - 2ab = 25 - 12 = 13 $$

$$ a^3 + b^3 = (a + b)^3 - 3ab(a + b) = 125 - 3(6)(5) = 125 - 90 = 35 $$

> Alternativa: $a^3 + b^3 = (a + b)(a^2 - ab + b^2) = 5(13 - 6) = 5(7) = 35$ ✓

**Resposta:** $a^2 + b^2 = 13$, $a^3 + b^3 = 35$.

**13.** Expanda $(x + 1)^3$ e use para calcular $1{,}01^3$ aproximadamente.

$$ (x + 1)^3 = x^3 + 3x^2 + 3x + 1 $$

$$ 1{,}01^3 = (1 + 0{,}01)^3 = 1 + 3(0{,}01) + 3(0{,}01)^2 + (0{,}01)^3 $$
$$ = 1 + 0{,}03 + 0{,}0003 + 0{,}000001 = 1{,}030301 $$

**Resposta:** $1{,}030301$ (exato! $(1{,}01)^3 = 1{,}030301$).

---
**Fim — Produtos Notáveis**
