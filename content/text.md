# Trabalhando com textos em HTML

Um dos principais objetivos do HTML é estruturar os textos e dar significado.

## Formatação de textos

* `<b>`Texto em negrito
* `<strong>`Texto importante
* `<i>`Texto em itálico
* `<em>`Texto em destaque
* `<mark>`Texto marcado
* `<small>`Texto menor
* `<del>`Texto excluído
* `<ins>`Texto inserido
* `<sub>`Texto subscrito
* `<sup>`Texto sobrescrito

## Abreviações

A tag  `<abbr>`define uma abreviação ou um acrônimo, use o atributo global title para mostrar a descrição da abreviação/acrônimo ao passar o mouse sobre o elemento.

```html
<p>A <abbr title="HyperText Markup Language">HTML</abbr> é uma linguagem de marcação.</p>
```

## Detalhes do contato

A tag `<address>`define as informações de contato do autor/proprietário de um documento ou artigo.

```html
<address>
Escrito por John Doe.<br>
Visite-nos em:<br>
Exemplo.com<br>
Caixa 564, Disneylândia<br>
EUA
</address>
```

## Citações

A tag `<blockquote>`define uma seção que é citada de outra fonte.

```html
<p>Aqui está uma citação do site do WWF:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
Há 50 anos, o WWF protege o futuro da natureza.
A principal organização de conservação do mundo,
O WWF funciona em 100 países e é apoiado por
1,2 milhão de membros nos Estados Unidos e
perto de 5 milhões em todo o mundo.
</blockquote>
```

A tag HTML `<q>`define uma citação curta.

```html
<p>O objetivo do WWF é: <q>Construir um futuro onde as pessoas vivam em harmonia com a natureza.</q></p>
```

## Caracteres especiais (HTML Entities)

Caracteres reservados em HTML devem ser substituídos por entidades de caracteres. Veja abaixo alguns dos mais utilizados:

## Bloco de código

Para representar códigos usamos a tag `<pre>` que define o texto pré-formatado, preservando espaços e quebras de linha e a tag `<code>` que define um pedaço de código.

```html
<pre>
    <code>
        <h1>Olá, Mundo!</h1>
			  <p>Meu primeiro documento HTML.</p>
    </code>
</pre>
```

[Voltar a Home](../README.md)

