# Portfolio de Rafael Lanti Garrocho

Web estática en HTML y CSS, con una paleta clara y diseño adaptable. Todas las páginas comparten `css/styles.css`.

## Estructura
- `index.html`: portada y resumen.
- `sobre-mi.html`: biografía y formación.
- `habilidades.html`: redes informáticas, desarrollo web, sistemas y competencias.
- `proyectos.html`: experiencias prácticas.
- `proceso.html`: metodología de trabajo.
- `contacto.html`: correo y perfiles sociales.
- `css/styles.css`: estilos compartidos.

## Antes de publicar
1. En `contacto.html`, cambia `TU_CORREO@ejemplo.com` por tu correo.
2. Cambia los enlaces `href="#"` de LinkedIn e Instagram por las URL reales.
3. Añade enlaces a tus webs reales y, si tienes permiso, capturas de los proyectos.
4. Revisa que los datos y las cifras reflejen tu experiencia. El incremento de visitas del club deportivo es un proyecto de comunicación digital, separado de tus conocimientos de redes informáticas.

## GitHub Pages
1. Crea un repositorio en GitHub.
2. Sube los archivos a la raíz del repositorio, dejando `index.html` en la raíz.
3. Ve a Settings → Pages.
4. Selecciona Deploy from a branch, rama `main` y carpeta `/ (root)`.
5. Guarda y espera a que GitHub Pages publique la web.

No necesita JavaScript ni compilación. Las fuentes se cargan desde Google Fonts; si no hay conexión, se usan fuentes alternativas del sistema.

\n## Añadir tu fotografía en la página de inicio\n\n1. Guarda tu foto en la carpeta `images` con el nombre `mi-foto.jpg`.\n2. La etiqueta `<img>` ya está añadida en `index.html`; no necesitas tocarla si usas ese nombre.\n3. Si tu imagen tiene otro nombre o formato, cambia el valor de `src` en esa etiqueta.\n\nLa foto se muestra en un marco vertical, con esquinas redondeadas y `object-fit: cover` para mantener sus proporciones.\n\n## Editar los estilos\n\n- `css/styles.css`: estilos generales compartidos por todo el portfolio y el diseño de la fotografía.\n- `css/paginas/index.css`, `sobre-mi.css`, `habilidades.css`, `proyectos.css`, `proceso.css` y `contacto.css`: archivos separados para añadir ajustes exclusivos de cada página.\n