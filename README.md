#HTML
##Conceito
É uma linguagem de marcação utilizada na construção de páginas na Web
## Tags HTML
<br> -> Quebra de linha (nula)
<p></p> -> Paragráfos
<hr> -> Linha horizontal (nula)
<h></h> ->Titulos ou textos
* Negrito
<Strong></Strong> -> Algo importante
<b></b> -> Destacar uma palavra
* Itálico
<i></i> -> Termos técnicos
* Sublinhado
<u></u> -> Sublinhado no texto
<bgcolor=’#FF0000’> -> Cor de fundo
Estilo de texto ex: -> < font size =”20px” > seu texto </font>
Estilo de fonte -> < font face = “ verdana”< seu texto </font>
* Listas
Lista não ordenada -> <ul> e <li> ex:
<ul>
<li> Arroz </li> 
<li> Batata </li> 
<li> Cebola </li>
</ul>
Lista ordenada -> <ol> e <li> ex:
<ol>
<li> Arroz </li> 
<li> Batata </li> 
<li> Cebola </li>
</ol>
Inserção de links -> <a> ex:
< a href =” endereço destino”> texto</a>
Inserção de imagens -> <img> ex:
< img src = “local da imagem”>
* Tabelas <table>
<tr> -> linha
<td> -> coluna 
Ex:
<table>
<tr>
<td>Frutas</td>
<td>Verduras</td>
</tr>
#CSS
## Conceito
Cascading Style Sheets é um mecanismo para adicionar estilo a um documento web.
Tipos
* Incorporado -> Por meio da tag <style>, no topo da página , dentro da tag <head>
<style>
P{ color: blue;
font-size: 30px}
</style> 
* Linkado -> Tag <link>
* Inline -> Diretamente no HTML
< p style =” color: red; font- size: 30 px” > seu texto  </p>
Seletores
Universal *;
Tipo elemento <e>;
Classe .;
ID #;
Link a;
backgroud-color / Cor de fundo;
backgroud-image / imagem como fundo de elemento;
backgroud-size /tamanho da imagem;
backgroud-position / posição da imagem;
backgroud-attachment/ imagem de fundo rolará com a tela;
backgroud-repeact / imagem se pode ou não repetir. 
<div> -> Div serve como um container para outros elementos
<nav> -> Concentra os links que formam a navegação do site
*Definição das propriedades de uma class
Seletor ponto + nome da classe ex:
.container-principal{font-family: ‘verdana’; color: #777;}
* Posições 
top – superior;
left- esquerda;
right- direita;
bottom -inferior;
fixed- fixa o elemento na coordenada atribuída;
realtive- o ponto inicial é o canto superior esquerdo do próprio elemento;
absolute-o ponto inicial é o elemento em que está incerido.
