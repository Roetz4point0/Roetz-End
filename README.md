# 🔥 Roetz-End – Co-Extrusion Hotend (Open Beta)
**by Jan Roetz / Roetz4.0**

---

## 🧠 Overview
The **Roetz-End** is an open-source, high-performance Co-Extrusion Hotend designed for  
**Directional Material Deposition (DMD)** — a process where each filament’s deposition  
is *actively controlled based on the print head’s movement direction.*

This marks the first public release of the Roetz-End concept —  
a platform for multi-material co-extrusion without mixing, purging, or waste.  

🎥 Full context and demonstration:  
👉 [YouTube Release Video](https://youtu.be/yourlink)

---

## 🛠️ Build Guide (Quick Start)

### Required Parts
| Component | Description | Source |
|------------|--------------|---------|
1x | **Hotend** | SLM printed aluminum | [PCBWay Project Link](#) |
1x | **Coldend** | SLM printed aluminum | [PCBWay Project Link](#) |
1x | **Back Bracing** | (optional) stainless steel sheet metal | [PCBWay Project Link](#) |
4x | **Heatbreak** | M6 (bottom) and Ø6mm cylindrical (top), Go-To: Creality Ender 3 S1 Heatbreak | Local supplier or: https://tinyurl.com/mtvx7jhu "Bimetal Throat" |
4x | **Heater** | Ø6mm x 20mm lenght, preferably. 24V 50W | Local supplier or: https://tinyurl.com/3yftytx4 "50W 24V" |
1x | **FAN** | 30x30x10mm Fan, preferably ball bearing and 24V | Local supplier or: https://tinyurl.com/23sj9bh6 "3010 24V" |
1x | **Nozzle** | Standard RepRap M6 | Local supplier |
   | **Screws** | M3-hex in 6-20mm lenght | Standard DIN / ISO |
   | **pneumatic couplers** | For Bowden Setup only. MINI-IQS Ø4mm/M6 or POC4/M6 | Local or: https://tinyurl.com/53jsmu88 "POC 4-M6"|
---

### Assembly Overview
1. Insert filament guides into the rear ports.  
2. Mount the SLM body to the adapter plate.  
3. Fasten with M3x12 screws.  
4. Install nozzles and heatbreaks.  
5. Verify alignment by extruding at low flow rate.

📘 Detailed assembly PDF: [BuildGuide/Roetz-End_BuildGuide_v1.pdf](./BuildGuide/Roetz-End_BuildGuide_v1.pdf)

---

## ⚙️ Technical Notes
- Four independent melt channels allow **directional placement** of materials or colors.  
- No purge blocks, no priming towers, no poop.  
- Flow rates up to **200 mm³/s** possible (depending on filament).  
- Fully compatible with standard hotend mounts.

---

## 📜 License
© 2025 Jan Roetz / Roetz4.0  
Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

You are free to share and adapt this work for **non-commercial** purposes,  
as long as attribution is given and derivative works use the same license.

---

## 💬 Community & Collaboration
This project is open for research and exploration.  
If you modify, build, or test the Roetz-End — share it!  
Post with `#RoetzEnd` or open a discussion under the [Issues tab](../../issues).

---

## 🧾 Files
- [STEP + STL Models](./Files)
- [BOM (Bill of Materials)](./Files/BOM.csv)
- [Build Guide PDF](./BuildGuide/Roetz-End_BuildGuide_v1.pdf)
