Los **formularios funcionales** en HTML y CSS son una parte esencial de cualquier sitio web interactivo. Permiten a los usuarios introducir datos que pueden ser enviados a un servidor para su procesamiento. Aquí tienes un ejemplo de cómo se podría estructurar un formulario funcional en HTML y CSS:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mi formulario funcional</title>
        <style>
            form {
                /* Centrar el formulario en la página */
                margin: 0 auto;
                width: 400px;
                /* Esquema del formulario */
                padding: 1em;
                border: 1px solid #ccc;
                border-radius: 1em;
            }
            ul {
                list-style: none;
                padding: 0;
                margin: 0;
            }
            form li + li {
                margin-top: 1em;
            }
            label {
                /* Tamaño y alineación uniforme */
                display: inline-block;
                width: 90px;
                text-align: right;
            }
            input, textarea {
                /* Para asegurarse de que todos los campos de texto tienen la misma configuración de letra
                Por defecto, las áreas de texto tienen un tipo de letra monoespaciada */
                font: 1em sans-serif;
                /* Tamaño uniforme del campo de texto */
                width: 300px;
                box-sizing: border-box;
                /* Hacer coincidir los bordes del campo del formulario */
                border: 1px solid #999;
            }
            input:focus, textarea:focus {
                /* Destacado adicional para elementos que tienen el cursor */
                border-color: #000;
            }
            textarea {
                /* Alinear los campos de texto multilínea con sus etiquetas */
                vertical-align: top;
                /* Proporcionar espacio para escribir texto */
                height: 5em;
            }
            .button {
                /* Alinear los botones con los campos de texto */
                padding-left: 90px; /* mismo tamaño que los elementos de la etiqueta */
            }
            button {
                /* Este margen adicional representa aproximadamente el mismo espacio que el espacio entre las etiquetas y sus campos de texto */
                margin-left: 0.5em;
            }
        </style>
    </head>
    <body>
        <form>
            <ul>
                <li>
                    <label for="name">Nombre:</label>
                    <input type="text" id="name" name="user_name">
                </li>
                <li>
                    <label for="mail">E-mail:</label>
                    <input type="email" id="mail" name="user_mail">
                </li>
                <li>
                    <label for="msg">Mensaje:</label>
                    <textarea id="msg" name="user_message"></textarea>
                </li>
                <li class="button">
                    <button type="submit">Enviar tu mensaje</button>
                </li>
            </ul>
        </form>
    </body>
</html>
```
Este es un ejemplo de un formulario de contacto simple con campos para el nombre, el correo electrónico y un mensaje. Cuando el usuario hace clic en el botón “Enviar tu mensaje”, los datos del formulario se envían para su procesamiento.