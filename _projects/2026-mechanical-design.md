---
layout: project
title: MAE 2250 Open Design Project
description: 
technologies: [Autodesk Fusion]
image: /assets/images/SpottedLanternfly_0901123.png
---

In our Intro to Mechanical Design (MAE 2250) class, we were tasked with developing a solution to address the growing population of the invasive Spotted Lanternfly. Since 2014, spotted lanternflies (SLF) have permeated through the north east, feeding on produce such as grapes and infecting over 70 plant species, threatening agriculture and biodiversity. The economic impacts of this invasive species have been estimated at $324 million annually.

So far, we are in the conceptual stage of defining our problem and brainstorming solutions.

[Client Pitch](#client-outline-and-pitch)

[Functional Prototype](#functional-prototype)

[Client Report](#client-report)


## Client Outline and Pitch:

**Proposed Solutions for Managing Spotted Lanternflies in Vineyards**

**Team:** Lanternfly Bye-Bye

**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape  

   Since 2014, spotted lanternflies (SLF) have permeated the northeast, feeding on produce such as grapes and infecting over 70 plant species, threatening agriculture and biodiversity. In 2025, the National Association of American Wineries valued New York’s wine industry at $16.81 billion. This high-value industry has been impacted by SLF, who damage grapevines and contaminate harvest. Below are two ideas our group has for addressing the issue. We appreciate any feedback you have for us.

### Poisonous Tree of Heaven
Our first idea focuses on managing the population of spotted lanternflies using a decoy tree of heaven. Our team would design a small container and fill it with a mix of tree of heaven sap and a toxin. Attracted by the sap, the lanternflies will dig into the container and ingest the toxin. Otherwise, the container can be equipped with a weight-activated nozzle that would douse the lanternflies in a toxic mix, similar to what many households currently use. The benefits of this product are the decoys are easily scalable and stackable, and they are able to protect the harvesters from the lanternflies while also working to reduce the fly population. By the end of the semester, our goal is to have a finalized trap and, ideally, have tested it in a real environment to see its effectiveness. 

### Essential Oils
Our second proposal attempts to prevent the spotted lanternflies from entering the vineyard by dettering them with essential oils.  By creating individual diffusers to place around the vineyard, the flies will not enter, and the plants will remain unharmed. Ideally, this idea could be developed to include a way to harm the lanternflies as well as deter them in order to help control the population and further protect the vineyard. This product would be nontoxic to surrounding plants and other animals, and would not require much maintence while protecting harvesters from the lanternflies.

### Key risks / unknowns

- Placement of the products is crucial. Because we are using a two-step solution, including attraction and detraction, we want to make sure we detract the flies into the attraction termination sites and not the other way around. Due to our budget and time constraints, we will have to rely on secondary research and data such as wind speed and direction.

-  Plant-safe compounds. Both of our proposed solutions involve liquid compounds to deter and remove lanternflies. The compounds used in the final solution will need to be safe for the grapes and approved by the FDA.


### Questions for the client
1. **Have you found anything that is effective at killing spotted lanternflies?**  
   *Decision affected: What measure to use to narrow down the population (toxins, phsyical means, etc)*
2. **Are spotted lanternflies deterred by other factors such as locations of the vineyards or human presence?**  
   *Decision affected: How to best implement our product* 
3. **Are there any parts of our plans that raise conerns for you?**  
   *Decision affected: Next steps* 


### References

- “New York Wine Industry - WineAmerica Economic Impact Study.” 2025. WineAmerica. WineAmerica Mobile. May 29, 2025. https://wineamerica.org/economic-impact-study-2025/new-york-wine-industry-2025/.

- “Spotted Lanternfly Reported Distribution Map.” 2017. CALS. 2017. https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly/spotted-lanternfly-reported-distribution-map.

- “Spotted Lanternfly in Perspective (U.S. National Park Service).” n.d. Www.nps.gov. https://www.nps.gov/articles/000/slf-in-perpective.htm.


## Functional Prototype

<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/overall-view.png" alt="Overall View" width="200">
<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/body-view.png" alt="Body View" width="200">
<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/lid-view.png" alt="Lid View" width="200">

### Prototype Assembly 
1. Gently press the motion sensors into the holes in the lid. Thread the wiring through the lid, ensuring connection is maintained between the sensors and the arduino.
2. Attach the bottle/nozzle connector to the spray bottle and the rest of the electronics in the center area of the base. Make sure that the arduino can rest on and activate the spray bottle.
3. Fill the outer area of the base with Tree of Heaven Sap or your preferred Spotted Lanternfly Attractor.
4. Thread the nozzles into the connector and through the outer holes of your choice.
5. Twist the lid onto the base and hang where desired.
 
### Success Criteria

The goal of our project is to effectively deter and eliminate 75% of Spotted Lanternflies within a vineyard before they reach the harvesters. Our product is a Tree of Heaven trick that attracts the flies with Tree of Heaven sap and through motion sensors sprays them with a damaging mixture. With our first functional prototype, we aimed to validate the core systems: motion detection, actuation, fluid delivery, and structural design, against measurable success criteria that directly support this goal.

1. Motion Sensor Reliability
   Assessed: The ability of the system to consistently detect Spotted Lanternflies as they land..
   Measurement: Percentage of successful sensor detections that trigger an LED light at a fixed distance (~6 inches).
   Target: ≥75% detection success rate.
   Result from testing: Achieved ~100% success rate across four sensors.
   Relevance to goal: Reliable detection is critical to ensuring flies are targeted before reaching crops.
2. Servo Activation 
   Assessed: If detected motion can successfully trigger the servo motor and spray mechanism.
   Measurement: Percentage of motion detections that result in correct servo actuation.
   Target: ≥75% successful actuation.
   Result from testing: ~50% success rate (limited by coding errors).
   Relevance to goal: This directly determines whether detected flies can actually be sprayed and eliminated.
3. Spray System Effectiveness 
   Assessed: Ability of the system to deliver pressurized liquid through multiple nozzles simultaneously.
   Measurement: Number of nozzles (target = 4) that can be supplied with sufficient pressure and coverage distance (~5 inches).
   Target: Functional delivery to all 4 nozzles at usable pressure.
   Result from testing: System functional, but insufficient pressure and setup for 4 nozzles simultaneously.
   Relevance to goal: Effective spray coverage is necessary to ensure flies are hit and eliminated.
4. Structural Integrity and Manufacturability 
   Assessed: Whether the housing can be accurately printed, assembled, and support system components.
   Measurement: Dimensional accuracy (fit of parts), successful assembly, and absence of structural defects.
   Target: Fully assembled prototype with precise component fit.
   Result from testing: Individual parts printed accurately with full assembly in the future.
   Relevance to goal: A durable and scalable housing is necessary for real vineyard usage..

For our live demonstration, we identified the detection-to-spray response as the most critical to show, as it validates our full system performance. By simulating Spotted Lanternflies, we hope to show a ≥75% success rate of identifying and accurately dousing any motion during the live demonstration.

## Client Report 

### Introduction:
Spotted lanternflies (SLF) are invasive insects that feed on plants and agricultural crops. They cause significant damage to native ecosystems and the US agriculture industry. SLF have a one-year life cycle, with egg masses being laid during fall and hatching during spring. Our goal for this project was to design a tool that aids local vineyards in managing SLF populations.

We ultimately decided to target SLF in their adult stage of life due to minimal knowledge of instar stages and challenges associated with targeting egg masses. Our primary goal was to design a system that would attract SLF and eliminate 75% of them within a 5-inch radius. 

### Final Prototype and Application:

<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/fig1.png" alt="Fig 1" width="500">

Figure 1: Assembled Prototype

Our final design is a lightweight device that attracts SLF before immobilizing them with a combination of adhesives and a directed spray. It leverages sap from the Tree of Heaven as the attraction mechanism. Upon approach, the insects are detected by an infrared sensor, triggering an actuation mechanism that releases a spray of organic soap and water mixture, rapidly immobilizing the SLF without damaging nearby plants. The spray can be replaced as desired. Additionally, the outer housing contains adhesive flypaper that captures insects approaching from outside the effective range. 

The device was designed with the intent of being scalable. Individual units can be mounted to a variety of locations, and once mounted, are largely autonomous. While the prototype currently runs off disposable batteries, a final product would ideally run off solar power. Each unit provides approximately 180 degrees of coverage, but multiple units can be strategically arranged to maximize coverage and performance.

<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/fig2fig3.png" alt="Fig 2" width="500">

Figures 2 & 3: Full View and Cross Section of prototype

### Testing and Results:
To evaluate our prototype’s performance, we tested the spray range, IR sensor detection range, and strength of the adhesive paper. 

<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/irdata.png" alt="IR data" width="500">

We assessed the IR sensor performance by measuring the detection rate as a function of angle. Experimental observations showed an effective FOV of approximately 120–140 degrees, with accuracy decreasing towards the edges. As a result, we included two sensors into the design to increase reliability.
<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/fly-paper.png" alt="fly paper data" width="500">

Finally, we tested the adhesive paper to determine its strength. Our results show that the flypaper is easily capable of retaining a lanternfly-sized object. The adhesive remained effective under moderate loading conditions, though overcrowding reduced marginal capture efficiency due to decreased sticking area. Overall, the flypaper is robust, reliably capturing insects missed by the spray.
At the system level, overall efficiency was evaluated by introducing a controlled number of objects and recording the proportion successfully detected and immobilized. The prototype achieved an average effectiveness of approximately 75% within the intended operating region, achieving our target specified in the problem statement. This discrepancy was primarily attributed to the limited spray radius and partial sensor coverage, which allowed some targets to pass through undetected or unsprayed.

### Prototype Details: 
Our initial full-scale functional prototype was designed as a branch-mounted, modular trapping system intended to provide 360° coverage of the surrounding area.

<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/fig4fig5fig6.png" alt="Overall View" width="600">

Figures 4, 5, 6: (Left to Right) Overall View; Body View with Spray Can and Nozzles; Lid View

A central feature of this design was a custom four-way nozzle intended to distribute spray evenly in all directions. This configuration was selected to improve the likelihood of SLF contact regardless of approach angle. However, during implementation, compatibility issues were identified between the custom nozzle design and the commercially available spray canisters, specifically related to pressure delivery and nozzle interface geometry. These constraints prevented the successful integration of the multi-directional spray system in the current iteration.
Despite these challenges, further investigation into alternative nozzle geometries, pressurized delivery systems, and adapter mechanisms suggests that a fully functional 360-degree spray configuration remains technically feasible. With appropriate redesign of the pressure regulation and nozzle coupling system, the original concept could be realized in a future iteration of the prototype, potentially improving overall capture efficiency and reducing reliance on auxiliary trapping components.

### Conclusion and Recommendation: 
After spending the semester designing and testing our system, we believe that our prototype has potential, but would benefit from further refinement. The primary limitation is the spraying mechanism, as our initial design specified a system capable of distributing fluid through multiple nozzles. Due to our time constraints, we chose to alter our housing to work with our original spraying mechanism, which can achieve a radius of about 10 inches. While this configuration could potentially work, the limitations of the spray required the addition of adhesive surfaces to achieve our desired efficiency. Further developments should prioritize a pressurized delivery system combined with multiple nozzles to enable 360-degree coverage.

### Bill of Materials:
<img src="https://cornell-mae-ug.github.io/sp26-portfolio-cwk66/assets/images/bom.png" alt="BOM" width="200">