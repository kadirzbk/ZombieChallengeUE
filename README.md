# ZombieChallenge 🧟‍♂️🔫

An action-packed First-Person Shooter (FPS) Zombie Survival game built with **Unreal Engine**. Fight your way through hordes of zombies in intense arena and forest environments.

---

## 🎮 Features

- **First-Person Shooter Mechanics**: Smooth movement, weapon handling, shooting, and reloading.
- **Dynamic Levels**: 
  - **Arena Shooter Level**: Fast-paced close quarters combat.
  - **Spruce Forest Level**: Open-world tactical survival.
- **Zombie AI**: Smart zombie spawning, pathfinding, and chasing behavior.
- **Optimized Assets**: High-quality modular environmental assets and models.

---

## 🛠️ Built With

- **Engine**: Unreal Engine (UE5)
- **Scripting**: Blueprints & C++
- **Version Control**: Git & Git LFS (Large File Storage)

---

## 🚀 Getting Started

### Prerequisites

1. Install [Unreal Engine](https://www.unrealengine.com/) (compatible version).
2. Install [Git](https://git-scm.com/) and [Git LFS](https://git-lfs.github.com/).

### Installation & Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kadirzbk/ZombieChallengeUE.git
   ```
2. **Initialize Git LFS** (to pull all large assets/textures):
   ```bash
   git lfs pull
   ```
3. Open the `ZombieChallenge.uproject` file in the Unreal Engine Editor.
4. Generate Visual Studio project files (if applicable) and compile/run the project.

---

## 📂 Project Structure

- `Config/`: Project and editor configuration files.
- `Content/`: All game assets, maps, blueprints, materials, and audio files.
- `Source/`: C++ source code (if applicable).
- `.gitignore`: Configured to exclude heavy temporary folders like `Binaries`, `Intermediate`, and `Saved`.
- `.gitattributes`: Configured to manage large assets (`.uasset`, `.umap`, `.fbx`, etc.) using Git LFS.
