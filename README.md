# Meteor Demod

Meteor Demod is a Windows desktop receiver for Meteor M2-3 and M2-4 LRPT weather satellite imagery. It supports RTL-SDR V3/V4, Airspy, and HackRF, with a live spectrum and waterfall, satellite tracker, image viewer, and post-processing controls.

## Download

Get the Windows installer or portable ZIP from the [latest release](https://github.com/fubarzi/Meteor-Demod/releases/latest).

- **Installer:** `MeteorDemod-Setup-1.0.34.exe`
- **Portable:** `MeteorDemod-Portable-1.0.34.zip` — extract it and run `MeteorDemod.exe`.

The portable ZIP includes the full usage guide in `README.md`. Set your own station grid and receiver after opening the app. A 137 MHz weather satellite antenna and supported SDR are required for reception.

## Images and mosaics

In the Images tab, **WIDEN IMAGE** doubles a narrow image's width and fits the whole widened result in the viewer. The widened shape stays consistent as you zoom or resize, and the button stays selected when you switch images. **Save a Copy** and **Crop** use the widened result; the original decode remains unchanged.

Saved mosaics offer **Auto Contrast**, **Vivid Colour**, **Sharpen**, and **Black & White** directly from the saved image, including older mosaics whose original decoded passes are unavailable. Channel-based looks remain available when their source passes and required channels are present. If you select another pass-based look while one is processing, the latest selection runs next.

## Checksums

| File | SHA-256 |
| --- | --- |
| `MeteorDemod-Setup-1.0.34.exe` | `F05666314E87C7EF53E44ED15EE6605EA861A154A0B87EEE9149C89864D54213` |
| `MeteorDemod-Portable-1.0.34.zip` | `EA25A075835FBDA5F788707292F450CFE5987B4C5582DA386301BE1F41FDD01C` |

The release packages include SatDump 1.2.2 and its license and source archive. This repository currently distributes the Windows build.
