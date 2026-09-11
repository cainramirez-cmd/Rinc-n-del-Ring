# Rincón del Ring

**Manual visual e interactivo de los golpes fundamentales del boxeo.** Una sola página HTML, sin dependencias ni build, pensada para enseñar a identificar cada golpe por su trayectoria, su mecánica y la zona real del cuerpo donde impacta — y también a leer táctica, escuelas, defensa y el cuerpo bajo fuego.

> Diagrama animado de un boxeador frente a una silueta de práctica, fichas técnicas de los 6 golpes de la numeración oficial, cues de entrenadores, escenarios tácticos, biología del impacto, tablas comparativas, glosario, quiz de reconocimiento y una lista de peleas para estudiar.


## Deploy

Pensado para desplegarse en [Vercel](https://rincon-del-ring.vercel.app/) como sitio estático: importar el repo, sin framework preset, sin build command.


## Características

### Fundamentos y diagrama
- **Sistema de numeración (1–6):** jab, cross, gancho adelantado, gancho trasero, uppercut adelantado y uppercut trasero, tal como se enseñan y se gritan en cualquier gimnasio.
- **Cadena cinética y checklist de guardia:** pie → cadera → torso → puño, más los puntos de postura que se revisan en el rincón.

### Fichas técnicas de cada golpe
- **Modo golpe individual:** biomecánica, uso táctico, cómo combina, cómo contrarrestarlo, defensa habitual.
- **Errores en texto:** no solo el nombre del error, sino *cómo se ve* en el gimnasio (hombro que baja, codo que se abre, jab que empuja en vez de latigear).

### Arsenal y defensa
- **Variantes y golpes especiales:** jab doble, jab de cuerpo, push jab, overhand, cross de contra, check hook, gancho al hígado, shovel hook, bolo punch, uppercut en clinch.
- **Seis formas de defensa:** guardia alta, slip, roll / bob and weave, parry, footwork defensivo, clinch — con jerarquía de preferencia (evitar → desviar → bloquear → absorber).
- **Tabla golpe rival → respuesta recomendada → contragolpe habilitado.**

### Táctica y decisión
- **Pilares tácticos:** control de distancia, feints, ring generalship, timing sobre velocidad, contraataque, trabajo de cuerpo, cambios de ritmo, lectura de guardia.
- **Los cuatro rangos:** larga, jab, media, corta/clinch.
- **Fases del combate:** rounds tempranos, medios y finales.

### El cuerpo en el ring
- **Por qué un golpe para o no:** explicación científica de mentón/mandíbula (apalancamiento y cizallamiento), sien, plexo solar (espasmo del diafragma) e hígado (respuesta vagal).
- **Lo que el ring le pide al organismo:** cadena cinética, fatiga y precisión, visión y fijación, equilibrio y base.

### Escuelas, arquetipos y reglas
- **Escuelas regionales:** Philly shoulder roll, Kronk, peek-a-boo; cubana, mexicana, puertorriqueña, británica/europea, soviética/del Este, filipina, japonesa — con referentes y contexto.
- **Cinco arquetipos:** boxer-puncher, swarmer, out-fighter, counter-puncher, slugger.
- **Reglamento:** duración de rounds, sistema 10-point must, qué mira un juez.
- **Amateur vs. profesional:** comparación en dos columnas (ritmo, puntuación, protección, prioridades).
- **Categorías de peso:** límites en **kg y lbs**, metros relativos de alcance/velocidad/potencia y varios exponentes históricos por división.

### Tablas, glosario y estudio
- **Tablas comparativas:** trayectoria, alcance, velocidad, potencia, riesgo, gasto, distancia ideal y **varios exponentes** por golpe base; tabla dedicada a variantes.
- **Glosario del rincón:** southpaw, clinch, TKO, cutman, telegrafiar, ring rust, feint, ring generalship, infighting, y más.
- **Peleas para estudiar:** lista solo texto (Ali–Foreman, Frazier–Ali I, Durán–Leonard I, Hearns–Leonard, Tyson–Spinks, Chávez–Taylor, Mayweather–Hatton, Pacquiao–Barrera, Inoue–Donaire II, Usyk–Joshua II) con *qué mirar* en cada una, sin links externos.

### Interactividad y experiencia
- **Mini perfiles de referentes:** clic en nombres (Ali, Frazier, Tyson, Mayweather, Chávez, Robinson, Hearns, Inoue, Durán, Cus D'Amato, Steward…) abre un panel con contexto de estilo y pelea sugerida.
- **100% responsive** y respeta `prefers-reduced-motion`.
- **CTA a Substack** (*Rincón del Ring*) para análisis y crónica en texto.


## Uso

No requiere instalación ni build. Alcanza con abrir el archivo en un navegador:

```bash
git clone https://github.com/cainramirez-cmd/rincon-del-ring.git
cd rincon-del-ring
open index.html   # o hacé doble clic en el archivo
```

## Estructura

```
rincon-del-ring/
├── index.html   # App completa: HTML + CSS + JS en un solo archivo
├── LICENSE      # Licencia MIT
└── README.md
```


## Tecnologías

- HTML5 + CSS3 (variables CSS, grid, clamp para tipografía fluida, vignette de atmósfera)
- JavaScript vanilla (sin frameworks ni dependencias de build)
- SVG dibujado a mano para el diagrama de trayectorias y zonas de impacto

## Nota

Esta guía es un punto de partida visual, no un reemplazo de la enseñanza presencial. Para corregir la mecánica real de cada golpe (postura, respiración, protección del mentón) entrená siempre frente a un entrenador o en un gimnasio con supervisión. Las explicaciones de zonas de impacto son divulgación anatómica orientada al boxeo, no consejo médico.


## Licencia

Distribuido bajo licencia [MIT](./LICENSE).

---

© 2026 [Caín N. Ramirez](https://github.com/cainramirez-cmd)
