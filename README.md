# 🧩 Brick-Building 3D Sandbox & Viewer

Ein interaktiver, browserbasierter 3D-Viewer und Editor für Baustein-Modelle in der Ego-Perspektive. Lade deine eigenen `.obj`- und `.mtl`-Modelle hoch, erkunde sie frei zu Fuß oder im Flugmodus und baue eigene einfache Steine hinzu!

---

## 🎮 Steuerung & Bedienung

### 🏃 Bewegung & Erkundung
* **W, A, S, D** – Vorwärts, rückwärts und seitwärts laufen
* **Maus** – Umsehen (Ego-Perspektive)
* **Leerzeichen (Space)** – Springen
* **ESC** – Maus freigeben / Menü bedienen

### 🛸 Flugmodus
* **C** – Flugmodus aktivieren / deaktivieren
* **Leerzeichen (Space)** – Nach oben fliegen
* **Shift (Umschalt)** – Nach unten fliegen

### 🛠️ Baumodus (Editor)
* **E** – Baumodus aktivieren / deaktivieren
* **Linksklick** – Baustein an der Zielposition platzieren
* **Rechtsklick** – Baustein anvisieren und löschen
* **Farbauswahl** – Über das Menü oben links kann die Farbe des nächsten Bausteins gewählt werden

---

## 📁 Eigene Modelle laden (.obj & .mtl)

1. Klicke oben links auf den Button **`📁 Dateien öffnen (.obj & .mtl)`**.
2. Wähle deine zusammengehörigen **.obj**- und **.mtl**-Dateien aus (z. B. exportiert aus *BrickLink Studio* oder von *mecabrick.com*).
3. Das Modell wird automatisch geladen und am Boden ausgerichtet.
4. Über die Schieberegler im Menü kannst du die **Skalierung** und **Position (X, Y, Z)** des Modells jederzeit anpassen.

---

## ⚙️ Technische Features
* Gebaut mit **Three.js** und **PointerLockControls**.
* **Physik & Kollision**: Realistische 360°-Kollision an Wänden, Ecken und Decken.
* **Keine Installation**: Läuft als reine HTML-Datei direkt im Browser.
