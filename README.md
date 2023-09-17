# FUNDAMENTALS PHYTON 

Bienvenidos a la guía para principiantes de Python realizada por Ramón Peinado Ruiz.

## CONCEPTOS BASICOS

 Python es un lenguaje de programación que se utiliza ampliamente en diferentes áreas, como desarrollo web, análisis de datos, inteligencia artificial, automatización de tareas y mucho más.
  <div align="center">
<img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" width="300px"/>
</div>
Características sobre Python:

- **Sintaxis sencilla**: Python se destaca por su sintaxis fácil de leer y comprender. Utiliza una indentación consistente en lugar de llaves o palabras clave para delimitar bloques de código, lo que mejora la legibilidad.
- **Tipado dinámico**: Python es un lenguaje de tipado dinámico, lo que significa que no es necesario declarar el tipo de variable antes de usarla. Las variables pueden cambiar de tipo durante la ejecución del programa.
- **Amplia biblioteca estándar**: Python cuenta con una amplia biblioteca estándar que ofrece una amplia gama de módulos y funciones listas para usar. Estos módulos cubren muchas tareas comunes, como manipulación de archivos, redes, acceso a bases de datos, generación de contenido web, entre otros.
- **Gran comunidad**: Python cuenta con una gran comunidad de desarrolladores activos en todo el mundo. Esto significa que puedes encontrar recursos, bibliotecas y ayuda fácilmente. La comunidad también contribuye al desarrollo de frameworks y bibliotecas populares, lo que facilita el trabajo con Python.
- **Multiplataforma**: Python es compatible con varios sistemas operativos, como Windows, macOS y Linux. Esto te permite escribir programas una vez y ejecutarlos en diferentes plataformas sin realizar cambios significativos en el código.
- **Versatilidad**: Python se utiliza en una amplia gama de aplicaciones. Puedes construir sitios web, crear scripts de automatización, desarrollar aplicaciones de escritorio, realizar análisis de datos, crear juegos y mucho más.



## ENTORNO DE PROGAMACION

Antes de poder programar en Python hemos de preparar nuestro entorno, estos son los pasos que hemos de tomar:

- **Instala Python**: Primero, necesitarás instalar Python en tu sistema. Puedes descargar la última versión estable de Python desde el sitio web oficial ([https://www.python.org](https://www.python.org/)). Asegúrate de seleccionar la versión adecuada para tu sistema operativo.
- **Elige un entorno de desarrollo**: Puedes utilizar el intérprete interactivo de Python en la línea de comandos para escribir y ejecutar código de Python de forma interactiva, para iniciarlo hemos de escribir Python en la linea de comandos una vez instalado. Sin embargo, también puedes considerar instalar un entorno de desarrollo integrado (IDE) que ofrezca características adicionales como **resaltado de sintaxis, depuración y sugerencias de código**. Algunos IDE populares para Python son PyCharm, Visual Studio Code, Atom y IDLE.

- **Instalación de Jupyter Notebook**: Jupyter Notebook es una aplicación web que le permite escribir y ejecutar programas Python en su navegador en lugar de en la línea de comandos. Para instalarlo escribiremos en nuestra terminal `pip install notebook` para entrar ejecutaremos un `jupyter notebook` y veremos algo como esto:

  <img src="/img/4ºimagenn.PNG"  />

## Primer Programa

Hemos escogido Visual Studio como entorno de desarrollo, vamos a realizar nuestro primer programa.

Nuestro primer programa será algo sencillito vamos a sacar por pantalla un comentario escrito a nuestro gusto usando la función de impresión `print ("").`

<img src="/img/2ºimagenn.PNG"  />

Como en cualquier otro lenguaje de programación **podemos comentar nuestro código con un simple #**.

Para poder ejecutar este programa hemos de guardarlo con la extensión .py, tras esto podremos ejecutarlo desde nuestra terminal.

Accederemos a la ubicación del archivo y una vez dentro ejecutaremos un `python hola.py`

<img src="/img/3ºimagenn.PNG"  />

## Entorno de Jupyter Notebook

Hemos comentado anteriormente que tenemos que instalar Jupyter notebook, vamos a justificar el uso de esta herramienta y mostrar como se usa:

Jupyter Notebooks es una herramienta creada por la organización sin fines de lucro Project Jupyter, que facilita la programación y la ciencia de datos en Python. Es una **aplicación web que permite escribir y ejecutar programas de Python en el navegador** en lugar de la línea de comandos.

Al ejecutar Jupyter Notebooks desde la línea de comandos, se inicia un servidor de aplicación web en el equipo, que se abre automáticamente en el navegador. Los archivos con extensión ".ipynb" son archivos de cuaderno de IPython, que son los que Jupyter Notebook ayuda a crear y editar.

Cada cuaderno consiste en una serie de celdas. Para **crear nuevas celdas**, se puede presionar **Shift + Enter**. Para **eliminar celdas**, se puede hacer clic fuera de la celda y luego **escribir "dd"**.

<img src="/img/5ºimagenn.PNG"  />

Las celdas pueden estar en dos modos: el **modo de comando y el modo de edición**. En el modo de edición, se puede ingresar código de Python y ejecutarlo presionando Shift + Enter. En el modo de comando, se pueden realizar acciones como crear nuevas celdas, cambiar el tipo de celda a Mark Down y utilizar atajos de teclado.

## Operadores

Estos son los operadores:

<img src="/img/6ºimagenn.PNG"  />

Ejemplos de su uso:

<img src="/img/7ºimagenn.PNG"  />

## Tipos de datos de objeto, prioridades de operador y conversión de tipos de datos

### Estos son los tipos de datos básicos y ejemplos:

<img src="/img/8ºimagenn.PNG"  />

<img src="/img/9ºimagenn.PNG"  />

Podemos detectar el tipo de dato con la función `type(datodelquequeremoseltipo)`

<img src="/img/10ºimagenn.PNG"  />



### Prioridad de los operadores:

Cuanto mas alto en la tabla mas alta la prioridad, el calculo se realiza antes:

<img src="/img/11ºimagenn.PNG"  />

Hemos de tener cuidado cuando hacemos ciertas ecuaciones, algunas dan errores como por ejemplo la division entre 0...

### Conversión de datos:

Podemos convertir el tipo de dato de manera simple:

<img src="/img/12ºimagenn.PNG"  />

Como vemos hay otro tipo de dato llamado None, este tipo de dato indica que la variable no tiene valor.

### Cadenas o Strings y sus aplicaciones:

La string ha de operarse con un entero en la multiplicación si no obtendremos un error

<img src="/img/13ºimagenn.PNG"  />

Si concatenamos una str y un numero entero obtendremos un error, tendríamos que modificar el tipo

<img src="/img/14ºimagenn.PNG"  />

Uso de la coma:

<img src="/img/15ºimagenn.PNG"  />

Si queremos citar dentro de las cadenas con " " o con '' :

<img src="/img/16ºimagenn.PNG"  />

Si queremos cambiar de linea usamos:

<img src="/img/17ºimagenn.PNG"  />

Si queremos insertar una tabulación en una cadena: 

<img src="/img/18ºimagenn.PNG"  />

Indexar las cadenas o como obtener un cierto caracter:

<img src="/img/19ºimagenn.PNG"  />

Si introducimos un valor negativo querra decir que empezamos por el ultimo carácter de nuestra cadena:

<img src="/img/20ºimagenn.PNG"  />

## Variables

Las variables se utilizan para almacenar valores de numeros reales, enteros, cadenas... existe una gramática especifica para la declaración de estas. Las variables se declaran con identificadores para poder diferenciarlas, estos identificadores deben de seguir estas reglas:

1. Los nombres de las variables pueden contener letras, números o barras bajas (`_`) pero no pueden contener espacios en blanco, letras con tilde o eñes. 

2. Tampoco pueden comenzar con números.

3. No pueden contener espacios o tabulaciones

4. Python distingue entre mayusculas y minusculas INDEX y index son variables diferentes

5. No se pueden usar las Keywords o las palabras reservadas para Python

   <img src="/img/21ºimagenn.PNG"  />

   

   No es necesario memorizarlas todas, se pueden obtener por pantalla de la siguiente manera

   <img src="/img/22ºimagenn.PNG"  />

   

Al identificar variables lo esencial es que se identifiquen de manera logica, es decir si vamos a introducir una variable la cual sea un peso, es logico que esta se llame peso.

Podemos identificara el tipo de dato de una variable de la misma manera que lo haciamos con los datos normales, `type(variable)`

<img src="/img/23ºimagenn.PNG"  />

Podemos asignar el valor de una operacion a una variable 

<img src="/img/24ºimagenn.PNG"  />

Tambien podemos asignar varios valores a varias variables de manera simultanea

<img src="/img/25ºimagenn.PNG"  />

O 1 valor a varias variables simultáneamente

<img src="/img/26ºimagenn.PNG"  />

## Operadores de asignación compuesta

Estos son los operadores de asignacion compuesta, facilitan las operaciones.<img src="/img/27ºimagenn.PNG"  />Ejemplos:

<img src="/img/28ºimagenn.PNG"  />

## Función de entrada

Podemos pedirle valores al usuario que use nuestro código esto se realiza mediante la función `input()`

Por ejemplo vamos a pedirle el peso y altura al usuario para calcular su índice de masa corporal

- Indicamos el tipo de dato antes de pedírselo, para evitarnos errores si introducen valores con decimales o centesimas indicamos que este es float

<img src="/img/29ºimagenn.PNG"  />



De la misma manera que pedimos datos numericos podemos pedir cadenas de caracteres o strings



<img src="/img/30ºimagenn.PNG"  />

Si le definimos el tipo de dato el cual vamos a introducir, Python solo aceptara ese tipo de dato y obtendremos un error si introducimos otro tipo de dato.



Ejercicios básicos numéricos:

<img src="/img/31ºimagenn.PNG"  />



## BIBLIOGRAFIA y AGRADECIMIENTOS

Esta guía básica no podía haber sido realizada sin la ayuda de este curso:

Curso de Iniciación a la programación con Inteligencia artificial y prompts de ChatGPT				EOI

Mencionar también la gran ayuda recibida por parte de toda la comunidad de Python y sus foros.

