## Símbolos del sistema

Dos amigos a quienes les gustaba la matemática se juntaron un día.

```
- Tengo ganas de inventar un sistema en base 16
- ¿para qué?
- Ya lo vas a ver, ahora tengo que elegir los símbolos
- Eso es fácil, hagamos como con el Octal: 0, 1 ...
- Ajá, pero ahí tenemos solo 10 símbolos distintos!
- Estem... bueno, seguimos por las letras!
- Buena idea!
```

Así, el **sistema hexadecimal** tiene el siguiente conjunto de 16 símbolos: {0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F}. Además de esto, los amigos tuvieron que definir cómo interpretar y cómo representar.

```
- ¿Cuánto vale la cadena 10?
- ¡Uy! tendríamos que definir cómo interpretar
- Ya se, interpretemos como en binario, octal, base 3 pero con los pesos que corresponde
- ¡Bien ahí! serían potencias de base 16... no?
- Claro, esa cadena vale 1x16¹ + 0*16⁰
- Genial, pero tengo una mala noticia... como interpretamos la cadena A0?
- Chan!!
```

No les costó mucho darse cuenta que tenían que decidir **que valor tenía cada letra** y entonces podían seguir con la secuencia del sistema decimal:

|Dígito | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | A | B | C | D | E | F |
|-------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Valor** | 0 | 1|2|3|4|5|6|7|8|9|10|11|12|13|14|15|


Veamos un ejemplo: supongamos un sistema hexadecimal de 2 caracteres. Entonces, si la cadena es `01` entonces la interpretación i es `16^0`

Veamos otro ejemplo: supongamos un sistema hexadecimal de 3 caracteres. Entonces, si la cadena es `0A` entonces la interpretación i es `10*16^0`

## A trabajar


>¿Cuál es la interpretación de la cadena _'A0'_?