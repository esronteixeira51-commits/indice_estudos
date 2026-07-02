### 13.7 Os Livros VII, VIII e IX — Teoria dos Números

Há algo que salta aos olhos para quem lê os *Elementos* em sequência: o Livro VII começa **do zero**. Nenhuma referência aos seis livros anteriores, nenhum reaproveitamento das proposições sobre triângulos, círculos ou proporções de grandezas. Os três livros de teoria dos números — VII, VIII e IX — formam uma unidade completamente independente, e só nos livros finais, XI–XIII, geometria e número voltam a se encontrar.

Esse recomeço não é acidental. É a aplicação prática, no próprio texto de Euclides, exatamente da distinção que vimos com Aristóteles (§12.3): número é discreto, baseado na unidade indivisível; grandeza é contínua, infinitamente divisível. São categorias diferentes — e por isso Euclides recusa-se a simplesmente citar o Livro V quando uma proposição de teoria dos números é estruturalmente idêntica a uma proposição sobre grandezas. As Proposições VII.5–6, por exemplo, demonstram a distributividade $n(b+d) = nb+nd$ para números — com uma demonstração praticamente *idêntica*, palavra por palavra, à da Proposição V.1 sobre grandezas. Euclides claramente *sabia* que o argumento era o mesmo. Mas reescreveu-o inteiramente, porque para ele número não era um tipo de grandeza — era uma entidade de outra natureza.

**A impressão digital de Teeteto, de novo.** É praticamente certo que muitas proposições aritméticas remontam aos Pitagóricos. Mas a maneira como o Livro VII usa definições precisas e demonstrações detalhadas — e sobretudo o jeito como o Livro VII é reaproveitado no Livro X — sugere que a compilação rigorosa é obra do mesmo matemático responsável pelo Livro X: **Teeteto** (§11.5), uma vez mais. O padrão de Teeteto parece ter sido sempre o mesmo, em qualquer área que tocasse: pegar um corpo de conhecimento solto e impreciso dos Pitagóricos — números figurados, irracionais, agora teoria elementar dos números — e refundá-lo com definições e provas que resistem a escrutínio.

**Uma curiosidade que surpreende todo leitor moderno.** As definições que abrem o Livro VII guardam algo estranho aos nossos olhos:

> *Definição 1. Uma unidade é aquilo em virtude do qual cada uma das coisas existentes é chamada de uma.*
> *Definição 2. Um número é uma multiplicidade composta de unidades.*

Se "multiplicidade" significa pluralidade, e a unidade não é, por definição, uma pluralidade — então, para Euclides, como para os Pitagóricos antes dele, **o número 1 não é, estritamente, um número**. É o *átomo* a partir do qual os números (2, 3, 4, ...) são compostos, mas não pertence à categoria que ele próprio gera. É uma distinção que parece bizarra hoje — mas reflete com precisão a metáfora atomista que orienta toda a teoria grega dos números: assim como um átomo não é, ele mesmo, uma molécula, a unidade não é, ela mesma, uma "multiplicidade".

Vale notar também que a **multiplicação** (Definição 15: "um número multiplica outro quando o que é multiplicado é somado a si mesmo tantas vezes quantas unidades há no outro") é a *única* operação aritmética que Euclides realmente define em todo o Livro VII — soma e subtração são simplesmente assumidas como já conhecidas. E mesmo essa definição, baseada em soma repetida, tem uma consequência nada trivial: a comutatividade $ab = ba$ (Proposição VII.16) não é óbvia a partir dessa definição — é preciso demonstrá-la, e Euclides o faz.

**O algoritmo de Euclides.** As duas primeiras proposições do Livro VII (VII.1–2) tratam do método para encontrar o **máximo divisor comum** de dois inteiros — e o procedimento é a versão numérica exata da *antiphairesis* (subtração reciprocada) que já vimos Teeteto aplicar a grandezas geométricas, na tentativa pré-Eudoxiana de definir proporção (§11.5). Dados $a$ e $b$ com $a > b$, subtraia $b$ de $a$ repetidamente até obter um resto $r_1 < b$; subtraia $r_1$ de $b$ até obter $r_2 < r_1$; e assim por diante. O último resto não nulo é o $\text{mdc}(a,b)$.

Por exemplo, $\text{mdc}(252, 105)$:
$$252 = 2 \times 105 + 42$$
$$105 = 2 \times 42 + 21$$
$$42 = 2 \times 21 + 0$$

Logo $\text{mdc}(252, 105) = 21$.

É exatamente o mesmo processo que, aplicado a grandezas incomensuráveis em vez de números inteiros, *nunca termina* — e é precisamente esse "nunca terminar" que, para Teeteto, sinalizava a incomensurabilidade (lembre-se do exemplo da diagonal do pentágono, §11.5, onde a sequência de quocientes é $1,1,1,1,\ldots$ para sempre). Aqui, com números inteiros, o processo *sempre* termina — e é essa garantia de terminação que torna o algoritmo de Euclides computacionalmente útil. O algoritmo permanece, 2.300 anos depois, o método padrão para calcular o MDC, e é a base do algoritmo RSA de criptografia que protege as comunicações da internet.

**O princípio do menor número — e por que números não são grandezas.** As Proposições VII.31 e VII.32 (todo número composto é divisível por algum primo; todo número é primo ou divisível por algum primo) usam uma técnica que Euclides emprega com frequência nos livros aritméticos: o **princípio do menor número**. Se $a$ é composto, é medido por algum $b$; se $b$ não é primo, é medido por $c$, que também mede $a$; e assim por diante. Euclides argumenta: "se a investigação continuar assim, será encontrado algum número primo que medirá o número anterior a ele — pois, se não for encontrado, uma série infinita de números medirá o número $a$, cada um menor que o anterior; o que é impossível em números."

Repare na frase final: "impossível *em números*." Qualquer sequência decrescente de números inteiros positivos tem necessariamente um menor elemento — não se pode descer para sempre. Mas o mesmo **não vale** para grandezas: o método de exaustão de Eudoxo (§10.4) depende exatamente do oposto — de uma sequência de grandezas que pode ser tornada menor que *qualquer* limite prefixado, sem nunca atingir um "menor elemento" absoluto. É a distinção discreto/contínuo de Aristóteles, agora vista em ação como ferramenta de demonstração: o que é trivialmente verdadeiro para números (existência de um mínimo) seria simplesmente falso para grandezas geométricas.

**O Lema de Euclides e o Teorema Fundamental da Aritmética.** Combinando VII.31–32 com uma proposição adicional, Euclides está a um passo de um dos resultados mais importantes de toda a matemática:

> **Proposição VII.30 (hoje "Lema de Euclides").** *Se um número primo mede o produto de dois números, ele mede pelo menos um deles.*

A demonstração: se o primo $p$ divide $ab$ mas não divide $a$, então $ab = sp$ para algum $s$, logo $p:a = b:s$. Como $p$ e $a$ são primos entre si, são os menores números nessa razão (por VII.20) — logo $b$ deve ser um múltiplo de $p$.

Combinando este lema com a Proposição **IX.14** ("se um número é o menor dentre os medidos por certos primos, nenhum outro primo o mede"), obtém-se exatamente a **unicidade da fatoração em primos** — o que hoje chamamos de Teorema Fundamental da Aritmética. Euclides nunca enuncia esse teorema como uma afirmação única e explícita — ele está disperso, implícito na combinação de várias proposições. Mas toda a maquinaria lógica necessária está lá, dois mil anos antes de Gauss tornar o teorema explícito e central na teoria dos números moderna.

**A infinidade dos primos** (IX.20) é, ainda hoje, considerada a demonstração mais elegante dos *Elementos*:

> **Proposição IX.20.** *Existem mais números primos do que qualquer quantidade que se possa designar previamente.*

Euclides usa, como em outras demonstrações que já vimos, um **exemplo generalizável**: escolhe apenas três primos, $A$, $B$, $C$, e mostra que sempre se pode encontrar mais um. Considere $N = ABC + 1$. Se $N$ é primo, encontramos um primo novo. Se $N$ é composto, é divisível por algum primo $p$ — e $p$ não pode ser $A$, $B$ ou $C$, pois nenhum desses divide $N$ (a divisão sempre deixaria resto 1). Em qualquer caso, existe um primo fora da lista original — e Euclides presumivelmente confiava que o leitor veria que o mesmo argumento funciona para qualquer quantidade inicial de primos, não apenas três.

A demonstração é indireta, curta e completamente geral. Depois de mais de dois milênios, nenhuma demonstração fundamentalmente mais simples foi encontrada.

**O Livro VIII e a herança de Arquitas.** O Livro VIII trata de números em **proporção contínua** — sequências $a_1, a_2, \ldots, a_n$ tais que $a_1:a_2 = a_2:a_3 = \cdots$ (o que hoje chamamos de progressão geométrica). É hoje amplamente aceito que boa parte desse livro remonta a **Arquitas de Tarento** (§4.3) — o mesmo pitagórico que generalizou as proporções musicais para dez médias, e de quem Platão recebeu seu treinamento matemático.

O resultado original de Arquitas, generalizado por Euclides na Proposição VIII.8, é fascinante por sua conexão direta com a música: não existe média proporcional entre dois números cuja razão, em termos mínimos, seja $(n+1):n$. A razão entre duas cordas que produzem uma oitava é $2:1$ — composta de uma quinta ($3:2$) e uma quarta ($4:3$). O resultado de Arquitas mostra que a **oitava não pode ser dividida em dois intervalos musicais iguais**. E esse resultado é, matematicamente, *equivalente* à incomensurabilidade de $\sqrt{2}$ com $1$ — a mesma catástrofe que abalou os Pitagóricos (§4.8), agora revestida de roupagem numérica e musical. O mesmo argumento mostra, ainda, que um tom inteiro (razão $9:8$) também não pode ser dividido em dois intervalos iguais — um problema que voltaria a importar, séculos depois, para quem tentasse afinar instrumentos de teclado por temperamento igual.

As Proposições VIII.11–12 trazem um eco direto de um problema que já conhecemos bem: Euclides mostra que entre dois números quadrados existe exatamente uma média proporcional, e entre dois números cubos existem exatamente duas. É a versão puramente numérica — sem nenhuma régua, compasso ou cone à vista — da redução de Hipócrates da duplicação do cubo a encontrar duas médias proporcionais (§6.4). O mesmo problema geométrico que motivou Menaecmo a descobrir as cônicas (§11.6) reaparece aqui, despido de geometria, como um fato puro sobre números inteiros.

**A soma de uma progressão geométrica** aparece, em linguagem de proporção, na Proposição IX.35 — que é, essencialmente, a fórmula $S_n = \dfrac{a(r^n-1)}{r-1}$ que usamos hoje para somar progressões geométricas, embora Euclides a expresse como uma proporção entre diferenças, sem nunca escrever uma fórmula fechada.

**Números perfeitos** encerram os livros de teoria dos números (IX.36): se a soma $1 + 2 + 2^2 + \cdots + 2^n$ é um número primo, então o produto dessa soma por $2^n$ é um **número perfeito** — igual à soma de seus próprios divisores. Por exemplo, $1+2+4=7$ é primo, e $7 \times 4 = 28$ é perfeito: de fato, $28 = 1+2+4+7+14$. Os Pitagóricos conheciam apenas quatro números perfeitos — 6, 28, 496 e 8.128 — e é uma curiosidade notável que Euclides tenha escolhido encerrar a parte mais técnica dos *Elementos* com um teorema sobre uma classe de números da qual só se conheciam quatro exemplos. Euler demonstraria, no século XVIII, que *todo* número perfeito par tem exatamente essa forma. Se existem números perfeitos ímpares permanece, ainda hoje, um problema aberto — um dos mais antigos da matemática, com 2.300 anos de idade.

---

*Fontes desta parte: Katz, § 3.6 · Boyer, cap. 5 · Struik, cap. III*

---
> **Status:** Parte 13 de N — Euclides: Livros VII–IX (completa)
> **Próxima parte:** Livro X — A classificação dos irracionais
