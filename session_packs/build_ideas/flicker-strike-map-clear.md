# Build Idea Pack — Flicker Strike Map Clear (CI Monk)

- Generated UTC: `2026-08-29T15:03:48+00:00`
- Idea slug: `flicker-strike-map-clear`
- Purpose: Engineer and optimize Flicker Strike as a primary map-clear skill for a CI Energy Shield Monk, focused on charge-fed teleport-strike clear speed, AoE coverage, and support gem selection aligned to clearing rather than bossing.
- Keywords: `flicker strike, teleport, charge, power charge, charge profusion, perpetual charge, combo, culmination, ailith's chimes, shattering palm, killing palm, monk, martial artist, cold, conversion, energy shield, chaos inoculation, area, aoe, radius, close combat, concentrated area, blindside, blind, cooldown, clear, map, controller, ps5`
- Max matched records per index: `120`
- Total included matches: `724`


## Claude usage rules

- Treat this as the active focused data pack for this build idea.
- This is not the full PoE2 database.
- If a needed passive, gem, item base, mod, rune, unique, or interaction is missing, ask the user to expand this idea's keywords in `build_ideas.json` and regenerate the pack.
- Do not invent mechanics or records not present in this pack, the build documents, screenshots, or user-provided tests.

## Passive key nodes

- Source: `build_knowledge/compact/passive_tree_key_nodes.json`
- Matches included: `120`

### 1. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 21327
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"21327","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["56876"]}
```

### 2. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 2995
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["30% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"2995","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["30% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["2516"]}
```

### 3. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 46380
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"46380","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["21327"]}
```

### 4. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 56876
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"56876","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["46380"]}
```

### 5. Power Charge Duration and Energy Shield

- Match score: `105`
- `id`: 13777
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"13777","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["38532"]}
```

### 6. Power Charge Duration and Energy Shield

- Match score: `105`
- `id`: 20791
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"20791","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["13777","11741"]}
```

### 7. Additional Power Charge Chance

- Match score: `70`
- `id`: 36643
- `n`: Additional Power Charge Chance
- `t`: small
- `sd`: ["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"]

```json
{"id":"36643","n":"Additional Power Charge Chance","t":"small","sd":["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"],"out":["1739"]}
```

### 8. Attack Area and Combo

- Match score: `70`
- `id`: 24883
- `n`: Attack Area and Combo
- `t`: small
- `sd`: ["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"]

```json
{"id":"24883","n":"Attack Area and Combo","t":"small","sd":["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"],"out":["44573"]}
```

### 9. Attack Area and Combo

- Match score: `70`
- `id`: 26211
- `n`: Attack Area and Combo
- `t`: small
- `sd`: ["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"]

```json
{"id":"26211","n":"Attack Area and Combo","t":"small","sd":["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"],"out":["24883"]}
```

### 10. Attack Area and Combo

- Match score: `70`
- `id`: 55377
- `n`: Attack Area and Combo
- `t`: small
- `sd`: ["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"]

```json
{"id":"55377","n":"Attack Area and Combo","t":"small","sd":["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"],"out":["26211","33463"]}
```

### 11. Critical Damage when consuming a Power Charge

- Match score: `70`
- `id`: 30615
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"30615","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]}
```

### 12. Critical Damage when consuming a Power Charge

- Match score: `70`
- `id`: 3336
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"3336","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["30615"]}
```

### 13. Critical Damage when consuming a Power Charge

- Match score: `70`
- `id`: 36231
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"36231","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["3336","31765"]}
```

### 14. Energy Shield Recharge Rate

- Match score: `70`
- `id`: 27686
- `n`: Energy Shield Recharge Rate
- `t`: small
- `sd`: ["20% increased [ESRechargeRate|Energy Shield Recharge Rate]"]

```json
{"id":"27686","n":"Energy Shield Recharge Rate","t":"small","sd":["20% increased [ESRechargeRate|Energy Shield Recharge Rate]"],"out":["12876"]}
```

### 15. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `70`
- `id`: 13228
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"13228","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["43486"]}
```

### 16. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `70`
- `id`: 39102
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"39102","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["13228"]}
```

### 17. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `70`
- `id`: 43486
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"43486","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["54289","39102"]}
```

### 18. Infusion and Power Charge Duration

- Match score: `70`
- `id`: 44188
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"44188","n":"Infusion and Power Charge Duration","t":"small","sd":["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["64427"]}
```

### 19. Infusion and Power Charge Duration

- Match score: `70`
- `id`: 51892
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"51892","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["59387","64427","44188"]}
```

### 20. Infusion and Power Charge Duration

- Match score: `70`
- `id`: 64427
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"64427","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]}
```

### 21. Power Charge Duration

- Match score: `70`
- `id`: 24812
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"24812","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["64643"]}
```

### 22. Power Charge Duration

- Match score: `70`
- `id`: 56360
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"56360","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["24812"]}
```

### 23. Power Charge Duration

- Match score: `70`
- `id`: 64643
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"64643","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["56360","27176"]}
```

### 24. Power Charge Mastery

- Match score: `70`
- `id`: 10162
- `n`: Power Charge Mastery
- `t`: small

```json
{"id":"10162","n":"Power Charge Mastery","t":"small"}
```

### 25. Power Charge Mastery

- Match score: `70`
- `id`: 31779
- `n`: Power Charge Mastery
- `t`: small

```json
{"id":"31779","n":"Power Charge Mastery","t":"small"}
```

### 26. Recover Mana on consuming Power Charge

- Match score: `70`
- `id`: 25890
- `n`: Recover Mana on consuming Power Charge
- `t`: small
- `sd`: ["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"]

```json
{"id":"25890","n":"Recover Mana on consuming Power Charge","t":"small","sd":["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"],"out":["54378"]}
```

### 27. Recover Mana on consuming Power Charge

- Match score: `70`
- `id`: 26863
- `n`: Recover Mana on consuming Power Charge
- `t`: small
- `sd`: ["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"]

```json
{"id":"26863","n":"Recover Mana on consuming Power Charge","t":"small","sd":["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"],"out":["25890","58198"]}
```

### 28. Recover Mana on consuming Power Charge

- Match score: `70`
- `id`: 54378
- `n`: Recover Mana on consuming Power Charge
- `t`: small
- `sd`: ["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"]

```json
{"id":"54378","n":"Recover Mana on consuming Power Charge","t":"small","sd":["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"],"out":["26863"]}
```

### 29. Shapeshifted Energy Shield Recharge

- Match score: `70`
- `id`: 41609
- `n`: Shapeshifted Energy Shield Recharge
- `t`: small
- `sd`: ["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]

```json
{"id":"41609","n":"Shapeshifted Energy Shield Recharge","t":"small","sd":["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]}
```

### 30. Shapeshifted Energy Shield Recharge

- Match score: `70`
- `id`: 541
- `n`: Shapeshifted Energy Shield Recharge
- `t`: small
- `sd`: ["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]

```json
{"id":"541","n":"Shapeshifted Energy Shield Recharge","t":"small","sd":["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]}
```

### 31. Armour and Energy Shield

- Match score: `45`
- `id`: 10824
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"10824","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["49734"]}
```

### 32. Armour and Energy Shield

- Match score: `45`
- `id`: 25648
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"25648","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["10824","58894","45736"]}
```

### 33. Armour and Energy Shield

- Match score: `45`
- `id`: 26592
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"26592","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["58894"]}
```

### 34. Armour and Energy Shield

- Match score: `45`
- `id`: 31290
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"31290","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32474","60332","32764","37609"]}
```

### 35. Armour and Energy Shield

- Match score: `45`
- `id`: 43077
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"43077","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["26592","43250"]}
```

### 36. Armour and Energy Shield

- Match score: `45`
- `id`: 45736
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"45736","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["15825"]}
```

### 37. Armour and Energy Shield

- Match score: `45`
- `id`: 60332
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"60332","n":"Armour and Energy Shield","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["21213"]}
```

### 38. Armour and Energy Shield Delay

- Match score: `45`
- `id`: 44213
- `n`: Armour and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"44213","n":"Armour and Energy Shield Delay","t":"small","sd":["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["869"]}
```

### 39. Armour and Energy Shield Delay

- Match score: `45`
- `id`: 869
- `n`: Armour and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"869","n":"Armour and Energy Shield Delay","t":"small","sd":["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["18959"]}
```

### 40. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 32964
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"32964","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["34617"]}
```

### 41. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 40377
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"40377","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["46318","7554","46628"]}
```

### 42. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 41384
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"41384","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51672"]}
```

### 43. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 46318
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"46318","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32964"]}
```

### 44. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 51672
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"51672","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["31955"]}
```

### 45. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 65509
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"65509","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["41384","51821"]}
```

### 46. Charge Duration

- Match score: `45`
- `id`: 19027
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"19027","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["21156","7847"]}
```

### 47. Charge Duration

- Match score: `45`
- `id`: 21156
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"21156","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["34623"]}
```

### 48. Charge Duration and Dexterity

- Match score: `45`
- `id`: 34623
- `n`: Charge Duration and Dexterity
- `t`: small
- `sd`: ["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"]

```json
{"id":"34623","n":"Charge Duration and Dexterity","t":"small","sd":["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"],"out":["14769","14262"]}
```

### 49. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 15343
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"15343","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["58692"]}
```

### 50. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 21227
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"21227","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["36290"]}
```

### 51. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 23046
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"23046","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["47976"]}
```

### 52. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 26556
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"26556","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["58692","59657"]}
```

### 53. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 28464
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"28464","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["8908"]}
```

### 54. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 3203
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"3203","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["30562","28464"]}
```

### 55. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 36290
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"36290","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["23046"]}
```

### 56. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 47831
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"47831","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["8734","49996"]}
```

### 57. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 51040
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"51040","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["9652"]}
```

### 58. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 58692
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"58692","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 59. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 58779
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"58779","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51040","327","23822","47976"]}
```

### 60. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 13359
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"13359","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["31943"]}
```

### 61. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 31943
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"31943","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["8382"]}
```

### 62. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 61863
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"61863","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["42045"]}
```

### 63. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 8382
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"8382","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["61863"]}
```

### 64. Energy Shield Delay

- Match score: `45`
- `id`: 14739
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"14739","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["49235"]}
```

### 65. Energy Shield Delay

- Match score: `45`
- `id`: 21404
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"21404","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["42825"]}
```

### 66. Energy Shield Delay

- Match score: `45`
- `id`: 22691
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"22691","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["39037","61027"]}
```

### 67. Energy Shield Delay

- Match score: `45`
- `id`: 25893
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"25893","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51169"]}
```

### 68. Energy Shield Delay

- Match score: `45`
- `id`: 27671
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"27671","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32681"]}
```

### 69. Energy Shield Delay

- Match score: `45`
- `id`: 27674
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"27674","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["44082"]}
```

### 70. Energy Shield Delay

- Match score: `45`
- `id`: 29695
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"29695","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 71. Energy Shield Delay

- Match score: `45`
- `id`: 30634
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"30634","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 72. Energy Shield Delay

- Match score: `45`
- `id`: 31630
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"31630","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["64474"]}
```

### 73. Energy Shield Delay

- Match score: `45`
- `id`: 31644
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"31644","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["14739","34058"]}
```

### 74. Energy Shield Delay

- Match score: `45`
- `id`: 3628
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"3628","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["64474","3251"]}
```

### 75. Energy Shield Delay

- Match score: `45`
- `id`: 36746
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"36746","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["40691"]}
```

### 76. Energy Shield Delay

- Match score: `45`
- `id`: 40691
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"40691","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["25893"]}
```

### 77. Energy Shield Delay

- Match score: `45`
- `id`: 42825
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"42825","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["31238"]}
```

### 78. Energy Shield Delay

- Match score: `45`
- `id`: 43736
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"43736","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["29695"]}
```

### 79. Energy Shield Delay

- Match score: `45`
- `id`: 44082
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"44082","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["4931"]}
```

### 80. Energy Shield Delay

- Match score: `45`
- `id`: 46857
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 4% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","5% increased Mana Cost [Efficiency]"]

```json
{"id":"46857","n":"Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 4% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","5% increased Mana Cost [Efficiency]"],"out":["52971"]}
```

### 81. Energy Shield Delay

- Match score: `45`
- `id`: 4748
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"4748","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["2254"]}
```

### 82. Energy Shield Delay

- Match score: `45`
- `id`: 49235
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"49235","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["42077"]}
```

### 83. Energy Shield Delay

- Match score: `45`
- `id`: 52743
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"52743","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["34541"]}
```

### 84. Energy Shield Delay

- Match score: `45`
- `id`: 64474
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"64474","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 85. Energy Shield Delay

- Match score: `45`
- `id`: 65437
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"65437","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["63064"]}
```

### 86. Energy Shield Delay

- Match score: `45`
- `id`: 8734
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"8734","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["52743"]}
```

### 87. Energy Shield Delay and Armour Applies to Elemental Damage

- Match score: `45`
- `id`: 23039
- `n`: Energy Shield Delay and Armour Applies to Elemental Damage
- `t`: small
- `sd`: ["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"23039","n":"Energy Shield Delay and Armour Applies to Elemental Damage","t":"small","sd":["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["64770"]}
```

### 88. Energy Shield Delay and Armour Applies to Elemental Damage

- Match score: `45`
- `id`: 7554
- `n`: Energy Shield Delay and Armour Applies to Elemental Damage
- `t`: small
- `sd`: ["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"7554","n":"Energy Shield Delay and Armour Applies to Elemental Damage","t":"small","sd":["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["23039"]}
```

### 89. Energy Shield Delay while Shapeshifted

- Match score: `45`
- `id`: 31673
- `n`: Energy Shield Delay while Shapeshifted
- `t`: small
- `sd`: ["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]

```json
{"id":"31673","n":"Energy Shield Delay while Shapeshifted","t":"small","sd":["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"],"out":["48649"]}
```

### 90. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 32681
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"32681","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32664","38668"]}
```

### 91. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 3630
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"3630","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["62624"]}
```

### 92. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 45631
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"45631","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["3630"]}
```

### 93. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 5188
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"5188","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["27671","38668","24165"]}
```

### 94. Rapid Recharge

- Match score: `45`
- `id`: 17973
- `n`: Rapid Recharge
- `t`: notable
- `sd`: ["12% increased [ESRechargeRate|Energy Shield Recharge Rate]","12% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"17973","n":"Rapid Recharge","t":"notable","sd":["12% increased [ESRechargeRate|Energy Shield Recharge Rate]","12% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["4748","22691"]}
```

### 95. Shapeshifted Energy Shield Delay

- Match score: `45`
- `id`: 27216
- `n`: Shapeshifted Energy Shield Delay
- `t`: small
- `sd`: ["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]

```json
{"id":"27216","n":"Shapeshifted Energy Shield Delay","t":"small","sd":["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"],"out":["30546"]}
```

### 96. Shapeshifted Energy Shield Delay

- Match score: `45`
- `id`: 31010
- `n`: Shapeshifted Energy Shield Delay
- `t`: small
- `sd`: ["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]

```json
{"id":"31010","n":"Shapeshifted Energy Shield Delay","t":"small","sd":["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]}
```

### 97. Cirel of Tarth's Light

- Match score: `40`
- `id`: 21213
- `n`: Cirel of Tarth's Light
- `t`: notable
- `sd`: ["+10% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","10% increased [LightRadius|Light Radius]","10% increased [Accuracy] Rating","10% increased Area of Effect"]

```json
{"id":"21213","n":"Cirel of Tarth's Light","t":"notable","sd":["+10% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","10% increased [LightRadius|Light Radius]","10% increased [Accuracy] Rating","10% increased Area of Effect"]}
```

### 98. Ailment Threshold from Energy Shield

- Match score: `35`
- `id`: 59798
- `n`: Ailment Threshold from Energy Shield
- `t`: small
- `sd`: ["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"]

```json
{"id":"59798","n":"Ailment Threshold from Energy Shield","t":"small","sd":["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"],"out":["5335"]}
```

### 99. Ancestral Boosted Area and Damage

- Match score: `35`
- `id`: 18207
- `n`: Ancestral Boosted Area and Damage
- `t`: small
- `sd`: ["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"]

```json
{"id":"18207","n":"Ancestral Boosted Area and Damage","t":"small","sd":["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"],"out":["53261"]}
```

### 100. Ancestral Boosted Area and Damage

- Match score: `35`
- `id`: 30780
- `n`: Ancestral Boosted Area and Damage
- `t`: small
- `sd`: ["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"]

```json
{"id":"30780","n":"Ancestral Boosted Area and Damage","t":"small","sd":["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"],"out":["17112","5410"]}
```

### 101. Ancestral Boosted Area and Damage

- Match score: `35`
- `id`: 53261
- `n`: Ancestral Boosted Area and Damage
- `t`: small
- `sd`: ["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"]

```json
{"id":"53261","n":"Ancestral Boosted Area and Damage","t":"small","sd":["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"],"out":["30780"]}
```

### 102. Area and Presence

- Match score: `35`
- `id`: 23364
- `n`: Area and Presence
- `t`: small
- `sd`: ["9% increased [Presence|Presence] Area of Effect","3% increased Area of Effect"]

```json
{"id":"23364","n":"Area and Presence","t":"small","sd":["9% increased [Presence|Presence] Area of Effect","3% increased Area of Effect"],"out":["33781","48614"]}
```

### 103. Area and Presence

- Match score: `35`
- `id`: 33781
- `n`: Area and Presence
- `t`: small
- `sd`: ["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"]

```json
{"id":"33781","n":"Area and Presence","t":"small","sd":["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"],"out":["65493"]}
```

### 104. Area and Presence

- Match score: `35`
- `id`: 48614
- `n`: Area and Presence
- `t`: small
- `sd`: ["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"]

```json
{"id":"48614","n":"Area and Presence","t":"small","sd":["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"],"out":["9018"]}
```

### 105. Area and Presence

- Match score: `35`
- `id`: 65493
- `n`: Area and Presence
- `t`: small
- `sd`: ["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"]

```json
{"id":"65493","n":"Area and Presence","t":"small","sd":["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"],"out":["43854"]}
```

### 106. Area and Presence

- Match score: `35`
- `id`: 9018
- `n`: Area and Presence
- `t`: small
- `sd`: ["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"]

```json
{"id":"9018","n":"Area and Presence","t":"small","sd":["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"],"out":["35918"]}
```

### 107. Area Damage

- Match score: `35`
- `id`: 1170
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"1170","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["58295"]}
```

### 108. Area Damage

- Match score: `35`
- `id`: 19277
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Spell] Area Damage"]

```json
{"id":"19277","n":"Area Damage","t":"small","sd":["10% increased [Spell] Area Damage"],"out":["44783"]}
```

### 109. Area Damage

- Match score: `35`
- `id`: 20645
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"20645","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["64284"]}
```

### 110. Area Damage

- Match score: `35`
- `id`: 36737
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased Area Damage"]

```json
{"id":"36737","n":"Area Damage","t":"small","sd":["10% increased Area Damage"],"out":["7542"]}
```

### 111. Area Damage

- Match score: `35`
- `id`: 3999
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"3999","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["37665","57863"]}
```

### 112. Area Damage

- Match score: `35`
- `id`: 41126
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"41126","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["1170","9918"]}
```

### 113. Area Damage

- Match score: `35`
- `id`: 44783
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Spell] Area Damage"]

```json
{"id":"44783","n":"Area Damage","t":"small","sd":["10% increased [Spell] Area Damage"],"out":["22949"]}
```

### 114. Area Damage

- Match score: `35`
- `id`: 53443
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"53443","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["5710","59767"]}
```

### 115. Area Damage

- Match score: `35`
- `id`: 57405
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"57405","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["64807"]}
```

### 116. Area Damage

- Match score: `35`
- `id`: 59480
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"59480","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["3999"]}
```

### 117. Area Damage

- Match score: `35`
- `id`: 61362
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased Area Damage"]

```json
{"id":"61362","n":"Area Damage","t":"small","sd":["10% increased Area Damage"],"out":["36737"]}
```

### 118. Area Damage

- Match score: `35`
- `id`: 9918
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"9918","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["16626"]}
```

### 119. Area Damage and Armour Break

- Match score: `35`
- `id`: 37665
- `n`: Area Damage and Armour Break
- `t`: small
- `sd`: ["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"]

```json
{"id":"37665","n":"Area Damage and Armour Break","t":"small","sd":["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"],"out":["35739"]}
```

### 120. Area Damage and Armour Break

- Match score: `35`
- `id`: 42410
- `n`: Area Damage and Armour Break
- `t`: small
- `sd`: ["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"]

```json
{"id":"42410","n":"Area Damage and Armour Break","t":"small","sd":["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"],"out":["9737"]}
```

## Passive full compact

- Source: `build_knowledge/compact/passive_tree_full_compact.json`
- Matches included: `120`

### 1. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 21327
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"21327","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["56876"]}
```

### 2. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 2995
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["30% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"2995","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["30% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["2516"]}
```

### 3. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 46380
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"46380","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["21327"]}
```

### 4. Energy Shield if Consumed Power Charge

- Match score: `105`
- `id`: 56876
- `n`: Energy Shield if Consumed Power Charge
- `t`: small
- `sd`: ["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"56876","n":"Energy Shield if Consumed Power Charge","t":"small","sd":["20% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["46380"]}
```

### 5. Power Charge Duration and Energy Shield

- Match score: `105`
- `id`: 13777
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"13777","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["38532"]}
```

### 6. Power Charge Duration and Energy Shield

- Match score: `105`
- `id`: 20791
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"20791","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["13777","11741"]}
```

### 7. Additional Power Charge Chance

- Match score: `70`
- `id`: 36643
- `n`: Additional Power Charge Chance
- `t`: small
- `sd`: ["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"]

```json
{"id":"36643","n":"Additional Power Charge Chance","t":"small","sd":["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"],"out":["1739"]}
```

### 8. Attack Area and Combo

- Match score: `70`
- `id`: 24883
- `n`: Attack Area and Combo
- `t`: small
- `sd`: ["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"]

```json
{"id":"24883","n":"Attack Area and Combo","t":"small","sd":["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"],"out":["44573"]}
```

### 9. Attack Area and Combo

- Match score: `70`
- `id`: 26211
- `n`: Attack Area and Combo
- `t`: small
- `sd`: ["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"]

```json
{"id":"26211","n":"Attack Area and Combo","t":"small","sd":["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"],"out":["24883"]}
```

### 10. Attack Area and Combo

- Match score: `70`
- `id`: 55377
- `n`: Attack Area and Combo
- `t`: small
- `sd`: ["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"]

```json
{"id":"55377","n":"Attack Area and Combo","t":"small","sd":["4% increased Area of Effect for [Attack|Attacks]","5% Chance to build an additional [Combo] on [HitDamage|Hit]"],"out":["26211","33463"]}
```

### 11. Critical Damage when consuming a Power Charge

- Match score: `70`
- `id`: 30615
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"30615","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]}
```

### 12. Critical Damage when consuming a Power Charge

- Match score: `70`
- `id`: 3336
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"3336","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["30615"]}
```

### 13. Critical Damage when consuming a Power Charge

- Match score: `70`
- `id`: 36231
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"36231","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["3336","31765"]}
```

### 14. Energy Shield Recharge Rate

- Match score: `70`
- `id`: 27686
- `n`: Energy Shield Recharge Rate
- `t`: small
- `sd`: ["20% increased [ESRechargeRate|Energy Shield Recharge Rate]"]

```json
{"id":"27686","n":"Energy Shield Recharge Rate","t":"small","sd":["20% increased [ESRechargeRate|Energy Shield Recharge Rate]"],"out":["12876"]}
```

### 15. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `70`
- `id`: 13228
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"13228","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["43486"]}
```

### 16. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `70`
- `id`: 39102
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"39102","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["13228"]}
```

### 17. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `70`
- `id`: 43486
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"43486","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["54289","39102"]}
```

### 18. Infusion and Power Charge Duration

- Match score: `70`
- `id`: 44188
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"44188","n":"Infusion and Power Charge Duration","t":"small","sd":["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["64427"]}
```

### 19. Infusion and Power Charge Duration

- Match score: `70`
- `id`: 51892
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"51892","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["59387","64427","44188"]}
```

### 20. Infusion and Power Charge Duration

- Match score: `70`
- `id`: 64427
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"64427","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]}
```

### 21. Power Charge Duration

- Match score: `70`
- `id`: 24812
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"24812","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["64643"]}
```

### 22. Power Charge Duration

- Match score: `70`
- `id`: 56360
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"56360","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["24812"]}
```

### 23. Power Charge Duration

- Match score: `70`
- `id`: 64643
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"64643","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["56360","27176"]}
```

### 24. Power Charge Mastery

- Match score: `70`
- `id`: 10162
- `n`: Power Charge Mastery
- `t`: small

```json
{"id":"10162","n":"Power Charge Mastery","t":"small"}
```

### 25. Power Charge Mastery

- Match score: `70`
- `id`: 31779
- `n`: Power Charge Mastery
- `t`: small

```json
{"id":"31779","n":"Power Charge Mastery","t":"small"}
```

### 26. Recover Mana on consuming Power Charge

- Match score: `70`
- `id`: 25890
- `n`: Recover Mana on consuming Power Charge
- `t`: small
- `sd`: ["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"]

```json
{"id":"25890","n":"Recover Mana on consuming Power Charge","t":"small","sd":["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"],"out":["54378"]}
```

### 27. Recover Mana on consuming Power Charge

- Match score: `70`
- `id`: 26863
- `n`: Recover Mana on consuming Power Charge
- `t`: small
- `sd`: ["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"]

```json
{"id":"26863","n":"Recover Mana on consuming Power Charge","t":"small","sd":["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"],"out":["25890","58198"]}
```

### 28. Recover Mana on consuming Power Charge

- Match score: `70`
- `id`: 54378
- `n`: Recover Mana on consuming Power Charge
- `t`: small
- `sd`: ["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"]

```json
{"id":"54378","n":"Recover Mana on consuming Power Charge","t":"small","sd":["Recover 2% of maximum Mana when you consume a [Charges|Power Charge]"],"out":["26863"]}
```

### 29. Shapeshifted Energy Shield Recharge

- Match score: `70`
- `id`: 41609
- `n`: Shapeshifted Energy Shield Recharge
- `t`: small
- `sd`: ["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]

```json
{"id":"41609","n":"Shapeshifted Energy Shield Recharge","t":"small","sd":["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]}
```

### 30. Shapeshifted Energy Shield Recharge

- Match score: `70`
- `id`: 541
- `n`: Shapeshifted Energy Shield Recharge
- `t`: small
- `sd`: ["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]

```json
{"id":"541","n":"Shapeshifted Energy Shield Recharge","t":"small","sd":["15% increased [ESRechargeRate|Energy Shield Recharge Rate] while [Shapeshift|Shapeshifted]"]}
```

### 31. Armour and Energy Shield

- Match score: `45`
- `id`: 10824
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"10824","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["49734"]}
```

### 32. Armour and Energy Shield

- Match score: `45`
- `id`: 25648
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"25648","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["10824","58894","45736"]}
```

### 33. Armour and Energy Shield

- Match score: `45`
- `id`: 26592
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"26592","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["58894"]}
```

### 34. Armour and Energy Shield

- Match score: `45`
- `id`: 31290
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"31290","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32474","60332","32764","37609"]}
```

### 35. Armour and Energy Shield

- Match score: `45`
- `id`: 43077
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"43077","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["26592","43250"]}
```

### 36. Armour and Energy Shield

- Match score: `45`
- `id`: 45736
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"45736","n":"Armour and Energy Shield","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["15825"]}
```

### 37. Armour and Energy Shield

- Match score: `45`
- `id`: 60332
- `n`: Armour and Energy Shield
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"60332","n":"Armour and Energy Shield","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["21213"]}
```

### 38. Armour and Energy Shield Delay

- Match score: `45`
- `id`: 44213
- `n`: Armour and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"44213","n":"Armour and Energy Shield Delay","t":"small","sd":["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["869"]}
```

### 39. Armour and Energy Shield Delay

- Match score: `45`
- `id`: 869
- `n`: Armour and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"869","n":"Armour and Energy Shield Delay","t":"small","sd":["12% increased [Armour]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["18959"]}
```

### 40. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 32964
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"32964","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["34617"]}
```

### 41. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 40377
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"40377","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["46318","7554","46628"]}
```

### 42. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 41384
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"41384","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51672"]}
```

### 43. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 46318
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"46318","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32964"]}
```

### 44. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 51672
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"51672","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["31955"]}
```

### 45. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 65509
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"65509","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["41384","51821"]}
```

### 46. Charge Duration

- Match score: `45`
- `id`: 19027
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"19027","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["21156","7847"]}
```

### 47. Charge Duration

- Match score: `45`
- `id`: 21156
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"21156","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["34623"]}
```

### 48. Charge Duration and Dexterity

- Match score: `45`
- `id`: 34623
- `n`: Charge Duration and Dexterity
- `t`: small
- `sd`: ["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"]

```json
{"id":"34623","n":"Charge Duration and Dexterity","t":"small","sd":["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"],"out":["14769","14262"]}
```

### 49. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 15343
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"15343","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["58692"]}
```

### 50. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 21227
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"21227","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["36290"]}
```

### 51. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 23046
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"23046","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["47976"]}
```

### 52. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 26556
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"26556","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["58692","59657"]}
```

### 53. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 28464
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"28464","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["8908"]}
```

### 54. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 3203
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"3203","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["30562","28464"]}
```

### 55. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 36290
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"36290","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["23046"]}
```

### 56. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 47831
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"47831","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["8734","49996"]}
```

### 57. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 51040
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"51040","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["9652"]}
```

### 58. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 58692
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"58692","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 59. Deflection and Energy Shield Delay

- Match score: `45`
- `id`: 58779
- `n`: Deflection and Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"58779","n":"Deflection and Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 5% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51040","327","23822","47976"]}
```

### 60. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 13359
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"13359","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["31943"]}
```

### 61. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 31943
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"31943","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["8382"]}
```

### 62. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 61863
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"61863","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["42045"]}
```

### 63. Elemental Damage and Energy Shield Delay

- Match score: `45`
- `id`: 8382
- `n`: Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"]

```json
{"id":"8382","n":"Elemental Damage and Energy Shield Delay","t":"small","sd":["4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","8% increased [ElementalDamage|Elemental Damage]"],"out":["61863"]}
```

### 64. Energy Shield Delay

- Match score: `45`
- `id`: 14739
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"14739","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["49235"]}
```

### 65. Energy Shield Delay

- Match score: `45`
- `id`: 21404
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"21404","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["42825"]}
```

### 66. Energy Shield Delay

- Match score: `45`
- `id`: 22691
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"22691","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["39037","61027"]}
```

### 67. Energy Shield Delay

- Match score: `45`
- `id`: 25893
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"25893","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51169"]}
```

### 68. Energy Shield Delay

- Match score: `45`
- `id`: 27671
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"27671","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32681"]}
```

### 69. Energy Shield Delay

- Match score: `45`
- `id`: 27674
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"27674","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["44082"]}
```

### 70. Energy Shield Delay

- Match score: `45`
- `id`: 29695
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"29695","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 71. Energy Shield Delay

- Match score: `45`
- `id`: 30634
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"30634","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 72. Energy Shield Delay

- Match score: `45`
- `id`: 31630
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"31630","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["64474"]}
```

### 73. Energy Shield Delay

- Match score: `45`
- `id`: 31644
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"31644","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["14739","34058"]}
```

### 74. Energy Shield Delay

- Match score: `45`
- `id`: 3628
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"3628","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["64474","3251"]}
```

### 75. Energy Shield Delay

- Match score: `45`
- `id`: 36746
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"36746","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["40691"]}
```

### 76. Energy Shield Delay

- Match score: `45`
- `id`: 40691
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"40691","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["25893"]}
```

### 77. Energy Shield Delay

- Match score: `45`
- `id`: 42825
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"42825","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["31238"]}
```

### 78. Energy Shield Delay

- Match score: `45`
- `id`: 43736
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"43736","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["29695"]}
```

### 79. Energy Shield Delay

- Match score: `45`
- `id`: 44082
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"44082","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["4931"]}
```

### 80. Energy Shield Delay

- Match score: `45`
- `id`: 46857
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["Gain [Deflect|Deflection Rating] equal to 4% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","5% increased Mana Cost [Efficiency]"]

```json
{"id":"46857","n":"Energy Shield Delay","t":"small","sd":["Gain [Deflect|Deflection Rating] equal to 4% of [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]","5% increased Mana Cost [Efficiency]"],"out":["52971"]}
```

### 81. Energy Shield Delay

- Match score: `45`
- `id`: 4748
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"4748","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["2254"]}
```

### 82. Energy Shield Delay

- Match score: `45`
- `id`: 49235
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"49235","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["42077"]}
```

### 83. Energy Shield Delay

- Match score: `45`
- `id`: 52743
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"52743","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["34541"]}
```

### 84. Energy Shield Delay

- Match score: `45`
- `id`: 64474
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"64474","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]}
```

### 85. Energy Shield Delay

- Match score: `45`
- `id`: 65437
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"65437","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["63064"]}
```

### 86. Energy Shield Delay

- Match score: `45`
- `id`: 8734
- `n`: Energy Shield Delay
- `t`: small
- `sd`: ["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"8734","n":"Energy Shield Delay","t":"small","sd":["6% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["52743"]}
```

### 87. Energy Shield Delay and Armour Applies to Elemental Damage

- Match score: `45`
- `id`: 23039
- `n`: Energy Shield Delay and Armour Applies to Elemental Damage
- `t`: small
- `sd`: ["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"23039","n":"Energy Shield Delay and Armour Applies to Elemental Damage","t":"small","sd":["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["64770"]}
```

### 88. Energy Shield Delay and Armour Applies to Elemental Damage

- Match score: `45`
- `id`: 7554
- `n`: Energy Shield Delay and Armour Applies to Elemental Damage
- `t`: small
- `sd`: ["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"7554","n":"Energy Shield Delay and Armour Applies to Elemental Damage","t":"small","sd":["+3% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","5% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["23039"]}
```

### 89. Energy Shield Delay while Shapeshifted

- Match score: `45`
- `id`: 31673
- `n`: Energy Shield Delay while Shapeshifted
- `t`: small
- `sd`: ["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]

```json
{"id":"31673","n":"Energy Shield Delay while Shapeshifted","t":"small","sd":["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"],"out":["48649"]}
```

### 90. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 32681
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"32681","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32664","38668"]}
```

### 91. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 3630
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"3630","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["62624"]}
```

### 92. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 45631
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"45631","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["3630"]}
```

### 93. Evasion and Energy Shield Delay

- Match score: `45`
- `id`: 5188
- `n`: Evasion and Energy Shield Delay
- `t`: small
- `sd`: ["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"5188","n":"Evasion and Energy Shield Delay","t":"small","sd":["12% increased [Evasion|Evasion Rating]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["27671","38668","24165"]}
```

### 94. Rapid Recharge

- Match score: `45`
- `id`: 17973
- `n`: Rapid Recharge
- `t`: notable
- `sd`: ["12% increased [ESRechargeRate|Energy Shield Recharge Rate]","12% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"17973","n":"Rapid Recharge","t":"notable","sd":["12% increased [ESRechargeRate|Energy Shield Recharge Rate]","12% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["4748","22691"]}
```

### 95. Shapeshifted Energy Shield Delay

- Match score: `45`
- `id`: 27216
- `n`: Shapeshifted Energy Shield Delay
- `t`: small
- `sd`: ["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]

```json
{"id":"27216","n":"Shapeshifted Energy Shield Delay","t":"small","sd":["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"],"out":["30546"]}
```

### 96. Shapeshifted Energy Shield Delay

- Match score: `45`
- `id`: 31010
- `n`: Shapeshifted Energy Shield Delay
- `t`: small
- `sd`: ["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]

```json
{"id":"31010","n":"Shapeshifted Energy Shield Delay","t":"small","sd":["10% [FasterESRechargeStart|faster start of Energy Shield Recharge] while [Shapeshift|Shapeshifted]"]}
```

### 97. Cirel of Tarth's Light

- Match score: `40`
- `id`: 21213
- `n`: Cirel of Tarth's Light
- `t`: notable
- `sd`: ["+10% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","10% increased [LightRadius|Light Radius]","10% increased [Accuracy] Rating","10% increased Area of Effect"]

```json
{"id":"21213","n":"Cirel of Tarth's Light","t":"notable","sd":["+10% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","10% increased [LightRadius|Light Radius]","10% increased [Accuracy] Rating","10% increased Area of Effect"]}
```

### 98. Ailment Threshold from Energy Shield

- Match score: `35`
- `id`: 59798
- `n`: Ailment Threshold from Energy Shield
- `t`: small
- `sd`: ["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"]

```json
{"id":"59798","n":"Ailment Threshold from Energy Shield","t":"small","sd":["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"],"out":["5335"]}
```

### 99. Ancestral Boosted Area and Damage

- Match score: `35`
- `id`: 18207
- `n`: Ancestral Boosted Area and Damage
- `t`: small
- `sd`: ["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"]

```json
{"id":"18207","n":"Ancestral Boosted Area and Damage","t":"small","sd":["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"],"out":["53261"]}
```

### 100. Ancestral Boosted Area and Damage

- Match score: `35`
- `id`: 30780
- `n`: Ancestral Boosted Area and Damage
- `t`: small
- `sd`: ["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"]

```json
{"id":"30780","n":"Ancestral Boosted Area and Damage","t":"small","sd":["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"],"out":["17112","5410"]}
```

### 101. Ancestral Boosted Area and Damage

- Match score: `35`
- `id`: 53261
- `n`: Ancestral Boosted Area and Damage
- `t`: small
- `sd`: ["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"]

```json
{"id":"53261","n":"Ancestral Boosted Area and Damage","t":"small","sd":["4% increased Area of Effect of [AncestralBoost|Ancestrally Boosted] [Attack|Attacks]","[AncestralBoost|Ancestrally Boosted] [Attack|Attacks] deal 8% increased Damage"],"out":["30780"]}
```

### 102. Area and Presence

- Match score: `35`
- `id`: 23364
- `n`: Area and Presence
- `t`: small
- `sd`: ["9% increased [Presence|Presence] Area of Effect","3% increased Area of Effect"]

```json
{"id":"23364","n":"Area and Presence","t":"small","sd":["9% increased [Presence|Presence] Area of Effect","3% increased Area of Effect"],"out":["33781","48614"]}
```

### 103. Area and Presence

- Match score: `35`
- `id`: 33781
- `n`: Area and Presence
- `t`: small
- `sd`: ["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"]

```json
{"id":"33781","n":"Area and Presence","t":"small","sd":["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"],"out":["65493"]}
```

### 104. Area and Presence

- Match score: `35`
- `id`: 48614
- `n`: Area and Presence
- `t`: small
- `sd`: ["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"]

```json
{"id":"48614","n":"Area and Presence","t":"small","sd":["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"],"out":["9018"]}
```

### 105. Area and Presence

- Match score: `35`
- `id`: 65493
- `n`: Area and Presence
- `t`: small
- `sd`: ["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"]

```json
{"id":"65493","n":"Area and Presence","t":"small","sd":["15% reduced [Presence|Presence] Area of Effect","6% increased Area of Effect"],"out":["43854"]}
```

### 106. Area and Presence

- Match score: `35`
- `id`: 9018
- `n`: Area and Presence
- `t`: small
- `sd`: ["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"]

```json
{"id":"9018","n":"Area and Presence","t":"small","sd":["20% increased [Presence|Presence] Area of Effect","3% reduced Area of Effect"],"out":["35918"]}
```

### 107. Area Damage

- Match score: `35`
- `id`: 1170
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"1170","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["58295"]}
```

### 108. Area Damage

- Match score: `35`
- `id`: 19277
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Spell] Area Damage"]

```json
{"id":"19277","n":"Area Damage","t":"small","sd":["10% increased [Spell] Area Damage"],"out":["44783"]}
```

### 109. Area Damage

- Match score: `35`
- `id`: 20645
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"20645","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["64284"]}
```

### 110. Area Damage

- Match score: `35`
- `id`: 36737
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased Area Damage"]

```json
{"id":"36737","n":"Area Damage","t":"small","sd":["10% increased Area Damage"],"out":["7542"]}
```

### 111. Area Damage

- Match score: `35`
- `id`: 3999
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"3999","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["37665","57863"]}
```

### 112. Area Damage

- Match score: `35`
- `id`: 41126
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"41126","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["1170","9918"]}
```

### 113. Area Damage

- Match score: `35`
- `id`: 44783
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Spell] Area Damage"]

```json
{"id":"44783","n":"Area Damage","t":"small","sd":["10% increased [Spell] Area Damage"],"out":["22949"]}
```

### 114. Area Damage

- Match score: `35`
- `id`: 53443
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"53443","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["5710","59767"]}
```

### 115. Area Damage

- Match score: `35`
- `id`: 57405
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"57405","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["64807"]}
```

### 116. Area Damage

- Match score: `35`
- `id`: 59480
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"59480","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["3999"]}
```

### 117. Area Damage

- Match score: `35`
- `id`: 61362
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased Area Damage"]

```json
{"id":"61362","n":"Area Damage","t":"small","sd":["10% increased Area Damage"],"out":["36737"]}
```

### 118. Area Damage

- Match score: `35`
- `id`: 9918
- `n`: Area Damage
- `t`: small
- `sd`: ["10% increased [Attack] Area Damage"]

```json
{"id":"9918","n":"Area Damage","t":"small","sd":["10% increased [Attack] Area Damage"],"out":["16626"]}
```

### 119. Area Damage and Armour Break

- Match score: `35`
- `id`: 37665
- `n`: Area Damage and Armour Break
- `t`: small
- `sd`: ["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"]

```json
{"id":"37665","n":"Area Damage and Armour Break","t":"small","sd":["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"],"out":["35739"]}
```

### 120. Area Damage and Armour Break

- Match score: `35`
- `id`: 42410
- `n`: Area Damage and Armour Break
- `t`: small
- `sd`: ["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"]

```json
{"id":"42410","n":"Area Damage and Armour Break","t":"small","sd":["[ArmourBreak|Break] 10% increased [Armour|Armour]","6% increased [Attack] Area Damage"],"out":["9737"]}
```

## Passive edges

- Source: `build_knowledge/compact/passive_tree_edges.json`
- Matches included: `0`

_No keyword matches in this index._

## Gems and skills

- Source: `build_knowledge/compact/gem_index.json`
- Matches included: `120`

### 1. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]

- Match score: `80`
- `k`: active_skill_area_of_effect_+%_final_per_endurance_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_area_of_effect_+%_final_per_endurance_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE","1":{"type":"Multiplier","var":"EnduranceCharge"}}]}
```

### 2. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `80`
- `k`: maximum_added_cold_damage_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"maximum_added_cold_damage_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMax","type":"BASE","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 3. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `80`
- `k`: minimum_added_cold_damage_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minimum_added_cold_damage_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMin","type":"BASE","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 4. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}, '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]

- Match score: `80`
- `k`: spell_maximum_base_cold_damage_per_removable_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}, '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"spell_maximum_base_cold_damage_per_removable_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}, '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"ColdMax"},"1":{"type":"Multiplier","var":"RemovableFrenzyCharge"}}]}
```

### 5. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMin'}, '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]

- Match score: `80`
- `k`: spell_minimum_base_cold_damage_per_removable_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMin'}, '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"spell_minimum_base_cold_damage_per_removable_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMin'}, '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"ColdMin"},"1":{"type":"Multiplier","var":"RemovableFrenzyCharge"}}]}
```

### 6. [{'flags': 2, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'RemovableTotalCharges'}}]

- Match score: `80`
- `k`: area_of_effect_+%_final_per_removable_power_frenzy_or_endurance_charge
- `n`: [{'flags': 2, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'RemovableTotalCharges'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"area_of_effect_+%_final_per_removable_power_frenzy_or_endurance_charge","n":"[{'flags': 2, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'RemovableTotalCharges'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":2,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE","1":{"type":"Multiplier","var":"RemovableTotalCharges"}}]}
```

### 7. Blindside

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemBlindsideSupport
- `n`: Blindside
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemBlindsideSupport","n":"Blindside","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 8. Charge Profusion I

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemChargeProfusionSupport
- `n`: Charge Profusion I
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemChargeProfusionSupport","n":"Charge Profusion I","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 9. Charge Profusion II

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemChargeProfusionSupportTwo
- `n`: Charge Profusion II
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemChargeProfusionSupportTwo","n":"Charge Profusion II","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 10. Concentrated Area

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemConcentratedAreaSupport
- `n`: Concentrated Area
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"area":true,"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemConcentratedAreaSupport","n":"Concentrated Area","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"area":true,"support":true}}
```

### 11. MeleeAtAnimationSpeedColdCombo35

- Match score: `70`
- `k`: MeleeAtAnimationSpeedColdCombo35
- `n`: MeleeAtAnimationSpeedColdCombo35
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedColdCombo35","n":"MeleeAtAnimationSpeedColdCombo35","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 12. MeleeAtAnimationSpeedColdCombo70

- Match score: `70`
- `k`: MeleeAtAnimationSpeedColdCombo70
- `n`: MeleeAtAnimationSpeedColdCombo70
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedColdCombo70","n":"MeleeAtAnimationSpeedColdCombo70","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 13. MeleeAtAnimationSpeedComboTeleport

- Match score: `70`
- `k`: MeleeAtAnimationSpeedComboTeleport
- `n`: MeleeAtAnimationSpeedComboTeleport
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedComboTeleport","n":"MeleeAtAnimationSpeedComboTeleport","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 14. Metadata/Items/Gem/SupportGemBlindside

- Match score: `70`
- `k`: Metadata/Items/Gem/SupportGemBlindside
- `n`: Metadata/Items/Gem/SupportGemBlindside
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support"]
- `base`: {"display_name":"Blindside","id":"Metadata/Items/Gem/SupportGemBlindside","release_state":"released"}

```json
{"k":"Metadata/Items/Gem/SupportGemBlindside","n":"Metadata/Items/Gem/SupportGemBlindside","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Blindside","id":"Metadata/Items/Gem/SupportGemBlindside","release_state":"released"},"tags":["support"]}
```

### 15. Perpetual Charge

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemPerpetualCharge
- `n`: Perpetual Charge
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemPerpetualCharge","n":"Perpetual Charge","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 16. RiptideColdCombo

- Match score: `70`
- `k`: RiptideColdCombo
- `n`: RiptideColdCombo
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"RiptideColdCombo","n":"RiptideColdCombo","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 17. SupportBlindsidePlayer

- Match score: `70`
- `k`: SupportBlindsidePlayer
- `n`: SupportBlindsidePlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":null,"allowed_types":["Attack","Damage","CrossbowSkill","CrossbowAmmoSkill"],"excluded_types":["DegenOnlySpellDamage"],"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportBlindsidePlayer","n":"SupportBlindsidePlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":null,"allowed_types":["Attack","Damage","CrossbowSkill","CrossbowAmmoSkill"],"excluded_types":["DegenOnlySpellDamage"],"letter":"","supports_gems_only":false},"is_support":true}
```

### 18. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]

- Match score: `55`
- `k`: active_skill_area_of_effect_radius_+%_final
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_area_of_effect_radius_+%_final","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE"}]}
```

### 19. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'limitVar': 'ComboStacksMax', 'type': 'Multiplier', 'var': 'ComboStacks'}}]

- Match score: `55`
- `k`: support_culmination_damage_+%_final_per_combo_stack
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'limitVar': 'ComboStacksMax', 'type': 'Multiplier', 'var': 'ComboStacks'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"support_culmination_damage_+%_final_per_combo_stack","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'limitVar': 'ComboStacksMax', 'type': 'Multiplier', 'var': 'ComboStacks'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"MORE","1":{"limitVar":"ComboStacksMax","type":"Multiplier","var":"ComboStacks"}}]}
```

### 20. [{'flags': 0, 'keywordFlags': 0, 'name': 'MineDetonationAreaOfEffect', 'type': 'INC'}]

- Match score: `55`
- `k`: mine_detonation_radius_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MineDetonationAreaOfEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"mine_detonation_radius_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MineDetonationAreaOfEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MineDetonationAreaOfEffect","type":"INC"}]}
```

### 21. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radius'}}]

- Match score: `55`
- `k`: active_skill_base_area_of_effect_radius
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radius'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_area_of_effect_radius","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radius'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"radius"}}]}
```

### 22. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radiusSecondary'}}]

- Match score: `55`
- `k`: active_skill_base_secondary_area_of_effect_radius
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radiusSecondary'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_secondary_area_of_effect_radius","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radiusSecondary'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"radiusSecondary"}}]}
```

### 23. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radiusTertiary'}}]

- Match score: `55`
- `k`: active_skill_base_tertiary_area_of_effect_radius
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radiusTertiary'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_tertiary_area_of_effect_radius","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'radiusTertiary'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"radiusTertiary"}}]}
```

### 24. [{'flags': 0, 'keywordFlags': 0, 'name': 'TrapTriggerAreaOfEffect', 'type': 'INC'}]

- Match score: `55`
- `k`: trap_trigger_radius_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'TrapTriggerAreaOfEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"trap_trigger_radius_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'TrapTriggerAreaOfEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"TrapTriggerAreaOfEffect","type":"INC"}]}
```

### 25. Elemental Discharge

- Match score: `55`
- `k`: Metadata/Items/Gems/SkillGemElementalDischarge
- `n`: Elemental Discharge
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"area":true,"cold":true,"fire":true,"grants_active_skill":true,"lightning":true,"payoff":true,"spell":true,"support":true,"trigger":true}

```json
{"k":"Metadata/Items/Gems/SkillGemElementalDischarge","n":"Elemental Discharge","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"area":true,"cold":true,"fire":true,"grants_active_skill":true,"lightning":true,"payoff":true,"spell":true,"support":true,"trigger":true}}
```

### 26. Metadata/Items/Gems/SupportGemElementalDischarge

- Match score: `55`
- `k`: Metadata/Items/Gems/SupportGemElementalDischarge
- `n`: Metadata/Items/Gems/SupportGemElementalDischarge
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support","grants_active_skill","spell","area","trigger","lightning","cold","fire","payoff"]
- `base`: {"display_name":"Elemental Discharge","id":"Metadata/Items/Gems/SupportGemElementalDischarge","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemElementalDischarge","n":"Metadata/Items/Gems/SupportGemElementalDischarge","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Elemental Discharge","id":"Metadata/Items/Gems/SupportGemElementalDischarge","release_state":"released"},"tags":["support","grants_active_skill","spell","area","trigger","lightning","cold","fire","payoff"]}
```

### 27. Shattering Palm

- Match score: `55`
- `k`: Metadata/Items/Gems/SkillGemShatteringPalm
- `n`: Shattering Palm
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"area":true,"attack":true,"cold":true,"dexterity":true,"grants_active_skill":true,"intelligence":true,"melee":true,"strike":true,"trigger":true}

```json
{"k":"Metadata/Items/Gems/SkillGemShatteringPalm","n":"Shattering Palm","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"area":true,"attack":true,"cold":true,"dexterity":true,"grants_active_skill":true,"intelligence":true,"melee":true,"strike":true,"trigger":true}}
```

### 28. [AoESkill|AoE]

- Match score: `45`
- `k`: area
- `n`: [AoESkill|AoE]
- `cat`: repoe_gem_tags
- `src`: repoe_poe2/gem_tags.json

```json
{"k":"area","n":"[AoESkill|AoE]","cat":"repoe_gem_tags","src":"repoe_poe2/gem_tags.json","v":"[AoESkill|AoE]"}
```

### 29. [{'div': 1000, '1': {'flags': 0, 'keywordFlags': 0, 'name': 'AncestralCallCooldown', 'type': 'BASE'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'Condition:AncestrallyBoosted', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: ancestral_call_spirit_strike_interval_ms
- `n`: [{'div': 1000, '1': {'flags': 0, 'keywordFlags': 0, 'name': 'AncestralCallCooldown', 'type': 'BASE'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'Condition:AncestrallyBoosted', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"ancestral_call_spirit_strike_interval_ms","n":"[{'div': 1000, '1': {'flags': 0, 'keywordFlags': 0, 'name': 'AncestralCallCooldown', 'type': 'BASE'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'Condition:AncestrallyBoosted', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"div":1000,"1":{"flags":0,"keywordFlags":0,"name":"AncestralCallCooldown","type":"BASE"}},{"flags":0,"keywordFlags":0,"name":"Condition:AncestrallyBoosted","type":"FLAG","value":true}]}
```

### 30. [{'div': 1000, '1': {'flags': 0, 'keywordFlags': 0, 'name': 'FistOfWarCooldown', 'type': 'BASE'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'Condition:AncestrallyBoosted', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: ancestral_slam_interval_duration
- `n`: [{'div': 1000, '1': {'flags': 0, 'keywordFlags': 0, 'name': 'FistOfWarCooldown', 'type': 'BASE'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'Condition:AncestrallyBoosted', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"ancestral_slam_interval_duration","n":"[{'div': 1000, '1': {'flags': 0, 'keywordFlags': 0, 'name': 'FistOfWarCooldown', 'type': 'BASE'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'Condition:AncestrallyBoosted', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"div":1000,"1":{"flags":0,"keywordFlags":0,"name":"FistOfWarCooldown","type":"BASE"}},{"flags":0,"keywordFlags":0,"name":"Condition:AncestrallyBoosted","type":"FLAG","value":true}]}
```

### 31. [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalChargeChance', 'type': 'BASE'}]

- Match score: `45`
- `k`: chance_to_gain_1_more_charge_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalChargeChance', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"chance_to_gain_1_more_charge_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalChargeChance', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AdditionalChargeChance","type":"BASE"}]}
```

### 32. [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE', '1': {'neg': True, 'skillType': 64, 'type': 'SkillType'}}]

- Match score: `45`
- `k`: support_added_cooldown_count_if_not_instant
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE', '1': {'neg': True, 'skillType': 64, 'type': 'SkillType'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"support_added_cooldown_count_if_not_instant","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE', '1': {'neg': True, 'skillType': 64, 'type': 'SkillType'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AdditionalCooldownUses","type":"BASE","1":{"neg":true,"skillType":64,"type":"SkillType"}}]}
```

### 33. [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE', '1': {'skillType': 254, 'type': 'SkillType'}}]

- Match score: `45`
- `k`: support_storm_skill_limit_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE', '1': {'skillType': 254, 'type': 'SkillType'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"support_storm_skill_limit_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE', '1': {'skillType': 254, 'type': 'SkillType'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AdditionalCooldownUses","type":"BASE","1":{"skillType":254,"type":"SkillType"}}]}
```

### 34. [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_added_cooldown_count
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_added_cooldown_count","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AdditionalCooldownUses","type":"BASE"}]}
```

### 35. [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_limit_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_limit_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AdditionalCooldownUses', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AdditionalCooldownUses","type":"BASE"}]}
```

### 36. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC', '1': {'neg': True, 'type': 'Condition', 'var': 'DualWielding'}}]

- Match score: `45`
- `k`: area_of_effect_+%_while_not_dual_wielding
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC', '1': {'neg': True, 'type': 'Condition', 'var': 'DualWielding'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"area_of_effect_+%_while_not_dual_wielding","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC', '1': {'neg': True, 'type': 'Condition', 'var': 'DualWielding'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"INC","1":{"neg":true,"type":"Condition","var":"DualWielding"}}]}
```

### 37. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC'}]

- Match score: `45`
- `k`: base_skill_area_of_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_skill_area_of_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"INC"}]}
```

### 38. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Condition', 'var': 'CastOnFrostbolt'}}]

- Match score: `45`
- `k`: active_skill_area_of_effect_+%_final_when_cast_on_frostbolt
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Condition', 'var': 'CastOnFrostbolt'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_area_of_effect_+%_final_when_cast_on_frostbolt","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Condition', 'var': 'CastOnFrostbolt'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE","1":{"type":"Condition","var":"CastOnFrostbolt"}}]}
```

### 39. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Condition', 'var': 'SandStance'}}]

- Match score: `45`
- `k`: skill_area_of_effect_+%_final_in_sand_stance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Condition', 'var': 'SandStance'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_area_of_effect_+%_final_in_sand_stance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Condition', 'var': 'SandStance'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE","1":{"type":"Condition","var":"SandStance"}}]}
```

### 40. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]

- Match score: `45`
- `k`: active_skill_area_of_effect_+%_final
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_area_of_effect_+%_final","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE"}]}
```

### 41. [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]

- Match score: `45`
- `k`: support_area_of_effect_+%_final
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"support_area_of_effect_+%_final","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE"}]}
```

### 42. [{'flags': 0, 'keywordFlags': 0, 'name': 'BlindChance', 'type': 'BASE'}]

- Match score: `45`
- `k`: global_chance_to_blind_on_hit_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'BlindChance', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"global_chance_to_blind_on_hit_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'BlindChance', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"BlindChance","type":"BASE"}]}
```

### 43. [{'flags': 0, 'keywordFlags': 0, 'name': 'BlindEffect', 'type': 'INC', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `45`
- `k`: blind_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'BlindEffect', 'type': 'INC', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"blind_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'BlindEffect', 'type': 'INC', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"BlindEffect","type":"INC","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 44. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamage', 'type': 'INC'}]

- Match score: `45`
- `k`: cold_damage_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamage', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cold_damage_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamage', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdDamage","type":"INC"}]}
```

### 45. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamage', 'type': 'MORE'}]

- Match score: `45`
- `k`: active_skill_cold_damage_+%_final
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamage', 'type': 'MORE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_cold_damage_+%_final","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamage', 'type': 'MORE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdDamage","type":"MORE"}]}
```

### 46. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageGainAsChaos', 'type': 'BASE'}]

- Match score: `45`
- `k`: non_skill_base_cold_damage_%_to_gain_as_chaos
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageGainAsChaos', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"non_skill_base_cold_damage_%_to_gain_as_chaos","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageGainAsChaos', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdDamageGainAsChaos","type":"BASE"}]}
```

### 47. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageGainAsFire', 'type': 'BASE'}]

- Match score: `45`
- `k`: cold_damage_%_to_add_as_fire
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageGainAsFire', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cold_damage_%_to_add_as_fire","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageGainAsFire', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdDamageGainAsFire","type":"BASE"}]}
```

### 48. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageTaken', 'type': 'INC'}]

- Match score: `45`
- `k`: cold_damage_taken_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageTaken', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cold_damage_taken_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDamageTaken', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdDamageTaken","type":"INC"}]}
```

### 49. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDotMultiplier', 'type': 'BASE'}]

- Match score: `45`
- `k`: cold_dot_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDotMultiplier', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cold_dot_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdDotMultiplier', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdDotMultiplier","type":"BASE"}]}
```

### 50. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_inflict_cold_exposure_on_hit_%_chance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_inflict_cold_exposure_on_hit_%_chance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdExposureChance","type":"BASE"}]}
```

### 51. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}]

- Match score: `45`
- `k`: maximum_added_cold_damage_vs_chilled_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"maximum_added_cold_damage_vs_chilled_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMax","type":"BASE","1":{"actor":"enemy","type":"ActorCondition","var":"Chilled"}}]}
```

### 52. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'OffHandAttack'}, '2': {'div': 15, 'stat': 'EvasionOnWeapon 2', 'type': 'PerStat'}}]

- Match score: `45`
- `k`: off_hand_maximum_added_cold_damage_per_15_shield_evasion
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'OffHandAttack'}, '2': {'div': 15, 'stat': 'EvasionOnWeapon 2', 'type': 'PerStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"off_hand_maximum_added_cold_damage_per_15_shield_evasion","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'OffHandAttack'}, '2': {'div': 15, 'stat': 'EvasionOnWeapon 2', 'type': 'PerStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMax","type":"BASE","1":{"type":"Condition","var":"OffHandAttack"},"2":{"div":15,"stat":"EvasionOnWeapon 2","type":"PerStat"}}]}
```

### 53. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE'}]

- Match score: `45`
- `k`: global_maximum_added_cold_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"global_maximum_added_cold_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMax","type":"BASE"}]}
```

### 54. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}]

- Match score: `45`
- `k`: minimum_added_cold_damage_vs_chilled_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minimum_added_cold_damage_vs_chilled_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMin","type":"BASE","1":{"actor":"enemy","type":"ActorCondition","var":"Chilled"}}]}
```

### 55. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'OffHandAttack'}, '2': {'div': 15, 'stat': 'EvasionOnWeapon 2', 'type': 'PerStat'}}]

- Match score: `45`
- `k`: off_hand_minimum_added_cold_damage_per_15_shield_evasion
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'OffHandAttack'}, '2': {'div': 15, 'stat': 'EvasionOnWeapon 2', 'type': 'PerStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"off_hand_minimum_added_cold_damage_per_15_shield_evasion","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'OffHandAttack'}, '2': {'div': 15, 'stat': 'EvasionOnWeapon 2', 'type': 'PerStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMin","type":"BASE","1":{"type":"Condition","var":"OffHandAttack"},"2":{"div":15,"stat":"EvasionOnWeapon 2","type":"PerStat"}}]}
```

### 56. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE'}]

- Match score: `45`
- `k`: global_minimum_added_cold_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"global_minimum_added_cold_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMin","type":"BASE"}]}
```

### 57. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdPenetration', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_reduce_enemy_cold_resistance_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdPenetration', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_reduce_enemy_cold_resistance_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdPenetration', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdPenetration","type":"BASE"}]}
```

### 58. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdResist', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_cold_damage_resistance_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdResist', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_cold_damage_resistance_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdResist', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdResist","type":"BASE"}]}
```

### 59. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdResistMax', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_maximum_cold_damage_resistance_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdResistMax', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_maximum_cold_damage_resistance_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdResistMax', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdResistMax","type":"BASE"}]}
```

### 60. [{'flags': 0, 'keywordFlags': 0, 'name': 'Condition:CannotConsumeCharges', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: cannot_consume_power_frenzy_endurance_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Condition:CannotConsumeCharges', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cannot_consume_power_frenzy_endurance_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Condition:CannotConsumeCharges', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Condition:CannotConsumeCharges","type":"FLAG","value":true}]}
```

### 61. [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownDoesNotLimitSkillSpeed', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: channelled_skill_do_not_go_on_cooldown_on_finishing_channel
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownDoesNotLimitSkillSpeed', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"channelled_skill_do_not_go_on_cooldown_on_finishing_channel","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownDoesNotLimitSkillSpeed', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CooldownDoesNotLimitSkillSpeed","type":"FLAG","value":true}]}
```

### 62. [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]

- Match score: `45`
- `k`: base_cooldown_speed_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_cooldown_speed_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC"}]}
```

### 63. [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]

- Match score: `45`
- `k`: base_spell_cooldown_speed_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_spell_cooldown_speed_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC"}]}
```

### 64. [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]

- Match score: `45`
- `k`: grenade_skill_cooldown_speed_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"grenade_skill_cooldown_speed_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC"}]}
```

### 65. [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]

- Match score: `45`
- `k`: support_cooldown_reduction_cooldown_recovery_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"support_cooldown_reduction_cooldown_recovery_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC"}]}
```

### 66. [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'MORE'}]

- Match score: `45`
- `k`: base_cooldown_speed_+%_final
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'MORE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_cooldown_speed_+%_final","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'MORE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"MORE"}]}
```

### 67. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Blinded'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_vs_blinded_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Blinded'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_vs_blinded_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Blinded'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"Blinded"}}]}
```

### 68. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 69. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `45`
- `k`: critical_strike_multiplier_+_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_multiplier_+_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritMultiplier","type":"BASE","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 70. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}, '2': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}, '3': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovablePowerCharge'}}]

- Match score: `45`
- `k`: discharge_damage_+%_if_3_charge_types_removed
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}, '2': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}, '3': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovablePowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"discharge_damage_+%_if_3_charge_types_removed","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}, '2': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}, '3': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovablePowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"limit":1,"type":"Multiplier","var":"RemovableEnduranceCharge"},"2":{"limit":1,"type":"Multiplier","var":"RemovableFrenzyCharge"},"3":{"limit":1,"type":"Multiplier","var":"RemovablePowerCharge"}}]}
```

### 71. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]

- Match score: `45`
- `k`: damage_+%_per_endurance_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"damage_+%_per_endurance_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"EnduranceCharge"}}]}
```

### 72. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `45`
- `k`: damage_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"damage_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 73. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `45`
- `k`: damage_+%_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"damage_+%_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 74. [{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE'}]

- Match score: `45`
- `k`: active_skill_base_all_damage_%_to_gain_as_cold
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_all_damage_%_to_gain_as_cold","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"DamageGainAsCold","type":"BASE"}]}
```

### 75. [{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE'}]

- Match score: `45`
- `k`: non_skill_base_all_damage_%_to_gain_as_cold
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"non_skill_base_all_damage_%_to_gain_as_cold","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"DamageGainAsCold","type":"BASE"}]}
```

### 76. [{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsFire', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffFire'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffCold'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsLightning', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffLightning'}}]

- Match score: `45`
- `k`: windstorm_gain_all_damage_%_as_corresponding_element_if_empowered
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsFire', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffFire'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffCold'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsLightning', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffLightning'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"windstorm_gain_all_damage_%_as_corresponding_element_if_empowered","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsFire', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffFire'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsCold', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffCold'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'DamageGainAsLightning', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'WhirlwindBuffLightning'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"DamageGainAsFire","type":"BASE","1":{"type":"Condition","var":"WhirlwindBuffFire"}},{"flags":0,"keywordFlags":0,"name":"DamageGainAsCold","type":"BASE","1":{"type":"Condition","var":"WhirlwindBuffCold"}},{"flags":0,"keywordFlags":0,"name":"DamageGainAsLightning","type":"BASE","1":{"type":"Condition","v...[trimmed]
```

### 77. [{'flags': 0, 'keywordFlags': 0, 'name': 'DealNoFire', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'DealNoCold', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'DealNoLightning', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: deal_no_elemental_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'DealNoFire', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'DealNoCold', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'DealNoLightning', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"deal_no_elemental_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'DealNoFire', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'DealNoCold', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'DealNoLightning', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"DealNoFire","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"DealNoCold","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"DealNoLightning","type":"FLAG","value":true}]}
```

### 78. [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'limit': 5, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]

- Match score: `45`
- `k`: buff_effect_duration_+%_per_removable_endurance_charge_limited_to_5
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'limit': 5, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"buff_effect_duration_+%_per_removable_endurance_charge_limited_to_5","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'limit': 5, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Duration","type":"INC","1":{"limit":5,"type":"Multiplier","var":"RemovableEnduranceCharge"}}]}
```

### 79. [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]

- Match score: `45`
- `k`: buff_effect_duration_+%_per_removable_endurance_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"buff_effect_duration_+%_per_removable_endurance_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Duration","type":"INC","1":{"type":"Multiplier","var":"RemovableEnduranceCharge"}}]}
```

### 80. [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]

- Match score: `45`
- `k`: skill_effect_duration_+%_per_removable_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_effect_duration_+%_per_removable_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Duration","type":"INC","1":{"type":"Multiplier","var":"RemovableFrenzyCharge"}}]}
```

### 81. [{'flags': 0, 'keywordFlags': 0, 'name': 'EnduranceChargesMax', 'type': 'OVERRIDE'}]

- Match score: `45`
- `k`: set_max_endurance_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'EnduranceChargesMax', 'type': 'OVERRIDE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"set_max_endurance_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'EnduranceChargesMax', 'type': 'OVERRIDE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"EnduranceChargesMax","type":"OVERRIDE"}]}
```

### 82. [{'flags': 0, 'keywordFlags': 0, 'name': 'EnergyShieldRecharge', 'type': 'INC'}]

- Match score: `45`
- `k`: base_skill_buff_energy_shield_recharge_rate_+%_to_apply
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'EnergyShieldRecharge', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_skill_buff_energy_shield_recharge_rate_+%_to_apply","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'EnergyShieldRecharge', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"EnergyShieldRecharge","type":"INC"}]}
```

### 83. [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]

- Match score: `45`
- `k`: inflict_exposure_for_x_ms_on_cold_crit
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_exposure_for_x_ms_on_cold_crit","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ExposureDuration","type":"BASE","1":{"type":"Condition","var":"CritInPast8Sec"},"2":{"type":"Condition","var":"ColdHasDamage"}},{"flags":0,"keywordFlags":0,"name":"InflictExposure","type":"FLAG","value":true,"1":{"type":"Condition","var":"CritInPast8Sec"},"2":{"type":"Condition","var":"ColdHasDamage"}}]}
```

### 84. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `45`
- `k`: active_skill_all_elemental_exposure_magnitude
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_all_elemental_exposure_magnitude","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"ColdExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"LightningExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 85. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `45`
- `k`: all_exposure_on_hit_magnitude
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"all_exposure_on_hit_magnitude","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"ColdExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"LightningExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 86. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `45`
- `k`: skill_base_oil_exposure_-_to_total_elemental_resistance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_base_oil_exposure_-_to_total_elemental_resistance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"ColdExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"LightningExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 87. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureEffect', 'type': 'INC'}]

- Match score: `45`
- `k`: exposure_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"exposure_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposureEffect","type":"INC"},{"flags":0,"keywordFlags":0,"name":"ColdExposureEffect","type":"INC"},{"flags":0,"keywordFlags":0,"name":"LightningExposureEffect","type":"INC"}]}
```

### 88. [{'flags': 0, 'keywordFlags': 0, 'name': 'FrenzyChargesMax', 'type': 'OVERRIDE'}]

- Match score: `45`
- `k`: set_max_frenzy_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FrenzyChargesMax', 'type': 'OVERRIDE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"set_max_frenzy_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FrenzyChargesMax', 'type': 'OVERRIDE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FrenzyChargesMax","type":"OVERRIDE"}]}
```

### 89. [{'flags': 0, 'keywordFlags': 0, 'name': 'IgnoreColdResistance', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: hits_ignore_enemy_cold_resistance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'IgnoreColdResistance', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"hits_ignore_enemy_cold_resistance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'IgnoreColdResistance', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"IgnoreColdResistance","type":"FLAG","value":true}]}
```

### 90. [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureChance', 'type': 'BASE'}]

- Match score: `45`
- `k`: inflict_exposure_on_hit_%_chance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureChance', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_exposure_on_hit_%_chance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureChance', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"LightningExposureChance","type":"BASE"},{"flags":0,"keywordFlags":0,"name":"ColdExposureChance","type":"BASE"},{"flags":0,"keywordFlags":0,"name":"FireExposureChance","type":"BASE"}]}
```

### 91. [{'flags': 0, 'keywordFlags': 0, 'name': 'MineLayingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `45`
- `k`: mine_throwing_speed_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MineLayingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"mine_throwing_speed_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MineLayingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MineLayingSpeed","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 92. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC'}}}]

- Match score: `45`
- `k`: minion_skill_area_of_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC'}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minion_skill_area_of_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'INC'}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"AreaOfEffect","type":"INC"}}}]}
```

### 93. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'ColdResist', 'type': 'BASE'}}}]

- Match score: `45`
- `k`: summon_cold_resistance_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'ColdResist', 'type': 'BASE'}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"summon_cold_resistance_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'ColdResist', 'type': 'BASE'}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"ColdResist","type":"BASE"}}}]}
```

### 94. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC', '1': {'type': 'Condition', 'var': 'CommandableSkill'}}}}]

- Match score: `45`
- `k`: minion_command_skill_cooldown_speed_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC', '1': {'type': 'Condition', 'var': 'CommandableSkill'}}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minion_command_skill_cooldown_speed_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC', '1': {'type': 'Condition', 'var': 'CommandableSkill'}}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC","1":{"type":"Condition","var":"CommandableSkill"}}}}]}
```

### 95. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}}}]

- Match score: `45`
- `k`: golem_cooldown_recovery_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"golem_cooldown_recovery_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC"}}}]}
```

### 96. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}}}]

- Match score: `45`
- `k`: minion_cooldown_recovery_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minion_cooldown_recovery_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CooldownRecovery', 'type': 'INC'}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"CooldownRecovery","type":"INC"}}}]}
```

### 97. [{'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ComboStacksMax', 'type': 'BASE'}]

- Match score: `45`
- `k`: skill_maximum_number_of_combo_stacks
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ComboStacksMax', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_maximum_number_of_combo_stacks","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ComboStacksMax', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Multiplier:ComboStacksMax","type":"BASE"}]}
```

### 98. [{'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedEnduranceChargeEffect', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedFrenzyChargeEffect', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedPowerChargeEffect', 'type': 'BASE'}]

- Match score: `45`
- `k`: chance_%_to_double_effect_of_removing_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedEnduranceChargeEffect', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedFrenzyChargeEffect', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedPowerChargeEffect', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"chance_%_to_double_effect_of_removing_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedEnduranceChargeEffect', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedFrenzyChargeEffect', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'Multiplier:ConsumedPowerChargeEffect', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Multiplier:ConsumedEnduranceChargeEffect","type":"BASE"},{"flags":0,"keywordFlags":0,"name":"Multiplier:ConsumedFrenzyChargeEffect","type":"BASE"},{"flags":0,"keywordFlags":0,"name":"Multiplier:ConsumedPowerChargeEffect","type":"BASE"}]}
```

### 99. [{'flags': 0, 'keywordFlags': 0, 'name': 'NoCooldownRecoveryInDuration', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: display_this_skill_cooldown_does_not_recover_during_buff
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'NoCooldownRecoveryInDuration', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"display_this_skill_cooldown_does_not_recover_during_buff","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'NoCooldownRecoveryInDuration', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"NoCooldownRecoveryInDuration","type":"FLAG","value":true}]}
```

### 100. [{'flags': 0, 'keywordFlags': 0, 'name': 'NoEnergyShieldRecharge', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: cannot_recharge_energy_shield
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'NoEnergyShieldRecharge', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cannot_recharge_energy_shield","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'NoEnergyShieldRecharge', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"NoEnergyShieldRecharge","type":"FLAG","value":true}]}
```

### 101. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanShock', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: all_damage_can_ignite_freeze_shock
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': ...[trimmed]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"all_damage_can_ignite_freeze_shock","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags':...[trimmed]
```

### 102. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: all_damage_can_ignite
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"all_damage_can_ignite","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalCanIgnite","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"LightningCanIgnite","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"ColdCanIgnite","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"ChaosCanIgnite","type":"FLAG","value":true}]}
```

### 103. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanShock', 'type': 'FLAG', 'value': True}]

- Match score: `45`
- `k`: all_damage_can_shock
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanShock', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"all_damage_can_shock","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanShock', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalCanShock","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"ColdCanShock","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"FireCanShock","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"ChaosCanShock","type":"FLAG","value":true}]}
```

### 104. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `45`
- `k`: physical_damage_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"physical_damage_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalDamage","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 105. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageConvertToCold', 'type': 'BASE'}]

- Match score: `45`
- `k`: base_physical_damage_%_to_convert_to_cold
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageConvertToCold', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_physical_damage_%_to_convert_to_cold","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageConvertToCold', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalDamageConvertToCold","type":"BASE"}]}
```

### 106. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageGainAsCold', 'type': 'BASE'}]

- Match score: `45`
- `k`: active_skill_base_physical_damage_%_to_gain_as_cold
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageGainAsCold', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_physical_damage_%_to_gain_as_cold","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageGainAsCold', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalDamageGainAsCold","type":"BASE"}]}
```

### 107. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageGainAsCold', 'type': 'BASE'}]

- Match score: `45`
- `k`: physical_damage_%_to_add_as_cold
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageGainAsCold', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"physical_damage_%_to_add_as_cold","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageGainAsCold', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalDamageGainAsCold","type":"BASE"}]}
```

### 108. [{'flags': 0, 'keywordFlags': 0, 'name': 'PowerChargesMax', 'type': 'OVERRIDE'}]

- Match score: `45`
- `k`: set_max_power_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PowerChargesMax', 'type': 'OVERRIDE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"set_max_power_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PowerChargesMax', 'type': 'OVERRIDE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PowerChargesMax","type":"OVERRIDE"}]}
```

### 109. [{'flags': 0, 'keywordFlags': 0, 'name': 'RepeatAreaOfEffect', 'type': 'INC'}]

- Match score: `45`
- `k`: echoed_spell_area_of_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'RepeatAreaOfEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"echoed_spell_area_of_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'RepeatAreaOfEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"RepeatAreaOfEffect","type":"INC"}]}
```

### 110. [{'flags': 0, 'keywordFlags': 0, 'name': 'RepeatAreaOfEffect', 'type': 'INC'}]

- Match score: `45`
- `k`: support_spell_echo_area_of_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'RepeatAreaOfEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"support_spell_echo_area_of_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'RepeatAreaOfEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"RepeatAreaOfEffect","type":"INC"}]}
```

### 111. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToChaos', 'type': 'BASE'}]

- Match score: `45`
- `k`: active_skill_base_cold_damage_%_to_convert_to_chaos
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToChaos', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_cold_damage_%_to_convert_to_chaos","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToChaos', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillColdDamageConvertToChaos","type":"BASE"}]}
```

### 112. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToChaos', 'type': 'BASE'}]

- Match score: `45`
- `k`: skill_cold_damage_%_to_convert_to_chaos
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToChaos', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_cold_damage_%_to_convert_to_chaos","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToChaos', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillColdDamageConvertToChaos","type":"BASE"}]}
```

### 113. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToFire', 'type': 'BASE'}]

- Match score: `45`
- `k`: active_skill_base_cold_damage_%_to_convert_to_fire
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToFire', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_cold_damage_%_to_convert_to_fire","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToFire', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillColdDamageConvertToFire","type":"BASE"}]}
```

### 114. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToFire', 'type': 'BASE'}]

- Match score: `45`
- `k`: skill_cold_damage_%_to_convert_to_fire
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToFire', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_cold_damage_%_to_convert_to_fire","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToFire', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillColdDamageConvertToFire","type":"BASE"}]}
```

### 115. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToLightning', 'type': 'BASE'}]

- Match score: `45`
- `k`: active_skill_base_cold_damage_%_to_convert_to_lightning
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToLightning', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_base_cold_damage_%_to_convert_to_lightning","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillColdDamageConvertToLightning', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillColdDamageConvertToLightning","type":"BASE"}]}
```

### 116. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'AreaOfEffect'}, '1': {'div': 50, 'stat': 'Str', 'type': 'PerStat'}}]

- Match score: `45`
- `k`: area_of_effect_+%_per_50_strength
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'AreaOfEffect'}, '1': {'div': 50, 'stat': 'Str', 'type': 'PerStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"area_of_effect_+%_per_50_strength","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'AreaOfEffect'}, '1': {'div': 50, 'stat': 'Str', 'type': 'PerStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"AreaOfEffect"},"1":{"div":50,"stat":"Str","type":"PerStat"}}]}
```

### 117. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'arrowSpeedAppliesToAreaOfEffect', 'value': True}}]

- Match score: `45`
- `k`: additive_arrow_speed_modifiers_apply_to_area_of_effect
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'arrowSpeedAppliesToAreaOfEffect', 'value': True}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additive_arrow_speed_modifiers_apply_to_area_of_effect","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'arrowSpeedAppliesToAreaOfEffect', 'value': True}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"arrowSpeedAppliesToAreaOfEffect","value":true}}]}
```

### 118. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}, '1': {'div': 10, 'stat': 'Int', 'type': 'PerStat'}}]

- Match score: `45`
- `k`: spell_maximum_base_cold_damage_+_per_10_intelligence
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}, '1': {'div': 10, 'stat': 'Int', 'type': 'PerStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"spell_maximum_base_cold_damage_+_per_10_intelligence","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}, '1': {'div': 10, 'stat': 'Int', 'type': 'PerStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"ColdMax"},"1":{"div":10,"stat":"Int","type":"PerStat"}}]}
```

### 119. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}}]

- Match score: `45`
- `k`: secondary_maximum_base_cold_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"secondary_maximum_base_cold_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"ColdMax"}}]}
```

### 120. [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}}]

- Match score: `45`
- `k`: spell_maximum_base_cold_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"spell_maximum_base_cold_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'SkillData', 'type': 'LIST', 'value': {'key': 'ColdMax'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"SkillData","type":"LIST","value":{"key":"ColdMax"}}]}
```

## Item bases/classes

- Source: `build_knowledge/compact/item_base_index.json`
- Matches included: `120`

### 1. arachnid_tomb_map_area

- Match score: `70`
- `k`: arachnid_tomb_map_area
- `n`: arachnid_tomb_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"arachnid_tomb_map_area","n":"arachnid_tomb_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 2. arachnid_tomb_map_area

- Match score: `70`
- `k`: 434
- `n`: arachnid_tomb_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"434","n":"arachnid_tomb_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"arachnid_tomb_map_area"}
```

### 3. Blindside

- Match score: `70`
- `k`: Metadata/Items/Gem/SupportGemBlindside
- `n`: Blindside
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SupportGemBlindside","n":"Blindside","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 4. cemetery_map_area

- Match score: `70`
- `k`: cemetery_map_area
- `n`: cemetery_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cemetery_map_area","n":"cemetery_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 5. cemetery_map_area

- Match score: `70`
- `k`: 435
- `n`: cemetery_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"435","n":"cemetery_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cemetery_map_area"}
```

### 6. Charge Profusion I

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemProfusion
- `n`: Charge Profusion I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemProfusion","n":"Charge Profusion I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 7. Charge Profusion II

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemProfusionTwo
- `n`: Charge Profusion II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemProfusionTwo","n":"Charge Profusion II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 8. Concentrated Area

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemConcentratedEffect
- `n`: Concentrated Area
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemConcentratedEffect","n":"Concentrated Area","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 9. core_map_area

- Match score: `70`
- `k`: core_map_area
- `n`: core_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"core_map_area","n":"core_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 10. core_map_area

- Match score: `70`
- `k`: 438
- `n`: core_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"438","n":"core_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"core_map_area"}
```

### 11. desert_map_area

- Match score: `70`
- `k`: desert_map_area
- `n`: desert_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"desert_map_area","n":"desert_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 12. desert_map_area

- Match score: `70`
- `k`: 424
- `n`: desert_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"424","n":"desert_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"desert_map_area"}
```

### 13. doedre_map_area

- Match score: `70`
- `k`: doedre_map_area
- `n`: doedre_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"doedre_map_area","n":"doedre_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 14. doedre_map_area

- Match score: `70`
- `k`: 1007
- `n`: doedre_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1007","n":"doedre_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"doedre_map_area"}
```

### 15. forest_map_area

- Match score: `70`
- `k`: forest_map_area
- `n`: forest_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"forest_map_area","n":"forest_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 16. forest_map_area

- Match score: `70`
- `k`: 375
- `n`: forest_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"375","n":"forest_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"forest_map_area"}
```

### 17. god_boss_map_area

- Match score: `70`
- `k`: god_boss_map_area
- `n`: god_boss_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"god_boss_map_area","n":"god_boss_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 18. god_boss_map_area

- Match score: `70`
- `k`: 879
- `n`: god_boss_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"879","n":"god_boss_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"god_boss_map_area"}
```

### 19. map_area_with_open_water

- Match score: `70`
- `k`: map_area_with_open_water
- `n`: map_area_with_open_water
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"map_area_with_open_water","n":"map_area_with_open_water","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 20. map_area_with_open_water

- Match score: `70`
- `k`: 470
- `n`: map_area_with_open_water
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"470","n":"map_area_with_open_water","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"map_area_with_open_water"}
```

### 21. Perpetual Charge

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemPerpetualCharge
- `n`: Perpetual Charge
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemPerpetualCharge","n":"Perpetual Charge","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 22. Tul's Charged Breachstone

- Match score: `55`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentCold2
- `n`: Tul's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentCold2","n":"Tul's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 23. Chayula's Charged Breachstone

- Match score: `45`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentChaos2
- `n`: Chayula's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentChaos2","n":"Chayula's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 24. Esh's Charged Breachstone

- Match score: `45`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentLightning2
- `n`: Esh's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentLightning2","n":"Esh's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 25. Uul-Netol's Charged Breachstone

- Match score: `45`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentPhysical2
- `n`: Uul-Netol's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentPhysical2","n":"Uul-Netol's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 26. Xoph's Charged Breachstone

- Match score: `45`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentFire2
- `n`: Xoph's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentFire2","n":"Xoph's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 27. [DNT-UNUSED] Combo Knife Throw

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemComboKnifeThrow
- `n`: [DNT-UNUSED] Combo Knife Throw
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemComboKnifeThrow","n":"[DNT-UNUSED] Combo Knife Throw","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 28. [DNT-UNUSED] Triple Slash Combo

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemTripleSlash
- `n`: [DNT-UNUSED] Triple Slash Combo
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemTripleSlash","n":"[DNT-UNUSED] Triple Slash Combo","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 29. act6_karui_area

- Match score: `35`
- `k`: act6_karui_area
- `n`: act6_karui_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"act6_karui_area","n":"act6_karui_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 30. act6_karui_area

- Match score: `35`
- `k`: 356
- `n`: act6_karui_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"356","n":"act6_karui_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"act6_karui_area"}
```

### 31. act_boss_area

- Match score: `35`
- `k`: act_boss_area
- `n`: act_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"act_boss_area","n":"act_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 32. act_boss_area

- Match score: `35`
- `k`: 159
- `n`: act_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"159","n":"act_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"act_boss_area"}
```

### 33. Ailith's Chimes

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemAilithLineage
- `n`: Ailith's Chimes
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemAilithLineage","n":"Ailith's Chimes","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 34. alira_area

- Match score: `35`
- `k`: alira_area
- `n`: alira_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"alira_area","n":"alira_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 35. alira_area

- Match score: `35`
- `k`: 794
- `n`: alira_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"794","n":"alira_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"alira_area"}
```

### 36. allows_inc_aoe

- Match score: `35`
- `k`: allows_inc_aoe
- `n`: allows_inc_aoe
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"allows_inc_aoe","n":"allows_inc_aoe","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 37. allows_inc_aoe

- Match score: `35`
- `k`: 729
- `n`: allows_inc_aoe
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"729","n":"allows_inc_aoe","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"allows_inc_aoe"}
```

### 38. aqueduct_area

- Match score: `35`
- `k`: aqueduct_area
- `n`: aqueduct_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"aqueduct_area","n":"aqueduct_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 39. aqueduct_area

- Match score: `35`
- `k`: 377
- `n`: aqueduct_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"377","n":"aqueduct_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"aqueduct_area"}
```

### 40. arakaali_area

- Match score: `35`
- `k`: arakaali_area
- `n`: arakaali_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"arakaali_area","n":"arakaali_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 41. arakaali_area

- Match score: `35`
- `k`: 992
- `n`: arakaali_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"992","n":"arakaali_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"arakaali_area"}
```

### 42. archer_boss_area

- Match score: `35`
- `k`: archer_boss_area
- `n`: archer_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archer_boss_area","n":"archer_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 43. archer_boss_area

- Match score: `35`
- `k`: 835
- `n`: archer_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"835","n":"archer_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archer_boss_area"}
```

### 44. archives_area

- Match score: `35`
- `k`: archives_area
- `n`: archives_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archives_area","n":"archives_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 45. archives_area

- Match score: `35`
- `k`: 431
- `n`: archives_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"431","n":"archives_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archives_area"}
```

### 46. area_with_water

- Match score: `35`
- `k`: area_with_water
- `n`: area_with_water
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"area_with_water","n":"area_with_water","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 47. area_with_water

- Match score: `35`
- `k`: 170
- `n`: area_with_water
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"170","n":"area_with_water","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"area_with_water"}
```

### 48. arena_area

- Match score: `35`
- `k`: arena_area
- `n`: arena_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"arena_area","n":"arena_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 49. arena_area

- Match score: `35`
- `k`: 401
- `n`: arena_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"401","n":"arena_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"arena_area"}
```

### 50. atziri_area

- Match score: `35`
- `k`: atziri_area
- `n`: atziri_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"atziri_area","n":"atziri_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 51. atziri_area

- Match score: `35`
- `k`: 824
- `n`: atziri_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"824","n":"atziri_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"atziri_area"}
```

### 52. bandit_area

- Match score: `35`
- `k`: bandit_area
- `n`: bandit_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bandit_area","n":"bandit_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 53. bandit_area

- Match score: `35`
- `k`: 379
- `n`: bandit_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"379","n":"bandit_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bandit_area"}
```

### 54. bear_boss_map

- Match score: `35`
- `k`: bear_boss_map
- `n`: bear_boss_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bear_boss_map","n":"bear_boss_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 55. bear_boss_map

- Match score: `35`
- `k`: 962
- `n`: bear_boss_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"962","n":"bear_boss_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bear_boss_map"}
```

### 56. belly_area

- Match score: `35`
- `k`: belly_area
- `n`: belly_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"belly_area","n":"belly_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 57. belly_area

- Match score: `35`
- `k`: 361
- `n`: belly_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"361","n":"belly_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"belly_area"}
```

### 58. blight_death_cold

- Match score: `35`
- `k`: blight_death_cold
- `n`: blight_death_cold
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"blight_death_cold","n":"blight_death_cold","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 59. blight_death_cold

- Match score: `35`
- `k`: 465
- `n`: blight_death_cold
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"465","n":"blight_death_cold","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"blight_death_cold"}
```

### 60. Blind I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemBlind
- `n`: Blind I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemBlind","n":"Blind I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 61. Blind II

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemBlindTwo
- `n`: Blind II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemBlindTwo","n":"Blind II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 62. blood_mage_boss_map

- Match score: `35`
- `k`: blood_mage_boss_map
- `n`: blood_mage_boss_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"blood_mage_boss_map","n":"blood_mage_boss_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 63. blood_mage_boss_map

- Match score: `35`
- `k`: 944
- `n`: blood_mage_boss_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"944","n":"blood_mage_boss_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"blood_mage_boss_map"}
```

### 64. breach_map

- Match score: `35`
- `k`: breach_map
- `n`: breach_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"breach_map","n":"breach_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 65. breach_map

- Match score: `35`
- `k`: 199
- `n`: breach_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"199","n":"breach_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"breach_map"}
```

### 66. breach_monster_cold

- Match score: `35`
- `k`: breach_monster_cold
- `n`: breach_monster_cold
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"breach_monster_cold","n":"breach_monster_cold","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 67. breach_monster_cold

- Match score: `35`
- `k`: 998
- `n`: breach_monster_cold
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"998","n":"breach_monster_cold","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"breach_monster_cold"}
```

### 68. bridge_area

- Match score: `35`
- `k`: bridge_area
- `n`: bridge_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bridge_area","n":"bridge_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 69. bridge_area

- Match score: `35`
- `k`: 877
- `n`: bridge_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"877","n":"bridge_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bridge_area"}
```

### 70. can_be_infected_map

- Match score: `35`
- `k`: can_be_infected_map
- `n`: can_be_infected_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"can_be_infected_map","n":"can_be_infected_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 71. can_be_infected_map

- Match score: `35`
- `k`: 462
- `n`: can_be_infected_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"462","n":"can_be_infected_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"can_be_infected_map"}
```

### 72. cannot_be_map_archnemesis

- Match score: `35`
- `k`: cannot_be_map_archnemesis
- `n`: cannot_be_map_archnemesis
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cannot_be_map_archnemesis","n":"cannot_be_map_archnemesis","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 73. cannot_be_map_archnemesis

- Match score: `35`
- `k`: 926
- `n`: cannot_be_map_archnemesis
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"926","n":"cannot_be_map_archnemesis","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cannot_be_map_archnemesis"}
```

### 74. carver_culture_area

- Match score: `35`
- `k`: carver_culture_area
- `n`: carver_culture_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"carver_culture_area","n":"carver_culture_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 75. carver_culture_area

- Match score: `35`
- `k`: 1231
- `n`: carver_culture_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1231","n":"carver_culture_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"carver_culture_area"}
```

### 76. catacomb_area

- Match score: `35`
- `k`: catacomb_area
- `n`: catacomb_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"catacomb_area","n":"catacomb_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 77. catacomb_area

- Match score: `35`
- `k`: 371
- `n`: catacomb_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"371","n":"catacomb_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"catacomb_area"}
```

### 78. cave_area

- Match score: `35`
- `k`: cave_area
- `n`: cave_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cave_area","n":"cave_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 79. cave_area

- Match score: `35`
- `k`: 399
- `n`: cave_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"399","n":"cave_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cave_area"}
```

### 80. chamber_of_sins_area

- Match score: `35`
- `k`: chamber_of_sins_area
- `n`: chamber_of_sins_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chamber_of_sins_area","n":"chamber_of_sins_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 81. chamber_of_sins_area

- Match score: `35`
- `k`: 365
- `n`: chamber_of_sins_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"365","n":"chamber_of_sins_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chamber_of_sins_area"}
```

### 82. chaos_golem_boss_area

- Match score: `35`
- `k`: chaos_golem_boss_area
- `n`: chaos_golem_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chaos_golem_boss_area","n":"chaos_golem_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 83. chaos_golem_boss_area

- Match score: `35`
- `k`: 807
- `n`: chaos_golem_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"807","n":"chaos_golem_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chaos_golem_boss_area"}
```

### 84. Charge Regulation

- Match score: `35`
- `k`: Metadata/Items/Gem/SkillGemChargeInfusion
- `n`: Charge Regulation
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemChargeInfusion","n":"Charge Regulation","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 85. Charged Compass

- Match score: `35`
- `k`: Metadata/Items/Currency/CurrencyItemisedSextantModifier
- `n`: Charged Compass
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyItemisedSextantModifier","n":"Charged Compass","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["currency","default"],"domain":"undefined"}
```

### 86. Charged Mark

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemChargedMark
- `n`: Charged Mark
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemChargedMark","n":"Charged Mark","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 87. Charged Shots I

- Match score: `35`
- `k`: Metadata/Items/Gem/SupportGemChargedShots
- `n`: Charged Shots I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SupportGemChargedShots","n":"Charged Shots I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 88. Charged Shots II

- Match score: `35`
- `k`: Metadata/Items/Gem/SupportGemChargedShotsTwo
- `n`: Charged Shots II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SupportGemChargedShotsTwo","n":"Charged Shots II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 89. Charged Staff

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemChargedStaff
- `n`: Charged Staff
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemChargedStaff","n":"Charged Staff","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 90. city_home_map

- Match score: `35`
- `k`: city_home_map
- `n`: city_home_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"city_home_map","n":"city_home_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 91. city_home_map

- Match score: `35`
- `k`: 945
- `n`: city_home_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"945","n":"city_home_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"city_home_map"}
```

### 92. Close Combat I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemCloseCombat
- `n`: Close Combat I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemCloseCombat","n":"Close Combat I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 93. Close Combat II

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemCloseCombatTwo
- `n`: Close Combat II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemCloseCombatTwo","n":"Close Combat II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 94. coast_boat_area

- Match score: `35`
- `k`: coast_boat_area
- `n`: coast_boat_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"coast_boat_area","n":"coast_boat_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 95. coast_boat_area

- Match score: `35`
- `k`: 414
- `n`: coast_boat_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"414","n":"coast_boat_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"coast_boat_area"}
```

### 96. Cold

- Match score: `35`
- `k`: cold
- `n`: Cold
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cold","n":"Cold","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 97. cold

- Match score: `35`
- `k`: 312
- `n`: cold
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"312","n":"cold","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cold"}
```

### 98. Cold Attunement

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemColdInfusion
- `n`: Cold Attunement
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemColdInfusion","n":"Cold Attunement","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 99. Cold Exposure

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemColdExposure
- `n`: Cold Exposure
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemColdExposure","n":"Cold Exposure","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 100. Cold Mastery

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemColdMastery
- `n`: Cold Mastery
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemColdMastery","n":"Cold Mastery","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 101. Cold Penetration

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemColdPenetration
- `n`: Cold Penetration
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemColdPenetration","n":"Cold Penetration","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 102. Cold Tattoo of Tasalio

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act4/Tattoo2_2
- `n`: Cold Tattoo of Tasalio
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act4/Tattoo2_2","n":"Cold Tattoo of Tasalio","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 103. cold_affinity

- Match score: `35`
- `k`: cold_affinity
- `n`: cold_affinity
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cold_affinity","n":"cold_affinity","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 104. cold_affinity

- Match score: `35`
- `k`: 721
- `n`: cold_affinity
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"721","n":"cold_affinity","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cold_affinity"}
```

### 105. cold_catalyst

- Match score: `35`
- `k`: cold_catalyst
- `n`: cold_catalyst
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cold_catalyst","n":"cold_catalyst","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 106. cold_catalyst

- Match score: `35`
- `k`: 1308
- `n`: cold_catalyst
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1308","n":"cold_catalyst","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cold_catalyst"}
```

### 107. cold_crafting_option

- Match score: `35`
- `k`: cold_crafting_option
- `n`: cold_crafting_option
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cold_crafting_option","n":"cold_crafting_option","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 108. cold_crafting_option

- Match score: `35`
- `k`: 1126
- `n`: cold_crafting_option
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1126","n":"cold_crafting_option","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cold_crafting_option"}
```

### 109. cold_resistance

- Match score: `35`
- `k`: cold_resistance
- `n`: cold_resistance
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cold_resistance","n":"cold_resistance","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 110. cold_resistance

- Match score: `35`
- `k`: 1264
- `n`: cold_resistance
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1264","n":"cold_resistance","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cold_resistance"}
```

### 111. Combo Finisher I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemComboFinisher
- `n`: Combo Finisher I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemComboFinisher","n":"Combo Finisher I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 112. Combo Finisher II

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemComboFinisherTwo
- `n`: Combo Finisher II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemComboFinisherTwo","n":"Combo Finisher II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 113. Cooldown Recovery I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemIngenuity
- `n`: Cooldown Recovery I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemIngenuity","n":"Cooldown Recovery I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 114. Cooldown Recovery II

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemIngenuityTwo
- `n`: Cooldown Recovery II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemIngenuityTwo","n":"Cooldown Recovery II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 115. crossroad_area

- Match score: `35`
- `k`: crossroad_area
- `n`: crossroad_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"crossroad_area","n":"crossroad_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 116. crossroad_area

- Match score: `35`
- `k`: 370
- `n`: crossroad_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"370","n":"crossroad_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"crossroad_area"}
```

### 117. crypt_area

- Match score: `35`
- `k`: crypt_area
- `n`: crypt_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"crypt_area","n":"crypt_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 118. crypt_area

- Match score: `35`
- `k`: 373
- `n`: crypt_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"373","n":"crypt_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"crypt_area"}
```

### 119. crystal_ore_area

- Match score: `35`
- `k`: crystal_ore_area
- `n`: crystal_ore_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"crystal_ore_area","n":"crystal_ore_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 120. crystal_ore_area

- Match score: `35`
- `k`: 420
- `n`: crystal_ore_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"420","n":"crystal_ore_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"crystal_ore_area"}
```

## Mods and affixes

- Source: `build_knowledge/compact/mod_index.json`
- Matches included: `120`

### 1. ColdResistAlsoGrantsFrenzyChargeOnKillJewelUnique__1

- Match score: `80`
- `k`: ColdResistAlsoGrantsFrenzyChargeOnKillJewelUnique__1
- `n`: ColdResistAlsoGrantsFrenzyChargeOnKillJewelUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: misc
- `stats`: [{"id":"local_unique_jewel_cold_resistance_also_grants_frenzy_charge_on_kill_chance","max":1,"min":1},{"id":"local_jewel_effect_base_radius","max":1500,"min":1500}]

```json
{"k":"ColdResistAlsoGrantsFrenzyChargeOnKillJewelUnique__1","n":"ColdResistAlsoGrantsFrenzyChargeOnKillJewelUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_unique_jewel_cold_resistance_also_grants_frenzy_charge_on_kill_chance","max":1,"min":1},{"id":"local_jewel_effect_base_radius","max":1500,"min":1500}],"domain":"misc","gen":"unique","lvl":1}
```

### 2. ExpeditionLogbookMapExpeditionExplosionRadius

- Match score: `80`
- `k`: ExpeditionLogbookMapExpeditionExplosionRadius
- `n`: ExpeditionLogbookMapExpeditionExplosionRadius
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: expedition_logbook
- `domain`: area
- `stats`: [{"id":"map_expedition_explosion_radius_+%","max":50,"min":25}]

```json
{"k":"ExpeditionLogbookMapExpeditionExplosionRadius","n":"ExpeditionLogbookMapExpeditionExplosionRadius","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_expedition_explosion_radius_+%","max":50,"min":25}],"domain":"area","gen":"expedition_logbook","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 3. MapCastawayGoldConversion

- Match score: `80`
- `k`: MapCastawayGoldConversion
- `n`: MapCastawayGoldConversion
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_all_items_drop_as_gold","max":1,"min":1}]

```json
{"k":"MapCastawayGoldConversion","n":"MapCastawayGoldConversion","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_all_items_drop_as_gold","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 4. MapColdDamageStrDexIntMission

- Match score: `80`
- `k`: MapColdDamageStrDexIntMission
- `n`: MapColdDamageStrDexIntMission
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":60,"min":40}]

```json
{"k":"MapColdDamageStrDexIntMission","n":"MapColdDamageStrDexIntMission","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":60,"min":40}],"domain":"area","gen":"unique","lvl":1}
```

### 5. MapColdResistanceStrDexIntMission

- Match score: `80`
- `k`: MapColdResistanceStrDexIntMission
- `n`: MapColdResistanceStrDexIntMission
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_additional_cold_resistance","max":40,"min":40}]

```json
{"k":"MapColdResistanceStrDexIntMission","n":"MapColdResistanceStrDexIntMission","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_additional_cold_resistance","max":40,"min":40}],"domain":"area","gen":"unique","lvl":1}
```

### 6. MapEnduranceChargesStrDexIntMission

- Match score: `80`
- `k`: MapEnduranceChargesStrDexIntMission
- `n`: MapEnduranceChargesStrDexIntMission
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_gain_x_endurance_charges_every_20_seconds","max":3,"min":1}]

```json
{"k":"MapEnduranceChargesStrDexIntMission","n":"MapEnduranceChargesStrDexIntMission","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_gain_x_endurance_charges_every_20_seconds","max":3,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 7. MapFlaskChargeRecoveryUnique__1_

- Match score: `80`
- `k`: MapFlaskChargeRecoveryUnique__1_
- `n`: MapFlaskChargeRecoveryUnique__1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_flask_charges_recovered_per_3_seconds_%","max":50,"min":50}]

```json
{"k":"MapFlaskChargeRecoveryUnique__1_","n":"MapFlaskChargeRecoveryUnique__1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_flask_charges_recovered_per_3_seconds_%","max":50,"min":50}],"domain":"area","gen":"unique","lvl":1}
```

### 8. MapFrenzyChargesStrDexIntMission

- Match score: `80`
- `k`: MapFrenzyChargesStrDexIntMission
- `n`: MapFrenzyChargesStrDexIntMission
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_gain_x_frenzy_charges_every_20_seconds","max":3,"min":1}]

```json
{"k":"MapFrenzyChargesStrDexIntMission","n":"MapFrenzyChargesStrDexIntMission","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_gain_x_frenzy_charges_every_20_seconds","max":3,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 9. MapMonsterColdDamageDelve

- Match score: `80`
- `k`: MapMonsterColdDamageDelve
- `n`: MapMonsterColdDamageDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":19,"min":10}]

```json
{"k":"MapMonsterColdDamageDelve","n":"MapMonsterColdDamageDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":19,"min":10}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 10. MapMonsterColdDamageDelve2

- Match score: `80`
- `k`: MapMonsterColdDamageDelve2
- `n`: MapMonsterColdDamageDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 20
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":49,"min":20}]

```json
{"k":"MapMonsterColdDamageDelve2","n":"MapMonsterColdDamageDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":49,"min":20}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":20}
```

### 11. MapMonsterColdDamageDelve3_

- Match score: `80`
- `k`: MapMonsterColdDamageDelve3_
- `n`: MapMonsterColdDamageDelve3_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":50}]

```json
{"k":"MapMonsterColdDamageDelve3_","n":"MapMonsterColdDamageDelve3_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":50}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 12. MapMonsterColdDamageDelve4

- Match score: `80`
- `k`: MapMonsterColdDamageDelve4
- `n`: MapMonsterColdDamageDelve4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 92
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":89,"min":70}]

```json
{"k":"MapMonsterColdDamageDelve4","n":"MapMonsterColdDamageDelve4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":89,"min":70}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":92}
```

### 13. MapMonsterColdDamageDelve5

- Match score: `80`
- `k`: MapMonsterColdDamageDelve5
- `n`: MapMonsterColdDamageDelve5
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":110,"min":90}]

```json
{"k":"MapMonsterColdDamageDelve5","n":"MapMonsterColdDamageDelve5","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":110,"min":90}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 14. MapMonsterColdDamageLabyrinth1

- Match score: `80`
- `k`: MapMonsterColdDamageLabyrinth1
- `n`: MapMonsterColdDamageLabyrinth1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":60,"min":60}]

```json
{"k":"MapMonsterColdDamageLabyrinth1","n":"MapMonsterColdDamageLabyrinth1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":60,"min":60}],"domain":"area","gen":"unique","lvl":1}
```

### 15. MapMonsterColdDamageLabyrinth2

- Match score: `80`
- `k`: MapMonsterColdDamageLabyrinth2
- `n`: MapMonsterColdDamageLabyrinth2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":70,"min":70}]

```json
{"k":"MapMonsterColdDamageLabyrinth2","n":"MapMonsterColdDamageLabyrinth2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":70,"min":70}],"domain":"area","gen":"unique","lvl":1}
```

### 16. MapMonsterColdDamageLabyrinth3

- Match score: `80`
- `k`: MapMonsterColdDamageLabyrinth3
- `n`: MapMonsterColdDamageLabyrinth3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":100}]

```json
{"k":"MapMonsterColdDamageLabyrinth3","n":"MapMonsterColdDamageLabyrinth3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 17. MapMonsterColdDamagePathOfEndurance

- Match score: `80`
- `k`: MapMonsterColdDamagePathOfEndurance
- `n`: MapMonsterColdDamagePathOfEndurance
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_convert_to_cold","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":100}]

```json
{"k":"MapMonsterColdDamagePathOfEndurance","n":"MapMonsterColdDamagePathOfEndurance","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_convert_to_cold","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 18. MapMonsterColdResistanceLabyrinth1

- Match score: `80`
- `k`: MapMonsterColdResistanceLabyrinth1
- `n`: MapMonsterColdResistanceLabyrinth1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":7,"min":7},{"id":"map_item_drop_rarity_+%","max":15,"min":15},{"id":"map_monsters_additional_cold_resistance","max":40,"min":40}]

```json
{"k":"MapMonsterColdResistanceLabyrinth1","n":"MapMonsterColdResistanceLabyrinth1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":7,"min":7},{"id":"map_item_drop_rarity_+%","max":15,"min":15},{"id":"map_monsters_additional_cold_resistance","max":40,"min":40}],"domain":"area","gen":"unique","lvl":1}
```

### 19. MapMonsterColdResistanceLabyrinth2

- Match score: `80`
- `k`: MapMonsterColdResistanceLabyrinth2
- `n`: MapMonsterColdResistanceLabyrinth2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":7,"min":7},{"id":"map_item_drop_rarity_+%","max":15,"min":15},{"id":"map_monsters_additional_cold_resistance","max":60,"min":60}]

```json
{"k":"MapMonsterColdResistanceLabyrinth2","n":"MapMonsterColdResistanceLabyrinth2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":7,"min":7},{"id":"map_item_drop_rarity_+%","max":15,"min":15},{"id":"map_monsters_additional_cold_resistance","max":60,"min":60}],"domain":"area","gen":"unique","lvl":1}
```

### 20. MapMonsterColdResistanceLabyrinth3

- Match score: `80`
- `k`: MapMonsterColdResistanceLabyrinth3
- `n`: MapMonsterColdResistanceLabyrinth3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":7,"min":7},{"id":"map_item_drop_rarity_+%","max":15,"min":15},{"id":"map_monsters_additional_cold_resistance","max":80,"min":80}]

```json
{"k":"MapMonsterColdResistanceLabyrinth3","n":"MapMonsterColdResistanceLabyrinth3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":7,"min":7},{"id":"map_item_drop_rarity_+%","max":15,"min":15},{"id":"map_monsters_additional_cold_resistance","max":80,"min":80}],"domain":"area","gen":"unique","lvl":1}
```

### 21. MapMonsterLethalNoCold

- Match score: `80`
- `k`: MapMonsterLethalNoCold
- `n`: MapMonsterLethalNoCold
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_damage_+%","max":50,"min":50},{"id":"map_monsters_%_physical_damage_to_gain_as_fire","max":50,"min":50},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":50,"min":50}]

```json
{"k":"MapMonsterLethalNoCold","n":"MapMonsterLethalNoCold","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_damage_+%","max":50,"min":50},{"id":"map_monsters_%_physical_damage_to_gain_as_fire","max":50,"min":50},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":50,"min":50}],"domain":"area","gen":"unique","lvl":1}
```

### 22. MapMonsterLethalRemoveCold

- Match score: `80`
- `k`: MapMonsterLethalRemoveCold
- `n`: MapMonsterLethalRemoveCold
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_damage_+%","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_fire","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":-50,"min":-50},{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":0,"min":0}]

```json
{"k":"MapMonsterLethalRemoveCold","n":"MapMonsterLethalRemoveCold","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_damage_+%","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_fire","max":0,"min":0},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":-50,"min":-50},{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":0,"min":0}],"domain":"area","gen":"unique","lvl":1}
```

### 23. MapMonstersAvoidPoisonBleedBlindDelve

- Match score: `80`
- `k`: MapMonstersAvoidPoisonBleedBlindDelve
- `n`: MapMonstersAvoidPoisonBleedBlindDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":30,"min":30}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindDelve","n":"MapMonstersAvoidPoisonBleedBlindDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":30,"min":30}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 24. MapMonstersAvoidPoisonBleedBlindDelve2

- Match score: `80`
- `k`: MapMonstersAvoidPoisonBleedBlindDelve2
- `n`: MapMonstersAvoidPoisonBleedBlindDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":40,"min":40}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindDelve2","n":"MapMonstersAvoidPoisonBleedBlindDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":40,"min":40}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 25. MapMonstersAvoidPoisonBleedBlindDelve3

- Match score: `80`
- `k`: MapMonstersAvoidPoisonBleedBlindDelve3
- `n`: MapMonstersAvoidPoisonBleedBlindDelve3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":50,"min":50}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindDelve3","n":"MapMonstersAvoidPoisonBleedBlindDelve3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":50,"min":50}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 26. MapMonstersAvoidPoisonBleedBlindUnique__1

- Match score: `80`
- `k`: MapMonstersAvoidPoisonBleedBlindUnique__1
- `n`: MapMonstersAvoidPoisonBleedBlindUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":0,"min":0},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":50,"min":50}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindUnique__1","n":"MapMonstersAvoidPoisonBleedBlindUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":0,"min":0},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":50,"min":50}],"domain":"area","gen":"unique","lvl":1}
```

### 27. MapMonstersBlindOnHitDelve

- Match score: `80`
- `k`: MapMonstersBlindOnHitDelve
- `n`: MapMonstersBlindOnHitDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 20
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_chance_to_blind_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersBlindOnHitDelve","n":"MapMonstersBlindOnHitDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_chance_to_blind_on_hit_%","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":20}
```

### 28. MapMonstersEnduranceChargeOnHitDelve2

- Match score: `80`
- `k`: MapMonstersEnduranceChargeOnHitDelve2
- `n`: MapMonstersEnduranceChargeOnHitDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersEnduranceChargeOnHitDelve2","n":"MapMonstersEnduranceChargeOnHitDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 29. MapMonstersEnduranceChargeOnHitDelve_

- Match score: `80`
- `k`: MapMonstersEnduranceChargeOnHitDelve_
- `n`: MapMonstersEnduranceChargeOnHitDelve_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":60,"min":30}]

```json
{"k":"MapMonstersEnduranceChargeOnHitDelve_","n":"MapMonstersEnduranceChargeOnHitDelve_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":60,"min":30}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 30. MapMonstersEnduranceChargeOnHitMapWorldsUnique__1

- Match score: `80`
- `k`: MapMonstersEnduranceChargeOnHitMapWorldsUnique__1
- `n`: MapMonstersEnduranceChargeOnHitMapWorldsUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":0,"min":0},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersEnduranceChargeOnHitMapWorldsUnique__1","n":"MapMonstersEnduranceChargeOnHitMapWorldsUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":0,"min":0},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 31. MapMonstersFrenzyChargeOnHitDelve

- Match score: `80`
- `k`: MapMonstersFrenzyChargeOnHitDelve
- `n`: MapMonstersFrenzyChargeOnHitDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_frenzy_charge_on_hit_%","max":60,"min":30}]

```json
{"k":"MapMonstersFrenzyChargeOnHitDelve","n":"MapMonstersFrenzyChargeOnHitDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_frenzy_charge_on_hit_%","max":60,"min":30}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 32. MapMonstersFrenzyChargeOnHitDelve2

- Match score: `80`
- `k`: MapMonstersFrenzyChargeOnHitDelve2
- `n`: MapMonstersFrenzyChargeOnHitDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_frenzy_charge_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersFrenzyChargeOnHitDelve2","n":"MapMonstersFrenzyChargeOnHitDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_frenzy_charge_on_hit_%","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 33. MapMonstersPowerChargeOnHitDelve2

- Match score: `80`
- `k`: MapMonstersPowerChargeOnHitDelve2
- `n`: MapMonstersPowerChargeOnHitDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_power_charge_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersPowerChargeOnHitDelve2","n":"MapMonstersPowerChargeOnHitDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_power_charge_on_hit_%","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 34. MapMonstersPowerChargeOnHitDelve_

- Match score: `80`
- `k`: MapMonstersPowerChargeOnHitDelve_
- `n`: MapMonstersPowerChargeOnHitDelve_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_power_charge_on_hit_%","max":60,"min":30}]

```json
{"k":"MapMonstersPowerChargeOnHitDelve_","n":"MapMonstersPowerChargeOnHitDelve_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_power_charge_on_hit_%","max":60,"min":30}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 35. MapMonstersPowerChargeOnHitMapWorldsUnique___1

- Match score: `80`
- `k`: MapMonstersPowerChargeOnHitMapWorldsUnique___1
- `n`: MapMonstersPowerChargeOnHitMapWorldsUnique___1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":0,"min":0},{"id":"map_monsters_add_power_charge_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersPowerChargeOnHitMapWorldsUnique___1","n":"MapMonstersPowerChargeOnHitMapWorldsUnique___1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":0,"min":0},{"id":"map_monsters_add_power_charge_on_hit_%","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 36. MapMonstersRemoveChargesOnHit

- Match score: `80`
- `k`: MapMonstersRemoveChargesOnHit
- `n`: MapMonstersRemoveChargesOnHit
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_steal_charges","max":100,"min":100}]

```json
{"k":"MapMonstersRemoveChargesOnHit","n":"MapMonstersRemoveChargesOnHit","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_steal_charges","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 37. MapMonstersRemoveChargesOnHit2_

- Match score: `80`
- `k`: MapMonstersRemoveChargesOnHit2_
- `n`: MapMonstersRemoveChargesOnHit2_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_steal_charges","max":100,"min":100}]

```json
{"k":"MapMonstersRemoveChargesOnHit2_","n":"MapMonstersRemoveChargesOnHit2_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_steal_charges","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 38. MapMonstersRemoveChargesOnHit3_

- Match score: `80`
- `k`: MapMonstersRemoveChargesOnHit3_
- `n`: MapMonstersRemoveChargesOnHit3_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_steal_charges","max":100,"min":100}]

```json
{"k":"MapMonstersRemoveChargesOnHit3_","n":"MapMonstersRemoveChargesOnHit3_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_steal_charges","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 39. MapPowerChargesStrDexIntMission

- Match score: `80`
- `k`: MapPowerChargesStrDexIntMission
- `n`: MapPowerChargesStrDexIntMission
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_gain_x_power_charges_every_20_seconds","max":3,"min":1}]

```json
{"k":"MapPowerChargesStrDexIntMission","n":"MapPowerChargesStrDexIntMission","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_gain_x_power_charges_every_20_seconds","max":3,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 40. MapSimulacrumChargeDrain1

- Match score: `80`
- `k`: MapSimulacrumChargeDrain1
- `n`: MapSimulacrumChargeDrain1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_remove_charges_on_hit_%","max":5,"min":5}]

```json
{"k":"MapSimulacrumChargeDrain1","n":"MapSimulacrumChargeDrain1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_remove_charges_on_hit_%","max":5,"min":5}],"domain":"area","gen":"unique","lvl":1}
```

### 41. MapSimulacrumChargeDrain2

- Match score: `80`
- `k`: MapSimulacrumChargeDrain2
- `n`: MapSimulacrumChargeDrain2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_remove_charges_on_hit_%","max":10,"min":10}]

```json
{"k":"MapSimulacrumChargeDrain2","n":"MapSimulacrumChargeDrain2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_remove_charges_on_hit_%","max":10,"min":10}],"domain":"area","gen":"unique","lvl":1}
```

### 42. MapSimulacrumExtraColdAndAilment1

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndAilment1
- `n`: MapSimulacrumExtraColdAndAilment1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":60},{"id":"map_monsters_chance_to_inflict_brittle_%","max":33,"min":33}]

```json
{"k":"MapSimulacrumExtraColdAndAilment1","n":"MapSimulacrumExtraColdAndAilment1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":60},{"id":"map_monsters_chance_to_inflict_brittle_%","max":33,"min":33}],"domain":"area","gen":"unique","lvl":1}
```

### 43. MapSimulacrumExtraColdAndAilment2

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndAilment2
- `n`: MapSimulacrumExtraColdAndAilment2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":79,"min":70},{"id":"map_monsters_chance_to_inflict_brittle_%","max":66,"min":66}]

```json
{"k":"MapSimulacrumExtraColdAndAilment2","n":"MapSimulacrumExtraColdAndAilment2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":79,"min":70},{"id":"map_monsters_chance_to_inflict_brittle_%","max":66,"min":66}],"domain":"area","gen":"unique","lvl":1}
```

### 44. MapSimulacrumExtraColdAndAilment3

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndAilment3
- `n`: MapSimulacrumExtraColdAndAilment3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":80},{"id":"map_monsters_chance_to_inflict_brittle_%","max":100,"min":100}]

```json
{"k":"MapSimulacrumExtraColdAndAilment3","n":"MapSimulacrumExtraColdAndAilment3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":80},{"id":"map_monsters_chance_to_inflict_brittle_%","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 45. MapSimulacrumExtraColdAndPenetration1

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndPenetration1
- `n`: MapSimulacrumExtraColdAndPenetration1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":60},{"id":"map_monsters_reduce_enemy_cold_resistance_%","max":5,"min":5}]

```json
{"k":"MapSimulacrumExtraColdAndPenetration1","n":"MapSimulacrumExtraColdAndPenetration1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":60},{"id":"map_monsters_reduce_enemy_cold_resistance_%","max":5,"min":5}],"domain":"area","gen":"unique","lvl":1}
```

### 46. MapSimulacrumExtraColdAndPenetration2_

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndPenetration2_
- `n`: MapSimulacrumExtraColdAndPenetration2_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":79,"min":70},{"id":"map_monsters_reduce_enemy_cold_resistance_%","max":7,"min":7}]

```json
{"k":"MapSimulacrumExtraColdAndPenetration2_","n":"MapSimulacrumExtraColdAndPenetration2_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":79,"min":70},{"id":"map_monsters_reduce_enemy_cold_resistance_%","max":7,"min":7}],"domain":"area","gen":"unique","lvl":1}
```

### 47. MapSimulacrumExtraColdAndPenetration3__

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndPenetration3__
- `n`: MapSimulacrumExtraColdAndPenetration3__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":80},{"id":"map_monsters_reduce_enemy_cold_resistance_%","max":10,"min":10}]

```json
{"k":"MapSimulacrumExtraColdAndPenetration3__","n":"MapSimulacrumExtraColdAndPenetration3__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":80},{"id":"map_monsters_reduce_enemy_cold_resistance_%","max":10,"min":10}],"domain":"area","gen":"unique","lvl":1}
```

### 48. MapSimulacrumExtraColdAndResistance1

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndResistance1
- `n`: MapSimulacrumExtraColdAndResistance1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":60},{"id":"map_monsters_additional_cold_resistance","max":30,"min":30}]

```json
{"k":"MapSimulacrumExtraColdAndResistance1","n":"MapSimulacrumExtraColdAndResistance1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":60},{"id":"map_monsters_additional_cold_resistance","max":30,"min":30}],"domain":"area","gen":"unique","lvl":1}
```

### 49. MapSimulacrumExtraColdAndResistance2__

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndResistance2__
- `n`: MapSimulacrumExtraColdAndResistance2__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":79,"min":70},{"id":"map_monsters_additional_cold_resistance","max":40,"min":40}]

```json
{"k":"MapSimulacrumExtraColdAndResistance2__","n":"MapSimulacrumExtraColdAndResistance2__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":79,"min":70},{"id":"map_monsters_additional_cold_resistance","max":40,"min":40}],"domain":"area","gen":"unique","lvl":1}
```

### 50. MapSimulacrumExtraColdAndResistance3

- Match score: `80`
- `k`: MapSimulacrumExtraColdAndResistance3
- `n`: MapSimulacrumExtraColdAndResistance3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":80},{"id":"map_monsters_additional_cold_resistance","max":50,"min":50}]

```json
{"k":"MapSimulacrumExtraColdAndResistance3","n":"MapSimulacrumExtraColdAndResistance3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":100,"min":80},{"id":"map_monsters_additional_cold_resistance","max":50,"min":50}],"domain":"area","gen":"unique","lvl":1}
```

### 51. UltimatumUniqueMapCooldownSpeed

- Match score: `80`
- `k`: UltimatumUniqueMapCooldownSpeed
- `n`: UltimatumUniqueMapCooldownSpeed
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_ultimatum_unique_map_boss_cooldown_speed","max":1,"min":1}]

```json
{"k":"UltimatumUniqueMapCooldownSpeed","n":"UltimatumUniqueMapCooldownSpeed","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_ultimatum_unique_map_boss_cooldown_speed","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 52. UltimatumUniqueMapLoseCharges

- Match score: `80`
- `k`: UltimatumUniqueMapLoseCharges
- `n`: UltimatumUniqueMapLoseCharges
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_ultimatum_unique_map_boss_lose_charges","max":1,"min":1}]

```json
{"k":"UltimatumUniqueMapLoseCharges","n":"UltimatumUniqueMapLoseCharges","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_ultimatum_unique_map_boss_lose_charges","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 53. AddedColdDamagePerFrenzyChargeEssence1

- Match score: `70`
- `k`: AddedColdDamagePerFrenzyChargeEssence1
- `n`: AddedColdDamagePerFrenzyChargeEssence1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AddedColdDamagePerFrenzyChargeEssence1","n":"AddedColdDamagePerFrenzyChargeEssence1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":63}
```

### 54. AddedColdDamagePerFrenzyChargeEssenceQuiver1

- Match score: `70`
- `k`: AddedColdDamagePerFrenzyChargeEssenceQuiver1
- `n`: AddedColdDamagePerFrenzyChargeEssenceQuiver1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AddedColdDamagePerFrenzyChargeEssenceQuiver1","n":"AddedColdDamagePerFrenzyChargeEssenceQuiver1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":63}
```

### 55. AddedColdDamagePerFrenzyChargeUnique__1

- Match score: `70`
- `k`: AddedColdDamagePerFrenzyChargeUnique__1
- `n`: AddedColdDamagePerFrenzyChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"minimum_added_cold_damage_per_frenzy_charge","max":12,"min":12},{"id":"maximum_added_cold_damage_per_frenzy_charge","max":14,"min":14}]

```json
{"k":"AddedColdDamagePerFrenzyChargeUnique__1","n":"AddedColdDamagePerFrenzyChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"minimum_added_cold_damage_per_frenzy_charge","max":12,"min":12},{"id":"maximum_added_cold_damage_per_frenzy_charge","max":14,"min":14}],"domain":"item","gen":"unique","lvl":1}
```

### 56. AddedColdDamagePerPowerChargeUnique__1

- Match score: `70`
- `k`: AddedColdDamagePerPowerChargeUnique__1
- `n`: AddedColdDamagePerPowerChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"spell_minimum_added_cold_damage_per_power_charge","max":10,"min":10},{"id":"spell_maximum_added_cold_damage_per_power_charge","max":20,"min":20}]

```json
{"k":"AddedColdDamagePerPowerChargeUnique__1","n":"AddedColdDamagePerPowerChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"spell_minimum_added_cold_damage_per_power_charge","max":10,"min":10},{"id":"spell_maximum_added_cold_damage_per_power_charge","max":20,"min":20}],"domain":"item","gen":"unique","lvl":1}
```

### 57. AddedColdDamagePerPowerChargeUnique__2

- Match score: `70`
- `k`: AddedColdDamagePerPowerChargeUnique__2
- `n`: AddedColdDamagePerPowerChargeUnique__2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"spell_minimum_added_cold_damage_per_power_charge","max":50,"min":50},{"id":"spell_maximum_added_cold_damage_per_power_charge","max":70,"min":70}]

```json
{"k":"AddedColdDamagePerPowerChargeUnique__2","n":"AddedColdDamagePerPowerChargeUnique__2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"spell_minimum_added_cold_damage_per_power_charge","max":50,"min":50},{"id":"spell_maximum_added_cold_damage_per_power_charge","max":70,"min":70}],"domain":"item","gen":"unique","lvl":1}
```

### 58. AreaOfEffectPerEnduranceChargeUnique__1

- Match score: `70`
- `k`: AreaOfEffectPerEnduranceChargeUnique__1
- `n`: AreaOfEffectPerEnduranceChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"area_of_effect_+%_per_endurance_charge","max":2,"min":2}]

```json
{"k":"AreaOfEffectPerEnduranceChargeUnique__1","n":"AreaOfEffectPerEnduranceChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"area_of_effect_+%_per_endurance_charge","max":2,"min":2}],"domain":"item","gen":"unique","lvl":1}
```

### 59. ChargeBonusAddedColdDamagePerFrenzyCharge

- Match score: `70`
- `k`: ChargeBonusAddedColdDamagePerFrenzyCharge
- `n`: ChargeBonusAddedColdDamagePerFrenzyCharge
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"minimum_added_cold_damage_per_frenzy_charge","max":8,"min":6},{"id":"maximum_added_cold_damage_per_frenzy_charge","max":13,"min":12}]

```json
{"k":"ChargeBonusAddedColdDamagePerFrenzyCharge","n":"ChargeBonusAddedColdDamagePerFrenzyCharge","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"minimum_added_cold_damage_per_frenzy_charge","max":8,"min":6},{"id":"maximum_added_cold_damage_per_frenzy_charge","max":13,"min":12}],"domain":"item","gen":"unique","lvl":1}
```

### 60. ChargeBonusColdDamageAddedAsChaos

- Match score: `70`
- `k`: ChargeBonusColdDamageAddedAsChaos
- `n`: ChargeBonusColdDamageAddedAsChaos
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"non_skill_cold_damage_%_to_gain_as_chaos_per_frenzy_charge","max":1,"min":1}]

```json
{"k":"ChargeBonusColdDamageAddedAsChaos","n":"ChargeBonusColdDamageAddedAsChaos","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_cold_damage_%_to_gain_as_chaos_per_frenzy_charge","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 61. ColdAndPhysicalNodesInRadiusSwapPropertiesUniqueJewel48_

- Match score: `70`
- `k`: ColdAndPhysicalNodesInRadiusSwapPropertiesUniqueJewel48_
- `n`: ColdAndPhysicalNodesInRadiusSwapPropertiesUniqueJewel48_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: misc
- `stats`: [{"id":"local_unique_jewel_physical_damage_increases_applies_to_cold_damage","max":1,"min":1},{"id":"local_unique_jewel_cold_damage_increases_applies_to_physical_damage","max":1,"min":1},{"id":"local_jewel_effect_base_radius","max":1500,"min":1500}]

```json
{"k":"ColdAndPhysicalNodesInRadiusSwapPropertiesUniqueJewel48_","n":"ColdAndPhysicalNodesInRadiusSwapPropertiesUniqueJewel48_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_unique_jewel_physical_damage_increases_applies_to_cold_damage","max":1,"min":1},{"id":"local_unique_jewel_cold_damage_increases_applies_to_physical_damage","max":1,"min":1},{"id":"local_jewel_effect_base_radius","max":1500,"min":1500}],"domain":"misc","gen":"unique","lvl":1}
```

### 62. CraftedJewelRadiusColdResistance

- Match score: `70`
- `k`: CraftedJewelRadiusColdResistance
- `n`: CraftedJewelRadiusColdResistance
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: suffix
- `domain`: misc
- `stats`: [{"id":"base_cold_damage_resistance_%","max":7,"min":5}]

```json
{"k":"CraftedJewelRadiusColdResistance","n":"CraftedJewelRadiusColdResistance","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_cold_damage_resistance_%","max":7,"min":5}],"domain":"misc","gen":"suffix","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 63. DaemonMapBossSummonKamikazeDemon_

- Match score: `70`
- `k`: DaemonMapBossSummonKamikazeDemon_
- `n`: DaemonMapBossSummonKamikazeDemon_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"display_monster_mod_nemesis_test","max":0,"min":0}]

```json
{"k":"DaemonMapBossSummonKamikazeDemon_","n":"DaemonMapBossSummonKamikazeDemon_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"display_monster_mod_nemesis_test","max":0,"min":0}],"domain":"monster","gen":"unique","lvl":1}
```

### 64. HarbingerMapAreaContainsAdditionalHarbingers

- Match score: `70`
- `k`: HarbingerMapAreaContainsAdditionalHarbingers
- `n`: HarbingerMapAreaContainsAdditionalHarbingers
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_num_extra_harbingers","max":6,"min":6}]

```json
{"k":"HarbingerMapAreaContainsAdditionalHarbingers","n":"HarbingerMapAreaContainsAdditionalHarbingers","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_num_extra_harbingers","max":6,"min":6}],"domain":"area","gen":"unique","lvl":1}
```

### 65. HarbingerMapAreaContainsAdditionalHarbingersUber

- Match score: `70`
- `k`: HarbingerMapAreaContainsAdditionalHarbingersUber
- `n`: HarbingerMapAreaContainsAdditionalHarbingersUber
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_num_extra_harbingers","max":20,"min":20}]

```json
{"k":"HarbingerMapAreaContainsAdditionalHarbingersUber","n":"HarbingerMapAreaContainsAdditionalHarbingersUber","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_num_extra_harbingers","max":20,"min":20}],"domain":"area","gen":"unique","lvl":1}
```

### 66. IncreasedAreaOfSkillsWithNoFrenzyChargesUnique__1_

- Match score: `70`
- `k`: IncreasedAreaOfSkillsWithNoFrenzyChargesUnique__1_
- `n`: IncreasedAreaOfSkillsWithNoFrenzyChargesUnique__1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"skill_area_of_effect_+%_while_no_frenzy_charges","max":15,"min":15}]

```json
{"k":"IncreasedAreaOfSkillsWithNoFrenzyChargesUnique__1_","n":"IncreasedAreaOfSkillsWithNoFrenzyChargesUnique__1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"skill_area_of_effect_+%_while_no_frenzy_charges","max":15,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 67. IncreasedColdDamagePerFrenzyChargeUnique__1

- Match score: `70`
- `k`: IncreasedColdDamagePerFrenzyChargeUnique__1
- `n`: IncreasedColdDamagePerFrenzyChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cold_damage_+%_per_frenzy_charge","max":20,"min":15}]

```json
{"k":"IncreasedColdDamagePerFrenzyChargeUnique__1","n":"IncreasedColdDamagePerFrenzyChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cold_damage_+%_per_frenzy_charge","max":20,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 68. IncreasedColdDamagePerFrenzyChargeUnique__2

- Match score: `70`
- `k`: IncreasedColdDamagePerFrenzyChargeUnique__2
- `n`: IncreasedColdDamagePerFrenzyChargeUnique__2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cold_damage_+%_per_frenzy_charge","max":20,"min":15}]

```json
{"k":"IncreasedColdDamagePerFrenzyChargeUnique__2","n":"IncreasedColdDamagePerFrenzyChargeUnique__2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cold_damage_+%_per_frenzy_charge","max":20,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 69. IzaroColdConversionBuff1

- Match score: `70`
- `k`: IzaroColdConversionBuff1
- `n`: IzaroColdConversionBuff1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"non_skill_base_physical_damage_%_to_gain_as_cold","max":10,"min":10}]

```json
{"k":"IzaroColdConversionBuff1","n":"IzaroColdConversionBuff1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_base_physical_damage_%_to_gain_as_cold","max":10,"min":10}],"domain":"monster","gen":"unique","lvl":1}
```

### 70. IzaroColdConversionBuff2

- Match score: `70`
- `k`: IzaroColdConversionBuff2
- `n`: IzaroColdConversionBuff2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"non_skill_base_physical_damage_%_to_gain_as_cold","max":20,"min":20}]

```json
{"k":"IzaroColdConversionBuff2","n":"IzaroColdConversionBuff2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_base_physical_damage_%_to_gain_as_cold","max":20,"min":20}],"domain":"monster","gen":"unique","lvl":1}
```

### 71. MapAreaContainsAbysses

- Match score: `70`
- `k`: MapAreaContainsAbysses
- `n`: MapAreaContainsAbysses
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_num_extra_abysses","max":2,"min":2},{"id":"dummy_stat_display_nothing","max":0,"min":0},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsAbysses","n":"MapAreaContainsAbysses","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_num_extra_abysses","max":2,"min":2},{"id":"dummy_stat_display_nothing","max":0,"min":0},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 72. MapAreaContainsBreaches_

- Match score: `70`
- `k`: MapAreaContainsBreaches_
- `n`: MapAreaContainsBreaches_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_contains_additional_breaches","max":3,"min":3},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsBreaches_","n":"MapAreaContainsBreaches_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_contains_additional_breaches","max":3,"min":3},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 73. MapAreaContainsEssences

- Match score: `70`
- `k`: MapAreaContainsEssences
- `n`: MapAreaContainsEssences
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_has_monoliths","max":0,"min":0},{"id":"map_extra_monoliths","max":3,"min":3},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsEssences","n":"MapAreaContainsEssences","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_has_monoliths","max":0,"min":0},{"id":"map_extra_monoliths","max":3,"min":3},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 74. MapAreaContainsExiles__

- Match score: `70`
- `k`: MapAreaContainsExiles__
- `n`: MapAreaContainsExiles__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"map_spawn_extra_exiles","max":10,"min":10}]

```json
{"k":"MapAreaContainsExiles__","n":"MapAreaContainsExiles__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_spawn_extra_exiles","max":10,"min":10}],"domain":"item","gen":"unique","lvl":1}
```

### 75. MapAreaContainsExpeditions____

- Match score: `70`
- `k`: MapAreaContainsExpeditions____
- `n`: MapAreaContainsExpeditions____
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_expedition_league","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsExpeditions____","n":"MapAreaContainsExpeditions____","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_expedition_league","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 76. MapAreaContainsGuardedVaalVessels

- Match score: `70`
- `k`: MapAreaContainsGuardedVaalVessels
- `n`: MapAreaContainsGuardedVaalVessels
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_expedition_encounter_additional_chance_%","max":100,"min":100}]

```json
{"k":"MapAreaContainsGuardedVaalVessels","n":"MapAreaContainsGuardedVaalVessels","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_expedition_encounter_additional_chance_%","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 77. MapAreaContainsHarbingers

- Match score: `70`
- `k`: MapAreaContainsHarbingers
- `n`: MapAreaContainsHarbingers
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_num_extra_harbingers","max":3,"min":3},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsHarbingers","n":"MapAreaContainsHarbingers","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_num_extra_harbingers","max":3,"min":3},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 78. MapAreaContainsHarvest

- Match score: `70`
- `k`: MapAreaContainsHarvest
- `n`: MapAreaContainsHarvest
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_harvest_league","max":1,"min":1},{"id":"map_chance_for_area_%_to_contain_harvest","max":100,"min":100},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsHarvest","n":"MapAreaContainsHarvest","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_harvest_league","max":1,"min":1},{"id":"map_chance_for_area_%_to_contain_harvest","max":100,"min":100},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 79. MapAreaContainsHeistCaches

- Match score: `70`
- `k`: MapAreaContainsHeistCaches
- `n`: MapAreaContainsHeistCaches
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"dummy_stat_display_nothing","max":0,"min":0},{"id":"map_heist_league","max":0,"min":0},{"id":"map_spawn_x_additional_heist_smugglers_caches","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsHeistCaches","n":"MapAreaContainsHeistCaches","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"dummy_stat_display_nothing","max":0,"min":0},{"id":"map_heist_league","max":0,"min":0},{"id":"map_spawn_x_additional_heist_smugglers_caches","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 80. MapAreaContainsInvasionBosses

- Match score: `70`
- `k`: MapAreaContainsInvasionBosses
- `n`: MapAreaContainsInvasionBosses
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"map_num_extra_invasion_bosses","max":5,"min":5},{"id":"dummy_stat_display_nothing","max":0,"min":0},{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsInvasionBosses","n":"MapAreaContainsInvasionBosses","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_num_extra_invasion_bosses","max":5,"min":5},{"id":"dummy_stat_display_nothing","max":0,"min":0},{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 81. MapAreaContainsLegionMonoliths

- Match score: `70`
- `k`: MapAreaContainsLegionMonoliths
- `n`: MapAreaContainsLegionMonoliths
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_legion_league","max":1,"min":1},{"id":"map_legion_league_extra_spawns","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsLegionMonoliths","n":"MapAreaContainsLegionMonoliths","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_legion_league","max":1,"min":1},{"id":"map_legion_league_extra_spawns","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 82. MapAreaContainsMetamorphs_

- Match score: `70`
- `k`: MapAreaContainsMetamorphs_
- `n`: MapAreaContainsMetamorphs_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_area_contains_metamorphs","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsMetamorphs_","n":"MapAreaContainsMetamorphs_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_area_contains_metamorphs","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 83. MapAreaContainsRituals_

- Match score: `70`
- `k`: MapAreaContainsRituals_
- `n`: MapAreaContainsRituals_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_area_contains_rituals","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsRituals_","n":"MapAreaContainsRituals_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_area_contains_rituals","max":1,"min":1},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 84. MapAreaContainsTormentedSpirits

- Match score: `70`
- `k`: MapAreaContainsTormentedSpirits
- `n`: MapAreaContainsTormentedSpirits
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_spawn_extra_torment_spirits","max":5,"min":5},{"id":"map_extra_content_weighting","max":1,"min":1}]

```json
{"k":"MapAreaContainsTormentedSpirits","n":"MapAreaContainsTormentedSpirits","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_spawn_extra_torment_spirits","max":5,"min":5},{"id":"map_extra_content_weighting","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 85. MapAreaLevel

- Match score: `70`
- `k`: MapAreaLevel
- `n`: MapAreaLevel
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_level_+","max":1,"min":1}]

```json
{"k":"MapAreaLevel","n":"MapAreaLevel","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_level_+","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 86. MapAtlasBreachIsCold

- Match score: `70`
- `k`: MapAtlasBreachIsCold
- `n`: MapAtlasBreachIsCold
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: atlas
- `stats`: [{"id":"sextant_uses_remaining","max":3,"min":3},{"id":"map_breach_type_override","max":3,"min":3},{"id":"map_breaches_num_additional_chests_to_spawn","max":3,"min":3}]

```json
{"k":"MapAtlasBreachIsCold","n":"MapAtlasBreachIsCold","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"sextant_uses_remaining","max":3,"min":3},{"id":"map_breach_type_override","max":3,"min":3},{"id":"map_breaches_num_additional_chests_to_spawn","max":3,"min":3}],"domain":"atlas","gen":"prefix","weights":[{"tag":"unique_map","weight":0},{"tag":"default","weight":1}],"lvl":1}
```

### 87. MapAtlasBreachIsColdMaven

- Match score: `70`
- `k`: MapAtlasBreachIsColdMaven
- `n`: MapAtlasBreachIsColdMaven
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: atlas
- `stats`: [{"id":"sextant_uses_remaining","max":15,"min":15},{"id":"map_breach_type_override","max":3,"min":3},{"id":"map_breaches_num_additional_chests_to_spawn","max":3,"min":3}]

```json
{"k":"MapAtlasBreachIsColdMaven","n":"MapAtlasBreachIsColdMaven","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"sextant_uses_remaining","max":15,"min":15},{"id":"map_breach_type_override","max":3,"min":3},{"id":"map_breaches_num_additional_chests_to_spawn","max":3,"min":3}],"domain":"atlas","gen":"prefix","weights":[{"tag":"unique_map","weight":0},{"tag":"default","weight":1}],"lvl":1}
```

### 88. MapAtlasColdDamageAndPacks3

- Match score: `70`
- `k`: MapAtlasColdDamageAndPacks3
- `n`: MapAtlasColdDamageAndPacks3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: atlas
- `stats`: [{"id":"sextant_uses_remaining","max":3,"min":3},{"id":"map_contains_additional_packs_of_cold_monsters","max":6,"min":6},{"id":"map_players_and_monsters_cold_damage_taken_+%","max":12,"min":12}]

```json
{"k":"MapAtlasColdDamageAndPacks3","n":"MapAtlasColdDamageAndPacks3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"sextant_uses_remaining","max":3,"min":3},{"id":"map_contains_additional_packs_of_cold_monsters","max":6,"min":6},{"id":"map_players_and_monsters_cold_damage_taken_+%","max":12,"min":12}],"domain":"atlas","gen":"prefix","weights":[{"tag":"no_monster_packs","weight":0},{"tag":"default","weight":1}],"lvl":1}
```

### 89. MapAtlasColdDamageAndPacksMaven_

- Match score: `70`
- `k`: MapAtlasColdDamageAndPacksMaven_
- `n`: MapAtlasColdDamageAndPacksMaven_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: atlas
- `stats`: [{"id":"sextant_uses_remaining","max":15,"min":15},{"id":"map_contains_additional_packs_of_cold_monsters","max":8,"min":8},{"id":"map_players_and_monsters_cold_damage_taken_+%","max":14,"min":14}]

```json
{"k":"MapAtlasColdDamageAndPacksMaven_","n":"MapAtlasColdDamageAndPacksMaven_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"sextant_uses_remaining","max":15,"min":15},{"id":"map_contains_additional_packs_of_cold_monsters","max":8,"min":8},{"id":"map_players_and_monsters_cold_damage_taken_+%","max":14,"min":14}],"domain":"atlas","gen":"prefix","weights":[{"tag":"no_monster_packs","weight":0},{"tag":"default","weight":1}],"lvl":1}
```

### 90. MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCost

- Match score: `70`
- `k`: MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCost
- `n`: MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCost
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: atlas
- `stats`: [{"id":"sextant_uses_remaining","max":3,"min":3},{"id":"map_ritual_number_of_free_rerolls","max":1,"min":1}]

```json
{"k":"MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCost","n":"MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCost","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"sextant_uses_remaining","max":3,"min":3},{"id":"map_ritual_number_of_free_rerolls","max":1,"min":1}],"domain":"atlas","gen":"prefix","weights":[{"tag":"unique_map","weight":0},{"tag":"no_monster_packs","weight":0},{"tag":"default","weight":1}],"lvl":1}
```

### 91. MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCostMaven

- Match score: `70`
- `k`: MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCostMaven
- `n`: MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCostMaven
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: atlas
- `stats`: [{"id":"sextant_uses_remaining","max":15,"min":15},{"id":"map_ritual_number_of_free_rerolls","max":1,"min":1}]

```json
{"k":"MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCostMaven","n":"MapAtlasRitualsInAreasCanBeRerolledOnceAtNoCostMaven","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"sextant_uses_remaining","max":15,"min":15},{"id":"map_ritual_number_of_free_rerolls","max":1,"min":1}],"domain":"atlas","gen":"prefix","weights":[{"tag":"unique_map","weight":0},{"tag":"no_monster_packs","weight":0},{"tag":"default","weight":1}],"lvl":1}
```

### 92. MapDoesntConsumeSextantCharge_

- Match score: `70`
- `k`: MapDoesntConsumeSextantCharge_
- `n`: MapDoesntConsumeSextantCharge_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"map_doesnt_consume_sextant_use","max":1,"min":1}]

```json
{"k":"MapDoesntConsumeSextantCharge_","n":"MapDoesntConsumeSextantCharge_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_doesnt_consume_sextant_use","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 93. MapDoesntConsumeSextantChargeChance

- Match score: `70`
- `k`: MapDoesntConsumeSextantChargeChance
- `n`: MapDoesntConsumeSextantChargeChance
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"map_chance_to_not_consume_sextant_use_%","max":50,"min":50}]

```json
{"k":"MapDoesntConsumeSextantChargeChance","n":"MapDoesntConsumeSextantChargeChance","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_chance_to_not_consume_sextant_use_%","max":50,"min":50}],"domain":"item","gen":"unique","lvl":1}
```

### 94. MapForceCorruptedSideArea

- Match score: `70`
- `k`: MapForceCorruptedSideArea
- `n`: MapForceCorruptedSideArea
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_force_side_area","max":1,"min":1}]

```json
{"k":"MapForceCorruptedSideArea","n":"MapForceCorruptedSideArea","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_force_side_area","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 95. MapIsQuestArea

- Match score: `70`
- `k`: MapIsQuestArea
- `n`: MapIsQuestArea
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_is_quest_area","max":1,"min":1}]

```json
{"k":"MapIsQuestArea","n":"MapIsQuestArea","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_is_quest_area","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 96. MapLeaguestoneAreaContainsAdditionalLeaguestone

- Match score: `70`
- `k`: MapLeaguestoneAreaContainsAdditionalLeaguestone
- `n`: MapLeaguestoneAreaContainsAdditionalLeaguestone
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: suffix
- `domain`: leaguestone
- `stats`: [{"id":"map_leaguestone_area_contains_x_additional_leaguestones","max":1,"min":1}]

```json
{"k":"MapLeaguestoneAreaContainsAdditionalLeaguestone","n":"MapLeaguestoneAreaContainsAdditionalLeaguestone","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_leaguestone_area_contains_x_additional_leaguestones","max":1,"min":1}],"domain":"leaguestone","gen":"suffix","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 97. MapMissionSubAreaMods

- Match score: `70`
- `k`: MapMissionSubAreaMods
- `n`: MapMissionSubAreaMods
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_extra_ruleset","max":0,"min":0},{"id":"map_mission_variation","max":0,"min":0},{"id":"map_mission_variation2","max":0,"min":0},{"id":"map_disable_missions","max":0,"min":0},{"id":"map_daily_mission_master_level","max":0,"min":0}]

```json
{"k":"MapMissionSubAreaMods","n":"MapMissionSubAreaMods","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_extra_ruleset","max":0,"min":0},{"id":"map_mission_variation","max":0,"min":0},{"id":"map_mission_variation2","max":0,"min":0},{"id":"map_disable_missions","max":0,"min":0},{"id":"map_daily_mission_master_level","max":0,"min":0}],"domain":"area","gen":"unique","lvl":1}
```

### 98. MapMonsterAreaOfEffectDelve

- Match score: `70`
- `k`: MapMonsterAreaOfEffectDelve
- `n`: MapMonsterAreaOfEffectDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":30,"min":30}]

```json
{"k":"MapMonsterAreaOfEffectDelve","n":"MapMonsterAreaOfEffectDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":30,"min":30}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 99. MapMonsterAreaOfEffectDelve2

- Match score: `70`
- `k`: MapMonsterAreaOfEffectDelve2
- `n`: MapMonsterAreaOfEffectDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 20
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":45,"min":45}]

```json
{"k":"MapMonsterAreaOfEffectDelve2","n":"MapMonsterAreaOfEffectDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":45,"min":45}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":20}
```

### 100. MapMonsterAreaOfEffectDelve3_

- Match score: `70`
- `k`: MapMonsterAreaOfEffectDelve3_
- `n`: MapMonsterAreaOfEffectDelve3_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":60,"min":60}]

```json
{"k":"MapMonsterAreaOfEffectDelve3_","n":"MapMonsterAreaOfEffectDelve3_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":60,"min":60}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 101. MapMonsterAreaOfEffectDelve4

- Match score: `70`
- `k`: MapMonsterAreaOfEffectDelve4
- `n`: MapMonsterAreaOfEffectDelve4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 92
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":75,"min":75}]

```json
{"k":"MapMonsterAreaOfEffectDelve4","n":"MapMonsterAreaOfEffectDelve4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":75,"min":75}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":92}
```

### 102. MapMonsterAreaOfEffectDelve5

- Match score: `70`
- `k`: MapMonsterAreaOfEffectDelve5
- `n`: MapMonsterAreaOfEffectDelve5
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":100,"min":100}]

```json
{"k":"MapMonsterAreaOfEffectDelve5","n":"MapMonsterAreaOfEffectDelve5","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":100,"min":100}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 103. MapMonsterAreaOfEffectLabyrinth1

- Match score: `70`
- `k`: MapMonsterAreaOfEffectLabyrinth1
- `n`: MapMonsterAreaOfEffectLabyrinth1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_area_of_effect_+%","max":45,"min":45}]

```json
{"k":"MapMonsterAreaOfEffectLabyrinth1","n":"MapMonsterAreaOfEffectLabyrinth1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_area_of_effect_+%","max":45,"min":45}],"domain":"area","gen":"unique","lvl":1}
```

### 104. MapMonsterAreaOfEffectLabyrinth2

- Match score: `70`
- `k`: MapMonsterAreaOfEffectLabyrinth2
- `n`: MapMonsterAreaOfEffectLabyrinth2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_area_of_effect_+%","max":70,"min":70}]

```json
{"k":"MapMonsterAreaOfEffectLabyrinth2","n":"MapMonsterAreaOfEffectLabyrinth2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_area_of_effect_+%","max":70,"min":70}],"domain":"area","gen":"unique","lvl":1}
```

### 105. MapMonsterAreaOfEffectLabyrinth3

- Match score: `70`
- `k`: MapMonsterAreaOfEffectLabyrinth3
- `n`: MapMonsterAreaOfEffectLabyrinth3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_area_of_effect_+%","max":100,"min":100}]

```json
{"k":"MapMonsterAreaOfEffectLabyrinth3","n":"MapMonsterAreaOfEffectLabyrinth3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":20,"min":20},{"id":"map_monsters_area_of_effect_+%","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 106. MapMonsterAreaOfEffectSynthesis

- Match score: `70`
- `k`: MapMonsterAreaOfEffectSynthesis
- `n`: MapMonsterAreaOfEffectSynthesis
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":30,"min":30}]

```json
{"k":"MapMonsterAreaOfEffectSynthesis","n":"MapMonsterAreaOfEffectSynthesis","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":30,"min":30}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 107. MapMonsterAreaOfEffectSynthesis2

- Match score: `70`
- `k`: MapMonsterAreaOfEffectSynthesis2
- `n`: MapMonsterAreaOfEffectSynthesis2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 49
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":45,"min":45}]

```json
{"k":"MapMonsterAreaOfEffectSynthesis2","n":"MapMonsterAreaOfEffectSynthesis2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":45,"min":45}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":49}
```

### 108. MapMonsterAreaOfEffectSynthesis3__

- Match score: `70`
- `k`: MapMonsterAreaOfEffectSynthesis3__
- `n`: MapMonsterAreaOfEffectSynthesis3__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 68
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":60,"min":60}]

```json
{"k":"MapMonsterAreaOfEffectSynthesis3__","n":"MapMonsterAreaOfEffectSynthesis3__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":60,"min":60}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":68}
```

### 109. MapMonsterAreaOfEffectSynthesis4

- Match score: `70`
- `k`: MapMonsterAreaOfEffectSynthesis4
- `n`: MapMonsterAreaOfEffectSynthesis4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 73
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":75,"min":75}]

```json
{"k":"MapMonsterAreaOfEffectSynthesis4","n":"MapMonsterAreaOfEffectSynthesis4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":75,"min":75}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":73}
```

### 110. MapMonsterAreaOfEffectSynthesis5

- Match score: `70`
- `k`: MapMonsterAreaOfEffectSynthesis5
- `n`: MapMonsterAreaOfEffectSynthesis5
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 79
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":100,"min":100}]

```json
{"k":"MapMonsterAreaOfEffectSynthesis5","n":"MapMonsterAreaOfEffectSynthesis5","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_area_of_effect_+%","max":100,"min":100}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":79}
```

### 111. MapMonsterColdDamageSynthesis

- Match score: `70`
- `k`: MapMonsterColdDamageSynthesis
- `n`: MapMonsterColdDamageSynthesis
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":19,"min":10}]

```json
{"k":"MapMonsterColdDamageSynthesis","n":"MapMonsterColdDamageSynthesis","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":19,"min":10}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 112. MapMonsterColdDamageSynthesis2_

- Match score: `70`
- `k`: MapMonsterColdDamageSynthesis2_
- `n`: MapMonsterColdDamageSynthesis2_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 49
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":49,"min":20}]

```json
{"k":"MapMonsterColdDamageSynthesis2_","n":"MapMonsterColdDamageSynthesis2_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":49,"min":20}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":49}
```

### 113. MapMonsterColdDamageSynthesis3_

- Match score: `70`
- `k`: MapMonsterColdDamageSynthesis3_
- `n`: MapMonsterColdDamageSynthesis3_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 68
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":50}]

```json
{"k":"MapMonsterColdDamageSynthesis3_","n":"MapMonsterColdDamageSynthesis3_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":69,"min":50}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":68}
```

### 114. MapMonsterColdDamageSynthesis4

- Match score: `70`
- `k`: MapMonsterColdDamageSynthesis4
- `n`: MapMonsterColdDamageSynthesis4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 73
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":89,"min":70}]

```json
{"k":"MapMonsterColdDamageSynthesis4","n":"MapMonsterColdDamageSynthesis4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":89,"min":70}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":73}
```

### 115. MapMonsterColdDamageSynthesis5__

- Match score: `70`
- `k`: MapMonsterColdDamageSynthesis5__
- `n`: MapMonsterColdDamageSynthesis5__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 79
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":110,"min":90}]

```json
{"k":"MapMonsterColdDamageSynthesis5__","n":"MapMonsterColdDamageSynthesis5__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_%_physical_damage_to_gain_as_cold","max":110,"min":90}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":79}
```

### 116. MapMonstersAvoidPoisonBleedBlindSynthesis

- Match score: `70`
- `k`: MapMonstersAvoidPoisonBleedBlindSynthesis
- `n`: MapMonstersAvoidPoisonBleedBlindSynthesis
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":20,"min":20}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindSynthesis","n":"MapMonstersAvoidPoisonBleedBlindSynthesis","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":20,"min":20}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 117. MapMonstersAvoidPoisonBleedBlindSynthesis2

- Match score: `70`
- `k`: MapMonstersAvoidPoisonBleedBlindSynthesis2
- `n`: MapMonstersAvoidPoisonBleedBlindSynthesis2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 68
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":30,"min":30}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindSynthesis2","n":"MapMonstersAvoidPoisonBleedBlindSynthesis2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":30,"min":30}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":68}
```

### 118. MapMonstersAvoidPoisonBleedBlindSynthesis3

- Match score: `70`
- `k`: MapMonstersAvoidPoisonBleedBlindSynthesis3
- `n`: MapMonstersAvoidPoisonBleedBlindSynthesis3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 79
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":40,"min":40}]

```json
{"k":"MapMonstersAvoidPoisonBleedBlindSynthesis3","n":"MapMonstersAvoidPoisonBleedBlindSynthesis3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_avoid_poison_bleed_impale_%","max":40,"min":40}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":79}
```

### 119. MapMonstersEnduranceChargeOnHitSynthesis2__

- Match score: `70`
- `k`: MapMonstersEnduranceChargeOnHitSynthesis2__
- `n`: MapMonstersEnduranceChargeOnHitSynthesis2__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 68
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":100,"min":100}]

```json
{"k":"MapMonstersEnduranceChargeOnHitSynthesis2__","n":"MapMonstersEnduranceChargeOnHitSynthesis2__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":100,"min":100}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":68}
```

### 120. MapMonstersEnduranceChargeOnHitSynthesis_

- Match score: `70`
- `k`: MapMonstersEnduranceChargeOnHitSynthesis_
- `n`: MapMonstersEnduranceChargeOnHitSynthesis_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":60,"min":30}]

```json
{"k":"MapMonstersEnduranceChargeOnHitSynthesis_","n":"MapMonstersEnduranceChargeOnHitSynthesis_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":13,"min":13},{"id":"map_item_drop_rarity_+%","max":8,"min":8},{"id":"map_pack_size_+%","max":5,"min":5},{"id":"map_monsters_add_endurance_charge_on_hit_%","max":60,"min":30}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":1}
```

## Rune mods

- Source: `build_knowledge/compact/rune_mod_index.json`
- Matches included: `1`

### 1. Rune of Culmination

- Match score: `35`
- `k`: Rune of Culmination
- `n`: Rune of Culmination
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Rune of Culmination","n":"Rune of Culmination","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

## Uniques

- Source: `build_knowledge/compact/unique_index.json`
- Matches included: `3`

### 1. Enezun's Charge

- Match score: `35`
- `id`: Enezun's Charge
- `k`: 209
- `n`: Enezun's Charge
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"209","n":"Enezun's Charge","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Enezun's Charge","item_class":"Wand"}
```

### 2. Scold's Bridle

- Match score: `35`
- `id`: Scold's Bridle
- `k`: 297
- `n`: Scold's Bridle
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"297","n":"Scold's Bridle","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Scold's Bridle","item_class":"Helmet"}
```

### 3. Eshtera's Path

- Match score: `10`
- `id`: Sekhema's Resolve Cold
- `k`: 234
- `n`: Eshtera's Path
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"234","n":"Eshtera's Path","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Sekhema's Resolve Cold","item_class":"Ring"}
```

## Misc

- Source: `build_knowledge/compact/misc_index.json`
- Matches included: `120`

### 1. With at least 40 [Intelligence] in Radius, Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
With at least 40 [Intelligence] in Radius, Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges

- Match score: `210`
- `k`: With at least 40 [Intelligence] in Radius, Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
With at least 40 [Intelligence] in Radius, Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges
- `n`: With at least 40 [Intelligence] in Radius, Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
With at least 40 [Intelligence] in Radius, Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"With at least 40 [Intelligence] in Radius, Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area\nWith at least 40 [Intelligence] in Radius, Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges","n":"With at least 40 [Intelligence] in Radius, Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area\nWith at least 40 [Intelligence] in Radius, Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 2. Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges

- Match score: `175`
- `k`: Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges
- `n`: Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area\nCold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges","n":"Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area\nCold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 3. Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges

- Match score: `140`
- `k`: Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges
- `n`: Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges","n":"Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 4. With at least 40 [Intelligence] in Radius, Cold Snap
has a {0}% chance to grant a Power Charge on Killing Blow

- Match score: `140`
- `k`: With at least 40 [Intelligence] in Radius, Cold Snap
has a {0}% chance to grant a Power Charge on Killing Blow
- `n`: With at least 40 [Intelligence] in Radius, Cold Snap
has a {0}% chance to grant a Power Charge on Killing Blow
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"With at least 40 [Intelligence] in Radius, Cold Snap\nhas a {0}% chance to grant a Power Charge on Killing Blow","n":"With at least 40 [Intelligence] in Radius, Cold Snap\nhas a {0}% chance to grant a Power Charge on Killing Blow","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 5. +{0} metre to explosion radius if a
[Charges|Power Charge] was Consumed

- Match score: `105`
- `k`: +{0} metre to explosion radius if a
[Charges|Power Charge] was Consumed
- `n`: +{0} metre to explosion radius if a
[Charges|Power Charge] was Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"+{0} metre to explosion radius if a\n[Charges|Power Charge] was Consumed","n":"+{0} metre to explosion radius if a\n[Charges|Power Charge] was Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 6. +{0} metres to explosion radius if a
[Charges|Power Charge] was Consumed

- Match score: `105`
- `k`: +{0} metres to explosion radius if a
[Charges|Power Charge] was Consumed
- `n`: +{0} metres to explosion radius if a
[Charges|Power Charge] was Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"+{0} metres to explosion radius if a\n[Charges|Power Charge] was Consumed","n":"+{0} metres to explosion radius if a\n[Charges|Power Charge] was Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 7. Adds {0} minimum Cold Damage to Spells per Power Charge

- Match score: `105`
- `k`: Adds {0} minimum Cold Damage to Spells per Power Charge
- `n`: Adds {0} minimum Cold Damage to Spells per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} minimum Cold Damage to Spells per Power Charge","n":"Adds {0} minimum Cold Damage to Spells per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 8. Adds {0} to {1} Cold Damage to Spells per Power Charge

- Match score: `105`
- `k`: Adds {0} to {1} Cold Damage to Spells per Power Charge
- `n`: Adds {0} to {1} Cold Damage to Spells per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} to {1} Cold Damage to Spells per Power Charge","n":"Adds {0} to {1} Cold Damage to Spells per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 9. Adds {1} maximum Cold Damage to Spells per Power Charge

- Match score: `105`
- `k`: Adds {1} maximum Cold Damage to Spells per Power Charge
- `n`: Adds {1} maximum Cold Damage to Spells per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {1} maximum Cold Damage to Spells per Power Charge","n":"Adds {1} maximum Cold Damage to Spells per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 10. Bonus radius if [Charges|Power Charge] Consumed@+{0}m

- Match score: `105`
- `k`: Bonus radius if [Charges|Power Charge] Consumed@+{0}m
- `n`: Bonus radius if [Charges|Power Charge] Consumed@+{0}m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Bonus radius if [Charges|Power Charge] Consumed@+{0}m","n":"Bonus radius if [Charges|Power Charge] Consumed@+{0}m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 11. Charged Dash has {0} to Radius of each Wave's last damage Area

- Match score: `105`
- `k`: Charged Dash has {0} to Radius of each Wave's last damage Area
- `n`: Charged Dash has {0} to Radius of each Wave's last damage Area
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Charged Dash has {0} to Radius of each Wave's last damage Area","n":"Charged Dash has {0} to Radius of each Wave's last damage Area","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 12. Cold Snap has a {0}% chance to grant a Power Charge on Killing Blow

- Match score: `105`
- `k`: Cold Snap has a {0}% chance to grant a Power Charge on Killing Blow
- `n`: Cold Snap has a {0}% chance to grant a Power Charge on Killing Blow
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Cold Snap has a {0}% chance to grant a Power Charge on Killing Blow","n":"Cold Snap has a {0}% chance to grant a Power Charge on Killing Blow","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 13. Gain a Power Charge when an Enemy Dies while in this Skill's Area

- Match score: `105`
- `k`: Gain a Power Charge when an Enemy Dies while in this Skill's Area
- `n`: Gain a Power Charge when an Enemy Dies while in this Skill's Area
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Power Charge when an Enemy Dies while in this Skill's Area","n":"Gain a Power Charge when an Enemy Dies while in this Skill's Area","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 14. Gain a Power Charge when an Enemy Dies while in this Skill's Area
Every second, gain a Power Charge if an Enemy is in Skill's Area

- Match score: `105`
- `k`: Gain a Power Charge when an Enemy Dies while in this Skill's Area
Every second, gain a Power Charge if an Enemy is in Skill's Area
- `n`: Gain a Power Charge when an Enemy Dies while in this Skill's Area
Every second, gain a Power Charge if an Enemy is in Skill's Area
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Power Charge when an Enemy Dies while in this Skill's Area\nEvery second, gain a Power Charge if an Enemy is in Skill's Area","n":"Gain a Power Charge when an Enemy Dies while in this Skill's Area\nEvery second, gain a Power Charge if an Enemy is in Skill's Area","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 15. More Area per [Charges|Power Charge] Consumed@{0}%

- Match score: `105`
- `k`: More Area per [Charges|Power Charge] Consumed@{0}%
- `n`: More Area per [Charges|Power Charge] Consumed@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More Area per [Charges|Power Charge] Consumed@{0}%","n":"More Area per [Charges|Power Charge] Consumed@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 16. Passives granting Cold Resistance or all Elemental Resistances in Radius
also grant an equal chance to gain a Frenzy Charge on Kill

- Match score: `105`
- `k`: Passives granting Cold Resistance or all Elemental Resistances in Radius
also grant an equal chance to gain a Frenzy Charge on Kill
- `n`: Passives granting Cold Resistance or all Elemental Resistances in Radius
also grant an equal chance to gain a Frenzy Charge on Kill
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Passives granting Cold Resistance or all Elemental Resistances in Radius\nalso grant an equal chance to gain a Frenzy Charge on Kill","n":"Passives granting Cold Resistance or all Elemental Resistances in Radius\nalso grant an equal chance to gain a Frenzy Charge on Kill","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 17. Passives granting Lightning Resistance or all Elemental Resistances in Radius
also grant an equal chance to gain a Power Charge on Kill

- Match score: `105`
- `k`: Passives granting Lightning Resistance or all Elemental Resistances in Radius
also grant an equal chance to gain a Power Charge on Kill
- `n`: Passives granting Lightning Resistance or all Elemental Resistances in Radius
also grant an equal chance to gain a Power Charge on Kill
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Passives granting Lightning Resistance or all Elemental Resistances in Radius\nalso grant an equal chance to gain a Power Charge on Kill","n":"Passives granting Lightning Resistance or all Elemental Resistances in Radius\nalso grant an equal chance to gain a Power Charge on Kill","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 18. Supported Skills have {0}% increased Trap Trigger Radius per Power Charge

- Match score: `105`
- `k`: Supported Skills have {0}% increased Trap Trigger Radius per Power Charge
- `n`: Supported Skills have {0}% increased Trap Trigger Radius per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills have {0}% increased Trap Trigger Radius per Power Charge","n":"Supported Skills have {0}% increased Trap Trigger Radius per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 19. Supported Skills have {0}% reduced Trap Trigger Radius per Power Charge

- Match score: `105`
- `k`: Supported Skills have {0}% reduced Trap Trigger Radius per Power Charge
- `n`: Supported Skills have {0}% reduced Trap Trigger Radius per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills have {0}% reduced Trap Trigger Radius per Power Charge","n":"Supported Skills have {0}% reduced Trap Trigger Radius per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 20. Take {0} Cold Damage on reaching Maximum Power Charges

- Match score: `105`
- `k`: Take {0} Cold Damage on reaching Maximum Power Charges
- `n`: Take {0} Cold Damage on reaching Maximum Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Take {0} Cold Damage on reaching Maximum Power Charges","n":"Take {0} Cold Damage on reaching Maximum Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 21. Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed

- Match score: `105`
- `k`: Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed
- `n`: Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed","n":"Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 22. Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed

- Match score: `105`
- `k`: Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed
- `n`: Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed","n":"Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 23. With at least 40 [Intelligence] in Radius, Discharge Cooldown is {0} ms

- Match score: `105`
- `k`: With at least 40 [Intelligence] in Radius, Discharge Cooldown is {0} ms
- `n`: With at least 40 [Intelligence] in Radius, Discharge Cooldown is {0} ms
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"With at least 40 [Intelligence] in Radius, Discharge Cooldown is {0} ms","n":"With at least 40 [Intelligence] in Radius, Discharge Cooldown is {0} ms","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 24. With at least 40 [Intelligence] in Radius, Discharge has {0}% less Area of Effect

- Match score: `105`
- `k`: With at least 40 [Intelligence] in Radius, Discharge has {0}% less Area of Effect
- `n`: With at least 40 [Intelligence] in Radius, Discharge has {0}% less Area of Effect
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"With at least 40 [Intelligence] in Radius, Discharge has {0}% less Area of Effect","n":"With at least 40 [Intelligence] in Radius, Discharge has {0}% less Area of Effect","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 25. With at least 40 [Intelligence] in Radius, Discharge has {0}% more Area of Effect

- Match score: `105`
- `k`: With at least 40 [Intelligence] in Radius, Discharge has {0}% more Area of Effect
- `n`: With at least 40 [Intelligence] in Radius, Discharge has {0}% more Area of Effect
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"With at least 40 [Intelligence] in Radius, Discharge has {0}% more Area of Effect","n":"With at least 40 [Intelligence] in Radius, Discharge has {0}% more Area of Effect","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 26. {0} second to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills

- Match score: `105`
- `k`: {0} second to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills
- `n`: {0} second to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0} second to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills","n":"{0} second to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 27. {0} seconds to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills

- Match score: `105`
- `k`: {0} seconds to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills
- `n`: {0} seconds to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0} seconds to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills","n":"{0} seconds to current [ESRecharge|Energy Shield Recharge] delay per [Combo] expended when using Skills","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 28. {0}% [SurpassChance|Surpassing] chance to gain a [Charges|Power Charge] when expending [Combo] with Supported Skills per [Combo] expended

- Match score: `105`
- `k`: {0}% [SurpassChance|Surpassing] chance to gain a [Charges|Power Charge] when expending [Combo] with Supported Skills per [Combo] expended
- `n`: {0}% [SurpassChance|Surpassing] chance to gain a [Charges|Power Charge] when expending [Combo] with Supported Skills per [Combo] expended
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% [SurpassChance|Surpassing] chance to gain a [Charges|Power Charge] when expending [Combo] with Supported Skills per [Combo] expended","n":"{0}% [SurpassChance|Surpassing] chance to gain a [Charges|Power Charge] when expending [Combo] with Supported Skills per [Combo] expended","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 29. {0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area

- Match score: `105`
- `k`: {0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area
- `n`: {0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area","n":"{0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 30. {0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area
Every second, gain a Power Charge if an Enemy is in this Skill's Area

- Match score: `105`
- `k`: {0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area
Every second, gain a Power Charge if an Enemy is in this Skill's Area
- `n`: {0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area
Every second, gain a Power Charge if an Enemy is in this Skill's Area
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area\nEvery second, gain a Power Charge if an Enemy is in this Skill's Area","n":"{0}% chance to gain a Power Charge when an Enemy Dies while in this Skill's Area\nEvery second, gain a Power Charge if an Enemy is in this Skill's Area","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 31. {0}% increased [EnergyShield|Energy Shield] per Power Charge

- Match score: `105`
- `k`: {0}% increased [EnergyShield|Energy Shield] per Power Charge
- `n`: {0}% increased [EnergyShield|Energy Shield] per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [EnergyShield|Energy Shield] per Power Charge","n":"{0}% increased [EnergyShield|Energy Shield] per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 32. {0}% increased Area of Effect per Power Charge

- Match score: `105`
- `k`: {0}% increased Area of Effect per Power Charge
- `n`: {0}% increased Area of Effect per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased Area of Effect per Power Charge","n":"{0}% increased Area of Effect per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 33. {0}% increased Area of Effect per Power Charge, up to a maximum of 50%

- Match score: `105`
- `k`: {0}% increased Area of Effect per Power Charge, up to a maximum of 50%
- `n`: {0}% increased Area of Effect per Power Charge, up to a maximum of 50%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased Area of Effect per Power Charge, up to a maximum of 50%","n":"{0}% increased Area of Effect per Power Charge, up to a maximum of 50%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 34. {0}% increased Cooldown Recovery Rate per Power Charge

- Match score: `105`
- `k`: {0}% increased Cooldown Recovery Rate per Power Charge
- `n`: {0}% increased Cooldown Recovery Rate per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased Cooldown Recovery Rate per Power Charge","n":"{0}% increased Cooldown Recovery Rate per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 35. {0}% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]

- Match score: `105`
- `k`: {0}% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]
- `n`: {0}% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]","n":"{0}% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 36. {0}% increased Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge

- Match score: `105`
- `k`: {0}% increased Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge
- `n`: {0}% increased Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge","n":"{0}% increased Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 37. {0}% increased Trap Trigger Radius per Power Charge

- Match score: `105`
- `k`: {0}% increased Trap Trigger Radius per Power Charge
- `n`: {0}% increased Trap Trigger Radius per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased Trap Trigger Radius per Power Charge","n":"{0}% increased Trap Trigger Radius per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 38. {0}% less Area of Effect per [Charges|Power Charge] Consumed

- Match score: `105`
- `k`: {0}% less Area of Effect per [Charges|Power Charge] Consumed
- `n`: {0}% less Area of Effect per [Charges|Power Charge] Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% less Area of Effect per [Charges|Power Charge] Consumed","n":"{0}% less Area of Effect per [Charges|Power Charge] Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 39. {0}% more Area of Effect per [Charges|Power Charge] Consumed

- Match score: `105`
- `k`: {0}% more Area of Effect per [Charges|Power Charge] Consumed
- `n`: {0}% more Area of Effect per [Charges|Power Charge] Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% more Area of Effect per [Charges|Power Charge] Consumed","n":"{0}% more Area of Effect per [Charges|Power Charge] Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 40. {0}% reduced Cooldown Recovery Rate per Power Charge

- Match score: `105`
- `k`: {0}% reduced Cooldown Recovery Rate per Power Charge
- `n`: {0}% reduced Cooldown Recovery Rate per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced Cooldown Recovery Rate per Power Charge","n":"{0}% reduced Cooldown Recovery Rate per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 41. {0}% reduced maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]

- Match score: `105`
- `k`: {0}% reduced maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]
- `n`: {0}% reduced maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]","n":"{0}% reduced maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 42. {0}% reduced Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge

- Match score: `105`
- `k`: {0}% reduced Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge
- `n`: {0}% reduced Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge","n":"{0}% reduced Recovery rate of Life and [EnergyShield|Energy Shield] per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 43. {0}% reduced Trap Trigger Radius per Power Charge

- Match score: `105`
- `k`: {0}% reduced Trap Trigger Radius per Power Charge
- `n`: {0}% reduced Trap Trigger Radius per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced Trap Trigger Radius per Power Charge","n":"{0}% reduced Trap Trigger Radius per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 44. -{0} second to base [ESRecharge|Energy Shield Recharge] delay

- Match score: `70`
- `k`: -{0} second to base [ESRecharge|Energy Shield Recharge] delay
- `n`: -{0} second to base [ESRecharge|Energy Shield Recharge] delay
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"-{0} second to base [ESRecharge|Energy Shield Recharge] delay","n":"-{0} second to base [ESRecharge|Energy Shield Recharge] delay","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 45. -{0} seconds to base [ESRecharge|Energy Shield Recharge] delay

- Match score: `70`
- `k`: -{0} seconds to base [ESRecharge|Energy Shield Recharge] delay
- `n`: -{0} seconds to base [ESRecharge|Energy Shield Recharge] delay
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"-{0} seconds to base [ESRecharge|Energy Shield Recharge] delay","n":"-{0} seconds to base [ESRecharge|Energy Shield Recharge] delay","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 46. 1 [Rarity|Rare] Monster in [Biome|Swamp] Areas has {0}% chance to be replaced by a random [MapBoss|Map Boss]

- Match score: `70`
- `k`: 1 [Rarity|Rare] Monster in [Biome|Swamp] Areas has {0}% chance to be replaced by a random [MapBoss|Map Boss]
- `n`: 1 [Rarity|Rare] Monster in [Biome|Swamp] Areas has {0}% chance to be replaced by a random [MapBoss|Map Boss]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"1 [Rarity|Rare] Monster in [Biome|Swamp] Areas has {0}% chance to be replaced by a random [MapBoss|Map Boss]","n":"1 [Rarity|Rare] Monster in [Biome|Swamp] Areas has {0}% chance to be replaced by a random [MapBoss|Map Boss]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 47. 1 [Rarity|Rare] Monster in [Biome|Swamp] Areas is replaced by a random [MapBoss|Map Boss]

- Match score: `70`
- `k`: 1 [Rarity|Rare] Monster in [Biome|Swamp] Areas is replaced by a random [MapBoss|Map Boss]
- `n`: 1 [Rarity|Rare] Monster in [Biome|Swamp] Areas is replaced by a random [MapBoss|Map Boss]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"1 [Rarity|Rare] Monster in [Biome|Swamp] Areas is replaced by a random [MapBoss|Map Boss]","n":"1 [Rarity|Rare] Monster in [Biome|Swamp] Areas is replaced by a random [MapBoss|Map Boss]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 48. 1% [FasterESRechargeStart|faster start of Energy Shield Recharge] per {0} maximum [Ward|Runic Ward]

- Match score: `70`
- `k`: 1% [FasterESRechargeStart|faster start of Energy Shield Recharge] per {0} maximum [Ward|Runic Ward]
- `n`: 1% [FasterESRechargeStart|faster start of Energy Shield Recharge] per {0} maximum [Ward|Runic Ward]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"1% [FasterESRechargeStart|faster start of Energy Shield Recharge] per {0} maximum [Ward|Runic Ward]","n":"1% [FasterESRechargeStart|faster start of Energy Shield Recharge] per {0} maximum [Ward|Runic Ward]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 49. 1% increased [ESRechargeRate|Energy Shield Recharge Rate] per {0} maximum [Ward|Runic Ward]

- Match score: `70`
- `k`: 1% increased [ESRechargeRate|Energy Shield Recharge Rate] per {0} maximum [Ward|Runic Ward]
- `n`: 1% increased [ESRechargeRate|Energy Shield Recharge Rate] per {0} maximum [Ward|Runic Ward]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"1% increased [ESRechargeRate|Energy Shield Recharge Rate] per {0} maximum [Ward|Runic Ward]","n":"1% increased [ESRechargeRate|Energy Shield Recharge Rate] per {0} maximum [Ward|Runic Ward]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 50. 25% chance for [AbyssalDepths|Abyssal Depths] in Level 78+ Areas to contain a Boss
25% chance for an Ulaman pit near the [MapBoss|Map Boss] to have the Incubator Queen

- Match score: `70`
- `k`: 25% chance for [AbyssalDepths|Abyssal Depths] in Level 78+ Areas to contain a Boss
25% chance for an Ulaman pit near the [MapBoss|Map Boss] to have the Incubator Queen
- `n`: 25% chance for [AbyssalDepths|Abyssal Depths] in Level 78+ Areas to contain a Boss
25% chance for an Ulaman pit near the [MapBoss|Map Boss] to have the Incubator Queen
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"25% chance for [AbyssalDepths|Abyssal Depths] in Level 78+ Areas to contain a Boss\n25% chance for an Ulaman pit near the [MapBoss|Map Boss] to have the Incubator Queen","n":"25% chance for [AbyssalDepths|Abyssal Depths] in Level 78+ Areas to contain a Boss\n25% chance for an Ulaman pit near the [MapBoss|Map Boss] to have the Incubator Queen","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 51. 3% more [Spell|Spell] Damage per [Charges|Power Charge]
Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]

- Match score: `70`
- `k`: 3% more [Spell|Spell] Damage per [Charges|Power Charge]
Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
- `n`: 3% more [Spell|Spell] Damage per [Charges|Power Charge]
Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"3% more [Spell|Spell] Damage per [Charges|Power Charge]\nGain [Charges|Power Charges] instead of [Charges|Frenzy Charges]","n":"3% more [Spell|Spell] Damage per [Charges|Power Charge]\nGain [Charges|Power Charges] instead of [Charges|Frenzy Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 52. 5% of [Physical] Damage prevented [Recoup|Recouped] as [EnergyShield|Energy Shield] per enemy [Power]
[EnergyShield|Energy Shield] does not [ESRecharge|Recharge]
You cannot Recover [EnergyShield|Energy Shield] from Regeneration
You cannot Recover [EnergyShield|Energy Shield] to above [Armour]

- Match score: `70`
- `k`: 5% of [Physical] Damage prevented [Recoup|Recouped] as [EnergyShield|Energy Shield] per enemy [Power]
[EnergyShield|Energy Shield] does not [ESRecharge|Recharge]
You cannot Recover [EnergyShield|Energy Shield] from Regeneration
You cannot Recover [EnergyShield|Energy Shield] to above [Armour]
- `n`: 5% of [Physical] Damage prevented [Recoup|Recouped] as [EnergyShield|Energy Shield] per enemy [Power]
[EnergyShield|Energy Shield] does not [ESRecharge|Recharge]
You cannot Recover [EnergyShield|Energy Shield] from Regeneration
You cannot Recover [EnergyShield|Energy Shield] to above [Armour]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"5% of [Physical] Damage prevented [Recoup|Recouped] as [EnergyShield|Energy Shield] per enemy [Power]\n[EnergyShield|Energy Shield] does not [ESRecharge|Recharge]\nYou cannot Recover [EnergyShield|Energy Shield] from Regeneration\nYou cannot Recover [EnergyShield|Energy Shield] to above [Armour]","n":"5% of [Physical] Damage prevented [Recoup|Recouped] as [EnergyShield|Energy Shield] per enemy [Power]\n[EnergyShield|Energy Shield] does not [ESRecharge|Recharge]\nYou cannot Recover [EnergyShield|Energy Shield] from Regeneration\nYou cannot Recover [EnergyShield|Energy Shield] to above [Armour]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 53. 80% more Area Radius against Enemies affected by an Ailment of the chosen Element

- Match score: `70`
- `k`: 80% more Area Radius against Enemies affected by an Ailment of the chosen Element
- `n`: 80% more Area Radius against Enemies affected by an Ailment of the chosen Element
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"80% more Area Radius against Enemies affected by an Ailment of the chosen Element","n":"80% more Area Radius against Enemies affected by an Ailment of the chosen Element","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 54. [Aura] grants {0}% increased [ESRechargeRate|Energy Shield Recharge Rate]

- Match score: `70`
- `k`: [Aura] grants {0}% increased [ESRechargeRate|Energy Shield Recharge Rate]
- `n`: [Aura] grants {0}% increased [ESRechargeRate|Energy Shield Recharge Rate]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Aura] grants {0}% increased [ESRechargeRate|Energy Shield Recharge Rate]","n":"[Aura] grants {0}% increased [ESRechargeRate|Energy Shield Recharge Rate]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 55. [Aura] grants {0}% reduced [ESRechargeRate|Energy Shield Recharge Rate]

- Match score: `70`
- `k`: [Aura] grants {0}% reduced [ESRechargeRate|Energy Shield Recharge Rate]
- `n`: [Aura] grants {0}% reduced [ESRechargeRate|Energy Shield Recharge Rate]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Aura] grants {0}% reduced [ESRechargeRate|Energy Shield Recharge Rate]","n":"[Aura] grants {0}% reduced [ESRechargeRate|Energy Shield Recharge Rate]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 56. [Biome|City] Areas have a {0}% chance to be [InvadedCityMap|Invaded] by another faction

- Match score: `70`
- `k`: [Biome|City] Areas have a {0}% chance to be [InvadedCityMap|Invaded] by another faction
- `n`: [Biome|City] Areas have a {0}% chance to be [InvadedCityMap|Invaded] by another faction
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Biome|City] Areas have a {0}% chance to be [InvadedCityMap|Invaded] by another faction","n":"[Biome|City] Areas have a {0}% chance to be [InvadedCityMap|Invaded] by another faction","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 57. [Biome|City] Areas have {0}% chance to be [AbandonedCityMap|Abandoned] and occupied by the Undead

- Match score: `70`
- `k`: [Biome|City] Areas have {0}% chance to be [AbandonedCityMap|Abandoned] and occupied by the Undead
- `n`: [Biome|City] Areas have {0}% chance to be [AbandonedCityMap|Abandoned] and occupied by the Undead
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Biome|City] Areas have {0}% chance to be [AbandonedCityMap|Abandoned] and occupied by the Undead","n":"[Biome|City] Areas have {0}% chance to be [AbandonedCityMap|Abandoned] and occupied by the Undead","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 58. [Buff] duration is {0} seconds per [Charges|Power Charge] Consumed

- Match score: `70`
- `k`: [Buff] duration is {0} seconds per [Charges|Power Charge] Consumed
- `n`: [Buff] duration is {0} seconds per [Charges|Power Charge] Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Buff] duration is {0} seconds per [Charges|Power Charge] Consumed","n":"[Buff] duration is {0} seconds per [Charges|Power Charge] Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 59. [Buff] duration per [Charges|Power Charge]@{0}s

- Match score: `70`
- `k`: [Buff] duration per [Charges|Power Charge]@{0}s
- `n`: [Buff] duration per [Charges|Power Charge]@{0}s
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Buff] duration per [Charges|Power Charge]@{0}s","n":"[Buff] duration per [Charges|Power Charge]@{0}s","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 60. [Buff] grants {0}% Increased [ESRecharge|Energy Shield Recharge Rate]

- Match score: `70`
- `k`: [Buff] grants {0}% Increased [ESRecharge|Energy Shield Recharge Rate]
- `n`: [Buff] grants {0}% Increased [ESRecharge|Energy Shield Recharge Rate]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Buff] grants {0}% Increased [ESRecharge|Energy Shield Recharge Rate]","n":"[Buff] grants {0}% Increased [ESRecharge|Energy Shield Recharge Rate]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 61. [ChilledGround|Chilled Ground] conversion radius@{0}m

- Match score: `70`
- `k`: [ChilledGround|Chilled Ground] conversion radius@{0}m
- `n`: [ChilledGround|Chilled Ground] conversion radius@{0}m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ChilledGround|Chilled Ground] conversion radius@{0}m","n":"[ChilledGround|Chilled Ground] conversion radius@{0}m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 62. [CoalescedCorruption|Coalesced Corruption] in your Maps have {0}% increased Merging Radius

- Match score: `70`
- `k`: [CoalescedCorruption|Coalesced Corruption] in your Maps have {0}% increased Merging Radius
- `n`: [CoalescedCorruption|Coalesced Corruption] in your Maps have {0}% increased Merging Radius
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[CoalescedCorruption|Coalesced Corruption] in your Maps have {0}% increased Merging Radius","n":"[CoalescedCorruption|Coalesced Corruption] in your Maps have {0}% increased Merging Radius","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 63. [Cold|Cold] Resistance is unaffected by [Resistances|Area Penalties]

- Match score: `70`
- `k`: [Cold|Cold] Resistance is unaffected by [Resistances|Area Penalties]
- `n`: [Cold|Cold] Resistance is unaffected by [Resistances|Area Penalties]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Cold|Cold] Resistance is unaffected by [Resistances|Area Penalties]","n":"[Cold|Cold] Resistance is unaffected by [Resistances|Area Penalties]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 64. [ContainsBreach|Breaches] in your Maps expand to at least {0} metre in radius
[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters

- Match score: `70`
- `k`: [ContainsBreach|Breaches] in your Maps expand to at least {0} metre in radius
[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters
- `n`: [ContainsBreach|Breaches] in your Maps expand to at least {0} metre in radius
[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ContainsBreach|Breaches] in your Maps expand to at least {0} metre in radius\n[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters","n":"[ContainsBreach|Breaches] in your Maps expand to at least {0} metre in radius\n[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 65. [ContainsBreach|Breaches] in your Maps expand to at least {0} metres in radius
[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters

- Match score: `70`
- `k`: [ContainsBreach|Breaches] in your Maps expand to at least {0} metres in radius
[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters
- `n`: [ContainsBreach|Breaches] in your Maps expand to at least {0} metres in radius
[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ContainsBreach|Breaches] in your Maps expand to at least {0} metres in radius\n[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters","n":"[ContainsBreach|Breaches] in your Maps expand to at least {0} metres in radius\n[ContainsBreach|Breaches] in your Maps remain open while there are alive Breach Monsters","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 66. [ContainsIrradiated|Non-Irradiated] Areas with [PowerfulMapBoss|Powerful Map Bosses] have +1 Level

- Match score: `70`
- `k`: [ContainsIrradiated|Non-Irradiated] Areas with [PowerfulMapBoss|Powerful Map Bosses] have +1 Level
- `n`: [ContainsIrradiated|Non-Irradiated] Areas with [PowerfulMapBoss|Powerful Map Bosses] have +1 Level
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ContainsIrradiated|Non-Irradiated] Areas with [PowerfulMapBoss|Powerful Map Bosses] have +1 Level","n":"[ContainsIrradiated|Non-Irradiated] Areas with [PowerfulMapBoss|Powerful Map Bosses] have +1 Level","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 67. [Conversion|Convert] {0}% of [Fire] Damage with [Mace] Skills to [Cold] Damage

- Match score: `70`
- `k`: [Conversion|Convert] {0}% of [Fire] Damage with [Mace] Skills to [Cold] Damage
- `n`: [Conversion|Convert] {0}% of [Fire] Damage with [Mace] Skills to [Cold] Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Conversion|Convert] {0}% of [Fire] Damage with [Mace] Skills to [Cold] Damage","n":"[Conversion|Convert] {0}% of [Fire] Damage with [Mace] Skills to [Cold] Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 68. [Conversion|Converts] {0}% of [Cold] damage to [Fire] damage

- Match score: `70`
- `k`: [Conversion|Converts] {0}% of [Cold] damage to [Fire] damage
- `n`: [Conversion|Converts] {0}% of [Cold] damage to [Fire] damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Conversion|Converts] {0}% of [Cold] damage to [Fire] damage","n":"[Conversion|Converts] {0}% of [Cold] damage to [Fire] damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 69. [Conversion|Converts] {0}% of [Physical|Physical] damage to [Cold|Cold] damage

- Match score: `70`
- `k`: [Conversion|Converts] {0}% of [Physical|Physical] damage to [Cold|Cold] damage
- `n`: [Conversion|Converts] {0}% of [Physical|Physical] damage to [Cold|Cold] damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Conversion|Converts] {0}% of [Physical|Physical] damage to [Cold|Cold] damage","n":"[Conversion|Converts] {0}% of [Physical|Physical] damage to [Cold|Cold] damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 70. [Corrupted] [Waystone|Waystones] open a Random Map Area when used on [BasicMap|Basic Maps]

- Match score: `70`
- `k`: [Corrupted] [Waystone|Waystones] open a Random Map Area when used on [BasicMap|Basic Maps]
- `n`: [Corrupted] [Waystone|Waystones] open a Random Map Area when used on [BasicMap|Basic Maps]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Corrupted] [Waystone|Waystones] open a Random Map Area when used on [BasicMap|Basic Maps]","n":"[Corrupted] [Waystone|Waystones] open a Random Map Area when used on [BasicMap|Basic Maps]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 71. [Curse|Cursed] Enemies grant a Power Charge when [HitDamage|Hit]

- Match score: `70`
- `k`: [Curse|Cursed] Enemies grant a Power Charge when [HitDamage|Hit]
- `n`: [Curse|Cursed] Enemies grant a Power Charge when [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Curse|Cursed] Enemies grant a Power Charge when [HitDamage|Hit]","n":"[Curse|Cursed] Enemies grant a Power Charge when [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 72. [Curse|Cursed] Enemies have a {0}% chance to grant a Power Charge when [HitDamage|Hit]

- Match score: `70`
- `k`: [Curse|Cursed] Enemies have a {0}% chance to grant a Power Charge when [HitDamage|Hit]
- `n`: [Curse|Cursed] Enemies have a {0}% chance to grant a Power Charge when [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Curse|Cursed] Enemies have a {0}% chance to grant a Power Charge when [HitDamage|Hit]","n":"[Curse|Cursed] Enemies have a {0}% chance to grant a Power Charge when [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 73. [DeliriumSplinter|Simulacrum Splinters] can drop from [ContainsDelirium|Delirium] Monsters in level 75+ Map Areas

- Match score: `70`
- `k`: [DeliriumSplinter|Simulacrum Splinters] can drop from [ContainsDelirium|Delirium] Monsters in level 75+ Map Areas
- `n`: [DeliriumSplinter|Simulacrum Splinters] can drop from [ContainsDelirium|Delirium] Monsters in level 75+ Map Areas
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[DeliriumSplinter|Simulacrum Splinters] can drop from [ContainsDelirium|Delirium] Monsters in level 75+ Map Areas","n":"[DeliriumSplinter|Simulacrum Splinters] can drop from [ContainsDelirium|Delirium] Monsters in level 75+ Map Areas","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 74. [DNT-Unused] [Conversion|Convert] {0}% of [Physical] Damage with [Mace] Skills to [Cold] Damage

- Match score: `70`
- `k`: [DNT-Unused] [Conversion|Convert] {0}% of [Physical] Damage with [Mace] Skills to [Cold] Damage
- `n`: [DNT-Unused] [Conversion|Convert] {0}% of [Physical] Damage with [Mace] Skills to [Cold] Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[DNT-Unused] [Conversion|Convert] {0}% of [Physical] Damage with [Mace] Skills to [Cold] Damage","n":"[DNT-Unused] [Conversion|Convert] {0}% of [Physical] Damage with [Mace] Skills to [Cold] Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 75. [DNT-UNUSED]With at least 40 [Intelligence] in Radius, each Lightning Tendrils Repeat has {0}% increased Area of Effect per Enemy Hit

- Match score: `70`
- `k`: [DNT-UNUSED]With at least 40 [Intelligence] in Radius, each Lightning Tendrils Repeat has {0}% increased Area of Effect per Enemy Hit
- `n`: [DNT-UNUSED]With at least 40 [Intelligence] in Radius, each Lightning Tendrils Repeat has {0}% increased Area of Effect per Enemy Hit
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[DNT-UNUSED]With at least 40 [Intelligence] in Radius, each Lightning Tendrils Repeat has {0}% increased Area of Effect per Enemy Hit","n":"[DNT-UNUSED]With at least 40 [Intelligence] in Radius, each Lightning Tendrils Repeat has {0}% increased Area of Effect per Enemy Hit","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 76. [EnergyShield|Energy Shield] is increased by [UncappedResist|Uncapped] [Resistances|Cold Resistance]

- Match score: `70`
- `k`: [EnergyShield|Energy Shield] is increased by [UncappedResist|Uncapped] [Resistances|Cold Resistance]
- `n`: [EnergyShield|Energy Shield] is increased by [UncappedResist|Uncapped] [Resistances|Cold Resistance]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[EnergyShield|Energy Shield] is increased by [UncappedResist|Uncapped] [Resistances|Cold Resistance]","n":"[EnergyShield|Energy Shield] is increased by [UncappedResist|Uncapped] [Resistances|Cold Resistance]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 77. [EnergyShield|Energy Shield] Recharge begins immediately and is not interrupted by Damage for {0} seconds when [Stun|Stunned] while using Supported Skills

- Match score: `70`
- `k`: [EnergyShield|Energy Shield] Recharge begins immediately and is not interrupted by Damage for {0} seconds when [Stun|Stunned] while using Supported Skills
- `n`: [EnergyShield|Energy Shield] Recharge begins immediately and is not interrupted by Damage for {0} seconds when [Stun|Stunned] while using Supported Skills
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[EnergyShield|Energy Shield] Recharge begins immediately and is not interrupted by Damage for {0} seconds when [Stun|Stunned] while using Supported Skills","n":"[EnergyShield|Energy Shield] Recharge begins immediately and is not interrupted by Damage for {0} seconds when [Stun|Stunned] while using Supported Skills","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 78. [ESRechargeRate|Energy Shield Recharge Rate] granted@{0}%

- Match score: `70`
- `k`: [ESRechargeRate|Energy Shield Recharge Rate] granted@{0}%
- `n`: [ESRechargeRate|Energy Shield Recharge Rate] granted@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRechargeRate|Energy Shield Recharge Rate] granted@{0}%","n":"[ESRechargeRate|Energy Shield Recharge Rate] granted@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 79. [ESRecharge|Energy Shield Recharge] has no delay

- Match score: `70`
- `k`: [ESRecharge|Energy Shield Recharge] has no delay
- `n`: [ESRecharge|Energy Shield Recharge] has no delay
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRecharge|Energy Shield Recharge] has no delay","n":"[ESRecharge|Energy Shield Recharge] has no delay","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 80. [ESRecharge|Energy Shield Recharge] is not interrupted by Damage if Recharge began [Recently]

- Match score: `70`
- `k`: [ESRecharge|Energy Shield Recharge] is not interrupted by Damage if Recharge began [Recently]
- `n`: [ESRecharge|Energy Shield Recharge] is not interrupted by Damage if Recharge began [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRecharge|Energy Shield Recharge] is not interrupted by Damage if Recharge began [Recently]","n":"[ESRecharge|Energy Shield Recharge] is not interrupted by Damage if Recharge began [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 81. [ESRecharge|Energy Shield Recharge] starts after spending a total of
 2000 Mana, no more than once every 2 seconds

- Match score: `70`
- `k`: [ESRecharge|Energy Shield Recharge] starts after spending a total of
 2000 Mana, no more than once every 2 seconds
- `n`: [ESRecharge|Energy Shield Recharge] starts after spending a total of
 2000 Mana, no more than once every 2 seconds
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRecharge|Energy Shield Recharge] starts after spending a total of\n 2000 Mana, no more than once every 2 seconds","n":"[ESRecharge|Energy Shield Recharge] starts after spending a total of\n 2000 Mana, no more than once every 2 seconds","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 82. [ESRecharge|Energy Shield Recharge] starts on use

- Match score: `70`
- `k`: [ESRecharge|Energy Shield Recharge] starts on use
- `n`: [ESRecharge|Energy Shield Recharge] starts on use
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRecharge|Energy Shield Recharge] starts on use","n":"[ESRecharge|Energy Shield Recharge] starts on use","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 83. [ESRecharge|Energy Shield Recharge] starts when you are Stunned

- Match score: `70`
- `k`: [ESRecharge|Energy Shield Recharge] starts when you are Stunned
- `n`: [ESRecharge|Energy Shield Recharge] starts when you are Stunned
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRecharge|Energy Shield Recharge] starts when you are Stunned","n":"[ESRecharge|Energy Shield Recharge] starts when you are Stunned","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 84. [ESRecharge|Energy Shield Recharge] starts when you use a Mana [Flask]

- Match score: `70`
- `k`: [ESRecharge|Energy Shield Recharge] starts when you use a Mana [Flask]
- `n`: [ESRecharge|Energy Shield Recharge] starts when you use a Mana [Flask]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ESRecharge|Energy Shield Recharge] starts when you use a Mana [Flask]","n":"[ESRecharge|Energy Shield Recharge] starts when you use a Mana [Flask]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 85. [Fire] Area [Spell|Spells] summon a Spirit per {0} metres of radius
[Projectile|Projectiles] from [Fire] [Spell|Spells] summon a Spirit on hit

- Match score: `70`
- `k`: [Fire] Area [Spell|Spells] summon a Spirit per {0} metres of radius
[Projectile|Projectiles] from [Fire] [Spell|Spells] summon a Spirit on hit
- `n`: [Fire] Area [Spell|Spells] summon a Spirit per {0} metres of radius
[Projectile|Projectiles] from [Fire] [Spell|Spells] summon a Spirit on hit
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Fire] Area [Spell|Spells] summon a Spirit per {0} metres of radius\n[Projectile|Projectiles] from [Fire] [Spell|Spells] summon a Spirit on hit","n":"[Fire] Area [Spell|Spells] summon a Spirit per {0} metres of radius\n[Projectile|Projectiles] from [Fire] [Spell|Spells] summon a Spirit on hit","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 86. [Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]

- Match score: `70`
- `k`: [Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]
- `n`: [Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]","n":"[Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 87. [LifeLeech|Life Leech] is [StatConversion|Converted] to [EnergyShieldLeech|Energy Shield Leech]

- Match score: `70`
- `k`: [LifeLeech|Life Leech] is [StatConversion|Converted] to [EnergyShieldLeech|Energy Shield Leech]
- `n`: [LifeLeech|Life Leech] is [StatConversion|Converted] to [EnergyShieldLeech|Energy Shield Leech]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[LifeLeech|Life Leech] is [StatConversion|Converted] to [EnergyShieldLeech|Energy Shield Leech]","n":"[LifeLeech|Life Leech] is [StatConversion|Converted] to [EnergyShieldLeech|Energy Shield Leech]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 88. [Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}

- Match score: `70`
- `k`: [Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}
- `n`: [Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}","n":"[Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 89. [MapBoss|Map Bosses] have {0}% increased [MonsterEffectiveness|Effectiveness] per 100 [Power] of Monsters slain in the Area

- Match score: `70`
- `k`: [MapBoss|Map Bosses] have {0}% increased [MonsterEffectiveness|Effectiveness] per 100 [Power] of Monsters slain in the Area
- `n`: [MapBoss|Map Bosses] have {0}% increased [MonsterEffectiveness|Effectiveness] per 100 [Power] of Monsters slain in the Area
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[MapBoss|Map Bosses] have {0}% increased [MonsterEffectiveness|Effectiveness] per 100 [Power] of Monsters slain in the Area","n":"[MapBoss|Map Bosses] have {0}% increased [MonsterEffectiveness|Effectiveness] per 100 [Power] of Monsters slain in the Area","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 90. [Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have

- Match score: `70`
- `k`: [Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `n`: [Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","n":"[Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 91. [Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have

- Match score: `70`
- `k`: [Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `n`: [Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","n":"[Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 92. [Offering|Offerings] from Supported Skills grant you a [Charges|Power Charge] every {0} seconds

- Match score: `70`
- `k`: [Offering|Offerings] from Supported Skills grant you a [Charges|Power Charge] every {0} seconds
- `n`: [Offering|Offerings] from Supported Skills grant you a [Charges|Power Charge] every {0} seconds
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Offering|Offerings] from Supported Skills grant you a [Charges|Power Charge] every {0} seconds","n":"[Offering|Offerings] from Supported Skills grant you a [Charges|Power Charge] every {0} seconds","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 93. [Projectile|Projectiles] per [Charges|Power Charge] Consumed@{0}

- Match score: `70`
- `k`: [Projectile|Projectiles] per [Charges|Power Charge] Consumed@{0}
- `n`: [Projectile|Projectiles] per [Charges|Power Charge] Consumed@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] per [Charges|Power Charge] Consumed@{0}","n":"[Projectile|Projectiles] per [Charges|Power Charge] Consumed@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 94. [Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming an additional Power Charge

- Match score: `70`
- `k`: [Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming an additional Power Charge
- `n`: [Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming an additional Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming an additional Power Charge","n":"[Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming an additional Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 95. [Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming {0} additional Power Charges

- Match score: `70`
- `k`: [Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming {0} additional Power Charges
- `n`: [Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming {0} additional Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming {0} additional Power Charges","n":"[Quarterstaff|Quarterstaff] Skills that consume [Charges|Power Charges] count as consuming {0} additional Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 96. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charge]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charge]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 97. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charge]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 98. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charge]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 99. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charge]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charge]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charge]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 100. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charge]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charge]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charge]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 101. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charge]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 102. [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]

- Match score: `70`
- `k`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `n`: [Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]
[Rarity|Rare] monsters grant {1} [Charges|Power Charges]
[Rarity|Unique] monsters grant {2} [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","n":"[Rarity|Normal and Magic] monsters grant {0} [Charges|Power Charges]\n[Rarity|Rare] monsters grant {1} [Charges|Power Charges]\n[Rarity|Unique] monsters grant {2} [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 103. [Sacrifice|Sacrificing] [EnergyShield|Energy Shield] does not interrupt [ESRecharge|Recharge]

- Match score: `70`
- `k`: [Sacrifice|Sacrificing] [EnergyShield|Energy Shield] does not interrupt [ESRecharge|Recharge]
- `n`: [Sacrifice|Sacrificing] [EnergyShield|Energy Shield] does not interrupt [ESRecharge|Recharge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Sacrifice|Sacrificing] [EnergyShield|Energy Shield] does not interrupt [ESRecharge|Recharge]","n":"[Sacrifice|Sacrificing] [EnergyShield|Energy Shield] does not interrupt [ESRecharge|Recharge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 104. [Shock|Shocks] you when you reach maximum [Charges|Power Charges]

- Match score: `70`
- `k`: [Shock|Shocks] you when you reach maximum [Charges|Power Charges]
- `n`: [Shock|Shocks] you when you reach maximum [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Shock|Shocks] you when you reach maximum [Charges|Power Charges]","n":"[Shock|Shocks] you when you reach maximum [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 105. [Shrine|Shrines] in your Maps have a 25% chance to enthrall monsters throughout the area
Enthralled monsters gain Shrine's effect for a short time and count as [ShrineMonster|Shrine Worshippers]

- Match score: `70`
- `k`: [Shrine|Shrines] in your Maps have a 25% chance to enthrall monsters throughout the area
Enthralled monsters gain Shrine's effect for a short time and count as [ShrineMonster|Shrine Worshippers]
- `n`: [Shrine|Shrines] in your Maps have a 25% chance to enthrall monsters throughout the area
Enthralled monsters gain Shrine's effect for a short time and count as [ShrineMonster|Shrine Worshippers]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Shrine|Shrines] in your Maps have a 25% chance to enthrall monsters throughout the area\nEnthralled monsters gain Shrine's effect for a short time and count as [ShrineMonster|Shrine Worshippers]","n":"[Shrine|Shrines] in your Maps have a 25% chance to enthrall monsters throughout the area\nEnthralled monsters gain Shrine's effect for a short time and count as [ShrineMonster|Shrine Worshippers]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 106. [SmallPassive|Small Passive] Skills in Radius also grant {0}% increased maximum [EnergyShield|Energy Shield]

- Match score: `70`
- `k`: [SmallPassive|Small Passive] Skills in Radius also grant {0}% increased maximum [EnergyShield|Energy Shield]
- `n`: [SmallPassive|Small Passive] Skills in Radius also grant {0}% increased maximum [EnergyShield|Energy Shield]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[SmallPassive|Small Passive] Skills in Radius also grant {0}% increased maximum [EnergyShield|Energy Shield]","n":"[SmallPassive|Small Passive] Skills in Radius also grant {0}% increased maximum [EnergyShield|Energy Shield]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 107. [SmallPassive|Small Passive] Skills in Radius also grant {0}% reduced maximum [EnergyShield|Energy Shield]

- Match score: `70`
- `k`: [SmallPassive|Small Passive] Skills in Radius also grant {0}% reduced maximum [EnergyShield|Energy Shield]
- `n`: [SmallPassive|Small Passive] Skills in Radius also grant {0}% reduced maximum [EnergyShield|Energy Shield]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[SmallPassive|Small Passive] Skills in Radius also grant {0}% reduced maximum [EnergyShield|Energy Shield]","n":"[SmallPassive|Small Passive] Skills in Radius also grant {0}% reduced maximum [EnergyShield|Energy Shield]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 108. [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage

- Match score: `70`
- `k`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage
- `n`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage","n":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 109. [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage

- Match score: `70`
- `k`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage
- `n`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage","n":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 110. [StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum [Divinity]

- Match score: `70`
- `k`: [StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum [Divinity]
- `n`: [StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum [Divinity]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum [Divinity]","n":"[StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum [Divinity]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 111. [StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum Mana
Mana Costs are Doubled

- Match score: `70`
- `k`: [StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum Mana
Mana Costs are Doubled
- `n`: [StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum Mana
Mana Costs are Doubled
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum Mana\nMana Costs are Doubled","n":"[StatConversion|Convert] 100% of maximum [EnergyShield|Energy Shield] to maximum Mana\nMana Costs are Doubled","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 112. [StoneSummoningCircle|Summoning Circles] in [Biome|Non-City] Areas have {0}% chance to instead
summon a random [DeadlyMapBoss|Deadly Map Boss]

- Match score: `70`
- `k`: [StoneSummoningCircle|Summoning Circles] in [Biome|Non-City] Areas have {0}% chance to instead
summon a random [DeadlyMapBoss|Deadly Map Boss]
- `n`: [StoneSummoningCircle|Summoning Circles] in [Biome|Non-City] Areas have {0}% chance to instead
summon a random [DeadlyMapBoss|Deadly Map Boss]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[StoneSummoningCircle|Summoning Circles] in [Biome|Non-City] Areas have {0}% chance to instead\nsummon a random [DeadlyMapBoss|Deadly Map Boss]","n":"[StoneSummoningCircle|Summoning Circles] in [Biome|Non-City] Areas have {0}% chance to instead\nsummon a random [DeadlyMapBoss|Deadly Map Boss]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 113. [Totem|Totems] created by Supported Skills have {0}% increased area of effect per allied [Totem] in effect radius

- Match score: `70`
- `k`: [Totem|Totems] created by Supported Skills have {0}% increased area of effect per allied [Totem] in effect radius
- `n`: [Totem|Totems] created by Supported Skills have {0}% increased area of effect per allied [Totem] in effect radius
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Totem|Totems] created by Supported Skills have {0}% increased area of effect per allied [Totem] in effect radius","n":"[Totem|Totems] created by Supported Skills have {0}% increased area of effect per allied [Totem] in effect radius","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 114. [Totem|Totems] created by Supported Skills have {0}% reduced area of effect per allied [Totem] in effect radius

- Match score: `70`
- `k`: [Totem|Totems] created by Supported Skills have {0}% reduced area of effect per allied [Totem] in effect radius
- `n`: [Totem|Totems] created by Supported Skills have {0}% reduced area of effect per allied [Totem] in effect radius
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Totem|Totems] created by Supported Skills have {0}% reduced area of effect per allied [Totem] in effect radius","n":"[Totem|Totems] created by Supported Skills have {0}% reduced area of effect per allied [Totem] in effect radius","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 115. Add additional content to areas with [PowerfulMapBoss|Powerful Map Bosses]

- Match score: `70`
- `k`: Add additional content to areas with [PowerfulMapBoss|Powerful Map Bosses]
- `n`: Add additional content to areas with [PowerfulMapBoss|Powerful Map Bosses]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Add additional content to areas with [PowerfulMapBoss|Powerful Map Bosses]","n":"Add additional content to areas with [PowerfulMapBoss|Powerful Map Bosses]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 116. Additional [Charges|Power Charge] chance@{0}%

- Match score: `70`
- `k`: Additional [Charges|Power Charge] chance@{0}%
- `n`: Additional [Charges|Power Charge] chance@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Additional [Charges|Power Charge] chance@{0}%","n":"Additional [Charges|Power Charge] chance@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 117. Additional [Strike|Strikes] per [Charges|Power Charge]@{0}

- Match score: `70`
- `k`: Additional [Strike|Strikes] per [Charges|Power Charge]@{0}
- `n`: Additional [Strike|Strikes] per [Charges|Power Charge]@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Additional [Strike|Strikes] per [Charges|Power Charge]@{0}","n":"Additional [Strike|Strikes] per [Charges|Power Charge]@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 118. Additional Images created with [Charges|Power Charge]@{0}

- Match score: `70`
- `k`: Additional Images created with [Charges|Power Charge]@{0}
- `n`: Additional Images created with [Charges|Power Charge]@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Additional Images created with [Charges|Power Charge]@{0}","n":"Additional Images created with [Charges|Power Charge]@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 119. Adds {0} to {1} Cold Damage to Hits against you per Frenzy Charge

- Match score: `70`
- `k`: Adds {0} to {1} Cold Damage to Hits against you per Frenzy Charge
- `n`: Adds {0} to {1} Cold Damage to Hits against you per Frenzy Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} to {1} Cold Damage to Hits against you per Frenzy Charge","n":"Adds {0} to {1} Cold Damage to Hits against you per Frenzy Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 120. Adds {0} to {1} Lightning Damage to Spells per Power Charge

- Match score: `70`
- `k`: Adds {0} to {1} Lightning Damage to Spells per Power Charge
- `n`: Adds {0} to {1} Lightning Damage to Spells per Power Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} to {1} Lightning Damage to Spells per Power Charge","n":"Adds {0} to {1} Lightning Damage to Spells per Power Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

## Index match summary

| Index | Status | Included matches |
|---|---|---:|
| Passive key nodes | OK | 120 |
| Passive full compact | OK | 120 |
| Passive edges | OK | 0 |
| Gems and skills | OK | 120 |
| Item bases/classes | OK | 120 |
| Mods and affixes | OK | 120 |
| Rune mods | OK | 1 |
| Uniques | OK | 3 |
| Misc | OK | 120 |
