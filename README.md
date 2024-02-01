# MP4UF1_APUNTES
Documentacion de Apuntes de le teoria de la Unidad Formativa

## GITHUB
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

<hr>
<a href="http://www.google.com" alt="Dirige a google" target="_blank">Esto es un enlace a Google</a>

## ENLACES
Para los enlaces hay que poner una ruta relativa que empiece por ../
Si empieza por file no se podra ver en el pages 



## TABLAS
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
El css es una hoja de estilo que sirve para darle estilo y diseño a uno o varios documentos html.

Los estilos se pueden asociar de diferentes maneras a los elementos HTML dado que estos pueden estar ubicados en diferentes sitios como por ejemplo:

En la cabecera del documento:
Aquí lo que podemos ver es como todas las etiquetas <p> tendran un color rojo y estará el texto alineado al centro.

          <!DOCTYPE html>
          <html lang="ca">
             <head>
                <!-- ... →
               <style> 
                  p { 
                    text-align:center; 
                    color:red 
                  } 
                </style>
             </head>
             <body>

En la propia etiqueta:
Aquí lo que podemos ver es como dentro de la etiqueta <p> hemos añadido un atributo para dar estilo a esa etiqueta style="" poniendo dentro de las comillas el estilo que le queremos dar al texto.

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

## Diseño responsive
El diseño web responsive es una técnica de diseño web que busca la correcta visualización de una misma página en distintos dispositivos. Desde ordenadores de escritorio a móviles.

Se trata de redimensionar y colocar los elementos de la web de forma que se adapten al ancho de cada dispositivo permitiendo una correcta visualización y una mejor experiencia de usuario.

Comandos diseño responsive
El primer comando a mostrar y uno de los más importantes es el display, que sirve para colocar los div como si fueran celdas o bloques.

## Ejemplo.

.flex {
    display: flex;
}
Otro comando importante en un diseño responsive es el comando float, que sirve para colocar en un lado u otro del contenedor.

## Ejemplo.

.left {
    float: left;
}

## Mediaquery
Las mediaqueries permiten aplicar estilos CSS según el tipo de dispositivo, lo cúal va por el tamaño o resolución de la pantalla o del ancho del viewport del navegador.

## Ejemplo.

@media only screen and (max-width: 700px){
    img{
        width: 600px;
    }
    .column2{
        width: 100%;
    }
}

## DISEÑO RESPONSIVE
Aqui tambien implementamos CSS, aunque aqui es mas para poner medidas, ocultar elementos...
El diseño responsive, es mucho mas util de lo que parece, ya que hace que no importe desde donde ves la pagina web, ya que te ajusta automaticamente las medidas y la resolución. Cabe destacar, que en Diseño responsive, el uso de etiquetas como section y como div, es bastante frecuente.
También es bastante frecuente usar comandos, como los que te voy a mostrar a continuación:

FLOAT
Este comando, se usa para alinear el elemento hacia la derecha o hacia la izquierda, obviamente sin modificar lo de alrededor, es decir que se ajusta automaticamente:

#right{ float: right; }

DISPLAY
Este comando podemos decir que "transforma" los DIV en celdas:

.flex{ display: flex; }

BOX-SIZING
Este comando se usa para modificar tanto borde y ancho y ajusta la medida al tamaño del contenido de la pagina:

*{ box-sizing: border-box;
}

FLEX-DIRECTION
Comando bastante util, y esque su funcionalidad es que mueve los elementos de la pagina, en base hacia donde movamos nosotros la pantalla

.box { display: flex; flex-direction: column; }

ALIGN
Como podemos tener en aplicaciones como Word, aqui también tenemos, y es el:

.flex{ align-items: center; }

Su principal funcion, es alinear los elementos a donde tu le pidas

JUSTIFY-CONTENT
Otro comando que nos podemos encontrar en Word, y nada diferente, sirve para justificar el contenido de la pagina web, poniendole un start, es para que lo justifique al borde inicial:

.box{ justify-content: start; }

IMAGENES
Esta parte es importante si queremos que las imagenes se ajusten automaticamente al ancho de la pagina y decirle que altura queremos que tenga:

header{ height: 100vh; background-image: url(ruta donde tenemos al imagen); background-size: cover; background-position: center; background-attachment: fixed; }

El background image, como su nombre dice, es para poner una imagen de fondo.
El background size cover, es para que la imagen de fondo de ajuste automaticamente al tamaño
El background position center tambien como su propio nombre indica, es para que el fondo esté centrado al contenedor
El background attachment fixed, significa que la imagen de fondo, se queda fijada en la posicion, haciendo que por mas que nos movamos, el fondo se quedará fijo en su puesto
