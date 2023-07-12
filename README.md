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

## PRIMER PROGRAMA

Hemos escogido Visual Studio como entorno de desarrollo, vamos a realizar nuestro primer programa.

Nuestro primer programa será algo sencillito vamos a sacar por pantalla un comentario escrito a nuestro gusto usando la función de impresión `print ("").`

<img src="/img/2ºimagenn.PNG"  />

Como en cualquier otro lenguaje de programación **podemos comentar nuestro código con un simple #**.

Para poder ejecutar este programa hemos de guardarlo con la extensión .py, tras esto podremos ejecutarlo desde nuestra terminal.

Accederemos a la ubicación del archivo y una vez dentro ejecutaremos un `python hola.py`

<img src="/img/3ºimagenn.PNG"  />

## ENTORNO DE JUPYTER NOTEBOOK

Hemos comentado anteriormente que tenemos que instalar Jupyter notebook, vamos a justificar el uso de esta herramienta y mostrar como se usa:

Jupyter Notebooks es una herramienta creada por la organización sin fines de lucro Project Jupyter, que facilita la programación y la ciencia de datos en Python. Es una **aplicación web que permite escribir y ejecutar programas de Python en el navegador** en lugar de la línea de comandos.

Al ejecutar Jupyter Notebooks desde la línea de comandos, se inicia un servidor de aplicación web en el equipo, que se abre automáticamente en el navegador. Los archivos con extensión ".ipynb" son archivos de cuaderno de IPython, que son los que Jupyter Notebook ayuda a crear y editar.

Cada cuaderno consiste en una serie de celdas. Para **crear nuevas celdas**, se puede presionar **Shift + Enter**. Para **eliminar celdas**, se puede hacer clic fuera de la celda y luego **escribir "dd"**.

<img src="/img/5ºimagenn.PNG"  />

Las celdas pueden estar en dos modos: el **modo de comando y el modo de edición**. En el modo de edición, se puede ingresar código de Python y ejecutarlo presionando Shift + Enter. En el modo de comando, se pueden realizar acciones como crear nuevas celdas, cambiar el tipo de celda a Mark Down y utilizar atajos de teclado.



## VARIABLES COMUNES+ Y TIPOS

Una **variable es una unidad fundamental en un programa** a la cual se le asigna un valor. Se puede crear la variable "x" y asignarle el valor 5 utilizando el signo igual (**=** conocido como **operador de asignación**, no confundir con **== el operador de declaración**). 

Existen reglas para los nombres de las variables. No pueden comenzar con números y no pueden contener caracteres especiales, excepto el guion bajo (_). Además, **es común que los nombres de las variables en Python comiencen con letras minúsculas**, las mayusculas se usan para las clases.

<img src="/img/6ºimagenn.PNG"  />

Se pueden asignar valores de texto a las variables. Estos **valores de texto se llaman cadenas o strings** en programación.

Para determinar el tipo de variable, se puede utilizar la función "type", si en algún momento olvidamos el tipo de variable podemos obtenerlo fácilmente con esta funcion.

<img src="/img/7ºimagenn.PNG"  />

Tipos de variables mas comunes:

- **Números enteros (int)**: Representan números enteros sin decimales. Por ejemplo: `1`, `10`, `-5`. Los números enteros en Python no tienen un límite de tamaño.
- **Números de punto flotante (float)**: Representan números con decimales. Por ejemplo: `3.14`, `2.71828`, `-0.5`. 
- **Cadenas de texto (str)**: Representan secuencias de caracteres entre comillas simples o dobles. Por ejemplo: `'Hola'`, `"Mundo"`, `'42'`. Puedes realizar diversas operaciones en cadenas, como concatenarlas (sumarlas como cadenas de texto), extraer subcadenas y formatearlas.
- **Booleanos (bool)**: Representan valores de verdad, es decir, verdadero (`True`) o falso (`False`)(Destacar que es sensitivo a minúsculas y si se pone `true` nos dará un error buscando una variable). Estos valores se utilizan principalmente en expresiones condicionales y bucles para tomar decisiones basadas en condiciones.





## ESTRUCTURA DE DATOS

- **Listas`[]`**: Es una estructura de datos que te p**ermite almacenar una colección ordenada** **(Son sensibles al orden)** **de elementos**. Puedes pensar en una lista como una secuencia de elementos separados por comas y encerrados entre corchetes.

  Características: Las listas son muy versátiles y **pueden contener elementos de diferentes tipos, como números, cadenas, booleanos e incluso otras listas**. Las listas son mutables, lo que significa que puedes modificar, agregar y eliminar elementos de ellas después de que se hayan creado. Es posible obtener el **valor de la longitud** de nuestra lista con la **función** `len(lista)`.

  Ejemplo:
  
  <img src="/img/8ºimagenn.PNG"  />
  
  
  
- **Sets o conjuntos` {}`**: Es una estructura de datos que representa una colección desordenada de elementos únicos. 

  Características: **Elementos únicos**, **no hay orden definido ni es sensible a este**, **mutabilidad** (Puedes agregar, eliminar y modificar elementos en un conjunto después de que se haya creado), **operaciones de conjuntos** (Estas operaciones te permiten combinar, comparar y manipular conjuntos de manera eficiente.)

  Ejemplo:

  <img src="/img/9ºimagenn.PNG"  />

- **Tuples`()`**: Es una estructura de datos similar a una lista. Se utilizan para almacenar una colección ordenada de elementos, al igual que las listas, pero con la característica adicional de inmutabilidad. 

  Características: **Elementos ordenados**, **inmutabilidad** (no se pueden modificar después de su creación. No puedes agregar, eliminar o modificar elementos individuales en una tupla como con las listas, vease el ejemplo. Sin embargo, puedes crear nuevas tuplas mediante la concatenación o el desempaquetado), **utilidad y ventajas** (son útiles cuando necesitas almacenar una colección de elementos que no cambiarán a lo largo del programa. También son más eficientes en términos de uso de memoria en comparación con las listas)

  Ejemplo:

  <img src="/img/10ºimagenn.PNG"  />

## BIBLIOGRAFIA y AGRADECIMIENTOS

Esta guía básica no podía haber sido realizada sin la ayuda de estos dos cursos:

Python Essential Training													Ryan Mitchell 		Linkedin Learning.

Mencionar también la gran ayuda recibida por parte de toda la comunidad de Python y sus foros.

