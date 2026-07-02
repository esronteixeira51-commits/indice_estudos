# Razões Trigonométricas no Triângulo Retângulo

A **trigonometria** estuda as relações entre ângulos e lados em triângulos, principalmente em triângulos retângulos. As três razões trigonométricas fundamentais — **seno**, **cosseno** e **tangente** — são ferramentas essenciais para resolver problemas de navegação, engenharia, arquitetura, física e incontáveis aplicações práticas.

## Definições no Triângulo Retângulo

Considere um triângulo retângulo com:
- Hipotenusa: $h$ (lado oposto ao ângulo reto)
- Cateto oposto ao ângulo $\theta$: $c_o$
- Cateto adjacente ao ângulo $\theta$: $c_a$

### Seno

O **seno** de um ângulo é a razão entre o cateto oposto e a hipotenusa:

$$ \sin \theta = \frac{\text{cateto oposto}}{\text{hipotenusa}} = \frac{c_o}{h} $$

### Cosseno

O **cosseno** de um ângulo é a razão entre o cateto adjacente e a hipotenusa:

$$ \cos \theta = \frac{\text{cateto adjacente}}{\text{hipotenusa}} = \frac{c_a}{h} $$

### Tangente

A **tangente** de um ângulo é a razão entre o cateto oposto e o cateto adjacente:

$$ \tan \theta = \frac{\text{cateto oposto}}{\text{cateto adjacente}} = \frac{c_o}{c_a} $$

### Relação Fundamental

$$ \tan \theta = \frac{\sin \theta}{\cos \theta} $$

## Identidade Fundamental da Trigonometria

$$ \sin^2 \theta + \cos^2 \theta = 1 $$

**Demonstração:** Pelo Teorema de Pitágoras: $c_o^2 + c_a^2 = h^2$. Dividindo por $h^2$:
$$ \frac{c_o^2}{h^2} + \frac{c_a^2}{h^2} = 1 \implies \sin^2 \theta + \cos^2 \theta = 1 $$

## Ângulos Notáveis

Os ângulos $30°$, $45°$ e $60°$ (ou $\frac{\pi}{6}$, $\frac{\pi}{4}$, $\frac{\pi}{6}$ rad) aparecem com frequência e possuem valores exatos:

| Ângulo | $30°$ ($\pi/6$) | $45°$ ($\pi/4$) | $60°$ ($\pi/3$) |
|--------|-----------------|-----------------|-----------------|
| **Seno** | $\frac{1}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ |
| **Cosseno** | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$ |
| **Tangente** | $\frac{\sqrt{3}}{3}$ | $1$ | $\sqrt{3}$ |

### Como Memorizar

Use o padrão numérico para seno:
$$ \sin 30° = \frac{\sqrt{1}}{2}, \quad \sin 45° = \frac{\sqrt{2}}{2}, \quad \sin 60° = \frac{\sqrt{3}}{2} $$

O cosseno segue a ordem inversa. A tangente é seno/cosseno.

## Razões Secundárias (Recíprocas)

| Razão | Definição | Identidade |
|-------|-----------|------------|
| **Secante** | $\sec \theta = \frac{h}{c_a} = \frac{1}{\cos \theta}$ | $= \frac{1}{\cos \theta}$ |
| **Cossecante** | $\csc \theta = \frac{h}{c_o} = \frac{1}{\sin \theta}$ | $= \frac{1}{\sin \theta}$ |
| **Cotangente** | $\cot \theta = \frac{c_a}{c_o} = \frac{1}{\tan \theta}$ | $= \frac{1}{\tan \theta}$ |

## Outras Identidades Importantes

$$ 1 + \tan^2 \theta = \sec^2 \theta $$
$$ 1 + \cot^2 \theta = \csc^2 \theta $$

## Exemplos

### Exemplo 1: Valor exato

Calcule $\sin 60° \cdot \cos 30° + \cos 60° \cdot \sin 30°$.

$$ = \frac{\sqrt{3}}{2} \cdot \frac{\sqrt{3}}{2} + \frac{1}{2} \cdot \frac{1}{2} $$
$$ = \frac{3}{4} + \frac{1}{4} = 1 $$

> **Observação:** Isso é a fórmula de $\sin(60° + 30°) = \sin 90° = 1$!

**Resposta:** 1.

### Exemplo 2: Triângulo retângulo

Num triângulo retângulo, a hipotenusa é 10 e um ângulo agudo é $30°$. Determine os catetos.

$$ c_o = 10 \cdot \sin 30° = 10 \cdot \frac{1}{2} = 5 $$
$$ c_a = 10 \cdot \cos 30° = 10 \cdot \frac{\sqrt{3}}{2} = 5\sqrt{3} \approx 8{,}66 $$

**Resposta:** Catetos: 5 e $5\sqrt{3}$.

### Exemplo 3: Encontrar o ângulo

Num triângulo retângulo, os catetos são 3 e 4. Determine os ângulos agudos (aproximados).

$$ \tan \alpha = \frac{3}{4} = 0{,}75 $$
$$ \alpha = \arctan(0{,}75) \approx 36{,}87° $$

$$ \tan \beta = \frac{4}{3} \approx 1{,}333 $$
$$ \beta = \arctan(1{,}333) \approx 53{,}13° $$

Verificação: $36{,}87° + 53{,}13° = 90°$ ✓

**Resposta:** $\approx 36{,}87°$ e $\approx 53{,}13°$.

### Exemplo 4: Identidade

Verifique que $\sin^2 45° + \cos^2 45° = 1$.

$$ \left(\frac{\sqrt{2}}{2}\right)^2 + \left(\frac{\sqrt{2}}{2}\right)^2 = \frac{2}{4} + \frac{2}{4} = 1 $$

**Resposta:** Verificado ✓.

## Aplicações na Vida Real

- **Topografia:** medir alturas de edifícios, montanhas, torres (ângulo de elevação)
- **Navegação:** determinar posição, distância ao horizonte, rumos de navegação
- **Engenharia:** inclinação de rampas, escadas, telhados, estradas
- **Arquitetura:** ângulos de telhado, escadas, escoramento, inclinação
- **Astronomia:** distâncias estelares, paralaxe, coordenadas celestes
- **Física:** decomposição de vetores, forças, movimento em planos inclinados
- **Música:** análise de ondas sonoras, frequências, harmônicos
- **Medicina:** imagens médicas (tomografia, ultrassom), angiografia
- **Jogos:** câmera 3D, rotação, perspectiva, direção de projéteis
- **Eletrônica:** análise de sinais alternados (CA), fasores, circuitos AC

## Problemas

### Nível 1 — Básico

**1.** Num triângulo retângulo, a hipotenusa é 13 e um cateto é 5. Determine $\sin \theta$, $\cos \theta$ e $\tan \theta$ para o ângulo oposto ao cateto 5.

$$ \text{Outro cateto} = \sqrt{13^2 - 5^2} = \sqrt{169 - 25} = \sqrt{144} = 12 $$

$$ \sin \theta = \frac{5}{13}, \quad \cos \theta = \frac{12}{13}, \quad \tan \theta = \frac{5}{12} $$

**Resposta:** $\sin \theta = 5/13$, $\cos \theta = 12/13$, $\tan \theta = 5/12$.

**2.** Calcule: $\sin 30° + \cos 60° + \tan 45°$.

$$ \frac{1}{2} + \frac{1}{2} + 1 = 2 $$

**Resposta:** 2.

**3.** Se $\sin \theta = 3/5$, determine $\cos \theta$ e $\tan \theta$ (supondo $\theta$ agudo).

$$ \cos^2 \theta = 1 - \frac{9}{25} = \frac{16}{25} \implies \cos \theta = \frac{4}{5} $$
$$ \tan \theta = \frac{3/5}{4/5} = \frac{3}{4} $$

**Resposta:** $\cos \theta = 4/5$, $\tan \theta = 3/4$.

**4.** Num triângulo retângulo, um cateto é 8 e o ângulo oposto a ele é $30°$. Determine a hipotenusa e o outro cateto.

$$ \sin 30° = \frac{8}{h} \implies h = \frac{8}{0{,}5} = 16 $$
$$ c_a = 16 \cdot \cos 30° = 16 \cdot \frac{\sqrt{3}}{2} = 8\sqrt{3} \approx 13{,}86 $$

**Resposta:** Hipotenusa = 16; outro cateto = $8\sqrt{3}$.

**5.** Verifique se $\sin^2 60° + \cos^2 30° = 2$.

$$ \left(\frac{\sqrt{3}}{2}\right)^2 + \left(\frac{\sqrt{3}}{2}\right)^2 = \frac{3}{4} + \frac{3}{4} = \frac{6}{4} = 1{,}5 \neq 2 $$

**Resposta:** Não, o valor é $1{,}5$ (ou $3/2$). Note que $\sin^2 \theta + \cos^2 \theta = 1$ é para o **mesmo** ângulo, não para ângulos diferentes.

### Nível 2 — Intermediário

**6.** Uma escada de 5 m está apoiada numa parede formando um ângulo de $60°$ com o chão. A que altura a escada toca a parede? A que distância da parede está a base da escada?

$$ h = 5 \cdot \sin 60° = 5 \cdot \frac{\sqrt{3}}{2} = \frac{5\sqrt{3}}{2} \approx 4{,}33 \text{ m} $$
$$ d = 5 \cdot \cos 60° = 5 \cdot \frac{1}{2} = 2{,}5 \text{ m} $$

**Resposta:** Altura ≈ 4,33 m; distância = 2,5 m.

**7.** De um ponto no solo, o topo de uma torre é visto sob um ângulo de elevação de $30°$. Afastando-se 20 m, o ângulo passa a ser $15°$. Qual a altura da torre? (Use: $\tan 15° = 2 - \sqrt{3} \approx 0{,}268$.)

Seja $h$ a altura e $x$ a distância inicial.
$$ \tan 30° = \frac{h}{x} \implies x = \frac{h}{\tan 30°} = h\sqrt{3} $$
$$ \tan 15° = \frac{h}{x + 20} = \frac{h}{h\sqrt{3} + 20} $$

$$ h = (h\sqrt{3} + 20) \cdot (2 - \sqrt{3}) $$
$$ h = h\sqrt{3}(2 - \sqrt{3}) + 20(2 - \sqrt{3}) $$
$$ h = h(2\sqrt{3} - 3) + 20(2 - \sqrt{3}) $$
$$ h - h(2\sqrt{3} - 3) = 20(2 - \sqrt{3}) $$
$$ h(1 - 2\sqrt{3} + 3) = 20(2 - \sqrt{3}) $$
$$ h(4 - 2\sqrt{3}) = 20(2 - \sqrt{3}) $$
$$ h = \frac{20(2 - \sqrt{3})}{2(2 - \sqrt{3})} = 10 \text{ m} $$

**Resposta:** 10 m.

**8.** Simplifique: $\frac{\sin 30° \cdot \cos 60°}{\tan 45°} + \sin^2 45°$.

$$ = \frac{\frac{1}{2} \cdot \frac{1}{2}}{1} + \left(\frac{\sqrt{2}}{2}\right)^2 = \frac{1}{4} + \frac{2}{4} = \frac{3}{4} $$

**Resposta:** $3/4$.

**9.** Se $\tan \theta = 2$ e $\theta$ é agudo, determine $\sin \theta$ e $\cos \theta$.

$$ \tan \theta = 2 \implies \frac{\sin \theta}{\cos \theta} = 2 \implies \sin \theta = 2\cos \theta $$

$$ \sin^2 \theta + \cos^2 \theta = 1 $$
$$ 4\cos^2 \theta + \cos^2 \theta = 1 \implies 5\cos^2 \theta = 1 $$
$$ \cos \theta = \frac{1}{\sqrt{5}} = \frac{\sqrt{5}}{5} $$
$$ \sin \theta = \frac{2\sqrt{5}}{5} $$

**Resposta:** $\sin \theta = \frac{2\sqrt{5}}{5}$, $\cos \theta = \frac{\sqrt{5}}{5}$.

**10.** Num triângulo retângulo, um ângulo agudo $\alpha$ satisfaz $\sin \alpha = 2\cos \alpha$. Determine $\sin \alpha$, $\cos \alpha$ e $\tan \alpha$.

$$ \sin \alpha = 2\cos \alpha \implies \tan \alpha = 2 $$

Igual ao exemplo anterior: $\sin \alpha = \frac{2\sqrt{5}}{5}$, $\cos \alpha = \frac{\sqrt{5}}{5}$, $\tan \alpha = 2$.

**Resposta:** $\sin \alpha = \frac{2\sqrt{5}}{5}$, $\cos \alpha = \frac{\sqrt{5}}{5}$, $\tan \alpha = 2$.

### Nível 3 — Desafio

**11.** (Ângulo de elevação) De um ponto no solo, o topo de um prédio é visto sob um ângulo de elevação $\alpha$. Aproximando-se 30 m, o ângulo passa a ser $\beta$. Se $\tan \alpha = 1/2$ e $\tan \beta = 3/4$, determine a altura do prédio.

$$ \tan \alpha = \frac{h}{x} = \frac{1}{2} \implies x = 2h $$
$$ \tan \beta = \frac{h}{x - 30} = \frac{3}{4} $$

$$ \frac{h}{2h - 30} = \frac{3}{4} $$
$$ 4h = 6h - 90 $$
$$ 2h = 90 \implies h = 45 \text{ m} $$

**Resposta:** 45 m.

**12.** (Projeção) Prove que a projeção de um segmento de comprimento $L$ sobre uma reta que forma um ângulo $\theta$ com ele tem comprimento $L \cos \theta$.

**Demonstração:** Considere o segmento como hipotenusa de um triângulo retângulo onde a projeção é o cateto adjacente ao ângulo $\theta$.
$$ \cos \theta = \frac{\text{projeção}}{L} \implies \text{projeção} = L \cos \theta $$

**Resposta:** Demonstrado.

**13.** (Área de triângulo) Prove que a área de um triângulo com dois lados $a$ e $b$ e ângulo entre eles $\theta$ é $A = \frac{1}{2}ab\sin\theta$.

**Demonstração:** Considere o lado $b$ como base. A altura relativa a essa base é $h = a\sin\theta$ (pois $a$ é a hipotenusa e $h$ é o cateto oposto ao ângulo $\theta$ no triângulo retângulo formado).

$$ A = \frac{1}{2} \cdot \text{base} \cdot \text{altura} = \frac{1}{2} \cdot b \cdot a\sin\theta = \frac{1}{2}ab\sin\theta $$

**Resposta:** Demonstrado.

---
**Fim — Razões Trigonométricas no Triângulo Retângulo**
