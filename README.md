# 🐻‍❄️ Eisbärchen

Ein kleines Tamagotchi im Browser: ein orangener Eisbär in Pixel-Art. Es läuft auf dem iPhone und am Computer, ohne zusätzliche Hardware.

## So funktioniert das Spiel
- **Ei:** Das Ei schlüpft nach einer Minute oder schneller, wenn man es 8 Mal antippt. Danach bekommt der Bär einen Namen.
- **Echtzeit:** Die Werte (Satt, Laune, Energie, Sauber, Gesundheit) sinken mit der echten Zeit, auch wenn die App geschlossen ist.
- **Nachts (22–7 Uhr)** schläft der Bär, und alles läuft viel langsamer.
- **Gnädig:** Der Bär stirbt erst nach etwa 1–2 Tagen ganz ohne Pflege.
- **Aktionen:** Füttern, Spielen (Minispiel „Links oder Rechts“), Schlafen/Wecken, Putzen, Medizin. Antippen = Streicheln.
- **Wiederbeleben:** einmal alle 48 Stunden.
- **1. Oktober:** Der Bär trägt einen Geburtstagshut, und es regnet Konfetti.
  Vorschau jederzeit mit `?geburtstag` am Ende der Adresse.

## Auf dem iPhone
In Safari öffnen → **Teilen** → **„Zum Home-Bildschirm“**. Danach nur noch über das Symbol auf dem Home-Bildschirm spielen.
Safari löscht sonst nach einiger Zeit ohne Nutzung die Spieldaten. Außerdem hat das Home-Bildschirm-Symbol einen eigenen Speicher.

## Veröffentlichen (GitHub Pages)
1. Repository auf **öffentlich** stellen (Settings → General → Danger Zone → Change visibility).
2. Settings → **Pages** → Source: „Deploy from a branch“ → Branch **`main`**, Ordner `/ (root)` → Save.
3. Nach 1–2 Minuten ist das Spiel unter `https://<benutzername>.github.io/Probe/` erreichbar.
