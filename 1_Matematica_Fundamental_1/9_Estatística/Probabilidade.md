# Probabilidade

A **probabilidade** é a medida da chance de um evento ocorrer. É uma ferramenta matemática que quantifica a incerteza, permitindo tomar decisões informadas diante de situações imprevisíveis. A probabilidade está presente em jogos, previsões do tempo, seguros, medicina, finanças e praticamente todos os aspectos da vida moderna.

## Definição

Probabilidade é um número entre **0** e **1** (ou entre **0%** e **100%**) que indica a chance de um evento acontecer.

- **0** (0%) = evento impossível
- **1** (100%) = evento certo
- **0,5** (50%) = evento tão provável quanto improvável

## Cálculo da Probabilidade

### Probabilidade Clássica (Teoria dos Jogos)

Quando todos os resultados são **igualmente prováveis**:

$$ P(A) = \frac{\text{número de casos favoráveis a } A}{\text{número total de casos possíveis}} $$

### Exemplo 1: Lançar um Dado

Qual a probabilidade de sair o número 4?

- Casos favoráveis: 1 (apenas o 4)
- Casos possíveis: 6 (1, 2, 3, 4, 5, 6)

$$ P(4) = \frac{1}{6} \approx 0{,}167 = 16{,}7\% $$

### Exemplo 2: Lançar uma Moeda

Qual a probabilidade de sair cara?

- Casos favoráveis: 1 (cara)
- Casos possíveis: 2 (cara, coroa)

$$ P(\text{cara}) = \frac{1}{2} = 0{,}5 = 50\% $$

### Exemplo 3: Baralho

Qual a probabilidade de tirar um ás de um baralho de 52 cartas?

- Casos favoráveis: 4 (4 ases)
- Casos possíveis: 52

$$ P(\text{ás}) = \frac{4}{52} = \frac{1}{13} \approx 0{,}077 = 7{,}7\% $$

## Espaço Amostral e Eventos

### Espaço Amostral ($S$)
Conjunto de **todos** os resultados possíveis.

**Exemplo:** Lançar um dado: $S = \{1, 2, 3, 4, 5, 6\}$

**Exemplo:** Lançar duas moedas: $S = \{(C,C), (C,K), (K,C), (K,K)\}$

### Evento ($A$)
Subconjunto do espaço amostral (resultados que nos interessam).

**Exemplo:** "Sair número par no dado": $A = \{2, 4, 6\}$

$$ P(A) = \frac{3}{6} = \frac{1}{2} = 50\% $$

## Propriedades da Probabilidade

### 1. Probabilidade entre 0 e 1

$$ 0 \leq P(A) \leq 1 $$

### 2. Soma das Probabilidades = 1

$$ P(S) = 1 $$

A soma das probabilidades de todos os resultados possíveis é 1 (100%).

### 3. Probabilidade do Evento Complementar

$$ P(A') = 1 - P(A) $$

O evento complementar é "A **não** acontecer".

**Exemplo:** Se $P(\text{chover}) = 0{,}3$, então $P(\text{não chover}) = 1 - 0{,}3 = 0{,}7$.

### 4. União de Eventos (A ou B)

$$ P(A \cup B) = P(A) + P(B) - P(A \cap B) $$

Se $A$ e $B$ são **mutuamente exclusivos** (não podem acontecer juntos):

$$ P(A \cup B) = P(A) + P(B) $$

**Exemplo:** Probabilidade de sair 2 ou 5 no dado:

$$ P(2 \cup 5) = P(2) + P(5) = \frac{1}{6} + \frac{1}{6} = \frac{2}{6} = \frac{1}{3} $$

### 5. Interseção de Eventos (A e B)

$$ P(A \cap B) = P(A) \times P(B|A) $$

Se $A$ e $B$ são **independentes** (um não afeta o outro):

$$ P(A \cap B) = P(A) \times P(B) $$

**Exemplo:** Lançar duas moedas. Probabilidade de duas caras:

$$ P(\text{cara} \cap \text{cara}) = \frac{1}{2} \times \frac{1}{2} = \frac{1}{4} = 25\% $$

## Probabilidade Condicional

Probabilidade de um evento ocorrer **dado que** outro já ocorreu.

$$ P(A|B) = \frac{P(A \cap B)}{P(B)} $$

**Exemplo:** Em uma turma, 60% são mulheres e 40% homens. Entre as mulheres, 30% têm olhos azuis. Entre os homens, 20% têm olhos azuis. Qual a probabilidade de uma pessoa sorteada ter olhos azuis?

$$ P(\text{azul}) = P(\text{azul}|M) \cdot P(M) + P(\text{azul}|H) \cdot P(H) $$
$$ P(\text{azul}) = 0{,}30 \times 0{,}60 + 0{,}20 \times 0{,}40 = 0{,}18 + 0{,}08 = 0{,}26 = 26\% $$

## Árvore de Probabilidades

Ferramenta visual para organizar probabilidades de eventos sequenciais.

```
          Primeiro Lançamento
          /              \
       Cara (1/2)      Coroa (1/2)
       /    \           /    \
    Cara  Coroa      Cara  Coroa
   (1/2)  (1/2)     (1/2)  (1/2)

Resultados finais:
- C,C: 1/2 × 1/2 = 1/4
- C,K: 1/2 × 1/2 = 1/4
- K,C: 1/2 × 1/2 = 1/4
- K,K: 1/2 × 1/2 = 1/4
```

## Probabilidade vs. Estatística

| Probabilidade | Estatística |
|---------------|-------------|
| Parte do modelo, prediz o futuro | Parte dos dados, analisa o passado |
| "Se lançar um dado honesto, qual a chance de sair 6?" | "Lancei um dado 100 vezes e saiu 6 em 18. O dado é honesto?" |
| Teoria → Dados | Dados → Conclusões |

## Probabilidade na Vida Real

### Jogos e Apostas
- **Mega-Sena:** escolher 6 números de 60. Probabilidade de acertar: $\frac{1}{C(60,6)} = \frac{1}{50.063.860}$
- **Loteria:** quase sempre desfavorável ao jogador (esperança matemática negativa)
- **Poker:** probabilidade de royal flush: $\frac{4}{2.598.960} \approx 0{,}00015\%$

### Saúde e Medicina
- **Teste de diagnóstico:** probabilidade de falso positivo, falso negativo
- **Eficácia de vacina:** probabilidade de proteção
- **Epidemiologia:** probabilidade de transmissão, taxa de letalidade

### Seguros
- **Prêmio:** calculado com base na probabilidade do sinistro
- **Expectativa de vida:** usada para apólices de vida
- **Risco de acidente:** usada para seguro de carro

### Finanças
- **Risco de investimento:** probabilidade de perda
- **Modelos de precificação:** probabilidade de default
- **Diversificação:** reduzir probabilidade de perda total

### Meteorologia
- "70% de chance de chuva" = em 70% dos dias com condições similares, choveu
- Previsões baseadas em modelos probabilísticos

### Genética
- Probabilidade de herança de traços (dominante/recessivo)
- Cor dos olhos, grupo sanguíneo, doenças hereditárias

### Tomada de Decisão
- **Análise de risco:** probabilidade × impacto
- **Teoria da decisão:** escolher ação com melhor resultado esperado

## Viés Cognitivo e Probabilidade

O cérebro humano é **ruim** em intuitivamente entender probabilidades:

### Falácia do Jogador (Gambler's Fallacy)
Acreditar que eventos passados afetam eventos independentes futuros.

> "A moeda deu cara 5 vezes seguidas. A próxima vai ser coroa, certeza!"

**Errado!** Cada lançamento é independente. $P(\text{cara}) = 50\%$ sempre.

### Falácia da Conjunção
Acreditar que "A e B" é mais provável que "A" sozinho.

> "Linda, solteira, 31 anos, formada em filosofia, trabalha em banco. É mais provável que ela seja feminista ou feminista e militante?"

**Resposta:** "Feminista" é mais provável (é um subconjunto maior). "Feminista e militante" é um subconjunto menor.

### Aversão à Perda
As pessoas sentem perdas mais intensamente que ganhos equivalentes.

> Preferir não perder R$ 100 do que ganhar R$ 100 (apesar do valor ser igual).

## Problemas de Probabilidade

### Nível 1 — Básico

**1.** Lança-se um dado honesto. Qual a probabilidade de sair um número maior que 4?

$$ A = \{5, 6\} \Rightarrow P(A) = \frac{2}{6} = \frac{1}{3} \approx 33{,}3\% $$

**2.** Uma urna tem 3 bolas vermelhas e 7 azuis. Qual a probabilidade de tirar uma vermelha?

$$ P(V) = \frac{3}{10} = 0{,}3 = 30\% $$

**3.** Qual a probabilidade de não sair vermelha?

$$ P(V') = 1 - 0{,}3 = 0{,}7 = 70\% $$

### Nível 2 — Intermediário

**4.** Lança-se uma moeda 3 vezes. Qual a probabilidade de sair pelo menos uma cara?

$$ P(\text{pelo menos 1 cara}) = 1 - P(\text{3 coroas}) = 1 - \frac{1}{8} = \frac{7}{8} = 87{,}5\% $$

**5.** Em um baralho de 52 cartas, qual a probabilidade de tirar uma carta de copas ou um rei?

$$ P(\text{copas} \cup \text{rei}) = P(\text{copas}) + P(\text{rei}) - P(\text{rei de copas}) $$
$$ = \frac{13}{52} + \frac{4}{52} - \frac{1}{52} = \frac{16}{52} = \frac{4}{13} \approx 30{,}8\% $$

**6.** Uma prova tem 10 questões de múltipla escolha com 4 alternativas cada. Se um aluno chutar tudo, qual a probabilidade de acertar todas?

$$ P = \left(\frac{1}{4}\right)^{10} = \frac{1}{1.048.576} \approx 0{,}000095\% $$

### Nível 3 — Desafio

**7.** Uma família tem 2 filhos. Sabendo que pelo menos um é menino, qual a probabilidade de ambos serem meninos?

Espaço amostral (sabendo que pelo menos um é menino): {MM, MF, FM}

$$ P(\text{ambos meninos} | \text{pelo menos 1 menino}) = \frac{1}{3} \approx 33{,}3\% $$

> **Surpreendente?** Muitos acham 50%, mas não é! Se soubéssemos que o **mais velho** é menino, aí sim seria 50%.

**8.** O problema de Monty Hall (Porta dos Desafortunados):

Você escolhe uma de 3 portas. Atrás de uma há um carro, das outras duas, cabras. O apresentador (que sabe onde está o carro) abre uma porta que você **não** escolheu, revelando uma cabra. Ele pergunta se você quer trocar de porta. Deve trocar?

**Sim!** Trocar dá **2/3 (66,7%)** de chance de ganhar. Ficar dá **1/3 (33,3%)**.

**Explicação:**
- Inicialmente: $P(\text{escolha certa}) = 1/3$, $P(\text{carro nas outras 2}) = 2/3$
- O apresentador abre uma porta com cabra (sabendo onde está)
- A probabilidade de 2/3 se concentra agora na única porta restante!
- Trocar = pegar a porta com 2/3 de chance

> **Dica:** Se não acredita, simule 100 vezes com cartas. A estatística não mente!

---
**Fim do capítulo 9 — Estatística**
