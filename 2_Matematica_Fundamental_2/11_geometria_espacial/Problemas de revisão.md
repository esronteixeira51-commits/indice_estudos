# Problemas de Revisão — Geometria Espacial

Este arquivo reúne problemas integrados que envolvem múltiplos conceitos de geometria espacial: poliedros, prismas, pirâmides, cilindros, cones e esferas. Os problemas exigem combinação de técnicas, interpretação de figuras e raciocínio espacial avançado.

## Revisão de Fórmulas-Chave

### Poliedros
- Fórmula de Euler: $V - A + F = 2$
- Pirâmide: $V = \frac{1}{3} A_b \cdot h$

### Prismas e Cilindros
- Prisma: $V = A_b \cdot h$, $A_t = A_l + 2A_b$
- Cilindro: $V = \pi r^2 h$, $A_l = 2\pi r h$, $A_t = 2\pi r(r + h)$

### Pirâmides e Cones
- Pirâmide: $V = \frac{1}{3} A_b \cdot h$, $A_l = \frac{1}{2} \cdot 2p \cdot a_p$
- Cone: $V = \frac{1}{3} \pi r^2 h$, $A_l = \pi r g$, $g = \sqrt{r^2 + h^2}$

### Esferas
- Área: $A = 4\pi r^2$
- Volume: $V = \frac{4}{3} \pi r^3$
- Semiesfera: $A = 3\pi r^2$, $V = \frac{2}{3} \pi r^3$

## Problemas

### Nível 1 — Básico (Revisão)

**1.** Um cubo tem aresta 5 cm. Determine sua diagonal, área total e volume.

$$ d = 5\sqrt{3} \approx 8{,}66 \text{ cm} $$
$$ A_t = 6 \cdot 25 = 150 \text{ cm}^2 $$
$$ V = 125 \text{ cm}^3 $$

**Resposta:** Diagonal = $5\sqrt{3}$ cm; $A_t = 150$ cm$^2$; $V = 125$ cm$^3$.

**2.** Um cilindro circular reto tem raio 4 cm e altura 10 cm. Determine sua área lateral e volume.

$$ A_l = 2\pi \cdot 4 \cdot 10 = 80\pi \approx 251{,}33 \text{ cm}^2 $$
$$ V = \pi \cdot 16 \cdot 10 = 160\pi \approx 502{,}65 \text{ cm}^3 $$

**Resposta:** $A_l = 80\pi$ cm$^2$; $V = 160\pi$ cm$^3$.

**3.** Uma pirâmide quadrangular regular tem base de lado 6 cm e altura 4 cm. Determine sua área total e volume.

$$ A_b = 36 \text{ cm}^2 $$
$$ a_p = \sqrt{4^2 + 3^2} = 5 \text{ cm} $$
$$ A_l = 2 \cdot 6 \cdot 5 = 60 \text{ cm}^2 $$
$$ A_t = 96 \text{ cm}^2 $$
$$ V = \frac{36 \cdot 4}{3} = 48 \text{ cm}^3 $$

**Resposta:** $A_t = 96$ cm$^2$; $V = 48$ cm$^3$.

**4.** Um cone circular reto tem raio 6 cm e altura 8 cm. Determine sua geratriz, área lateral e volume.

$$ g = \sqrt{36 + 64} = 10 \text{ cm} $$
$$ A_l = \pi \cdot 6 \cdot 10 = 60\pi \approx 188{,}50 \text{ cm}^2 $$
$$ V = \frac{1}{3} \cdot 36\pi \cdot 8 = 96\pi \approx 301{,}59 \text{ cm}^3 $$

**Resposta:** $g = 10$ cm; $A_l = 60\pi$ cm$^2$; $V = 96\pi$ cm$^3$.

**5.** Uma esfera tem raio 6 cm. Determine sua área superficial e volume.

$$ A = 4\pi \cdot 36 = 144\pi \approx 452{,}39 \text{ cm}^2 $$
$$ V = \frac{4}{3}\pi \cdot 216 = 288\pi \approx 904{,}78 \text{ cm}^3 $$

**Resposta:** $A = 144\pi$ cm$^2$; $V = 288\pi$ cm$^3$.

---

### Nível 2 — Intermediário (Aplicação)

**6.** Uma caixa d'água tem formato de paralelepípedo reto com dimensões $2 \times 3 \times 4$ m. Quantos litros de água ela armazena quando cheia? Se a água chega a apenas 2,5 m de altura, quantos litros há na caixa?

$$ V_{cheia} = 2 \cdot 3 \cdot 4 = 24 \text{ m}^3 = 24.000 \text{ litros} $$

Se altura = 2,5 m (e a base é $2 \times 3$):
$$ V = 2 \cdot 3 \cdot 2{,}5 = 15 \text{ m}^3 = 15.000 \text{ litros} $$

**Resposta:** Cheia: 24.000 litros. Com 2,5 m: 15.000 litros.

**7.** Um silo tem formato de cilindro com um cone na parte superior. O cilindro tem raio 3 m e altura 8 m. O cone tem mesma base e altura 4 m. Determine a capacidade total do silo em litros.

$$ V_{cil} = \pi \cdot 9 \cdot 8 = 72\pi \text{ m}^3 $$
$$ V_{cone} = \frac{1}{3} \cdot \pi \cdot 9 \cdot 4 = 12\pi \text{ m}^3 $$
$$ V_{total} = 84\pi \approx 263{,}89 \text{ m}^3 = 263.890 \text{ litros} $$

**Resposta:** $84\pi$ m$^3$ $\approx$ 263.890 litros.

**8.** Uma pirâmide hexagonal regular e um prisma hexagonal regular têm a mesma base e mesma altura. Se o volume do prisma é 180 cm$^3$, determine a área lateral da pirâmide sabendo que seu apótema é 5 cm.

$$ V_{prisma} = A_b \cdot h = 180 \text{ cm}^3 $$
$$ V_{pirâmide} = \frac{A_b \cdot h}{3} = 60 \text{ cm}^3 $$

$$ A_b = \frac{180}{h} $$

Para hexágono regular: $A_b = \frac{3L^2\sqrt{3}}{2}$ e $2p = 6L$.

$$ A_l = \frac{1}{2} \cdot 6L \cdot 5 = 15L $$

Precisamos encontrar $L$. Como $A_b = \frac{3L^2\sqrt{3}}{2} = \frac{180}{h}$, precisamos de $h$.

Do volume da pirâmide: $A_b \cdot h = 180 \implies A_b = \frac{180}{h}$.

Também: $a_p^2 = h^2 + a_b^2 \implies 25 = h^2 + \left(\frac{L\sqrt{3}}{2}\right)^2 = h^2 + \frac{3L^2}{4}$.

De $A_b = \frac{3L^2\sqrt{3}}{2} = \frac{180}{h}$: $L^2 = \frac{120}{h\sqrt{3}} = \frac{40\sqrt{3}}{h}$.

Substituindo: $25 = h^2 + \frac{3}{4} \cdot \frac{40\sqrt{3}}{h} = h^2 + \frac{30\sqrt{3}}{h}$.

$$ h^2 + \frac{30\sqrt{3}}{h} = 25 $$

Multiplicando por $h$: $h^3 + 30\sqrt{3} = 25h$.

Tentando $h = 3$: $27 + 30\sqrt{3} \approx 27 + 51{,}96 = 78{,}96 \neq 75$.

Tentando $h = 2\sqrt{3} \approx 3{,}46$: $(2\sqrt{3})^3 + 30\sqrt{3} = 24\sqrt{3} + 30\sqrt{3} = 54\sqrt{3} \approx 93{,}53$ e $25 \cdot 2\sqrt{3} = 50\sqrt{3} \approx 86{,}60$. Não.

Tentando $h = \sqrt{3}$: $3\sqrt{3} + 30\sqrt{3} = 33\sqrt{3} \approx 57{,}16$ e $25\sqrt{3} \approx 43{,}30$. Não.

Vamos resolver numericamente: $h^3 - 25h + 51{,}96 = 0$.

Para $h = 2$: $8 - 50 + 51{,}96 = 9{,}96$.
Para $h = 2{,}5$: $15{,}625 - 62{,}5 + 51{,}96 = 5{,}085$.
Para $h = 3$: $27 - 75 + 51{,}96 = 3{,}96$.
Para $h = 3{,}5$: $42{,}875 - 87{,}5 + 51{,}96 = 7{,}335$.

Hmm, o valor muda de sinal? Para $h = 2$: positivo. Para $h = 3$: positivo. Verificando $h = 4$: $64 - 100 + 51{,}96 = 15{,}96$ (positivo). $h = 1$: $1 - 25 + 51{,}96 = 27{,}96$ (positivo). Não há raiz positiva real? Verificando a derivada: $3h^2 - 25 = 0 \implies h = \sqrt{25/3} \approx 2{,}89$. Mínimo em $h \approx 2{,}89$: $(2{,}89)^3 - 25(2{,}89) + 51{,}96 = 24{,}1 - 72{,}25 + 51{,}96 = 3{,}81$ (positivo). Não há raiz real positiva.

Isso significa que os dados são inconsistentes. Vamos simplificar o problema: seja $h = 3$ cm e $a_p = 5$ cm.

$$ a_b = \sqrt{25 - 9} = 4 \text{ cm} $$
$$ \frac{L\sqrt{3}}{2} = 4 \implies L = \frac{8}{\sqrt{3}} = \frac{8\sqrt{3}}{3} \text{ cm} $$
$$ A_b = \frac{3}{2} \cdot \frac{64 \cdot 3}{9} = \frac{3}{2} \cdot \frac{64}{3} = 32 \text{ cm}^2 $$
$$ A_b \cdot h = 32 \cdot 3 = 96 \neq 180 $$

Não funciona. Vamos ajustar: seja $V_{prisma} = 180$ e $a_p = 5$.

Se $h = 4$: $A_b = 45$ cm$^2$.
$a_b = \sqrt{25 - 16} = 3$ cm.
$\frac{L\sqrt{3}}{2} = 3 \implies L = 2\sqrt{3}$ cm.
$A_b = \frac{3 \cdot 12 \cdot \sqrt{3}}{2} = 18\sqrt{3} \approx 31{,}18 \neq 45$.

Se $h = 4$ e $a_p = 5$ com $A_b = 45$ não dá hexágono regular. Vamos recalcular com $A_b = 45$:
$\frac{3L^2\sqrt{3}}{2} = 45 \implies L^2 = \frac{30}{\sqrt{3}} = 10\sqrt{3} \approx 17{,}32$.
$a_b = \frac{L\sqrt{3}}{2} = \frac{\sqrt{10\sqrt{3}} \cdot \sqrt{3}}{2} \approx \frac{4{,}16 \cdot 1{,}73}{2} \approx 3{,}60$.
$a_p^2 = h^2 + a_b^2 = 16 + 12{,}96 = 28{,}96 \approx 29 \neq 25$.

Vamos reformular o problema com dados consistentes. Seja $a_p = 5$ cm, $h = 4$ cm, e $a_b = 3$ cm (dá $L = 2\sqrt{3}$ cm e $A_b = 18\sqrt{3}$ cm$^2$).

$V_{prisma} = 18\sqrt{3} \cdot 4 = 72\sqrt{3} \approx 124{,}7$ cm$^3$.

Vamos usar $V_{prisma} = 72\sqrt{3}$ cm$^3$ no problema.

**Reformulado:** Uma pirâmide hexagonal regular e um prisma hexagonal regular têm a mesma base e mesma altura $h = 4$ cm. Se o volume do prisma é $72\sqrt{3}$ cm$^3$, determine a área lateral da pirâmide sabendo que seu apótema é 5 cm.

$$ A_b = \frac{72\sqrt{3}}{4} = 18\sqrt{3} \text{ cm}^2 $$
$$ A_l = \frac{1}{2} \cdot 6L \cdot 5 = 15L $$

De $A_b = \frac{3L^2\sqrt{3}}{2} = 18\sqrt{3}$: $L^2 = 12 \implies L = 2\sqrt{3}$ cm.
$$ A_l = 15 \cdot 2\sqrt{3} = 30\sqrt{3} \approx 51{,}96 \text{ cm}^2 $$

**Resposta:** $30\sqrt{3}$ cm$^2$ $\approx 51{,}96$ cm$^2$.

**9.** Uma esfera de raio 5 cm está inscrita num cubo. Determine:
(a) A aresta do cubo
(b) A área total do cubo
(c) O volume entre o cubo e a esfera (espaço vazio)

**(a)** $a = 2r = 10$ cm
**(b)** $A_t = 6 \cdot 100 = 600$ cm$^2$
**(c)** $V_{cub} = 1000$ cm$^3$, $V_{esf} = \frac{4}{3}\pi \cdot 125 = \frac{500\pi}{3} \approx 523{,}60$ cm$^3$
$V_{vazio} = 1000 - \frac{500\pi}{3} \approx 476{,}40$ cm$^3$

**Resposta:** (a) 10 cm; (b) 600 cm$^2$; (c) $1000 - \frac{500\pi}{3}$ cm$^3$ $\approx 476{,}40$ cm$^3$.

**10.** Uma urna tem formato de tronco de cone com raios 4 cm e 2 cm, e altura 6 cm. Se está cheia de areia até a borda, e a areia pesa 1,5 g/cm$^3$, qual o peso total da areia?

$$ V = \frac{\pi \cdot 6}{3}(16 + 4 + 8) = 2\pi \cdot 28 = 56\pi \approx 175{,}93 \text{ cm}^3 $$
$$ P = 175{,}93 \cdot 1{,}5 \approx 263{,}89 \text{ g} $$

**Resposta:** $56\pi$ cm$^3$ de areia $\approx$ 263,9 g.

---

### Nível 3 — Desafio (Integração e Raciocínio Avançado)

**11.** (Olimpíada) Um tetraedro regular tem aresta $a$. Determine o raio da esfera inscrita (tangencia todas as faces) e o raio da esfera circunscrita (passa por todos os vértices).

**Raio da esfera circunscrita:**
O centro do tetraedro equidista dos vértices. A distância do centro a um vértice é:
$$ R = \frac{a\sqrt{6}}{4} $$

**Raio da esfera inscrita:**
O centro equidista das faces. A distância do centro a uma face é:
$$ r = \frac{a\sqrt{6}}{12} = \frac{R}{3} $$

**Razão:**
$$ \frac{R}{r} = 3 $$

**Resposta:** $R = \frac{a\sqrt{6}}{4}$; $r = \frac{a\sqrt{6}}{12}$; Razão $R/r = 3$.

**12.** (ENEM-style) Uma fábrica produz latas cilíndricas de raio 5 cm e altura 12 cm. Para reduzir custo, a fábrica decide manter o volume mas usar a forma que minimiza a área superficial (para menos material). Se pudessem usar qualquer forma, qual seria o raio ideal? (Dica: para cilindro de volume fixo, a área é minimizada quando $h = 2r$ — cilindro equilátero.)

Volume atual:
$$ V = \pi \cdot 25 \cdot 12 = 300\pi \text{ cm}^3 $$

Para cilindro equilátero com mesmo volume:
$$ V = 2\pi r^3 = 300\pi \implies r^3 = 150 \implies r = \sqrt[3]{150} \approx 5{,}31 \text{ cm} $$

$$ h = 2r = 2\sqrt[3]{150} \approx 10{,}62 \text{ cm} $$

**Resposta:** Raio ideal = $\sqrt[3]{150}$ cm $\approx 5{,}31$ cm; altura ideal = $2\sqrt[3]{150}$ cm $\approx 10{,}62$ cm.

**13.** (Vestibular) Uma esfera de raio $R$ é cortada por dois planos paralelos que distam $d$ do centro, um de cada lado, formando uma cunha esférica (o segmento entre os dois planos). Determine o volume desta cunha em função de $R$ e $d$, e a área da zona esférica (superfície lateral da cunha).

**Volume:**
O volume é a esfera menos dois segmentos esféricos. Cada segmento tem altura $h = R - d$.

$$ V_{segmento} = \frac{\pi (R-d)^2}{3}(3R - (R-d)) = \frac{\pi (R-d)^2}{3}(2R + d) $$

$$ V_{cunha} = \frac{4}{3}\pi R^3 - 2 \cdot \frac{\pi (R-d)^2}{3}(2R + d) $$

$$ = \frac{2\pi}{3}[2R^3 - (R-d)^2(2R + d)] $$

$$ = \frac{2\pi}{3}[2R^3 - (R^2 - 2Rd + d^2)(2R + d)] $$

$$ = \frac{2\pi}{3}[2R^3 - (2R^3 + R^2d - 4R^2d - 2Rd^2 + 2Rd^2 + d^3)] $$

$$ = \frac{2\pi}{3}[2R^3 - 2R^3 + 3R^2d - d^3] $$

$$ = \frac{2\pi}{3}(3R^2d - d^3) = \frac{2\pi d}{3}(3R^2 - d^2) $$

**Área da zona esférica:**
$$ A_{zona} = 2\pi R \cdot (2d) = 4\pi R d $$

> **Nota:** A área da zona esférica depende apenas de $R$ e da distância entre os planos ($2d$), não da posição! (Teorema de Arquimedes)

**Resposta:** Volume = $\frac{2\pi d}{3}(3R^2 - d^2)$; Área da zona = $4\pi R d$.

**14.** (Aplicação real) Um arquiteto projeta um museu com uma cúpula semiesférica de raio 15 m sobre uma base cilíndrica de mesmo raio e altura 8 m. Determine:
(a) O volume total do edifício
(b) A área externa total (inclui cúpula + lateral do cilindro + base)
(c) Se a pintura externa custa R$ 25,00/m², qual o custo total?

**(a) Volume:**
$$ V_{semiesf} = \frac{2}{3}\pi \cdot 15^3 = \frac{2}{3}\pi \cdot 3375 = 2250\pi \text{ m}^3 $$
$$ V_{cil} = \pi \cdot 225 \cdot 8 = 1800\pi \text{ m}^3 $$
$$ V_{total} = 4050\pi \approx 12.731{,}85 \text{ m}^3 $$

**(b) Área externa:**
$$ A_{cúpula} = 2\pi \cdot 15^2 = 450\pi \text{ m}^2 \quad \text{(metade da superfície esférica)} $$
$$ A_{lateral cil} = 2\pi \cdot 15 \cdot 8 = 240\pi \text{ m}^2 $$
$$ A_{base} = \pi \cdot 15^2 = 225\pi \text{ m}^2 $$
$$ A_{total} = 450\pi + 240\pi + 225\pi = 915\pi \approx 2873{,}88 \text{ m}^2 $$

**(c) Custo:**
$$ \text{Custo} = 915\pi \cdot 25 \approx 71.847{,}00 \text{ reais} $$

**Resposta:** (a) $4050\pi$ m$^3$; (b) $915\pi$ m$^2$; (c) R$ $22.875\pi$ $\approx$ R$ 71.847,00.

**15.** (Desafio de otimização) Um fabricante produz embalagens cilíndricas de volume fixo $V$. Determine a razão $h/r$ que minimiza o custo de material (área superficial). Prove que o cilindro equilátero ($h = 2r$) é a solução ideal e calcule a economia percentual comparado a um cilindro com $h = 4r$ e mesmo volume.

**Otimização:**
$$ V = \pi r^2 h \implies h = \frac{V}{\pi r^2} $$

$$ A = 2\pi r^2 + 2\pi r h = 2\pi r^2 + 2\pi r \cdot \frac{V}{\pi r^2} = 2\pi r^2 + \frac{2V}{r} $$

Derivando em relação a $r$:
$$ \frac{dA}{dr} = 4\pi r - \frac{2V}{r^2} = 0 $$
$$ 4\pi r = \frac{2V}{r^2} \implies 2\pi r^3 = V $$

Como $V = \pi r^2 h$:
$$ 2\pi r^3 = \pi r^2 h \implies h = 2r $$

**Economia:**
Para $h = 2r$ (ótimo): $A_{min} = 2\pi r^2 + 2\pi r(2r) = 6\pi r^2$.

Para $h = 4r$ (com mesmo volume $V = 2\pi r^3$):
Se $V = 2\pi r^3 = \pi r'^2 \cdot 4r' = 4\pi r'^3$, então $r'^3 = r^3/2$, $r' = r/\sqrt[3]{2}$.

$$ A = 2\pi r'^2 + 2\pi r' \cdot 4r' = 10\pi r'^2 = 10\pi \cdot \frac{r^2}{2^{2/3}} = \frac{10\pi r^2}{2^{2/3}} $$

$$ \frac{A_{h=4r}}{A_{min}} = \frac{10\pi r^2 / 2^{2/3}}{6\pi r^2} = \frac{10}{6 \cdot 2^{2/3}} = \frac{5}{3 \cdot 1{,}587} = \frac{5}{4{,}76} \approx 1{,}05 $$

Economia = $(1 - 1/1{,}05) \cdot 100\% \approx 4{,}8\%$.

Ou calculando numericamente: $A_{h=4r} \approx 1{,}05 \cdot A_{min}$. Economia $\approx 5\%$.

**Resposta:** Razão ótima = $h/r = 2$. Economia comparado a $h = 4r$ ≈ 5% de material.

---
**Fim — Problemas de Revisão (Geometria Espacial)**
