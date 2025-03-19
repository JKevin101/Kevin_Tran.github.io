---
title: "Multi-Material Needle Nose Pliers"
excerpt: "A functional, multi-material 3D printed needle nose pliers designed for gripping and manipulating through-hole resistors."
header:
  image: /assets/img/Pliers/Full_Assembly.jpg
  teaser: /assets/img/Pliers/Teaser.jpg
gallery:
  - url: /assets/img/Pliers/Prototype.jpg
    image_path: /assets/img/Pliers/Prototype.jpg
    alt: "Initial Prototype"
  - url: /assets/img/Pliers/Iteration.jpg
    image_path: /assets/img/Pliers/Iteration.jpg
    alt: "Design Iteration"
  - url: /assets/img/Pliers/Working.jpg
    image_path: /assets/img/Pliers/Working.jpg
    alt: "Final Working Model"
---

## Project Overview
This project focuses on creating functional, multi-material needle nose pliers using 3D printing techniques. The pliers are designed to grip and manipulate through-hole resistors, utilizing print-in-place manufacturing and elastomeric materials to achieve a flexible, spring-return mechanism.

**Print-in-place models** are innovative designs that function immediately after being printed without the need for additional assembly. These designs often rely on careful clearances between moving parts and precise print orientations. While single-material extrusion is common, incorporating flexible components can greatly enhance functionality, resulting in smoother and more controlled movements.

*Learn more about print-in-place mechanisms:*
- [Print-in-Place Tips](https://core-electronics.com.au/guides/print-in-place-tips/)
- [Print-in-Place Spring Loaded Box](https://www.instructables.com/Print-in-Place-Spring-Loaded-Box/)

---

## Real-World Applications of Print-in-Place
Print-in-place techniques have been widely adopted by hobbyists, engineers, and companies to create functional moving parts directly from the print bed. Here are some examples:

- **Windshield Wipers** – Hobbyists have used print-in-place techniques to create **windshield wipers** where the handle is made of **PLA or ABS** for structural strength, while the wiper blade itself is printed using **TPU** to provide the necessary flexibility.  
  *Source: [Reddit - 3D Printed Wiper](https://www.reddit.com/r/3Dprinting/comments/xyzabc/)*  

- **Hinged Tools and Clamps** – Many 3D printing enthusiasts have designed **print-in-place clamps** that feature **built-in hinges**, allowing them to function as **snap-fit clips** or **hand-tightened vices**. These are commonly printed in **PETG or PLA** for rigidity and **TPU for gripping surfaces**.  
  *Source: [Thingiverse - Print-in-Place Clamp](https://www.thingiverse.com/thing:2827439)*  

- **Flexible Prosthetics** – Companies and makers have leveraged print-in-place techniques to produce **prosthetic hands and fingers** that use **PLA or PETG for rigid bones** and **TPU for flexible joints**, eliminating the need for assembly while maintaining lifelike motion.  
  *Source: [e-NABLE Prosthetics](https://enablingthefuture.org/)*  

- **Functional Gears and Bearings** – Engineers have created **gears, universal joints, and bearing systems** using print-in-place techniques, often combining **Nylon or ABS for strength** and **TPU for dampening** to reduce friction and noise in moving parts.  
  *Source: [Hackaday - Print-in-Place Bearings](https://hackaday.com/2020/05/28/3d-printed-print-in-place-bearing-design/)*  

These applications highlight the **versatility** of print-in-place designs, demonstrating how **different materials can be strategically combined** to enhance performance.

---

## Design and Iterative Process
The needle nose pliers were designed with a nine-part assembly to accommodate the capabilities of the available 3D printers. The components include:

- **Four rigid parts:** Two handles and two tips, printed from PLA for structural integrity.
- **Two rubber tips:** Made from TPU to provide enhanced grip on small components.
- **Two handle grips:** Also made from TPU to improve user comfort.
- **One flexible inner piece:** Crafted from TPU, acting as a spring mechanism to return the pliers to the open position.

### Iterative Process  
During the design phase, I went through **three iterations** of the pliers before achieving the final working version:

1. **First Attempt:** The tolerance was too loose, causing the parts to **fall apart when clicked together**.
2. **Second Attempt:** The fit was improved, but the **thickness of the pliers was too thin**, leading them to **bend the wrong way under pressure**.
3. **Final Version:** Adjustments were made to **increase thickness** for strength and **fine-tune the tolerances**. TPU **rubberized tips and handles** were added for better grip and usability.

*Design Inspiration:*  
The initial design was inspired by modernist print-in-place pliers found in [this article](https://all3dp.com/3d-printed-flexible-pliers/). The **triangle patterning** was developed based on a **3x3 flexible square piece**, with suppressed patterns to balance durability and flexibility.

*Material Selection:*
- **PLA (Polylactic Acid):** Chosen for the rigid components due to its strength and ease of printing.
- **TPU (Thermoplastic Polyurethane):** Selected for the flexible components, providing the necessary elasticity for the spring mechanism and enhanced grip surfaces.

*Assembly Method:*
The design allows for a **hand-pressed assembly** without the need for additional tools. Tolerances were carefully calibrated to ensure a snug fit for the rigid components, while looser tolerances were applied to the rubber grips and tips to accommodate TPU flexibility.

---

## Specifications
- **Jaw Length:** Approximately 51 mm
- **Jaw Capacity:** Approximately 10 mm
- **Materials:**
  - *Handles and Tips:* PLA
  - *Rubber Tips and Handle Grips:* TPU
  - *Inner Spring Component:* TPU
- **Assembly:** Hand-pressed, no tools required
- **Printer Used:** Creality K1C

---

## Print Settings
*Comparison of PLA and TPU Print Settings:*

| Parameter           | PLA                         | TPU                         |
|---------------------|-----------------------------|-----------------------------|
| Nozzle Temperature  | 200-220°C                   | 210-230°C                   |
| Bed Temperature     | 50-60°C                     | 30-60°C                     |
| Cooling Fan         | On                          | Off or Low                  |
| Print Speed         | 60-100 mm/s                 | 20-40 mm/s                  |

*Source: [Creality Filaments Parameter Guide](https://store.creality.com/blog/creality-3d-printer-filaments-type-parameter)*


---

## CAD Model
An interactive view of the CAD model is embedded below for a more detailed understanding of the design.

<iframe src="https://a360.co/4bFuyR6" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

## Image Gallery
{% include gallery caption="From left to right: Initial prototype testing, design iteration for optimized spring geometry, and the final working model of the pliers." %}

---

## Operation and Use
1. **Assembly:** Align and press the components together according to the design specifications. No tools are required; the parts are designed for a snug fit.
2. **Testing:** Confirm the spring-back function and check for smooth movement.
3. **Use:** Grip and manipulate through-hole resistors or similar small components with precision.

*Demonstration:*
![Pliers in Action](https://example.com/assets/img/Pliers/Demo.gif)

---

## Conclusion
This project demonstrates the potential of combining rigid and flexible materials in 3D printed designs. The final product effectively grips small electronic components, showcasing the value 
