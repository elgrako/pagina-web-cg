# Code Genius eSports — Página web

Landing page de la comunidad de eSports **Code Genius**: presentación del club, calendario de partidos, rosters de equipos y acceso a Discord.

## Secciones

- **Inicio** — cabecera con efecto parallax.
- **Sobre nosotros** — presentación del club.
- **Calendario** — próximos partidos y publicaciones sociales, en carruseles (Swiper).
- **Equipo** — tarjetas de los rosters con efecto de tarjeta 3D (CSS `perspective` / `transform-style: preserve-3d`).
- **Jugadores** — miembros del club.
- **Tutoriales** y enlace directo a Discord.

## Tecnologías

HTML, CSS y JavaScript vanilla. [Swiper](https://swiperjs.com/) (vía CDN) para los carruseles de calendario. Efecto parallax e interacciones con tarjetas implementados a mano en CSS/JS, sin librerías de animación adicionales.

## Estructura

| Archivo | Contenido |
|---|---|
| `index.html` | Contenido y estructura de la página |
| `styles.css` | Estilos principales (incluye las tarjetas 3D y el layout) |
| `parallax.css` | Estilos del efecto parallax de la cabecera |
| `img/` | Logos, avatares del roster y recursos gráficos |

## Cómo usarla

Página estática: basta con abrir `index.html` en el navegador. No requiere build ni backend.
