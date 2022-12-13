# Proyecto Línea de Comandos

## Ejercicio 1. 
Ingrese al directorio ```thecmdchallenge/```

1. Utilizo ```dirs``` para saber en qué carpeta estoy. Estoy en ```/workspace/exercise-terminal-challenge```.
2. Utilizo el comando ```cd thecmdchallenge/``` para entrar a la carpeta indicada.
3. Utilizo ```dirs``` para saber en qué carpeta estoy. Ya estoy en ```/workspace/exercise-terminal-challenge/thecmdchallenge```

## Ejercicio 2.
Imprimir la ruta del directorio actual

1. Utilizo ```dirs``` para saber en qué carpeta estoy. Ya estoy en ```/workspace/exercise-terminal-challenge/thecmdchallenge```
2. Copio la ruta en la que me encuentro y utilizo el comando ```echo /workspace/exercise-terminal-challenge/thecmdchallenge ```

## Ejercicio 3.
Enumere todos los archivos del directorio actual, incluidos los ocultos

1. Utilizo el comando ```ls --all```. Luego me aparecen todos los archivos, incluidos los ocultos.

## Ejercicio 4.

Ahora enumere todos los archivos dentro del proyecto, recursivamente (todos los archivos en la jerarquía).

1. Utilizo el comando ```cd ..``` para ir una carpeta atrás, que sería la principal del proyecto.
2. Utilizo el comando ```ls --all``` para que se listen todos los archivos de la carpeta en la que me encuentro (la principal del proyecto).

## Ejercicio 5.
Borrar todo el desorden desde la línea de comando

1. Utilizo el comando ```clear``` para limpiar la línea de comandos.

## Ejercicio 6.
Vaya al último nivel debajo de la carpeta ```small-name``` y muestre en la consola el contenido del archivo trophy.txt.

1. Utilizo el comando ```find -name trophy.txt``` para conocer la ruta completa en la que se encuentra el archivo.
2. Utilizo ```nano ./thecmdchallenge/small-name/bigger-name-than-before/omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious/trophy.txt``` para visualizar el contenido.


## Ejercicio 7.
Suba un nivel y acceda al directorio funcode y enumere todos los archivos con la extensión típica de javascript.

1. Busco la carpeta "funcode" con el comando ```find -name funcode```.
2. Copio la ruta que me aparece para poder ir a ese directorio, utilizando ```cd ./excercise-terminal-challenge/thecmdchallenge/funcode```
3. Utilizo el comando ```ls```.

## Ejercicio 8.
Cree un nuevo directorio dentro de funcode/the-most-funny/ llamado “not-tan-funny“

1. Voy al directorio "the-most-funny" con el comando ```cd the-most-funny```, ya que estaba en el directorio padre.
2. Utilizo el comando ```mkdir ./excercise-terminal-challenge/thecmdchallenge/funcode/the-most-funny/ llamado “not-tan-funny```.

## Ejercicio 9.

Cree una copia de the-mostboring-text.txt (puede encontrarlo dentro de los elementos secundarios de /boringfolder/) y asígnele el nombre lol.txt.

1. Busco el archivo ```the-mostboring-text.txt``` con el comando ```find -name the-mostboring-text.txt``` para obtener la ruta completa.
2. Utilizo el comando ```cp ./boringfolder/the-mostboring-text.txt ./boringfolder/lol.txt ```.

## Ejercicio 10.


Mueve funcode/kids.jpg dentro de funcode/images/hello/

1. Utilizo el comando ```mv funcode/kids.jpg funcode/images/hello/```.

## Ejercicio 11.

Elimine el directorio "small-name".

1. Utilizo el comando ```rm -r small-name```.
2. Luego elimino el directorio ya vacío con el comando ```rmdir small-name```.

## Ejercicio 12.
Imprime en la línea de comando el contenido de the-ultimate-joke.txt.

1. Utilizo el comando ```find -name the-ultimate-joke.txt``` para conocer la ruta del archivo.
2. Luego utilizo ```nano ./lol/the-ultimate-joke.txt```

## Ejercicio 13.

Elimina todo el contenido de la carpeta "boringfolder", son extremadamente aburridos…

1. Utilizo el comando ```rm -r boringfolder```.

## Ejercicio 14.
Abra el archivo kamehameha/dragon-ball-jokes.md usando el editor de texto de línea de comando VI

1. Entro a la carpeta kamehameha y utilizo el comando ```dragon-ball-jokes.md```.
