Ahora sí, vamos a hacer algo de lo que te prometimos.

Partiendo de un tablero en el que solamente hay bolitas azules, vamos a querer “replicarlo” en rojo. O sea, en cada celda, poner tantas bolitas rojas como bolitas azules haya. Algunos ejemplos:

||||
|:-:|:-:|:-:|
|![1x1a3](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a3.png)|<i class="fa fa-arrow-right"></i>|![1x1a3r3](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a3r3.png)|
|![1x1a1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a1.png)|<i class="fa fa-arrow-right"></i>|![1x1a1r1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1a1r1.png)|
|![1x1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1.png)|<i class="fa fa-arrow-right"></i>|![1x1](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-3-repeticion-simple/master/1x1.png)|

La estructura es fácil, hay que poner una cantidad de bolitas rojas, y para eso vamos a usar el `PonerN` que creamos recién. El color que tenemos que poner es `Rojo`, pero ¿cómo hacemos para saber cuál es la cantidad?

El truco es preguntarle a Gobstones cuántas bolitas azules hay en la celda actual, mediante una expresión que viene definida: `nroBolitas(color)`. En nuestro caso, podemos obtener el número que queremos escribiendo `nroBolitas(Azul)`.

> Usando `PonerN(cantidad, color)` y `nroBolitas(color)`, escribí un procedimiento `ReplicarAzulesConRojas()` que haga lo que describimos recién.
