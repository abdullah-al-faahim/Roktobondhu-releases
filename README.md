# রক্তবন্ধু · Roktobondhu — Android releases

Roktobondhu connects blood donors with patients' families in Bangladesh on a live OpenStreetMap map. Donor locations stay approximate (about 500 m) until a donor accepts a request, and phone numbers are shared only after accept.

This repository hosts the Android builds. Source code is kept in a separate repository.

## Download

Get the latest APK from [Releases](../../releases/latest).

| File | For |
| --- | --- |
| `roktobondhu-<version>-arm64-v8a.apk` | Most phones from 2017 onward (pick this one if unsure) |
| `roktobondhu-<version>-armeabi-v7a.apk` | Older 32-bit phones |
| `roktobondhu-<version>-universal.apk` | Any phone (larger download) |

`SHA256SUMS.txt` lists checksums for each file.

## Install

1. Download the APK on your Android phone (Android 7.0 or newer).
2. Open it and allow "Install unknown apps" for your browser or file manager when asked.
3. Open Roktobondhu, choose বাংলা or English.

## Current builds are demos

Builds in this repository run in **demo mode**: they use sample donors, hospitals and requests stored only on your phone, and nothing is sent to a server.

- Sign in with any Bangladeshi mobile number and the code `123456`.
- About 20 seconds after setup you receive a sample request alert.
- If you post a request, a sample donor accepts it and you can watch them travel to the hospital.

The APKs are signed with a development key, so Android may warn about an unknown developer. They are not on the Play Store yet.

## Map data

© OpenStreetMap contributors, tiles by OpenFreeMap. Optional satellite view: Sentinel-2 cloudless by EOX IT Services GmbH (2016 mosaic, CC BY 4.0).
