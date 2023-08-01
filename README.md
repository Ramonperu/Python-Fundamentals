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



## VARIABLES COMUNES Y TIPOS

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
  
  
  
- **Sets o conjuntos`{}`**: Es una estructura de datos que representa una colección desordenada de elementos únicos. 

  Características: **Elementos únicos**, **no hay orden definido ni es sensible a este**, **mutabilidad** (Puedes agregar, eliminar y modificar elementos en un conjunto después de que se haya creado), **operaciones de conjuntos** (Estas operaciones te permiten combinar, comparar y manipular conjuntos de manera eficiente.)

  Ejemplo:

  <img src="/img/9ºimagenn.PNG"  />

- **Tuples`()`**: Es una estructura de datos similar a una lista. Se utilizan para almacenar una colección ordenada de elementos, al igual que las listas, pero con la característica adicional de inmutabilidad. 

  Características: **Elementos ordenados**, **inmutabilidad** (no se pueden modificar después de su creación. No puedes agregar, eliminar o modificar elementos individuales en una tupla como con las listas, vease el ejemplo. Sin embargo, puedes crear nuevas tuplas mediante la concatenación o el desempaquetado), **utilidad y ventajas** (son útiles cuando necesitas almacenar una colección de elementos que no cambiarán a lo largo del programa. También son más eficientes en términos de uso de memoria en comparación con las listas)

  Ejemplo:

  
  
  <img src="/img/10ºimagenn.PNG"  />

- **Diccionarios`{}`**: Es una estructura de datos que permite almacenar pares de clave-valor.

  Características: **Pares clave-valor**(Los pares clave-valor se separan con dos puntos `:` y cada par se separa por comas. Por ejemplo: `{clave1: valor1, clave2: valor2}`.La clave puede ser cualquier tipo de dato inmutable, como una cadena, un número o una tupla, mientras que el valor puede ser cualquier tipo de dato válido en Python), **acceso a los valores mediante claves**, **mutabilidad**(se puede agregar modificar o eliminar), **operaciones de diccionario** (Los diccionarios en Python proporcionan una variedad de operaciones útiles).

  <img src="/img/11ºimagenn.PNG"  />

## OPERADORES

Los operadores son las instrucciones que nos dicen que hacer con los datos, hay varios tipos:

- **Operadores aritméticos**:  Realizan operaciones matemáticas en números. Los operadores aritméticos incluyen:
  - Suma: `+` (por ejemplo, `1 + 1 = 2`).
  - Multiplicación: `*` (por ejemplo, `2 * 3 = 6`).
  - Exponente: `**` (por ejemplo, `5 ** 2 = 25`).
  - División: `/` (por ejemplo, `20 / 5 = 4.0`). Siempre devuelve un valor decimal (float).
  - Módulo: `%` (por ejemplo, `20 % 6 = 2`). Devuelve el resto de una división.
- **Operadores de concatenación de cadenas**: Operan en cadenas y se utilizan para unir o repetir cadenas.
  - Concatenación: `+` (por ejemplo, `"Hola " + "mundo" = "Hola mundo"`).
  - Repetición: `*` (por ejemplo, `"Hola " * 4 = "Hola Hola Hola Hola "`).
- **Comparacion**: Comparan dos valores y devuelven un valor booleano 
  - Igualdad: `==` (por ejemplo, `4 == 4` es verdadero).
  - Menor que: `<` (por ejemplo, `4 < 5` es verdadero).
  - Menor o igual que: `<=` (por ejemplo, `5 <= 5` es verdadero).
  - Mayor que: `>` (por ejemplo, `5 > 2` es verdadero).
  - Mayor o igual que: `>=` (por ejemplo, `5 >= 2` es verdadero).
  - Diferente: `!=` (por ejemplo, `4 != 5` es verdadero).
- **Operadores lógicos**: Operan en valores booleanos y combinan o niegan condiciones.
  - Y lógico: `and` (por ejemplo, `True and False` es falso).
  - O lógico: `or` (por ejemplo, `True or False` es verdadero).
  - No lógico: `not` (por ejemplo, `not True` es falso).
- **Operadores de membresía**: Verifican si un valor está presente en una secuencia.
  - Pertenece a: `in` (por ejemplo, `1 in [1, 2, 3, 4, 5]` es verdadero).
  - No pertenece a: `not in` (por ejemplo, `10 not in [1, 2, 3, 4, 5]` es verdadero).



## Flujo de control

- **if**: Usado para **ejecutar una decisión en base a una condición**. Si en este ejemplo cambiáramos el valor a `False` no se imprimiría nada en pantalla.

  <img src="/img/12ºimagenn.PNG"  />

  Después de los dos puntos del condicional `if ramonestaprogramando:` se aplica una sangria, esto quiere decir que todo lo que hay tras los dos puntos se ejecutará SOLO si se cumple que `ramonestaprogramando = True`.

  - **if - else**:  nos dará la posibilidad de **ejecutar otra cosa si la condición del if no se cumple**:

  <img src="/img/13ºimagenn.PNG"  />

  Podemos introducir condiciones dentro de otras condiciones:

  <img src="/img/14ºimagenn.PNG"  />

  Si cambiamos la variable de julio a `False` no llegariamos al 'Todos estan programando'.

- **for**: El bucle "for" te **permite recorrer cada elemento de una lista** (u otro tipo de secuencia) **y realizar una acción con cada uno** de ellos.

  <img src="/img/15ºimagenn.PNG"  />

  

  Destacar que el "fruta" dentro de nuestro bucle es una variable la cual nosotros declaramos en la linea del for y podemos nombrarla a nuestro gusto. En este ejemplo podríamos haberlo llamado "numero" para facilitar el entendimiento.

  <img src="/img/16ºimagenn.PNG"  />

- **while**: Se utiliza **cuando deseas repetir un bloque de código mientras se cumple una condición específica**. Esto significa que el bloque de código se ejecutará una y otra vez hasta que la condición sea falsa.

  <img src="/img/17ºimagenn.PNG"  />

  Normalmente se usa el bucle while cuando las condiciones están cambiando o se ven directamente impactadas por el bloque debajo del bucle while, si no este bucle puede quedar ejecutándose de manera infinita.

## Funciones

Las funciones en Python son mini-programas, son bloques de código que se pueden llamar y reutilizar fácilmente para realizar una tarea específica. Las funciones se definen utilizando la palabra clave "def", seguida del nombre de la función y paréntesis. 

Creemos por ejemplo una función que multiplique una variable por 10:

<img src="/img/18ºimagenn.PNG"  />

Para usarla simplemente hemos de ejecutar la función con un valor en su interior:

<img src="/img/19ºimagenn.PNG"  />

Las funciones no han de devolver siempre algo, simplemente pueden mutar o cambiar una variable:

<img src="/img/20ºimagenn.PNG"  />

Si usas una función que no devuelve nada, asegúrate de no operar con el valor devuelto como si fuera otro tipo de dato, esto puede causar problemas.



## Clases y objetos

Las clases **son como plantillas o moldes para crear objetos**. Cada clase define cómo se verá y qué podrá hacer un objeto. Las clases generalmente **comienzan con letras mayúsculas** y es lo que las diferencia de los nombres de variables y funciones

La manera mas simple de entender las clases es con el ejemplo del perro:

Todos los perros tienen características similares, como color de pelo, tamaño, ladrido, y pueden hacer cosas como caminar, ladrar y comer.

En Python, creamos una clase para definir cómo se comportará un perro. Para hacerlo, utilizamos la palabra clave "class" seguida del nombre de la clase y dos puntos. Dentro de la clase, definimos las características y acciones del perro usando funciones especiales llamadas "métodos".

Al definir la clase hemos de definir la primera función, la función `init`, init significa inicialización y esta función se llama cada vez que se cree una instancia de la clase que estemos creando.

<img src="/img/21ºimagenn.PNG"  />

## BIBLIOGRAFIA y AGRADECIMIENTOS

Esta guía básica no podía haber sido realizada sin la ayuda de estos dos cursos:

Python Essential Training													Ryan Mitchell 		Linkedin Learning.

Mencionar también la gran ayuda recibida por parte de toda la comunidad de Python y sus foros.

