## 10. Eudoxo de Cnido — A Solução que Salvou a Matemática

**Eudoxo de Cnido** (c. 408–355 a.C.) é provavelmente o maior matemático do período clássico — e um dos menos conhecidos pelo público geral. Foi discípulo de Platão, fundou sua própria escola em Cízico, e retornou a Atenas como matemático e astrônomo reconhecido. Arquimedes, o maior matemático da Antiguidade, atribuía a ele as demonstrações dos teoremas fundamentais sobre volumes de cones, pirâmides e esferas. Suas obras se perderam completamente — conhecemos suas contribuições apenas pelas referências de Euclides, Arquimedes e Proclo.

Eudoxo resolveu *duas* crises simultâneas que ameaçavam os fundamentos da matemática grega: a crise das proporções (causada pelos irracionais) e a crise do infinito (causada pelos paradoxos de Zenão). Fez isso com duas criações que permanecem, em essência, na matemática moderna: a **teoria das proporções** e o **método de exaustão**.

---

### 10.1 A Crise das Proporções

Recorde o problema. Os pitagóricos definiam a proporção $a:b = c:d$ usando a ideia de que duas grandezas são sempre comensuráveis — isto é, existe sempre uma unidade $u$ tal que $a = mu$ e $b = nu$ para inteiros $m$ e $n$. Nesse caso, $a:b = m:n$, uma razão entre inteiros.

Mas a descoberta dos irracionais destruiu essa base: a diagonal e o lado de um quadrado são incomensuráveis — não existe unidade comum. Como então comparar razões envolvendo grandezas incomensuráveis? O teorema de Hipócrates sobre áreas de círculos ($A_1 : A_2 = d_1^2 : d_2^2$) usava proporções — mas sua demonstração era suspeita, pois $d_1$ e $d_2$ podem ser incomensuráveis.

Toda a estrutura de proporções que os gregos usavam para comparar figuras geométricas estava comprometida.

---

### 10.2 A Definição de Eudoxo

A solução de Eudoxo está na **Definição 5 do Livro V** dos *Elementos* de Euclides — considerada por muitos matemáticos a definição mais sofisticada da matemática antiga:

> *Diz-se que grandezas estão na mesma razão, a primeira para a segunda e a terceira para a quarta, se — tomados quaisquer equimúltiplos da primeira e da terceira e quaisquer equimúltiplos da segunda e da quarta — os primeiros equimúltiplos são ambos maiores que, ambos iguais a, ou ambos menores que os últimos, considerados em ordem correspondente.*

Em linguagem moderna: $a:b = c:d$ se e somente se, para quaisquer inteiros positivos $m$ e $n$:

$$ma \gtrless nb \iff mc \gtrless nd$$

Isto é: se $ma > nb$, então $mc > nd$; se $ma = nb$, então $mc = nd$; se $ma < nb$, então $mc < nd$.

**Por que isso funciona sem assumir comensurabilidade?**

A definição não diz nada sobre a existência de uma unidade comum. Ela apenas diz que as duas razões *se comportam da mesma forma* diante de qualquer múltiplo inteiro. Isso é verificável mesmo para grandezas incomensuráveis — basta testar todos os pares de inteiros $m$ e $n$.

**Exemplo concreto:** Queremos verificar que $1:\sqrt{2} = \sqrt{2}:2$ (ou seja, que $\sqrt{2}$ é a média geométrica de 1 e 2).

Para quaisquer $m$, $n$ inteiros, a condição é: $m \cdot 1 \gtrless n \cdot \sqrt{2}$ se e somente se $m \cdot \sqrt{2} \gtrless n \cdot 2$.

Dividindo tudo por $\sqrt{2}$: a primeira condição equivale a $m/\sqrt{2} \gtrless n$, e a segunda a $m \gtrless n\sqrt{2}$, que é a mesma coisa. ✓

A definição funciona — sem nunca mencionar que $\sqrt{2}$ é irracional, sem precisar de uma unidade comum, sem invocar frações.

**A conexão com os números reais modernos:** A definição de Eudoxo é estruturalmente idêntica às *cortaduras de Dedekind* (1872). Dedekind definiu um número real como uma partição dos racionais em duas classes: os menores que o número e os maiores. Eudoxo faz o mesmo para grandezas geométricas: a razão $a:b$ é caracterizada pela forma como ela se compara com todas as razões racionais $m:n$. A diferença é apenas de vocabulário — Eudoxo trabalhava com grandezas geométricas, Dedekind com números abstratos.

---

### 10.3 O Axioma de Eudoxo (ou de Arquimedes)

Antes da definição de proporção, Eudoxo estabeleceu um axioma que Arquimedes mais tarde tornaria famoso com seu próprio nome:

> *Diz-se que grandezas têm uma razão entre si quando, multiplicadas, podem superar uma à outra.*

Em outras palavras: para quaisquer grandezas positivas $a$ e $b$, existe um inteiro $n$ tal que $na > b$.

**O que esse axioma exclui:** grandezas infinitesimais fixas. Se existisse uma grandeza $\varepsilon$ tão pequena que nenhum múltiplo inteiro dela superasse $b$, o axioma falharia. O axioma garante que o infinitesimal fixo não existe na geometria grega — e essa garantia é o que torna o método de exaustão possível.

**Exemplo:** O axioma garante que, dado um segmento minúsculo $\varepsilon$ e uma circunferência $C$, existe sempre um inteiro $n$ tal que $n\varepsilon > C$. Não importa quão pequeno seja $\varepsilon$ — ele não é infinitesimalmente fixo. Isso elimina o "ângulo de contingência" (o ângulo entre uma tangente e a curva num ponto), que parecia ser uma grandeza menor que qualquer ângulo retilíneo positivo mas maior que zero.

---

### 10.4 O Método de Exaustão

Com o axioma estabelecido, Eudoxo construiu a ferramenta que os gregos usariam por séculos para calcular áreas e volumes de figuras curvilíneas: o **método de exaustão**.

O princípio é o seguinte. Para calcular a área de uma figura curvilínea $F$, inscreve-se nela uma sequência de polígonos $P_1, P_2, P_3, \ldots$ com número crescente de lados, tal que a diferença entre a área de $F$ e a área de $P_n$ pode ser tornada menor que qualquer grandeza prefixada $\varepsilon > 0$. Do axioma de Eudoxo, segue a proposição:

> *Se de uma grandeza subtrairmos não menos que a metade, e do resto novamente não menos que a metade, e assim continuarmos, eventualmente obteremos uma grandeza menor que qualquer grandeza prefixada da mesma espécie.*

**Exemplo real — área do círculo:**

O caso mais célebre — e o exemplo que Euclides registraria formalmente como a **Proposição XII-2** dos *Elementos*, dois mil e trezentos anos antes de chegar até nós — é demonstrar que a área $A$ de um círculo de diâmetro $d$ satisfaz $A/A' = d^2/d'^2$ para dois círculos quaisquer.

Inscreva no círculo menor um polígono regular de $n$ lados com área $p_n$, e no maior um polígono semelhante com área $P_n$. É demonstrável que $p_n/P_n = d^2/d'^2$ (polígonos semelhantes têm áreas na razão dos quadrados dos lados correspondentes) — esse fato auxiliar é, ele mesmo, a Proposição XII-1, generalização direta de um resultado anterior de Eudoxo sobre polígonos semelhantes em geral (VI-20).

Agora, suponha por contradição que $A/A' > d^2/d'^2$. Então existe $A'' < A$ tal que $A''/A' = d^2/d'^2$. Pelo método de exaustão, podemos inscrever um polígono $p_n$ com $p_n > A''$. Mas então $p_n/P_n = d^2/d'^2 = A''/A'$, logo $P_n > A'$ — absurdo, pois $P_n$ é inscrito em $A'$.

Simetria: suponha $A/A' < d^2/d'^2$ e derive outra contradição. Logo $A/A' = d^2/d'^2$. ∎

**O que é elegante:** a demonstração nunca diz "a área do polígono converge para a área do círculo". Ela apenas diz que, se as áreas não são proporcionais, chegamos a um absurdo. O infinito não aparece explicitamente — ele está escondido no "podemos inscrever um polígono tão próximo quanto queiramos".

**Um limite importante do método — e uma ponte para Arquimedes.** Vale destacar algo que o próprio Katz observa com precisão: o método de exaustão *prova* que uma fórmula é correta — mas não oferece nenhuma pista de *como descobrir* essa fórmula em primeiro lugar. Eudoxo demonstrou rigorosamente que o volume da pirâmide é $\frac{1}{3}Bh$ (Proposição XII-7 dos *Elementos*) e que o do cone é $\frac{1}{3}$ do cilindro correspondente (Proposição XII-10) — mas esses resultados já eram conhecidos, suspeitados ou intuídos havia muito tempo: pelos egípcios (que sabiam a fórmula sem prová-la), e por **Demócrito** (§8), que provavelmente chegou a ela por um argumento de fatias indivisíveis. Eudoxo entra exatamente onde Demócrito tinha de parar: ele tinha a fórmula correta, mas não a justificativa que resistisse à pergunta "por quê?". A exaustão de Eudoxo é a *verificação* rigorosa de uma conjectura — não a *ferramenta de descoberta*. Essa distinção entre descobrir e demonstrar voltará, de forma ainda mais explícita, quando estudarmos *O Método* de Arquimedes (§14): um tratado em que o maior matemático da Antiguidade revela, deliberadamente, como usava um raciocínio mecânico não rigoroso para *descobrir* resultados — e só depois os vestia com o rigor de exaustão para publicá-los.

---

### 10.5 As Esferas Homocêntricas

Eudoxo era também o maior astrônomo de sua época, e sua contribuição à astronomia é inseparável de sua matemática.

Platão propusera o programa: representar os movimentos dos planetas por **combinações de movimentos circulares uniformes**. Eudoxo respondeu com o sistema de **esferas homocêntricas** (todas centradas na Terra):

- Para o Sol e a Lua: 3 esferas cada.
- Para cada um dos cinco planetas: 4 esferas cada.
- Para as estrelas fixas: 1 esfera.

Total: $3 + 3 + 5 \times 4 + 1 = 27$ esferas.

Cada esfera gira uniformemente em torno de um eixo fixo na superfície da esfera maior que a contém. Compondo as rotações, Eudoxo conseguia reproduzir o movimento observado dos planetas — inclusive o movimento retrógrado (quando os planetas parecem mover-se para trás no céu).

A curva gerada pela composição das rotações das quatro esferas de um planeta é chamada **hippopede** (grilhão de cavalo) — uma curva em forma de oito traçada sobre a esfera. É uma das poucas curvas novas reconhecidas pelos gregos antes de Apolônio, e é obtida tanto cinematicamente (por composição de rotações) quanto estereometricamente (como interseção de uma esfera com um cilindro tangente internamente).

O sistema de Eudoxo era matematicamente elegante mas astronomicamente imperfeito — não reproduzia as variações de velocidade e brilho dos planetas. Mas sua estrutura influenciou dois mil anos de cosmologia, de Aristóteles a Copérnico.

---

### 10.6 Por Que Eudoxo Importa

A teoria das proporções de Eudoxo resolve um problema que a matemática moderna trata com números reais. Os números reais foram rigorosamente definidos apenas em 1872 — por Dedekind (cortaduras) e Cantor (sequências de Cauchy). Durante os 2.200 anos entre Eudoxo e Dedekind, a teoria das proporções de Eudoxo era a única fundação rigorosa para comparar grandezas incomensuráveis.

Newton usou proporções no estilo de Eudoxo nos *Principia* (1687) porque a álgebra de seu tempo ainda não tinha uma teoria rigorosa dos números reais. Quando Newton escrevia que "a força é proporcional à aceleração", estava usando a linguagem e o rigor de Eudoxo.

O método de exaustão de Eudoxo, por sua vez, é o cálculo integral *sem* o conceito de limite. É mais trabalhoso — cada teorema exige uma dupla *reductio* — mas é rigorosamente correto dentro dos axiomas aceitos. Arquimedes o usaria para descobrir áreas e volumes que só seriam recalculados com o cálculo moderno dois mil anos depois — embora, como vimos, "descobrir" não seja a palavra exata: Arquimedes descobria por outros meios, e *demonstrava* com a exaustão de Eudoxo.

> **Conexão com o projeto:** O axioma de Eudoxo — que nenhuma grandeza é infinitesimalmente pequena em relação a outra — é o fundamento matemático da **precisão numérica finita**. Em computação de ponto flutuante, toda grandeza tem uma representação com número finito de bits: não existe infinitesimal abaixo da resolução da máquina. Isso é exatamente o axioma de Eudoxo implementado em hardware. O método de exaustão, por sua vez, é o princípio dos algoritmos iterativos de controle do rover: cada iteração reduz o erro por um fator constante, e após $n$ passos o erro é menor que qualquer tolerância prefixada — precisamente a "propriedade de exaustão" de Euclides X.1. E a distinção entre descoberta e demonstração tem um paralelo direto em engenharia de software: um protótipo heurístico que "funciona na prática" (a descoberta) ainda precisa, depois, de testes formais e provas de corretude (a demonstração) antes de ir para um sistema crítico como o rover.

---

*Fontes desta parte: Boyer, cap. 4 · Katz, § 3.8 (Livro XII de Euclides) · Struik, cap. III*

---
> **Status:** Parte 7 de N — Eudoxo de Cnido (completa)
> **Próxima parte:** A Academia de Platão — sólidos regulares, Teeteto, Menaecmo e as cônicas, e a Seção A (Aristóteles)
