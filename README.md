# 🌊 Open-Source DIY Underwater Thruster

This repository contains the technical details, CAD measurements, and production guidelines for a high-efficiency underwater thruster, specifically designed for competitive underwater robotics (e.g., Teknofest, MATE ROV).

## 🚀 Technical Specifications
Based on the provided technical drawings, the thruster features the following dimensions:
* **Nozzle Outer Diameter:** 96.7 mm
* **Propeller Diameter:** 75 mm (3-blade high-torque design)
* **Total Length:** 127.2 mm
* **Mounting Interface:** 30x35 mm base with 4 x M3 screw holes (6mm depth)
* **Cable Exit:** Waterproofed cable with length > 80 cm

## 🛠️ Bill of Materials (BOM)
To minimize costs while maintaining professional standards, the following components are recommended:
* **Motor:** Brushless DC (BLDC) Outrunner - Waterproofed via epoxy potting.
* **Housing & Duct:** 3D Printed PETG or ASA (for UV and water resistance).
* **Bearings:** 2x Stainless Steel (316L) or Hybrid Ceramic bearings.
* **Shaft:** 4mm or 5mm Stainless Steel shaft.
* **Potting Compound:** High-quality, low-viscosity epoxy resin (Approx. 40ml per unit).

## 🔧 Production & Assembly
### 1. 3D Printing Guidelines
- **Material:** PETG, ASA, or Carbon Fiber reinforced filaments.
- **Infill:** 100% for the motor mount; 40-60% for the nozzle.
- **Post-Processing:** Sanding or chemical smoothing is recommended to reduce hydrodynamic drag.

### 2. Waterproofing (Potting)
- The stator windings must be fully encapsulated in epoxy.
- **Pro Tip:** Use a vacuum chamber after pouring epoxy to eliminate air bubbles, preventing structural failure under high pressure.

### 3. Scaling the Production
With a **7.5 kg epoxy stock**, approximately **150 to 180 individual thruster units** can be waterproofed, making this a highly scalable solution for team-based projects.

## 📊 Cost Analysis
By manufacturing the nozzle, propeller, and motor windings in-house, the cost per unit is estimated at **$30 - $45**, offering a significant saving compared to commercial alternatives ($200+).

## 📂 File Structure
- `/CAD`: `.stl` and `.step` files for 3D printing.
- `/Docs`: Technical drawings and performance charts.
- `/Electronics`: ESC wiring diagrams and PWM control logic.
