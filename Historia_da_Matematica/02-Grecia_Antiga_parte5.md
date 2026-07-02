## 8. Demócrito de Abdera — O Átomo e o Volume

**Demócrito de Abdera** (c. 460–370 a.C.) é mais conhecido como o pai do atomismo físico — a doutrina de que toda matéria é feita de partículas indivisíveis, os átomos, movendo-se no vazio. Mas seus contemporâneos o conheciam também como geômetra, e ele se gabava de que nem os "estiradores de corda" do Egito o superavam em geometria prática.

Demócrito viajou mais do que qualquer outro intelectual de seu tempo — Egito, Babilônia, Pérsia, possivelmente a Índia. Escreveu obras de matemática que Arquimedes, séculos depois, ainda citava com respeito. Nenhuma sobreviveu.

### 8.1 O Volume da Pirâmide

Os egípcios sabiam calcular o volume de uma pirâmide: $V = \frac{1}{3}Bh$, onde $B$ é a área da base e $h$ a altura. Mas sabiam *que* a fórmula funcionava, não *por que* funcionava. Demonstrá-la exigia um tipo de argumento que a matemática egípcia não possuía.

Arquimedes registra que **Demócrito foi o primeiro a enunciar** que o volume do cone é um terço do cilindro de mesma base e altura, e que o volume da pirâmide é um terço do prisma correspondente — mas acrescenta que Demócrito *não demonstrou* esses resultados rigorosamente. A demonstração rigorosa viria de Eudoxo, cerca de um século depois.

O que Demócrito provavelmente fez foi um argumento por **atomismo geométrico**: imagine a pirâmide cortada em infinitas fatias horizontais infinitamente finas, paralelas à base. Cada fatia é um polígono semelhante à base, com área proporcional ao quadrado da distância ao vértice. Some todas as fatias — e o resultado é $\frac{1}{3}Bh$.

Em linguagem moderna, esse argumento é uma integral:

$$V = \int_0^h B\left(\frac{x}{h}\right)^2 dx = \frac{B}{h^2} \cdot \frac{h^3}{3} = \frac{Bh}{3}$$

Demócrito não tinha cálculo, mas tinha a intuição física do atomismo: sólidos são "feitos de" fatias infinitamente finas, e a soma dessas fatias *é* o volume. A mesma lógica que aplicava à matéria física, aplicava à geometria.

### 8.2 O Paradoxo das Fatias — Nas Palavras Preservadas de Demócrito

Mas o próprio Demócrito percebeu um problema devastador em seu argumento — e, ao contrário de quase tudo na Idade Heroica, *temos um fragmento de suas palavras reais*, preservado não por Eudemo ou Proclo, mas por uma cadeia diferente: o filósofo estoico **Crisipo** (c. 280–206 a.C.) registrou a formulação de Demócrito, e essa citação sobreviveu.

O problema: considere um cone dividido em fatias horizontais paralelas à base, cada uma "indivisível" — uma seção transversal infinitamente fina. Duas fatias adjacentes quaisquer: a de cima e a de baixo. Elas são iguais ou diferentes?

Na formulação de Demócrito, transmitida por Crisipo: se as seções forem desiguais, o cone teria a superfície "irregular, com reentrâncias, como degraus". Mas se forem iguais, o cone seria indistinguível de um cilindro — feito, em suas próprias palavras, "de círculos iguais, não desiguais, o que é muito absurdo".

**Se forem iguais:** então todas as fatias têm a mesma área. Somando infinitas fatias iguais, obtemos um *cilindro* — não um cone. Contradição.

**Se forem diferentes:** então as faces superior e inferior de cada fatia têm áreas diferentes. O cone seria então uma pilha de troncos de cone em degraus — uma figura com superfície em escada, não a superfície lisa que imaginamos. Também contradição.

O detalhe mais honesto sobre esse fragmento — e o Katz é explícito nesse ponto — é que **não sabemos qual foi a conclusão final de Demócrito**. Temos o problema formulado com clareza notável; não temos a resposta que ele mesmo lhe deu, se é que chegou a uma. O paradoxo antecipa, com dois mil anos de antecedência, as questões que Cauchy e Riemann precisariam resolver para tornar o cálculo rigoroso. A saída moderna é o conceito de limite: as fatias não são *iguais*, mas a diferença entre fatias adjacentes se torna arbitrariamente pequena quando a espessura das fatias tende a zero — e a soma das diferenças converge para zero no limite. O cone em degraus *converge* para o cone liso.

Demócrito não tinha essa linguagem. Mas ter formulado o paradoxo com clareza suficiente para que Crisipo, dois séculos depois, ainda o considerasse digno de citar literalmente é em si um feito intelectual considerável — e foi provavelmente esse problema que motivou Eudoxo a desenvolver o método de exaustão com o rigor que faltava.

### 8.3 O Princípio de Cavalieri — Dois Mil Anos Antes de Cavalieri

O argumento implícito de Demócrito contém o germe do que seria chamado, no século XVII, de **princípio de Cavalieri**: se duas figuras sólidas têm a mesma altura e, em qualquer altura $x$, as seções transversais têm a mesma área, então os dois sólidos têm o mesmo volume.

O próprio Katz mostra como esse caminho poderia ter sido percorrido passo a passo, e essa reconstrução vale a pena seguir de perto porque aponta diretamente para dois resultados que Euclides demonstraria, com todo o rigor, no Livro XII dos *Elementos* — que veremos em detalhe mais adiante (§11):

**Primeiro passo (germe da Proposição XII-5 de Euclides):** Imagine duas pirâmides de mesma altura e bases triangulares, cortadas por planos paralelos às respectivas bases, a distâncias iguais do topo. As seções correspondentes em cada pirâmide têm áreas proporcionais às áreas das bases. Se cada pirâmide é "feita de" infinitas dessas seções indivisíveis, somá-las preserva a proporção — logo, **pirâmides de mesma altura estão entre si na mesma razão que suas bases**. É exatamente o que a Proposição XII-5 afirma, embora Euclides a prove sem qualquer menção a indivisíveis, por *reductio ad absurdum* e o método de exaustão.

**Segundo passo (germe da Proposição XII-7 de Euclides):** um prisma triangular de base $B$ e altura $h$ pode ser dividido em três pirâmides de bases e alturas iguais — todas com o mesmo volume por simetria. Logo cada pirâmide tem volume $\frac{1}{3}Bh$, e o resultado egípcio finalmente recebe sua justificativa.

Esse tipo de argumento — comparar sólidos fatia a fatia — é a essência da integração. Cavalieri o formalizaria em 1635. Newton e Leibniz o tornariam o cálculo integral em 1666–1675. Mas a intuição estava em Demócrito, em Abdera, em torno de 430 a.C. — e a distância entre essa intuição e a prova rigorosa de Euclides é precisamente a distância entre *adivinhar* um resultado e *demonstrá-lo*: a obsessão grega que atravessa todo este capítulo.

### 8.4 Atomismo Físico e Atomismo Geométrico

Há uma tensão fascinante na obra de Demócrito: seu atomismo *físico* postulava átomos indivisíveis e finitos; seu atomismo *geométrico* precisava de fatias *infinitamente* finas para funcionar. Os dois programas são contraditórios.

Mas essa tensão era produtiva. O atomismo físico dava a Demócrito a intuição de que objetos contínuos são feitos de partes discretas — e essa intuição o levava a resultados corretos em geometria, mesmo que o fundamento filosófico fosse inconsistente. É um exemplo de como uma metáfora errada pode levar a matemática certa.

Platão ignorou Demócrito. Aristóteles o criticou duramente — e, como veremos quando tratarmos da Academia (§10) e de Aristóteles (§10, Seção A), a crítica aristotélica aos indivisíveis se tornaria doutrina oficial da matemática grega por dois milênios. Suas obras físicas foram deliberadamente destruídas na antiguidade — segundo a tradição, por ordem de Platão. Das obras matemáticas, nada restou além das citações de Arquimedes e do fragmento preservado por Crisipo. O que teria produzido Demócrito com mais tempo e mais influência é uma das grandes questões abertas da história da matemática.

> **Conexão com o projeto:** O argumento de Demócrito para o volume do cone — somar infinitas fatias horizontais — é literalmente o que um computador faz ao calcular a trajetória de um rover por integração numérica. A posição futura é a "soma" de infinitos deslocamentos infinitesimais. O paradoxo das fatias é o erro de truncamento: fatias finitas em vez de infinitesimais. Escolher o passo de integração certo é o mesmo problema que Demócrito enfrentou, sem a linguagem para resolvê-lo — e sua honestidade em registrar o paradoxo sem fingir tê-lo resolvido é, em si, uma lição de engenharia: documentar a limitação conhecida de um método é tão valioso quanto o método em si.

---

*Fontes desta parte: Boyer, cap. 4 · Katz, § 3.8 (citação via Crisipo) · Struik, cap. III*

---
> **Status:** Parte 5 de N — Demócrito de Abdera (completa)
> **Próxima parte:** Zenão de Eleia — os quatro paradoxos do movimento e da divisibilidade
