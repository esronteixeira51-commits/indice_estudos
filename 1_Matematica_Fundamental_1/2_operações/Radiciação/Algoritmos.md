# Algoritmos de Radiciação

## Método da Fatoração (Para Raízes Exatas)

**Exemplo:** $\sqrt{784}$

### Passo a Passo

1. **Fatore o radicando** em fatores primos:

$$ 784 = 2 \times 392 = 2^2 \times 196 = 2^4 \times 49 = 2^4 \times 7^2 $$

2. **Separe em pares** (para raiz quadrada, ou grupos de $n$ para raiz $n$-ésima):

$$ \sqrt{2^4 \times 7^2} = \sqrt{(2^2)^2 \times 7^2} $$

3. **Extraia** um fator de cada par:

$$ 2^2 \times 7 = 4 \times 7 = 28 $$

**Resultado:** $\sqrt{784} = 28$

## Verificação por Potenciação

$$ 28^2 = 784 \text{ (verificado!)} $$

## Algoritmo da Divisão Sucessiva

Dividir por primos até chegar a 1:

$$ 784 \div 2 = 392 $$
$$ 392 \div 2 = 196 $$
$$ 196 \div 2 = 98 $$
$$ 98 \div 2 = 49 $$
$$ 49 \div 7 = 7 $$
$$ 7 \div 7 = 1 $$

Resultado: $2^4 \times 7^2$.

## Estimativa para Raízes Não Exatas

**Exemplo:** $\sqrt{50}$

$$ 7^2 = 49 \text{ e } 8^2 = 64 $$

Logo: $\sqrt{50} \approx 7{,}07$ (pois está muito próximo de 49).

## Dicas
- Memorize quadrados perfeitos até 20: $1, 4, 9, 16, 25, 36, 49, 64, 81, 100, 121, 144, 169, 196, 225, 256, 289, 324, 361, 400$.
- Cubos perfeitos: $1, 8, 27, 64, 125, 216, 343, 512, 729, 1000$.

---
**Próximo:** [Problemas](Problemas.md)
