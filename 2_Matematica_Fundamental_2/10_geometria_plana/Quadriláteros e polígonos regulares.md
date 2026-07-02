# Quadriláteros e Polígonos Regulares

**Quadriláteros** são polígonos de quatro lados, e **polígonos regulares** são polígonos com todos os lados e ângulos internos iguais. Neste arquivo, exploramos as propriedades, classificações e fórmulas de área dessas figuras fundamentais.

## Quadriláteros Notáveis

### Paralelogramo

Quadrilátero com lados opostos paralelos.

**Propriedades:**
- Lados opostos congruentes (iguais)
- Ângulos opostos congruentes
- Diagonais se bissectam (cortam ao meio)
- Ângulos adjacentes são suplementares

**Área:**
$$ A = b \cdot h $$

Onde $b$ é a base e $h$ é a altura (distância entre as bases paralelas).

### Retângulo

Paralelogramo com todos os ângulos retos ($90°$).

**Propriedades:**
- Tudo do paralelogramo, mais:
- Diagonais congruentes (iguais entre si)
- Ângulos todos iguais a $90°$

**Área:**
$$ A = b \cdot h = \ell \cdot w \quad \text{(comprimento } \times \text{ largura)} $$

**Perímetro:**
$$ P = 2(b + h) $$

**Diagonal:**
$$ d = \sqrt{b^2 + h^2} \quad \text{(Pitágoras)} $$

### Losango

Paralelogramo com todos os lados iguais.

**Propriedades:**
- Tudo do paralelogramo, mais:
- Diagonais perpendiculares (formam $90°$)
- Diagonais são bisetrizes dos ângulos

**Área:**
$$ A = \frac{D \cdot d}{2} $$

Onde $D$ e $d$ são as diagonais maiores e menores.

### Quadrado

Retângulo e losango ao mesmo tempo (todos os lados iguais e todos os ângulos $90°$).

**Propriedades:**
- Tudo do retângulo e do losango
- Diagonais iguais, perpendiculares, e bisetrizes

**Área:**
$$ A = L^2 $$

**Perímetro:**
$$ P = 4L $$

**Diagonal:**
$$ d = L\sqrt{2} $$

### Trapézio

Quadrilátero com apenas um par de lados paralelos (bases).

**Tipos:**
- **Trapézio isósceles:** lados não paralelos (pernas) congruentes
- **Trapézio retângulo:** um ângulo reto (dois ângulos retos, adjacentes)

**Área:**
$$ A = \frac{(B + b) \cdot h}{2} $$

Onde $B$ é a base maior, $b$ é a base menor, $h$ é a altura.

**Segmento médio (base média):**
$$ b_m = \frac{B + b}{2} $$

$$ A = b_m \cdot h $$

## Tabela Comparativa de Quadriláteros

| Propriedade | Paralelogramo | Retângulo | Losango | Quadrado | Trapézio |
|-------------|---------------|-----------|---------|----------|----------|
| Lados opostos $\parallel$ | ✓ | ✓ | ✓ | ✓ | 1 par |
| Todos os ângulos $= 90°$ | | ✓ | | ✓ | |
| Todos os lados iguais | | | ✓ | ✓ | |
| Diagonais iguais | | ✓ | | ✓ | (isósceles) |
| Diagonais $\perp$ | | | ✓ | ✓ | |
| Diagonais bissectam | ✓ | ✓ | ✓ | ✓ | |

## Polígonos Regulares

Polígono com todos os lados e ângulos internos iguais.

### Ângulo Interno

$$ \alpha = \frac{(n - 2) \cdot 180°}{n} $$

### Ângulo Central

$$ \theta = \frac{360°}{n} $$

### Apótema (distância do centro ao meio de um lado)

$$ a = \frac{L}{2 \tan(\pi/n)} = R \cdot \cos\left(\frac{\pi}{n}\right) $$

Onde $L$ é o lado e $R$ é o raio da circunferência circunscrita.

### Área

$$ A = \frac{n \cdot L \cdot a}{2} = \frac{n \cdot R^2 \cdot \sin(2\pi/n)}{2} $$

Ou:

$$ A = \frac{P \cdot a}{2} \quad \text{(Perímetro } \times \text{ apótema / 2)} $$

### Áreas de Polígonos Regulares Comuns

| Polígono | Fórmula de Área (em função do lado $L$) |
|----------|----------------------------------------|
| Triângulo equilátero | $A = \frac{L^2\sqrt{3}}{4}$ |
| Quadrado | $A = L^2$ |
| Pentágono regular | $A = \frac{5L^2}{4\tan(36°)} \approx 1{,}72L^2$ |
| Hexágono regular | $A = \frac{3L^2\sqrt{3}}{2} \approx 2{,}60L^2$ |
| Octógono regular | $A = 2(1+\sqrt{2})L^2 \approx 4{,}83L^2$ |

## Exemplos

### Exemplo 1: Área do losango

Um losango tem diagonais 10 cm e 6 cm. Qual sua área?

$$ A = \frac{10 \cdot 6}{2} = 30 \text{ cm}^2 $$

**Resposta:** $30 \text{ cm}^2$.

### Exemplo 2: Área do trapézio

Um trapézio tem bases 8 cm e 12 cm, e altura 5 cm. Qual sua área?

$$ A = \frac{(8 + 12) \cdot 5}{2} = \frac{20 \cdot 5}{2} = 50 \text{ cm}^2 $$

**Resposta:** $50 \text{ cm}^2$.

### Exemplo 3: Área do hexágono regular

Um hexágono regular tem lado 4 cm. Qual sua área?

$$ A = \frac{3 \cdot 4^2 \cdot \sqrt{3}}{2} = \frac{3 \cdot 16 \cdot \sqrt{3}}{2} = 24\sqrt{3} \approx 41{,}57 \text{ cm}^2 $$

**Resposta:** $24\sqrt{3} \text{ cm}^2 \approx 41{,}57 \text{ cm}^2$.

### Exemplo 4: Diagonal do quadrado

Um quadrado tem lado 5 cm. Qual a diagonal?

$$ d = 5\sqrt{2} \approx 7{,}07 \text{ cm} $$

**Resposta:** $5\sqrt{2}$ cm $\approx 7{,}07$ cm.

## Aplicações na Vida Real

- **Arquitetura:** projetos de salas, jardins, pisos, tetos
- **Engenharia:** cálculo de áreas de terrenos, estradas, reservatórios
- **Agricultura:** área de plantio, cálculo de insumos
- **Design:** padrões de pisos, mosaicos, tesselações
- **Jogos:** grids, mapas, colisão em tiles quadrados/hexagonais
- **Tecnologia:** pixels (quadrados), layout de telas, design responsivo
- **Matemática recreativa:** quebra-cabeças de polígonos, tangram
- **Empacotamento:** caixas (paralelepípedos), embalagens hexagonais (mel)
- **Esportes:** campos de futebol (retângulo), pistas de atletismo
- **Arte:** mosaicos, azulejos, padrões geométricos

## Problemas

### Nível 1 — Básico

**1.** Um retângulo tem lados 6 cm e 8 cm. Determine sua área, perímetro e diagonal.

$$ A = 6 \cdot 8 = 48 \text{ cm}^2 $$
$$ P = 2(6 + 8) = 28 \text{ cm} $$
$$ d = \sqrt{6^2 + 8^2} = \sqrt{36 + 64} = \sqrt{100} = 10 \text{ cm} $$

**Resposta:** Área = $48 \text{ cm}^2$, perímetro = $28$ cm, diagonal = $10$ cm.

**2.** Um losango tem diagonais 8 cm e 10 cm. Qual sua área?

$$ A = \frac{8 \cdot 10}{2} = 40 \text{ cm}^2 $$

**Resposta:** $40 \text{ cm}^2$.

**3.** Um trapézio tem bases 6 cm e 10 cm, e altura 4 cm. Qual sua área?

$$ A = \frac{(6 + 10) \cdot 4}{2} = 32 \text{ cm}^2 $$

**Resposta:** $32 \text{ cm}^2$.

**4.** Um quadrado tem diagonal $6\sqrt{2}$ cm. Qual o lado?

$$ d = L\sqrt{2} = 6\sqrt{2} \implies L = 6 \text{ cm} $$

**Resposta:** Lado = 6 cm.

**5.** Determine o ângulo interno de um hexágono regular.

$$ \alpha = \frac{(6-2) \cdot 180°}{6} = \frac{4 \cdot 180°}{6} = 120° $$

**Resposta:** $120°$.

### Nível 2 — Intermediário

**6.** Um retângulo tem área $48 \text{ m}^2$ e um lado mede 6 m. Determine o outro lado e a diagonal.

$$ b = \frac{48}{6} = 8 \text{ m} $$
$$ d = \sqrt{6^2 + 8^2} = 10 \text{ m} $$

**Resposta:** Outro lado = 8 m, diagonal = 10 m.

**7.** Um losango tem perímetro 20 cm e uma diagonal 6 cm. Determine a outra diagonal e a área.

$$ L = \frac{20}{4} = 5 \text{ cm} $$

Relação entre diagonais e lado em losango:
$$ \left(\frac{D}{2}\right)^2 + \left(\frac{d}{2}\right)^2 = L^2 $$

$$ \left(\frac{6}{2}\right)^2 + \left(\frac{d}{2}\right)^2 = 25 $$
$$ 9 + \frac{d^2}{4} = 25 \implies \frac{d^2}{4} = 16 \implies d^2 = 64 \implies d = 8 \text{ cm} $$

$$ A = \frac{6 \cdot 8}{2} = 24 \text{ cm}^2 $$

**Resposta:** Outra diagonal = 8 cm, área = $24 \text{ cm}^2$.

**8.** Um trapézio isósceles tem bases 8 cm e 14 cm, e altura 4 cm. Determine os lados não paralelos e a área.

$$ A = \frac{(8 + 14) \cdot 4}{2} = 44 \text{ cm}^2 $$

Projeção de cada lado não paralelo sobre a base maior:
$$ \frac{14 - 8}{2} = 3 \text{ cm} $$

$$ L = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5 \text{ cm} $$

**Resposta:** Área = $44 \text{ cm}^2$, lados não paralelos = 5 cm cada.

**9.** Determine a área de um pentágono regular de lado 4 cm.

$$ A = \frac{5 \cdot 4^2}{4 \tan(36°)} = \frac{80}{4 \cdot 0{,}7265} = \frac{80}{2{,}906} \approx 27{,}53 \text{ cm}^2 $$

**Resposta:** Aproximadamente $27{,}53 \text{ cm}^2$ (ou $20\tan(54°) \approx 27{,}53$).

**10.** Um terreno tem formato de trapézio com bases 40 m e 60 m, e altura 30 m. Se o metro quadrado vale R$ 500,00, qual o valor do terreno?

$$ A = \frac{(40 + 60) \cdot 30}{2} = 1500 \text{ m}^2 $$
$$ \text{Valor} = 1500 \cdot 500 = 750.000 \text{ reais} $$

**Resposta:** R$ 750.000,00.

### Nível 3 — Desafio

**11.** Um quadrado está inscrito num círculo de raio $R$. Determine a área do quadrado e a área da região entre o círculo e o quadrado.

Diagonal do quadrado = diâmetro do círculo = $2R$
$$ L\sqrt{2} = 2R \implies L = R\sqrt{2} $$
$$ A_{quadrado} = L^2 = 2R^2 $$
$$ A_{círculo} = \pi R^2 $$
$$ A_{região} = \pi R^2 - 2R^2 = R^2(\pi - 2) $$

**Resposta:** Área do quadrado = $2R^2$. Área entre círculo e quadrado = $R^2(\pi - 2)$.

**12.** Um hexágono regular tem lado $L$. Prove que sua área é $\frac{3L^2\sqrt{3}}{2}$ e determine sua área em função do raio $R$ da circunferência circunscrita.

Um hexágono regular é formado por 6 triângulos equiláteros de lado $L$ (pois o raio $R = L$ no hexágono regular).

$$ A_{triângulo} = \frac{L^2\sqrt{3}}{4} $$
$$ A_{hexágono} = 6 \cdot \frac{L^2\sqrt{3}}{4} = \frac{3L^2\sqrt{3}}{2} $$

Como $R = L$:
$$ A = \frac{3R^2\sqrt{3}}{2} $$

**Resposta:** Área = $\frac{3L^2\sqrt{3}}{2} = \frac{3R^2\sqrt{3}}{2}$ (pois $R = L$).

**13.** Um terreno tem formato de trapézio retângulo com bases 20 m e 30 m, e altura 15 m. Quanto de cerca é necessária para cercar o terreno (perímetro)?

$$ \text{Base maior} = 30 \text{ m}, \text{ base menor} = 20 \text{ m}, \text{ altura} = 15 \text{ m} $$

Lados do trapézio retângulo:
- Lado perpendicular (altura) = 15 m
- Base inferior = 30 m
- Base superior = 20 m
- Lado inclinado: diferença de bases = $30 - 20 = 10$ m

$$ L_{inclinado} = \sqrt{10^2 + 15^2} = \sqrt{100 + 225} = \sqrt{325} = 5\sqrt{13} \approx 18{,}03 \text{ m} $$

$$ P = 30 + 20 + 15 + 5\sqrt{13} = 65 + 5\sqrt{13} \approx 83{,}03 \text{ m} $$

**Resposta:** $65 + 5\sqrt{13}$ m $\approx 83{,}03$ m.

---
**Fim — Quadriláteros e Polígonos Regulares**
