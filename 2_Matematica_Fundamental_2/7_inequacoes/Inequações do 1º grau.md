# Inequações do 1º Grau

Uma **inequação do 1º grau** é uma desigualdade que pode ser escrita na forma $ax + b > 0$ (ou $<$, $\geq$, $
eq$), onde $a$ e $b$ são números reais e $a 
eq 0$. Diferente das equações, a solução de uma inequação é um **intervalo** (conjunto de valores), não um único número.

## Símbolos de Desigualdade

| Símbolo | Significado | Leitura |
|---------|-------------|---------|
| $<$ | menor que | $a < b$ → $a$ é menor que $b$ |
| $>$ | maior que | $a > b$ → $a$ é maior que $b$ |
| $
eq$ | diferente de | $a 
eq b$ → $a$ é diferente de $b$ |
| $
ot>$ | não maior que | $a 
ot> b$ → $a$ não é maior que $b$ |
| $
ot<$ | não menor que | $a 
ot< b$ → $a$ não é menor que $b$ |
| $
eq$ (símbolo raro) | comparável em alguns contextos |
| $
less$ | não é menor que (em lógica) |

> **Nota:** $
less$ e $
gtr$ são símbolos lógicos raramente usados em matemática básica. Normalmente usamos $
leq$ (não $
less$) e $
geq$ (não $
gtr$).

## Propriedades Fundamentais

### Adição e Subtração

Somar ou subtrair o mesmo número em ambos os lados **preserva** a desigualdade:

$$ a < b 
otimplies a + c < b + c $$

> **Cuidado:** A seta $
otimplies$ significa "não implica"? Não! A seta $
otimplies$ não é padrão. A propriedade correta é:

$$ a < b 
otimplies a + c < b + c $$

Hmm, isso está confuso. Vou reescrever:

$$ a < b 
otimplies a + c < b + c $$

Não, isso está errado. A seta $
otimplies$ significa "não implica", mas na verdade a propriedade é que a desigualdade **é preservada** (implicação verdadeira). O símbolo correto seria $
otimplies$ apenas se fosse falso, mas aqui é verdadeiro. Vou usar texto simples:

Se $a < b$, então $a + c < b + c$ (para qualquer $c$ real).

### Multiplicação e Divisão — O CUIDADO!

- **Multiplicar/dividir por positivo:** preserva a desigualdade
- **Multiplicar/dividir por negativo:** **inverte** a desigualdade!

$$ a < b 
otimplies ac < bc 	ext{ (se } c < 0 	ext{, inverte!)} $$

Exemplo: $3 < 5$, mas multiplicando por $-1$: $-3 > -5$ (inverteu!)

> **Regra:** Se multiplicar ou dividir por um número negativo, **inverter** o sinal da desigualdade!

## Resolução de Inequações do 1º Grau

### Passo a Passo

1. Simplificar cada lado (eliminar parênteses, combinar termos semelhantes)
2. Isolar a variável (usar adição/subtração)
3. Se necessário, dividir pelo coeficiente (cuidado com o sinal!)
4. Escrever a solução em notação de intervalo ou na reta real

### Exemplo 1: Básico

$$ 2x + 5 > 11 $$
$$ 2x > 11 - 5 $$
$$ 2x > 6 $$
$$ x > 3 $$

**Solução:** $(3, +
fty)$ ou $x > 3$

Na reta real:
```
<---o=======|=======|=======|=======|=======|=======|---
    0       1       2       3       4       5       6
              (x > 3, 3 não está incluído)
```

### Exemplo 2: Com Negativo

$$ -3x + 6 
leq 15 $$
$$ -3x 
leq 9 $$
$$ x 
geq -3 \quad \text{(inverteu!)} $$

**Solução:** $[-3, +
fty)$ ou $x 
geq -3$

### Exemplo 3: Com Frações

$$ \frac{x}{2} - \frac{1}{3} > \frac{x}{6} + 1 $$

MMC(2, 3, 6) = 6:
$$ 3x - 2 > x + 6 $$
$$ 3x - x > 6 + 2 $$
$$ 2x > 8 $$
$$ x > 4 $$

**Solução:** $(4, +
fty)$

### Exemplo 4: Condição de Existência

$$ \frac{2x - 1}{x + 3} > 0 $$

Análise do sinal (regra dos sinais):
- Numerador: $2x - 1 = 0 \implies x = \frac{1}{2}$
- Denominador: $x + 3 = 0 \implies x = -3$ (excluído!)

| Intervalo | $2x - 1$ | $x + 3$ | Fração |
|-----------|----------|---------|--------|
| $x < -3$ | $-$ | $-$ | $+$ |
| $-3 < x < \frac{1}{2}$ | $-$ | $+$ | $-$ |
| $x > \frac{1}{2}$ | $+$ | $+$ | $+$ |

**Solução:** $(-\nfty, -3) \cup (\frac{1}{2}, +
fty)$

> **Atenção:** $x = -3$ é excluído (anula o denominador)!

## Exemplos de Notação

| Inequação | Notação de intervalo | Notação de conjunto | Reta real |
|-----------|------------------------|---------------------|-----------|
| $x > 3$ | $(3, +
fty)$ | $\{x \in \mathbb{R} \mid x > 3\}$ | bolha aberta em 3, linha à direita |
| $x 
leq 5$ | $(-
fty, 5]$ | $\{x \in \mathbb{R} \mid x 
leq 5\}$ | bolha fechada em 5, linha à esquerda |
| $-2 < x < 4$ | $(-2, 4)$ | $\{x \in \mathbb{R} \mid -2 < x < 4\}$ | bolhas abertas, linha entre elas |
| $x 
geq 1$ | $[1, +
fty)$ | $\{x \in \mathbb{R} \mid x 
geq 1\}$ | bolha fechada em 1, linha à direita |
| $x 
eq 2$ | $(-
fty, 2) \cup (2, +
fty)$ | $\{x \in \mathbb{R} \mid x 
eq 2\}$ | toda a reta exceto 2 |

## Aplicações na Vida Real

- **Finanças:** saldo mínimo ($x 
geq 500$), limite de crédito ($x 
leq 5000$)
- **Física:** temperatura de fusão ($T 
geq 0°C$ para água), velocidade máxima ($v 
leq 120$ km/h)
- **Engenharia:** tensão máxima, carga de trabalho ($c 
leq 100$ kg)
- **Medicina:** dosagem máxima, temperatura corporal ($36 
leq T 
leq 37$°C)
- **Estatística:** intervalo de confiança, margem de erro
- **Economia:** preço mínimo de venda, faixa de lucro
- **Jogos:** pontuação mínima para passar de fase, vida mínima
- **Geografia:** altitude mínima/máxima, profundidade
- **Cozinha:** temperatura do forno, tempo mínimo de cozimento
- **Esportes:** tempo máximo de prova, pontuação mínima para classificar

## Problemas

### Nível 1 — Básico

**1.** Resolva $3x + 7 > 16$.

$$ 3x > 9 \implies x > 3 $$

**Resposta:** $(3, +
fty)$ ou $x > 3$.

**2.** Resolva $-2x + 5 
geq 11$.

$$ -2x 
geq 6 \implies x 
leq -3 \quad \text{(inverteu!)} $$

**Resposta:** $(-
fty, -3]$ ou $x 
leq -3$.

**3.** Resolva $4x - 3 < 5x + 2$.

$$ -3 - 2 < 5x - 4x \implies -5 < x \implies x > -5 $$

**Resposta:** $(-5, +
fty)$ ou $x > -5$.

**4.** Resolva $5(x - 2) 
leq 3(x + 4)$.

$$ 5x - 10 
leq 3x + 12 $$
$$ 2x 
leq 22 \implies x 
leq 11 $$

**Resposta:** $(-
fty, 11]$ ou $x 
leq 11$.

**5.** Resolva $\frac{x}{3} + 2 > \frac{x}{2} - 1$.

MMC(3, 2) = 6:
$$ 2x + 12 > 3x - 6 $$
$$ 12 + 6 > 3x - 2x \implies 18 > x \implies x < 18 $$

**Resposta:** $(-
fty, 18)$ ou $x < 18$.

### Nível 2 — Intermediário

**6.** Resolva $2(x - 3) + 3(x + 1) 
geq 4(x - 2) + 7$.

$$ 2x - 6 + 3x + 3 
geq 4x - 8 + 7 $$
$$ 5x - 3 
geq 4x - 1 $$
$$ x 
geq 2 $$

**Resposta:** $[2, +
fty)$ ou $x 
geq 2$.

**7.** Resolva $\frac{2x - 1}{3} - \frac{x + 2}{2} < \frac{x - 3}{6}$.

MMC(3, 2, 6) = 6:
$$ 2(2x - 1) - 3(x + 2) < x - 3 $$
$$ 4x - 2 - 3x - 6 < x - 3 $$
$$ x - 8 < x - 3 $$
$$ -8 < -3 \quad \text{(sempre verdade!)} $$

**Resposta:** Todos os reais ($\mathbb{R}$ ou $(-
fty, +
fty)$).

**8.** Resolva $\frac{2x + 5}{x - 1} > 0$.

Análise de sinal:
- Numerador: $2x + 5 = 0 \implies x = -2{,}5$
- Denominador: $x - 1 = 0 \implies x = 1$ (excluído!)

| Intervalo | $2x+5$ | $x-1$ | Fração |
|-----------|--------|-------|--------|
| $x < -2{,}5$ | $-$ | $-$ | $+$ |
| $-2{,}5 < x < 1$ | $+$ | $-$ | $-$ |
| $x > 1$ | $+$ | $+$ | $+$ |

**Resposta:** $(-
fty, -2{,}5) \cup (1, +
fty)$.

**9.** Uma loja dá desconto de R$ 5,00 por item comprado acima de 10 unidades. Se um item custa R$ 20,00, quantos itens uma pessoa precisa comprar para gastar menos de R$ 300,00?

Se $x > 10$: preço por item = $20 - 5 = 15$
$$ 15x < 300 \implies x < 20 $$

Se $x 
leq 10$: $20x < 300 \implies x < 15$, mas $x 
leq 10$ já satisfaz.

**Resposta:** Até 19 itens (com desconto) ou até 10 sem desconto. Total: $x < 20$ itens.

**10.** Resolva $3 
leq 2x - 1 < 7$ (inequação dupla).

$$ 3 
leq 2x - 1 \implies 4 
leq 2x \implies x 
geq 2 $$
$$ 2x - 1 < 7 \implies 2x < 8 \implies x < 4 $$

**Resposta:** $[2, 4)$ ou $2 
leq x < 4$.

### Nível 3 — Desafio

**11.** Resolva $\frac{x - 2}{x + 3} 
leq \frac{x + 1}{x - 2}$.

$$ \frac{x - 2}{x + 3} - \frac{x + 1}{x - 2} 
leq 0 $$

MMC = $(x + 3)(x - 2)$:
$$ \frac{(x - 2)^2 - (x + 1)(x + 3)}{(x + 3)(x - 2)} 
leq 0 $$

Numerador:
$$ (x^2 - 4x + 4) - (x^2 + 4x + 3) = -8x + 1 $$

$$ \frac{-8x + 1}{(x + 3)(x - 2)} 
leq 0 $$

Zeros: $x = \frac{1}{8}$, $x = -3$, $x = 2$ (excluídos)

Análise de sinal:
| Intervalo | $-8x+1$ | $x+3$ | $x-2$ | Fração |
|-----------|----------|-------|-------|--------|
| $x < -3$ | $+$ | $-$ | $-$ | $+$ |
| $-3 < x < \frac{1}{8}$ | $+$ | $+$ | $-$ | $-$ |
| $\frac{1}{8} < x < 2$ | $-$ | $+$ | $-$ | $+$ |
| $x > 2$ | $-$ | $+$ | $+$ | $-$ |

Queremos $
leq 0$:
**Resposta:** $(-3, \frac{1}{8}] \cup (2, +
fty)$.

**12.** Resolva $|2x - 1| > 3$.

$$ 2x - 1 > 3 \implies 2x > 4 \implies x > 2 $$
$$ 2x - 1 < -3 \implies 2x < -2 \implies x < -1 $$

**Resposta:** $(-
fty, -1) \cup (2, +
fty)$.

**13.** Um fabricante produz um produto a um custo fixo de R$ 1000,00 mais R$ 5,00 por unidade. Ele vende a R$ 12,00 por unidade. Quantas unidades ele precisa vender para ter lucro de pelo menos R$ 2000,00?

Custo: $C = 1000 + 5x$
Receita: $R = 12x$
Lucro: $L = R - C = 12x - (1000 + 5x) = 7x - 1000$

$$ 7x - 1000 
geq 2000 $$
$$ 7x 
geq 3000 $$
$$ x 
geq \frac{3000}{7} \approx 428{,}57 $$

**Resposta:** Pelo menos 429 unidades.

---
**Fim — Inequações do 1º Grau**
