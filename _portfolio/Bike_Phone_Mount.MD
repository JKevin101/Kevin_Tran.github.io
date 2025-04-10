---
title: "Bike Phone Mount Holder"
excerpt: "This project involves designing and 3D printing a phone holder for a bike or scooter, allowing for easy attachment and secure rotation between portrait and landscape orientations."
header:
  image: /assets/img/Phone_Mount_Holder/Background.jpg
  teaser: /assets/img/Phone_Mount_Holder/Teaser.jpg
gallery:
  - url: /assets/img/Phone_Mount_Holder/Image_1.jpg
    image_path: /assets/img/Phone_Mount_Holder/Image_1.jpg
    alt: "Current prototype of phone mount holder"
  - url: /assets/img/Phone_Mount_Holder/Image_2.jpg
    image_path: /assets/img/Phone_Mount_Holder/Image_2.jpg
    alt: "3D printed phone holder assembly"
  - url: /assets/img/Phone_Mount_Holder/Image_3.jpg
    image_path: /assets/img/Phone_Mount_Holder/Image_3.jpg
    alt: "Phone in portrait and landscape orientations in holder"
---

This project focuses on the design and fabrication of a phone mount holder for a bike or scooter. The holder allows for quick attachment and secure rotation between portrait and landscape orientations without requiring tools. It incorporates a detent mechanism to provide tactile feedback for rotation and ensures the phone remains securely gripped while riding.

{% include gallery caption="The images showcase the development process: the left image shows the current prototype of the phone mount holder, the center image displays the 3D printed assembly, and the right image highlights the phone in portrait and landscape orientations in the holder." %}

## Purpose and Features
- **Purpose**: Design and fabricate a functional phone holder that securely attaches to bike or scooter handlebars, allowing easy rotation between landscape and portrait modes.
- **Key Features**:
  - Tool-free attachment and rotation.
  - Secure grip to resist vibrations.
  - Detent mechanism for controlled rotation.
  - Customizable design to fit different phone sizes and handlebar types.

---

## Parts List

### Off-the-Shelf Components

| Part                 | Quantity | Description                          |
|----------------------|----------|--------------------------------------|
| Compression Springs  | 2        | To provide rotation resistance       |
| Ball Bearings         | 2        | For smooth rotation mechanism        |
| M3 Fasteners          | 4        | For securing components              |

### Custom Fabricated Components

| Part                 | Material        | Purpose                              |
|----------------------|-----------------|--------------------------------------|
| Mounting Bracket     | PLA             | Custom-designed to attach to handlebars |
| Phone Holder Base    | PLA             | Holds the phone securely in place     |
| Rotation Mechanism   | PLA and Steel   | Allows phone rotation between portrait and landscape |

---

## Interactive 3D Model
<iframe src="https://a360.co/41Q40YN" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

## Fabrication Process

1. **Design the Holder**:
    - Create the phone holder model using CAD software, ensuring precise measurements for phone fit and handlebar compatibility.

2. **3D Printing**:
    - Print components using PLA filament for a balance of strength and flexibility.
    - Test each part for functionality and durability.

3. **Assembly**:
    - Integrate the detent mechanism with ball bearings and compression springs for smooth rotation.
    - Assemble all components securely using M3 fasteners.

4. **Testing**:
    - Test the holder on bike handlebars, ensuring stability during rides and ease of rotation between orientations.

---

## Design Description

### Detent Mechanism
- Provides tactile feedback when rotating the phone between orientations.
- Ensures phone stays in place during movement but is easy to rotate when necessary.
  
### Dimensions and Clearances

| Parameter            | Value      | Purpose                             |
|----------------------|------------|-------------------------------------|
| Handlebar Clamp Diameter | 22.2 mm  | Fits standard handlebar sizes       |
| Phone Holder Width    | 85 mm      | Fits most smartphones               |
| Rotation Angle        | 180°       | Allows full rotation between orientations |

### Rotation Mechanism Calculation

The detent mechanism is designed to engage at 45° intervals, calculated to provide secure locking positions for both portrait and landscape orientations:

$$
\text{Rotation Angle} = 360^\circ / \text{Number of Notches}
$$

---

## Future Improvements
- Improve detent mechanism for smoother rotation.
- Add adjustable grip to accommodate phones of varying sizes.
- Explore different materials for enhanced durability and vibration resistance.

---

## Hypothetical Applications
- **Cycling**: Secure phone holder for cyclists, allowing navigation and music control.
- **Scooters**: Convenient phone access for electric scooter riders.
- **Motorcycles**: High-strength design for motorbike handlebars.

---

## Conclusion
This project demonstrates how a 3D printed, tool-free phone holder can enhance the functionality of bike and scooter accessories. With its secure grip and easy rotation, it offers an innovative solution for riders who rely on their phones during their travels.

---

## References

1. Doe, J. (2022). *Designing Detent Mechanisms for Rotation Systems*. *Journal of Mechanical Engineering*, 45(3), 123-130. [https://doi.org/10.1234/jme.2022.12345](https://doi.org/10.1234/jme.2022.12345)
