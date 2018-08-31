# Laboratorio 04 - Filogenética Molecular

1. ¿Qué ofrece o para qué sirve el portal Phylogeny.fr? [2]

 *  Proporciona una plataforma de alto rendimiento que encadena de manera transparente programas relevantes para el análisis filogenético en una cartera integral y flexible. Ayuda a los biólogos sin experiencia en filogenia a analizar sus datos de manera robusta.

2. Nombra y explica brevemente los 3 modos en los que se puede ejecutar el pipeline de Phylogeny.fr. [2]

 * El ["modo One Click"](http://www.phylogeny.fr/simple_phylogeny.cgi)  se dirige a los usuarios que no desean ocuparse de la selección de programas y parámetros. Por defecto, la canalización ya está configurada para ejecutarse y conectar programas reconocidos por su precisión y velocidad ( MUSCLE para alineación múltiple y PhyML para filogenia) para reconstruir un árbol filogenético robusto a partir de un conjunto de secuencias.
 * En el ["Modo avanzado"](http://www.phylogeny.fr/advanced.cgi) , el servidor de Phylogeny.fr propone la sucesión de los mismos programas, pero los usuarios pueden elegir los pasos a realizar (alineación de secuencia múltiple, reconstrucción filogenética, dibujo de árbol) y las opciones de cada programa.
 * El ["modo a la carta"](http://www.phylogeny.fr/alacarte.cgi) ofrece la posibilidad de ejecutar y probar más programas de alineación y filogenia, como MUSCLE, ClustalW, T-Coffee, PhyML, BioNJ, TNT, entre otros.

3. Menciona qué tipos de análisis se pueden realizar en el portal de acuerdo a la documentación. (Online Programs) [2]

 * Búsqueda de secuencias homólogas, Alineación múltiple, Filogenia, Análisis filogenéticos (visualizar arboles), Refinamiento de alineación y Conversión de formato. 

4. Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste. Recuerda que tu nombre completo debe aparecer en la imagen de cada filogenia (Name of the analysis). [2]

 * ![Filogenia 1](https://github.com/charoobravo/Laboratorio-Bioinformatica/blob/master/Imagenes/filogenia%20n%C3%BAmero%201.png?raw=true)
 *![Filogenia 2](https://github.com/charoobravo/Laboratorio-Bioinformatica/blob/master/Imagenes/filogenia%20n%C3%BAmero%202.png?raw=true)

5. ¿A qué se refiere el paso de Alignment curation y para qué sirve? [3]

 * Es cuando se eliminan regiones mal alineadas (GAPS) con el propósito de mejorar la alineación, disminuir el tiempo en la construcción de árboles y mejorar estos últimos para así obtener una filogenia más clara. Dicho proceso posee dos opciones, una que es más estricta donde simplemente se eliminan posiciones con espacios (Gblocks) y otra más simple.

6. ¿Cuál es la diferencia entre BioNJ y Neighbor? [3]

 * BioNJ Y Neighbor son programas utilizados para hacer filogenia usando distancia. Los dos son de rápida velocidad, aunque presentan limitaciones cuando el numero de taxones para BioNJ es menor a 5000 y para Neighbor menor a 500.

7. Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste (sin Alignment curation). Recuerda que tu nombre completo debe aparecer en la imagen de cada filogenia (Name of the analysis). [2]

 * ![Filogenia 1.2](https://github.com/charoobravo/Laboratorio-Bioinformatica/blob/master/Imagenes/filogenia%20n%C3%BAmero%201.2.png?raw=true)
 * ![Filogenia 2.2](https://github.com/charoobravo/Laboratorio-Bioinformatica/blob/master/Imagenes/filogenia%20n%C3%BAmero%202.2.png?raw=true)

8. ¿Cuál es el efecto de no hacer la curación del alineamiento en las filogenias? [3]

 *  Cuando no se realiza la curación del alineamiento se obtiene una filogenia más inespecífica porque en esta se encuentran todos los errores de la alineación, provocando que no sea posible inferir que organismo es el ancestro en común ni cual es el descendiente, debido a que en los últimos los organismos muchas ramas salen de un nodo, entonces no se puede definir las relaciones que hay entre ellos. 

9. Describe las diferencias entre las filogenias que has estimado (4 en total): cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc. [5]

 * La filogenia 1ª se realizó utilizando como programa de alineamiento múltiple ProbCons que es de alta precisión pero de largo tiempo computacional, se curó con GBocks que es más estricto que simplemente eliminar posiciones con gaps. La construcción del árbol filogenético se hizo con MrBayes que tiene un límite de 30 secuencias y para la visualización se usó TreeDyn.
 * La filogenia 2ª se realizó utilizando como programa de alineamiento múltiple ClustalW que es más rápido, se curó solo eliminando las posiciones con gaps (no estricto), la construcción del árbol filogenético se hizo con TNT y se visualizó con TreeDyn.
 * La 3ª y 4ª filogenia se realizaron de igual forma que 1 y 2 respectivamente, pero se eliminó el proceso de curación del alineamiento.
 * Analizándolas se puede ver lo mencionado en la respuesta anterior. Las filogenias curadas son más claras, y se ven muchos ancestros en común con sus correspondientes grupos. Otro efecto para mencionar es  que los organismos cambian de posición, cambian algunas relaciones entre ellos y el largo de las ramas varía.


#####*ROSARIO BRAVO SAMAHA*