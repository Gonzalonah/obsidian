Claro, aquí te presento ejemplos detallados de las estructuras de control `if`, `while`, `for`, y `foreach` en PHP:

### Estructura `if` (condicional): 
#decisiones #condicional

La estructura `if` permite ejecutar un bloque de código si una condición es verdadera.

```php
$edad = 18;

if ($edad >= 18) {
    echo "Eres mayor de edad.";
} else {
    echo "Eres menor de edad.";
}
```

### Estructura `while` (bucle mientras):
#bucles

La estructura `while` ejecuta un bloque de código mientras una condición sea verdadera.

```php
$contador = 1;

while ($contador <= 5) {
    echo "Iteración $contador <br>";
    $contador++;
}
```

### Estructura `for` (bucle for):
#bucles 
La estructura `for` proporciona una forma compacta de iterar un bloque de código un número específico de veces.

```php
for ($i = 1; $i <= 5; $i++) {
    echo "Iteración $i <br>";
}
```

### Estructura `foreach` (bucle foreach):
#bucles 
La estructura `foreach` se utiliza para iterar sobre arrays o colecciones.

```php
$colores = array("rojo", "verde", "azul");

foreach ($colores as $color) {
    echo $color . "<br>";
}
```

### Nota sobre `foreach` con arrays asociativos:

Cuando trabajas con arrays asociativos (clave-valor), puedes usar `foreach` de esta manera:

```php
$persona = array("nombre" => "Juan", "edad" => 25, "ciudad" => "Madrid");

foreach ($persona as $clave => $valor) {
    echo "$clave: $valor <br>";
}
```

Estos son ejemplos básicos, y estas estructuras pueden combinarse y anidarse según sea necesario en tu código. Además, ten en cuenta que las estructuras `while` y `for` también pueden tener condiciones más complejas y ser utilizadas para iterar sobre elementos más dinámicos. Estas estructuras de control son fundamentales para la lógica y el flujo de ejecución en PHP.