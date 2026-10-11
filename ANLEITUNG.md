# Motorraum aufs iPhone bringen (kostenlos)

## 1. Online stellen mit GitHub Pages
1. Kostenloses Konto auf github.com anlegen.
2. Oben rechts auf **+ → New repository**. Name z. B. `motorraum`, **Public**, dann **Create repository**.
3. Auf **uploading an existing file** klicken und alle Dateien aus diesem Ordner hineinziehen
   (`index.html`, `manifest.json`, `sw.js`, die drei `.png`-Icons). **Commit changes**.
4. Im Repository: **Settings → Pages**. Bei *Source* „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, **Save**.
5. Nach ein bis zwei Minuten läuft die App unter `https://DEINNAME.github.io/motorraum/`.

## 2. Auf den Home-Bildschirm
1. Die Adresse auf dem iPhone in **Safari** öffnen.
2. **Teilen**-Symbol → **Zum Home-Bildschirm** → **Hinzufügen**.
3. Jetzt startet Motorraum wie eine App, im Vollbild und auch offline.

## Updates
Neue `index.html` hochladen und in `sw.js` die Zeile `motorraum-v1` auf `motorraum-v2` usw. ändern.
Beim nächsten Öffnen mit Internet holt sich die App die neue Version.

Dein Fortschritt (XP, Garage) wird nur auf dem iPhone gespeichert.
