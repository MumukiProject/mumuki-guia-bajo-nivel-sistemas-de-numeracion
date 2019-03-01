Así como para el sistema decimal multiplicábamos la base diez, en el sistema binario estaremos multiplicando al número dos. Para poder convertir números de binario a decimal (¡y entender qué significan todos esos ceros y unos :stuck_out_tongue_closed_eyes:), vamos a interpretar el número como hicimos hasta ahora, pero con base 2.

Por ejemplo, para interpretar el número :one::one::zero::one:, hacemos igual que con el sistema binario, pero reemplazando el diez por el dos.

Entonces el último dígito no se multiplica; el anteúltimo, se multiplica por dos; el anterior, se multiplica por dos y por dos; y el anterior, se multiplica por dos y por dos y por dos:

`:one: * 2 * 2 * 2 + :one: * 2 * 2 + :zero: * 2 + :one:`

Hay dos cosas que podemos hacer. Primero, sabemos que `2 * 2` es 4 y que `2 * 2 * 2` es 8. Entonces nos queda...

`:one: * 8 + :one: * 4 + :zero: * 2 + :one:`

Y segundo, la multiplicación por :zero: no aporta nada al resultado, por lo que la podemos quitar. Ahora sólo queda...

`:one: * 8 + :one: * 4 + :one:`

¡Y ahora sólo nos falta sumar! `:eight: + :four: + :one: = :one::three:`, lo que significa que el número :one::one::zero::one: en binario representa :one:three: en el sistema decimal. ¡Y así se puede convertir cualquier número! :grin:

> Ahora es tu turno: completá la siguiente oración. Te recomendamos pensar la interpretación de la misma forma que en el ejemplo de este ejercicio :wink: 