# El Rol de HTML
Html(Lenguage de Marcas de Hipertexto) es un lenguaje para nuestra estructura de nuestro sitio web, que nos sirve para dar estructura, orden y representar información hacía los usuarios

## Anatomia de un elemento HTML
!(/img/html/anatomia.png)

1. La etiqueta de apertura: consiste en el nombre del elemento (en este caso, p), encerrado por paréntesis angulares (< >) de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento  en este caso, dónde es el comienzo del párrafo—.
2. La etiqueta de cierre: es igual que la etiqueta de apertura, excepto que incluye una barra de cierre (/) antes del nombre de la etiqueta. Establece dónde termina el elemento —en este caso dónde termina el párrafo—.
3. El contenido: este es el contenido del elemento, que en este caso es sólo texto.
4. El elemento: la etiqueta de apertura, más la etiqueta de cierre, más el contenido equivale al elemento

## Atributos 

Los atributos contienen información adicional acerca del elemento, la cual no quieres que aparezca en el contenido real del elemento. Aquí class es el nombre del atributo y editor-note el valor del atributo. En este caso, el atributo class permite darle al elemento un nombre identificativo, que se puede utilizar luego para apuntarle al elemento información de estilo y demás cosas.

Un atributo debe tener siempre:

1. Un espacio entre este y el nombre del elemento (o del atributo previo, si el elemento ya posee uno o más atributos).
2. El nombre del atributo, seguido por un signo de igual (=).
3. Comillas de apertura y de cierre, encerrando el valor del atributo.

Los atributos siempre se incluyen en la etiqueta de apertura de un elemento, nunca en la de cierre.

### Estructura de HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

Tienes:

* `<!DOCTYPE html>` — el tipo de documento. Es un preámbulo requerido. Anteriormente, cuando HTML era joven (cerca de 1991/2), los tipos de documento actuaban como vínculos a un conjunto de reglas que el código HTML de la página debía seguir para ser considerado bueno, lo que podía significar la verificación automática de errores y algunas otras cosas de utilidad. Sin embargo, hoy día es simplemente un artefacto antiguo que a nadie le importa, pero que debe ser incluido para que todo funcione correctamente. Por ahora, eso es todo lo que necesitas saber.
* `<html></html>` — el elemento `<html>`. Este elemento encierra todo el contenido de la página entera y, a veces, se le conoce como el elemento raíz (root element).
* ``<head></head> ``— el elemento ``<head>``. Este elemento actúa como un contenedor de todo aquello que quieres incluir en la página HTML que no es contenido visible por los visitantes de la página. Incluye cosas como palabras clave (keywords), una descripción de la página que quieres que aparezca en resultados de búsquedas, código CSS para dar estilo al contenido, declaraciones del juego de caracteres, etc.
* ``<meta charset="utf-8">`` — ``<meta>``. Este elemento establece el juego de caracteres que tu documento usará en utf-8, que incluye casi todos los caracteres de todos los idiomas humanos. Básicamente, puede manejar cualquier contenido de texto que puedas incluir. No hay razón para no establecerlo, y puede evitar problemas en el futuro.
* ``<title></title>`` — el elemento ``<title> ``establece el título de tu página, que es el título que aparece en la pestaña o en la barra de título del navegador cuando la página es cargada, y se usa para describir la página cuando es añadida a los marcadores o como favorita.
* ``<body></body>`` — el elemento ``<body>``. Encierra todo el contenido que deseas mostrar a los usuarios web que visiten tu página, ya sea texto, imágenes, videos, juegos, pistas de audio reproducibles, y demás.

### Sintaxis de HTML
````<!DOCTYPE>: Define el tipo de documento.
<html>: Contenedor raíz de un documento HTML.
<head>: Contiene meta-información sobre el documento.
<title>: Define el título del documento en la barra del navegador.
<meta>: Define metadatos sobre el documento.
<link>: Define la relación entre el documento actual y un recurso externo.
<style>: Define estilos CSS internos.
<script>: Define scripts de cliente.
<base>: Especifica la URL base para todas las URL relativas en el documento.
Sección del Cuerpo
<body>: Contiene el contenido del documento.
Encabezados
<h1> a <h6>: Define encabezados, siendo <h1> el de mayor importancia.
Texto y Formato
<p>: Define un párrafo.
<br>: Inserta un salto de línea.
<hr>: Inserta una línea horizontal.
<b>: Define texto en negrita.
<strong>: Define texto importante (negrita).
<i>: Define texto en cursiva.
<em>: Define texto enfatizado (cursiva).
<small>: Define texto pequeño.
<mark>: Define texto resaltado.
<del>: Define texto tachado.
<ins>: Define texto subrayado.
<sub>: Define texto como subíndice.
<sup>: Define texto como superíndice.
<blockquote>: Define una cita en bloque.
<q>: Define una cita en línea.
<code>: Define un fragmento de código.
<pre>: Define texto preformateado.
<address>: Define la información de contacto del autor/dueño del documento.
<cite>: Define el título de una obra.
Listas
<ul>: Define una lista desordenada.
<ol>: Define una lista ordenada.
<li>: Define un elemento de lista.
<dl>: Define una lista de definición.
<dt>: Define un término en una lista de definición.
<dd>: Define una descripción de un término en una lista de definición.
Enlaces
<a>: Define un hipervínculo.
Imágenes
<img>: Define una imagen.
Multimedia
<audio>: Define contenido de sonido.
<video>: Define contenido de video.
<source>: Define múltiples recursos para elementos multimedia.
<track>: Define subtítulos para contenido multimedia.
<embed>: Define un contenedor para una aplicación externa (plug-in).
<object>: Define un contenedor para un recurso externo.
<param>: Define parámetros para un objeto.
Integración de Contenido
<iframe>: Define un marco en línea.
Formularios
<form>: Define un formulario HTML.
<input>: Define un control de entrada.
<textarea>: Define un área de texto de entrada.
<button>: Define un botón clickeable.
<select>: Define un menú desplegable.
<option>: Define una opción en un menú desplegable.
<optgroup>: Define un grupo de opciones en un menú desplegable.
<label>: Define una etiqueta para un control de entrada.
<fieldset>: Agrupa elementos relacionados en un formulario.
<legend>: Define una leyenda para un elemento <fieldset>.
<datalist>: Define una lista de opciones predefinidas para controles de entrada.
<output>: Define el resultado de un cálculo.
Tablas
<table>: Define una tabla.
<caption>: Define un título para una tabla.
<th>: Define una celda de encabezado en una tabla.
<tr>: Define una fila en una tabla.
<td>: Define una celda en una tabla.
<thead>: Agrupa el contenido del encabezado en una tabla.
<tbody>: Agrupa el contenido del cuerpo en una tabla.
<tfoot>: Agrupa el contenido del pie en una tabla.
<col>: Especifica propiedades de columna para cada columna dentro de un <colgroup>.
<colgroup>: Especifica un grupo de una o más columnas en una tabla.
Estilo y Semántica
<style>: Define estilos CSS internos.
<div>: Define una sección en un documento (bloque).
<span>: Define una sección en línea (en línea).
Etiquetas de Programación
<script>: Define un script de cliente.
<noscript>: Define un contenido alternativo para usuarios que tienen deshabilitado el soporte de scripts.
Etiquetas de Metadatos
<meta>: Define metadatos sobre un documento HTML.
Contenedores de Agrupación
<section>: Define una sección en un documento.
<nav>: Define un conjunto de enlaces de navegación.
<article>: Define un contenido independiente y aislado.
<aside>: Define contenido lateral (como una barra lateral).
<header>: Define el encabezado de una sección o página.
<footer>: Define el pie de página de una sección o página.
<main>: Define el contenido principal del documento.
<figure>: Define contenido autónomo, como una imagen con su leyenda.
<figcaption>: Define una leyenda para el elemento <figure>.
Elementos de Enlace
<a>: Define un hipervínculo.
<link>: Define la relación entre el documento actual y un recurso externo.
Contenido Interactivo
<details>: Define detalles adicionales que el usuario puede ver o esconder.
<summary>: Define un encabezado visible para el elemento <details>.
<dialog>: Define un diálogo o una ventana.
Contenido Web Avanzado
<canvas>: Define un área de gráficos para dibujar gráficos a través de scripting (usualmente JavaScript).
<svg>: Define gráficos vectoriales escalables.
Otros
<template>: Define una plantilla reutilizable.
<slot>: Define un espacio donde se puede insertar contenido DOM en una plantilla.

````