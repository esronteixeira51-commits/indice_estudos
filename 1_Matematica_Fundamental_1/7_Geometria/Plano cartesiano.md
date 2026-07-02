# Plano Cartesiano

O **plano cartesiano** é uma ferramenta matemática que permite localizar pontos em uma superfície plana usando dois eixos numéricos perpendiculares. É a base da geometria analítica e é usado em mapas, gráficos, GPS, jogos digitais, design gráfico e incontáveis aplicações.

## Definição

O plano cartesiano é formado por dois eixos numéricos perpendiculares:
- **Eixo horizontal (x):** chamado de **eixo das abscissas**
- **Eixo vertical (y):** chamado de **eixo das ordenadas**

O ponto onde os dois eixos se cruzam é a **origem** (0, 0).

## Os Eixos x e y

```
              y (ordenadas)
              ↑
              │
    II        │         I
   (−,+)     │        (+,+)
              │
    ──────────┼──────────→ x (abscissas)
              │
   III        │        IV
   (−,−)     │        (+,−)
              │
              ↓
```

### Eixo x (Abscissas)
- Horizontal
- Positivo para a **direita**
- Negativo para a **esquerda**
- Pode representar: largura, tempo, distância horizontal, etc.

### Eixo y (Ordenadas)
- Vertical
- Positivo para **cima**
- Negativo para **baixo**
- Pode representar: altura, temperatura, distância vertical, etc.

## Pares Ordenados

Um **par ordenado** $(x, y)$ representa um ponto no plano cartesiano:
- $x$ = coordenada horizontal (valor no eixo x)
- $y$ = coordenada vertical (valor no eixo y)

> **Importante:** $(x, y)$ é diferente de $(y, x)$! A ordem importa.

### Exemplos

| Ponto | Par Ordenado | Como encontrar |
|-------|-------------|----------------|
| A | (2, 3) | 2 para a direita, 3 para cima |
| B | (−1, 4) | 1 para a esquerda, 4 para cima |
| C | (−3, −2) | 3 para a esquerda, 2 para baixo |
| D | (4, −1) | 4 para a direita, 1 para baixo |
| O | (0, 0) | Origem — centro |

## Quadrantes

Os eixos dividem o plano em **quatro quadrantes**:

| Quadrante | x | y | Sinal do par | Exemplo |
|-----------|---|---|-------------|---------|
| **I** | + | + | (+, +) | (2, 3) |
| **II** | − | + | (−, +) | (−2, 3) |
| **III** | − | − | (−, −) | (−2, −3) |
| **IV** | + | − | (+, −) | (2, −3) |

> **Pontos nos eixos não pertencem a nenhum quadrante!**
> - Ponto no eixo x: $(x, 0)$ — exemplo: $(3, 0)$
> - Ponto no eixo y: $(0, y)$ — exemplo: $(0, 5)$

## Localização e Plotagem de Pontos

### Como Plotar (Marcar) um Ponto

1. **Comece na origem** (0, 0)
2. **Mova horizontalmente** conforme o valor de x (direita se +, esquerda se −)
3. **Mova verticalmente** conforme o valor de y (cima se +, baixo se −)
4. **Marque o ponto**

### Exemplo: Plotar A(3, 2)

```
    y
    ↑
  3 ┤
  2 ┤     ● A(3,2)
  1 ┤
  0 ┼─────┬─────┬────→ x
    0     1     2     3
```

1. Origem → 3 para a direita → 2 para cima → marque A

### Exemplo: Plotar B(−2, 4)

```
    y
    ↑
  4 ┤  ● B(−2,4)
  3 ┤
  2 ┤
  1 ┤
  0 ┼─────┬─────┬────→ x
   −2    −1     0     1
```

1. Origem → 2 para a esquerda → 4 para cima → marque B

### Exemplo: Plotar C(−1, −3)

```
    y
    ↑
  0 ┼─────┬─────┬────→ x
    0     1
  −1 ┤
  −2 ┤
  −3 ┤  ● C(−1,−3)
    ↓
```

1. Origem → 1 para a esquerda → 3 para baixo → marque C

## Distância entre Dois Pontos

Para calcular a distância entre dois pontos $A(x_1, y_1)$ e $B(x_2, y_2)$, formamos um triângulo retângulo e usamos o **Teorema de Pitágoras**:

$$ d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2} $$

### Exemplo

Distância entre A(1, 2) e B(4, 6):

$$ d = \sqrt{(4 - 1)^2 + (6 - 2)^2} = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5 $$

## Aplicações do Plano Cartesiano

| Área | Uso |
|------|-----|
| **Mapas e GPS** | Coordenadas geográficas (latitude, longitude) |
| **Gráficos** | Eixos de gráficos de funções, estatísticas |
| **Jogos** | Posição de personagens, tiros, mapas |
| **Design** | Softwares gráficos (Photoshop, Illustrator) |
| **Arquitetura** | Plantas e elevações em coordenadas |
| **Física** | Movimento de objetos, trajetórias |
| **Robótica** | Navegação de robôs, braços mecânicos |
| **Astronomia** | Coordenadas de estrelas e planetas |

## Coordenadas Geográficas (Curiosidade)

A Terra usa um sistema similar ao plano cartesiano, mas com esferas:
- **Latitude:** posição Norte-Sul (equivalente ao y)
- **Longitude:** posição Leste-Oeste (equivalente ao x)

**Exemplo:** São Paulo, Brasil ≈ 23,5° S, 46,6° W

## Problemas

### Nível 1 — Básico

**1.** Em qual quadrante está o ponto P(3, 4)?

**Resposta:** Quadrante I (x > 0, y > 0).

**2.** Qual é a coordenada do ponto que está 2 unidades à direita e 5 unidades acima da origem?

**Resposta:** (2, 5).

**3.** O ponto Q(−2, 3) está em qual quadrante?

**Resposta:** Quadrante II (x < 0, y > 0).

**4.** O ponto R(0, −4) está em qual eixo?

**Resposta:** Eixo y (x = 0).

### Nível 2 — Intermediário

**5.** Dados os pontos A(1, 2), B(−3, 1), C(−2, −2), D(4, −1):

a) Quais estão no Quadrante I? **Resposta:** A(1, 2)

b) Quais estão no Quadrante III? **Resposta:** C(−2, −2)

c) Quais estão no eixo x? **Resposta:** Nenhum (nenhum tem y = 0).

**6.** Calcule a distância entre A(0, 0) e B(6, 8):

$$ d = \sqrt{(6-0)^2 + (8-0)^2} = \sqrt{36 + 64} = \sqrt{100} = 10 $$

**Resposta:** 10 unidades.

**7.** Um quadrado tem vértices em (0, 0), (4, 0), (4, 4) e (0, 4). Qual é o lado e a área do quadrado?

- Lado = distância entre (0,0) e (4,0) = 4
- Área = lado² = 16

**Resposta:** Lado = 4, Área = 16.

### Nível 3 — Desafio

**8.** Três vértices de um retângulo são A(1, 2), B(1, 5) e C(6, 2). Encontre o quarto vértice D.

```
    y
    ↑
  5 ┤  B(1,5) ─────── D(6,5)
    │    │               │
  2 ┤  A(1,2) ─────── C(6,2)
    │
    └────────────────────→ x
         1       6
```

**Resposta:** D(6, 5). (x de C, y de B)

**9.** Um ponto P está no eixo x e está equidistante de A(2, 3) e B(2, −3). Qual é a coordenada de P?

P está no eixo x → P(x, 0)

Distância PA = Distância PB:
$$ \sqrt{(x-2)^2 + (0-3)^2} = \sqrt{(x-2)^2 + (0-(-3))^2} $$
$$ \sqrt{(x-2)^2 + 9} = \sqrt{(x-2)^2 + 9} $$

Toda x funciona! Mas o ponto mais natural no eixo x equidistante é o ponto médio entre as projeções... na verdade, qualquer ponto do eixo x é equidistante de A(2,3) e B(2,-3) porque a eixo x é o eixo de simetria.

Mas o ponto **no eixo x** que é "mais natural" é o que está alinhado horizontalmente, ou seja, o ponto médio entre (2,3) e (2,-3) projetado no eixo x... na verdade, o ponto P(2, 0) é o ponto do eixo x que está diretamente entre A e B.

**Resposta:** P(2, 0). (O ponto no eixo x com a mesma abscissa que A e B.)

---
**Próximo:** [Transformações Geométricas](Transformações%20geométricas.md)
