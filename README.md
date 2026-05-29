<div align="center">

<!-- Replace with your project logo or banner -->
<img src="https://via.placeholder.com/120x120.png?text=LOGO" alt="Project Logo" width="120" height="120" />

<h1>DrumXRoll</h1>

<p><em>An extended-reality drum learning system for Meta Quest 3 — teaching rhythm, timing, and limb coordination through immersive XR.</em></p>

[![License](https://img.shields.io/badge/license-Academic%2FResearch-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/Nmsrt/DrumXRoll/releases)
[![Unity](https://img.shields.io/badge/Unity-2022.3.55f1-black.svg)](https://unity.com/)
[![Platform](https://img.shields.io/badge/platform-Meta%20Quest%203-blueviolet.svg)](https://www.meta.com/quest/quest-3/)
[![Issues](https://img.shields.io/github/issues/Nmsrt/DrumXRoll)](https://github.com/Nmsrt/DrumXRoll/issues)

<br />

[Report Bug](https://github.com/Nmsrt/DrumXRoll/issues/new?template=bug_report.md) · [Request Feature](https://github.com/Nmsrt/DrumXRoll/issues/new?template=feature_request.md)

</div>

---

> ⚠️ **The `Assets/` folder is NOT included in this repository.** The full project exceeds 17GB and must be downloaded separately. See [Assets Folder Notice](#assets-folder-notice) below.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Assets Folder Notice](#assets-folder-notice)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [About the Research](#about-the-research)
- [License](#license)
- [Contact](#contact)

---

## Overview

**DrumXRoll** is a Unity-based multimodal drum-learning system built for the **Meta Quest 3**. It teaches drumming fundamentals through a piano-roll–style note visualizer, interactive lesson modes, and physical drum-set integration — blending gesture tracking, spatial cues, and real-time feedback to help learners develop rhythm, timing, and limb coordination.

This repository contains the Unity project **scripts**, **project settings**, and **package definitions** required for both the linear and spatial versions of DrumXRoll.

---

## Features

- ✅ **Piano-roll visualizer** — Spatialized falling notes guide learners through each piece.
- ✅ **Drum-hit detection** — Real-time interaction logic for both virtual and physical drum sets.
- ✅ **Metronome & timing windows** — Precision feedback on timing accuracy and consistency.
- ✅ **Multiple lesson modes** — Watch & Listen, Try Yourself, Compose on the Fly, Constraint & Create, and more.
- ✅ **XR integration** — Built natively for Meta Quest 3 with gesture tracking and spatial cues.
- ✅ **UI/UX flows** — Scene controllers, managers, and core scripts for a complete learning experience.
- ✅ **Adaptive learning** — Lesson flows suited to beginner and intermediate drummers.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Engine | [Unity 2022.3.55f1](https://unity.com/) |
| Platform | [Meta Quest 3](https://www.meta.com/quest/quest-3/) |
| XR Framework | Meta XR SDK |
| Language | C# |
| Asset Storage | Google Drive (external — see below) |

---

## Assets Folder Notice

The complete `Assets/` folder is **not included** in this repository. The full project size exceeds **17GB**, which goes beyond GitHub's free storage limits.

Download the assets from the links below, then place the folder in the project root before opening in Unity.

| Version | Download Link |
|---|---|
| Linear Assets | [Google Drive — Linear Assets](https://drive.google.com/drive/folders/14SE4Ph2MdCxOPNk0VD3J6okTuiSGPZoS?usp=sharing) |
| Spatial Assets | [Google Drive — Spatial Assets](https://drive.google.com/drive/folders/1YuiprpejYM5Vm2vVEnZXH14A4VhvfLHK?usp=sharing) |

> ⚠️ Certain proprietary assets (models, music files, textures) cannot be redistributed and are only available via the links above.

---

## Getting Started

### Prerequisites

- [Unity 2022.3.55f1](https://unity.com/releases/editor/archive) — use this exact version to avoid compatibility issues.
- [Meta Quest 3](https://www.meta.com/quest/quest-3/) headset for XR deployment.
- Downloaded `Assets/` folder from the Google Drive links above.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nmsrt/DrumXRoll.git
   cd DrumXRoll
   ```

2. **Download the Assets folder** from the [Google Drive links](#assets-folder-notice) above.

3. **Place the `Assets/` folder** in the project root so the structure looks like this:
   ```
   DrumXRoll/
   ├── Assets/
   ├── Packages/
   ├── ProjectSettings/
   └── UserSettings/       ← optional
   ```

4. **Open the project in Unity 2022.3.55f1.**

5. **Wait for Unity to reimport assets** on the first load — this may take several minutes due to project size.

---

## Project Structure

```
DrumXRoll/
├── Assets/                   # ⚠️ Not included — download from Google Drive
├── Packages/                 # Unity package definitions
├── ProjectSettings/          # Unity project configuration
├── UserSettings/             # Local editor preferences (optional)
└── README.md
```

---

## About the Research

DrumXRoll is developed under the **Human-X Interactions Lab (HXIL)** at **De La Salle University** as part of ongoing research into XR-based music education. The system explores how extended reality can make drumming practice more immersive and intuitive by combining:

- **Visual learning** via spatialized falling notes
- **Kinesthetic learning** using real and virtual drum sets
- **Adaptive lesson flows** for beginner and intermediate players
- **Instant feedback** on timing accuracy and consistency

---

## License

This project is for **academic and research purposes only**. Certain proprietary assets (models, music files, textures) cannot be redistributed and are only available via the provided external drive links.

---

## Contact

**Neo Monserrat** — neo.monserrat@gmail.com

Project Link: [https://github.com/Nmsrt/DrumXRoll](https://github.com/Nmsrt/DrumXRoll)

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/Nmsrt">Nmsrt</a></sub>
</div>
