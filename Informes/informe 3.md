# Parte 1: El artículo genoma

1. ¿Cuántos *Sequencing Projects* y *Analysis Projects* hay depositados en GOLD? ¿Cuál es la diferencia entre ambos? [2]

 * Hay 215.124 sequencing projects y 174.491 analysis projects. El primero es el organismo o muestra individual que apunta a la secuenciación. Un proyecto de genoma individual puede estar compuesto por más de una secuencia de tecnologías. Un proyecto de secuenciación puede ser un genoma aislado, o una muestra de metagenoma, o un transcriptoma, o un metatranscriptoma,, etc. A partir de una única muestra de biología, se pueden realizar múltiples proyectos de secuenciación diferentes. Mientras que el segundo es el procesamiento informático de un proyecto de secuenciación. Describe cómo se realizaron el ensamblaje y la anotación de un proyecto de secuencia. 

2. ¿Cuál es el dominio más representado en la base de datos, archea, bacteria, eukaryote, o virus? [1]

 * Bacteria con  276.030.

3. ¿Cuáles son los phyla más representados entre los proyectos de genomas bacterianos en la base de datos? [1]

 * Candidate division.

4. ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.) [1]

 * Medico con un 58,9%

5. ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma) [2]

 * The bonobo genome compared with the chimpanzee and human genomes. Prüfer K, et al. Nature 2012 Jun 28. 

6. Explica, qué es el N50, L50, y NG50. [3]

 * **N50**: Es la longitud de los contigs de forma que usando contigs de igual o mayor tamaño produce la mitad de las bases del genoma. Esto se puede calcular ordenando todos los contigs de mayor a menor, luego se hace una suma acumilativa y cuando se llega a la mitad de esta se ve el largo del contigs, ese valor será el N50 y representará el 50% de todo el genoma.
 * **L50**: Dado un conjunto de contigs, cada uno con su propia longitud, el conteo L50 se define como el menor número de contigs cuya suma de longitud produce N50.
 * **NG50**: La estadística NG50 es igual a N50, excepto que es el 50% del tamaño del genoma conocido o estimado que debe ser de la longitud NG50 o más. Esto permite comparaciones significativas entre diferentes conjuntos. En el caso típico en que el tamaño del conjunto no es más que el tamaño del genoma, la estadística NG50 no será más que la estadística N50.

7. ¿Cuál es el propósito de calcular estas estadísticas? [3]

 * Estas estadísticas se usan en el ensamblaje del genoma, que se aplican a la longitud de los contigs. El propósito del N50 es definir la calidad del ensamblaje del genoma, es ampliamente utilizado en el ensamblado o montaje de un genoma, especialmente en referencia a la longitud de los contig dentro de un proyecto de ensamblado de un genoma. En cambio el NG50 permite comparar diferentes conjuntos , ya que implica que el tamaño del genoma debe ser la de la longitud NG50 o mas.

8. ¿Cuántos contigs conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los contigs) [3]

 * 121.356 contings conforman el genoma del Bonobo. Su N50 es de 66.676 y el L50 es de 11.048.

9. ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?

 * El largo total es de 3286.64 Mb y el %GC es 42.3185. El GC% representa la cantidad de pares Guanina-Citosina en el genoma y el largo del genoma varía proporcionalmente a la complejidad del organismo: cuanto más complejo es un organismo, mayor es también la cantidad de ADN, y en consecuencia de genes, contenida en sus células.

10. ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?

 * Para ensamblar se utilizó Celera Assembler v. 5.4.3 y para secuenciar se usó 454 GS FLX; 454 GS FLX Titanium

----------

# Parte 2: Predicción de genes

1. Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [start] y término [stop])? [3]

 * Se encontraron 7 ORFs. El 1, 2, y 3 se encuentran en la hebra positiva y el 4, 5, 6, y 7 están en la negativa. El largos de los ORFs son los siguientes: ORFs1: 302 aa ORFs2: 25 aa ORFs3: 32 aa ORFs4: 146 aa ORFs5: 134 ORFs6: 27 aa ORFs7: 47 aa. Se sobreponen 5 y 3, 4 y 2, 6 y 4, 7 y 1.

2. ¿Qué tipo de programa es ORFfinder, Ab initio o por homología? [2]

 * Es Ab initio, porque busca marcos de lectura abiertos (ORF) en una secuencia de ADN.

3. ¿A qué organismo pertenece la secuencia en cuestión? [2]

 * Haemophilus influenzae

4. ¿Qué gen(s) está(n) codificados en la secuencia? [2]

 *  `FdhE superfamily, NAT_SF superfamily y DNA_III_psi.`

5. Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)? [3]

 * El 1, 4 y 5. Porque los otros se encuentran "insertados" en los mencionados mientras que estos son la secuencia completa le los genes nombrados en la respuesta de la pregunta 4.
 

##### *ROSARIO BRAVO*