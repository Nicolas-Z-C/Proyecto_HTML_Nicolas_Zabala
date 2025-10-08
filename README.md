Autor
Nicolas Zabala Castañeda
Descripción
Este proyecto es un sitio web estático para LuxTime, una marca de relojes de lujo. La página principal (index.html) incluye un banner con carrusel de imágenes, un catálogo preliminar de productos con enlaces a páginas detalladas de relojes, una sección de historia de la compañía, hitos clave, misión, visión, valores, logros, testimonios y proyecciones futuras. El diseño es responsivo, adaptándose a diferentes tamaños de pantalla mediante media queries en CSS. El sitio enfatiza la elegancia, la sostenibilidad y la precisión, con transiciones y animaciones para mejorar la experiencia del usuario.
Stack Tecnológico

HTML5: Estructura del sitio web, incluyendo secciones como navegación, banner, catálogo, historia y secciones de visión/misión.
CSS3: Estilos, layouts con grid y flexbox, animaciones (e.g., carrusel), transiciones (e.g., hover effects), media queries para responsividad y tipografía personalizada.
Fuentes: Roboto (variable font con soporte para italic y weights, incluida en assets/fonts).
No se utilizan frameworks o librerías externas; es un sitio puro de HTML y CSS.

Requerimientos

Un navegador web moderno (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge o Safari) con soporte para HTML5 y CSS3.
No se requiere servidor; el sitio es estático y puede abrirse directamente desde el sistema de archivos (e.g., abriendo index.html en el navegador).
Resolución recomendada: Al menos 375px de ancho para vistas móviles, hasta full HD para desktops.
Espacio en disco: Aproximadamente 10-20 MB (debido a las imágenes y fuentes).
No hay dependencias de instalación; solo clona el repositorio y abre los archivos HTML.

Estructura de Archivos
A continuación, se muestra la estructura del proyecto en formato de árbol (basado en las capturas proporcionadas y el código HTML/CSS). El directorio raíz contiene carpetas para assets (recursos como imágenes y fuentes), CSS (estilos), HTML (páginas) y el README.
text.
├── assets
│   ├── fonts
│   │   └── Roboto
│   │       ├── OFL.txt
│   │       ├── README.txt
│   │       ├── Roboto-Italic-VariableFont_wdth,wght.ttf
│   │       └── Roboto-VariableFont_wdth,wght.ttf
│   └── imgs
│       ├── carrusel
│       │   ├── 1.jpg
│       │   ├── 2.jpg
│       │   └── 3.avif
│       ├── fondos
│       │   ├── 1.webp
│       │   ├── 2.webp
│       │   ├── 3.webp
│       │   ├── 4.webp
│       │   ├── 5.webp
│       │   ├── 6.webp
│       │   ├── 7.webp
│       │   ├── 8.webp
│       │   ├── 9.webp
│       │   ├── 10.webp
│       │   ├── 11.webp
│       │   ├── 12.webp
│       │   ├── 13.webp
│       │   ├── 14.webp
│       │   ├── 15.webp
│       │   ├── 16.webp
│       │   ├── 17.webp
│       │   ├── 18.webp
│       │   ├── 19.webp
│       │   └── 20.webp
│       ├── historia
│       │   ├── 1.jpg
│       │   ├── 2.jpg
│       │   ├── 3.jpg
│       │   └── 4.jpg
│       ├── logos
│       │   ├── 1.jpg
│       │   ├── 2.png
│       │   └── lux.svg
│       ├── logros
│       │   ├── 1.jpg
│       │   └── 2.png
│       ├── misc
│       │   ├── 1.jpg
│       │   └── 2.png
│       ├── nosotros
│       │   ├── 1.jfif
│       │   ├── 3.webp
│       │   └── 4.jpg
│       ├── relojes
│       │   ├── 1.webp
│       │   ├── 2.webp
│       │   ├── 3.webp
│       │   ├── 4.webp
│       │   ├── 5.webp
│       │   ├── 6.webp
│       │   ├── 7.webp
│       │   ├── 8.webp
│       │   ├── 9.webp
│       │   ├── 10.webp
│       │   ├── 11.webp
│       │   ├── 12.webp
│       │   ├── 13.webp
│       │   ├── 14.webp
│       │   ├── 15.webp
│       │   ├── 16.webp
│       │   ├── 17.webp
│       │   ├── 18.webp
│       │   ├── 19.webp
│       │   └── 20.webp
│       └── testimonios
│           ├── 1.svg
│           └── 3.svg
├── css
│   ├── catalog.css
│   ├── catalogwatches.css
│   ├── company.css
│   ├── contact.css
│   └── main.css
├── html
│   ├──catalog
│   │   ├── 1.html
│   │   ├── 2.html
│   │   ├── 3.html
│   │   ├── 4.html
│   │   ├── 5.html
│   │   ├── 6.html
│   │   ├── 7.html
│   │   ├── 8.html
│   │   ├── 9.html
│   │   ├── 10.html
│   │   ├── 11.html
│   │   ├── 12.html
│   │   ├── 13.html
│   │   ├── 14.html
│   │   ├── 15.html
│   │   ├── 16.html
│   │   ├── 17.html
│   │   ├── 18.html
│   │   ├── 19.html
│   │   └── 20.html
│   ├── catalog.html
│   ├── company.html
│   ├── contact.html
│   └── index.html
└── README.md
Notas sobre la estructura:

assets/imgs/relojes: Contiene imágenes de 20 relojes (1.webp a 20.webp), referenciadas en el catálogo.
html: Incluye páginas individuales para cada reloj (1.html a 20.html), asumiendo que son detalles de productos. Nota: En el código de index.html, las rutas son "/html/Catalog/1.html", lo que podría indicar un subdirectorio "Catalog" dentro de "html" no visible en las capturas; si es así, ajusta la estructura moviendo 1.html-20.html a html/Catalog/.
El carrusel usa imágenes de assets/imgs/carrusel.
Fuentes Roboto se cargan vía @font-face en main.css.

Instrucciones de Uso

Clona o descarga el repositorio.
Abre html/index.html en tu navegador.
Navega por las secciones: Casa (index), Catálogo, Nosotros y Contacto.
Para ver páginas de relojes individuales, haz clic en los enlaces del catálogo.

Si hay errores en las rutas (e.g., imágenes no cargan), verifica las referencias en el HTML/CSS contra la estructura real.
Contribuciones
Si deseas contribuir, crea un pull request con mejoras en responsividad, accesibilidad o adiciones de funcionalidades (e.g., JavaScript para interacciones avanzadas). Contacta al autor para más detalles.