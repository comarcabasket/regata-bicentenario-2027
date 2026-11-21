# 51.ª Regata Internacional del Río Negro — Regata del Bicentenario

Versión de publicación del sitio oficial (v12, noviembre de 2026).

## Publicación recomendada: GitHub + Cloudflare Pages

1. Creá un repositorio nuevo (por ejemplo, `regata-bicentenario-2027`).
2. Subí el CONTENIDO de esta carpeta a la raíz del repositorio; `index.html` debe quedar en la raíz. No subas la carpeta contenedora como una subcarpeta.
3. En Cloudflare Dashboard → Workers & Pages → Create application → Pages → Connect to Git.
4. Conectá el repositorio en la rama `main`, usando el preset None / Static HTML. No hay build: dejá vacío el build command, y seleccioná `/` como directorio de salida si el panel lo solicita.
5. Publicá y abrí la URL asignada que termina en `.pages.dev` desde un móvil y una PC. Comprobá imágenes, menú, Reglamento PDF y Multimedia.
6. El dominio propio puede vincularse luego en la pestaña Custom domains del proyecto.

## Pendientes antes de la versión definitiva

- Enlazar la dirección EXTERNA de Inscripciones y del sistema de TIEMPOS. Los botones actualmente mantienen un aviso de enlace pendiente; no efectúan una inscripción ni muestran tiempos reales.
- Descargar y conservar localmente la **fotografía de portada** que fue facilitada como URL de ImgBB. Ahora se referencia al enlace externo y se utiliza una imagen local de respaldo si la URL deja de responder. Es importante no depender de servicios de terceros hasta enero de 2027.
- Validar la redacción de la conmemoración y los datos institucionales con los organizadores.

## Estructura

- `index.html`: sitio web (CSS y JavaScript incluidos)
- `assets/`: logos y 18 fotografías de galería en WebP
- `docs/`: reglamento de 2027

No se requiere pagar hosting ni configurar una base de datos para este contenido estático.
