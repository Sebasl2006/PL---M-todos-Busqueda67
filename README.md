## PRACTICA BUSQUEDA BINARIA
📌 Información General
Título: Práctica de Algoritmos de Ordenamiento
Asignatura: Estructura de Datos

Carrera: Computación

Estudiante: [Sebastian Lopez]

Fecha: [18/11/25]

Profesor: Ing. Pablo Torres
## DESCRIPCION
Generar una aplicación que, dado un arreglo y un elemento, lo busque dentro de su
arreglo implementando Búsqueda Binaria.

Presentar el siguiente funcionamiento:

• Entrada:

o Arreglo ingresado por teclado.
o Ordenar el arreglo con el método que desee.

• Salida:

o Arreglo en cada búsqueda, alto, bajo, valor de centro.

o Elemento encontrado o no.

o Indicar si va a buscar en el subarreglo de la derecha o 
izquierda. 

## EJEMPLO DE ENTRADA
EJEMPLO:
Ingrese Persona:

 Nombe: Pablo

 Edad: 4

Ingrese Persona:

 Nombe: Maria

 Edad: 5
 Ingrese Persona:

 Nombe: Juan

 Edad: 18
 
Ingrese Persona:

 Nombe: David

 Edad: 60

Ingrese Persona:

 Nombe: Mateo

 Edad: 25

Ingrese Persona:

 Nombe: Diego

 Edad: 12

Ingrese Persona:

 Nombe: Ana

 Edad: 8

Ingrese Persona:

 Nombe: Alicia

 Edad: 9

Ingrese Persona:

 Nombe: Jaime

 Edad: 40

 Valor la personada de la edad: 18


## EJEMPLO DE SALIDA
8 | 4 | 5 | 9 | 12 | 18 | 25 | 40 | 60

bajo=0 alto=8 centro=4 valorCentro=12 --> DERECHA

18 | 25 | 40 | 60

bajo=5 alto=8 centro=6 valorCentro=25 --> IZQUIERDA

18 |

bajo=5 alto=5 centro=5 valorCentro=18 --> ENCONTRADO

La persona con la edad 18 es Pablo






