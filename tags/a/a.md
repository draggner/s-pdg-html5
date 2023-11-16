# `<a>`

O termo âncora representado pela tag `<a>` pode se comportar em criar links/converter textos/imagens para se interligar em outras páginas.

Para definir a configuração de comportamento de interligar o elemento para outra página, não precisa apenas da declaração `<a>`. É necessário inserir o atributo `href`, que serve para informar o direcionamento para a página correspodente.

Por exemplo,
```HTML
<a href="https://google.com">Click aqui</a>
```

Ao clicar no elemento `Clique aqui`, o navegador intrepeta que deve ser encaminhado para a página ligada pela tag, inicialmente inserido pelo atributo `href`, que é onde será direcionado.

Outra utilizade de uso é agrupar outros elementos de texto em HTML como forma de links, dando destaque para o elemento `<p>` de parágrafo.

```HTML
<p>Isto aqui é um parágrafo&#44; <a href="#">Click aqui para saber mais</a></p>
```
Como demostrado na imagem abaixo:
<div align="center">
  <img src="../../tags/a/Screenshot_3.png">
</div>

Apesar da intrepetação do código não ser exibido a vírgula no elemento especial, no browser é possível perceber essa exebição.

> Observação - a vírgula pode ter uma representação intrepetada atraves do elementos especiais, como `&#44;` que representa a vírgula(&#44;)