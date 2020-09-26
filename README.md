![titulo](https://i.imgur.com/5czw1H9.png)

Para entendermos sobre as propriedades CSS de layout, o artigo é divido em cinco tópicos: DOM,  Box Model, Propriedades de Layout, Propriedade Display: Flex e CSS-Grid.

## Document Object Model (DOM)
![DOM](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)

Em português significa: **Modelo de Objeto de Documento**. Tem como objetivo definir a estrutura lógica (muito parecida com uma árvore) dos documentos e a maneira como um documento é manipulado.


## Box Model
![Box Model](https://tableless.github.io/iniciantes/assets/img/box-model.png)

O Box Model define o tamanho dos elementos e é descrito as caixas geradas pelo HTML, detalhando as opções de margens, bordas, paddings e conteúdo de cada elemento. 
## Propriedades de Layout
**Propriedade Margin**: Essa propriedade define a distância a partir de cada um dos lados e de seus elementos vizinhos (em, pixels ou %). 

![Margin](https://www.maujor.com/imagens/ogmargintut.png)

**Propriedade Padding**: Distância do elemento entre a borda e o conteúdo. (em, pixels ou %). 

![Definindo padding com CSS](https://www.maujor.com/imagens/ogpaddingtut.png)

**Propriedade Position**: Indica ao navegador como ele tratará um elemento específico. (Statis, Relative, Absolute ou Fixed).

![Saiba tudo sobre a propriedade position | by Daniel Cavalcanti | Jaguaribe  Tech | Medium](https://miro.medium.com/max/450/1*umKRLLADpNt-IPQK6jqdhw.jpeg)

**Propriedade Float**: Faz o objeto flutuar ao lado do conteúdo (Left, Right ou None).

![divs com float left e right respectivamente](http://www.brunoprogramacao.com.br/wp-content/uploads/2013/10/post-float3.png)

**Propriedade Visibility**: Oculta um elemento enquanto deixa o espaço onde ele teria sido criado. Usado para ocultar linhas e colunas de uma tabela (Visible, Hidden ou Collapse).

![css-visibility-show-block](https://www.programaria.org/wp-content/uploads/2016/07/css-visibility-show-block.png)

**Propriedade Outline**: Externo às bordas, aplica formatação ao redor do elemento. (Outline-color, Outline-style, Outline-width e Outline). 
**Propriedade Display**: Faz aplicação de quebra. (Inline, Block, None, Inline-block, List-item, Flex). 

![Tutorial CSS - A propriedade CSS display](https://www.maujor.com/tutorial/display/op_runin.gif)



## Propriedade Display: Flex

A propriedade indica que o conteúdo dentro de um container se comportará como um bloco. 
*Exemplo: No arquivo **estilo.css** inserir a propriedade **display:flex** no identificador **#content**.*

**Propriedade Flex-direction**: Formata a direção do posicionamento dos elementos (Row, Column, Row-reverse e Column-reverse).

![Flexbox | desenvolvimento para web](https://storage.googleapis.com/dpw/app/uploads/2015/04/flexbox-flex-direction.png)

**Propriedade Flex-wrap**: Diz se os elementos filhos aceitarão ou não um quebra de conteúdo (Wrap, Nowrap e Wrap-reverse).
![Flexbox | desenvolvimento para web](https://storage.googleapis.com/dpw/app/uploads/2015/04/flexbox-flex-wrap.png)

**Propriedade Justify-content**: Determina o posicionamento dos elementos na página (Flex-start, Flex-end, Space-around e Space-between).

![Flexbox | desenvolvimento para web](https://storage.googleapis.com/dpw/app/uploads/2015/04/flexbox-justify-content.png)

**Propriedade Align-items**: Determina o posicionamento vertical dos elementos na página (Flex-start, Flex-end, Center, Strech e Baseline). 

![Aligning Items in a Flex Container - CSS | MDN](https://mdn.mozillademos.org/files/15631/align5.png)

**Propriedade Align-content**: Alinha as linhas do container em relação ao eixo vertical. A propriedade só funciona se existir mais de uma linha de flex-itens. Para isso o flex-wrap precisa ser wrap (Stretch, Flex-start, Flex-end, Center, Space-between e Space-around).

![Aligning Items in a Flex Container - CSS | MDN](https://mdn.mozillademos.org/files/15631/align5.png)

**Propriedade Flex-flow**: O flex-flow é um atalho para as propriedades flex-direction e flex-wrap. Você não verá muito o seu uso, pois geralmente quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap (Row noweap, Row wrap e Column nowrap).

**Propriedade Order**: Determina a ordem em que os elementos serão exibidos na página (Valor inteiro).

**Propriedade Flex-grow**: Define a propriedade de crescer o elemento na página. 

**Propriedade Flex-shrink**: Define a propriedade de encolher o elemento na página.

**Propriedade Flex-basis**: Define o width dos elementos antes de distribuir o restante para o flex-grow (Pixel). 

## CSS-Grid
![Introduction to CSS Grid - Bill Erickson](https://www.billerickson.net/wp-content/uploads/2018/09/css-grid-intro.jpg)

O CSS Grid Layout é o sistema de layout mais completo em CSS. É um sistema bidimensional, o que significa que pode lidar com colunas e linhas, você poderá trabalhar com o Grid Layout aplicando regras CSS tanto a um elemento pai (que se torna o Grid Container) quanto aos filhos desse elemento (que se tornam Grid Items).


## Referências
Este artigo foi feito a partir do material visto em aula e os seguintes sites: 

*[origamid.com]*

*[simplesnippets.tech]*

*[maujor.com]*

*[medium.com]*

*[brunoprogramacao.com.br]*

*[programaria.org]*

*[googleapis.com]*

*[mozillademos.org]*

*[billerickson.net]*


## ALYSON CAMARGO BP3002241
