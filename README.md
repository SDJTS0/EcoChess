# NEXO CHESS UNIVERSAL · MVP 0.1

PWA inicial para explorar una experiencia de ajedrez, salas comunitarias y proyectos regenerativos.

## Qué incluye esta versión
- Interfaz adaptable a móvil y escritorio.
- Tablero local con selección de piezas y movimientos demostrativos.
- Navegación Jugar / Salas / Proyectos / Mi impacto.
- Salas y mensajes de demostración en la sesión del navegador.
- Catálogo de proyectos de ejemplo.
- Manifest y service worker para instalación/caché básica.

## Qué NO está implementado todavía
- No hay partidas legales completas ni rival de IA.
- No hay chat real entre usuarios: los mensajes son locales a la sesión.
- No hay cuentas, servidor, base de datos ni sincronización entre dispositivos.
- Los proyectos y métricas son ejemplos, no resultados ambientales reales.

## Publicar con GitHub Pages desde Android
1. Crea un repositorio público llamado `nexo-chess-universal`.
2. Sube `index.html`, `manifest.json`, `sw.js` y `README.md` a la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
6. Espera a que termine la publicación. La URL normalmente tendrá el formato `https://TU-USUARIO.github.io/nexo-chess-universal/`.

## Siguiente fase técnica
1. Integrar una biblioteca de reglas de ajedrez y pruebas.
2. Conectar autenticación, PostgreSQL y mensajería en tiempo real.
3. Añadir permisos, moderación, límites antispam y políticas de privacidad.
4. Implementar el registro de proyectos, evidencias y revisión humana.
5. Añadir pruebas automatizadas y registrar cambios con Git.

## Principio de integridad
No afirmar que una función está activa hasta probarla. Mantener el Elo ajedrecístico separado de las contribuciones comunitarias y del impacto ambiental verificado.
