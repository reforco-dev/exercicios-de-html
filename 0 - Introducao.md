## Introdução ao HTML
HTML é uma das linguagens que compõe o kit básico de programação web, para criar sites, blogs e outros sistemas web, ele vai fornecer a estrutura para a aplicação semelhante à um edifício que precisa de colunas, paredes e fundação, esse estrutura poderá ser personalizada com CSS posteriormente.

### Extensões úteis

- Live Server: simula um servidor e evita que você precise recarregar a página à cada alteração no código;
- Auto Complete Tag: ajuda você a não esquecer de fechar as tags;

### Tags

Tags são a matéria prima que compõe uma página, assim como uma casa precisa de tijolos, concreto, telhas, uma página web precisa de tags específicas para compor sua estrutura, praticamente todas as tags tem uma finalidade e devem ser utilizadas adequadamente, porem, caso utilizi-as de modo "errado" isso não trará prejuízos na estrutura em si, mas pode atrapalhar na indexização da sua página.

### Estrutura básica

Abaixo você pode ver a base de uma página web, que é composta por a tag html e dentro dela as tags head e body, a tag head é onde inserimos informações sobre à página e também conectamos bibliotecas externas, no body é onde de fato inserimos nosso código e formamos as estruturas vísiveis para os usuários.

Perceba que quase todas as tags são formadas por uma abertura \<\> e um fechamento \<\/\>.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

### Tags de texto

O ideal numa estrutura HTML é que não tenha textos soltos pra isso podemos usar várias tags de texto diferentes para inserir este conteúdo.

Tags para cabeçalho;

```html
<h1>Cabeçalho 1</h1>
<h2>Cabeçalho 2</h2>
<h3>Cabeçalho 3</h3>
<h4>Cabeçalho 4</h4>
<h5>Cabeçalho 5</h5>
<h6>Cabeçalho 6</h6>
```

Tag para parágrafo;

```html
<p>parágrfo parágrfo parágrfo parágrfo parágrfo parágrfo parágrfo parágrfo parágrfo.</p>
```

Tags para deixar o texto em negrito;

```html
<b>Negrito</b>
<strong>Negrito</strong> 
```

Tags para deixar o texto em itálico;

```html
<i>Negrito</i>
<em>Negrito</em> 
```

