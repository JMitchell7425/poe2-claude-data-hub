# Build Idea Pack — Lightning Shock Build

- Generated UTC: `2026-06-27T11:46:01+00:00`
- Idea slug: `lightning-shock-build`
- Purpose: Engineer a lightning/shock build with high clear speed and strong damage amplification.
- Keywords: `lightning, shock, shocked, electrocute, storm, spark, arc, exposure, penetration, ailment, elemental, critical, crit, cast speed, projectile, area, aoe, mana, energy shield, sorceress, stormweaver`
- Max matched records per index: `120`
- Total included matches: `737`


## Claude usage rules

- Treat this as the active focused data pack for this build idea.
- This is not the full PoE2 database.
- If a needed passive, gem, item base, mod, rune, unique, or interaction is missing, ask the user to expand this idea's keywords in `build_ideas.json` and regenerate the pack.
- Do not invent mechanics or records not present in this pack, the build documents, screenshots, or user-provided tests.

## Passive key nodes

- Source: `build_knowledge/compact/passive_tree_key_nodes.json`
- Matches included: `120`

### 1. Arcane Surge on Critical Hit

- Match score: `105`
- `id`: 2244
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"2244","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]}
```

### 2. Arcane Surge on Critical Hit

- Match score: `105`
- `id`: 54067
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"54067","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"],"out":["27626","2244"]}
```

### 3. Archon Duration and Critical Damage

- Match score: `105`
- `id`: 23436
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"23436","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["29197"]}
```

### 4. Archon Duration and Critical Damage

- Match score: `105`
- `id`: 26300
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"26300","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["23436"]}
```

### 5. Archon Duration and Critical Damage

- Match score: `105`
- `id`: 29197
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"29197","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["11428"]}
```

### 6. Attack and Cast Speed on Critical

- Match score: `105`
- `id`: 20236
- `n`: Attack and Cast Speed on Critical
- `t`: small
- `sd`: ["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"]

```json
{"id":"20236","n":"Attack and Cast Speed on Critical","t":"small","sd":["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"],"out":["4346"]}
```

### 7. Mana Regeneration and Critical Chance

- Match score: `105`
- `id`: 28578
- `n`: Mana Regeneration and Critical Chance
- `t`: small
- `sd`: ["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"]

```json
{"id":"28578","n":"Mana Regeneration and Critical Chance","t":"small","sd":["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"]}
```

### 8. Mana Regeneration and Critical Chance

- Match score: `105`
- `id`: 904
- `n`: Mana Regeneration and Critical Chance
- `t`: small
- `sd`: ["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"]

```json
{"id":"904","n":"Mana Regeneration and Critical Chance","t":"small","sd":["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"],"out":["28578"]}
```

### 9. Projectile Critical Chance

- Match score: `105`
- `id`: 61347
- `n`: Projectile Critical Chance
- `t`: small
- `sd`: ["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"]

```json
{"id":"61347","n":"Projectile Critical Chance","t":"small","sd":["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"],"out":["64488"]}
```

### 10. Projectile Critical Chance

- Match score: `105`
- `id`: 64488
- `n`: Projectile Critical Chance
- `t`: small
- `sd`: ["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"]

```json
{"id":"64488","n":"Projectile Critical Chance","t":"small","sd":["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"],"out":["7201"]}
```

### 11. Spell Critical Chance and Critical Ailment Effect

- Match score: `105`
- `id`: 57178
- `n`: Spell Critical Chance and Critical Ailment Effect
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [BuffMagnitude|Magnitude] of [DamagingAilments|Damaging Ailments] you inflict with [Critical|Critical Hits]"]

```json
{"id":"57178","n":"Spell Critical Chance and Critical Ailment Effect","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [BuffMagnitude|Magnitude] of [DamagingAilments|Damaging Ailments] you inflict with [Critical|Critical Hits]"],"out":["21245","5284"]}
```

### 12. Archon of the Storm

- Match score: `90`
- `id`: 27434
- `n`: Archon of the Storm
- `t`: notable
- `sd`: ["Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana"]

```json
{"id":"27434","n":"Archon of the Storm","t":"notable","sd":["Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana"],"out":["15984"]}
```

### 13. Exposed to the Storm

- Match score: `85`
- `id`: 40990
- `n`: Exposed to the Storm
- `t`: notable
- `sd`: ["Damage [Penetration|Penetrates] 18% [Resistances|Lightning Resistance]","15% increased [Critical|Critical Hit Chance] against enemies with [Exposure]"]

```json
{"id":"40990","n":"Exposed to the Storm","t":"notable","sd":["Damage [Penetration|Penetrates] 18% [Resistances|Lightning Resistance]","15% increased [Critical|Critical Hit Chance] against enemies with [Exposure]"]}
```

### 14. Elemental Ailment Chance

- Match score: `80`
- `id`: 38068
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"]

```json
{"id":"38068","n":"Elemental Ailment Chance","t":"small","sd":["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"]}
```

### 15. Elemental Ailment Chance

- Match score: `80`
- `id`: 51968
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"]

```json
{"id":"51968","n":"Elemental Ailment Chance","t":"small","sd":["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"]}
```

### 16. Elemental Ailment Chance

- Match score: `80`
- `id`: 56409
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"]

```json
{"id":"56409","n":"Elemental Ailment Chance","t":"small","sd":["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"],"out":["25101","43139","65248"]}
```

### 17. Elemental Ailment Chance

- Match score: `80`
- `id`: 58362
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"]

```json
{"id":"58362","n":"Elemental Ailment Chance","t":"small","sd":["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"],"out":["51335"]}
```

### 18. Elemental Ailment Duration

- Match score: `80`
- `id`: 39752
- `n`: Elemental Ailment Duration
- `t`: small
- `sd`: ["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"]

```json
{"id":"39752","n":"Elemental Ailment Duration","t":"small","sd":["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"],"out":["5936","38068"]}
```

### 19. Elemental Ailment Duration

- Match score: `80`
- `id`: 65248
- `n`: Elemental Ailment Duration
- `t`: small
- `sd`: ["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"]

```json
{"id":"65248","n":"Elemental Ailment Duration","t":"small","sd":["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"]}
```

### 20. Lightning Storm

- Match score: `80`
- `id`: 60878
- `n`: Lightning Storm
- `t`: notable
- `sd`: ["[Gain] 6% of [Lightning] damage as Extra [Cold] damage","15% reduced [BuffEffect|effect] of [Shock|Shock] on you","15% increased [BuffMagnitude|Magnitude] of [Shock|Shock] you inflict"]

```json
{"id":"60878","n":"Lightning Storm","t":"notable","sd":["[Gain] 6% of [Lightning] damage as Extra [Cold] damage","15% reduced [BuffEffect|effect] of [Shock|Shock] on you","15% increased [BuffMagnitude|Magnitude] of [Shock|Shock] you inflict"],"out":["17044","14122","44405"]}
```

### 21. Morgana, the Storm Seer

- Match score: `75`
- `id`: 64770
- `n`: Morgana, the Storm Seer
- `t`: notable
- `sd`: ["+8% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","You cannot be [Electrocute|Electrocuted]","50% reduced [BuffEffect|effect] of [Shock|Shock] on you"]

```json
{"id":"64770","n":"Morgana, the Storm Seer","t":"notable","sd":["+8% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","You cannot be [Electrocute|Electrocuted]","50% reduced [BuffEffect|effect] of [Shock|Shock] on you"]}
```

### 22. Accuracy and Attack Critical Chance

- Match score: `70`
- `id`: 38703
- `n`: Accuracy and Attack Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"]

```json
{"id":"38703","n":"Accuracy and Attack Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"],"out":["8249"]}
```

### 23. Accuracy and Attack Critical Chance

- Match score: `70`
- `id`: 63525
- `n`: Accuracy and Attack Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"]

```json
{"id":"63525","n":"Accuracy and Attack Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"],"out":["53094"]}
```

### 24. Accuracy and Attack Critical Chance

- Match score: `70`
- `id`: 8249
- `n`: Accuracy and Attack Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"]

```json
{"id":"8249","n":"Accuracy and Attack Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"],"out":["63525","16816"]}
```

### 25. Accuracy and Critical Chance

- Match score: `70`
- `id`: 22208
- `n`: Accuracy and Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"]

```json
{"id":"22208","n":"Accuracy and Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"],"out":["15207"]}
```

### 26. Accuracy and Critical Chance

- Match score: `70`
- `id`: 59503
- `n`: Accuracy and Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"]

```json
{"id":"59503","n":"Accuracy and Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"],"out":["22208"]}
```

### 27. Ailment Chance and Elemental Damage

- Match score: `70`
- `id`: 28859
- `n`: Ailment Chance and Elemental Damage
- `t`: small
- `sd`: ["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"]

```json
{"id":"28859","n":"Ailment Chance and Elemental Damage","t":"small","sd":["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"],"out":["45382"]}
```

### 28. Ailment Chance and Elemental Damage

- Match score: `70`
- `id`: 45382
- `n`: Ailment Chance and Elemental Damage
- `t`: small
- `sd`: ["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"]

```json
{"id":"45382","n":"Ailment Chance and Elemental Damage","t":"small","sd":["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"],"out":["53265"]}
```

### 29. Ailment Threshold from Energy Shield

- Match score: `70`
- `id`: 59798
- `n`: Ailment Threshold from Energy Shield
- `t`: small
- `sd`: ["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"]

```json
{"id":"59798","n":"Ailment Threshold from Energy Shield","t":"small","sd":["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"],"out":["5335"]}
```

### 30. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 32964
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"32964","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["34617"]}
```

### 31. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 40377
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"40377","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["46318","7554","46628"]}
```

### 32. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 41384
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"41384","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51672"]}
```

### 33. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 46318
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"46318","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32964"]}
```

### 34. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 51672
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"51672","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["31955"]}
```

### 35. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 65509
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"65509","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["41384","51821"]}
```

### 36. Attack Critical Chance

- Match score: `70`
- `id`: 21070
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"21070","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["57388"]}
```

### 37. Attack Critical Chance

- Match score: `70`
- `id`: 23259
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"23259","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["22864"]}
```

### 38. Attack Critical Chance

- Match score: `70`
- `id`: 33946
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"33946","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["34074","57227"]}
```

### 39. Attack Critical Chance

- Match score: `70`
- `id`: 34074
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"34074","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["23259"]}
```

### 40. Attack Critical Chance

- Match score: `70`
- `id`: 35048
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"35048","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["43650"]}
```

### 41. Attack Critical Chance

- Match score: `70`
- `id`: 54983
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"54983","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["39369"]}
```

### 42. Attack Critical Chance

- Match score: `70`
- `id`: 57227
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"57227","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["23259"]}
```

### 43. Attack Critical Damage

- Match score: `70`
- `id`: 19802
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"19802","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["64399"]}
```

### 44. Attack Critical Damage

- Match score: `70`
- `id`: 26176
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"26176","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["43650"]}
```

### 45. Attack Critical Damage

- Match score: `70`
- `id`: 2936
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"2936","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["13407"]}
```

### 46. Attack Critical Damage

- Match score: `70`
- `id`: 53386
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"53386","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["57388"]}
```

### 47. Attack Critical Damage

- Match score: `70`
- `id`: 64399
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"64399","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["2511"]}
```

### 48. Ballista Critical Damage

- Match score: `70`
- `id`: 56897
- `n`: Ballista Critical Damage
- `t`: small
- `sd`: ["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"56897","n":"Ballista Critical Damage","t":"small","sd":["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 49. Ballista Critical Strike

- Match score: `70`
- `id`: 31112
- `n`: Ballista Critical Strike
- `t`: small
- `sd`: ["10% increased [Ballista] [Critical|Critical Hit Chance]"]

```json
{"id":"31112","n":"Ballista Critical Strike","t":"small","sd":["10% increased [Ballista] [Critical|Critical Hit Chance]"]}
```

### 50. Ballista Critical Strike and Damage

- Match score: `70`
- `id`: 63828
- `n`: Ballista Critical Strike and Damage
- `t`: small
- `sd`: ["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]

```json
{"id":"63828","n":"Ballista Critical Strike and Damage","t":"small","sd":["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]}
```

### 51. Bleed on Critical Chance

- Match score: `70`
- `id`: 62388
- `n`: Bleed on Critical Chance
- `t`: small
- `sd`: ["15% chance to inflict [Bleeding|Bleeding] on [Critical|Critical Hit]"]

```json
{"id":"62388","n":"Bleed on Critical Chance","t":"small","sd":["15% chance to inflict [Bleeding|Bleeding] on [Critical|Critical Hit]"],"out":["26282"]}
```

### 52. Bleeding Chance on Critical

- Match score: `70`
- `id`: 39570
- `n`: Bleeding Chance on Critical
- `t`: small
- `sd`: ["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"]

```json
{"id":"39570","n":"Bleeding Chance on Critical","t":"small","sd":["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"],"out":["49394"]}
```

### 53. Bleeding Chance on Critical

- Match score: `70`
- `id`: 56330
- `n`: Bleeding Chance on Critical
- `t`: small
- `sd`: ["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"]

```json
{"id":"56330","n":"Bleeding Chance on Critical","t":"small","sd":["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"],"out":["39570"]}
```

### 54. Blinded Enemies Critical

- Match score: `70`
- `id`: 24570
- `n`: Blinded Enemies Critical
- `t`: small
- `sd`: ["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"]

```json
{"id":"24570","n":"Blinded Enemies Critical","t":"small","sd":["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"],"out":["28441"]}
```

### 55. Blinded Enemies Critical

- Match score: `70`
- `id`: 47235
- `n`: Blinded Enemies Critical
- `t`: small
- `sd`: ["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"]

```json
{"id":"47235","n":"Blinded Enemies Critical","t":"small","sd":["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"],"out":["24570"]}
```

### 56. Bow Critical Damage

- Match score: `70`
- `id`: 25586
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"25586","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["38993"]}
```

### 57. Bow Critical Damage

- Match score: `70`
- `id`: 38993
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"38993","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["21112"]}
```

### 58. Critical Bleeding Effect

- Match score: `70`
- `id`: 23786
- `n`: Critical Bleeding Effect
- `t`: small
- `sd`: ["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"]

```json
{"id":"23786","n":"Critical Bleeding Effect","t":"small","sd":["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"],"out":["33391"]}
```

### 59. Critical Bleeding Effect

- Match score: `70`
- `id`: 33391
- `n`: Critical Bleeding Effect
- `t`: small
- `sd`: ["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"]

```json
{"id":"33391","n":"Critical Bleeding Effect","t":"small","sd":["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"],"out":["56330","49661"]}
```

### 60. Critical Bleeding Effect

- Match score: `70`
- `id`: 49394
- `n`: Critical Bleeding Effect
- `t`: small
- `sd`: ["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"]

```json
{"id":"49394","n":"Critical Bleeding Effect","t":"small","sd":["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"],"out":["23786"]}
```

### 61. Critical Chance

- Match score: `70`
- `id`: 11509
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"]

```json
{"id":"11509","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"],"out":["7465"]}
```

### 62. Critical Chance

- Match score: `70`
- `id`: 14958
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"14958","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["17548"]}
```

### 63. Critical Chance

- Match score: `70`
- `id`: 16861
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"16861","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["27303"]}
```

### 64. Critical Chance

- Match score: `70`
- `id`: 18737
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"18737","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["17725"]}
```

### 65. Critical Chance

- Match score: `70`
- `id`: 1915
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] against Humanoids"]

```json
{"id":"1915","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] against Humanoids"],"out":["60085"]}
```

### 66. Critical Chance

- Match score: `70`
- `id`: 21017
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"21017","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["26969","55789"]}
```

### 67. Critical Chance

- Match score: `70`
- `id`: 24135
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"24135","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["34419"]}
```

### 68. Critical Chance

- Match score: `70`
- `id`: 24420
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"24420","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["33829","9442"]}
```

### 69. Critical Chance

- Match score: `70`
- `id`: 26319
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"26319","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["30990"]}
```

### 70. Critical Chance

- Match score: `70`
- `id`: 26969
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"26969","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["16861"]}
```

### 71. Critical Chance

- Match score: `70`
- `id`: 30990
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"30990","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["58939"]}
```

### 72. Critical Chance

- Match score: `70`
- `id`: 31692
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"31692","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["46197"]}
```

### 73. Critical Chance

- Match score: `70`
- `id`: 32660
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"]

```json
{"id":"32660","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"]}
```

### 74. Critical Chance

- Match score: `70`
- `id`: 33829
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"33829","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["18737"]}
```

### 75. Critical Chance

- Match score: `70`
- `id`: 38541
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"38541","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61601"]}
```

### 76. Critical Chance

- Match score: `70`
- `id`: 39540
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"39540","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["55933","50558"]}
```

### 77. Critical Chance

- Match score: `70`
- `id`: 40760
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"40760","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["21779","9185","47177"]}
```

### 78. Critical Chance

- Match score: `70`
- `id`: 41085
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"41085","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["4367","46070"]}
```

### 79. Critical Chance

- Match score: `70`
- `id`: 4157
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"4157","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["49220"]}
```

### 80. Critical Chance

- Match score: `70`
- `id`: 4346
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"4346","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["4519","20677"]}
```

### 81. Critical Chance

- Match score: `70`
- `id`: 44357
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"44357","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["63713"]}
```

### 82. Critical Chance

- Match score: `70`
- `id`: 44420
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"44420","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["28021"]}
```

### 83. Critical Chance

- Match score: `70`
- `id`: 45702
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"45702","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61333","31692"]}
```

### 84. Critical Chance

- Match score: `70`
- `id`: 46171
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"46171","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61421"]}
```

### 85. Critical Chance

- Match score: `70`
- `id`: 46760
- `n`: Critical Chance
- `t`: small
- `sd`: ["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"]

```json
{"id":"46760","n":"Critical Chance","t":"small","sd":["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"],"out":["51534","8631"]}
```

### 86. Critical Chance

- Match score: `70`
- `id`: 49107
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"49107","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["54562"]}
```

### 87. Critical Chance

- Match score: `70`
- `id`: 51534
- `n`: Critical Chance
- `t`: small
- `sd`: ["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"]

```json
{"id":"51534","n":"Critical Chance","t":"small","sd":["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"],"out":["24483"]}
```

### 88. Critical Chance

- Match score: `70`
- `id`: 54562
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"54562","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["2745"]}
```

### 89. Critical Chance

- Match score: `70`
- `id`: 55088
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"55088","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61196"]}
```

### 90. Critical Chance

- Match score: `70`
- `id`: 55621
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"55621","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["38537"]}
```

### 91. Critical Chance

- Match score: `70`
- `id`: 57181
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"57181","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["52448"]}
```

### 92. Critical Chance

- Match score: `70`
- `id`: 59256
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"]

```json
{"id":"59256","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"],"out":["8531"]}
```

### 93. Critical Chance

- Match score: `70`
- `id`: 60107
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"60107","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["57204"]}
```

### 94. Critical Chance

- Match score: `70`
- `id`: 61333
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"61333","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["46197"]}
```

### 95. Critical Chance

- Match score: `70`
- `id`: 62424
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"62424","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"]}
```

### 96. Critical Chance

- Match score: `70`
- `id`: 7353
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"7353","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["9046"]}
```

### 97. Critical Chance

- Match score: `70`
- `id`: 7465
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"]

```json
{"id":"7465","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"],"out":["17664"]}
```

### 98. Critical Chance

- Match score: `70`
- `id`: 8631
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"8631","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["32660","59256","30979"]}
```

### 99. Critical Chance

- Match score: `70`
- `id`: 9046
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"9046","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["56776"]}
```

### 100. Critical Chance

- Match score: `70`
- `id`: 9185
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"9185","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["60107"]}
```

### 101. Critical Chance and Damage

- Match score: `70`
- `id`: 43650
- `n`: Critical Chance and Damage
- `t`: small
- `sd`: ["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"]

```json
{"id":"43650","n":"Critical Chance and Damage","t":"small","sd":["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"],"out":["21070","53386"]}
```

### 102. Critical Damage

- Match score: `70`
- `id`: 13419
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"13419","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["14958"]}
```

### 103. Critical Damage

- Match score: `70`
- `id`: 20024
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"20024","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["44223"]}
```

### 104. Critical Damage

- Match score: `70`
- `id`: 21779
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"21779","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["57204"]}
```

### 105. Critical Damage

- Match score: `70`
- `id`: 23040
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23040","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38493"]}
```

### 106. Critical Damage

- Match score: `70`
- `id`: 23915
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23915","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["41529"]}
```

### 107. Critical Damage

- Match score: `70`
- `id`: 28021
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28021","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["9782"]}
```

### 108. Critical Damage

- Match score: `70`
- `id`: 28223
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28223","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6100"]}
```

### 109. Critical Damage

- Match score: `70`
- `id`: 29959
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"29959","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6891","60362"]}
```

### 110. Critical Damage

- Match score: `70`
- `id`: 3458
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"3458","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["45609"]}
```

### 111. Critical Damage

- Match score: `70`
- `id`: 34621
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"34621","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38541"]}
```

### 112. Critical Damage

- Match score: `70`
- `id`: 36602
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"36602","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["18465"]}
```

### 113. Critical Damage

- Match score: `70`
- `id`: 38493
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"38493","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["55621"]}
```

### 114. Critical Damage

- Match score: `70`
- `id`: 39569
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"39569","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["35901","3458","7353"]}
```

### 115. Critical Damage

- Match score: `70`
- `id`: 41529
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41529","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["21380"]}
```

### 116. Critical Damage

- Match score: `70`
- `id`: 41665
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41665","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["50562"]}
```

### 117. Critical Damage

- Match score: `70`
- `id`: 44223
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"44223","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 118. Critical Damage

- Match score: `70`
- `id`: 45609
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"45609","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 119. Critical Damage

- Match score: `70`
- `id`: 535
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"535","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["34621"]}
```

### 120. Critical Damage

- Match score: `70`
- `id`: 55596
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"55596","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["8509"]}
```

## Passive full compact

- Source: `build_knowledge/compact/passive_tree_full_compact.json`
- Matches included: `120`

### 1. Arcane Surge on Critical Hit

- Match score: `105`
- `id`: 2244
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"2244","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]}
```

### 2. Arcane Surge on Critical Hit

- Match score: `105`
- `id`: 54067
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"54067","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"],"out":["27626","2244"]}
```

### 3. Archon Duration and Critical Damage

- Match score: `105`
- `id`: 23436
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"23436","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["29197"]}
```

### 4. Archon Duration and Critical Damage

- Match score: `105`
- `id`: 26300
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"26300","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["23436"]}
```

### 5. Archon Duration and Critical Damage

- Match score: `105`
- `id`: 29197
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"29197","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["11428"]}
```

### 6. Attack and Cast Speed on Critical

- Match score: `105`
- `id`: 20236
- `n`: Attack and Cast Speed on Critical
- `t`: small
- `sd`: ["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"]

```json
{"id":"20236","n":"Attack and Cast Speed on Critical","t":"small","sd":["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"],"out":["4346"]}
```

### 7. Mana Regeneration and Critical Chance

- Match score: `105`
- `id`: 28578
- `n`: Mana Regeneration and Critical Chance
- `t`: small
- `sd`: ["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"]

```json
{"id":"28578","n":"Mana Regeneration and Critical Chance","t":"small","sd":["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"]}
```

### 8. Mana Regeneration and Critical Chance

- Match score: `105`
- `id`: 904
- `n`: Mana Regeneration and Critical Chance
- `t`: small
- `sd`: ["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"]

```json
{"id":"904","n":"Mana Regeneration and Critical Chance","t":"small","sd":["8% increased Mana Regeneration Rate","8% increased [Critical|Critical Hit Chance]"],"out":["28578"]}
```

### 9. Projectile Critical Chance

- Match score: `105`
- `id`: 61347
- `n`: Projectile Critical Chance
- `t`: small
- `sd`: ["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"]

```json
{"id":"61347","n":"Projectile Critical Chance","t":"small","sd":["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"],"out":["64488"]}
```

### 10. Projectile Critical Chance

- Match score: `105`
- `id`: 64488
- `n`: Projectile Critical Chance
- `t`: small
- `sd`: ["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"]

```json
{"id":"64488","n":"Projectile Critical Chance","t":"small","sd":["[Projectile|Projectiles] have 12% increased [Critical] Hit Chance against Enemies further than 6m"],"out":["7201"]}
```

### 11. Spell Critical Chance and Critical Ailment Effect

- Match score: `105`
- `id`: 57178
- `n`: Spell Critical Chance and Critical Ailment Effect
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [BuffMagnitude|Magnitude] of [DamagingAilments|Damaging Ailments] you inflict with [Critical|Critical Hits]"]

```json
{"id":"57178","n":"Spell Critical Chance and Critical Ailment Effect","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [BuffMagnitude|Magnitude] of [DamagingAilments|Damaging Ailments] you inflict with [Critical|Critical Hits]"],"out":["21245","5284"]}
```

### 12. Archon of the Storm

- Match score: `90`
- `id`: 27434
- `n`: Archon of the Storm
- `t`: notable
- `sd`: ["Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana"]

```json
{"id":"27434","n":"Archon of the Storm","t":"notable","sd":["Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana"],"out":["15984"]}
```

### 13. Exposed to the Storm

- Match score: `85`
- `id`: 40990
- `n`: Exposed to the Storm
- `t`: notable
- `sd`: ["Damage [Penetration|Penetrates] 18% [Resistances|Lightning Resistance]","15% increased [Critical|Critical Hit Chance] against enemies with [Exposure]"]

```json
{"id":"40990","n":"Exposed to the Storm","t":"notable","sd":["Damage [Penetration|Penetrates] 18% [Resistances|Lightning Resistance]","15% increased [Critical|Critical Hit Chance] against enemies with [Exposure]"]}
```

### 14. Elemental Ailment Chance

- Match score: `80`
- `id`: 38068
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"]

```json
{"id":"38068","n":"Elemental Ailment Chance","t":"small","sd":["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"]}
```

### 15. Elemental Ailment Chance

- Match score: `80`
- `id`: 51968
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"]

```json
{"id":"51968","n":"Elemental Ailment Chance","t":"small","sd":["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"]}
```

### 16. Elemental Ailment Chance

- Match score: `80`
- `id`: 56409
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"]

```json
{"id":"56409","n":"Elemental Ailment Chance","t":"small","sd":["24% increased [Flammability] [BuffMagnitude|Magnitude]","12% increased [Freeze|Freeze] Buildup","12% increased chance to [Shock]"],"out":["25101","43139","65248"]}
```

### 17. Elemental Ailment Chance

- Match score: `80`
- `id`: 58362
- `n`: Elemental Ailment Chance
- `t`: small
- `sd`: ["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"]

```json
{"id":"58362","n":"Elemental Ailment Chance","t":"small","sd":["20% increased [Flammability] [BuffMagnitude|Magnitude]","10% increased [Freeze|Freeze] Buildup","10% increased chance to [Shock]"],"out":["51335"]}
```

### 18. Elemental Ailment Duration

- Match score: `80`
- `id`: 39752
- `n`: Elemental Ailment Duration
- `t`: small
- `sd`: ["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"]

```json
{"id":"39752","n":"Elemental Ailment Duration","t":"small","sd":["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"],"out":["5936","38068"]}
```

### 19. Elemental Ailment Duration

- Match score: `80`
- `id`: 65248
- `n`: Elemental Ailment Duration
- `t`: small
- `sd`: ["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"]

```json
{"id":"65248","n":"Elemental Ailment Duration","t":"small","sd":["10% increased Duration of [Ignite], [Shock] and [Chill] on Enemies"]}
```

### 20. Lightning Storm

- Match score: `80`
- `id`: 60878
- `n`: Lightning Storm
- `t`: notable
- `sd`: ["[Gain] 6% of [Lightning] damage as Extra [Cold] damage","15% reduced [BuffEffect|effect] of [Shock|Shock] on you","15% increased [BuffMagnitude|Magnitude] of [Shock|Shock] you inflict"]

```json
{"id":"60878","n":"Lightning Storm","t":"notable","sd":["[Gain] 6% of [Lightning] damage as Extra [Cold] damage","15% reduced [BuffEffect|effect] of [Shock|Shock] on you","15% increased [BuffMagnitude|Magnitude] of [Shock|Shock] you inflict"],"out":["17044","14122","44405"]}
```

### 21. Morgana, the Storm Seer

- Match score: `75`
- `id`: 64770
- `n`: Morgana, the Storm Seer
- `t`: notable
- `sd`: ["+8% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","You cannot be [Electrocute|Electrocuted]","50% reduced [BuffEffect|effect] of [Shock|Shock] on you"]

```json
{"id":"64770","n":"Morgana, the Storm Seer","t":"notable","sd":["+8% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","10% [FasterESRechargeStart|faster start of Energy Shield Recharge]","You cannot be [Electrocute|Electrocuted]","50% reduced [BuffEffect|effect] of [Shock|Shock] on you"]}
```

### 22. Accuracy and Attack Critical Chance

- Match score: `70`
- `id`: 38703
- `n`: Accuracy and Attack Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"]

```json
{"id":"38703","n":"Accuracy and Attack Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"],"out":["8249"]}
```

### 23. Accuracy and Attack Critical Chance

- Match score: `70`
- `id`: 63525
- `n`: Accuracy and Attack Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"]

```json
{"id":"63525","n":"Accuracy and Attack Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"],"out":["53094"]}
```

### 24. Accuracy and Attack Critical Chance

- Match score: `70`
- `id`: 8249
- `n`: Accuracy and Attack Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"]

```json
{"id":"8249","n":"Accuracy and Attack Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","6% increased [Accuracy] Rating"],"out":["63525","16816"]}
```

### 25. Accuracy and Critical Chance

- Match score: `70`
- `id`: 22208
- `n`: Accuracy and Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"]

```json
{"id":"22208","n":"Accuracy and Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"],"out":["15207"]}
```

### 26. Accuracy and Critical Chance

- Match score: `70`
- `id`: 59503
- `n`: Accuracy and Critical Chance
- `t`: small
- `sd`: ["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"]

```json
{"id":"59503","n":"Accuracy and Critical Chance","t":"small","sd":["8% increased [Critical|Critical Hit Chance] for [Attack|Attacks]","8% increased [Accuracy] Rating"],"out":["22208"]}
```

### 27. Ailment Chance and Elemental Damage

- Match score: `70`
- `id`: 28859
- `n`: Ailment Chance and Elemental Damage
- `t`: small
- `sd`: ["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"]

```json
{"id":"28859","n":"Ailment Chance and Elemental Damage","t":"small","sd":["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"],"out":["45382"]}
```

### 28. Ailment Chance and Elemental Damage

- Match score: `70`
- `id`: 45382
- `n`: Ailment Chance and Elemental Damage
- `t`: small
- `sd`: ["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"]

```json
{"id":"45382","n":"Ailment Chance and Elemental Damage","t":"small","sd":["10% increased [ElementalDamage|Elemental Damage]","6% increased chance to inflict [Ailments]"],"out":["53265"]}
```

### 29. Ailment Threshold from Energy Shield

- Match score: `70`
- `id`: 59798
- `n`: Ailment Threshold from Energy Shield
- `t`: small
- `sd`: ["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"]

```json
{"id":"59798","n":"Ailment Threshold from Energy Shield","t":"small","sd":["Gain additional [AilmentThreshold|Ailment Threshold] equal to 12% of maximum [EnergyShield|Energy Shield]"],"out":["5335"]}
```

### 30. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 32964
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"32964","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["34617"]}
```

### 31. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 40377
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"40377","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["46318","7554","46628"]}
```

### 32. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 41384
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"41384","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["51672"]}
```

### 33. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 46318
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"46318","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+6% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","3% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["32964"]}
```

### 34. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 51672
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"51672","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["31955"]}
```

### 35. Armour Applies to Elemental Damage and Energy Shield Delay

- Match score: `70`
- `id`: 65509
- `n`: Armour Applies to Elemental Damage and Energy Shield Delay
- `t`: small
- `sd`: ["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"]

```json
{"id":"65509","n":"Armour Applies to Elemental Damage and Energy Shield Delay","t":"small","sd":["+5% of [Armour|Armour] also applies to [ElementalDamage|Elemental Damage]","4% [FasterESRechargeStart|faster start of Energy Shield Recharge]"],"out":["41384","51821"]}
```

### 36. Attack Critical Chance

- Match score: `70`
- `id`: 21070
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"21070","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["57388"]}
```

### 37. Attack Critical Chance

- Match score: `70`
- `id`: 23259
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"23259","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["22864"]}
```

### 38. Attack Critical Chance

- Match score: `70`
- `id`: 33946
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"33946","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["34074","57227"]}
```

### 39. Attack Critical Chance

- Match score: `70`
- `id`: 34074
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"34074","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["23259"]}
```

### 40. Attack Critical Chance

- Match score: `70`
- `id`: 35048
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"35048","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["43650"]}
```

### 41. Attack Critical Chance

- Match score: `70`
- `id`: 54983
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"54983","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["39369"]}
```

### 42. Attack Critical Chance

- Match score: `70`
- `id`: 57227
- `n`: Attack Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"]

```json
{"id":"57227","n":"Attack Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] for [Attack|Attacks]"],"out":["23259"]}
```

### 43. Attack Critical Damage

- Match score: `70`
- `id`: 19802
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"19802","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["64399"]}
```

### 44. Attack Critical Damage

- Match score: `70`
- `id`: 26176
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"26176","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["43650"]}
```

### 45. Attack Critical Damage

- Match score: `70`
- `id`: 2936
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"2936","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["13407"]}
```

### 46. Attack Critical Damage

- Match score: `70`
- `id`: 53386
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"53386","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["57388"]}
```

### 47. Attack Critical Damage

- Match score: `70`
- `id`: 64399
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"64399","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["2511"]}
```

### 48. Ballista Critical Damage

- Match score: `70`
- `id`: 56897
- `n`: Ballista Critical Damage
- `t`: small
- `sd`: ["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"56897","n":"Ballista Critical Damage","t":"small","sd":["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 49. Ballista Critical Strike

- Match score: `70`
- `id`: 31112
- `n`: Ballista Critical Strike
- `t`: small
- `sd`: ["10% increased [Ballista] [Critical|Critical Hit Chance]"]

```json
{"id":"31112","n":"Ballista Critical Strike","t":"small","sd":["10% increased [Ballista] [Critical|Critical Hit Chance]"]}
```

### 50. Ballista Critical Strike and Damage

- Match score: `70`
- `id`: 63828
- `n`: Ballista Critical Strike and Damage
- `t`: small
- `sd`: ["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]

```json
{"id":"63828","n":"Ballista Critical Strike and Damage","t":"small","sd":["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]}
```

### 51. Bleed on Critical Chance

- Match score: `70`
- `id`: 62388
- `n`: Bleed on Critical Chance
- `t`: small
- `sd`: ["15% chance to inflict [Bleeding|Bleeding] on [Critical|Critical Hit]"]

```json
{"id":"62388","n":"Bleed on Critical Chance","t":"small","sd":["15% chance to inflict [Bleeding|Bleeding] on [Critical|Critical Hit]"],"out":["26282"]}
```

### 52. Bleeding Chance on Critical

- Match score: `70`
- `id`: 39570
- `n`: Bleeding Chance on Critical
- `t`: small
- `sd`: ["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"]

```json
{"id":"39570","n":"Bleeding Chance on Critical","t":"small","sd":["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"],"out":["49394"]}
```

### 53. Bleeding Chance on Critical

- Match score: `70`
- `id`: 56330
- `n`: Bleeding Chance on Critical
- `t`: small
- `sd`: ["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"]

```json
{"id":"56330","n":"Bleeding Chance on Critical","t":"small","sd":["10% chance to inflict Bleeding on [Critical|Critical Hit] with [Attack|Attacks]"],"out":["39570"]}
```

### 54. Blinded Enemies Critical

- Match score: `70`
- `id`: 24570
- `n`: Blinded Enemies Critical
- `t`: small
- `sd`: ["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"]

```json
{"id":"24570","n":"Blinded Enemies Critical","t":"small","sd":["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"],"out":["28441"]}
```

### 55. Blinded Enemies Critical

- Match score: `70`
- `id`: 47235
- `n`: Blinded Enemies Critical
- `t`: small
- `sd`: ["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"]

```json
{"id":"47235","n":"Blinded Enemies Critical","t":"small","sd":["Enemies Blinded by you have 15% reduced [Critical|Critical Hit] Chance"],"out":["24570"]}
```

### 56. Bow Critical Damage

- Match score: `70`
- `id`: 25586
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"25586","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["38993"]}
```

### 57. Bow Critical Damage

- Match score: `70`
- `id`: 38993
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"38993","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["21112"]}
```

### 58. Critical Bleeding Effect

- Match score: `70`
- `id`: 23786
- `n`: Critical Bleeding Effect
- `t`: small
- `sd`: ["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"]

```json
{"id":"23786","n":"Critical Bleeding Effect","t":"small","sd":["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"],"out":["33391"]}
```

### 59. Critical Bleeding Effect

- Match score: `70`
- `id`: 33391
- `n`: Critical Bleeding Effect
- `t`: small
- `sd`: ["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"]

```json
{"id":"33391","n":"Critical Bleeding Effect","t":"small","sd":["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"],"out":["56330","49661"]}
```

### 60. Critical Bleeding Effect

- Match score: `70`
- `id`: 49394
- `n`: Critical Bleeding Effect
- `t`: small
- `sd`: ["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"]

```json
{"id":"49394","n":"Critical Bleeding Effect","t":"small","sd":["15% increased [BuffMagnitude|Magnitude] of [Bleeding|Bleeding] you inflict with [Critical|Critical Hits]"],"out":["23786"]}
```

### 61. Critical Chance

- Match score: `70`
- `id`: 11509
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"]

```json
{"id":"11509","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"],"out":["7465"]}
```

### 62. Critical Chance

- Match score: `70`
- `id`: 14958
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"14958","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["17548"]}
```

### 63. Critical Chance

- Match score: `70`
- `id`: 16861
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"16861","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["27303"]}
```

### 64. Critical Chance

- Match score: `70`
- `id`: 18737
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"18737","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["17725"]}
```

### 65. Critical Chance

- Match score: `70`
- `id`: 1915
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] against Humanoids"]

```json
{"id":"1915","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] against Humanoids"],"out":["60085"]}
```

### 66. Critical Chance

- Match score: `70`
- `id`: 21017
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"21017","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["26969","55789"]}
```

### 67. Critical Chance

- Match score: `70`
- `id`: 24135
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"24135","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["34419"]}
```

### 68. Critical Chance

- Match score: `70`
- `id`: 24420
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"24420","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["33829","9442"]}
```

### 69. Critical Chance

- Match score: `70`
- `id`: 26319
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"26319","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["30990"]}
```

### 70. Critical Chance

- Match score: `70`
- `id`: 26969
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"26969","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["16861"]}
```

### 71. Critical Chance

- Match score: `70`
- `id`: 30990
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"30990","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["58939"]}
```

### 72. Critical Chance

- Match score: `70`
- `id`: 31692
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"31692","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["46197"]}
```

### 73. Critical Chance

- Match score: `70`
- `id`: 32660
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"]

```json
{"id":"32660","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"]}
```

### 74. Critical Chance

- Match score: `70`
- `id`: 33829
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"33829","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["18737"]}
```

### 75. Critical Chance

- Match score: `70`
- `id`: 38541
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"38541","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61601"]}
```

### 76. Critical Chance

- Match score: `70`
- `id`: 39540
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"39540","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["55933","50558"]}
```

### 77. Critical Chance

- Match score: `70`
- `id`: 40760
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"40760","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["21779","9185","47177"]}
```

### 78. Critical Chance

- Match score: `70`
- `id`: 41085
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"41085","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["4367","46070"]}
```

### 79. Critical Chance

- Match score: `70`
- `id`: 4157
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"4157","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["49220"]}
```

### 80. Critical Chance

- Match score: `70`
- `id`: 4346
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"4346","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["4519","20677"]}
```

### 81. Critical Chance

- Match score: `70`
- `id`: 44357
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"44357","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["63713"]}
```

### 82. Critical Chance

- Match score: `70`
- `id`: 44420
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"44420","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["28021"]}
```

### 83. Critical Chance

- Match score: `70`
- `id`: 45702
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"45702","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61333","31692"]}
```

### 84. Critical Chance

- Match score: `70`
- `id`: 46171
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"46171","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61421"]}
```

### 85. Critical Chance

- Match score: `70`
- `id`: 46760
- `n`: Critical Chance
- `t`: small
- `sd`: ["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"]

```json
{"id":"46760","n":"Critical Chance","t":"small","sd":["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"],"out":["51534","8631"]}
```

### 86. Critical Chance

- Match score: `70`
- `id`: 49107
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"49107","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["54562"]}
```

### 87. Critical Chance

- Match score: `70`
- `id`: 51534
- `n`: Critical Chance
- `t`: small
- `sd`: ["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"]

```json
{"id":"51534","n":"Critical Chance","t":"small","sd":["16% increased [Critical|Critical Hit Chance] if you haven't dealt a Critical Hit [Recently]"],"out":["24483"]}
```

### 88. Critical Chance

- Match score: `70`
- `id`: 54562
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"54562","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["2745"]}
```

### 89. Critical Chance

- Match score: `70`
- `id`: 55088
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"55088","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["61196"]}
```

### 90. Critical Chance

- Match score: `70`
- `id`: 55621
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"55621","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["38537"]}
```

### 91. Critical Chance

- Match score: `70`
- `id`: 57181
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"57181","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"],"out":["52448"]}
```

### 92. Critical Chance

- Match score: `70`
- `id`: 59256
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"]

```json
{"id":"59256","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance] if you have Killed [Recently]"],"out":["8531"]}
```

### 93. Critical Chance

- Match score: `70`
- `id`: 60107
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"60107","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["57204"]}
```

### 94. Critical Chance

- Match score: `70`
- `id`: 61333
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"61333","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["46197"]}
```

### 95. Critical Chance

- Match score: `70`
- `id`: 62424
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit Chance]"]

```json
{"id":"62424","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit Chance]"]}
```

### 96. Critical Chance

- Match score: `70`
- `id`: 7353
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"7353","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["9046"]}
```

### 97. Critical Chance

- Match score: `70`
- `id`: 7465
- `n`: Critical Chance
- `t`: small
- `sd`: ["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"]

```json
{"id":"7465","n":"Critical Chance","t":"small","sd":["12% increased [Critical|Critical Hit] Chance against Enemies that have entered your [Presence] [Recently]"],"out":["17664"]}
```

### 98. Critical Chance

- Match score: `70`
- `id`: 8631
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"8631","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["32660","59256","30979"]}
```

### 99. Critical Chance

- Match score: `70`
- `id`: 9046
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"9046","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["56776"]}
```

### 100. Critical Chance

- Match score: `70`
- `id`: 9185
- `n`: Critical Chance
- `t`: small
- `sd`: ["10% increased [Critical|Critical Hit Chance]"]

```json
{"id":"9185","n":"Critical Chance","t":"small","sd":["10% increased [Critical|Critical Hit Chance]"],"out":["60107"]}
```

### 101. Critical Chance and Damage

- Match score: `70`
- `id`: 43650
- `n`: Critical Chance and Damage
- `t`: small
- `sd`: ["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"]

```json
{"id":"43650","n":"Critical Chance and Damage","t":"small","sd":["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"],"out":["21070","53386"]}
```

### 102. Critical Damage

- Match score: `70`
- `id`: 13419
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"13419","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["14958"]}
```

### 103. Critical Damage

- Match score: `70`
- `id`: 20024
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"20024","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["44223"]}
```

### 104. Critical Damage

- Match score: `70`
- `id`: 21779
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"21779","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["57204"]}
```

### 105. Critical Damage

- Match score: `70`
- `id`: 23040
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23040","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38493"]}
```

### 106. Critical Damage

- Match score: `70`
- `id`: 23915
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23915","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["41529"]}
```

### 107. Critical Damage

- Match score: `70`
- `id`: 28021
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28021","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["9782"]}
```

### 108. Critical Damage

- Match score: `70`
- `id`: 28223
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28223","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6100"]}
```

### 109. Critical Damage

- Match score: `70`
- `id`: 29959
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"29959","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6891","60362"]}
```

### 110. Critical Damage

- Match score: `70`
- `id`: 3458
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"3458","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["45609"]}
```

### 111. Critical Damage

- Match score: `70`
- `id`: 34621
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"34621","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38541"]}
```

### 112. Critical Damage

- Match score: `70`
- `id`: 36602
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"36602","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["18465"]}
```

### 113. Critical Damage

- Match score: `70`
- `id`: 38493
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"38493","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["55621"]}
```

### 114. Critical Damage

- Match score: `70`
- `id`: 39569
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"39569","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["35901","3458","7353"]}
```

### 115. Critical Damage

- Match score: `70`
- `id`: 41529
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41529","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["21380"]}
```

### 116. Critical Damage

- Match score: `70`
- `id`: 41665
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41665","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["50562"]}
```

### 117. Critical Damage

- Match score: `70`
- `id`: 44223
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"44223","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 118. Critical Damage

- Match score: `70`
- `id`: 45609
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"45609","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 119. Critical Damage

- Match score: `70`
- `id`: 535
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"535","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["34621"]}
```

### 120. Critical Damage

- Match score: `70`
- `id`: 55596
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"55596","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["8509"]}
```

## Passive edges

- Source: `build_knowledge/compact/passive_tree_edges.json`
- Matches included: `0`

_No keyword matches in this index._

## Gems and skills

- Source: `build_knowledge/compact/gem_index.json`
- Matches included: `120`

### 1. [{'flags': 4, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE', 'value': 100, '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]

- Match score: `140`
- `k`: inflict_lightning_exposure_for_x_ms_on_shock
- `n`: [{'flags': 4, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE', 'value': 100, '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_lightning_exposure_for_x_ms_on_shock","n":"[{'flags': 4, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE', 'value': 100, '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":4,"keywordFlags":0,"name":"LightningExposureChance","type":"BASE","value":100,"1":{"actor":"enemy","type":"ActorCondition","var":"Shocked"}}]}
```

### 2. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Electrocuted'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Frozen'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Ignited'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}}}]

- Match score: `125`
- `k`: minion_damage_+%_final_per_different_elemental_ailment_on_target
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Electrocuted'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Frozen'}}}}, {'flags': 0, 'keywordFlags': 0, 'name...[trimmed]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minion_damage_+%_final_per_different_elemental_ailment_on_target","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Electrocuted'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Frozen'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Chilled'}}}}, {'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': ...[trimmed]
```

### 3. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]

- Match score: `115`
- `k`: critical_strike_chance_+%_vs_shocked_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_vs_shocked_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"Shocked"}}]}
```

### 4. [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]

- Match score: `105`
- `k`: inflict_exposure_for_x_ms_on_shock
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_exposure_for_x_ms_on_shock","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ExposureDuration","type":"BASE","1":{"actor":"enemy","type":"ActorCondition","var":"Shocked"}},{"flags":0,"keywordFlags":0,"name":"InflictExposure","type":"FLAG","value":true,"1":{"actor":"enemy","type":"ActorCondition","var":"Shocked"}}]}
```

### 5. CGEArchnemesisShockedGround

- Match score: `105`
- `k`: CGEArchnemesisShockedGround
- `n`: CGEArchnemesisShockedGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEArchnemesisShockedGround","n":"CGEArchnemesisShockedGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 6. CGEArchnemesisShockedGroundParent

- Match score: `105`
- `k`: CGEArchnemesisShockedGroundParent
- `n`: CGEArchnemesisShockedGroundParent
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEArchnemesisShockedGroundParent","n":"CGEArchnemesisShockedGroundParent","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 7. CGEManaEssenceManaBlastTrapShockedGround

- Match score: `105`
- `k`: CGEManaEssenceManaBlastTrapShockedGround
- `n`: CGEManaEssenceManaBlastTrapShockedGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEManaEssenceManaBlastTrapShockedGround","n":"CGEManaEssenceManaBlastTrapShockedGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 8. DeliriumLightningDemonShockedGroundUnique

- Match score: `105`
- `k`: DeliriumLightningDemonShockedGroundUnique
- `n`: DeliriumLightningDemonShockedGroundUnique
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"DeliriumLightningDemonShockedGroundUnique","n":"DeliriumLightningDemonShockedGroundUnique","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 9. VaalIncursionArchitectProjectileLightning

- Match score: `105`
- `k`: VaalIncursionArchitectProjectileLightning
- `n`: VaalIncursionArchitectProjectileLightning
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"VaalIncursionArchitectProjectileLightning","n":"VaalIncursionArchitectProjectileLightning","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 10. VaalIncursionArchitectProjectileLightning2

- Match score: `105`
- `k`: VaalIncursionArchitectProjectileLightning2
- `n`: VaalIncursionArchitectProjectileLightning2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"VaalIncursionArchitectProjectileLightning2","n":"VaalIncursionArchitectProjectileLightning2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 11. VaalIncursionArchitectProjectileLightningCombo

- Match score: `105`
- `k`: VaalIncursionArchitectProjectileLightningCombo
- `n`: VaalIncursionArchitectProjectileLightningCombo
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"VaalIncursionArchitectProjectileLightningCombo","n":"VaalIncursionArchitectProjectileLightningCombo","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 12. [{'flags': 0, 'keywordFlags': 0, 'name': 'CannotShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotChill', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotElectrocute', 'type': 'FLAG', 'value': True}]

- Match score: `90`
- `k`: cannot_inflict_elemental_ailments
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CannotShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotChill', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotElectrocute', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cannot_inflict_elemental_ailments","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CannotShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotChill', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'CannotElectrocute', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CannotShock","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"CannotChill","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"CannotFreeze","type":"FLAG","value":true},{"flags":0,"keywordFlags":0,"name":"CannotIgnite","type":"FLAG","value":true},{"flags":0,"keywordFlags":0...[trimmed]
```

### 13. Elemental Storm

- Match score: `90`
- `k`: Metadata/Items/Gems/SkillGemAscendancyElementalStorm
- `n`: Elemental Storm
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"area":true,"cold":true,"duration":true,"fire":true,"grants_active_skill":true,"lightning":true,"orb":true,"spell":true,"trigger":true}

```json
{"k":"Metadata/Items/Gems/SkillGemAscendancyElementalStorm","n":"Elemental Storm","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"area":true,"cold":true,"duration":true,"fire":true,"grants_active_skill":true,"lightning":true,"orb":true,"spell":true,"trigger":true}}
```

### 14. Metadata/Items/Gem/SkillGemAscendancyElementalStorm

- Match score: `90`
- `k`: Metadata/Items/Gem/SkillGemAscendancyElementalStorm
- `n`: Metadata/Items/Gem/SkillGemAscendancyElementalStorm
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["grants_active_skill","spell","area","trigger","lightning","cold","fire","duration","orb"]
- `base`: {"display_name":"Elemental Storm","id":"Metadata/Items/Gem/SkillGemAscendancyElementalStorm","release_state":"released"}

```json
{"k":"Metadata/Items/Gem/SkillGemAscendancyElementalStorm","n":"Metadata/Items/Gem/SkillGemAscendancyElementalStorm","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Elemental Storm","id":"Metadata/Items/Gem/SkillGemAscendancyElementalStorm","release_state":"released"},"tags":["grants_active_skill","spell","area","trigger","lightning","cold","fire","duration","orb"]}
```

### 15. [{'flags': 0, 'keywordFlags': 0, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]

- Match score: `80`
- `k`: critical_ailment_dot_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_ailment_dot_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"DotMultiplier","type":"BASE","1":{"type":"Condition","var":"CriticalStrike"}}]}
```

### 16. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `80`
- `k`: active_skill_all_elemental_exposure_magnitude
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_all_elemental_exposure_magnitude","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"ColdExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"LightningExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 17. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `80`
- `k`: skill_base_oil_exposure_-_to_total_elemental_resistance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_base_oil_exposure_-_to_total_elemental_resistance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"ColdExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"LightningExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 18. Cast on Elemental Ailment

- Match score: `80`
- `k`: Metadata/Items/Gems/SkillGemCastOnElementalAilment
- `n`: Cast on Elemental Ailment
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"buff":true,"cold":true,"fire":true,"grants_active_skill":true,"intelligence":true,"lightning":true,"meta":true,"persistent":true,"trigger":true}

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnElementalAilment","n":"Cast on Elemental Ailment","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"buff":true,"cold":true,"fire":true,"grants_active_skill":true,"intelligence":true,"lightning":true,"meta":true,"persistent":true,"trigger":true}}
```

### 19. Metadata/Items/Gems/SkillGemCastOnElementalAilment

- Match score: `80`
- `k`: Metadata/Items/Gems/SkillGemCastOnElementalAilment
- `n`: Metadata/Items/Gems/SkillGemCastOnElementalAilment
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["intelligence","grants_active_skill","buff","persistent","trigger","lightning","cold","fire","meta"]
- `base`: {"display_name":"Cast on Elemental Ailment","id":"Metadata/Items/Gems/SkillGemCastOnElementalAilment","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnElementalAilment","n":"Metadata/Items/Gems/SkillGemCastOnElementalAilment","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Cast on Elemental Ailment","id":"Metadata/Items/Gems/SkillGemCastOnElementalAilment","release_state":"released"},"tags":["intelligence","grants_active_skill","buff","persistent","trigger","lightning","cold","fire","meta"]}
```

### 20. [{'flags': 0, 'keywordFlags': 0, 'name': 'ElementalPenetration', 'type': 'BASE'}]

- Match score: `70`
- `k`: base_penetrate_elemental_resistances_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ElementalPenetration', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_penetrate_elemental_resistances_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ElementalPenetration', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ElementalPenetration","type":"BASE"}]}
```

### 21. [{'flags': 0, 'keywordFlags': 0, 'name': 'ElementalPenetration', 'type': 'BASE'}]

- Match score: `70`
- `k`: reduce_enemy_elemental_resistance_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ElementalPenetration', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"reduce_enemy_elemental_resistance_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ElementalPenetration', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ElementalPenetration","type":"BASE"}]}
```

### 22. [{'flags': 0, 'keywordFlags': 0, 'name': 'EnemyElementalAilmentDuration', 'type': 'INC'}]

- Match score: `70`
- `k`: base_elemental_status_ailment_duration_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'EnemyElementalAilmentDuration', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_elemental_status_ailment_duration_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'EnemyElementalAilmentDuration', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"EnemyElementalAilmentDuration","type":"INC"}]}
```

### 23. [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]

- Match score: `70`
- `k`: inflict_exposure_for_x_ms_on_cold_crit
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_exposure_for_x_ms_on_cold_crit","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ExposureDuration","type":"BASE","1":{"type":"Condition","var":"CritInPast8Sec"},"2":{"type":"Condition","var":"ColdHasDamage"}},{"flags":0,"keywordFlags":0,"name":"InflictExposure","type":"FLAG","value":true,"1":{"type":"Condition","var":"CritInPast8Sec"},"2":{"type":"Condition","var":"ColdHasDamage"}}]}
```

### 24. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]

- Match score: `70`
- `k`: all_exposure_on_hit_magnitude
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"all_exposure_on_hit_magnitude","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposure', 'type': 'BASE', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"ColdExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}},{"flags":0,"keywordFlags":0,"name":"LightningExposure","type":"BASE","1":{"effectType":"Debuff","type":"GlobalEffect"}}]}
```

### 25. [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureEffect', 'type': 'INC'}]

- Match score: `70`
- `k`: exposure_effect_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureEffect', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"exposure_effect_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureEffect', 'type': 'INC'}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureEffect', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FireExposureEffect","type":"INC"},{"flags":0,"keywordFlags":0,"name":"ColdExposureEffect","type":"INC"},{"flags":0,"keywordFlags":0,"name":"LightningExposureEffect","type":"INC"}]}
```

### 26. [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanElectrocute', 'type': 'FLAG', 'value': True}]

- Match score: `70`
- `k`: base_lightning_damage_can_electrocute
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanElectrocute', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_lightning_damage_can_electrocute","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanElectrocute', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"LightningCanElectrocute","type":"FLAG","value":true}]}
```

### 27. [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningCannotShock', 'type': 'FLAG', 'value': True}]

- Match score: `70`
- `k`: lightning_damage_cannot_shock
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningCannotShock', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"lightning_damage_cannot_shock","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'LightningCannotShock', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"LightningCannotShock","type":"FLAG","value":true}]}
```

### 28. [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureChance', 'type': 'BASE'}]

- Match score: `70`
- `k`: inflict_exposure_on_hit_%_chance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureChance', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_exposure_on_hit_%_chance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdExposureChance', 'type': 'BASE'}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireExposureChance', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"LightningExposureChance","type":"BASE"},{"flags":0,"keywordFlags":0,"name":"ColdExposureChance","type":"BASE"},{"flags":0,"keywordFlags":0,"name":"FireExposureChance","type":"BASE"}]}
```

### 29. [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}]

- Match score: `70`
- `k`: base_inflict_lightning_exposure_on_hit_%_chance
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_inflict_lightning_exposure_on_hit_%_chance","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'LightningExposureChance', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"LightningExposureChance","type":"BASE"}]}
```

### 30. [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningPenetration', 'type': 'BASE'}]

- Match score: `70`
- `k`: base_reduce_enemy_lightning_resistance_%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'LightningPenetration', 'type': 'BASE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_reduce_enemy_lightning_resistance_%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'LightningPenetration', 'type': 'BASE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"LightningPenetration","type":"BASE"}]}
```

### 31. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanShock', 'type': 'FLAG', 'value': True}]

- Match score: `70`
- `k`: all_damage_can_ignite_freeze_shock
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': ...[trimmed]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"all_damage_can_ignite_freeze_shock","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ColdCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanIgnite', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'LightningCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'FireCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'ChaosCanFreeze', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalCanShock', 'type': 'FLAG', 'value': True}, {'flags': 0, 'keywordFlags':...[trimmed]
```

### 32. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageTaken', 'type': 'INC', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}, '2': {'type': 'Condition', 'var': 'Shocked'}}]

- Match score: `70`
- `k`: enemies_you_shock_take_%_increased_physical_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageTaken', 'type': 'INC', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}, '2': {'type': 'Condition', 'var': 'Shocked'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"enemies_you_shock_take_%_increased_physical_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamageTaken', 'type': 'INC', '1': {'effectType': 'Debuff', 'type': 'GlobalEffect'}, '2': {'type': 'Condition', 'var': 'Shocked'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalDamageTaken","type":"INC","1":{"effectType":"Debuff","type":"GlobalEffect"},"2":{"type":"Condition","var":"Shocked"}}]}
```

### 33. [{'flags': 0, 'keywordFlags': 2097152, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]

- Match score: `70`
- `k`: critical_poison_dot_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 2097152, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_poison_dot_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 2097152, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":2097152,"name":"DotMultiplier","type":"BASE","1":{"type":"Condition","var":"CriticalStrike"}}]}
```

### 34. [{'flags': 1, 'keywordFlags': 0, 'name': 'LightningMin', 'type': 'BASE', '1': {'percent': 1, 'stat': 'Mana', 'type': 'PercentStat'}}, {'flags': 1, 'keywordFlags': 0, 'name': 'LightningMax', 'type': 'BASE', '1': {'percent': 1, 'stat': 'Mana', 'type': 'PercentStat'}}]

- Match score: `70`
- `k`: attack_skills_have_added_lightning_damage_equal_to_%_of_maximum_mana
- `n`: [{'flags': 1, 'keywordFlags': 0, 'name': 'LightningMin', 'type': 'BASE', '1': {'percent': 1, 'stat': 'Mana', 'type': 'PercentStat'}}, {'flags': 1, 'keywordFlags': 0, 'name': 'LightningMax', 'type': 'BASE', '1': {'percent': 1, 'stat': 'Mana', 'type': 'PercentStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"attack_skills_have_added_lightning_damage_equal_to_%_of_maximum_mana","n":"[{'flags': 1, 'keywordFlags': 0, 'name': 'LightningMin', 'type': 'BASE', '1': {'percent': 1, 'stat': 'Mana', 'type': 'PercentStat'}}, {'flags': 1, 'keywordFlags': 0, 'name': 'LightningMax', 'type': 'BASE', '1': {'percent': 1, 'stat': 'Mana', 'type': 'PercentStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":1,"keywordFlags":0,"name":"LightningMin","type":"BASE","1":{"percent":1,"stat":"Mana","type":"PercentStat"}},{"flags":1,"keywordFlags":0,"name":"LightningMax","type":"BASE","1":{"percent":1,"stat":"Mana","type":"PercentStat"}}]}
```

### 35. [{'flags': 2, 'keywordFlags': 0, 'name': 'ImpaleChance', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]

- Match score: `70`
- `k`: spell_impale_on_crit_%_chance
- `n`: [{'flags': 2, 'keywordFlags': 0, 'name': 'ImpaleChance', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"spell_impale_on_crit_%_chance","n":"[{'flags': 2, 'keywordFlags': 0, 'name': 'ImpaleChance', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":2,"keywordFlags":0,"name":"ImpaleChance","type":"BASE","1":{"type":"Condition","var":"CriticalStrike"}}]}
```

### 36. additional_base_critical_strike_chance

- Match score: `70`
- `k`: additional_base_critical_strike_chance
- `n`: additional_base_critical_strike_chance
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additional_base_critical_strike_chance","n":"additional_base_critical_strike_chance","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 37. additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad

- Match score: `70`
- `k`: additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad
- `n`: additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad","n":"additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 38. additional_critical_strike_chance_permyriad_while_affected_by_elusive

- Match score: `70`
- `k`: additional_critical_strike_chance_permyriad_while_affected_by_elusive
- `n`: additional_critical_strike_chance_permyriad_while_affected_by_elusive
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additional_critical_strike_chance_permyriad_while_affected_by_elusive","n":"additional_critical_strike_chance_permyriad_while_affected_by_elusive","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 39. ArchitectComboStompLightning

- Match score: `70`
- `k`: ArchitectComboStompLightning
- `n`: ArchitectComboStompLightning
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"ArchitectComboStompLightning","n":"ArchitectComboStompLightning","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 40. ArchnemesisElementalWeakness

- Match score: `70`
- `k`: ArchnemesisElementalWeakness
- `n`: ArchnemesisElementalWeakness
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"ArchnemesisElementalWeakness","n":"ArchnemesisElementalWeakness","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 41. AtziriElementalSpearCombo

- Match score: `70`
- `k`: AtziriElementalSpearCombo
- `n`: AtziriElementalSpearCombo
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"AtziriElementalSpearCombo","n":"AtziriElementalSpearCombo","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 42. BallLightningRogueExileSorceress2

- Match score: `70`
- `k`: BallLightningRogueExileSorceress2
- `n`: BallLightningRogueExileSorceress2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"BallLightningRogueExileSorceress2","n":"BallLightningRogueExileSorceress2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 43. base_mana_leech_from_elemental_damage_permyriad

- Match score: `70`
- `k`: base_mana_leech_from_elemental_damage_permyriad
- `n`: base_mana_leech_from_elemental_damage_permyriad
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_mana_leech_from_elemental_damage_permyriad","n":"base_mana_leech_from_elemental_damage_permyriad","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 44. base_self_critical_strike_multiplier_-%

- Match score: `70`
- `k`: base_self_critical_strike_multiplier_-%
- `n`: base_self_critical_strike_multiplier_-%
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_self_critical_strike_multiplier_-%","n":"base_self_critical_strike_multiplier_-%","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 45. Blazing Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemBlazingCriticalSupport
- `n`: Blazing Critical
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"attack":true,"duration":true,"fire":true,"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemBlazingCriticalSupport","n":"Blazing Critical","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"attack":true,"duration":true,"fire":true,"support":true}}
```

### 46. BoneCultistZealotAbyssLightningstorm

- Match score: `70`
- `k`: BoneCultistZealotAbyssLightningstorm
- `n`: BoneCultistZealotAbyssLightningstorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"BoneCultistZealotAbyssLightningstorm","n":"BoneCultistZealotAbyssLightningstorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 47. BoneCultistZealotLightningstorm

- Match score: `70`
- `k`: BoneCultistZealotLightningstorm
- `n`: BoneCultistZealotLightningstorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"BoneCultistZealotLightningstorm","n":"BoneCultistZealotLightningstorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 48. Cast on Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemCastOnCriticalStrike
- `n`: Cast on Critical
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"buff":true,"grants_active_skill":true,"intelligence":true,"meta":true,"persistent":true,"trigger":true}

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnCriticalStrike","n":"Cast on Critical","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"buff":true,"grants_active_skill":true,"intelligence":true,"meta":true,"persistent":true,"trigger":true}}
```

### 49. CGEArchnemesisLightningWalkerGround

- Match score: `70`
- `k`: CGEArchnemesisLightningWalkerGround
- `n`: CGEArchnemesisLightningWalkerGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEArchnemesisLightningWalkerGround","n":"CGEArchnemesisLightningWalkerGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 50. CGEArchnemesisPlayerLightningWalkerGround

- Match score: `70`
- `k`: CGEArchnemesisPlayerLightningWalkerGround
- `n`: CGEArchnemesisPlayerLightningWalkerGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEArchnemesisPlayerLightningWalkerGround","n":"CGEArchnemesisPlayerLightningWalkerGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 51. CGEBoneCultistShockedGround

- Match score: `70`
- `k`: CGEBoneCultistShockedGround
- `n`: CGEBoneCultistShockedGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEBoneCultistShockedGround","n":"CGEBoneCultistShockedGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 52. CGECasterEssenceShockedGround

- Match score: `70`
- `k`: CGECasterEssenceShockedGround
- `n`: CGECasterEssenceShockedGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGECasterEssenceShockedGround","n":"CGECasterEssenceShockedGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 53. CGECentipedeReactorGuardianShockedGround

- Match score: `70`
- `k`: CGECentipedeReactorGuardianShockedGround
- `n`: CGECentipedeReactorGuardianShockedGround
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGECentipedeReactorGuardianShockedGround","n":"CGECentipedeReactorGuardianShockedGround","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 54. ChaosArchitectProjectileNova

- Match score: `70`
- `k`: ChaosArchitectProjectileNova
- `n`: ChaosArchitectProjectileNova
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"ChaosArchitectProjectileNova","n":"ChaosArchitectProjectileNova","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 55. DeceleratingProjectilesArchitectBloodSpray

- Match score: `70`
- `k`: DeceleratingProjectilesArchitectBloodSpray
- `n`: DeceleratingProjectilesArchitectBloodSpray
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"DeceleratingProjectilesArchitectBloodSpray","n":"DeceleratingProjectilesArchitectBloodSpray","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 56. DelayedLightningSpark

- Match score: `70`
- `k`: DelayedLightningSpark
- `n`: DelayedLightningSpark
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"DelayedLightningSpark","n":"DelayedLightningSpark","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 57. DelayedLightningSparkTriggerCascade

- Match score: `70`
- `k`: DelayedLightningSparkTriggerCascade
- `n`: DelayedLightningSparkTriggerCascade
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"DelayedLightningSparkTriggerCascade","n":"DelayedLightningSparkTriggerCascade","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 58. DelveLightningOrbProjectile

- Match score: `70`
- `k`: DelveLightningOrbProjectile
- `n`: DelveLightningOrbProjectile
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"DelveLightningOrbProjectile","n":"DelveLightningOrbProjectile","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 59. EASArchnemesisElementalExplosionWithGroundEffect

- Match score: `70`
- `k`: EASArchnemesisElementalExplosionWithGroundEffect
- `n`: EASArchnemesisElementalExplosionWithGroundEffect
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"EASArchnemesisElementalExplosionWithGroundEffect","n":"EASArchnemesisElementalExplosionWithGroundEffect","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 60. EASTheTrialMasterElementalProjectiles

- Match score: `70`
- `k`: EASTheTrialMasterElementalProjectiles
- `n`: EASTheTrialMasterElementalProjectiles
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"EASTheTrialMasterElementalProjectiles","n":"EASTheTrialMasterElementalProjectiles","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 61. EDSTwilightOverseerLightningStorm

- Match score: `70`
- `k`: EDSTwilightOverseerLightningStorm
- `n`: EDSTwilightOverseerLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"EDSTwilightOverseerLightningStorm","n":"EDSTwilightOverseerLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 62. ElementalStormPlayer

- Match score: `70`
- `k`: ElementalStormPlayer
- `n`: ElementalStormPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"ElementalStormPlayer","n":"ElementalStormPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 63. FirestormRogueExileSorceress1

- Match score: `70`
- `k`: FirestormRogueExileSorceress1
- `n`: FirestormRogueExileSorceress1
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"FirestormRogueExileSorceress1","n":"FirestormRogueExileSorceress1","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 64. GPSBreachHandMageLightningVolatileProjectile

- Match score: `70`
- `k`: GPSBreachHandMageLightningVolatileProjectile
- `n`: GPSBreachHandMageLightningVolatileProjectile
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GPSBreachHandMageLightningVolatileProjectile","n":"GPSBreachHandMageLightningVolatileProjectile","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 65. GSArchitectBossRuneComboLightningSnake

- Match score: `70`
- `k`: GSArchitectBossRuneComboLightningSnake
- `n`: GSArchitectBossRuneComboLightningSnake
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSArchitectBossRuneComboLightningSnake","n":"GSArchitectBossRuneComboLightningSnake","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 66. GSBoneCultistZealotRunemarkedLightningStorm

- Match score: `70`
- `k`: GSBoneCultistZealotRunemarkedLightningStorm
- `n`: GSBoneCultistZealotRunemarkedLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSBoneCultistZealotRunemarkedLightningStorm","n":"GSBoneCultistZealotRunemarkedLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 67. GSChimeraBossLightningOrbArc

- Match score: `70`
- `k`: GSChimeraBossLightningOrbArc
- `n`: GSChimeraBossLightningOrbArc
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSChimeraBossLightningOrbArc","n":"GSChimeraBossLightningOrbArc","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 68. GSDeliriumDemonProjectileLightningImpact

- Match score: `70`
- `k`: GSDeliriumDemonProjectileLightningImpact
- `n`: GSDeliriumDemonProjectileLightningImpact
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSDeliriumDemonProjectileLightningImpact","n":"GSDeliriumDemonProjectileLightningImpact","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 69. GSDoryaniLightningStormBolt

- Match score: `70`
- `k`: GSDoryaniLightningStormBolt
- `n`: GSDoryaniLightningStormBolt
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSDoryaniLightningStormBolt","n":"GSDoryaniLightningStormBolt","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 70. GSDoryaniLightningStormBoltConstant

- Match score: `70`
- `k`: GSDoryaniLightningStormBoltConstant
- `n`: GSDoryaniLightningStormBoltConstant
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSDoryaniLightningStormBoltConstant","n":"GSDoryaniLightningStormBoltConstant","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 71. GSGemlingArcherBossLightningArrowWallImpact

- Match score: `70`
- `k`: GSGemlingArcherBossLightningArrowWallImpact
- `n`: GSGemlingArcherBossLightningArrowWallImpact
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSGemlingArcherBossLightningArrowWallImpact","n":"GSGemlingArcherBossLightningArrowWallImpact","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 72. GSKaruiCaptainBoss2ValakoLightningStormBolt

- Match score: `70`
- `k`: GSKaruiCaptainBoss2ValakoLightningStormBolt
- `n`: GSKaruiCaptainBoss2ValakoLightningStormBolt
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSKaruiCaptainBoss2ValakoLightningStormBolt","n":"GSKaruiCaptainBoss2ValakoLightningStormBolt","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 73. GSMonsterModLightningMirageAOE

- Match score: `70`
- `k`: GSMonsterModLightningMirageAOE
- `n`: GSMonsterModLightningMirageAOE
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSMonsterModLightningMirageAOE","n":"GSMonsterModLightningMirageAOE","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 74. GSMonsterModLightningMirageAOE2

- Match score: `70`
- `k`: GSMonsterModLightningMirageAOE2
- `n`: GSMonsterModLightningMirageAOE2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSMonsterModLightningMirageAOE2","n":"GSMonsterModLightningMirageAOE2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 75. GSMonsterModLightningStorm

- Match score: `70`
- `k`: GSMonsterModLightningStorm
- `n`: GSMonsterModLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSMonsterModLightningStorm","n":"GSMonsterModLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 76. GSMonsterModShockedGroundNova

- Match score: `70`
- `k`: GSMonsterModShockedGroundNova
- `n`: GSMonsterModShockedGroundNova
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSMonsterModShockedGroundNova","n":"GSMonsterModShockedGroundNova","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 77. GSMonsterModShockedGroundNovaOnDeath

- Match score: `70`
- `k`: GSMonsterModShockedGroundNovaOnDeath
- `n`: GSMonsterModShockedGroundNovaOnDeath
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSMonsterModShockedGroundNovaOnDeath","n":"GSMonsterModShockedGroundNovaOnDeath","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 78. GSPlayerMonsterModLightningStorm

- Match score: `70`
- `k`: GSPlayerMonsterModLightningStorm
- `n`: GSPlayerMonsterModLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSPlayerMonsterModLightningStorm","n":"GSPlayerMonsterModLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 79. GSPlayerMonsterModShockedGroundNova

- Match score: `70`
- `k`: GSPlayerMonsterModShockedGroundNova
- `n`: GSPlayerMonsterModShockedGroundNova
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSPlayerMonsterModShockedGroundNova","n":"GSPlayerMonsterModShockedGroundNova","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 80. GSStormConduitShockwave

- Match score: `70`
- `k`: GSStormConduitShockwave
- `n`: GSStormConduitShockwave
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSStormConduitShockwave","n":"GSStormConduitShockwave","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 81. GSStormGuardCallLightning

- Match score: `70`
- `k`: GSStormGuardCallLightning
- `n`: GSStormGuardCallLightning
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSStormGuardCallLightning","n":"GSStormGuardCallLightning","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 82. GSUltimatumStormRuneLightningStrike

- Match score: `70`
- `k`: GSUltimatumStormRuneLightningStrike
- `n`: GSUltimatumStormRuneLightningStrike
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSUltimatumStormRuneLightningStrike","n":"GSUltimatumStormRuneLightningStrike","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 83. GSVaalArchivistLightningBlast

- Match score: `70`
- `k`: GSVaalArchivistLightningBlast
- `n`: GSVaalArchivistLightningBlast
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSVaalArchivistLightningBlast","n":"GSVaalArchivistLightningBlast","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 84. GSWraithSpookyRunemarkedIceLightningProjectileImpact

- Match score: `70`
- `k`: GSWraithSpookyRunemarkedIceLightningProjectileImpact
- `n`: GSWraithSpookyRunemarkedIceLightningProjectileImpact
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSWraithSpookyRunemarkedIceLightningProjectileImpact","n":"GSWraithSpookyRunemarkedIceLightningProjectileImpact","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 85. GTBoneCultistZealotRunemarkedLightningStorm

- Match score: `70`
- `k`: GTBoneCultistZealotRunemarkedLightningStorm
- `n`: GTBoneCultistZealotRunemarkedLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTBoneCultistZealotRunemarkedLightningStorm","n":"GTBoneCultistZealotRunemarkedLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 86. GTBoneZealotAbyssLightningStorm

- Match score: `70`
- `k`: GTBoneZealotAbyssLightningStorm
- `n`: GTBoneZealotAbyssLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTBoneZealotAbyssLightningStorm","n":"GTBoneZealotAbyssLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 87. GTBoneZealotLightningStorm

- Match score: `70`
- `k`: GTBoneZealotLightningStorm
- `n`: GTBoneZealotLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTBoneZealotLightningStorm","n":"GTBoneZealotLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 88. GTDeliriumFinalBossLightningProjectileSpam

- Match score: `70`
- `k`: GTDeliriumFinalBossLightningProjectileSpam
- `n`: GTDeliriumFinalBossLightningProjectileSpam
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTDeliriumFinalBossLightningProjectileSpam","n":"GTDeliriumFinalBossLightningProjectileSpam","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 89. GTDoryaniLightningStorm

- Match score: `70`
- `k`: GTDoryaniLightningStorm
- `n`: GTDoryaniLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTDoryaniLightningStorm","n":"GTDoryaniLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 90. GTDoryaniLightningStormMaps

- Match score: `70`
- `k`: GTDoryaniLightningStormMaps
- `n`: GTDoryaniLightningStormMaps
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTDoryaniLightningStormMaps","n":"GTDoryaniLightningStormMaps","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 91. GTKaruiCaptainBoss2ValakoLightningStorm

- Match score: `70`
- `k`: GTKaruiCaptainBoss2ValakoLightningStorm
- `n`: GTKaruiCaptainBoss2ValakoLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTKaruiCaptainBoss2ValakoLightningStorm","n":"GTKaruiCaptainBoss2ValakoLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 92. GTMonsterModLightningStorm

- Match score: `70`
- `k`: GTMonsterModLightningStorm
- `n`: GTMonsterModLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTMonsterModLightningStorm","n":"GTMonsterModLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 93. GTPlayerMonsterModLightningStorm

- Match score: `70`
- `k`: GTPlayerMonsterModLightningStorm
- `n`: GTPlayerMonsterModLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTPlayerMonsterModLightningStorm","n":"GTPlayerMonsterModLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 94. GTStormGuardCallLightning

- Match score: `70`
- `k`: GTStormGuardCallLightning
- `n`: GTStormGuardCallLightning
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTStormGuardCallLightning","n":"GTStormGuardCallLightning","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 95. HeistRobotStormcallerShockRifleSingle

- Match score: `70`
- `k`: HeistRobotStormcallerShockRifleSingle
- `n`: HeistRobotStormcallerShockRifleSingle
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"HeistRobotStormcallerShockRifleSingle","n":"HeistRobotStormcallerShockRifleSingle","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 96. IncursionArchitectLightningSlashLeft

- Match score: `70`
- `k`: IncursionArchitectLightningSlashLeft
- `n`: IncursionArchitectLightningSlashLeft
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionArchitectLightningSlashLeft","n":"IncursionArchitectLightningSlashLeft","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 97. IncursionArchitectLightningSlashRight

- Match score: `70`
- `k`: IncursionArchitectLightningSlashRight
- `n`: IncursionArchitectLightningSlashRight
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionArchitectLightningSlashRight","n":"IncursionArchitectLightningSlashRight","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 98. IncursionChaosArchitectProjectile1

- Match score: `70`
- `k`: IncursionChaosArchitectProjectile1
- `n`: IncursionChaosArchitectProjectile1
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionChaosArchitectProjectile1","n":"IncursionChaosArchitectProjectile1","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 99. IncursionChaosArchitectProjectile2

- Match score: `70`
- `k`: IncursionChaosArchitectProjectile2
- `n`: IncursionChaosArchitectProjectile2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionChaosArchitectProjectile2","n":"IncursionChaosArchitectProjectile2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 100. IncursionChaosArchitectProjectile3

- Match score: `70`
- `k`: IncursionChaosArchitectProjectile3
- `n`: IncursionChaosArchitectProjectile3
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionChaosArchitectProjectile3","n":"IncursionChaosArchitectProjectile3","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 101. IncursionChaosArchitectProjectile4

- Match score: `70`
- `k`: IncursionChaosArchitectProjectile4
- `n`: IncursionChaosArchitectProjectile4
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionChaosArchitectProjectile4","n":"IncursionChaosArchitectProjectile4","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 102. IncursionChaosArchitectProjectile5

- Match score: `70`
- `k`: IncursionChaosArchitectProjectile5
- `n`: IncursionChaosArchitectProjectile5
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionChaosArchitectProjectile5","n":"IncursionChaosArchitectProjectile5","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 103. IncursionChaosArchitectProjectile6

- Match score: `70`
- `k`: IncursionChaosArchitectProjectile6
- `n`: IncursionChaosArchitectProjectile6
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionChaosArchitectProjectile6","n":"IncursionChaosArchitectProjectile6","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 104. IncursionSummonLightningStorm

- Match score: `70`
- `k`: IncursionSummonLightningStorm
- `n`: IncursionSummonLightningStorm
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionSummonLightningStorm","n":"IncursionSummonLightningStorm","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 105. IncursionSummonLightningStorm2

- Match score: `70`
- `k`: IncursionSummonLightningStorm2
- `n`: IncursionSummonLightningStorm2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"IncursionSummonLightningStorm2","n":"IncursionSummonLightningStorm2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 106. Inexorable Critical I

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemInevitableCriticalsSupport
- `n`: Inexorable Critical I
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemInevitableCriticalsSupport","n":"Inexorable Critical I","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 107. Inexorable Critical II

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemInevitableCriticalsSupportTwo
- `n`: Inexorable Critical II
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemInevitableCriticalsSupportTwo","n":"Inexorable Critical II","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 108. Lightning Exposure

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemLightningExposureSupport
- `n`: Lightning Exposure
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"duration":true,"lightning":true,"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemLightningExposureSupport","n":"Lightning Exposure","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"duration":true,"lightning":true,"support":true}}
```

### 109. Lightning Penetration

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemLightningPenetrationSupport
- `n`: Lightning Penetration
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"lightning":true,"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemLightningPenetrationSupport","n":"Lightning Penetration","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"lightning":true,"support":true}}
```

### 110. LightningBoltRogueExileSorceress2

- Match score: `70`
- `k`: LightningBoltRogueExileSorceress2
- `n`: LightningBoltRogueExileSorceress2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"LightningBoltRogueExileSorceress2","n":"LightningBoltRogueExileSorceress2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 111. LightningIncursionSpark

- Match score: `70`
- `k`: LightningIncursionSpark
- `n`: LightningIncursionSpark
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"LightningIncursionSpark","n":"LightningIncursionSpark","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 112. LightningIncursionSparkEpic

- Match score: `70`
- `k`: LightningIncursionSparkEpic
- `n`: LightningIncursionSparkEpic
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"LightningIncursionSparkEpic","n":"LightningIncursionSparkEpic","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 113. LightningWarpRogueExileSorceress2

- Match score: `70`
- `k`: LightningWarpRogueExileSorceress2
- `n`: LightningWarpRogueExileSorceress2
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"LightningWarpRogueExileSorceress2","n":"LightningWarpRogueExileSorceress2","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 114. MetaCastOnElementalAilmentPlayer

- Match score: `70`
- `k`: MetaCastOnElementalAilmentPlayer
- `n`: MetaCastOnElementalAilmentPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MetaCastOnElementalAilmentPlayer","n":"MetaCastOnElementalAilmentPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 115. Metadata/Items/Gems/SkillGemCastOnCritical

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemCastOnCritical
- `n`: Metadata/Items/Gems/SkillGemCastOnCritical
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["intelligence","grants_active_skill","buff","persistent","trigger","meta"]
- `base`: {"display_name":"Cast on Critical","id":"Metadata/Items/Gems/SkillGemCastOnCritical","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnCritical","n":"Metadata/Items/Gems/SkillGemCastOnCritical","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Cast on Critical","id":"Metadata/Items/Gems/SkillGemCastOnCritical","release_state":"released"},"tags":["intelligence","grants_active_skill","buff","persistent","trigger","meta"]}
```

### 116. Metadata/Items/Gems/SupportGemBlazingCritical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemBlazingCritical
- `n`: Metadata/Items/Gems/SupportGemBlazingCritical
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support","attack","fire","duration"]
- `base`: {"display_name":"Blazing Critical","id":"Metadata/Items/Gems/SupportGemBlazingCritical","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemBlazingCritical","n":"Metadata/Items/Gems/SupportGemBlazingCritical","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Blazing Critical","id":"Metadata/Items/Gems/SupportGemBlazingCritical","release_state":"released"},"tags":["support","attack","fire","duration"]}
```

### 117. Metadata/Items/Gems/SupportGemInevitableCritical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemInevitableCritical
- `n`: Metadata/Items/Gems/SupportGemInevitableCritical
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support"]
- `base`: {"display_name":"Inexorable Critical I","id":"Metadata/Items/Gems/SupportGemInevitableCritical","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemInevitableCritical","n":"Metadata/Items/Gems/SupportGemInevitableCritical","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Inexorable Critical I","id":"Metadata/Items/Gems/SupportGemInevitableCritical","release_state":"released"},"tags":["support"]}
```

### 118. Metadata/Items/Gems/SupportGemInevitableCriticalTwo

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemInevitableCriticalTwo
- `n`: Metadata/Items/Gems/SupportGemInevitableCriticalTwo
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support"]
- `base`: {"display_name":"Inexorable Critical II","id":"Metadata/Items/Gems/SupportGemInevitableCriticalTwo","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemInevitableCriticalTwo","n":"Metadata/Items/Gems/SupportGemInevitableCriticalTwo","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Inexorable Critical II","id":"Metadata/Items/Gems/SupportGemInevitableCriticalTwo","release_state":"released"},"tags":["support"]}
```

### 119. Metadata/Items/Gems/SupportGemLightningExposure

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemLightningExposure
- `n`: Metadata/Items/Gems/SupportGemLightningExposure
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support","lightning","duration"]
- `base`: {"display_name":"Lightning Exposure","id":"Metadata/Items/Gems/SupportGemLightningExposure","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemLightningExposure","n":"Metadata/Items/Gems/SupportGemLightningExposure","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Lightning Exposure","id":"Metadata/Items/Gems/SupportGemLightningExposure","release_state":"released"},"tags":["support","lightning","duration"]}
```

### 120. Metadata/Items/Gems/SupportGemLightningPenetration

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemLightningPenetration
- `n`: Metadata/Items/Gems/SupportGemLightningPenetration
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support","lightning"]
- `base`: {"display_name":"Lightning Penetration","id":"Metadata/Items/Gems/SupportGemLightningPenetration","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemLightningPenetration","n":"Metadata/Items/Gems/SupportGemLightningPenetration","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Lightning Penetration","id":"Metadata/Items/Gems/SupportGemLightningPenetration","release_state":"released"},"tags":["support","lightning"]}
```

## Item bases/classes

- Source: `build_knowledge/compact/item_base_index.json`
- Matches included: `120`

### 1. archer_boss_area

- Match score: `70`
- `k`: archer_boss_area
- `n`: archer_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archer_boss_area","n":"archer_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 2. archer_boss_area

- Match score: `70`
- `k`: 835
- `n`: archer_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"835","n":"archer_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archer_boss_area"}
```

### 3. archives_area

- Match score: `70`
- `k`: archives_area
- `n`: archives_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archives_area","n":"archives_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 4. archives_area

- Match score: `70`
- `k`: 431
- `n`: archives_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"431","n":"archives_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archives_area"}
```

### 5. Blazing Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemBlazingCritical
- `n`: Blazing Critical
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemBlazingCritical","n":"Blazing Critical","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 6. Cast on Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemCastOnCritical
- `n`: Cast on Critical
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnCritical","n":"Cast on Critical","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Meta Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 7. Cast on Elemental Ailment

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemCastOnElementalAilment
- `n`: Cast on Elemental Ailment
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnElementalAilment","n":"Cast on Elemental Ailment","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Meta Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 8. caster_critical

- Match score: `70`
- `k`: caster_critical
- `n`: caster_critical
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"caster_critical","n":"caster_critical","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 9. caster_critical

- Match score: `70`
- `k`: 1298
- `n`: caster_critical
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1298","n":"caster_critical","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"caster_critical"}
```

### 10. Critical

- Match score: `70`
- `k`: critical
- `n`: Critical
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"critical","n":"Critical","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 11. critical

- Match score: `70`
- `k`: 575
- `n`: critical
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"575","n":"critical","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"critical"}
```

### 12. Critical Wand

- Match score: `70`
- `k`: Metadata/Items/Weapons/OneHandWeapons/Wands/FourWand11
- `n`: Critical Wand
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["wand","onehand","default"]
- `req`: {"dexterity":0,"intelligence":92,"level":52,"strength":0}
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/OneHandWeapons/Wands/FourWand11","n":"Critical Wand","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Wand","tags":["wand","onehand","default"],"req":{"dexterity":0,"intelligence":92,"level":52,"strength":0},"domain":"item"}
```

### 13. critical_utility_flask

- Match score: `70`
- `k`: critical_utility_flask
- `n`: critical_utility_flask
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"critical_utility_flask","n":"critical_utility_flask","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 14. critical_utility_flask

- Match score: `70`
- `k`: 47
- `n`: critical_utility_flask
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"47","n":"critical_utility_flask","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"critical_utility_flask"}
```

### 15. Elemental Storm

- Match score: `70`
- `k`: Metadata/Items/Gem/SkillGemAscendancyElementalStorm
- `n`: Elemental Storm
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemAscendancyElementalStorm","n":"Elemental Storm","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 16. Inexorable Critical I

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemInevitableCritical
- `n`: Inexorable Critical I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemInevitableCritical","n":"Inexorable Critical I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 17. Inexorable Critical II

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemInevitableCriticalTwo
- `n`: Inexorable Critical II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemInevitableCriticalTwo","n":"Inexorable Critical II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 18. Lightning Exposure

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemLightningExposure
- `n`: Lightning Exposure
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemLightningExposure","n":"Lightning Exposure","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 19. Lightning Penetration

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemLightningPenetration
- `n`: Lightning Penetration
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemLightningPenetration","n":"Lightning Penetration","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 20. lightning_area

- Match score: `70`
- `k`: lightning_area
- `n`: lightning_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"lightning_area","n":"lightning_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 21. lightning_area

- Match score: `70`
- `k`: 402
- `n`: lightning_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"402","n":"lightning_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"lightning_area"}
```

### 22. Pinpoint Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemPinpointCritical
- `n`: Pinpoint Critical
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemPinpointCritical","n":"Pinpoint Critical","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 23. Supercritical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemSupercritical
- `n`: Supercritical
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemSupercritical","n":"Supercritical","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 24. Greater Storm Rune

- Match score: `45`
- `k`: Metadata/Items/SoulCores/RuneLightningGreater
- `n`: Greater Storm Rune
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["rune","rune_greater","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/SoulCores/RuneLightningGreater","n":"Greater Storm Rune","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"SoulCore","tags":["rune","rune_greater","default"],"domain":"undefined"}
```

### 25. Lesser Storm Rune

- Match score: `45`
- `k`: Metadata/Items/SoulCores/RuneLightningLesser
- `n`: Lesser Storm Rune
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["rune","rune_lesser","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/SoulCores/RuneLightningLesser","n":"Lesser Storm Rune","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"SoulCore","tags":["rune","rune_lesser","default"],"domain":"undefined"}
```

### 26. Perfect Storm Rune

- Match score: `45`
- `k`: Metadata/Items/SoulCores/RuneLightningPerfect
- `n`: Perfect Storm Rune
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["rune","rune_perfect","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/SoulCores/RuneLightningPerfect","n":"Perfect Storm Rune","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"SoulCore","tags":["rune","rune_perfect","default"],"domain":"undefined"}
```

### 27. Storm Rune

- Match score: `45`
- `k`: Metadata/Items/SoulCores/RuneLightning
- `n`: Storm Rune
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["rune","rune_normal","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/SoulCores/RuneLightning","n":"Storm Rune","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"SoulCore","tags":["rune","rune_normal","default"],"domain":"undefined"}
```

### 28. [DNT-UNUSED] Arcane Archery

- Match score: `35`
- `k`: Metadata/Items/Gem/SkillGemAscendancyMetaArcaneArchery
- `n`: [DNT-UNUSED] Arcane Archery
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemAscendancyMetaArcaneArchery","n":"[DNT-UNUSED] Arcane Archery","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Meta Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 29. [DNT-UNUSED] Spiral Projectiles I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemSpiralProjectiles
- `n`: [DNT-UNUSED] Spiral Projectiles I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemSpiralProjectiles","n":"[DNT-UNUSED] Spiral Projectiles I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 30. [DNT-UNUSED] Storm Blade

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemStormBlade
- `n`: [DNT-UNUSED] Storm Blade
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemStormBlade","n":"[DNT-UNUSED] Storm Blade","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 31. [DNT] Meta Ranged Attack on Shock

- Match score: `35`
- `k`: Metadata/Items/Gem/SkillGemAscendancyMetaRangedAttackOnShock
- `n`: [DNT] Meta Ranged Attack on Shock
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemAscendancyMetaRangedAttackOnShock","n":"[DNT] Meta Ranged Attack on Shock","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Meta Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 32. act6_karui_area

- Match score: `35`
- `k`: act6_karui_area
- `n`: act6_karui_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"act6_karui_area","n":"act6_karui_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 33. act6_karui_area

- Match score: `35`
- `k`: 356
- `n`: act6_karui_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"356","n":"act6_karui_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"act6_karui_area"}
```

### 34. act_boss_area

- Match score: `35`
- `k`: act_boss_area
- `n`: act_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"act_boss_area","n":"act_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 35. act_boss_area

- Match score: `35`
- `k`: 159
- `n`: act_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"159","n":"act_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"act_boss_area"}
```

### 36. Advancing Storm

- Match score: `35`
- `k`: Metadata/Items/Gem/SupportGemAdvancingStorm
- `n`: Advancing Storm
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SupportGemAdvancingStorm","n":"Advancing Storm","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 37. Aftershock I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemAftershock
- `n`: Aftershock I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemAftershock","n":"Aftershock I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 38. Aftershock II

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemAftershockTwo
- `n`: Aftershock II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemAftershockTwo","n":"Aftershock II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 39. Aftershock III

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemAftershockThree
- `n`: Aftershock III
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemAftershockThree","n":"Aftershock III","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 40. Ailment

- Match score: `35`
- `k`: ailment
- `n`: Ailment
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"ailment","n":"Ailment","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 41. ailment

- Match score: `35`
- `k`: 589
- `n`: ailment
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"589","n":"ailment","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"ailment"}
```

### 42. alira_area

- Match score: `35`
- `k`: alira_area
- `n`: alira_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"alira_area","n":"alira_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 43. alira_area

- Match score: `35`
- `k`: 794
- `n`: alira_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"794","n":"alira_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"alira_area"}
```

### 44. allows_additional_projectiles

- Match score: `35`
- `k`: allows_additional_projectiles
- `n`: allows_additional_projectiles
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"allows_additional_projectiles","n":"allows_additional_projectiles","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 45. allows_additional_projectiles

- Match score: `35`
- `k`: 728
- `n`: allows_additional_projectiles
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"728","n":"allows_additional_projectiles","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"allows_additional_projectiles"}
```

### 46. allows_inc_aoe

- Match score: `35`
- `k`: allows_inc_aoe
- `n`: allows_inc_aoe
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"allows_inc_aoe","n":"allows_inc_aoe","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 47. allows_inc_aoe

- Match score: `35`
- `k`: 729
- `n`: allows_inc_aoe
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"729","n":"allows_inc_aoe","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"allows_inc_aoe"}
```

### 48. Amanamu's Gaze

- Match score: `35`
- `k`: Metadata/Items/SoulCores/AmanamusGaze
- `n`: Amanamu's Gaze
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["abyssal_eye","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/SoulCores/AmanamusGaze","n":"Amanamu's Gaze","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"SoulCore","tags":["abyssal_eye","default"],"domain":"undefined"}
```

### 49. Amanamu's Tithe

- Match score: `35`
- `k`: Metadata/Items/Gem/SupportGemAmanamusTithe
- `n`: Amanamu's Tithe
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SupportGemAmanamusTithe","n":"Amanamu's Tithe","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 50. amanamu_mod

- Match score: `35`
- `k`: amanamu_mod
- `n`: amanamu_mod
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"amanamu_mod","n":"amanamu_mod","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 51. amanamu_mod

- Match score: `35`
- `k`: 1183
- `n`: amanamu_mod
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1183","n":"amanamu_mod","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"amanamu_mod"}
```

### 52. anarchy_leaguestone

- Match score: `35`
- `k`: anarchy_leaguestone
- `n`: anarchy_leaguestone
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"anarchy_leaguestone","n":"anarchy_leaguestone","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 53. anarchy_leaguestone

- Match score: `35`
- `k`: 218
- `n`: anarchy_leaguestone
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"218","n":"anarchy_leaguestone","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"anarchy_leaguestone"}
```

### 54. aqueduct_area

- Match score: `35`
- `k`: aqueduct_area
- `n`: aqueduct_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"aqueduct_area","n":"aqueduct_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 55. aqueduct_area

- Match score: `35`
- `k`: 377
- `n`: aqueduct_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"377","n":"aqueduct_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"aqueduct_area"}
```

### 56. arachnid_tomb_map_area

- Match score: `35`
- `k`: arachnid_tomb_map_area
- `n`: arachnid_tomb_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"arachnid_tomb_map_area","n":"arachnid_tomb_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 57. arachnid_tomb_map_area

- Match score: `35`
- `k`: 434
- `n`: arachnid_tomb_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"434","n":"arachnid_tomb_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"arachnid_tomb_map_area"}
```

### 58. arakaali_area

- Match score: `35`
- `k`: arakaali_area
- `n`: arakaali_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"arakaali_area","n":"arakaali_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 59. arakaali_area

- Match score: `35`
- `k`: 992
- `n`: arakaali_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"992","n":"arakaali_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"arakaali_area"}
```

### 60. Arc

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemArc
- `n`: Arc
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemArc","n":"Arc","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 61. Arcane Dirk

- Match score: `35`
- `k`: Metadata/Items/Weapons/OneHandWeapons/Daggers/FourDagger12
- `n`: Arcane Dirk
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["dagger","one_hand_weapon","onehand","weapon","default"]
- `req`: {"dexterity":55,"intelligence":55,"level":56,"strength":0}
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/OneHandWeapons/Daggers/FourDagger12","n":"Arcane Dirk","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Dagger","tags":["dagger","one_hand_weapon","onehand","weapon","default"],"req":{"dexterity":55,"intelligence":55,"level":56,"strength":0},"domain":"item"}
```

### 62. Arcane Raiment

- Match score: `35`
- `k`: Metadata/Items/Armours/BodyArmours/FourBodyInt15
- `n`: Arcane Raiment
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["int_armour","body_armour","armour","default"]
- `req`: {"dexterity":0,"intelligence":121,"level":73,"strength":0}
- `domain`: item

```json
{"k":"Metadata/Items/Armours/BodyArmours/FourBodyInt15","n":"Arcane Raiment","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Body Armour","tags":["int_armour","body_armour","armour","default"],"req":{"dexterity":0,"intelligence":121,"level":73,"strength":0},"domain":"item"}
```

### 63. Arcane Surge

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemArcaneSurge
- `n`: Arcane Surge
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemArcaneSurge","n":"Arcane Surge","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 64. Arcanist's Etcher

- Match score: `35`
- `k`: Metadata/Items/Currency/CurrencyMagicQuality
- `n`: Arcanist's Etcher
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quality_currency","currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyMagicQuality","n":"Arcanist's Etcher","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["quality_currency","currency","default"],"domain":"undefined"}
```

### 65. Arced Claw

- Match score: `35`
- `k`: Metadata/Items/Weapons/OneHandWeapons/Claws/FourClaw7
- `n`: Arced Claw
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["vaal_basetype","claw","one_hand_weapon","onehand","weapon","default"]
- `req`: {"dexterity":60,"intelligence":0,"level":33,"strength":0}
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/OneHandWeapons/Claws/FourClaw7","n":"Arced Claw","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Claw","tags":["vaal_basetype","claw","one_hand_weapon","onehand","weapon","default"],"req":{"dexterity":60,"intelligence":0,"level":33,"strength":0},"domain":"item"}
```

### 66. Arced Longsword

- Match score: `35`
- `k`: Metadata/Items/Weapons/TwoHandWeapons/TwoHandSwords/FourTwoHandSword6
- `n`: Arced Longsword
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["maraketh_basetype","sword","two_hand_weapon","twohand","weapon","default"]
- `req`: {"dexterity":29,"intelligence":0,"level":28,"strength":29}
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/TwoHandWeapons/TwoHandSwords/FourTwoHandSword6","n":"Arced Longsword","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Two Hand Sword","tags":["maraketh_basetype","sword","two_hand_weapon","twohand","weapon","default"],"req":{"dexterity":29,"intelligence":0,"level":28,"strength":29},"domain":"item"}
```

### 67. Arched Greataxe

- Match score: `35`
- `k`: Metadata/Items/Weapons/TwoHandWeapons/TwoHandAxes/FourTwoHandAxe4
- `n`: Arched Greataxe
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["maraketh_basetype","axe","two_hand_weapon","twohand","weapon","default"]
- `req`: {"dexterity":12,"intelligence":0,"level":16,"strength":25}
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/TwoHandWeapons/TwoHandAxes/FourTwoHandAxe4","n":"Arched Greataxe","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Two Hand Axe","tags":["maraketh_basetype","axe","two_hand_weapon","twohand","weapon","default"],"req":{"dexterity":12,"intelligence":0,"level":16,"strength":25},"domain":"item"}
```

### 68. archer_boss

- Match score: `35`
- `k`: archer_boss
- `n`: archer_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archer_boss","n":"archer_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 69. archer_boss

- Match score: `35`
- `k`: 834
- `n`: archer_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"834","n":"archer_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archer_boss"}
```

### 70. Architect's Orb

- Match score: `35`
- `k`: Metadata/Items/Currency/CurrencyIncursionDoubleCorrupt
- `n`: Architect's Orb
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["incursion_currency","currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyIncursionDoubleCorrupt","n":"Architect's Orb","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["incursion_currency","currency","default"],"domain":"undefined"}
```

### 71. Archive Reliquary Key

- Match score: `35`
- `k`: Metadata/Items/MapFragments/UberSearingExarchVaultKey
- `n`: Archive Reliquary Key
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/UberSearingExarchVaultKey","n":"Archive Reliquary Key","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"VaultKey","tags":["default"],"domain":"undefined"}
```

### 72. Archmage

- Match score: `35`
- `k`: Metadata/Items/Gem/SkillGemArchmage
- `n`: Archmage
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemArchmage","n":"Archmage","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 73. Archnemesis Mods

- Match score: `35`
- `k`: ArchnemesisMod
- `n`: Archnemesis Mods
- `cat`: repoe_item_classes
- `src`: repoe_poe2/item_classes.json

```json
{"k":"ArchnemesisMod","n":"Archnemesis Mods","cat":"repoe_item_classes","src":"repoe_poe2/item_classes.json"}
```

### 74. Archon Crown

- Match score: `35`
- `k`: Metadata/Items/Armours/Helmets/FourHelmetStrInt8
- `n`: Archon Crown
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["str_int_armour","helmet","armour","default"]
- `req`: {"dexterity":0,"intelligence":50,"level":65,"strength":50}
- `domain`: item

```json
{"k":"Metadata/Items/Armours/Helmets/FourHelmetStrInt8","n":"Archon Crown","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Helmet","tags":["str_int_armour","helmet","armour","default"],"req":{"dexterity":0,"intelligence":50,"level":65,"strength":50},"domain":"item"}
```

### 75. Archon of Chayula

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemArchonOfChayula
- `n`: Archon of Chayula
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemArchonOfChayula","n":"Archon of Chayula","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 76. Arcing Quarterstaff

- Match score: `35`
- `k`: Metadata/Items/Weapons/TwoHandWeapons/Staves/FourQuarterstaff4Cruel
- `n`: Arcing Quarterstaff
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["warstaff","two_hand_weapon","twohand","weapon","default"]
- `req`: {"dexterity":71,"intelligence":29,"level":51,"strength":0}
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/TwoHandWeapons/Staves/FourQuarterstaff4Cruel","n":"Arcing Quarterstaff","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Warstaff","tags":["warstaff","two_hand_weapon","twohand","weapon","default"],"req":{"dexterity":71,"intelligence":29,"level":51,"strength":0},"domain":"item"}
```

### 77. Arctic Armour

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemArcticArmour
- `n`: Arctic Armour
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemArcticArmour","n":"Arctic Armour","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 78. Arctic Howl

- Match score: `35`
- `k`: Metadata/Items/Gem/SkillGemWolfArcticHowl
- `n`: Arctic Howl
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemWolfArcticHowl","n":"Arctic Howl","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 79. area_with_water

- Match score: `35`
- `k`: area_with_water
- `n`: area_with_water
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"area_with_water","n":"area_with_water","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 80. area_with_water

- Match score: `35`
- `k`: 170
- `n`: area_with_water
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"170","n":"area_with_water","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"area_with_water"}
```

### 81. arena_area

- Match score: `35`
- `k`: arena_area
- `n`: arena_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"arena_area","n":"arena_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 82. arena_area

- Match score: `35`
- `k`: 401
- `n`: arena_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"401","n":"arena_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"arena_area"}
```

### 83. atziri_area

- Match score: `35`
- `k`: atziri_area
- `n`: atziri_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"atziri_area","n":"atziri_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 84. atziri_area

- Match score: `35`
- `k`: 824
- `n`: atziri_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"824","n":"atziri_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"atziri_area"}
```

### 85. Ball Lightning

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemBallLightning
- `n`: Ball Lightning
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemBallLightning","n":"Ball Lightning","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 86. bandit_area

- Match score: `35`
- `k`: bandit_area
- `n`: bandit_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bandit_area","n":"bandit_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 87. bandit_area

- Match score: `35`
- `k`: 379
- `n`: bandit_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"379","n":"bandit_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bandit_area"}
```

### 88. belly_area

- Match score: `35`
- `k`: belly_area
- `n`: belly_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"belly_area","n":"belly_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 89. belly_area

- Match score: `35`
- `k`: 361
- `n`: belly_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"361","n":"belly_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"belly_area"}
```

### 90. blight_death_lightning

- Match score: `35`
- `k`: blight_death_lightning
- `n`: blight_death_lightning
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"blight_death_lightning","n":"blight_death_lightning","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 91. blight_death_lightning

- Match score: `35`
- `k`: 466
- `n`: blight_death_lightning
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"466","n":"blight_death_lightning","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"blight_death_lightning"}
```

### 92. Bonestorm

- Match score: `35`
- `k`: Metadata/Items/Gem/SkillGemBonestorm
- `n`: Bonestorm
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SkillGemBonestorm","n":"Bonestorm","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Active Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 93. breach_monster_lightning

- Match score: `35`
- `k`: breach_monster_lightning
- `n`: breach_monster_lightning
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"breach_monster_lightning","n":"breach_monster_lightning","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 94. breach_monster_lightning

- Match score: `35`
- `k`: 1000
- `n`: breach_monster_lightning
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1000","n":"breach_monster_lightning","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"breach_monster_lightning"}
```

### 95. bridge_area

- Match score: `35`
- `k`: bridge_area
- `n`: bridge_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bridge_area","n":"bridge_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 96. bridge_area

- Match score: `35`
- `k`: 877
- `n`: bridge_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"877","n":"bridge_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bridge_area"}
```

### 97. cannot_be_archnemesis

- Match score: `35`
- `k`: cannot_be_archnemesis
- `n`: cannot_be_archnemesis
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cannot_be_archnemesis","n":"cannot_be_archnemesis","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 98. cannot_be_archnemesis

- Match score: `35`
- `k`: 921
- `n`: cannot_be_archnemesis
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"921","n":"cannot_be_archnemesis","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cannot_be_archnemesis"}
```

### 99. cannot_be_map_archnemesis

- Match score: `35`
- `k`: cannot_be_map_archnemesis
- `n`: cannot_be_map_archnemesis
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cannot_be_map_archnemesis","n":"cannot_be_map_archnemesis","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 100. cannot_be_map_archnemesis

- Match score: `35`
- `k`: 926
- `n`: cannot_be_map_archnemesis
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"926","n":"cannot_be_map_archnemesis","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cannot_be_map_archnemesis"}
```

### 101. carver_culture_area

- Match score: `35`
- `k`: carver_culture_area
- `n`: carver_culture_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"carver_culture_area","n":"carver_culture_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 102. carver_culture_area

- Match score: `35`
- `k`: 1231
- `n`: carver_culture_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1231","n":"carver_culture_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"carver_culture_area"}
```

### 103. Cast on Shock

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemCastOnShock
- `n`: Cast on Shock
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnShock","n":"Cast on Shock","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Meta Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 104. catacomb_area

- Match score: `35`
- `k`: catacomb_area
- `n`: catacomb_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"catacomb_area","n":"catacomb_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 105. catacomb_area

- Match score: `35`
- `k`: 371
- `n`: catacomb_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"371","n":"catacomb_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"catacomb_area"}
```

### 106. cave_area

- Match score: `35`
- `k`: cave_area
- `n`: cave_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cave_area","n":"cave_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 107. cave_area

- Match score: `35`
- `k`: 399
- `n`: cave_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"399","n":"cave_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cave_area"}
```

### 108. cemetery_map_area

- Match score: `35`
- `k`: cemetery_map_area
- `n`: cemetery_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cemetery_map_area","n":"cemetery_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 109. cemetery_map_area

- Match score: `35`
- `k`: 435
- `n`: cemetery_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"435","n":"cemetery_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cemetery_map_area"}
```

### 110. chamber_of_sins_area

- Match score: `35`
- `k`: chamber_of_sins_area
- `n`: chamber_of_sins_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chamber_of_sins_area","n":"chamber_of_sins_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 111. chamber_of_sins_area

- Match score: `35`
- `k`: 365
- `n`: chamber_of_sins_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"365","n":"chamber_of_sins_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chamber_of_sins_area"}
```

### 112. chaos_golem_boss_area

- Match score: `35`
- `k`: chaos_golem_boss_area
- `n`: chaos_golem_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chaos_golem_boss_area","n":"chaos_golem_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 113. chaos_golem_boss_area

- Match score: `35`
- `k`: 807
- `n`: chaos_golem_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"807","n":"chaos_golem_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chaos_golem_boss_area"}
```

### 114. coast_boat_area

- Match score: `35`
- `k`: coast_boat_area
- `n`: coast_boat_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"coast_boat_area","n":"coast_boat_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 115. coast_boat_area

- Match score: `35`
- `k`: 414
- `n`: coast_boat_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"414","n":"coast_boat_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"coast_boat_area"}
```

### 116. Cold Exposure

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

### 117. Cold Penetration

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

### 118. Colossal Mana Flask

- Match score: `35`
- `k`: Metadata/Items/Flasks/FourFlaskMana6
- `n`: Colossal Mana Flask
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["mana_flask","flask","default"]
- `domain`: flask

```json
{"k":"Metadata/Items/Flasks/FourFlaskMana6","n":"Colossal Mana Flask","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"ManaFlask","tags":["mana_flask","flask","default"],"domain":"flask"}
```

### 119. Concentrated Area

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemConcentratedEffect
- `n`: Concentrated Area
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemConcentratedEffect","n":"Concentrated Area","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 120. core_map_area

- Match score: `35`
- `k`: core_map_area
- `n`: core_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"core_map_area","n":"core_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

## Mods and affixes

- Source: `build_knowledge/compact/mod_index.json`
- Matches included: `120`

### 1. <<ExpedRuneElectrocuting>><rgb(219,217,206)>{Electrocuting Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Lightning Damage}
<rgb(135,134,253)>{Lightning Damage Electrocutes}
<rgb(135,134,253)>{Shocked Ground Trails}

- Match score: `140`
- `k`: ExpeditionMonsterModRuneElectrocuting
- `n`: <<ExpedRuneElectrocuting>><rgb(219,217,206)>{Electrocuting Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Lightning Damage}
<rgb(135,134,253)>{Lightning Damage Electrocutes}
<rgb(135,134,253)>{Shocked Ground Trails}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"non_skill_base_all_damage_%_to_gain_as_lightning","max":10,"min":10},{"id":"base_lightning_damage_can_electrocute","max":1,"min":1},{"id":"active_skill_electrocutes_as_though_dealt_damage_+%_final","max":-50,"min":-50},{"id":"dummy_expedition_rune_electrocuting","max":1,"min":1}]

```json
{"k":"ExpeditionMonsterModRuneElectrocuting","n":"<<ExpedRuneElectrocuting>><rgb(219,217,206)>{Electrocuting Rune}\r\n<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}\r\n<rgb(135,134,253)>{Extra Lightning Damage}\r\n<rgb(135,134,253)>{Lightning Damage Electrocutes}\r\n<rgb(135,134,253)>{Shocked Ground Trails}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_base_all_damage_%_to_gain_as_lightning","max":10,"min":10},{"id":"base_lightning_damage_can_electrocute","max":1,"min":1},{"id":"active_skill_electrocutes_as_though_dealt_damage_+%_final","max":-50,"min":-50},{"id":"dummy_expedition_rune_electrocuting","max":1,"min":1}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 2. <<ExpedRuneElectrocuting>><rgb(219,217,206)>{Electrocuting Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Lightning Damage}
<rgb(135,134,253)>{Lightning Damage Electrocutes}
<rgb(135,134,253)>{Shocked Ground Trails}

- Match score: `140`
- `k`: ExpeditionMonsterModRuneElectrocutingPower
- `n`: <<ExpedRuneElectrocuting>><rgb(219,217,206)>{Electrocuting Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Lightning Damage}
<rgb(135,134,253)>{Lightning Damage Electrocutes}
<rgb(135,134,253)>{Shocked Ground Trails}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"non_skill_base_all_damage_%_to_gain_as_lightning","max":20,"min":20},{"id":"base_lightning_damage_can_electrocute","max":1,"min":1},{"id":"active_skill_electrocutes_as_though_dealt_damage_+%_final","max":-15,"min":-15},{"id":"dummy_expedition_rune_electrocuting","max":1,"min":1}]

```json
{"k":"ExpeditionMonsterModRuneElectrocutingPower","n":"<<ExpedRuneElectrocuting>><rgb(219,217,206)>{Electrocuting Rune}\r\n<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}\r\n<rgb(135,134,253)>{Extra Lightning Damage}\r\n<rgb(135,134,253)>{Lightning Damage Electrocutes}\r\n<rgb(135,134,253)>{Shocked Ground Trails}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_base_all_damage_%_to_gain_as_lightning","max":20,"min":20},{"id":"base_lightning_damage_can_electrocute","max":1,"min":1},{"id":"active_skill_electrocutes_as_though_dealt_damage_+%_final","max":-15,"min":-15},{"id":"dummy_expedition_rune_electrocuting","max":1,"min":1}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 3. UniqueCriticalDamageBonusWhileShocked1

- Match score: `140`
- `k`: UniqueCriticalDamageBonusWhileShocked1
- `n`: UniqueCriticalDamageBonusWhileShocked1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_bonus_+%_final_while_shocked","max":25,"min":15}]

```json
{"k":"UniqueCriticalDamageBonusWhileShocked1","n":"UniqueCriticalDamageBonusWhileShocked1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_bonus_+%_final_while_shocked","max":25,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 4. ImmuneToElementalAilmentsWhileLifeAndManaCloseUnique__1

- Match score: `115`
- `k`: ImmuneToElementalAilmentsWhileLifeAndManaCloseUnique__1
- `n`: ImmuneToElementalAilmentsWhileLifeAndManaCloseUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"unaffected_by_ignite_and_shock_while_max_life_mana_within_500","max":1,"min":1}]

```json
{"k":"ImmuneToElementalAilmentsWhileLifeAndManaCloseUnique__1","n":"ImmuneToElementalAilmentsWhileLifeAndManaCloseUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"unaffected_by_ignite_and_shock_while_max_life_mana_within_500","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 5. MonsterProjectilesDropShockedGround

- Match score: `115`
- `k`: MonsterProjectilesDropShockedGround
- `n`: MonsterProjectilesDropShockedGround
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"projectiles_drop_ground_lightning","max":1,"min":1},{"id":"base_projectile_ground_effect_duration","max":3000,"min":3000}]

```json
{"k":"MonsterProjectilesDropShockedGround","n":"MonsterProjectilesDropShockedGround","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"projectiles_drop_ground_lightning","max":1,"min":1},{"id":"base_projectile_ground_effect_duration","max":3000,"min":3000}],"domain":"monster","gen":"unique","lvl":1}
```

### 6. AddedLightningDamagePerShockedEnemyKilledUnique__1

- Match score: `105`
- `k`: AddedLightningDamagePerShockedEnemyKilledUnique__1
- `n`: AddedLightningDamagePerShockedEnemyKilledUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"minimum_added_lightning_damage_per_shocked_enemy_killed_recently","max":1,"min":1},{"id":"maximum_added_lightning_damage_per_shocked_enemy_killed_recently","max":10,"min":10}]

```json
{"k":"AddedLightningDamagePerShockedEnemyKilledUnique__1","n":"AddedLightningDamagePerShockedEnemyKilledUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"minimum_added_lightning_damage_per_shocked_enemy_killed_recently","max":1,"min":1},{"id":"maximum_added_lightning_damage_per_shocked_enemy_killed_recently","max":10,"min":10}],"domain":"item","gen":"unique","lvl":1}
```

### 7. AlwaysCritShockedEnemiesUnique__1

- Match score: `105`
- `k`: AlwaysCritShockedEnemiesUnique__1
- `n`: AlwaysCritShockedEnemiesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"always_crit_shocked_enemies","max":1,"min":1}]

```json
{"k":"AlwaysCritShockedEnemiesUnique__1","n":"AlwaysCritShockedEnemiesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"always_crit_shocked_enemies","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 8. CannotCritNonShockedEnemiesUnique___1

- Match score: `105`
- `k`: CannotCritNonShockedEnemiesUnique___1
- `n`: CannotCritNonShockedEnemiesUnique___1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cannot_crit_non_shocked_enemies","max":1,"min":1}]

```json
{"k":"CannotCritNonShockedEnemiesUnique___1","n":"CannotCritNonShockedEnemiesUnique___1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cannot_crit_non_shocked_enemies","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 9. CriticalChanceIncreasedByUncappedLightningResistanceUnique__1

- Match score: `105`
- `k`: CriticalChanceIncreasedByUncappedLightningResistanceUnique__1
- `n`: CriticalChanceIncreasedByUncappedLightningResistanceUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strike_chance_increased_by_overcapped_lightning_resistance","max":1,"min":1}]

```json
{"k":"CriticalChanceIncreasedByUncappedLightningResistanceUnique__1","n":"CriticalChanceIncreasedByUncappedLightningResistanceUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_chance_increased_by_overcapped_lightning_resistance","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 10. CriticalStrikesDealIncreasedLightningDamageUnique__1

- Match score: `105`
- `k`: CriticalStrikesDealIncreasedLightningDamageUnique__1
- `n`: CriticalStrikesDealIncreasedLightningDamageUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 87
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"lightning_damage_+%","max":50,"min":50}]

```json
{"k":"CriticalStrikesDealIncreasedLightningDamageUnique__1","n":"CriticalStrikesDealIncreasedLightningDamageUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"lightning_damage_+%","max":50,"min":50}],"domain":"item","gen":"unique","lvl":87}
```

### 11. CriticalStrikesDealIncreasedLightningDamageUnique__1Royale_

- Match score: `105`
- `k`: CriticalStrikesDealIncreasedLightningDamageUnique__1Royale_
- `n`: CriticalStrikesDealIncreasedLightningDamageUnique__1Royale_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 87
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"lightning_damage_+%","max":20,"min":20}]

```json
{"k":"CriticalStrikesDealIncreasedLightningDamageUnique__1Royale_","n":"CriticalStrikesDealIncreasedLightningDamageUnique__1Royale_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"lightning_damage_+%","max":20,"min":20}],"domain":"item","gen":"unique","lvl":87}
```

### 12. HandWrapsAbyssModGlovesKurgalSuffixArcaneSurgeOnCriticalHit

- Match score: `105`
- `k`: HandWrapsAbyssModGlovesKurgalSuffixArcaneSurgeOnCriticalHit
- `n`: HandWrapsAbyssModGlovesKurgalSuffixArcaneSurgeOnCriticalHit
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"HandWrapsAbyssModGlovesKurgalSuffixArcaneSurgeOnCriticalHit","n":"HandWrapsAbyssModGlovesKurgalSuffixArcaneSurgeOnCriticalHit","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":1}
```

### 13. ManaRegenerationWhileShockedEssence1

- Match score: `105`
- `k`: ManaRegenerationWhileShockedEssence1
- `n`: ManaRegenerationWhileShockedEssence1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ManaRegenerationWhileShockedEssence1","n":"ManaRegenerationWhileShockedEssence1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":63}
```

### 14. PassageUniqueAmanamuReducedIncomingCriticalBonus

- Match score: `105`
- `k`: PassageUniqueAmanamuReducedIncomingCriticalBonus
- `n`: PassageUniqueAmanamuReducedIncomingCriticalBonus
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"base_self_critical_strike_multiplier_-%","max":30,"min":20}]

```json
{"k":"PassageUniqueAmanamuReducedIncomingCriticalBonus","n":"PassageUniqueAmanamuReducedIncomingCriticalBonus","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_self_critical_strike_multiplier_-%","max":30,"min":20}],"domain":"item","gen":"unique","lvl":1}
```

### 15. ProjectileAttackCriticalStrikeChanceUnique__1

- Match score: `105`
- `k`: ProjectileAttackCriticalStrikeChanceUnique__1
- `n`: ProjectileAttackCriticalStrikeChanceUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"projectile_attack_skill_critical_strike_chance_+%","max":60,"min":40}]

```json
{"k":"ProjectileAttackCriticalStrikeChanceUnique__1","n":"ProjectileAttackCriticalStrikeChanceUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"projectile_attack_skill_critical_strike_chance_+%","max":60,"min":40}],"domain":"item","gen":"unique","lvl":1}
```

### 16. StormBladeEnchantmentLocalLightningPenetration

- Match score: `105`
- `k`: StormBladeEnchantmentLocalLightningPenetration
- `n`: StormBladeEnchantmentLocalLightningPenetration
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_lightning_penetration_%","max":0,"min":0}]

```json
{"k":"StormBladeEnchantmentLocalLightningPenetration","n":"StormBladeEnchantmentLocalLightningPenetration","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_lightning_penetration_%","max":0,"min":0}],"domain":"item","gen":"unique","lvl":1}
```

### 17. UniqueCriticalStrikesIgnoreLightningResistance1

- Match score: `105`
- `k`: UniqueCriticalStrikesIgnoreLightningResistance1
- `n`: UniqueCriticalStrikesIgnoreLightningResistance1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 69
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strikes_ignore_lightning_resistance","max":1,"min":1}]

```json
{"k":"UniqueCriticalStrikesIgnoreLightningResistance1","n":"UniqueCriticalStrikesIgnoreLightningResistance1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strikes_ignore_lightning_resistance","max":1,"min":1}],"domain":"item","gen":"unique","lvl":69}
```

### 18. UniqueLightningExposureOnCrit1

- Match score: `105`
- `k`: UniqueLightningExposureOnCrit1
- `n`: UniqueLightningExposureOnCrit1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"inflict_lightning_exposure_on_crit","max":1,"min":1}]

```json
{"k":"UniqueLightningExposureOnCrit1","n":"UniqueLightningExposureOnCrit1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"inflict_lightning_exposure_on_crit","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 19. UniqueMutatedVaalSpellCriticalChancePerMana

- Match score: `105`
- `k`: UniqueMutatedVaalSpellCriticalChancePerMana
- `n`: UniqueMutatedVaalSpellCriticalChancePerMana
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"spell_critical_strike_chance_+%_per_100_max_mana_with_non_channelling_skills","max":3,"min":3}]

```json
{"k":"UniqueMutatedVaalSpellCriticalChancePerMana","n":"UniqueMutatedVaalSpellCriticalChancePerMana","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"spell_critical_strike_chance_+%_per_100_max_mana_with_non_channelling_skills","max":3,"min":3}],"domain":"item","gen":"unique","lvl":1}
```

### 20. UniqueProjectileIncreasedCriticalHitChancePerPierce1

- Match score: `105`
- `k`: UniqueProjectileIncreasedCriticalHitChancePerPierce1
- `n`: UniqueProjectileIncreasedCriticalHitChancePerPierce1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"projectiles_crit_chance_+%_for_each_time_they_have_pierced","max":64,"min":42}]

```json
{"k":"UniqueProjectileIncreasedCriticalHitChancePerPierce1","n":"UniqueProjectileIncreasedCriticalHitChancePerPierce1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"projectiles_crit_chance_+%_for_each_time_they_have_pierced","max":64,"min":42}],"domain":"item","gen":"unique","lvl":1}
```

### 21. UniqueTriggerLightningBoltOnCriticalStrike1

- Match score: `105`
- `k`: UniqueTriggerLightningBoltOnCriticalStrike1
- `n`: UniqueTriggerLightningBoltOnCriticalStrike1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 69
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_display_triggers_level_x_lightning_bolt_on_critical_strike","max":1,"min":1}]

```json
{"k":"UniqueTriggerLightningBoltOnCriticalStrike1","n":"UniqueTriggerLightningBoltOnCriticalStrike1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_display_triggers_level_x_lightning_bolt_on_critical_strike","max":1,"min":1}],"domain":"item","gen":"unique","lvl":69}
```

### 22. UniqueTriggerSparkOnKillingShockedEnemy1

- Match score: `105`
- `k`: UniqueTriggerSparkOnKillingShockedEnemy1
- `n`: UniqueTriggerSparkOnKillingShockedEnemy1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_display_triggers_level_x_spark_on_killing_shocked_enemy_with_enemy_location_as_origin","max":1,"min":1}]

```json
{"k":"UniqueTriggerSparkOnKillingShockedEnemy1","n":"UniqueTriggerSparkOnKillingShockedEnemy1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_display_triggers_level_x_spark_on_killing_shocked_enemy_with_enemy_location_as_origin","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 23. ZealotryCriticalStrikesPenetratesElementalResistances

- Match score: `105`
- `k`: ZealotryCriticalStrikesPenetratesElementalResistances
- `n`: ZealotryCriticalStrikesPenetratesElementalResistances
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strikes_penetrates_%_elemental_resistances_while_affected_by_zealotry","max":10,"min":8}]

```json
{"k":"ZealotryCriticalStrikesPenetratesElementalResistances","n":"ZealotryCriticalStrikesPenetratesElementalResistances","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strikes_penetrates_%_elemental_resistances_while_affected_by_zealotry","max":10,"min":8}],"domain":"item","gen":"unique","lvl":1}
```

### 24. MapShockedGroundDelve

- Match score: `90`
- `k`: MapShockedGroundDelve
- `n`: MapShockedGroundDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":20,"min":20},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}]

```json
{"k":"MapShockedGroundDelve","n":"MapShockedGroundDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":20,"min":20},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 25. MapShockedGroundDelve2_

- Match score: `90`
- `k`: MapShockedGroundDelve2_
- `n`: MapShockedGroundDelve2_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":35,"min":35},{"id":"map_ground_effect_patches_per_100_tiles","max":24,"min":24},{"id":"map_ground_effect_radius","max":16,"min":16}]

```json
{"k":"MapShockedGroundDelve2_","n":"MapShockedGroundDelve2_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":35,"min":35},{"id":"map_ground_effect_patches_per_100_tiles","max":24,"min":24},{"id":"map_ground_effect_radius","max":16,"min":16}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 26. MapShockedGroundDelve3

- Match score: `90`
- `k`: MapShockedGroundDelve3
- `n`: MapShockedGroundDelve3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":50,"min":50},{"id":"map_ground_effect_patches_per_100_tiles","max":28,"min":28},{"id":"map_ground_effect_radius","max":18,"min":18}]

```json
{"k":"MapShockedGroundDelve3","n":"MapShockedGroundDelve3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":50,"min":50},{"id":"map_ground_effect_patches_per_100_tiles","max":28,"min":28},{"id":"map_ground_effect_radius","max":18,"min":18}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 27. MapShockedGroundDescent2

- Match score: `90`
- `k`: MapShockedGroundDescent2
- `n`: MapShockedGroundDescent2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_ground_lightning","max":1,"min":1},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}]

```json
{"k":"MapShockedGroundDescent2","n":"MapShockedGroundDescent2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_ground_lightning","max":1,"min":1},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}],"domain":"area","gen":"unique","lvl":1}
```

### 28. MapShockedGroundStrDexIntMission

- Match score: `90`
- `k`: MapShockedGroundStrDexIntMission
- `n`: MapShockedGroundStrDexIntMission
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":40,"min":30},{"id":"map_item_drop_rarity_+%","max":40,"min":30},{"id":"map_ground_lightning","max":1,"min":1},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}]

```json
{"k":"MapShockedGroundStrDexIntMission","n":"MapShockedGroundStrDexIntMission","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":40,"min":30},{"id":"map_item_drop_rarity_+%","max":40,"min":30},{"id":"map_ground_lightning","max":1,"min":1},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}],"domain":"area","gen":"unique","lvl":1}
```

### 29. MapSimulacrumInflictAilmentsAndPenetration1_

- Match score: `90`
- `k`: MapSimulacrumInflictAilmentsAndPenetration1_
- `n`: MapSimulacrumInflictAilmentsAndPenetration1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_chance_to_inflict_status_ailments","max":15,"min":15},{"id":"map_monsters_penetrate_elemental_resistances_%","max":5,"min":5}]

```json
{"k":"MapSimulacrumInflictAilmentsAndPenetration1_","n":"MapSimulacrumInflictAilmentsAndPenetration1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_chance_to_inflict_status_ailments","max":15,"min":15},{"id":"map_monsters_penetrate_elemental_resistances_%","max":5,"min":5}],"domain":"area","gen":"unique","lvl":1}
```

### 30. MapSimulacrumInflictAilmentsAndPenetration2

- Match score: `90`
- `k`: MapSimulacrumInflictAilmentsAndPenetration2
- `n`: MapSimulacrumInflictAilmentsAndPenetration2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_chance_to_inflict_status_ailments","max":20,"min":20},{"id":"map_monsters_penetrate_elemental_resistances_%","max":7,"min":7}]

```json
{"k":"MapSimulacrumInflictAilmentsAndPenetration2","n":"MapSimulacrumInflictAilmentsAndPenetration2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_chance_to_inflict_status_ailments","max":20,"min":20},{"id":"map_monsters_penetrate_elemental_resistances_%","max":7,"min":7}],"domain":"area","gen":"unique","lvl":1}
```

### 31. MapSimulacrumInflictAilmentsAndPenetration3

- Match score: `90`
- `k`: MapSimulacrumInflictAilmentsAndPenetration3
- `n`: MapSimulacrumInflictAilmentsAndPenetration3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_chance_to_inflict_status_ailments","max":30,"min":30},{"id":"map_monsters_penetrate_elemental_resistances_%","max":10,"min":10}]

```json
{"k":"MapSimulacrumInflictAilmentsAndPenetration3","n":"MapSimulacrumInflictAilmentsAndPenetration3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_chance_to_inflict_status_ailments","max":30,"min":30},{"id":"map_monsters_penetrate_elemental_resistances_%","max":10,"min":10}],"domain":"area","gen":"unique","lvl":1}
```

### 32. ExpeditionRelicDownsideElementalAilmentChance

- Match score: `80`
- `k`: ExpeditionRelicDownsideElementalAilmentChance
- `n`: ExpeditionRelicDownsideElementalAilmentChance
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: prefix
- `domain`: expedition_relic
- `stats`: [{"id":"ignite_chance_+%","max":100,"min":100},{"id":"hit_damage_freeze_multiplier_+%","max":100,"min":100},{"id":"shock_chance_+%","max":100,"min":100}]

```json
{"k":"ExpeditionRelicDownsideElementalAilmentChance","n":"ExpeditionRelicDownsideElementalAilmentChance","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"ignite_chance_+%","max":100,"min":100},{"id":"hit_damage_freeze_multiplier_+%","max":100,"min":100},{"id":"shock_chance_+%","max":100,"min":100}],"domain":"expedition_relic","gen":"prefix","weights":[{"tag":"expedition_atoll_remnant_logbook","weight":1},{"tag":"expedition_tundra_remnant_logbook","weight":1},{"tag":"default","weight":0}],"lvl":1}
```

### 33. LightningStrikesOnCritUnique__1

- Match score: `80`
- `k`: LightningStrikesOnCritUnique__1
- `n`: LightningStrikesOnCritUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 50
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_display_cast_lightning_on_critical_strike","max":12,"min":12}]

```json
{"k":"LightningStrikesOnCritUnique__1","n":"LightningStrikesOnCritUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_display_cast_lightning_on_critical_strike","max":12,"min":12}],"domain":"item","gen":"unique","lvl":50}
```

### 34. LightningStrikesOnCritUnique__2

- Match score: `80`
- `k`: LightningStrikesOnCritUnique__2
- `n`: LightningStrikesOnCritUnique__2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 87
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_display_cast_lightning_on_critical_strike","max":30,"min":30}]

```json
{"k":"LightningStrikesOnCritUnique__2","n":"LightningStrikesOnCritUnique__2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_display_cast_lightning_on_critical_strike","max":30,"min":30}],"domain":"item","gen":"unique","lvl":87}
```

### 35. LightningStrikesOnCritUnique__2Royale

- Match score: `80`
- `k`: LightningStrikesOnCritUnique__2Royale
- `n`: LightningStrikesOnCritUnique__2Royale
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 50
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_display_cast_lightning_on_critical_strike","max":1,"min":1}]

```json
{"k":"LightningStrikesOnCritUnique__2Royale","n":"LightningStrikesOnCritUnique__2Royale","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_display_cast_lightning_on_critical_strike","max":1,"min":1}],"domain":"item","gen":"unique","lvl":50}
```

### 36. MapMonsterCriticalStrikesAndDamageDelve

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageDelve
- `n`: MapMonsterCriticalStrikesAndDamageDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":150,"min":100},{"id":"map_monsters_critical_strike_multiplier_+","max":25,"min":20}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageDelve","n":"MapMonsterCriticalStrikesAndDamageDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":150,"min":100},{"id":"map_monsters_critical_strike_multiplier_+","max":25,"min":20}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 37. MapMonsterCriticalStrikesAndDamageDelve2

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageDelve2
- `n`: MapMonsterCriticalStrikesAndDamageDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 20
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":151},{"id":"map_monsters_critical_strike_multiplier_+","max":30,"min":26}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageDelve2","n":"MapMonsterCriticalStrikesAndDamageDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":151},{"id":"map_monsters_critical_strike_multiplier_+","max":30,"min":26}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":20}
```

### 38. MapMonsterCriticalStrikesAndDamageDelve3

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageDelve3
- `n`: MapMonsterCriticalStrikesAndDamageDelve3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":250,"min":201},{"id":"map_monsters_critical_strike_multiplier_+","max":35,"min":31}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageDelve3","n":"MapMonsterCriticalStrikesAndDamageDelve3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":250,"min":201},{"id":"map_monsters_critical_strike_multiplier_+","max":35,"min":31}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 39. MapMonsterCriticalStrikesAndDamageDelve4

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageDelve4
- `n`: MapMonsterCriticalStrikesAndDamageDelve4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 92
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":300,"min":251},{"id":"map_monsters_critical_strike_multiplier_+","max":40,"min":36}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageDelve4","n":"MapMonsterCriticalStrikesAndDamageDelve4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":300,"min":251},{"id":"map_monsters_critical_strike_multiplier_+","max":40,"min":36}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":92}
```

### 40. MapMonsterCriticalStrikesAndDamageDelve5

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageDelve5
- `n`: MapMonsterCriticalStrikesAndDamageDelve5
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":400,"min":301},{"id":"map_monsters_critical_strike_multiplier_+","max":45,"min":41}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageDelve5","n":"MapMonsterCriticalStrikesAndDamageDelve5","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":400,"min":301},{"id":"map_monsters_critical_strike_multiplier_+","max":45,"min":41}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 41. MapMonsterCriticalStrikesAndDamageLabyrinth1

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageLabyrinth1
- `n`: MapMonsterCriticalStrikesAndDamageLabyrinth1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":15,"min":15},{"id":"map_item_drop_rarity_+%","max":30,"min":30},{"id":"map_monsters_critical_strike_chance_+%","max":180,"min":180},{"id":"map_monsters_critical_strike_multiplier_+","max":33,"min":33}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageLabyrinth1","n":"MapMonsterCriticalStrikesAndDamageLabyrinth1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":15,"min":15},{"id":"map_item_drop_rarity_+%","max":30,"min":30},{"id":"map_monsters_critical_strike_chance_+%","max":180,"min":180},{"id":"map_monsters_critical_strike_multiplier_+","max":33,"min":33}],"domain":"area","gen":"unique","lvl":1}
```

### 42. MapMonsterCriticalStrikesAndDamageLabyrinth2

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageLabyrinth2
- `n`: MapMonsterCriticalStrikesAndDamageLabyrinth2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":15,"min":15},{"id":"map_item_drop_rarity_+%","max":30,"min":30},{"id":"map_monsters_critical_strike_chance_+%","max":280,"min":280},{"id":"map_monsters_critical_strike_multiplier_+","max":38,"min":38}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageLabyrinth2","n":"MapMonsterCriticalStrikesAndDamageLabyrinth2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":15,"min":15},{"id":"map_item_drop_rarity_+%","max":30,"min":30},{"id":"map_monsters_critical_strike_chance_+%","max":280,"min":280},{"id":"map_monsters_critical_strike_multiplier_+","max":38,"min":38}],"domain":"area","gen":"unique","lvl":1}
```

### 43. MapMonsterCriticalStrikesAndDamageLabyrinth3

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageLabyrinth3
- `n`: MapMonsterCriticalStrikesAndDamageLabyrinth3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":15,"min":15},{"id":"map_item_drop_rarity_+%","max":30,"min":30},{"id":"map_monsters_critical_strike_chance_+%","max":380,"min":380},{"id":"map_monsters_critical_strike_multiplier_+","max":43,"min":43}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageLabyrinth3","n":"MapMonsterCriticalStrikesAndDamageLabyrinth3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":15,"min":15},{"id":"map_item_drop_rarity_+%","max":30,"min":30},{"id":"map_monsters_critical_strike_chance_+%","max":380,"min":380},{"id":"map_monsters_critical_strike_multiplier_+","max":43,"min":43}],"domain":"area","gen":"unique","lvl":1}
```

### 44. MapMonsterCriticalStrikesAndDamagePathOfEndurance

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamagePathOfEndurance
- `n`: MapMonsterCriticalStrikesAndDamagePathOfEndurance
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_critical_strike_chance_+%","max":400,"min":400},{"id":"map_monsters_critical_strike_multiplier_+","max":45,"min":45}]

```json
{"k":"MapMonsterCriticalStrikesAndDamagePathOfEndurance","n":"MapMonsterCriticalStrikesAndDamagePathOfEndurance","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_monsters_critical_strike_chance_+%","max":400,"min":400},{"id":"map_monsters_critical_strike_multiplier_+","max":45,"min":45}],"domain":"area","gen":"unique","lvl":1}
```

### 45. MapMonsterCriticalStrikesAndDamageUnique__1

- Match score: `80`
- `k`: MapMonsterCriticalStrikesAndDamageUnique__1
- `n`: MapMonsterCriticalStrikesAndDamageUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":50,"min":50},{"id":"map_monsters_critical_strike_chance_+%","max":1000,"min":500},{"id":"map_monsters_critical_strike_multiplier_+","max":100,"min":60}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageUnique__1","n":"MapMonsterCriticalStrikesAndDamageUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":0,"min":0},{"id":"map_item_drop_rarity_+%","max":0,"min":0},{"id":"map_pack_size_+%","max":50,"min":50},{"id":"map_monsters_critical_strike_chance_+%","max":1000,"min":500},{"id":"map_monsters_critical_strike_multiplier_+","max":100,"min":60}],"domain":"area","gen":"unique","lvl":1}
```

### 46. MapMonstersBaseSelfCriticalMultiplierDelve

- Match score: `80`
- `k`: MapMonstersBaseSelfCriticalMultiplierDelve
- `n`: MapMonstersBaseSelfCriticalMultiplierDelve
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":20,"min":15}]

```json
{"k":"MapMonstersBaseSelfCriticalMultiplierDelve","n":"MapMonstersBaseSelfCriticalMultiplierDelve","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":20,"min":15}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 47. MapMonstersBaseSelfCriticalMultiplierDelve2

- Match score: `80`
- `k`: MapMonstersBaseSelfCriticalMultiplierDelve2
- `n`: MapMonstersBaseSelfCriticalMultiplierDelve2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 20
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":25,"min":21}]

```json
{"k":"MapMonstersBaseSelfCriticalMultiplierDelve2","n":"MapMonstersBaseSelfCriticalMultiplierDelve2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":25,"min":21}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":20}
```

### 48. MapMonstersBaseSelfCriticalMultiplierDelve3

- Match score: `80`
- `k`: MapMonstersBaseSelfCriticalMultiplierDelve3
- `n`: MapMonstersBaseSelfCriticalMultiplierDelve3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 52
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":30,"min":26}]

```json
{"k":"MapMonstersBaseSelfCriticalMultiplierDelve3","n":"MapMonstersBaseSelfCriticalMultiplierDelve3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":30,"min":26}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":52}
```

### 49. MapMonstersBaseSelfCriticalMultiplierDelve4

- Match score: `80`
- `k`: MapMonstersBaseSelfCriticalMultiplierDelve4
- `n`: MapMonstersBaseSelfCriticalMultiplierDelve4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 92
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":35,"min":31}]

```json
{"k":"MapMonstersBaseSelfCriticalMultiplierDelve4","n":"MapMonstersBaseSelfCriticalMultiplierDelve4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":35,"min":31}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":92}
```

### 50. MapMonstersBaseSelfCriticalMultiplierDelve5

- Match score: `80`
- `k`: MapMonstersBaseSelfCriticalMultiplierDelve5
- `n`: MapMonstersBaseSelfCriticalMultiplierDelve5
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 173
- `gen`: delve_area
- `domain`: delve_area
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":40,"min":36}]

```json
{"k":"MapMonstersBaseSelfCriticalMultiplierDelve5","n":"MapMonstersBaseSelfCriticalMultiplierDelve5","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":40,"min":36}],"domain":"delve_area","gen":"delve_area","weights":[{"tag":"default","weight":1}],"lvl":173}
```

### 51. MapShockedGroundSynthesis2__

- Match score: `80`
- `k`: MapShockedGroundSynthesis2__
- `n`: MapShockedGroundSynthesis2__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 68
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":35,"min":35},{"id":"map_ground_effect_patches_per_100_tiles","max":24,"min":24},{"id":"map_ground_effect_radius","max":16,"min":16}]

```json
{"k":"MapShockedGroundSynthesis2__","n":"MapShockedGroundSynthesis2__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":35,"min":35},{"id":"map_ground_effect_patches_per_100_tiles","max":24,"min":24},{"id":"map_ground_effect_radius","max":16,"min":16}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":68}
```

### 52. MapShockedGroundSynthesis3

- Match score: `80`
- `k`: MapShockedGroundSynthesis3
- `n`: MapShockedGroundSynthesis3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 79
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":50,"min":50},{"id":"map_ground_effect_patches_per_100_tiles","max":28,"min":28},{"id":"map_ground_effect_radius","max":18,"min":18}]

```json
{"k":"MapShockedGroundSynthesis3","n":"MapShockedGroundSynthesis3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":50,"min":50},{"id":"map_ground_effect_patches_per_100_tiles","max":28,"min":28},{"id":"map_ground_effect_radius","max":18,"min":18}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":79}
```

### 53. MapShockedGroundSynthesis_

- Match score: `80`
- `k`: MapShockedGroundSynthesis_
- `n`: MapShockedGroundSynthesis_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 50
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":20,"min":20},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}]

```json
{"k":"MapShockedGroundSynthesis_","n":"MapShockedGroundSynthesis_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":10,"min":10},{"id":"map_item_drop_rarity_+%","max":6,"min":6},{"id":"map_pack_size_+%","max":4,"min":4},{"id":"map_ground_lightning_base_magnitude","max":20,"min":20},{"id":"map_ground_effect_patches_per_100_tiles","max":20,"min":20},{"id":"map_ground_effect_radius","max":14,"min":14}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":50}
```

### 54. MapSimulacrumCriticals1

- Match score: `80`
- `k`: MapSimulacrumCriticals1
- `n`: MapSimulacrumCriticals1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":151},{"id":"map_monsters_critical_strike_multiplier_+","max":30,"min":20},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":24,"min":20}]

```json
{"k":"MapSimulacrumCriticals1","n":"MapSimulacrumCriticals1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":151},{"id":"map_monsters_critical_strike_multiplier_+","max":30,"min":20},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":24,"min":20}],"domain":"area","gen":"unique","lvl":1}
```

### 55. MapSimulacrumCriticals2

- Match score: `80`
- `k`: MapSimulacrumCriticals2
- `n`: MapSimulacrumCriticals2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_critical_strike_chance_+%","max":250,"min":201},{"id":"map_monsters_critical_strike_multiplier_+","max":40,"min":31},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":29,"min":25}]

```json
{"k":"MapSimulacrumCriticals2","n":"MapSimulacrumCriticals2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_critical_strike_chance_+%","max":250,"min":201},{"id":"map_monsters_critical_strike_multiplier_+","max":40,"min":31},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":29,"min":25}],"domain":"area","gen":"unique","lvl":1}
```

### 56. MapSimulacrumCriticals3_

- Match score: `80`
- `k`: MapSimulacrumCriticals3_
- `n`: MapSimulacrumCriticals3_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_critical_strike_chance_+%","max":300,"min":251},{"id":"map_monsters_critical_strike_multiplier_+","max":50,"min":41},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":35,"min":30}]

```json
{"k":"MapSimulacrumCriticals3_","n":"MapSimulacrumCriticals3_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_critical_strike_chance_+%","max":300,"min":251},{"id":"map_monsters_critical_strike_multiplier_+","max":50,"min":41},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":35,"min":30}],"domain":"area","gen":"unique","lvl":1}
```

### 57. MapSimulacrumExtraLightningAndAilment1

- Match score: `80`
- `k`: MapSimulacrumExtraLightningAndAilment1
- `n`: MapSimulacrumExtraLightningAndAilment1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":69,"min":60},{"id":"map_monsters_chance_to_inflict_sapped_%","max":33,"min":33}]

```json
{"k":"MapSimulacrumExtraLightningAndAilment1","n":"MapSimulacrumExtraLightningAndAilment1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":69,"min":60},{"id":"map_monsters_chance_to_inflict_sapped_%","max":33,"min":33}],"domain":"area","gen":"unique","lvl":1}
```

### 58. MapSimulacrumExtraLightningAndAilment2_

- Match score: `80`
- `k`: MapSimulacrumExtraLightningAndAilment2_
- `n`: MapSimulacrumExtraLightningAndAilment2_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":79,"min":70},{"id":"map_monsters_chance_to_inflict_sapped_%","max":66,"min":66}]

```json
{"k":"MapSimulacrumExtraLightningAndAilment2_","n":"MapSimulacrumExtraLightningAndAilment2_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":79,"min":70},{"id":"map_monsters_chance_to_inflict_sapped_%","max":66,"min":66}],"domain":"area","gen":"unique","lvl":1}
```

### 59. MapSimulacrumExtraLightningAndAilment3___

- Match score: `80`
- `k`: MapSimulacrumExtraLightningAndAilment3___
- `n`: MapSimulacrumExtraLightningAndAilment3___
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":100,"min":80},{"id":"map_monsters_chance_to_inflict_sapped_%","max":100,"min":100}]

```json
{"k":"MapSimulacrumExtraLightningAndAilment3___","n":"MapSimulacrumExtraLightningAndAilment3___","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":100,"min":80},{"id":"map_monsters_chance_to_inflict_sapped_%","max":100,"min":100}],"domain":"area","gen":"unique","lvl":1}
```

### 60. MapSimulacrumExtraLightningAndPenetration1

- Match score: `80`
- `k`: MapSimulacrumExtraLightningAndPenetration1
- `n`: MapSimulacrumExtraLightningAndPenetration1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":69,"min":60},{"id":"map_monsters_reduce_enemy_lightning_resistance_%","max":5,"min":5}]

```json
{"k":"MapSimulacrumExtraLightningAndPenetration1","n":"MapSimulacrumExtraLightningAndPenetration1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":69,"min":60},{"id":"map_monsters_reduce_enemy_lightning_resistance_%","max":5,"min":5}],"domain":"area","gen":"unique","lvl":1}
```

### 61. MapSimulacrumExtraLightningAndPenetration2__

- Match score: `80`
- `k`: MapSimulacrumExtraLightningAndPenetration2__
- `n`: MapSimulacrumExtraLightningAndPenetration2__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":79,"min":70},{"id":"map_monsters_reduce_enemy_lightning_resistance_%","max":7,"min":7}]

```json
{"k":"MapSimulacrumExtraLightningAndPenetration2__","n":"MapSimulacrumExtraLightningAndPenetration2__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":79,"min":70},{"id":"map_monsters_reduce_enemy_lightning_resistance_%","max":7,"min":7}],"domain":"area","gen":"unique","lvl":1}
```

### 62. MapSimulacrumExtraLightningAndPenetration3

- Match score: `80`
- `k`: MapSimulacrumExtraLightningAndPenetration3
- `n`: MapSimulacrumExtraLightningAndPenetration3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":100,"min":80},{"id":"map_monsters_reduce_enemy_lightning_resistance_%","max":10,"min":10}]

```json
{"k":"MapSimulacrumExtraLightningAndPenetration3","n":"MapSimulacrumExtraLightningAndPenetration3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_%_physical_damage_to_gain_as_lightning","max":100,"min":80},{"id":"map_monsters_reduce_enemy_lightning_resistance_%","max":10,"min":10}],"domain":"area","gen":"unique","lvl":1}
```

### 63. MayhemEventDifficultyIncreasedMonsterCritical

- Match score: `80`
- `k`: MayhemEventDifficultyIncreasedMonsterCritical
- `n`: MayhemEventDifficultyIncreasedMonsterCritical
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":200},{"id":"map_monsters_critical_strike_multiplier_+","max":35,"min":35}]

```json
{"k":"MayhemEventDifficultyIncreasedMonsterCritical","n":"MayhemEventDifficultyIncreasedMonsterCritical","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":200},{"id":"map_monsters_critical_strike_multiplier_+","max":35,"min":35}],"domain":"area","gen":"unique","lvl":1}
```

### 64. PassageUniqueAmanamuAbyssalWastingPreventsCrits

- Match score: `80`
- `k`: PassageUniqueAmanamuAbyssalWastingPreventsCrits
- `n`: PassageUniqueAmanamuAbyssalWastingPreventsCrits
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"abyssal_wasting_also_prevents_enemies_from_dealing_critical_strikes","max":1,"min":1}]

```json
{"k":"PassageUniqueAmanamuAbyssalWastingPreventsCrits","n":"PassageUniqueAmanamuAbyssalWastingPreventsCrits","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"abyssal_wasting_also_prevents_enemies_from_dealing_critical_strikes","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 65. PassageUniqueAmanamuArmourAppliesToElementalDamage

- Match score: `80`
- `k`: PassageUniqueAmanamuArmourAppliesToElementalDamage
- `n`: PassageUniqueAmanamuArmourAppliesToElementalDamage
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"armour_%_applies_to_fire_cold_lightning_damage","max":30,"min":20}]

```json
{"k":"PassageUniqueAmanamuArmourAppliesToElementalDamage","n":"PassageUniqueAmanamuArmourAppliesToElementalDamage","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"armour_%_applies_to_fire_cold_lightning_damage","max":30,"min":20}],"domain":"item","gen":"unique","lvl":1}
```

### 66. PassageUniqueAmanamuHybridArmourAndArmourElemental

- Match score: `80`
- `k`: PassageUniqueAmanamuHybridArmourAndArmourElemental
- `n`: PassageUniqueAmanamuHybridArmourAndArmourElemental
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"physical_damage_reduction_rating_+%","max":40,"min":30},{"id":"armour_%_applies_to_fire_cold_lightning_damage","max":30,"min":20}]

```json
{"k":"PassageUniqueAmanamuHybridArmourAndArmourElemental","n":"PassageUniqueAmanamuHybridArmourAndArmourElemental","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"physical_damage_reduction_rating_+%","max":40,"min":30},{"id":"armour_%_applies_to_fire_cold_lightning_damage","max":30,"min":20}],"domain":"item","gen":"unique","lvl":1}
```

### 67. PercentManaRecoveredWhenYouShockUnique__1

- Match score: `80`
- `k`: PercentManaRecoveredWhenYouShockUnique__1
- `n`: PercentManaRecoveredWhenYouShockUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"recover_%_maximum_mana_when_enemy_shocked","max":3,"min":3}]

```json
{"k":"PercentManaRecoveredWhenYouShockUnique__1","n":"PercentManaRecoveredWhenYouShockUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"recover_%_maximum_mana_when_enemy_shocked","max":3,"min":3}],"domain":"item","gen":"unique","lvl":1}
```

### 68. ShockedEnemiesExplodeUnique__1_

- Match score: `80`
- `k`: ShockedEnemiesExplodeUnique__1_
- `n`: ShockedEnemiesExplodeUnique__1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"shocked_enemies_explode_for_%_life_as_lightning_damage","max":5,"min":5}]

```json
{"k":"ShockedEnemiesExplodeUnique__1_","n":"ShockedEnemiesExplodeUnique__1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"shocked_enemies_explode_for_%_life_as_lightning_damage","max":5,"min":5}],"domain":"item","gen":"unique","lvl":1}
```

### 69. UberSimulacrumCriticals1_

- Match score: `80`
- `k`: UberSimulacrumCriticals1_
- `n`: UberSimulacrumCriticals1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_monsters_critical_strike_chance_+%","max":330,"min":301},{"id":"map_monsters_critical_strike_multiplier_+","max":60,"min":50},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":35,"min":35}]

```json
{"k":"UberSimulacrumCriticals1_","n":"UberSimulacrumCriticals1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_monsters_critical_strike_chance_+%","max":330,"min":301},{"id":"map_monsters_critical_strike_multiplier_+","max":60,"min":50},{"id":"map_monsters_base_self_critical_strike_multiplier_-%","max":35,"min":35}],"domain":"area","gen":"unique","lvl":1}
```

### 70. UltimatumUniqueMapExtraCriticalRolls

- Match score: `80`
- `k`: UltimatumUniqueMapExtraCriticalRolls
- `n`: UltimatumUniqueMapExtraCriticalRolls
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: area
- `stats`: [{"id":"map_ultimatum_unique_map_boss_extra_critical_rolls","max":1,"min":1}]

```json
{"k":"UltimatumUniqueMapExtraCriticalRolls","n":"UltimatumUniqueMapExtraCriticalRolls","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_ultimatum_unique_map_boss_extra_critical_rolls","max":1,"min":1}],"domain":"area","gen":"unique","lvl":1}
```

### 71. UniqueCriticalStrikesIgnoreResistances1

- Match score: `80`
- `k`: UniqueCriticalStrikesIgnoreResistances1
- `n`: UniqueCriticalStrikesIgnoreResistances1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strikes_ignore_elemental_resistances","max":1,"min":1}]

```json
{"k":"UniqueCriticalStrikesIgnoreResistances1","n":"UniqueCriticalStrikesIgnoreResistances1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strikes_ignore_elemental_resistances","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 72. UniqueElementalAilmentDuration1

- Match score: `80`
- `k`: UniqueElementalAilmentDuration1
- `n`: UniqueElementalAilmentDuration1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"ignite_shock_chill_duration_+%","max":-30,"min":-40}]

```json
{"k":"UniqueElementalAilmentDuration1","n":"UniqueElementalAilmentDuration1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"ignite_shock_chill_duration_+%","max":-30,"min":-40}],"domain":"item","gen":"unique","lvl":1}
```

### 73. UniqueElementalDamageFromHitsContributesToCoreEleAilments1

- Match score: `80`
- `k`: UniqueElementalDamageFromHitsContributesToCoreEleAilments1
- `n`: UniqueElementalDamageFromHitsContributesToCoreEleAilments1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"elemental_damage_also_contributes_to_flammability_ignite_chill_freeze_and_shock","max":1,"min":1}]

```json
{"k":"UniqueElementalDamageFromHitsContributesToCoreEleAilments1","n":"UniqueElementalDamageFromHitsContributesToCoreEleAilments1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"elemental_damage_also_contributes_to_flammability_ignite_chill_freeze_and_shock","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 74. <<ExpedRuneArcane>><rgb(219,217,206)>{Arcane Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Energy Shield}
<rgb(135,134,253)>{Trigger a Stunning nova when Energy Shield is depleted}

- Match score: `70`
- `k`: ExpeditionMonsterModRuneArcane
- `n`: <<ExpedRuneArcane>><rgb(219,217,206)>{Arcane Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Energy Shield}
<rgb(135,134,253)>{Trigger a Stunning nova when Energy Shield is depleted}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"base_maximum_life_%_to_gain_as_total_energy_shield","max":30,"min":30}]

```json
{"k":"ExpeditionMonsterModRuneArcane","n":"<<ExpedRuneArcane>><rgb(219,217,206)>{Arcane Rune}\r\n<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}\r\n<rgb(135,134,253)>{Extra Energy Shield}\r\n<rgb(135,134,253)>{Trigger a Stunning nova when Energy Shield is depleted}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_maximum_life_%_to_gain_as_total_energy_shield","max":30,"min":30}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 75. <<ExpedRuneArcane>><rgb(219,217,206)>{Arcane Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Energy Shield}
<rgb(135,134,253)>{Trigger a Stunning nova when Energy Shield is depleted}

- Match score: `70`
- `k`: ExpeditionMonsterModRuneArcanePower
- `n`: <<ExpedRuneArcane>><rgb(219,217,206)>{Arcane Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Extra Energy Shield}
<rgb(135,134,253)>{Trigger a Stunning nova when Energy Shield is depleted}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"base_maximum_life_%_to_gain_as_total_energy_shield","max":60,"min":60}]

```json
{"k":"ExpeditionMonsterModRuneArcanePower","n":"<<ExpedRuneArcane>><rgb(219,217,206)>{Arcane Rune}\r\n<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}\r\n<rgb(135,134,253)>{Extra Energy Shield}\r\n<rgb(135,134,253)>{Trigger a Stunning nova when Energy Shield is depleted}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_maximum_life_%_to_gain_as_total_energy_shield","max":60,"min":60}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 76. <<ExpedRunePrismatic>><rgb(219,217,206)>{Prismatic Rune}
<rgb(135,134,253)>{All Damage can Shock}
<rgb(135,134,253)>{All Damage can Chill}
<rgb(135,134,253)>{All Damage can Ignite}
<rgb(135,134,253)>{All Elemental Resistance}

- Match score: `70`
- `k`: ExpeditionMonsterModRunePrismatic
- `n`: <<ExpedRunePrismatic>><rgb(219,217,206)>{Prismatic Rune}
<rgb(135,134,253)>{All Damage can Shock}
<rgb(135,134,253)>{All Damage can Chill}
<rgb(135,134,253)>{All Damage can Ignite}
<rgb(135,134,253)>{All Elemental Resistance}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"base_resist_all_elements_%","max":15,"min":15},{"id":"non_skill_base_all_damage_%_to_gain_as_random_element","max":0,"min":0},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_ignite","max":1,"min":1}]

```json
{"k":"ExpeditionMonsterModRunePrismatic","n":"<<ExpedRunePrismatic>><rgb(219,217,206)>{Prismatic Rune}\r\n<rgb(135,134,253)>{All Damage can Shock}\r\n<rgb(135,134,253)>{All Damage can Chill}\r\n<rgb(135,134,253)>{All Damage can Ignite}\r\n<rgb(135,134,253)>{All Elemental Resistance}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_resist_all_elements_%","max":15,"min":15},{"id":"non_skill_base_all_damage_%_to_gain_as_random_element","max":0,"min":0},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_ignite","max":1,"min":1}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 77. <<ExpedRunePrismatic>><rgb(219,217,206)>{Prismatic Rune}
<rgb(135,134,253)>{All Damage can Shock}
<rgb(135,134,253)>{All Damage can Chill}
<rgb(135,134,253)>{All Damage can Ignite}
<rgb(135,134,253)>{All Elemental Resistance}
<rgb(135,134,253)>{Damage gained as a Random Element}

- Match score: `70`
- `k`: ExpeditionMonsterModRunePrismaticPower
- `n`: <<ExpedRunePrismatic>><rgb(219,217,206)>{Prismatic Rune}
<rgb(135,134,253)>{All Damage can Shock}
<rgb(135,134,253)>{All Damage can Chill}
<rgb(135,134,253)>{All Damage can Ignite}
<rgb(135,134,253)>{All Elemental Resistance}
<rgb(135,134,253)>{Damage gained as a Random Element}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"base_resist_all_elements_%","max":30,"min":30},{"id":"non_skill_base_all_damage_%_to_gain_as_random_element","max":20,"min":20},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_ignite","max":1,"min":1}]

```json
{"k":"ExpeditionMonsterModRunePrismaticPower","n":"<<ExpedRunePrismatic>><rgb(219,217,206)>{Prismatic Rune}\r\n<rgb(135,134,253)>{All Damage can Shock}\r\n<rgb(135,134,253)>{All Damage can Chill}\r\n<rgb(135,134,253)>{All Damage can Ignite}\r\n<rgb(135,134,253)>{All Elemental Resistance}\r\n<rgb(135,134,253)>{Damage gained as a Random Element}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_resist_all_elements_%","max":30,"min":30},{"id":"non_skill_base_all_damage_%_to_gain_as_random_element","max":20,"min":20},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_ignite","max":1,"min":1}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 78. <<ExpedRuneTempest>><rgb(219,217,206)>{Tempest Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Cannot be Shocked or Chilled}
<rgb(135,134,253)>{All Damage can Shock and Chill}

- Match score: `70`
- `k`: ExpeditionMonsterModRuneTempest
- `n`: <<ExpedRuneTempest>><rgb(219,217,206)>{Tempest Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Cannot be Shocked or Chilled}
<rgb(135,134,253)>{All Damage can Shock and Chill}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"base_cannot_be_shocked","max":0,"min":0},{"id":"base_cannot_be_chilled","max":0,"min":0},{"id":"base_avoid_shock_%","max":60,"min":60},{"id":"base_avoid_chill_%","max":60,"min":60}]

```json
{"k":"ExpeditionMonsterModRuneTempest","n":"<<ExpedRuneTempest>><rgb(219,217,206)>{Tempest Rune}\r\n<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}\r\n<rgb(135,134,253)>{Cannot be Shocked or Chilled}\r\n<rgb(135,134,253)>{All Damage can Shock and Chill}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"base_cannot_be_shocked","max":0,"min":0},{"id":"base_cannot_be_chilled","max":0,"min":0},{"id":"base_avoid_shock_%","max":60,"min":60},{"id":"base_avoid_chill_%","max":60,"min":60}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 79. <<ExpedRuneTempest>><rgb(219,217,206)>{Tempest Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Cannot be Shocked or Chilled}
<rgb(135,134,253)>{All Damage can Shock and Chill}

- Match score: `70`
- `k`: ExpeditionMonsterModRuneTempestPower
- `n`: <<ExpedRuneTempest>><rgb(219,217,206)>{Tempest Rune}
<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}
<rgb(135,134,253)>{Cannot be Shocked or Chilled}
<rgb(135,134,253)>{All Damage can Shock and Chill}
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"base_cannot_be_shocked","max":1,"min":1},{"id":"base_cannot_be_chilled","max":1,"min":1},{"id":"base_avoid_shock_%","max":60,"min":60},{"id":"base_avoid_chill_%","max":60,"min":60}]

```json
{"k":"ExpeditionMonsterModRuneTempestPower","n":"<<ExpedRuneTempest>><rgb(219,217,206)>{Tempest Rune}\r\n<font:'fontin'>{<italic>{<rgb(110,87,66)>{Monsters gain:}}}\r\n<rgb(135,134,253)>{Cannot be Shocked or Chilled}\r\n<rgb(135,134,253)>{All Damage can Shock and Chill}","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"all_damage_can_shock","max":1,"min":1},{"id":"all_damage_can_chill","max":1,"min":1},{"id":"base_cannot_be_shocked","max":1,"min":1},{"id":"base_cannot_be_chilled","max":1,"min":1},{"id":"base_avoid_shock_%","max":60,"min":60},{"id":"base_avoid_chill_%","max":60,"min":60}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 80. AdditionalCriticalStrikeChancePerPowerChargeUnique__1

- Match score: `70`
- `k`: AdditionalCriticalStrikeChancePerPowerChargeUnique__1
- `n`: AdditionalCriticalStrikeChancePerPowerChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"additional_critical_strike_chance_per_power_charge_permyriad","max":30,"min":30}]

```json
{"k":"AdditionalCriticalStrikeChancePerPowerChargeUnique__1","n":"AdditionalCriticalStrikeChancePerPowerChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"additional_critical_strike_chance_per_power_charge_permyriad","max":30,"min":30}],"domain":"item","gen":"unique","lvl":1}
```

### 81. AdditionalMeleeDamageToShockedEnemiesUniqueDagger6

- Match score: `70`
- `k`: AdditionalMeleeDamageToShockedEnemiesUniqueDagger6
- `n`: AdditionalMeleeDamageToShockedEnemiesUniqueDagger6
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"melee_damage_+%_vs_shocked_enemies","max":100,"min":100}]

```json
{"k":"AdditionalMeleeDamageToShockedEnemiesUniqueDagger6","n":"AdditionalMeleeDamageToShockedEnemiesUniqueDagger6","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"melee_damage_+%_vs_shocked_enemies","max":100,"min":100}],"domain":"item","gen":"unique","lvl":1}
```

### 82. AlloyElementalPenetration1

- Match score: `70`
- `k`: AlloyElementalPenetration1
- `n`: AlloyElementalPenetration1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AlloyElementalPenetration1","n":"AlloyElementalPenetration1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":45}
```

### 83. AttackCriticalStrikeChance1

- Match score: `70`
- `k`: AttackCriticalStrikeChance1
- `n`: AttackCriticalStrikeChance1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance1","n":"AttackCriticalStrikeChance1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":5}
```

### 84. AttackCriticalStrikeChance2

- Match score: `70`
- `k`: AttackCriticalStrikeChance2
- `n`: AttackCriticalStrikeChance2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance2","n":"AttackCriticalStrikeChance2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":20}
```

### 85. AttackCriticalStrikeChance3

- Match score: `70`
- `k`: AttackCriticalStrikeChance3
- `n`: AttackCriticalStrikeChance3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance3","n":"AttackCriticalStrikeChance3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":30}
```

### 86. AttackCriticalStrikeChance4

- Match score: `70`
- `k`: AttackCriticalStrikeChance4
- `n`: AttackCriticalStrikeChance4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance4","n":"AttackCriticalStrikeChance4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":44}
```

### 87. AttackCriticalStrikeChance5

- Match score: `70`
- `k`: AttackCriticalStrikeChance5
- `n`: AttackCriticalStrikeChance5
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance5","n":"AttackCriticalStrikeChance5","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":58}
```

### 88. AttackCriticalStrikeChance6

- Match score: `70`
- `k`: AttackCriticalStrikeChance6
- `n`: AttackCriticalStrikeChance6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance6","n":"AttackCriticalStrikeChance6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":72}
```

### 89. AttackCriticalStrikeMultiplier1

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier1
- `n`: AttackCriticalStrikeMultiplier1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier1","n":"AttackCriticalStrikeMultiplier1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":8}
```

### 90. AttackCriticalStrikeMultiplier2

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier2
- `n`: AttackCriticalStrikeMultiplier2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier2","n":"AttackCriticalStrikeMultiplier2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":21}
```

### 91. AttackCriticalStrikeMultiplier3

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier3
- `n`: AttackCriticalStrikeMultiplier3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier3","n":"AttackCriticalStrikeMultiplier3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":31}
```

### 92. AttackCriticalStrikeMultiplier4

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier4
- `n`: AttackCriticalStrikeMultiplier4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier4","n":"AttackCriticalStrikeMultiplier4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":45}
```

### 93. AttackCriticalStrikeMultiplier5

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier5
- `n`: AttackCriticalStrikeMultiplier5
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier5","n":"AttackCriticalStrikeMultiplier5","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":59}
```

### 94. AttackCriticalStrikeMultiplier6

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier6
- `n`: AttackCriticalStrikeMultiplier6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier6","n":"AttackCriticalStrikeMultiplier6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":74}
```

### 95. AvoidElementalAilmentsPerStackableJewelUnique__1

- Match score: `70`
- `k`: AvoidElementalAilmentsPerStackableJewelUnique__1
- `n`: AvoidElementalAilmentsPerStackableJewelUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: misc
- `stats`: [{"id":"avoid_all_elemental_status_%_per_stackable_unique_jewel","max":12,"min":12},{"id":"number_of_stackable_unique_jewels","max":1,"min":1}]

```json
{"k":"AvoidElementalAilmentsPerStackableJewelUnique__1","n":"AvoidElementalAilmentsPerStackableJewelUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"avoid_all_elemental_status_%_per_stackable_unique_jewel","max":12,"min":12},{"id":"number_of_stackable_unique_jewels","max":1,"min":1}],"domain":"misc","gen":"unique","lvl":1}
```

### 96. AvoidElementalAilmentsUnique__1_

- Match score: `70`
- `k`: AvoidElementalAilmentsUnique__1_
- `n`: AvoidElementalAilmentsUnique__1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"avoid_all_elemental_status_%","max":30,"min":30}]

```json
{"k":"AvoidElementalAilmentsUnique__1_","n":"AvoidElementalAilmentsUnique__1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"avoid_all_elemental_status_%","max":30,"min":30}],"domain":"item","gen":"unique","lvl":1}
```

### 97. AvoidElementalAilmentsUnique__2

- Match score: `70`
- `k`: AvoidElementalAilmentsUnique__2
- `n`: AvoidElementalAilmentsUnique__2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"avoid_all_elemental_status_%","max":25,"min":20}]

```json
{"k":"AvoidElementalAilmentsUnique__2","n":"AvoidElementalAilmentsUnique__2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"avoid_all_elemental_status_%","max":25,"min":20}],"domain":"item","gen":"unique","lvl":1}
```

### 98. BaseUnarmedCriticalStrikeChanceUnique__1

- Match score: `70`
- `k`: BaseUnarmedCriticalStrikeChanceUnique__1
- `n`: BaseUnarmedCriticalStrikeChanceUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"base_melee_critical_strike_chance_while_unarmed_%","max":700,"min":700}]

```json
{"k":"BaseUnarmedCriticalStrikeChanceUnique__1","n":"BaseUnarmedCriticalStrikeChanceUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_melee_critical_strike_chance_while_unarmed_%","max":700,"min":700}],"domain":"item","gen":"unique","lvl":1}
```

### 99. BaseUnarmedCriticalStrikeChanceUnique__2

- Match score: `70`
- `k`: BaseUnarmedCriticalStrikeChanceUnique__2
- `n`: BaseUnarmedCriticalStrikeChanceUnique__2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"base_melee_critical_strike_chance_while_unarmed_%","max":110,"min":10}]

```json
{"k":"BaseUnarmedCriticalStrikeChanceUnique__2","n":"BaseUnarmedCriticalStrikeChanceUnique__2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_melee_critical_strike_chance_while_unarmed_%","max":110,"min":10}],"domain":"item","gen":"unique","lvl":1}
```

### 100. BerserkInfluenceWarcryArea1

- Match score: `70`
- `k`: BerserkInfluenceWarcryArea1
- `n`: BerserkInfluenceWarcryArea1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BerserkInfluenceWarcryArea1","n":"BerserkInfluenceWarcryArea1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":45}
```

### 101. BerserkInfluenceWarcryArea2

- Match score: `70`
- `k`: BerserkInfluenceWarcryArea2
- `n`: BerserkInfluenceWarcryArea2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BerserkInfluenceWarcryArea2","n":"BerserkInfluenceWarcryArea2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":75}
```

### 102. BetrayalUpgradeMonsterCriticalStrikeChanceAndAccuracy

- Match score: `70`
- `k`: BetrayalUpgradeMonsterCriticalStrikeChanceAndAccuracy
- `n`: BetrayalUpgradeMonsterCriticalStrikeChanceAndAccuracy
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"critical_strike_chance_+%","max":300,"min":300},{"id":"base_critical_strike_multiplier_+","max":25,"min":25},{"id":"accuracy_rating_+%","max":40,"min":40}]

```json
{"k":"BetrayalUpgradeMonsterCriticalStrikeChanceAndAccuracy","n":"BetrayalUpgradeMonsterCriticalStrikeChanceAndAccuracy","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_chance_+%","max":300,"min":300},{"id":"base_critical_strike_multiplier_+","max":25,"min":25},{"id":"accuracy_rating_+%","max":40,"min":40}],"domain":"monster","gen":"unique","lvl":1}
```

### 103. BetrayalUpgradeMonsterLightningDamageAndShock_

- Match score: `70`
- `k`: BetrayalUpgradeMonsterLightningDamageAndShock_
- `n`: BetrayalUpgradeMonsterLightningDamageAndShock_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"non_skill_base_physical_damage_%_to_gain_as_lightning","max":50,"min":50},{"id":"all_damage_can_shock","max":1,"min":1},{"id":"base_chance_to_shock_%","max":100,"min":100}]

```json
{"k":"BetrayalUpgradeMonsterLightningDamageAndShock_","n":"BetrayalUpgradeMonsterLightningDamageAndShock_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_base_physical_damage_%_to_gain_as_lightning","max":50,"min":50},{"id":"all_damage_can_shock","max":1,"min":1},{"id":"base_chance_to_shock_%","max":100,"min":100}],"domain":"monster","gen":"unique","lvl":1}
```

### 104. BleedOnMeleeCriticalStrikeUnique__1

- Match score: `70`
- `k`: BleedOnMeleeCriticalStrikeUnique__1
- `n`: BleedOnMeleeCriticalStrikeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_chance_to_bleed_on_crit_50%","max":1,"min":1}]

```json
{"k":"BleedOnMeleeCriticalStrikeUnique__1","n":"BleedOnMeleeCriticalStrikeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_chance_to_bleed_on_crit_50%","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 105. BodyArmourImplicitReducedCriticalStrikeDamageTaken1

- Match score: `70`
- `k`: BodyArmourImplicitReducedCriticalStrikeDamageTaken1
- `n`: BodyArmourImplicitReducedCriticalStrikeDamageTaken1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"base_self_critical_strike_multiplier_-%","max":25,"min":15}]

```json
{"k":"BodyArmourImplicitReducedCriticalStrikeDamageTaken1","n":"BodyArmourImplicitReducedCriticalStrikeDamageTaken1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_self_critical_strike_multiplier_-%","max":25,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 106. CannotBeShocked

- Match score: `70`
- `k`: CannotBeShocked
- `n`: CannotBeShocked
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"base_cannot_be_shocked","max":100,"min":100}]

```json
{"k":"CannotBeShocked","n":"CannotBeShocked","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_cannot_be_shocked","max":100,"min":100}],"domain":"item","gen":"unique","lvl":1}
```

### 107. CannotBeShockedWhileFrozenUniqueStaff14

- Match score: `70`
- `k`: CannotBeShockedWhileFrozenUniqueStaff14
- `n`: CannotBeShockedWhileFrozenUniqueStaff14
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cannot_be_shocked_while_frozen","max":1,"min":1}]

```json
{"k":"CannotBeShockedWhileFrozenUniqueStaff14","n":"CannotBeShockedWhileFrozenUniqueStaff14","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cannot_be_shocked_while_frozen","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 108. CannotBeShockedWhileMaximumEnduranceChargesUnique_1

- Match score: `70`
- `k`: CannotBeShockedWhileMaximumEnduranceChargesUnique_1
- `n`: CannotBeShockedWhileMaximumEnduranceChargesUnique_1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cannot_be_shocked_while_at_maximum_endurance_charges","max":1,"min":1}]

```json
{"k":"CannotBeShockedWhileMaximumEnduranceChargesUnique_1","n":"CannotBeShockedWhileMaximumEnduranceChargesUnique_1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cannot_be_shocked_while_at_maximum_endurance_charges","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 109. CannotBeShockedWithIntHigherThanStrUnique__1

- Match score: `70`
- `k`: CannotBeShockedWithIntHigherThanStrUnique__1
- `n`: CannotBeShockedWithIntHigherThanStrUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cannot_be_shocked_with_int_higher_than_strength","max":1,"min":1}]

```json
{"k":"CannotBeShockedWithIntHigherThanStrUnique__1","n":"CannotBeShockedWithIntHigherThanStrUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cannot_be_shocked_with_int_higher_than_strength","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 110. CannotLeechFromCriticalStrikesUnique___1

- Match score: `70`
- `k`: CannotLeechFromCriticalStrikesUnique___1
- `n`: CannotLeechFromCriticalStrikesUnique___1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cannot_leech_life_from_critical_strikes","max":1,"min":1}]

```json
{"k":"CannotLeechFromCriticalStrikesUnique___1","n":"CannotLeechFromCriticalStrikesUnique___1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cannot_leech_life_from_critical_strikes","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 111. CastSocketedColdSkillsOnCriticalStrikeUnique__1

- Match score: `70`
- `k`: CastSocketedColdSkillsOnCriticalStrikeUnique__1
- `n`: CastSocketedColdSkillsOnCriticalStrikeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_unique_cast_socketed_cold_skills_on_melee_critical_strike","max":1,"min":1}]

```json
{"k":"CastSocketedColdSkillsOnCriticalStrikeUnique__1","n":"CastSocketedColdSkillsOnCriticalStrikeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_unique_cast_socketed_cold_skills_on_melee_critical_strike","max":1,"min":1}],"domain":"item","gen":"unique","adds_tags":["caster_unique_weapon"],"lvl":1}
```

### 112. CastSocketedSpellsOnShockedEnemyKillUnique__1

- Match score: `70`
- `k`: CastSocketedSpellsOnShockedEnemyKillUnique__1
- `n`: CastSocketedSpellsOnShockedEnemyKillUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cast_linked_spells_on_shocked_enemy_kill_%","max":50,"min":50}]

```json
{"k":"CastSocketedSpellsOnShockedEnemyKillUnique__1","n":"CastSocketedSpellsOnShockedEnemyKillUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cast_linked_spells_on_shocked_enemy_kill_%","max":50,"min":50}],"domain":"item","gen":"unique","lvl":1}
```

### 113. ChanceToAvoidElementalStatusAilments1

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilments1
- `n`: ChanceToAvoidElementalStatusAilments1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilments1","n":"ChanceToAvoidElementalStatusAilments1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":23}
```

### 114. ChanceToAvoidElementalStatusAilments2

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilments2
- `n`: ChanceToAvoidElementalStatusAilments2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilments2","n":"ChanceToAvoidElementalStatusAilments2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":41}
```

### 115. ChanceToAvoidElementalStatusAilments3__

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilments3__
- `n`: ChanceToAvoidElementalStatusAilments3__
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilments3__","n":"ChanceToAvoidElementalStatusAilments3__","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":57}
```

### 116. ChanceToAvoidElementalStatusAilments4

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilments4
- `n`: ChanceToAvoidElementalStatusAilments4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilments4","n":"ChanceToAvoidElementalStatusAilments4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":73}
```

### 117. ChanceToAvoidElementalStatusAilmentsEssence1

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilmentsEssence1
- `n`: ChanceToAvoidElementalStatusAilmentsEssence1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilmentsEssence1","n":"ChanceToAvoidElementalStatusAilmentsEssence1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":42}
```

### 118. ChanceToAvoidElementalStatusAilmentsEssence2

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilmentsEssence2
- `n`: ChanceToAvoidElementalStatusAilmentsEssence2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilmentsEssence2","n":"ChanceToAvoidElementalStatusAilmentsEssence2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":58}
```

### 119. ChanceToAvoidElementalStatusAilmentsEssence3

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilmentsEssence3
- `n`: ChanceToAvoidElementalStatusAilmentsEssence3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilmentsEssence3","n":"ChanceToAvoidElementalStatusAilmentsEssence3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":74}
```

### 120. ChanceToAvoidElementalStatusAilmentsEssence4

- Match score: `70`
- `k`: ChanceToAvoidElementalStatusAilmentsEssence4
- `n`: ChanceToAvoidElementalStatusAilmentsEssence4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"ChanceToAvoidElementalStatusAilmentsEssence4","n":"ChanceToAvoidElementalStatusAilmentsEssence4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":82}
```

## Rune mods

- Source: `build_knowledge/compact/rune_mod_index.json`
- Matches included: `8`

### 1. Amanamu's Gaze

- Match score: `35`
- `k`: Amanamu's Gaze
- `n`: Amanamu's Gaze
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Amanamu's Gaze","n":"Amanamu's Gaze","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 2. Countess Seske's Rune of Archery

- Match score: `35`
- `k`: Countess Seske's Rune of Archery
- `n`: Countess Seske's Rune of Archery
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Countess Seske's Rune of Archery","n":"Countess Seske's Rune of Archery","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 3. Greater Rune of Alacrity

- Match score: `35`
- `k`: Greater Rune of Alacrity
- `n`: Greater Rune of Alacrity
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Greater Rune of Alacrity","n":"Greater Rune of Alacrity","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 4. Greater Storm Rune

- Match score: `35`
- `k`: Greater Storm Rune
- `n`: Greater Storm Rune
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Greater Storm Rune","n":"Greater Storm Rune","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 5. Legacy of Keeper of the Arc

- Match score: `35`
- `k`: Legacy of Keeper of the Arc
- `n`: Legacy of Keeper of the Arc
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Legacy of Keeper of the Arc","n":"Legacy of Keeper of the Arc","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 6. Lesser Storm Rune

- Match score: `35`
- `k`: Lesser Storm Rune
- `n`: Lesser Storm Rune
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Lesser Storm Rune","n":"Lesser Storm Rune","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 7. Perfect Storm Rune

- Match score: `35`
- `k`: Perfect Storm Rune
- `n`: Perfect Storm Rune
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Perfect Storm Rune","n":"Perfect Storm Rune","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

### 8. Storm Rune

- Match score: `35`
- `k`: Storm Rune
- `n`: Storm Rune
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Storm Rune","n":"Storm Rune","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

## Uniques

- Source: `build_knowledge/compact/unique_index.json`
- Matches included: `9`

### 1. Calgyra's Arc

- Match score: `35`
- `id`: Calgyra's Arc
- `k`: 324
- `n`: Calgyra's Arc
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"324","n":"Calgyra's Arc","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Calgyra's Arc","item_class":"Shield"}
```

### 2. Choir of the Storm

- Match score: `35`
- `id`: Choir of the Storm
- `k`: 256
- `n`: Choir of the Storm
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"256","n":"Choir of the Storm","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Choir of the Storm","item_class":"Amulet"}
```

### 3. Ghostmarch

- Match score: `35`
- `id`: Ghostmarch
- `k`: 117
- `n`: Ghostmarch
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"117","n":"Ghostmarch","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Ghostmarch","item_class":"Boots"}
```

### 4. Keeper of the Arc

- Match score: `35`
- `id`: Keeper of the Arc
- `k`: 241
- `n`: Keeper of the Arc
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"241","n":"Keeper of the Arc","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Keeper of the Arc","item_class":"Helmet"}
```

### 5. Lightning Coil

- Match score: `35`
- `id`: Lightning Coil
- `k`: 376
- `n`: Lightning Coil
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"376","n":"Lightning Coil","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Lightning Coil","item_class":"Body Armour"}
```

### 6. Sandstorm Visage

- Match score: `35`
- `id`: Sandstorm Visage
- `k`: 231
- `n`: Sandstorm Visage
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"231","n":"Sandstorm Visage","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Sandstorm Visage","item_class":"Helmet"}
```

### 7. The Eternal Spark

- Match score: `35`
- `id`: The Eternal Spark
- `k`: 137
- `n`: The Eternal Spark
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"137","n":"The Eternal Spark","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"The Eternal Spark","item_class":"Focii"}
```

### 8. The Prisoner's Manacles

- Match score: `35`
- `id`: The Prisoner's Manacles
- `k`: 307
- `n`: The Prisoner's Manacles
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"307","n":"The Prisoner's Manacles","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"The Prisoner's Manacles","item_class":"Gloves"}
```

### 9. Zaida's Longevity

- Match score: `10`
- `id`: Sekhema's Resolve Lightning
- `k`: 235
- `n`: Zaida's Longevity
- `cat`: repoe_uniques
- `src`: repoe_poe2/uniques.json

```json
{"k":"235","n":"Zaida's Longevity","cat":"repoe_uniques","src":"repoe_poe2/uniques.json","id":"Sekhema's Resolve Lightning","item_class":"Ring"}
```

## Misc

- Source: `build_knowledge/compact/misc_index.json`
- Matches included: `120`

### 1. 100% of Physical Damage Converted to Cold Damage while Sphere has no Ailments
100% of Physical Damage Converted to Lightning Damage while sphere is Shocked or Sapped
100% of Physical Damage Converted to Cold Damage while Sphere is Frozen or Brittle

- Match score: `140`
- `k`: 100% of Physical Damage Converted to Cold Damage while Sphere has no Ailments
100% of Physical Damage Converted to Lightning Damage while sphere is Shocked or Sapped
100% of Physical Damage Converted to Cold Damage while Sphere is Frozen or Brittle
- `n`: 100% of Physical Damage Converted to Cold Damage while Sphere has no Ailments
100% of Physical Damage Converted to Lightning Damage while sphere is Shocked or Sapped
100% of Physical Damage Converted to Cold Damage while Sphere is Frozen or Brittle
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"100% of Physical Damage Converted to Cold Damage while Sphere has no Ailments\n100% of Physical Damage Converted to Lightning Damage while sphere is Shocked or Sapped\n100% of Physical Damage Converted to Cold Damage while Sphere is Frozen or Brittle","n":"100% of Physical Damage Converted to Cold Damage while Sphere has no Ailments\n100% of Physical Damage Converted to Lightning Damage while sphere is Shocked or Sapped\n100% of Physical Damage Converted to Cold Damage while Sphere is Frozen or Brittle","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 2. [Projectile] [Chain|Chains] an additional time on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]

- Match score: `140`
- `k`: [Projectile] [Chain|Chains] an additional time on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]
- `n`: [Projectile] [Chain|Chains] an additional time on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile] [Chain|Chains] an additional time on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]","n":"[Projectile] [Chain|Chains] an additional time on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 3. [Projectile] [Chain|Chains] {0} additional times on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]

- Match score: `140`
- `k`: [Projectile] [Chain|Chains] {0} additional times on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]
- `n`: [Projectile] [Chain|Chains] {0} additional times on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile] [Chain|Chains] {0} additional times on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]","n":"[Projectile] [Chain|Chains] {0} additional times on first hitting a [Shock|Shocked] or [Electrocute|Electrocuted] enemy, releasing a Shockwave on each [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 4. Always [Critical|Critical Hit] Shocked Enemies

- Match score: `140`
- `k`: Always [Critical|Critical Hit] Shocked Enemies
- `n`: Always [Critical|Critical Hit] Shocked Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Always [Critical|Critical Hit] Shocked Enemies","n":"Always [Critical|Critical Hit] Shocked Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 5. Inflict Lightning [Exposure|Exposure] on [Critical|Critical Hit]

- Match score: `140`
- `k`: Inflict Lightning [Exposure|Exposure] on [Critical|Critical Hit]
- `n`: Inflict Lightning [Exposure|Exposure] on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Inflict Lightning [Exposure|Exposure] on [Critical|Critical Hit]","n":"Inflict Lightning [Exposure|Exposure] on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 6. Modifiers to Chance to Avoid being Shocked apply to all Elemental Ailments

- Match score: `140`
- `k`: Modifiers to Chance to Avoid being Shocked apply to all Elemental Ailments
- `n`: Modifiers to Chance to Avoid being Shocked apply to all Elemental Ailments
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Modifiers to Chance to Avoid being Shocked apply to all Elemental Ailments","n":"Modifiers to Chance to Avoid being Shocked apply to all Elemental Ailments","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 7. Spawn a [Remnant] on [Critical|Critically Hitting] a target affected by an [ElementalAilments|Elemental Ailment], no more than once every {0} seconds

- Match score: `140`
- `k`: Spawn a [Remnant] on [Critical|Critically Hitting] a target affected by an [ElementalAilments|Elemental Ailment], no more than once every {0} seconds
- `n`: Spawn a [Remnant] on [Critical|Critically Hitting] a target affected by an [ElementalAilments|Elemental Ailment], no more than once every {0} seconds
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Spawn a [Remnant] on [Critical|Critically Hitting] a target affected by an [ElementalAilments|Elemental Ailment], no more than once every {0} seconds","n":"Spawn a [Remnant] on [Critical|Critically Hitting] a target affected by an [ElementalAilments|Elemental Ailment], no more than once every {0} seconds","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 8. Spawn a [Remnant] on [Critical|Critically Hitting] target affected by an [ElementalAilments|Elemental Ailment], no more than once per second

- Match score: `140`
- `k`: Spawn a [Remnant] on [Critical|Critically Hitting] target affected by an [ElementalAilments|Elemental Ailment], no more than once per second
- `n`: Spawn a [Remnant] on [Critical|Critically Hitting] target affected by an [ElementalAilments|Elemental Ailment], no more than once per second
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Spawn a [Remnant] on [Critical|Critically Hitting] target affected by an [ElementalAilments|Elemental Ailment], no more than once per second","n":"Spawn a [Remnant] on [Critical|Critically Hitting] target affected by an [ElementalAilments|Elemental Ailment], no more than once per second","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 9. Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metre

- Match score: `140`
- `k`: Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metre
- `n`: Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metre
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metre","n":"Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metre","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 10. Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metres

- Match score: `140`
- `k`: Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metres
- `n`: Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metres
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metres","n":"Supported Skills create [ShockedGround|Shocked Ground] for {0} second when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metres","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 11. Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metre

- Match score: `140`
- `k`: Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metre
- `n`: Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metre
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metre","n":"Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metre","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 12. Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metres

- Match score: `140`
- `k`: Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metres
- `n`: Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use
[ShockedGround|Shocked Ground] created this way has a radius of {1} metres
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metres","n":"Supported Skills create [ShockedGround|Shocked Ground] for {0} seconds when they [Critical|Critically Hit], no more than once per Skill use\n[ShockedGround|Shocked Ground] created this way has a radius of {1} metres","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 13. Trigger Elemental Storm on [Critical|Critical Hit] with [Spell|Spells]

- Match score: `140`
- `k`: Trigger Elemental Storm on [Critical|Critical Hit] with [Spell|Spells]
- `n`: Trigger Elemental Storm on [Critical|Critical Hit] with [Spell|Spells]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Trigger Elemental Storm on [Critical|Critical Hit] with [Spell|Spells]","n":"Trigger Elemental Storm on [Critical|Critical Hit] with [Spell|Spells]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 14. You cannot deal [Critical|Critical Hits] against non-Shocked Enemies

- Match score: `140`
- `k`: You cannot deal [Critical|Critical Hits] against non-Shocked Enemies
- `n`: You cannot deal [Critical|Critical Hits] against non-Shocked Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"You cannot deal [Critical|Critical Hits] against non-Shocked Enemies","n":"You cannot deal [Critical|Critical Hits] against non-Shocked Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 15. Your [Critical|Critical Hits] Knock Back Shocked Enemies

- Match score: `140`
- `k`: Your [Critical|Critical Hits] Knock Back Shocked Enemies
- `n`: Your [Critical|Critical Hits] Knock Back Shocked Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Your [Critical|Critical Hits] Knock Back Shocked Enemies","n":"Your [Critical|Critical Hits] Knock Back Shocked Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 16. {0}% increased [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]

- Match score: `140`
- `k`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]
- `n`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]","n":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 17. {0}% increased [Critical|Critical Hit Chance] against Enemies that are affected
by no Elemental [Ailments]

- Match score: `140`
- `k`: {0}% increased [Critical|Critical Hit Chance] against Enemies that are affected
by no Elemental [Ailments]
- `n`: {0}% increased [Critical|Critical Hit Chance] against Enemies that are affected
by no Elemental [Ailments]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [Critical|Critical Hit Chance] against Enemies that are affected\nby no Elemental [Ailments]","n":"{0}% increased [Critical|Critical Hit Chance] against Enemies that are affected\nby no Elemental [Ailments]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 18. {0}% increased [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies

- Match score: `140`
- `k`: {0}% increased [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies
- `n`: {0}% increased [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies","n":"{0}% increased [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 19. {0}% increased [Critical|Critical Hit] Chance against Enemies affected
by Elemental Ailments

- Match score: `140`
- `k`: {0}% increased [Critical|Critical Hit] Chance against Enemies affected
by Elemental Ailments
- `n`: {0}% increased [Critical|Critical Hit] Chance against Enemies affected
by Elemental Ailments
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [Critical|Critical Hit] Chance against Enemies affected\nby Elemental Ailments","n":"{0}% increased [Critical|Critical Hit] Chance against Enemies affected\nby Elemental Ailments","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 20. {0}% increased [Critical|Critical Hit] Chance against Shocked Enemies

- Match score: `140`
- `k`: {0}% increased [Critical|Critical Hit] Chance against Shocked Enemies
- `n`: {0}% increased [Critical|Critical Hit] Chance against Shocked Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [Critical|Critical Hit] Chance against Shocked Enemies","n":"{0}% increased [Critical|Critical Hit] Chance against Shocked Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 21. {0}% increased [Critical|Critical Hit] Chance if you've been Shocked [Recently]

- Match score: `140`
- `k`: {0}% increased [Critical|Critical Hit] Chance if you've been Shocked [Recently]
- `n`: {0}% increased [Critical|Critical Hit] Chance if you've been Shocked [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [Critical|Critical Hit] Chance if you've been Shocked [Recently]","n":"{0}% increased [Critical|Critical Hit] Chance if you've been Shocked [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 22. {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]

- Match score: `140`
- `k`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]
- `n`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]","n":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] while [Shock|Shocked]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 23. {0}% reduced [Critical|Critical Hit Chance] against Enemies that are affected
by no Elemental [Ailments]

- Match score: `140`
- `k`: {0}% reduced [Critical|Critical Hit Chance] against Enemies that are affected
by no Elemental [Ailments]
- `n`: {0}% reduced [Critical|Critical Hit Chance] against Enemies that are affected
by no Elemental [Ailments]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [Critical|Critical Hit Chance] against Enemies that are affected\nby no Elemental [Ailments]","n":"{0}% reduced [Critical|Critical Hit Chance] against Enemies that are affected\nby no Elemental [Ailments]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 24. {0}% reduced [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies

- Match score: `140`
- `k`: {0}% reduced [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies
- `n`: {0}% reduced [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies","n":"{0}% reduced [Critical|Critical Hit] Chance against [Shock|Shocked] Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 25. {0}% reduced [Critical|Critical Hit] Chance against Enemies affected
by Elemental Ailments

- Match score: `140`
- `k`: {0}% reduced [Critical|Critical Hit] Chance against Enemies affected
by Elemental Ailments
- `n`: {0}% reduced [Critical|Critical Hit] Chance against Enemies affected
by Elemental Ailments
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [Critical|Critical Hit] Chance against Enemies affected\nby Elemental Ailments","n":"{0}% reduced [Critical|Critical Hit] Chance against Enemies affected\nby Elemental Ailments","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 26. {0}% reduced [Critical|Critical Hit] Chance against Shocked Enemies

- Match score: `140`
- `k`: {0}% reduced [Critical|Critical Hit] Chance against Shocked Enemies
- `n`: {0}% reduced [Critical|Critical Hit] Chance against Shocked Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [Critical|Critical Hit] Chance against Shocked Enemies","n":"{0}% reduced [Critical|Critical Hit] Chance against Shocked Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 27. {0}% reduced [Critical|Critical Hit] Chance if you've been Shocked [Recently]

- Match score: `140`
- `k`: {0}% reduced [Critical|Critical Hit] Chance if you've been Shocked [Recently]
- `n`: {0}% reduced [Critical|Critical Hit] Chance if you've been Shocked [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [Critical|Critical Hit] Chance if you've been Shocked [Recently]","n":"{0}% reduced [Critical|Critical Hit] Chance if you've been Shocked [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 28. {0}% to [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are affected
by Elemental Ailments

- Match score: `140`
- `k`: {0}% to [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are affected
by Elemental Ailments
- `n`: {0}% to [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are affected
by Elemental Ailments
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% to [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are affected\nby Elemental Ailments","n":"{0}% to [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are affected\nby Elemental Ailments","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 29. +1 Arctic Petal per [Power] of targets Killed with [Critical|Critical] [HitDamage|Hits]

- Match score: `105`
- `k`: +1 Arctic Petal per [Power] of targets Killed with [Critical|Critical] [HitDamage|Hits]
- `n`: +1 Arctic Petal per [Power] of targets Killed with [Critical|Critical] [HitDamage|Hits]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"+1 Arctic Petal per [Power] of targets Killed with [Critical|Critical] [HitDamage|Hits]","n":"+1 Arctic Petal per [Power] of targets Killed with [Critical|Critical] [HitDamage|Hits]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 30. [Archon] Buffs also grant {0}% increased [CriticalDamageBonus|Critical Damage Bonus]

- Match score: `105`
- `k`: [Archon] Buffs also grant {0}% increased [CriticalDamageBonus|Critical Damage Bonus]
- `n`: [Archon] Buffs also grant {0}% increased [CriticalDamageBonus|Critical Damage Bonus]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Archon] Buffs also grant {0}% increased [CriticalDamageBonus|Critical Damage Bonus]","n":"[Archon] Buffs also grant {0}% increased [CriticalDamageBonus|Critical Damage Bonus]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 31. [Archon] Buffs also grant {0}% increased [Critical|Critical Hit Chance]

- Match score: `105`
- `k`: [Archon] Buffs also grant {0}% increased [Critical|Critical Hit Chance]
- `n`: [Archon] Buffs also grant {0}% increased [Critical|Critical Hit Chance]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Archon] Buffs also grant {0}% increased [Critical|Critical Hit Chance]","n":"[Archon] Buffs also grant {0}% increased [Critical|Critical Hit Chance]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 32. [Attack] [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]

- Match score: `105`
- `k`: [Attack] [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]
- `n`: [Attack] [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Attack] [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]","n":"[Attack] [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 33. [Critical|Critical Hit] Chance is increased by Lightning Resistance

- Match score: `105`
- `k`: [Critical|Critical Hit] Chance is increased by Lightning Resistance
- `n`: [Critical|Critical Hit] Chance is increased by Lightning Resistance
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hit] Chance is increased by Lightning Resistance","n":"[Critical|Critical Hit] Chance is increased by Lightning Resistance","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 34. [Critical|Critical Hit] Chance is increased by Overcapped Lightning Resistance

- Match score: `105`
- `k`: [Critical|Critical Hit] Chance is increased by Overcapped Lightning Resistance
- `n`: [Critical|Critical Hit] Chance is increased by Overcapped Lightning Resistance
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hit] Chance is increased by Overcapped Lightning Resistance","n":"[Critical|Critical Hit] Chance is increased by Overcapped Lightning Resistance","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 35. [Critical|Critical Hits] [IgnoreResistances|Ignore] Enemy Monster [Resistances|Lightning Resistance]

- Match score: `105`
- `k`: [Critical|Critical Hits] [IgnoreResistances|Ignore] Enemy Monster [Resistances|Lightning Resistance]
- `n`: [Critical|Critical Hits] [IgnoreResistances|Ignore] Enemy Monster [Resistances|Lightning Resistance]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hits] [IgnoreResistances|Ignore] Enemy Monster [Resistances|Lightning Resistance]","n":"[Critical|Critical Hits] [IgnoreResistances|Ignore] Enemy Monster [Resistances|Lightning Resistance]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 36. [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]

- Match score: `105`
- `k`: [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]
- `n`: [Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]","n":"[Critical|Critical Hits] ignore Enemy Monster [Resistances|Elemental Resistances]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 37. [Critical|Critical Hits] ignore non-negative Enemy Monster [Resistances|Elemental Resistances]

- Match score: `105`
- `k`: [Critical|Critical Hits] ignore non-negative Enemy Monster [Resistances|Elemental Resistances]
- `n`: [Critical|Critical Hits] ignore non-negative Enemy Monster [Resistances|Elemental Resistances]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hits] ignore non-negative Enemy Monster [Resistances|Elemental Resistances]","n":"[Critical|Critical Hits] ignore non-negative Enemy Monster [Resistances|Elemental Resistances]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 38. [Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances while affected by Zealotry

- Match score: `105`
- `k`: [Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances while affected by Zealotry
- `n`: [Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances while affected by Zealotry
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances while affected by Zealotry","n":"[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances while affected by Zealotry","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 39. [Critical|Critical Hits] with Lightning Skills Sap the Enemy

- Match score: `105`
- `k`: [Critical|Critical Hits] with Lightning Skills Sap the Enemy
- `n`: [Critical|Critical Hits] with Lightning Skills Sap the Enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Critical|Critical Hits] with Lightning Skills Sap the Enemy","n":"[Critical|Critical Hits] with Lightning Skills Sap the Enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 40. [ElementalDamage|Elemental Damage] from [HitDamage|Hits] is taken from the Barrier before your Life, Mana or [EnergyShield|Energy Shield]
Barrier can take [ElementalDamage|Elemental Damage] equal to {0}% of your [Armour] and [Evasion|Evasion Rating], up to a maximum of 32,000

- Match score: `105`
- `k`: [ElementalDamage|Elemental Damage] from [HitDamage|Hits] is taken from the Barrier before your Life, Mana or [EnergyShield|Energy Shield]
Barrier can take [ElementalDamage|Elemental Damage] equal to {0}% of your [Armour] and [Evasion|Evasion Rating], up to a maximum of 32,000
- `n`: [ElementalDamage|Elemental Damage] from [HitDamage|Hits] is taken from the Barrier before your Life, Mana or [EnergyShield|Energy Shield]
Barrier can take [ElementalDamage|Elemental Damage] equal to {0}% of your [Armour] and [Evasion|Evasion Rating], up to a maximum of 32,000
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[ElementalDamage|Elemental Damage] from [HitDamage|Hits] is taken from the Barrier before your Life, Mana or [EnergyShield|Energy Shield]\nBarrier can take [ElementalDamage|Elemental Damage] equal to {0}% of your [Armour] and [Evasion|Evasion Rating], up to a maximum of 32,000","n":"[ElementalDamage|Elemental Damage] from [HitDamage|Hits] is taken from the Barrier before your Life, Mana or [EnergyShield|Energy Shield]\nBarrier can take [ElementalDamage|Elemental Damage] equal to {0}% of your [Armour] and [Evasion|Evasion Rating], up to a maximum of 32,000","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 41. [EnergyShield|Energy Shield] Recovered on killing a [Shock|Shocked] Enemy@{0}%

- Match score: `105`
- `k`: [EnergyShield|Energy Shield] Recovered on killing a [Shock|Shocked] Enemy@{0}%
- `n`: [EnergyShield|Energy Shield] Recovered on killing a [Shock|Shocked] Enemy@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[EnergyShield|Energy Shield] Recovered on killing a [Shock|Shocked] Enemy@{0}%","n":"[EnergyShield|Energy Shield] Recovered on killing a [Shock|Shocked] Enemy@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 42. [Exposure] on [Cold] [Critical|Critical Hit]@{0}s

- Match score: `105`
- `k`: [Exposure] on [Cold] [Critical|Critical Hit]@{0}s
- `n`: [Exposure] on [Cold] [Critical|Critical Hit]@{0}s
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Exposure] on [Cold] [Critical|Critical Hit]@{0}s","n":"[Exposure] on [Cold] [Critical|Critical Hit]@{0}s","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 43. [Gain] {0}% of Damage as [Lightning] Damage for {1} seconds on killing a [Shock|Shocked] enemy with Supported Skills

- Match score: `105`
- `k`: [Gain] {0}% of Damage as [Lightning] Damage for {1} seconds on killing a [Shock|Shocked] enemy with Supported Skills
- `n`: [Gain] {0}% of Damage as [Lightning] Damage for {1} seconds on killing a [Shock|Shocked] enemy with Supported Skills
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Gain] {0}% of Damage as [Lightning] Damage for {1} seconds on killing a [Shock|Shocked] enemy with Supported Skills","n":"[Gain] {0}% of Damage as [Lightning] Damage for {1} seconds on killing a [Shock|Shocked] enemy with Supported Skills","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 44. [Gain] {0}% of Damage as Extra [Lightning] Damage while on [ShockedGround|Shocked Ground]

- Match score: `105`
- `k`: [Gain] {0}% of Damage as Extra [Lightning] Damage while on [ShockedGround|Shocked Ground]
- `n`: [Gain] {0}% of Damage as Extra [Lightning] Damage while on [ShockedGround|Shocked Ground]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Gain] {0}% of Damage as Extra [Lightning] Damage while on [ShockedGround|Shocked Ground]","n":"[Gain] {0}% of Damage as Extra [Lightning] Damage while on [ShockedGround|Shocked Ground]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 45. [Lightning] damage per second if [ShockedGround|Shocked Ground] absorbed@{0}

- Match score: `105`
- `k`: [Lightning] damage per second if [ShockedGround|Shocked Ground] absorbed@{0}
- `n`: [Lightning] damage per second if [ShockedGround|Shocked Ground] absorbed@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Lightning] damage per second if [ShockedGround|Shocked Ground] absorbed@{0}","n":"[Lightning] damage per second if [ShockedGround|Shocked Ground] absorbed@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 46. [Lightning] Damage with [Critical|Non-Critical Hits] is [Lucky]

- Match score: `105`
- `k`: [Lightning] Damage with [Critical|Non-Critical Hits] is [Lucky]
- `n`: [Lightning] Damage with [Critical|Non-Critical Hits] is [Lucky]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Lightning] Damage with [Critical|Non-Critical Hits] is [Lucky]","n":"[Lightning] Damage with [Critical|Non-Critical Hits] is [Lucky]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 47. [Penetration|Penetrates] {0}% [Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]

- Match score: `105`
- `k`: [Penetration|Penetrates] {0}% [Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]
- `n`: [Penetration|Penetrates] {0}% [Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Penetration|Penetrates] {0}% [Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]","n":"[Penetration|Penetrates] {0}% [Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 48. [Projectile] added [Lightning] [ElementalInfusion|Infusion] damage@{0}–{1}

- Match score: `105`
- `k`: [Projectile] added [Lightning] [ElementalInfusion|Infusion] damage@{0}–{1}
- `n`: [Projectile] added [Lightning] [ElementalInfusion|Infusion] damage@{0}–{1}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile] added [Lightning] [ElementalInfusion|Infusion] damage@{0}–{1}","n":"[Projectile] added [Lightning] [ElementalInfusion|Infusion] damage@{0}–{1}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 49. [Projectile|Projectiles] have {0}% increased [Critical] Hit Chance against Enemies further than 6m

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% increased [Critical] Hit Chance against Enemies further than 6m
- `n`: [Projectile|Projectiles] have {0}% increased [Critical] Hit Chance against Enemies further than 6m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% increased [Critical] Hit Chance against Enemies further than 6m","n":"[Projectile|Projectiles] have {0}% increased [Critical] Hit Chance against Enemies further than 6m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 50. [Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m
- `n`: [Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m","n":"[Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 51. [Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m
- `n`: [Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m","n":"[Projectile|Projectiles] have {0}% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 52. [Projectile|Projectiles] have {0}% increased [Critical|Critical Hit] chance for each time they have [Pierce|Pierced]

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% increased [Critical|Critical Hit] chance for each time they have [Pierce|Pierced]
- `n`: [Projectile|Projectiles] have {0}% increased [Critical|Critical Hit] chance for each time they have [Pierce|Pierced]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% increased [Critical|Critical Hit] chance for each time they have [Pierce|Pierced]","n":"[Projectile|Projectiles] have {0}% increased [Critical|Critical Hit] chance for each time they have [Pierce|Pierced]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 53. [Projectile|Projectiles] have {0}% reduced [Critical] Hit Chance against Enemies further than 6m

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% reduced [Critical] Hit Chance against Enemies further than 6m
- `n`: [Projectile|Projectiles] have {0}% reduced [Critical] Hit Chance against Enemies further than 6m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% reduced [Critical] Hit Chance against Enemies further than 6m","n":"[Projectile|Projectiles] have {0}% reduced [Critical] Hit Chance against Enemies further than 6m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 54. [Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m
- `n`: [Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m","n":"[Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies further than 6m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 55. [Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m

- Match score: `105`
- `k`: [Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m
- `n`: [Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m","n":"[Projectile|Projectiles] have {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] against Enemies within 2m","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 56. [Projectile|Projectiles] which pass through the [ElementalInfusion|Infused] wall deal {0} to {1} Added [Lightning] Damage

- Match score: `105`
- `k`: [Projectile|Projectiles] which pass through the [ElementalInfusion|Infused] wall deal {0} to {1} Added [Lightning] Damage
- `n`: [Projectile|Projectiles] which pass through the [ElementalInfusion|Infused] wall deal {0} to {1} Added [Lightning] Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Projectile|Projectiles] which pass through the [ElementalInfusion|Infused] wall deal {0} to {1} Added [Lightning] Damage","n":"[Projectile|Projectiles] which pass through the [ElementalInfusion|Infused] wall deal {0} to {1} Added [Lightning] Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 57. [Trigger] Lightning Bolt Skill on [Critical|Critical Hit]

- Match score: `105`
- `k`: [Trigger] Lightning Bolt Skill on [Critical|Critical Hit]
- `n`: [Trigger] Lightning Bolt Skill on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Trigger] Lightning Bolt Skill on [Critical|Critical Hit]","n":"[Trigger] Lightning Bolt Skill on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 58. [Trigger] Spark Skill on killing a [Shock|Shocked] Enemy

- Match score: `105`
- `k`: [Trigger] Spark Skill on killing a [Shock|Shocked] Enemy
- `n`: [Trigger] Spark Skill on killing a [Shock|Shocked] Enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Trigger] Spark Skill on killing a [Shock|Shocked] Enemy","n":"[Trigger] Spark Skill on killing a [Shock|Shocked] Enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 59. [Trigger|Triggers] Fiery Explosion, Arcing Bolt, or Icy Wave on [Melee] [Critical|Critical Hit]

- Match score: `105`
- `k`: [Trigger|Triggers] Fiery Explosion, Arcing Bolt, or Icy Wave on [Melee] [Critical|Critical Hit]
- `n`: [Trigger|Triggers] Fiery Explosion, Arcing Bolt, or Icy Wave on [Melee] [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Trigger|Triggers] Fiery Explosion, Arcing Bolt, or Icy Wave on [Melee] [Critical|Critical Hit]","n":"[Trigger|Triggers] Fiery Explosion, Arcing Bolt, or Icy Wave on [Melee] [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 60. [Warcry|Warcries] inflict {0} [CriticalWeakness|Critical Weakness] on Enemies

- Match score: `105`
- `k`: [Warcry|Warcries] inflict {0} [CriticalWeakness|Critical Weakness] on Enemies
- `n`: [Warcry|Warcries] inflict {0} [CriticalWeakness|Critical Weakness] on Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Warcry|Warcries] inflict {0} [CriticalWeakness|Critical Weakness] on Enemies","n":"[Warcry|Warcries] inflict {0} [CriticalWeakness|Critical Weakness] on Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 61. [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [IgnitedGround|Ignited] and [ShockedGround|Shocked] Ground

- Match score: `105`
- `k`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [IgnitedGround|Ignited] and [ShockedGround|Shocked] Ground
- `n`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [IgnitedGround|Ignited] and [ShockedGround|Shocked] Ground
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [IgnitedGround|Ignited] and [ShockedGround|Shocked] Ground","n":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [IgnitedGround|Ignited] and [ShockedGround|Shocked] Ground","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 62. [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [IgnitedGround|Ignited], [ShockedGround|Shocked], and [ChilledGround|Chilled] Ground

- Match score: `105`
- `k`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [IgnitedGround|Ignited], [ShockedGround|Shocked], and [ChilledGround|Chilled] Ground
- `n`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [IgnitedGround|Ignited], [ShockedGround|Shocked], and [ChilledGround|Chilled] Ground
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [IgnitedGround|Ignited], [ShockedGround|Shocked], and [ChilledGround|Chilled] Ground","n":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [IgnitedGround|Ignited], [ShockedGround|Shocked], and [ChilledGround|Chilled] Ground","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 63. [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [ShockedGround|Shocked Ground]

- Match score: `105`
- `k`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [ShockedGround|Shocked Ground]
- `n`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [ShockedGround|Shocked Ground]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [ShockedGround|Shocked Ground]","n":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [ShockedGround|Shocked Ground]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 64. [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [ShockedGround|Shocked] and [ChilledGround|Chilled] Ground

- Match score: `105`
- `k`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [ShockedGround|Shocked] and [ChilledGround|Chilled] Ground
- `n`: [Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count
as being boosted by [ShockedGround|Shocked] and [ChilledGround|Chilled] Ground
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [ShockedGround|Shocked] and [ChilledGround|Chilled] Ground","n":"[Wind|Wind Skills] which can be boosted by [ElementalGround|Elemental Ground Surfaces] count\nas being boosted by [ShockedGround|Shocked] and [ChilledGround|Chilled] Ground","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 65. Adds {0} to {1} Lightning Damage against Shocked Enemies

- Match score: `105`
- `k`: Adds {0} to {1} Lightning Damage against Shocked Enemies
- `n`: Adds {0} to {1} Lightning Damage against Shocked Enemies
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} to {1} Lightning Damage against Shocked Enemies","n":"Adds {0} to {1} Lightning Damage against Shocked Enemies","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 66. Adds {0} to {1} Lightning Damage for each Shocked Enemy you've Killed [Recently]

- Match score: `105`
- `k`: Adds {0} to {1} Lightning Damage for each Shocked Enemy you've Killed [Recently]
- `n`: Adds {0} to {1} Lightning Damage for each Shocked Enemy you've Killed [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} to {1} Lightning Damage for each Shocked Enemy you've Killed [Recently]","n":"Adds {0} to {1} Lightning Damage for each Shocked Enemy you've Killed [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 67. Adds {0} to {1} Lightning Damage if you've dealt a [Critical|Critical Hit] [Recently]

- Match score: `105`
- `k`: Adds {0} to {1} Lightning Damage if you've dealt a [Critical|Critical Hit] [Recently]
- `n`: Adds {0} to {1} Lightning Damage if you've dealt a [Critical|Critical Hit] [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Adds {0} to {1} Lightning Damage if you've dealt a [Critical|Critical Hit] [Recently]","n":"Adds {0} to {1} Lightning Damage if you've dealt a [Critical|Critical Hit] [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 68. Arctic Petals on [Critical|Critical] [HitDamage|Hit] vs Rare or Unique@{0}

- Match score: `105`
- `k`: Arctic Petals on [Critical|Critical] [HitDamage|Hit] vs Rare or Unique@{0}
- `n`: Arctic Petals on [Critical|Critical] [HitDamage|Hit] vs Rare or Unique@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Arctic Petals on [Critical|Critical] [HitDamage|Hit] vs Rare or Unique@{0}","n":"Arctic Petals on [Critical|Critical] [HitDamage|Hit] vs Rare or Unique@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 69. Arctic Petals per [Power] of [Critical|Critical] [HitDamage|Hit] Kills@1

- Match score: `105`
- `k`: Arctic Petals per [Power] of [Critical|Critical] [HitDamage|Hit] Kills@1
- `n`: Arctic Petals per [Power] of [Critical|Critical] [HitDamage|Hit] Kills@1
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Arctic Petals per [Power] of [Critical|Critical] [HitDamage|Hit] Kills@1","n":"Arctic Petals per [Power] of [Critical|Critical] [HitDamage|Hit] Kills@1","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 70. Area has patches of [ShockedGround|Shocked Ground]

- Match score: `105`
- `k`: Area has patches of [ShockedGround|Shocked Ground]
- `n`: Area has patches of [ShockedGround|Shocked Ground]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Area has patches of [ShockedGround|Shocked Ground]","n":"Area has patches of [ShockedGround|Shocked Ground]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 71. Area has patches of [ShockedGround|Shocked Ground] which increase Damage taken by {0}%

- Match score: `105`
- `k`: Area has patches of [ShockedGround|Shocked Ground] which increase Damage taken by {0}%
- `n`: Area has patches of [ShockedGround|Shocked Ground] which increase Damage taken by {0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Area has patches of [ShockedGround|Shocked Ground] which increase Damage taken by {0}%","n":"Area has patches of [ShockedGround|Shocked Ground] which increase Damage taken by {0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 72. Area has patches of Shocked Ground

- Match score: `105`
- `k`: Area has patches of Shocked Ground
- `n`: Area has patches of Shocked Ground
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Area has patches of Shocked Ground","n":"Area has patches of Shocked Ground","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 73. Become [Ignite|Ignited] when you deal a [Critical|Critical Hit], taking {0}% of your maximum Life and [EnergyShield|Energy Shield] as [Fire] Damage per second

- Match score: `105`
- `k`: Become [Ignite|Ignited] when you deal a [Critical|Critical Hit], taking {0}% of your maximum Life and [EnergyShield|Energy Shield] as [Fire] Damage per second
- `n`: Become [Ignite|Ignited] when you deal a [Critical|Critical Hit], taking {0}% of your maximum Life and [EnergyShield|Energy Shield] as [Fire] Damage per second
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Become [Ignite|Ignited] when you deal a [Critical|Critical Hit], taking {0}% of your maximum Life and [EnergyShield|Energy Shield] as [Fire] Damage per second","n":"Become [Ignite|Ignited] when you deal a [Critical|Critical Hit], taking {0}% of your maximum Life and [EnergyShield|Energy Shield] as [Fire] Damage per second","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 74. Can [Attack] as though using a [Quarterstaff] while both of your hand slots are empty
[UnarmedAttack|Unarmed Attacks] that would use an [Equipped] [Quarterstaff]'s damage have:
• Base [UnarmedDamage|Unarmed] [Physical] damage replaced with damage based on their Skill Level
• 1% more [Attack] Speed per 75 [ItemEvasion|Item Evasion] on [EquipArmour|Equipped Armour Items]
• +0.1% to [Critical|Critical Hit Chance] per 10 [ItemEnergyShield|Item Energy Shield] on [EquipArmour|Equipped Armour Items]

- Match score: `105`
- `k`: Can [Attack] as though using a [Quarterstaff] while both of your hand slots are empty
[UnarmedAttack|Unarmed Attacks] that would use an [Equipped] [Quarterstaff]'s damage have:
• Base [UnarmedDamage|Unarmed] [Physical] damage replaced with damage based on their Skill Level
• 1% more [Attack] Speed per 75 [ItemEvasion|Item Evasion] on [EquipArmour|Equipped Armour Items]
• +0.1% to [Critical|Critical Hit Chance] per 10 [ItemEnergyShield|Item Energy Shield] on [EquipArmour|Equipped Armour Items]
- `n`: Can [Attack] as though using a [Quarterstaff] while both of your hand slots are empty
[UnarmedAttack|Unarmed Attacks] that would use an [Equipped] [Quarterstaff]'s damage have:
• Base [UnarmedDamage|Unarmed] [Physical] damage replaced with damage based on their Skill Level
• 1% more [Attack] Speed per 75 [ItemEvasion|Item Evasion] on [EquipArmour|Equipped Armour Items]
• +0.1% to [Critical|Critical Hit Chance] per 10 [ItemEnergyShield|Item Energy Shield] on [EquipArmour|Equipped Armour Items]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Can [Attack] as though using a [Quarterstaff] while both of your hand slots are empty\n[UnarmedAttack|Unarmed Attacks] that would use an [Equipped] [Quarterstaff]'s damage have:\n• Base [UnarmedDamage|Unarmed] [Physical] damage replaced with damage based on their Skill Level\n• 1% more [Attack] Speed per 75 [ItemEvasion|Item Evasion] on [EquipArmour|Equipped Armour Items]\n• +0.1% to [Critical|Critical Hit Chance] per 10 [ItemEnergyShield|Item Energy Shield] on [EquipArmour|Equipped Armour Items]","n":"Can [Attack] as though using a [Quarterstaff] while both of your hand slots are empty\n[UnarmedAttack|Unarmed Attacks] that would use an [Equipped] [Quarterstaff]'s damage have:\n• Base [UnarmedDamage|Unarmed] [Physical] damage replaced with damage based on their Skill Level\n• 1% more [Attack] Speed per 75 [ItemEvasion|Item Evasion] on [EquipArmour|Equipped Armour Items]\n• +0.1% to...[trimmed]
```

### 75. Cannot Ignite, Chill, Freeze or Shock
[Critical|Critical Hits] inflict Scorch, Brittle and Sapped

- Match score: `105`
- `k`: Cannot Ignite, Chill, Freeze or Shock
[Critical|Critical Hits] inflict Scorch, Brittle and Sapped
- `n`: Cannot Ignite, Chill, Freeze or Shock
[Critical|Critical Hits] inflict Scorch, Brittle and Sapped
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Cannot Ignite, Chill, Freeze or Shock\n[Critical|Critical Hits] inflict Scorch, Brittle and Sapped","n":"Cannot Ignite, Chill, Freeze or Shock\n[Critical|Critical Hits] inflict Scorch, Brittle and Sapped","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 76. Cannot Regenerate Mana if you haven't dealt a [Critical|Critical Hit] [Recently]

- Match score: `105`
- `k`: Cannot Regenerate Mana if you haven't dealt a [Critical|Critical Hit] [Recently]
- `n`: Cannot Regenerate Mana if you haven't dealt a [Critical|Critical Hit] [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Cannot Regenerate Mana if you haven't dealt a [Critical|Critical Hit] [Recently]","n":"Cannot Regenerate Mana if you haven't dealt a [Critical|Critical Hit] [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 77. Creates a storm when you Kill a Shocked Enemy

- Match score: `105`
- `k`: Creates a storm when you Kill a Shocked Enemy
- `n`: Creates a storm when you Kill a Shocked Enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Creates a storm when you Kill a Shocked Enemy","n":"Creates a storm when you Kill a Shocked Enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 78. Creates a storm when you Kill a Shocked Enemy or Shock an Enemy

- Match score: `105`
- `k`: Creates a storm when you Kill a Shocked Enemy or Shock an Enemy
- `n`: Creates a storm when you Kill a Shocked Enemy or Shock an Enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Creates a storm when you Kill a Shocked Enemy or Shock an Enemy","n":"Creates a storm when you Kill a Shocked Enemy or Shock an Enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 79. Damage [Gain|Gained] as [Lightning] for {1} seconds on kill vs [Shock|Shocked]@{0}%

- Match score: `105`
- `k`: Damage [Gain|Gained] as [Lightning] for {1} seconds on kill vs [Shock|Shocked]@{0}%
- `n`: Damage [Gain|Gained] as [Lightning] for {1} seconds on kill vs [Shock|Shocked]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Damage [Gain|Gained] as [Lightning] for {1} seconds on kill vs [Shock|Shocked]@{0}%","n":"Damage [Gain|Gained] as [Lightning] for {1} seconds on kill vs [Shock|Shocked]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 80. Damage [Penetration|Penetrates] {0}% [Lightning|Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]

- Match score: `105`
- `k`: Damage [Penetration|Penetrates] {0}% [Lightning|Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]
- `n`: Damage [Penetration|Penetrates] {0}% [Lightning|Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Damage [Penetration|Penetrates] {0}% [Lightning|Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]","n":"Damage [Penetration|Penetrates] {0}% [Lightning|Lightning] [Resistances|Resistance] if on [LowMana|Low Mana]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 81. Elemental Damage with Hits is Lucky while you are Shocked

- Match score: `105`
- `k`: Elemental Damage with Hits is Lucky while you are Shocked
- `n`: Elemental Damage with Hits is Lucky while you are Shocked
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Elemental Damage with Hits is Lucky while you are Shocked","n":"Elemental Damage with Hits is Lucky while you are Shocked","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 82. Enemies [Shock|Shocked] by Supported Skills take {0}% of damage from [Ignite] as [Lightning] damage as well as [Fire] damage

- Match score: `105`
- `k`: Enemies [Shock|Shocked] by Supported Skills take {0}% of damage from [Ignite] as [Lightning] damage as well as [Fire] damage
- `n`: Enemies [Shock|Shocked] by Supported Skills take {0}% of damage from [Ignite] as [Lightning] damage as well as [Fire] damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Enemies [Shock|Shocked] by Supported Skills take {0}% of damage from [Ignite] as [Lightning] damage as well as [Fire] damage","n":"Enemies [Shock|Shocked] by Supported Skills take {0}% of damage from [Ignite] as [Lightning] damage as well as [Fire] damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 83. Enemies Shocked by you have {0}% of Physical Damage they deal converted to Lightning

- Match score: `105`
- `k`: Enemies Shocked by you have {0}% of Physical Damage they deal converted to Lightning
- `n`: Enemies Shocked by you have {0}% of Physical Damage they deal converted to Lightning
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Enemies Shocked by you have {0}% of Physical Damage they deal converted to Lightning","n":"Enemies Shocked by you have {0}% of Physical Damage they deal converted to Lightning","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 84. Enemies Shocked or Frozen by you take {0}% increased Elemental Damage

- Match score: `105`
- `k`: Enemies Shocked or Frozen by you take {0}% increased Elemental Damage
- `n`: Enemies Shocked or Frozen by you take {0}% increased Elemental Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Enemies Shocked or Frozen by you take {0}% increased Elemental Damage","n":"Enemies Shocked or Frozen by you take {0}% increased Elemental Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 85. Enemies Shocked or Frozen by you take {0}% reduced Elemental Damage

- Match score: `105`
- `k`: Enemies Shocked or Frozen by you take {0}% reduced Elemental Damage
- `n`: Enemies Shocked or Frozen by you take {0}% reduced Elemental Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Enemies Shocked or Frozen by you take {0}% reduced Elemental Damage","n":"Enemies Shocked or Frozen by you take {0}% reduced Elemental Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 86. Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]

- Match score: `105`
- `k`: Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]
- `n`: Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]","n":"Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 87. Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana

- Match score: `105`
- `k`: Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana
- `n`: Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana","n":"Gain [ElementalArchon|Elemental Archon] after spending 100% of your Maximum Mana","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 88. Gain [ElementalArchon|Elemental Archon] when your [ESRecharge|Energy Shield Recharge] begins

- Match score: `105`
- `k`: Gain [ElementalArchon|Elemental Archon] when your [ESRecharge|Energy Shield Recharge] begins
- `n`: Gain [ElementalArchon|Elemental Archon] when your [ESRecharge|Energy Shield Recharge] begins
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain [ElementalArchon|Elemental Archon] when your [ESRecharge|Energy Shield Recharge] begins","n":"Gain [ElementalArchon|Elemental Archon] when your [ESRecharge|Energy Shield Recharge] begins","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 89. Gain [LightningArchon|Lightning Archon] after spending 100% of your Maximum Mana

- Match score: `105`
- `k`: Gain [LightningArchon|Lightning Archon] after spending 100% of your Maximum Mana
- `n`: Gain [LightningArchon|Lightning Archon] after spending 100% of your Maximum Mana
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain [LightningArchon|Lightning Archon] after spending 100% of your Maximum Mana","n":"Gain [LightningArchon|Lightning Archon] after spending 100% of your Maximum Mana","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 90. Gain {0}% to [Critical|Critical Hit] Chance for 2 seconds after Spending a total of 800 Mana

- Match score: `105`
- `k`: Gain {0}% to [Critical|Critical Hit] Chance for 2 seconds after Spending a total of 800 Mana
- `n`: Gain {0}% to [Critical|Critical Hit] Chance for 2 seconds after Spending a total of 800 Mana
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain {0}% to [Critical|Critical Hit] Chance for 2 seconds after Spending a total of 800 Mana","n":"Gain {0}% to [Critical|Critical Hit] Chance for 2 seconds after Spending a total of 800 Mana","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 91. Gains {0} [Energy] per [Power] of enemies you
[Critical|Critically Hit] with Skills, modified by the percentage of the enemy's [AilmentThreshold|Ailment Threshold] the Critical Hit will deal

- Match score: `105`
- `k`: Gains {0} [Energy] per [Power] of enemies you
[Critical|Critically Hit] with Skills, modified by the percentage of the enemy's [AilmentThreshold|Ailment Threshold] the Critical Hit will deal
- `n`: Gains {0} [Energy] per [Power] of enemies you
[Critical|Critically Hit] with Skills, modified by the percentage of the enemy's [AilmentThreshold|Ailment Threshold] the Critical Hit will deal
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gains {0} [Energy] per [Power] of enemies you\n[Critical|Critically Hit] with Skills, modified by the percentage of the enemy's [AilmentThreshold|Ailment Threshold] the Critical Hit will deal","n":"Gains {0} [Energy] per [Power] of enemies you\n[Critical|Critically Hit] with Skills, modified by the percentage of the enemy's [AilmentThreshold|Ailment Threshold] the Critical Hit will deal","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 92. Immune to Elemental Ailments while you have [ArcaneSurge|Arcane Surge]

- Match score: `105`
- `k`: Immune to Elemental Ailments while you have [ArcaneSurge|Arcane Surge]
- `n`: Immune to Elemental Ailments while you have [ArcaneSurge|Arcane Surge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Immune to Elemental Ailments while you have [ArcaneSurge|Arcane Surge]","n":"Immune to Elemental Ailments while you have [ArcaneSurge|Arcane Surge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 93. Inflict [Exposure|Lightning Exposure] for {0} seconds when you [Electrocute] an Enemy

- Match score: `105`
- `k`: Inflict [Exposure|Lightning Exposure] for {0} seconds when you [Electrocute] an Enemy
- `n`: Inflict [Exposure|Lightning Exposure] for {0} seconds when you [Electrocute] an Enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Inflict [Exposure|Lightning Exposure] for {0} seconds when you [Electrocute] an Enemy","n":"Inflict [Exposure|Lightning Exposure] for {0} seconds when you [Electrocute] an Enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 94. JewelCriticalAilmentEffect

- Match score: `105`
- `k`: JewelCriticalAilmentEffect
- `n`: JewelCriticalAilmentEffect
- `cat`: pob_mod_jewel
- `src`: pob_data_poe2/ModJewel.json

```json
{"k":"JewelCriticalAilmentEffect","n":"JewelCriticalAilmentEffect","cat":"pob_mod_jewel","src":"pob_data_poe2/ModJewel.json","level":1}
```

### 95. JewelRadiusCriticalAilmentEffect

- Match score: `105`
- `k`: JewelRadiusCriticalAilmentEffect
- `n`: JewelRadiusCriticalAilmentEffect
- `cat`: pob_mod_jewel
- `src`: pob_data_poe2/ModJewel.json

```json
{"k":"JewelRadiusCriticalAilmentEffect","n":"JewelRadiusCriticalAilmentEffect","cat":"pob_mod_jewel","src":"pob_data_poe2/ModJewel.json","level":1}
```

### 96. JewelRadiusSpearCriticalDamage

- Match score: `105`
- `k`: JewelRadiusSpearCriticalDamage
- `n`: JewelRadiusSpearCriticalDamage
- `cat`: pob_mod_jewel
- `src`: pob_data_poe2/ModJewel.json

```json
{"k":"JewelRadiusSpearCriticalDamage","n":"JewelRadiusSpearCriticalDamage","cat":"pob_mod_jewel","src":"pob_data_poe2/ModJewel.json","level":1}
```

### 97. JewelSpearCriticalDamage

- Match score: `105`
- `k`: JewelSpearCriticalDamage
- `n`: JewelSpearCriticalDamage
- `cat`: pob_mod_jewel
- `src`: pob_data_poe2/ModJewel.json

```json
{"k":"JewelSpearCriticalDamage","n":"JewelSpearCriticalDamage","cat":"pob_mod_jewel","src":"pob_data_poe2/ModJewel.json","level":1}
```

### 98. Knock Back Enemies if you get a [Critical|Critical Hit] with Projectile Damage

- Match score: `105`
- `k`: Knock Back Enemies if you get a [Critical|Critical Hit] with Projectile Damage
- `n`: Knock Back Enemies if you get a [Critical|Critical Hit] with Projectile Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Knock Back Enemies if you get a [Critical|Critical Hit] with Projectile Damage","n":"Knock Back Enemies if you get a [Critical|Critical Hit] with Projectile Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 99. Lightning Bolts strike the targets of your next {0} [Attack|Attack] [HitDamage|Hits]
after killing a [Shock|Shocked] enemy with [Attack|Attack] damage

- Match score: `105`
- `k`: Lightning Bolts strike the targets of your next {0} [Attack|Attack] [HitDamage|Hits]
after killing a [Shock|Shocked] enemy with [Attack|Attack] damage
- `n`: Lightning Bolts strike the targets of your next {0} [Attack|Attack] [HitDamage|Hits]
after killing a [Shock|Shocked] enemy with [Attack|Attack] damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Lightning Bolts strike the targets of your next {0} [Attack|Attack] [HitDamage|Hits]\nafter killing a [Shock|Shocked] enemy with [Attack|Attack] damage","n":"Lightning Bolts strike the targets of your next {0} [Attack|Attack] [HitDamage|Hits]\nafter killing a [Shock|Shocked] enemy with [Attack|Attack] damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 100. Lightning Damage of Enemies Hitting you while you're Shocked is Lucky

- Match score: `105`
- `k`: Lightning Damage of Enemies Hitting you while you're Shocked is Lucky
- `n`: Lightning Damage of Enemies Hitting you while you're Shocked is Lucky
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Lightning Damage of Enemies Hitting you while you're Shocked is Lucky","n":"Lightning Damage of Enemies Hitting you while you're Shocked is Lucky","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 101. Lightning Damage of Enemies Hitting you while you're Shocked is Unlucky

- Match score: `105`
- `k`: Lightning Damage of Enemies Hitting you while you're Shocked is Unlucky
- `n`: Lightning Damage of Enemies Hitting you while you're Shocked is Unlucky
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Lightning Damage of Enemies Hitting you while you're Shocked is Unlucky","n":"Lightning Damage of Enemies Hitting you while you're Shocked is Unlucky","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 102. Lose {0}% of maximum [EnergyShield|Energy Shield] when you deal a [Critical|Critical Hit]

- Match score: `105`
- `k`: Lose {0}% of maximum [EnergyShield|Energy Shield] when you deal a [Critical|Critical Hit]
- `n`: Lose {0}% of maximum [EnergyShield|Energy Shield] when you deal a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Lose {0}% of maximum [EnergyShield|Energy Shield] when you deal a [Critical|Critical Hit]","n":"Lose {0}% of maximum [EnergyShield|Energy Shield] when you deal a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 103. Mana [Leech] from [Critical|Critical Hits] is instant

- Match score: `105`
- `k`: Mana [Leech] from [Critical|Critical Hits] is instant
- `n`: Mana [Leech] from [Critical|Critical Hits] is instant
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Mana [Leech] from [Critical|Critical Hits] is instant","n":"Mana [Leech] from [Critical|Critical Hits] is instant","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 104. Non-[Channelling] [Spell|Spells] have {0}% increased [Critical|Critical Hit Chance] per 100 maximum Mana

- Match score: `105`
- `k`: Non-[Channelling] [Spell|Spells] have {0}% increased [Critical|Critical Hit Chance] per 100 maximum Mana
- `n`: Non-[Channelling] [Spell|Spells] have {0}% increased [Critical|Critical Hit Chance] per 100 maximum Mana
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Non-[Channelling] [Spell|Spells] have {0}% increased [Critical|Critical Hit Chance] per 100 maximum Mana","n":"Non-[Channelling] [Spell|Spells] have {0}% increased [Critical|Critical Hit Chance] per 100 maximum Mana","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 105. Non-[Channelling] [Spell|Spells] have {0}% reduced [Critical|Critical Hit Chance] per 100 maximum Mana

- Match score: `105`
- `k`: Non-[Channelling] [Spell|Spells] have {0}% reduced [Critical|Critical Hit Chance] per 100 maximum Mana
- `n`: Non-[Channelling] [Spell|Spells] have {0}% reduced [Critical|Critical Hit Chance] per 100 maximum Mana
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Non-[Channelling] [Spell|Spells] have {0}% reduced [Critical|Critical Hit Chance] per 100 maximum Mana","n":"Non-[Channelling] [Spell|Spells] have {0}% reduced [Critical|Critical Hit Chance] per 100 maximum Mana","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 106. Non-[Channelling] Spells cost Double Mana and [Critical|Critically Hit]

- Match score: `105`
- `k`: Non-[Channelling] Spells cost Double Mana and [Critical|Critically Hit]
- `n`: Non-[Channelling] Spells cost Double Mana and [Critical|Critically Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Non-[Channelling] Spells cost Double Mana and [Critical|Critically Hit]","n":"Non-[Channelling] Spells cost Double Mana and [Critical|Critically Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 107. Non-[Channelling] Spells have {0}% chance to cost Double Mana and [Critical|Critically Hit]

- Match score: `105`
- `k`: Non-[Channelling] Spells have {0}% chance to cost Double Mana and [Critical|Critically Hit]
- `n`: Non-[Channelling] Spells have {0}% chance to cost Double Mana and [Critical|Critically Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Non-[Channelling] Spells have {0}% chance to cost Double Mana and [Critical|Critically Hit]","n":"Non-[Channelling] Spells have {0}% chance to cost Double Mana and [Critical|Critically Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 108. Non-[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances

- Match score: `105`
- `k`: Non-[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances
- `n`: Non-[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Non-[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances","n":"Non-[Critical|Critical Hits] Penetrate {0}% of Enemy Elemental Resistances","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 109. Projectile [Attack] Skills have {0}% increased [Critical|Critical Hit] Chance

- Match score: `105`
- `k`: Projectile [Attack] Skills have {0}% increased [Critical|Critical Hit] Chance
- `n`: Projectile [Attack] Skills have {0}% increased [Critical|Critical Hit] Chance
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectile [Attack] Skills have {0}% increased [Critical|Critical Hit] Chance","n":"Projectile [Attack] Skills have {0}% increased [Critical|Critical Hit] Chance","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 110. Projectile [Attack] Skills have {0}% reduced [Critical|Critical Hit] Chance

- Match score: `105`
- `k`: Projectile [Attack] Skills have {0}% reduced [Critical|Critical Hit] Chance
- `n`: Projectile [Attack] Skills have {0}% reduced [Critical|Critical Hit] Chance
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectile [Attack] Skills have {0}% reduced [Critical|Critical Hit] Chance","n":"Projectile [Attack] Skills have {0}% reduced [Critical|Critical Hit] Chance","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 111. Projectile [Attack] Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus]

- Match score: `105`
- `k`: Projectile [Attack] Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus]
- `n`: Projectile [Attack] Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectile [Attack] Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus]","n":"Projectile [Attack] Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 112. Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they do not Pierce

- Match score: `105`
- `k`: Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they do not Pierce
- `n`: Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they do not Pierce
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they do not Pierce","n":"Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they do not Pierce","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 113. Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they Pierce

- Match score: `105`
- `k`: Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they Pierce
- `n`: Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they Pierce
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they Pierce","n":"Projectiles have {0}% increased [Critical|Critical Hit] Chance against Targets they Pierce","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 114. Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they do not Pierce

- Match score: `105`
- `k`: Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they do not Pierce
- `n`: Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they do not Pierce
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they do not Pierce","n":"Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they do not Pierce","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 115. Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they Pierce

- Match score: `105`
- `k`: Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they Pierce
- `n`: Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they Pierce
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they Pierce","n":"Projectiles have {0}% reduced [Critical|Critical Hit] Chance against Targets they Pierce","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 116. Projectiles leave Shocked Ground

- Match score: `105`
- `k`: Projectiles leave Shocked Ground
- `n`: Projectiles leave Shocked Ground
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Projectiles leave Shocked Ground","n":"Projectiles leave Shocked Ground","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 117. Recover {0}% of maximum [EnergyShield|Energy Shield] when a Supported Skill deals a [KillingBlow|Killing Blow] to a [Shock|Shocked] enemy

- Match score: `105`
- `k`: Recover {0}% of maximum [EnergyShield|Energy Shield] when a Supported Skill deals a [KillingBlow|Killing Blow] to a [Shock|Shocked] enemy
- `n`: Recover {0}% of maximum [EnergyShield|Energy Shield] when a Supported Skill deals a [KillingBlow|Killing Blow] to a [Shock|Shocked] enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Recover {0}% of maximum [EnergyShield|Energy Shield] when a Supported Skill deals a [KillingBlow|Killing Blow] to a [Shock|Shocked] enemy","n":"Recover {0}% of maximum [EnergyShield|Energy Shield] when a Supported Skill deals a [KillingBlow|Killing Blow] to a [Shock|Shocked] enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 118. Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second if you've dealt a [Critical|Critical Hit] with this weapon [Recently]

- Match score: `105`
- `k`: Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second if you've dealt a [Critical|Critical Hit] with this weapon [Recently]
- `n`: Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second if you've dealt a [Critical|Critical Hit] with this weapon [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second if you've dealt a [Critical|Critical Hit] with this weapon [Recently]","n":"Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second if you've dealt a [Critical|Critical Hit] with this weapon [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 119. Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second while Shocked

- Match score: `105`
- `k`: Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second while Shocked
- `n`: Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second while Shocked
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second while Shocked","n":"Regenerate {0}% of maximum [EnergyShield|Energy Shield] per second while Shocked","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 120. Regenerate {0}% of maximum Mana and [EnergyShield|Energy Shield] per second for 2 seconds when you Freeze, Shock or Ignite an Enemy

- Match score: `105`
- `k`: Regenerate {0}% of maximum Mana and [EnergyShield|Energy Shield] per second for 2 seconds when you Freeze, Shock or Ignite an Enemy
- `n`: Regenerate {0}% of maximum Mana and [EnergyShield|Energy Shield] per second for 2 seconds when you Freeze, Shock or Ignite an Enemy
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Regenerate {0}% of maximum Mana and [EnergyShield|Energy Shield] per second for 2 seconds when you Freeze, Shock or Ignite an Enemy","n":"Regenerate {0}% of maximum Mana and [EnergyShield|Energy Shield] per second for 2 seconds when you Freeze, Shock or Ignite an Enemy","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
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
| Rune mods | OK | 8 |
| Uniques | OK | 9 |
| Misc | OK | 120 |
