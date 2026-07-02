### 14.8 Sobre Conoides e Esferoides — Proto-Integração

Em *Sobre Conoides e Esferoides*, Arquimedes calcula volumes de sólidos gerados pela rotação de seções cônicas:
- **Paraboloide de revolução** (rotação de uma parábola): $V = \frac{1}{2} \pi r^2 h$ (metade do cilindro circunscrito).
- **Elipsoide de revolução** (rotação de uma elipse).
- **Hiperboloide de revolução**.

O método é descrito explicitamente por Arquimedes para o paraboloide e é o mais próximo que os gregos chegaram da integração formal:

Divida o eixo de altura $h$ em $n$ partes iguais de largura $h/n$. Sobre cada fatia, construa cilindros inscritos e circunscritos. A soma dos cilindros inscritos é:

$$\sum_{k=1}^{n-1} \pi \cdot \frac{a^2 k}{n} \cdot \frac{h}{n} = \frac{\pi a^2 h}{n^2} \sum_{k=1}^{n-1} k = \frac{\pi a^2 h}{n^2} \cdot \frac{(n-1)n}{2} = \frac{\pi a^2 h}{2}\left(1 - \frac{1}{n}\right)$$

A soma dos circunscritos é similar, com $+1/n$ em vez de $-1/n$. Quando $n \to \infty$, ambas convergem para $\frac{\pi a^2 h}{2}$. Arquimedes mostra que o volume do paraboloide é espremido entre as duas somas — e, pelo método de exaustão, é exatamente $\frac{\pi a^2 h}{2} = \frac{1}{2}V_{\text{cilindro}}$.

Isso é uma **soma de Riemann** antes de Riemann — com a diferença de que Arquimedes não toma o limite, mas usa a dupla *reductio* para espremer o valor entre dois extremos.

Entre os resultados adicionais deste tratado, Arquimedes também demonstra que o volume de um segmento de paraboloide de revolução é $\frac{3}{2}$ do volume do cone com a mesma base e o mesmo eixo — um companheiro direto da relação $\frac{4}{3}$ que vimos para a área do segmento parabólico plano (§14.6): a mesma família de curvas gerando relações de proporção igualmente elegantes, uma em área, outra em volume.

---

### 14.9 O Método — A Redescoberta do Século XX

Em 1906, o filólogo dinamarquês Johan Ludwig Heiberg foi a Constantinopla investigar rumores de um palimpsesto matemático numa biblioteca. Um palimpsesto é um pergaminho reutilizado — o texto original foi apagado e sobrescrito com um novo texto. O que Heiberg encontrou foi um livro de orações cristãs do século XIII — e sob o texto cristão, restos de um manuscrito matemático grego do século X.

Com paciência extraordinária, Heiberg leu o texto original: era *O Método* de Arquimedes, perdido desde o início da era cristã e o único exemplar existente. A leitura foi completada no século XXI usando imageamento espectral de alta resolução e fluorescência de raios-X no Stanford Linear Accelerator Center — tecnologia do século XXI recuperando matemática do século III a.C.

*O Método* é único na obra de Arquimedes porque **revela como ele descobria** seus resultados — não apenas como os demonstrava. Os outros tratados são obras finalizadas, com demonstrações rigorosas mas sem rastros da análise preliminar. *O Método* é o rascunho.

O método de Arquimedes usava a **lei da alavanca como ferramenta heurística**:

**Exemplo — área do segmento parabólico (Proposição 1):**

Considere o segmento parabólico $ABC$ e o triângulo $AFC$ onde $FC$ é tangente à parábola em $C$. Arquimedes "pensou" em cada figura como formada pela totalidade de suas fatias verticais (segmentos paralelos ao eixo).

Para uma fatia típica $OP$ do segmento parabólico e $OM$ do triângulo, a propriedade da parábola garante que:

$$OP : OM = HK : HO$$

onde $H$ é o ponto de apoio da alavanca e $K$ é o ponto médio de $HC$. Isso significa que a fatia $OP$, colocada na extremidade $H$ da alavanca, equilibra a fatia $OM$ na sua posição atual.

"Pesando" todas as fatias assim, o segmento parabólico todo colocado em $H$ equilibra o triângulo $AFC$ no seu centro de gravidade, que está a $1/3$ de $H$ ao ponto $C$. Portanto:

$$\text{Área}(\text{segmento}) \cdot HK = \text{Área}(\triangle AFC) \cdot \frac{HC}{3}$$

Como $HK = HC/2$: $\text{Área}(\text{segmento}) = \frac{1}{3}\text{Área}(\triangle AFC) = \frac{4}{3}\text{Área}(\triangle ABC)$. ✓ — exatamente o resultado que já tínhamos visto demonstrado rigorosamente por exaustão (§14.6), agora obtido por um caminho muito mais curto e muito menos rigoroso.

Arquimedes deixou claro que considerava esse "método mecânico" uma ferramenta de *descoberta*, não de *demonstração*: ele próprio escreve que é mais fácil fornecer a demonstração rigorosa de um teorema quando já se sabe, de antemão, o que está envolvido. A demonstração rigorosa vinha depois, pelo método de exaustão — exatamente a sequência que já antecipamos quando discutimos Eudoxo (§10.4): primeiro a descoberta, depois a prova.

Essa distinção — entre o contexto da descoberta e o contexto da justificação — é central na filosofia da ciência moderna. Arquimedes a articulou com nitidez 2.300 anos antes de Karl Popper.

---

### 14.10 Resultados Adicionais

**Os 13 sólidos semirregulares:** Papus registra que Arquimedes descobriu os 13 poliedros convexos cujas faces são polígonos regulares de dois ou mais tipos diferentes e cujos vértices são todos equivalentes. São os hoje chamados **sólidos de Arquimedes** — o cuboctaedro, o icosidodecaedro, e outros 11. Foram redescobertos por Kepler em 1619.

**A fórmula de Herão:** Os árabes registram que Arquimedes conhecia a fórmula para a área de um triângulo em termos de seus lados: $A = \sqrt{s(s-a)(s-b)(s-c)}$, onde $s = (a+b+c)/2$. A fórmula é chamada "de Herão" porque a demonstração mais antiga que sobreviveu é a de Herão de Alexandria (§17) — mas a prioridade é de Arquimedes.

**O Livro de Lemas — O Arbelos:** O *Livro de Lemas* (preservado apenas em tradução árabe) contém um estudo do **arbelos** ("faca do sapateiro") — a região entre três semicírculos tangentes. Arquimedes demonstra que o círculo inscrito na região tem diâmetro igual à perpendicular do ponto de tangência dos dois semicírculos menores. E que os dois círculos inscritos nas duas metades do arbelos são iguais. São resultados elementares mas elegantes — o tipo de geometria recreativa que Arquimedes cultivava ao lado do trabalho pesado.

**A trissecção por neusis:** O *Livro de Lemas* também contém uma trissecção do ângulo por *neusis* — inserção de um segmento de comprimento fixo entre uma reta e um círculo de forma que passe por um ponto dado. É uma construção com régua *marcada* (não a régua sem marcas de Platão) e resolve o problema em poucos passos.

**O Stomachion — combinatória antes da combinatória.** O mesmo palimpsesto que preservou *O Método* (§14.9) também guarda fragmentos de um tratado curioso, conhecido como **Stomachion**: um quebra-cabeça geométrico no estilo do tangram, formado por 14 peças planas que se encaixam para formar um quadrado. O que sobrou do texto sugere que Arquimedes não estava apenas brincando com o quebra-cabeça — estava investigando, com seriedade matemática, **de quantas maneiras diferentes** as 14 peças podem ser reorganizadas para formar o mesmo quadrado. Se essa leitura estiver correta, Arquimedes estava fazendo **análise combinatória** — contagem sistemática de configurações possíveis — dois mil anos antes do campo receber esse nome. É apenas um fragmento, e boa parte do tratado original se perdeu, mas o suficiente sobreviveu para intrigar matemáticos modernos: em 2003, o problema de contar exatamente quantas montagens distintas do Stomachion são possíveis foi finalmente resolvido por computador, com resposta 17.152.

Vale lembrar, por fim, que estes catorze tratados sobreviventes são apenas uma fração do que Arquimedes escreveu. Fontes antigas — incluindo o próprio historiador romano Lívio — mencionam obras mais extensas sobre alavancas e centros de gravidade, sobre os poliedros semirregulares mencionados acima, sobre óptica e sobre astronomia, todas hoje completamente perdidas. O que temos é extraordinário; o que se perdeu, segundo qualquer estimativa razoável, era provavelmente ainda mais.

> **Conexão com o projeto:** *O Método* de Arquimedes — descobrir resultados por analogia física (equilíbrio de alavanca) e depois demonstrá-los rigorosamente — é exatamente como a engenharia moderna de controle funciona. Um controlador PID é primeiro projetado por intuição física (parâmetro proporcional controla o erro, integral elimina o erro residual, derivativo amortece oscilações), depois verificado por análise rigorosa de estabilidade (critério de Routh-Hurwitz, margem de fase). A separação entre descoberta heurística e verificação formal que Arquimedes articulou é o fluxo de trabalho padrão de qualquer projeto de controle de missão. E o Stomachion — contar configurações possíveis de um conjunto fixo de peças — é estruturalmente o mesmo problema que o software de planejamento de movimento do rover enfrenta ao enumerar configurações possíveis de juntas robóticas que satisfazem um conjunto de restrições geométricas.

---

*Fontes desta parte: Boyer, cap. 6 · Struik, cap. III · Katz, § 4.3*

---
> **Status:** Parte 19 de N — Arquimedes: Conoides e Esferoides, O Método, Resultados Adicionais (completa — encerra a seção de Arquimedes)
> **Próxima parte:** Apolônio de Perga — o Grande Geômetra das Cônicas
