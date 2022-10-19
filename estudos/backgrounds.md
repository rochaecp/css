# CSS - Backgrounds

~~~ css
div {
  background-image: url("../img/hogwarts3.jpg"), url("../img/hogwarts.jpg");
  background-size: 95% 95%;           /* Valores: cover=cobre toda a tela */
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-color: #e6eeff;
  background-position: center center; /* x e y bottom */
  background-origin: content-box;     /* or border-box */
  background-clip: padding-box;       /* content-box   */
  background: url(img_flwr.gif) right bottom no-repeat, url(paper.gif) left top repeat;
  background: radial-gradient(#ccf2ff, #80cbff, #1aa1ff, #002d4d);
}
~~~
