Los símbolos del cero al nueve valen lo que dicen: si vemos escrito un 9, significa que representa el número 9.

A partir de ahí, los valores son los siguientes:

| Símbolo | Valor |
|---|---|
|A|10|
|B|11|
|C|12|
|D|13|
|E|14|
|F|15|

Sabiendo eso, podemos interpretar igual que en decimal y binario, pero teniendo en cuenta que ahora la base es 16.

Para interpretar el número `BF8`, seguimos los mismos pasos que antes: el último dígito mantiene su valor, el anterior se multiplica por 16, y el anterior se multiplica por 16 y por 16. Y como siempre, si hay más dígitos, se agregan más multiplicaciones por la base. :relaxed:

`B * 16 * 16 + F * 16 + 8`

Como `16 * 16` es `256`, reemplazamos:

`B * 256 + F * 16 + 8`

Y reemplazando por los valores de `B` y `F`, que son `11` y `15` según la tabla de arriba:

`11 * 256 + 15 * 16 + 8 = 3064`, por lo que `BF8` en hexadecimal representa el número `3064` en decimal (¡y viceversa!).

> ¡A agarrar la calculadora! Interpretá como en el ejemplo y completá la siguiente oración: