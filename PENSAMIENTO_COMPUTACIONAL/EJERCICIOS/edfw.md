1. inicio
2. asignar i==0
3. para i<=6
4. declarar (num,sum,i)
5. mostrar ("Escribe el numero para sumar")
6. asignar (num)
7. sum=sum+num
8. mostrar ("La suma de los numeros es (sum)")
9. asignar i++
10. finpara
11. fin

![image](https://user-images.githubusercontent.com/68087383/164778337-04725b7b-06ae-4cb9-ba3b-8308aeb0a5af.png)
![image](https://user-images.githubusercontent.com/68087383/164777240-23e7c7ea-8d74-4b09-9382-9891184b69e6.png)

![image](https://user-images.githubusercontent.com/68087383/164781473-c9f33ca3-48e0-48af-8f4e-31a2e0a00cbc.png)

Algoritmo sin_titulo
	Para i<-1 Hasta 10 Con Paso 1 Hacer
		Para tab<-1 Hasta 10 Con Paso 1 Hacer
			res<-tab * i
			Escribir "',tab,'x',i,'=',res,'" 
			
		Fin Para
	Fin Para
FinAlgoritmo


![image](https://user-images.githubusercontent.com/68087383/165593492-65f8a330-3eea-4e37-b8cb-a7bafd2e7783.png)
Algoritmo calificaciones 
	c<-0
	i<-1
	ma<-0
	me<-0
	Mientras i<11 Hacer
		Escribir "Ingresa la calificacion ',i,'"
		Leer c
		Si c<10 Entonces
			Si c>7 Entonces
				ma<-ma+1
			SiNo
				me<-me+1
			Fin Si
		SiNo
			Si c<0 Entonces
				Escribir "Escribe bien la calificacion"
				m<-m+1
				i<-i-1
			SiNo
				Si c>10 Entonces
					Escribir "Escribe bien la calificacion"
					m<-m+1
					i<-i-1
				SiNo
					
				Fin Si
			Fin Si
			Escribir "Escribe bien la calificacion"
			m<-m+1
			i<-i-1
		FinSi
		i=i+1
	Fin Mientras
	Escribir "Las calificaciones menores a 7 son ',me,', las mayores son ',ma,' y las incorrectas son ',m,'"
	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/68087383/165590561-085a66a0-54d8-4f70-b46b-aecb590edd3f.png)

![image](https://user-images.githubusercontent.com/68087383/165596956-c907d8e6-a174-43f9-acde-0ef61c6c860a.png)

Algoritmo calificaciones 
	c<-0
	i<-1
	ma<-0
	me<-0
	Mientras i<11 Hacer
		Escribir "Ingresa la calificacion ',i,'"
		Leer c
		Si c<10 Entonces
			Si c>7 Entonces
				ma<-ma+1
			SiNo
				me<-me+1
			Fin Si
		SiNo
			Si c<0 Entonces
				Escribir "Escribe bien la calificacion"
				m<-m+1
				i<-i-1
			SiNo
				Si c>10 Entonces
					Escribir "Escribe bien la calificacion"
					m<-m+1
					i<-i-1
				SiNo
					
				Fin Si
			Fin Si
			Escribir "Escribe bien la calificacion"
			m<-m+1
			i<-i-1
		FinSi
		i=i+1
	Fin Mientras
	Escribir "Las calificaciones menores a 7 son ',me,', las mayores son ',ma,' y las incorrectas son ',m,'"
	
FinAlgoritmo

![image](https://user-images.githubusercontent.com/68087383/165597036-61f209f6-d141-4bc0-b0ed-b4f562c5d7fc.png)
