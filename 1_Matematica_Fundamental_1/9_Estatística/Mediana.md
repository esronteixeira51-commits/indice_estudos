# Mediana

A **mediana** é uma medida de tendência central que representa o valor que divide um conjunto de dados ordenados ao meio: metade dos dados está abaixo dela e metade acima. Diferente da média, a mediana é **resistente a valores extremos** (outliers), o que a torna mais confiável em dados assimétricos.

## Definição

Mediana = valor que ocupa a **posição central** dos dados ordenados.

- 50% dos dados são **menores ou iguais** à mediana
- 50% dos dados são **maiores ou iguais** à mediana

## Cálculo da Mediana

### Passo 1: Ordene os dados
Coloque os valores em ordem crescente (ou decrescente).

### Passo 2: Encontre a posição central

- Se $n$ (quantidade de dados) é **ímpar**: mediana é o valor exato do meio.
  $$ \text{Posição} = \frac{n+1}{2} $$

- Se $n$ é **par**: mediana é a média aritmética dos dois valores centrais.
  $$ \text{Posição} = \frac{n}{2} \text{ e } \frac{n}{2} + 1 $$

### Exemplo 1 — $n$ ímpar

Dados: 3, 7, 1, 9, 5

Ordem: 1, 3, 5, 7, 9

$$ n = 5 \Rightarrow \text{Posição} = \frac{5+1}{2} = 3 $$

Mediana = **5** (o 3º valor)

### Exemplo 2 — $n$ par

Dados: 4, 8, 2, 10, 6, 12

Ordem: 2, 4, 6, 8, 10, 12

$$ n = 6 \Rightarrow \text{Posições centrais: 3º e 4º} $$

$$ \text{Mediana} = \frac{6 + 8}{2} = 7 $$

## Mediana com Dados Agrupados (Tabela de Frequência)

Quando os dados estão em uma tabela de frequência, primeiro construímos a **frequência acumulada** para encontrar a posição mediana.

### Exemplo

| Valor ($x_i$) | Frequência ($f_i$) | Frequência Acumulada ($F_i$) |
|---------------|----------------------|------------------------------|
| 2 | 3 | 3 |
| 4 | 5 | 8 |
| 6 | 7 | 15 |
| 8 | 4 | 19 |
| 10 | 1 | 20 |

$$ n = 20 \Rightarrow \text{Posição mediana} = \frac{20}{2} = 10 \text{ e } 11 $$

- Até o valor 4: $F_i = 8$ (ainda não chegamos)
- Até o valor 6: $F_i = 15$ (passamos!)

$$ \text{Mediana} = 6 $$

## Mediana com Dados em Classes (Intervalos)

Para dados contínuos agrupados em classes, usamos a **fórmula de interpolação linear**:

$$ Md = L_i + \left( \frac{\frac{n}{2} - F_{ant}}{f_{Md}} \right) \times h $$

Onde:
- $L_i$ = limite inferior da classe mediana
- $n$ = total de dados
- $F_{ant}$ = frequência acumulada anterior à classe mediana
- $f_{Md}$ = frequência da classe mediana
- $h$ = amplitude da classe

### Exemplo

| Classes (cm) | $f_i$ | $F_i$ |
|--------------|-------|-------|
| 150 ⊢ 160 | 5 | 5 |
| 160 ⊢ 170 | 8 | 13 |
| 170 ⊢ 180 | 12 | 25 |
| 180 ⊢ 190 | 7 | 32 |
| 190 ⊢ 200 | 3 | 35 |

$$ n = 35 \Rightarrow \text{Posição mediana} = \frac{35+1}{2} = 18 $$

A classe mediana é **170 ⊢ 180** (pois $F_{ant} = 13 < 18 \leq 25 = F_i$)

$$ L_i = 170, \quad F_{ant} = 13, \quad f_{Md} = 12, \quad h = 10 $$

$$ Md = 170 + \left( \frac{17{,}5 - 13}{12} \right) \times 10 = 170 + \frac{4{,}5}{12} \times 10 = 170 + 3{,}75 = 173{,}75 \text{ cm} $$

> **Nota:** Para $n$ ímpar, usamos $\frac{n+1}{2}$. Para $n$ par, $\frac{n}{2}$ e $\frac{n}{2}+1$.

## Mediana vs. Média: Quando Usar Cada?

| Situação | Melhor Medida | Por quê? |
|----------|-------------|----------|
| Dados simétricos, sem outliers | Média | Usa todos os dados, mais precisa |
| Dados assimétricos (cauda longa) | Mediana | Não é afetada por valores extremos |
| Salários, rendas, preços de imóveis | Mediana | Alguns valores muito altos distorcem a média |
| Notas de classe com aluno nota 0 | Mediana | O zero "puxa" a média para baixo |
| Temperaturas diárias | Média | Valores simétricos, sem outliers |

### Exemplo Clássico: Salários

Salários de 5 pessoas: R$ 2.000, R$ 2.500, R$ 3.000, R$ 3.500, R$ 50.000

- **Média:** $\frac{61.000}{5} = 12.200$ (R$ 12.200 — não representa ninguém!)
- **Mediana:** 3.000 (R$ 3.000 — representa o "típico"!)

> **Conclusão:** A média foi distorcida pelo salário de R$ 50.000. A mediana é mais representativa.

## Propriedades da Mediana

1. **Não usa todos os dados** — apenas os valores centrais
2. **Resistente a outliers** — valores extremos não a afetam
3. **Sempre existe** (diferente da moda, que pode não existir)
4. **Única** — há apenas uma mediana
5. **Pode ser usada com dados ordinais** — dados que têm ordem, mas não intervalos fixos

## Mediana na Vida Real

- **Economia:** mediana salarial (IBGE), mediana de preços de imóveis
- **Saúde:** mediana de idade de diagnóstico, mediana de tempo de internação
- **Educação:** mediana de notas (menos sensível a notas 0 de faltantes)
- **Esportes:** mediana de pontuação (elimina performances extremas)
- **Mercado:** mediana de preços de produtos (um item caro não distorce)
- **Meteorologia:** mediana de temperatura (dias muito quentes ou frios não afetam)
- **Política:** renda mediana da população (indicador oficial do IBGE)

## Problemas de Mediana

### Nível 1 — Básico

**1.** Encontre a mediana: 2, 5, 8, 12, 15

Ordem: 2, 5, 8, 12, 15
$$ n = 5 \Rightarrow \text{Posição} = 3 $$

**Resposta:** Mediana = **8**.

**2.** Encontre a mediana: 10, 4, 8, 2, 6

Ordem: 2, 4, 6, 8, 10
$$ n = 5 \Rightarrow \text{Posição} = 3 $$

**Resposta:** Mediana = **6**.

**3.** Encontre a mediana: 3, 7, 1, 9, 5, 11

Ordem: 1, 3, 5, 7, 9, 11
$$ n = 6 \Rightarrow \text{Posições: 3º e 4º} $$
$$ \text{Mediana} = \frac{5 + 7}{2} = 6 $$

**Resposta:** Mediana = **6**.

### Nível 2 — Intermediário

**4.** As idades de 7 alunos são: 12, 13, 11, 14, 12, 15, 13. Qual a mediana?

Ordem: 11, 12, 12, 13, 13, 14, 15
$$ n = 7 \Rightarrow \text{Posição} = 4 $$

**Resposta:** Mediana = **13**.

**5.** Os pesos de 8 pessoas são: 55, 60, 58, 62, 70, 65, 58, 72 kg. Qual a mediana?

Ordem: 55, 58, 58, 60, 62, 65, 70, 72
$$ n = 8 \Rightarrow \text{Posições: 4º e 5º} $$
$$ \text{Mediana} = \frac{60 + 62}{2} = 61 \text{ kg} $$

**Resposta:** Mediana = **61 kg**.

**6.** Dada a tabela:

| Nota | $f_i$ |
|------|-------|
| 4 | 3 |
| 5 | 5 |
| 6 | 8 |
| 7 | 4 |

Qual a mediana?

$$ n = 20 \Rightarrow \text{Posições: 10º e 11º} $$

Frequências acumuladas: 4→3, 5→8, 6→16, 7→20
- 10º e 11º valores estão na classe da nota 6.

**Resposta:** Mediana = **6**.

### Nível 3 — Desafio

**7.** Em uma empresa, 9 funcionários ganham: R$ 1.800, R$ 2.000, R$ 2.100, R$ 2.200, R$ 2.300, R$ 2.400, R$ 2.500, R$ 3.000, R$ 15.000. Qual a média e qual a mediana? Qual é mais representativa?

Ordem: 1.800, 2.000, 2.100, 2.200, 2.300, 2.400, 2.500, 3.000, 15.000

$$ \text{Média} = \frac{1.800 + 2.000 + 2.100 + 2.200 + 2.300 + 2.400 + 2.500 + 3.000 + 15.000}{9} = \frac{33.300}{9} = 3.700 $$

$$ n = 9 \Rightarrow \text{Posição} = 5 $$
$$ \text{Mediana} = 2.300 $$

**Resposta:** Média = R$ 3.700, Mediana = R$ 2.300. A mediana é mais representativa porque o salário de R$ 15.000 distorce a média.

**8.** Se a mediana de 5 números é 8 e os quatro primeiros são 3, 5, 7, 9, qual é o quinto número, sabendo que a média é 7,6?

$$ \text{Mediana} = 8 \Rightarrow \text{o 3º número é 8} $$

Mas os dados ordenados são: 3, 5, 7, 9, ?

Para a mediana ser 8, o 3º valor deve ser 8. Então 7 e 9 precisam ser rearranjados, ou o 5º valor é tal que o ordenamento mude.

Se o 5º valor é $x$:
- Se $x \geq 9$: ordenado é 3, 5, 7, 9, x → mediana = 7 ❌
- Se $7 \leq x < 9$: ordenado é 3, 5, 7, x, 9 → mediana = 7 ❌
- Se $5 \leq x < 7$: ordenado é 3, 5, x, 7, 9 → mediana = x = 8 ❌ (8 não está entre 5 e 7)
- Se $3 \leq x < 5$: ordenado é 3, x, 5, 7, 9 → mediana = 5 ❌
- Se $x < 3$: ordenado é x, 3, 5, 7, 9 → mediana = 5 ❌

Espera, há um erro na interpretação. Se os 4 primeiros dados são 3, 5, 7, 9 (não necessariamente ordenados), e precisamos de 5 valores com mediana 8...

Se ordenamos: para mediana 8 com 5 valores, o 3º valor deve ser 8. Temos 3, 5, 7, 9. Precisamos de 8 como o 3º valor. Então o 5º valor deve ser ≤ 5 para que 8 seja o 3º? Não, não temos 8 nos dados...

Releitura: os 4 primeiros são 3, 5, 7, 9. O 5º valor deve ser tal que, ao ordenar, o 3º seja 8.

Para o 3º valor ser 8, precisamos que 8 esteja nos dados. Então o 5º valor é 8, e ao ordenar: 3, 5, 7, 8, 9 → mediana = 7 ❌

Ou o 5º valor é > 9 e 8 também deve estar... mas não está.

Reinterpretação: os valores dados são os 4 primeiros **na ordem da coleta**, não ordenados. E o 5º valor é desconhecido. Se ordenarmos todos os 5, a mediana deve ser 8.

Se o 5º valor é $x$ e $x = 8$: ordenado 3, 5, 7, 8, 9 → mediana = 7 ❌

Se $x$ é tal que o 3º ordenado seja 8, então dois valores devem ser ≤ 8 e dois devem ser ≥ 8. Temos 3, 5, 7 (3 valores < 8), 9 (> 8). Para o 3º ser 8, precisamos que o 5º valor seja ≥ 8 e um dos 3, 5, 7 seja 8... mas nenhum é 8.

Hmm, o problema tem inconsistência se os 4 valores são fixos como 3, 5, 7, 9. Vou ajustar o problema para que faça sentido.

Vamos refazer: Se a mediana de 5 números é 10 e os valores são 4, 8, 10, 12, x, determine x sabendo que a média é 9.

$$ \text{Média} = \frac{4 + 8 + 10 + 12 + x}{5} = 9 $$
$$ 34 + x = 45 \Rightarrow x = 11 $$

Ordem: 4, 8, 10, 11, 12 → mediana = 10 ✓

Vou usar este problema no arquivo.

---
**Fim — Mediana**
