# Yanis Ameseder — Sicherheitsforscher / Security Researcher

Unabhängiger Sicherheitsforscher mit Fokus auf **USB-Angriffsflächen**, **Web Application Security** und **Windows-Treiberexploitation**. Ich baue quelloffene Offensive-Tools für autorisierte Penetrationstests und Sicherheitsforschung.

---

## 🔧 Aktive Projekte

### Hardware Security

| Repo | Beschreibung |
|------|-------------|
| [stm32-usb-fuzzer](https://github.com/G4MEOVER18/stm32-usb-fuzzer) | Hardware-USB-Descriptor-Fuzzer auf STM32F103C8T6 — 30 Angriffsmodi gegen `usbhub.sys`, `usbccgp.sys`, `hidparse.sys`, `usbstor.sys` |
| [usb-army-penetrator](https://github.com/G4MEOVER18/usb-army-penetrator) | USB/WiFi-Penetrationstesting-Plattform auf ESP32 — BadUSB, HID, Netzwerk-Emulation, WiFi Marauder, VNC, Agent *(Fork von [i-am-shodan/USBArmyKnife](https://github.com/i-am-shodan/USBArmyKnife))* |

### Web Application Security

| Repo | Beschreibung |
|------|-------------|
| [jwt-pwn](https://github.com/G4MEOVER18/jwt-pwn) | JWT-Angriffs-Toolkit: `alg:none`, RS256→HS256 Confusion, Claim-Manipulation, `kid`-Injection, HMAC-Brute-Force |
| [cors-scanner](https://github.com/G4MEOVER18/cors-scanner) | CORS-Fehlkonfigurations-Scanner: reflektierte Origins, Null-Origin, Subdomain/Suffix-Bypass |
| [http-header-auditor](https://github.com/G4MEOVER18/http-header-auditor) | OWASP HTTP-Sicherheits-Header-Prüfer: HSTS, CSP, X-Frame-Options, Referrer-Policy |
| [subdomain-takeover-scanner](https://github.com/G4MEOVER18/subdomain-takeover-scanner) | Subdomain-Takeover-Scanner: 30+ Provider-Fingerprints, NXDOMAIN-Erkennung, concurrent |
| [web-recon-toolkit](https://github.com/G4MEOVER18/web-recon-toolkit) | Web-Reconnaissance-Toolkit: Tech-Fingerprinting, Dir-Brute-Force, E-Mail-Harvesting, DNS, Wayback |

---

## Forschungsschwerpunkte

- **Windows USB-Treiber-Stack** — Kernel-Pool-Allokationen, Descriptor-Parser-Schwachstellen, Treiber-Rebind-Races
- **Web-Auth-Schwachstellen** — JWT, OAuth, Session Management, CORS, HTTP-Header
- **Embedded Firmware** — STM32, ESP32, Hardware-Angriffsflächen
- **CVE-Forschung** — aktiv zu CVE-2024-21429-Klasse in `usbhub.sys`

---

## Prinzipien

- **Keine externen Abhängigkeiten** wo möglich (Python stdlib, reines C)
- **Nur autorisierter Einsatz** — alle Tools enthalten klare rechtliche Hinweise
- **Bildungswert** — dokumentierte Angriffstheorie, nicht nur PoC

---

## Kontakt

- E-Mail: g4me.over.18@gmail.com
- Alle Tools MIT-lizenziert — Beiträge und Bug-Reports willkommen

---

## Unterstützung / Donations

Wenn diese Tools deiner Sicherheitsforschung geholfen haben:

**Bitcoin:** `39vZWmnUwDReQ15BwqQXzyqVQ6U8LardEf`
