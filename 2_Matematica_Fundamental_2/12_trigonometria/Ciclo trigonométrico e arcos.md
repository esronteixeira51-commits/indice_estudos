# Ciclo Trigonométrico e Arcos

O **ciclo trigonométrico** (ou círculo trigonométrico, círculo unitário) é uma circunferência de raio 1 centrada na origem de um sistema de coordenadas cartesianas. Ele generaliza as razões trigonométricas para ângulos de qualquer medida — positivos, negativos, agudos, obtusos, maiores que $360°$, e em radianos. É a base para as funções trigonométricas modernas.

## Definição do Ciclo Trigonométrico

$$ x^2 + y^2 = 1 $$

- Centro: origem $(0, 0)$
- Raio: $r = 1$

Para um ponto $P$ no ciclo, associado a um ângulo $\theta$ (medido a partir do eixo positivo $x$, no sentido anti-horário):

$$ P = (\cos \theta, \sin \theta) $$

## Sinais das Razões Trigonométricas por Quadrante

| Quadrante | Ângulos | Seno | Cosseno | Tangente |
|-----------|---------|------|---------|----------|
| **1º** | $0° < \theta < 90°$ | $+$ | $+$ | $+$ |
| **2º** | $90° < \theta < 180°$ | $+$ | $-$ | $-$ |
| **3º** | $180° < \theta < 270°$ | $-$ | $-$ | $+$ |
| **4º** | $270° < \theta < 360°$ | $-$ | $+$ | $-$ |

**Mnemônico:** "**A**ll **S**tudents **T**ake **C**alculus" (All, Sine, Tangent, Cosine positivos nos quadrantes 1, 2, 3, 4 respectivamente).

Em português: "**T**odos **S**ão **T**alentosos **C**riativos" (Todos, Seno, Tangente, Cosseno).

## Redução ao 1º Quadrante

Para calcular razões trigonométricas de ângulos em qualquer quadrante, reduzimos ao ângulo agudo correspondente (referência) e ajustamos o sinal conforme o quadrante.

### 2º Quadrante ($180° - \alpha$ ou $\pi - \alpha$)

$$ \sin(180° - \alpha) = \sin \alpha $$
$$ \cos(180° - \alpha) = -\cos \alpha $$
$$ \tan(180° - \alpha) = -\tan \alpha $$

### 3º Quadrante ($180° + \alpha$ ou $\pi + \alpha$)

$$ \sin(180° + \alpha) = -\sin \alpha $$
$$ \cos(180° + \alpha) = -\cos \alpha $$
$$ \tan(180° + \alpha) = \tan \alpha $$

### 4º Quadrante ($360° - \alpha$ ou $2\pi - \alpha$)

$$ \sin(360° - \alpha) = -\sin \alpha $$
$$ \cos(360° - \alpha) = \cos \alpha $$
$$ \tan(360° - \alpha) = -\tan \alpha $$

### Ângulos maiores que $360°$ (ou negativos)

Adicione ou subtraia múltiplos de $360°$ (ou $2\pi$) até encontrar um ângulo equivalente entre $0°$ e $360°$:

$$ \sin(\theta + 360°k) = \sin \theta, \quad \cos(\theta + 360°k) = \cos \theta $$

## Ângulos Negativos

$$ \sin(-\theta) = -\sin \theta \quad \text{(função ímpar)} $$
$$ \cos(-\theta) = \cos \theta \quad \text{(função par)} $$
$$ \tan(-\theta) = -\tan \theta \quad \text{(função ímpar)} $$

## Arcos e Radianos

### Conversão

$$ 180° = \pi \text{ rad} $$
$$ 1° = \frac{\pi}{180} \text{ rad} \approx 0{,}01745 \text{ rad} $$
$$ 1 \text{ rad} = \frac{180°}{\pi} \approx 57{,}2958° $$

### Comprimento de Arco

$$ s = r \cdot \theta \quad \text{(} \theta \text{ em radianos)} $$

### Área do Setor Circular

$$ A = \frac{1}{2} r^2 \theta = \frac{1}{2} r \cdot s \quad \text{(} \theta \text{ em radianos)} $$

## Simetrias no Ciclo Trigonométrico

### Simetria em relação ao eixo $x$ (ângulos $\theta$ e $-\theta$)

$$ \sin(-\theta) = -\sin \theta, \quad \cos(-\theta) = \cos \theta $$

### Simetria em relação ao eixo $y$ (ângulos $\theta$ e $\pi - \theta$)

$$ \sin(\pi - \theta) = \sin \theta, \quad \cos(\pi - \theta) = -\cos \theta $$

### Simetria em relação à origem (ângulos $\theta$ e $\pi + \theta$)

$$ \sin(\pi + \theta) = -\sin \theta, \quad \cos(\pi + \theta) = -\cos \theta $$

### Simetria em relação à reta $y = x$ (ângulos $\theta$ e $\frac{\pi}{2} - \theta$)

$$ \sin\left(\frac{\pi}{2} - \theta\right) = \cos \theta, \quad \cos\left(\frac{\pi}{2} - \theta\right) = \sin \theta $$

### Simetria em relação à reta $y = -x$ (ângulos $\theta$ e $\frac{3\pi}{2} - \theta$)

$$ \sin\left(\frac{3\pi}{2} - \theta\right) = -\cos \theta, \quad \cos\left(\frac{3\pi}{2} - \theta\right) = -\sin \theta $$

## Ângulos Complementares e Suplementares

### Complementares ($\alpha + \beta = 90°$ ou $\frac{\pi}{2}$)

$$ \sin \alpha = \cos \beta, \quad \cos \alpha = \sin \beta, \quad \tan \alpha = \cot \beta $$

### Suplementares ($\alpha + \beta = 180°$ ou $\pi$)

$$ \sin \alpha = \sin \beta, \quad \cos \alpha = -\cos \beta, \quad \tan \alpha = -\tan \beta $$

## Valores Especiais no Ciclo

| Ângulo | $0°$ | $90°$ | $180°$ | $270°$ | $360°$ |
|--------|------|-------|--------|--------|--------|
| **Seno** | $0$ | $1$ | $0$ | $-1$ | $0$ |
| **Cosseno** | $1$ | $0$ | $-1$ | $0$ | $1$ |
| **Tangente** | $0$ | **ind.** | $0$ | **ind.** | $0$ |

## Exemplos

### Exemplo 1: Redução ao 1º quadrante

Calcule $\sin 150°$.

$$ 150° = 180° - 30° \quad \text{(2º quadrante)} $$
$$ \sin 150° = \sin 30° = \frac{1}{2} \quad \text{(sinal positivo no 2º)} $$

**Resposta:** $1/2$.

### Exemplo 2: Redução ao 1º quadrante

Calcule $\cos 240°$.

$$ 240° = 180° + 60° \quad \text{(3º quadrante)} $$
$$ \cos 240° = -\cos 60° = -\frac{1}{2} \quad \text{(sinal negativo no 3º)} $$

**Resposta:** $-1/2$.

### Exemplo 3: Ângulo negativo

Calcule $\sin(-30°)$.

$$ \sin(-30°) = -\sin 30° = -\frac{1}{2} $$

**Resposta:** $-1/2$.

### Exemplo 4: Arco maior que $360°$

Calcule $\tan 750°$.

$$ 750° = 2 \cdot 360° + 30° $$
$$ \tan 750° = \tan 30° = \frac{\sqrt{3}}{3} $$

**Resposta:** $\sqrt{3}/3$.

### Exemplo 5: Comprimento de arco

Um arco tem raio 5 cm e ângulo central $60°$ ($= \pi/3$ rad). Determine o comprimento do arco.

$$ s = r \cdot \theta = 5 \cdot \frac{\pi}{3} = \frac{5\pi}{3} \approx 5{,}24 \text{ cm} $$

**Resposta:** $\frac{5\pi}{3}$ cm $\approx 5{,}24$ cm.

## Aplicações na Vida Real

- **Navegação:** rumos, azimutes, coordenadas polares, GPS
- **Astronomia:** coordenadas celestes (ascensão reta, declinação), movimento dos planetas
- **Física:** movimento circular, pêndulos, ondas harmônicas simples
- **Engenharia:** mecanismos rotativos, engrenagens, virabrequins, balanceamento
- **Música:** análise de frequências, harmônicos, síntese sonora
- **Medicina:** imagens médicas (tomografia, ressonância), angiografia
- **Arquitetura:** escadas em espiral, rampas curvas, estruturas circulares
- **Jogos:** rotação de sprites, câmeras orbitais, movimentos circulares
- **Eletrônica:** corrente alternada, fasores, análise de circuitos AC
- **Dança/patinação:** piruetas, rotações, ângulos de salto

## Problemas

### Nível 1 — Básico

**1.** Determine o sinal de: $\sin 200°$, $\cos 300°$, $\tan 100°$.

- $200°$ está no 3º quadrante: $\sin 200° < 0$ (negativo)
- $300°$ está no 4º quadrante: $\cos 300° > 0$ (positivo)
- $100°$ está no 2º quadrante: $\tan 100° < 0$ (negativo)

**Resposta:** $\sin 200° < 0$, $\cos 300° > 0$, $\tan 100° < 0$.

**2.** Calcule $\sin 120°$, $\cos 135°$, $\tan 225°$.

$$ \sin 120° = \sin(180° - 60°) = \sin 60° = \frac{\sqrt{3}}{2} $$
$$ \cos 135° = -\cos 45° = -\frac{\sqrt{2}}{2} $$
$$ \tan 225° = \tan(180° + 45°) = \tan 45° = 1 $$

**Resposta:** $\sin 120° = \frac{\sqrt{3}}{2}$, $\cos 135° = -\frac{\sqrt{2}}{2}$, $\tan 225° = 1$.

**3.** Converta $150°$ para radianos e $\frac{5\pi}{6}$ radianos para graus.

$$ 150° = 150 \cdot \frac{\pi}{180} = \frac{5\pi}{6} \text{ rad} $$
$$ \frac{5\pi}{6} = \frac{5 \cdot 180°}{6} = 150° $$

**Resposta:** $150° = \frac{5\pi}{6}$ rad; $\frac{5\pi}{6}$ rad = $150°$.

**4.** Determine o comprimento de um arco de $45°$ numa circunferência de raio 8 cm.

$$ 45° = \frac{\pi}{4} \text{ rad} $$
$$ s = 8 \cdot \frac{\pi}{4} = 2\pi \approx 6{,}28 \text{ cm} $$

**Resposta:** $2\pi$ cm $\approx 6{,}28$ cm.

**5.** Calcule $\cos(-60°) + \sin(-30°)$.

$$ \cos(-60°) = \cos 60° = \frac{1}{2} $$
$$ \sin(-30°) = -\sin 30° = -\frac{1}{2} $$
$$ \text{Resultado} = \frac{1}{2} - \frac{1}{2} = 0 $$

**Resposta:** 0.

### Nível 2 — Intermediário

**6.** Calcule o valor exato de $\sin 210° \cdot \cos 330° + \tan 120°$.

$$ \sin 210° = \sin(180° + 30°) = -\sin 30° = -\frac{1}{2} $$
$$ \cos 330° = \cos(360° - 30°) = \cos 30° = \frac{\sqrt{3}}{2} $$
$$ \tan 120° = \tan(180° - 60°) = -\tan 60° = -\sqrt{3} $$

$$ = \left(-\frac{1}{2}\right) \cdot \frac{\sqrt{3}}{2} + (-\sqrt{3}) = -\frac{\sqrt{3}}{4} - \sqrt{3} = -\frac{5\sqrt{3}}{4} $$

**Resposta:** $-\frac{5\sqrt{3}}{4}$.

**7.** Determine a área de um setor circular de raio 6 cm e ângulo central $120°$.

$$ 120° = \frac{2\pi}{3} \text{ rad} $$
$$ A = \frac{1}{2} \cdot 36 \cdot \frac{2\pi}{3} = 12\pi \approx 37{,}70 \text{ cm}^2 $$

**Resposta:** $12\pi$ cm$^2$ $\approx 37{,}70$ cm$^2$.

**8.** Se $\sin \theta = -3/5$ e $\theta$ está no 3º quadrante, determine $\cos \theta$ e $\tan \theta$.

$$ \cos^2 \theta = 1 - \frac{9}{25} = \frac{16}{25} $$

No 3º quadrante, cosseno é negativo:
$$ \cos \theta = -\frac{4}{5} $$
$$ \tan \theta = \frac{-3/5}{-4/5} = \frac{3}{4} $$

**Resposta:** $\cos \theta = -4/5$, $\tan \theta = 3/4$.

**9.** Um ponto se move ao longo de uma circunferência de raio 4 m com velocidade angular constante de $30°/s$. Quanto tempo leva para percorrer um arco de $2\pi$ m? Qual a distância percorrida em 10 segundos?

Velocidade angular: $\omega = 30°/s = \frac{\pi}{6}$ rad/s.

Comprimento do arco $2\pi$ m:
$$ s = r \cdot \theta \implies 2\pi = 4 \cdot \theta \implies \theta = \frac{\pi}{2} \text{ rad} = 90° $$
$$ t = \frac{90°}{30°/s} = 3 \text{ s} $$

Distância em 10 s:
$$ \theta = 30°/s \cdot 10 = 300° = \frac{5\pi}{3} \text{ rad} $$
$$ s = 4 \cdot \frac{5\pi}{3} = \frac{20\pi}{3} \approx 20{,}94 \text{ m} $$

**Resposta:** 3 s para percorrer $2\pi$ m; $\frac{20\pi}{3}$ m $\approx 20{,}94$ m em 10 s.

**10.** Simplifique: $\frac{\sin(180° - x)}{\sin x} + \frac{\cos(360° - x)}{\cos x}$.

$$ \frac{\sin x}{\sin x} + \frac{\cos x}{\cos x} = 1 + 1 = 2 $$

**Resposta:** 2.

### Nível 3 — Desafio

**11.** (Simetria) Demonstre que $\sin(90° + \theta) = \cos \theta$ e $\cos(90° + \theta) = -\sin \theta$ usando o ciclo trigonométrico.

**Demonstração:** O ponto $(\cos(90° + \theta), \sin(90° + \theta))$ no ciclo pode ser obtido rotacionando $(\cos \theta, \sin \theta)$ por $90°$. A rotação de $90°$ transforma $(x, y)$ em $(-y, x)$. Logo:
$$ \cos(90° + \theta) = -\sin \theta, \quad \sin(90° + \theta) = \cos \theta $$

**Resposta:** Demonstrado.

**12.** (Radianos e graus) A Terra completa uma volta em aproximadamente 24 horas em torno de seu eixo. A latitude de São Paulo é aproximadamente $23°$ S. Qual a velocidade angular da Terra em rad/s? Qual a velocidade linear de um ponto na superfície da Terra no equador? E em São Paulo? (Raio da Terra $\approx 6371$ km.)

**Velocidade angular:**
$$ \omega = \frac{2\pi \text{ rad}}{24 \cdot 3600 \text{ s}} = \frac{2\pi}{86400} \approx 7{,}27 \cdot 10^{-5} \text{ rad/s} $$

**Velocidade linear no equador:**
$$ v = \omega \cdot R = \frac{2\pi \cdot 6371}{86400} \approx 463{,}8 \text{ m/s} \approx 1670 \text{ km/h} $$

**Velocidade linear em São Paulo:**
O raio da trajetória de São Paulo é $R \cdot \cos(23°)$.
$$ v_{SP} = \omega \cdot R \cdot \cos(23°) = 463{,}8 \cdot \cos(23°) \approx 463{,}8 \cdot 0{,}921 \approx 427 \text{ m/s} \approx 1537 \text{ km/h} $$

**Resposta:** $\omega \approx 7{,}27 \times 10^{-5}$ rad/s; Equador ≈ 1670 km/h; São Paulo ≈ 1537 km/h.

**13.** (Arquimedes e a retificação da circunferência) Usando o ciclo trigonométrico, prove que $\lim_{x \to 0} \frac{\sin x}{x} = 1$ (x em radianos). Aplique isso para mostrar que a derivada do seno é o cosseno.

**Demonstração geométrica:**
No ciclo trigonométrico, para $x > 0$ pequeno:
- Área do triângulo OAB (A = $(1,0)$, B = $(\cos x, \sin x)$): $\frac{1}{2} \sin x$
- Área do setor OAB: $\frac{x}{2}$
- Área do triângulo OAT (T = $(1, \tan x)$): $\frac{1}{2} \tan x$

Para $x$ pequeno:
$$ \frac{1}{2} \sin x < \frac{x}{2} < \frac{1}{2} \tan x $$

$$ \sin x < x < \tan x = \frac{\sin x}{\cos x} $$

Dividindo por $\sin x$ (positivo para $x > 0$ pequeno):
$$ 1 < \frac{x}{\sin x} < \frac{1}{\cos x} $$

Tomando o limite $x \to 0$:
$$ 1 \leq \lim_{x \to 0} \frac{x}{\sin x} \leq 1 \implies \lim_{x \to 0} \frac{\sin x}{x} = 1 $$

**Derivada do seno:**
$$ \frac{d}{dx} \sin x = \lim_{h \to 0} \frac{\sin(x+h) - \sin x}{h} $$
$$ = \lim_{h \to 0} \frac{\sin x \cos h + \cos x \sin h - \sin x}{h} $$
$$ = \sin x \cdot \lim_{h \to 0} \frac{\cos h - 1}{h} + \cos x \cdot \lim_{h \to 0} \frac{\sin h}{h} $$

$$ = \sin x \cdot 0 + \cos x \cdot 1 = \cos x $$

**Resposta:** Demonstrado que $\lim_{x \to 0} \frac{\sin x}{x} = 1$ e $\frac{d}{dx} \sin x = \cos x$.

---
**Fim — Ciclo Trigonométrico e Arcos**
