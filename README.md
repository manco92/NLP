# NLP

El procesamiento de lenguaje natural, o NLP (por sus siglas en inglés referentes a Natural Language Processing), 
corresponde a una rama de ciencias de la computación, más específicamente al apartado de inteligencia artificial, 
la cual se encarga de otorgale a las computadoras la abilidad de interpretar texto y palabras habladas de una manera
muy similar a la que las personas la entendemos.

Este es un repositorio del curso de NLP correspondiente a la Especialización en Inteligencia Artificial de la 
Universidad de Buenos Aires. A continuación, enumero los 6 desafíos que me fueron planteados a lo largo de la cursada, explicados brevemente. La resolución de los mismos con las conclusiones correspondiente se encuentran en esta misma carpeta.

## DESAFÍO 1

En este desafío, creé funciones de conceptos básicos de NLP, como una función que obtenga el vocabulario, 
otra transforme a OHE una lista, otra que transforme una matriz TF-IDF, entre otras.

## DESAFÍO 2

Programé un bot basado en reglas. Lo diseñé para una tienda que vende café. 
Le agregué más categorías y para mejorar la performance cambié el bag of words que estaba hecho por TF-IDF.
Además, lo testeé con 4 personas diferentes. Cada persona formula diferents preguntas y tiene distintos sesgos, 
es por eso que al probarlo con más personas, se puede ir mejorando el bot cada vez más.

## DESAFÍO 3

Utilicé la biblia como dataset para crear los embeddings porque es un corpus muy popular y me resultó interesante analizarlo. 
Entrené 2 modelos: uno lematizando y removiendo las stopwords; y el otro sin. 
La explicación más detallada y las conclusiones están al final de cada notebook.

## DESAFÍO 4

Utilicé la novela EL Señor de los Anillos para entrenar el modelo de próxima palabra.
La explicación más detallada y las conclusiones están al final del notebook.

## DESAFÍO 5

Utilicé RNN (LSTM) para categorizar reseñas. Probé con embeddings sin entrenar y preentrenados. 
El objetivo es lograr una accuracy entre 0.50 y 0.70 en validación.
La explicación más detallada y las conclusiones están al final del notebook.

## DESAFÍO 6

Utilicé un esquema encoder-decoder para entrenar un bot.
La explicación más detallada y las conclusiones están al final del notebook.
