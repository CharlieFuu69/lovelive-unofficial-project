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
| `2025-03-16 21:22 (GMT -3)`    | 226                 | 8                  | 83.33% (15/18 tareas)  |

---

### Tasklist de características:

- [x] **1. [COMPLETADO] REACONDICIONAMIENTO DEL NÚCLEO DE "REN'PY RHYTHMBEATS!"**

- [x] **2. [COMPLETADO] INTEGRACIÓN DEL SERVICIO DE DISCORD RICH PRESENCE.**

- [x] **3. [COMPLETADO] ALMACENAMIENTO DE DATOS PRINCIPALES DEL JUGADOR.**

- [x] **4. [COMPLETADO] SELECTOR DE CANCIONES (MODO "UN SOLO JUGADOR").**

- [x] **5. [COMPLETADO] SISTEMA DE CACHING DE DISPLAYABLES (IMÁGENES/MVs).**

- [x] **6. [COMPLETADO] SISTEMA DE PROGRESO DE JUGADOR (NIVEL DE JUGADOR).**

- [x] **7. [COMPLETADO] PANEL DE COLECCIÓN DEL JUGADOR.**

- [x] **8. [COMPLETADO] MENÚ DE RECLUTAMIENTO (Gacha).**

- [x] **9. [COMPLETADO] GESTOR DE ASSETS Y DESCARGAS DESDE EL CDN.**

- [x] **10. [COMPLETADO] MENÚ DE INICIO.**

- [x] **11. [COMPLETADO] PANEL DE AFINIDAD CON SCHOOL IDOL FAVORITA.**

- [x] **12. [COMPLETADO] PANEL DE FORMACIÓN DE LIVE SHOW.**

- [x] **13. [COMPLETADO] APARTADO DE JUEGO: LIVE SHOWS.**

- [x] **14. [COMPLETADO] PANEL DE PERFIL DEL JUGADOR.**

- [x] **15. [COMPLETADO] SISTEMA DE CUENTAS DE JUGADOR (LoveLive Producer ID).**

- [ ] **16. [EN CURSO... (`13/22 - 59.10%`)] EVENTOS ONLINE ASÍNCRONOS (MODOS DE JUEGO Y BACKEND DEL SERVIDOR).**
>
>    - [ ] (Evento Competitivo) LoveLive! Grand Prix.
>    >    - [x] Crear subclase de `RhythmBeatsCore()` para la mecánica del "LoveLive! Grand Prix".
>    >
>    >    - [ ] Objeto del cliente `GrandPrixClient()`.
>    >    >    - [x] Obtener Deadline (fecha límite) del evento.
>    >    >    - [x] Formatear cuenta regresiva de duración del evento.
>    >    >    - [x] Disparar acciones en fases de la cuenta regresiva del evento.
>    >    >    - [x] (`enter_room`) Comprobar actualizaciones pendientes al entrar a la sala.
>    >    >    - [x] (`enter_room`) Obtener el Ranking de jugadores del evento.
>    >    >    - [x] (`update_own`) Ingresar jugador al evento/Actualizar performance.
>    >    >    - [ ] (`push_match`) Empujar/Actualizar datos del Match (PvP) cuando termina el Live Show.
>    >
>    >    - [ ] Secuencias del evento.
>    >    >    - [x] Secuencia del Lobby (`seq_grandprix_lobby`).
>    >    >    - [x] Secuencia para Preparación de Performance (`seq_grandprix_select_song`).
>    >    >    - [x] Secuencia para resultados de Performance (`seq_llgp_perform_results`).
>    >    >    - [ ] Secuencia para el Match PvP (`seq_llgp_match_start`).
>    >    >    - [ ] Secuencia para resultados del Match (`seq_llgp_match_results`).
>    >    >    - [ ] Secuencia para fin del evento/Premiación (`seq_llgp_event_results`).
>    >
>    >    - [ ] Interfaz del evento.
>    >    >    - [x] Ventana del Lobby (`llgp_event_lobby`).
>    >    >    - [x] Ventana de Gestión de Performance (`llgp_perform_menu`).
>    >    >    - [x] Ventana de resultados de Performance (`llgp_perform_results`).
>    >    >    - [x] Ventana de Ranking Mundial (`llgp_event_ranking`).
>    >    >    - [ ] Ventana de lista de productores/Buscar Partida (`llgp_match_list`).
>    >    >    - [ ] Ventana de Inicio del Match (`llgp_match_start`).
>    >    >    - [ ] Ventana de Resultados del Match (`llgp_match_results`).
>    >    >    - [ ] Ventana de resultados del evento/Premiación (`llgp_event_results`).
>
> _(Esperando más tickets...)_

- [ ] **17. [PENDIENTE] TIENDA DE ATUENDOS.**

- [ ] **18. [PENDIENTE] MAPEAR UN TOTAL DE 30 CANCIONES PARA EL LANZAMIENTO.**

---

### Procedimientos no considerados para el progreso:

- [ ] **[PENDIENTE] COMPROBACIÓN DE ERRORES Y CORRECCIONES PREVIAS.**

- [ ] **[PENDIENTE] INICIO DE PERIODO DE "BETA CERRADA".**

- [ ] **[PENDIENTE] LIBERACIÓN DE "LOVELIVE! UNOFFICIAL PROJECT".**

- [ ] **[PENDIENTE] LIBERACIÓN DEL CÓDIGO FUENTE DEL JUEGO (GitHub).**
