---
version: alpha
name: "Marca maximalista — Rojo vibrante / Morado profundo"
description: "Sistema enérgico, atrevido y elegante en rojos y lilas, con Kepler Std para títulos y Neulis Neue para texto. Alto contraste, ornamentación puntual y claridad funcional."
colors:
  primary: "#FF1E17"
  primary-intense: "#BF0F0C"
  primary-deep: "#7F0000"
  secondary-bright: "#DC8EFF"
  secondary: "#9D50BE"
  secondary-deep: "#5D117D"
  neutral: "#FFFFFF"
  surface: "{colors.neutral}"
  on-surface: "{colors.secondary-deep}"
  error: "{colors.primary-deep}"
typography:
  display:
    fontFamily: "Kepler Std"
    fontSize: "48px"
    fontWeight: 900
    lineHeight: 1.1
  headline-lg:
    fontFamily: "Kepler Std"
    fontSize: "38px"
    fontWeight: 700
    lineHeight: 1.15
  headline-md:
    fontFamily: "Kepler Std"
    fontSize: "30px"
    fontWeight: 600
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Neulis Neue"
    fontSize: "22px"
    fontWeight: 500
    lineHeight: 1.3
  body-lg:
    fontFamily: "Neulis Neue"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.5
  body-md:
    fontFamily: "Neulis Neue"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.45
  label-lg:
    fontFamily: "Neulis Neue"
    fontSize: "18px"
    fontWeight: 500
    lineHeight: 1.4
  label-md:
    fontFamily: "Neulis Neue"
    fontSize: "16px"
    fontWeight: 500
    lineHeight: 1.4
  caption:
    fontFamily: "Neulis Neue"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  full: "9999px"
spacing:
  base: "8px"
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "32px"
  xl: "48px"
  2xl: "64px"
  3xl: "96px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  button-primary-hover:
    backgroundColor: "{colors.secondary-deep}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  button-primary-active:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  button-secondary-hover:
    backgroundColor: "{colors.primary-intense}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  button-ghost:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary-deep}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  chip-default:
    backgroundColor: "{colors.secondary-bright}"
    textColor: "{colors.secondary-deep}"
    typography: "{typography.label-md}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
  chip-strong:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
  badge-alert:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "{spacing.xs}"
  badge-secondary:
    backgroundColor: "{colors.primary-intense}"
    textColor: "{colors.neutral}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: "{spacing.xs}"
  input-default:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  input-error:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.error}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
  link-default:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary-deep}"
    typography: "{typography.body-md}"
  link-hover:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  card-text:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: "{spacing.md}"
---

# Sistema de diseño de marca

## Overview

Estética enérgica, atrevida y elegante, apoyada en rojos vibrantes y lilas con un tono oscuro para dar seguridad. Transmite seguridad, dinamismo y creatividad.

Identidad maximalista pero legible: layouts llamativos con blanco estratégico para dar aire sin vaciar la composición, y tipografía con propósito. Pensada para creadores y desarrolladores; respeta el tiempo y la carga cognitiva.

En una frase: acento audaz sin abrumar, alto contraste y componentes con ornamentación que complementan, dan personalidad y llaman la atención.

La jerarquía de color general es: `{colors.primary}` acción principal, `{colors.primary-intense}` acción secundaria / hover, `{colors.primary-deep}` estados profundos o activos, `{colors.secondary-bright}` fondos y acentos suaves, `{colors.secondary}` componentes secundarios, `{colors.secondary-deep}` jerarquía, contraste y hover principal, `{colors.neutral}` base, descanso y contraste.

> **[REVISAR] Nombre del sistema:** usé "Marca maximalista — Rojo vibrante / Morado profundo" porque tu documento no indica nombre de marca. Cámbialo en `name` si quieres.

## Colors

La paleta vive del contraste entre rojos intensos y lilas. Los claros dan dinamismo y frescura; los oscuros dan estabilidad y profundidad. El blanco es la pausa para que no se vuelva pesado.

- **Lila brillante ({colors.secondary-bright} #DC8EFF):** apoyo y fondo en bloques destacados. Energía y ligereza sin competir con los principales.
- **Lila medio ({colors.secondary} #9D50BE):** secciones secundarias, fondos y gráficos. Da continuidad entre claros y oscuros.
- **Morado profundo ({colors.secondary-deep} #5D117D):** contraste, seguridad y elegancia. Títulos, bloques importantes, fondos de alto impacto y mayor jerarquía.
- **Rojo vibrante ({colors.primary} #FF1E17):** principal color de acción. Llamadas de atención, botones, acentos, ilustraciones y respuesta inmediata.
- **Rojo intenso ({colors.primary-intense} #BF0F0C):** variante contenida del rojo. Profundidad, contraste y énfasis gráfico.
- **Rojo oscuro ({colors.primary-deep} #7F0000):** el más sobrio. Detalles, sombras, estados profundos, fuerza sin protagonismo.
- **Blanco ({colors.neutral} #FFFFFF):** base neutral y descanso. Textos sobre fondos oscuros, áreas de lectura y equilibrio del maximalismo.
- **Superficie ({colors.surface}):** referencia a `{colors.neutral}`. Fondo base de tarjetas, campos y enlaces.
- **Sobre superficie ({colors.on-surface}):** referencia a `{colors.secondary-deep}`. Texto principal sobre fondos claros.
- **Error ({colors.error}):** referencia a `{colors.primary-deep}`. Estados de error.

## Typography

Dos familias con roles complementarios. Kepler Std da el carácter expresivo, editorial y elegante. Neulis Neue mantiene lectura clara, contemporánea y funcional en textos largos.

Para usarlas en web, añade en tu HTML:

```html
<link rel="stylesheet" href="https://use.typekit.net/guo6nyk.css">
```

Ese mismo enlace sirve para Kepler Std y para Neulis Neue.

- **Kepler Std:** principal para títulos, frases destacadas y mayor jerarquía.
- **Kepler Std Display / Subhead:** títulos grandes y encabezados, en Semibold, Bold y Black para énfasis sin depender solo del tamaño.
- **Kepler Std Italic:** recurso expresivo puntual para palabras clave, citas o acentos editoriales.
- **Neulis Neue:** cuerpo y navegación. Limpia y geométrica, equilibra a Kepler.
- **Neulis Neue Medium:** subtítulos, botones, etiquetas e interactivos con más presencia.

Jerarquía (tamaño, peso y contraste, no solo tamaño):

- **Display:** `{typography.display}` Kepler Std Black/Bold Display 40–48px.
- **Título 1:** `{typography.headline-lg}` Kepler Std Bold 36–40px.
- **Título 2:** `{typography.headline-md}` Kepler Std Semibold 28–32px.
- **Título 3 / subsección:** `{typography.headline-sm}` Neulis Neue Medium 20–24px.
- **Cuerpo:** `{typography.body-lg}` / `{typography.body-md}` Neulis Neue Regular 18–20px, interlineado 1.4–1.5.
- **Botones y etiquetas:** `{typography.label-lg}` / `{typography.label-md}` Neulis Neue Medium 16–18px.
- **Pequeño / captions:** `{typography.caption}` Neulis Neue Regular 14–16px.

> **[REVISAR] Valores únicos elegidos de tus rangos:** usé display 48px, headline-lg 38px, headline-md 30px, headline-sm 22px, body 20/18px. Ajusta en `typography` si quieres otro punto del rango.
> **[REVISAR] Pesos numéricos propuestos:** Black=900, Bold=700, Semibold=600, Medium=500, Regular=400. Tu documento solo daba nombres. Confirma que coinciden con tus archivos de Typekit.
> **[REVISAR] Interlineados propuestos para títulos:** 1.1 / 1.15 / 1.2 / 1.3. Solo diste interlineado de cuerpo (1.4–1.5). Revisa si quieres más aire.

## Layout

Estructura flexible para composiciones dinámicas sin perder claridad. Aunque hay decoración intensa, cada sección mantiene jerarquía clara y fácil de recorrer.

- **Unidad base `{spacing.base}`:** 8px. Escala principal `{spacing.xs}` 8, `{spacing.sm}` 16, `{spacing.md}` 24, `{spacing.lg}` 32, `{spacing.xl}` 48, `{spacing.2xl}` 64 y `{spacing.3xl}` 96px.
- **Interno:** botones y pequeños 12–16px; tarjetas y bloques 16–32px según jerarquía. En tokens uso `{spacing.sm}` 16px y `{spacing.md}` 24px como base.
- **Entre secciones:** 64–96px vertical (`{spacing.2xl}` a `{spacing.3xl}`) para pausas visuales.
- **Retícula:** 12 columnas en escritorio para módulos asimétricos, superposiciones y composiciones editoriales sin perder alineación.
- **Ancho máximo:** aprox. 1440px centrado; el extra es margen, no se estiran textos.
- **Blanco estratégico:** no grandes vacíos, sino separaciones que destacan lo importante y equilibran lo ornamentado.
- **Responsive:** móvil 320–599px 1 columna, márgenes 16px, secciones 32–48px; tableta 600–1023px 2–3 columnas, márgenes 32–48px, secciones 48–64px; escritorio 1024–1439px 12 columnas, márgenes 48–64px, secciones 64–96px; amplio 1440px+ contenido centrado 1440px. Interactivos mínimo 44×44px. En móvil la navegación se compacta y botones/enlaces/campos crecen en área táctil. Títulos Kepler reducen escala; cuerpo Neulis se mantiene 16–20px.

Se pueden combinar bloques de distintos tamaños, imágenes, ilustraciones, formas y superpuestos, siempre con alineación clara. Enérgico y espontáneo, nunca desordenado.

## Elevation & Depth

Base mayormente plana. Profundidad con sombras suaves, superposiciones y cambios de escala, tamaño, contraste, color y desplazamiento. No es realismo, es dimensión gráfica y editorial.

- **Nivel plano:** tarjetas y bloques en reposo sin sombra, solo color y contraste.
- **Sutil (hover / interactivo):** aprox. `0 2px 6px` con baja opacidad para indicar activación.
- **Media (destacadas, menús flotantes, superpuestos):** aprox. `0 6px 16px`, bordes definidos.
- **Alta (prioritarios, emergentes):** aprox. `0 10px 28px`, sin exagerar.
- **Superposición:** montar gráficos para reforzar lo maximalista, sin tapar lectura.
- **Capas oscuras:** fondo oscurecido 40–50% en modales y foco para concentrar atención.

> **[REVISAR] Color y opacidad de sombras propuestos:** tu documento solo da desplazamientos. Si el validador te pide color, usa `rgba(93,17,125,0.12)` para sutil, `rgba(93,17,125,0.16)` para media y `rgba(127,0,0,0.20)` para alta. Confirma si prefieres negro puro.

## Shapes

Recursos orgánicos, abstractos y fluidos para movimiento y contraste frente a la intensidad cromática. No representan figuras concretas; son acentos que suavizan y equilibran.

- **Orgánicas:** siluetas libres, curvas amplias e irregulares: fluidez y espontaneidad.
- **Abstractas:** manchas, ondas o trazos que acompañan sin ser protagonistas. Uso puntual en focos decorativos.
- **Rectángulo de esquinas ampliamente redondeadas:** forma funcional principal para contenedores de texto, botones, etiquetas y bloques. Da suavidad y estabilidad. Usa `{rounded.md}` en botones e inputs, `{rounded.xl}` en bloques de texto y `{rounded.full}` en chips/badges.
- **Contraste de formas:** el rectángulo ordena frente a marcos ornamentales y asimetrías; lo redondeado evita rigidez.
- **Contraste visual:** suavizan el alto contraste rojo/lila/blanco.
- **Composición:** libres acompañan o se superponen a imágenes; redondeados contienen información o interacción. En móvil se simplifican, recortan o eliminan.

> **[REVISAR] Radios propuestos:** `sm` 8px, `md` 16px, `lg` 24px, `xl` 32px, `full` 9999px. Tu documento dice "ampliamente redondeadas" sin número. Ajusta en `rounded` a tu gusto.

## Components

Lógica de alto contraste, claridad funcional y acentos expresivos. La interacción se refuerza cambiando entre familia roja y morada.

### Botones

- **Principal `button-primary`:** fondo `{colors.primary}` #FF1E17, texto `{colors.neutral}`, `{typography.label-md}` Neulis Neue Medium.
- **Hover `button-primary-hover`:** cambia a `{colors.secondary-deep}` #5D117D.
- **Pressed / activo `button-primary-active`:** `{colors.primary-deep}` #7F0000 o `{colors.secondary-deep}`, con ligera reducción de escala.
- **Secundario `button-secondary`:** fondo `{colors.secondary}` #9D50BE, texto blanco.
- **Hover secundario `button-secondary-hover`:** `{colors.primary-intense}` #BF0F0C o `{colors.primary}`.
- **Fantasma `button-ghost`:** sin fondo, texto `{colors.secondary-deep}` o `{colors.primary-intense}`. En hover cambia a la familia opuesta y puede subrayarse.
- **Cursor personalizado estrella:** archivo `@assets/Componentes/cursor_personalizado.svg`. Cursor dinámico que cambia de color según fondo para mantener contraste. Sobre claros/blancos/lilas claros usa el mayor contraste entre `{colors.primary}` y `{colors.secondary-deep}`. Sobre botón rojo → `{colors.secondary-deep}`; sobre botón morado → `{colors.primary}`. Cambio inmediato en hover, misma forma/tamaño/posición. Nunca uses el mismo color dominante del elemento.

> **[REVISAR] Tamaño de cursor propuesto:** 32px (tu documento no da tamaño). Si quieres otro, dímelo y lo fijo en guía.

### Etiquetas, chips y badges

- **`chip-default`:** fondo `{colors.secondary-bright}` #DC8EFF, texto `{colors.secondary-deep}`.
- **`chip-strong`:** fondo `{colors.secondary}` con texto blanco para mayor énfasis.
- **`badge-alert`:** `{colors.primary}` para alerta/destacados.
- **`badge-secondary`:** `{colors.primary-intense}` para secundarios.

### Tarjetas y contenedores

Tarjeta de proyecto = marco gráfico personalizado que contiene solo la imagen, sin tarjeta rectangular extra. Silueta ornamental con entradas curvas laterales según `@assets/Componentes/marco.svg`. Es el elemento visual principal.

**Color del marco:** según imagen, buscando mayor contraste sin romper paleta: `{colors.primary}` #FF1E17, `{colors.primary-intense}` #BF0F0C, `{colors.primary-deep}` #7F0000, `{colors.secondary-bright}` #DC8EFF, `{colors.secondary}` #9D50BE, `{colors.secondary-deep}` #5D117D. Si foto oscura/rojiza/cálida → rojo brillante o lila claro; si clara/rosada/lila → morado profundo o rojo oscuro. Evita marco cercano al color dominante. Prioridad: contraste imagen-marco, no repetir siempre el mismo.

**Texto descriptivo `card-text`:** bloque independiente en rectángulo horizontal de esquinas ampliamente redondeadas (`{rounded.xl}`), debajo o próximo al marco. Zona de lectura estable frente a la forma expresiva. Usa `{spacing.md}` de acolchado.

### Campos y formularios

Fondo `{colors.neutral}`, estructura sencilla. `input-default` texto `{colors.on-surface}`. Focus principal borde `{colors.secondary-deep}`; focus énfasis borde `{colors.primary}`; error `input-error` texto/borde `{colors.error}` / `{colors.primary-intense}`; auxiliares o fondos secundarios `{colors.secondary-bright}`.

### Navegación y enlaces

`link-default` base `{colors.secondary-deep}`. En hover `link-hover` cambia a `{colors.primary}` y puede subrayarse. Activo `{colors.primary-intense}` o `{colors.secondary}` según sección.

### Íconos

Base `{colors.secondary-deep}` o `{colors.primary}`. En interactivos se invierte: rojo #FF1E17 → morado #5D117D, o morado #9D50BE → rojo #BF0F0C. Hace la interacción reconocible y une las dos familias.

## Do's and Don'ts

Sí:

- Usa `{colors.primary}` y `{colors.secondary-deep}` como principales de acción y contraste.
- Mantén el cambio rojo ↔ morado en hover e interacción.
- Usa Kepler Std para títulos y alta jerarquía.
- Usa Neulis Neue para cuerpo, navegación, botones y funcionales.
- Mantén jerarquía clara con tamaño, peso, color y espaciado.
- Retícula consistente y espacios amplios para equilibrar el maximalismo.
- Formas orgánicas, abstractas y fluidas como acentos puntuales.
- Blanco `{colors.neutral}` como descanso y contraste.
- Sombras sutiles solo cuando comuniquen profundidad o interacción.
- Permite superposiciones y asimetrías si la lectura sigue clara.
- Botones con suficiente área y contraste.
- Lilas `{colors.secondary-bright}` y `{colors.secondary}` para fondos, etiquetas y secundarios.

No:

- No uses rojo y morado con igual intensidad en todo; siempre con jerarquía.
- No llenes todo de formas orgánicas o decoración.
- No uses abstractas como fondo constante tras textos largos.
- No conviertas maximalismo en saturación; evita muchos altos contrastes juntos.
- No uses Kepler Std para párrafos largos o navegación.
- No mezcles demasiados pesos en una misma sección.
- No bajes cuerpo de 16px.
- No comuniques estado solo con color; añade peso, borde, subrayado o escala.
- No sombras profundas ni 3D realista.
- No abuses de redondeadas en todo; úsalas con intención.
- No pongas texto sobre combinaciones poco legibles.
- No dejes que lo ornamental tape botones, navegación o contenido.
- No agregues colores fuera de paleta sin función.
- No dejes que la decoración mande sobre el contenido.
