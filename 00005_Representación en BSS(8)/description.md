## Sistemas restringidos

Vamos a poner en práctica lo aprendido, suponendo un sistema BSS(8). Entonces todas las cadenas del sistema **deben tener 8 bits**. Vemos un ejemplo donce se debe representar el número 26: ya vimos que puede representarse con 5 bits mediante la cadena `11010`. 

¿Cómo hacemos para que dicha representación sea válida en BSS(8), es decir que tenga 8 bits?

Correcto! Completando con 0s a la izquierda: `00011010`

## Siempre podemos comprobar

¿Como comprobamos que esto tiene sentido? Interpretando la cadena! 
Entonces la interpretación de `00011010` es: **2^4+2^3+2^1**

## A trabajar

>¿Cómo es la cadena que representa al valor 4 en un sistema BSS(8)?