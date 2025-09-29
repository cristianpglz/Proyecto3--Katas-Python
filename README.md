Proyecto3--Katas-Python

This repository contains a collection of Python katas designed to practice and reinforce key programming concepts. Each exercise focuses on problem-solving while applying clean code principles and Python best practices.

Exercise 1

Creamos una función con un parámetro con su valor predefinido, a continuación dentro de la función vamos a crear una lista vacía para almacenar el resultado. Abrimos un bucle for con una variable char recogiendo el texto predefinido o ingresado por el usuario como parámetro, luego creamos el primer if que lo que hará es comprobar que si char es espacio vacío aplica un continue y va a la siguiente letra, en el segundo if vamos a comprobar si la letra está en la lista y sumarle uno, y si no está le agrega un valor, por último devolvemos la lista y fuera de la función hacemos inputText para preguntarle al usuario el texto, y por último llamamos a la función que nos devolverá el resultado.

Exercise 2

Utilicé dos maneras de hacer este ejercicio porque primero creé una manera de hacerlo y luego, viendo información, descubrí otra manera que me pareció muy interesante y quise practicarla. La primera es la más común: creamos una lista de números, luego una función donde le pasamos el número y dentro de la función multiplicamos por dos y devolvemos el resultado. Una vez con todo eso creamos otra variable en la que en ella crea un duplicado de lista en el que dentro con map va a recorrer cada número y con la función multiplicarlo por dos.

En la segunda manera, utiliza la misma lista de números, crea una variable en la que como antes duplica una lista, recorre la lista con el map, crea una función anónima llamada lambda con el parámetro x, multiplica x por 2, lo que nos devuelve el mismo resultado del anterior.

Exercise 3

En este ejercicio he pensado mucho en los "posibles fallos" que pudiera haber, comencé creando una lista con unas cuantas palabras, a continuación una función que busque si la palabra está en la lista mediante una list comprehension y con un if y un bucle añadimos los resultados, luego he creado otra que haga la pregunta al usuario de cuál es la palabra que ingresa, y ahí integré un bucle que pida la palabra, y busque cualquier posible espacio o número o carácter especial que pueda haber, además agregué un par de except para que no se cuelgue si hay algún fallo. Por último llamamos a la función.

Exercise 4

Lo primero fue crear las dos listas, lo segundo fue crear una variable donde en ella creamos una copia de la lista, y dentro hacemos un map, una función anónima, cogemos los valores de dos en dos con el zip y se restan los dos valores, después printeamos el resultado.

Exercise 5

Definimos las variables, creamos una función, dentro de la misma creamos una variable que recoja una suma de la lista de números y luego lo divida por su longitud, a continuación, creamos un if que compare si el resultado es aprobado o suspenso, por último retornamos los resultados y fuera los printeamos.

Exercise 6

Igual que en el ejercicio 3, he creado una función para limpiar la consola y otra para recoger el número que introduzca el usuario, por último creamos otra función donde se recoge el número, se comprueba si es menor a 0, si es 0 o 1, y por último se devuelve el número por la llamada a la función -1.

Exercise 7

Creamos la lista de tuplas, creamos una función que recoja la lista, creamos una variable que cree una lista y recorra cada tupla, añadiéndolo a la lista creada, por último comprobamos su type y devolvemos el resultado.

Exercise 8

Creamos una función para la limpieza de terminal, otra para la recogida de los números introducidos por el usuario, haciendo validación de errores y devolviendo los valores y la llamada a la siguiente función, la cual creamos y hacemos la división entre los dos números que recoge y trabajamos en los posibles errores que pudiera haber.

Exercise 9

Creamos la variable con la lista de animales, luego la función para excluir, dentro creamos la variable de animales que no queremos, creamos otra donde dentro crearemos una lista filtrando con una función anónima donde lea cada una y la compare, luego printeamos el resultado.

Exercise 10

En este ejercicio vamos a crear una función que recoja una lista, y dentro calcularemos su promedio, lo que hice fue crear una función antes que da aviso de error, y dentro de la función lo llamamos para que el programa nos avise del motivo y no provoque un error.