# FPS-project-X — Neon Range

A lightweight, mobile-friendly fictional sci-fi first-person arcade prototype. It runs as a static website and can be wrapped as an Android app with Capacitor.

## Play
Open `index.html` in a modern browser. On mobile, use the direction pad to move, drag the scene to look around, and tap glowing drones to score. On desktop, use WASD or arrow keys to move and click targets.

## Publish with GitHub Pages
1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for the deployment; the published URL will appear on the Pages settings screen.

On GitHub Free, Pages requires a public repository. The entry file `index.html` is at the repository root.

## Android APK
The GitHub Actions workflow can build a debug APK manually. Open **Actions → Build Android APK → Run workflow**. After it succeeds, open that run and download the `fps-project-x-debug-apk` artifact. Extract the downloaded ZIP to get the APK. Debug APKs are for testing, not Play Store release.

## Notes
- Early prototype; not a finished commercial game.
- No external images, sounds, or game-engine downloads are required.
- Never commit passwords, API keys, or signing keys to the repository.
