# Radioastronomia Solar - Proyecto de procesamiento de una señal "Paso del Sol" capturada por un Radio Telescopio Casero.

Sobre el Radio Telescopio Casero:
Consiste en una antena de TV satelital (Sky en este caso) de forma parabólica, sobre una base plana hecha de madera. La antena es conectada mediante cable coaxial al amplificador "Sat Finder" y este mediante una conexión de cable auxiliar (audio) con Jack 3.5 mm hacia la entrada del microfono de una computadora. La lectura de los datos se realizó mediante el software Radio-Sky Pipe II.

El código contiene:
1. Lectura de los datos adquiridos por el programa Radio-Sky Pipe en archivo .csv
2. Ploteo de los datos con la columna "SPU" y "Fecha"
3. Preliminar de un ajuste de los datos a una Gaussiana, por corregir.
