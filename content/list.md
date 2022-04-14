# Listas

Uma **lista não ordenada** começa com a `<ul>`tag. Os itens da lista serão marcados com marcadores (pequenos círculos pretos) por padrão:

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

Você também pode escolher o marcador do item, utilizando o atributo `<ul style="list-style-type: ;">` que pode ter um dos seguintes valores:

* **disc** -  define o marcador do item da lista para um marcador (padrão)
* **circle** - define o marcador do item da lista para um círculo
* **square** -  define o marcador do item da lista para um quadrado
* **none** -  os itens da lista não serão marcados

Uma **lista ordenada** começa com a `<ol>`tag. Os itens da lista serão marcados com números por padrão:

```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

Você também pode escolher o marcador do item, utilizando o atributo `<ol type=" ">` que pode ter um dos seguintes valores:

* A - define o marcador do item para alfabeticamente maiúscula (A, B, C, D)
* a - define o marcador do item para alfabeticamente minúscula (a, b, c, d)
* I - define o marcador do item para números romanos maiúsculo (I, II, III, IV)
* i - define o marcador do item para números romanos minúsculo (i, ii, iii, iv)
* 1 - define o marcador do item para Números decimais (1, 2, 3, 4)

**Lista de descrição**

A `<dl>`tag define a lista de descrição, a tag `<dt>` define o termo (nome) e a tag `<dd>` difine a descrição cada termo.

```html
<dl>
    <dt>Hypertext</dt>
    <dd>É um hiper texto com possibilidades...</dd>

    <dt>Markup</dt>
    <dd>Marcação do texto</dd>

    <dt>Languague</dt>
    <dd>Linguagem com sua semântica e sintaxe....</dd>
</dl>
```

[Voltar a Home](../README.md)

