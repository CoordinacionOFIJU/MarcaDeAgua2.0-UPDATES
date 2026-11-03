# Marca de agua 2.0 · Actualizaciones

Archivos que lee el programa al abrirse para saber si hay una versión nueva.

- `version.json`: número de la última versión, dirección del zip, huella SHA-256 y novedades.
- `app-X.Y.Z.zip`: la carpeta `resources\app` completa de cada versión. Se conservan las anteriores para que nunca haya una versión anunciada sin su archivo correspondiente.
- `app.zip`: copia de la 2.0.5 para el aviso de esa versión que pueda quedar en caché.

No contiene videos ni datos de entregas.
