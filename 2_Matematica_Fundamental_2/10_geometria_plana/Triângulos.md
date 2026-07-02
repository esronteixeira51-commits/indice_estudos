# Triângulos

O **triângulo** é o polígono mais simples e fundamental da geometria. Com três lados e três ângulos, é a base para toda a trigonometria e para muitas estruturas na engenharia e arquitetura. Neste arquivo, exploramos classificações, propriedades, congruência, semelhança, relações métricas e o Teorema de Pitágoras.

## Classificação dos Triângulos

### Por Lados

| Tipo | Definição | Propriedade |
|------|-----------|-------------|
| **Equilátero** | 3 lados iguais | 3 ângulos iguais a $60°$ cada |
| **Isósceles** | 2 lados iguais | Ângulos da base são iguais |
| **Escaleno** | 3 lados diferentes | 3 ângulos diferentes |

### Por Ângulos

| Tipo | Definição | Característica |
|------|-----------|----------------|
| **Acutângulo** | 3 ângulos agudos ($< 90°$) | Todos os ângulos $< 90°$ |
| **Retângulo** | 1 ângulo reto ($= 90°$) | Hipotenusa é o maior lado |
| **Obtusângulo** | 1 ângulo obtuso ($> 90°$) | O maior lado opõe-se ao ângulo obtuso |

> **Todo triângulo equilátero é acutângulo.**
> **Um triângulo pode ser isósceles e retângulo ao mesmo tempo.**

## Desigualdade Triangular

Em qualquer triângulo, a soma de dois lados quaisquer é **sempre maior** que o terceiro lado:

$$ a + b > c \quad a + c > b \quad b + c > a $$

**Consequência:** A diferença de dois lados é menor que o terceiro lado.

### Exemplo

Podemos formar um triângulo com lados 3, 4, 5?
$$ 3 + 4 > 5 \text{ ✓} \quad 3 + 5 > 4 \text{ ✓} \quad 4 + 5 > 3 \text{ ✓} $$
Sim! É um triângulo retângulo.

Podemos formar um triângulo com lados 2, 3, 6?
$$ 2 + 3 = 5 < 6 \text{ ✗} $$
Não! A soma dos dois menores não supera o maior.

## Soma dos Ângulos Internos

Em qualquer triângulo:

$$ \alpha + \beta + \gamma = 180° $$

## Congruência de Triângulos

Dois triângulos são **congruentes** quando têm os mesmos lados e ângulos (mesma forma e tamanho).

### Casos de Congruência

| Sigla | Condição | Significado |
|-------|----------|-------------|
| **LLL** | 3 lados iguais | 3 lados correspondentes congruentes |
| **LAL** | 2 lados e o ângulo entre eles | Lado-ângulo-lado |
| **ALA** | 1 lado e 2 ângulos adjacentes | Ângulo-lado-ângulo |
| **LAA** | 1 lado, 1 ângulo adjacente e 1 ângulo oposto | Lado-ângulo-ângulo |
| **AL (cateto-hipotenusa)** | Triângulos retângulos | Cateto e hipotenusa congruentes |

> **Não é caso de congruência:** AAA (ângulos iguais garantem semelhança, não congruência) e LLA (dois lados e um ângulo não adjacente — ambiguo).

## Semelhança de Triângulos

Dois triângulos são **semelhantes** quando têm a mesma forma (ângulos iguais), mas não necessariamente o mesmo tamanho. Os lados correspondentes são proporcionais.

$$ \frac{a}{a'} = \frac{b}{b'} = \frac{c}{c'} = k $$

Onde $k$ é a **razão de semelhança**.

### Casos de Semelhança

| Sigla | Condição | Significado |
|-------|----------|-------------|
| **AA** | 2 ângulos iguais | Se 2 ângulos são iguais, o 3º também é |
| **LAL** | 2 lados proporcionais e ângulo entre eles igual | Lado-ângulo-lado |
| **LLL** | 3 lados proporcionais | 3 lados em proporção |

## Relações Métricas no Triângulo Retângulo

Seja um triângulo retângulo com:
- Hipotenusa: $a$
- Catetos: $b$ e $c$
- Altura relativa à hipotenusa: $h$
- Projeções dos catetos sobre a hipotenusa: $m$ (de $b$) e $n$ (de $c$)

$$ m + n = a $$

### Relações

1. **Teorema de Pitágoras:**
$$ a^2 = b^2 + c^2 $$

2. **Cateto é média geométrica entre a hipotenusa e sua projeção:**
$$ b^2 = a \cdot m \quad \text{e} \quad c^2 = a \cdot n $$

3. **Altura é média geométrica entre as projeções:**
$$ h^2 = m \cdot n $$

4. **Área:**
$$ \text{Área} = \frac{b \cdot c}{2} = \frac{a \cdot h}{2} $$

5. **Relação entre catetos e hipotenusa:**
$$ b \cdot c = a \cdot h $$

## Teorema de Pitágoras

No triângulo retângulo, o quadrado da hipotenusa é igual à soma dos quadrados dos catetos:

$$ a^2 = b^2 + c^2 $$

### Triângulos Pitagóricos (Lados Inteiros)

Ternos pitagóricos primitivos: $(3, 4, 5)$, $(5, 12, 13)$, $(8, 15, 17)$, $(7, 24, 25)$, $(20, 21, 29)$

Múltiplos também são pitagóricos: $(6, 8, 10)$, $(9, 12, 15)$, etc.

### Consequências

- Diagonal do quadrado de lado $a$: $d = a\sqrt{2}$
- Diagonal do retângulo de lados $a$ e $b$: $d = \sqrt{a^2 + b^2}$
- Diagonal do cubo de aresta $a$: $d = a\sqrt{3}$

## Exemplos

### Exemplo 1: Classificação

Um triângulo tem lados 5, 5, 8. Classifique-o.

- Dois lados iguais → **isósceles**
- Verificar ângulos: $5^2 + 5^2 = 25 + 25 = 50 > 64 = 8^2$? Não, $50 < 64$.
- Como $a^2 > b^2 + c^2$ (sendo $a$ o maior lado), é **obtusângulo**.

**Resposta:** Isósceles obtusângulo.

### Exemplo 2: Semelhança

Dois triângulos têm ângulos $30°$, $60°$ e $90°$. Se o menor lado do primeiro é 4 e o menor lado do segundo é 6, qual a razão de semelhança?

- Razão $k = \frac{6}{4} = \frac{3}{2} = 1{,}5$

**Resposta:** $k = 1{,}5$ (o segundo é 1,5 vezes maior).

### Exemplo 3: Pitágoras

Um triângulo retângulo tem catetos 6 e 8. Qual a hipotenusa?

$$ a^2 = 6^2 + 8^2 = 36 + 64 = 100 \implies a = 10 $$

**Resposta:** Hipotenusa = 10.

### Exemplo 4: Relações métricas

Num triângulo retângulo, a hipotenusa é 10 e um cateto é 6. Determine o outro cateto, a altura e as projeções.

$$ b^2 + c^2 = 100 $$
$$ b = 6 \implies 36 + c^2 = 100 \implies c^2 = 64 \implies c = 8 $$

$$ \text{Área} = \frac{6 \cdot 8}{2} = 24 = \frac{10 \cdot h}{2} \implies h = 4{,}8 $$

$$ b^2 = a \cdot m \implies 36 = 10 \cdot m \implies m = 3{,}6 $$
$$ c^2 = a \cdot n \implies 64 = 10 \cdot n \implies n = 6{,}4 $$

Verificação: $m + n = 3{,}6 + 6{,}4 = 10 = a$ ✓

**Resposta:** Cateto = 8, altura = 4,8, projeções: 3,6 e 6,4.

## Aplicações na Vida Real

- **Engenharia:** treliças triangulares, estruturas de pontes (triângulo é rígido)
- **Arquitetura:** escadas, telhados, estruturas de suporte
- **Navegação:** triangulação, GPS, determinação de posição
- **Astronomia:** distâncias estelares, paralaxe (triângulo Terra-estrela-Sol)
- **Topografia:** medição de distâncias inacessíveis (indiretas)
- **Carpintaria:** esquadros, calços, montagem de estruturas
- **Jogos:** colisão, pathfinding, detecção de visão (triângulos de visão)
- **Computação gráfica:** malhas triangulares (meshes), renderização 3D
- **Física:** decomposição de vetores, forças em equilíbrio
- **Medicina:** triangulação em imagens médicas, posicionamento cirúrgico

## Problemas

### Nível 1 — Básico

**1.** Os lados de um triângulo medem 7, 8 e 15. Esse triângulo existe? Justifique.

$$ 7 + 8 = 15 \text{ (não é maior que 15, é igual!)} $$

**Resposta:** Não existe. A soma dos dois menores deve ser **estritamente maior** que o maior.

**2.** Um triângulo retângulo tem catetos 9 e 12. Determine a hipotenusa.

$$ a^2 = 9^2 + 12^2 = 81 + 144 = 225 \implies a = 15 $$

**Resposta:** Hipotenusa = 15.

**3.** Os ângulos de um triângulo são $50°$ e $60°$. Qual é o terceiro ângulo?

$$ 180° - 50° - 60° = 70° $$

**Resposta:** $70°$.

**4.** Um triângulo isósceles tem ângulo de vértice $40°$. Quais são os ângulos da base?

$$ 180° - 40° = 140° \implies \text{ângulos da base} = \frac{140°}{2} = 70° $$

**Resposta:** $70°$ cada.

**5.** Dois triângulos são semelhantes com razão $k = 3$. Se o primeiro tem lados 2, 3, 4, quais os lados do segundo?

$$ 2 \cdot 3 = 6, \quad 3 \cdot 3 = 9, \quad 4 \cdot 3 = 12 $$

**Resposta:** 6, 9, 12.

### Nível 2 — Intermediário

**6.** Um triângulo retângulo tem hipotenusa 25 e um cateto 7. Determine o outro cateto e a altura relativa à hipotenusa.

$$ b^2 = 25^2 - 7^2 = 625 - 49 = 576 \implies b = 24 $$

$$ \text{Área} = \frac{7 \cdot 24}{2} = 84 = \frac{25 \cdot h}{2} \implies h = \frac{168}{25} = 6{,}72 $$

**Resposta:** Cateto = 24, altura = 6,72.

**7.** Um triângulo equilátero tem lado 6. Determine sua altura e área.

$$ h^2 + 3^2 = 6^2 \implies h^2 = 36 - 9 = 27 \implies h = 3\sqrt{3} $$

$$ A = \frac{6 \cdot 3\sqrt{3}}{2} = 9\sqrt{3} $$

**Resposta:** Altura = $3\sqrt{3}$, Área = $9\sqrt{3}$.

**8.** A diagonal de um retângulo mede 13 e um lado mede 5. Quanto mede o outro lado?

$$ a^2 + 5^2 = 13^2 \implies a^2 = 169 - 25 = 144 \implies a = 12 $$

**Resposta:** 12.

**9.** Em um triângulo retângulo, a projeção de um cateto sobre a hipotenusa é 4 e a hipotenusa é 10. Determine o cateto e a altura.

$$ b^2 = a \cdot m = 10 \cdot 4 = 40 \implies b = \sqrt{40} = 2\sqrt{10} $$

$$ n = a - m = 10 - 4 = 6 $$
$$ h^2 = m \cdot n = 4 \cdot 6 = 24 \implies h = \sqrt{24} = 2\sqrt{6} $$

**Resposta:** Cateto = $2\sqrt{10}$, altura = $2\sqrt{6}$.

**10.** Dois triângulos são semelhantes. O primeiro tem perímetro 12 e o segundo 30. Se o maior lado do primeiro é 5, qual o maior lado do segundo?

$$ \text{Razão} = k = \frac{30}{12} = 2{,}5 $$
$$ \text{Maior lado do segundo} = 5 \cdot 2{,}5 = 12{,}5 $$

**Resposta:** 12,5.

### Nível 3 — Desafio

**11.** (Pitágoras generalizado) Num triângulo qualquer, vale a **Lei dos Cossenos**:
$$ a^2 = b^2 + c^2 - 2bc \cos A $$

Se $a = 7$, $b = 5$, $c = 8$, determine o ângulo $A$ (oposto ao lado $a$).

$$ 49 = 25 + 64 - 2 \cdot 5 \cdot 8 \cdot \cos A $$
$$ 49 = 89 - 80 \cos A $$
$$ 80 \cos A = 40 \implies \cos A = \frac{1}{2} \implies A = 60° $$

**Resposta:** $A = 60°$.

**12.** Um triângulo retângulo tem catetos $x$ e $x+1$, e hipotenusa $x+2$. Determine $x$ e os lados do triângulo.

$$ (x+2)^2 = x^2 + (x+1)^2 $$
$$ x^2 + 4x + 4 = x^2 + x^2 + 2x + 1 $$
$$ x^2 + 4x + 4 = 2x^2 + 2x + 1 $$
$$ 0 = x^2 - 2x - 3 $$
$$ (x-3)(x+1) = 0 \implies x = 3 \text{ (positivo)} $$

Lados: 3, 4, 5.

**Resposta:** $x = 3$. Lados: 3, 4, 5 (triângulo pitagórico clássico).

**13.** Um espelho está colocado na parede a uma altura de 1,5 m. Uma pessoa de 1,7 m de altura está a 2 m do espelho. Se a pessoa olha para o espelho, a que altura no espelho ela deve olhar para ver os próprios olhos? (Aproxime: os olhos estão a 1,6 m do chão.)

Usando triângulos semelhantes (a pessoa e sua imagem são simétricas em relação ao espelho):
- A pessoa está a 2 m do espelho, sua imagem está a 2 m "atrás" do espelho (total 4 m de distância entre pessoa e imagem).
- Os olhos da pessoa estão a 1,6 m do chão.
- O espelho está a 1,5 m do chão.

A pessoa deve olhar para um ponto no espelho tal que a linha de visão dos olhos até a imagem dos olhos passe pelo espelho.

Usando semelhança de triângulos:
- Triângulo formado pela pessoa, o espelho, e o ponto de reflexão.
- A pessoa está a 2 m do espelho, a imagem está a 2 m do outro lado (4 m total).
- Os olhos da pessoa estão a 1,6 m, a base da imagem está a 0 m.

Ponto no espelho = média ponderada: a altura no espelho é $(1{,}6 + 1{,}6)/2 = 1{,}6$ m? Não, isso é incorreto.

Correto: A pessoa vê sua imagem "atrás" do espelho. A imagem dos olhos está a 1,6 m de altura. Para que a pessoa veja seus olhos, o raio de luz vai dos olhos da pessoa, reflete no espelho, e vai para os olhos da pessoa.

Pela lei da reflexão, o ângulo de incidência = ângulo de reflexão. Isso implica que o ponto no espelho está na mesma altura dos olhos (1,6 m) se a pessoa estiver de pé. Mas o espelho começa a 1,5 m, então o ponto está a 1,6 m - 1,5 m = 0,1 m acima da base do espelho (ou seja, a pessoa deve olhar 10 cm acima da base do espelho, a 1,6 m do chão).

**Resposta:** A pessoa deve olhar a 1,6 m de altura (ou 10 cm acima da base do espelho, que está a 1,5 m).

---
**Fim — Triângulos**
