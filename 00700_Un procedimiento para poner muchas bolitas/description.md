Hasta ahora no hicimos ningún programa que necesitara información sobre el tablero para hacer lo que se pide en cada caso.
Ahora vamos a hacer algo de eso. 

Para eso vamos a crear un procedimiento que nos ayude a poner muchas bolitas. Sí, podríamos simplemente usar un `repeat` para lograrlo, pero vamos a preferir crear un `procedure` que se encargue de ello, de esa manera ganamos en:

* **declaratividad:** cuando tengamos que usarlo para resolver problemas más complejos nos vamos a concentrar en el "qué" (poner muchas bolitas) y no en el "cómo" (un `repeat` y un `Poner`)
* **reutilización de código:** como poner muchas bolitas es una tarea común, está bueno tener un procedimiento que lo resuelva: lo escribimos una vez y lo usamos para siempre

> Tu tarea es escribir un procedimiento `PonerN(cantidad, color)` que reciba un número y un color, y ponga la cantidad de bolitas del color dado.
