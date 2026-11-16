# 📚 My GitHub Projects

**Legend:** 🔧 personal project · 🍴 fork (modified or adapted)

Forks that I have not modified are not listed. For forks, only the branches containing my own commits are shown.

- [🎛️ AUDIO](#️-audio)
- [🚁 FPV](#-fpv)

---

## 🎛️ AUDIO

| | Repo | Description | Language |
|:---:|---|---|---|
| 🎚️ | 🔧 [GSR24M-driver](https://github.com/FLORIANSV35/GSR24M-driver) | macOS driver (app + daemon + CoreAudio plug-in) for the Allen & Heath GS-R24 FireWire card, Apple silicon, no kext. | Swift |
| <img src="logos/SimplePlug.png" width="48" alt="SimplePlug"> | 🔧 [SimplePlug](https://github.com/FLORIANSV35/SimplePlug) | Minimal host for a single AU plugin with 2 in / 2 out (macOS). VST3 version for Windows. | Swift |
| <img src="logos/Stream-deck-Advance-Audio-Player.png" width="48" alt="Stream Deck Advance Audio Player"> | 🔧 [Stream-deck-Advance-Audio-Player](https://github.com/FLORIANSV35/Stream-deck-Advance-Audio-Player) | Advanced audio player for Stream Deck (macOS + Windows beta): synchronized multi-track playback, multi-output routing, fades, waveform trim points, live volume. | TypeScript |
| <img src="logos/Von-De-larsen.png" width="48" alt="Von De Larsen"> | 🔧 [Von-De-larsen](https://github.com/FLORIANSV35/Von-De-larsen) | Vocal plugin (AU + VST3 + standalone app with 1 to 8 channels, macOS Apple Silicon): anti-feedback and background noise reduction for live sound vocals. 5.3 ms latency at 48 kHz. | C++ |
| <img src="logos/3D-to-AI.png" width="48" alt="3D-to-AI"> | 🔧 [3D-to-AI](https://github.com/FLORIANSV35/3D-to-AI) | OBJ → DAE (Collada) converter for Adamson ArrayIntelligence: 3D preview, placement, cropping, macOS `.app` build. | Python |

---

## 🚁 FPV

### Spectrum analysis & race timing (RotorHazard)

| | Repo | Description | Language |
|:---:|---|---|---|
| 📶 | 🔧 [rotorhazard-rssi-scanner](https://github.com/FLORIANSV35/rotorhazard-rssi-scanner) | RotorHazard plugin: use a node as a real-time 5.8 GHz spectrum analyzer (spectrum, band map, focus + IM3/IM5, captures). | HTML |
| 🛰️ | 🔧 [Drone-Scan-Tool](https://github.com/FLORIANSV35/Drone-Scan-Tool) | 5.8 GHz spectrum analyzer and drone beacon (Remote ID) detector on ESP32-S3 + RX5808, with a web app (Web Serial) and a RotorHazard Timer Backpack mode. | HTML / Arduino |
| 🏁 | 🍴 [vrxc_elrs](https://github.com/FLORIANSV35/vrxc_elrs) | Integrate the ExpressLRS Backpack into RotorHazard.<br>**Branches:** [`pr/video-channels`](https://github.com/FLORIANSV35/vrxc_elrs/tree/pr/video-channels) · [`pr/web-connection`](https://github.com/FLORIANSV35/vrxc_elrs/tree/pr/web-connection) · [`web-bridge`](https://github.com/FLORIANSV35/vrxc_elrs/tree/web-bridge) | Python |
| 🎒 | 🍴 [Backpack](https://github.com/FLORIANSV35/Backpack) | Firmware for ExpressLRS compatible backpacks.<br>**Branches:** [`graphn-hdz-bkpk`](https://github.com/FLORIANSV35/Backpack/tree/graphn-hdz-bkpk) · [`graphn-rapidf-bkpk`](https://github.com/FLORIANSV35/Backpack/tree/graphn-rapidf-bkpk) · [`timer-msp-set-vtx-config`](https://github.com/FLORIANSV35/Backpack/tree/timer-msp-set-vtx-config) | JavaScript |

### DGAC beacons & camera control (ESP32-C3)

| | Repo | Description | Language |
|:---:|---|---|---|
| 📍 | 🔧 [balise-dgac](https://github.com/FLORIANSV35/balise-dgac) | DGAC (Remote ID) WiFi beacon for ESP32-C3, powered by the GPS of a Betaflight FC (MSP). | C++ |
| 🎥 | 🔧 [MSP-control-dji-action2](https://github.com/FLORIANSV35/MSP-control-dji-action2) | Control a DJI Action 2 over BLE (REC on arm) + OSD via ELRS Backpack, ESP32-C3. | C++ |
| 📍🎥 | 🔧 [balise-dgac-dji-action2](https://github.com/FLORIANSV35/balise-dgac-dji-action2) | Both combined: DGAC beacon + DJI Action 2 control (BLE) + ELRS Backpack OSD, with switchable features. | C++ |

### HDZero

| | Repo | Description | Language |
|:---:|---|---|---|
| <img src="logos/graphn-hdzero-goggle-fw.png" width="48" alt="HDZero Goggles"> | 🍴 [graphn-hdzero-goggle-fw](https://github.com/FLORIANSV35/graphn-hdzero-goggle-fw) | Unofficial community build of the HDZero goggles firmware (Goggle, Goggle2, BoxPro), versioned `graphn`. Flash at your own risk.<br>**Branches:** [`main`](https://github.com/FLORIANSV35/graphn-hdzero-goggle-fw/tree/main) | C |
| <img src="logos/graphn-hdzero-vtx.png" width="64" alt="HDZero"> | 🍴 [graphn-hdzero-vtx](https://github.com/FLORIANSV35/graphn-hdzero-vtx) | Fork of the HDZero VTX firmware (8051 MCU of the DM5680 baseband chip).<br>**Branches:** [`main`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/tree/main) · [`modify-analog-hdzero-adapter-camera-index`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/tree/modify-analog-hdzero-adapter-camera-index) · [`ultra-test`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/tree/ultra-test) | C |
| <img src="logos/hdzero-programmer-mac.png" width="48" alt="HDZero Programmer"> | 🍴 [hdzero-programmer-mac](https://github.com/FLORIANSV35/hdzero-programmer-mac) | macOS (Apple Silicon) port of the HDZero programmer: VTX tab via a libusb CH341 driver. Not yet validated on real hardware.<br>**Branches:** [`main`](https://github.com/FLORIANSV35/hdzero-programmer-mac/tree/main) | Python |

---

<sub>14 public repos (+ 1 unmodified fork hidden) · updated 2026-11-16 · logos taken from the repos themselves (stored in [logos/](logos/)), emoji when a repo has no logo</sub>
