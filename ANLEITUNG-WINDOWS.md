# FLOH IPTV unter Windows installieren

*[English](INSTALL-WINDOWS.md) · Deutsch*

FLOH IPTV ist ein Player für IPTV-Playlists (M3U) mit Programmführer. Die App
bringt keine Sender mit: Du trägst den Playlist-Link deines eigenen Anbieters ein.

Läuft unter Windows 10 und 11 (64 Bit), mit Maus und Tastatur.

![Startseite](bilder/firetv-startseite.png)

## Installieren

1. Herunterladen: [FLOH-IPTV-windows.zip](https://github.com/kingflooow/floh-iptv/releases/latest/download/FLOH-IPTV-windows.zip)
   (kurz: `kingflooow.github.io/floh-iptv/windows`).
2. Rechtsklick auf die ZIP-Datei → **Alle extrahieren…** → einen Ordner wählen, zum Beispiel
   *Dokumente*. Es entsteht der Ordner **FLOH IPTV**.
3. Im Ordner **FLOH IPTV.exe** doppelklicken.
4. Beim ersten Start zeigt Windows eventuell „Der Computer wurde durch Windows geschützt“:
   **Weitere Informationen** → **Trotzdem ausführen**. Das kommt, weil die App neu und nicht
   kostenpflichtig signiert ist.

Tipp: Rechtsklick auf **FLOH IPTV.exe** → **Weitere Optionen anzeigen** → **Senden an** →
**Desktop (Verknüpfung erstellen)**, dann startet die App vom Desktop aus.

## Playlist eintragen

1. FLOH IPTV öffnen und auf den Bildschirm klicken (oder **Enter** drücken).
2. Auf *Playlist link* klicken, den Link deines Anbieters einfügen (**Strg + V**) und **Enter**
   drücken.
3. **Esc** drücken: die Senderliste lädt. Das Programm (EPG) holt sich die App aus der Playlist,
   sonst kannst du den EPG-Link in den Einstellungen eintragen.

Zum Ausprobieren ohne eigene Liste: `https://kingflooow.github.io/floh-iptv/demo.m3u`

## Bedienung

Mit der Maus:

| | Wirkung |
|---|---|
| Zeigen | wählt aus |
| Klick | öffnen, Sender abspielen |
| Mausrad | Liste oder Reihe blättern |
| Rechtsklick | zurück |
| Klick aufs Video | Senderliste |
| Doppelklick aufs Video | Vollbild an / aus |

Mit der Tastatur:

| Taste | Wirkung |
|---|---|
| Pfeiltasten, Enter | auswählen, öffnen |
| Esc oder Rücktaste | zurück; auf der Startseite zweimal: beenden |
| Bild auf / Bild ab | nächster / vorheriger Sender |
| 0–9 | Sendernummer |
| I | Infoleiste |
| P | letzter Sender |
| Y | Favorit an / aus |
| G | Favoriten |
| R | Playlist neu laden |
| B | Einstellungen |
| F11 oder Alt + Enter | Vollbild an / aus |

## Updates

Die neue ZIP-Datei genauso entpacken und den alten Ordner **FLOH IPTV** ersetzen.
Einstellungen und Favoriten bleiben erhalten (sie liegen nicht im Programmordner).

## Wenn die App nicht startet

FLOH IPTV braucht die *Microsoft Edge WebView2 Runtime*. Sie ist in Windows 11 und in
aktuellem Windows 10 enthalten. Fehlt sie, zeigt die App einen Hinweis mit dem Link zum
kostenlosen Download bei Microsoft.

Der Videoplayer in der App ist [mpv](https://mpv.io) (LGPL); Lizenzen und Quellen stehen im
Ordner *licenses*.
