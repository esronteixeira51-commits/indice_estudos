## 14. Arquimedes de Siracusa — O Maior Matemático da Antiguidade

**Arquimedes** (c. 287–212 a.C.) é o único matemático da Antiguidade que os historiadores modernos colocam sem hesitação na mesma prateleira que Newton, Gauss e Euler. Voltaire escreveu que havia mais imaginação na cabeça de Arquimedes do que na de Homero. Leibniz, que inventou o cálculo integral independentemente de Newton, disse que quem entende Arquimedes e Apolônio admira menos os feitos dos grandes matemáticos posteriores.

Nasceu em Siracusa, na Sicília, filho de um astrônomo. Estudou em Alexandria — provavelmente com discípulos de Euclides — e voltou a Siracusa, onde viveu o resto da vida em contato com a corte do rei Hierão II. Durante o cerco romano de Siracusa (214–212 a.C.), inventou máquinas de guerra — catapultas, guinchos para levantar navios, possivelmente espelhos concentradores de calor — que mantiveram os romanos à distância por três anos. Quando a cidade finalmente caiu, foi morto por um soldado romano que interrompeu sua concentração num problema geométrico. O general romano Marcelo havia ordenado que o poupasse.

Diferentemente de Euclides, que compilou e organizou, Arquimedes era um **descobridor**. Seus tratados registram não apenas resultados mas o método pelo qual os obteve. Diz-se que considerava seus engenhos mecânicos menos importantes que seus trabalhos matemáticos — e pediu que seu túmulo fosse marcado com a figura de uma esfera inscrita num cilindro, em memória de seu teorema favorito.

Sobreviveram catorze de seus tratados — um número notável para a Antiguidade. Juntos, representam o ponto mais alto da matemática grega.

---

### 14.1 Sobre o Equilíbrio dos Planos — A Lei da Alavanca

A lei da alavanca já era conhecida antes de Arquimedes: dois pesos em equilíbrio são inversamente proporcionais às suas distâncias ao fulcro. O que Arquimedes fez foi **demonstrá-la** a partir de princípios estáticos, sem recorrer ao argumento cinemático de Aristóteles (que invocava movimentos e velocidades para justificar o equilíbrio).

O ponto de partida de Arquimedes é um **axioma de simetria**: um sistema bilateralmente simétrico está em equilíbrio. Nada mais óbvio — se a balança é igual dos dois lados, não há razão para pender para nenhum lado.

Desse axioma simples, Arquimedes deriva o caso geral. Considere uma barra horizontal sem peso, com três pesos unitários: um em cada extremidade e um no meio. Por simetria, está em equilíbrio sobre o ponto central. Agora, considere apenas os dois pesos do lado direito: pelo mesmo axioma de simetria, eles podem ser substituídos por um peso duplo no ponto médio do braço direito, sem alterar o equilíbrio. Isso significa que um peso de 2 unidades a distância 1 equilibra um peso de 1 unidade a distância 2 — e por generalização, $m_1 d_1 = m_2 d_2$.

**Aplicação real:** O mesmo princípio governa a distribuição de carga em plataformas de pouso de rovers. O centro de massa do veículo deve estar diretamente acima do polígono de suporte formado pelas rodas — caso contrário, o torque resultante tomba a plataforma. Calcular onde posicionar baterias, motores e instrumentos para manter o centro de massa na posição ideal é exatamente o problema que Arquimedes formalizou.

---

### 14.2 Sobre Corpos Flutuantes — O Princípio de Arquimedes

O tratado *Sobre Corpos Flutuantes* começa com um único postulado sobre a natureza dos fluidos — que a pressão num fluido em equilíbrio age perpendicularmente a qualquer superfície — e deriva dele o princípio que ainda leva o nome de Arquimedes:

> *Um sólido imerso num fluido sofre uma força vertical para cima igual ao peso do fluido deslocado.*

A história do eureka — Arquimedes pulando da banheira ao perceber como determinar se a coroa do rei era de ouro puro — é provavelmente lendária. Mas o método é real: uma coroa de ouro puro e uma de ouro adulterado com prata, ambas com o mesmo peso, têm volumes diferentes (prata é menos densa que ouro). Imersas em água, deslocam quantidades diferentes de água. A diferença de deslocamento revela a fraude — sem destruir a coroa.

**Aplicação real:** Sondas planetárias que usam balões para flutuar na atmosfera de Vênus ou Titã dependem diretamente do princípio de Arquimedes aplicado a gases: o empuxo é o peso do gás deslocado, e o sistema flutua em equilíbrio quando esse empuxo iguala o peso total do balão mais a carga útil.

O segundo livro do tratado vai muito além da hidrostática básica: analisa as posições de equilíbrio de **segmentos de paraboloide** flutuando num fluido, dependendo da razão entre a densidade do sólido e a do fluido e da orientação do eixo. São cálculos de estabilidade de flutuação — o tipo de análise que engenheiros navais modernos fazem para garantir que um navio não vire em mar agitado.

---

### 14.3 O Contador de Areia — Números Imensos e os Logaritmos

No *Psammites* ("Contador de Areia"), Arquimedes se propõe a demonstrar que pode escrever um número maior que o número de grãos de areia necessários para preencher o universo. O propósito não é apenas exibicionismo — é mostrar que o sistema grego de numeração pode ser estendido para lidar com números arbitrariamente grandes.

O sistema jônico de numeração (§2.2) ia até dezenas de milhares de miríades ($10^8$). Para ir além, Arquimedes propôs uma hierarquia:

- **Primeira ordem:** números até $10^8$ (uma miríade de miríades).
- **Segunda ordem:** números até $10^{16}$.
- **Terceira ordem:** até $10^{24}$.
- ...e assim por diante.

Usando o universo heliocêntrico de Aristarco (que era muito maior que o geocêntrico padrão), Arquimedes estimou que o universo tem diâmetro de $10^{14}$ estádios. Um grão de areia tem diâmetro de $\sim 1/40$ de um dedo, e um dedo cúbico contém $\sim 640.000.000$ grãos. Fazendo as contas, Arquimedes concluiu que o número de grãos necessários é menor que $10^{63}$ — e escreveu esse número explicitamente em sua notação.

**O embrião dos logaritmos:** Mais importante que o cálculo em si é uma observação incidental de Arquimedes: somar as "ordens" dos números corresponde a multiplicar os números. Ou seja:

$$\text{ordem}(a) + \text{ordem}(b) = \text{ordem}(a \times b)$$

Isso é a lei dos logaritmos — $\log(ab) = \log a + \log b$ — enunciada dois mil anos antes de Napier inventá-los em 1614. Arquimedes não desenvolveu o conceito, mas a intuição estava lá.

---

### 14.4 Medida do Círculo — O Cálculo de π

Em *Medida do Círculo*, Arquimedes demonstra três resultados:

**Proposição 1:** A área de qualquer círculo é igual à de um triângulo retângulo cujos catetos são, respectivamente, o raio e a circunferência do círculo. Em notação moderna: $A = \frac{1}{2} \cdot r \cdot 2\pi r = \pi r^2$.

**Proposição 2:** A razão da área do círculo ao quadrado do diâmetro é aproximadamente $11:14$. (Isso equivale a $\pi \approx 22/7 \approx 3{,}1429$, a famosa aproximação.)

**Proposição 3:** $3\frac{10}{71} < \pi < 3\frac{10}{70}$, ou seja, $3{,}1408\ldots < \pi < 3{,}1429\ldots$

Para demonstrar a Proposição 3, Arquimedes usou o método de exaustão de Eudoxo, inscrevendo e circunscrevendo polígonos regulares no círculo e calculando seus perímetros. Começando com o hexágono ($n=6$) e dobrando sucessivamente o número de lados até $n = 96$, obteve os dois limites.

O cálculo exige raízes quadradas — Arquimedes computava à mão, usando o método iterativo babilônico, e registrou resultados como:

$$\sqrt{3} > \frac{265}{153} \approx 1{,}7320\ldots \qquad \text{(correto: } 1{,}73205\ldots\text{)}$$
$$\sqrt{3} < \frac{1351}{780} \approx 1{,}73205\ldots$$

Como Arquimedes obteve essas frações não é explicado no texto — provavelmente era conhecimento técnico que considerava dispensável documentar. Mas a precisão é notável para cálculo manual.

**O processo iterativo:** Dado o perímetro $p_n$ do polígono inscrito de $n$ lados e o perímetro $P_n$ do circunscrito, Arquimedes calculava:

$$P_{2n} = \frac{2 P_n p_n}{P_n + p_n} \qquad (\text{média harmônica})$$
$$p_{2n} = \sqrt{P_{2n} \cdot p_n} \qquad (\text{média geométrica})$$

Essa alternância de médias harmônica e geométrica é hoje chamada **algoritmo de Arquimedes** — e converge muito rapidamente: a cada duplicação do número de lados, o número de casas decimais corretas aproximadamente dobra.

---

*Fontes desta parte: Boyer, cap. 6 · Struik, cap. III*

---
> **Status:** Parte 17 de N — Arquimedes: introdução, Alavanca, Flutuantes, Contador de Areia, Medida do Círculo (completa)
> **Próxima parte:** Espirais, Quadratura da Parábola, e a descoberta da equação cúbica em *Sobre a Esfera e o Cilindro*
