# Flugradar – Firmware

Fertige Firmware für das Flugradar (ESP32-S3, Waveshare ESP32-S3-Touch-LCD-5), ein privates Bastelprojekt.

Die Geräte fragen `version.json` einmal am Tag ab und bieten eine neue Version zum Installieren an.
Jede Datei unter `firmware/` ist signiert; die Geräte installieren nur Firmware mit der passenden
Signatur. Der Quellcode liegt nicht hier.

| Datei | Inhalt |
|---|---|
| `version.json` | neueste Version, Download-Adresse, Größe, Änderungen |
| `firmware/flugradar-X.Y.Z.bin` | Firmware (die letzten drei Versionen) |

Erzeugt mit `release.ps1` – bitte nicht von Hand ändern.
