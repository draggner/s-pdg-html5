# Tag HTML - button
O elemento `button` serve para inserir um botão clicavel na aplicação web.

Geralmente, os botões são utilizados dentro do elemento `form` para quando o usuário informar os dados dentro dos elementos de entrada,`input`. E quando o usuário clicar no valor do elemento `button`, possívelmente com o atributo `submit` para informar o comportamento padrão do formulário, os dados vão ser encaminhados para URL inicialmente inserida pelo elemento `form` com atributo `action`.

Logo abaixo um exemplo de código HTML do elemento `button`

```HTML
<button>Enviar</button>
```

Em seguida a exibição,

<div align="center">
  <img src="Screenshot_6.png">
</div>

É possível perceber que o proprio navegador traz propriedades pré-estilizadas para a exibição do elemento `button`

Ao inserir um elemento `button` abaixo de um elemento `input` por exemplo, mesmo inserido um abaixo do outro, no navegador estão um ao lado do outro. É mostrado adiante na imagem abaixo:

<div align="center">
  <img src="Screenshot_7.png">
</div>

Isso ocorre porque os elementos `input` e `button` são elementos em linha (inline) o qual demostra a exibição informada.

O inline é um comportamento dos elementos estarem alinhados no HTML


## Em relação do elemento button e form

Na criação do elemento `button` dentro de um elemento `form` possui um comportamento padrão. Quando o usuário clica no botão para encaminhar as informações, isso é por padrão mas não é esplicito na aplicação.

Para não causar esses conflitos, é recomendado inserir o atributo `type` acompanhado com o valor `submit` ao elemento `button` para deixar claro que o elemento `button` é o elemento de envio do formulário.