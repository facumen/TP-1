# TP-1
Trabajo Práctico 1: El Juego de la Ruleta 
El Juego de la Ruleta

La ruleta es un juego de azar, típico de los casinos y muy popularizada en versiones on line. Consiste en realizar apuestas con respecto al número que saldrá en una ruleta con 37 números (del 0 al 36), luego girarla y determinar las ganancias (si hubiera) de cada apostador.

Se puede apostar a un número específicamente (lo que se denomina pleno), o a alguna de sus características (par/impar, rojo/negro, entre otras). Cada una representa un premio diferente para el apostador (recupera la ficha apostada y se agregan las que gane).



En la versión que se pide implementar aquí, sólo habrá un jugador contra la ruleta. Las apuestas posibles, y sus pagos, se describen a continuación:

Apuesta

Cuánto gana?

Par/Impar - Rojo/Negro - Pasa/Falta

Recupera 1 ficha y gana 1

Docenas / Columnas

Recupera 1 ficha y gana 2

Pleno (número)

Recupera 1 ficha y gana 35

 

Al comenzar el juego, el jugador contará con 6 fichas. Antes del lanzamiento, se le pedirá que elija entre rojo/negro, entre par/impar, pasa/falta, una de las docenas, una de las columnas y un número fijo a apostar. A cada una de esas seis posibilidades le apostará 1 ficha.

Luego se realizará el lanzamiento de la ruleta, simulado por medio de la generación de un número aleatorio. El programa debe identificar las características del número, teniendo en cuenta que:

El 0 no tiene color, no se considera par ni impar, no se incluye en las docenas ni en pasa/falta.
Colores:el tapete presenta el siguiente patrón:
○     1 al 10 impares rojos y pares negros

○     11 al 18 impares negros y pares rojos

○     19 al 28 impares rojos y pares negros

○     29 al 36 impares negros y pares rojos

Pasa/Falta: si el número está comprendido entre los números del 1 al 18 es Falta, si va del 19 al 36 es Pasa.
Los números se dividen en 3 docenas, cada una de ellas abarca 12 números.
Los números se distribuyen sobre el tapete en 3 columnas (piensen un poco para determinar en qué forma se puede determinar a qué columna pertenece un  número...)
Los pares/impares no necesitan explicación :-)
A partir del número obtenido, determinar y mostrar:

1.)    Cuántas fichas recuperó y cuántas ganó el jugador (si es que recuperó/ganó alguna)

2.)    Cuánto dinero en efectivo recibirá al momento de canjear sus fichas (recuperadas+ganadas), si sabemos que cada ficha equivale a $100 y que el Casino retiene 5% del monto en concepto de comisión.


