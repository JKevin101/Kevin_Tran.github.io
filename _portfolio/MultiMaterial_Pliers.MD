---
title: "Multi-Material Pliers"
excerpt: "A functional, multi-material 3D printed pliers designed for gripping and manipulating through-hole resistors."
header:
  image: /assets/img/MultiMaterial_Pliers/Background.jpg
  teaser: /assets/img/MultiMaterial_Pliers/Teaser.jpg
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
This project focuses on creating functional, multi-material pliers using 3D printing techniques. The pliers are designed to grip and manipulate through-hole resistors, utilizing print-in-place manufacturing and elastomeric materials to achieve a flexible, spring-return mechanism.

Print-in-place models are innovative designs that function immediately after being printed without the need for additional assembly. These designs often rely on careful clearances between moving parts and precise print orientations. While single-material extrusion is common, incorporating flexible components can greatly enhance functionality.

## Video Demonstration
<iframe width="560" height="315" src="https://www.youtube.com/embed/UGwhHsRSFCI" frameborder="0" allowfullscreen></iframe>

---

## Real-World Applications of Print-in-Place
Print-in-place techniques have been widely adopted by hobbyists, engineers, and companies to create functional moving parts directly from the print bed. 

### Example Applications
- **Squeegee** – Hobbyists have used this technique to create window wipers where the handle is made of PLA or ABS for strength, while the wiper blade itself is printed using TPU for flexibility.  
  *Source: [Yeggi - 3D Printed Squeegee](https://www.yeggi.com/q/tpu+squeegee/)*  

- **Hinged Tools and Clamps** – Many designers create print-in-place clamps with built-in hinges for snap-fit clips or hand-tightened vices, often using PETG or PLA for rigidity and TPU for gripping surfaces.  
  *Source: [Printables - Print-in-Place Clamp](https://www.printables.com/model/974751-clamp-print-in-place)*  

- **Spring Loaded Box** – Many designers incorporate this print-in-place technique making a 3D-printable, spring-loaded storage box designed in Fusion 360, featuring built-in flexing mechanisms that eliminate the need for assembly.
  *Source: [AutoDesk Instructables - Print-in-Place Spring Loaded Box](https://www.instructables.com/Print-in-Place-Spring-Loaded-Box/)*  

---

## Design and Iterative Process
The print-in-place pliers were designed with a nine-part assembly to accommodate the capabilities of the available 3D printers. 

### Components
- Four rigid parts: Two handles and two tips (PLA)
- Two rubber tips: Provides grip for handling resistors (TPU)
- Two handle grips: Improves comfort (TPU)
- One flexible inner piece: Acts as a spring mechanism (TPU)

### Design Iteration & Prototyping  
Refining the pliers required multiple test prints to achieve the best balance of fit, strength, and flexibility. Below is the progression of three key iterations:  

{% include gallery caption="From left to right: Initial prototype testing, design iteration for optimized spring geometry, and the final working model of the pliers." %}  

1. **First Attempt:** The tolerance was too loose, causing parts to fall apart when clicked together.  
2. **Second Attempt:** The fit was improved, but the thickness was too thin, making the pliers bend the wrong way under pressure.  
3. **Final Version:** Increased thickness for durability, refined tolerances, and incorporated TPU rubberized tips and handles for enhanced grip.  

This iterative process ensured a functional print-in-place mechanism while maintaining a strong, yet flexible, spring action.  

### Design Inspiration  
The initial design was inspired by modernist print-in-place pliers found in [this article](https://all3dp.com/3d-printed-flexible-pliers/). The triangle patterning was developed based on a 3x3 flexible square piece, with suppressed patterns to balance durability and flexibility.

### Materials Used
- PLA (Polylactic Acid): For rigid handles and tips
- TPU (Thermoplastic Polyurethane): For flexible spring, grips, and rubberized tips  

### Assembly Method
The design allows for hand-pressed assembly without the need for additional tools.  
- Tight tolerances ensure a snug fit for rigid components.  
- Looser tolerances accommodate TPU flexibility in grips and tips.  

---

## Specifications  

| Feature            | Measurement |
|--------------------|------------|
| Jaw Length        | ~51 mm     |
| Jaw Capacity      | ~10 mm     |
| Square Size       | 6 mm       |
| Tip Thickness     | 1.5 mm     |
| Grip Thickness    | 3 mm       |
| Tight Tolerance   | 0.1 mm     |
| Looser Tolerance  | 0.15 mm    |

--- 

## Print Settings   

| Parameter          | PLA          | TPU          |
|--------------------|-------------|-------------|
| Nozzle Temp       | 200-220°C    | 210-230°C   |
| Bed Temp          | 50-60°C      | 30-60°C     |
| Cooling Fan       | On           | Off/Low     |
| Print Speed       | 60-100 mm/s  | 20-40 mm/s  |

[Creality Filaments Parameter Guide](https://store.creality.com/blog/creality-3d-printer-filaments-type-parameter)

---

## CAD Model  

<iframe src="https://a360.co/4bFuyR6" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

## Operation and Use  
1. **Assembly:** Align and press the components together. No tools required.  
2. **Testing:** Check for proper movement and spring-back function.  
3. **Use:** Grip and manipulate through-hole resistors or similar small components.  

---

## Conclusion  
This project demonstrates how multi-material 3D printing can be used to create functional, print-in-place designs. By strategically combining rigid and flexible materials, these pliers effectively grip small electronic components while maintaining durability and usability.  

