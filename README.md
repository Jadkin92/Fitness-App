# HeavyMetal Workouts

A mobile-first workout tracker packaged for Android with Capacitor. The app includes strength routines, a workout session logger, rest timer, weekly activity, and a local training history.

## Requirements

- Node.js 20 or newer
- Android Studio with the Android SDK installed

## Get started

```sh
npm install
npm run dev
```

## Android

The Android Studio project is in `android/`. To rebuild the web app and copy it into the native project, run:

```sh
npm run android:sync
```

Then open the Android project with:

```sh
npm run android:open
```

To run on an attached device or emulator from Android Studio, select the `app` run configuration. Workout data is currently stored locally on the device; cloud sync and account features are not included.