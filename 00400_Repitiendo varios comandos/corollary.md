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

Bastante parecido a lo que acabás de hacer, ¿no? ¡Intentemos mejorarlo!