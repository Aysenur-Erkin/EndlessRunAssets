# EndlessRunAssets 🚀

A plug-and-play **Unity asset pack** for quickly prototyping an endless-runner game.  
---

## Directory Overview

* **Assets/Scenes** — `Demo.unity`, `MainMenu.unity`  
* **Assets/Prefabs** — Player, obstacles, background elements  
* **Assets/Scripts** — `PlayerController.cs`, `ObstacleSpawner.cs`, `GameManager.cs`, utilities  
* **Assets/Sprites** — Tileable ground, background layers, icons  
* **Assets/Audio** — SFX (`jump`, `coin`, `hit`) and BGM loop  
* **Assets/Animations** — Animator controllers & clips  
* **Assets/Fonts / Materials / UI** — HUD fonts, materials, canvas prefabs  
---

## Prerequisites
* Unity Hub + Unity  
---

## Installation

1. **Clone** the repository  
       
       git clone https://github.com/Aysenur-Erkin/EndlessRunAssets.git
       
2. **Open** the project in Unity Hub ( Open → select the cloned folder ).  
3. After import finishes, load **Assets/Scenes/Demo.unity**.  
4. Press **Play**:  
   * ← / → or **A / D** – move  
   * **Space** – jump  

---

## Usage & Customization

| Action                     | Where to change it                              |
| -------------------------- | ----------------------------------------------- |
| Runner base speed          | `GameManager` prefab  →  **Base Speed** field   |
| Character artwork          | Replace sprite on **Player** prefab             |
| Add a new obstacle         | Duplicate an existing obstacle prefab           |
| Spawn rate & gap distance  | Public fields in **ObstacleSpawner.cs**         |


