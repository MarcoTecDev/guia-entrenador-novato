<div align="center">

<img src="img/pokemon/ilustraciones/pikachu.png" alt="Pikachu" width="160">

# Pocket Monster · Tu primera aventura

**¡Bienvenido al mundo de los Pokémon, entrenador!**

*Guía web para entrenadores Pokémon novatos, organizada por generaciones.*

<img src="img/readme/pokedex-1025.svg" alt="Los 1025 Pokémon desfilando" width="880">

<sub>🔴 ¡Los <b>1025 Pokémon</b> de la Pokédex Nacional, desfilando sin parar!</sub>

### 🗺️ [¡Empieza tu aventura en Kanto!](https://marcotecdev.github.io/guia-entrenador-novato/)

![HTML5](https://img.shields.io/badge/Tipo-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Tipo-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-No%20es%20muy%20eficaz...-lightgrey?style=for-the-badge)
![Nivel](https://img.shields.io/badge/Entrenador-1º%20de%20DAW-FFCB05?style=for-the-badge)

</div>

---

> 🧑‍🔬 **Profesor:** ¡Hola! ¡Bienvenido al mundo de los POKéMON!
> Este es un proyecto de clase de **1º de DAW**, entrenado solo con **HTML y CSS**.
> Tu aventura está a punto de comenzar... ▼

---

## 🎒 Mochila · Contenido de la web

| Objeto | Descripción |
| :---: | --- |
| 🏠 **Página de inicio** | Una tarjeta por cada generación: número, región, juegos, año y la consola en la que salió. |
| 🗺️ **10 páginas de generación** | De Kanto a la generación 10, cada una con su color y con estas secciones: historia de la región, mapa, juegos (originales, remakes, secuelas y DLC), tráileres de YouTube (con `<iframe>`) y Pokémon iniciales. |
| ✉️ **Página de contacto** | 🚧 En construcción. |
| 🔀 **Rutas** | Enlaces para ir a la generación anterior y a la siguiente. |
| 📱 **Diseño adaptable** | Funciona en ordenador, tablet y móvil. |

---

## 🧭 Mapa de la región · Estructura del proyecto

```
🗺️ guia-entrenador-novato/
├── 🏠 index.html               Pueblo de origen: página de inicio (se queda fuera para que GitHub Pages la encuentre)
├── 🛤️ paginas/
│   ├── ✉️ contacto.html        Página de contacto
│   └── 📍 generaciones/
│       ├── generacion-1.html    Páginas de cada generación
│       ├── ...
│       └── generacion-10.html
├── 🎨 css/
│   ├── estilos.css          Hoja de estilos de toda la web
│   └── fuentes/             Fuente pixel Press Start 2P
├── 🖼️ img/
│   ├── caratulas/           Carátulas de los juegos, una carpeta por generación (gen1... gen10)
│   ├── consolas/            Imágenes de las consolas de cada generación
│   ├── readme/              Carrusel animado de los 1025 Pokémon para este README
│   ├── pokemon/
│   │   ├── ilustraciones/   Ilustraciones oficiales de los iniciales
│   │   └── iconos/          Iconos de menú de los iniciales (Escarlata y Púrpura)
│   ├── regiones/            Una carpeta por región (1-kanto, 2-johto... 10-por-descubrir)
│   │   ├── 1-kanto/mapa.png      Mapa de la región (aquí van también sus carátulas e iniciales)
│   │   ├── ...
│   │   └── 9-paldea/             Mapa e imágenes de los DLC (dlc1-..., dlc2-...)
│   └── en-construccion.jpg  Imagen de las páginas en construcción
└── 📼 media/                Audio y vídeo (vacía de momento)
```

---

## ⚔️ Movimientos aprendidos · Tecnologías

<div align="center">

| Movimiento | Tipo | Efecto |
| --- | :---: | --- |
| **HTML5** | 🟠 Estructura | Esqueleto de todas las páginas. |
| **CSS3** | 🔵 Estilo | Flexbox, grid, variables, `@font-face`, `@media` para móvil y transiciones con `:hover`. |

</div>

> ⚠️ **¡JavaScript no está en el equipo!** La web no usa JavaScript ni librerías externas.
> Todo funciona en local salvo los tráileres, que se cargan desde YouTube y necesitan internet.

---

## 🎮 ¡Pulsa START! · Cómo verla en local

<img src="img/consolas/game-boy.png" width="72" align="right" alt="Game Boy">

1. **Captura** el repositorio (descárgalo o clónalo):
   ```bash
   git clone https://github.com/MarcoTecDev/guia-entrenador-novato.git
   ```
2. **Abre** `index.html` en el navegador.
3. ¡Elige a tu inicial y empieza a explorar! 🔴⚪

---

## 📜 Pokédex de créditos

- **Fuente:** [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P), de CodeMan38, licencia SIL Open Font License.
- **Imágenes de los Pokémon:** [PokeAPI/sprites](https://github.com/PokeAPI/sprites): ilustraciones oficiales e iconos de menú de Escarlata y Púrpura, recortados y redimensionados.
- **Iniciales de la generación 10** (Browt, Pombon y Gecqua): ilustraciones oficiales tomadas de [WikiDex](https://www.wikidex.net/wiki/Pok%C3%A9mon_Viento_y_Pok%C3%A9mon_Oleaje).
- **Carrusel de los 1025 Pokémon del README:** sprites de [PokeAPI/sprites](https://github.com/PokeAPI/sprites), unidos en una sola tira animada con SVG.
- **Sprites de la generación 10:** hechos por [CarnekVT](https://www.deviantart.com/carnekvt/art/Pokemon-Winds-and-Waves-Starters-in-Sprite-version-1303886486) en DeviantArt (aún no hay sprites oficiales).
- **Carátulas de los juegos:** [WikiDex](https://www.wikidex.net), ajustadas a un mismo tamaño cuadrado (440 × 440).
- **Imágenes de consolas:** tema «Systematic» de [RetroArch Assets](https://github.com/libretro/retroarch-assets) (libretro), licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Recortadas y redimensionadas.
- **Pokémon** y sus personajes son © Nintendo, Game Freak y The Pokémon Company. Este es un proyecto educativo sin ánimo de lucro y no tiene relación oficial con ellos.

---

<div align="center">

## 🏆 Entrenador

**MarcoTecDev** · [GitHub](https://github.com/MarcoTecDev)

<img src="img/pokemon/iconos/browt.png" width="48" alt="Browt"><img src="img/pokemon/iconos/pombon.png" width="48" alt="Pombon"><img src="img/pokemon/iconos/gecqua.png" width="48" alt="Gecqua">

*¡Hazte con todos!* ✨

</div>
