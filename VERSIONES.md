# Versiones

Historial de la app de seguimiento de la Mitja Marató de Barcelona 2027.

Convención: el archivo que se publica en GitHub Pages se llama siempre `index.html`. Las copias archivadas llevan sufijo (`index_v2.html`, `index_v3.html`…). La clave de `localStorage` solo cambia cuando cambia la numeración de semanas, porque los datos se indexan por número de semana y posición de la sesión.

---

## v2 — 7 de octubre de 2026

Archivo: `index_v2.html` · Clave de almacenamiento: `mitja-bcn-2027-v2`

**Objetivo**

- 1:43:00 (4:53 min/km) → **1:40:00 (4:44 min/km)**, FC de carrera 172–178.

Motivo: el export completo de Garmin de la preparación 2024–25 mostró que el 1:44:40 se consiguió con 17,4 km/semana y 2,4 sesiones, con solo dos tiradas por encima de 15 km. Y con dos 10K de 44:52 y 45:00, que predicen 1:38 de tabla. La Mitja de 2025 se corrió a 148 pulsaciones de media cuando en los 20 km de Sant Boi se había corrido a 180: el limitante era la resistencia específica y la intensidad de carrera, no el motor.

**Calendario**

- 20 semanas desde el 1 de octubre de 2026 → **18 semanas desde el lunes 12 de octubre de 2026**.
- Bloque de base de 4 semanas → 3 semanas (25, 29 y 26 km).

**Días**

- Martes, jueves y domingo → **martes (calidad), jueves (rodaje suave), sábado (tirada larga)**.
- Fuerza: dos sesiones semanales → **una, pegada al martes justo después de la calidad**. El miércoles está ocupado con el golf, y lunes, viernes y domingo caen todos mal respecto a la calidad o al largo.
- Bloques 2 y 4 de la sesión de fuerza, que no cargan las piernas, cualquier día.

**Ritmos y pulsaciones**

Recalibrados sobre una FC máxima de 203, la más alta registrada en 2025.

| Zona | v1 | v2 | FC |
|---|---|---|---|
| Suave | 6:00–6:20 | 5:25–5:45 | <148 |
| Largo | 5:40–6:00 | 5:15–5:35 | 148–158 |
| Medio | 5:10–5:25 | 4:50–5:00 | 160–168 |
| Ritmo media | 4:50–4:55 | 4:44 | 172–178 |
| Umbral | 4:40–4:48 | 4:32–4:38 | 178–185 |
| Series | 4:28–4:38 | 4:15–4:25 | — |

Las zonas de v1 estaban 45–60 s/km por debajo del ritmo al que corre de verdad en rodaje suave, así que la app le habría descontado nota por correr normal.

**Volumen**

- Media 31 → **33,7 km/semana**. Pico 40 → **43** (semana 14).
- Tiradas largas: máxima 19 km → **21 km** (semana 14) y **20 km con 12 km a 4:44** (semana 16, sesión clave).

**Funciones nuevas**

- Rango de FC objetivo en cada sesión y campo para anotar la FC media real.
- Aviso automático cuando una sesión de calidad se corre más de 5 pulsaciones por debajo del rango.
- Sección de la sesión de fuerza: 5 bloques de 5 min a rondas, con el bloque 3 sustituido y dibujos de los cuatro ejercicios nuevos.
- Sección de los dos controles con el plan de contingencia escrito.
- Sección de cómo encaja la semana.

**Sesión de fuerza**

- Bloque 1: de 10 a 8 repeticiones con más peso.
- Bloque 3 (hombro, bíceps, tríceps) sustituido por gemelo, sóleo, peso muerto rumano a una pierna y plancha lateral.
- Bloque 5 (pliometría) hasta la semana 14, fuera desde la 15.
- Bloques 2 y 4 sin cambios.

**Controles**

| Cuándo | Objetivo | Decisión |
|---|---|---|
| Domingo 29 de noviembre (sem. 7) | 10K ≤ 46:00 | Por encima de 47:00 → bajar a 1:43 y ritmo de media a 4:53 |
| Domingo 24 de enero (sem. 15) | 10K ≤ 44:30 | Por debajo de 44:00 → 1:38 sobre la mesa |

**Icono y nombre**

`icon.png` (180×180) e `icon-512.png` regenerados con "1:40". iOS congela nombre e icono al crear el acceso directo: hay que borrar el de 1:43 y volver a añadirlo.

---

## v1 — septiembre de 2026

Archivo original. Objetivo 1:43:00 a 4:53 min/km. 20 semanas desde el 1 de octubre de 2026, 3 sesiones por semana (martes, jueves, domingo) más dos sesiones de fuerza. Media de 31 km/semana, pico de 40. Zonas de ritmo sin calibrar contra datos reales, sin objetivos de pulsaciones y sin detalle de la sesión de fuerza.

Clave de almacenamiento: `mitja-bcn-2027`.
