Muchas veces cuando usamos un `repeat` nos encontramos con que el último caso es levemente distinto a los anteriores, situación que solemos llamar **caso borde**. Pero mejor, veamos un ejemplo.

El siguiente programa que te presentamos dibuja una línea negra hacia el Este dejando el cabezal **fuera de la línea**, una celda hacia el Este.

```gobstones
program {
  repeat(4) {
    Poner(Negro)
    Mover(Este)
  }
}
```

Si ahora queremos hacer que deje el cabezal en la última celda de la línea, tenemos dos opciones:

* **Mover el cabezal al Oeste luego de dibujar la línea.** Un truco medio feo, porque para funcionar necesita que haya al menos 5 espacios al Este de la posición inicial, cuando nuestra línea sólo ocupará 4.
* **Tratar el último caso de manera especial.** Esta opción es más interesante y más fiel a lo que queremos hacer: la última vez no queremos que el cabezal se mueva, simplemente nos basta con poner la bolita negra.

> Teniendo en cuenta esto último, escribí una nueva versión del programa que deje el cabezal en la última celda de la línea.