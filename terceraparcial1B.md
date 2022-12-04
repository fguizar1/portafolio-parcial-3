# presentacion 
## Problemas resueltos en clase de diagramas de flujo 
### Ejercicio 1. Utilizando dos vectores capture edad y semestre de un estudiante 
#### 1.1 Analisis 
Se necesita un proceso en el que almacenemos un array de 100 para despues preguntar el numero de estudiantes e introducir el numero, para despues introducir un numero, y asi tener una condicion, para posteriormente empezar con un ciclo For y poder calcular la edad y que este dentro de el rango, y asi hacer lo mismo con el semestre para despues tener la impresiones de ambas cosas y dar fin.
#### 1.2 Diagrama 

#### 1.3 Entradas 
se hace la entrada de de el numero de el estudiante, la edad y el semestre 
#### 1.4 Salidas 
La impresion de edad y el semestre 
#### 1.5 Prueba de escritotio 

### Ejercicio 2. 
#### 2.1 Analisis 
rellenar una matriz y pedir el numero de el estudiante para que te lo introduzca que debe de estar dentro de el rango para despues tener un ciclo For y preguntar por la edad, y si la edad esta dentro de el rango se continua y si no se da un error despues tener un proceso M[i,0]= edad, para despues preguntar por el semestre y si esta dentro de el rango avanza para despues imprimir la matriz y dar fin.
#### 2.2 Diagrama 

#### 2.3 Entradas 
edad, num de estudiante y semestre
#### 2.4 Salidas 
la impresion de la matriz 
#### 2.5 Prueba de escritorio 
### Ejercicio 3 Rellenar una matriz cuadrada de nxn con un numero leido de el teclado 
#### 3.1 Analisis 
se necesita una matriz de 50,50 para despues que ingresen el tamaño de la matriz y si es mayor a 2 y menor que 50 pasa y si no marcara fuera de rango despues decir que nos den el numero leido de el teclado y que nos den el numero y si es mayor que 0 y menor que 50 pasa y si no fuera de rango para despues tener 2 ciclos For uno que sea i=0;i<n;i++ y el otro j=0;j<n;j++ para despues tener un proceso que la matriz este dentro de i y j y asi el final.
#### 3.2 Diagrama 

#### 3.3 Entradas 
el tamaño de la matriz, el numero de el teclado 
#### 3.4 Salida
se rellena la matriz 
#### 3.5 Prueba de escritrio 

Ejercicio 4. Rellenar una matriz con numeros consecutivos hasta nxn 
#### 4.1 Analisis 
se necesita una matriz de 50,50 para despues preguntar el tamaño de la matriz y si es mayor a 1 y menor o igual a 50 pasa si no fuera de rango para despues tener dos ciclos For i=0;i<n;i++ y el otro j=0;j<n;j++  y asi tener en la matriz que M[i,j] = C y despues tener que C = C+1 y que entre en un ciclo y haga lo mismo en el otro y asi dar la matriz con numeros.
#### 4.2 Diagrama 

#### 4.3 Entardas 
se necesita la entrada de el tamaño de la matriz 
#### 4.4 Salidas 
la matriz rellenada con numeros consecutivos 
#### 4.5 Prueba de escritorio 

Ejercicio 5. rellenar una matriz con numeros 
#### 5.1 Analisis 
se necesita una matriz de [100,100] para despues pedir el numero de la matriz si es mayor que 1 y menor que 99 pasa si no da fuera de rango para despues tener dos ciclos For i=0;i<n;i++ y el otro j=0;j<n;j++ y despues un proceso que sea M[i,j]=j+1 y despues que pase por los dos ciclos y dar fin.
#### 5.2 Diagrama 

#### 5.3 Entradas 
la entrada de el numero de la matriz 
#### 5.4 Salidas 
la matriz con numeros 
##### 5.5 Prueba de escritorio 

### Ejercicio 6. Generar una matriz cuadrada 
#### 6.1 Analisis 
se necesita una matriz de 100, 100 para despues pedir el tamaño de la matriz si la matriz es mayor que 1 y menor o igual que 100 entonces pasa y si no entonces se regresa, para despues tener dos ciclos For i=0;i<n;i++ y el otro j=0;j<n;j++ y despues decir que si j = i si es si entonces un proceso que diga que M[i,j] = i+1 y si es no M[i,j] =0 y pasan por los ciclos dando fin al diagrama 
#### 6.2 Diagrama 

#### 6.3 Entradas 
la entrada de el tamaño de la matriz 
#### 6.4 Salidas 
la matriz diagonal con numeros consecutivos 
#### 6.5 Prueba de escritorio 

### Ejercicio 7. 
#### 7.1 Analisis 
se necesita una matriz de 100,100 para despues preguntar el tamaño de la matriz despues ssi la matriz es mayor igual a 2 y menor igual a 100 si es si avanza y ponemos nuestro primer ciclo i=0;i<n;i++ y el otro j=0;j<n;j++ para despues tener que si j=i si es si entonces un proceso M[i,j]=i+1 y si es no otro proceso M[i,j]j=0 para despues dar fin.
#### 7.2 Diagrama 

#### 7.3 Entrada
el tamaño de la matriz 
#### 7.4 Salida
el relleno de la matriz 
#### 7.5 Prueba de escritorio 

###Ejercicio 8.
#### 8.1 Analisis 
se necesita un array de n un contador que sea = 1 y una suma = 0 para despues preguntar cuantos numeros y despues tener una condicion de que si es mayor a 0 y menor igual a 100 pasa si no fuera de rango y despues tener un ciclo For i=0;i<n;i++ para despues un proceso de A[i]=S+C y despues otro proceso de S=S+C y despues otro proceso de C=C+1 para despues regresar al proceso y dr fin despues de el contador.
#### 8.2 Diagrama 

#### 8.3 Entradas 
el numero de el array 
#### 8.4 Salidas 
la suma de el array 
#### 8.5 Prueba de escritorio 

### Ejercicio 9.
#### 9.1 Analisis 
se necesita una matriz de 5,5 para despues preguntar el tamaño de la matriz para despues una condicion de que tenga que ser mayor a 1 y menor a 6 para despues tener dos ciclos For  i=0;i<n;i++ y el otro j=0;j<n;j++ y un proceso M[i,j] y asi seguir y despues que nos lleve a otro ciclo i=0;i<n;i++ para despues otro proceso DP=DP+M[i,j] y despues otros dos ciclos i=0;i<n;i++ y el otro j=0;j<n;j++ y una condicion de que si i+j=n-1 si es si un proceso DI=DI+M[i,j] y si es no pasa directo para despues otra condicion DI>DP si es si imprimir DI es mayor y si es no DP es mayor para poder dar fin.
#### 9.2 Diagrama 

#### 9.3 Entrada
el tamaño de la matriz 
#### 9.4 Salida
la impresion de dos numeros 
#### 9.5 Pruebas de escritorio 

### Ejercicio 10. El 1B quiere conocer el promedio por persona y por materia, ademas la materia con mejor promedio grupal y con mejor promedio. son 7 materias y 31 alumnos, menciona los alumnos en riesgo.
#### 10.1 Analisis 
se necesita una matriz de [1,31] VA[33] VM[7] empezamos teniendo dos ciclos i=0;i<n;i++ y el otro j=0;j<n;j++ para despues tener un proceso VA[i]=VA[i]+M[i,j] y despues volver a repetir todos los ciclos una y otra y otra vez y dar fin. 
#### 10.2 Diagrama 
[DFD10-MD.jpg](https://postimg.cc/pmFnvjyv)
#### 10.3 Entrada
La entrada de el numero de alumnos, las materias 
#### 10.4 Salidas 
el promedio por persona y por materia, el promedio grupal y el mejor promedio 
#### 10.5 Prueba de escritorio 

