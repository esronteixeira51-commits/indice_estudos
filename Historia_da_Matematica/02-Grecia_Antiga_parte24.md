## 19. A Aritmética Grega e seus Limites Estruturais

Depois de completar o arco astronômico — Aristarco (§17), Hiparco (§17) e Ptolomeu (§18) — temos uma visão completa da trigonometria grega e de suas conquistas. É o momento certo para um balanço crítico: o que a aritmética grega *não* conseguia fazer, e por quê. Isso prepara o terreno para Menelau e Herão, que contornam essas limitações com métodos práticos, e para o salto que o Período 3 deste projeto fará rumo à matemática islâmica e indiana — onde várias dessas limitações seriam finalmente superadas.

Ao longo deste capítulo, vimos os gregos alcançarem resultados extraordinários em geometria, trigonometria e teoria dos números. Mas há um padrão consistente em todas essas realizações: **sempre que possível, os gregos convertiam problemas aritméticos em problemas geométricos**. A razão não era estética — era estrutural. A aritmética grega tinha limitações que a geometria não tinha.

---

### 19.1 O Sistema de Numeração e suas Consequências

O sistema jônico (alfabético), que apresentamos em detalhe em §2.2, funcionava bem para inteiros e para aritmética básica com ábaco. Mas tinha uma falha crítica: **não havia notação posicional para frações**.

No sistema babilônico, a notação posicional estendia-se naturalmente para frações: $1;30$ significava $1 + 30/60 = 1{,}5$ em base sexagesimal. No sistema decimal moderno, $1{,}5$ usa a mesma lógica. Qualquer fração cujo denominador é uma potência da base pode ser escrita diretamente.

No sistema grego, não havia esse mecanismo. As opções eram:

**Frações unitárias** (no estilo egípcio, §2.4): $1/2 + 1/4$ em vez de $3/4$. Cômodo para denominadores pequenos, inviável para denominadores como $720$ (que aparece na tabela de Ptolomeu, §18.3).

**Frações sexagesimais** (emprestadas dos babilônios): os astrônomos (Hiparco, Ptolomeu) adotaram o sistema babilônico para cálculos astronômicos precisos. Por isso os minutos e segundos de ângulo ainda usam base 60 — é a aritmética babilônica preservada pela astronomia grega.

**Razões entre inteiros** (o método padrão dos geômetras): em vez de escrever $3/4$, escrever "a razão de 3 para 4". Isso é exato e rigoroso — mas torna a álgebra praticamente impossível. Como escrever "o dobro de $3/4$"? Seria "a razão de 6 para 4" ou "a razão de 3 para 2" — mas não há um procedimento algorítmico simples para manipular essas razões.

**Exemplo concreto do problema:** A solução da equação $3x + 5 = 11$ é $x = 2$ — trivial. Mas a solução de $3x + 5 = 12$ é $x = 7/3$. Em aritmética moderna, escrevemos $7/3$ e prosseguimos. Em aritmética grega, temos "a razão de 7 para 3" — que não pode ser somada a outra razão sem primeiro encontrar um denominador comum, operação que a notação grega tornava trabalhosa. Diofanto (§21) lidava com isso usando seu sistema sincopado, mas para os geômetras a resposta usual era **reformular o problema geometricamente** para que a solução fosse um segmento de reta, não uma fração.

---

### 19.2 A Ausência de Números Negativos

Os gregos não reconheciam números negativos como objetos matemáticos legítimos. "Um número menor que zero" era uma contradição nos termos — um número é uma quantidade de alguma coisa, e não existe quantidade negativa de qualquer coisa concreta.

**Consequências práticas:**

A equação $x - 5 = 3$ tem solução $x = 8$ — aceitável. A equação $x - 5 = -3$, que equivale a $x = 2$, seria mal formulada: o que significa "menos três"? Os gregos rescreveriam como $5 - x = 3$, com solução $x = 2$ — o mesmo resultado, mas sem invocar um número negativo.

**O problema com equações quadráticas:** Uma equação como $x^2 - 5x + 6 = 0$ tem raízes $x = 2$ e $x = 3$ — ambas positivas, ambas aceitáveis. Mas $x^2 + 5x + 6 = 0$ tem raízes $x = -2$ e $x = -3$ — ambas negativas, portanto inexistentes para os gregos. A equação "não tem solução".

Isso não era apenas uma limitação técnica — era uma escolha filosófica. Os gregos identificavam números com grandezas geométricas (comprimentos, áreas, volumes), e grandezas geométricas não são negativas. A aceitação dos negativos exigia desconectar o conceito de número do conceito de grandeza física — um passo que os indianos deram (Brahmagupta, 628 d.C.) e que os europeus resistiram até o século XVII.

**Exemplo de como isso limitava a álgebra:** Diofanto, ao encontrar uma equação com solução negativa, dizia que o problema "é absurdo" (*atopos*) e descartava. Ele nunca considerou que a solução negativa pudesse ter significado algum.

---

### 19.3 A Ausência do Zero como Número

Os gregos tinham o conceito de "nada" (*meden*), mas não o zero como número que pode ser somado, subtraído ou multiplicado. O zero posicional (para indicar uma posição vazia numa representação posicional) aparece nos babilônios tardios e na astronomia de Ptolomeu — mas como símbolo de ausência, não como número.

**Por que isso importa:**

Sem zero, a aritmética de potências fica incompleta. $x^2 \div x = x^1$ — aceitável. $x^1 \div x = x^0 = 1$ — requer que $x^0$ faça sentido. Os gregos não teriam escrito $x^0$; teriam dito "a razão de $x$ para $x$, que é a razão de igualdade (1 para 1)". Correto, mas notacionalmente incômodo.

Diofanto usou inversos ($1/x$, $1/x^2$, etc.) como objetos separados — não como $x^{-1}$ e $x^{-2}$. A unificação de potências positivas, zero e negativas num único sistema expoente coerente ($x^n$ para qualquer $n$ inteiro) só aconteceu com a álgebra simbólica do século XVII.

---

### 19.4 O Preço da Elegância: O Que Não Foi Descoberto

Essas limitações aritméticas tiveram consequências concretas para o que a matemática grega pôde alcançar — mas é preciso ser preciso sobre *qual* tipo de resultado ficou fora de alcance.

**A equação cúbica geral — uma distinção importante.** Já vimos, em detalhe, gregos resolvendo equações cúbicas *específicas*: Menaecmo resolveu o problema de Delos (§11.6) por interseção de duas parábolas; Arquimedes reduziu o problema de cortar uma esfera numa razão de volumes dada a uma cúbica e a resolveu pela interseção de uma parábola com uma hipérbole (§14.7); Apolônio encontrou a evoluta cúbica da parábola por métodos puramente geométricos (§15.5). Em nenhum desses casos, porém, havia um **procedimento algébrico geral** — uma fórmula que, dados os coeficientes $a, b, c, d$ de $ax^3+bx^2+cx+d=0$ quaisquer, produzisse a raiz por um número fixo de operações aritméticas. Cada cúbica grega exigia uma construção geométrica nova, desenhada para aquele problema específico.

A **solução geral** da equação cúbica esperaria até 1545, quando Cardano publicou sua fórmula algébrica. A razão da demora é precisamente uma das limitações que vimos: a fórmula de Cardano exige, em alguns casos (quando as três raízes são reais), extrair a raiz quadrada de um número negativo no meio do cálculo — os chamados números complexos —, ainda que o resultado final seja real. Sem números negativos, e muito menos sem raízes de negativos, esse caminho algébrico estava estruturalmente bloqueado para os gregos. Eles podiam *desenhar* a solução de uma cúbica específica; não podiam *calculá-la* por uma fórmula universal.

**As séries infinitas:** Arquimedes somou séries geométricas (na quadratura da parábola, §14.6) e calculou resultados equivalentes a integrais (Conoides e Esferoides, §14.8). Mas nunca desenvolveu uma teoria de séries em geral — o que exigiria uma notação algébrica para o termo geral $a_n$ e para a soma $\sum_{n=0}^{\infty} a_n$. Sem essa notação, cada série era um caso especial tratado geometricamente.

**A teoria dos números algébricos:** Teeteto classificou irracionais da forma $\sqrt{a} \pm \sqrt{b}$ (Livro X dos *Elementos*, §13.8). Mas não havia linguagem para ir além — para tratar $\sqrt[3]{2}$ (a solução do problema de Delos), ou $\sqrt[4]{3}$, ou raízes de polinômios de grau 5 ou mais. A teoria dos números algébricos de Galois (1830), que classifica esses objetos, exige a álgebra simbólica de variáveis e polinômios abstratos.

---

### 19.5 A Solução Grega: Fazer Tudo com Geometria

Diante dessas limitações aritméticas, os gregos desenvolveram uma estratégia coerente: **converter toda álgebra em geometria**.

- Uma equação linear $ax = b$ torna-se "encontrar o segmento $x$ tal que o retângulo de lados $a$ e $x$ seja igual ao retângulo de lados $b$ e $1$" — construção trivial com régua e compasso.

- Uma equação quadrática $x^2 + bx = c$ torna-se "aplicar ao segmento $b$ um retângulo igual a $c$ com excesso de um quadrado" — resolvida pelo Livro II dos *Elementos* (§13.4) e generalizada no Livro VI (§13.6).

- Uma equação cúbica $x^3 = 2a^3$ torna-se "encontrar a aresta do cubo duplicado" — resolvida pela interseção de cônicas (Menaecmo, §11.6).

Essa estratégia funcionou — mas tinha um custo: cada grau de equação exigia uma técnica geométrica nova, e não havia um procedimento unificado que cobrisse todos os casos. A álgebra simbólica, quando chegou, ofereceu exatamente isso: um procedimento uniforme para qualquer grau, sem precisar "desenhar" a equação no plano.

**O contraste com os babilônios:** Os babilônios tinham procedimentos algébricos para equações quadráticas que funcionavam numericamente — "multiplique, adicione, extraia a raiz" (vimos isso em detalhe no Período 1 deste projeto, e de novo em §13.6 ao comparar VI.28–29 com a tábua BM 13901). Não eram rigorosos em termos gregos, mas eram computacionalmente eficientes. Os gregos trocaram eficiência computacional por rigor lógico — uma escolha que moldou a matemática ocidental por dois milênios.

> **Conexão com o projeto:** As limitações da aritmética grega são o espelho exato das limitações da aritmética de ponto fixo em sistemas embarcados. Um processador ARM Cortex-M4 sem unidade de ponto flutuante opera apenas com inteiros — exatamente como a aritmética grega. Algoritmos de controle escritos para esses processadores usam "álgebra geométrica digital": escalam as grandezas por potências de 2 (em vez de construir retângulos), mantêm razões entre inteiros (em vez de frações decimais), e evitam negativos usando representação em complemento de dois (o análogo digital de "reformular o problema para que a solução seja positiva"). A estratégia grega de converter álgebra em geometria tem um descendente direto na estratégia de converter ponto flutuante em ponto fixo nos sistemas de controle do rover.

---

*Fontes desta parte: Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 24 de N — A Aritmética Grega e seus Limites Estruturais (completa — Seção B do apêndice original, integrada)
> **Próxima parte:** Menelau e Herão — A Corrente Secundária
