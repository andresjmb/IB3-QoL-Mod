# Infinity Blade III PC – QoL mod

Small quality-of-life mod for the Infinity Blade III PC port (v1.0.0).

## Features

- **World map:** every place shows **NEW**, **VISITED** or **COMPLETED**, and the level you need if yours is too low. **LOCATIONS** button with the full list. Mouse wheel zoom.
- **Gem Cutter & Potion Master:** **RECIPES** button with every recipe, using the game's icons. Click a result to see what it does.
- **Restart any fight**, including the ones the game normally won't let you restart (super bosses, story fights): hold **R** for 0.7 s during the fight or on the defeat screen. The pause menu's "Restart Battle" and the defeat screen's "Replay" are always available too.

![World map](screenshots/map.jpg)

![Recipes in the Fusion Chamber](screenshots/recipes-gems.jpg)

## Install

1. Download **`dinput8.dll`** (above).
2. Put it in `InfinityBlade3_v1.0.0\Binaries\Win64` (next to `IB3.exe`).
3. Play.

To uninstall, delete `dinput8.dll`. No game files or saves are changed.

**Steam Deck / Linux:** add `WINEDLLOVERRIDES="dinput8=n,b" %command%` to the launch options.

---

Unofficial fan project. Infinity Blade III belongs to ChAIR Entertainment.
