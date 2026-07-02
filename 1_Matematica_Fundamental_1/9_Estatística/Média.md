# Média

A **média** é uma medida de tendência central que representa o valor "típico" ou "equilibrado" de um conjunto de dados. É a medida mais conhecida e usada da estatística, aparecendo em notas escolares, salários, temperaturas, avaliações de produtos e incontáveis situações do dia a dia.

## Definição

A média aritmética (simples) é a **soma de todos os valores dividida pelo número de valores**.

$$ \bar{x} = \frac{x_1 + x_2 + x_3 + \ldots + x_n}{n} = \frac{\sum_{i=1}^{n} x_i}{n} $$

Onde:
- $\bar{x}$ (x-barra) = média
- $x_i$ = cada valor do conjunto
- $n$ = número total de valores
- $\sum$ (sigma) = somatório

## Cálculo da Média Aritmética Simples

### Exemplo 1

Notas de um aluno: 6, 7, 8, 9, 5

$$ \bar{x} = \frac{6 + 7 + 8 + 9 + 5}{5} = \frac{35}{5} = 7 $$

**Interpretação:** A nota média do aluno é 7.

### Exemplo 2

Temperaturas diárias: 22°, 25°, 24°, 23°, 26°

$$ \bar{x} = \frac{22 + 25 + 24 + 23 + 26}{5} = \frac{120}{5} = 24° $$

**Interpretação:** A temperatura média foi 24°.

## Média Aritmética Ponderada

Quando os valores têm **pesos** ou **importâncias** diferentes.

$$ \bar{x}_p = \frac{x_1 \cdot p_1 + x_2 \cdot p_2 + \ldots + x_n \cdot p_n}{p_1 + p_2 + \ldots + p_n} = \frac{\sum x_i \cdot p_i}{\sum p_i} $$

### Exemplo

Notas de um aluno com pesos diferentes:
- Prova 1: nota 6, peso 2
- Prova 2: nota 8, peso 3
- Prova 3: nota 7, peso 5

$$ \bar{x}_p = \frac{6 \times 2 + 8 \times 3 + 7 \times 5}{2 + 3 + 5} = \frac{12 + 24 + 35}{10} = \frac{71}{10} = 7{,}1 $$

> Sem os pesos, a média simples seria $\frac{6+8+7}{3} = 7$.

## Média com Dados Agrupados (Frequência)

Quando temos uma tabela de frequência, multiplicamos cada valor por sua frequência.

$$ \bar{x} = \frac{\sum x_i \cdot f_i}{\sum f_i} = \frac{\sum x_i \cdot f_i}{n} $$

### Exemplo

| Nota ($x_i$) | Frequência ($f_i$) | $x_i \cdot f_i$ |
|--------------|-------------------|----------------|
| 5 | 3 | 15 |
| 6 | 4 | 24 |
| 7 | 5 | 35 |
| 8 | 5 | 40 |
| 9 | 3 | 27 |
| **Total** | **20** | **141** |

$$ \bar{x} = \frac{141}{20} = 7{,}05 $$

## Média com Dados em Classes

Para dados agrupados em intervalos, usa-se o **ponto médio** de cada classe.

$$ \bar{x} = \frac{\sum x_i \cdot f_i}{n} $$

Onde $x_i$ = ponto médio da classe.

### Exemplo

| Classes (cm) | Ponto Médio ($x_i$) | $f_i$ | $x_i \cdot f_i$ |
|--------------|----------------------|-------|----------------|
| 150 ⊢ 157 | 153,5 | 3 | 460,5 |
| 157 ⊢ 164 | 160,5 | 5 | 802,5 |
| 164 ⊢ 171 | 167,5 | 7 | 1.172,5 |
| 171 ⊢ 178 | 174,5 | 8 | 1.396,0 |
| 178 ⊢ 185 | 181,5 | 5 | 907,5 |
| 185 ⊢ 192 | 188,5 | 2 | 377,0 |
| **Total** | | **30** | **5.116,0** |

$$ \bar{x} = \frac{5.116}{30} = 170{,}53 \text{ cm} $$

## Outras Médias

### Média Geométrica
Usada para taxas de crescimento, retornos de investimentos.

$$ G = \sqrt[n]{x_1 \cdot x_2 \cdot \ldots \cdot x_n} $$

**Exemplo:** Crescimento anual de 10%, 20%, -5%

$$ G = \sqrt[3]{1{,}10 \times 1{,}20 \times 0{,}95} = \sqrt[3]{1{,}254} = 1{,}078 $$

Crescimento médio: **7,8% ao ano**.

> A média aritmética daria $(10+20-5)/3 = 8,33\%$, que superestima o crescimento real.

### Média Harmônica
Usada para taxas, velocidades médias quando as distâncias são iguais.

$$ H = \frac{n}{\frac{1}{x_1} + \frac{1}{x_2} + \ldots + \frac{1}{x_n}} $$

**Exemplo:** Ida a 60 km/h, volta a 40 km/h. Velocidade média?

$$ H = \frac{2}{\frac{1}{60} + \frac{1}{40}} = \frac{2}{\frac{2+3}{120}} = \frac{2}{\frac{5}{120}} = \frac{2 \times 120}{5} = 48 \text{ km/h} $$

> A média aritmética $(60+40)/2 = 50$ km/h estaria **errada**!

## Propriedades da Média Aritmética

### 1. Soma dos Desvios é Zero

$$ \sum (x_i - \bar{x}) = 0 $$

A soma das diferenças entre cada valor e a média é sempre zero.

### 2. Mínimo da Soma dos Quadrados

A média é o valor que **minimiza** a soma dos quadrados dos desvios:

$$ \sum (x_i - \bar{x})^2 \text{ é mínima} $$

### 3. Sensível a Valores Extremos (Outliers)

A média é fortemente influenciada por valores muito altos ou muito baixos.

**Exemplo:** Salários: R$ 2.000, R$ 2.500, R$ 3.000, R$ 3.500, R$ 50.000

$$ \bar{x} = \frac{2.000 + 2.500 + 3.000 + 3.500 + 50.000}{5} = \frac{61.000}{5} = 12.200 $$

A média de R$ 12.200 **não representa** bem os 4 primeiros salários! O valor de R$ 50.000 "puxa" a média para cima.

> **Alternativa:** Para dados com outliers, a **mediana** é mais representativa.

## Mediana (Medida Alternativa)

A **mediana** é o valor que divide os dados ordenados ao meio: 50% dos dados estão abaixo e 50% acima.

### Cálculo

1. Ordene os dados
2. Se $n$ é ímpar: mediana = valor do meio
3. Se $n$ é par: mediana = média dos dois valores do meio

**Exemplo:** 2, 5, 7, 8, 10, 12, 15 (n = 7, ímpar)

Mediana = **8** (o 4º valor)

**Exemplo:** 2, 5, 7, 8, 10, 12 (n = 6, par)

Mediana = $\frac{7+8}{2} = 7{,}5$

## Moda

A **moda** é o valor que aparece com **maior frequência**.

**Exemplo:** 2, 3, 3, 4, 5, 5, 5, 6, 7

Moda = **5** (aparece 3 vezes)

> Uma distribuição pode ter uma moda (unimodal), duas (bimodal), ou mais (multimodal), ou nenhuma (amodal).

## Comparação: Média, Mediana, Moda

| Característica | Média | Mediana | Moda |
|----------------|-------|---------|------|
| Usa todos os dados | Sim | Não | Não |
| Sensível a outliers | Sim | Não | Não |
| Pode ser usada com dados qualitativos | Não | Não | Sim |
| Única | Sempre | Sempre | Pode ter várias |
| Melhor para | Dados simétricos | Dados assimétricos | Dados categóricos |

## Média na Vida Real

- **Notas escolares:** média bimestral, média final
- **Salários:** salário médio de uma profissão (cuidado com outliers!)
- **Temperatura:** temperatura média do mês, do ano
- **Esportes:** média de pontos por jogo, média de gols
- **Economia:** renda média per capita, PIB per capita
- **Saúde:** pressão arterial média, batimentos cardíacos médios
- **Avaliações:** nota média de produtos (estrelas), média de satisfação
- **Meteorologia:** pluviosidade média, umidade média

## Problemas de Média

### Nível 1 — Básico

**1.** Calcule a média: 4, 6, 8, 10, 12

$$ \bar{x} = \frac{4 + 6 + 8 + 10 + 12}{5} = \frac{40}{5} = 8 $$

**2.** Notas de João: 5, 7, 8. Qual a média?

$$ \bar{x} = \frac{5 + 7 + 8}{3} = \frac{20}{3} = 6{,}67 $$

### Nível 2 — Intermediário

**3.** Uma prova tem 3 questões valendo 2, 3 e 5 pontos. Um aluno tirou 8, 6 e 7. Qual a média ponderada?

$$ \bar{x}_p = \frac{8 \times 2 + 6 \times 3 + 7 \times 5}{2 + 3 + 5} = \frac{16 + 18 + 35}{10} = \frac{69}{10} = 6{,}9 $$

**4.** Calcule a média da tabela:

| Valor | $f_i$ |
|-------|-------|
| 2 | 5 |
| 4 | 8 |
| 6 | 4 |
| 8 | 3 |

$$ \bar{x} = \frac{2 \times 5 + 4 \times 8 + 6 \times 4 + 8 \times 3}{5+8+4+3} = \frac{10 + 32 + 24 + 24}{20} = \frac{90}{20} = 4{,}5 $$

### Nível 3 — Desafio

**5.** A média de 5 números é 12. Se adicionarmos um 6º número, a média dos 6 números passa a ser 11. Qual é o 6º número?

$$ \text{Soma dos 5 primeiros} = 5 \times 12 = 60 $$
$$ \text{Soma dos 6 números} = 6 \times 11 = 66 $$
$$ \text{6º número} = 66 - 60 = 6 $$

**6.** Em uma empresa, 10 funcionários ganham R$ 2.000, 5 ganham R$ 4.000, 3 ganham R$ 8.000 e 1 ganha R$ 50.000. Calcule a média e a mediana. Qual é mais representativa?

**Média:**
$$ \bar{x} = \frac{10(2.000) + 5(4.000) + 3(8.000) + 1(50.000)}{19} = \frac{20.000 + 20.000 + 24.000 + 50.000}{19} = \frac{114.000}{19} = 6.000 $$

**Mediana:**
Ordenando: 2.000 (10x), 4.000 (5x), 8.000 (3x), 50.000 (1x)
19 valores → 10º valor é a mediana → **R$ 2.000**

> **Conclusão:** A mediana (R$ 2.000) representa melhor a maioria dos funcionários. A média (R$ 6.000) foi distorcida pelo salário de R$ 50.000.

---
**Próximo:** [Probabilidade](Probabilidade.md)
