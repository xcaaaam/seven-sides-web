# Seven Sides — website (v1, prototipo)

Pantalla principal de Seven Sides: plataforma que conecta empresas (cooperantes) con proyectos y comunidades de Latinoamérica para cooperar con valor compartido, sin burocracia.

## Qué incluye
- Carrusel infinito con los 7 pilares; al pasar el cursor, la tarjeta se expande y muestra el pilar en una capa de vidrio.
- Barra inferior: logo a la izquierda y tres acciones en estilo *liquid glass*: **Unirme como cooperante**, **Postular mi proyecto** y **¿Qué es Seven Sides?**
- Formularios de prototipo (aún no envían datos) y panel explicativo con el heptágono: 7 pilares nombrados y la naturaleza al centro.
- Adaptado a móvil.

## Añadir las animaciones
Cada tarjeta tiene un espacio reservado. Para usar un video o imagen libre de derechos:
1. Copia el archivo en `assets/media/` (ej. `energia.mp4`, ideal < 4 MB, en bucle, sin audio).
2. En `index.html`, dentro de `PILLARS`, cambia `media:null` por `media:"assets/media/energia.mp4"` en el pilar que corresponda.

## Estructura
```
index.html          página completa (HTML, CSS y JS)
assets/brand/       logos e isotipo en SVG
assets/media/       animaciones de las tarjetas (pendientes)
```

## Ver en local
Abre `index.html` en el navegador. Para publicarlo: GitHub Pages → Settings → Pages → rama `main`, carpeta raíz.

## Tipografías
Poppins (marca), Sora (texto) y JetBrains Mono (detalles), desde Google Fonts. Verde de marca: `#0d9944`.
