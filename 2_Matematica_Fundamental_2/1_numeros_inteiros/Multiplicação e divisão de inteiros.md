# Multiplicação e Divisão de Inteiros

A **multiplicação** e **divisão** de inteiros seguem regras específicas para os sinais. Uma vez compreendida a **regra de sinais**, essas operações tornam-se simples e intuitivas.

## Multiplicação de Inteiros

### Regra de Sinais

| Sinais | Resultado | Exemplo |
|--------|-----------|---------|
| $(+) \times (+)$ | $+$ | $3 \times 4 = 12$ |
| $(-) \times (-)$ | $+$ | $(-3) \times (-4) = 12$ |
| $(+) \times (-)$ | $-$ | $3 \times (-4) = -12$ |
| $(-) \times (+)$ | $-$ | $(-3) \times 4 = -12$ |

> **Regra mnemônica:**
> - **Sinais iguais = positivo** (mais com mais, menos com menos)
> - **Sinais diferentes = negativo** (mais com menos, menos com mais)

### Propriedades da Multiplicação

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| **Fechamento** | Produto de inteiros é inteiro | $(-3) \times 5 = -15 \in \mathbb{Z}$ |
| **Comutativa** | $a \times b = b \times a$ | $(-4) \times 3 = 3 \times (-4) = -12$ |
| **Associativa** | $(a \times b) \times c = a \times (b \times c)$ | $[(-2) \times 3] \times (-4) = (-2) \times [3 \times (-4)] = 24$ |
| **Elemento Neutro** | $a \times 1 = a$ | $(-7) \times 1 = -7$ |
| **Elemento Anulador** | $a \times 0 = 0$ | $(-9) \times 0 = 0$ |
| **Distributiva** | $a \times (b + c) = a \times b + a \times c$ | $(-2) \times (3 + 5) = (-2) \times 3 + (-2) \times 5 = -16$ |

### Produto de Múltiplos Fatores

Conte o número de fatores negativos:
- **Número par de negativos:** resultado positivo
- **Número ímpar de negativos:** resultado negativo

**Exemplo:** $(-2) \times (-3) \times (-4) \times (-5) \times (-1)$

Negativos: 5 (ímpar) → resultado **negativo**

$$ |(-2) \times (-3) \times (-4) \times (-5) \times (-1)| = 2 \times 3 \times 4 \times 5 \times 1 = 120 $$
$$ \text{Resultado} = -120 $$

## Divisão de Inteiros

### Regra de Sinais

As regras são as **mesmas** da multiplicação:

| Sinais | Resultado | Exemplo |
|--------|-----------|---------|
| $(+) \div (+)$ | $+$ | $12 \div 3 = 4$ |
| $(-) \div (-)$ | $+$ | $(-12) \div (-3) = 4$ |
| $(+) \div (-)$ | $-$ | $12 \div (-3) = -4$ |
| $(-) \div (+)$ | $-$ | $(-12) \div 3 = -4$ |

> **Divisão por zero é indefinida!** $a \div 0$ não existe (impossível).

### Divisão Não Exata

Quando a divisão não é exata, podemos ter quociente e resto (para inteiros positivos), ou frações/ decimais (para racionais).

**Para inteiros:** a divisão euclidiana exige que o resto seja não negativo e menor que o divisor.

**Exemplo:** $(-17) \div 5$

Queremos $-17 = 5 \times q + r$ com $0 \leq r < 5$:
$$ q = -4, \quad r = 3 \quad (-17 = 5 \times (-4) + 3 = -20 + 3) $$

> **Importante:** A regra "dividendo = divisor × quociente + resto" vale para inteiros, mas o resto deve ser sempre não negativo!

## Exemplos

### Multiplicação

#### Exemplo 1

$$ (-7) \times (-6) = 42 $$

Negativo × negativo = positivo. Valor absoluto: $7 \times 6 = 42$.

#### Exemplo 2

$$ (-5) \times 8 \times (-2) \times (-3) $$

Negativos: 3 (ímpar) → resultado negativo

$$ 5 \times 8 \times 2 \times 3 = 240 $$
$$ \text{Resultado} = -240 $$

#### Exemplo 3: Distributiva

$$ (-4) \times (7 + (-3)) = (-4) \times 7 + (-4) \times (-3) = -28 + 12 = -16 $$

Verificação: $(-4) \times 4 = -16$ ✓

### Divisão

#### Exemplo 4

$$ (-56) \div (-8) = 7 $$

Negativo ÷ negativo = positivo. $56 \div 8 = 7$.

#### Exemplo 5

$$ 45 \div (-9) = -5 $$

Positivo ÷ negativo = negativo.

#### Exemplo 6: Com resto

$$ (-23) \div 4 $$

$$ -23 = 4 \times (-6) + 1 \quad (0 \leq 1 < 4) $$

Quociente: $-6$, Resto: $1$

Verificação: $4 \times (-6) + 1 = -24 + 1 = -23$ ✓

## Aplicações na Vida Real

- **Finanças:** 5 prestações de R$ -200 (débito) = R$ -1.000 total
- **Temperatura:** temperatura cai 3°C por hora, em 5 horas: $-3 \times 5 = -15°C$ total
- **Jogos:** perde 10 pontos em cada uma de 4 fases: $-10 \times 4 = -40$ pontos
- **Física:** força para baixo (negativa) × deslocamento para baixo (negativo) = trabalho positivo
- **Química:** cargas iônicas em reações (balanceamento de equações)
- **Geografia:** latitude × longitude em coordenadas (norte/ sul, leste/ oeste)
- **Economia:** lucro/ prejuízo por unidade × número de unidades vendidas
- **Engenharia:** esforços e deformações com sinais (tração/ compressão)
- **Programação:** operações com coordenadas, vetores, pixels
- **Matemática:** fatoração, simplificação de expressões, potências

## Problemas

### Nível 1 — Básico

**1.** Calcule: $(-8) \times (-7)$

**Resposta:** $56$ (negativo × negativo = positivo)

**2.** Calcule: $(-9) \times 6$

**Resposta:** $-54$ (negativo × positivo = negativo)

**3.** Calcule: $(-48) \div (-6)$

**Resposta:** $8$ (negativo ÷ negativo = positivo)

**4.** Calcule: $35 \div (-5)$

**Resposta:** $-7$ (positivo ÷ negativo = negativo)

**5.** Calcule: $(-3) \times (-4) \times (-2)$

Negativos: 3 (ímpar) → resultado negativo

$$ 3 \times 4 \times 2 = 24 \implies \text{Resultado} = -24 $$

**Resposta:** $-24$

### Nível 2 — Intermediário

**6.** Calcule: $(-2)^3 \times (-3)^2 \times (-5)$

$$ (-2)^3 = -8 $$
$$ (-3)^2 = 9 $$
$$ (-8) \times 9 \times (-5) = (-72) \times (-5) = 360 $$

Negativos: 2 (par) → positivo ✓

**Resposta:** $360$

**7.** Aplique a distributiva: $(-5) \times [8 + (-3)]$

$$ (-5) \times 8 + (-5) \times (-3) = -40 + 15 = -25 $$

Verificação: $(-5) \times 5 = -25$ ✓

**Resposta:** $-25$

**8.** Um navio afunda 2 metros por hora. Qual sua profundidade após 7 horas? Use número negativo para representar abaixo do nível do mar.

$$ -2 \times 7 = -14 \text{ m} $$

**Resposta:** $-14$ m (14 m abaixo do nível do mar).

**9.** Calcule o quociente e resto de $(-37) \div 5$.

$$ -37 = 5 \times (-8) + 3 \quad (0 \leq 3 < 5) $$

Quociente: $-8$, Resto: $3$

Verificação: $5 \times (-8) + 3 = -40 + 3 = -37$ ✓

**Resposta:** Quociente = $-8$, Resto = $3$.

**10.** Se $a = -4$ e $b = -6$, calcule $a \times b$, $a \div b$, $b \div a$, e $a \times (a + b)$.

$$ a \times b = (-4) \times (-6) = 24 $$
$$ a \div b = (-4) \div (-6) = \frac{2}{3} \text{ (não inteiro!)} $$

> **Aviso:** Divisão de inteiros nem sempre resulta em inteiro! Se quisermos quociente e resto: $-4 = (-6) \times 1 + 2$ (resto 2, quociente 1). Ou $-4 = (-6) \times 0 + (-4)$ (resto não negativo... complicado).

Se interpretarmos como fração (números racionais): $(-4) \div (-6) = \frac{2}{3}$.

$$ b \div a = (-6) \div (-4) = \frac{3}{2} = 1{,}5 $$
$$ a \times (a + b) = (-4) \times (-4 - 6) = (-4) \times (-10) = 40 $$

**Resposta:** $a \times b = 24$; $a \div b = \frac{2}{3}$; $b \div a = \frac{3}{2}$; $a \times (a + b) = 40$.

### Nível 3 — Desafio

**11.** Se $a = -2$, $b = 3$, e $c = -4$, calcule $(a \times b) \div c + (b \times c) \div a$.

$$ a \times b = (-2) \times 3 = -6 $$
$$ (-6) \div (-4) = \frac{3}{2} = 1{,}5 $$

$$ b \times c = 3 \times (-4) = -12 $$
$$ (-12) \div (-2) = 6 $$

$$ 1{,}5 + 6 = 7{,}5 = \frac{15}{2} $$

**Resposta:** $\frac{15}{2}$ ou $7{,}5$.

**12.** Calcule o produto: $(-1) \times (-2) \times (-3) \times \ldots \times (-10)$.

São 10 fatores negativos (par) → resultado positivo.

$$ |\text{Produto}| = 1 \times 2 \times 3 \times \ldots \times 10 = 10! = 3.628.800 $$

**Resposta:** $+3.628.800$ (ou $10!$)

**13.** Determine o sinal do produto $(-1) \times (-1)^2 \times (-1)^3 \times \ldots \times (-1)^{20}$ sem calcular o valor.

Cada termo: $(-1)^n$ vale:
- $n$ ímpar: $-1$
- $n$ par: $+1$

Termos de 1 a 20: ímpares são 1, 3, 5, ..., 19 (10 termos ímpares = 10 termos valendo $-1$)
Pares são 2, 4, 6, ..., 20 (10 termos pares = 10 termos valendo $+1$)

Produto: $(-1)^{10} \times (+1)^{10} = (+1) \times (+1) = +1$

Sinal: **positivo**.

**Resposta:** Positivo (o produto vale $+1$).

---
**Fim — Multiplicação e Divisão de Inteiros**
