# Audios em HTML

Para adicionar um audio em uma página da web usamos a tag `<audio>`
				
```html
<audio preload="" controls autoplay loop> 	
       <source scr="audio.mp3" typy="audio/mpeg"> 	
				<source scr="audio.ogg" typy="audio/ogg"> 	-
				<source scr="audio.wav" typy="audio/wav"> 	
				<p>Seu navegador não suporta o o áudio<a href="audio.mp3" download="audio.mp3" type="audio/mpeg"></a></p>
</audio>
```
O atributo preload indica se áudio será pré carregado ou não e aceita três valores:

* metadata - carrega apenas as informações sobre o arquivo.
* none - não carrega absolutamente nada até que o usuário clique no botão play
* auto - carrega o arquivo de áudio inteiro assim que a página for carregada.

Atributo `cotrols` apresenta o player na tela.

Atributo `autoplay` inicia a reprodução do áudio assim que a página for carregada.

Atributo `loop` vai fazer com que o áudio seja repetido eternamente.

E dentro da tag `<source>` adicionamos os formatos diferentes do mesmo áudio, coloque seu formato favorito como primeiro da lista, os demais só serão carregados caso o de cima falhe.

Caso todos falhem, criamos um parágrafo que permite o download do arquivo.

[Voltar a Home](../README.md)

