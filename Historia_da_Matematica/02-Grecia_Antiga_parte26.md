## 21. Diofanto de Alexandria — A Álgebra que os Gregos Esqueceram

**Diofanto de Alexandria** (c. 250 d.C.) é um dos personagens mais enigmáticos da matemática antiga. Não sabemos quando nasceu, não sabemos quando morreu, não sabemos onde estudou. A única "biografia" que temos é um enigma numérico preservado na *Antologia Grega*, que serve como exercício de equação linear:

> *"Deus concedeu a Diofanto ser menino por um sexto de sua vida; depois, acrescentando um doze avos, cobriu seu rosto de penugem. Após um sétimo mais, acendeu a lâmpada do matrimônio; e cinco anos após seu casamento, deu-lhe um filho. Ai! criança tardia e infeliz — após atingir a metade da vida do pai, o Destino frio o levou. Depois de consolar sua dor com a ciência dos números por quatro anos, Diofanto terminou sua vida."*

Seja $x$ a idade de Diofanto ao morrer. Então:

$$\frac{x}{6} + \frac{x}{12} + \frac{x}{7} + 5 + \frac{x}{2} + 4 = x$$

$$x\left(\frac{1}{6} + \frac{1}{12} + \frac{1}{7} + \frac{1}{2}\right) + 9 = x$$

$$x \cdot \frac{14 + 7 + 12 + 42}{84} + 9 = x \implies x \cdot \frac{75}{84} + 9 = x \implies 9 = x \cdot \frac{9}{84} \implies x = 84$$

Diofanto viveu 84 anos. Se o enigma é biográfico, passou 14 anos como criança, 7 como adolescente, 12 como jovem adulto, casou-se aos 33, teve um filho aos 38, perdeu o filho aos 80, e passou os últimos quatro anos com a matemática como consolo.

Mas o que importa não é a vida de Diofanto — é o que ele escreveu.

---

### 21.1 A Arithmetica — Um Livro sem Precedente, e um Mistério de Transmissão

A obra principal de Diofanto, a **Arithmetica**, era originalmente em treze livros. Seis chegaram até nós em grego; outros quatro foram encontrados em tradução árabe no século XX e publicados em 1983. Os três restantes estão perdidos.

**Um detalhe que muda a forma de ler os "livros árabes".** Há algo curioso sobre esses quatro livros adicionais que vale registrar antes de prosseguir. O estilo deles é perceptivelmente diferente do estilo dos seis livros gregos: cada passo da solução é explicado com mais detalhe, de forma mais didática. Isso levou os estudiosos a uma hipótese intrigante — talvez o texto árabe não seja uma tradução do **original** de Diofanto, mas sim de um **comentário** sobre a *Arithmetica* escrito por **Hipátia de Alexandria**, por volta do ano 400 d.C. Se essa hipótese estiver correta, o que os matemáticos lêem hoje como "Livros IV a VII de Diofanto" pode ser, na verdade, a obra de Hipátia *explicando* Diofanto — preservada, paradoxalmente, com mais fidelidade do que os textos originais do próprio autor que ela comentava. Voltaremos a Hipátia e seu papel na transmissão do conhecimento matemático mais adiante neste capítulo.

A *Arithmetica* é uma coleção de aproximadamente 150 problemas resolvidos — mas não é um livro de exercícios comum. É um tratado de álgebra disfarçado de coleção de problemas: cada problema ilustra uma técnica, cada técnica resolve uma classe de equações.

O que torna a *Arithmetica* única na matemática antiga é seu **duplo afastamento** das tradições que a precederam:

**1. Afasta-se da geometria grega:** Euclides, Arquimedes e Apolônio representavam números por segmentos de reta, operações por áreas e volumes. Diofanto opera com números abstratos — sem nenhuma referência geométrica. Suas incógnitas são números, não segmentos. Suas soluções são números, não construções.

**2. Afasta-se da tradição babilônica:** Os babilônios aceitavam soluções aproximadas e trabalhavam com exemplos numéricos específicos sem nenhuma noção de generalidade. Diofanto exige soluções **exatas e racionais**, e seus métodos — embora apresentados em exemplos — têm a estrutura de técnicas gerais.

A *Arithmetica* fica num espaço singular: mais abstrata que a matemática babilônica, mais algébrica que a matemática grega clássica, mais precisa que qualquer coisa que vinha antes.

---

### 21.2 A Álgebra Sincopada — Meio Caminho para o Simbolismo

O desenvolvimento histórico da álgebra passa por três estágios:

| Estágio | Características | Exemplos |
|---|---|---|
| **Retórico** | Tudo escrito em palavras | Papiro Ahmes, tabletes babilônicos |
| **Sincopado** | Abreviações para termos recorrentes | **Diofanto** |
| **Simbólico** | Símbolos abstratos com regras formais | Viète (1591), Descartes (1637) |

Diofanto estava no segundo estágio — e estava séculos à frente de seus contemporâneos.

**As abreviações de Diofanto:**

| Conceito | Símbolo de Diofanto | Equivalente moderno |
|---|---|---|
| Incógnita | $\varsigma$ (contração das duas primeiras letras de *arithmos*, número) | $x$ |
| Quadrado da incógnita | $\Delta^{\upsilon}$ (*dynamis*) | $x^2$ |
| Cubo da incógnita | $K^{\upsilon}$ (*kubos*) | $x^3$ |
| Quarta potência | $\Delta^{\upsilon}\Delta$ | $x^4$ |
| Quinta potência | $\Delta K^{\upsilon}$ | $x^5$ |
| Sexta potência | $K^{\upsilon}K$ | $x^6$ |
| Unidade | $M̊$ (de *monas*, unidade) | constante |
| Inverso da incógnita | $\varsigma^{-1}$ | $1/x$ |
| Subtração | $\Lambda$ (uma espécie de menos) | $-$ |

**Exemplo:** O que hoje escrevemos como $3x^2 + 12x + 9$ Diofanto escrevia, nos manuscritos sobreviventes, como uma sequência de símbolos equivalente a "$\Delta^{\upsilon}$ três, $\varsigma$ doze, $M̊$ nove" — três quadrados, doze números, nove unidades. Note que mesmo $\varsigma$ e $M̊$, os símbolos mais básicos, são abreviações de palavras gregas comuns — não invenções arbitrárias.

É notação estranha para nós — mas foi um salto enorme em relação a escrever "o cubo de um número menos duas vezes o seu quadrado mais dez vezes o número menos uma unidade".

**A regra dos sinais.** Diofanto também enunciou explicitamente a regra para multiplicar termos com subtração: uma quantidade subtrativa multiplicada por outra quantidade subtrativa resulta numa quantidade aditiva; uma subtrativa multiplicada por uma aditiva resulta numa subtrativa. É exatamente a nossa regra "menos vezes menos é mais" — mas é importante entender o que Diofanto *não* estava fazendo: ele não lidava com números negativos como entidades autônomas (que, como vimos em §19.2, não existiam para os gregos). Estava apenas descrevendo como tratar termos que aparecem com o sinal de subtração dentro de uma única expressão — uma regra sobre *manipulação simbólica*, não sobre uma nova classe de números.

**O que faltava para o simbolismo completo:**
- Símbolos para operações entre termos ($+$, $-$, $=$).
- Notação para múltiplas incógnitas ($x$, $y$, $z$).
- A noção de que a letra representa uma quantidade *variável*, não apenas uma incógnita específica.

Esses elementos viriam com Viète (1591) e Descartes (1637) — 1.300 anos depois.

---

### 21.3 Os Problemas Determinados — Equações com Uma Solução

Os primeiros livros da *Arithmetica* tratam de **equações determinadas** — sistemas com número igual de equações e incógnitas, cujas soluções são únicas (ou em número finito).

**Exemplo I.15:** Encontrar dois números tais que sua soma seja $20$ e a soma de seus quadrados seja $208$.

Diofanto não usa duas incógnitas. Usa **uma**: seja o maior número $10 + x$ e o menor $10 - x$ (a soma é automaticamente 20). Então:

$$(10+x)^2 + (10-x)^2 = 208$$
$$200 + 2x^2 = 208$$
$$x^2 = 4 \implies x = 2$$

Os números são $12$ e $8$.

**A técnica:** Diofanto quase sempre reduz o problema a uma variável, escolhendo as incógnitas de forma inteligente para satisfazer automaticamente uma das condições. Essa é a habilidade central da *Arithmetica* — e por ela Diofanto merece ser chamado algebrista, mesmo que não tivesse o simbolismo completo.

**Exemplo II.8:** Dividir um quadrado em dois quadrados.

"Dado o quadrado $16$, dividi-lo em dois quadrados."

Seja um dos quadrados $x^2$. O outro deve ser $16 - x^2$, e deve também ser um quadrado perfeito. Diofanto escreve o segundo como $(2x - 4)^2$ (uma escolha engenhosa que garante que a diferença seja um quadrado para qualquer $x$):

$$(2x-4)^2 = 16 - x^2$$
$$4x^2 - 16x + 16 = 16 - x^2$$
$$5x^2 = 16x \implies x = \frac{16}{5}$$

Os dois quadrados são $\left(\frac{16}{5}\right)^2 = \frac{256}{25}$ e $\left(\frac{12}{5}\right)^2 = \frac{144}{25}$.

Verificação: $\frac{256}{25} + \frac{144}{25} = \frac{400}{25} = 16$. ✓

Esse problema — **II.8** — foi o que, 1.400 anos depois, levou Fermat ao seu Último Teorema (§21.5).

---

### 21.4 A Análise Diofantina — Equações Indeterminadas, e um Encontro Acidental com Curvas Elípticas

A parte mais original e influente da *Arithmetica* é a **análise diofantina**: a resolução de equações com menos equações do que incógnitas, buscando soluções racionais ou inteiras.

Uma equação diofantina típica tem infinitas soluções reais, mas talvez nenhuma, finitas ou infinitas soluções **racionais** — e Diofanto procurava especificamente as racionais (ou inteiras positivas).

**Exemplo III.5:** Encontrar três números tais que o produto de quaisquer dois, somado ao terceiro, seja um quadrado perfeito.

Seja os três números $x$, $y$, $z$. As três condições são:
$$xy + z = \square, \quad xz + y = \square, \quad yz + x = \square$$

Diofanto resolve tentando $z = 1$, e escolhendo $x$ e $y$ de forma que as primeiras duas condições sejam satisfeitas automaticamente, depois verificando a terceira.

O método gera uma solução — não todas as soluções. Diofanto nunca reclama que encontrou todas as soluções; encontrar uma já era suficiente para o propósito.

**Um método emprestado do Egito.** A partir do Livro IV, Diofanto começa a usar uma técnica que é, em espírito, exatamente a **falsa posição** dos escribas egípcios que vimos no Período 1 deste projeto — embora aplicada aqui a um contexto algébrico muito mais sofisticado: ele escolhe uma forma particular e conveniente para a incógnita, contendo um parâmetro livre, e depois ajusta esse parâmetro para satisfazer a equação.

**Um problema (IV.24) que antecipa, sem saber, a ferramenta que resolveria Fermat.** Considere o problema: dividir um número dado $a$ em duas partes $y$ e $a-y$, tais que o produto dessas partes seja igual ao cubo de um número menos esse próprio número:

$$y(a-y) = x^3 - x$$

Diofanto escolhe $a = 6$ e busca $x$ na forma $x = my - 1$ (a constante $-1$ é escolhida deliberadamente para eliminar o termo constante da equação resultante). Testando $m=2$: $x = 2y-1$, e a equação se torna $6y - y^2 = (2y-1)^3 - (2y-1) = 8y^3 - 12y^2+4y$ — uma equação cúbica em $y$ que Diofanto então resolve para o caso específico.

**Por que isso importa tanto hoje:** A equação $y(a-y) = x^3-x$ — cúbica numa variável, quadrática na outra — é exatamente o tipo de objeto que a matemática moderna chama de **curva elíptica**. Diofanto não tinha a menor ideia disso, claro: o conceito de curva elíptica como objeto geométrico-algébrico autônomo só seria formalizado no século XIX. Mas o fato de que problemas da *Arithmetica* geram, sistematicamente, equações dessa forma exata é a razão profunda pela qual a demonstração do Último Teorema de Fermat — que nasceu de uma nota à margem de um exemplar da *Arithmetica* (§21.5) — precisou, 1.750 anos depois, da teoria das curvas elípticas e das formas modulares para ser completada. Diofanto plantou, sem saber, tanto a pergunta quanto uma pista sobre a ferramenta que um dia a resolveria.

**Diofanto e a impossibilidade — quase Fermat, sem nunca dizer.** Há um padrão sutil e revelador em vários pontos da *Arithmetica*: Diofanto evita silenciosamente alguns problemas específicos. Ele resolve "encontrar dois quadrados cuja soma é um quadrado" (é o próprio II.8) e "encontrar três quartas potências cuja soma é um quadrado" (V.29) — mas nunca tenta, em nenhum lugar do texto sobrevivente, "encontrar dois **cubos** cuja soma é um **cubo**", nem "duas quartas potências cuja soma é um quadrado". Essas omissões não são acidentais: ambos os problemas são, de fato, **impossíveis** — exatamente o caso $n=3$ do que se tornaria o Último Teorema de Fermat. Há indícios de que matemáticos árabes já reconheciam essa impossibilidade desde o século X. É bastante provável que o próprio Diofanto tenha tentado esses problemas, falhado, e simplesmente os omitido — sem nunca declarar ou demonstrar a impossibilidade.

Num único momento da *Arithmetica* (problema D.11, um dos livros recuperados em árabe), Diofanto chega a mencionar explicitamente uma impossibilidade: depois de resolver um problema relacionado, ele observa que não é possível encontrar um quadrado que, somado a cada uma de duas partes em que se divide, resulte sempre num quadrado — e por isso passa a um problema "que é possível" em vez desse. Por trás dessa observação está o fato (demonstrável hoje por um argumento simples de congruência módulo 4) de que o número $3$ não pode ser escrito como soma de dois quadrados racionais. Diofanto não oferece prova — apenas constata o fato e segue adiante. É o mais próximo que ele chega de declarar, por escrito, "isto é impossível" — e mesmo assim, sem nunca demonstrar por quê.

**A "equação de Pell":** Entre os problemas da *Arithmetica* há casos da forma $x^2 - Dy^2 = 1$ (para $D$ não quadrado perfeito), como $x^2 - 30y^2 = 1$ e $x^2 - 26y^2 = 1$. Essas equações foram estudadas sistematicamente pelos indianos (Brahmagupta, 628 d.C.) e pelos europeus medievais, e receberam o nome (errôneo) de "equação de Pell" do matemático inglês John Pell (século XVII). Diofanto as encontrou como casos particulares sem desenvolver uma teoria geral.

**Exemplo de equação de Pell ($D=2$):** $x^2 - 2y^2 = 1$.

Soluções inteiras: $(x, y) = (1, 0)$, $(3, 2)$, $(17, 12)$, $(99, 70)$, $(577, 408)$, ...

A regra de recorrência: $(x_{n+1}, y_{n+1}) = (3x_n + 4y_n, \; 2x_n + 3y_n)$. As razões $x_n/y_n$ convergem para $\sqrt{2}$: $1, 3/2, 17/12, 99/70, 577/408, \ldots = 1{,}41421356\ldots$ — aproximações cada vez melhores do irracional.

---

### 21.5 O Último Teorema de Fermat — Uma Nota à Margem

Em 1637, **Pierre de Fermat** estava lendo a *Arithmetica* de Diofanto na tradução latina de Bachet (1621). Ao chegar ao problema II.8 — dividir um quadrado em dois quadrados — escreveu na margem do livro:

> *"É impossível dividir um cubo em dois cubos, uma quarta potência em duas quartas potências, e em geral qualquer potência maior que dois em duas potências do mesmo grau. Tenho uma demonstração verdadeiramente maravilhosa disso, mas esta margem é pequena demais para contê-la."*

Em linguagem moderna: a equação $x^n + y^n = z^n$ não tem soluções em inteiros positivos para $n > 2$.

Para $n = 2$: existem infinitas soluções (as ternas pitagóricas: $3^2 + 4^2 = 5^2$, $5^2 + 12^2 = 13^2$, ...).

Para $n = 3$: **nenhuma solução** (demonstrado por Euler em 1770) — exatamente o caso que, como vimos em §21.4, o próprio Diofanto provavelmente já suspeitava e silenciosamente evitou, dezessete séculos antes.

Para $n = 4$: **nenhuma** (demonstrado pelo próprio Fermat).

Para $n = 5$: **nenhuma** (Dirichlet e Legendre, 1825).

Para $n$ geral: **nenhuma** — mas a demonstração levou **358 anos** e o trabalho de dezenas de matemáticos. Foi completada por **Andrew Wiles** em 1995, usando geometria algébrica do século XX (curvas elípticas e formas modulares) que Fermat certamente não conhecia — mas que, como vimos, já espreitava, sem nome, dentro da própria *Arithmetica* que Fermat estava lendo. A nota à margem foi, provavelmente, um erro de Fermat — a demonstração que ele acreditava ter era muito provavelmente falha.

O teorema é hoje o mais famoso da matemática — e teria permanecido desconhecido se Fermat não estivesse lendo Diofanto.

---

### 21.6 O Lugar de Diofanto na História

A posição de Diofanto na história da álgebra é simultaneamente central e marginal.

**Central** porque:
- É o único matemático grego que praticou álgebra no sentido moderno — manipulação de incógnitas numéricas abstratas.
- Suas técnicas para equações indeterminadas são genuinamente originais e influenciaram diretamente os matemáticos árabes (al-Karaji, al-Khayyam) e europeus medievais.
- O problema II.8 gerou o Último Teorema de Fermat — o problema que mais motivou o desenvolvimento da álgebra e da teoria dos números nos séculos XVII–XX.

**Marginal** porque:
- Não desenvolveu notação simbólica completa — ficou no estágio sincopado.
- Não tinha uma teoria geral das equações — resolvia casos específicos.
- Não usava números negativos ou zero como objetos matemáticos autônomos.
- Sua influência direta na matemática grega foi mínima — seus contemporâneos não desenvolveram suas ideias.

O salto de Diofanto para a álgebra simbólica de Viète e Descartes precisou de 1.300 anos e passou pela Índia e pelo mundo árabe — onde al-Khwarizmi (820 d.C.) e al-Karaji (1000 d.C.) desenvolveram as ideias de Diofanto em direções que os gregos nunca tentaram.

**O contraste com Arquimedes:** Arquimedes foi o ponto mais alto da tradição geométrica grega — e seus sucessores imediatos ficaram muito aquém dele. Diofanto foi o ponto mais alto da tradição algébrica grega — e igualmente não teve sucessores imediatos à sua altura. As duas tradições paralelas da matemática grega — a geométrica e a algébrica — atingiram seus picos separadamente, sem nunca se fundir na Antiguidade.

A fusão só ocorreu com Descartes em 1637 — quando a geometria analítica finalmente uniu as duas tradições numa única linguagem. E o problema que serviu de teste para a nova linguagem de Descartes foi o problema de Papus-Apolônio (§15.6). A geometria de Apolônio e a álgebra de Diofanto, mil anos depois de separadas, tornaram-se a mesma coisa.

> **Conexão com o projeto:** A análise diofantina — encontrar soluções inteiras ou racionais de sistemas subdeterminados — é o problema central do **planejamento discreto de trajetórias**: dado um conjunto de posições alvo e restrições de tempo (valores inteiros de passos de controle), encontrar uma sequência de comandos que satisfaça as restrições. Os algoritmos de programação inteira usados no planejamento de missões do rover são descendentes diretos dos métodos de Diofanto, formalizados pela programação linear inteira de Dantzig (1947) e pelos algoritmos de ramificação e limitação. O Último Teorema de Fermat, por sua vez, gerou a teoria das curvas elípticas — que é hoje a base da criptografia de chave pública de curva elíptica (ECDSA), o protocolo de assinatura digital usado nas comunicações seguras entre o rover e a Terra. É uma curiosidade e tanto que a mesma família de objetos matemáticos — curvas elípticas — que Diofanto tocou sem saber no problema IV.24 seja, hoje, literalmente o que protege criptograficamente os comandos enviados a um rover em Marte.

---

*Fontes desta parte: Katz, § 6.2 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 26 de N — Diofanto de Alexandria (completa)
> **Próxima parte:** Papus de Alexandria e o Fim da Tradição Grega
