# Pong Game

Ein klassisches Pong-Spiel, das in Python mit dem `turtle`-Modul entwickelt wurde.

## 🏓 Über das Spiel

Spiele den absoluten Arcade-Klassiker Pong! Treibe den Ball rüber zu deinem Gegner, um Punkte zu erzielen. Wenn ein Spieler den Ball nicht mit seinem Schläger zurückschlagen kann, bekommt der andere Spieler einen Punkt.

## 🎮 Steuerung

Das Spiel ist für zwei Spieler an einer Tastatur ausgelegt:

**Rechter Spieler:**
- **Pfeiltaste Oben (⬆️):** Schläger nach oben bewegen
- **Pfeiltaste Unten (⬇️):** Schläger nach unten bewegen

**Linker Spieler:**
- **Taste W:** Schläger nach oben bewegen
- **Taste S:** Schläger nach unten bewegen

## 🚀 Installation & Spielen (Für Spieler)

Du musst für dieses Spiel **nichts installieren** und benötigst auch kein Python. Lade dir einfach die fertige Datei für dein System herunter:

### Windows (.exe)
1. Gehe auf der rechten Seite dieser GitHub-Seite auf **"Releases"** (oder klicke auf die neueste Version).
2. Lade die Datei `pong-game-windows-latest.zip` herunter.
3. Entpacke die ZIP-Datei.
4. Starte das Spiel mit einem Doppelklick auf `pong-game.exe`.

### macOS (.app / Binary)
1. Gehe auf der rechten Seite dieser GitHub-Seite auf **"Releases"** (oder klicke auf die neueste Version).
2. Lade die Datei `pong-game-macos-latest.zip` herunter.
3. Entpacke die ZIP-Datei.
4. Starte das Spiel durch einen Klick auf die Spieldatei `pong-game`.
*(Hinweis für Mac-Nutzer: Da das Spiel nicht von Apple signiert ist, musst du es in den Systemeinstellungen unter Datenschutz und Sicherheit akzeptieren, um es zu starten).*

---

## 🛠️ Für Entwickler (Ausführen aus dem Quellcode)

Wenn du den Code bearbeiten oder das Spiel direkt über Python ausführen möchtest:

1. **Voraussetzung:** Python (>= 3.12) und ein Paketmanager wie `uv` oder `pip` müssen installiert sein.
2. **Repository klonen / herunterladen:**
   ```bash
   git clone https://github.com/TsukasaMita/pong-game.git
   cd pong-game
   ```
3. **Das Spiel starten:** Führe den folgenden Befehl im Terminal aus:
   ```bash
   python main.py
   # oder falls uv genutzt wird:
   uv run main.py
   ```

Viel Spaß beim Spielen! 🏓✨
