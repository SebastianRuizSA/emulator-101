# emulator-101
How to make emulators

## Objetivo:
Repasar el funcionamiento de una CPU para tener en cuenta las limitantes del hardware al programar. 
Repaso de conceptos claves en C, como por ejemplo punteros.
Aprender un poco de ASM.
Aprender la arquitectura de un 8080(procesador de 8-bit).

## Fundamentales:
CPU -> registros(A es un acumulador, los otros 6 son regitros de 8 bit siendo posible generar 3 registros de 16, BC por ejemplo) e instrucciones(1-3 bytes)
PC(Program Counter, 16 bit) -> Puntero
Timing -> En un procesador cada instruccion toma un cierto tiempo en completarse (ciclos), en 8080 estos tiempos son constantes.
Logica -> Los procesadores utilizan operaciones logica(AND OR por ejemplo), como en el caso de los arcades en donde se quiere cambiar un solo bit de registro.
ASM -> Cada linea es una instruccion al procesador, la idea es escribir el minimo de instrucciones posibles para realizar una tarea.
Stacks -> Push/Pop desde el principio.


