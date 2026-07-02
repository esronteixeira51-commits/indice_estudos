## 13. Euclides de Alexandria — A Arquitetura do Conhecimento

**Euclides** (c. 330–270 a.C.) é o matemático mais lido da história. Seu livro *Os Elementos* (*Stoicheia*) foi copiado, traduzido e ensinado por 2.300 anos — mais do que qualquer outro texto matemático, e talvez mais do que qualquer outro texto não religioso. Quando Abraham Lincoln queria aprender a argumentar com rigor, estudou Euclides. Quando Spinoza quis escrever filosofia com precisão, adotou o estilo dos *Elementos*. Quando Einstein, aos doze anos, leu os *Elementos* e verificou o teorema de Pitágoras por si mesmo, descreveu a experiência como um "livro sagrado da geometria".

Sobre a vida de Euclides, sabemos quase nada. Provavelmente estudou com discípulos de Platão em Atenas, depois foi para Alexandria, onde ensinou no *Mouseion* — a universidade fundada por Ptolomeu I, poucos anos depois da morte de Aristóteles e Alexandre (§12.6). A única anedota preservada conta que quando um aluno perguntou para que servia estudar geometria, Euclides ordenou a um escravo que lhe desse três moedas: "pois ele precisa ter lucro com o que aprende."

Os *Elementos* não eram um compêndio de todo o conhecimento geométrico — eram um **texto introdutório estruturado logicamente**, cobrindo geometria plana elementar, teoria dos números e álgebra geométrica. Euclides não pretendia ser original; compilou, selecionou e organizou resultados de Teeteto, Eudoxo, Hipócrates e outros (§6, §10, §11), acrescentando suas próprias demonstrações onde necessário. O que foi genuinamente seu foi a **arquitetura**: a escolha dos axiomas, a ordem das proposições, a escolha de quais demonstrações usar.

---

### 13.1 A Estrutura Axiomática

Como Aristóteles havia prescrito (§12.2), uma obra científica precisa começar com definições e axiomas. Euclides seguiu a receita à risca: prefaciou o Livro I com **23 definições**, **5 postulados** (geométricos, específicos do domínio) e **5 noções comuns** (verdades gerais, válidas para qualquer disciplina) — e dali derivou 465 proposições em 13 livros, cada uma demonstrada a partir das anteriores.

**As definições** definem os objetos básicos:
- "Um ponto é o que não tem partes."
- "Uma linha é comprimento sem largura."
- "Uma superfície é o que tem apenas comprimento e largura."
- "Um ângulo plano é a inclinação mútua de duas linhas que se encontram e não estão sobre uma reta."
- "Retas paralelas são retas que, estando no mesmo plano e sendo prolongadas indefinidamente em ambas as direções, não se encontram em nenhuma delas."

Platão pode ter sugerido algumas. Aristóteles as teria criticado como circulares — definir "ponto" como "sem partes" não ajuda quem não sabe o que é ponto. A crítica é válida; a matemática moderna distingue entre **termos primitivos** (não definidos) e **termos derivados** (definidos em termos dos primitivos). Euclides não fazia essa distinção explicitamente — pelos padrões de hoje, essas definições são matematicamente inúteis. Mas, na prática, seus argumentos dependem apenas das propriedades formalizadas nos postulados e nas noções comuns, não das definições verbais.

**Os cinco postulados** são:

1. *Traçar uma reta de qualquer ponto a qualquer ponto.*
2. *Prolongar uma reta finita continuamente em linha reta.*
3. *Descrever um círculo com qualquer centro e qualquer raio.*
4. *Todos os ângulos retos são iguais entre si.*
5. *Se uma reta cortando duas retas faz os ângulos interiores de um mesmo lado menores que dois retos, as duas retas, se prolongadas indefinidamente, se encontram desse lado.*

Os quatro primeiros são breves e intuitivos. O quinto é longo, convoluto e não parece do mesmo tipo que os outros. Os matemáticos gregos já notavam a assimetria — e durante 2.000 anos tentaram *demonstrar* o quinto postulado a partir dos quatro primeiros, convencidos de que ele era um teorema disfarçado de axioma. Veremos exatamente onde e por que Euclides precisou dele (§13.3) — e, mais adiante (§13.7), como essa tentativa de dois milênios terminaria nas geometrias não euclidianas.

**As cinco noções comuns** são axiomas lógicos gerais, no sentido exato em que Aristóteles as havia definido (§12.2) — verdades que valem para qualquer ciência, não apenas para a geometria:

1. Coisas iguais a uma mesma coisa são iguais entre si.
2. Se iguais são adicionados a iguais, os totais são iguais.
3. Se iguais são subtraídos de iguais, os restos são iguais.
4. Coisas que coincidem são iguais.
5. O todo é maior que a parte.

**Uma nota metodológica importante.** Embora Euclides tenha modelado a estrutura geral dos *Elementos* segundo as ideias de Aristóteles — definições, depois axiomas, depois teoremas demonstrados em cadeia —, ele **não usou silogismos** em suas demonstrações. Seus argumentos são escritos em linguagem natural e empregam, na prática, as noções da lógica proposicional: é possível encontrar exemplos das quatro regras básicas de inferência que vimos com os Estoicos (§12.1) espalhados pelas demonstrações de Euclides — sobretudo o *modus tollens*, na forma de *reductio ad absurdum*, que reaparecerá a cada poucas páginas. É a mesma ironia que já apontamos: Aristóteles forneceu a arquitetura conceitual da ciência dedutiva, mas a ferramenta de raciocínio que os matemáticos gregos realmente usaram, na prática, veio de outro lugar.

---

### 13.2 Os Treze Livros — Um Mapa

| Livros | Conteúdo |
|---|---|
| I–II | Geometria plana elementar e álgebra geométrica |
| III–IV | Geometria do círculo |
| V | Teoria geral das proporções (Eudoxo) |
| VI | Figuras semelhantes e proporções |
| VII–IX | Teoria dos números (aritmética) |
| X | Classificação dos irracionais (Teeteto) |
| XI–XII | Geometria no espaço e método de exaustão |
| XIII | Os cinco sólidos regulares (Teeteto) |

---

### 13.3 O Livro I — Lendo de Trás para Frente

Há uma maneira reveladora de ler o Livro I que a maioria dos leitores modernos não descobre por conta própria. Se você ler o Livro I do começo, proposição por proposição, nunca sabe o que vem a seguir — é uma sequência aparentemente arbitrária de fatos sobre triângulos, paralelas e áreas. **É só ao chegar ao final, na demonstração do Teorema de Pitágoras (I.47), que o propósito de tudo se revela**: o Livro I inteiro foi arquitetado, do Postulado 1 até a Proposição 46, especificamente para tornar I.47 demonstrável.

A forma mais instrutiva de estudar o Livro I, portanto, é ao contrário: comece pelo teorema final e pergunte, a cada passo, "o que isso exige que eu já tenha demonstrado?" — recuando até as definições e os postulados. Essa é também a forma mais honesta de entender *por que* certos resultados precisam ser assumidos sem prova: são exatamente os pontos onde a cadeia de "o que isso exige" para de encontrar justificativa em algo mais simples.

**O teorema final:**

> **Proposição I.47.** *Em triângulos retângulos, o quadrado sobre o lado que subtende o ângulo reto é igual à soma dos quadrados sobre os lados que contêm o ângulo reto.*

A demonstração de Euclides — a figura conhecida informalmente como "moinho de vento" ou "cadeira da noiva" — não usa semelhança de triângulos (essa demonstração, mais curta, é reservada para o Livro VI, depois que a teoria das proporções estiver rigorosamente fundada). Em vez disso, usa apenas **congruência e decomposição de áreas**: sobre os três lados do triângulo retângulo $ABC$ (ângulo reto em $A$), Euclides constrói os quadrados $ABFG$, $BCDE$ e $ACKH$. Traça a reta $AL$ paralela a $BD$, dividindo o quadrado da hipotenusa em dois retângulos. Depois demonstra que o retângulo $BDL$ tem a mesma área do quadrado sobre $AB$, e que o retângulo $CEL$ tem a mesma área do quadrado sobre $AC$ — bastando, ao final, somar as duas igualdades (pela Noção Comum 2: iguais somados a iguais são iguais).

Para entender essa demonstração, é essencial notar algo que Euclides nunca define explicitamente: o que significa duas figuras planas serem "iguais". Para ele, significa "área igual" — mas ele nunca formaliza o conceito de área, nem calcula uma única área numérica em toda a demonstração. Em vez disso, seu método é sempre **decompor as regiões em peças e mostrar que as peças coincidem** — justificado pela Noção Comum 4 (coisas que coincidem são iguais). É um estilo de demonstração radicalmente diferente do "calcule a área com uma fórmula" que aprendemos hoje.

Agora, recuando: o que essa demonstração de I.47 exige?

**Nível 1 — construir o quadrado.** Antes de falar de "o quadrado sobre $AB$", é preciso saber construir um quadrado sobre um segmento qualquer:

> **Proposição I.46.** *Descrever um quadrado sobre uma reta dada.*

A construção de Euclides: erga uma perpendicular $AC$ ao segmento $AB$ (usando I.11), marque $AD = AB$ sobre essa perpendicular (usando I.3 — transportar distâncias com o compasso), trace por $D$ uma paralela a $AB$ e por $B$ uma paralela a $AD$ (usando I.31), encontrando-se em $E$. Prova-se que $ADEB$ é um quadrado mostrando que é um paralelogramo (I.34: lados opostos de um paralelogramo são iguais) e que seus ângulos são retos (usando I.29: ângulos alternos internos entre paralelas).

**Nível 2 — congruência e a equivalência triângulo-retângulo.** A demonstração de I.47 também precisa do critério de congruência LAL:

> **Proposição I.4 (LAL).** *Se dois triângulos têm dois lados respectivamente iguais, e os ângulos compreendidos por esses lados também iguais, os triângulos são congruentes.*

Euclides demonstra isso por **superposição**: imagina o primeiro triângulo sendo deslocado e colocado sobre o segundo, com um lado coincidindo com o lado correspondente, e os ângulos também coincidindo. Tacitamente, Euclides assume que esse movimento é sempre possível sem deformar a figura — um pressuposto físico, não um postulado formal. É um dos pontos mais discutidos dos *Elementos*: ao invés de fornecer um postulado explícito sobre movimento rígido, os matemáticos do século XIX preferiram simplesmente tomar o próprio LAL como axioma, descartando a superposição como método de prova.

E precisa também da relação entre retângulos e triângulos de mesma base e altura:

> **Proposição I.41.** *Se um paralelogramo tem a mesma base que um triângulo e está entre as mesmas paralelas, o paralelogramo tem o dobro da área do triângulo.*

De novo, Euclides não usa as fórmulas $A = bh$ e $A = \frac{1}{2}bh$ que tornariam isso imediato — usa decomposição: o paralelogramo se divide pela diagonal em dois triângulos iguais ao triângulo dado (por I.37 e I.34).

**Nível 3 — paralelas e perpendiculares.** Tanto I.46 quanto I.41 dependem, em algum ponto, de saber construir uma perpendicular (I.11) e uma paralela (I.31) a uma reta dada.

A construção da perpendicular (I.11) começa desenhando um **triângulo equilátero** sobre um segmento — o que nos leva à primeira proposição de todo o livro:

> **Proposição I.1.** *Construir um triângulo equilátero sobre um segmento dado.*

A construção: trace dois círculos, cada um com centro numa extremidade do segmento e raio igual ao próprio segmento (usando o Postulado 3). O terceiro vértice é o ponto onde os dois círculos se cruzam.

**Aqui está o primeiro buraco lógico dos *Elementos*** — e é apropriado que apareça já na primeira proposição. Como Euclides sabe que os dois círculos realmente se cruzam? No diagrama, parece óbvio. Mas nenhum dos cinco postulados garante isso — seria necessário um axioma de continuidade explícito, que só seria formulado rigorosamente no século XIX (veremos isso quando chegarmos às fundações modernas da geometria). Euclides, como quase todos os geômetras até então, confiava no diagrama onde a lógica pura ainda não alcançava.

A construção da paralela (I.31) depende, por sua vez, de:

> **Proposição I.27.** *Se uma reta, ao cair sobre duas retas, forma ângulos alternos iguais, então as duas retas são paralelas.*

Aqui Euclides usa, pela primeira vez de forma explícita neste percurso, uma **dupla *reductio ad absurdum*** — exatamente a ferramenta lógica estoica que mencionamos em §13.1: suponha que as retas, mesmo com ângulos alternos iguais, não sejam paralelas. Então elas se encontram em algum ponto $G$, formando um triângulo onde um ângulo externo seria igual a um ângulo interno oposto — o que contradiz a proposição seguinte (I.16). Logo, a suposição é falsa, e as retas são paralelas.

E essa proposição anterior é onde aparece **o segundo buraco lógico**:

> **Proposição I.16.** *Em qualquer triângulo, se um dos lados é prolongado, o ângulo externo é maior que qualquer um dos ângulos internos não adjacentes a ele.*

A demonstração de Euclides prolonga um segmento $BE$ até um ponto $F$ tal que $EF = BE$ exatamente — mas **nenhum dos cinco postulados autoriza estender uma reta até um comprimento específico**; o Postulado 2 só garante que uma reta finita pode ser prolongada, não que pode ser prolongada até bater num comprimento predeterminado. É um pressuposto adicional, não declarado. E essa falha não é apenas uma curiosidade histórica: o corolário imediato de I.16 — que dois ângulos quaisquer de um triângulo somam menos que dois ângulos retos (I.17) — desempenharia, dois mil anos depois, um papel central nas tentativas (e no eventual fracasso) de demonstrar o quinto postulado a partir dos outros quatro, abrindo caminho para a descoberta das geometrias não euclidianas (§13.7).

**Nível 4 — o coração do livro.** Tanto I.46 quanto I.27/I.31 dependem, em algum ponto, da proposição mais importante e mais discutida de todo o Livro I:

> **Proposição I.29.** *Uma reta que cai sobre retas paralelas forma ângulos alternos iguais, o ângulo externo igual ao interno e oposto, e os ângulos internos do mesmo lado somando dois ângulos retos.*

Há três afirmações aqui, e qualquer uma implica facilmente as outras duas. A questão que Euclides precisou resolver foi: **qual delas demonstrar — e a partir de quê?** As fontes gregas anteriores a Euclides mostram que a situação era genuinamente confusa: ninguém sabia exatamente o que assumir para provar esse fato aparentemente óbvio sobre paralelas. Euclides já havia demonstrado a *recíproca* (I.27, vista acima, e I.28) — mas, ao que tudo indica, não encontrou nenhuma forma de demonstrar I.29 diretamente a partir de princípios mais simples.

Foi então que Euclides tomou a decisão mais célebre e mais controversa de toda a obra: ele tomou a *contrapositiva* da terceira afirmação de I.29 e a colocou, no início do Livro I, como axioma — o **Postulado 5**, o postulado das paralelas, que já vimos em §13.1. Com o postulado em mãos, a demonstração de I.29 é um *reductio* direto: se o ângulo $AGH$ fosse diferente do ângulo $GHD$, a soma dos ângulos de um certo lado seria menor que dois retos — e pelo Postulado 5, as retas se encontrariam, contradizendo a hipótese de que são paralelas.

**A árvore completa**, recuando de I.47 até os postulados:

```
I.47 (Teorema de Pitágoras)
 ├─ I.46 (construir o quadrado)
 │   ├─ I.11 (perpendicular) ── I.1 (triângulo equilátero) ⚠ [buraco: interseção dos círculos]
 │   ├─ I.31 (paralela) ── I.27 (ângulos alternos ⟹ paralelas)
 │   │                       └─ I.16 (ângulo externo) ⚠ [buraco: prolongar até comprimento dado]
 │   │                            └─ I.29 (ângulos entre paralelas) ── POSTULADO 5
 │   ├─ I.3 (transportar distância) ── Postulados 1 e 3
 │   └─ I.34 (paralelogramo: lados opostos iguais) ── I.29
 ├─ I.4 — LAL (congruência) ⚠ [buraco: superposição/movimento rígido]
 └─ I.41 (paralelogramo = 2× triângulo) ── I.37, I.34
```

**O que essa árvore revela.** O Teorema de Pitágoras, o resultado culminante do Livro I, depende — além de praticamente todos os resultados anteriores, incluindo os três critérios de congruência de triângulos — do **Postulado das Paralelas**. Entre os cinco postulados de Euclides, só o quinto provocou controvérsia real ao longo dos séculos, justamente porque muitos sentiam que ele não era "autoevidente" da forma que um postulado deveria ser, segundo o próprio padrão de Aristóteles (§12.2). E quase desde o momento em que os *Elementos* circularam, geômetras tentaram demonstrá-lo como teorema a partir apenas dos outros nove axiomas. Muitos pensaram ter conseguido — mas um exame cuidadoso de cada uma dessas tentativas sempre revela, ou um erro, ou (mais frequentemente) outra suposição não declarada, talvez mais intuitiva que a de Euclides, mas igualmente indemonstrável a partir dos outros nove.

A suposição alternativa mais conhecida — e a que a maioria dos livros didáticos modernos usa em vez do Postulado 5 original — é:

> **Axioma de Playfair.** *Por um ponto dado fora de uma reta dada, pode-se construir exatamente uma paralela à reta dada.*

Esse axioma é inteiramente equivalente ao Postulado 5 de Euclides — pelo menos assumindo que retas de comprimento arbitrário podem ser traçadas e que a Proposição I.16 (com seu próprio buraco lógico) é verdadeira. É mais intuitivo de enunciar, e por isso prevaleceu no ensino — mas logicamente, é exatamente a mesma pedra angular sobre a qual todo o edifício do Livro I, e portanto boa parte da geometria grega, está construído.

---

*Fontes desta parte: Katz, § 3.2 (cadeia completa de I.47) · Boyer, cap. 5 · Struik, cap. III*

---
> **Status:** Parte 10 de N — Euclides: estrutura axiomática e Livro I (completa)
> **Próxima parte:** Livro II (álgebra geométrica) e Livros III–VI (geometria do círculo e teoria das proporções)
