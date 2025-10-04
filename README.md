Proyecto3--Katas-Python

This repository contains a collection of Python katas designed to practice and reinforce key programming concepts. Each exercise focuses on problem-solving while applying clean code principles and Python best practices.

Ejercicio 1

Creamos una función con un parámetro con su valor predefinido, a continuación dentro de la función vamos a crear una lista vacía para almacenar el resultado. Abrimos un bucle for con una variable char recogiendo el texto predefinido o ingresado por el usuario como parámetro, luego creamos el primer if que lo que hará es comprobar que si char es espacio vacío aplica un continue y va a la siguiente letra, en el segundo if vamos a comprobar si la letra está en la lista y sumarle uno, y si no está le agrega un valor, por último devolvemos la lista y fuera de la función hacemos inputText para preguntarle al usuario el texto, y por último llamamos a la función que nos devolverá el resultado.

Ejercicio 2

Utilicé dos maneras de hacer este ejercicio porque primero creé una manera de hacerlo y luego, viendo información, descubrí otra manera que me pareció muy interesante y quise practicarla. La primera es la más común: creamos una lista de números, luego una función donde le pasamos el número y dentro de la función multiplicamos por dos y devolvemos el resultado. Una vez con todo eso creamos otra variable en la que en ella crea un duplicado de lista en el que dentro con map va a recorrer cada número y con la función multiplicarlo por dos.

En la segunda manera, utiliza la misma lista de números, crea una variable en la que como antes duplica una lista, recorre la lista con el map, crea una función anónima llamada lambda con el parámetro x, multiplica x por 2, lo que nos devuelve el mismo resultado del anterior.

Ejercicio 3

En este ejercicio he pensado mucho en los "posibles fallos" que pudiera haber, comencé creando una lista con unas cuantas palabras, a continuación una función que busque si la palabra está en la lista mediante una list comprehension y con un if y un bucle añadimos los resultados, luego he creado otra que haga la pregunta al usuario de cuál es la palabra que ingresa, y ahí integré un bucle que pida la palabra, y busque cualquier posible espacio o número o carácter especial que pueda haber, además agregué un par de except para que no se cuelgue si hay algún fallo. Por último llamamos a la función.

Ejercicio 4

Lo primero fue crear las dos listas, lo segundo fue crear una variable donde en ella creamos una copia de la lista, y dentro hacemos un map, una función anónima, cogemos los valores de dos en dos con el zip y se restan los dos valores, después printeamos el resultado.

Ejercicio 5

Definimos las variables, creamos una función, dentro de la misma creamos una variable que recoja una suma de la lista de números y luego lo divida por su longitud, a continuación, creamos un if que compare si el resultado es aprobado o suspenso, por último retornamos los resultados y fuera los printeamos.

Ejercicio 6

Igual que en el ejercicio 3, he creado una función para limpiar la consola y otra para recoger el número que introduzca el usuario, por último creamos otra función donde se recoge el número, se comprueba si es menor a 0, si es 0 o 1, y por último se devuelve el número por la llamada a la función -1.

Ejercicio 7

Creamos la lista de tuplas, creamos una función que recoja la lista, creamos una variable que cree una lista y recorra cada tupla, añadiéndolo a la lista creada, por último comprobamos su type y devolvemos el resultado.



Ejercicio 8

Creamos una función para la limpieza de terminal, otra para la recogida de los números introducidos por el usuario, haciendo validación de errores y devolviendo los valores y la llamada a la siguiente función, la cual creamos y hacemos la división entre los dos números que recoge y trabajamos en los posibles errores que pudiera haber.



Ejercicio 9

Creamos la variable con la lista de animales, luego la función para excluir, dentro creamos la variable de animales que no queremos, creamos otra donde dentro crearemos una lista filtrando con una función anónima donde lea cada una y la compare, luego printeamos el resultado.



Ejercicio 10

En este ejercicio vamos a crear una función que recoja una lista, y dentro calcularemos su promedio, lo que hice fue crear una función antes que da aviso de error, y dentro de la función lo llamamos para que el programa nos avise del motivo y no provoque un error.



Ejercicio 11

Comenzamos creando la funcion para borrar la consola,a continuacion creamos la funcion principal,la cual recoje la llamada del usuario y filtra que sean numeros y cantidad correcta,por ultimo y separada,creamos la funcion que maneja los posibles errores,y por ultimo la llamamos a la funcion que inicia el bucle.


Ejercicio 12

Creamos nuestra variable con la frase,creamos la funcion,en ella creamos otra variable que separe las palabras,por ultimo a la vez que printeamos creamos la lista haciendo map de result y sacando la medida de cada palabra.


Ejercicio 13

Iniciamos una funcion en la que en el interior creamos una variable con la frase,creamos otra en la que filtre los espacios,y a continuacion otra que cree una lista recorra las letras las junte entre mayuscula y minuscula y las junte en una tupla.


Ejercicio 14

Creamos las dos variables iniciales,una lista de palabras y una letra,a continuancion creamos una funcion que recoja las dos variables.Luego abrimos un try y dentro creamos una variable que cree una lista que dentro creara una funcion anonima donde filtrara cada inicio de palabra con la letra que se le solicita antes.por ultimo intentamos corregir cualquier tipo de error que pueda devolver.


Ejercicio 15

creamos la primera variable y le añadimos una lista de numeros,a continuacion creamos la otra variable que en su interior creara una lista donde recorra la lista anterior y sume 3 a cada numero.

Ejercicio 16

Comenzamos creando las variables que nos informa el titulo,a continuacion creamos una funcion que recoja los dos valores.procedemos abriendo un try y creamos una variable que cree una lista y filtre por palabras que sean mayores al valor recogido,a continuacion printeamos el resultado,y corregimos posibles errores comunes.

Ejercicio 17

Importamos la funcion reduce,creamos la lista de numeros,creamos nuestra funcion y le pasamos la lista.Abrimos un try y en su interior creamos una variable la cual se va a encargar de multiplicar un numero por 10 y sumarle el siguiente.por ultimo prevenimos posibles errores.

Ejercicio 18 

Creamos la lista de estudiantes con sus notas,creamos una funcion en la que en su interior crearemos una variable donde creara una lista y filtre en una funcion anonima la calificacion de estudiantes sea mayor a 90,por ultimo printeamos el resultado.

Ejercicio 19

Creamos la lista de numeros,luego una variable en la que dentro creara una lista que filtrara que el resto de una division no sea 0.

Ejercicio 20

Creamos una lista con valores integer y string,a continuacion creamos una funcion donde en su interior trabajaremos con una variable que crea una lista y filtra con isinstance los valores int de la lista recogida anteriormente.

Ejercicio 21

creamos la variable con el numero a trabajar,creamos la funcion y dentro creamos la variable que contenga la funcion lambda donde elevamos el numero que recogemos.por ultimo printeamos el resultado y recojemos el numero.