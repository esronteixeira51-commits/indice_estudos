### 14.5 Sobre Espirais — Trissecção e a Tangente Cinemática

A **espiral de Arquimedes** é definida cinematicamente: um ponto parte da origem e se afasta uniformemente ao longo de um raio que gira uniformemente. Em coordenadas polares:

$$r = a\theta$$

onde $a$ é a razão entre a velocidade linear e a velocidade angular. É uma curva que cresce linearmente com o ângulo — diferentemente da espiral logarítmica (onde $r = e^{a\theta}$), que aparece em conchas de nautilus.

**Trissecção do ângulo pela espiral:** Para trissectar um ângulo $\theta$, basta encontrar o ponto $P$ na espiral onde $r = a\theta$ e dividir o segmento $OP$ em três partes iguais. Os pontos $R$ e $S$ que dividem $OP$ correspondem a ângulos $\theta/3$ e $2\theta/3$ pela propriedade $r \propto \theta$ da espiral. É o mesmo princípio da quadratriz de Hípias (§7), aplicado a uma curva diferente — mais um exemplo do padrão que vimos repetidamente neste capítulo: gregos diferentes, séculos diferentes, atacando o mesmo problema clássico com curvas novas.

**A tangente cinemática:** Arquimedes encontrou a tangente à espiral em qualquer ponto usando raciocínio cinemático. Um ponto sobre a espiral tem dois movimentos simultâneos: radial (ao longo do raio vetor) e circular (perpendicular ao raio vetor). A tangente é a resultante dos dois movimentos — encontrada pelo paralelogramo de velocidades.

Em linguagem de cálculo: se $r = a\theta$, então $dr/d\theta = a$, e a tangente forma com o raio vetor um ângulo $\psi$ tal que $\tan\psi = r/(dr/d\theta) = \theta$. Arquimedes não escreveu isso assim, mas o resultado geométrico que obteve é equivalente.

**Quadratura do círculo pela espiral:** Se $P$ é o ponto onde a espiral corta a semirreta perpendicular ao eixo polar, a **subtangente polar** em $P$ (o segmento da tangente ao eixo polar) tem comprimento exatamente igual ao arco do quarto de circunferência de raio $OP$. Isso permite construir um segmento de comprimento $\pi r$ a partir de $r$ — e com isso quadrar o círculo. Novamente, a construção usa a espiral, não régua e compasso.

---

### 14.6 Quadratura da Parábola — Duas Demonstrações

Em *Quadratura da Parábola*, Arquimedes demonstra que a área de um segmento parabólico (a região entre a parábola e uma corda) é $\frac{4}{3}$ da área do triângulo inscrito de mesma base e altura. É a primeira quadratura de uma seção cônica na história.

**Primeira demonstração — método de exaustão:** Inscreva o maior triângulo $ABC$ no segmento. Nos dois sub-segmentos que restam, inscreva os maiores triângulos possíveis. A propriedade da parábola garante que cada novo triângulo tem $\frac{1}{4}$ da área do anterior. A área total é:

$$A = T + \frac{T}{4} + \frac{T}{16} + \cdots = T \sum_{n=0}^{\infty} \left(\frac{1}{4}\right)^n = T \cdot \frac{1}{1 - 1/4} = \frac{4T}{3}$$

Arquimedes não escreveu a soma da série geométrica infinita assim — esse conceito era inaceitável na matemática grega (lembre-se da distinção entre infinito potencial e atual, §12.4). Em vez disso, demonstrou por dupla *reductio ad absurdum* que a área não pode ser nem maior nem menor que $\frac{4T}{3}$.

**Segunda demonstração — método mecânico:** Usando princípios de equilíbrio (como numa alavanca), Arquimedes "pesou" fatias do segmento parabólico contra fatias de um triângulo de área conhecida. A demonstração aparece em *O Método* (§14.9) e é mais curta — mas Arquimedes a considerava uma heurística, não uma prova rigorosa.

---

### 14.7 Sobre a Esfera e o Cilindro — O Teorema Favorito, e uma Equação Cúbica Escondida

Arquimedes pediu que em seu túmulo fosse gravada uma esfera inscrita num cilindro. O motivo: ele havia descoberto e demonstrado que:

$$\frac{V_{\text{cilindro}}}{V_{\text{esfera}}} = \frac{A_{\text{cilindro}}}{A_{\text{esfera}}} = \frac{3}{2}$$

onde o cilindro tem o mesmo diâmetro e altura da esfera (altura = diâmetro = $2r$).

Em termos explícitos:
- $V_{\text{esfera}} = \frac{4}{3}\pi r^3$
- $V_{\text{cilindro}} = \pi r^2 \cdot 2r = 2\pi r^3$, razão $= 3:2$ ✓
- $A_{\text{esfera}} = 4\pi r^2$
- $A_{\text{cilindro}} = 2\pi r^2 + 2\pi r \cdot 2r = 6\pi r^2$, razão $= 4:6 = 2:3$ ✓

O tratado demonstra também que a **área de qualquer zona esférica** (a superfície entre dois planos paralelos) depende apenas da **largura** da zona — não da posição. Uma zona de largura $h$ numa esfera de raio $r$ tem área $2\pi r h$, independente de onde a zona está na esfera. Em particular, dois hemisférios da mesma esfera têm a mesma área superficial, não importa se um é "polar" e o outro "equatorial".

**Isso equivale a integrar o seno:** A área de uma zona entre $\theta_1$ e $\theta_2$ é:
$$A = \int_{\theta_1}^{\theta_2} 2\pi r \cos\theta \cdot r\, d\theta = 2\pi r^2 (\sin\theta_2 - \sin\theta_1) = 2\pi r (r\sin\theta_2 - r\sin\theta_1) = 2\pi r h$$

Arquimedes obteve esse resultado por métodos geométricos — mas o equivalente moderno é a integral do seno, um dos resultados centrais do cálculo.

**O resultado escondido no Livro II — uma equação cúbica.** O primeiro livro de *Sobre a Esfera e o Cilindro* contém os resultados acima, já espetaculares. Mas é no **segundo livro**, bem menos citado fora dos círculos especializados, que Arquimedes faz algo ainda mais surpreendente — e que o documento original deste projeto não tinha capturado.

O problema (Proposição 4): **dada uma esfera, cortá-la por um plano de modo que os dois segmentos resultantes tenham volumes numa razão dada.**

Depois de uma análise cuidadosa, Arquimedes reduz esse problema a uma equação que, em notação moderna, escrevemos como:

$$x^2(a-x) = c^2 d$$

onde $a$ é o diâmetro da esfera, e $c^2 d$ é uma quantidade fixa que depende da razão de volumes desejada e da posição de um ponto auxiliar na construção. É, sem rodeios, uma **equação cúbica** em $x$.

**Um problema de máximo, resolvido geometricamente — sem cálculo.** Antes de mostrar como resolver a equação, Arquimedes precisava saber *se* ela tinha solução — e isso exigia algo notavelmente parecido com otimização: ele demonstrou que a expressão $x^2(a-x)$ atinge seu **valor máximo** exatamente quando $x = \frac{2}{3}a$. Esse máximo vale $\frac{4}{27}a^3$. Logo, o problema só tem solução quando $c^2d \leq \frac{4}{27}a^3$ — e, quando essa condição é satisfeita, há uma solução se a igualdade vale, e duas soluções distintas se a desigualdade é estrita.

É exatamente o tipo de análise que hoje faríamos derivando $f(x) = x^2(a-x)$, igualando a derivada a zero e resolvendo $2ax - 3x^2 = 0$, o que dá $x = \frac{2}{3}a$. Arquimedes chegou ao mesmo ponto sem qualquer noção de derivada — por um argumento puramente geométrico sobre razões e proporções, similar em espírito ao que ele já havia feito noutros tratados, mas aplicado aqui a um problema de máximo, não de área ou volume.

**A solução — conexão direta com Menaecmo.** Tendo estabelecido que a equação é solúvel, Arquimedes precisava efetivamente *encontrar* $x$. Sua estratégia é a mesma que já vimos com Menaecmo (§11.6) na duplicação do cubo: reduzir o problema à **interseção de duas cônicas**. Através de uma sequência elaborada de proporções envolvendo retângulos auxiliares, Arquimedes mostra que a quantidade procurada corresponde ao ponto de interseção entre uma **parábola** (definida por uma das relações de proporção) e uma **hipérbole** (definida por outra). Construindo as duas curvas e localizando sua interseção, o problema original — cortar a esfera na razão de volumes desejada — fica resolvido.

É a mesma estratégia geral de Menaecmo (duas parábolas para a duplicação do cubo, §11.6), agora aplicada por Arquimedes, um século e meio depois, a um problema completamente diferente, com uma combinação diferente de cônicas (parábola e hipérbole, em vez de duas parábolas). O repertório de "resolver problemas geométricos difíceis via interseção de cônicas", criado por Menaecmo na Academia de Platão, havia se tornado, na época de Arquimedes, uma técnica padrão do arsenal grego.

**Arquimedes "resolveu uma equação cúbica"? Uma ressalva necessária.** É comum descrever esse resultado dizendo que "Arquimedes resolveu uma equação cúbica" — e, no sentido amplo de álgebra geométrica que já discutimos (§13.4), isso é defensável. Mas vale a mesma cautela histórica de sempre: não há indício de que Arquimedes estivesse pensando em "resolver uma equação". Ele estava construindo a solução de um problema geométrico específico e concreto — cortar uma esfera numa razão dada — usando exclusivamente objetos geométricos (incluindo seções cônicas, já bem estabelecidas desde Euclides e Aristeu, §11.6). Se isso conta como "resolver uma equação cúbica" é, na melhor das hipóteses, uma questão de interpretação retrospectiva — o que não diminui em nada a genialidade matemática envolvida.

> **Conexão com o projeto:** O problema de encontrar o valor de $x$ que maximiza $x^2(a-x)$ sem usar derivadas — exatamente o que Arquimedes fez — é um exemplo arquetípico de **otimização restrita por busca geométrica**, o tipo de problema que motores de planejamento de trajetória do rover ainda resolvem quando o espaço de busca é pequeno e bem estruturado o suficiente para evitar o custo computacional de métodos baseados em gradiente. Cada vez que um algoritmo de otimização verifica os extremos de um intervalo e os pontos críticos para encontrar um máximo, está repetindo, com ferramentas diferentes, exatamente o raciocínio de Arquimedes para $x = \frac{2}{3}a$.

---

*Fontes desta parte: Katz, § 4.3 (Livro II, Proposição 4) · Boyer, cap. 6 · Struik, cap. III*

---
> **Status:** Parte 18 de N — Arquimedes: Espirais, Quadratura da Parábola, Esfera e Cilindro (completa)
> **Próxima parte:** Conoides e Esferoides, *O Método*, e os Resultados Adicionais (incluindo o Stomachion)
