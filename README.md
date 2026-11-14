# Guía de estudio DSY1102 · Cápsula del Tiempo FX

Sitio estático, en español, para aprender la evolución R00–R06 del proyecto JavaFX *Cápsula del Tiempo FX*.

## Contenido

- Guía paso a paso con ejemplos Java, FXML, DAO y JSON.
- Plan de 7 sesiones, preguntas de repaso y checklist.
- Progreso local mediante `localStorage` (sin cuentas ni sincronización entre dispositivos).
- Diseño adaptable a computadores y teléfonos.
- No se necesita backend, base de datos ni instalación de dependencias para la página.

## Abrir localmente

Abre `index.html` en tu navegador. Para desplegar, coloca todo este proyecto en un repositorio público de GitHub.

## Publicar en GitHub Pages (método sencillo)

1. En GitHub crea un repositorio nuevo, por ejemplo `DSY1102-Guia-Estudio`.
2. Sube `index.html`, `README.md` y `.nojekyll` (opcionalmente también el workflow de `.github/workflows/pages.yml`).
3. En el repositorio abre **Settings → Pages**.
4. Si usas el workflow incluido, configura **Source: GitHub Actions**. Al actualizar `main`, el workflow publica la web.
5. Si prefieres no usar workflows, configura **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
6. Tu sitio quedará en `https://TU-USUARIO.github.io/DSY1102-Guia-Estudio/` (sustituye nombre de usuario y repositorio).

No habilites simultáneamente ambos métodos de publicación. Elige uno.

## Actualizar la web

Edita `index.html`, guarda y súbelo al repositorio. GitHub Pages publicará la nueva versión.

## Referencias del docente

- Presentación: https://cmartinezs.github.io/DSY1102-DESARROLLO-ORIENTADO-OBJETOS-2026-2/pages/classes/capsula-tiempo-fx/#1
- Código JavaFX: https://github.com/cmartinezs/DSY1102-JFX-TIME-CAPSULE
- R06: https://github.com/cmartinezs/DSY1102-JFX-TIME-CAPSULE/tree/feat/dsy1102-r06-json-recovery

Sitio de estudio independiente; no incluye la aplicación JavaFX original.


## Proyecto Java completo (nuevo)

La carpeta `proyecto-java/` contiene **15 archivos de código**: `pom.xml`, `module-info.java`, clases JavaFX, modelo, Service, DAO JSON, FXML y tres clases de pruebas. Abre esa carpeta en IntelliJ con JDK 21, importa Maven y ejecuta `Launcher`. La web incluye instrucciones de creación de cada archivo y su código íntegro, copiable y descargable.

La guía web se publica en GitHub Pages, pero **JavaFX es una aplicación de escritorio** y se ejecuta localmente.
