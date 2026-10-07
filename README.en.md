<!-- README language switch -->
[![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-555555?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-1677ff?style=for-the-badge)](README.en.md)
<!-- /README language switch -->

# CSC-240-Group-Project

A C++ group coursework project. The current code implements basic interactions between a wizard, an enemy creature, and spells.

## Code structure

| File | Contents |
| --- | --- |
| `Wizard.h` / `Wizard.cpp` | The wizard's name, health, mana, and healing method |
| `Creature.h` / `Creature.cpp` | Creature health, attack power, resistances, and damage handling |
| `Spell.h` / `Spell.cpp` | Spell mana costs, damage, and healing effects |
| `main.cpp` | Creates Merlin and a Goblin, then demonstrates Fireball and Healing Light |
| `GroupDriver.cpp` | Group driver file |

Start reading at [`main.cpp`](main.cpp). The repository currently contains a basic demonstration; it does not yet provide a dedicated build configuration or a complete game guide.
