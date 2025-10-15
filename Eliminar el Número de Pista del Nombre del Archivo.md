<!-- Autor: David charles -->
## Eliminar el Número de Pista del Nombre del Archivo
### Si tus archivos están nombrados con el número de pista al principio (*ej. 01 - Nombre de la Canción.mp3*), puedes usar una de las funciones de Mp3tag para renombrarlos en lote.

1. Abre Mp3tag y carga tus archivos:
  Arrastra y suelta la carpeta que contiene todas las canciones a las que quieres quitarles el número de pista en la ventana principal de Mp3tag.
2. Selecciona todas las canciones:
  Una vez que los archivos estén cargados, haz clic en cualquiera de ellos y presiona Ctrl + A para seleccionarlos todos. Verás que todos los archivos se resaltan en azul.

3. Abre la herramienta "Convertir > Etiqueta - Nombre de archivo":
   3.1 Ve al menú superior y haz clic en "Convertir".
   3.2 En el menú desplegable, selecciona la opción "Etiqueta - Nombre de archivo" (o presiona Alt + 2).
4. Configura el formato del nuevo nombre:
  Se abrirá una nueva ventana. En el campo "Formato de cadena", debes especificar cómo quieres que se llame el archivo.
  Si tus archivos tienen un formato como Número de Pista - Título, el formato original podría ser algo como $num(%track%,2) - %title%.(<==== haciendo referencia a que tienes que escribir esto en el campo de texto)

5. Para eliminar el número de pista, simplemente borra la parte correspondiente a la pista. Por ejemplo, si solo quieres que el nombre del archivo sea el título de la canción, escribe en el campo:
  %title%
6. Si también quieres incluir el artista, puedes usar:
  %artist% - %title%
La clave es no incluir *%track%* en la nueva cadena de formato.

7. Previsualiza y aplica los cambios:
  La ventana te mostrará una vista previa de cómo se verá el nombre de archivo actual y cómo quedará el nuevo nombre. Revisa que esté correcto.
  Si estás satisfecho con la vista previa, haz clic en "Aceptar".

8. Confirma la operación:
  Mp3tag te pedirá confirmación antes de renombrar todos los archivos. Confirma la acción.
9. Final
  Mp3tag renombrará todos los archivos seleccionados según el nuevo formato que especificaste, eliminando así el número de pista del nombre del archivo.

> Nota: 
> Esto es un proceso tardado y puede llevar algún tiempo dependiendo de la cantidad de canciones que tengas no te desesperes
