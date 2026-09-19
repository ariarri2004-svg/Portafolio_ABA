---
version: alpha
name: "Ariadna Bravo — Portfolio Creativo"
description: "Identidad juvenil, creativa y editorial — rosa, magenta y azul — para el portafolio de Ariadna Bravo. Adaptado de DESIGN_Ariadna_Bravo.docx."
colors:
  primary: "#C52F70"
  primary-hover: "#A8285E"
  surface: "#F8D9E3"
  surface-cream: "#FFF8EA"
  secondary: "#78B3F3"
  secondary-container: "#DDEBFF"
  neutral-dark: "#3A2940"
  white: "#FFFFFF"
typography:
  display:
    fontFamily: "Anton"
    fontSize: "52px"
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: "-0.02em"
  h1:
    fontFamily: "Anton"
    fontSize: "44px"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  h2:
    fontFamily: "Anton"
    fontSize: "32px"
    fontWeight: 400
    lineHeight: 1.1
  h3:
    fontFamily: "Montserrat"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.2
  subtitle:
    fontFamily: "Montserrat"
    fontSize: "18px"
    fontWeight: 600
    lineHeight: 1.3
  body-lg:
    fontFamily: "Montserrat"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: "Montserrat"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Montserrat"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Montserrat"
    fontSize: "14px"
    fontWeight: 600
    lineHeight: 1.0
    letterSpacing: "0.08em"
  button:
    fontFamily: "Montserrat"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1.0
    letterSpacing: "0.02em"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "32px"
  xl: "48px"
  2xl: "64px"
  gutter: "24px"
  section: "48px"
rounded:
  none: "0px"
  sm: "8px"
  md: "12px"
  lg: "16px"
  xl: "24px"
  pill: "9999px"
  full: "9999px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "{spacing.sm}"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "{spacing.sm}"
  button-secondary:
    backgroundColor: "{colors.surface-cream}"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "{spacing.sm}"
  card:
    backgroundColor: "{colors.surface-cream}"
    textColor: "{colors.neutral-dark}"
    rounded: "{rounded.lg}"
    padding: "{spacing.md}"
  card-alt:
    backgroundColor: "{colors.white}"
    textColor: "{colors.neutral-dark}"
    rounded: "{rounded.lg}"
    padding: "{spacing.md}"
  chip-category:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "{spacing.xs}"
  chip-category-active:
    backgroundColor: "{colors.secondary-container}"
    textColor: "{colors.neutral-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "{spacing.xs}"
  link:
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  photo-frame:
    backgroundColor: "{colors.surface-cream}"
    rounded: "{rounded.xl}"
    padding: "{spacing.xs}"
---

## Overview

Identidad visual creativa, juvenil, expresiva y cercana para el portafolio de Ariadna Bravo — diseñadora gráfica que experimenta combinando recursos visuales para convertir ideas en propuestas claras y atractivas.

La estética es alegre y editorial: composiciones dinámicas, tipografías gruesas, bloques de color, formas orgánicas y contrastes fuertes. No busca rigidez corporativa; busca sentirse personal, actual y con energía. El color ({colors.primary} magenta como protagonista sobre {colors.surface} rosa suave y {colors.surface-cream} crema), la tipografía {typography.display} y las formas lúdicas son protagonistas sin perder legibilidad.

> En una frase: una identidad gráfica femenina, divertida y segura.

TODO: Revisar — valores de `spacing`, `rounded` y `typography.lineHeight` fueron inferidos a partir de rangos del documento original (8–48 px) porque el docx no especificaba radios ni interlineados exactos.

## Colors

La paleta parte del lenguaje visual observado en el portafolio. Todos los valores del front matter son normativos; los nombres descriptivos en prosa mapean a tokens.

- **Rosa suave ({colors.surface} #F8D9E3):** atmósfera principal, fondos amplios y lienzos de página.
- **Magenta ({colors.primary} #C52F70):** color de marca protagonista — nombre, títulos, acentos, botones primarios y elementos destacados. Su variante hover es {colors.primary-hover} (#A8285E) — *TODO: Revisar — tono hover inferido 15% más oscuro*.
- **Crema ({colors.surface-cream} #FFF8EA):** neutral cálido para fondos secundarios, recuadros y contraste con {colors.primary}.
- **Azul claro ({colors.secondary} #78B3F3):** contraste y énfasis — subtítulos, detalles y apoyo interactivo. No debe competir en peso con {colors.primary}.
- **Azul muy claro ({colors.secondary-container} #DDEBFF):** fondos de apoyo y resaltados suaves.
- **Morado oscuro ({colors.neutral-dark} #3A2940):** texto principal de alto contraste sobre {colors.surface} y {colors.surface-cream}. Garantiza AA sobre crema.
- **Blanco ({colors.white} #FFFFFF):** fotografías, texto sobre {colors.primary} y zonas de máximo contraste.

Regla de proporción: {colors.surface} como base atmosférica, {colors.primary} como acción, {colors.secondary} como acento puntual. Evitar usar {colors.primary} y {colors.secondary} con el mismo peso en la misma vista.

## Typography

El sistema tipográfico conserva el carácter fuerte y juvenil del portafolio con solo dos familias — sin serifs — para mantener legibilidad y coherencia.

- **Títulos y nombre:** {typography.display} / {typography.h1} / {typography.h2} en **Anton** (400, condensada y gruesa). Uso en mayúsculas para nombres, categorías y títulos cortos.
- **Subtítulos, botones y categorías:** {typography.subtitle} y {typography.button} / {typography.label} en **Montserrat SemiBold (600)**. Las categorías usan {typography.label} en mayúsculas con `letterSpacing: 0.08em`.
- **Cuerpo:** {typography.body-md} (16px) y {typography.body-lg} (18px) en **Montserrat Regular (400)**. {typography.body-sm} (14px) para notas. Evitar serifs en la jerarquía principal.
- **Escala fluida — TODO: Revisar — valores exactos inferidos dentro de los rangos del documento:**
  - Display / título principal: 36–52px → token `display` 52px / `h1` 44px
  - Encabezados: 22–32px → `h2` 32px / `h3` 24px
  - Subtítulos: 16–20px → `subtitle` 18px
  - Cuerpo: 14–18px → `body-sm` 14px / `body-md` 16px / `body-lg` 18px
- Jerarquía por tamaño, peso, color ({colors.primary} vs {colors.neutral-dark} vs {colors.secondary}) y composición, no solo por familia.

Todas las familias deben cargarse como `Anton Regular` y `Montserrat` (400/600) en `.woff2` — ya convertidas en `ASSETS/Anton` y `ASSETS/Montserrat/static`.

## Layout

Composiciones que generan **equilibrio, movimiento y dinamismo** mediante tamaño, posición y proporción para crear jerarquía y dirigir la atención.

- **Retícula guía no visible:** se usa 12 columnas fluidas con `gutter` {spacing.gutter} y márgenes laterales {spacing.md}–{spacing.lg} como herramienta de construcción, nunca como elemento gráfico final.
- **Espacio en blanco estructural:** separa elementos, evita saturación y da protagonismo a imágenes y títulos. Las secciones principales usan al menos {spacing.section} (48px) entre sí — *TODO: Revisar — valor inferido*.
- **Formas inclinadas:** bloques de color, círculos y óvalos pueden romper la retícula con intención, manteniendo estructura legible. El flujo debe ser fácil de recorrer en Z o en columna.
- **Escala de espaciado 8px:** {spacing.xs} 8px, {spacing.sm} 16px, {spacing.md} 24px, {spacing.lg} 32px, {spacing.xl} 48px. Adaptar según importancia; nunca usar valores intermedios arbitrarios.
- **Responsivo:**
  - Móvil: 1 columna, márgenes 16–24px ({spacing.sm}–{spacing.md}), secciones apiladas verticalmente, fotografías grandes, títulos breves, área táctil mínima 44×44 px.
  - Tableta: 2 columnas cuando el contenido lo permita; bloques de color como separadores.
  - Escritorio: retícula flexible 2–4 columnas, composición abierta con fotografías, categorías y proyectos distribuidos.
  - Medios fluidos: imágenes se adaptan al ancho sin perder recorte.

## Elevation & Depth

Profundidad visual **ligera y gráfica**, no realista. La jerarquía se logra primero por contraste de color ({colors.surface} vs {colors.primary} vs {colors.surface-cream} vs {colors.secondary}) y superposición; la sombra es solo un apoyo sutil.

- **Sombras suaves y difusas:** solo para separar capas — fotografías, botones `{components.button-primary}` y tarjetas `{components.card}` — del fondo. *TODO: Revisar — valores de sombra inferidos porque el documento no especifica blur/spread:* usar `0 4px 12px rgba(58,41,64,0.08)` para tarjetas y `0 2px 8px rgba(58,41,64,0.10)` para botones; evitar sombras duras o efectos 3D.
- **Sin elevación pesada:** no usar sombras fuertes, biseles ni brillos que alejen la identidad de su carácter editorial.
- **Orden de capas:** fondo {colors.surface} → contenedor {colors.surface-cream}/{colors.white} con sombra ligera → elemento protagonista en {colors.primary}.

## Shapes

El lenguaje de formas combina geometría y organicidad en contraste con la tipografía gruesa. Sensación suave y lúdica.

- **Óvalos y círculos** para fotografías, proyectos destacados o retratos — token {rounded.full} / {rounded.xl} según proporción; funcionan como marcos con borde {colors.surface-cream} o {colors.primary}.
- **Bloques inclinados / diagonales** para generar dinamismo y separar secciones.
- **Formas orgánicas** como recurso decorativo puntual, sin competir con el contenido.
- **Píldoras** para botones y etiquetas — {rounded.pill} (`9999px`) obligatorio en `{components.button-primary}`, `{components.button-secondary}` y `{components.chip-category}`.
- **Radios del sistema — *TODO: Revisar — radios inferidos*:**
  - `sm` {rounded.sm} 8px — detalles pequeños
  - `md` {rounded.md} 12px — inputs
  - `lg` {rounded.lg} 16px — tarjetas `{components.card}`
  - `xl` {rounded.xl} 24px — marcos de foto ovalados
  - `pill`/`full` {rounded.pill} 9999px — botones y chips
- Evitar decoraciones excesivas; no todos los componentes necesitan el mismo radio.

## Components

Todos los componentes referencian tokens del front matter; no usar colores literales en código.

**Botones**
- Primario `{components.button-primary}`: fondo {colors.primary} (#C52F70), texto {colors.white}, tipografía {typography.button} (Montserrat 600), forma {rounded.pill} tipo píldora, padding {spacing.sm}. Puede llevar pequeño detalle en {colors.secondary}. Hover `{components.button-primary-hover}` invierte protagonismo hacia {colors.primary-hover} más oscuro.
- Secundario `{components.button-secondary}`: fondo {colors.surface-cream}, texto {colors.primary}, borde 1px en {colors.primary}, misma tipografía y radio. Apariencia sencilla y gráfica.

**Tarjetas y contenedores**
- `{components.card}` en {colors.surface-cream} o `{components.card-alt}` en {colors.white}, bordes discretos, esquinas {rounded.lg}, padding {spacing.md}. Priorizar imagen protagonista y título breve; evitar bloques largos de texto. Usar sombra ligera de Elevation & Depth.

**Fotografías**
- Protagonistas. Recortes rectangulares, circulares u ovalados con radio {rounded.xl}–{rounded.full}. Se permite marco en {colors.surface-cream} o {colors.primary} para integrar con la identidad.

**Navegación y enlaces**
- Enlaces principales cortos y claros. `{components.link}` en {colors.primary} como acción; {colors.secondary} como apoyo. Estados activos con subrayado, cambio a {colors.primary-hover} o pequeño elemento gráfico — nunca solo por color.

**Categorías y etiquetas**
- `{components.chip-category}`: mayúsculas, {typography.label} (Montserrat 600, tracking 0.08em), fondo {colors.primary}, texto {colors.white}, {rounded.pill}. Selección activa `{components.chip-category-active}` en {colors.secondary-container} con texto {colors.neutral-dark}. Ejemplos: MODELADO 3D, IDENTIDAD DE MARCA, BRANDING, ILUSTRACIÓN.

## Do's and Don'ts

**Do — Sí hacer**
- Usar {colors.surface} rosa como atmósfera y {colors.primary} magenta como protagonista único por vista.
- Usar {colors.secondary} azul solo para contraste y destaque puntual.
- Combinar tipografía gruesa {typography.display} (Anton) con cuerpo legible {typography.body-md} (Montserrat Regular).
- Dar protagonismo a fotografías y proyectos; mantener espacio libre con {spacing.xl} y {spacing.section}.
- Usar composiciones dinámicas, inclinaciones y formas orgánicas con intención y retícula invisible.
- Conservar estética creativa, juvenil y personal, con suficiente aire alrededor de cada elemento.
- Respetar {rounded.pill} en botones y chips; mantener sombras suaves de Elevation & Depth.

**Don't — No hacer**
- No saturar una composición con todos los colores ({colors.primary}, {colors.secondary}, {colors.surface}, {colors.surface-cream}) a igual peso; uno debe dominar.
- No usar {colors.secondary} y {colors.primary} con la misma jerarquía en todos los elementos.
- No sacrificar legibilidad por experimentación excesiva; mantener contraste AA ({colors.neutral-dark} sobre {colors.surface-cream} ≥ 7:1).
- No usar sombras fuertes, efectos 3D o biseles.
- No introducir tipografías decorativas o serifs en la jerarquía principal; limitarse a Anton + Montserrat.
- No rellenar espacios solo para evitar vacío; el blanco es parte del diseño.
- No volver la identidad excesivamente corporativa o rígida.
