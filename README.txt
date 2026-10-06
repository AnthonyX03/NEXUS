NEXUS // ANTHONYX003
=====================

Versión PWA lista para GitHub Pages.

CONTENIDO
---------
- index.html              Portal NEXUS responsive
- manifest.webmanifest    Configuración PWA
- sw.js                   Service Worker / caché offline
- icon-192.png            Icono PWA
- icon-512.png            Icono PWA
- icon-maskable-512.png   Icono PWA maskable
- Intro.mp3               Música de fondo (placeholder)

INSTALACIÓN EN GITHUB PAGES
---------------------------
1. Sube TODOS estos archivos a la raíz del repositorio que uses para NEXUS.
2. Activa GitHub Pages desde Settings > Pages.
3. Abre la URL HTTPS publicada.
4. En Android/Chrome compatible aparecerá el botón "Install" cuando el navegador considere la web instalable.
5. En iPhone/iPad: Safari > Compartir > Añadir a pantalla de inicio.

IMPORTANTE SOBRE Intro.mp3
--------------------------
El ZIP contiene un archivo placeholder llamado Intro.mp3 porque la pista original no estaba disponible en esta sesión.
Sustitúyelo por tu archivo real manteniendo EXACTAMENTE el nombre:
    Intro.mp3

La web lo reproducirá en bucle a volumen 35 % después de que el usuario interactúe con la página, respetando las restricciones de autoplay.

NOTAS PWA
---------
- La instalación depende del navegador y del dispositivo.
- El sitio debe servirse mediante HTTPS; GitHub Pages cumple este requisito.
- El Service Worker cachea el portal y sus recursos principales.
- Los juegos externos siguen siendo páginas independientes.
- Esta PWA NO convierte automáticamente los cuatro juegos en una sola aplicación ni los instala juntos.
