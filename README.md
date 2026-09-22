# Portafolio_ABA — Ariadna Bravo Arriaga

**Autora:** Ariadna Bravo Arriaga — Diseño Gráfico, Universidad La Salle CDMX

Repositorio del portafolio creativo de Ariadna Bravo. Contiene la identidad visual editorial (rosa, magenta, azul y crema), el sistema de diseño en `DESIGN.md`, la landing one-page del CV (`index.html`) y los assets originales (tipografías Anton + Montserrat, portadas, renders, fotografías y mockups). Todo el sitio es HTML/CSS/JavaScript vanilla, mobile-first, semántico y accesible (contraste AA, foco visible).

## Descripción breve

Este repositorio documenta y publica el portafolio de Ariadna Bravo:
- **Sistema de diseño** definido en `DESIGN.md` (tokens de color, tipografía, espaciado, radios, sombras y componentes) con referencia visual en `design.html`.
- **Landing CV** `index.html` — one-page responsive derivada de `CV.md` (arquitectura de `Arquitectura_CV_Ariadna_Bravo.docx`), con hero, sobre mí, habilidades, software, idiomas, proyectos (6 tarjetas clickeables con galería / libro interactivo para Editorial) y contacto.
- **Contenido** fiel al portafolio: sin empleos ni fechas inventadas, solo formación La Salle y áreas Modelado 3D, Identidad de marca, Branding e Ilustración.
- **Assets** en `ASSETS/` (Anton, Montserrat woff2, `TODOS_LOS_ELEMENTOS/{COMPONENTES,IMAGENES,MODELADO}`) como única fuente de verdad visual.

## Páginas publicadas (GitHub Pages)

- **Landing CV — `index.html`:** https://ariarri2004-svg.github.io/Portafolio_ABA/
- **Sistema de diseño — `design.html`:** https://ariarri2004-svg.github.io/Portafolio_ABA/design.html

> Activa GitHub Pages en el repositorio: `Settings → Pages → Source: main / root` para que ambas URLs queden disponibles.

## Archivos del repositorio

- **Sistema de diseño:** [DESIGN.md](https://github.com/ariarri2004-svg/Portafolio_ABA/blob/main/DESIGN.md) — tokens y guía visual (fuente: `DESIGN_Ariadna_Bravo.docx`)
- **Arquitectura CV (markdown):** [CV.md](https://github.com/ariarri2004-svg/Portafolio_ABA/blob/main/CV.md) — conversión fiel de `Arquitectura_CV_Ariadna_Bravo.docx`

## Documentos PDF

- **Diseño — PDF original:** [DESIGN_Ariadna_Bravo.pdf](https://github.com/ariarri2004-svg/Portafolio_ABA/blob/main/DESIGN_Ariadna_Bravo.pdf)
- **Diseño — DOCX fuente (segundo documento del sistema):** [DESIGN_Ariadna_Bravo.docx](https://github.com/ariarri2004-svg/Portafolio_ABA/blob/main/DESIGN_Ariadna_Bravo.docx) — el repositorio contiene un único PDF de diseño (`DESIGN_Ariadna_Bravo.pdf`); el segundo documento del sistema es el `.docx` fuente. Si se genera un segundo PDF (p. ej. `CV.pdf`), se enlazará aquí.

## Estructura

```
.
├─ index.html          # landing CV (vanilla, mobile-first)
├─ design.html         # referencia visual del DESIGN.md
├─ DESIGN.md           # sistema de diseño (tokens)
├─ CV.md               # arquitectura CV en markdown
├─ DESIGN_Ariadna_Bravo.pdf / .docx
├─ Arquitectura_CV_Ariadna_Bravo.docx
├─ ASSETS/
│  ├─ Anton/ + Montserrat/
│  └─ TODOS_LOS_ELEMENTOS/{COMPONENTES,IMAGENES,MODELADO}
└─ README.md
```

## Desarrollo local

```bash
# clonar y abrir
git clone https://github.com/ariarri2004-svg/Portafolio_ABA.git
# abrir index.html o design.html directamente en el navegador (no requiere build)
```

Tokens CSS derivados 1:1 de `DESIGN.md` en `:root` (`--color-primary #C52F70`, `--color-surface #F8D9E3`, etc.), tipografías locales `.woff2`, y galería/libro interactivo para proyectos sin dependencias.

---
© 2026 Ariadna Bravo Arriaga — Portafolio creativo.
