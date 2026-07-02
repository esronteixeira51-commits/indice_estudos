# Representação Decimal (Finita e Infinita Periódica)

Todo número racional pode ser representado na forma **decimal**, que pode ser **finita** (termina) ou **infinita periódica** (repete um padrão). Essa dualidade é uma das características fundamentais dos racionais.

## Decimais Finitas

Uma fração resulta em decimal finita quando o denominador (na forma irredutível) tem apenas fatores **2** e **5**.

### Critério

$$ \frac{a}{b} \text{ é decimal finita} \iff b = 2^m \times 5^n \text{ (na forma irredutível)} $$

### Exemplos

$$ \frac{3}{4} = \frac{3}{2^2} = 0{,}75 \quad \text{(finita)} $$
$$ \frac{7}{20} = \frac{7}{2^2 \times 5} = 0{,}35 \quad \text{(finita)} $$
$$ \frac{1}{8} = \frac{1}{2^3} = 0{,}125 \quad \text{(finita)} $$
$$ \frac{3}{25} = \frac{3}{5^2} = 0{,}12 \quad \text{(finita)} $$

## Decimais Infinitas Periódicas (Dízimas)

Uma fração resulta em dízima periódica quando o denominador (na forma irredutível) tem algum fator **diferente de 2 e 5**.

### Critério

$$ \frac{a}{b} \text{ é dízima periódica} \iff b \text{ tem fator primo } \neq 2 \text{ e } \neq 5 $$

### Exemplos

$$ \frac{1}{3} = 0{,}333\ldots = 0{,}\overline{3} \quad \text{(período 3)} $$
$$ \frac{1}{7} = 0{,}142857142857\ldots = 0{,}\overline{142857} \quad \text{(período 142857)} $$
$$ \frac{2}{9} = 0{,}222\ldots = 0{,}\overline{2} \quad \text{(período 2)} $$
$$ \frac{1}{6} = 0{,}1666\ldots = 0{,}1\overline{6} \quad \text{(não periódica 1, periódica 6)} $$

## Tipos de Dízimas

### 1. Dízima Periódica Simples

O período começa imediatamente após a vírgula:

$$ 0{,}\overline{3} = 0{,}333\ldots $$
$$ 0{,}\overline{142857} = 0{,}142857142857\ldots $$

### 2. Dízima Periódica Composta

Há uma parte **não periódica** antes do período:

$$ 0{,}1\overline{6} = 0{,}1666\ldots $$
$$ 0{,}12\overline{34} = 0{,}12343434\ldots $$

### 3. Decimal Finita como Dízima

Toda decimal finita pode ser escrita como dízima com período 0 (ou período 9):

$$ 0{,}5 = 0{,}5000\ldots = 0{,}50\overline{0} $$
$$ 0{,}5 = 0{,}4999\ldots = 0{,}4\overline{9} \quad \text{(veja a prova em } 0{,}\overline{9} = 1) $$

## Fração Geratriz de Dízimas

### Dízima Periódica Simples

$$ 0{,}\overline{ab} = \frac{ab}{99} \quad \text{(dois algarismos no período → dois 9s)} $$

$$ 0{,}\overline{abc} = \frac{abc}{999} $$

**Regra geral:**

$$ 0{,}\overline{a_1 a_2 \ldots a_n} = \frac{a_1 a_2 \ldots a_n}{\underbrace{99\ldots9}_{n \text{ vezes}}} $$

### Dízima Periódica Composta

$$ 0{,}a\overline{bc} = \frac{abc - a}{90} \quad \text{(1 não periódico, 2 periódicos)} $$

$$ 0{,}ab\overline{cd} = \frac{abcd - ab}{9900} $$

**Regra geral:**
- Numerador: número completo (não periódico + periódico) menos parte não periódica
- Denominador: um 9 para cada algarismo do período, um 0 para cada algarismo não periódico

### Exemplos

$$ 0{,}\overline{7} = \frac{7}{9} $$
$$ 0{,}\overline{23} = \frac{23}{99} $$
$$ 0{,}2\overline{5} = \frac{25 - 2}{90} = \frac{23}{90} $$
$$ 0{,}12\overline{34} = \frac{1234 - 12}{9900} = \frac{1222}{9900} = \frac{611}{4950} $$

## Exemplos

### Exemplo 1: Classificação

Classifique as decimais de $\frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \frac{1}{5}, \frac{1}{6}, \frac{1}{7}$:

| Fração | Denominador | Fatores | Tipo | Decimal |
|--------|-------------|---------|------|---------|
| $\frac{1}{2}$ | 2 | $2^1$ | Finita | $0{,}5$ |
| $\frac{1}{3}$ | 3 | $3^1$ | Periódica simples | $0{,}\overline{3}$ |
| $\frac{1}{4}$ | 4 | $2^2$ | Finita | $0{,}25$ |
| $\frac{1}{5}$ | 5 | $5^1$ | Finita | $0{,}2$ |
| $\frac{1}{6}$ | 6 | $2 \times 3$ | Periódica composta | $0{,}1\overline{6}$ |
| $\frac{1}{7}$ | 7 | $7^1$ | Periódica simples | $0{,}\overline{142857}$ |

### Exemplo 2: Fração Geratriz

Encontre a fração de $0{,}\overline{63}$:

$$ 0{,}\overline{63} = \frac{63}{99} = \frac{7}{11} $$

### Exemplo 3: Fração Geratriz Composta

Encontre a fração de $0{,}4\overline{5}$:

$$ 0{,}4\overline{5} = \frac{45 - 4}{90} = \frac{41}{90} $$

## Aplicações na Vida Real

- **Engenharia:** medições precisas, tolerâncias (0,125 mm = $\frac{1}{8}$ mm)
- **Finanças:** taxas de juros, câmbio (0,333... = $\frac{1}{3}$)
- **Química:** concentrações, pH (logaritmo, mas baseado em medidas racionais)
- **Farmácia:** dosagens ($0{,}\overline{3}$ ml = $\frac{1}{3}$ ml)
- **Construção:** medidas em sistema métrico e imperial
- **Mecânica:** rotações, engrenagens (0,142857... = $\frac{1}{7}$)
- **Estatística:** probabilidades (0,333... = chance de 1 em 3)
- **Programação:** precisão de ponto flutuante (erros de arredondamento)
- **Música:** harmonias, frequências (oitavas, quintas)
- **Geografia:** coordenadas GPS, precisão de medidas

## Problemas

### Nível 1 — Básico

**1.** Classifique a decimal de $\frac{3}{8}$: finita ou periódica? Calcule.

$$ 8 = 2^3 \text{ (apenas 2s)} \implies \text{finita} $$
$$ \frac{3}{8} = 0{,}375 $$

**Resposta:** Decimal finita: $0{,}375$.

**2.** Classifique a decimal de $\frac{2}{9}$: finita ou periódica? Calcule.

$$ 9 = 3^2 \text{ (tem fator 3)} \implies \text{periódica} $$
$$ \frac{2}{9} = 0{,}\overline{2} $$

**Resposta:** Dízima periódica simples: $0{,}\overline{2}$.

**3.** Encontre a fração geratriz de $0{,}\overline{4}$.

$$ 0{,}\overline{4} = \frac{4}{9} $$

**Resposta:** $\frac{4}{9}$.

**4.** Encontre a fração geratriz de $0{,}\overline{25}$.

$$ 0{,}\overline{25} = \frac{25}{99} $$

**Resposta:** $\frac{25}{99}$.

**5.** Classifique a decimal de $\frac{5}{12}$: finita ou periódica? Por quê?

$$ 12 = 2^2 \times 3 \text{ (tem fator 3)} \implies \text{periódica} $$

**Resposta:** Periódica (composta), porque $12 = 2^2 \times 3$ tem fator 3 (diferente de 2 e 5).

### Nível 2 — Intermediário

**6.** Encontre a fração geratriz de $0{,}1\overline{6}$.

$$ 0{,}1\overline{6} = \frac{16 - 1}{90} = \frac{15}{90} = \frac{1}{6} $$

**Resposta:** $\frac{1}{6}$.

**7.** Encontre a fração geratriz de $0{,}2\overline{34}$.

$$ 0{,}2\overline{34} = \frac{234 - 2}{990} = \frac{232}{990} = \frac{116}{495} $$

**Resposta:** $\frac{116}{495}$ (ou $\frac{232}{990}$ não simplificada).

**8.** Determine se $\frac{7}{40}$ é decimal finita ou periódica. Calcule.

$$ 40 = 2^3 \times 5 \text{ (apenas 2s e 5s)} \implies \text{finita} $$
$$ \frac{7}{40} = 0{,}175 $$

**Resposta:** Decimal finita: $0{,}175$.

**9.** Calcule $\frac{1}{7}$ e identifique o período.

$$ \frac{1}{7} = 0{,}142857142857\ldots = 0{,}\overline{142857} $$

**Resposta:** Dízima periódica simples com período 142857 (6 algarismos).

**10.** Encontre a fração geratriz de $1{,}\overline{23}$.

$$ 1{,}\overline{23} = 1 + 0{,}\overline{23} = 1 + \frac{23}{99} = \frac{99 + 23}{99} = \frac{122}{99} = 1\frac{23}{99} $$

**Resposta:** $\frac{122}{99}$.

### Nível 3 — Desafio

**11.** Prove que $\frac{1}{7}$ tem período de comprimento 6.

O período da dízima de $\frac{1}{p}$ (p primo) divide $p - 1$ (Teorema de Fermat).

Para $p = 7$: o período divide $7 - 1 = 6$. Os divisores de 6 são 1, 2, 3, 6.

- Período 1? $0{,}\overline{a} = \frac{a}{9}$. $\frac{a}{9} = \frac{1}{7} \implies a = \frac{9}{7}$ (não inteiro). ✗
- Período 2? $0{,}\overline{ab} = \frac{ab}{99}$. $\frac{ab}{99} = \frac{1}{7} \implies ab = \frac{99}{7}$ (não inteiro). ✗
- Período 3? $0{,}\overline{abc} = \frac{abc}{999}$. $\frac{abc}{999} = \frac{1}{7} \implies abc = \frac{999}{7} = 142{,}714...$ (não inteiro). ✗

Logo, o período é **6**.

$$ \frac{1}{7} = 0{,}\overline{142857} $$

**Resposta:** Período 6 (provado que não pode ser 1, 2, ou 3).

**12.** Encontre a fração geratriz de $0{,}\overline{9}$ de duas formas diferentes e mostre que é igual a 1.

**Forma 1:** Seja $x = 0{,}\overline{9} = 0{,}999\ldots$
$$ 10x = 9{,}999\ldots = 9 + x $$
$$ 9x = 9 \implies x = 1 $$

**Forma 2:** Regra das dízimas:
$$ 0{,}\overline{9} = \frac{9}{9} = 1 $$

**Resposta:** $0{,}\overline{9} = 1$ (prova algébrica e por regra).

**13.** Se $\frac{1}{n}$ tem decimal finita com 3 casas decimais, quantos valores possíveis $n$ existem (números inteiros positivos)?

$$ \frac{1}{n} = 0{,}abc = \frac{abc}{1000} $$
$$ n = \frac{1000}{abc} $$

Para $n$ ser inteiro, $abc$ deve dividir 1000. $abc$ é um número de 1 a 3 algarismos (1 a 999).

$1000 = 2^3 \times 5^3 = 8 \times 125$

Divisores de 1000: $(3+1)(3+1) = 16$ divisores.

Excluindo 1000 (que daria $n = 1$ e decimal $0{,}001$ que tem 3 casas... mas $0{,}001 = 0{,}0010 = 0{,}00100$... hmm, $n = 1$ dá $1{,}000$, não $0{,}abc$ com $abc$ tendo 3 casas decimais significativas?)

Na verdade, $abc$ de 1 a 999 que divide 1000:
Divisores de 1000: 1, 2, 4, 5, 8, 10, 20, 25, 40, 50, 100, 125, 200, 250, 500, 1000.

De 1 a 999: 15 divisores (excluindo 1000).

Mas $\frac{1}{n}$ ter "3 casas decimais" significa que o denominador na forma irredutível tem $2^3 \times 5^3 = 1000$ como divisor do denominador, ou seja, $n$ divide 1000? Não, é o contrário: $n$ deve ser tal que $n = 2^a \times 5^b$ com $a \leq 3$ e $b \leq 3$ (para ter no máximo 3 casas).

Mas para ter **exatamente** 3 casas decimais finitas (e não menos), $n$ deve ter $a = 3$ ou $b = 3$ (ou ambos) na forma $2^a \times 5^b$.

Valores de $n = 2^a \times 5^b$ com $0 \leq a, b \leq 3$:
Total: $4 \times 4 = 16$ valores (1, 2, 4, 5, 8, 10, 20, 25, 40, 50, 100, 125, 200, 250, 500, 1000).

Para ter **exatamente** 3 casas (não 1 ou 2):
- $a = 3$ ou $b = 3$ (ou ambos)
- Excluir $a < 3$ E $b < 3$ (que dão 1 ou 2 casas)

Valores com $a < 3$ e $b < 3$: $2^0 \times 5^0 = 1, 2, 4, 5, 10, 20, 25, 50, 100$ (9 valores? Não, $3 \times 3 = 9$ valores).

Valores com $a = 3$ ou $b = 3$: $16 - 9 = 7$ valores.
São: 8, 40, 200, 125, 250, 500, 1000. (7 valores).

**Resposta:** 7 valores: 8, 40, 125, 200, 250, 500, 1000.

---
**Fim — Representação Decimal**
