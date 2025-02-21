# El Zorro y las Ocas 🦊🦢

## Descripción

**"El Zorro y las Ocas"** es un juego de **jugador contra jugador** en el que un jugador controla al zorro y otro a las ocas. El objetivo del zorro es comer todas las ocas, mientras que las ocas deben intentar atrapar al zorro. El juego se desarrolla en un tablero con reglas similares a las del juego de las damas.
Realizado en Intelx86.

### Objetivos del Juego:
- **Zorro:** Comer todas las ocas saltando sobre ellas y ganando turnos adicionales por cada oca comida.
- **Ocas:** Intentar atrapar al zorro moviéndose en su dirección.

## Reglas del Juego

1. **Tablero:**  
   El juego se juega en un tablero con 4 orientaciones posibles. El jugador puede elegir cualquiera de ellas al inicio.

2. **Movimiento del Zorro:**  
   El zorro puede moverse en cualquier dirección y, si salta sobre una oca, la come. Al comer una oca, obtiene otro turno.

3. **Movimiento de las Ocas:**  
   Las ocas solo pueden moverse hacia el zorro, intentando atraparlo.

4. **Victoria:**  
   - El **zorro** gana si logra comer todas las ocas.  
   - Las **ocas** ganan si logran acorralar al zorro.

5. **Contador de Movimientos:**  
   Se mantiene un contador del número de movimientos realizados por el zorro.

6. **Guardar y Cargar Partidas:**  
   El juego permite guardar una única partida por tablero.

---

## Instrucciones de Uso para Linux

### 1. Ensamblar el archivo principal:
```bash
nasm main.asm -f elf64
```

### 2. Ensamblar el archivo con la lógica del juego:
```bash
nasm procedimientoDelJuego.asm -f elf64
```

### 3. Crear el ejecutable del juego:
```bash
gcc procedimientoDelJuego.o main.o -no-pie -o juego
```

### 4. Ejecutar el juego:
```bash
./juego
```


