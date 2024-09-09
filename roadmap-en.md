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
| `2024-09-09 00:58 (GMT -3)`    | 173                 | 2                  | 61.11% (11/18 tasks)   |

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

- [ ] **[IN PROGRESS: 95.23%] LIVE SHOW FORMATION PANEL.**
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
> - [x] Card storage logic changes.
>   > - [x] (Gacha) Assign a unique identifier (based on `UUIDv4`) to each claimed card.
>   > - [x] (Gacha) Detect UUID collision to prevent two cards from getting the same UUID.
>   > - [x] (Collection) Modify card logic in `collection -> cards`, to dictionary (`dict()`).
>   > - [x] (Collection) Modify card manager logic (`SchoolIdolManager()`).
>
> - [ ] Live Show Preparation.
>   > - [x] Strategy/formation manager:
>   >   > - [x] Create strategy class (`LiveStrategy()`).
>   >   > - [x] Initialize collection and strategy in class constructor.
>   >   > - [x] Split formation into active and passive strategy.
>   >   > - [x] Get passive strategy power (LP).
>   >   > - [x] Get average active strategy power (LP).
>   >   > - [x] Get Skill of active cards and prepare data usable by RhythmBeats engine.
>   >   > - [x] Create method to add/replace card from a slot in formation.
>   >
>   > - [x] Create vertical thumbnails of the cards to display the strategy cards.
>   > - [x] Create the window/scene to configure the Live Show strategy.
>   > - [x] Create card selector to configure strategy (consider using screen `tab_cardlist`).
>   > - [ ] Create a card preview window when opening the card selector.

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
