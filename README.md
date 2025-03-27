# Bimestral_1
Bimestral No.1 (Periodo_1)

# Pygame number1

En este juego controlas el cohete de un agente espacial llamado: Ramko-Poochi y tu objetivo es escapar de latino america, pero no sera nada facil por que tendras que evitar colisionar con planetas que caen en el trancurso de tu viaje en el espacio.

## Condiciones

* Python 3.x
* Pygame (`pip install pygame`)

## Proceso :D

1.  Asegúrate de tener Python y Pygame instalados.
2.  Guarda el código en un archivo llamado `juego.py`.
3.  Crea una carpeta llamada `img` en el mismo directorio que `juego.py`.
4.  Coloca las imágenes `COHETE.png` y `PLANETA.png` dentro de la carpeta `img`.
5.  Abre una terminal o línea de comandos, navega al directorio donde guardaste el archivo `juego.py` y ejecuta:

    ```bash
    python juego.py
    ```

## Controles

* **Flecha Derecha:** Mueve el cohete a la derecha.
* **Flecha Izquierda:** Mueve el cohete a la izquierda.
* **ESC:** Game Over (perdiste xd)

## Estructura del Código

* **Inicialización:** Se inicializa Pygame, se definen las dimensiones de la ventana, los colores, y se cargan las imágenes.
* **Variables del Juego:** Se definen variables para la posición y movimiento del cohete, la posición y velocidad de los planetas, la puntuación, y la fuente para mostrar la puntuación.
* **Bucle Principal:** El bucle principal del juego se ejecuta hasta que el jugador presiona ESC o el cohete colisiona con un planeta o se sale de los margenes de la ventana.

## Imágenes

El juego utiliza las siguientes imágenes:

* `img/COHETE.png`: Imagen del cohete.
* `img/PLANETA.png`: Imagen de los planetas.

Asegúrate de que estas imágenes estén presentes en la carpeta `img` para que el juego funcione correctamente.