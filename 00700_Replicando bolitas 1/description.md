Hasta ahora no hicimos ningún programa que necesitara información sobre el tablero para hacer lo que se pide en cada caso.
Ahora vamos a hacer algo de eso. 

Nuestro primer experimento va a ser bien sencillo: partiendo de un tablero en el que solamente hay bolitas azules, vamos a querer “replicarlo” en rojo. O sea, en cada celda, poner tantas bolitas rojas como bolitas azules haya. Algunos ejemplos de la transformación que queremos hacer:

||||
|:-:|:-:|:-:|
|![1x1a3](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a3.png)|<i class="fa fa-arrow-right"></i>|![1x1a3r3](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a3r3.png)|
|![1x1a1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a1.png)|<i class="fa fa-arrow-right"></i>|![1x1a1r1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a1r1.png)|
|![1x1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1.png)|<i class="fa fa-arrow-right"></i>|![1x1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1.png)|


La estructura es fácil, hay que poner una cantidad de bolitas rojas. Podríamos simplemente usar un `repeat` para lograrlo, pero vamos a preferir crear un `procedure` que se encargue de poner muchas bolitas, de esa manera nuestro el procedimiento responsable de "replicar" va a quedar más sencillo de leer.

> Tu tarea es escribir un procedimiento `PonerN(cantidad, color)` que reciba un número y un color, y ponga la cantidad de bolitas del color dado.
