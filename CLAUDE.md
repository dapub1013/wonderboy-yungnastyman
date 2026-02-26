# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal Baldur's Gate 3 (BG3) character build reference repository. It contains markdown files documenting level-by-level class progression, feats, spells, and item checklists for a party.

## Repository Structure

Each file documents one character:

- `wonderboy.md` — Player character: Monk (Way of the Open Hand) / Rogue (Thief) multiclass. Includes a respec at level 9.
- `yungnastyman.md` — Player character: Warlock (The Hexblade), pure class through level 12.
- `shadowheart.md` — Companion: Cleric (Death Domain), pure class through level 12.
- `laezel.md` — Companion: Fighter (Battle Master), pure class through level 12.

## Document Format Conventions

Each build file follows this structure:

1. **Header** with a YouTube/web build reference link and an anchor link to the Items section.
2. **Level-by-level progression** — each level lists only the choices made at that level (class, subclass, feats, spells, cantrips, invocations, etc.).
3. **Items section** organized by Act (Act 1 / Act 2 / Act 3) or game phase (Early/Mid/Late), with:
   - Checkbox status: `⬜` (not yet obtained), `✅` (obtained), `❌` (skipped/replaced)
   - Item slot label (Amulet, Armour, Boots, etc.)
   - Item name as a `bg3.wiki` hyperlink
   - Location tag in backticks (e.g., `` `Goblin Camp` ``)
   - Vendor name in bold or loot source description
   - Map coordinates where relevant (e.g., `X: -321 Y: -135`)
4. **Elixirs section** (some builds) listing consumables and where to obtain them.
5. **Notes** for important reminders (e.g., respec triggers, unequip conditions, item synergy sets).

## Editing Guidelines

- Keep item checkboxes current as items are obtained (`⬜` → `✅`) or decided against (`⬜` → `❌`).
- Respec notes belong inline near the relevant level or item, not in a separate section.
- Item synergy groups (like "Buff on Heal" or "Radiating Orb" sets) should be documented in a **Weapons Notes** or similar subsection at the end of the Items section.
- All item names should link to `bg3.wiki` for reference.
- Coordinates use the format `X: ### Y: ###`.
