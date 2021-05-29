# platzi-projects

### Recap Programación básica

 HTML (Lenguaje de marcas de hipertexto), es el lenguaje donde se define la información o el contenido del documento. El formato de los archivos es .html.

CSS (Lenguaje de estilos en cascada), es el lenguaje donde se especifica el diseño del documento, maneja todo lo relacionado con la parte visual. El formato de los archivos es .css.

JavaScript, es el lenguaje que hace que todo sea interactivo y que nos permite crear sitios web El formato de los archivos es .js. Además, es el lenguaje de programación que interpreta el navegador.

 Una variable es un elemento que se emplea para almacenar y hacer referencia a otro valor. Gracias a las variables es posible crear “programas genéricos”, es decir, programas que funcionan siempre igual e independientemente de los valores concretos utilizados.

 ### primera linea de codigo

 alert ("Mi nombre es mabiel")
 so sirve para dar un aviso
 este curos nos enseña mas bien a declarar variables...

 ### JavaScript no es Java

 Java es un lenguaje para servidores, aplicaciones de escritorio y aplicaciones Android

JavaScript es el lenguaje de la web, servidores, robots, etc

### Primeros pasos en el navegador con alert

alert('Hola mamá, estoy programando');
Lo que has hecho es ejecutar una función, estas son colecciones de código que hacen algo, en JS siempre que quieres ejecutar una debes escribir paréntesis de apertura y de cierre, las comillas delimitan un texto (string) y punto y coma (;) se utiliza para terminar la instrucción.

También, podemos crear operaciones básicas,

var x = 1;

var y = 2;

var z = x + y;

Hemos declarado variables, las declaramos con la palabra reservada var, el nombre, operador de asignación (=) y el valor que va a tener.

### HTML, CSS, JavaScript de verdad

Los archivos HTML funciona con etiquetas, por ejemplo

Hola mamá *ya casi aprendo*

Todos los contenidos en HTML deberían estar dentro de una etiqueta, y todos los archivos HTML tienen esta estructura, cómo

<title>Título de la página</title>

Contenido de la página

La etiqueta que te permite escribir CSS dentro de HTML es <style>, se coloca dentro de head. La etiqueta para escribir JS dentro de HTML es <script>, se coloca antes de terminar el body.


### Obteniendo datos del usuario
cosas que tengo que tener en cuenta al momento de interactuar  con lo de esta parte del curso

La consola nos sirve para saber el estado de las variables
 
Cuando tienen un valor en comillas("") es un texto
 
Puedes usar la función prompt para recibir datos del usuario.
 
Concatenar es unir cadenas de texto a variables

### Flujo y condicionales

Para escribir una condicional usas la palabra reservada if, puedes escribir una como

if (planeta == 1)

{

// Código si la condición se cumple

}

else

{

// Código si la condición no se cumple

}

Si quisiéramos tener tener varias condiciones podemos escribir nuevas condiciones con la palabra reservada else if

if (planeta == 1)

{

// Código si la condición se cumple

}

else if (planeta == 2)

{

// Código si la segunda condición se cumple

}

else

{

// Código si las condiciones no se cumplen

}

### El DOM: nuestro lugar de trabajo en la web

n programación existen objetos, estos son como envolturas para código, el navegador tiene algunos nativos cómo:

navigator: El objeto que contiene las funciones del navegador, también te permite acceder también al sistema operativo como el gps, guardar datos en el disco duro, etc.

window: El objeto que maneja cada una de las pestañas.

document: El objeto que contiene todo lo que vemos dentro de nuestra página

### Cómo funcionan Window y Document

Los objetos contienen

Métodos: funciones dentro de un objeto
Atributo o propiedad: variables internas que almacenan valores

 ### Dibujando en el DOM
 Para dibujar usamos JS para darle las instrucciones y los canvas funcionan con coordenadas

Solamente llegando al canvas no podemos dibujar, debemos crear un contexto, ahora sí, mira cómo dibujar con HTML y JavaScript
y tenemos que recordar que ID es el identificador con el que podemos encontrar etiquetas con JavaScript, los nombres siguen las mismas reglas que las variables
 
Puedes obtener un elemento con su id buscándolo con document.getElementById('nombre_id');

### Funciones en JavaScript

La funciones son una herramienta que nos permite escribir código que vamos a re-usar múltiples veces,

Puedes escribir una función en JavaScript así:

function nombreFuncion(parametros) {

 //Código que ejecuta la función

}
 
cómo crear una función con la que puedas crear las líneas que necesites.