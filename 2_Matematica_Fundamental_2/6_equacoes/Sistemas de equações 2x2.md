# Sistemas de Equações do 1º Grau (2×2)

Um **sistema de equações do 1º grau** com duas incógnitas (2×2) consiste em duas equações lineares com duas variáveis. A solução é o par ordenado $(x, y)$ que satisfaz **ambas** as equações simultaneamente.

## Conceito

$$ \begin{cases} a_1x + b_1y = c_1 \\ a_2x + b_2y = c_2 \end{cases} $$

### Tipos de Sistema

| Tipo | Condição | Solução | Interpretação geométrica |
|------|----------|---------|--------------------------|
| **Possível e determinado** | $\frac{a_1}{a_2} \neq \frac{b_1}{b_2}$ | Única | Retas se intersectam em um ponto |
| **Possível e indeterminado** | $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$ | Infinitas | Retas coincidentes |
| **Impossível** | $\frac{a_1}{a_2} = \frac{b_1}{b_2} \neq \frac{c_1}{c_2}$ | Nenhuma | Retas paralelas distintas |

## Método da Adição (Eliminação)

Multiplicar as equações para que os coeficientes de uma variável sejam opostos, depois somar as equações para eliminar essa variável.

### Exemplo 1

$$ \begin{cases} 2x + 3y = 13 \\ 3x - 2y = 0 \end{cases} $$

Multiplicar a 1ª por 2 e a 2ª por 3:
$$ \begin{cases} 4x + 6y = 26 \\ 9x - 6y = 0 \end{cases} $$

Somar: $13x = 26 \implies x = 2$

Substituir na 2ª: $3(2) - 2y = 0 \implies 6 = 2y \implies y = 3$

**Resposta:** $(2, 3)$

## Método da Substituição

Isolar uma variável em uma equação e substituir na outra.

### Exemplo 2

$$ \begin{cases} x + y = 7 \\ 2x - y = 5 \end{cases} $$

Da 1ª: $y = 7 - x$

Substituir na 2ª:
$$ 2x - (7 - x) = 5 $$
$$ 2x - 7 + x = 5 $$
$$ 3x = 12 \implies x = 4 $$
$$ y = 7 - 4 = 3 $$

**Resposta:** $(4, 3)$

## Método Gráfico (Introdução)

Cada equação representa uma **reta** no plano cartesiano. A solução é o ponto de interseção.

### Exemplo 3

$$ \begin{cases} x + y = 5 \\ x - y = 1 \end{cases} $$

| Reta 1: $x + y = 5$ | Reta 2: $x - y = 1$ |
|---|---|
| (0, 5) | (0, -1) |
| (5, 0) | (1, 0) |

As retas se intersectam em $(3, 2)$.

Verificação: $3 + 2 = 5$ ✓, $3 - 2 = 1$ ✓

**Resposta:** $(3, 2)$

## Sistemas Indeterminados e Impossíveis

### Indeterminado

$$ \begin{cases} 2x + 4y = 8 \\ x + 2y = 4 \end{cases} $$

A 2ª equação × 2 = 1ª equação. São a mesma reta!

Solução: infinitos pares $(x, 4 - 2x)$ para qualquer $x$.

### Impossível

$$ \begin{cases} x + y = 3 \\ x + y = 5 \end{cases} $$

Retas paralelas distintas. Não há interseção.

## Aplicações na Vida Real

- **Finanças:** mistura de investimentos com diferentes taxas
- **Química:** mistura de soluções com diferentes concentrações
- **Economia:** equilíbrio de mercado (oferta = demanda)
- **Física:** encontro de dois móveis, equilíbrio de forças
- **Engenharia:** circuitos elétricos (Leis de Kirchhoff)
- **Geografia:** interseção de rotas, coordenadas
- **Cozinha:** mistura de ingredientes para obter composição desejada
- **Esportes:** estatísticas, médias combinadas
- **Jogos:** colisão de trajetórias, encontro de personagens
- **Logística:** otimização de rotas, custos combinados

## Problemas

### Nível 1 — Básico

**1.** Resolva por adição:
$$ \begin{cases} x + y = 10 \\ x - y = 2 \end{cases} $$

Somar: $2x = 12 \implies x = 6$
Substituir: $6 + y = 10 \implies y = 4$

**Resposta:** $(6, 4)$.

**2.** Resolva por substituição:
$$ \begin{cases} y = 2x \\ 3x + y = 15 \end{cases} $$

$$ 3x + 2x = 15 \implies 5x = 15 \implies x = 3 $$
$$ y = 2(3) = 6 $$

**Resposta:** $(3, 6)$.

**3.** Classifique o sistema:
$$ \begin{cases} 2x + y = 4 \\ 4x + 2y = 8 \end{cases} $$

$$ \frac{2}{4} = \frac{1}{2} = \frac{4}{8} $$

**Resposta:** Possível e indeterminado (infinitas soluções).

**4.** Classifique o sistema:
$$ \begin{cases} x + y = 3 \\ x + y = 7 \end{cases} $$

**Resposta:** Impossível (retas paralelas).

**5.** A soma de dois números é 25 e a diferença é 7. Quais são os números?

$$ x + y = 25, \quad x - y = 7 $$
$$ 2x = 32 \implies x = 16, \quad y = 9 $$

**Resposta:** 16 e 9.

### Nível 2 — Intermediário

**6.** Resolva:
$$ \begin{cases} 3x + 2y = 12 \\ 5x - 3y = 1 \end{cases} $$

1ª × 3: $9x + 6y = 36$
2ª × 2: $10x - 6y = 2$
Somar: $19x = 38 \implies x = 2$
$3(2) + 2y = 12 \implies 6 + 2y = 12 \implies y = 3$

**Resposta:** $(2, 3)$.

**7.** Resolva:
$$ \begin{cases} \frac{x}{2} + \frac{y}{3} = 4 \\ x - y = 2 \end{cases} $$

Da 2ª: $x = y + 2$
Substituir na 1ª:
$$ \frac{y + 2}{2} + \frac{y}{3} = 4 $$
$$ 3(y + 2) + 2y = 24 $$
$$ 3y + 6 + 2y = 24 $$
$$ 5y = 18 \implies y = \frac{18}{5} = 3{,}6 $$
$$ x = 3{,}6 + 2 = 5{,}6 $$

**Resposta:** $(5{,}6; 3{,}6)$ ou $(\frac{28}{5}, \frac{18}{5})$.

**8.** Um quiosque vende cachorro-quente por R$ 8,00 e refrigerante por R$ 5,00. Num dia, vendeu 20 itens e arrecadou R$ 130,00. Quantos de cada vendeu?

$$ x + y = 20 $$
$$ 8x + 5y = 130 $$

$x = 20 - y$:
$$ 8(20 - y) + 5y = 130 $$
$$ 160 - 8y + 5y = 130 $$
$$ -3y = -30 \implies y = 10 $$
$$ x = 10 $$

**Resposta:** 10 cachorros-quentes e 10 refrigerantes.

**9.** Resolva graficamente (aproximadamente):
$$ \begin{cases} y = x + 1 \\ y = -2x + 4 \end{cases} $$

Igualar: $x + 1 = -2x + 4 \implies 3x = 3 \implies x = 1, y = 2$

**Resposta:** $(1, 2)$.

**10.** Para que valor de $k$ o sistema tem infinitas soluções?
$$ \begin{cases} 2x + ky = 6 \\ 4x + 8y = 12 \end{cases} $$

Para infinitas: $\frac{2}{4} = \frac{k}{8} = \frac{6}{12}$
$$ \frac{1}{2} = \frac{k}{8} \implies k = 4 $$

**Resposta:** $k = 4$.

### Nível 3 — Desafio

**11.** Resolva:
$$ \begin{cases} \frac{1}{x} + \frac{1}{y} = \frac{5}{6} \\ \frac{2}{x} - \frac{3}{y} = \frac{1}{6} \end{cases} $$

Seja $u = \frac{1}{x}$, $v = \frac{1}{y}$:
$$ \begin{cases} u + v = \frac{5}{6} \\ 2u - 3v = \frac{1}{6} \end{cases} $$

1ª × 3: $3u + 3v = \frac{5}{2}$
Somar com 2ª: $5u = \frac{5}{2} + \frac{1}{6} = \frac{15 + 1}{6} = \frac{16}{6} = \frac{8}{3}$
$$ u = \frac{8}{15} $$
$$ v = \frac{5}{6} - \frac{8}{15} = \frac{25 - 16}{30} = \frac{9}{30} = \frac{3}{10} $$

$$ x = \frac{15}{8}, \quad y = \frac{10}{3} $$

**Resposta:** $x = \frac{15}{8}$, $y = \frac{10}{3}$.

**12.** Três canetas e dois lápis custam R$ 11,00. Duas canetas e três lápis custam R$ 9,00. Quanto custa uma caneta e um lápis juntos?

$$ 3c + 2l = 11 $$
$$ 2c + 3l = 9 $$

Somar as equações:
$$ 5c + 5l = 20 \implies c + l = 4 $$

**Resposta:** R$ 4,00 (sem precisar encontrar c e l individualmente!).

**13.** Uma pessoa tem R$ 200,00 em notas de R$ 5,00, R$ 10,00 e R$ 20,00. Se o número de notas de R$ 5,00 é o dobro do número de notas de R$ 20,00, e o total de notas é 18, quantas notas de cada valor ela tem?

Sejam $x$ = notas de 5, $y$ = notas de 10, $z$ = notas de 20:
$$ x + y + z = 18 $$
$$ 5x + 10y + 20z = 200 $$
$$ x = 2z $$

$x = 2z$:
$$ 2z + y + z = 18 \implies y + 3z = 18 $$
$$ 5(2z) + 10y + 20z = 200 \implies 10z + 10y + 20z = 200 \implies 10y + 30z = 200 \implies y + 3z = 20 $$

$$ y + 3z = 18 $$
$$ y + 3z = 20 $$

$18 = 20$? Impossível! O sistema não tem solução.

> **Nota:** Este problema é um sistema 3×3. Vamos ajustar: se o total de notas fosse 19 em vez de 18, ou o total fosse R$ 210, teria solução. Vamos recalcular com total de notas = 19:

$$ y + 3z = 19 $$
$$ y + 3z = 20 $$

Ainda impossível. Vamos usar total = 20 notas:
$$ y + 3z = 20 $$
$$ y + 3z = 20 $$

Infinitas soluções! Escolhamos $z = 2$: $y = 14$, $x = 4$. Verificação: $4 + 14 + 2 = 20$ notas, $5(4) + 10(14) + 20(2) = 20 + 140 + 40 = 200$ ✓

**Resposta:** Se total = 20 notas: 4 notas de R$ 5, 14 notas de R$ 10, 2 notas de R$ 20. (O problema original com 18 notas é impossível.)

---
**Fim — Sistemas de Equações do 1º Grau (2×2)**
