


**CSS3:**

Las hojas de estilo CSS pueden aplicarse de tres formas:
+ **Hoja de estilo externa**: El CSS está escrito en un archivo independiente con una extensión .css y se vincula desde un elemento `<link>` de HTML.
+ **Hoja de estilo interna**: Colocas tu CSS dentro de un elemento `<style>` contenido dentro del elemento `<head>` del HTML.
+ **Estilo en línea**: Aplicas el estilo directamente a un elemento HTML específico utilizando el atributo `style`.

La estructura de un documento CSS se basa en la organización del código siguiendo el formato del siguiente bloque:

```css
selector {
    propiedad: valor; /* Comentario */
}
```

- **Selector**: Elemento o elementos del documento que vamos a seleccionar para aplicarle un estilo concreto.
- **Propiedad**: Característica principal que vamos a definir con el valor indicado a continuación.
- **Valor**: Cada propiedad tiene una serie de valores concretos asignables, con los que tendrá uno u otro comportamiento.
- **Comentario**: Fragmento de texto entre `/* y */` con anotaciones o aclaraciones para el desarrollador (el navegador los ignorará)