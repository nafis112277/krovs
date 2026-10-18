# Food Fashion — Android shell (APK build only)

Minimal Capacitor project. The app loads the hosted website set in
`capacitor.config.ts` (`server.url`), so no web source is needed here.

## Build the APK on GitHub

1. Push this folder's contents to a GitHub repo (keep the `.github` folder).
2. Repo -> **Actions** -> **Build Android APK** -> **Run workflow**.
3. When it finishes, download `food-fashion-debug-apk` from the run's **Artifacts**.

## Before a Play Store release

- Set `server.url` in `capacitor.config.ts` to the published production URL.
- Debug APK is for testing; Play needs a signed release (AAB).
