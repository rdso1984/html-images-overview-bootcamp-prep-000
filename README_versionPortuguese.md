# Criando Imagens em HTML

Você as têm visto em todo lugar. Imagens fazem a internet atraente e divertida. A habilidade para adicionar imagens em webpages é, primeiro de tudo, especificações da HTML. Isso é o como importante ela é. A melhor parte é que adicionar imagens é tão importante quanto _fácil_. Que grande combinação.

Imagens são adicionadas a webpage com a tag `img`. Dê uma olhada abaixo no CodePen interface.

<iframe height='265' scrolling='no' title='HTML Images' src='//codepen.io/joemburgess/embed/rwjooK/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/rwjooK/'>HTML Images</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Na esquerda você verá o seguinte código:

```html
<img src="https://curriculum-content.s3.amazonaws.com/web-development/FIS_New_Logo.png">
```

À direita você vê o nosso logo. Essa tag tem uma coisa que você nunca viu antes: um atributo. A image tag tem um atributo chamado `src` atributo. Para carregar uma imagem, nós colocamos o atributo `src` igual a URL (entre `"`) da imagem que nós queremos. Nesse específico caso a URL é:

```
https://curriculum-content.s3.amazonaws.com/web-development/FIS_New_Logo.png
```

Se nós queremos alterar a imagem para alguma outra coisa, nós simplesmente precisamos alterar a URL para uma imagem diferente. Aqui está outra URL para utilizar:

```
https://curriculum-content.s3.amazonaws.com/web-development/circle_logo.jpg
```

Vá em frente e mude o código HTML para usar essa nova URL, como assim:


```html
<img src="https://curriculum-content.s3.amazonaws.com/web-development/circle_logo.jpg">
```

Você agora deve ver nosso logo em círculo ao invés do logo todo. Parabéns! Agora você sabe como adicionar imagens a websites usando a tag `img` com o atributo `src`. Muito legal :)
