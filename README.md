# XivCinema

**The player for players.** Watch videos with your party in Final Fantasy XIV, in sync, on a big screen standing in the game world or in a floating window.

This repository hosts XivCinema's releases for Dalamud's plugin installer.

## Install

1. In game, open Dalamud's settings (`/xlsettings`) → **Experimental** → **Custom Plugin Repositories**.
2. Add this URL, tick **Enabled**, and save:

   ```
   https://raw.githubusercontent.com/jeffrick-cloud/XivCinema-releases/main/repo.json
   ```

3. Open the plugin installer (`/xlplugins`), search for **XivCinema** and install it.

The video player comes inside the plugin; nothing else to install.

## Join a watch party

When the host pastes an invite into party chat, a **[Join watch party]** link appears under it. Click it. If it doesn't show, paste the whole `XivCinema invite: wss://…` line into **Watch Party → Join** in the XivCinema window (`/cinema`).

| Command | What it does |
| --- | --- |
| `/cinema` | Open or close the XivCinema window |
| `/cinema place` | Stand the 3D screen in front of you |
| `/cinema host` | Start hosting a watch party |
| `/cinema stop` | Stop hosting, leave the party, or stop the video |

> XivCinema is a third-party Dalamud plugin. It is not affiliated with or endorsed by Square Enix.

## Third-party software

- [VLC](https://www.videolan.org/vlc/) 3.0.24 (libVLC and plugins; LGPL 2.1 or later, some plugins GPL), from the `VideoLAN.LibVLC.Windows` package. Source: [code.videolan.org](https://code.videolan.org/videolan/vlc).
- [LibVLCSharp](https://code.videolan.org/videolan/LibVLCSharp) 3.9.7.1 (LGPL 2.1).
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) (Unlicense), downloaded by the plugin at runtime, not bundled.
