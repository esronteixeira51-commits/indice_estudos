# Gráficos

Os **gráficos** são representações visuais de dados que facilitam a compreensão, comparação e identificação de padrões. Um bom gráfico comunica informações de forma rápida e intuitiva, muitas vezes mais eficientemente que tabelas ou textos.

## Definição

Gráfico é uma representação **visual** de dados numéricos ou categóricos, usando formas geométricas, cores, posições e tamanhos.

## Tipos de Gráficos

### 1. Gráfico de Barras (Colunas)
Usado para comparar valores entre categorias.

- **Barras verticais (colunas):** mais comuns, fáceis de ler
- **Barras horizontais:** melhor para categorias com nomes longos

**Quando usar:** Comparar quantidades entre grupos diferentes.

**Exemplo:** Notas médias por turma

```
Nota
 9 |                                          ████
 8 |                    ████                    ████
 7 |      ████          ████          ████      ████
 6 |      ████          ████          ████      ████
 5 |      ████    ████  ████          ████      ████
   |-----------------------------------------------
      Turma A   Turma B   Turma C   Turma D
```

### 2. Gráfico de Barras Empilhadas
Mostra a composição de cada categoria.

**Exemplo:** População por sexo em cada cidade
- Cada barra = cidade total
- Segmentos = masculino / feminino

### 3. Gráfico de Setores (Pizza)
Mostra a **proporção** de cada parte em relação ao todo.

**Quando usar:** Quando as partes somam 100% e há poucas categorias (idealmente 2-7).

**Exemplo:** Distribuição de gastos mensais

```
         Aluguel 30%
            ████
      ████████████████
    ██  Alimentação   ██
   ██      25%         ██
  ██                    ██
  ██  Transporte 20%    ██
  ██                    ██
   ██   Lazer 15%     ██
    ██   Outros 10%  ██
      ████████████████
```

> **Limite:** Evite pizzas com muitas fatias — fica confuso. Prefira barras se houver mais de 7 categorias.

### 4. Gráfico de Linhas
Mostra a **evolução** de uma variável ao longo do tempo.

**Quando usar:** Dados temporais, tendências, previsões.

**Exemplo:** Temperatura média ao longo dos meses

```
Temp. (°C)
 30 |                              ●
 25 |                    ●        / \
 20 |          ●        / \      /   \
 15 |    ●    / \      /   ●    /     \
 10 |   / \  /   ●    /     \  /       ●
  5 |  /   ●/     \  /       ●/
  0 | ●            ●/
   |--------------------------------
     Jan  Fev  Mar  Abr  Mai  Jun  Jul
```

### 5. Histograma
Semelhante ao gráfico de barras, mas para **dados agrupados em classes** (intervalos). As barras se tocam (sem espaço entre elas).

**Quando usar:** Distribuição de frequências de dados contínuos (altura, peso, salário, notas).

**Exemplo:** Distribuição de alturas

```
Freq.
 10 |       ████
  8 |  ████ ████ ████
  6 |  ████ ████ ████ ████
  4 |  ████ ████ ████ ████ ████
  2 |  ████ ████ ████ ████ ████ ████
   |--------------------------------
     150-155 155-160 160-165 165-170 170-175 175-180
              Altura (cm)
```

> **Diferença crucial:** No histograma, a **área** da barra representa a frequência (não apenas a altura). Se as classes têm tamanhos diferentes, ajuste a altura.

### 6. Gráfico de Dispersão (Scatter Plot)
Mostra a relação entre **duas variáveis quantitativas**.

**Quando usar:** Verificar correlação entre duas grandezas.

**Exemplo:** Horas de estudo vs. Nota na prova

```
Nota
 10 |                    ●
  9 |              ●  ●    ●
  8 |        ●  ●    ●  ●
  7 |     ●    ●  ●
  6 |  ●    ●
  5 | ●
   |------------------------
     1  2  3  4  5  6  7  8
          Horas de estudo
```

> **Tendência:** quanto mais horas de estudo, maior a nota (correlação positiva).

### 7. Pictograma
Usa **imagens ou símbolos** para representar quantidades.

**Quando usar:** Público infantil ou comunicação simples.

**Exemplo:** População de animais em um zoológico

🐘 🐘 🐘 = 3 elefantes
🦒 🦒 🦒 🦒 🦒 = 5 girafas
🦁 🦁 = 2 leões

> **Cuidado:** Símbolos de tamanhos diferentes podem distorcer a percepção.

### 8. Gráfico de Área
Semelhante ao de linhas, mas a área abaixo da linha é preenchida.

**Quando usar:** Enfatizar a magnitude total acumulada.

### 9. Gráfico de Caixa (Box Plot)
Resumo visual da distribuição: mínimo, Q1, mediana, Q3, máximo.

**Quando usar:** Comparar distribuições e identificar outliers.

```
     |----[====|====]----|
    Min  Q1   Med  Q3   Max
```

## Como Escolher o Gráfico Certo

| Objetivo | Melhor Gráfico |
|----------|----------------|
| Comparar categorias | Barras |
| Mostrar proporções do todo | Pizza (até 7 categorias) |
| Mostrar tendência no tempo | Linhas |
| Distribuição de dados contínuos | Histograma |
| Relação entre duas variáveis | Dispersão |
| Comparar distribuições | Caixa (Box Plot) |
| Dados para crianças | Pictograma |

## Elementos de um Gráfico

1. **Título:** descreve o que o gráfico mostra
2. **Eixos:** rotulados com nomes e unidades
3. **Escala:** clara e proporcional
4. **Legenda:** explica cores ou símbolos (se houver)
5. **Fonte:** origem dos dados

## Erros Comuns e Armadilhas

### 1. Escala Enganosa
Iniciar o eixo Y em um valor diferente de zero pode distorcer comparações.

```
Errado:                    Correto:
Vendas                     Vendas
500 | ████                 500 | ████
490 | ████                 400 | ████
480 | ██                   300 | ████
     |-------                   |-------
      A   B                   0 |-------
                               A   B
(Aparece que A vende o dobro, mas é só 4% a mais!)
```

### 2. Pizza com Muitas Fatias
Mais de 7 categorias torna a pizza ilegível.

### 3. Cores Confusas
Usar cores semelhantes ou em excesso dificulta a leitura.

### 4. Gráfico 3D Desnecessário
Efeitos 3D em barras ou pizzas distorcem a percepção de tamanho.

### 5. Sem Título ou Rótulos
O leitor não sabe o que está vendo.

### 6. Dados Incompletos ou Faltantes
Gráficos com lacunas criam interpretações erradas.

## Gráficos na Vida Real

- **Economia:** gráficos de inflação, desemprego, PIB ao longo do tempo (linhas)
- **Eleições:** intenção de voto por candidato (barras)
- **Saúde:** evolução de casos de doenças (linhas + área)
- **Clima:** temperaturas médias mensais (barras ou linhas)
- **Esportes:** estatísticas de jogadores (barras, radar)
- **Finanças pessoais:** distribuição de gastos (pizza), evolução da poupança (linhas)
- **Redes sociais:** crescimento de seguidores (linhas), engajamento por tipo de post (barras)

## Construindo um Gráfico: Passo a Passo

1. **Defina o objetivo:** o que você quer mostrar?
2. **Escolha o tipo de gráfico:** qual melhor comunica a mensagem?
3. **Organize os dados:** tabela de frequência ou série temporal
4. **Desenhe os eixos:** com escala adequada (comece em zero se possível)
5. **Plote os dados:** barras, linhas, pontos...
6. **Adicione título, rótulos e legenda**
7. **Verifique:** o gráfico é claro? Não distorce a informação?
8. **Inclua a fonte**

---
**Próximo:** [Média](Média.md)
