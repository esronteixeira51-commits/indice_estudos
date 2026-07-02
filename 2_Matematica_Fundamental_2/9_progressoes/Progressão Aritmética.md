# Progressão Aritmética (PA)

Uma **Progressão Aritmética (PA)** é uma sequência numérica em que cada termo, a partir do segundo, é obtido somando uma constante chamada **razão** ao termo anterior. PAs aparecem em pagamentos parcelados, escadas, filas de assentos em teatros, e muitos outros contextos do dia a dia.

## Conceito

$$ a_1, a_2, a_3, \ldots, a_n, \ldots $$

Onde:

$$ a_{n+1} = a_n + r \quad \text{(para todo } n \geq 1 \text{)} $$

- $a_1$ = **primeiro termo**
- $r$ = **razão** (constante adicionada)
- $a_n$ = termo de ordem $n$

## Classificação

| Razão | Tipo | Exemplo |
|-------|------|---------|
| $r > 0$ | **Crescente** | $2, 5, 8, 11, \ldots$ |
| $r < 0$ | **Decrescente** | $10, 7, 4, 1, \ldots$ |
| $r = 0$ | **Constante** | $3, 3, 3, 3, \ldots$ |

## Termo Geral

$$ a_n = a_1 + (n - 1) \cdot r $$

**Demonstração:**
- $a_2 = a_1 + r = a_1 + 1r$
- $a_3 = a_2 + r = a_1 + 2r$
- $a_4 = a_3 + r = a_1 + 3r$
- $\vdots$
- $a_n = a_1 + (n - 1)r$

### Exemplo

Na PA $(3, 7, 11, 15, \ldots)$:
- $a_1 = 3$, $r = 4$
- $a_{10} = 3 + 9 \cdot 4 = 3 + 36 = 39$
- $a_{25} = 3 + 24 \cdot 4 = 3 + 96 = 99$

## Soma dos Termos de uma PA Finita

$$ S_n = a_1 + a_2 + a_3 + \ldots + a_n $$

Fórmula:

$$ S_n = \frac{(a_1 + a_n) \cdot n}{2} $$

Ou, usando o termo geral:

$$ S_n = \frac{[2a_1 + (n - 1)r] \cdot n}{2} $$

**Demonstração (método de Gauss):**

Escrevemos a soma na ordem direta e na inversa:

$$ S_n = a_1 + a_2 + \ldots + a_{n-1} + a_n $$
$$ S_n = a_n + a_{n-1} + \ldots + a_2 + a_1 $$

Somando termo a termo: cada par $(a_1 + a_n), (a_2 + a_{n-1}), \ldots$ vale $a_1 + a_n$ (propriedade da PA: $a_k + a_{n+1-k} = a_1 + a_n$).

$$ 2S_n = n \cdot (a_1 + a_n) $$
$$ S_n = \frac{n(a_1 + a_n)}{2} $$

### Exemplo

Calcule a soma dos 20 primeiros termos da PA $(2, 5, 8, \ldots)$:

- $a_1 = 2$, $r = 3$
- $a_{20} = 2 + 19 \cdot 3 = 2 + 57 = 59$
- $S_{20} = \frac{(2 + 59) \cdot 20}{2} = \frac{61 \cdot 20}{2} = 610$

## Propriedades Importantes

### Propriedade Central

Em uma PA, cada termo (exceto os extremos) é a **média aritmética** dos seus vizinhos:

$$ a_k = \frac{a_{k-1} + a_{k+1}}{2} $$

### Propriedade de Simetria

$$ a_1 + a_n = a_2 + a_{n-1} = a_3 + a_{n-2} = \ldots $$

## PA como Função Afim

O termo geral de uma PA é uma **função afim** de $n$:

$$ a_n = rn + (a_1 - r) $$

Ou seja, $a_n = f(n)$ onde $f$ é uma função afim com coeficiente angular $r$.

### Exemplo

Para $a_n = 3n + 2$:
- $a_1 = 5$, $r = 3$
- PA: $(5, 8, 11, 14, \ldots)$

## Interpolação Aritmética

Inserir $k$ meios aritméticos entre dois termos $a$ e $b$:

$$ r = \frac{b - a}{k + 1} $$

### Exemplo

Inserir 3 meios aritméticos entre 4 e 20:

$$ r = \frac{20 - 4}{3 + 1} = \frac{16}{4} = 4 $$

PA: $(4, 8, 12, 16, 20)$

## Aplicações na Vida Real

- **Finanças:** prestações em amortização constante (SAC)
- **Física:** movimento uniformemente variado (MUV) — posição em função do tempo
- **Construção:** escadas com degraus de altura constante
- **Música:** escala cromática (intervalos de semitom constante)
- **Astronomia:** distâncias de Bode (aproximação PA para distâncias planetárias)
- **Arquitetura:** fileiras de assentos em teatros, fileiras de árvores
- **Esportes:** contagem regressiva, intervalos de treino
- **Jogos:** dano crescente por nível, progressão linear de XP
- **Estatística:** médias móveis, tendência linear
- **Engenharia:** viga sob carga distribuída uniformemente (variação linear de tensão)

## Problemas

### Nível 1 — Básico

**1.** Determine o 10º termo da PA $(5, 8, 11, \ldots)$.

$$ a_1 = 5, r = 3 $$
$$ a_{10} = 5 + 9 \cdot 3 = 5 + 27 = 32 $$

**Resposta:** $a_{10} = 32$.

**2.** Qual a razão da PA $(20, 16, 12, 8, \ldots)$?

$$ r = 16 - 20 = -4 $$

**Resposta:** $r = -4$ (PA decrescente).

**3.** Calcule a soma dos 10 primeiros termos da PA $(1, 3, 5, 7, \ldots)$.

$$ a_1 = 1, r = 2, a_{10} = 1 + 9 \cdot 2 = 19 $$
$$ S_{10} = \frac{(1 + 19) \cdot 10}{2} = \frac{20 \cdot 10}{2} = 100 $$

**Resposta:** $S_{10} = 100$.

**4.** Encontre o primeiro termo de uma PA onde $a_5 = 17$ e $r = 3$.

$$ a_5 = a_1 + 4r = 17 $$
$$ a_1 + 12 = 17 \implies a_1 = 5 $$

**Resposta:** $a_1 = 5$.

**5.** Quantos termos tem a PA $(3, 7, 11, \ldots, 47)$?

$$ a_n = 47 = 3 + (n-1) \cdot 4 $$
$$ 44 = (n-1) \cdot 4 \implies n - 1 = 11 \implies n = 12 $$

**Resposta:** 12 termos.

### Nível 2 — Intermediário

**6.** Calcule a soma de todos os números ímpares de 1 a 99.

PA: $(1, 3, 5, \ldots, 99)$
- $a_1 = 1$, $r = 2$, $a_n = 99$
- $99 = 1 + (n-1) \cdot 2 \implies 98 = 2(n-1) \implies n = 50$
- $S_{50} = \frac{(1 + 99) \cdot 50}{2} = \frac{100 \cdot 50}{2} = 2500$

**Resposta:** 2500.

**7.** O 3º termo de uma PA é 8 e o 7º termo é 20. Determine o 1º termo e a razão.

$$ a_3 = a_1 + 2r = 8 $$
$$ a_7 = a_1 + 6r = 20 $$

Subtraindo: $4r = 12 \implies r = 3$
$$ a_1 + 6 = 8 \implies a_1 = 2 $$

**Resposta:** $a_1 = 2$, $r = 3$.

**8.** Quantos múltiplos de 7 existem entre 100 e 1000?

Primeiro múltiplo de 7 após 100: $7 \times 15 = 105$
Último múltiplo de 7 antes de 1000: $7 \times 142 = 994$

PA: $(105, 112, 119, \ldots, 994)$
- $a_1 = 105$, $r = 7$, $a_n = 994$
- $994 = 105 + (n-1) \cdot 7$
- $889 = (n-1) \cdot 7 \implies n - 1 = 127 \implies n = 128$

**Resposta:** 128 múltiplos.

**9.** A soma dos 15 primeiros termos de uma PA é 225. Se o 15º termo é 29, determine o 1º termo.

$$ S_{15} = \frac{(a_1 + a_{15}) \cdot 15}{2} = 225 $$
$$ \frac{(a_1 + 29) \cdot 15}{2} = 225 $$
$$ (a_1 + 29) \cdot 15 = 450 $$
$$ a_1 + 29 = 30 \implies a_1 = 1 $$

**Resposta:** $a_1 = 1$.

**10.** Inserir 5 meios aritméticos entre 2 e 20.

$$ r = \frac{20 - 2}{5 + 1} = \frac{18}{6} = 3 $$

PA: $(2, 5, 8, 11, 14, 17, 20)$

**Resposta:** 5, 8, 11, 14, 17.

### Nível 3 — Desafio

**11.** Prove que em uma PA finita com $n$ termos, $a_k + a_{n+1-k} = a_1 + a_n$ para qualquer $k$.

$$ a_k = a_1 + (k-1)r $$
$$ a_{n+1-k} = a_1 + (n+1-k-1)r = a_1 + (n-k)r $$

$$ a_k + a_{n+1-k} = a_1 + (k-1)r + a_1 + (n-k)r = 2a_1 + (n-1)r $$
$$ = a_1 + [a_1 + (n-1)r] = a_1 + a_n $$

**Resposta:** Prova verificada. Propriedade de simetria da PA.

**12.** A soma dos $n$ primeiros termos de uma PA é $S_n = 3n^2 + 5n$. Determine o 10º termo e a razão.

$$ a_n = S_n - S_{n-1} \text{ (para } n \geq 2 \text{)} $$
$$ a_n = (3n^2 + 5n) - [3(n-1)^2 + 5(n-1)] $$
$$ = 3n^2 + 5n - 3(n^2 - 2n + 1) - 5n + 5 $$
$$ = 3n^2 + 5n - 3n^2 + 6n - 3 - 5n + 5 $$
$$ = 6n + 2 $$

$$ a_1 = S_1 = 3 + 5 = 8 $$
Verificação: $a_1 = 6(1) + 2 = 8$ ✓

$$ a_{10} = 6(10) + 2 = 62 $$
$$ r = a_2 - a_1 = (6 \cdot 2 + 2) - 8 = 14 - 8 = 6 $$

**Resposta:** $a_{10} = 62$, $r = 6$.

**13.** Uma escada tem 20 degraus. O primeiro degrau tem 20 cm de altura, e cada degrau seguinte tem 3 cm a mais que o anterior. Qual a altura total da escada até o 20º degrau?

PA: $(20, 23, 26, \ldots)$
- $a_1 = 20$, $r = 3$, $n = 20$
- $a_{20} = 20 + 19 \cdot 3 = 20 + 57 = 77$ cm
- $S_{20} = \frac{(20 + 77) \cdot 20}{2} = \frac{97 \cdot 20}{2} = 970$ cm

**Resposta:** 970 cm = 9,70 m.

---
**Fim — Progressão Aritmética (PA)**
