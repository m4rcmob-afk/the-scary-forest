# Portal de juegos · LOS BRAWLHALLAS

Dos juegos de Unity accesibles desde https://m4rcmob-afk.github.io/the-scary-forest/

## Juegos

- **The Scary Forest**: `TheScaryForest-Juego/index.html`. Endless runner 3D, tres vidas y récord local. Se conservan sus archivos originales.
- **Maze / 03**: `Pacman-Juego/index.html`. Laberinto 3D inspirado en Pac-Man: 36 puntos, dos enemigos con visión frontal y una salida desbloqueable.

La portada permite abrir cada juego directamente o cargar uno dentro del portal. Al cambiar de juego se descarga el reproductor anterior de la página; la partida en curso termina.

## Controles

The Scary Forest: Espacio / arriba / derecha para saltar; abajo / S para agacharse; P / Esc para pausa; R / Enter al perder.

Maze / 03: flechas para moverse, R para reiniciar, M para silenciar o activar la música. Recoger los 36 puntos y salir por la puerta superior; tocar un enemigo termina la partida.

## Publicación

GitHub Pages publica `main`, carpeta raíz `/`. Mantener `.nojekyll`, `index.html` y las dos carpetas de juego. WebGL requiere HTTP/HTTPS y JavaScript activado. La compilación Maze usa Gzip con descompresión de respaldo para funcionar en GitHub Pages sin cabeceras personalizadas.

Para actualizar Maze desde Unity: **Pac-Man > Compilar juego para GitHub Pages**. El resultado se escribe en `PortalWeb/Pacman-Juego/` dentro del proyecto Unity. Subir los archivos completos de la compilación, no los assets fuente de Unity.

## Equipo

- Marco Arturo Cabrera Escobar
- Alan Steven Torrez Lopez
- Jheremy Jhostin Ramirez Arcani
