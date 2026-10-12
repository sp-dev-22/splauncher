# SP Launcher

A minimalist, student-friendly Android launcher — built with Kotlin and Jetpack Compose.

SP Launcher replaces your phone's home screen with a calm, distraction-free one: a clean clock, your favourite apps as colourful text pills, small Notes / Reminders / Goals / Tasks widgets, and a built-in **Focus Mode** that silences notifications and blocks distracting apps while you study.

## Features

- **Three-page home** — Settings · Home · App Drawer, swiped left and right.
- **Focus Mode** — a floating Pomodoro timer that keeps running over other apps, silences notifications, and blocks apps you have not allowed.
- **Daily app limits** — set a daily time budget per app; when it runs out, the app is locked for the day.
- **Widgets** — clock and date, plus swipeable Notes, Reminders and Goals cards and a Tasks checklist.
- **Badges & focus history** — milestones for your study sessions, and a log of past sessions.

## Tech

- Kotlin, Jetpack Compose, Material 3
- Single-module Android app (minSdk 24, targetSdk 36)
- All data is stored locally on the device (SharedPreferences) — no server, no account.

## Building an APK

A GitHub Actions workflow (`.github/workflows/build-apk.yml`) builds an installable **debug APK** on every push to `main`, and can also be run manually from the **Actions** tab. The APK is attached to the `apk-latest` release for a direct download.

To install: download `app-debug.apk`, allow "install unknown apps" for your browser or file manager, and open the file to install.

## About the developer

- **Name:** Somdatt Prajapat
- **Age:** 22
- **Region:** Rajasthan, India
- **Language:** Hindi
- **Profession:** Student

## License

**All rights reserved.** This source code is published for viewing and reference only. No permission is granted to use, copy, modify, distribute or reuse it in any way. See [LICENSE](LICENSE) for the full notice.
