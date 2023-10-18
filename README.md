# Codigos-CC3001---Algoritmos-y-Estructuras-de-Datos
Una colección de códigos de tareas interesantes realizadas para el curso "Algoritmos y Estructuras de Datos".

Sobre Tarea 1:
- El objetivo principal de esta tarea fue estudiar un problema inspirado en un fenómeno físico, a través de un modelo matemático, el cual si bien es sencillo, produce resultados que presentan una estructura muy interesante. El fenómeno físico asociado tiene que ver con la formación de una pila de arena, la cual tras un punto colapsa y se derrama hacia los lugares vecinos con cierta predicción simplificada.
- Para esto se debió implementar una función en Python que, según un número N que representa la cantidad de granos de arena, entregara en una matriz de numpy la imagen de cómo se vería la distribución de los granos de arena siguiendo este modelo.
- Algunas modificaciones que realizaría a esta tarea para mayor eficiencia, sería simplemente redistribuir cada vez que se encuentre algo >=4 en vez de usar np.argmax en cada iteración.
