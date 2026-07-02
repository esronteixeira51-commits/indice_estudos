# Áreas de Figuras Compostas e Aplicações

**Figuras compostas** são formadas pela união ou diferença de figuras geométricas simples. Calcular áreas, perímetros e volumes de figuras compostas é uma habilidade essencial em arquitetura, engenharia, design e na vida cotidiana — desde calcular a tinta necessária para pintar uma parede com janelas até determinar o terreno de uma casa com piscina.

## Estratégias para Figuras Compostas

### 1. Decomposição

Dividir a figura composta em figuras simples (retângulos, triângulos, círculos, etc.) e somar suas áreas.

$$ A_{total} = A_1 + A_2 + A_3 + \ldots $$

### 2. Subtração

Calcular a área de uma figura maior e subtrair as áreas das partes que não pertencem à figura desejada.

$$ A_{total} = A_{grande} - A_{vazio} $$

### 3. Complementação

Completar a figura para formar uma figura simples e depois subtrair o "excesso".

### 4. Coordenadas e Geometria Analítica

Usar coordenadas cartesianas para calcular áreas (fórmula de Shoelace, integração).

## Fórmulas de Área Revisão Rápida

| Figura | Fórmula |
|--------|---------|
| Triângulo | $A = \frac{b \cdot h}{2}$ |
| Retângulo | $A = b \cdot h$ |
| Quadrado | $A = L^2$ |
| Losango | $A = \frac{D \cdot d}{2}$ |
| Paralelogramo | $A = b \cdot h$ |
| Trapézio | $A = \frac{(B + b) \cdot h}{2}$ |
| Círculo | $A = \pi r^2$ |
| Setor circular | $A = \frac{\theta}{360°} \cdot \pi r^2$ |
| Triângulo equilátero | $A = \frac{L^2\sqrt{3}}{4}$ |
| Hexágono regular | $A = \frac{3L^2\sqrt{3}}{2}$ |

## Exemplos

### Exemplo 1: L em retângulos

Uma figura em "L" é formada por dois retângulos: um de $8 \times 3$ e outro de $3 \times 5$. Qual a área total?

$$ A = 8 \cdot 3 + 3 \cdot 5 = 24 + 15 = 39 \text{ unidades}^2 $$

Ou como um retângulo grande menos um vazio:
$$ A = 8 \cdot 8 - 5 \cdot 5 = 64 - 25 = 39 \text{ unidades}^2 $$

**Resposta:** $39 \text{ unidades}^2$.

### Exemplo 2: Parede com janela

Uma parede retangular mede $5 \times 3$ m. Nela há uma janela retangular de $1{,}2 \times 0{,}8$ m. Quanto de tinta é necessário (em m$^2$) para pintar a parede?

$$ A_{parede} = 5 \cdot 3 = 15 \text{ m}^2 $$
$$ A_{janela} = 1{,}2 \cdot 0{,}8 = 0{,}96 \text{ m}^2 $$
$$ A_{pintar} = 15 - 0{,}96 = 14{,}04 \text{ m}^2 $$

**Resposta:** $14{,}04$ m$^2$.

### Exemplo 3: Terreno com piscina

Um terreno retangular $20 \times 30$ m tem uma piscina circular de raio 5 m no centro. Qual a área do terreno que não é piscina?

$$ A_{terreno} = 20 \cdot 30 = 600 \text{ m}^2 $$
$$ A_{piscina} = \pi \cdot 5^2 = 25\pi \approx 78{,}54 \text{ m}^2 $$
$$ A_{restante} = 600 - 25\pi \approx 521{,}46 \text{ m}^2 $$

**Resposta:** $600 - 25\pi$ m$^2$ $\approx 521{,}46$ m$^2$.

### Exemplo 4: Cruz de quadrados

Uma cruz é formada por 5 quadrados congruentes de lado 2. Qual sua área e perímetro?

$$ A = 5 \cdot 2^2 = 20 \text{ unidades}^2 $$

Perímetro: contando os lados externos (12 lados de tamanho 2):
$$ P = 12 \cdot 2 = 24 \text{ unidades} $$

**Resposta:** Área = 20, Perímetro = 24.

### Exemplo 5: Semicírculos sobre o diâmetro

Um círculo de raio 6 cm tem dois semicírculos menores construídos sobre seu diâmetro (como em um símbolo de Yin-Yang). Os semicírculos menores têm raio 3 cm. Qual a área da região entre o círculo grande e os dois semicírculos menores?

$$ A_{círculo} = \pi \cdot 6^2 = 36\pi \text{ cm}^2 $$
$$ A_{semicírculos} = 2 \cdot \frac{\pi \cdot 3^2}{2} = 9\pi \text{ cm}^2 $$
$$ A_{região} = 36\pi - 9\pi = 27\pi \text{ cm}^2 $$

**Resposta:** $27\pi$ cm$^2$ $\approx 84{,}82$ cm$^2$.

## Fórmula de Shoelace (Área de Polígono por Coordenadas)

Para um polígono com vértices $(x_1, y_1), (x_2, y_2), \ldots, (x_n, y_n)$:

$$ A = \frac{1}{2} |x_1y_2 + x_2y_3 + \ldots + x_ny_1 - (y_1x_2 + y_2x_3 + \ldots + y_nx_1)| $$

## Aplicações na Vida Real

- **Construção:** cálculo de área de pisos, paredes, telhados, terrenos irregulares
- **Agricultura:** cálculo de área de plantio, divisão de terrenos
- **Arquitetura:** plantas baixas, corte de materiais, aproveitamento de espaço
- **Design de interiores:** carpete, pisos, tinta, papel de parede
- **Paisagismo:** cálculo de grama, cascalho, área de jardins
- **Engenharia:** corte de chapas, otimização de material, áreas de seção
- **Cartografia:** área de lagos, florestas, cidades (polígonos irregulares)
- **Jogos:** colisão, área de spawn, pathfinding em grids
- **Artesanato:** corte de tecido, couro, papel, vidro
- **Economia doméstica:** cálculo de custo de materiais por área

## Problemas

### Nível 1 — Básico

**1.** Uma figura é formada por um retângulo $5 \times 3$ e um triângulo de base 5 e altura 2 sobreposto à base superior. Qual a área total?

$$ A = 5 \cdot 3 + \frac{5 \cdot 2}{2} = 15 + 5 = 20 \text{ unidades}^2 $$

**Resposta:** $20 \text{ unidades}^2$.

**2.** Um terreno quadrado de lado 40 m tem uma casa retangular de $15 \times 10$ m no centro. Qual a área livre?

$$ A = 40^2 - 15 \cdot 10 = 1600 - 150 = 1450 \text{ m}^2 $$

**Resposta:** $1450$ m$^2$.

**3.** Uma figura é formada por um semicírculo de raio 4 sobre um retângulo $8 \times 5$. Qual a área total?

$$ A = 8 \cdot 5 + \frac{\pi \cdot 4^2}{2} = 40 + 8\pi \approx 40 + 25{,}13 = 65{,}13 \text{ unidades}^2 $$

**Resposta:** $40 + 8\pi$ $\approx 65{,}13$ unidades$^2$.

**4.** Um cartaz retangular $60 \times 40$ cm tem 4 fotos quadradas de $10 \times 10$ cm. Qual a área do cartaz não coberta pelas fotos?

$$ A = 60 \cdot 40 - 4 \cdot 10^2 = 2400 - 400 = 2000 \text{ cm}^2 $$

**Resposta:** $2000$ cm$^2$.

**5.** Uma pista de atletismo tem formato retangular $100 \times 50$ m, com semicírculos nos dois lados menores (raio 25 m). Qual o comprimento total da pista (perímetro)?

$$ \text{Comprimento retas} = 2 \cdot 100 = 200 \text{ m} $$
$$ \text{Comprimento semicírculos (2 juntos = 1 círculo)} = 2\pi \cdot 25 = 50\pi \approx 157{,}08 \text{ m} $$
$$ P = 200 + 50\pi \approx 357{,}08 \text{ m} $$

**Resposta:** $200 + 50\pi$ m $\approx 357{,}08$ m.

### Nível 2 — Intermediário

**6.** Um jardim tem formato de trapézio com bases 10 m e 16 m, e altura 8 m. No centro há uma fonte circular de raio 2 m. Qual a área do jardim (sem a fonte)?

$$ A_{trapézio} = \frac{(10 + 16) \cdot 8}{2} = 104 \text{ m}^2 $$
$$ A_{fonte} = \pi \cdot 2^2 = 4\pi \approx 12{,}57 \text{ m}^2 $$
$$ A_{jardim} = 104 - 4\pi \approx 91{,}43 \text{ m}^2 $$

**Resposta:** $104 - 4\pi$ m$^2$ $\approx 91{,}43$ m$^2$.

**7.** Uma figura é formada por um quadrado de lado 8 com um triângulo equilátero sobre um lado e um semicírculo sobre o lado oposto. Qual a área total?

$$ A_{quadrado} = 8^2 = 64 $$
$$ A_{triângulo} = \frac{8^2\sqrt{3}}{4} = 16\sqrt{3} \approx 27{,}71 $$
$$ A_{semicírculo} = \frac{\pi \cdot 4^2}{2} = 8\pi \approx 25{,}13 $$

$$ A_{total} = 64 + 16\sqrt{3} + 8\pi \approx 116{,}84 \text{ unidades}^2 $$

**Resposta:** $64 + 16\sqrt{3} + 8\pi$ $\approx 116{,}84$ unidades$^2$.

**8.** Uma parede de $4 \times 2{,}5$ m tem uma porta $2{,}1 \times 0{,}9$ m e uma janela $1{,}2 \times 0{,}8$ m. Se um litro de tinta cobre 4 m$^2$, quantos litros são necessários?

$$ A_{parede} = 4 \cdot 2{,}5 = 10 \text{ m}^2 $$
$$ A_{porta} = 2{,}1 \cdot 0{,}9 = 1{,}89 \text{ m}^2 $$
$$ A_{janela} = 1{,}2 \cdot 0{,}8 = 0{,}96 \text{ m}^2 $$
$$ A_{pintar} = 10 - 1{,}89 - 0{,}96 = 7{,}15 \text{ m}^2 $$
$$ \text{Litros} = \frac{7{,}15}{4} = 1{,}7875 \approx 2 \text{ litros} $$

**Resposta:** Aproximadamente 2 litros (exato: 1,79 litros, arredondando para cima = 2 litros).

**9.** Uma estrela de 5 pontas (pentagrama) é inscrita num círculo de raio 10 cm. Cada ponta é um triângulo isósceles com base igual ao lado do pentágono regular inscrito. Determine a área da estrela (aproximada).

Raio = 10 cm. Lado do pentágono regular inscrito: $L = 2R\sin(36°) = 20 \cdot 0{,}588 \approx 11{,}76$ cm.

Apótema do pentágono: $a = R\cos(36°) = 10 \cdot 0{,}809 \approx 8{,}09$ cm.

Altura de cada ponta da estrela: $h = R - a = 10 - 8{,}09 = 1{,}91$ cm.

Área de uma ponta: $A_1 = \frac{11{,}76 \cdot 1{,}91}{2} \approx 11{,}23$ cm$^2$.
Área das 5 pontas: $5 \cdot 11{,}23 \approx 56{,}15$ cm$^2$.

Área do pentágono central: $A_{pent} = \frac{5 \cdot 11{,}76 \cdot 8{,}09}{2} \approx 237{,}8$ cm$^2$.

Área total da estrela = área das 5 pontas + área do pentágono.
Mas o pentagrama é mais complexo... Vamos simplificar: a estrela de 5 pontas é a união de 5 triângulos isósceles sobre um pentágono regular. A área da estrela é igual à área do pentágono convexo (o "buraco" da estrela) mais as 5 pontas.

Área do pentágono regular: $A = \frac{5 \cdot L^2}{4\tan(36°)} \approx \frac{5 \cdot 138{,}3}{2{,}91} \approx 237{,}6$ cm$^2$.

Área total da estrela $\approx 237{,}6 + 5 \cdot 11{,}23 \approx 293{,}75$ cm$^2$.

**Resposta:** Aproximadamente $294$ cm$^2$ (cálculo aproximado).

**10.** Uma piscina tem formato circular de raio 5 m, com uma borda retangular de concreto de 1 m de largura ao redor. Qual a área total (piscina + borda)?

Raio externo = $5 + 1 = 6$ m.
$$ A_{total} = \pi \cdot 6^2 = 36\pi \approx 113{,}10 \text{ m}^2 $$

**Resposta:** $36\pi$ m$^2$ $\approx 113{,}10$ m$^2$.

### Nível 3 — Desafio

**11.** Um terreno tem formato de um triângulo retângulo com catetos 30 m e 40 m. Nele há uma casa retangular $15 \times 10$ m e uma piscina circular de raio 5 m. Qual a área do terreno livre?

$$ A_{terreno} = \frac{30 \cdot 40}{2} = 600 \text{ m}^2 $$
$$ A_{casa} = 15 \cdot 10 = 150 \text{ m}^2 $$
$$ A_{piscina} = \pi \cdot 5^2 = 25\pi \approx 78{,}54 \text{ m}^2 $$
$$ A_{livre} = 600 - 150 - 25\pi = 450 - 25\pi \approx 371{,}46 \text{ m}^2 $$

**Resposta:** $450 - 25\pi$ m$^2$ $\approx 371{,}46$ m$^2$.

**12.** Uma chapa metálica quadrada de lado 20 cm tem 4 furos circulares de raio 2 cm, um em cada canto, com os centros a 4 cm de cada borda. Determine a área remanescente.

$$ A_{quadrado} = 20^2 = 400 \text{ cm}^2 $$
$$ A_{furos} = 4 \cdot \pi \cdot 2^2 = 16\pi \approx 50{,}27 \text{ cm}^2 $$
$$ A_{restante} = 400 - 16\pi \approx 349{,}73 \text{ cm}^2 $$

Verificação: os furos não se sobrepõem (distância entre centros = $20 - 8 = 12$ cm, diâmetro = 4 cm, $12 > 4$ ✓).

**Resposta:** $400 - 16\pi$ cm$^2$ $\approx 349{,}73$ cm$^2$.

**13.** Um campo de futebol tem dimensões $105 \times 68$ m. Na área central há um círculo de raio 9,15 m (círculo central). Nas extremidades há duas áreas semicirculares de raio 9,15 m (área do gol). Determine a área jogável fora dessas marcações circulares (considere apenas as áreas dentro do campo).

$$ A_{campo} = 105 \cdot 68 = 7140 \text{ m}^2 $$
$$ A_{círculo central} = \pi \cdot 9{,}15^2 \approx 263{,}02 \text{ m}^2 $$
$$ A_{semicírculos} = 2 \cdot \frac{\pi \cdot 9{,}15^2}{2} = \pi \cdot 9{,}15^2 \approx 263{,}02 \text{ m}^2 $$

$$ A_{fora} = 7140 - 263{,}02 - 263{,}02 = 7140 - 526{,}04 = 6613{,}96 \text{ m}^2 $$

**Resposta:** Aproximadamente $6614$ m$^2$ (sem contar outras marcações como área de pênalti, etc.).

---
**Fim — Áreas de Figuras Compostas e Aplicações**
