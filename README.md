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

Etiquetas: es la representación de un elemento HTML. Se dividen en etiquetas de apertura, representadas por ```<etiqueta>``` y etiquetas de cierre, representadas por ```</etiqueta>```.
Contenido: es el texto o elementos encerrados por la etiqueta, este valor es opcional en algunas de ellas.
Anatomía de un elemento HTML
**Qué son atributos HTML**
Los atributos HTML son propiedades en la etiqueta de apertura que manejan el comportamiento del elemento. Su valor está envuelto en comillas.

![](img/frontend_developer06.png) 

**Qué son los elementos vacíos**
Los elementos vacíos son aquellos que únicamente se representan en una etiqueta de apertura. Por ejemplo, la etiqueta de imagen: ```<img...>```

![](img/frontend_developer08.png) 

Estas etiquetas pueden cerrarse en la misma etiqueta de apertura, utilizando la barra inclinada “/” al final: ```<img.../>```.

**Qué es el anidamiento de elementos**

El anidamiento de elementos HTML consiste en envolver varias etiquetas en otras etiquetas.

Interpreta a cada elemento HTML como una caja donde puedes guardar diferentes elementos u otras cajas. Estas cajas tendrán diferentes tamaños y estarán colocadas junto a otras.

![](img/frontend_developer07.png) 


Aquellas etiquetas que envuelven a otras se las denomina “padres”. Es decir, ```<section>``` es padre de ```<h1>```, ```<p>```, ```<ul>```, y a su vez ```<ul>``` es padre de 3 etiquetas ```<li>```

Las etiquetas que son el contenido de otras, se las denomina “hijos”. Es decir, las etiquetas ```<h1>```, ```<p>```, ```<ul>``` son hijos de ```<section>```, y a su vez las etiquetas ```<li>``` son hijos de ```<ul>```.

- **Estructura básica de un documento HTML**
La estructura básica de un documento HTML está configurado por las siguientes etiquetas principales:


![](img/frontend_developer09.png) 

Etiqueta Doctype
La etiqueta ```<!DOCTYPE html>``` especifica que el archivo se maneje con la versión 5 de HTML.

Etiqueta html
La etiqueta ```<html>``` define el elemento raíz de un documento HTML. Todos los demás elementos deben estar contenidos dentro de este elemento raíz. En esta etiqueta se especifica el lenguaje de la página web mediante la propiedad lang.

Etiqueta head
La etiqueta ```<head>``` define la metainformación, es decir, toda información que no es contenido como tal de la página web. Por ejemplo, los enlaces a archivos CSS y JavaScript, el título y la imagen que aparecen en la pestaña del navegador. Esto es importante para motores de búsqueda como Google.

Etiqueta body
La etiqueta ```<body>``` define el contenido de la página web. Debe ser hijo cercano de "html" y padre de todas las etiquetas HTML, excepto por aquellas que definan metainformación.

- **Comentarios de HTML**
Los comentarios de HTML consiste en señalar algo que se ignorará. Para establecer un comentario HTML se lo envuelve entre <!-- y -->, independiente de la cantidad de líneas.

```html
<!-- Este es un comentario de una línea -->
<!--
Este es un comentario de varias líneas
-->
```
Desafío: construye la estructura de un documento HTML
Utiliza tu editor Visual Studio Code o la herramienta codi.link. Si utilizas codi.link puedes visualizar toda la página web en la opción “Preview”.

Solución al reto

- **¿Qué es HTML semántico?**

El HTML semántico consiste en que cada elemento tenga su propia etiqueta que lo defina correctamente. Sin utilizar etiquetas muy generales, como ```<div>``` o ```<span>```

El problema con la etiqueta div
La etiqueta div define un bloque genérico de contenido, que no tiene ningún valor semántico. Se utiliza para elementos de diseño como contenedores.

![](img/frontend_developer11.png) 

¿Cuáles son las etiquetas semánticas?
Las etiquetas semánticas para definir una interfaz de una página web son:

```<header>```: define el encabezado de la página (no confundir con ```<head>```).
```<nav>```: define una barra de navegación que incluye enlaces.
```<section>```: define una sección de la página.
```<footer>```: define un pie de página o de sección.
```<article>```: define un artículo, el cual puede tener su propio encabezado, navegación, sección o pie de página.
Ahora que ya conoces las etiquetas semánticas, evita el uso excesivo de ```<div>```.

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

```css
/* Este es un comentario de una línea */
/* 
Este es un comentario de varias líneas
*/
```
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


- **selectores: básicos y combinadores**

El selector define el elemento o conjunto de elementos HTML a los cuales se añadirán estilos. Existen nombres de colores propios de CSS que puedes explorar. A continuación veamos más sobre selectores.
https://htmlcolorcodes.com/es/nombres-de-los-colores/
Cuáles son los selectores básicos
Un selector básico es la mínima expresión CSS para colocar estilos.
```css
selector {
    /* Estilos */
}
```
![](img/frontend_developer14.png)

1. Selector de tipo
Selecciona todos los elementos que coincidan con el nombre de la etiqueta HTML.

```css
div {
    /* Todos los div en el documento */
}
```

Desafío de selector de tipo
Intenta dar un color de fondo a 10 etiquetas ```<div>``` con un solo selector, utiliza la propiedad background-color.

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
De un conjunto de etiquetas ```<div>``` intenta dar un color de fondo a las etiquetas que contengan la clase "card" con un solo selector. Después, intenta dar un color de letra diferente para las etiquetas que contengan "card1" y "card2"

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
![](img/frontend_developer15.png)

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
Intenta colocar un color de letra a todas las etiquetas ```<li>``` que son hijos de la clase ```<container>```.

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
**Tipos de selectores: pseudoclases y pseudoelementos**

![](img/pseudoclases-elementos.png)

Existen otros tipos de selectores, además de los selectores básicos y combinadores, capaces de cambiar un estado o añadir algo más al elemento. Estos son denominados pseudoclases y pseudoelementos.

https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes#indice_de_las_pseudo-clases_est%C3%A1ndar
Cuáles son las pseudoclases
Una pseudoclase define el estilo de un estado especial de un elemento.

Índice de pseudo-clases estándar.
Sintaxis
```css
selector : pseudoclase { 
    propiedad: valor;
}
```

:hover
Representa el estado en el cual el cursor está encima del elemento.
Ejemplo: https://codi.link/PGRpdj5TZcOxw6FsYW1lPC9kaXY+%7CZGl2IHsNCiAgZm9udC1zaXplOiAzcmVtOw0KICBjdXJzb3I6IHBvaW50ZXI7DQp9DQoNCmRpdjpob3ZlciB7DQogIGNvbG9yOiByZWQ7DQp9%7C

:active
Representa el estado de un elemento que no ha sido visitado.
Ejemplo
https://codi.link/PGEgaHJlZj0iIyI+Q2xpY2tlYW1lPC9hPg==%7CYSB7DQogIGZvbnQtc2l6ZTogM3JlbTsNCn0NCg0KYTpsaW5rIHsNCiAgY29sb3I6IHJlZDsNCn0=%7C

:visited
Representa el estado de un elemento que ya ha sido visitado.

Ejemplo https://codi.link/PGEgaHJlZj0iIyI+Q2xpY2tlYW1lPC9hPg==%7CYSB7DQogIGZvbnQtc2l6ZTogM3JlbTsNCn0NCg0KYTp2aXNpdGVkIHsNCiAgY29sb3I6IHJlZDsNCn0=%7C

:not()
Representa el estado en el cual no coinciden los selectores que se indiquen.
ejemplo: https://codi.link/PGRpdj5BenVsPC9kaXY+DQo8ZGl2PkF6dWw8L2Rpdj4NCjxkaXYgY2xhc3M9Im5lZ3JvIj5OZWdybzwvZGl2Pg0KPGRpdj5BenVsPC9kaXY+DQo8ZGl2PkF6dWw8L2Rpdj4=%7CZGl2IHsNCiAgZm9udC1zaXplOiAzcmVtOw0KfQ0KDQpkaXY6bm90KC5uZWdybykgew0KICBjb2xvcjogYmx1ZTsNCn0=%7C

:nth-child()
Representa el estado en el cual coinciden los hijos del elemento según el valor indicado.

Valores de palabras clave:

odd: los elementos hijos en posiciones impares.
even: los elementos hijos en posiciones pares.
Fórmula matemática: An+B donde A y B son números enteros.

Ejemplo: https://codi.link/PGRpdj4xIE5lZ3JvPC9kaXY+DQo8ZGl2PjIgQXp1bDwvZGl2Pg0KPGRpdj4zIE5lZ3JvPC9kaXY+DQo8ZGl2PjQgTmVncm88L2Rpdj4NCjxkaXY+NSBOZWdybzwvZGl2Pg==%7CZGl2IHsNCiAgZm9udC1zaXplOiAzcmVtOw0KfQ0KDQpkaXY6bnRoLWNoaWxkKDIpIHsNCiAgY29sb3I6IGJsdWU7DQp9%7C

Cuáles son los pseudoselementos
Un pseudoelemento define el estilo de una parte específica de un elemento.
Listas de pseudoelementos https://developer.mozilla.org/es/docs/web/css/pseudo-elements#lista_de_pseudoelementos

Sintaxis
```css
selector :: pseudo-elemento { 
    propiedad: valor;
}
```

::before
Sirve para agregar un contenido antes del elemento. El contenido es agregado mediante la propiedad content de CSS.

Ejemplo https://codi.link/PGgxPlTDrXR1bG88L2gxPg0KPGgyPlN1YnTDrXR1bG9zPC9oMj4NCjxoMj5TdWJ0w610dWxvczwvaDI+DQo8aDI+U3VidMOtdHVsb3M8L2gyPg0KPGgyPlN1YnTDrXR1bG9zPC9oMj4NCjxoMj5TdWJ0w610dWxvczwvaDI+DQo=%7CaDI6YmVmb3JlIHsNCiAgY29udGVudDogIiAqICI7DQogIGNvbG9yOiByZWQ7DQp9%7C
::after
Sirve para agregar un contenido después del elemento. El contenido es agregado mediante la propiedad content de CSS.

Ejemplo https://codi.link/PCEtLSBOYXZiYXIgaW1wcm92aXNhZGEgLS0+DQo8bmF2Pg0KICA8dWw+DQogICAgPGxpPkhvbWU8L2xpPg0KICAgIDxsaT5EZXN0YWNhZG9zPC9saT4NCiAgICA8bGk+RWxlbWVudG9zPC9saT4NCiAgICA8bGk+Q2xhc2VzPC9saT4NCiAgICA8bGk+TcOhcy4uLjwvbGk+DQogIDwvdWw+DQo8L25hdj4NCg==%7CbmF2IHVsIHsNCiAgbGlzdC1zdHlsZTogbm9uZTsNCiAgZGlzcGxheTogZmxleDsNCiAganVzdGlmeS1jb250ZW50OiBzcGFjZS1hcm91bmQ7DQogIGN1cnNvcjogcG9pbnRlcjsNCn0NCg0KbmF2IHVsIGxpOjphZnRlciB7DQogIGNvbnRlbnQ6ICJ8IjsNCiAgbWFyZ2luOiAxcmVtOw0KICBjb2xvcjogcmVkOw0KfQ==%7C

::first-letter
Sirve para añadir estilos a a la primera letra del texto de cualquier elemento.

Ejemplo https://codi.link/PHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0KPHA+U295IG90cm8gcMOhcnJhZm88L3A+DQo8cD5Tb3kgb3RybyBww6FycmFmbzwvcD4NCjxwPlNveSBvdHJvIHDDoXJyYWZvPC9wPg0K%7COjpmaXJzdC1sZXR0ZXJ7DQogIGNvbG9yOiByZWQ7DQp9DQo=%7C

Lecturas recomendadas


https://github.com/platzi/curso-frontend-developer/blob/5108689bdb6599cc92bd9595db28784f9be48704/curso-1/selectores-3.html


Pseudo-elements - CSS: Cascading Style Sheets | MDN

https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements


Meet the Pseudo Class Selectors | CSS-Tricks - CSS-Tricks

https://css-tricks.com/pseudo-class-selectors/

**Cascada y especificidad en CSS**

En algún punto, cuando estés creando una página web, te encontrarás con problemas con los estilos, por ejemplo:

¿Por qué no se aplica el color que le estoy poniendo?
¿Por qué este elemento se comporta de manera diferente?
Probablemente, sea un inconveniente de cascada o especificidad.

Qué es la cascada en CSS
La cascada es el concepto que determina qué estilos se colocan sobre otros, priorizando a aquellos que se encuentren más abajo del código. Recordarás que CSS es la abreviación de Cascade Style Sheets, que traducido es hojas de estilos en Cascada.


![](img/frontend_developer16.png)

Mira el siguiente código e identifica de qué color de letra tendrá la etiqueta ```<h1>```.

```css
h1 {
    color: red;
}

h1 {
    color: blue;
}
```

La etiqueta ```<h1>``` tendrá un color blue de letra, esto porque está situado más abajo en el código. Esto ocurre con cada propiedad de CSS que se repita en algún punto más arriba del código.

*Qué es especificidad en CSS*

La especificidad consiste en dar un valor a una regla CSS sobre qué tan específico es el estilo, esto para que los navegadores puedan saber qué estilos aplicar sobre otros, independientemente de dónde se encuentren en el código. El estilo se aplicará donde la especificidad sea mayor.

*Tipos de especificidad en CSS*

Existen 6 tipos de especificidad con su respectivo valor, donde X es la cantidad de estilos que lo contienen. Mira la siguiente imagen:

![](img/Especificidad.png)

Valor con mayor especificidad
La palabra reservada !important es un valor de toda propiedad CSS que provee una especificidad de 10000, por lo que se aplicará ante otros estilos. Esto es una mala práctica y no deberías utilizarlo.
```css
{
    color: red !important;
}
```

Estilos en línea
Los estilos en línea son las propiedades CSS escritas en el HTML a través de la propiedad style de toda etiqueta. También es una mala práctica y debes evitarlo.
```html
<h1 style="color: blue;">Especificidad</h1>
```

Especificidad en selectores
El tema de los selectores ya lo conoces, por lo tanto, los selectores de tipo ID son más específicos que las clases, atributos y pseudoclases. Estas últimas son más específicas que los elementos y pseudoelementos. El selector universal tiene una especificidad de 0.

En un proyecto deberías evitar los !important y estilos en línea, para trabajar únicamente con la especificidad de los selectores. Sin embargo, debes tener presente que los selectores combinadores suman la especificidad de cada selector básico para obtener la especificidad total de la regla CSS.

![](img/frontend_developer18.png)

Si utilizas Visual Studio Code y mantienes el mouse sobre el selector, te mostrará la especificidad total. Specificity Calculator es una página web donde puedes calcular la especificidad.
link https://specificity.keegan.st/


## Tipos de display más usados: block, inline e inline-block

La propiedad ```display``` establece el tipo de visualización de los elementos HTML sin afectar el flujo normal de los elementos.

![](img/frontend_developer19.png)

Existen etiquetas que por defecto su display ya está determinado, como la etiqueta ```<div>``` que tiene display block, ```<span>``` tiene display inline y ```<button>``` tiene display inline-block.

Abordaremos los tipos de display ```block```, ```inline``` e ```inline-block``` a continuación.

Visualización en bloque (```block```)
El display block **establece que un elemento ocupará todo el espacio disponible por defecto y el siguiente elemento a este se situará por debajo.

Es posible añadir medidas de anchura ```width``` y altura ```height``` a estos a elementos.

También es posible agregar todas las propiedades del modelo de caja (no te preocupes de este concepto, ya lo abordaremos).

[Ejemplo de display block](https://codi.link/PGRpdj5Tb3kgZGlzcGxheSBibG9jazwvZGl2Pg0KPGRpdj5Tb3kgZGlzcGxheSBibG9jazwvZGl2Pg0KPGRpdiBjbGFzcz0iY29uX21lZGlkYXMiPlNveSBkaXNwbGF5IGJsb2NrPC9kaXY+DQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KZGl2ew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KICAvKiBtYXJnaW46IDEwcHg7ICovDQogIC8qIHBhZGRpbmc6IDEwcHg7ICovDQp9DQoNCi5jb25fbWVkaWRhcyB7DQogIC8qIHdpZHRoOiAyMDBweDsgKi8NCiAgLyogaGVpZ2h0OiAyMDBweDsgKi8NCn0NCg0KLyogSWdub3JhIGVzdG9zIGVzdGlsb3MsIHBvciBhaG9yYSAqLw0KKiB7DQogIGZvbnQtc2l6ZTogMS4ycmVtOw0KICBtYXJnaW46IDA7DQp9DQoNCg0KDQo=%7C) 
Visualización en línea (```inline```)
El display ```inline``` establece que un elemento ocupará el espacio del contenido del mismo y el siguiente elemento se situará a la derecha.
 
No es posible añadir medidas de anchura ```width``` y altura ```height``` a estos a elementos.

También, no es posible agregar todas las propiedades del modelo de caja, únicamente funcionará la propiedad margin en el eje horizontal (no te preocupes de este concepto, ya lo abordaremos).

[Ejemplo de display inline](https://codi.link/PHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4+U295IGRpc3BsYXkgaW5saW5lPC9zcGFuPg0KPHNwYW4gY2xhc3M9ImNvbl9tZWRpZGFzIj5Tb3kgZGlzcGxheSBpbmxpbmU8L3NwYW4+DQoNCg==%7CLyogUXVpdGEgeSBhZ3JlZ2EgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0Kc3BhbnsNCiAgYmFja2dyb3VuZC1jb2xvcjogYXF1YTsNCiAgLyogbWFyZ2luOiAyMHB4OyAqLw0KICAvKiBwYWRkaW5nOiAyMHB4OyAqLw0KfQ0KDQouY29uX21lZGlkYXMgew0KICAvKiB3aWR0aDogMjAwcHg7ICovDQogIC8qIGhlaWdodDogMjAwcHg7ICovDQp9DQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBmb250LXNpemU6IDEuMnJlbTsNCiAgbWFyZ2luOiAwOw0KfQ0KDQoNCg0K%7C)
Visualización de bloque y línea (inline-block)
El display inline-block combina las ventajas de bloque de colocar medidas al elemento y propiedades del modelo de caja correctamente; con las ventajas de inline de color un elemento seguido de otro en el mismo espacio.

Si elemento excede el contenido total, se coloca en la siguiente línea por debajo.
[Ejemplo de display inline-block](https://codi.link/PGJ1dHRvbj5Tb3kgZGlzcGxheSBpbmxpbmUtYmxvY2s8L2J1dHRvbj4NCjxidXR0b24+U295IGRpc3BsYXkgaW5saW5lLWJsb2NrPC9idXR0b24+DQo8YnV0dG9uPlNveSBkaXNwbGF5IGlubGluZS1ibG9jazwvYnV0dG9uPg0KPGJ1dHRvbj5Tb3kgZGlzcGxheSBpbmxpbmUtYmxvY2s8L2J1dHRvbj4NCjxidXR0b24gY2xhc3M9ImNvbl9tZWRpZGFzIj5Tb3kgZGlzcGxheSBpbmxpbmUtYmxvY2s8L2J1dHRvbj4NCg0K%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KYnV0dG9uew0KICAvKiBtYXJnaW46IDEwcHg7ICovDQogIC8qIHBhZGRpbmc6IDEwcHg7ICovDQp9DQoNCi5jb25fbWVkaWRhcyB7DQogIC8qIHdpZHRoOiAzMDBweDsgKi8NCiAgLyogaGVpZ2h0OiAxMDBweDsgKi8NCn0NCg0KLyogSWdub3JhIGVzdG9zIGVzdGlsb3MsIHBvciBhaG9yYSAqLw0KKiB7DQogIGZvbnQtc2l6ZTogMS4xcmVtOw0KICBtYXJnaW46IDA7DQp9DQoNCg0KDQo=%7C)


Visualización nula (none)
El display none desactiva la visualización de un elemento, como si el elemento no existiera.

[Ejemplo de display none](https://codi.link/PGRpdj48L2Rpdj4NCjxkaXY+PC9kaXY+DQo8ZGl2IGNsYXNzPSJkZXNhcGFyZWNlciI+DQogIEVuIG1pIHNpZ3VpZW50ZSB0cnVjbywgwqF2b3kgYSBkZXNhcGFyZWNlciENCjwvZGl2Pg0KPGRpdj48L2Rpdj4NCjxkaXY+PC9kaXY+DQo=%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmRlc2FwYXJlY2Vyew0KICAvKiBkaXNwbGF5OiBub25lOyAqLw0KICBiYWNrZ3JvdW5kLWNvbG9yOiBjb3JuZmxvd2VyYmx1ZTsNCiAgDQp9DQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBib3gtc2l6aW5nOiBib3JkZXItYm94Ow0KICBmb250LXNpemU6IDEuMXJlbTsNCiAgbWFyZ2luOiAwOw0KfQ0KDQpib2R5ew0KICBkaXNwbGF5OiBmbGV4Ow0KfQ0KDQpkaXZ7DQogIGJhY2tncm91bmQtY29sb3I6IGNvcmFsOw0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQogIGZvbnQtd2VpZ2h0OiA4MDA7DQogIHBhZGRpbmc6IDhweDsNCn0NCg0KDQoNCg==%7C)

**Tipos de display más usados: flexbox y CSS grid**

El display ```flex``` y ```grid``` son formas de visualización de elementos recientes y cada uno tienen sus propias características para crear interfaces de manera efectiva, a partir de un contenedor padre que dotará a los elementos hijos de superpoderes del posicionamiento.

Ambas son herramientas muy útiles en el desarrollo, especialmente para la creación de interfaces amigables al usuario y aptas para cualquier dispositivo, que este último se lo conoce como responsive design.

Sin embargo, ambas herramientas tienen temas muy extensos de entender, y como mi intención no es estresarte con demasiada información, simplemente ten presente de manera general en qué consisten.
    
### Flexbox
    
![](img/display.png)
Flexbox consiste en el ordenamiento de elementos hijos en un solo eje, por defecto horizontalmente. El elemento padre o contenedor deberá contener la propiedad ```display``` con el valor ```flex```. A partir de aquí, ya puedes ordenar los hijos según sea necesario.
    
[Ejemplo de flexbox](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCjwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lcnsNCiAgLyogZGlzcGxheTogZmxleDsgKi8NCn0NCg0KLmNvbnRhaW5lciBkaXYgew0KICB3aWR0aDogMTAwcHg7IA0KICBoZWlnaHQ6IDEwMHB4Ow0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4pew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4rMSl7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQoNCg0KDQoNCg0K%7C)

Cuando domines los temas básicos de CSS y las propiedades más usadas, revisadas en el contenido del curso, sigue con Flexbox. Puedes utilizar la guía y el curso en Platzi sobre el tema:
    
[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    
Qué es grid
Grid consiste en el ordenamiento de elementos hijos en dos ejes, como si fuera una cuadrícula o tabla. El elemento padre o contenedor deberá contener la propiedad display con el valor grid y debes definir las medidas de las columnas y de las filas. A partir de aquí, ya puedes ordenar los hijos según sea necesario.
    
[Ejemplo de Grid](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCjwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lcnsNCi8qICAgDQogIGRpc3BsYXk6IGdyaWQ7DQogIGdyaWQtdGVtcGxhdGUtY29sdW1uczogMTAwcHggMTAwcHggMTAwcHg7DQogIGdyaWQtdGVtcGxhdGUtcm93czogMTAwcHggMTAwcHggMTAwcHg7IA0KICAqLw0KDQoNCn0NCg0KLmNvbnRhaW5lciBkaXYgew0KICB3aWR0aDogMTAwcHg7IA0KICBoZWlnaHQ6IDEwMHB4Ow0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4pew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4rMSl7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQoNCg0KDQoNCg0K%7C)
    
Cuando domines lo básico de Flexbox, sigue con Grid. Puedes utilizar la guía y el curso en Platzi que tenemos sobre el tema:
    
[Complete guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
    
    
Flexbox vs CSS Grid: ¿Cuál es la diferencia?

https://platzi.com/blog/flexbox-vs-css-grid-cual-es-la-diferencia/


curso-frontend-developer/display-1.html at 5108689bdb6599cc92bd9595db28784f9be48704 · platzi/curso-frontend-developer · GitHub

https://github.com/platzi/curso-frontend-developer/blob/5108689bdb6599cc92bd9595db28784f9be48704/curso-1/display-1.html


A Complete Guide to Flexbox | CSS-Tricks

https://css-tricks.com/snippets/css/a-guide-to-flexbox/


### Modelo de caja


El modelo de caja se compone de cuatro elementos: margin, border, padding y contenido

![](img/frontend_developer20.png)

Si entras a las herramientas de desarrollador de tu navegador y señalas un elemento HTML, en la sección de estilos te aparecerá una vista parecida a la anterior imagen, este es el modelo de caja del elemento señalado.

### Qué es el contenido del elemento HTML

El contenido del elemento, como su nombre lo indica, es todo lo que está dentro del elemento. Este tiene medidas establecidas por las propiedades ```width``` y ```height```, que representan la anchura y la altura, respectivamente. Si imaginamos una caja, este valor sería todo lo que decidas colocar dentro.

```css
div {
    width: 100px;
    height: 100px;
}
```

### Qué son los bordes del elemento HTML
El border consiste en el perfil o borde de un elemento HTML. Si imaginamos una caja, sería la caja en sí. Para definir un borde es necesario utilizar las siguientes tres propiedades:

* ```border-color```: establece el color del borde.
* ```border-style```: establece el estilo propio del borde, estos pueden ser: none (sin borde), dotted (puntos), dashed (guiones), solid (continuo), double (doble continuo), groove (recuadro).
* ```border-width```: estable la anchura del borde.

También se puede establecer los tres valores en una sola propiedad border donde no importa el orden.

```css
div {
    border: [color] [style] [width];
}

div {
    border-color: red;
    border-style: solid;
    border-width: 1px;
}
```

![Ejemplo de bordes](https://codi.link/PGRpdiBjbGFzcz0ibm9uZSI+U2luIGJvcmRlPC9kaXY+DQo8ZGl2IGNsYXNzPSJkb3R0ZWQiPkNvbiBwdW50b3M8L2Rpdj4NCjxkaXYgY2xhc3M9ImRhc2hlZCI+Q29uIGd1aW9uZXM8L2Rpdj4NCjxkaXYgY2xhc3M9InNvbGlkIj5Db250aW51bzwvZGl2Pg0KPGRpdiBjbGFzcz0iZG91YmxlIj5kb2JsZSBjb250aW51bzwvZGl2Pg0KPGRpdiBjbGFzcz0iZ3Jvb3ZlIj5Db24gcmVjdWFkcm88L2Rpdj4NCg0KDQo=%7CZGl2ew0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQp9DQoNCi5ub25lew0KICAvKiBWYWxvciBwb3IgZGVmZWN0byBkZSBkaXYgKi8NCiAgYm9yZGVyOiAzcHggYmxhY2sgbm9uZTsNCn0NCg0KLmRvdHRlZHsNCiAgYm9yZGVyOiAzcHggYmxhY2sgZG90dGVkOw0KfQ0KDQouZGFzaGVkew0KICBib3JkZXI6IDNweCBibGFjayBkYXNoZWQ7DQp9DQoNCi5zb2xpZHsNCiAgYm9yZGVyOiAzcHggYmxhY2sgc29saWQ7DQp9DQoNCi5kb3VibGV7DQogIGJvcmRlcjogM3B4IGJsYWNrIGRvdWJsZTsNCn0NCg0KLmdyb292ZXsNCiAgYm9yZGVyOiA1cHggZ3JlZW55ZWxsb3cgZ3Jvb3ZlOw0KfQ0KDQoNCg0KLyogSWdub3JhIGVzdG9zIGVzdGlsb3MsIHBvciBhaG9yYSAqLw0KKiB7DQogIGZvbnQtc2l6ZTogMS4xcmVtOw0KICBtYXJnaW46IDA7DQp9DQoNCmJvZHl7DQogIGRpc3BsYXk6IGZsZXg7DQogIGZsZXgtd3JhcDogd3JhcDsNCiAgZ2FwOiAxLjVyZW07DQogIG1hcmdpbjogMjBweDsNCiAgZm9udC13ZWlnaHQ6IDgwMDsNCn0NCg0KDQoNCg==%7C)
También estableciendo de manera individual los valores de cada posición:


```css
div {
  border-top: 5px solid blue;
  border-bottom: 5px solid red;
  border-left: 5px solid black;
  border-right: 5px solid yellow;
}
```

## Qué es el espaciado interno del elemento HTML o padding

El ```padding``` consiste en el espacio entre el borde y el contenido del elemento HTML. Si imaginamos una caja, este valor sería el espacio entre la caja y lo que deseas guardar.

```css
div {
    padding: 100px;
}
```
[Ejemplo de Padding](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KZGl2ew0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KICBib3JkZXI6IHNvbGlkIDFweCBibGFjazsNCiAgLyogcGFkZGluZzogMzBweDsgKi8NCn0NCg0KDQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBmb250LXNpemU6IDEuMXJlbTsNCiAgbWFyZ2luOiAwLjVyZW07DQp9DQo=%7C)


Puedes establecer el padding en cada posición en una sola línea de las siguientes maneras:

* ```padding: [arriba] [derecha] [abajo] [izquierda]```, siguiendo el sentido horario.
* ```padding: [arriba] [derecha e izquierda] [abajo]```, siguiendo el eje principal.
* ```padding: [arriba y abajo] [derecha e izquierda]```, siguiendo los ejes del elemento.
También estableciendo de manera individual los valores de cada posición:

```css
div {
    padding-top: 10px;
    padding-bottom: 15px;
    padding-left: 20px;
    padding-right: 10px;
}
```

### Qué es el espaciado externo del elemento HTML o margin

El ```margin``` consiste en el espacio entre el borde y otro elemento HTML. Si imaginamos una caja, es el espacio entre tu caja y otra caja.

```css
div {
    margin: 10px;
}
```
[Ejemplo de margin](https://codi.link/PGRpdiBjbGFzcyA9ICJtYXJnaW4iPkxvcmVtIGlwc3VtIGRvbG9yIHNpdCBhbWV0IGNvbnNlY3RldHVyIGFkaXBpc2ljaW5nIGVsaXRpPC9kaXY+DQo8ZGl2PlNveSBvdHJvIGVsZW1lbnRvPC9kaXY+DQoNCg0K%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KZGl2ew0KICB3aWR0aDogMTIwcHg7DQogIGhlaWdodDogMTIwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KICBib3JkZXI6IHNvbGlkIDFweCBibGFjazsNCn0NCg0KLm1hcmdpbiB7DQogIC8qIG1hcmdpbjogMjBweDsgKi8NCn0NCg0KDQoNCi8qIElnbm9yYSBlc3RvcyBlc3RpbG9zLCBwb3IgYWhvcmEgKi8NCiogew0KICBmb250LXNpemU6IDEuMXJlbTsNCiAgbWFyZ2luOiAwOw0KfQ0KDQpib2R5ew0KICBkaXNwbGF5OiBmbGV4Ow0KICBtYXJnaW46IDIwcHg7DQogIGZvbnQtd2VpZ2h0OiA4MDA7DQp9DQoNCg0KDQoNCg==%7C)

Puedes establecer el margin en cada posición en una sola línea de las siguientes maneras:

* ```margin: [arriba] [derecha] [abajo] [izquierda]```, siguiendo el sentido horario.
* ```margin: [arriba] [abajo] [derecha e izquierda]```, siguiendo el eje principal.
* ```margin: [arriba y abajo] [derecha e izquierda]```, siguiendo los ejes del elemento.

También estableciendo de manera individual los valores de cada posición:

```css
div {
    margin-top: 10px;
    margin-bottom: 15px;
    margin-left: 20px;
    margin-right: 10px;
}
```

### Qué son los valores por defecto

Por defecto, el navegador establece valores iniciales a algunas propiedades CSS, este es el caso de ```margin``` y ```padding```. Una buena práctica es utilizar el selector universal para restablecer estos valores a ```0```, para que no surjan errores inesperados.

```css
* {
    margin: 0;
    padding: 0;
}
```

### Qué es el tamaño total del elemento

El tamaño total del elemento está determinado por la suma de los valores de las propiedades border ```padding``` y ```width``` o ```height```, dependiendo del eje. La propiedad margin no está incluida en este cálculo.

Por ejemplo, definimos los siguientes estilos:

```css
div{
  width: 150px;
  height: 150px;
  padding: 20px;
  border: 10px solid gray;
  margin: 30px;
}
```
[Ejemplo de medidas totales](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCn0NCg0KZGl2ew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBncmVlbnllbGxvdzsNCiAgd2lkdGg6IDE1MHB4Ow0KICBoZWlnaHQ6IDE1MHB4Ow0KICBwYWRkaW5nOiAyMHB4Ow0KICBib3JkZXI6IDEwcHggc29saWQgZ3JheTsNCiAgbWFyZ2luOiAzMHB4Ow0KfQ0KDQoNCg0KDQoNCg0KDQoNCg==%7C)

El tamaño total del elemento será de ```210px``` en ambos ejes, donde la suma fue: ```150``` (altura/anchura) + ```20 x 2``` (padding ambos lados) + ```10 x 2``` (borde ambos lados). Si evaluamos este elemento en las herramientas del desarrollador mostrará su tamaño como ```210x210```

![](img/frontend_developer22.png)


Aunque se conozca las medidas de los elementos de esta manera, no siempre existirá un control total. Por lo que podríamos establecer el tamaño total del elemento con ```width``` y ```height```, y no solo del contenido, añadiendo la propiedad ```box-sizing```.


## Propiedad box-sizing

La propiedad ```box-sizing```establece cómo se calculará el width y el height si incluyen bordes y espacios internos. Como buena práctica, se lo coloca en el selector universal, para que todos los elementos sigan esta tendencia.
```css
* {
  box-sizing: border-box;
}
```


Con el valor ```border-box```, el tamaño total del elemento será igual al especificado en el ```width``` y ```height```, provocando que las medidas del contenido cambien con respecto a los bordes y espacios internos.

Por ejemplo, con los estilos que definimos anteriormente, establezcamos esta nueva propiedad.

[Ejemplo de box-sizing](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KICAvKiBib3gtc2l6aW5nOiBib3JkZXItYm94OyAqLw0KfQ0KDQpkaXZ7DQogIGJhY2tncm91bmQtY29sb3I6IGdyZWVueWVsbG93Ow0KICB3aWR0aDogMTUwcHg7DQogIGhlaWdodDogMTUwcHg7DQogIHBhZGRpbmc6IDIwcHg7DQogIGJvcmRlcjogMTBweCBzb2xpZCBncmF5Ow0KICBtYXJnaW46IDMwcHg7DQp9DQoNCg0KDQoNCg0K%7C)

El tamaño total del elemento será de ```150px``` en ambos ejes, donde se calcularon las medidas del contenido para que la suma total sea lo especificado en el ```width``` y ```height```. Si evaluamos este elemento en las herramientas del desarrollador mostrará su tamaño total como ```150x150``` y el contenido como ```90x90```.

![](img/frontend_developer23.png)

Conclusión, establece las medidas totales del elemento con ```width``` y ```height```, junto con ```box-sizing: border-box```, para que el contenido se adecue a las necesidades del contenedor.

## ¿Cuál es el problema con el tamaño de los bordes?

Recapitulando, el tamaño total de un elemento es la suma de tres: el borde, el espacio interior y el contenido.

Entonces, en algunas ocasiones tendrás la intención de añadir un borde al realizar un hover. Esto provocará que el elemento necesite más espacio del inicial, en un contenedor con más elementos puede ocasionar un conflicto.

Mira el siguiente ejemplo, e intenta poner el cursor sobre un elemento ¿qué sucede?
[Ejemplo de problema con bordes](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg==%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KfQ0KDQpkaXZ7DQogIGRpc3BsYXk6IGlubGluZS1ibG9jazsNCiAgYmFja2dyb3VuZC1jb2xvcjogZ3JlZW55ZWxsb3c7DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgcGFkZGluZzogMjBweDsNCiAgbWFyZ2luOiAzMHB4Ow0KfQ0KDQpkaXY6aG92ZXJ7DQogIGJvcmRlcjogMTBweCBzb2xpZCBncmF5Ow0KICBjdXJzb3I6IHBvaW50ZXI7DQp9DQoNCg0KDQoNCg0K%7C)

Observaste este comportamiento, debes tener cuidado con lo que agregas porque puedes provocar errores.

La solución a esto es colocar un borde de color ```transparent``` (transparente) y del mismo tamaño que el otro borde. Esto hará que el elemento se mantenga en su tamaño total, lo único que cambia es el color.

# Colapso de márgenes

El colapso de márgenes sucede cuando dos elementos bloque adyacentes tienen un determinado valor de ```margin```, entonces estos márgenes se solapan en un solo valor, el mayor de ambos.

![](img/frontend_developer25.png)

## Ejemplo de colapso de márgenes

Mira el siguiente código, cambia el valor de ```display``` a ```inline-block``` y observa el resultado.

[Ejemplo de colapso de márgenes](https://codi.link/PGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KPGRpdj5Mb3JlbSBpcHN1bSBkb2xvciBzaXQgYW1ldCBjb25zZWN0ZXR1ciBhZGlwaXNpY2luZyBlbGl0aTwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBsbyBxdWUgb2N1cnJlICovDQpkaXZ7DQogIGRpc3BsYXk6IGlubGluZS1ibG9jazsNCiAgbWFyZ2luOiA0MHB4Ow0KICBiYWNrZ3JvdW5kLWNvbG9yOiBncmVlbnllbGxvdzsNCiAgd2lkdGg6IDgwJTsNCiAgaGVpZ2h0OiA1MHB4Ow0KICBwYWRkaW5nOiAxMHB4Ow0KfQ0KDQoNCg0KDQoNCg0K%7C)

![](img/frontend_developer24.png)

Como puedes observar, al cambiar el display este comportamiento desaparece. Además, en flexbox y grid no ocurre el colapso de márgenes. Cuida los márgenes que colocas en los elementos de tipo bloque.

# Posicionamiento en CSS

El posicionamiento en CSS consiste en cómo un elemento se situará, con respecto a su elemento padre y al flujo normal del documento. El flujo normal del documento es el orden de los elementos establecidos en el HTML.

La posición del elemento se la define con la propiedad ```position```, mediante los siguientes valores:

* ```static```
* ```relative```
* ```absolute```
* ```sticky```
![](img/Capture.PNG.png)

## Propiedades de posición

Además de la propiedad ```position```, existen cuatro propiedades del elemento de acuerdo a su posición con respecto a su padre, estas son: ```top``` (arriba), ```bottom``` (debajo), ```left``` (izquierda) y ```right``` (derecha).

```css
div {
    top: 10px;
    bottom: 15px;
    left: 20px;
    right: 10px;
}
```

Estos valores estarán establecidos en el padre próximo que tenga la posición ```relative```.

Si ```top``` y ```bottom``` están definidos, ```top``` gana. Si ```left``` y ```rigth``` están definidos, ```left``` gana (dependiendo el idioma configurado).

### Posición estática

La posición ```static``` es el valor por defecto de todo elemento HTML, consiste en respetar el flujo normal del documento donde las propiedades de posición no pueden ser establecidas.

[Ejemplo position static](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCiAgPGRpdj48L2Rpdj4NCjwvZGl2Pg0KDQoNCg0K%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLmNvbnRhaW5lcnsNCiAgd2lkdGg6IDEwMCU7DQoNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lciBkaXYgew0KICB3aWR0aDogMTAwcHg7IA0KICBoZWlnaHQ6IDEwMHB4Ow0KLyogDQogIHRvcDogMTBweDsNCiAgYm90dG9tOiAxNXB4Ow0KICBsZWZ0OiAyMHB4Ow0KICByaWdodDogMTBweDsgDQogICovDQp9DQoNCi5jb250YWluZXIgZGl2Om50aC1jaGlsZCgybil7DQogIGJhY2tncm91bmQtY29sb3I6IGFxdWE7DQp9DQoNCi5jb250YWluZXIgZGl2Om50aC1jaGlsZCgybisxKXsNCiAgYmFja2dyb3VuZC1jb2xvcjogYnJvd247DQp9DQoNCg0KDQoNCg0KDQo=%7C)
### Posición relative
La posición ```relative``` consiste en respetar el flujo normal del documento donde las propiedades de posición sí pueden ser establecidas.

[Ejemplo position relative](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdiBjbGFzcz0icmVsYXRpdmUiPjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KICA8ZGl2PjwvZGl2Pg0KPC9kaXY+DQoNCg0KDQo=%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KLmNvbnRhaW5lcnsNCiAgd2lkdGg6IDEwMCU7DQp9DQoNCi5jb250YWluZXIgZGl2IHsNCiAgd2lkdGg6IDEwMHB4OyANCiAgaGVpZ2h0OiAxMDBweDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lciAucmVsYXRpdmV7DQogIC8qIHBvc2l0aW9uOiByZWxhdGl2ZTsgKi8NCiAgLyogdG9wOiA1MHB4OyAqLw0KICAvKiBsZWZ0OiA1MHB4OyAqLw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4pew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBhcXVhOw0KfQ0KDQouY29udGFpbmVyIGRpdjpudGgtY2hpbGQoMm4rMSl7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQoNCg0KDQoNCg0K%7C)
### Posición absoluta
La posición ```absolute``` consiste en quitar al elemento del flujo normal del documento donde las propiedades de posición sí pueden ser establecidas.

En el siguiente ejemplo, observa que pasa con el primer elemento con respecto a los demás.

[Ejemplo position absolute](https://codi.link/PGRpdiBjbGFzcz0iY29udGFpbmVyIj4NCiAgPGRpdiBjbGFzcz0iYWJzb2x1dGUiPjE8L2Rpdj4NCiAgPGRpdj4yPC9kaXY+DQogIDxkaXY+MzwvZGl2Pg0KICA8ZGl2PjQ8L2Rpdj4NCiAgPGRpdj41PC9kaXY+DQo8L2Rpdj4NCg0KDQoNCg==%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCiAgZm9udC1zaXplOiAxLjVyZW07DQp9DQoNCi8qIEltcG9ydGFudGUgZWwgcG9zaXRpb24gKi8NCi5jb250YWluZXJ7DQogIHBvc2l0aW9uOiByZWxhdGl2ZTsNCiAgd2lkdGg6IDEwMCU7DQp9DQoNCi5jb250YWluZXIgZGl2IHsNCiAgd2lkdGg6IDEwMHB4OyANCiAgaGVpZ2h0OiAxMDBweDsNCn0NCg0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KLmNvbnRhaW5lciAuYWJzb2x1dGV7DQogIC8qIHBvc2l0aW9uOiBhYnNvbHV0ZTsgKi8NCiAgLyogbGVmdDogMTUwcHg7ICovDQogIC8qIHRvcDogNTBweDsgKi8NCn0NCg0KLmNvbnRhaW5lciBkaXY6bnRoLWNoaWxkKDJuKXsNCiAgYmFja2dyb3VuZC1jb2xvcjogYXF1YTsNCn0NCg0KLmNvbnRhaW5lciBkaXY6bnRoLWNoaWxkKDJuKzEpew0KICBiYWNrZ3JvdW5kLWNvbG9yOiBicm93bjsNCn0NCg0KDQoNCg0KDQoNCg0KDQo=%7C)
Habrás notado que el elemento “2” desaparece, pero en realidad lo que sucede es que sitúa por detrás del elemento con posición absoluta que salió del flujo normal del documento. Este comportamiento se debe al eje Z de la pantalla y al contexto de apilamiento.

Elemento padre más próximo con posición relativa
El elemento con posición absoluta se desplazará arriba, abajo, izquierda o derecha con respecto al elemento padre más próximo con posición relativa.

Si no existe un padre con posición relativa de un elemento con posición absoluta, este se desplazará con respecto al elemento raíz del documento.

En el siguiente ejemplo, te encontrarás varios contenedores padres, incluso las etiquetas ```<html>``` y ```<body>```. Sigue los pasos y observa el comportamiento. Ignora los estilos iniciales, simplemente sirven para establecer la estructura del ejercicio.

[Ejemplo de position en diferentes contenedores padre](https://codi.link/PHA+Qm9keTwvcD4NCjxkaXYgY2xhc3M9ImFidWVsbyI+DQogIDxwPkFidWVsbzwvcD4NCiAgPGRpdiBjbGFzcz0icGFkcmUiPg0KICAgIDxwPlBhZHJlPC9wPg0KICAgIDxkaXYgY2xhc3M9Imhpam8iPg0KICAgICAgPHA+SGlqbzwvcD4NCiAgICA8L2Rpdj4NCiAgPC9kaXY+DQo8L2Rpdj4=%7CLyogRWwgZWplcmNpY2lvIGVzdMOhIGhhc3RhIGFiYWpvICovDQoNCiogew0KICBtYXJnaW46IDA7DQogIHBhZGRpbmc6IDA7DQogIGJveC1zaXppbmc6IGJvcmRlci1ib3g7DQogIHRleHQtYWxpZ246IGNlbnRlcjsNCn0NCg0KaHRtbHsNCiAgbWFyZ2luOiAyMHB4Ow0KICBib3JkZXI6IDFweCByZWQgc29saWQ7DQp9DQoNCmJvZHkgew0KICBtYXJnaW46IDIwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IHdoZWF0Ow0KICBib3JkZXI6IDFweCBibGFjayBzb2xpZDsNCn0NCg0KcCB7DQogIGZvbnQtc2l6ZTogMS41cmVtOw0KICBmb250LXdlaWdodDogYm9sZDsNCiAgbWFyZ2luLWJvdHRvbTogNTBweDsNCg0KfQ0KDQouYWJ1ZWxvew0KICB3aWR0aDogMTAwJTsNCiAgaGVpZ2h0OiAxMDB2aDsNCiAgYmFja2dyb3VuZC1jb2xvcjogeWVsbG93Z3JlZW47DQp9DQoNCi5wYWRyZXsNCiAgd2lkdGg6IDc1JTsNCiAgaGVpZ2h0OiA3NSU7DQogIGJhY2tncm91bmQtY29sb3I6IGNhZGV0Ymx1ZTsNCn0NCg0KLmhpam97DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgYmFja2dyb3VuZC1jb2xvcjogcm9zeWJyb3duOyANCn0NCg0KDQovKiBMbyDDum5pY28gcXVlIHF1aWVybyBxdWUgZW50aWVuZGFzIGVzIHF1ZSBoYXkgMyBjb250ZW5lZG9yZXMsIGxvcyBjdcOhbGVzIA0KLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCBjb21wb3J0YW1pZW50byAqLw0KDQoNCi5oaWpvIHsNCiAgLyogcG9zaXRpb246IGFic29sdXRlOyAqLw0KICAvKiB0b3A6IDA7ICovDQp9DQoNCi8qIMK/IFBvciBxdcOpIHN1Y2VkacOzIGVzdG8gPyAqLw0KDQpodG1sIHsNCiAgLyogcG9zaXRpb246IHJlbGF0aXZlOyAqLw0KfQ0KDQpib2R5IHsNCiAgLyogcG9zaXRpb246IHJlbGF0aXZlOyAqLw0KfQ0KDQouYWJ1ZWxvew0KICAvKiBwb3NpdGlvbjogcmVsYXRpdmU7ICovDQp9DQoNCi5wYWRyZSB7DQogIC8qIHBvc2l0aW9uOiByZWxhdGl2ZTsgKi8NCn0NCg0KLyogwr8gQWhvcmEgZW50ZW5kaXN0ZSA/ICovDQoNCg0KDQoNCg0KDQoNCg0K%7C)
Como pudiste observar, en el elemento con posición absoluta, su desplazamiento se basa con relación al elemento padre más próximo con posición relativa.

### Posición fija
La posición ```fixed``` consiste en quitar al elemento del flujo normal del documento y fijarlo en un lugar; donde las propiedades de posición sí pueden ser establecidas.

En el siguiente ejemplo, desplázate por el documento, observa el comportamiento antes y después de colocar la posición fija.

[Ejemplo position fixed](https://codi.link/PG5hdj5EZSBncmFuZGUgcXVpZXJvIHNlciB1bmEgYmFycmEgZGUgbmF2ZWdhY2nDs248L25hdj4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQo8cD5Tb3kgdW4gcMOhcnJhZm8sIGJhamEgcG9yIGZhdm9yPC9wPg0KPHA+U295IHVuIHDDoXJyYWZvLCBiYWphIHBvciBmYXZvcjwvcD4NCjxwPlNveSB1biBww6FycmFmbywgYmFqYSBwb3IgZmF2b3I8L3A+DQoNCg0KDQo=%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCiAgZm9udC1zaXplOiAxLjFyZW07DQp9DQoNCi8qIERlc3Bsw6F6YXRlIHBvciBlbCBkb2N1bWVudG8geSBkZXNwdcOpcyBxdWl0YSBsb3MgY29tZW50YXJpb3MgeSBvYnNlcnZhIGVsIGNvbXBvcnRhbWllbnRvICovDQoNCm5hdiB7DQogIC8qIHBvc2l0aW9uOiBmaXhlZDsgKi8NCiAgLyogdG9wOiAwOyAqLw0KICBiYWNrZ3JvdW5kLWNvbG9yOiBjb3JuZmxvd2VyYmx1ZTsNCiAgd2lkdGg6IDEwMCU7DQogIGhlaWdodDogYXV0bzsNCiAgcGFkZGluZzogMjBweDsNCn0NCg0KcCB7DQogIHBhZGRpbmc6IDEwcHg7DQp9DQoNCg0KDQoNCg0KDQoNCg0K%7C)
### Posición variable fija
La posición ```sticky``` consiste en quitar al elemento del flujo normal del documento y fijarlo en un lugar mientras su contenedor sea visible; donde las propiedades de posición sí pueden ser establecidas.

En el siguiente ejemplo, desplázate por el documento, observa el comportamiento antes y después de colocar la posición variable fija.

[Ejemplo de position sticky](https://codi.link/PGRpdj4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDE8L3A+DQogIDx1bD4NCiAgICA8bGk+RWxlbWVudG8gMTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDI8L2xpPg0KICAgIDxsaT5FbGVtZW50byAzPC9saT4NCiAgICA8bGk+RWxlbWVudG8gNDwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDU8L2xpPg0KICAgIDxsaT5FbGVtZW50byA2PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDg8L2xpPg0KICAgIDxsaT5FbGVtZW50byA5PC9saT4NCiAgICA8bGk+RWxlbWVudG8gMTA8L2xpPg0KICA8L3VsPg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gMjwvcD4NCiAgPHVsPg0KICAgIDxsaT5FbGVtZW50byAxPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDM8L2xpPg0KICAgIDxsaT5FbGVtZW50byA0PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDY8L2xpPg0KICAgIDxsaT5FbGVtZW50byA3PC9saT4NCiAgICA8bGk+RWxlbWVudG8gODwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDk8L2xpPg0KICAgIDxsaT5FbGVtZW50byAxMDwvbGk+DQogIDwvdWw+DQogIDxwPlNveSB1biBww6FycmFmbyAzPC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDQ8L3A+DQogIDx1bD4NCiAgICA8bGk+RWxlbWVudG8gMTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDI8L2xpPg0KICAgIDxsaT5FbGVtZW50byAzPC9saT4NCiAgICA8bGk+RWxlbWVudG8gNDwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDU8L2xpPg0KICAgIDxsaT5FbGVtZW50byA2PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDg8L2xpPg0KICAgIDxsaT5FbGVtZW50byA5PC9saT4NCiAgICA8bGk+RWxlbWVudG8gMTA8L2xpPg0KICA8L3VsPg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gNTwvcD4NCiAgPHVsPg0KICAgIDxsaT5FbGVtZW50byAxPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDM8L2xpPg0KICAgIDxsaT5FbGVtZW50byA0PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDY8L2xpPg0KICAgIDxsaT5FbGVtZW50byA3PC9saT4NCiAgICA8bGk+RWxlbWVudG8gODwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDk8L2xpPg0KICAgIDxsaT5FbGVtZW50byAxMDwvbGk+DQogIDwvdWw+DQogIDxwPlNveSB1biBww6FycmFmbyA2PC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDc8L3A+DQogIDx1bD4NCiAgICA8bGk+RWxlbWVudG8gMTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDI8L2xpPg0KICAgIDxsaT5FbGVtZW50byAzPC9saT4NCiAgICA8bGk+RWxlbWVudG8gNDwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDU8L2xpPg0KICAgIDxsaT5FbGVtZW50byA2PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDg8L2xpPg0KICAgIDxsaT5FbGVtZW50byA5PC9saT4NCiAgICA8bGk+RWxlbWVudG8gMTA8L2xpPg0KICA8L3VsPg0KICA8cD5Tb3kgdW4gcMOhcnJhZm8gODwvcD4NCiAgPHVsPg0KICAgIDxsaT5FbGVtZW50byAxPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDM8L2xpPg0KICAgIDxsaT5FbGVtZW50byA0PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDY8L2xpPg0KICAgIDxsaT5FbGVtZW50byA3PC9saT4NCiAgICA8bGk+RWxlbWVudG8gODwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDk8L2xpPg0KICAgIDxsaT5FbGVtZW50byAxMDwvbGk+DQogIDwvdWw+DQogIDxwPlNveSB1biBww6FycmFmbyA5PC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCiAgPHA+U295IHVuIHDDoXJyYWZvIDEwPC9wPg0KICA8dWw+DQogICAgPGxpPkVsZW1lbnRvIDE8L2xpPg0KICAgIDxsaT5FbGVtZW50byAyPC9saT4NCiAgICA8bGk+RWxlbWVudG8gMzwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDQ8L2xpPg0KICAgIDxsaT5FbGVtZW50byA1PC9saT4NCiAgICA8bGk+RWxlbWVudG8gNjwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDc8L2xpPg0KICAgIDxsaT5FbGVtZW50byA4PC9saT4NCiAgICA8bGk+RWxlbWVudG8gOTwvbGk+DQogICAgPGxpPkVsZW1lbnRvIDEwPC9saT4NCiAgPC91bD4NCjwvZGl2Pg==%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCiAgZm9udC1zaXplOiAxLjFyZW07DQp9DQoNCi8qIERlc3Bsw6F6YXRlIHBvciBlbCBkb2N1bWVudG8geSBkZXNwdcOpcyBxdWl0YSBsb3MgY29tZW50YXJpb3MgeSBvYnNlcnZhIGVsIGNvbXBvcnRhbWllbnRvICovDQoNCnAgew0KICAvKiBwb3NpdGlvbjogc3RpY2t5OyAqLw0KICAvKiB0b3A6IDA7ICovDQogIGJhY2tncm91bmQtY29sb3I6IGNvcm5mbG93ZXJibHVlOw0KICBwYWRkaW5nOiAxMHB4Ow0KfQ0KDQpsaSB7DQogIG1hcmdpbjogMjBweCAzMHB4Ow0KfQ0KDQoNCg0KDQoNCg0KDQoNCg0K%7C)



## Z-index y el contexto de apilamiento

El contexto de apilamiento consiste en la superposición de capas o elementos a lo largo del eje Z del navegador. Esto es importante para evitar que un elemento esté ocultando a otro.


![](img/giphy.gif)

### Qué son los planos y ejes
El navegador está constituido de tres planos y ejes: el ancho o X; el alto o Y; y el de profundidad o Z.

El eje X positivo está hacia la derecha; el eje Y positivo está hacia abajo; y el eje Z positivo está hacia el usuario.

![](img/animationland03.PNG)

Estos son muy importantes para mover los elementos del HTML desde un punto inicial hacia un punto final.

## Qué es la propiedad z-index

El contexto de apilamiento se configura con la propiedad ```z-index```.

Por defecto, todos los elementos tienen un valor ```auto```, es decir, el orden está definido por la estructura del HTML. Los primeros elementos estarán detrás y los últimos estarán de frente.

Si se establece un valor positivo, este elemento se sitúa por delante de los demás. Si se establece un valor negativo, se sitúa por detrás.

Si un elemento tiene un ```z-index``` mayor a otro, estará por delante. Sin embargo, si un elemento que tiene un ```z-index``` menor a otros, sus hijos nunca estarán por encima, aunque su ```z-index``` sea mayor.

![](img/frontend_developer27.png)


[Ejemplo de contexto de apilamientos](https://codi.link/PGRpdiBjbGFzcz0icmVkIj5SZWQ8L2Rpdj4NCjxkaXYgY2xhc3M9ImJsdWUiPkJsdWUNCiAgPGRpdiBjbGFzcz0ieWVsbG93Ij4NCiAgICBZZWxsb3cgKGhpam8gZGUgYmx1ZSkNCiAgPC9kaXY+DQo8L2Rpdj4=%7CLyogUXVpdGEgbG9zIGNvbWVudGFyaW9zIHkgb2JzZXJ2YSBlbCByZXN1bHRhZG8gKi8NCg0KZGl2IHsNCiAgLyogcG9zaXRpb246IGFic29sdXRlOyAqLw0KfQ0KDQoucmVkew0KICAvKiB6LWluZGV4OiA1OyAqLw0KICAvKiB0b3A6IDUwcHg7ICovDQp9DQoNCi5ibHVlew0KICAvKiB6LWluZGV4OiA0OyAqLw0KICAvKiBsZWZ0OiA1MHB4OyAqLw0KfQ0KDQoueWVsbG93ew0KICAvKiB6LWluZGV4OiA2OyAqLw0KICAvKiByaWdodDogLTIwcHg7ICovDQogIC8qIHRvcDogNDBweDsgKi8NCn0NCg0KDQovKiBJZ25vcmEgbG9zIHNpZ3VpZW50ZXMgZXN0aWxvcyAqLw0KDQoqIHsNCiAgbWFyZ2luOiAwOw0KICBwYWRkaW5nOiAwOw0KICBib3gtc2l6aW5nOiBib3JkZXItYm94Ow0KICBmb250LXNpemU6IDEuMXJlbTsNCn0NCg0KZGl2IHsNCiAgd2lkdGg6IDIwMHB4Ow0KICBoZWlnaHQ6IDIwMHB4Ow0KfQ0KDQoucmVkew0KICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2IoMjQ2LCAxMDgsIDEwOCk7DQp9DQoNCi5ibHVlew0KICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2IoMTAyLCAxMDIsIDI0OSk7DQp9DQoNCi55ZWxsb3d7DQogIHdpZHRoOiAxNTBweDsNCiAgaGVpZ2h0OiAxNTBweDsNCiAgYmFja2dyb3VuZC1jb2xvcjogeWVsbG93Ow0KfQ0KDQoNCg0K%7C)
Como puedes observar en la imagen, el elemento con la clase ```yellow``` tiene un ```z-index``` mayor a ```red```, pero no está por encima, porque su contexto de apilamiento está dentro del contexto de apilamiento del elemento ```blue```, así mismo, nunca estará por detrás de su elemento padre.

# Propiedades y valores de CSS más usados

Las propiedades CSS más usadas son las siguientes, separadas en secciones comunes, algunas ya las conocemos:

* Display
* Margin
* Padding
* Border
* Width
* Height
* Color
* Background

![](img/frontend_developer28.png)

También, si deseas conocer todas las etiquetas existentes, puedes revisar el sitio web CSS Reference.
https://cssreference.io/

## Propiedades de textos

Las propiedades para manipular los textos y tipografía son los siguientes:

* ```font-size```: establece un tamaño de fuente.
* ```font-weight```: establece el resaltado del texto, con valores de 100 a 900 en intervalos de 100; donde 100 es delgada y 900 es negrita.
* ```font-family```: establece el tipo de fuente.
* ```text-align```: establece la posición del texto: right, left, center y justify.
* ```color```: establece el color del texto.

## Bordes redondeados

La propiedad que establece bordes redondeados es: ```border-radius```.

[Ejemplo de bordes redondeados](https://codi.link/PGRpdiBjbGFzcz0iYm9yZGVyIj48L2Rpdj4NCjxkaXYgY2xhc3M9ImNpcmNsZSI+PC9kaXY+%7CZGl2IHsNCiAgd2lkdGg6IDIwMHB4Ow0KICBoZWlnaHQ6IDIwMHB4Ow0KICBiYWNrZ3JvdW5kLWNvbG9yOiBicm93bjsNCiAgbWFyZ2luOiAyMHB4Ow0KICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7DQp9DQoNCi5ib3JkZXJ7DQogIGJvcmRlci1yYWRpdXM6IDM1cHg7DQp9DQoNCi5jaXJjbGV7DQogIGJvcmRlci1yYWRpdXM6IDUwJTsNCn0NCg0KDQo=%7C)


# Unidades de medida

Las unidades de medida establecen una longitud para un determinado elemento o tipografía. Existen dos tipos de medidas: absolutas y relativas.

![](img/frontend_developer29.png)

## Qué son las medidas absolutas

Las medidas absolutas son valores fijos, por lo que la medida no cambiará. La unidad absoluta más utilizada son los píxeles ```px```, las demás son muy poco utilizadas, pero es bueno que las conozcas.


| Unidad        | Nombre           | Equivalencia  |
| ------------- |:-------------:| -----:|
| px            | píxeles       | 1 px = 1/96 in |
| cm    | centímetros      |   1 cm = 96/2.54 px |
| mm  |  milímetros      |    1 mm = 1/10 cm |
| Q    | cuartos de milímetros      |   1 Q = 1/4 mm |
| in  |  pulgadas      |    1 in = 2.54 cm = 96 px |
| pc    | picas     |   1 pc = 1/6 in |
| pt  |  puntos      |    1 pt = 1/72 in |

## Qué son las medidas relativas
Las medidas relativas son valores variables, por lo que la medida depende de un valor externo. Se debe tener en cuidado con estas porque un pequeño cambio puede desencadenar tamaños muy elevados.



| Unidad        | Depende de           |
| ------------- |:-------------:|
| em            | el elemento que lo contiene       | 
| rem    | el elemento raíz      | 
| vw  |  1% del ancho de la pantalla (view width)      | 
| vh    | 1% de la altura de la pantalla (view height)     | 
| vmin  |  1% de la dimensión más pequeña de la pantalla      | 
| vman    | 1% de la dimensión más grande de la pantalla     | 
| ch  |  anchura del caracter “0” del elemento que lo contiene      | 
| lh  |  altura de la línea del elemento que lo contiene     | 

## Diferencia entre rem y em

La medida ```em``` depende del elemento que lo contiene, es decir, si un elemento tiene ```font-size``` de ```20px```, el valor de ```em``` es igual a ```20px```, el valor de ```2em``` será de ```40px``` y así sucesivamente.

La medida rem depende del elemento raíz, el valor del font-size del elemento raíz es de ```16px```, por lo tanto, el valor de ```2rem``` es igual a ```32px```, y así sucesivamente.

[Ejemplo de medida em](https://codi.link/PGRpdiBjbGFzcz0ibml2ZWwxIj4NCiAgPHA+TGV0cmEgZGUgMjBweDwvcD4NCiAgPGRpdiBjbGFzcz0ibml2ZWwyIj4NCiAgICA8cD5MZXRyYSBkZSAyMHB4PC9wPg0KICAgIDxkaXYgY2xhc3M9Im5pdmVsMyI+DQogICAgICA8cD5MZXRyYSBkZSA0MHB4PC9wPg0KICAgICAgPGRpdiBjbGFzcz0ibml2ZWw0Ij4NCiAgICAgICAgPHA+TGV0cmEgZGUgODBweDwvcD4NCiAgICAgIDwvZGl2Pg0KICAgIDwvZGl2Pg0KICA8L2Rpdj4NCjwvZGl2Pg==%7CKiB7DQogIG1hcmdpbjogMDsNCn0NCg0KLm5pdmVsMSB7DQogIC8qIFB1ZWRlcyBjYW1iaWFyIGVzdGUgdmFsb3IgKi8NCiAgZm9udC1zaXplOiAyMHB4Ow0KfQ0KDQoubml2ZWwyIHsNCiAgLyogdGFtYcOxbyA9IDIwcHggKiAxID0gMjBweCAqLw0KICBmb250LXNpemU6IDFlbTsNCn0NCg0KLm5pdmVsMyB7DQogIC8qIHRhbWHDsW8gPSAyMHB4ICogMiA9IDQwcHggKi8NCiAgZm9udC1zaXplOiAyZW07DQp9DQoNCi5uaXZlbDQgew0KICAvKiB0YW1hw7FvID0gNDBweCAqIDIgPSA4MHB4ICovDQogIGZvbnQtc2l6ZTogMmVtOw0KfQ0KDQoNCg==%7C)

En las herramientas del desarrollador, te muestra el tamaño de la fuente (font) en píxeles.

![](img/frontend_developer30.png)

[Ejemplo de medida rem](https://codi.link/PGRpdiBjbGFzcz0ibml2ZWwxIj4NCiAgPHA+TGV0cmEgZGUgMjBweDwvcD4NCiAgPGRpdiBjbGFzcz0ibml2ZWwyIj4NCiAgICA8cD5MZXRyYSBkZSAxNnB4PC9wPg0KICAgIDxkaXYgY2xhc3M9Im5pdmVsMyI+DQogICAgICA8cD5MZXRyYSBkZSAzMnB4PC9wPg0KICAgICAgPGRpdiBjbGFzcz0ibml2ZWw0Ij4NCiAgICAgICAgPHA+TGV0cmEgZGUgMzJweDwvcD4NCiAgICAgIDwvZGl2Pg0KICAgIDwvZGl2Pg0KICA8L2Rpdj4NCjwvZGl2Pg==%7CLm5pdmVsMSB7DQogIC8qIFB1ZWRlcyBjYW1iaWFyIGVzdGUgdmFsb3IgKi8NCiAgZm9udC1zaXplOiAyMHB4Ow0KfQ0KDQoubml2ZWwyIHsNCiAgLyogdGFtYcOxbyA9IDE2cHggKiAxID0gMTZweCAqLw0KICBmb250LXNpemU6IDFyZW07DQp9DQoNCi5uaXZlbDMgew0KICAvKiB0YW1hw7FvID0gMTZweCAqIDIgPSAzMnB4ICovDQogIGZvbnQtc2l6ZTogMnJlbTsNCn0NCg0KLm5pdmVsNCB7DQogIC8qIHRhbWHDsW8gPSAxNnB4ICogMiA9IDMycHggKi8NCiAgZm9udC1zaXplOiAycmVtOw0KfQ0KDQoNCg==%7C)

## Diferencia entre porcentajes y la anchura y altura de la pantalla

Los porcentajes representan el tamaño con respecto al total del elemento padre. Si el elemento padre tiene ```20px```, entonces el ```100%``` será de ```20px```.

Por otra parte, las medidas de anchura ```vw``` y altura ```vh``` representan el tamaño con respecto al total de la pantalla. Si el elemento tiene un tamaño de ```100vw``` será el ```100``` por ciento de la pantalla.

Si un elemento tiene todo el tamaño de la pantalla, entonces solamente en ese punto la medida ```100%``` será igual a ```100vw``` o ```100vh```.

## Problema con las medidas de texto

Los navegadores tienen una opción para cambiar el tamaño del texto. Con medidas absolutas, el tamaño de la letra no cambiará, por lo que será un problema para el usuario.

Con medidas relativas, el tamaño cambiará con respecto a la fuente del elemento raíz. Por lo que estas son una buena opción para solucionar este problema de accesibilidad, en específico la medida ```rem```.

Sin embargo, la medida ```rem``` equivale a ```16px``` y puede ser confuso mientras utilices valores altos. Por lo que vamos a cambiar el valor del elemento de la raíz para que la medida rem sea igual a 10px.

En la etiqueta ```<html>``` cambia el valor de la propiedad ```font-size``` a ```62.5%```, resultado de una regla de tres: si ```16px``` es igual al ```100%``` entonces cuál será el porcentaje para ```10px```.

```css
html {
    font-size: 62.5%;
}
```

Con este cambio, la medida ```rem``` será igual a ```10px```, ahora los puedes utilizar sin problema y tus textos cambiarán según las preferencias de usuario.

# Responsive Design

El diseño responsivo (Responsive Design) consiste en un conjunto de herramientas para que tu sitio se vea bien en varias medidas de pantalla, esto incluye imágenes, tipografía, internacionalización de la página y entre otros.

En la actualidad, la mayoría de sitios web son visitados desde un celular, por lo que asegurarse que nuestro sitio sea responsivo para cualquier dispositivo es fundamental para optimizar las ganancias.

## Qué son las media queries

Las media queries son reglas CSS que establecen un comportamiento distinto o diferentes estilos en un cierto rango de la pantalla. Esto sirve para establecer el layout del sitio web para diferentes tipos de pantalla: escritorio, tablets y celulares.

* ```max-width / max-height```: establece un rango máximo para cierto comportamiento.
* ```min-width / min-height```: establece un rango mínimo para cierto comportamiento.
Estos valores son parecidos a condicionales, mientras se cumpla la condición, aplica determinados estilos.

### Estructura de la media querie

La estructura de una media querie consiste en empezar con ```@media```, seguido del tipo de la media querie estableciendo un rango, envolviendo las reglas CSS dentro de ese rango.

![](img/frontend_developer31.png)

```css
@media (max-width:750px){
    div {
        color: red;
    }
    p {
        background-color: red;
    }
}
```

#### Herramientas del desarrollador para media queries

Para observar que los cambios se estén aplicando correctamente, las herramientas de desarrollador serán de gran ayuda.

Abre las herramientas del navegador y da clic en la opción “Toggle device tool”, aquí podrás manipular la pantalla y observar en cuántos píxeles está ocurriendo determinados estilos.

![](img/frontend_developer32.png)

Utiliza el siguiente ejemplo para visualizar cómo cambian los estilos según la longitud de la pantalla. Puedes revisar la media querie que está en el código. Aunque solo cambien el color de dos elementos, puede estar cualquier propiedad que desees, prueba con todo.

[Ejemplo de media queries](https://codi.link/PGRpdiBjbGFzcz0iY2FyZDEiPjwvZGl2Pg0KPGRpdiBjbGFzcz0iY2FyZDIiPjwvZGl2Pg0KDQo=%7CKiB7DQogIG1hcmdpbjogMDsNCiAgcGFkZGluZzogMDsNCiAgYm94LXNpemluZzogYm9yZGVyLWJveDsNCn0NCg0KYm9keSB7DQogIHdpZHRoOiAxMDB2dzsNCiAgaGVpZ2h0OiAxMDB2aDsNCn0NCg0KLmNhcmQxew0KICB3aWR0aDogMTAwJTsNCiAgaGVpZ2h0OiAyNSU7DQogIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KfQ0KDQouY2FyZDIgew0KICB3aWR0aDogNTAlOw0KICBoZWlnaHQ6IDc1JTsNCiAgYmFja2dyb3VuZC1jb2xvcjogY2hhcnRyZXVzZTsNCn0NCg0KQG1lZGlhIChtaW4td2lkdGg6IDUwMHB4KXsNCiAgLmNhcmQxIHsNCiAgICAgIGJhY2tncm91bmQtY29sb3I6IGNoYXJ0cmV1c2U7DQogIH0NCg0KICAuY2FyZDIgew0KICAgIGJhY2tncm91bmQtY29sb3I6IGJyb3duOw0KICB9DQp9DQoNCg==%7C)

# ¿Qué son las arquitecturas CSS? ¿Para qué sirven?

Las arquitecturas CSS consisten en manejar el código CSS con una serie de reglas y patrones para facilitar su lectura, mantenibilidad y escabilidad.

El código que has manejado no se asemeja a la realidad, pues deberás manejar varios cientos o miles de líneas de código. Las arquitecturas CSS se encargan de manejar una norma en el código para que cualquiera pueda añadir o quitar funcionalidad sin mucho trabajo.

![](img/frontend_developer33.png)

## Objetivos de las arquitecturas de CSS


Los objetivos de las arquitecturas de CSS son:

* ```Ser predecible```: el código debe ser lo menos complejo posible.
* ```Reutilizable```: el código debe ser lo menos redundante, para evitar problemas con la especificidad.
* ```Mantenible```: el código debe ser lo más fácil de manejar para añadir o quitar estilos.
* ```Escalable```: el código debe ser capaz de crecer.

## Buenas prácticas de las arquitecturas de CSS

Las buenas prácticas de las arquitecturas de CSS son:

* ```Lineamientos y estándares```: definir normas en tu grupo de trabajo de cómo estará escrito el código.
* ```Documentación```: establecer una breve explicación del código y de los lineamientos, esto sirve especialmente para nuevas personas se familiaricen con lo que deben hacer.
* ```Componentes```: establecer de manera componetizada cada uno de los elementos de tu página, es decir, manejarlos por partes para después unirlos en un todo.
