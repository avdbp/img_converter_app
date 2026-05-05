# img_converter_app

Convertidor de imágenes en el navegador: WebP, PNG o JPG, con calidad ajustable, renombrado, redimensionado y descarga individual o en ZIP.

Abre `index.html`: interfaz en **español** por defecto. Usa los botones **ES | EN** arriba a la derecha para cambiar **todo** el texto de la página (estadísticas, calidad, descarga ZIP, título del navegador, etc.). La URL puede llevar `?lang=en` o `?lang=es` para compartir en ese idioma. El archivo `index-en.html` solo redirige a `index.html?lang=en` por compatibilidad con enlaces antiguos.

## Uso

1. Arrastra imágenes o haz clic para seleccionarlas.
2. Elige formato de salida, calidad y opciones de renombre/redimensionado.
3. Pulsa **Convertir**; las descargas se inician según el modo elegido (1:1 o ZIP).

Requiere conexión a internet para cargar JSZip desde CDN.
