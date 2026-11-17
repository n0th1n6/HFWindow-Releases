# HF Window

HF propagation planning for Android.

## Download

[Download HF Window 1.0.4 APK](https://github.com/n0th1n6/HFWindow-Releases/releases/download/v1.0.4/HF-Window-1.0.4-release.apk)

[All releases](https://github.com/n0th1n6/HFWindow-Releases/releases)

Android 8.0 or newer with a current Android System WebView is required. This is a non-debuggable release build signed with the dedicated HF Window certificate. Install it with the Android package installer. **If you installed a testing APK through 1.0.3, uninstall that app first:** its debug signature differs, and uninstalling removes its saved settings. Future release APKs signed with the same release certificate can update 1.0.4 normally.

## Features

- Seven-day HF planning outlook with ranked operating windows.
- Eight amateur HF bands from 80 m through 10 m.
- Transmitting and listening coordinates, path distance and bearing.
- Country labels, map zoom/pinch, panning, and exact map-point selection.
- Country-name shortcuts to capital or administrative-seat coordinates.
- Saved station settings, NOAA solar flux/Kp refresh, manual offline scenarios, and CSV export.

## Prediction limits

Scores are experimental relative planning estimates, not contact probabilities or calibrated VOACAP forecasts. Solar flux is held constant; times beyond available NOAA Kp coverage use the manual scenario. Verify conditions on the air.

## About this repository

This public repository distributes APK binaries, checksums and release information. Application development is maintained in a separate private repository. The APK is a hybrid application and includes its bundled HTML, JavaScript and map assets.

Map and base capital coordinates: [Natural Earth](https://www.naturalearthdata.com/). Space-weather data: [NOAA SWPC](https://www.swpc.noaa.gov/).
