# 1:40 — Mitja de Barcelona 2027

Seguimiento personal del plan de entrenamiento para la Mitja Marató de Barcelona del **14 de febrero de 2027**. Objetivo: **1:40:00** (4:44 min/km, FC de carrera 172–178).

Plan de 19 semanas del **5 de octubre de 2026** al día de carrera. Tres carreras por semana (lunes, miércoles y fin de semana) más un día de fuerza. Media de 33 km por semana, pico de 43.

## Por qué 1:40 y no 1:43

De la preparación real de 2024–25, que acabó en 1:44:40:

- 17,4 km/semana de media durante 20 semanas, 2,4 sesiones por semana.
- Solo dos tiradas por encima de 15 km en toda la preparación, y una era carrera.
- 10K en 44:52 dos semanas antes de la media, y otro en 45:00 el 31 de diciembre. Eso predice una media de 1:38 de tabla.
- La Mitja se corrió a **148 pulsaciones de media** (máxima 175), cuando en los 20 km de Sant Boi se había corrido a 180 de media. Se corrió a intensidad de rodaje largo.

Conclusión: el limitante no era el motor, era la resistencia específica y la intensidad de carrera. Este plan casi duplica el volumen, añade umbral y ritmo específico, y lleva las tiradas largas hasta 21 km.

## La semana tipo

| Día | Qué toca |
|---|---|
| Lunes | Rodaje suave |
| Martes o jueves | Fuerza, una sesión |
| Miércoles | Calidad: series, umbral o ritmo |
| Sábado o domingo | Tirada larga |

El rodaje suave va el lunes y la calidad el miércoles, no al revés. Así la sesión dura siempre tiene dos días desde la carrera anterior y dos o tres hasta el largo del fin de semana. Si el largo cae en domingo, el rodaje del lunes va corto y muy suave o se salta; si cae en sábado, el lunes se hace entero.

Excepciones, ya escritas en la app: en las semanas 8 y 16 la calidad se mueve al lunes porque el domingo hay un 10K de control, y en la semana de carrera los días pasan a miércoles (activación) y viernes (rodaje corto).

## Cambios frente a la v1

- Objetivo 1:43 → **1:40**, ritmo de media 4:53 → **4:44**.
- 20 semanas desde el 1 de octubre → **19 semanas desde el 5 de octubre**.
- Zonas recalibradas sobre una FC máxima de 203. El rodaje suave pasa de 6:00–6:20 a **5:25–5:45**, que es donde corre de verdad.
- Volumen: media 31 → 33 km/semana, pico 40 → 43.
- Dos tiradas de 21 y 20 km (semanas 15 y 17). La sesión clave pasa de 10 km a 4:55 a **12 km a 4:44**.
- Días de entreno: lunes, miércoles y sábado o domingo. Un día de fuerza en lugar de dos.
- Objetivos de **FC por sesión**, campo para anotar la FC media real y un aviso cuando se corre una sesión de calidad por debajo del rango.
- Controles: 10K ≤ 46:00 en la semana 8 y ≤ 44:30 en la semana 16.
- Clave de almacenamiento nueva (`mitja-bcn-2027-v2`), porque la numeración de semanas ha cambiado.

## Publicarlo en GitHub Pages

1. Repositorio `Media-1-43` (o crea uno nuevo, `mitja-bcn-2027`).
2. Sube `index.html`, `icon.png`, `icon-512.png` y `README.md` a la raíz. Los cuatro archivos van juntos: si el icono no está en la raíz, iOS pondrá una captura de la página.
3. **Settings → Pages**, en *Source* elige `Deploy from a branch`, rama `main` y carpeta `/ (root)`. Guarda.
4. En un par de minutos estará en `https://TU-USUARIO.github.io/REPO/`.
5. En el móvil, abre esa dirección en Safari (no en Chrome) y usa *Compartir → Añadir a pantalla de inicio*. Aparecerá como **1:40** con el icono oscuro.

Si ya tenías el acceso directo **1:43** en el iPhone, **bórralo y vuelve a añadirlo**: iOS guarda el nombre y el icono en el momento de crearlo y no los actualiza.

## Cómo funciona

- Cada semana tiene sus sesiones con día, objetivo, kilómetros, ritmo previsto y rango de pulsaciones. Marca el check cuando la hagas.
- Al marcar, se rellenan los km previstos: cámbialos si has hecho otra cosa.
- Anota ritmo real, FC media y esfuerzo percibido (1 a 10).
- Si en una sesión de calidad la FC queda más de 5 pulsaciones por debajo del rango, la app lo avisa. Es el error de 2025 y el que más tiempo cuesta.
- Cada semana recibe una nota sobre 10: constancia 45 %, volumen 20 %, ritmo 25 % y fuerza 10 %. En el ritmo, pasarse de rápido descuenta igual que quedarse corto. La cabecera muestra la nota media y la racha de semanas con 7 o más.
- En la sesión de fuerza solo marcas si la has hecho o no.
- La barra de 19 semanas de arriba muestra el volumen de cada una y cuánto llevas hecho.

## Plan de contingencia

Está escrito dentro de la app, en la sección *Los dos controles*:

- 10K de noviembre por encima de 47:00 → baja el objetivo a 1:43 y cambia el ritmo de media a 4:53 en las sesiones específicas.
- 10K de enero por debajo de 44:00 → el 1:38 entra en juego.

## La sesión de fuerza

Está dentro de la app, en la sección *La sesión de fuerza*, con el enlace **Ver la sesión completa** desde la ficha de fuerza de cada semana.

Formato: 2 min de calentamiento, 5 bloques de 5 minutos a rondas (normalmente 2 o más) y 20 s de descanso entre bloques. Unos 27 minutos en total.

Cambios sobre la rutina original:

- **Bloque 1** (sentadilla, tijeras, empuje de cadera): de 10 a 8 repeticiones con más peso. Menos rondas y más fuerza.
- **Bloque 3** sustituido. El de hombro, bíceps y tríceps no mueve la marca en una media. Entra: elevación de talón con rodilla estirada (gemelo, 15 por pierna), elevación de talón con rodilla flexionada (sóleo, 15 por pierna), peso muerto rumano a una pierna (8 por pierna) y plancha lateral (30 s por lado). Una ronda ya ocupa casi 4 minutos, así que saldrá una ronda y media.
- **Bloque 5** (pliometría) se mantiene hasta la semana 15 y se quita a partir de la 16.
- Bloques 2 y 4 sin cambios.

Los cuatro ejercicios nuevos van dibujados, con el músculo que trabaja marcado en naranja.

Día: **jueves** si la tirada larga cae en domingo, **lunes** si cae en sábado. Nunca el martes.

## Dónde se guardan los datos

En el almacenamiento local del navegador, en tu dispositivo. No hay servidor ni cuenta.

- Los datos **no se sincronizan** entre el móvil y el ordenador. Elige uno como principal.
- Si borras los datos de navegación del sitio, se pierden.
- Usa **Exportar copia** cada pocas semanas. Con **Importar copia** lo recuperas o lo pasas a otro dispositivo.

## Cambiar el plan

Todo está en la constante `PLAN`, al principio del `<script>` de `index.html`. Cada semana es un objeto con sus sesiones; cada sesión tiene `rp` (ritmo previsto de la sesión completa) y `fc` (rango de pulsaciones). Edita y haz commit: los checks ya guardados se mantienen porque se indexan por número de semana y posición de la sesión.

Si añades o quitas sesiones en una semana ya registrada, los datos de esa semana pueden descolocarse. Exporta antes de reordenar.
