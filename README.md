# Culinary-lab
Archivos bases proyecto de maquetación culinary-lab

# Elementos de apoyo


**Links:**
https://bootsnipp.com/?page=6

https://bootsnipp.com/snippets/featured/grid-columns-divider
https://bootsnipp.com/snippets/featured/responsive-simple-testimonials

**Sección 2**
https://bootsnipp.com/snippets/featured/responsive-bs-carousel-with-hero-headers
https://bootsnipp.com/snippets/featured/header-curtain-effect

**Sección 3**
https://bootsnipp.com/snippets/featured/simple-responsive-carousel
https://bootsnipp.com/snippets/featured/thumbnail-carousel-single-image-sliding

**Sección 4**
https://bootsnipp.com/snippets/featured/responsive-quote-carousel
https://bootsnipp.com/snippets/featured/simple-subscribe-form

**Sección 5**
https://bootsnipp.com/snippets/featured/pricing-tables
https://bootsnipp.com/snippets/featured/fade-quote-carousel

https://bootsnipp.com/snippets/featured/responsive-bs-carousel-with-hero-headers

https://bootsnipp.com/snippets/featured/thumbnail-carousel



*Entre otros . . .*


## Detalles en Código
Proyecto Maquetado - Culinary Lab - Lección 30 - 14 Junio 2017

## HTML:
1º Se enlazan los elementos a utilizar para el proyecto.

 	```<!-- meta:vp para que aparezca la etiqueta de abajo echa lista -->
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">```

  ```<!-- Tipografía e Iconos-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Poppins:300,400,500,600,700&amp;subset=devanagari,latin-ext" rel="stylesheet">```
    
 ```<!-- Conectando los css -->
    <link rel="stylesheet" href="assets/bootstrap.css">
    <link rel="stylesheet" href="assets/media.css">
    <link rel="stylesheet" href="assets/style.css">```
    
*Conectando antes del cierre del body, los elementos de javascript*

 ```<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>```

 ```<!-- Bootstrap Latest compiled and minified JavaScript -->
    <script type="text/javascript" src="assets/bootstrap.js"></script>
    <script type="text/javascript" src="assets/funciones.js"></script>```

**Sección 1 Material**
1° Analizaremos un poco el Nav. Según la información adquerida de https://www.w3schools.com/bootstrap/bootstrap_navbar.asp:
*"Con Bootstrap, una barra de navegación se puede extender o contraer, dependiendo del tamaño de la pantalla.
  Una barra de navegación estándar se crea con ```<nav class="navbar navbar-default">```."*
  
*"Algunas reglas del sistema de Grilla Bootstrap:

  1.- Filas (row) deben ser colocados dentro de un .container(ancho fijo (fixed-width)) o .container-fluid(ancho completo (full-width)) para la alineación y el relleno adecuado (padding).
  2.- Utilice row para crear grupos de columnas horizontales.
  3.- El contenido debe ser colocado dentro de las columnas, y sólo las columnas puede ser hijos inmediatos de filas.
  4.- Clases predefinidas les gusta .row y .col-sm-4 están disponibles para hacer rápidamente diseños de cuadrícula (grid layouts).
  5.- Columnas crean canalones (huecos entre contenido de la columna) a través de relleno. Que el relleno se compensa (offset) en filas para la primera y última columna a través de margen negativo en.rows.
  6.- Columnas de la cuadrícula se crean especificando el número de 12 columnas disponibles que desea abarcar. Por ejemplo, tres columnas iguales usarían tres.col-sm-4.

  "*

Vista Previa del Ejercicio --> https://m2b0c17.github.io/culinary-lab/

