# Wabash Rider — test builds

These are **test builds** of the Wabash Rider (Terre Haute bus) Android app for sideloading only.
They are **not** the Play Store version and are signed with a test key.

## Latest: v1.0.0-test2 (versionCode 2)

Get the APKs from the [v1.0.0-test2 release](https://github.com/jaywestmarketing/wabashrider-test-builds/releases/tag/v1.0.0-test2):

- [`wabashrider-1.0.0-test2-universal.apk`](https://github.com/jaywestmarketing/wabashrider-test-builds/releases/download/v1.0.0-test2/wabashrider-1.0.0-test2-universal.apk): any phone (32-bit or 64-bit), ~103 MB
- [`wabashrider-1.0.0-test2-arm64.apk`](https://github.com/jaywestmarketing/wabashrider-test-builds/releases/download/v1.0.0-test2/wabashrider-1.0.0-test2-arm64.apk): 64-bit Android only, ~34 MB

What's in test2:

- **Uninstall test1 first** (Settings > Apps > Wabash Rider > Uninstall), then install test2.
- Targets Android 16 (API 36); needs Android 7 or newer.
- Real Terre Haute Transit routes, stops and scheduled times from the official THTU GTFS feed (valid through Jan 1, 2027). Times are scheduled, not live GPS.
- Place search (addresses, businesses, landmarks) with the nearest stops works through bus.reale.one. Stop and route search also works offline.
- **No map yet:** the Map tab shows the nearest stops instead, until a Google Maps key is added.

SHA-256:

```
665d045c6f5ad7b2b7923d9b7ca5eb64f4d810a858236815913a8a6e473eebbe  wabashrider-1.0.0-test2-universal.apk
b7fa17e59ce35d39b5d17364a05a1a2d1b5ddf5b4a9134d2ed6d0008297781b0  wabashrider-1.0.0-test2-arm64.apk
```

## Older: v1.0.0-test1

Get the APKs from the [v1.0.0-test1 release](https://github.com/jaywestmarketing/wabashrider-test-builds/releases/tag/v1.0.0-test1):

- `wabashrider-1.0.0-test-arm64.apk` — 64-bit (arm64-v8a) phones, ~25 MB
- `wabashrider-1.0.0-test-universal.apk` — any phone (32-bit or 64-bit), ~63 MB

## Sideload steps

1. Open the APK link on the phone in Chrome and download it (tap "Download anyway" if warned).
2. If an older Wabash Rider is installed, uninstall it first (Settings > Apps > Wabash Rider > Uninstall).
3. Tap the downloaded file. If asked, allow installs from this source (Chrome) in Settings, then go back.
4. If Play Protect warns about an unknown developer, tap "More details" > "Install anyway".
5. Tap Install, then Open.

Uninstall this test build before installing a future Play Store version.

## SHA-256 (test1)

```
7e6ca00f4151a8bf7ebb2ef32eab62019709890292fb3d36f8ad94e5e1e31b87  wabashrider-1.0.0-test-arm64.apk
4fe23b38a15a8d1fade918bd2aa53a910f1838bc4e345b26acbeecfd6df1305c  wabashrider-1.0.0-test-universal.apk
```
