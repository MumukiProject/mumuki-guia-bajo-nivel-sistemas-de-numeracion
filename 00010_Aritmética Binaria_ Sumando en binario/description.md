Los sistemas de numeración deben proveer, además de los mecanismos de interpretación y representación, algoritmos para operar con esas cadenas: suma, resta, multiplicación, division...

Tal como hemos aprendido a sumar "en papel" para el sistema decimal, pensaremos la suma como un algortimo por columnas: se suman las columnas empezando por la de menor peso (a la derecha) y acarreando a la siguiente columna si corresponde. Por ejemplo, si en decimal debemos sumar dos digitos cuya suma no alcanza el límite de la base (que es 10):

```
 3
+4
---
 7
```

Similarmente, en binario debemos distinguir algunos casos, que tienen que ver con las posibles combinaciones entre ambos operandos, que afortunadamente no son muchos, pues cada operando puede ser solamente `0` ó bien `1`.

Entonces los casos posibles son sólo 4:

![Suma: casos](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-sistemas-de-numeracion/blob/master/images/casos-suma.png?raw=true)

# Poniendo en práctica

¿Cuál es *la cadena* que resulta de sumar las cadenas `101` y `001`?
