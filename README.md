Proyecto 3 -- Katas-Python

This repository contains a collection of Python katas designed to practice and reinforce key programming concepts. Each exercise focuses on problem-solving while applying clean code principles and Python best practices.

Ejercicio 1

Creamos una función con un parámetro con su valor predefinido, a continuación, dentro de la función vamos a crear una lista vacía para almacenar el resultado. Abrimos un bucle for con una variable char recogiendo el texto predefinido o ingresado por el usuario como parámetro, luego creamos el primer if que lo que hará es comprobar que, si char es espacio vacío, aplica un continue y va a la siguiente letra. En el segundo if vamos a comprobar si la letra está en la lista y sumarle uno, y si no está le agrega un valor. Por último, devolvemos la lista y fuera de la función hacemos inputText para preguntarle al usuario el texto, y por último llamamos a la función que nos devolverá el resultado.

Ejercicio 2

Utilicé dos maneras de hacer este ejercicio porque primero creé una manera de hacerlo y luego, viendo información, descubrí otra manera que me pareció muy interesante y quise practicarla. La primera es la más común: creamos una lista de números, luego una función donde le pasamos el número y dentro de la función multiplicamos por dos y devolvemos el resultado. Una vez con todo eso, creamos otra variable en la que se crea un duplicado de lista en el que, dentro, con map, va a recorrer cada número y con la función multiplicarlo por dos.

En la segunda manera, utilizo la misma lista de números, creo una variable en la que, como antes, duplico una lista, recorro la lista con el map, creo una función anónima llamada lambda con el parámetro x, multiplico x por 2, lo que nos devuelve el mismo resultado del anterior.

Ejercicio 3

En este ejercicio he pensado mucho en los "posibles fallos" que pudiera haber. Comencé creando una lista con unas cuantas palabras, a continuación una función que busque si la palabra está en la lista mediante una list comprehension y con un if y un bucle añadimos los resultados. Luego he creado otra que haga la pregunta al usuario de cuál es la palabra que ingresa, y ahí integré un bucle que pida la palabra y busque cualquier posible espacio, número o carácter especial que pueda haber. Además, agregué un par de except para que no se cuelgue si hay algún fallo. Por último, llamamos a la función.

Ejercicio 4

Lo primero fue crear las dos listas, lo segundo fue crear una variable donde se crea una copia de la lista, y dentro hacemos un map, una función anónima, cogemos los valores de dos en dos con el zip y se restan los dos valores. Después printeamos el resultado.

Ejercicio 5

Definimos las variables, creamos una función, dentro de la misma creamos una variable que recoja una suma de la lista de números y luego la divida por su longitud. A continuación, creamos un if que compare si el resultado es aprobado o suspenso. Por último, retornamos los resultados y fuera los printeamos.

Ejercicio 6

Igual que en el ejercicio 3, he creado una función para limpiar la consola y otra para recoger el número que introduzca el usuario. Por último, creamos otra función donde se recoge el número, se comprueba si es menor a 0, si es 0 o 1, y por último se devuelve el número por la llamada a la función -1.

Ejercicio 7

Creamos la lista de tuplas, creamos una función que recoja la lista, creamos una variable que cree una lista y recorra cada tupla, añadiéndolo a la lista creada. Por último, comprobamos su type y devolvemos el resultado.

Ejercicio 8

Creamos una función para la limpieza de terminal, otra para la recogida de los números introducidos por el usuario, haciendo validación de errores y devolviendo los valores y la llamada a la siguiente función, la cual creamos y hacemos la división entre los dos números que recoge, y trabajamos en los posibles errores que pudiera haber.

Ejercicio 9

Creamos la variable con la lista de animales, luego la función para excluir, dentro creamos la variable de animales que no queremos, creamos otra donde dentro crearemos una lista filtrando con una función anónima donde lea cada una y la compare. Luego printeamos el resultado.

Ejercicio 10

En este ejercicio vamos a crear una función que recoja una lista, y dentro calcularemos su promedio. Lo que hice fue crear una función antes que da aviso de error, y dentro de la función lo llamamos para que el programa nos avise del motivo y no provoque un error.

Ejercicio 11

Comenzamos creando la función para borrar la consola, a continuación, creamos la función principal, la cual recoge la llamada del usuario y filtra que sean números y cantidad correcta. Por último y separada, creamos la función que maneja los posibles errores, y por último la llamamos a la función que inicia el bucle.

Ejercicio 12

Creamos nuestra variable con la frase, creamos la función, en ella creamos otra variable que separe las palabras. Por último, a la vez que printeamos, creamos la lista haciendo map de result y sacando la medida de cada palabra.

Ejercicio 13

Iniciamos una función en la que, en el interior, creamos una variable con la frase, creamos otra en la que filtre los espacios y, a continuación, otra que cree una lista, recorra las letras, las junte entre mayúscula y minúscula y las junte en una tupla.

Ejercicio 14

Creamos las dos variables iniciales, una lista de palabras y una letra. A continuación, creamos una función que recoja las dos variables. Luego abrimos un try y dentro creamos una variable que cree una lista que dentro creará una función anónima donde filtrará cada inicio de palabra con la letra que se le solicita antes. Por último, intentamos corregir cualquier tipo de error que pueda devolver.

Ejercicio 15

Creamos la primera variable y le añadimos una lista de números. A continuación, creamos la otra variable que, en su interior, creará una lista donde recorra la lista anterior y sume 3 a cada número.

Ejercicio 16

Comenzamos creando las variables que nos informa el título. A continuación, creamos una función que recoja los dos valores. Procedemos abriendo un try y creamos una variable que cree una lista y filtre por palabras que sean mayores al valor recogido. A continuación, printeamos el resultado y corregimos posibles errores comunes.

Ejercicio 17

Importamos la función reduce, creamos la lista de números, creamos nuestra función y le pasamos la lista. Abrimos un try y en su interior creamos una variable la cual se va a encargar de multiplicar un número por 10 y sumarle el siguiente. Por último, prevenimos posibles errores.

Ejercicio 18

Creamos la lista de estudiantes con sus notas, creamos una función en la que, en su interior, crearemos una variable donde creará una lista y filtre, en una función anónima, que la calificación de estudiantes sea mayor a 90. Por último, printeamos el resultado.

Ejercicio 19

Creamos la lista de números, luego una variable en la que dentro creará una lista que filtrará que el resto de una división no sea 0.

Ejercicio 20

Creamos una lista con valores integer y string. A continuación, creamos una función donde, en su interior, trabajaremos con una variable que crea una lista y filtra con isinstance los valores int de la lista recogida anteriormente.

Ejercicio 21

Creamos la variable con el número a trabajar, creamos la función y dentro creamos la variable que contenga la función lambda donde elevamos el número que recogemos. Por último, printeamos el resultado y recogemos el número.

Ejercicio 22

Lo primero que hice fue importar la función reduce de la librería functools, luego creé la lista de números. A continuación, agregué la función que recoge la lista. En su interior, creé la variable que utiliza el reduce con una lambda para multiplicar los números y devolver el resto. Por último, printeamos el resultado.

Ejercicio 23

Creamos la lista con las palabras, luego la función que, guardando en una variable, utilice reduce y sume la primera palabra con un espacio y la segunda palabra. Luego printeamos el resultado.

Ejercicio 24

Creamos la lista con los números, luego la función donde añadiremos una variable que, con reduce, reste cada uno de los números.

Ejercicio 25

Creamos la cadena de texto, luego una función que haga print del tamaño del texto, incluyendo los espacios.

Ejercicio 26

Creamos la variable que utiliza la función lambda para hacer la división de dos números. Por último, hacemos print y le pasamos los números.

Ejercicio 27

Creamos una función que recoja una lista de números y, dentro, printeamos el resultado de sumar todos los números de la lista y dividir entre el tamaño de la lista.

Ejercicio 28

Iniciamos la función que recoge los items, creamos una variable a la que le vamos a meter los repetidos, creamos un bucle for el cual leerá si un item está en la lista o no. Si está, devuelve ese item y lo agrega; si no, no lo añade.

Ejercicio 29

Añadimos una variable con números. A continuación, creamos una función que, en su interior, convierta la variable dada a un str y luego retornamos un # multiplicado por el largo de la variable menos 4, y por último le sumamos una lista menos los cuatro últimos números.

Ejercicio 30

Creamos una función la cual separa las letras y las ordena en orden, comprueba si son iguales; si lo son, devuelve True y si no, False.

Ejercicio 31

Empezamos creando la función que comprueba que la palabra está en la lista. Si no lo está, da error. Luego creamos la función que pregunta al usuario las palabras para añadir a la lista y cuál es el que quiere buscar. Por último, llamamos a la función que comprueba la lista y se la pasamos como parámetro.

Ejercicio 32

Creamos la lista que va a recibir y comenzamos con nuestra función. En ella creamos dos variables: una que busque si está el nombre completo exactamente igual y la otra solo por una palabra. Por último, buscamos si está el nombre completo. Si está ese o alguno más, si solo se escriben caracteres-números, y por último, si no está.

Ejercicio 33

Creamos una función que recoja dos listas de números y, en su interior, retorne la suma de cada uno de sus números mediante una función lambda.

Ejercicio 34

Creamos una clase Árbol, añadimos la función inicial con el parámetro, el cual va a ser la base. A continuación, llamamos a todas las funciones, las cuales, paso a paso, van a ir realizando su función.

Ejercicio 35

Creamos la clase UsuarioBanco, creamos las funciones básicas que nos pide el ejercicio y la principal en la que definimos todo parte por parte. En las funciones hacemos que cumplan sus funciones y corregir sus posibles errores. Por último, agregamos los usos solicitados por el enunciado.

Ejercicio 36

Comenzamos a crear la función principal del ejercicio. A continuación, creamos las tres funciones solicitadas en el enunciado. Creamos las posibles opciones que puede pedir el usuario y vamos uno a uno llamando a las funciones necesarias para cada evento.

Ejercicio 37

Creamos la función que va a trabajar según la hora que sea, con varias zonas marcadas por unas horas específicas y sus limitaciones. A continuación, después de preguntar al usuario, marcamos con un try el resultado para recoger los minutos y corregir posibles errores.

Ejercicio 38

Creamos una función la cual recoja la nota, y dependiendo de cada caso, entre un baremo de notas dará el resultado esperado.

Ejercicio 39

Creamos la función y, en ella, con los parámetros recogidos, comenzamos con las restricciones. Si es rectángulo, base por altura; si es círculo, es el radio elevado a dos por el número π; y en triángulo, es base por altura entre dos.

Ejercicio 40

Creamos las dos funciones que consulten al usuario el precio y el descuento, con sus respectivas limitaciones. A continuación, creamos la función principal, la cual va a llamar y guardar en unas variables a las anteriores funciones. Comprobamos si hay descuento; si no lo hay, damos el precio; si lo hay, aplicamos el descuento y mostramos el resultado.