# **PCB_Tools**  

## **Description**  

Welcome to the **PCB_Tools** repository! This project provides a collection of tools and resources for designing and manufacturing printed circuit boards (PCBs). Here, you'll find schematic libraries, PCB footprints, and a set of manufacturing rules tailored for specific industry standards.  

## **Contents**  

- **Schematic Library** – Collection of component schematics.  
- **PCB Library** – Footprints and layout references.  
- **Manufacturing Rules** – Design constraints and specifications for PCB fabrication.  

## **Naming Convention**  

To ensure consistency and clarity, the libraries follow a structured naming convention for both schematics and PCB footprints.  

### **Schematic Naming:**  

```
(THT/SMD) component_name (details)
```

- **THT/SMD** → Specifies whether the component is Through-Hole (THT) or Surface-Mount Device (SMD).  
- **component_name** → Component type (e.g., resistor, capacitor, IC, etc.).  
- **(details)** → Additional specifications.  

**Examples:**  
- `THT Resistor 10kΩ`  
- `SMD ESP32-S3 IC`  

### **PCB Footprint Naming:**  

```
(THT/SMD) component_name (package/specifications)
```

- **THT/SMD** → Defines the mounting technology.  
- **component_name** → Identifies the component.  
- **(package/specifications)** → Specifies the package type.  

**Examples:**  
- `SMD Capacitor 0603`  
- `SMD ATmega328P TQFP-32`  

---

Thank you for using **PCB_Tools**! I hope this repository helps streamline your PCB design and manufacturing process. 🚀
