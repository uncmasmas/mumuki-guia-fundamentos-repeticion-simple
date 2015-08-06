Ahora que ya tenemos un `MoverOeste` genérico, podemos construir el `DibujarLineaNegra` que queríamos. Como el procedimiento tiene que servir para cualquier `longitud`, esta vez esperaremos recibir ese número por parámetro.

Para tu comodidad, te dejamos nuevamente el código de `DibujarLineaNegra3`, pero usando el `MoverOeste` que definiste en el ejercicio anterior:

```puppet
procedure DibujarLineaNegra3() {
  repeat(2) {
    Poner(Negro)
    Mover(Este)
  }

  Poner(Negro)
  MoverOeste(2)
}
```

> Escribí el procedimiento `DibujarLineaNegra(longitud)` que dibuje una línea negra hacia el Este, de la longitud recibida. El cabezal debe terminar donde empezó.