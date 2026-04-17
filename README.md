#  AC to DC Converter PCB

##  Introduction

This project is a PCB design of an AC to DC converter that converts alternating current (AC) into direct current (DC). It is widely used in electronic devices where DC power is required.

---

##  Purpose

* Understand AC to DC conversion
* Learn bridge rectifier working
* Practice PCB design and component placement
* Build fundamentals of electronics

---

##  Why This Project

This project was built to gain hands-on experience in PCB design and fabrication. It helps understand the complete workflow from schematic design to PCB layout.

---

##  Working Principle

* AC input is given through connector **J1 (AC IN)**
* Bridge rectifier (**D1–D4**) converts AC to pulsating DC
* Capacitor **C1** smooths the output
* LED (**D5**) indicates power ON
* Resistor **R1** discharges capacitor safely

---

##  Rectifier Operation

* Positive cycle → D1 & D4 conduct
* Negative cycle → D2 & D3 conduct
* Output → Unidirectional DC

---

## 🔩 Components Used

| Component | Value / Type          |
| --------- | --------------------- |
| D1–D4     | 1N4007                |
| C1        | 470µF – 1000µF / 25V+ |
| D5        | Red LED               |
| R2        | 330Ω – 1kΩ            |
| R1        | 1kΩ – 10kΩ (optional) |
| J1, J2    | 2-pin connectors      |

---

#  Project Preview

# PCB 3D View

![PCB 3D]

### PCB Layout

![Layout]

# Schematic

![Schematic]

---

#  Safety Note

This circuit involves AC mains voltage. Proper precautions should be taken while testing.

---

#  Future Improvements

* Add voltage regulator (7805 / 7812)
* Add fuse protection
* Improve filtering efficiency
* Add enclosure design

---

# Files Included

* `.kicad_pro` → Project file
* `.kicad_sch` → Schematic
* `.kicad_pcb` → PCB layout

---
