# PCB_Tools

## Description

Welcome to the **PCB_Tools** repository. This project aims to provide a comprehensive collection of tools and resources for the design and manufacturing of printed circuit boards (PCBs). Here you will find components schematics, footprints, and a set of manufacturing rules specific to some companies in the industry.

## Contents

#### 1. Schematic Librarie
#### 2. PCB Librarie
#### 3. Manufacturing Rules

## Naming Convention

To maintain consistency and clarity, the libraries follow a specific naming convention for both schematics and PCBs.

### Schematic:

```
(THT/SMD) component_name (details)
```

- **THT/SMD:** Indicates whether the component is Through-Hole Technology (THT) or Surface-Mount Device (SMD).
- **component_name:** The name of the component, such as resistor, capacitor, transistor, etc.
- **(details):** Additional information about the component.

**Example:**

- `THT Resistor`
- `ESP32-S3 IC`

### PCB:

```
(THT/SMD) component_name (package/specifications)
```

- **THT/SMD:** Indicates whether the component is Through-Hole Technology (THT) or Surface-Mount Device (SMD).
- **component_name:** The name of the component, such as resistor, capacitor, transistor, etc.
- **(package/specifications):** Details about the component's package type and specifications.

**Example:**

- `SMD Capacitor 0603`
- `SMD TQFP-32/ATmega328P IC`

This naming convention ensures that all components are easily identifiable and their specifications and package types are clearly understood.

---

Thank you for using **PCB_Tools**! I hope this repository is useful for your PCB design and manufacturing projects.
