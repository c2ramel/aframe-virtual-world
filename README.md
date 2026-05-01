# Project: Transforming "Stopping by Woods on a Snowy Evening" into an Interactive 3D Visualization

## Overview
This project is an interactive 3D virtual environment built using **A-Frame (WebVR)** for the *Virtual World Design and Research* course at National Cheng Kung University. 

Our team has re-imagined Robert Frost’s 1923 poem, **"Stopping by Woods on a Snowy Evening,"** as an immersive virtual world. 

## The Team
*   **[Member 1 Name]** - Role / Collaboration
*   **[Member 2 Name]** - Role / Collaboration
*   **[Member 3 Name]** - Role / Collaboration
*   **[Member 4 Name]** - Role / Collaboration

## How to Run the Project
To ensure all 3D models and textures load correctly, the project must be served through a local server.

1.  **Clone the Repository:**
    
```bash
git clone https://github.com/c2ramel/aframe-virtual-world.git
```
2.  **Open in VS Code:** Open the project folder in Visual Studio Code.
3.  **Launch Live Server:** 
    *   Ensure the **Live Server** extension is installed.
    *   Right-click `scene1.html` and select **"Open with Live Server"**.
    *   The world will launch at `http://127.0.0.1:5500/scene1.html`.

## Interaction & Controls
*   **Movement:** Use the **W, A, S, D** keys to walk through the snowy forest.
*   **Perspective:** **Click and drag** the mouse to look around at the woods and the frozen lake.
*   **Navigation Guide:** Follow the path to find the "promises" hidden within the scene.

## Deliverables
- [ ] **Scene Files:** Complete HTML and GLB/GLTF assets.
- [ ] **Report:** 2-page PDF including team details, scene screenshots, and poem interpretation.
- [ ] **Walkthrough:** 90-second video demonstrating the interactive atmosphere.

## Original Poem Reference
*   **Title:** Stopping by Woods on a Snowy Evening (1923)
*   **Author:** Robert Frost
*   **Source:** [Poem Foundation - Stopping by Woods on a Snowy Evening](https://www.poetryfoundation.org/poems/42891/stopping-by-woods-on-a-snowy-evening)

## Recommended File Structure
```
aframe-virtual-world/
├── assets/                                  # Sub-folder for all media
│   ├── forest_model.glb                     # 3D forest assets
│   ├── cabin.gltf                           # 3D structure assets
│   └── snow_texture.jpg                     # Image for sky or ground
├── scene1.html                              # Main A-Frame code
├── README.md                                # GitHub documentation
├── README.txt                               # Initial project notes
├── A-Frame_Tutorial_1_Basics.pdf            # Reference material
├── A-Frame_Tutorial_2_Adding 3D Models.pdf  # Reference material
└── deliverables/                            # Folder for final submission items
    ├── Project_Report.pdf                   # 2-page design report
    └── Walkthrough_Video.mp4                # 90-second screen capture
```
