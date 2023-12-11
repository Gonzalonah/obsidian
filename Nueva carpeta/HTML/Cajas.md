#html 
# Modelado en cajas / Sistema de cajas / Box Model
En html se trabaja con la etiqueta DIV


# Poner ejemplo


Cajas en CSS es fundamental para entender cómo se estructuran y se posicionan los elementos en una página web.

En CSS, todos los elementos HTML se representan como cajas rectangulares. Cada vez que se inserta una etiqueta HTML, se crea automáticamente una nueva caja rectangular que encierra los contenidos de ese elemento.

Existen dos tipos de cajas en CSS:

* **Cajas en bloque**: Estas cajas fuerzan un salto de línea al final de la línea y se extienden en la dirección de la línea para llenar todo el espacio disponible en su contenedor. Ejemplos de elementos de bloque incluyen los encabezados (`<h1>, <h2>, <h3>, <h4>, <h5> y <h6>`) y los párrafos (`<p>`).
* **Cajas en línea**: Estas cajas no fuerzan ningún salto de línea al final de la línea. Ejemplos de elementos en línea incluyen los enlaces (`<a>`) y los elementos `<span>`, `<em>` y `<strong>`.

Cada caja consta de varias partes:
- **Contenido**: Es la parte interior del elemento, excluyendo el relleno. 
- **Relleno (padding)**: Es la parte interior del elemento, entre el contenido y el borde. 
- **Borde (border)**: Es el límite que separa el interior del exterior del elemento. 
- **Margen (margin)**: Es la parte exterior del elemento, por fuera del borde.
# En conjunto con css
#CSS 
- El modelo de caja describe cómo se representan y dimensionan los elementos en HTML.
   - Consiste en el contenido, el relleno (padding), el borde y el margen.

   ```css
   /* Ejemplo del modelo de caja */
   div {
       width: 200px;
       padding: 20px;
       border: 2px solid black;
       margin: 10px;
   }
   ```
