# Pomodoro

Personal Flutter practice project (the repo's own description: a way to learn Flutter by building a Pomodoro timer; commits from January 2023 to April 2024). It is a small app, not a finished product.

![cover](cover.jpg)

## What it does

- Onboarding screens (`introduction_screen`), then a home screen with a fixed 25-minute countdown (`twentyFiveMin = 1500` s in `lib/ui/page/home_screen.dart`), start/pause, and a completed-session counter.
- Rotating "work hard" quotes loaded from `assets/workHardQuote.json`.
- Visual design follows the [POMO UIKIT](https://www.behance.net/gallery/98918603/POMO-UIKIT) design on Behance.
- Not implemented: configurable durations, break timers.

## How to run

```
flutter pub get
flutter run
```

Needs a Flutter SDK compatible with `sdk: '>=2.18.6 <3.0.0'` in `pubspec.yaml` (Dart 2.x era, early 2023); newer SDKs may need dependency upgrades. I did not build the app when tidying this repo.
