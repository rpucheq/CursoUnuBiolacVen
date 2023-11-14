## Introducción a la línea de comandos
La línea de comandos es una forma de interactuar con el sistema operativo mediante texto, sin usar una interfaz gráfica. La línea de comandos te permite ejecutar programas, manipular archivos, navegar por directorios y realizar otras tareas usando una serie de instrucciones o comandos. La línea de comandos es especialmente útil para la bioinformática, ya que te permite procesar grandes cantidades de datos, automatizar tareas repetitivas y usar herramientas específicas para el análisis de secuencias, alineamientos, ensamblajes, anotaciones, etc.

## Acceso a la línea de comandos
Para acceder a la línea de comandos, necesitas abrir una terminal o una consola, que es una aplicación que te permite escribir y ejecutar los comandos. Dependiendo del sistema operativo que uses, la forma de abrir la terminal puede variar. Por ejemplo, en Windows puedes usar el programa CMD o PowerShell, en Mac OS puedes usar la aplicación Terminal y en Linux puedes usar varias opciones como GNOME Terminal, Konsole o XTerm. Una vez que abras la terminal, verás una ventana con un fondo negro o de otro color y un texto que indica el nombre de usuario, el nombre del equipo y el directorio actual, seguido de un símbolo como $ o >. Este texto se llama prompt y es donde puedes escribir los comandos.

## Comandos básicos
Los comandos son palabras o abreviaturas que indican al sistema operativo qué acción realizar. Los comandos pueden tener opciones o argumentos que modifican su comportamiento o especifican los datos de entrada o salida. Los comandos, las opciones y los argumentos se separan por espacios y se terminan con la tecla Enter. Algunos comandos básicos de la línea de comandos son los siguientes:


- `pwd`: muestra el directorio actual o la ruta de acceso completa donde estás trabajando.
- `ls`: lista los archivos y directorios que hay en el directorio actual. Puedes usar la opción -l para ver más detalles, como el tamaño, la fecha y los permisos de los archivos, o la opción -a para ver también los archivos ocultos.
- `cd`: cambia el directorio actual al que se indica como argumento. Puedes usar cd .. para ir al directorio padre o `cd ~` para ir al directorio home o raíz.
- `mkdir`: crea un nuevo directorio con el nombre que se indica como argumento.
- `cp`: copia el archivo o directorio que se indica como primer argumento al destino que se indica como segundo argumento. Puedes usar la opción -r para copiar recursivamente un directorio y todo su contenido
- `mv`:  mueve o renombra el archivo o directorio que se indica como primer argumento al destino que se indica como segundo argumento.
- `head`: muestra las primeras líneas del archivo que se indica como argumento. Puedes usar la opción -n para especificar el número de líneas que quieres ver.
- `tail`: muestra las últimas líneas del archivo que se indica como argumento. Puedes usar la opción -n para especificar el número de líneas que quieres ver.
- `grep`: busca un patrón o una palabra en el archivo o directorio que se indica como argumento. Puedes usar la opción -i para ignorar las mayúsculas y minúsculas, la opción -v para mostrar las líneas que no coinciden con el patrón, o la opción -c para contar el número de coincidencias.
