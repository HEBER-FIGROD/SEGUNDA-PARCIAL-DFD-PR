# SEGUNDA-PARCIAL-DFD-PR
SEGUNDA PARCIAL DFD PR

Heber Emmanuel Figueroa Rodríguez

### Ejercicio 1 FOR. Contar del 1 hasta el 10 y sumar los valores.

#### 1.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable suma=0, despues utilizar el simbolo de ciclo de for para hacer un contador de i=1; i<=10; i++, en caso de que i sea menor a 10 se utiliza otro simbolo de proceso para ingresar s=s+i y se regressa al ciclo hasta que i sea mayor a 10 y al final se utiliza un simboo de salida para imprimir la suma de los numeos.

#### 1.2 DIAGRAMA DE FLUJO DE DATOS
[![0.jpg](https://i.postimg.cc/SQcrpp5f/0.jpg)](https://postimg.cc/K4vLnCm1)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|i  |i<=10|i++|s=s+i|s|
|---|---|-----|---|-----|-|
|0  |1  |si   |1  |1    |1|
|0  |1  |si   |2  |2    |2|
|0  |2  |si   |3  |3    |3|
|0  |3  |si   |4  |4    |4|
|0  |4  |si   |5  |5    |5|
|0  |5  |si   |6  |6    |6|
|0  |6  |si   |7  |7    |7|
|0  |7  |si   |8  |8    |8|
|0  |8  |si   |9  |9    |9|
|0  |9  |si   |10 |10   |10|
|0  |10 |si   |11 |     |55|
|0  |11 |no   |

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 CICLO FOR
i=1; i<=10; i++

###  1.7 CODIGO



### Ejecicio 1 Do/While. Contar del 1 al 10 y sumar los valores.

#### 1.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza otro simbolo de proceso para asignar s=c+s, volvemos a utilizar otro simbolo de proceso para asignar c=c+1, despues se utiliza un simbolo de decision para preguntar si c<=10, en caso de que si sea asi se regresa al simbolo de proceso de s=c+s, hasta que c sea = a 10 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 1.2 DIAGRAMA DE FLUJO DE DATOS
[![1.jpg](https://i.postimg.cc/VkbKVbjD/1.jpg)](https://postimg.cc/qN4ctqD3)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|c=1|s=c+s|c=c+1|c<=10|s|
|---|---|-----|-----|-----|-|
|0  |1  |1    |2    |si   |1|
|   |   |2    |3    |si   |2|
|   |   |3    |4    |si   |3|
|   |   |4    |5    |si   |4|
|   |   |5    |6    |si   |5|
|   |   |6    |7    |si   |6|
|   |   |7    |8    |si   |7|
|   |   |8    |9    |si   |8|
|   |   |9    |10   |si   |9|
|   |   |10   |11   |no   |10|
|   |   |     |     |     |55|

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 PROCESO
S=0
C=1
S=C+S
C=C+1

### 1.7 DECISION
C<=10

### 1.8 CODIGO



### Ejercicio 1 While. Contar del 1 al 10 y sumar los valores.

#### 1.1 ANÁLISIS
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza un simbolo de decision para preguntar si c<=10, en caso de que si sea asi se utiliza un simbolo de proceso que asigna las variables de s=c+s, despues se utiliza otro simbolo de proceso que asigna las variables de c=c+1, despues de regresa al simbolo de decision y asi repetidamente hasta que c sea mayor a 10 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 1.2 DIAGRAMA DE FLUJO DE DATOS
[![2.jpg](https://i.postimg.cc/52bR6STT/2.jpg)](https://postimg.cc/1f7Hdw9r)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|c=1|C<=10|s=s+c|c=c+1|s|
|---|---|-----|-----|-----|-|
|0  |1  |si   |1    |2    |1|
|   |   |si   |2    |3    |2|
|   |   |si   |3    |4    |3|
|   |   |si   |4    |5    |4|
|   |   |si   |5    |6    |5|
|   |   |si   |6    |7    |6|
|   |   |si   |7    |8    |7|
|   |   |si   |8    |9    |8|
|   |   |si   |9    |10   |9|
|   |   |si   |10   |11   |10|
|   |   |no   |     |     |55|

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 PROCESO
S=0
C=1
S=C+S
C=C+1

### 1.7 DECISION
C<=10

### 1.8 CODIGO




### Ejercicio 2 FOR. Obtenga la suma de los primero 5 numeros pares.

#### 2.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable suma=0, despues utilizar el simbolo de ciclo de for para hacer un contador de i=2; i<=10; i=i+2, en caso de que i sea menor a 10 se utiliza otro simbolo de proceso para ingresar s=s+i y se regressa al ciclo hasta que i sea mayor a 10 y al final se utiliza un simboo de salida para imprimir la suma de los numeos.

#### 2.2 DIAGRAMA DE FLUJO DE DATOS
[![3.jpg](https://i.postimg.cc/MKvFRGpb/3.jpg)](https://postimg.cc/rK2j2MWK)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|i  |i<=10|i+2|s=s+i|s|
|---|---|-----|---|-----|-|
|0  |2  |si   |2  |2    |2|
|0  |4  |si   |4  |4    |4|
|0  |6  |si   |6  |6    |6|
|0  |8  |si   |8  |8    |8|
|0  |10 |si   |10 |10   |10|
|0  |   |si   |12 |     |30|
|0  |   |no   |

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 CICLO FOR
i=1; i<=10; i++

###  1.7 CODIGO



### Ejecicio 2 Do/While. Obtenga la suma de los primeros 5 numero pares.

#### 2.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza otro simbolo de proceso para asignar s=s+c*2, volvemos a utilizar otro simbolo de proceso para asignar c=c+1, despues se utiliza un simbolo de decision para preguntar si c<=5, en caso de que si sea asi se regresa al simbolo de proceso de s=s+c*2, hasta que c sea mayor a 5 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 2.2 DIAGRAMA DE FLUJO DE DATOS
[![4.jpg](https://i.postimg.cc/sXpvTW4F/4.jpg)](https://postimg.cc/YGCr9hP8)

#### 2.3 PRUEBA DE ESCRITORIO
|s=0|c=1|s=s+c*2|c=c+1|c<=5|s|
|---|---|-----|-----|-----|-|
|0  |1  |2    |2    |si   |2|
|   |   |4    |3    |si   |4|
|   |   |6    |4    |si   |6|
|   |   |8    |5    |si   |8|
|   |   |10   |6    |no   |10|
|   |   |     |     |     |30|

#### 2.4 ENTRADAS
NINGUNA

#### 2.5 SALIDA
S

### 2.6 PROCESO
S=0
C=1
S=S+C*2
C=C+1

### 2.7 DECISION
C<=5

### 2.8 CODIGO






### Ejercicio 2 While. Obtener la suma de los primeros 5 numeros pares.

#### 2.1 ANÁLISIS
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza un simbolo de decision para preguntar si c<=5, en caso de que si sea asi se utiliza un simbolo de proceso que asigna las variables de s=s+C*2, despues se utiliza otro simbolo de proceso que asigna las variables de c=c+1, despues de regresa al simbolo de decision y asi repetidamente hasta que c sea mayor a 5 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 2.2 DIAGRAMA DE FLUJO DE DATOS
[![5.jpg](https://i.postimg.cc/633GpqdF/5.jpg)](https://postimg.cc/946fxWgB)

#### 2.3 PRUEBA DE ESCRITORIO
|s=0|c=1|C<=5 |s=s+c*2|c=c+1|s|
|---|---|-----|-----|-----|-|
|0  |1  |si   |2    |2    |2|
|   |   |si   |4    |3    |4|
|   |   |si   |6    |4    |6|
|   |   |si   |8    |5    |8|
|   |   |si   |10   |6    |10|
|   |   |no   |     |     |30|


#### 12.4 ENTRADAS
NINGUNA

#### 2.5 SALIDA
S

### 2.6 PROCESO
S=0
C=1
S=S+C*2
C=C+1

### 2.7 DECISION
C<=5

### 2.8 CODIGO

