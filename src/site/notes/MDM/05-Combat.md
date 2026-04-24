---
{"dg-publish":true,"permalink":"/mdm/05-combat/","noteIcon":""}
---

# Combat

---

## Initiative

At the start of combat, everyone rolls **1d6**. This determines turn order. 

- Highest result goes first
- Ties: reroll between tied parties
- **One PC per round** may choose to defer their action to later in the order
- Monsters roll once per groups, not individually. "Boss" would get a separate roll.

---

## Taking Your Turn

On your turn you may:
- **Move** and **Act** (attack, cast, use item, etc.) in any order
- **Act only** (staying in place)
- **Defer** (pass now, act later — once per round per PC)

You choose whether to move before or after your action.

---

## Movement & Range Bands

MDM uses three range bands instead of a grid. The GM describes positioning; players describe intent.

| Band | Distance | To Enter |
|------|----------|----------|
| **Close** | Adjacent, engaged | Already there, or 1 move from Near |
| **Near** | Same area, ~10m | 1 move action from Close or Far |
| **Far** | Different area, ~30m+ | Full turn — no action this round |

**Key rules:**
- You can move one band and still act in the same turn
- Moving two bands (e.g. Far to Close) costs your full turn — no attack, no spell
- You choose whether to move before or after your action
- **Ranged weapons** can target Near and Far. **Melee weapons** require Close.
- **Thrown weapons** can target Near only.
- Spells specify range in their description; most offensive spells reach Near, zone spells affect Close.

> [!GM] Don't overthink positioning. If a player says "I close with the guard" and it's reasonable, it happens. Range bands exist to create meaningful choices — charging across a room vs. hanging back to shoot — not to adjudicate inches.

> [!PLAYTEST] Flag: Do range bands feel natural in play or do they create arguments? Watch for cases where Near/Close distinction matters most.

---

## Making an Attack

**Roll 3d6 under your DX** for the appropriate skill and you hit.

Modifiers to attacker DX:
- Shield (defender): see shield table
- Dim light or obscurement: -1 DX
- Prone target (melee): +2 DX
- Prone target (ranged): -2 DX
- Target at Far range: -1 DX

---

## Damage

On a hit, roll the weapon's damage dice. Apply flat damage — no stat modifiers added.

**Armor reduces damage** by its DR value (minimum 0 per hit).

---

## Melee Weapons

| Weapon | Damage | Min ST | Cost | Weight | Range | Notes |
|--------|--------|--------|------|--------|-------|-------|
| Dagger | 1d6 | ST 6 | 2sp | 0.5kg | Close/thrown Near | Concealable |
| Hand Axe | 1d6+1 | ST 8 | 4sp | 1.5kg | Close/thrown Near | |
| Short Sword | 1d6+1 | ST 8 | 6sp | 1kg | Close | |
| Short Bow | 1d6+1 | ST 8 | 5sp | 1kg | Near/Far | Arrows 1cp each |
| Spear | 2d6 | ST 9 | 3sp | 2kg | Close/thrown Near | Reach |
| Crossbow | 2d6+1 | ST 9 | 8sp | 3kg | Near/Far | 1 action to reload, bolts 1cp each |
| Broadsword | 2d6 | ST 10 | 1gp | 2kg | Close | |
| Mace | 2d6 | ST 10 | 8sp | 2.5kg | Close | |
| Battle Axe | 2d6+1 | ST 11 | 1gp | 3kg | Close | |
| Long Bow | 2d6 | ST 11 | 8sp | 1.5kg | Near/Far | Arrows 1cp each |
| Great Sword | 3d6 | ST 13 | 2gp | 4kg | Close | Two-handed |
| War Hammer | 3d6 | ST 13 | 2gp | 4.5kg | Close | Two-handed |

**Minimum ST:** A character without the required ST cannot wield the weapon effectively. They may attempt to use it at -2 DX.

---
**Ranged Weapons — Gunpowder & Energy**

| Weapon           | Damage | Min ST | Cost   | Weight | Range      | Notes                            |
| ---------------- | ------ | ------ | ------ | ------ | ---------- | -------------------------------- |
| Flintlock Pistol | 2d6    | ST 8   | Note A | 1kg    | Near       | 1 action to reload               |
| Sawn-Off Shotgun | 3d6    | ST 9   | Note A | 2kg    | Close only | -2 DX beyond Close               |
| Musket           | 2d6+1  | ST 10  | Note A | 4kg    | Near/Far   | 2 actions to reload              |
| Rifle            | 3d6    | ST 10  | Note A | 4kg    | Near/Far   | 1 action to reload               |
| Laser Pistol     | 2d6    | ST 7   | Note A | 0.5kg  | Near       | Ignores DR 1                     |
| Laser Rifle      | 3d6    | ST 9   | Note A | 2kg    | Near/Far   | Ignores DR 2                     |
| Plasma Pistol    | 2d6+2  | ST 8   | Note A | 1kg    | Near       | Zone on crit                     |
| Plasma Rifle     | 3d6+2  | ST 11  | Note A | 3kg    | Near/Far   | Zone on crit, ignores DR 1       |
| Pulse Cannon     | 4d6    | ST 13  | Note A | 6kg    | Near/Far   | Two-handed, 1 action to recharge |
| Disruptor        | 3d6    | ST 10  | Note A | 2kg    | Near       | Bypasses all DR                  |
| Phaser           | 12d6   | ST 8   | Note B | 2kg    | Near/Far   | Literally evaporates people      |

Note A - Requires Outsider Equipment disadvantage
Note B - Requires Outsider Extreme Equipment disadvantage


**Notes:**

- Gunpowder weapons can't fire in heavy rain without a Luck roll
- Energy weapons require power cells — 10 shots per cell
- "Ignores DR" means subtract that value from target's DR before applying damage

Want this merged into the main weapons table?


---

## Armor

| Armor | DR | Min ST | Cost | Weight |
|-------|----|--------|------|--------|
| Leather | 1 | ST 8 | 2gp | 5kg |
| Chain | 3 | ST 11 | 8gp | 15kg |
| Plate | 5 | ST 14 | 25gp | 25kg |

**Wearing armor above your ST minimum:**
You may wear armor with a higher ST requirement than you possess, but take **-1 DX per point of ST you fall short**.

| Shortfall | DX Penalty |
|-----------|------------|
| 1 ST | -1 DX |
| 2 ST | -2 DX |
| 3 ST | -3 DX (maximum) |
| 4+ ST | Cannot wear it |

**Armor — Modern & Advanced**

| Armor              | DR  | Min ST | Cost   | Weight | Notes                                      |
| ------------------ | --- | ------ | ------ | ------ | ------------------------------------------ |
| Kevlar Vest        | 2   | ST 7   | Note A | 3kg    | Concealable under clothing                 |
| Tactical Vest      | 3   | ST 9   | Note A | 6kg    | Has equipment slots                        |
| Riot Armor         | 4   | ST 11  | Note A | 12kg   |                                            |
| Military Plate     | 5   | ST 13  | Note A | 20kg   |                                            |
| Powered Exosuit    | 6   | ST 8   | Note A | 35kg   | ST requirement is suit's, not wearer's     |
| Energy Shield Belt | 3   | ST 7   | Note A | 0.5kg  | vs energy only; 10 charges, 1/hit          |
| Ablative Plating   | 4   | ST 10  | Note A | 8kg    | Degrades — loses 1 DR per 3 hits           |
| Stealth Suit       | 1   | ST 7   | Note A | 2kg    | -2 DX to attackers who haven't spotted you |

**Notes:**

- Kevlar and Tactical Vest: mages can wear these — no metal
- Powered Exosuit: wearer uses suit's ST for carrying capacity
- Energy Shield Belt: stacks with worn armor; energy damage only

Want this merged into the main armor table, or keep fantasy and modern/sci-fi separate?



> [!PLAYTEST] Flag: Does the armor ST penalty rule create interesting decisions or just frustration?

---

## Shields

| Shield | Attacker DX Penalty | Min ST | Cost | Weight | Notes |
|--------|-------------------|--------|------|--------|-------|
| Buckler | -1 | ST 8 | 1sp | 1kg | |
| Round | -2 | ST 10 | 3sp | 3kg | |
| Kite | -3 | ST 12 | 6sp | 5kg | |
| Tower | -4 | ST 14 | 1gp | 8kg | -1 bearer DX, two-handed, max dagger only |

Shield penalty applies to the attacker's DX roll, making hits harder.

---

## Damage & Death

| HP | State |
|----|-------|
| 1+ | Active |
| 0 | Unconscious, bleeding 1 HP/turn |
| Negative ST value | Dead |

**Stabilizing:** Any character adjacent (Close) to a downed ally may use their action to stabilize them (Medicine skill or Stabilize spell). Stops the bleed. Does not restore HP.

---

## Encumbrance

| Load | Limit | Effect |
|------|-------|--------|
| Light | ST x2 kg | No penalty |
| Medium | ST x3 kg | -1 DX |
| Heavy | ST x4 kg | -2 DX |
| Overloaded | Beyond heavy | -4 DX, move only |

> [!PLAYTEST] Flag: Encumbrance may be simplified or removed after playtesting. Track it once and see if it adds anything.

pc0607