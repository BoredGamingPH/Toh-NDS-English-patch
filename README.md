# Tales of Hearts DS – English Translation v0.9.2 (test build)

A full English translation of the Japanese Nintendo DS game *Tales of Hearts*, for both the **Anime Movie Edition** and the **CG Movie Edition**. It is based on the official English script of **Tales of Hearts R** (PS Vita): R's names, terms and lines are used wherever a scene matches, and DS-only scenes are translated in the same style.

> **Tool-assisted translation.** The translation and the patching tools were made with AI assistance (Claude, by Anthropic), alongside the official *Tales of Hearts R* English script. Some lines may still read stiffly or miss nuance, so player feedback is especially valuable.

## What's translated

- All story scenes, skits (including choices and hint skits), NPC dialogue and side quests
- Menus, battle interface, tutorials, shops, save/load and the Synopsis
- Items, materials, accessories, Somas, artes, skills, titles, enemies and the Monster Book
- Town-name banners and title-screen buttons
- Labels drawn as pictures in the menus: shop columns, camp menu, Curestone settings, status screens, battle-mode tabs, formation, town & dungeon list, name-entry keyboard, slot machine

## How to apply

There is one patch for each Japanese edition. Both have the same translation; the editions differ only in their movies.

| | Anime Movie Edition | CG Movie Edition |
|---|---|---|
| Your ROM | `Tales of Hearts - Anime Movie Edition (Japan).nds` | `Tales of Hearts - CG Movie Edition (Japan).nds` |
| ROM CRC32 | **82C1282F** | **6BEA837E** |
| Patch | `Tales of Hearts DS - English (R script) v0.9.2.xdelta` | `Tales of Hearts DS CG Movie Edition - English (R script) v0.9.2.xdelta` |
| Patched CRC32 | **65DA96E9** | **B01B8034** |

1. Get your own dump of one of the Japanese ROMs and check its CRC32 against the table.
2. Apply the matching patch with xdelta3, xdeltaUI, Delta Patcher or [RomPatcher.js](https://www.marcrobledo.com/RomPatcher.js/).
3. Check the patched ROM's CRC32.

Apply it to the clean Japanese ROM, not to a ROM that already has another English patch. Start a new game.

No ROMs are provided here.

## What we need from testers

- Play through and report any leftover Japanese text, text running off its box, garbled graphics, or crashes.
- Include a screenshot and say where it happened (chapter, town or menu).
- Please also mention lines that read awkwardly or don't fit the scene.

Report issues in the [Issues](../../issues) tab.

## Changes

Full history: [CHANGELOG.md](CHANGELOG.md)

**v0.9.2**
- Translated the Synopsis menu: all 48 chapter summaries, with their titles.
- Added a CG Movie Edition patch (same translation).

**v0.9.1**
- Fixed the first entry of several lists still showing Japanese: Fire Willstone (material), Asteria (Soma), World Map (key item), Play Time (grade shop) and Kor (enemy entry).

**v0.9**
- First public test build.

## Known issues

- A few sample pictures in the camp menu (e.g. the menu title box) may still show Japanese if the game doesn't draw over them. Please report it with a screenshot if you see it.

## Ko-Fi
https://ko-fi.com/boredgamingph - FULLY OPTIONAL I want this to be clear, I just added this if you want to support.

## AI Disclaimer
Current usages of AI is the generation of the Translation, the patch
and translation of this git Readme for grammar correction and conciseness

## Credits

- English text based on *Tales of Hearts R* © Bandai Namco Entertainment; DS-only scenes translated in the same style.
- Font spacing adjustments by Dawnbomb (from his Tales of Hearts DS patch v0.8.25).
- Translation and tools made with AI assistance (Claude, by Anthropic).

*Tales of Hearts* is © Bandai Namco Entertainment. This is an unofficial fan translation, not affiliated with or endorsed by Bandai Namco.
