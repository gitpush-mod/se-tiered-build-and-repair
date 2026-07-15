<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0B1021,45:2563EB,100:7C3AED&text=Tiered%20Build%20And%20Repair&fontColor=ffffff&fontAlignY=35&fontSize=30&desc=Progression-gated%20nanobots%20for%20Digi%27s%20Build%20%2B%20Repair%20System&descAlignY=57&descSize=15" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Space%20Engineers-1-0EA5E9?style=for-the-badge" alt="SE1" />
  <img src="https://img.shields.io/badge/Requires-Digi's%20Nanobot%20B%26R-orange?style=for-the-badge" alt="Requires Digi B&R" />
  <a href="https://github.com/gitpush-mod/se-tiered-build-and-repair/issues/new?template=bug_report.md&labels=bug"><img src="https://img.shields.io/badge/Report%20a%20bug-red?style=for-the-badge&logo=github&logoColor=white" alt="Report a bug" /></a>
</p>

> **"Nanobots shouldn't be a one-block win-button. Earn them."**

Turns Digi's popular **[Nanobot Build and Repair System](https://steamcommunity.com/sharedfiles/filedetails/?id=857053359)** into a three-tier progression: a cheap early-game welder, a mid-game any-grid builder, and an endgame prototech monster with full welding, grinding, and janitor sweep. Progression-gated the same way NJFL gates its Advanced blocks: **Superconductors, Reactor Components, and eventually Prototech Scrap.**

## ✨ The three tiers

| Tier | Subtype prefix | Grids | Mode | Grinding | Janitor | Prototech gate |
|---|---|---|---|---|---|---|
| **Base — Build And Repair** | `STG_NanobotBase` | LG only, static grids | Walk (connected sub-grids) | ❌ | ❌ | ❌ |
| **Upgraded — Upgraded Build And Repair** | `STG_NanobotUpgraded` | LG + SG, any grid | Fly (nearby disconnected ships too) | ❌ | ❌ | ❌ |
| **Advanced — Advanced Build And Repair** | `STG_NanobotAdvanced` | LG + SG, any grid | Fly | ✅ | ✅ (grind enemy/abandoned blocks) | ✅ (Prototech Scrap in build recipe) |

Progressive Superconductor and Reactor Component taxes across tiers, matching the NJFL scaling.

## ⚠️ Requires Digi's Nanobot Build and Repair System

This mod **references models from** [Digi's original Nanobot Build and Repair System](https://steamcommunity.com/sharedfiles/filedetails/?id=857053359). You must have that mod subscribed and loaded for the block models and icons to render. Load Digi's mod first, then this one.

## 🚀 Install

**Workshop publish pending.** Currently distributed as a manual install:

1. Install [**Digi's Nanobot Build and Repair System**](https://steamcommunity.com/sharedfiles/filedetails/?id=857053359) (required dependency)
2. Clone or download this repo into your `%AppData%\SpaceEngineers\Mods\` folder as `Tiered Build And Repair`
3. Enable both mods in the mod list, Digi's first
4. New tier-1 through tier-3 nanobot blocks appear in the Cube Blocks category

The Workshop version will be published shortly — a subscribe link will replace this section then.

## 🎯 Compatibility

- ✅ **Space Engineers 1** — actively maintained
- ✅ **Save-safe** — additive block set, doesn't overwrite Digi's originals
- ✅ **Multiplayer + dedicated servers** — same server-safety as Digi's mod
- ⚠️ **Requires Digi's mod** (see above)

## 🐛 Found a bug?

- **[Open an issue with the bug template](https://github.com/gitpush-mod/se-tiered-build-and-repair/issues/new?template=bug_report.md&labels=bug)**

## 🙌 Credits

- **Author:** [Chris Carpenter (Godimas101)](https://github.com/Godimas101)
- **Model / icon / core B&R system:** [Digi](https://steamcommunity.com/id/Digi_SE) — Nanobot Build and Repair System is the foundation this mod builds on
- **Test bed:** [Sturmgrenadier Hosting](https://sghq.org/)

## 🧡 Support

Free and always will be. **Patreon** for the ongoing project log.

[![Support on Patreon](https://raw.githubusercontent.com/Godimas101/personal-projects/main/patreon/images/buttons/patreon-medium.png)](https://patreon.com/Godimas101)

---

*Part of the [`gitpush-mod`](https://github.com/gitpush-mod) mod collection. Made with ♥ (and a lot of coffee) by Godimas + Claude.*
