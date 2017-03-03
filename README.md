# Ejercicio 5.5.6. Sumador JavaScript muy simple con sumas aleatorias
Ejercicio de asignaturas de aplicaciones HTML5. Tema JavaScript. Sumador JavaScript muy simple con sumas aleatorias

## Enunciado
Realiza un sumador como el descrito en el ejercicio "Sumador JavaScript muy simple" (ejercicio 5.5.5), pero de forma que se incluya un texto en el que, si se pica con el ratón, se genere una nueva suma con dos sumandos aleatorios.

> #### Ejercicio 5.5.5. Sumador JavaScript muy simple
> Utilizando la función creada en el ejercicio "Función que cambia un elemento HTML" (ejercicio  5.5.4), escribir una  función que realice una suma.

> Para  ello, partimos de una página HTML que tenga el siguiente código:

> ```html
> <p>
>     Adder...<span id='op'>5+3</span>
>     <span id="res"></span> <a href="">Add!</a>
> </p>
> ```

> El objetivo es que cuando se pulse sobre "Add!" aparezca a continuación de "5+3" la cadena "=8" (siendo 8 la suma de los dos operandos).  Para ello la función a escribir aceptará como parámetros dos cadena de texto, que serán el identificador del elemento HTML donde está la operación, y el del elemento donde se escribirá el resultado.

> Se considera que la operación estará siempre en formato "primer número, +, segundo número".  La función tendrá que buscar la operación, identificar los operandos  en  ella  (por  ejemplo,  usando  "split"),  realizar  la  suma  y,  utilizando  la función  de  cambio  de  un  elemento  HTML,  escribir  el  contenido  en  el  elemento HTML del resultado.

## Resultado
[https://acamara7es.github.io/X-Nav-JS-Sumador/index.html](https://acamara7es.github.io/X-Nav-JS-Sumador/index.html)

## Comentarios y mejoras
Después de realizar el ejercicio propuesto en el enunciado, en clase el profesor nos propuso una ampliación del mismo, que consistía en poder generar una lista de sumas a través de un enlace, que generaba una suma como la del ejercicio original cada vez que se pulsaba, pero que además generaba también un enlace en cada suma que pulsándolo resolvía la operación que le correspondía.

El resultado de esta ampliación es [este](https://acamara7es.github.io/X-Nav-JS-Sumador/index_ext.html)
