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
| `2024-09-21 14:55 (GMT -3)`    | 180                 | 4                  | 66.66% (12/18 tasks)   |

---

### Feature checklist:

- [x] **[COMPLETE] REFURBISHING THE CORE OF "REN'PY RHYTHMBEATS!".**

- [x] **[COMPLETE] DISCORD RICH PRESENCE SERVICE INTEGRATION.**

- [x] **[COMPLETE] STORAGE OF MAIN PLAYER DATA.**

- [x] **[COMPLETE] SONG SELECTOR ("SINGLE PLAYER" MODE).**

- [x] **[COMPLETE] DISPLAYABLE CACHING SYSTEM (IMAGES/MVs).**

- [x] **[COMPLETE] PLAYER PROGRESS SYSTEM (PLAYER LEVEL).**

- [x] **[COMPLETE] PLAYER COLLECTION PANEL.**

- [x] **[COMPLETE] RECRUITMENT MENU (Gacha).**

- [x] **[COMPLETE] ASSETS MANAGER AND DOWNLOADS FROM THE CDN.**

- [x] **[COMPLETE] HOME MENU.**

- [x] **[COMPLETE] AFFINITY PANEL WITH FAVORITE SCHOOL IDOL.**

- [x] **[COMPLETE] LIVE SHOW FORMATION PANEL.**

- [ ] **[IN PROGRESS: `20/24 (83.33%)`] GAME SECTION: LIVE SHOWS.**
> - [ ] Scoring logic in Live Shows.
>   > - [x] Get active strategy summation as base score per card.
>   > - [x] Get list of active cards to be cycled through for each note played.
>   > - [x] Create subclass of RhythmBeats (`RhythmSessionNormal()`) for "Single Player" game mode.
>   > - [x] Subclass must have a note counter for idle and active state of Skills.
>   > - [x] `periodic_tap()` method must perform a rotation of active cards for each note played.
>   > - [x] `periodic_tap()` method must automatically reset rotation rate to avoid `IndexError` errors.
>   > - [ ] Skills inspector and trigger.
>   >   > - [ ] Trigger Skill "Combo Skill" (Add `m` LP for `n` number of notes).
>   >   > - [ ] Trigger Skill "Combo Skill" (Increase LP by `m`% for `n` number of notes).
>   >
>   > _[Waiting for more inputs...]_
>
> - [x] Sequence of the Live Shows.
>   > - [x] Show cover art, title, Full Combo and BPM of the song to play.
>   > - [x] Instantiate the game as a Ren'Py RhythmBeats core object! (`RhythmPlayground()`).
>   > - [x] Show Live Show judgment at the end of the game (Live Cleared!, Full Combo!, All Perfect!).
>   > - [x] Show XP obtained by Live Show performance.
>   >   > - [x] XP for Live Show judgment.
>   >   > - [x] XP for average reaction time.
>   >   > - [x] XP for new record achieved.
>   >
>   > - [ ] Show results (statistics) of the Live Show.
>   >   > - [x] Number of notes Perfect!.
>   >   > - [x] Amount of notes Great!.
>   >   > - [x] Number of Miss notes.
>   >   > - [x] Show Full Combo/All Perfect flag.
>   >   > - [x] Show new record flag.
>   >   > - [x] Show PP obtained in the Live Show.
>   >   > - [x] Show the Rank of the Live Show (CBAS).
>   >   > - [ ] Choose and display Live Show reward items.

- [ ] **[PENDING] MISSION PANEL WITH REWARDS.**

- [ ] **[PENDING] PLAYER PROFILE PANEL.**

- [ ] **[PENDING] PLAYER ACCOUNT SYSTEM (LoveLive Fan ID, Database).**

- [ ] **[PENDING] ASYNCHRONOUS ONLINE EVENTS (GAME MODES AND SERVER BACKEND).**

- [ ] **[PENDING] MAP A TOTAL OF 30 SONGS FOR RELEASE.**

---

### Procedures not considered for progress:

- [ ] **[PENDING] BUG CHECKING AND PREVIOUS CORRECTIONS.**

- [ ] **[PENDING] START OF "CLOSED BETA" PERIOD.**

- [ ] **[PENDING] OFFICIAL RELEASE OF "LOVELIVE! UNOFFICIAL PROJECT".**

- [ ] **[PENDING] GAME SOURCE CODE RELEASE.**
