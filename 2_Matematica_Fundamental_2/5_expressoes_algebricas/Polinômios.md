# Polinômios

Um **polinômio** é uma expressão algébrica formada pela soma de um ou mais monômios. Os polinômios são fundamentais em toda a matemática: descrevem curvas, modelam fenômenos naturais, e são a base para equações, funções e cálculo.

## Definição

$$ P(x) = a_n x^n + a_{n-1} x^{n-1} + \ldots + a_2 x^2 + a_1 x + a_0 $$

Onde:
- $a_n, a_{n-1}, \ldots, a_0$ são os **coeficientes** (números reais)
- $n$ é um **número natural**
- $x$ é a **variável**
- $a_n x^n$ é o **termo dominante** (com maior expoente)

## Grau de um Polinômio

O **grau** é o maior expoente entre os termos com coeficiente não nulo.

| Polinômio | Grau | Nome |
|-----------|------|------|
| $5$ | $0$ | Constante |
| $2x + 3$ | $1$ | Linear (ou do 1º grau) |
| $x^2 - 5x + 6$ | $2$ | Quadrado (ou do 2º grau) |
| $4x^3 - 2x + 1$ | $3$ | Cúbico (ou do 3º grau) |
| $x^4 + 3x^2 - 7$ | $4$ | Quartico (ou do 4º grau) |

## Adição e Subtração de Polinômios

Somamos/subtraímos **termos semelhantes** (mesma parte literal).

### Exemplo 1

$$ (3x^2 + 2x - 5) + (x^2 - 4x + 7) $$
$$ = 3x^2 + x^2 + 2x - 4x - 5 + 7 $$
$$ = 4x^2 - 2x + 2 $$

### Exemplo 2

$$ (5x^3 - 2x^2 + x) - (3x^3 + x^2 - 4x) $$
$$ = 5x^3 - 2x^2 + x - 3x^3 - x^2 + 4x $$
$$ = 2x^3 - 3x^2 + 5x $$

## Multiplicação de Polinômios

Usamos a **propriedade distributiva**: cada termo de um polinômio multiplica cada termo do outro.

### Monômio × Polinômio

$$ 3x \cdot (2x^2 - 5x + 1) = 6x^3 - 15x^2 + 3x $$

### Binômio × Binômio (Método FOIL)

$$ (a + b)(c + d) = ac + ad + bc + bd $$

**F**irst (primeiros), **O**uter (externos), **I**nner (internos), **L**ast (últimos)

$$ (x + 2)(x + 3) = x \cdot x + x \cdot 3 + 2 \cdot x + 2 \cdot 3 = x^2 + 3x + 2x + 6 = x^2 + 5x + 6 $$

### Polinômio × Polinômio

$$ (x^2 + 2x - 1)(x - 3) $$
$$ = x^2 \cdot x + x^2 \cdot (-3) + 2x \cdot x + 2x \cdot (-3) + (-1) \cdot x + (-1) \cdot (-3) $$
$$ = x^3 - 3x^2 + 2x^2 - 6x - x + 3 $$
$$ = x^3 - x^2 - 7x + 3 $$

## Divisão de Polinômios (Casos Simples)

### Divisão por Monômio

Dividir cada termo do polinômio pelo monômio:

$$ \frac{6x^3 - 9x^2 + 3x}{3x} = \frac{6x^3}{3x} - \frac{9x^2}{3x} + \frac{3x}{3x} = 2x^2 - 3x + 1 $$

### Divisão de Polinômio por Binômio (Método da Chave)

Dividir $x^2 + 5x + 6$ por $x + 2$:

1. $x^2 \div x = x$ → multiplicar: $x(x + 2) = x^2 + 2x$ → subtrair: $(x^2 + 5x) - (x^2 + 2x) = 3x$
2. $3x \div x = 3$ → multiplicar: $3(x + 2) = 3x + 6$ → subtrair: $(3x + 6) - (3x + 6) = 0$

$$ \frac{x^2 + 5x + 6}{x + 2} = x + 3 $$

Verificação: $(x + 2)(x + 3) = x^2 + 5x + 6$ ✓

## Valor Numérico de um Polinômio

Substituir a variável por um valor e calcular:

$$ P(x) = x^2 - 3x + 2 $$
$$ P(1) = 1^2 - 3(1) + 2 = 1 - 3 + 2 = 0 $$
$$ P(2) = 2^2 - 3(2) + 2 = 4 - 6 + 2 = 0 $$

> Quando $P(a) = 0$, dizemos que $a$ é uma **raiz** (ou zero) do polinômio.

## Exemplos

### Exemplo 1: Adição

$$ (2x^3 - x^2 + 4x - 1) + (x^3 + 3x^2 - 2x + 5) $$
$$ = 3x^3 + 2x^2 + 2x + 4 $$

### Exemplo 2: Multiplicação

$$ (x - 1)(x^2 + x + 1) $$
$$ = x(x^2 + x + 1) - 1(x^2 + x + 1) $$
$$ = x^3 + x^2 + x - x^2 - x - 1 $$
$$ = x^3 - 1 $$

> **Caso especial:** $(x - 1)(x^2 + x + 1) = x^3 - 1$ (fatoração de diferença de cubos!)

### Exemplo 3: Divisão com Resto

Dividir $x^3 + 2x^2 - x + 3$ por $x + 1$:

1. $x^3 \div x = x^2$ → $x^2(x + 1) = x^3 + x^2$ → subtrair: $(x^3 + 2x^2) - (x^3 + x^2) = x^2$
2. $x^2 \div x = x$ → $x(x + 1) = x^2 + x$ → subtrair: $(x^2 - x) - (x^2 + x) = -2x$
3. $-2x \div x = -2$ → $-2(x + 1) = -2x - 2$ → subtrair: $(-2x + 3) - (-2x - 2) = 5$

$$ x^3 + 2x^2 - x + 3 = (x + 1)(x^2 + x - 2) + 5 $$

Quociente: $x^2 + x - 2$, Resto: $5$

## Aplicações na Vida Real

- **Física:** trajetória de projéteis $y = ax^2 + bx + c$ (parábola)
- **Economia:** funções de custo, receita, lucro (polinômios do 2º grau)
- **Engenharia:** deflexão de vigas (polinômios cúbicos), tensão de materiais
- **Computação:** interpolação polinomial, curvas de Bézier (design gráfico)
- **Medicina:** modelos de crescimento tumoral, concentração de medicamentos
- **Estatística:** regressão polinomial, ajuste de curvas
- **Química:** equilíbrio químico, constantes de equilíbrio (polinômios em concentrações)
- **Ecologia:** modelos populacionais (logísticos, polinômios aproximados)
- **Arquitetura:** cálculo de estruturas, formas curvas, otimização de espaços
- **Jogos:** colisões, trajetórias, pathfinding (polinômios de interpolação)

## Problemas

### Nível 1 — Básico

**1.** Qual o grau de $3x^4 - 2x^2 + 5x - 7$?

**Resposta:** Grau 4.

**2.** Calcule $(2x^2 + 3x - 1) + (x^2 - 2x + 4)$.

$$ 2x^2 + x^2 + 3x - 2x - 1 + 4 = 3x^2 + x + 3 $$

**Resposta:** $3x^2 + x + 3$.

**3.** Calcule $(x + 3)(x + 2)$.

$$ x^2 + 2x + 3x + 6 = x^2 + 5x + 6 $$

**Resposta:** $x^2 + 5x + 6$.

**4.** Calcule $2x \cdot (3x^2 - x + 4)$.

$$ 6x^3 - 2x^2 + 8x $$

**Resposta:** $6x^3 - 2x^2 + 8x$.

**5.** Calcule $P(2)$ para $P(x) = x^2 - 3x + 5$.

$$ P(2) = 4 - 6 + 5 = 3 $$

**Resposta:** 3.

### Nível 2 — Intermediário

**6.** Calcule $(2x - 3)(x^2 + 2x - 1)$.

$$ 2x(x^2 + 2x - 1) - 3(x^2 + 2x - 1) $$
$$ = 2x^3 + 4x^2 - 2x - 3x^2 - 6x + 3 $$
$$ = 2x^3 + x^2 - 8x + 3 $$

**Resposta:** $2x^3 + x^2 - 8x + 3$.

**7.** Divida $x^2 - 5x + 6$ por $x - 2$.

$$ x^2 \div x = x \to x(x - 2) = x^2 - 2x \to (-5x) - (-2x) = -3x $$
$$ -3x \div x = -3 \to -3(x - 2) = -3x + 6 \to 6 - 6 = 0 $$

$$ \frac{x^2 - 5x + 6}{x - 2} = x - 3 $$

**Resposta:** $x - 3$.

**8.** Calcule $(x^2 - 2x + 3) - (2x^2 + x - 5) + (x^2 - 3x + 1)$.

$$ x^2 - 2x + 3 - 2x^2 - x + 5 + x^2 - 3x + 1 $$
$$ = (x^2 - 2x^2 + x^2) + (-2x - x - 3x) + (3 + 5 + 1) $$
$$ = 0x^2 - 6x + 9 = -6x + 9 $$

**Resposta:** $-6x + 9$.

**9.** Se $P(x) = x^2 - 4x + 3$, verifique que $P(1) = 0$ e $P(3) = 0$. O que isso significa?

$$ P(1) = 1 - 4 + 3 = 0 \quad \checkmark $$
$$ P(3) = 9 - 12 + 3 = 0 \quad \checkmark $$

Significa que $x = 1$ e $x = 3$ são **raízes** (zeros) do polinômio. Logo $P(x) = (x - 1)(x - 3)$.

**Resposta:** $P(1) = P(3) = 0$. Significa que 1 e 3 são raízes, e $P(x) = (x - 1)(x - 3)$.

**10.** Calcule $(x + 1)(x - 1)(x^2 + 1)$.

$$ (x + 1)(x - 1) = x^2 - 1 $$
$$ (x^2 - 1)(x^2 + 1) = x^4 - 1 $$

**Resposta:** $x^4 - 1$.

### Nível 3 — Desafio

**11.** Divida $2x^3 - 5x^2 + 4x - 1$ por $x - 1$ e encontre o quociente e o resto.

1. $2x^3 \div x = 2x^2$ → $2x^2(x - 1) = 2x^3 - 2x^2$ → $(-5x^2) - (-2x^2) = -3x^2$
2. $-3x^2 \div x = -3x$ → $-3x(x - 1) = -3x^2 + 3x$ → $(4x) - (3x) = x$
3. $x \div x = 1$ → $1(x - 1) = x - 1$ → $(-1) - (-1) = 0$

$$ 2x^3 - 5x^2 + 4x - 1 = (x - 1)(2x^2 - 3x + 1) + 0 $$

Verificação: $(x - 1)(2x^2 - 3x + 1) = 2x^3 - 3x^2 + x - 2x^2 + 3x - 1 = 2x^3 - 5x^2 + 4x - 1$ ✓

**Resposta:** Quociente: $2x^2 - 3x + 1$. Resto: $0$.

**12.** Sabendo que $P(x) = x^3 + ax^2 + bx + c$ satisfaz $P(1) = 0$, $P(2) = 0$, e $P(0) = 6$, encontre $a$, $b$, $c$.

$$ P(0) = c = 6 $$
$$ P(1) = 1 + a + b + 6 = 0 \implies a + b = -7 $$
$$ P(2) = 8 + 4a + 2b + 6 = 0 \implies 4a + 2b = -14 \implies 2a + b = -7 $$

De $a + b = -7$ e $2a + b = -7$:
$$ (2a + b) - (a + b) = -7 - (-7) \implies a = 0 $$
$$ b = -7 $$

$$ P(x) = x^3 - 7x + 6 $$

Verificação: $P(1) = 1 - 7 + 6 = 0$ ✓, $P(2) = 8 - 14 + 6 = 0$ ✓, $P(0) = 6$ ✓

**Resposta:** $a = 0$, $b = -7$, $c = 6$. $P(x) = x^3 - 7x + 6$.

**13.** O lucro de uma empresa é modelado por $L(x) = -2x^2 + 80x - 600$, onde $x$ é o número de unidades vendidas. Calcule o lucro para $x = 10$, $x = 20$, e $x = 30$. Em qual valor de $x$ o lucro parece ser máximo?

$$ L(10) = -2(100) + 800 - 600 = -200 + 800 - 600 = 0 $$
$$ L(20) = -2(400) + 1600 - 600 = -800 + 1600 - 600 = 200 $$
$$ L(30) = -2(900) + 2400 - 600 = -1800 + 2400 - 600 = 0 $$

O lucro é máximo entre $x = 20$ e $x = 30$ (na verdade, no vértice da parábola $x = -b/2a = -80/(-4) = 20$).

**Resposta:** $L(10) = 0$, $L(20) = 200$, $L(30) = 0$. Máximo em $x = 20$ (máximo = 200).

---
**Fim — Polinômios**
