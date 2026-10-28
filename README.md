# Derechos de autor en videojuegos: presentación de la clase

Presentación web para una clase presencial sobre derechos de autor en videojuegos (derecho colombiano y comparado). Es un conjunto de 67 diapositivas: una portada, una lámina de introducción, nueve capítulos y cuatro talleres intercalados donde la clase los alcanza. Cada diapositiva muestra el capítulo al que pertenece. Las normas y sentencias se citan desde sus fuentes oficiales y cada imagen lleva su licencia.

Sitio publicado: https://jorgevillegasres.github.io/games_copyright/

## Archivos

- `index.html`: la presentación completa (HTML, CSS y JavaScript en un solo archivo).
- `assets/img/`: las 25 imágenes usadas. La tabla de créditos del capítulo 9 indica autor, licencia y enlace de cada una.
- `.nojekyll`: indica a GitHub Pages que sirva los archivos tal cual.
- `.claude/launch.json` (no se publica): configuración para servir la carpeta en `http://localhost:8765` durante el desarrollo.

## Cómo se usa

- **Avanzar y retroceder:** flechas del teclado, barra espaciadora, Av Pág / Re Pág, los botones de la esquina inferior derecha o deslizar en pantallas táctiles. Inicio y Fin van a la primera y a la última diapositiva.
- **Índice:** el botón «Índice» (o el menú en móvil) abre la tabla de contenido con todas las diapositivas agrupadas por capítulo; cada entrada salta directamente a su lámina.
- **Enlaces directos:** cada diapositiva tiene su propia dirección, por ejemplo `index.html#c4-2` (capítulo 4, lámina 2) o `index.html#t1-3` (taller 1, lámina 3). Sirven para enviar a los estudiantes a una lámina concreta.
- **Ver todo:** muestra todas las diapositivas seguidas, para leer o estudiar de corrido. Se vuelve al formato de diapositivas con el mismo botón.
- **Notas del docente** (dentro del índice): modo solo para quien dicta la clase. Muestra en la primera lámina de cada capítulo una nota con el tiempo sugerido, el método y la frase de transición; un cronómetro flotante con presets; y los eventos sorpresa del Taller 1. Los estudiantes no ven nada de esto salvo que lo activen.
- **Talleres:** cada equipo trabaja en su propio dispositivo. Lo que escriben (term sheet, acuerdo de mediación, takedown, cláusulas, lista de verificación) se guarda en el navegador de ese dispositivo y se copia con el botón «Copiar» para pegarlo en el formulario de entrega del curso.
- **Encuestas a mano alzada** (capítulos 1 y 4): se registran desde el dispositivo que proyecta, un clic por voto.

## Diseño

- Portada oscura a pantalla completa con movimiento de fondo, tipografía display en mayúsculas (Bebas Neue), texto en Inter, etiquetas con tracking amplio, bordes finos blancos, menú superpuesto y animaciones de entrada. Es un único tema oscuro.
- La tipografía de referencia del concepto era una fuente «demo» sin licencia clara; se sustituyó por Bebas Neue e Inter (SIL Open Font License), servidas por Google Fonts. Los iconos son de Lucide (ISC), incrustados como SVG.
- El fondo de la portada es una animación propia en canvas. El video de referencia mostraba personajes de terceros (Tortugas Ninja, The Witcher) y no se incluyó; en `index.html` hay un comentario que indica cómo poner un video con derechos propios.

## Publicación

El sitio se sirve con GitHub Pages desde la rama `gh-pages`, que contiene lo mismo que `main`. Para publicar un cambio:

```bash
git push origin main && git push -f origin main:gh-pages
```

Si en Settings → Pages se cambia la fuente a `main` / `(root)`, bastará con el push a `main`.

## Notas sobre las fuentes

- Las capturas de normas y sentencias colombianas se amparan en el art. 41 de la Ley 23 de 1982 (libre reproducción de leyes y decisiones judiciales). Las obras del Gobierno de Estados Unidos (USCO, D.C. Circuit) están en dominio público. Los comunicados del TJUE se reproducen con indicación de fuente. Las fotografías provienen de Wikimedia Commons bajo licencias libres. Las capturas de la DNDA y de Nintendo se incluyen como cita con fines docentes.
- El enlace a SC424-2024 del documento original devolvía error al verificarlo; la presentación enlaza al PDF oficial de la Corte Suprema y a la compilación de la CRC, ambos verificados el 28 de octubre de 2026.
- El fotograma «Nebula Run», la cadena de titularidad, el flujo de ingeniería inversa y el esquema de Micro Star son elaboraciones propias para la clase.
