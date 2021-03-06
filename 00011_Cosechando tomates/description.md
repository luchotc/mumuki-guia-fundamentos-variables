Finalmente nuestra humilde huerta dio sus frutos y ya estamos en condiciones de cosechar los tomates. :grin: :tomato:

¿Cómo haremos esto? Muy sencillo, **sacaremos** los tomates de nuestras 3 plantas-celdas y los dejaremos en el origen. Veamos qué aspecto tiene nuestra huerta:

**Antes de cosechar**

![](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-guia-fundamentos-variables/master/images/tomates-por-cosechar.png)

**Después de cosechar**

![](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-guia-fundamentos-variables/master/images/tomates-cosechados.png)

Para que nos sirva para la próxima cosecha también, vamos a escribir un procedimiento lo suficientemente _inteligente_ como para que funcione con cualquier cantidad de tomates (la huerta por el momento no va a agrandarse, así que no hay que preocuparse por eso). Afortunadamente tu _caja de herramientas_ no viene vacía, te dejamos algunas cosas en la Biblioteca:

* la función `cantidadTomates()` que indica cuántos tomates hay en la planta (celda) actual;
* el procedimiento `CosecharPlanta()` que cosecha todos los tomates que hay en una planta;
* el procedimiento `DejarTomates(cantidad)` que deja la cantidad de tomates indicada por parámetro en la celda actual.
 
Además, te ayudamos un poco con la estructura de tu solución para que sólo tengas que concentrarte en lo que queremos que aprendas acá: <del>a cosechar tomates</del> **a usar variables**. :wink:

> Completá el procedimiento `CosecharHuerta()` con la ayuda que te brindamos.