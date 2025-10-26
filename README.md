# Interactive-mechanics-Development-
This repository features technical documentation and showcase of development of interactions and gameplay mechanics for spatial immersive cubic space. Set of games developed with Unreal Engine and Touch Designer.   

> This repository documents the interactive mechanics and technical design behind the project.  
> The **primary goal** of this repo is to showcase the technical and interactive mechanics, not to publish full source code.


## Demo (Short)
![Demo](meida/gifs/IntroTechart.gif)


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

3. In Unreal Engine Tecnical architecture build to keep core development structure for all games
- Master components / Controls
- Game Mechanic Components
With Plastic SCM we developed a workflow where we start to work with Master Project that has fundamental components for various game mechanics. IN this way if some of the main components chanee it changes across every other project

4. SHOW RUNNER
   -With nDisplay outputing content in 4K resolution to test space. Reached FPS 50-60 on one RTX 4090. 
   

## Key Mechanics
### Mechanic 1 — *Name*
- Why this mechanic exists
- How it works (short)
- Parameters that matter

*(GIF placeholder)*

### Mechanic 2 — **
*(Same structure)*

## Samples
| File | Description |
|------|-------------|
| `samples/touchdesigner/ExampleModule.tox` | Self-contained example (to be added). |

## Tech Stack
- TouchDesigner (version)
- Controllers / Sensory input (if any)
- OS / Hardware notes

## Credits
Your Name • Year
