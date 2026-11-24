<p align="center">
  <img src="assets/suite-banner.svg" alt="rodvay Native Zero-Bloat Windows Suite" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-0f172a?style=flat-square&logo=windows&logoColor=38bdf8" alt="Windows 10/11"/>
  <img src="https://img.shields.io/badge/C%23%20%2F%20Win32-Native%20APIs-1e293b?style=flat-square&logo=csharp&logoColor=34d399" alt="Native Win32"/>
  <img src="https://img.shields.io/badge/Dependencies-Zero-1e293b?style=flat-square&color=a78bfa" alt="Zero Dependencies"/>
  <img src="https://img.shields.io/badge/Telemetry-None-1e293b?style=flat-square&color=34d399" alt="Zero Telemetry"/>
  <img src="https://img.shields.io/badge/License-MIT-1e293b?style=flat-square&color=fbbf24" alt="MIT License"/>
  <a href="https://linux.do"><img src="https://img.shields.io/badge/Community-LINUX%20DO-1C1C1E?style=flat-square&logo=linux&logoColor=38BDF8" alt="LINUX DO Community"/></a>
</p>

---

### Why This Suite Exists

Modern Windows utilities routinely ship **150 MB+ Electron wrappers** and silent background updaters just to read a sensor, clean a temp folder, kill a port, or dim a monitor.

Every tool below is engineered from scratch directly on **native Windows APIs** (`Win32`, `iphlpapi`, `dxva2`, `dwmapi`, `gdi32`, `kernel32`) — **single portable executable**, **zero installers**, **zero telemetry**, **reversible safety**, and **trilingual UI (`EN / TR / 简体中文`)**.

---

## Native Zero-Bloat Windows Suite

> **Want everything in one place?** Grab [**ZeroBox**](https://github.com/rodvay/ZeroBox) (`~81 KB`) — the official on-demand modular toolbox & unified system tray launcher that installs, SHA-256 verifies, updates, or removes any tool below with 1 click!

| Tool | Category | Size | What It Does | Latest | Stars | Download |
| :--- | :--- | :---: | :--- | :---: | :---: | :---: |
| **[ZeroBox](https://github.com/rodvay/ZeroBox)** | Modular Hub | `~81 KB` | On-demand plugin launcher, PE/ZIP + SHA-256 verified installer, 3-tier mirror failover & unified system tray | [![Release](https://img.shields.io/github/v/release/rodvay/ZeroBox?style=flat-square&color=38bdf8&label=)](https://github.com/rodvay/ZeroBox/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/ZeroBox?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/ZeroBox/stargazers) | [EXE](https://github.com/rodvay/ZeroBox/releases/latest) |
| **[PCUptime](https://github.com/rodvay/PCUptime)** | Diagnostics | `~50 KB` | Real uptime, Fast Startup detection, BSOD crash & Sleep/Wake event timeline | [![Release](https://img.shields.io/github/v/release/rodvay/PCUptime?style=flat-square&color=38bdf8&label=)](https://github.com/rodvay/PCUptime/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/PCUptime?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/PCUptime/stargazers) | [EXE](https://github.com/rodvay/PCUptime/releases/latest) |
| **[SafeSweep](https://github.com/rodvay/SafeSweep)** | Maintenance | `~70 KB` | Transparent 2-step system junk, browser cache & Windows Update cleaner with preview | [![Release](https://img.shields.io/github/v/release/rodvay/SafeSweep?style=flat-square&color=34d399&label=)](https://github.com/rodvay/SafeSweep/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/SafeSweep?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/SafeSweep/stargazers) | [EXE](https://github.com/rodvay/SafeSweep/releases/latest) |
| **[WinForge](https://github.com/rodvay/WinForge)** | System Tweaks | `~150 KB` | Reversible Windows 10/11 privacy/performance optimizer, AppX debloater & Winget manager | [![Release](https://img.shields.io/github/v/release/rodvay/WinForge?style=flat-square&color=a78bfa&label=)](https://github.com/rodvay/WinForge/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/WinForge?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/WinForge/stargazers) | [EXE](https://github.com/rodvay/WinForge/releases/latest) |
| **[CorePulse](https://github.com/rodvay/CorePulse)** | Hardware & HUD | `~230 KB` | Live CPU/GPU/RAM sensors, custom PWM fan curves & 32-bit Gaming HUD (`0px` flush + free drag) | [![Release](https://img.shields.io/github/v/release/rodvay/CorePulse?style=flat-square&color=f87171&label=)](https://github.com/rodvay/CorePulse/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/CorePulse?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/CorePulse/stargazers) | [ZIP](https://github.com/rodvay/CorePulse/releases/latest) |
| **[PortWatch](https://github.com/rodvay/PortWatch)** | Network & Firewall | `~105 KB` | Live TCP/UDP port killer (30+ dev/proxy tags), `0px` Mini Speed HUD & 1-click reversible firewall | [![Release](https://img.shields.io/github/v/release/rodvay/PortWatch?style=flat-square&color=34d399&label=)](https://github.com/rodvay/PortWatch/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/PortWatch?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/PortWatch/stargazers) | [EXE](https://github.com/rodvay/PortWatch/releases/latest) |
| **[LumiBar](https://github.com/rodvay/LumiBar)** | Display & Power | `~86 KB` | Hardware DDC/CI multi-monitor brightness & contrast, Warm Night Tint, Keep-Awake & Smart Idle sleep | [![Release](https://img.shields.io/github/v/release/rodvay/LumiBar?style=flat-square&color=fbbf24&label=)](https://github.com/rodvay/LumiBar/releases/latest) | [![Stars](https://img.shields.io/github/stars/rodvay/LumiBar?style=flat-square&color=fbbf24&label=★)](https://github.com/rodvay/LumiBar/stargazers) | [EXE](https://github.com/rodvay/LumiBar/releases/latest) |

---

### Shared Engineering Principles

- **Tiny & Instant:** Every app launches in milliseconds and uses a fraction of the RAM of Electron/WebView alternatives.
- **Reversible & Safe by Default:** System tweaks can be reverted, firewall rules are isolated & 1-click removable, monitor gamma restores automatically on exit, critical OS processes are locked, and power timers include a 60-second cancellable grace warning.
- **Zero-SDK Reproducible Builds:** Every repo includes `build.ps1` / `build.bat` that builds directly with Windows' inbox .NET Framework 4.x `csc.exe` — inspect the C# source and compile your own binary in 2 seconds.
- **First-Class Trilingual & High-DPI UI:** Automatic OS locale detection (`English`, `Türkçe`, `简体中文`), dark title bars, Per-Monitor V2 DPI scaling, System Tray integration, and Single-Instance Mutex.

---

### 简体中文速览 · Türkçe Özet

- **中文：** 本主页收录 **ZeroBox 模块化工具箱**（仅 81 KB，按需插件式安装/更新/三级镜像容灾/统一托盘管理）以及 **6 款原生零臃肿 Windows 10/11 开源工具**（单文件 ~50–230 KB，告别 Electron 内存占用与后台遥测）：涵盖系统运行/蓝屏诊断 (**PCUptime**)、透明垃圾清理 (**SafeSweep**)、可逆系统优化 (**WinForge**)、硬件监控与 32-bit 游戏顶栏 (**CorePulse**)、端口查杀与可逆防火墙 (**PortWatch**)，以及 DDC/CI 硬件亮度调节与智能防休眠 (**LumiBar**)。全部原生支持 **简体中文**，开源免费（MIT）。
- **Türkçe:** Bu profilde **ZeroBox Modüler Araç Kutusu** (yalnızca 81 KB, isteğe bağlı eklenti yöneticisi, 3 katmanlı ayna desteği ve birleşik sistem tepsisi) ile Windows 10/11 için kurulumsuz, telemetrisiz ve tamamı **~50–230 KB** boyutunda **6 adet açık kaynak yerel Windows aracı** yer alır: **PCUptime**, **SafeSweep**, **WinForge**, **CorePulse**, **PortWatch** ve **LumiBar**. Tamamı yerleşik **Türkçe** dil desteği ve MIT lisansı ile gelir.

---

<p align="center">
  If any of these micro-tools saved you RAM or time, a ⭐ helps more people discover bloat-free Windows software!
</p>
