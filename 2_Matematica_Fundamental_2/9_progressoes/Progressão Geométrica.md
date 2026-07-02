# Progressão Geométrica (PG)

Uma **Progressão Geométrica (PG)** é uma sequência numérica em que cada termo, a partir do segundo, é obtido multiplicando o termo anterior por uma constante chamada **razão**. PGs descrevem crescimentos e decaimentos exponenciais: juros compostos, cadeias de epidemias, decaimento radioativo, e memória de computadores.

## Conceito

$$ a_1, a_2, a_3, \ldots, a_n, \ldots $$

Onde:

$$ a_{n+1} = a_n \cdot q \quad \text{(para todo } n \geq 1 \text{)} $$

- $a_1$ = **primeiro termo**
- $q$ = **razão** (constante multiplicada)
- $a_n$ = termo de ordem $n$

## Classificação

| Razão | Tipo | Exemplo |
|-------|------|---------|
| $q > 1$ e $a_1 > 0$ | **Crescente** | $2, 6, 18, 54, \ldots$ |
| $0 < q < 1$ e $a_1 > 0$ | **Decrescente** | $81, 27, 9, 3, \ldots$ |
| $q = 1$ | **Constante** | $5, 5, 5, 5, \ldots$ |
| $q < 0$ | **Alternante** (sinais alternados) | $3, -6, 12, -24, \ldots$ |
| $q = 0$ | **Nula** a partir do 2º termo | $5, 0, 0, 0, \ldots$ |
| $q = -1$ | **Alternante constante** | $7, -7, 7, -7, \ldots$ |

> **Atenção:** Se $a_1 = 0$, todos os termos são 0 (PG trivial). Se $q = 0$, a partir do 2º termo são todos 0.

## Termo Geral

$$ a_n = a_1 \cdot q^{n-1} $$

**Demonstração:**
- $a_2 = a_1 \cdot q = a_1 \cdot q^1$
- $a_3 = a_2 \cdot q = a_1 \cdot q^2$
- $a_4 = a_3 \cdot q = a_1 \cdot q^3$
- $\vdots$
- $a_n = a_1 \cdot q^{n-1}$

### Exemplo

Na PG $(3, 6, 12, 24, \ldots)$:
- $a_1 = 3$, $q = 2$
- $a_8 = 3 \cdot 2^{7} = 3 \cdot 128 = 384$
- $a_{10} = 3 \cdot 2^9 = 3 \cdot 512 = 1536$

## Soma dos Termos de uma PG Finita

$$ S_n = a_1 + a_2 + a_3 + \ldots + a_n $$

Fórmula:

$$ S_n = a_1 \cdot \frac{q^n - 1}{q - 1} \quad \text{(para } q \neq 1 \text{)} $$

Para $q = 1$: $S_n = n \cdot a_1$

**Demonstração:**

$$ S_n = a_1 + a_1q + a_1q^2 + \ldots + a_1q^{n-1} $$
$$ q \cdot S_n = a_1q + a_1q^2 + \ldots + a_1q^{n-1} + a_1q^n $$

Subtraindo:
$$ S_n - qS_n = a_1 - a_1q^n $$
$$ S_n(1 - q) = a_1(1 - q^n) $$
$$ S_n = a_1 \cdot \frac{1 - q^n}{1 - q} = a_1 \cdot \frac{q^n - 1}{q - 1} $$

### Exemplo

Calcule a soma dos 6 primeiros termos da PG $(2, 4, 8, 16, \ldots)$:

- $a_1 = 2$, $q = 2$, $n = 6$
- $S_6 = 2 \cdot \frac{2^6 - 1}{2 - 1} = 2 \cdot \frac{64 - 1}{1} = 2 \cdot 63 = 126$

Verificação: $2 + 4 + 8 + 16 + 32 + 64 = 126$ ✓

## Soma dos Termos de uma PG Infinita (Convergente)

Quando $|q| < 1$, a PG infinita converge:

$$ S_{\infty} = a_1 + a_1q + a_1q^2 + a_1q^3 + \ldots = \frac{a_1}{1 - q} $$

**Intuição:** Como $|q| < 1$, $q^n \to 0$ quando $n \to \infty$. Então:

$$ S_{\infty} = \lim_{n \to \infty} a_1 \cdot \frac{1 - q^n}{1 - q} = \frac{a_1}{1 - q} $$

### Exemplo

$$ S = 1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \ldots = \frac{1}{1 - \frac{1}{2}} = \frac{1}{\frac{1}{2}} = 2 $$

## Propriedades Importantes

### Propriedade Central

Em uma PG, cada termo (exceto os extremos) é a **média geométrica** dos seus vizinhos:

$$ a_k^2 = a_{k-1} \cdot a_{k+1} $$

$$ a_k = \sqrt{a_{k-1} \cdot a_{k+1}} \quad \text{(para } a_k > 0 \text{)} $$

### Propriedade de Simetria

$$ a_1 \cdot a_n = a_2 \cdot a_{n-1} = a_3 \cdot a_{n-2} = \ldots $$

## PG como Função Exponencial

O termo geral de uma PG é uma **função exponencial** de $n$:

$$ a_n = a_1 \cdot q^{n-1} = \frac{a_1}{q} \cdot q^n $$

Ou seja, $a_n = C \cdot q^n$ onde $C = \frac{a_1}{q}$.

### Exemplo

Para $a_n = 5 \cdot 2^n$:
- $a_1 = 10$, $q = 2$
- PG: $(10, 20, 40, 80, \ldots)$

## Interpolação Geométrica

Inserir $k$ meios geométricos entre dois termos $a$ e $b$ (ambos positivos ou ambos negativos):

$$ q = \sqrt[k+1]{\frac{b}{a}} $$

### Exemplo

Inserir 3 meios geométricos entre 2 e 32:

$$ q = \sqrt[4]{\frac{32}{2}} = \sqrt[4]{16} = 2 $$

PG: $(2, 4, 8, 16, 32)$

## Aplicações na Vida Real

- **Finanças:** juros compostos, rendimento de investimentos
- **Biologia:** crescimento de populações (bactérias, vírus)
- **Física:** decaimento radioativo, meia-vida
- **Engenharia:** escala de decibéis (logarítmica baseada em PG)
- **Tecnologia:** Lei de Moore (dobrar transistores), memória RAM (capacidades dobram)
- **Epidemiologia:** fase inicial de propagação de doenças (contatos)
- **Jogos:** dano duplicado, combos exponenciais, experiência por nível
- **Música:** escala de frequências (oitavas, frequências dobram)
- **Arte:** fractais, subdivisões geométricas
- **Estatística:** esperança em jogos de azar, distribuição geométrica

## Problemas

### Nível 1 — Básico

**1.** Determine o 6º termo da PG $(2, 6, 18, \ldots)$.

$$ a_1 = 2, q = 3 $$
$$ a_6 = 2 \cdot 3^{5} = 2 \cdot 243 = 486 $$

**Resposta:** $a_6 = 486$.

**2.** Qual a razão da PG $(81, 27, 9, 3, \ldots)$?

$$ q = \frac{27}{81} = \frac{1}{3} $$

**Resposta:** $q = \frac{1}{3}$ (PG decrescente).

**3.** Calcule a soma dos 5 primeiros termos da PG $(1, 2, 4, \ldots)$.

$$ a_1 = 1, q = 2, n = 5 $$
$$ S_5 = 1 \cdot \frac{2^5 - 1}{2 - 1} = \frac{32 - 1}{1} = 31 $$

**Resposta:** $S_5 = 31$.

**4.** Encontre o primeiro termo de uma PG onde $a_4 = 24$ e $q = 2$.

$$ a_4 = a_1 \cdot q^3 = 24 $$
$$ a_1 \cdot 8 = 24 \implies a_1 = 3 $$

**Resposta:** $a_1 = 3$.

**5.** Calcule a soma infinita: $S = 8 + 4 + 2 + 1 + \frac{1}{2} + \ldots$

$$ a_1 = 8, q = \frac{1}{2} \quad (|q| < 1 \text{, converge!}) $$
$$ S = \frac{8}{1 - \frac{1}{2}} = \frac{8}{\frac{1}{2}} = 16 $$

**Resposta:** $S = 16$.

### Nível 2 — Intermediário

**6.** O 3º termo de uma PG é 12 e o 6º termo é 96. Determine o 1º termo e a razão.

$$ a_3 = a_1 \cdot q^2 = 12 $$
$$ a_6 = a_1 \cdot q^5 = 96 $$

Dividindo: $\frac{a_6}{a_3} = q^3 = \frac{96}{12} = 8 \implies q = 2$

$$ a_1 \cdot 4 = 12 \implies a_1 = 3 $$

**Resposta:** $a_1 = 3$, $q = 2$.

**7.** Um investimento de R$ 1000,00 rende 10% ao ano. Qual o montante após 5 anos? (Use PG)

PG dos montantes anuais: $(1000, 1100, 1210, 1331, 1464,1, \ldots)$

$$ a_5 = 1000 \cdot (1{,}1)^5 = 1000 \cdot 1{,}61051 = 1610{,}51 $$

Ou usando a soma? Não, o montante no final do ano $n$ é $a_n = 1000(1,1)^n$.

$$ M_5 = 1000 \cdot (1{,}1)^5 = 1610{,}51 $$

**Resposta:** R$ 1610,51.

**8.** Uma bola é jogada de uma altura de 10 m. A cada quicada, ela sobe a metade da altura anterior. Qual a distância total percorrida até parar?

Queda: $10 + 5 + 2{,}5 + 1{,}25 + \ldots = \frac{10}{1 - 1/2} = 20$ m
Sobe: $5 + 2{,}5 + 1{,}25 + \ldots = \frac{5}{1 - 1/2} = 10$ m

Total: $20 + 10 = 30$ m

**Resposta:** 30 m.

**9.** Inserir 4 meios geométricos entre 1 e 243.

$$ q = \sqrt[5]{\frac{243}{1}} = \sqrt[5]{243} = 3 $$

PG: $(1, 3, 9, 27, 81, 243)$

**Resposta:** 3, 9, 27, 81.

**10.** Uma cultura de bactérias triplica a cada hora. Se começa com 200 bactérias, quantas haverá após 6 horas?

$$ a_7 = 200 \cdot 3^6 = 200 \cdot 729 = 145800 $$

**Resposta:** 145.800 bactérias.

### Nível 3 — Desafio

**11.** Prove que em uma PG finita com $n$ termos, $a_k \cdot a_{n+1-k} = a_1 \cdot a_n$ para qualquer $k$.

$$ a_k = a_1 \cdot q^{k-1} $$
$$ a_{n+1-k} = a_1 \cdot q^{n+1-k-1} = a_1 \cdot q^{n-k} $$

$$ a_k \cdot a_{n+1-k} = a_1 \cdot q^{k-1} \cdot a_1 \cdot q^{n-k} = a_1^2 \cdot q^{n-1} $$
$$ = a_1 \cdot (a_1 \cdot q^{n-1}) = a_1 \cdot a_n $$

**Resposta:** Prova verificada. Propriedade de simetria da PG.

**12.** A soma dos $n$ primeiros termos de uma PG é $S_n = 2(3^n - 1)$. Determine o 5º termo e a razão.

$$ a_n = S_n - S_{n-1} \text{ (para } n \geq 2 \text{)} $$
$$ a_n = 2(3^n - 1) - 2(3^{n-1} - 1) $$
$$ = 2 \cdot 3^n - 2 - 2 \cdot 3^{n-1} + 2 $$
$$ = 2 \cdot 3^n - 2 \cdot 3^{n-1} $$
$$ = 2 \cdot 3^{n-1}(3 - 1) = 4 \cdot 3^{n-1} $$

$$ a_1 = S_1 = 2(3 - 1) = 4 $$
Verificação: $a_1 = 4 \cdot 3^0 = 4$ ✓

$$ a_5 = 4 \cdot 3^4 = 4 \cdot 81 = 324 $$
$$ q = \frac{a_2}{a_1} = \frac{4 \cdot 3^1}{4} = 3 $$

**Resposta:** $a_5 = 324$, $q = 3$.

**13.** Seja a PG infinita $(1, x, x^2, x^3, \ldots)$ com $0 < x < 1$. Se a soma é $\frac{5}{4}$, determine $x$.

$$ S_{\infty} = \frac{1}{1 - x} = \frac{5}{4} $$
$$ 1 - x = \frac{4}{5} $$
$$ x = 1 - \frac{4}{5} = \frac{1}{5} = 0{,}2 $$

**Resposta:** $x = \frac{1}{5}$ ou $0{,}2$.

---
**Fim — Progressão Geométrica (PG)**
