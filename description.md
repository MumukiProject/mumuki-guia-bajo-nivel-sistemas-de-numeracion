A lo largo de la historia, los seres humanos han ido utilizando distintas técnicas para representar números: los egipcios usaban jeroglíficos, los romanos usaban letras, y nosotros en la actualidad utilizamos el **sistema de numeración decimal**. Los diez dígitos que conocemos, :zero::one::two::three::four::five::six::seven::eight::nine:, sirven para representar todos los números que existen - y así podemos leerlos, transmitirlos, almacenarlos y comunicarlos. 

¡Pero el decimal no es el único sistema de numeración que existe! En el mundo de la computación :computer: también se utilizan otros sistemas, como el **binario**, el **octal** y el **hexadecimal**. ¡Aprendamos sobre ellos! :grin:

------------

El sistema de numeración provee un mecanismo para representar números y así poder leerlos, transmitirlos, almacenarlos y comunicarlos.

Cada sistema propone una forma particular de escribir números, con sus propiedades y limitaciones. Por ejemplo, el sistema romano no permite escribir números negativos o fracciones.

En los sistemas de **numeración ponderados o posicionales** el valor de un dígito depende tanto del símbolo utilizado, como de la posición que ése símbolo ocupa en la cadena.


### ¿Qué significan estas cadenas?

Por ejemplo, la cadena 10 (en el sistema decimal) representa la cantidad de _diez_  y la cadena 100 representa la cantidad _cien_. Además, ocurre que las cadenas 001, 01 y 1 representan todas el número _uno_.

### Interpretando en el sistema decimal

La cadena **10**, como dijimos, representa el valor _diez_, o _diez unidades_, donde la unidad es el elemento mas pequeño. Le estamos dando valor también al decir que representa *una decena*, y si puedo expresar las decenas, entonces puedo escribirlo así:
```
1*10
```

La cadena **12**, representa el valor _doce_, es decir que representa *1* decena y *2* unidades. Esto quiere decir que lo puedo escribir como:

```
1*10 + 2*1
```

Mas aún, eso puede _normalizarse_ usando potencias de 10, así:

```
1*10^1 + 2*10^0
```

(con el caracter **^** se indica una potencia!)