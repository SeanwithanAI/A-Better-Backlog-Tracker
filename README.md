<div align="center">

<img src="docs/logo.svg" width="96" alt="A Better Backlog Tracker logo">

# A Better Backlog Tracker

**Game Backlog & Play Log: what to play next, how long it takes, and your year in games**

![Version](https://img.shields.io/badge/version-2026--11--14%20mk9-7C3AED)
![Single file](https://img.shields.io/badge/single%20file-HTML-5B21B6)
![No account needed](https://img.shields.io/badge/no%20sign--up-required-334155)
![PageVault ready](https://img.shields.io/badge/PageVault-ready-2563eb)

*by SeanwithanAI*

</div>

![Library: cover-art tiles with status, main-story time and hours played](docs/screenshots/library.png)

---

## Overview

A Better Backlog Tracker keeps your game backlog, your play log and your reviews in one place. It helps you decide what to play next, plans a year of games around the time you actually have, and wraps each year up with a recap. It's all in one HTML file, with nothing to install and no sign-up.

## Features

- **Find games before you add them.** Search the free **RAWG** game database and see screenshots, player ratings, Metacritic score, genres, platforms, developer and a description first.
- **Cover-art library.** Sharp box-art tiles (Steam box art when available) showing status, how excited you are (🔥 ✨ 🌙), the player rating, main-story time, hours played and a progress bar. Switch to detail cards any time. Filter by status or genre, and sort by rating, length, time played, release date, or excitement (most → least or least → most).
- **Real box art.** With a free SteamGridDB key, the tracker fills in proper box art (not screenshots), through PageVault. It only fills covers you haven't set yourself: paste a SteamGridDB link or upload your own and it's left alone; clear it and automatic art comes back.
- **Upload your own pictures.** Add your own cover (portrait 600 × 900, 2:3) and screenshots (landscape 1920 × 1080, 16:9) to any game. In PageVault they're saved on your server.
- **HowLongToBeat times.** Every game links to HowLongToBeat and keeps its main-story hours. Estimated times are marked **≈** until you confirm them.
- **How excited are you?** *🔥 Can't wait*, *✨ Interested* or *🌙 Someday*, each explained, so the backlog sorts itself.
- **Up next.** One clear pick for what to play next, plus backups, each with the reasons (*"Heavy on story, like Disco Elysium, which you enjoyed"*). Choose how long a game you want, from short to 30 h+. **Not now** hides a pick for 3 days.
- **It learns what you like.** After you finish a game, *How was it?* asks how you felt (😍 🙂 😐 👎), what worked (story, combat, music, challenge…), what didn't, and whether you want more like it. Every review changes the picks and the **Your taste so far** summary.
- **Other players' opinions.** RAWG player ratings (Exceptional → Skip), the critic score, recent posts from the game's subreddit, and links to Steam, Metacritic, RAWG and Backloggd reviews.
- **Year plan.** Set a goal (*finish 20 games*) and how many hours a week you can play. The plan fills the year month by month from your backlog. Mark a game **📌 must play** and the plan makes room, telling you what it moved out to stay within your hours. If the goal doesn't fit, it shows how many hours a week you'd need.
- **Play log with start and finish dates.** Log when you started and finished each game, with optional hours and notes. See a **calendar** of what you played each day, and a counter of games played and finished this year, with your goal.
- **Year in review.** Games played and finished, hours, longest streak, favorite, most played, quickest finish, longest journey, month by month, and every game's start-to-finish timeline. A banner announces it each December.
- **Import your backlog.** Paste a list of games, or import a game-list file (for example, a Backloggd backlog). Games you already have are skipped, and RAWG can fill in covers and ratings afterwards.
- **Ayn Thor playtime (optional).** Cocoon's backups include every play session. Make a backup in Cocoon and import it in the **Sync** tab. Only new sessions are added, so importing the same backup again is safe.
- **Steam playtime (optional).** Add your Steam Web API key and SteamID64. In PageVault, your playtime syncs automatically every time you open the tracker (at most every 30 minutes): new hours go into your play log, and games you've started move to Playing. Opened on its own, use **Sync now** with a proxy or the two-step copy-and-paste.
- **Day or Dark.** Choose Day, Dark or Auto (follows your device) in Settings.
- **Backup and restore,** with a reminder when you haven't backed up in a week (outside PageVault).
- **Download app + data.** In **Settings**, one click downloads a .zip with this version of the app, a backup of your data, and a short note on how to restore it. Open the HTML anywhere and restore the backup to pick up where you left off. In PageVault it's the exact file that's installed.

## Screenshots

| Up next | Year in review |
|---|---|
| ![Up next: the top pick with reasons, and other good picks](docs/screenshots/upnext.png) | ![Year in review: totals, highlights and month by month](docs/screenshots/recap.png) |

| Year plan |
|---|
| ![Year plan: games laid out month by month, with must-play pins](docs/screenshots/plan.png) |

<sub>Screenshots use made-up games and example data.</sub>

## Getting started

1. Open `A-Better-Backlog-Tracker-<date>-<mk>.html` in any modern browser, or open it from **PageVault**.
2. For game search, get a free API key at [rawg.io/apidocs](https://rawg.io/apidocs) and paste it in **Find games** (or **Settings**).
3. Add games from **Find games**, use **Import a list**, or import a game-list file from **Settings → Import backup**.
4. Mark how excited you are about each game, and check **Up next** when you can't decide.
5. When you start or finish a game, log it in **Play log** and answer *How was it?*

Online lookups (RAWG, Steam, cover images) use free public services. Everything else works offline.

## Where your data is stored

| Opened from… | Saved to | Badge shown under the app's name |
|---|---|---|
| **PageVault** | Your own server only, separately for each signed-in person. Nothing is kept in the browser. No backup reminders. | *Saved to your server* |
| **A local file** | This browser only. Use **Settings → Back up** to keep a copy; a reminder appears after 7 days without one. | *Saved on this device only* |

Backups include your API keys. Moving between the two: back up on one side and **Import backup** on the other.

## Versioning

Every release is a new file named with the release date. The first release of a day is just the date; later releases that same day add `mk1`, `mk2`, `mk3`… (the count starts over each day), e.g. `A-Better-Backlog-Tracker-2026-11-13.html`, then `A-Better-Backlog-Tracker-2026-11-13-mk1.html`. The version also appears under the app's name and in the footer. Older files stay in the repo, so PageVault can roll back to any of them.

| Version | Notes |
|---|---|
| **2026-11-14 mk9** | **Download app + data (.zip)** replaces Download this app: one click gives a zip with the app's HTML, your backup and a how-to-restore note. Like a backup, it includes your API keys. |
| **2026-11-14 mk8** | **Download this app** in **Settings**: the HTML file for this version, to keep or run on its own. |
| **2026-11-14 mk7** | Year plan: 🔥 Can't-wait games are always included, and games that aren't out yet start the month they release (the rest of the plan works around them); games coming out later, or with no date, are listed separately. Each game has an editable release date and a “Not out yet” box; Up next skips unreleased games. Play log: a “This is the day I started the game” box instead of marking games started automatically, and “No change” is the default. The calendar shows only days you played; Year in review is unchanged and now explains its colors. |
| **2026-11-14 mk6** | Ayn Thor playtime is imported by hand only (**Sync → Import a Cocoon backup**); the automatic pickup through PageVault was removed. |
| **2026-11-14 mk5** | Ayn Thor playtime from Cocoon: import a Cocoon backup in the **Sync** tab (formerly Steam), or have new backups come in automatically through PageVault's imports folder (PageVault 2026-11-14 mk3). Each session becomes a play-log entry; games not in your library can be added, linked or ignored. Name matching no longer treats “Ultimate” as an edition word. Times under an hour show in minutes. |
| **2026-11-14 mk4** | Day, Dark or Auto appearance in **Settings** (Auto follows your device), like the other apps. |
| **2026-11-14 mk3** | Box art from SteamGridDB (needs a free key and PageVault 2026-11-14 mk2) instead of screenshots; never replaces art you linked or uploaded, and clearing your link brings automatic art back. Upload your own cover and screenshots, with recommended sizes shown. |
| **2026-11-14 mk2** | Automatic Steam playtime sync in PageVault, through PageVault's new relay (needs PageVault 2026-11-14 mk1 or later). Game search and RAWG lookups also go through the relay in PageVault, so they work in Brave on iPhone. |
| **2026-11-14 mk1** | Phones: the game window fills the screen with the close button always visible (it was hidden behind the browser bar in Brave), and the phone's Back button or swipe closes it. Text boxes no longer zoom the page on iPhone. Tile badges moved to the top so they don't cover the box art; on phones the status is a colored dot, matching the dots on the filter buttons. |
| **2026-11-14** | Tiles show the player rating and your excitement icon (🔥 ✨ 🌙). New sorts: release date (newest/oldest) and excitement in both directions. Sharper cover art (Steam 2× box art, full-width RAWG art). Better RAWG matching for names with accents, years or editions, plus **Settings → Find art & details** for games still missing art. |
| **2026-11-13 mk4** | PageVault ready: *Saved to your server* / *Saved on this device only* badge, a 7-day backup reminder outside PageVault, and backup status in Settings. Fixed screenshots and header pictures that didn't load (they now use sizes RAWG actually serves, and fall back to the full-size image). |
| **2026-11-13 mk3** | Game-list imports keep estimated main-story times (marked ≈) and Backloggd links. The year plan fills your hours sensibly instead of choosing only the shortest games. |
| **2026-11-13 mk2** | Year plan with goals, hours per week and must-play games. Import a pasted list or a game-list file. Recommendations learn story and narrative preferences. Yearly goal on the play log. |
| **2026-11-13 mk1** | Play log with start and finish dates, calendar, Year in review, and excitement levels. |
| **2026-11-13** | *How was it?* reviews, other players' ratings and subreddit posts, and the Up next recommender. |
| **2026-11-12 mk1** | Cover-art tiles. |
| **2026-11-12** | First release. |

---

<div align="center"><sub>A Better Backlog Tracker · Game Backlog & Play Log · by SeanwithanAI · private repository</sub></div>
