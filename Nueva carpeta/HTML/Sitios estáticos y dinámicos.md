Los **sitios web estáticos** son aquellos que muestran el mismo contenido a todos los usuarios y no cambian en función de las acciones del usuario. Son ideales para sitios web simples o con contenido estático que no necesita actualizarse con frecuencia.

Aquí tienes un ejemplo de cómo se podría estructurar un sitio web estático en HTML y CSS:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mi sitio web estático</title>
        <link rel="stylesheet" href="estilos.css">
    </head>
    <body>
        <h1>Bienvenidos a mi sitio web estático</h1>
        <p>Este es un ejemplo de contenido estático.</p>
    </body>
</html>
```
```css
body {
    background-color: lightblue;
}

h1 {
    color: navy;
    margin-left: 20px;
}
```
Algunos ejemplos de sitios web estáticos incluyen:
1. Bootstrap: Este es un sitio web que ofrece una amplia gama de componentes y estilos predefinidos para facilitar el desarrollo de sitios web responsivos y móviles.
2. TwitchCon: Este es un sitio web que proporciona información sobre el evento anual de Twitch, incluyendo detalles sobre los oradores, la programación y cómo comprar entradas.
3. Collins: Este es un sitio web de una agencia de diseño que muestra su cartera de trabajo.
4. Camilo Holguin: Este es un sitio web personal que muestra la cartera de trabajo del diseñador Camilo Holguin. 
5. Prism: Este es un sitio web que ofrece una biblioteca de resaltado de sintaxis.

Los **sitios web dinámicos**, por otro lado, pueden mostrar contenido diferente a diferentes usuarios, y el contenido puede cambiar en función de las acciones del usuario. Son ideales para sitios web que requieren actualizaciones frecuentes, como tiendas en línea, blogs o plataformas de noticias.

Aquí tienes un ejemplo de cómo se podría estructurar un sitio web dinámico en HTML, CSS y JavaScript:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mi sitio web dinámico</title>
        <link rel="stylesheet" href="estilos.css">
        <script src="script.js"></script>
    </head>
    <body>
        <h1>¡Bienvenidos a mi sitio web dinámico!</h1>
        <p id="mensaje">Este es un ejemplo de contenido dinámico generado con JavaScript.</p>
        <button onclick="cambiarMensaje()">Cambiar mensaje</button>
    </body>
</html>
```
```css
body {
    background-color: lightblue;
}

h1 {
    color: navy;
    margin-left: 20px;
}
```
```javascript
function cambiarMensaje() {
    document.getElementById("mensaje").innerHTML = "El mensaje ha cambiado!";
}
```
Algunos ejemplos de sitios web dinámicos incluyen:
1. Página de Marketplace de Facebook: Facebook es uno de los ejemplos más claros de página web dinámica. Cada vez que actualizas la página o entras a tu sitio de noticias encuentras diferentes publicaciones de tus amigos. 
2. Ofertas del día de Amazon: Amazon es una de las tiendas en línea más grandes del mundo. Cada vez que visitas la página, te muestra diferentes ofertas del día. 
3. Cesta de compras de Carrefour: Carrefour es un ejemplo de un sitio de comercio electrónico. Cuando añades productos a tu cesta de compras, la página se actualiza dinámicamente para reflejar los cambios.