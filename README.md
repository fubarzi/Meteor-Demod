# Meteor Demod

Meteor Demod is a Windows desktop receiver for Meteor M2-3 and M2-4 LRPT weather satellite imagery. It supports RTL-SDR V3/V4, Airspy, and HackRF, with a live spectrum and waterfall, satellite tracker, image viewer, and post-processing controls.

## Download

Get the Windows installer or portable ZIP from the [latest release](https://github.com/fubarzi/Meteor-Demod/releases/latest).

- **Installer:** `MeteorDemod-Setup-1.0.31.exe`
- **Portable:** `MeteorDemod-Portable-1.0.31.zip` — extract it and run `MeteorDemod.exe`.

The portable ZIP includes the full usage guide in `README.md`. Set your own station grid and receiver after opening the app. A 137 MHz weather satellite antenna and supported SDR are required for reception.

## Image proportions

In the Images tab, press **WIDEN IMAGE** beside Equalize image channels to double a narrow image's width. Press it again to return to the original view. **Save a Copy** and **Crop** use the widened image; the original decode stays unchanged.

## Checksums

| File | SHA-256 |
| --- | --- |
| `MeteorDemod-Setup-1.0.31.exe` | `E41A4AD90B0290B099BCFD24742E2CC9C8C8367C947608FD8AC75AF7553BBC3D` |
| `MeteorDemod-Portable-1.0.31.zip` | `97A683CC9102B76856A58B08A01F8157702BF8D22D4242D417FB4AC8207A36AD` |

The release packages include SatDump 1.2.2 and its license and source archive. This repository currently distributes the Windows build.
