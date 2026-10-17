# Infinity Blade III PC – QoL mod

Small quality-of-life mod for the Infinity Blade III PC port (v1.0.0).

[![Download dinput8.dll](https://img.shields.io/badge/DOWNLOAD-dinput8.dll-2ea44f?style=for-the-badge)](https://github.com/andresjmb/IB3-QoL-Mod/raw/main/dinput8.dll)

## Features

- **World map:** every place shows **NEW**, **VISITED** or **COMPLETED**, and the level you need if yours is too low. **LOCATIONS** button with the full list. Mouse wheel zoom.
- **Gem Cutter & Potion Master:** **RECIPES** button with every recipe, using the game's icons. Click a result to see what it does.
- **Restart any fight**, including the ones the game normally won't let you restart (super bosses, story fights): hold **R** for 0.7 s during the fight or on the defeat screen. The pause menu's "Restart Battle" and the defeat screen's "Replay" are always available too.
- **Sword clash taps on the keyboard:** when blades lock in a parry clash and the game asks you to tap fast, press **F** or **Numpad 5** instead of clicking. These keys do nothing at any other moment.
- **Diagonal combo steps work** (see below).

![World map](screenshots/map.jpg)

![Recipes in the Fusion Chamber](screenshots/recipes-gems.jpg)

## Install

1. Download **`dinput8.dll`** with the green button above.
2. Put it in `InfinityBlade3_v1.0.0\Binaries\Win64` (next to `IB3.exe`).
3. Play.

To uninstall, delete `dinput8.dll`. No game files or saves are changed.

**Steam Deck / Linux:** add `WINEDLLOVERRIDES="dinput8=n,b" %command%` to the launch options.

## Fixed in v0.6: diagonal combo steps

**The bug (in the game):** some weapons, like Snikt, have combos with diagonal arrows, and those steps almost never registered. The game accepts only one exact slash for each diagonal step, the flat one that's closer to horizontal. A swipe that was a bit steeper counted as up or down instead, and with the keyboard, Numpad 7 and Numpad 3 send the steep diagonals, so the up-left and down-right steps were impossible.

**The fix:** a diagonal step now also accepts the steeper diagonal next to it. That covers natural diagonal swipes and Numpad 7 / 3. Straight steps work exactly as before.

---

Unofficial fan project. Infinity Blade III belongs to ChAIR Entertainment.
