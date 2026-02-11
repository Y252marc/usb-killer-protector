# USB killer Protector | 🛡️ USB SHIELD | The 5kV Hard-Isolation Barrier
**Magnetic isolation. Zero physical connection. Total motherboard safety.**

![GitHub License](https://img.shields.io/github/license/Y252marc/usb-killer-protector?style=for-the-badge&color=10b981)
![KiCad Version](https://img.shields.io/badge/KiCad-9.0-blueviolet?style=for-the-badge&logo=kicad)
![Hardware Status](https://img.shields.io/badge/Hardware-Verified-orange?style=for-the-badge)

👉 **[Launch Interactive Project Site](https://y252marc.github.io/usb-killer-protector/)**

---

### ⚡ The Problem: The "Spark"
USB Killers don't hack your software; they execute your hardware. By dumping high-voltage DC into your port, they fry your motherboard in milliseconds. Standard protectors are too slow.

### 🔌 The Solution: The "Moat"
I didn't just build a filter; I built a physical gap. Data is teleported across a 4.5mm "moat" using magnetic fields, while power is handled by a floating transformer. If an attacker dumps 200V into the target side, it literally has no physical path to reach your laptop.

---

### 🛠️ Hardware Loadout
* **The Brain**: **ADuM4160** Digital Isolator (Rated for **5,000V** isolation).
* **The Power**: **RFM-0505S** Isolated DC-DC Converter (Floating 5V power).
* **The Guard**: Dual **SMAJ5.0A** TVS Diodes (Clamping transients at the source).
* **The Kill Switch**: **JS202011SCQN** DPDT switch for instant manual data disconnection.



---

### 📐 Engineering Excellence
* **Split Ground Planes**: Two entirely separate copper islands—Clean vs. Dirty.
* **Differential Data Highway**: Matched D+/D- lines with 24Ω termination for zero-drop communication.
* **Pro Layout**: 2-layer FR4 with 2mm rounded edges for a clean, crack-proof finish.

### 📂 Inside the Repo
* **3D Assets**: STEP models for the isolator, transformer, and ports.
* **Production**: Factory-ready Gerber and Drill files.
* **Source**: Full KiCad 9 design project.

---

### 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### ⚠️ Disclaimer
*Testing destructive hardware is dangerous. This shield is for research and educational vibes only. Use it at your own risk.*
