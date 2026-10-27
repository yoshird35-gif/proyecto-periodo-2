# Ciberseguridad 360 — Proyecto P2

Sitio educativo de cinco páginas sobre ciberseguridad, basado en los documentos del Proyecto Segundo Parcial. Se reutilizó la organización general del ZIP original y se adaptó su contenido, estilos y navegación al tema del equipo.

## Estructura

- `index.html`: inicio, carrusel y modal.
- `amenazas.html`: malware, phishing, robo de identidad, fraude y ransomware; incluye accordion.
- `ciberacoso.html`: tipos, consecuencias y pasos de actuación.
- `contrasenas.html`: recomendaciones, autenticación multifactor y mini actividad interactiva.
- `privacidad.html`: protección de datos, lista de comprobación y formulario demostrativo.
- `css/estilos.css`: estilos propios compartidos.
- `css/`: Bootstrap CSS local.
- `js/`: Bootstrap JavaScript local.
- `evidencias/`: carpeta para capturas del proceso y vistas responsivas.
- `mockups/`: carpeta para bocetos de escritorio, tableta y móvil.

## Probar en la computadora

Abre `index.html` en el navegador. Para una prueba más completa, puedes usar la extensión Live Server de Visual Studio Code.

## Publicar con GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `proyecto-ciberseguridad-p2`.
2. Sube el contenido de esta carpeta a la raíz del repositorio (no subas únicamente el ZIP).
3. En GitHub entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, guarda los cambios.
6. Espera a que GitHub Pages publique el sitio. La URL suele tener el formato `https://TU-USUARIO.github.io/proyecto-ciberseguridad-p2/`.
7. Comprueba la navegación entre las cinco páginas en computadora y móvil y copia la URL pública y la del repositorio para tu entrega.

## Evidencias que faltan por realizar

- Captura del código HTML/CSS mostrando los ocho componentes Bootstrap.
- Captura del sitio en escritorio, tableta y teléfono.
- Captura de Settings → Pages y del sitio publicado.
- Mockups propios realizados en Canva, Figma o PowerPoint.
- Sustituye `TU-USUARIO` por tu nombre de usuario real y añade los enlaces finales al documento escolar.

## Componentes Bootstrap incluidos

- Navbar: todas las páginas.
- Carousel: `index.html`.
- Cards: inicio y páginas de contenido.
- Buttons: enlaces y acciones.
- Grid System: filas y columnas responsivas.
- Accordion: `amenazas.html`.
- Modal: `index.html`.
- Form: `privacidad.html`.

## Nota

El formulario de comentarios es una demostración local: no almacena ni transmite datos. El fondo principal utiliza una imagen remota de Unsplash, por lo que esa imagen requiere conexión a internet; el contenido y Bootstrap están incluidos localmente.
