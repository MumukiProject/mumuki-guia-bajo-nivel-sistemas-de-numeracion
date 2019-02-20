Así como para el sistema decimal utilizamos potencias de diez, en el sistema binario estaremos utilizando potencias de dos. Para poder convertir números de binario a decimal (¡y entender qué significan todos esos ceros y unos :stuck_out_tongue_closed_eyes:), vamos a interpretar el número como hicimos hasta ahora, pero con base 2.

Por ejemplo, para interpretar el número :one::zero::one:, hacemos:

`:one: * 2^2 + :zero: * 2^1 + :one: * 2^0`

El segundo término, que multiplica por cero, se puede quitar para que la expresión sea más simple. Y como la multiplicación por uno no aporta nada, podemos quitar esos :one:. Entonces nos queda...

`2^2 + 2^0`

Como `2^2 = :four:` y `2^0 = :one:`, el número :one::zero::one: en binario representa :five: en el sistema decimal. ¡Y así se puede convertir cualquier número! :grin:

> Ahora es tu turno: escribí en el editor la interpretación del número :one::zero::one::zero:. Escribí los términos **en orden**, con la potencia más grande primero, y reducí la expresión quitando los términos con cero y las multiplicaciones por uno. O sea, ¡igual que en el ejemplo de este ejercicio! :wink:
