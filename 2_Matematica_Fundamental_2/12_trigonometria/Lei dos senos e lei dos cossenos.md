# Lei dos Senos e Lei dos Cossenos

Para triângulos **quaisquer** (não apenas retângulos), as **Lei dos Senos** e a **Lei dos Cossenos** generalizam a trigonometria, permitindo calcular lados e ângulos mesmo quando não temos um triângulo retângulo. São ferramentas fundamentais em topografia, navegação, engenharia, astronomia e física.

## Lei dos Senos

Em qualquer triângulo, a razão entre o comprimento de um lado e o seno do ângulo oposto é constante e igual ao diâmetro da circunferência circunscrita ao triângulo.

$$ \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R $$

Onde $R$ é o raio da circunferência circunscrita ao triângulo.

### Demonstração

Considere um triângulo qualquer inscrito num círculo de raio $R$. Traçando a altura do vértice $C$ ao lado $c$, dividimos o triângulo em dois triângulos retângulos. A altura $h = a \sin B = b \sin A$. Logo:
$$ \frac{a}{\sin A} = \frac{b}{\sin B} $$

Por simetria, todas as razões são iguais. Para mostrar que igualam $2R$, considere o triângulo inscrito num círculo. O ângulo $A$ é um ângulo inscrito que subtende o arco $a$. O ângulo central que subtende o mesmo arco mede $2A$. Se $R$ é o raio, a corda $a = 2R \sin A$ (porque metade da corda é $R \sin A$). Logo:
$$ \frac{a}{\sin A} = 2R $$

## Lei dos Cossenos (Fórmula de Pitágoras Generalizada)

Em qualquer triângulo:

$$ a^2 = b^2 + c^2 - 2bc \cos A $$
$$ b^2 = a^2 + c^2 - 2ac \cos B $$
$$ c^2 = a^2 + b^2 - 2ab \cos C $$

### Casos Especiais

- Se $A = 90°$: $\cos 90° = 0$, então $a^2 = b^2 + c^2$ (Pitágoras!)
- Se $A < 90°$: $\cos A > 0$, então $a^2 < b^2 + c^2$ (triângulo acutângulo em relação a $A$)
- Se $A > 90°$: $\cos A < 0$, então $a^2 > b^2 + c^2$ (triângulo obtusângulo em relação a $A$)

### Demonstração

Coloque o triângulo num sistema de coordenadas com $A$ na origem, $B$ no eixo $x$ a distância $c$, e $C$ em $(b\cos A, b\sin A)$. A distância $a$ entre $B$ e $C$:

$$ a^2 = (b\cos A - c)^2 + (b\sin A)^2 $$
$$ a^2 = b^2\cos^2 A - 2bc\cos A + c^2 + b^2\sin^2 A $$
$$ a^2 = b^2(\cos^2 A + \sin^2 A) + c^2 - 2bc\cos A $$
$$ a^2 = b^2 + c^2 - 2bc\cos A $$

## Fórmula da Área de um Triângulo Qualquer

$$ A = \frac{1}{2}ab\sin C = \frac{1}{2}bc\sin A = \frac{1}{2}ac\sin B $$

### Fórmula de Herão (com os três lados)

$$ A = \sqrt{p(p-a)(p-b)(p-c)} $$

Onde $p = \frac{a+b+c}{2}$ é o semiperímetro.

## Resolução de Triângulos

### Casos de Congruência (que determinam um triângulo único)

1. **LLL (3 lados):** Use Lei dos Cossenos para encontrar os ângulos.
2. **LAL (2 lados e ângulo entre eles):** Use Lei dos Cossenos para o 3º lado, depois Lei dos Senos para outros ângulos.
3. **ALA (2 ângulos e lado entre eles):** Use soma dos ângulos = $180°$ para o 3º ângulo, depois Lei dos Senos para os lados.
4. **LAA (2 ângulos e lado não entre eles):** Similar ao caso anterior.
5. **LLA (2 lados e ângulo não entre eles):** **Caso ambíguo** — pode haver 0, 1 ou 2 triângulos!

### Caso Ambíguo (LLA)

Dados $a$, $b$, e $A$ (ângulo oposto ao lado $a$), pode haver:
- **Nenhum triângulo:** se $a < b \sin A$ (o lado é muito curto para alcançar)
- **Um triângulo retângulo:** se $a = b \sin A$
- **Dois triângulos:** se $b \sin A < a < b$ (o lado $a$ pode "fechar" de duas maneiras)
- **Um triângulo:** se $a \geq b$

## Exemplos

### Exemplo 1: Lei dos Senos

Num triângulo, $a = 8$, $A = 30°$, $B = 45°$. Determine $b$ e $c$.

$$ C = 180° - 30° - 45° = 105° $$

$$ \frac{b}{\sin 45°} = \frac{8}{\sin 30°} = \frac{8}{0{,}5} = 16 $$
$$ b = 16 \cdot \sin 45° = 16 \cdot \frac{\sqrt{2}}{2} = 8\sqrt{2} \approx 11{,}31 $$

$$ c = 16 \cdot \sin 105° = 16 \cdot \sin(60° + 45°) = 16 \cdot \frac{\sqrt{6} + \sqrt{2}}{4} = 4(\sqrt{6} + \sqrt{2}) \approx 15{,}45 $$

**Resposta:** $b = 8\sqrt{2} \approx 11{,}31$; $c = 4(\sqrt{6} + \sqrt{2}) \approx 15{,}45$.

### Exemplo 2: Lei dos Cossenos

Num triângulo, $b = 5$, $c = 7$, $A = 60°$. Determine $a$.

$$ a^2 = 5^2 + 7^2 - 2 \cdot 5 \cdot 7 \cdot \cos 60° $$
$$ a^2 = 25 + 49 - 70 \cdot 0{,}5 = 74 - 35 = 39 $$
$$ a = \sqrt{39} \approx 6{,}24 $$

**Resposta:** $a = \sqrt{39} \approx 6{,}24$.

### Exemplo 3: Área

Num triângulo, $a = 6$, $b = 8$, $C = 45°$. Determine a área.

$$ A = \frac{1}{2} \cdot 6 \cdot 8 \cdot \sin 45° = 24 \cdot \frac{\sqrt{2}}{2} = 12\sqrt{2} \approx 16{,}97 $$

**Resposta:** $12\sqrt{2} \approx 16{,}97$.

### Exemplo 4: Ângulo pelo cosseno

Num triângulo, $a = 7$, $b = 8$, $c = 9$. Determine o ângulo $A$.

$$ \cos A = \frac{b^2 + c^2 - a^2}{2bc} = \frac{64 + 81 - 49}{2 \cdot 8 \cdot 9} = \frac{96}{144} = \frac{2}{3} $$
$$ A = \arccos\left(\frac{2}{3}\right) \approx 48{,}19° $$

**Resposta:** $A = \arccos(2/3) \approx 48{,}19°$.

### Exemplo 5: Caso ambíguo

Determine quantos triângulos existem com $a = 5$, $b = 8$, $A = 30°$.

$$ b \sin A = 8 \cdot 0{,}5 = 4 $$

Como $b \sin A = 4 < a = 5 < b = 8$: **dois triângulos**!

**Resposta:** Dois triângulos (caso ambíguo).

## Aplicações na Vida Real

- **Topografia:** medição de distâncias inacessíveis (triangulação), levantamento de terrenos
- **Navegação:** determinação de posição (GPS usa triangulação), rumos, distâncias
- **Engenharia:** cálculo de estruturas triangulares, treliças, pontes
- **Astronomia:** paralaxe, distâncias estelares, posição de corpos celestes
- **Física:** decomposição de vetores em qualquer direção, equilíbrio de forças
- **Arquitetura:** estruturas triangulares, telhados, escadas, rampas
- **Robótica:** cinemática inversa, posicionamento de braços robóticos
- **Medicina:** triangulação em imagens médicas, posicionamento cirúrgico
- **Jogos:** pathfinding, colisão, detecção de visão, raycasting
- **Oceanografia:** mapeamento do fundo do mar, posicionamento de navios

## Problemas

### Nível 1 — Básico

**1.** Num triângulo, $a = 10$, $A = 30°$, $B = 60°$. Determine $b$ e $c$.

$$ C = 90° $$
$$ \frac{b}{\sin 60°} = \frac{10}{\sin 30°} = 20 $$
$$ b = 20 \cdot \frac{\sqrt{3}}{2} = 10\sqrt{3} \approx 17{,}32 $$
$$ c = 20 \cdot \sin 90° = 20 $$

**Resposta:** $b = 10\sqrt{3} \approx 17{,}32$; $c = 20$.

**2.** Num triângulo, $b = 6$, $c = 8$, $A = 120°$. Determine $a$.

$$ a^2 = 36 + 64 - 2 \cdot 6 \cdot 8 \cdot \cos 120° = 100 - 96 \cdot (-0{,}5) = 100 + 48 = 148 $$
$$ a = \sqrt{148} = 2\sqrt{37} \approx 12{,}17 $$

**Resposta:** $a = 2\sqrt{37} \approx 12{,}17$.

**3.** Num triângulo, $a = 7$, $b = 9$, $C = 60°$. Determine a área.

$$ A = \frac{1}{2} \cdot 7 \cdot 9 \cdot \sin 60° = \frac{63}{2} \cdot \frac{\sqrt{3}}{2} = \frac{63\sqrt{3}}{4} \approx 27{,}28 $$

**Resposta:** $\frac{63\sqrt{3}}{4} \approx 27{,}28$.

**4.** Num triângulo, $a = 5$, $b = 7$, $c = 8$. Determine $\cos A$.

$$ \cos A = \frac{49 + 64 - 25}{2 \cdot 7 \cdot 8} = \frac{88}{112} = \frac{11}{14} $$

**Resposta:** $\frac{11}{14}$.

**5.** Determine quantos triângulos existem com $a = 4$, $b = 6$, $A = 30°$.

$$ b \sin A = 6 \cdot 0{,}5 = 3 $$
Como $a = 4 > 3$ e $a = 4 < 6$: **dois triângulos**.

**Resposta:** Dois triângulos.

### Nível 2 — Intermediário

**6.** (Topografia) Dois observadores estão a 500 m de distância. Ambos avistam uma torre. Do observador A, o ângulo entre a linha de visão para a torre e a linha para o observador B é $60°$. Do observador B, o ângulo correspondente é $75°$. Qual a distância de cada observador à torre?

$$ C = 180° - 60° - 75° = 45° $$
$$ \frac{a}{\sin 60°} = \frac{b}{\sin 75°} = \frac{500}{\sin 45°} = \frac{500}{\sqrt{2}/2} = 500\sqrt{2} \approx 707{,}11 $$

$$ a = 707{,}11 \cdot \sin 60° = 707{,}11 \cdot \frac{\sqrt{3}}{2} \approx 612{,}37 \text{ m} $$
$$ b = 707{,}11 \cdot \sin 75° = 707{,}11 \cdot \frac{\sqrt{6} + \sqrt{2}}{4} \approx 683{,}01 \text{ m} $$

**Resposta:** A: ≈ 612 m; B: ≈ 683 m.

**7.** Num triângulo, $a = 8$, $b = 10$, $c = 12$. Determine os três ângulos.

$$ \cos A = \frac{100 + 144 - 64}{2 \cdot 10 \cdot 12} = \frac{180}{240} = 0{,}75 \implies A \approx 41{,}41° $$
$$ \cos B = \frac{64 + 144 - 100}{2 \cdot 8 \cdot 12} = \frac{108}{192} = 0{,}5625 \implies B \approx 55{,}77° $$
$$ C = 180° - 41{,}41° - 55{,}77° \approx 82{,}82° $$

**Resposta:** $A \approx 41{,}41°$, $B \approx 55{,}77°$, $C \approx 82{,}82°$.

**8.** (Navegação) Um navio navega 40 km na direção N $30°$ E, depois 50 km na direção S $60°$ E. A que distância e em que direção está o navio do ponto de partida?

Componente Leste (x): $40 \sin 30° + 50 \sin 60° = 40 \cdot 0{,}5 + 50 \cdot \frac{\sqrt{3}}{2} = 20 + 25\sqrt{3} \approx 63{,}30$ km
Componente Norte (y): $40 \cos 30° - 50 \cos 60° = 40 \cdot \frac{\sqrt{3}}{2} - 50 \cdot 0{,}5 = 20\sqrt{3} - 25 \approx 9{,}64$ km

$$ d = \sqrt{63{,}30^2 + 9{,}64^2} \approx \sqrt{4006 + 93} \approx \sqrt{4099} \approx 64{,}03 \text{ km} $$
$$ \theta = \arctan\frac{63{,}30}{9{,}64} \approx 81{,}34° \text{ a leste do norte} $$

Direção: N $81{,}34°$ E (aproximadamente N $81°$ E).

**Resposta:** ≈ 64 km na direção N $81°$ E.

**9.** (Fórmula de Herão) Determine a área de um triângulo com lados 13, 14, 15.

$$ p = \frac{13 + 14 + 15}{2} = 21 $$
$$ A = \sqrt{21(21-13)(21-14)(21-15)} = \sqrt{21 \cdot 8 \cdot 7 \cdot 6} = \sqrt{7056} = 84 $$

**Resposta:** 84.

**10.** Prove que num triângulo qualquer, $\frac{a+b}{c} = \frac{\cos\frac{A-B}{2}}{\sin\frac{C}{2}}$.

**Demonstração:**
$$ a = 2R\sin A, \quad b = 2R\sin B, \quad c = 2R\sin C $$
$$ \frac{a+b}{c} = \frac{\sin A + \sin B}{\sin C} = \frac{2\sin\frac{A+B}{2}\cos\frac{A-B}{2}}{2\sin\frac{C}{2}\cos\frac{C}{2}} $$

Como $A + B = 180° - C$: $\frac{A+B}{2} = 90° - \frac{C}{2}$, então $\sin\frac{A+B}{2} = \cos\frac{C}{2}$.

$$ = \frac{2\cos\frac{C}{2}\cos\frac{A-B}{2}}{2\sin\frac{C}{2}\cos\frac{C}{2}} = \frac{\cos\frac{A-B}{2}}{\sin\frac{C}{2}} $$

**Resposta:** Demonstrado.

### Nível 3 — Desafio

**11.** (Distância estelar — paralaxe) Uma estrela é observada da Terra em dois pontos opostos da órbita terrestre (6 meses de diferença, base de 2 UA = $3 \cdot 10^8$ km). O ângulo de paralaxe (metade do ângulo de desvio) é $0{,}5''$ (0,5 segundos de arco). Determine a distância da estrela em anos-luz. (1 ano-luz ≈ $9{,}46 \cdot 10^{12}$ km, $1° = 3600''$.)

$$ \theta = 0{,}5'' = \frac{0{,}5}{3600}° = \frac{0{,}5}{3600} \cdot \frac{\pi}{180} \text{ rad} \approx 2{,}42 \cdot 10^{-6} \text{ rad} $$

Para ângulos pequenos: $\tan \theta \approx \theta$ (em radianos).
$$ d = \frac{1{,}5 \cdot 10^8}{2{,}42 \cdot 10^{-6}} \approx 6{,}20 \cdot 10^{13} \text{ km} $$
$$ \text{Anos-luz} = \frac{6{,}20 \cdot 10^{13}}{9{,}46 \cdot 10^{12}} \approx 6{,}55 \text{ anos-luz} $$

**Resposta:** Aproximadamente 6,55 anos-luz.

**12.** (Circuncírculo) Prove que a área de um triângulo é $A = \frac{abc}{4R}$, onde $R$ é o raio da circunferência circunscrita.

**Demonstração:**
$$ A = \frac{1}{2}bc\sin A $$

Pela Lei dos Senos: $\frac{a}{\sin A} = 2R \implies \sin A = \frac{a}{2R}$.

$$ A = \frac{1}{2}bc \cdot \frac{a}{2R} = \frac{abc}{4R} $$

**Resposta:** Demonstrado.

**13.** (Incircunferência) Prove que o raio $r$ da circunferência inscrita num triângulo é $r = \frac{A}{p}$, onde $A$ é a área e $p$ é o semiperímetro.

**Demonstração:**
O centro da circunferência inscrita é equidistante dos três lados. A área do triângulo é a soma das áreas dos três triângulos formados pelo incentro e cada lado:
$$ A = \frac{1}{2}ar + \frac{1}{2}br + \frac{1}{2}cr = \frac{r}{2}(a+b+c) = rp $$

Logo: $r = \frac{A}{p}$.

**Resposta:** Demonstrado.

---
**Fim — Lei dos Senos e Lei dos Cossenos**
