# Installing FLOH IPTV on Windows

*English · [Deutsch](ANLEITUNG-WINDOWS.md)*

FLOH IPTV is a player for IPTV playlists (M3U) with a TV guide. It brings no channels: you
enter the playlist link of your own provider.

Runs on Windows 10 and 11 (64-bit), with mouse and keyboard.

![Home screen](bilder/firetv-startseite.png)

## Install

1. Download [FLOH-IPTV-windows.zip](https://github.com/kingflooow/floh-iptv/releases/latest/download/FLOH-IPTV-windows.zip)
   (short: `kingflooow.github.io/floh-iptv/windows`).
2. Right-click the ZIP file → **Extract All…** → choose a folder, *Documents* for example.
   This creates the folder **FLOH IPTV**.
3. In that folder, double-click **FLOH IPTV.exe**.
4. The first time, Windows may show "Windows protected your PC": **More info** → **Run anyway**.
   It does so because the app is new and not signed with a paid certificate.

Tip: right-click **FLOH IPTV.exe** → **Show more options** → **Send to** → **Desktop (create
shortcut)** to start the app from the desktop.

## Entering your playlist

1. Open FLOH IPTV and click the screen (or press **Enter**).
2. Click *Playlist link*, paste your provider's link (**Ctrl + V**) and press **Enter**.
3. Press **Esc**: the channel list loads. The app takes the TV guide (EPG) from the playlist;
   otherwise you can enter a guide link in the settings.

To try it without a list of your own: `https://kingflooow.github.io/floh-iptv/demo.m3u`

## Using it

With the mouse:

| | Does |
|---|---|
| Point | selects |
| Click | opens, plays a channel |
| Wheel | scrolls a list or row |
| Right-click | back |
| Click on the video | channel list |
| Double-click on the video | full screen on / off |

With the keyboard:

| Key | Does |
|---|---|
| Arrow keys, Enter | select, open |
| Esc or Backspace | back; twice on Home: exit |
| Page Up / Page Down | next / previous channel |
| 0–9 | channel number |
| I | info bar |
| P | last channel |
| Y | favorite on / off |
| G | favorites |
| R | reload the playlist |
| B | settings |
| F11 or Alt + Enter | full screen on / off |

## Updates

Unzip the new ZIP file the same way and replace the old **FLOH IPTV** folder.
Settings and favorites stay (they are not kept in the program folder).

## If the app does not start

FLOH IPTV needs the *Microsoft Edge WebView2 Runtime*, which comes with Windows 11 and current
Windows 10. If it is missing, the app shows a note with the link to the free download from
Microsoft.

The video player inside the app is [mpv](https://mpv.io) (LGPL); licences and sources are in the
*licenses* folder.
