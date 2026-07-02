# Poliedros e Classificação

Um **poliedro** é um sólido geométrico limitado por polígonos planos, chamados **faces**. Os segmentos comuns a duas faces são as **arestas**, e os pontos onde convergem três ou mais arestas são os **vértices**.

## Elementos de um Poliedro

| Elemento | Definição | Notação |
|----------|-----------|---------|
| **Faces** | Polígonos que limitam o poliedro | $F$ |
| **Arestas** | Segmentos de interseção entre duas faces | $A$ |
| **Vértices** | Pontos de interseção de três ou mais arestas | $V$ |

## Fórmula de Euler (Poliedros Convexos)

Para todo poliedro convexo, vale a relação:

$$ V - A + F = 2 $$

**Demonstração:**
A fórmula de Euler pode ser demonstrada por indução ou por "achatamento" (flattening) do poliedro. Considere um poliedro convexo com $V$ vértices, $A$ arestas e $F$ faces. Se removermos uma face e "esticarmos" o restante num plano, obtemos um grafo planar. Para árvores (grafos sem ciclos), $V = A + 1$. Adicionando faces, cada nova face adiciona uma aresta a mais que vértices, mantendo $V - A + F = 2$.

> **Importante:** A fórmula de Euler vale apenas para poliedros **convexos** (ou topologicamente equivalentes a uma esfera).

## Poliedros Regulares (Platônicos)

São poliedros convexos cujas faces são polígonos regulares congruentes e em que o mesmo número de arestas se encontra em cada vértice.

### Os 5 Poliedros Regulares

| Nome | Faces | Forma das Faces | Vértices | Arestas | Faces | Característica |
|------|-------|-----------------|----------|---------|-------|----------------|
| **Tetraedro** | 4 | Triângulos equiláteros | 4 | 6 | 4 | Menor poliedro regular |
| **Hexaedro (Cubo)** | 6 | Quadrados | 8 | 12 | 6 | Mais familiar |
| **Octaedro** | 8 | Triângulos equiláteros | 6 | 12 | 8 | Dual do cubo |
| **Dodecaedro** | 12 | Pentágonos regulares | 20 | 30 | 12 | 12 faces pentagonais |
| **Icasaedro** | 20 | Triângulos equiláteros | 12 | 30 | 20 | 20 faces triangulares |

### Verificação de Euler

| Poliedro | V | A | F | V - A + F |
|----------|---|---|---|-----------|
| Tetraedro | 4 | 6 | 4 | 4 - 6 + 4 = **2** ✓ |
| Cubo | 8 | 12 | 6 | 8 - 12 + 6 = **2** ✓ |
| Octaedro | 6 | 12 | 8 | 6 - 12 + 8 = **2** ✓ |
| Dodecaedro | 20 | 30 | 12 | 20 - 30 + 12 = **2** ✓ |
| Icosaedro | 12 | 30 | 20 | 12 - 30 + 20 = **2** ✓ |

## Poliedros de Platão — Propriedades Específicas

### Tetraedro Regular

- 4 faces triangulares, 4 vértices, 6 arestas
- Ângulo diedro (entre faces): $\arccos(1/3) \approx 70{,}53°$
- Altura: $h = a\frac{\sqrt{6}}{3}$
- Área total: $A = a^2\sqrt{3}$
- Volume: $V = \frac{a^3\sqrt{2}}{12}$

### Cubo

- 6 faces quadradas, 8 vértices, 12 arestas
- Ângulo diedro: $90°$
- Diagonal da face: $a\sqrt{2}$
- Diagonal do cubo: $a\sqrt{3}$
- Área total: $A = 6a^2$
- Volume: $V = a^3$

### Octaedro Regular

- 8 faces triangulares, 6 vértices, 12 arestas
- Pode ser visto como duas pirâmides quadradas unidas pela base
- Área total: $A = 2a^2\sqrt{3}$
- Volume: $V = \frac{a^3\sqrt{2}}{3}$

### Dodecaedro Regular

- 12 faces pentagonais, 20 vértices, 30 arestas
- Área total: $A = 3a^2\sqrt{25 + 10\sqrt{5}}$
- Volume: $V = \frac{a^3(15 + 7\sqrt{5})}{4}$

### Icosaedro Regular

- 20 faces triangulares, 12 vértices, 30 arestas
- Área total: $A = 5a^2\sqrt{3}$
- Volume: $V = \frac{5a^3(3 + \sqrt{5})}{12}$

## Poliedros em Geral (Não Regulares)

### Prismas

Poliedros com duas bases congruentes e paralelas, e faces laterais retangulares (se reto) ou paralologramos (se oblíquo).

**Área total:** $A = 2A_{base} + A_{lateral}$
**Volume:** $V = A_{base} \cdot h$

### Pirâmides

Poliedros com uma base poligonal e faces laterais triangulares que convergem para um vértice (ápice).

**Área total:** $A = A_{base} + A_{lateral}$
**Volume:** $V = \frac{1}{3} A_{base} \cdot h$

## Exemplos

### Exemplo 1: Fórmula de Euler

Um poliedro convexo tem 12 arestas e 6 faces. Quantos vértices tem?

$$ V - A + F = 2 $$
$$ V - 12 + 6 = 2 $$
$$ V = 2 + 12 - 6 = 8 $$

**Resposta:** 8 vértices. Trata-se de um cubo!

### Exemplo 2: Verificação de Euler

Um poliedro tem 10 vértices e 15 arestas. Quantas faces deve ter para ser convexo?

$$ 10 - 15 + F = 2 \implies F = 7 $$

**Resposta:** 7 faces.

### Exemplo 3: Tetraedro

Um tetraedro regular tem aresta 6 cm. Determine sua área total e volume.

$$ A = 6^2 \sqrt{3} = 36\sqrt{3} \approx 62{,}35 \text{ cm}^2 $$
$$ V = \frac{6^3 \sqrt{2}}{12} = \frac{216\sqrt{2}}{12} = 18\sqrt{2} \approx 25{,}46 \text{ cm}^3 $$

**Resposta:** Área total = $36\sqrt{3}$ cm$^2$; Volume = $18\sqrt{2}$ cm$^3$.

### Exemplo 4: Cubo

Um cubo tem diagonal igual a $5\sqrt{3}$ cm. Determine sua aresta, área total e volume.

$$ a\sqrt{3} = 5\sqrt{3} \implies a = 5 \text{ cm} $$
$$ A = 6 \cdot 5^2 = 150 \text{ cm}^2 $$
$$ V = 5^3 = 125 \text{ cm}^3 $$

**Resposta:** Aresta = 5 cm; Área = 150 cm$^2$; Volume = 125 cm$^3$.

## Aplicações na Vida Real

- **Arquitetura:** construções geodésicas, cúpulas, estruturas poliedrais
- **Cristalografia:** cristais formam poliedros (cubos de sal, octaedros de diamante)
- **Jogos:** dados (dodecaedro, icosaedro), peças de jogos, puzzles (cubos mágicos)
- **Matemática:** teoria dos grafos, topologia, dualidade poliedral
- **Química:** moléculas (metano = tetraedro, fullereno = icosaedro truncado)
- **Biologia:** células de abelha (hexagonais), radiolários (esqueletos poliedrais)
- **Design:** joias, esculturas, objetos decorativos poliedrais
- **Engenharia:** estruturas espaciais, painéis solares, antenas
- **Arte:** obras de Escher, M.C. Escher explorou poliedros em suas gravuras
- **Computação:** malhas 3D, polígonos em modelagem, poliedros em física de jogos

## Problemas

### Nível 1 — Básico

**1.** Um poliedro convexo tem 8 vértices e 12 arestas. Quantas faces tem?

$$ 8 - 12 + F = 2 \implies F = 6 $$

**Resposta:** 6 faces.

**2.** Um poliedro tem 6 faces e 12 arestas. Quantos vértices tem?

$$ V - 12 + 6 = 2 \implies V = 8 $$

**Resposta:** 8 vértices.

**3.** Um cubo tem aresta 4 cm. Determine sua área total e volume.

$$ A = 6 \cdot 4^2 = 96 \text{ cm}^2 $$
$$ V = 4^3 = 64 \text{ cm}^3 $$

**Resposta:** Área = 96 cm$^2$; Volume = 64 cm$^3$.

**4.** Um tetraedro regular tem aresta 3 cm. Determine sua área total.

$$ A = 3^2 \sqrt{3} = 9\sqrt{3} \approx 15{,}59 \text{ cm}^2 $$

**Resposta:** $9\sqrt{3}$ cm$^2$ $\approx 15{,}59$ cm$^2$.

**5.** Verifique a fórmula de Euler para um octaedro regular (6 vértices, 12 arestas, 8 faces).

$$ V - A + F = 6 - 12 + 8 = 2 $$

**Resposta:** $6 - 12 + 8 = 2$ ✓

### Nível 2 — Intermediário

**6.** Um poliedro convexo tem todas as faces triangulares. Se tem 4 vértices, determine o número de faces e arestas.

Como cada face é um triângulo, cada face tem 3 arestas. Mas cada aresta pertence a 2 faces.
$$ 3F = 2A \implies A = \frac{3F}{2} $$

Por Euler: $4 - A + F = 2 \implies A = F + 2$

$$ \frac{3F}{2} = F + 2 \implies 3F = 2F + 4 \implies F = 4 $$
$$ A = 6 $$

**Resposta:** 4 faces, 6 arestas (é um tetraedro).

**7.** Um cubo tem diagonal $10\sqrt{3}$ m. Determine sua aresta, área total e volume.

$$ a\sqrt{3} = 10\sqrt{3} \implies a = 10 \text{ m} $$
$$ A = 6 \cdot 100 = 600 \text{ m}^2 $$
$$ V = 1000 \text{ m}^3 $$

**Resposta:** Aresta = 10 m; Área = 600 m$^2$; Volume = 1000 m$^3$.

**8.** Um octaedro regular tem aresta 4 cm. Determine sua área total e volume.

$$ A = 2 \cdot 4^2 \sqrt{3} = 32\sqrt{3} \approx 55{,}43 \text{ cm}^2 $$
$$ V = \frac{4^3 \sqrt{2}}{3} = \frac{64\sqrt{2}}{3} \approx 30{,}17 \text{ cm}^3 $$

**Resposta:** Área = $32\sqrt{3}$ cm$^2$; Volume = $\frac{64\sqrt{2}}{3}$ cm$^3$.

**9.** Um poliedro convexo tem 20 vértices e 30 arestas. Determine o número de faces e identifique o poliedro regular correspondente.

$$ 20 - 30 + F = 2 \implies F = 12 $$

Poliedro com 20 vértices, 30 arestas, 12 faces: **dodecaedro**.

**Resposta:** 12 faces; é um dodecaedro regular.

**10.** A soma dos ângulos de todas as faces de um poliedro convexo é $720°$. Se cada face é um triângulo, quantas faces tem o poliedro?

Soma dos ângulos de um triângulo = $180°$.
$$ \text{Número de faces} = \frac{720°}{180°} = 4 $$

**Resposta:** 4 faces (tetraedro).

### Nível 3 — Desafio

**11.** Prove que não existe poliedro regular com faces hexagonais regulares. (Dica: cada vértice de um poliedro regular deve ter pelo menos 3 faces e a soma dos ângulos em cada vértice deve ser menor que $360°$.)

Ângulo interno do hexágono regular = $120°$.

Se 3 hexágonos se encontram em um vértice: $3 \cdot 120° = 360°$ (aplainamento, não forma poliedro).
Se mais de 3: soma $> 360°$ (impossível para poliedro convexo).
Se menos de 3: apenas 2 faces se encontram (não forma vértice).

Portanto, não é possível formar um poliedro regular com faces hexagonais.

**Resposta:** Demonstrado: a soma dos ângulos em cada vértice seria $\geq 360°$, impossibilitando a formação de um poliedro convexo.

**12.** Um poliedro convexo tem 12 faces, sendo 8 triângulos e 4 hexágonos. Determine o número de vértices e arestas.

Contando arestas por faces:
$$ 8 \cdot 3 + 4 \cdot 6 = 24 + 24 = 48 $$

Como cada aresta pertence a 2 faces:
$$ 2A = 48 \implies A = 24 $$

Por Euler:
$$ V - 24 + 12 = 2 \implies V = 14 $$

**Resposta:** 14 vértices, 24 arestas.

**13.** (Cubo e octaedro) Um cubo e um octaedro regular são "poliedros duais" (dualidade): os vértices de um correspondem às faces do outro. Se um cubo tem aresta $a$, determine a aresta do octaedro dual inscrito no cubo (com vértices nos centros das faces do cubo).

Centros das faces de um cubo de aresta $a$:
- As faces estão a distância $a/2$ do centro em cada direção.
- Centros de faces adjacentes distam: $\sqrt{(a/2)^2 + (a/2)^2} = \sqrt{a^2/4 + a^2/4} = \sqrt{a^2/2} = a/\sqrt{2} = a\frac{\sqrt{2}}{2}$

**Resposta:** A aresta do octaedro dual é $a\frac{\sqrt{2}}{2}$.

---
**Fim — Poliedros e Classificação**
