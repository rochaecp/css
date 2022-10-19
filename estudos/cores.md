# CSS - Cores

- Há 147 named colors (ex blue).

~~~css
p {
  color: red;
  color: rgb(123, 20, 233);         /* Cor na base 10 */
  color: rgba(123, 88, 9, 0.5);     /* RGB Alpha 0 <= a <= 1 */
  color: #09AA34;                   /* Hexadecimal. #FFFFFF é a mesma cor que #FFF, #AA33BB é a mesma cor que #A3B */
  color: hsl(182.2, 20%, 50%);      /* HSL colors: Hue, Saturation, and Lightness; ex: hsl(182, 20%, 50%). Hue: 0 a 360. Saturation: 0% a 100%. Lightness: 0% a 100%. */
  color: hsla(239, 45%, 22%, 0.4);
  opacity: 0.5;                     /* Nível de transparencia em porcentagem */
  box-shadow: 10px 10px 5px green;
}

/* Redundância para caso o navegador não tenha suporte para rgba. 
A última declaração têm prioridade */
h1 {
  color: rgb(22, 34, 88);
  color: rgba(22, 34, 88, 0.4);
}

/* Linear Gradient */
div {
  background: linear-gradient(to top right, rgba(255, 0, 0, 0), blue, green, yellow); /* to right, left, top;  to top right /// Angulos: 80deg */
}

/* Radial Gradient */
div {
  background: radial-gradient(red, green, blue);
}
~~~