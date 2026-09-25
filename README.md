# TraceStamp Camera downloads

This public repository hosts **official Android APK releases** of TraceStamp Camera. The app is free and ad-free. Application source code and signing material are kept in a separate private repository.

## Download

[Open the latest release and download the APK](https://github.com/ajay-develops/tracestamp-camera-releases/releases/latest).

Use Android 10 or newer. Download the `.apk` asset, open it on your device, and allow installation from your browser or file manager when Android asks. This is a direct-download release; it is not in Google Play yet.

Each release includes a `.sha256` file. To check a downloaded file on macOS or Linux, keep the APK and checksum in the same folder and run:

```sh
shasum -a 256 -c TraceStamp-Camera-v0.1.0.apk.sha256
```

## v0.1.0

TraceStamp saves photos and videos with a visible date and time. You can add a custom text line, choose a stamp corner, use front or rear camera, and optionally include current GPS coordinates. GPS starts off and asks for permission separately. Captures stay on your device; the app has no account, ads, analytics, backend or network permission.

The APK was tested on a Pixel 8a. It has not been submitted to an app store, and it has not been tested across a broad device range. See the release notes for the exact feature and test list.

For an update, install the newer APK over the older one. Keep downloads from this repository so the signing identity remains consistent.
