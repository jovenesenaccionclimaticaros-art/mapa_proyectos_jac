# Mapa de proyectos · Fondo Jóvenes en Acción Climática Rosario

Mapa interactivo (Leaflet + OpenStreetMap) de los proyectos de las ediciones 2024, 2025 y 2026.

- `index.html`: el mapa.
- `proyectos.csv`: los datos. Para sumar o corregir un proyecto, editá este archivo (columnas `lat` y `lon` en grados decimales; `eje` es el eje de la convocatoria y `tema` el grupo para filtrar). Los que no tienen coordenadas aparecen en "Sin ubicar".

## Publicar en GitHub Pages
1. Subí `index.html` y `proyectos.csv` a un repositorio nuevo.
2. Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.
3. En un par de minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
