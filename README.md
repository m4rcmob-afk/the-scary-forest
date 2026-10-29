# The Scary Forest

Portal oficial y videojuego Web desarrollado por **LOS BRAWLHALLAS**.

- Marco Arturo Cabrera Escobar
- Alan Steven Torrez Lopez
- Jheremy Jhostin Ramirez Arcani

Portal: https://m4rcmob-afk.github.io/the-scary-forest/

La página principal presenta la historia, el personaje, los controles, las reglas, las métricas y el equipo. Desde Jugar ahora se abre la versión de Unity, que también puede ejecutarse dentro del portal.

## Controles

- Espacio / flecha arriba / flecha derecha: saltar.
- Flecha abajo / S: agacharse.
- Esc / P: pausa, continuar, reiniciar o volver al inicio.
- R / Enter: reiniciar tras perder.

Tres vidas, un punto por obstáculo esquivado y récord local. La carrera continúa hasta el tercer choque.

## Publicación

GitHub Pages publica la rama `main`, carpeta raíz `/`. `index.html` es el portal; `TheScaryForest-Juego/index.html` es el juego. Mantener los archivos de `Build/` junto a la versión Web y el archivo `.nojekyll` en la raíz.

Para actualizar el juego, reemplazar los archivos de `TheScaryForest-Juego/` con una nueva compilación Web de Unity y subir un commit. Los controles requieren un teclado; el juego se sirve por HTTP/HTTPS.
