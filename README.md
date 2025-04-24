#Proyecto: Rock-Paper-Scissors

Este proyecto es una implementación del clásico juego de "Piedra, Papel o Tijeras", en el que un jugador humano se enfrenta a una inteligencia artificial (IA). El objetivo es crear un juego interactivo que permita a un jugador elegir entre Piedra, Papel o Tijeras, y que el sistema determine quién gana según las reglas del juego.

Descripción del Juego

El juego sigue las reglas tradicionales:

Piedra gana a Tijeras.
Tijeras gana a Papel.
Papel gana a Piedra.
El jugador humano hace su elección, y la IA hace la suya. Luego se determina el resultado:

Si ambos jugadores eligen lo mismo, es un empate.
Si el jugador humano gana, se muestra el mensaje correspondiente.
Si la IA gana, también se muestra el resultado.
Lógica del Juego

Elección del Jugador: El jugador puede elegir entre tres opciones: Piedra, Papel o Tijeras. Se le solicita que ingrese su elección por medio de la terminal.
Elección de la IA: La IA elige aleatoriamente entre Piedra, Papel o Tijeras utilizando la función random.choice(), lo que le permite tomar decisiones al azar.
Determinación del Resultado: Después de que ambos jugadores hacen su elección, el juego determina el resultado utilizando las reglas previamente mencionadas:
Si ambos jugadores eligen lo mismo, se declara un empate.
Si las elecciones no son iguales, se determina el ganador según las reglas tradicionales de "Piedra, Papel o Tijeras".
Estructura de Archivos:
main.py: Contiene la función principal que interactúa con el jugador, muestra los resultados y controla el flujo del juego.
RPS.py: Define las funciones que manejan la lógica del juego, como la elección de la IA y la determinación del resultado.
test_module.py: Contiene pruebas unitarias para asegurarse de que las funciones que implementan la lógica del juego funcionen correctamente.
Características Adicionales

Interactividad: El juego interactúa con el jugador a través de la terminal, pidiendo que elijan una opción entre Piedra, Papel o Tijeras.
Mensajes de Resultados: Después de cada ronda, el juego muestra un mensaje indicando si el jugador ha ganado, perdido o si ha sido un empate.
Repetibilidad: El jugador puede jugar varias rondas de forma continua, y el juego sigue funcionando hasta que el jugador decida detenerse.
Cómo jugar

Para jugar, simplemente ejecuta el archivo main.py en tu entorno local, y sigue las instrucciones que se muestran en la terminal para hacer tu elección.

bash
Copiar
Editar
python main.py
El juego continuará hasta que decidas salir.

