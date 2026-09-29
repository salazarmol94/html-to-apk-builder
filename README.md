# HTML-to-APK Builder V6

Primera versión limpia para probar la compilación real mediante GitHub Actions.

## Estructura

- `.github/workflows/build-apk.yml` → motor de compilación.
- `input-web.zip` → aplicación HTML de prueba.
- `sample-web/index.html` → fuente de la prueba.
- `builder/index.html` → interfaz informativa.

## Prueba

1. Subir estos archivos al repositorio.
2. Abrir GitHub Actions.
3. Ejecutar `Build APK from Web ZIP`.
4. Esperar a que termine.
5. Descargar el artifact `html-to-apk-debug`.

No se necesita instalar Android Studio, JDK ni Gradle en el PC.
