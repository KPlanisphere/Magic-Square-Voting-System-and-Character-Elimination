# CUADRADO MAGICO
## PREGUNTA 1: Examen 2 - Programación 1

1. Escriba un programa en C que lea una matriz cuadrada de números enteros y determine si la matriz leída representa un cuadrado mágico. Implemente una función que reciba la matriz, evalúe si es cuadrado mágico y retorne un 1 si lo es y un 0 en caso contrario. Nota: Un cuadrado mágico es una matriz de números consecutivos (1..n^{2}), cuya disposición produce que la suma de los números por filas, columnas y diagonales sea la misma.

# SISTEMA DE ELECCIONES
## PREGUNTA 2:
2. Escriba un programa en C que simule un sistema de votaciones, considerando lo siguiente:
	- El sistema debe tener, únicamente, dos tipos de usuario:
		- El votante.
		- El administrador (Usuario: admin, Password: 1234).
	- Al ejecutarse el programa, debe imprimirse el siguiente menú:
		- Votar. Esta opción debe invocar una función que lea los datos del votante (matricula, contraseña) y validar si es un usuario válido. Si el usuario es correcto, se debe proceder a la votación, imprimiendo el siguiente menú.
			- Candidato 1
			- Candidato 2
			- Anular
		Una vez el usuario haya emitido el voto, se debe invocar a una función que incremente los votos del candidato seleccionado.

		- Finalizar votación: Esta opción debe invocar una función que lea los datos del administrador y validar si es un usuario válido, si lo es, se debe finalizar la votación e invocar a una función que imprima los resultados (Votos del candidato 1, votos del candidato 2, votos nulos).

Para la elaboración de este programa tomé en cuenta lo siguiente:
- La función para leer y validar los datos del votante y del administrador debe ser la misma.
- Por ningún motivo, un usuario que no sea administrador puede finalizar la votación.
- Sólo debe haber en su programa tres funciones:
	- primera para leer y validar los datos.
	- La segunda para votar. Es obligatorio que esta función reciba un único parámetro y su tipo de retorno sea void.
	- La tercera para imprimir los resultados: Es obligatorio que el tipo de retorno de esta función sea void.
- Se debe informar cuando un usuario sea inválido.
- El usuario debe tener registrados 3 votantes.
- No se debe usar arreglos.
- No utilice estructuras (struct).
- Las variables para el conteo de votos deben estar declaradas en el main.

# ELIMINACIÓN DE CARACTERES
## PREGUNTA 3:

3. Escriba un programa en C que lea una cadena y elimine un número específico de caracteres de la cadena a partir de una posición dada. El programa deberá solicitar al usuario la cadena, la posición en la cadena a partir de la cual se borrarán los caracteres y el número de caracteres a eliminar.

Consideraciones del programa:
- Implemente una función que realice este proceso y reciba por parámetros la cadena, la posición y el número de caracteres por borrar
- No utilice una función de la librería ``string.h`` que ya realicé lo solicitado.
