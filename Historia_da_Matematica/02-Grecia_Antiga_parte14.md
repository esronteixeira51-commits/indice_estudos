### 13.8 O Livro X — A Classificação dos Irracionais

Muitos historiadores consideram o Livro X **o mais importante** de toda a obra de Euclides — não pela quantidade de leitores modernos que o estudam (poucos chegam até lá), mas pela sofisticação técnica que representa. Com 115 proposições, é o mais longo dos treze livros, e provavelmente o mais bem organizado de todos.

**A motivação e a origem.** O propósito declarado do Livro X é classificar certas grandezas incomensuráveis — e uma das motivações centrais era puramente prática: caracterizar os comprimentos das arestas dos poliedros regulares, cuja construção no Livro XIII forma o clímax apropriado de toda a obra. Euclides precisava de uma forma não numérica de comparar as arestas do icosaedro e do dodecaedro com o diâmetro da esfera em que estão inscritos — e essa pergunta, aparentemente simples, levaria a um esquema de classificação muito mais elaborado do que sua resposta direta exigiria.

A atribuição de boa parte deste livro a **Teeteto** (§11.5) não é apenas tradição vaga — há uma conexão biográfica precisa. Foi no diálogo platônico que leva o nome de Teeteto que a questão de determinar quais números têm raízes quadradas incomensuráveis com a unidade foi levantada pela primeira vez, num contexto narrativo. É a resposta a essa pergunta específica, dada logo no início do Livro X, que conduz a toda a classificação geral que se segue.

**Uma armadilha terminológica.** Antes de prosseguir, vale uma advertência sobre vocabulário: Euclides usa a palavra "racional" de um jeito **diferente** do uso moderno. Se a reta de referência tem comprimento 1, não apenas retas de comprimento $a/b$ (com $a,b$ inteiros) são chamadas "racionais" no sentido de Euclides — mas também retas de comprimento $\sqrt{ab}$, para inteiros positivos $a$ e $b$ quaisquer. É um lembrete oportuno: ao traduzir termos técnicos antigos para o vocabulário matemático moderno, corremos sempre o risco de importar conotações que não estavam lá originalmente — o mesmo cuidado que já tivemos ao questionar se o Livro II era realmente "álgebra" (§13.4).

**A primeira proposição — o motor do método de exaustão.** A Proposição X.1 é fundamental não apenas para este livro, mas para todo o Livro XII:

> **Proposição X.1.** *Dadas duas grandezas desiguais, se da maior se subtrai uma grandeza maior que sua metade, e do que resta se subtrai novamente uma grandeza maior que sua metade, e se esse processo é repetido continuamente, restará alguma grandeza menor que a menor das grandezas dadas.*

Esse é exatamente o princípio geral que descrevemos, em palavras quase idênticas, quando apresentamos o método de exaustão de Eudoxo (§10.4) — e agora podemos ver sua justificativa precisa: o resultado depende diretamente da **Definição 4 do Livro V**, o critério de Eudoxo para quando duas grandezas têm uma razão entre si (§10.3) — que exige que algum múltiplo $n$ da grandeza menor supere a maior. A partir dessa garantia, $n$ subtrações sucessivas, cada uma removendo mais da metade do que resta, eventualmente produzem uma grandeza menor que qualquer limite prefixado. É a peça que faltava: agora sabemos exatamente qual proposição numerada Eudoxo e Euclides usavam, e de qual axioma anterior ela depende.

**Onde número e grandeza finalmente se encontram.** As Proposições X.2 e X.3 retomam a *antiphairesis* — a subtração reciprocada que Teeteto aplicou a grandezas geométricas (§11.5) e que, no Livro VII, Euclides aplicou a números inteiros sob o nome de algoritmo de Euclides (§13.7, VII.1–2). Como é o **mesmo procedimento** aplicado a dois domínios diferentes, Euclides pode agora conectar os dois conceitos: as Proposições X.5 e X.6 demonstram que duas grandezas são comensuráveis **precisamente quando** sua razão é a razão entre um número e outro número. Ou seja: mesmo sendo número e grandeza noções formalmente distintas (§12.3), é possível aplicar toda a maquinaria da proporção numérica (Livro VII) a grandezas comensuráveis. A definição mais elaborada de Eudoxo (Livro V, Definição 5) só é estritamente necessária quando as grandezas são **incomensuráveis** — exatamente o caso que motivou sua criação.

**A generalização completa de Teeteto.** Chegamos agora ao resultado que coroa décadas de trabalho que acompanhamos por todo este capítulo. Recorde: Teodoro de Cirene demonstrou, caso a caso, a irracionalidade de $\sqrt{3}, \sqrt{5}, \ldots$ até $\sqrt{17}$, sem que saibamos por que parou ali (§11.4). A Proposição X.9 é a generalização completa que faltava:

> **Proposição X.9 (Teeteto).** *Dois lados de quadrados são comensuráveis em comprimento se, e somente se, os quadrados estão entre si na razão de um número quadrado para outro número quadrado.*

Em termos modernos: a raiz quadrada de **qualquer** inteiro que não seja um quadrado perfeito é incomensurável com a unidade. Não mais caso a caso até 17 — todos os infinitos casos, de uma só vez.

A parte interessante da demonstração é a direção "somente se". Suponha que dois lados $a, b$ são comensuráveis em comprimento. Então $a:b = c:d$ para números inteiros $c, d$ — e, portanto, as razões duplicadas também são iguais. Mas Euclides já havia demonstrado, em **VI.20** (§11.6, sobre figuras semelhantes), que o quadrado sobre $a$ está para o quadrado sobre $b$ na razão duplicada de $a$ para $b$; e em **VIII.11** (§13.7, sobre médias proporcionais entre números quadrados), que $c^2$ está para $d^2$ na razão duplicada de $c$ para $d$. Combinando as duas — uma sobre grandezas geométricas, outra sobre números inteiros — o resultado segue diretamente. É uma demonstração elegante precisamente porque amarra, num único argumento, resultados de três livros diferentes que vínhamos acumulando ao longo deste capítulo.

**A classificação — com exemplos concretos.** O restante do Livro X (mais de cem proposições) classifica sistematicamente segmentos irracionais que não são comensuráveis com a unidade, nem mesmo "comensuráveis em quadrado" com ela. A classificação completa é demasiado extensa para reproduzir aqui, mas vale a pena sentir seu sabor com algumas das definições mais usadas no Livro XIII:

- **Linha medial**: o lado de um quadrado cuja área é igual ao retângulo contido por duas retas racionais comensuráveis apenas em quadrado. Exemplo: como $1$ e $\sqrt{5}$ são comensuráveis apenas em quadrado (seus quadrados, $1$ e $5$, estão numa razão racional; eles mesmos, não), e o retângulo contido por eles tem área $\sqrt{5}$, o comprimento $\sqrt[4]{5}$ é medial.
- **Binômio**: a soma de duas retas racionais comensuráveis apenas em quadrado. Exemplo: $1 + \sqrt{5}$.
- **Apótoma**: a diferença de duas retas racionais comensuráveis apenas em quadrado. Exemplo: $\sqrt{5} - 1$ — que, não por acaso, é exatamente a seção áurea que conhecemos desde os Pitagóricos (§4.4)!
- **Menor**: um caso mais complexo — a diferença $x - y$ entre duas retas incomensuráveis em quadrado, tais que $x^2+y^2$ é racional e $xy$ é uma área medial. Exemplo: com $x = \sqrt{5+2\sqrt{5}}$ e $y = \sqrt{5-2\sqrt{5}}$, a diferença $x-y$ é uma "menor".

É significativo notar que, embora cada um desses comprimentos possa ser expresso hoje como solução de uma equação polinomial, Euclides nunca usa qualquer maquinaria algébrica — tudo é feito geometricamente, com régua, compasso e comparação direta de áreas. Os exemplos numéricos acima são uma tradução para conforto do leitor moderno; para Euclides, cada um desses objetos era uma construção geométrica específica, não uma fórmula.

A motivação prática, como dissemos no início, era a geometria dos sólidos regulares: as arestas do icosaedro e do dodecaedro inscritos numa esfera de raio $r$ envolvem expressões exatamente desse tipo — como $r\sqrt{(10-2\sqrt{5})/5}$ —, e é precisamente esse tipo de irracional "aninhado" que toda essa classificação foi construída para nomear e domesticar.

---

*Fontes desta parte: Katz, § 3.7 · Boyer, cap. 5 · Struik, cap. III*

---
> **Status:** Parte 14 de N — Euclides: Livro X (completa)
> **Próxima parte:** Livros XI–XIII — Geometria no espaço e os cinco sólidos regulares
