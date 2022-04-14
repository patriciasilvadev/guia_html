# Imagem

Para adicionar uma imagem em uma página da web usamos a tag `<img>`. Ela contém dois atributos obrigatórios, o `src` e o `alt`.

**Exemplo:**

```html
<img src="" alt="">
```

O atributo `src` específica o caminho de origem da imagem, que pode ser um caminho interno caso a imagem esteja dentro de alguma pasta do projeto ou pode ser caminho externo caso a imagem esteja em um servidor/site e neste caso adicionamos a url da imagem.

**Exemplos:**

```html
<img src="img/imagem.jpg" alt="">

<img src="[https://pt.m.wikipedia.org/wiki/Ficheiro:HTML5_logo_and_wordmark.svg](https://pt.m.wikipedia.org/wiki/Ficheiro:HTML5_logo_and_wordmark.svg)" alt="">
```

O atributo `alt` que define texto alternativo, se o usuário por algum motivo não puder visualizar a imagem, o valor do `alt` será apresentado.

```html
<img src="logohtml.png" alt="Logo da linguagem HTML5.">
```

# Favicon

Um favicon é uma pequena imagem apresentada ao lado do título da página na gui do navegador.

Para adicionar um favicon em uma página da web usamos a tag `<link>` dentro da tag de cabeçalho `<head>`. Ela contém dois atributos obrigatórios, o `type` e o `href`.

**Exemplo:**
```html
<link rel="icon" type="image/x-icon" href="favicon.icon">
```


[Voltar a Home](../README.md)

