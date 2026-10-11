# PragmaticAudio Lossless

**Bit-perfect streaming to your speakers and headphones.** Play from Plex, your network shares, DLNA servers, local files
or (on Mac, Windows, Android and iOS 27) everything your device plays, to AirPlay 1 and 2 speakers, DLNA players and
Chromecast. The app shows exactly what happens to the music on the way: **green** when it arrives untouched
(bit-perfect), **orange** when it had to be converted once, **red** when the source is lossy or it was converted twice.
Made by [Pragmatic Audio](https://www.pragmaticaudio.com/).

This repository holds the **downloads** (see [Releases](../../releases)). The source is not published here.

## What it does

- **Finds your speakers** and shows what each one really takes: AirPlay version, formats, sample rates and bit depths,
  pairing and PIN. Pick a route and format yourself, or let it choose the best lossless one.
- **Plays your music** from Plex (linked with a 4-character code, like a TV), SMB network shares (pin your folders),
  DLNA servers and local FLAC/WAV files, with pause, stop, next and previous.
- **Explains the chain**: source → any conversion → the receiver, with the one conversion done here, carefully, when it
  is unavoidable (AirPlay tops out at 48 kHz / 24-bit).
- **DSP corrections per device**: bass & treble, or AutoEQ / Equalizer APO `Filters.txt` for left and right.
- **Live views**: spectrum, meters, VU and more, analysed only while open.

## Downloads

Early releases: please try them and report what you find in [Issues](../../issues).

| Platform | Get it | Status |
|---|---|---|
| **macOS** (macOS 14 or newer) | the `.dmg` in the latest [`macos-v*` release](../../releases) | Signed and notarised by Apple. |
| **Windows 11** | the `Setup.exe` in the latest `windows-v*` release | Coming soon. |
| **Android** | the `.apk` in the latest `android-v*` release | Coming soon. |
| **iPhone and iPad** | TestFlight | Coming soon. |

### Installing on macOS

1. Open the `.dmg` and drag **PragmaticAudio Lossless** to Applications.
2. To send everything the Mac plays, the app can install its audio driver, a virtual output called
   **PragmaticAudio Lossless** (macOS asks for an administrator password). Playing from Plex, shares, DLNA or files
   needs no driver.
3. Allow **Local Network** access when macOS asks: it is how the app finds and reaches your speakers.
