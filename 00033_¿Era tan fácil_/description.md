No sólo para convertir desde el sistema decimal podemos recibir ayuda. Si bien es útil entender cómo pasar números a decimal desde distintos sistemas (¡y así saber cómo funcionan!), en la práctica hay lenguajes que lo pueden hacer por nosotros, y Ruby es el indicado una vez más. :grin:

Para escribir un número binario hay que agregarle el prefijo `0b`, y para escribir un número hexadecimal, el prefijo `0x`. Al enviar estos números en la consola, los convierte automáticamente a sus equivalentes en decimal.

```ruby
ム 0b11101101
=> 237

ム 0x2FB
=> 763
```

¡Y no termina ahí! Hasta se pueden realizar operaciones sobre números de distintos sistemas, como sumas, restas o multiplicaciones:

```ruby
ム (0b11101101 + 0x2FB) * 2
=> 2000
```

> ¡A probar! Ahora es al revés: escribí números en binario y hexadecimal y fijate a qué equivalen en el sistema decimal.