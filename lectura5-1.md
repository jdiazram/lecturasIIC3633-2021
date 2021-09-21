# Crítica a Combining Predictions for Accurate Recommender Systems. Jahrer, M., Töscher, A. and Legenstein, R. (2010)

[link paper](https://dl.acm.org/doi/10.1145/1835804.1835893)

Este paper habla acerca de como el uso de varios modelos ensamblados pueden entregar mejores resultados que solo modelos por separado.

Me parece bueno el detalle de la explicación de los modelos usados, ya que con esto se puede reproducir el paper junto a sus experimentos, con el fin de explicar los resultados y conclusiones, para entender de mejor manera lo obtenido por los autores. Un detalle negativo es no explicar en detalle porque se usó un cierto tipo de parámetro; creo que debe ser trasparente este tipo de información, porque da la sensación de que los parámetros fueron casualmente correctos para obtener buenos resultados, en comparación a mostrar un historial de experimentos variando los parámetros y validando cual fue el mejor de ellos.

Otro detalle interesante es entregar los ordenes “O” de cada modelo, así la reproducibilidad de estos quedaría limitada a los requerimientos computacionales que se cuenten para los experimentos. Si bien este paper es del 2010, actualmente en términos de hardware, se ha avanzado y caros componentes son mas cercanos para la replica de estos experimentos y mejorar los resultados, por ejemplo ensamblando nuevos modelos robustos. 

Además, creo interesante la manera de mesclar los modelos mediante una combinación lineal (restando las predicciones a los datos originales para el siguiente modelo), aunque creo que hubiera sido mucho mas concluyente el uso de otras combinaciones de tal forma de dejar claro porque esa combinación lineal es mejor comparada con modelos aislados. Lo anterior también hubiera quedado mas claro realizando un estudio de ablación, sacando elementos importantes de cada modelo para ver el impacto de ese elemento en el resultado final.

Este tipo de trabajos, muestra las ventajas de usar ensambles, puesto que se toma lo mejor de cada modelo y se mezcla con las mejores características de otros, con el fin de obtener mejores resultados en general, pero siempre teniendo en consideración los datos a usar y manteniendo las propiedades estadísticas de ellos, por ejemplo la distribución de los datos, ya que al dividir para el proceso de entrenamiento y de test (probe set para este caso) se puede perder información valiosa teniendo buenos resultados en las métricas de medición, pero sin sentido.
