Consideraciones:

- Se incluyen las 2 bases de datos utilizadas dentro del archivo '.zip' (1 de elecciones, 1 de coordenadas geogr�ficas).

- El programa fue desarrollado en Python 3.7.

- Se utilizaron las siguientes librer�as adicionales:

	- numpy, pandas (Data Science)
	- xlrd (es necesario tenerla instalada para que pandas pueda usar la funci�n read_excel())

- Si se requiere probar el algoritmo utilizando valores grandes de K (mayores a 7), se deber�n agregar m�s colores a la lista 'colors' 
que se encuentra dentro de la funci�n 'plot_clusters()', sino va a resultar en un error al no tener 1 color distinto para cada cluster.