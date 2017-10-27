Hasta el momento los ejemplos que vimos sólo repetían un comando, pero como mencionamos al comenzar es posible repetir cualquier **secuencia de comandos** - en definitiva lo que se repite es un **bloque** y, como ya sabíamos, en un bloque puede haber tantos comandos como se nos ocurra.

Miremos el código  que podríamos haber hecho sin usar `repeat`, con algunos espacios en blanco para ayudarnos a reconocer la secuencia que se repite. Este programa dibuja una línea negra de 6 bolitas.

```gobstones
program {
  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)  

  Poner(Negro)
  Mover(Este)  
}
```

¿Notás qué es lo que se repite y cuántas veces? Bueno, eso es lo que tenés que poner en el `repeat`.

> Escribí una versión superadora del programa anterior, esta vez usando `repeat`.