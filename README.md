# Manu's Editing

A Flutter Android video editor starter project.

## Build locally

```bash
flutter pub get
flutter build apk --release
```

The release APK will be generated at:

`build/app/outputs/flutter-apk/app-release.apk`

## GitHub Actions

Push this project to GitHub. The workflow in `.github/workflows/android.yml`
builds the release APK automatically and uploads it as a workflow artifact.
