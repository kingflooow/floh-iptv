# FLOH IPTV auf einem Samsung-Fernseher installieren

FLOH IPTV ist ein Player für IPTV-Playlists (M3U) mit Programmführer. Die App
bringt keine Sender mit: Du trägst den Playlist-Link deines eigenen Anbieters ein.

![Startseite](bilder/start.png)

## Was du brauchst

- Einen Samsung-Smart-TV ab Baujahr 2017 (Tizen).
- Einen Windows-PC, Mac oder Linux-Rechner **oder** ein Android-Handy im selben WLAN wie der Fernseher.
- Ein kostenloses Samsung-Konto. Damit erstellt das Installationsprogramm das Zertifikat für deinen Fernseher.
- Die Datei **FLOH-IPTV.wgt**: <https://github.com/kingflooow/floh-iptv/releases/latest/download/FLOH-IPTV.wgt>

## 1. Entwicklermodus am Fernseher einschalten (einmalig)

1. Am Fernseher **Apps** öffnen.
2. Auf der Fernbedienung nacheinander **1 2 3 4 5** drücken. Falls es keine Zifferntasten gibt, über die Bildschirm-Zifferntasten.
3. Im Fenster **Developer mode** auf **On** stellen.
4. Bei **Host PC IP** die IP-Adresse des PCs oder Handys eintragen, mit dem du installierst.
   Am PC findest du sie unter *Einstellungen → Netzwerk*, am Handy unter *WLAN → Details*.
5. Den Fernseher neu starten: die Ein/Aus-Taste gedrückt halten, bis er neu startet.

## 2. FLOH IPTV installieren

1. **Apps2Samsung** herunterladen: <https://github.com/Apps2Samsung/Apps2Samsung/releases>
   (für Windows, Mac und Linux, und als Android-App).
2. Apps2Samsung starten und deinen Fernseher auswählen.
3. **Eigene .wgt** bzw. *custom .wgt* wählen und die heruntergeladene Datei `FLOH-IPTV.wgt` angeben.
4. Bei der ersten Installation mit deinem Samsung-Konto anmelden.
5. **Installieren**. Danach steht FLOH IPTV in der App-Liste des Fernsehers.

## 3. Playlist eintragen

1. FLOH IPTV öffnen und **OK** drücken.
2. Den Playlist-Link deines Anbieters eintragen. Das Programm (EPG) holt sich die App aus der
   Playlist, sonst kannst du den EPG-Link in den Einstellungen (**BLAUE** Taste) eintragen.

## Bedienung

| Taste | Wirkung |
|---|---|
| OK | Senderliste öffnen, Sender abspielen |
| Hoch / Runter, CH+ / CH- | nächster / vorheriger Sender |
| Links / Rechts in der Liste | ganze Seite blättern |
| GELB | Favorit an/aus |
| GRÜN | Favoriten |
| BLAU | Einstellungen |
| ZURÜCK | Infoleiste weg, dann Startseite; auf der Startseite zweimal: beenden |

![Senderliste](bilder/senderliste.png)
![Programmführer](bilder/programm.png)

## Updates und Hinweise

- Ein Update installierst du genauso mit der neuen Datei. Einstellungen und Favoriten bleiben erhalten.
- Nach einem großen Firmware-Update des Fernsehers kann die App verschwinden. Dann einfach neu installieren.
- Hängt ein Sender, wählt die App ihn selbst neu an und weicht danach auf eine andere Fassung oder den
  nächsten Sender aus. Das lässt sich in den Einstellungen anpassen.
