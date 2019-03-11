Una forma de interpretar los números que nos puede servir para todos los sistemas consiste en utilizar la **base**. En el sistema decimal la base es **diez**, porque son diez los símbolos que tenemos (:zero::one::two::three::four::five::six::seven::eight::nine:).

En particular, lo que nos va a resultar útil de la base es multiplicarla sucesivas veces. Mirá:

|Operación |Resultado|
|------|-------|
| 10 | 10 |
| 10 * 10 | 100 |
| 10 * 10 * 10 | 1000 |
| 10 * 10 * 10 * 10 | 10000 |

¿Viste que en el ejercicio anterior el 275 se podía representar mediante `:two::zero::zero: + :seven::zero: + :five:`?

Esa misma representación se puede expresar multiplicando sucesivamente la base, como en la tabla de arriba, para cada dígito. En el último dígito no multiplicamos nada; en el anterior, multiplicamos por la base una vez; en el anterior a ese, multiplicamos por la base dos veces...:

`:two: * 10 * 10 + :seven: * 10 + :five: = :two::seven::five:`

Pero para que sea más simple, sabiendo que `10 * 10` es igual a 100:

`:two: * 100 + :seven: * 10 + :five: = :two::seven::five:`

> ¡Eso fue un montón! :cold_sweat: Teniendo en cuenta el ejemplo del número 275, identificá cuál de las siguientes expresiones es equivalente al número 936.
