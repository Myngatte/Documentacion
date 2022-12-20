# Documentacion 

## Lo básico de Markdown

#=encabezado ,cantidad de #= nivel de encabezado ej:
# encabezado
###### encabezado 2
Solo se pueden hasta 6 #

*(palabra)* o _(palabra)_ =palabra en cursiva
**(palabra)** o __(palabra)__= palabra en negrita
Se pueden juntar ***(palabra)*** o ___(palabra)___

*/- más espacio(tecla) =  enlistar
* hola
* dsamd
- hey
- jsad

Lo siguiente remarcará el texto:
 ````html
(texto marcado)
````

[link](URL "texto alternativo") = formato para links

![link](URL "texto alternativo") = formato para poner imagenes

Creación de tabla:
| Encabezado1 | Encabezado2 | Encabezado 3|

|---------- |   |:------------:|  |--------:| (Formato de tabla)

(izquierda)    (medio)    (derecha)

Ej:

| Encabezado1 | Encabezado2 | Encabezado 3|
|---------- |:------------:|--------:|
| Item1 | Bolgrafos | 1000 euro|
| Item2 | grapadors | 20 euro |
| Item3 | lapis | 150 euro|

# *Comandos de git*

“git init”: notifica a git que este directorio es un repositorio. Internamente crea un directorio .git

“git clone”:
Usado para clonar repositorios.

Uso: git clone (link)

“git add”:
Añadir que quieres subir a github, pero no lo hará. Paso principal para subir cosas a la plataforma git, pero repito, no hará nada sin “git commit -m”.

“git commit -m”: 
Le da un nombre a la versión que se sube. 

Uso: git commit -m “(texto)”

“git push”:
Añadir de forma definitiva lo que querías subir en “git add”

Uso: git push origin(rama repositorio local) main(rama remoto)

# *Documentación básica de html*

Formato usual de html que usamos : comenzar proyecto con “html:5"

lang = lenguaje

Este comando se hace escribiendo “link:favicon”, este cambia el icono de la página web

Se escriben subtítulos, de números enteros, siendo h1 la letra más grande, y cuando más grande el número más pequeño será el texto de dentro, sirve para poder diferenciar y priorizar temas.


Para poner imagenes, src=se pone el link de la imagen, es decir su ubicación, “img/” se refiere a la carpeta donde esta, se debe escribir dependiendo de su ubicación de manera recursiva, después se escribe el nombre de la imagen
“alt=” es un alternativo en caso de que la imagen falle.

Para escribir texto poner dentro de 

Definir formato de pagina con

“head” usado para título y encabezado de página(lo que sería equivalente a la presentación) y “body” usado para el resto(contenido, fotos, links, etc), como la división en una redacción.

# ApuntesCSS

Un archivo ``CSS`` hace posible editar para darle un toque estético a tu página web

Para comenzar a hacer estilos, primero creamos una carpeta "CSS" con un archivo ".css" 

Para poner a uso estos estilos debemos vincular el archivo ".css" con el archivo al cual le queremos poner los estilos con ``link``

Para poder vincularlo correctamente, en el ``src`` del ``link`` hay que poner la ubicación del archivo como si fuese una imagén

Ej: link rel="stylesheet" href="mystyle.css"

También podemos añadir o cambiar la fuente del texto, tan solo debemos ir a la pagina oficial de ``Google fonts`` y copiar el link/comandos de la fuente el cual queremos usar, y vincularlo 

#Dentro del CSS
- Selectores
A la hora de poner estilos hay que elegir "qué", en concreto,
Tenemos:
- ``*`` Como selector universal, es decir, que coje todo.
- ``xxxxx.class`` Para seleccionar una clase 
- ``Etiqueta`` Seleccionar la etiqueta, ejemplo: ``h1``
- ``#`` Para elegir objetos con ``id``, id es un identificador que le puedes poner a cualquier texto en concreto, imagenes, etc. Se pone con ``id=""``

Una vez se haya seleccionado el selector, los estilos se deben poner de esta forma:

``(Selector)`` {

    (lo que quieres hacer);

}


En los estilos que hemos aprendido estan:

### ``Padding``

Lo que seria la sangría, es decir el margen

### ``Backgrounds``

Para editar el fondo

### ``Borders``

Para añadir o editar bordes

### ``Height/Width``

Tal cual como su traducción al español, hacen referencia a la anchura y la altura
