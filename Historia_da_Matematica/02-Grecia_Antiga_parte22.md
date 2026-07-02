## 17. Aristarco e Hiparco — Trigonometria a Serviço do Cosmos

A astronomia grega não era apenas contemplação filosófica do céu — era medição. Os astrônomos do período helenístico queriam saber *quanto* o Sol estava distante, *quão grande* era a Lua, *quando* exatamente ocorreria um eclipse. Para isso, precisavam de uma matemática de ângulos e distâncias que os *Elementos* de Euclides não forneciam diretamente. Essa necessidade gerou a trigonometria.

---

### 17.1 Aristarco de Samos — O Copérnico Grego

**Aristarco de Samos** (c. 310–230 a.C.) foi o primeiro a propor que a Terra gira em torno do Sol — não o contrário. Arquimedes o menciona no *Contador de Areia* (§14.3): Aristarco afirmava que o universo era enormemente maior do que se pensava, porque a ausência de paralaxe estelar (as estrelas não parecem mudar de posição conforme a Terra se move) só podia ser explicada se as estrelas estivessem a distâncias imensas.

O modelo heliocêntrico de Aristarco foi rejeitado pela maioria dos astrônomos gregos — não por dogmatismo, mas por razões físicas aparentemente sólidas: se a Terra se move, por que os objetos lançados verticalmente não caem para trás? Por que não sentimos o vento do movimento? Por que não há paralaxe estelar observável? Aristarco respondeu corretamente que a paralaxe existe mas é imperceptível pela enorme distância das estrelas — mas essa resposta parecia ad hoc, e a maioria preferiu o geocentrismo.

O único tratado sobrevivente de Aristarco é *Sobre os Tamanhos e Distâncias do Sol e da Lua* — escrito antes de sua proposta heliocêntrica, e portanto ainda geocêntrico. É o primeiro texto que usa raciocínio trigonométrico para medir distâncias astronômicas.

---

### 17.2 Medindo a Distância ao Sol — O Primeiro Cálculo Trigonométrico

O método de Aristarco é engenhoso em sua simplicidade e devastador em sua dependência de uma medição precisa.

**A situação geométrica:** Quando a Lua está exatamente na **quadratura** — meio cheia, nem crescente nem minguante —, o ângulo $\angle \text{Sol-Lua-Terra} = 90°$ (a Lua iluminada em exatamente metade significa que o Sol está perpendicular à linha Terra-Lua). Nesse momento, Terra ($T$), Lua ($L$) e Sol ($S$) formam um triângulo retângulo com o ângulo reto em $L$.

O ângulo $\angle LTS$ (o ângulo Sol-Terra visto da Terra, com a Lua no quadrante) pode ser medido diretamente por observação. Se esse ângulo é $\alpha$, então:

$$\frac{TL}{TS} = \cos\alpha$$

Aristarco mediu $\alpha \approx 87°$ — o que dá $\cos 87° \approx 0{,}052$, implicando que o Sol está aproximadamente **19 vezes** mais longe que a Lua.

**O valor correto:** O ângulo real é $\alpha \approx 89°50'$ — apenas $10'$ menor que $90°$. Isso dá $\cos 89°50' \approx 0{,}0029$, implicando que o Sol está **340 vezes** mais longe que a Lua (o valor moderno é $\approx 389$).

A diferença entre $87°$ e $89°50'$ parece pequena — menos de $3°$ — mas porque o cosseno varia muito rapidamente próximo de $90°$, esse erro de $3°$ na medição produz um erro de fator 18 no resultado. A medição dos $87°$ com instrumentos primitivos era simples; mas discriminar $87°$ de $89°50'$ exigia uma precisão que os instrumentos de Aristarco não tinham.

**Por que o método é correto apesar do resultado errado:** A geometria é impecável. O erro é experimental — não conceitual. Aristarco inventou um método válido para medir distâncias astronômicas usando apenas ângulos e trigonometria. O método ainda é usado hoje (com instrumentos modernos que medem $89°50'$ com facilidade).

---

### 17.3 Tamanhos Relativos de Sol, Terra e Lua

Do ângulo $\alpha$ e da observação de eclipses lunares, Aristarco extraiu uma série de resultados sobre tamanhos relativos.

**Durante um eclipse lunar total**, a sombra da Terra tem largura angular de $\approx 2$ diâmetros lunares na distância da Lua. Isso significa:

$$R_T - R_L \approx \frac{R_T d_L}{d_S} \cdot 2 \approx \frac{2R_T}{19}$$

onde $d_L$ e $d_S$ são as distâncias da Lua e do Sol. Combinando com o fato de que Sol e Lua têm quase o mesmo tamanho aparente visto da Terra ($\approx 0{,}5°$, o que significa $R_L/d_L \approx R_S/d_S$), Aristarco concluiu que:

$$\frac{R_S}{R_T} \approx 6{,}3 \quad \text{a } 7{,}2$$

O Sol tem raio entre 6 e 7 vezes o raio da Terra. O valor moderno é $\approx 109$. Novamente, o método é correto; o dado de entrada ($d_S/d_L \approx 19$) é que estava errado.

**Consequência intelectual importante:** Aristarco calculou que o Sol tem volume $\approx 300$ vezes maior que a Terra. Isso foi provavelmente o que o levou ao heliocentrismo — parecia absurdo que um objeto 300 vezes maior girasse em torno de um menor. É um argumento físico, não matemático. E é correto.

---

### 17.4 O Método das Desigualdades de Aristarco

Aristarco não tinha tabelas trigonométricas. Para calcular $\cos 87°$, usou um teorema geométrico que hoje escrevemos como:

$$\frac{\sin\alpha}{\sin\beta} < \frac{\alpha}{\beta} < \frac{\tan\alpha}{\tan\beta} \quad \text{para } 0 < \beta < \alpha < 90°$$

**Demonstração geométrica (o caso especial):** Num círculo de raio $r$, considere dois arcos $\alpha$ e $\beta$ ($\alpha > \beta$). A corda subtendida pelo arco maior é mais do que proporcionalmente maior que a corda do arco menor — mas menos do que proporcionalmente às tangentes. Geometricamente:

$$\text{corda}(\alpha) : \text{corda}(\beta) < \alpha : \beta$$

Isso é porque o arco "estica" menos do que linearmente quando se aumenta o ângulo perto de $90°$ (a corda de $180°$ é o diâmetro, mas o arco de $180°$ é $\pi r > 2r$).

Usando essas desigualdades com $\alpha = 87°$ e valores de referência, Aristarco obteve:

$$\frac{1}{20} < \frac{TL}{TS} < \frac{1}{18}$$

Ou seja, o Sol está entre 18 e 20 vezes mais longe que a Lua. O resultado correto é ~389 — mas o método das desigualdades funcionou dentro das limitações do dado medido.

---

### 17.5 Hiparco de Niceia — O Pai da Trigonometria

**Hiparco de Niceia** (c. 190–120 a.C.) trabalhou principalmente em Rodes e é unanimemente considerado o maior astrônomo grego — e o criador da trigonometria como disciplina sistemática.

Suas obras originais quase todas se perderam. Conhecemos seus trabalhos principalmente através de Ptolomeu, que os usou extensivamente no *Almagesto* (§18). O que sobreviveu é um único comentário sobre um poema astronômico — obra menor que não dá ideia da profundidade de suas contribuições.

**Contribuições astronômicas de Hiparco:**
- Catálogo de ~850 estrelas com posições e magnitudes.
- Valores melhorados do mês sinódico lunar (29 dias, 12 horas, 44 minutos, 3 segundos — o valor moderno é 29 dias, 12 horas, 44 minutos, 2,9 segundos).
- Determinação da precessão dos equinócios — a lenta rotação do eixo terrestre com período de ~26.000 anos, que faz as constelações "derivar" ao longo dos séculos.
- Teoria do movimento da Lua com sistema de epiciclo + excêntrico — usando a equivalência que Apolônio havia demonstrado entre os dois modelos (§15.8).
- Dois sistemas de coordenadas para mapear o céu: o **eclíptico** (longitude $\lambda$ e latitude $\beta$ medidas a partir do plano da órbita da Terra) e o **equatorial** (ascensão reta $\alpha$ e declinação $\delta$, medidas a partir do equador celeste) — Hiparco preferia o segundo para seu catálogo de estrelas. Converter entre os dois sistemas exige **trigonometria esférica**, e é exatamente essa exigência prática que tornou indispensável o desenvolvimento de uma trigonometria plana sistemática primeiro.

**Contribuição matemática central:** A primeira tabela de cordas da história.

---

### 17.6 A Tabela de Cordas de Hiparco

Antes de Hiparco, a relação entre ângulos e distâncias era tratada caso a caso, com desigualdades como as de Aristarco. Hiparco percebeu que seria imensamente mais útil ter uma tabela que associasse cada ângulo ao comprimento da corda que ele subtende num círculo de raio fixo.

**A relação entre cordas e senos modernos:**

Para um círculo de raio $R$, a corda que subtende um arco de $\theta$ graus tem comprimento:

$$\text{corda}(\theta) = 2R \sin\left(\frac{\theta}{2}\right)$$

Portanto, a tabela de cordas de Hiparco é essencialmente uma tabela de senos — mas para ângulos metade dos tabelados, e multiplicada por $2R$ em vez de $1$.

**A escolha do raio — mais sutil do que parece.** Como os ângulos eram medidos em graus e minutos, Hiparco decidiu usar a mesma unidade para o raio do círculo. Sabendo que a circunferência vale $2\pi R$, e usando para $\pi$ a aproximação sexagesimal $3;8,30$ (ou seja, $3 + 8/60 + 30/3600 \approx 3{,}1417$ — próxima da média entre os dois limites que Arquimedes havia calculado, §14.4), Hiparco calculou:

$$R = \frac{360 \times 60}{2\pi} \approx \frac{21.600}{6{,}2833} \approx 3438 \text{ (em minutos de arco)}$$

A escolha não é arbitrária nem motivada por conveniência sexagesimal simples — é deliberadamente projetada para que a medida de um ângulo, definida como o comprimento cortado na circunferência dividido pelo raio, coincida exatamente com sua medida em **radianos**. É uma normalização notavelmente moderna para um astrônomo do século II a.C.

**Cordas básicas que Hiparco calculava, com esse raio:**

A corda de $60°$ é igual ao raio: $\text{corda}(60°) = R = 3438'$. (Pois o triângulo equilátero inscrito tem lados iguais ao raio.)

A corda de $90°$ é o lado do quadrado inscrito: $\text{corda}(90°) = R\sqrt{2} \approx 4862'$.

A corda de $36°$ vem do pentágono regular: $\text{corda}(36°) = R(\sqrt{5}-1)/2 \approx 2125'$ (está ligada à seção áurea, §4.4 e §11.5!).

A corda do suplemento: $\text{corda}(180°-\theta) = \sqrt{(2R)^2 - \text{corda}(\theta)^2}$ — pelo teorema de Pitágoras, pois corda e corda-suplemento são os dois catetos de um triângulo retângulo inscrito no diâmetro.

**A fórmula de subtração de arcos:** Para construir a tabela incrementalmente, Hiparco precisava calcular a corda da diferença de dois arcos a partir das cordas individuais. Em linguagem moderna:

$$\sin(\alpha - \beta) = \sin\alpha\cos\beta - \cos\alpha\sin\beta$$

Em termos de cordas:

$$\text{corda}(\alpha - \beta) = \frac{\text{corda}(\alpha) \cdot \text{corda}(180°-\beta) - \text{corda}(\beta) \cdot \text{corda}(180°-\alpha)}{2R}$$

Partindo de $\text{corda}(60°) = 3438'$ e $\text{corda}(36°) \approx 2125'$, Hiparco calculava $\text{corda}(60°-36°) = \text{corda}(24°)$, depois $\text{corda}(24°/2) = \text{corda}(12°)$ (pela fórmula do arco metade), depois $\text{corda}(6°)$, $\text{corda}(3°)$, $\text{corda}(1°30')$, $\text{corda}(45')$... e por interpolação, $\text{corda}(1°)$.

**Uma nota para mais adiante.** Vale registrar, para quando chegarmos a Ptolomeu (§18): o astrônomo alexandrino herdaria o método de Hiparco quase intacto, mas adotaria uma convenção de raio diferente e mais simples — $R = 60$, aproveitando diretamente a divisibilidade do sistema sexagesimal, sem a sutileza adicional do radiano que Hiparco havia embutido em sua escolha de $3438$. As duas escolhas de raio coexistem na literatura histórica sobre trigonometria grega, e é fácil confundi-las — mas pertencem a dois astrônomos diferentes, com motivações diferentes, e a tabelas diferentes, com mais de duzentos anos de distância entre elas.

**A extensão da tabela:** Segundo Teon de Alexandria, Hiparco compilou uma tabela de cordas em 12 livros — provavelmente cobrindo ângulos de $7{,}5'$ em $7{,}5'$ (um oitavo de grau) de $0°$ a $180°$. Isso daria 1.440 entradas. A tabela se perdeu — sabemos de sua existência e de seu método apenas pelas referências posteriores de Téon e Ptolomeu.

---

### 17.7 A Precessão dos Equinócios — Medindo o Tempo Profundo

A maior descoberta observacional de Hiparco foi a **precessão dos equinócios** — um fenômeno que opera numa escala de tempo muito maior que uma vida humana.

O eixo de rotação da Terra não é fixo no espaço: ele precessa lentamente como um pião que está perdendo velocidade, descrevendo um cone em torno da normal ao plano da órbita com período de $\approx 25.772$ anos. Isso significa que:

- O ponto vernal (equinócio de primavera) se move $\approx 50''$ por ano ao longo da eclíptica.
- As estrelas que estão "no zênite" mudam ao longo de milênios. Thuban era a estrela polar há 4.000 anos (quando os egípcios construíam as pirâmides). Polaris é a estrela polar hoje. Vega será a estrela polar em $\approx 14.000$ anos.
- As constelações do zodíaco associadas a cada estação mudaram desde a Antiguidade. "Aquário" (o Aquário astronômico) ainda não está alinhado com o equinócio de primavera — o "Age of Aquarius" dos anos 1960 estava astronomicamente errado por alguns séculos.

**Como Hiparco descobriu:** Comparou a posição da estrela Espiga (Virgo) em relação ao ponto vernal com medições 150 anos anteriores feitas por Timócaris. A posição havia mudado $\approx 2°$ — correspondendo a $\approx 50''$ por ano. Hiparco estimou o período em $\geq 36.000$ anos (conservador, mas na ordem de grandeza correta).

**A implicação para a astronomia:** Tabelas estelares perdem precisão ao longo do tempo porque as estrelas "derivam" em relação ao equinócio. Qualquer sistema de navegação celeste — seja um astrônomo grego, seja um sistema inercial moderno calibrado por estrelas — precisa corrigir para a precessão.

> **Conexão com o projeto:** O método de Aristarco — inferir distâncias a partir de ângulos medidos — é o princípio da **telemetria de radar**: mede-se o ângulo de elevação e o tempo de retorno do sinal para calcular distância e altitude. Os sistemas de aterrissagem de rovers usam radar Doppler e altímetro de radar que implementam exatamente essa geometria. A precessão descoberta por Hiparco é relevante para qualquer missão de longa duração: os catálogos estelares usados para navegação celeste precisam ser corrigidos para a época da missão, não para a época em que o catálogo foi compilado. E a escolha de Hiparco de um raio que faz a corda coincidir com o radiano é, estruturalmente, o mesmo problema que escolher unidades internamente consistentes num sistema de controle: a JPL perdeu a sonda Mars Climate Orbiter em 1999 porque um módulo de software usava unidades imperiais (libras-força) e outro usava unidades métricas (newtons) — exatamente o tipo de inconsistência de convenção que Hiparco evitou com seu raio de 3438.

---

*Fontes desta parte: Katz, § 5.1 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 22 de N — Aristarco e Hiparco (completa)
> **Próxima parte:** Ptolomeu de Alexandria — a Síntese Matemática do Cosmos
