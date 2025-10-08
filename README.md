# 🏴‍☠️ Tiny Pirate Quest

*A 2D browser adventure built with Godot by **Dannalyze** for the 2025 LittleJS Game Jam.*

---

## 🎮 Overview

**Tiny Pirate Quest** is a light-hearted platformer inspired by classic side-scrollers like *Mario* and *Sonic* — reimagined through a One-Piece-style world.

You’ll guide **Lufu**, a young straw-hat pirate, through islands filled with hazards, coins, and quirky enemies, all leading to a final boss showdown worthy of the Grand Line.

Idle animations, dynamic music, and smooth physics give the game a fun, living feel — because even pirates need to look cool when standing still. 🏴‍☠️✨

---

## 🧩 Gameplay Features

* ⚡ Smooth running and jumping mechanics
* 🎩 Idle + special idle animations (Lufu adjusts his hat, looks around, or stretches)
* 💥 Boss battle finale inspired by classic Sonic end-acts
* 🎵 Original background music and sound effects (`.ogg` format)
* 🌅 Pixel-art style level design with parallax backgrounds

---

## 🕹️ Controls

| Action     | Key        |
| ---------- | ---------- |
| Move Left  | ← or A     |
| Move Right | → or D     |
| Jump       | Space or W |
| Pause      | Esc        |

---

## ⚙️ Built With

* [Godot Engine 4.x](https://godotengine.org/)
* GDScript
* Custom assets and effects by **Dannalyze**

---

## 🧠 Development Notes

The game uses a **CharacterBody2D**-based movement system with smooth acceleration and a timed idle system:

> If Lufu stays still for 3 seconds, a special idle animation plays (like stretching or adjusting his hat).

---

## 🚀 How to Run Locally

1. Clone the repository

   ```bash
   git clone https://github.com/YOURUSERNAME/TinyPirateQuest.git
   cd TinyPirateQuest
   ```
2. Open the folder in **Godot 4.x**
3. Press **F5** to run the project
4. To export as a web build:

   * Go to **Project → Export → Web**
   * Add preset: “Web (HTML5)”
   * Click **Export Project** → choose folder → upload `.html` and `.wasm` files to [itch.io](https://itch.io)

---

## 📜 License

This project is licensed under the **MIT License** — feel free to learn from, remix, or improve upon it.
Credit **Dannalyze** if you share or build on this project.

---

## 💬 Credits

**Game Design & Programming:** Dannalyze
**Engine:** Godot
**Special Thanks:** LittleJS Jam Community

---

> *"Even a tiny pirate can dream big — as long as they keep sailing forward."*
> — **Dannalyze**
