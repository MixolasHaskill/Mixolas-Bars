# Mixolas Bars

**Controller-first action bars, customizable keybindings, and flexible UI layouts for World of Warcraft.**

Mixolas Bars is a free World of Warcraft addon by **Mixolas HasKill**. It provides configurable action bars, modifier-aware diamond layouts, visual customization, profile tools, and keybinding management. Designed alongside a Steam Controller 2 setup, the addon is also usable independently of Steam Input.

> Not making World of Warcraft a controller game — making a controller meet the demands of World of Warcraft.

## Current beta

**Version:** `0.21.11-rc.8.66` (Classic Hardcore beta)

**Supported client:**
- WoW Classic Era / Hardcore — **1.15.9** (`11509`)

RC8.66 is the current download. RC8.65 is the most recent separately documented live gameplay QA baseline (five tests passed on Classic Hardcore). A cross-computer fresh-install test has not been confirmed. This is a beta, not a stable release.

**Download:** [Mixolas Bars RC8.66 Hardcore Beta ZIP](https://raw.githubusercontent.com/MixolasHaskill/Mixolas-Bars/main/MixolasBars_0.21.11_RC8.66_CurseForge_Hardcore_Beta_Lean.zip) · [RC8.66 release notes](RELEASE_NOTES_RC8.66.md)

## Highlights

- Custom action bars, modifier diamonds, decorative frames, and Pet Bar
- SHIFT, CTRL, ALT, and combined-modifier keybinding organization
- Adjustable visual styles, frames, labels, positions, and visibility
- Built-in protected **MIXOLAS** Hardcore preset with 59 Mixolas binding slots and 86 native WoW key mappings
- Editable personal profiles, with backup/restore and portable settings import/export
- Explicit confirmation before applying the preset's native WoW keybindings

## Install

1. Close World of Warcraft.
2. Download the **RC8.66 Hardcore Beta ZIP** using the link above.
3. Extract it to your game client's `Interface/AddOns/` directory so that `Interface/AddOns/MixolasBars/MixolasBars.toc` exists.
4. Start WoW and enable **Mixolas Bars** in the AddOns list.
5. Back up your SavedVariables and existing native WoW keybindings before selecting/applying the MIXOLAS preset.

The package also documents `/mxbtransfer` for portable settings.

**Important:** The addon does *not* copy your Blizzard action-slot spell placements or macro contents. Its included preset may apply native WoW shortcuts after a confirmation prompt. Keep a backup of your existing bindings. Steam Controller 2 configurations are downloaded separately.

## Steam Controller 2

- [Quick setup & download video](https://youtu.be/ZJXug3yZYmo)
**NEW — November 11, 2026: Only one Steam Input layout is needed.**

- **[Steam Deck / Steam Controller 2 WoW Layout — universal download](https://steaminputdb.com/config/3838058545)**
- [Current setup and Free Mouse instructions](STEAM_INPUT_SETUP.md)

The older separate Steam/Guide Button Chord setup demonstrated in the Quick Start video is obsolete. Hold **D-pad Down** to enable Free Mouse temporarily: Always-On right-click releases, LT/RT become right/left mouse click, and releasing D-pad Down restores gameplay controls. No second Guide Button download is required.
- [Mixolas HasKill on YouTube](https://www.youtube.com/@mixolashaskill)

The video covers Steam layout installation and the Always-On command, rather than in-game keybinding configuration.

## Limitations and feedback

- Cross-computer camera-view transfer is not yet verified; camera views were observed applying on the author's test installation.
- This project is in active beta development. Feedback and reproducible bug reports are welcome.

See [RC8.66 release notes](RELEASE_NOTES_RC8.66.md) for the current package description and testing notes.
