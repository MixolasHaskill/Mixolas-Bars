# Mixolas Bars

**Controller-first action bars, customizable keybindings, and flexible UI layouts for World of Warcraft.**

Mixolas Bars is a free World of Warcraft addon by **Mixolas HasKill**. It provides configurable action bars, modifier-aware diamond layouts, visual customization, profile tools, and keybinding management. Designed alongside a Steam Controller 2 setup, the addon is also usable independently of Steam Input.

> Not making World of Warcraft a controller game — making a controller meet the demands of World of Warcraft.

## Current beta

**Version:** `0.21.11-rc.8.65` (initial public beta, October 31, 2026)

**Supported client:**
- WoW Classic Era / Hardcore — **1.15.9** (`11509`)

RC8.65 passed five live in-game QA checks on Classic Hardcore. A cross-computer fresh-install test has not been confirmed. This is a beta, not a stable release.

**Downloads:** [GitHub releases](https://github.com/MixolasHaskill/Mixolas-Bars/releases) · [Release details](RELEASE_NOTES_RC8.65.md)

## Highlights

- Custom action bars, modifier diamonds, decorative frames, and Pet Bar
- SHIFT, CTRL, ALT, and combined-modifier keybinding organization
- Adjustable visual styles, frames, labels, positions, and visibility
- Built-in protected **MIXOLAS** Hardcore preset with 59 Mixolas binding slots and 86 native WoW key mappings
- Editable personal profiles, with backup/restore and portable settings import/export
- Explicit confirmation before applying the preset's native WoW keybindings

## Install

1. Close World of Warcraft.
2. Download the **Hardcore Beta** ZIP from **Releases**.
3. Extract it to your game client's `Interface/AddOns/` directory so that `Interface/AddOns/MixolasBars/MixolasBars.toc` exists.
4. Start WoW and enable **Mixolas Bars** in the AddOns list.
5. Back up your SavedVariables and existing native WoW keybindings before selecting/applying the MIXOLAS preset.

The package also documents `/mxbtransfer` for portable settings.

**Important:** The addon does *not* copy your Blizzard action-slot spell placements or macro contents. Its included preset may apply native WoW shortcuts after a confirmation prompt. Keep a backup of your existing bindings. Steam Controller 2 configurations are downloaded separately.

## Steam Controller 2

- [Quick setup & download video](https://youtu.be/ZJXug3yZYmo)
- [SteamInputDB configuration 3830487043](https://steaminputdb.com/config/3830487043)
- [SteamInputDB configuration 3830487378](https://steaminputdb.com/config/3830487378)
- [Mixolas HasKill on YouTube](https://www.youtube.com/@mixolashaskill)

The video covers Steam layout installation and the Always-On command, rather than in-game keybinding configuration.

## Limitations and feedback

- Cross-computer camera-view transfer is not yet verified; camera views were observed applying on the author's test installation.
- This project is in active beta development. Feedback and reproducible bug reports are welcome.

See [RC8.65 release notes](RELEASE_NOTES_RC8.65.md) for the full change summary and package checksum.
