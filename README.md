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
