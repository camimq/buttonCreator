# CSS GRID
[Link YouTube](https://www.youtube.com/watch?v=HN1UjzRSdBk) - Desvendando o CSS Grid na prática | [Mayk Brito](https://github.com/maykbrito)

## GRID
- Bidimensional.
- Divisão de toda a página em linhas e colunas.
- Colocar elementos onde quiser nessa divisão.

## GRID OU FLEXBOX
- Grid: Duas dimensões (colunas e linhas).
- Flexbox: Uma dimensão (ou coluna ou linha).
- Um complementa o trabalho do outro.
- Grid delimita os limites (header, footer, sidebars e etc) e o flexbox alinha os elementos.
- Verificar quais navegadores ainda não estão aceitando Grid (se houver)

## PROPRIEDADES

`container` e `item(s)`

## CONTAINER

- `Display: grid;`: inicia o container, dizendo que é grid.
- `grid-template-columns`: fatia as colunas (quantas colunas tem).
- `grid-template-rows`: define quantas linhas tem.
- `grid-gap`: espaçamento - é um atalho para o `grid-row-gap` e para o `grid-column-gap`. Caso precise aplicar o espaçamento só em um ou em outro, basta utilizar as propriedades separadamente.
    - `grid-row-gap`: espaçamento da linha.
    - `grid-column-gap`: espaçamento da coluna.
- `grid-template-areas`: delimita áreas.

... e mais 4 propriedades e **alinhamentos**

## ITEMS

- `grid-column`: onde fica o ítem dentro da coluna.
    - `grid-column-start`:
    - `grid-column-end`:
- `grid-row` : onde fica o ítem dentro da linha.
    - `grid-row-start`:
    - `grid-row-end`:
- `grid-area`: onde fica o ítem dentro da área delimitada.

... e mais 2 propriedades de **alinhamento**

# Grid: Alinhamento

Existem 6 propriedades para alinhamento:

1. `justify-content`:
2. `align-content`:
3. `justify-item`:
4. `align-items`:
5. `justify-self`:
6. `align-self`:

Vamos separá-los em 2 grupos

1. `justify` e `align`
2. `content`, `items` e `self`

----

## Justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita.
O **eixo y** é o posicionemnto vertical, de cima para baixo.

## Content, Items e Self

Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades.

### Content

`justify-content`e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são raras, pois só é aplicado caso o grid deja menor que a área definida. (Por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com um grid pequeno, para o tamanho da área do grid)

Podemos usar **7 valores**:

1. start
2. end
3. center
4. strech
5. space-between
6. space-around
7. space-evenly

### Items

`justify-items` e `align-items` vai permitir alinar os itens do nosso grid, em qualquer espaço disponível, na célula que ele habitar.

Podemmos usar **4 valores**:

1. start
2. ende
3. center
4. strech

### Self

`justify-self` e `align-self`vai nos permitir alinhar o item em si.

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicado diretamente ao item de um grid.