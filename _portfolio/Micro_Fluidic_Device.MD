---
title: "Pinch Flow Fractionation Microfluidic Device"
excerpt: "This project develops a PFF microfluidic device that sorts particles by size for use in diagnostics, environmental monitoring, and pharmaceutical research."
header:
  image: /assets/img/Device_Assembly.jpg
  teaser: /assets/img/Teaser.jpg
gallery:
  - url: /assets/img/Mold_Photo.jpg
    image_path: /assets/img/Mold_Photo.jpg
    alt: "3D printed mold image"
  - url: /assets/img/Final_Device.jpg
    image_path: /assets/img/Final_Device.jpg
    alt: "final device image"
  - url: /assets/img/Channel_Diagram.png
    image_path: /assets/img/Channel_Diagram.png
    alt: "channel geometry visualization"
---

This project focuses on the design and fabrication of a **Pinch Flow Fractionation (PFF) microfluidic device**, which sorts particles based on size using carefully controlled fluid flow patterns. The device leverages sheath flow to focus particles and uses pinch geometries to split particles into different outlets based on size. 

{% include gallery caption="The images showcase the device's development process: the left image shows the resin-printed mold, the center image displays the final assembled device, and the right image highlights the channel geometry that enables size-based separation." %}

### Purpose and Features
- **Purpose**: To create a functional microfluidic sorter capable of separating particles by size for applications such as medical diagnostics, environmental monitoring, and pharmaceutical development.
- **Key Features**:
  - Pinch flow geometry for controlled particle separation.
  - Dual sheath flow inlets for precise focusing.
  - Multi-outlet design for size-based fractionation.
  - Fabrication using resin printing, parylene coating, and PDMS casting.

---

### Parts List
#### Off-the-Shelf Components

| **Part**                | **Quantity** | **Description**                        |
|-------------------------|--------------|----------------------------------------|
| Syringe Pumps            | 3            | For controlled sheath and sample flow |
| Microfluidic Tubing       | Variable     | Connects device to syringe pumps      |
| Glass Slides              | 1            | Bonding surface for PDMS channels     |

#### Custom Fabricated Components

| **Part**          | **Material**      | **Purpose**                           |
|--------------------|------------------|--------------------------------------|
| Microfluidic Mold  | Resin (3D Print) | Master mold for casting PDMS layer |
| PDMS Layer         | PDMS Silicone    | Fluidic channels for sorting        |

---

### Interactive 3D Model
<iframe src="https://fusion360.autodesk.com/embed/YOUR_MODEL_URL_HERE" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

### Fabrication Process

1. **3D Printed Mold Preparation**:
    - Print high-resolution mold using resin printer.
    - Clean and post-cure the mold thoroughly.

2. **Parylene Coating**:
    - Deposit a thin parylene layer onto the mold.
    - This prevents PDMS adhesion and ensures smooth channels.

3. **PDMS Casting**:
    - Mix PDMS base and curing agent (10:1 ratio).
    - Degas and pour over the coated mold.
    - Cure at 70°C for 2 hours, then demold.

4. **Device Assembly**:
    - Punch inlet and outlet ports.
    - Bond PDMS to a glass slide using oxygen plasma treatment.
    - Connect tubing to the ports for flow control.

---

### Design Discussion

#### Why Coat Molds with Parylene?
- Prevents PDMS adhesion to the resin mold.
- Provides smoother surfaces for laminar flow.
- Enhances mold reusability.

#### Geometry for Sorting
| Parameter          | Value         | Purpose |
|-------------------|---------------|---------|
| Pinch Width       | 200 µm       | Focuses particles into a single streamline |
| Outlet Width      | 300 µm       | Accommodates sorted particles |
| Inlet Ports       | 3            | Sample (center) + sheath flows (sides) |
| Outlet Ports      | 3            | Collects different size fractions |

The tight pinch region ensures smaller particles follow shifted streamlines, while larger particles remain near the centerline.

#### Flow Equalization Measures
- Symmetrical outlet channels to balance hydraulic resistance.
- Equal sheath flow rates to ensure centered sample stream.
- Minimized sharp turns to avoid turbulence.

---

### Future Improvements
- Refine channel geometry to enhance separation resolution.
- Introduce curved inlet regions for smoother particle focusing.
- Add optical detection for real-time monitoring.

---

### Hypothetical Applications
- **Medical Diagnostics**: Isolating rare circulating tumor cells (CTCs) from blood.
- **Environmental Monitoring**: Filtering microplastics from water.
- **Pharmaceutical Research**: Sorting nanoparticles for drug delivery.

---

### Bonus Attempt (If Applicable)

We experimented with:
- **Dual-stage separation** by adding a second separation zone downstream.
- **Fluorescence tracking** for particle verification during sorting.

Although alignment between layers proved challenging, initial results were promising.

---

### References

1. Yamada, M., & Seki, M. (2005). Hydrodynamic filtration for on-chip particle concentration and classification utilizing microfluidics. *Lab on a Chip*, 5(11), 1233-1239. [https://doi.org/10.1039/b508677a](https://doi.org/10.1039/b508677a)
2. Whitesides, G. M. (2006). The origins and the future of microfluidics. *Nature*, 442(7101), 368-373. [https://doi.org/10.1038/nature05058](https://doi.org/10.1038/nature05058)

---

### Conclusion
This project demonstrates the potential of combining 3D printing, precision fluid control, and microfluidic design principles to achieve robust, scalable particle separation. Such technology can power next-generation diagnostics, environmental testing, and advanced material sorting.

---
