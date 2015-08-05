Mirá como quedaría `DibujarLineaNegra3` usando `repeat`:

```puppet
procedure DibujarLineaNegra3() {
  repeat(3) {
    Poner(Negro)
    Mover(Este)
  }

  Poner(Negro)
  MoverOeste2()
}
```

Bastante parecido a lo que acabás de hacer, ¿no? En particular, hay 2 cosas que deberíamos **parametrizar** para poder crear un procedimiento que sirva para dibujar lineas de cualquier tamaño:

* cuántas veces se repite la secuencia `Poner(Negro)` - `Mover(Este)`
* cuántas veces se mueve al `Oeste` para dejar el cabezal en la posición inicial

> Vamos a encargarnos ahora de lo segundo: creá un procedimiento `MoverOeste(cantidad)` que haga que el cabezal se desplace la cantidad especificada de veces hacia el `Oeste`.
