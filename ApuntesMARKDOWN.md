# Guía Completa de Markdown

Markdown es un lenguaje de marcado ligero que te permite aplicar formato a texto usando un editor de texto plano. Su principal ventaja es que es fácil de leer y escribir, incluso sin ser procesado, y se convierte fácilmente a HTML y otros formatos.

## Sintaxis Básica

A continuación, se presentan los elementos fundamentales de la sintaxis de Markdown.

### Encabezados

Para crear encabezados, utiliza el símbolo de almohadilla (`#`) al principio de la línea. El número de almohadillas corresponde al nivel del encabezado (del 1 al 6).

```markdown
# Encabezado de Nivel 1
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### Encabezado de Nivel 6
```

### Párrafos y Saltos de Línea

Para crear un párrafo, simplemente separa el texto con una línea en blanco. [2] Para forzar un salto de línea dentro de un párrafo, termina la línea con dos o más espacios en blanco antes de presionar enter. [3]

```markdown
Esto es un párrafo.

Este es otro párrafo.

Esta línea tiene un salto de línea al final (dos espacios)  
y esta es la siguiente línea.
```

### Énfasis en el Texto

Puedes dar énfasis al texto utilizando asteriscos (`*`) o guiones bajos (`_`).

*   **Cursiva:** Envuelve el texto con un asterisco o un guión bajo. [20]
*   **Negrita:** Envuelve el texto con dos asteriscos o dos guiones bajos. [20]
*   **Negrita y Cursiva:** Envuelve el texto con tres asteriscos o tres guiones bajos.
*   **Tachado:** Envuelve el texto con dos virgulillas (`~~`). [18]

```markdown
*Este texto está en cursiva.*
_Este también está en cursiva._

**Este texto está en negrita.**
__Este también está en negrita.__

***Este texto está en negrita y cursiva.***

~~Este texto está tachado.~~
```

### Citas en Bloque

Para crear una cita en bloque, añade un signo de mayor que (`>`) al principio de la línea. [5]

```markdown
> Esta es una cita en bloque.
>
> > También puedes anidar citas en bloque.
```

### Listas

Markdown soporta tanto listas ordenadas como desordenadas.

#### Listas Desordenadas

Utiliza asteriscos (`*`), signos de más (`+`) o guiones (`-`) para crear listas desordenadas. [11]

```markdown
* Elemento 1
* Elemento 2
  * Subelemento 2.1
  * Subelemento 2.2
* Elemento 3
```

#### Listas Ordenadas

Utiliza números seguidos de un punto para crear listas ordenadas. [2]

```markdown
1. Primer elemento
2. Segundo elemento
3. Tercer elemento
```

### Código

Puedes formatear código tanto en línea como en bloques.

#### Código en Línea

Envuelve el código con comillas invertidas (`` ` ``) para mostrarlo en línea. [10]

```markdown
Usa la función `printf()` para imprimir en la consola.
```

#### Bloques de Código

Para crear un bloque de código, indenta cada línea con al menos cuatro espacios o una tabulación, o utiliza "vallas de código" (tres comillas invertidas ``` o tres virgulillas `~~~`) antes y después del bloque. Puedes especificar el lenguaje de programación después de las comillas de apertura para el resaltado de sintaxis.

````markdown
```python
def hola_mundo():
    print("¡Hola, Mundo!")
```