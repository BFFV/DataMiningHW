Consideraciones:

- Para probar con la base de datos completa se recomienda utilizar un support de 100. Con esto se 
demora menos de 10 segundos en hacer el fit() y entrega una gran cantidad de reglas útiles.

- NO se recomienda utilizar un support muy bajo (alrededor de 50), ya que el algoritmo se queda 
demasiado rato ejecutando y los itemsets frecuentes serán de mala calidad.

- Se incluyeron ejemplos de prueba en la parte de cargar los datos. Estos sirven para probar 
el algoritmo en bases de datos pequeñas. En algunas de sus reglas la Conviction tendía a infinito,
 por lo que se aproximó dividiendo por un número pequeño en vez de 0.