# Curso de CSS Grid Layout da Origamid.

# Container

## grid-template-columns:
> Cria e manipula a largura da coluna - Container

## grid-template-rows:
> Cria e manipula a altura do conteúdo - Container

## auto-fit: propriedade do repeat()
> Ajuste Automático

## auto-fill: propriedade do repeat()
> Preenchimento Automático

## grid-template-areas:
> Cria e nomeia as áreas do layout e só pode criar áreas dentro da grade explícita - Container

## grid-template: 
> Atalho para definir o grid-template-columns, grid-template-rows e grid-template-areas.

## grid-auto-columns:
> Define o tamanho das colunas que forem feitas automáticamente.

# grid-auto-rows:
> Define o tamanho das linhas que forem feitas automáticamente

## grid-auto-flow:
> Define qual vai ser o comportamento automático quando surgirem novos elementos, se vão ser (row,column, dense)

- Row:O grid irá criar linhas quando não houver mais espaços
- Column: O grid irá criar colunas ---
- dense: Tenta posicionar o máximo dos elementos que existirem nas primeiras partes do grid (pode desorganizar o conteúdo).

# Item

## grid-area: 
> Move o elemento criado pelo grid-template-area para a área solicitada - Item

## grid-column & grid-row:
> Abreviação de grid-column-start,end  e grid-row-start,end elas ofertam mais flexibilidades na hora de posicionar os itens.

[W3C](https://www.w3.org/TR/css-grid-1/#overview-placement)

[grid-row-column-start-end vs grid-area e grid-template area](https://stackoverflow.com/questions/55213061/css-grid-grid-row-column-start-end-vs-grid-area-grid-template-area)

[Origamid Documentação](https://www.origamid.com/projetos/css-grid-layout-guia-completo/)
