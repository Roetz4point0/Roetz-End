# 🔥 Roetz-End – Co-Extrusion Hotend (Open Beta)
**by Jan Roetz / Roetz4.0**

---

## 🧠 Overview
The **Roetz-End** is an open-source, high-performance Co-Extrusion Hotend designed for  
**Directional Material Deposition (DMD)** — a process where each filament’s deposition  
is *actively controlled based on the print head’s movement direction.*

![Hotend ](https://github.com/user-attachments/assets/d081ae19-be35-4995-8184-e67cb86368ac)

This marks the first public release of the Roetz-End concept —  
a platform for multi-material co-extrusion without mixing, purging, or waste.  

 ![Cube_Small](https://github.com/user-attachments/assets/980db05e-d1d9-4646-9f7b-875dba7a0147)


🎥 Full context, demonstration and build information:  
👉 [YouTube Release Video](https://youtu.be/6pM_ltAM7_s)

---

## ⚙️ Technical Notes
- Four independent melt channels allow **directional placement** of materials or colors.  
- No purge blocks, no priming towers, no poop.  
- Flow rates up to **200 mm³/s** possible (depending on filament).

---

## 🛠️ Build Guide (Quick Start)

### Required Parts
| Component | Description | Source |
|------------|--------------|---------|
| 1x **Hotend** | SLM printed aluminum | Online SLM manufacturer, read the buildguide|
| 1x **Coldend** | SLM printed aluminum | Online SLM manufacturer, read the buildguide |
| 1x **Back Bracing** | (optional) stainless steel sheet metal | Online sheet metal manufacturer, read the buildguide|
| 4x **Heatbreak** V0.9 | M6 (bottom) and Ø6mm cylindrical (top), Go-To: Creality Ender 3 S1 Heatbreak | Local supplier or: https://tinyurl.com/mtvx7jhu "Bimetal Throat" |
| 2x **Heatbreak** V0.91 | 2	Bimetal	M6 thread bottom with 5mm key / copper top | Local supplier or: [https://tinyurl.com/mtvx7jhu](https://tinyurl.com/tph7v3sw) "Chimera Heatbreak" |
| 4x **Heater** | Ø6mm x 20mm lenght, preferably. 24V 50W | Local supplier or: https://tinyurl.com/3yftytx4 "50W 24V" |
| 1x **FAN** | 30x30x10mm Fan, preferably ball bearing and 24V | Local supplier or: https://tinyurl.com/23sj9bh6 "3010 24V" |
| 1x **Nozzle** | Standard RepRap M6 | Local supplier |
| **Screws** | M3-hex in 6-20mm lenght | Standard DIN / ISO |
| **pneumatic couplers** | For Bowden Setup only. MINI-IQS Ø4mm/M6 or POC4/M6 | Local or: https://tinyurl.com/53jsmu88 "POC 4-M6"|
---

### Assembly Overview
1. Check all threads if they are deep enough and run freely.  
2. Check hole sizes if heatbreaks and heater cartridges do fit.
3. Wire heater and thermistor into your printers mainboard
4. Screw heatbreaks and nozzle into the hotend (consider using some teflon tape)
5. Heat up Hotend to 250°C, use soft pliers to thread heatbreaks and nozzle in all the way. (Let it cool down afterwards)
6. Marry Hot- and Coldend. Make sure it seats properly and torque down the 3 screws to close the flexure.


📘 Detailed assembly PDF: [BuildGuide/BuildManual_v0.9-Beta.pdf](./BuildGuide/BuildManual_v0.9-BETA.pdf)

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
- [STL Models](./Files)
- [BOM (Bill of Materials)](./BuildGuide/BOM.csv)
- [Build Guide PDF](./BuildGuide/BuildManual_v0.9-BETA.pdf)
