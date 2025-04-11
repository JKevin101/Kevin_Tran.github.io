---
title: "Bike Phone Mount Holder"
excerpt: "This project involves designing and 3D printing a phone holder for a bike or scooter, allowing for easy attachment and secure rotation between portrait and landscape orientations."
header:
  image: /assets/img/Phone_Mount_Holder/Teaser.jpg
  teaser: /assets/img/Phone_Mount_Holder/Teaser.jpg
gallery:
  - url: /assets/img/Phone_Mount_Holder/Render.png
    image_path: /assets/img/Phone_Mount_Holder/Render.png
    alt: "Render"
  - url: /assets/img/Phone_Mount_Holder/Section Analysis.png
    image_path: /assets/img/Phone_Mount_Holder/Section Analysis.png
    alt: "Section Analysis"
  - url: /assets/img/Phone_Mount_Holder/GIF.gif
    image_path: /assets/img/Phone_Mount_Holder/GIF.gif
    alt: "GIF"
---

This project focuses on the design and fabrication of a phone mount holder for a bike or scooter. The holder allows for quick attachment and secure rotation between portrait and landscape orientations without requiring tools. It incorporates a detent mechanism to provide tactile feedback for rotation and ensures the phone remains securely gripped while riding.

{% include gallery caption="The images showcase the final design: the left image shows the final design of the phone mount holder, the right image displays the section analysis of detent mechanism as well as the final section design, and a .gif of the mount moving  vertically and horizontally." %}

---

## Top-Down Modeling Description and Process
- This project leveraged the top-down modeling approach by starting with the highest-level component (the bike mount). From there, I worked down to design the phone case holder, incorporating a detent mechanism to help support the range of motion for rotating the phone between portrait and landscape orientations. This approach allowed me to focus on fitting components together efficiently while ensuring functionality.

---

## Rationale Behind the Design
- The design was based on a hinge mechanism for the mount, allowing easy installation. The use of two detent mechanisms provides the necessary degrees of freedom to rotate the phone and lock it securely in place in both orientations. This approach balances ease of use with secure, stable mounting for the phone.

---

## Rotation Mechanism Used
- Two detent mechanisms were used to rotate the phone horizontally and vertically. This mechanism worked well due to the use of ball bearings and springs, which ensured the phone snapped securely into place when rotated. The harder springs provided the necessary resistance for smooth rotation and secure placement.

---

## Adjustments for 3D Printing
- All dimensions required tolerance adjustments, with a loose tolerance of 0.15 mm for the holes used for screws and nuts. This ensured that each part could move freely without being too tight while maintaining enough resistance to keep the parts securely in place and prevent any loose connections during use.

---

## 3D Printing Technology Used
- The primary printing technology used was FFF (Fused Filament Fabrication) with the Creality K1C printer. This allowed for rapid prototyping and testing of tolerances, making it easier to refine the design. The final version of the mount and detent mechanism was printed using SLS (Selective Laser Sintering) with nylon for greater durability, as PLA would not provide enough strength to maintain its structural integrity in harsh conditions.

---

## Assembly Instructions
- Assembly involves combining multiple parts together using screws, nuts, ball bearings, and compression springs. To use the mount, simply tighten a screw once to hold the mount securely in place. The degree of freedom allows for easy adjustment, and the phone can be securely held in place without any risk of falling out.

---

## Printing Technology for Each Part
- The mount and detent mechanism were made using SLS with nylon, ensuring durability and resistance to breakage under tough conditions. The phone holder was made from PLA, as it didn't require as much strength to hold the phone. The grip was added to the mount for better adhesion to the bicycle handlebar, while the phone holder compresses and grips the phone securely.

---

## CAD Model
<iframe src="https://a360.co/3XX2wuJ" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

## Components

This section includes images and descriptions of the individual components used in the phone mount holder:


| **Component**       | **Description**                                        | **Image**                                      |
|---------------------|--------------------------------------------------------|------------------------------------------------|
| **Mount**           | The primary structure that attaches to the bike handlebar, providing support for the phone holder. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Mount" width="200"/> |
| **Clip**            | A clip that securely holds the phone in place.         | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Clip" width="200"/> |
| **Ball Rod**        | The component that allows the rotation mechanism to move the phone horizontally. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Ball Rod" width="200"/> |
| **Detent Base**     | The base of the detent mechanism that ensures the phone stays in place at the desired orientation. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Detent Base" width="200"/> |
| **Detent**          | The ball-bearing mechanism that locks the phone in place at specific rotation angles. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Detent" width="200"/> |
| **Top Detent**      | The top part of the detent mechanism that works in conjunction with the detent base. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Top Detent" width="200"/> |
| **Phone Mount**     | The part that holds the phone securely in place during use. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Phone Mount" width="200"/> |
| **Top Plate**       | The top plate that provides additional structural support and stability for the entire assembly. | <img src="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAA..." alt="Top Plate" width="200"/> |

![Mount](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAA...)


---
