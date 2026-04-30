---
title: "Generative Design SLS Truck Hanger with Motor Mount"
excerpt: "SLS printed truck hanger with motor mount for an electric scooter."
header:
  image: assets/img/IMG_8871.jpeg
  teaser: assets/img/IMG_8872.jpeg
gallery:
  - image_path: assets/img/IMG_8870.jpeg
  - image_path: assets/img/IMG_8873.jpeg
  - image_path: assets/img/IMG_8872.jpeg

---
# Description on Generative Design + Powder Bed Fusion 

The purpose of this project was to capitalize on the unique pairing of powder bed fusion and generative design. Generative design is a process by which computer automated design systems use artificial intelligence to design alternative designs based on set parameters [1](https://www.autodesk.com/solutions/generative-design/manufacturing). Artificial intelligence produces innovative designs by testing the limits of a design given the geometry constraints to improved, consolidated, light weight, and sustainable designs. With multiple design iterations and options, generative design allows for optimized material usage. Likewise, powder bed fusion is the process by which powder is heated below melting point through radiant/convention heating to which a laser scans to provide energy as layers of powder are added layer by layer. The result is fast, batch prints that are support free and mechanically strong [2](https://www.protolabs.com/resources/design-tips/powder-bed-fusion/). Powder bed fusion is able to produce the unique shapes made by generative design easier than traditional 3D printing methods. 


The combination of these two processes, with their unique ability to potentially save cost and time, has impacted both the aerospace and automotive industry. One example of this can be seen in companies using the technologies to design fluid structures optimized for large scale meet high business needs [3](https://www.youtube.com/watch?v=qeloZL7DGC8). Within the automotive industry, the technology is being studied to reduce the weight of cars significantly [4](https://www.sciencedirect.com/science/article/pii/S1526612522003723). This is made possible in the idea that generative design can significantly reduce the number of components needed in an assembly. Examples of commercial uses that wanted to capitalize on this include general motors attempting to reduce eight components in a seat bracket to one, NASA using unique brackets for its excite telescope, and various companies attempting to reduce components in thrusters and cabin separators [5](https://digitaldesignnetwork.org/news/modern-uses-of-generative-design/). Perhaps one of the most unique utilizations of the technology is the design of the “skeletal chair” which is simply one singular component significantly less than traditional chairs [6](https://www.fastcompany.com/90334218/this-is-the-first-commercial-product-made-using-generative-design). 

# Design and Load Cases
In regards to generative design, load cases are important as they significantly improve outcomes. Generative design relies on load cases to produce minimum possible solutions as load cases inform where material is needed. Insufficient load cases could produce incorrect geometries with too much or too little material that may not be optimized properly or may be structurally insufficient respectfully. The challenge with load cases is often getting these load cases correct. 

| Name of Force  | Magnitude | Location  | Short Rational | Solution |
| ------------- | ------------- |
| Vertical load at the axle  | 1079 N | At the axle  | To represent the rider’s weight | For up to 110 kg person 110 kg x 9.81 m/ s^2 |
| Torque at the motor mount  | 5 N*m | At the motor mount  | To represent belt-driven propulsion| Motor output torque (recommended by artificial intelligence)  |
| Lateral load at the axle   | 540 N | At the axle  | To represent turning or carving |Half the initial static load |
| Vertical load at the mount   | 25 N | At the axle  | To represent the weight of the motor | For 2.5 kg motor 2.5 kg x 9.81 m / s^2 |
| Other vertical load at the axle  | 2158 N | At the axle  | To represent impact  | Double the weight of the rider  |
| Lateral load at the mount   | 167 N | At the motor mount   | To represent the belt tension   | Based on timing belt pull and 5 N*m torque at the mount (recommended by artificial intelligence)  |
| Gravity  | 9.807 m / s^2 | - 180.0 deg (Y)  | To represent the gravitational pull of the earth  | Force of g  |


With the emphasis of this project on experimenting with generative design, the use of artificial intelligence was permissible when generating forces. Loads were determined based on the examples of regular and extreme forces. The following table depicts the forces determined by artificial intelligence. Judging by the final outcome printed, the following forces did in fact produce adequate enough cases to produce a functioning model as depicted. The model was able to adequately hold the rotating motor, belt, and wheels and turn with enough clearance. 

Insert Gifs 


With this it is plausible to state, artificial intelligence was able to determine possibly the minimal amount of forces to consider. Nonetheless, given the thinness of the design in certain areas such as holding the motor mounting plate, greater consideration should be given when determining forces as there were possible missing considerations. Future iterations should follow the following process when determining which forces to apply to the model. For one, the relative weight of the rider should be determined; in this case, 110 kg was used as a general baseline. The weight of the rider is essential in determining the static gravitational load on the axles which is mass times gravitational acceleration. This force is essential as, when the rider is stationary, it should equate to the normal forces. With this, the weight of the motor should likewise be determined. With this measurement, the motor mount weight should have also included the weight of the belt and pulley factored in times gravity. Likewise, more precisely, the motor's center of mass should have been considered to determine moment weight. Without these exact measures prior, this could be one of the reasons the holding supports on the model, while adequate and held, felt thin. To add, the motor mount should have been a turning force instead of a lateral force as the motor will spin. Lateral forces to consider should include those on the axles which should have taken into account the idea that at a certain point in time, when turning, all the weight will be on one side; hence, this force could have included the combination of forces applied by the weight of the rider and forces due to acceleration towards one direction. This is not to mention the impacts of the force of friction for example. A more elaborate approach should have been taken for determining impact forces drom the motor and axle. Artificial intelligence determined that twice the static weight was an adequate marker for expressing these lateral forces to represent the dynamics of real world use; likewise, with regards to turning, artificial intelligence approximated it to be 0.5g of lateral acceleration. Future iterations of design should be more precise in calculating each of these forces mentioned in combination. Given this is an electric scooter, the intricacies of the motor introduced another element of torque. Artificial intelligence estimated this to be 5 N*m; a more precise reading could be taken by looking up the exact motor information as this again may have contributed to the thinness for the motor supports. With this, artificial intelligence also anticipated the pulley radius to be 30mm and hence a belt tension of 167N towards the pulley wheel. A future iteration should measure the radius of the wheel first and using the motor torque determine the axle acceleration using the total mass of the skateboard. As evident, while the cases provided were adequate, future iterations should take a more mathematically precise approach using the following guidelines to determine which forces to apply to the model. 


# ALSi10Mg and 17-4 PH Models
The following model reflects the ALSi10Mg truck outcome created.  
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811e50dc84da5485552?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
The following is a rendering of the completed longboard assembly with the generative design
ALSi10Mg truck.
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028113a07214b18081fe7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

The following model reflects the 17-4 PH (printed with Nylon 12) truck outcome created.  
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811373007d3efcf6220?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
The following is a rendering of the completed longboard assembly with the generative design
17-4 PH (printed with Nylon 12) truck.
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028113a07214b18081fe7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

When comparing the ALSi10Mg and 17-4 PH outcomes, although the same constraints were applied and a minimum safety factor of 2, ALSi10Mg notably produced a way more bulky outcome. This is notably because aluminum is less strong, the computer compromised by adding more material. The steel outcome appeared more refined as it is noted for its thinness. Less material here is a clear indication of the strength of the material. With this, 17-4 PH was chosen. Note that the design was ultimately printed with Nylon 12. It is possible that any areas that feel frail, given steel is way stronger, may have not felt this way. 

# Notes on Generative Design 
With this experience, the usefulness of generative design is extremely evident. The application of experimenting with different materials can be a clear means of optimizing shape, cutting costs, and gaining an expansive understanding of potential outcomes with different materials. As evident, the drawbacks appear to be the necessary information when creating a functional and optimal model. For one, with the necessity of different observe and preserve geometries, the process can seem double the work of simply creating a model. Double the work in a real-world setting can mean higher costs and time. Likewise, as evident by the final outcome, there is a necessity of physics to understand all the appropriate load cases that should be applied. Likewise, a level of intuition and thinking by the user is required. As seen in this project, generative design is amazing at creating light weight components especially when paired with the powdered printing. For reference, the steel component was 0.232 kg which is way less than any commercial option. Unfortunately, with this printing process, given the complex geometries produced, there is time needed for post-processing. With all this, it is plausible to see the application of generative design most useful in applications with low production volume but high performance needs. As mentioned, for this reason the technology has been used in the automotive and aerospace industries as making seat or engine brackets seem to be an appropriate example of a niche product with required constraints. 

![iteration](/assets/img/IMG_8900.jpeg)
![iteration](/assets/img/IMG_8901.jpeg)

# Relavent Specifications 

![Gif of Pliers Working](/assets/img/Adobe Express - IMG_8869-2.gif)



{% include gallery caption="Rendering and real-life images of custom multimaterial pliers" %}
