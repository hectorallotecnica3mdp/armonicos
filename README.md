# Armónicos en la instalación

Simulador educativo, autocontenido y adaptable a móviles para explorar cómo las cargas no lineales modifican la corriente, la tensión y la corriente de neutro. Permite ajustar manualmente cada orden entre el 2.º y el 25.º armónico, con los impares más comunes visibles desde el inicio.

## Probar localmente

Abrí `index.html` en un navegador moderno. No requiere dependencias ni compilación.

## Publicar en GitHub Pages

El flujo `.github/workflows/pages.yml` publica el sitio al hacer push a `main` y permite lanzarlo manualmente desde **Actions**. En la configuración del repositorio, seleccioná **Settings → Pages → Build and deployment → Source: GitHub Actions**. La URL aparece al finalizar la primera publicación.

## Alcance del modelo

Los espectros de carga y las corrientes de fuga son valores ilustrativos, no mediciones. La app supone 220 V fase-neutro, 50 Hz, cargas equilibradas y una impedancia de red inductiva simplificada. No sustituye mediciones, estudios eléctricos, normas aplicables ni asesoramiento profesional. Los supuestos y limitaciones también están explicados dentro de la app.
