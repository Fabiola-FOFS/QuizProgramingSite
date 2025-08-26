### html é o esqueleto
- tudo o que vou fazer preciso colocar a estrutura

h1 - (e demais até 7)
usado para titulo, subtitulos topicos
h1 só um por pagina

# Informações para o navegador 
<doctype html> declaração mostra a versão do html que se está usando

<html> tag raiz - entre essa tag se coloca tudo o que vai no projeto
codigo html

# metadados - informação para o navegador/ ñ para usuarios - essas informações ficam na tag <head>
<meta> - tag vazia de metadados: colocamos o atributo dentro da tag + o content
<head> cabeça ficam os metadados(informações de descrição titulo stilo)
<body> parte visual/ subtitulos
 # no body - a forma mais comum de organizar as paginas é 
cabeçalho - <header>
corpo - <main>
rodapé - <footer>
essas tags são semanticas - só servem para dividir o conteudo da pagina 
mecanismos do google ranqueiam melhor paginas bem desenhadas e ajuda na acessibilidade

<section> tag semantica para definir seções dentro da pagina por exemplo introdução perguntas e etc
elementos filhos - devem ser escritos após um tab (idetação)
<p> paragrafo

tags para destacar o texto 
<strong> negrito
<em> italico - enfase 
<br> pula 
<abbr> tag para colocar descrição dinamica ao passar o mouse por cima 

tag de comentário no CSS 
<!--comentário--> Nada do que for escrito no comentário será lido pelo navegador

<form> formulário- permite guardar e processar a entrada do usuario entre com dados - permite criar listas para escolha
<input> permite entrada do usuario 
***atributos*** da tag input 
-- type= : o tipo de entrada pode ser : text, radio, 
value: informar o dado que vai para o bd
id= : 
name= : atributos para rastrear a informação
*placeholder* : texto que fica na caixa informando o que o usuario deve fazer/escrever
<label for=""> : aqui fica a informação visivel na pagina