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
<etiqueta>
  Contenido
</etiqueta>
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
<hr> <!-- Línea horizontal -->
```

### Atributos de las etiquetas

Todos los elementos de HTML pueden tener atributos. Los atributos proporcionan información adicional sobre los elementos HTML.

```html
<etiqueta atributo="valor">
  Contenido
</etiqueta>
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

    <img src="imagen.jpg" alt="Texto alternativo">

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
    <br>: para insertar un salto de línea.
    <hr>: para insertar una línea horizontal.
    <img>: para insertar una imagen.
    <input>: para crear un campo de entrada de datos, como un cuadro de texto o un botón.
    <meta>: para agregar información meta a la página, como descripción y palabras clave.
    <link>: para vincular la página a una hoja de estilo CSS o a otro recurso externo.
    <area>: para definir una región de un mapa de imagen.
    <base>: para establecer la URL base para todas las URL relativas dentro de una página.
    <col>: para definir las propiedades de estilo para una columna de una tabla.
    <embed>: para incrustar contenido multimedia, como audio o video.
    <param>: para establecer parámetros para un objeto multimedia en la página.
    <source>: para especificar la fuente de un elemento multimedia.
    
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

2- target: Es un atributo opcional que especifica dónde abrir el recurso enlazado. Los valores posibles son _blank,_self, _parent,_top, o un nombre de ventana o marco.

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
<img src="imagen.jpg" alt="Texto alternativo">
```

2- alt: Es un atributo opcional que proporciona un texto alternativo para la imagen. Este texto se muestra si la imagen no se puede cargar o si el usuario navega con un lector de pantalla.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo">
```

3- width: Es un atributo opcional que especifica el ancho de la imagen en píxeles.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" width="300">
```

4- height: Es un atributo opcional que especifica la altura de la imagen en píxeles.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" height="200">
```

5- loading: Es un atributo opcional que especifica cómo se debe cargar la imagen. Los valores posibles son auto, eager, lazy, y otros.

Ejemplo:

```html
<img src="imagen.jpg" alt="Texto alternativo" loading="lazy">
```

#### Favicon

El favicon es un icono que se muestra en la pestaña del navegador y en la lista de marcadores. Para agregar un favicon a tu sitio web, puedes utilizar la etiqueta <link> en el elemento <head> del documento HTML. El atributo rel especifica la relación entre el documento actual y el recurso enlazado, y el atributo href especifica la URL del icono. Aquí tienes un ejemplo de cómo agregar un favicon a tu sitio web:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
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
<iframe src="pagina.html" width="300" height="200" title="Título del marco"></iframe>
```

2- width: Es un atributo opcional que especifica el ancho del marco en píxeles.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco"></iframe>
```

3- height: Es un atributo opcional que especifica la altura del marco en píxeles.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco"></iframe>
```

4- title: Es un atributo opcional que proporciona un título para el marco. Este texto se muestra como una información sobre herramientas cuando el usuario coloca el cursor sobre el marco.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco"></iframe>
```

5- loading: Es un atributo opcional que especifica cómo se debe cargar el marco. Los valores posibles son auto, eager, lazy, y otros.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco" loading="lazy"></iframe>
```

6- frameborder: Es un atributo opcional que especifica si el marco debe tener un borde. Los valores posibles son 0 y 1.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco" frameborder="0"></iframe>
```

5- allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share":  Este atributo controla qué acciones están permitidas dentro del iframe. En este caso, se permiten varias acciones relacionadas con el control de reproducción de video, la escritura en el portapapeles y el uso de sensores del dispositivo, entre otras.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
```

6- allowfullscreen: Es un atributo opcional que especifica si el marco debe permitir la visualización en pantalla completa.

Ejemplo:

```html
<iframe src="pagina.html" width="300" height="200" title="Título del marco" allowfullscreen></iframe>
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
<form action="/procesar.php">
  ...
</form>
```

2- method: Es un atributo opcional que especifica el método HTTP que se utilizará para enviar los datos del formulario. Los valores posibles son get y post.

Ejemplo:

```html
<form action="/procesar.php" method="post">
  ...
</form>
```

3- target: Es un atributo opcional que especifica dónde se debe mostrar el resultado del procesamiento del formulario. Los valores posibles son _blank,_self, _parent,_top, o un nombre de ventana o marco.

Ejemplo:

```html
<form action="/procesar.php" method="post" target="_blank">
  ...
</form>

4- autocomplete: Es un atributo opcional que especifica si el navegador debe completar automáticamente los campos del formulario.

Ejemplo:

```html
<form action="/procesar.php" method="post" autocomplete="on">
  ...
</form>

5- novalidate: Es un atributo opcional que especifica que el formulario no debe ser validado antes de enviar los datos.

Ejemplo:

```html
<form action="/procesar.php" method="post" novalidate>
  ...
</form>
```

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
<form action="/procesar.php" method="post" accept-charset="UTF-8">
  ...
</form>
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
<form action="/procesar.php" method="post" name="formulario">
  ...
</form>
```

#### Formulario Básico

La etiqueta form se utiliza para crear un formulario en un documento HTML. El atributo action especifica la URL del script que procesará los datos del formulario, y el atributo method especifica el método HTTP que se utilizará para enviar los datos del formulario. Aquí tienes un ejemplo de cómo crear un formulario básico:

```html
<form action="/procesar.php" method="post">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre">
  <label for="email">Correo Electrónico:</label>
  <input type="email" id="email" name="email">
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
<input type="text" name="nombre">
```

2- email: Crea un campo de texto para introducir una dirección de correo electrónico.

Ejemplo:

```html
<input type="email" name="email">
```

3- password: Crea un campo de texto para introducir una contraseña.

Ejemplo:

```html
<input type="password" name="contrasena">
```

4- checkbox: Crea una casilla de verificación que el usuario puede marcar o desmarcar.

Ejemplo:

```html
<input type="checkbox" name="suscribirse" value="1">
```

5- radio: Crea un botón de opción que el usuario puede seleccionar.

Ejemplo:

```html
<input type="radio" name="genero" value="masculino">
<input type="radio" name="genero" value="femenino">
```

6- file: Crea un control de entrada para seleccionar un archivo para cargar.

Ejemplo:

```html
<input type="file" name="archivo">
```

7- submit: Crea un botón para enviar el formulario.

Ejemplo:

```html
<input type="submit" value="Enviar">
```

8- reset: Crea un botón para restablecer el formulario a su estado inicial.

Ejemplo:

```html
<input type="reset" value="Restablecer">
```

9- hidden: Crea un campo de entrada oculto que no se muestra en el formulario.

Ejemplo:

```html
<input type="hidden" name="id" value="123">
```

#### Atributos de entrada de datos

La etiqueta input puede tener varios atributos opcionales que controlan el aspecto y el comportamiento del control de entrada. Aquí tienes una descripción de algunos de los atributos más comunes:

1- placeholder: Es un atributo opcional que proporciona un texto de marcador de posición para el control de entrada. Este texto se muestra en el control de entrada cuando está vacío.

Ejemplo:

```html
<input type="text" name="nombre" placeholder="Nombre">
```

2- required: Es un atributo opcional que especifica que el control de entrada es obligatorio. Si el usuario intenta enviar el formulario sin completar el control de entrada, se mostrará un mensaje de error.

Ejemplo:

```html
<input type="email" name="email" required>
```

3- disabled: Es un atributo opcional que especifica que el control de entrada está deshabilitado. Esto significa que el usuario no puede interactuar con el control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" disabled>
```

4- readonly: Es un atributo opcional que especifica que el control de entrada es de solo lectura. Esto significa que el usuario puede ver el valor del control de entrada, pero no puede cambiarlo.

Ejemplo:

```html
<input type="text" name="nombre" value="Humberto" readonly>
```

5- autofocus: Es un atributo opcional que especifica que el control de entrada debe recibir el enfoque automáticamente cuando se carga la página.

Ejemplo:

```html
<input type="text" name="nombre" autofocus>
```

6- autocomplete: Es un atributo opcional que especifica si el control de entrada debe permitir que el navegador complete automáticamente el valor del control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" autocomplete="on">
```

7- pattern: Es un atributo opcional que especifica un patrón que debe coincidir con el valor del control de entrada. Si el valor del control de entrada no coincide con el patrón, se mostrará un mensaje de error.

Ejemplo:

```html
<input type="text" name="codigo" pattern="[A-Za-z]{3}\d{3}">
```

8- min: Es un atributo opcional que especifica el valor mínimo que se puede introducir en el control de entrada.

Ejemplo:

```html
<input type="number" name="edad" min="18">
```

9- max: Es un atributo opcional que especifica el valor máximo que se puede introducir en el control de entrada.

Ejemplo:

```html
<input type="number" name="edad" max="100">
```

10- step: Es un atributo opcional que especifica el tamaño de los pasos que se pueden introducir en el control de entrada.

Ejemplo:

```html
<input type="number" name="edad" step="5">
```

11- list: Es un atributo opcional que especifica el ID de un elemento datalist que proporciona una lista de opciones para el control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" list="nombres">
<datalist id="nombres">
  <option value="Humberto">
  <option value="Juan">
  <option value="María">
</datalist>

12- multiple: Es un atributo opcional que especifica que el control de entrada puede aceptar múltiples valores.

Ejemplo:

```html
<input type="file" name="archivos" multiple>
```

13- accept: Es un atributo opcional que especifica los tipos de archivos que se pueden seleccionar en el control de entrada.

Ejemplo:

```html
<input type="file" name="archivos" accept="image/*">
```

14- value: Es un atributo opcional que especifica el valor inicial del control de entrada.

Ejemplo:

```html
<input type="text" name="nombre" value="Humberto">
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
<input type="text" id="nombre" name="nombre">
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
  <input type="text" id="nombre" name="nombre">
  <label for="email">Correo Electrónico:</label>
  <input type="email" id="email" name="email">
  <label for="telefono">Teléfono:</label>
  <input type="tel" id="telefono" name="telefono">
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

```html
<table border="1">
  ...
</table>

2- cellpadding: Es un atributo opcional que especifica el espacio entre el borde de la celda y su contenido. El valor del atributo es un número entero que representa el espacio en píxeles.

Ejemplo:

```html
<table cellpadding="10">
  ...
</table>
```

3- cellspacing: Es un atributo opcional que especifica el espacio entre las celdas de la tabla. El valor del atributo es un número entero que representa el espacio en píxeles.

Ejemplo:

```html
<table cellspacing="5">
  ...
</table>

4- width: Es un atributo opcional que especifica el ancho de la tabla. El valor del atributo es un número entero que representa el ancho en píxeles.

Ejemplo:

```html
<table width="300">
  ...
</table>
```

5- align: Es un atributo opcional que especifica la alineación horizontal de la tabla. Los valores posibles son left, center, y right.

Ejemplo:

```html
<table align="center">
  ...
</table>

6- bgcolor: Es un atributo opcional que especifica el color de fondo de la tabla. El valor del atributo es un nombre de color o un código hexadecimal.

Ejemplo:

```html
<table bgcolor="#f0f0f0">
  ...
</table>
```
