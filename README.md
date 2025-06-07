# 🧙 Text RPG Game – Feature Expansion Project

Welcome to our Escape Room RPG game repository! Developed as part of our coursework, this project began with a simple text-based role-playing game template. Working collaboratively, our team extended the original code by implementing new features, enhancing gameplay mechanics, and transforming it into a fully interactive experience. The final result includes rich game logic, multimedia integration, and engaging visual and audio effects that bring the escape room adventure to life.

---

## 📌 Project Summary

We were given a starter text RPG game and tasked with adding our own features and improvements. This was a **group project**, and we released two main versions:

- **Beta Version** – Introduced a playable structure and core mechanics.
- **Final Version** – Fully interactive experience with game progression, visual/audio feedback, and a minigame.

---

## 🛠 Features Implemented

### 🎮 Core Gameplay
- A story-driven escape room plot: _"Escape the house before the Tech_Sorcerer returns!"_
- Room-based exploration using a command-line interface.
- Interactions with furniture, objects, and doors using `explore` and `examine` commands.
- Puzzle-based progression involving collecting keys and unlocking doors.

### 🔑 Object and Room Mechanics
- Multiple rooms (`Game Room`, `Bedroom 1`, `Bedroom 2`, `Living Room`, `Library`, `Outside`) interconnected via doors.
- Inventory system to track collected keys.
- Items like beds, cauldrons, tables, and furniture may contain important clues or keys.
- `object_relations` dictionary links items, rooms, and keys dynamically.

### 🧪 Minigame: Potion Puzzle
- A color combination challenge using the `table of spells`.
- Players must select the correct pair of colored bottles to unlock Door B or be turned into a frog and retry.

### 🎨 GUI and Visual Enhancements
- Basic GUI using `tkinter` with custom buttons and message popups.
- Turtle graphics window displays an image (`giphy.gif`) at game completion.
- Background color and interaction instructions guide the player visually.

### 🔊 Audio Effects
- Final message converted to speech using Google Text-to-Speech (`gTTS`) and played via `playsound`.
- `text_to_sound()` function used for other dynamic audio prompts.

---



