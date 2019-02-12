## Interpretando en el sistema binario :one:

La **interpretación** es el proceso por el cual se obtiene el valor de una cadena dada. 

![Interpretacion](https://raw.githubusercontent.com/Orga-UNQ/mumuki-guia-bajo-nivel-sistemas-de-numeracion/master/images/interpretar.png "Interpretacion")


La interpretación decimal puede aplicarse casi directamente en el sistema binario, considerando que la base es 2, ¿Cual es el valor de la cadena `1`? 

Correcto! su valor es: **1\*2^0 = 2^0 = 1**

Casualmente, el dígito `1` en binario representa el **valor 1**

Veamos mas ejemplos:

* La cadena `11` se interpreta: **1\*2^1 + 1\*2^0 = 2+1 = 3**
* La cadena `101` se interpreta: **1\*2^2 + 0\*2^1 + 1\*2^0 = 4+1 = 5**

### Atención! 
De ahora en más, las interpretaciones deben ser **ordenadas** y **económicas**. Es decir que mumuki espera que describas cada potencia en orden descendente, y que describas sólo los términos **cuyo bit vale 1**. Por ejemplo, **NO** está bien escribir esto:

> 1\*2^1 + 1\*2^2

porque está en orden incorrecto.

Además, si debe ser económica, la interpretación de la cadena `10` **no debe ser** ninguna de las siguientes:

* 1\*2^1
* 1\*2^1 + 0\*2^0

Entonces, la interpretación correcta para mumuki de la cadena `10` es **2^1** ¿Mas económico, no?

### Para calentar motores


Para familiarizarte con la manera en que esperamos que escribas tus respuestas, copiá lo que ponemos abajo y pegalo en el editor. Luego dale clic al botón enviar.

```
2^2 + 2^1 + 2^0
```
