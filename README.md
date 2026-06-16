# Belseh Updates

Public update files for the Belseh Android app.

## Live Files

- Update manifest: `https://raw.githubusercontent.com/BenjaminMisheto/belseh-updates/main/update.json`
- Update builder page: `https://benjaminmisheto.github.io/belseh-updates/`

## Release Flow

1. Build a new APK with a higher Android versionCode.
2. Upload the APK to a GitHub Release.
3. Update `update.json` with the release APK URL, SHA-256 hash, size, version name, and version code.
4. Push `update.json` to `main`.

The app reads `update.json` when the user taps **Check update**.
