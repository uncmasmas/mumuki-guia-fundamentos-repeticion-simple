Hasta ahora los ejemplos que vimos sólo repetían un comando, pero como mencionamos al comenzar es posible repetir cualquier **secuencia de comandos**.

Miremos el código de `DibujarLineaNegra6` que podríamos haber hecho sin usar `repeat`, con algunos espacios en blanco para ayudarnos a reconocer la secuencia que se repite:

```puppet
procedure DibujarLineaNegra6() {
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

> Escribí una versión superadora de `DibujarLineaNegra6`, usando `repeat`.