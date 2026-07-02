# Prismas e Cilindros

**Prismas** são poliedros com duas bases congruentes e paralelas, conectadas por faces laterais retangulares (prisma reto) ou paralelogramos (prisma oblíquo). **Cilindros** são os análogos não-poliedricos, com bases circulares e superfície lateral curva.

## Prismas

### Elementos

| Elemento | Definição |
|----------|-----------|
| **Bases** | Dois polígonos congruentes e paralelos |
| **Faces laterais** | Paralelogramos (retângulos em prismas retos) |
| **Arestas laterais** | Segmentos que unem vértices correspondentes das bases |
| **Altura** | Distância entre os planos das bases |

### Área Lateral

A área lateral é a soma das áreas das faces laterais.

**Prisma reto:**
$$ A_l = 2p \cdot h $$

Onde $2p$ é o perímetro da base e $h$ é a altura.

**General:**
$$ A_l = \text{soma das áreas das faces laterais} $$

### Área Total

$$ A_t = A_l + 2A_b $$

Onde $A_b$ é a área da base.

### Volume

$$ V = A_b \cdot h $$

> O volume de um prisma depende apenas da área da base e da altura, não da forma lateral.

## Prismas Especiais

### Prisma Triangular Reto

- Base: triângulo
- Área lateral: $A_l = (a + b + c) \cdot h$
- Volume: $V = A_b \cdot h = \frac{b \cdot H}{2} \cdot h$

### Prisma Quadrangular Reto (Paralelepípedo Retângulo)

- Base: retângulo
- Área lateral: $A_l = 2(a + b) \cdot h$
- Volume: $V = a \cdot b \cdot h$

### Cubo (Paralelepípedo Quadrado)

- Todas as faces são quadrados
- Área total: $A_t = 6a^2$
- Volume: $V = a^3$
- Diagonal: $d = a\sqrt{3}$

### Prisma Hexagonal Regular

- Base: hexágono regular
- Área da base: $A_b = \frac{3L^2\sqrt{3}}{2}$
- Área lateral: $A_l = 6L \cdot h$
- Volume: $V = \frac{3L^2\sqrt{3}}{2} \cdot h$

## Cilindros

### Cilindro Circular Reto

Superfície gerada pela rotação de um retângulo em torno de um de seus lados, ou por uma reta paralela a um eixo fixo, mantendo distância constante.

### Elementos

| Elemento | Definição | Fórmula |
|----------|-----------|---------|
| **Raio da base** | Raio do círculo de base | $r$ |
| **Altura** | Distância entre os planos das bases | $h$ |
| **Geratriz** | Segmento que gera a superfície lateral (geratriz = altura em cilindro reto) | $g = h$ |

### Área da Base

$$ A_b = \pi r^2 $$

### Área Lateral

Desenvolvendo a superfície lateral, obtemos um retângulo:
- Base do retângulo = comprimento da circunferência = $2\pi r$
- Altura do retângulo = altura do cilindro = $h$

$$ A_l = 2\pi r \cdot h $$

### Área Total

$$ A_t = 2\pi r^2 + 2\pi r h = 2\pi r(r + h) $$

### Volume

$$ V = \pi r^2 \cdot h $$

> O volume de um cilindro é igual ao de um prisma com a mesma área de base e mesma altura.

### Cilindro Equilátero

Cilindro cuja altura é igual ao diâmetro da base ($h = 2r$).

$$ A_t = 2\pi r^2 + 2\pi r(2r) = 6\pi r^2 $$
$$ V = \pi r^2(2r) = 2\pi r^3 $$

## Exemplos

### Exemplo 1: Prisma triangular

Um prisma triangular reto tem base com lados 3 cm, 4 cm, 5 cm e altura 10 cm. Determine sua área lateral, área total e volume.

$$ A_b = \frac{3 \cdot 4}{2} = 6 \text{ cm}^2 \quad \text{(triângulo retângulo)} $$
$$ 2p = 3 + 4 + 5 = 12 \text{ cm} $$
$$ A_l = 12 \cdot 10 = 120 \text{ cm}^2 $$
$$ A_t = 120 + 2 \cdot 6 = 132 \text{ cm}^2 $$
$$ V = 6 \cdot 10 = 60 \text{ cm}^3 $$

**Resposta:** $A_l = 120$ cm$^2$, $A_t = 132$ cm$^2$, $V = 60$ cm$^3$.

### Exemplo 2: Cilindro

Um cilindro circular reto tem raio 5 cm e altura 12 cm. Determine sua área lateral, área total e volume.

$$ A_l = 2\pi \cdot 5 \cdot 12 = 120\pi \approx 376{,}99 \text{ cm}^2 $$
$$ A_b = \pi \cdot 5^2 = 25\pi \text{ cm}^2 $$
$$ A_t = 120\pi + 2 \cdot 25\pi = 170\pi \approx 534{,}07 \text{ cm}^2 $$
$$ V = 25\pi \cdot 12 = 300\pi \approx 942{,}48 \text{ cm}^3 $$

**Resposta:** $A_l = 120\pi$ cm$^2$, $A_t = 170\pi$ cm$^2$, $V = 300\pi$ cm$^3$.

### Exemplo 3: Cilindro equilátero

Um cilindro equilátero tem raio 3 cm. Determine sua área total e volume.

$$ h = 2r = 6 \text{ cm} $$
$$ A_t = 6\pi \cdot 3^2 = 54\pi \approx 169{,}65 \text{ cm}^2 $$
$$ V = 2\pi \cdot 3^3 = 54\pi \approx 169{,}65 \text{ cm}^3 $$

**Resposta:** $A_t = 54\pi$ cm$^2$, $V = 54\pi$ cm$^3$ (coincidem numericamente!).

### Exemplo 4: Tanque cilíndrico

Um tanque cilíndrico tem raio 2 m e altura 5 m. Quantos litros de água ele armazena quando cheio? (1 m$^3$ = 1000 litros)

$$ V = \pi \cdot 2^2 \cdot 5 = 20\pi \approx 62{,}83 \text{ m}^3 $$
$$ \text{Litros} = 62{,}83 \cdot 1000 = 62.830 \text{ litros} $$

**Resposta:** $20\pi$ m$^3$ $\approx$ 62.830 litros.

## Aplicações na Vida Real

- **Engenharia:** tubos, canos, reservatórios, colunas, pilares
- **Arquitetura:** colunas cilíndricas, silos, tanques de armazenamento
- **Indústria:** rolos, tambores, bobinas, engrenagens cilíndricas
- **Embalagens:** latas, garrafas, tubos de pasta de dente, embalagens cilíndricas
- **Mecânica:** pistões, cilindros de motor, rolamentos, virabrequins
- **Agricultura:** silos, reservatórios de água, tanques de combustível
- **Construção:** vigas, pilares, tubulações, calhas
- **Design:** móveis, luminárias, vasos, objetos decorativos cilíndricos
- **Transporte:** tanques de caminhão, vagões-tanque, tubos de óleo
- **Medicina:** seringas, tubos de ensaio, cilindros de oxigênio

## Problemas

### Nível 1 — Básico

**1.** Um prisma quadrangular reto tem base de lado 5 cm e altura 8 cm. Determine sua área lateral, área total e volume.

$$ A_b = 5^2 = 25 \text{ cm}^2 $$
$$ 2p = 20 \text{ cm} $$
$$ A_l = 20 \cdot 8 = 160 \text{ cm}^2 $$
$$ A_t = 160 + 2 \cdot 25 = 210 \text{ cm}^2 $$
$$ V = 25 \cdot 8 = 200 \text{ cm}^3 $$

**Resposta:** $A_l = 160$ cm$^2$, $A_t = 210$ cm$^2$, $V = 200$ cm$^3$.

**2.** Um cilindro circular reto tem raio 4 cm e altura 10 cm. Determine sua área lateral e volume.

$$ A_l = 2\pi \cdot 4 \cdot 10 = 80\pi \approx 251{,}33 \text{ cm}^2 $$
$$ V = \pi \cdot 4^2 \cdot 10 = 160\pi \approx 502{,}65 \text{ cm}^3 $$

**Resposta:** $A_l = 80\pi$ cm$^2$; $V = 160\pi$ cm$^3$.

**3.** Um cubo tem aresta 3 cm. Determine sua área total e volume.

$$ A_t = 6 \cdot 3^2 = 54 \text{ cm}^2 $$
$$ V = 3^3 = 27 \text{ cm}^3 $$

**Resposta:** $A_t = 54$ cm$^2$; $V = 27$ cm$^3$.

**4.** Um prisma hexagonal regular tem lado da base 4 cm e altura 6 cm. Determine sua área lateral.

$$ A_l = 6 \cdot 4 \cdot 6 = 144 \text{ cm}^2 $$

**Resposta:** $144$ cm$^2$.

**5.** Um cilindro tem volume $500\pi$ cm$^3$ e raio 5 cm. Determine sua altura.

$$ \pi \cdot 5^2 \cdot h = 500\pi \implies 25h = 500 \implies h = 20 \text{ cm} $$

**Resposta:** 20 cm.

### Nível 2 — Intermediário

**6.** Uma caixa d'água tem formato de prisma quadrangular reto com base de 2 m por 2 m e altura 3 m. Quantos litros de água ela armazena quando cheia? (1 m$^3$ = 1000 L)

$$ V = 2 \cdot 2 \cdot 3 = 12 \text{ m}^3 = 12.000 \text{ litros} $$

**Resposta:** 12.000 litros.

**7.** Um cilindro equilátero tem área total $24\pi$ cm$^2$. Determine seu raio e volume.

$$ A_t = 6\pi r^2 = 24\pi \implies r^2 = 4 \implies r = 2 \text{ cm} $$
$$ h = 2r = 4 \text{ cm} $$
$$ V = 2\pi r^3 = 2\pi \cdot 8 = 16\pi \text{ cm}^3 $$

**Resposta:** Raio = 2 cm; Volume = $16\pi$ cm$^3$.

**8.** Um prisma triangular reto tem altura 15 cm e volume 270 cm$^3$. Se a base é um triângulo retângulo com catetos na razão 3:4, determine os catetos e a hipotenusa da base.

$$ A_b = \frac{V}{h} = \frac{270}{15} = 18 \text{ cm}^2 $$

Seja os catetos $3x$ e $4x$:
$$ \frac{3x \cdot 4x}{2} = 18 \implies 6x^2 = 18 \implies x^2 = 3 \implies x = \sqrt{3} $$

$$ \text{Catetos: } 3\sqrt{3} \text{ cm e } 4\sqrt{3} \text{ cm} $$
$$ \text{Hipotenusa: } \sqrt{(3\sqrt{3})^2 + (4\sqrt{3})^2} = \sqrt{27 + 48} = \sqrt{75} = 5\sqrt{3} \text{ cm} $$

**Resposta:** Catetos: $3\sqrt{3}$ cm e $4\sqrt{3}$ cm; Hipotenusa: $5\sqrt{3}$ cm.

**9.** Um tanque cilíndrico horizontal (como um barril deitado) tem raio 1 m e comprimento 3 m. Se está cheio até a metade, quantos litros de água contém? (Dica: a área do segmento circular para metade do círculo é metade da área do círculo.)

$$ V = A_{segmento} \cdot \text{comprimento} = \frac{\pi r^2}{2} \cdot L = \frac{\pi \cdot 1}{2} \cdot 3 = \frac{3\pi}{2} \text{ m}^3 $$

$$ \text{Litros} = \frac{3\pi}{2} \cdot 1000 \approx 4712 \text{ litros} $$

**Resposta:** $\frac{3\pi}{2}$ m$^3$ $\approx$ 4.712 litros.

**10.** Um prisma hexagonal regular tem área total $72\sqrt{3}$ cm$^2$ e altura 5 cm. Determine o lado da base.

$$ A_b = \frac{3L^2\sqrt{3}}{2} $$
$$ A_l = 6L \cdot 5 = 30L $$
$$ A_t = 2 \cdot \frac{3L^2\sqrt{3}}{2} + 30L = 3L^2\sqrt{3} + 30L = 72\sqrt{3} $$

$$ 3L^2\sqrt{3} + 30L - 72\sqrt{3} = 0 $$
Dividindo por 3:
$$ L^2\sqrt{3} + 10L - 24\sqrt{3} = 0 $$

Usando a fórmula de Bháskara:
$$ L = \frac{-10 + \sqrt{100 + 4 \cdot \sqrt{3} \cdot 24\sqrt{3}}}{2\sqrt{3}} = \frac{-10 + \sqrt{100 + 288}}{2\sqrt{3}} = \frac{-10 + \sqrt{388}}{2\sqrt{3}} $$

Hmm, isso está ficando complexo. Vamos tentar $L = 2\sqrt{3}$:
$$ 3(2\sqrt{3})^2\sqrt{3} + 30(2\sqrt{3}) = 3 \cdot 12 \cdot \sqrt{3} + 60\sqrt{3} = 36\sqrt{3} + 60\sqrt{3} = 96\sqrt{3} \neq 72\sqrt{3} $$

Tentando $L = 2$:
$$ 3 \cdot 4 \cdot \sqrt{3} + 60 = 12\sqrt{3} + 60 \neq 72\sqrt{3} $$

Tentando $L = 2\sqrt{3}$ deu $96\sqrt{3}$. Vamos resolver numericamente: $3\sqrt{3}L^2 + 30L - 72\sqrt{3} = 0$.

Aproximando $\sqrt{3} \approx 1{,}732$:
$$ 5{,}196L^2 + 30L - 124{,}7 = 0 $$
$$ L = \frac{-30 + \sqrt{900 + 4 \cdot 5{,}196 \cdot 124{,}7}}{2 \cdot 5{,}196} = \frac{-30 + \sqrt{900 + 2591}}{10{,}392} = \frac{-30 + 59{,}1}{10{,}392} \approx 2{,}80 $$

Vamos tentar $L = 2\sqrt{3}$ com cálculo exato: $A_t = 3L^2\sqrt{3} + 30L$.
Se $A_t = 72\sqrt{3}$: $3L^2\sqrt{3} + 30L = 72\sqrt{3}$.

Tentando $L = 2\sqrt{3}$: $3 \cdot 12 \cdot \sqrt{3} + 60\sqrt{3} = 96\sqrt{3}$ (muito alto).
Tentando $L = \sqrt{3}$: $3 \cdot 3 \cdot \sqrt{3} + 30\sqrt{3} = 39\sqrt{3}$ (muito baixo).

A resposta está entre $\sqrt{3}$ e $2\sqrt{3}$. Vamos resolver exatamente:

$$ L = \frac{-30 + \sqrt{900 + 288\sqrt{3} \cdot \sqrt{3}}}{2\sqrt{3}} = \frac{-30 + \sqrt{900 + 864}}{2\sqrt{3}} = \frac{-30 + \sqrt{1764}}{2\sqrt{3}} = \frac{-30 + 42}{2\sqrt{3}} = \frac{12}{2\sqrt{3}} = \frac{6}{\sqrt{3}} = 2\sqrt{3} $$

Hmm, isso dá $L = 2\sqrt{3}$, mas vimos que $A_t = 96\sqrt{3}$. Verificando o discriminante: $b^2 - 4ac = 900 - 4(3\sqrt{3})(-72\sqrt{3}) = 900 + 864 \cdot 3 = 900 + 2592 = 3492$.

$\sqrt{3492} = \sqrt{4 \cdot 873} = 2\sqrt{873} = 2\sqrt{9 \cdot 97} = 6\sqrt{97}$. Não é 42.

Vamos refazer: $a = 3\sqrt{3}$, $b = 30$, $c = -72\sqrt{3}$.
$$ \Delta = 900 - 4(3\sqrt{3})(-72\sqrt{3}) = 900 + 864 \cdot 3 = 900 + 2592 = 3492 $$
$$ \sqrt{3492} \approx 59{,}1 $$
$$ L = \frac{-30 + 59{,}1}{6\sqrt{3}} \approx \frac{29{,}1}{10{,}39} \approx 2{,}80 $$

**Resposta:** Aproximadamente $L \approx 2{,}8$ cm (ou $L = \frac{-30 + 6\sqrt{97}}{6\sqrt{3}}$ cm exato).

### Nível 3 — Desafio

**11.** Um cilindro circular reto e um prisma quadrangular reto têm a mesma altura $h$ e o mesmo volume. Se o raio do cilindro é $r$, determine o lado da base do prisma.

$$ V_{cilindro} = V_{prisma} $$
$$ \pi r^2 h = L^2 h $$
$$ L^2 = \pi r^2 $$
$$ L = r\sqrt{\pi} $$

**Resposta:** $L = r\sqrt{\pi}$.

**12.** Um reservatório cilíndrico vertical tem raio 3 m e altura 8 m. Inicialmente vazio, é preenchido a uma taxa de 2 m$^3$/min. Em quanto tempo (em horas) estará cheio? Quando a água atinge 4 m de altura, qual a área da superfície molhada (inclui fundo + parede lateral molhada)?

**Tempo para encher:**
$$ V = \pi \cdot 3^2 \cdot 8 = 72\pi \approx 226{,}19 \text{ m}^3 $$
$$ \text{Tempo} = \frac{72\pi}{2} = 36\pi \text{ min} \approx 113{,}10 \text{ min} \approx 1{,}89 \text{ h} $$

**Superfície molhada quando h = 4 m:**
$$ A_{fundo} = \pi \cdot 3^2 = 9\pi \text{ m}^2 $$
$$ A_{lateral molhada} = 2\pi \cdot 3 \cdot 4 = 24\pi \text{ m}^2 $$
$$ A_{total molhada} = 9\pi + 24\pi = 33\pi \approx 103{,}67 \text{ m}^2 $$

**Resposta:** Tempo = $36\pi$ min $\approx 1{,}89$ h. Superfície molhada = $33\pi$ m$^2$ $\approx 103{,}67$ m$^2$.

**13.** Um cubo é inscrito num cilindro equilâtero (as bases do cubo estão nas bases do cilindro, e os vértices do cubo tocam a superfície lateral do cilindro). Se o cilindro tem raio $R$, determine a aresta do cubo e a razão entre os volumes do cilindro e do cubo.

No cilindro equilátero: $h = 2R$.
O cubo inscrito tem altura igual à do cilindro: $a = h = 2R$? Não, porque a base do cubo deve ser um quadrado inscrito na base circular do cilindro.

Se a base do cubo é um quadrado inscrito no círculo de raio $R$:
$$ a\sqrt{2} = 2R \implies a = R\sqrt{2} $$

Altura do cubo = aresta da base (pois é um cubo) = $R\sqrt{2}$.
Mas o cilindro tem altura $2R$. Para que o cubo caiba: $R\sqrt{2} \leq 2R$ ✓ (pois $\sqrt{2} \approx 1{,}41 < 2$).

$$ V_{cub} = (R\sqrt{2})^3 = 2R^3\sqrt{2} $$
$$ V_{cilindro} = \pi R^2 \cdot 2R = 2\pi R^3 $$
$$ \text{Razão} = \frac{V_{cilindro}}{V_{cub}} = \frac{2\pi R^3}{2R^3\sqrt{2}} = \frac{\pi}{\sqrt{2}} = \frac{\pi\sqrt{2}}{2} \approx 2{,}22 $$

**Resposta:** Aresta = $R\sqrt{2}$. Razão = $\frac{\pi\sqrt{2}}{2} \approx 2{,}22$.

---
**Fim — Prismas e Cilindros**
