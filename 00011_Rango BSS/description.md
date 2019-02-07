# Hablemos de rango
Es momento de preguntarnos: ¿qué números nos permite manejar un sistema? Pensemos un rato en BSS(2): ¿Cuantas cadenas pueden formarse con 2 bits? 

> 00 - 01 - 10 - 11 

Vemos que con 2 bits pueden hacerse 4 combinaciones, es decir 2^2.

Si esas cadenas están ordenadas alfabéticamente y asociadas cada una a un valor, tendremos:

|Cadena | Interpretacion | Valor|
| ------------- |:-------------:| -----:|
|00 |  |0|
|01 | 2^0 |1|
|10 | 2^1  |2|
|11 | 2^1 + 2^0 |3|

Es decir, que el rango de valores representables en BSS(3) son los enteros entre 0 y 3 (inclusive)

# A poner en práctica

Supongamos un sistema BSS(4). Entonces la cantidad de cadenas que pueden construirse en ese sistema son 16, pues la cantidad de combinaciones es 2^4=16

> ¿Cuál es máximo valor representable?

