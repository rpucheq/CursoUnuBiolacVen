## Introducción a R
R es un lenguaje de programación y un entorno de software para el análisis estadístico y la visualización de datos. R es ampliamente utilizado por científicos de datos, investigadores, profesores y estudiantes de diversas disciplinas. R tiene una gran comunidad de usuarios que contribuyen con paquetes que extienden sus funcionalidades y facilitan el trabajo con datos.

## Instalación de R y RStudio
Para empezar a usar R, necesitamos instalar dos programas: R y RStudio. R es el lenguaje propiamente dicho, mientras que RStudio es un entorno de desarrollo integrado (IDE) que nos ofrece una interfaz gráfica y varias herramientas para facilitar la escritura y ejecución de código en R.

Para instalar R, debemos ir a la página web oficial de R y descargar la versión adecuada para nuestro sistema operativo. Una vez descargado el archivo, lo ejecutamos y seguimos las instrucciones del instalador.

Para instalar RStudio, debemos ir a la página web oficial de RStudio y descargar la versión gratuita de RStudio Desktop para nuestro sistema operativo. Una vez descargado el archivo, lo ejecutamos y seguimos las instrucciones del instalador.

## Primeros pasos con R y RStudio
Una vez instalados R y RStudio, podemos abrir RStudio y veremos una ventana dividida en cuatro paneles:

1 El panel superior izquierdo es el editor de scripts, donde podemos escribir y guardar nuestro código en R.
2. El panel inferior izquierdo es la consola, donde podemos ejecutar nuestro código en R y ver los resultados.
3. El panel superior derecho es el entorno, donde podemos ver los objetos que hemos creado en R, como variables, funciones, datos, etc.
4. El panel inferior derecho es el visor, donde podemos ver los gráficos que hemos generado en R, así como acceder a otras herramientas, como el explorador de archivos, el historial de comandos, el gestor de paquetes, la ayuda, etc.

## Comandos
```{r}
2 + 3
```
### Asignacion de Variables
```{r}
x <- 2 + 3 # asignamos el resultado de la suma a una variable llamada x
y <- 4 + 5 # asignamos el resultado de la suma a una variable llamada y
z <- x + y # asignamos el resultado de la suma de x e y a una variable llamada z
z # mostramos el valor de la variable z
```

## Tipos de datos y estructuras de datos en R
R puede trabajar con diferentes tipos de datos, como números, caracteres, lógicos, fechas, etc. Cada tipo de dato tiene sus propias características y operaciones. Por ejemplo, podemos escribir en la consola:

```{r}
2 + 3 # suma de números
"R" + "Studio" # concatenación de caracteres
TRUE & FALSE # operación lógica
as.Date("2023-11-12") # conversión a fecha
```

### Como ver que tipos de datos son:
```{r}
class(2 + 3)
class("R" + "Studio")
class(TRUE & FALSE)
class(as.Date("2023-11-12"))
```

### A quien pedir ayuda
Para obtener ayuda sobre una función o un paquete de R, puedes usar la función `help()` o el símbolo `?`. Por ejemplo, si escribes help(mean) o `?mean` y presionas Enter, verás la documentación de la función mean, que calcula la media de un conjunto de datos. También puedes usar la función `example()` para ver ejemplos de uso de una función. Por ejemplo, si escribes `example(mean)` y presionas Enter, verás algunos ejemplos de cómo usar la función mean.
