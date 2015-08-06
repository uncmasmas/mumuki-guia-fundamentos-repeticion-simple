Hasta ahora no hicimos ningún programa que necesitara información sobre el tablero para hacer lo que se pide en cada caso.
Ahora vamos a hacer algo de eso. 

Nuestro primer experimento va a ser bien sencillo: partiendo de un tablero en el que solamente hay bolitas azules, vamos a querer “replicarlo” en rojo. O sea, en cada celda, poner tantas bolitas rojas como bolitas azules haya. Algunos ejemplos de la transformación que queremos hacer:

La estructura es fácil, hay que poner una cantidad de bolitas rojas. Podríamos simplemente usar un `repeat` para lograrlo, pero vamos a preferir crear un `procedure` que se encargue de poner muchas bolitas, de esa manera nuestro el procedimiento responsable de "replicar" va a quedar más sencillo de leer.

> Tu tarea es escribir un procedimiento `PonerN(cantidad, color)` que reciba un número y un color, y ponga la cantidad de bolitas del color dado.
