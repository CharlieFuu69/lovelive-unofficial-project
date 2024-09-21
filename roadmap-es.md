<p align="center">
  <img width="180" height="180" src="https://github.com/CharlieFuu69/RenPy_RhythmBeats/blob/main/icons/llup_icon.png">
</p>

<h2 align="center"> LoveLive! UNOFFICIAL PROJECT </h2>
<h5 align="center"> Roadmap (Progreso de desarrollo) </h5>

> [!NOTE]
> _Este Roadmap puede estar sujeto a cambios debido a retrasos, creación de nuevas características y otros elementos no señalados._

---

### Resumen:

| Última actualización de status | Tickets completados | Tickets pendientes | Progreso total         |
|---|---|---|---|
| `2024-09-18 21:00 (GMT -3)`    | 174                 | 1                  | 66.66% (12/18 tareas)  |

---

### Tasklist de características:

- [x] **[COMPLETADO] REACONDICIONAMIENTO DEL NÚCLEO DE "REN'PY RHYTHMBEATS!"**

- [x] **[COMPLETADO] INTEGRACIÓN DEL SERVICIO DE DISCORD RICH PRESENCE.**

- [x] **[COMPLETADO] ALMACENAMIENTO DE DATOS PRINCIPALES DEL JUGADOR.**

- [x] **[COMPLETADO] SELECTOR DE CANCIONES (MODO "UN SOLO JUGADOR").**

- [x] **[COMPLETADO] SISTEMA DE CACHING DE DISPLAYABLES (IMÁGENES/MVs).**

- [x] **[COMPLETADO] SISTEMA DE PROGRESO DE JUGADOR (NIVEL DE JUGADOR).**

- [x] **[COMPLETADO] PANEL DE COLECCIÓN DEL JUGADOR.**

- [x] **[COMPLETADO] MENÚ DE RECLUTAMIENTO (Gacha).**

- [x] **[COMPLETADO] GESTOR DE ASSETS Y DESCARGAS DESDE EL CDN.**

- [x] **[COMPLETADO] MENÚ DE INICIO.**

- [x] **[COMPLETADO] PANEL DE AFINIDAD CON SCHOOL IDOL FAVORITA.**

- [x] **[COMPLETADO] PANEL DE FORMACIÓN DE LIVE SHOW.**

- [ ] **[EN CURSO: 82.35%] APARTADO DE JUEGO: LIVE SHOWS.**
> - [ ] Lógica de puntuación en Live Shows.
>   > - [ ] Obtener sumatoria de estrategia activa como puntuación base por carta.
>   > - [ ] Obtener lista de cartas activas para ser recorridas por cada nota tocada.
>   > - [ ] Crear subclase de RhythmBeats (`RhythmSessionNormal()`) para el modo de juego "Un solo jugador".
>   > - [ ] La subclase debe tener un contador de notas para estado de reposo y estado activo de Skills.
>   > - [ ] El método `periodic_tap()` debe ser readaptado para la lógica de puntuación por estrategias.
>   > - [ ] El método `periodic_tap()` debe ejecutar una rotación de cartas activas por cada nota tocada.
>   > - [ ] El método `periodic_tap()` debe reiniciar automáticamente el índice de rotación para evitar errores de tipo `IndexError`.
>   > - [ ] Inspector y disparador de Skills.
>   >   > - [ ] Disparar Skill "Combo Skill" (Sumar `m` LP para `n` cantidad de notas).
>   >   > - [ ] Disparar Skill "Combo Skill" (Incrementar en `m`% el LP para `n` cantidad de notas).
>   > 
>   > - [ ] _[Definiendo más tickets...]_
>
> - [x] Secuencia de los Live Shows.
>   > - [x] Mostrar portada, título, Full Combo y BPM de la canción a jugar.
>   > - [x] Instanciar la partida como objeto del núcleo de Ren'Py RhythmBeats! (`RhythmSessionNormal()`).
>   > - [x] Mostrar juicio del Live Show al finalizar la partida (Live Cleared!, Full Combo!, All Perfect!).
>   > - [x] Mostrar XP obtenida por performance del Live Show.
>   >   > - [x] XP por juicio del Live Show.
>   >   > - [x] XP por tiempo de reacción promedio.
>   >   > - [x] XP por nuevo récord alcanzado.
>   >
>   > - [ ] Mostrar resultados (estadísticas) del Live Show.
>   >   > - [x] Cantidad de notas Perfect!.
>   >   > - [x] Cantidad de notas Great!.
>   >   > - [x] Cantidad de notas Miss.
>   >   > - [x] Mostrar bandera de Full Combo/All Perfect.
>   >   > - [x] Mostrar bandera de nuevo récord.
>   >   > - [x] Mostrar LP obtenido en el Live Show.
>   >   > - [x] Mostrar el Rank del Live Show (CBAS).
>   >   > - [ ] Escoger y mostrar los ítems de recompensa del Live Show.

- [ ] **[PENDIENTE] PANEL DE MISIONES CON RECOMPENSAS.**

- [ ] **[PENDIENTE] PANEL DE PERFIL DEL JUGADOR.**

- [ ] **[PENDIENTE] SISTEMA DE CUENTAS DE JUGADOR (LoveLive Fan ID, Database).**

- [ ] **[PENDIENTE] EVENTOS ONLINE ASÍNCRONOS (MODOS DE JUEGO Y BACKEND DEL SERVIDOR).**

- [ ] **[PENDIENTE] MAPEAR UN TOTAL DE 30 CANCIONES PARA EL LANZAMIENTO.**

---

### Procedimientos no considerados para el progreso:

- [ ] **[PENDIENTE] COMPROBACIÓN DE ERRORES Y CORRECCIONES PREVIAS.**

- [ ] **[PENDIENTE] INICIO DE PERIODO DE "BETA CERRADA".**

- [ ] **[PENDIENTE] LIBERACIÓN DE "LOVELIVE! UNOFFICIAL PROJECT".**

- [ ] **[PENDIENTE] LIBERACIÓN DEL CÓDIGO FUENTE DEL JUEGO (GitHub).**
