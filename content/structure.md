# Estrutura Básica

Para começar a desenvolver uma página Web, criamos um arquivo renomeado como **index.html** utilizando um editor de código como Notepad++, Sublime Text ou Visual Code e nele adicionamos a estrutura básica de um página em HTML, com *indentação* que são os avanços e recuos, usando uma tecla tab do teclado ou espaço, para organizar as linhas de código da nossa página.

**Exemplo em código da estrutura básica do HTML**

```html
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <title>HTML Tutorial</title>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
  <h1>Olá, Mundo!</h1>
  <p>Meu primeiro documento HTML.</p>
  <!-- comentários -->
</body>

</html>
```

## Exemplo Explicado com as principais Tags

* A `<!DOCTYPE html>`declaração define que este documento é um documento HTML5
* A tag `<html>` é o elemento raiz de uma página HTML
* A tag `<head>` contém informações meta sobre a página HTML
* A tag `<title>` especifica um título para a página HTML (que é mostrado na barra de título do navegador ou na guia da página)
* A tag `<body>` define o corpo do documento e é um recipiente para todos os conteúdos visíveis, como títulos, parágrafos, imagens, hiperlinks, tabelas, listas, etc.
* A tag `<h1>` define cabeçalhos, que vão do `<h1>` ao `<h6>`. Definindo assim o título mais importante ao menos importante.
* A tag `<p>` define um parágrafo. Um parágrafo sempre começa em uma nova linha e os navegadores adicionam automaticamente algum espaço em branco (uma margem) antes e depois de um parágrafo.

## Exemplo Explicado com as principais Meta Tags

As tags `<meta>` servem para descrever o conteúdo de uma página para os mecanismos de buscas.

* `Charset` especifica a codificação de caracteres para o documento HTML. A especificação HTML5 incentiva os desenvolvedores da Web a usar o conjunto de caracteres UTF-8, que abrange quase todos os caracteres e símbolos do mundo!
* `Description` define uma descrição da sua página da web.
* `keywords` define palavras-chave para motores de busca.
* `author` define o autor de uma página, geralmente o desenvolver ou a empresa desenvolvedora.
* `viewport` Configura a janela de visualização para que seu site fique bem em todos os dispositivos.

## Outras Tags que podemos utilizar

* A tag `<hr>` define uma quebra temática em uma página HTML (por exemplo, uma mudança de tópico).
* A tag `<br>` insere uma única quebra de linha. É útil para escrever endereços ou poemas.
* A tag `<div>` utilizada quando queremos dividir conteúdos em blocos de código, como por exemplo, cards.  

[Voltar a Home](../README.md)

