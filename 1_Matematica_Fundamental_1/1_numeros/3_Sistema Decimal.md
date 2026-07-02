# Sistema Decimal

O **sistema decimal** (ou sistema de base 10) é o método que usamos para representar números, baseado em **dez algarismos** e na **posição** de cada algarismo no número. É o sistema mais usado no mundo e foi uma das maiores conquistas da matemática.

## Características do Sistema Decimal

### Base 10
O sistema decimal é de **base 10** porque usa **dez símbolos** (0, 1, 2, 3, 4, 5, 6, 7, 8, 9) e cada posição vale **dez vezes** a posição anterior.

### Valor Posicional
Cada algarismo tem um valor que depende de sua **posição** no número. Isso permite escrever números enormes com apenas dez símbolos.

## Ordem de Grandeza (Classes)

Os números são organizados em **ordens** (de direita para esquerda):

| Ordem | Valor | Exemplo no número 4.321 |
|-------|-------|------------------------|
| Unidade | 1 | 1 |
| Dezena | 10 | 20 |
| Centena | 100 | 300 |
| Unidade de milhar | 1.000 | 4.000 |
| Dezena de milhar | 10.000 | — |
| Centena de milhar | 100.000 | — |
| Unidade de milhão | 1.000.000 | — |

## Classes e Períodos

No sistema brasileiro, agrupamos as ordens em **classes** de três em três:

```
1.234.567.890
│   │   │   │
│   │   │   └── Unidade simples
│   │   └── Classe dos milhares
│   └── Classe dos milhões
└── Classe dos bilhões
```

### Tabela de Classes

| Classe | 1ª ordem | 2ª ordem | 3ª ordem |
|--------|----------|----------|----------|
| **Unidades** | unidade | dezena | centena |
| **Milhares** | unidade de milhar | dezena de milhar | centena de milhar |
| **Milhões** | unidade de milhão | dezena de milhão | centena de milhão |
| **Bilhões** | unidade de bilhão | dezena de bilhão | centena de bilhão |

## Exemplo Completo

Analisando o número **45.678**:

| Posição | Algarismo | Valor |
|---------|-----------|-------|
| Dezena de milhar | 4 | 40.000 |
| Unidade de milhar | 5 | 5.000 |
| Centena | 6 | 600 |
| Dezena | 7 | 70 |
| Unidade | 8 | 8 |

$$ 45.678 = 40.000 + 5.000 + 600 + 70 + 8 $$

## Decomposição Polinomial

Todo número pode ser decomposto como soma de potências de 10:

$$ 45.678 = 4 \times 10^4 + 5 \times 10^3 + 6 \times 10^2 + 7 \times 10^1 + 8 \times 10^0 $$

$$ 45.678 = 4 \times 10.000 + 5 \times 1.000 + 6 \times 100 + 7 \times 10 + 8 \times 1 $$

## Outros Sistemas de Numeração (Curiosidade)

| Sistema | Base | Algarismos usados | Uso |
|---------|------|-------------------|-----|
| **Decimal** | 10 | 0-9 | Cotidiano |
| **Binário** | 2 | 0, 1 | Computadores |
| **Hexadecimal** | 16 | 0-9, A-F | Programação |
| **Octal** | 8 | 0-7 | Sistemas Unix antigos |
| **Romano** | — | I, V, X, L, C, D, M | Numeração tradicional |

**Exemplo:** O número 5 em diferentes sistemas:
- Decimal: 5
- Binário: 101
- Hexadecimal: 5
- Romano: V

## Problemas

### Nível 1 — Básico

**1.** Quantas dezenas tem o número 80?

**Resposta:** 8 dezenas.

**2.** Qual a classe do algarismo 7 no número 7.456?

**Resposta:** Classe dos milhares (unidade de milhar).

### Nível 2 — Intermediário

**3.** Decomponha o número 3.502 usando as ordens:

$$ 3.502 = 3.000 + 500 + 0 + 2 $$

**4.** Escreva por extenso: 23.045

**Resposta:** Vinte e três mil e quarenta e cinco.

### Nível 3 — Desafio

**5.** Qual é o menor número de 5 algarismos diferentes que pode ser formado?

**Resposta:** 10.234 (zero não pode ser o primeiro algarismo).

**6.** Se no número 2.345 trocarmos o algarismo das centenas com o das unidades, qual número teremos?

**Resposta:** 2.543.

---
**Próximo:** [Valor Posicional](4_Valor%20Posicional.md)
