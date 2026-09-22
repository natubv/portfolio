---
version: alpha
name: Natalia Ballesteros
description: Sistema maximalista expresivo en rojo y morado con base editorial Kepler Std + Neulis Neue, reticula 12 columnas y concentraciones controladas de energia grafica.
colors:
  purple-light: "#DC8EFF"
  purple-medium: "#9D50BE"
  purple-deep: "#5D117D"
  red-vibrant: "#FF1E17"
  red-medium: "#BF0F0C"
  red-dark: "#7F0000"
  white: "#FFFFFF"
  blue-accent: "#75B0E3"
  primary: "#5D117D"
  secondary: "#9D50BE"
  tertiary: "#FF1E17"
  neutral: "#FFFFFF"
  error: "#FF1E17"
typography:
  display-kepler:
    fontFamily: Kepler Std
    fontSize: 72px
    fontWeight: 700
    lineHeight: 1.1
  h1-kepler:
    fontFamily: Kepler Std
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1.1
  nav:
    fontFamily: Neulis Neue
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.4
  body:
    fontFamily: Neulis Neue
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: Neulis Neue
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  card-title:
    fontFamily: Neulis Neue
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.4
  card-body:
    fontFamily: Neulis Neue
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.4
  chip:
    fontFamily: Neulis Neue
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.4
  input-text:
    fontFamily: Neulis Neue
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.4
  input-placeholder:
    fontFamily: Neulis Neue
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.4
  input-label:
    fontFamily: Neulis Neue
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.4
  input-helper:
    fontFamily: Neulis Neue
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.4
  skill-front:
    fontFamily: Neulis Neue
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.2
  skill-back-title:
    fontFamily: Neulis Neue
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.3
  skill-back-body:
    fontFamily: Neulis Neue
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
  edu-title:
    fontFamily: Neulis Neue
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.3
  edu-institution:
    fontFamily: Neulis Neue
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.4
  edu-date:
    fontFamily: Neulis Neue
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.4
spacing:
  base: 8px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  2xl: 64px
  3xl: 96px
  card-gap: 24px
  section-h: 48px
  section-v: 96px
  nav-h: 72px
rounded:
  none: 0px
  sm: 16px
  md: 24px
  lg: 32px
  full: 9999px
components:
  button-primary:
    backgroundColor: "{colors.red-vibrant}"
    textColor: "{colors.white}"
    typography: "{typography.nav}"
    rounded: "{rounded.sm}"
    padding: 16px
  button-primary-hover:
    backgroundColor: "{colors.purple-deep}"
    textColor: "{colors.white}"
    typography: "{typography.nav}"
    rounded: "{rounded.sm}"
    padding: 16px
  button-secondary:
    backgroundColor: "{colors.purple-medium}"
    textColor: "{colors.white}"
    typography: "{typography.nav}"
    rounded: "{rounded.sm}"
    padding: 16px
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.purple-deep}"
    typography: "{typography.nav}"
    rounded: "{rounded.sm}"
    padding: 16px
  chip:
    backgroundColor: "{colors.purple-medium}"
    textColor: "{colors.white}"
    typography: "{typography.chip}"
    rounded: "{rounded.full}"
    padding: 16px
  chip-light:
    backgroundColor: "{colors.purple-light}"
    textColor: "{colors.primary}"
    typography: "{typography.chip}"
    rounded: "{rounded.full}"
    padding: 16px
  card:
    backgroundColor: "{colors.purple-medium}"
    textColor: "{colors.white}"
    typography: "{typography.card-body}"
    rounded: "{rounded.md}"
    padding: 24px
  card-purple-light:
    backgroundColor: "{colors.purple-light}"
    textColor: "{colors.primary}"
    typography: "{typography.card-body}"
    rounded: "{rounded.md}"
    padding: 24px
  card-red-dark:
    backgroundColor: "{colors.red-dark}"
    textColor: "{colors.neutral}"
    typography: "{typography.card-body}"
    rounded: "{rounded.md}"
    padding: 24px
  card-red-medium:
    backgroundColor: "{colors.red-medium}"
    textColor: "{colors.neutral}"
    typography: "{typography.card-body}"
    rounded: "{rounded.md}"
    padding: 24px
  input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.purple-deep}"
    typography: "{typography.input-text}"
    rounded: "{rounded.sm}"
    padding: 18px
  input-focus:
    backgroundColor: "{colors.white}"
    textColor: "{colors.purple-deep}"
    typography: "{typography.input-text}"
    rounded: "{rounded.sm}"
    padding: 18px
  input-error:
    backgroundColor: "{colors.white}"
    textColor: "{colors.purple-deep}"
    typography: "{typography.input-text}"
    rounded: "{rounded.sm}"
    padding: 18px
  navbar:
    backgroundColor: transparent
    textColor: "{colors.white}"
    typography: "{typography.nav}"
    height: 72px
    padding: 16px
  hero:
    backgroundColor: "{colors.white}"
    textColor: "{colors.purple-deep}"
    typography: "{typography.body}"
    padding: 48px
  project-card-info:
    backgroundColor: "{colors.white}"
    textColor: "{colors.purple-deep}"
    typography: "{typography.card-body}"
    rounded: "{rounded.md}"
    padding: 24px
  skill-card-red:
    backgroundColor: "{colors.red-vibrant}"
    textColor: "{colors.white}"
    typography: "{typography.skill-back-body}"
    rounded: "{rounded.md}"
    padding: 24px
  skill-card-purple:
    backgroundColor: "{colors.purple-medium}"
    textColor: "{colors.white}"
    typography: "{typography.skill-back-body}"
    rounded: "{rounded.md}"
    padding: 24px
  edu-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.purple-deep}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 24px
  icon:
    backgroundColor: transparent
    textColor: "{colors.red-vibrant}"
    typography: "{typography.body}"
    size: 24px
---

# Natalia Ballesteros

## Overview

Sistema maximalista, expresivo, energetico y dinamico, equilibrado con estructura clara y espacios amplios de descanso visual. El maximalismo son concentraciones controladas de energia grafica, no acumulacion constante. Conviven zonas de alta intensidad con areas limpias para mantener claridad, legibilidad y jerarquia.

Principio general: mucho caracter, no mucho ruido. Composicion asimetrica con diferencias de escala, contraste cromatico, superposicion y formas graficas para generar movimiento. Base editorial (Kepler Std) + elementos expresivos (figuras, color). Resultado creativo y atrevido sin perder orden ni funcionalidad. Referencia de densidad: ~30% intensidad grafica / 70% contenido y respiracion, solo como guia visual, no medida obligatoria.

## Colors

Paleta de dos familias principales que pueden funcionar independientes o complementarse. Trabajar preferentemente con un color dominante, uno secundario y un acento opcional. No usar toda la paleta a la vez.

- **Lila claro ({colors.purple-light}):** superficies secundarias, detalles y contrastes suaves.
- **Morado medio ({colors.purple-medium}):** componentes, formas y jerarquia media. Estado base de bordes de inputs.
- **Morado profundo ({colors.purple-deep}):** mayor peso del morado. Profundidad, estabilidad, jerarquia. Texto sobre fondos claros morados, foco de inputs, enlaces sobre fondos claros.
- **Rojo vibrante ({colors.red-vibrant}):** mayor energia. Enfasis, acciones, alta atencion. Error en formularios, hover de enlaces.
- **Rojo medio ({colors.red-medium}):** variaciones monocromaticas rojas.
- **Rojo oscuro ({colors.red-dark}):** mayor profundidad del rojo. Marcos, peso visual, texto sobre fondos claros rojos.
- **Blanco ({colors.white}):** descanso visual, superficie neutral y contraste frente a la intensidad. Fondo de campos.
- **Azul claro ({colors.blue-accent}):** reservado exclusivamente para determinadas figuras graficas secundarias. Acento inesperado, nunca dominante, nunca funcional, nunca en iconos.

Relaciones monocromaticas obligatorias dentro de un mismo componente: rojo + rojo o morado + morado. Tonos oscuros para estructura y marcos, claros para superficies interiores. Ejemplos: `{colors.red-dark}` -> `{colors.red-medium}` / `{colors.red-vibrant}` ; `{colors.purple-deep}` -> `{colors.purple-medium}` / `{colors.purple-light}`. El azul no sustituye a los principales ni sale de figuras secundarias.

> **REVISAR:** no se definio color exacto de placeholder ni de deshabilitados. Se asume placeholder en `{colors.purple-medium}` de menor contraste y deshabilitados con contraste reducido sobre `{colors.white}`. Confirmar valores.

## Typography

Dos familias, sin agregar una tercera sin justificacion. La variedad se construye con tamano + peso + contraste + espacio.

Cargar asi en HTML (mismo CSS para ambas):

```html
<link rel="stylesheet" href="https://use.typekit.net/guo6nyk.css">
```

- **Kepler Std ({typography.display-kepler} / {typography.h1-kepler}):** titulos y alta jerarquia. Caracter editorial, contraste frente a lo funcional. Permite saltos grandes de escala.
- **Neulis Neue ({typography.body}, {typography.nav}, {typography.chip}, {typography.input-text}):** cuerpo, navegacion, etiquetas, botones, info secundaria y funcional. Equilibra a Kepler con lectura clara y directa.

Jerarquia aplicada: titulos de tarjeta en {typography.card-title}, cuerpo en {typography.card-body} con interlineado 1.4 (movil: 20px / 16px). Navegacion en {typography.nav}. Chips en {typography.chip}. Inputs en {typography.input-text} con placeholder {typography.input-placeholder}, label {typography.input-label} y ayuda {typography.input-helper}. Habilidades frontal {typography.skill-front} (30-36px, se tokeniza a 32px), reverso {typography.skill-back-title} + {typography.skill-back-body}. Educacion {typography.edu-title} + {typography.edu-institution} + {typography.edu-date} + {typography.body-sm}. Enlaces de alta jerarquia que funcionan como titulos pueden usar Kepler Std; navegacion y funcionales siempre Neulis Neue.

> **REVISAR:** Kepler no trae tamanos px en el original. Se propuso display 72px / h1 56px como valor razonable. Ajustar a tu escala editorial real. Skill-front se promedio a 32px dentro del rango 30-36px.

## Layout

Unidad base {spacing.base}. Todo margen, padding y separacion deriva de multiplos: {spacing.xs}, {spacing.sm}, {spacing.md}, {spacing.lg}, {spacing.xl}, {spacing.2xl}, {spacing.3xl}.

Escritorio max-width 1440px, rejilla 12 columnas para composiciones asimetricas sin perder alineacion. La rejilla es control, se permiten desplazamientos y variaciones. El vacio es activo. Zonas con mucho texto llevan menor densidad grafica; transiciones y alta jerarquia admiten mas concentracion.

Hero full-width con contenido max 1440px, padding horizontal {spacing.section-h} y vertical {spacing.3xl} en escritorio. Navbar altura {spacing.nav-h}, fondo transparente o solido de paleta, composicion limpia de baja densidad para compensar zonas expresivas. Tarjetas separadas por {spacing.card-gap} a {spacing.lg}. Padding interno de tarjetas {spacing.md} a {spacing.lg}, separacion titulo-contenido {spacing.xs} a {spacing.sm}. Inputs con padding 14px 18px tokenizado a {spacing.sm} / 18px (ver Components). Labels a {spacing.xs} del campo. Textarea min-height 140px.

Responsivo por recomposicion, no por escalado proporcional: escritorio con expresion completa, superposicion y agrupaciones completas; tableta reduce ~20-30% decoracion y simplifica grupos; movil a estructura vertical con solo decoracion esencial, sin scroll horizontal accidental, sin cubrir informacion, y sin poner informacion critica solo en hover. Areas tactiles minimas 44x44px (controles carousel 48x48px).

> **REVISAR:** breakpoints exactos tablet/movil no definidos. Propuesta razonable: tablet <=1024px, movil <=768px. Confirmar.

## Elevation & Depth

La profundidad se construye con escala, superposicion, contraste, posicion, movimiento y jerarquia. Las sombras son secundarias, no el recurso principal. Tres niveles:

- **Plana:** sin sombra. Superficies estables que no necesitan separarse del fondo.
- **Sutil:** separacion minima para interactivos o superficies que flotan levemente.
- **Media:** mayor separacion para destacados, estados interactivos o elementos por encima de otros.

Superposicion permitida si no rompe legibilidad. Figuras pueden entrar parcial desde bordes o ir detras de componentes. Interactivos prefieren escala, posicion y contraste antes que sombras. Transiciones de tarjetas 300-450ms, nav y links 200-300ms, carousel 350-500ms, flip de habilidades 500-700ms.

> **REVISAR:** valores de sombra (blur/spread/color) no definidos en el original. Se dejan fuera de tokens a proposito para no inventar sistema de sombras. Si quieres sombras tokenizables, definir sm/md aqui.

## Shapes

Tres categorias: figuras primarias, secundarias y contenedores funcionales.

**Figuras primarias - estrellas puntiagudas irregulares.** Mayor identidad, construccion angulosa, asimetrica y explosiva, puntas de longitud y direccion variables, nada perfectamente geometrico. Uso individual, parejas, grupos pequenos, parcial fuera de limites, varias escalas y rotaciones. Menor frecuencia que las secundarias. Colores: `{colors.purple-light}`, `{colors.purple-medium}`, `{colors.purple-deep}`, `{colors.red-vibrant}`, `{colors.red-medium}`, `{colors.red-dark}`. Nunca `{colors.blue-accent}`. Assets individuales: `assets/componentes/figura_ind_1.svg`, `assets/componentes/figura_ind_2.svg`, `assets/componentes/figura_ind_3.svg` (alias `@assets/componentes/figura_ind_*.svg`). Conjunto: `assets/componentes/Figuras_principales.svg` (alias `@assets/componentes/Figuras_principales.svg`).

**Figuras secundarias - ritmo.** Vocabulario: flor redondeada, asterisco 8 brazos, ovalo horizontal, ovalo inclinado, linea ondulada, 3 lineas diagonales. Geometria simple y suave. Mayor frecuencia pero en grupos intencionales de 2 a 5 elementos, distintos tamanos y orientaciones, no distribucion uniforme. Pueden usar toda la paleta incluido `{colors.blue-accent}`. El azul solo vive aqui. Assets: `assets/componentes/sec_1.svg` (flor), `assets/componentes/sec_2.svg` (asterisco), `assets/componentes/sec_3.svg` (ovalo horizontal), `assets/componentes/sec_4.svg` (ovalo inclinado), `assets/componentes/sec_5.svg` (ondulada), `assets/componentes/sec_6.svg` (3 diagonales).

**Contenedores funcionales - recuadros redondeados.** Para texto, imagenes, info o interactivos. Radios: inputs {rounded.sm}, tarjetas {rounded.md}, info de proyecto {rounded.lg}, chips {rounded.full}. Regla marco oscuro -> interior claro, misma familia: `{colors.red-dark}` -> `{colors.red-medium}` / `{colors.red-vibrant}` ; `{colors.purple-deep}` -> `{colors.purple-medium}` / `{colors.purple-light}`. Jamas mezclar familias en un contenedor.

> **REVISAR:** se mapeo sec_1..sec_6 a cada figura por orden probable. Confirmar que sec_1=flor, sec_2=asterisco, etc. Encontrado ademas `assets/componentes/cursor_personalizado.svg` no descrito en el documento; indicar si es parte del sistema o ignorarlo.

## Components

Botones con esquinas redondeadas y superficie solida. Principal en alta intensidad ({components.button-primary} sobre `{colors.red-vibrant}`), secundario baja jerarquia dentro de la misma paleta ({components.button-secondary}). Hover puede cruzar rojo<->morado ({components.button-primary-hover}). Fantasma sin superficie ({components.button-ghost}) con texto/borde/cambio cromatico. Area minima comoda 44x44px con padding interno generoso.

Tarjetas base ({components.card}) en rojo o morado solido, radio {rounded.md}, texto Neulis Neue blanco sobre oscuro y `{colors.purple-deep}` o `{colors.red-dark}` sobre claro segun familia. Titulo {typography.card-title}, cuerpo {typography.card-body}. Hero ({components.hero}) y navbar ({components.navbar}, 72px, Neulis 18px/600) mantienen baja densidad para compensar. Links: `{colors.purple-deep}` en claro / blanco en oscuro, hover a `{colors.red-vibrant}` con shift 2px o subrayado 2px, activo con subrayado 3px, transicion 200-300ms.

Campos ({components.input}): fondo `{colors.white}`, borde 2px `{colors.purple-medium}`, foco a `{colors.purple-deep}` ({components.input-focus}) con halo ~3px `{colors.purple-light}` baja opacidad, error borde `{colors.red-vibrant}` ({components.input-error}) + ayuda {typography.input-helper}, label {typography.input-label} a 8px, textarea min 140px, deshabilitado sin efectos y contraste reducido.

Iconos ({components.icon}) simples, solidos, alto contraste, base 24px (28-32px en jerarquia alta), 44x44px minimo en controles. Colores permitidos: `{colors.red-vibrant}`, `{colors.red-medium}`, `{colors.purple-deep}`, `{colors.purple-medium}`, `{colors.white}` segun fondo. Nunca `{colors.blue-accent}`, nunca degradados ni 3D. Hover cambia rojo<->morado o escala ~1.08 en 200-300ms.

Chips ({components.chip}): pildora {rounded.full}, {typography.chip}, padding 8px 16px, fondos `{colors.purple-light}`, `{colors.purple-medium}`, `{colors.red-vibrant}` o `{colors.red-medium}` con texto de contraste. Mas pequenas que botones/tarjetas, informativas, sin `{colors.blue-accent}`.

Avatar 320x320 escritorio / 260 tableta / 220 movil, marco de color 8-12px en cualquier principal, rotacion ~45deg del contenedor grafico sin deformar ni inclinar el retrato (compensar contenido si hace falta).

Tarjeta proyecto: marco personalizado `assets/componentes/marco.svg` en cualquiera de los 6 principales, imagen con recorte controlado sin deformar, recuadro inferior {rounded.md} a {rounded.lg} ({components.project-card-info}, padding 24px). Marco + recuadro = una unidad. Tren horizontal con gap {spacing.card-gap} a {spacing.lg}, chevrons < > de 40-48px con hit 48x48px, scroll 350-500ms sin autoplay, hover escala 1.12-1.18 en 300-450ms como una sola unidad sin mover a las vecinas.

Tarjeta habilidad `assets/componentes/habiliades_shape.svg` (respetar nombre con typo actual): marco 8px + interior, radio {rounded.md}, 280-320x360-420px. Roja: marco `{colors.red-dark}` o `{colors.red-medium}` + interior `{colors.red-medium}` o `{colors.red-vibrant}` ({components.skill-card-red}). Morada: marco `{colors.purple-deep}` + interior `{colors.purple-medium}` o `{colors.purple-light}` ({components.skill-card-purple}). Frontal solo nombre {typography.skill-front} como tarjeta fisica; reverso titulo {typography.skill-back-title} + desc {typography.skill-back-body}. Flip tipo pasar pagina de libro, eje Y lateral (transform-origin en borde), ~180deg, 500-700ms suave, sin mover vecinas.

Tarjeta educacion/experiencia `assets/componentes/edu_exp.svg`: mismo marco personalizado, familia roja o morada, marco fuerte `{colors.red-dark}` / `{colors.red-medium}` / `{colors.purple-deep}` + interior claro misma familia ({components.edu-card}). Totalmente estatica: sin flip, rotacion, escala, desplazamiento ni 3D. Titulo {typography.edu-title}, institucion {typography.edu-institution}, fecha {typography.edu-date}, descripcion {typography.body-sm} 1.5, padding {spacing.md} a {spacing.lg}. Zona estable del sistema.

> **REVISAR:** boton exacto (hex primario/secundario, padding, radio) no cerrado en original; se propuso primario `{colors.red-vibrant}`, secundario `{colors.purple-medium}`, radio `{rounded.sm}`, padding 16px. Texto de chip sobre `{colors.purple-light}` debe ser `{colors.purple-deep}` por contraste, confirmar. Halo de foco 3px con opacidad exacta por definir (sugerido 40%).

## Do's and Don'ts

Do:

- Manten maximalismo concentrado y controlado, con espacios amplios para equilibrar alta energia.
- Usa estrellas como mayor jerarquia y secundarias para ritmo, en grupos de 2-5 con escalas variadas y composicion asimetrica.
- Manten relaciones monocromaticas por componente: oscuro para estructura/marco, claro para superficie/interior.
- Reserva `{colors.blue-accent}` solo para figuras secundarias.
- Usa esquinas redondeadas en contenedores y genera profundidad con escala, posicion y superposicion.
- Manten legibilidad sobre decoracion y usa movimiento como extension de jerarquia (200-700ms segun componente).

Don't:

- No distribuyas formas aleatoriamente, no llenes todo, no uses una sola escala ni conviertas estrellas en patron repetitivo.
- No uses `{colors.blue-accent}` en funcionales, iconos, chips o botones.
- No mezcles rojo y morado en un componente monocromatico ni introduzcas colores fuera de paleta.
- No uses degradados como recurso principal ni dependas de sombras.
- No dejes que formas tapen lectura, no uses movimiento constante que distraiga ni agregues tipografias nuevas sin justificacion.
- No escales desktop a movil tal cual; recompón a vertical, conserva hits 44x44px y no escondas informacion solo en hover.
