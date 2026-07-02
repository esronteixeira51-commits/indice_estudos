# Funções Trigonométricas

As funções trigonométricas — **seno** ($\sin$), **cosseno** ($\cos$), **tangente** ($\tan$) e suas recíprocas — são funções periódicas que modelam fenômenos oscilatórios e circulares. Elas descrevem movimentos harmônicos, ondas, correntes alternadas, sons, luzes, e aparecem em praticamente todas as áreas da ciência e engenharia.

## Definições como Funções

### Função Seno

$$ f(x) = \sin x $$

- **Domínio:** $\mathbb{R}$ (todos os reais)
- **Imagem:** $[-1, 1]$
- **Período:** $2\pi$ (ou $360°$)
- **Função ímpar:** $\sin(-x) = -\sin x$
- **Zeros:** $x = k\pi$, onde $k \in \mathbb{Z}$
- **Máximo ($=1$):** $x = \frac{\pi}{2} + 2k\pi$
- **Mínimo ($=-1$):** $x = \frac{3\pi}{2} + 2k\pi$

### Função Cosseno

$$ f(x) = \cos x $$

- **Domínio:** $\mathbb{R}$
- **Imagem:** $[-1, 1]$
- **Período:** $2\pi$
- **Função par:** $\cos(-x) = \cos x$
- **Zeros:** $x = \frac{\pi}{2} + k\pi$, onde $k \in \mathbb{Z}$
- **Máximo ($=1$):** $x = 2k\pi$
- **Mínimo ($=-1$):** $x = \pi + 2k\pi$

### Função Tangente

$$ f(x) = \tan x = \frac{\sin x}{\cos x} $$

- **Domínio:** $\mathbb{R} \setminus \left\{\frac{\pi}{2} + k\pi\right\}$ (onde $\cos x = 0$)
- **Imagem:** $\mathbb{R}$ (todos os reais)
- **Período:** $\pi$ (ou $180°$)
- **Função ímpar:** $\tan(-x) = -\tan x$
- **Zeros:** $x = k\pi$
- **Assíntotas verticais:** $x = \frac{\pi}{2} + k\pi$

## Funções Recíprocas

| Função | Definição | Período | Domínio |
|--------|-----------|---------|---------|
| **Secante** | $\sec x = \frac{1}{\cos x}$ | $2\pi$ | $\cos x \neq 0$ |
| **Cossecante** | $\csc x = \frac{1}{\sin x}$ | $2\pi$ | $\sin x \neq 0$ |
| **Cotangente** | $\cot x = \frac{1}{\tan x} = \frac{\cos x}{\sin x}$ | $\pi$ | $\sin x \neq 0$ |

## Transformações das Funções Trigonométricas

### Função Geral: $f(x) = a \cdot \sin(bx + c) + d$

| Parâmetro | Efeito | Valor padrão |
|-----------|--------|-------------|
| $a$ | **Amplitude** (altura da onda) | $|a|$ |
| $b$ | **Frequência** angular; período = $\frac{2\pi}{|b|}$ | $b = 1$ → período $2\pi$ |
| $c$ | **Deslocamento de fase** (fase inicial); desloca horizontalmente $-\frac{c}{b}$ | $c = 0$ |
| $d$ | **Deslocamento vertical** (média/linha do eixo) | $d = 0$ |

### Exemplos de Transformação

- $y = 2\sin x$: amplitude dobrada
- $y = \sin(2x)$: período reduzido pela metade ($\pi$ em vez de $2\pi$)
- $y = \sin(x + \frac{\pi}{2}) = \cos x$: deslocado $-\frac{\pi}{2}$ (ou $\frac{\pi}{2}$ para a esquerda)
- $y = \sin x + 1$: deslocado 1 unidade para cima
- $y = -\sin x$: refletido no eixo $x$

## Identidades Trigonométricas Fundamentais

### Soma e Diferença de Ângulos

$$ \sin(a + b) = \sin a \cos b + \cos a \sin b $$
$$ \sin(a - b) = \sin a \cos b - \cos a \sin b $$
$$ \cos(a + b) = \cos a \cos b - \sin a \sin b $$
$$ \cos(a - b) = \cos a \cos b + \sin a \sin b $$
$$ \tan(a + b) = \frac{\tan a + \tan b}{1 - \tan a \tan b} $$
$$ \tan(a - b) = \frac{\tan a - \tan b}{1 + \tan a \tan b} $$

### Ângulo Duplo

$$ \sin(2a) = 2\sin a \cos a $$
$$ \cos(2a) = \cos^2 a - \sin^2 a = 2\cos^2 a - 1 = 1 - 2\sin^2 a $$
$$ \tan(2a) = \frac{2\tan a}{1 - \tan^2 a} $$

### Ângulo Metade (Bissecção)

$$ \sin^2\left(\frac{a}{2}\right) = \frac{1 - \cos a}{2} $$
$$ \cos^2\left(\frac{a}{2}\right) = \frac{1 + \cos a}{2} $$
$$ \tan\left(\frac{a}{2}\right) = \frac{1 - \cos a}{\sin a} = \frac{\sin a}{1 + \cos a} $$

### Transformação em Produto (Fatoração)

$$ \sin a + \sin b = 2\sin\left(\frac{a+b}{2}\right)\cos\left(\frac{a-b}{2}\right) $$
$$ \sin a - \sin b = 2\cos\left(\frac{a+b}{2}\right)\sin\left(\frac{a-b}{2}\right) $$
$$ \cos a + \cos b = 2\cos\left(\frac{a+b}{2}\right)\cos\left(\frac{a-b}{2}\right) $$
$$ \cos a - \cos b = -2\sin\left(\frac{a+b}{2}\right)\sin\left(\frac{a-b}{2}\right) $$

## Equações Trigonométricas Fundamentais

### $\sin x = \sin \alpha$

$$ x = \alpha + 2k\pi \quad \text{ou} \quad x = \pi - \alpha + 2k\pi, \quad k \in \mathbb{Z} $$

### $\cos x = \cos \alpha$

$$ x = \alpha + 2k\pi \quad \text{ou} \quad x = -\alpha + 2k\pi, \quad k \in \mathbb{Z} $$

### $\tan x = \tan \alpha$

$$ x = \alpha + k\pi, \quad k \in \mathbb{Z} $$

## Exemplos

### Exemplo 1: Amplitude e período

Determine a amplitude e o período de $f(x) = 3\sin(2x)$.

- Amplitude = $|3| = 3$
- Período = $\frac{2\pi}{2} = \pi$

**Resposta:** Amplitude = 3, período = $\pi$.

### Exemplo 2: Fase e deslocamento

Determine o deslocamento de fase de $f(x) = \sin(x - \frac{\pi}{3})$.

Deslocamento = $-\frac{c}{b} = -\frac{(-\pi/3)}{1} = \frac{\pi}{3}$ para a direita.

**Resposta:** Deslocamento de $\frac{\pi}{3}$ para a direita.

### Exemplo 3: Soma de ângulos

Calcule $\sin 75°$ usando $\sin(45° + 30°)$.

$$ \sin 75° = \sin(45° + 30°) = \sin 45° \cos 30° + \cos 45° \sin 30° $$
$$ = \frac{\sqrt{2}}{2} \cdot \frac{\sqrt{3}}{2} + \frac{\sqrt{2}}{2} \cdot \frac{1}{2} $$
$$ = \frac{\sqrt{6}}{4} + \frac{\sqrt{2}}{4} = \frac{\sqrt{6} + \sqrt{2}}{4} $$

**Resposta:** $\frac{\sqrt{6} + \sqrt{2}}{4}$.

### Exemplo 4: Ângulo duplo

Se $\sin x = \frac{3}{5}$ e $x$ está no 1º quadrante, determine $\sin(2x)$.

$$ \cos x = \sqrt{1 - \frac{9}{25}} = \frac{4}{5} $$
$$ \sin(2x) = 2 \cdot \frac{3}{5} \cdot \frac{4}{5} = \frac{24}{25} $$

**Resposta:** $24/25$.

### Exemplo 5: Resolver equação trigonométrica

Resolva $\sin x = \frac{1}{2}$ para $x \in [0, 2\pi]$.

$$ x = \frac{\pi}{6} \quad \text{ou} \quad x = \pi - \frac{\pi}{6} = \frac{5\pi}{6} $$

**Resposta:** $x = \frac{\pi}{6}$ ou $x = \frac{5\pi}{6}$.

## Aplicações na Vida Real

- **Física:** movimento harmônico simples (molas, pêndulos), ondas mecânicas
- **Engenharia:** vibrações, análise de sinais, filtros, circuitos AC
- **Música:** ondas sonoras, frequências, harmônicos, síntese de som
- **Eletrônica:** corrente alternada, análise de Fourier, processamento de sinais
- **Medicina:** eletrocardiograma (ECG), ondas cerebrais (EEG), ultrassom
- **Astronomia:** variações de brilho de estrelas, órbitas, marés
- **Meteorologia:** variações de temperatura, marés, ciclos climáticos
- **Arquitetura:** desenho de curvas, estruturas onduladas, iluminação
- **Jogos:** animações cíclicas, movimentos oscilatórios, câmeras, física de fluidos
- **Economia:** análise de ciclos econômicos, sazonalidade, previsões

## Problemas

### Nível 1 — Básico

**1.** Determine a amplitude e o período de $f(x) = 2\cos(3x)$.

- Amplitude = $|2| = 2$
- Período = $\frac{2\pi}{3}$

**Resposta:** Amplitude = 2; período = $\frac{2\pi}{3}$.

**2.** Determine o deslocamento vertical e horizontal de $f(x) = \sin(x + \frac{\pi}{4}) + 2$.

- Deslocamento horizontal: $-\frac{\pi}{4}$ (esquerda)
- Deslocamento vertical: $+2$ (para cima)

**Resposta:** $\frac{\pi}{4}$ para a esquerda; 2 para cima.

**3.** Calcule $\cos 75°$ usando $\cos(45° + 30°)$.

$$ \cos 75° = \cos 45° \cos 30° - \sin 45° \sin 30° $$
$$ = \frac{\sqrt{2}}{2} \cdot \frac{\sqrt{3}}{2} - \frac{\sqrt{2}}{2} \cdot \frac{1}{2} = \frac{\sqrt{6} - \sqrt{2}}{4} $$

**Resposta:** $\frac{\sqrt{6} - \sqrt{2}}{4}$.

**4.** Se $\cos x = \frac{5}{13}$ e $x$ está no 1º quadrante, determine $\cos(2x)$.

$$ \cos(2x) = 2\cos^2 x - 1 = 2 \cdot \frac{25}{169} - 1 = \frac{50}{169} - \frac{169}{169} = -\frac{119}{169} $$

**Resposta:** $-\frac{119}{169}$.

**5.** Resolva $\cos x = \frac{\sqrt{2}}{2}$ para $x \in [0, 2\pi]$.

$$ x = \frac{\pi}{4} \quad \text{ou} \quad x = 2\pi - \frac{\pi}{4} = \frac{7\pi}{4} $$

**Resposta:** $x = \frac{\pi}{4}$ ou $x = \frac{7\pi}{4}$.

### Nível 2 — Intermediário

**6.** Demonstre que $\sin(90° + x) = \cos x$ usando a fórmula de soma.

$$ \sin(90° + x) = \sin 90° \cos x + \cos 90° \sin x = 1 \cdot \cos x + 0 \cdot \sin x = \cos x $$

**Resposta:** Demonstrado.

**7.** Simplifique $\frac{\sin(2x)}{\sin x}$ para $\sin x \neq 0$.

$$ \frac{2\sin x \cos x}{\sin x} = 2\cos x $$

**Resposta:** $2\cos x$.

**8.** Se $\tan x = 2$ e $\tan y = 3$, determine $\tan(x + y)$.

$$ \tan(x + y) = \frac{2 + 3}{1 - 2 \cdot 3} = \frac{5}{1 - 6} = \frac{5}{-5} = -1 $$

**Resposta:** $-1$.

**9.** Resolva $2\sin x - 1 = 0$ para $x \in [0, 2\pi]$.

$$ \sin x = \frac{1}{2} $$
$$ x = \frac{\pi}{6} \quad \text{ou} \quad x = \frac{5\pi}{6} $$

**Resposta:** $x = \frac{\pi}{6}$ ou $x = \frac{5\pi}{6}$.

**10.** Determine o valor máximo e mínimo de $f(x) = 3\sin x + 4\cos x$.

Usando a identidade $a\sin x + b\cos x = R\sin(x + \alpha)$, onde $R = \sqrt{a^2 + b^2}$:
$$ R = \sqrt{9 + 16} = 5 $$

O valor máximo é $R = 5$ e o mínimo é $-R = -5$.

**Resposta:** Máximo = 5; Mínimo = $-5$.

### Nível 3 — Desafio

**11.** (Fórmula de prostaférese) Demonstre que $\sin a + \sin b = 2\sin\frac{a+b}{2}\cos\frac{a-b}{2}$.

**Demonstração:**
Seja $u = \frac{a+b}{2}$ e $v = \frac{a-b}{2}$. Então $a = u + v$ e $b = u - v$.

$$ \sin a + \sin b = \sin(u+v) + \sin(u-v) $$
$$ = (\sin u \cos v + \cos u \sin v) + (\sin u \cos v - \cos u \sin v) $$
$$ = 2\sin u \cos v = 2\sin\frac{a+b}{2}\cos\frac{a-b}{2} $$

**Resposta:** Demonstrado.

**12.** (Equação geral) Resolva $\sin x + \cos x = 1$ para $x \in [0, 2\pi]$.

**Método 1:** Dividir por $\sqrt{2}$:
$$ \frac{1}{\sqrt{2}}\sin x + \frac{1}{\sqrt{2}}\cos x = \frac{1}{\sqrt{2}} $$
$$ \sin x \cos 45° + \cos x \sin 45° = \frac{\sqrt{2}}{2} $$
$$ \sin(x + 45°) = \frac{\sqrt{2}}{2} $$

$$ x + 45° = 45° + 360°k \quad \text{ou} \quad x + 45° = 135° + 360°k $$
$$ x = 0° + 360°k \quad \text{ou} \quad x = 90° + 360°k $$

Em $[0, 2\pi]$: $x = 0$ ou $x = \frac{\pi}{2}$.

**Resposta:** $x = 0$ ou $x = \frac{\pi}{2}$ (ou $0°$ ou $90°$).

**13.** (Movimento harmônico) A posição de uma massa em uma mola é dada por $x(t) = A\sin(\omega t + \phi)$. Se $A = 5$ cm, $\omega = 2$ rad/s, e $\phi = \frac{\pi}{4}$, determine:
(a) A posição inicial ($t = 0$)
(b) A posição após 1 segundo
(c) O primeiro instante em que a posição é zero

**(a)** $x(0) = 5\sin(\frac{\pi}{4}) = 5 \cdot \frac{\sqrt{2}}{2} = \frac{5\sqrt{2}}{2} \approx 3{,}54$ cm.

**(b)** $x(1) = 5\sin(2 + \frac{\pi}{4}) = 5\sin(2 + 0{,}785) = 5\sin(2{,}785) \approx 5 \cdot 0{,}349 \approx 1{,}75$ cm.

**(c)** $x(t) = 0 \implies \sin(2t + \frac{\pi}{4}) = 0$
$$ 2t + \frac{\pi}{4} = k\pi \implies t = \frac{k\pi - \pi/4}{2} = \frac{k\pi}{2} - \frac{\pi}{8} $$

Para $k = 1$: $t = \frac{\pi}{2} - \frac{\pi}{8} = \frac{3\pi}{8} \approx 1{,}18$ s.

**Resposta:** (a) $\frac{5\sqrt{2}}{2}$ cm; (b) ≈ 1,75 cm; (c) $\frac{3\pi}{8}$ s ≈ 1,18 s.

---
**Fim — Funções Trigonométricas**
