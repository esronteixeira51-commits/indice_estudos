# Organização de Dados

A **organização de dados** é o processo de arranjar, classificar e estruturar as informações coletadas para facilitar a análise e a compreensão. Dados brutos (raw data) são difíceis de interpretar; organizados, revelam padrões e tendências.

## Definição

Organização de dados é o processo de **ordenar, classificar, agrupar e apresentar** dados de forma sistemática para análise estatística.

## Rol (Lista Ordenada)

O primeiro passo na organização é colocar os dados em **ordem crescente** (ou decrescente). Essa lista ordenada chama-se **rol**.

### Exemplo

Dados brutos (notas de 20 alunos):

$$ 5, 8, 7, 6, 9, 5, 7, 8, 6, 9, 7, 5, 8, 6, 7, 9, 8, 6, 7, 8 $$

Rol (ordem crescente):

$$ 5, 5, 5, 6, 6, 6, 6, 7, 7, 7, 7, 7, 8, 8, 8, 8, 8, 9, 9, 9 $$

## Frequência

A **frequência** indica quantas vezes cada valor (ou categoria) aparece nos dados.

### Frequência Absoluta ($f_i$)
Número de vezes que o valor aparece.

| Nota ($x_i$) | Frequência ($f_i$) |
|--------------|-------------------|
| 5 | 3 |
| 6 | 4 |
| 7 | 5 |
| 8 | 5 |
| 9 | 3 |
| **Total** | **20** |

### Frequência Relativa ($fr_i$)
Proporção do valor em relação ao total (em decimal ou porcentagem).

$$ fr_i = \frac{f_i}{n} $$

| Nota ($x_i$) | $f_i$ | $fr_i$ (decimal) | $fr_i$ (%) |
|--------------|-------|------------------|------------|
| 5 | 3 | 0,15 | 15% |
| 6 | 4 | 0,20 | 20% |
| 7 | 5 | 0,25 | 25% |
| 8 | 5 | 0,25 | 25% |
| 9 | 3 | 0,15 | 15% |
| **Total** | **20** | **1,00** | **100%** |

### Frequência Acumulada ($F_i$)
Soma das frequências até aquele valor.

| Nota ($x_i$) | $f_i$ | $F_i$ |
|--------------|-------|-------|
| 5 | 3 | 3 |
| 6 | 4 | 7 (3+4) |
| 7 | 5 | 12 (7+5) |
| 8 | 5 | 17 (12+5) |
| 9 | 3 | 20 (17+3) |

> **Interpretação:** 12 alunos tiraram nota 7 ou menos.

### Frequência Relativa Acumulada ($Fr_i$)

$$ Fr_i = \frac{F_i}{n} $$

| Nota ($x_i$) | $F_i$ | $Fr_i$ |
|--------------|-------|--------|
| 5 | 3 | 0,15 (15%) |
| 6 | 7 | 0,35 (35%) |
| 7 | 12 | 0,60 (60%) |
| 8 | 17 | 0,85 (85%) |
| 9 | 20 | 1,00 (100%) |

> **Interpretação:** 60% dos alunos tiraram nota 7 ou menos.

## Dados Agrupados em Classes (Intervalos)

Quando há muitos valores diferentes, agrupamos em **intervalos** (classes).

### Passos para Agrupar em Classes

1. **Determine o número de classes:** geralmente entre 5 e 20
   - Regra de Sturges: $k = 1 + 3,3 \log n$ (onde $n$ = número de dados)

2. **Calcule a amplitude total:** $AT = \text{valor máximo} - \text{valor mínimo}$

3. **Calcule a amplitude de classe:** $h = \frac{AT}{k}$ (arredonde para cima)

4. **Construa os intervalos:** começando do valor mínimo

### Exemplo

Alturas de 30 alunos (em cm):

$$ 150, 152, 155, 158, 160, 161, 163, 164, 165, 166, $$
$$ 167, 168, 169, 170, 171, 172, 173, 174, 175, 176, $$
$$ 177, 178, 179, 180, 181, 182, 183, 185, 187, 190 $$

**Amplitude total:** $190 - 150 = 40$ cm
**Número de classes (Sturges):** $k = 1 + 3,3 \log(30) \approx 1 + 3,3(1,48) \approx 5,9$ → 6 classes
**Amplitude de classe:** $h = 40/6 \approx 6,7$ → arredondar para 7 ou 8 (use 7)

| Classes (cm) | $f_i$ |
|----------------|-------|
| 150 ⊢ 157 | 3 |
| 157 ⊢ 164 | 5 |
| 164 ⊢ 171 | 7 |
| 171 ⊢ 178 | 8 |
| 178 ⊢ 185 | 5 |
| 185 ⊢ 192 | 2 |
| **Total** | **30** |

> **Notação:** 150 ⊢ 157 significa de 150 (incluído) até 157 (excluído). Alguns usam [150, 157).

## Ponto Médio de Classe ($x_i$)

Para cálculos com dados agrupados, usa-se o ponto médio de cada classe:

$$ x_i = \frac{\text{limite inferior} + \text{limite superior}}{2} $$

| Classes (cm) | $x_i$ | $f_i$ |
|--------------|-------|-------|
| 150 ⊢ 157 | 153,5 | 3 |
| 157 ⊢ 164 | 160,5 | 5 |
| 164 ⊢ 171 | 167,5 | 7 |
| 171 ⊢ 178 | 174,5 | 8 |
| 178 ⊢ 185 | 181,5 | 5 |
| 185 ⊢ 192 | 188,5 | 2 |

## Dados Qualitativos

Para dados categóricos, a organização é mais simples: contar as frequências de cada categoria.

### Exemplo

Cores favoritas de 40 pessoas:

| Cor | $f_i$ | $fr_i$ (%) |
|-----|-------|------------|
| Azul | 12 | 30% |
| Vermelho | 8 | 20% |
| Verde | 6 | 15% |
| Amarelo | 4 | 10% |
| Preto | 10 | 25% |
| **Total** | **40** | **100%** |

## Dicas de Organização

1. **Sempre verifique** se o total das frequências bate com o número de dados
2. **Arredonde com critério** — não exagere nas casas decimais
3. **Classes de mesmo tamanho** facilitam a análise (quando possível)
4. **Evite classes muito amplas** — escondem detalhes
5. **Evite classes muito estreitas** — ficam com frequências muito baixas
6. **Rótulos claros** — sempre indique unidades e o que representa cada coluna

---
**Próximo:** [Tabelas](Tabelas.md)
