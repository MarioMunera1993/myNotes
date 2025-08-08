# Copia del contenido del profe
## semana 1
## Introducción a JavaScript
JavaScript es un lenguaje de programación versátil y ampliamente utilizado que permite agregar interactividad y dinamismo a las aplicaciones web y más allá.

## ¿Qué es JavaScript?
### Definición:

1. JavaScript es un lenguaje de programación interpretado, de alto nivel y orientado a eventos, principalmente utilizado para agregar interactividad a páginas web.
2. Es multiplataforma: se ejecuta en navegadores (lado cliente) y en servidores (con entornos como Node.js).
3. Soporta paradigmas como programación funcional, orientada a objetos y basada en eventos.

### Características clave:

1. Dinámico: Permite modificar el contenido de una página web en tiempo real (por ejemplo, actualizar un texto sin recargar la página).
2. Ligero: No requiere compilación, ya que los navegadores lo interpretan directamente.
3. Estandarizado: Basado en ECMAScript, con versiones actualizadas como ES6 (2015) que introdujeron mejoras significativas.

## Historia de JavaScript

### Origen:

* Creado en 1995 por Brendan Eich en Netscape Communications.
* Inicialmente llamado Mocha, luego LiveScript, y finalmente JavaScript para capitalizar la popularidad de Java (aunque no están relacionados).
* Primer propósito: Agregar pequeñas funcionalidades interactivas a páginas web estáticas.

### Evolución:

* 1997: Estandarización como ECMAScript (ES1).
* 2009: ES5 trajo mejoras en funcionalidad.
* 2015: ES6 (ECMAScript 2015) introdujo características modernas como arrow functions, let/const, y promesas.
* Actualmente: Actualizaciones anuales (ES2020, ES2023, etc.) para mantener el lenguaje relevante.

### Impacto:

De ser un lenguaje para animaciones simples, pasó a ser la base de aplicaciones web complejas, servidores, e incluso inteligencia artificial.

## Usos y Aplicaciones
JavaScript es un pilar del desarrollo moderno debido a su flexibilidad. Sus principales usos incluyen:

1. Desarrollo web (lado cliente):
    * Manipulación del DOM (Document Object Model) para cambiar contenido, estilos o estructura de una página.
    * Ejemplos: Validar formularios, crear animaciones, manejar eventos (clics, teclas).
    * Frameworks populares: React, Vue.js, Angular.

2. Desarrollo backend (lado servidor):
    * Con Node.js, JavaScript se usa para construir servidores, APIs y aplicaciones escalables.
    * Ejemplo: Plataformas como Netflix y PayPal usan Node.js.

3. Aplicaciones móviles:
    * Frameworks como React Native permiten crear aplicaciones nativas para iOS y Android.
    * Ejemplo: Aplicaciones como Instagram y Airbnb.

4. Juegos y gráficos:
    * Bibliotecas como Three.js o Phaser permiten crear juegos 2D/3D en navegadores.
    * Ejemplo: Juegos interactivos en sitios web.

5. Otros usos:
    * Automatización (scripts con Node.js).
    * Inteligencia artificial (TensorFlow.js para modelos de machine learning).
    * Internet de las cosas (IoT) con plataformas como Johnny-Five.

### Rol en el Desarrollo Web
JavaScript es uno de los tres pilares del desarrollo web, junto con HTML y CSS:

* HTML: Define la estructura de una página (títulos, párrafos, imágenes).
* CSS: Controla el diseño y estilo (colores, fuentes, disposición).
* JavaScript: Añade interactividad y lógica (eventos, cálculos, actualizaciones dinámicas).

~~~html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de JavaScript</title>
  <style>
    button { padding: 10px; font-size: 16px; }
  </style>
</head>
<body>
  <h1 id="mensaje">¡Haz clic en el botón!</h1>
  <button onclick="cambiarMensaje()">Cambiar Mensaje</button>
  <script>
    function cambiarMensaje() {
      document.getElementById("mensaje").innerText = "¡JavaScript en acción!";
    }
  </script>
</body>
</html>
~~~
* Explicación:
    * HTML crea la estructura (título y botón).
    * CSS estiliza el botón.
    * JavaScript cambia el texto del título al hacer clic