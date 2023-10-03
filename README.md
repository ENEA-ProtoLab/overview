# Summary
A collection of tutorials/templates developed as part of M4_Spoke3_Deliverable_D3.3.5_ECOSISTER (PNRR) research project on "Development of generative processing strategies for the breakdown of product characteristics and possible redesign and recovery actions". 

The activity focused on enhancing understanding of the tools and acquiring skills through algorithm scripting using Computatational Design tools like Grasshopper and its plug-ins. These step-by-step tutorials were designed for specific courses, summer schools, or industrial training programs. These tools developed want to help in sharing knowledge and saving resources, hopefully driving economic growth. 

Rhinoceros 3D was chosen due to its ability to provide a seamless and continuous workflow, thanks to its wide range of open-source tools that facilitate transversal applications. This way enables a smooth process without any interruptions after the design phase, giving the opportunity to directly integrate Topology Optimization (TO) and Lattice Structures (LS) processes, eliminating the necessity of model redefinition or conversion. 

The templates are largely based on vanilla-GH, but a few plug-ins were also used: [Crystallon](https://www.food4rhino.com/en/app/crystallon); [Weaverbird](https://www.giuliopiacentino.com/weaverbird/); [Alpaca4D](https://www.food4rhino.com/en/app/alpaca4d-openseesgh); [Dendro](https://www.food4rhino.com/en/app/dendro); [MeshEdit](https://www.food4rhino.com/en/app/meshedit); [Ngon](https://www.food4rhino.com/en/app/ngon); [Octopus](https://www.food4rhino.com/en/app/octopus).


&#x1F536;*The GH files are free to download after asking to become a member.*

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

![image](https://github.com/ENEA-protolab/summery/assets/144337113/3800c78c-7ff3-4514-930b-0c134196a4bc) ![image](https://github.com/ENEA-protolab/summery/assets/144337113/653f6d2e-073f-4d00-8851-26698fc229fb)


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

![image](https://github.com/ENEA-protolab/summery/assets/144337113/ca5aa88f-1063-4434-9f2e-26cbc91cb402) ![image](https://github.com/ENEA-protolab/summery/assets/144337113/ccd4f548-02d6-4d48-ad55-ea215bf2a3a9)


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
With beam, too, it’s possible to start refining the LS. Starting from values obtained by a previous FEA is possible to choose between the best configuration with the best structure. As Galapagos can only manage one goal, the Octopus’s plugin is implemented. In fact, with Octopus is possible to set one or multi-objective goals. So, to displacement goal, this time, it’s possible to add also a mass goal. By analysing different beam configurations using Octopus, the algorithm systematically determines which arrangement offers the most robust and stable structure with the least amount of displacement by minor mass. It's essential to note that as it explores various beam configurations with Octopus, a novel FEA needs to perform again for each configuration (Alpaca4d). For this case, it’s possible to use a different kind of element to discretize the LS: each truss composing the LS can be represented by a “beam element” and another FEA.

![image](https://github.com/ENEA-protolab/overview/assets/144337113/aaa8db11-570c-403d-8d38-c0a2e0f484a8)


## Classification
Each tutorial can also be categorized according to which product characteristics is to breakdown using three key criteria: Weight-Critical, Structural Complexity, and Adaptive Performance.

*A.*	**Weight-Critical**: these tutorials/templates are focused on optimizing the LS to minimize the overall weight of the product while ensuring it maintains its structural integrity and performance. The goal of these strategies is to efficiently distribute materials, create lightweight designs and products that are more resource efficient. Tutorials 1, 2, 7, 11, 12.

*B.*	**Structural Complexity**: these strategies involve designing intricate and adaptable lattice structures that can effectively handle different load and stress conditions. The integration of FEA simulations ensures that products can withstand complex structural demands. Achieving TO structural complexity allows for enhanced structural integrity and adaptability to various structural scenarios. Tutorials 8, 9, 10, 15.

*C.*	**Adaptive Performance**: these procedures take in consideration the necessity to adapt the LS within design constraints. By incorporating techniques that redefine the LS based on specific data values, explore different unit cell configurations, and conform to the design space provided, products can integrate LS with different characteristics within the geometry, offering improved structural integration and customization to meet specific performance criteria. Tutorials 3, 4, 5, 6, 13, 14.


## Case study
In order to verify the feasibility of this collection of tutorials, they have been implemented in 5 case studies representing the Consumer Goods sector: for Music Instrument, a chin rest for violin; for Footwear, a high-heeled shoe; for packaging, a necklaces jewelry display; for Eyewear, a pair of sunglasses; for Sports Equipment, a riser for archery. For each of this case studies one or more tutorials according to its criteria and goals (classified as A, B or C, like stated before). As the tutorials provide a general template for each case it was necessary to tweak and customize the script in order to take account of the inputs, the chosen 3Dp technology and also any design constraints. But the general strategy was basically left untouched from the templates.


1.	*Chin rest for violin (A):* in this case the goal was to minimize the material usage, leaving the exterior design untouched. Starting from a 3D scan of an old chin rest, a stochastic LS was applied just to find the most efficient space-filling topological structure while also ensuring a relatively large thickness on account of structural reasons. The final 3D printable mesh is generated by SDF tools (with Dendro) and achieves almost 64% material minimization (from a starting volume of 191460 mm3 to an optimized volume of 7005 mm3).

![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/c862b560-6c1a-4737-ab27-90c44a6aa7fc)
![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/bec7624d-51ec-401d-abbd-74eaff69c9fc)


2.	*High-heeled shoe:* here the goal was to minimize material but also meet specific stress conditions filling the entire volume of the shoe with a shell LS. Also for this case, the input mesh is obtained by a 3D scan of an old sole. To find the stress value, a VbFEA was run (by Alpaca4D), applying a z-force of 588N (around 60kg) to some local points as loads and points touching the ground as supports. For the brick size, and hence the voxel size, a 10x10x10 mm dimension was chosen and PA12 (typical of MJF or SLS 3Dp) as the designated material. After running the FEA, the equivalent stresses for each brick is calculated by the VonMises Stress Equation in order to perform data-driven-design on each of the voxels. By implementing isosurface representation it is possible to inform each voxel with a TPMS (a gyroid) by its mathematical formula. Thickness is then generated by remapping the stress data in a range of values suitable to be 3D printed.

![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/ae9d1306-499c-4f05-950b-8f90a354780d)
![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/7e9463af-ce69-4bcb-a111-bfeb3e2e76dd)


3.	*Necklaces jewelry display:* two versions/scenarios were developed for this case: a mesh input or a NURBS surface input. In both cases the goal was to replace a flatness of the display with an aesthetically appealing LS. Starting from the mesh input, a curvature analysis is performed (with Ngon) to find the absolute curvature values for each vertex of the mesh. The curvature values are then remapped in a range of thickness suitable for 3Dp and used to offset the initial mesh. The space generated is hence filled with unit cells in which a beam LS is deployed. The LS is also complemented by the outer edges of the mesh and two different radii are assigned to the final LS. For the NURBS surface case, instead, it was chosen to add also some curves for design and rigidity purposes. The curves are mapped on the surface and used to generate conformal ribs with gradient features in order to apply a beam LS. The initial surface is remeshed to find a nice trid-shaped skin structure on which the LS is morphed and merged to avoid overlapping problems. An overall radius is assigned to the final LS suitable to the 3Dp technology chosen.

![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/f2046a5e-5c80-4916-b2aa-02a092116806)![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/35b9bdf9-6caf-48c4-b168-0048c30758ce)
![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/5527d841-93f9-410e-a8a9-f1ec74374afb)![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/abee37a9-f6df-47c8-aa58-529b4cd2e4d8)


4.	*Sunglasses:* the sunglasses in this case were already designed to be 3D printed, so the final goal was mostly directed to add aesthetic features but also find which configuration provides the least amount of material. A designated volume is voxelized by 3x3x3 mm unit cells in which a beam configuration is then deployed. To ensure comfort, a skin LS of trid-sphaed meshes is generated for the outer parts of the volume. The two LS are then morphed and merged together. To find which configuration produces the least amount of volume, an evolutionary algorithm with Galapagos is integrated: the algorithm will go through each of the 13 possible configurations trying to minimize the thickness of the LS. The final output shows how some configurations are really close to one another in terms of volume occupied, giving space to possible user-customization while still remaining in a very close range of volumes.

![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/e6d025b6-cf29-4b50-b485-8482a8f2af1f)
![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/4097ea0b-6cd0-46ac-96cb-6355e3182e5a)


5.	*Riser for archery:* the riser itself was reconstructed from a broken one and remeshed in a nice quad-shaped structure. Like for the shoe, also for this case, the goal was to minimize material but also meet specific stress conditions filling the entire volume of the riser with a shell LS for the grip zone and a beam LS for the top limb and the bottom limb, thus splitting the problem in three parts. Stresses are applied as load points with specific vector direction for each part (84N with 15.5° inclination for the top limb, 87N with the same inclination but mirrored for the bottom limb and 178N with a straight direction for the grip). The supports are fixed only for translation displacement, with freedom of rotation as the limbs need to be flexible, and are individuated at specific z-heights (approximately where the parts are divided. As for the shoe, a FEA is run with 10x10x10 mm voxelization, each voxel representing a brick element at which ABS material properties are assigned. Equivalent stresses are calculated by the VonMises Stress Equation, then assigned and separated by each relative voxel. For the two limb part a simple beam LS is deployed giving to each unit cell a specific thickness value. To the internal LS is added a skin LS based on the quad-mesh structure of the parts, with an overall minimal thickness. As for the grip volume, like for the shoe, a shell LS is chosen (gyroid) with variable thickness driven by the remapped stress values. Boolean operation to trim out exceeding LS and join everything together is done by implicit modeling and SDF tools (by Dendro). The final volume achieves almost an 80% reduction of material (from a starting volume of 555211 mm3 to an optimized volume of 110958 mm3).

![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/d9b9ed38-4b6d-4ec4-beba-a9ce741247a5)![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/f7ff6ce6-0d61-464b-9901-c02079727cfb)
![image](https://github.com/ENEA-ProtoLab/overview/assets/144337113/1697acd0-af5d-48d1-bab0-6a32f56c5618)
