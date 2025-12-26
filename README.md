# Pelican-Stuff 🐧

Eine Sammlung nützlicher Skripte und Konfigurationen für das **Pelican Panel** (und Pterodactyl).

## 🎮 NeoForge-Installer
Dieses Repository enthält ein robustes Installations-Skript für NeoForge Minecraft-Server. Es wurde speziell entwickelt, um Versionskonflikte und Java-Probleme zu vermeiden.

### Features
* **Java 21 Support:** Installiert automatisch Java 21 via Backports auf Debian 12 (Bookworm).
* **Automatisierung:** Erkennt die richtige NeoForge-Version für deine Minecraft-Version.
* **Smart-Format:** Korrigiert automatisch die Download-Links für neuere NeoForge-Versionen (1.20.2+).
* **Cleanup:** Bereinigt den Server-Ordner nach der Installation von temporären Dateien.

## 🚀 Nutzung im Panel

### Empfohlenes Docker-Image
Für Minecraft 1.21+ sollte dein Server dieses Image verwenden:
`ghcr.io/pterodactyl/yolks:java_21`

## 📂 Inhalt dieses Repos
* Das Haupt-Installationsskript für NeoForge.
* (Optional: Hier kannst du weitere Skripte auflisten, die du noch hinzufügst)

## ⚖️ Lizenz
Dieses Projekt ist unter der [MIT License](LICENSE) lizenziert.
