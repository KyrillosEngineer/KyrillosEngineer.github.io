---
title: "Custom Bike Phone Mount"
excerpt: "This custom bike phone mount rotates landscape and portrait."
header:
  image: assets/img/IMG_0451.jpeg
  teaser: assets/img/IMG_0454.jpeg
gallery:
  - image_path: assets/img/IMG_0457.jpeg
  - image_path: assets/img/IMG_0465.jpeg
  - image_path: assets/img/IMG_0466.jpeg

---
# Description (background)

The following phone mount was designed using the process of top-down modeling. Top-down modeling leverages an initial design intent first with specific subsystems or details added next [1](https://www.autodesk.com/solutions/top-down-modeling). Top-down modeling is great for producing complex modeling as future planning and continued coordination can be mitigated.  Compared to assemblies for example, top-down modeling emphasizes global parameters which help in the case of rework any changes; this allows for rapid iteration and reduced errors. 

This technique was useful when designing the bike phone mount as the design underwent many iterations before taking the final form. The bike phone mount has different interlocking components; with top-down modeling, it was easy to update changes and avoid mistakes. Specifically with the ball dent mechanism, sizing was extremely crucial in relation to all parts from the spring compartment, ball size, and ball dent sizes. 


# Cad Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811797ca02df317ef95?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Design and 3D Printing

As mentioned, the design of the bike phone mount underwent several design iterations. The first iteration was inspired by the fundamental basics of the design [2](https://a360.co/4tUYMY7); at the simplest level the design needed to clamp onto the bike bar, hold the phone, and be able to rotate. For the purposes of this assignment, the phone mount had to also fit the provided bike handle (22.2mm), rotate both horizontally and vertically, and incorporate a ball dent mechanism with a ball [3](https://www.amazon.com/dp/B08KTBM74G?_encoding=UTF8&ref=cm_sw_r_cp_ud_dp_JJ291HCGP34Q6S5E5WH5&ref_=cm_sw_r_cp_ud_dp_JJ291HCGP34Q6S5E5WH5&social_share=cm_sw_r_cp_ud_dp_JJ291HCGP34Q6S5E5WH5&th=1) and spring component [4](https://www.amazon.com/dp/B092R6CK89?_encoding=UTF8&ref=cm_sw_r_cp_ud_dp_PXVTPNAWY5ZCRPB8NT42&ref_=cm_sw_r_cp_ud_dp_PXVTPNAWY5ZCRPB8NT42&social_share=cm_sw_r_cp_ud_dp_PXVTPNAWY5ZCRPB8NT42&th=1). This mentioned design lacked creativity and was therefore abandoned early in the process. After doing external research, I was very drawn to the idea of a minimalist design. The following design in particular was something I wanted to replicate given that, when the mount was not in use, the design was barely noticeable [5](https://www.youtube.com/shorts/S4l79fcqU4s). Furthermore, the design was capable of rotation but after further analyzing its commercial use [6](https://loop.cc/en-us/products/loop-mount-twist?utm_source=avelon&utm_medium=affiliate&avln_cid=fd3f05f8-c8a7-4bca-b71e-1185d4f3abe2), I found it extremely difficult to fit the ball and spring mechanism properly. For this reason, this design suffered from sizing issues when attempted and was therefore not capable of securing the phone in place [7](https://a360.co/4d19GoH). 

After this research, what became most important to the success of the design was focusing on the ball dent mechanism. Inspiration was drawn from this simple ball dent mechanism [8](https://www.youtube.com/watch?v=qUkXTm1FJAw&t=80s). This design was implemented by designing an inner circular component to house a spring (20mm). With the ball (8mm) to sit on spring, this component also accounted for the idea that ⅔ of the ball could be housed in the component also. Following this design, an extruded circular pole could hold the other component. In my design, I decided to attach this inner component to the component which will attach to the bike mount. With these measurements, an outer component was designed with the dents of the ball extruded; this was possible through the circular pattern feature. With these designed indentations, as the outer component rotates around the inner component the spring will force the ball to lock the motion in place; this is identifiable by the clicking sound. The outer component was designed to fit in the circular pole coming from the inner component. In my design, I decided to thread this pole just enough to add a designed nut to hold the compartments in place without limiting the rotational movement. 

![iteration](/assets/img/IMG_0456.jpeg)
Cross-section view of internal rotation mechanism.

Building of this mechanism, given the vertically threaded pole and threaded nut, the phone holder had to have been designed vertically. Inspiration was drawn from the following design [9](https://youtu.be/lbjfYI-VtNI?si=h-mKocR8QopmS4Th). A vertical pole was designed on each side of the threaded pole attached to the outer rotating component. These poles were attached to the phone holder mechanism. The beauty of this mechanism is it has two detachable parts that allow any size phone to fit and be locked appropriately. This vertical design allowed for something for the user to grab and spin to activate the rotation through the ball dent mechanism. 

![iteration](/assets/img/IMG_0453.jpeg)
Fusion Rendering of phone holder with phone on it.
![iteration](/assets/img/IMG_0455.jpeg)

Clearance and tolerance was accounted for in the original design and print as the compartment and pattern was designed with 4mm of clearance as if it were designed for a longer spring.This was especially necessary given the fact this would be 3d printed with filament which could shrink or create a tight fit. 3D printing with filament provides effective durability and temperature resistance. Preferably, this design should have been printed with PLA but, due to time constraints and filament shortages, ABS was chosen. Because my design did not utilize screws, ABS actually ended up working perfectly fine with minimal shortcomings. Each part was printed in ABS. ABS produced some warping specifically in the bottom clamp. Filament is best for quick and easy prototyping but in this case, given the orientation of design, there was so much support material beyond. Ultimately, this design worked as the ball dent mechanism produced rotational movement. Pictured are real-life individual images of each of the top-down components.

![iteration](/assets/img/IMG_0458.jpeg)
![iteration](/assets/img/IMG_0459.jpeg)
![iteration](/assets/img/IMG_0460.jpeg)
![iteration](/assets/img/IMG_0461.jpeg)

# Working Demonstration  

![Putting on the Phone](/assets/IMG_0449-ezgif.com-video-to-gif-converter.gif)
The following depicts placing the phone on the mount. 

![Phone Spinning](/assets/IMG_0447-ezgif.com-video-to-gif-converter.gif)
The following depicts the phone on the mount spinning. 

![Phone Spinning Closer](/assets/IMG_0450-ezgif.com-video-to-gif-converter.gif)
The depicts a closer look of the phone on the mount spinning. 

# Materials and Instructions 

| Material  | Quantity |
| ------------- | ------------- |
| M5 x 5.7 Heat Insert | 4  |
| M5x30mm Screws | 2  |
| 8mm Ball | 1  |
| 8x20 Compression Spring | 1  |

Following design and printing, assembly is simple. Remove excess supports and material. Begin by interesting the four M5 heat inserts in the, 2 in the bottom clamp and 2 in the top clamp. Following this, to build the ball dent mechanism, insert the ball and spring in the designated component in the top clamp piece. Attach the outer rotating clamp which has the phone holder already attached over the top of this (note: it will be a tight squeeze/be careful as the ball may pop out). Next, add the small threaded nut over the center pole for added security. From there, place your phone in the designated holder position. Add the other clamp to clamp the phone in place horizontally. Add the threaded nut to keep it in place. 


{% include gallery caption="Rendering and real-life images of the bike mount including the components (spring and ball not pictured)" %}
