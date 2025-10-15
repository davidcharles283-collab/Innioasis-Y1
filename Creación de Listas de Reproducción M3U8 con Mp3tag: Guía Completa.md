<!-- Autor: David charles -->
Crear listas de reproducción musicales en formato .m3u8 con el popular editor de metadatos Mp3tag es un proceso sencillo y eficiente. Este formato, a diferencia del .m3u tradicional, utiliza la codificación UTF-8, lo que garantiza la correcta visualización de caracteres especiales e internacionales en los nombres de los archivos y en los metadatos de las canciones.

A continuación, se detalla el procedimiento paso a paso para generar sus propias listas de reproducción .m3u8 utilizando Mp3tag.

## Paso 1: Agregar los Archivos de Música a Mp3tag
Antes de crear la lista de reproducción, es necesario cargar las canciones deseadas en el programa. Para ello, existen dos métodos principales:
  1. Arrastrar y soltar: Simplemente seleccione los archivos de música o las carpetas que los contienen desde el explorador de archivos de su sistema operativo y arrástrelos a la ventana principal de Mp3tag.
  2. Desde el menú "Archivo": Diríjase a Archivo > Añadir directorio... para seleccionar una carpeta completa de música. Mp3tag cargará todos los archivos de audio compatibles que se encuentren en ella y en sus subdirectorios.

## Paso 2: Organizar el Orden de Reproducción
  1. Una vez que los archivos están cargados en Mp3tag, puede definir el orden en el que aparecerán en la lista de reproducción.
    Para reordenar las canciones, mantenga presionada la ```tecla Alt``` y, a continuación, haga ```clic``` y arrastre las pistas hacia arriba o hacia abajo en el listado hasta alcanzar la secuencia deseada.

## Paso 3: Configurar las Opciones de la Lista de Reproducción (Opcional)
Mp3tag ofrece una serie de ajustes para personalizar la creación de las listas de reproducción. Para acceder a ellos, vaya a ```Herramientas > Opciones > Lista de reproducción```. En esta sección, podrá configurar:
  1. Escribir información extendida: Si se activa, se incluirá en el archivo de la lista de reproducción información adicional como la duración y el título de la canción (```#EXTINF```), lo que permite que el reproductor muestre estos datos sin necesidad de leer las etiquetas del archivo de audio.
  2. Entradas relativas al directorio de trabajo: Esta opción permite crear rutas de archivo relativas en lugar de absolutas, lo que puede ser útil si planea mover la lista de reproducción y los archivos de música juntos a otra ubicación.
  3. Crear lista de reproducción automáticamente: Permite generar una lista de reproducción de forma automática al guardar las etiquetas de los archivos.

## Paso 4: Generar la Lista de Reproducción .m3u8
Con los archivos cargados y organizados, el siguiente paso es crear el archivo de la lista de reproducción:
  1. Diríjase al menú ```Archivo > Lista de reproducción (archivos seleccionados)...``` si desea incluir únicamente las canciones que tiene seleccionadas, o ```Archivo > Lista de reproducción (todos los archivos)...``` para incluir todas las canciones cargadas.
  2. Se abrirá un cuadro de diálogo para guardar el archivo. En el campo "Nombre de archivo", escriba el nombre que desee para su lista de reproducción y, fundamentalmente, añada la extensión ```.m3u8``` al final. Por ejemplo: ```Mi Playlist de Rock.m3u8```.
  3. Haga clic en ```"Guardar"```.

Al utilizar la extensión ```.m3u8```, Mp3tag generará automáticamente el archivo con la codificación UTF-8, asegurando así la compatibilidad con caracteres especiales y acentos en los nombres de archivo y metadatos.

## Creación de Múltiples Listas de Reproducción
Para situaciones en las que se necesite crear varias listas de reproducción de forma masiva, por ejemplo, una por cada carpeta de álbum, Mp3tag ofrece una herramienta muy útil:
  1. Vaya a ```Archivo > Generar listas de reproducción....```
  2. En la ventana que aparece, puede definir un patrón para el nombre de archivo de la lista de reproducción y un formato para dividir los archivos en diferentes listas. Un caso de uso común es utilizar %_folderpath% para crear una lista de reproducción por cada subdirectorio.
  3. La vista previa le mostrará las listas de reproducción que se crearán.

Este método automatiza el proceso y es ideal para organizar grandes bibliotecas musicales de manera eficiente.
```Al final el archivo que de genera lo pones en la carpeta playlist y listo.```
