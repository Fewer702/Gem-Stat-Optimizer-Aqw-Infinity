# Gem Stat Optimizer
A lightweight browser tool for **AdventureQuest Worlds: Infinity** that helps you manage your gem inventory and maximize your character's overall stats across all four equipment slots.

## Features
- **Bag inventory** — add gems with their equipment tag (Weapon, Armor, Helm, Cape) and class type (Fighter, Wizard, Thief, Healer, Lucky)
- **Equipment slots** — click any gem in your bag to instantly equip it to its matching slot
- **Live stat bars** — see your total STR, END, DEX, INT, WIS, and LCK update in real time based on what's equipped
- **Auto-save** — all gems and equipped state save to your browser's local storage, so your data persists every time you reopen the file

## How to use
1. Open `gem_stat_optimizer.html` in any modern browser
2. Select a slot, class, and stat values, then click **Add to bag**
3. Click a gem pill in the bag to equip it — a green checkmark confirms it's active
4. Click the × on any equipment slot to unequip
5. Your data saves automatically — no action needed

## Stat weights tracked
| Stat | Label |
|------|-------|
| Strength | STR |
| Endurance | END |
| Dexterity | DEX |
| Intelligence | INT |
| Wisdom | WIS |
| Luck | LCK |

## Notes
- Local storage saves to the specific browser you use — data won't transfer between browsers or devices
- No internet connection required after the file is opened (icons load from a CDN on first load)
- Built as a single self-contained HTML file — no install, no dependencies

please enjoy my code :)
