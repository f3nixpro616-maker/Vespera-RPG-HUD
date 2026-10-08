# Vespera RPG HUD

Extensión experimental para SillyTavern. Fichas multijugador, barras de Carne/Psique/Impulso, inventario, óbolos, ubicación, condiciones, consecuencias, marcas y Caras del Destino.

## Publicar en GitHub

Crea un repositorio y sube `manifest.json`, `index.js`, `style.css` y este README a la **raíz**. Luego en SillyTavern: **Extensions → Install extension** y pega la URL del repositorio.

## Uso

Pulsa **⚔ Vespera** abajo a la derecha. Crea fichas con **+ PJ**, edita sus valores, lanza 2 a 5 Caras del Destino y exporta partidas como JSON.

Los resultados son dados d6 individuales (no se suman): 1 Ruptura, 2 Vacío, 3 Tensión, 4 Acierto, 5 Triunfo, 6 Resonancia. Se usa la aleatoriedad criptográfica del navegador.

**Limitaciones:** datos guardados solo en el navegador mediante `localStorage`; no se sincronizan entre dispositivos o jugadores. La IA no actualiza las fichas ni ve automáticamente las tiradas: usa **Copiar estado** y pégalo en el chat. No probado todavía dentro de una instalación real de SillyTavern.
