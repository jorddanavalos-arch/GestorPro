# GestorPro

Aplicación web progresiva (PWA) lista para publicar en GitHub Pages.

## Publicar

1. Cree un repositorio en GitHub.
2. Suba **todo el contenido** de esta carpeta a la raíz del repositorio.
3. Abra **Settings > Pages**.
4. En **Build and deployment**, seleccione **Deploy from a branch**.
5. Seleccione la rama `main` y la carpeta `/(root)`, luego guarde.
6. Abra la URL publicada y espere unos segundos. El botón **Instalar** aparecerá cuando el navegador habilite la instalación.

## Importante

- No cambie la ubicación de `manifest.webmanifest`, `sw.js` ni de la carpeta `icons`.
- GitHub Pages usa HTTPS, requisito necesario para el service worker.
- Al actualizar la aplicación, cambie `CACHE_NAME` en `sw.js` para forzar la actualización del caché.
- Los datos se guardan localmente en el navegador del dispositivo. No se sincronizan entre dispositivos.
