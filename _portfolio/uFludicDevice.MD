---
title: "Pinch Flow Fractionation (PFF) Device"
excerpt: "50x70 mm device for sorting particles between 125-150 micrometers and 425-500 micrometers."
header:
  image: assets/img/IMG_8871.jpeg
  teaser: assets/img/IMG_8872.jpeg
gallery:
  - image_path: assets/img/IMG_8870.jpeg
  - image_path: assets/img/IMG_8873.jpeg
  - image_path: assets/img/IMG_8872.jpeg

---
# Description (Introduction)

Pinch flow fractionation (PFF), at a very simple level, is a method of separating small particles. This passive method of flow first appeared in a 2004 paper [1](https://pubs.acs.org/doi/10.1021/ac049863r); continuous flow and separation of particles in PFF is reliant on geometry as narrow channels “pinch” particles in a predictable streamline that can be mathematically demonstrated. In PFF, particles are made to collide being pushed to the uppermost channel. This is done in order to sort the particles into different outlets; particles spread according to the streamline with smaller particles rising to the upper most channel. According to PFF, particle flow can be predicted using channel width and particle diameter as a particle’s center of mass is crucial for its movement. Changing flow rates are also impactful. The following equation (where y axis position of the particle is equal to the width of the pinched region minus half the diameter of the particle times the width of the broad region over the the width of the pinched region) is extremely useful for determining flow. 


There are many applications that require the sorting of particles [2](https://www.sciencedirect.com/science/article/abs/pii/S0255270124004252). Specific applications of particle separation include sorting white and red cells, cancerous cells, or exosomes. Compared to traditional methods of separation, PFF provides a mathematical framework that allows for precise control. With reliance on geometry, there is no physical sieving and thus the method is continuous and less prone to clogging. 

# Cad Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811ae6e416bf0a0ed11?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Design
Following the ideas in the original PFF paper, this design followed a symmetric approach as evident by the uniform pinching/expanding and spacing of branches. This approach was chosen due to its simplicity and noted effectiveness in achieving desired flow. The goal of the design was laminar flow which was possible through the geometry of the device. Following the aforementioned logic of the equation, smaller particles rise to the upper most position and greatest separation would be achieved through a larger common ratio of widths.  

Outlet boundaries were placed under these assumptions as well as the functional requirements noted in the assignment with small particles being 125-150 micrometers and the large particles being 425-500 micrometers with the device contained in 50x70 mm space. The smallest channel should be 1.2-1.5 times the diameter of the largest particle. The broad section must be at least 15 mm. Inlets or outlets must be at least 11 mm apart from each other. Channels must be 3 mm away from the edge. There must be a 4:1 aspect ratio. With these specifications, the y axis location of the large particles was determined to be from 9750-10962.5 and the y axis location of the small particles was determined to be from 13425-13812.5. With this, it was very evident the smallest particle outlet was at the very top, with the large below, and the buffer at the bottom. Following the idea of center of mass mentioned, outlet boundaries were placed in between these vertical positions to account for possible paths.The following is a depiction of some of my calculations as well as critical dimensions of channels determined. The following was then applied to CAD. 

Possible balance issues were addressed by following in line with previous attempts. The main issues regarding balance involve the flow of the buffer. In order to shift this flow and prevent any particle redistribution as a result, on-flow chip resistance was added by altering the lengths of the channels and thereby increasing their hydraulic resistance. As noted, keeping the buffer outlet the shortest length allows it to have the least resistance and the largest fraction of flow. The particle outlets were hence made longer. This idea seemed in line with previous literature and attempts as well as the fluids resistance equations [3](https://pmc.ncbi.nlm.nih.gov/articles/PMC9118023/).  It is worth mentioning the outlets nonetheless had to remain equidistant from each other vertically. In hindsight, looking at the design, there are sharp edges that should be smoothened as these could have factored into particle deviation. Likewise, the smallest path could have been altered by being slightly wider as evident by the testing results later mentioned. All of this could point to the need for a more quantitative approach to approaching resistance needed. 

# Instructions  

Very simply, following a final CAD design, the device was printed with clear resin for visibility purposes and a slightly larger height for accuracy purposes. As with resin prints, it was washed for five minutes on the buildplate then again for five minutes detached from the plate. The device was then left to dry until all IPA was dried off. Any debris was blown off using compressed air. A one minute surface cure was performed with the supports on; the supports were removed following this. Note safety attire and measures were taken. Likewise, note, the inside of the uncured mold was not to be touched under any circumstance. From this, the mold was cased out and treated with plasma to produce the mold used for testing. 

![Gif of Pliers Working](/assets/img/Adobe Express - IMG_8869-2.gif)

# Discussion 

Resin printing was the preferred method of manufacturing given the ability to quickly print smooth, highly detailed parts. This was essential for the very small channels that required high resolution for printing. Likewise, multiple parts could be printed at once. If necessary, the design could be scaled up to account for different particles following the same processes above; increased pinch width, length, and outlet locations could be recalculated to fit a wider range of particle size. In general, as noted, printer specifications such as 85 μm minimum feature size limit the lower limit particle size that can be separated. 

As evident by the testing of this design [4](https://canva.link/8s7u201cit3v9d0), there were times of success by which the particles did separate but improvements do need to be made as it was evident any level of success was not comprehensive. Note, initial errors in calculations resulted in an influx of particles initially in the video but with correction this was later stabilized. Nonetheless, as a result, at a certain point, particles clogged the upper most tube because of early influx. This also resulted in air bubbles but these were later cleared as evident. Given the pattern of separation that occurred, as mentioned previously, exploring a more concrete and precise means of calculating resistance is necessary. It is possible errors were possible through casting since the device is so small. In regards to the testing set up in general, as noted by Dr. Florian, a stand to angle the syringe pumps and rigid tubing could alleviate some difficulties and be possible improvements. Possible improvements in the future could also include built in design separators as one student successfully did.  

{% include gallery caption="Rendering and real-life images of custom multimaterial pliers" %}
