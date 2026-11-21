# Medellín Te Orienta · Proyecto universitario

Página web que reúne los entregables del proyecto **Medellín Te Orienta**, una guía para que la ciudadanía sepa a dónde acudir y cómo reportar incidentes de inseguridad en Medellín.

**Institución Universitaria Pascual Bravo** · TICs y Competencias Digitales · Docente: Julián Andrés Correa Uribe · 2026

## Contenido

| Sección | Archivo |
| --- | --- |
| Página del proyecto | `index.html` |
| 01 · Planteamiento del problema | `docs/planteamiento-del-problema.pdf` |
| 02 · Ensayo | `docs/ensayo.pdf` |
| 03 · Guion del pitch | `docs/guion-del-pitch.pdf` |
| 04 · Video del pitch | Configurable en `index.html` (`VIDEO_CONFIG`) |
| 05 · Prototipo | `prototipo/index.html` |
| 06 · Demostración | `assets/demo/1.jpg` – `4.jpg` |
| 07 · Solución final | `solucion/index.html` |

## Equipo

- [Mónica Alvarado](https://sites.google.com/pascualbravo.edu.co/angelesvisual?usp=sharing)
- [Emanuel Henao](https://sites.google.com/pascualbravo.edu.co/emanuelhenaoportafolio/inicio)
- [Isabella Sepúlveda](https://sites.google.com/pascualbravo.edu.co/mi-perfilprofesional/pagina-de-inicio)

## Ver en local

Sitio estático en HTML, CSS y JS, sin dependencias. Abre `index.html` o sirve la carpeta:

```bash
python -m http.server 8000
```

## Publicar con GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.

## Agregar el video

En `index.html`, busca `VIDEO_CONFIG` y completa **una** opción:

```js
const VIDEO_CONFIG = { youtube: "https://youtu.be/TU_ID", file: "", poster: "" };
// o, con un MP4 de menos de 100 MB dentro del repo:
const VIDEO_CONFIG = { youtube: "", file: "video/video-pitch.mp4", poster: "" };
```

> Proyecto académico. No es un canal oficial de la Alcaldía, la Policía ni la Fiscalía. En caso de emergencia llama al **123**.
