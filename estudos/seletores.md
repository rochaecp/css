# CSS Seletores

> Ex.: um seletor:
~~~css
p {
  font-size: 42px; /* Edita parágrafo <p> (...) </p> */
}
~~~

> Ex.: multiplos seletores:
~~~css
h1, h2, p {
  color: green;
}
~~~

> Ex.: seleciona o caption de todas tabelas:
~~~css
table caption {
  color: green;
}
~~~

> Ex.: seletor universal - se aplica a todos elementos da página:
~~~css
* {
  color: green;
}
~~~

> Ex.: seletor atributo aplica propriedade somente a inputs do tipo submit:
~~~css
input[type="submit"] {
  width: 300px;
}
~~~

## IDs:

- Só pode haver um elemento na página com um determinado ID.

~~~css
#header {
  color: green;
}
~~~

## Classes:

- Diversos elementos podem possuir a mesma classe.

~~~css
.container {
  color: #008000;
}

div.container {
  color: green;
}
~~~

> Ex.: formata todos os parágrafos da classe .breaking:
~~~css
p.breaking {
  color: green;
}
~~~

> Ex.: formata os <p> com class=enf q estiver dentro da div class=cont
~~~css
div.cont p.enf {
  color: green;
}
~~~
