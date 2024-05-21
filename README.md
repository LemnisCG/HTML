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

### Como se veria todo este codigo en un Documento HTML

<!DOCTYPE html>
```<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo Completo de HTML</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body { font-family: Arial, sans-serif; }
        header, footer { background-color: #f4f4f4; padding: 20px; text-align: center; }
        nav { margin: 20px; }
        nav a { margin: 0 10px; }
        section, article, aside { margin: 20px 0; }
        figure { text-align: center; }
        table { width: 100%; border-collapse: collapse; margin: 20px 0; }
        th, td { border: 1px solid #ddd; padding: 8px; text-align: left; }
        th { background-color: #f4f4f4; }
    </style>
</head>
<body>
    <header>
        <h1>Ejemplo Completo de HTML</h1>
    </header>

    <nav>
        <a href="#contenido-principal">Inicio</a>
        <a href="#articulo">Artículo</a>
        <a href="#formulario">Formulario</a>
    </nav>

    <main id="contenido-principal">
        <section>
            <h2>Sección Principal</h2>
            <p>Este es un párrafo de ejemplo. <strong>Texto en negrita</strong>, <em>texto en cursiva</em>, <mark>texto resaltado</mark>, <small>texto pequeño</small>, <del>texto tachado</del>, <ins>texto subrayado</ins>.</p>
            <blockquote>
                Este es un bloque de cita. <q>Esta es una cita en línea.</q>
            </blockquote>
            <pre>
                Código preformateado:
                <code>
function ejemplo() {
    console.log("Hola Mundo");
}
                </code>
            </pre>
            <address>
                Contacto: <a href="mailto:ejemplo@correo.com">ejemplo@correo.com</a>
            </address>
            <p>Referencias: <cite>Nombre del Libro</cite></p>
        </section>

        <section>
            <h2>Listas</h2>
            <ul>
                <li>Elemento de lista desordenada 1</li>
                <li>Elemento de lista desordenada 2</li>
                <li>Elemento de lista desordenada 3</li>
            </ul>
            <ol>
                <li>Elemento de lista ordenada 1</li>
                <li>Elemento de lista ordenada 2</li>
                <li>Elemento de lista ordenada 3</li>
            </ol>
            <dl>
                <dt>Término 1</dt>
                <dd>Descripción del término 1</dd>
                <dt>Término 2</dt>
                <dd>Descripción del término 2</dd>
            </dl>
        </section>

        <article id="articulo">
            <h2>Artículo</h2>
            <p>Este es un artículo de ejemplo.</p>
        </article>

        <aside>
            <h2>Barra Lateral</h2>
            <p>Contenido adicional como una barra lateral.</p>
        </aside>

        <figure>
            <img src="imagen.jpg" alt="Descripción de la imagen">
            <figcaption>Este es un pie de foto.</figcaption>
        </figure>

        <section>
            <h2>Tabla</h2>
            <table>
                <caption>Ejemplo de Tabla</caption>
                <thead>
                    <tr>
                        <th>Encabezado 1</th>
                        <th>Encabezado 2</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Dato 1</td>
                        <td>Dato 2</td>
                    </tr>
                    <tr>
                        <td>Dato 3</td>
                        <td>Dato 4</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td>Pie 1</td>
                        <td>Pie 2</td>
                    </tr>
                </tfoot>
            </table>
        </section>

        <section id="formulario">
            <h2>Formulario</h2>
            <form action="/ruta/del/formulario" method="post">
                <fieldset>
                    <legend>Información Personal</legend>
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" required>
                    
                    <label for="email">Correo electrónico:</label>
                    <input type="email" id="email" name="email" required>
                    
                    <label for="mensaje">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje"></textarea>
                    
                    <label for="opciones">Opciones:</label>
                    <select id="opciones" name="opciones">
                        <optgroup label="Grupo 1">
                            <option value="1">Opción 1</option>
                            <option value="2">Opción 2</option>
                        </optgroup>
                        <optgroup label="Grupo 2">
                            <option value="3">Opción 3</option>
                            <option value="4">Opción 4</option>
                        </optgroup>
                    </select>
                    
                    <label>
                        <input type="checkbox" name="suscribir" checked> Suscribirse al boletín
                    </label>
                    
                    <label>
                        <input type="radio" name="sexo" value="masculino"> Masculino
                    </label>
                    <label>
                        <input type="radio" name="sexo" value="femenino"> Femenino
                    </label>
                    
                    <input type="submit" value="Enviar">
                </fieldset>
            </form>
        </section>
        
        <section>
            <h2>Contenido Multimedia</h2>
            <audio controls>
                <source src="audio.mp3" type="audio/mp3">
                Tu navegador no soporta el elemento de audio.
            </audio>
            <video controls>
                <source src="video.mp4" type="video/mp4">
                Tu navegador no soporta el elemento de video.
            </video>
        </section>
        
        <section>
            <h2>Contenido Interactivo</h2>
            <details>
                <summary>Más información</summary>
                <p>Este es un detalle adicional que se puede ver u ocultar.</p>
            </details>
            <dialog open>
                <p>Este es un cuadro de diálogo.</p>
                <button onclick="this.parentElement.close()">Cerrar</button>
            </dialog>
        </section>

        <section>
            <h2>Contenido Gráfico</h2>
            <canvas id="miCanvas" width="200" height="200" style="border:1px solid #000000;"></canvas>
            <svg width="100" height="100">
                <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
            </svg>
        </section>

        <template id="miTemplate">
            <p>Este es un contenido de plantilla.</p>
        </template>

        <slot name="miSlot">Contenido por defecto</slot>
    </main>

    <footer>
        <p>Pie de página del documento</p>
    </footer>

    <script>
        function ejemplo() {
            console.log("Hola Mundo");
        }
    </script>
</body>
</html>```
