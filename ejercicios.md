<section class="cover">
# Guía de ejercicios de javascript
</section>

<section>

## Operaciones básicas, Prompt y Alert

- Escribir un programa que muestre un prompt donde el usuario ingresa un número, luego muestra otro prompt pidiendo otro número, finalmente el programa muestra una alerta con los resultados.

- Crear un programa donde el usuario ingrese en un prompt la temeperatura en celcius y el programa muestre en una alerta la temperatura en fahrenheit.

- Pedir un número a un usuario a través de un prompt y luego dividirlo por 10, ejemplo: 5 / 10  igual 0.5

## If and else

- Crear un programa que determine si un número introducido en un Prompt es par o no, la respuesta será mostrada en una alerta.

- Crear un programa que determine si un número introducido en un Prompt es divisible por 5 o no, mostrar el resultado con console.log

- Crear un programa que determine si un número introducido en un popup es divisible por 11 y 5 o no, mostrar el resultado con console.log

- Crear un programa que encuentre que le pida al usuario dos números en un popup y luego muestre en un alerta el número mayor.

- Crear un programa que le pida al usuario primero un  números al usuario a través de un prompt y luego un segundo número para luego mostar en un alerta el número mayor, esta vez realizar el ejercicio ocupando un if ternario.

- Crear un programa que determine si un string introducido por un usuario empieza con un número o con una letra.

- Crear un programa donde se introduzcan los tres ángulos internos de un triángulo y se determine si el tríangulo es válido o no.

- Determinar si una palabra empieza con mayúscula o no.

- Determinar si un año dado es biciesto.

- Escribir un programa JavaScript en el que el programa escoge al azar un entero entre 1 y 10, el usuario , luego a el usuario se le pedirá que introduzca un número en un popup para intentar adivinarlo. Si la entrada del usuario coincide con el número de conjetura, el programa mostrará un mensaje de "buen trabajo" de lo contrario mostrará un mensaje de "No corresponde "

## Loops

### While

- Mostrar todos los números de 1 a n aumentando de 1 en 1 donde n lo ingresa el usuario en un popup

- Mostrar todos los números de 1 a N aumentando de 2 en 2 donde n lo ingresa el usuario en un popup

- Mostrar todos los números de N a 1 disminuyendo de 1 en 1 donde n lo ingresa el usuario en un popup

- Escribir utilizando console.log la tabla del 9

- Pedir al usuario que ingrese un número en un popup, hacer la suma de todos los dígitos, validar que el número ingresado no contenga letas.

- Realizar la suma de todos los números pares entre N y M donde N y M los ingresa un usuario.

- Realizar la sumatorio de los primeros N números, donde N es ingresado por el usuario.

- Realizar el factorial de los primeros N números.

### Ejercicios de divisores con while (o for)
- Encontrar todos los divisores de un número.

- Determinar si un número ingresado por el usuario en un loop es primo o no, validar que el número ingresado sea mayor o igual a dos.

- Crear un programa que determine si un número es perfecto o no, (se dice que un número es perfecto si el número es igual a sus divisores, ejemplos 6 = 1 + 2 + 3)

### Doble loop

- Generar los primeros N números primos, donde n es ingresado por el usuario.

- Generar los primeros N números perfectos.

## Patrones con Loop anidados 

Dibujar los siguientes patrones ocupando `document.write`, para rellenar los espacios vacíos se imprimer un espacio vacío.

Cuadrado lleno:

<pre><center>*****
*****
*****
*****
*****</center></pre>

Cuadrado hueco:

<pre><center>*****
*   *
*   *
*   *
*****</center></pre>

Tablero de Ajedrez:

<pre><center>* * * * * * * *
 * * * * * * * 
* * * * * * * *
 * * * * * * * 
* * * * * * * *
 * * * * * * * 
* * * * * * * *
 * * * * * * * 

</center></pre>
Cuadrado hueco:

<pre><center>*****
*   *
*   *
*   *
*****</center></pre>

Piramide Izquierda:

<pre><center>*     
**    
***   
****  
***** </center></pre>

Pirámide centrada

<pre><center>*
***
*****
*******
*********</center></pre>

Pirámide invertida

<pre><center>*********
*******
*****
***
*
</center></pre>


Diamante:

<pre><center>*
***
*****
*******
*********
*******
*****
***
*
</center></pre>

## Funciones

- Crear una función que reciba un valor cualquiera y lo muestre ocupando console.log(), llamar a la función pasando el valor 5

- La siguiente función devuelve undefined en lugar de la multiplicación, se pide arreglarla
  
  ~~~js
	function multiply(a, b){
	  a * b
	}
   ~~~

- Crear una función que reciba dos valores y devuelva la suma de ellos.

- Crear una función que reciba un número entero y muestre un error si el tipo de dato pasado es de otro tipo.

- Crear una función autoejecutable que muestre "muuu" en pantalla

## Array

- Dado el array = [1,2,3,4,5,6]

	- Iterar por todos los elementos dentro de un array utilizando while y mostrarlos en pantalla.
	
	- Iterar por todos los elementos dentro de un array utilizando for y mostrarlos en pantalla.
	
	- Iterar por todos los elementos dentro de un array utilizando .forEach y mostrarlos en pantalla.
	
	- Mostrar todos los elementos dentro de un array sumándole uno a cada uno.
	
	- Generar una copia de un array pero con todos los elementos incrementado en 1.

	- Calcular el promedio

- Crear un array vacío, luego generar 20 números al azar y guardarlos en un array.

- Crear un array vacío, luego generar N números al azar y guardarlos en un array, N es introducido por el usuario a través de un propmpt.

- Dado un array que contiene ["azul", "amarillo", "rojo", "verde", "café", "rosa"] determinar si un color introducido por el usuario a través de un prompt se encuentra dentro del array o no.

## String y arrays

- El usuario ingrese un string con varias palabras separadas por coma en un popup y se deben convertir en un array, (el usuario ingresa: "1,2,3,4,5" y se convierte en [1,2,3,4,5])

- Convertir un array ingresado dentro del código en un string (existe un método en javascript para hacerlo)

### Unión, intersección y conteo

- Existen dos arrays, cada uno con 5 palabras, generar un nuevo array con la intersección de ambos elementos. (Ejemplo: [1,2,3] unión [1,2,4] = [1,2]

- Existen dos arrays, cada uno con 5 palabras, generar un nuevo array con la unión de ambos elementos, (Ejemplo: [1,2,3] unión [1,2,4] = [1,1,2,2,3,4]

- El usuario ingresa dos conjuntos de números separados por coma, el programa debe determinar si ambos conjuntos tienen la misma cantidad de números.

- El usuario ingresa dos conjuntos de números separados por coma, si ambos conjuntos tienen la misma cantidad de elementos mostrar un arreglo que contenga la suma de cada elemento. (Ejemplo: [1,2,3] + [2,3,4] = [3,5,7])

### Otros
- El usuario ingresa un conjunto de números separados por coma ahora se debe generar un array pero con el orden invertido.

## Matrices

- Recorrer un arreglo de arreglos para mostrarlo como una matirz, ejemplo [[1,1],[2,2]] se mostraría de la siguiente forma:

| 1  | 1  |
|----|----|
| 2  |  2 |


- Sumar [[1,1],[2,2]] con [[3,1],[3,2]]

- Contar la cantiad de elementos dentro de una matriz.

- Multiplicar una matriz por un escalar, si la matriz inicial es [[1,2,3],[4,5,6]], al multiplicarla por dos deberíamos obtener [[2,4,6],[8,10,12]]

- Encontrar el número mayor en una matriz.

- Determinar si un determinado número se encuentra dentro de una matriz o no.

- Devolver la suma de todos los elementos en la diagonal de la matriz.

- Mostrar la transpuesta de una matriz, o sea dado:

	|   1   |     2 |     3 |
	|-------|-------|-------|
	| **4** | **5** | **6** |
	| **7** | **8** | **9** |

	Debería quedar como:

	|   1   |     4 |     7 |
	|-------|-------|-------|
	| **2** | **5** | **8** |
	| **3** | **6** | **9** |

## Funciones y arreglos

- Crear una función que reciba un arreglo como parámetro y devuelva una copia del arreglo

- Crear una función que devuelva el promedio de un arreglo, en caso de que el arreglo esté vacío debe devolver cero.

- Crear una función que calcule el promedio dentro de un arreglo pero dentro de un rango, esta función recibe el arreglo, un punto de partida y uno de termino y devuelve el promedio de los valores dentro del rango especificado.

## Objetos

- Personas
	- Crear un objeto literal persona con nombre y edad y una método que determine si es mayor de edad o no.
	
	- Crear una función constructora que permita crear objetos personas pasandole solo un nombre y edad, agregar el método 
	
	- Crear un array que contenga varios objetos persona
	
	- Crear una función que reciba el array y devuelva la edad promedio del grupo de personas.
 
- Teléfono
	- Crear una función constructora que devuelva objetos del tipo teléfono, como argumento debe recibir un número de telefono, el objeto creado tiene el número de llamadas que debe ser inicializado en cero y un método llamar que debe aumentar el número de llamados en uno

## DOM

- Utilizando getElementById y innerHTML transformar el emoticon en un smiley

	~~~html
	<p id="demo"> :( </p>
	~~~

- Utilizando la instrucción setInterval mostrar la hora exacta y actualizarla cada segundo.


</section>
