# Desarrollo Web

En este repositorio se encuentran los ejercicios y proyectos realizados en el curso de Desarrollo Web de Coderhouse.

## Recursos

HTML: <https://developer.mozilla.org/es/docs/Web/HTML>

HTML Reference: <https://htmlreference.io/>

Devdocs: <https://devdocs.io/html/>

colorhunt: <https://colorhunt.co/>

colormagick: <https://colormagic.app/>

colors: <https://coolors.co/>

### Herramientas

### Extensiones

Live Server: Permite visualizar los cambios en tiempo real en el navegador.
<https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer>

Open in Browser: Permite abrir el archivo HTML en el navegador.
<https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser>

Live Preview: Permite visualizar los cambios en tiempo real en el navegador.
<https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server>

Auto Rename Tag: Permite renombrar las etiquetas de apertura y cierre de manera automática.
<https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag>

Auto Close Tag: Permite cerrar las etiquetas de manera automática.
<https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag>

Prettier: Formatea el código de manera automática.
<https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode>

CSS Peek: Permite visualizar el código CSS de manera rápida.
<https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek>

indent-rainbow: Permite visualizar los espacios en blanco de manera más clara.
<https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow>

## Menú de Navegación

- [Clase 1 Prototipado y conceptos básicos de HTML](#clase-1-prototipado-y-conceptos-básicos-de-html)
- [Clase 2 Primeros paso con HTML](#clase-2-primeros-paso-con-html)
- [After Class 1](#after-class-1)
- [Clase 3 Incluyendo CSS en nuestro proyecto](#clase-3-incluyendo-css-en-nuestro-proyecto)
- [Clase 4 CSS + Box Model](#clase-4-css--box-model)
- [Primera Entrega](#primera-pre-entrega)
- [Clase 5 Flexbox](#clase-5-flexbox)
- [Clase 6 Grid](#clase-6-grid)
- [Clase 7 Media Queries](#clase-7-media-queries)
- [Clase 8 Pseudoclases y Pseudoelementos](#clase-8-pseudoclases-y-bem)

## Clase 1 Prototipado y conceptos básicos de HTML

### SKETCH

Es un dibujo rápido o bosquejo guía, que reproduce de manera muy sencilla un concepto, una idea o generalidad de un proyecto.

### WIREFRAME

Es la representación estática, en baja calidad, de un diseño. Se definen, para una mejor comprensión, los siguientes aspectos:

¿Qué? Los principales grupos de contenido.

¿Dónde? La estructura de la información.

¿Cómo? La descripción y visualización básica del usuario – interacción de la interfaz

### Mockup

Es la representación estática de un diseño, en calidad media o alta.

### Prototipo

Es la representación dinámica de un diseño, en calidad media o alta.

### HTML

Es un lenguaje de marcado que se utiliza para el desarrollo de páginas de internet. Se trata de la sigla que corresponde a HyperText Markup Language, es decir, Lenguaje de Marcas de Hipertexto.

Para nombrar los archivos HTML se utiliza la extensión .html, tiene que estar en minúsculas y sin espacios, evitar el uso de caracteres especiales y tildes.

Sintaixs básica de HTML:

```html
<etiqueta> Contenido </etiqueta>
```

Casi todas las etiquetas tienen una apertura y un cierre, con excepción de algunas como `<img>` o `<br>`

### Etiquetas cerradas

Las etiquetas cerradas son aquellas que tienen un contenido que se encuentra entre la apertura y el cierre de la etiqueta.

```html
<p>Soy un parrafo</p>
```

### Etiquetas auto-cerradas

Las etiquetas auto-cerradas son aquellas que no tienen contenido y se cierran en la misma etiqueta de apertura.

```html
<hr />
<!-- Línea horizontal -->
```

### Atributos de las etiquetas

Todos los elementos de HTML pueden tener atributos. Los atributos proporcionan información adicional sobre los elementos HTML.

```html
<etiqueta atributo="valor"> Contenido </etiqueta>
```

### Anidar etiquetas

Anidar etiquetas significa que una etiqueta se encuentra dentro de otra.

```html
<p>Esto es un <strong>párrafo</strong></p>
```

### Sintaxis básica de un documento HTML

Es importante mantener el orden dentro del codigo y tabular el contenido para una mejor comprensión.

```html
<!DOCTYPE html>
<html>
 <head>
  <title>Titulo de la página</title>
 </head>
 <body>
  <h1>Encabezado de nivel 1</h1>
  <p>Esto es un párrafo</p>
 </body>
</html>
```

### Estructura básica de un documento HTML

La estructura básica de un documento HTML se compone de la siguiente manera:

- DOCTYPE: Es la declaración que indica al navegador que el documento es de tipo HTML.

```html
<!DOCTYPE html>
```

- HTML: Es el elemento raíz de un documento HTML.

```html
<html>
 ...
</html>
```

- HEAD: Es el contenedor de los metadatos de un documento HTML.

```html
<head>
 ...
</head>
```

- TITLE: Es el título de un documento HTML.

```html
<title>Titulo de la página</title>
```

- BODY: Es el contenedor de todo el contenido visible de un documento HTML.

```html
<body>
 ...
</body>
```

### Tipos de elementos HTML (bloque e inline)

Bloque: Los elementos de bloque siempre comienzan en una nueva línea y ocupan todo el ancho disponible.

```html
<h1>Esto es un párrafo</h1>
```

Inline: Los elementos en línea no comienzan en una nueva línea y solo ocupan el ancho necesario.

```html
<a href="#">Esto es un enlace</a>
```

### Contenedores

Los contenedores son elementos que agrupan otros elementos.

```html
<div>
 <p>Esto es un párrafo</p>
</div>
```

```html
<p>Esto es un <span>texto</span></p>
```

### Etiqutas semánticas

Las etiquetas semánticas son aquellas que tienen un significado.

```html
<header>
 <nav>
  <ul>
   <li><a href="#">Inicio</a></li>
   <li><a href="#">Nosotros</a></li>
   <li><a href="#">Contacto</a></li>
  </ul>
 </nav>
</header>
<main>
 <article>
  <h1>Titulo del artículo</h1>
  <p>Contenido del artículo</p>
 </article>
 <aside>
  <h2>Publicidad</h2>
  <p>Contenido del aside</p>
 </aside>
</main>
<footer>
 <p>Derechos reservados</p>
</footer>
```

### Ejemplos de algunas etiquetas HTML mas utilizadas

```html
<!DOCTYPE html>
<html>
 <head>
  <title>Titulo de la página</title>
 </head>
 <body>
  <!-- Encabezados -->
  <h1>Encabezado de nivel 1</h1>
  <h2>Encabezado de nivel 2</h2>
  <h3>Encabezado de nivel 3</h3>
  <h4>Encabezado de nivel 4</h4>
  <h5>Encabezado de nivel 5</h5>
  <h6>Encabezado de nivel 6</h6>

  <p>Esto es un párrafo</p>
  <strong>Texto en negrita</strong>
  <em>Texto en cursiva</em>

  <!-- Etiquetas contenedores por ejemplo -->
  <div>Contenedor de Bloque</div>
  <span>Contenedor de Linea</span>

  <!-- Etiquetas Semanticas -->
  <header>Encabezado</header>
  <nav>Menu de Navegacion</nav>
  <main>Contenido Principal</main>
  <article>Articulo</article>
  <section>Seccion</section>
  <aside>Contenido Secundario</aside>
  <footer>Pie de Pagina</footer>

  <a href="#">Esto es un enlace</a>

  <img src="imagen.jpg" alt="Texto alternativo" />

  <ul>
   <li>Elemento de lista</li>
   <li>Elemento de lista</li>
   <li>Elemento de lista</li>
  </ul>
  <ol>
   <li>Elemento de lista ordenada</li>
   <li>Elemento de lista ordenada</li>
   <li>Elemento de lista ordenada</li>
  </ol>
  <table>
   <tr>
    <th>Encabezado de tabla</th>
    <th>Encabezado de tabla</th>
   </tr>
   <tr>
    <td>Dato de tabla</td>
    <td>Dato de tabla</td>
   </tr>
   <tr>
    <td>Dato de tabla</td>
    <td>Dato de tabla</td>
   </tr>
  </table>

  <!-- Etiquetas Abiertas -->
  <br />: para insertar un salto de línea.
  <hr />
  : para insertar una línea horizontal. <img />: para insertar una imagen.
  <input />: para crear un campo de entrada de datos, como un cuadro de texto
  o un botón. <meta />: para agregar información meta a la página, como
  descripción y palabras clave. <link />: para vincular la página a una hoja
  de estilo CSS o a otro recurso externo. <area />: para definir una región de
  un mapa de imagen. <base />: para establecer la URL base para todas las URL
  relativas dentro de una página.
  <col />
  : para definir las propiedades de estilo para una columna de una tabla.
  <embed />: para incrustar contenido multimedia, como audio o video.
  <param />
  : para establecer parámetros para un objeto multimedia en la página.
  <source />
  : para especificar la fuente de un elemento multimedia.
 </body>
</html>
```

## Clase 2 Primeros paso con HTML

Repaso:
![repaso-clase-02](https://github.com/humbertodrc/desarrollo-web-camada-53815/assets/63797901/e6163876-c158-4b23-adaf-c6ae500ff089)

### Enlaces

La etiqueta de enlace en HTML se utiliza para crear hipervínculos a otros recursos, como páginas web, imágenes, archivos de audio, videos, etc. La etiqueta <a> se utiliza junto con el atributo href, que especifica la URL del recurso al que se debe enlazar. Además del atributo href, la etiqueta <a> puede tener otros atributos opcionales, como target, title, rel, download, entre otros. Aquí tienes una descripción de algunos de los atributos más comunes:

1- href: Es el atributo obligatorio que especifica la dirección URL del recurso al que se enlazará. Puede ser una URL relativa o absoluta.

Ejemplo:

```html
<a href="https://www.google.com">Visitar Google</a>
```

2- target: Es un atributo opcional que especifica dónde abrir el recurso enlazado. Los valores posibles son \_blank,\_self, \_parent,\_top, o un nombre de ventana o marco.

Ejemplo:

```html
<a href="https://www.google.com" target="_blank">Visitar Google</a>
```

3- title: Es un atributo opcional que proporciona información adicional sobre el recurso al que se enlaza. Este texto se muestra como una información sobre herramientas cuando el usuario coloca el cursor sobre el enlace.

Ejemplo:

```html
<a href="https://www.google.com" title="Visitar Google">Visitar Google</a>
```

4- rel: Es un atributo opcional que especifica la relación entre el documento actual y el recurso enlazado. Los valores posibles son noreferrer, nofollow, noopener, y otros. Por ejemplo, nofollow indica que los motores de búsqueda no deben seguir el enlace:

Ejemplo:

```html
<a href="https://www.google.com" rel="nofollow">Visitar Google</a>
```

5- download: Es un atributo opcional que indica que el recurso enlazado debe descargarse en lugar de mostrarse en el navegador. El valor del atributo es el nombre de archivo sugerido para la descarga.

Ejemplo:

```html
<a href="documento.pdf" download>Descargar PDF</a>
```

#### Enlace Absoluto

Un enlace absoluto especifica la dirección completa del recurso al que se enlaza, incluyendo el protocolo (como "http://" o "https://"), el nombre de dominio y la ruta del recurso dentro del dominio.

```html
<a href="https://www.google.com">Visitar Google</a>
```

En este ejemplo, el enlace absoluto apunta a la página de inicio de Google.

#### Enlace Relativo

Un enlace relativo especifica la dirección del recurso en relación con la ubicación del documento HTML actual. Esto significa que el enlace se forma utilizando una ruta relativa al documento actual en lugar de especificar la URL completa.

```html
<a href="pagina.html">Enlace Relativo</a>
<a href="../otrapagina.html">Enlace Relativo</a>
```

En este caso, el enlace apunta a la página "otrapagina.html" que se encuentra en el directorio padre del documento HTML actual. El uso de .. indica que estamos retrocediendo un nivel en la jerarquía de directorios antes de buscar la página.

### Explicacion de las como moverse entre directorios

- ./: Este se refiere al directorio actual en el que te encuentras. Por ejemplo, si estás en el directorio /home/usuario/proyecto y quieres hacer referencia a un archivo en ese mismo directorio, puedes usar ./nombre_archivo.
- ../: Este se refiere al directorio padre del directorio actual. Por ejemplo, si estás en /home/usuario/proyecto y quieres hacer referencia a un archivo en el directorio padre (por ejemplo, en /home/usuario), puedes usar ../nombre_archivo.
  Estos caracteres son útiles cuando estás navegando por tu sistema de archivos en la línea de comandos o cuando estás escribiendo rutas en tu código para acceder a archivos o directorios relativos.

### Enlaces a secciones de la misma página o internos

Para crear un enlace a una sección específica de la misma página, puedes utilizar el atributo href con el valor del ID de la sección a la que quieres enlazar. Por ejemplo, si tienes una sección con el ID "seccion1" y quieres enlazar a ella, puedes hacer lo siguiente:

```html
<a href="#seccion1">Enlace a Sección 1</a>
```

En caso de que quieras moverte a una seccion especifica de otra pagina, puedes hacerlo de la siguiente manera:

```html
<a href="pagina.html#seccion1">Enlace a Sección 1</a>
```

### Multimedia en HTML

#### Imágenes

La etiqueta <img> se utiliza para insertar imágenes en un documento HTML. La etiqueta <img> es un elemento vacío, lo que significa que no tiene contenido y no tiene una etiqueta de cierre. En su lugar, la etiqueta <img> tiene un atributo src que especifica la URL de la imagen que se debe mostrar. Además del atributo src, la etiqueta <img> puede tener otros atributos opcionales, como alt, width, height, loading, y otros. Aquí tienes una descripción de algunos de los atributos más comunes:

1- src: Es el atributo obligatorio que especifica la URL de la imagen que se debe mostrar. Puede ser una URL relativa o absoluta.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" />
```

2- alt: Es un atributo opcional que proporciona un texto alternativo para la imagen. Este texto se muestra si la imagen no se puede cargar o si el usuario navega con un lector de pantalla.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" />
```

3- width: Es un atributo opcional que especifica el ancho de la imagen en píxeles.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" width="300" />
```

4- height: Es un atributo opcional que especifica la altura de la imagen en píxeles.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" height="200" />
```

5- loading: Es un atributo opcional que especifica cómo se debe cargar la imagen. Los valores posibles son auto, eager, lazy, y otros.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" loading="lazy" />
```

#### Favicon

El favicon es un icono que se muestra en la pestaña del navegador y en la lista de marcadores. Para agregar un favicon a tu sitio web, puedes utilizar la etiqueta <link> en el elemento <head> del documento HTML. El atributo rel especifica la relación entre el documento actual y el recurso enlazado, y el atributo href especifica la URL del icono. Aquí tienes un ejemplo de cómo agregar un favicon a tu sitio web:

```html
<!DOCTYPE html>
<html>
 <head>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <title>Titulo de la página</title>
 </head>
 <body>
  ...
 </body>
</html>
```

### Iframes

La etiqueta iframe se utiliza para insertar un marco en un documento HTML. Un marco es un área rectangular en la página que muestra otro documento HTML incrustado. La etiqueta iframe tiene un atributo src que especifica la URL del documento que se debe mostrar en el marco. Además del atributo src, la etiqueta iframe puede tener otros atributos opcionales, como width, height, title, loading, y otros. Aquí tienes una descripción de algunos de los atributos más comunes:

1- src: Es el atributo obligatorio que especifica la URL del documento que se debe mostrar en el marco. Puede ser una URL relativa o absoluta.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
></iframe>
```

2- width: Es un atributo opcional que especifica el ancho del marco en píxeles.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
></iframe>
```

3- height: Es un atributo opcional que especifica la altura del marco en píxeles.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
></iframe>
```

4- title: Es un atributo opcional que proporciona un título para el marco. Este texto se muestra como una información sobre herramientas cuando el usuario coloca el cursor sobre el marco.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
></iframe>
```

5- loading: Es un atributo opcional que especifica cómo se debe cargar el marco. Los valores posibles son auto, eager, lazy, y otros.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
 loading="lazy"
></iframe>
```

6- frameborder: Es un atributo opcional que especifica si el marco debe tener un borde. Los valores posibles son 0 y 1.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
 frameborder="0"
></iframe>
```

5- allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share": Este atributo controla qué acciones están permitidas dentro del iframe. En este caso, se permiten varias acciones relacionadas con el control de reproducción de video, la escritura en el portapapeles y el uso de sensores del dispositivo, entre otras.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
 allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
></iframe>
```

6- allowfullscreen: Es un atributo opcional que especifica si el marco debe permitir la visualización en pantalla completa.

Ejemplo:

```html
<iframe
 src="pagina.html"
 width="300"
 height="200"
 title="Título del marco"
 allowfullscreen
></iframe>
```

### Listas

Las listas son un tipo de estructura de datos que se utiliza para almacenar una colección de elementos. En HTML, puedes crear listas ordenadas, listas desordenadas y listas de definición utilizando las etiquetas ol, ul y dl, respectivamente. Aquí tienes una descripción de cada tipo de lista:

#### Listas Ordenadas

La etiqueta ol se utiliza para crear listas ordenadas, es decir, listas en las que los elementos se enumeran con números o letras. Cada elemento de la lista se crea con la etiqueta li. Aquí tienes un ejemplo de cómo crear una lista ordenada:

```html
<ol>
 <li>Elemento 1</li>
 <li>Elemento 2</li>
 <li>Elemento 3</li>
</ol>
```

#### Listas Desordenadas

La etiqueta ul se utiliza para crear listas desordenadas, es decir, listas en las que los elementos se enumeran con viñetas o puntos. Cada elemento de la lista se crea con la etiqueta li. Aquí tienes un ejemplo de cómo crear una lista desordenada:

```html
<ul>
 <li>Elemento 1</li>
 <li>Elemento 2</li>
 <li>Elemento 3</li>
</ul>
```

#### Listas de Definición

La etiqueta dl se utiliza para crear listas de definición, es decir, listas en las que cada elemento consta de un término seguido de una descripción. Cada término se crea con la etiqueta dt y cada descripción se crea con la etiqueta dd. Aquí tienes un ejemplo de cómo crear una lista de definición:

```html
<dl>
 <dt>Término 1</dt>
 <dd>Descripción 1</dd>
 <dt>Término 2</dt>
 <dd>Descripción 2</dd>
 <dt>Término 3</dt>
 <dd>Descripción 3</dd>
</dl>
```

### Formularios

Los formularios son una parte fundamental de la web moderna. Se utilizan para recopilar datos del usuario, como nombres, contraseñas, direcciones de correo electrónico, comentarios, etc. En HTML, puedes crear formularios utilizando la etiqueta form y varios tipos de controles de formulario, como input, textarea, select, button, y otros. Aquí tienes una descripción de algunos de los controles de formulario más comunes:

### Atributos de Formulario

La etiqueta form puede tener varios atributos opcionales que controlan el aspecto y el comportamiento del formulario. Aquí tienes una descripción de algunos de los atributos más comunes:

1- action: Es un atributo obligatorio que especifica la URL del script que procesará los datos del formulario.

Ejemplo:

```html
<form action="/procesar.php">...</form>
```

2- method: Es un atributo opcional que especifica el método HTTP que se utilizará para enviar los datos del formulario. Los valores posibles son get y post.

Ejemplo:

```html
<form action="/procesar.php" method="post">...</form>
```

3- target: Es un atributo opcional que especifica dónde se debe mostrar el resultado del procesamiento del formulario. Los valores posibles son \_blank,\_self, \_parent,\_top, o un nombre de ventana o marco.

Ejemplo:

````html
<form action="/procesar.php" method="post" target="_blank">...</form>

4- autocomplete: Es un atributo opcional que especifica si el navegador debe
completar automáticamente los campos del formulario. Ejemplo: ```html
<form action="/procesar.php" method="post" autocomplete="on">...</form>

5- novalidate: Es un atributo opcional que especifica que el formulario no debe
ser validado antes de enviar los datos. Ejemplo: ```html
<form action="/procesar.php" method="post" novalidate>...</form>
````

6- enctype: Es un atributo opcional que especifica cómo se deben codificar los datos del formulario antes de enviarlos al servidor. Los valores posibles son application/x-www-form-urlencoded, multipart/form-data, y text/plain.

Ejemplo:

```html
<form action="/procesar.php" method="post" enctype="multipart/form-data">
 ...
</form>
```

7- accept-charset: Es un atributo opcional que especifica el conjunto de caracteres que se utilizará para codificar los datos del formulario.

Ejemplo:

```html
<form action="/procesar.php" method="post" accept-charset="UTF-8">...</form>
```

El atributo enctype (encodificación de tipo de contenido) se utiliza en la etiqueta form para especificar cómo se debe codificar el contenido de los datos del formulario antes de enviarlo al servidor. Aquí están los valores que puede tomar el atributo enctype y sus significados:

application/x-www-form-urlencoded:

Este es el valor predeterminado si no se especifica ningún otro. En este tipo de codificación, los caracteres especiales se convierten en secuencias de escape %XX, donde XX representa el valor hexadecimal del carácter.
Es adecuado para enviar datos de formularios simples que no incluyen archivos binarios.
multipart/form-data:

Este tipo de codificación se utiliza para enviar datos de formularios que incluyen archivos binarios, como imágenes o archivos de audio.
Los datos se dividen en varias partes, cada una de las cuales contiene un campo del formulario y su valor, junto con los datos binarios del archivo.
Es necesario cuando se envían archivos, ya que no se pueden codificar correctamente usando application/x-www-form-urlencoded.
text/plain:

En este tipo de codificación, los datos del formulario se envían en texto plano sin ningún tipo de codificación especial.
Los caracteres especiales no se convierten en secuencias de escape %XX, lo que significa que se envían directamente como están.
Este tipo de codificación es menos común y generalmente se usa solo en casos especiales donde es necesario un formato de datos simple y legible.
Es importante elegir el valor adecuado para el atributo enctype según el tipo de datos que se estén enviando desde el formulario. Por lo general, para formularios estándar sin archivos adjuntos, se utiliza application/x-www-form-urlencoded, mientras que para formularios que incluyen archivos se utiliza multipart/form-data.

8- name: Es un atributo opcional que especifica el nombre del formulario. Este nombre se utiliza para identificar el formulario en el script que procesará los datos del formulario.

Ejemplo:

```html
<form action="/procesar.php" method="post" name="formulario">...</form>
```

#### Formulario Básico

La etiqueta form se utiliza para crear un formulario en un documento HTML. El atributo action especifica la URL del script que procesará los datos del formulario, y el atributo method especifica el método HTTP que se utilizará para enviar los datos del formulario. Aquí tienes un ejemplo de cómo crear un formulario básico:

```html
<form action="/procesar.php" method="post">
 <label for="nombre">Nombre:</label>
 <input type="text" id="nombre" name="nombre" />
 <label for="email">Correo Electrónico:</label>
 <input type="email" id="email" name="email" />
 <label for="comentario">Comentario:</label>
 <textarea id="comentario" name="comentario"></textarea>
 <button type="submit">Enviar</button>
</form>
```

#### Etiquetas de ingreso de datos en formularios

La etiqueta input se utiliza para crear controles de entrada en un formulario. El atributo type especifica el tipo de control de entrada que se debe crear, y el atributo name especifica el nombre del control de entrada. Aquí tienes una descripción de algunos de los tipos de control de entrada más comunes:

1- text: Crea un campo de texto de una sola línea.

Ejemplo:

```html
<input type="text" name="nombre" />
```

2- email: Crea un campo de texto para introducir una dirección de correo electrónico.

Ejemplo:

```html
<input type="email" name="email" />
```

3- password: Crea un campo de texto para introducir una contraseña.

Ejemplo:

```html
<input type="password" name="contrasena" />
```

4- checkbox: Crea una casilla de verificación que el usuario puede marcar o desmarcar.

Ejemplo:

```html
<input type="checkbox" name="suscribirse" value="1" />
```

5- radio: Crea un botón de opción que el usuario puede seleccionar.

Ejemplo:

```html
<input type="radio" name="genero" value="masculino" />
<input type="radio" name="genero" value="femenino" />
```

6- file: Crea un control de entrada para seleccionar un archivo para cargar.

Ejemplo:

```html
<input type="file" name="archivo" />
```

7- submit: Crea un botón para enviar el formulario.

Ejemplo:

```html
<input type="submit" value="Enviar" />
```

8- reset: Crea un botón para restablecer el formulario a su estado inicial.

Ejemplo:

```html
<input type="reset" value="Restablecer" />
```

9- hidden: Crea un campo de entrada oculto que no se muestra en el formulario.

Ejemplo:

```html
<input type="hidden" name="id" value="123" />
```

#### Atributos de entrada de datos

La etiqueta input puede tener varios atributos opcionales que controlan el aspecto y el comportamiento del control de entrada. Aquí tienes una descripción de algunos de los atributos más comunes:

1- placeholder: Es un atributo opcional que proporciona un texto de marcador de posición para el control de entrada. Este texto se muestra en el control de entrada cuando está vacío.

Ejemplo:

```html
<input type="text" name="nombre" placeholder="Nombre" />
```

2- required: Es un atributo opcional que especifica que el control de entrada es obligatorio. Si el usuario intenta enviar el formulario sin completar el control de entrada, se mostrará un mensaje de error.

Ejemplo:

```html
<input type="email" name="email" required />
```

3- disabled: Es un atributo opcional que especifica que el control de entrada está deshabilitado. Esto significa que el usuario no puede interactuar con el control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" disabled />
```

4- readonly: Es un atributo opcional que especifica que el control de entrada es de solo lectura. Esto significa que el usuario puede ver el valor del control de entrada, pero no puede cambiarlo.

Ejemplo:

```html
<input type="text" name="nombre" value="Humberto" readonly />
```

5- autofocus: Es un atributo opcional que especifica que el control de entrada debe recibir el enfoque automáticamente cuando se carga la página.

Ejemplo:

```html
<input type="text" name="nombre" autofocus />
```

6- autocomplete: Es un atributo opcional que especifica si el control de entrada debe permitir que el navegador complete automáticamente el valor del control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" autocomplete="on" />
```

7- pattern: Es un atributo opcional que especifica un patrón que debe coincidir con el valor del control de entrada. Si el valor del control de entrada no coincide con el patrón, se mostrará un mensaje de error.

Ejemplo:

```html
<input type="text" name="codigo" pattern="[A-Za-z]{3}\d{3}" />
```

8- min: Es un atributo opcional que especifica el valor mínimo que se puede introducir en el control de entrada.

Ejemplo:

```html
<input type="number" name="edad" min="18" />
```

9- max: Es un atributo opcional que especifica el valor máximo que se puede introducir en el control de entrada.

Ejemplo:

```html
<input type="number" name="edad" max="100" />
```

10- step: Es un atributo opcional que especifica el tamaño de los pasos que se pueden introducir en el control de entrada.

Ejemplo:

```html
<input type="number" name="edad" step="5" />
```

11- list: Es un atributo opcional que especifica el ID de un elemento datalist que proporciona una lista de opciones para el control de entrada.

Ejemplo:

````html
<input type="text" name="nombre" list="nombres" />
<datalist id="nombres">
 <option value="Humberto"></option>
 <option value="Juan"></option>
 <option value="María"></option>
</datalist>

12- multiple: Es un atributo opcional que especifica que el control de entrada
puede aceptar múltiples valores. Ejemplo: ```html
<input type="file" name="archivos" multiple />
````

13- accept: Es un atributo opcional que especifica los tipos de archivos que se pueden seleccionar en el control de entrada.

Ejemplo:

```html
<input type="file" name="archivos" accept="image/*" />
```

14- value: Es un atributo opcional que especifica el valor inicial del control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" value="Humberto" />
```

#### Etiqueta de Textarea

La etiqueta textarea se utiliza para crear un control de entrada de texto de varias líneas en un formulario. El contenido del control de entrada se especifica entre las etiquetas de apertura y cierre de textarea. Aquí tienes un ejemplo de cómo crear un control de entrada de texto de varias líneas:

```html
<textarea name="comentario"></textarea>
```

#### Etiqueta Label

La etiqueta label se utiliza para asociar un texto descriptivo con un control de entrada en un formulario. El atributo for especifica el ID del control de entrada al que se debe asociar el texto descriptivo. Aquí tienes un ejemplo de cómo asociar un texto descriptivo con un control de entrada:

```html
<label for="nombre">Nombre:</label>
<input type="text" id="nombre" name="nombre" />
```

#### Etiqueta Select

La etiqueta select se utiliza para crear un control de selección en un formulario. La etiqueta select contiene una o más etiquetas option, que representan las opciones que el usuario puede seleccionar. Aquí tienes un ejemplo de cómo crear un control de selección:

```html
<select name="pais">
 <option value="ar">Argentina</option>
 <option value="br">Brasil</option>
 <option value="cl">Chile</option>
 <option value="co">Colombia</option>
 <option value="mx">México</option>
 <option value="pe">Perú</option>
</select>
```

#### Conjunto de Campos

Las etiquetas fieldset y legend se utilizan para agrupar un conjunto de campos relacionados en un formulario. La etiqueta fieldset contiene uno o más campos de formulario, y la etiqueta legend proporciona un título descriptivo para el conjunto de campos. Aquí tienes un ejemplo de cómo agrupar un conjunto de campos:

```html
<fieldset>
 <legend>Datos Personales</legend>
 <label for="nombre">Nombre:</label>
 <input type="text" id="nombre" name="nombre" />
 <label for="email">Correo Electrónico:</label>
 <input type="email" id="email" name="email" />
 <label for="telefono">Teléfono:</label>
 <input type="tel" id="telefono" name="telefono" />
</fieldset>
```

### Tablas

Las tablas se utilizan para mostrar datos en filas y columnas. En HTML, puedes crear tablas utilizando las etiquetas table, tr, th y td. Aquí tienes una descripción de cada una de estas etiquetas:

#### Tabla Básica

La etiqueta table se utiliza para crear una tabla en un documento HTML. La etiqueta tr se utiliza para crear una fila en la tabla, y la etiqueta th se utiliza para crear una celda de encabezado. La etiqueta td se utiliza para crear una celda de datos. Aquí tienes un ejemplo de cómo crear una tabla básica:

```html
<table>
 <tr>
  <th>Encabezado 1</th>
  <th>Encabezado 2</th>
  <th>Encabezado 3</th>
 </tr>
 <tr>
  <td>Dato 1</td>
  <td>Dato 2</td>
  <td>Dato 3</td>
 </tr>
 <tr>
  <td>Dato 4</td>
  <td>Dato 5</td>
  <td>Dato 6</td>
 </tr>
</table>
```

#### Atributos de Tabla

La etiqueta table puede tener varios atributos opcionales que controlan el aspecto y el comportamiento de la tabla. Aquí tienes una descripción de algunos de los atributos más comunes:

1- border: Es un atributo opcional que especifica el ancho del borde de la tabla. El valor del atributo es un número entero que representa el ancho del borde en píxeles.

Ejemplo:

````html
<table border="1">
 ...
</table>

2- cellpadding: Es un atributo opcional que especifica el espacio entre el borde
de la celda y su contenido. El valor del atributo es un número entero que
representa el espacio en píxeles. Ejemplo: ```html
<table cellpadding="10">
 ...
</table>
````

3- cellspacing: Es un atributo opcional que especifica el espacio entre las celdas de la tabla. El valor del atributo es un número entero que representa el espacio en píxeles.

Ejemplo:

````html
<table cellspacing="5">
 ...
</table>

4- width: Es un atributo opcional que especifica el ancho de la tabla. El valor
del atributo es un número entero que representa el ancho en píxeles. Ejemplo:
```html
<table width="300">
 ...
</table>
````

5- align: Es un atributo opcional que especifica la alineación horizontal de la tabla. Los valores posibles son left, center, y right.

Ejemplo:

````html
<table align="center">
 ...
</table>

6- bgcolor: Es un atributo opcional que especifica el color de fondo de la
tabla. El valor del atributo es un nombre de color o un código hexadecimal.
Ejemplo: ```html
<table bgcolor="#f0f0f0">
 ...
</table>
````

## After Class 1

Resumen de lo que vimos en el after class 1:

- Nombrar los archivos
- Arquitectura de carpetas
- index.html
- Etiqutas HTML
- Etiquetas abiertas y cerradas
- Atributos de las etiquetas
- Anidamiento de etiquetas
- Sintaixs de las etiquetas
- Estructura de un documento HTML
- Elementos de bloque y de línea
- Etiquetas de titulo
- Contenedores de bloque y de línea
- HTML semántico
- Enlaces
- Enlaces absolutos y relativos
- Imágenes
- Listas
- Tipos de listas

### Algunas preguntad del after class 1

¿Que seria el UTF-8? Para que se usa?

El UTF-8 es un formato de codificación de caracteres que se utiliza para representar texto en la web. UTF-8 es un estándar de codificación de caracteres que permite representar la mayoría de los caracteres del mundo en una sola codificación. UTF-8 es el estándar de codificación de caracteres más utilizado en la web y es compatible con la mayoría de los navegadores y sistemas operativos.

UTF-8 es crucial para la correcta representación de texto en la mayoría de las aplicaciones informáticas y en la web.Qué sucede si no se utiliza:

Representación de caracteres: UTF-8 asigna un número único a cada carácter utilizado en una amplia variedad de idiomas y escrituras. Esto permite que los sistemas informáticos interpreten y muestren correctamente los caracteres, independientemente del idioma en el que estén escritos.

Compatibilidad multilingüe: UTF-8 es capaz de representar caracteres de múltiples idiomas y escrituras en un solo estándar. Esto es esencial para la comunicación global en la era digital, ya que permite que las aplicaciones y sistemas informáticos funcionen correctamente para usuarios que hablan diferentes idiomas y escriben en diferentes sistemas de escritura.

Prevención de errores de visualización: Si no se utiliza UTF-8 y en su lugar se emplea otro estándar de codificación de caracteres más limitado, es probable que ocurran errores de visualización al mostrar texto en idiomas que no son compatibles con ese estándar. Esto puede provocar que los caracteres se muestren incorrectamente, lo que dificulta o imposibilita la comprensión del texto.

Interoperabilidad: UTF-8 es ampliamente adoptado y compatible con la mayoría de los sistemas operativos, navegadores web, bases de datos y aplicaciones. Utilizar UTF-8 garantiza una mejor interoperabilidad entre diferentes sistemas y plataformas, lo que facilita el intercambio de datos y la comunicación entre usuarios de todo el mundo.

En resumen, si no se utiliza UTF-8, es probable que se produzcan errores de visualización y problemas de compatibilidad al mostrar texto en diferentes idiomas y escrituras. Esto puede dificultar la comunicación efectiva y limitar la funcionalidad de las aplicaciones y sistemas informáticos en un entorno globalizado. Por lo tanto, es altamente recomendable utilizar UTF-8 para garantizar la correcta representación y visualización del texto en todas las circunstancias.

Es obligatorio el uso de UTF-8 en HTML?

El uso de UTF-8 no es obligatorio en HTML, pero es altamente recomendable. UTF-8 es el estándar de codificación de caracteres más ampliamente utilizado y compatible en la web, y su uso garantiza la correcta representación y visualización del texto en una amplia variedad de idiomas y escrituras. Además, UTF-8 es compatible con la mayoría de los navegadores web, sistemas operativos y aplicaciones, lo que facilita la interoperabilidad y el intercambio de datos en un entorno globalizado.

Debo usar siempre el atributo alt en las etiquetas de imagen?

El atributo alt es un atributo opcional en las etiquetas de imagen en HTML, pero su uso es altamente recomendable. El atributo alt proporciona un texto alternativo que se muestra si la imagen no se puede cargar o si el usuario navega con un lector de pantalla. El texto alternativo es importante para la accesibilidad web, ya que permite que los usuarios con discapacidades visuales o que utilizan tecnologías de asistencia comprendan el contenido de la imagen.

Debo agregar el atributo target="\_blank" a todos los enlaces externos o internos?

El atributo target="\_blank" se utiliza para abrir un enlace en una nueva ventana o pestaña del navegador. Si bien su uso puede ser útil en algunos casos, no es necesario agregar el atributo target="\_blank" a todos los enlaces externos. Abrir enlaces en una nueva ventana o pestaña puede ser una preferencia del usuario, por lo que es recomendable permitir que el usuario decida cómo desea abrir el enlace. Además, el uso excesivo del atributo target="\_blank" puede resultar molesto para los usuarios y dificultar la navegación en el sitio web.

Como puedo organizar la estructura de archivos y carpetas en un proyecto web hecho con HTML y CSS?

La organización de la estructura de archivos y carpetas en un proyecto web hecho con HTML y CSS puede variar según las necesidades y preferencias del desarrollador. Sin embargo, una estructura de carpetas comúnmente utilizada para proyectos web incluye las siguientes carpetas y archivos:

- Archivo "index.html": Es el archivo principal que representa la página de inicio del sitio web.
- Carpeta "css": Contiene los archivos CSS utilizados para estilizar el sitio web.
- Carpeta "js": Contiene los archivos JavaScript utilizados para agregar interactividad y funcionalidad al sitio web.
- Carpeta "img": Contiene las imágenes utilizadas en el sitio web.
- Carpeta "fonts": Contiene las fuentes utilizadas en el sitio web.
- Carpeta "assets": Contiene otros recursos multimedia, como videos, audios, iconos, etc.
- Carpeta "pages": Contiene archivos HTML adicionales para otras páginas del sitio web, como "about.html", "contact.html", etc.

Esta estructura de carpetas y archivos proporciona una organización clara y coherente para los recursos utilizados en el proyecto web, lo que facilita la gestión y el mantenimiento del sitio web.

En que caso se puede utilizar la etiqueta span?

La etiqueta span se utiliza para aplicar estilos o comportamientos específicos a un fragmento de texto en un documento HTML. La etiqueta span es un elemento de línea que no tiene un significado semántico específico, pero se utiliza para envolver y aplicar estilos a partes específicas del texto. Algunos casos comunes en los que se puede utilizar la etiqueta span incluyen:

En que caso se puede utilizar la etiqueta div?

La etiqueta div se utiliza para crear contenedores de bloque en un documento HTML. La etiqueta div es un elemento de bloque que no tiene un significado semántico específico, pero se utiliza para agrupar y estructurar otros elementos HTML, como texto, imágenes, formularios, etc. Algunos casos comunes en los que se puede utilizar la etiqueta div incluyen:

- Agrupar y estructurar elementos relacionados en una sección de la página.
- Aplicar estilos o comportamientos específicos a un grupo de elementos.
- Crear diseños de página utilizando CSS y flexbox o grid.

Cual es la diferencia entre un elemento de bloque y un elemento de línea en HTML?

En HTML, los elementos de bloque y de línea son dos tipos de elementos que se utilizan para estructurar y presentar el contenido en una página web. La diferencia principal entre los elementos de bloque y de línea radica en su comportamiento y presentación visual en el diseño de la página. Aquí tienes una descripción de las diferencias entre los elementos de bloque y de línea:

Elementos de bloque:

- Los elementos de bloque ocupan todo el ancho disponible en su contenedor y comienzan en una nueva línea.
- Los elementos de bloque pueden contener otros elementos de bloque o de línea, así como otros elementos de bloque.

Elementos de línea:

- Los elementos de línea ocupan solo el ancho necesario para mostrar su contenido y no comienzan en una nueva línea.
- Los elementos de línea no pueden contener otros elementos de bloque, pero pueden contener otros elementos de línea.

Una herramienta que me permite saber si puedo colocar una etiqueta dentro de otra es:

[text](https://caninclude.glitch.me/)

Cual es el significado de las etiquetas semanticas en HTML?

Las etiquetas semánticas en HTML son elementos que proporcionan un significado y estructura semántica al contenido de una página web. Las etiquetas semánticas ayudan a los motores de búsqueda, navegadores web y tecnologías de asistencia a comprender y presentar el contenido de manera más clara y significativa. Algunos ejemplos de etiquetas semánticas en HTML incluyen:

- header: Representa la cabecera de una sección o de la página.
- nav: Representa una sección de navegación.
- main: Representa el contenido principal de la página.
- section: Representa una sección genérica de contenido.
- article: Representa un artículo independiente, como un blog post o una noticia.
- aside: Representa contenido relacionado o secundario.
- footer: Representa el pie de página de una sección o de la página.

¿Como puedo crear carpetas en VSC y hacer anidamiento de carpetas?

Para crear carpetas en Visual Studio Code (VSC) y hacer anidamiento de carpetas, puedes seguir estos pasos:

1. Abre Visual Studio Code.
2. Abre el explorador de archivos haciendo clic en el icono de la carpeta en la barra lateral izquierda o derecha.
3. Haz clic con el botón derecho del ratón en el área del explorador de archivos y selecciona "New Folder" en el menú contextual o selecciona el icono 📁 "New Folder" .
4. Escribe el nombre de la nueva carpeta y presiona Enter para crearla.
5. Para hacer anidamiento de carpetas, haz clic con el botón derecho del ratón en la carpeta que deseas anidar y selecciona "New Folder" en el menú contextual o selecciona el icono 📁 "New Folder" .
6. Escribe el nombre de la nueva carpeta anidada y presiona Enter para crearla.

¿Puedo modificar el tamaño de una imagen sin usar CSS?

Sí, puedes modificar el tamaño de una imagen en HTML sin usar CSS utilizando los atributos width y height en la etiqueta img. Los atributos width y height permiten especificar el ancho y la altura de la imagen en píxeles, respectivamente. Aquí tienes un ejemplo de cómo modificar el tamaño de una imagen en HTML sin usar CSS:

```html
<img src="imagen.jpg" alt="Texto alternativo" width="300" height="200" />
```

Debo seguir un orden especifico al agregar atributos a las etiquetas HTML?

No hay un orden específico obligatorio para agregar atributos a las etiquetas HTML, pero es recomendable seguir un orden coherente y consistente para mantener la legibilidad y la organización del código. Algunas prácticas comunes para agregar atributos a las etiquetas HTML incluyen:

- Agrupar atributos relacionados juntos.
- Ordenar los atributos alfabéticamente o por relevancia.
- Mantener un formato consistente en todo el código.

En general, el orden de los atributos en las etiquetas HTML no afecta el funcionamiento del código, pero seguir un orden coherente puede facilitar la lectura y el mantenimiento del código.

¿Como puedo validar si tengo errores al momento de escribir HTML?

Puedes validar si tienes errores al momento de escribir HTML utilizando herramientas de validación de HTML en línea o extensiones de Visual Studio Code. Algunas opciones para validar HTML incluyen:

- Validadores en línea: Hay varios validadores de HTML en línea gratuitos disponibles que te permiten pegar o cargar tu código HTML y verificar si hay errores de sintaxis o problemas de estructura. Algunos ejemplos de validadores en línea incluyen el W3C Markup Validation Service y el HTML Validator de W3Schools.

- Otra opción es utilizar extensiones de Visual Studio Code como la extensión "Prettier - Code formatter".

- Podemos hacer una validación a mano cerrando nuestros bloques de código, con la ayuda que nos ofrece VSC.

¿Puedo colocar dentro de un elemento de linea un elemento de bloque?

No, no puedes colocar un elemento de bloque dentro de un elemento de línea en HTML. Los elementos de bloque ocupan todo el ancho disponible en su contenedor y comienzan en una nueva línea, mientras que los elementos de línea ocupan solo el ancho necesario para mostrar su contenido y no comienzan en una nueva línea. Por lo tanto, los elementos de bloque y de línea tienen comportamientos y restricciones diferentes en la estructura del documento HTML.

¿Que contenido puedo colocar dentro de un elemento de bloque?

Dentro de un elemento de bloque en HTML, puedes colocar una amplia variedad de contenido, incluyendo:

- Otros elementos de bloque.
- Elementos de línea.
- Texto.
- Imágenes.
- Formularios.
- Tablas.
- Listas.
- Contenido multimedia, como videos y audios.
- Contenido estructural, como encabezados, secciones, artículos, etc.

¿Que elementos van dentro del body de un documento HTML?

Dentro del elemento body de un documento HTML, puedes colocar una amplia variedad de elementos y contenido, incluyendo:

- Encabezados y títulos.
- Secciones y artículos.
- Listas.
- Tablas.
- Formularios.
- Imágenes.
- Contenido multimedia, como videos y audios.
- Enlaces.
- Texto y párrafos.
- Contenido estructural, como encabezados, secciones, artículos, etc.

¿Que elementos van dentro del head de un documento HTML?

Dentro del elemento head de un documento HTML, puedes colocar una variedad de elementos y contenido relacionado con la configuración y metadatos del documento, incluyendo:

- El elemento title, que especifica el título del documento.
- Elementos meta, que proporcionan metadatos sobre el documento, como la codificación de caracteres, la descripción, las palabras clave, etc.
- Elementos link, que vinculan el documento con hojas de estilo externas, fuentes, iconos, etc.
- Elementos script, que vinculan el documento con scripts externos, como JavaScript.
- Elementos style, que contienen estilos CSS en línea para el documento.

¿En caso puedo utilizar una etiqueta article, se puede utilizar para crear una card?

Sí, puedes utilizar la etiqueta article para crear una tarjeta (card) en HTML. La etiqueta article se utiliza para representar un artículo independiente, como un blog post, una noticia, una publicación en redes sociales, etc. Las tarjetas son un componente común en el diseño de interfaces de usuario y se utilizan para mostrar contenido de manera visualmente atractiva y estructurada. Aquí tienes un ejemplo de cómo utilizar la etiqueta article para crear una tarjeta en HTML:

```html
<article class="card">
 <img src="imagen.jpg" alt="Texto alternativo" />
 <h2>Título del artículo</h2>
 <p>Contenido del artículo</p>
 <a href="#">Leer más</a>
</article>
```

¿Como puedo crear un footer siguiento las buenas practicas de HTML?

Para crear un footer siguiendo las buenas prácticas de HTML, puedes utilizar la etiqueta footer para representar el pie de página de una sección o de la página. Dentro de la etiqueta footer, puedes colocar contenido relacionado con la navegación, información de contacto, enlaces a redes sociales, créditos, etc. Aquí tienes un ejemplo de cómo crear un footer siguiendo las buenas prácticas de HTML:

```html
<footer>
 <nav>
  <ul>
   <li><a href="#">Inicio</a></li>
   <li><a href="#">Acerca de</a></li>
   <li><a href="#">Contacto</a></li>
  </ul>
 </nav>
 <p>&copy; 2022 Mi Sitio Web</p>
</footer>
```

¿Como puedo crear un header siguiendo las buenas practicas de HTML?

Para crear un header siguiendo las buenas prácticas de HTML, puedes utilizar la etiqueta header para representar la cabecera de una sección o de la página. Dentro de la etiqueta header, puedes colocar contenido relacionado con la navegación, el logotipo, el título, la descripción, etc. Aquí tienes un ejemplo de cómo crear un header siguiendo las buenas prácticas de HTML:

```html
<header>
 <h1>Nombre del Sitio Web</h1>
 <p>Descripción del Sitio Web</p>
 <nav>
  <ul>
   <li><a href="#">Inicio</a></li>
   <li><a href="#">Acerca de</a></li>
   <li><a href="#">Contacto</a></li>
  </ul>
 </nav>
</header>
```

¿Que son los comentarios en HTML y como puedo agregarlos?

Los comentarios en HTML son fragmentos de texto que se utilizan para documentar y explicar el código HTML. Los comentarios no se muestran en la página web, pero son útiles para proporcionar información adicional sobre el código, como notas, explicaciones, recordatorios, etc. Los comentarios en HTML se crean utilizando la sintaxis <!-- comentario -->. Aquí tienes un ejemplo de cómo agregar comentarios en HTML:

```html
<!-- Este es un comentario en HTML -->
<p>Este es un párrafo de texto.</p>
```

¿Puedo agregar una etiqueta "a" a una imagen?

Sí, puedes agregar una etiqueta "a" (enlace) a una imagen en HTML. Al envolver una imagen con una etiqueta "a", puedes hacer que la imagen sea clicle y enlace a otra página web, un archivo, una sección de la página, etc. Aquí tienes un ejemplo de cómo agregar una etiqueta "a" a una imagen en HTML:

```html
<a href="pagina.html">
 <img src="imagen.jpg" alt="Texto alternativo" />
</a>
```

¿Cual es la diferencia entre un enlace absoluto y un enlace relativo?

La diferencia entre un enlace absoluto y un enlace relativo radica en la forma en que se especifica la URL del recurso al que se enlaza. Aquí tienes una descripción de las diferencias entre los enlaces absolutos y relativos:

Enlace absoluto:

- Un enlace absoluto especifica la URL completa del recurso, incluyendo el protocolo (http:// o https://), el nombre de dominio (<www.ejemplo.com>), la ruta del recurso (/ruta/archivo.html), y cualquier parámetro adicional.

- Los enlaces absolutos comienzan con el protocolo y el nombre de dominio, lo que significa que apuntan directamente a una ubicación específica en la web.

- Los enlaces absolutos son útiles cuando se enlaza a recursos externos o a ubicaciones específicas en un sitio web.

Enlace relativo:

- Un enlace relativo especifica la ruta del recurso en relación con la ubicación actual del documento HTML.

- Los enlaces relativos no incluyen el protocolo ni el nombre de dominio, sino que se basan en la ubicación del documento HTML para determinar la ruta del recurso.

- Los enlaces relativos son útiles cuando se enlaza a recursos dentro del mismo sitio web o en la misma carpeta que el documento HTML.

En resumen, la diferencia principal entre un enlace absoluto y un enlace relativo radica en la forma en que se especifica la URL del recurso. Los enlaces absolutos apuntan directamente a una ubicación específica en la web, mientras que los enlaces relativos se basan en la ubicación del documento HTML para determinar la ruta del recurso.

## Clase 3 Incluyendo CSS en nuestro proyecto

### Introducción a CSS

CSS (Cascading Style Sheets) es un lenguaje de hojas de estilo utilizado para describir la presentación visual de un documento HTML. CSS se utiliza para aplicar estilos, como colores, fuentes, márgenes, tamaños, etc., a los elementos HTML y para controlar el diseño y la apariencia de una página web. Aquí tienes una descripción de algunos conceptos y características clave de CSS:

- Selectores: Los selectores se utilizan para apuntar a elementos HTML específicos y aplicar estilos a esos elementos. Los selectores pueden ser etiquetas HTML, clases, IDs, atributos, etc.

- Propiedades: Las propiedades se utilizan para especificar los estilos que se aplicarán a los elementos seleccionados. Las propiedades pueden controlar el color, la fuente, el tamaño, el margen, el relleno, la alineación, etc.

- Valores: Los valores se utilizan para definir los estilos específicos que se aplicarán a las propiedades. Los valores pueden ser colores, tamaños, fuentes, márgenes, etc.

- Reglas: Las reglas de estilo se componen de un selector, una o más propiedades y sus valores correspondientes. Las reglas de estilo se utilizan para aplicar estilos a los elementos HTML seleccionados.

- Clases: Las clases se utilizan para aplicar estilos a uno o más elementos HTML. Las clases se definen en el documento CSS y se aplican a los elementos HTML utilizando el atributo class.

- IDs: Los IDs se utilizan para aplicar estilos a un elemento HTML específico. Los IDs se definen en el documento CSS y se aplican a los elementos HTML utilizando el atributo id.

- Herencia: La herencia en CSS permite que los estilos se apliquen a los elementos secundarios basados en los estilos de sus elementos padres.

- Cascada: La cascada en CSS se refiere a la forma en que se aplican y priorizan los estilos cuando hay conflictos entre reglas de estilo.

### Sintaxis de CSS

La sintaxis de CSS se compone de reglas de estilo que se utilizan para aplicar estilos a los elementos HTML. Cada regla de estilo se compone de un selector, una o más propiedades y sus valores correspondientes. Aquí tienes una descripción de la sintaxis de CSS:

```css
selector {
 propiedad: valor;
 propiedad: valor;
 ...;
}
```

- Selector: El selector apunta a los elementos HTML a los que se aplicarán los estilos. Los selectores pueden ser etiquetas HTML, clases, IDs, atributos, etc.

- Propiedad: La propiedad especifica el estilo que se aplicará a los elementos seleccionados. Las propiedades pueden controlar el color, la fuente, el tamaño, el margen, el relleno, la alineación, etc.

- Valor: El valor define el estilo específico que se aplicará a la propiedad. Los valores pueden ser colores, tamaños, fuentes, márgenes, etc.

Regla semantica de CSS

- Cada declaración de estilo debe terminar con un punto y coma (;) y esta formada por una propiedad y un valor.
- No se ve afectado por los espacios en blanco.
- Cuando la propiedad represente un numero el valor debe ir acompañado de una unidad de medida.

### Padres e hijos en CSS

En CSS, los elementos HTML pueden tener una relación de padre e hijo, lo que significa que un elemento puede ser el padre de otro elemento. La relación de padre e hijo se utiliza para aplicar estilos a los elementos secundarios basados en los estilos de sus elementos padres. Aquí tienes una descripción de cómo se utiliza la relación de padre e hijo en CSS:

```css
/* Estilo aplicado a todos los párrafos dentro de un div */
div p {
 color: red;
}
```

Otro ejemplo con mas de un nivel de anidamiento:

```css
/* Estilo aplicado a todos los párrafos dentro de un div dentro de un main */
main div p {
 color: red;
}
```

### Agrergando CSS a un documento HTML

Hay varias formas de agregar CSS a un documento HTML, incluyendo:

- CSS en línea: Puedes agregar estilos CSS directamente en la etiqueta style dentro del documento HTML.

- CSS interno: Puedes agregar estilos CSS dentro de la etiqueta style en la sección head del documento HTML.

- CSS externo: Puedes vincular un archivo CSS externo al documento HTML utilizando la etiqueta link en la sección head del documento HTML.

### CSS externo

Para agregar estilos CSS externos a un documento HTML, puedes crear un archivo CSS separado y vincularlo al documento HTML utilizando la etiqueta link en la sección head. Aquí tienes un ejemplo de cómo vincular un archivo CSS externo a un documento HTML:

```html
<!DOCTYPE html>
<html>
 <head>
  <link rel="stylesheet" href="estilos.css" />
 </head>
 <body>
  ...
 </body>
</html>
```

### CSS interno

Para agregar estilos CSS internos a un documento HTML, puedes utilizar la etiqueta style en la sección head del documento HTML. Aquí tienes un ejemplo de cómo agregar estilos CSS internos a un documento HTML:

```html
<!DOCTYPE html>
<html>
 <head>
  <style>
   /* Estilos CSS internos */
   body {
    font-family: Arial, sans-serif;
   }
  </style>
 </head>
 <body>
  ...
 </body>
</html>
```

### CSS en línea

Para agregar estilos CSS en línea a un elemento HTML, puedes utilizar el atributo style directamente en la etiqueta del elemento. Aquí tienes un ejemplo de cómo agregar estilos CSS en línea a un elemento HTML:

```html
<!DOCTYPE html>
<html>
 <head>
  ...
 </head>
 <body>
  <p style="color: red;">Este es un párrafo de texto con estilo en línea.</p>
 </body>
</html>
```

### Selectores de CSS

Los selectores de CSS se utilizan para apuntar a elementos HTML específicos y aplicar estilos a esos elementos. Los selectores pueden ser etiquetas HTML, clases, IDs, atributos, etc. Aquí tienes una descripción de algunos tipos comunes de selectores de CSS:

- Selectores de etiqueta: Los selectores de etiqueta apuntan a elementos HTML específicos, como p, h1, div, etc.

Ejemplo del HTML y CSS:

```html
<!DOCTYPE html>
<html>
 <head> </head>
 <body>
  <p>Este es un párrafo de texto.</p>
  <h1>Este es un encabezado de nivel 1.</h1>
  <div>Este es un div.</div>
 </body>
</html>
```

```css
/* Estilo aplicado a todos los párrafos */
p {
 color: red;
}
```

- Selectores de clase: Los selectores de clase apuntan a elementos HTML que tienen una clase específica. Los selectores de clase se definen con un punto (.) seguido del nombre de la clase.

Ejemplo del HTML y CSS:

```html
<!DOCTYPE html>
<html>
 <head> </head>
 <body>
  <p class="destacado">Este es un párrafo de texto destacado.</p>
  <p>Este es otro párrafo de texto.</p>
 </body>
</html>
```

```css
/* Estilo aplicado a todos los elementos con la clase "destacado" */
.destacado {
 color: red;
}
```

- Selectores de ID: Los selectores de ID apuntan a un elemento HTML específico que tiene un ID específico. Los selectores de ID se definen con un signo de almohadilla (#) seguido del nombre del ID.

Ejemplo del HTML y CSS:

```html
<!DOCTYPE html>
<html>
 <head> </head>
 <body>
  <p id="parrafo1">Este es un párrafo de texto.</p>
  <p id="parrafo2">Este es otro párrafo de texto.</p>
 </body>
</html>
```

```css
/* Estilo aplicado al elemento con el ID "parrafo1" */
#parrafo1 {
 color: red;
}
```

- Selectores de atributo: Los selectores de atributo apuntan a elementos HTML que tienen un atributo específico. Los selectores de atributo se definen utilizando corchetes [] y especificando el nombre del atributo y, opcionalmente, el valor del atributo.

Ejemplo del HTML y CSS:

```html
<!DOCTYPE html>
<html>
 <head> </head>
 <body>
  <a href="pagina1.html">Enlace 1</a>
  <a href="pagina2.html">Enlace 2</a>
 </body>
</html>
```

```css
/* Estilo aplicado a todos los enlaces con el atributo "href" */
a[href] {
 color: red;
}
```

- Selectores de combinación: Los selectores de combinación se utilizan para apuntar a elementos HTML que cumplen con múltiples condiciones. Los selectores de combinación pueden combinar selectores de etiqueta, clases, IDs, atributos, etc.

Ejemplo del HTML y CSS:

```html
<!DOCTYPE html>
<html>
 <head> </head>
 <body>
  <p class="destacado">Este es un párrafo de texto destacado.</p>
  <p>Este es otro párrafo de texto.</p>
 </body>
</html>
```

```css
/* Estilo aplicado a todos los párrafos con la clase "destacado" dentro de un div */
div p.destacado {
 color: red;
}
```

### Que es un CLASS y un ID en CSS?

En CSS, una clase es un identificador que se utiliza para aplicar estilos a uno o más elementos HTML. Las clases se definen en el documento CSS utilizando un punto (.) seguido del nombre de la clase, y se aplican a los elementos HTML utilizando el atributo class. Aquí tienes un ejemplo de cómo definir y aplicar una clase en CSS:

```css
/* Definición de una clase en CSS */
.destacado {
 color: red;
}
```

```html
<!-- Aplicación de una clase a un elemento HTML -->
<p class="destacado">Este es un párrafo de texto destacado.</p>
```

Un ID es un identificador único que se utiliza para aplicar estilos a un elemento HTML específico. Los IDs se definen en el documento CSS utilizando un signo de almohadilla (#) seguido del nombre del ID, y se aplican a los elementos HTML utilizando el atributo id. Aquí tienes un ejemplo de cómo definir y aplicar un ID en CSS:

```css
/* Definición de un ID en CSS */
#parrafo1 {
 color: red;
}
```

```html
<!-- Aplicación de un ID a un elemento HTML -->
<p id="parrafo1">Este es un párrafo de texto.</p>
```

### Que debo usar para seleccionar un elemento en CSS, un CLASS o un ID?

La elección entre usar una clase o un ID para seleccionar un elemento en CSS depende de la naturaleza y el propósito del estilo que se desea aplicar. Aquí tienes algunas consideraciones para elegir entre una clase y un ID:

- Clase: Debes usar una clase cuando quieras aplicar un estilo a uno o más elementos HTML que comparten características o estilos similares. Las clases son útiles para aplicar estilos a grupos de elementos relacionados y para reutilizar estilos en diferentes partes de un documento HTML.

- ID: Debes usar un ID cuando quieras aplicar un estilo a un elemento HTML específico que es único en el documento. Los IDs son útiles para aplicar estilos a elementos individuales y para identificar elementos específicos en el documento HTML.

Pero en general, es recomendable utilizar clases en lugar de IDs para aplicar estilos en CSS, ya que las clases son más flexibles, reutilizables y fáciles de mantener. Los IDs deben reservarse para casos en los que se necesita identificar un elemento específico en el documento HTML, como anclas de navegación, secciones de la página, etc. Se recomienda evitar el uso excesivo de IDs y en su lugar utilizar clases para aplicar estilos de manera más eficiente y escalable.

### Herencia en CSS

La herencia en CSS se refiere a la forma en que los estilos se aplican a los elementos secundarios basados en los estilos de sus elementos padres. Los estilos heredados se aplican automáticamente a los elementos secundarios, a menos que se anulen con estilos específicos. Aquí tienes una descripción de cómo funciona la herencia en CSS:

```css
/* Estilo aplicado a todos los párrafos */
div {
 color: red;
}
```

```html
<!DOCTYPE html>
<html>
 <head> </head>
 <body>
  <div>
   <<p>Este es un párrafo de texto.</p>
  </div>
 </body>
</html>
```

En este ejemplo, el párrafo dentro del div heredará automáticamente el color rojo del div.

### Cuales propiedades de CSS se heredan?

Algunas propiedades de CSS se heredan automáticamente de los elementos padres a los elementos secundarios, mientras que otras no se heredan. Aquí tienes una lista de algunas propiedades de CSS comunes que se heredan:

- color
- font-family
- font-size
- font-style
- font-weight
- line-height
- text-align
- text-decoration
- text-transform
- visibility

### Como lee el navegador los estilos de CSS?

Cuando un navegador lee los estilos de CSS, sigue un proceso de cascada y priorización para determinar qué estilos se aplicarán a los elementos HTML. Aquí tienes una descripción del proceso que sigue un navegador para leer los estilos de CSS:

- Selección de estilos: El navegador selecciona los estilos de CSS que se aplicarán a los elementos HTML basándose en las reglas de estilo definidas en el documento CSS y en los estilos heredados.

- Cascada: El navegador aplica los estilos seleccionados siguiendo las reglas de cascada de CSS, que determinan la prioridad y la especificidad de los estilos.

- Especificidad: Los estilos con mayor especificidad tienen prioridad sobre los estilos con menor especificidad. La especificidad de un estilo se basa en el tipo de selector, las clases, los IDs, etc.

- Importancia: Los estilos con mayor importancia tienen prioridad sobre los estilos con menor importancia. La importancia de un estilo se puede especificar utilizando la regla !important en el documento CSS.

- Orden de aparición: En caso de que dos estilos tengan la misma especificidad e importancia, el estilo que aparece más tarde en el documento CSS tiene prioridad.

En resumen, cuando un navegador lee los estilos de CSS, selecciona los estilos que se aplicarán a los elementos HTML, sigue las reglas de cascada y priorización de CSS, y aplica los estilos siguiendo el orden de aparición en el documento CSS.

### Explicacion de la procedencia de declaraciones de CSS

La procedencia de las declaraciones de CSS se refiere a la forma en que se determina qué estilos se aplicarán a los elementos HTML basándose en las reglas de estilo definidas en el documento CSS. La procedencia de las declaraciones de CSS se basa en las reglas de cascada y priorización de CSS, que determinan la prioridad y la especificidad de los estilos. Aquí tienes una descripción de la procedencia de las declaraciones de CSS:

- Si son propiedades distintas, se combinan.

- Si es una propiedad repetida, queda una sola.

- ID pisa cualquier regla, al menos que la regla tenga !important.

- Class sobrepasa a las etiquetas.

- Etiquetas tiene la menor prioridad.

### Estilos en linea, no recomendado

Los estilos en línea no son recomendados en CSS, ya que pueden dificultar la gestión y el mantenimiento de los estilos en un documento HTML. Los estilos en línea se aplican directamente a los elementos HTML utilizando el atributo style, lo que puede dificultar la reutilización, la coherencia y la escalabilidad de los estilos. En lugar de utilizar estilos en línea, es recomendable utilizar estilos internos o externos en un documento CSS para aplicar estilos de manera más eficiente y organizada.

### Importancia de los selectores en CSS o especificidad

La importancia de los selectores en CSS, también conocida como especificidad, es un concepto clave que determina qué estilos se aplicarán a los elementos HTML basándose en las reglas de estilo definidas en el documento CSS. La especificidad de un selector se basa en el tipo de selector, las clases, los IDs, etc., y determina la prioridad y la importancia de los estilos. Aquí tienes una descripción de la importancia de los selectores en CSS o especificidad:

- Etiquetas: Los selectores de etiqueta tienen la menor especificidad y prioridad en CSS. Los estilos aplicados a través de selectores de etiqueta se aplicarán a todos los elementos HTML del mismo tipo.

- Clases: Los selectores de clase tienen mayor especificidad y prioridad que los selectores de etiqueta en CSS. Los estilos aplicados a través de clases se aplicarán a los elementos HTML que tengan la clase específica.

### !important en CSS

La regla !important en CSS se utiliza para especificar la importancia de un estilo y para darle prioridad sobre otros estilos. La regla !important se coloca al final de la declaración de estilo y anula cualquier estilo con menor importancia. Aquí tienes un ejemplo de cómo utilizar la regla !important en CSS:

```css
/* Estilo con !important */
p {
 color: red !important;
}
```

En este ejemplo, el color rojo tiene prioridad sobre cualquier otro estilo que se aplique al párrafo.

No se recomienda el uso excesivo de la regla !important en CSS, ya que puede dificultar la gestión y el mantenimiento de los estilos. Es preferible utilizar selectores específicos y evitar el uso de !important siempre que sea posible.

### Primeras propiedades de CSS

#### Propiedad color

La propiedad color en CSS se utiliza para especificar el color del texto de un elemento HTML. La propiedad color puede tomar valores como nombres de colores, códigos hexadecimales, códigos RGB, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad color en CSS:

```css
/* Estilo aplicado al color del texto */
p {
 color: red;
}
```

#### Que herramientas puedo utilizar para seleccionar un color en CSS?

Puedes utilizar varias herramientas para seleccionar un color en CSS, incluyendo:

- Paleta de colores: Puedes utilizar una paleta de colores en línea o una herramienta de selección de colores en un editor de código para elegir un color específico.

#### Estilos de Listas

La propiedad list-style en CSS se utiliza para especificar el estilo de las viñetas o numeración de una lista HTML. La propiedad list-style puede tomar valores como disc, circle, square, decimal, lower-roman, upper-roman, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad list-style en CSS:

```css
/* Estilo aplicado al estilo de la lista */
ul {
 list-style: disc;
}
```

```css
/* Eliminando estilo de las listas */
ul {
 list-style: none;
}
```

#### Estilos de Texto

La propiedad font-family en CSS se utiliza para especificar la fuente del texto de un elemento HTML. La propiedad font-family puede tomar valores como nombres de fuentes, familias genéricas de fuentes, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad font-family en CSS:

```css
/* Estilo aplicado a la fuente del texto */
p {
 font-family: Arial, sans-serif;
}
```

La propieda font-size en CSS se utiliza para especificar el tamaño del texto de un elemento HTML. La propiedad font-size puede tomar valores como píxeles, em, porcentajes, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad font-size en CSS:

```css
/* Estilo aplicado al tamaño del texto */
p {
 font-size: 16px;
}
```

La propiedad font-weight en CSS se utiliza para especificar el grosor del texto de un elemento HTML. La propiedad font-weight puede tomar valores como normal, bold, bolder, lighter, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad font-weight en CSS:

```css
/* Estilo aplicado al grosor del texto */
p {
 font-weight: bold;
}
```

La propiedad font-style en CSS se utiliza para especificar el estilo de la fuente del texto de un elemento HTML. La propiedad font-style puede tomar valores como normal, italic, oblique, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad font-style en CSS:

```css
/* Estilo aplicado al estilo de la fuente del texto */
p {
 font-style: italic;
}
```

La propiedad text-align en CSS se utiliza para especificar la alineación del texto de un elemento HTML. La propiedad text-align puede tomar valores como left, right, center, justify, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad text-align en CSS:

```css
/* Estilo aplicado a la alineación del texto */
p {
 text-align: center;
}
```

La propiedad text-decoration en CSS se utiliza para especificar la decoración del texto de un elemento HTML. La propiedad text-decoration puede tomar valores como none, underline, overline, line-through, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad text-decoration en CSS:

```css
/* Estilo aplicado a la decoración del texto */
p {
 text-decoration: underline;
}
```

#### Estilos de Fondo o background

La propiedad background-color en CSS se utiliza para especificar el color de fondo de un elemento HTML. La propiedad background-color puede tomar valores como nombres de colores, códigos hexadecimales, códigos RGB, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad background-color en CSS:

```css
/* Estilo aplicado al color de fondo */
body {
 background-color: lightgray;
}
```

La propiedad background-image en CSS se utiliza para especificar una imagen de fondo para un elemento HTML. La propiedad background-image puede tomar valores como URLs de imágenes, gradientes, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad background-image en CSS:

```css
/* Estilo aplicado a la imagen de fondo */
body {
 background-image: url("imagen.jpg");
}
```

La propiedad background-repeat en CSS se utiliza para especificar cómo se repetirá una imagen de fondo en un elemento HTML. La propiedad background-repeat puede tomar valores como repeat, no-repeat, repeat-x, repeat-y, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad background-repeat en CSS:

```css
/* Estilo aplicado a la repetición de la imagen de fondo */
body {
 background-repeat: no-repeat;
}
```

La propiedad background-position en CSS se utiliza para especificar la posición de una imagen de fondo en un elemento HTML. La propiedad background-position puede tomar valores como top, bottom, left, right, center, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad background-position en CSS:

```css
/* Estilo aplicado a la posición de la imagen de fondo */
body {
 background-position: center;
}
```

La propiedad background-attachment en CSS se utiliza para especificar si una imagen de fondo se desplazará con el contenido de un elemento HTML. La propiedad background-attachment puede tomar valores como scroll, fixed, local, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad background-attachment en CSS:

```css
/* Estilo aplicado a la fijación de la imagen de fondo */
body {
 background-attachment: fixed;
}
```

La propiedad background-size en CSS se utiliza para especificar el tamaño de una imagen de fondo en un elemento HTML. La propiedad background-size puede tomar valores como auto, cover, contain, valores de longitud, porcentajes, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad background-size en CSS:

```css
/* Estilo aplicado al tamaño de la imagen de fondo */
body {
 background-size: cover;
}
```

```css
/* Estilo aplicado al tamaño de la imagen de fondo */
body {
 background-size: 100px 100px;
}
```

```css
/* Estilo aplicado al tamaño de la imagen de fondo */
body {
 background-size: 50% 50%;
}
```

### Unidades de medida en CSS

#### Unidades de medida absolutas

Las unidades de medida absolutas en CSS se utilizan para especificar tamaños fijos que no cambian con el tamaño de la ventana del navegador o el dispositivo. Algunas unidades de medida absolutas comunes incluyen:

- px (píxeles): Una unidad de medida de píxeles que se utiliza para especificar tamaños fijos en píxeles.

- in (pulgadas): Una unidad de medida de pulgadas que se utiliza para especificar tamaños fijos en pulgadas.

- cm (centímetros): Una unidad de medida de centímetros que se utiliza para especificar tamaños fijos en centímetros.

- mm (milímetros): Una unidad de medida de milímetros que se utiliza para especificar tamaños fijos en milímetros.

- pt (puntos): Una unidad de medida de puntos que se utiliza para especificar tamaños fijos en puntos.

- pc (picas): Una unidad de medida de picas que se utiliza para especificar tamaños fijos en picas.

#### Unidades de medida relativas

Las unidades de medida relativas en CSS se utilizan para especificar tamaños que se ajustan automáticamente en relación con el tamaño de la ventana del navegador o el dispositivo. Algunas unidades de medida relativas comunes incluyen:

- em: Una unidad de medida relativa que se utiliza para especificar tamaños en relación con el tamaño de la fuente del elemento.

- rem: Una unidad de medida relativa que se utiliza para especificar tamaños en relación con el tamaño de la fuente del elemento raíz (root).

- % (porcentaje): Una unidad de medida relativa que se utiliza para especificar tamaños en relación con el tamaño del elemento padre.

- vw (viewport width): Una unidad de medida relativa que se utiliza para especificar tamaños en relación con el ancho de la ventana del navegador.

- vh (viewport height): Una unidad de medida relativa que se utiliza para especificar tamaños en relación con la altura de la ventana del navegador.

### Reset CSS

El reset CSS es una técnica utilizada para restablecer los estilos predeterminados de los elementos HTML a un estado consistente y predecible en todos los navegadores. El reset CSS se utiliza para eliminar los márgenes, rellenos, tamaños de fuente, estilos de lista, etc., que pueden variar entre los navegadores y los sistemas operativos. Al restablecer los estilos predeterminados, el reset CSS proporciona una base limpia y consistente para aplicar estilos personalizados en un documento HTML. Aquí tienes un ejemplo de un reset CSS básico:

```css
/* Reset CSS básico */
* {
 margin: 0;
 padding: 0;
 box-sizing: border-box;
}
```

Reset mas avanzado:

```css
/* Reset CSS avanzado */
html {
 box-sizing: border-box;
}
*, *::before, *::after {
 box-sizing: inherit;
}
body {
 margin: 0;
 font-family: Arial, sans-serif;
}
h1, h2, h3, h4, h5, h6 {
 font-size: inherit;
 font-weight: inherit;
}
ul, ol {
 list-style: none;
}
```

## Clase 4 CSS + Box Model

### Box Model en CSS

El Box Model es un concepto fundamental en CSS que describe cómo se representan y se organizan los elementos HTML en una página web. El Box Model se compone de cuatro partes principales: el contenido, el relleno, el borde y el margen. Aquí tienes una descripción de cada parte del Box Model:

- Contenido: El contenido de un elemento HTML, como texto, imágenes, etc.

- Relleno: El espacio entre el contenido y el borde de un elemento HTML.

- Borde: El borde de un elemento HTML que rodea el contenido y el relleno.

- Margen: El espacio entre el borde de un elemento HTML y los elementos adyacentes.

### Width y Height en CSS

La propiedad width en CSS se utiliza para especificar el ancho de un elemento HTML. La propiedad width puede tomar valores como píxeles, porcentajes, em, rem, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad width en CSS:

```css
/* Estilo aplicado al ancho del elemento */
div {
 width: 200px;
}
```

La propiedad height en CSS se utiliza para especificar la altura de un elemento HTML. La propiedad height puede tomar valores como píxeles, porcentajes, em, rem, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad height en CSS:

```css
/* Estilo aplicado a la altura del elemento */
div {
 height: 100px;
}
```

### Overflow en CSS

La propiedad overflow en CSS se utiliza para especificar cómo se manejará el contenido que desborda los límites de un elemento HTML. La propiedad overflow puede tomar valores como visible, hidden, scroll, auto, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad overflow en CSS:

```css
/* Estilo aplicado al desbordamiento del contenido */
div {
 overflow: visible;
}
```

```css
/* Estilo aplicado al desbordamiento del contenido */
div {
 overflow: hidden;
}
```

```css
/* Estilo aplicado al desbordamiento del contenido */
div {
 overflow: scroll;
}
```

```css
/* Estilo aplicado al desbordamiento del contenido */
div {
 overflow: auto;
}
```

### Margin en CSS

La propiedad margin en CSS se utiliza para especificar el margen de un elemento HTML. La propiedad margin puede tomar valores como píxeles, porcentajes, em, rem, auto, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad margin en CSS:

```css
/* Esto le aplica un margen a todo el div */
div {
 margin: 10px;
}
```

```css
/* Esto le aplica un margen arribe y abajo de 10px y a los lados de 20px */
div {
 margin: 10px 20px;
}
```

```css
/* Esto le aplica un margen arriba de 10px, a la derecha de 20px, abajo de 30px y a la izquierda de 40px */
div {
 margin: 10px 20px 30px 40px;
}
```

```css
/* Esto le aplica solo un margen a los lados de 30px y no le aplica arriba y abajo */
div {
 margin: 0 30px;
}
```

### Padding en CSS

La propiedad padding en CSS se utiliza para especificar el relleno de un elemento HTML. La propiedad padding puede tomar valores como píxeles, porcentajes, em, rem, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad padding en CSS:

```css
/* Esto le aplica un relleno a todo el div */
div {
 padding: 10px;
}
```

```css
/* Esto le aplica un relleno arribe y abajo de 10px y a los lados de 20px */
div {
 padding: 10px 20px;
}
```

```css
/* Esto le aplica un relleno arriba de 10px, a la derecha de 20px, abajo de 30px y a la izquierda de 40px */
div {
 padding: 10px 20px 30px 40px;
}
```

```css
/* Esto le aplica solo un relleno a los lados de 30px y no le aplica arriba y abajo */
div {
 padding: 0 30px;
}
```

### Border en CSS

La propiedad border en CSS se utiliza para especificar el borde de un elemento HTML. La propiedad border puede tomar valores como ancho, estilo y color. Aquí tienes un ejemplo de cómo utilizar la propiedad border en CSS:

```css
/* Esto le aplica un borde a todo el div */
div {
 border: 1px solid black;
}
```

```css
/* Esto le aplica un borde arriba y abajo de 1px y a los lados de 2px */
div {
 border: 1px 2px;
}
```

```css
/* Esto le aplica un borde arriba de 1px, a la derecha de 2px, abajo de 3px y a la izquierda de 4px */
div {
 border: 1px 2px 3px 4px;
}
```

```css
/* Esto le aplica solo un borde a los lados de 3px y no le aplica arriba y abajo */
div {
 border: 0 3px;
}
```

Estilos de borde:

- solid: Un borde sólido.
- dotted: Un borde punteado.
- dashed: Un borde discontinuo.
- double: Un borde doble.

### Display en CSS

La propiedad display en CSS se utiliza para especificar cómo se mostrará un elemento HTML en la página web. La propiedad display puede tomar valores como block, inline, inline-block, none, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad display en CSS:

```css
/* Esto le aplica un display de bloque al div */
div {
 display: block;
}
```

```css
/* Esto le aplica un display en línea al div */
div {
 display: inline;
}
```

```css
/* Esto le aplica un display en línea con bloque al div */
div {
 display: inline-block;
}
```

```css
/* Esto le aplica un display de ninguno al div */
div {
 display: none;
}
```

Tipos de elementos:

- block: Un elemento de bloque que ocupa todo el ancho disponible y comienza en una nueva línea.

- inline: Un elemento en línea que ocupa solo el ancho necesario y no comienza en una nueva línea.

- inline-block: nos permite tomar lo mejor de ambos mundos. Un elemento en línea que puede tener un ancho y alto.

### Ocultar elementos en CSS

La propiedad display en CSS se utiliza para ocultar elementos HTML en la página web. La propiedad display puede tomar el valor none para ocultar un elemento. Aquí tienes un ejemplo de cómo ocultar un elemento en CSS:

```css
/* Esto le aplica un display de ninguno al div */
div {
 display: none;
}
```

### Position en CSS

La propiedad position en CSS se utiliza para especificar el método de posicionamiento de un elemento HTML en la página web. La propiedad position puede tomar valores como static, relative, absolute, fixed, sticky, etc. Aquí tienes un ejemplo de cómo utilizar la propiedad position en CSS:

```css
/* Esto le aplica un position estático al div */
div {
 position: static;
}
```

```css
/* Esto le aplica un position relativo al div */
div {
 position: relative;
}
```

```css
/* Esto le aplica un position absoluto al div */
div {
 position: absolute;
}
```

```css
/* Esto le aplica un position fijo al div */
div {
 position: fixed;
}
```

```css
/* Esto le aplica un position pegajoso al div */
div {
 position: sticky;
}
```

### Valores de la propiedad position en CSS

- static: El elemento se coloca en el flujo normal del documento.
- relative: El elemento se coloca en relación con su posición original.
- absolute: El elemento se coloca en relación con su elemento padre más cercano.
- fixed: El elemento se coloca en relación con la ventana del navegador.
- sticky: El elemento se coloca en relación con el desplazamiento del documento.

Le podemos pasar valores de top, right, bottom y left para especificar la posición del elemento.

### Propiedad z-index en CSS

La propiedad z-index en CSS se utiliza para especificar el orden de apilamiento de los elementos HTML en la página web. La propiedad z-index puede tomar valores enteros positivos y negativos para determinar el orden de apilamiento de los elementos. Aquí tienes un ejemplo de cómo utilizar la propiedad z-index en CSS:

```css
/* Esto le aplica un z-index de 1 al div */
div {
 z-index: 1;
}
```

Caso de uso:

- Si tienes dos elementos superpuestos, puedes utilizar z-index para especificar cuál elemento debe estar encima del otro.

## Primera pre-entrega

## Prototipo de la Web (Formato: PDF o Imagen)

- Objetivo: Mostrar una representación visual de cómo lucirá el sitio web cuando esté completamente funcional.
  Ejemplo: Utilizar herramientas como Balsamiq para crear un diseño estático que ilustre la disposición de los elementos en la página, como el encabezado, el pie de página, la barra de navegación, etc. Si quieren usar figma o adobe XD también es valido pero no es necesario ya que son programas mas complejos.

## Estructura Inicial de la Web en HTML (Formato: Archivos HTML)

- Objetivo: Convertir el diseño estático del prototipo en una estructura HTML básica.
- Incluye:

1. Etiquetas Semánticas: Utilizar etiquetas HTML5 semánticas como \<header\>, \<nav\>, \<main\>, \<section\>, \<article\>, \<footer\>, etc., para estructurar el contenido de manera significativa.
   Ejemplo: \<header\>, \<nav\>, \<footer\>.
2. Contenido: Insertar contenido real utilizando etiquetas HTML apropiadas como \<img\>, \<p\>, \<h1\>, \<h2\>, etc., para denotar dónde estarán los elementos como imágenes, párrafos y títulos.
   Ejemplo: \<img src="imagen.jpg" alt="Descripción de la imagen"\>, \<p\>Texto del párrafo.\</p\>, \<h1\>Título principal\</h1\>.
3. Páginas: Incluir las secciones del sitio web ya maquetadas con la estructura propia de cada página.
   Ejemplo: Crear archivos HTML separados para cada página del sitio, como index.html, acerca.html, contacto.html, etc.
4. Enlaces: Agregar enlaces entre las páginas del sitio web.
   Ejemplo: \<a href="contacto.html"\>Contacto\</a\>.
5. Agrear estilos CSS: Agregar estilos CSS para darle formato a la estructura HTML.se deben usar las propiedades de CSS que hemos visto en clase modificar textos, encabezados, img, colores, background y box modeling. Puede ser un estilo basico, no es necesario que sea muy elaborado.
   Ejemplo: \<link rel="stylesheet" href="styles.css"\>.
6. Realizar la correcta anidación de las etiquetas HTML para que la estructura sea clara y entendible.
7. Sintaxis: Utilizar una sintaxis limpia y clara, con sangrías y retornos de carro adecuados.
8. Indentación: Utilizar sangrías para mostrar la jerarquía y anidación de las etiquetas HTML.
9. Estrucura: Crear una estructura de carpetas y archivos clara y organizada.

## Clase 5 Flexbox

### Flexbox en CSS

Flexbox es un modelo de diseño en CSS que permite crear diseños flexibles y eficientes para elementos HTML. Flexbox se basa en un sistema de cajas flexibles que se pueden organizar y alinear de manera dinámica, lo que facilita la creación de diseños complejos y responsivos. Aquí tienes una descripción de los conceptos clave de Flexbox:

- Contenedor Flex: Un contenedor flex es un elemento HTML que contiene elementos flexibles y se configura con la propiedad display: flex en CSS.

- Elementos Flex: Los elementos flex son los hijos de un contenedor flex y se configuran con la propiedad flex: 1 en CSS.

- Eje Principal: El eje principal es la dirección principal en la que se alinean los elementos flex dentro de un contenedor flex. El eje principal se configura con la propiedad flex-direction en CSS.

### Beneficios de Flexbox

- Diseño flexible: Flexbox permite crear diseños flexibles y adaptables que se ajustan automáticamente al tamaño de la ventana del navegador o el dispositivo.

- Alineación dinámica: Flexbox permite alinear y distribuir elementos flexibles de manera dinámica y eficiente, lo que facilita la creación de diseños complejos y responsivos.

- Ordenamiento: Flexbox permite cambiar el orden de los elementos flexibles de manera dinámica, lo que facilita la creación de diseños personalizados y adaptables.

### Propiedades de Flexbox

- display: Esta propiedad determina si un contenedor es un contenedor flexible o un bloque regular.

Ejemplo:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
}
```

- flex-direction: Controla la dirección en la que se colocan los elementos flexibles dentro de su contenedor.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-direction: row;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-direction: row-reverse;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-direction: column;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-direction: column-reverse;
}
```

- flex-wrap: Controla si los elementos flexibles se envuelven en múltiples líneas o no.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-wrap: nowrap;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-wrap: wrap;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-wrap: wrap-reverse;
}
```

- flex-flow: Es una propiedad abreviada que combina flex-direction y flex-wrap en una sola declaración.

Ejemplo:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-flow: row wrap;
}
```

- justify-content: Controla la alineación de los elementos flexibles a lo largo del eje principal del contenedor.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 justify-content: flex-start;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 justify-content: flex-end;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 justify-content: center;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 justify-content: space-between;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 justify-content: space-around;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 justify-content: space-evenly;
}
```

- align-items: Controla la alineación de los elementos flexibles a lo largo del eje transversal del contenedor.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-items: stretch;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-items: flex-start;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-items: flex-end;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-items: center;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-items: baseline;
}
```

- align-content: Solo se aplica si hay varias líneas de elementos flexibles dentro del contenedor. Controla la alineación de esas líneas en el eje transversal.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: stretch;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: flex-start;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: flex-end;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: center;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: space-between;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: space-around;
}
```

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 align-content: space-evenly;
}
```

### Ejemplo de Flexbox

```css
/* Estilo aplicado al contenedor flex */
.container {
 display: flex;
 flex-direction: row;
 justify-content: space-between;
 align-items: center;
}
```

```css
/* Estilo aplicado a los elementos flex */
.item {
 flex: 1;
 align-self: center;
 order: 2;
}
```

### Resumen de cada propiedad de Flexbox

### Propiedades de Flexbox en CSS

1. **`display`**: Esta propiedad determina si un contenedor es un contenedor flexible o un bloque regular.
   - `flex`: Establece el contenedor como un contenedor flexible.
   - `inline-flex`: Establece el contenedor como un contenedor flexible en línea.

2. **`flex-direction`**: Controla la dirección en la que se colocan los elementos flexibles dentro de su contenedor.
   - `row`: Los elementos son colocados en la misma dirección que el texto.
   - `row-reverse`: Los elementos son colocados en la dirección opuesta a la del texto.
   - `column`: Los elementos son colocados de arriba a abajo.
   - `column-reverse`: Los elementos son colocados de abajo a arriba.

3. **`flex-wrap`**: Controla si los elementos flexibles se envuelven en múltiples líneas o no.
   - `nowrap`: Los elementos se ajustan en una sola línea.
   - `wrap`: Los elementos se envuelven en múltiples líneas si es necesario.
   - `wrap-reverse`: Los elementos se envuelven en múltiples líneas en dirección opuesta.

4. **`flex-flow`**: Es una propiedad abreviada que combina `flex-direction` y `flex-wrap` en una sola declaración.

5. **`justify-content`**: Controla la alineación de los elementos flexibles a lo largo del eje principal del contenedor.
   - `flex-start`: Los elementos se alinean al principio del contenedor.
   - `flex-end`: Los elementos se alinean al final del contenedor.
   - `center`: Los elementos se alinean en el centro del contenedor.
   - `space-between`: Los elementos se distribuyen equitativamente; el primer elemento está al principio, el último al final.
   - `space-around`: Los elementos se distribuyen equitativamente con espacios iguales alrededor de ellos.
   - `space-evenly`: Los elementos se distribuyen equitativamente con espacios iguales alrededor de ellos, incluyendo el espacio antes y después del primer y último elemento.

6. **`align-items`**: Controla la alineación de los elementos flexibles a lo largo del eje transversal del contenedor.
   - `stretch`: Los elementos se estiran para llenar el contenedor.
   - `flex-start`: Los elementos se alinean al principio del contenedor.
   - `flex-end`: Los elementos se alinean al final del contenedor.
   - `center`: Los elementos se alinean en el centro del contenedor.
   - `baseline`: Los elementos se alinean según la línea de base.

7. **`align-content`**: Solo se aplica si hay varias líneas de elementos flexibles dentro del contenedor. Controla la alineación de esas líneas en el eje transversal.
   - `stretch`: Las líneas se estiran para llenar el contenedor.
   - `flex-start`: Las líneas se alinean al principio del contenedor.
   - `flex-end`: Las líneas se alinean al final del contenedor.
   - `center`: Las líneas se alinean en el centro del contenedor.
   - `space-between`: Las líneas se distribuyen equitativamente; la primera línea está al principio, la última al final.
   - `space-around`: Las líneas se distribuyen equitativamente con espacios iguales alrededor de ellas.
   - `space-evenly`: Las líneas se distribuyen equitativamente con espacios iguales alrededor de ellas, incluyendo el espacio antes y después de la primera y última línea.

### Recursos de Flexbox

- [Flexbox playground](https://codepen.io/enxaneta/full/adLPwv): Un entorno de desarrollo en línea para experimentar con Flexbox.
- [Flexbox Froggy](https://flexboxfroggy.com/): Un juego en línea que te enseña los conceptos básicos de Flexbox.
- [Flexbox Defense](http://www.flexboxdefense.com/): Un juego en línea que te enseña los conceptos básicos de Flexbox.
- [CSS-Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/): Una guía completa de Flexbox con ejemplos y explicaciones detalladas.
- [MDN Web Docs: Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox): Documentación oficial de Flexbox en MDN Web Docs.
- [cssreference.io: Flexbox](https://cssreference.io/flexbox/): Una guía de referencia rápida de Flexbox con ejemplos y explicaciones.
- [Flexbox Cheatsheet](https://yoksel.github.io/flex-cheatsheet/): Una hoja de trucos de Flexbox con ejemplos y explicaciones.
- [Flexbox Playground](https://flexbox.tech/): Un entorno de desarrollo en línea para experimentar con Flexbox.
- [Flexy Boxes](https://the-echoplex.net/flexyboxes/): Un generador de código en línea para Flexbox.
- [Flexer](https://www.flexer.dev/): Un generador de código en línea para Flexbox.
- [Flexbox Patterns](https://www.flexboxpatterns.com/): Una colección de patrones de diseño comunes creados con Flexbox.

### Propiedades de los hijo avanzadas

Existe una serie de propiedades que se pueden aplicar a los elementos flexibles para controlar su comportamiento y apariencia dentro del contenedor flex. Algunas de estas propiedades incluyen:

- Flex-grow: Controla la capacidad de un elemento flexible para crecer en relación con otros elementos flexibles en el contenedor.

- Flex-shrink: Controla la capacidad de un elemento flexible para encogerse en relación con otros elementos flexibles en el contenedor.

- Flex-basis: Establece el tamaño base de un elemento flexible antes de que se apliquen flex-grow y flex-shrink.

Valores de las propiedades:

Defaul:

```css
/* Estilo aplicado a los elementos flex */
.item {
   flex-grow: 0; /* Valor por defecto, posibles valores 0, 1, 2, etc. */
   flex-shrink: 1; /* Valor por defecto, posibles valores 0, 1, 2, etc. */
   flex-basis: auto; /* Valor por defecto, posibles valores auto, 100px, 50%, etc. */
}
```

Ejemplo:

```css
/* Estilo aplicado a los elementos flex */
.item {
   flex-grow: 1; /* El elemento crecerá para llenar el espacio disponible. */
   flex-shrink: 0; /* El elemento no se encogerá si no hay espacio suficiente. */
   flex-basis: 100px; /* El elemento tendrá un tamaño base de 100px. */
}
```

Estas propiedades se pueden combinar en una sola declaración abreviada llamada flex, que toma los valores de flex-grow, flex-shrink y flex-basis en ese orden.

Ejemplo:

```css
/* Estilo aplicado a los elementos flex */
.item {
   flex: 1 0 100px; /* Equivalente a flex-grow: 1; flex-shrink: 0; flex-basis: 100px; */
}
```

## Clase 6 Grid

Grid es un modelo de diseño en CSS que permite crear diseños de cuadrícula flexibles y eficientes para elementos HTML. Grid se basa en un sistema de cuadrícula bidimensional que se puede organizar y alinear de manera dinámica, lo que facilita la creación de diseños complejos y responsivos.

### Diferencias entre Flexbox y Grid

- Flexbox: Flexbox es un modelo de diseño unidimensional que se utiliza para organizar y alinear elementos flexibles en una sola dirección, como filas o columnas.

- Grid: Grid es un modelo de diseño bidimensional que se utiliza para organizar y alinear elementos en una cuadrícula de filas y columnas.

Ambos modelos de diseño son complementarios y se pueden utilizar juntos para crear diseños flexibles y eficientes en una página web.

### Propiedades de Grid

- display: Esta propiedad determina si un contenedor es un contenedor de cuadrícula o un bloque regular.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
}
```

- grid-template-columns: Establece el número y el tamaño de las columnas en la cuadrícula.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 grid-template-columns: 100px 200px 300px;
}
```

- grid-template-rows: Establece el número y el tamaño de las filas en la cuadrícula.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 grid-template-rows: 100px 200px 300px;
}
```

- grid-template-areas: Establece un nombre para cada área de la cuadrícula y asigna elementos a esas áreas.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 grid-template-areas:
 "header header header"
 "sidebar main main"
 "footer footer footer";
}
```

- gap: Establece el espacio entre las filas y las columnas de la cuadrícula.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 gap: 10px;
}
```

- column-gap: Establece el espacio entre las columnas de la cuadrícula.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 gcolumn-gap: 10px;
}
```

- row-gap: Establece el espacio entre las filas de la cuadrícula.

Ejemplo:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 row-gap: 10px;
}
```

### Posicionamiento de los hijos desde el contenedor

- justify-items: Controla la alineación de los elementos en el eje principal de la cuadrícula.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-items: start;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-items: end;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-items: center;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-items: stretch;
}
```

- align-items: Controla la alineación de los elementos en el eje transversal de la cuadrícula.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-items: start;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-items: end;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-items: center;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-items: stretch;
}
```

- justify-content: Controla la alineación de las columnas en el eje principal de la cuadrícula.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-content: start;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-content: end;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-content: center;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-content: space-between;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-content: space-around;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 justify-content: space-evenly;
}
```

- align-content: Controla la alineación de las filas en el eje transversal de la cuadrícula.

Ejemplo de valores:

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-content: start;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-content: end;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-content: center;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-content: space-between;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-content: space-around;
}
```

```css
/* Estilo aplicado al contenedor de cuadrícula */
.container {
 display: grid;
 align-content: space-evenly;
}
```

### Posicionamiento de los hijos desde el hijo

- justify-self: Controla la alineación de un elemento en el eje principal de la cuadrícula.

Ejemplo de valores:

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 justify-self: start;
}
```

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 justify-self: end;
}
```

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 justify-self: center;
}
```

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 justify-self: stretch;
}
```

- align-self: Controla la alineación de un elemento en el eje transversal de la cuadrícula.

Ejemplo de valores:

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 align-self: start;
}
```

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 align-self: end;
}
```

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 align-self: center;
}
```

```css
/* Estilo aplicado al hiji de la cuadrícula */
.item {
 align-self: stretch;
}
```

## Clase 7 Media Queries

### Diseño Responsivo

El diseño responsivo es una técnica de diseño web que permite crear sitios web que se adaptan y responden a diferentes tamaños de pantalla, dispositivos y resoluciones. El diseño responsivo utiliza técnicas como media queries, flexbox y grid para crear diseños flexibles y adaptables que se ajustan automáticamente al tamaño de la ventana del navegador o el dispositivo.

### Media Queries

Las media queries son una técnica de diseño web que permite aplicar estilos CSS específicos a diferentes tamaños de pantalla, dispositivos y resoluciones. Las media queries se utilizan para crear diseños responsivos que se adaptan y responden a diferentes contextos de visualización.

### Sintaxis de Media Queries

La sintaxis de una media query en CSS consta de tres partes principales: un tipo de medio, una condición y un bloque de estilos. Aquí tienes un ejemplo de la sintaxis de una media query en CSS:

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px */
@media screen and (max-width: 600px) {
 body {
   background-color: lightblue;
 }
}
```

### Tipos de Medios

Los tipos de medios en CSS se utilizan para especificar el tipo de dispositivo o contexto de visualización al que se aplicarán los estilos CSS. Algunos tipos de medios comunes incluyen:

- all: Todos los dispositivos y contextos de visualización.

- screen: Pantallas de computadoras, tabletas y teléfonos.

- print: Impresoras y documentos impresos.

- speech: Lectores de pantalla y dispositivos de voz.

### Condiciones de Media Queries

Las condiciones de las media queries en CSS se utilizan para especificar las reglas que se aplicarán a diferentes tamaños de pantalla, dispositivos y resoluciones. Algunas condiciones comunes incluyen:

- width: El ancho de la ventana del navegador o el dispositivo.

- height: La altura de la ventana del navegador o el dispositivo.

- orientation: La orientación de la pantalla del dispositivo.

- aspect-ratio: La relación de aspecto de la pantalla del dispositivo.

- resolution: La resolución de la pantalla del dispositivo.

### Ejemplos de Media Queries

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px */
@media screen and (max-width: 600px) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con un ancho mínimo de 600px */
@media screen and (min-width: 600px) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con una orientación horizontal */
@media screen and (orientation: landscape) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con una orientación vertical */
@media screen and (orientation: portrait) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con una relación de aspecto de 16:9 */
@media screen and (aspect-ratio: 16/9) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con una resolución de 300 ppp */
@media screen and (resolution: 300dpi) {
 body {
   background-color: lightblue;
 }
}
```

### Operadores Lógicos en Media Queries

Los operadores lógicos en las media queries en CSS se utilizan para combinar múltiples condiciones en una sola media query. Algunos operadores lógicos comunes incluyen:

- and: Combina múltiples condiciones en una sola media query.

- not: Niega una condición en una media query.

- only: Limita la aplicación de una media query a dispositivos que admiten la condición.

Ejemplos de operadores lógicos:

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px y una orientación horizontal */
@media screen and (max-width: 600px) and (orientation: landscape) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px y una orientación vertical */
@media screen and (max-width: 600px) and (orientation: portrait) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px y una orientación vertical */
@media screen and (max-width: 600px) and (orientation: portrait) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px y una orientación vertical */
@media screen and (max-width: 600px) and (orientation: portrait) {
 body {
   background-color: lightblue;
 }
}
```

```css
/* Estilo aplicado a una pantalla con un ancho máximo de 600px y una orientación vertical */
@media screen and (max-width: 600px) and (orientation: portrait) {
 body {
   background-color: lightblue;
 }
}
```

### Enfoque Mobile First

El enfoque "Mobile First" es una técnica de diseño web que se centra en el diseño y desarrollo de sitios web para dispositivos móviles antes que para dispositivos de escritorio. El enfoque "Mobile First" utiliza media queries y estilos CSS para crear diseños responsivos que se adaptan y responden a diferentes tamaños de pantalla, dispositivos y resoluciones.

Cuando trabajamos con media queries, es importante tener en cuenta el enfoque "Mobile First" para garantizar que los estilos se apliquen correctamente en dispositivos móviles y se adapten a dispositivos de escritorio.

### Ejemplo de Media Queries con el enfoque "Mobile First"

```css
/* Estilo aplicado a todos los dispositivos */
body {
 background-color: red;
}

/* Estilo aplicado a dispositivos con un ancho mínimo de 600px */
@media screen and (min-width: 600px) {
 body {
   background-color: lightgreen;
 }
}
```

### Breakpoints en Media Queries

Los breakpoints en media queries se utilizan para definir los puntos de quiebre en los que se aplicarán estilos CSS específicos a diferentes tamaños de pantalla, dispositivos y resoluciones. Los breakpoints se utilizan para crear diseños responsivos que se adaptan y responden a diferentes contextos de visualización.

Algunos breakpoints comunes incluyen:

- Pequeño: Dispositivos móviles con un ancho máximo de 600px.

- Mediano: Dispositivos de tableta con un ancho mínimo de 600px.

- Grande: Dispositivos de escritorio con un ancho mínimo de 1200px.

### Puntos a tener en cuenta a la hora de trabajar con Media Queries

- Utilizar el enfoque "Mobile First" para garantizar que los estilos se apliquen correctamente en dispositivos móviles y se adapten a dispositivos de escritorio.

- Utilizar breakpoints en media queries para definir los puntos de quiebre en los que se aplicarán estilos CSS específicos a diferentes tamaños de pantalla, dispositivos y resoluciones.

- Utilizar operadores lógicos en media queries para combinar múltiples condiciones en una sola media query.

- Utilizar tipos de medios en media queries para especificar el tipo de dispositivo o contexto de visualización al que se aplicarán los estilos CSS.

### Sintaxis Moderna de Media Queries ("Bonus 🚀")

Ahora en CSS tenemos una nueva sintaxis para poder escribir media querys de una manera más intuitiva y menos confusa, mediante rangos.

La nueva sintaxis de rangos para media querys de CSS consiste en usar operadores de comparación (populares en cualquier lenguaje de programación) en lugar de min-width y max-width.

< evalúa si un valor es menor que otro valor.
> evalúa si un valor es mayor que otro valor.
= evalúa si un valor es igual a otro valor.
<= evalúa si un valor es menor o igual a otro valor.
>= evalúa si un valor es mayor o igual a otro valor.

Ejemplo de la nueva sintaxis de media queries:

```css
// sintaxis clásica
@media screen and (min-width: 600px) {
  .element {
    /* La media query se aplica para resoluciones mayores a 600px */
  }
}

// sintaxis de rango
@media screen and (width >= 600px) {
  .element {
    /* La media query se aplica para 
       resoluciones mayores o iguales a 600px */
  }
}
```

```css
/* sintaxis clásica */
@media screen and (max-width: 800px) {
  .element {
    /* La media query se aplica para resoluciones menores a 800px */
  }
}

// sintaxis de rango
@media screen and (width <= 800px) {
  .element {
    /* La media query se aplica para 
       resoluciones menores o iguales a 600px */
  }
}
```

## Clase Bonus: Imagenes Responsivas

Podemos crear imágenes responsivas en CSS utilizando la propiedad max-width: 100%; para que las imágenes se ajusten automáticamente al tamaño de su contenedor. Esto garantiza que las imágenes se vean bien en dispositivos móviles y se adapten a diferentes tamaños de pantalla.

Ejemplo de imagen responsiva en CSS:

```css
/* Estilo aplicado a una imagen para que sea responsiva */
img {
 display: block;
 max-width: 100%;
 height: auto;
}
```

Otra forma de hacerlo es utilizar formatos de imagen modernos como WebP o , que ofrecen una mejor compresión y calidad que los formatos de imagen tradicionales como JPEG y PNG. Los formatos de imagen modernos son compatibles con la mayoría de los navegadores modernos y ofrecen una mejor experiencia de usuario en términos de rendimiento y calidad de imagen.

Ejemlo de imagen responsiva con formatos de imagen modernos:

```html
<picture>
 <source srcset="image.webp" type="image/webp">
 <source srcset="image.jpg" type="image/jpeg">
 <img loading="lazy" src="image.jpg" alt="Descripción de la imagen">
</picture>
```

Aplicando la propiedad loading="lazy" a las imágenes para que se carguen de forma diferida y mejoren el rendimiento de la página. La carga diferida de imágenes es una técnica de optimización de rendimiento que retrasa la carga de imágenes hasta que el usuario las necesita, lo que reduce el tiempo de carga de la página y mejora la experiencia del usuario.

### Indicando un sizes en el source de la imagen

```html
<picture>
  <source
     sizes="1920w, 1280w, 640w" 
     srcset="img/imagen.avif 1920w, 
         img/imagen-1280.avif 1280w, 
         img/imagen-640.avif 640w" 
     type="image/avif">
  <source
     sizes="1920w, 1280w, 640w" 
     srcset="img/imagen.webp 1920w, 
         img/imagen-1280.webp 1280w, 
         img/imagen-640.webp 640w" 
     type="image/webp">
  <source
     sizes="1920w, 1280w, 640w" 
     srcset="img/imagen.jpg 1920w, 
         img/imagen-1280.jpg 1280w, 
         img/imagen-640.jpg 640w" 
     type="image/jpeg">
  <img loading="lazy" decoding="async" src="img/imagen.jpg" lazyalt="imagen" width="500" height="300">
</picture>
```

Con este codigo estamos indicando que la imagen se va a mostrar en diferentes tamaños, dependiendo del tamaño de la pantalla del usuario, esto se hace con la propiedad sizes, que indica los tamaños de la imagen que se van a mostrar, en este caso 1920w, 1280w y 640w, que indican que la imagen se va a mostrar en esos tamaños dependiendo del tamaño de la pantalla del usuario.

Referencias:

<https://developer.mozilla.org/es/docs/Web/HTML/Element/picture>

<https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source>

## Clase 8: Pseudoclases y BEM

### Pseudoclases

Las pseudoclases en CSS son selectores que se utilizan para aplicar estilos a elementos en diferentes estados o situaciones. Algunas pseudoclases comunes incluyen:

- :link: Aplica estilos a un enlace no visitado.

- :hover: Aplica estilos a un elemento cuando el usuario pasa el cursor sobre él.

- :focus: Aplica estilos a un elemento cuando recibe el foco.

- :active: Aplica estilos a un elemento cuando está activo o seleccionado.

- :visited: Aplica estilos a un enlace visitado.

- :nth-child(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos.

- :not(): Aplica estilos a un elemento que no cumple con un selector específico.

- :first-child: Aplica estilos al primer hijo de un elemento.

- :last-child: Aplica estilos al último hijo de un elemento.

- :nth-of-type(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos del mismo tipo.

- :nth-last-child(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos, comenzando desde el último hijo.

- :nth-last-of-type(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos del mismo tipo, comenzando desde el último hijo.

### Detalle de :nth-child()

La pseudoclase :nth-child() en CSS se utiliza para seleccionar elementos que son hijos de un elemento padre y que cumplen con un cierto patrón de orden. Esta pseudoclase toma un argumento entre paréntesis, que se puede expresar en diferentes formas para seleccionar elementos específicos dentro del conjunto de hijos.

Los valores que se pueden pasar a :nth-child() son:

- n: Este valor representa todos los elementos hijos.
- n + a: Selecciona todos los elementos cuyo índice es mayor o igual a "a".
- n - a: Selecciona todos los elementos cuyo índice es menor o igual a "a".
- an + b: Selecciona todos los elementos cuyo índice es un múltiplo de "a" más "b".
- even: Selecciona todos los elementos hijos con índices pares.
- odd: Selecciona todos los elementos hijos con índices impares.

Por ejemplo, aquí hay algunos ejemplos de cómo se pueden usar:

:nth-child(2n): Selecciona todos los elementos hijos con índices pares.
:nth-child(3n + 1): Selecciona cada tercer elemento, comenzando desde el primer hijo.
:nth-child(odd): Selecciona todos los elementos hijos con índices impares.
:nth-child(4): Selecciona el cuarto elemento hijo.
Estos son solo algunos ejemplos, pero hay muchas formas de usar :nth-child() dependiendo de la estructura y el diseño del HTML que estés trabajando. Esta pseudoclase es útil para aplicar estilos específicos a elementos específicos dentro de una lista o de cualquier otro conjunto de elementos.

Ejemlos:

```css
/* Estilo aplicado a todos los elementos pares */
li:nth-child(2n) {
  background-color: lightgray;
}
```

```css
/* Estilo aplicado a todos los elementos pares */
li:nth-child(even) {
  background-color: lightgray;
}
```

```css
/* Estilo aplicado a todos los elementos impares */
li:nth-child(odd) {
  background-color: lightgray;
}
```

```css
/* Estilo aplicado al primer elemento */
li:nth-child(1) {
  font-weight: bold;
}
```

```css
/* Estilo aplicado al segundo elemento */
li:nth-child(2) {
  font-style: italic;
}
```

```css
/* Estilo aplicado a cada tercer elemento, comenzando desde el primer hijo */
li:nth-child(3n + 1) {
  color: red;
}
```

```css
/* Estilo aplicado a cada tercer elemento, comenzando desde el segundo hijo */
li:nth-child(3n + 2) {
  color: blue;
}
```

```css
/* Estilo aplicado a cada tercer elemento, comenzando desde el tercer hijo */
li:nth-child(3n + 3) {
  color: green;
}
```

### Algunas extras que no se mencionaron en la clase:

- :first-child: Aplica estilos al primer hijo de un elemento.

Ejemplo:

```css
/* Estilo para el primer hijo de un elemento */
.parent > *:first-child {
  color: blue;
}

```

- :last-child: Aplica estilos al último hijo de un elemento.

Ejemplo:

```css
/* Estilo para el último hijo de un elemento */
.parent > *:last-child {
  color: blue;
}
```

- :nth-of-type(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos del mismo tipo.

Ejemplo:

```css
/* Estilo para el tercer elemento div */
div:nth-of-type(3) {
  background-color: yellow;
}
```

- :nth-last-child(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos, comenzando desde el último hijo.

Ejemplo:

```css
/* Estilo para el penúltimo hijo de un elemento */
.parent > *:nth-last-child(2) {
  font-weight: bold;
}
```

- :nth-last-of-type(): Aplica estilos a un elemento basado en su posición en relación con sus hermanos del mismo tipo, comenzando desde el último hijo.

Ejemplo:

```css
/* Estilo para el penúltimo elemento div */
div:nth-last-of-type(2) {
  background-color: yellow;
}
```

### BEM (Block Element Modifier)

BEM es una metodología de nomenclatura de clases en CSS que se utiliza para crear estilos CSS escalables y reutilizables. BEM se basa en tres conceptos principales: bloques, elementos y modificadores.

- Bloques: Son componentes independientes y autónomos que pueden ser reutilizados en diferentes contextos.

- Elementos: Son partes de un bloque que no tienen sentido por sí mismos y solo tienen sentido en el contexto del bloque.

- Modificadores: Son variantes de un bloque o un elemento que alteran su apariencia o comportamiento.

Ejemplo de nomenclatura de clases en BEM:

```css
/* Estilo aplicado a un bloque */
.block {
 /* Estilos del bloque */
}

/* Estilo aplicado a un elemento dentro de un bloque */
.block__element {
 /* Estilos del elemento */
}

/* Estilo aplicado a un bloque con un modificador */
.block--modifier {
 /* Estilos del bloque con el modificador */
}
```

```html
<!-- Ejemplo de uso de clases en BEM -->
<div class="block">
 <h1 class="block__title">Título del bloque</h1>
 <p class="block__text">Texto del bloque</p>
 <button class="block__button block__button--primary">Botón del bloque</button>
</div>
```

```css
/* Estilo aplicado a un bloque */
.block {
 /* Estilos del bloque */
}

/* Estilo aplicado a un elemento dentro de un bloque */
.block__title {
 /* Estilos del elemento */
}

/* Estilo aplicado a un elemento dentro de un bloque */

.block__text {
 /* Estilos del elemento */
}

/* Estilo aplicado a un bloque con un modificador */
.block__button {
 /* Estilos del bloque con el modificador */
}

/* Estilo aplicado a un bloque con un modificador */
.block__button--primary {
 /* Estilos del bloque con el modificador */
}
```

### Ventajas de BEM

- Mejora la legibilidad y mantenibilidad del código CSS.

- Facilita la reutilización de estilos y componentes.

- Evita la especificidad excesiva y los conflictos de estilos.

- Proporciona una estructura clara y coherente para los estilos CSS.

### Desventajas de BEM

- Puede generar clases largas y repetitivas en el HTML y el CSS.

- Puede ser difícil de aprender y aplicar para los principiantes.

- Puede ser difícil de mantener y actualizar en proyectos grandes y complejos.

### Recursos de BEM

- [BEM: Block Element Modifier](https://en.bem.info/methodology/css/): Sitio web oficial de BEM con documentación y ejemplos.

- [BEM 101](https://css-tricks.com/bem-101/): Una guía completa de BEM con ejemplos y explicaciones detalladas.

- [BEM Naming Cheat Sheet](https://9elements.com/bem-cheat-sheet/): Una hoja de trucos de BEM con ejemplos y explicaciones.
