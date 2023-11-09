# href

O conceito de atributos são pré-configurações que define comportamentos específicos para uma respectiva tag.

No caso do atributo `href` possui uma funcionalidade de direcionar para um endereço especificado. Ou seja, o dominio (URL) para uma página.

O uso do atributo, a sintaxe básica de escrita é acompanhado:

```HTML
<element_name nome_atributo=""></element_name>
```

Dentre o nome da tag, com uma barra de espaço, se insere o/os atributo(s).

Existem certos atributos que não precisam de parâmetros para serem devidamente inseridos, passando os valores dentre as aspas ("").

Como mensionado, o atributo `href` aponta para uma URL especifica. Essa URL pode tornar um caminho absoluto ou relativo.

**URL Absoluto**

É quando se insere o dominio completo da página, como por exemplo: `https://exemplo.com`

**URL Relativo**

Esse dominio não é apontado para um URL e sim, aponta para um diretório correspondente. No documento dentro do site, por exemplo: `./src/img/exemplo.jpg`

Quando se utiliza esse apontamento para o diretório, quer dizer que "src" está dentro do diretório raiz (`/`) e que tem outra pasta para aponta na imagem correspodente.

> Observação: Ao apontar para outro diretório sem especificar no atributo, o servidor web normalmente pode retornar para o documento "index.html" dentro desse diretório.
