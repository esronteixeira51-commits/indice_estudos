## 22. Papus de Alexandria e o Fim da Tradição Grega

**Papus de Alexandria** (c. 290–350 d.C.) foi o último grande matemático da tradição grega clássica — e tinha plena consciência disso. Sua obra principal, a **Coleção** (*Synagoge*), é ao mesmo tempo um monumento e um epitáfio: um registro sistemático do que os gregos haviam descoberto, enriquecido com resultados novos e generalizações que nenhum predecessor havia alcançado, escrito num momento em que a tradição que ele representava estava visivelmente em declínio.

"Quase tudo o que havia sido estudado pelos matemáticos," escreveu Papus no prefácio, "caiu em esquecimento por causa da escassez de estudiosos que possam lidar com esses assuntos." Era 320 d.C. — a matemática grega tinha 900 anos de história. Ela viveria por mais 200 anos, mas nunca mais atingiria o nível de Papus.

A Coleção provavelmente não foi organizada pelo próprio Papus como um todo unificado — tudo indica que foi reunida, pouco depois de sua morte, por um editor que tentava preservar seus papéis dispersos. Isso explica por que a qualidade dos oito livros varia tanto: alguns são sínteses polidas e originais; outros, levantamentos apressados do trabalho de predecessores.

---

### 22.1 A Coleção — Um Inventário do Saber Grego, e uma Mulher Esquecida

A **Coleção** era originalmente em oito livros. O primeiro e parte do segundo estão perdidos. Os seis livros e meio restantes cobrem:

- **Livro II:** Multiplicação de grandes números (sistema de Apolônio para números acima de $10^8$).
- **Livro III:** Teoria das médias; problemas impossíveis com régua e compasso; os cinco sólidos regulares.
- **Livro IV:** A quadratriz de Hípias; espiral de Arquimedes; generalizações do teorema de Pitágoras.
- **Livro V:** Isoperimetria — qual figura tem maior área para um dado perímetro?
- **Livro VI:** Astronomia e óptica.
- **Livro VII:** O Tesouro da Análise; o Problema de Papus; o Teorema de Papus-Guldin.
- **Livro VIII:** Mecânica — máquinas simples, centros de gravidade.

A Coleção é nossa fonte primária para conhecer obras gregas hoje perdidas — inclusive as *Cônicas* de Aristeu, os *Porismas* de Euclides e vários tratados de Apolônio. Sem Papus, nossa visão da matemática grega seria muito mais fragmentada.

**Um detalhe precioso, e quase único nas fontes gregas.** O prefácio do Livro III é dedicado a **Pandrósia**, descrita por Papus como uma professora de geometria. Ele reclama, com certa irritação, que "algumas pessoas, alegando ter aprendido matemática" com ela, lhe apresentaram recentemente o enunciado errado de certos problemas — especificamente, pessoas que tentavam resolver o problema das duas médias proporcionais (a redução de Hipócrates para a duplicação do cubo, §6.4) usando **apenas régua e compasso**, algo que Papus já considerava impossível, embora não nos diga como sabia disso, dois milênios antes da prova rigorosa de Galois (§13.13).

A queixa de Papus é, ao mesmo tempo, uma reclamação pedagógica e uma evidência histórica rara: mostra que, na Alexandria do século IV d.C., havia **mulheres ensinando geometria avançada** e formando alunos — alunos que, é verdade, nem sempre absorviam corretamente os limites do que régua e compasso podem fazer. Pandrósia não é Hipátia (que viveria uma geração depois, §22.7) — é uma figura quase completamente perdida da história, conhecida apenas por essa única menção incidental. Mas é um lembrete valioso de que a tradição matemática alexandrina, mesmo em seu declínio, não era um clube exclusivamente masculino.

---

### 22.2 Isoperimetria — As Abelhas Sabem Geometria

O Livro V começa com uma epígrafe que captura o espírito de Papus:

> *"As abelhas, em virtude de uma certa intuição geométrica, sabem que o hexágono é maior que o quadrado e o triângulo e conterá mais mel com o mesmo gasto de material."*

O **problema isoperimétrico** pergunta: entre todas as figuras planas com um dado perímetro, qual tem a maior área?

**Caso de polígonos regulares:** Papus demonstrou que, entre polígonos regulares de mesmo perímetro, o que tem mais lados tem maior área. Em particular, o hexágono regular supera o quadrado e o triângulo.

**Prova para o caso hexágono vs. quadrado:**

Seja o perímetro $P$. O lado do hexágono é $P/6$; o lado do quadrado é $P/4$.

Área do hexágono regular: $A_6 = \frac{3\sqrt{3}}{2}\left(\frac{P}{6}\right)^2 = \frac{3\sqrt{3}}{2} \cdot \frac{P^2}{36} = \frac{\sqrt{3}P^2}{24} \approx 0{,}0722\,P^2$

Área do quadrado: $A_4 = \left(\frac{P}{4}\right)^2 = \frac{P^2}{16} = 0{,}0625\,P^2$

$A_6 / A_4 = \frac{\sqrt{3}/24}{1/16} = \frac{2\sqrt{3}}{3} \approx 1{,}155$

O hexágono tem $15{,}5\%$ mais área que o quadrado de mesmo perímetro. As abelhas otimizam — instintivamente ou por evolução — a razão área/material.

**O resultado geral:** Papus demonstrou, seguindo o tratado perdido de Zenodoro (c. 180 a.C.), que o **círculo** tem a maior área entre todas as figuras planas (polígonos ou curvas) de mesmo perímetro. Equivalentemente: entre todas as figuras de mesma área, o círculo tem o menor perímetro.

Isso é o **Problema Isoperimétrico** — cuja demonstração rigorosa só viria com Weierstrass no século XIX. A versão de Zenodoro e Papus era geometricamente convincente mas não rigorosa pelo padrão moderno.

**A versão 3D:** Papus enunciou também que, entre todos os sólidos de mesma superfície, a **esfera** tem o maior volume — o análogo tridimensional. Isso motivaria muito trabalho posterior.

**Aplicação real:** O problema isoperimétrico aparece em toda a engenharia onde material é caro e espaço interno é valioso: design de tanques de combustível (esferas para naves espaciais), design de condutos de fluido (tubos circulares para dado fluxo com mínima perda de pressão), design de antenas (formas que maximizam a área de abertura para dado volume de material). O rover em Marte carrega tanques de propelente com geometria otimizada por esse princípio.

---

### 22.3 O Teorema de Papus — Generalização do Teorema de Pitágoras

No Livro IV, Papus apresenta uma generalização elegante do teorema de Pitágoras que funciona para **qualquer triângulo** — não apenas os retângulos.

**Enunciado:** Seja $ABC$ um triângulo qualquer. Construa paralelogramos $ABDE$ e $BCFG$ sobre os lados $AB$ e $BC$ (quaisquer paralelogramos — não necessariamente quadrados). Prolongue os lados $DE$ e $FG$ até que se encontrem no ponto $H$. Construa sobre $AC$ o paralelogramo $ACJK$ tal que $AK$ e $CJ$ sejam paralelas e iguais a $BH$. Então:

$$\text{Área}(ABDE) + \text{Área}(BCFG) = \text{Área}(ACJK)$$

**Por que é uma generalização:** Quando $\angle ABC = 90°$ e os paralelogramos são quadrados, $BH$ é perpendicular a $AC$ e a construção reproduz exatamente o "moinho de vento" do teorema de Pitágoras (Euclides I.47, §13.3). Para ângulos não retos e paralelogramos não quadrados, o resultado ainda vale.

**Demonstração (esboço):** O paralelogramo $ACJK$ pode ser decomposto e recomposto em partes iguais aos paralelogramos sobre $AB$ e $BC$ por uma série de transformações de áreas preservando igualdade — a técnica padrão dos *Elementos*, aqui aplicada a uma configuração mais geral.

**Exemplo numérico:** Triângulo com $A = (0,0)$, $B = (4, 3)$, $C = (6, 0)$. Construa quadrados sobre $AB$ e $BC$:
- $|AB|^2 = 16 + 9 = 25$, área do quadrado sobre $AB = 25$.
- $|BC|^2 = 4 + 9 = 13$, área do quadrado sobre $BC = 13$.
- A generalização de Papus (com o paralelogramo especial sobre $AC$) dará área total $= 38$.

Verificação: pela lei dos cossenos, $|AC|^2 = |AB|^2 + |BC|^2 - 2|AB||BC|\cos(\angle ABC)$. O ângulo $\angle ABC$ não é reto, então $|AC|^2 \neq 25 + 13 = 38$ em geral — mas o paralelogramo de Papus sobre $AC$ **não** é o quadrado; é um paralelogramo específico construído pela receita de Papus, e sua área é exatamente $38$. ✓

---

### 22.4 O Problema de Papus — O Gatilho da Geometria Analítica

O resultado mais importante historicamente na Coleção é o **Problema de Papus** no Livro VII, mencionado em conexão com Apolônio (§15.6) mas que merece tratamento completo aqui.

**O problema em sua forma mais simples (quatro retas):**

Dadas quatro retas $\ell_1, \ell_2, \ell_3, \ell_4$ no plano, encontrar o lugar geométrico dos pontos $P$ tais que:

$$d(P, \ell_1) \cdot d(P, \ell_3) = k \cdot d(P, \ell_2) \cdot d(P, \ell_4)$$

onde $d(P, \ell_i)$ é a distância de $P$ à reta $\ell_i$ (medida em ângulo fixado com a reta) e $k$ é uma constante.

**O resultado:** O lugar geométrico é sempre uma seção cônica — elipse, parábola ou hipérbole (possivelmente degenerada em retas ou um ponto).

Papus demonstrou isso por métodos sintéticos, seguindo Apolônio. Mas então fez algo mais ousado: **generalizou para $n$ retas**.

**Para 6 retas:** Encontrar $P$ tal que $d_1 \cdot d_3 \cdot d_5 = k \cdot d_2 \cdot d_4 \cdot d_6$. Isso é uma equação de grau 3 em coordenadas — uma curva cúbica, geralmente.

**O limite das três dimensões — e como Papus tentou escapar dele.** Papus foi honesto sobre onde sua própria generalização travava. Para quatro ou seis retas, o problema ainda fazia sentido geometricamente: o produto de até três distâncias podia ser interpretado como o volume de um paralelepípedo retangular — um objeto genuíno do espaço tridimensional. Mas, ao considerar **mais de seis retas**, ele próprio observou que a linguagem geométrica simplesmente quebra: não se pode mais falar da "razão entre a figura contida por quatro delas e a figura contida pelo restante", porque — em suas palavras — **nenhuma figura pode ser contida em mais de três dimensões**. É a mesma barreira que Herão já havia ignorado silenciosamente ao multiplicar quatro comprimentos em sua fórmula da área (§20.2) — mas Papus, ao contrário de Herão, *reconhece* explicitamente o problema em vez de simplesmente contorná-lo.

E então, notavelmente, Papus sugere uma saída: mesmo sem um objeto geométrico de dimensão superior a três para representar o produto, pode-se ainda assim **expressar a razão compondo as razões que as retas individuais mantêm entre si** — tratando o produto não como um volume físico, mas como uma operação algébrica abstrata sobre números. É um vislumbre, momentâneo e não desenvolvido, exatamente da mudança de perspectiva que a álgebra simbólica tornaria rotineira: abandonar a exigência de que cada operação corresponda a um objeto geométrico concreto. Papus chegou a ver a porta — mas não tinha o vocabulário para abri-la. Ele próprio reconheceu a derrota, com uma nota de amargura: lamentou que os geômetras de sua geração não tivessem resolvido o problema "a ponto de a curva ser reconhecível", e comentou que os matemáticos contemporâneos "não têm a mesma qualidade dos antigos e dos melhores escritores".

**Em 1637, Descartes pegou o desafio.**

René Descartes estava escrevendo *La Géométrie* — o apêndice ao *Discurso do Método* onde apresentava sua geometria analítica recém-inventada. Para demonstrar seu poder, escolheu o Problema de Papus como teste.

Em notação cartesiana, se as retas têm equações lineares em $x$ e $y$, as distâncias $d_i(P)$ são expressões lineares em $x$ e $y$. O produto de $n$ distâncias é um polinômio de grau $n$. A condição $d_1 \cdots d_n = k \cdot d_{n+1} \cdots d_{2n}$ é uma equação de grau $n$ em $x$ e $y$ — que define uma curva de grau $n$.

Para $n = 2$ (quatro retas): equação de grau 2 $\Rightarrow$ cônica. ✓ (Confirma Apolônio.)
Para $n = 3$ (seis retas): equação de grau 3 $\Rightarrow$ curva cúbica. (Novo resultado.)
Para $n = 4$ (oito retas): equação de grau 4 $\Rightarrow$ quártica. (Impossível sem álgebra.)

"Este problema," escreveu Descartes, "foi o que primeiro me levou a tentar encontrar um novo método de geometria." O Problema de Papus, posto em linguagem algébrica, revelava que a geometria analítica classificava automaticamente curvas de qualquer grau — exatamente a porta que Papus havia entrevisto sem conseguir atravessar, treze séculos antes.

O problema que Papus deixou em aberto foi o problema que gerou a geometria moderna.

---

### 22.5 O Teorema de Papus-Guldin — Volumes por Centróides

No Livro VII da Coleção, Papus enuncia dois teoremas sobre sólidos e superfícies de revolução que hoje carregam seu nome junto ao do matemático suíço Paul Guldin (1577–1643), que os redescobriu independentemente:

**Primeiro Teorema (Superfícies):** Se uma curva plana de comprimento $L$ gira em torno de um eixo externo a ela, a área da superfície gerada é:

$$A = 2\pi \bar{d} \cdot L$$

onde $\bar{d}$ é a distância do centróide (centro de gravidade) da curva ao eixo de rotação.

**Segundo Teorema (Volumes):** Se uma região plana de área $S$ gira em torno de um eixo externo a ela, o volume do sólido gerado é:

$$V = 2\pi \bar{d} \cdot S$$

onde $\bar{d}$ é a distância do centróide da região ao eixo de rotação.

**Exemplo — Toro (rosquinha):** Um círculo de raio $r$ com centro a distância $R > r$ do eixo de rotação gera um toro quando rotacionado. O centróide do círculo está no seu centro, a distância $R$ do eixo.

$$V_{\text{toro}} = 2\pi R \cdot \pi r^2 = 2\pi^2 R r^2$$
$$A_{\text{toro}} = 2\pi R \cdot 2\pi r = 4\pi^2 R r$$

**Verificação para $R = 3$, $r = 1$:** $V = 2\pi^2 \cdot 3 \cdot 1 = 6\pi^2 \approx 59{,}2$. Integrando diretamente, o resultado coincide. ✓

**Por que o teorema é poderoso:** Permite calcular volumes de sólidos complexos sem integração direta — apenas conhecendo o centróide. Papus o apresentou como "um grande número de teoremas de todos os tipos sobre curvas, superfícies e sólidos, todos demonstrados simultaneamente por uma única demonstração." É uma das primeiras instâncias de um **teorema unificador** na matemática — um resultado que engloba infinitos casos particulares. Curiosamente, não há registro da demonstração original de Papus para esse resultado — apenas o enunciado; é possível que a prova estivesse num dos livros da Coleção hoje perdidos.

**Exemplo de aplicação real:** O volume de combustível num tanque toroidal (usado em alguns veículos espaciais para envolver o motor central) é calculado diretamente pelo segundo teorema de Papus-Guldin: $V = 2\pi \bar{d} \cdot S$, onde $S$ é a área da seção transversal do tanque e $\bar{d}$ é a distância do centróide dessa seção ao eixo do veículo.

---

### 22.6 O Tesouro da Análise — e uma Omissão Curiosa

O Livro VII da Coleção descreve uma coleção de obras conhecida como **Tesouro da Análise** (*Domain of Analysis*) — uma biblioteca de textos avançados destinados a quem já havia estudado os *Elementos* e queria ir além. Papus não reproduz esses textos — apenas os comenta, com lemas auxiliares destinados a ajudar o leitor a atravessar passagens que os autores originais, séculos antes, haviam considerado "óbvias".

Papus descreve o método central dessas obras:

> *"A análise é o procedimento de assumir como conhecido o que se busca, e daí passar pelas suas consequências até algo que seja aceito como verdadeiro pela síntese."*

Em outras palavras: para demonstrar que $X$ é verdadeiro, **assuma** $X$, derive consequências até chegar a algo evidentemente verdadeiro, depois **inverta o argumento**. Se a inversão é possível, a demonstração está completa.

Esse é o **método analítico** — atribuído a Platão, formalizado por Papus, e ainda hoje o método padrão de descoberta matemática. Quando um matemático hoje "chuta" uma solução e depois verifica que funciona, está usando o método de Papus.

As obras no Tesouro incluíam:
- *Divisão de figuras* de Euclides.
- *Dados* de Euclides.
- *Porismas* de Euclides (perdido).
- *Lugares Geométricos Planos* de Apolônio (perdido).
- *Cônicas* de Apolônio (parcialmente preservada).
- *Dividir em uma Razão* de Apolônio (preservada em tradução árabe).
- *Lugares Geométricos Sólidos* de Aristeu (perdido).
- *Sobre Médias* de Eratóstenes (perdido).

Papus também menciona que as *Cônicas* de Apolônio continham 487 teoremas — e como os sete livros preservados contêm 382, o oitavo (perdido) devia conter 105.

**Uma ausência reveladora.** Há algo de genuinamente curioso na lista de Papus: a *Arithmetica* de Diofanto (§21) não aparece em lugar nenhum do Tesouro da Análise — apesar de, na prática, **todo problema da Arithmetica seguir exatamente o método analítico** que Papus descreve: assumir a incógnita, derivar uma equação, resolver, verificar. Por que essa omissão? Não sabemos com certeza, mas a hipótese mais plausível é que Papus considerasse o trabalho puramente algébrico de Diofanto de um nível diferente — talvez menos "nobre" — do que os tratados geométricos clássicos que compunham sua lista. Se essa hipótese estiver certa, é uma ironia digna de nota: o próprio teórico do método analítico não reconheceu, no melhor exemplo desse método disponível em sua época, um exemplo digno de menção. A tradição algébrica e a tradição geométrica grega, como já vimos em §21.6, nunca se reconheceram plenamente uma à outra — mesmo quando uma delas, sem saber, já estava praticando o que a outra apenas teorizava.

---

### 22.7 Hipátia — A Última Luz de Alexandria

Depois de Papus, a matemática grega entrou num declínio progressivo que não era apenas intelectual — era civilizacional. E nenhuma figura encarna esse declínio com mais força do que **Hipátia de Alexandria** (c. 360–415 d.C.) — a quem já fizemos referência duas vezes neste capítulo (§21.1, sobre a possível autoria dos livros árabes de Diofanto, e §18, indiretamente, através de Ptolomeu) e que merece, agora, seu devido espaço.

Filha do matemático e astrônomo **Téon de Alexandria** (que produziu a edição padrão dos *Elementos* de Euclides usada por toda a Antiguidade tardia e a Idade Média — a maioria dos manuscritos que sobreviveram até hoje derivam da recensão de Téon, não do texto original), Hipátia foi educada por ele desde jovem e superou-o em reputação. Ensinou matemática, astronomia e filosofia neoplatônica em Alexandria, atraindo alunos de toda a região — incluindo cristãos, o que é notável dado o contexto religioso cada vez mais tenso de sua época.

**O que sabemos de sua obra matemática** vem inteiramente de referências indiretas, já que nenhum texto firmado por ela sobreviveu independentemente:

- Um **comentário sobre o Almagesto de Ptolomeu** (§18), do qual parte pode estar incorporada nas edições que usamos hoje — alguns historiadores acreditam que o Livro III do Almagesto, na forma como chegou até nós, reflete o trabalho editorial de Hipátia.
- Uma possível **edição comentada das *Cônicas* de Apolônio** (§15), ajudando a preservar e simplificar passagens difíceis — exatamente o tipo de trabalho que Papus descreve fazer para o Tesouro da Análise (§22.6), sugerindo que Hipátia trabalhava na mesma tradição editorial e pedagógica.
- Como já vimos em §21.1, é genuinamente possível que os quatro livros "árabes" da *Arithmetica* de Diofanto que sobreviveram sejam, na verdade, uma tradução de um **comentário de Hipátia** sobre a obra — não o texto original de Diofanto. Se for esse o caso, Hipátia não é apenas uma transmissora passiva: parte do que aprendemos hoje sobre álgebra diofantina pode estar filtrado pela sua própria voz pedagógica, sem que percebamos.

Em **415 d.C.**, Hipátia foi assassinada por uma multidão em Alexandria, num contexto de conflito político e religioso entre o patriarca cristão Cirilo e o prefeito romano Orestes — conflito em que ela, como figura pública influente e pagã, tornou-se alvo. O evento é frequentemente marcado como o fim simbólico da matemática alexandrina — embora a causalidade seja mais complexa do que costuma ser contada. A Biblioteca de Alexandria já havia sido danificada (não "queimada completamente", como o mito popular sugere) em episódios anteriores; o *Museum* continuou funcionando por algum tempo depois. Mas o assassinato de Hipátia representa o momento em que Alexandria deixou de ser um lugar seguro para o tipo de investigação intelectual independente que ela representava — e é, com razão, o ponto onde a maioria dos historiadores traça o fim de uma era de mil anos de matemática alexandrina, de Euclides a ela.

**Sobre Proclo**, que viria a desempenhar papel crucial na preservação do que sabemos sobre os matemáticos pré-euclidianos — já o apresentamos com o devido detalhe em §13.12, quando discutimos as tentativas antigas de demonstrar o quinto postulado. Basta aqui registrar a cronologia: Proclo nasceu em 412 d.C., três anos antes da morte de Hipátia, e dirigiria a Academia de Atenas algumas décadas depois — a última geração de uma tradição filosófica que remontava, nominalmente, setecentos anos a Platão.

Em **529 d.C.**, o imperador Justiniano fechou as escolas filosóficas de Atenas por decreto — considerando-as focos de paganismo incompatíveis com o Império Cristão. Vários filósofos foram para a Pérsia, onde o rei sassânida os acolheu. Essa data é convencionalmente marcada como o fim da matemática grega na Europa.

**Boécio** (c. 480–524 d.C.), filósofo romano que tentou traduzir para o latim toda a lógica de Aristóteles e vários tratados matemáticos gregos, foi executado pelo rei ostrogodo Teodorico em 524 d.C. por suspeita de traição. Na prisão, escreveu *De Consolatione Philosophiae* — um dos textos mais lidos da Idade Média. Seus manuais matemáticos (baseados em Nicômaco e Euclides) eram elementares, mas foram a principal fonte de matemática grega no Ocidente latino por séculos.

---

### 22.8 Por Que a Tradição Grega Terminou

O declínio da matemática grega não foi um evento súbito — foi um processo de dois séculos. Várias causas contribuíram:

**1. Ausência de mecanismos institucionais:** A matemática grega dependia de patronato real (os Ptolomeus em Alexandria) e de escolas filosóficas (a Academia, o Liceu). Quando o patronato secou e as escolas foram fechadas ou marginalizadas, não havia universidades, sociedades científicas ou publicações periódicas para manter a tradição viva.

**2. A crise do papiro:** O papiro egípcio — o principal meio de escrita — tornou-se escasso e caro no período tardio. Muitos textos foram simplesmente não copiados. O que não foi copiado, perdeu-se quando os exemplares originais se deterioraram.

**3. A mudança de valores:** O neoplatonismo tardio e o cristianismo nascente compartilhavam uma desconfiança do conhecimento mundano e empírico em favor da contemplação espiritual. A matemática continuou sendo valorizada como disciplina propedêutica — mas o impulso para descobrir coisas novas diminuiu.

**4. O problema das fontes:** À medida que as obras originais iam sendo perdidas, os estudiosos posteriores se tornavam comentadores — explicando textos existentes em vez de produzir novos resultados. Comentar é mais fácil que descobrir; e a acumulação de comentários sobre comentários diluía progressivamente o conteúdo matemático. Papus, Téon e Hipátia — os três últimos nomes importantes desta seção — eram, cada um à sua maneira, primariamente comentadores.

**5. A ausência de álgebra simbólica:** Sem uma notação algébrica eficiente, cada resultado novo exigia argumentação geométrica longa e ad hoc. O espaço de problemas atacáveis era limitado pelo que a geometria sintética conseguia expressar. Quando Diofanto apontou o caminho para uma álgebra mais eficiente, ninguém o seguiu — nem mesmo Papus, como vimos em §22.6, reconheceu plenamente seu valor.

---

### 22.9 O Legado — O Que Sobreviveu e Por Quê

Dos tesouros da matemática grega, o que chegou até nós chegou por três rotas:

**Rota 1 — Manuscritos gregos em Constantinopla:** O Império Romano do Oriente manteve a tradição de copiar textos gregos. Quando Constantinopla caiu para os turcos otomanos em 1453, muitos estudiosos fugiram para a Itália carregando manuscritos — precipitando o Renascimento italiano. Os *Elementos* de Euclides e as *Cônicas* de Apolônio chegaram ao Ocidente por essa rota.

**Rota 2 — Tradução árabe:** A partir do século VIII, os califas abássidas em Bagdá financiaram a tradução sistemática de textos gregos para o árabe. Matemáticos como al-Khwarizmi, Thabit ibn Qurra e al-Biruni não apenas traduziram — desenvolveram as ideias gregas em novas direções. Os três últimos livros das *Cônicas* de Apolônio sobrevivem apenas em tradução árabe — e, como vimos, talvez quatro dos treze livros de Diofanto sobrevivam apenas através do filtro de um comentário de Hipátia, ele mesmo só preservado em árabe.

**Rota 3 — Citações em autores posteriores:** Muitos resultados de matemáticos cujas obras se perderam (Aristeu, Teeteto, Eudemo) chegaram até nós apenas porque Proclo, Papus ou outros os citaram. Sem a *Coleção* de Papus, Hiparco, Menelau e Aristeu seriam praticamente desconhecidos. Sem Proclo, não saberíamos quase nada sobre Tales e os matemáticos anteriores a Platão (§1.3).

O que se perdeu é, provavelmente, mais do que o que sobreviveu. Papus menciona dezenas de obras que não temos. A *História da Geometria* de Eudemo — nossa fonte primária sobre a matemática pré-platônica, preservada apenas via Proclo — está perdida em sua forma original. Os *Porismas* de Euclides, descritos por Papus como uma das obras mais profundas da Antiguidade, estão perdidos. Os oito livros originais de Hiparco sobre cordas estão perdidos.

Mas o que sobreviveu foi suficiente para dar ao Renascimento europeu as ferramentas que precisava — e, indiretamente, para tornar possível a Revolução Científica do século XVII.

> **Conexão com o projeto:** O Problema de Papus — encontrar curvas satisfazendo condições de distância a múltiplas retas — é formalmente equivalente ao problema de **localização por múltiplas medições**: dado um conjunto de balizas (retas ou pontos de referência) e medições de distância ou ângulo a cada uma, encontrar a posição do rover. Os algoritmos modernos de localização e mapeamento simultâneos (SLAM) usados em rovers autônomos resolvem exatamente esse problema para centenas de pontos de referência em tempo real. O Teorema de Papus-Guldin, por sua vez, é a ferramenta padrão para calcular momentos de inércia de sólidos de revolução — necessários para o projeto do sistema de estabilização de atitude do rover durante o pouso e as manobras. E a barreira dimensional que Papus reconheceu — nenhuma figura geométrica cabe em mais de três dimensões — é exatamente o motivo pelo qual sistemas de controle modernos abandonam representações geométricas literais em favor de **espaços de estado** abstratos de dimensão arbitrária: um rover com seis graus de liberdade (posição e orientação) já exige um espaço de estado de pelo menos doze dimensões (incluindo velocidades), algo que nenhuma figura física jamais poderia representar — exatamente a "porta" que Papus viu mas não conseguiu abrir.

---

*Fontes desta parte: Katz, §§ 6.3–6.4 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 27 de N — Papus de Alexandria (completa)
> **Próxima parte:** Seção C (Legado e Transmissão) e Síntese do Período — fechamento do capítulo
