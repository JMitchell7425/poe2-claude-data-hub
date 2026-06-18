# Build Idea Pack — Charge-Stacking Build

- Generated UTC: `2026-06-18T13:47:03+00:00`
- Idea slug: `charge-stacking-build`
- Purpose: Engineer around power, frenzy, endurance, charge generation, charge consumption, and charge scaling.
- Keywords: `charge, charges, power charge, frenzy charge, endurance charge, gain charge, consume charge, maximum charge, critical, crit, duration, killing palm, charge profusion, overflowing power, damage, speed, boss, clear`
- Max matched records per index: `120`
- Total included matches: `722`


## Claude usage rules

- Treat this as the active focused data pack for this build idea.
- This is not the full PoE2 database.
- If a needed passive, gem, item base, mod, rune, unique, or interaction is missing, ask the user to expand this idea's keywords in `build_ideas.json` and regenerate the pack.
- Do not invent mechanics or records not present in this pack, the build documents, screenshots, or user-provided tests.

## Passive key nodes

- Source: `build_knowledge/compact/passive_tree_key_nodes.json`
- Matches included: `120`

### 1. Critical Damage when consuming a Power Charge

- Match score: `185`
- `id`: 30615
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"30615","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]}
```

### 2. Critical Damage when consuming a Power Charge

- Match score: `185`
- `id`: 3336
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"3336","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["30615"]}
```

### 3. Critical Damage when consuming a Power Charge

- Match score: `185`
- `id`: 36231
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"36231","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["3336","31765"]}
```

### 4. Archon Duration and Critical Damage

- Match score: `140`
- `id`: 23436
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"23436","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["29197"]}
```

### 5. Archon Duration and Critical Damage

- Match score: `140`
- `id`: 26300
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"26300","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["23436"]}
```

### 6. Archon Duration and Critical Damage

- Match score: `140`
- `id`: 29197
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"29197","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["11428"]}
```

### 7. Endurance Charge Duration

- Match score: `115`
- `id`: 21390
- `n`: Endurance Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Endurance Charge] Duration"]

```json
{"id":"21390","n":"Endurance Charge Duration","t":"small","sd":["20% increased [Charges|Endurance Charge] Duration"],"out":["7972"]}
```

### 8. Endurance Charge Duration

- Match score: `115`
- `id`: 25229
- `n`: Endurance Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Endurance Charge] Duration"]

```json
{"id":"25229","n":"Endurance Charge Duration","t":"small","sd":["20% increased [Charges|Endurance Charge] Duration"],"out":["21390"]}
```

### 9. Endurance Charge Duration

- Match score: `115`
- `id`: 7972
- `n`: Endurance Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Endurance Charge] Duration"]

```json
{"id":"7972","n":"Endurance Charge Duration","t":"small","sd":["20% increased [Charges|Endurance Charge] Duration"],"out":["25229","5663"]}
```

### 10. Endurance Charge Duration and Armour

- Match score: `115`
- `id`: 11027
- `n`: Endurance Charge Duration and Armour
- `t`: small
- `sd`: ["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"11027","n":"Endurance Charge Duration and Armour","t":"small","sd":["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["59433"]}
```

### 11. Endurance Charge Duration and Armour

- Match score: `115`
- `id`: 41701
- `n`: Endurance Charge Duration and Armour
- `t`: small
- `sd`: ["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"41701","n":"Endurance Charge Duration and Armour","t":"small","sd":["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["11741","11027"]}
```

### 12. Fire Damage when consuming an Endurance Charge

- Match score: `115`
- `id`: 15494
- `n`: Fire Damage when consuming an Endurance Charge
- `t`: small
- `sd`: ["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"]

```json
{"id":"15494","n":"Fire Damage when consuming an Endurance Charge","t":"small","sd":["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"],"out":["1865","43584"]}
```

### 13. Fire Damage when consuming an Endurance Charge

- Match score: `115`
- `id`: 1865
- `n`: Fire Damage when consuming an Endurance Charge
- `t`: small
- `sd`: ["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"]

```json
{"id":"1865","n":"Fire Damage when consuming an Endurance Charge","t":"small","sd":["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"],"out":["54934"]}
```

### 14. Fire Damage when consuming an Endurance Charge

- Match score: `115`
- `id`: 54934
- `n`: Fire Damage when consuming an Endurance Charge
- `t`: small
- `sd`: ["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"]

```json
{"id":"54934","n":"Fire Damage when consuming an Endurance Charge","t":"small","sd":["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"],"out":["15494"]}
```

### 15. Frenzy Charge Duration

- Match score: `115`
- `id`: 13341
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"13341","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["63255","56841","18451"]}
```

### 16. Frenzy Charge Duration

- Match score: `115`
- `id`: 18451
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"18451","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"]}
```

### 17. Frenzy Charge Duration

- Match score: `115`
- `id`: 24210
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"24210","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["26932"]}
```

### 18. Frenzy Charge Duration

- Match score: `115`
- `id`: 24295
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["25% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"24295","n":"Frenzy Charge Duration","t":"small","sd":["25% increased [Charges|Frenzy Charge] Duration"],"out":["37336"]}
```

### 19. Frenzy Charge Duration

- Match score: `115`
- `id`: 26932
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"26932","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["34543"]}
```

### 20. Frenzy Charge Duration

- Match score: `115`
- `id`: 35801
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["25% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"35801","n":"Frenzy Charge Duration","t":"small","sd":["25% increased [Charges|Frenzy Charge] Duration"],"out":["23508"]}
```

### 21. Frenzy Charge Duration

- Match score: `115`
- `id`: 41873
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"41873","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"]}
```

### 22. Frenzy Charge Duration

- Match score: `115`
- `id`: 55995
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"55995","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["41873"]}
```

### 23. Frenzy Charge Duration

- Match score: `115`
- `id`: 56841
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"56841","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["18451"]}
```

### 24. Frenzy Charge Duration

- Match score: `115`
- `id`: 57970
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"57970","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["55995","21537"]}
```

### 25. Infusion and Power Charge Duration

- Match score: `115`
- `id`: 44188
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"44188","n":"Infusion and Power Charge Duration","t":"small","sd":["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["64427"]}
```

### 26. Infusion and Power Charge Duration

- Match score: `115`
- `id`: 51892
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"51892","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["59387","64427","44188"]}
```

### 27. Infusion and Power Charge Duration

- Match score: `115`
- `id`: 64427
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"64427","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]}
```

### 28. Power Charge Duration

- Match score: `115`
- `id`: 24812
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"24812","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["64643"]}
```

### 29. Power Charge Duration

- Match score: `115`
- `id`: 56360
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"56360","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["24812"]}
```

### 30. Power Charge Duration

- Match score: `115`
- `id`: 64643
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"64643","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["56360","27176"]}
```

### 31. Power Charge Duration and Energy Shield

- Match score: `115`
- `id`: 13777
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"13777","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["38532"]}
```

### 32. Power Charge Duration and Energy Shield

- Match score: `115`
- `id`: 20791
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"20791","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["13777","11741"]}
```

### 33. Attack and Cast Speed on Critical

- Match score: `105`
- `id`: 20236
- `n`: Attack and Cast Speed on Critical
- `t`: small
- `sd`: ["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"]

```json
{"id":"20236","n":"Attack and Cast Speed on Critical","t":"small","sd":["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"],"out":["4346"]}
```

### 34. Attack Critical Damage

- Match score: `105`
- `id`: 19802
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"19802","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["64399"]}
```

### 35. Attack Critical Damage

- Match score: `105`
- `id`: 26176
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"26176","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["43650"]}
```

### 36. Attack Critical Damage

- Match score: `105`
- `id`: 2936
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"2936","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["13407"]}
```

### 37. Attack Critical Damage

- Match score: `105`
- `id`: 53386
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"53386","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["57388"]}
```

### 38. Attack Critical Damage

- Match score: `105`
- `id`: 64399
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"64399","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["2511"]}
```

### 39. Ballista Critical Damage

- Match score: `105`
- `id`: 56897
- `n`: Ballista Critical Damage
- `t`: small
- `sd`: ["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"56897","n":"Ballista Critical Damage","t":"small","sd":["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 40. Ballista Critical Strike and Damage

- Match score: `105`
- `id`: 63828
- `n`: Ballista Critical Strike and Damage
- `t`: small
- `sd`: ["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]

```json
{"id":"63828","n":"Ballista Critical Strike and Damage","t":"small","sd":["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]}
```

### 41. Bow Critical Damage

- Match score: `105`
- `id`: 25586
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"25586","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["38993"]}
```

### 42. Bow Critical Damage

- Match score: `105`
- `id`: 38993
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"38993","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["21112"]}
```

### 43. Critical Chance and Damage

- Match score: `105`
- `id`: 43650
- `n`: Critical Chance and Damage
- `t`: small
- `sd`: ["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"]

```json
{"id":"43650","n":"Critical Chance and Damage","t":"small","sd":["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"],"out":["21070","53386"]}
```

### 44. Critical Damage

- Match score: `105`
- `id`: 13419
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"13419","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["14958"]}
```

### 45. Critical Damage

- Match score: `105`
- `id`: 20024
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"20024","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["44223"]}
```

### 46. Critical Damage

- Match score: `105`
- `id`: 21779
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"21779","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["57204"]}
```

### 47. Critical Damage

- Match score: `105`
- `id`: 23040
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23040","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38493"]}
```

### 48. Critical Damage

- Match score: `105`
- `id`: 23915
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23915","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["41529"]}
```

### 49. Critical Damage

- Match score: `105`
- `id`: 28021
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28021","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["9782"]}
```

### 50. Critical Damage

- Match score: `105`
- `id`: 28223
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28223","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6100"]}
```

### 51. Critical Damage

- Match score: `105`
- `id`: 29959
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"29959","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6891","60362"]}
```

### 52. Critical Damage

- Match score: `105`
- `id`: 3458
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"3458","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["45609"]}
```

### 53. Critical Damage

- Match score: `105`
- `id`: 34621
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"34621","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38541"]}
```

### 54. Critical Damage

- Match score: `105`
- `id`: 36602
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"36602","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["18465"]}
```

### 55. Critical Damage

- Match score: `105`
- `id`: 38493
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"38493","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["55621"]}
```

### 56. Critical Damage

- Match score: `105`
- `id`: 39569
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"39569","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["35901","3458","7353"]}
```

### 57. Critical Damage

- Match score: `105`
- `id`: 41529
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41529","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["21380"]}
```

### 58. Critical Damage

- Match score: `105`
- `id`: 41665
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41665","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["50562"]}
```

### 59. Critical Damage

- Match score: `105`
- `id`: 44223
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"44223","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 60. Critical Damage

- Match score: `105`
- `id`: 45609
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"45609","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 61. Critical Damage

- Match score: `105`
- `id`: 535
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"535","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["34621"]}
```

### 62. Critical Damage

- Match score: `105`
- `id`: 55596
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"55596","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["8509"]}
```

### 63. Critical Damage

- Match score: `105`
- `id`: 55789
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"55789","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["41665"]}
```

### 64. Critical Damage

- Match score: `105`
- `id`: 59039
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"59039","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["28223"]}
```

### 65. Critical Damage

- Match score: `105`
- `id`: 59061
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"]

```json
{"id":"59061","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"],"out":["28267"]}
```

### 66. Critical Damage

- Match score: `105`
- `id`: 60362
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"60362","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["56265"]}
```

### 67. Critical Damage

- Match score: `105`
- `id`: 6100
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"6100","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["20963"]}
```

### 68. Critical Damage

- Match score: `105`
- `id`: 630
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"630","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["13419"]}
```

### 69. Critical Damage

- Match score: `105`
- `id`: 6891
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"6891","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["56265"]}
```

### 70. Critical Damage

- Match score: `105`
- `id`: 8509
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"]

```json
{"id":"8509","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"],"out":["59061"]}
```

### 71. Critical Damage

- Match score: `105`
- `id`: 9782
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"9782","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["20677"]}
```

### 72. Critical Damage Bonus on You

- Match score: `105`
- `id`: 25092
- `n`: Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 12% reduced [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"25092","n":"Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 12% reduced [CriticalDamageBonus|Critical Damage Bonus]"],"out":["34313"]}
```

### 73. Critical Damage vs Full Life

- Match score: `105`
- `id`: 52630
- `n`: Critical Damage vs Full Life
- `t`: small
- `sd`: ["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"]

```json
{"id":"52630","n":"Critical Damage vs Full Life","t":"small","sd":["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"],"out":["61800","28371"]}
```

### 74. Critical Damage vs Full Life

- Match score: `105`
- `id`: 61800
- `n`: Critical Damage vs Full Life
- `t`: small
- `sd`: ["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"]

```json
{"id":"61800","n":"Critical Damage vs Full Life","t":"small","sd":["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"]}
```

### 75. Dagger Critical Damage

- Match score: `105`
- `id`: 35755
- `n`: Dagger Critical Damage
- `t`: small
- `sd`: ["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"]

```json
{"id":"35755","n":"Dagger Critical Damage","t":"small","sd":["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"],"out":["54058"]}
```

### 76. Dagger Critical Damage

- Match score: `105`
- `id`: 54058
- `n`: Dagger Critical Damage
- `t`: small
- `sd`: ["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"]

```json
{"id":"54058","n":"Dagger Critical Damage","t":"small","sd":["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"],"out":["62001"]}
```

### 77. Damage and Criticals vs Dazed Enemies

- Match score: `105`
- `id`: 21945
- `n`: Damage and Criticals vs Dazed Enemies
- `t`: small
- `sd`: ["5% chance to [Daze] on [HitDamage|Hit]"]

```json
{"id":"21945","n":"Damage and Criticals vs Dazed Enemies","t":"small","sd":["5% chance to [Daze] on [HitDamage|Hit]"],"out":["61718","26572","39128","54545"]}
```

### 78. Damage on Critical

- Match score: `105`
- `id`: 4519
- `n`: Damage on Critical
- `t`: small
- `sd`: ["10% increased Damage if you've dealt a [Critical|Critical Hit] [Recently]"]

```json
{"id":"4519","n":"Damage on Critical","t":"small","sd":["10% increased Damage if you've dealt a [Critical|Critical Hit] [Recently]"],"out":["13724"]}
```

### 79. Gain Maximum Endurance Charges on Gaining Endurance Charge

- Match score: `105`
- `id`: 12601
- `n`: Gain Maximum Endurance Charges on Gaining Endurance Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]

```json
{"id":"12601","n":"Gain Maximum Endurance Charges on Gaining Endurance Charge","t":"small","sd":["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"],"out":["50908","35745"]}
```

### 80. Gain Maximum Endurance Charges on Gaining Endurance Charge

- Match score: `105`
- `id`: 35745
- `n`: Gain Maximum Endurance Charges on Gaining Endurance Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]

```json
{"id":"35745","n":"Gain Maximum Endurance Charges on Gaining Endurance Charge","t":"small","sd":["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]}
```

### 81. Gain Maximum Endurance Charges on Gaining Endurance Charge

- Match score: `105`
- `id`: 483
- `n`: Gain Maximum Endurance Charges on Gaining Endurance Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]

```json
{"id":"483","n":"Gain Maximum Endurance Charges on Gaining Endurance Charge","t":"small","sd":["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"],"out":["12601","35745"]}
```

### 82. Gain Maximum Frenzy Charges on Gaining Frenzy Charge

- Match score: `105`
- `id`: 25058
- `n`: Gain Maximum Frenzy Charges on Gaining Frenzy Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"]

```json
{"id":"25058","n":"Gain Maximum Frenzy Charges on Gaining Frenzy Charge","t":"small","sd":["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"],"out":["48828","4681"]}
```

### 83. Gain Maximum Frenzy Charges on Gaining Frenzy Charge

- Match score: `105`
- `id`: 4681
- `n`: Gain Maximum Frenzy Charges on Gaining Frenzy Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"]

```json
{"id":"4681","n":"Gain Maximum Frenzy Charges on Gaining Frenzy Charge","t":"small","sd":["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"],"out":["48828","26228"]}
```

### 84. Gain Maximum Frenzy Charges on Gaining Frenzy Charge

- Match score: `105`
- `id`: 48828
- `n`: Gain Maximum Frenzy Charges on Gaining Frenzy Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"]

```json
{"id":"48828","n":"Gain Maximum Frenzy Charges on Gaining Frenzy Charge","t":"small","sd":["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"],"out":["34840"]}
```

### 85. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `105`
- `id`: 13228
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"13228","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["43486"]}
```

### 86. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `105`
- `id`: 39102
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"39102","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["13228"]}
```

### 87. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `105`
- `id`: 43486
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"43486","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["54289","39102"]}
```

### 88. Invocation Critical Damage

- Match score: `105`
- `id`: 16024
- `n`: Invocation Critical Damage
- `t`: small
- `sd`: ["[Invoke|Invocation] [Spell|Spells] have 20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"16024","n":"Invocation Critical Damage","t":"small","sd":["[Invoke|Invocation] [Spell|Spells] have 20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["29288"]}
```

### 89. Minion Critical Damage

- Match score: `105`
- `id`: 34199
- `n`: Minion Critical Damage
- `t`: small
- `sd`: ["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"34199","n":"Minion Critical Damage","t":"small","sd":["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 90. Minion Critical Damage

- Match score: `105`
- `id`: 43557
- `n`: Minion Critical Damage
- `t`: small
- `sd`: ["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"43557","n":"Minion Critical Damage","t":"small","sd":["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 91. Physical Damage and Critical Chance

- Match score: `105`
- `id`: 1599
- `n`: Physical Damage and Critical Chance
- `t`: small
- `sd`: ["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"]

```json
{"id":"1599","n":"Physical Damage and Critical Chance","t":"small","sd":["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"],"out":["31286"]}
```

### 92. Physical Damage and Critical Chance

- Match score: `105`
- `id`: 35173
- `n`: Physical Damage and Critical Chance
- `t`: small
- `sd`: ["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"]

```json
{"id":"35173","n":"Physical Damage and Critical Chance","t":"small","sd":["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"],"out":["1599"]}
```

### 93. Quarterstaff Critical Damage

- Match score: `105`
- `id`: 52399
- `n`: Quarterstaff Critical Damage
- `t`: small
- `sd`: ["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"]

```json
{"id":"52399","n":"Quarterstaff Critical Damage","t":"small","sd":["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"],"out":["9444"]}
```

### 94. Quarterstaff Critical Damage

- Match score: `105`
- `id`: 59694
- `n`: Quarterstaff Critical Damage
- `t`: small
- `sd`: ["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"]

```json
{"id":"59694","n":"Quarterstaff Critical Damage","t":"small","sd":["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"],"out":["52399"]}
```

### 95. Spell Critical Damage

- Match score: `105`
- `id`: 1143
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"1143","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["58170","50084"]}
```

### 96. Spell Critical Damage

- Match score: `105`
- `id`: 15618
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"15618","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["57710"]}
```

### 97. Spell Critical Damage

- Match score: `105`
- `id`: 26682
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"26682","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["3472","56640"]}
```

### 98. Spell Critical Damage

- Match score: `105`
- `id`: 2672
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"2672","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["45569"]}
```

### 99. Spell Critical Damage

- Match score: `105`
- `id`: 32054
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"32054","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["62153"]}
```

### 100. Spell Critical Damage

- Match score: `105`
- `id`: 45569
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"45569","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["55596"]}
```

### 101. Spell Critical Damage

- Match score: `105`
- `id`: 48821
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"48821","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["15618"]}
```

### 102. Spell Critical Damage

- Match score: `105`
- `id`: 56640
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"56640","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["10398"]}
```

### 103. Spell Critical Damage

- Match score: `105`
- `id`: 61067
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"61067","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]}
```

### 104. Spell Critical Damage

- Match score: `105`
- `id`: 62153
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"62153","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["55947"]}
```

### 105. Strength and Critical Damage Bonus on You

- Match score: `105`
- `id`: 25458
- `n`: Strength and Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"]

```json
{"id":"25458","n":"Strength and Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"],"out":["37568"]}
```

### 106. Strength and Critical Damage Bonus on You

- Match score: `105`
- `id`: 34853
- `n`: Strength and Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"]

```json
{"id":"34853","n":"Strength and Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"],"out":["25458","43044"]}
```

### 107. Strength and Critical Damage Bonus on You

- Match score: `105`
- `id`: 37568
- `n`: Strength and Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"]

```json
{"id":"37568","n":"Strength and Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"],"out":["45370"]}
```

### 108. Thorn Critical Damage

- Match score: `105`
- `id`: 14459
- `n`: Thorn Critical Damage
- `t`: small
- `sd`: ["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"14459","n":"Thorn Critical Damage","t":"small","sd":["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"],"out":["5544"]}
```

### 109. Thorn Critical Damage

- Match score: `105`
- `id`: 5544
- `n`: Thorn Critical Damage
- `t`: small
- `sd`: ["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"5544","n":"Thorn Critical Damage","t":"small","sd":["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"],"out":["43711"]}
```

### 110. Charge Duration

- Match score: `90`
- `id`: 19027
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"19027","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["21156","7847"]}
```

### 111. Charge Duration

- Match score: `90`
- `id`: 21156
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"21156","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["34623"]}
```

### 112. Charge Duration and Dexterity

- Match score: `90`
- `id`: 34623
- `n`: Charge Duration and Dexterity
- `t`: small
- `sd`: ["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"]

```json
{"id":"34623","n":"Charge Duration and Dexterity","t":"small","sd":["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"],"out":["14769","14262"]}
```

### 113. Additional Power Charge Chance

- Match score: `80`
- `id`: 36643
- `n`: Additional Power Charge Chance
- `t`: small
- `sd`: ["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"]

```json
{"id":"36643","n":"Additional Power Charge Chance","t":"small","sd":["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"],"out":["1739"]}
```

### 114. Arcane Surge on Critical Hit

- Match score: `80`
- `id`: 2244
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"2244","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]}
```

### 115. Arcane Surge on Critical Hit

- Match score: `80`
- `id`: 54067
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"54067","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"],"out":["27626","2244"]}
```

### 116. Armour if Consumed Endurance Charge

- Match score: `80`
- `id`: 19122
- `n`: Armour if Consumed Endurance Charge
- `t`: small
- `sd`: ["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"19122","n":"Armour if Consumed Endurance Charge","t":"small","sd":["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["28432"]}
```

### 117. Armour if Consumed Endurance Charge

- Match score: `80`
- `id`: 23062
- `n`: Armour if Consumed Endurance Charge
- `t`: small
- `sd`: ["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"23062","n":"Armour if Consumed Endurance Charge","t":"small","sd":["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["19122"]}
```

### 118. Armour if Consumed Endurance Charge

- Match score: `80`
- `id`: 28432
- `n`: Armour if Consumed Endurance Charge
- `t`: small
- `sd`: ["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"28432","n":"Armour if Consumed Endurance Charge","t":"small","sd":["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["20416","23062"]}
```

### 119. Critical Overload

- Match score: `80`
- `id`: 5501
- `n`: Critical Overload
- `t`: notable
- `sd`: ["15% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"5501","n":"Critical Overload","t":"notable","sd":["15% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["48821"]}
```

### 120. Critical Strike

- Match score: `80`
- `id`: 9294
- `n`: Critical Strike
- `t`: notable
- `sd`: ["Chance to [HitDamage|Hit] with [Attack|Attacks] can [ExceedChance|exceed 100%]\nGain additional [Critical|Critical Hit] Chance equal to 25% of excess chance to [HitDamage|Hit] with [Attack|Attacks]"]

```json
{"id":"9294","n":"Critical Strike","t":"notable","sd":["Chance to [HitDamage|Hit] with [Attack|Attacks] can [ExceedChance|exceed 100%]\nGain additional [Critical|Critical Hit] Chance equal to 25% of excess chance to [HitDamage|Hit] with [Attack|Attacks]"],"out":["528"]}
```

## Passive full compact

- Source: `build_knowledge/compact/passive_tree_full_compact.json`
- Matches included: `120`

### 1. Critical Damage when consuming a Power Charge

- Match score: `185`
- `id`: 30615
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"30615","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]}
```

### 2. Critical Damage when consuming a Power Charge

- Match score: `185`
- `id`: 3336
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"3336","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["30615"]}
```

### 3. Critical Damage when consuming a Power Charge

- Match score: `185`
- `id`: 36231
- `n`: Critical Damage when consuming a Power Charge
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"]

```json
{"id":"36231","n":"Critical Damage when consuming a Power Charge","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]"],"out":["3336","31765"]}
```

### 4. Archon Duration and Critical Damage

- Match score: `140`
- `id`: 23436
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"23436","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["29197"]}
```

### 5. Archon Duration and Critical Damage

- Match score: `140`
- `id`: 26300
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"26300","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["23436"]}
```

### 6. Archon Duration and Critical Damage

- Match score: `140`
- `id`: 29197
- `n`: Archon Duration and Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"]

```json
{"id":"29197","n":"Archon Duration and Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Archon] Buff duration"],"out":["11428"]}
```

### 7. Endurance Charge Duration

- Match score: `115`
- `id`: 21390
- `n`: Endurance Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Endurance Charge] Duration"]

```json
{"id":"21390","n":"Endurance Charge Duration","t":"small","sd":["20% increased [Charges|Endurance Charge] Duration"],"out":["7972"]}
```

### 8. Endurance Charge Duration

- Match score: `115`
- `id`: 25229
- `n`: Endurance Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Endurance Charge] Duration"]

```json
{"id":"25229","n":"Endurance Charge Duration","t":"small","sd":["20% increased [Charges|Endurance Charge] Duration"],"out":["21390"]}
```

### 9. Endurance Charge Duration

- Match score: `115`
- `id`: 7972
- `n`: Endurance Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Endurance Charge] Duration"]

```json
{"id":"7972","n":"Endurance Charge Duration","t":"small","sd":["20% increased [Charges|Endurance Charge] Duration"],"out":["25229","5663"]}
```

### 10. Endurance Charge Duration and Armour

- Match score: `115`
- `id`: 11027
- `n`: Endurance Charge Duration and Armour
- `t`: small
- `sd`: ["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"11027","n":"Endurance Charge Duration and Armour","t":"small","sd":["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["59433"]}
```

### 11. Endurance Charge Duration and Armour

- Match score: `115`
- `id`: 41701
- `n`: Endurance Charge Duration and Armour
- `t`: small
- `sd`: ["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"41701","n":"Endurance Charge Duration and Armour","t":"small","sd":["10% increased [Charges|Endurance Charge] Duration","10% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["11741","11027"]}
```

### 12. Fire Damage when consuming an Endurance Charge

- Match score: `115`
- `id`: 15494
- `n`: Fire Damage when consuming an Endurance Charge
- `t`: small
- `sd`: ["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"]

```json
{"id":"15494","n":"Fire Damage when consuming an Endurance Charge","t":"small","sd":["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"],"out":["1865","43584"]}
```

### 13. Fire Damage when consuming an Endurance Charge

- Match score: `115`
- `id`: 1865
- `n`: Fire Damage when consuming an Endurance Charge
- `t`: small
- `sd`: ["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"]

```json
{"id":"1865","n":"Fire Damage when consuming an Endurance Charge","t":"small","sd":["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"],"out":["54934"]}
```

### 14. Fire Damage when consuming an Endurance Charge

- Match score: `115`
- `id`: 54934
- `n`: Fire Damage when consuming an Endurance Charge
- `t`: small
- `sd`: ["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"]

```json
{"id":"54934","n":"Fire Damage when consuming an Endurance Charge","t":"small","sd":["3% increased [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]"],"out":["15494"]}
```

### 15. Frenzy Charge Duration

- Match score: `115`
- `id`: 13341
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"13341","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["63255","56841","18451"]}
```

### 16. Frenzy Charge Duration

- Match score: `115`
- `id`: 18451
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"18451","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"]}
```

### 17. Frenzy Charge Duration

- Match score: `115`
- `id`: 24210
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"24210","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["26932"]}
```

### 18. Frenzy Charge Duration

- Match score: `115`
- `id`: 24295
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["25% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"24295","n":"Frenzy Charge Duration","t":"small","sd":["25% increased [Charges|Frenzy Charge] Duration"],"out":["37336"]}
```

### 19. Frenzy Charge Duration

- Match score: `115`
- `id`: 26932
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"26932","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["34543"]}
```

### 20. Frenzy Charge Duration

- Match score: `115`
- `id`: 35801
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["25% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"35801","n":"Frenzy Charge Duration","t":"small","sd":["25% increased [Charges|Frenzy Charge] Duration"],"out":["23508"]}
```

### 21. Frenzy Charge Duration

- Match score: `115`
- `id`: 41873
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"41873","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"]}
```

### 22. Frenzy Charge Duration

- Match score: `115`
- `id`: 55995
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"55995","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["41873"]}
```

### 23. Frenzy Charge Duration

- Match score: `115`
- `id`: 56841
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"56841","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["18451"]}
```

### 24. Frenzy Charge Duration

- Match score: `115`
- `id`: 57970
- `n`: Frenzy Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Frenzy Charge] Duration"]

```json
{"id":"57970","n":"Frenzy Charge Duration","t":"small","sd":["20% increased [Charges|Frenzy Charge] Duration"],"out":["55995","21537"]}
```

### 25. Infusion and Power Charge Duration

- Match score: `115`
- `id`: 44188
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"44188","n":"Infusion and Power Charge Duration","t":"small","sd":["8% increased [Charges|Power Charge] Duration","8% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["64427"]}
```

### 26. Infusion and Power Charge Duration

- Match score: `115`
- `id`: 51892
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"51892","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"],"out":["59387","64427","44188"]}
```

### 27. Infusion and Power Charge Duration

- Match score: `115`
- `id`: 64427
- `n`: Infusion and Power Charge Duration
- `t`: small
- `sd`: ["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]

```json
{"id":"64427","n":"Infusion and Power Charge Duration","t":"small","sd":["6% increased [Charges|Power Charge] Duration","6% increased [ElementalInfusion|Elemental Infusion] duration"]}
```

### 28. Power Charge Duration

- Match score: `115`
- `id`: 24812
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"24812","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["64643"]}
```

### 29. Power Charge Duration

- Match score: `115`
- `id`: 56360
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"56360","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["24812"]}
```

### 30. Power Charge Duration

- Match score: `115`
- `id`: 64643
- `n`: Power Charge Duration
- `t`: small
- `sd`: ["20% increased [Charges|Power Charge] Duration"]

```json
{"id":"64643","n":"Power Charge Duration","t":"small","sd":["20% increased [Charges|Power Charge] Duration"],"out":["56360","27176"]}
```

### 31. Power Charge Duration and Energy Shield

- Match score: `115`
- `id`: 13777
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"13777","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["38532"]}
```

### 32. Power Charge Duration and Energy Shield

- Match score: `115`
- `id`: 20791
- `n`: Power Charge Duration and Energy Shield
- `t`: small
- `sd`: ["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"]

```json
{"id":"20791","n":"Power Charge Duration and Energy Shield","t":"small","sd":["10% increased [Charges|Power Charge] Duration","10% increased maximum [EnergyShield|Energy Shield] if you've consumed a [Charges|Power Charge] [Recently|Recently]"],"out":["13777","11741"]}
```

### 33. Attack and Cast Speed on Critical

- Match score: `105`
- `id`: 20236
- `n`: Attack and Cast Speed on Critical
- `t`: small
- `sd`: ["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"]

```json
{"id":"20236","n":"Attack and Cast Speed on Critical","t":"small","sd":["3% increased [Attack] Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]","3% increased Cast Speed if you've dealt a [Critical|Critical Hit] [Recently|Recently]"],"out":["4346"]}
```

### 34. Attack Critical Damage

- Match score: `105`
- `id`: 19802
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"19802","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["64399"]}
```

### 35. Attack Critical Damage

- Match score: `105`
- `id`: 26176
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"26176","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["43650"]}
```

### 36. Attack Critical Damage

- Match score: `105`
- `id`: 2936
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"2936","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["13407"]}
```

### 37. Attack Critical Damage

- Match score: `105`
- `id`: 53386
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"53386","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["57388"]}
```

### 38. Attack Critical Damage

- Match score: `105`
- `id`: 64399
- `n`: Attack Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"]

```json
{"id":"64399","n":"Attack Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus] for [Attack] Damage"],"out":["2511"]}
```

### 39. Ballista Critical Damage

- Match score: `105`
- `id`: 56897
- `n`: Ballista Critical Damage
- `t`: small
- `sd`: ["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"56897","n":"Ballista Critical Damage","t":"small","sd":["10% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 40. Ballista Critical Strike and Damage

- Match score: `105`
- `id`: 63828
- `n`: Ballista Critical Strike and Damage
- `t`: small
- `sd`: ["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]

```json
{"id":"63828","n":"Ballista Critical Strike and Damage","t":"small","sd":["6% increased [Ballista] [CriticalDamageBonus|Critical Damage Bonus]","10% increased [Ballista] [Critical|Critical Hit Chance]"]}
```

### 41. Bow Critical Damage

- Match score: `105`
- `id`: 25586
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"25586","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["38993"]}
```

### 42. Bow Critical Damage

- Match score: `105`
- `id`: 38993
- `n`: Bow Critical Damage
- `t`: small
- `sd`: ["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"]

```json
{"id":"38993","n":"Bow Critical Damage","t":"small","sd":["16% increased [CriticalDamageBonus|Critical Damage Bonus] with Bows"],"out":["21112"]}
```

### 43. Critical Chance and Damage

- Match score: `105`
- `id`: 43650
- `n`: Critical Chance and Damage
- `t`: small
- `sd`: ["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"]

```json
{"id":"43650","n":"Critical Chance and Damage","t":"small","sd":["8% increased [CriticalDamageBonus|Critical Damage Bonus]","5% increased [Critical|Critical Hit Chance]"],"out":["21070","53386"]}
```

### 44. Critical Damage

- Match score: `105`
- `id`: 13419
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"13419","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["14958"]}
```

### 45. Critical Damage

- Match score: `105`
- `id`: 20024
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"20024","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["44223"]}
```

### 46. Critical Damage

- Match score: `105`
- `id`: 21779
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"21779","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["57204"]}
```

### 47. Critical Damage

- Match score: `105`
- `id`: 23040
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23040","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38493"]}
```

### 48. Critical Damage

- Match score: `105`
- `id`: 23915
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"23915","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["41529"]}
```

### 49. Critical Damage

- Match score: `105`
- `id`: 28021
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28021","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["9782"]}
```

### 50. Critical Damage

- Match score: `105`
- `id`: 28223
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"28223","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6100"]}
```

### 51. Critical Damage

- Match score: `105`
- `id`: 29959
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"29959","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["6891","60362"]}
```

### 52. Critical Damage

- Match score: `105`
- `id`: 3458
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"3458","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["45609"]}
```

### 53. Critical Damage

- Match score: `105`
- `id`: 34621
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"34621","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["38541"]}
```

### 54. Critical Damage

- Match score: `105`
- `id`: 36602
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"36602","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["18465"]}
```

### 55. Critical Damage

- Match score: `105`
- `id`: 38493
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"38493","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["55621"]}
```

### 56. Critical Damage

- Match score: `105`
- `id`: 39569
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"39569","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["35901","3458","7353"]}
```

### 57. Critical Damage

- Match score: `105`
- `id`: 41529
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41529","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["21380"]}
```

### 58. Critical Damage

- Match score: `105`
- `id`: 41665
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"41665","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["50562"]}
```

### 59. Critical Damage

- Match score: `105`
- `id`: 44223
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"44223","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 60. Critical Damage

- Match score: `105`
- `id`: 45609
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"45609","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 61. Critical Damage

- Match score: `105`
- `id`: 535
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"535","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["34621"]}
```

### 62. Critical Damage

- Match score: `105`
- `id`: 55596
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"55596","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["8509"]}
```

### 63. Critical Damage

- Match score: `105`
- `id`: 55789
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"55789","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["41665"]}
```

### 64. Critical Damage

- Match score: `105`
- `id`: 59039
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"59039","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["28223"]}
```

### 65. Critical Damage

- Match score: `105`
- `id`: 59061
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"]

```json
{"id":"59061","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"],"out":["28267"]}
```

### 66. Critical Damage

- Match score: `105`
- `id`: 60362
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"60362","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["56265"]}
```

### 67. Critical Damage

- Match score: `105`
- `id`: 6100
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"6100","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["20963"]}
```

### 68. Critical Damage

- Match score: `105`
- `id`: 630
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"630","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["13419"]}
```

### 69. Critical Damage

- Match score: `105`
- `id`: 6891
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"6891","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["56265"]}
```

### 70. Critical Damage

- Match score: `105`
- `id`: 8509
- `n`: Critical Damage
- `t`: small
- `sd`: ["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"]

```json
{"id":"8509","n":"Critical Damage","t":"small","sd":["20% increased [CriticalDamageBonus|Critical Damage Bonus] if you haven't dealt a [Critical|Critical Hit] [Recently]"],"out":["59061"]}
```

### 71. Critical Damage

- Match score: `105`
- `id`: 9782
- `n`: Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"9782","n":"Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["20677"]}
```

### 72. Critical Damage Bonus on You

- Match score: `105`
- `id`: 25092
- `n`: Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 12% reduced [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"25092","n":"Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 12% reduced [CriticalDamageBonus|Critical Damage Bonus]"],"out":["34313"]}
```

### 73. Critical Damage vs Full Life

- Match score: `105`
- `id`: 52630
- `n`: Critical Damage vs Full Life
- `t`: small
- `sd`: ["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"]

```json
{"id":"52630","n":"Critical Damage vs Full Life","t":"small","sd":["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"],"out":["61800","28371"]}
```

### 74. Critical Damage vs Full Life

- Match score: `105`
- `id`: 61800
- `n`: Critical Damage vs Full Life
- `t`: small
- `sd`: ["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"]

```json
{"id":"61800","n":"Critical Damage vs Full Life","t":"small","sd":["40% increased [CriticalDamageBonus|Critical Damage Bonus] against Enemies that are on Full Life"]}
```

### 75. Dagger Critical Damage

- Match score: `105`
- `id`: 35755
- `n`: Dagger Critical Damage
- `t`: small
- `sd`: ["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"]

```json
{"id":"35755","n":"Dagger Critical Damage","t":"small","sd":["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"],"out":["54058"]}
```

### 76. Dagger Critical Damage

- Match score: `105`
- `id`: 54058
- `n`: Dagger Critical Damage
- `t`: small
- `sd`: ["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"]

```json
{"id":"54058","n":"Dagger Critical Damage","t":"small","sd":["10% increased [CriticalDamageBonus|Critical Damage Bonus] with [Dagger|Daggers]"],"out":["62001"]}
```

### 77. Damage and Criticals vs Dazed Enemies

- Match score: `105`
- `id`: 21945
- `n`: Damage and Criticals vs Dazed Enemies
- `t`: small
- `sd`: ["5% chance to [Daze] on [HitDamage|Hit]"]

```json
{"id":"21945","n":"Damage and Criticals vs Dazed Enemies","t":"small","sd":["5% chance to [Daze] on [HitDamage|Hit]"],"out":["61718","26572","39128","54545"]}
```

### 78. Damage on Critical

- Match score: `105`
- `id`: 4519
- `n`: Damage on Critical
- `t`: small
- `sd`: ["10% increased Damage if you've dealt a [Critical|Critical Hit] [Recently]"]

```json
{"id":"4519","n":"Damage on Critical","t":"small","sd":["10% increased Damage if you've dealt a [Critical|Critical Hit] [Recently]"],"out":["13724"]}
```

### 79. Gain Maximum Endurance Charges on Gaining Endurance Charge

- Match score: `105`
- `id`: 12601
- `n`: Gain Maximum Endurance Charges on Gaining Endurance Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]

```json
{"id":"12601","n":"Gain Maximum Endurance Charges on Gaining Endurance Charge","t":"small","sd":["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"],"out":["50908","35745"]}
```

### 80. Gain Maximum Endurance Charges on Gaining Endurance Charge

- Match score: `105`
- `id`: 35745
- `n`: Gain Maximum Endurance Charges on Gaining Endurance Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]

```json
{"id":"35745","n":"Gain Maximum Endurance Charges on Gaining Endurance Charge","t":"small","sd":["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]}
```

### 81. Gain Maximum Endurance Charges on Gaining Endurance Charge

- Match score: `105`
- `id`: 483
- `n`: Gain Maximum Endurance Charges on Gaining Endurance Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"]

```json
{"id":"483","n":"Gain Maximum Endurance Charges on Gaining Endurance Charge","t":"small","sd":["2% chance that if you would gain [Charges|Endurance Charges], you instead gain up to maximum [Charges|Endurance Charges]"],"out":["12601","35745"]}
```

### 82. Gain Maximum Frenzy Charges on Gaining Frenzy Charge

- Match score: `105`
- `id`: 25058
- `n`: Gain Maximum Frenzy Charges on Gaining Frenzy Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"]

```json
{"id":"25058","n":"Gain Maximum Frenzy Charges on Gaining Frenzy Charge","t":"small","sd":["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"],"out":["48828","4681"]}
```

### 83. Gain Maximum Frenzy Charges on Gaining Frenzy Charge

- Match score: `105`
- `id`: 4681
- `n`: Gain Maximum Frenzy Charges on Gaining Frenzy Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"]

```json
{"id":"4681","n":"Gain Maximum Frenzy Charges on Gaining Frenzy Charge","t":"small","sd":["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"],"out":["48828","26228"]}
```

### 84. Gain Maximum Frenzy Charges on Gaining Frenzy Charge

- Match score: `105`
- `id`: 48828
- `n`: Gain Maximum Frenzy Charges on Gaining Frenzy Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"]

```json
{"id":"48828","n":"Gain Maximum Frenzy Charges on Gaining Frenzy Charge","t":"small","sd":["2% chance that if you would gain [Charges|Frenzy Charges], you instead gain up to your maximum number of [Charges|Frenzy Charges]"],"out":["34840"]}
```

### 85. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `105`
- `id`: 13228
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"13228","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["43486"]}
```

### 86. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `105`
- `id`: 39102
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"39102","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["13228"]}
```

### 87. Gain Maximum Power Charges on Gaining Power Charge

- Match score: `105`
- `id`: 43486
- `n`: Gain Maximum Power Charges on Gaining Power Charge
- `t`: small
- `sd`: ["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"]

```json
{"id":"43486","n":"Gain Maximum Power Charges on Gaining Power Charge","t":"small","sd":["2% chance that if you would gain [Charges|Power Charges], you instead gain up to\nyour maximum number of [Charges|Power Charges]"],"out":["54289","39102"]}
```

### 88. Invocation Critical Damage

- Match score: `105`
- `id`: 16024
- `n`: Invocation Critical Damage
- `t`: small
- `sd`: ["[Invoke|Invocation] [Spell|Spells] have 20% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"16024","n":"Invocation Critical Damage","t":"small","sd":["[Invoke|Invocation] [Spell|Spells] have 20% increased [CriticalDamageBonus|Critical Damage Bonus]"],"out":["29288"]}
```

### 89. Minion Critical Damage

- Match score: `105`
- `id`: 34199
- `n`: Minion Critical Damage
- `t`: small
- `sd`: ["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"34199","n":"Minion Critical Damage","t":"small","sd":["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 90. Minion Critical Damage

- Match score: `105`
- `id`: 43557
- `n`: Minion Critical Damage
- `t`: small
- `sd`: ["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"43557","n":"Minion Critical Damage","t":"small","sd":["[Minion|Minions] have 15% increased [CriticalDamageBonus|Critical Damage Bonus]"]}
```

### 91. Physical Damage and Critical Chance

- Match score: `105`
- `id`: 1599
- `n`: Physical Damage and Critical Chance
- `t`: small
- `sd`: ["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"]

```json
{"id":"1599","n":"Physical Damage and Critical Chance","t":"small","sd":["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"],"out":["31286"]}
```

### 92. Physical Damage and Critical Chance

- Match score: `105`
- `id`: 35173
- `n`: Physical Damage and Critical Chance
- `t`: small
- `sd`: ["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"]

```json
{"id":"35173","n":"Physical Damage and Critical Chance","t":"small","sd":["5% increased [Critical|Critical Hit Chance]","8% increased [Physical] Damage"],"out":["1599"]}
```

### 93. Quarterstaff Critical Damage

- Match score: `105`
- `id`: 52399
- `n`: Quarterstaff Critical Damage
- `t`: small
- `sd`: ["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"]

```json
{"id":"52399","n":"Quarterstaff Critical Damage","t":"small","sd":["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"],"out":["9444"]}
```

### 94. Quarterstaff Critical Damage

- Match score: `105`
- `id`: 59694
- `n`: Quarterstaff Critical Damage
- `t`: small
- `sd`: ["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"]

```json
{"id":"59694","n":"Quarterstaff Critical Damage","t":"small","sd":["18% increased [CriticalDamageBonus|Critical Damage Bonus] with [Quarterstaff|Quarterstaves]"],"out":["52399"]}
```

### 95. Spell Critical Damage

- Match score: `105`
- `id`: 1143
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"1143","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["58170","50084"]}
```

### 96. Spell Critical Damage

- Match score: `105`
- `id`: 15618
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"15618","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["57710"]}
```

### 97. Spell Critical Damage

- Match score: `105`
- `id`: 26682
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"26682","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["3472","56640"]}
```

### 98. Spell Critical Damage

- Match score: `105`
- `id`: 2672
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"2672","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["45569"]}
```

### 99. Spell Critical Damage

- Match score: `105`
- `id`: 32054
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"32054","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["62153"]}
```

### 100. Spell Critical Damage

- Match score: `105`
- `id`: 45569
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"45569","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["55596"]}
```

### 101. Spell Critical Damage

- Match score: `105`
- `id`: 48821
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"48821","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["15618"]}
```

### 102. Spell Critical Damage

- Match score: `105`
- `id`: 56640
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"56640","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["10398"]}
```

### 103. Spell Critical Damage

- Match score: `105`
- `id`: 61067
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"61067","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]}
```

### 104. Spell Critical Damage

- Match score: `105`
- `id`: 62153
- `n`: Spell Critical Damage
- `t`: small
- `sd`: ["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"62153","n":"Spell Critical Damage","t":"small","sd":["15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["55947"]}
```

### 105. Strength and Critical Damage Bonus on You

- Match score: `105`
- `id`: 25458
- `n`: Strength and Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"]

```json
{"id":"25458","n":"Strength and Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"],"out":["37568"]}
```

### 106. Strength and Critical Damage Bonus on You

- Match score: `105`
- `id`: 34853
- `n`: Strength and Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"]

```json
{"id":"34853","n":"Strength and Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"],"out":["25458","43044"]}
```

### 107. Strength and Critical Damage Bonus on You

- Match score: `105`
- `id`: 37568
- `n`: Strength and Critical Damage Bonus on You
- `t`: small
- `sd`: ["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"]

```json
{"id":"37568","n":"Strength and Critical Damage Bonus on You","t":"small","sd":["[HitDamage|Hits] against you have 5% reduced [CriticalDamageBonus|Critical Damage Bonus]","+5 to [Strength]"],"out":["45370"]}
```

### 108. Thorn Critical Damage

- Match score: `105`
- `id`: 14459
- `n`: Thorn Critical Damage
- `t`: small
- `sd`: ["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"14459","n":"Thorn Critical Damage","t":"small","sd":["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"],"out":["5544"]}
```

### 109. Thorn Critical Damage

- Match score: `105`
- `id`: 5544
- `n`: Thorn Critical Damage
- `t`: small
- `sd`: ["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"]

```json
{"id":"5544","n":"Thorn Critical Damage","t":"small","sd":["30% increased [Thorns|Thorns] [CriticalDamageBonus|Critical Damage Bonus]"],"out":["43711"]}
```

### 110. Charge Duration

- Match score: `90`
- `id`: 19027
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"19027","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["21156","7847"]}
```

### 111. Charge Duration

- Match score: `90`
- `id`: 21156
- `n`: Charge Duration
- `t`: small
- `sd`: ["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"]

```json
{"id":"21156","n":"Charge Duration","t":"small","sd":["15% increased [Charges|Endurance, Frenzy and Power Charge] Duration"],"out":["34623"]}
```

### 112. Charge Duration and Dexterity

- Match score: `90`
- `id`: 34623
- `n`: Charge Duration and Dexterity
- `t`: small
- `sd`: ["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"]

```json
{"id":"34623","n":"Charge Duration and Dexterity","t":"small","sd":["10% increased [Charges|Endurance, Frenzy and Power Charge] Duration","+5 to [Dexterity]"],"out":["14769","14262"]}
```

### 113. Additional Power Charge Chance

- Match score: `80`
- `id`: 36643
- `n`: Additional Power Charge Chance
- `t`: small
- `sd`: ["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"]

```json
{"id":"36643","n":"Additional Power Charge Chance","t":"small","sd":["10% chance when you gain a [Charges|Power Charge] to gain an additional [Charges|Power Charge]"],"out":["1739"]}
```

### 114. Arcane Surge on Critical Hit

- Match score: `80`
- `id`: 2244
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"2244","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]}
```

### 115. Arcane Surge on Critical Hit

- Match score: `80`
- `id`: 54067
- `n`: Arcane Surge on Critical Hit
- `t`: small
- `sd`: ["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"]

```json
{"id":"54067","n":"Arcane Surge on Critical Hit","t":"small","sd":["5% chance to Gain [ArcaneSurgeDuration|Arcane Surge] when you deal a [Critical|Critical Hit]"],"out":["27626","2244"]}
```

### 116. Armour if Consumed Endurance Charge

- Match score: `80`
- `id`: 19122
- `n`: Armour if Consumed Endurance Charge
- `t`: small
- `sd`: ["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"19122","n":"Armour if Consumed Endurance Charge","t":"small","sd":["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["28432"]}
```

### 117. Armour if Consumed Endurance Charge

- Match score: `80`
- `id`: 23062
- `n`: Armour if Consumed Endurance Charge
- `t`: small
- `sd`: ["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"23062","n":"Armour if Consumed Endurance Charge","t":"small","sd":["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["19122"]}
```

### 118. Armour if Consumed Endurance Charge

- Match score: `80`
- `id`: 28432
- `n`: Armour if Consumed Endurance Charge
- `t`: small
- `sd`: ["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"]

```json
{"id":"28432","n":"Armour if Consumed Endurance Charge","t":"small","sd":["20% increased [Armour] if you've consumed an [Charges|Endurance Charge] [Recently]"],"out":["20416","23062"]}
```

### 119. Critical Overload

- Match score: `80`
- `id`: 5501
- `n`: Critical Overload
- `t`: notable
- `sd`: ["15% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"]

```json
{"id":"5501","n":"Critical Overload","t":"notable","sd":["15% increased [Critical|Critical Hit Chance] for [Spell|Spells]","15% increased [CriticalDamageBonus|Critical Spell Damage Bonus]"],"out":["48821"]}
```

### 120. Critical Strike

- Match score: `80`
- `id`: 9294
- `n`: Critical Strike
- `t`: notable
- `sd`: ["Chance to [HitDamage|Hit] with [Attack|Attacks] can [ExceedChance|exceed 100%]\nGain additional [Critical|Critical Hit] Chance equal to 25% of excess chance to [HitDamage|Hit] with [Attack|Attacks]"]

```json
{"id":"9294","n":"Critical Strike","t":"notable","sd":["Chance to [HitDamage|Hit] with [Attack|Attacks] can [ExceedChance|exceed 100%]\nGain additional [Critical|Critical Hit] Chance equal to 25% of excess chance to [HitDamage|Hit] with [Attack|Attacks]"],"out":["528"]}
```

## Passive edges

- Source: `build_knowledge/compact/passive_tree_edges.json`
- Matches included: `0`

_No keyword matches in this index._

## Gems and skills

- Source: `build_knowledge/compact/gem_index.json`
- Matches included: `120`

### 1. [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]

- Match score: `105`
- `k`: inflict_exposure_for_x_ms_on_cold_crit
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"inflict_exposure_for_x_ms_on_cold_crit","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ExposureDuration', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}, {'flags': 0, 'keywordFlags': 0, 'name': 'InflictExposure', 'type': 'FLAG', 'value': True, '1': {'type': 'Condition', 'var': 'CritInPast8Sec'}, '2': {'type': 'Condition', 'var': 'ColdHasDamage'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ExposureDuration","type":"BASE","1":{"type":"Condition","var":"CritInPast8Sec"},"2":{"type":"Condition","var":"ColdHasDamage"}},{"flags":0,"keywordFlags":0,"name":"InflictExposure","type":"FLAG","value":true,"1":{"type":"Condition","var":"CritInPast8Sec"},"2":{"type":"Condition","var":"ColdHasDamage"}}]}
```

### 2. GAHarborBossChargeStompFire

- Match score: `105`
- `k`: GAHarborBossChargeStompFire
- `n`: GAHarborBossChargeStompFire
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAHarborBossChargeStompFire","n":"GAHarborBossChargeStompFire","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 3. SupportIncreasedCriticalDamagePlayer

- Match score: `105`
- `k`: SupportIncreasedCriticalDamagePlayer
- `n`: SupportIncreasedCriticalDamagePlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":null,"allowed_types":["Damage","Attack","CrossbowAmmoSkill"],"excluded_types":null,"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportIncreasedCriticalDamagePlayer","n":"SupportIncreasedCriticalDamagePlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":null,"allowed_types":["Damage","Attack","CrossbowAmmoSkill"],"excluded_types":null,"letter":"","supports_gems_only":false},"is_support":true}
```

### 4. SupportBlazingCriticalPlayer

- Match score: `90`
- `k`: SupportBlazingCriticalPlayer
- `n`: SupportBlazingCriticalPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":["Duration"],"allowed_types":["Attack","Damage","CrossbowAmmoSkill"],"excluded_types":["UsedByProxy","Triggered","Persistent"],"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportBlazingCriticalPlayer","n":"SupportBlazingCriticalPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":["Duration"],"allowed_types":["Attack","Damage","CrossbowAmmoSkill"],"excluded_types":["UsedByProxy","Triggered","Persistent"],"letter":"","supports_gems_only":false},"is_support":true}
```

### 5. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `80`
- `k`: critical_strike_chance_+%_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 6. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `80`
- `k`: critical_strike_multiplier_+_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_multiplier_+_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritMultiplier","type":"BASE","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 7. [{'flags': 0, 'keywordFlags': 4096, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `80`
- `k`: trap_critical_strike_multiplier_+_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 4096, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"trap_critical_strike_multiplier_+_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 4096, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":4096,"name":"CritMultiplier","type":"BASE","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 8. [{'flags': 0, 'keywordFlags': 8192, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `80`
- `k`: mine_critical_strike_chance_+%_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 8192, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"mine_critical_strike_chance_+%_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 8192, 'name': 'CritChance', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":8192,"name":"CritChance","type":"INC","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 9. Blazing Critical

- Match score: `80`
- `k`: Metadata/Items/Gems/SkillGemBlazingCriticalSupport
- `n`: Blazing Critical
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"attack":true,"duration":true,"fire":true,"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemBlazingCriticalSupport","n":"Blazing Critical","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"attack":true,"duration":true,"fire":true,"support":true}}
```

### 10. Metadata/Items/Gems/SupportGemBlazingCritical

- Match score: `80`
- `k`: Metadata/Items/Gems/SupportGemBlazingCritical
- `n`: Metadata/Items/Gems/SupportGemBlazingCritical
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support","attack","fire","duration"]
- `base`: {"display_name":"Blazing Critical","id":"Metadata/Items/Gems/SupportGemBlazingCritical","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemBlazingCritical","n":"Metadata/Items/Gems/SupportGemBlazingCritical","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Blazing Critical","id":"Metadata/Items/Gems/SupportGemBlazingCritical","release_state":"released"},"tags":["support","attack","fire","duration"]}
```

### 11. Supercritical

- Match score: `80`
- `k`: Metadata/Items/Gems/SkillGemIncreasedCriticalDamageSupport
- `n`: Supercritical
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemIncreasedCriticalDamageSupport","n":"Supercritical","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 12. SupportInevitableCriticalsPlayer

- Match score: `80`
- `k`: SupportInevitableCriticalsPlayer
- `n`: SupportInevitableCriticalsPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":null,"allowed_types":["Attack","Damage","CrossbowAmmoSkill"],"excluded_types":["UsedByProxy","Triggered","Persistent"],"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportInevitableCriticalsPlayer","n":"SupportInevitableCriticalsPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":null,"allowed_types":["Attack","Damage","CrossbowAmmoSkill"],"excluded_types":["UsedByProxy","Triggered","Persistent"],"letter":"","supports_gems_only":false},"is_support":true}
```

### 13. SupportInevitableCriticalsPlayerTwo

- Match score: `80`
- `k`: SupportInevitableCriticalsPlayerTwo
- `n`: SupportInevitableCriticalsPlayerTwo
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":null,"allowed_types":["Attack","Damage","CrossbowAmmoSkill"],"excluded_types":["UsedByProxy","Triggered","Persistent"],"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportInevitableCriticalsPlayerTwo","n":"SupportInevitableCriticalsPlayerTwo","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":null,"allowed_types":["Attack","Damage","CrossbowAmmoSkill"],"excluded_types":["UsedByProxy","Triggered","Persistent"],"letter":"","supports_gems_only":false},"is_support":true}
```

### 14. SupportPinpointCriticalPlayer

- Match score: `80`
- `k`: SupportPinpointCriticalPlayer
- `n`: SupportPinpointCriticalPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":null,"allowed_types":["Damage","Attack","CrossbowAmmoSkill"],"excluded_types":null,"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportPinpointCriticalPlayer","n":"SupportPinpointCriticalPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":null,"allowed_types":["Damage","Attack","CrossbowAmmoSkill"],"excluded_types":null,"letter":"","supports_gems_only":false},"is_support":true}
```

### 15. [{'flags': 0, 'keywordFlags': 0, 'name': 'Condition:CannotConsumeCharges', 'type': 'FLAG', 'value': True}]

- Match score: `70`
- `k`: cannot_consume_power_frenzy_endurance_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Condition:CannotConsumeCharges', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"cannot_consume_power_frenzy_endurance_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Condition:CannotConsumeCharges', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Condition:CannotConsumeCharges","type":"FLAG","value":true}]}
```

### 16. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}, '2': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}, '3': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovablePowerCharge'}}]

- Match score: `70`
- `k`: discharge_damage_+%_if_3_charge_types_removed
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}, '2': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}, '3': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovablePowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"discharge_damage_+%_if_3_charge_types_removed","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}, '2': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}, '3': {'limit': 1, 'type': 'Multiplier', 'var': 'RemovablePowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"limit":1,"type":"Multiplier","var":"RemovableEnduranceCharge"},"2":{"limit":1,"type":"Multiplier","var":"RemovableFrenzyCharge"},"3":{"limit":1,"type":"Multiplier","var":"RemovablePowerCharge"}}]}
```

### 17. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]

- Match score: `70`
- `k`: damage_+%_per_endurance_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"damage_+%_per_endurance_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"EnduranceCharge"}}]}
```

### 18. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: damage_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"damage_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 19. [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]

- Match score: `70`
- `k`: damage_+%_per_power_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"damage_+%_per_power_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'PowerCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"PowerCharge"}}]}
```

### 20. [{'flags': 0, 'keywordFlags': 0, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]

- Match score: `70`
- `k`: critical_ailment_dot_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_ailment_dot_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"DotMultiplier","type":"BASE","1":{"type":"Condition","var":"CriticalStrike"}}]}
```

### 21. [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'limit': 5, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]

- Match score: `70`
- `k`: buff_effect_duration_+%_per_removable_endurance_charge_limited_to_5
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'limit': 5, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"buff_effect_duration_+%_per_removable_endurance_charge_limited_to_5","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'limit': 5, 'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Duration","type":"INC","1":{"limit":5,"type":"Multiplier","var":"RemovableEnduranceCharge"}}]}
```

### 22. [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]

- Match score: `70`
- `k`: buff_effect_duration_+%_per_removable_endurance_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"buff_effect_duration_+%_per_removable_endurance_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableEnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Duration","type":"INC","1":{"type":"Multiplier","var":"RemovableEnduranceCharge"}}]}
```

### 23. [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]

- Match score: `70`
- `k`: skill_effect_duration_+%_per_removable_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"skill_effect_duration_+%_per_removable_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'Duration', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'RemovableFrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"Duration","type":"INC","1":{"type":"Multiplier","var":"RemovableFrenzyCharge"}}]}
```

### 24. [{'flags': 0, 'keywordFlags': 0, 'name': 'EnduranceChargesMax', 'type': 'OVERRIDE'}]

- Match score: `70`
- `k`: set_max_endurance_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'EnduranceChargesMax', 'type': 'OVERRIDE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"set_max_endurance_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'EnduranceChargesMax', 'type': 'OVERRIDE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"EnduranceChargesMax","type":"OVERRIDE"}]}
```

### 25. [{'flags': 0, 'keywordFlags': 0, 'name': 'FrenzyChargesMax', 'type': 'OVERRIDE'}]

- Match score: `70`
- `k`: set_max_frenzy_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'FrenzyChargesMax', 'type': 'OVERRIDE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"set_max_frenzy_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'FrenzyChargesMax', 'type': 'OVERRIDE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"FrenzyChargesMax","type":"OVERRIDE"}]}
```

### 26. [{'flags': 0, 'keywordFlags': 0, 'name': 'MineLayingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: mine_throwing_speed_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MineLayingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"mine_throwing_speed_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MineLayingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MineLayingSpeed","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 27. [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: physical_damage_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"physical_damage_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PhysicalDamage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PhysicalDamage","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 28. [{'flags': 0, 'keywordFlags': 0, 'name': 'PowerChargesMax', 'type': 'OVERRIDE'}]

- Match score: `70`
- `k`: set_max_power_charges
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'PowerChargesMax', 'type': 'OVERRIDE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"set_max_power_charges","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'PowerChargesMax', 'type': 'OVERRIDE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"PowerChargesMax","type":"OVERRIDE"}]}
```

### 29. [{'flags': 0, 'keywordFlags': 0, 'name': 'ProjectileSpeedAppliesToProjectileDamage', 'type': 'FLAG', 'value': True}]

- Match score: `70`
- `k`: projectile_speed_additive_modifiers_also_apply_to_projectile_damage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ProjectileSpeedAppliesToProjectileDamage', 'type': 'FLAG', 'value': True}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"projectile_speed_additive_modifiers_also_apply_to_projectile_damage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ProjectileSpeedAppliesToProjectileDamage', 'type': 'FLAG', 'value': True}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ProjectileSpeedAppliesToProjectileDamage","type":"FLAG","value":true}]}
```

### 30. [{'flags': 0, 'keywordFlags': 0, 'name': 'TrapThrowingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: trap_throwing_speed_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'TrapThrowingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"trap_throwing_speed_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'TrapThrowingSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"TrapThrowingSpeed","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 31. [{'flags': 0, 'keywordFlags': 2097152, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]

- Match score: `70`
- `k`: critical_poison_dot_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 2097152, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_poison_dot_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 2097152, 'name': 'DotMultiplier', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":2097152,"name":"DotMultiplier","type":"BASE","1":{"type":"Condition","var":"CriticalStrike"}}]}
```

### 32. [{'flags': 0, 'keywordFlags': 524288, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: ailment_damage_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 524288, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"ailment_damage_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 524288, 'name': 'Damage', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":524288,"name":"Damage","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 33. [{'flags': 0, 'keywordFlags': 8192, 'name': 'ProjectileSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: mine_projectile_speed_+%_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 8192, 'name': 'ProjectileSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"mine_projectile_speed_+%_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 8192, 'name': 'ProjectileSpeed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":8192,"name":"ProjectileSpeed","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 34. [{'flags': 1, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]

- Match score: `70`
- `k`: active_skill_attack_damage_+%_final_per_endurance_charge
- `n`: [{'flags': 1, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_attack_damage_+%_final_per_endurance_charge","n":"[{'flags': 1, 'keywordFlags': 0, 'name': 'Damage', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'EnduranceCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":1,"keywordFlags":0,"name":"Damage","type":"MORE","1":{"type":"Multiplier","var":"EnduranceCharge"}}]}
```

### 35. [{'flags': 1, 'keywordFlags': 0, 'name': 'Speed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `70`
- `k`: base_attack_speed_+%_per_frenzy_charge
- `n`: [{'flags': 1, 'keywordFlags': 0, 'name': 'Speed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_attack_speed_+%_per_frenzy_charge","n":"[{'flags': 1, 'keywordFlags': 0, 'name': 'Speed', 'type': 'INC', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":1,"keywordFlags":0,"name":"Speed","type":"INC","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 36. [{'flags': 2, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'RemovableTotalCharges'}}]

- Match score: `70`
- `k`: area_of_effect_+%_final_per_removable_power_frenzy_or_endurance_charge
- `n`: [{'flags': 2, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'RemovableTotalCharges'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"area_of_effect_+%_final_per_removable_power_frenzy_or_endurance_charge","n":"[{'flags': 2, 'keywordFlags': 0, 'name': 'AreaOfEffect', 'type': 'MORE', '1': {'type': 'Multiplier', 'var': 'RemovableTotalCharges'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":2,"keywordFlags":0,"name":"AreaOfEffect","type":"MORE","1":{"type":"Multiplier","var":"RemovableTotalCharges"}}]}
```

### 37. [{'flags': 2, 'keywordFlags': 0, 'name': 'ImpaleChance', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]

- Match score: `70`
- `k`: spell_impale_on_crit_%_chance
- `n`: [{'flags': 2, 'keywordFlags': 0, 'name': 'ImpaleChance', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"spell_impale_on_crit_%_chance","n":"[{'flags': 2, 'keywordFlags': 0, 'name': 'ImpaleChance', 'type': 'BASE', '1': {'type': 'Condition', 'var': 'CriticalStrike'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":2,"keywordFlags":0,"name":"ImpaleChance","type":"BASE","1":{"type":"Condition","var":"CriticalStrike"}}]}
```

### 38. additional_base_critical_strike_chance

- Match score: `70`
- `k`: additional_base_critical_strike_chance
- `n`: additional_base_critical_strike_chance
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additional_base_critical_strike_chance","n":"additional_base_critical_strike_chance","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 39. additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad

- Match score: `70`
- `k`: additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad
- `n`: additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad","n":"additional_critical_strike_chance_per_10_shield_maximum_energy_shield_permyriad","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 40. additional_critical_strike_chance_permyriad_while_affected_by_elusive

- Match score: `70`
- `k`: additional_critical_strike_chance_permyriad_while_affected_by_elusive
- `n`: additional_critical_strike_chance_permyriad_while_affected_by_elusive
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"additional_critical_strike_chance_permyriad_while_affected_by_elusive","n":"additional_critical_strike_chance_permyriad_while_affected_by_elusive","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 41. base_self_critical_strike_multiplier_-%

- Match score: `70`
- `k`: base_self_critical_strike_multiplier_-%
- `n`: base_self_critical_strike_multiplier_-%
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_self_critical_strike_multiplier_-%","n":"base_self_critical_strike_multiplier_-%","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 42. CannotConsumeCharges

- Match score: `70`
- `k`: 222
- `n`: CannotConsumeCharges
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"222","n":"CannotConsumeCharges","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"CannotConsumeCharges"}
```

### 43. Cast on Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemCastOnCriticalStrike
- `n`: Cast on Critical
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"buff":true,"grants_active_skill":true,"intelligence":true,"meta":true,"persistent":true,"trigger":true}

```json
{"k":"Metadata/Items/Gems/SkillGemCastOnCriticalStrike","n":"Cast on Critical","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"buff":true,"grants_active_skill":true,"intelligence":true,"meta":true,"persistent":true,"trigger":true}}
```

### 44. CGEFallenGodBossChaosChargeFire

- Match score: `70`
- `k`: CGEFallenGodBossChaosChargeFire
- `n`: CGEFallenGodBossChaosChargeFire
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEFallenGodBossChaosChargeFire","n":"CGEFallenGodBossChaosChargeFire","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 45. CGEFallenGodBossChaosChargeFireSanctified

- Match score: `70`
- `k`: CGEFallenGodBossChaosChargeFireSanctified
- `n`: CGEFallenGodBossChaosChargeFireSanctified
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"CGEFallenGodBossChaosChargeFireSanctified","n":"CGEFallenGodBossChaosChargeFireSanctified","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 46. Charge Profusion I

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemChargeProfusionSupport
- `n`: Charge Profusion I
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemChargeProfusionSupport","n":"Charge Profusion I","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 47. Charge Profusion II

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemChargeProfusionSupportTwo
- `n`: Charge Profusion II
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemChargeProfusionSupportTwo","n":"Charge Profusion II","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 48. ConsumesCharges

- Match score: `70`
- `k`: 130
- `n`: ConsumesCharges
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"130","n":"ConsumesCharges","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"ConsumesCharges"}
```

### 49. EASKulemakBossHeadCharge

- Match score: `70`
- `k`: EASKulemakBossHeadCharge
- `n`: EASKulemakBossHeadCharge
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"EASKulemakBossHeadCharge","n":"EASKulemakBossHeadCharge","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 50. GAArenaBeastBossFissureDamage

- Match score: `70`
- `k`: GAArenaBeastBossFissureDamage
- `n`: GAArenaBeastBossFissureDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAArenaBeastBossFissureDamage","n":"GAArenaBeastBossFissureDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 51. GAChaosGodOwlBossBatDamage

- Match score: `70`
- `k`: GAChaosGodOwlBossBatDamage
- `n`: GAChaosGodOwlBossBatDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAChaosGodOwlBossBatDamage","n":"GAChaosGodOwlBossBatDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 52. GAHarborBossChargeBash

- Match score: `70`
- `k`: GAHarborBossChargeBash
- `n`: GAHarborBossChargeBash
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAHarborBossChargeBash","n":"GAHarborBossChargeBash","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 53. GAHellscapeDemonBossLeapSlamDamage

- Match score: `70`
- `k`: GAHellscapeDemonBossLeapSlamDamage
- `n`: GAHellscapeDemonBossLeapSlamDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAHellscapeDemonBossLeapSlamDamage","n":"GAHellscapeDemonBossLeapSlamDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 54. GAMastodonChargeShape

- Match score: `70`
- `k`: GAMastodonChargeShape
- `n`: GAMastodonChargeShape
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAMastodonChargeShape","n":"GAMastodonChargeShape","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 55. GAPrimordialExpeditionBossChargedSlam

- Match score: `70`
- `k`: GAPrimordialExpeditionBossChargedSlam
- `n`: GAPrimordialExpeditionBossChargedSlam
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAPrimordialExpeditionBossChargedSlam","n":"GAPrimordialExpeditionBossChargedSlam","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 56. GARathbreakerChargeSlash

- Match score: `70`
- `k`: GARathbreakerChargeSlash
- `n`: GARathbreakerChargeSlash
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GARathbreakerChargeSlash","n":"GARathbreakerChargeSlash","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 57. GASerpentCasterBossTailSwipeDamage

- Match score: `70`
- `k`: GASerpentCasterBossTailSwipeDamage
- `n`: GASerpentCasterBossTailSwipeDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GASerpentCasterBossTailSwipeDamage","n":"GASerpentCasterBossTailSwipeDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 58. GASharkBossDiveLongRangeCharge

- Match score: `70`
- `k`: GASharkBossDiveLongRangeCharge
- `n`: GASharkBossDiveLongRangeCharge
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GASharkBossDiveLongRangeCharge","n":"GASharkBossDiveLongRangeCharge","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 59. GASharkBossDiveMediumRangeCharge

- Match score: `70`
- `k`: GASharkBossDiveMediumRangeCharge
- `n`: GASharkBossDiveMediumRangeCharge
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GASharkBossDiveMediumRangeCharge","n":"GASharkBossDiveMediumRangeCharge","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 60. GASkeletonSnakeBossHeadSlamBodyDamage

- Match score: `70`
- `k`: GASkeletonSnakeBossHeadSlamBodyDamage
- `n`: GASkeletonSnakeBossHeadSlamBodyDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GASkeletonSnakeBossHeadSlamBodyDamage","n":"GASkeletonSnakeBossHeadSlamBodyDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 61. GATitanBossFissureDamage

- Match score: `70`
- `k`: GATitanBossFissureDamage
- `n`: GATitanBossFissureDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GATitanBossFissureDamage","n":"GATitanBossFissureDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 62. GAVaalColossusBossChargedSlam

- Match score: `70`
- `k`: GAVaalColossusBossChargedSlam
- `n`: GAVaalColossusBossChargedSlam
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAVaalColossusBossChargedSlam","n":"GAVaalColossusBossChargedSlam","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 63. GAVolcanicMinibossFissureDamage

- Match score: `70`
- `k`: GAVolcanicMinibossFissureDamage
- `n`: GAVolcanicMinibossFissureDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GAVolcanicMinibossFissureDamage","n":"GAVolcanicMinibossFissureDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 64. GeneratesCharges

- Match score: `70`
- `k`: 146
- `n`: GeneratesCharges
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"146","n":"GeneratesCharges","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"GeneratesCharges"}
```

### 65. GSCyclopsSpiderBossComboBeamDamage

- Match score: `70`
- `k`: GSCyclopsSpiderBossComboBeamDamage
- `n`: GSCyclopsSpiderBossComboBeamDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSCyclopsSpiderBossComboBeamDamage","n":"GSCyclopsSpiderBossComboBeamDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 66. GSCyclopsSpiderBossWebRockFlyingDamage

- Match score: `70`
- `k`: GSCyclopsSpiderBossWebRockFlyingDamage
- `n`: GSCyclopsSpiderBossWebRockFlyingDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSCyclopsSpiderBossWebRockFlyingDamage","n":"GSCyclopsSpiderBossWebRockFlyingDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 67. GSDemonClawBossBulletHellDamageHigh

- Match score: `70`
- `k`: GSDemonClawBossBulletHellDamageHigh
- `n`: GSDemonClawBossBulletHellDamageHigh
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSDemonClawBossBulletHellDamageHigh","n":"GSDemonClawBossBulletHellDamageHigh","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 68. GSDemonClawBossBulletHellDamageLow

- Match score: `70`
- `k`: GSDemonClawBossBulletHellDamageLow
- `n`: GSDemonClawBossBulletHellDamageLow
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSDemonClawBossBulletHellDamageLow","n":"GSDemonClawBossBulletHellDamageLow","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 69. GSIceOwlBossIceSpikeDamage

- Match score: `70`
- `k`: GSIceOwlBossIceSpikeDamage
- `n`: GSIceOwlBossIceSpikeDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSIceOwlBossIceSpikeDamage","n":"GSIceOwlBossIceSpikeDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 70. GSKaruiCaptainBoss2LaserDamage

- Match score: `70`
- `k`: GSKaruiCaptainBoss2LaserDamage
- `n`: GSKaruiCaptainBoss2LaserDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSKaruiCaptainBoss2LaserDamage","n":"GSKaruiCaptainBoss2LaserDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 71. GSOverlordBossRaiseAndRazeExplosionDamage

- Match score: `70`
- `k`: GSOverlordBossRaiseAndRazeExplosionDamage
- `n`: GSOverlordBossRaiseAndRazeExplosionDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSOverlordBossRaiseAndRazeExplosionDamage","n":"GSOverlordBossRaiseAndRazeExplosionDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 72. GSOverlordBossRaiseAndRazeRockUpwardDamage

- Match score: `70`
- `k`: GSOverlordBossRaiseAndRazeRockUpwardDamage
- `n`: GSOverlordBossRaiseAndRazeRockUpwardDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSOverlordBossRaiseAndRazeRockUpwardDamage","n":"GSOverlordBossRaiseAndRazeRockUpwardDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 73. GSShipwreckBossWaveDamage

- Match score: `70`
- `k`: GSShipwreckBossWaveDamage
- `n`: GSShipwreckBossWaveDamage
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GSShipwreckBossWaveDamage","n":"GSShipwreckBossWaveDamage","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 74. GTLieutenantBruteChargeSlam

- Match score: `70`
- `k`: GTLieutenantBruteChargeSlam
- `n`: GTLieutenantBruteChargeSlam
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"GTLieutenantBruteChargeSlam","n":"GTLieutenantBruteChargeSlam","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 75. Heightened Charges

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemHeightenedChargesSupport
- `n`: Heightened Charges
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemHeightenedChargesSupport","n":"Heightened Charges","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 76. HeistMilitaryMinibossShieldCharge

- Match score: `70`
- `k`: HeistMilitaryMinibossShieldCharge
- `n`: HeistMilitaryMinibossShieldCharge
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"HeistMilitaryMinibossShieldCharge","n":"HeistMilitaryMinibossShieldCharge","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 77. HellscapeDemonBossMeleeAtAnimationSpeedFireKnockback

- Match score: `70`
- `k`: HellscapeDemonBossMeleeAtAnimationSpeedFireKnockback
- `n`: HellscapeDemonBossMeleeAtAnimationSpeedFireKnockback
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"HellscapeDemonBossMeleeAtAnimationSpeedFireKnockback","n":"HellscapeDemonBossMeleeAtAnimationSpeedFireKnockback","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 78. Inexorable Critical I

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemInevitableCriticalsSupport
- `n`: Inexorable Critical I
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemInevitableCriticalsSupport","n":"Inexorable Critical I","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 79. Inexorable Critical II

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemInevitableCriticalsSupportTwo
- `n`: Inexorable Critical II
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemInevitableCriticalsSupportTwo","n":"Inexorable Critical II","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 80. MASBaronBossBackwardsChargeCleave

- Match score: `70`
- `k`: MASBaronBossBackwardsChargeCleave
- `n`: MASBaronBossBackwardsChargeCleave
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MASBaronBossBackwardsChargeCleave","n":"MASBaronBossBackwardsChargeCleave","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 81. MASBaronBossFrontalChargeCleave

- Match score: `70`
- `k`: MASBaronBossFrontalChargeCleave
- `n`: MASBaronBossFrontalChargeCleave
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MASBaronBossFrontalChargeCleave","n":"MASBaronBossFrontalChargeCleave","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 82. MDJetpackMiniBossChargedCannon

- Match score: `70`
- `k`: MDJetpackMiniBossChargedCannon
- `n`: MDJetpackMiniBossChargedCannon
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MDJetpackMiniBossChargedCannon","n":"MDJetpackMiniBossChargedCannon","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 83. MDJetpackMiniBossChargedCannonTriggered

- Match score: `70`
- `k`: MDJetpackMiniBossChargedCannonTriggered
- `n`: MDJetpackMiniBossChargedCannonTriggered
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MDJetpackMiniBossChargedCannonTriggered","n":"MDJetpackMiniBossChargedCannonTriggered","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 84. MDJetpackMiniBossFloatingChargedCannon

- Match score: `70`
- `k`: MDJetpackMiniBossFloatingChargedCannon
- `n`: MDJetpackMiniBossFloatingChargedCannon
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MDJetpackMiniBossFloatingChargedCannon","n":"MDJetpackMiniBossFloatingChargedCannon","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 85. MDJetpackMiniBossFloatingChargedCannonTriggered

- Match score: `70`
- `k`: MDJetpackMiniBossFloatingChargedCannonTriggered
- `n`: MDJetpackMiniBossFloatingChargedCannonTriggered
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MDJetpackMiniBossFloatingChargedCannonTriggered","n":"MDJetpackMiniBossFloatingChargedCannonTriggered","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 86. MeleeAtAnimationSpeedBoss

- Match score: `70`
- `k`: MeleeAtAnimationSpeedBoss
- `n`: MeleeAtAnimationSpeedBoss
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedBoss","n":"MeleeAtAnimationSpeedBoss","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 87. MeleeAtAnimationSpeedBoss180

- Match score: `70`
- `k`: MeleeAtAnimationSpeedBoss180
- `n`: MeleeAtAnimationSpeedBoss180
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedBoss180","n":"MeleeAtAnimationSpeedBoss180","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 88. MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelMaceBoss

- Match score: `70`
- `k`: MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelMaceBoss
- `n`: MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelMaceBoss
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelMaceBoss","n":"MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelMaceBoss","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 89. MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelUnarmedBoss

- Match score: `70`
- `k`: MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelUnarmedBoss
- `n`: MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelUnarmedBoss
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelUnarmedBoss","n":"MeleeAtAnimationSpeedWithDirectionalKnockbackMarakethSentinelUnarmedBoss","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 90. Metadata/Items/Gems/SkillGemCastOnCritical

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

### 91. Metadata/Items/Gems/SupportGemInevitableCritical

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

### 92. Metadata/Items/Gems/SupportGemInevitableCriticalTwo

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

### 93. Metadata/Items/Gems/SupportGemPinpointCritical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemPinpointCritical
- `n`: Metadata/Items/Gems/SupportGemPinpointCritical
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support"]
- `base`: {"display_name":"Pinpoint Critical","id":"Metadata/Items/Gems/SupportGemPinpointCritical","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemPinpointCritical","n":"Metadata/Items/Gems/SupportGemPinpointCritical","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Pinpoint Critical","id":"Metadata/Items/Gems/SupportGemPinpointCritical","release_state":"released"},"tags":["support"]}
```

### 94. Metadata/Items/Gems/SupportGemSupercritical

- Match score: `70`
- `k`: Metadata/Items/Gems/SupportGemSupercritical
- `n`: Metadata/Items/Gems/SupportGemSupercritical
- `cat`: repoe_skill_gems
- `src`: repoe_poe2/skill_gems.json
- `tags`: ["support"]
- `base`: {"display_name":"Supercritical","id":"Metadata/Items/Gems/SupportGemSupercritical","release_state":"released"}

```json
{"k":"Metadata/Items/Gems/SupportGemSupercritical","n":"Metadata/Items/Gems/SupportGemSupercritical","cat":"repoe_skill_gems","src":"repoe_poe2/skill_gems.json","base":{"display_name":"Supercritical","id":"Metadata/Items/Gems/SupportGemSupercritical","release_state":"released"},"tags":["support"]}
```

### 95. override_off_hand_base_critical_strike_chance_to_5%

- Match score: `70`
- `k`: override_off_hand_base_critical_strike_chance_to_5%
- `n`: override_off_hand_base_critical_strike_chance_to_5%
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"override_off_hand_base_critical_strike_chance_to_5%","n":"override_off_hand_base_critical_strike_chance_to_5%","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json"}
```

### 96. Pinpoint Critical

- Match score: `70`
- `k`: Metadata/Items/Gems/SkillGemPinpointCritical
- `n`: Pinpoint Critical
- `cat`: pob_gems
- `src`: pob_data_poe2/Gems.json
- `tags`: {"support":true}

```json
{"k":"Metadata/Items/Gems/SkillGemPinpointCritical","n":"Pinpoint Critical","cat":"pob_gems","src":"pob_data_poe2/Gems.json","tags":{"support":true}}
```

### 97. RequiresCharges

- Match score: `70`
- `k`: 221
- `n`: RequiresCharges
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"221","n":"RequiresCharges","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"RequiresCharges"}
```

### 98. RockSliderShieldChargeSanctum

- Match score: `70`
- `k`: RockSliderShieldChargeSanctum
- `n`: RockSliderShieldChargeSanctum
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"RockSliderShieldChargeSanctum","n":"RockSliderShieldChargeSanctum","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 99. SkillConsumesEnduranceChargesOnUse

- Match score: `70`
- `k`: 171
- `n`: SkillConsumesEnduranceChargesOnUse
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"171","n":"SkillConsumesEnduranceChargesOnUse","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"SkillConsumesEnduranceChargesOnUse"}
```

### 100. SkillConsumesFrenzyChargesOnUse

- Match score: `70`
- `k`: 170
- `n`: SkillConsumesFrenzyChargesOnUse
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"170","n":"SkillConsumesFrenzyChargesOnUse","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"SkillConsumesFrenzyChargesOnUse"}
```

### 101. SkillConsumesPowerChargesOnUse

- Match score: `70`
- `k`: 169
- `n`: SkillConsumesPowerChargesOnUse
- `cat`: repoe_active_skill_types
- `src`: repoe_poe2/active_skill_types.json

```json
{"k":"169","n":"SkillConsumesPowerChargesOnUse","cat":"repoe_active_skill_types","src":"repoe_poe2/active_skill_types.json","v":"SkillConsumesPowerChargesOnUse"}
```

### 102. SupportHeightenedChargesPlayer

- Match score: `70`
- `k`: SupportHeightenedChargesPlayer
- `n`: SupportHeightenedChargesPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":null,"allowed_types":["ConsumesCharges"],"excluded_types":null,"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportHeightenedChargesPlayer","n":"SupportHeightenedChargesPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":null,"allowed_types":["ConsumesCharges"],"excluded_types":null,"letter":"","supports_gems_only":false},"is_support":true}
```

### 103. TCBaronBossHowlChargeOut

- Match score: `70`
- `k`: TCBaronBossHowlChargeOut
- `n`: TCBaronBossHowlChargeOut
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"TCBaronBossHowlChargeOut","n":"TCBaronBossHowlChargeOut","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 104. TCFallenGodChaosChargeSanctified

- Match score: `70`
- `k`: TCFallenGodChaosChargeSanctified
- `n`: TCFallenGodChaosChargeSanctified
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"TCFallenGodChaosChargeSanctified","n":"TCFallenGodChaosChargeSanctified","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 105. TCHarborBossCharge

- Match score: `70`
- `k`: TCHarborBossCharge
- `n`: TCHarborBossCharge
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `is_support`: False

```json
{"k":"TCHarborBossCharge","n":"TCHarborBossCharge","cat":"repoe_skills","src":"repoe_poe2/skills.json","is_support":false}
```

### 106. SupportChargeInhibitionPlayer

- Match score: `55`
- `k`: SupportChargeInhibitionPlayer
- `n`: SupportChargeInhibitionPlayer
- `cat`: repoe_skills
- `src`: repoe_poe2/skills.json
- `support`: {"added_minion_types":null,"added_types":["CannotConsumeCharges"],"allowed_types":["Damage","Attack","CrossbowSkill","CrossbowAmmoSkill","Spell","DegenOnlySpellDamage"],"excluded_types":["UsedByProxy","Persistent","RequiresCharges"],"letter":"","supports_gems_only":false}
- `is_support`: True

```json
{"k":"SupportChargeInhibitionPlayer","n":"SupportChargeInhibitionPlayer","cat":"repoe_skills","src":"repoe_poe2/skills.json","support":{"added_minion_types":null,"added_types":["CannotConsumeCharges"],"allowed_types":["Damage","Attack","CrossbowSkill","CrossbowAmmoSkill","Spell","DegenOnlySpellDamage"],"excluded_types":["UsedByProxy","Persistent","RequiresCharges"],"letter":"","supports_gems_only":false},"is_support":true}
```

### 107. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `45`
- `k`: maximum_added_cold_damage_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"maximum_added_cold_damage_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMax', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMax","type":"BASE","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 108. [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]

- Match score: `45`
- `k`: minimum_added_cold_damage_per_frenzy_charge
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minimum_added_cold_damage_per_frenzy_charge","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'ColdMin', 'type': 'BASE', '1': {'type': 'Multiplier', 'var': 'FrenzyCharge'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"ColdMin","type":"BASE","1":{"type":"Multiplier","var":"FrenzyCharge"}}]}
```

### 109. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Bleeding'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_vs_bleeding_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Bleeding'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_vs_bleeding_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Bleeding'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"Bleeding"}}]}
```

### 110. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Blinded'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_vs_blinded_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Blinded'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_vs_blinded_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Blinded'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"Blinded"}}]}
```

### 111. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'FullLife'}}]

- Match score: `45`
- `k`: critical_strike_chance_against_enemies_on_full_life_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'FullLife'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_against_enemies_on_full_life_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'FullLife'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"FullLife"}}]}
```

### 112. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Immobilised'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_vs_immobilised_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Immobilised'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_vs_immobilised_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Immobilised'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"Immobilised"}}]}
```

### 113. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_vs_shocked_enemies
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_vs_shocked_enemies","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'actor': 'enemy', 'type': 'ActorCondition', 'var': 'Shocked'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"actor":"enemy","type":"ActorCondition","var":"Shocked"}}]}
```

### 114. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'div': 5, 'stat': 'Rage', 'type': 'PerStat'}}]

- Match score: `45`
- `k`: critical_strike_chance_+%_per_5_rage
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'div': 5, 'stat': 'Rage', 'type': 'PerStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%_per_5_rage","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC', '1': {'div': 5, 'stat': 'Rage', 'type': 'PerStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC","1":{"div":5,"stat":"Rage","type":"PerStat"}}]}
```

### 115. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC'}]

- Match score: `45`
- `k`: critical_strike_chance_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_strike_chance_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC"}]}
```

### 116. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'MORE'}]

- Match score: `45`
- `k`: active_skill_critical_strike_chance_+%_final
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'MORE'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"active_skill_critical_strike_chance_+%_final","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'MORE'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritChance","type":"MORE"}]}
```

### 117. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'div': 100, 'stat': 'EnergyShieldOnWeapon 2', 'type': 'PerStat'}}]

- Match score: `45`
- `k`: critical_multiplier_+%_per_100_max_es_on_shield
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'div': 100, 'stat': 'EnergyShieldOnWeapon 2', 'type': 'PerStat'}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"critical_multiplier_+%_per_100_max_es_on_shield","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE', '1': {'div': 100, 'stat': 'EnergyShieldOnWeapon 2', 'type': 'PerStat'}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritMultiplier","type":"BASE","1":{"div":100,"stat":"EnergyShieldOnWeapon 2","type":"PerStat"}}]}
```

### 118. [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'INC'}]

- Match score: `45`
- `k`: base_critical_strike_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'INC'}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"base_critical_strike_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'INC'}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"CritMultiplier","type":"INC"}]}
```

### 119. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC'}}}]

- Match score: `45`
- `k`: minion_critical_strike_chance_+%
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC'}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minion_critical_strike_chance_+%","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CritChance', 'type': 'INC'}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"CritChance","type":"INC"}}}]}
```

### 120. [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE'}}}]

- Match score: `45`
- `k`: minion_critical_strike_multiplier_+
- `n`: [{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE'}}}]
- `cat`: pob_skill_stat_map
- `src`: pob_data_poe2/SkillStatMap.json

```json
{"k":"minion_critical_strike_multiplier_+","n":"[{'flags': 0, 'keywordFlags': 0, 'name': 'MinionModifier', 'type': 'LIST', 'value': {'mod': {'flags': 0, 'keywordFlags': 0, 'name': 'CritMultiplier', 'type': 'BASE'}}}]","cat":"pob_skill_stat_map","src":"pob_data_poe2/SkillStatMap.json","v":[{"flags":0,"keywordFlags":0,"name":"MinionModifier","type":"LIST","value":{"mod":{"flags":0,"keywordFlags":0,"name":"CritMultiplier","type":"BASE"}}}]}
```

## Item bases/classes

- Source: `build_knowledge/compact/item_base_index.json`
- Matches included: `120`

### 1. Blazing Critical

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

### 2. Cast on Critical

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

### 3. caster_critical

- Match score: `70`
- `k`: caster_critical
- `n`: caster_critical
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"caster_critical","n":"caster_critical","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 4. caster_critical

- Match score: `70`
- `k`: 1298
- `n`: caster_critical
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1298","n":"caster_critical","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"caster_critical"}
```

### 5. Charge Profusion I

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

### 6. Charge Profusion II

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

### 7. Critical

- Match score: `70`
- `k`: critical
- `n`: Critical
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"critical","n":"Critical","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 8. critical

- Match score: `70`
- `k`: 575
- `n`: critical
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"575","n":"critical","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"critical"}
```

### 9. Critical Wand

- Match score: `70`
- `k`: Metadata/Items/Weapons/OneHandWeapons/Wands/FourWand11
- `n`: Critical Wand
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["wand","onehand","default"]
- `domain`: item

```json
{"k":"Metadata/Items/Weapons/OneHandWeapons/Wands/FourWand11","n":"Critical Wand","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Wand","tags":["wand","onehand","default"],"domain":"item"}
```

### 10. critical_utility_flask

- Match score: `70`
- `k`: critical_utility_flask
- `n`: critical_utility_flask
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"critical_utility_flask","n":"critical_utility_flask","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 11. critical_utility_flask

- Match score: `70`
- `k`: 47
- `n`: critical_utility_flask
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"47","n":"critical_utility_flask","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"critical_utility_flask"}
```

### 12. Heightened Charges

- Match score: `70`
- `k`: Metadata/Items/Gem/SupportGemTwofold
- `n`: Heightened Charges
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gem/SupportGemTwofold","n":"Heightened Charges","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 13. Inexorable Critical I

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

### 14. Inexorable Critical II

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

### 15. Pinpoint Critical

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

### 16. Supercritical

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

### 17. Essence of Alacrity

- Match score: `45`
- `k`: Metadata/Items/Currency/CurrencyEssenceSpeedCaster
- `n`: Essence of Alacrity
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["essence","currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyEssenceSpeedCaster","n":"Essence of Alacrity","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["essence","currency","default"],"domain":"undefined"}
```

### 18. Greater Essence of Alacrity

- Match score: `45`
- `k`: Metadata/Items/Currency/CurrencyGreaterEssenceSpeedCaster
- `n`: Greater Essence of Alacrity
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["essence","currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyGreaterEssenceSpeedCaster","n":"Greater Essence of Alacrity","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["essence","currency","default"],"domain":"undefined"}
```

### 19. Lesser Essence of Alacrity

- Match score: `45`
- `k`: Metadata/Items/Currency/CurrencyLesserEssenceSpeedCaster
- `n`: Lesser Essence of Alacrity
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["essence","currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyLesserEssenceSpeedCaster","n":"Lesser Essence of Alacrity","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["essence","currency","default"],"domain":"undefined"}
```

### 20. Perfect Essence of Alacrity

- Match score: `45`
- `k`: Metadata/Items/Currency/CurrencyPerfectEssenceSpeedCaster
- `n`: Perfect Essence of Alacrity
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["essence","currency","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Currency/CurrencyPerfectEssenceSpeedCaster","n":"Perfect Essence of Alacrity","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"StackableCurrency","tags":["essence","currency","default"],"domain":"undefined"}
```

### 21. [DNT-UNUSED] Bone Cultist Shield Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act2/BoneCultistShieldBossDrop
- `n`: [DNT-UNUSED] Bone Cultist Shield Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act2/BoneCultistShieldBossDrop","n":"[DNT-UNUSED] Bone Cultist Shield Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 22. [DNT-UNUSED] Cyclops Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act5/CyclopsBossDrop
- `n`: [DNT-UNUSED] Cyclops Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act5/CyclopsBossDrop","n":"[DNT-UNUSED] Cyclops Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 23. [DNT-UNUSED] Dredge Fiend Shaman Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act3/DredgeFiendShamanBossDrop
- `n`: [DNT-UNUSED] Dredge Fiend Shaman Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act3/DredgeFiendShamanBossDrop","n":"[DNT-UNUSED] Dredge Fiend Shaman Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 24. [DNT-UNUSED] Eel Monster Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act3/EelMonsterBossDrop
- `n`: [DNT-UNUSED] Eel Monster Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act3/EelMonsterBossDrop","n":"[DNT-UNUSED] Eel Monster Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 25. [DNT-UNUSED] Fallen God Miniboss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act5/FallenGodMinibossDrop
- `n`: [DNT-UNUSED] Fallen God Miniboss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act5/FallenGodMinibossDrop","n":"[DNT-UNUSED] Fallen God Miniboss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 26. [DNT-UNUSED] Fountain Statue Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act4/FountainStatueBossDrop
- `n`: [DNT-UNUSED] Fountain Statue Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act4/FountainStatueBossDrop","n":"[DNT-UNUSED] Fountain Statue Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 27. [DNT-UNUSED] Quadrilla Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act3/QuadrillaBossDrop
- `n`: [DNT-UNUSED] Quadrilla Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act3/QuadrillaBossDrop","n":"[DNT-UNUSED] Quadrilla Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 28. [DNT-UNUSED] Shipwreck Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act4/ShipwreckBossDrop
- `n`: [DNT-UNUSED] Shipwreck Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act4/ShipwreckBossDrop","n":"[DNT-UNUSED] Shipwreck Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 29. [DNT-UNUSED] Sudoku Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act4/SudokuBossDrop
- `n`: [DNT-UNUSED] Sudoku Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act4/SudokuBossDrop","n":"[DNT-UNUSED] Sudoku Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 30. [DNT-UNUSED] Twilight Order Guard Boss

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act4/TwilightOrderGuardBoss
- `n`: [DNT-UNUSED] Twilight Order Guard Boss
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act4/TwilightOrderGuardBoss","n":"[DNT-UNUSED] Twilight Order Guard Boss","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 31. [DNT-UNUSED] Vaal Blood Priestess Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act3/VaalBloodPriestessBossDrop
- `n`: [DNT-UNUSED] Vaal Blood Priestess Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act3/VaalBloodPriestessBossDrop","n":"[DNT-UNUSED] Vaal Blood Priestess Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 32. [DNT-UNUSED] Vaal Sun Worshipper Boss Drop

- Match score: `35`
- `k`: Metadata/Items/QuestItems/Gallows/Act3/VaalSunWorshipperBossDrop
- `n`: [DNT-UNUSED] Vaal Sun Worshipper Boss Drop
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["quest_item","quest_item","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/QuestItems/Gallows/Act3/VaalSunWorshipperBossDrop","n":"[DNT-UNUSED] Vaal Sun Worshipper Boss Drop","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"QuestItem","tags":["quest_item","quest_item","default"],"domain":"undefined"}
```

### 33. abyss_lich_boss

- Match score: `35`
- `k`: abyss_lich_boss
- `n`: abyss_lich_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"abyss_lich_boss","n":"abyss_lich_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 34. abyss_lich_boss

- Match score: `35`
- `k`: 860
- `n`: abyss_lich_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"860","n":"abyss_lich_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"abyss_lich_boss"}
```

### 35. act_boss_area

- Match score: `35`
- `k`: act_boss_area
- `n`: act_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"act_boss_area","n":"act_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 36. act_boss_area

- Match score: `35`
- `k`: 159
- `n`: act_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"159","n":"act_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"act_boss_area"}
```

### 37. affliction_boss

- Match score: `35`
- `k`: affliction_boss
- `n`: affliction_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"affliction_boss","n":"affliction_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 38. affliction_boss

- Match score: `35`
- `k`: 993
- `n`: affliction_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"993","n":"affliction_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"affliction_boss"}
```

### 39. archer_boss

- Match score: `35`
- `k`: archer_boss
- `n`: archer_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archer_boss","n":"archer_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 40. archer_boss

- Match score: `35`
- `k`: 834
- `n`: archer_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"834","n":"archer_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archer_boss"}
```

### 41. archer_boss_area

- Match score: `35`
- `k`: archer_boss_area
- `n`: archer_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"archer_boss_area","n":"archer_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 42. archer_boss_area

- Match score: `35`
- `k`: 835
- `n`: archer_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"835","n":"archer_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"archer_boss_area"}
```

### 43. atziri_boss

- Match score: `35`
- `k`: atziri_boss
- `n`: atziri_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"atziri_boss","n":"atziri_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 44. atziri_boss

- Match score: `35`
- `k`: 899
- `n`: atziri_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"899","n":"atziri_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"atziri_boss"}
```

### 45. bear_boss_map

- Match score: `35`
- `k`: bear_boss_map
- `n`: bear_boss_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bear_boss_map","n":"bear_boss_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 46. bear_boss_map

- Match score: `35`
- `k`: 962
- `n`: bear_boss_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"962","n":"bear_boss_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bear_boss_map"}
```

### 47. bestiary_beast_boss

- Match score: `35`
- `k`: bestiary_beast_boss
- `n`: bestiary_beast_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bestiary_beast_boss","n":"bestiary_beast_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 48. bestiary_beast_boss

- Match score: `35`
- `k`: 293
- `n`: bestiary_beast_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"293","n":"bestiary_beast_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bestiary_beast_boss"}
```

### 49. bestiary_spirit_boss

- Match score: `35`
- `k`: bestiary_spirit_boss
- `n`: bestiary_spirit_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"bestiary_spirit_boss","n":"bestiary_spirit_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 50. bestiary_spirit_boss

- Match score: `35`
- `k`: 833
- `n`: bestiary_spirit_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"833","n":"bestiary_spirit_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"bestiary_spirit_boss"}
```

### 51. blight_boss

- Match score: `35`
- `k`: blight_boss
- `n`: blight_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"blight_boss","n":"blight_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 52. blight_boss

- Match score: `35`
- `k`: 649
- `n`: blight_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"649","n":"blight_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"blight_boss"}
```

### 53. blood_mage_boss_map

- Match score: `35`
- `k`: blood_mage_boss_map
- `n`: blood_mage_boss_map
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"blood_mage_boss_map","n":"blood_mage_boss_map","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 54. blood_mage_boss_map

- Match score: `35`
- `k`: 944
- `n`: blood_mage_boss_map
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"944","n":"blood_mage_boss_map","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"blood_mage_boss_map"}
```

### 55. boss

- Match score: `35`
- `k`: boss
- `n`: boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"boss","n":"boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 56. boss

- Match score: `35`
- `k`: 1103
- `n`: boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1103","n":"boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"boss"}
```

### 57. breachlord_boss_domain

- Match score: `35`
- `k`: breachlord_boss_domain
- `n`: breachlord_boss_domain
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"breachlord_boss_domain","n":"breachlord_boss_domain","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 58. breachlord_boss_domain

- Match score: `35`
- `k`: 887
- `n`: breachlord_boss_domain
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"887","n":"breachlord_boss_domain","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"breachlord_boss_domain"}
```

### 59. brute_boss

- Match score: `35`
- `k`: brute_boss
- `n`: brute_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"brute_boss","n":"brute_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 60. brute_boss

- Match score: `35`
- `k`: 967
- `n`: brute_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"967","n":"brute_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"brute_boss"}
```

### 61. cannot_possess_boss

- Match score: `35`
- `k`: cannot_possess_boss
- `n`: cannot_possess_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cannot_possess_boss","n":"cannot_possess_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 62. cannot_possess_boss

- Match score: `35`
- `k`: 948
- `n`: cannot_possess_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"948","n":"cannot_possess_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cannot_possess_boss"}
```

### 63. Cast when Damage Taken

- Match score: `35`
- `k`: Metadata/Items/Gems/SkillGemCastWhenDamageTaken
- `n`: Cast when Damage Taken
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SkillGemCastWhenDamageTaken","n":"Cast when Damage Taken","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Meta Skill Gem","tags":["gem","default"],"domain":"undefined"}
```

### 64. caster_damage

- Match score: `35`
- `k`: caster_damage
- `n`: caster_damage
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"caster_damage","n":"caster_damage","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 65. caster_damage

- Match score: `35`
- `k`: 614
- `n`: caster_damage
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"614","n":"caster_damage","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"caster_damage"}
```

### 66. caster_speed

- Match score: `35`
- `k`: caster_speed
- `n`: caster_speed
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"caster_speed","n":"caster_speed","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 67. caster_speed

- Match score: `35`
- `k`: 1297
- `n`: caster_speed
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"1297","n":"caster_speed","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"caster_speed"}
```

### 68. chaos_damage

- Match score: `35`
- `k`: chaos_damage
- `n`: chaos_damage
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chaos_damage","n":"chaos_damage","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 69. chaos_damage

- Match score: `35`
- `k`: 659
- `n`: chaos_damage
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"659","n":"chaos_damage","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chaos_damage"}
```

### 70. chaos_golem_boss_area

- Match score: `35`
- `k`: chaos_golem_boss_area
- `n`: chaos_golem_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chaos_golem_boss_area","n":"chaos_golem_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 71. chaos_golem_boss_area

- Match score: `35`
- `k`: 807
- `n`: chaos_golem_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"807","n":"chaos_golem_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chaos_golem_boss_area"}
```

### 72. Charge Regulation

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

### 73. Charged Compass

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

### 74. Charged Mark

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

### 75. Charged Shots I

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

### 76. Charged Shots II

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

### 77. Charged Staff

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

### 78. Chayula's Charged Breachstone

- Match score: `35`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentChaos2
- `n`: Chayula's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentChaos2","n":"Chayula's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 79. chayula_boss

- Match score: `35`
- `k`: chayula_boss
- `n`: chayula_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"chayula_boss","n":"chayula_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 80. chayula_boss

- Match score: `35`
- `k`: 862
- `n`: chayula_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"862","n":"chayula_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"chayula_boss"}
```

### 81. Compressed Duration I

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemFastForward
- `n`: Compressed Duration I
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemFastForward","n":"Compressed Duration I","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 82. Compressed Duration II

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemFastForwardTwo
- `n`: Compressed Duration II
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemFastForwardTwo","n":"Compressed Duration II","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 83. cortex_boss

- Match score: `35`
- `k`: cortex_boss
- `n`: cortex_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"cortex_boss","n":"cortex_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 84. cortex_boss

- Match score: `35`
- `k`: 938
- `n`: cortex_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"938","n":"cortex_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"cortex_boss"}
```

### 85. crusader_conqueror_boss

- Match score: `35`
- `k`: crusader_conqueror_boss
- `n`: crusader_conqueror_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"crusader_conqueror_boss","n":"crusader_conqueror_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 86. crusader_conqueror_boss

- Match score: `35`
- `k`: 886
- `n`: crusader_conqueror_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"886","n":"crusader_conqueror_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"crusader_conqueror_boss"}
```

### 87. Damage

- Match score: `35`
- `k`: damage
- `n`: Damage
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"damage","n":"Damage","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 88. damage

- Match score: `35`
- `k`: 582
- `n`: damage
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"582","n":"damage","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"damage"}
```

### 89. delve_lich_boss

- Match score: `35`
- `k`: delve_lich_boss
- `n`: delve_lich_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"delve_lich_boss","n":"delve_lich_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 90. delve_lich_boss

- Match score: `35`
- `k`: 902
- `n`: delve_lich_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"902","n":"delve_lich_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"delve_lich_boss"}
```

### 91. delve_protovaal_boss

- Match score: `35`
- `k`: delve_protovaal_boss
- `n`: delve_protovaal_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"delve_protovaal_boss","n":"delve_protovaal_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 92. delve_protovaal_boss

- Match score: `35`
- `k`: 900
- `n`: delve_protovaal_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"900","n":"delve_protovaal_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"delve_protovaal_boss"}
```

### 93. delve_vaal_boss

- Match score: `35`
- `k`: delve_vaal_boss
- `n`: delve_vaal_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"delve_vaal_boss","n":"delve_vaal_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 94. delve_vaal_boss

- Match score: `35`
- `k`: 901
- `n`: delve_vaal_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"901","n":"delve_vaal_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"delve_vaal_boss"}
```

### 95. elder_boss

- Match score: `35`
- `k`: elder_boss
- `n`: elder_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"elder_boss","n":"elder_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 96. elder_boss

- Match score: `35`
- `k`: 884
- `n`: elder_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"884","n":"elder_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"elder_boss"}
```

### 97. elder_guardian_boss

- Match score: `35`
- `k`: elder_guardian_boss
- `n`: elder_guardian_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"elder_guardian_boss","n":"elder_guardian_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 98. elder_guardian_boss

- Match score: `35`
- `k`: 861
- `n`: elder_guardian_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"861","n":"elder_guardian_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"elder_guardian_boss"}
```

### 99. elder_map_boss

- Match score: `35`
- `k`: elder_map_boss
- `n`: elder_map_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"elder_map_boss","n":"elder_map_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 100. elder_map_boss

- Match score: `35`
- `k`: 783
- `n`: elder_map_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"783","n":"elder_map_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"elder_map_boss"}
```

### 101. eldritch_pinnacle_boss

- Match score: `35`
- `k`: eldritch_pinnacle_boss
- `n`: eldritch_pinnacle_boss
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"eldritch_pinnacle_boss","n":"eldritch_pinnacle_boss","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 102. eldritch_pinnacle_boss

- Match score: `35`
- `k`: 990
- `n`: eldritch_pinnacle_boss
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"990","n":"eldritch_pinnacle_boss","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"eldritch_pinnacle_boss"}
```

### 103. Elemental Discharge

- Match score: `35`
- `k`: Metadata/Items/Gems/SupportGemElementalDischarge
- `n`: Elemental Discharge
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["support_gem","gem","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/Gems/SupportGemElementalDischarge","n":"Elemental Discharge","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Support Skill Gem","tags":["support_gem","gem","default"],"domain":"undefined"}
```

### 104. elemental_damage

- Match score: `35`
- `k`: elemental_damage
- `n`: elemental_damage
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"elemental_damage","n":"elemental_damage","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 105. elemental_damage

- Match score: `35`
- `k`: 611
- `n`: elemental_damage
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"611","n":"elemental_damage","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"elemental_damage"}
```

### 106. Embossed Boots

- Match score: `35`
- `k`: Metadata/Items/Armours/Boots/FourBootsDex3
- `n`: Embossed Boots
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["dex_armour","maraketh_basetype","boots","armour","default"]
- `req`: {"dexterity":23,"intelligence":0,"level":16,"strength":0}
- `domain`: item

```json
{"k":"Metadata/Items/Armours/Boots/FourBootsDex3","n":"Embossed Boots","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Boots","tags":["dex_armour","maraketh_basetype","boots","armour","default"],"req":{"dexterity":23,"intelligence":0,"level":16,"strength":0},"domain":"item"}
```

### 107. endurance_charge

- Match score: `35`
- `k`: endurance_charge
- `n`: endurance_charge
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"endurance_charge","n":"endurance_charge","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 108. endurance_charge

- Match score: `35`
- `k`: 581
- `n`: endurance_charge
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"581","n":"endurance_charge","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"endurance_charge"}
```

### 109. Esh's Charged Breachstone

- Match score: `35`
- `k`: Metadata/Items/MapFragments/CurrencyBreachFragmentLightning2
- `n`: Esh's Charged Breachstone
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["breachstone2","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/MapFragments/CurrencyBreachFragmentLightning2","n":"Esh's Charged Breachstone","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"Breachstone","tags":["breachstone2","default"],"domain":"undefined"}
```

### 110. frenzy_charge

- Match score: `35`
- `k`: frenzy_charge
- `n`: frenzy_charge
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"frenzy_charge","n":"frenzy_charge","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 111. frenzy_charge

- Match score: `35`
- `k`: 580
- `n`: frenzy_charge
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"580","n":"frenzy_charge","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"frenzy_charge"}
```

### 112. goatman_boss_area

- Match score: `35`
- `k`: goatman_boss_area
- `n`: goatman_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"goatman_boss_area","n":"goatman_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 113. goatman_boss_area

- Match score: `35`
- `k`: 844
- `n`: goatman_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"844","n":"goatman_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"goatman_boss_area"}
```

### 114. god_boss_map_area

- Match score: `35`
- `k`: god_boss_map_area
- `n`: god_boss_map_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"god_boss_map_area","n":"god_boss_map_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 115. god_boss_map_area

- Match score: `35`
- `k`: 879
- `n`: god_boss_map_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"879","n":"god_boss_map_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"god_boss_map_area"}
```

### 116. golem_boss_area

- Match score: `35`
- `k`: golem_boss_area
- `n`: golem_boss_area
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"golem_boss_area","n":"golem_boss_area","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 117. golem_boss_area

- Match score: `35`
- `k`: 806
- `n`: golem_boss_area
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"806","n":"golem_boss_area","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"golem_boss_area"}
```

### 118. grants_crit_chance_support

- Match score: `35`
- `k`: grants_crit_chance_support
- `n`: grants_crit_chance_support
- `cat`: repoe_tag_details
- `src`: repoe_poe2/tag_details.json

```json
{"k":"grants_crit_chance_support","n":"grants_crit_chance_support","cat":"repoe_tag_details","src":"repoe_poe2/tag_details.json"}
```

### 119. grants_crit_chance_support

- Match score: `35`
- `k`: 291
- `n`: grants_crit_chance_support
- `cat`: repoe_tags
- `src`: repoe_poe2/tags.json

```json
{"k":"291","n":"grants_crit_chance_support","cat":"repoe_tags","src":"repoe_poe2/tags.json","v":"grants_crit_chance_support"}
```

### 120. Greater Rune of Alacrity

- Match score: `35`
- `k`: Metadata/Items/SoulCores/RuneSpecial3
- `n`: Greater Rune of Alacrity
- `cat`: repoe_base_items
- `src`: repoe_poe2/base_items.json
- `tags`: ["rune","default"]
- `domain`: undefined

```json
{"k":"Metadata/Items/SoulCores/RuneSpecial3","n":"Greater Rune of Alacrity","cat":"repoe_base_items","src":"repoe_poe2/base_items.json","item_class":"SoulCore","tags":["rune","default"],"domain":"undefined"}
```

## Mods and affixes

- Source: `build_knowledge/compact/mod_index.json`
- Matches included: `120`

### 1. GlobalCriticalMultiplierWithNoFrenzyChargesUnique__1

- Match score: `140`
- `k`: GlobalCriticalMultiplierWithNoFrenzyChargesUnique__1
- `n`: GlobalCriticalMultiplierWithNoFrenzyChargesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"global_critical_strike_multiplier_+_while_you_have_no_frenzy_charges","max":50,"min":50}]

```json
{"k":"GlobalCriticalMultiplierWithNoFrenzyChargesUnique__1","n":"GlobalCriticalMultiplierWithNoFrenzyChargesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"global_critical_strike_multiplier_+_while_you_have_no_frenzy_charges","max":50,"min":50}],"domain":"item","gen":"unique","lvl":1}
```

### 2. ReducedExtraDamageFromCritsWithNoPowerChargesUnique__1

- Match score: `140`
- `k`: ReducedExtraDamageFromCritsWithNoPowerChargesUnique__1
- `n`: ReducedExtraDamageFromCritsWithNoPowerChargesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"extra_damage_taken_from_crit_while_no_power_charges_+%","max":-50,"min":-50}]

```json
{"k":"ReducedExtraDamageFromCritsWithNoPowerChargesUnique__1","n":"ReducedExtraDamageFromCritsWithNoPowerChargesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"extra_damage_taken_from_crit_while_no_power_charges_+%","max":-50,"min":-50}],"domain":"item","gen":"unique","lvl":1}
```

### 3. UniqueMutatedVaalCriticalStrikeMultiplierIfConsumedPowerChargeRecently

- Match score: `115`
- `k`: UniqueMutatedVaalCriticalStrikeMultiplierIfConsumedPowerChargeRecently
- `n`: UniqueMutatedVaalCriticalStrikeMultiplierIfConsumedPowerChargeRecently
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_hit_damage_bonus_+%_if_consumed_power_charge_recently","max":60,"min":-60}]

```json
{"k":"UniqueMutatedVaalCriticalStrikeMultiplierIfConsumedPowerChargeRecently","n":"UniqueMutatedVaalCriticalStrikeMultiplierIfConsumedPowerChargeRecently","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_hit_damage_bonus_+%_if_consumed_power_charge_recently","max":60,"min":-60}],"domain":"item","gen":"unique","lvl":1}
```

### 4. AdditionalCriticalStrikeChancePerPowerChargeUnique__1

- Match score: `105`
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

### 5. BodyArmourImplicitReducedCriticalStrikeDamageTaken1

- Match score: `105`
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

### 6. ChargeBonusCriticalStrikeChancePerEnduranceCharge

- Match score: `105`
- `k`: ChargeBonusCriticalStrikeChancePerEnduranceCharge
- `n`: ChargeBonusCriticalStrikeChancePerEnduranceCharge
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strike_chance_+%_per_endurance_charge","max":6,"min":6}]

```json
{"k":"ChargeBonusCriticalStrikeChancePerEnduranceCharge","n":"ChargeBonusCriticalStrikeChancePerEnduranceCharge","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_chance_+%_per_endurance_charge","max":6,"min":6}],"domain":"item","gen":"unique","lvl":1}
```

### 7. ChargeBonusCriticalStrikeChancePerFrenzyCharge

- Match score: `105`
- `k`: ChargeBonusCriticalStrikeChancePerFrenzyCharge
- `n`: ChargeBonusCriticalStrikeChancePerFrenzyCharge
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strike_chance_+%_per_frenzy_charge","max":6,"min":6}]

```json
{"k":"ChargeBonusCriticalStrikeChancePerFrenzyCharge","n":"ChargeBonusCriticalStrikeChancePerFrenzyCharge","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_chance_+%_per_frenzy_charge","max":6,"min":6}],"domain":"item","gen":"unique","lvl":1}
```

### 8. ChargeBonusCriticalStrikeMultiplierPerPowerCharge

- Match score: `105`
- `k`: ChargeBonusCriticalStrikeMultiplierPerPowerCharge
- `n`: ChargeBonusCriticalStrikeMultiplierPerPowerCharge
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strike_multiplier_+_per_power_charge","max":3,"min":3}]

```json
{"k":"ChargeBonusCriticalStrikeMultiplierPerPowerCharge","n":"ChargeBonusCriticalStrikeMultiplierPerPowerCharge","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_multiplier_+_per_power_charge","max":3,"min":3}],"domain":"item","gen":"unique","lvl":1}
```

### 9. ChargeBonusFlaskChargeOnCritFrenzyCharges

- Match score: `105`
- `k`: ChargeBonusFlaskChargeOnCritFrenzyCharges
- `n`: ChargeBonusFlaskChargeOnCritFrenzyCharges
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"gain_flask_charge_on_crit_chance_%_while_at_maximum_frenzy_charges","max":100,"min":100}]

```json
{"k":"ChargeBonusFlaskChargeOnCritFrenzyCharges","n":"ChargeBonusFlaskChargeOnCritFrenzyCharges","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"gain_flask_charge_on_crit_chance_%_while_at_maximum_frenzy_charges","max":100,"min":100}],"domain":"item","gen":"unique","lvl":1}
```

### 10. CriticalMultiplierPerPowerChargeUnique__1

- Match score: `105`
- `k`: CriticalMultiplierPerPowerChargeUnique__1
- `n`: CriticalMultiplierPerPowerChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strike_multiplier_+_per_power_charge","max":10,"min":6}]

```json
{"k":"CriticalMultiplierPerPowerChargeUnique__1","n":"CriticalMultiplierPerPowerChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_multiplier_+_per_power_charge","max":10,"min":6}],"domain":"item","gen":"unique","lvl":1}
```

### 11. CriticalStrikesDealIncreasedLightningDamageUnique__1

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

### 12. CriticalStrikesDealIncreasedLightningDamageUnique__1Royale_

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

### 13. CriticalStrikesDealNoDamageUnique__1

- Match score: `105`
- `k`: CriticalStrikesDealNoDamageUnique__1
- `n`: CriticalStrikesDealNoDamageUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strikes_deal_no_damage","max":1,"min":1}]

```json
{"k":"CriticalStrikesDealNoDamageUnique__1","n":"CriticalStrikesDealNoDamageUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strikes_deal_no_damage","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 14. DamageTakenPerPowerChargeOnCritUnique__1

- Match score: `105`
- `k`: DamageTakenPerPowerChargeOnCritUnique__1
- `n`: DamageTakenPerPowerChargeOnCritUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"dummy_stat_display_nothing","max":12000,"min":12000}]

```json
{"k":"DamageTakenPerPowerChargeOnCritUnique__1","n":"DamageTakenPerPowerChargeOnCritUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"dummy_stat_display_nothing","max":12000,"min":12000}],"domain":"item","gen":"unique","lvl":1}
```

### 15. EssenceReducedCriticalDamageAgainstYou1

- Match score: `105`
- `k`: EssenceReducedCriticalDamageAgainstYou1
- `n`: EssenceReducedCriticalDamageAgainstYou1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"EssenceReducedCriticalDamageAgainstYou1","n":"EssenceReducedCriticalDamageAgainstYou1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":72}
```

### 16. FlaskChargesOnCritUniqueTwoHandAxe8

- Match score: `105`
- `k`: FlaskChargesOnCritUniqueTwoHandAxe8
- `n`: FlaskChargesOnCritUniqueTwoHandAxe8
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"recharge_flasks_on_crit","max":1,"min":1}]

```json
{"k":"FlaskChargesOnCritUniqueTwoHandAxe8","n":"FlaskChargesOnCritUniqueTwoHandAxe8","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"recharge_flasks_on_crit","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 17. GainEnduranceChargeWhenCriticallyHit

- Match score: `105`
- `k`: GainEnduranceChargeWhenCriticallyHit
- `n`: GainEnduranceChargeWhenCriticallyHit
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"add_endurance_charge_on_enemy_critical_strike","max":1,"min":1}]

```json
{"k":"GainEnduranceChargeWhenCriticallyHit","n":"GainEnduranceChargeWhenCriticallyHit","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"add_endurance_charge_on_enemy_critical_strike","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 18. GainFrenzyChargeOnCriticalHit

- Match score: `105`
- `k`: GainFrenzyChargeOnCriticalHit
- `n`: GainFrenzyChargeOnCriticalHit
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"add_frenzy_charge_on_critical_strike","max":1,"min":1}]

```json
{"k":"GainFrenzyChargeOnCriticalHit","n":"GainFrenzyChargeOnCriticalHit","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"add_frenzy_charge_on_critical_strike","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 19. GladiatorBossEliteSharingEnduranceCharges

- Match score: `105`
- `k`: GladiatorBossEliteSharingEnduranceCharges
- `n`: GladiatorBossEliteSharingEnduranceCharges
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"add_endurance_charge_on_skill_hit_%","max":100,"min":100},{"id":"monster_share_charges_with_pack","max":1,"min":1}]

```json
{"k":"GladiatorBossEliteSharingEnduranceCharges","n":"GladiatorBossEliteSharingEnduranceCharges","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"add_endurance_charge_on_skill_hit_%","max":100,"min":100},{"id":"monster_share_charges_with_pack","max":1,"min":1}],"domain":"monster","gen":"unique","lvl":1}
```

### 20. IncreasedDamageAtNoFrenzyChargesUnique__1

- Match score: `105`
- `k`: IncreasedDamageAtNoFrenzyChargesUnique__1
- `n`: IncreasedDamageAtNoFrenzyChargesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"damage_while_no_frenzy_charges_+%","max":80,"min":60}]

```json
{"k":"IncreasedDamageAtNoFrenzyChargesUnique__1","n":"IncreasedDamageAtNoFrenzyChargesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"damage_while_no_frenzy_charges_+%","max":80,"min":60}],"domain":"item","gen":"unique","lvl":1}
```

### 21. MapMonsterCriticalStrikesAndDamageDelve

- Match score: `105`
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

### 22. MapMonsterCriticalStrikesAndDamageDelve2

- Match score: `105`
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

### 23. MapMonsterCriticalStrikesAndDamageDelve3

- Match score: `105`
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

### 24. MapMonsterCriticalStrikesAndDamageDelve4

- Match score: `105`
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

### 25. MapMonsterCriticalStrikesAndDamageDelve5

- Match score: `105`
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

### 26. MapMonsterCriticalStrikesAndDamageLabyrinth1

- Match score: `105`
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

### 27. MapMonsterCriticalStrikesAndDamageLabyrinth2

- Match score: `105`
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

### 28. MapMonsterCriticalStrikesAndDamageLabyrinth3

- Match score: `105`
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

### 29. MapMonsterCriticalStrikesAndDamagePathOfEndurance

- Match score: `105`
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

### 30. MapMonsterCriticalStrikesAndDamageSynthesis2

- Match score: `105`
- `k`: MapMonsterCriticalStrikesAndDamageSynthesis2
- `n`: MapMonsterCriticalStrikesAndDamageSynthesis2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 49
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":151},{"id":"map_monsters_critical_strike_multiplier_+","max":30,"min":26}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageSynthesis2","n":"MapMonsterCriticalStrikesAndDamageSynthesis2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":200,"min":151},{"id":"map_monsters_critical_strike_multiplier_+","max":30,"min":26}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":49}
```

### 31. MapMonsterCriticalStrikesAndDamageSynthesis3

- Match score: `105`
- `k`: MapMonsterCriticalStrikesAndDamageSynthesis3
- `n`: MapMonsterCriticalStrikesAndDamageSynthesis3
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 68
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":250,"min":201},{"id":"map_monsters_critical_strike_multiplier_+","max":35,"min":31}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageSynthesis3","n":"MapMonsterCriticalStrikesAndDamageSynthesis3","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":250,"min":201},{"id":"map_monsters_critical_strike_multiplier_+","max":35,"min":31}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":68}
```

### 32. MapMonsterCriticalStrikesAndDamageSynthesis4

- Match score: `105`
- `k`: MapMonsterCriticalStrikesAndDamageSynthesis4
- `n`: MapMonsterCriticalStrikesAndDamageSynthesis4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 73
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":300,"min":251},{"id":"map_monsters_critical_strike_multiplier_+","max":40,"min":36}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageSynthesis4","n":"MapMonsterCriticalStrikesAndDamageSynthesis4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":300,"min":251},{"id":"map_monsters_critical_strike_multiplier_+","max":40,"min":36}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":73}
```

### 33. MapMonsterCriticalStrikesAndDamageSynthesis5

- Match score: `105`
- `k`: MapMonsterCriticalStrikesAndDamageSynthesis5
- `n`: MapMonsterCriticalStrikesAndDamageSynthesis5
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 79
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":400,"min":301},{"id":"map_monsters_critical_strike_multiplier_+","max":45,"min":41}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageSynthesis5","n":"MapMonsterCriticalStrikesAndDamageSynthesis5","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":400,"min":301},{"id":"map_monsters_critical_strike_multiplier_+","max":45,"min":41}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":79}
```

### 34. MapMonsterCriticalStrikesAndDamageSynthesis_

- Match score: `105`
- `k`: MapMonsterCriticalStrikesAndDamageSynthesis_
- `n`: MapMonsterCriticalStrikesAndDamageSynthesis_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: synthesis_a
- `domain`: synthesis_a
- `stats`: [{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":150,"min":100},{"id":"map_monsters_critical_strike_multiplier_+","max":25,"min":20}]

```json
{"k":"MapMonsterCriticalStrikesAndDamageSynthesis_","n":"MapMonsterCriticalStrikesAndDamageSynthesis_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"map_item_drop_quantity_+%","max":16,"min":16},{"id":"map_item_drop_rarity_+%","max":9,"min":9},{"id":"map_pack_size_+%","max":6,"min":6},{"id":"map_monsters_critical_strike_chance_+%","max":150,"min":100},{"id":"map_monsters_critical_strike_multiplier_+","max":25,"min":20}],"domain":"synthesis_a","gen":"synthesis_a","weights":[{"tag":"default","weight":1}],"lvl":1}
```

### 35. MapMonsterCriticalStrikesAndDamageUnique__1

- Match score: `105`
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

### 36. NonCriticalDamageMultiplierUniqueHelmetInt7

- Match score: `105`
- `k`: NonCriticalDamageMultiplierUniqueHelmetInt7
- `n`: NonCriticalDamageMultiplierUniqueHelmetInt7
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"dummy_stat_display_nothing","max":0,"min":0}]

```json
{"k":"NonCriticalDamageMultiplierUniqueHelmetInt7","n":"NonCriticalDamageMultiplierUniqueHelmetInt7","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"dummy_stat_display_nothing","max":0,"min":0}],"domain":"item","gen":"unique","lvl":1}
```

### 37. NonCriticalStrikesDealNoDamageUnique__1

- Match score: `105`
- `k`: NonCriticalStrikesDealNoDamageUnique__1
- `n`: NonCriticalStrikesDealNoDamageUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"non_critical_strikes_deal_no_damage","max":1,"min":1}]

```json
{"k":"NonCriticalStrikesDealNoDamageUnique__1","n":"NonCriticalStrikesDealNoDamageUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_critical_strikes_deal_no_damage","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 38. NonCriticalStrikesDealNoDamageUnique__2

- Match score: `105`
- `k`: NonCriticalStrikesDealNoDamageUnique__2
- `n`: NonCriticalStrikesDealNoDamageUnique__2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"non_critical_strikes_deal_no_damage","max":1,"min":1}]

```json
{"k":"NonCriticalStrikesDealNoDamageUnique__2","n":"NonCriticalStrikesDealNoDamageUnique__2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_critical_strikes_deal_no_damage","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 39. PassageUniqueUlamanCriticalDamageBonus

- Match score: `105`
- `k`: PassageUniqueUlamanCriticalDamageBonus
- `n`: PassageUniqueUlamanCriticalDamageBonus
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"base_critical_strike_multiplier_+","max":25,"min":15}]

```json
{"k":"PassageUniqueUlamanCriticalDamageBonus","n":"PassageUniqueUlamanCriticalDamageBonus","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_critical_strike_multiplier_+","max":25,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 40. SoulInfluenceReducedCriticalDamageAgainstYou

- Match score: `105`
- `k`: SoulInfluenceReducedCriticalDamageAgainstYou
- `n`: SoulInfluenceReducedCriticalDamageAgainstYou
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"SoulInfluenceReducedCriticalDamageAgainstYou","n":"SoulInfluenceReducedCriticalDamageAgainstYou","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":65}
```

### 41. TakeNoExtraDamageFromCriticalStrikesUnique__1

- Match score: `105`
- `k`: TakeNoExtraDamageFromCriticalStrikesUnique__1
- `n`: TakeNoExtraDamageFromCriticalStrikesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"self_take_no_extra_damage_from_critical_strikes","max":1,"min":1}]

```json
{"k":"TakeNoExtraDamageFromCriticalStrikesUnique__1","n":"TakeNoExtraDamageFromCriticalStrikesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"self_take_no_extra_damage_from_critical_strikes","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 42. UniqueBowDamageFromLifeFlaskCharges1

- Match score: `105`
- `k`: UniqueBowDamageFromLifeFlaskCharges1
- `n`: UniqueBowDamageFromLifeFlaskCharges1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"consume_%_of_maximum_life_flask_charges_on_bow_attack","max":10,"min":10},{"id":"bow_attacks_deal_added_physical_damage_equal_to_x%_of_life_flask_recovery_amount","max":10,"min":5}]

```json
{"k":"UniqueBowDamageFromLifeFlaskCharges1","n":"UniqueBowDamageFromLifeFlaskCharges1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"consume_%_of_maximum_life_flask_charges_on_bow_attack","max":10,"min":10},{"id":"bow_attacks_deal_added_physical_damage_equal_to_x%_of_life_flask_recovery_amount","max":10,"min":5}],"domain":"item","gen":"unique","lvl":1}
```

### 43. UniqueCriticalDamageBonusWhileShocked1

- Match score: `105`
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

### 44. UniqueCriticalMultiplierPerPowerCharge1

- Match score: `105`
- `k`: UniqueCriticalMultiplierPerPowerCharge1
- `n`: UniqueCriticalMultiplierPerPowerCharge1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"critical_strike_multiplier_+_per_power_charge","max":12,"min":12}]

```json
{"k":"UniqueCriticalMultiplierPerPowerCharge1","n":"UniqueCriticalMultiplierPerPowerCharge1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"critical_strike_multiplier_+_per_power_charge","max":12,"min":12}],"domain":"item","gen":"unique","lvl":1}
```

### 45. UniqueMutatedVaalCastSpeedIfCriticalStrikeDealtRecently

- Match score: `105`
- `k`: UniqueMutatedVaalCastSpeedIfCriticalStrikeDealtRecently
- `n`: UniqueMutatedVaalCastSpeedIfCriticalStrikeDealtRecently
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"cast_speed_+%_if_have_crit_recently","max":15,"min":-15}]

```json
{"k":"UniqueMutatedVaalCastSpeedIfCriticalStrikeDealtRecently","n":"UniqueMutatedVaalCastSpeedIfCriticalStrikeDealtRecently","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"cast_speed_+%_if_have_crit_recently","max":15,"min":-15}],"domain":"item","gen":"unique","lvl":1}
```

### 46. UniqueReducedCriticalDamageTakenWhileChilled1

- Match score: `105`
- `k`: UniqueReducedCriticalDamageTakenWhileChilled1
- `n`: UniqueReducedCriticalDamageTakenWhileChilled1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"enemy_hit_critical_strike_chance_+%_against_self_while_chilled","max":-35,"min":-50}]

```json
{"k":"UniqueReducedCriticalDamageTakenWhileChilled1","n":"UniqueReducedCriticalDamageTakenWhileChilled1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"enemy_hit_critical_strike_chance_+%_against_self_while_chilled","max":-35,"min":-50}],"domain":"item","gen":"unique","lvl":1}
```

### 47. UniqueTakeNoExtraDamageFromCriticalStrikes1

- Match score: `105`
- `k`: UniqueTakeNoExtraDamageFromCriticalStrikes1
- `n`: UniqueTakeNoExtraDamageFromCriticalStrikes1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"self_take_no_extra_damage_from_critical_strikes","max":1,"min":1}]

```json
{"k":"UniqueTakeNoExtraDamageFromCriticalStrikes1","n":"UniqueTakeNoExtraDamageFromCriticalStrikes1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"self_take_no_extra_damage_from_critical_strikes","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 48. BossMinionFlaskChargeIncrease100

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease100
- `n`: BossMinionFlaskChargeIncrease100
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":100,"min":100}]

```json
{"k":"BossMinionFlaskChargeIncrease100","n":"BossMinionFlaskChargeIncrease100","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":100,"min":100}],"domain":"monster","gen":"unique","lvl":1}
```

### 49. BossMinionFlaskChargeIncrease150

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease150
- `n`: BossMinionFlaskChargeIncrease150
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":150,"min":150}]

```json
{"k":"BossMinionFlaskChargeIncrease150","n":"BossMinionFlaskChargeIncrease150","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":150,"min":150}],"domain":"monster","gen":"unique","lvl":1}
```

### 50. BossMinionFlaskChargeIncrease200

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease200
- `n`: BossMinionFlaskChargeIncrease200
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":200,"min":200}]

```json
{"k":"BossMinionFlaskChargeIncrease200","n":"BossMinionFlaskChargeIncrease200","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":200,"min":200}],"domain":"monster","gen":"unique","lvl":1}
```

### 51. BossMinionFlaskChargeIncrease250

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease250
- `n`: BossMinionFlaskChargeIncrease250
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":250,"min":250}]

```json
{"k":"BossMinionFlaskChargeIncrease250","n":"BossMinionFlaskChargeIncrease250","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":250,"min":250}],"domain":"monster","gen":"unique","lvl":1}
```

### 52. BossMinionFlaskChargeIncrease300

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease300
- `n`: BossMinionFlaskChargeIncrease300
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":300,"min":300}]

```json
{"k":"BossMinionFlaskChargeIncrease300","n":"BossMinionFlaskChargeIncrease300","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":300,"min":300}],"domain":"monster","gen":"unique","lvl":1}
```

### 53. BossMinionFlaskChargeIncrease350

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease350
- `n`: BossMinionFlaskChargeIncrease350
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":350,"min":350}]

```json
{"k":"BossMinionFlaskChargeIncrease350","n":"BossMinionFlaskChargeIncrease350","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":350,"min":350}],"domain":"monster","gen":"unique","lvl":1}
```

### 54. BossMinionFlaskChargeIncrease400

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease400
- `n`: BossMinionFlaskChargeIncrease400
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":400,"min":400}]

```json
{"k":"BossMinionFlaskChargeIncrease400","n":"BossMinionFlaskChargeIncrease400","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":400,"min":400}],"domain":"monster","gen":"unique","lvl":1}
```

### 55. BossMinionFlaskChargeIncrease50

- Match score: `80`
- `k`: BossMinionFlaskChargeIncrease50
- `n`: BossMinionFlaskChargeIncrease50
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"monster_slain_flask_charges_granted_+%","max":50,"min":50}]

```json
{"k":"BossMinionFlaskChargeIncrease50","n":"BossMinionFlaskChargeIncrease50","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"monster_slain_flask_charges_granted_+%","max":50,"min":50}],"domain":"monster","gen":"unique","lvl":1}
```

### 56. ChargeBonusPowerChargeOnCrit

- Match score: `80`
- `k`: ChargeBonusPowerChargeOnCrit
- `n`: ChargeBonusPowerChargeOnCrit
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"add_power_charge_on_critical_strike_%","max":20,"min":20}]

```json
{"k":"ChargeBonusPowerChargeOnCrit","n":"ChargeBonusPowerChargeOnCrit","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"add_power_charge_on_critical_strike_%","max":20,"min":20}],"domain":"item","gen":"unique","lvl":1}
```

### 57. HandWrapsUniqueImpaleOnCriticalHit1

- Match score: `80`
- `k`: HandWrapsUniqueImpaleOnCriticalHit1
- `n`: HandWrapsUniqueImpaleOnCriticalHit1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"deal_thorns_damage_on_melee_crit","max":1,"min":1}]

```json
{"k":"HandWrapsUniqueImpaleOnCriticalHit1","n":"HandWrapsUniqueImpaleOnCriticalHit1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"deal_thorns_damage_on_melee_crit","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 58. HandWrapsUniqueMutatedVaalPoisonDurationIfConsumedFrenzyChargeRecently

- Match score: `80`
- `k`: HandWrapsUniqueMutatedVaalPoisonDurationIfConsumedFrenzyChargeRecently
- `n`: HandWrapsUniqueMutatedVaalPoisonDurationIfConsumedFrenzyChargeRecently
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: suffix
- `domain`: item
- `stats`: [{"id":"damage_+%_per_poison_up_to_75%","max":35,"min":20},{"id":"poison_reflected_to_self","max":1,"min":1}]

```json
{"k":"HandWrapsUniqueMutatedVaalPoisonDurationIfConsumedFrenzyChargeRecently","n":"HandWrapsUniqueMutatedVaalPoisonDurationIfConsumedFrenzyChargeRecently","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"damage_+%_per_poison_up_to_75%","max":35,"min":20},{"id":"poison_reflected_to_self","max":1,"min":1}],"domain":"item","gen":"suffix","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 59. HarvestAlternateWeaponQualityLocalCriticalStrikeChance__

- Match score: `80`
- `k`: HarvestAlternateWeaponQualityLocalCriticalStrikeChance__
- `n`: HarvestAlternateWeaponQualityLocalCriticalStrikeChance__
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_quality_does_not_increase_damage","max":1,"min":1},{"id":"local_critical_strike_chance_+%_per_4%_quality","max":1,"min":1}]

```json
{"k":"HarvestAlternateWeaponQualityLocalCriticalStrikeChance__","n":"HarvestAlternateWeaponQualityLocalCriticalStrikeChance__","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_quality_does_not_increase_damage","max":1,"min":1},{"id":"local_critical_strike_chance_+%_per_4%_quality","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 60. PhysAddedAsChaosWithMaxPowerChargesUnique__1

- Match score: `80`
- `k`: PhysAddedAsChaosWithMaxPowerChargesUnique__1
- `n`: PhysAddedAsChaosWithMaxPowerChargesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"non_skill_base_physical_damage_%_to_gain_as_chaos_while_at_maximum_power_charges","max":12,"min":8}]

```json
{"k":"PhysAddedAsChaosWithMaxPowerChargesUnique__1","n":"PhysAddedAsChaosWithMaxPowerChargesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"non_skill_base_physical_damage_%_to_gain_as_chaos_while_at_maximum_power_charges","max":12,"min":8}],"domain":"item","gen":"unique","lvl":1}
```

### 61. TamedMonsterCritDamage

- Match score: `80`
- `k`: TamedMonsterCritDamage
- `n`: TamedMonsterCritDamage
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: monster
- `stats`: [{"id":"base_critical_strike_multiplier_+","max":150,"min":150}]

```json
{"k":"TamedMonsterCritDamage","n":"TamedMonsterCritDamage","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"base_critical_strike_multiplier_+","max":150,"min":150}],"domain":"monster","gen":"unique","weights":[{"tag":"default","weight":0}],"lvl":1}
```

### 62. UltimatumUniqueMapExtraCriticalRolls

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

### 63. UltimatumUniqueMapLoseCharges

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

### 64. UniqueChanceForSpellCriticalHitsToBeLucky1

- Match score: `80`
- `k`: UniqueChanceForSpellCriticalHitsToBeLucky1
- `n`: UniqueChanceForSpellCriticalHitsToBeLucky1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"spell_critical_hit_chance_%_for_lucky_damage","max":30,"min":15}]

```json
{"k":"UniqueChanceForSpellCriticalHitsToBeLucky1","n":"UniqueChanceForSpellCriticalHitsToBeLucky1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"spell_critical_hit_chance_%_for_lucky_damage","max":30,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 65. UniquePowerChargeOnCritChance1

- Match score: `80`
- `k`: UniquePowerChargeOnCritChance1
- `n`: UniquePowerChargeOnCritChance1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"add_power_charge_on_critical_strike_%","max":25,"min":25}]

```json
{"k":"UniquePowerChargeOnCritChance1","n":"UniquePowerChargeOnCritChance1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"add_power_charge_on_critical_strike_%","max":25,"min":25}],"domain":"item","gen":"unique","lvl":1}
```

### 66. UniqueReducedExtraDamageFromCritsPerSocketable1

- Match score: `80`
- `k`: UniqueReducedExtraDamageFromCritsPerSocketable1
- `n`: UniqueReducedExtraDamageFromCritsPerSocketable1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"local_base_self_critical_strike_multiplier_-%_per_rune_or_soul_core","max":20,"min":15}]

```json
{"k":"UniqueReducedExtraDamageFromCritsPerSocketable1","n":"UniqueReducedExtraDamageFromCritsPerSocketable1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"local_base_self_critical_strike_multiplier_-%_per_rune_or_soul_core","max":20,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 67. AccuracyRatingWithMaxFrenzyChargesUnique__1

- Match score: `70`
- `k`: AccuracyRatingWithMaxFrenzyChargesUnique__1
- `n`: AccuracyRatingWithMaxFrenzyChargesUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"accuracy_rating_while_at_maximum_frenzy_charges","max":500,"min":400}]

```json
{"k":"AccuracyRatingWithMaxFrenzyChargesUnique__1","n":"AccuracyRatingWithMaxFrenzyChargesUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"accuracy_rating_while_at_maximum_frenzy_charges","max":500,"min":400}],"domain":"item","gen":"unique","lvl":1}
```

### 68. AddedColdDamagePerFrenzyChargeEssence1

- Match score: `70`
- `k`: AddedColdDamagePerFrenzyChargeEssence1
- `n`: AddedColdDamagePerFrenzyChargeEssence1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AddedColdDamagePerFrenzyChargeEssence1","n":"AddedColdDamagePerFrenzyChargeEssence1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":63}
```

### 69. AddedColdDamagePerFrenzyChargeEssenceQuiver1

- Match score: `70`
- `k`: AddedColdDamagePerFrenzyChargeEssenceQuiver1
- `n`: AddedColdDamagePerFrenzyChargeEssenceQuiver1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AddedColdDamagePerFrenzyChargeEssenceQuiver1","n":"AddedColdDamagePerFrenzyChargeEssenceQuiver1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":63}
```

### 70. AddedColdDamagePerFrenzyChargeUnique__1

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

### 71. AddedColdDamagePerPowerChargeUnique__1

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

### 72. AddedColdDamagePerPowerChargeUnique__2

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

### 73. AddedLightningDamagePerPowerChargeUnique__1

- Match score: `70`
- `k`: AddedLightningDamagePerPowerChargeUnique__1
- `n`: AddedLightningDamagePerPowerChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"minimum_added_lightning_damage_to_spells_per_power_charge","max":3,"min":3},{"id":"maximum_added_lightning_damage_to_spells_per_power_charge","max":9,"min":9}]

```json
{"k":"AddedLightningDamagePerPowerChargeUnique__1","n":"AddedLightningDamagePerPowerChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"minimum_added_lightning_damage_to_spells_per_power_charge","max":3,"min":3},{"id":"maximum_added_lightning_damage_to_spells_per_power_charge","max":9,"min":9}],"domain":"item","gen":"unique","lvl":1}
```

### 74. AddedPhysicalDamagePerEnduranceChargeUnique__1

- Match score: `70`
- `k`: AddedPhysicalDamagePerEnduranceChargeUnique__1
- `n`: AddedPhysicalDamagePerEnduranceChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"minimum_added_physical_damage_per_endurance_charge","max":5,"min":5},{"id":"maximum_added_physical_damage_per_endurance_charge","max":8,"min":8}]

```json
{"k":"AddedPhysicalDamagePerEnduranceChargeUnique__1","n":"AddedPhysicalDamagePerEnduranceChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"minimum_added_physical_damage_per_endurance_charge","max":5,"min":5},{"id":"maximum_added_physical_damage_per_endurance_charge","max":8,"min":8}],"domain":"item","gen":"unique","lvl":1}
```

### 75. AdditionalChainWhileAtMaxFrenzyChargesUnique___1

- Match score: `70`
- `k`: AdditionalChainWhileAtMaxFrenzyChargesUnique___1
- `n`: AdditionalChainWhileAtMaxFrenzyChargesUnique___1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"num_of_additional_chains_at_max_frenzy_charges","max":1,"min":1}]

```json
{"k":"AdditionalChainWhileAtMaxFrenzyChargesUnique___1","n":"AdditionalChainWhileAtMaxFrenzyChargesUnique___1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"num_of_additional_chains_at_max_frenzy_charges","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 76. AdditionalPhysicalDamageReductionPerSiphoningChargeUnique__1

- Match score: `70`
- `k`: AdditionalPhysicalDamageReductionPerSiphoningChargeUnique__1
- `n`: AdditionalPhysicalDamageReductionPerSiphoningChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"dummy_stat_display_nothing","max":1,"min":1}]

```json
{"k":"AdditionalPhysicalDamageReductionPerSiphoningChargeUnique__1","n":"AdditionalPhysicalDamageReductionPerSiphoningChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"dummy_stat_display_nothing","max":1,"min":1}],"domain":"item","gen":"unique","lvl":1}
```

### 77. AlloyCastSpeedDamageAsExtraColdHybrid1

- Match score: `70`
- `k`: AlloyCastSpeedDamageAsExtraColdHybrid1
- `n`: AlloyCastSpeedDamageAsExtraColdHybrid1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AlloyCastSpeedDamageAsExtraColdHybrid1","n":"AlloyCastSpeedDamageAsExtraColdHybrid1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":65}
```

### 78. AlloyFlaskChargesPerSecond1

- Match score: `70`
- `k`: AlloyFlaskChargesPerSecond1
- `n`: AlloyFlaskChargesPerSecond1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AlloyFlaskChargesPerSecond1","n":"AlloyFlaskChargesPerSecond1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":45}
```

### 79. AttackAndCastSpeedPerFrenzyChargeUniqueBootsDex4

- Match score: `70`
- `k`: AttackAndCastSpeedPerFrenzyChargeUniqueBootsDex4
- `n`: AttackAndCastSpeedPerFrenzyChargeUniqueBootsDex4
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"attack_and_cast_speed_+%_per_frenzy_charge","max":-4,"min":-4}]

```json
{"k":"AttackAndCastSpeedPerFrenzyChargeUniqueBootsDex4","n":"AttackAndCastSpeedPerFrenzyChargeUniqueBootsDex4","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"attack_and_cast_speed_+%_per_frenzy_charge","max":-4,"min":-4}],"domain":"item","gen":"unique","lvl":1}
```

### 80. AttackCriticalStrikeChance1

- Match score: `70`
- `k`: AttackCriticalStrikeChance1
- `n`: AttackCriticalStrikeChance1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance1","n":"AttackCriticalStrikeChance1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":5}
```

### 81. AttackCriticalStrikeChance2

- Match score: `70`
- `k`: AttackCriticalStrikeChance2
- `n`: AttackCriticalStrikeChance2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance2","n":"AttackCriticalStrikeChance2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":20}
```

### 82. AttackCriticalStrikeChance3

- Match score: `70`
- `k`: AttackCriticalStrikeChance3
- `n`: AttackCriticalStrikeChance3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance3","n":"AttackCriticalStrikeChance3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":30}
```

### 83. AttackCriticalStrikeChance4

- Match score: `70`
- `k`: AttackCriticalStrikeChance4
- `n`: AttackCriticalStrikeChance4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance4","n":"AttackCriticalStrikeChance4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":44}
```

### 84. AttackCriticalStrikeChance5

- Match score: `70`
- `k`: AttackCriticalStrikeChance5
- `n`: AttackCriticalStrikeChance5
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance5","n":"AttackCriticalStrikeChance5","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":58}
```

### 85. AttackCriticalStrikeChance6

- Match score: `70`
- `k`: AttackCriticalStrikeChance6
- `n`: AttackCriticalStrikeChance6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeChance6","n":"AttackCriticalStrikeChance6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":72}
```

### 86. AttackCriticalStrikeMultiplier1

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier1
- `n`: AttackCriticalStrikeMultiplier1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier1","n":"AttackCriticalStrikeMultiplier1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":8}
```

### 87. AttackCriticalStrikeMultiplier2

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier2
- `n`: AttackCriticalStrikeMultiplier2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier2","n":"AttackCriticalStrikeMultiplier2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":21}
```

### 88. AttackCriticalStrikeMultiplier3

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier3
- `n`: AttackCriticalStrikeMultiplier3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier3","n":"AttackCriticalStrikeMultiplier3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":31}
```

### 89. AttackCriticalStrikeMultiplier4

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier4
- `n`: AttackCriticalStrikeMultiplier4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier4","n":"AttackCriticalStrikeMultiplier4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":45}
```

### 90. AttackCriticalStrikeMultiplier5

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier5
- `n`: AttackCriticalStrikeMultiplier5
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier5","n":"AttackCriticalStrikeMultiplier5","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":59}
```

### 91. AttackCriticalStrikeMultiplier6

- Match score: `70`
- `k`: AttackCriticalStrikeMultiplier6
- `n`: AttackCriticalStrikeMultiplier6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"AttackCriticalStrikeMultiplier6","n":"AttackCriticalStrikeMultiplier6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":74}
```

### 92. AttackDamageLeechPerFrenzyChargeUnique__1

- Match score: `70`
- `k`: AttackDamageLeechPerFrenzyChargeUnique__1
- `n`: AttackDamageLeechPerFrenzyChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"dummy_stat_display_nothing","max":50,"min":50}]

```json
{"k":"AttackDamageLeechPerFrenzyChargeUnique__1","n":"AttackDamageLeechPerFrenzyChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"dummy_stat_display_nothing","max":50,"min":50}],"domain":"item","gen":"unique","lvl":1}
```

### 93. AvoidElementalDamagePerFrenzyChargeUnique__1

- Match score: `70`
- `k`: AvoidElementalDamagePerFrenzyChargeUnique__1
- `n`: AvoidElementalDamagePerFrenzyChargeUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"avoid_elemental_damage_%_per_frenzy_charge","max":2,"min":2}]

```json
{"k":"AvoidElementalDamagePerFrenzyChargeUnique__1","n":"AvoidElementalDamagePerFrenzyChargeUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"avoid_elemental_damage_%_per_frenzy_charge","max":2,"min":2}],"domain":"item","gen":"unique","lvl":1}
```

### 94. BaseUnarmedCriticalStrikeChanceUnique__1

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

### 95. BaseUnarmedCriticalStrikeChanceUnique__2

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

### 96. BeltImplicitIncreasedCharmChargesGained1

- Match score: `70`
- `k`: BeltImplicitIncreasedCharmChargesGained1
- `n`: BeltImplicitIncreasedCharmChargesGained1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 55
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"charm_charges_gained_+%","max":30,"min":20}]

```json
{"k":"BeltImplicitIncreasedCharmChargesGained1","n":"BeltImplicitIncreasedCharmChargesGained1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"charm_charges_gained_+%","max":30,"min":20}],"domain":"item","gen":"unique","lvl":55}
```

### 97. BeltImplicitIncreasedFlaskChargesGained1

- Match score: `70`
- `k`: BeltImplicitIncreasedFlaskChargesGained1
- `n`: BeltImplicitIncreasedFlaskChargesGained1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 18
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"flask_charges_gained_+%","max":30,"min":20}]

```json
{"k":"BeltImplicitIncreasedFlaskChargesGained1","n":"BeltImplicitIncreasedFlaskChargesGained1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"flask_charges_gained_+%","max":30,"min":20}],"domain":"item","gen":"unique","lvl":18}
```

### 98. BeltImplicitReducedCharmChargesUsed1

- Match score: `70`
- `k`: BeltImplicitReducedCharmChargesUsed1
- `n`: BeltImplicitReducedCharmChargesUsed1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 39
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"charm_charges_used_+%","max":-10,"min":-15}]

```json
{"k":"BeltImplicitReducedCharmChargesUsed1","n":"BeltImplicitReducedCharmChargesUsed1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"charm_charges_used_+%","max":-10,"min":-15}],"domain":"item","gen":"unique","lvl":39}
```

### 99. BeltImplicitReducedFlaskChargesUsed1

- Match score: `70`
- `k`: BeltImplicitReducedFlaskChargesUsed1
- `n`: BeltImplicitReducedFlaskChargesUsed1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 50
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"flask_charges_used_+%","max":-10,"min":-15}]

```json
{"k":"BeltImplicitReducedFlaskChargesUsed1","n":"BeltImplicitReducedFlaskChargesUsed1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"flask_charges_used_+%","max":-10,"min":-15}],"domain":"item","gen":"unique","lvl":50}
```

### 100. BeltIncreasedCharmChargesGained1

- Match score: `70`
- `k`: BeltIncreasedCharmChargesGained1
- `n`: BeltIncreasedCharmChargesGained1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedCharmChargesGained1","n":"BeltIncreasedCharmChargesGained1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":2}
```

### 101. BeltIncreasedCharmChargesGained2

- Match score: `70`
- `k`: BeltIncreasedCharmChargesGained2
- `n`: BeltIncreasedCharmChargesGained2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedCharmChargesGained2","n":"BeltIncreasedCharmChargesGained2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":16}
```

### 102. BeltIncreasedCharmChargesGained3

- Match score: `70`
- `k`: BeltIncreasedCharmChargesGained3
- `n`: BeltIncreasedCharmChargesGained3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedCharmChargesGained3","n":"BeltIncreasedCharmChargesGained3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":32}
```

### 103. BeltIncreasedCharmChargesGained4

- Match score: `70`
- `k`: BeltIncreasedCharmChargesGained4
- `n`: BeltIncreasedCharmChargesGained4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedCharmChargesGained4","n":"BeltIncreasedCharmChargesGained4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":48}
```

### 104. BeltIncreasedCharmChargesGained5

- Match score: `70`
- `k`: BeltIncreasedCharmChargesGained5
- `n`: BeltIncreasedCharmChargesGained5
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedCharmChargesGained5","n":"BeltIncreasedCharmChargesGained5","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":70}
```

### 105. BeltIncreasedCharmChargesGained6

- Match score: `70`
- `k`: BeltIncreasedCharmChargesGained6
- `n`: BeltIncreasedCharmChargesGained6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedCharmChargesGained6","n":"BeltIncreasedCharmChargesGained6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":81}
```

### 106. BeltIncreasedFlaskChargesGained1

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGained1
- `n`: BeltIncreasedFlaskChargesGained1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedFlaskChargesGained1","n":"BeltIncreasedFlaskChargesGained1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":2}
```

### 107. BeltIncreasedFlaskChargesGained2

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGained2
- `n`: BeltIncreasedFlaskChargesGained2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedFlaskChargesGained2","n":"BeltIncreasedFlaskChargesGained2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":16}
```

### 108. BeltIncreasedFlaskChargesGained3_____

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGained3_____
- `n`: BeltIncreasedFlaskChargesGained3_____
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedFlaskChargesGained3_____","n":"BeltIncreasedFlaskChargesGained3_____","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":32}
```

### 109. BeltIncreasedFlaskChargesGained4

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGained4
- `n`: BeltIncreasedFlaskChargesGained4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedFlaskChargesGained4","n":"BeltIncreasedFlaskChargesGained4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":48}
```

### 110. BeltIncreasedFlaskChargesGained5_

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGained5_
- `n`: BeltIncreasedFlaskChargesGained5_
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedFlaskChargesGained5_","n":"BeltIncreasedFlaskChargesGained5_","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":70}
```

### 111. BeltIncreasedFlaskChargesGained6

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGained6
- `n`: BeltIncreasedFlaskChargesGained6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltIncreasedFlaskChargesGained6","n":"BeltIncreasedFlaskChargesGained6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":81}
```

### 112. BeltIncreasedFlaskChargesGainedUnique__1_

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGainedUnique__1_
- `n`: BeltIncreasedFlaskChargesGainedUnique__1_
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"flask_charges_gained_+%","max":25,"min":15}]

```json
{"k":"BeltIncreasedFlaskChargesGainedUnique__1_","n":"BeltIncreasedFlaskChargesGainedUnique__1_","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"flask_charges_gained_+%","max":25,"min":15}],"domain":"item","gen":"unique","lvl":1}
```

### 113. BeltIncreasedFlaskChargesGainedUniqueBelt2

- Match score: `70`
- `k`: BeltIncreasedFlaskChargesGainedUniqueBelt2
- `n`: BeltIncreasedFlaskChargesGainedUniqueBelt2
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"flask_charges_gained_+%","max":50,"min":50}]

```json
{"k":"BeltIncreasedFlaskChargesGainedUniqueBelt2","n":"BeltIncreasedFlaskChargesGainedUniqueBelt2","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"flask_charges_gained_+%","max":50,"min":50}],"domain":"item","gen":"unique","lvl":1}
```

### 114. BeltReducedCharmChargesUsed1

- Match score: `70`
- `k`: BeltReducedCharmChargesUsed1
- `n`: BeltReducedCharmChargesUsed1
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltReducedCharmChargesUsed1","n":"BeltReducedCharmChargesUsed1","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":3}
```

### 115. BeltReducedCharmChargesUsed2

- Match score: `70`
- `k`: BeltReducedCharmChargesUsed2
- `n`: BeltReducedCharmChargesUsed2
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltReducedCharmChargesUsed2","n":"BeltReducedCharmChargesUsed2","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":18}
```

### 116. BeltReducedCharmChargesUsed3

- Match score: `70`
- `k`: BeltReducedCharmChargesUsed3
- `n`: BeltReducedCharmChargesUsed3
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltReducedCharmChargesUsed3","n":"BeltReducedCharmChargesUsed3","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":33}
```

### 117. BeltReducedCharmChargesUsed4

- Match score: `70`
- `k`: BeltReducedCharmChargesUsed4
- `n`: BeltReducedCharmChargesUsed4
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltReducedCharmChargesUsed4","n":"BeltReducedCharmChargesUsed4","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":50}
```

### 118. BeltReducedCharmChargesUsed5

- Match score: `70`
- `k`: BeltReducedCharmChargesUsed5
- `n`: BeltReducedCharmChargesUsed5
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltReducedCharmChargesUsed5","n":"BeltReducedCharmChargesUsed5","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":72}
```

### 119. BeltReducedCharmChargesUsed6

- Match score: `70`
- `k`: BeltReducedCharmChargesUsed6
- `n`: BeltReducedCharmChargesUsed6
- `cat`: pob_mod_item
- `src`: pob_data_poe2/ModItem.json

```json
{"k":"BeltReducedCharmChargesUsed6","n":"BeltReducedCharmChargesUsed6","cat":"pob_mod_item","src":"pob_data_poe2/ModItem.json","level":81}
```

### 120. BeltReducedFlaskChargesGainedUnique__1

- Match score: `70`
- `k`: BeltReducedFlaskChargesGainedUnique__1
- `n`: BeltReducedFlaskChargesGainedUnique__1
- `cat`: repoe_mods
- `src`: repoe_poe2/mods.json
- `lvl`: 1
- `gen`: unique
- `domain`: item
- `stats`: [{"id":"flask_charges_gained_+%","max":-30,"min":-30}]

```json
{"k":"BeltReducedFlaskChargesGainedUnique__1","n":"BeltReducedFlaskChargesGainedUnique__1","cat":"repoe_mods","src":"repoe_poe2/mods.json","stats":[{"id":"flask_charges_gained_+%","max":-30,"min":-30}],"domain":"item","gen":"unique","lvl":1}
```

## Rune mods

- Source: `build_knowledge/compact/rune_mod_index.json`
- Matches included: `1`

### 1. Greater Rune of Alacrity

- Match score: `35`
- `k`: Greater Rune of Alacrity
- `n`: Greater Rune of Alacrity
- `cat`: pob_mod_runes
- `src`: pob_data_poe2/ModRunes.json

```json
{"k":"Greater Rune of Alacrity","n":"Greater Rune of Alacrity","cat":"pob_mod_runes","src":"pob_data_poe2/ModRunes.json"}
```

## Uniques

- Source: `build_knowledge/compact/unique_index.json`
- Matches included: `1`

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

## Misc

- Source: `build_knowledge/compact/misc_index.json`
- Matches included: `120`

### 1. You take {0}% increased Extra Damage from [Critical|Critical Hits] while you have no Power Charges

- Match score: `210`
- `k`: You take {0}% increased Extra Damage from [Critical|Critical Hits] while you have no Power Charges
- `n`: You take {0}% increased Extra Damage from [Critical|Critical Hits] while you have no Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"You take {0}% increased Extra Damage from [Critical|Critical Hits] while you have no Power Charges","n":"You take {0}% increased Extra Damage from [Critical|Critical Hits] while you have no Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 2. You take {0}% reduced Extra Damage from [Critical|Critical Hits] while you have no Power Charges

- Match score: `210`
- `k`: You take {0}% reduced Extra Damage from [Critical|Critical Hits] while you have no Power Charges
- `n`: You take {0}% reduced Extra Damage from [Critical|Critical Hits] while you have no Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"You take {0}% reduced Extra Damage from [Critical|Critical Hits] while you have no Power Charges","n":"You take {0}% reduced Extra Damage from [Critical|Critical Hits] while you have no Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 3. {0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have no Frenzy Charges

- Match score: `210`
- `k`: {0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have no Frenzy Charges
- `n`: {0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have no Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have no Frenzy Charges","n":"{0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have no Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 4. {0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]

- Match score: `210`
- `k`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]
- `n`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]","n":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 5. {0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]

- Match score: `210`
- `k`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]
- `n`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]","n":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 6. {0}% increased [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]

- Match score: `210`
- `k`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]
- `n`: {0}% increased [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]","n":"{0}% increased [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 7. {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]

- Match score: `210`
- `k`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]
- `n`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]","n":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've consumed a [Charges|Power Charge] [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 8. {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]

- Match score: `210`
- `k`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]
- `n`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]","n":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] if you've gained a [Charges|Power Charge] [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 9. {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]

- Match score: `210`
- `k`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]
- `n`: {0}% reduced [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]","n":"{0}% reduced [CriticalDamageBonus|Critical Damage Bonus] per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 10. 3% more [Spell|Spell] Damage per [Charges|Power Charge]
Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]

- Match score: `175`
- `k`: 3% more [Spell|Spell] Damage per [Charges|Power Charge]
Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
- `n`: 3% more [Spell|Spell] Damage per [Charges|Power Charge]
Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"3% more [Spell|Spell] Damage per [Charges|Power Charge]\nGain [Charges|Power Charges] instead of [Charges|Frenzy Charges]","n":"3% more [Spell|Spell] Damage per [Charges|Power Charge]\nGain [Charges|Power Charges] instead of [Charges|Frenzy Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 11. [Attack|Attacks] consume an [Charges|Endurance Charge] to [Critical|Critically Hit]

- Match score: `175`
- `k`: [Attack|Attacks] consume an [Charges|Endurance Charge] to [Critical|Critically Hit]
- `n`: [Attack|Attacks] consume an [Charges|Endurance Charge] to [Critical|Critically Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Attack|Attacks] consume an [Charges|Endurance Charge] to [Critical|Critically Hit]","n":"[Attack|Attacks] consume an [Charges|Endurance Charge] to [Critical|Critically Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 12. [Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have

- Match score: `175`
- `k`: [Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `n`: [Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","n":"[Minion|Minions] have {0}% increased [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 13. [Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have

- Match score: `175`
- `k`: [Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `n`: [Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","n":"[Minion|Minions] have {0}% reduced [Critical|Critical Hit Chance] per Maximum [Charges|Power Charge] you have","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 14. Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
Gain [Charges|Frenzy Charges] instead of [Charges|Endurance Charges]
Gain [Charges|Endurance Charges] instead of [Charges|Power Charges]

- Match score: `175`
- `k`: Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
Gain [Charges|Frenzy Charges] instead of [Charges|Endurance Charges]
Gain [Charges|Endurance Charges] instead of [Charges|Power Charges]
- `n`: Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]
Gain [Charges|Frenzy Charges] instead of [Charges|Endurance Charges]
Gain [Charges|Endurance Charges] instead of [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]\nGain [Charges|Frenzy Charges] instead of [Charges|Endurance Charges]\nGain [Charges|Endurance Charges] instead of [Charges|Power Charges]","n":"Gain [Charges|Power Charges] instead of [Charges|Frenzy Charges]\nGain [Charges|Frenzy Charges] instead of [Charges|Endurance Charges]\nGain [Charges|Endurance Charges] instead of [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 15. Gain a [Charges|Power Charge] on [Critical|Critical Hit]

- Match score: `175`
- `k`: Gain a [Charges|Power Charge] on [Critical|Critical Hit]
- `n`: Gain a [Charges|Power Charge] on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a [Charges|Power Charge] on [Critical|Critical Hit]","n":"Gain a [Charges|Power Charge] on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 16. Gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges

- Match score: `175`
- `k`: Gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges
- `n`: Gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges","n":"Gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 17. Gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]

- Match score: `175`
- `k`: Gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]
- `n`: Gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]","n":"Gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 18. Lose all Power Charges on [Critical|Critical Hit]

- Match score: `175`
- `k`: Lose all Power Charges on [Critical|Critical Hit]
- `n`: Lose all Power Charges on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Lose all Power Charges on [Critical|Critical Hit]","n":"Lose all Power Charges on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 19. Minimum Endurance Charges equal to Maximum while stationary
Minimum Frenzy Charges equal to Maximum while stationary
Minimum Power Charges equal to Maximum while stationary

- Match score: `175`
- `k`: Minimum Endurance Charges equal to Maximum while stationary
Minimum Frenzy Charges equal to Maximum while stationary
Minimum Power Charges equal to Maximum while stationary
- `n`: Minimum Endurance Charges equal to Maximum while stationary
Minimum Frenzy Charges equal to Maximum while stationary
Minimum Power Charges equal to Maximum while stationary
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Minimum Endurance Charges equal to Maximum while stationary\nMinimum Frenzy Charges equal to Maximum while stationary\nMinimum Power Charges equal to Maximum while stationary","n":"Minimum Endurance Charges equal to Maximum while stationary\nMinimum Frenzy Charges equal to Maximum while stationary\nMinimum Power Charges equal to Maximum while stationary","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 20. More [Critical|Critical Hit] chance on [Charges|Power Charge] Consumption@{0}%

- Match score: `175`
- `k`: More [Critical|Critical Hit] chance on [Charges|Power Charge] Consumption@{0}%
- `n`: More [Critical|Critical Hit] chance on [Charges|Power Charge] Consumption@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More [Critical|Critical Hit] chance on [Charges|Power Charge] Consumption@{0}%","n":"More [Critical|Critical Hit] chance on [Charges|Power Charge] Consumption@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 21. More [Critical|Critical Hit] Chance with [Charges|Power Charge]@{0}%

- Match score: `175`
- `k`: More [Critical|Critical Hit] Chance with [Charges|Power Charge]@{0}%
- `n`: More [Critical|Critical Hit] Chance with [Charges|Power Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More [Critical|Critical Hit] Chance with [Charges|Power Charge]@{0}%","n":"More [Critical|Critical Hit] Chance with [Charges|Power Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 22. Supported Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps

- Match score: `175`
- `k`: Supported Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps
- `n`: Supported Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps","n":"Supported Skills have {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 23. Supported Skills will consume a [Charges|Power Charge] on use if possible
Supported Skills have {0}% less chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]

- Match score: `175`
- `k`: Supported Skills will consume a [Charges|Power Charge] on use if possible
Supported Skills have {0}% less chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]
- `n`: Supported Skills will consume a [Charges|Power Charge] on use if possible
Supported Skills have {0}% less chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills will consume a [Charges|Power Charge] on use if possible\nSupported Skills have {0}% less chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]","n":"Supported Skills will consume a [Charges|Power Charge] on use if possible\nSupported Skills have {0}% less chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 24. Supported Skills will consume a [Charges|Power Charge] on use if possible
Supported Skills have {0}% more chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]

- Match score: `175`
- `k`: Supported Skills will consume a [Charges|Power Charge] on use if possible
Supported Skills have {0}% more chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]
- `n`: Supported Skills will consume a [Charges|Power Charge] on use if possible
Supported Skills have {0}% more chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills will consume a [Charges|Power Charge] on use if possible\nSupported Skills have {0}% more chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]","n":"Supported Skills will consume a [Charges|Power Charge] on use if possible\nSupported Skills have {0}% more chance to [Critical|Critically Hit] when consuming [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 25. You take {0}% increased Extra Damage from [Critical|Critical Hits] per Endurance Charge

- Match score: `175`
- `k`: You take {0}% increased Extra Damage from [Critical|Critical Hits] per Endurance Charge
- `n`: You take {0}% increased Extra Damage from [Critical|Critical Hits] per Endurance Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"You take {0}% increased Extra Damage from [Critical|Critical Hits] per Endurance Charge","n":"You take {0}% increased Extra Damage from [Critical|Critical Hits] per Endurance Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 26. You take {0}% reduced Extra Damage from [Critical|Critical Hits] per Endurance Charge

- Match score: `175`
- `k`: You take {0}% reduced Extra Damage from [Critical|Critical Hits] per Endurance Charge
- `n`: You take {0}% reduced Extra Damage from [Critical|Critical Hits] per Endurance Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"You take {0}% reduced Extra Damage from [Critical|Critical Hits] per Endurance Charge","n":"You take {0}% reduced Extra Damage from [Critical|Critical Hits] per Endurance Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 27. {0}% [Critical|Critical Hit] Chance while at maximum Power Charges

- Match score: `175`
- `k`: {0}% [Critical|Critical Hit] Chance while at maximum Power Charges
- `n`: {0}% [Critical|Critical Hit] Chance while at maximum Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% [Critical|Critical Hit] Chance while at maximum Power Charges","n":"{0}% [Critical|Critical Hit] Chance while at maximum Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 28. {0}% chance to gain a [Charges|Power Charge] on [Critical|Critical Hit]

- Match score: `175`
- `k`: {0}% chance to gain a [Charges|Power Charge] on [Critical|Critical Hit]
- `n`: {0}% chance to gain a [Charges|Power Charge] on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% chance to gain a [Charges|Power Charge] on [Critical|Critical Hit]","n":"{0}% chance to gain a [Charges|Power Charge] on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 29. {0}% chance to gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges

- Match score: `175`
- `k`: {0}% chance to gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges
- `n`: {0}% chance to gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% chance to gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges","n":"{0}% chance to gain a [Flask] Charge when you deal a [Critical|Critical Hit] while at maximum Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 30. {0}% Chance to gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]

- Match score: `175`
- `k`: {0}% Chance to gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]
- `n`: {0}% Chance to gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% Chance to gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]","n":"{0}% Chance to gain up to maximum [Charges|Endurance Charges] when you take a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 31. {0}% chance to refresh [Charges|Endurance Charge] Duration when you are [HitDamage|Hit]

- Match score: `175`
- `k`: {0}% chance to refresh [Charges|Endurance Charge] Duration when you are [HitDamage|Hit]
- `n`: {0}% chance to refresh [Charges|Endurance Charge] Duration when you are [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% chance to refresh [Charges|Endurance Charge] Duration when you are [HitDamage|Hit]","n":"{0}% chance to refresh [Charges|Endurance Charge] Duration when you are [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 32. {0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have a Frenzy Charge

- Match score: `175`
- `k`: {0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have a Frenzy Charge
- `n`: {0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have a Frenzy Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have a Frenzy Charge","n":"{0}% Global [CriticalDamageBonus|Critical Damage Bonus] while you have a Frenzy Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 33. {0}% less [Critical|Critical Hit] Chance while
you have a [Charges|Power Charge]

- Match score: `175`
- `k`: {0}% less [Critical|Critical Hit] Chance while
you have a [Charges|Power Charge]
- `n`: {0}% less [Critical|Critical Hit] Chance while
you have a [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% less [Critical|Critical Hit] Chance while\nyou have a [Charges|Power Charge]","n":"{0}% less [Critical|Critical Hit] Chance while\nyou have a [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 34. {0}% more [Critical|Critical Hit] Chance while
you have a [Charges|Power Charge]

- Match score: `175`
- `k`: {0}% more [Critical|Critical Hit] Chance while
you have a [Charges|Power Charge]
- `n`: {0}% more [Critical|Critical Hit] Chance while
you have a [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% more [Critical|Critical Hit] Chance while\nyou have a [Charges|Power Charge]","n":"{0}% more [Critical|Critical Hit] Chance while\nyou have a [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 35. {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps

- Match score: `175`
- `k`: {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps
- `n`: {0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"{0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps","n":"{0}% to [CriticalDamageBonus|Critical Damage Bonus] per Power Charge when used by Traps","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 36. [Buff] duration is {0} seconds per [Charges|Power Charge] Consumed

- Match score: `140`
- `k`: [Buff] duration is {0} seconds per [Charges|Power Charge] Consumed
- `n`: [Buff] duration is {0} seconds per [Charges|Power Charge] Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Buff] duration is {0} seconds per [Charges|Power Charge] Consumed","n":"[Buff] duration is {0} seconds per [Charges|Power Charge] Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 37. [Buff] duration per [Charges|Power Charge]@{0}s

- Match score: `140`
- `k`: [Buff] duration per [Charges|Power Charge]@{0}s
- `n`: [Buff] duration per [Charges|Power Charge]@{0}s
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Buff] duration per [Charges|Power Charge]@{0}s","n":"[Buff] duration per [Charges|Power Charge]@{0}s","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 38. [Flask|Flasks] gain {1} Charges when you take a [Critical|Critical Hit]

- Match score: `140`
- `k`: [Flask|Flasks] gain {1} Charges when you take a [Critical|Critical Hit]
- `n`: [Flask|Flasks] gain {1} Charges when you take a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Flask|Flasks] gain {1} Charges when you take a [Critical|Critical Hit]","n":"[Flask|Flasks] gain {1} Charges when you take a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 39. [Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]

- Match score: `140`
- `k`: [Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]
- `n`: [Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]","n":"[Gain] {0}% of [Physical] Damage as Extra [Chaos] Damage while at maximum [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 40. [Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}

- Match score: `140`
- `k`: [Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}
- `n`: [Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}","n":"[Lightning|Lightning] damage per [Charges|Power Charge]@{0}–{1}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 41. [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage

- Match score: `140`
- `k`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage
- `n`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage","n":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% less Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 42. [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage

- Match score: `140`
- `k`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage
- `n`: [Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage","n":"[Spell|Spells] consume a [Charges|Power Charge] if able to deal {0}% more Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 43. Avoid Elemental Damage from Hits while you have Frenzy Charges

- Match score: `140`
- `k`: Avoid Elemental Damage from Hits while you have Frenzy Charges
- `n`: Avoid Elemental Damage from Hits while you have Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Avoid Elemental Damage from Hits while you have Frenzy Charges","n":"Avoid Elemental Damage from Hits while you have Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 44. Barrage and Frenzy have {0}% increased [Critical|Critical Hit] Chance per Endurance Charge

- Match score: `140`
- `k`: Barrage and Frenzy have {0}% increased [Critical|Critical Hit] Chance per Endurance Charge
- `n`: Barrage and Frenzy have {0}% increased [Critical|Critical Hit] Chance per Endurance Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Barrage and Frenzy have {0}% increased [Critical|Critical Hit] Chance per Endurance Charge","n":"Barrage and Frenzy have {0}% increased [Critical|Critical Hit] Chance per Endurance Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 45. Barrage and Frenzy have {0}% reduced [Critical|Critical Hit] Chance per Endurance Charge

- Match score: `140`
- `k`: Barrage and Frenzy have {0}% reduced [Critical|Critical Hit] Chance per Endurance Charge
- `n`: Barrage and Frenzy have {0}% reduced [Critical|Critical Hit] Chance per Endurance Charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Barrage and Frenzy have {0}% reduced [Critical|Critical Hit] Chance per Endurance Charge","n":"Barrage and Frenzy have {0}% reduced [Critical|Critical Hit] Chance per Endurance Charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 46. Buff duration is {0} seconds per [Charges|Power Charge] Consumed

- Match score: `140`
- `k`: Buff duration is {0} seconds per [Charges|Power Charge] Consumed
- `n`: Buff duration is {0} seconds per [Charges|Power Charge] Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Buff duration is {0} seconds per [Charges|Power Charge] Consumed","n":"Buff duration is {0} seconds per [Charges|Power Charge] Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 47. Buff duration per [Charges|Power Charge]@{0}s

- Match score: `140`
- `k`: Buff duration per [Charges|Power Charge]@{0}s
- `n`: Buff duration per [Charges|Power Charge]@{0}s
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Buff duration per [Charges|Power Charge]@{0}s","n":"Buff duration per [Charges|Power Charge]@{0}s","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 48. Buff grants {0} to {1} Added [Quarterstaff|Quarterstaff] [Attack|Attack] [Lightning|Lightning] damage per [Charges|Power Charge] Consumed, up to your maximum [Charges|Power Charges]

- Match score: `140`
- `k`: Buff grants {0} to {1} Added [Quarterstaff|Quarterstaff] [Attack|Attack] [Lightning|Lightning] damage per [Charges|Power Charge] Consumed, up to your maximum [Charges|Power Charges]
- `n`: Buff grants {0} to {1} Added [Quarterstaff|Quarterstaff] [Attack|Attack] [Lightning|Lightning] damage per [Charges|Power Charge] Consumed, up to your maximum [Charges|Power Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Buff grants {0} to {1} Added [Quarterstaff|Quarterstaff] [Attack|Attack] [Lightning|Lightning] damage per [Charges|Power Charge] Consumed, up to your maximum [Charges|Power Charges]","n":"Buff grants {0} to {1} Added [Quarterstaff|Quarterstaff] [Attack|Attack] [Lightning|Lightning] damage per [Charges|Power Charge] Consumed, up to your maximum [Charges|Power Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 49. Can [Attack] as though using a [Quarterstaff] while both of your hand slots are empty
[UnarmedAttack|Unarmed Attacks] that would use an [Equipped] [Quarterstaff]'s damage have:
• Base [UnarmedDamage|Unarmed] [Physical] damage replaced with damage based on their Skill Level
• 1% more [Attack] Speed per 75 [ItemEvasion|Item Evasion] on [EquipArmour|Equipped Armour Items]
• +0.1% to [Critical|Critical Hit Chance] per 10 [ItemEnergyShield|Item Energy Shield] on [EquipArmour|Equipped Armour Items]

- Match score: `140`
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

### 50. Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges

- Match score: `140`
- `k`: Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges
- `n`: Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area
Cold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area\nCold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges","n":"Cold Snap grants Power Charges instead of Frenzy Charges when Enemies die in its Area\nCold Snap's Cooldown can be bypassed by Power Charges instead of Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 51. Consumes all [Charges|Endurance Charges] to increase [Warcry] duration by {0}% per charge

- Match score: `140`
- `k`: Consumes all [Charges|Endurance Charges] to increase [Warcry] duration by {0}% per charge
- `n`: Consumes all [Charges|Endurance Charges] to increase [Warcry] duration by {0}% per charge
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Consumes all [Charges|Endurance Charges] to increase [Warcry] duration by {0}% per charge","n":"Consumes all [Charges|Endurance Charges] to increase [Warcry] duration by {0}% per charge","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 52. Damage per [Charges|Power Charge] Consumed@{0}

- Match score: `140`
- `k`: Damage per [Charges|Power Charge] Consumed@{0}
- `n`: Damage per [Charges|Power Charge] Consumed@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Damage per [Charges|Power Charge] Consumed@{0}","n":"Damage per [Charges|Power Charge] Consumed@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 53. Deals {0} to {1} base [Lightning|Lightning] Damage per [Charges|Power Charge] removed

- Match score: `140`
- `k`: Deals {0} to {1} base [Lightning|Lightning] Damage per [Charges|Power Charge] removed
- `n`: Deals {0} to {1} base [Lightning|Lightning] Damage per [Charges|Power Charge] removed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Deals {0} to {1} base [Lightning|Lightning] Damage per [Charges|Power Charge] removed","n":"Deals {0} to {1} base [Lightning|Lightning] Damage per [Charges|Power Charge] removed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 54. Deals {0}% more damage when Consuming a [Charges|Frenzy Charge]

- Match score: `140`
- `k`: Deals {0}% more damage when Consuming a [Charges|Frenzy Charge]
- `n`: Deals {0}% more damage when Consuming a [Charges|Frenzy Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Deals {0}% more damage when Consuming a [Charges|Frenzy Charge]","n":"Deals {0}% more damage when Consuming a [Charges|Frenzy Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 55. Duration per [Charges|Endurance Charge] Consumed@{0}

- Match score: `140`
- `k`: Duration per [Charges|Endurance Charge] Consumed@{0}
- `n`: Duration per [Charges|Endurance Charge] Consumed@{0}
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Duration per [Charges|Endurance Charge] Consumed@{0}","n":"Duration per [Charges|Endurance Charge] Consumed@{0}","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 56. Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges

- Match score: `140`
- `k`: Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges
- `n`: Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges","n":"Flicker Strike and Vigilant Strike's Cooldown can be bypassed by Power Charges instead of Frenzy or Endurance Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 57. For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% less cost
•Green: {2}% less Movement Speed Penalty from using Skills while Moving

- Match score: `140`
- `k`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% less cost
•Green: {2}% less Movement Speed Penalty from using Skills while Moving
- `n`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% less cost
•Green: {2}% less Movement Speed Penalty from using Skills while Moving
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% less cost\n•Green: {2}% less Movement Speed Penalty from using Skills while Moving","n":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% less cost\n•Green: {2}% less Movement Speed Penalty from using Skills while Moving","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 58. For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% less cost
•Green: {2}% more Movement Speed Penalty from using Skills while Moving

- Match score: `140`
- `k`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% less cost
•Green: {2}% more Movement Speed Penalty from using Skills while Moving
- `n`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% less cost
•Green: {2}% more Movement Speed Penalty from using Skills while Moving
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% less cost\n•Green: {2}% more Movement Speed Penalty from using Skills while Moving","n":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% less cost\n•Green: {2}% more Movement Speed Penalty from using Skills while Moving","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 59. For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% more cost
•Green: {2}% less Movement Speed Penalty from using Skills while Moving

- Match score: `140`
- `k`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% more cost
•Green: {2}% less Movement Speed Penalty from using Skills while Moving
- `n`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% more cost
•Green: {2}% less Movement Speed Penalty from using Skills while Moving
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% more cost\n•Green: {2}% less Movement Speed Penalty from using Skills while Moving","n":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% more cost\n•Green: {2}% less Movement Speed Penalty from using Skills while Moving","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 60. For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% more cost
•Green: {2}% more Movement Speed Penalty from using Skills while Moving

- Match score: `140`
- `k`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% more cost
•Green: {2}% more Movement Speed Penalty from using Skills while Moving
- `n`: For each colour of Socketed Support Gem that is most numerous, gain:
•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]
•Blue: Skills have {1}% more cost
•Green: {2}% more Movement Speed Penalty from using Skills while Moving
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% more cost\n•Green: {2}% more Movement Speed Penalty from using Skills while Moving","n":"For each colour of Socketed Support Gem that is most numerous, gain:\n•Red: [HitDamage|Hits] against you have no [CriticalDamageBonus|Critical Damage Bonus]\n•Blue: Skills have {1}% more cost\n•Green: {2}% more Movement Speed Penalty from using Skills while Moving","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 61. Gain [ArcaneSurgeDuration|Arcane Surge] on Hit with Spells while at maximum Power Charges

- Match score: `140`
- `k`: Gain [ArcaneSurgeDuration|Arcane Surge] on Hit with Spells while at maximum Power Charges
- `n`: Gain [ArcaneSurgeDuration|Arcane Surge] on Hit with Spells while at maximum Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain [ArcaneSurgeDuration|Arcane Surge] on Hit with Spells while at maximum Power Charges","n":"Gain [ArcaneSurgeDuration|Arcane Surge] on Hit with Spells while at maximum Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 62. Gain a Frenzy Charge for each Enemy you hit with a [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain a Frenzy Charge for each Enemy you hit with a [Critical|Critical Hit]
- `n`: Gain a Frenzy Charge for each Enemy you hit with a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Frenzy Charge for each Enemy you hit with a [Critical|Critical Hit]","n":"Gain a Frenzy Charge for each Enemy you hit with a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 63. Gain a Frenzy Charge on [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain a Frenzy Charge on [Critical|Critical Hit]
- `n`: Gain a Frenzy Charge on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Frenzy Charge on [Critical|Critical Hit]","n":"Gain a Frenzy Charge on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 64. Gain a Frenzy Charge on reaching Maximum Power Charges

- Match score: `140`
- `k`: Gain a Frenzy Charge on reaching Maximum Power Charges
- `n`: Gain a Frenzy Charge on reaching Maximum Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Frenzy Charge on reaching Maximum Power Charges","n":"Gain a Frenzy Charge on reaching Maximum Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 65. Gain a Power Charge for each Enemy you hit with a [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain a Power Charge for each Enemy you hit with a [Critical|Critical Hit]
- `n`: Gain a Power Charge for each Enemy you hit with a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Power Charge for each Enemy you hit with a [Critical|Critical Hit]","n":"Gain a Power Charge for each Enemy you hit with a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 66. Gain a Power Charge on [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain a Power Charge on [Critical|Critical Hit]
- `n`: Gain a Power Charge on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Power Charge on [Critical|Critical Hit]","n":"Gain a Power Charge on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 67. Gain a Power Charge on [Melee] [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain a Power Charge on [Melee] [Critical|Critical Hit]
- `n`: Gain a Power Charge on [Melee] [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Power Charge on [Melee] [Critical|Critical Hit]","n":"Gain a Power Charge on [Melee] [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 68. Gain a Power Charge on Non-[Critical|Critical Hit]

- Match score: `140`
- `k`: Gain a Power Charge on Non-[Critical|Critical Hit]
- `n`: Gain a Power Charge on Non-[Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain a Power Charge on Non-[Critical|Critical Hit]","n":"Gain a Power Charge on Non-[Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 69. Gain an Endurance Charge on [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain an Endurance Charge on [Critical|Critical Hit]
- `n`: Gain an Endurance Charge on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain an Endurance Charge on [Critical|Critical Hit]","n":"Gain an Endurance Charge on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 70. Gain an Endurance Charge on [Melee] [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain an Endurance Charge on [Melee] [Critical|Critical Hit]
- `n`: Gain an Endurance Charge on [Melee] [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain an Endurance Charge on [Melee] [Critical|Critical Hit]","n":"Gain an Endurance Charge on [Melee] [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 71. Gain an Endurance Charge on Bow [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain an Endurance Charge on Bow [Critical|Critical Hit]
- `n`: Gain an Endurance Charge on Bow [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain an Endurance Charge on Bow [Critical|Critical Hit]","n":"Gain an Endurance Charge on Bow [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 72. Gain an Endurance Charge when you take a [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain an Endurance Charge when you take a [Critical|Critical Hit]
- `n`: Gain an Endurance Charge when you take a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain an Endurance Charge when you take a [Critical|Critical Hit]","n":"Gain an Endurance Charge when you take a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 73. Gain an Endurance Charge, Frenzy Charge, and Power Charge when you use a Vaal Skill

- Match score: `140`
- `k`: Gain an Endurance Charge, Frenzy Charge, and Power Charge when you use a Vaal Skill
- `n`: Gain an Endurance Charge, Frenzy Charge, and Power Charge when you use a Vaal Skill
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain an Endurance Charge, Frenzy Charge, and Power Charge when you use a Vaal Skill","n":"Gain an Endurance Charge, Frenzy Charge, and Power Charge when you use a Vaal Skill","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 74. Gain {0} [Flask] Charges when you deal a [Critical|Critical Hit]

- Match score: `140`
- `k`: Gain {0} [Flask] Charges when you deal a [Critical|Critical Hit]
- `n`: Gain {0} [Flask] Charges when you deal a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain {0} [Flask] Charges when you deal a [Critical|Critical Hit]","n":"Gain {0} [Flask] Charges when you deal a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 75. Gain {0}% of [Lightning|Lightning] Damage as [Chaos|Chaos] Damage per [Charges|Power Charge]

- Match score: `140`
- `k`: Gain {0}% of [Lightning|Lightning] Damage as [Chaos|Chaos] Damage per [Charges|Power Charge]
- `n`: Gain {0}% of [Lightning|Lightning] Damage as [Chaos|Chaos] Damage per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain {0}% of [Lightning|Lightning] Damage as [Chaos|Chaos] Damage per [Charges|Power Charge]","n":"Gain {0}% of [Lightning|Lightning] Damage as [Chaos|Chaos] Damage per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 76. Gain {0}% of Damage as Extra [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]

- Match score: `140`
- `k`: Gain {0}% of Damage as Extra [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]
- `n`: Gain {0}% of Damage as Extra [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Gain {0}% of Damage as Extra [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]","n":"Gain {0}% of Damage as Extra [Fire] Damage per [Charges|Endurance Charge] consumed [Recently]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 77. Grant a [Charges|Frenzy Charge] to [Allies] in your [Presence] on [HitDamage|Hit]

- Match score: `140`
- `k`: Grant a [Charges|Frenzy Charge] to [Allies] in your [Presence] on [HitDamage|Hit]
- `n`: Grant a [Charges|Frenzy Charge] to [Allies] in your [Presence] on [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Grant a [Charges|Frenzy Charge] to [Allies] in your [Presence] on [HitDamage|Hit]","n":"Grant a [Charges|Frenzy Charge] to [Allies] in your [Presence] on [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 78. Grant an [Charges|Endurance Charge] to [Allies] in your [Presence] on [HitDamage|Hit]

- Match score: `140`
- `k`: Grant an [Charges|Endurance Charge] to [Allies] in your [Presence] on [HitDamage|Hit]
- `n`: Grant an [Charges|Endurance Charge] to [Allies] in your [Presence] on [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Grant an [Charges|Endurance Charge] to [Allies] in your [Presence] on [HitDamage|Hit]","n":"Grant an [Charges|Endurance Charge] to [Allies] in your [Presence] on [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 79. Grant an [Charges|Power Charge] to [Allies] in your [Presence] on [HitDamage|Hit]

- Match score: `140`
- `k`: Grant an [Charges|Power Charge] to [Allies] in your [Presence] on [HitDamage|Hit]
- `n`: Grant an [Charges|Power Charge] to [Allies] in your [Presence] on [HitDamage|Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Grant an [Charges|Power Charge] to [Allies] in your [Presence] on [HitDamage|Hit]","n":"Grant an [Charges|Power Charge] to [Allies] in your [Presence] on [HitDamage|Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 80. If Diamond [Flask] Charges are consumed, {0}% increased [Critical|Critical Hit] Chance

- Match score: `140`
- `k`: If Diamond [Flask] Charges are consumed, {0}% increased [Critical|Critical Hit] Chance
- `n`: If Diamond [Flask] Charges are consumed, {0}% increased [Critical|Critical Hit] Chance
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"If Diamond [Flask] Charges are consumed, {0}% increased [Critical|Critical Hit] Chance","n":"If Diamond [Flask] Charges are consumed, {0}% increased [Critical|Critical Hit] Chance","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 81. If Diamond [Flask] Charges are consumed, {0}% reduced [Critical|Critical Hit] Chance

- Match score: `140`
- `k`: If Diamond [Flask] Charges are consumed, {0}% reduced [Critical|Critical Hit] Chance
- `n`: If Diamond [Flask] Charges are consumed, {0}% reduced [Critical|Critical Hit] Chance
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"If Diamond [Flask] Charges are consumed, {0}% reduced [Critical|Critical Hit] Chance","n":"If Diamond [Flask] Charges are consumed, {0}% reduced [Critical|Critical Hit] Chance","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 82. If Poisonous Concoction or Explosive Concoction consume Charges from a Sulphur Flask, Enemies Killed by their Hits have {0}% chance to Explode, dealing 10% of their Life as Physical Damage

- Match score: `140`
- `k`: If Poisonous Concoction or Explosive Concoction consume Charges from a Sulphur Flask, Enemies Killed by their Hits have {0}% chance to Explode, dealing 10% of their Life as Physical Damage
- `n`: If Poisonous Concoction or Explosive Concoction consume Charges from a Sulphur Flask, Enemies Killed by their Hits have {0}% chance to Explode, dealing 10% of their Life as Physical Damage
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"If Poisonous Concoction or Explosive Concoction consume Charges from a Sulphur Flask, Enemies Killed by their Hits have {0}% chance to Explode, dealing 10% of their Life as Physical Damage","n":"If Poisonous Concoction or Explosive Concoction consume Charges from a Sulphur Flask, Enemies Killed by their Hits have {0}% chance to Explode, dealing 10% of their Life as Physical Damage","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 83. Immortal Call increases Duration without removing Endurance Charges

- Match score: `140`
- `k`: Immortal Call increases Duration without removing Endurance Charges
- `n`: Immortal Call increases Duration without removing Endurance Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Immortal Call increases Duration without removing Endurance Charges","n":"Immortal Call increases Duration without removing Endurance Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 84. Increased [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%

- Match score: `140`
- `k`: Increased [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%
- `n`: Increased [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Increased [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%","n":"Increased [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 85. Less duration when consuming a [Charges|Power Charge]@{0}%

- Match score: `140`
- `k`: Less duration when consuming a [Charges|Power Charge]@{0}%
- `n`: Less duration when consuming a [Charges|Power Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Less duration when consuming a [Charges|Power Charge]@{0}%","n":"Less duration when consuming a [Charges|Power Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 86. More [ElementalDamage|Elemental Damage] granted per [Charges|Power Charge]@{0}%

- Match score: `140`
- `k`: More [ElementalDamage|Elemental Damage] granted per [Charges|Power Charge]@{0}%
- `n`: More [ElementalDamage|Elemental Damage] granted per [Charges|Power Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More [ElementalDamage|Elemental Damage] granted per [Charges|Power Charge]@{0}%","n":"More [ElementalDamage|Elemental Damage] granted per [Charges|Power Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 87. More [SkillSpeed|Skill Speed] on [Charges|Frenzy Charge] Consumption@{0}%

- Match score: `140`
- `k`: More [SkillSpeed|Skill Speed] on [Charges|Frenzy Charge] Consumption@{0}%
- `n`: More [SkillSpeed|Skill Speed] on [Charges|Frenzy Charge] Consumption@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More [SkillSpeed|Skill Speed] on [Charges|Frenzy Charge] Consumption@{0}%","n":"More [SkillSpeed|Skill Speed] on [Charges|Frenzy Charge] Consumption@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 88. More [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%

- Match score: `140`
- `k`: More [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%
- `n`: More [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%","n":"More [SkillSpeed|Skill Speed] with [Charges|Frenzy Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 89. More Damage if [Charges|Frenzy Charge] Consumed@{0}%

- Match score: `140`
- `k`: More Damage if [Charges|Frenzy Charge] Consumed@{0}%
- `n`: More Damage if [Charges|Frenzy Charge] Consumed@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More Damage if [Charges|Frenzy Charge] Consumed@{0}%","n":"More Damage if [Charges|Frenzy Charge] Consumed@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 90. More Damage if [Charges|Power Charge] Consumed@{0}%

- Match score: `140`
- `k`: More Damage if [Charges|Power Charge] Consumed@{0}%
- `n`: More Damage if [Charges|Power Charge] Consumed@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More Damage if [Charges|Power Charge] Consumed@{0}%","n":"More Damage if [Charges|Power Charge] Consumed@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 91. More Damage per [Charges|Frenzy Charge] Consumed@{0}%

- Match score: `140`
- `k`: More Damage per [Charges|Frenzy Charge] Consumed@{0}%
- `n`: More Damage per [Charges|Frenzy Charge] Consumed@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More Damage per [Charges|Frenzy Charge] Consumed@{0}%","n":"More Damage per [Charges|Frenzy Charge] Consumed@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 92. More Damage per [Charges|Power Charge] Consumed@{0}%

- Match score: `140`
- `k`: More Damage per [Charges|Power Charge] Consumed@{0}%
- `n`: More Damage per [Charges|Power Charge] Consumed@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More Damage per [Charges|Power Charge] Consumed@{0}%","n":"More Damage per [Charges|Power Charge] Consumed@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 93. More damage when Consuming [Charges|Frenzy Charge]@{0}%

- Match score: `140`
- `k`: More damage when Consuming [Charges|Frenzy Charge]@{0}%
- `n`: More damage when Consuming [Charges|Frenzy Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More damage when Consuming [Charges|Frenzy Charge]@{0}%","n":"More damage when Consuming [Charges|Frenzy Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 94. More duration when consuming a [Charges|Power Charge]@{0}%

- Match score: `140`
- `k`: More duration when consuming a [Charges|Power Charge]@{0}%
- `n`: More duration when consuming a [Charges|Power Charge]@{0}%
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"More duration when consuming a [Charges|Power Charge]@{0}%","n":"More duration when consuming a [Charges|Power Charge]@{0}%","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 95. Phase Run increases Duration without removing Frenzy Charges

- Match score: `140`
- `k`: Phase Run increases Duration without removing Frenzy Charges
- `n`: Phase Run increases Duration without removing Frenzy Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Phase Run increases Duration without removing Frenzy Charges","n":"Phase Run increases Duration without removing Frenzy Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 96. Recharges {0} Charge when you deal a [Critical|Critical Hit]

- Match score: `140`
- `k`: Recharges {0} Charge when you deal a [Critical|Critical Hit]
- `n`: Recharges {0} Charge when you deal a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Recharges {0} Charge when you deal a [Critical|Critical Hit]","n":"Recharges {0} Charge when you deal a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 97. Recharges {0} Charge when you take a [Critical|Critical Hit]

- Match score: `140`
- `k`: Recharges {0} Charge when you take a [Critical|Critical Hit]
- `n`: Recharges {0} Charge when you take a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Recharges {0} Charge when you take a [Critical|Critical Hit]","n":"Recharges {0} Charge when you take a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 98. Recharges {0} Charges when you deal a [Critical|Critical Hit]

- Match score: `140`
- `k`: Recharges {0} Charges when you deal a [Critical|Critical Hit]
- `n`: Recharges {0} Charges when you deal a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Recharges {0} Charges when you deal a [Critical|Critical Hit]","n":"Recharges {0} Charges when you deal a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 99. Recharges {0} Charges when you take a [Critical|Critical Hit]

- Match score: `140`
- `k`: Recharges {0} Charges when you take a [Critical|Critical Hit]
- `n`: Recharges {0} Charges when you take a [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Recharges {0} Charges when you take a [Critical|Critical Hit]","n":"Recharges {0} Charges when you take a [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 100. Socketed Gems are Supported by Level {0} Power Charge On Critical

- Match score: `140`
- `k`: Socketed Gems are Supported by Level {0} Power Charge On Critical
- `n`: Socketed Gems are Supported by Level {0} Power Charge On Critical
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Socketed Gems are Supported by Level {0} Power Charge On Critical","n":"Socketed Gems are Supported by Level {0} Power Charge On Critical","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 101. Socketed Skills deal {0}% more
damage per [Charges|Power Charge] Consumed

- Match score: `140`
- `k`: Socketed Skills deal {0}% more
damage per [Charges|Power Charge] Consumed
- `n`: Socketed Skills deal {0}% more
damage per [Charges|Power Charge] Consumed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Socketed Skills deal {0}% more\ndamage per [Charges|Power Charge] Consumed","n":"Socketed Skills deal {0}% more\ndamage per [Charges|Power Charge] Consumed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 102. Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant a [Charges|Frenzy Charge]

- Match score: `140`
- `k`: Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant a [Charges|Frenzy Charge]
- `n`: Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant a [Charges|Frenzy Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant a [Charges|Frenzy Charge]","n":"Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant a [Charges|Frenzy Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 103. Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant {0} [Charges|Frenzy Charges]

- Match score: `140`
- `k`: Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant {0} [Charges|Frenzy Charges]
- `n`: Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant {0} [Charges|Frenzy Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant {0} [Charges|Frenzy Charges]","n":"Supported Skills [Consume] [Parry|Parried] Debuff on [HitDamage|Hit] to grant {0} [Charges|Frenzy Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 104. Supported Skills [Consume] a [Charges|Frenzy Charge] on use to [ArmourBreak|Break Armour] equal to {0}% of [Physical|Physical Damage] dealt

- Match score: `140`
- `k`: Supported Skills [Consume] a [Charges|Frenzy Charge] on use to [ArmourBreak|Break Armour] equal to {0}% of [Physical|Physical Damage] dealt
- `n`: Supported Skills [Consume] a [Charges|Frenzy Charge] on use to [ArmourBreak|Break Armour] equal to {0}% of [Physical|Physical Damage] dealt
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills [Consume] a [Charges|Frenzy Charge] on use to [ArmourBreak|Break Armour] equal to {0}% of [Physical|Physical Damage] dealt","n":"Supported Skills [Consume] a [Charges|Frenzy Charge] on use to [ArmourBreak|Break Armour] equal to {0}% of [Physical|Physical Damage] dealt","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 105. Supported Skills consume a [Charges|Power Charge] on use
Supported Skills have {0}% less duration when consuming a [Charges|Power Charge]

- Match score: `140`
- `k`: Supported Skills consume a [Charges|Power Charge] on use
Supported Skills have {0}% less duration when consuming a [Charges|Power Charge]
- `n`: Supported Skills consume a [Charges|Power Charge] on use
Supported Skills have {0}% less duration when consuming a [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills consume a [Charges|Power Charge] on use\nSupported Skills have {0}% less duration when consuming a [Charges|Power Charge]","n":"Supported Skills consume a [Charges|Power Charge] on use\nSupported Skills have {0}% less duration when consuming a [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 106. Supported Skills consume a [Charges|Power Charge] on use
Supported Skills have {0}% more duration when consuming a [Charges|Power Charge]

- Match score: `140`
- `k`: Supported Skills consume a [Charges|Power Charge] on use
Supported Skills have {0}% more duration when consuming a [Charges|Power Charge]
- `n`: Supported Skills consume a [Charges|Power Charge] on use
Supported Skills have {0}% more duration when consuming a [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills consume a [Charges|Power Charge] on use\nSupported Skills have {0}% more duration when consuming a [Charges|Power Charge]","n":"Supported Skills consume a [Charges|Power Charge] on use\nSupported Skills have {0}% more duration when consuming a [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 107. Supported Skills deal {0}% increased Damage per [Charges|Power Charge]

- Match score: `140`
- `k`: Supported Skills deal {0}% increased Damage per [Charges|Power Charge]
- `n`: Supported Skills deal {0}% increased Damage per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills deal {0}% increased Damage per [Charges|Power Charge]","n":"Supported Skills deal {0}% increased Damage per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 108. Supported Skills deal {0}% less Damage per [Charges|Power Charge]

- Match score: `140`
- `k`: Supported Skills deal {0}% less Damage per [Charges|Power Charge]
- `n`: Supported Skills deal {0}% less Damage per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills deal {0}% less Damage per [Charges|Power Charge]","n":"Supported Skills deal {0}% less Damage per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 109. Supported Skills deal {0}% more Damage per [Charges|Power Charge]

- Match score: `140`
- `k`: Supported Skills deal {0}% more Damage per [Charges|Power Charge]
- `n`: Supported Skills deal {0}% more Damage per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills deal {0}% more Damage per [Charges|Power Charge]","n":"Supported Skills deal {0}% more Damage per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 110. Supported Skills deal {0}% reduced Damage per [Charges|Power Charge]

- Match score: `140`
- `k`: Supported Skills deal {0}% reduced Damage per [Charges|Power Charge]
- `n`: Supported Skills deal {0}% reduced Damage per [Charges|Power Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills deal {0}% reduced Damage per [Charges|Power Charge]","n":"Supported Skills deal {0}% reduced Damage per [Charges|Power Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 111. Supported Skills gain a Power Charge on [Critical|Critical Hit]

- Match score: `140`
- `k`: Supported Skills gain a Power Charge on [Critical|Critical Hit]
- `n`: Supported Skills gain a Power Charge on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills gain a Power Charge on [Critical|Critical Hit]","n":"Supported Skills gain a Power Charge on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 112. Supported Skills have {0}% chance to gain a Power Charge on [Critical|Critical Hit]

- Match score: `140`
- `k`: Supported Skills have {0}% chance to gain a Power Charge on [Critical|Critical Hit]
- `n`: Supported Skills have {0}% chance to gain a Power Charge on [Critical|Critical Hit]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills have {0}% chance to gain a Power Charge on [Critical|Critical Hit]","n":"Supported Skills have {0}% chance to gain a Power Charge on [Critical|Critical Hit]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 113. Supported Skills have {0}% increased [Critical|Critical Hit] Chance per
Power Charge when used by Mines

- Match score: `140`
- `k`: Supported Skills have {0}% increased [Critical|Critical Hit] Chance per
Power Charge when used by Mines
- `n`: Supported Skills have {0}% increased [Critical|Critical Hit] Chance per
Power Charge when used by Mines
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills have {0}% increased [Critical|Critical Hit] Chance per\nPower Charge when used by Mines","n":"Supported Skills have {0}% increased [Critical|Critical Hit] Chance per\nPower Charge when used by Mines","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 114. Supported Skills have {0}% reduced [Critical|Critical Hit] Chance per
Power Charge when used by Mines

- Match score: `140`
- `k`: Supported Skills have {0}% reduced [Critical|Critical Hit] Chance per
Power Charge when used by Mines
- `n`: Supported Skills have {0}% reduced [Critical|Critical Hit] Chance per
Power Charge when used by Mines
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills have {0}% reduced [Critical|Critical Hit] Chance per\nPower Charge when used by Mines","n":"Supported Skills have {0}% reduced [Critical|Critical Hit] Chance per\nPower Charge when used by Mines","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 115. Supported Skills will consume a [Charges|Frenzy Charge] on use if possible
Supported Skills have {0}% less [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]

- Match score: `140`
- `k`: Supported Skills will consume a [Charges|Frenzy Charge] on use if possible
Supported Skills have {0}% less [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]
- `n`: Supported Skills will consume a [Charges|Frenzy Charge] on use if possible
Supported Skills have {0}% less [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills will consume a [Charges|Frenzy Charge] on use if possible\nSupported Skills have {0}% less [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]","n":"Supported Skills will consume a [Charges|Frenzy Charge] on use if possible\nSupported Skills have {0}% less [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 116. Supported Skills will consume a [Charges|Frenzy Charge] on use if possible
Supported Skills have {0}% more [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]

- Match score: `140`
- `k`: Supported Skills will consume a [Charges|Frenzy Charge] on use if possible
Supported Skills have {0}% more [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]
- `n`: Supported Skills will consume a [Charges|Frenzy Charge] on use if possible
Supported Skills have {0}% more [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Supported Skills will consume a [Charges|Frenzy Charge] on use if possible\nSupported Skills have {0}% more [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]","n":"Supported Skills will consume a [Charges|Frenzy Charge] on use if possible\nSupported Skills have {0}% more [SkillSpeed|Skill Speed] when consuming [Charges|Frenzy Charges]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 117. Take {0} [Chaos] damage per second per [Charges|Endurance Charge]

- Match score: `140`
- `k`: Take {0} [Chaos] damage per second per [Charges|Endurance Charge]
- `n`: Take {0} [Chaos] damage per second per [Charges|Endurance Charge]
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Take {0} [Chaos] damage per second per [Charges|Endurance Charge]","n":"Take {0} [Chaos] damage per second per [Charges|Endurance Charge]","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 118. Take {0} Cold Damage on reaching Maximum Power Charges

- Match score: `140`
- `k`: Take {0} Cold Damage on reaching Maximum Power Charges
- `n`: Take {0} Cold Damage on reaching Maximum Power Charges
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Take {0} Cold Damage on reaching Maximum Power Charges","n":"Take {0} Cold Damage on reaching Maximum Power Charges","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 119. Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed

- Match score: `140`
- `k`: Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed
- `n`: Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed","n":"Teleports and [Strike|Strikes] {0} additional time per [Charges|Power Charge], with 285% more [Attack] Speed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
```

### 120. Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed

- Match score: `140`
- `k`: Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed
- `n`: Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed
- `cat`: repoe_stats_by_file
- `src`: repoe_poe2/stats_by_file.json

```json
{"k":"Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed","n":"Teleports and [Strike|Strikes] {0} additional times per [Charges|Power Charge], with 285% more [Attack] Speed","cat":"repoe_stats_by_file","src":"repoe_poe2/stats_by_file.json"}
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
| Uniques | OK | 1 |
| Misc | OK | 120 |
