---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


# Painful Motivation

## Required Addons / Weakauras
### Addons

[Big Wigs](https://www.curseforge.com/wow/addons/big-wigs)

[Method Raid Tools](https://www.curseforge.com/wow/addons/method-raid-tools)

[RCLootCouncil](https://www.curseforge.com/wow/addons/rclootcouncil)
### Weak Auras

#### PM Raid Packs
[PM - Raid Utilities](https://wago.io/fT3mmuaXM)

[PM - Amirdrassil Pack (10.2)](https://wago.io/3BOQnsnbo)

#### Utility
[Kaze MRT Reminders - included in PM - Raid Utilities](https://wago.io/n7l5uN3YM)

[Interrupt Assignment Anchors - included in PM - Raid Utilities](https://wago.io/InterruptAnchor)

#### Liquid Weakauras
[Liquid Amirdrassil WA](https://wago.io/LiquidAmirdrassil)

[Liquid Anchors](https://wago.io/LiquidAnchors)

[Liquid Backend Utilities](https://wago.io/LiquidWeakAuras)
### Macro
Purchase Squeaky Bat off AH and keep in your inventory. When you use your macro it will also use the squeaky bat creating a event in the log for us to use during log reviews of Warcraft Logs. 
```
/run WeakAuras.ScanEvents("LIQUID_PRIVATE_AURA_MACRO", true)
/click ExtraActionButton1
/use Squeaky Bat
```

## Healing Resources

[PM Healing CD Sheet (10.2)](https://docs.google.com/spreadsheets/d/1wTBt3kroM1073QTZB_SzQhVLCF1-fX7VfCiAwbcIXAs/edit#gid=495019183)

## Other Resources

#### Mythic Trap
https://www.mythictrap.com/en

<br>
<br>
<br>

## Loot Rules
### Important Additional Requirements:
1. Tier must have a note that states how many pieces you have and your track upgrade. (e.g. "4 piece, Champ to Myth")
2. Upgrading the same BiS item: **Two** tracks is **Major**, **One** track is **Minor**
3. Include if an item is BiS for you in your loot note (e.g. "BiS ST Trinket")

#### Item Tracks for Reference
```
LFR:    463 Veteran  [Vet]
Normal: 476 Champion [Champ]
Heroic: 483 Hero     
Mythic: 489 Myth
``` 
#### Roll Options
**Major Upgrade:** (Add to note if item is BiS)
- 9+ ilvl
- Same item upgrade by **Two** tracks (including BiS)
- 3-6 ilvl with Tertiary

**Minor Upgrade:**
- 3-6 ilvl
- Same item upgrade by **One** track (including BiS)
- 0 ilvl with Tertiary
- Tier token for chance at Tertiary

**Sidegrade:**
- 0 ilvl
- Item that will be swapped for AoE / ST
- Item for M+

**Offspec:**
- Item for offspec

**Transmog:**
- Item for transmog

**Pass:**
- I do not want this item

### Loot Priority: 
```
Main: Primary Raid Char
Alt: Any other character
```
1. Main Major
2. Main Minor
3. Main Sidegrade / Alt BiS
4. Alt Major
5. Main Offspec / Alt Minor
6. Transmog

### Loot Flowchart
[Loot Flowchart Link](https://cdn.discordapp.com/attachments/998649601806577814/1184593729198235678/painful_motivation_loot_roll_diagram.png)

<br>
<br>
<br>

## Strategy Sourcing and Disclaimer

All strategies discussed by myself (Yvairel) come from a variety of sources. Primarily: RLE Discord, Viserio Discord, Mythic Trap, Dratnos Strategy Videos. No strateies are set in stone and can always be changed.

Keep in mind this does not mean making major changes to the strategy mid-pull due to a "feeling". If you feel something major we are doing is going poorly contact me AFTER raid and we can review videos, see how we want to handle it, and make changes for the next raid night.

Small tweaks you think should be made to the strategy should always be voiced in between pulls. We can discuss and decide to use the tweak or not before the next pull.

Any clarifcations you need should be asked in between pulls. I will always take the time to re-explain something if necessary. 

I keep a video of every single pull we do locally on my machine and I am happy to review any of them with anyone who has questions, comments, or concerns. If you do not feel comfortable discussing these things with me then please reach out to Sinon or Snoop and they can bring it up to me. 
 
### Primary sources of strategy information
These are the resources I use for our strategies. 

- Raid Leader Exchange Discord (90% of the strats come from here)
- Viserio Discord
- Mythic Trap
- Lorrgs (logs data normalization)