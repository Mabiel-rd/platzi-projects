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

### Ciclos while y for en JavaScript

Al ejecutar el VI, se ejecuta el código dentro del ciclo While y luego se evalúa la condición de la terminal. ... A diferencia de un ciclo For, la ejecución del ciclo While no depende de la cantidad de iteraciones; por lo tanto, un ciclo While se ejecuta indefinidamente si la condición nunca ocurre.

Otro concepto fundamental en programación son los ciclos,
Los ciclos son piezas de código que se repiten hasta que se cumple una condición

### Eventos y Formularios en HTML y JavaScript

Los eventos son funciones que suceden cuando algo ocurre,  sucesos cómo un click, pulsar una tecla, colocar el mouse sobre un botón, etc.

Creemos un programa que reciba la cantidad de líneas con las que queremos crear nuestra imagen.

tenemos que recordar que Cuando queremos enviar información a un servidor podemos usar un formularios

En JavaScript puedes agregar un manejador de eventos con element.addEventListener('event', function)

### Detectar eventos del teclado con JavaScript

Podemos hacer que nuestro dibujo reaccione al teclado, primero debemos aprender a detectar eventos del teclado.

 Recordemos que un programador divide los grandes problemas en problemas más pequeños.
 
Todo manejador de eventos devuelve un objeto con los detalles del evento

### Funciones matemáticas y números aleatorios en JavaScript

cosas importantes que tenemos que saber 

Math.floor() devuelve el número entero por debajo de los decimales.

Math.ceil() devuelve el siguiente número entero arriba de los decimales

Math.random() devuelve un número aleatorio de 0 a 0.999..

### Uso y carga de imágenes en Canvas

En canvas puedes insertar imágenes, hagámoslo con nuestra villa platzi.

tenemos que tener en cuenta que Debemos agregar la imagen en el evento load del objeto.
 
Debemos usar el método .drawImage del canvas para insertar la imagen.

Canvas dibuja siempre encima del último objeto.

### División, módulo y residuo en JavaScript

Cuando te presentas a un trabajo de programador tal vez debas resolver un problema llamado fizzbuzz, este busca conocer tus conocimientos, veamos cómo resolverlos

Primero debes conocer cómo calcular el residuo de una división, ahora puedes llevar esto a código

estas son las  cosas que tenemos que tomar en cuenta
Para calcular el módulo puedes usar % tambien que Los programas dividen los programas complejos en problemas pequeños y tambien queLa operación lógica and (y) se escribe en JavaScript con &&.


