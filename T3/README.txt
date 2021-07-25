Consideraciones:

- Se incluyen las 2 bases de datos utilizadas dentro del archivo '.zip' (1 de elecciones, 1 de coordenadas geográficas).

- El programa fue desarrollado en Python 3.7.

- Se utilizaron las siguientes librerías adicionales:

	- numpy, pandas (Data Science)
	- xlrd (es necesario tenerla instalada para que pandas pueda usar la función read_excel())

- Si se requiere probar el algoritmo utilizando valores grandes de K (mayores a 7), se deberán agregar más colores a la lista 'colors' 
que se encuentra dentro de la función 'plot_clusters()', sino va a resultar en un error al no tener 1 color distinto para cada cluster.