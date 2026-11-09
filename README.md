# 🧠 TYM — Track Your Mind

A complete to-do & life-tracking app: tasks, reminders with a ringing
alarm, habits, focus timer, study tracker, exam countdowns and a
weekly timetable — all in one app, all data stored on your own device.

## ▶ Live app
Open **index.html** (the whole app in one file) — or the GitHub Pages
site for this repo.

## ✨ Features
- Tasks with subtasks (nested), priorities, tags, attachments, repeats
  (daily / weekdays / weekly / every-2-weeks / monthly)
- Multiple reminders per task + full-screen alarm with snooze
- Natural-language quick add: "Pay fees tomorrow 5pm !high #college"
- Voice input, command palette (Ctrl+K), full keyboard shortcuts
- Today with Top-3 focus, progress ring and day streak
- Calendar (drag to reschedule), Timeline with "Plan My Day",
  Kanban Board, Eisenhower Matrix
- Pomodoro focus timer with ambience sounds and session log
- Habits with streaks, daily routines, Review with a year heatmap
- Study: subjects & chapters with spaced-revision tasks
- Exams: countdowns + one-tap revision plans · Weekly timetable
- Dark mode, offline PWA, backup export/import, CSV import

## 📱 Android
The `android-app/` project (in the source zip) wraps the app with
Capacitor, including real phone notifications. Build steps are in
`android-app/BUILD-ANDROID.md`.

## 🛠 Tech
Plain HTML / CSS / JavaScript — no framework, no build step.
One file per screen, every file commented. Data never leaves the device.
