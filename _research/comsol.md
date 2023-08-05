---
title: "COMSOL"
layout: single-portfolio
excerpt: "<img src='/images/research/comsol_nanopore_ep.png' alt=''>"
collection: research
order_number: 40
header: 
  og_image: "research/comsol_nanopore_ep.png"
---

Finite Element Analysis (FEA) is a computational method used in microfluidics and electrokinetic biosensor research to analyze and simulate the behavior of fluids, electric fields, and particles at the microscale level. It involves dividing complex geometries into smaller, finite elements, allowing for accurate modeling and prediction of fluid flow, electrokinetic phenomena, and particle transport within microfluidic devices and electrokinetic biosensors.

In microfluidics, FEA helps in understanding fluid behavior, such as pressure distribution, velocity profiles, and mixing efficiency, within intricate channel networks. It enables researchers to optimize device designs, predict flow patterns, and evaluate the performance of various microfluidic components, such as valves, pumps, and mixers. FEA also aids in studying phenomena like droplet formation, particle trapping, and droplet merging, providing insights for the development of advanced lab-on-a-chip systems.

Regarding electrokinetic biosensors, FEA assists in simulating electric fields, ion concentration distributions, and the movement of charged particles within microchannels. It enables the analysis of electroosmotic flow, electrophoresis, dielectrophoresis, and other electrokinetic phenomena relevant to biosensing applications. By utilizing FEA, researchers can optimize electrode geometries, electrode configurations, and operational parameters to enhance the sensitivity, selectivity, and overall performance of electrokinetic biosensors.

## Analysis of fluid performance of micromixer with and without obstacles inside of microchannel

> In the field of mechanics, a micromixer is a device that utilizes mechanical microparts to mix fluids. This technology holds significant importance in various industries, such as the chemical and pharmaceutical sectors, analytical chemistry, biochemical analysis, and high-throughput synthesis. The micromixer takes advantage of fluid miniaturization to reduce the quantities involved in chemical and/or biochemical processes, making it a key tool in these applications.

The term "micromixing" is commonly used to describe the level of mixing on a molecular scale. The time taken to achieve homogeneity becomes crucial in systems where the micromixing time is comparable to or longer than the characteristic time constant of the reaction. In such cases, mixing and reaction occur simultaneously rather than sequentially, leading to potential throttling of reactions due to insufficient mixing. Several examples of reactions that rely on molecular-level homogeneity include competitive consecutive reactions, Michaelis-Menten type reactions, autocatalytic reactions, and polymerizations. In these scenarios, achieving effective mixing becomes vital for the success of the reaction processes.

In the passive micromixer, obstacles were strategically positioned inside the microchannel to interrupt the flow and minimize the diffusion path. This disruption of the flow velocity field causes the flow direction to interact with another fluid, resulting in convection that significantly enhances the mixing process. Model 1 was designed as three-dimensional rectangle straight channel with 1000 µm* 200 µm* 50 µm in Width, Length and Hight.  Model 2 was designed based on model 1 but incorporated six circle-shaped obstacles symmetrically placed at the center of the channel. A comparison with a straight channel revealed that the mixing efficiency was significantly improved, even with species possessing the same diffusion coefficient. Fig. b demonstrates that the two fluid flows required a longer distance to achieve uniform mixing. Notably, the simulation results  revealed fluid velocity constrictions around the circular obstacles, highlighted in red color. These constrictions arose as the fluid encountered the obstacles, resulting in the highest speeds. In this well-designed configuration, the two fluid flows from separate inlets were skillfully diverted to the sides of the channel, effectively preventing the diffusion of the two species as they encountered the obstacles.

### Concentration and velocity profiles of two passive micromixers: without/with obstacles;
<img src='/images/research/comsol_mixer.png' alt=''>


## Analysis of fluid flow in Nanopore sensing

> Finite Element Analysis (FEA) presents significant benefits in nanopore biosensor design and optimization. It involves dividing complex structures like nanopores into smaller, manageable elements to simulate their behavior under different conditions. In nanopore biosensor development, FEA provides crucial insights into fluid flow patterns, electric field distribution, and molecular interactions within the nanopore system. A key advantage of FEA is its capacity to predict and visualize nanopore behavior in real-world scenarios, a challenge for experimental methods alone. This predictive ability allows researchers to optimize design parameters and material properties, enhancing sensor performance. FEA also enables rapid prototyping and iterative design improvements without time-consuming and expensive experiments. Moreover, FEA simulates the nanopore response to various analytes, aiding in the creation of highly sensitive and selective biosensors. 

### Fluid flow pattern for a 1 μm diameter pore in the near tip region with applied a -30V and b +30 V at the base in 1 mM KCl solution
<img src='/images/research/NANOPORE_COMSOL.png' alt=''>


## Analysis of electric field distribution in electrochemical impedance spectroscopy (EIS) sensing platform

> Analyzing the electric field distribution in an electrochemical impedance spectroscopy (EIS) sensing platform offers several key advantages. EIS is a powerful technique used to study the electrical properties of electrochemical systems. By analyzing the electric field distribution, researchers can gain insights into the interactions between analytes and electrodes. Understanding the spatial distribution of the electric field provides valuable information about the kinetics and mechanisms of the electrochemical processes occurring at the electrode surface. This knowledge is crucial for optimizing sensor performance and sensitivity. Additionally, studying the electric field distribution helps in the design and modification of electrodes to enhance the sensor's detection capabilities. It enables researchers to identify areas of high sensitivity and target specific regions for enhanced analyte capture and detection. By fine-tuning the electric field distribution, researchers can achieve improved selectivity and sensitivity in EIS sensing platforms.

### 2D cross-section simulation of electric field distribution of IDEs at (i) 15 μm; (ii) 30 μm; (iii) 50 μm;
<img src='/images/research/different IDE.png' alt=''>

