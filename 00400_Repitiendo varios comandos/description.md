# REVISAR, ESTÁ COPY-PASTEADO

Como te decíamos en el corolario del ejercicio anterior, al usar un `repeat` se puede repetir cualquier **secuencia de comandos**. Hasta ahora los ejemplos que vimos sólo repetían un comando (`Mover(Oeste)`), pero en este ejercicio vas a tener que repetir más de uno.

Miremos el código de `DibujarLineaNegra6` que podríamos haber hecho hasta ahora, con algunos espacios en blanco para ayudarnos a reconocer la secuencia que se repite:

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
}
```

¿Notás qué secuencia de comandos se repite y cuántas veces? Bueno, eso es lo que tenés que poner en el `repeat`.

> Escribí una versión superadora de `DibujarLineaNegra6`, usando `repeat`.