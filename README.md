# Ollama mit Open WebUI Setup

Diese Docker Compose Konfiguration erstellt eine Ollama-Umgebung mit Open WebUI Interface, die GPU, NPU und CPU nutzt.

## Voraussetzungen

- Docker Desktop für Windows
- NVIDIA Container Toolkit (für GPU-Unterstützung)
- NVIDIA Treiber

## Installation & Start

1. Stellen Sie sicher, dass Docker Desktop läuft
2. Öffnen Sie ein Terminal im Projektverzeichnis
3. Führen Sie folgenden Befehl aus:
   ```
   docker compose up -d
   ```

## Zugriff

- Open WebUI Interface: http://localhost:3000
- Ollama API: http://localhost:11434

## Volumes

- `ollama_data`: Speichert die Ollama Modelle und Konfigurationen
- `open_webui_data`: Speichert die Open WebUI Daten und Einstellungen
