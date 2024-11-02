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
| `2024-11-02 12:31 (GMT -3)`    | 186                 | 4                  | 66.67% (12/18 tareas)  |

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

- [ ] **[EN CURSO: `29/32 (90.63%)`] APARTADO DE JUEGO: LIVE SHOWS.**
> - [x] Lógica de puntuación en Live Shows.
>   > - [x] Obtener sumatoria de estrategia activa como puntuación base por carta.
>   > - [x] Obtener lista de cartas activas para ser recorridas por cada nota tocada.
>   > - [x] Crear subclase de RhythmBeats (`RhythmSessionNormal()`) para el modo de juego "Un solo jugador".
>   > - [x] La subclase debe tener un contador de notas para estado de reposo y estado activo de Skills.
>   > - [x] El método `periodic_tap()` debe ejecutar una rotación de cartas activas por cada nota tocada.
>   > - [x] El método `periodic_tap()` debe reiniciar automáticamente el índice de rotación para evitar errores de tipo `IndexError`.
>   > - [x] Establecer puntuación base de un Fever Time.
>   > - [x] Definir los tiempos de Fever Time en el Dataset de canciones.
>   > - [x] Inspector y disparador de Skills.
>   >   > - [x] Disparar Skills de tipo `combo->int` (Sumar `m` LP para `n` cantidad de notas).
>   >   > - [x] Disparar Skills de tipo `combo->pct` (Incrementar en `m`% el LP para `n` cantidad de notas).
>   >   > - [x] Disparar Skills de tipo `fever` (Sumar `m` LP durante el Fever Time).
>   >
>   > - [x] Reacondicionamiento de RhythmBeats.
>   >   > - [x] Crear método tipo Callback `periodic_loop()`, cuyo llamado debe ser constante en el bucle principal del sistema rítmico.
>   >   > - [x] Sobreescribir método `periodic_loop()` con la lógica de supervisión de Fever Time
>
> - [ ] Secuencia de los Live Shows.
>   > - [x] Mostrar portada, título, Full Combo y BPM de la canción a jugar.
>   > - [x] Instanciar la partida como objeto del núcleo de Ren'Py RhythmBeats! (`RhythmSessionNormal()`).
>   > - [x] Mostrar Skills activas.
>   > - [x] Mostrar fases de Fever Time (Fever Challenge, Fever Time).
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
>   >   > - [ ] Agregar conteo de notas FAST/SLOW.
>   >   > - [ ] Mostrar sprite de la School Idol correspondiente a la carta MVP del Live Show.
>   >   > - [x] Mostrar animación de Subida de nivel de jugador.
>   >   > - [ ] Escoger y mostrar los ítems de recompensa del Live Show.

- [ ] **[PENDIENTE] PANEL DE PERFIL DEL JUGADOR.**

- [ ] **[PENDIENTE] SISTEMA DE CUENTAS DE JUGADOR (LoveLive Fan ID, Database).**

- [ ] **[PENDIENTE] EVENTOS ONLINE ASÍNCRONOS (MODOS DE JUEGO Y BACKEND DEL SERVIDOR).**

- [ ] **[PENDIENTE] TIENDA DE ATUENDOS.**

- [ ] **[PENDIENTE] MAPEAR UN TOTAL DE 30 CANCIONES PARA EL LANZAMIENTO.**

---

### Procedimientos no considerados para el progreso:

- [ ] **[PENDIENTE] COMPROBACIÓN DE ERRORES Y CORRECCIONES PREVIAS.**

- [ ] **[PENDIENTE] INICIO DE PERIODO DE "BETA CERRADA".**

- [ ] **[PENDIENTE] LIBERACIÓN DE "LOVELIVE! UNOFFICIAL PROJECT".**

- [ ] **[PENDIENTE] LIBERACIÓN DEL CÓDIGO FUENTE DEL JUEGO (GitHub).**
