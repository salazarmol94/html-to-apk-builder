# HTML-to-APK Builder V5

Motor de compilación en GitHub Actions.

PRIMERA PRUEBA:
1. Sube el archivo `input-web.zip` incluido en este paquete al repositorio.
2. Ve a Actions.
3. Selecciona `Build APK from Web ZIP`.
4. Pulsa `Run workflow`.
5. Al terminar, descarga el artefacto `html-to-apk-debug`.

La interfaz está en `builder/index.html`.

IMPORTANTE: esta V5 prueba primero el motor de compilación. La conexión automática del formulario del navegador con GitHub se hará en la siguiente etapa, usando un backend seguro; no se deben colocar tokens de GitHub dentro de JavaScript del navegador.
