## 9. Zenão de Eleia — Os Paradoxos do Infinito

**Zenão de Eleia** (c. 490–430 a.C.) era discípulo de Parmênides, o filósofo que ensinava que o movimento e a multiplicidade são ilusões — que o Ser é uno, eterno e imóvel. Zenão não tentou provar essa doutrina diretamente. Fez algo mais habilidoso: tomou as premissas dos adversários — os pitagóricos, que acreditavam que espaço e tempo são compostos de pontos e instantes — e mostrou que elas levam a contradições.

Seu método era dialético: *reductio ad absurdum*. Assuma o que seu oponente acredita. Derive uma contradição. Logo a crença é falsa.

Aristóteles nos preservou quatro paradoxos de Zenão. São os mais influentes da história da filosofia — e também os mais matematicamente fecundos, pois forçaram os gregos a pensar com rigor sobre infinito, continuidade e limite.

### 9.1 A Dicotomia

*"Antes que um objeto possa percorrer uma distância qualquer, precisa percorrer a primeira metade. Mas antes de percorrer a primeira metade, precisa percorrer o primeiro quarto. E antes disso, o primeiro oitavo. E assim por diante, sem fim. Logo, o movimento nunca pode começar."*

Em termos modernos: para percorrer a distância 1, é preciso completar a sequência infinita de tarefas

$$\frac{1}{2},\quad \frac{1}{4},\quad \frac{1}{8},\quad \frac{1}{16},\quad \ldots$$

Cada tarefa exige tempo finito. Uma infinidade de tarefas exige tempo infinito. Logo o movimento é impossível.

O erro — que os gregos não tinham linguagem para articular — está em assumir que a *soma* de infinitos termos positivos é necessariamente infinita. Não é. A série geométrica

$$\sum_{n=1}^{\infty} \frac{1}{2^n} = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \cdots = 1$$

converge para 1. Uma infinidade de intervalos de tempo cada vez menores pode somar um tempo finito. Mas demonstrar isso rigorosamente exige o conceito de limite — que os gregos não possuíam.

É interessante notar como Aristóteles, ao tentar refutar Zenão, chegou perto da resposta moderna sem completá-la: ele concedia que o tempo, como o espaço, é infinitamente divisível — mas argumentava que isso não é um problema, porque um corpo em tempo finito não entra em contato com uma infinidade de coisas *quantitativamente*, apenas com uma infinidade de coisas no sentido da *divisibilidade*, "pois nesse sentido o próprio tempo também é infinito". É uma intuição correta vestida em linguagem que ainda não tinha o conceito formal de série convergente para se expressar com precisão.

### 9.2 O Aquiles e a Tartaruga

*"Aquiles aposta corrida com uma tartaruga e lhe dá vantagem. Quando Aquiles chega ao ponto de partida da tartaruga, ela já avançou um pouco. Quando Aquiles cobre essa distância, ela avançou mais um pouco. O processo se repete indefinidamente. Aquiles nunca alcança a tartaruga."*

É a Dicotomia em versão progressiva em vez de regressiva. Se Aquiles corre 10 vezes mais rápido que a tartaruga, e a tartaruga parte com 100 m de vantagem, a sequência de posições onde Aquiles chega e a tartaruga já avançou é:

$$100,\quad 10,\quad 1,\quad 0{,}1,\quad 0{,}01,\quad \ldots$$

A soma dessas distâncias extras é $100 + 10 + 1 + 0{,}1 + \cdots = 111{,}1\overline{1} = \frac{1000}{9}$ metros — finita. Aquiles alcança a tartaruga em $\frac{1000}{9}$ metros a partir do seu ponto de partida. Mas para provar isso, é preciso somar uma série geométrica infinita — e aceitar que séries infinitas podem ter somas finitas.

O paradoxo é pedagogicamente poderoso porque nossa intuição falha precisamente aqui: *infinitos passos* parecem exigir *tempo infinito*. Zenão explorou esse conflito entre intuição e lógica com maestria.

### 9.3 A Flecha

*"Uma flecha em voo sempre ocupa um espaço igual a si mesma. Mas o que ocupa um espaço igual a si mesmo está em repouso. Logo, a flecha em voo está sempre em repouso. O movimento é uma ilusão."*

Este paradoxo é estruturalmente diferente dos dois anteriores. A Dicotomia e o Aquiles argumentam contra a **subdivisibilidade infinita** do espaço e do tempo. A Flecha argumenta contra a hipótese *oposta*: que o tempo é composto de **instantes indivisíveis**.

Se o tempo é feito de instantes atômicos, então em cada instante a flecha ocupa uma posição definida e não se move — pois movimento exige dois instantes diferentes. Somando uma infinidade de "repousos instantâneos", obtemos... repouso. O movimento é ilusório.

O erro moderno é claro: velocidade não é uma propriedade de um instante isolado — é o *limite* da razão $\Delta x / \Delta t$ quando $\Delta t \to 0$. A noção de derivada resolve o paradoxo. Mas a derivada foi inventada por Newton e Leibniz em 1666–1675. Zenão formulou o problema em 450 a.C.

### 9.4 O Estádio

*"Sejam três fileiras de corpos de igual tamanho: $A_1 A_2 A_3 A_4$ estacionários, $B_1 B_2 B_3 B_4$ movendo-se para a direita, $C_1 C_2 C_3 C_4$ movendo-se para a esquerda, ambos com a mesma velocidade relativa aos $A$. Em um instante mínimo, cada $B$ passa por um $A$, e cada $C$ passa por um $A$. Mas nesse mesmo instante, cada $B$ passou por dois $C$ — logo, o instante mínimo pode ser subdividido. Contradição."*

Numa configuração inicial:

```
A:  A1  A2  A3  A4
B:      B1  B2  B3  B4
C:  C4  C3  C2  C1
```

Após um instante:

```
A:  A1  A2  A3  A4
B:          B1  B2  B3  B4
C:      C4  C3  C2  C1
```

$B_1$ passou por $A_2$ (um $A$) e por $C_2$ e $C_1$ (dois $C$). Se o instante era mínimo e indivisível, como $B_1$ pode ter passado por duas coisas diferentes?

O paradoxo expõe a inconsistência de supor que existe um "menor intervalo de tempo possível" enquanto se permite que corpos se movam com velocidades diferentes. Zenão concebe os corpos como elementos indivisíveis de espaço, deslocando-se numa unidade indivisível de tempo — e mostra que, ainda assim, deve ter existido um momento em que $B_1$ estava exatamente sobre $C_1$. Ou o cruzamento não ocorreu (e não houve movimento algum), ou, no instante supostamente indivisível, cada objeto ocupou duas posições distintas — o que significa que o instante não era, de fato, indivisível.

A resolução moderna é rejeitar a premissa: não existe instante mínimo indivisível. O tempo é denso — entre quaisquer dois instantes, há sempre um terceiro.

### 9.5 Quatro Ataques, Não Quatro Acidentes

Há algo que se perde se lermos os quatro paradoxos como uma lista solta de quebra-cabeças. O próprio Katz chama atenção para um padrão: tomados em conjunto, os quatro paradoxos não se repetem — cada um ataca uma combinação lógica diferente das possíveis hipóteses sobre divisibilidade de espaço e tempo. A Dicotomia e o Aquiles exploram o que acontece se admitirmos divisibilidade infinita; a Flecha e o Estádio exploram o que acontece se admitirmos o oposto, elementos indivisíveis. Visto assim, o conjunto não é uma coleção de quatro ideias parecidas — é uma varredura metódica de todas as posturas filosóficas disponíveis na época sobre a natureza do contínuo, com cada uma delas levada a uma contradição.

(Vale uma ressalva honesta: definir com exatidão qual paradoxo corresponde a qual combinação específica — quem assume o quê sobre espaço e quem assume o quê sobre tempo — é uma questão que os próprios comentadores antigos e modernos não tratam de forma totalmente uniforme; até o relato do Katz contém, num resumo conciso, uma classificação que parece tensionar com a descrição detalhada que ele mesmo dá de cada paradoxo individualmente algumas linhas antes. O que é incontroverso é a conclusão geral: Zenão não estava sendo apenas engenhoso — estava sendo sistemático.)

### 9.6 O Impacto Matemático dos Paradoxos

Os paradoxos de Zenão não eram curiosidades filosóficas — eram ataques diretos aos fundamentos da matemática pitagórica. Se os pitagóricos acreditavam que grandezas geométricas eram compostas de pontos discretos (a "unidade com posição" de Aristóteles), Zenão mostrava que essa crença levava a contradições sobre movimento e divisibilidade.

O impacto foi profundo e duradouro. Os paradoxos forçaram os matemáticos gregos a:

**1. Separar números de grandezas.** Se os números são discretos (há um inteiro entre 3 e 5, mas não entre 3 e 4) e as grandezas geométricas são contínuas (entre quaisquer dois pontos há sempre outro), então números e grandezas são objetos de naturezas diferentes. Essa separação — que Euclides consagra ao tratar aritmética e geometria em livros distintos dos *Elementos* — é uma resposta direta a Zenão. Foi também essa mesma distinção, formalizada por Aristóteles entre o **discreto** (número, base na unidade indivisível) e o **contínuo** (grandeza, divisível em divisíveis infinitamente divisíveis), que daria a Euclides a linguagem precisa para tratar os dois domínios sem confundi-los — algo que veremos com mais detalhe quando chegarmos a Aristóteles (§12).

**2. Evitar o infinito atual.** Os gregos distinguiam o **infinito potencial** (o processo que nunca termina) do **infinito atual** (uma coleção infinita completa). Zenão mostrou que o infinito atual gera paradoxos. Os gregos responderam banindo-o da matemática rigorosa — o que explica por que o método de exaustão de Eudoxo funciona por dupla *reductio ad absurdum* em vez de "somar infinitas fatias".

**3. Desenvolver o método de exaustão.** A saída que Eudoxo encontrou para as questões levantadas por Zenão e pela incomensurabilidade foi demonstrar teoremas sobre áreas e volumes sem nunca afirmar que "a série converge" — mas apenas que a diferença entre a área e qualquer estimativa pode ser tornada menor que qualquer grandeza prefixada. É uma formulação operacional do limite, sem usar o conceito de limite.

### 9.7 Zenão e o Cálculo

Os paradoxos de Zenão ficaram sem resposta satisfatória por dois mil anos. Newton e Leibniz resolveram os paradoxos práticos (como calcular velocidades instantâneas e áreas sob curvas) com o cálculo diferencial e integral — mas a fundação rigorosa do cálculo exigiu mais dois séculos, com Cauchy (1821) e Weierstrass (1872) desenvolvendo a teoria dos limites com precisão formal.

A definição moderna de limite — $\lim_{x \to a} f(x) = L$ significa que para todo $\varepsilon > 0$ existe $\delta > 0$ tal que $|x - a| < \delta \Rightarrow |f(x) - L| < \varepsilon$ — é essencialmente a resposta aos paradoxos de Zenão expressa em linguagem matemática precisa. Zenão perguntou: como somas infinitas podem ser finitas? Weierstrass respondeu: definindo com rigor o que significa "tão próximo quanto se queira" sem nunca atingir o limite.

> **Conexão com o projeto:** Os paradoxos de Zenão descrevem exatamente o problema de **integração numérica em tempo real**: o rover precisa calcular sua posição integrando medições de aceleração (acelerômetro) a cada instante. Mas "cada instante" é, na prática, um intervalo finito $\Delta t$. A soma de infinitos passos infinitesimais (integral contínua) é aproximada por finitos passos finitos (soma de Riemann). O erro acumulado — análogo ao paradoxo da Dicotomia — é o principal desafio de navegação inercial em ambientes sem GPS, como Marte.

---

*Fontes desta parte: Boyer, cap. 4 · Katz, § 2.3.3 · Struik, cap. III*

---
> **Status:** Parte 6 de N — Zenão de Eleia (completa)
> **Próxima parte:** Eudoxo de Cnido — a solução que salvou a matemática grega (teoria das proporções, método de exaustão, axioma de Arquimedes)
