# Front-End-Developer-


Introducción

- **HTML**
    
    Son siglas en ingles de HyperText Markup Language o Lenguaje de Marcado de Hipertexto.
    
    ### ¿Para qué sirve?
    
    Nos sirve para estructurar toda nuestra página web, si hacemos la referencia con el cuerpo humano es como el sistema óseo, lo vamos a utilizar para colocar texto, imágenes, botones, videos, etc. Nos da una estructura inicial.
    
    
    - **Motores de renderizado**
    
    Cuando escribimos nuestros archivos HTML y CSS con ciertas etiquetas, selectores, atributos, propiedades, etc, todo eso el navegador no lo entiende y para poder entenderlo cada navegador tiene un motor que le permite entender y hacer visible en pixeles lo que nosotros hemos escrito.
    
    Cada navegador tiene diferentes motores, pero realizan el mismo proceso.


- **Anatomía de un documento HTML y sus elementos**

Antes de empezar a escribir código HTML, debemos conocer la anatomía de un documento y sus elementos.

¿Cuáles son los elementos HTML?
Los elementos son cada una de las partes que conforman un archivo HTML. Su estructura contiene:

Etiquetas: es la representación de un elemento HTML. Se dividen en etiquetas de apertura, representadas por <etiqueta> y etiquetas de cierre, representadas por </etiqueta>.
Contenido: es el texto o elementos encerrados por la etiqueta, este valor es opcional en algunas de ellas.
Anatomía de un elemento HTML
**Qué son atributos HTML**
Los atributos HTML son propiedades en la etiqueta de apertura que manejan el comportamiento del elemento. Su valor está envuelto en comillas.

![](img/frontend_developer06.png) 

**Qué son los elementos vacíos**
Los elementos vacíos son aquellos que únicamente se representan en una etiqueta de apertura. Por ejemplo, la etiqueta de imagen: <img...>.

![](img/frontend_developer08.png) 

Estas etiquetas pueden cerrarse en la misma etiqueta de apertura, utilizando la barra inclinada “/” al final: <img.../>.

**Qué es el anidamiento de elementos**

El anidamiento de elementos HTML consiste en envolver varias etiquetas en otras etiquetas.

Interpreta a cada elemento HTML como una caja donde puedes guardar diferentes elementos u otras cajas. Estas cajas tendrán diferentes tamaños y estarán colocadas junto a otras.

![](img/frontend_developer07.png) 


Aquellas etiquetas que envuelven a otras se las denomina “padres”. Es decir, "#section" es padre de "#h1", "#p", "#ul", y a su vez "#ul" es padre de 3 etiquetas "#li".

Las etiquetas que son el contenido de otras, se las denomina “hijos”. Es decir, las etiquetas "h1", "p", "ul" son hijos de "section", y a su vez las etiquetas "li" son hijos de "ul".

- **Estructura básica de un documento HTML**
La estructura básica de un documento HTML está configurado por las siguientes etiquetas principales:


![](img/frontend_developer09.png) 

Etiqueta Doctype
La etiqueta <!DOCTYPE html> especifica que el archivo se maneje con la versión 5 de HTML.

Etiqueta html
La etiqueta "html" define el elemento raíz de un documento HTML. Todos los demás elementos deben estar contenidos dentro de este elemento raíz. En esta etiqueta se especifica el lenguaje de la página web mediante la propiedad lang.

Etiqueta head
La etiqueta "head" define la metainformación, es decir, toda información que no es contenido como tal de la página web. Por ejemplo, los enlaces a archivos CSS y JavaScript, el título y la imagen que aparecen en la pestaña del navegador. Esto es importante para motores de búsqueda como Google.

Etiqueta body
La etiqueta "body" define el contenido de la página web. Debe ser hijo cercano de "html" y padre de todas las etiquetas HTML, excepto por aquellas que definan metainformación.

- **Comentarios de HTML**
Los comentarios de HTML consiste en señalar algo que se ignorará. Para establecer un comentario HTML se lo envuelve entre <!-- y -->, independiente de la cantidad de líneas.

<!-- Este es un comentario de una línea -->
<!--
Este es un comentario de varias líneas
-->
Desafío: construye la estructura de un documento HTML
Utiliza tu editor Visual Studio Code o la herramienta codi.link. Si utilizas codi.link puedes visualizar toda la página web en la opción “Preview”.

Solución al reto

- **¿Qué es HTML semántico?**

El HTML semántico consiste en que cada elemento tenga su propia etiqueta que lo defina correctamente. Sin utilizar etiquetas muy generales, como -div- o -span-.

El problema con la etiqueta div
La etiqueta div define un bloque genérico de contenido, que no tiene ningún valor semántico. Se utiliza para elementos de diseño como contenedores.

![](img/frontend_developer11.png) 

¿Cuáles son las etiquetas semánticas?
Las etiquetas semánticas para definir una interfaz de una página web son:

"header": define el encabezado de la página (no confundir con "head").
"nav": define una barra de navegación que incluye enlaces.
"section": define una sección de la página.
"footer": define un pie de página o de sección.
"article": define un artículo, el cual puede tener su propio encabezado, navegación, sección o pie de página.
Ahora que ya conoces las etiquetas semánticas, evita el uso excesivo de "div".

![](img/frontend_developer10.png) 

Ventajas de utilizar HTML semántico
Las ventajas de utilizar un HTML semántico son:

Ayuda a tu sitio a ser accesible
Mejora tu posicionamiento (SEO)
Código más claro, legible y mantenible
Ayuda a buscadores (como Google) a encontrar tu página


- **Etiquetas de HTML más usadas**


HTML Reference - A free guide to all HTML elements and attributes.

http://htmlreference.io/


curso-frontend-developer/etiquetas.html at 5108689bdb6599cc92bd9595db28784f9be48704 · platzi/curso-frontend-developer · GitHub

https://github.com/platzi/curso-frontend-developer/blob/5108689bdb6599cc92bd9595db28784f9be48704/curso-1/etiquetas.html


44 etiquetas HTML que debes conocer

https://platzi.com/blog/etiquetas-html-debes-conocer/


- **Anatomía de una declaración CSS: selectores, propiedades y valores**

Antes de empezar a escribir código CSS, debemos conocer la anatomía de una declaración de estilos.

Qué es una declaración de CSS
Una declaración de CSS es un bloque que especifica el conjunto de estilos que se añadirán a un elemento HTML. Su estructura contiene lo siguiente:

Selector: define el elemento o conjunto de elementos a los cuales se añadirán los estilos.
Propiedad: es el nombre del estilo de CSS.
Valor: es el valor que tomará la propiedad.


![](img/frontend_developer10.png)

Qué son comentarios de CSS
Los comentarios de CSS consisten en señalar algo que se ignorará. Para establecer un comentario CSS se lo envuelve entre /* y */, independiente de la cantidad de líneas.


/* Este es un comentario de una línea */
/* 
Este es un comentario de varias líneas
*/

Propiedades iniciales de CSS
Antes de empezar con CSS utilizaremos algunas propiedades de CSS.

color: establece el color del texto de un elemento.
background-color: establece un color de fondo al elemento.
font-size: establece el tamaño de la fuente.
width: establece la anchura de un elemento.
height: establece la altura de un elemento.
Medidas iniciales
Estas son las medidas iniciales que debes conocer para establecer tamaños de elementos o de tipografía:

px: establece una longitud de píxeles.
%: establece un porcentaje con respecto a una medida base.
Profundiza más sobre el tema de medidas en:

Unidades de medida
https://platzi.com/clases/2467-frontend-developer/40844-unidades-de-medida/


- **Tipos de selectores: básicos y combinadores**

El selector define el elemento o conjunto de elementos HTML a los cuales se añadirán estilos. Existen nombres de colores propios de CSS que puedes explorar. A continuación veamos más sobre selectores.
https://htmlcolorcodes.com/es/nombres-de-los-colores/
Cuáles son los selectores básicos
Un selector básico es la mínima expresión CSS para colocar estilos.

selector {
    /* Estilos */
}

![](img/frontend_developer10.png)

1. Selector de tipo
Selecciona todos los elementos que coincidan con el nombre de la etiqueta HTML.

```css
div {
    /* Todos los div en el documento */
}
```

Desafío de selector de tipo
Intenta dar un color de fondo a 10 etiquetas <div> con un solo selector, utiliza la propiedad background-color.

Desafío selector de tipo

Solución al desafío

2. Selector de clase
Selecciona todos los elementos que coincidan con las etiquetas HTML que contengan el atributo class

```html
<!--archivo HTML-->
<div class="card"> Soy una carta </div>
```
Para seleccionar estos elementos, se empieza por un punto . y seguido el valor exacto del atributo class de la etiqueta. Puede ser cualquier valor que desees colocar.

```css
.card {
    /* Todas las etiquetas con la clase "card" */
}
```

Puede existir más de un valor dentro del atributo class separados por espacios.
```html
<!--archivo HTML-->
<div class="card card1"> Soy una carta </div>
<div class="card card2"> Soy una carta </div>
```
```css
.card {
    /* Todas las etiquetas con la clase "card" */
}

.card1 {
    /* Todas las etiquetas con la clase "card1" */
}

.card2 {
    /* Todas las etiquetas con la clase "card2" */
}
```

Desafío de selector de clase
De un conjunto de etiquetas <div> intenta dar un color de fondo a las etiquetas que contengan la clase "card" con un solo selector. Después, intenta dar un color de letra diferente para las etiquetas que contengan "card1" y "card2"

Desafío selector de clase

Solución al desafío

3. Selector de identificador único (id)
Selecciona el único elemento que coincida con la etiqueta HTML que contenga el atributo id. Solo puede existir un valor id para todo el documento.
```html
<!--archivo HTML-->
<button id="eliminar"> Eliminar  </button>
```

Para seleccionar el elemento, se empieza por el símbolo de hashtag # y seguido el valor exacto del atributo id de la etiqueta. Puede ser cualquier valor que desees colocar.
```css
/* archivo CSS */
#eliminar {
    /* La única etiqueta con el id "eliminar" */
}
```

Desafío de selector de ID
De un conjunto de etiquetas <button>, existe un único botón para eliminar. Intenta colocar un color de fondo rojo a este elemento.

Desafío selector de ID

Solución al desafío

4. Selector de atributo
Selecciona los elementos que coincidan con la etiqueta HTML que contenga el atributo y valor especificado.

```html
<!--archivo HTML-->
<a href="https://platzi.com"> Ir a Platzi </a>
```

Para seleccionar los elementos, se empieza por el nombre de la etiqueta, seguido de corchetes [] que contiene el atributo y valor especificado.

```css
/* archivo CSS */
a[href=""https://platzi.com"] {
    /* Todas las etiquetas <a> con una propiedad href con valor "https://platzi.com" */
}
```

Desafío de selector de atributo
Intenta colocar un color de fondo a las etiquetas <a> que contengan el atributo href con el valor de "https://platzi.com".

Desafío selector de atributo

Solución al desafío

5. Selector universal
Selecciona todos los elementos del documento mediante un asterisco *.
```css
* {
    /* Todos los elementos */
}
```
Desafío de selector universal
Intenta colocar un color de fondo a todos los elementos del documento.

Desafío selector universal

Solución al desafío

Cuáles son los selectores combinadores
Un selector combinador es la unión de dos o más selectores básicos.

```css
selector1 selector2 selector3 {
    /* Estilos */
}
```

1. Combinador de descendientes
Selecciona todos los elementos del selector de la derecha que son hijos del selector de la izquierda, independientemente de la profundidad. Estos selectores están separados por un espacio.

```css
padre hijos {
    /* Todos los hijos del padre */
}

div p{
    /* Todos los hijos <p> de <div>*/
}

.container img{
    /* Todos los hijos <img> de la clase "container"*/
}

```

Desafío del combinador de descendientes
Intenta colocar un color de letra a todas las etiquetas <li> que son hijos de la clase "container".

Desafío combinador de descendientes

Solución al desafío

2. Combinador de hijo directo
Selecciona todos los elementos del selector de la derecha que son hijos directos del selector de la izquierda. Estos selectores están separados por >.

```css
padre > hijos_directos {
    /* Todos los hijos directos del padre */
}

div > p{
    /* Todos los hijos directos <p> de <div>*/
}

.container > img{
    /* Todos los hijos directos <img> de la clase "container"*/
}
```

Desafío de combinador de hijo directo
Intenta colocar un color de letra a todos las etiquetas ```<p>``` que son hijos directos de la clase ```<container>```.

Desafío combinador de hijo directo

Solución al desafío

3. Combinador de elemento adyacente
Selecciona todos los elementos del selector de la derecha que están adyacente al selector de la izquierda. Estos selectores están separados por +.

```css
elemento + adyacente {
    /* Elementos adyacentes */
}

div + p{
    /* Todos los <p> adyacentes a <div>*/
}

.container + img{
    /* Todos los <img> adyacentes a la clase "container"*/
}
```

Adyacente significa que comparten el mismo padre y está situado inmediatamente hacia abajo de otro elemento. Por ejemplo, en el siguiente código, ```html<div>``` está adyacente a ```html<h1>``` y ```html<p>``` está adyacente a ```html<div>```. Sin embargo, ```html<h1>``` no está adyacente a ```html<div>``` y ```html<div>``` no está adyacente a <p>.

```html
<!--archivo HTML -->
<h1>Soy un título </h1>
<div>Soy un div</div>
<p>Soy un párrafo</p>
```

Desafío de combinador de elemento adyacente
Intenta colocar un color de letra a todos las etiquetas <p> que están adyacente a las etiquetas <div>.

Desafío combinador de elemento adyacente

```css
elemento ~ hermanos {
    /* Elementos hermanos */
}

div ~ p{
    /* Todos los <p> hermanos de <div>*/
}

.container ~ img{
    /* Todos los <img> hermanos de la clase "container"*/
}
```

Solución al desafío

4. Combinador general de hermanos
Selecciona todos los elementos del selector de la derecha que son hermanos del selector de la izquierda. Estos selectores están separados por ~.


Hermanos significa que comparten el mismo padre y están situados hacia abajo de otro elemento. Por ejemplo, en el siguiente código, ```<div>``` y ```<p>``` son hermanos de ```<h1>```, pero ```<h1>``` no es hermano de ```<div>``` y ```<p>```.

```html
<!--archivo HTML -->
<h1>Soy un título </h1>
<div>Soy un div</div>
<p>Soy un párrafo</p>
```
