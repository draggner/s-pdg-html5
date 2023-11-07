# `<html>` e `<!DOCTYPE>`

Em HTML, em todo começo antes de programar códigos em HTML, é necessário criar um arquivo com a devida extensão `.html` ou `.htm`, para que o browser consiga intrepetar que isto é um arquivo HTML e que possa realizar as devidas renderizações de elementos na página. Porém é necessário de um outro requisito que será abordado logo abaixo. 

Ambas as extensões mencionadas funcionam porém é utilizados por grande parte dos desenvolvedores a extensão `.html`

## Identificador para o Browser: `<!DOCTYPE>`

O `<!DOCTYPE>` é uma declarativa que deve ser incluida no topo do documento HTML, antes mesmo da tag `<html>`

Porém toda declarativa tem acompanhamento de uma identificação, uma forma do navegador entender e renderizar com os devidos recursos, que esse arquivo, é um documento HTML:

```HTML
<!DOCTYPE html>
```

Esse tipo de declarativa no topo do código, é uma forma necessária para os navegadores renderizarem os elementos e devidas especificações relevantes na construção da estrutura da aplicação HTML. A ausencia desse `<!DOCTYPE html>` o navegador tendem a utilizar outras formas de renderização diferente, causando certas incompatibilidade em alguas especificações de elementos, comportamentos, tags, dentre outros.


## O corpo do documento HTML

A tag `<html>` é um elemento responsavel por agrupar todo o documento HTML e inclusive as demais tags HTML. É essa tag que o browser realiza a intrepetação de todo o documento após a identificação da declarativa `<!DOCTYPE html>`. Que então, renderizará os elementos HTML com sua devida estrutura programada.

Por exemplo, de código HTML:

```HTML
<!DOCTYPE html>
<html>
  <h1>Hello, World!</h1>
</html>
```

Dessa forma, o navegador além de identificar a extensão do arquivos, do código acima, ele renderiza a tag `<h1>` com seu devido comportamento, proposito de uso e com as pré-estilizações definidas pelo browser.

<div align="center">
  <img src="../../assets/2ELEMENT_HTML_doctype_html.png" alt="400x180">
</div>