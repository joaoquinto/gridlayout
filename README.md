# Curso de CSS Grid Layout da Origamid.

# Container

## grid-template-columns:
> Cria colunas e manipula a largura da coluna - Container

```css
/* Cria 2 colunas com 1fr e 3 colunas com o min de 100px e o max de 1fr */
.container{
    display:grid;
    grid-template-conlumns: 1fr 1fr repeat(3,minmax(100px,1fr));
}

/* 
Cria e ajusta automaticamente as colunas com o min de 1fr e max de 2fr.

auto-fit pode ser trocado pelo auto-fill, porém o auto-fill é preenchimento automático
*/

.container{
    display:grid;
    grid-template-columns: repeat(auto-fit,minmax(1fr, 2fr))
}

```

## grid-template-rows:
> Cria linhas e manipula a altura do conteúdo

```css
/* Cria 2 linhas de 1fr e cria 3 linhas com min 100px e max de 1fr */

.container{
    display: grid;
    grid-template-rows:  1fr 1fr repeat(3,minmax(100px,1fr));
}
```

## auto-fit: propriedade do repeat()
> Ajuste Automático

## auto-fill: propriedade do repeat()
> Preenchimento Automático


```css
/* 
Auto-fit ajuda na responsividade por se ajustar automaticamente
*/
.container{
    display:grid;
    grid-template-columns: repeat(auto-fit,minmax(1fr, 2fr));
    grid-template-rows: repeat(4 ,100px);
}

```
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
