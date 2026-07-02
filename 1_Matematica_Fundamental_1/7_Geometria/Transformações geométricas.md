# Transformações Geométricas

As **transformações geométricas** são operações que movem, giram, refletem ou alteram figuras no plano ou no espaço. As três transformações fundamentais do ensino fundamental são a **reflexão** (espelho), a **translação** (deslizamento) e a **rotação** (giro). Elas preservam o tamanho e a forma das figuras — apenas mudam sua posição ou orientação.

## Tipos de Transformações Isométricas

Transformações **isométricas** (ou congruências) preservam:
- Comprimento dos lados
- Medida dos ângulos
- Área
- Perímetro

Ou seja, a figura original e a transformada são **congruentes** (idênticas em forma e tamanho).

## 1. Reflexão (Simetria Axial)

A **reflexão** é como olhar para uma figura em um **espelho**. A figura é "virada" para o outro lado de uma linha (eixo de reflexão).

### Características
- A figura é **espelhada** em relação a um eixo
- Cada ponto e sua imagem estão à **mesma distância** do eixo
- O eixo de reflexão é a **mediatriz** do segmento que une um ponto e sua imagem
- A figura é **invertida** (direita vira esquerda, esquerda vira direita)

### Reflexão no Eixo x

$(x, y) \rightarrow (x, -y)$

```
    y
    ↑
    │    A(2,3) ──────→ A'(2,−3)
    │      ●              ●
    │
───┼───→ x
    │
    │
    ↓
```

### Reflexão no Eixo y

$(x, y) \rightarrow (-x, y)$

```
    y
    ↑
    │   B'(−3,2) ←────── B(3,2)
    │      ●              ●
    │
───┼───→ x
```

### Reflexão na Origem (Ponto)

$(x, y) \rightarrow (-x, -y)$

Equivalente a duas reflexões: uma no eixo x e outra no eixo y.

### Reflexão na Vida Real

- Espelho: sua imagem refletida
- Água calma: reflexão de montanhas e árvores
- Letras: "A" refletida horizontalmente vira uma forma simétrica
- Dança: movimentos simétricos entre dois dançarinos

## 2. Translação (Deslizamento)

A **translação** é o **deslizamento** de uma figura sem girar ou espelhar. Todos os pontos da figura se movem na **mesma direção** e pela **mesma distância**.

### Características
- A figura "desliza" para outra posição
- Todos os pontos se movem pelo **mesmo vetor** (mesma direção, mesma distância)
- Não há rotação nem espelhamento
- A figura fica na **mesma orientação** (cima continua sendo cima)

### Translação no Plano Cartesiano

$(x, y) \rightarrow (x + a, y + b)$

Onde $a$ = deslocamento horizontal, $b$ = deslocamento vertical.

### Exemplo

Transladar o triângulo ABC 4 unidades para a direita e 2 unidades para cima:

- A(1, 1) → A'(5, 3)
- B(3, 1) → B'(7, 3)
- C(2, 3) → C'(6, 5)

```
    y
    ↑
  5 ┤           C'(6,5)
  4 ┤
  3 ┤    C(2,3)     A'(5,3) B'(7,3)
  2 ┤
  1 ┤    A(1,1) B(3,1)
  0 ┼─────┬─────┬─────┬─────┬────→ x
    0     1     2     3     4     5
```

### Translação na Vida Real

- Elevador: movimento vertical de translação
- Escada rolante: translação inclinada
- Carro em linha reta: translação horizontal
- Peças de xadrez movendo-se em linha reta (torre, raina)
- Arrastar uma janela na tela do computador

## 3. Rotação (Giro)

A **rotação** é o **giro** de uma figura em torno de um ponto fixo (centro de rotação) por um determinado ângulo.

### Características
- A figura **gira** em torno de um ponto fixo
- Todos os pontos se movem em **círculos** ao redor do centro
- O centro de rotação pode estar **dentro** ou **fora** da figura
- A figura pode girar no **sentido horário** ou **anti-horário**

### Ângulos Comuns de Rotação

| Ângulo | Sentido | Resultado |
|--------|---------|-----------|
| 90° | Anti-horário | Um quarto de volta |
| 180° | Anti-horário | Meia volta (ponta-cabeça) |
| 270° | Anti-horário | Três quartos de volta |
| 360° | Qualquer | Volta completa (figura original) |

> **Dica:** Sentido anti-horário = positivo. Sentido horário = negativo.

### Rotação na Origem (0, 0)

- **90° anti-horário:** $(x, y) \rightarrow (-y, x)$
- **180°:** $(x, y) \rightarrow (-x, -y)$
- **270° anti-horário (ou 90° horário):** $(x, y) \rightarrow (y, -x)$

### Exemplo: Rotação de 90° Anti-horário

Ponto A(3, 1) rotacionado 90° em torno da origem:

$$ A(3, 1) \rightarrow A'(-1, 3) $$

```
    y
    ↑
  3 ┤     A'(−1,3)
  2 ┤
  1 ┤         A(3,1)
  0 ┼─────┬─────┬────→ x
   −1     0     1     2     3
```

### Exemplo: Rotação de 180°

Ponto B(2, 3) rotacionado 180° em torno da origem:

$$ B(2, 3) \rightarrow B'(-2, -3) $$

### Rotação na Vida Real

- Ponteiros do relógio: rotação em torno do centro
- Parafuso: rotação combinada com translação
- Máquina de lavar: rotação do cesto
- Tombo (cambalhota): rotação de 360° do corpo
- Girar a chave na fechadura: rotação de ~90°
- Ventilador: rotação contínua das pás
- Planeta Terra: rotação de 360° em ~24h

## Composição de Transformações

Transformações podem ser combinadas:

1. **Translação + Translação** = outra translação
2. **Reflexão + Reflexão** (eixos paralelos) = translação
3. **Reflexão + Reflexão** (eixos que se cruzam) = rotação
4. **Rotação + Rotação** (mesmo centro) = outra rotação

## Transformações vs. Propriedades

| Propriedade | Reflexão | Translação | Rotação |
|-------------|----------|------------|---------|
| Preserva comprimentos | ✅ Sim | ✅ Sim | ✅ Sim |
| Preserva ângulos | ✅ Sim | ✅ Sim | ✅ Sim |
| Preserva área | ✅ Sim | ✅ Sim | ✅ Sim |
| Preserva orientação | ❌ Não | ✅ Sim | ✅ Sim |
| Preserva coordenadas (x,y) | ❌ Não | ❌ Não | ❌ Não |
| Inverte "direita/esquerda" | ✅ Sim | ❌ Não | ❌ Não |

## Identificando Transformações

| Característica | Qual transformação? |
|----------------|---------------------|
| Figura "virada" como espelho | Reflexão |
| Figura deslizou, mesma orientação | Translação |
| Figura girou, mesma orientação relativa | Rotação |
| Figura "de cabeça para baixo" | Rotação 180° ou Reflexão dupla |
| Figura e imagem são idênticas e paralelas | Translação |

## Problemas

### Nível 1 — Básico

**1.** O que acontece com um ponto (3, 4) quando refletido no eixo x?

**Resposta:** Vira (3, −4).

**2.** Um ponto (2, 5) é transladado 3 unidades para a direita e 1 unidade para baixo. Qual a nova coordenada?

**Resposta:** (2 + 3, 5 − 1) = (5, 4).

**3.** O que é uma rotação de 360°?

**Resposta:** A figura volta à posição original — uma volta completa.

### Nível 2 — Intermediário

**4.** Reflete o ponto (−2, 3) no eixo y e depois no eixo x. Qual a coordenada final?

- Reflexão no eixo y: (−2, 3) → (2, 3)
- Reflexão no eixo x: (2, 3) → (2, −3)

**Resposta:** (2, −3).

**5.** Um triângulo com vértices A(1,1), B(3,1), C(2,3) é rotacionado 180° em torno da origem. Quais as novas coordenadas?

- A(1,1) → A'(−1,−1)
- B(3,1) → B'(−3,−1)
- C(2,3) → C'(−2,−3)

**Resposta:** A'(−1,−1), B'(−3,−1), C'(−2,−3).

**6.** Qual transformação leva o ponto (4, 2) ao ponto (4, 6)?

- x permanece 4, y aumenta de 2 para 6

**Resposta:** Translação de 4 unidades para cima (0, +4).

### Nível 3 — Desafio

**7.** Um quadrado tem vértices em (1,1), (3,1), (3,3), (1,3). Após uma reflexão no eixo y, qual a área do novo quadrado? E se for uma rotação de 90° em torno da origem?

- Reflexão no eixo y: (−1,1), (−3,1), (−3,3), (−1,3). Lado = 2. Área = **4**.
- Rotação 90°: (1,1)→(−1,1), (3,1)→(−1,3), (3,3)→(−3,3), (1,3)→(−3,1). Lado = 2. Área = **4**.

> As transformações isométricas preservam a área!

**Resposta:** Área = 4 em ambos os casos.

**8.** Um ponto P está a 5 unidades da origem. Após uma rotação de 90° em torno da origem, a que distância P' está da origem? E após uma reflexão no eixo x? E após uma translação de (3, 4)?

- Rotação: distância preservada → **5**
- Reflexão: distância preservada → **5**
- Translação: a distância da origem muda! P'(x+3, y+4). Se P era (5, 0), P' é (8, 4). Distância = $\sqrt{8^2 + 4^2} = \sqrt{80} = 4\sqrt{5} \approx 8.94$.

**Resposta:** Rotação: 5; Reflexão: 5; Translação: varia (não preserva distância à origem, mas preserva tamanho da figura).

---
**Fim — Transformações Geométricas**
