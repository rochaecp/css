# CSS - Textos e fontes

- Web Safe Fonts: fontes encontradas na maioria dos dispositivos;
- Quando o valor de uma propriedade é 0 não precisamos incluir a unidade.
- Quando adicionamos 2 fontes: caso a primeira não funcione a segunda é utilizada.

~~~css
.classeTexto {
  font-family: cursive, Times;      /* Redundância para fontes. */
  font-family: "Times New Roman";   /* Usamos "" para fontes com mais de uma palavra. */
  font-size: 18px;                  /* px = pixels, em 200% ou em 1.3em */
  font-style: italic;               /* Valores: normal, italic, oblique*/
  font-weight: bold;                /* Valores: normal, 100, 200, ..., 800, 900*/
  text-transform: uppercase;        /* Valores: uppercase, capitalize, lowercase */
  text-decoration: underline;       /* Padrão Default browsers: Times New Roman*/
  text-shadow: 2px 2px 4px #FF0000; /* Valores: overline, underline */
  text-indent: 30px;                /* Posição horiz, vertical, desfoque e cor */
  text-align: left;                 /* Valores: center right */
  font-variant: small-caps;         /* Valores: normal, small-caps */
  word-spacing: 0.3em;              /* Valores: default = 0.25em */
  letter-spacing: 0.3em;
  line-height: 1.8;
  white-space: nowrap;              /* Valores: pre, pre-line, pre-wrap, initial */
  color: white;
  line-height: 1.7em;               /* Valores: em px ou ems aumentar espaço entre linhas*/
}
~~~
