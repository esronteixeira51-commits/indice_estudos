# Algoritmos de Subtração

## Algoritmo Tradicional (Com Empréstimo)

**Exemplo:** $523 - 267$

### Passo a Passo

1. Alinhe os números pela ordem de grandeza:

```
  523
- 267
-----
```

2. Subtraia as **unidades**:
   $$ 3 - 7 $$
   Não é possível! Pede-se emprestado **1 dezena** (10 unidades).
   $$ 13 - 7 = 6 $$

3. Subtraia as **dezenas**:
   Agora temos $1$ (em vez de 2) na casa das dezenas.
   $$ 1 - 6 $$
   Não é possível! Pede-se emprestado **1 centena** (10 dezenas).
   $$ 11 - 6 = 5 $$

4. Subtraia as **centenas**:
   Agora temos $4$ (em vez de 5) na casa das centenas.
   $$ 4 - 2 = 2 $$

```
  4 1 13
  ⁵ ² ³
- 2 6 7
-----
  2 5 6
```

**Resultado:** $523 - 267 = 256$

**Verificação:** $256 + 267 = 523$ ✅

## Método da Adição Complementar

Quanto falta para chegar ao minuendo?

$$ 267 + \square = 523 $$

$$ 267 + 3 = 270 $$
$$ 270 + 30 = 300 $$
$$ 300 + 200 = 500 $$
$$ 500 + 23 = 523 $$

Total: $3 + 30 + 200 + 23 = 256$

## Subtração com Arredondamento

$$ 523 - 267 = 523 - 300 + 33 = 223 + 33 = 256 $$

## Dicas
- Sempre comece pela direita (unidades).
- O "empréstimo" (tira de, aumenta) é o mecanismo central.
- **Verifique sempre** com a adição: $resultado + subtraendo = minuendo$.

---
**Próximo:** [Problemas](Problemas.md)
