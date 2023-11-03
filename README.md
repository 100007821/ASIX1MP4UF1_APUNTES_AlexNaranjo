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

#ENLACES
Para los enlaces hay que poner una ruta relativa que empiece por ../
Si empieza por file no se podra ver en el pages 

GITHUB
Git clone:
Propósito: Este comando se utiliza para clonar (copiar) un repositorio Git existente desde un servidor remoto, como GitHub, GitLab o Bitbucket, a tu computadora local.
Uso: Debes proporcionar la URL del repositorio que deseas clonar, como se mencionó en la respuesta anterior.


Git add:
Propósito: Se utiliza para agregar cambios realizados en tus archivos locales al área de preparación (staging area) en Git. Esto indica a Git qué cambios deseas incluir en el próximo commit.
Uso: Puedes especificar archivos individuales o patrones de archivos. Por ejemplo, para agregar todos los cambios, puedes usar git add ., y para agregar un archivo específico, puedes usar git add nombre-del-archivo.


Git commit:
Propósito: Este comando se usa para crear un nuevo commit (instantánea de los cambios) con los archivos que has agregado previamente al área de preparación. Debes proporcionar un mensaje descriptivo para el commit que explique los cambios realizados.

Git push:
Propósito: Una vez que has hecho commits en tu repositorio local, puedes usar este comando para enviar esos commits al repositorio remoto en GitHub u otro servicio similar. Esto actualiza el repositorio remoto con tus cambios.


TABLAS
table
   Aquí van las filas y celdas de la tabla 
</table>
Etiqueta tr: Esta etiqueta se utiliza para definir una fila en la tabla. Cada fila contendrá una serie de celdas.

<table>
  <tr>
   Aquí van las celdas de la primera fila 
  </tr>
  <tr>
    Aquí van las celdas de la segunda fila 
  </tr>
</table>
Etiqueta th: Esta etiqueta se utiliza para definir las celdas de encabezado de la tabla. Se utilizan típicamente en la primera fila o fila de encabezado de la tabla para etiquetar las columnas.

<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
  </tr>
  <tr>
    Aquí van las celdas de datos 
  </tr>
</table>
Etiqueta td: Esta etiqueta se utiliza para definir las celdas de datos en la tabla. Se utilizan para mostrar la información real en la tabla.

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


## ESTILOS CSS
Son un conjunto de reglas y propiedades que se utilizan para controlar la presentación y el aspecto visual de elementos HTML en una página web. Los estilos CSS permiten definir cómo se deben mostrar elementos como texto, imágenes, enlaces, márgenes, colores, tamaños de fuente, espaciado y otros aspectos visuales en una página web.

## Etiquetas mas utilizadas
Color: Esta etiqueta se utiliza para definir el color del texto de un elemento. Puedes especificar el color en diversos formatos, como nombres de colores, códigos hexadecimales o valores RGB.

Font-family: Controla la fuente o tipo de letra que se aplicará al texto de un elemento.

Font-size: Determina el tamaño de la fuente del texto en un elemento.

Font-weight: Permite especificar el grosor o la negrita de la fuente.

Text-align: Define la alineación del texto dentro de un elemento, como "left" (izquierda), "center" (centro) o "right" (derecha).

Background-color: Establece el color de fondo de un elemento, como un div o una sección.

Margin y padding: Estas etiquetas se utilizan para controlar los márgenes y el espacio interior (relleno) alrededor de un elemento, respectivamente. Puedes especificar valores para la parte superior, derecha, inferior y izquierda.

Border: Define las propiedades del borde de un elemento, como su grosor, estilo y color.

Width y height: Estas etiquetas permiten definir el ancho y la altura de un elemento.

<p>Esto es una <span style="color: blue;">frase en color azul</span> utilizando CSS en HTML.</p>
