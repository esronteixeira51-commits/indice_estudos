### 13.6 Os Livros V e VI — A Teoria das Proporções em Ação

O Livro V é, para os matemáticos modernos que entendem o que está em jogo, o mais admirado de toda a obra. Em apenas 25 proposições, Euclides desenvolve formalmente a teoria de proporções que vimos nascer com Eudoxo (§10.2) — e demonstra suas propriedades fundamentais a partir da Definição 5, sem nunca precisar assumir comensurabilidade.

As propriedades demonstradas incluem: se $a:b = c:d$, então $b:a = d:c$ (inversão), $(a+b):b = (c+d):d$ (composição), $a:c = b:d$ (alternação), e outras regras que hoje reconheceríamos como manipulação algébrica de frações — exceto que aqui as "frações" são razões entre grandezas geométricas arbitrárias, potencialmente incomensuráveis, e cada demonstração funciona para todos os casos, sem excluir os irracionais.

O Livro VI aplica essa teoria para demonstrar resultados sobre **figuras semelhantes**: triângulos com os mesmos ângulos têm lados proporcionais; a altura relativa à hipotenusa de um triângulo retângulo o divide em dois triângulos, ambos semelhantes ao original e entre si.

**A demonstração mais curta do Teorema de Pitágoras.** Quando reconstruímos a cadeia de dependências da Proposição I.47 (§13.3), mencionamos que Euclides guardava para mais tarde uma segunda demonstração do mesmo teorema, mais curta, possível apenas depois que a teoria das proporções estivesse rigorosamente fundada. É hora de cumprir essa promessa.

> **Proposição VI.31.** *Em triângulos retângulos, a figura construída sobre o lado que subtende o ângulo reto é igual à soma das figuras semelhantes e similarmente situadas construídas sobre os lados que contêm o ângulo reto.*

A demonstração: seja $ABC$ um triângulo retângulo com o ângulo reto em $C$. Trace a altura $CH$ até a hipotenusa $AB$. Os três triângulos $ACH$, $CBH$ e $ABC$ são todos semelhantes entre si (compartilham ângulos por construção). Como áreas de figuras semelhantes estão entre si na razão dos quadrados dos lados correspondentes (um resultado do próprio Livro VI), temos:

$$\frac{[ACH]}{[ABC]} = \frac{AH}{AB} \qquad \text{e} \qquad \frac{[CBH]}{[ABC]} = \frac{BH}{AB}$$

Somando, e usando que $AH + BH = AB$:

$$\frac{[ACH] + [CBH]}{[ABC]} = \frac{AH+BH}{AB} = 1$$

Mas $[ACH] + [CBH] = [ABC]$ por construção (a altura divide o triângulo original exatamente nesses dois pedaços) — o que confirma a identidade, mas o ponto realmente notável é que o mesmo argumento de proporção, aplicado não a triângulos mas aos **quadrados** sobre cada lado (que são apenas casos particulares de "figuras semelhantes e similarmente situadas"), dá exatamente $a^2 = c \cdot AH$ e $b^2 = c \cdot BH$, onde $c = AB$. Somando, $a^2 + b^2 = c(AH+BH) = c \cdot c = c^2$. É o Teorema de Pitágoras, novamente — agora em três linhas, graças à maquinaria de semelhança que o Livro I não tinha disponível.

Euclides foi além do caso do quadrado: ele observou que a relação vale para *qualquer* figura semelhante construída sobre os três lados — triângulos, pentágonos, ou qualquer polígono, desde que as três figuras sejam semelhantes entre si e estejam posicionadas de forma correspondente. É uma generalização genuína, e os comentadores antigos a atribuem ao próprio Euclides.

**Três caminhos para o mesmo ponto — a média proporcional.** Vale notar algo que conecta esta seção a duas partes anteriores deste capítulo. A Proposição **VI.13** ensina a construir a **média geométrica** entre dois segmentos $a$ e $b$ — isto é, encontrar $x$ tal que $a:x = x:b$, ou $x = \sqrt{ab}$ — usando exatamente o mesmo semicírculo que já vimos duas vezes antes: é a construção que resolve $x^2 = cd$ na Proposição **II.14** (§13.4), e é a mesma construção ponto a ponto que **Menaecmo** usava para desenhar pontos de suas parábolas na busca pela duplicação do cubo (§11.6). Euclides chega ao mesmo resultado por três métodos em três livros diferentes — pela álgebra geométrica de áreas (II.14), pela teoria das proporções e semelhança (VI.13), e implicitamente, pela aplicação prática de Menaecmo. Esse tipo de redundância não é desperdício: é exatamente como a matemática grega consolidava um resultado central, atacando-o repetidamente com ferramentas diferentes até que cada conexão possível estivesse mapeada.

**Resolvendo quadráticas de novo — agora com excesso e deficiência.** O Livro VI completa o ciclo que abrimos na parte anterior sobre a origem dos nomes das cônicas. As Proposições **VI.28** e **VI.29** generalizam a "aplicação de áreas" (§13.4) para os dois casos que faltavam:

> **VI.28 (aplicação deficiente — *elleipsis*).** Aplicar a um segmento dado $AB$ um paralelogramo de área dada $c$, cujo lado é *menor* que $AB$, com o "déficit" sendo um paralelogramo semelhante a um dado.

> **VI.29 (aplicação excedente — *hyperbolé*).** Aplicar a um segmento dado $AB$ um paralelogramo de área dada $c$, cujo lado é *maior* que $AB$, com o "excesso" sendo um paralelogramo semelhante a um dado.

Tomando o paralelogramo dado como um quadrado para simplificar (e seguindo Katz), com $b = AB$, essas duas construções resolvem exatamente as equações quadráticas:

$$bx - x^2 = c \qquad \text{(VI.28, deficiente)} \qquad \qquad bx + x^2 = c \qquad \text{(VI.29, excedente)}$$

com soluções $x = \dfrac{b}{2} \mp \sqrt{\left(\dfrac{b}{2}\right)^2 \mp c}$, respectivamente — a fórmula quadrática, construída geometricamente, ponto por ponto, sem nunca escrever um único símbolo algébrico.

**Uma ponte de volta à Mesopotâmia.** Se você comparar essas duas equações com a álgebra babilônica que vimos no Período 1 deste projeto, vai notar algo notável: a tábua BM 13901 resolvia precisamente $x^2 + \frac{2}{3}x = \frac{7}{12}$ — exatamente a forma $x^2 + bx = c$, a mesma família de VI.29 — usando um método de "cortar e colar" retângulos que é, em espírito, idêntico ao que Euclides faz aqui com gnômons. Esse paralelo levantou, entre historiadores, um debate genuíno e ainda não resolvido: a álgebra geométrica grega seria uma **tradução deliberada** dos resultados quase-algébricos babilônicos para a linguagem geométrica, motivada pela exigência grega de demonstração e pela descoberta de que nem todo segmento pode ser representado por um "número" (a incomensurabilidade, §4.8)? Os argumentos a favor incluem o fato de que as soluções de Euclides espelham de perto as soluções babilônicas de problemas semelhantes, e que o próprio método babilônico já era "geometria ingênua" — um terreno fértil para refinamento grego. Mas não há evidência direta e inequívoca de transmissão cultural: sabemos que a Mesopotâmia esteve sob domínio persa a partir do século VI a.C., em contato regular com os gregos, e que a atividade matemática cuneiforme continuou até período relativamente tardio — então o *contato* era certamente possível. O que falta é a prova documental de que ele de fato ocorreu, com essa finalidade específica. A resposta honesta, como em tantos pontos deste capítulo, é que não sabemos — mas a coincidência estrutural entre as duas tradições, separadas por mais de mil anos e um mar de distância, é demasiado precisa para ser ignorada.

---

*Fontes desta parte: Katz, § 3.3 (continuação) · Boyer, cap. 5 · Struik, cap. III*

---
> **Status:** Parte 12 de N — Euclides: Livros V–VI (completa)
> **Próxima parte:** Livros VII–IX — Teoria dos Números (números primos, perfeitos, o algoritmo de Euclides, a infinitude dos primos)
