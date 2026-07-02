# Dízimas Periódicas — Fração Geratriz

Uma **dízima periódica** é uma representação decimal infinita em que um ou mais algarismos se repetem indefinidamente. A **fração geratriz** é a fração que, ao ser dividida, produz exatamente essa dízima. Saber encontrar a fração geratriz é fundamental para trabalhar com precisão em cálculos.

## Tipos de Dízimas

### 1. Dízima Periódica Simples

O período começa **imediatamente** após a vírgula.

$$ 0{,}\overline{3} = 0{,}333\ldots $$
$$ 0{,}\overline{27} = 0{,}272727\ldots $$
$$ 0{,}\overline{142857} = 0{,}142857142857\ldots $$

### 2. Dízima Periódica Composta

Existe uma parte **não periódica** (antecedente) antes do período.

$$ 0{,}1\overline{6} = 0{,}1666\ldots $$
$$ 0{,}12\overline{34} = 0{,}12343434\ldots $$
$$ 0{,}123\overline{456} = 0{,}123456456456\ldots $$

## Método Algébrico para Fração Geratriz

### Dízima Simples

Seja $x = 0{,}\overline{abc}$

**Passo 1:** Multiplique por $10^n$ onde $n$ = número de algarismos do período.
$$ 1000x = abc{,}\overline{abc} $$

**Passo 2:** Subtraia $x$
$$ 1000x - x = abc{,}\overline{abc} - 0{,}\overline{abc} $$
$$ 999x = abc $$

**Passo 3:** Isole $x$
$$ x = \frac{abc}{999} $$

**Regra geral:**
$$ 0{,}\overline{a_1 a_2 \ldots a_n} = \frac{a_1 a_2 \ldots a_n}{\underbrace{99\ldots9}_{n \text{ vezes}}} $$

### Dízima Composta

Seja $x = 0{,}ab\overline{cd}$

**Passo 1:** Multiplique por $10^m$ onde $m$ = número de algarismos da parte não periódica.
$$ 100x = ab{,}\overline{cd} $$

**Passo 2:** Multiplique por $10^{m+n}$ onde $n$ = número de algarismos do período.
$$ 10000x = abcd{,}\overline{cd} $$

**Passo 3:** Subtraia
$$ 10000x - 100x = abcd - ab $$
$$ 9900x = abcd - ab $$

**Passo 4:** Isole $x$
$$ x = \frac{abcd - ab}{9900} $$

**Regra geral:**
$$ 0{,}\underbrace{a_1 \ldots a_m}_{\text{não periódica}}\overline{\underbrace{b_1 \ldots b_n}_{\text{período}}} = \frac{a_1 \ldots a_m b_1 \ldots b_n - a_1 \ldots a_m}{\underbrace{99\ldots9}_{n \text{ vezes}}\underbrace{00\ldots0}_{m \text{ vezes}}} $$

## Exemplos Detalhados

### Exemplo 1: Simples

$$ x = 0{,}\overline{7} $$
$$ 10x = 7{,}\overline{7} $$
$$ 10x - x = 7 $$
$$ 9x = 7 $$
$$ x = \frac{7}{9} $$

### Exemplo 2: Simples com 2 algarismos

$$ x = 0{,}\overline{23} $$
$$ 100x = 23{,}\overline{23} $$
$$ 100x - x = 23 $$
$$ 99x = 23 $$
$$ x = \frac{23}{99} $$

### Exemplo 3: Composta

$$ x = 0{,}2\overline{5} $$
$$ 10x = 2{,}\overline{5} $$
$$ 100x = 25{,}\overline{5} $$
$$ 100x - 10x = 25 - 2 = 23 $$
$$ 90x = 23 $$
$$ x = \frac{23}{90} $$

### Exemplo 4: Composta com mais algarismos

$$ x = 0{,}12\overline{34} $$
$$ 100x = 12{,}\overline{34} $$
$$ 10000x = 1234{,}\overline{34} $$
$$ 10000x - 100x = 1234 - 12 = 1222 $$
$$ 9900x = 1222 $$
$$ x = \frac{1222}{9900} = \frac{611}{4950} $$

### Exemplo 5: Número Misto

$$ x = 1{,}\overline{6} $$
$$ x = 1 + 0{,}\overline{6} = 1 + \frac{6}{9} = 1 + \frac{2}{3} = \frac{5}{3} $$

Ou diretamente:
$$ x = 1{,}\overline{6} $$
$$ 10x = 16{,}\overline{6} $$
$$ 10x - x = 16{,}\overline{6} - 1{,}\overline{6} = 15 $$
$$ 9x = 15 $$
$$ x = \frac{15}{9} = \frac{5}{3} $$

## Tabela de Dízimas Comuns

| Dízima | Fração | Tipo |
|--------|--------|------|
| $0{,}\overline{1}$ | $\frac{1}{9}$ | Simples |
| $0{,}\overline{2}$ | $\frac{2}{9}$ | Simples |
| $0{,}\overline{3}$ | $\frac{1}{3}$ | Simples |
| $0{,}\overline{4}$ | $\frac{4}{9}$ | Simples |
| $0{,}\overline{5}$ | $\frac{5}{9}$ | Simples |
| $0{,}\overline{6}$ | $\frac{2}{3}$ | Simples |
| $0{,}\overline{7}$ | $\frac{7}{9}$ | Simples |
| $0{,}\overline{8}$ | $\frac{8}{9}$ | Simples |
| $0{,}\overline{9}$ | $\frac{9}{9} = 1$ | Simples (caso especial) |
| $0{,}1\overline{6}$ | $\frac{1}{6}$ | Composta |
| $0{,}0\overline{1}$ | $\frac{1}{90}$ | Composta |
| $0{,}\overline{09}$ | $\frac{1}{11}$ | Simples |
| $0{,}\overline{142857}$ | $\frac{1}{7}$ | Simples |

## Aplicações na Vida Real

- **Finanças:** taxas de juros (0,333...% = 1/3%)
- **Engenharia:** precisão infinita em teoria, aproximação na prática
- **Computação:** erros de ponto flutuante (0,1 não é exato em binário!)
- **Física:** constantes (1/3 na carga do quark)
- **Música:** acústica, harmonias (frequências racionais)
- **Estatística:** probabilidades (1/3 = 0,333...)
- **Química:** proporções estequiométricas
- **Medicina:** dosagens fracionárias
- **Economia:** divisões perfeitas de recursos
- **Geometria:** proporções áurea (irracional, mas aproximada por racionais)

## Problemas

### Nível 1 — Básico

**1.** Encontre a fração geratriz de $0{,}\overline{4}$.

$$ x = 0{,}\overline{4} \implies 10x = 4{,}\overline{4} \implies 9x = 4 \implies x = \frac{4}{9} $$

**Resposta:** $\frac{4}{9}$.

**2.** Encontre a fração geratriz de $0{,}\overline{36}$.

$$ x = 0{,}\overline{36} \implies 100x = 36{,}\overline{36} \implies 99x = 36 \implies x = \frac{36}{99} = \frac{4}{11} $$

**Resposta:** $\frac{4}{11}$.

**3.** Encontre a fração geratriz de $0{,}1\overline{6}$.

$$ x = 0{,}1\overline{6} \implies 10x = 1{,}\overline{6}, 100x = 16{,}\overline{6} \implies 90x = 15 \implies x = \frac{15}{90} = \frac{1}{6} $$

**Resposta:** $\frac{1}{6}$.

**4.** Encontre a fração geratriz de $0{,}\overline{123}$.

$$ x = 0{,}\overline{123} \implies 1000x = 123{,}\overline{123} \implies 999x = 123 \implies x = \frac{123}{999} = \frac{41}{333} $$

**Resposta:** $\frac{41}{333}$.

**5.** Encontre a fração geratriz de $2{,}\overline{5}$.

$$ x = 2{,}\overline{5} \implies 10x = 25{,}\overline{5} \implies 9x = 23 \implies x = \frac{23}{9} = 2\frac{5}{9} $$

**Resposta:** $\frac{23}{9}$ (ou $2\frac{5}{9}$).

### Nível 2 — Intermediário

**6.** Encontre a fração geratriz de $0{,}2\overline{34}$.

$$ x = 0{,}2\overline{34} \implies 10x = 2{,}\overline{34}, 1000x = 234{,}\overline{34} $$
$$ 1000x - 10x = 234 - 2 = 232 \implies 990x = 232 \implies x = \frac{232}{990} = \frac{116}{495} $$

**Resposta:** $\frac{116}{495}$.

**7.** Encontre a fração geratriz de $0{,}0\overline{1}$.

$$ x = 0{,}0\overline{1} = 0{,}0111\ldots \implies 100x = 1{,}\overline{1}, 1000x = 11{,}\overline{1} $$
$$ 1000x - 100x = 11 - 1 = 10 \implies 900x = 10 \implies x = \frac{10}{900} = \frac{1}{90} $$

Ou pela regra: $\frac{01 - 0}{90} = \frac{1}{90}$.

**Resposta:** $\frac{1}{90}$.

**8.** Encontre a fração geratriz de $0{,}\overline{9}$ e explique o resultado.

$$ x = 0{,}\overline{9} \implies 10x = 9{,}\overline{9} \implies 9x = 9 \implies x = 1 $$

**Resposta:** $\frac{9}{9} = 1$. A dízima $0{,}\overline{9}$ é exatamente igual a 1 (não é "quase 1", é igual).

**9.** Encontre a fração geratriz de $0{,}123\overline{456}$.

$$ x = 0{,}123\overline{456} \implies 1000x = 123{,}\overline{456}, 1000000x = 123456{,}\overline{456} $$
$$ 999000x = 123456 - 123 = 123333 \implies x = \frac{123333}{999000} = \frac{41111}{333000} $$

**Resposta:** $\frac{41111}{333000}$ (ou $\frac{123333}{999000}$).

**10.** Encontre a fração geratriz de $5{,}3\overline{2}$.

$$ x = 5{,}3\overline{2} \implies 10x = 53{,}\overline{2}, 100x = 532{,}\overline{2} $$
$$ 100x - 10x = 532 - 53 = 479 \implies 90x = 479 \implies x = \frac{479}{90} = 5\frac{29}{90} $$

**Resposta:** $\frac{479}{90}$ (ou $5\frac{29}{90}$).

### Nível 3 — Desafio

**11.** Se $0{,}\overline{a} = \frac{5}{11}$ (onde $a$ é um algarismo), qual é $a$?

$$ 0{,}\overline{a} = \frac{a}{9} = \frac{5}{11} \implies a = \frac{45}{11} $$

Mas $a$ deve ser um algarismo (0-9). $\frac{45}{11} \approx 4{,}09$ (não é inteiro de 0 a 9).

**Problema:** $0{,}\overline{a}$ com um algarismo não pode dar $\frac{5}{11}$ porque $\frac{5}{11} = 0{,}\overline{45}$ (período de 2 algarismos, não 1).

**Resposta:** Impossível. $\frac{5}{11} = 0{,}\overline{45}$ tem período de 2 algarismos, não pode ser escrita como $0{,}\overline{a}$ com um algarismo.

**12.** Mostre que $0{,}\overline{142857} \times 7 = 0{,}\overline{999999} = 1$.

$$ 0{,}\overline{142857} = \frac{142857}{999999} = \frac{1}{7} $$
$$ \frac{1}{7} \times 7 = 1 $$

E $0{,}\overline{999999} = \frac{999999}{999999} = 1$.

**Resposta:** Prova verificada. $0{,}\overline{142857} = \frac{1}{7}$.

**13.** Encontre a fração geratriz de $0{,}\overline{123456790}$ (note: falta o 8!).

$$ x = 0{,}\overline{123456790} \implies 10^9 x = 123456790{,}\overline{123456790} $$
$$ 999999999x = 123456790 \implies x = \frac{123456790}{999999999} $$

Note que $999999999 = 9 \times 111111111 = 9 \times 3 \times 37037037 = 27 \times 37037037$...

$123456790 \times 8 = 987654320$. E $999999999 = 9 \times 111111111$.
$111111111 \div 12345679 = 9$ (aproximadamente? $12345679 \times 9 = 111111111$). 

$123456790 = 12345679 \times 10 = 10 \times 12345679$.
$999999999 = 9 \times 111111111 = 9 \times 9 \times 12345679 = 81 \times 12345679$.

$$ x = \frac{10 \times 12345679}{81 \times 12345679} = \frac{10}{81} $$

**Resposta:** $\frac{10}{81}$ (dízima com período 123456790, que interessantemente não contém o dígito 8).

---
**Fim — Dízimas Periódicas: Fração Geratriz**
