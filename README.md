# Desarrollo Web

En este repositorio se encuentran los ejercicios y proyectos realizados en el curso de Desarrollo Web de Coderhouse.

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

### Tipos de elementos HTML (bloque e inline):

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
    <h1>Encabezado de nivel 1</h1>
    <h2>Encabezado de nivel 2</h2>
    <h3>Encabezado de nivel 3</h3>
    <h4>Encabezado de nivel 4</h4>
    <h5>Encabezado de nivel 5</h5>
    <h6>Encabezado de nivel 6</h6>
    <p>Esto es un párrafo</p>
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
  </body>
</html>
