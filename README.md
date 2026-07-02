# BlackToon Extension Build Repo

## Extension repository URL

Use this as the extension repo/index URL:

```text
https://raw.githubusercontent.com/seongbae80/blacktoon-extension-builds/main/repo/index.min.json
```

Full index:

```text
https://raw.githubusercontent.com/seongbae80/blacktoon-extension-builds/main/repo/index.json
```

Direct APK:

```text
https://raw.githubusercontent.com/seongbae80/blacktoon-extension-builds/main/repo/apk/tachiyomi-ko.blacktoon-v1.4.2-debug.apk
```

## Notes

- Target extension only: `src/ko/blacktoon`
- `versionCode`: 1 -> 2
- `baseUrl`: `https://blacktoon.me` -> `https://blacktoon415.com`
- Build command: `./gradlew src:ko:blacktoon:assembleDebug`
