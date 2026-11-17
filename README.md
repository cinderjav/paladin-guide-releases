# Paladin Guide

A World of Warcraft: Forever addon for **Retribution Paladins**, **Feral Druids** and **Enhancement Shamans**. It shows which spell to press next, reminds you of missing buffs, says whether gear is an upgrade (crafted gear too), lists gear upgrades for your level, suggests where to level, and guides you through dungeons boss by boss.

On a Druid it calls itself **Feral Guide**, and on a Shaman **Enhancement Guide**.

## Download

Get the latest `PaladinGuide-x.y.z.zip` from **[Releases](../../releases/latest)**.

## Install

1. Quit the game.
2. Open the zip. Inside is a folder named `PaladinGuide`.
3. Put that `PaladinGuide` folder in your game's AddOns folder:
   - Windows: `C:\Program Files (x86)\World of Warcraft\_forever_\Interface\AddOns\`
   - Mac: `/Applications/World of Warcraft/_forever_/Interface/AddOns/`
   - If `AddOns` doesn't exist yet, create it.
4. Check the path. It must be `...\AddOns\PaladinGuide\PaladinGuide.toc`.
   - Windows' "Extract All" can add an extra folder, giving `AddOns\PaladinGuide-0.5.0\PaladinGuide\`.
   - If that happens, move the inner `PaladinGuide` folder up into `AddOns`.
5. Start the game.
6. On the character screen, click **AddOns** (bottom left) and make sure **Paladin Guide** is ticked.
7. Log in.

Optional but recommended:
- **Questie**, for quests to pick up in the leveling guide.
- **Auctionator**, for Auction House prices in the Gear tab.

## Use

- Type `/pg` to list the commands.
- Target an enemy and the box shows what to press: the big icon now, then the next two.
- The round button by the minimap opens the pane:
  - left-click for Leveling;
  - right-click for Stats;
  - shift-click for Gear.
- `/pg unlock` lets you move the box, and `/pg lock` fixes it in place.
- In a dungeon, a step card shows the next boss, how to get there and its tactic, with a star on a boss that drops an upgrade for you. Its **Map** button shows the floor with the route. `/pg dungeons` lists the dungeons around your level and the quests to take in.
- `/pg check` shows what the addon can see.
  - **Druids:** after your first fight, type `/pg check` and send the line that starts "In your last fight". It says whether the game lets addons see energy and combo points.

## Updating

Download the new zip and replace the `PaladinGuide` folder.

- Restart the game, rather than `/reload`.
- Your settings are kept.

## License note

The boss positions on the dungeon maps (`PaladinGuide/DungeonPins.lua`) come from [CMaNGOS classic-db](https://github.com/cmangos/classic-db) and are under the GNU General Public License version 3. That file may be shared under its terms.

