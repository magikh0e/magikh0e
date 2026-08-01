```
███╗   ███╗ █████╗  ██████╗ ██╗██╗  ██╗██╗  ██╗ ██████╗ ███████╗
████╗ ████║██╔══██╗██╔════╝ ██║██║ ██╔╝██║  ██║██╔═████╗██╔════╝
██╔████╔██║███████║██║  ███╗██║█████╔╝ ███████║██║██╔██║█████╗
██║╚██╔╝██║██╔══██║██║   ██║██║██╔═██╗ ██╔══██║████╔╝██║██╔══╝
██║ ╚═╝ ██║██║  ██║╚██████╔╝██║██║  ██╗██║  ██║╚██████╔╝███████╗
╚═╝     ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝
> security research · home automation · car hacking · breaking things on purpose
```

```console
visitor@github:~$ whoami
magikh0e — infosec tinkerer. I automate my house, hack my Jeep,
           and write down what worked before I forget.

visitor@github:~$ cat .plan
"Hackers do it with all sorts of characters."
```

[![Website](https://img.shields.io/badge/magikh0e.pl-0a0a0a?style=flat-square&logo=firefox&logoColor=00ff9c)](https://magikh0e.pl)
[![Tropical Roots Maui](https://img.shields.io/badge/Tropical%20Roots%20Maui-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPHBhdGggZD0iTTExIDIwQTcgNyAwIDAgMSA5LjggNi4xQzE1LjUgNSAxNyA0LjQ4IDE5IDJjMSAyIDIgNC4xOCAyIDggMCA1LjUtNC43OCAxMC0xMCAxMFoiLz48cGF0aCBkPSJNMiAyMWMwLTMgMS44NS01LjM2IDUuMDgtNiIvPjwvc3ZnPg%3D%3D)](https://tropicalrootsmaui.com)
[![Mastodon](https://img.shields.io/badge/@magikh0e-0a0a0a?style=flat-square&logo=mastodon&logoColor=6364ff)](https://infosec.exchange/@magikh0e)
[![Home Assistant](https://img.shields.io/badge/Home%20Assistant-0a0a0a?style=flat-square&logo=homeassistant&logoColor=18bcf2)](https://magikh0e.pl/pubHomeAutomation/)
[![Exploits](https://img.shields.io/badge/exploit%20archive-0a0a0a?style=flat-square&logo=hackthebox&logoColor=9fef00)](https://magikh0e.pl/exploits/)
[![Cults3D](https://img.shields.io/badge/Cults3D-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xMiAyIDMgN3YxMGw5IDUgOS01VjdaIi8%2BPHBhdGggZD0iTTMgN2w5IDUgOS01TTEyIDEydjEwIi8%2BPC9zdmc%2B)](https://cults3d.com/en/users/magikh0e/3d-models)

---

```console
visitor@github:~$ ls ~/projects/
```

### 🏠 home-automation/
- **[haos_stuff](https://github.com/magikh0e/haos_stuff)** — my full Home Assistant OS setup: hardware dashboards (grow tents, power stations, 3D printers, unified TV control), automations, voice briefings, custom blueprints, and a reverse-engineered Cannatrol BLE protocol
- **[ha-home-grow](https://github.com/magikh0e/ha-home-grow)** — native HACS integration for tracking plants (growth stage, health, age)
- **[ha-medication-reminder](https://github.com/magikh0e/ha-medication-reminder)** · **[-yaml](https://github.com/magikh0e/ha-medication-reminder-yaml)** — UI-managed dose tracking for people and pets: multi-dose schedules, nag + escalation reminders, refill and cost tracking, and fractional doses; custom-integration and YAML-package flavors

### 🌱 gardening/
- **[PlantManager](https://github.com/magikh0e/PlantManager)** — a complete offline cultivation manager in a single HTML file: mother and clone tracking, feeding and environment logs, KNF and VPD/DLI calculators, harvest, trichome, and cost tracking, lineage and genetic trees, and 30+ SVG analytics charts. Local-first, no accounts, no tracking.

### 🚗 car-hacking/
- **[canbus-scripts](https://github.com/magikh0e/canbus-scripts)** — bash + can-utils diagnostics over SocketCAN: OBD-II PIDs, DTC clearing, and a live engine dashboard for Linux / Raspberry Pi rigs
- **[jeep-jl-powernet-scripts](https://github.com/magikh0e/jeep-jl-powernet-scripts)** — Linux/SocketCAN tooling for the 2018+ Jeep Wrangler (JL) "Powernet" CAN bus: read sensors, drive the HVAC and EVIC dash, honk, hold RPM, and live-dashboard the bus
- **[bitpirate-to-savvycan](https://github.com/magikh0e/bitpirate-to-savvycan)** — Python tools to turn an [ESP32 Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) CAN capture into a SavvyCAN (GVRET) CSV with optional DBC decoding, plus a Wi-Fi capture fetcher; stdlib only

### 🔐 security/
- **[Wordlists](https://github.com/magikh0e/Wordlists)** — aggregated, SecLists-derived security-testing wordlists: discovery, fuzzing, passwords, usernames, payloads, and IOCs
- **[CVEs](https://github.com/magikh0e/CVEs)** — proof-of-concept exploit code for select CVEs
- **[FlipperZero_Stuff](https://github.com/magikh0e/FlipperZero_Stuff)** — custom firmware, Sub-GHz & IR captures, NFC/RFID, BadUSB payloads, external hardware, and curated tools/links for the Flipper Zero

### 🖥️ self-hosted/
- **[open-relay](https://github.com/magikh0e/open-relay)** — self-hosted, end-to-end-encrypted chat service (FastAPI + React, native [Tauri](https://tauri.app) desktop app). Channels, threads, DMs with browser-side E2EE and safety numbers — no company in the middle
- **[volcano-hybrid-control](https://github.com/magikh0e/volcano-hybrid-control)** — browser Web Bluetooth control for the Storz & Bickel Volcano Hybrid (temperature, heat, fan, presets, bag fill), no app or backend; BLE protocol from [home-assistant-volcano-hybrid](https://github.com/SavageNL/home-assistant-volcano-hybrid)

### 🖨️ 3d-printing/
- **[PrintVault](https://github.com/magikh0e/PrintVault)** — local-first manager for 3D print files: indexes your folders in place, reads slicer settings from gcode, looks inside unextracted archives, and finds duplicates. Browser or desktop, nothing uploaded
- **[wisblock-case-generator](https://github.com/magikh0e/wisblock-case-generator)** — parametric OpenSCAD case for the RAK19007 + RAK4631 Meshtastic node, snap or screw lid, every dimension tunable
- **[heltec-v4-case-generator](https://github.com/magikh0e/heltec-v4-case-generator)** — parametric OpenSCAD case for the Heltec WiFi LoRa 32 V4, OLED window + SMA antenna option, ships print-ready STLs

### 🌐 the-site/
- **[magikh0e.pl](https://magikh0e.pl)** — exploit archive, hardware & car-hacking guides, home-lab write-ups, and a few infosec browser games ([Hack the Gibson](https://magikh0e.pl/gibson/), [Exploit-dle](https://magikh0e.pl/exploit-dle/), [Crypto-dle](https://magikh0e.pl/crypto-dle/))

---

```console
visitor@github:~$ uname -a && cat /etc/stack
```

![Home Assistant](https://img.shields.io/badge/-Home%20Assistant-0a0a0a?style=flat-square&logo=homeassistant&logoColor=18bcf2)
![ESPHome](https://img.shields.io/badge/-ESPHome-0a0a0a?style=flat-square&logo=espressif&logoColor=e7352c)
![Linux](https://img.shields.io/badge/-Linux-0a0a0a?style=flat-square&logo=linux&logoColor=ffd43b)
![BSD](https://img.shields.io/badge/-BSD-0a0a0a?style=flat-square&logo=bsd&logoColor=ef4444)
![UNIX](https://img.shields.io/badge/-UNIX-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPHJlY3QgeD0iMiIgeT0iMyIgd2lkdGg9IjIwIiBoZWlnaHQ9IjE4IiByeD0iMiIvPjxwYXRoIGQ9Ik02IDlsMyAzLTMgM00xMyAxNWg1Ii8%2BPC9zdmc%2B)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-0a0a0a?style=flat-square&logo=raspberrypi&logoColor=c51a4a)
![Python](https://img.shields.io/badge/-Python-0a0a0a?style=flat-square&logo=python&logoColor=3776ab)
![C](https://img.shields.io/badge/-C-0a0a0a?style=flat-square&logo=c&logoColor=a8b9cc)
![Rust](https://img.shields.io/badge/-Rust-0a0a0a?style=flat-square&logo=rust&logoColor=dea584)
![Perl](https://img.shields.io/badge/-Perl-0a0a0a?style=flat-square&logo=perl&logoColor=00ff9c)
![Assembly](https://img.shields.io/badge/-Assembly-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjYiIHk9IjYiIHdpZHRoPSIxMiIgaGVpZ2h0PSIxMiIgcng9IjEiLz48cGF0aCBkPSJNOSAxdjNNMTUgMXYzTTkgMjB2M00xNSAyMHYzTTEgOWgzTTEgMTVoM00yMCA5aDNNMjAgMTVoMyIvPjwvc3ZnPg%3D%3D)
![Bash](https://img.shields.io/badge/-Bash-0a0a0a?style=flat-square&logo=gnubash&logoColor=4eaa25)
![YAML](https://img.shields.io/badge/-YAML-0a0a0a?style=flat-square&logo=yaml&logoColor=cb171e)
![CAN bus](https://img.shields.io/badge/-CAN%20bus-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPHBhdGggZD0iTTIgMTJoMjBNNiAxMlY3TTEyIDEyVjdNMTggMTJWNyIvPjxyZWN0IHg9IjMiIHk9IjMiIHdpZHRoPSI2IiBoZWlnaHQ9IjQiIHJ4PSIxIi8%2BPHJlY3QgeD0iMTUiIHk9IjMiIHdpZHRoPSI2IiBoZWlnaHQ9IjQiIHJ4PSIxIi8%2BPGNpcmNsZSBjeD0iMTIiIGN5PSI1IiByPSIxLjUiLz48L3N2Zz4%3D)

---

<div align="center">

[![Followers](https://img.shields.io/github/followers/magikh0e?style=for-the-badge&logo=github&logoColor=00ff9c&label=FOLLOWERS&labelColor=0a0a0a&color=00ff9c)](https://github.com/magikh0e?tab=followers)
[![Flipper repo stars](https://img.shields.io/github/stars/magikh0e/FlipperZero_Stuff?style=for-the-badge&logo=github&logoColor=00ff9c&label=FLIPPER%20%E2%98%85&labelColor=0a0a0a&color=00ff9c)](https://github.com/magikh0e/FlipperZero_Stuff)

</div>

```console
visitor@github:~$ logout
Connection to github.com closed.
```
