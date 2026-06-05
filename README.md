# Yanis Ameseder — G4MEOVER18

**IT-Quereinsteiger · Security Research · Homelab · Embedded · lokale KI · Systemanalyse**

Ich bin Yanis Ameseder aus St. Gallen und komme ursprünglich aus dem Strassen- und Tiefbau. Ich habe viele Jahre praktisch, körperlich und organisatorisch gearbeitet, Baustellen geführt, Verantwortung übernommen und gelernt, Probleme direkt an realen Systemen zu lösen. Heute nutze ich genau diese Arbeitsweise für IT, Cybersecurity, Hardware, Automatisierung und lokale KI.

Ich bin kein klassisch ausgebildeter Informatiker. Meine IT-Kompetenz kommt aus eigenen Projekten, Fehlern, Logs, Debugging, Hardwaretests, kaputten Setups, wiederholbarem Aufbau und der Frage:

> Was passiert eigentlich, wenn man das so macht?

Ab **August 2026** starte ich den **TECH-Track der Digital Talents Academy am GBW St. Gallen** als strukturierten Einstieg in die Informatik. Bis dahin baue ich weiter: Tools, Labore, Scanner, Embedded-Systeme, KI-Workflows, Sicherheitskonzepte und dokumentierte Proof-of-Concepts.

---

## Über mich

Ich arbeite interessengetrieben und sehr praxisnah. Mich interessieren Systeme dort, wo mehrere Ebenen zusammenkommen:

- Hardware
- Firmware
- Betriebssysteme
- Netzwerke
- Virtualisierung
- lokale KI
- Automatisierung
- Security
- Dokumentation

Mein Denkstil ist stark verknüpfend. Ich erkenne Muster, stelle ungewöhnliche Fragen und baue daraus technische Konzepte. Was manchmal sprunghaft wirkt, führt in der Praxis oft zu klaren Testaufbauten, reproduzierbaren Ergebnissen und dokumentierten Lösungen.

Mein Arbeitsmuster:

```text
Hypothese → Test → Log → Fehleranalyse → Fix → Dokumentation
```

Ich zerlege Systeme nicht, um sie kaputtzumachen, sondern um zu verstehen, wie sie funktionieren, wo sie sich widersprechen und wie man sie robuster macht.

---

## Haltung

- Lernen passiert dort, wo es schwierig wird.
- Logs sind ehrlicher als Vermutungen.
- Gute Dokumentation ist Teil der Lösung.
- Sicherheit gehört in autorisierte Tests, Labore, CTFs und kontrollierte Umgebungen.
- Ein Proof-of-Concept ist für mich ein Denkmodell, kein Selbstzweck.
- Ich baue lieber ein eigenes Werkzeug und verstehe es, als nur ein fertiges Tool zu benutzen.

> Ich sehe nicht nur, was ist.  
> Ich frage mich, was sein könnte — und was passiert, wenn jemand es ausnutzt.

---

## Technische Schwerpunkte

### Software & Automatisierung

- Python
- tkinter / GUI-Tools
- PowerShell
- Batch
- Markdown
- REST-APIs
- JSON / CSV / strukturierte Daten
- PyInstaller-Builds
- Tool-Launcher
- Reporting-Generatoren

### Systeme & Infrastruktur

- Windows 10 / Windows 11
- Debian / Ubuntu
- Alpine Linux
- Proxmox
- Hyper-V
- Docker / Docker Compose
- systemd / OpenRC
- Nginx Reverse Proxy
- Cloudflare Tunnel / Access
- SSH key-only Zugriff
- VM-Design mit OVMF, Cloud-Init und sauberer Storage-Trennung

### Security & Analyse

- Netzwerkanalyse
- Portscanning
- Banner-Grabbing
- OS-Fingerprinting
- Web-Application-Security
- XSS
- SQL Injection
- JWT-Tests
- CORS-Fehlkonfigurationen
- HTTP-Sicherheitsheader
- Subdomain-Recon
- Hash-Analyse
- Firmware-Analyse
- USB-/HID-/Treiberverhalten
- autorisierte Penetrationstests und Security Research

### Embedded / IoT / Funk

- ESP32 / ESP32-S3
- STM32F103 / Blue Pill
- Flipper Zero
- Heltec / LoRa
- SX1262 / SX1278
- LoRa 868 / 433
- BLE
- GNSS / u-blox
- MQTT
- UART / SPI / I2C
- Display-Dashboards
- Hardware-Prototyping

### Lokale KI

- Ollama
- OpenWebUI
- RAG-Pipelines
- lokale Tool-Server
- Modell-Orchestrierung
- REST-Agentensysteme
- OpenClaw / AI-Agenten-Lab
- Proxmox-basierte KI-VMs
- isolierte Runner-VMs
- lokale Datenpfade, Caches und reproduzierbare KI-Setups

---

# Projekte

## G4MEOVER Security Suite

**All-in-One Pentesting-GUI für Windows**  
Python 3.12 · tkinter · Catppuccin Mocha · 13+ integrierte Module

Die G4MEOVER Security Suite ist mein zentrales Windows-GUI-Tool für autorisierte Sicherheitstests, Labore und Security Research. Ziel ist eine Oberfläche, die typische Pentest-Aufgaben bündelt, ohne dass ständig zwischen vielen einzelnen Tools gewechselt werden muss.

Repository:  
[github.com/G4MEOVER18/g4meover-security-suite](https://github.com/G4MEOVER18/g4meover-security-suite)

### Enthaltene Bereiche

- Dashboard mit Tool-Status und Quickstart
- Netzwerk-Scanner mit nmap / Masscan-Anbindung
- WLAN/WPA-Analyse mit PCAP-Konvertierung
- Handshake-Sniffer
- PMKID-Extraktor
- Hashcat / John / Hydra Integration
- Web-Testing mit gobuster, nikto, sqlmap, whatweb
- OSINT: Whois, DNS, crt.sh, Shodan, Geo-IP, OUI
- Exploit- und CVE-Recherche
- Reporting mit Markdown / HTML / TXT
- Hilfesystem mit Schritt-für-Schritt-Anleitungen
- Konfigurationssystem für Tool-Pfade, API-Keys und Workspaces
- API-Server für KI-/Agenten-Integration

Dieses Projekt zeigt meinen Ansatz sehr gut: viele einzelne Tools, aber in eine strukturierte Oberfläche gebracht, dokumentiert und erweiterbar gemacht.

---

## g4meover-pentest-cockpit

**KI-gestütztes Pentest-Cockpit für autorisierte Security-Labs**  
Python · PySide6 · Cyber Red/Blue Design · KI-Integration

Das g4meover-pentest-cockpit ist ein modernes, KI-gestütztes Pentesting-Cockpit für Windows. Es baut auf PySide6 auf und erweitert den Ansatz der G4MEOVER Security Suite um direkte KI-Anbindung und eine überarbeitete Oberfläche im Cyber Red/Blue-Stil.

Repository:  
[github.com/G4MEOVER18/g4meover-pentest-cockpit](https://github.com/G4MEOVER18/g4meover-pentest-cockpit)

Merkmale:

- PySide6-basierte moderne Oberfläche
- Cyber Red/Blue Design-Sprache
- KI-gestützte Analyse und Auswertung von Scan-Ergebnissen
- Für autorisierte Security-Labs und Penetrationstests
- Weiterentwicklung der GUI-Philosophie aus der G4MEOVER Security Suite

---

## Hardware Security

| Repository | Beschreibung |
|---|---|
| [stm32-usb-fuzzer](https://github.com/G4MEOVER18/stm32-usb-fuzzer) | Hardware-USB-Descriptor-Fuzzer auf STM32F103C8T6. Sendet absichtlich fehlerhafte USB-Deskriptoren, um Windows-USB-Treiberverhalten in autorisierten Laborumgebungen zu analysieren. Enthält 30 wählbare Modi, UART-Steuerung, Reset-Counter und verschiedene Descriptor-Testgruppen. |
| [usb-army-penetrator](https://github.com/G4MEOVER18/usb-army-penetrator) | USB-/WiFi-Penetrationstesting-Projekt auf ESP32-Basis. Fokus auf BadUSB, HID, Mass Storage, WiFi Marauder, Remote-Agent-Ansätze und Lernzwecke. Fork-/Inspirationsbasis: USBArmyKnife. |

---

## Flipper Zero

| Repository | Beschreibung |
|---|---|
| [G4MEOVER-FW](https://github.com/G4MEOVER18/G4MEOVER-FW) | Custom Flipper Zero Firmware v1.0.0 auf Momentum-Basis. API 87.1 · CH-DE BadUSB-Layouts · lora_ukfe-Integration · G4MEOVER-Branding · eigene Apps und experimentelle Security-/Hardware-Workflows. |
| [ProtoPirate](https://github.com/G4MEOVER18/ProtoPirate) | FAP v3.1 — Car-Key-Fob RF-Decoder, Analyzer und Emulator. 27+ Protokolle (KIA, Ford, VAG, PSA, Honda, Subaru...). Sub-GHz · Rolling Code · KeeLoq · XTEA · AES128. |
| [lora-ukfe](https://github.com/G4MEOVER18/lora-ukfe) | FAP v1.0.0 — USB Army Knife Flipper Edition. Remote-Steuerung für Heltec ESP32 LoRa v3 via UART/JSON. LoRa-Scan · WiFi-Deauth · Evil Portal · BadUSB-Trigger · 10 Menüeinträge. |
| [RollJam](https://github.com/G4MEOVER18/RollJam) | Rolling-Code-Capture-und-Replay-Forschungs-App für Flipper Zero. Analyse und Replay von Rolling-Code-Systemen in autorisierten Laborumgebungen. |
| [RollLab](https://github.com/G4MEOVER18/RollLab) | Rolling Code Vulnerability Lab — Analyse, Replay, Rollback und Sync-Window-Probe für Flipper Zero. Vollständige Testumgebung für Rolling-Code-Schwachstellen und autorisierte Forschung. |

---

## Web Application Security

| Repository | Beschreibung |
|---|---|
| [xss-hunter](https://github.com/G4MEOVER18/xss-hunter) | XSS-Scanner mit Payloads für verschiedene Kontexte, WAF-Erkennung, DOM-Sink-Analyse, Formularerkennung und Crawl-Modus. Reines Python, für autorisierte Tests und Lernzwecke. |
| [sqli-hunter](https://github.com/G4MEOVER18/sqli-hunter) | SQL-Injection-Scanner mit Error-based, Boolean-blind, Time-based Detection, DBMS-Fingerprinting, UNION-Extraktion und Tamper-Skripten. Inspiriert von sqlmap, aber als leichtgewichtige Python-Implementierung. |
| [jwt-pwn](https://github.com/G4MEOVER18/jwt-pwn) | JWT-Test-Toolkit für autorisierte Pentests: alg:none, RS256→HS256 Confusion, Claim-Manipulation, kid-Injection, HMAC-Brute-Force und weitere JWT-Prüfungen. |
| [cors-scanner](https://github.com/G4MEOVER18/cors-scanner) | Scanner für CORS-Fehlkonfigurationen: reflektierte Origins, Null-Origin-Bypass, Subdomain-Wildcards, Suffix-Bypass und Vary-Header-Prüfung. |
| [http-header-auditor](https://github.com/G4MEOVER18/http-header-auditor) | OWASP-orientierter HTTP-Sicherheitsheader-Prüfer für HSTS, CSP, X-Frame-Options, X-Content-Type-Options, Referrer-Policy, Permissions-Policy und CI/CD-Auswertung. |
| [subdomain-takeover-scanner](https://github.com/G4MEOVER18/subdomain-takeover-scanner) | Scanner für mögliche Subdomain-Takeover-Szenarien mit Provider-Fingerprints, CNAME-Analyse und TLS-/DNS-Kontext. |
| [web-recon-toolkit](https://github.com/G4MEOVER18/web-recon-toolkit) | Toolkit für Web-Reconnaissance: Tech-Fingerprinting, Directory-Checks, DNS-Enumeration, Wayback-Analyse, E-Mail-Harvesting und Secret-Detection. |

---

## Security Research / PoC

| Repository | Beschreibung |
|---|---|
| [SteamCloud-PoC-by-Yanis](https://github.com/G4MEOVER18/SteamCloud-PoC-by-Yanis) | Nicht-bösartiger, edukativer Proof-of-Concept: Demonstration, wie Steam-Cloud-Save-Funktionalität theoretisch für strukturierte, dormante Payloads via Savegame-Dateien missbraucht werden könnte. Rein zu Forschungs- und Lernzwecken dokumentiert. |

---

## Netzwerk & Passwortanalyse

| Repository | Beschreibung |
|---|---|
| [netmap](https://github.com/G4MEOVER18/netmap) | Reines Python-Netzwerk-Reconnaissance-Tool ohne externe Abhängigkeiten. TCP/UDP-Portscan, Banner-Grabbing, CIDR-Scan, heuristisches OS-Fingerprinting, Script-Engine, JSON- und Grepable-Output. |
| [hashpwn](https://github.com/G4MEOVER18/hashpwn) | Hash-Analyse- und Cracking-Toolkit mit Unterstützung für verschiedene Hash-Typen, Wörterbuchangriffe, Regelangriffe und Maskenangriffe. |

---

## Infrastruktur- und Homelab-Projekte

### Proxmox / Homelab

Ich betreibe und dokumentiere eigene Proxmox-Setups mit mehreren VMs, klarer Storage-Trennung und Zugriffskonzepten.

Schwerpunkte:

- Proxmox VE
- Ubuntu Server VMs
- Cloud-Init
- OVMF / UEFI
- getrennte OS- und Daten-Disks
- SSH key-only Zugriff
- zentrale Jump-VMs
- Cloudflare Access / Zero Trust
- Docker-Services
- lokale KI-Stacks
- Logging und reproduzierbare Installationsschritte

### KI-Core / lokale KI

Mein lokales KI-Lab kombiniert Proxmox, Ubuntu, GPU-/CPU-Tests, Ollama, OpenWebUI, RAG-Datenpfade und eigene Tool-Server. Ziel ist ein System, das nicht nur Modelle startet, sondern lokale Daten, Tools und Agenten kontrolliert miteinander verbindet.

Schwerpunkte:

- lokale LLMs
- Ollama
- OpenWebUI
- RAG
- REST-Toolserver
- KI-Agenten
- isolierte Runner-VMs
- saubere Datenpfade
- reproduzierbare Deployments
- Dokumentation vor Umbauten

Repository (Systemdokumentation):  
[github.com/G4MEOVER18/ki-core-docs](https://github.com/G4MEOVER18/ki-core-docs) — Öffentliche Architekturdokumentation der verteilten, selbst-gehosteten KI-Infrastruktur.

---

## Embedded- und IoT-Projekte

| Projekt | Beschreibung |
|---|---|
| [ESP32-LCD-Time-SD-FTP](https://github.com/G4MEOVER18/ESP32-LCD-Time-SD-FTP) | ESP32-S3 Display-Dashboard mit Uhrzeit, NTP, SD-Logging, FTP-Server, WebUI und Statusanzeige. |
| [ESP32S3-MiniPwn-Dashboard](https://github.com/G4MEOVER18/ESP32S3-MiniPwn-Dashboard) | Kleines ESP32-S3 Dashboard für Netzwerk-/Status-/Security-Experimente. |
| [ESP32-CaptivePortal](https://github.com/G4MEOVER18/ESP32-CaptivePortal) | ESP32 Captive Portal — WiFi-Captive-Portal-Implementierung für Netzwerk-Experimente und Lernzwecke. |
| [RadioGateway](https://github.com/G4MEOVER18/RadioGateway) | ESP32-/LoRa-/MQTT-Gateway für Telemetrie, Funk-Experimente und lokale Logging-Pipelines. |
| [LoRa-Ra-08-CubeCell](https://github.com/G4MEOVER18/LoRa-Ra-08-CubeCell) | CubeCell HTCC-AB01 LoRa-Experimente und Firmware-Tests für Ra-08 und verwandte Module. |
| [LoRa-868](https://github.com/G4MEOVER18/LoRa-868) | Experimentelle LoRa-868-Projekte für lokale Funkstrecken, Gateways und Low-Power-Kommunikation. |
| [LoRa-433](https://github.com/G4MEOVER18/LoRa-433) | Experimentelle LoRa-433-Tests für alternative Frequenzbereiche und Hardwarevergleiche. |
| [SoundNode](https://github.com/G4MEOVER18/SoundNode) | ESP32 Cheap Yellow Display als MP3-/Audio-Node mit SD und Bluetooth. |
| [TFT-AutoProbe](https://github.com/G4MEOVER18/TFT-AutoProbe) | Mini-Sketch zum schnellen Testen und Verifizieren von TFT_eSPI-Display-Setups. |
| LinkVault-XIAO-Notes | Notiz-/Link-/Hardware-Projekt rund um Seeed XIAO Boards und kleine Embedded-Workflows. |

---

## Größere Projekte in Arbeit

### StoneBook

**KI-gestütztes Analyse- und Datenbank-Tool für Edelsteine, Mineralien, Fossilien und Gesteine**

StoneBook ist ein umfangreiches Offline-/Online-Projekt zur strukturierten Erfassung, Analyse und Dokumentation von Gesteins- und Mineralienfunden.

Geplante und entwickelte Bereiche:

- lokale Datenbank
- GUI-only Bedienung
- Objektverwaltung
- Bilder pro Objekt
- CSV / JSON / DOCX Export
- KI-gestützte Analyse
- lokale KI-Anbindung
- Batch-Verarbeitung
- Fundort-, UV-, Härte-, Dichte- und Merkmalsfelder
- saubere Ordnerstruktur
- Dokumentationsmodule

Ziel: Ein Werkzeug, das Sammlungsdaten, Fotos, Beobachtungen und KI-Auswertung in einer nachvollziehbaren lokalen Datenbank zusammenführt.

Repository:  
[github.com/G4MEOVER18/StoneBook](https://github.com/G4MEOVER18/StoneBook)

---

### SmartTag / DogyTag

**Multi-Radio Low-Power Tracker**

Ein abofreier Tracker-Ansatz mit Kombination aus:

- LoRa
- BLE
- GNSS
- Low-Power-Zuständen
- Gateway-Logik
- Nahbereichssuche
- Geofence-Ideen
- optionalem Mobilfunk-Booster

Ziel ist ein robustes Hybrid-System: stromsparender Normalbetrieb, grobe LoRa-Ortung, BLE-Feinsuche und GPS nur bei Bedarf.

Repository (Firmware):  
[github.com/G4MEOVER18/dogytag-firmware](https://github.com/G4MEOVER18/dogytag-firmware) — ESP32S3, Heltec, CubeCell. LoRaWAN EU868 · Raw LoRa 868/433 MHz · BLE-Geofence · GPS. 4 Firmware-Komponenten.

---

### NetzwerkAnalyseTool

GUI-Tool für Windows zur einfachen lokalen Netzwerkanalyse.

Geplante und umgesetzte Bereiche:

- WLAN-Scan
- Subnetzerkennung
- Portscan
- Geräteerkennung
- MAC-/OUI-Auflösung
- CSV-Export
- einfache Oberfläche für Nicht-Experten
- klare deutsche Beschriftung

---

### Systemanalyse-Tool

GUI-Tool zur Hardware- und Systemerfassung.

Fokus:

- CPU
- RAM
- Mainboard
- BIOS
- Storage
- Windows-Informationen
- Export als strukturierte Datei
- nutzbar für Inventar, Fehlersuche und Dokumentation

---

## Stack

```text
Sprachen:
Python · C/C++ · PowerShell · Batch · Markdown

GUI:
tkinter · Windows GUI Tools · einfache Admin-Oberflächen

Security:
Pentesting · Web-Security · Netzwerkanalyse · Firmware-Analyse · USB/HID · Recon

Embedded:
ESP32 · ESP32-S3 · STM32F103 · Flipper Zero · Heltec · CubeCell · XIAO

Funk:
LoRa 868 · LoRa 433 · BLE · GNSS · MQTT · UART · SPI · I2C

Infrastruktur:
Proxmox · Docker · Docker Compose · Nginx · Cloudflare Tunnel · Cloudflare Access

KI:
Ollama · OpenWebUI · RAG · lokale Toolserver · REST-Agentensysteme · OpenClaw

Betriebssysteme:
Windows 11 · Debian · Ubuntu · Alpine Linux
```

---

## Forschungsschwerpunkte

### USB / Hardware Security

- USB-Descriptor-Verhalten
- Windows USB-Treiber-Stack
- HID
- Mass Storage
- Composite Devices
- Fuzzing in kontrollierten Laboren
- STM32-basierte Testgeräte

### Web Security

- XSS
- SQL Injection
- JWT
- CORS
- HTTP Security Headers
- Subdomain Takeover
- Reconnaissance
- WAF-Erkennung
- Reporting

### Netzwerk

- Portscanning
- Banner-Grabbing
- OS-Fingerprinting
- CIDR-Scans
- Service-Erkennung
- lokale Netzwerkdokumentation
- einfache GUIs für komplexe Netzwerkanalyse

### Embedded RF

- LoRa
- BLE
- GNSS
- ESP32
- Gateways
- Telemetrie
- Low-Power-Design
- MQTT-Logging

### Lokale KI & Agenten

- lokale LLM-Workflows
- Tool-Calling
- RAG
- Offline-Dokumentenanalyse
- Agenten-Runner
- kontrollierte VM-Umgebungen
- lokale Datenhoheit

---

## Warum diese Repos existieren

Viele meiner Projekte sind nicht entstanden, weil es kein fertiges Tool dafür gibt. Sie sind entstanden, weil ich verstehen will, wie Systeme intern arbeiten.

Ich baue bewusst eigene Versionen von bekannten Werkzeugideen, weil dabei der Lerneffekt entsteht:

- Welche Annahmen macht ein Tool?
- Welche Fehler treten in echten Umgebungen auf?
- Wie lässt sich ein Ergebnis dokumentieren?
- Wie macht man ein Tool für andere verständlich?
- Wie trennt man Forschung, Labor und reale Nutzung sauber?

Deshalb sind meine Repos eine Mischung aus:

- Lernprojekten
- Security Research
- GUI-Werkzeugen
- Homelab-Dokumentation
- Embedded-Prototypen
- lokalen KI-Workflows
- Proof-of-Concepts

---

## Sicherheit & Ethik

Alle Security-Projekte sind für folgende Szenarien gedacht:

- eigene Labore
- autorisierte Penetrationstests
- CTFs
- Schulung
- Forschung
- Dokumentation
- defensive Analyse
- kontrollierte Testumgebungen

Nicht gedacht sind sie für unautorisierte Angriffe, Missbrauch oder Tests gegen fremde Systeme ohne ausdrückliche Erlaubnis.

---

## Ausbildung & Perspektive

Ich bin IT-Quereinsteiger und baue mein Portfolio sichtbar über reale Projekte auf.

Ab **August 2026**:

**Digital Talents Academy – TECH-Track**  
Gewerbliches Berufs- und Weiterbildungszentrum St. Gallen

Ziel:

- Einstieg in die IT
- später Spezialisierung Richtung Cybersecurity
- Plattform-/Systementwicklung
- Security Engineering
- lokale KI-Systeme
- Infrastruktur und Automatisierung

---

## Kontakt

- GitHub: [G4MEOVER18](https://github.com/G4MEOVER18)
- Website: [ameseder.com](https://ameseder.com)

---

## Support

Wenn dir meine Projekte helfen oder du meine Hardware-/Forschungszeit unterstützen möchtest:

**Bitcoin:**  
`39vZWmnUwDReQ15BwqQXzyqVQ6U8LardEf`

**PayPal:**  
[paypal.me/Freakbank1](https://paypal.me/Freakbank1)

Bug-Reports, Ideen und konstruktives Feedback sind willkommen.

---

## Kurz gesagt

Ich komme nicht aus der klassischen Informatik.

Ich komme aus der Praxis.

Ich baue, teste, zerlege, dokumentiere und lerne an echten Systemen.

Mein Ziel ist nicht, nur Tools zu benutzen.  
Mein Ziel ist, Systeme zu verstehen — und daraus bessere Werkzeuge zu bauen.
