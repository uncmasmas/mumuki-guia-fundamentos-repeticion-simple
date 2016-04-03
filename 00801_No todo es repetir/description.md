Los ejemplos que hiciste en los ejercicios anteriores se solucionaban simplemente repitiendo cosas. Pero no todo es repetir, también podemos poner comandos tanto **antes** como **después**, al igual que veníamos haciendo hasta ahora.

Por ejemplo, este es un programa que se mueve al Sur y **luego** pone 4 bolitas rojas:

```puppet
program {
  Mover(Sur)
  
  repeat(4) {
    Poner(Rojo)
  }
}
```

Fijate que el `Mover(Sur)` lo pusimos **antes** del `repeat`, y por lo tanto se ejecuta una vez sola.

> Sabiendo esto, escribí `Poner10AlNoreste()`, que ponga 10 bolitas negras en la primera celda al Noreste del cabezal.