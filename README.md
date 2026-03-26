# 🧬 BIODIGITAL SIMULATOR: AVIAN KINETIC REACTOR
### *Lucio Arese x TRON Aesthetic Analysis | Version 4.0*

This project is a high-performance **3D Audio Spectrogram** designed to visualize the complex architecture of birdsong. Unlike traditional 2D scrolling graphs, this engine projects sound into a **Temporal-Cubic Manifold**, creating a physical "sculpture" of audio history that exists within a digital grid.

## 🚀 Live Demo
👉 [https://arcesoftware.github.io/TronArese/]

## 📸 Preview
![Demo](demo.gif)
---

## 💎 The Aesthetic Philosophy
The visual engine is a hybrid of two distinct digital art styles:
1.  **Lucio Arese:** Minimalist, architectural wireframes with high-precision line work.
2.  **TRON (1982/2010):** A high-contrast "Grid" environment utilizing a Neon Cyan to Hot Magenta chromatic scale.

---

## ⚙️ The Oscillation-Emission Model
The simulation discards fixed Cartesian measurements in favor of **Dynamic Amplitude Oscillations**. Each frame of audio is treated as a unique "Emission Event":

| Dimension | Variable | Mapping Logic |
| :--- | :--- | :--- |
| **X-Axis** | **Frequency** | Cropped to $2\text{kHz} - 12\text{kHz}$ (The "Avian Sweet Spot") to ensure 100% volume utilization. |
| **Y-Axis** | **Amplitude** | Scaled via $A^{0.6}$ to boost quieter chirps and fill the vertical box height ($400\text{px}$). |
| **Z-Axis** | **Lifetime** | A rolling history of $100$ frames at $60\text{fps}$, creating a $1.6$-second "Sonic Trail." |
| **Color** | **Spectral Index** | Linear gradient: **Cyan** ($180^{\circ}$) for mid-tones $\to$ **Magenta** ($300^{\circ}$) for high-frequency peaks. |

---

## 🎮 Interactive Command Protocol
The simulation is fully interactive, optimized for real-time manipulation on high-end hardware (NVIDIA RTX 4070 Ti+).

* **`SPACEBAR`**: **REINITIATE REACTOR.** Instantly restarts the `test.mp3` buffer.
* **`MOUSE MOVE`**: **ORBIT CAMERA.** Rotate the 3D cube to inspect the "back" of the soundwaves.
* **`SCROLL WHEEL`**: **DEPTH ZOOM.** Move the camera physically into the grid to see micro-oscillations.
* **`ESC`**: **RESET GRID.** Resets the camera to the original architectural blueprint perspective.
* **`CLICK`**: **BOOT SYSTEM.** Initializes the WebAudio context and starts the emission.

---

## 📂 Project Structure
To run the simulation, ensure your directory is organized as follows:
```text
root/
├── index.html          <-- The provided code
└── test1.mp3        <-- Your birdsong recording (Required)
└── test.mp3        <-- Your birdsong recording (Optional)    
