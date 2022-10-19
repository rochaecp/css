# CSS - Outros

~~~css
div {
  cursor: pointer;              /* Valores: wait e outros em https://www.w3schools.com/cssref/pr_class_cursor.asp */
  cursor: url(img.jpg), auto;   /* Insere imagem no lugar do cursor */
}

/* Insere texto antes de todos os parágrafos */
p:before {
  content: " texto antes dos parágrafos. ";
  color: green;
}

/* Insere texto após todos os parágrafos */
p:after {
  content: " texto depois dos paragráfos. ";
  color: red;
}

/* Insere texto apos todos parágrafos quando o mouse passa sobre o parágrafo */
p:hover:after {
  content: " texto surge ao mover mouse no parágrafo. ";
  color: blue;
  background-color: yellow;
}

/* hover: realiza estilo quando mexer mouse sobre o item */
li a:hover:not(.ativo) {
  color: green;
}

/* last-child: insere estilo somente o último item de uma série de itens. Ex.: último elemento de uma lista. */
li:last-child {
  border-right: none;
}
~~~
