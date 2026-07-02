## 5. A Idade Heroica da Matemática (c. 450–400 a.C.)

Entre o fim da geração pitagórica e a fundação da Academia de Platão, a matemática grega passou por uma fase que Boyer chamou, com razão, de **Idade Heroica**: raramente, antes ou depois, homens com tão poucos recursos metodológicos atacaram problemas de significado tão fundamental.

O contexto histórico é o século V a.C. — o mesmo século das Guerras Médicas e da Idade de Péricles, de Sófocles e Tucídides. Atenas havia derrotado os persas em Maratona e Salamina e vivia seu auge político e cultural. A prosperidade da cidade atraiu sábios de todo o mundo grego, e o encontro de temperamentos jônios (pragmáticos, curiosos sobre a natureza) com temperamentos itálicos (metafísicos, influenciados pelo pitagorismo) produziu uma síntese explosiva.

Sete matemáticos concentram as realizações do período:

| Matemático | Origem | Contribuição central |
|---|---|---|
| Hipócrates de Quios | Quios (Egeu) | Quadratura de lúnulas, redução do problema de Delos |
| Hípias de Elis | Elis (Peloponeso) | A quadratriz — primeira curva além de reta e círculo |
| Zenão de Eleia | Eleia (Itália) | Os quatro paradoxos do movimento e da divisibilidade |
| Demócrito de Abdera | Abdera (Trácia) | Volumes de cone e pirâmide, atomismo geométrico |
| Anaxágoras de Clazomene | Clazomene (Jônia) | Primeira tentativa de quadratura do círculo |
| Arquitas de Tarento | Tarento (Itália) | Solução tridimensional da duplicação do cubo |
| Hipasus de Metaponto | Metaponto (Itália) | Descoberta dos irracionais (ver §4.8) |

Nenhuma obra matemática original desse período sobreviveu. Temos apenas fragmentos preservados por Simplício (século VI d.C.) citando Eudemo (século IV a.C.) — a cadeia de transmissão descrita em §1.3. Mas a consistência dos relatos e a coerência interna dos resultados atribuídos a esses matemáticos sugerem que as tradições são substancialmente confiáveis.

### 5.1 Os Três Problemas Clássicos

O que une os matemáticos da Idade Heroica é que quase todos trabalharam em torno de três problemas que se tornaram os desafios definidores da geometria grega — e permaneceriam sem solução por mais de dois mil anos:

**1. Quadratura do círculo:** dado um círculo, construir com régua e compasso um quadrado de mesma área.

**2. Duplicação do cubo (Problema de Delos):** dada a aresta de um cubo, construir com régua e compasso a aresta de um cubo com o dobro do volume.

**3. Trissecção do ângulo:** dado um ângulo arbitrário, construir com régua e compasso um ângulo igual a um terço do dado.

A condição "só com régua e compasso" é fundamental. A régua permite traçar retas; o compasso, arcos de círculo. Com esses dois instrumentos, os gregos podiam construir raízes quadradas, somas, diferenças e produtos de segmentos — mas não raízes cúbicas nem $\pi$. No século XIX, a teoria de Galois demonstraria rigorosamente que os três problemas são *impossíveis* sob essa restrição — a quadratura porque $\pi$ é transcendente, a duplicação porque $\sqrt[3]{2}$ não é construtível, a trissecção porque o ângulo geral não é. Mas o esforço de atacar o impossível produziu boa parte da matemática grega.

A origem dos dois primeiros problemas é envolta em lenda. Anaxágoras, preso em Atenas por afirmar que o Sol era uma pedra incandescente (não uma divindade), teria tentado quadrar o círculo durante o cativeiro. A duplicação do cubo teria nascido de uma consulta ao oráculo de Delos sobre como deter uma peste — o oráculo teria exigido que o altar cúbico de Apolo fosse duplicado, e os atenienses, ao simplesmente dobrar as dimensões lineares, multiplicaram o volume por oito em vez de dois.

**Um detalhe que mostra o alcance cultural do problema:** a quadratura do círculo não era assunto restrito a matemáticos especializados — era conhecida o suficiente pelo público ateniense comum para servir de piada. Na comédia *As Aves*, de Aristófanes, apresentada em **414 a.C.**, uma personagem chamada Méton aparece em cena carregando instrumentos de geometria e anunciando que vai "quadrar o círculo" para planejar as ruas de uma cidade utópica — e a fala é recebida como absurdo cômico pelo público. Isso é evidência direta e datável de que, já em 414 a.C., o ateniense médio sabia que "quadrar o círculo" significava tentar o impossível. O problema havia escapado dos círculos acadêmicos e se tornado parte da cultura geral — um pouco como hoje "resolver a parada do P versus NP" funciona como referência cômica para algo notoriamente difícil.

> **Conexão com o projeto:** A impossibilidade dos três problemas clássicos sob restrições específicas é um resultado sobre o que é *computável* com um dado conjunto de ferramentas. A engenharia de sistemas embarcados enfrenta restrições análogas: não é toda função matemática que pode ser calculada em tempo real com os recursos disponíveis. Saber o que é impossível sob dadas restrições é tão valioso quanto saber o que é possível.

---

## 6. Hipócrates de Quios — A Primeira Área Curvilínea

**Hipócrates de Quios** (c. 470–410 a.C.) não deve ser confundido com seu famoso contemporâneo, o médico Hipócrates de Cós. O matemático Hipócrates era mercador da ilha de Quios que, segundo Aristóteles, foi roubado — por piratas ou por fraude em Bizâncio — e chegou a Atenas arruinado. Foi ali que se voltou para a geometria, onde alcançou sucesso notável. A história é típica da Idade Heroica: a matemática como refúgio e ascensão intelectual.

Proclo informa que Hipócrates compilou os primeiros *Elementos* da geometria grega — antecipando Euclides por mais de um século. O texto se perdeu. Mas temos algo mais raro: um fragmento preservado por Simplício, que afirma tê-lo copiado literalmente de Eudemo. É o trecho mais antigo de matemática grega que conhecemos em algo próximo ao original.

### 6.1 O Teorema Fundamental de Hipócrates

O fragmento descreve a demonstração de Hipócrates de um resultado sobre áreas de círculos:

> *Segmentos de círculo semelhantes estão na mesma razão que os quadrados de suas bases.*

Em linguagem moderna: se dois segmentos circulares são semelhantes (ângulos centrais iguais), suas áreas são proporcionais aos quadrados de suas cordas. Desse resultado, Hipócrates derivou um corolário sobre círculos inteiros: **as áreas de dois círculos estão entre si como os quadrados de seus diâmetros** — um fato que, segundo Katz, já era conhecido empiricamente pelos escribas babilônios, mas que Hipócrates foi o primeiro a tentar justificar por argumento dedutivo.

Este teorema — hoje demonstrado trivialmente por $A = \pi r^2$ — exigiu no século V a.C. um argumento cuidadoso, pois os irracionais acabavam de ser descobertos e a teoria das proporções ainda não era rigorosa o suficiente para lidar com grandezas incomensuráveis. O mérito de Hipócrates foi *enunciar* o teorema com precisão e oferecer uma justificativa suficientemente convincente para sua época. A demonstração rigorosa viria de Eudoxo, um século depois (ver §9).

### 6.2 A Quadratura das Lúnulas

Com esse teorema em mãos, Hipócrates realizou a **primeira quadratura rigorosa de uma área curvilínea** na história da matemática — isto é, a primeira vez que se demonstrou que uma região delimitada por curvas tem a mesma área que um polígono exato.

Uma **lúnula** (*menisco*) é a região em forma de crescente delimitada por dois arcos circulares de raios diferentes. O resultado de Hipócrates foi que certas lúnulas têm área exatamente igual à de triângulos — e portanto podem ser "quadradas" (convertidas em quadrados de mesma área).

**Primeira quadratura:** Considere um triângulo isósceles retângulo $ABC$ com o ângulo reto em $B$, inscrito num semicírculo de diâmetro $AC$. Sobre a hipotenusa $AC$ construa um segmento circular semelhante aos segmentos sobre os lados $AB$ e $BC$.

Como os segmentos são semelhantes, suas áreas são proporcionais aos quadrados das bases. Pelo teorema de Pitágoras, $AC^2 = AB^2 + BC^2$, logo o segmento sobre $AC$ tem área igual à soma dos segmentos sobre $AB$ e $BC$.

Portanto: a lúnula formada entre o semicírculo sobre $AC$ e o arco sobre $AB$ e $BC$ tem área **exatamente igual** ao triângulo $ABC$.

Não uma aproximação — uma igualdade exata. E o triângulo pode ser convertido num quadrado de mesma área por construção com régua e compasso. A lúnula foi "quadrada".

**Segunda quadratura:** Hipócrates estendeu o resultado para um trapézio isósceles $ABCD$ inscrito num círculo, com $AD^2 = AB^2 + BC^2 + CD^2$. A lúnula construída sobre $AD$ tem área igual ao trapézio. Eudemo descreve ainda uma terceira e uma quarta quadratura, de configurações mais complexas.

### 6.3 Por Que Isso Importa

Hipócrates sabia que suas quadraturas de lúnulas *não* implicavam a quadratura do círculo — ele trabalhava com lúnulas específicas, não com qualquer região curvilínea. Mas o resultado era encorajador: se áreas curvilíneas podiam ser igualadas a polígonos, talvez o círculo inteiro também pudesse. O próprio Katz observa que, embora Hipócrates tenha dado construções para quadrar outras lúnulas e combinações de lúnulas, ele nunca conseguiu de fato quadrar um círculo completo — e é justamente o padrão consistente de tentativa, parcial sucesso e limite intransponível que caracteriza toda a Idade Heroica.

O que não sabia — e só seria demonstrado em 1882 por Lindemann — é que $\pi$ é transcendente, e portanto a quadratura do círculo com régua e compasso é impossível. O entusiasmo de Hipócrates era compreensível e frutífero: perseguir o impossível o levou a criar ferramentas matemáticas genuinamente novas, organizadas por ele mesmo no primeiro livro conhecido de elementos de geometria.

### 6.4 A Redução do Problema de Delos

Hipócrates também fez o progresso mais importante do período sobre a duplicação do cubo — e a forma como ele chegou lá ilustra perfeitamente a filosofia de "ir do concreto ao abstrato" que guia este projeto.

**O caso mais simples primeiro — dobrar um quadrado.** Antes de atacar o cubo, considere o problema mais fácil: dado um quadrado de lado $a$, como construir um quadrado de área dupla? A resposta clássica é encontrar uma **média proporcional** $b$ entre $a$ e $2a$ — ou seja, um valor $b$ tal que

$$\frac{a}{b} = \frac{b}{2a}$$

Multiplicando cruzado, $b^2 = 2a^2$ — exatamente o lado do quadrado de área dupla. Esse $b$ é construtível com régua e compasso (é a diagonal do quadrado original, como o próprio teorema de Pitágoras garante). Hipócrates certamente dominava esse tipo de construção com média proporcional única.

**Generalizando para três dimensões.** O insight de Hipócrates foi perceber que o problema do cubo é a versão tridimensional desse mesmo mecanismo — só que em vez de **uma** média proporcional entre $a$ e $2a$, são necessárias **duas**: dadas duas grandezas $a$ e $b$, inserir duas médias proporcionais $x$ e $y$ entre elas, ou seja, encontrar $x$ e $y$ tais que:

$$\frac{a}{x} = \frac{x}{y} = \frac{y}{b}$$

Se $b = 2a$, eliminando $y$ da proporção:

$$x^3 = a^2 \cdot b = 2a^3$$

Logo $x = a\sqrt[3]{2}$ — exatamente a aresta do cubo duplicado.

A redução de Hipócrates transformou um problema geométrico obscuro num problema algébrico preciso: encontrar duas médias proporcionais entre dois segmentos dados. Mas há uma diferença crucial entre o caso do quadrado e o caso do cubo: **uma** média proporcional é sempre construtível com régua e compasso — é só uma raiz quadrada. **Duas** médias proporcionais simultâneas, porém, equivalem a extrair uma raiz cúbica — e isso, como a matemática do século XIX provaria, está fora do alcance da régua e do compasso. Hipócrates identificou exatamente o problema certo a resolver; não tinha, e não poderia ter, as ferramentas para resolvê-lo dentro das regras clássicas.

Esse problema, por sua vez, inspiraria soluções engenhosas de Arquitas (§7), Menaecmo (§13) e do próprio Apolônio — cada um abandonando a restrição de régua e compasso e usando curvas diferentes para "inserir" as médias.

> **Conexão com o projeto:** A inserção de duas médias proporcionais entre $a$ e $b$ é equivalente a calcular $a \cdot (b/a)^{1/3}$ e $a \cdot (b/a)^{2/3}$ — isto é, interpolar geometricamente em escala logarítmica. Essa operação aparece hoje no projeto de antenas de banda larga e em filtros de frequência para o sistema de comunicação do rover: a escala logarítmica é a "proporção contínua" do espaço de frequências. E a lição metodológica de Hipócrates — resolver primeiro a versão mais simples e de dimensão menor de um problema antes de generalizar — é exatamente a estratégia recomendada hoje em otimização numérica: testar um algoritmo de controle num modelo 1D ou 2D simplificado antes de generalizar para o espaço de estados completo de um rover em 3D.

---

*Fontes desta parte: Boyer, cap. 4 · Katz, §§ 2.1.4 · Struik, cap. III*

---
> **Status:** Parte 3 de N — A Idade Heroica (introdução) + Hipócrates de Quios (completa)
> **Próxima parte:** Hípias de Elis — a quadratriz e a trissecção do ângulo
