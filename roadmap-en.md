<p align="center">
  <img width="180" height="180" src="https://github.com/CharlieFuu69/RenPy_RhythmBeats/blob/main/icons/llup_icon.png">
</p>

<h2 align="center"> LoveLive! UNOFFICIAL PROJECT </h2>
<h5 align="center"> Roadmap (Development progress) </h5>

> [!NOTE]
> _This Roadmap may be subject to change due to delays, creation of new features and other elements not noted.._

---

### Summary:

| Last status update             | Completed tickets   | Pending tickets    | Total progress         |
|---|---|---|---|
| `2025-04-13 02:21 (GMT -4)`    | 231                 | 3                  | 83.33% (15/18 tasks)   |

---

### Feature checklist:

- [x] **1. [COMPLETE] REFURBISHING THE CORE OF "REN'PY RHYTHMBEATS!".**

- [x] **2. [COMPLETE] DISCORD RICH PRESENCE SERVICE INTEGRATION.**

- [x] **3. [COMPLETE] STORAGE OF MAIN PLAYER DATA.**

- [x] **4. [COMPLETE] SONG SELECTOR ("SINGLE PLAYER" MODE).**

- [x] **5. [COMPLETE] DISPLAYABLE CACHING SYSTEM (IMAGES/MVs).**

- [x] **6. [COMPLETE] PLAYER PROGRESS SYSTEM (PLAYER LEVEL).**

- [x] **7. [COMPLETE] PLAYER COLLECTION PANEL.**

- [x] **8. [COMPLETE] RECRUITMENT MENU (Gacha).**

- [x] **9. [COMPLETE] ASSETS MANAGER AND DOWNLOADS FROM THE CDN.**

- [x] **10. [COMPLETE] HOME MENU.**

- [x] **11. [COMPLETE] AFFINITY PANEL WITH FAVORITE SCHOOL IDOL.**

- [x] **12. [COMPLETE] LIVE SHOW FORMATION PANEL.**

- [x] **13. [COMPLETE] GAME SECTION: LIVE SHOWS.**

- [x] **14. [COMPLETE] PLAYER PROFILE PANEL.**

- [ ] **15. [COMPLETE] PLAYER ACCOUNT SYSTEM (LoveLive Producer ID).**

- [ ] **16. [IN PROGRESS... (`19/22 - 86.36%`)] ASYNCHRONOUS ONLINE EVENTS (GAME MECHANICS AND SERVER BACKEND).**

> [!NOTE]
> *This task involves developing the Fangame's asynchronous event system, specifically the competitive mechanics for the **"LoveLive! Grand Prix"**, a type of event where the core of its competitiveness will be the players' reaction time.*

>    - **DEDICATED SUBCLASS OF `RhythmBeatsCore()`.**
>    >    - [x] Create a subclass of `RhythmBeatsCore()` for the "LoveLive! Grand Prix" mechanics.
>
>    - **CLIENT OBJECT `GrandPrixClient()`.**
>    >    - [x] Get the event's deadline.
>    >    - [x] Format the event's duration countdown.
>    >    - [x] Trigger actions based on the event's countdown phases.
>    >    - [x] (`enter_room`) Check for pending updates upon entering the room.
>    >    - [x] (`enter_room`) Get the event's player ranking.
>    >    - [x] (`update_own`) Enter a player into the event/Update performance.
>    >    - [ ] (`push_match`) Push/Update Match (PvP) data when the Live Show ends.
>
>    - **EVENT SEQUENCES.**
>    >    - [x] Lobby sequence (`seq_grandprix_lobby`).
>    >    - [x] Performance Preparation sequence (`seq_grandprix_select_song`).
>    >    - [x] Performance Results sequence (`seq_llgp_perform_results`).
>    >    - [x] PvP Match sequence (`seq_llgp_match_start`).
>    >    - [x] Match Results sequence (`seq_llgp_match_results`).
>    >    - [ ] Sequence for end of event/Awards (`seq_llgp_event_results`).
>
>    - **EVENT INTERFACE.**
>    >    - [x] Lobby window (`llgp_event_lobby`).
>    >    - [x] Performance management window (`llgp_perform_menu`).
>    >    - [x] Performance results window (`llgp_perform_results`).
>    >    - [x] World ranking window (`llgp_event_ranking`).
>    >    - [x] Producer list/Find match window (`llgp_match_list`).
>    >    - [x] Match start window (`llgp_match_start`).
>    >    - [x] Match results window (`llgp_match_results`).
>    >    - [ ] Event Results/Awards Window (`llgp_event_results`).
>
>    _(Waiting for more entries...)_

- [ ] **17. [PENDING] OUTFIT SHOP.**

- [ ] **18. [PENDING] MAP A TOTAL OF 30 SONGS FOR RELEASE.**

---

### Procedures not considered for progress:

- [ ] **[PENDING] BUG CHECKING AND PREVIOUS CORRECTIONS.**

- [ ] **[PENDING] START OF "CLOSED BETA" PERIOD.**

- [ ] **[PENDING] OFFICIAL RELEASE OF "LOVELIVE! UNOFFICIAL PROJECT".**

- [ ] **[PENDING] GAME SOURCE CODE RELEASE.**
