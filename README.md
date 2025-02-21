El Zorro y las Ocas
Descripción
"El Zorro y las Ocas" es un juego de jugador contra jugador en el que un jugador controla al zorro y otro a las ocas. El objetivo del zorro es comer todas las ocas, mientras que las ocas deben intentar atrapar al zorro. El juego se desarrolla en un tablero y utiliza reglas similares a las del juego de las damas.

Objetivos del Juego:
Zorro: Comer todas las ocas saltando sobre ellas y ganando turnos adicionales por cada oca comida.
Ocas: Intentar atrapar al zorro moviéndose en su dirección.
Reglas del Juego
Tablero: El juego se juega en un tablero con 4 orientaciones posibles. El jugador puede elegir cualquiera de ellas al inicio.

Movimiento del Zorro: El zorro puede moverse en cualquier dirección y, si salta sobre una oca, la come. Al comer una oca, obtiene otro turno.

Movimiento de las Ocas: Las ocas solo pueden moverse hacia el zorro, intentando atraparlo.

Victoria:

El zorro gana si logra comer todas las ocas.
Las ocas ganan si logran acorralar al zorro.
Contador de Movimientos: Se mantiene un contador del número de movimientos realizados por el zorro.

Guardar y Cargar Partidas: El juego permite guardar una única partida por tablero.

Instrucciones de Uso
Compilar y Ejecutar:
Ensamblar el archivo principal:

bash
Copiar
Editar
nasm main.asm -f elf64
Ensamblar el archivo con la lógica del juego:

bash
Copiar
Editar
nasm procedimientoDelJuego.asm -f elf64
Crear el ejecutable del juego:

bash
Copiar
Editar
gcc procedimientoDelJuego.o main.o -no-pie -o juego
Ejecutar el juego:

bash
Copiar
Editar
./juego
Tecnologías Utilizadas
Lenguaje de Programación: Assembly Intel x86
Compilador: NASM y GCC
Plataforma: Linux (consola)
