# Sistemas de Inequações

Um **sistema de inequações** é um conjunto de duas ou mais inequações que devem ser satisfeitas **simultaneamente**. A solução é a **interseção** das soluções de cada inequação individual — ou seja, os valores que satisfazem TODAS as inequações ao mesmo tempo.

## Conceito

$$ \begin{cases} f_1(x) > 0 \\ f_2(x) < 0 \\ f_3(x) 
geq 5 \end{cases} $$

A solução é:
$$ S = S_1 \cap S_2 \cap S_3 $$

Onde $S_i$ é a solução da inequação $i$.

## Resolução de Sistemas de Inequações do 1º Grau

### Passo a Passo

1. Resolver cada inequação separadamente
2. Encontrar a **interseção** das soluções
3. Representar na reta real

### Exemplo 1: Duas inequações

$$ \begin{cases} 2x + 3 > 7 \\ 5x - 1 
leq 14 \end{cases} $$

1ª: $2x > 4 \implies x > 2$
2ª: $5x 
leq 15 \implies x 
leq 3$

Interseção: $2 < x 
leq 3$

**Resposta:** $(2, 3]$

Na reta real:
```
<---|=======|=======|=======|=======|=======|---
    0       1       2       3       4       5
              o=======]
            (2 < x 
leq 3)
```

### Exemplo 2: Três inequações

$$ \begin{cases} x + 2 > 0 \\ 3x - 6 < 0 \\ 2x + 1 
geq -3 \end{cases} $$

1ª: $x > -2$
2ª: $3x < 6 \implies x < 2$
3ª: $2x 
geq -4 \implies x 
geq -2$

Interseção: $-2 
leq x < 2$ (a 1ª diz $x > -2$, a 3ª diz $x 
geq -2$; a mais restritiva é $x > -2$... espera, $x > -2$ e $x 
geq -2$ → a interseção é $x > -2$)

Correção: 
- $x > -2$ (estrita)
- $x < 2$ (estrita)
- $x 
geq -2$ (inclui -2)

Interseção de $x > -2$ e $x 
geq -2$ é $x > -2$ (mais restritiva).
Interseção com $x < 2$: $-2 < x < 2$

**Resposta:** $(-2, 2)$

> **Nota:** $x = -2$ não satisfaz $x > -2$ (primeira inequação).

### Exemplo 3: Sem solução

$$ \begin{cases} x > 5 \\ x < 3 \end{cases} $$

$x > 5$ e $x < 3$ são disjuntos (não se intersectam).

**Resposta:** $
emptyset$ (conjunto vazio) — sem solução.

## Sistemas de Inequações do 2º Grau

### Passo a Passo

1. Resolver cada inequação do 2º grau separadamente
2. Encontrar a interseção das soluções
3. Representar na reta real

### Exemplo 4: Uma do 1º e uma do 2º grau

$$ \begin{cases} x^2 - 5x + 6 > 0 \\ 2x - 1 < 7 \end{cases} $$

1ª: $x^2 - 5x + 6 > 0 \implies (x - 2)(x - 3) > 0 \implies x < 2$ ou $x > 3$
2ª: $2x < 8 \implies x < 4$

Interseção:
- $(-
fty, 2) \cap (-
fty, 4) = (-
fty, 2)$
- $(3, +
fty) \cap (-
fty, 4) = (3, 4)$

**Resposta:** $(-
fty, 2) \cup (3, 4)$

### Exemplo 5: Duas do 2º grau

$$ \begin{cases} x^2 - 4 
leq 0 \\ x^2 - 9 > 0 \end{cases} $$

1ª: $x^2 
leq 4 \implies -2 
leq x 
leq 2$
2ª: $x^2 > 9 \implies x < -3$ ou $x > 3$

Interseção:
- $[-2, 2] \cap (-
fty, -3) = 
emptyset$
- $[-2, 2] \cap (3, +
fty) = 
emptyset$

**Resposta:** $
emptyset$ (sem solução)

### Exemplo 6: Duas do 2º grau com interseção

$$ \begin{cases} x^2 - x - 6 < 0 \\ x^2 - 4x + 3 
geq 0 \end{cases} $$

1ª: $x^2 - x - 6 < 0 \implies (x - 3)(x + 2) < 0 \implies -2 < x < 3$
2ª: $x^2 - 4x + 3 
geq 0 \implies (x - 1)(x - 3) 
geq 0 \implies x 
leq 1$ ou $x 
geq 3$

Interseção:
- $(-2, 3) \cap (-
fty, 1] = (-2, 1]$
- $(-2, 3) \cap [3, +
fty) = 
emptyset$ (pois $x < 3$ e $x 
geq 3$ não se intersectam)

**Resposta:** $(-2, 1]$

## Representação Gráfica (Plano Cartesiano)

Para sistemas com **duas variáveis** (ex: $x$ e $y$), cada inequação representa uma **região do plano**.

### Exemplo: Região do plano

$$ \begin{cases} y > x + 1 \\ y 
leq -x + 3 \end{cases} $$

1ª: Região **acima** da reta $y = x + 1$ (linha tracejada, não inclui a reta)
2ª: Região **abaixo** da reta $y = -x + 3$ (linha contínua, inclui a reta)

A solução é a interseção dessas duas regiões (um triângulo/semiplano limitado).

## Sistemas com Variáveis Separadas

$$ \begin{cases} 2x + 1 > 5 \\ 3y - 2 
leq 7 \end{cases} $$

Como $x$ e $y$ são independentes, resolvemos separadamente:
- $x > 2$
- $y 
leq 3$

A solução é o conjunto de pares $(x, y)$ com $x > 2$ e $y 
leq 3$ (uma região semi-infinita do plano).

## Aplicações na Vida Real

- **Economia:** faixa de produção lucrativa (lucro > 0 E custo < orçamento)
- **Física:** temperatura em faixa segura ($T_{min} 
leq T 
leq T_{max}$)
- **Engenharia:** especificações de projeto (tolerâncias múltiplas)
- **Medicina:** dosagem segura (concentração mínima E máxima)
- **Finanças:** preço de venda (custo < preço < concorrência)
- **Geografia:** coordenadas dentro de região (latitude E longitude em faixa)
- **Jogos:** posição válida (dentro de mapa E fora de obstáculos)
- **Química:** mistura de soluções (concentração A em faixa E concentração B em faixa)
- **Estatística:** dados dentro de múltiplos critérios de qualidade
- **Logística:** horário de entrega (após horário mínimo E antes de horário máximo)

## Problemas

### Nível 1 — Básico

**1.** Resolva:
$$ \begin{cases} x + 3 > 5 \\ 2x - 1 < 7 \end{cases} $$

1ª: $x > 2$
2ª: $2x < 8 \implies x < 4$

**Resposta:** $(2, 4)$ ou $2 < x < 4$.

**2.** Resolva:
$$ \begin{cases} 3x + 2 
geq 8 \\ x - 4 < 1 \end{cases} $$

1ª: $3x 
geq 6 \implies x 
geq 2$
2ª: $x < 5$

**Resposta:** $[2, 5)$ ou $2 
leq x < 5$.

**3.** Resolva:
$$ \begin{cases} x > 3 \\ x < 1 \end{cases} $$

**Resposta:** $
emptyset$ (sem solução).

**4.** Resolva:
$$ \begin{cases} x^2 - 4 < 0 \\ x + 1 > 0 \end{cases} $$

1ª: $-2 < x < 2$
2ª: $x > -1$

Interseção: $(-1, 2)$

**Resposta:** $(-1, 2)$.

**5.** Resolva:
$$ \begin{cases} 2x + 1 > 3 \\ 4x - 5 < 7 \\ x + 2 
geq 1 \end{cases} $$

1ª: $x > 1$
2ª: $4x < 12 \implies x < 3$
3ª: $x 
geq -1$

Interseção: $(1, 3)$

**Resposta:** $(1, 3)$.

### Nível 2 — Intermediário

**6.** Resolva:
$$ \begin{cases} x^2 - 5x + 6 
leq 0 \\ x^2 - 9 > 0 \end{cases} $$

1ª: $2 
leq x 
leq 3$
2ª: $x < -3$ ou $x > 3$

Interseção: $
emptyset$ (sem solução)

**Resposta:** $
emptyset$ (sem solução).

**7.** Resolva:
$$ \begin{cases} x^2 - 3x + 2 > 0 \\ x^2 - x - 6 < 0 \end{cases} $$

1ª: $(x - 1)(x - 2) > 0 \implies x < 1$ ou $x > 2$
2ª: $(x - 3)(x + 2) < 0 \implies -2 < x < 3$

Interseção:
- $(-
fty, 1) \cap (-2, 3) = (-2, 1)$
- $(2, +
fty) \cap (-2, 3) = (2, 3)$

**Resposta:** $(-2, 1) \cup (2, 3)$.

**8.** Resolva:
$$ \begin{cases} \frac{x - 1}{x + 2} > 0 \\ x - 3 < 0 \end{cases} $$

1ª: Análise de sinal: raízes $x = 1$ e $x = -2$ (excluído)
   - $x < -2$: $(-)(-) = +$
   - $-2 < x < 1$: $(-)(+) = -$
   - $x > 1$: $(+)(+) = +$
   Solução: $(-
fty, -2) \cup (1, +
fty)$

2ª: $x < 3$

Interseção:
- $(-
fty, -2) \cap (-
fty, 3) = (-
fty, -2)$
- $(1, +
fty) \cap (-
fty, 3) = (1, 3)$

**Resposta:** $(-
fty, -2) \cup (1, 3)$.

**9.** Resolva:
$$ \begin{cases} 2x + 3y > 6 \\ x - y < 2 \end{cases} $$

(Gráfico no plano — região do semiplano)

1ª: $y > -\frac{2}{3}x + 2$ (acima da reta)
2ª: $y > x - 2$ (acima da reta)

A solução é a região acima de ambas as retas (interseção de dois semiplanos).

**Resposta:** Região do plano acima de ambas as retas $y = -\frac{2}{3}x + 2$ e $y = x - 2$.

**10.** Uma empresa produz um produto com lucro dado por $L(x) = -2x^2 + 20x - 32$, onde $x$ é a quantidade produzida. Para que valores de $x$ o lucro é positivo E a produção é menor que 8 unidades?

$$ \begin{cases} -2x^2 + 20x - 32 > 0 \\ x < 8 \end{cases} $$

1ª: $-2x^2 + 20x - 32 > 0 \implies x^2 - 10x + 16 < 0$
$(x - 2)(x - 8) < 0 \implies 2 < x < 8$

2ª: $x < 8$

Interseção: $2 < x < 8$
Mas $x$ deve ser inteiro (unidades): $x 
leq 7$

**Resposta:** $2 < x < 8$ (ou $x 
leq 7$ se inteiro).

### Nível 3 — Desafio

**11.** Resolva:
$$ \begin{cases} x^2 - 7x + 12 > 0 \\ x^2 - 5x + 6 
leq 0 \\ x^2 - 4 > 0 \end{cases} $$

1ª: $(x - 3)(x - 4) > 0 \implies x < 3$ ou $x > 4$
2ª: $(x - 2)(x - 3) 
leq 0 \implies 2 
leq x 
leq 3$
3ª: $x^2 > 4 \implies x < -2$ ou $x > 2$

Interseção passo a passo:
- 1ª e 2ª: $[-2, 3]$ não... espera, 1ª diz $x < 3$ ou $x > 4$, 2ª diz $2 
leq x 
leq 3$
  - Interseção: $[2, 3)$ (pois $x < 3$ de 1ª, e $2 
leq x 
leq 3$ de 2ª)
  - $x = 3$ é excluído (1ª é estrita)

- Com 3ª: $[2, 3) \cap ((-2) 
infty, -2) \cup (2, +
fty))$ = $(2, 3)$

**Resposta:** $(2, 3)$.

**12.** Resolva:
$$ \begin{cases} |x - 2| < 3 \\ |x + 1| 
leq 4 \end{cases} $$

1ª: $-3 < x - 2 < 3 \implies -1 < x < 5$
2ª: $-4 
leq x + 1 
leq 4 \implies -5 
leq x 
leq 3$

Interseção: $(-1, 3]$

**Resposta:** $(-1, 3]$.

**13.** Para que valores de $x$ a expressão $\frac{x^2 - 4}{x^2 - 9}$ é positiva E $x^2 - 1 < 0$?

$$ \begin{cases} \frac{x^2 - 4}{x^2 - 9} > 0 \\ x^2 - 1 < 0 \end{cases} $$

2ª: $-1 < x < 1$

1ª: Numerador: $x = \pm 2$. Denominador: $x = \pm 3$ (excluídos)
   No intervalo $(-1, 1)$:
   - $x^2 - 4 < 0$ (pois $x^2 < 1 < 4$)
   - $x^2 - 9 < 0$ (pois $x^2 < 1 < 9$)
   - Fração: $(-)/(-) = +$

Toda a 2ª satisfaz a 1ª!

**Resposta:** $(-1, 1)$.

---
**Fim — Sistemas de Inequações**
