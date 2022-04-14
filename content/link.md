# Links

Para adicionar um link em uma página criamos **âncoras** através da tag <a>. Os links permitem que os usuários naveguem de uma página para a outra

Exemplo:
```html
<a href="#" target="" rel="">Link</a>
```
O `href` é seu principal atributo, que indica o destino daquele link. Quando ainda não definimos a URL que será adicionada, podemos colocar # como valor. E o texto do link é a parte que fica visível para o leitor.

Por padrão, a página vinculada será aberta na janela atual do navegador. Mas podemos alterar isso com o atributo `target` que pode ter os seguintes valores, sendo as duas primeiras opções as mais utilizadas:
* `_self` - abre o documento na mesma janela
* `_black` - abre o documento em uma nova janela
* `_parent` - abre o documento no quadro pai
* `_top` - abre o documento em todo o corpo da janela

Existe outro atributo bem interessante que indica a natureza do destino, ele é o `rel`, que aceita os seguintes valores:
* `next` - indica que o link é para próxima página
* `prev` - indica que o link é para página anterior
* `author` - indica que o link é para o site do autor do artigo
* `external` - indica que é um link para outro site

# Link Interno

Nesse caso, temos duas opções: navegar por links da mesma página, ou navegar por páginas locais.

Navegando por links da mesma página, ao clicar no link o navegador mudará o foco para o elemento que possui `id` igual aquele indicado no `href`

Exemplo:
```html
<a href="#titulo1">Ir para Título 1</a>
<!-- Outros elementos-->

<h1 id="titulo1">Título 1</h1>
```

Navegando por páginas locais, ao clicar no link o navegador abrirá outra página daquele site.

Exemplo:
```html
<a href="../index.html">Ir para Home</a>
```
Se quiser se referir a página atual, pode usar ./ antes do nome do arquivo. E se quiser se referir a página  imediatamente superiores na hierarquia do site, pode usar ../

# Link Externo

Nesse caso, ao clicar no link o navegador abrirá a página de outro site. Dentro do atributo `href` colocamos a URL de outro site.

Exemplo:
```html
<a href="https://google.com">Ir para o Google</a>
```

# Realizando Downloads através de links

A partir da versão HTML5, podemos adicionar o atributo `download` para efetuar o download de qualquer arquivo.

Exemplo:
```html
<a href="arquivos/html.pdf" download="html.pdf" type="application/pdf">Baixar PDF</a>
```
Aqui vão alguns *media types* mais usados:
* application/zip
* text/html
* text/css
* text/javascript
* video/mp4
* video/h264
* video/JPEG
* audio/aac
* audio/mpeg
* font/ttf
* image/jpeg
* image/png

[Voltar a Home](../README.md)
