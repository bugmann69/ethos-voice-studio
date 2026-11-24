# ETHOS Voice Studio

An offline Linux desktop application for creating spoken announcements, sound effects, and voice packs for FrSky transmitters running ETHOS. Independent project; not affiliated with or endorsed by FrSky.

## Download

**[Download version 0.8.0](https://github.com/bugmann69/ethos-voice-studio/releases/tag/v0.8.0)**

Choose `ethos-voice-studio_0.8.0_amd64.deb` under Assets. The installer is approximately 579 MiB and includes starter Piper and Kokoro voices. This is a development release.

## Install on Linux

For 64-bit Intel/AMD Linux Mint 22 / Ubuntu 24.04 systems. Open the Debian package in your software installer, or run from its download folder:

```bash
sudo apt install ./ethos-voice-studio_0.8.0_amd64.deb
```

Internet may be needed to install system dependencies. Once installed, the included voices and sound effects work offline. Launch ETHOS Voice Studio from your application menu. Close an older running copy before upgrading. Personal libraries, packs and settings are not included in the installer.

## Features

- Simple and Advanced interfaces.
- Searchable sound library with playback and multi-file pack transfers.
- Offline speech with Piper, Kokoro and eSpeak NG.
- Individual and batch generation with automatic filenames.
- Sound Effect Maker: beeps, chimes, warning pulses, sweeps and sirens.
- Voice packs with multiple voices, categories and pronunciation settings.
- Installation preview, local backups, hash verification and automatic ejection of the radio’s associated SD/FLASH volumes.

## First use

1. Choose or create a voice pack.
2. Import recordings, generate speech, or make sound effects and add them to the pack.
3. Connect the radio, detect storage, and review the installation preview.
4. Confirm installation and keep USB connected until **Safe to disconnect** appears.
5. On the radio, open **System → General → Audio** and assign your pack to Voice 2 or 3 for custom announcements. Keep your working main voice.

Back up your radio before first use. Compatibility and playback should be checked on your transmitter and firmware. Version 0.8.0 passed 83 automated tests plus GUI and packaged-app checks; new sound effects have not been qualified on physical hardware.

## Source and licenses

The release includes `ethos-voice-studio-0.8.0-source.tar.gz` with application source, tests, setup/build scripts and documentation, plus `SHA256SUMS-0.8.0` for verification. Use that source archive rather than GitHub’s automatically generated archive of this download-page repository.

Application source is GPL-3.0-or-later. Bundled engines, libraries and voice models have their own licenses; see LICENSE and NOTICE in the source archive and the notices installed with the application.

## Feedback

Please [open an issue](https://github.com/bugmann69/ethos-voice-studio/issues) with your app version, Linux version, transmitter model, ETHOS firmware version and steps to reproduce the problem. Do not include private radio backups or personal data.
