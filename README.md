<div align="center">

<img src="./assets/banner.svg" alt="Dmitry Prokofev — XAKER — Robotics Engineer" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&width=600&lines=Ground+Control+Systems+for+UGVs;%D0%9D%D0%B0%D0%B7%D0%B5%D0%BC%D0%BD%D1%8B%D0%B5+%D1%81%D1%82%D0%B0%D0%BD%D1%86%D0%B8%D0%B8+%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F+%D0%B4%D1%80%D0%BE%D0%BD%D0%B0%D0%BC%D0%B8;Python+%C2%B7+MAVLink+%C2%B7+CRSF+%C2%B7+SBC;Robotics+Engineer" alt="Typing SVG"/>

</div>

## Проекты HAUGER IT

| Проект | Публичная витрина на GitHub | Сайт | Статус |
|---|---|---|---|
| **RoverLink** — станция на наземной машине | [Открыть RoverLink](https://github.com/xaker-enginer/roverlink) | [hauger-it.com/roverlink](https://hauger-it.com/roverlink/) | ТП-34 внедрён, испытания прошли успешно |
| **RoverLink НСУ** — программа оператора для Windows | [Описание НСУ](https://github.com/xaker-enginer/roverlink/blob/main/docs/nsu.md) | [hauger-it.com/nsu](https://hauger-it.com/nsu/) | 0.1.0-beta2 |
| **GCS-G** — наземная станция БПЛА | [Открыть GCS-G](https://github.com/xaker-enginer/gcs-g) | [hauger-it.com/gcs-g](https://hauger-it.com/gcs-g/) | Стендовая разработка, 0.7.4-dev |
| **Рельеф** — карты, высоты и радиолинии | [Открыть Рельеф](https://github.com/xaker-enginer/relief) | [hauger-it.com/relief](https://hauger-it.com/relief/) | Нативные Android и iOS, beta13 |

НСУ — отдельный проект; его публичное описание пока размещено в витрине RoverLink.
Исходники НСУ, GCS-G и нативного «Рельефа» хранятся в закрытых репозиториях.

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

### RoverLink — бортовая станция наземной машины

Связывает Mission Planner, камеры и систему управления машины. Raspberry Pi
и Radxa ROCK 5C, веб-панель, RTSP-видео, диагностика и удалённая связь через ZeroTier.

**Три платформы и четыре режима:** Богомол B5 без полётного контроллера,
Богомол B5 с полётным контроллером, Антилопа 4×4 и ТП-34.
**ТП-34 внедрён; испытания прошли успешно.** Для него развивается отдельная
ветка с микшером дневных, ночных и задних камер и аппаратным кодированием видео.

[Публичная витрина RoverLink](https://github.com/xaker-enginer/roverlink) ·
[Проект на сайте](https://hauger-it.com/roverlink/)

Основная разработка хранится в приватном репозитории. Специализированные
ветки поставляются отдельно; номер бета-сборки не означает новый стабильный релиз.

## Другие проекты HAUGER IT

### RoverLink НСУ — приложение оператора для Windows

Отдельный проект поста управления: поиск станции, RTSP H.264/H.265,
выбор и калибровка HID-пульта, назначение каналов и передача MAVLink.
Видеокомпоненты входят в автономный установщик.

**0.1.0-beta2:** программные проверки выполнены; проверка с физическим
пультом и машиной ещё предстоит. Исходники приватные.

[Возможности и статус НСУ](https://github.com/xaker-enginer/roverlink/blob/main/docs/nsu.md)

### GCS-G — наземная станция для БПЛА

Raspberry Pi 5, веб-панель, RC/CRSF через Pico, управление видеоприёмником,
USB-захват и RTSP H.264. Сканер 40 каналов для совместимого приёмного тракта.

**0.7.4-dev, стендовая разработка.** Подтверждены отдельные проверки
управления и видео; полётные испытания и проверка failsafe реального борта
не объявляются завершёнными. Исходники приватные.

[Публичная витрина GCS-G](https://github.com/xaker-enginer/gcs-g)

### Рельеф — карты, высоты и радиолинии

Нативные Android и iOS: офлайн-карты и рельеф, профиль радиолинии и зона
Френеля, свои точки и маршруты, координаты СК-42 и WGS-84, обмен GPX/KML,
управление ротатором мачты по Wi-Fi.

**beta13:** Android — основная платформа; iOS — нативное приложение с
установкой подписанного IPA. Старая веб-версия заморожена. Исходники приватные.

[Публичная витрина Рельефа](https://github.com/xaker-enginer/relief)

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

[![Telegram](https://img.shields.io/badge/TELEGRAM-@dmitry__haker-0d1117?style=for-the-badge&logo=telegram&logoColor=26A5E4&labelColor=161b22&color=26A5E4)](https://t.me/dmitry_haker)
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
