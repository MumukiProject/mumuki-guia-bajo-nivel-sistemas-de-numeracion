### Idea

Existe un mecanismo para traducir cadenas binarias a hexadecimales y viceversa, sin la necesidad de interpretarlas para encontrar el valor representado. Para hacerlo, por única vez confeccionaremos una tabla donde se asocia **cada dígito hexadecimal con una cadena de 4 bits**.

| Dígito | Cadena 4 bits |
|:------:|:-------------:|
| 0 | 0000 |
| 1 | 0001 |
| 2 | 0010 |
| 3 | 0011 |
| 4 | 0100 |
| 5 | 0101 |
| 6 | 0110 |
| 7 | 0111 |
| 8 | 1000 |
| 9 | 1001 |
| A | 1010 |
| B | 1011 |
| C | 1100 |
| D | 1101 |
| E | 1110 |
| F | 1111 |

#### Aplicando la tabla
Supongamos que tenemos una cadena de bits:```01010110``` y necesitamos **su equivalente** en hexadecimal, entonces:
1. Agrupamos los bits en paquetes de 4, comenzando por la parte menos significativa (bits de menos peso): ```01010110```
2. Asociamos **cada paquete** con un dígito hexadecimal, **usando la tabla** confeccionada arriba: 

| 0101 | 0110 |
|:----:|:----:|
|   5  |   6  |

#### Comprobando el trabajo

¿Se te ocurre alguna forma de comprobar el trabajo?

> I(01010110) = 2⁶+2⁴+2²+2¹ = (2²*2⁴ + 1*2⁴) + (2²+2¹) = (2² + 1) * 2⁴ + (2²+2¹) * 1 = (2² + 1) * 16¹ + (2²+2¹) * 16⁰ = 5 * 16¹ + 6 * 16⁰

Esta última expresión (**5 * 16¹ + 6 * 16⁰)**) se puede representar en hexadecimal literalmente:

> R( 5 * 16¹ + 6 * 16⁰) = 56

### Atención

Si la cadena en binario tiene una cantidad de bits que no es múltiplo de 4, entonces se deben **completar con 0s a la izquierda**. Por ejemplo:

1. Se tiene la cadena ```110101101```
2. Se agrupan los bits comenzando desde la derecha: ```1 1010 1101```
3. Se completa el grupo de la izquierda con 0s: ```0001 1010 1101```
4. Se traduce aplicando la tabla:

| 0001 | 1010 | 1101 |
|:----:|:----:|:----:|
|   1  |   A  | D    |

### A trabajar

¿Cuál es la cadena hexadecimal equivalente a ```111000```?
