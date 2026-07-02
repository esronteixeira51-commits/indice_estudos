# Sequências

Uma **sequência** é uma lista ordenada de números (ou objetos) em que cada elemento ocupa uma posição específica. As sequências são fundamentais na álgebra e aparecem naturalmente em padrões da natureza, música, finanças e ciência.

## Definição

Uma sequência é uma função cujos elementos são indexados por números naturais:

$$ a_1, a_2, a_3, a_4, \ldots, a_n $$

- $a_1$ = primeiro termo
- $a_2$ = segundo termo
- $a_n$ = termo geral (enésimo termo)

## Tipos de Sequências

### Sequência Numérica
Conjunto de números em ordem:

$$ 2, 4, 6, 8, 10, \ldots $$

### Sequência Alfabética

$$ A, B, C, D, E, \ldots $$

### Sequência de Figuras

Triângulos, quadrados, pentágonos... em ordem crescente de lados.

## Sequências Famosas

### Números Naturais
$$ 1, 2, 3, 4, 5, \ldots $$

### Números Pares
$$ 2, 4, 6, 8, 10, \ldots $$
**Fórmula:** $a_n = 2n$

### Números Ímpares
$$ 1, 3, 5, 7, 9, \ldots $$
**Fórmula:** $a_n = 2n - 1$

### Sequência de Quadrados
$$ 1, 4, 9, 16, 25, \ldots $$
**Fórmula:** $a_n = n^2$

### Sequência de Cubos
$$ 1, 8, 27, 64, 125, \ldots $$
**Fórmula:** $a_n = n^3$

### Sequência de Fibonacci
$$ 1, 1, 2, 3, 5, 8, 13, 21, 34, \ldots $$
**Regra:** cada termo é a soma dos dois anteriores: $F_n = F_{n-1} + F_{n-2}$

## Termo Geral (Fórmula da Sequência)

O termo geral permite calcular **qualquer termo** sem conhecer os anteriores.

**Exemplo:** $a_n = 3n + 2$

- $a_1 = 3(1) + 2 = 5$
- $a_2 = 3(2) + 2 = 8$
- $a_5 = 3(5) + 2 = 17$
- $a_{100} = 3(100) + 2 = 302$

## Descobrindo o Padrão

Dada uma sequência, descubra a regra:

$$ 5, 8, 11, 14, 17, \ldots $$

Diferença entre termos: $8-5=3$, $11-8=3$, $14-11=3$ → **diferença constante = 3**

Fórmula: $a_n = 3n + 2$ (pois $a_1 = 5$)

## Sequência Aritmética (PA)

Cada termo é o anterior mais uma **razão constante** $r$:

$$ a_n = a_1 + (n-1) \cdot r $$

**Exemplo:** $5, 9, 13, 17, \ldots$ (razão $r = 4$)

$$ a_n = 5 + (n-1) \cdot 4 = 4n + 1 $$

## Sequência Geométrica (PG)

Cada termo é o anterior multiplicado por uma **razão constante** $q$:

$$ a_n = a_1 \cdot q^{n-1} $$

**Exemplo:** $3, 6, 12, 24, \ldots$ (razão $q = 2$)

$$ a_n = 3 \cdot 2^{n-1} $$

## Sequência Visual

```
Termo 1:  ●         (1 ponto)
Termo 2:  ● ●       (2 pontos)
Termo 3:  ● ● ●     (3 pontos)
Termo 4:  ● ● ● ●   (4 pontos)

Fórmula: a_n = n
```

---
**Próximo:** [Padrões](Padrões.md)
