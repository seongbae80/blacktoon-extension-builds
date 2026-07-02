# BlackToon Extension Build

Hermes/Codex-assisted BlackToon extension debug APK build.

## Install APK

```text
apk/tachiyomi-ko.blacktoon-v1.4.2-debug.apk
```

## Source changes

See `patches/blacktoon-v1.4.2.patch`.

## Notes

- Target extension only: `src/ko/blacktoon`
- `versionCode`: 1 -> 2
- `baseUrl`: `https://blacktoon.me` -> `https://blacktoon415.com`
- Build command: `./gradlew src:ko:blacktoon:assembleDebug`
