# Derechos de autor en videojuegos: página de la clase

Página web de apoyo para una clase presencial sobre derechos de autor en videojuegos (derecho colombiano y comparado). Está organizada como una presentación del profesor: una portada a pantalla completa, nueve capítulos numerados y cuatro talleres intercalados donde la clase los alcanza. Las normas y sentencias se citan desde sus fuentes oficiales y cada imagen lleva su licencia.

## Archivos

- `index.html`: la página completa (HTML, CSS y JavaScript en un solo archivo).
- `assets/img/`: las 25 imágenes usadas (capturas de normas y sentencias, comunicados oficiales, fotografías con licencia libre). La tabla de créditos del capítulo 9 indica autor, licencia y enlace de cada una.
- `.claude/launch.json`: configuración para servir la carpeta en `http://localhost:8765` durante el desarrollo.

## Cómo usarla

1. Abrir `index.html` en el navegador (doble clic) o servir la carpeta con cualquier servidor estático:

   ```bash
   python -m http.server 8765
   ```

2. El botón **Índice** (o el menú en móvil) abre la tabla de contenido. Al final de cada capítulo hay enlaces al anterior y al siguiente.

3. **Notas del docente** (dentro del índice) activa un modo solo para quien dicta la clase: muestra al inicio de cada capítulo una nota con el tiempo sugerido, el método y la frase de transición, un cronómetro flotante con presets, los eventos sorpresa del Taller 1 y el botón **Proyectar**, que muestra un capítulo a la vez con letra más grande y navegación con las flechas del teclado. Los estudiantes no ven nada de esto salvo que lo activen.

4. Cada equipo trabaja en su propio dispositivo. Lo que escriben en los talleres (term sheet, acuerdo de mediación, takedown, cláusulas, lista de verificación) se guarda en el navegador de ese dispositivo y se copia con el botón «Copiar» para pegarlo en el formulario de entrega del curso.

5. Las encuestas a mano alzada (capítulos 1 y 4) se registran desde el dispositivo que proyecta: un clic por voto.

## Diseño

- Concepto: portada oscura a pantalla completa con movimiento de fondo, tipografía display en mayúsculas (Bebas Neue), texto en Inter, etiquetas con tracking amplio, bordes finos blancos, menú superpuesto y animaciones de entrada. Es un único tema oscuro.
- La tipografía de referencia del concepto era una fuente «demo» sin licencia clara; se sustituyó por Bebas Neue e Inter (SIL Open Font License), servidas por Google Fonts. Los iconos son de Lucide (ISC), incrustados como SVG.
- El fondo de la portada es una animación propia en canvas. El video de referencia mostraba personajes de terceros (Tortugas Ninja, The Witcher) y no se incluyó; en `index.html` hay un comentario que indica cómo poner un video con derechos propios.

## Notas sobre las fuentes

- Las capturas de normas y sentencias colombianas se amparan en el art. 41 de la Ley 23 de 1982 (libre reproducción de leyes y decisiones judiciales). Las obras del Gobierno de Estados Unidos (USCO, D.C. Circuit) están en dominio público. Los comunicados del TJUE se reproducen con indicación de fuente. Las fotografías provienen de Wikimedia Commons bajo licencias libres. Las capturas de la DNDA y de Nintendo se incluyen como cita con fines docentes.
- El enlace a SC424-2024 del documento original devolvía error al verificarlo; la página enlaza al PDF oficial de la Corte Suprema y a la compilación de la CRC, ambos verificados el 28 de octubre de 2026.
- El fotograma «Nebula Run», la cadena de titularidad, el flujo de ingeniería inversa y el esquema de Micro Star son elaboraciones propias para la clase.
