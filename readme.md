# Creando las primeras páginas web
Link de la página: [https://angeldiaz-21.github.io/barberia-alura/](https://angeldiaz-21.github.io/barberia-alura/)
## HTML5 Y CSS3 parte 1: Mi primera página web

En este curso se vio lo que es el HTML y CSS, la estructura básica de una archivo HTML, a definir estilos para los elementos usando CSS dando como resultado el desarrollo de una página web.

### ¿Que se aprendió a lo largo de este curso?

* Introducción al HTML y sus etiquetas.
* Como definir el título y los párrafos de un texto, utilizando las etiquetas `<h1>` y `<p>`, respectivamente.
* Como destacar ciertas oraciones o palabras con la etiqueta `<strong>`.
* Como dar énfasis a ciertas partes del texto con la eitiqeuta `<em>`.
* Uso de la etiqueta `<DOCTYPE>` para definir la versión de HTML que se esta utilizando.
* Uso de la etiqueta `<html>` que marca el contenid a ser renderizado en el navegador. Dentro se puede definir el lenguaje de la página a través de la propiedad `lang`.
* Cómo pasar las informaciones del encoding de la página para el navegador a través de la etiqueta `<meta>` y de la propieda `charset`.
* Uso de la etiqueta `<title>` para definir el título de la página.
* Separar la información que esta siendo pasada al navegador utilizando la etiqueta `<head>`.
* Separar el contenido de la página utilizando la etiqueta `<body>`.
* Configurar la presentación de los textos: Alineamiento, tamaño de la fuente, el color del fondo y el color del texto.
* Aplicar estilos CSS.
* Como adicionar una imagen en la página.
* Como ajustar la altura y la anchura de un elemento con la propiedad `height` y `widt`, respectivamente.
* Uso de la propiedad `padding` y `margin`.
* Como usar las listas ordenadas y no ordenadas (`ol` y `ul`).
* Concepto de clases y como referenciarla en el CSS.
* Divisiores de contenido utilizando la etiqueta `<div>`
* Los comportamientos `inline` y `block`.
* El concepto de encabezado de página y como crearlo.

## HTML5 y CSS3 parte 2: Posicionamiento, listas y navegación

En este curso se vio la forma de navegar entre páginas web, el reset.css y el posicionamiento por el CSS, las diferencias entre inline-block, lidiar con los bordes y capturar eventos con CSS, crear el encabezado y pie de página de una página web.

### ¿Que se aprendió a lo largo de este curso?

* Crear links para movernos a otras páginas con la etiqueta `<a>` y como quitar su decoración.
* Como transformar el texto para tener todas las letras en mayúsculas con la propiedad `text-transform`.
* Como quitar los estilos que el navegador crea automáticamente.
* Como funcionan los posicionamientos static, relative y absolute de los elementos.
* Uso de la etiqueta `<main>` para el contenido principal de la página.
* A crear listas complejas con títulos, imágenes y párrafos.
* A utilizar la propiedad `inline-block`.
* A practicar y estilizar el contenido principal de la página productos.
* Aplicar bordes a los elementos y bordes redondeados con las propiedades `border` y `border-radius` respectivamente.
* Uso de pseudo clases CSS como:
  * *hover*: Cuando el usuario pasa el cursor sobre el elemento. En este caso se ocupo para cambiar el tamaño de fuente, el color de fondo, border redondeados e incluso a implementar una transition.
  * *active*: Cuando un elemento está siendo activado (dando clic) por el usuario. En este caso para cambiar el tamaño y color de borde.
* Uso de la etiqueta `<footer>` para el pie de página.

## HTML5 y CSS3 parte 3: Trabajando con formularios y tablas

En este curso se vio como crear formularios, campos para dispositivos móviles, presentar información en tablas. Estilos para formularios, campos y tablas, así como el uso de transformaciones y transiciones.

### ¿Que se aprendió a lo largo de este curso?

* A crear un formulario.
* Uso de la etiqueta `<input>`, para la entrada de datos del usuario.
* A crear una etiqueta para el input con la etiqueta `<label>`.
* Que las etiquetas `<input>` y `<label>` poseen por defecto la propiedad `display inline`.
* Tipos de input, como text, email. number, submit.
* Uso de `textarea` para entradas de texto de más de una fila.
* Uso de `input` `radio`, `checkbox`.
* Uso del elemento `select` el cuál es un selector, un campo de selección de un ítem, y el elemento `option` que representa cada opción del selector.
* Uso de los `input` `email` y `tel`.
* Uso del atributo `required` para configurar los campos como obligatorios.
* Como mostrar una sugerencia usando el atributo `placeholder`.
* Uso del atributo `checked` para dejar una opción marcada en el `input` `radio` y `checkbox`.
* Como estructurar mejor el código usando los elementos `fieldset` y `legend`.
* Realizar transiciones en los elementos con la propiedad CSS `transition`.
* Modificar el estilo del puntero del mouse a través de la propiedad `cursor`.
* Realizar transformaciones en los elementos, como aumentar proporcionalmente la escala de determinado elemento o rotarlo a través de la propiedad `transform`.
* A crear una tabla HTML y colocar estilos.
  * La etiqueta `table`, representa la tabla.
  * La etiqueta `tr`, representa la fila de la tabla.
  * La etiqueta `td`, representa la celda de la tabla.
  * La etiqueta `thead`, representa el encabezado de la tabla.
  * La etiqueta `tbody`, representa el cuerpo de la tabla.
  * La etiqueta `th`, representa la celda del encabezado de la tabla.
  * La etiqueta `tfoot`, representa el pie de página de la tabla.

## HTML5 y CSS3 parte 4: Avanzando en CSS

En este curso se vio como importar contenido externo como fuentes, videos y mapas. También el uso de las pseudoclases, pseudoelementos, selectores de CSS avanzados, aprender a lidiar con la opacidad, sombra y comprender el viewport y el diseño responsivo.

### ¿Que se aprendió a lo largo de este curso?

* Medidas proporcionales con CSS.
* Como funciona la propiedad `float` y como se puede usar para que los elementos floten sobre al lado que se indica.
* Como limpiar la propiedad `float` con la propiedad `clear` del CSS.
* Utilizar fuentes externas.
* Como incorporar un mapa y un video.
* Pseudo-elementos.
* A mejorar la semántica ded la página principal con nuevas divisiones.
* Selectores avanzados CSS
  * Selector `>`: Permite acceder a los hijos de determinado elemento. Por ejemplo, para acceder a todos los `p` dentro de `main`:
    `main > p { } `
  * Selector `+`: Para acceder al primer hermano de determinado elemento. Por ejemplo, para acceder el primer `p` después del elemento `img`:
    `ìmg + p { }`
  * Selector `~`: Para acceder a todos los hermanos de determinado elemento. Por ejemplo, para acceder a todos los `p` después de un elemento `img`:
    `img ~ p { }`
  * Selector `not`: Para acceder a los elementos, excepto algunos. Por ejemplo, para acceder a todos los `p` dentro de `main` excepto el `p` que tiene el `id` `missao`:
    `main p:not(#missao) { }`
* Como agregar un sombreado alrededor de los elementos con la propiedad CSS `box-shadow`.
  * `box-shadow` admite 5 parámetros:
    El primero permite establecer la sombra en el eje x, si es positivo la sombra estará del lado derecho, si es negativo estará en el lado izquierdo.
    El segundo permite establecer la sombre en el eje y, si es positivo la sombra estará abajo del elemento, si es negativo estará arriba del elemento o derecha superior.
    El tercer parámetro permite difuminar la sombra, es decir, en que proporción va de solido a más transparente. Entre más grande el número más estara difuminada la sombra.
    El cuarto parámetro es la expansión, permite establecer hasta donde queremos que llegue la sombra.
    El quinto parámetro es el color.
    También se puede agregar más sombras, solo se tiene que poner una coma (,) para separarlas y también se puede establecer que la sombra sea interna, para esto desde un principio se coloca el valor inset.
* Como agregar un sombreado a los textos con la propiedad CSS `text-shadow`.
* Design responsivo: Cómo ajustar el estilo de la página según el tamaño de pantalla del dispositivo.
* Media Queries.
