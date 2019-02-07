El proceso de representacion es el de construir una cadena a partir de un valor.

![representacion](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-sistemas-de-numeracion/blob/master/images/representar.png?raw=true "Representacion")

Para representar valores mediante cadenas binarias, se deben realizar divisiones sucesivas por la base 2 hasta obtener un cociente igual a cero, **tomando cada resto como bits de la cadena**. 

Vamos a un ejemplo, si se necesita representar el número 26:


![Representar 26 en binario](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-sistemas-de-numeracion/blob/master/images/repbinaria26.png?raw=true)

1. Se divide 26%2 dando un cociente de 13 y un resto 0
2. Se divide 13%2 dando un cociente de 6 y un resto 1
3. Se divide 6%2 dando un cociente de 3 y un resto 0
2. Se divide 3%2 dando un cociente de 1 y un resto 1
3. Se divide 1%2 dando un cociente de 0 y un resto 1
4. Se construye la cadena **tomando solo los restos, empezando por el último**: 11010

### A practicar

>¿Cuál es la cadena que representa el 6 en BSS?

