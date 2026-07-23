# Yester Hill Ritual Combat Cheat Sheet

## Battlefield Layout

- **Circle diameter:** ~250 ft (~125 ft radius)
- **Entry to mist edge:** ~60 ft (berserkers + druid assailants block here)
- **Shroud of mist:** 60 ft radius cylinder around statue, 150 ft tall, 6 in thick edges
- **Wall of roots:** 15 ft thick, 30 ft tall, inner edge 5 ft from the ritualist druids
- **Druids:** 13 naturalists encircle statue, each 10 ft from it; Svarog stands among them
- **Statue:** Center of circle, Huge size, 30 ft tall

---

## Initiative Timeline

### Every Round (Ritual Active)

| Init Count | Event |
|:---:|---|
| **20** | Wall segments regenerate 10 HP (if ≥1 HP and not in sunlight; suppressed if took radiant/fire last round) |
| **0** | Spirit guardians and similar start-of-turn effects damage the wall |
| End of round | If fewer than 12 druids chanting, roll d12. If result > chanting druids: all creatures inside wall make **DC 17 CON save** or take **7 (2d6) lightning** + dazed. 2nd trigger: **10 (3d6)**. 3rd trigger: **ritual ruined** |

### Ritual Disruption Sequence (after ritual ruined or gem retrieved)

| Init Count | Event |
|:---:|---|
| **20** (Round 1) | **Statue collapses.** Climbers: DC 10 DEX save or 1d6 bludgeoning + fall prone 30 ft from base. Svarog: 14 (4d6) bludgeoning, knocked prone + restrained |
| **10** (Round 2) | Raven swarms descend to carry players away (2 swarms per Medium creature, 1 per Small) |
| **0** (Round 3) | **All creatures within 30 ft of statue:** DC 17 CON save, **56 (16d6) lightning** on fail, half on success |

Ludmilla uses Dimension Door to escape on her next turn after disruption.

---

## Combatant Statblocks

### Ludmilla Vilisevic (Phase 1)

| | |
|---|---|
| **AC** | 15 (natural armor) |
| **HP** | 120 (16d8+48) |
| **Speed** | 30 ft (50 ft fly with shroud) |
| **Saves** | DEX +6, INT +7, WIS +3 |
| **Resist** | Necrotic; BPS from nonmagical weapons |
| **Prof** | +3 |

| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 16 (+3) | 16 (+3) | 16 (+3) | 18 (+4) | 10 (+0) | 12 (+1) |

**Passive Features:**
- **Devil's Sight** — 120 ft darkvision (magical + nonmagical)
- **Regeneration** — 10 HP/start of turn (blocked by radiant/holy water)
- **Spider Climb**
- **Sunlight Hypersensitivity** — 20 radiant/start of turn, disadv on attacks + checks
- **Fast Grappler** — no extra movement to drag grappled creatures

**Actions:**
- **Grease** — DC 15, 20-ft square
- **Command** — DC 15, up to 2 targets, 3-word command if within 10 ft of all
- **Hypnotic Pattern (2/day)** — DC 15
- **Dimension Door (1/day)**

**Bonus Actions:**
- **Shroud of Shadows (1/day)** — 50 ft fly (hover), reflects melee damage back. 1st radiant/holy water hit: fly drops to 25 ft + falls 20 ft. 2nd: shroud vanishes
- **Entangling Slime** — Casts Web (DC 15) on same area as Grease

**Reactions (3/round, 1/turn; losing reactions loses 1 instead):**
- **Misty Step** — trigger: takes damage
- **Disrupt Spell (3/day)** — 60 ft, caster of 3rd-level-or-lower spell makes DC 15 spellcasting save or spell fails
- **Mage's Reprisal** — trigger: missed by spell attack or saves vs spell. Caster makes DC 15 CON save or takes 7 (2d6) force
- **Contingency (1/day)** — trigger: would drop to 0 HP. Auto-Dimension Door (can't be countered). **She escapes the fight**

> **DM Notes:**
> - Opens with Grease → Entangling Slime combo, then Hypnotic Pattern once players escape
> - Swarms of ravens wake hypnotized PCs on init 20 of the following round
> - Shroud of Shadows reflects melee damage back to attacker (same amount + type)
> - Contingency = she teleports away at 0 HP. No phase 2 in this fight
> - Provokes Muriel on round 1 (see Muriel section)

**Scaling:**

| Players | HP | Mage's Reprisal |
|:---:|:---:|---|
| 3 | 84 | 5 (2d4) |
| 4 | 102 | 6 (1d12) |
| 5 | 120 | 7 (2d6) |
| 6 | 136 | 7 (2d6) |

---

### Druid Assailant (x2)

| | |
|---|---|
| **AC** | 11 (16 with Barkskin) |
| **HP** | 55 (10d8+10) |
| **Speed** | 30 ft |
| **Prof** | +2 |
| **Spell DC** | 12, +4 spell attacks |

| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 10 (+0) | 12 (+1) | 13 (+1) | 12 (+1) | 15 (+2) | 11 (+0) |

**Spells:**
- Cantrips: produce flame, shillelagh, thorn whip
- 1st (4 slots): faerie fire, longstrider, speak with animals, thunderwave
- 2nd (3 slots): barkskin, darkvision

**Actions:**
- **Multiattack** — 2x Quarterstaff
- **Quarterstaff** — +2 hit (+4 w/ shillelagh), 3 (1d6) or 6 (1d8+2) w/ shillelagh

**Bonus:** **Speed of the Adder** — Cast an action spell as bonus action (no other non-cantrip that turn)

**Reaction:** **Gift of the Gulthias** — When attacked, casts Barkskin (no concentration) if 2nd-level slot available

> **DM Notes:** Round 1: Faerie Fire (bonus) + Multiattack (action). Round 2: Thunderwave 2nd level (bonus) + Multiattack (action).

---

### Berserker (x2)

*Standard MM Berserker*

| | |
|---|---|
| **AC** | 13 (hide armor) |
| **HP** | 67 (9d8+27) |
| **Speed** | 30 ft |

| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 16 (+3) | 12 (+1) | 17 (+3) | 9 (-1) | 11 (+0) | 9 (-1) |

**Reckless** — Advantage on melee STR attacks this turn, attacks against it have advantage until next turn.

**Actions:**
- **Greataxe** — +5 to hit, 9 (1d12+3) slashing

---

### Svarog (Druid Naturalist with extras)

| | |
|---|---|
| **AC** | 11 (16 with Barkskin) |
| **HP** | 55 (10d8+10) |
| **Speed** | 30 ft (0 while ritualing; enters combat when PCs enter circle) |
| **Prof** | +2 |
| **Spell DC** | 12, +4 spell attacks |

| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 10 (+0) | 12 (+1) | 13 (+1) | 12 (+1) | 15 (+2) | 11 (+0) |

**Spells:**
- Cantrips: gust, infestation, produce flame
- 1st (4 slots): entangle, fog cloud, speak with animals, thunderwave
- 2nd (3 slots): barkskin, moonbeam

**Actions:**
- **Quarterstaff** — +2 to hit, 3 (1d6) bludgeoning
- **Gust of Wind** — (action)

**Bonus:** **Speed of the Adder** — Cast an action spell as bonus action

**Reaction:**
- **Gift of the Gulthias** — Barkskin when attacked (no concentration)
- **Bind Elements (3/day)** — 60 ft. When a creature casts a 3rd-level-or-lower spell dealing acid/cold/fire/lightning/thunder, force DC 12 spellcasting save. On fail: spell fizzles, Svarog gets orb. Next turn bonus action: ranged spell attack +5, 60 ft, 1d6 per spell level of absorbed type

> **DM Notes:**
> - Svarog wields Kavan's wand (raised the wall of roots)
> - Ceases chanting and enters combat when PCs enter the inner circle
> - If statue collapses: takes 14 (4d6) bludgeoning, prone + restrained
> - Druids won't cast thunderwave inside the circle (fear damaging statue)

---

### Druid Naturalist (x12, ritualists)

| | |
|---|---|
| **AC** | 11 (16 with Barkskin) |
| **HP** | 55 (10d8+10) |
| **Speed** | 0 (bound by roots during ritual) |

- **During ritual:** Action = chanting (requires concentration). No bonus actions or reactions
- Can be disrupted (break concentration like a spell)
- 12 rounds of chanting to complete the ritual

> **DM Notes:** These don't fight. They chant. Track how many are alive/chanting each round for the lightning check. If ritual completes → Wintersplinter is born.

---

## Obstacle Statblocks

### Shroud of Mist (Ludmilla's)

| | |
|---|---|
| **Shape** | Hollow cylinder, 60 ft radius, 150 ft tall, 6 in thick edges |
| **Duration** | 10 min or dismissed (bonus action); no concentration |
| **Interior** | Lightly obscured by faint mist |
| **Edges** | Opaque |

**On contact (1st time on a turn, non-undead):** DC 15 CON save or 10 (3d6) necrotic + slowed (extra ft per ft moved, attacks have advantage vs them, disadv on DEX saves)

> **DM Notes:** Necrotic damage inhibits Muriel's regeneration. She looks surprised when this happens.

---

### Wall of Roots

**Per Segment (5 ft x 5 ft x 5 ft):**

| | |
|---|---|
| **AC** | 15 |
| **HP** | 20 |
| **Vulnerability** | Radiant |
| **Immunity** | Piercing, Psychic |
| **Saves** | STR/CON +3; auto-fail DEX/INT/WIS/CHA |
| **Cover** | Full (opaque) |

**Regeneration (Init 20):** Regains 10 HP if ≥1 HP and not in sunlight. Suppressed if took radiant or fire damage last round.

**Wrathful Roots (outer edge only):** First time a non-Ludmilla creature moves along outer edge or ends turn there: DC 17 DEX save or grappled (escape DC 17) + 3 (1d6) bludgeoning + 7 (2d6) piercing per start of turn. Grappling roots: AC 15, 10 HP, vulnerable to radiant, immune to piercing/psychic.

**Moving through:** 4 ft movement per 1 ft. First time entering or ending turn inside: DC 17 DEX save, 7d8 slashing (half on save).

**Flying over (within 300 ft):** DC 17 DEX save or grappled + fall prone. Same damage as wrathful roots (1d6 bludg + 2d6 piercing/turn). Roots: AC 15, 20 HP, vuln radiant, immune piercing/psychic.

> **DM Notes:** Interior edges (corridors carved by PCs) do NOT trigger wrathful roots. Spirit guardians damages segments at init 0.

---

### Statue of Strahd

| | |
|---|---|
| **Size** | Huge, 30 ft tall |
| **HP (total)** | 100 |
| **Chest (gem location)** | AC 10, 10 HP, immune to poison + psychic |
| **Gem access** | Only after chest reduced to 0 HP |

> **DM Notes:** Gem is 30 ft up (climbing required). Statue collapses on init 20 after ritual disruption.

---

## Ally Statblocks

### Muriel Vinshaw (Wereraven)

| | |
|---|---|
| **AC** | 14 (leather armor) |
| **HP** | 63 (14d8) |
| **Speed** | 30 ft (fly 50 ft in hybrid/raven form) |
| **Prof** | +2 |

| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 10 (+0) | 16 (+3) | 11 (+0) | 13 (+1) | 15 (+2) | 14 (+2) |

- **Regeneration** — 10 HP/turn unless took necrotic or silvered weapon damage
- **Plummet** — Fly 20 ft straight + descending 5 ft, then hit with shortsword = +7 (2d6) piercing, target DC 12 STR or prone
- **Multiattack** — 2 attacks (1 can be hand crossbow)
- **Shortsword** — +5, 6 (1d6+3) piercing
- **Hand Crossbow** — +5, 30/120, 6 (1d6+3) piercing
- **Bonus:** **Shapechange** — hybrid/raven/human
- **Reaction:** **Interpose** — takes damage for adjacent ally

> **TRIGGER WARNING — Muriel's Rage:**
> - Ludmilla provokes Muriel on round 1. DC 25 Persuasion to calm her (no action)
> - If not calmed, Muriel transforms to hybrid and attacks Ludmilla
> - When Muriel takes piercing/slashing damage, blood spills onto the ground:
>   - Wall segments within 30 ft of her: **regain 10 HP** (even if regen suppressed)
>   - Destroyed segment squares: gain Spike Growth effect
>   - Spike Growth squares: replaced by wall segment with 5 HP
> - DC 20 Persuasion to stop her (adv if invoking Elric; auto-success if previously bonded over loss)
> - **Necrotic damage (from mist) blocks her regeneration**

---

### Ireena Kolyana

| | |
|---|---|
| **AC** | 15 (breastplate) |
| **HP** | 25 (5d8) |
| **Speed** | 30 ft |

| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 11 (+0) | 12 (+1) | 11 (+0) | 12 (+1) | 14 (+2) | 16 (+3) |

- **Rapier** — +3, 5 (1d8+1) slashing
- **Crossbow** — +3, 80/320, 5 (1d8+1) piercing
- **Bonus:** Helpful (Help as BA), Cunning Action (Dash/Disengage/Hide)
- **Reaction:** Parry (+2 AC vs one melee attack)
- **Healer** — Expend healer's kit use, target spends HD, regain roll + prof bonus (reroll 1s). Has 2 Healer's Kits

---

### Swarms of Ravens (allies, non-combatant)

- Wake hypnotized PCs on init 20 of the round after Hypnotic Pattern
- Carry PCs away from collapsing statue (init 10, round 2 of disruption): 2 swarms per Medium, 1 per Small

---

## Quick Reference: Ritual Countdown

Track druids chanting per round (start: 12, Svarog breaks off = 12 chanting initially):

| Round | Druids Chanting | Lightning Check? |
|:---:|:---:|---|
| 1-12 | Track kills/silences | If <12 chanting: roll d12, if result > chanters → lightning |

**Lightning escalation:** 1st = 2d6, 2nd = 3d6, 3rd = ritual destroyed

**Ritual completes** after 12 successful rounds → Wintersplinter born.

## Combat Flow Summary

1. **Conversation phase** — Ludmilla talks; berserkers + druid assailants approach over 2 rounds
2. **Ritual begins** — Lightning strikes, druids start chanting (12-round clock)
3. **Outer fight** — PCs vs 2 berserkers + 2 druid assailants (60 ft from mist)
4. **Shroud of mist** — DC 15 CON or 10 (3d6) necrotic + slowed
5. **Wall of roots** — Svarog raises it; PCs must breach/bypass
6. **Ludmilla engages** — Grease/Web combo → Hypnotic Pattern. Flies with shroud
7. **Inner circle** — Svarog fights; PCs can attack druids or climb statue for gem
8. **Win condition** — Retrieve gem OR disrupt ritual (3 lightning triggers)
9. **Disruption sequence** — 3-round countdown: statue falls → ravens rescue → 16d6 lightning explosion
