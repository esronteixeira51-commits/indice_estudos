# Algoritmos de Divisão

## Algoritmo Tradicional (Longa)

**Exemplo:** $735 \div 28$

### Passo a Passo

1. Monte a divisão:

```
    _____
28 | 735
```

2. Divida as **centenas** (ou o menor agrupamento possível):
   - $73 \div 28$: o maior múltiplo de 28 que não excede 73 é $2 \times 28 = 56$.
   - Escreva **2** no quociente (acima das dezenas).

```
      2___
28 | 735
     56
     ---
     17
```

3. **Baixe** o próximo dígito (5) ao lado do resto parcial:

```
      2___
28 | 735
     56
     ---
     175
```

4. Divida **175** por 28:
   - $6 \times 28 = 168$.
   - Escreva **6** no quociente (acima das unidades).

```
      26
28 | 735
     56
     ---
     175
     168
     ----
       7
```

5. **Resto final:** 7 (que é menor que 28, como deve ser).

**Resultado:** $735 \div 28 = 26$ resto $7$

**Verificação:** $28 \times 26 + 7 = 728 + 7 = 735$ ✅

## Divisão por Estimativa

$$ 735 \div 28 \approx 700 \div 28 = 25 $$

Ajuste: $28 \times 25 = 700$, resto 35. $35 \div 28 = 1$ resto 7. Total: $26$ resto $7$.

## Divisão com Números Decimais

Transformar em números inteiros:

$$ 7{,}35 \div 0{,}28 = \frac{735}{100} \div \frac{28}{100} = 735 \div 28 = 26{,}25 $$

## Dicas
- Estime antes de calcular.
- Verifique sempre: $divisor \times quociente + resto = dividendo$.
- O resto deve ser sempre menor que o divisor.

---
**Próximo:** [Problemas](Problemas.md)
