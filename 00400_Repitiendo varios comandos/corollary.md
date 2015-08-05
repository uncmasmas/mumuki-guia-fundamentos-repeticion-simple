¿Viste qué importante es definir bien qué comandos hay que repetir y cuáles no?

Es muy común, al principio, olvidarse de colocar las llaves o incluso pensar que no son importantes. Pero tené mucho cuidado: poner las llaves en el lugar erróneo pueden cambiar por completo lo que hace tu programa, mirá qué distinto es el resultado si corremos sólo un poquito la llave final:

```puppet
procedure DibujarLineaNegra6() {
  repeat(5) {
    Poner(Negro)
    Mover(Este)
    Poner(Negro)
  }

  MoverOeste5()
}
```

![Linea negra mal hecha](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/6x2h00-linea-negra-6-mal.png)