# OOP-RPG-COMBAT-PYTHON

A turn-based RPG combat system built in Python using Object-Oriented Programming principles.

## About

This project implements a text-based RPG combat engine in Python. It demonstrates core OOP concepts — classes, inheritance, encapsulation, and polymorphism — through a classic role-playing game combat scenario. Players can choose a character class, face enemies, use skills and items, and experience a fully structured battle system.

## Features

- **Multiple character classes** — Warrior, Mage, Rogue, each with unique stats and abilities
- **Enemy encounters** — Fight against a variety of enemies with different attack patterns
- **Turn-based combat** — Choose between attack, use a skill, use an item, or flee each turn
- **Skills system** — Characters can use special abilities that consume mana or energy
- **Inventory & items** — Collect and use potions and equipment during battles
- **Stat system** — HP, MP, Attack, Defense, Speed, and more
- **Level & XP** — Gain experience points and level up after defeating enemies

## Project Structure

```
OOP-RPG-COMBAT-PYTHON/
├── main.py              # Entry point — starts the game
├── characters/
│   ├── base_character.py    # Abstract base class for all characters
│   ├── player.py            # Player character class
│   └── enemy.py             # Enemy character class
├── combat/
│   ├── battle.py            # Combat loop and turn management
│   └── actions.py           # Attack, skill, and item action logic
├── skills/
│   └── skill.py             # Skill definitions and effects
├── items/
│   └── item.py              # Item definitions (potions, equipment)
└── utils/
    └── display.py           # Console output helpers
```

## Getting Started

### Prerequisites

- Python 3.8 or higher

### Installation

```bash
git clone https://github.com/novello-dev/OOP-RPG-COMBAT-PYTHON.git
cd OOP-RPG-COMBAT-PYTHON
```

### Running the Game

```bash
python main.py
```

## OOP Concepts Used

| Concept | Where It Is Applied |
|---|---|
| **Classes & Objects** | Every character, enemy, skill, and item is a class |
| **Inheritance** | `Player` and `Enemy` inherit from `BaseCharacter` |
| **Encapsulation** | Stats and state are managed through class methods |
| **Polymorphism** | Each character class overrides `use_skill()` differently |
| **Abstraction** | `BaseCharacter` defines the interface for all fighters |

## License

This project is open source and available under the [MIT License](LICENSE).
