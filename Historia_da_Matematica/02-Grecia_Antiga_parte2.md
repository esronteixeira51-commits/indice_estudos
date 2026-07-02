## 4. Os Pitagóricos: Quando o Número Tentou Ser o Cosmo

Nenhuma escola do pensamento antigo misturou tanto misticismo e matemática rigorosa quanto os **Pitagóricos**. Fundada por **Pitágoras de Samos** (c. 570–495 a.C.) — figura lendária que teria estudado em Babilônia e no Egito —, a escola estabeleceu-se em Crotona, no sul da Itália, como uma irmandade filosófica e política de orientação quase monástica: propriedade comum, sigilo rigoroso, regras dietéticas, e um culto ao conhecimento que misturava religião órfica com investigação racional.

Pitágoras era, ao contrário de Tales, primariamente um profeta e um místico. Mas o que diferencia os Pitagóricos de uma seita religiosa qualquer é que a base de sua doutrina era a matemática — não como ferramenta de cálculo, mas como chave do cosmos.

Enquanto os sofistas e atomistas celebravam a mudança e a matéria, os Pitagóricos buscavam o **eterno e o imutável**. E o que há de mais eterno do que os números? Seu programa pode ser resumido numa frase que a tradição lhes atribui: *"Tudo é número."*

### 4.1 O Misticismo dos Números

Para os Pitagóricos, os números não eram abstrações neutras — tinham personalidades, gênero e poder moral.

O **um** era o gerador de todos os números, o número da razão. O **dois** era o primeiro par, feminino, o número da opinião. O **três** era o primeiro número masculino verdadeiro, o da harmonia — pois combina unidade (1) e diversidade (2). O **quatro** era o número da justiça, por ser o primeiro quadrado perfeito. O **cinco** era o casamento, união do primeiro feminino (2) com o primeiro masculino verdadeiro (3). O **seis** era a criação.

Mas o número mais sagrado era o **dez** — o *tetractys*. Dez é a soma 1+2+3+4, e esses quatro números representam as quatro dimensões possíveis da existência: o ponto (1), a reta (2 pontos), o plano (3 pontos não colineares) e o espaço (4 pontos não coplanares). O dez encerrava o universo inteiro em uma única figura triangular de pontos:

```
    •
   • •
  • • •
 • • • •
```

Os Pitagóricos juravam seus votos pelo tetractys. A veneração ao número dez não era ditada pela anatomia dos dedos — era uma dedução geométrica sobre a estrutura do espaço. Que um grupo filosófico chegasse a essa conclusão por raciocínio é, em si mesmo, notável.

### 4.2 Números Figurados — e Como Eles Geram Ternas Pitagóricas

Os Pitagóricos tornavam os números visíveis ao arranjá-los em padrões de pedrinhas (*psephoi*) — o equivalente grego ao ábaco, mas usado para descobrir teoremas, não apenas para calcular.

Os **números triangulares** (1, 3, 6, 10, 15…) têm fórmula geral $T_n = n(n+1)/2$. São construídos empilhando linhas de pontos: uma linha com 1, depois 2, depois 3, e assim por diante.

Os **números quadrados** (1, 4, 9, 16…) revelam algo elegante: a diferença entre quadrados consecutivos é sempre um número ímpar — 4−1=3, 9−4=5, 16−9=7. Em outras palavras, $n^2$ é a soma dos $n$ primeiros ímpares. Os ímpares eram chamados *gnômons* porque, dispostos em forma de L em torno de dois lados de um quadrado, geram o próximo quadrado:

```
1   →   1+3=4   →   4+5=9   →   9+7=16
•       • •         • • •       • • • •
        • •         • • •       • • • •
                    • • •       • • • •
                                • • • •
```

Cada gnômon é literalmente visível na figura: para passar de um quadrado de lado $n-1$ para um de lado $n$, basta acrescentar uma faixa em L de $2n-1$ pontos — uma fileira ao longo de cada um dos dois lados, mais o ponto do canto. Não é uma fórmula abstrata decorada; é uma manobra com pedras sobre uma mesa, e o resultado geral — que a soma dos $n$ primeiros ímpares é sempre $n^2$ — fica demonstrado pela própria construção, sem necessidade de álgebra.

A sequência dos pares $2+4+6+\cdots+2n = n(n+1)$ gerava os **números oblongos**, cada um o dobro de um triangular: $2T_n = n(n+1)$. E há um teorema visualmente imediato que conecta as duas famílias — qualquer número quadrado é a soma de dois triangulares consecutivos:

$$n^2 = T_{n-1} + T_n$$

Basta sobrepor mentalmente um triângulo de lado $n-1$ a outro de lado $n$, encaixados em diagonal: juntos preenchem exatamente um quadrado de lado $n$. Verificação numérica: $T_3 + T_4 = 6 + 10 = 16 = 4^2$. ✓

**Da figura geométrica à terna pitagórica.** A propriedade do gnômon não serve apenas para somar ímpares — ela é, na verdade, uma máquina de gerar ternas pitagóricas. Considere um gnômon cujo valor $n$ (sendo $n$ ímpar) é, ele próprio, um quadrado perfeito. Isso significa que dois quadrados consecutivos diferem por um quadrado perfeito — exatamente a relação $a^2 + b^2 = c^2$.

A regra é direta: para qualquer $n$ ímpar maior que 1,

$$\left(n,\ \frac{n^2-1}{2},\ \frac{n^2+1}{2}\right)$$

é sempre uma terna pitagórica. A lógica: o gnômon de valor $n^2$ separa o quadrado de lado $(n^2-1)/2$ do quadrado de lado $(n^2+1)/2$ — e esses dois lados diferem em exatamente uma unidade, garantindo que a conta sempre funcione.

| $n$ (ímpar) | $\frac{n^2-1}{2}$ | $\frac{n^2+1}{2}$ | Terna | Verificação |
|---|---|---|---|---|
| 3 | 4 | 5 | (3, 4, 5) | $9+16=25$ ✓ |
| 5 | 12 | 13 | (5, 12, 13) | $25+144=169$ ✓ |
| 7 | 24 | 25 | (7, 24, 25) | $49+576=625$ ✓ |
| 9 | 40 | 41 | (9, 40, 41) | $81+1600=1681$ ✓ |

Para $n$ par, a regra correspondente usa $m = n/2$:

$$\left(n,\ m^2-1,\ m^2+1\right)$$

Exemplo: $n=8$, $m=4$: $(8,\ 15,\ 17)$. Verificação: $64 + 225 = 289 = 17^2$ ✓.

Esse mecanismo é importante por uma razão que ultrapassa a curiosidade aritmética: ele mostra que os Pitagóricos não apenas *conheciam* casos isolados do teorema que levaria seu nome — tinham um **método sistemático e demonstrável** para gerar infinitas ternas. É uma sofisticação diferente da que vimos na tábua babilônica Plimpton 322 (Período 1): os babilônios geravam ternas por um procedimento algébrico em base sexagesimal sem registrar o porquê; os Pitagóricos derivavam o mesmo resultado de uma figura geométrica visível, cujo funcionamento qualquer membro da irmandade podia verificar pessoalmente, pedra por pedra.

Havia ainda números pentagonais, hexagonais e poliedrais — uma taxonomia geométrica inteira dos inteiros, que Euclides herdaria e formalizaria nos Livros VII–IX dos *Elementos*.

### 4.3 Proporções, Música e as Dez Médias

Os Pitagóricos descobriram que as consonâncias musicais correspondem a razões simples entre inteiros. Uma oitava é a razão 2:1 entre comprimentos de corda vibrante; uma quinta perfeita, 3:2; uma quarta, 4:3. O universo inteiro, imaginavam eles, funcionaria por proporções análogas — a chamada *harmonia das esferas*.

Distinguiram inicialmente três tipos de proporção, com exemplos concretos:

**Aritmética:** $b - a = c - b$, ou seja, $2b = a + c$.
Exemplo: 2, 5, 8 — as diferenças são sempre 3. É a média que usamos no dia a dia.

**Geométrica:** $b/a = c/b$, ou seja, $b^2 = ac$.
Exemplo: 2, 6, 18 — as razões são sempre 3. É a média dos juros compostos.

**Harmônica:** $2/b = 1/a + 1/c$.
Exemplo: 3, 4, 6 — verifique: $2/4 = 1/3 + 1/6 = 1/2$. ✓
É a média que aparece em velocidade média de ida e volta, e em resistores em paralelo.

Arquitas de Tarento e seus sucessores generalizaram o sistema para **dez médias**, cobrindo todas as relações proporcionais fundamentais entre três grandezas $a < b < c$. As três primeiras são as clássicas acima; as demais, como $(b-a)/(c-b) = a/c$ (quarta média) ou $(c-a)/(b-a) = c/a$ (sétima média), cobrem relações menos imediatas mas matematicamente completas. Esse sistema era o núcleo da teoria das proporções pitagórica e fornecia linguagem matemática para descrever desde a harmonia musical até as proporções dos polígonos regulares.

### 4.4 A Seção Áurea e o Pentágono

O símbolo secreto da irmandade pitagórica era a **estrela de cinco pontas** — o pentágono estrelado, formado traçando as cinco diagonais de um pentágono regular. E essa figura escondia uma proporção que os Pitagóricos chamavam simplesmente de "a secção" (*tomé*), hoje conhecida como **seção áurea**.

Considere um segmento $RS$ de comprimento $a$. O ponto $P_1$ o divide em *média e extrema razão* quando o segmento inteiro está para a parte maior como a parte maior está para a menor:

$$\frac{a}{x} = \frac{x}{a - x}$$

Multiplicando cruzado: $x^2 = a(a-x)$, ou seja:

$$x^2 + ax - a^2 = 0$$

Sua solução positiva é $x = a\,(\sqrt{5}-1)/2 \approx 0{,}618\,a$. A razão $a/x = (\sqrt{5}+1)/2 \approx 1{,}618$ é hoje chamada $\phi$ (phi), a razão áurea.

O que torna essa proporção fascinante é uma propriedade iterativa: se $P_1$ divide $RS$ em seção áurea, e marcamos $P_2$ sobre o segmento maior $RP_1$ tal que $RP_2 = P_1S$, então $P_2$ divide $RP_1$ novamente em seção áurea. O processo se repete indefinidamente, produzindo segmentos cada vez menores sempre na mesma proporção — uma estrutura autossimilar. No pentágono, cada diagonal é dividida pelas outras exatamente nessa razão, e o pentágono menor formado no centro tem as mesmas proporções do original.

Kepler escreveria dois mil anos depois: "A geometria tem dois grandes tesouros: um é o teorema de Pitágoras; o outro, a divisão de um segmento em média e extrema razão. O primeiro pode ser comparado a uma medida de ouro; o segundo podemos chamar de joia preciosa."

### 4.5 O Teorema de Pitágoras — e o que os Babilônios Não Perceberam

O teorema que leva o nome de Pitágoras era conhecido pelos babilônios como relação numérica entre lados de triângulos específicos. O que os Pitagóricos fizeram foi concebê-lo como **proposição geométrica universal** — válida para *qualquer* triângulo retângulo, demonstrável por argumento lógico, independente de qualquer medição.

Onde a Babilônia via: "o lado 3 e o lado 4 dão hipotenusa 5", os Pitagóricos viram: "o quadrado construído sobre a hipotenusa tem área igual à soma dos quadrados construídos sobre os catetos." A diferença não é de conteúdo — é de *escopo* e de *método*. O resultado babilônio é uma receita verificada por casos; o resultado pitagórico é um teorema derivado de princípios, aplicável a todos os casos de uma só vez.

A prova mais simples usa rearranjo de áreas: construa um quadrado de lado $(a+b)$ e preencha-o de dois modos diferentes — em ambos, quatro triângulos retângulos de catetos $a$ e $b$ deixam um resíduo. No primeiro modo, o resíduo é o quadrado $c^2$; no segundo, são os quadrados $a^2$ e $b^2$. Como as áreas totais são iguais, $c^2 = a^2 + b^2$.

### 4.6 Filolau e o Universo Numérico

O pitagórico **Filolau de Tarento** (c. 470–390 a.C.) foi o primeiro a escrever uma exposição sistemática do pitagorismo — e suas ideias ilustram até onde a fé no número podia levar.

Filolau postulou o primeiro sistema astronômico não geocêntrico da história. No centro do universo, dizia ele, há um **fogo central** em torno do qual giram dez corpos: a Contra-Terra (invisível a nós), a Terra, a Lua, o Sol, os cinco planetas e a esfera das estrelas fixas. Por que dez? Porque o tetractys exige dez. O universo foi construído para satisfazer o número sagrado.

A Contra-Terra nunca é vista porque a Terra mantém sempre a mesma face voltada para o fogo central, e habitamos o lado oposto. O Sol não emite luz própria — reflete a luz do fogo. É um sistema fisicamente absurdo, mas matematicamente ousado: **a Terra se move**, e o geocentrismo não é uma necessidade lógica. Copérnico, quase dois mil anos depois, citaria os pitagóricos para argumentar que sua doutrina da Terra móvel não era tão revolucionária quanto parecia.

### 4.7 Aritmética e Logística

A relação dos Pitagóricos com o cálculo numérico era ambivalente — e essa ambivalência se tornaria uma característica permanente da matemática grega. Eles faziam uma distinção clara entre dois tipos de prática numérica:

**Aritmética** (*arithmetiké*): o estudo teórico das propriedades dos inteiros — o que é um número primo, o que é um número perfeito, como as razões se relacionam. Uma disciplina intelectual, vizinha da filosofia.

**Logística** (*logistiké*): o cálculo prático — contar, medir, computar impostos, dividir heranças. Uma disciplina manual, relegada a mercadores e soldados.

Ao elevar a aritmética ao status de filosofia e rebaixar o cálculo a artesanato, os Pitagóricos criaram uma matemática que preferia a elegância à computação — que demonstra que $\sqrt{2}$ é irracional mas não calcula quanto ele vale. Essa tensão entre o rigoroso e o computacional atravessa toda a história da matemática grega, e tem uma raiz que já examinamos: o próprio sistema de numeração jônico (§2) tornava o cálculo numérico desajeitado, o que reforçava — e talvez tenha causado — essa preferência filosófica pela geometria.

### 4.8 A Catástrofe dos Irracionais

E aqui os Pitagóricos toparam com a maior crise da matemática antiga.

Se "tudo é número" — entendendo-se por número as razões entre inteiros —, então qualquer grandeza geométrica deveria ser expressa por uma fração. Mas considere o quadrado de lado 1: quanto mede sua diagonal?

Pelo teorema de Pitágoras: $d^2 = 1^2 + 1^2 = 2$, portanto $d = \sqrt{2}$.

Será $\sqrt{2}$ igual a uma fração $p/q$ com $p$ e $q$ inteiros sem fator comum?

Suponha que sim. Então $p^2 = 2q^2$, logo $p^2$ é par, logo $p$ é par — escreva $p = 2r$. Substituindo: $4r^2 = 2q^2$, portanto $q^2 = 2r^2$, logo $q$ também é par. Mas se $p$ e $q$ são ambos pares, compartilham o fator 2 — contradizendo a hipótese.

$\sqrt{2}$ **não é racional**. É *incomensurável* com a unidade.

A descoberta pode ter vindo não do quadrado, mas do **pentágono**. A propriedade iterativa da seção áurea implica que a razão diagonal/lado no pentágono regular é também irracional — o processo de divisão nunca termina, sem encontrar jamais uma unidade comum às duas grandezas. Se foi essa a rota, o próprio símbolo sagrado da irmandade carregava a prova de que o fundamento da irmandade era falso.

A tradição atribui a descoberta a **Hipasus de Metaponto**, pitagórico que teria revelado o segredo e sido expulso da irmandade — ou, segundo versões mais dramáticas, afogado no mar pelos próprios irmãos. A história é provavelmente lendária, mas reflete a profundidade da crise: a incomensurabilidade não era um problema técnico a ser contornado. Era a demonstração de que o programa inteiro dos Pitagóricos — o universo explicado por razões de inteiros — estava errado em seus próprios termos.

Os gregos a resolveram não ampliando o conceito de número — como faríamos hoje ao introduzir os irracionais na reta real — mas **rejeitando o número como ferramenta universal**. Grandezas geométricas passariam a ser tratadas geometricamente, por comparação direta de comprimentos e áreas, sem passar por números. Essa decisão, tomada no final do século V a.C., moldou a matemática grega por duzentos anos — até que Eudoxo criasse uma teoria das proporções capaz de contornar o problema com rigor completo.

Vale notar que Aristóteles, ao comentar a descoberta um século depois, observou que a incomensurabilidade, uma vez compreendida, deixa de ser surpreendente para qualquer geômetra — é simplesmente uma consequência de como números e grandezas se relacionam. O que parecia catástrofe filosófica tornou-se, com o tempo, um fato matemático tranquilo. Mas o caminho até essa tranquilidade exigiu retrabalhar os fundamentos inteiros da disciplina.

> **Conexão com o projeto:** A distinção entre aritmética (teoria) e logística (cômputo) ressurge na engenharia moderna como a distinção entre modelagem matemática e implementação numérica. Um controlador PID para estabilização do rover é matematicamente elegante em teoria contínua — mas sua implementação real usa aritmética de ponto flutuante com erros de truncamento, exatamente o tipo de problema que a logística resolve e que a aritmética pitagórica ignorava. E o próprio mecanismo de geração de ternas pitagóricas por gnômons tem eco direto em algoritmos de geração de coordenadas inteiras usados em sistemas de visão computacional do rover, onde se busca economia computacional evitando operações de ponto flutuante sempre que uma relação exata entre inteiros resolve o problema.

---

*Fontes desta parte: Boyer, cap. 4 · Katz, §§ 2.1.3–2.2 · Struik, cap. III*

---
> **Status:** Parte 2 de N — Os Pitagóricos (completa)
> **Próxima parte:** A Idade Heroica — Hipócrates de Quios, Hípias de Elis e os Três Problemas Clássicos
