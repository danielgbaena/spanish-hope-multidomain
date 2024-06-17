# Annotation guidelines

The SpanishHopeMultidomain dataset consist of 2,000 tweets annotated as hs (hope speech) or nhs (non-hope speech). A text was considered hs or nhs if it matched the requirements from the annotation guidelines listed below.

## Index

- [Annotation instructions](https://github.com/danielgbaena/spanish-hope-multidomain#annotation-instructions).
- [Categories](https://github.com/danielgbaena/spanish-hope-multidomain#categories).
- [Topics](https://github.com/danielgbaena/spanish-hope-multidomain#topics).

## Annotation instructions

### General instructions

Each text corresponds to one tweet and every tweet would be tagged only if it makes complete sense by itself and, therefore, if it is not necessary to read any additional tweets from the comments, retweets or review the rest of tweets in the thread, in case our tweet could be part of a Twitter thread of tweets.
Nevertheless, if in order to understand a tweet it is necessary to know some popular news, such as the murder of Samuel Luiz in La Coruña (Spain) or the well-known Spanish “ley trans” draft law presentation, to name a few examples, we will consider our tweet to be comprehensive by itself and then we will proceed to tag it within a category other than None.
Finally, in all cases we will only tag each tweet in a single category.

### Working with the spreadsheet

The `text` column will show the content of each tweet, the `category` column will be filled in with the category that the annotator will associate with the tweet and the `topic` column will be associated with the theme of the text. Thus, all tweets will be tagged using the categories described in the next section.

## Categories

All possible categories are listed below:

1. Hope speech (hs).
2. Not hope speech (nhs).

For each category, a definition is provided reflecting when a tweet should be considered as belonging to it. In addition, several examples are shown to make them more understandable and the choice of tags for all examples is explained.

### Hope speech

A text was annotated as hs (hope speech) if:
1. It explicitly supports the social integration of minorities.
2. It is a positive inspiration for a vulnerable community.
3. It explicitly encourages people who might find themselves in a situation.
4. It unconditionally promotes tolerance.
Below, you will find several examples, accompanied by their explanation of label choice.

#### Case 1

It explicitly supports the social integration of minorities.

##### Example

> He leído a gente diciendo que a las lesbianas le pueden gustar los hombres porque hay mujeres trans?? Si eres una mujer trans eres una MUJER, no eres ni un hombre ni una mujer a medias ni leches. . Y lo mismo, si a un chico trans le gusta una mujer es hetero, porque es UN CHICO.

#### Case 2

It is a positive inspiration for a vulnerable community.

##### Example

> ¿Qué necesidad tiene la gente de decirme que estoy gorda? 🙄. Bro, no me importa tu comentario. Estoy bien y me siento bien con mi cuerpo actualmente.

#### Case 3

It explicitly encourages people who might find themselves in a situation.

##### Example

> Eee? Gorda?? Vos? Vos estás hermosa, ayer, hoy y siempre. No le hagas caso a esos porque se ve que necesitan más aumento o no sé, capaz que los lentes son de la feria

#### Case 4

It unconditionally promotes tolerance.

##### Example

> Sí, todo mi apoyo. Pero sí, debe de haber equilibrios. Yo, como persona🏳️‍🌈 GAY, debo tener los mismos derechos que los heteros. El equilibrio es democrático. No caigamos en clasismos, favoritismos y prejuicios. Son derechos fundamentales. El INE, no puede, ni debe disponer derecho

### Not hope speech

On the other hand, a text will be annotated as nhs (not hope speech) if:
1. It does does not express any positive sentiment.
2. It explicitly seeks violence.
3. It uses insults.

#### Case 1

It does does not express any positive sentiment.

##### Example

> Un inmigrante en paro devuelve 400 euros que se encontró en una caja olvidada entre dos coches de la calle Pérez Galdós de Logroño

#### Case 2

It explicitly seeks violence.

##### Example

> Tío cuando van a dejar de quejarse de la "inclusión forzada"?. Es negra? inclusión forzada. Es homosexual? inclusión forzada. Es mujer? inclusión forzadísima. Hermano callaos ya la puta boca os falta decir que la sirenita fue inclusión forzada de las pelirrojas en su momento

#### Case 3

It uses insults.

##### Example

> No tengo ni puta idea son unos maricones hijos de la gran puta los que fushean

## Topics

All possible topics are listed below:

1. LGBT (lgbt).
2. Obesity (obesity).
3. Racism (racism).

For each topic, a definition is provided reflecting when some text should be considered as being part of it. In addition, several examples are shown to make them more understandable and the choice of tags for all examples is explained.

### LGBT example

> He leído a gente diciendo que a las lesbianas le pueden gustar los hombres porque hay mujeres trans?? Si eres una mujer trans eres una MUJER, no eres ni un hombre ni una mujer a medias ni leches. . Y lo mismo, si a un chico trans le gusta una mujer es hetero, porque es UN CHICO.

### Obesity example

> Eee? Gorda?? Vos? Vos estás hermosa, ayer, hoy y siempre. No le hagas caso a esos porque se ve que necesitan más aumento o no sé, capaz que los lentes son de la feria

### Racism example

> Un inmigrante en paro devuelve 400 euros que se encontró en una caja olvidada entre dos coches de la calle Pérez Galdós de Logroño
