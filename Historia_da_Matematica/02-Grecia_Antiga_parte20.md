## 15. Apolônio de Perga — O Grande Geômetra das Cônicas

**Apolônio de Perga** (c. 262–190 a.C.) nasceu em Perga, na costa sul da atual Turquia, estudou em Alexandria e ensinou em Pérgamo — a única biblioteca que rivalizava com a de Alexandria. Leibniz escreveu que quem compreende Arquimedes e Apolônio admira menos os feitos dos mais notáveis homens de épocas posteriores. É uma afirmação forte. É verdadeira.

Sabe-se pouco sobre sua vida com certeza — a maior parte do que conhecemos vem dos prefácios dos próprios livros das *Cônicas*, e de títulos e resumos preservados por autores posteriores. Há algo contraintuitivo nessas fontes: na Antiguidade, Apolônio tornou-se famoso **primeiro por seu trabalho em astronomia**, e só depois por sua matemática — exatamente o inverso de como é lembrado hoje, quando praticamente ninguém o associa a contribuições astronômicas e todos o conhecem pelas cônicas (§15.8 mostrará por quê essa reputação original não era injustificada).

Sua obra prima, *Cônicas* (*Konika*), em oito livros, é o tratado mais avançado de geometria da Antiguidade — tão sofisticado que permaneceu incompreensível para a maioria dos leitores por séculos. Dos oito livros originais, sete sobreviveram: quatro em grego, três em tradução árabe do século IX. Apenas o oitavo está perdido. É difícil, para um leitor de hoje, compreender como Apolônio conseguiu descobrir e demonstrar centenas de teoremas belos e difíceis sem qualquer simbolismo algébrico moderno — mas conseguiu, e não há registro de nenhuma obra matemática grega posterior que se aproxime da complexidade ou do refinamento das *Cônicas*.

O que Apolônio fez com as cônicas foi o que Euclides fez com a geometria plana: tomou um corpo de conhecimento disperso — as seções de Menaecmo (§11.6), os trabalhos perdidos de Aristeu e do próprio Euclides — e o reorganizou com profundidade e generalidade sem precedente. Mas diferentemente de Euclides, Apolônio também descobriu resultados substancialmente novos.

---

### 15.1 As Três Curvas de Um Único Cone

Antes de Apolônio, as três curvas — elipse, parábola e hipérbole — eram obtidas de **três tipos diferentes de cone**:

- Um cone com ângulo reto no vértice, cortado perpendicularmente a um elemento: **parábola** (Menaecmo).
- Um cone acutângulo, cortado perpendicularmente: **elipse**.
- Um cone obtusângulo, cortado perpendicularmente: **hipérbole**.

As curvas pareciam ser objetos de famílias diferentes, com poucas propriedades em comum.

A primeira grande contribuição de Apolônio foi mostrar que **todas as três curvas podem ser obtidas de um único cone**, simplesmente variando a inclinação do plano de corte. Mas o passo de Apolônio foi, na verdade, ainda mais radical do que essa unificação sugere — ele generalizou a própria **definição de cone**. Em vez de um cone reto e fixo, Apolônio define a superfície cônica de forma genuinamente geral: tome um ponto fixo e um círculo que não está no mesmo plano do ponto; trace uma reta (não um segmento — uma reta completa, estendida em ambas as direções) ligando o ponto à circunferência; e gire essa reta, mantendo o ponto fixo, ao longo de toda a circunferência. A superfície gerada — composta das duas folhas opostas pelo vértice — é a superfície cônica. O eixo nem precisa ser perpendicular à base: é, em geral, um **cone duplo oblíquo**.

Para classificar as três curvas dentro desse cone generalizado, Apolônio usa uma construção precisa: corta o cone por um plano que passa pelo eixo, obtendo o **triângulo axial** $ABC$ (onde $BC$ é um diâmetro do círculo da base). O plano de corte que efetivamente produz a cônica intersecta o plano do triângulo axial numa reta $EG$. A classificação então segue diretamente da posição dessa reta:

- Se $EG$ é **paralela** a um dos lados do triângulo axial: **parábola**.
- Se $EG$ **intersecta os dois lados** do triângulo axial: **elipse**.
- Se $EG$ intersecta um lado e o **prolongamento do outro lado** além do vértice $A$: **hipérbole** — com dois ramos, um em cada folha do cone duplo.

Para isso, Apolônio precisou trabalhar com o cone duplo — dois cones unidos pelo vértice e estendidos indefinidamente em ambas as direções. A hipérbole passa a ser naturalmente uma curva de **dois ramos**, e não "duas hipérboles" como era dito antes (a diferença em relação ao cone obtusângulo original de Menaecmo, que produzia só um ramo por vez).

Apolônio demonstrou também que o mesmo resultado vale para cones oblíquos quaisquer — não apenas retos. Isso unificou as três famílias de curvas numa teoria única — e os nomes que ele escolheu para elas refletem essa unificação, como veremos adiante.

---

### 15.2 Os Nomes: Elipse, Parábola, Hipérbole

As palavras elipse, parábola e hipérbole não foram inventadas por Apolônio — eram termos técnicos preexistentes na teoria da "aplicação de áreas" pitagórica, sistematizada por Euclides (§13.4, §13.6, Livros I, II e VI). Apolônio as transplantou para as cônicas de forma que captura sua essência geométrica.

Para cada cônica, Apolônio escolhia um vértice $A$, um eixo $AK$, e um parâmetro $l$ (o *latus rectum*) — e derivava aquilo que chamava de **"sintoma"** (*symptoma*) da curva: a relação característica entre a ordenada e a abscissa de um ponto arbitrário sobre ela. Vale registrar, mais uma vez, a mesma ressalva que já fizemos para o Livro II de Euclides (§13.4) e para o Livro II de *Sobre a Esfera e o Cilindro* de Arquimedes (§14.7): **não há evidência de que Apolônio tenha usado qualquer tipo de álgebra**. Ele sempre apresentou seus resultados em linguagem geométrica pura. A "tradução" para equações modernas, que seguimos abaixo por clareza, é uma conveniência didática — não o que está de fato escrito nas *Cônicas*.

A relação fundamental entre a ordenada $y$ e a abscissa $x$, traduzida para a forma que usamos hoje, é:

**Parábola:** $y^2 = lx$

O quadrado da ordenada é *exatamente igual* ao retângulo de lados $l$ e $x$. A área $y^2$ é "aplicada" ao segmento $x$ com exatidão — sem excesso nem falta. *Parabole* significa "colocação ao lado, comparação".

**Elipse:** $y^2 = lx - \frac{l}{2a} x^2 = lx\left(1 - \frac{x}{2a}\right)$

O quadrado da ordenada é *menor* que $lx$ — a área "falta" (*elleipsis* em grego). A curva se fecha porque $y$ decresce quando $x$ supera o valor ótimo.

**Hipérbole:** $y^2 = lx + \frac{l}{2a} x^2 = lx\left(1 + \frac{x}{2a}\right)$

O quadrado da ordenada *excede* $lx$ — há um "lançamento além" (*hyperbole* em grego). A curva diverge.

Em notação moderna, reduzindo à forma canônica:

| Cônica | Equação canônica | Parâmetro $l$ |
|---|---|---|
| Parábola | $y^2 = 2px$ | $l = 2p$ |
| Elipse | $x^2/a^2 + y^2/b^2 = 1$ | $l = 2b^2/a$ |
| Hipérbole | $x^2/a^2 - y^2/b^2 = 1$ | $l = 2b^2/a$ |

As mesmas palavras — elipse ("falta"), parábola ("igual"), hipérbole ("excesso") — que Apolônio usou para curvas geométricas em 200 a.C. são as palavras que usamos em retórica hoje: uma hipérbole é um exagero, uma parábola é uma comparação, uma elipse é uma omissão.

---

### 15.3 Diâmetros Conjugados — Coordenadas Oblíquas

A propriedade fundamental de uma elipse ou hipérbole é que os pontos médios de qualquer família de cordas paralelas formam um diâmetro. Apolônio demonstrou que a cada diâmetro corresponde um **diâmetro conjugado** — o diâmetro cujas cordas são paralelas ao primeiro.

Dois diâmetros $d_1$ e $d_2$ são conjugados quando as tangentes nos extremos de $d_1$ são paralelas a $d_2$, e vice-versa. Em termos modernos, para a elipse $x^2/a^2 + y^2/b^2 = 1$, os diâmetros $y = mx$ e $y = m'x$ são conjugados quando $mm' = -b^2/a^2$.

**Por que isso importa:** Os eixos cartesianos que usamos hoje — perpendiculares entre si, alinhados com os eixos da cônica — são um caso especial. Apolônio trabalhava com sistemas de diâmetros conjugados oblíquos, que são mais naturais para muitas propriedades das cônicas. Em particular, demonstrou:

**Para a elipse:** Se $a'$ e $b'$ são os semidiâmetros conjugados de qualquer par de diâmetros conjugados, então:

$$a'^2 + b'^2 = a^2 + b^2 = \text{constante}$$

**Para a hipérbole:**

$$a'^2 - b'^2 = a^2 - b^2 = \text{constante}$$

Esses teoremas são os equivalentes cônicos do Teorema de Pitágoras — invariantes que se conservam quando se rotaciona o sistema de referência dentro da curva.

**Exemplo concreto:** Numa elipse de semieixos $a = 5$ e $b = 3$, qualquer par de diâmetros conjugados $(a', b')$ satisfaz $a'^2 + b'^2 = 25 + 9 = 34$. Se $a' = 4$, então $b' = \sqrt{34 - 16} = \sqrt{18} \approx 4{,}24$.

---

### 15.4 Tangentes por Divisão Harmônica

Apolônio encontrou um método elegante para construir tangentes a cônicas usando a **divisão harmônica**.

Para uma elipse com vértices $A$ e $A'$ no eixo maior, e um ponto $Q$ sobre a elipse com abscissa $N$:

1. Encontre o ponto $T$ que divide $AA'$ *externamente* na mesma razão em que $N$ divide $AA'$ internamente:
$$\frac{AN}{NA'} = \frac{AT}{TA'} \quad \text{(mas } T \text{ fora de } AA'\text{)}$$

2. A reta $TQ$ é tangente à elipse em $Q$.

Em linguagem moderna: $T$ é o **conjugado harmônico** de $N$ em relação a $A$ e $A'$. A quádrupla $(A, N, A', T)$ forma uma **razão harmônica** — uma das noções mais importantes da geometria projetiva, que Desargues e Pascal desenvolveriam no século XVII.

**O que é uma razão harmônica:** Quatro pontos $A, B, C, D$ numa reta formam uma razão harmônica quando:

$$\frac{AC}{CB} = -\frac{AD}{DB}$$

(com sinal, indicando que $C$ divide internamente e $D$ divide externamente). A razão harmônica se conserva sob projeções perspectivas — e é por isso que ela aparece naturalmente nas cônicas, que são seções perspectivas de um cone.

Apolônio não tinha a linguagem projetiva de Desargues — mas estava descobrindo as mesmas estruturas, por métodos puramente sintéticos.

---

### 15.5 Normais como Distâncias Mínimas — As Evolutas

O Livro V das *Cônicas* — que Apolônio descreve no prefácio como um dos temas mais belos para contemplar por si mesmo — trata de **retas mínimas e máximas** traçadas de um ponto externo a uma cônica.

Dados um ponto $Q$ e uma cônica, a distância de $Q$ a um ponto $P$ da cônica varia conforme $P$ se move. A reta $QP$ que minimiza essa distância é a **normal à cônica em $P$** — perpendicular à tangente em $P$.

A abordagem de Apolônio é inversa à que usamos hoje:
- **Hoje:** definimos normal como perpendicular à tangente, depois provamos que minimiza distâncias.
- **Apolônio:** define a normal como o segmento que minimiza a distância, depois demonstra que é perpendicular à tangente.

Para a **parábola** $y^2 = 2px$, Apolônio demonstra que o pé da normal do ponto $G$ no eixo ao ponto $P = (x_0, y_0)$ da parábola satisfaz:

$$NG = p \quad \text{(a subnormal é constante, igual ao semilatus rectum)}$$

Em notação moderna: se a normal em $P = (x_0, y_0)$ corta o eixo em $G = (x_G, 0)$, então $x_G - x_0 = p$. Isso significa que a subnormal (projeção da normal sobre o eixo) tem comprimento constante $p$, independente do ponto $P$.

**As evolutas:** Quando Apolônio busca os pontos no plano a partir dos quais se pode traçar exatamente $n$ normais a uma cônica, ele encontra **condições críticas** — curvas que hoje chamamos de **evolutas** (o lugar dos centros de curvatura da cônica).

Para a parábola $y^2 = 2px$, a evoluta é:

$$27py^2 = 8(x - p)^3$$

Esta é uma cúbica — e Apolônio a encontrou sem nenhuma noção de curvatura, derivada ou cálculo. É um feito extraordinário de raciocínio geométrico puro, e — vale notar — um companheiro direto da cúbica que vimos Arquimedes resolver em *Sobre a Esfera e o Cilindro* (§14.7): mais uma vez, equações de terceiro grau emergindo naturalmente de problemas puramente geométricos sobre cônicas, sem que nenhum dos dois geômetras as reconhecesse como "equações" no sentido moderno.

**Para as cônicas centrais** ($x^2/a^2 \pm y^2/b^2 = 1$), as evolutas são as *astroides* generalizadas:

$$(ax)^{2/3} \pm (by)^{2/3} = (a^2 \mp b^2)^{2/3}$$

Essas curvas aparecem no projeto de lentes ópticas (onde a evoluta da secção transversal determina a aberração da lente) e no projeto de engrenagens (onde dentes em perfil evolvente transmitem torque uniforme).

---

### 15.6 O Lugar a Três e Quatro Retas

O problema que mais orgulhou Apolônio — e que mais influenciou a história da matemática — é o **lugar a três e quatro retas**, descrito no Livro III.

**Enunciado:** Dadas três (ou quatro) retas no plano, encontrar o lugar geométrico de um ponto $P$ tal que o produto de duas das distâncias de $P$ às retas seja proporcional ao quadrado da terceira distância (no caso de três retas), ou o produto de duas distâncias seja proporcional ao produto das outras duas (no caso de quatro retas).

Em coordenadas modernas, se as retas têm equações $A_i x + B_i y + C_i = 0$, as distâncias de $P = (x,y)$ às retas são $d_i = |A_i x + B_i y + C_i|/\sqrt{A_i^2 + B_i^2}$. A condição para quatro retas é:

$$d_1 \cdot d_3 = k \cdot d_2 \cdot d_4$$

Substituindo, isso resulta numa equação de segundo grau em $x$ e $y$ — que representa sempre uma seção cônica (possivelmente degenerada).

Euclides havia considerado casos especiais. Apolônio demonstrou o resultado geral — que o lugar é sempre uma cônica — para três e quatro retas. E Papus, vários séculos depois (§19), generalizou para $n$ retas, observando que para $n > 4$ as condições envolvem produtos de mais de duas dimensões e sugerindo que o caso geral gera "curvas que são simplesmente chamadas curvas" — sem nome.

**O impacto histórico:** Quando Descartes, em 1637, quis demonstrar o poder de sua geometria analítica recém-inventada, escolheu exatamente o problema de Papus como teste. Descartes mostrou que com coordenadas, o problema se torna trivial — é apenas álgebra. Esse único exemplo convenceu os matemáticos europeus de que a geometria analítica era superior à geometria sintética dos gregos. O *Discurso do Método* foi publicado junto com *La Géométrie* como apêndice — e é o problema de Papus-Apolônio que Descartes usa para justificar a nova abordagem.

---

### 15.7 O Problema de Apolônio — Tangências

Numa obra perdida chamada *Tangências*, Apolônio tratou o seguinte problema:

> Dados três objetos no plano — cada um podendo ser um ponto, uma reta ou um círculo — construir um círculo tangente aos três.

Isso gera $\binom{3}{0} + \binom{3}{1} + \binom{3}{2} + \binom{3}{3} = 10$ casos combinatórios. O mais fácil: três pontos dados (o círculo circunscrito). O mais difícil: **três círculos dados**.

No caso de três círculos, geralmente existem **oito soluções** — oito círculos tangentes simultaneamente aos três dados. Newton deu uma solução no *Arithmetica Universalis* (1707). Hoje o problema tem conexões com empacotamento de esferas, geometria hiperbólica e teoria dos números.

O "círculo de Apolônio" — o lugar geométrico dos pontos cuja razão de distâncias a dois pontos fixos é constante — aparece também nas *Cônicas*. Se a razão é $k \neq 1$, o lugar é um círculo. Se $k = 1$, é a mediatriz do segmento entre os dois pontos.

**Aplicação real:** O problema de Apolônio generaliza-se para esferas em três dimensões, e essa generalização é usada em **trilateração** — o método que o GPS usa para determinar posição. Dadas as distâncias a três satélites (três esferas), a posição é a interseção. O "problema de Apolônio esférico" é o formalismo matemático subjacente.

---

### 15.8 Ciclos e Epiciclos — A Astronomia de Apolônio

Lembramos, na abertura desta seção, que Apolônio ficou famoso na Antiguidade primeiro por astronomia. Aqui está o motivo: ele propôs uma alternativa ao sistema de esferas homocêntricas de Eudoxo (§10.5) que se tornou o modelo dominante por 1.800 anos.

O sistema de **epiciclos**: um planeta $P$ move-se uniformemente em torno de um círculo pequeno (o *epiciclo*) de centro $C$; e $C$ move-se uniformemente em torno de um círculo maior (o *deferente*) de centro na Terra $E$.

O sistema **excêntrico**: o planeta $P$ move-se uniformemente em torno de um círculo grande de centro $C'$; e $C'$ move-se em torno de um círculo pequeno de centro $E$.

Apolônio demonstrou que, se $PC = C'E$, os dois sistemas são **geometricamente equivalentes** — produzem exatamente a mesma trajetória aparente do planeta visto da Terra. A demonstração usa propriedades dos paralelogramos e é um elegante resultado de geometria elementar.

**Por que isso importa:** A equivalência de epiciclos e excêntricos significa que a escolha entre os dois modelos é convencional — não há observação que distinga um do outro. Isso antecipa a discussão moderna sobre **subdeterminação teórica**: dois modelos diferentes podem ser empiricamente equivalentes. A escolha entre eles é feita por critérios de simplicidade ou coerência com outros princípios — não por observação direta.

Ptolomeu, vários séculos depois (§18), adotou o sistema de epiciclos com refinamentos (o equante) para reproduzir os movimentos planetários com precisão de arco-minuto. O sistema ptolomaico foi o modelo astronômico padrão do mundo ocidental até Copérnico (1543).

---

### 15.9 O Legado das Cônicas

Apolônio não sabia que estudava as órbitas dos planetas. Mas estava.

Em 1609, Kepler descobriu que as órbitas planetárias são **elipses** com o Sol num foco — não círculos, como Copérnico ainda supunha. Para calcular posições planetárias, Kepler precisava das propriedades das elipses — e encontrou tudo no Livro III das *Cônicas* de Apolônio.

Em 1687, Newton demonstrou nos *Principia* que qualquer corpo sujeito a uma força atrativa de intensidade $\propto 1/r^2$ se move numa cônica — elipse (órbitas fechadas), parábola (velocidade exata de escape) ou hipérbole (velocidade acima do escape). As trajetórias de todos os corpos celestes são cônicas. A matemática que Apolônio havia desenvolvido "por beleza intrínseca" descrevia a estrutura do sistema solar.

E no Livro V — as normais e evolutas — Apolônio havia essencialmente descoberto a curvatura das cônicas. Newton usaria a curvatura como conceito central no cálculo. As normais de Apolônio são a curvatura de Newton expressa na linguagem da Antiguidade.

> **Conexão com o projeto:** As trajetórias de transferência orbital para Marte são cônicas — especificamente, semi-elipses de transferência de Hohmann. O pericélio (ponto mais próximo do Sol) é a órbita da Terra, o afélio (mais distante) é a órbita de Marte. O cálculo dessas trajetórias usa diretamente as propriedades das elipses de Apolônio: o semieixo maior determina o período orbital (terceira lei de Kepler, $T^2 \propto a^3$), e a excentricidade determina as velocidades no pericélio e afélio pela conservação de energia. Apolônio não poderia imaginar que suas "belas curvas para contemplar por si mesmas" seriam, 2.200 anos depois, a ferramenta de cálculo de trajetórias para Marte.

---

*Fontes desta parte: Katz, §§ 4.4–4.5 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 20 de N — Apolônio de Perga (completa)
> **Próxima parte:** Eratóstenes de Cirene — a medida da Terra
