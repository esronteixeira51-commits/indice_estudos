# Notação Científica

A **notação científica** é uma forma padronizada de escrever números muito grandes ou muito pequenos, usando potências de base 10. É essencial em ciências, engenharia, tecnologia e qualquer área que lide com grandezas de escala variada.

## Conceito

Um número em notação científica é escrito como:

$$ a \times 10^n $$

Onde:
- $1 \leq |a| < 10$ (a **mantissa** ou coeficiente, com exatamente um dígito não-zero antes da vírgula)
- $n \in \mathbb{Z}$ (o **expoente** ou ordem de grandeza)

### Exemplos de Conversão

$$ 3400 = 3{,}4 \times 10^3 $$
$$ 0{,}0056 = 5{,}6 \times 10^{-3} $$
$$ 150000000 = 1{,}5 \times 10^8 $$
$$ 0{,}000000021 = 2{,}1 \times 10^{-8} $$

## Conversão para Notação Científica

### Números Grandes (positivos)

1. Mova a vírgula para a esquerda até que reste apenas um dígito antes dela
2. Conte quantas casas a vírgula moveu → esse é o expoente $n$ (positivo)

**Exemplo:** $4500000$
$$ 4500000 = 4{,}500000 \times 10^6 = 4{,}5 \times 10^6 $$

### Números Pequenos (positivos)

1. Mova a vírgula para a direita até que reste apenas um dígito antes dela
2. Conte quantas casas a vírgula moveu → esse é o expoente $n$ (negativo)

**Exemplo:** $0{,}0000032$
$$ 0{,}0000032 = 3{,}2 \times 10^{-6} $$

### Números Negativos

A mantissa mantém o sinal negativo:

$$ -0{,}00045 = -4{,}5 \times 10^{-4} $$

### Números entre 1 e 10 (ou -10 e -1)

$$ 7{,}3 = 7{,}3 \times 10^0 $$

## Notação de Engenharia

Similar à notação científica, mas o expoente é sempre múltiplo de 3:

$$ 45000 = 45 \times 10^3 \text{ (engenharia)} = 4{,}5 \times 10^4 \text{ (científica)} $$

Facilita o uso de prefixos do SI (kilo, mega, giga, etc.).

## Operações com Notação Científica

### Adição e Subtração

Converter para o mesmo expoente, depois operar:

$$ 3{,}2 \times 10^4 + 5{,}1 \times 10^3 = 32 \times 10^3 + 5{,}1 \times 10^3 = 37{,}1 \times 10^3 = 3{,}71 \times 10^4 $$

### Multiplicação

Multiplicar mantissas, somar expoentes:

$$ (2{,}5 \times 10^3) \times (4{,}0 \times 10^{-2}) = (2{,}5 \times 4{,}0) \times 10^{3+(-2)} = 10 \times 10^1 = 1{,}0 \times 10^2 $$

### Divisão

Dividir mantissas, subtrair expoentes:

$$ \frac{6{,}4 \times 10^5}{3{,}2 \times 10^{-2}} = \frac{6{,}4}{3{,}2} \times 10^{5-(-2)} = 2{,}0 \times 10^7 $$

### Potência

Elevar mantissa à potência, multiplicar expoente:

$$ (2{,}0 \times 10^3)^2 = 2{,}0^2 \times 10^{3 \times 2} = 4{,}0 \times 10^6 $$

### Raiz

$$ \sqrt{9{,}0 \times 10^4} = \sqrt{9{,}0} \times 10^{\frac{4}{2}} = 3{,}0 \times 10^2 $$

## Prefixos do SI (Sistema Internacional)

| Prefixo | Símbolo | Fator | Notação |
|---------|---------|-------|---------|
| yotta | Y | $10^{24}$ | 1 000 000 000 000 000 000 000 000 |
| zetta | Z | $10^{21}$ | 1 000 000 000 000 000 000 000 |
| exa | E | $10^{18}$ | 1 000 000 000 000 000 000 |
| peta | P | $10^{15}$ | 1 000 000 000 000 000 |
| tera | T | $10^{12}$ | 1 000 000 000 000 |
| giga | G | $10^9$ | 1 000 000 000 |
| mega | M | $10^6$ | 1 000 000 |
| kilo | k | $10^3$ | 1 000 |
| hecto | h | $10^2$ | 100 |
| deca | da | $10^1$ | 10 |
| unidade | — | $10^0$ | 1 |
| deci | d | $10^{-1}$ | 0,1 |
| centi | c | $10^{-2}$ | 0,01 |
| mili | m | $10^{-3}$ | 0,001 |
| micro | μ | $10^{-6}$ | 0,000 001 |
| nano | n | $10^{-9}$ | 0,000 000 001 |
| pico | p | $10^{-12}$ | 0,000 000 000 001 |
| femto | f | $10^{-15}$ | 0,000 000 000 000 001 |
| atto | a | $10^{-18}$ | 0,000 000 000 000 000 001 |
| zepto | z | $10^{-21}$ | 0,000 000 000 000 000 000 001 |
| yocto | y | $10^{-24}$ | 0,000 000 000 000 000 000 000 001 |

## Aplicações

### Astronomia

- Distância Terra-Sol: $1{,}496 \times 10^{11}$ m ≈ 150 milhões de km
- Massa do Sol: $1{,}989 \times 10^{30}$ kg
- Raio de um átomo: ~$1 \times 10^{-10}$ m

### Física

- Velocidade da luz: $2{,}998 \times 10^8$ m/s
- Carga do elétron: $1{,}602 \times 10^{-19}$ C
- Constante de Planck: $6{,}626 \times 10^{-34}$ J·s

### Química

- Número de Avogadro: $6{,}022 \times 10^{23}$ mol$^{-1}$
- Massa de um átomo de carbono: $1{,}993 \times 10^{-23}$ g

### Computação

- 1 KB (kilobyte) = $2^{10} = 1024$ bytes (notação binária)
- 1 MB = $2^{20}$ bytes
- 1 GB = $2^{30}$ bytes
- 1 TB = $2^{40}$ bytes

> **Nota:** Na indústria, às vezes usam potências de 10 (1 GB = $10^9$ bytes) em vez de 2. Isso causa confusão! (Gibibyte vs Gigabyte)

### Biologia

- Tamanho de uma célula: ~$1 \times 10^{-5}$ m (10 μm)
- Tamanho de uma bactéria: ~$1 \times 10^{-6}$ m (1 μm)
- Tamanho de um vírus: ~$1 \times 10^{-7}$ m (100 nm)
- Comprimento do DNA humano esticado: ~$2$ m = $2 \times 10^9$ nm

### Economia

- PIB do Brasil: ~$2 \times 10^{12}$ dólares (2 trilhões)
- Dívida pública: ~$5 \times 10^{12}$ reais (5 trilhões)
- População mundial: ~$8 \times 10^9$ (8 bilhões)

## Exemplos

### Exemplo 1: Conversão

$$ 0{,}0000000000000000000000000000009109 \text{ kg (massa do elétron)} $$

$$ = 9{,}109 \times 10^{-31} \text{ kg} $$

### Exemplo 2: Multiplicação

$$ (4{,}0 \times 10^5) \times (2{,}5 \times 10^{-3}) = 10{,}0 \times 10^2 = 1{,}0 \times 10^3 $$

### Exemplo 3: Comparação

Qual é maior: $3{,}2 \times 10^7$ ou $9{,}5 \times 10^6$?

$$ 3{,}2 \times 10^7 = 32 \times 10^6 > 9{,}5 \times 10^6 $$

$3{,}2 \times 10^7$ é maior.

### Exemplo 4: Distância das Estrelas

A estrela mais próxima (Proxima Centauri) está a $4{,}24$ anos-luz. 1 ano-luz = $9{,}46 \times 10^{15}$ m.

$$ 4{,}24 \times 9{,}46 \times 10^{15} = 40{,}1 \times 10^{15} = 4{,}01 \times 10^{16} \text{ m} $$

## Problemas

### Nível 1 — Básico

**1.** Escreva $567000$ em notação científica.

$$ 5{,}67 \times 10^5 $$

**Resposta:** $5{,}67 \times 10^5$.

**2.** Escreva $0{,}0000083$ em notação científica.

$$ 8{,}3 \times 10^{-6} $$

**Resposta:** $8{,}3 \times 10^{-6}$.

**3.** Converta $2{,}4 \times 10^4$ para número decimal.

$$ 2{,}4 \times 10^4 = 24000 $$

**Resposta:** $24000$.

**4.** Converta $7{,}1 \times 10^{-3}$ para número decimal.

$$ 7{,}1 \times 10^{-3} = 0{,}0071 $$

**Resposta:** $0{,}0071$.

**5.** Calcule $(3{,}0 \times 10^4) \times (2{,}0 \times 10^2)$.

$$ (3{,}0 \times 2{,}0) \times 10^{4+2} = 6{,}0 \times 10^6 $$

**Resposta:** $6{,}0 \times 10^6$.

### Nível 2 — Intermediário

**6.** Calcule $\frac{8{,}4 \times 10^7}{2{,}1 \times 10^{-3}}$.

$$ \frac{8{,}4}{2{,}1} \times 10^{7-(-3)} = 4{,}0 \times 10^{10} $$

**Resposta:** $4{,}0 \times 10^{10}$.

**7.** Some $4{,}5 \times 10^3 + 2{,}3 \times 10^2$ e escreva em notação científica.

$$ 4{,}5 \times 10^3 = 45 \times 10^2 $$
$$ 45 \times 10^2 + 2{,}3 \times 10^2 = 47{,}3 \times 10^2 = 4{,}73 \times 10^3 $$

**Resposta:** $4{,}73 \times 10^3$.

**8.** A massa de um próton é $1{,}67 \times 10^{-27}$ kg. A massa de um elétron é $9{,}11 \times 10^{-31}$ kg. Quantas vezes um próton é mais massivo que um elétron?

$$ \frac{1{,}67 \times 10^{-27}}{9{,}11 \times 10^{-31}} = \frac{1{,}67}{9{,}11} \times 10^{4} \approx 0{,}183 \times 10^4 = 1{,}83 \times 10^3 $$

**Resposta:** Aproximadamente $1{,}83 \times 10^3$ vezes (ou ~1830 vezes).

**9.** A distância Terra-Lua é $3{,}84 \times 10^8$ m. A distância Terra-Sol é $1{,}50 \times 10^{11}$ m. Quantas vezes a distância Terra-Sol é maior que a Terra-Lua?

$$ \frac{1{,}50 \times 10^{11}}{3{,}84 \times 10^8} = \frac{1{,}50}{3{,}84} \times 10^3 \approx 0{,}391 \times 10^3 = 3{,}91 \times 10^2 $$

**Resposta:** Aproximadamente $3{,}91 \times 10^2$ vezes (ou ~391 vezes).

**10.** Escreva a velocidade da luz ($299792458$ m/s) em notação científica com 3 algarismos significativos.

$$ 2{,}998 \times 10^8 \approx 3{,}00 \times 10^8 \text{ m/s} $$

**Resposta:** $3{,}00 \times 10^8$ m/s.

### Nível 3 — Desafio

**11.** A população mundial é cerca de $8{,}0 \times 10^9$ pessoas. Se cada pessoa recebesse $1{,}0 \times 10^6$ dólares (1 milhão), qual seria o total em notação científica? Compare com o PIB mundial (~$1{,}0 \times 10^{14}$ dólares).

$$ 8{,}0 \times 10^9 \times 1{,}0 \times 10^6 = 8{,}0 \times 10^{15} \text{ dólares} $$

Comparação: $8{,}0 \times 10^{15} > 1{,}0 \times 10^{14}$ (80 vezes maior que o PIB mundial!)

**Resposta:** $8{,}0 \times 10^{15}$ dólares. Seria 80 vezes o PIB mundial — impossível!

**12.** O átomo de hidrogênio tem raio de $5{,}29 \times 10^{-11}$ m. Seu núcleo (próton) tem raio de $8{,}4 \times 10^{-16}$ m. Qual a razão entre o raio do átomo e o raio do núcleo? Quantos núcleos caberiam lado a lado no diâmetro do átomo?

$$ \frac{5{,}29 \times 10^{-11}}{8{,}4 \times 10^{-16}} = \frac{5{,}29}{8{,}4} \times 10^5 \approx 0{,}63 \times 10^5 = 6{,}3 \times 10^4 $$

Diâmetro do átomo = $2 \times 5{,}29 \times 10^{-11} = 1{,}058 \times 10^{-10}$ m.
Diâmetro do núcleo = $2 \times 8{,}4 \times 10^{-16} = 1{,}68 \times 10^{-15}$ m.

$$ \frac{1{,}058 \times 10^{-10}}{1{,}68 \times 10^{-15}} = \frac{1{,}058}{1{,}68} \times 10^5 \approx 0{,}63 \times 10^5 = 6{,}3 \times 10^4 $$

**Resposta:** Razão de raio ≈ $6{,}3 \times 10^4$. Caberiam ~$6{,}3 \times 10^4$ núcleos no diâmetro do átomo.

**13.** A luz do Sol leva cerca de 8 minutos e 20 segundos para chegar à Terra. A velocidade da luz é $3{,}00 \times 10^8$ m/s. Calcule a distância Terra-Sol em km e em notação científica.

$$ 8 \text{ min } 20 \text{ s} = 8 \times 60 + 20 = 500 \text{ s} $$
$$ d = v \times t = 3{,}00 \times 10^8 \times 500 = 1500 \times 10^8 = 1{,}50 \times 10^{11} \text{ m} $$
$$ = 1{,}50 \times 10^8 \text{ km} $$

**Resposta:** $1{,}50 \times 10^{11}$ m ou $1{,}50 \times 10^8$ km.

---
**Fim — Notação Científica**
