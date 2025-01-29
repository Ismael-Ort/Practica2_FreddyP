Ismael Ortega: 10145335 
Yeremy Veloz: 10143628

Descripción

El programa realiza un desplazamiento de elementos dentro de un arreglo de cadenas de texto. El usuario proporciona una secuencia de datos y un valor entero T, que indica cuántas veces 
se deben realizar los desplazamientos. El arreglo se divide en dos mitades: la primera mitad se rota hacia la izquierda y la segunda mitad hacia la derecha, repitiendo el proceso T veces.

Ejecución

Ejemplo de Entrada y Salida

Entrada:

Digite la secuencia de datos (separado por espacio): df 23 45 34 33 h 5 2

Indique el valor de T: 4

Proceso Interno:

1. Rotación izquierda en la primera mitad (df 23 45 34 → 23 45 34 df → 45 34 df 23 → 34 df 23 45 → df 23 45 34)

2. Rotación derecha en la segunda mitad (33 h 5 2 → 2 33 h 5 → 5 2 33 h → h 5 2 33 → 33 h 5 2

Salida:

Resultado: df 23 45 34 33 h 5 2

Análisis de Rendimiento

El rendimiento del programa depende del tamaño del arreglo de entrada n y del número de desplazamientos T, ya que cada desplazamiento recorre aproximadamente n/2 elementos, lo que da una complejidad de O(T * n) 
en el peor caso, mientras que el uso de memoria adicional es mínimo porque el programa opera directamente sobre el arreglo proporcionado.
