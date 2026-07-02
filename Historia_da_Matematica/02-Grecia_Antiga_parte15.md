### 13.9 O Livro XI — Geometria Sólida: Os Livros I e VI em Três Dimensões

Os três últimos livros dos *Elementos* tratam de geometria tridimensional — e o Livro XI estabelece os fundamentos: planos, retas no espaço, ângulos diedros, paralelepípedos.

**Um padrão estrutural elegante.** Se você já entendeu os Livros I e VI (§13.3 e §13.6), o Livro XI vai parecer estranhamente familiar — porque, em essência, é uma tradução sistemática de resultados desses dois livros para três dimensões. A Proposição XI.11 (traçar uma perpendicular a um plano, a partir de um ponto externo) e a XI.12 (o mesmo, a partir de um ponto no próprio plano) espelham diretamente I.11–12. A Proposição XI.31 — paralelepípedos sobre bases iguais e com a mesma altura são iguais — é a versão tridimensional de I.36 (paralelogramos sobre bases iguais, entre as mesmas paralelas, são iguais). A XI.32 — paralelepípedos de mesma altura estão entre si como suas bases — espelha VI.1. E a XI.34 — em paralelepípedos iguais, as bases são inversamente proporcionais às alturas — espelha VI.14 e VI.16.

**O padrão duplicado→triplicado.** A correspondência mais bonita é a Proposição XI.33: paralelepípedos semelhantes estão entre si na **razão triplicada** de seus lados correspondentes. No Livro VI, vimos que figuras planas semelhantes estão na razão **duplicada** dos lados (VI.19–20) — o princípio que usamos repetidamente neste capítulo, de Hipócrates (§6.1) a Teeteto (§13.8). A passagem de "duplicada" para "triplicada" é exatamente o que esperaríamos ao subir de área (dimensão 2) para volume (dimensão 3): se os lados escalam por um fator $k$, áreas escalam por $k^2$ e volumes por $k^3$. Euclides nunca calcula um único volume numérico no Livro XI — como sempre, ele lida apenas com razões e proporções. Mas dessas proposições é fácil derivar os resultados básicos sobre volumes de paralelepípedos. As "fórmulas" propriamente ditas para outros sólidos — pirâmides, cones, esferas — ficam reservadas para o Livro XII.

**Por que a esfera é definida de um jeito estranho.** Há uma curiosidade na lista de definições que abre o Livro XI: a esfera não é definida por analogia com o círculo (como "o conjunto de pontos equidistantes de um centro", que seria o paralelo natural à Definição 15 do Livro I). Em vez disso, Euclides a define **dinamicamente**: é a figura gerada quando um semicírculo gira em torno de seu diâmetro até retornar à posição original.

Por que essa escolha? Presumivelmente porque Euclides não pretendia discutir as propriedades da esfera com a mesma profundidade que discutiu as do círculo no Livro III — essas propriedades já eram conhecidas em sua época e tratadas em outros textos, incluindo um do próprio Euclides, hoje perdido. Dentro dos *Elementos*, a esfera só reaparece em dois lugares: no Livro XII, para calcular seu volume, e no Livro XIII, para construir os cinco sólidos regulares inscritos nela — e é exatamente ali que a definição por rotação ganha sentido prático: as construções do Livro XIII mostram, literalmente, como cada poliedro regular se encaixa numa esfera fazendo girar um semicírculo em torno deles, do mesmo jeito que a própria esfera foi definida.

---

### 13.10 O Livro XII — O Método de Exaustão em Ação

O traço que distingue o Livro XII de todos os outros é o uso sistemático de um processo de limite — o método de exaustão de Eudoxo, que já apresentamos em detalhe (§10.4). Aqui ele é aplicado à área do círculo e aos volumes de pirâmides, cones e esferas. As "fórmulas" para essas figuras já eram conhecidas havia muito tempo — é praticamente certo que o volume da pirâmide já era conhecido tanto pelos egípcios (lembre-se do Papiro de Moscou, no Período 1 deste projeto) quanto pelos babilônios. Mas para os gregos, conhecer uma fórmula não bastava: era preciso **provar** — e o método de Eudoxo fornecia a prova. O que ele não fornecia, como já notamos (§10.4), era uma forma de *descobrir* a fórmula em primeiro lugar.

Os quatro resultados centrais do Livro XII são:

> **XII.2.** *Círculos estão entre si como os quadrados de seus diâmetros.*

> **XII.7 (corolário).** *Toda pirâmide é a terça parte do prisma que tem a mesma base e altura iguais.*

> **XII.10.** *Todo cone é a terça parte do cilindro que tem a mesma base e altura iguais.*

> **XII.18.** *Esferas estão entre si na razão triplicada de seus respectivos diâmetros.*

Já encontramos XII.2 como o exemplo concreto do método de exaustão (§10.4) e XII.7 como o resultado que Demócrito provavelmente descobriu por atomismo geométrico e Eudoxo demonstrou rigorosamente (§8.3, §10.4). A XII.18 completa, para esferas, exatamente o mesmo padrão de "razão triplicada" que acabamos de ver em XI.33 para paralelepípedos semelhantes — volumes de sólidos semelhantes sempre escalam com o cubo das dimensões lineares correspondentes, e os gregos demonstravam isso, caso a caso, para cada família de sólidos.

**Um buraco lógico que vale a pena precisar.** Quando apresentamos a demonstração de XII.2 em §10.4, simplificamos um passo da forma "suponha que existe $A''$ tal que...". Vale a pena agora ser mais preciso sobre exatamente onde está o problema, porque é genuinamente revelador sobre os limites do próprio sistema de Euclides.

A demonstração completa de Euclides começa assumindo, por contradição, que $A_1 : A_2 \neq d_1^2 : d_2^2$. Isso significa que existe alguma área $S$ — maior ou menor que $A_2$ — tal que $d_1^2 : d_2^2 = A_1 : S$. Mas aqui está o problema: **Euclides nunca demonstrou que uma "quarta proporcional" desse tipo existe para três grandezas arbitrárias** — ele só provou isso para três *retas* (Proposição VI.12), não para áreas em geral. A existência de $S$ precisaria, rigorosamente, de algum tipo de argumento de continuidade que Euclides simplesmente não fornece — talvez porque, como o próprio Katz observa, ele não exigia a construção efetiva dessa grandeza, apenas sua existência lógica para fins do *reductio ad absurdum*.

Esse é o mesmo tipo de lacuna que já documentamos no Livro I — a interseção dos círculos em I.1, a extensão de reta em I.16 (§13.3) — um pressuposto de continuidade que o diagrama torna intuitivamente óbvio, mas que os cinco postulados, tomados literalmente, não garantem. O restante da demonstração, a partir daí, é exatamente o argumento de dupla *reductio* com polígonos inscritos que já detalhamos em §10.4.

**Uma ponte de volta ao Egito e à Babilônia.** Vale fechar esta seção notando, de novo, como o Livro XII inteiro pode ser lido como o capítulo final de uma história que começou no Período 1 deste projeto: o volume da pirâmide, que os egípcios calculavam corretamente sem justificativa (Papiro de Moscou) e que Demócrito provavelmente descobriu por um argumento intuitivo de fatias (§8.1), finalmente recebe, aqui, sua demonstração formal e definitiva — quase mil e quinhentos anos depois dos primeiros escribas egípcios terem registrado a fórmula correta.

---

### 13.11 O Livro XIII — O Clímax: Os Cinco Sólidos Regulares

O Livro XIII é o ponto culminante de toda a obra — não por acidente, mas por desenho. Euclides termina exatamente onde Platão (§11.2) e Teeteto (§11.5) haviam apontado: na construção dos cinco sólidos regulares e na demonstração de que são, exatamente, cinco — nem mais, nem menos.

O Livro XIII constrói cada um dos cinco sólidos — tetraedro, octaedro e icosaedro inscritos numa esfera com auxílio do pentágono e da seção áurea (§4.4, §11.5); o cubo e o dodecaedro com a mesma proporção desempenhando papel central na aresta deste último. A proposição final do livro (XIII.18) demonstra a unicidade: não existe um sexto poliedro regular convexo possível, e a demonstração — contar quantos polígonos regulares podem se encontrar num único vértice sem exceder 360° — é exatamente a que já vimos em §11.5.

As proposições finais calculam a razão entre a aresta de cada sólido e o raio $R$ da esfera circunscrita — o ponto de chegada de toda a classificação de irracionais do Livro X (§13.8):

| Sólido | Aresta $e$ em termos do raio $R$ |
|---|---|
| Tetraedro | $e = R\sqrt{8/3}$ |
| Cubo | $e = R \cdot 2/\sqrt{3}$ |
| Octaedro | $e = R\sqrt{2}$ |
| Icosaedro | $e = R\sqrt{(10 - 2\sqrt{5})/5}$ |
| Dodecaedro | $e = R(\sqrt{5}-1)/\sqrt{3}$ |

Note como a aresta do dodecaedro envolve diretamente $\sqrt{5}-1$ — o **apótoma** que classificamos no Livro X (§13.8) e que reconhecemos, desde os Pitagóricos (§4.4), como a seção áurea. Treze livros, centenas de proposições, e o edifício inteiro converge exatamente para o número que abriu este capítulo com a estrela secreta da irmandade pitagórica.

> **Conexão com o projeto:** O padrão "razão duplicada para áreas, triplicada para volumes" que atravessa os Livros VI, XI e XII é a mesma lei de escala que rege a engenharia de qualquer estrutura física — incluindo o chassi do rover. Dobrar as dimensões lineares de uma estrutura multiplica sua área de superfície por 4 e seu volume (e portanto sua massa) por 8: é por isso que estruturas maiores precisam de proporções diferentes, não apenas de uma ampliação uniforme — um problema central no projeto de qualquer veículo que precisa equilibrar massa, resistência estrutural e dissipação de calor.

---

*Fontes desta parte: Katz, § 3.8 · Boyer, cap. 5 · Struik, cap. III*

---
> **Status:** Parte 15 de N — Euclides: Livros XI–XIII (completa)
> **Próxima parte:** O Quinto Postulado e as Geometrias Não Euclidianas — encerrando a seção de Euclides
