# Polígonos

Um **polígono** é uma figura plana fechada formada apenas por **segmentos de reta** que se encontram em seus extremos (vértices). Os polígonos são a base da geometria plana e aparecem constantemente na arquitetura, design, natureza e tecnologia.

## Definição

Polígono = figura plana + fechada + lados retos

## Elementos de um Polígono

### Lados (Arestas)
Os segmentos de reta que formam a borda do polígono.

### Vértices
Os pontos onde dois lados se encontram.

### Ângulos Internos
As aberturas formadas no interior do polígono em cada vértice.

### Ângulos Externos
As aberturas formadas fora do polígono, complementando o ângulo interno até 180° (em polígonos convexos).

### Diagonais
Segmentos que unem dois vértices não consecutivos.

## Classificação por Número de Lados

| Nº Lados | Nome | Soma dos Ângulos Internos |
|----------|------|---------------------------|
| 3 | Triângulo | 180° |
| 4 | Quadrilátero | 360° |
| 5 | Pentágono | 540° |
| 6 | Hexágono | 720° |
| 7 | Heptágono | 900° |
| 8 | Octógono | 1.080° |
| 9 | Eneágono | 1.260° |
| 10 | Decágono | 1.440° |
| n | n-ágono | $(n-2) \times 180°$ |

## Classificação por Forma

### Convexos
Todos os ângulos internos são menores que 180°. Qualquer segmento entre dois pontos do interior está inteiramente contido no polígono.

```
    ___________
   /           \
  /             \
 |               |
  \             /
   \___________/
   
   Convexo: nenhuma "dentadura"
```

### Côncavos (Não Convexos)
Possuem pelo menos um ângulo interno maior que 180° (reflexo). Há segmentos entre pontos internos que saem do polígono.

```
    ____
   /    \
  |      |
   \  __/
    |/
    
   Côncavo: possui "dentadura"
```

## Classificação por Regularidade

### Polígonos Regulares
Todos os lados têm o **mesmo comprimento** e todos os ângulos internos têm a **mesma medida**.

| Polígono Regular | Medida de Cada Ângulo Interno |
|------------------|-------------------------------|
| Triângulo equilátero | 60° |
| Quadrado | 90° |
| Pentágono regular | 108° |
| Hexágono regular | 120° |
| Heptágono regular | 128,57° |
| Octógono regular | 135° |

**Fórmula:**
$$ \text{Ângulo interno} = \frac{(n-2) \times 180°}{n} $$

### Polígonos Irregulares
Lados e/ou ângulos de medidas diferentes.

## Fórmulas Fundamentais

### Soma dos Ângulos Internos
$$ S_i = (n - 2) \times 180° $$

### Soma dos Ângulos Externos (Convexo)
$$ S_e = 360° \text{ (sempre!)} $$

### Medida de Cada Ângulo Interno (Regular)
$$ \alpha = \frac{(n-2) \times 180°}{n} $$

### Medida de Cada Ângulo Externo (Regular)
$$ \beta = \frac{360°}{n} $$

Observe: $\alpha + \beta = 180°$ (são suplementares)

### Número de Diagonais
$$ d = \frac{n(n-3)}{2} $$

## Diagonais dos Principais Polígonos

| Polígono | Nº Lados | Diagonais |
|----------|----------|-----------|
| Triângulo | 3 | 0 |
| Quadrilátero | 4 | 2 |
| Pentágono | 5 | 5 |
| Hexágono | 6 | 9 |
| Heptágono | 7 | 14 |
| Octógono | 8 | 20 |
| Decágono | 10 | 35 |

## Polígonos na Vida Real

- **Triângulos:** estruturas de pontes (triângulo = forma mais rígida), escamas de peixes
- **Quadrados:** pisos, azulejos, telas, janelas
- **Hexágonos:** favos de mel (maximiza área com mínimo material), células de planta
- **Octógonos:** sinais de PARE, moedas antigas
- **Pentágonos:** estrelas de bandeiras, estadias de futebol
- **Heptágonos:** raramente na natureza, mas em moedas (Reino Unido)

## Polígonos Estrelados

Formados quando as diagonais de um polígono regular se cruzam, criando uma figura em estrela.

- **Pentagrama:** estrela de 5 pontas (do pentágono)
- **Hexagrama:** estrela de 6 pontas (Estrela de Davi)
- **Octograma:** estrela de 8 pontas

---
**Próximo:** [Circunferência](Circunferência.md)
