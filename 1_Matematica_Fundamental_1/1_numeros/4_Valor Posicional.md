# Valor Posicional

O **valor posicional** (ou valor de lugar) é a regra que define que o valor de um algarismo depende da **posição** que ele ocupa no número. Graças a essa propriedade, conseguimos escrever números enormes usando apenas dez algarismos.

## Princípio Fundamental

> **O valor de um algarismo = algarismo × valor da posição (ordem)**

## As Ordens e Seus Valores

Cada posição em um número vale **dez vezes** a posição imediatamente à sua direita:

```
...  100.000   10.000   1.000    100     10      1
...    │         │        │       │       │       │
...    CM       DM       UM      C       D       U
```

| Ordem | Abreviação | Valor | Multiplica por |
|-------|-----------|-------|----------------|
| Centena de milhar | CM | 100.000 | 10⁵ |
| Dezena de milhar | DM | 10.000 | 10⁴ |
| Unidade de milhar | UM | 1.000 | 10³ |
| Centena | C | 100 | 10² |
| Dezena | D | 10 | 10¹ |
| Unidade | U | 1 | 10⁰ |

## Exemplo Detalhado

No número **6.728**:

| Algarismo | Posição | Valor Posicional | Cálculo |
|-----------|---------|------------------|---------|
| 6 | Unidade de milhar | 6.000 | 6 × 1.000 |
| 7 | Centena | 700 | 7 × 100 |
| 2 | Dezena | 20 | 2 × 10 |
| 8 | Unidade | 8 | 8 × 1 |

$$ 6.728 = 6.000 + 700 + 20 + 8 $$

## O Poder do Zero

O algarismo **0** (zero) é essencial no valor posicional. Ele **ocupa um lugar** sem adicionar valor, permitindo que outros algarismos estejam na posição correta.

**Exemplo:** 5.043

- Sem o zero, 5.43 seria 543 (centenas, dezenas, unidades)
- O zero "segura" a posição das centenas, fazendo o 5 valer 5.000 e o 4 valer 40

## Trocando Algarismos de Lugar

Se trocarmos a posição de dois algarismos, o valor do número muda completamente:

- **357** → trocar 3 e 7: **753** (aumentou!)
- **42** → trocar 4 e 2: **24** (diminuiu!)
- **101** → trocar 1 e 0 (do meio): **110** (mudou!)

## Completando com Zeros

Quando movemos um algarismo para a esquerda, ele multiplica o valor por 10. Para manter o valor, adicionamos zeros:

- 5 unidades = 5
- 5 dezenas = 50 (5 × 10)
- 5 centenas = 500 (5 × 100)
- 5 milhares = 5.000 (5 × 1.000)

## Problemas

### Nível 1 — Básico

**1.** No número 842, qual o valor posicional do algarismo 8?

**Resposta:** 8 centenas = 800.

**2.** Qual o valor do algarismo 3 em 3.456?

**Resposta:** 3 milhares = 3.000.

**3.** No número 507, o algarismo 0 tem que valor?

**Resposta:** 0 dezenas = 0 (mas ele ocupa a posição, fazendo o 5 valer 500).

### Nível 2 — Intermediário

**4.** Decomponha o número 9.405 por valor posicional:

$$ 9.405 = 9 \times 1.000 + 4 \times 100 + 0 \times 10 + 5 \times 1 $$

**5.** Qual número é formado por 7 unidades de milhar, 3 centenas e 9 unidades?

**Resposta:** 7.309.

### Nível 3 — Desafio

**6.** No número 56.789, qual a diferença entre o valor posicional do algarismo 7 e o valor posicional do algarismo 9?

- 7 está na centena: 7 × 100 = 700
- 9 está na unidade: 9 × 1 = 9

**Diferença: 700 − 9 = 691.**

**7.** Troque o algarismo das dezenas com o das centenas no número 4.321. Qual o novo número?

**Resposta:** 4.231 (3 centenas e 2 dezenas trocam: 4.231).

---
**Próximo:** [Leitura](5_leitura.md)
