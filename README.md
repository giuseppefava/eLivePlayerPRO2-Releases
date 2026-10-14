# eLive Player PRO 2

**Free multimedia playback software for musicians, singers, karaoke hosts, DJs, and live entertainers — for Windows.**

[Official website](https://www.eliveplayer.com/) · [Download the full installer](https://www.eliveplayer.com/eLivePlayer-setup) · [GitHub Releases](https://github.com/giuseppefava/eLivePlayerPRO2-Releases/releases) · [Facebook community](https://www.facebook.com/eLiveSoftware/)

## About eLive Player PRO 2

eLive Player PRO 2 is a Windows application designed to make managing and playing backing tracks, MIDI files, karaoke songs, audio, and video easier during rehearsals and live performances. It combines media playback, setlist organization, on-screen lyrics, MIDI tools, and real-time sound controls in a single interface.

The program is **free to use, including for live performances**. Development is supported by voluntary donations; a registration code provided to supporters can shorten the startup screen. A paid license is not required for ordinary use.

## Key features

### Audio and video playback

- Play common audio formats, including **MP3, WAV, FLAC, OGG, OPUS, WMA, AIFF, and AIF**.
- Play **MIDI and KAR** files, **KFN** karaoke files, and video formats such as **MP4, AVI, and MKV**.
- Support **MP3 + CDG** karaoke pairs where the matching `.cdg` file is available.
- Change **pitch (transpose), tempo, and gain** while playing, without permanently changing the original media file.
- Prepare the next song while managing the current one, with playback and mixing controls intended for live use.

### Karaoke and lyrics

- Display synchronized lyrics where they are available in a supported file or metadata format.
- Use a dedicated karaoke view, including a **second-monitor** option for audiences or singers.
- Customize lyric presentation, including font, size, colors, layout, and background options.
- Work with several karaoke and lyric metadata conventions, including those used in supported MIDI, KFN, and audio files.

### MIDI and SoundFonts

- Play MIDI backing tracks with **SoundFont (SF2)** support.
- The **full SETUP** includes high quality General MIDI SoundFonts for getting started.
- Manage MIDI channels, instruments, banks, volume, pan, mute/solo, and effects such as reverb and chorus.
- Access MIDI input/output configuration and supported virtual-instrument options, depending on the installed hardware and plugins.

### Playlists and performance tools

- Create, save, rename, organize, reorder, and shuffle playlists.
- Browse local media folders, search for songs, and prepare a performance setlist.
- Adjust playback settings and manage audio mixing and crossfade options.
- View recognized musical chords with guitar- and piano-oriented displays.
- Use integrated performance utilities such as the sound-effects panel, loop controls, tuner, and audio equalization/DSP tools.

*Format and feature availability may depend on the type of media file, its embedded information, connected audio/MIDI devices, and installed plugins.*

## Download and installation

### New installation — full SETUP

If eLive Player PRO 2 is not already installed, use the **complete installer**:

**[Download eLivePlayerPRO2_SETUP.exe](https://www.eliveplayer.com/eLivePlayer-setup)**

The full installer provides the application, its required runtime components, and the essential MIDI SoundFonts. Run the installer on Windows and follow the on-screen instructions.

### Existing installation — UPDATE

If eLive Player PRO 2 is already installed, use **eLivePlayerPRO2_UPDATE.exe** when an update package is available for the new release:

**[UPDATE download page / link](https://www.eliveplayer.com/eLivePlayer-update)**

The UPDATE installer is designed to install into the **existing application directory** rather than create a new installation. It is intended to preserve existing SoundFonts, `config.ini`, license/registration information, and other user data that do not need to be replaced.

**Do not use the UPDATE package for a first-time installation.** Use the full SETUP instead.

Check [GitHub Releases](https://github.com/giuseppefava/eLivePlayerPRO2-Releases/releases) for the packages actually published with each version. Not every release necessarily includes both installers.

## Automatic update process

In supported versions, eLive Player PRO 2 checks online for newer releases without blocking normal startup. When an update is available:

1. The application notifies you and asks whether you want to update.
2. If you accept, the UPDATE installer is downloaded to a temporary location.
3. The download is checked against the **SHA-256 checksum** provided by the update manifest.
4. eLive closes through its normal shutdown procedure and launches the installer.
5. Follow the Inno Setup wizard to complete the update. The installer may offer to launch eLive again on the final screen.

Save your work and stop any active performance before applying an update. Although the UPDATE installer is designed to preserve user data, keeping a backup of important configuration files and custom SoundFonts is recommended.

## Free use and optional support

eLive Player PRO 2 is offered **free of charge**, including for performing live. The project is independently developed and supported by voluntary donations. Supporters may receive a registration code associated with a shorter startup experience.

For information about supporting development, visit [the official donation page](https://www.eliveplayer.com/donation/).

## Help and official links

- **Website:** https://www.eliveplayer.com/
- **Download page:** https://www.eliveplayer.com/download/
- **GitHub Releases:** https://github.com/giuseppefava/eLivePlayerPRO2-Releases/releases
- **Facebook:** https://www.facebook.com/eLiveSoftware/
- **YouTube:** https://www.youtube.com/@eLiveSoftware/

For download or installation problems, confirm that you are using a package from an official link and that it is appropriate for either a new installation or an existing one. Windows may display a security or reputation warning for downloaded executables; review the file and its source before deciding whether to run it.

## About this repository

This repository is the **official distribution location for eLive Player PRO 2 Windows releases**. It contains release information and downloadable installer packages. It is not presented as a source-code repository.

**Developed by Giuseppe Fava / eLive Software.**

© 2018–2026 Giuseppe Fava. Refer to the license terms accompanying the installer for conditions of use.
