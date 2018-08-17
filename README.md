# Algoritmo para la Generación de Árboles de Desiciones ID3
<br>

<div style="text-align: justify">

En general un árbol de decisiones representa un conjunto de reglas estructuradas jerárquicamente que puede servir para la clasificación y la toma de decisiones.Cada camino de la raíz a una hoja corresponde a una conjunción de evaluación de atributos  y el árbol en si es una disyunción de estas conjunciones.La mayoría de los algoritmos que han sido desarrollados para el aprendizaje mediante árboles de decisión son variantes de un algoritmo núcleo que emplea una búsqueda voraz top-down a través del espacio de los posibles árboles de decisión. Este acercamiento fue ejemplificado por los algoritmos ID3 (Quinlan 1986) y por su sucesor C4.5 (Quinlan 1993)

El conjunto de ejemplos deberá estar conformado por una serie de tuplas de valores, cada uno de ellos denominados atributos, en el que uno de ellos, ( el atributo a clasificar ) es el objetivo, el cual es de tipo binario( positivo o negativo, sí o no, válido o inválido. Tambié se debe tener en cuenta que ID3 solo trabaja con atributos nominales. ID3 realiza su labor mediante la construcción de un árbol de decisión, cuyos elementos son: 
</div> 
<ol>
<li>Nodos: Los cuales contendrán atributos.</li>
<li>Arcos: Los cuales contienen valores posibles del nodo padre. </li>
<li>Hojas: Nodos que clasifican el ejemplo como positivo o negativo (valores del atributo clase)</li>
</ol>

<br>
<div style="text-align: justify">


La heurística del algoritmo se basa en seleccionar el atributo que mayor incida en la clasificación para ello usaremos el estadístico llamado Ganancia de Información.Este nos da una medida de efectividad de un atributo en la clasificación del conjunto de entrenamiento.
La Ganancia de Información a su vez utiliza la entrepía de de información que nos da la medida de la cantidad de ruido o desorden que contiene o libera un sistema. Caracteriza la (im)pureza de una colección arbitraria de datos. Por tanto la Ganancia de Información es la reducción esperada en la entropía del conjunto casusada por conocer un atributo A cualquiera. A continuación se implementa el algoritmo ID3 utilizando la biblioteca Graphviz para la estructura de datos de árbol y la visualización.
</div> 
