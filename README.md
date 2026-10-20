# FiestaMundo — calendario de fiestas y celebraciones

Sitio estático hecho con HTML, CSS y JavaScript. No necesita servidor, dependencias ni API.

## Incluye
- Diseño adaptable a móvil, tableta y ordenador.
- Buscador por nombre, descripción, categoría y lugar.
- Filtros por mes, categoría y región.
- Próximas celebraciones y calendario por meses.
- Fichas con descripción, lugar, tradiciones y aviso de fechas variables.
- Botón para descargar un archivo `.ics` e importar una fiesta al calendario personal.
- Compartir/copiar enlace, guías, preguntas frecuentes y metadatos SEO.
- Cálculo de Pascua y fechas derivadas como Carnaval y Semana Santa.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en https://github.com/new.
2. Sube `index.html` y `README.md` a la raíz.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
6. Abre la URL que aparecerá en GitHub Pages.

## Actualizar el calendario
La lista se crea en `buildEvents(y)`, en `index.html`. Las fechas fijas y Semana Santa se calculan por año; las fechas de festivales lunares y algunos eventos oficiales son orientativas y deben verificarse. Añade nuevos eventos siguiendo las llamadas a `event(...)`.

## Nota de precisión
Esta web es una guía de celebraciones conocidas, no un calendario oficial completo de cada municipio. Un evento cultural no implica necesariamente un día festivo laboral. Confirma siempre las fechas con fuentes oficiales antes de organizar viajes o actividades.
