Como te adelantamos en el ejercicio anterior, en Gobstones existe una forma de decir "quiero que **estos comandos** se **repitan esta cantidad de veces**".

Entonces, cuando es necesario repetir un comando (como `Mover`, `Poner`, `DibujarLineaNegra`, etc) un cierto número de veces, en lugar de copiar el mismo comando esa cantidad de veces como veníamos haciendo hasta ahora, podemos utilizar la sentencia `repeat`. 

Veamos entonces cómo quedaría `MoverOeste10` usando `repeat`:

```puppet
procedure MoverOeste10() {
  repeat(10) {
    Mover(Oeste)
  }
}
```

> Pero no tenés por qué creernos: ¡copiá este código en el editor y fijate si funciona!