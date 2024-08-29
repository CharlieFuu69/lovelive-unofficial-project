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
| `2024-08-29 00:42 (GMT -4)`    | 156                 | 8                  | 61.11% (11/18 tareas)  |

---

### Checklist de características:

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

- [ ] **[EN CURSO] PANEL DE FORMACIÓN DE LIVE SHOW.**
> - [ ] Esquemas de Gacha.
>   > - [x] Cambiar keys de estadísticas (`perfect_pwr`/`great_pwr`) a (`active_pwr`/`passive_pwr`).
>   > - [ ] Crear esquema de Skills con variantes: Clase 1, Clase 2, etcétera.
>   > - [ ] Asignar Skills al azar al obtener cartas de tipo SR y UR.
>   >
>
> - [x] Colección.
>   > - [x] Modificar la clase `Card()` para obtener la Skill de la carta actual.
>   > - [x] Modificar visualizador de cartas para indicar la Skill de la carta.
>
> - [ ] Preparación de Live Shows.
>   - [ ] Crear la ventana/escena para configurar la estrategia del Live Show.
>   - [ ] Crear miniaturas verticales de las cartas para visualizar las cartas de la estrategia.
>   - [ ] Crear selector de cartas para configurar la estrategia (considerar uso de screen `tab_cardlist`).
>   - [ ] Crear selector de estrategias (en caso de que el jugador quiera configurar más de una estrategia).
>
> - [ ] Lógica de puntuación de Live Shows.
>   > - [ ] Crear gestor de estrategias con lógica orientada a objetos (clase `LiveStrategy()`).
>   > - [ ] Crear método de inicialización de estrategia (Si no hay estrategias, creará una estrategia vacía. Si hay estrategias configuradas, las carga).
>   > - _[Definiendo más tickets]_
>
>  _[Definiendo más sub-tareas]_

- [ ] **[EN ESPERA] APARTADO DE JUEGO: LIVE SHOWS.**
> - [x] Secuencia de los Live Shows.
>   > - [x] Mostrar portada, título, Full Combo y BPM de la canción a jugar.
>   > - [x] Instanciar la partida como objeto del núcleo de Ren'Py RhythmBeats! (`RhythmPlayground()`).
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
