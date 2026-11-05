# Pocket Monster · Tu primera aventura

Guía web para entrenadores Pokémon novatos, organizada por generaciones.
Proyecto de clase de **1º de DAW**, hecho solo con **HTML y CSS**.

🔗 **Ver la web:** https://marcotecdev.github.io/guia-entrenador-novato/

## Contenido

- **Página de inicio** con una tarjeta por cada generación: número, región, juegos, año y la consola en la que salió.
- **10 páginas de generación** (de Kanto a la generación 10), cada una con su color y con estas secciones:
  historia de la región, mapa, juegos (originales, remakes, secuelas y DLC) y Pokémon iniciales.
- **Página de contacto** (en construcción).
- Enlaces para ir a la generación anterior y a la siguiente.
- Diseño adaptado a ordenador, tablet y móvil.

## Estructura del proyecto

```
guia-entrenador-novato/
├── index.html               Página de inicio
├── generacion-1.html        Páginas de cada generación
├── ...
├── generacion-10.html
├── contacto.html            Página de contacto
├── css/
│   ├── estilos.css          Hoja de estilos de toda la web
│   └── fuentes/             Fuente pixel Press Start 2P
├── img/
│   ├── consolas/            Imágenes de las consolas de cada generación
│   ├── pokemon/
│   │   ├── modelos/         Modelos 3D de los iniciales (Escarlata y Púrpura)
│   │   └── sprites/         Sprites pixel art de los iniciales
│   ├── regiones/            Una carpeta por región (1-kanto, 2-johto... 10-por-descubrir)
│   │   ├── 1-kanto/mapa.png      Mapa de la región (aquí van también sus carátulas e iniciales)
│   │   ├── ...
│   │   └── 9-paldea/             Mapa e imágenes de los DLC (dlc1-..., dlc2-...)
│   └── en-construccion.jpg  Imagen de las páginas en construcción
└── media/                   Audio y vídeo (vacía de momento)
```

## Tecnologías

- **HTML5**
- **CSS3**: flexbox, grid, `@font-face`, `@media` para móvil y transiciones con `:hover`.

No usa JavaScript ni librerías externas: todo funciona en local, sin conexión a internet.

## Cómo verla en local

1. Descarga o clona el repositorio:
   ```bash
   git clone https://github.com/MarcoTecDev/guia-entrenador-novato.git
   ```
2. Abre `index.html` en el navegador.

## Créditos

- **Fuente:** [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P), de CodeMan38, licencia SIL Open Font License.
- **Imágenes de los Pokémon:** [PokeAPI/sprites](https://github.com/PokeAPI/sprites): modelos de Escarlata y Púrpura y sprites pixel art, recortados y redimensionados.
- **Imágenes de consolas:** tema «Systematic» de [RetroArch Assets](https://github.com/libretro/retroarch-assets) (libretro), licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Recortadas y redimensionadas.
- **Pokémon** y sus personajes son © Nintendo, Game Freak y The Pokémon Company. Este es un proyecto educativo sin ánimo de lucro y no tiene relación oficial con ellos.

## Autor

**MarcoTecDev** · [GitHub](https://github.com/MarcoTecDev)
