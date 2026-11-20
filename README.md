# Clave de Tesla para el modo avanzado de Glanceboard

Plantilla para publicar en GitHub Pages la clave pública que Tesla exige a cada aplicación de la Fleet API.

1. Usa esta plantilla y llama al repositorio `tuusuario.github.io`.
2. Sube a `.well-known/appspecific/` el archivo `com.tesla.3p.public-key.pem` que genera Glanceboard (reemplaza el vacío).
3. Activa GitHub Pages: Settings › Pages › Deploy from a branch › main › / (root).

- `.nojekyll`: imprescindible; sin él GitHub no publica `.well-known`.
- `callback/`: devuelve el resultado del inicio de sesión de Tesla a la app. No guarda ni envía nada.

Guía completa: https://wattboard.github.io/glanceboard-web/ayuda/modo-avanzado/

Glanceboard es una app independiente, sin relación con Tesla, Inc.
