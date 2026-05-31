# vorld-landing

> Cinematic agency landing page built with Three.js, GSAP & vanilla JS — no frameworks, no build tools.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat&logo=greensock&logoColor=black)

---

## Vista previa

Una landing page de agencia digital con estética editorial oscura, partículas 3D reactivas al ratón, animaciones de scroll y tipografía bold. Construida en un único archivo HTML autocontenido, sin dependencias de build ni frameworks.

---

## Stack

| Tecnología | Uso |
|---|---|
| **Three.js r128** | Campo de partículas 3D + torus knot animado + canvas procedurales |
| **GSAP 3.12 + ScrollTrigger** | Animaciones de entrada, parallax, reveal on scroll, contadores |
| **Canvas 2D API** | Arte generativo en las tarjetas de proyectos (grid, waves, dots) |
| **Anton (Google Fonts)** | Tipografía display con soporte completo de caracteres latinos |
| **HTML / CSS / JS puro** | Sin React, sin Vite, sin dependencias de build |

---

## Características

- **Fondo Three.js** — 2200 partículas animadas con líneas de conexión dinámicas y parallax al mover el ratón
- **Torus knot 3D** — objeto metálico con iluminación dinámica en la sección "Sobre el estudio"
- **Arte generativo** — tres canvas procedurales únicos para las tarjetas de proyectos
- **GSAP ScrollTrigger** — reveals, parallax en el hero, contadores animados y stagger en cards
- **Cursor personalizado** — cursor dot con blend mode `difference`
- **Marquee infinito** — banda de servicios con pausa en hover
- **Navbar reactiva** — backdrop-filter y border al hacer scroll
- **Scroll suave** — navegación anclada con ease personalizado
- **Un solo archivo** — `index.html` autocontenido, abre directo en el navegador

---

## Uso

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/vorld-landing.git

# Abre en el navegador (sin servidor necesario)
open index.html
```

O simplemente descarga `index.html` y ábrelo directamente.

---

## Estructura

```
vorld-landing/
└── index.html   # Todo en un único archivo: HTML + CSS + JS
```

---

## Personalización rápida

Las variables CSS en `:root` controlan toda la paleta:

```css
:root {
  --bg:      #0a0a0a;   /* Fondo principal */
  --accent:  #d4ff5e;   /* Color de acento */
  --text:    #f0ede6;   /* Texto principal */
  --muted:   #5a5a52;   /* Texto secundario */
}
```

---

## Licencia

MIT — úsalo, modifícalo y adáptalo libremente.
