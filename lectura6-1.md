# Crítica a Deep Learning Based Recommender System: A Survey and New Perspectives. Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019)

[link paper](https://dl.acm.org/doi/10.1145/3285029)

Este paper habla acerca del aporte de Deep Learning que ha realizado a los sistemas de recomendación.

Estoy de acuerdo que faltan más publicaciones relacionadas con Deep learning y sistemas de recomendación, y por lo cual se realizó esta review donde se puede entender en detalle la relación de mutuo beneficio entre ambos. Cada año el estado del arte en Deep Learning mejora, por lo mismo aprovechar estas innovadoras ventajas para los sistemas de recomendación es una oportunidad de crecer en los diferentes escenarios, tales como tareas, dominios y recomendaciones.

En dos cosas estoy en desacuerdo: (1) las redes neuronales son una caja negra; existe una tendencia denominada Explainable Artificial Intelligence (XAI) que usa diferentes técnicas para intentar explicar el comportamiento y como aprenden las redes neuronales, como por ejemplo lo realizado por Elayan et. al. [1] donde se modela el comportamiento de los usuarios, pero se debe entender como ese comportamiento puede influenciarse para mejorar ciertas actividades, como por ejemplo el uso de energía eléctrica, y esto lo hacen mediante XAI aplicado a IoT y (2) la cantidad de ajustes en los hiper-parámetros; si bien una mayor cantidad de complejidad del modelo implica mayor cantidad de ajustes para encontrar los mejores hiper-parámetros, lo que produce una mayor demanda de computo, existen trabajos como el de Frankle y Carbin [2] donde exponen que buenas formas de diseñar los modelos (hiper-parámetros) puede reducir la cantidad de parámetros y por consiguiente el computo para esto.

Los autores dan una buena perspectiva toxonómica del aporte de Deep learning a los sistemas de recomendación y como significativamente han mejorado los resultados sobre los modelos tradicionales, lo que ejemplifica el gran impacto, no solo en sistemas de recomendación, que ha realizado Dee Learning en la gran mayoría de las tareas donde se ha aplicado.


[1] Haya Elayan and Moayad Aloqaily and Mohsen Guizani, Internet of Behavior (IoB) and Explainable AI Systems for Influencing IoT Behavior. 2021. https://arxiv.org/abs/2109.07239

[2] Jonathan Frankle and Michael Carbin. The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks. 2019. https://arxiv.org/abs/1803.03635

