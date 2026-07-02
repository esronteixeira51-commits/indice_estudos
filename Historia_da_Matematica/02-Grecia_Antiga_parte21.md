## 16. Eratóstenes de Cirene — A Medida da Terra

**Eratóstenes de Cirene** (c. 276–194 a.C.) era o tipo de intelectual que os gregos alexandrinos admiravam e invejavam: extraordinariamente competente em tudo, mas não o melhor em nada. Seus rivais o chamavam de *Beta* — o segundo, o eterno segundo lugar. Ele era o segundo melhor astrônomo, o segundo melhor matemático, o segundo melhor poeta, o segundo melhor filósofo. O que seus rivais não perceberam é que ser o segundo melhor em cinco disciplinas simultaneamente é mais raro e mais valioso do que ser o melhor em uma.

Nascido em Cirene (hoje Líbia), estudou em Atenas e foi chamado a Alexandria por Ptolomeu III para ensinar o herdeiro real e dirigir a Biblioteca — o cargo intelectual mais prestigioso do mundo antigo. Foi para ele que Arquimedes enviou *O Método* (§14.9), com uma nota explicando que preferia comunicar seus resultados a alguém capaz de apreciá-los.

---

### 16.1 A Medição da Circunferência da Terra

A contribuição mais famosa de Eratóstenes é uma medição que combina observação astronômica simples com raciocínio geométrico elegante — e produziu um resultado correto com menos de 2% de erro, usando apenas uma vara e sua sombra.

**A observação:** No solstício de verão (21 de junho), ao meio-dia, o Sol brilhava diretamente para dentro de um poço fundo em **Siene** (atual Assuã, no sul do Egito) — ou seja, estava exatamente no zênite. No mesmo dia e hora, em **Alexandria** (ao norte de Siene, aproximadamente no mesmo meridiano), uma vara vertical projetava uma sombra. O ângulo entre a vara e a direção do Sol era $1/50$ de um círculo completo — ou seja, $360°/50 = 7°12'$.

**O argumento geométrico:**

```
         Sol (raios paralelos)
              ↓        ↓
    Siene ————●        ●———— Alexandria
              |        |
              |   θ    |
              O (centro da Terra)
```

Como os raios do Sol chegam paralelos à Terra (o Sol está a distância imensa), o ângulo $\theta$ entre as verticais de Siene e Alexandria *é o mesmo* que o ângulo entre os raios do Sol e a vara em Alexandria — por serem ângulos alternos internos entre paralelas cortadas por uma transversal (a mesma propriedade que vimos em I.29, §13.3).

Portanto $\theta = 1/50$ de $360°$, e a distância Siene–Alexandria é $1/50$ da circunferência total. Eratóstenes sabia que essa distância era aproximadamente **5.000 estádios** (medida por passo de camelo ou por bematistas — medidores profissionais de distância). Logo:

$$C = 50 \times 5.000 = 250.000 \text{ estádios}$$

**Um ajuste muito humano.** Eratóstenes parece ter, em algum momento, modificado seu próprio resultado de 250.000 para **252.000 estádios** — não porque tivesse refeito a medição, mas, ao que tudo indica, porque 252.000 dividido por 360 dá exatamente **700 estádios por grau**, um número redondo muito mais conveniente para uso prático em mapas e cálculos posteriores do que os 694,4 estádios por grau que o resultado original implicaria. É um lembrete de que mesmo a ciência mais rigorosa às vezes troca uma precisão de quinta casa decimal por um número que cabe melhor numa tabela.

**Qual é o valor moderno?** Um estádio grego equivalia a aproximadamente 157–185 metros (havia variações regionais, e ainda hoje os historiadores debatem qual seria o estádio exato usado por Eratóstenes). Com o estádio mais aceito atualmente (~185 m), o resultado original de 250.000 estádios dá:

$$C \approx 250.000 \times 185 \text{ m} = 46.250 \text{ km}$$

A circunferência real da Terra é 40.075 km — um erro de aproximadamente 15–16%, dependendo de qual dos dois resultados de Eratóstenes (250.000 ou 252.000 estádios) e qual conversão de estádio se usa. Com o estádio de 157 m, o resultado cai para dentro de 2% do valor real. O grau de acerto depende dessas escolhas — mas em qualquer interpretação razoável, o método é correto e o resultado é notável para uma medição do século III a.C.

**As fontes de erro:** Siene não está exatamente no Trópico de Câncer (está a $\sim 0°02'$ ao norte). Siene e Alexandria não estão exatamente no mesmo meridiano (Alexandria está $\sim 3°$ a oeste). A distância de 5.000 estádios era uma estimativa arredondada. E o ângulo de $1/50$ de círculo é provavelmente um arredondamento de uma medição que pode ter sido feita com precisão de $\pm 15'$. Todos esses erros se cancelaram parcialmente — com sorte ou com habilidade, ou com as duas coisas.

**Uma escolha posterior, com consequências distantes.** Vale registrar o que aconteceu com esse número depois. Quando **Ptolomeu** (§18), quase quatro séculos mais tarde, compilou sua própria *Geografia*, ele claramente conhecia o valor de Eratóstenes — mas optou por usar uma estimativa bem menor: 180.000 estádios, equivalente a apenas 500 estádios por grau, cerca de 17% *menor* que a circunferência real (o erro oposto ao de Eratóstenes). Não sabemos com certeza por que Ptolomeu preferiu o valor menor. O que sabemos é que sua *Geografia* permaneceu a referência padrão do mundo ocidental por mais de mil anos — e alguns historiadores apontam que essa subestimativa da circunferência terrestre, propagada através de Ptolomeu, pode ter contribuído para o erro de cálculo de Colombo ao planejar sua viagem para o Oriente em 1492: uma Terra menor implica uma distância menor entre a Europa e a Ásia navegando para o oeste — exatamente o tipo de erro que levaria Colombo a esperar encontrar as Índias onde, na verdade, encontrou um continente inteiramente desconhecido aos europeus.

**Por que isso era possível:** Eratóstenes sabia que a Terra é esférica — isso já era consenso entre os filósofos gregos desde Pitágoras ou antes. O que ele fez foi *medir* a esfera. A ideia de que Colombo precisou "provar" que a Terra era redonda é um mito medieval: nenhum grego letrado acreditava que a Terra fosse plana. A questão, desde Eratóstenes, era sempre: quão grande ela é? — e é precisamente a resposta a essa pergunta, mal herdada via Ptolomeu, que mil setecentos anos depois ajudaria a enganar Colombo.

---

### 16.2 O Crivo de Eratóstenes

A segunda contribuição matemática famosa de Eratóstenes é o **crivo** — um algoritmo sistemático para encontrar todos os números primos abaixo de um limite $N$.

**O algoritmo:**

1. Escreva todos os inteiros de 2 a $N$.
2. Marque 2 como primo. Risque todos os múltiplos de 2 (4, 6, 8, …).
3. O próximo não riscado é 3 — marque como primo. Risque todos os múltiplos de 3 (6, 9, 12, …). Os que já foram riscados não importam.
4. O próximo não riscado é 5 — marque como primo. Risque múltiplos de 5.
5. Continue até $\sqrt{N}$. Todos os números restantes são primos.

**Por que parar em $\sqrt{N}$?** Se $N$ tem um fator composto $p > \sqrt{N}$, o cofator $q = N/p$ satisfaz $q < \sqrt{N}$ — e $N$ já teria sido riscado quando processamos $q$. Logo, nenhum número $\leq N$ pode ser composto sem ter um fator $\leq \sqrt{N}$.

**Exemplo para $N = 30$:**

```
2  3  4  5  6  7  8  9  10
11 12 13 14 15 16 17 18 19 20
21 22 23 24 25 26 27 28 29 30
```

Riscar múltiplos de 2: eliminam 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30.
Riscar múltiplos de 3: eliminam 9, 15, 21, 27.
Riscar múltiplos de 5: elimina 25 (15 já foi).

Como $\sqrt{30} < 6$, paramos. Os primos até 30 são:

$$2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$

**A complexidade do crivo:** O crivo de Eratóstenes tem complexidade $O(N \log \log N)$ — quase linear. Para $N = 10^9$, encontra todos os primos em segundos num computador moderno. Versões otimizadas (crivo segmentado, crivo de Atkin) são usadas hoje para calcular primos em criptografia de chave pública.

**Densidade dos primos:** O crivo revela empiricamente que os primos ficam progressivamente mais raros conforme $N$ cresce — mas nunca acabam (pela demonstração de Euclides, §13.7). A taxa exata de rarefação foi descoberta independentemente por Gauss e Legendre no século XIX: a quantidade de primos menores que $N$ é aproximadamente $N / \ln N$. Essa afirmação, o **Teorema dos Números Primos**, foi demonstrada rigorosamente apenas em 1896, por Hadamard e de la Vallée Poussin.

---

### 16.3 Outras Contribuições

Eratóstenes também calculou a distância e o tamanho do Sol e da Lua, a inclinação da eclíptica (o ângulo entre o plano da órbita da Terra e o equador celeste — ele obteve $23°51'20''$, o valor moderno é $23°26'$), e escreveu um tratado sobre médias geométricas hoje perdido.

Em uma carta a Ptolomeu III, Eratóstenes descreveu um instrumento mecânico chamado *mesolábio* para encontrar duas médias proporcionais entre dois segmentos — a solução do Problema de Delos (§6.4). O instrumento usava três réguas deslizantes que se interceptam; ajustando-as, encontram-se as médias por interpolação mecânica. Platão teria ficado horrorizado (lembre-se de sua reação à solução mecânica de Menaecmo, §11.3) — mas o método funcionava.

Eratóstenes também escreveu *Geographica*, o primeiro tratado sistemático de geografia matemática, usando latitudes e longitudes para mapear o mundo conhecido. A grade de coordenadas geográficas que usamos hoje — incluindo o GPS — descende diretamente desse sistema.

Conta a tradição que Eratóstenes perdeu a visão na velhice e, incapaz de ler ou observar o céu, se deixou morrer de fome voluntariamente. Tinha aproximadamente 82 anos.

> **Conexão com o projeto:** O método de Eratóstenes — inferir a geometria global a partir de medições locais — é o princípio da **geodésia**, a ciência que determina a forma e o tamanho de um planeta. Antes de pousar em Marte, é necessário conhecer seu raio, achatamento e campo gravitacional com precisão milimétrica. As sondas Mars Global Surveyor e MAVEN mediram esses parâmetros usando exatamente o mesmo princípio: diferenças de ângulo e distância entre pontos conhecidos do planeta. Eratóstenes fez isso com uma vara e uma sombra. Fazemos com rádio Doppler e acelerômetros — mas o raciocínio é o mesmo. E a lição sobre Ptolomeu vale também para engenharia de missão: um parâmetro físico mal herdado de uma fonte antiga, sem verificação independente, pode propagar erro por gerações inteiras de cálculo — exatamente por isso que parâmetros orbitais críticos de Marte são reverificados por múltiplas missões independentes antes de serem usados em planejamento de pouso.

---

*Fontes desta parte: Katz, § 5.3 · Boyer, cap. 7 · Struik, cap. III*

---
> **Status:** Parte 21 de N — Eratóstenes de Cirene (completa)
> **Próxima parte:** Aristarco e Hiparco — Trigonometria a Serviço do Cosmos
