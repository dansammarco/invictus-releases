# Invictus

A personal investment-research app: type a ticker and Claude builds a full company model from the SEC filings.

This repository holds only the signed builds. **Download the newest one from [the latest release](https://github.com/dansammarco/invictus-releases/releases/latest).**

| | Download | Then |
|---|---|---|
| **Windows** 10 or 11 | `Invictus-<version>.zip` | Unzip it anywhere (Documents is a good place) and open `Invictus.exe`. The first time, Windows may say it protected your PC (Invictus isn't signed): click **More info**, then **Run anyway**. |
| **Mac** with Apple Silicon (M1 or newer), macOS 11+ | `Invictus-MacOS-<version>.zip` | Double-click to unzip, do the one-time step below, then open `Invictus.app`. |

## First open on a Mac

Invictus isn't signed by Apple, so macOS marks a downloaded copy as unverified and would run it from a temporary place,
away from its folder. Once, before the first open:

1. Open **Terminal**.
2. Type `xattr -dr com.apple.quarantine ` (with a space at the end).
3. Drag the unzipped Invictus folder into the Terminal window and press **Return**.

Then double-click `Invictus.app`. Updates afterwards need nothing.

## Updates

Invictus checks this page for a newer version while it runs. When there is one, the top of the window shows
**Update to x.y.z**: click it, read what's new, then **Update and Restart**. It never updates without your click, and
your models, settings and history (the `Data` folder) are never touched. Every download is checked against Invictus's
signing key before it is installed.

## Moving models between computers

On a model's Front Page, **More, Export Package** makes one `.invictus` file you can email or share through OneDrive.
On the other computer, **Open Package** (on Home, or in Settings) shows what it holds before anything changes, and
asks before replacing a model you already have. Packages open on Windows and Mac alike.
