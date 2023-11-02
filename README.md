# MP4UF1_APUNTES
Documentacion de Apuntes de le teoria de la Unidad Formativa

## Primer Capitulo: Markdown

Este texto esta en *cursiva*.
Este texto esta en _cursiva_.
Este texto esta en **negrita**.
Este texto esta en __negrita__.
Este texto esta en **_cursiva y negrita_**.


1. Primera opcion de menu
2. Segunda opcion de menu
3. Tercera opción de menu

* Primera opcion de lista desordenada
* Segunda opcion de lista desordenada
- Tercera opcion de lista desordenada
    1. Primer submenu
    2. Segundo submenu
- Cuarta opcion de lista desordenada
    * Tercer submenu
    * Cuarto submenu
+ Quinto opcion de lista desordenada
+ Sexto opcion de lista desordenada

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un parrafo<p>
    </body>
</html>
```
[Esto es un enlace](http://joan23.fje.edu "enlace a la web del cole")

|Primera Col.| Segunda Col.|3 Col|
|---------------|:----------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo cebra|gris|blanco
|Clase|ASIX1|M4|

## CAPITULO 2: HTML
<p>La etiqueta p sirve para crear un parrafo </p>
<p>Para insertar una imagen se utiliza la etiqueta img y href poniendo en enlace de la imagen.</p>
<p>Para insertar un salto de linea la etiqueta es br</p>
<p>Todos los documentos HTML tienen dos bloques: Head y body; todo lo que se va a ver en la pagina sera escrito en el body</p>
<h3>Creacion de listas</h3>
A partir de aqui explico lo que es una lista
<p>Para la creacion de listas utilizaremos las etiquetas li y ol </p>
<p>Para crear un sub lista hay que añadir dentro de la etiquela li un ul </p>
<ol>
    <li>Primer elemento</li>
    <ul>
        <li>Primer elemento nivel 2</li>
        <li>Primer elemento nivel 2</li>
        <li>Primer elemento nivel 2</li>
    </ul>
    <li>Segun elemento</li>
    <li>Tercer elemento</li>
</ol>
<ul>
    <li>Primer elemento</li>
    <li>Segun elemento</li>
    <li>Tercer elemento</li>
</ul>
<br>
Ejemplo de enlaces
<hr>
<a href="http://www.google.com" alt="Dirige a google" target="_blank"></a>

ENLACES
Para los enlaces hay que poner una ruta relativa que empiece por ../
Si empieza por file no se podra ver en el pages 
Etiqueta <table>: Esta etiqueta se utiliza para definir la tabla en HTML. Debe envolver todo el contenido de la tabla.
html


TABLAS
<table>
  <!-- Aquí van las filas y celdas de la tabla -->
</table>
Etiqueta <tr>: Esta etiqueta se utiliza para definir una fila en la tabla. Cada fila contendrá una serie de celdas.

<table>
  <tr>
    <!-- Aquí van las celdas de la primera fila -->
  </tr>
  <tr>
    <!-- Aquí van las celdas de la segunda fila -->
  </tr>
</table>
Etiqueta <th>: Esta etiqueta se utiliza para definir las celdas de encabezado de la tabla. Se utilizan típicamente en la primera fila o fila de encabezado de la tabla para etiquetar las columnas.

<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
  </tr>
  <tr>
    <!-- Aquí van las celdas de datos -->
  </tr>
</table>
Etiqueta <td>: Esta etiqueta se utiliza para definir las celdas de datos en la tabla. Se utilizan para mostrar la información real en la tabla.

<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
  </tr>
  <tr>
    <td>Dato 1</td>
    <td>Dato 2</td>
  </tr>
</table>
Aquí tienes un ejemplo de una tabla HTML completa con varias filas y columnas:

<table>
  <tr>
    <th>Nombre</th>
    <th>Edad</th>
  </tr>
  <tr>
    <td>Juan</td>
    <td>25</td>
  </tr>
  <tr>
    <td>María</td>
    <td>30</td>
  </tr>
</table>
Puedes personalizar la apariencia de las tablas utilizando CSS para definir estilos, bordes, colores y más. Las tablas son una forma efectiva de mostrar datos en una página web de manera organizada y estructurada.