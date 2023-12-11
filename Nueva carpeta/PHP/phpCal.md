PHP admite una variedad de operaciones matemáticas, tanto para números enteros como para números de punto flotante. Aquí te muestro algunas de las operaciones matemáticas más comunes en PHP:

### Operaciones Básicas:

1. **Suma:**

   ```php
   $numero1 = 10;
   $numero2 = 5;
   $suma = $numero1 + $numero2;
   echo "Suma: $suma";  // Muestra "Suma: 15"
   ```

2. **Resta:**

   ```php
   $numero1 = 10;
   $numero2 = 5;
   $resta = $numero1 - $numero2;
   echo "Resta: $resta";  // Muestra "Resta: 5"
   ```

3. **Multiplicación:**

   ```php
   $numero1 = 10;
   $numero2 = 5;
   $multiplicacion = $numero1 * $numero2;
   echo "Multiplicación: $multiplicacion";  // Muestra "Multiplicación: 50"
   ```

4. **División:**

   ```php
   $numero1 = 10;
   $numero2 = 5;
   $division = $numero1 / $numero2;
   echo "División: $division";  // Muestra "División: 2"
   ```

### Operaciones con Asignación:

```php
$numero = 10;

// Suma con asignación
$numero += 5;  // Equivalente a $numero = $numero + 5;

// Resta con asignación
$numero -= 3;  // Equivalente a $numero = $numero - 3;

// Multiplicación con asignación
$numero *= 2;  // Equivalente a $numero = $numero * 2;

// División con asignación
$numero /= 4;  // Equivalente a $numero = $numero / 4;
```

### Operaciones Incremento/Decremento:

```php
$numero = 5;

// Incremento
$numero++;  // Equivalente a $numero = $numero + 1;

// Decremento
$numero--;  // Equivalente a $numero = $numero - 1;
```

### Operaciones con Números de Punto Flotante:

```php
$decimal1 = 10.5;
$decimal2 = 2.5;

$suma_decimales = $decimal1 + $decimal2;
$resta_decimales = $decimal1 - $decimal2;
$multiplicacion_decimales = $decimal1 * $decimal2;
$division_decimales = $decimal1 / $decimal2;
```

### Funciones Matemáticas:

PHP también proporciona muchas funciones matemáticas incorporadas que pueden realizar operaciones más complejas, como `sqrt` para la raíz cuadrada, `pow` para la potencia, `abs` para el valor absoluto, etc.

```php
$numero = 9;

$raiz_cuadrada = sqrt($numero);
$potencia = pow($numero, 2);  // Elevar al cuadrado
$valor_absoluto = abs(-7);  // Valor absoluto
```

Estos son solo algunos ejemplos de las operaciones matemáticas que puedes realizar en PHP. Puedes combinar estas operaciones y utilizar funciones matemáticas más avanzadas según tus necesidades en tu aplicación.