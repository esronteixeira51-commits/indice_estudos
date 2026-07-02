# Algoritmos de Adição

## Algoritmo Tradicional (Por Ordem de Grandeza)

**Exemplo:** $456 + 378$

### Passo a Passo

1. Alinhe os números pela **ordem de grandeza** (unidades, dezenas, centenas):

```
  456
+ 378
-----
```

2. Some as **unidades**:
   $$ 6 + 8 = 14 $$
   Escreva **4**, e **vai 1** para as dezenas.

3. Some as **dezenas** (com o "vai 1"):
   $$ 5 + 7 + 1 = 13 $$
   Escreva **3**, e **vai 1** para as centenas.

4. Some as **centenas** (com o "vai 1"):
   $$ 4 + 3 + 1 = 8 $$
   Escreva **8**.

```
  ¹¹
  456
+ 378
-----
  834
```

**Resultado:** $456 + 378 = 834$

## Adição com Decomposição

$$ 456 + 378 = (400 + 50 + 6) + (300 + 70 + 8) $$
$$ = (400 + 300) + (50 + 70) + (6 + 8) $$
$$ = 700 + 120 + 14 = 834 $$

## Adição com Arredondamento

$$ 456 + 378 = 456 + 400 - 22 = 856 - 22 = 834 $$

## Dicas
- Sempre comece pela direita (unidades).
- O "vai 1" (transporte) é fundamental para o resultado correto.
- Verifique com a subtração: $834 - 378 = 456$.

---
**Próximo:** [Problemas](Problemas.md)
