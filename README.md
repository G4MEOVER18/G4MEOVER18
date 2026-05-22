# Yanis Ameseder — Security Researcher

Independent security researcher focused on **USB attack surface**, **web application security**, and **Windows driver exploitation**. Building open-source offensive tools for authorized penetration testing and driver security research.

---

## Active Projects

### Hardware Security
| Repo | Description |
|------|-------------|
| [stm32-usb-fuzzer](https://github.com/G4MEOVER18/stm32-usb-fuzzer) | Hardware USB descriptor fuzzer on STM32F103C8T6 — 30 attack modes targeting `usbhub.sys`, `usbccgp.sys`, `hidparse.sys`, `usbstor.sys` |

### Web Application Security
| Repo | Description |
|------|-------------|
| [jwt-pwn](https://github.com/G4MEOVER18/jwt-pwn) | JWT attack toolkit: `alg:none`, RS256→HS256 confusion, claim tampering, `kid` injection, HMAC brute-force |
| [cors-scanner](https://github.com/G4MEOVER18/cors-scanner) | CORS misconfiguration scanner: reflected origins, null origin, subdomain/suffix bypass, credential leakage |
| [http-header-auditor](https://github.com/G4MEOVER18/http-header-auditor) | OWASP security header auditor: HSTS, CSP, X-Frame-Options, Referrer-Policy, information disclosure |

---

## Research Areas

- **Windows USB driver stack** — kernel pool allocation patterns, descriptor parser edge cases, driver rebind races
- **Web auth vulnerabilities** — JWT, OAuth, session management, CORS
- **Embedded firmware** — STM32, ESP32, hardware attack surfaces
- **CVE research** — actively targeting CVE-2024-21429 class issues in `usbhub.sys`

---

## Philosophy

All tools are built with a focus on:
- **Zero dependencies** where possible (Python stdlib, C only)
- **Authorised use** — every tool includes clear legal disclaimers
- **Educational value** — documented attack theory, not just PoC

---

## Contact

- Email: g4me.over.18@gmail.com
- All tools MIT licensed — contributions and bug reports welcome

**Support this research:**  
Bitcoin: `39vZWmnUwDReQ15BwqQXzyqVQ6U8LardEf`
