Al igual que con el sistema binario, no es simple convertir a hexadecimal desde el sistema decimal :confused:. Implicaría dividir muchas veces por 16 para quedarse con los restos (¿alguien recuerda cómo dividir por dos cifras? :stuck_out_tongue:) o convertir a binario como paso intermedio. Mejor, usemos la tecnología una vez más. :bulb:

Esta vez, Ruby nos va a ayudar a convertir a hexadecimal. Igual que antes, pero con una nueva base: ahora, luego del número que queremos convertir, vamos a estar escribiendo `.to_s(16)`.

```ruby
ム 127.to_s(16)
=> "7f"
``` 

Ruby nos devuelve las letras en minúsculas, pero es lo mismo: los símbolos `abcdef` son equivalentes a `ABCDEF`.

> ¡A probar! Convertí a hexadecimal algún número grande.