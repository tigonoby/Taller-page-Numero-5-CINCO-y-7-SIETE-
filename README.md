# Taller página número 5 (CINCO) y 7 (SIETE)

Recreación de una página web de servicios de marketing hecha con **HTML y CSS puros** (sin JavaScript ni frameworks), como ejercicio de maquetación: barra de navegación, tarjetas de servicios y sección de testimonios.

## Qué contiene la página

- **Barra de navegación** (`navbar`): logo, enlaces (Home, About, Services, Blog, Pages, Contact), menú desplegable en "Pages" que aparece al pasar el cursor (`:hover`) y botón "Free Consultation" con degradado.
- **Sección de servicios**: cuadrícula con `display: grid` y `repeat(auto-fit, minmax(200px, 1fr))` que contiene una tarjeta destacada ("We Will Help Your Business Growing") y tres tarjetas blancas (Social Marketing y dos de Business Ideas) con ícono, título y descripción.
- **Testimonios**: bloque con título, descripción y una tarjeta de testimonio con sombra, autor y foto circular, maquetado con Flexbox.

## Estructura

```
index.html   Estructura de la página
style.css    Estilos (Flexbox, Grid, degradados, menú desplegable)
```

## Cómo verlo

No requiere instalación ni servidor:

```bash
git clone https://github.com/tigonoby/Taller-page-Numero-5-CINCO-y-7-SIETE-.git
cd Taller-page-Numero-5-CINCO-y-7-SIETE-
```

Abre `index.html` en el navegador (doble clic o arrastrándolo a una ventana). Se necesita conexión a internet porque los logos e íconos se cargan desde URLs externas.

## Observaciones

- Las imágenes (logo, íconos y foto) están enlazadas desde sitios externos; si esas URL cambian o dejan de estar disponibles, no se mostrarán. Para un uso estable conviene descargarlas dentro del repositorio.
- No hay reglas `@media`; la adaptación a pantallas pequeñas depende solo de la cuadrícula `auto-fit` y del `meta viewport`.
- En `index.html`, la tarjeta `testimonial-card` se abre con un `<div>` pero se cierra con `</footer>`; es un detalle de marcado por corregir.
- Los enlaces del menú apuntan a `#` (es una maqueta sin navegación real).

## Tecnologías

HTML5 y CSS3.
