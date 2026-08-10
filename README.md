<div align="center">

<img src="./assets/banner.svg" alt="Dmitry Prokofev — XAKER — Robotics Engineer" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&width=600&lines=Ground+Control+Systems+for+UGVs;%D0%9D%D0%B0%D0%B7%D0%B5%D0%BC%D0%BD%D1%8B%D0%B5+%D1%81%D1%82%D0%B0%D0%BD%D1%86%D0%B8%D0%B8+%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F+%D0%B4%D1%80%D0%BE%D0%BD%D0%B0%D0%BC%D0%B8;Python+%C2%B7+MAVLink+%C2%B7+CRSF+%C2%B7+SBC;Robotics+Engineer" alt="Typing SVG"/>

</div>

```
┌──────────────────────────────────────────────────────────────┐
│  > whoami                                                    │
│  Dmitry Prokofev [XAKER] — Robotics Engineer                 │
│  > mission                                                   │
│  Building ground control systems for unmanned vehicles       │
│  > status                                                    │
│  ● ONLINE — LINK SECURE — MODE: AUTONOMOUS                   │
└──────────────────────────────────────────────────────────────┘
```

## `▌ ABOUT // О СЕБЕ`

**EN** — Robotics engineer focused on **unmanned ground vehicles (UGV)**. I design and build ground control stations that run on single-board computers — from protocol translation (MAVLink / CRSF / SBUS) and low-latency video pipelines to web-based control panels with real-time telemetry. Open-source core, commercial-grade reliability.

**RU** — Инженер-робототехник, специализируюсь на **беспилотных наземных машинах**. Проектирую и разрабатываю наземные станции управления на одноплатных компьютерах: трансляция протоколов (MAVLink / CRSF / SBUS), видеопотоки с низкой задержкой, веб-панель управления с телеметрией в реальном времени. Открытое ядро — надёжность коммерческого уровня.

```python
class RoboticsEngineer:
    name     = "Dmitry Prokofev"
    callsign = "XAKER"
    focus    = ["UGV", "ground control stations", "telemetry", "video streaming"]
    hardware = ["Raspberry Pi 4/5", "Radxa ROCK 5C", "ESP32", "flight controllers"]
    mission  = "reliable control links for unmanned machines"
```

## `▌ FLAGSHIP PROJECT // ФЛАГМАНСКИЙ ПРОЕКТ`

<div align="center">

<a href="https://github.com/xaker-enginer/roverlink">
<img src="./assets/roverlink-banner.svg" alt="RoverLink — Ground Control Station for UGVs" width="100%"/>
</a>

</div>

### 🛰 RoverLink — Ground Control Station for UGVs

**EN** — A ground control station for unmanned ground vehicles running on single-board computers. Two operational modes: a virtual CRSF-based flight controller for ESP32-equipped machines, and a transparent MAVLink USB relay for full flight controllers. Unified codebase across three SBC platforms. Web control panel, real-time telemetry, RTSP video pipeline, ZeroTier remote access, Mission Planner integration, failsafe logic.

**RU** — Наземная станция управления беспилотной машиной на одноплатном компьютере. Два режима работы: виртуальный полётный контроллер на базе CRSF для машин с ESP32 и прозрачный MAVLink USB-ретранслятор для полноценных полётных контроллеров. Единая кодовая база для трёх платформ. Веб-панель управления, телеметрия в реальном времени, видеотракт RTSP, удалённый доступ через ZeroTier, интеграция с Mission Planner, отработка failsafe.

<div align="center">

[![Repository](https://img.shields.io/badge/REPOSITORY-roverlink-0d1117?style=for-the-badge&logo=github&logoColor=22c55e&labelColor=161b22&color=22c55e)](https://github.com/xaker-enginer/roverlink)
[![License](https://img.shields.io/badge/LICENSE-GPL--3.0-0d1117?style=for-the-badge&logo=gnu&logoColor=f59e0b&labelColor=161b22&color=f59e0b)](https://github.com/xaker-enginer/roverlink/blob/main/LICENSE)
![Version](https://img.shields.io/badge/CORE-v2.2-0d1117?style=for-the-badge&labelColor=161b22&color=4ade80)

</div>

> ⚙️ **EN:** Core development happens in a private R&D repository; the open-source core is published under GPL-3.0 with a commercial branch offering extended per-device functionality.
> **RU:** Основная разработка ведётся в закрытом dev-репозитории; открытое ядро публикуется под GPL-3.0, коммерческая ветка даёт расширенную функциональность с активацией на устройство.

## `▌ TECH STACK // СТЕК`

<div align="center">

**` SOFTWARE `**

![Python](https://img.shields.io/badge/Python_3.11%2B-0d1117?style=for-the-badge&logo=python&logoColor=4ade80&labelColor=161b22)
![Flask](https://img.shields.io/badge/Flask-0d1117?style=for-the-badge&logo=flask&logoColor=e6edf3&labelColor=161b22)
![Socket.IO](https://img.shields.io/badge/Socket.IO-0d1117?style=for-the-badge&logo=socketdotio&logoColor=e6edf3&labelColor=161b22)
![FFmpeg](https://img.shields.io/badge/FFmpeg-0d1117?style=for-the-badge&logo=ffmpeg&logoColor=22c55e&labelColor=161b22)
![MediaMTX](https://img.shields.io/badge/MediaMTX-0d1117?style=for-the-badge&logoColor=e6edf3&labelColor=161b22&color=0d1117)

**` PROTOCOLS & COMMS `**

![MAVLink](https://img.shields.io/badge/MAVLink-0d1117?style=for-the-badge&labelColor=161b22&color=22c55e)
![CRSF](https://img.shields.io/badge/CRSF-0d1117?style=for-the-badge&labelColor=161b22&color=22c55e)
![SBUS](https://img.shields.io/badge/SBUS-0d1117?style=for-the-badge&labelColor=161b22&color=22c55e)
![RTSP](https://img.shields.io/badge/RTSP-0d1117?style=for-the-badge&labelColor=161b22&color=f59e0b)
![ZeroTier](https://img.shields.io/badge/ZeroTier-0d1117?style=for-the-badge&logo=zerotier&logoColor=f59e0b&labelColor=161b22)

**` HARDWARE & OS `**

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_4%2F5-0d1117?style=for-the-badge&logo=raspberrypi&logoColor=ff4d4d&labelColor=161b22)
![Radxa](https://img.shields.io/badge/Radxa_ROCK_5C-0d1117?style=for-the-badge&labelColor=161b22&color=4ade80)
![ESP32](https://img.shields.io/badge/ESP32-0d1117?style=for-the-badge&logo=espressif&logoColor=e6edf3&labelColor=161b22)
![Linux](https://img.shields.io/badge/Linux_%2F_systemd-0d1117?style=for-the-badge&logo=linux&logoColor=e6edf3&labelColor=161b22)

</div>

## `▌ TELEMETRY // СТАТИСТИКА`

<div align="center">

![Followers](https://img.shields.io/github/followers/xaker-enginer?style=for-the-badge&logo=github&logoColor=22c55e&label=FOLLOWERS&labelColor=161b22&color=22c55e)
![Stars](https://img.shields.io/github/stars/xaker-enginer/roverlink?style=for-the-badge&logo=github&logoColor=f59e0b&label=ROVERLINK%20STARS&labelColor=161b22&color=f59e0b)
![Top language](https://img.shields.io/github/languages/top/xaker-enginer/roverlink?style=for-the-badge&logo=python&logoColor=4ade80&label=CORE&labelColor=161b22&color=4ade80)

![Last commit](https://img.shields.io/github/last-commit/xaker-enginer/roverlink?style=for-the-badge&label=LAST%20COMMIT&labelColor=161b22&color=22c55e)
![Commit activity](https://img.shields.io/github/commit-activity/m/xaker-enginer/roverlink?style=for-the-badge&label=COMMITS%2FMONTH&labelColor=161b22&color=22c55e)
![Repo size](https://img.shields.io/github/repo-size/xaker-enginer/roverlink?style=for-the-badge&label=PAYLOAD&labelColor=161b22&color=4ade80)

<img src="https://streak-stats.demolab.com?user=xaker-enginer&theme=dark&background=0d1117&border=22c55e&ring=22c55e&fire=f59e0b&currStreakLabel=22c55e" alt="GitHub streak"/>

</div>

## `▌ COMMS // СВЯЗЬ`

<div align="center">

[![Telegram](https://img.shields.io/badge/TELEGRAM-@drmitry__haker-0d1117?style=for-the-badge&logo=telegram&logoColor=26A5E4&labelColor=161b22&color=26A5E4)](https://t.me/drmitry_haker)
[![Email](https://img.shields.io/badge/EMAIL-dmitry@hauger--it.com-0d1117?style=for-the-badge&logo=gmail&logoColor=f59e0b&labelColor=161b22&color=f59e0b)](mailto:dmitry@hauger-it.com)

<br/>

```
> EN: Open to collaboration on UGV / robotics / ground control projects.
> RU: Открыт к сотрудничеству по проектам UGV, робототехники и наземных станций управления.
```

<img src="https://komarev.com/ghpvc/?username=xaker-enginer&style=for-the-badge&color=22c55e&label=PROFILE+SCANS"/>

</div>

<div align="center">
<sub><code>// end of transmission ●</code></sub>
</div>
