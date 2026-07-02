## 20. Menelau, Herão e a Corrente Secundária

A matemática grega tardia — do século I ao III d.C. — apresenta uma divisão cada vez mais nítida entre dois mundos paralelos. De um lado, a geometria sintética clássica no estilo de Euclides e Arquimedes, que busca beleza e generalidade. Do outro, uma matemática prática, diretamente ligada à medição, construção e cálculo — mais próxima da tradição babilônica do que do ideal platônico.

**Menelau de Alexandria** representa o ápice da primeira tradição nesse período. **Herão de Alexandria** é o grande representante da segunda. Os dois viveram provavelmente na mesma cidade, aproximadamente no mesmo século, e produziram obras completamente diferentes em espírito — mas igualmente importantes para a história da matemática.

---

### 20.1 Menelau de Alexandria — Triângulos na Esfera

**Menelau de Alexandria** (c. 70–140 d.C.) escreveu um tratado sobre cordas em seis livros — hoje perdido — e uma obra chamada **Sphaerica** em três livros, que sobreviveu em tradução árabe. A *Sphaerica* estabelece a geometria dos triângulos esféricos de forma análoga ao que Euclides fez para os triângulos planos — e é o fundamento da trigonometria esférica que governou a astronomia e a navegação por quinze séculos.

**Por que a esfera importa:** A astronomia observacional mede ângulos entre estrelas e planetas tal como aparecem projetados na **esfera celeste** — uma esfera imaginária de raio infinito centrada na Terra. As posições são dadas por coordenadas angulares (ascensão reta e declinação, ou longitude e latitude eclíptica, §17.5). Calcular a distância angular entre dois astros, ou prever quando um planeta cruzará o meridiano local, são problemas de geometria na superfície de uma esfera — não no plano.

#### O Triângulo Esférico

Um **triângulo esférico** é formado por três arcos de círculos máximos (grandes círculos) sobre a superfície de uma esfera. Seus "lados" são arcos — medidos em graus, não em comprimento. Seus "ângulos" são os ângulos diedros entre os planos dos grandes círculos.

A geometria esférica difere profundamente da plana em vários aspectos:

**1. A soma dos ângulos internos é maior que $180°$:**

$$A + B + C = 180° + \frac{E}{\pi R^2} \cdot 180°$$

onde $E$ é a área do triângulo esférico e $R$ é o raio da esfera. O excesso $E / (\pi R^2) \cdot 180°$ — chamado **excesso esférico** — é proporcional à área. Um triângulo que ocupa $1/8$ da esfera tem $A + B + C = 270°$.

**Exemplo real:** O triângulo formado pelo Polo Norte, por um ponto no equador a $0°$ de longitude e por outro no equador a $90°$ de longitude tem três ângulos retos: $90° + 90° + 90° = 270°$. Verifique: esse triângulo ocupa $1/8$ da superfície esférica, e o excesso é $90°$. ✓

**2. Dois triângulos com os mesmos ângulos são congruentes** (não apenas semelhantes como no plano):

No plano, triângulos com os mesmos ângulos podem ter tamanhos arbitrariamente diferentes — são semelhantes. Na esfera, os ângulos determinam *completamente* o triângulo (inclusive seu tamanho), pois o tamanho angular dos lados está vinculado ao excesso esférico. Menelau demonstrou essa propriedade no Livro I da *Sphaerica* — ela não tem análogo euclidiano.

**3. Não existem triângulos semelhantes não congruentes na esfera:**

Uma consequência direta do ponto anterior. Em geometria esférica, a semelhança implica congruência — o que torna a trigonometria esférica fundamentalmente diferente da plana.

#### O Teorema de Menelau

O resultado mais famoso de Menelau é uma extensão do teorema de transversais para triângulos esféricos. Mas comecemos com o caso plano, que Menelau considerava conhecido:

**Caso plano:** Se uma reta transversal corta os lados $AB$, $BC$ e $CA$ (ou seus prolongamentos) de um triângulo nos pontos $D$, $E$ e $F$ respectivamente, então:

$$\frac{AD}{DB} \cdot \frac{BE}{EC} \cdot \frac{CF}{FA} = 1$$

(usando valores absolutos das razões; em versão com sinal, o produto é $-1$, refletindo que uma transversal genuína sempre corta um número ímpar dos três lados externamente.)

**Exemplo concreto:** Triângulo com $A = (0,0)$, $B = (4,0)$, $C = (0,3)$. A transversal passa pelos pontos $D = (2,0)$, sobre $AB$, e $F = (0,-3)$, sobre o prolongamento de $CA$ além de $A$.

A reta por $D$ e $F$ tem inclinação $\frac{0-(-3)}{2-0} = \frac{3}{2}$, e equação $y = \frac{3}{2}x - 3$. Substituindo na reta $BC$ (equação $3x+4y=12$), encontra-se a interseção $E = \left(\frac{8}{3}, 1\right)$.

Agora, as três razões:

$$\frac{AD}{DB} = \frac{2}{2} = 1$$

$$\frac{BE}{EC}: \text{ parametrizando } B \to C \text{, } E \text{ corresponde a } t=\tfrac{1}{3} \text{ do caminho, logo } \frac{BE}{EC} = \frac{1/3}{2/3} = \frac{1}{2}$$

$$\frac{CF}{FA} = \frac{6}{3} = 2 \quad (F \text{ está fora do segmento } CA\text{, a divisão é externa})$$

Produto: $1 \times \frac{1}{2} \times 2 = 1$. ✓

A demonstração de Menelau usa apenas semelhança de triângulos — é elementar e elegante.

**Caso esférico — o Teorema de Menelau esférico:**

Para um triângulo esférico $ABC$ e um grande círculo transversal que corta os lados (ou seus prolongamentos) em $D$, $E$, $F$:

$$\frac{\sin AD}{\sin DB} \cdot \frac{\sin BE}{\sin EC} \cdot \frac{\sin CF}{\sin FA} = 1$$

Os segmentos de reta são substituídos por **senos dos arcos** correspondentes — porque na esfera são os senos que entram nas relações de semelhança, não os comprimentos diretamente.

**Por que os senos:** Em geometria esférica, a relação análoga à semelhança de triângulos planos usa senos dos ângulos e dos lados (arcos). A **lei dos senos esférica** diz:

$$\frac{\sin a}{\sin A} = \frac{\sin b}{\sin B} = \frac{\sin c}{\sin C}$$

onde $a$, $b$, $c$ são os lados (em graus) e $A$, $B$, $C$ são os ângulos opostos. O teorema de Menelau esférico é uma consequência direta dessa lei aplicada a quatro triângulos.

#### Aplicação Astronômica

Menelau usou o teorema esférico para calcular a **declinação do Sol** em qualquer data — o ângulo entre o Sol e o equador celeste — a partir de outros ângulos medidos diretamente. O procedimento envolve montar um triângulo esférico na esfera celeste com os lados sendo arcos do equador, da eclíptica e do meridiano do lugar, e aplicar o teorema de Menelau para extrair o ângulo desejado.

Esse tipo de cálculo — transformar coordenadas de um sistema para outro na esfera celeste — é o pão diário da astronomia de posição, e é exatamente a ferramenta que **Ptolomeu** (§18.4) usaria, décadas depois, para resolver triângulos esféricos retângulos no Almagesto — construindo, segundo seu próprio relato, configurações de Menelau encaixadas para extrair cada elemento desconhecido passo a passo. O teorema de Menelau foi a principal ferramenta computacional para isso até que a trigonometria esférica moderna (introduzida pelos árabes no século IX) forneceu fórmulas mais diretas.

---

### 20.2 Herão de Alexandria — A Matemática do Praticante

**Herão de Alexandria** (c. 10–75 d.C.) é o mais importante representante de uma tradição que os filósofos gregos tentavam ignorar: a matemática como ferramenta de trabalho. Arquiteto, engenheiro e professor, Herão escreveu manuais práticos que traduziam a geometria abstrata dos *Elementos* em procedimentos concretos para medir terras, construir máquinas e resolver problemas comerciais.

Suas obras incluem *Métrica* (mensuração de áreas e volumes), *Geométrica* (problemas de medição), *Estereométrica* (volumes), *Pneumática* (máquinas a vapor e pneumáticas), *Mecânica* (máquinas simples) e *Dióptrica* (instrumentos de medição angular, onde Herão resolve problemas de triangulação à distância usando — como Ptolomeu faria depois — uma tabela de cordas própria). A maior parte sobreviveu — algumas originalmente perdidas e redescobertas em manuscritos de Constantinopla no século XIX.

O estilo de Herão é completamente diferente de Euclides: **sem demonstrações formais na maioria dos casos**, **com exemplos numéricos específicos**, **com receitas passo a passo**. É o manual do técnico, não o tratado do filósofo — embora, como veremos, Herão soubesse demonstrar quando o problema exigia.

#### A Fórmula de Herão — e Por Que Ela é "Ageométrica"

A contribuição mais famosa de Herão é a fórmula para a área de um triângulo em termos de seus três lados:

$$A = \sqrt{s(s-a)(s-b)(s-c)}$$

onde $s = (a+b+c)/2$ é o semiperímetro. Os árabes registram que Arquimedes já conhecia essa fórmula — mas a demonstração mais antiga que temos é a de Herão, na *Métrica*, que de fato apresenta uma prova geométrica completa e correta.

**Um detalhe que vale a pena destacar — e que se conecta diretamente a algo que vimos com Aristóteles (§12.3).** Dentro do sistema de Euclides, o produto de dois comprimentos é uma área (um retângulo); o produto de três comprimentos é um volume (um paralelepípedo). Mas o que é o produto de **quatro** comprimentos — $s(s-a)(s-b)(s-c)$? Não existe um objeto geométrico de quatro dimensões no universo de Euclides. É precisamente o tipo de operação que a distinção aristotélica entre número (que pode ser multiplicado indefinidamente) e grandeza (limitada à dimensão 3 do espaço físico) deveria proibir.

Herão não comenta essa estranheza — provavelmente porque já estava presente em sua fonte (possivelmente o próprio Arquimedes), e porque sua preocupação era prática, não filosófica: a fórmula funciona, produz o número certo, e isso basta. Mas o fato de que ela aparece sem alarde é, em si, revelador: mostra que, por baixo da "fachada geométrica" oficial da matemática grega — a que vimos em Euclides, Apolônio e Arquimedes, sempre cuidadosos em nunca multiplicar mais do que três grandezas — havia uma tradição computacional paralela, menos rigorosa quanto aos fundamentos, disposta a tratar comprimentos como números puros e multiplicá-los livremente. Essa tradição "ageométrica" é exatamente a corrente secundária que dá nome a esta seção.

**Derivação elementar (não a de Herão, mas equivalente, usando a lei dos cossenos):**

Da lei dos cossenos, $\cos C = (a^2 + b^2 - c^2)/(2ab)$. A área é $A = \frac{1}{2}ab\sin C$.

$$A^2 = \frac{a^2 b^2 \sin^2 C}{4} = \frac{a^2 b^2 (1-\cos^2 C)}{4}$$

$$= \frac{a^2 b^2}{4} \cdot \left[1 - \left(\frac{a^2+b^2-c^2}{2ab}\right)^2\right] = \frac{(2ab)^2 - (a^2+b^2-c^2)^2}{16}$$

$$= \frac{[2ab + (a^2+b^2-c^2)][2ab - (a^2+b^2-c^2)]}{16} = \frac{[(a+b)^2 - c^2][c^2 - (a-b)^2]}{16}$$

$$= \frac{(a+b+c)(a+b-c)(c+a-b)(c-a+b)}{16} = s(s-a)(s-b)(s-c)$$

Logo $A = \sqrt{s(s-a)(s-b)(s-c)}$. ∎

**Exemplo numérico:** Triângulo com lados $a=13$, $b=14$, $c=15$.

$s = (13+14+15)/2 = 21$.

$A = \sqrt{21 \cdot 8 \cdot 7 \cdot 6} = \sqrt{7056} = 84$.

Verificação: a altura sobre o lado $b=14$ é $h = 2A/b = 168/14 = 12$. O triângulo é formado por dois triângulos retângulos de lados $5$, $12$, $13$ e $9$, $12$, $15$ — o que confirma $h=12$ e a área $=\frac{1}{2} \cdot 14 \cdot 12 = 84$. ✓

**Aplicação real:** A fórmula de Herão é usada em cartografia para calcular áreas de polígonos irregulares divididos em triângulos — exatamente o que os sistemas de mapeamento do rover fazem ao estimar a área de regiões de interesse no terreno marciano.

#### O Algoritmo de Herão para Raízes Quadradas

O mesmo texto que apresenta a fórmula da área traz, na sequência, a necessidade prática de calcular $\sqrt{720}$ — e é nesse contexto que Herão descreve seu método para raízes quadradas, que é, na realidade, o algoritmo babilônico de dois mil anos antes (§Período 1 deste projeto) — mas que ficou associado ao seu nome no Ocidente.

**O exemplo original de Herão, em suas próprias palavras (paraphraseado):** Como $720$ não é um quadrado perfeito, comece pelo quadrado mais próximo: $729 = 27^2$. Divida $720$ por $27$: obtém-se $26\frac{2}{3}$. Some isso a $27$: $53\frac{2}{3}$. Tome a metade: $26\frac{5}{6}$. Esse é o valor aproximado de $\sqrt{720}$ — e, de fato, $\left(26\frac{5}{6}\right)^2 = 720\frac{1}{36}$, errando por apenas $1/36$. Se for necessária mais precisão, repita o processo usando $26\frac{5}{6}$ como novo ponto de partida.

Generalizando esse procedimento específico, obtemos a fórmula iterativa:

$$x_{n+1} = \frac{1}{2}\left(x_n + \frac{N}{x_n}\right)$$

O processo converge quadraticamente: a cada iteração, o número de casas decimais corretas aproximadamente dobra.

**Exemplo com $\sqrt{2}$, começando com $x_0 = 1$:**

$$x_1 = \frac{1}{2}\left(1 + \frac{2}{1}\right) = 1{,}5$$

$$x_2 = \frac{1}{2}\left(1{,}5 + \frac{2}{1{,}5}\right) = \frac{1}{2}(1{,}5 + 1{,}333) = 1{,}4167$$

$$x_3 = \frac{1}{2}\left(1{,}4167 + \frac{2}{1{,}4167}\right) = \frac{1}{2}(1{,}4167 + 1{,}4118) = 1{,}41422\ldots$$

O valor correto é $\sqrt{2} = 1{,}41421356\ldots$ — após três iterações, teríamos 5 casas corretas.

**Por que converge:** O algoritmo é o método de Newton-Raphson aplicado à função $f(x) = x^2 - N$. A iteração $x \mapsto x - f(x)/f'(x) = x - (x^2-N)/(2x) = (x + N/x)/2$ é exatamente a fórmula de Herão. Newton "descobriu" o método geral em 1669 — mas o caso específico da raiz quadrada é mesopotâmico, com a versão de Herão sendo o elo de transmissão para o mundo grego e árabe. Curiosamente, o algoritmo de Ptolomeu para suas próprias raízes quadradas (usado na construção da tabela de cordas, §18.3) era ligeiramente diferente do de Herão — talvez um refletindo cálculo em base dez e o outro em base sexagesimal, talvez ambos derivados independentemente da mesma fonte babilônica.

**Aplicação real:** O algoritmo de Herão é implementado em hardware de ponto flutuante para calcular raízes quadradas em um único ciclo de clock. A instrução `FSQRT` dos processadores x86 modernos usa uma variante refinada desse método. O processador que controla o computador de bordo do rover usa esse algoritmo dezenas de milhares de vezes por segundo.

#### Áreas de Polígonos Regulares — Uma Pequena Concessão à Teoria

A *Métrica* também contém fórmulas para a área de polígonos regulares de 3 a 12 lados em termos do comprimento do lado $a$: por exemplo, $A_3 \approx \frac{13}{30}a^2$ para o triângulo equilátero e $A_5 \approx \frac{5}{3}a^2$ para o pentágono. Cada fórmula vem de aproximar as raízes quadradas que aparecem na derivação geométrica.

Há uma ironia simpática nisso: para derivar a fórmula do **eneágono regular** (9 lados), Herão precisou recorrer a uma **tabela de cordas** — exatamente o instrumento da tradição "teórica" de Hiparco e Ptolomeu (§17.6, §18.3). O engenheiro prático, sempre que o problema concreto exigia, não hesitava em tomar de empréstimo a ferramenta mais sofisticada da tradição rival. A separação entre "teoria" e "prática" que estamos descrevendo nesta seção é real e útil como categoria histórica — mas nunca foi uma muralha impermeável.

#### O Princípio da Mínima Distância — A Física da Reflexão

Em sua *Catóptrica* (óptica de espelhos), Herão demonstrou que a **lei da reflexão** — ângulo de incidência igual ao ângulo de reflexão — é uma consequência de um princípio físico mais fundamental: **a luz percorre o caminho mais curto possível**. Aqui, ao contrário da fórmula da área, Herão oferece uma demonstração completa e rigorosa, no melhor estilo euclidiano.

**A demonstração de Herão:**

Seja $S$ a fonte de luz, $M$ o espelho (uma reta), e $E$ o olho do observador. O raio de luz vai de $S$ a um ponto $P$ no espelho e daí a $E$. Dentre todos os pontos $P$ possíveis no espelho, qual minimiza o comprimento total $SP + PE$?

Construa $S'$, a reflexão de $S$ no espelho (ponto simétrico em relação à reta $M$). Então $SP = S'P$ para qualquer $P$ no espelho. Portanto:

$$SP + PE = S'P + PE \geq S'E$$

com igualdade quando $P$ está sobre o segmento $S'E$ — ou seja, quando $S$, $P$ e $E$ satisfazem a lei da reflexão (os ângulos são iguais porque $S'$, $P$, $E$ são colineares e $S'$ é o simétrico de $S$).

**O ponto filosófico:** Herão não apenas descreveu como a luz se comporta — explicou *por que* ela se comporta assim. A natureza "prefere" o caminho mais curto. Esse princípio — hoje chamado **Princípio de Fermat** (1662) — é o fundamento da óptica geométrica e tem a forma geral:

> *A luz percorre o caminho que minimiza (ou extremiza) o tempo de percurso.*

Fermat o generalizou para a refração 1.600 anos depois de Herão. Leibniz e Euler formalizaram o princípio variacional. E no século XX, Feynman mostrou que o princípio de mínima ação — a versão quântica do princípio de Herão — é o fundamento de toda a mecânica quântica e eletrodinâmica quântica.

Herão, o engenheiro prático, havia formulado um dos princípios mais profundos da física.

#### A Máquina a Vapor de Herão

Herão descreveu na *Pneumática* um dispositivo que ele chamava de **aeolípila** — uma esfera com bicos tangenciais que girava pelo vapor d'água expelido por uma caldeira abaixo. É funcionalmente uma turbina a vapor primitiva.

A aeolípila nunca foi usada para trabalho mecânico na Antiguidade. O trabalho escravo era barato; não havia incentivo econômico para desenvolver a máquina. E sem a ciência da termodinâmica (que só viria no século XIX), não havia como entender a eficiência ou escalar o dispositivo.

Mas o princípio estava lá: calor convertido em movimento rotativo. A Revolução Industrial, 1.700 anos depois, seria construída sobre esse princípio.

#### Herão e a Matemática Babilônica

O estilo de Herão — exemplos numéricos específicos, receitas muitas vezes sem demonstração, resultados aproximados — é tão semelhante ao dos tabletes babilônicos que historiadores suspeitam de uma linha direta de transmissão. O Egito helenístico estava em contato contínuo com a Mesopotâmia; é provável que a tradição de problemas práticos nunca tenha sido interrompida, apenas ocultada pela preferência dos filósofos pela matemática abstrata.

Um exemplo típico de Herão, da *Geométrica*: "Dado que a soma do diâmetro, da circunferência e da área de um círculo é $212$, encontre o diâmetro." O procedimento é: multiplique $212$ por $154$, adicione $841$, extraia a raiz quadrada, subtraia $29$, divida por $11$. Resposta: $14$.

Verifique: diâmetro $= 14$, circunferência $\approx 44$, área $\approx 154$. Soma $= 14 + 44 + 154 = 212$. ✓

O problema mistura dimensões (comprimento e área) — algo que Euclides jamais permitiria, e exatamente o mesmo tipo de licença "ageométrica" que já notamos na fórmula da área do triângulo. Herão não se importava: o problema funcionava numericamente, e isso era suficiente para o propósito prático.

---

### 20.3 O Contraste — Dois Mundos na Mesma Cidade

Herão e Menelau provavelmente trabalharam em Alexandria na mesma época. A diferença entre suas obras ilustra a divisão fundamental da matemática grega:

| | Menelau | Herão |
|---|---|---|
| Estilo | Demonstrações formais | Receitas numéricas (mas não só) |
| Objetivo | Entender por quê | Calcular o quê |
| Público | Filósofos e astrônomos | Engenheiros e comerciantes |
| Tradição | Euclides, Arquimedes | Babilônia, Egito prático |
| Impacto imediato | Pequeno | Grande |
| Impacto de longo prazo | Imenso (via trigonometria esférica árabe) | Imenso (via algoritmos numéricos) |

Essa divisão — entre matemática teórica e matemática computacional — nunca foi resolvida na Antiguidade. Os gregos escolheram valorizar a primeira e tolerar a segunda. Os árabes e os indianos, que herdaram ambas as tradições, as fundiram mais organicamente. A síntese completa só ocorreu com o cálculo do século XVII — quando Newton e Leibniz criaram uma matemática que era ao mesmo tempo rigorosamente demonstrável (como Euclides) e poderosa em computação (como Herão).

> **Conexão com o projeto:** O contraste Menelau/Herão é o contraste entre o **modelo matemático** e o **algoritmo de implementação** — uma distinção central em qualquer sistema embarcado. O teorema de Menelau fornece a geometria correta para transformar coordenadas na esfera celeste (necessário para navegação estelar do rover). O algoritmo de Herão implementa essa geometria em aritmética de ponto fixo eficiente para o processador de bordo. Ambos são necessários: o teorema sem o algoritmo é impraticável; o algoritmo sem o teorema é um procedimento cego que pode divergir ou produzir resultados incorretos. A engenharia moderna de sistemas de controle exige os dois — e a origem de cada um está, respectivamente, em Menelau e Herão.

---

*Fontes desta parte: Katz, §§ 5.3.1–5.3.2 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 25 de N — Menelau e Herão (completa)
> **Próxima parte:** Diofanto de Alexandria — A Álgebra que os Gregos Esqueceram
