# Interactive-mechanics-Development-
This repository features technical dev showcase of interactions and gameplay mechanics for spatial immersive cubic space. Set of games developed with Unreal Engine and Touch Designer.   

> This repository documents the interactive mechanics and technical design.  
> The **primary goal** of this repo is to showcase the technical and interactive mechanics, featurimg the role of developer.
> [![LinkedIn][linkedin-shield]][linkedin-url]


## Demo (Short)
![Demo](media/gifs/Demo.gif)


## Development of Core System 
1. Players Tracking & Data Mapping
 
Real-time position and orientation data is captured for each player. Then processed and normalized in selected game engine.
Developed in a a way that each player receives a persistent ID that remains consistent across the entire show.

2. Interaction Logic Framework inside Game Engine 
 - Individual player tracking data
 - Proccesed Average position of all players - developed into 3 main navigation principles, that applies to different gameplays

This framework allows:
- One-player mechanics
- Multi-player cooperative behaviors
- Global environment state changes
- Adaptive difficulty based on group dynamic
**Developed Framework is a core to create various interactive mechanics.**

3. In Unreal Engine Tecnical architecture builded to keep core development structure modular or same across games.If there is a change in master project it waill aplly to any other developed game gameproject. 
- Master components / Controls
- Game Mechanic Components


4. SHOW RUNN
   -With nDisplay outputing content in 4K resolution to test space. Reached FPS 50-60 on one RTX 4090.

  ## Technical Art for spatial gaming and previsualizations
Development of spatial games in Unreal Engine requries RnD of the technical art as well, working with the shader, finding out a solutions that will work for Spatial immersive enviropment.
- Shader that work with the interaction logic
- Materials, VFX that works and looks cool with nDisaplay rendering
- Combinig with position ddata and blueprit coding
 
### Developed toolset in Unreal Engine for immersive scene previsualization
![Projection Tec Art](media/gifs/IntroTechart.gif)
   
## Higlighted dev mechanics
RnD of navigation principles
RnD of the core game mechanics 
Metasound and chain reaction to make a drummachine
real time vertex paint and shader dev

## Key Mechanics
### Mechanic 1 — *Name*
- Why this mechanic exists
- How it works (short)
- Parameters that matter

*(GIF placeholder)*

### Mechanic 2 — **
*(Same structure)*

## Touch Designer
I defined which gaming experience should be build in which engine from the optimization and performance perspective,
A few interactive experiences build in the Touch Designer using Python to write a logic. (appears it is the best approach) 
| File | Description |
|------|-------------|
| `samples/touchdesigner/ExampleModule.tox` | Self-contained example (to be added). |



## Tech Stack
- TouchDesigner (version)
- Controllers / Sensory input (if any)
- OS / Hardware notes

## Credits
Your Name • Year
