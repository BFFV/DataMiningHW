Consideraciones:

- Para probar con la base de datos completa se recomienda utilizar un support de 100. Con esto se 
demora menos de 10 segundos en hacer el fit() y entrega una gran cantidad de reglas �tiles.

- NO se recomienda utilizar un support muy bajo (alrededor de 50), ya que el algoritmo se queda 
demasiado rato ejecutando y los itemsets frecuentes ser�n de mala calidad.

- Se incluyeron ejemplos de prueba en la parte de cargar los datos. Estos sirven para probar 
el algoritmo en bases de datos peque�as. En algunas de sus reglas la Conviction tend�a a infinito,
 por lo que se aproxim� dividiendo por un n�mero peque�o en vez de 0.