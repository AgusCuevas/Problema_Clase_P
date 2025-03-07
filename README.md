# Investigación sobre los Problemas P

## Introducción

La teoría de la complejidad computacional estudia la eficiencia de los algoritmos en función del tiempo y espacio requeridos para resolver problemas. Dentro de esta teoría, la clase de problemas P (polinomial) juega un papel fundamental, ya que representa los problemas de decisión que pueden resolverse de manera eficiente con una Máquina de Turing Determinista (MTD).

## Definición de P
La clase P está conformada por todos los problemas de decisión que pueden resolverse en tiempo polinomial con una MTD. Formalmente, un problema pertenece a P si existe un algoritmo que lo resuelve en O(n^k), donde n es el tamaño de la entrada y k es una constante.

En términos prácticos, esto significa que los problemas en P pueden resolverse con algoritmos eficientes que son factibles en la práctica para valores razonables de n.

## Ejemplos de Problemas en P

Algunos ejemplos clásicos de problemas en P incluyen:

- **Ordenamiento de números** (QuickSort, MergeSort, HeapSort) con una complejidad de O(n log n).
- **Búsqueda en Grafos** con con una complejidad de O(n + m), donde n es el número de nodos y m el número de aristas.
- **Multiplicación de matrices** con una complejidad aproximada de O(n^2.37) usando algoritmos como el de Strassen.

## Relación con NP y NP-completos

P es un subconjunto de NP (Nondeterministic Polynomial time), que contiene los problemas para los cuales una solución propuesta puede verificarse en tiempo polinomial. Sin embargo, no se sabe si P = NP, lo que es uno de los mayores problemas abiertos en la computación teórica.

Dentro de NP existen los problemas NP-completos, que son al menos tan difíciles como cualquier otro problema en NP. Si se demostrara que un problema NP-completo está en P, entonces P = NP.

## Problemas P-Completos

Los problemas **P-completos** son aquellos que representan los problemas más difíciles dentro de la clase P en términos de paralelización. Son problemas en P a los que cualquier otro problema en P puede reducirse en tiempo polinomial mediante una reducción logspace. Algunos ejemplos incluyen:

- **Caminos más cortos en grafos** (en ciertos casos restrictivos).
- **Evaluación de circuitos booleanos**.

Estos problemas son importantes en el estudio de la paralelización de algoritmos, ya que si un problema P-completo puede resolverse eficientemente en paralelo, entonces probablemente todos los problemas en P puedan hacerlo también.

## Importancia de P en la Computación

La clase P es considerada la clase de problemas "fácilmente computables", ya que un problema que se resuelve en tiempo polinomial es generalmente tratable en la práctica. La clasificación de un problema como perteneciente a P permite a los diseñadores de algoritmos buscar soluciones eficientes en lugar de métodos de fuerza bruta exponenciales.

## Conclusión

Los problemas en P son fundamentales en la teoría de la complejidad computacional y en la práctica de la informática. Su estudio permite diseñar algoritmos eficientes y establecer los límites de la computación factible. La pregunta de si P = NP sigue siendo un problema abierto y su resolución tendría implicaciones profundas en la informática, matemáticas y muchas otras disciplinas.

## 
