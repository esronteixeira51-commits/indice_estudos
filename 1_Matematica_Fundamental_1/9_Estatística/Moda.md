# Moda

A **moda** é a medida de tendência central que indica o valor que aparece com **maior frequência** em um conjunto de dados. É a única medida que pode ser usada com **dados qualitativos** (categorias) e é especialmente útil para identificar o valor mais comum ou típico em uma distribuição.

## Definição

Moda = valor que ocorre com a **maior frequência** em um conjunto de dados.

## Tipos de Moda

| Tipo | Definição | Exemplo |
|------|-----------|---------|
| **Unimodal** | Apenas uma moda | 2, 3, 3, 4, 5 → moda = 3 |
| **Bimodal** | Duas modas (mesma frequência máxima) | 2, 2, 3, 3, 4 → modas = 2 e 3 |
| **Multimodal** | Três ou mais modas | 1, 1, 2, 2, 3, 3 → modas = 1, 2, 3 |
| **Amodal** | Nenhuma moda (todos têm mesma frequência) | 1, 2, 3, 4, 5 → amodal |

## Como Encontrar a Moda

### Passo 1: Conte a frequência de cada valor

### Passo 2: Identifique o valor com maior frequência

### Exemplo 1 — Unimodal

Dados: 2, 3, 3, 4, 5, 5, 5, 6, 7

| Valor | Frequência |
|-------|------------|
| 2 | 1 |
| 3 | 2 |
| 4 | 1 |
| 5 | 3 |
| 6 | 1 |
| 7 | 1 |

**Moda = 5** (aparece 3 vezes — frequência máxima)

### Exemplo 2 — Bimodal

Dados: 1, 2, 2, 3, 3, 4, 5

| Valor | Frequência |
|-------|------------|
| 1 | 1 |
| 2 | 2 |
| 3 | 2 |
| 4 | 1 |
| 5 | 1 |

**Modas = 2 e 3** (ambos aparecem 2 vezes — frequência máxima)

### Exemplo 3 — Amodal

Dados: 10, 20, 30, 40, 50

Cada valor aparece 1 vez. **Amodal** — não há moda.

## Moda com Dados Qualitativos (Categóricos)

A moda é a única medida de tendência central que funciona com dados qualitativos, pois não envolve cálculos matemáticos — apenas contagem de frequências.

### Exemplo

Cores favoritas de 20 pessoas:

| Cor | Frequência |
|-----|------------|
| Azul | 8 |
| Vermelho | 5 |
| Verde | 4 |
| Amarelo | 3 |

**Moda = Azul** (cor mais escolhida)

> Não faz sentido calcular média ou mediana de cores! A moda é perfeita para dados categóricos.

## Moda com Dados Agrupados em Classes (Intervalos)

Quando os dados estão agrupados em classes, identificamos a **classe modal** — a classe com a maior frequência.

### Exemplo

| Altura (cm) | Frequência |
|-------------|------------|
| 150 ⊢ 160 | 5 |
| 160 ⊢ 170 | 12 |
| 170 ⊢ 180 | 20 |
| 180 ⊢ 190 | 8 |
| 190 ⊢ 200 | 3 |

**Classe modal = 170 ⊢ 180** (frequência 20, a maior)

> Podemos estimar a moda dentro da classe modal usando fórmulas de interpolação, mas no ensino fundamental basta identificar a classe modal.

## Moda, Média e Mediana: Quando Usar Cada?

| Situação | Melhor Medida | Por quê? |
|----------|-------------|----------|
| Dados numéricos simétricos | Média | Usa todos os dados |
| Dados numéricos com outliers | Mediana | Resistente a extremos |
| Dados categóricos (cores, gênero, marca) | Moda | Única medida possível |
| Identificar o mais popular, mais vendido | Moda | Mostra o mais frequente |
| Distribuição com pico claro | Moda | Identifica o valor típico |
| Decisão de estoque (qual produto comprar mais) | Moda | Mostra o mais demandado |

## Propriedades da Moda

1. **Pode ser usada com dados qualitativos** — diferente da média e mediana
2. **Não usa todos os dados** — apenas o valor mais frequente
3. **Resistente a outliers** — valores extremos não a afetam (se não forem a moda)
4. **Pode não existir** (amodal) ou ter múltiplos valores (bimodal, multimodal)
5. **Não é única** — pode haver várias modas
6. **Não é afetada por valores extremos** — a menos que o valor extremo se torne a moda

## Moda na Vida Real

### Comércio e Vendas
- **Produto mais vendido:** qual tamanho de camiseta comprar mais? Moda = M
- **Sabor de pizza mais pedido:** moda = Calabresa
- **Cor mais popular:** moda = Azul
- **Tamanho de calçado mais vendido:** moda = 42

### Educação
- **Nota mais frequente:** em uma turma, qual nota apareceu mais?
- **Matéria mais escolhida como favorita:** moda = Matemática

### Saúde
- **Sintoma mais comum:** moda = Febre
- **Faixa etária mais atendida:** moda = 30-40 anos

### Estatísticas Oficiais
- **Transporte mais usado:** moda = Ônibus
- **Escolaridade mais comum:** moda = Ensino médio completo
- **Bairro com mais reclamações:** moda = Centro

### Pesquisas e Opinião
- **Candidato mais votado:** moda (na intenção de voto)
- **Canal de TV mais assistido:** moda
- **Rede social mais usada:** moda = Instagram (entre jovens)

## Moda em Gráficos

- **Gráfico de barras:** a barra mais alta indica a moda
- **Histograma:** a coluna mais alta é a classe modal
- **Gráfico de pizza:** a fatia maior não é necessariamente a moda (a moda depende dos dados brutos, não das proporções)

## Problemas de Moda

### Nível 1 — Básico

**1.** Encontre a moda: 2, 3, 3, 4, 5, 5, 5, 6

| Valor | Frequência |
|-------|------------|
| 2 | 1 |
| 3 | 2 |
| 4 | 1 |
| 5 | 3 |
| 6 | 1 |

**Resposta:** Moda = **5**.

**2.** Encontre a moda: 7, 8, 9, 10, 11

**Resposta:** Amodal — todos têm frequência 1.

**3.** Encontre a moda: 1, 2, 2, 3, 3, 4

| Valor | Frequência |
|-------|------------|
| 1 | 1 |
| 2 | 2 |
| 3 | 2 |
| 4 | 1 |

**Resposta:** Bimodal — modas = **2 e 3**.

### Nível 2 — Intermediário

**4.** Em uma pesquisa de cor favorita, 40 pessoas responderam: Azul (12), Vermelho (8), Verde (10), Amarelo (6), Preto (4). Qual a moda?

**Resposta:** Moda = **Azul** (12 votos, maior frequência).

**5.** As notas de uma turma de 30 alunos foram:

| Nota | Alunos |
|------|--------|
| 4 | 2 |
| 5 | 5 |
| 6 | 8 |
| 7 | 10 |
| 8 | 4 |
| 9 | 1 |

Qual a moda?

**Resposta:** Moda = **7** (10 alunos, maior frequência).

**6.** Os pesos (em kg) de 10 pessoas são: 55, 60, 58, 60, 62, 65, 58, 60, 70, 72. Encontre a moda.

| Peso | Frequência |
|------|------------|
| 55 | 1 |
| 58 | 2 |
| 60 | 3 |
| 62 | 1 |
| 65 | 1 |
| 70 | 1 |
| 72 | 1 |

**Resposta:** Moda = **60 kg**.

### Nível 3 — Desafio

**7.** Em uma fábrica, os funcionários têm as seguintes idades: 25, 28, 30, 30, 32, 35, 35, 35, 38, 40, 42, 45, 50, 55, 60. Calcule a média, mediana e moda. Qual medida é mais representativa para descrever a "idade típica" dos funcionários?

*Resolução:*

Ordem: 25, 28, 30, 30, 32, 35, 35, 35, 38, 40, 42, 45, 50, 55, 60

$$ n = 15 $$

$$ \text{Média} = \frac{25+28+30+30+32+35+35+35+38+40+42+45+50+55+60}{15} = \frac{570}{15} = 38 $$

$$ \text{Mediana (posição 8)} = 35 $$

$$ \text{Moda} = 35 \text{ (aparece 3 vezes)} $$

**Resposta:** Média = 38, Mediana = 35, Moda = 35. A mediana e a moda (35) são mais representativas, pois a média (38) é puxada para cima pelos funcionários mais velhos (55, 60).

**8.** Uma loja vende camisetas nos tamanhos P, M, G, GG. As vendas do mês foram: P (15), M (45), G (30), GG (10). Qual o tamanho modal? Se a loja for comprar 100 camisetas para o próximo mês, quantas de cada tamanho deveria comprar, aproximadamente, seguindo a proporção das vendas?

$$ \text{Total vendido} = 15 + 45 + 30 + 10 = 100 $$

$$ \text{Moda} = \text{M} \text{ (45 vendas)} $$

Proporções para 100 camisetas:
- P: $\frac{15}{100} \times 100 = 15$
- M: $\frac{45}{100} \times 100 = 45$
- G: $\frac{30}{100} \times 100 = 30$
- GG: $\frac{10}{100} \times 100 = 10$

**Resposta:** Moda = M. Deveria comprar 15 P, 45 M, 30 G, 10 GG.

---
**Fim — Moda**
