# Armónicos en la instalación

Simulador educativo, autocontenido y adaptable a móviles para explorar cómo las cargas no lineales modifican la corriente, la tensión y la corriente de neutro. Permite ajustar manualmente cada orden entre el 2.º y el 25.º armónico, con los impares más comunes visibles desde el inicio.

## Probar localmente

Abrí `index.html` en un navegador moderno. No requiere dependencias ni compilación. La instalación como app y el modo sin conexión requieren servir el sitio por HTTPS o desde `localhost`; abrir el archivo directamente no alcanza.

En teléfonos, los controles quedan en un panel desplazable arriba y el gráfico seleccionado permanece visible abajo. Las pestañas permiten cambiar entre corrientes, tensión y espectro.

## Instalar en el teléfono

La app se instala desde su sitio publicado en GitHub Pages:

- **Android (Chrome):** abrí el sitio y elegí **Instalar app** en el menú del navegador. Si todavía no aparece, esperá unos segundos y recargá la página para que se registre el modo sin conexión.
- **iPhone/iPad (Safari):** abrí el sitio, tocá **Compartir → Añadir a pantalla de inicio**. En iOS no se instala desde el menú de Chrome.

La app puede abrirse sin conexión después de cargarla una vez con internet.

## Publicar en GitHub Pages

El flujo `.github/workflows/pages.yml` publica el sitio al hacer push a `main` y permite lanzarlo manualmente desde **Actions**. En la configuración del repositorio, seleccioná **Settings → Pages → Build and deployment → Source: GitHub Actions**. La URL aparece al finalizar la primera publicación.

## Alcance del modelo

Los espectros de carga y las corrientes de fuga son valores ilustrativos, no mediciones. La app supone 220 V fase-neutro, 50 Hz, cargas equilibradas y una impedancia de red inductiva simplificada. No sustituye mediciones, estudios eléctricos, normas aplicables ni asesoramiento profesional. Los supuestos y limitaciones también están explicados dentro de la app.
