# 📚 My GitHub Projects

**Legend:** 🔧 personal project · 🍴 fork (modified or adapted) · 🔒 private project (published website only)

Forks that I have not modified are not listed. For forks, only the branches containing my own commits are shown.

- [🎛️ AUDIO](#️-audio)
- [🚁 FPV](#-fpv)

---

## 🎛️ AUDIO

| | Repo | Description | Language |
|:---:|---|---|---|
| 🎚️ | 🔧 [GSR24M-driver](https://github.com/FLORIANSV35/GSR24M-driver) | macOS driver (app + daemon + CoreAudio plug-in) for the Allen & Heath GS-R24 FireWire card, Apple silicon, no kext.<br>**Latest release:** [`v0.5.1`](https://github.com/FLORIANSV35/GSR24M-driver/releases/tag/v0.5.1) | Swift |
| <img src="logos/SimplePlug.png" width="48" alt="SimplePlug"> | 🔧 [SimplePlug](https://github.com/FLORIANSV35/SimplePlug) | Minimal host for a single AU plugin with 2 in / 2 out (macOS). VST3 version for Windows.<br>**Latest release:** [`V26.11.12`](https://github.com/FLORIANSV35/SimplePlug/releases/tag/V26.11.12) | Swift |
| <img src="logos/Stream-deck-Advance-Audio-Player.png" width="48" alt="Stream Deck Advance Audio Player"> | 🔧 [Stream-deck-Advance-Audio-Player](https://github.com/FLORIANSV35/Stream-deck-Advance-Audio-Player) | Advanced audio player for Stream Deck (macOS + Windows beta): synchronized multi-track playback, multi-output routing, fades, waveform trim points, live volume.<br>**Latest release:** [`v26.9.104`](https://github.com/FLORIANSV35/Stream-deck-Advance-Audio-Player/releases/tag/v26.9.104) | TypeScript |
| <img src="logos/Von-De-larsen.png" width="48" alt="Von De Larsen"> | 🔧 [Von-De-larsen](https://github.com/FLORIANSV35/Von-De-larsen) | Vocal plugin (AU + VST3 + standalone app with 1 to 8 channels, macOS Apple Silicon): anti-feedback and background noise reduction for live sound vocals. 5.3 ms latency at 48 kHz.<br>**Latest release:** [`v0.2.4`](https://github.com/FLORIANSV35/Von-De-larsen/releases/tag/v0.2.4) | C++ |
| <img src="logos/3D-to-AI.png" width="48" alt="3D-to-AI"> | 🔧 [3D-to-AI](https://github.com/FLORIANSV35/3D-to-AI) | OBJ → DAE (Collada) converter for Adamson ArrayIntelligence: 3D preview, placement, cropping, macOS `.app` build.<br>**Latest release:** [`V26.10.07`](https://github.com/FLORIANSV35/3D-to-AI/releases/tag/V26.10.07) | Python |
| <img src="logos/CCA.png" width="48" alt="CCA"> | 🔒 CCA (CableCalc Adamson) | Web app for cabling prep of audio/stage gear (Adamson speakers): automatic cable calculation per position, power and signal distribution on racks, prep sheets, PDF/Locasyst export, collaborative project tracking.<br>**Website:** [flosv.fr/cca](https://www.flosv.fr/cca) | PHP / JS |
| <img src="logos/ASR.png" width="48" alt="ASR"> | 🔒 ASR (Array Shoot Reader) | Web app that reads array shoots and draws true-scale cluster and flat sub-array diagrams (box dimensions, spacing, angles), rigging plot, lightweight PDF export.<br>**Website:** [flosv.fr/asr](https://www.flosv.fr/asr) | HTML / JS |

---

## 🚁 FPV

### Spectrum analysis & race timing (RotorHazard)

| | Repo | Description | Language |
|:---:|---|---|---|
| 📶 | 🔧 [rotorhazard-rssi-scanner](https://github.com/FLORIANSV35/rotorhazard-rssi-scanner) | RotorHazard plugin: use a node as a real-time 5.8 GHz spectrum analyzer (spectrum, band map, focus + IM3/IM5, captures). | HTML |
| 🛰️ | 🔧 [Drone-Scan-Tool](https://github.com/FLORIANSV35/Drone-Scan-Tool) | 5.8 GHz spectrum analyzer and drone beacon (Remote ID) detector on ESP32-S3 + RX5808, with a web app (Web Serial) and a RotorHazard Timer Backpack mode. | HTML / Arduino |
| 🏁 | 🍴 [vrxc_elrs](https://github.com/FLORIANSV35/vrxc_elrs) | Integrate the ExpressLRS Backpack into RotorHazard.<br>**Latest release:** [`web-bridge-v0.3.0`](https://github.com/FLORIANSV35/vrxc_elrs/releases/tag/web-bridge-v0.3.0)<br>**Branches:** [`pr/video-channels`](https://github.com/FLORIANSV35/vrxc_elrs/tree/pr/video-channels) · [`pr/web-connection`](https://github.com/FLORIANSV35/vrxc_elrs/tree/pr/web-connection) · [`web-bridge`](https://github.com/FLORIANSV35/vrxc_elrs/tree/web-bridge) | Python |
| 🎒 | 🍴 [Backpack](https://github.com/FLORIANSV35/Backpack) | Firmware for ExpressLRS compatible backpacks.<br>**Latest release:** [`graphn-rapidf-bkpk-1.5.9-graphn-b1aff93`](https://github.com/FLORIANSV35/Backpack/releases/tag/graphn-rapidf-bkpk-1.5.9-graphn-b1aff93)<br>**Branches:** [`graphn-hdz-bkpk`](https://github.com/FLORIANSV35/Backpack/tree/graphn-hdz-bkpk) · [`graphn-rapidf-bkpk`](https://github.com/FLORIANSV35/Backpack/tree/graphn-rapidf-bkpk) · [`timer-msp-set-vtx-config`](https://github.com/FLORIANSV35/Backpack/tree/timer-msp-set-vtx-config) | JavaScript |

### DGAC beacons & camera control (ESP32-C3)

| | Repo | Description | Language |
|:---:|---|---|---|
| 📍 | 🔧 [balise-dgac](https://github.com/FLORIANSV35/balise-dgac) | DGAC (Remote ID) WiFi beacon for ESP32-C3, powered by the GPS of a Betaflight FC (MSP).<br>**Latest release:** [`V26.10.01`](https://github.com/FLORIANSV35/balise-dgac/releases/tag/V26.10.01) | C++ |
| 🎥 | 🔧 [MSP-control-dji-action2](https://github.com/FLORIANSV35/MSP-control-dji-action2) | Control a DJI Action 2 over BLE (REC on arm) + OSD via ELRS Backpack, ESP32-C3.<br>**Latest release:** [`V26.10.01`](https://github.com/FLORIANSV35/MSP-control-dji-action2/releases/tag/V26.10.01) | C++ |
| 📍🎥 | 🔧 [balise-dgac-dji-action2](https://github.com/FLORIANSV35/balise-dgac-dji-action2) | Both combined: DGAC beacon + DJI Action 2 control (BLE) + ELRS Backpack OSD, with switchable features.<br>**Latest release:** [`V26.10.01`](https://github.com/FLORIANSV35/balise-dgac-dji-action2/releases/tag/V26.10.01) | C++ |

### HDZero

| | Repo | Description | Language |
|:---:|---|---|---|
| <img src="logos/graphn-hdzero-goggle-fw.png" width="48" alt="HDZero Goggles"> | 🍴 [graphn-hdzero-goggle-fw](https://github.com/FLORIANSV35/graphn-hdzero-goggle-fw) | Unofficial community build of the HDZero goggles firmware (Goggle, Goggle2, BoxPro), versioned `graphn`. Flash at your own risk.<br>**Latest release:** [`graphn-v26.11.14`](https://github.com/FLORIANSV35/graphn-hdzero-goggle-fw/releases/tag/graphn-v26.11.14)<br>**Branches:** [`main`](https://github.com/FLORIANSV35/graphn-hdzero-goggle-fw/tree/main) | C |
| <img src="logos/graphn-hdzero-vtx.png" width="64" alt="HDZero"> | 🍴 [graphn-hdzero-vtx](https://github.com/FLORIANSV35/graphn-hdzero-vtx) | Fork of the HDZero VTX firmware (8051 MCU of the DM5680 baseband chip).<br>**Latest release:** [`graphn-v26.10.03`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/releases/tag/graphn-v26.10.03)<br>**Branches:** [`main`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/tree/main) · [`modify-analog-hdzero-adapter-camera-index`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/tree/modify-analog-hdzero-adapter-camera-index) · [`ultra-test`](https://github.com/FLORIANSV35/graphn-hdzero-vtx/tree/ultra-test) | C |
| <img src="logos/hdzero-programmer-mac.png" width="48" alt="HDZero Programmer"> | 🍴 [hdzero-programmer-mac](https://github.com/FLORIANSV35/hdzero-programmer-mac) | macOS (Apple Silicon) port of the HDZero programmer: VTX tab via a libusb CH341 driver. Not yet validated on real hardware.<br>**Latest release:** [`v2.1.0-mac1`](https://github.com/FLORIANSV35/hdzero-programmer-mac/releases/tag/v2.1.0-mac1)<br>**Branches:** [`main`](https://github.com/FLORIANSV35/hdzero-programmer-mac/tree/main) | Python |

---

<sub>14 public repos (+ 1 unmodified fork hidden) · 2 private projects with published sites · updated 2026-11-16 · logos taken from the repos themselves (stored in [logos/](logos/)), emoji when a repo has no logo</sub>
