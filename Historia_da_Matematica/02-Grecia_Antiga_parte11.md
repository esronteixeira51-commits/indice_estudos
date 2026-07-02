### 13.4 O Livro II — Álgebra Geométrica?

O Livro I, como vimos, é o "kit de ferramentas" básico do geômetra grego — um conjunto de resultados usados constantemente em qualquer demonstração avançada. O Livro II é uma criatura completamente diferente: 14 proposições sobre relações entre retângulos e quadrados, sem objetivo aparente, raramente citadas no restante dos *Elementos*. Por isso, o propósito do Livro II tem sido motivo de debate entre historiadores da matemática há mais de cem anos.

**Uma ressalva historiográfica necessária.** A interpretação tradicional — adotada amplamente desde o final do século XIX, e que seguimos abaixo por sua utilidade pedagógica — é que o Livro II é **álgebra geométrica**: a representação de conceitos algébricos por meio de figuras. Quadrados de lado $a$ seriam representações geométricas de $a^2$; retângulos de lados $a$ e $b$, do produto $ab$; e relações entre essas figuras corresponderiam a equações.

Mas é importante saber que **a maioria dos historiadores hoje duvida que esse fosse o propósito original de Euclides**. Euclides nunca multiplica dois comprimentos entre si — ele não tinha como definir essa operação para grandezas arbitrárias. Em vários pontos multiplica um comprimento por um número (um inteiro positivo), mas, fora isso, fala apenas de "retângulos contidos por duas retas". A visão mais aceita atualmente é que Euclides pretendia, no Livro II, apenas reunir um corpo coerente de conhecimento geométrico sobre retângulos — útil não necessariamente nos *Elementos* propriamente, mas em matemática grega mais avançada, como o estudo das seções cônicas que veremos com Apolônio (§15). A leitura "algébrica" é uma tradução conveniente para o leitor moderno, não necessariamente a intenção original do autor — um lembrete saudável de que projetar nossas próprias categorias mentais sobre textos antigos é um risco constante ao estudar história da matemática, o mesmo cuidado que já tivemos com as atribuições incertas a Tales (§3.2) e Hípias (§7).

Com essa ressalva em mente, a tradução algébrica continua sendo uma ferramenta útil para entender o conteúdo:

| Proposição | Equivalente algébrico moderno |
|---|---|
| II.1 | $a(b+c+d) = ab + ac + ad$ (distributividade) |
| II.2 | $(a+b)^2 = a^2 + 2ab + b^2$ |
| II.3 | $(a+b)(a-b) = a^2 - b^2$ |
| II.4 | $a^2 = (a-b)^2 + 2b(a-b) + b^2$ |
| II.5–6 | Resolução geométrica de $ax - x^2 = b^2$ (equação quadrática) |
| II.11 | Construção da seção áurea |
| II.14 | Construção de um quadrado igual a um retângulo dado |

**O método das figuras "visíveis" e "invisíveis".** Vale a pena examinar como Euclides demonstra II.1, porque revela algo importante sobre o estilo de toda a álgebra geométrica grega. A proposição afirma — em linguagem moderna — a distributividade: se uma reta $BC$ é dividida em qualquer número de partes (Euclides usa três, como exemplo generalizável), o retângulo contido por uma reta $A$ e $BC$ é igual à soma dos retângulos contidos por $A$ e cada uma das partes. Euclides traça os retângulos *de fato* — figuras visíveis no diagrama — e a partir delas conclui sobre os retângulos "invisíveis" mencionados no enunciado (o retângulo entre $A$ e a reta inteira, que não está desenhado como peça única, mas decomposto). Esse padrão — provar um resultado sobre figuras invisíveis usando uma construção visível — reaparece ao longo de toda a álgebra geométrica grega, inclusive na geometria do círculo que veremos a seguir.

A Proposição II.5 merece atenção especial pois é a base da resolução geométrica de equações quadráticas. Em linguagem moderna, ela diz:

$$\left(\frac{a}{2}\right)^2 = \left(\frac{a}{2} - b\right)^2 + ab$$

Geometricamente: se um segmento $AB = a$ é cortado no meio em $C$ e num ponto qualquer em $D$, então o quadrado sobre $CD$ (a semissoma menos a semidiferença) mais o retângulo $AD \cdot DB$ é igual ao quadrado sobre $CA$.

**Como isso resolve equações quadráticas:** Suponha que queremos $x$ tal que $ax - x^2 = b^2$. Usando II.5 com $a = AB$ e $x = AD$, a construção geométrica dá $x = a/2 - \sqrt{(a/2)^2 - b^2}$ — exatamente a fórmula quadrática, executada com régua e compasso. Euclides não escreve fórmulas; constrói segmentos. Mas o algoritmo é o mesmo. **Vale notar que essa interpretação "Euclides resolvia equações quadráticas" também não é de Euclides** — foi feita explicitamente apenas no **século IX d.C.**, por matemáticos islâmicos como Al-Khwarizmi, que reconheceram nas proposições II.5–6 uma justificativa geométrica para os procedimentos algébricos que estavam desenvolvendo. Esse reaproveitamento, mil e duzentos anos depois de Euclides, é um exemplo perfeito de como um resultado pode sobreviver à intenção original de seu autor — algo que já vimos com a quadratriz de Hípias reaproveitada por Nicômedes (§7.3).

**A origem da terminologia de Apolônio.** Há um fio que vale a pena começar a puxar aqui, e que vamos completar quando chegarmos a Apolônio (§15). A Proposição I.44 introduz a técnica pitagórica de **"aplicação de áreas"** (*parabolé*): dado um segmento e um ângulo, construir sobre o segmento um paralelogramo de área dada. O Livro VI generaliza essa técnica para casos onde o paralelogramo construído é **deficiente** (*ellipsis*) ou **excedente** (*hyperbolé*) em relação ao segmento dado — as Proposições VI.28 e VI.29, que veremos em detalhe na próxima parte. Esses três termos gregos — aplicação exata, deficiente, excedente — são exatamente os nomes que Apolônio reaproveitaria, um século depois de Euclides, para batizar as três cônicas: parábola, elipse e hipérbole. Apolônio não inventou vocabulário novo — emprestou, com extraordinária precisão conceitual, uma terminologia que já vinha sendo refinada havia gerações dentro da própria álgebra geométrica de Euclides.

---

### 13.5 Os Livros III e IV — A Geometria do Círculo e a Construção do Pentágono

Os Livros I e II tratam de figuras retilíneas — delimitadas por segmentos de reta. No Livro III, Euclides se volta para a figura curva mais fundamental: o círculo.

Os gregos eram fascinados pela simetria do círculo — o fato de que, por mais que se gire, ele sempre parece igual. Consideravam-no a mais perfeita das figuras planas, assim como a esfera era a mais perfeita das figuras sólidas. Essas ideias filosóficas forneceriam, mais adiante (§18), a base de toda a astronomia grega — onde planetas e estrelas só poderiam mover-se em círculos perfeitos, por dignidade cósmica.

**O fio condutor dos Livros III–IV.** Se há um princípio organizador único para o Livro III, é este: preparar tudo que é necessário para, no Livro IV, construir polígonos regulares inscritos e circunscritos a um círculo. A construção do triângulo, do quadrado e do hexágono é relativamente intuitiva, e provavelmente já era conhecida dos próprios Pitagóricos. A construção do **pentágono regular**, porém, é genuinamente difícil — exige dividir um segmento em "extrema e média razão" (a seção áurea que já conhecemos bem, §4.4 e §11.5) — e é provavelmente um desenvolvimento posterior, possivelmente devido ao próprio **Teeteto** (§11.5), no início do século IV a.C. A maior parte da segunda metade do Livro III existe, especificamente, para tornar essa construção do pentágono possível — que por sua vez seria usada para construir o dodecaedro e o icosaedro no Livro XIII.

**Um exemplo de demonstração — o produto de cordas que se cruzam.** Para sentir o estilo de Euclides em ação no círculo, vale acompanhar uma demonstração concreta:

> **Proposição III.35.** *Se duas retas se cruzam dentro de um círculo, o retângulo contido pelos segmentos de uma é igual ao retângulo contido pelos segmentos da outra.*

Em notação moderna: se as cordas $AC$ e $BD$ se cruzam em $E$, então $AE \cdot EC = DE \cdot EB$.

A demonstração é um exemplo perfeito do método "visível/invisível" que já vimos no Livro II: os retângulos mencionados no enunciado são *invisíveis* — não aparecem desenhados diretamente. Euclides traça do centro $F$ do círculo as perpendiculares $FG$ e $FH$ às duas cordas (o que faz de $G$ e $H$ seus pontos médios), e conecta $FB$, $FC$ e $FE$. Aplicando II.5 ao segmento $AC$ (cortado ao meio em $G$ e num ponto qualquer em $E$): o retângulo contido por $AE$ e $EC$, somado ao quadrado sobre $EG$, é igual ao quadrado sobre $GC$. Somando o quadrado sobre $GF$ a ambos os lados e aplicando o Teorema de Pitágoras duas vezes (em $GFC$ e em $GFE$), conclui-se que o retângulo $AE \cdot EC$ somado ao quadrado sobre $FE$ é igual ao quadrado sobre $FC$ — que é igual ao quadrado sobre $FB$ (ambos são raios). O mesmo argumento aplicado à corda $BD$ dá: o retângulo $DE \cdot EB$ somado ao quadrado sobre $FE$ também é igual ao quadrado sobre $FB$. Como os dois resultados têm o mesmo lado direito, os retângulos são iguais. ∎

Note como essa única demonstração reaproveita três resultados que já vimos: II.5 (Livro II), o Teorema de Pitágoras (I.47) e a definição de raio. É assim que os *Elementos* se sustentam — cada livro novo recombina o que vem antes, em vez de recomeçar do zero.

**A tangente, antes do cálculo.** A Proposição III.16 estabelece o que hoje chamaríamos de tangente a um círculo, embora Euclides não use essa palavra: ele demonstra que a reta perpendicular ao diâmetro, em sua extremidade, cai fora do círculo, e que nenhuma outra reta pode ser interposta entre ela e a circunferência nesse ponto. Essa última condição — "nenhuma reta pode ser interposta" — tornou-se, ao longo dos séculos seguintes, parte da própria definição padrão de tangente, usada até a invenção do cálculo diferencial oferecer uma definição baseada em limites.

A Proposição III.31 ratifica algo que já conhecemos bem: o ângulo inscrito num semicírculo é reto — o quinto teorema atribuído a Tales (§3.1), agora demonstrado dentro do sistema axiomático completo de Euclides, dois séculos depois da atribuição original.

---

*Fontes desta parte: Katz, §§ 3.3–3.4 · Boyer, cap. 5 · Struik, cap. III*

---
> **Status:** Parte 11 de N — Euclides: Livro II e Livros III–IV (completa)
> **Próxima parte:** Livros V–VI (teoria das proporções e figuras semelhantes) e início dos Livros VII–IX (teoria dos números)
