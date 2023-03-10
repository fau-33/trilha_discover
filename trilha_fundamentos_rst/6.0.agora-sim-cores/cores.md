# Cores

Usamos CSS para alterar cores em nosso documento.

## Tipos

* Background-color (para caixas)
* color (para textos)
* border-color (para-caixas)
* outros...

## Valores

Podemos definir os valors por:

* palavra-chave (blue, transparent)
* hexadecimal (#990011)
* funções: rgb, rgba, hsl, hsla

```css
element {
  /* keyword values*/
  color: currentcolor;

  /* <named-color> values*/
  color: red;
  color: orange;
  color: tan;
  color: rebeccapurple;

   /* <hex-color> values 0-F*/
   color: #090; /* RED GREEN BLUE*/
   color: #009900;
   color: #090a;
   color: #009900aa;

   /* <rgb()> values*/
   color: rgb(34, 12, 64, 0.6); /* 0 - 255 */
   color: rgba(34, 12, 64, 0.6);
   color: rgb(34 12 64 / 0.6);
   color: rgba(34 12 64 / 0.3);
   color: rgba(34.0 12 64 / 60%);
   color: rgba(34.6 12 64 / 30%);

   /* <hsl()> values*/
  color: hsl(30, 100%, 50%, 0.6); /* Hue - Saturation - Lumiance */
  color: hsl(30, 100%, 50%, 0.6);
  color: hsl(30 100% 50% / 0.6);
  color: hsla(30 100% 50% / 0.6);
  color: hsl(30.0 100% 50% / 60%);
  color: hsl(30.2 100% 50% / 60%);

  /* Global Values*/
  color: inherit;
  color: initial;
  color: unset;

}
```
