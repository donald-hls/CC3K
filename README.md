# CC3K – Chamber Crawler 3000
A turn-based, rogue-like dungeon crawler implemented in **C++20**, the project demonstrates strong object-oriented design, modularity, and extensibility.

---

## 🧩 Overview
CC3K is played on a grid-based dungeon consisting of chambers filled with enemies, items, and obstacles.  
Players choose from various races and navigate floors while battling enemies, collecting potions, and managing strategy around gold, attack, and defence.

The game is terminal-based and supports both keyboard interaction and command file execution.

---

## ✨ Core Features
### 🎮 Gameplay
- Multiple playable races (Human, Elf, Dwarf, Orc, etc.)
- Hostile and non-hostile enemies with unique behaviours
- Floor generation using chamber-based tiling
- Movement, attacks, potions, treasure collection
- Multi-floor progression and win/lose state handling
- Merchant & dragon hoard mechanics
- Turn-based enemy AI

### 🧱 Architecture & Design
- Fully object-oriented C++20 design
- Strong module separation
- Use of Key Design Patterns:
  - **Observer** (for display updates)
  - **Factory** (for enemy/item creation)
  - **Decorator** (for potion stat buffs)
  - **Strategy / Polymorphism** (for enemy behaviors)
- High cohesion and low coupling across modules

---
