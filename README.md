# Mi taller · Mofumofu Studio

Un taller personal de crochet para computadora, con una base vacía y apariencia personalizable. Sin cuentas, instalaciones ni servicios de pago.

## Funciones

- Una pieza por tarjeta, movible entre Tejiendo, Para decorar y Terminadas. También se puede cambiar la etapa desde el formulario usando el teclado.
- Stock automático por modelo y aguja (1 mm / 2 mm). Vendida y Regalada descuentan disponibilidad y conservan el historial.
- Fotos originales de piezas terminadas en una galería privada del navegador. No se comprimen ni se altera el tejido.
- Patrones con PDF, imágenes, enlaces, notas originales y adaptaciones, vinculables a piezas.
- Cinco colores editables, color de texto, nombre del taller y paletas iniciales.
- Respaldo e importación JSON que incluyen todos los archivos.

## Probar en computadora

Con Node.js instalado, ejecutar `npm start` y abrir http://127.0.0.1:4173. No requiere instalar dependencias. `npm test` ejecuta las comprobaciones del stock y las copias.

## Probar desde GitHub

El proyecto funciona directamente con GitHub Pages: en el repositorio, ir a Settings → Pages → Deploy from a branch → main → / (root). La aplicación estará en `https://USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Datos y privacidad

Los datos y archivos se guardan en IndexedDB, dentro del navegador actual. **No hay sincronización entre dispositivos ni copia en la nube.** GitHub solo aloja la aplicación vacía. Cada visitante tiene su taller independiente. Borrar los datos del navegador elimina el taller: descargá copias periódicas desde Copias de respaldo. Cambiar la dirección de la aplicación o el navegador crea un almacenamiento separado; usá exportación/importación para trasladar tus datos.

Se admiten JPG, PNG, WebP y PDF de hasta 20 MB por archivo. El espacio total depende de la cuota del navegador. Si falla un guardado, la app conserva el estado anterior. Las tipografías se descargan de Google Fonts; sin conexión se usa una fuente local de respaldo.
