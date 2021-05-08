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