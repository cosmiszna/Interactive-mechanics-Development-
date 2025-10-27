<h1>Interactive Mechanics Development </h1>

This repository features technical dev showcase of interactions and gameplay mechanics for spatial immersive cubic space. Set of games developed with Unreal Engine and Touch Designer.   

> This repository documents the interactive mechanics and technical design.  
> The **primary goal** of this repo is to showcase the technical and interactive mechanics, featuring the role of developer.



[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/diana-bohutska-4a0663206/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000?logo=vercel&logoColor=white)](https://readymag.website/u3945815658/4699220/)
[![Gmail](https://img.shields.io/badge/Email-Me-red?style=flat&logo=gmail&logoColor=white)](mailto:dboh.contact@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=Instagram&logoColor=white)](https://www.instagram.com/64xram/)


• I developed and implemented real-time interactive pipelines in Unreal Engine and TouchDesigner, integrating tracking systems and sensor data to achieve stable, low-latency interaction behavior.

• Optimize rendering workflows for real-time output, including material logic, shader behavior, lighting systems, performance budgets.

• Collaborate with creative and technical directors to translate artistic concepts into interactive gaming system.

## Demo (Short)
<p align="center">
  <img src="media/gifs/Demo.gif" alt="Demo" />
</p>

### Development of Core System 
1. Players Tracking & Data Mapping
 
Real-time position and orientation data is captured for each player. Then processed and normalized inside selected game engine.
Each player is assigned a persistent ID that remains stable throughout the entire experience (no ID switching or resets), ensuring consistent interaction logic.

2. Tracking data proceedes in Game engine and developed into two primary Interaction layers:
     - Individual player tracking data (position, orientation, movement states)
   - Proccesed Average position of all players - developed into main navigation principles that enables different gameplay modes.

This framework allows:
    - One-player mechanics
    - Multi-player cooperative behaviors
    - Global environment state changes
    - Adaptive difficulty based on group dynamic
**Developed Framework functions as a core for building diverse interactive mechanics.**

3. In Unreal Engine Tecnical architecture builded to keep core development structure modular and shared across all game variations. Any updates made in the master project propagate automatically to all derived game projects. 
    - Master components / Controls
    - Game Mechanic Components
      
      This ensures consistency, reduces duplication.


4. SHOW RUNN
   -The system was deployed using nDisplay, outputting content in 4K resolution for the installation test environment

  ## Technical Art for spatial gaming and previsualizations
Development of spatial games in Unreal Engine requries RnD of the technical art as well, working with the shader, finding out a solutions that will work for Spatial immersive enviropment.
- Shader that work with the interaction logic
- Materials, VFX that works and looks cool with nDisaplay rendering
- Combinig with position data and blueprint coding
 
### Developed toolset in Unreal Engine for immersive scene previsualization
<p align="center">
  <img src="media/gifs/IntroTechart.gif" width="450" />

  For previsualizations I  worked with the various CG pipelines including animation, shaders in UE, rendering.
   
## Higlighted dev mechanics

    -RnD of the core game mechanics 
    -RnD of the navigation principles
<p align="center">
  <img src="media/gifs/nvnso.gif" width="320" />
  <img src="media/gifs/NVNdg.gif" width="320" />
</p>

<p align="center">
  <img src="media/gifs/nvmcp1sp.gif" width="320" />
  <img src="media/gifs/nvmcp2dg.gif" width="320" />
</p>

    -Real time vertex paint and shader dev

  <p align="center">
  <img src="media/gifs/mechanics_3.gif" width="320" />
  <img src="media/gifs/mechanics_8.gif" width="320" />
</p>


## Touch Designer
One of the important task in the development was to define which gaming experience should be build in which engine from the optimization and performance perspective,
A few interactive experiences build in the Touch Designer using Python to write gaming logic. (appears it is the best approach) 

## Tech Stack
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-000000?logo=unrealengine&logoColor=white)



## Avarness
This content is not intended for public release.
Use or share only if you received the link directly from the author of this repository.
## Credits
Diana Bohutska • 2025
