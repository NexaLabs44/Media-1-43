# 1:43 — Mitja de Barcelona 2027

Seguimiento personal del plan de entrenamiento para la Mitja Marató de Barcelona del **14 de febrero de 2027**. Objetivo: **1:43:00** (4:53 min/km).

Plan de 20 semanas, 3 sesiones por semana más fuerza opcional, del 1 de octubre de 2026 al día de carrera.

## Publicarlo en GitHub Pages

1. Crea un repositorio nuevo, por ejemplo `mitja-bcn-2027`. Puede ser privado si activas Pages desde una cuenta Pro; si es gratuita, hazlo público (no contiene datos personales).
2. Sube `index.html`, `icon.png`, `icon-512.png` y `README.md` a la raíz. Los cuatro archivos van juntos: si el icono no está en la raíz, iOS pondrá una captura de la página.
3. Ve a **Settings → Pages**, en *Source* elige `Deploy from a branch`, rama `main` y carpeta `/ (root)`. Guarda.
4. En un par de minutos estará en `https://TU-USUARIO.github.io/mitja-bcn-2027/`.
5. En el móvil, abre esa dirección en Safari (no en Chrome) y usa *Compartir → Añadir a pantalla de inicio*. Aparecerá como **1:43** con el icono oscuro. Se abre a pantalla completa, sin barra del navegador.

## Cómo funciona

- Cada semana tiene sus sesiones con día, objetivo y ritmo. Marca el check cuando la hagas.
- Al marcar, se rellenan los km previstos: cámbialos si has hecho otra cosa.
- Anota ritmo real y esfuerzo percibido (1 a 10) para ver la tendencia.
- Las notas semanales se guardan solas.
- La barra de 20 semanas de arriba muestra el volumen de cada una y cuánto llevas hecho.

## Dónde se guardan los datos

En el almacenamiento local del navegador, en tu dispositivo. No hay servidor ni cuenta.

Consecuencias prácticas:

- Los datos **no se sincronizan** entre el móvil y el ordenador. Elige uno como principal.
- Si borras los datos de navegación del sitio, se pierden.
- Usa **Exportar copia** cada pocas semanas y guarda el JSON. Con **Importar copia** lo recuperas o lo pasas a otro dispositivo.

## Cambiar el nombre o el icono

El nombre de la pantalla de inicio está en `<meta name="apple-mobile-web-app-title" content="1:43">`. El icono es `icon.png`, de 180×180 px.

iOS guarda el nombre y el icono en el momento de añadir el acceso directo. Si los cambias después, borra el acceso directo del iPhone y vuelve a añadirlo.

## Cambiar el plan

Todo el plan está en la constante `PLAN`, al principio del `<script>` de `index.html`. Cada semana es un objeto con sus sesiones. Edita textos, kilómetros o ritmos y haz commit: los checks ya guardados se mantienen porque se indexan por número de semana y posición de la sesión.

Si añades o quitas sesiones en una semana ya registrada, los datos de esa semana pueden descolocarse. Exporta antes de reordenar.
