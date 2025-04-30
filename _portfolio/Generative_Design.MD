---
title: "Mug Holder Design"
excerpt: "This project involves designing a mug holder for a desk to optimize space and keep workspaces organized using generative design in Fusion 360."
header:
  image: /assets/img/Generative_Design/Teaser.jpg
  teaser: /assets/img/Generative_Design/Teaser.jpg
gallery:
  - url: /assets/img/Generative_Design/Render.png
    image_path: /assets/img/Generative_Design/Render.png
    alt: "Render"
  - url: /assets/img/Generative_Design/Design_Examples.png
    image_path: /assets/img/Generative_Design/Design_Examples.png
    alt: "Designs"
  - url: /assets/img/Generative_Design/GIF.gif
    image_path: /assets/img/Generative_Design/GIF.gif
    alt: "GIF"
---

This project focuses on the design and fabrication of a mug holder intended to be placed on the side of a desk. The holder helps keep desks uncluttered by utilizing vertical space, making it ideal for environments where space is limited. The design was created using generative design in Fusion 360, optimizing the structure based on forces acting when the mug is placed on the holder.

{% include gallery caption="The images showcase the final design: the left image shows the final render of the mug holder, the right image displays the different generative design outcomes, and the .gif demonstrates the holder's functionality in normal use." %}

---

## Video Demonstration
<iframe width="560" height="315" 
  src="https://www.youtube.com/embed/o_VVrviIlS4?feature=share" 
  frameborder="0" 
  allowfullscreen>
</iframe>

---

## Overview

The design is a mug/cup holder intended to be placed on the side of a desk. It aims to help when desks become cluttered, ensuring the holder does not take up additional surface space. The design was created using generative design in Fusion 360, optimizing the structure based on forces acting when the mug or cup is placed in the holder. This solution is ideal for environments where space is limited and helps organize workspaces by utilizing vertical space.

The main function is to hold a mug/cup securely while keeping the desk area uncluttered. This design is relevant as it solves a common issue in workspaces, allowing for better organization and easy access to essential items.

---

## Preserve and Obstacle Geometry

The preserved regions in the design include the bottom plate, fixed to the desk, the thread holder bottoms, and the top plate. These areas are critical for ensuring the holder remains securely attached to the desk and provides a stable base for the cup.

The main obstacles are the mug and the desk surface. The design must avoid interfering with the mug and mug handle to ensure there is space to fit the mug inside. Additionally, the space between the clamp and the top plate must have clearance for the screw and desk thickness to clamp properly.

---

## Load Case Application and Structural Constraints

For the generative design study of the mug holder, several forces were applied to simulate usage. A 200 N downward force represents the weight of the mug, simulating compression on the edges of the mug holder. A 0.736 N·mm remote moment was applied to simulate torque or twist from adjusting the mug, while a 1000 N upward force counteracts the downward force that is applied between the mug holder and the connection to the clamp.

An 80 N angled force at 40° simulates diagonal contact, such as an angled push or the mug pressing against the clamp. A 100 N bearing load represents radial pressure at pivot points, ensuring the holder can handle rotational forces. Lastly, a 300 N downward force simulates the vertical pressure stacked weight on the holder connection to the clamp.

These forces were applied at key areas like mounting points and clamp regions to evaluate load distribution and stability. Structural constraints were applied at the mounting points to prevent movement, ensuring the holder remains secure.

---

## Critique of Generative Design

Generative design is very useful in creating optimized geometries, particularly in reducing material use while maintaining structural integrity. However, while this offers incredible flexibility and optimization, it comes with limitations. For example, generative design may not always offer the most practical or manufacturable designs. Especially for more traditional or heavily regulated industries like automotive, this may require further iterations and modification.

Generative design also excels in fields where lightweight and efficiency are essential. Industries like aerospace or medical device manufacturing are areas where it can provide significant benefits, especially when aiming to reduce material waste while retaining high mechanical performance.

---

## Embedded Fusion 360 Model
<iframe src="https://a360.co/4d1l7ft" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

## Table of Forces Applied

| Name of Force     | Magnitude | Location                    | Rationale |
|-------------------|-----------|-----------------------------|-----------|
| Downward Force     | 200 N     | Edges of the mug holder     | Simulates compression from the weight of the mug |
| Remote Moment      | 0.736 N·mm| Clamp areas                 | Simulates torque from adjusting the mug |
| Upward Force       | 1000 N    | Connection between the mug holder and clamp | Counteracts the downward force |
| Angled Force       | 80 N      | Clamp interface             | Simulates diagonal contact when pushing or adjusting the mug |
| Bearing Load       | 100 N     | Pivot points                | Ensures the holder handles rotational forces |
| Vertical Pressure  | 300 N     | Connection to the clamp     | Simulates the vertical pressure from the mug's weight |

---
