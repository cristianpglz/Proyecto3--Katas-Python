# Proyecto3--Katas-Python
This repository contains a collection of Python katas designed to practice and reinforce key programming concepts. Each exercise focuses on problem-solving while applying clean code principles and Python best practices.


# Exercise 1
Creamos una funcion con un parametro con su valor predefinido,a continuacion dentro de la funcion vamos a crear una lista vacia para almacenar el resultado.Abrimos un bucle for con una variable char recogiendo el testo predefinido o ingresado por el usuario como parametro,luego creamos el primer if que lo que hara es comprobar que si char es espacio vacio aplica un continue y va a la siguiente letra,en el segundo if vamos a comprobar si la letra esta en la lista y sumarle uno,y si no esta le agrega un valor,por ultimo devolvemos la lista y fuera de la funcion hacemos in imputText para preguntarle al usuario el texto,y por ultimo llamamos a la funcion que no devolvera el resultado.


# Exercise 2
Utilice dos maneras de hacer este ejercicio porque primero cree una manera de hacerlo y luego viendo informacion descubri otra manera que me parecio muy interesante y quise practicarla,la primera es la mas comun,creamos una lista de numeros,luego una funcion donde le pasamos el numero y dentro de la funcion multiplicamos por dos y devolvemos el resultado.una vez con todo eso creamos otra variable en el que en ella crea un duplicado de lista en el que dentro con map va recorrer cada numero y con la funcion multiplicarlo por dos.

En la segunda manera,utiliza la misma lista de numeros,crea una variable en la que como antes duplica una lista,recorre la lista con el map crea una funcion anonima llamada lambda con el parametro x,multiplica x por 2,lo que nos devuelve el mismo resultado del anterior.


# Exercise 3
En este ejercicio e pensado mucho en los "posibles fallos" que pudiera haber,comence creando una lista con unas cuantas palabras,a continuacion una funcion que busque si la palabra esta en la lista mediante una list comprension y con un if y un bucle añadimos los resultados,luego e creado otra que haga la pregunta al usuario de cual es la palabra que ingresar,y ahi integre un bucle que pida la palabra,y busque cualquier posible espacio o numero o caracter especial que pueda haber,a mas agregue un par de except para que no se cuelgue si hay algun fallo.Por ultimo llamamos a la funcion.


# Exercise 4
Lo primero fue crear las dos listas,lo segundo fue crear una varieable donde en ella creamos la una copia de la lista,y dentro hacemos un map,una funcion anonima,cogemos los valores de dos en dos con el zip y se restan los dos valores,despues printeamos el resultado.


# Exercise 5
Definimos las variables,creamos una funcion,dentro de la misma creamos una variable que recoja una suma de la lista de numeros y luego lo divida por su longitud,a continuacion,creamos un if que compare si el resultado es aprovado o suspento,por ultimo returnamos los resultados y fuera los printeamos.


# Exercise 6
igual que en el ejercicio 3,e creado una funcion para limpiar la consola y otra para recoger el numero que introduzca el usuario,por ultimo creamos otra funcion donde se recoge el numero se comprueba si es menor a 0,si es 0 o 1 
y por ultimo se devuelve el numero por la llamada a la funcion -1.


# Exercise 7
creamos la lista de tuplas,creamos una funcion que recoja la lista,creamos una variable que cree una lista y recorra cada tupla,añadiendolo a la lista creada,por ultimo comprobamos su type y devolvemos el resultado.


# Exercise 8
creaamos una funcion para la limpieza de terminal, otra para la recogida de los numeros introducida por el usuario,haciendo validacion de errores y devolviendo los valores y la llamada a la siguiente funcion,la cual creamos y hacemos la division entre los dos numeros que recoje y trabajamos en los posibles errores que pudiera haber.


# Exercise 9