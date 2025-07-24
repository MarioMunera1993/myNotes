## Apuntes De HTML
```markdown
# Curso Completo de HTML: De Cero a Experto

¡Bienvenido al Curso Completo de HTML! Esta guía está diseñada para llevarte desde los conceptos más básicos hasta un nivel experto en HTML.

---

## Módulo 1: Introducción a HTML

En este módulo, descubrirás qué es HTML, su evolución y por qué es la base del desarrollo web. Exploraremos la estructura básica de un documento HTML y aprenderemos sobre etiquetas, elementos y atributos esenciales.

### 1.1 ¿Qué es HTML?
HTML (HyperText Markup Language) o Lenguaje de Marcado de Hipertexto es el componente fundamental de la World Wide Web. [19] No es un lenguaje de programación, sino un lenguaje de marcado que se utiliza para estructurar el contenido de una página web. [6, 9]

*   **Hipertexto:** Se refiere a los enlaces que conectan páginas web entre sí.
*   **Lenguaje de marcado:** Se refiere al uso de etiquetas para \"marcar\" o definir elementos dentro de un documento.

### 1.2 Estructura básica de un documento HTML
Todo documento HTML tiene una estructura fundamental que los navegadores interpretan para mostrar el contenido. [8, 15]

```html
<!DOCTYPE html>
<html>
<head>
    <title>Título de la Página</title>
</head>
<body>
    <h1>Mi primer encabezado</h1>
    <p>Mi primer párrafo.</p>
</body>
</html>
```

*   `<!DOCTYPE html>`: Define que el documento es de tipo HTML5. [1]
*   `<html>`: Es el elemento raíz de una página HTML. [1]
*   `<head>`: Contiene metadatos sobre el documento, como el título. [1, 15]
*   `<title>`: Especifica el título que se muestra en la pestaña del navegador. [1, 15]
*   `<body>`: Contiene el contenido visible de la página web. [1, 11]

### 1.3 Elementos y Etiquetas
HTML se compone de elementos que se escriben utilizando etiquetas. [13] Las etiquetas suelen venir en pares: una de apertura y una de cierre. [4]

*   **Etiqueta de apertura:** `<h1>`
*   **Contenido:** El texto o elemento que se ve afectado.
*   **Etiqueta de cierre:** `</h1>`

### 1.4 Atributos
Los atributos proporcionan información adicional sobre los elementos HTML. Se especifican siempre en la etiqueta de apertura.

*   **Ejemplo:** El atributo `href` en un enlace:
    ```html
    <a href=\"https://www.google.com\">Ir a Google</a>
    ```

---

## Módulo 2: Fundamentos de HTML

Este módulo se centra en las etiquetas y elementos esenciales para construir el contenido de una página web.

### 2.1 Encabezados y Párrafos
Los encabezados se utilizan para estructurar el contenido jerárquicamente, desde `<h1>` (el más importante) hasta `<h6>`. [1] Los párrafos se definen con la etiqueta `<p>`. [4]

```html
<h1>Encabezado de Nivel 1</h1>
<h2>Encabezado de Nivel 2</h2>
<p>Este es un párrafo de texto.</p>
```

### 2.2 Formato de Texto
Existen diversas etiquetas para dar formato al texto:

*   `<strong>` o `<b>`: Para texto en negrita.
*   `<em>` o `<i>`: Para texto en cursiva.
*   `<u>`: Para texto subrayado.
*   `<small>`: Para texto más pequeño. [11]

### 2.3 Listas
HTML ofrece dos tipos principales de listas:

*   **Listas ordenadas (`<ol>`):** Los elementos se numeran.
*   **Listas no ordenadas (`<ul>`):** Los elementos se marcan con viñetas.

Cada elemento de la lista se define con la etiqueta `<li>`.

```html
<ol>
  <li>Primer elemento</li>
  <li>Segundo elemento</li>
</ol>

<ul>
  <li>Elemento con viñeta</li>
  <li>Otro elemento con viñeta</li>
</ul>
```

### 2.4 Enlaces (Hipervínculos)
Los enlaces se crean con la etiqueta `<a>` y el atributo `href`. [8]

```html
<a href=\"https://www.wikipedia.org\">Visita Wikipedia</a>
```

### 2.5 Imágenes
Las imágenes se insertan con la etiqueta `<img>`, que es una etiqueta vacía (no tiene etiqueta de cierre).

*   El atributo `src` especifica la ruta de la imagen.
*   El atributo `alt` proporciona un texto alternativo por si la imagen no se puede mostrar.

```html
<img src=\"imagen.jpg\" alt=\"Descripción de la imagen\">
```

---

## Módulo 3: Tablas y Formularios

Aprende a organizar datos en tablas y a recopilar información del usuario mediante formularios.

### 3.1 Creación de Tablas
Las tablas se crean con la etiqueta `<table>`.

*   `<tr>`: Define una fila de la tabla.
*   `<th>`: Define una celda de encabezado.
*   `<td>`: Define una celda de datos.

```html
<table>
  <tr>
    <th>Nombre</th>
    <th>Apellido</th>
  </tr>
  <tr>
    <td>Juan</td>
    <td>Pérez</td>
  </tr>
</table>
```

### 3.2 Formularios HTML
Los formularios se crean con la etiqueta `<form>` y se utilizan para recopilar datos del usuario.

### 3.3 Elementos de Formulario
Existen diversos elementos de entrada (`<input>`) y otros elementos para construir formularios:

*   `<input type=\"text\">`: Campo de texto de una línea.
*   `<input type=\"password\">`: Campo de contraseña.
*   `<input type=\"submit\">`: Botón para enviar el formulario.
*   `<textarea>`: Área de texto de múltiples líneas.
*   `<select>`, `<option>`: Lista desplegable.
*   `<input type=\"checkbox\">`: Casilla de verificación.
*   `<input type=\"radio\">`: Botón de opción.

```html
<form>
  <label for=\"nombre\">Nombre:</label><br>
  <input type=\"text\" id=\"nombre\" name=\"nombre\"><br>
  <label for=\"apellido\">Apellido:</label><br>
  <input type=\"text\" id=\"apellido\" name=\"apellido\"><br><br>
  <input type=\"submit\" value=\"Enviar\">
</form>
```

---

## Módulo 4: HTML Semántico

El HTML semántico utiliza etiquetas que describen el significado del contenido, mejorando la accesibilidad y el SEO.

### 4.1 ¿Qué es el HTML Semántico?
Consiste en utilizar las etiquetas HTML para su propósito previsto, aportando significado al contenido. [12]

### 4.2 Elementos Estructurales Semánticos
HTML5 introdujo nuevos elementos para definir las diferentes partes de una página web: [1]

*   `<header>`: Define la cabecera de una página o sección.
*   `<nav>`: Contiene los enlaces de navegación. [1]
*   `<main>`: Especifica el contenido principal de la página. [1]
*   `<section>`: Define una sección dentro de un documento.
*   `<article>`: Representa contenido independiente y autocontenido. [2]
*   `<aside>`: Para contenido relacionado pero separado del principal (como una barra lateral). [2]
*   `<footer>`: Define el pie de página.

---

## Módulo 5: Multimedia en HTML5

HTML5 facilitó la incrustación de contenido multimedia sin necesidad de plugins externos.

### 5.1 Vídeo
El elemento `<video>` se utiliza para incrustar vídeos.

```html
<video controls width=\"250\">
    <source src=\"video.mp4\" type=\"video/mp4\">
    Tu navegador no soporta la etiqueta de vídeo.
</video>
```

### 5.2 Audio
De forma similar, el elemento `<audio>` se utiliza para el sonido. [2]

```html
<audio controls>
    <source src=\"audio.mp3\" type=\"audio/mpeg\">
    Tu navegador no soporta la etiqueta de audio.
</audio>
```

---

## Módulo 6: Temas Avanzados

Este módulo explora funcionalidades avanzadas de HTML5.

### 6.1 Atributos `data-*`
Permiten almacenar información adicional privada en los elementos HTML.

```html
<article data-id-articulo=\"12345\" data-categoria=\"noticias\">
...
</article>
```

### 6.2 Canvas y SVG
*   **`<canvas>`**: Se utiliza para dibujar gráficos sobre la marcha a través de JavaScript. [2]
*   **`<svg>`**: Se utiliza para gráficos vectoriales escalables.

### 6.3 Geolocation API
Permite al usuario compartir su ubicación con una aplicación web.

### 6.4 Web Storage
Proporciona a las aplicaciones web métodos para almacenar datos en el navegador del cliente.

*   **`localStorage`**: Almacena datos sin fecha de caducidad.
*   **`sessionStorage`**: Almacena datos para una sesión (los datos se pierden al cerrar la pestaña del navegador).

### 6.5 Web Workers
Son una forma de que las aplicaciones web ejecuten scripts en segundo plano de forma independiente de la interfaz de usuario.

---

## Módulo 7: Accesibilidad Web (A11y)

Escribir HTML accesible garantiza que personas con discapacidades puedan utilizar la web.

### 7.1 Atributos ARIA
Los atributos de *Accessible Rich Internet Applications* (ARIA) ayudan a que las aplicaciones web dinámicas sean más accesibles.

### 7.2 Uso correcto de `alt` en imágenes
El texto alternativo es crucial para los lectores de pantalla.

### 7.3 Formularios Accesibles
Asegúrate de que todos los campos del formulario estén correctamente etiquetados con `<label>`.

---

## Módulo 8: Mejores Prácticas y Recursos

Consejos finales y recursos para continuar tu aprendizaje.

### 8.1 Validación de HTML
Utiliza herramientas como el [Validador de W3C](https://validator.w3.org/) para comprobar que tu código HTML es correcto.

### 8.2 Mantente Actualizado
La tecnología web evoluciona constantemente. Sigue blogs y documentación de confianza como [MDN Web Docs](https://developer.mozilla.org/). [4]

### 8.3 Referencias de Etiquetas
*   [Referencia de Elementos HTML de MDN](https://developer.mozilla.org/es/docs/Web/HTML/Element) [11]
*   [Lista completa de etiquetas HTML5](https://www.w3schools.com/tags/default.asp)

---

¡Felicidades por completar el curso! Ahora tienes una base sólida para crear sitios web estructurados y semánticos. El siguiente paso natural es aprender CSS para dar estilo a tus páginas y JavaScript para añadir interactividad. [3, 10]
```"""