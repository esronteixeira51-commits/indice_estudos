## 7. Hípias de Elis — A Primeira Curva Nova

**Hípias de Elis** (c. 460–400 a.C.) era sofista — um professor profissional que cobrava pelo ensino, o que os pitagóricos consideravam escandaloso. Platão o retrata nos diálogos com pouca simpatia: vaidoso, enciclopédico e superficial. Mas independentemente do caráter, a tradição atribui a Hípias algo que nenhum matemático havia feito antes: a introdução na geometria de uma **curva completamente nova**, que não era reta nem círculo.

Vale uma nota de cautela, na mesma linha da que já fizemos sobre Tales (§3.2): a atribuição da curva a Hípias é a versão tradicional e mais aceita, mas as fontes antigas sobre sua origem exata são esparsas — Katz, ao descrevê-la, refere-se a ela com prudência como "uma curva provavelmente introduzida" no século V a.C., sem cravar uma autoria absoluta. O que é seguro é que a curva existia e circulava entre os geômetras gregos décadas antes de Platão, e que a tradição — talvez já no século IV a.C. — a associou ao nome de Hípias.

A curva é hoje chamada **quadratriz de Hípias** — e sua definição é puramente cinemática: é o lugar geométrico de um ponto gerado por dois movimentos simultâneos e uniformes.

### 7.1 Definição da Quadratriz

Considere o quadrado $ABCD$ com lado de comprimento $a$. Dois movimentos ocorrem simultaneamente, ambos com a mesma duração $T$:

- O lado $AB$ desce uniformemente até coincidir com $DC$ (movimento de translação).
- O raio $DA$ gira uniformemente no sentido horário até coincidir com $DC$ (movimento de rotação).

Em qualquer instante $t \in [0, T]$:
- O lado em translação ocupa a posição $A'B'$, a uma altura $y = a(1 - t/T)$ de $DC$.
- O raio em rotação ocupa a posição $DA''$, formando um ângulo $\theta = \frac{\pi}{2}(1 - t/T)$ com $DC$.

O ponto $P$ é a interseção de $A'B'$ com $DA''$ naquele instante. O lugar geométrico de $P$ para todo $t$ é a quadratriz.

Em coordenadas cartesianas com origem em $D$ e $DC$ sobre o eixo $x$, a equação é:

$$y = x \tan\!\left(\frac{\pi y}{2a}\right)$$

ou equivalentemente, em coordenadas polares com origem em $D$:

$$r = \frac{2a\theta}{\pi \sin\theta}$$

A curva parte do ponto $A$ (quando $t = 0$, $\theta = \pi/2$) e se aproxima do ponto $Q = (2a/\pi, 0)$ quando $t \to T$ — mas nunca chega ali pelo processo de construção, pois o movimento se encerra quando ambos os segmentos coincidem com $DC$.

### 7.2 Trissecção do Ângulo pela Quadratriz

O uso imediato que Hípias deu à curva foi a **trissecção de ângulos** — e pela quadratriz, a trissecção de qualquer ângulo é trivial.

Suponha que queremos trissectar o ângulo $\angle PDC$. O ponto $P$ está sobre a quadratriz. Pelo processo de construção, a altura $y$ do ponto $P$ é proporcional ao ângulo $\theta = \angle PDA$. Logo:

1. Encontre a ordenada $y_P$ do ponto $P$.
2. Divida o segmento $B'C$ em três partes iguais — operação trivial com régua e compasso — obtendo pontos a alturas $y_P/3$ e $2y_P/3$.
3. As retas horizontais nessas alturas cortam a quadratriz em pontos $V$ e $W$.
4. As retas $DV$ e $DW$ trissectam $\angle PDC$.

O raciocínio é direto: como $y \propto \theta$ ao longo da quadratriz (ambos variam linearmente com $t$), dividir $y$ em três partes iguais divide $\theta$ em três partes iguais. A quadratriz converte o problema angular num problema linear — e divisão de segmentos em partes iguais é elementar.

Generalizando: qualquer subdivisão de um ângulo em $n$ partes iguais reduz-se a dividir um segmento em $n$ partes iguais. A quadratriz é essencialmente um "retificador angular" — transforma ângulos em comprimentos.

### 7.3 Quadratura do Círculo pela Quadratriz

**Dinóstrato** (c. 350 a.C.), irmão de Menaecmo, observou que a quadratriz pode ser usada também para quadrar o círculo — o que lhe valeu o nome alternativo *quadratriz* (de *quadratura*).

O ponto crucial é o limite da curva quando $\theta \to 0$: o ponto $Q$ onde a quadratriz encontraria o eixo $x$ (se o processo pudesse ser completado). Dinóstrato demonstrou — por uma elegante dupla *reductio ad absurdum* tipicamente grega — que:

$$DQ = \frac{2a}{\pi}$$

Isto é, o segmento $DQ$ é o diâmetro $DC = a$ dividido por $\pi/2$. Em outras palavras, conhecer $Q$ equivale a conhecer $\pi$.

Com $DQ$ em mãos, a quadratura do círculo se torna direta:

1. O círculo de raio $a$ tem circunferência $2\pi a$.
2. Pela proporção $DC/DQ = \pi/2$, construímos um segmento de comprimento $2\pi a$ facilmente.
3. Um triângulo de base $2\pi a$ e altura $a$ tem área $\pi a^2$ — igual à do círculo.
4. Converter o triângulo em quadrado de mesma área é uma construção clássica com régua e compasso.

O círculo está "quadrado" — *se* pudermos construir o ponto $Q$.

E aqui está o problema: $Q$ é um ponto limite, não atingido pelo processo cinemático de construção da quadratriz. Dinóstrato *assumiu* que $Q$ existe e que pode ser usado na construção — mas não havia justificativa rigorosa para isso. Os gregos eram conscientes da questão: Espeusipo e Proclo criticaram a construção precisamente por esse motivo.

A crítica é matematicamente correta: construir $Q$ com régua e compasso equivale a construir $\pi$ algebricamente, o que é impossível (pois $\pi$ é transcendente). Mas a *intuição* de Dinóstrato estava certa — a quadratriz *conecta* ângulos a comprimentos de arco, e essa conexão *é* a chave para $\pi$.

**A curva sobrevive a seu próprio criador.** O mais notável sobre a quadratriz é sua longevidade. Mais de um século depois de Dinóstrato — já na era de Arquimedes, em pleno século III a.C. — o matemático **Nicômedes** (final do século III a.C.) voltou à mesma curva, refinando e detalhando a aplicação à quadratura do círculo de forma mais explícita do que seus predecessores. Uma única curva, definida por um sofista do século V a.C. para resolver um problema angular, atravessou duzentos anos de matemática grega e foi reaproveitada por gerações sucessivas de geômetras para um propósito totalmente diferente do original — a medida da circunferência. É um exemplo claro de como a matemática grega funcionava por acumulação: poucos resultados eram descartados; a maioria era retomada, reinterpretada e estendida por quem vinha depois.

### 7.4 Significado da Quadratriz

A quadratriz é importante por três razões que vão além do problema imediato:

**É a primeira curva definida cinematicamente.** Antes de Hípias, as curvas geométricas eram seções de sólidos (como as cônicas de Menaecmo) ou lugares geométricos definidos por condições estáticas. A quadratriz é gerada por *movimento* — dois movimentos simultâneos e proporcionais. Esse modo de pensar curvas como trajetórias de pontos em movimento é o precursor direto das coordenadas paramétricas e do cálculo.

**Demonstra os limites da régua e do compasso.** A construção da quadratriz exige movimento contínuo e uniforme — algo que régua e compasso não podem realizar. Isso torna explícito, pela primeira vez, que há problemas geométricos genuínos que *escapam* ao universo das construções elementares.

**Introduz a ideia de limite.** O ponto $Q$ só existe como limite de um processo infinito. Dinóstrato o usou sem justificá-lo rigorosamente — e os gregos sentiram o desconforto. Essa tensão entre o processo infinito e seu resultado finito é exatamente o que o método de exaustão de Eudoxo tentará resolver, e o que o cálculo de Newton e Leibniz resolverá definitivamente dois mil anos depois.

> **Conexão com o projeto:** A quadratriz converte medição angular em medição linear — o princípio fundamental de qualquer encoder rotativo. Os encoders usados nos atuadores do rover fazem exatamente isso: traduzem rotação em pulsos contáveis, linearizando o espaço angular. Hípias não tinha encoders, mas inventou o princípio. E a forma como Nicômedes reaproveitou, séculos depois, uma curva criada para outro fim é o mesmo princípio de reuso de componentes em engenharia: um sensor projetado para medir ângulo de junta pode, com a interpretação matemática certa, servir também para medir velocidade angular ou posição linear — a curva (ou o sensor) é a mesma; a aplicação é que se descobre depois.

---

*Fontes desta parte: Boyer, cap. 4 · Katz, § 4.3 (referência cruzada sobre Nicômedes) · Struik, cap. III*

---
> **Status:** Parte 4 de N — Hípias de Elis (completa)
> **Próxima parte:** Demócrito de Abdera — o átomo, o volume da pirâmide e o princípio de Cavalieri antecipado em dois mil anos
