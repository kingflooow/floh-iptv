# Installing FLOH IPTV on a Samsung TV

*English · [Deutsch](ANLEITUNG-SAMSUNG.md)*

FLOH IPTV is a player for IPTV playlists (M3U) with a TV guide. It brings no channels: you
enter the playlist link of your own provider.

![Home screen](bilder/start.png)

## What you need

- A Samsung Smart TV from 2017 or later (Tizen).
- A Windows PC, Mac or Linux computer **or** an Android phone on the same Wi-Fi as the TV.
- A free Samsung account. The installer uses it to create the certificate for your TV.
- The file **FLOH-IPTV.wgt**: <https://github.com/kingflooow/floh-iptv/releases/latest/download/FLOH-IPTV.wgt>

## 1. Switch on developer mode on the TV (once)

1. Open **Apps** on the TV.
2. Press **1 2 3 4 5** on the remote, one after the other. Without number keys, use the on-screen
   number pad.
3. In the **Developer mode** window choose **On**.
4. Under **Host PC IP** enter the IP address of the PC or phone you install from.
   On a PC you find it under *Settings → Network*, on a phone under *Wi-Fi → Details*.
5. Restart the TV: hold the power key until it restarts.

## 2. Install FLOH IPTV

1. Download **Apps2Samsung**: <https://github.com/Apps2Samsung/Apps2Samsung/releases>
   (for Windows, Mac and Linux, and as an Android app).
2. Start Apps2Samsung and choose your TV.
3. Choose **custom .wgt** and pick the downloaded file `FLOH-IPTV.wgt`.
4. The first time, sign in with your Samsung account.
5. **Install**. FLOH IPTV is then in the TV's app list.

## 3. Enter your playlist

1. Open FLOH IPTV and press **OK**.
2. Enter your provider's playlist link. The app takes the TV guide (EPG) from the playlist;
   otherwise you can enter a guide link in the settings (**BLUE** key).

## Remote control

| Key | Does |
|---|---|
| OK | open the channel list, play a channel |
| Up / Down, CH+ / CH- | next / previous channel |
| Left / Right in the list | a whole page |
| YELLOW | favorite on/off |
| GREEN | favorites |
| BLUE | settings |
| BACK | hide the info bar, then Home; twice on Home: exit |

![Channel list](bilder/senderliste.png)
![TV guide](bilder/programm.png)

## Updates and notes

- Install an update the same way with the new file. Settings and favorites stay.
- After a big firmware update of the TV the app may disappear. Then simply install it again.
- If a channel freezes, the app reopens it by itself, then moves to another version or the next
  channel. You can change this in the settings.
