# Yanis Ameseder

14 Jahre Straßen- und Tiefbau, davon die letzten Jahre Polier auf eigenen Baustellen. Gut bezahlt, sinnlos. Irgendwann hab ich aufgehört, mir einzureden, dass es das ist.

Jetzt baue ich Dinge aus Code, Mikrocontrollern und Ideen, die mich seit der Kindheit nicht losgelassen haben. Keine formale IT-Ausbildung – alles kommt aus eigenen Projekten, Logs, Fehlern und der Frage: *Was passiert eigentlich, wenn man das so macht?*

Ab **August 2026** starte ich den TECH-Track der Digital Talents Academy am GBW St. Gallen als strukturierten Einstieg. Bis dahin baue ich weiter.

---

## Projekte

### G4MEOVER Security Suite
**All-in-One Pentesting GUI für Windows** — Python 3.12, tkinter, Catppuccin Mocha Dark

15 integrierte Module in einem Fenster: Netzwerk-Scanner (nmap + Masscan), WiFi/WPA-Cracking (hashcat), tshark Live-Capture, Wordlist-Manager, Network Isolation Tester, VirusTotal-Lookup, Web-Testing (gobuster/nikto/sqlmap), OSINT & Recon (Shodan/crt.sh/WhoIs), Exploit Research (searchsploit/NVD/MSF), Reporting mit HTML-Export. 13 Tools, eine Oberfläche.

→ [g4meover-security-suite](https://github.com/G4MEOVER18/g4meover-security-suite) · [Releases](https://github.com/G4MEOVER18/g4meover-security-suite/releases/latest) · [Wiki](https://github.com/G4MEOVER18/g4meover-security-suite/wiki)

---

### Hardware Security

| Repo | Beschreibung |
|------|-------------|
| [stm32-usb-fuzzer](https://github.com/G4MEOVER18/stm32-usb-fuzzer) | Hardware-USB-Descriptor-Fuzzer auf STM32F103C8T6 — 30 Angriffsmodi gegen `usbhub.sys`, `usbccgp.sys`, `hidparse.sys`, `usbstor.sys`, `winusb.sys`. BSOD-Reproduktion, autonome Registry-Manipulation |
| [usb-army-penetrator](https://github.com/G4MEOVER18/usb-army-penetrator) | USB/WiFi-Penetrationstesting auf ESP32 — BadUSB, HID, Mass Storage, WiFi Marauder, Remote Agent, VNC *(Fork: [USBArmyKnife](https://github.com/i-am-shodan/USBArmyKnife))* |

---

### Flipper Zero

| Repo | Beschreibung |
|------|-------------|
| [G4MEOVER-FW](https://github.com/G4MEOVER18/G4MEOVER-FW) | Custom Flipper Zero Firmware auf Momentum-Basis — CH-DE BadUSB-Layouts, LoRa-Integration (Heltec), eigene Apps, UKFE-Erweiterungen |

---

### Web Application Security

| Repo | Beschreibung |
|------|-------------|
| [xss-hunter](https://github.com/G4MEOVER18/xss-hunter) | XSS-Scanner: 44 Payloads / 7 Kontexte, WAF-Erkennung (Cloudflare/Akamai/ModSec), DOM-Sink-Analyse, Crawl-Modus |
| [sqli-hunter](https://github.com/G4MEOVER18/sqli-hunter) | SQL-Injection: Error-based (88 Regex / 8 DBMS), Boolean-blind, Time-based, UNION-Extraktion, 4 Tamper-Skripte |
| [jwt-pwn](https://github.com/G4MEOVER18/jwt-pwn) | JWT-Angriffe: `alg:none`, RS256→HS256 Confusion, jku/x5u Injection, `kid`-Injection, HMAC-Brute-Force |
| [cors-scanner](https://github.com/G4MEOVER18/cors-scanner) | CORS-Fehlkonfigurations-Scanner: 13 Probe-Typen, Header-Injection-Bypasses, Preflight-Bypass |
| [http-header-auditor](https://github.com/G4MEOVER18/http-header-auditor) | OWASP HTTP-Header-Prüfer: HSTS, CSP, Cookie-Sicherheit, Cache-Control, Redirect-Chain |
| [subdomain-takeover-scanner](https://github.com/G4MEOVER18/subdomain-takeover-scanner) | 35+ Provider-Fingerprints, CNAME-Chain-Analyse, TLS-SAN-Enumeration |
| [web-recon-toolkit](https://github.com/G4MEOVER18/web-recon-toolkit) | Tech-Fingerprint, Dir-Bruteforce, E-Mail-Harvesting, DNS-Enum, Wayback, Secret-Detection |

---

### Netzwerk & Passwörter

| Repo | Beschreibung |
|------|-------------|
| [netmap](https://github.com/G4MEOVER18/netmap) | Netzwerk-Scanner: TCP/UDP, Banner-Grabbing (20 Services), OS-Fingerprinting, CIDR, Script-Engine |
| [hashpwn](https://github.com/G4MEOVER18/hashpwn) | Hash-Cracking: 35+ Typen (NTLM, bcrypt, argon2, MD5, SHA*, MySQL, Oracle...), Wörterbuch, Regelangriff, Maskenangriff |

---

### In Arbeit

| Projekt | Stand |
|---------|-------|
| ESP32-LCD-Time-SD-FTP | ESP32-S3 Dashboard mit NTP, SD-Logging, FTP-Server, WebUI |
| SmartTag | Multi-Radio Low-Power Tracker (LoRa + BLE + GNSS) |
| RadioGateway | ESP32 MQTT/LoRa-Gateway |
| SoundNode | ESP32 Cheap Yellow Display als MP3-Player (ESP-IDF) |
| StoneBook | KI-gestütztes Analyse- und Datenbank-Tool für Edel- und Mineralsteine |

---

## Stack

```
Sprachen      Python · C/C++ · PowerShell · Batch · Markdown
Embedded      ESP32-S3 · STM32F1 · CubeCell ASR6502 · Heltec
Funk          LoRaWAN EU868 · Raw LoRa 868/433 · BLE · GNSS (u-blox)
Infra         Proxmox · Docker/Compose · Nginx · Cloudflare Tunnel
KI lokal      Ollama · OpenWebUI · RAG-Pipelines · REST-Agentensystem
Security      Pentesting · Netzwerkanalyse · Firmware-Analyse · Web-Sec
OS            Windows 11 · Debian/Ubuntu · Alpine
```

---

## Forschungsschwerpunkte

- **USB-Treiber-Stack (Windows)** — Descriptor-Parser, Kernel-Pool-Allokationen, BSOD-Reproduktion
- **Web-Auth** — JWT, OAuth, Session Management, CORS, XSS, SQLi
- **Embedded RF** — LoRaWAN, Raw LoRa, BLE-Angriffsflächen, UART-Protokolle
- **Netzwerk-Reconnaissance** — Portscanning, OS-Fingerprinting, Subdomain-Takeover

> Alle Tools für autorisierte Penetrationstests und Sicherheitsforschung. Keine externen Abhängigkeiten wo möglich.

---

## Support

Wenn meine Projekte dir geholfen haben – jeder Beitrag geht direkt in Hardware und Forschungszeit:

**Bitcoin:** `39vZWmnUwDReQ15BwqQXzyqVQ6U8LardEf`  
**PayPal:** [paypal.me/Freakbank1](https://paypal.me/Freakbank1)

Bug-Reports und Beiträge willkommen. Alles MIT-lizenziert.
