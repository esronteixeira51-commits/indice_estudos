# Círculo e Circunferência

A **circunferência** é o conjunto de todos os pontos de um plano equidistantes de um ponto fixo (centro). O **círculo** é a região do plano limitada pela circunferência. O círculo é uma das figuras mais perfeitas da geometria, aparecendo em rodas, planetas, ondas, células e incontáveis fenômenos naturais.

## Elementos do Círculo

| Elemento | Definição | Notação |
|----------|-----------|---------|
| **Raio** | Segmento do centro a qualquer ponto da circunferência | $r$ ou $R$ |
| **Diâmetro** | Segmento que passa pelo centro, ligando dois pontos da circunferência | $d = 2r$ |
| **Corda** | Segmento ligando dois pontos da circunferência | |
| **Arco** | Parte da circunferência entre dois pontos | medido em graus ou radianos |
| **Setor** | Região limitada por dois raios e um arco | |
| **Segmento** | Região limitada por uma corda e um arco | |
| **Semicírculo** | Metade do círculo, limitado por um diâmetro | |

## Comprimento da Circunferência

$$ C = 2\pi r = \pi d $$

Onde $\pi \approx 3{,}14159...$ é a razão entre o comprimento da circunferência e o diâmetro (constante para todos os círculos).

## Área do Círculo

$$ A = \pi r^2 $$

**Demonstração informal:**
Divida o círculo em muitos setores e rearranje-os formando um paralelogramo aproximado:
- Base $\approx \pi r$ (metade da circunferência)
- Altura $\approx r$
- Área $\approx \pi r \cdot r = \pi r^2$

## Arcos e Ângulos

### Arco de Circunferência

O comprimento de um arco que subtende um ângulo central $\theta$ (em radianos):

$$ \ell = r \cdot \theta $$

Se $\theta$ estiver em graus:
$$ \ell = \frac{\pi r \theta}{180°} = \frac{2\pi r \cdot \theta}{360°} $$

### Ângulo Central vs Inscrito

- **Ângulo central:** vértice no centro. Mede igual ao arco correspondente.
- **Ângulo inscrito:** vértice na circunferência. Mede a metade do arco correspondente.

$$ \text{Ângulo inscrito} = \frac{1}{2} \cdot \text{Ângulo central} = \frac{1}{2} \cdot \text{Arco} $$

### Ângulo na Semicircunferência

Todo ângulo inscrito que subtende um diâmetro é um **ângulo reto** ($90°$).

$$ \text{Ângulo inscrito em semicírculo} = 90° $$

## Área do Setor Circular

$$ A_{setor} = \frac{\theta}{360°} \cdot \pi r^2 = \frac{\theta \cdot r^2}{2} \quad \text{(se } \theta \text{ em radianos)} $$

## Área do Segmento Circular

$$ A_{segmento} = A_{setor} - A_{triângulo} $$

$$ A_{segmento} = \frac{r^2}{2}(\theta - \sin\theta) \quad \text{(se } \theta \text{ em radianos)} $$

## Comprimento da Corda

$$ c = 2r \cdot \sin\left(\frac{\theta}{2}\right) $$

Onde $\theta$ é o ângulo central (em radianos) subtendido pela corda.

## Ângulo Externo e Interno

- **Ângulo externo** (formado por duas tangentes): $180° - \text{arco menor}$
- **Ângulo interno** (formado por duas cordas): $\frac{\text{arco}_1 + \text{arco}_2}{2}$
- **Ângulo de secantes** (fora do círculo): $\frac{\text{arco maior} - \text{arco menor}}{2}$

## Exemplos

### Exemplo 1: Comprimento e área

Um círculo tem raio 5 cm. Determine o comprimento da circunferência e a área.

$$ C = 2\pi \cdot 5 = 10\pi \approx 31{,}42 \text{ cm} $$
$$ A = \pi \cdot 5^2 = 25\pi \approx 78{,}54 \text{ cm}^2 $$

**Resposta:** $C = 10\pi$ cm $\approx 31{,}42$ cm; $A = 25\pi$ cm$^2$ $\approx 78{,}54$ cm$^2$.

### Exemplo 2: Arco e setor

Determine o comprimento do arco e a área do setor de um círculo de raio 8 cm, com ângulo central $45°$.

$$ \ell = \frac{2\pi \cdot 8 \cdot 45°}{360°} = \frac{16\pi \cdot 45}{360} = \frac{16\pi}{8} = 2\pi \approx 6{,}28 \text{ cm} $$

$$ A_{setor} = \frac{45°}{360°} \cdot \pi \cdot 8^2 = \frac{1}{8} \cdot 64\pi = 8\pi \approx 25{,}13 \text{ cm}^2 $$

**Resposta:** Arco = $2\pi$ cm $\approx 6{,}28$ cm; Setor = $8\pi$ cm$^2$ $\approx 25{,}13$ cm$^2$.

### Exemplo 3: Ângulo inscrito

Um ângulo inscrito subtende um arco de $120°$. Quanto mede o ângulo inscrito?

$$ \text{Ângulo inscrito} = \frac{120°}{2} = 60° $$

**Resposta:** $60°$.

### Exemplo 4: Área do segmento

Determine a área do segmento circular de um círculo de raio 6 cm, com ângulo central $60°$ ($= \pi/3$ rad).

$$ A_{setor} = \frac{60°}{360°} \cdot \pi \cdot 6^2 = \frac{1}{6} \cdot 36\pi = 6\pi \text{ cm}^2 $$

$$ A_{triângulo} = \frac{1}{2} \cdot r^2 \cdot \sin(60°) = \frac{1}{2} \cdot 36 \cdot \frac{\sqrt{3}}{2} = 9\sqrt{3} \text{ cm}^2 $$

$$ A_{segmento} = 6\pi - 9\sqrt{3} \approx 18{,}85 - 15{,}59 = 3{,}26 \text{ cm}^2 $$

**Resposta:** $6\pi - 9\sqrt{3}$ cm$^2$ $\approx 3{,}26$ cm$^2$.

## Aplicações na Vida Real

- **Engenharia:** rodas, engrenagens, tubos, canos, pistões
- **Arquitetura:** cúpulas, abóbadas, janelas redondas (óculos), rosáceas
- **Astronomia:** órbitas (aproximadamente circulares), discos de planetas, anéis de Saturno
- **Navegação:** radar, alcance de antenas, áreas de cobertura
- **Biologia:** células, gotas de água, olhos, seções de troncos
- **Física:** movimento circular, campos centrados, ondas circulares
- **Design:** logotipos, botões, ícones, interface de usuário
- **Agricultura:** pivôs centrais de irrigação (círculos perfeitos)
- **Música:** bocais de instrumentos de sopro, caixas de ressonância
- **Jogos:** campos de visão circulares, áreas de efeito (AOE), hitboxes circulares

## Problemas

### Nível 1 — Básico

**1.** Um círculo tem raio 4 cm. Determine o comprimento da circunferência e a área.

$$ C = 2\pi \cdot 4 = 8\pi \approx 25{,}13 \text{ cm} $$
$$ A = \pi \cdot 4^2 = 16\pi \approx 50{,}27 \text{ cm}^2 $$

**Resposta:** $C = 8\pi$ cm $\approx 25{,}13$ cm; $A = 16\pi$ cm$^2$ $\approx 50{,}27$ cm$^2$.

**2.** Um círculo tem área $36\pi$ cm$^2$. Determine o raio e o diâmetro.

$$ \pi r^2 = 36\pi \implies r^2 = 36 \implies r = 6 \text{ cm} $$
$$ d = 12 \text{ cm} $$

**Resposta:** Raio = 6 cm, diâmetro = 12 cm.

**3.** Determine o comprimento de um arco de $90°$ em um círculo de raio 10 cm.

$$ \ell = \frac{90°}{360°} \cdot 2\pi \cdot 10 = \frac{1}{4} \cdot 20\pi = 5\pi \approx 15{,}71 \text{ cm} $$

**Resposta:** $5\pi$ cm $\approx 15{,}71$ cm.

**4.** Um ângulo inscrito subtende um arco de $80°$. Qual a medida do ângulo inscrito?

$$ \frac{80°}{2} = 40° $$

**Resposta:** $40°$.

**5.** Determine a área de um setor de $60°$ num círculo de raio 9 cm.

$$ A = \frac{60°}{360°} \cdot \pi \cdot 9^2 = \frac{1}{6} \cdot 81\pi = \frac{27\pi}{2} \approx 42{,}41 \text{ cm}^2 $$

**Resposta:** $\frac{27\pi}{2}$ cm$^2$ $\approx 42{,}41$ cm$^2$.

### Nível 2 — Intermediário

**6.** Uma roda tem raio 35 cm. Quantos metros ela percorre em 100 voltas?

$$ C = 2\pi \cdot 35 = 70\pi \approx 219{,}91 \text{ cm} = 2{,}1991 \text{ m} $$
$$ \text{Distância} = 100 \cdot 2{,}1991 \approx 219{,}91 \text{ m} $$

Ou exato: $100 \cdot 70\pi = 7000\pi$ cm $= 70\pi$ m $\approx 219{,}91$ m.

**Resposta:** $70\pi$ m $\approx 219{,}91$ m.

**7.** Um círculo tem área $50$ cm$^2$. Determine o raio (aproximado).

$$ \pi r^2 = 50 \implies r^2 = \frac{50}{\pi} \approx 15{,}92 \implies r \approx 3{,}99 \approx 4 \text{ cm} $$

**Resposta:** $r = \sqrt{50/\pi} \approx 3{,}99$ cm $\approx 4$ cm.

**8.** Um triângulo está inscrito num círculo de raio 5 cm. Dois vértices formam um diâmetro. Se o terceiro vértice forma um ângulo de $30°$ com o diâmetro, determine a área do triângulo.

O triângulo é retângulo (ângulo na semicircunferência = $90°$).
Hipotenusa = diâmetro = 10 cm.

Se o ângulo com o diâmetro é $30°$:
$$ a = 10 \cdot \sin(30°) = 10 \cdot 0{,}5 = 5 \text{ cm} $$
$$ b = 10 \cdot \cos(30°) = 10 \cdot \frac{\sqrt{3}}{2} = 5\sqrt{3} \text{ cm} $$

$$ A = \frac{5 \cdot 5\sqrt{3}}{2} = \frac{25\sqrt{3}}{2} \approx 21{,}65 \text{ cm}^2 $$

**Resposta:** $\frac{25\sqrt{3}}{2}$ cm$^2$ $\approx 21{,}65$ cm$^2$.

**9.** Determine a área de uma coroa circular (anel) entre círculos de raios 5 cm e 3 cm.

$$ A_{coroa} = \pi \cdot 5^2 - \pi \cdot 3^2 = 25\pi - 9\pi = 16\pi \approx 50{,}27 \text{ cm}^2 $$

**Resposta:** $16\pi$ cm$^2$ $\approx 50{,}27$ cm$^2$.

**10.** Um setor tem área $12\pi$ cm$^2$ e raio 6 cm. Determine o ângulo central em graus.

$$ A_{setor} = \frac{\theta}{360°} \cdot \pi r^2 $$
$$ 12\pi = \frac{\theta}{360°} \cdot 36\pi $$
$$ 12 = \frac{\theta \cdot 36}{360} = \frac{\theta}{10} $$
$$ \theta = 120° $$

**Resposta:** $120°$.

### Nível 3 — Desafio

**11.** Um quadrado está inscrito num círculo de raio $R$. Determine a área do quadrado em função de $R$, e a razão entre a área do quadrado e a área do círculo.

Diagonal do quadrado = $2R$
$$ L\sqrt{2} = 2R \implies L = R\sqrt{2} $$
$$ A_{quadrado} = L^2 = 2R^2 $$
$$ A_{círculo} = \pi R^2 $$
$$ \text{Razão} = \frac{2R^2}{\pi R^2} = \frac{2}{\pi} \approx 0{,}637 = 63{,}7\% $$

**Resposta:** Área do quadrado = $2R^2$. Razão = $\frac{2}{\pi} \approx 63{,}7\%$.

**12.** Determine a área do segmento circular de um círculo de raio 10 cm, delimitado por uma corda que dista 6 cm do centro.

Distância da corda ao centro = 6 cm.
Metade da corda: $\sqrt{10^2 - 6^2} = \sqrt{100 - 36} = \sqrt{64} = 8$ cm.
Corda = 16 cm.

Ângulo central: $\cos(\theta/2) = \frac{6}{10} = 0{,}6 \implies \theta/2 = \arccos(0{,}6) \approx 53{,}13°$
$$ \theta \approx 106{,}26° = 106{,}26 \cdot \frac{\pi}{180} \approx 1{,}855 \text{ rad} $$

$$ A_{setor} = \frac{106{,}26°}{360°} \cdot \pi \cdot 100 \approx 0{,}295 \cdot 314{,}16 \approx 92{,}68 \text{ cm}^2 $$

$$ A_{triângulo} = \frac{1}{2} \cdot 10^2 \cdot \sin(106{,}26°) = 50 \cdot 0{,}96 \approx 48 \text{ cm}^2 $$

Ou usando base e altura: $A_{triângulo} = \frac{16 \cdot 6}{2} = 48$ cm$^2$.

$$ A_{segmento} = 92{,}68 - 48 = 44{,}68 \text{ cm}^2 $$

Exato: $A_{segmento} = 50(\theta - \sin\theta)$ com $\theta = 2\arccos(0{,}6)$.

$$ \sin\theta = 2\sin(\theta/2)\cos(\theta/2) = 2 \cdot 0{,}8 \cdot 0{,}6 = 0{,}96 $$
$$ A_{segmento} = 50(1{,}855 - 0{,}96) = 50(0{,}895) \approx 44{,}75 \text{ cm}^2 $$

**Resposta:** Aproximadamente $44{,}75$ cm$^2$ (exato: $50(2\arccos(0{,}6) - 0{,}96)$ cm$^2$).

**13.** Uma pista de atletismo tem formato circular com raio 36 m. Um atleta corre na pista 2 (1 m para fora do raio interno, ou seja, raio 37 m). Quanto a mais ele corre em uma volta completa comparado a quem corre na pista 1 (raio 36 m)?

$$ C_1 = 2\pi \cdot 36 = 72\pi \text{ m} $$
$$ C_2 = 2\pi \cdot 37 = 74\pi \text{ m} $$
$$ \text{Diferença} = 74\pi - 72\pi = 2\pi \approx 6{,}28 \text{ m} $$

**Resposta:** Aproximadamente 6,28 m a mais (independente do raio interno! A diferença é sempre $2\pi \cdot \text{distância entre pistas}$).

---
**Fim — Círculo e Circunferência**
