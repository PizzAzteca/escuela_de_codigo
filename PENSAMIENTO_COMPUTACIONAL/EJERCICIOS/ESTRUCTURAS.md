# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo
* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

1. Inicio
2. Declarar (letra)char
3. Mostrar ("Escribe el caracter")
4. Asignar (letra)
5. SI (letra)==s || (letra)==n, ENTONCES mostrar ("El caracter ok") SINO  mostrar ("El caracter no") 
finsi
6. fin

![image](https://user-images.githubusercontent.com/68087383/164299358-45691330-52b5-40ab-b749-b5f3c3363e60.png)


* Un programa que pida una letra y detecte si es una vocal. 

1. inicio
2. declarar (letra)char
3. mostrar ("Escribe la letra")
4. asigna (letra)
5. SI (letra)==a || (letra)==e || (letra)==i || (letra)==o || (letra)==u, ENTONCES mostrar ("La letra es una vocal") SINO mostrar ("La letra no es una vocal") FINSI
6. fin

![image](https://user-images.githubusercontent.com/68087383/164302315-fa00a2dc-bcdb-41d7-a44b-dfbf90a421e8.png)


* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

1. inicio
2. declara (n1, n2, n3,res)int
3. mostrar ("Escribe el numero 1")
4. asigna (n1)
5. mostrar ("Escribe el numero 2")
6. asigna (n2)
7. mostrar ("Escribe el numero 3")
8. asigna (n3)
9. SI (n1) < (n2) ENTONCES 
{SI (n2) < (n3) ENTONCES
mostrar ("El orden es (n1),(n2),(n3)")
SINO 
[SI (n1) < (n3) ENTONCES[
mostrar ("El orden es (n1),(n3),(n2)") 
SINO
mostrar ("El orden es (n3),(n1),(n2)")
FINSI]
FINSI}
SINO
{SI (n1) < (n3) ENTONCES
mostrar ("El orden es (n2)(n1)(n3)")
SINO 
[SI (n2) < (n3) ENTONCES 
mostrar ("El orden es (n2)(n3)(n1)") 
SINO 
mostrar ("El orden es (n3)(n2)(n1)") 
FINSI]
FINSI}
FINSI
13. fin

Algoritmo sin_titulo
	Escribir "Escribe los 3 numeros"
	Leer n1
	Leer n2
	Leer n3
	Si n1<n2 Entonces
		Si n2<n3 Entonces
			Escribir "El orden es ',n1,',',n2,',',n3,'"
		SiNo
			Si n1<n3 Entonces
				Escribir "El orden es ',n1,',',n3,',',n2,'"
			SiNo
				Escribir "El orden es ',n3,',',n1,',',n2,'"
			Fin Si
		Fin Si
	SiNo
		Si n1<n3 Entonces
			Escribir "El orden es ',n2,',',n1,',',n3,'"
		SiNo
			Si n2<n3 Entonces
				Escribir "El orden es ',n2,',',n3,',',n1,'"
			SiNo
				Escribir "El orden es ',n3,',',n2,',',n1,'"
			Fin Si
		Fin Si
	Fin Si
FinAlgoritmo

* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.
* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
