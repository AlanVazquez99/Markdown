MarkDown
===
Indice
---
+ [Elementos basicos](#Elementos-basicos)
    + [Titulos](#Titulos)
    + [tipografia](#Tipografia)
    + [Parrafos](#Parrafos)
        + [Mas de un parrafo](#Mas-de-un-parrafo)
    + [Listas](#Listas)
        + [Anidacion de Listas](#Anidacion-de-listas)
        + [Enumeraciones](#Enumeraciones)
+ [Mas elementos de texto](#Mas-elementos-de-texto)
    + [Citas](#Citas)
    + [Tablas](#Tablas)
        + [Otros usos de las tablas](#Otros-usos-de-las-tablas)
    + [Enlaces](#Enlaces)
        + [Enlaces de imagenes](#Enlaces-de-imagenes)
    + [Caracteres especiales](#Caracteres-especiales)
+ [Codigo](#Codigo)
    + [Escribiendo codigo](#Escribiendo-codigo)
    + [Resaltado de sintaxis](#Resaltado-de-sintaxis)
        + [python](#python)
        + [javascript](#javascript)
    + [Inclusion de codigo de texto](#Inclusion-de-codigo-de-texto)
___


___
<br><br><br>

# Elementos basicos
## Titulos

###### Header 6
##### Header 5
#### Header 4
### Header 3
## Header 2
# Header 1
Header 1 
======== 
Header 2
--------
<br>

___
## Tipografia
_italicas_ y __negritas__

*italicas* y **negritas**

**_negrita e italica_** o __*alternativamente*__ o ***tambien asi***, ___incluso asi___

`tipo terminal: codigo terminal`

~~tachado~~

Subindices y superindices: SO<sub>4</sub><sup>=</sup>

<br>

## Parrafos
Esto es un parrafo. Lorem ipsum dolor sit amet, consectetur
adipiscing elit. Donec nec nisi a sem porta ornare ac a nulla.
Pellentesque consectetur viverra neque. Nullam et erat a mauris
fringilla vulputate.

Este es otro. Cras porta magna at sapien mollis pharetra. Duis
hendrerit scelerisque lectus, eget pellentesque erat volutpat vel.
Nulla eget viverra sem, sed pharetra orci. Etiam a iaculis leo. Ut
viverra eleifend tortor.

<br>

### Mas de un parrafo
1. Esto es un parrafo. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nec nisi a sem porta ornare ac a nulla.
Pellentesque consectetur viverra neque.
    
    Este es otro. Cras porta magna at sapien mollis pharetra.
Duis hendrerit scelerisque lectus, eget pellentesque erat volutpat vel.

2. Este es otro item.

<br>

## Listas
* Es facil hacer una lista de items
- añadiendo otro
+ y otro mas

<br>

### Enumeraciones
1. Una lista numerada
2. tambien es facil
3. un numero, un punto y un espacio.
1. No importa el valor...

<br>

### Anidacion de listas
1. Lista numerada con subıtem
    * No olvidar la regla
    1. de los 4 espacios
    1. pero seamos sistematicos
2. Para terminar


<br><br><br>


# Mas elementos de texto
## Citas

    Pueden utilizarse tal como se hace en los mensajes de correo electronico (para indicar el momento en que se remite el texto).

        Y claro, puede anidarse sin problemas.

            Con varios niveles. . .

<br>

## Tablas

| left  | center | right |
| :---  | :----: | ----: |
| Celda | x      | x     |
| x     | Cell   | $200  |


right  | center | left
-----: | :----: | :----
Celda  | x  	| $10  
x      | $20    | x

Los "|" externos son opcionales

Los dos puntos se utilizan para determinar la alineacion

<br>

### Otros usos de las tablas
| Uso de markdown | Justificacion |
| --------------- | ------------- |
Para no iniciados | Cuando los usuarios no son usuarios avanzados de software para creacion de documentos. 
Creacion de borradores | Para trabajar despreocupados de aspectos formales, pero siendo precisos

<br>

## Enlaces
[GitHub: AlanVazquez](https://github.com/AlanVazquez99/ "Comentario sobre el enlace")
<https://github.com/AlanVazquez99/>
 
Es posible definir el [Enlace] para hacer mas legible el texto, o tener dos versiones de un mismo texto cambiando solo los enlaces, hablamos obviamente de un hiper[enlace].

No hay sensibilidad a mayusculas. Puede haber mas de una palabra.

[enlace]: http://es.wikipedia.org/wiki/Hiperenlace "Hiperenlace"

<br>

### Enlaces de imagenes
![Daff Steel](images/logo.png "logo de daffsteel")
![logo]

[logo]: images/logo.png "enlace definido en otro lugar"

<br>

## Caracteres especiales
* Contra barra y espacio: \\ 
* Tilde grave: \``
* Asterisco y barra baja: \* \_
* Parentesis: \{\} \[\] \(\)
* Sostenido: \#
* Otros: \+ \- \. \! \: \|

<br>

## Lıneas horizontales
___
---
***
_ _ _ _ 
- - - -
* * * *

<br>

## Comentarios
Aquı hay un comentario

<!-- Esto es un comentario --> 
<br><br><br>

# Codigo
## Escribiendo codigo
~~~
    Codigo
    aqui
~~~

<br>

## Resaltado de sintaxis
### python
```python
import lifetime
for each_day in lifetime.days():
carpe_diem()
```
### javascript
```javascript
const express = require('espress');
var app = express();

app.listen(3000, function () {
  console.log('Servidor = http://localhost:3000');
});
```
<br>

## Inclusion de codigo de texto
html, cuando el destino final sea un fichero .html

Es posible <b>utilizar</b> marcas de html