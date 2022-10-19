# CSS - Transition

- A propriedade transition suaviza a transição de estado.

~~~css
div {
  transition-property: all;                         /* width height all  */
  transition-duration: 1s;                          /* Sempre em segundos! */
  transition-delay: 2s;                             /* Tempo de espera para iniciar a transição.*/
  transition-timing-function: ease;                 /* Valores: ease, ease-in, ease-out, ease-in-out, linear */
  transition: width 2s linear 1s, height 2s linear; /* Insere no estilo do objeto que irá mudar */
}
~~~
