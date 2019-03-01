Pero no sólo convertir binarios a decimales es útil: también nos gustaría poder transformar cualquier número decimal a binario. Por ejemplo, ¿cuál es la representación binaria del número 37?

Lamentablemente, convertir de decimal a binario no es tan simple :disappointed:: hay que dividir muchas veces e ir llevando cuenta de los restos de cada división. ¡Pero la tecnología está de nuestro lado! :computer:

El lenguaje [Ruby](https://www.ruby-lang.org/es/), por ejemplo, nos permite convertir entre sistemas de una forma muy simple, escribiendo `.to_s(2)` luego de un número. Si queremos saber cómo escribir 37 en binario...

```ruby
ム 37.to_s(2)
=> "10011"
``` 

Entre paréntesis escribimos la base del sistema al que queremos convertir, que en binario es `2`. Se puede escribir la base de cualquier otro sistema, así que nos va a servir más adelante. :smirk:

> ¡Ahora te toca a vos! Probá convertir a binario tus números favoritos. Y pensá: ¿qué pasa si escribís algún número `.to_s(10)`?