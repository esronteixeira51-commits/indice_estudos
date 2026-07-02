# Arredondamento

O **arredondamento** é a operação de aproximar um número para um valor mais simples, de acordo com uma regra pré-estabelecida. É usado constantemente na vida real: em compras, medições, estatísticas, finanças e ciência.

## Regras de Arredondamento

### Regra Principal

Para arredondar um número para uma determinada ordem (unidade, dezena, centena...), observe o algarismo **imediatamente à direita** da ordem desejada:

- Se for **0, 1, 2, 3, 4** → mantém o algarismo da ordem e zera os seguintes (arredondamento **para baixo**)
- Se for **5, 6, 7, 8, 9** → aumenta em 1 o algarismo da ordem e zera os seguintes (arredondamento **para cima**)

## Arredondamento para a Unidade (Número Inteiro)

**Exemplo:** Arredondar 47,3 para a unidade
- Algarismo da unidade: 7
- Algarismo à direita: 3 (menor que 5)
- **Resultado: 47**

**Exemplo:** Arredondar 47,8 para a unidade
- Algarismo da unidade: 7
- Algarismo à direita: 8 (maior ou igual a 5)
- **Resultado: 48**

## Arredondamento para a Dezena

**Exemplo:** Arredondar 234 para a dezena
- Algarismo da dezena: 3
- Algarismo à direita: 4 (menor que 5)
- **Resultado: 230**

**Exemplo:** Arredondar 237 para a dezena
- Algarismo da dezena: 3
- Algarismo à direita: 7 (maior ou igual a 5)
- **Resultado: 240**

## Arredondamento para a Centena

**Exemplo:** Arredondar 4.567 para a centena
- Algarismo da centena: 5
- Algarismo à direita: 6 (maior ou igual a 5)
- **Resultado: 4.600**

**Exemplo:** Arredondar 4.543 para a centena
- Algarismo da centena: 5
- Algarismo à direita: 4 (menor que 5)
- **Resultado: 4.500**

## Arredondamento para o Milhar

**Exemplo:** Arredondar 12.456 para o milhar
- Algarismo do milhar: 2
- Algarismo à direita: 4 (menor que 5)
- **Resultado: 12.000**

**Exemplo:** Arredondar 12.567 para o milhar
- Algarismo do milhar: 2
- Algarismo à direita: 5 (maior ou igual a 5)
- **Resultado: 13.000**

## Arredondamento de Números Decimais

**Exemplo:** Arredondar 3,14159 para:

- 1 casa decimal: 3,1 (próximo algarismo é 4)
- 2 casas decimais: 3,14 (próximo algarismo é 1)
- 3 casas decimais: 3,142 (próximo algarismo é 5)
- 4 casas decimais: 3,1416 (próximo algarismo é 9)

## Caso Especial: Arredondamento com 5

Quando o algarismo à direita é exatamente **5**, arredondamos para cima:

- 2,5 → 3
- 4,5 → 5
- 12,5 → 13

> **Nota:** Alguns contextos científicos usam o "arredondamento para o par mais próximo" (2,5 → 2, 3,5 → 4), mas no ensino fundamental adotamos a regra padrão: 5 ou mais, arredonda para cima.

## Aplicações do Arredondamento

- **Preços:** R$ 4,99 é psicologicamente "R$ 4" (arredondamento mental)
- **Medições:** uma mesa de 1,47 m pode ser "aproximadamente 1,5 m"
- **População:** "cerca de 10 milhões de habitantes"
- **Notas:** média 7,45 → 7,5 (arredondamento escolar)
- **Câmbio:** dólar a R$ 5,1234 → R$ 5,12

## Problemas

### Nível 1 — Básico

**1.** Arredonde 47 para a dezena.

**Resposta:** 50 (algarismo à direita da dezena é 7 ≥ 5).

**2.** Arredonde 3,24 para 1 casa decimal.

**Resposta:** 3,2 (próximo algarismo é 4 < 5).

**3.** Arredonde 1.234 para a centena.

**Resposta:** 1.200 (próximo algarismo da centena é 3 < 5).

### Nível 2 — Intermediário

**4.** Arredonde 8.765 para o milhar.

**Resposta:** 9.000 (algarismo do milhar é 8, próximo é 7 ≥ 5, então 8+1=9).

**5.** Arredonde 2,71828 para 2 casas decimais.

**Resposta:** 2,72 (terceira casa é 8 ≥ 5).

**6.** Arredonde 45.678 para a centena.

**Resposta:** 45.700 (próximo algarismo da centena é 7 ≥ 5).

### Nível 3 — Desafio

**7.** Arredonde 999 para a dezena.

- 999 → 9 centenas, 9 dezenas, 9 unidades
- Dezena é 9, unidade é 9 ≥ 5 → dezena vira 10, sobe para centena
- Centena era 9, vira 10 → 1.000

**Resposta:** 1.000.

**8.** Um terreno mede 12.456 m². Arredonde para a centena mais próxima e para o milhar mais próximo. Qual diferença entre os dois arredondamentos?

- Centena: 12.500 m²
- Milhar: 12.000 m²
- Diferença: 12.500 − 12.000 = 500 m²

**Resposta:** 500 m².

---
**Próximo:** [Estimativa](13_estimativa.md)
