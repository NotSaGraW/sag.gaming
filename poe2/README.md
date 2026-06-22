# Path of Exile 2 — Personal SSF Reference

> League: **Runes of Aldur** · Patch: **0.5.2** · Character: **[Lossehelim (Disciple of Varashta)](https://poe.ninja/poe2/profile/SaGraW-0758/runesofaldur/character/Lossehelim)** · Last updated: June 2026

[![License](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/) [![Patch](https://img.shields.io/badge/patch-0.5.2-blue)](https://www.pathofexile.com/forum) [![Status](https://img.shields.io/badge/status-active-green)]()

---

## Contents

**Part I — Crafting**

- [Basics](#basics)
- [Item Level](#item-level)
- [Essences](#essences)
- [Omens](#omens)
- [Desecration](#desecration)
- [Fracturing Orbs](#fracturing-orbs)
- [Runeforging](#runeforging)
- [Crafting Workflow](#crafting-workflow)

**Part II — League Mechanics**

- [What Drops, Build Value and How to Use It](#what-drops-build-value-and-how-to-use-it)
- [Atlas Node Priority](#atlas-node-priority)
- [Atlas Masters](#atlas-masters)
- [Biomes](#biomes)
- [Tablets](#tablets)

**Part III — Gear Priorities**

- [Current State](#current-state)
- [Priorities](#priorities)
- [Crafting by Slot](#crafting-by-slot)

**Part IV — Early Endgame (historical record)**

- [Fortress Questline Path](#fortress-questline-path)

> Items marked ⚠️ are diffuse, single-source, or inconclusive despite multiple reports. Everything else carries the normal reliability of a game guide.

---

# Part I — Crafting

## Basics

A rare item has 6 mods maximum: 3 prefixes and 3 suffixes. Prefixes and suffixes are independent — a currency that targets prefixes never touches suffixes.

Each item can hold **1 crafted mod + 1 desecrated mod** maximum. Essences, Perfect Essences and Imbued Alloys all share the same crafted slot. Chaining is not possible.

At T15-16, use **Perfect** Exalted/Regal/Chaos when available — they floor at mod level 50, cutting the lowest tiers from the pool.

Before any expensive craft: open **PoE2DB** (poe2db.tw), look up the base, check which tags the mods you need carry and at what ilvl T1 unlocks. There is no in-game modifier browser, so PoE2DB is mandatory while crafting.

---

## Item Level

T15 maps with monster level 79-80 drop bases of the right ilvl directly. Key T1 gates:

| Mod | Slot | Min ilvl for T1 |
|---|---|---|
| % Movement Speed | Boots | 82 |
| Elemental Resistance | All | 82 (+41–45%) |
| Chaos Resistance | Body Armour | 81 |
| +# Minion Skill Levels | Amulet/Sceptre | 81 |
| +# Max Life / ES | Body/Belt/Jewellery | Varies — check PoE2DB |

An item at ilvl 75-80 has less mod competition than one at ilvl 82 — better odds of hitting what you want at the cost of locking out the absolute T1s.

---

## Essences

Guarantee a specific mod on craft. Limit: 1 Greater + 1 Perfect per item. Use on the hardest mod to get for each piece.

| Essence | Type | Guarantees | Use case |
|---|---|---|---|
| Essence of Enhancement | Prefix | % increased Global Armour/Evasion/ES | Body armour, boots |
| Essence of the Body | Prefix | +# Maximum Life | Belt, jewellery |
| Essence of Command | Prefix | % increased Damage to Allies | Main sceptre |

---

## Omens

Activate automatically with the next currency used.

**Rule:** Sinistral = Prefix · Dextral = Suffix

| Omen | Effect | When |
|---|---|---|
| Omen of Sinistral Exaltation | Exalt adds a Prefix only | Suffixes full, prefix slot open |
| Omen of Dextral Exaltation | Exalt adds a Suffix only | Prefixes full, suffix slot open |
| Omen of Sinistral Annulment | Annulment removes a Prefix | Good suffixes, bad prefix to remove |
| Omen of Dextral Annulment | Annulment removes a Suffix | Good prefixes, bad suffix to remove |
| Omen of Light | Annulment removes only the Desecrated mod | Retry Desecration without touching the rest |
| Omen of Abyssal Echoes | Rerolls the 3 Desecration options | None of the 3 options are useful |
| Omen of Sinistral Necromancy | Desecration reveal targets Prefixes only | Force desecrated mod onto a prefix |
| Omen of Dextral Necromancy | Desecration reveal targets Suffixes only | Force desecrated mod onto a suffix |

**Core combo:** Omen of Light + Annulment = remove the Desecrated mod without touching the rest of the item.

---

## Desecration

Abyssal Bones add a hidden mod, revealed at the Well of Souls (Mastodon Badlands, Act 2 — or via the Well inside Abyss encounters in maps). Maximum 1 Desecrated mod per item. Desecration is the only system in the game that can add mods outside an item's natural pool.

Bones are type-specific: Jawbone (weapons), Rib (armour), Collarbone (accessories), Cranium (jewels).

| Bone quality | Mod level floor | Use |
|---|---|---|
| Gnawed | Cap at 64 | Campaign-tier gear only — cannot be used on high ilvl map items |
| Preserved | None | Any slot, any ilvl |
| Ancient | ≥ 40 | Targeted high-end crafts. Drops only from Abyss chests, not monsters |

If the item has 6 mods, the Bone removes a random mod of the matching affix type before adding the Desecrated one. With an open slot, it adds without removing.

**Retry loop:** Omen of Light + Annulment removes only the Desecrated mod, leaving the rest intact. Omen of Abyssal Echoes rerolls the 3 revealed options.

**Faction-specific mods** (revealed at the Well of Souls): Amanamu (defensive — shields/body armour), Ulaman (offensive — weapons/jewellery crit/elemental), Kurgal (ailments — poison/bleed/ignite). Bias the pool with the matching faction Omen.

---

## Fracturing Orbs

Lock a mod permanently — nothing can remove it afterwards. Use when you have T1 on the hardest mod to get and want to build the rest on top without risking it. In SSF there is no recovery if a hard-won T1 gets wiped.

**Priority targets:** +Minion Skill Levels (suffix) on sceptre · T1 ES (prefix) on body armour.

Source: Cleansed maps are the primary Fracturing Orb drop. Summoning Circles (slotted via tablets) also produce them.

---

## Runeforging

Runes socket into items without occupying the crafted slot. Materials — Runic Alloys and Verisium — come from Expedition. Apply after crafting is complete. Socketed Jewels are now preserved when Runeforging an item.

---

## Crafting Workflow

```
1. Base at the right ilvl (PoE2DB → highest T1 gate among the mods you need)
2. Essence → lock the hardest mod to get (one shot only per item)
3. Fill remaining slots with targeted Exalts
   → Sinistral/Dextral Exaltation to control which side gets the mod
   → If one side is full: Annulment Omen to open a slot first
4. Desecration
   → Necromancy Omen to target prefix or suffix side
   → Faction Omen to bias toward Amanamu/Ulaman/Kurgal pool
   → Abyssal Echoes if none of the 3 options are useful
   → Omen of Light + Annulment to remove and retry
5. Divine → only when all mods are correct but values are low
6. Fracture → lock the highest-value mod before corrupting
7. Runes → after everything else; no interaction with the craft
8. Corruption → final layer, pure RNG
```

---

# Part II — League Mechanics

## What Drops, Build Value and How to Use It

In SSF, Atlas investment decisions are driven by what you need to craft, not by trade value.

| League | What it drops | Build value | How to use it |
|---|---|---|---|
| **Abyss** | Abyssal Bones (incl. Ancient from chests), Exalted Orbs, Omens, Heart of the Well jewels, raw currency | Only source of Bones — the entire Desecration system runs on Abyss. Accessible on any build that can clear the map | Slot Abyss tablets with "additional Abyss". Pull Amanamu rares out of the darkness before killing for upgraded Omen drops. Enter every Abyssal Depths/Dark Domain that opens |
| **Ritual** | Omens, uniques, Ritual-only idols | Omens of Annulment, Exaltation and Necromancy enable directed crafting. Deferral system lets you bank items and lower their cost each map | Farm altars per map before advancing. With reduced deferment cost you can defer expensive items at near-zero cost, working toward them over several maps |
| **Breach** | Amulets/rings/belts with minion and caster mods, Breach rings, Catalysts, Hiveblood, Altered Collarbone | Rings with additional minion projectiles scale all ranged minions. Altered Collarbone adds otherworldly Breach mods without crafting from the Genesis Tree. ⚠️ ~1,458 Hiveblood = guaranteed ilvl 84 base via Wombgift | Complete Origins of the Fortress to unlock the Genesis Tree. Catalysts are only available through it. Take Shape the Change and Power in Rares first |
| **Delirium** | Divine Orbs, Liquid Emotions, Megalomaniac Jewels, Simulacrum Splinters | Liquid Emotions are endgame jewel crafting material — in SSF you use them yourself. Megalomaniac Jewels with minion damage notables can be significant | Build must sustain full fog at T15. +4 Spread is mandatory on the Delirium tree or loot drops massively |
| **Temple (Atziri's)** ⚠️ | Vaal currency, Vaal Orbs, Irradiated tablets, Soul Cores & Ancient Soul Cores (Core Destabilizer room), double corruption | Soul Cores for socketing. Double corruption for high-risk final-layer crafts | ⚠️ Temple is under rework in 0.5.3 — verify current rewards before investing heavily |
| **Expedition** | Runic Alloys, Verisium, Fluxes, Masterwork Runes | Runeforging materials. Fluxes swap resistances on gear — useful in SSF for closing res gaps without replacing pieces. Masterwork Runes upgrade Greater Runes in a socket to Perfect | Apply Runeforging after all other crafting is done |
| **Trial of Chaos** | Soul Core (Xipocado), Chaos Orbs, Adorned jewel (2% chance) | Soul Core of Dominion: 40% increased Damage with Command Skills on sceptre/wand/staff — applies directly to Deception and Brutality. Limited to 1 | Requires Inscribed Ultimatum ≥ level 65. Socket into the main sceptre immediately |

---

## Atlas Node Priority

```
ABYSS:    "Lord of the Pit" (spreads fissures across the map) → "Abyss pits
          scattered through areas" → Rogue Exile / Heart of the Well nodes
          Faction: Amanamu (Lightless Legions) for Omens and minion-relevant
          defensive Desecrated mods
          Produces: Abyssal Bones, Exalted Orbs, Omens

RITUAL:   Ritual sub-tree + reduced deferment cost
          Produces: Omens, uniques

BREACH:   Genesis Tree first → Shape the Change → Power in Rares
          Produces: Catalysts, minion-projectile rings, Hiveblood

DELIRIUM: +4 Spread mandatory. Engage when fog at T15 is sustainable
          Produces: Divines, Liquid Emotions, Megalomaniac Jewels
```

---

## Atlas Masters

Three Masters, each with a 12-node sub-tree. One active per map; switching between maps is free; all three progress simultaneously. Up to 4 nodes from the active Master apply per map.

**Doryani** — the relevant one for SSF target farming. The Precursor Terraformer node lets map bosses guard a Terraformer that changes the biome of adjacent maps, activating biome-specific Atlas nodes. This is how you direct what content/currency a region produces. Also gives an extra revive — useful for 6-mod, 3-tablet maps — and irradiation (+1 area level).

**Hilda** — boss-focused. More rares and uniques, boss buffs. Ancient Inscriptions grants 8% Tablet Effect per different Tablet. Use when running pinnacle bosses; activate before opening a pinnacle fragment.

**Jado** — strongbox and unique-item oriented. Least aligned with minion SSF crafting; skip unless farming strongboxes specifically.

---

## Biomes

Biome-specific Atlas nodes grant bonuses depending on the map's biome. Combined with Doryani's Precursor Terraformer (which forces a map into a chosen biome), this enables target farming. Spec the biome nodes you want, then terraform maps into that biome.

| Biome | Bonus focus |
|---|---|
| Forest | Up to 65% increased rare monsters — best for rare-density farming |
| Swamp | Node available: Exalted Orb has 10% chance to drop as Chaos Orb |
| Grass | Perfect currencies |
| Mountain | Tablets / runes |
| Cities | Juiced 4-tablet maps |
| Water | Gold (+50%) or currency from chests (+15%) |

---

## Tablets

Each non-league-mechanic tablet slot increases the drop chance of tablets from random content appearing in the map. Filling all 3 slots with the same tablet type (e.g. 3× Abyss) shows only that mechanic and drops fewer of those tablets. For tablet sustain, run mixed tablets or boss-rush maps with Irradiated/Overseer tablets.

Key tablet mods: "Map contains an additional Abyss" (mandatory on Abyss tablets), Elevated tablets give +1 zone level, Overseer empowers the map boss for extra loot.

---

# Part III — Gear Priorities

## Current State

> [Lossehelim on poe.ninja](https://poe.ninja/poe2/profile/SaGraW-0758/runesofaldur/character/Lossehelim)

| Stat | Value | Status |
|---|---|---|
| ES | 6,609 | Sufficient for CI transition |
| Life | 1,736 | Emergency buffer — gone with CI |
| Chaos res | 39% | Solved by CI |
| Chaos max hit | 8.7k | Solved by CI |
| Elemental max hit | 31k | No issue |
| Block | 30% | From shield |
| Deception DPS | 38k | Rotation working |

---

## Priorities

**1. CI — transition now**

CI solves chaos resistance; it is not something you do after solving it. With CI, maximum life becomes 1 and the character becomes immune to chaos damage and bleeding. With 6,609 ES you already handle T15-16 — the defensive pool against physical and elemental hits does not change. Sacred Rituals references ES, not life, so it stays active and physical damage reduction remains the same.

What changes post-CI: chaos immune, bleeding immune, stun covered by the tree's "28% of maximum ES as additional Stun Threshold" (~1,850 at current ES). Ground DoT still stops ES recharge but without the 1,736 life buffer — move out faster. Two passive nodes lose almost all value: "5% of Maximum Life Converted to ES" gives 0.05 ES with life at 1, and "Immune to Bleeding while Archon Buff is active" is made redundant by CI itself.

**2. Breach rings with additional minion projectiles**

Scales all ranged minions simultaneously — Skeletal Snipers, Arsonists and Frost Mages all fire more projectiles, multiplying AoE and single-target output at once. Requires Breach Atlas investment and completing Origins of the Fortress to access the Genesis Tree.

**3. Main sceptre (WS1): % Increased Damage to Allies (prefix) + +Minion Skill Levels (suffix)**

Bases: Rattling Sceptre or Omen Sceptre. Target mod is +# to Level of all Minion Skills — it is a **suffix**. Use Omen of Dextral Exaltation to force Exalts into the suffix slot when hunting it. Use Essence of Command to lock % Increased Damage to Allies as the main prefix. % increased Spirit is the second most valuable prefix.

**4. Abyssal Eye socketable + Heart of the Well**

Amanamu's Gaze: up to +30% DoT Multiplier for minions. For Heart of the Well jewels, the Tier A priority for minion builds is defensive utility — crit mods do not propagate to minion damage in the current patch, so do not chase them.

**5. Pending gem upgrades**

Skeletal Reaver: Minion Splash I → II · Skeletal Frost Mage: Multishot I → II

---

## Crafting by Slot

| Slot | Prefix target | Suffix target | Strategy |
|---|---|---|---|
| Body Armour | T1 ES (ilvl varies — check PoE2DB) | Post-CI: elemental res or minion mod | Fracture T1 ES. Essence of Enhancement to lock it. Chaos res has no value post-CI |
| Sceptre WS1 | % Increased Damage to Allies + % Spirit | +Minion Skill Levels | Fracture +Minion Skill Levels. Essence of Command for % ally damage prefix. Omen of Dextral Exaltation to push Exalts into the suffix slot |
| Rings | ES | Elemental res | Chaos res irrelevant post-CI. Breach rings with minion projectile mod override everything else here |
| Amulet | Spirit + Life | +Minion Skill Levels | +Minion Skill Levels is a suffix. Divine if values are low; do not replace if mods are correct |
| Boots | ES | Movement Speed T1 (ilvl 82) | Essence of Enhancement to lock ES. Regal hunting movespeed |

---

# Part IV — Early Endgame (historical record)

> This section documents the path from campaign-end to a complete Atlas as it worked in 0.5. It does not apply to the current character (Atlas complete, 4 ascendancies taken) — it is kept as a record of the patch.

## Fortress Questline Path

Atlas progression in 0.5 happens inside the Precursor Fortress walls — normal mapping does not progress the Atlas. The path:

Rush the +1 tablet mod node at the centre of the Atlas tree (not the top). Grab all "Tablet" and "Waystone" nodes (Ctrl+F on the tree to highlight them). Unlock "Irradiated tablets can now drop" — they no longer drop by default.

Clear a corrupted tower area to unlock Doryani as a Master, which gives +1 revive (allowing 6-mod maps with 3 tablets and double the attempts). Stay in the Fortress until you reach T15 maps and roughly 50-100 Atlas points.

From there, either venture out into whichever mechanic with semi-decent Atlas bonuses, or finish the Arbiter of Divinity questline in the Fortress for +40 Atlas points and rush the top of the tree for 4-mod tablets. Later, hunt Matriarch/Patriarch citadels (red beams in the fog outside the walls) to fight Arbiter of Divinity repeatedly — roughly +40 Atlas points per kill — to complete the Atlas.

Waystone sustain: buy 3× T14 from Doryani and combine them into 1× T15 at the Reforging Bench if you run dry.

---

*Patch 0.5.2 — Runes of Aldur. Update on 0.6.*
