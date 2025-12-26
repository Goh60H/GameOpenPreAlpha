# GameOpenPreAlpha

This repository contains a **pre-alpha build** of a turn-based, hex-grid dungeon crawler currently under development.

Download links: 
| Version | Windows | macOS | Linux |
|---------|---------|-------|-------|
| v0.0.2  | - | - | - |
| v0.0.1  | - | [Download](https://drive.google.com/file/d/1GLRfu3dPuhFQxbtAy2nJ7WAKiNeDp__h/view?usp=sharing) | - |

⚠️ **Note:** 

This game has only been tested on Windows, for it is the operating system I use when developing. 

If a version does not work on any operating system, I kindly request to have an e-mail sent to rpgdevcontact@gmail.com. I thank your cooperation in advance.

---

## ▶️ How to Run

1. Download and extract the `.zip` file.
2. Open the extracted folder.
3. Execute `RPG1.exe`.
4. When prompted for network access, you may safely **deny** it — the game does not use any online features.

The game should now be running.

---

## 🕹️ About the Game

The game features **turn-based combat and exploration** in a **procedurally generated dungeon** built on a hexagonal grid.

### Current Features
- Procedurally generated maps
- Turn-based combat
- Two enemy types
- Three playable dungeon levels

Each level currently:
- Shares the same visual ambientation
- Uses the same enemy types

### Level Transitions
- **Green over brown portal** → go to the next level  
- **Red over brown portal** → go to the previous level  

⚠️ **Note:**  
The first level contains a special exit portal, but its functionality has **not yet been implemented**.

### Death & Retry
Upon dying, the player may restart the game on a **newly generated map**, facing the same enemy types as before.

---

## 🎮 Controls

- **Left Click**: Select a hexagon to choose movement direction
- **1, 2, 3, 4**: Use abilities (see below)
- **Spacebar**: End your turn
- **Middle mouse button (hold and move)**: Rotate the camera
- **Middle mouse button (use the wheel)**: Get closer or further
- **A, W, S, D**: Moves the camera

---

## ⚔️ Abilities

### 1. Jab
- Weak melee attack  
- Consumes **stamina**

### 2. Bow Shot
- Ranged attack  
- Cannot be used at melee range  
- Cannot pass through walls  
- Consumes **stamina**  

⚠️ The character does not currently have a bow equipped, so the animation is incorrect.  
This ability is included so it can already be tested. The correct animation is the one used by the enemies wielding a bow.

### 3. Slash
- Strong melee attack  
- Consumes **stamina**

### 4. Teleport
- Instantly move to an unoccupied hexagon  
- Can cross walls  
- Consumes **energy**

---

## 🚧 Development Status

This is a **pre-alpha** version:
- Systems are incomplete
- Balance is not final
- Visuals and animations are provisional
- Bugs and rough edges are expected

Feedback and testing are welcome.

If you have anything you would like to share with the developer please, contact him using this e-mail address: rpgdevcontact@gmail.com
