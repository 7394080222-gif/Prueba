# Mi amiga la vaca — paquete listo para publicar gratis

Esta carpeta contiene una app web estática instalable (PWA) con los módulos de animales, manejo, reproducción, salud, producción, finanzas y asistente básico.

## Probar en tu computadora
Abre `index.html` en un navegador. Los datos se guardan localmente en ese navegador. Para probar instalación PWA y modo sin conexión, debes servir la carpeta por HTTPS o localhost.

## Publicar gratis con GitHub Pages
1. Crea una cuenta gratuita en https://github.com si no tienes una.
2. Crea un repositorio nuevo, por ejemplo `mi-amiga-la-vaca`.
3. Sube TODOS los archivos de esta carpeta a la raíz del repositorio: `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`.
4. En el repositorio entra a **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, elige la rama `main` y carpeta `/ (root)`, y pulsa **Save**.
6. Espera a que GitHub Pages termine la publicación. La dirección será del tipo `https://TU-USUARIO.github.io/mi-amiga-la-vaca/` (copia la URL exacta que GitHub muestre).

## Instalar en el celular
Abre la URL publicada en Chrome (Android) y elige **Instalar aplicación** o **Añadir a pantalla principal**. En iPhone, abre en Safari y usa **Compartir → Añadir a pantalla de inicio**.

## Limitaciones importantes
- Es un prototipo local: no tiene cuentas, base de datos compartida ni sincronización entre dispositivos.
- Los registros se guardan en el almacenamiento del navegador de cada dispositivo. Usa **Exportar datos** con frecuencia y guarda el JSON en un lugar seguro.
- El asistente usa reglas sencillas y tus registros locales; no es una IA veterinaria.
- Las alertas aparecen dentro de la aplicación; no se envían notificaciones push.
- No usa HTTPS hasta que se publique con GitHub Pages.
