# Crítica: Collaborative Filtering for Implicit Feedback Datasets
> Una de las formas más comunes y estudiadas para realizar recomendaciones es mediante el feedback explícito, como por ejemplo en base a ratings que pone el usuario a ciertos elementos. Sin embargo, los autores ofrecen un enfoque distinto que es utilizar datasets con feedback implícito para poder realizar recomendaciones a los usuarios. Para demostrar la validez de su enfoque utilizaron información sobre la cantidad de tiempo que los usuarios sintonizaron ciertos programas y realizaron recomendaciones sobre otros programas que los usuarios les podrían interesar. Los resultados señalaron que este modelo basado en feedback implícito realiza mejores recomendaciones en comparación al algoritmo "most popular" y "neighborhood".

> Siento que tienen ciertas fórmulas que no explican bien desde donde aparecen o por qué se decide utilizar estas por sobre otras, un ejemplo de esto es lo que ocurre en la sección 6, donde definen la fórmula de peso para un show en específico pero nunca explican el por qué de esta.

> Por otro lado, siento que al comparar su modelo con los otros, los resultados no son tan concluyendes, ya que el algoritmo "most popular" no da recomendaciones tan acertadas en comparación a otros debido a que no toma en cuenta las preferencias del usuario. Además, tampoco se plantea una comparación con distintos valores para la cantidad de vecinos en el algoritmo "Neighborhood", por lo que podría darse que para un valor óptimo de este parámetro el método ofrecido por los autores sea inferior.

> Por último, me gustaría señalar que creo que el utilizar feedback implícito es sumamente desafiante, ya que existe el problema de que uno no sabe a ciencia cierta qué es lo que está haciendo o pensando el usuario, por ejemplo, este puede tener sintonizado un programa de televisión, pero no verlo realmente. Pese a ello, considero que es un campo con un enorme potencial y si los autores consiguen agregar la flexibilidad suficiente al programa para poder superar ciertas limitaciones que les provee actualmente el dataset de feedback implícito, no tengo dudas de que se podría convertir en un mecanismo importante de recomendación.