# Rincón del Ring

**Manual visual e interactivo de los golpes fundamentales del boxeo.** Una sola página HTML, sin dependencias ni build, pensada para enseñar a identificar cada golpe por su trayectoria, su mecánica y la zona real del cuerpo donde impacta.

> Diagrama animado de un boxeador frente a una silueta de práctica, fichas técnicas de los 6 golpes de la numeración oficial, variantes tácticas, tablas comparativas y un quiz de reconocimiento visual.


## Deploy

Pensado para desplegarse en [Vercel](https://rincon-del-ring.vercel.app/) como sitio estático: importar el repo, sin framework preset, sin build command.

## Características

- **Sistema de numeración (1–6):** jab, cross, gancho adelantado, gancho trasero, uppercut adelantado y uppercut trasero, tal como se enseñan y se gritan en cualquier gimnasio.
- **Diagrama interactivo persistente:** las 6 trayectorias están siempre visibles como líneas guía; al seleccionar un golpe, su recorrido se anima en color hasta la zona de impacto real (mentón, sien, plexo solar o hígado) sobre una silueta rival.
- **Toggle de guardia:** alterná entre postura ortodoxa y zurda (southpaw); el diagrama se espeja y las etiquetas se actualizan.
- **Modo golpe individual:** ficha técnica completa por golpe — biomecánica, uso táctico, error común y defensa habitual.
- **Modo combinaciones:** armá tu propia secuencia, elegí entre 8 combinaciones preparadas (uno-dos, rompe guardia, ataque al cuerpo, etc.), generá una combinación aleatoria y controlá la velocidad de reproducción.
- **Variantes y golpes especiales:** jab doble, jab de cuerpo, overhand, cross de contra, check hook, gancho al hígado, bolo punch y uppercut en clinch.
- **Tablas comparativas:** trayectoria, alcance, velocidad, potencia, riesgo al fallar, gasto energético, distancia ideal y un exponente histórico de referencia por golpe, además de una tabla dedicada a las variantes.
- **Quiz de reconocimiento:** se muestra la trayectoria sin nombre y hay que identificar el golpe; incluye botón para repetir la animación las veces que haga falta antes de responder.
- **100% responsive** y respeta `prefers-reduced-motion` para quienes prefieren menos animaciones.

## Uso

No requiere instalación ni build. Alcanza con abrir el archivo en un navegador:

```bash
git clone https://github.com/cainramirez-cmd/rincon-del-ring.git
cd rincon-del-ring
open index.html   # o hacé doble clic en el archivo
```

También podés publicarlo directamente con **GitHub Pages**: `Settings → Pages → Deploy from branch → main /(root)`.

## Estructura

```
rincon-del-ring/
├── index.html   # App completa: HTML + CSS + JS en un solo archivo
├── LICENSE      # Licencia MIT
└── README.md
```

## Tecnologías

- HTML5 + CSS3 (variables CSS, grid, clamp para tipografía fluida)
- JavaScript vanilla (sin frameworks ni dependencias de build)
- SVG dibujado e importado a mano para el diagrama de trayectorias
- Tipografías [Anton](https://fonts.google.com/specimen/Anton), [Oswald](https://fonts.google.com/specimen/Oswald) e [Inter](https://fonts.google.com/specimen/Inter) vía Google Fonts

## Nota

Esta guía es un punto de partida visual, no un reemplazo de la enseñanza presencial. Para corregir la mecánica real de cada golpe (postura, respiración, protección del mentón) entrená siempre frente a un entrenador o en un gimnasio con supervisión.

## Licencia

Distribuido bajo licencia [MIT](./LICENSE).

---

© 2026 [Caín N. Ramirez](https://github.com/cainramirez-cmd)
