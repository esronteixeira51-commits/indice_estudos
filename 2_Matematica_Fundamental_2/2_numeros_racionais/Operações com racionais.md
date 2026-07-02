# Operações com Racionais

As **operações com números racionais** (frações, decimais e números mistos) seguem as mesmas propriedades das operações com inteiros, mas com cuidados especiais para os denominadores. Dominar essas operações é fundamental para todo o restante da matemática.

## Adição e Subtração

### Mesmo Denominador

$$ \frac{a}{c} + \frac{b}{c} = \frac{a + b}{c} $$

$$ \frac{a}{c} - \frac{b}{c} = \frac{a - b}{c} $$

### Denominadores Diferentes

Encontrar o MMC (mínimo múltiplo comum) dos denominadores:

$$ \frac{a}{b} + \frac{c}{d} = \frac{a \times d + c \times b}{b \times d} $$

Ou usando MMC:
$$ \frac{a}{b} + \frac{c}{d} = \frac{a \times \frac{MMC}{b} + c \times \frac{MMC}{d}}{MMC} $$

**Exemplo:**
$$ \frac{2}{3} + \frac{3}{5} = \frac{2 \times 5 + 3 \times 3}{15} = \frac{10 + 9}{15} = \frac{19}{15} $$

## Multiplicação

$$ \frac{a}{b} \times \frac{c}{d} = \frac{a \times c}{b \times d} $$

> **Simplificar antes de multiplicar** (se possível) para facilitar os cálculos!

**Exemplo:**
$$ \frac{2}{3} \times \frac{9}{4} = \frac{2 \times 9}{3 \times 4} = \frac{18}{12} = \frac{3}{2} $$

Ou simplificando antes:
$$ \frac{2}{3} \times \frac{9}{4} = \frac{2}{\cancel{3}_1} \times \frac{\cancel{9}^3}{4} = \frac{2 \times 3}{1 \times 4} = \frac{6}{4} = \frac{3}{2} $$

## Divisão

$$ \frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \times \frac{d}{c} = \frac{a \times d}{b \times c} $$

> **Dividir por fração é multiplicar pelo inverso!**

**Exemplo:**
$$ \frac{2}{3} \div \frac{4}{5} = \frac{2}{3} \times \frac{5}{4} = \frac{10}{12} = \frac{5}{6} $$

## Potenciação

$$ \left(\frac{a}{b}\right)^n = \frac{a^n}{b^n} $$

$$ \left(\frac{a}{b}\right)^{-n} = \frac{b^n}{a^n} $$

**Exemplo:**
$$ \left(\frac{2}{3}\right)^3 = \frac{8}{27} $$
$$ \left(\frac{2}{3}\right)^{-2} = \frac{9}{4} $$

## Expressões com Vários Tipos

Converter tudo para frações, depois operar:

$$ 1\frac{1}{2} + 0{,}75 - \frac{2}{3} $$

$$ 1\frac{1}{2} = \frac{3}{2} = \frac{6}{4} $$
$$ 0{,}75 = \frac{3}{4} $$
$$ \frac{2}{3} = \frac{8}{12} \text{ (vamos usar } MMC(2, 4, 3) = 12) $$

$$ \frac{3}{2} = \frac{18}{12}, \quad \frac{3}{4} = \frac{9}{12}, \quad \frac{2}{3} = \frac{8}{12} $$

$$ \frac{18}{12} + \frac{9}{12} - \frac{8}{12} = \frac{19}{12} = 1\frac{7}{12} $$

## Propriedades das Operações

| Propriedade | Adição | Multiplicação |
|-------------|--------|--------------|
| **Fechamento** | $\frac{a}{b} + \frac{c}{d} = \frac{ad+bc}{bd} \in \mathbb{Q}$ | $\frac{a}{b} \times \frac{c}{d} = \frac{ac}{bd} \in \mathbb{Q}$ |
| **Comutativa** | $\frac{a}{b} + \frac{c}{d} = \frac{c}{d} + \frac{a}{b}$ | $\frac{a}{b} \times \frac{c}{d} = \frac{c}{d} \times \frac{a}{b}$ |
| **Associativa** | $\left(\frac{a}{b} + \frac{c}{d}\right) + \frac{e}{f} = \frac{a}{b} + \left(\frac{c}{d} + \frac{e}{f}\right)$ | $\left(\frac{a}{b} \times \frac{c}{d}\right) \times \frac{e}{f} = \frac{a}{b} \times \left(\frac{c}{d} \times \frac{e}{f}\right)$ |
| **Elemento Neutro** | $\frac{a}{b} + 0 = \frac{a}{b}$ | $\frac{a}{b} \times 1 = \frac{a}{b}$ |
| **Inverso** | $\frac{a}{b} + \left(-\frac{a}{b}\right) = 0$ | $\frac{a}{b} \times \frac{b}{a} = 1$ (para $a \neq 0$) |
| **Distributiva** | $\frac{a}{b} \times \left(\frac{c}{d} + \frac{e}{f}\right) = \frac{a}{b} \times \frac{c}{d} + \frac{a}{b} \times \frac{e}{f}$ |

## Exemplos

### Exemplo 1: Expressão Complexa

$$ \frac{2}{3} + \frac{1}{2} \times \frac{4}{5} - \frac{1}{6} \div \frac{1}{3} $$

**Ordem:** multiplicação e divisão primeiro.

$$ \frac{1}{2} \times \frac{4}{5} = \frac{4}{10} = \frac{2}{5} $$
$$ \frac{1}{6} \div \frac{1}{3} = \frac{1}{6} \times 3 = \frac{3}{6} = \frac{1}{2} $$

$$ \frac{2}{3} + \frac{2}{5} - \frac{1}{2} = \frac{20}{30} + \frac{12}{30} - \frac{15}{30} = \frac{17}{30} $$

### Exemplo 2: Números Mistos

$$ 2\frac{1}{3} \times 1\frac{1}{2} \div \frac{5}{6} $$

$$ 2\frac{1}{3} = \frac{7}{3}, \quad 1\frac{1}{2} = \frac{3}{2} $$

$$ \frac{7}{3} \times \frac{3}{2} = \frac{21}{6} = \frac{7}{2} $$
$$ \frac{7}{2} \div \frac{5}{6} = \frac{7}{2} \times \frac{6}{5} = \frac{42}{10} = \frac{21}{5} = 4\frac{1}{5} $$

### Exemplo 3: Decimais e Frações

$$ 0{,}75 + \frac{1}{4} - 1\frac{1}{2} \times 0{,}5 $$

$$ 0{,}75 = \frac{3}{4}, \quad \frac{1}{4} = \frac{1}{4}, \quad 1\frac{1}{2} = \frac{3}{2}, \quad 0{,}5 = \frac{1}{2} $$

$$ \frac{3}{2} \times \frac{1}{2} = \frac{3}{4} $$
$$ \frac{3}{4} + \frac{1}{4} - \frac{3}{4} = \frac{1}{4} = 0{,}25 $$

## Aplicações na Vida Real

- **Cozinha:** dobrar, triplicar, reduzir receitas
- **Construção:** medidas, cortes, proporções
- **Finanças:** cálculos de juros, parcelamentos, descontos
- **Farmácia:** dosagens proporcionais ao peso
- **Estatística:** médias ponderadas, probabilidades
- **Engenharia:** cálculos de resistência, tensão, fluxo
- **Química:** concentrações, diluições, misturas
- **Física:** velocidade, aceleração, densidade
- **Economia:** índices, taxas, participações societárias
- **Música:** ritmos, compassos, subdivisões

## Problemas

### Nível 1 — Básico

**1.** Calcule: $\frac{2}{5} + \frac{3}{5}$

**Resposta:** $\frac{5}{5} = 1$.

**2.** Calcule: $\frac{3}{4} - \frac{1}{2}$

$$ \frac{3}{4} - \frac{2}{4} = \frac{1}{4} $$

**Resposta:** $\frac{1}{4}$.

**3.** Calcule: $\frac{2}{3} \times \frac{3}{4}$

$$ \frac{2 \times 3}{3 \times 4} = \frac{6}{12} = \frac{1}{2} $$

**Resposta:** $\frac{1}{2}$.

**4.** Calcule: $\frac{3}{5} \div \frac{2}{3}$

$$ \frac{3}{5} \times \frac{3}{2} = \frac{9}{10} $$

**Resposta:** $\frac{9}{10}$.

**5.** Calcule: $\left(\frac{2}{3}\right)^2$

$$ \frac{2^2}{3^2} = \frac{4}{9} $$

**Resposta:** $\frac{4}{9}$.

### Nível 2 — Intermediário

**6.** Calcule: $\frac{1}{2} + \frac{2}{3} - \frac{1}{4} + \frac{5}{6}$

$$ MMC(2, 3, 4, 6) = 12 $$
$$ \frac{6}{12} + \frac{8}{12} - \frac{3}{12} + \frac{10}{12} = \frac{21}{12} = \frac{7}{4} = 1\frac{3}{4} $$

**Resposta:** $\frac{7}{4}$ (ou $1\frac{3}{4}$).

**7.** Calcule: $2\frac{1}{3} \times 1\frac{1}{2} \div \frac{5}{4}$

$$ \frac{7}{3} \times \frac{3}{2} = \frac{7}{2} $$
$$ \frac{7}{2} \div \frac{5}{4} = \frac{7}{2} \times \frac{4}{5} = \frac{28}{10} = \frac{14}{5} = 2\frac{4}{5} $$

**Resposta:** $\frac{14}{5}$ (ou $2\frac{4}{5}$).

**8.** Calcule: $0{,}75 + \frac{1}{2} - 0{,}25 \times \frac{2}{3}$

$$ 0{,}25 \times \frac{2}{3} = \frac{1}{4} \times \frac{2}{3} = \frac{2}{12} = \frac{1}{6} $$
$$ \frac{3}{4} + \frac{1}{2} - \frac{1}{6} = \frac{9}{12} + \frac{6}{12} - \frac{2}{12} = \frac{13}{12} = 1\frac{1}{12} $$

**Resposta:** $\frac{13}{12}$ (ou $1\frac{1}{12}$).

**9.** Uma receita usa $2\frac{1}{4}$ xícaras de farinha. Se você faz o triplo da receita, quanto usa? Se depois divide a massa em 6 porções iguais, quanto de farinha há em cada porção?

$$ 2\frac{1}{4} \times 3 = \frac{9}{4} \times 3 = \frac{27}{4} = 6\frac{3}{4} \text{ xícaras} $$
$$ \frac{27}{4} \div 6 = \frac{27}{4} \times \frac{1}{6} = \frac{27}{24} = \frac{9}{8} = 1\frac{1}{8} \text{ xícaras por porção} $$

**Resposta:** Total: $6\frac{3}{4}$ xícaras. Por porção: $1\frac{1}{8}$ xícaras.

**10.** Simplifique: $\frac{1}{1 + \frac{1}{1 + \frac{1}{2}}}$

$$ 1 + \frac{1}{2} = \frac{3}{2} $$
$$ 1 + \frac{1}{3/2} = 1 + \frac{2}{3} = \frac{5}{3} $$
$$ \frac{1}{5/3} = \frac{3}{5} $$

**Resposta:** $\frac{3}{5}$.

### Nível 3 — Desafio

**11.** Calcule: $\frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \frac{1}{16} + \frac{1}{32} + \frac{1}{64} + \frac{1}{128} + \frac{1}{256}$

Isso é uma progressão geométrica! Ou observe o padrão:
$$ \frac{1}{2} = \frac{128}{256}, \quad \frac{1}{4} = \frac{64}{256}, \quad \frac{1}{8} = \frac{32}{256}, \quad \frac{1}{16} = \frac{16}{256} $$
$$ \frac{1}{32} = \frac{8}{256}, \quad \frac{1}{64} = \frac{4}{256}, \quad \frac{1}{128} = \frac{2}{256}, \quad \frac{1}{256} = \frac{1}{256} $$

$$ \frac{128 + 64 + 32 + 16 + 8 + 4 + 2 + 1}{256} = \frac{255}{256} $$

Ou pela fórmula da PG: $S_n = \frac{a_1(1 - q^n)}{1 - q} = \frac{\frac{1}{2}(1 - (\frac{1}{2})^8)}{1 - \frac{1}{2}} = 1 - \frac{1}{256} = \frac{255}{256}$.

**Resposta:** $\frac{255}{256}$.

**12.** Se $\frac{a}{b} + \frac{c}{d} = \frac{a+c}{b+d}$ para frações positivas, o que isso implica sobre $a, b, c, d$?

$$ \frac{a}{b} + \frac{c}{d} = \frac{ad + bc}{bd} = \frac{a+c}{b+d} $$

$$ (ad + bc)(b + d) = bd(a + c) $$
$$ ad(b+d) + bc(b+d) = abd + bcd $$
$$ abd + ad^2 + b^2c + bcd = abd + bcd $$
$$ ad^2 + b^2c = 0 $$

Como todas são positivas, $ad^2 + b^2c = 0$ é impossível (soma de positivos = 0).

**Resposta:** É impossível para frações positivas. A igualdade $\frac{a}{b} + \frac{c}{d} = \frac{a+c}{b+d}$ nunca ocorre (a não ser que alguma seja zero, mas não são frações positivas).

> **Nota:** Este é um erro comum! A soma de frações NUNCA é $\frac{a+c}{b+d}$ (exceto casos triviais).

**13.** Uma liga metálica é feita de $\frac{2}{5}$ cobre, $\frac{1}{3}$ zinco e o resto de estanho. Qual a fração de estanho? Se a liga pesa 150 kg, quanto de cada metal há?

$$ \frac{2}{5} + \frac{1}{3} = \frac{6}{15} + \frac{5}{15} = \frac{11}{15} \text{ (cobre + zinco)} $$
$$ \text{Estanho} = 1 - \frac{11}{15} = \frac{4}{15} $$

$$ \text{Cobre} = 150 \times \frac{2}{5} = 60 \text{ kg} $$
$$ \text{Zinco} = 150 \times \frac{1}{3} = 50 \text{ kg} $$
$$ \text{Estanho} = 150 \times \frac{4}{15} = 40 \text{ kg} $$

Verificação: $60 + 50 + 40 = 150$ ✓

**Resposta:** Estanho = $\frac{4}{15}$. Cobre: 60 kg, Zinco: 50 kg, Estanho: 40 kg.

---
**Fim — Operações com Racionais**
