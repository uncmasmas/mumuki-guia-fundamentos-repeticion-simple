Como te adelantamos en el ejercicio anterior, en Gobstones existe una forma de decir _"quiero que **estos comandos** se **repitan esta cantidad de veces**"_.

Entonces, cuando es necesario repetir un comando (como `Mover`, `Poner`, `Sacar`) un cierto número de veces, en lugar de copiar y pegar como veníamos haciendo hasta ahora, podemos utilizar la sentencia `repeat`.

Sabiendo esto, así es como quedaría el desafío que resolvimos antes usando `repeat`:

```gobstones
program{
  repeat(10) {
    Mover(Oeste)
  }
}
```

> Pero no tenés por qué creernos: ¡escribí este código en el editor y fijate si funciona!