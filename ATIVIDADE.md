# HTML e CSS :woman_technologist:

As linguagens de HTML e CSS são muito usadas na elaboração de websites, sempre conectadas ao trabalho em front-end. É verdade que há quem não considere ambos nem sequer uma linguagem de programação, mas outros tipos de linguagem, como veremos abaixo.

## Aprofundando sobre HTML :computer:

Talvez HTML seja a linguagem mais conhecida, por ter sido muito relevante no passado e por ter sido o passatempo das blogueiras adolescentes millenials. Apesar de não ser considerada uma linguagem de programação, é considera uma linguagem de marcação de texto.

O HTML significa _HyperText Markup Language_, ou seja, é uma linguagem de marcação de texto, que acaba por transformá-lo em hipertexto. 

Ou seja, **ele serve para organizar e etiquetar (_tag_) a estrutura de um texto**. Sua marcação ajuda, por exemplo, a dizer onde começa e onde termina cada seção do texto (cabeçalho, parágrafos, imagens, etc.). 

Para fazer esse "etiquetamento", o HTML usa uma estrutura específica, muito focada no uso dos símbolos **"<" e "/>"**. O símbolo aberto precisa sempre "fechar" e, para que o código entenda esse fechamento, é necessário usar a barra **"/"**. Esses são os principais marcadores do HTMl, sendo usados em conjunto com outros fatores para conseguir dar corpo ao texto.

Outro ponto interessante a se mencionar sobre o HTML é sua lógica sequencial em tamanho x números. Por exemplo, para criar um título como o desta página "HTML e CSS" seria necessário escrever, sem os espaços: **< h1>HTML e CSS</ h1>.**

Já para um título menor, como o dessa seção, o correto seria: **< h2>Aprofundando sobre HTML</ h2>** e assim sucessivamente. O comando **<h>** serve para criar títulos e destaques e os números que o sucedem ditam o tamanho e destaque que queremos dar.

Abaixo compartilho uma simples tabela com alguns marcadores comuns de HTML (com espaços para visualização, mas corretamente usados sem eles) e suas funções:

|               | HTML                                 |
|---------------|--------------------------------------|
| Título grande |  < h1>Título aqui</ h1>.                 |
| Negrito       | < b>Texto aqui</ b>.                    |
| Itálico       | < i>Texto aqui</ i>.                    |
| Links         | < a href="LINK AQUI">Nome do Site</ a>. |
| Imagem        | < img src="caminho até a img">.        |

## Aprofundando sobre CSS :desktop_computer:	

Já O CSS serve para estilização de componentes escritos em linguagens de marcação, com o próprio HTML visto anteriormente. CSS é o acrônimo de _Cascading Style Sheet_, em tradução livre: Folha de Estilo em Cascatas. Seu nome se dá justamente pela forma de organização do seu código, que parece cair em "cascata". 

**Seu principal objetivo é separar o conteúdo do site de sua apresentação visual, alterando elementos que a afete** (ex: cores, espaçamentos, fontes, etc.). A ideia então é justamente separar o conteúdo e formato de um documento de sua apresentação, deixando-o mais visualmente agradável. Apesar de ser um pouco mais complexo que o HTML, o CSS também tem sintaxe simples e fácil compreensão. 

Sua escrita é menos "travada" como a do HTML, mas também é uma linguagem de marcação. Por exemplo, o uso "NOME: DESCRIÇÃO" é muito comum para delimitar algum tipo de alteração desejada, conforme vemos abaixo: 

> font: bold 12px verdana;
Nesse exemplo, estamos definindo que a fonte utilizada naquilo que estamos criando será verdana, tamanho 12 e em negrito.

O CSS é uma linguagem que usa muito *ATRIBUTOS*. Ou seja, comandos que definem algum tipo de relacionamento ou fazem alguma atribuição. Na tabela abaixo, compartilhamos alguns dos atributos utilizados e quais são suas funções:

|                                 | CSS              |
|---------------------------------|------------------|
| Alterar Plano de Fundo          | background-color |
| Tamanho da Fonte                | font-size        |
| Aplicar itálico                 | font-style       |
| Aplicar negrito                 | font-variant     |
| Configurar alinhamento do texto | text-align       |


Da mesma forma, é possível fazer links entre o CSS e o HTML, vinculando algum elemento que criamos no HTML a uma configuração que estamos fazendo no CSS. Em primeiro lugar, é importante adicionar uma linha de código na tag **<head>** do HTML, que avise ao código que há uma folha de estilo CSS vinculada a ele. 

## E o que mais? :mag_right:

No front-end há outra linguagem (essa sim efetivamente de programação) que é muito utilizada: o **JavaScript**. O objetivo deste README não é dar muitos detalhes desta linguagem, bem mais complexa e utilizada também corriqueiramente em back-end. Todavia, para que a explicação fique bem completa, é importante saber que esta linguagem permite que a implementação de itens mais complexos em páginas web de forma não-estática. Ou seja, segundo o site dos Developers do Mozilla:

> JavaScript é uma linguagem de programação que permite a você criar conteúdo que se atualiza dinamicamente, controlar multimídias, imagens animadas, e tudo o mais que há de interessante. Ok, não tudo, mas é maravilhoso o que você pode efetuar com algumas linhas de código JavaScript.

O mundo da programação é gigantesco e a vontade de aprender não termina neste README! Continue estudando e vamos sempre lutar para termos cada vez mais **MULHERES NA TECNOLOGIA**!

### Bibliografia utilizada :books:

- Curso online "Eu Programo" da [Programaria](https://www.programaria.org/curso-online-euprogramo/)
- [TOTVS](https://www.totvs.com/blog/developers/o-que-e-css/#:~:text=O%20CSS%20tem%20a%20tarefa,aspecto%20est%C3%A9tico%20de%20uma%20p%C3%A1gina)
- [TECMUNDO](https://www.tecmundo.com.br/programacao/2705-o-que-e-css-.htm)
- [HOSTINGER](https://www.hostinger.com.br/tutoriais/como-linkar-css-no-html)
- [DEVELOPER MOZILLA](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

### Disclaimer :label:
Este README foi realizado como primeira tarefa do curso Todas em Tech da [Reprograma](https://reprograma.com.br/). Para saber mais sobre qual era o desafio, por favor acesse o [GITHUB](https://github.com/reprograma/On16-TodasEmTech-S1-Git) da semana 1 do programa.