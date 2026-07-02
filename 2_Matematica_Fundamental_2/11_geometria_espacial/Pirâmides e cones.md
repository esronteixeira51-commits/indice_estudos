# Pirâmides e Cones

**Pirâmides** são poliedros com uma base poligonal e faces laterais triangulares que convergem para um vértice comum (ápice). **Cones** são os análogos não-poliedricos, com base circular e superfície lateral curva que converge para um ponto (vértice).

## Pirâmides

### Elementos

| Elemento | Definição |
|----------|-----------|
| **Base** | Polígono que sustenta a pirâmide |
| **Vértice (ápice)** | Ponto onde convergem as faces laterais |
| **Altura** | Distância perpendicular do ápice ao plano da base |
| **Aresta lateral** | Segmento que une o ápice a um vértice da base |
| **Apótema da base** | Distância do centro ao meio de um lado da base |
| **Apótema da pirâmide** | Altura de uma face lateral (altura do triângulo) |

### Área Lateral

Soma das áreas das faces triangulares:

$$ A_l = \frac{1}{2} \cdot 2p \cdot a_p $$

Onde $2p$ é o perímetro da base e $a_p$ é o apótema da pirâmide (altura das faces laterais).

### Área Total

$$ A_t = A_b + A_l $$

### Volume

$$ V = \frac{1}{3} A_b \cdot h $$

> **Atenção:** O fator $\frac{1}{3}$ é fundamental! Um prisma com a mesma base e altura tem volume 3 vezes maior que a pirâmide.

## Pirâmides Regulares

Pirâmide cuja base é um polígono regular e cujo ápice está alinhado perpendicularmente ao centro da base.

### Relação Fundamental

$$ a_p^2 = h^2 + a_b^2 $$

Onde $a_p$ é o apótema da pirâmide, $h$ é a altura, e $a_b$ é o apótema da base.

### Relação da Aresta Lateral

$$ \ell^2 = h^2 + R^2 $$

Onde $\ell$ é a aresta lateral e $R$ é o raio da circunferência circunscrita à base (distância do centro a um vértice).

## Pirâmides Especiais

### Pirâmide Quadrangular Regular

- Base: quadrado de lado $L$
- Apótema da base: $a_b = L/2$
- Área da base: $A_b = L^2$
- Área lateral: $A_l = 2L \cdot a_p$
- Volume: $V = \frac{L^2 \cdot h}{3}$

### Pirâmide Triangular Regular (Tetraedro Regular)

- Base: triângulo equilátero de lado $a$
- Área da base: $A_b = \frac{a^2\sqrt{3}}{4}$
- Altura: $h = \frac{a\sqrt{6}}{3}$
- Volume: $V = \frac{a^3\sqrt{2}}{12}$

### Pirâmide Hexagonal Regular

- Base: hexágono regular de lado $L$
- Área da base: $A_b = \frac{3L^2\sqrt{3}}{2}$
- Área lateral: $A_l = 3L \cdot a_p$
- Volume: $V = \frac{L^2\sqrt{3} \cdot h}{2}$

## Cones

### Cone Circular Reto

Superfície gerada pela rotação de um triângulo retângulo em torno de um cateto.

### Elementos

| Elemento | Definição | Fórmula |
|----------|-----------|---------|
| **Raio da base** | Raio do círculo de base | $r$ |
| **Altura** | Distância do vértice ao plano da base | $h$ |
| **Geratriz** | Segmento do vértice a um ponto da circunferência | $g = \sqrt{r^2 + h^2}$ |

### Área da Base

$$ A_b = \pi r^2 $$

### Área Lateral

$$ A_l = \pi r g = \pi r \sqrt{r^2 + h^2} $$

> **Demonstração:** A superfície lateral desenvolvida é um setor circular de raio $g$ e arco $2\pi r$. A área do setor é $\frac{2\pi r}{2\pi g} \cdot \pi g^2 = \pi r g$.

### Área Total

$$ A_t = \pi r^2 + \pi r g = \pi r(r + g) $$

### Volume

$$ V = \frac{1}{3} \pi r^2 h $$

> Mesmo fator $\frac{1}{3}$ da pirâmide! Um cilindro com a mesma base e altura tem volume 3 vezes maior.

### Cone Equilátero

Cone cuja geratriz é igual ao diâmetro da base ($g = 2r$).

$$ h^2 + r^2 = (2r)^2 = 4r^2 \implies h^2 = 3r^2 \implies h = r\sqrt{3} $$

$$ A_t = \pi r^2 + \pi r(2r) = 3\pi r^2 $$
$$ V = \frac{1}{3} \pi r^2 (r\sqrt{3}) = \frac{\pi r^3 \sqrt{3}}{3} $$

## Tronco de Pirâmide e Tronco de Cone

### Tronco de Pirâmide

Parte de uma pirâmide entre a base e um plano paralelo à base.

$$ V = \frac{h}{3}(A_B + A_b + \sqrt{A_B \cdot A_b}) $$

Onde $A_B$ é a área da base maior, $A_b$ é a área da base menor, e $h$ é a altura do tronco.

### Tronco de Cone

$$ V = \frac{\pi h}{3}(R^2 + r^2 + Rr) $$

Onde $R$ é o raio da base maior, $r$ é o raio da base menor.

Área lateral do tronco de cone:
$$ A_l = \pi(R + r)g $$

Onde $g$ é a geratriz do tronco.

## Exemplos

### Exemplo 1: Pirâmide quadrangular regular

Uma pirâmide quadrangular regular tem base de lado 6 cm e altura 4 cm. Determine sua área lateral, área total e volume.

$$ A_b = 6^2 = 36 \text{ cm}^2 $$

Apótema da base: $a_b = 6/2 = 3$ cm.
Apótema da pirâmide: $a_p = \sqrt{4^2 + 3^2} = \sqrt{16 + 9} = \sqrt{25} = 5$ cm.

$$ A_l = \frac{1}{2} \cdot 24 \cdot 5 = 60 \text{ cm}^2 $$
$$ A_t = 36 + 60 = 96 \text{ cm}^2 $$
$$ V = \frac{36 \cdot 4}{3} = 48 \text{ cm}^3 $$

**Resposta:** $A_l = 60$ cm$^2$, $A_t = 96$ cm$^2$, $V = 48$ cm$^3$.

### Exemplo 2: Cone

Um cone circular reto tem raio 3 cm e altura 4 cm. Determine sua geratriz, área lateral, área total e volume.

$$ g = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = 5 \text{ cm} $$
$$ A_l = \pi \cdot 3 \cdot 5 = 15\pi \approx 47{,}12 \text{ cm}^2 $$
$$ A_b = \pi \cdot 3^2 = 9\pi \text{ cm}^2 $$
$$ A_t = 9\pi + 15\pi = 24\pi \approx 75{,}40 \text{ cm}^2 $$
$$ V = \frac{1}{3} \cdot 9\pi \cdot 4 = 12\pi \approx 37{,}70 \text{ cm}^3 $$

**Resposta:** $g = 5$ cm, $A_l = 15\pi$ cm$^2$, $A_t = 24\pi$ cm$^2$, $V = 12\pi$ cm$^3$.

### Exemplo 3: Tronco de cone

Um tronco de cone tem raios $R = 6$ cm e $r = 2$ cm, e altura $h = 4$ cm. Determine seu volume.

$$ V = \frac{\pi \cdot 4}{3}(36 + 4 + 12) = \frac{4\pi}{3} \cdot 52 = \frac{208\pi}{3} \approx 217{,}72 \text{ cm}^3 $$

**Resposta:** $\frac{208\pi}{3}$ cm$^3$ $\approx 217{,}72$ cm$^3$.

### Exemplo 4: Cone equilátero

Um cone equilátero tem raio 4 cm. Determine sua altura, área total e volume.

$$ g = 2r = 8 \text{ cm} $$
$$ h = \sqrt{8^2 - 4^2} = \sqrt{64 - 16} = \sqrt{48} = 4\sqrt{3} \approx 6{,}93 \text{ cm} $$
$$ A_t = 3\pi \cdot 4^2 = 48\pi \approx 150{,}80 \text{ cm}^2 $$
$$ V = \frac{\pi \cdot 4^3 \sqrt{3}}{3} = \frac{64\pi\sqrt{3}}{3} \approx 116{,}18 \text{ cm}^3 $$

**Resposta:** $h = 4\sqrt{3}$ cm, $A_t = 48\pi$ cm$^2$, $V = \frac{64\pi\sqrt{3}}{3}$ cm$^3$.

## Aplicações na Vida Real

- **Arquitetura:** telhados, cúpulas, pirâmides egípcias, torres com pontas
- **Engenharia:** funis, bocais, silos com ponta cônica, chaminés
- **Indústria:** copos cônicos, embalagens de sorvete, cones de trânsito
- **Geologia:** vulcões (formato cônico), depósitos aluviais
- **Astronomia:** crateras de impacto, montanhas, formações rochosas
- **Acústica:** cornetas, megafones, alto-falantes (cone de som)
- **Militar:** silos de mísseis, abrigos com teto cônico
- **Esportes:** slalom (cones), treinamento de agilidade
- **Medicina:** funis de laboratório, embudos, cones de Otoscopia
- **Arte:** esculturas, objetos decorativos, origami cônico

## Problemas

### Nível 1 — Básico

**1.** Uma pirâmide quadrangular regular tem base de lado 8 cm e altura 3 cm. Determine sua área total e volume.

$$ A_b = 64 \text{ cm}^2 $$
$$ a_p = \sqrt{3^2 + 4^2} = 5 \text{ cm} $$
$$ A_l = 2 \cdot 8 \cdot 5 = 80 \text{ cm}^2 $$
$$ A_t = 64 + 80 = 144 \text{ cm}^2 $$
$$ V = \frac{64 \cdot 3}{3} = 64 \text{ cm}^3 $$

**Resposta:** $A_t = 144$ cm$^2$, $V = 64$ cm$^3$.

**2.** Um cone circular reto tem raio 6 cm e altura 8 cm. Determine sua geratriz, área lateral e volume.

$$ g = \sqrt{36 + 64} = 10 \text{ cm} $$
$$ A_l = \pi \cdot 6 \cdot 10 = 60\pi \approx 188{,}50 \text{ cm}^2 $$
$$ V = \frac{1}{3} \cdot 36\pi \cdot 8 = 96\pi \approx 301{,}59 \text{ cm}^3 $$

**Resposta:** $g = 10$ cm, $A_l = 60\pi$ cm$^2$, $V = 96\pi$ cm$^3$.

**3.** Uma pirâmide triangular regular tem base de lado 4 cm e altura 6 cm. Determine seu volume.

$$ A_b = \frac{4^2\sqrt{3}}{4} = 4\sqrt{3} \text{ cm}^2 $$
$$ V = \frac{4\sqrt{3} \cdot 6}{3} = 8\sqrt{3} \approx 13{,}86 \text{ cm}^3 $$

**Resposta:** $8\sqrt{3}$ cm$^3$ $\approx 13{,}86$ cm$^3$.

**4.** Um cone tem volume $100\pi$ cm$^3$ e raio 5 cm. Determine sua altura.

$$ \frac{1}{3} \pi \cdot 25 \cdot h = 100\pi $$
$$ \frac{25h}{3} = 100 \implies h = 12 \text{ cm} $$

**Resposta:** 12 cm.

**5.** Um tronco de pirâmide quadrangular tem bases de lados 10 cm e 6 cm, e altura 4 cm. Determine seu volume.

$$ A_B = 100, \quad A_b = 36 $$
$$ V = \frac{4}{3}(100 + 36 + \sqrt{3600}) = \frac{4}{3}(136 + 60) = \frac{4}{3} \cdot 196 = \frac{784}{3} \approx 261{,}33 \text{ cm}^3 $$

**Resposta:** $\frac{784}{3}$ cm$^3$ $\approx 261{,}33$ cm$^3$.

### Nível 2 — Intermediário

**6.** Uma pirâmide hexagonal regular tem base de lado 5 cm e apótema da pirâmide 12 cm. Determine sua área lateral, área total e volume.

$$ A_b = \frac{3 \cdot 5^2 \sqrt{3}}{2} = \frac{75\sqrt{3}}{2} \approx 64{,}95 \text{ cm}^2 $$
$$ 2p = 30 \text{ cm} $$
$$ A_l = \frac{1}{2} \cdot 30 \cdot 12 = 180 \text{ cm}^2 $$
$$ A_t = 180 + \frac{75\sqrt{3}}{2} \approx 244{,}95 \text{ cm}^2 $$

Apótema da base: $a_b = \frac{5\sqrt{3}}{2} \approx 4{,}33$ cm.
Altura: $h = \sqrt{12^2 - (5\sqrt{3}/2)^2} = \sqrt{144 - 75/4} = \sqrt{144 - 18{,}75} = \sqrt{125{,}25} \approx 11{,}19$ cm.

$$ V = \frac{1}{3} \cdot \frac{75\sqrt{3}}{2} \cdot 11{,}19 \approx 242{,}3 \text{ cm}^3 $$

**Resposta:** $A_l = 180$ cm$^2$, $A_t \approx 244{,}95$ cm$^2$, $V \approx 242{,}3$ cm$^3$.

**7.** Um cone equilátero tem área total $27\pi$ cm$^2$. Determine seu raio, altura e volume.

$$ A_t = 3\pi r^2 = 27\pi \implies r^2 = 9 \implies r = 3 \text{ cm} $$
$$ h = r\sqrt{3} = 3\sqrt{3} \approx 5{,}20 \text{ cm} $$
$$ V = \frac{\pi \cdot 27 \cdot 3\sqrt{3}}{3} = 27\pi\sqrt{3} \approx 147{,}03 \text{ cm}^3 $$

**Resposta:** Raio = 3 cm, $h = 3\sqrt{3}$ cm, $V = 27\pi\sqrt{3}$ cm$^3$.

**8.** Uma pirâmide quadrangular regular tem volume 72 cm$^3$ e altura 6 cm. Determine o lado da base e a área total.

$$ V = \frac{L^2 \cdot h}{3} = 72 $$
$$ \frac{L^2 \cdot 6}{3} = 72 \implies 2L^2 = 72 \implies L^2 = 36 \implies L = 6 \text{ cm} $$

$$ a_p = \sqrt{6^2 + 3^2} = \sqrt{45} = 3\sqrt{5} \text{ cm} $$
$$ A_l = 2 \cdot 6 \cdot 3\sqrt{5} = 36\sqrt{5} \approx 80{,}50 \text{ cm}^2 $$
$$ A_t = 36 + 36\sqrt{5} = 36(1 + \sqrt{5}) \approx 116{,}50 \text{ cm}^2 $$

**Resposta:** Lado = 6 cm, $A_t = 36(1 + \sqrt{5})$ cm$^2$.

**9.** Um funil tem formato de tronco de cone com raios 5 cm e 2 cm, e altura 6 cm. Determine sua capacidade em litros (1 L = 1000 cm$^3$).

$$ V = \frac{\pi \cdot 6}{3}(25 + 4 + 10) = 2\pi \cdot 39 = 78\pi \approx 245{,}04 \text{ cm}^3 $$
$$ \text{Litros} = \frac{78\pi}{1000} \approx 0{,}245 \text{ L} $$

**Resposta:** $78\pi$ cm$^3$ $\approx 0{,}245$ litros.

**10.** Uma pirâmide e um prisma têm a mesma base e a mesma altura. Se o volume do prisma é 180 cm$^3$, qual o volume da pirâmide?

$$ V_{pirâmide} = \frac{1}{3} V_{prisma} = \frac{180}{3} = 60 \text{ cm}^3 $$

**Resposta:** 60 cm$^3$.

### Nível 3 — Desafio

**11.** Um cone e um cilindro têm a mesma base e mesmo volume. Se o cone tem altura 12 cm, qual a altura do cilindro? Se o cilindro tem altura 12 cm, qual a altura do cone?

**Caso 1:** Cone $h_c = 12$, cilindro $h_{cil}$ = ?
$$ \frac{1}{3} A_b \cdot 12 = A_b \cdot h_{cil} \implies 4 = h_{cil} $$

**Caso 2:** Cilindro $h_{cil} = 12$, cone $h_c$ = ?
$$ \frac{1}{3} A_b \cdot h_c = A_b \cdot 12 \implies h_c = 36 $$

**Resposta:** Se cone tem altura 12, cilindro tem altura 4. Se cilindro tem altura 12, cone tem altura 36.

**12.** Uma pirâmide quadrangular regular tem aresta lateral igual a $5\sqrt{2}$ cm e altura 5 cm. Determine o lado da base, a área total e o volume.

$$ \ell^2 = h^2 + R^2 $$
$$ (5\sqrt{2})^2 = 5^2 + R^2 $$
$$ 50 = 25 + R^2 \implies R^2 = 25 \implies R = 5 \text{ cm} $$

Para um quadrado: $R = \frac{L\sqrt{2}}{2} = 5 \implies L\sqrt{2} = 10 \implies L = 5\sqrt{2}$ cm.

$$ A_b = (5\sqrt{2})^2 = 50 \text{ cm}^2 $$
$$ a_p = \sqrt{h^2 + a_b^2} = \sqrt{25 + (5\sqrt{2}/2)^2} = \sqrt{25 + 25/2} = \sqrt{37{,}5} = \frac{5\sqrt{6}}{2} \approx 6{,}12 \text{ cm} $$

$$ A_l = 2 \cdot 5\sqrt{2} \cdot \frac{5\sqrt{6}}{2} = 25\sqrt{12} = 50\sqrt{3} \approx 86{,}60 \text{ cm}^2 $$
$$ A_t = 50 + 50\sqrt{3} = 50(1 + \sqrt{3}) \approx 136{,}60 \text{ cm}^2 $$
$$ V = \frac{50 \cdot 5}{3} = \frac{250}{3} \approx 83{,}33 \text{ cm}^3 $$

**Resposta:** Lado = $5\sqrt{2}$ cm; $A_t = 50(1 + \sqrt{3})$ cm$^2$; $V = \frac{250}{3}$ cm$^3$.

**13.** (Semelhança de cones) Um cone pequeno é cortado por um plano paralelo à base, deixando um tronco de altura 4 cm. O cone original tem altura 6 cm e raio 3 cm. Determine o raio do cone menor removido e o volume do tronco.

Cone original: $h = 6$, $r = 3$.
Cone menor: $h' = 6 - 4 = 2$ cm.

Por semelhança:
$$ \frac{r'}{r} = \frac{h'}{h} = \frac{2}{6} = \frac{1}{3} \implies r' = 1 \text{ cm} $$

Volume do cone original:
$$ V = \frac{1}{3} \pi \cdot 9 \cdot 6 = 18\pi \text{ cm}^3 $$

Volume do cone menor:
$$ V' = \frac{1}{3} \pi \cdot 1 \cdot 2 = \frac{2\pi}{3} \text{ cm}^3 $$

Volume do tronco:
$$ V_{tronco} = 18\pi - \frac{2\pi}{3} = \frac{54\pi - 2\pi}{3} = \frac{52\pi}{3} \approx 54{,}45 \text{ cm}^3 $$

**Resposta:** Raio do cone menor = 1 cm. Volume do tronco = $\frac{52\pi}{3}$ cm$^3$ $\approx 54{,}45$ cm$^3$.

---
**Fim — Pirâmides e Cones**
