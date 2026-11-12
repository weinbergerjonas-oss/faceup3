FACEUP – iPhone-Web-App-Prototyp

Dateien:
- index.html: App-Oberfläche und lokale Gesichtspunkt-Erkennung
- manifest.webmanifest: PWA-Installationsdaten
- sw.js: einfacher Offline-App-Shell-Cache
- icon.svg: App-Symbol

Wichtig:
1. Eine PWA muss über HTTPS gehostet werden (z. B. eigener Webspace oder ein statischer Hosting-Anbieter).
2. Öffne die HTTPS-Adresse in Safari auf dem iPhone.
3. Tippe auf Teilen > Zum Home-Bildschirm.
4. Beim ersten Gesichtsscan ist Internet nötig, um MediaPipe und das Erkennungsmodell zu laden.
5. Die Bildanalyse läuft im Browser. Das Foto wird von dieser App nicht an einen Server gesendet.
6. Die Erkennung liefert Gesichtspunkte/Orientierung, keine Attraktivitätsbewertung, Diagnose oder Messung der Knochenstruktur.

Dies ist ein Prototyp, keine veröffentlichte App im App Store.