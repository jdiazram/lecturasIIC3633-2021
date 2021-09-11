# Crítica a Content-Based Recommendation Systems. Michael J. Pazzani y Daniel Billsus. 2007

[link paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.448.662&rep=rep1&type=pdf)

Este paper habla acerca de los sistemas de recomendación basados en contenidos y como estos son usados en una gran variedad de dominios.

Existe una buena explicación de los algoritmos para crear modelos de las preferencias de usuarios mediante las historias de usuarios, visto desde el punto de vista de la clasificación.
Destacar también la relación directa que existe entre los sistemas de recomendación y la recuperación de información, ya que en los inicios de los sistemas de recomendación basado en contenidos usaban las consultas de usuarios para referirse al modelo de usuario.

Además, los autores destacan el hecho de que si no existen suficiente información para distinguir los interés de los usuarios (items que gustan y los que no) este tipo de sistemas no podrán dar buenas recomendaciones, con lo que estoy de acuerdo, ya que aprender los intereses de los usuarios es complejo en la medida de tener la información suficiente.

Creo faltó, quizás sea por la época (2007), más detalle en el uso y aplicación de los datos no estructurados o descripción de texto no estructurado, puesto que se hacía una transformación hacia texto estructurado, con lo cual se puede perder información valiosa, por ejemplo el significado de las palabras y su contexto dentro de la frase. Ahora con los Transformer (https://arxiv.org/abs/1706.03762) o los modelos de lenguaje actuales (por ejemplo BERT https://arxiv.org/abs/1810.04805, u otro modelo preentrenado) sería buena herramienta para resolver ese tipo de problemas, o como BERT4Rec (https://arxiv.org/abs/1904.06690)  que es un modelo que utiliza “deep bidirectional self-attention” para modelar secuencias de comportamientos de los usuarios, el cual se podría vincular con las historias de usuarios de paper leído y mejorar ese detalla faltante.
