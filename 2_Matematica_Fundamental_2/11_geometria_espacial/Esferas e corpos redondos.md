# Esferas e Corpos Redondos

A **esfera** é o sólido geométrico mais perfeito e simétrico — o conjunto de todos os pontos do espaço equidistantes de um ponto fixo (centro). É a forma das bolas, planetas, gotas de água, bolhas de sabão e incontáveis fenômenos naturais. Juntamente com cilindros e cones, forma a família dos **corpos redondos**.

## Esfera

### Elementos

| Elemento | Definição | Notação |
|----------|-----------|---------|
| **Raio** | Distância do centro a qualquer ponto da superfície | $r$ ou $R$ |
| **Diâmetro** | Segmento que passa pelo centro, ligando dois pontos | $d = 2r$ |
| **Superfície** | Conjunto de todos os pontos a distância $r$ do centro | |
| **Semiesfera** | Metade da esfera, cortada por um plano que passa pelo centro | |

### Área da Superfície Esférica

$$ A = 4\pi r^2 $$

**Demonstração:**
Pode ser demonstrada por métodos de cálculo (integração) ou pelo método de Arquimedes: a área da superfície esférica é igual à área lateral de um cilindro circunscrito de altura $2r$, ou seja, $2\pi r \cdot 2r = 4\pi r^2$.

### Volume da Esfera

$$ V = \frac{4}{3} \pi r^3 $$

**Demonstração:**
Pode ser demonstrada por integração ou pelo método de Cavalieri: a esfera pode ser "decomposta" em infinitas pirâmides com vértice no centro e bases na superfície. Como $V = \frac{1}{3} A_{base} \cdot h$ para pirâmides, e a soma das áreas das bases é a área da esfera ($4\pi r^2$), e a altura média é $r$:
$$ V = \frac{1}{3} \cdot 4\pi r^2 \cdot r = \frac{4}{3}\pi r^3 $$

### Semiesfera

**Área da superfície:**
$$ A = 2\pi r^2 + \pi r^2 = 3\pi r^2 $$
(Inclui a metade da superfície esférica + a base circular)

**Volume:**
$$ V = \frac{2}{3} \pi r^3 $$

## Fusos e Cunhas Esféricas

### Fuso Esférico

Região da superfície esférica limitada por dois semicírculos máximos (como fatias de laranja).

$$ A_{fuso} = \frac{\alpha}{360°} \cdot 4\pi r^2 $$

Onde $\alpha$ é o ângulo do fuso em graus.

### Cunha Esférica

Região do volume da esfera limitada por dois semicírculos máximos (como uma fatia de melão).

$$ V_{cunha} = \frac{\alpha}{360°} \cdot \frac{4}{3}\pi r^3 $$

## Calota Esférica e Segmento Esférico

### Calota Esférica

Parte da superfície esférica cortada por um plano.

$$ A_{calota} = 2\pi r h $$

Onde $h$ é a altura da calota (distância do plano ao "polo" da calota).

> **Nota:** A área da calota depende apenas de $r$ e $h$, não do raio do corte!

### Segmento Esférico (de uma base)

Parte da esfera limitada por um plano (calota + base circular).

$$ V_{segmento} = \frac{\pi h}{6}(3a^2 + h^2) $$

Onde $a$ é o raio do corte e $h$ é a altura do segmento.

Alternativamente:
$$ V_{segmento} = \frac{\pi h^2}{3}(3r - h) $$

## Esfera Inscrita e Circunscrita

### Esfera Inscrita em Cubo

- Raio da esfera inscrita: $r = a/2$ (metade da aresta)
- A esfera tangencia todas as faces do cubo

### Esfera Circunscrita ao Cubo

- Raio da esfera circunscrita: $R = a\sqrt{3}/2$ (metade da diagonal do cubo)
- A esfera passa por todos os vértices do cubo

### Cubo Inscrito em Esfera

- Aresta do cubo: $a = 2R/\sqrt{3} = 2R\sqrt{3}/3$

## Exemplos

### Exemplo 1: Esfera básica

Uma esfera tem raio 6 cm. Determine sua área superficial e seu volume.

$$ A = 4\pi \cdot 6^2 = 144\pi \approx 452{,}39 \text{ cm}^2 $$
$$ V = \frac{4}{3}\pi \cdot 6^3 = \frac{4}{3}\pi \cdot 216 = 288\pi \approx 904{,}78 \text{ cm}^3 $$

**Resposta:** $A = 144\pi$ cm$^2$; $V = 288\pi$ cm$^3$.

### Exemplo 2: Semiesfera

Uma semiesfera tem raio 5 m. Determine sua área total e volume.

$$ A = 3\pi \cdot 5^2 = 75\pi \approx 235{,}62 \text{ m}^2 $$
$$ V = \frac{2}{3}\pi \cdot 5^3 = \frac{250\pi}{3} \approx 261{,}80 \text{ m}^3 $$

**Resposta:** $A = 75\pi$ m$^2$; $V = \frac{250\pi}{3}$ m$^3$.

### Exemplo 3: Esfera inscrita e circunscrita ao cubo

Um cubo tem aresta 4 cm. Determine os raios das esferas inscrita e circunscrita, e as razões entre seus volumes.

**Inscrita:** $r = 4/2 = 2$ cm
$$ V_{insc} = \frac{4}{3}\pi \cdot 8 = \frac{32\pi}{3} \text{ cm}^3 $$

**Circunscrita:** $R = 4\sqrt{3}/2 = 2\sqrt{3}$ cm
$$ V_{circ} = \frac{4}{3}\pi \cdot (2\sqrt{3})^3 = \frac{4}{3}\pi \cdot 24\sqrt{3} = 32\pi\sqrt{3} \text{ cm}^3 $$

**Razão:**
$$ \frac{V_{circ}}{V_{insc}} = \frac{32\pi\sqrt{3}}{32\pi/3} = 3\sqrt{3} \approx 5{,}20 $$

**Resposta:** $r = 2$ cm, $R = 2\sqrt{3}$ cm. Razão dos volumes = $3\sqrt{3}$.

### Exemplo 4: Calota esférica

Uma calota esférica tem raio de esfera 10 cm e altura 2 cm. Determine sua área.

$$ A_{calota} = 2\pi \cdot 10 \cdot 2 = 40\pi \approx 125{,}66 \text{ cm}^2 $$

**Resposta:** $40\pi$ cm$^2$ $\approx 125{,}66$ cm$^2$.

### Exemplo 5: Segmento esférico

Um segmento esférico de uma base tem raio da esfera 5 cm e altura 2 cm. Determine seu volume.

$$ V = \frac{\pi \cdot 2^2}{3}(3 \cdot 5 - 2) = \frac{4\pi}{3} \cdot 13 = \frac{52\pi}{3} \approx 54{,}45 \text{ cm}^3 $$

**Resposta:** $\frac{52\pi}{3}$ cm$^3$ $\approx 54{,}45$ cm$^3$.

## Aplicações na Vida Real

- **Astronomia:** planetas, estrelas, lua, sol (aproximadamente esféricos)
- **Física:** campos gravitacionais e elétricos de simetria esférica
- **Esportes:** bolas de futebol, basquete, tênis, golfe, bilhar
- **Biologia:** células, ovos, gotas de água, bolhas de sabão
- **Indústria:** rolamentos de esferas, válvulas de esfera, mancais
- **Geologia:** pérolas, granadas, depósitos minerais esféricos
- **Medicina:** globos oculares, articulações (cabeça do fêmur), próteses
- **Engenharia:** tanques esféricos de armazenamento, antenas parabólicas
- **Navegação:** globo terrestre, mapas projetados de esferas
- **Jogos:** bolas de cristal, orbes, esferas de energia, planetas em jogos espaciais

## Problemas

### Nível 1 — Básico

**1.** Uma esfera tem raio 3 cm. Determine sua área superficial e volume.

$$ A = 4\pi \cdot 9 = 36\pi \approx 113{,}10 \text{ cm}^2 $$
$$ V = \frac{4}{3}\pi \cdot 27 = 36\pi \approx 113{,}10 \text{ cm}^3 $$

**Resposta:** $A = 36\pi$ cm$^2$; $V = 36\pi$ cm$^3$ (coincidem!).

**2.** Uma semiesfera tem raio 4 m. Determine sua área total e volume.

$$ A = 3\pi \cdot 16 = 48\pi \approx 150{,}80 \text{ m}^2 $$
$$ V = \frac{2}{3}\pi \cdot 64 = \frac{128\pi}{3} \approx 134{,}04 \text{ m}^3 $$

**Resposta:** $A = 48\pi$ m$^2$; $V = \frac{128\pi}{3}$ m$^3$.

**3.** Uma esfera tem volume $36\pi$ cm$^3$. Determine seu raio e área.

$$ \frac{4}{3}\pi r^3 = 36\pi \implies r^3 = 27 \implies r = 3 \text{ cm} $$
$$ A = 4\pi \cdot 9 = 36\pi \text{ cm}^2 $$

**Resposta:** Raio = 3 cm; $A = 36\pi$ cm$^2$.

**4.** Uma esfera tem área $64\pi$ cm$^2$. Determine seu raio e volume.

$$ 4\pi r^2 = 64\pi \implies r^2 = 16 \implies r = 4 \text{ cm} $$
$$ V = \frac{4}{3}\pi \cdot 64 = \frac{256\pi}{3} \approx 268{,}08 \text{ cm}^3 $$

**Resposta:** Raio = 4 cm; $V = \frac{256\pi}{3}$ cm$^3$.

**5.** Um fuso esférico de ângulo $60°$ tem raio 9 cm. Determine sua área.

$$ A_{fuso} = \frac{60°}{360°} \cdot 4\pi \cdot 81 = \frac{1}{6} \cdot 324\pi = 54\pi \approx 169{,}65 \text{ cm}^2 $$

**Resposta:** $54\pi$ cm$^2$ $\approx 169{,}65$ cm$^2$.

### Nível 2 — Intermediário

**6.** Uma esfera está inscrita num cilindro equilátero (a esfera tangencia as bases e a superfície lateral). Se o raio da esfera é 5 cm, determine a altura do cilindro, sua área total e volume. Qual a razão entre os volumes?

**Cilindro equilátero:** $h = 2r = 10$ cm.

O raio da esfera inscrita é igual ao raio do cilindro: $r = 5$ cm.

$$ A_{cil} = 6\pi \cdot 25 = 150\pi \text{ cm}^2 $$
$$ V_{cil} = 2\pi \cdot 125 = 250\pi \text{ cm}^3 $$
$$ V_{esf} = \frac{4}{3}\pi \cdot 125 = \frac{500\pi}{3} \text{ cm}^3 $$

$$ \text{Razão} = \frac{V_{cil}}{V_{esf}} = \frac{250\pi}{500\pi/3} = \frac{250 \cdot 3}{500} = \frac{3}{2} = 1{,}5 $$

**Resposta:** Altura = 10 cm; $A_{cil} = 150\pi$ cm$^2$; $V_{cil} = 250\pi$ cm$^3$; Razão = 1,5.

**7.** Uma esfera de raio 6 cm é cortada por um plano a 2 cm do centro. Determine a área da calota e a área do círculo de corte.

Altura da calota: $h = 6 - 2 = 4$ cm.

$$ A_{calota} = 2\pi \cdot 6 \cdot 4 = 48\pi \approx 150{,}80 \text{ cm}^2 $$

Raio do círculo de corte: $a = \sqrt{6^2 - 2^2} = \sqrt{36 - 4} = \sqrt{32} = 4\sqrt{2}$ cm.
$$ A_{corte} = \pi \cdot 32 = 32\pi \approx 100{,}53 \text{ cm}^2 $$

**Resposta:** Calota = $48\pi$ cm$^2$; Círculo de corte = $32\pi$ cm$^2$.

**8.** Uma esfera de raio 10 cm e um cubo têm o mesmo volume. Determine a aresta do cubo e a razão entre a área da esfera e a área total do cubo.

$$ V_{esf} = \frac{4}{3}\pi \cdot 1000 = \frac{4000\pi}{3} \approx 4188{,}79 \text{ cm}^3 $$

$$ a^3 = \frac{4000\pi}{3} \implies a = \sqrt[3]{\frac{4000\pi}{3}} \approx \sqrt[3]{4188{,}79} \approx 16{,}12 \text{ cm} $$

$$ A_{cub} = 6a^2 \approx 6 \cdot 259{,}85 \approx 1559{,}1 \text{ cm}^2 $$
$$ A_{esf} = 4\pi \cdot 100 = 400\pi \approx 1256{,}64 \text{ cm}^2 $$

$$ \text{Razão} = \frac{A_{esf}}{A_{cub}} \approx \frac{1256{,}64}{1559{,}1} \approx 0{,}806 $$

**Resposta:** Aresta $\approx 16{,}12$ cm; Razão $\approx 0{,}81$ (a esfera tem menor área para o mesmo volume — é a forma mais eficiente).

**9.** Um planeta tem raio aproximado de 6.371 km. Determine sua área superficial aproximada.

$$ A = 4\pi \cdot (6.371)^2 = 4\pi \cdot 40.589.641 \approx 510.064.472 \text{ km}^2 $$

$$ A \approx 5,1 \cdot 10^8 \text{ km}^2 = 510 \text{ milhões de km}^2 $$

**Resposta:** Aproximadamente 510 milhões de km$^2$ (área real da Terra ≈ 510 milhões de km$^2$).

**10.** Uma calota esférica tem área $40\pi$ cm$^2$ e a esfera tem raio 10 cm. Determine a altura da calota e o volume do segmento esférico correspondente.

$$ A_{calota} = 2\pi r h = 40\pi $$
$$ 2\pi \cdot 10 \cdot h = 40\pi \implies h = 2 \text{ cm} $$

$$ V_{segmento} = \frac{\pi \cdot 2^2}{3}(3 \cdot 10 - 2) = \frac{4\pi}{3} \cdot 28 = \frac{112\pi}{3} \approx 117{,}29 \text{ cm}^3 $$

**Resposta:** Altura = 2 cm; Volume = $\frac{112\pi}{3}$ cm$^3$.

### Nível 3 — Desafio

**11.** Prove que entre todos os sólidos com mesmo volume, a esfera é o que tem menor área superficial (princípio da isoperimetria em 3D). Aplique isso para justificar por que bolhas de sabão são esféricas e por que planetas tendem a ser esféricos.

A **isoperimetria** em 3D diz que para um volume fixo, a esfera minimiza a área superficial. Isso é demonstrado usando cálculo variacional (inequação isoperimétrica).

**Aplicações:**
- **Bolhas de sabão:** a tensão superficial minimiza a área da superfície, e como o volume de ar dentro é fixo, a forma esférica é a de menor energia superficial.
- **Planetas:** a gravidade atua como uma "tensão superficial gravitacional", puxando a massa para o centro e minimizando a energia potencial gravitacional, resultando em uma forma esférica (ou esferoide para corpos em rotação rápida).

**Resposta:** A esfera minimiza a área para volume dado (isoperimetria). Bolhas de sabão e planetas seguem esse princípio de minimização de energia.

**12.** Uma esfera de raio $R$ e um cone equilátero têm o mesmo volume. Determine a razão entre as áreas totais da esfera e do cone.

$$ V_{esf} = V_{cone} $$
$$ \frac{4}{3}\pi R^3 = \frac{\pi r^3 \sqrt{3}}{3} $$
$$ 4R^3 = r^3\sqrt{3} \implies r^3 = \frac{4R^3}{\sqrt{3}} = \frac{4R^3\sqrt{3}}{3} $$
$$ r = R \cdot \sqrt[3]{\frac{4\sqrt{3}}{3}} = R \cdot \sqrt[3]{\frac{4}{\sqrt{3}}} $$

$$ A_{esf} = 4\pi R^2 $$
$$ A_{cone} = 3\pi r^2 = 3\pi R^2 \left(\frac{4\sqrt{3}}{3}\right)^{2/3} $$

$$ \text{Razão} = \frac{4\pi R^2}{3\pi R^2 \left(\frac{4\sqrt{3}}{3}\right)^{2/3}} = \frac{4}{3\left(\frac{4\sqrt{3}}{3}\right)^{2/3}} $$

$$ = \frac{4}{3} \cdot \left(\frac{3}{4\sqrt{3}}\right)^{2/3} = \frac{4}{3} \cdot \left(\frac{3^{1/2}}{4}\right)^{2/3} = \frac{4}{3} \cdot \frac{3^{1/3}}{4^{2/3}} = \frac{4^{1/3} \cdot 3^{1/3}}{3} = \frac{(12)^{1/3}}{3} $$

Aproximando: $\frac{2{,}289}{3} \approx 0{,}763$.

**Resposta:** Razão = $\frac{4}{3} \cdot \left(\frac{3}{4\sqrt{3}}\right)^{2/3} \approx 0{,}76$ (a esfera tem menor área para mesmo volume).

**13.** (Problema de Arquimedes) Uma esfera está inscrita num cilindro reto (a esfera tangencia as bases e a superfície lateral). Arquimedes provou que a razão entre os volumes do cilindro e da esfera é $3/2$, e a razão entre as áreas também é $3/2$. Verifique isso para uma esfera de raio $r$.

**Cilindro circunscrito:** raio $r$, altura $2r$.

$$ V_{cil} = \pi r^2 \cdot 2r = 2\pi r^3 $$
$$ V_{esf} = \frac{4}{3}\pi r^3 $$
$$ \frac{V_{cil}}{V_{esf}} = \frac{2\pi r^3}{4\pi r^3/3} = \frac{2 \cdot 3}{4} = \frac{3}{2} $$

$$ A_{cil} = 2\pi r^2 + 2\pi r \cdot 2r = 2\pi r^2 + 4\pi r^2 = 6\pi r^2 $$
$$ A_{esf} = 4\pi r^2 $$
$$ \frac{A_{cil}}{A_{esf}} = \frac{6\pi r^2}{4\pi r^2} = \frac{3}{2} $$

**Resposta:** Verificado: razão dos volumes = 3/2, razão das áreas = 3/2. Arquimedes considerou esta uma de suas maiores conquistas e pediu que uma esfera inscrita num cilindro fosse gravada em sua lápide.

---
**Fim — Esferas e Corpos Redondos**
