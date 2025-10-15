
# Salar de Uyuni - Atardecer (HTML + CSS)

Ahora el proyecto representa el Salar de Uyuni al atardecer. La escena está hecha únicamente con HTML y CSS (sin imágenes). Incluye cielo con nubes en movimiento, sol con resplandor, cordillera lejana, la planicie blanca del salar con reflejos tipo espejo y pequeñas islas rocosas.

Características principales:
- 100% CSS/HTML, sin imágenes.
- Animaciones con `@keyframes`: nubes en movimiento, ligero vaivén del sol y shimmer en la superficie del salar.
- Efectos hover/focus: elevación de islas (hover/focus en `.island`) y mayor brillo en la superficie al pasar el cursor sobre la escena.

Archivos:
- `index.html` - la página principal (Salar de Uyuni al atardecer).
- `styles.css` - estilos y todas las formas/animaciones.

Cómo abrir:
1. Abrir `index.html` en un navegador moderno (Chrome, Edge, Firefox).
2. Para desarrollo, abrir en VS Code y usar la extensión Live Server o simplemente arrastrar `index.html` al navegador.

Siguientes mejoras posibles:
- Modo noche (luna + estrellas) con transición; botón para alternar día/noche.
- Añadir fauna (flamencos en charcas, cóndores volando) exclusivamente en CSS.
- Efecto parallax con JavaScript para profundidad al mover el ratón.

Si quieres que añada alguna de estas mejoras, dime cuál y la implemento.

Modos disponibles:
- Día: paleta clara y cielo azul, brillo alto en la superficie.
- Tarde: paleta de atardecer (modo por defecto al abrir la página).
- Amanecer: tonos cálidos y ligero brillo en la sal.
- Noche: oculta el sol, muestra la luna y estrellas, paleta oscura.

Cómo usar el selector de modo:
- Usa los botones en la esquina superior izquierda para alternar entre `Día`, `Tarde`, `Amanecer` y `Noche`.
- Los botones son accesibles: puedes moverte con Tab y activar con Enter o Barra espaciadora.

Si quieres que el modo se guarde (localStorage) o que el cambio tenga animación adicional, lo añado.
