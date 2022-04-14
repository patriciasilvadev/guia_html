# Vídeos em HTML

Para adicionar um vídeo em uma página da web usamos a tag `<video>` e a tag `<source>` para inserir a mídia, colocamos mais de um formato e o navegador usará o primeiro formatos reconhecido.
Exemplo:

```html
<video width="320" height="240" poster="img.jpg" controls> 
				<source src="movie.mp4" type="video/mp4"> 
				<source src="movie.ogg" type="video/ogg">
				<p>Seu browser não suporta o vídeo.</p>
</video> 
```

Adicionamos os atributos `width` e `height`, para definir altura e largura ao vídeo.

O atributo `poster` configura uma imagem que vai aparecer de capa, enquanto o usuário não aperta o play.

E o atributo `controls` adiciona controles, como reproduzir, pausar e volume.

Se preferir pode colocar também o atributo `autoplay`, que reproduz o vídeo automaticamente assim que a página é carregada.

[Voltar a Home](../README.md)

