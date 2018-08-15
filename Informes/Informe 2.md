# Parte 1: Colectar genes homólogos

1. ¿Qué función cumple el gen SRY? [2]

 * Este gen sin intrones codifica un factor de transcripción que es un miembro de la familia de proteínas de unión a ADN del grupo de alta movilidad (HMG). Esta proteína es el factor determinante de los testículos (TDF), que inicia la determinación del sexo masculino.

2. ¿Cuántos genes ortólogos están anotados en esa base de datos? [1]
 
 * Según NCBI el gen SRY humano tiene 28 ortólogos. [Sitio NCBI](https://www.ncbi.nlm.nih.gov/gene/6736) 

# Parte 2: Alineamiento múltiple

1. ¿Qué es el EMBL-EBI? [2]

 * Es el Instituto Europeo de Bioinformática, este desarrollo bases de datos, herramientas y software que hacen posible alinear, verificar y visualizar los diversos datos producidos en la investigación financiada con fondos públicos, y hace que la información esté disponible libremente para todos. 

2. ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas? [2]

 * MUSCLE, adecuado para alineaciones medianas. 

3. ¿Qué otros tipo de herramientas ofrece EMBL-EBI? [2]

 * Clustal Omega: Nueva herramienta de MSA que utiliza árboles de guía sembrados y técnicas de perfil de perfil HMM para generar alineaciones. Adecuado para alineaciones medianas y grandes.
 * Kalign: Herramienta MSA muy rápida que se concentra en las regiones locales. Adecuado para grandes alineaciones.
 * MAFFT: Herramienta MSA que usa transformadas rápidas de Fourier. Adecuado para alineaciones medianas y grandes.
 * MUSCLE: Herramienta precisa de MSA, especialmente buena con proteínas. Adecuado para alineaciones medianas.
 * MView: Transforme un resultado de Búsqueda de similitud de secuencia en una Alineación de secuencia múltiple o vuelva a formatear una Alineación de secuencia múltiple mediante el programa MView.
 * T-Coffee: Herramienta MSA basada en consistencia que intenta mitigar los riesgos de los métodos de alineación progresiva. Adecuado para pequeñas alineaciones.
 * WebPRANK: El EBI tiene un nuevo programa de alineamiento de secuencia múltiple que tiene en cuenta la filogenia y hace uso de información evolutiva para ayudar a colocar inserciones y eliminaciones.
[Alineación de secuencia múltiple (MSA)](https://www.ebi.ac.uk/Tools/msa/)

4. ¿Cuál es el costo de abrir un gap? [1]

 * Es de 1.53
5. ¿Cuál es el costo de extender un gap? [1]

 * Es de 0.123

6. ¿Cuál es la longitud total del alineamiento? [1]

 * La longitud es de 1935.
7. ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos? [2]

 * Viendo el árbol filogenético se puede decir que es Piliocolobus tephrosceles  (especie de primate).

8. ¿Cuál es el más lejano? [2]

 * Es Miniopterus natalensis (especie de murciélago).

9. ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro? [2]

 * Es Equus przewalskii (caballo).

10. ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye? [3]

 * Si el costo de gap aumenta habrá menor cantidad de inserciones, lo que resultará en una secuencia total más corta. En cambio si el costo gap disminuye habrà una mayor cantidad de inserciones resultando una secuencia total más larga. Esto también se puede entender por la forma en que el programa alinea las secuencias, ya que, si aumento el costo de abrir un gap el programa preferirá extender uno a que abrir otro (por el costo que este tiene), resultando en una secuencia más corta.

11. ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye? [3]

 * 

12. ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? [2]

 * Disminuyó la longitud de la secuencia de 1934 a 1895.

13. Prueba lo mismo, pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento. [2]

 * La longitud total del alineamiento aumenta de 1934 a 1989.

# Parte 3: Diseño de partidores

1. Agrega a tu informe una lista de los "LEFT PRIMER" y "RIGHT PRIMER" que obtuviste usando Primer3. [3]

 * LEFT PRIMER 1: AGAGTGAAGCGACCCATGAA
 * RIGHT PRIMER 1: TCTCTGTGCATGGCCTGTAA
 * LEFT PRIMER 2: TTACAGGCCATGCACAGAGA
 * RIGHT PRIMER 2: CTTGAGTGTGTGGCTTTCGT
 * LEFT PRIMER 3: GGATAGAGTGAAGCGACCCA
 * RIGHT PRIMER 3: TTTCTCTCTGTGCATGGCCT
 * LEFT PRIMER 4: AGATGCTGCCGAAGAATTGC
 * RIGHT PRIMER 4: GCTTTGTCCAGTGGCTGTAG
 * LEFT PRIMER 5: CGAAGATGCTGCCGAAGAAT
 * RIGHT PRIMER 5: CTACAGCTTTGTCCAGTGGC

2. Indica los partidores forward y reverse que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano. [5]

 * Escogí el left primer 1 junto con el right primer 1. Mi elección fue basada en el valor de Q que me entrega el programa AmplifX de cada primer (para los dos es de 95). Este valor es un valor de probabilidad y mientras más altos son los dos Q tendre una mayor probabilidad de que resulte mejor la amplificación. 

3. ¿Cuál es el largo del amplicón? ¿Y la temperatura de annealing sugerida? [3]

 * De 191 nucleotidos y de 54°C.







