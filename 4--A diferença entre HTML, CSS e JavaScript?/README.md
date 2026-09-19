# Título do Vídeo
A diferença entre HTML, CSS e JavaScript ?

## Informações
Módulo 1 // Capítulo 3 // Aula 1

- Link do vídeo: https://www.youtube.com/watch?v=B4FU3NFRTDw&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=9
- Duração do Vídeo: 26:32 minutos
- Data de visualização: 16/07/2026 e 04/08/2026

## Conteúdos aprendidos 


HTML é referido em feminino porque é a linguagem HTML e CSS é representada no feminino plural porque são as folhas de estilo.

!! Não se pode dizer que se programa em HTML e CSS pois elas não são linguagens de programação, o certo dizer que desenvolve em HTML e CSS.

HTML: HyperText Markup Language = linguagem de marcação para hipertexto,
hipertexto é quando você tem um texto e uma área que você pode clicar e ele vai pra outro texto , mas também pode ser aplicado para imagens

Markup significa que é de marcas, pois a linguagem HTML é fundamentada em marcas, ela não tem estruturas de uma linguagem de programação como variável, condição e etc. 

CSS: Cascading Style Sheets = folhas de estilo em cascata.
A qual vai acrescentando informações a próxima folha semelhante a uma cascata 

-A linguagem HTML era uma linguagem focada em conteúdo, o qual pode ser texto, imagem, vídeo e tabela. Caso você leia um artigo, o artigo é o HTML devido ser o conteúdo.

-Enquanto o CSS é o design responsável pelas cores, organização, tamanhos e posicionamento do site, pois não adianta ter conteúdo e ser feio ou ser difícil de compreender . 

-Junto com o HTML e CSS se trabalha também com o Javascript(JS) o qual é responsável pelas interações como menus, animações, popups e validações.
-Javascript(JS) é o meio que você vai desenvolver o site, pois não adianta ter conteúdo e um bom design se você não tem como construir um site para inserir essas informações. 
*Um exemplo é como se o JS fosse o museu, o HTML fosse as obras de arte e o CSS é a aparência do museu.

É necessário sempre utilizar os 3, pois cada um tem sua funcionalidade e sua importância, quando tiramos alguns deles em um site como o youtube, sem o JS fica impossível a utilização, pois o youtube funciona totalmente com interatividade, sem o CSS fica totalmente desorganizado e horrível de compreender e sem o HTML os vídeos não funcionam.

    *Como criar conteúdo em HTML
Todas as partes que estiverem sublinhadas são códigos, como: <h1>
Por exemplo, a frase “Exemplo de título” seria o conteúdo do HTML mas para transformá-lo em título será necessário a utilização do colchete angular para a frase.
<h1> chamado de abertura de tag e quando a frase terminar se utiliza colchete angular e a barra </h1> chamado de fechamento de tag, ficando assim:  <h1>Exemplo de título</h1> lembrando que não pode usar espaço!

Para a criação de parágrafo se inicia com colchete angular e p <p> e para terminar se finaliza com colchete angular, p e barra </p>

Existem tags mais complexas como: <img src=”foto.png” alt=”Exemplo de foto”>
img é a abertura de tag, mas não tem barra fechamento, a grande maioria das tags tem abertura e fechamento mas existem algumas exceções como hr, meta, img.
src e alt são chamados de parâmetro foto.png e “Exemplo de foto” são chamados de valor. src vem de origem     //      alt vem de alternativo

    *Como montar o estilo em CSS 
Para iniciar é necessário colocar h1 referente ao trecho que eu quero personalizar e entre chaves colocar o código, ficando assim:
h1{                     }
o h1 é chamado de seletor e dentro do seletores se coloca as linhas , como exemplo adicionar:
h1{
       font-family: Arial;
}
O qual essa linha vai fazer com que a fonte de letra padrão deixe de times new roman para ser arial, a linha font-family:Arial; e todas as linhas dentro das chaves são chamadas de declaração e toda declaração CSS termina com ; como por exemplo:

h1{
       font-family: Arial;
       font-size:20pt;
       color:blue;
}
na linha color:blue, color é propriedade e blue é valor 

    *Estrutura básica do documento HTML
Todo documento HTML tem que a primeira linha começar com a especificação de que se vai utilizar o HTML5 e para transmitir essa mensagem se usa o código:
<!DOCTYPE html>   

 !DOCTYPE é uma tag específica de configuração para dizer que ele é HTML 5.
Depois disso vai começar o HTML e para isso a gente vai montar o par que e a abertura e fechamento da tag.

<html lang=’’pt-br’’>  significa que o site vai ser em português.
<head> significa cabeça, nessa parte vai estar localizado as configurações do site.
<body> significa corpo, nessa parte vai estar localizado a parte visível e estética do site.

UTF-8 é o sistema de codificação de caracteres mais usado na internet para traduzir letras, números e símbolos em sequências de bits que o computador consegue entender e exibir corretamente, ou seja, a linha de código:
<meta charsete=”UTF-8’’> significa a utilização de acentos e outros caracteres.
<meta name=”viewport” content “width=devide-width , initial-scale=1.0”> significa  que o site vai ocupar a parte branca toda do site
<tittle>Document</tittle> significa o título do site
Para finalizar o <head>, <body>, o html e outros códigos é necessário adicionar a barra, como </head>, </body>, </html>.
---------------------------------------------------------------------------------------------------------

    *Estrutura básica do documento HTML
Ao reunir o que foi passado neste essa última parte -Estrutura básica do documento HTML- é possível montar o código: 

<!DOCTYPE html>   
<html lang=’’pt-br’’>
	<head> 
		<meta charsete=”UTF-8’’> 
<meta name=”viewport” content “width=devide-width ,     
initial-scale=1.0”>
	</head> 
	<body>
		<h1>Olá, Mundo!</h1>
	</body>
</html>

    *Como funcionam a HTML e as CSS?
O HTML e o CSS ficam localizados no servidor, assim tiramos uma cópia trazendo para o nosso computador sendo disponibilizado para o navegador (como google chrome,Mozilla Firefox,Microsoft Edge, etc) do usuário, a função do navegador é analisar linha por linha digitada e gerar um resultado visual o qual é enviado para o computador fazendo com que o site apareça na tela.