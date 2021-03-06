# twet

Introducción:

Cada archivo consta de varios tweets, los cuales estan relacionados con las distintas
empresas que cotizan en la Bolsa de Valores de México. Todas las etiquetas disponibles se encuentran en el siguiente enlace:

http://www.bmv.com.mx/es/emisoras/informacion-de-emisoras

El fin del ejercicio es clasificar cada tweet dentro de tres posibles categorías:
* +1: Si el tweet expresa una visión positiva de la empresa de la que se habla
* 0: Si el tweet es vago o inconcluso, no se puede concluir nada con lo que se expresa
* -1: Si el tweet expresa una visión negativa de la empresa de la que se habla

En pocas palabras, se tienen tres (3) clases posibles: una que representa un sentimiento
positivo de la etiqueta que habla, una clase que maneja el caso en donde el tweet no 
aporta nada de información y una clase que maneja el caso donde el sentimiento es negativo
en relación a la etiqueta de la empresa en cuestión.

Por otro lado, las etiqueta pueden también interpretarse como un indicador de como el
mensaje del tweet afecta la visión del que lo lee y la empresa en cuestión, que puede
ser positivo o negativo.

Por ejemplo:

#Amediasesion el $IPC retrocede 0.45%. Avanzan $LALA $AC $ELEKTR Bajan $OHLMEX $VOLAR $WALMEX ¿RSI sobre compra o s? https://t.co/CtY94rqGUc

En el tweet anterior, existe la confusión de como interpretar el tweet, por lo que es necesario leer en relación a que etiqueta se hace mención para poder clasficarlo. Si el tweet se relaciona con la etiqueta $LALA, entonces es positivo (por la pabra 'avanzan') pero si se habla de $OHLMEX es negativo (por la palabra 'bajan').

La tarea consta de registrar manualmente una lista de 1422 tweets, con el fin de poder
realizar un diccionario de términos que faciliten su clasifiación automática.

Instrucciones generales:

* Para cada tweet, leer y designar una clase apropiada, denotadas por 1, 0 o -1. El valor
  que representa cada clase se puede encontrar en los párrafos anteriores.

* No es necesario guardar el archivo, el enlace en Google Docs se guarda de manera automática.

* Repetir para cada archivo.

* En caso de no tener los elementos suficientes para poder dicernir entre positivo o negativo, marcarlo como neutro.

De antemano, muchas gracias por participar en éste ejercicio. Cualquier aclaración, mandar
un correo a: lzun.morales@gmail.com
