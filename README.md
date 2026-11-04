# My Life Dashboard

A Bengali, local-first Personal Life Management website for daily routines, HSC Science study planning, Medical Admission preparation, checklists, progress reviews, learning notes, faith, wellbeing and intentional screen-time tracking.

## Features

- Responsive Bengali dashboard for Windows laptop, tablet and mobile.
- Editable daily timetable and daily checklist.
- Study planner for Biology, Chemistry, Physics, Higher Mathematics, English and ICT.
- Focus timer and manual study-session log.
- Seven-day task and study-progress charts.
- Website active-time tracker, plus manual entries for other Windows applications.
- Daily micro-lessons and a topic-based Life Guide with a two-minute daily revision.
- Daily reflection and weekly review.
- JSON export/import backup.
- Browser Local Storage persistence and a service worker for offline caching on HTTPS/localhost.
- No account, analytics, external API or backend required.

## Run on Windows

1. Download this repository as a ZIP, or clone it.
2. Open the project folder.
3. Double-click `index.html` to preview the app in Chrome or Edge.
4. Your routine, checklist, study and notes are saved in that browser's Local Storage.

The core app works when opened directly. Installable offline caching requires a secure origin such as GitHub Pages (`https://...`) or `localhost`.

## Publish with GitHub Pages

1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Open the Pages URL shown by GitHub after deployment completes.

No build command, Node.js, database, API key or paid hosting is required.

## First-time setup

1. Open **আমার রুটিন** and change the sample times to match your actual college schedule, local prayer times, commute and sleep needs.
2. Open **সেটিংস ও Backup** and set your wake/sleep targets and weekly study goal.
3. Open **আজকের Checklist** and personalize the starter tasks.
4. In **Study Planner**, adjust each subject's progress and add real study sessions.
5. Use **Screen Time** for this website's active tab time. Add other app usage manually if you want an approximate overall picture.
6. Read **Life Guide → দৈনিক Life Revision** each morning or evening.
7. Download a JSON backup regularly.

## Screen-time limitation

A normal website cannot read the total usage time of other Windows applications. This app measures time while its own tab is visible and the browser window is focused. Usage of other apps must be entered manually. This is a browser security limitation, not a missing permission in the app.

## Data and privacy

- Routine, checklist, study logs, reflections and screen-time records are stored in this browser's Local Storage.
- The app does not automatically upload personal data to GitHub or any server.
- Different browsers and devices do not sync automatically.
- Clearing browser site data may erase saved information. Use **Settings → Backup & Restore** regularly.
- Keep a separate backup of important personal or academic records.

## A supportive tool, not a score of your worth

A missed task does not make the day a failure. Adjust the routine to real life, rest when needed and restart with the next useful step.