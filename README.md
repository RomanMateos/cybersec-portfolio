# Portafolio de Ethical Hacking / Pentesting

Registro técnico de laboratorios de ciberseguridad ofensiva realizados en un entorno
controlado (Kali Linux + VirtualBox + NAT Network), siguiendo la metodología **PTES**
(Penetration Testing Execution Standard) y el estándar de severidad **CVSS v3.1**.

> ⚠️ **Uso exclusivamente educativo.** Todas las pruebas se ejecutan sobre máquinas
> vulnerables de laboratorio (Metasploitable 2/3, VulnHub) dentro de una red aislada
> (NAT Network), sin exposición a internet ni a terceros.

## Objetivo del repositorio

Documentar el proceso de aprendizaje en Ethical Hacking / Blue Team, como evidencia
práctica de cara a una futura especialización en investigación de cibercrimen y
forense digital .

## Estructura

```
├── 01-lab-setup/              # Instalación de Kali, VirtualBox, Metasploitable 2/3, Nessus
├── 02-recon-osint/            # Google Dorks, Shodan, Sherlock
├── 03-active-attack/          # Phishing, OWASP ZAP, explotación (kill chain completo)
├── 04-reports/                # Informes técnicos individuales por laboratorio (CVSS v3.1)
└── docs/
    └── metodologia.md         # PTES, CVSS v3.1, mapeo con hallazgos
```

## Metodología aplicada (PTES)

| Fase | Carpeta correspondiente |
|---|---|
| Pre-engagement / Intelligence Gathering | `02-recon-osint/` |
| Threat Modeling / Vulnerability Analysis | `03-active-attack/` (ZAP, Nessus) |
| Exploitation / Post-Exploitation | `03-active-attack/` (Coffee Addicts, etc.) |
| Reporting | `04-reports/` |

## Entorno de laboratorio

- **Hipervisor:** VirtualBox
- **Red:** NAT Network (segmento aislado, sin salida directa a internet salvo actualizaciones)
- **Atacante:** Kali Linux
- **Objetivos:** Metasploitable 2, Metasploitable 3, máquinas de VulnHub (ej. Coffee Addicts)
- **Escáner de vulnerabilidades:** Nessus (instalado en Kali)

## Registro de laboratorios

| # | Laboratorio | Estado | Informe |
|---|---|---|---|
| 01 | Setup del entorno (Kali, VirtualBox, Metasploitable 2/3, Nessus) | 🔄 En curso | [Ver informe](04-reports/01-lab-setup.md) |
| 02 | OSINT: Google Dorks, Shodan, Sherlock | ⬜ Pendiente | — |
| 03 | Explotación completa (Coffee Addicts) | ⬜ Pendiente | — |

---
*Autor: Román Suárez — Ingeniería en Informática, mención Ingeniería de Datos, Duoc UC*
