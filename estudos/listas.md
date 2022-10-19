# CSS Listas

- O navegador insere um padding padrão;
- "\1F44D" = um emoji

> Ex.: lista não ordenada:
~~~css
ul {
  list-style-type: none;            /* Valores: square, "\1F44D" */
  list-style-image: url('a.jpg');   /* Imagem */
  overflow: hidden;                 /* Valores: scroll, hidden, auto, visible */
}
~~~

> Ex.: lista ordenada:
~~~css
ol {
  list-style-type: none;  /* Valores: upper-roman*/ 
}
~~~

> Ex.: last-child: aplica a propriedade somente ao último ítem de uma sequência de itens
~~~css
li:last-child {
  border-right: none;
}
~~~
