# my_first_repo
El README es el archivo en el cual hacemos la descripción del proyecto, ya sea open source o privado. Es importante tener un buen archivo README, ya que este lista todas las instrucciones y dependencias para ejecutar correctamente nuestro proyecto

## Que es Markdown
Es un formato de escritura que permite la generación de contenido fácil y rápido, permite generar una salida (por lo general) en formato HTML sin necesidad de aprender a profundidad el lenguaje HTML. Es ampliamente utilizado por su facilidad de generar texto enriquecido. Su extensión es .md

## Encabezados
Lo utilizamos para resaltar una parte importante, títulos, subtítulos, etc. Se utiliza el símbolo # para demarcar el inicio de un encabezado. Existen 6 niveles que se corresponden con la cantidad de # utilizados.

## Párrafos
En formato Markdown escribirlos no es tan distinto a escribir en un texto plano, automáticamente se reconoce que es un párrafo, por ejemplo: JavaScript es un lenguaje muy poderoso.

## Itálicas y Negritas
Hay partes en las que necesitaremos hacer énfasis en ciertas palabras, lo común es que utilicemos itálicas y negritas para resaltarlas, en Markdown debemos encerrar el texto con * para itálicas, ** para negritas, **_ para ambas

+ **Esto es una negrita**
+ *Esto es una cursiva*
+ **_Esto es una negrita cursiva_**

## Citas
Se utilizan para mostrar referencias a otros autores, se emplea el símbolo > para iniciar una cita

> ### Mensaje del autor
> hola gracias por utilizar mi proyecto.

## Listas
Podemos utilizar listas ordenadas (anteponiendo el número) y listas sin orden (anteponiendo un - ):

1. Laravel
2. JavaScript
3. HTML
4. CSS
5. VueJS
6. PHP

- Trabajar con algún Framework de PHP es lo máximo
- JQuery no esta muerto, solo es para conocedores y no fanfarrones.
- VSCode es lento pero tiene mayor soporte

## Bloques de información
Delimitar por 3 ~ virguilillas
~~~
Esto es un bloque de información
~~~ 

## Código
Es necesario tabular el contenido y en automático lo reconocerá como código, o delimintarlo con ``` para resaltarlo en sintaxis (añadiendo el nombre del lenguaje)
``` javascript
    var name = 'Escuela de JavaScript';
    console.log(name);
```

## Lineas Horizontales
Es como los hr en HTML, para ello es necesario colocar 3 de los siguientes elementos en una linea en blanco
***
---
___

### Enlaces
Se crean escribiendo el texto entre [] y el link entre ()
[Este enlace manda a google](http://www.google.com)

### Imágenes
Lo mismo que los enlaces, pero se antepone el !
![Texto alternativo](http://lorempixel.com/400/200/)

### Enlaces sin enmascarar
Es decir, no tienen un texto alternativo, muestra la url completa. para ello es necesario encerrar la url entre <>
<http://youtube.com>

### Tablas
Código | Nombre | Apellidos | Calificación | Colegiatura
-- | -- | -- | :--: | --:
00400 | Alejandro | Reyes Prieto | 9.8 | $1,000.00
54722 | Mariana | Fuentes Medina | 10.0 | $ 950.00
33512 | Nicanor | Huertas Valeriano | 8.2 | $1,000.00
22412 | Miguel | Villada Cejudo | 9.7 | $655.90

### Texto tachado
Delimitar el texto con dos virguirillas
Este ~~es un texto tachado~~ de la documentación

### Listas de definición

HTML
    : es un lenguaje informático de marcado de contenido
    : actualmente se encuentra en la versión 5
    : incluye muchas APIs para el trabajo con dispositivos móviles

CSS
    : es el lenguaje informático para la presentación de contenidos escritos principalmente en lenguaje HTML