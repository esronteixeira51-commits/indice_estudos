## 18. Ptolomeu de Alexandria — A Síntese Matemática do Cosmos

**Cláudio Ptolomeu** (c. 100–170 d.C.) fez observações astronômicas em Alexandria de 127 a 151 d.C. Quase nada se sabe de sua vida pessoal. O que sabemos é que escreveu, em treze livros, a obra mais influente da astronomia pré-moderna — a *Syntaxis Mathematike* ("Síntese Matemática"), que os árabes chamariam de *al-majisti* ("a maior"), e que chegou ao Ocidente como **Almagesto**.

O Almagesto foi o modelo astronômico padrão do mundo ocidental por **1.400 anos** — de 150 d.C. até a publicação do *De Revolutionibus* de Copérnico em 1543. Nenhum outro livro científico, com exceção dos *Elementos* de Euclides, exerceu influência comparável sobre o pensamento humano por tanto tempo.

Mas o Almagesto não é apenas astronomia. É também o tratado de trigonometria mais completo da Antiguidade — com a primeira tabela de cordas rigorosamente construída e documentada que sobreviveu até hoje. Diferente da tabela de Hiparco (§17.6), perdida e reconstruída apenas indiretamente, a de Ptolomeu sobreviveu por completo — e usa o raio $R = 60$ (diâmetro $120$), a convenção sexagesimal mais simples que mencionamos ao final daquela seção.

---

### 18.1 O Teorema de Ptolomeu — A Chave das Tabelas

A peça central da trigonometria de Ptolomeu é um teorema sobre quadriláteros inscritos num círculo, que leva seu nome:

> **Teorema de Ptolomeu:** Se $ABCD$ é um quadrilátero convexo inscrito num círculo, então o produto das diagonais é igual à soma dos produtos dos pares de lados opostos:
> $$AC \cdot BD = AB \cdot CD + BC \cdot AD$$

**Demonstração:** Marque o ponto $E$ sobre $AC$ tal que $\angle ABE = \angle DBC$. Então $\triangle ABE \sim \triangle DBC$ (ângulos iguais, pois $\angle BAE = \angle BDC$ como ângulos inscritos no mesmo arco). Logo $AB/DB = AE/DC$, ou seja $AE = AB \cdot DC / DB$.

Também $\triangle ABD \sim \triangle EBC$ (mesmos ângulos). Logo $AD/EC = BD/BC$, ou seja $EC = BC \cdot AD / BD$.

Somando: $AC = AE + EC = \frac{AB \cdot DC + BC \cdot AD}{BD}$, que é o teorema. ∎

**Por que isso constrói tabelas de cordas:** Considere um caso especial onde $AD$ é um **diâmetro** do círculo de raio $R = 60$ (diâmetro $= 120$). Posicione os pontos tal que o arco $BD = 2\alpha$ e o arco $CD = 2\beta$. Então:

$$BD = \text{corda}(2\alpha), \quad CD = \text{corda}(2\beta), \quad BC = \text{corda}(2\alpha - 2\beta)$$
$$AB = \text{corda}(180° - 2\alpha), \quad AC = \text{corda}(180° - 2\beta)$$

Substituindo no Teorema de Ptolomeu com $AD = 120$:

$$120 \cdot \text{corda}(2\alpha - 2\beta) = \text{corda}(2\alpha) \cdot \text{corda}(180° - 2\beta) - \text{corda}(2\beta) \cdot \text{corda}(180° - 2\alpha)$$

Usando $\text{corda}(\theta) = 120\sin(\theta/2)$:

$$\sin(\alpha - \beta) = \sin\alpha\cos\beta - \cos\alpha\sin\beta$$

É a fórmula da subtração do seno — derivada diretamente do Teorema de Ptolomeu. É exatamente a mesma fórmula que vimos Hiparco usar (§17.6) — mas agora demonstrada a partir de um teorema geométrico autônomo e elegante, em vez de assumida diretamente. Analogamente, variando a configuração, obtém-se:

$$\sin(\alpha + \beta) = \sin\alpha\cos\beta + \cos\alpha\sin\beta$$
$$\cos(\alpha \pm \beta) = \cos\alpha\cos\beta \mp \sin\alpha\sin\beta$$

Ptolomeu não escreveu essas fórmulas com senos e cossenos — mas as usou na linguagem de cordas, e são completamente equivalentes. Por isso são às vezes chamadas **fórmulas de Ptolomeu**.

---

### 18.2 A Fórmula do Arco Metade

Para construir sua tabela em incrementos finos, Ptolomeu precisava também da fórmula que reduz a corda de $\theta$ à corda de $\theta/2$:

Seja $D$ o ponto médio do arco $BC$ num círculo de diâmetro $AC = 120$. Construindo geometricamente a partir de propriedades do círculo e do triângulo isósceles, Ptolomeu demonstrou:

$$\text{corda}^2\!\left(\frac{\theta}{2}\right) = \frac{120 \cdot [120 - \text{corda}(180° - \theta)]}{2}$$

Em termos modernos, com $\text{corda}(\theta) = 120\sin(\theta/2)$:

$$\sin^2\!\left(\frac{\theta}{2}\right) = \frac{1 - \cos\theta}{2}$$

— a identidade do ângulo metade que qualquer estudante de trigonometria memoriza hoje.

---

### 18.3 Construção da Tabela Passo a Passo

Com as duas ferramentas — a fórmula da diferença e a fórmula do arco metade — Ptolomeu construiu sua tabela de forma sistemática:

**Passo 1 — Cordas conhecidas diretamente:**

| Arco | Corda | Origem |
|---|---|---|
| $60°$ | $60{,}000$ | Lado do hexágono regular inscrito = raio |
| $72°$ | $70{,}534$ | Lado do pentágono regular inscrito |
| $90°$ | $84{,}853$ | Lado do quadrado inscrito = $60\sqrt{2}$ |
| $120°$ | $103{,}923$ | Lado do triângulo equilátero inscrito = $60\sqrt{3}$ |

**Passo 2 — Corda de $36°$:**
Do pentágono regular (§4.4 e §11.5), a seção áurea dá:
$$\text{corda}(36°) = 60 \cdot \frac{\sqrt{5}-1}{2} \approx 37{,}083$$

**Passo 3 — Corda de $12°$:**
Pela fórmula da diferença com $\alpha = 72°$ e $\beta = 60°$:
$$\text{corda}(12°) = \frac{\text{corda}(72°) \cdot \text{corda}(120°) - \text{corda}(60°) \cdot \text{corda}(108°)}{120} \approx 12{,}533$$

**Passo 4 — Subdivisões por arco metade:**

$$\text{corda}(6°) \approx 6{,}270 \quad \text{corda}(3°) \approx 3{,}141 \quad \text{corda}(1°30') \approx 1{,}571 \quad \text{corda}(45') \approx 0{,}785$$

**Passo 5 — Corda de $1°$:**
$\text{corda}(1°)$ não pode ser obtida exatamente por combinação das cordas conhecidas (pois $1°$ não é divisor inteiro de $60°$ ou $72°$). Ptolomeu a obteve por **interpolação linear** entre $\text{corda}(1°30')$ e $\text{corda}(45')$:

$$\text{corda}(1°) \approx \frac{2}{3}\,\text{corda}(1°30') + \frac{1}{3}\,\text{corda}(45') = \frac{2}{3}(1{,}5708) + \frac{1}{3}(0{,}7854) \approx 1{,}0472$$

Usando $\text{corda}(\theta) = 120\sin(\theta/2)$, o valor exato é $120\sin(0{,}5°) = 1{,}04720\ldots$ ✓ — Ptolomeu acertou na quinta casa decimal.

**Passo 6 — Corda de $30'$:**
Por arco metade de $1°$:
$$\text{corda}(30') \approx 0{,}5236$$

**Extensão da tabela:** Com incrementos de $30'$ e a fórmula da adição, Ptolomeu construiu a tabela completa de $0°30'$ a $180°$ em passos de $30'$ — um total de 360 entradas. Cada entrada é acompanhada de uma **coluna de diferenças** que permite interpolação linear dentro de cada intervalo de $30'$.

**Exemplo de entrada:** A corda de $\text{arc} = 60°$:

```
Arco: 60°  0'    Corda: 60p  0'  0''    Diferença: 0p 31' 24''
```

A "diferença" é o incremento por $1'$ de arco — permite calcular, por interpolação, $\text{corda}(60°17')$, por exemplo.

**O valor implícito de $\pi$:**
Ptolomeu usou $\text{corda}(1°) \approx 1p2'50''$ em notação sexagesimal. Com 720 lados, o polígono inscrito tem perímetro $720 \times \text{corda}(0°30') \approx 720 \times 0{,}5236 = 377{,}0$. Dividindo pelo diâmetro $120$:

$$\pi \approx \frac{377}{120} \approx 3{,}14167$$

Valor correto até a quarta casa decimal — melhor que os $3\,\frac{10}{70}$ de Arquimedes ($\approx 3{,}1429$, §14.4).

---

### 18.4 O Sistema Astronômico do Almagesto

Com a trigonometria estabelecida nos primeiros livros, os restantes do Almagesto constroem o modelo completo dos movimentos celestes.

O sistema de Ptolomeu é geocêntrico — a Terra está (aproximadamente) no centro do universo — mas é muito mais sofisticado que o de Eudoxo (§10.5). Para cada planeta, Ptolomeu combina três elementos:

**Deferente:** Um círculo grande em torno do qual o centro do epiciclo se move. O centro do deferente não é exatamente a Terra — está deslocado ligeiramente (órbita *excêntrica*).

**Epiciclo:** Um círculo pequeno cujo centro se move ao longo do deferente, e sobre o qual o planeta se move. O epiciclo explica o movimento retrógrado: quando o planeta está na parte interior do epiciclo (mais próximo da Terra), move-se para trás em relação às estrelas. Apolônio já havia demonstrado a equivalência matemática entre esse sistema e o modelo excêntrico alternativo (§15.8) — Ptolomeu combina os dois.

**Equante:** A novidade radical de Ptolomeu. O centro do epiciclo não se move com velocidade angular uniforme em relação ao centro do deferente — mas em relação a um ponto especial chamado **equante**, simétrico ao da Terra em relação ao centro do deferente.

Geometricamente, se o centro do deferente é $C$, a Terra está em $E$ a uma distância $d$ de $C$, e o equante $Q$ está diametralmente oposto a $E$ em relação a $C$ (também a distância $d$). O centro do epiciclo move-se de forma que o ângulo $\angle EQC$ cresce uniformemente com o tempo.

**Por que o equante?** Sem ele, o sistema de epiciclos puros não reproduzia as variações de velocidade observadas dos planetas. Com ele, o Almagesto previa posições planetárias com precisão de arco-minuto — suficiente para todas as necessidades práticas de navegação, calendário e astrologia.

**O que Copérnico não suportava:** Copérnico, 1.400 anos depois, aceitou o geocentrismo por muitos anos — mas não conseguia aceitar o equante. Ele considerava que o equante violava o princípio de que movimentos celestes devem ser compostos de círculos com rotação *uniforme*. Em seus primeiros escritos (*Commentariolus*, 1514), ele propôs substituir o equante por mais epiciclos. A busca por um modelo sem equante foi uma das motivações originais do heliocentrismo copernicano — não o geocentrismo em si.

---

### 18.5 A Tabela de Cordas em Uso Real — Calculando a Posição de Júpiter

Para ilustrar como o Almagesto era usado na prática, considere o cálculo simplificado da longitude de Júpiter numa data dada.

O procedimento de Ptolomeu para Júpiter (resumido):

1. **Calcule a anomalia média** $\lambda$: quantos graus Júpiter percorreu no deferente desde o pericélio (ponto mais próximo da Terra), usando o período orbital de Júpiter (11,86 anos) e o tempo decorrido.

2. **Corrija para o equante**: a velocidade angular não é uniforme em relação ao centro, mas em relação ao equante. A correção $c_1(\lambda)$ é tabelada como função de $\lambda$ — e é calculada usando o Teorema de Ptolomeu e a tabela de cordas.

3. **Calcule a anomalia do epiciclo** $\alpha$: quantos graus Júpiter percorreu no epiciclo desde o auge (ponto mais distante da Terra no epiciclo).

4. **Corrija para a posição no epiciclo**: a contribuição do epiciclo à longitude vista da Terra depende de $\alpha$ e da distância ao equante. Novamente, calculada via tabela de cordas.

5. **Some todas as correções** à longitude média para obter a longitude verdadeira.

Cada etapa requer uma ou duas entradas na tabela de cordas e interpolação linear. Um astrônomo experiente do século XII conseguia fazer esse cálculo para todos os planetas visíveis em algumas horas de trabalho — com resultado preciso ao arco-minuto.

---

### 18.6 A Geografia — O Erro que Enviou Colombo ao Destino Errado

Além do Almagesto, Ptolomeu escreveu a *Geographia* — um atlas matemático do mundo conhecido em oito livros, com um catálogo de ~8.000 lugares com latitudes e longitudes estimadas.

A *Geographia* introduziu duas inovações duradouras:

**O sistema de coordenadas geográficas:** Latitudes medidas a partir do equador (como hoje), longitudes medidas a partir de um meridiano de referência escolhido (o meridiano das Ilhas Canárias, o ponto mais ocidental do mundo conhecido). O sistema que usamos hoje é diretamente descendente.

**Projeções cartográficas:** Ptolomeu descreveu dois métodos para projetar a superfície esférica da Terra num mapa plano. A **projeção cônica** (linhas de latitude projetadas como arcos de círculo) e a **projeção estereográfica** (projeção de um polo sobre um plano equatorial). Demonstrou que a projeção estereográfica é **conforme** — preserva os ângulos localmente, embora distorça as áreas.

**O erro fatídico — agora com os números reconciliados.** Já antecipamos esse episódio em §16.1 (Eratóstenes): Ptolomeu adotou para a circunferência da Terra o valor de **180.000 estádios** — de Posidônio, não uma medição própria — em vez do valor (ajustado) de **252.000 estádios** de Eratóstenes. Comparando diretamente em estádios, sem precisar converter para quilômetros (e assim evitando a ambiguidade sobre o comprimento exato do estádio que já discutimos):

$$\frac{252.000 - 180.000}{252.000} \approx 28{,}6\% \approx 29\%$$

O valor de Ptolomeu era cerca de 29% menor que o de Eratóstenes — o número que vimos antes converter para algo entre 15% e 17% menor que a circunferência *real*, dependendo da conversão do estádio adotada, já que o próprio valor de Eratóstenes tinha uma margem de erro em relação à realidade. O essencial, em qualquer caso, é a direção do erro: Ptolomeu encolheu a Terra.

Combinado com uma superestimativa da extensão leste-oeste do mundo conhecido (Ptolomeu atribuía ~180° de longitude ao continente euroasiático; o valor real é ~130°), a *Geographia* pintava um mundo onde a distância por mar de Portugal à China, seguindo para oeste, era de apenas ~120° de longitude — cerca de 10.000 km.

O valor real é ~230° de longitude, ou ~18.000 km — e havia o continente americano no meio, que Ptolomeu não sabia que existia.

Quando Colombo planejou sua viagem em 1492, usou os números de Ptolomeu. Seu plano era alcançar as Índias em ~3.000 milhas náuticas — uma viagem longa mas viável com os navios disponíveis. O valor real era ~12.000 milhas náuticas. Se Colombo soubesse disso, provavelmente não teria zarpado — e a América não teria sido "descoberta" naquele momento.

O erro de Ptolomeu, propagado por 1.400 anos, foi a premissa falsa que tornou a viagem de Colombo possível.

---

### 18.7 Óptica e Refração

Ptolomeu também escreveu uma *Óptica* — o único tratado antigo detalhado sobre o assunto, sobrevivendo parcialmente em tradução latina de uma tradução árabe.

Além da geometria dos espelhos planos, côncavos e convexos, Ptolomeu fez a primeira tentativa quantitativa de medir a **refração** — o desvio dos raios de luz ao passarem entre meios diferentes (ar para água, ar para vidro).

Ele mediu experimentalmente os ângulos de incidência e refração para vários ângulos e tabulou os resultados. Tentou ajustar uma lei matemática aos dados. Propôs que o ângulo de refração é proporcional ao ângulo de incidência — o que é errado.

A lei correta — $n_1 \sin\theta_1 = n_2 \sin\theta_2$ (Lei de Snell) — foi descoberta em 1621 por Willebrord Snell. Mas os dados experimentais de Ptolomeu estão surpreendentemente próximos dos valores corretos para ângulos pequenos (onde $\sin\theta \approx \theta$, tornando a lei de Ptolomeu uma boa aproximação). Ptolomeu tinha bons instrumentos e boa metodologia — faltou-lhe apenas a função trigonométrica correta para descrever os dados.

> **Conexão com o projeto:** A tabela de cordas de Ptolomeu é o ancestral direto das tabelas de senos e cossenos que os microcontroladores do rover armazenam em memória flash. O algoritmo de Ptolomeu — calcular valores novos a partir de valores conhecidos por fórmulas de adição e arco metade — é idêntico às rotinas **CORDIC** (COordinate Rotation DIgital Computer) usadas em FPGAs e processadores de sinais para calcular funções trigonométricas em hardware sem unidade de ponto flutuante. O sistema do equante — um ponto que não é o centro mas em relação ao qual o movimento é uniforme — é o equivalente histórico do **frame de referência não inercial** que os sistemas de navegação do rover usam para compensar a rotação de Marte durante a missão.

---

*Fontes desta parte: Katz, § 5.2 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 23 de N — Ptolomeu de Alexandria (completa)
> **Próxima parte:** Seção B — A Aritmética Grega e seus Limites (o apêndice original, agora integrado em seu ponto de encaixe correto)
