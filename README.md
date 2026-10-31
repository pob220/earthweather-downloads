# Earthweather downloads

[Earthweather 1.10.0 — Windows x64 and Android](https://github.com/pob220/earthweather-downloads/releases/tag/v1.10.0).

- **Windows desktop:** [download the standalone x64 installer](https://github.com/pob220/earthweather-downloads/releases/download/v1.10.0/Earthweather-Setup-1.10.0-windows-x64.exe). Includes Desktop and Start menu shortcuts. No separate Python, Node.js or data server is needed. [Windows guide](https://github.com/pob220/earthweather-downloads/releases/download/v1.10.0/INSTALL-WINDOWS.md).
- **Android tablet:** [download the signed ARM64 APK](https://github.com/pob220/earthweather-downloads/releases/download/v1.10.0/earthweather-1.10.0-arm64.apk), install over the existing app, and launch **Earthweather**. No PC or companion server is needed. [Android guide](https://github.com/pob220/earthweather-downloads/releases/download/v1.10.0/INSTALL-ANDROID.md), [device validation](https://github.com/pob220/earthweather-downloads/releases/download/v1.10.0/ANDROID-VALIDATION.md).
- **Linux:** desktop and browser/service installers remain in [the 1.8.0 release](https://github.com/pob220/earthweather-downloads/releases/tag/v1.8.0), with its distribution-specific installation guides.

Windows and Android 1.10.0 include their native C++ front detector, required GEBCO/NASA geography, place names, global bathymetry, Anglesey detail and prepared coastlines. Forecasts and observations need an initial internet connection; saved products and geographic layers remain available offline. The optional NASA imagery upgrade is downloaded in the app and retained locally.

**New in 1.10:** choose **Colour overlay → Air temperature · 2 m** for a Celsius map over land and sea, with a fixed scale, freezing marker, strength control and the selected forecast time. [Temperature guide](https://github.com/pob220/earthweather-downloads/releases/download/v1.10.0/TEMPERATURE.md).

The appearance pane can be moved and minimised. The preset destination panel has been removed to leave more room for the globe. Show-position and centre-position controls remain available; Android supports device location and Wi-Fi NMEA with device fallback.

The Windows installer is unsigned. Download `SHA256SUMS` from the same release to verify files. Dataset attribution, licences and build provenance accompany the release. Private XTD models and account credentials are not distributed. Fronts retain their experimental model-derived status; platform qualifications and numerical comparisons are documented with the release.

The 1.10.0 Android package was built and its shared renderer checked at desktop and tablet browser sizes. It has not yet had a new physical-tablet test; the last physical-device qualification is 1.9.0. See the accompanying validation notes.
