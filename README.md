# libmitoming-logger
The library supports exporting logcat to a file named `debug-android app.txt` for analyzing Android application errors.
# LibMitoMing Logger

## Purpose
This library supports writing Android application logcats to a `debug-androidapp.txt` file in device storage for debugging purposes.

## Scope of Use
- For debugging and application development purposes only.

- Not for cheating, hacking, or illegal activities.

## Platform
- Android (ARM64 / x86_64)
- Requires write permission to external storage (`WRITE_EXTERNAL_STORAGE` or `MANAGE_EXTERNAL_STORAGE` depending on Android version)

## How to Use
1. Download `libmitoming.zip` from the **Releases** folder.

2. Extract to get `libmitoming.so`.

3. Embed it into your Android application.

 4. The log file will be recorded at `/storage/emulated/0/debug-androidapp.txt`.

## Disclaimer
The author is not responsible for any misuse.