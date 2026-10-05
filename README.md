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
- **[ha-medication-reminder](https://github.com/magikh0e/ha-medication-reminder)** · **[-yaml](https://github.com/magikh0e/ha-medication-reminder-yaml)** — UI-managed dose tracking for people and pets: multi-dose schedules, nag + escalation reminders, refill and cost tracking, and fractional doses; custom-integration and YAML-package flavors, [guide](https://magikh0e.pl/pubHomeAutomation/medication-reminder.html)
- **[ha-creality-dashboards](https://github.com/magikh0e/ha-creality-dashboards)** — ready-to-use Home Assistant dashboards for Creality printers (K2 Plus and more), built with stock Lovelace cards only so no custom frontend cards are needed; pairs with the ha_creality_ws integration

### 🌱 gardening/
- **[PlantManager](https://github.com/magikh0e/PlantManager)** — a complete offline cultivation manager in a single HTML file: mother and clone tracking, feeding and environment logs, KNF and VPD/DLI calculators, harvest, trichome, and cost tracking, lineage and genetic trees, and 30+ SVG analytics charts. Local-first, no accounts, no tracking.

### 🚗 car-hacking/
- **[canbus-scripts](https://github.com/magikh0e/canbus-scripts)** — bash + can-utils diagnostics over SocketCAN: OBD-II PIDs, DTC clearing, and a live engine dashboard for Linux / Raspberry Pi rigs
- **[jeep-jl-powernet-scripts](https://github.com/magikh0e/jeep-jl-powernet-scripts)** — Linux/SocketCAN tooling for the 2018+ Jeep Wrangler (JL) "Powernet" CAN bus: read sensors, drive the HVAC and EVIC dash, honk, hold RPM, and live-dashboard the bus
- **[bitpirate-to-savvycan](https://github.com/magikh0e/bitpirate-to-savvycan)** — Python tools to turn an [ESP32 Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) CAN capture into a SavvyCAN (GVRET) CSV with optional DBC decoding, plus a Wi-Fi capture fetcher; stdlib only

### 🔐 security/
- **[pueo](https://github.com/magikh0e/pueo)** — a handheld multi-radio field tool on a stock ESP32 “cheap yellow display”: Wi-Fi and BLE reconnaissance, sub-GHz capture and replay, NFC read and clone, GPS wardriving, and jam detection, in a printed enclosure zoned to keep the radios apart. Reproducible builds, a dimensioned case, and write-ups at [pueo.magikh0e.pl](https://pueo.magikh0e.pl); forked from [ESP32-DIV](https://github.com/cifertech/ESP32-DIV) by CiferTech
- **[surveillance-signatures](https://github.com/magikh0e/surveillance-signatures)** — WiFi/BLE identifiers that surveillance hardware broadcasts unprompted (plate readers, fixed and body cameras, smart glasses, item trackers, fleet modules, pentest kit): 266 graded signatures across nine tables, as Markdown, CSV and JSON, pulled from [Pueo](https://github.com/magikh0e/pueo)'s detector
- **[Wordlists](https://github.com/magikh0e/Wordlists)** — aggregated, SecLists-derived security-testing wordlists: discovery, fuzzing, passwords, usernames, payloads, and IOCs
- **[CVEs](https://github.com/magikh0e/CVEs)** — proof-of-concept exploit code for select CVEs
- **[FlipperZero_Stuff](https://github.com/magikh0e/FlipperZero_Stuff)** — custom firmware, Sub-GHz & IR captures, NFC/RFID, BadUSB payloads, external hardware, and curated tools/links for the Flipper Zero
- **[nmea_decode](https://github.com/magikh0e/nmea_decode)** — single-file NMEA 0183 decoder for GPS and AIS (file, serial, TCP or UDP; stdlib only, JSON / fix-summary output)

### 🖥️ self-hosted/
- **[open-relay](https://github.com/magikh0e/open-relay)** — self-hosted, end-to-end-encrypted chat service (FastAPI + React, native [Tauri](https://tauri.app) desktop app). Channels, threads, DMs with browser-side E2EE and safety numbers — no company in the middle
- **[volcano-hybrid-control](https://github.com/magikh0e/volcano-hybrid-control)** — browser Web Bluetooth control for the Storz & Bickel Volcano Hybrid (temperature, heat, fan, presets, bag fill), no app or backend; BLE protocol from [home-assistant-volcano-hybrid](https://github.com/SavageNL/home-assistant-volcano-hybrid)

### 🖨️ 3d-printing/
- **[PrintVault](https://github.com/magikh0e/PrintVault)** — local-first manager for 3D print files: indexes your folders in place, reads slicer settings from gcode, looks inside unextracted archives, and finds duplicates. Browser or desktop, nothing uploaded, [live](https://printvault.magikh0e.pl/app/)
- **[headfit](https://github.com/magikh0e/headfit)** — helmet and mask fit bench in one HTML file: build a head from three tape measurements, load an STL, and see where it collides before you print. Local-first, nothing uploaded, [live](https://printvault.magikh0e.pl/headfit.html)

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
![HTML](https://img.shields.io/badge/-HTML-0a0a0a?style=flat-square&logo=html5&logoColor=e34f26)
![CSS](https://img.shields.io/badge/-CSS-0a0a0a?style=flat-square&logo=css&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/-JavaScript-0a0a0a?style=flat-square&logo=javascript&logoColor=f7df1e)
![C](https://img.shields.io/badge/-C-0a0a0a?style=flat-square&logo=c&logoColor=a8b9cc)
![C++](https://img.shields.io/badge/-C%2B%2B-0a0a0a?style=flat-square&logo=cplusplus&logoColor=00599C)
![Rust](https://img.shields.io/badge/-Rust-0a0a0a?style=flat-square&logo=rust&logoColor=dea584)
![Assembly](https://img.shields.io/badge/-Assembly-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxyZWN0IHg9IjYiIHk9IjYiIHdpZHRoPSIxMiIgaGVpZ2h0PSIxMiIgcng9IjEiLz48cGF0aCBkPSJNOSAxdjNNMTUgMXYzTTkgMjB2M00xNSAyMHYzTTEgOWgzTTEgMTVoM00yMCA5aDNNMjAgMTVoMyIvPjwvc3ZnPg%3D%3D)
![Python](https://img.shields.io/badge/-Python-0a0a0a?style=flat-square&logo=python&logoColor=3776ab)
![Bash](https://img.shields.io/badge/-Bash-0a0a0a?style=flat-square&logo=gnubash&logoColor=4eaa25)
![Perl](https://img.shields.io/badge/-Perl-0a0a0a?style=flat-square&logo=perl&logoColor=00ff9c)
![YAML](https://img.shields.io/badge/-YAML-0a0a0a?style=flat-square&logo=yaml&logoColor=cb171e)
![CAN bus](https://img.shields.io/badge/-CAN%20bus-0a0a0a?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjljIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPHBhdGggZD0iTTIgMTJoMjBNNiAxMlY3TTEyIDEyVjdNMTggMTJWNyIvPjxyZWN0IHg9IjMiIHk9IjMiIHdpZHRoPSI2IiBoZWlnaHQ9IjQiIHJ4PSIxIi8%2BPHJlY3QgeD0iMTUiIHk9IjMiIHdpZHRoPSI2IiBoZWlnaHQ9IjQiIHJ4PSIxIi8%2BPGNpcmNsZSBjeD0iMTIiIGN5PSI1IiByPSIxLjUiLz48L3N2Zz4%3D)

---

```console
visitor@github:~$ cat ~/.stats
```

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=magikh0e&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=00ff9c&icon_color=00ff9c&text_color=b0b0b0" alt="magikh0e's GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=magikh0e&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=00ff9c&text_color=b0b0b0" alt="Top languages" height="165">
</p>

---

<div align="center">

[![Followers](https://img.shields.io/github/followers/magikh0e?style=for-the-badge&logo=github&logoColor=00ff9c&label=FOLLOWERS&labelColor=0a0a0a&color=00ff9c)](https://github.com/magikh0e?tab=followers)
[![Flipper repo stars](https://img.shields.io/github/stars/magikh0e/FlipperZero_Stuff?style=for-the-badge&logo=github&logoColor=00ff9c&label=FLIPPER%20%E2%98%85&labelColor=0a0a0a&color=00ff9c)](https://github.com/magikh0e/FlipperZero_Stuff)

</div>

```console
visitor@github:~$ logout
Connection to github.com closed.
```
