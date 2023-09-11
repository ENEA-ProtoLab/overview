# Summary
A collection of tutorials/templates developed as part of M4_Spoke3_Deliverable_D3.3.5_ECOSISTER (PNRR) research project on "Development of generative processing strategies for the breakdown of product characteristics and possible redesign and recovery actions". 

The activity focused on enhancing understanding of the tools and acquiring skills through algorithm scripting using Computatational Design tools like Grasshopper and its plug-ins. These step-by-step tutorials were designed for specific courses, summer schools, or industrial training programs. These tools developed want to help in sharing knowledge and saving resources, hopefully driving economic growth. 

Rhinoceros 3D was chosen due to its ability to provide a seamless and continuous workflow, thanks to its wide range of open-source tools that facilitate transversal applications. This way enables a smooth process without any interruptions after the design phase, giving the opportunity to directly integrate Topology Optimization (TO) and Lattice Structures (LS) processes, eliminating the necessity of model redefinition or conversion. 

The templates are largely based on vanilla-GH, but a few plug-ins were also used: Crystallon; Weaverbird; Alpaca4D; Dendro; MeshEdit; Ngon.

*The GH files are free to downoad after asking to become a member.*

## Templates
1.	*Application of a Uniform LS in an Enclosed Volume:*
This workflow involves applying a uniform LS within an enclosed volume. The LS is then trimmed using the referenced boundary volume, and thickening is driven by an attractor point field. The advantages of this approach include efficient material distribution, lightweight design, and adaptability to different boundary conditions.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/c53138c4-b5e6-477e-8d75-9c68e703e012)


2.	*Conformal LS between Surfaces:*
This workflow achieves a conformal LS between surfaces or meshes through graph curve manipulation. This manipulation allows for a more conformal voxelization of the reference geometries. The advantages of this approach include improved surface adaptation, enhanced structural integrity, and the ability to create LS with intricate connections.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/0f571284-0693-4505-b951-e2f0b396810a)


3.	*Strategy for Modifying or Morphing Voxel LS:*
This LS workflow focuses on modifying or morphing an LS based on specific values assigned to each cell unit. The same data can drive thickening or mesh color by remapping the values within a user-defined domain. The advantages of this strategy lie in its flexibility, allowing for customized LS designs based on specific performance criteria, and the ability to achieve desired structural characteristics.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/391a2430-d500-43b9-88c1-abd0492bb0d6)


4.	*Offsetting Surface (or Mesh) Based on Data Values:*
This workflow involves offsetting a surface or mesh based on data values such as curvature analysis or mesh color mapping. The same data can drive thickening or mesh color by remapping the values within a user-defined domain. The advantages of this approach include the ability to create intricate and variable LS geometries, adaptability to complex geometries, and improved structural performance.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/e523be10-cab8-4d2d-beff-73cecf5cf965)


5.	*Transition (or Morphing) Strategy between Heterogenous LS Unit Cell Beam Configurations:*
This workflow focuses on transitioning or morphing between two different LS unit cell configurations. The transition can occur in a type-by-type fashion, such as from beam to beam or shell to shell. The morphing values can be provided by an attractor point field or any general analysis scalar field. The advantages of this approach include achieving smooth transitions between different LS configurations, flexibility in creating LS with varied mechanical properties, and improved structural performance.
In this case, the morphing is between a Body Centered and Body Centered Cubic configuration.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/668f8100-0bea-4804-b31f-58b250a54aec) ![image](https://github.com/ENEA-protolab/overview/assets/144337113/53ba5e29-01c1-4c17-bace-4cd08311915f)


6.	*Transition (or Morphing) Strategy between Heterogenous LS Unit Cell Shell Configurations:*
This workflow focuses on transitioning or morphing between two different LS unit cell configurations. The transition can occur in a type-by-type fashion, such as from beam to beam or shell to shell. The morphing values can be provided by an attractor point field or any general analysis scalar field. The advantages of this approach include achieving smooth transitions between different LS configurations, flexibility in creating LS with varied mechanical properties, and improved structural performance.
In this case, the morphing is between a Schwartz Primitive with different isovalue (t) configuration.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/437cf46d-e6d3-40e0-9b2b-932fee26df5f)


7.	*General Procedure for Generating a Skin Structure and Merging with the Inner LS:*
This workflow involves generating a skin structure from meshes and connecting it with the inner LS. The original LS can be morphed to reach the skin according to a user-defined distance, or a transitioning LS can be realized between the skin and the inner structure. The advantages of this workflow include improved structural integration, enhanced aesthetics, and the ability to create LS with complex outer appearances.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/8d232bff-18b2-4d0a-8bca-91651438ce01)


8.	*FEA Analysis of a Cube under General Stress (for Beam LS):*
This workflow utilizes FEA to analyze a cube under general stress. The analysis provides valuable information to inform specific geometry features such as LS thickness or mesh color. The advantages of this approach include precise stress analysis, a better understanding of load distribution, and the ability to optimize LS based on stress results.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/bc65744d-882f-48b7-a322-732420f88b8d)


9.	*FEA Analysis of a Cube under General Stress (for Shell LS):*
This workflow utilizes FEA to analyze a cube under general stress. The analysis provides valuable information to inform specific geometry features such as LS thickness or mesh color. The advantages of this approach include precise stress analysis, a better understanding of load distribution, and the ability to optimize LS based on stress results. In this case, it was applied a shell LS (Gyroid) as a mesh input.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/251c60cf-fcfd-413d-8147-565582d8704c)

10.	*FEA Analysis with Isosurface Representation:*
This workflow employs FEA to analyze a cube under general stress. The brick elements representing voxels are used to populate the LS, and an isosurface representation is applied to inform each unit cell with a Triply Periodic Minimal Surface (TPMS) according to its mathematical formula. This workflow allows for the creation of conformal LS with shell unit cells. The advantages include achieving intricate geometries inspired by mathematical surfaces, improved structural performance, and aesthetic appeal.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/644777d8-3924-4364-8b92-bfbaf32b2758)


11.	*Surface Conformal Ribs LS:*
This workflow provides an adaptable strategy for generating ribs conformal to any surface. First, it’s necessary to find the curves on which build the ribs. These curves are then used to guide the construction of the voxel. The voxelization process itself can be conformable to the curve employing a graph mapper to manually distribuite the voxels. After, the voxels are populated with a LS, which is then thickened. It was necessary to edit one Crystallon’s component to function with n curves. Also, particular attention was given in how to link and merge the LS of the ribs with the LS of the skin: through a distance range it’s possible to morph the closest nodes of the ribs LS to the merge it with the skin.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/36c58462-e45f-4e55-ab45-3cbf18385b16) ![image](https://github.com/ENEA-protolab/overview/assets/144337113/9aca372c-3f7c-45e8-9fbf-737dd51537f2)


12.	*Stochastic LS:*
Stochastic LS are used often to lightweighting and infill purposes, as they don’t provide a particularly rigid structure. In particular, the Voronoi algorithm provides a simple and efficient space-filling topological structure. In the workflow are present also solution to trim and clean the final LS in order to conform it to a specific shape. As the computational load for calculating the Voronoi algorithm can be heavy, a novel solution to thicken the final LS is provided through Dendro’s plugin. In fact, with Dendro is possible to use implicit modelling tools (and SDF) to quickly generate a thickened mesh (even with various thickness according to points field attraction).

![image](https://github.com/ENEA-protolab/overview/assets/144337113/43e4ca61-6512-411b-81e7-1c4900683cbb)


13.	*Stochastic LS with Design Constrains:*
In this workflow some design constraints are added in the context of generating a LS. Specifically two points acts as a placeholder for fastener applications (housing for a screw or a bolt). Thanks to implicit modelling (with Dendro’s pluglin) is possible to take in consideration the volume occupied by the housing and subtract it from the LS. Implicit modelling in this case can have a way faster calculation then classic brep Boolean operations.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/9a76ac6d-22a9-4d0e-9582-73018da665df)


14.	*Shell LS Configuration and Area Optimization with Evolutionary Algorithm:*
As a lot of cases have been addressed, it’s now possible to start refining the LS. Starting from values obtained by a previous FEA, the aim is to identify the most advantageous configuration for the LS, particularly which shell structures optimized for area efficiency. In GH, with Galapagos is possible to implement an Evolutionary that allows for a systematic exploration of a diverse range of shell configurations.  By subjecting numerous shell configurations to Galapagos, the algorithm determines the configuration that exhibits the least surface area. The selected design will represent an efficient and robust LS, achieving the minimum surface area and material utilization. An ulterior optimization using the same logic could be to find the minimum thickness according to a novel FEA, but starting from the best configuration found for minimum surface area.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/499575e7-e271-41f8-a88d-455acf8775f2)


15.	*Beam LS Optimization with Multi-Goal Evolutionary Algorithm:*
With beam, too, it’s possible to start refining the LS. Starting from values obtained by a previous VbFEA is possible to choose between the best configuration with the best structure. As Galapagos can only manage one goal, the Octopus’s plugin is implemented. In fact, with Octopus is possible to set one or multi-objective goals. So, to displacement goal, this time, it’s possible to add also a mass goal. By analysing different beam configurations using Octopus, the algorithm systematically determines which arrangement offers the most robust and stable structure with the least amount of displacement by minor mass. It's essential to note that as it explores various beam configurations with Octopus, a novel FEA needs to perform again for each configuration (by Alpaca4d). For this case, it’s possible to use a different kind of element to discretize the LS: each truss composing the LS can be represented by a “beam element” and run a more classic FEA.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/aaa8db11-570c-403d-8d38-c0a2e0f484a8)


## Classification
Each tutorial can also be categorized according to which product characteristics is to breakdown using three key criteria: Weight-Critical, Structural Complexity, and Adaptive Performance.

*A.*	**Weight-Critical**: these tutorials/templates are focused on optimizing the LS to minimize the overall weight of the product while ensuring it maintains its structural integrity and performance. The goal of these strategies is to efficiently distribute materials, create lightweight designs and products that are more resource efficient. Tutorials 1, 2, 7, 11, 12. 

*B.*	**Structural Complexity**: these strategies involve designing intricate and adaptable lattice structures that can effectively handle different load and stress conditions. The integration of FEA simulations ensures that products can withstand complex structural demands. Achieving TO structural complexity allows for enhanced structural integrity and adaptability to various structural scenarios. Tutorials 8, 9, 10, 15.

*C.*	**Adaptive Performance**: these procedures take in consideration the necessity to adapt the LS within design constraints. By incorporating techniques that redefine the LS based on specific data values, explore different unit cell configurations, and conform to the design space provided, products can integrate LS with different characteristics within the geometry, offering improved structural integration and customization to meet specific performance criteria. Tutorials 3, 4, 5, 6, 13, 14.
