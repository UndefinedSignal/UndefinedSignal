<div align="center">

# Hi, I'm Arvi 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=640&lines=Software+developer;VR%2FXR+tracking+tinkerer;Teaching+VR+headsets+tricks+they+can't+do+out+of+the+box;C%2B%2B+%C2%B7+C%23+%C2%B7+Python+%C2%B7+JS)](https://git.io/typing-svg)

**I build the missing pieces of VR tracking — and the tools around it.**

[![Profile views](https://komarev.com/ghpvc/?username=UndefinedSignal&style=flat-square&color=58a6ff&label=Profile+views)](https://github.com/UndefinedSignal)
[![GitHub followers](https://img.shields.io/github/followers/UndefinedSignal?style=flat-square&color=58a6ff&label=Followers)](https://github.com/UndefinedSignal?tab=followers)
[![Hireable](https://img.shields.io/badge/Open%20to%20opportunities-yes-2ea44f?style=flat-square)](https://github.com/UndefinedSignal)

</div>

---

## 🧭 About me

Software developer who spends his free time deep in VR hardware: camera pipelines, face tracking, frame timing, and everything else that makes a headset do more than the vendor intended. On GitHub since 2012.

- 🔭 Currently working on **MouthLink** — custom mouth tracking for the PICO 4 Pro, with channels the stock model simply doesn't have (tongue direction, separate cheeks, TongueRoll)
- 🥽 Main playground: **PICO 4 Pro (rooted), SteamVR, VRCFaceTracking, VRChat**
- 🛠 I like tools that solve one annoying problem well — see **LANplorer** and **VrHitchLog**
- 🎮 Side interests: game dev (Unreal Engine), Unity editor tooling, Discord bots, WoW RP addons

---

## ⭐ Featured projects

### 🗣 MouthLink — custom mouth tracking ecosystem for PICO 4 Pro

A full pipeline: the headset's raw mouth camera is streamed to a PC, where your own trained model turns it into blendshapes for VRChat via VRCFaceTracking — personal calibration for *your* face and channels the stock tracker doesn't have at all.

| Repo | What it does | Tech |
|---|---|---|
| [**MouthLink**](https://github.com/UndefinedSignal/MouthLink) | PC side of the pipeline: UDP protocol, receiver, session recording, prompted calibration, dataset builder, PyTorch training (ONNX export) | Python, .NET |
| [**PicoET-Enhance-MouthLink**](https://github.com/UndefinedSignal/PicoET-Enhance-MouthLink) | Headset-side fork of PicoET-Enhance: streams the raw mouth camera (400×400 IR @ 90 Hz) plus per-frame stock labels with matching timestamps | C++ |
| [**UnifiedPicoModule-MouthLink**](https://github.com/UndefinedSignal/UnifiedPicoModule-MouthLink) | VRCFaceTracking module: runs the model live on CPU (~2–3 ms/frame) and layers tongue direction (Left/Right/Up/Down) over stock tracking | C# |
| [**QuestLHSync-pico4pro**](https://github.com/UndefinedSignal/QuestLHSync-pico4pro) | Aligns SteamVR Lighthouse trackers/controllers with a standalone headset's own inside-out tracking | C++ |

Verified on real hardware: 90 fps stream at ~20 ms latency, stock eye/mouth tracking untouched, model evaluated on unseen headset fits.

### 🔧 Other things I've built

| Repo | What it does | Tech |
|---|---|---|
| [**arvi-vrc-tools**](https://github.com/UndefinedSignal/arvi-vrc-tools) | Unity/VRChat editor tools as VPM packages: Blend Tree Param Picker, Parameter Driver Picker, Clip Browser — installable straight into VCC | C#, Unity |
| [**VrHitchLog**](https://github.com/UndefinedSignal/VrHitchLog) | Hunts periodic VR micro-stutters: SteamVR frame timing + per-core CPU stalls + 50 Hz headset ping. Caught a Xiaomi router's `trafficd` freezing VR every 5.2 s | C# |
| [**LANplorer**](https://github.com/UndefinedSignal/LANplorer) | Zero-dependency LAN text/file exchange between machines — one `server.js`, a browser on the other end, UI styled as a Windows XP Explorer window | JavaScript (Node) |
| [**DiscordActivityPulse**](https://github.com/UndefinedSignal/DiscordActivityPulse) | Discord bot that monitors forum activity and pulses it to your server | JavaScript |
| [**RPS-Emotes**](https://github.com/UndefinedSignal/RPS-Emotes) | Emotes addon for WoW RP servers | Lua |

---

## 🧰 Tech stack

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

![SteamVR](https://img.shields.io/badge/SteamVR-1b2838?style=for-the-badge&logo=steam&logoColor=white)
![PICO](https://img.shields.io/badge/PICO%204%20Pro-00A9CE?style=for-the-badge&logoColor=white)
![VRChat](https://img.shields.io/badge/VRChat-35424A?style=for-the-badge&logoColor=white)

---

## 📊 Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=UndefinedSignal&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&rank_icon=github" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=UndefinedSignal&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top languages"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=UndefinedSignal&theme=github-dark-blue&hide_border=true" alt="GitHub streak"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=UndefinedSignal&theme=github-compact&hide_border=true&area=true" alt="Activity graph"/>
</div>

---

<details>
<summary><b>🇷🇺 По-русски</b></summary>
<br>

Привет! Я Арви — разработчик, который в свободное время ковыряет VR-железо: камеры, трекинг лица, тайминги кадров и всё, что заставляет шлем делать больше, чем задумал вендор.

- 🔭 Сейчас работаю над **MouthLink** — собственным трекингом рта для PICO 4 Pro с каналами, которых у стоковой модели нет вообще (направление языка, отдельные щёки, TongueRoll)
- 🥽 Основной стенд: **PICO 4 Pro (root), SteamVR, VRCFaceTracking, VRChat**
- 🛠 Люблю инструменты, которые хорошо решают одну раздражающую проблему — смотри **LANplorer** и **VrHitchLog**
- 🎮 В стороне: геймдев (Unreal Engine), редакторские тулы для Unity, боты для Discord, аддоны для WoW RP

**Главные проекты:**

- [**MouthLink**](https://github.com/UndefinedSignal/MouthLink) — кастомный трекинг рта: кадры с камеры шлема → своя модель → blendshapes в VRChat
- [**arvi-vrc-tools**](https://github.com/UndefinedSignal/arvi-vrc-tools) — редакторские тулы для Unity/VRChat, ставятся как VPM-пакеты через VCC
- [**VrHitchLog**](https://github.com/UndefinedSignal/VrHitchLog) — поиск периодических микрофризов в VR (поймал роутер Xiaomi, который вешал VR каждые 5,2 секунды)
- [**LANplorer**](https://github.com/UndefinedSignal/LANplorer) — обмен текстом и файлами в локальной сети без единой зависимости, интерфейс в стиле проводника Windows XP

Открыт к интересным предложениям — можно связаться через issue в любом из репозиториев.

</details>

---

<div align="center">
  <i>"The stock model can't do that" is a starting point, not an answer.</i>
</div>
