# SP Launcher

A minimalist, student-friendly Android launcher — built with Kotlin and Jetpack Compose.

SP Launcher replaces your phone's home screen with a calm, distraction-free one: a clean clock, your favourite apps as colourful text pills, small widgets, a full Study Manager, and a built-in **Focus Mode** that silences notifications and blocks distracting apps while you study.

## Download

**Latest: v1.5** — grab `app-debug.apk` from the [Releases](../../releases) page.

To install: download the APK, allow "install unknown apps" for your browser or file manager, and open the file.

## Features

- **Three-page home** — Settings · Home · App Drawer, swiped left and right.
- **Study Manager** — a Course > Subject > Topic > Class tree with deadlines, two-level reminders (a simple alert and a "deadline missed" nudge), per-topic study minutes and a colour-coded progress graph. Start a Focus session straight from a topic or class.
- **Focus Mode** — a floating Pomodoro timer that keeps running over other apps, silences notifications and blocks apps you haven't allowed. Session minutes are logged to the topic you were studying, and you get a one-tap "mark done" when a session ends.
- **Notes** — one swipeable Notes widget. Tag each item with Note / Reminder / Goal, or type your own custom tag.
- **Widgets** — clock & date, a Study "due today / overdue" card, a swipeable Tasks checklist, and Screen Time + Focused Time for today. Hide any widget from Settings.
- **Daily app limits** — a daily time budget per app, which resets every night at 23:59.
- **Themes** — Default, Pink, Green, Saffron and Seattle, each with a light and a dark (night) palette.
- **Backup & Restore** — export everything to a file and restore it, or let it auto-backup weekly to a folder you choose.
- **Daily study summary** — one notification a day with what's due, overdue and how long you studied.

## Support & Contact

- **WhatsApp:** [@somdatt.smiles](https://wa.me/somdatt.smiles) — support, feedback, bug reports.
- **GitHub:** [@sp-dev-22](https://github.com/sp-dev-22) — download more apps.
- **Support our project:** [github.com/sp-dev-22/splauncher](https://github.com/sp-dev-22/splauncher) — a star is appreciated.

## Tech

- Kotlin, Jetpack Compose, Material 3
- Single-module Android app (minSdk 24, targetSdk 36)
- All data is stored locally on the device (SharedPreferences) — no server, no account.

## Building an APK

A GitHub Actions workflow (`.github/workflows/build-apk.yml`) builds an installable **debug APK** on every push to `main`, and can also be run manually from the **Actions** tab.

## About the developer

- **Name:** Somdatt Prajapat
- **Age:** 22
- **Region:** Rajasthan, India
- **Language:** Hindi
- **Profession:** Student

## License

**All rights reserved.** This source code is published for viewing and reference only. No permission is granted to use, copy, modify, distribute or reuse it in any way. See [LICENSE](LICENSE) for the full notice.
