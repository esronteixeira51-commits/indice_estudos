# Problemas de Revisão — Trigonometria

Este arquivo reúne problemas integrados que envolvem múltiplos conceitos de trigonometria: razões trigonométricas no triângulo retângulo, ciclo trigonométrico, funções trigonométricas, transformações, identidades, lei dos senos, lei dos cossenos e aplicações práticas. Os problemas exigem combinação de técnicas, interpretação de figuras e raciocínio avançado.

## Revisão de Conceitos-Chave

### Razões Trigonométricas no Triângulo Retângulo
- $\sin \theta = \frac{cateto \ oposto}{hipotenusa}$, $\cos \theta = \frac{cateto \ adjacente}{hipotenusa}$, $\tan \theta = \frac{cateto \ oposto}{cateto \ adjacente}$
- $\sin^2 \theta + \cos^2 \theta = 1$, $\tan \theta = \frac{\sin \theta}{\cos \theta}$
- Ângulos notáveis: $30°$ ($\frac{\pi}{6}$), $45°$ ($\frac{\pi}{4}$), $60°$ ($\frac{\pi}{3}$)

### Ciclo Trigonométrico
- Sinais por quadrante: 1º (todos +), 2º (seno +), 3º (tangente +), 4º (cosseno +)
- Redução ao 1º quadrante: $\sin(180° - x) = \sin x$, $\cos(180° - x) = -\cos x$, etc.
- Ângulos negativos: $\sin(-x) = -\sin x$, $\cos(-x) = \cos x$
- Período: $360°$ ou $2\pi$ para seno e cosseno; $180°$ ou $\pi$ para tangente

### Funções Trigonométricas
- $f(x) = a\sin(bx + c) + d$: amplitude $|a|$, período $\frac{2\pi}{|b|}$, fase $-\frac{c}{b}$, média $d$
- Soma de ângulos: $\sin(a+b)$, $\cos(a+b)$, $\tan(a+b)$
- Ângulo duplo: $\sin(2x)$, $\cos(2x)$, $\tan(2x)$
- Equações: $\sin x = \sin \alpha \Rightarrow x = \alpha + 2k\pi$ ou $x = \pi - \alpha + 2k\pi$

### Lei dos Senos e Cossenos
- $\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R$
- $a^2 = b^2 + c^2 - 2bc\cos A$
- Área: $A = \frac{1}{2}ab\sin C = \frac{abc}{4R}$

## Problemas

### Nível 1 — Básico (Revisão)

**1.** Num triângulo retângulo, a hipotenusa é 17 e um cateto é 8. Determine $\sin \theta$, $\cos \theta$ e $\tan \theta$ para o ângulo oposto ao cateto 8.

$$ \text{Outro cateto} = \sqrt{17^2 - 8^2} = \sqrt{289 - 64} = \sqrt{225} = 15 $$
$$ \sin \theta = \frac{8}{17}, \quad \cos \theta = \frac{15}{17}, \quad \tan \theta = \frac{8}{15} $$

**Resposta:** $\sin \theta = 8/17$, $\cos \theta = 15/17$, $\tan \theta = 8/15$.

**2.** Calcule: $\sin 30° \cos 60° + \cos 30° \sin 60°$.

$$ = \frac{1}{2} \cdot \frac{1}{2} + \frac{\sqrt{3}}{2} \cdot \frac{\sqrt{3}}{2} = \frac{1}{4} + \frac{3}{4} = 1 $$

> **Observação:** Isso é $\sin(30° + 60°) = \sin 90° = 1$!

**Resposta:** 1.

**3.** Determine o sinal de: $\sin 310°$, $\cos 200°$, $\tan 150°$.

- $310°$ está no 4º quadrante: $\sin 310° < 0$ (negativo)
- $200°$ está no 3º quadrante: $\cos 200° < 0$ (negativo)
- $150°$ está no 2º quadrante: $\tan 150° < 0$ (negativo)

**Resposta:** $\sin 310° < 0$, $\cos 200° < 0$, $\tan 150° < 0$.

**4.** Converta $135°$ para radianos e $\frac{7\pi}{4}$ radianos para graus.

$$ 135° = 135 \cdot \frac{\pi}{180} = \frac{3\pi}{4} \text{ rad} $$
$$ \frac{7\pi}{4} = \frac{7 \cdot 180°}{4} = 315° $$

**Resposta:** $135° = \frac{3\pi}{4}$ rad; $\frac{7\pi}{4}$ rad = $315°$.

**5.** Determine a amplitude e o período de $f(x) = 4\sin(2x + \frac{\pi}{3})$.

- Amplitude = $|4| = 4$
- Período = $\frac{2\pi}{2} = \pi$

**Resposta:** Amplitude = 4; período = $\pi$.

---

### Nível 2 — Intermediário (Aplicação)

**6.** Uma escada de 8 m está apoiada numa parede formando um ângulo de $50°$ com o chão. A que altura a escada toca a parede? (Use $\sin 50° \approx 0{,}766$.)

$$ h = 8 \cdot \sin 50° \approx 8 \cdot 0{,}766 = 6{,}13 \text{ m} $$

**Resposta:** Aproximadamente 6,13 m.

**7.** De um ponto no solo, o topo de uma torre é visto sob um ângulo de elevação de $45°$. Afastando-se 20 m, o ângulo passa a ser $30°$. Qual a altura da torre?

$$ \tan 45° = \frac{h}{x} = 1 \implies x = h $$
$$ \tan 30° = \frac{h}{x + 20} = \frac{1}{\sqrt{3}} $$
$$ h = \frac{h + 20}{\sqrt{3}} $$
$$ h\sqrt{3} = h + 20 $$
$$ h(\sqrt{3} - 1) = 20 $$
$$ h = \frac{20}{\sqrt{3} - 1} = \frac{20(\sqrt{3} + 1)}{3 - 1} = 10(\sqrt{3} + 1) \approx 27{,}32 \text{ m} $$

**Resposta:** $10(\sqrt{3} + 1)$ m $\approx 27{,}32$ m.

**8.** Calcule o valor exato de $\sin 15°$ usando $\sin(45° - 30°)$.

$$ \sin 15° = \sin(45° - 30°) = \sin 45° \cos 30° - \cos 45° \sin 30° $$
$$ = \frac{\sqrt{2}}{2} \cdot \frac{\sqrt{3}}{2} - \frac{\sqrt{2}}{2} \cdot \frac{1}{2} = \frac{\sqrt{6} - \sqrt{2}}{4} $$

**Resposta:** $\frac{\sqrt{6} - \sqrt{2}}{4}$.

**9.** Se $\sin x = \frac{2}{3}$ e $\cos x > 0$, determine $\cos(2x)$.

$$ \cos^2 x = 1 - \frac{4}{9} = \frac{5}{9} \implies \cos x = \frac{\sqrt{5}}{3} $$
$$ \cos(2x) = \cos^2 x - \sin^2 x = \frac{5}{9} - \frac{4}{9} = \frac{1}{9} $$

**Resposta:** $1/9$.

**10.** Resolva $2\cos x - \sqrt{3} = 0$ para $x \in [0, 2\pi]$.

$$ \cos x = \frac{\sqrt{3}}{2} $$
$$ x = \frac{\pi}{6} \quad \text{ou} \quad x = \frac{11\pi}{6} $$

**Resposta:** $x = \frac{\pi}{6}$ ou $x = \frac{11\pi}{6}$.

**11.** Num triângulo, $a = 7$, $b = 9$, $C = 60°$. Determine $c$ e a área.

$$ c^2 = 49 + 81 - 2 \cdot 7 \cdot 9 \cdot \cos 60° = 130 - 126 \cdot 0{,}5 = 130 - 63 = 67 $$
$$ c = \sqrt{67} \approx 8{,}19 $$
$$ A = \frac{1}{2} \cdot 7 \cdot 9 \cdot \sin 60° = \frac{63}{2} \cdot \frac{\sqrt{3}}{2} = \frac{63\sqrt{3}}{4} \approx 27{,}28 $$

**Resposta:** $c = \sqrt{67} \approx 8{,}19$; Área = $\frac{63\sqrt{3}}{4} \approx 27{,}28$.

**12.** (Navegação) Um navio parte de um porto e navega 30 km na direção N $45°$ E, depois 40 km na direção S $45°$ E. A que distância e em que direção está o navio do porto?

Componente Leste: $30\sin 45° + 40\sin 45° = 70 \cdot \frac{\sqrt{2}}{2} = 35\sqrt{2} \approx 49{,}50$ km
Componente Norte: $30\cos 45° - 40\cos 45° = -10 \cdot \frac{\sqrt{2}}{2} = -5\sqrt{2} \approx -7{,}07$ km (7,07 km para sul)

$$ d = \sqrt{(35\sqrt{2})^2 + (5\sqrt{2})^2} = \sqrt{2450 + 50} = \sqrt{2500} = 50 \text{ km} $$

$$ \tan \theta = \frac{49{,}50}{7{,}07} = 7 \implies \theta = \arctan(7) \approx 81{,}87° \text{ a leste do sul} $$

Direção: S $81{,}87°$ E (aproximadamente S $82°$ E).

**Resposta:** 50 km na direção S $82°$ E (ou aproximadamente Leste).

---

### Nível 3 — Desafio (Integração e Raciocínio Avançado)

**13.** (Aplicação) A altura das marés em um porto pode ser modelada por $h(t) = 2\sin\left(\frac{\pi t}{6}\right) + 3$, onde $h$ é em metros e $t$ em horas ($t = 0$ é meia-noite). Determine:
(a) A maré alta e a maré baixa (altura)
(b) O período das marés (em horas)
(c) Os horários da primeira maré alta e da primeira maré baixa após meia-noite

**(a)** Amplitude = 2, média = 3.
Maré alta: $3 + 2 = 5$ m
Maré baixa: $3 - 2 = 1$ m

**(b)** Período = $\frac{2\pi}{\pi/6} = 12$ horas

**(c)** Maré alta: $\sin\left(\frac{\pi t}{6}\right) = 1 \implies \frac{\pi t}{6} = \frac{\pi}{2} \implies t = 3$ h (3:00)
Maré baixa: $\sin\left(\frac{\pi t}{6}\right) = -1 \implies \frac{\pi t}{6} = \frac{3\pi}{2} \implies t = 9$ h (9:00)

**Resposta:** (a) Alta = 5 m, Baixa = 1 m; (b) 12 h; (c) Alta às 3:00, Baixa às 9:00.

**14.** (Vestibular) Num triângulo, $a = 8$, $b = 10$, $c = 12$. Determine:
(a) Os três ângulos
(b) A área
(c) O raio da circunferência circunscrita $R$
(d) O raio da circunferência inscrita $r$

**(a)**
$$ \cos A = \frac{100 + 144 - 64}{2 \cdot 10 \cdot 12} = \frac{180}{240} = 0{,}75 \implies A = \arccos(0{,}75) \approx 41{,}41° $$
$$ \cos B = \frac{64 + 144 - 100}{2 \cdot 8 \cdot 12} = \frac{108}{192} = 0{,}5625 \implies B = \arccos(0{,}5625) \approx 55{,}77° $$
$$ C = 180° - 41{,}41° - 55{,}77° \approx 82{,}82° $$

**(b)** Usando Fórmula de Herão:
$$ p = 15, \quad A = \sqrt{15 \cdot 7 \cdot 5 \cdot 3} = \sqrt{1575} = 15\sqrt{7} \approx 39{,}69 $$

**(c)** $R = \frac{abc}{4A} = \frac{8 \cdot 10 \cdot 12}{4 \cdot 15\sqrt{7}} = \frac{960}{60\sqrt{7}} = \frac{16}{\sqrt{7}} = \frac{16\sqrt{7}}{7} \approx 6{,}05$

**(d)** $r = \frac{A}{p} = \frac{15\sqrt{7}}{15} = \sqrt{7} \approx 2{,}65$

**Resposta:** (a) $A \approx 41{,}41°$, $B \approx 55{,}77°$, $C \approx 82{,}82°$; (b) $15\sqrt{7}$; (c) $\frac{16\sqrt{7}}{7}$; (d) $\sqrt{7}$.

**15.** (Desafio) Prove a identidade: $\tan x + \tan y + \tan z = \tan x \tan y \tan z$ quando $x + y + z = \pi$ (e nenhum ângulo é múltiplo de $\frac{\pi}{2}$).

**Demonstração:**
$$ x + y = \pi - z $$
$$ \tan(x + y) = \tan(\pi - z) = -\tan z $$

$$ \frac{\tan x + \tan y}{1 - \tan x \tan y} = -\tan z $$
$$ \tan x + \tan y = -\tan z (1 - \tan x \tan y) $$
$$ \tan x + \tan y = -\tan z + \tan x \tan y \tan z $$
$$ \tan x + \tan y + \tan z = \tan x \tan y \tan z $$

**Resposta:** Demonstrado.

**16.** (Olimpíada) Se $\sin x + \cos x = \frac{1}{2}$, determine $\sin^3 x + \cos^3 x$.

$$ (\sin x + \cos x)^2 = \frac{1}{4} = \sin^2 x + \cos^2 x + 2\sin x \cos x = 1 + 2\sin x \cos x $$
$$ 2\sin x \cos x = -\frac{3}{4} \implies \sin x \cos x = -\frac{3}{8} $$

$$ \sin^3 x + \cos^3 x = (\sin x + \cos x)(\sin^2 x - \sin x \cos x + \cos^2 x) $$
$$ = \frac{1}{2} \left(1 - \left(-\frac{3}{8}\right)\right) = \frac{1}{2} \cdot \frac{11}{8} = \frac{11}{16} $$

**Resposta:** $11/16$.

---
**Fim — Problemas de Revisão (Trigonometria)**
