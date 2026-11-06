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
- Botón de modo día (icono de Solrock, fondo de Reshiram) y modo noche (icono de Lunatone, fondo de Zekrom), hecho solo con CSS.

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
│   ├── caratulas/           Carátulas de los juegos, una carpeta por generación (gen1... gen10)
│   ├── wallpaper/           Fondos de pantalla del modo día (Reshiram) y noche (Zekrom)
│   ├── modoNocheDia/        Iconos del botón de modo: Solrock (día) y Lunatone (noche)
│   ├── consolas/            Imágenes de las consolas de cada generación
│   ├── pokemon/
│   │   ├── ilustraciones/   Ilustraciones oficiales de los iniciales
│   │   └── iconos/          Iconos de menú de los iniciales (Escarlata y Púrpura)
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
- **Imágenes de los Pokémon:** [PokeAPI/sprites](https://github.com/PokeAPI/sprites): ilustraciones oficiales e iconos de menú de Escarlata y Púrpura, recortados y redimensionados.
- **Iniciales de la generación 10** (Browt, Pombon y Gecqua): ilustraciones oficiales tomadas de [WikiDex](https://www.wikidex.net/wiki/Pok%C3%A9mon_Viento_y_Pok%C3%A9mon_Oleaje).
- **Sprites de la generación 10:** hechos por [CarnekVT](https://www.deviantart.com/carnekvt/art/Pokemon-Winds-and-Waves-Starters-in-Sprite-version-1303886486) en DeviantArt (aún no hay sprites oficiales).
- **Carátulas de los juegos:** [WikiDex](https://www.wikidex.net), ajustadas a un mismo tamaño cuadrado (440 × 440).
- **Imágenes de consolas:** tema «Systematic» de [RetroArch Assets](https://github.com/libretro/retroarch-assets) (libretro), licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Recortadas y redimensionadas.
- **Pokémon** y sus personajes son © Nintendo, Game Freak y The Pokémon Company. Este es un proyecto educativo sin ánimo de lucro y no tiene relación oficial con ellos.

## Autor

**MarcoTecDev** · [GitHub](https://github.com/MarcoTecDev)
