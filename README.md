# Yanis Ameseder — Sicherheitsforscher

Unabhängiger Sicherheitsforscher mit Fokus auf **USB-Angriffsflächen**, **Web Application Security**, **Embedded Firmware** und **Windows-Treiberexploitation**. Alle Tools für autorisierte Penetrationstests und Sicherheitsforschung — quelloffen, dokumentiert, keine externen Abhängigkeiten wo möglich.

---

## Hardware Security

| Repo | Beschreibung |
|------|-------------|
| [stm32-usb-fuzzer](https://github.com/G4MEOVER18/stm32-usb-fuzzer) | Hardware-USB-Descriptor-Fuzzer auf STM32F103C8T6 — 30 Angriffsmodi gegen `usbhub.sys`, `usbccgp.sys`, `hidparse.sys`, `usbstor.sys`, `winusb.sys`. BSOD-Reproduktion, autonome Registry-Manipulation |
| [usb-army-penetrator](https://github.com/G4MEOVER18/usb-army-penetrator) | USB/WiFi-Penetrationstesting auf ESP32 — BadUSB, HID, Mass Storage, WiFi Marauder, Remote Agent, VNC, Hot Mic, G4MEOVER RadioRemote *(Fork: [USBArmyKnife](https://github.com/i-am-shodan/USBArmyKnife))* |
| [dogytag-firmware](https://github.com/G4MEOVER18/dogytag-firmware) | Multi-Radio Haustier-Tracking: LoRaWAN EU868 OTAA + Raw LoRa 868/433 MHz + BLE-Geofence + GPS — XIAO ESP32S3, Heltec Tracker, CubeCell. Vier Firmware-Komponenten, ein System |

## Web Application Security

| Repo | Beschreibung |
|------|-------------|
| [xss-hunter](https://github.com/G4MEOVER18/xss-hunter) | XSS-Scanner: 44 Payloads in 7 Kontexten, WAF-Erkennung (Cloudflare/Akamai/ModSec/F5/Imperva), WAF-Bypass-Varianten, DOM-Sink-Analyse, Crawl-Modus *(inspiriert von [XSStrike](https://github.com/s0md3v/XSStrike))* |
| [sqli-hunter](https://github.com/G4MEOVER18/sqli-hunter) | SQL-Injection: Error-based (88 Regex/8 DBMS), Boolean-blind, Time-based, DBMS-Fingerprint, UNION-Extraktion, 4 Tamper-Skripte *(inspiriert von [sqlmap](https://github.com/sqlmapproject/sqlmap))* |
| [jwt-pwn](https://github.com/G4MEOVER18/jwt-pwn) | JWT-Angriffs-Toolkit: `alg:none` (4 Varianten), RS256→HS256 Confusion, jku/x5u Injection, Claim-Eskalation, `kid`-Injection, HMAC-Brute-Force (parallel) |
| [cors-scanner](https://github.com/G4MEOVER18/cors-scanner) | CORS-Fehlkonfigurations-Scanner: 13 Probe-Typen, Header-Injection-Bypasses, Response-Body-Analyse, Bulk-Scan, Preflight-Bypass |
| [http-header-auditor](https://github.com/G4MEOVER18/http-header-auditor) | OWASP HTTP-Header-Prüfer: HSTS, CSP (unsafe-inline/eval Detection), Cookie-Sicherheit, CORS, Cache-Control, Redirect-Chain, Batch-Modus |
| [subdomain-takeover-scanner](https://github.com/G4MEOVER18/subdomain-takeover-scanner) | Subdomain-Takeover: 35+ Provider-Fingerprints, CNAME-Chain-Analyse, DNS-Fallback, TLS-SAN-Enumeration, NXDOMAIN-Erkennung |
| [web-recon-toolkit](https://github.com/G4MEOVER18/web-recon-toolkit) | Web-Reconnaissance: Tech-FP, Dir-Brute-Force, E-Mail-Harvesting, DNS-Enum, Wayback, SSL-Analyse, Secret-Detection, Subdomain-Enumeration |

## Netzwerk & Passwörter

| Repo | Beschreibung |
|------|-------------|
| [netmap](https://github.com/G4MEOVER18/netmap) | Netzwerk-Scanner: TCP/UDP-Scan, Banner-Grabbing (20 Services), OS-Fingerprinting, CIDR-Subnetz, Script-Engine, T1-T5 Timing *(inspiriert von [nmap](https://nmap.org) / [masscan](https://github.com/robertdavidgraham/masscan))* |
| [hashpwn](https://github.com/G4MEOVER18/hashpwn) | Hash-Cracking: 35+ Typen (NTLM, bcrypt, argon2, MD5, SHA*, MySQL, Oracle, Cisco...), Wörterbuch, Regelangriff, Maskenangriff, Potfile-Resume *(inspiriert von [hashcat](https://github.com/hashcat/hashcat))* |

---

## Forschungsschwerpunkte

- **Windows USB-Treiber-Stack** — Kernel-Pool-Allokationen, Descriptor-Parser-Schwachstellen, CVE-2024-21429-Klasse in `usbhub.sys`
- **Web-Auth-Schwachstellen** — JWT, OAuth, Session Management, CORS, HTTP-Header, XSS, SQLi
- **Embedded RF-Sicherheit** — LoRaWAN, Raw LoRa, 433 MHz ISM, BLE-Angriffsflächen, UART-Protokolle
- **Hardware-Firmware** — STM32, ESP32-S3, CubeCell ASR6502, Heltec-Plattformen
- **Netzwerk-Reconnaissance** — Portscanning, Banner-Grabbing, OS-Fingerprinting, Subdomain-Takeover

---

## Prinzipien

- Keine externen Abhängigkeiten wo möglich — Python stdlib, reines C/C++
- Nur autorisierter Einsatz — alle Tools mit klaren Rechtshinweisen
- Vollständig dokumentiert — Angriffstheorie, nicht nur PoC

---

## Support

Wenn diese Projekte deiner Sicherheitsforschung geholfen haben — jeder Beitrag ermöglicht weitere Hardware und Forschungszeit:

> **Bitcoin:** `39vZWmnUwDReQ15BwqQXzyqVQ6U8LardEf`
>
> **PayPal:** [paypal.me/Freakbank1](https://paypal.me/Freakbank1)

Beiträge und Bug-Reports willkommen — alles MIT-lizenziert.
