---
title: "Custom Multimaterial Pliers"
excerpt: "These custom multimaterial pliers are able to successfully pick and place at least one resistor."
header:
  image: assets/img/IMG_8871.jpeg
  teaser: assets/img/IMG_8872.jpeg
gallery:
  - image: assets/img/IMG_8870.jpeg
  - image_path: assets/img/IMG_8873.jpeg
  - image_path: assets/img/IMG_8872.jpeg

---
# Description (background)

The purpose of this project was to create pliers with different materials to practice print-in-place parts. In order to measure the efficacy of design, the pliers were tested to carry at minimum one resistor.

Print-in-place parts refers to any printable design that has interlocking or moving mechanisms printed as a single assembly [1](https://www.thingiverse.com/blog?p=print-in-place-beginners-guide). Consistent with their singular print, parts are distinct in that they are simultaneous in movement. Asides from educational purposes such as for this project, there are many real world examples of print-in-place parts. An example of this can be seen in living hinges which is essentially thin plastic that connects two pieces [2](https://www.hubs.com/knowledge-base/how-design-living-hinges-3d-printing/). This is utilized in anything from food packaging, storage containers, shampoos, or even toys. 

In this case, the goal was thus to make a functional set of pliers in one print with no assembly. In regards to materials printing well together, adherence or bonding can be determined by similar chemical composition, surface energies, cooling rates, shrinking rates, and mechanical properties. For example, in a multimaterial print, ABS and TPU could thus be a good combination to print for in this project. Unfortunately, due to limited multimaterial  printers, this was performed in more than one print. For this reason, TPU and PLA were utilized. The goal of the assignment was thus to make a three part design incorporating two rigid and one elastic components. 

# Cad Model
The following model reflects the multimaterial (print-in-place) nose pliers created.  
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811c1b3e412b5dbcaa1?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Design and 3D Printing

The design consisted of three parts: the jaws, the handles, and the center piece. The following design, being multimaterial, was created with PLA and TPU.The center “spring component”, which is essential for the movement of the pliers, was made with TPU due its high elasticity and high durability. The “jaws” and “handles” of the pliers, which are essential for usability of the pliers as the jaws are intended to grab on the resistor through the user controlling and squeezing the handles, were made out of PLA to ensure the rigid structure. 

An iterative design approach was taken for this project. The center “spring component” took multiple attempts to design given this was my initial experience using the pattern feature on fusion.The center “spring component” had to be perfectly shaped to be contained inside the matching triangular pockets of the jaws and handles for adherence. Likewise, the center “spring component” required a certain print setting. For example, the layers of solid material were reduced to 0, the perimeters were increased (to 6), and the infill was changed to rectilinear with a sparse of 18%. The rectilinear orientation is essential as it creates the one direction movement; this paired with the elasticity of TPU makes it possible to move the jaws by squeezing the handles. Initially when printing the center “spring component” because the “teeth” of the design (for the locking mechanism) were not initially joined, the printer did not recognize the “teeth” as one design with the center and thus the teeth printed separately as apparent below. It is worth mentioning also 0.1mm overlap was added when printing this center “spring component” to ensure a tight fit. The images below depict the center “spring component” iterative process.

The following design was inspired by the various examples of pliers presented in class. As noted in class, the in-pocket triangular casings are rooted by traditional Japanese design. The in-pocket triangular casing allows the different materials to connect sound and tightness. 

![iteration](assets/img/IMG_8900.jpeg)
![iteration](assets/img/IMG_8901.jpeg)

# Relavent Specifications 

The jaw length is 95 mm. The tips of the jaw to grab the resistor is 10.5 mm long. The jaw capacity is 9.25mm. 

![Gif of Pliers Working](assets/img/Adobe Express - IMG_8869-2.gif)
The following gif shows these custom multimaterial pliers are able to successfully pick and place at least one resistor.
As seen, the pliers flex appropriately and successfully are able to move one resistor at minimum.

# Adjusted Printing Settings 

| Jaw and Handle Component Setting  | Adjustment |
| ------------- | ------------- |
| Infill Pattern | JuxtaPosition  |
| Material | PLA  |
| Top Solid Layers | 4  |
| Bottom Solid Layers | 3  |

| Center Component Setting  | Adjustment |
| ------------- | ------------- |
| Infill Pattern | Rectalinear  |
| Infill Sparse | 18%  |
| Fill Angle | 90 degrees  |
| Material | TPU  |
| Top Solid Layers | 0  |
| Bottom Solid Layers | 0  |
| Perimeter Contor | 6  |

