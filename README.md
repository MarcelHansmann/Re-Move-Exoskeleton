#  Re-Move: Open-Source Knee Exoskeleton

<p align="center">
  <img src="(https://raw.githubusercontent.com/MarcelHansmann/Re-Move-Exoskeleton/main/photos/Img2.png)" width="600" title="Re-Move Exoskeleton">
</p>

*Designed to democratize access to mobility assistance.*

## 🎯 Overview
Re-Move is a knee exoskeleton designed to assist with squatting movements. Rooted in an open-source philosophy and engineered for user fabrication, its goal is to democratize access to mobility assistance. Current commercial solutions cost around €2,000; **Re-Move reduces this cost to just €50 per unit**, making it forty times more affordable.

The system stores potential energy in elastic springs during knee flexion (the downward phase) and releases it in a controlled manner during extension (the upward phase), providing a **23% assistance** to the user's effort. Structurally, the device consists of four 3D-printed elements assembled with standardized metal components that provide all necessary structural rigidity.
<p align="center">
  <img src="https://raw.githubusercontent.com/MarcelHansmann/Re-Move-Exoskeleton/main/photos/Img4.png" width="600" title="Re-Move Exoskeleton">
</p>
---


## 📦 Bill of Materials (BOM) & Files

The total cost of materials is approximately €50. You will need both the standard hardware components and the 3D printed parts.

### 1. Standard Hardware (Off-the-shelf)

| Component | Quantity | Notes | Where to Buy / Link |
| :--- | :---: | :--- | :--- |
| **Aluminum Profile** (45x25mm) | 2 meters | Structural chassis | [Buy at Leroy Merlin](https://www.leroymerlin.es/productos/perfil-forma-rectangular-de-aluminio-blanco-standers-alt-45-x-an-25mm-x-l-2-m-87477282.html) |
| **Extension Springs** (18x115mm) | 4 units | Energy storage (Max 8kg load) | [Buy at Leroy Merlin](https://www.leroymerlin.es/productos/muelle-tensor-de-acero-cincado-standers-carga-max-8-kg-18x115mm-91007856.html) |
| **Velcro Straps** | 4 units | User attachment | [Buy at Amazon](https://www.amazon.es/dp/B0B18BQSF3/) |
| **Polyester Cord** | 1 unit | Mechanism linkage (50m roll) | [Buy at Leroy Merlin](https://www.leroymerlin.es/productos/cuerda-de-poliester-de-50-m-y-19-75-kg-de-carga-util-16746884.html) |
| **M8 Threaded Rod** | 1 meter | For rigidity | Any local hardware store |
| **M8 Hex Nuts** | 10 units | Assembly fasteners | Any local hardware store |

---

### 2. 3D Printed Parts & Print Settings

**Print with Bambu Studio (Plug & Play):**

Download the `.3mf` plates with all elements ready to go — settings are already configured inside the files, just slice and print!

👉 📥 **[Download Right Leg .3mf File](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/BambuLabFiles/RightLegPlate.3mf
)**

👉 📥 **[Download Left Leg .3mf File](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/BambuLabFiles/LeftLegPlate.3mf
)**

*Basic Slicing Guidelines:*
- **Material:** PLA Basic recommended.
- **Walls/Perimeters:** Minimum 2 walls.
- **Infill:** 15% general infill.
- **Modifier Infill:** 45% infill in the areas defined by the modifier files.
- **Supports:** Activate supports.

---

### 3. CAD Source Files (SolidWorks)

For those who want to modify or inspect the design, the original SolidWorks files are available below.

*Right Leg (4 parts):*
- 📥 [Download Right Leg Part 1.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part1_Right.SLDPRT
)
- 📥 [Download Right Leg Part 2.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part2_Right.SLDPRT
)
- 📥 [Download Right Leg Part 3.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part3_Right.SLDPRT
)
- 📥 [Download Right Leg Part 4.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part4_Right.SLDPRT
)

*Left Leg (4 parts):*
- 📥 [Download Left Leg Part 1.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part1_Left.SLDPRT
)
- 📥 [Download Left Leg Part 2.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part2_Left.SLDPRT
)
- 📥 [Download Left Leg Part 3.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part3_Left.SLDPRT)
- 📥 [Download Left Leg Part 4.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part4_left.SLDPRT
)

*Shared Part (both legs):*
- 📥 [Download Shared Part.SLDPRT](https://github.com/MarcelHansmann/Re-Move-Exoskeleton/raw/main/cad/Part5_Shared.SLDPRT
)

## 🛠️ Assembly Instructions
Re-Move is designed for easy self-assembly. You do not need advanced technical skills, and the process takes less than 2 hours.

We have created a highly visual, step-by-step assembly manual to guide you through cutting the aluminum, placing the springs, and routing the straps.

📖 📥 **[Download the Visual Assembly Manual (PDF)](ruta/al/teu_manual.pdf)**

---

## ⚠️ Safety Disclaimer
**Please read carefully before building or using.**
Re-Move is an experimental, open-source engineering project. **It is NOT a certified medical device.** It is designed solely to assist with the vertical squatting motion, not for walking or supporting full body weight in cases of severe paralysis. 

Be careful while using the tools to modify the aluminium profile. They tend to be dumb-proof, but are still designed to make their way through harder things than your fingers.

The author has no medical knowledge (so far) and assumes no responsibility for injuries. Use at your own risk. 



---

## 📄 License
This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.
