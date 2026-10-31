Tales of Hearts DS (Anime Movie Edition) - English Translation, v0.9 (test build)
================================================================================

A complete English translation of the Japanese Nintendo DS game, written to match the
official English script of the remake Tales of Hearts R (PS Vita): same names, same terms,
and R's own lines wherever a scene matches.

Tool-assisted translation: the translation and the patching tools were made with AI
assistance (Claude, by Anthropic), alongside the official Tales of Hearts R English script.

Translated
----------
- All story scenes, skits (including choices and hint skits), NPC dialogue and side quests
- Menus, battle interface, tutorials, shop names, save/load messages
- Items, materials, accessories, Somas, artes and skills, titles, enemies and Monster Book,
  battle memos, strategies, Spiria Link data
- Town-name banners and title-screen buttons
- Labels drawn as pictures in the menus: shop columns, camp menu (Area / Play Time / Gald),
  Curestone settings, status screen (ATK, DEF, Arte ATK...), battle mode tabs, formation,
  town & dungeon list, name-entry keyboard, slot machine, completion rate

Not yet translated
------------------
- A few sample pictures in the camp menu (e.g. the menu title box) that the game may draw
  over at run time. If you see Japanese there, please report it with a screenshot.

How to apply
------------
1. You need the Japanese ROM:
     Tales of Hearts - Anime Movie Edition (Japan).nds
     CRC32: 82C1282F
2. Apply "Tales of Hearts DS - English (R script) v0.9.xdelta" with xdelta3 or xdeltaUI
   (or any VCDIFF patcher, e.g. Delta Patcher / RomPatcher.js).
3. The patched ROM should have CRC32: F86AF16E

Apply it to the clean Japanese ROM, not to a ROM that already has another English patch.
Start a new game (old saves from other patches may show leftover text).

Credits
-------
- English text based on Tales of Hearts R (c) Bandai Namco Entertainment; DS-only scenes
  translated in the same style.
- Font spacing adjustments by Dawnbomb (from his Tales of Hearts DS patch v0.8.25).
- Translation and tools made with AI assistance (Claude, by Anthropic): custom Node.js
  toolchain for script, data and UI text insertion and image editing.

This is a test build. Please report untranslated text, text running off boxes, or crashes,
with a screenshot and where it happened.
