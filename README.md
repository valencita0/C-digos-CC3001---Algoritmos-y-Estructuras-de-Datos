# Codigos-CC3001---Algoritmos-y-Estructuras-de-Datos
Una colección de códigos de tareas interesantes realizadas para el curso "Algoritmos y Estructuras de Datos".

Sobre Tarea 1:
- El objetivo principal de esta tarea fue estudiar un problema inspirado en un fenómeno físico, a través de un modelo matemático, el cual si bien es sencillo, produce resultados que presentan una estructura muy interesante. El fenómeno físico asociado tiene que ver con la formación de una pila de arena, la cual tras un punto colapsa y se derrama hacia los lugares vecinos con cierta predicción simplificada.
- Para esto se debió implementar una función en Python que, según un número N que representa la cantidad de granos de arena, entregara en una matriz de numpy la imagen de cómo se vería la distribución de los granos de arena siguiendo este modelo.
- Algunas modificaciones que realizaría a esta tarea para mayor eficiencia, sería simplemente redistribuir cada vez que se encuentre algo >=4 en vez de usar np.argmax en cada iteración.

Sobre Tarea 2:
- El objetivo principal de esta tarea fue desarrollar una calculadora de expresiones matemáticas al estilo Matlab o Maple, pero con capacidad de procesar un conjunto de comandos bien restringido.
- Esta tarea no me dejó del todo conforme con la organización general. Si pudiera hacerla de nuevo, cambiaría las siguientes implementaciones:
1) En vez de tener una función contar_operadores, habría juntado los operadores en una lista y recorrerla para operar los números.
2) Juntar el código repetido para mayor legibilidad.

Sobre Tarea 3:
- El objetivo principal de esta tarea fue escribir un programa que encuentre la solución a un tablero arbitrario de Sudoku. 
- Posibles mejoras a esta tarea tienen que ver con la distribución de los 'ifs' en la función auxiliar 'rec_imposible'.

Sobre Tarea 4:
- El objetivo principal de esta tarea fue trabajar con árboles que representan fórmulas generando códigos para evaluarlas. En concreto: Dada una fórmula, generar una secuencia de instrucciones elementales que la evalúen.

Sobre Tarea 5:
- El objetivo principal de esta tarea fue trabajar con árboles de búsqueda binaria posicional, implementando las clases Arbol, Nodoi y Nodoe con los métodos insert, search y find en todos lugares en donde corresponda.

Sobre Tarea 6:
- El objetivo principal de esta tarea fue comparar el desempeño de la versión original de Quicksort con el de la variante "Mediana de 3". En la primera, el método de partición debe elegir el pivote como el primer elemento del sub arreglo que está particionando. En la segunda, el pivote debe elegirse como la mediana entre el primero, el del medio y el último elemento.
- Posibles mejoras a esta tarea tienen que ver con una mejor distribución de los casos a revisar, tal que se tuviera un menor uso de if/else.
