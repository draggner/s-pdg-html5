# `<head>`

A tag `<head>` é um elemento responsável por configurar as configurações principais da página.

Geralmente, as informações que são introduzidas não são exibidas na página principal do navegador mas, tem as informações sobre o documento HTML. Por exemplo, os metadados, folhas de estilos e scripts externos.

Declaração padrão da tag:

```HTML
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    ...
  </head>
</html>  
```

<div align="center">
  <img src="../../assets/5ELEMENT_HEAD_BROWSER.png" alt="460x180">
</div>

No exemplo acima, por ser um elemento de configuração, geralmente as informações dentro dessa tag não são visiveis para o usuário.

Porém, no exemplo abaixo, é possível ver as configurações, que são visiveis porém não na página principal:

<div align="center">
  <img src="../../assets/5ELEMENT_HEAD_DEV_TOOLS.png" alt="440x400">
</div>

Nesse exemplo, é utilizado uma tag `<title>` que será introduzida em breve, porém é para mostrar que o conteúdo da tag `<head>` armazena informações de configurações que não são exibidas para o usuário.

A tag `<head>` é o segundo elemento `child` da tag `<html>`. Tem o comportamento, anteriomente mensionado, o conteúdo são as principais configurações do documento e podem ser inseridos algumas tags que serão abordados logo abaixo.