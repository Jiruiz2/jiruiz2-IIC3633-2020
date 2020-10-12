# Crítica: Carousel Personalization in Music Streaming Apps with Contextual Bandits

Los proveedores de archivos multimedia, como las plataformas de streaming de música, frecuentemente utilizan carruseles deslizables para recomendar contenido a sus usuarios. Sin embargo, seleccionar los *items* más relevantes para recomendarle a una persona es algo complicado. Por esto es que los autores plantearon como solución la modelación del carrusel deslizable como un problema del bandido multibrazo con multiples reproducciones, realizando actualizaciones basadas en el método cascada y usando feedback retrasado por grupo. Por último, probaron sus resultados con un grupo de usuarios reales, comprobando la efectividad del *framework* que ofrecían.

Considero que los carruseles deslizables son una muy buena opción a la hora de recomendar, ya que permiten recibir feedback de manera más sencilla por parte del usuario debido a que le aportan interactividad, invitándolo a participar para poder descubrir nuevas recomendaciones que no le aparecieron inicialmente.

Me parece sumamente útil el hecho de que se aseguren de definir términos como "Carrusel deslizable" o "Bandidos multibrazos" al introducir el tema, ya que facilita mucho la lectura y el entendimiento de la misma.

Creo que los autores tomaron una buena decisión al asumir que no podían saber exactamente cuantas tarjetas fueron vistas por cada usuario, ya que, como bien mencionan, en las aplicaciones reales, las personas no hacen click en las tarjetas, sino que "deslizan" la pantalla.

Pienso que los autores tomaron una buena decisión al iniciar con experimentos *offline*, ya que estos son mucho menos costosos que su opción *online*, aunque sus resultados pueden no ser tan robustos en comparación a los obtenidos en un entorno más realista. Sin embargo, al momento de realizar investigaciones el presupuesto es una restricción importante, por lo que definir la mejor manera de modelar el problema utilizando una simulación del comportamiento de los usuarios es una opción acertada.

Me sorprendió que las recomendaciones semi-personalizadas tuvieran un mejor desempeño que las totalmente personalizadas, ya que la intuición dice que mientras más se tome en consideración a la persona, mejor serán los resultados que obtendrá el algoritmo. Sin embargo, puede que lo ocurrido no se deba a que la completa personalización de las recomendaciones sea una mala opción, sino a que es muy complicado poder categorizar a un usuario para conseguir recomendarle lo más adecuado para el o ella.

Por su parte, los experimentos "online" son los que otorgan resultados más definitorios a la hora de confirmar si una idea es realmente un aporte, ya que se puede verificar de manera directa cómo los usuarios interactúan con la aplicación y si esta les resulta útil o no.

Por último, me parece sumamente destacable el hecho de que hayan liberado el dataset para que pueda ser utilizado por otras personas, ya que uno de los principales problemas a la hora de idear un tema de investigación es disponer de un set de datos apropiado para lo que se está buscando demostrar.