# Algoritmos de Multiplicação

## Algoritmo Tradicional (Padrão)

**Exemplo:** $347 \times 26$

### Passo a Passo

1. Alinhe os números:

```
   347
×   26
------
```

2. Multiplique pelo **6** (unidades do multiplicador):
   - $6 \times 7 = 42$ → escreva **2**, vai **4**
   - $6 \times 4 = 24 + 4 = 28$ → escreva **8**, vai **2**
   - $6 \times 3 = 18 + 2 = 20$ → escreva **20**

```
   347
×   26
------
  2082
```

3. Multiplique pelo **2** (dezenas do multiplicador), **adicionando um zero**:
   - $2 \times 7 = 14$ → escreva **4**, vai **1**
   - $2 \times 4 = 8 + 1 = 9$ → escreva **9**
   - $2 \times 3 = 6$ → escreva **6**

```
   347
×   26
------
  2082
  6940
```

4. **Some os resultados parciais**:

```
   347
×   26
------
  2082
+ 6940
------
  9022
```

**Resultado:** $347 \times 26 = 9.022$

## Multiplicação com Decomposição

$$ 347 \times 26 = 347 \times (20 + 6) = 347 \times 20 + 347 \times 6 = 6.940 + 2.082 = 9.022 $$

## Multiplicação com Arredondamento

$$ 347 \times 26 = 347 \times 25 + 347 = 8.675 + 347 = 9.022 $$

## Dicas
- Multiplique de direita para esquerda.
- O zero no segundo produto parcial representa a ordem de grandeza (dezenas).
- Verifique com a divisão: $9.022 \div 26 = 347$.

---
**Próximo:** [Problemas](Problemas.md)
