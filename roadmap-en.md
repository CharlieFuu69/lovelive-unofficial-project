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
| `2024-08-29 00:42 (GMT -4)`    | 159                 | 7                  | 61.11% (11/18 tasks)   |

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

- [ ] **[IN PROGRESS] LIVE SHOW FORMATION PANEL.**
> - [x] Gacha Schemes.
>   > - [x] Change stat keys (`perfect_pwr`/`great_pwr`) to (`active_pwr`/`passive_pwr`).
>   > - [x] Create Skill Scheme with variants: Class 1, Class 2, etc.
>   > - [x] Assign Skills randomly when getting SR and UR type cards.
>   > - [x] Skill Assignment: Variant V1 to R type cards, and V1 (or higher) to SR/UR type cards.
>
> - [x] Collection.
>   > - [x] Modify `Card()` class to get the Skill of the current card.
>   > - [x] Modify card display to indicate the Skill of the card.
>
> - [ ] Live Show Preparation.
>   > - [ ] Create the window/scene to configure the Live Show strategy.
>   > - [ ] Create vertical thumbnails of the cards to display the strategy cards.
>   > - [ ] Create card selector to configure strategy (consider using screen `tab_cardlist`).
>   > - [ ] Create strategy selector (in case player wants to configure more than one strategy).
>
> - [ ] Live Show scoring logic.
>   > - [ ] Create strategy manager with object-oriented logic (class `LiveStrategy()`).
>   > - [ ] Create strategy initialization method (If there are no strategies, it will create an empty strategy. If there are strategies configured, it will load them).
>   > - _[Defining more tickets]_
>
> _[Defining more sub-tasks]_

- [ ] **[WAITING] GAME SECTION: LIVE SHOWS.**
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
