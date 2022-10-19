# CSS - Posições

~~~css
div {
  position: static;        /* Valores: static = é o padrão, não faz nada */
  position: fixed;         /* fixa elemento na posição */
  position: relative;   
  top: -20px;   
  left: 20px;              /* Deve ter top, left, ... definidas, posição relativa à pos do elem */
  position: absolute;      /* Igual fixed, porém em rel ao elem relativo mais próximo */
  display: inline-block;   /* Valores: inline (span, a), block(div, p, form, header ...), inline-block */
  direction: ltr;          /* Valores: left to right. há rtl, direciona texto dentro de div */
}
~~~
