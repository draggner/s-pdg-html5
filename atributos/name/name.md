### Atributo - name

Para haver uma associação de dados para serem acessados no atributo `action` é necessário inserir no elemento `input` o atributo `name`, que serve para o valor presente seja representado os dados enviados.

Por exemplo,

```HTML
	<input type="text" name="email">
```

Se no campo eu informar um email qualquer, os dados serão armazenados no name e quando houver um submit no formulário, os dados será encaminhados para URL especificada no elemento `form` no atributo `action`.
